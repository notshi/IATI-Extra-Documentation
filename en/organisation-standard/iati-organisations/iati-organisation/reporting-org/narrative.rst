Example Usage
~~~~~~~~~~~~~
The ``narrative`` child element can be used to declare freetext for the ``reporting-org`` element.

.. literalinclude:: ../../../organisation-standard-example-annotated.xml
	:language: xml
	:start-after: <!--reporting-org starts-->
	:end-before: <!--reporting-org ends-->

The ``narrative`` element can be repeated for any language additional to the default language set in ``iati-organisation``, by using the ``@xml:lang`` attribute:

.. literalinclude:: ../../../organisation-standard-example-annotated.xml
	:language: xml
	:start-after: <!--reporting-org starts-->
	:end-before: <!--reporting-org ends-->

Changelog
~~~~~~~~~

2.01
^^^^

| The ``narrative`` element was introduced in 2.01.
