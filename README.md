# Telosys templates bundle for REST testing with SOAP-UI

A [Telosys](http://www.telosys.org/) bundle to generate files for [SoapUI](https://www.soapui.org/) tool.

This bundle generates a SoapUI project file (XML file) containing a set of REST requests for each entity defined in the model.

Once the project file has been generated just import it in SoapUI with "*File / Import project*"

The generated project has been tested with SoapUI 5.5.0

## Requirements

- Telosys 3.1.2 (or +)


## Dependencies

- No dependency

## Variables

This bundle uses the following variables :

- `PROJECT_NAME`
- `REST_URL_ROOT   (  e.g. http://localhost:8080 )`  

These variables must be defined before launching code generation


## License

This project uses the [LGPL v3 License](https://www.gnu.org/licenses/lgpl-3.0.en.html).