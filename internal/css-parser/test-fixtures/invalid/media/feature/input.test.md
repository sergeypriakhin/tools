# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/css-parser/index.test.ts --update-snapshots` to update.

## `invalid > media > feature`

```javascript
CSSRoot {
	body: [
		CSSAtRule {
			name: "media"
			prelude: []
			block: CSSMediaQueryList {
				prelude: [
					CSSMediaQuery {
						value: CSSMediaType {
							value: "screen"
							loc: SourceLocation invalid/media/feature/input.css 1:7-1:13
						}
						loc: SourceLocation invalid/media/feature/input.css 1:6-1:18
					}
				]
				block: CSSBlock {
					value: []
					startingTokenValue: "{"
					loc: SourceLocation invalid/media/feature/input.css 1:18-1:20
				}
				loc: SourceLocation invalid/media/feature/input.css 1:6-1:20
			}
			loc: SourceLocation invalid/media/feature/input.css 1:0-1:20
		}
	]
	comments: []
	corrupt: false
	diagnostics: [
		{
			origins: [{entity: "ParserCore<css>"}]
			description: {
				advice: []
				category: ["parse"]
				categoryValue: "css"
				message: RAW_MARKUP {value: "A left parenthesis or the keyword <emphasis>not</emphasis> are expected in this position."}
			}
			location: {
				language: "css"
				path: RelativePath<invalid/media/feature/input.css>
				end: Position 1:19
				start: Position 1:18
			}
		}
	]
	path: RelativePath<invalid/media/feature/input.css>
	loc: SourceLocation invalid/media/feature/input.css 1:0-1:20
}
```
