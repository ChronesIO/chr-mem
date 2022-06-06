file(GLOB_RECURSE chr-mem-impl CONFIGURE_DEPENDS "*.cxx")
target_sources(chr-mem PUBLIC ${chr-mem-impl})