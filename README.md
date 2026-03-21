# Privacy Terms

Rails app for hosting standard legal pages: Privacy, Terms, and Accessibility.

## Pages
- `/` (root) renders Privacy
- `/privacy`
- `/terms`
- `/accessibility`

## Content
Content is stored in `config/legal_content.json`. Update the copy there and the pages will reflect it.

## Navigation
This template does not render legal page links inside the legal pages themselves. Add links in your existing site footer or navigation if you want cross-links between Privacy, Terms, and Accessibility.

## Setup
```bash
bin/setup
```

## Run
```bash
bin/rails s
```

## Tests
```bash
bin/rails test
bin/rails test:system
```

System tests run with `rack_test` for CI compatibility.
