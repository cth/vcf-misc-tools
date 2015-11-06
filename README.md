## vcf-misc-tools

This a couple of tools for use with VCF files. These are not really general purpose tools, 
but more specialized tools to itch my own scratches. For a general purpose full-fledged tool suite take a look at 
[vcf-tools](https://github.com/vcftools/vcftools).

* _vcf-from-imputed_: Tool for converting imputed files (mach or impute2) to a VCF file, including conversion between dosages, genotype likehoods and "called" genotypes. 

* _vcf-bsearch_: Tool that does fast extraction of given positions/ranges in a sorted, but not necessarily indexed VCF file using a combination of binary and linear search. The output is another VCF file.

## Licence
Copyright 2015 Christian Theil Have

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, 
INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A 
PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT 
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF 
CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE 
OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

