
```Javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let res = await client.api('/security/securityActions')
	.version('beta')
	.get();

```