APP_NAME = connector-tests
APP_PATH = tests/connector-tests
BUILDPACK = eu.gcr.io/kyma-project/test-infra/buildpack-golang-toolbox:v20200423-1d9d6590
SCRIPTS_DIR = $(realpath $(shell pwd)/../..)/scripts

include $(SCRIPTS_DIR)/generic_make_go.mk

VERIFY_IGNORE := /vendor\|/automock\|/testdata

verify:: vet

test-local: ;
