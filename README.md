# eslint-config-sagastandard
eslint sharable config for sagastandard

## Install (project)
Add as dependencies:
```bash
$ npm install --save-dev \
  eslint \
  eslint-config-sagastandard \
  eslint-config-semistandard \
  eslint-config-standard \
  eslint-config-standard-jsx \
  eslint-plugin-import \
  eslint-plugin-node \
  eslint-plugin-promise \
  eslint-plugin-react \
  eslint-plugin-standard
```

Add the following to your `eslintrc.json` or to your `package.json` `"eslintConfig"` key:
```json
{
  "extends": [ "sagastandard" ]
}
```

## Install (global)

```bash
$ npm install -g \
  eslint \
  eslint-config-sagastandard \
  eslint-config-semistandard \
  eslint-config-standard \
  eslint-config-standard-jsx \
  eslint-plugin-import \
  eslint-plugin-node \
  eslint-plugin-promise \
  eslint-plugin-react \
  eslint-plugin-standard

```

## Usage

Read up on how to use [sharable configs](http://eslint.org/docs/developer-guide/shareable-configs) at the eslint website.

### Atom
Use [linter-eslint](https://github.com/AtomLinter/linter-eslint)

### Sublime
Use [SublimeLinter-eslint](https://github.com/roadhump/SublimeLinter-eslin)

## License

[ISC](LICENSE.md)
