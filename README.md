# java-module

My attempt to understand java module feature by making my hands dirty.

javac --module-source-path src -d out $(find . -name '*.java')

java -p out -m parser/learning.ak.parser.CoreParser
