# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > modules > export-declaration-trailing-comma`

### `ast`

```javascript
JSRoot {
	body: [
		JSExportExternalDeclaration {
			namedSpecifiers: [
				JSExportExternalSpecifier {
					leadingComments: ["1"]
					trailingComments: ["2", "3", "4"]
					exported: JSIdentifier {
						name: "Foo"
						loc: SourceLocation es2015/modules/export-declaration-trailing-comma/input.js 2:12-2:15 (Foo)
					}
					local: JSIdentifier {
						name: "Foo"
						loc: SourceLocation es2015/modules/export-declaration-trailing-comma/input.js 2:12-2:15 (Foo)
					}
					loc: SourceLocation es2015/modules/export-declaration-trailing-comma/input.js 2:12-2:15
				}
			]
			source: JSStringLiteral {
				value: "foo"
				loc: SourceLocation es2015/modules/export-declaration-trailing-comma/input.js 5:18-5:23
			}
			loc: SourceLocation es2015/modules/export-declaration-trailing-comma/input.js 1:0-5:24
		}
	]
	comments: [
		CommentBlock {
			id: "1"
			value: " One "
			loc: SourceLocation es2015/modules/export-declaration-trailing-comma/input.js 2:2-2:11
		}
		CommentBlock {
			id: "2"
			value: " Two "
			loc: SourceLocation es2015/modules/export-declaration-trailing-comma/input.js 3:2-3:11
		}
		CommentBlock {
			id: "3"
			value: " Three "
			loc: SourceLocation es2015/modules/export-declaration-trailing-comma/input.js 4:2-4:13
		}
		CommentBlock {
			id: "4"
			value: " Four "
			loc: SourceLocation es2015/modules/export-declaration-trailing-comma/input.js 5:2-5:12
		}
	]
	corrupt: false
	diagnostics: []
	directives: []
	hasHoistedVars: false
	sourceType: "module"
	syntax: []
	path: UIDPath<es2015/modules/export-declaration-trailing-comma/input.js>
	loc: SourceLocation es2015/modules/export-declaration-trailing-comma/input.js 1:0-6:0
}
```

### `diagnostics`

```

```
