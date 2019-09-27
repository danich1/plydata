.. _api:

#############
API Reference
#############

One table verbs
===============

.. currentmodule:: plydata.one_table_verbs

.. autosummary::
   :toctree: generated/
   :nosignatures:
   :template: main.rst

   arrange
   create
   define
   distinct
   do
   group_by
   group_indices
   head
   mutate
   pull
   query
   rename
   sample_frac
   sample_n
   select
   slice_rows
   summarize
   tail
   transmute
   ungroup
   unique

Helpers
-------

.. currentmodule:: plydata.helper_verbs

.. autosummary::
   :toctree: generated/
   :nosignatures:
   :template: main.rst

   add_count
   add_tally
   count
   tally
   call
   arrange_all
   arrange_at
   arrange_if
   create_all
   create_at
   create_if
   group_by_all
   group_by_at
   group_by_if
   mutate_all
   mutate_at
   mutate_if
   query_all
   query_at
   query_if
   rename_all
   rename_at
   rename_if
   summarise_all
   summarise_at
   summarise_if
   summarize_all
   summarize_at
   summarize_if
   transmute_all
   transmute_at
   transmute_if


Two table verbs
===============

.. currentmodule:: plydata.two_table_verbs

.. autosummary::
   :toctree: generated/
   :nosignatures:
   :template: main.rst

   anti_join
   full_join
   inner_join
   left_join
   outer_join
   right_join
   semi_join


Expression helpers
==================
These classes can be used construct complicated conditional assignment
expressions.

.. currentmodule:: plydata.expressions

.. autosummary::
   :toctree: generated/
   :nosignatures:
   :template: main.rst

   case_when
   if_else


Tidy Verbs
==========
These verbs help create `tidy data <https://en.wikipedia.org/wiki/Tidy_data>`_.

.. currentmodule:: plydata.tidy

.. autosummary::
   :toctree: generated/
   :nosignatures:
   :template: main.rst

   gather
   spread
   separate
   separate_rows
   extract
   pivot_wider
   pivot_longer

Options
=======

.. currentmodule:: plydata.options

.. autosummary::
   :toctree: generated/
   :nosignatures:
   :template: main.rst

   modify_input_data
   get_option
   set_option
   options

Useful Functions
================

.. currentmodule:: plydata.utils

.. autosummary::
   :toctree: generated/
   :nosignatures:
   :template: main.rst

   Q
   n
