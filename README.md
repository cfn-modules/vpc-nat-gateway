# cfn-modules: AWS VPC NAT gateway

This is an internal module. Have a look at the [vpc](https://www.npmjs.com/package/@cfn-modules/vpc) module instead.

## Limitations

* Highly available: NAT gateways only live in a single AZ by design (use on in each AZ to overcome limitation)
* Scalable: NAT gateways capacity (CPU, RAM, network, ...) is limited by design
