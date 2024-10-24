# Summary

This is an example treebank made to ilustrate UD annotation choices made for Latvian based on the Cairo sample sentences. Created by [AI Lab](http://ailab.lv) at Institute of Mathematics and Computer Science, University of Latvia.


# Introduction

This treebank is developed together with the main Latvian UD Treebank (UD_Latvian-LVTB) by the same team with the same workflow and convertion tools. It contains the 20 Cairo example sentences and is meant to be a quick reference on how various syntactic constructions of Latvian are annotated in UD. For more information on Latvian UD Treebank, see the documentation of [UD_Latvian-LVTB](https://github.com/UniversalDependencies/UD_Latvian-LVTB) or the original [LVTB](http://sintakse.korpuss.lv) treebank.


# Acknowledgments

This work was supported by the State Research Programme's project [Research on Modern Latvian Language and Development of Language Technology](http://www.digitalhumanities.lv/projects/vpp-late/) under the grant agreement No. VPP-LETONIKA-2021/1-0006.


## References

* Pretkalniņa L., Rituma L., Saulīte B. Deriving enhanced Universal Dependencies from a hybrid dependency-constituency treebank. Proceedings of the 21sh International Conference Text, Speech, and Dialogue, LNCS, Vol. 11107, Springer Link, 2018, pp. 95-105


# Changelog

* 2024-11-15 v2.15
  * Introduced advmod:emph for various particles.
  * DET/PRON distinction is now done by lexeme, not by syntax tree.
  * Most of comparison constructions considered secondary predicative components in Latvian are now advcl or acl in UD.

* 2024-05-15 v2.14
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.14
License: CC BY-SA 4.0
Includes text: yes
Genre: grammar-examples
Lemmas: manual native
UPOS: converted from manual
XPOS: manual native
Features: converted from manual
Relations: converted from manual
Contributors: Pretkalniņa, Lauma; Rituma, Laura; Saulīte, Baiba; Nešpore-Bērzkalne, Gunta
Contributing: elsewhere
Contact: lauma@ailab.lv
===============================================================================
</pre>
