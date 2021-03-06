Welcome to mp-units!
====================

**mp-units** is a compile-time enabled Modern C++ library that provides compile-time dimensional
analysis and unit/quantity manipulation. Source code is hosted on `GitHub <https://github.com/mpusz/units>`_
with a permissive `MIT license <https://github.com/mpusz/units/blob/master/LICENSE.md>`_.


.. important::

    The **mp-units** library is the subject of this ISO C++ paper: `P1935 <https://wg21.link/p1935>`_.
    It is explained in this `CppCon 2019 talk <https://youtu.be/0YW6yxkdhlU>`_ (slightly dated now).
    We are working towards potentially having it standardized for C++23 and are actively looking
    for parties interested in field trialing the library.

.. note::

    As this library targets C++23 and extensively uses C++20 features as of now it compiles correctly
    only with gcc-9.3 and newer.

.. toctree::
    :maxdepth: 2
    :caption: Getting Started:

    introduction
    quick_start
    usage
    framework
    use_cases
    design
    examples
    faq

.. toctree::
    :maxdepth: 2
    :caption: Reference:

    reference/core
    reference/systems
    reference/math
    reference/random

.. note::

    Source code documentation tools used to generate the above chapter still do not understand
    C++20 to well which results in some issues in the generated output. We do our best to address
    this ASAP.

.. toctree::
    :maxdepth: 1
    :caption: Appendix:

    glossary
    genindex
    CHANGELOG
