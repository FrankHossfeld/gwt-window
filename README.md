![GWT3/J2CL compatible](https://img.shields.io/badge/GWT3/J2CL-compatible-brightgreen.svg)

# gwt-window

A future-proof port of the `com.google.user.window.Window` GWT module,
with no dependency on `gwt-user` (besides the Java Runtime Emulation),
to prepare for GWT 3 / J2Cl.

### Dependency

```xml
<dependency>
    <groupId>org.gwtproject.user.window</groupId>
    <artifactId>gwt-window</artifactId>
    <version>1.0-SNAPSHOT</version>
</dependency>
```

### Instructions
To build gwt-window:

* run `mvn clean install`

on the parent directory.

To run the j2cl tests:

* switch to the 'gwt-window-j2cl-tests' directory
* run `mvn j2cl:clean` & `mvn j2cl:test`

