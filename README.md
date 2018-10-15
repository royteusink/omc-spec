# OpenMediaCollection - Specification

## media spec

```javascript
{
	"id": "string",
	"title": "string",
	"description": "string",
	"colored": "boolean",
	"condition": {
		"id": "integer",
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
	"tags": [{
		"id": "integer",
		"name": "string"
	}],
	"things": [{
		"id": "integer",
		"name": "string"
	}],
	"persons": [{
		"id": "integer",
		"firstname": "string",
		"lastnameprefix": "string",
		"lastname": "string"
	}]
}
```
