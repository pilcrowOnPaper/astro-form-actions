# Changelog

### 0.4.1

- [Fix] Proper types for `result.inputValues` for `action()`

### 0.4.0

- [Breaking] Rename `handleFormSubmission()` to `action()`
- [Breaking] Rename `result.redirect_location` to `result.redirectLocation` for return type of `submitForm()`

### 0.3.2

- Remove unused code

### 0.3.1

- Remove `parse-multipart-data` dependency
- Remove Node dependencies

### 0.3.0

- Enable CSRF protection by default
- [Breaking] Remove `redirected` from `handleFormSubmission` result, add `redirectLocation`
- [Breaking] `inputValues` in `handleFormSubmission` result omits file values
- Make body parameter for `resolve` optional

### 0.2.3

- Update README

### 0.2.2

- [Fix] Fix package.json

### 0.2.1

- [Fix] Proper types for `handleFormSubmission`