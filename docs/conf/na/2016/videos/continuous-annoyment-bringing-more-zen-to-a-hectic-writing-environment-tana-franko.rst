:template: 2017/video-details.html

Continuous Annoyment: Bringing More Zen to a Hectic Writing Environment
=======================================================================

{% set talk = conferences[2016]['na']['speakers'][18] %}
{% set output %}
{% include conf_py_root + '/_templates/video-details-body.html' %}
{% endset %}
.. raw:: html

    {{ output|indent(4) }}
