# Stylometry

Stylometric analysis of text to find author word usage statistics, written in Icon.
If no dictionary is provided it will attempt to open the default dictionary provided.
If no file is provided the program will start a prompt and read text from stdin and after pressing [Ctrl-d] the input will be analyzed.

Compile: 
`icont stylometry.icon`

Usage: 
`./stylometry [-d dictionary] [-f file]`
