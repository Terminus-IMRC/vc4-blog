RM := rm -f
TIDY := tidy

TIDY_QUIET := y

index.html: index-orig.html $(MAKEFILE_LIST)
	$(TIDY) -o "$@" -indent --tidy-mark n --vertical-space y --hide-comments y --quiet "$(TIDY_QUIET)" -utf8 "$<"

.PHONY: clean
clean:
	$(RM) index.html
