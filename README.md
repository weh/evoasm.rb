# Evoasm

## Description

*Evoasm* is an AIMGP (*Automatic Induction of Machine code by Genetic Programming*) engine.

You give it a set of examples, that is, several input/output pairs, that describe a program's behavior.
It will then try to come up with a short program (in the form of machine code) that follows your specification,
by means of genetic programming.
*Awasm* contains a JIT that executes the generated machine code on the fly.

Currently, the only supported architecture is **x86_64**.

**NOTE:** *Evoasm* is in a very early stage.

## Installation

    $ gem install evoasm --pre
    
### Requirements

* Ruby 2.3 (MRI)
* [Capstone](http://www.capstone-engine.org/) for disassembling (*optional*).
* POSIX-compliant OS (Linux and Mac OS X should both work).

## Usage

Please see [Getting Started](https://github.com/furunkel/evoasm/wiki/Getting-Started).


## Contributing

1. Fork it ( https://github.com/furunkel/evoasm/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request

## License

[MPL-2.0][license]

[license]: https://github.com/furunkel/evoasm/blob/master/LICENSE.txt
