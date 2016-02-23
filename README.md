# Overview

Simple test suite, aim of which is to guarantee that Jackson components that are meant to work on JDK6 runtime
do so. This is becoming an issues with 2.7, where runtime baseline is kept as JDK6 for `jackson-databind`,
but some features of JDK7 are accessible via dynamic reflection.

Going forward this may become even bigger issue, when JDK8 features are to be incorporated.
Further down the road it will stop becoming an issue once we stop supporting JDK6 runtime, but until then
automated testing is necessary.

