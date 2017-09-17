# Change Log

All notable changes will be documented in this file.

## [Unreleased]

### New Features
- An independent module for GZoltar's Agent
- New Agent options:
  - buildlocation -- directory with classes to instrument
  - destfile -- the output file for spectrym data
  - includes -- list of classes, separated by ':', allowed to be instrumented (by default all classes are) (wildcards are allowed)
  - excludes -- list of classes, separated by ':', not allowed to be instrumented (by default no class is excluded) (wildcards are allowed)
  - exclclassloader -- list of Java ClassLoaders not allowed to be instrumented (wildcards are allowed)
  - inclnolocationclasses -- specifies whether also classes without a source location should be instrumented
  - output -- specifies the output mode, valid options are file, console, or none
- Remove FlexJSON dependency

### Non-functional Changes
- Rename all modules to 'com.gzoltar'
- Format all .java files according to google style guide
- Improve build infrastructure
