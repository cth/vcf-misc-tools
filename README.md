## vcf-misc-tools

This a collection of tools for use with VCF files. These are not really general purpose tools, 
but more specialized tools to itch my own scratches. For a general tool suite take a look at 
[vcf-tools](https://github.com/vcftools/vcftools)

* _vcf-from-imputed_: Tool for converting imputed files (mach or impute2) to a VCF file, including conversion between dosages, genotype likehoods and "called" genotypes. 

* _vcf-bsearch_: Tool that does fast extraction of given positions in a sorted, but not necessarily indexed VCF file using a combination of binary and linear search. The output is another VCF file.


## Licence

	vcf-misc-tools 
    Copyright (C) 2015  Christian Theil HAve

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.

