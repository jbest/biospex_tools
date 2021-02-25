# biospex_tools
A collection of tools for working with Biospex (https://biospex.org/ , https://github.com/iDigBio/Biospex) data

**biospex_expander** is a Jupyter notebook that allows you to load a Biospex export into a pandas dataframe and expand the JSON values for the 'occurrence' field into multiple columns.

**Darwin Core Assembler** (see separate repo - https://github.com/jbest/darwin-core-assembly) is a Jupyter notebook that allows you to filter the occurrence and image records from a Darwin Core Archive (such as exported from Symbiota) based on which records you want to be imported into a Biospex project. Once the appropriate filters are applied, a new DwC Archive is generated, ready to upload to Biospex.
