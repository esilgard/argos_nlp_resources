resources available for use with the argos_nlp natural langauge processing pipeline available at
https://github.com/esilgard/argos_nlp

CONTENTS:

models
	this directory contains toy language models and feature sets (with no PHI) which can be used to test machine learning functionality and external dependencies in algorithms by the same name found in the argos_nlp repository.  These models are meant to be used for testing purposes only; they are not expected to correctly classify pathology reports and/or produce reliable data.  The 'models' directory will need to be placed in argos_nlp/fhcrc_pathology and the engine called with '-ml y' as a command line flag in order to test the machine learning algorithms.