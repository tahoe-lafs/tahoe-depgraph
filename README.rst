==============
tahoe-depgraph
==============

`View the generated graph on github pages.
<https://tahoe-lafs.github.io/tahoe-depgraph/>`_

A little thing based on `Toby Dickenson's py2depgraph
<http://www.tarind.com/py2depgraph.py>`_ for determining the dependency tree of
tahoe-lafs.

It's generalizable, but I haven't. The purpose of this is for assisting in
python 3 porting: module dependencies as determined from imports are useful in
determining which things have their dependencies ported or not.
