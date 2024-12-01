1. (Optional) Update repository:
	1.1. Obtain latest updates from upstream:
	```
	git remote add upstream "https://github.com/be5invis/Iosevka.git"
	git fetch --depth 3 upstream main
	git merge upstream/main --allow-unrelated-histories
	```

1. Prepare environment:
	2.1. Install npm dependencies on this directory by running command here:
	```
	npm install
	```
	2.2. Make sure to have `ttfautohint` installed and in environment path.

2. Start building by running commands:
```
npm run build -- contents::IosevkaCkt
npm run build -- contents::IosevkaCktFixedSpacing
```