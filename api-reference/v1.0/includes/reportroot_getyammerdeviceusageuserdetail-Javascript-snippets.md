
```Javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let res = await client.api('/reports/getYammerDeviceUsageUserDetail(period='D7')')
	.get();

```