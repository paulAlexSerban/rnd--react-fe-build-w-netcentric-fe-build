# RND - Small Project - React Fe Build w. @netcentric/fe-build

## Use-case: Small w. Low complexity React Project
- monolithic and monorepo
- naming convention - Atomic Design and BEM
- file structure & architecture & concepts -  OOCSS, SMACSS, The 7-in-1, Atomic-Design, ITCSS
- CSS file spliting strategy: layer splitting
- implement basic Atomic Design modules structuring
	- `./components` -> RENAME -> `./library`
	- abstract and split components
		- `./library`  INCLUDES `./atoms`, `./molecules`, `./organisms`
		- `./system`  INCLUDES `./templates`, `./pages`
	- namings: `a-componentName__base`, `m-componentName__base`, `o-componentName__base`, ...
- recomanded for prorotyping organsisms widgets and  small SPAs
