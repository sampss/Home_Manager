
// Project Structure - each app should be built in a self contained fashion, yet should share files where possible.
Home_Manager
	>android
	>ios
	App.tsx
	index.js
	README.md
	^src
		^standAloneApps
			>PortionConverter
			>UnitConverter
			^Recipes
				>assets
				>components
				>data
				>screens
				>utils
			>Stockpile
			>RefridgeratorNotes
		>SharedData
		>SharedUtils
	>node_modules