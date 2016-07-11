RM := rm -f
TIDY := tidy

index.html: index-orig.html fig1.png fig2.png fig3.png $(MAKEFILE_LIST)
	$(TIDY) -o "$@" -indent --tidy-mark n --vertical-space y --hide-comments y -utf8 "$<"

.PHONY: clean
clean:
	$(RM) index.html
