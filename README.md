This is an attempt to have a JSON Schema for capturing mapping information to map OMOP to FHIR.

You only need to use the O52R4-mapping directory to create *.yaml files. Ignore the other directories for now. They are meant for additional features later.

Use this with VS Code.  Open the VS Code workspace with the O2F.code-workspace file to get the configuration needed to use the schema.

It appears that the JSON Schema support for JSON files, in the latest VS Code (1.64.2 at the time of this writing), is worse than it was few versions ago. However, the schema support for *.yaml files is good. So, it wouldn't make sense giving this situation to represent mapping info in the JSON format. The same JASON Schema will support *.yaml file editing.

TODO: Document the schema once it's stable.  Look at the O52R4-mapping/test.yaml file to get some sense of what's there.