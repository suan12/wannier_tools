# Wannier_tools
**Authorship**

Written by QuanSheng Wu in Fortran (wuquansheng@gmail.com)
Copyright (c) 2010 QuanSheng Wu. All rights reserved.

**Pull down the package**

git clone https://github.com/quanshengwu/wannier_tools.git

**Brief introductions**

Use wannier functions to get the surface state of slab system 
or edge state of nanowire system or just bulk band. Especially
usefull for topological insulator.

Jan 29 2015 at ETH
With given hr files from wannier90, 

0. There is a Bi2Se3 example in the examples folder. The user guide is in the doc folder. Please read the user guide first. 

1. we can get the bulk energy band with given 
high symmetry kpoint lines. 

2. We can get the energy band for slab system when 
you specify a plane, which can be done by modify ham_qlayer2qlayer.f90. From 
this calculation, you can get surface state. This is very useful for studying
topological insulator. 

3. We can get the energy band for nanowire system also.

4. We can get fermi-surface for slab system. 

5. We can use iterative green's 
function to get beautifull surface state.


**License and agreement**

If you use our code, please cite this website “Q.S.Wu, https://github.com/quanshengwu/wannier_tools" . If you have good ideas to improve this code, do not hesitate to contact me. Your contribution will be recorded.

**Publication**

* [Nodal chain metals, arXiv:1604.03112, 2016 ](https://arxiv.org/abs/1604.03112)
* [Surface states and bulk electronic structure in the candidate type-II Weyl semimetal WTe2, arXiv:1604.02411, 2016](https://arxiv.org/abs/1604.02411)
* [Topological Phases in InAs1−xSbx: From Novel Topological Semimetal to Majorana Wire, arxiv:1602.07001, 2016](https://arxiv.org/abs/1602.07001)
* [Type-II Weyl semimetals, Nature 527, 495–498 (26 November 2015)](http://www.nature.com/nature/journal/v527/n7579/full/nature15768.html) 



