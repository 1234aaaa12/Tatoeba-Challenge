#
# remove duplicates and clean some old names from newstest
#

SCOREFILES := $(patsubst %.txt,%.fix,${wildcard */*.scores.txt})
BLEUSCOREFILES := ${SCOREFILES:.scores.fix=.bleu-scores.fix}
CHRFSCOREFILES := ${SCOREFILES:.scores.fix=.chrf-scores.fix}
COMETSCOREFILES := ${SCOREFILES:.scores.fix=.comet-scores.fix}


all: ${SCOREFILES} ${BLEUSCOREFILES} ${CHRFSCOREFILES} ${COMETSCOREFILES}

%.scores.fix: %.scores.txt
	sed -e 's/\(news.*[0-9][0-9][0-9][0-9]\)-[a-z][a-z][a-z][a-z]	/\1	/' $< |  \
	sed -e 's/\(news.*2021\)\.[a-z][a-z]\-[a-z][a-z]	/\1	/' |\
	rev | uniq -f5 | rev | sort -u > $@
	if [ `diff $< $@ | wc -l` -gt 0 ]; then \
	  mv $@ $<; \
	fi
	rm -f $@

%-scores.fix: %-scores.txt
	if [ -e $< ]; then \
	  sed 's/\(news.*[0-9][0-9][0-9][0-9]\)\-[a-z][a-z][a-z][a-z]	/\1	/' $< |\
	  sed -e 's/\(news.*2021\)\.[a-z][a-z]\-[a-z][a-z]	/\1	/' |\
	  rev | uniq -f1 | rev > $@; \
	  if [ `diff $< $@ | wc -l` -gt 0 ]; then \
	    mv $@ $<; \
	  fi; \
	  rm -f $@; \
	fi

%.bleu-scores.txt: %.scores.txt
	cut -f1,2,4 $< | \
	sed 's/\(news.*[0-9][0-9][0-9][0-9]\)\-[a-z][a-z][a-z][a-z]	/\1	/' |\
	sed -e 's/\(news.*2021\)\.[a-z][a-z]\-[a-z][a-z]	/\1	/' |\
	rev | uniq -f1 | rev > $@


%.chrf-scores.txt: %.scores.txt
	cut -f1,2,3 $< |\
	sed 's/\(news.*[0-9][0-9][0-9][0-9]\)\-[a-z][a-z][a-z][a-z]	/\1	/' |\
	sed -e 's/\(news.*2021\)\.[a-z][a-z]\-[a-z][a-z]	/\1	/' |\
	rev | uniq -f1 | rev > $@

## cannot produce comet scores here
%.comet-scores.txt:
	@echo "don't know how to produce comet scores"
