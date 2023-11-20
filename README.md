# Executor

An interface for executing contract calls.

## Interface

```solidity
/// @notice Executor interface.
interface IExecutor {
    function execute(address target, uint256 value, bytes calldata data)
        external
        payable
        returns (bytes memory result);
}
```
