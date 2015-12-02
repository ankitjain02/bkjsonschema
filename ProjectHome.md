jsonschema-code-generation-tools is a package containing two (2) tools that can generate parsing code for JSON object files (for now it generates Objective C code, but in the future it will generate Java parsing code based on Jackson). Both tools are based around simple extensions to the JSON Schema (RFC draft: http://tools.ietf.org/html/draft-zyp-json-schema-02) to better describe data types useful in complex parsing code.

The BkCoreData2JsonSchema Xcode project builds a command line tool that can generate a JSON schema file describing the entities (attributes and relationships) contained in a Core Data managed object model (.xcdatamodel files).

You can checkout the last source code to get it or [download a zip package here](http://code.google.com/p/bkjsonschema/downloads/detail?name=jsonschema-code-generation-tools-v1.0.zip&can=2&q=).