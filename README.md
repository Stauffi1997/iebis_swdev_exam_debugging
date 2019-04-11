Debugging Solutions
==================

1.*replaceAll* method takes a regex as first argument, a simple dot "." is a special character, meaning to tell it it's the actual dot we need "\."
2.The bounderies of the Randomiser need to be set to 3 if we want them to countain 2 as well
3.Stringbuffer doesn't take char '' characters, replace with ""
4.The switch statements need breaks, otherwise they will stay in the condition.
