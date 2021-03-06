Example Usage
~~~~~~~~~~~~~
The ``narrative`` child element can be used to declare freetext for the ``description`` element.

.. literalinclude:: ../../../../../activity-standard-example-annotated.xml
	:language: xml
	:start-after: <!--result-document-link example starts-->
	:end-before: <!--result-document-link example ends-->

| The ``narrative`` element can be repeated for any language additional to the default language set in ``iati-organisation``, by using the ``@xml:lang`` attribute.

| Note: This relates to the language of the text in the XML.

Changelog
~~~~~~~~~

2.03
^^^^
| This mandatory ``narrative`` element of a ``description`` in a ``document-link`` element was `added <https://discuss.iatistandard.org/t/add-document-link-to-results-indicator-included-2-03/895>`__.
