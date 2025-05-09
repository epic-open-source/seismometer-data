# seismometer-data
Data repository for [seismometer](http://github.com/epic-open-source/seismometer/) examples.

| :warning: This is not a general-purpose data archive :warning: |
| :---: |

This repository exists to provide example data sets used for documentation, examples, and issue submission that do not contain PHI or PII. The data sets may have their own associated license. 
The datasets may change or be removed at any time if they are no longer useful for the seismometer documentation. Some of the datasets have also been modified from their canonical sources.
These datasets may have been altered from thier original form to include synthetic data to demonstrate Seismomter use cases. Do not use this data for anything other than illustrative purposes.

## Data sources


A list of where these datasets originate from.

- `diabetes`: https://archive.ics.uci.edu/dataset/296/diabetes+130-us+hospitals+for+years+1999-2008

## Adding and Versioning Data Sets

Avoid breaking changes. Try not to remove (or rename) columns if modifying a dataset that is currently in use as a Seismometer example. If necessary, consider creating a versioned directory to allow existing users to continue to use earlier datasets and support backwards compatibility.

Include the default testing files associated with a dataset, so it's easy to import the entire folder contents into a model notebook folder for experimentation.

