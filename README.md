Object oriented shell
=====================

Collection of tools for working with object oriented shell.

This list assumes that object is described via JSON.

Preparing input
---------------

- ``jize`` – build JSON from text **(not yet implemented)**
- ``jfl``- format JSON data: one line – one JSON **(not yet implemented)**

System utils
-------------

- [``jls``](https://github.com/max-voloshin/jls), [``json4shell:ls2json``](https://github.com/amarao/json4shell) – analog of ``ls``
- ``jps`` – analog of ``ps`` **(not yet implemented)**
- ``jlsof`` – analog of ``lsof`` **(not yet implemented)**
- ``jfind`` – analog of ``find`` **(not yet implemented)**
- ``jipt`` – info from ``iptables`` **(not yet implemented)**

Manipulation
------------

- [``json4shell:array-head``](https://github.com/amarao/json4shell) – first N elements in array
- [``json4shell:array-tail``](https://github.com/amarao/json4shell) – last N elements in array
- [``json4shell:array-slice``](https://github.com/amarao/json4shell) – elements from N to M
- [``json4shell:array-get``](https://github.com/amarao/json4shell) – N element from array
- [``json4shell:array-uniq``](https://github.com/amarao/json4shell) – deduplicated array (every element repeat once)
- [``json4shell:array-sort``](https://github.com/amarao/json4shell) – sort array elements
- [``json4shell:array-shuffle``](https://github.com/amarao/json4shell) – randomize array
- [``json4shell:object-get``](https://github.com/amarao/json4shell) – value for key in object
- [``json4shell:object-values``](https://github.com/amarao/json4shell) – values of object as array

Preparing output
----------------

- [``json4shell:json-print``](https://github.com/amarao/json4shell)
