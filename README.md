# Quick Start #

1) To install the package and any packages that it depends on, run:
	npm install

2) To install all dependencies, run:
	npm i electron-is-dev

3) To install these packages at devDependencies, run:
	npm i -D concurrently electron electron-builder wait-on cross-env

4) To run the application as an Electron app, run:
	npm run electron-dev

OR

5) To distribute the desktop app, run:
	npm run electron-dev
	
	- When the build is successful, the "dist" folder is created. Inside it, you can run the .exe file to install the app or you can run it directly from the "win-unpacked" folder.
