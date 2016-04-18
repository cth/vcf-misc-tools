## vcf-misc-tools

This a couple of tools for use with VCF files which may
contain imputed data, i.e., dosages or genotype likelihoods.

* _vcf-from-imputed_: Tool for converting imputed files (mach or impute2) to a VCF file, including conversion between dosages, genotype likehoods and "called" genotypes. 

* _vcf-bsearch_: Tool that does fast extraction of given positions/ranges in a sorted, but not necessarily indexed VCF file using a combination of binary and linear search. The output is another VCF file.

* _vcf-to-dosage-table_: Converts dosages from a VCF to a transposed tabular format (rows=individuals, cols=variants). Besage the dosage table file, an INFO file details REF/ALT alleles, ALT frequency and imputation score (INFO) for each variant.

* _vcf-split_: Column/individual-wise split of VCF file into several VCFs files. 

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

