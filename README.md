# Connect Julia SDK

[![Build Status](https://travis-ci.org/Lanzafame/Connect.jl.svg?branch=master)](https://travis-ci.org/Lanzafame/ConnectSDK.jl)

## Getting Access

Sign up at [https://getconnect.io](https://getconnect.io) to generate and retrieve your API keys so that you can start using the SDK.

## Installation

```julia
Pkg.add("ConnectSDK")
```

## Usage

```julia
using ConnectSDK

connect = ConnectClient(projectid, apikey)

r = push(connect, collection, data)

```

## Support

Get your questions answered and join in with the connect community at [http://docs.getconnect.io/discuss](http://docs.getconnect.io/discuss).

## Contributing

We love open source, so we are happy to accept pull requests and will endeavor to fix the issues and include the enhancements that the community raise.

## TODO

 - Event Batches
 - Queries
 - More tests
