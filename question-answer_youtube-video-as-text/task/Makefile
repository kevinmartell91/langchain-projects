.PHONY: help

help: logo ## get a list of all the targets, and their short descriptions
	@# source for the incantation: https://marmelab.com/blog/2016/02/29/auto-documented-makefile.html
	@grep -E '^[a-zA-Z_-]+:.?## .$$' Makefile | awk 'BEGIN {FS = ":.*?##"}; {printf "\033[1;38;5;214m%-12s\033[0m %s\n", $$1, $$2}' 

environment: # install required environment for the tutorial
	python3 -m pip install -qqq -r requirements.txt
		
logo: ## prints tha logo
	@cat logo.txt; echo "\n"