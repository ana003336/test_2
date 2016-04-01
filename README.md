#!/bin/bash

DEFAULT_FOLDER="${HOME}/data_testing"
DEFAULT_SUBFOLDER="1023"
DEFAULT_RUN="FALSE"
DEFAULT_SCRIPT="${HOME}/projects/pipelines/examples/pipeline.sh"
# Function: get_options
#Retrive the -- StudyFolder=, Subscript and specified
get_batch_options()
local arguments=($@)

