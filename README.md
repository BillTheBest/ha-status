Usage

1. Config:
By default it starts on port 7828 (STAT)
For other config add in your .env file STATUS_PORT=<port_number>

2. Install
npm install haproxy-status

3. Usage
3.1 No http library
require('./../lib/status').load();
3.2 Hapi or Express
require('./../lib/status').load(yourServerObject);

For some examples you can look in test/default.js