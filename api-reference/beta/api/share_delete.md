# Delete share

Delete share.
## Prerequisites
The following **scopes** are required to execute this API: 
## HTTP request
<!-- { "blockType": "ignored" } -->
```http
DELETE /shares/{id}

```
## Request headers
| Name       | Type | Description|
|:---------------|:--------|:----------|
| Authorization  | string  | Bearer <token>. Required. |

## Request body
Do not supply a request body for this method.


## Response
If successful, this method returns `204, No Content` response code. It does not return anything in the response body.

## Example
##### Request
Here is an example of the request.
<!-- {
  "blockType": "request",
  "name": "delete_share"
}-->
```http
DELETE https://graph.microsoft.com/beta/shares/{id}
```
##### Response
Here is an example of the response. 
<!-- {
  "blockType": "response",
  "truncated": true
} -->
```http
HTTP/1.1 204 No Content
```

<!-- uuid: 8fcb5dbc-d5aa-4681-8e31-b001d5168d79
2015-10-25 14:57:30 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "Delete share",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->