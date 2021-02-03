Too bypass cache there are 3 steps

1) reverse Fastly MD5 hash
2) recalculate edge server cache algorithm
3) redirect all fastly headers to origin utilizing advanced URL manipulation techniques such as:
"/"
"//"
"///"
"////"
and, posssibly the most advanced, "/////"