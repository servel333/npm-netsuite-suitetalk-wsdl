Contains the [NetSuite SuiteTalk](http://www.netsuite.com/portal/developers/resources/suitetalk-documentation.shtml) [WSDL_v2016_2_0 files](http://www.netsuite.com/download/WSDL_v2016_2_0.zip)

## Usage

```
const soap = require('soap');
const wsdl = require('netsuite-suitetalk-wsdl-v2016-2.0');

soap.createClient(wsdl.netsuiteWsdl, (err, client) => {
  if(err) {
    console.log(err);
    process.exit(1);
  }

  // client ...
});
```
