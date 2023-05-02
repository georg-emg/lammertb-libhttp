# LibHTTP API Reference

### `struct httplib_client_options;`

### Fields

| Field | Type | Description |
| :--- | :--- | :--- |
|**`host`**|`const char *`|The hostname or IP address to connect to|
|**`port`**|`int`|The port on the server|
|**`client_cert`**|`const char *`|Pointer to client certificate|
|**`client_private_key`**|`const char *`|Pointer to client private key, or NULL to use certificate file|
|**`server_cert`**|`const char *`|Pointer to a server certificate|

### Description

The the `mgclient_options` structure contains host and security information to connect as a client to another host. A parameter of this type is used in the call to the function [`httplib_connect_client_secure()`](httplib_connect_client_secure.md).

### See Also

* [`httplib_connect_client_secure();`](httplib_connect_client_secure.md)
