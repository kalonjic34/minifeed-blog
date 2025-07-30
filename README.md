# MiniFeed Blog

MiniFeed is a simple microblogging website built with [Flask](https://flask.palletsprojects.com/). Users can submit short text entries, which are displayed with their submission date.

## Features

- Add new blog entries via a form
- View recent posts with formatted dates
- Responsive and clean design using custom CSS
- Minimal dependencies

## Project Structure

```
.
├── app.py
├── static/
│   ├── logo.png
│   └── css/
│       └── styles.css
├── templates/
│   └── home.html
└── .gitignore
```

- `app.py`: Main Flask application.
- `static/`: Static assets (CSS, images).
- `templates/`: HTML templates.

## Getting Started

### Prerequisites

- Python 3.7+
- [Flask](https://flask.palletsprojects.com/)

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/minifeed-blog.git
    cd minifeed-blog
    ```

2. (Optional) Create and activate a virtual environment:
    ```sh
    python -m venv .venv
    source .venv/bin/activate  # On Windows: .venv\Scripts\activate
    ```

3. Install Flask:
    ```sh
    pip install flask
    ```

### Running the App

Start the Flask development server:

```sh
python app.py
```

Then open [http://127.0.0.1:5000/](http://127.0.0.1:5000/) in your browser.

## Usage

- Add a new entry using the form at the top.
- Recent posts will appear below, showing the content and the date.

## Customization

- Edit `static/css/styles.css` to change the look and feel.
- Update `templates/home.html` to modify the HTML structure.

## Notes

- Entries are stored in memory and will be lost when the server restarts.
- For persistent storage, consider integrating a database.
- This limitation will be fixed soon