# Sample project for internal compile error

```
npm install
npx hardhat compile
```

This causes the error:
```
Internal exception in StandardCompiler::compile: /solidity/libsolidity/interface/Natspec.cpp(89): Throw in function static Json::Value solidity::frontend::Natspec::userDocumentation(const solidity::frontend::ContractDefinition &)
Dynamic exception type: boost::wrapexcept<solidity::langutil::InternalCompilerError>
std::exception::what: Solidity assertion failed
[solidity::util::tag_comment*] = Solidity assertion failed

Error HH600: Compilation failed

For more info go to https://hardhat.org/HH600 or run Hardhat with --show-stack-traces
```