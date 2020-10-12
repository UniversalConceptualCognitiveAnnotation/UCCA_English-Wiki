The UCCA Wikipedia Corpus
=========================
Version 2.0.0 (April 15, 2020)
----------------------------------

This bundle contains 367 passages annotated according to the foundational layer of UCCA. 
The passages are given as xmls in a format which is described below. The total number of tokens 
in this corpus is 158690. It also contains the annotation guidelines that were given to the annotators,
and a metadata file.

The dataset is a part of the UCCA project developed in the NLP lab of the Hebrew University 
by Omri Abend and Ari Rappoport. The users of this dataset are kindly requested to cite [the following publication](http://www.aclweb.org/anthology/P13-1023):

```
@inproceedings{abend-rappoport-2013-universal,
    title = "{U}niversal {C}onceptual {C}ognitive {A}nnotation ({UCCA})",
    author = "Abend, Omri  and
      Rappoport, Ari",
    booktitle = "Proc. of ACL",
    month = aug,
    year = "2013",
    address = "Sofia, Bulgaria",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/P13-1023",
    pages = "228--238",
}
```

Example passages can be graphically viewed through our [web application](http://ucca.cs.huji.ac.il).
Please refer to [our website](http://www.cs.huji.ac.il/~oabend/ucca.html) or email (oabend@cs.huji.ac.il)
for regular updates on the UCCA project and available resources.


Files included
--------------
1. The passages files in an XML format. file names are of the form `ucca_passageXXX.xml` where XXX 
   is the passage ID. Please see [the UCCA resource webpage](http://www.cs.huji.ac.il/~oabend/ucca.html) for a software package for reading and using 
   these files.
2. [`metadata`](metadata): a file that contains some metadata for the passages. Specifically it contains the source
   of the text used (i.e., the Wikipedia article it was taken from), and the index of the annotator
   that did the final proof-reading (it can be 2,3 or 6).
3. [`guidelines.pdf`](guidelines.pdf): the annotation guidelines that were given to the annotators are summarized in 
   this file named "UCCA in a nutshell". Concise definitions are available through the UCCA website
   as well.
4. [`short_defs.deprecated.pdf`](short_defs.deprecated.pdf): a brief summary of the categories used by UCCA's foundational layer (used for the original annotation).


XML format
----------
See [`FORMAT.md`](https://github.com/UniversalConceptualCognitiveAnnotation/docs/blob/master/FORMAT.md).


Licensing
---------

The texts are taken from the English Wikipedia (http://en.wikipedia.org). 
The specific articles they were taken from are listed in the metadata file. 
The Wikipedia texts, as well as the UCCA annotation is distributed under the 
"Attribution-ShareAlike 3.0 Unported" license (http://creativecommons.org/licenses/by-sa/3.0/).
Please follow the link for exact details.


ACKNOWLEDGEMENTS:
-----------------

We would like to thank Tomer Eshet for his partnering in developing the UCCA web application,
and Amit Beka for his help with UCCA's development set and software tools. We would also like
to thank our four annotators for hard and thorough work.

