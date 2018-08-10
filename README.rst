======================================
Graphviz extension for Python-Markdown
======================================

A Python Markdown extension that replaces inline Graphviz definitins with inline SVGs or PNGs!

refer: https://github.com/sprin/markdown-inline-graphviz

example::

    {% dot attack_plan.svg
        digraph G {
            rankdir=LR
            Earth [peripheries=2]
            Mars
            Earth -> Mars
        }
    %}
