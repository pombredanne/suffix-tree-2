===========================
 A Generalized Suffix Tree
===========================

A Generalized Suffix Tree for any Python iterable, with Lowest Common Ancestor
retrieval.

.. code-block:: shell

   pip install suffix-tree

This implementation:

- works with any Python iterable, not just strings, if the items are hashable,
- is a generalized suffix tree for sets of iterables,
- uses Ukkonen's algorithm to build the tree in linear time,
- does constant-time Lowest Common Ancestor retrieval,
- outputs the tree as GraphViz .dot file.

This implementation follows [Gusfield1997]_ Chapter 6, with some differences:

- indices are 0-based (a Python convention),
- end indices point one element beyond the end (also a Python convention).

PyPi: https://pypi.org/project/suffix-tree/

.. [Gusfield1997] Gusfield, Dan.  Algorithms on strings, trees, and sequences.
                  1997.  Cambridge University Press.
