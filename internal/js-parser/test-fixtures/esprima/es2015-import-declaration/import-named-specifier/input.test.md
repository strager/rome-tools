# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-import-declaration > import-named-specifier`

### `ast`

```javascript
JSRoot {
	body: [
		JSImportDeclaration {
			namedSpecifiers: [
				JSImportSpecifier {
					imported: JSIdentifier {
						name: "bar"
						loc: SourceLocation esprima/es2015-import-declaration/import-named-specifier/input.js 1:8-1:11 (bar)
					}
					local: JSImportSpecifierLocal {
						name: JSBindingIdentifier {
							name: "bar"
							loc: SourceLocation esprima/es2015-import-declaration/import-named-specifier/input.js 1:8-1:11 (bar)
						}
						loc: SourceLocation esprima/es2015-import-declaration/import-named-specifier/input.js 1:8-1:11
					}
					loc: SourceLocation esprima/es2015-import-declaration/import-named-specifier/input.js 1:8-1:11
				}
			]
			source: JSStringLiteral {
				value: "foo"
				loc: SourceLocation esprima/es2015-import-declaration/import-named-specifier/input.js 1:18-1:23
			}
			loc: SourceLocation esprima/es2015-import-declaration/import-named-specifier/input.js 1:0-1:24
		}
	]
	comments: []
	corrupt: false
	diagnostics: []
	directives: []
	hasHoistedVars: false
	sourceType: "module"
	syntax: []
	path: UIDPath<esprima/es2015-import-declaration/import-named-specifier/input.js>
	loc: SourceLocation esprima/es2015-import-declaration/import-named-specifier/input.js 1:0-2:0
}
```

### `diagnostics`

```

```
