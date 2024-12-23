build/make/core/tasks/platform_availability_check.mk:37: warning: --- framework-minus-apex:frameworks/base ----
build/make/core/tasks/platform_availability_check.mk:38: warning:  Following modules are requested to be installed. But are not available for platform because they do not have "//apex_available:platform"
 or they depend on other modules that are not available for platform
Offending entries:
framework-minus-apex:frameworks/base
In file included from build/make/core/main.mk:1458:
In file included from build/make/core/Makefile:6130:
build/make/core/tasks/platform_availability_check.mk:38: error: Build failed.
