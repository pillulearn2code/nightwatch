1. npm init (to create a package.json)
2. npm install --save-dev nightwatch (install nightwatch)
3. node_module folder will be added to the project.
4. add test folder
5. add reports and scenario folder inside test folder.
6. Copy "nightwatch.json"  to the main folder.from node_module/nightwatch/bin 
7. Edit nightwatch.json file.
9. add the test in the scenario folder.
8. in the commandline check the chromevriver is install.
9. Run chrome driver 
chromedriver --url-base=wd/hub --port=4444
10. In the new tab run the test using commant 
npm run test:nightwatch
