# Django Fullstack dengan HTMX dan TailwindCSS

This project is a fullstack web application example using Django as the backend, and HTMX and TailwindCSS as frontend technologies. It is designed to demonstrate how to combine these three technologies to build a fast, responsive, and maintainable web application.

## Fitur Utama

- **Django Backend**: Provides the API and business logic of the application.
- **HTMX**: Enables page updates without full page reloads, resulting in a more dynamic user experience.
- **TailwindCSS**: A CSS framework offering pre-built utilities for creating beautiful and responsive designs with ease.

### Instalasi

1. Clone this repository:
```bash
git clone https://github.com/hendrapaiton/fullstack.git
```

2. Navigate into the project directory:
```bash
cd fullstack
```

3. Create and activate a virtual environment:
```bash
python -m venv .venv
source .venv/bin/activate  # On Windows use `.venv\Scripts\activate`
```

4. Install the dependencies:
```bash
pip install -r requirements.txt
tailwindcss -i ./static/src/main.css -o ./static/src/output.css --minify
```
5. Start the development server:

```bash
python manage.py runserver
```


### Usage

1. Open your browser and access http://127.0.0.1:8000 to view the application.

2. Explore the available features and see how HTMX works without full page reloads.

3. Enjoy the responsive and beautiful design created with TailwindCSS.


### Contribution

If you would like to contribute to this project, please fork this repository and create a pull request with your changes. Be sure to run all tests before submitting your pull request.


### License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.