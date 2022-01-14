# Java-BibCreator

![Badge](https://img.shields.io/badge/Java-v8.0-orange?color=orange&style=for-the-badge) ![Badge](https://img.shields.io/badge/LICENSE-MIT-green?color=blue&style=for-the-badge)

This is a school project using pure Java to practice ***Exception Handling***, and ***File I/O***, as well as other ***object-oriented concepts***. The main task of this tool is read and process a given .bib file (which has one or more
articles) and create 3 different files with the correct reference formats for IEEE, ACM and NJ. The source code here is just for others to study. ***It is absolutely not allowed to use for cheating!***

## Original File Format Example
```txt
@ARTICLE{  
    8247289,  
    author      =   {J. Park and J. N. James and Q. Li and Y. Xu and W. Huang},  
    journal     =   {IEEE Transactions on Vehicular Technology},  
    title       =   {Optimal DASH-Multicasting over LTE},  
    year        =   {2018},  
    volume      =   {PP},  
    number      =   {99},  
    pages       =   {15-27},  
    keywords    =   {Forward error correction;Long Term Evolution;Maintenance engineering;Multicast
                    communication;Resourcemanagement;Static VAr compensators;Streamingmedia;DASH;LTE;convexoptimization;eMBMS;multicasting},  
    doi         =   {10.1109/TVT.2018.2789899}, ISSN={0018-9545},  
    month       =   {January},  
}
```
## New File Format Example

#### IEEE Format
J. Park, J. N. James, Q. Li, Y. Xu, W. Huang. "Optimal DASH-Multicasting over LTE", IEEE Transactions on Vehicular Technology, vol. PP, no. 99, p. 15-27, January 2018.
#### ACM Format
[1] J. Park et al. 2018. Optimal DASH-Multicasting over LTE. IEEE Transactions on Vehicular Technology. PP, 99 (2018), 15-27. DOI:https://doi.org/10.1109/TVT.2018.2789899.
#### NJ Format
J. Park & J. N. James & Q. Li & Y. Xu & W. Huang. Optimal DASH-Multicasting over LTE. IEEE Transactions on Vehicular Technology. PP, 15-27(2018).

## Java Classes Used

- Scanner
- BufferedReader
- StringTokenizer
- FileInvalidException (created manually)
