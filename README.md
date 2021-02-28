# node-hello-world
"name": "HelloWorldNodeApp",
	"version": "0.0.1",
	"private": true,
	"scripts": {
		"start": "node app.js",
		"test-unit": "mocha test/unit-test.js --reporter json --reporter-options output=test/unit-test.json | tee test/unit-test.json"
	},
	"dependencies": {
		"express": "4.17.x",
		"cfenv": "1.2.x"
	},
	"repository": {},
	"engines": {
		"node": "10.x || 12.x"
	},
	"devDependencies": {
		"chai": "^4.2.0",
		"mocha": "^7.0.1",
		"nyc": "*"
