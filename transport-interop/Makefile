GO_SUBDIRS := $(wildcard impl/go/v0.33/.)

all: $(GO_SUBDIRS) $(JS_SUBDIRS) $(RUST_SUBDIRS) $(NIM_SUBDIRS) $(ZIG_SUBDIRS) $(JAVA_SUBDIRS)
$(JS_SUBDIRS):
	$(MAKE) -C $@
$(GO_SUBDIRS):
	$(MAKE) -C $@
$(RUST_SUBDIRS):
	$(MAKE) -C $@
$(NIM_SUBDIRS):
	$(MAKE) -C $@
$(ZIG_SUBDIRS):
	$(MAKE) -C $@
$(JAVA_SUBDIRS):
	$(MAKE) -C $@

.PHONY: $(GO_SUBDIRS) $(JS_SUBDIRS) $(RUST_SUBDIRS) $(NIM_SUBDIRS) $(ZIG_SUBDIRS) $(JAVA_SUBDIRS) all
