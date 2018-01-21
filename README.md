# java-module

My attempt to understand java module feature by making my hands dirty.

javac --module-source-path src -d out $(find . -name '*.java')

java -p out -m parser/learning.ak.parser.CoreParser

java --list-modules

module-info.java
exports source_modle_package to target_module_package for exclusive use
