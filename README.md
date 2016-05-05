ngBraveApp sceleton for creating bower packages
==============================================

Package contains:

1. Sample README.md
2. Sample package.json
3. MIT LICENSE file
4. Gulp tasks for eslint and karma tests
5. Bower conf file
6. Editorconfig file
7. Simple test
8. Task to build dist files
9. Example Angular module
10. Coverage info

Development
-----------
To run the code in your development environment:

1. Run `git clone --recursive git@bitbucket.org:sizeof/angular-brave-app-sceleton.git angular-brave-app-sceleton`
2. Run `npm install`
3. Run `gulp` for watch changes in code

For development module on local

1. Run `bower link` on component directory
2. Go to the app root directory and run `bower link angular-brave-app-sceleton` 

Notice! You must re-link your bower module in app after changes in component 


Production
----------
To build minified version:

1. Run `gulp dist`
2. Add files to repo `git add .`
3. Commit changes `git commit -m "Message"`
3. Make tag version `git tag -a x.y.z`
4. Push version to git `git push --tags`
