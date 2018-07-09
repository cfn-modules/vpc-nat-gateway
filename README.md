[![Build Status](https://travis-ci.org/cfn-modules/vpc-nat-gateway.svg?branch=master)](https://travis-ci.org/cfn-modules/vpc-nat-gateway)
[![NPM version](https://img.shields.io/npm/v/@cfn-modules/vpc-nat-gateway.svg)](https://www.npmjs.com/package/@cfn-modules/vpc-nat-gateway)

# cfn-modules: AWS VPC NAT gateway

This is an internal module. Have a look at the [vpc](https://www.npmjs.com/package/@cfn-modules/vpc) module instead.

## Limitations

* Highly available: NAT gateways only live in a single AZ by design (use on in each AZ to overcome limitation)
* Scalable: NAT gateways capacity (CPU, RAM, network, ...) is limited by design
