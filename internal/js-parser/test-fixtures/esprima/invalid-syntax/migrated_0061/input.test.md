# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > invalid-syntax > migrated_0061`

### `ast`

```javascript
JSRoot {
	body: [
		JSExpressionStatement {
			expression: JSBinaryExpression {
				operator: "+"
				left: JSNumericLiteral {
					value: 1
					loc: SourceLocation esprima/invalid-syntax/migrated_0061/input.js 1:0-1:1
				}
				right: JSObjectExpression {
					properties: [
						JSObjectProperty {
							key: JSStaticPropertyKey {
								value: JSIdentifier {
									name: "t"
									loc: SourceLocation esprima/invalid-syntax/migrated_0061/input.js 1:6-1:7 (t)
								}
								loc: SourceLocation esprima/invalid-syntax/migrated_0061/input.js 1:6-1:7
							}
							value: JSReferenceIdentifier {
								name: "t"
								loc: SourceLocation esprima/invalid-syntax/migrated_0061/input.js 1:8-1:9 (t)
							}
							loc: SourceLocation esprima/invalid-syntax/migrated_0061/input.js 1:6-1:9
						}
						JSObjectProperty {
							key: JSStaticPropertyKey {
								value: JSIdentifier {
									name: ""
									loc: SourceLocation esprima/invalid-syntax/migrated_0061/input.js 2:0-2:0 ()
								}
								loc: SourceLocation esprima/invalid-syntax/migrated_0061/input.js 2:0-2:0
							}
							value: JSReferenceIdentifier {
								name: ""
								loc: SourceLocation esprima/invalid-syntax/migrated_0061/input.js 2:0-2:0 ()
							}
							loc: SourceLocation esprima/invalid-syntax/migrated_0061/input.js 2:0-2:0
						}
					]
					loc: SourceLocation esprima/invalid-syntax/migrated_0061/input.js 1:4-2:0
				}
				loc: SourceLocation esprima/invalid-syntax/migrated_0061/input.js 1:0-2:0
			}
			loc: SourceLocation esprima/invalid-syntax/migrated_0061/input.js 1:0-2:0
		}
	]
	comments: []
	corrupt: false
	diagnostics: [
		{
			origins: [{entity: "ParserCore<js>"}]
			description: {
				advice: []
				category: ["parse"]
				categoryValue: "js"
				message: RAW_MARKUP {value: "Expected an identifier"}
			}
			location: {
				language: "js"
				path: UIDPath<esprima/invalid-syntax/migrated_0061/input.js>
				end: Position 1:10
				start: Position 2:0
			}
		}
	]
	directives: []
	hasHoistedVars: false
	sourceType: "script"
	syntax: []
	path: UIDPath<esprima/invalid-syntax/migrated_0061/input.js>
	loc: SourceLocation esprima/invalid-syntax/migrated_0061/input.js 1:0-2:0
}
```

### `diagnostics`

```

 esprima/invalid-syntax/migrated_0061/input.js:2 parse(js) ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Expected an identifier

    1 + { t:t,


```
