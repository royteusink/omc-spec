# OpenMediaCollection - Specification

## media spec

```javascript
{
	"title": "string",
	"description": "string",
	"colored": "boolean",
	"condition": {
		"name": "string"
	},
	"created": "datetime",
	"updated": "datetime",
	"dimension": {
		"width": "integer",
		"height": "integer",
	},
	"file": {
		"name": "string"
		"path": "string",
		"size": "integer",
		"type": "integer",
	},
	"fingerprint": {
		"perceptual": "biginteger",
		"hash": "string"
	},
	"location": {
		"latitude": "double",
		"longitude": "double"
	},
	"period": {
		"from": "integer",
		"to": "integer"
	},
	"colors": [{
		"name": "string",
		"hex": "string"
	}],
	"tags": [{
		"name": "string"
	}],
	"things": [{
		"name": "string"
	}],
	"persons": [{
		"firstname": "string",
		"lastnameprefix": "string",
		"lastname": "string"
	}]
}
```
