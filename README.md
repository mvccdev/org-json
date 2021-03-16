![](https://img.shields.io/static/v1?label=category&message=json&color=red)

# Org JSON

A collection of campus organization data in JSON format.

[Documentation](doc/toc.md)

## Example

It's not recommended to do this from the main branch. Please use a release.

	fetch("https://raw.githubusercontent.com/mvccdev/org-json/main/api/{NAME}.json")
		.then((resp) => {
			resp.json().then((data) => {
				//
				// Iterate through the array here.
				//
			}
		});
	});

## Skill Prerequisites

A basic understanding of the following skills are necessary to use this project.

* [ES6](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
* [JSON](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON)

# Tool Dependencies

Install the following tools to use this project in your local development environment.

* [Node.js](https://nodejs.org/)
* [Git](https://git-scm.com/)
* [GitHub Desktop](https://desktop.github.com/)

## Installing

Follow these steps to install this project.

	git clone https://github.com/org-json/org-json.git
	cd org-json
	npm install
	npm run watch

## Building

Use the following CL commands to test or compile this project:

| Name          | Description                                          |
| ------------- | ---------------------------------------------------- |
| npm run watch | Test the project in a local development server       |
| npm run build | Build the project                                    |

## Contributing

Pull requests are encouraged and welcome.

## License

MIT
