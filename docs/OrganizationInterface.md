* [OrganizationInterface](#organizationinterface)
  * [supportsInterface](#function-supportsinterface)
  * [getAssociatedKeys](#function-getassociatedkeys)
  * [getOrgJsonUri](#function-getorgjsonuri)
  * [getOrgJsonHash](#function-getorgjsonhash)
  * [owner](#function-owner)
  * [hasAssociatedKey](#function-hasassociatedkey)

# OrganizationInterface


## *function* supportsInterface

OrganizationInterface.supportsInterface(interfaceId) `view` `01ffc9a7`

> Returns true if this contract implements the interface defined by `interfaceId`. See the corresponding [EIP section](https://eips.ethereum.org/EIPS/eip-165#how-interfaces-are-identified) to learn more about how these ids are created.     * This function call must use less than 30 000 gas.

Inputs

| **type** | **name** | **description** |
|-|-|-|
| *bytes4* | interfaceId | undefined |


## *function* getAssociatedKeys

OrganizationInterface.getAssociatedKeys() `view` `0ba11d86`

> Returns all associatedKeys belonging to this organization.



Outputs

| **type** | **name** | **description** |
|-|-|-|
| *address[]* |  | undefined |

## *function* getOrgJsonUri

OrganizationInterface.getOrgJsonUri() `view` `1d855977`

> Returns the URI of ORG.JSON file stored off-chain.



Outputs

| **type** | **name** | **description** |
|-|-|-|
| *string* |  | undefined |

## *function* getOrgJsonHash

OrganizationInterface.getOrgJsonHash() `view` `72cd7fc9`

> Returns keccak256 hash of raw ORG.JSON contents. This should be used to verify that the contents of ORG.JSON has not been tampered with. It is a responsibility of the Organization owner to keep this hash up to date.



Outputs

| **type** | **name** | **description** |
|-|-|-|
| *bytes32* |  | undefined |

## *function* owner

OrganizationInterface.owner() `view` `8da5cb5b`

> Returns the address of the current owner.



Outputs

| **type** | **name** | **description** |
|-|-|-|
| *address* |  | undefined |

## *function* hasAssociatedKey

OrganizationInterface.hasAssociatedKey(addr) `view` `f5760597`

> Returns if an `address` is associated with the Organization. Associated keys can be used on behalf of the organization, typically to sign messages.

Inputs

| **type** | **name** | **description** |
|-|-|-|
| *address* | addr | Associated Ethereum address |

Outputs

| **type** | **name** | **description** |
|-|-|-|
| *bool* |  | undefined |

---