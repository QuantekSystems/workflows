# Workflows
This repository contains clinical workflow projects, which contain a json file describing the project, and additional files, typically Business Process Model and Notation (BPMN) and decision model and notation (DMN) files. They are organized broadly by the specific healthcare domain. Each workflow may have separate copyright and licensing.

# Contributing
To contribute a workflow, clone the repository, create a new folder under the correct category (e.g. radiation oncology or elsewhere), add a json file describing the project, a Readme.md, and the workflow files. Then issue a pull request.

# Project Description in JSON
Beneath is an example format to describe your project:

```
{
	"id": "my.project.id",
	"label": "Project Name",
	"author": {"id": "unique.author.name", "name":"John Doe", "linkedin": "url to linked in profile"},
	"organization": {"id": "organization.name", "name": "Organization Name", "website": "url to website", "linkedin": "url to linked in profile"}
	"license": "MIT",
	"description": "Description of workflow project to provide context around use case, and the related files such as BPMN and DMN."
}
```