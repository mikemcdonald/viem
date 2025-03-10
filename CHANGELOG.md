# viem

## 1.4.0

### Minor Changes

- [#908](https://github.com/wagmi-dev/viem/pull/908) [`988c65f8`](https://github.com/wagmi-dev/viem/commit/988c65f8218c9ce0549c04b3779efb5f685da75f) Thanks [@moldy530](https://github.com/moldy530)! - Added coin type support for `getEnsAddress`.

### Patch Changes

- [#878](https://github.com/wagmi-dev/viem/pull/878) [`4e227303`](https://github.com/wagmi-dev/viem/commit/4e2273036f8bbc7973b13467d7cb9baa2f17a460) Thanks [@salieflewis](https://github.com/salieflewis)! - Exported `Filter` type.

## 1.3.1

### Patch Changes

- [#907](https://github.com/wagmi-dev/viem/pull/907) [`319cdb61`](https://github.com/wagmi-dev/viem/commit/319cdb615f0ac6cff0385bb371be9a7da51abe80) Thanks [@Raiden1411](https://github.com/Raiden1411)! - Updated `abitype` to 0.9.3

## 1.3.0

### Minor Changes

- [`30a88482`](https://github.com/wagmi-dev/viem/commit/30a88482d541a346990eac9630b7fa1f1550c90a) Thanks [@jxom](https://github.com/jxom)! - Added chains:
  - `base`
  - `mev`
  - `mevTestnet`

## 1.2.15

### Patch Changes

- [#885](https://github.com/wagmi-dev/viem/pull/885) [`020c744d`](https://github.com/wagmi-dev/viem/commit/020c744d85e4150b4248407eae8a52ce390cfa9d) Thanks [@TateB](https://github.com/TateB)! - Added `null` resolver check to ENS Actions.

## 1.2.14

### Patch Changes

- [#883](https://github.com/wagmi-dev/viem/pull/883) [`ad96d39f`](https://github.com/wagmi-dev/viem/commit/ad96d39f6c9266dc6965013e255990952fa9323d) Thanks [@tmm](https://github.com/tmm)! - Exported missing types

## 1.2.13

### Patch Changes

- [#874](https://github.com/wagmi-dev/viem/pull/874) [`a9bc9f6d`](https://github.com/wagmi-dev/viem/commit/a9bc9f6d182052a536e51dc6fa75afda91de331a) Thanks [@Alexsey](https://github.com/Alexsey)! - Fixed `BaseError.walk` to return `null` if the predicate callback is not satisfied.

## 1.2.12

### Patch Changes

- [#864](https://github.com/wagmi-dev/viem/pull/864) [`b851c41b`](https://github.com/wagmi-dev/viem/commit/b851c41b87dce60af6be1e518e3c7a1b16e99b63) Thanks [@jxom](https://github.com/jxom)! - Fixed an issue where `dataSuffix` was not being provided to the `request` returned from `simulateTransaction`.

## 1.2.11

### Minor Changes

- [#857](https://github.com/wagmi-dev/viem/pull/857) [`513a7b9a`](https://github.com/wagmi-dev/viem/commit/513a7b9a4c037591b0fe4dd4fb4364bf8fed9726) Thanks [@tmm](https://github.com/tmm)! - Prettify-ed client types

## 1.2.10

### Patch Changes

- [#853](https://github.com/wagmi-dev/viem/pull/853) [`a955007e`](https://github.com/wagmi-dev/viem/commit/a955007e00f9076f4d2faefb5473df0fb968de8e) Thanks [@johngrantuk](https://github.com/johngrantuk)! - Allow using EIP-1559 transactions on chains with 0 base fee.

## 1.2.9

### Patch Changes

- [`d24e5bc4`](https://github.com/wagmi-dev/viem/commit/d24e5bc48100afb62a25c8515874be9fddb4c7c3) Thanks [@jxom](https://github.com/jxom)! - Fixed a race condition in `waitForTransactionReceipt` causing multiple parallel instances to not resolve.

## 1.2.8

### Patch Changes

- [#755](https://github.com/wagmi-dev/viem/pull/755) [`064cc09e`](https://github.com/wagmi-dev/viem/commit/064cc09e40dfb0b436b84c01aafdb448928153b3) Thanks [@aaronmgdr](https://github.com/aaronmgdr)! - Added serializer for Celo CIP-42 transactions.

* [#822](https://github.com/wagmi-dev/viem/pull/822) [`9a1e42bd`](https://github.com/wagmi-dev/viem/commit/9a1e42bd5d3ceef6527e04275499bef5ff4b4a39) Thanks [@RielJ](https://github.com/RielJ)! - Added ability to pass `value` to `deployContract`.

## 1.2.7

### Patch Changes

- [#825](https://github.com/wagmi-dev/viem/pull/825) [`d9e0a64c`](https://github.com/wagmi-dev/viem/commit/d9e0a64c30011d60f873008ec68baa324f70b7ad) Thanks [@tmm](https://github.com/tmm)! - Exported types.

* [#824](https://github.com/wagmi-dev/viem/pull/824) [`9dcec526`](https://github.com/wagmi-dev/viem/commit/9dcec5262c57085f6ff9f220471891e8805ba6b5) Thanks [@frangio](https://github.com/frangio)! - Added missing `package.json#peerDependenciesMeta`.

## 1.2.6

### Patch Changes

- [#808](https://github.com/wagmi-dev/viem/pull/808) [`7567f58e`](https://github.com/wagmi-dev/viem/commit/7567f58e808b5cf67e46c151bf0569a2820be7bd) Thanks [@jxom](https://github.com/jxom)! - Fixed `RpcTransaction` type to not include `typeHex`.

* [#808](https://github.com/wagmi-dev/viem/pull/808) [`7567f58e`](https://github.com/wagmi-dev/viem/commit/7567f58e808b5cf67e46c151bf0569a2820be7bd) Thanks [@jxom](https://github.com/jxom)! - Fixed an issue where `TransactionRequest` did not narrow based on type.

## 1.2.5

### Patch Changes

- [`81282fc1`](https://github.com/wagmi-dev/viem/commit/81282fc1d9cd4187e2caed051f221b2d4e57ec3a) Thanks [@jxom](https://github.com/jxom)! - Exported `signatureToHex`.

## 1.2.4

### Patch Changes

- [`11c844a1`](https://github.com/wagmi-dev/viem/commit/11c844a1804270bfafa903061d1f98605067203d) Thanks [@jxom](https://github.com/jxom)! - Exported `sign` in `viem/accounts`.

## 1.2.3

### Patch Changes

- [#802](https://github.com/wagmi-dev/viem/pull/802) [`b610634c`](https://github.com/wagmi-dev/viem/commit/b610634c62547178fe3737dbb37fb8db302e30c6) Thanks [@tmm](https://github.com/tmm)! - Bumped dependencies and exported types.

## 1.2.2

### Patch Changes

- [`5a8f59d5`](https://github.com/wagmi-dev/viem/commit/5a8f59d5e1d9df27c6897637346dbfe0bfcb2e62) Thanks [@tmm](https://github.com/tmm)! - Exported type

## 1.2.1

### Patch Changes

- [`96cb7534`](https://github.com/wagmi-dev/viem/commit/96cb7534c1be9ab635e70ad463551a29b7f2c553) Thanks [@jxom](https://github.com/jxom)! - Fixed multicall with ABI overrides.

## 1.2.0

### Minor Changes

- [#791](https://github.com/wagmi-dev/viem/pull/791) [`98fd9172`](https://github.com/wagmi-dev/viem/commit/98fd9172045c344429d5a716f497e422d85c0348) Thanks [@jxom](https://github.com/jxom)! - Implemented ability to "extend" Clients via `client.extend` & refactored Actions to accept a tree-shakable Client.

## 1.1.8

### Patch Changes

- [#783](https://github.com/wagmi-dev/viem/pull/783) [`91e85c76`](https://github.com/wagmi-dev/viem/commit/91e85c76df0ee665fb26dbadd473da5ec87e5029) Thanks [@izayl](https://github.com/izayl)! - Added a static `code` property to RPC Error classes.

## 1.1.7

### Patch Changes

- [`d0b4619e`](https://github.com/wagmi-dev/viem/commit/d0b4619e55ee697c9b8e03e9818b93c6a25b3ba2) Thanks [@jxom](https://github.com/jxom)! - Exported `decodeDeployData`.

## 1.1.6

### Patch Changes

- [`ec58ed1b`](https://github.com/wagmi-dev/viem/commit/ec58ed1b8be60973817ff401f1bf340fda854208) Thanks [@jxom](https://github.com/jxom)! - Fixed type narrowing on EIP1474 schemas

## 1.1.5

### Patch Changes

- [`c4e996b8`](https://github.com/wagmi-dev/viem/commit/c4e996b85404f4083e58c51ea98ac556d8ecd436) Thanks [@jxom](https://github.com/jxom)! - Fixed errorneous type defition being generated by `tsc`.

## 1.1.4

### Patch Changes

- [`75745a60`](https://github.com/wagmi-dev/viem/commit/75745a60fc83a13c3bec20ff04829b82d0852c07) Thanks [@jxom](https://github.com/jxom)! - Lax `parseUnits` value parameter.

## 1.1.3

### Patch Changes

- [#758](https://github.com/wagmi-dev/viem/pull/758) [`67b628df`](https://github.com/wagmi-dev/viem/commit/67b628df19edead79d8c6ef4755b407b3ce0486f) Thanks [@jxom](https://github.com/jxom)! - Added support for empty string in EIP712Domain name field.

## 1.1.2

### Patch Changes

- [`c974c25f`](https://github.com/wagmi-dev/viem/commit/c974c25ff28f9eec5bf5d4030146db2b215614d5) Thanks [@jxom](https://github.com/jxom)! - Added `zora` as a supported chain.

## 1.1.1

### Patch Changes

- [`5dd98d3e`](https://github.com/wagmi-dev/viem/commit/5dd98d3e57e993a7cae27030c8c10944cf5e204b) Thanks [@jxom](https://github.com/jxom)! - Exported `formatLog`

## 1.1.0

### Minor Changes

- [#691](https://github.com/wagmi-dev/viem/pull/691) [`6e65789f`](https://github.com/wagmi-dev/viem/commit/6e65789fb596ac3e64a9e5e7de1c18257fa50a59) Thanks [@aaronmgdr](https://github.com/aaronmgdr)! - Added custom chain serializers via `chain.serializers`.

* [#740](https://github.com/wagmi-dev/viem/pull/740) [`d435351d`](https://github.com/wagmi-dev/viem/commit/d435351d8637e096b1542da8bb1762858d006363) Thanks [@jxom](https://github.com/jxom)! - Added support for Optimism Deposit Transactions.

### Patch Changes

- [#709](https://github.com/wagmi-dev/viem/pull/709) [`043b2cba`](https://github.com/wagmi-dev/viem/commit/043b2cbaf8877ae67cf163d2ea19df9f08eb3808) Thanks [@jxom](https://github.com/jxom)! - Refactored serializable/serialized transaction types.

* [#735](https://github.com/wagmi-dev/viem/pull/735) [`e7ee66c8`](https://github.com/wagmi-dev/viem/commit/e7ee66c8f92262def25fe59403f19ecfbac47ad8) Thanks [@holic](https://github.com/holic)! - Fixed block formatting in `watchBlocks` for WebSocket subscriptions.

- [`1f3f2834`](https://github.com/wagmi-dev/viem/commit/1f3f2834a443165a71b27d2d0d46fa13532ccdd1) Thanks [@jxom](https://github.com/jxom)! - Added `typeHex` to `Transaction` type.

## 1.0.7

### Patch Changes

- [#707](https://github.com/wagmi-dev/viem/pull/707) [`3fc045d1`](https://github.com/wagmi-dev/viem/commit/3fc045d152a11edb698bd86aecb38909f6a3f811) Thanks [@tmm](https://github.com/tmm)! - Made TypeScript requirement explicit (was missing previously).

## 1.0.6

### Patch Changes

- [`90fd40ba`](https://github.com/wagmi-dev/viem/commit/90fd40ba0d5b7e248c7494ca5cbfa46eac281753) Thanks [@jxom](https://github.com/jxom)! - Fixed potential nullish `chainId` conflict in `sendTransaction` (for Local Accounts).

## 1.0.5

### Patch Changes

- [#699](https://github.com/wagmi-dev/viem/pull/699) [`79d1b4af`](https://github.com/wagmi-dev/viem/commit/79d1b4af5037eee4b408af9d0e3cf5e228d2601d) Thanks [@jxom](https://github.com/jxom)! - Support custom transaction formatters on `sendUnsignedTransaction`.

## 1.0.4

### Patch Changes

- [`8407fdcc`](https://github.com/wagmi-dev/viem/commit/8407fdcc16e97a5346a07382c25cb1681a50d5e8) Thanks [@jxom](https://github.com/jxom)! - Fixed fraction length overflow edge-case.

## 1.0.3

### Patch Changes

- [#687](https://github.com/wagmi-dev/viem/pull/687) [`a274ab33`](https://github.com/wagmi-dev/viem/commit/a274ab335688ce84d7fa8ca72427de7fe9937b13) Thanks [@jeetiss](https://github.com/jeetiss)! - Added `/*#__PURE__*/` annotatations for better tree-shaking

* [#672](https://github.com/wagmi-dev/viem/pull/672) [`e033f467`](https://github.com/wagmi-dev/viem/commit/e033f467082bcfa6f42c490ede1d7df50f497456) Thanks [@sambacha](https://github.com/sambacha)! - Turned off `esModuleInterop` & `allowSyntheticDefaultImports` in tsconfig.

- [#683](https://github.com/wagmi-dev/viem/pull/683) [`fe259a0e`](https://github.com/wagmi-dev/viem/commit/fe259a0ed6e4f7e264a7c5c761fea3a8ca68efc9) Thanks [@jeetiss](https://github.com/jeetiss)! - Marked package as side effects free

## 1.0.2

### Patch Changes

- [#677](https://github.com/wagmi-dev/viem/pull/677) [`a0a2ebb`](https://github.com/wagmi-dev/viem/commit/a0a2ebb6b53354be1c1492eed3bfd1b218ac71e4) Thanks [@hexcowboy](https://github.com/hexcowboy)! - Added ability to pass an `AbiFunction` to `getFunctionSelector`, and `AbiEvent` to `getEventSelector`.

## 1.0.1

### Patch Changes

- [#675](https://github.com/wagmi-dev/viem/pull/675) [`61429677`](https://github.com/wagmi-dev/viem/commit/61429677b28ad5ce8240a4278ef0f0cc1587b57a) Thanks [@tmm](https://github.com/tmm)! - Fixed payable `value` type inference.

## 1.0.0

### [Migration Guide](https://viem.sh/docs/migration-guide.html)

### Major Changes

- [#576](https://github.com/wagmi-dev/viem/pull/576) [`7d42767`](https://github.com/wagmi-dev/viem/commit/7d4276775a6d42cfab850498e522fe31134f0880) Thanks [@jxom](https://github.com/jxom)! - Released v1.

* [#576](https://github.com/wagmi-dev/viem/pull/576) [`7d42767`](https://github.com/wagmi-dev/viem/commit/7d4276775a6d42cfab850498e522fe31134f0880) Thanks [@jxom](https://github.com/jxom)! - **Breaking (edge case):** `decodeEventLog` no longer attempts to partially decode events. If the log does not conform to the ABI (mismatch between the number of indexed/non-indexed arguments to topics/data), it will throw an error.

- [#576](https://github.com/wagmi-dev/viem/pull/576) [`7d42767`](https://github.com/wagmi-dev/viem/commit/7d4276775a6d42cfab850498e522fe31134f0880) Thanks [@jxom](https://github.com/jxom)! - **Breaking:** `logIndex` & `transactionIndex` on `Log` now return a `number` instead of a `bigint`

* [#576](https://github.com/wagmi-dev/viem/pull/576) [`7d42767`](https://github.com/wagmi-dev/viem/commit/7d4276775a6d42cfab850498e522fe31134f0880) Thanks [@jxom](https://github.com/jxom)! - **Breaking:** Removed `ethersWalletToAccount` adapter.

  This adapter was introduced when viem did not have Private Key & HD Accounts. Since 0.2, viem provides all the utilities needed to create and import [Private Key](https://viem.sh/docs/accounts/privateKey.html) & [HD Accounts](https://viem.sh/docs/accounts/mnemonic.html).

  If you still need it, you can copy + paste the [old implementation](https://github.com/wagmi-dev/viem/blob/a9a71507032db896295fa1f3fa2dd6c2bdc85137/src/adapters/ethers.ts).

### Patch Changes

- [#576](https://github.com/wagmi-dev/viem/pull/576) [`7d42767`](https://github.com/wagmi-dev/viem/commit/7d4276775a6d42cfab850498e522fe31134f0880) Thanks [@jxom](https://github.com/jxom)! - Added Batch JSON-RPC on `http` Transport.

* [#657](https://github.com/wagmi-dev/viem/pull/657) [`af48368`](https://github.com/wagmi-dev/viem/commit/af48368f07856e50cb7afa8cac077e3a0ecc05fb) Thanks [@izayl](https://github.com/izayl)! - Fixed `getAbiItem` from returning mismatched type when overload with different lengths.

- [#576](https://github.com/wagmi-dev/viem/pull/576) [`7d42767`](https://github.com/wagmi-dev/viem/commit/7d4276775a6d42cfab850498e522fe31134f0880) Thanks [@jxom](https://github.com/jxom)! - Upgraded ENS Universal Resolver contract address.

* [#576](https://github.com/wagmi-dev/viem/pull/576) [`7d42767`](https://github.com/wagmi-dev/viem/commit/7d4276775a6d42cfab850498e522fe31134f0880) Thanks [@jxom](https://github.com/jxom)! - Added support for labels larger than 255 bytes when resolving ENS names.

- [#576](https://github.com/wagmi-dev/viem/pull/576) [`7d42767`](https://github.com/wagmi-dev/viem/commit/7d4276775a6d42cfab850498e522fe31134f0880) Thanks [@jxom](https://github.com/jxom)! - Added a `strict` parameter to `getLogs`, `createEventFilter` & `createContractEventFilter`.

  When `strict` mode is turned **on**, only logs that conform to the indexed/non-indexed arguments on the event definition/ABI (`event`) will be returned.
  When `strict` mode is turned **off (default)**, logs that do not conform to the indexed/non-indexed arguments on the event definition/ABI (`event`) will be included, but the `args` property will be `undefined` (as we cannot decode these events).

* [#576](https://github.com/wagmi-dev/viem/pull/576) [`7d42767`](https://github.com/wagmi-dev/viem/commit/7d4276775a6d42cfab850498e522fe31134f0880) Thanks [@jxom](https://github.com/jxom)! - Refactored EIP1193 request fn types.

## 0.3.50

### Patch Changes

- [`7dc25b5`](https://github.com/wagmi-dev/viem/commit/7dc25b56ae5f8c69255f6ebc404fb49c33cb13b7) Thanks [@jxom](https://github.com/jxom)! - Improved Ganache test actions.

## 0.3.49

### Patch Changes

- [`0b92f3a`](https://github.com/wagmi-dev/viem/commit/0b92f3ad535a27e1b8ba70fc3f6e1087ed2cd05f) Thanks [@jxom](https://github.com/jxom)! - Added more chains from @wagmi/chains.

## 0.3.47

### Patch Changes

- [`cc256c0`](https://github.com/wagmi-dev/viem/commit/cc256c0a0dd5cb99975c5a497e5eb025990deaff) Thanks [@jxom](https://github.com/jxom)! - Fixed unit conversion.

## 0.3.46

### Patch Changes

- [`770c3d1e`](https://github.com/wagmi-dev/viem/commit/770c3d1e1954b94dea6a58e7180b8600e910ad4e) Thanks [@jxom](https://github.com/jxom)! - Bumped `@wagmi/chains`.

## 0.3.45

### Patch Changes

- [#637](https://github.com/wagmi-dev/viem/pull/637) [`bbd8f07`](https://github.com/wagmi-dev/viem/commit/bbd8f072f92f189c0b55d5e3cf8c9e4f38b1c6bc) Thanks [@jxom](https://github.com/jxom)! - Updated `abitype` to 0.8.7.

## 0.3.44

### Patch Changes

- [#610](https://github.com/wagmi-dev/viem/pull/610) [`06ee89c5`](https://github.com/wagmi-dev/viem/commit/06ee89c53a5f0226407b915cdf9da5550ed58010) Thanks [@jxom](https://github.com/jxom)! - Added ability to hash data representation of `message` via a `raw` attribute in `signMessage`, `verifyMessage`, `recoverMessageAddress`.

  ```ts
  await walletClient.signMessage({
    message: { raw: "0x68656c6c6f20776f726c64" }
  });
  ```

## 0.3.43

### Patch Changes

- [#632](https://github.com/wagmi-dev/viem/pull/632) [`2538548`](https://github.com/wagmi-dev/viem/commit/2538548a5c6a897a8a2c5a0e5ea6398c86b54c59) Thanks [@tmm](https://github.com/tmm)! - Exported missing portable type.

* [#630](https://github.com/wagmi-dev/viem/pull/630) [`a446a50`](https://github.com/wagmi-dev/viem/commit/a446a50ad8fe0b6c4a20df82e37a0492995840a4) Thanks [@tmm](https://github.com/tmm)! - Narrowed contract instance address.

## 0.3.42

### Patch Changes

- [#619](https://github.com/wagmi-dev/viem/pull/619) [`73c7f498`](https://github.com/wagmi-dev/viem/commit/73c7f4980ebc755068b8cf9df70390d1e2ab2524) Thanks [@sakulstra](https://github.com/sakulstra)! - Added `address` and `abi` properties to Contract Instances.

## 0.3.41

### Patch Changes

- [`1b3f584`](https://github.com/wagmi-dev/viem/commit/1b3f5847a44ba051f19d42dfb03962a4c6a4e36b) Thanks [@jxom](https://github.com/jxom)! - Fixed `chainId` type on Transaction types.

## 0.3.40

### Patch Changes

- [#608](https://github.com/wagmi-dev/viem/pull/608) [`6e9313b`](https://github.com/wagmi-dev/viem/commit/6e9313b8ed13f930666a06991ed0cd61ab286de0) Thanks [@tmm](https://github.com/tmm)! - Exported types

## 0.3.39

### Patch Changes

- [#603](https://github.com/wagmi-dev/viem/pull/603) [`ee2b2b8`](https://github.com/wagmi-dev/viem/commit/ee2b2b8c2eba540cc73ef78e29870f3314a008c3) Thanks [@ilamanov](https://github.com/ilamanov)! - Fixed `getFunctionSelector` for functions with no arguments.

## 0.3.38

### Patch Changes

- [#598](https://github.com/wagmi-dev/viem/pull/598) [`baea299`](https://github.com/wagmi-dev/viem/commit/baea2991ce405015e4f68c2fde90a154b698e7a4) Thanks [@iuriiiurevich](https://github.com/iuriiiurevich)! - Fixed an issue in `withCache` where the promise cache would not clear upon rejection.

## 0.3.37

### Patch Changes

- [#572](https://github.com/wagmi-dev/viem/pull/572) [`3e5bcbf`](https://github.com/wagmi-dev/viem/commit/3e5bcbf1233ea3cc8674767c10bd8dccdfd99182) Thanks [@tmm](https://github.com/tmm)! - Fixed contract instance `estimateGas` typing.

## 0.3.36

### Patch Changes

- [#554](https://github.com/wagmi-dev/viem/pull/554) [`d5297c6`](https://github.com/wagmi-dev/viem/commit/d5297c6e32fc148a63c34fe47cd590cfc9c665ec) Thanks [@tmm](https://github.com/tmm)! - Fixed portable types

* [#556](https://github.com/wagmi-dev/viem/pull/556) [`81a3aed`](https://github.com/wagmi-dev/viem/commit/81a3aed513167588f0c3433af8407cc23c78f61f) Thanks [@tmm](https://github.com/tmm)! - Fallback to `client.account` for `estimateGas`.

- [#560](https://github.com/wagmi-dev/viem/pull/560) [`a5dd3c6`](https://github.com/wagmi-dev/viem/commit/a5dd3c6dcdb2c7625aacd9c9bc498bd86530dd77) Thanks [@Volchunovich](https://github.com/Volchunovich)! - Fixed docs links

## 0.3.35

### Patch Changes

- [`1cc1dc2`](https://github.com/wagmi-dev/viem/commit/1cc1dc2e989765ea0d0afd72375505b93e0013a5) Thanks [@jxom](https://github.com/jxom)! - Fixed `account` parameter type on `readContract`.

## 0.3.34

### Patch Changes

- [`5c75ee5`](https://github.com/wagmi-dev/viem/commit/5c75ee598a0bd09709f619464e48cbb5fa2327d8) Thanks [@jxom](https://github.com/jxom)! - Added `EstimateContractGasParameters` & `EstimateContractGasReturnType` types.

## 0.3.33

### Patch Changes

- [`0cb8f31`](https://github.com/wagmi-dev/viem/commit/0cb8f31589d65d056de66c13637635785d97b730) Thanks [@jxom](https://github.com/jxom)! - Fixed an issue where `watchContractEvent` would throw a serialize error for bigint args.

## 0.3.32

### Patch Changes

- [`fb5b321`](https://github.com/wagmi-dev/viem/commit/fb5b321a9238d68a59f387632dd89ccb626a8cb5) Thanks [@jxom](https://github.com/jxom)! - Allowed recovery id as v when recovering public key.

* [`9df44ce`](https://github.com/wagmi-dev/viem/commit/9df44cea3843a74f9e04591d3c683db1982269fb) Thanks [@jxom](https://github.com/jxom)! - Added `ganache` as another mode for Test Client

## 0.3.31

### Patch Changes

- [#540](https://github.com/wagmi-dev/viem/pull/540) [`0d8f154`](https://github.com/wagmi-dev/viem/commit/0d8f154fbcbf68f8f8b1b8bde0cf5661ffc44370) Thanks [@jxom](https://github.com/jxom)! - Added proxy packages to support bundlers that are not compatible with `package.json#exports`.

## 0.3.30

### Patch Changes

- [`228d949`](https://github.com/wagmi-dev/viem/commit/228d949bce648065ecef629173d1b847e2fc8f21) Thanks [@jxom](https://github.com/jxom)! - Bumped `waitForTransactionReceipt` retry count.

## 0.3.29

### Patch Changes

- [#527](https://github.com/wagmi-dev/viem/pull/527) [`840d3d7`](https://github.com/wagmi-dev/viem/commit/840d3d7411a33ad02c71bd180b53244df91cd779) Thanks [@jxom](https://github.com/jxom)! - Fixed `trim` to trim trailing zero byte data instead of all trailing zeros.

## 0.3.28

### Patch Changes

- [`ffee4f8`](https://github.com/wagmi-dev/viem/commit/ffee4f86928ada54d2c6a4403aafa7b861eeccb2) Thanks [@jxom](https://github.com/jxom)! - Bumped `waitForTransactionReceipt` exponential backoff scalar

## 0.3.27

### Patch Changes

- [#519](https://github.com/wagmi-dev/viem/pull/519) [`2ab7b56`](https://github.com/wagmi-dev/viem/commit/2ab7b56ea6828f92e10f287bac68f1f70815da1a) Thanks [@jxom](https://github.com/jxom)! - Batched websocket initialization.

* [#518](https://github.com/wagmi-dev/viem/pull/518) [`65a0896`](https://github.com/wagmi-dev/viem/commit/65a0896426a28e2d11438984a6ed6b604d87c316) Thanks [@jxom](https://github.com/jxom)! - Added `strict` option to `isHex` & optimized data utilities.

- [#515](https://github.com/wagmi-dev/viem/pull/515) [`c1b81dc`](https://github.com/wagmi-dev/viem/commit/c1b81dc36ad787b632099a98ba2b4bd5e03ddafa) Thanks [@jxom](https://github.com/jxom)! - Optimized `getTransaction` strategy in `waitForTransactionReceipt`.

## 0.3.26

### Patch Changes

- [#500](https://github.com/wagmi-dev/viem/pull/500) [`1da5831`](https://github.com/wagmi-dev/viem/commit/1da583137a32f381a2e2e5f260105ce8542bbaee) Thanks [@jxom](https://github.com/jxom)! - refactor: lax log types

## 0.3.25

### Patch Changes

- [#506](https://github.com/wagmi-dev/viem/pull/506) [`f396e5d`](https://github.com/wagmi-dev/viem/commit/f396e5d242bbf68a4b34596db6943d52fee19e79) Thanks [@jxom](https://github.com/jxom)! - Support suffixed data in `decodeAbiParameters`.

## 0.3.24

### Patch Changes

- [`9852bcd`](https://github.com/wagmi-dev/viem/commit/9852bcdfb83bfdda43fb276b3a1266b30592d56e) Thanks [@jxom](https://github.com/jxom)! - Fixed custom solidity errors with no args.

## 0.3.23

### Patch Changes

- [#489](https://github.com/wagmi-dev/viem/pull/489) [`d130c72`](https://github.com/wagmi-dev/viem/commit/d130c7277bbb175b7ce82fe2c32ad9f65b3ae63f) Thanks [@tmm](https://github.com/tmm)! - Improved RpcError code types.

* [`670d825`](https://github.com/wagmi-dev/viem/commit/670d825aa8105a6fc5e4fedc540d055d28ec91e1) Thanks [@jxom](https://github.com/jxom)! - Fixed \`call\` revert data for node clients that have nested error data.

- [#487](https://github.com/wagmi-dev/viem/pull/487) [`566e77d`](https://github.com/wagmi-dev/viem/commit/566e77dfafcd5b5486260e492d8db890b788b264) Thanks [@kdembler](https://github.com/kdembler)! - fix encodeEventTopics for leading non-indexed args

## 0.3.22

### Patch Changes

- [`9ae5eaa`](https://github.com/wagmi-dev/viem/commit/9ae5eaa1465240d07577d380e7387f1a065707e3) Thanks [@jxom](https://github.com/jxom)! - Fixed `functionName` type inference in `SimulateContractReturnType`.

## 0.3.21

### Patch Changes

- [#475](https://github.com/wagmi-dev/viem/pull/475) [`64a2f51`](https://github.com/wagmi-dev/viem/commit/64a2f51799431faf28946127a3d62373051d8553) Thanks [@jxom](https://github.com/jxom)! - Fixed \`hashMessage\` string conversion for messages that have same format as hex bytes.

* [#474](https://github.com/wagmi-dev/viem/pull/474) [`1886095`](https://github.com/wagmi-dev/viem/commit/18860951b7276c5b67632113f96a09cda3a48d25) Thanks [@jxom](https://github.com/jxom)! - Exported `assertCurrentChain` util.

## 0.3.20

### Patch Changes

- [#470](https://github.com/wagmi-dev/viem/pull/470) [`be9501e`](https://github.com/wagmi-dev/viem/commit/be9501eb3b509a0fe09dd087ee46d11642a9c408) Thanks [@jxom](https://github.com/jxom)! - Fixed issue where `waitForTransactionReceipt` would throw immediately for RPC Providers which may be slow to sync mined transactions.

## 0.3.19

### Patch Changes

- [#320](https://github.com/wagmi-dev/viem/pull/320) [`6d6d092`](https://github.com/wagmi-dev/viem/commit/6d6d092c6cacb229bb2696261ae9dbe742c26647) Thanks [@janek26](https://github.com/janek26)! - Added support for Contract Wallet signature verification (EIP-6492) via `publicClient.verifyMessage` & `publicClient.verifyTypedData`.

## 0.3.18

### Patch Changes

- [#445](https://github.com/wagmi-dev/viem/pull/445) [`9e096a9`](https://github.com/wagmi-dev/viem/commit/9e096a92e2722e0dd0acd5ab79d5907e7d9bc82f) Thanks [@jxom](https://github.com/jxom)! - Refactored contract decoding utility types.

* [#448](https://github.com/wagmi-dev/viem/pull/448) [`29cf036`](https://github.com/wagmi-dev/viem/commit/29cf0363f0bfe89f0d63a281272151c6bba47ce1) Thanks [@jxom](https://github.com/jxom)! - Refactored inferred types on `Log` (eventName, args, topics), `getLogs`, `getFilterLogs` & `getFilterChanges`.

- [#435](https://github.com/wagmi-dev/viem/pull/435) [`711cf94`](https://github.com/wagmi-dev/viem/commit/711cf9460a262fb12c520d7860f22915fb4c58f6) Thanks [@Raiden1411](https://github.com/Raiden1411)! - Updated `abitype` to `0.8.2` and exported abitype errors.

* [#445](https://github.com/wagmi-dev/viem/pull/445) [`9e096a9`](https://github.com/wagmi-dev/viem/commit/9e096a92e2722e0dd0acd5ab79d5907e7d9bc82f) Thanks [@jxom](https://github.com/jxom)! - Made "name" parameter (`eventName`, `functionName`, etc) optional on contract encoding/decoding utilities when only one ABI item is provided.

## 0.3.17

### Patch Changes

- [#443](https://github.com/wagmi-dev/viem/pull/443) [`ca0cb85`](https://github.com/wagmi-dev/viem/commit/ca0cb852999dd90aebdb938d8bf4dbbec504a173) Thanks [@jxom](https://github.com/jxom)! - Fixed eth_call & eth_estimateGas calls for nodes that conform to the older JSON-RPC spec.

## 0.3.16

### Patch Changes

- [`482aaa1`](https://github.com/wagmi-dev/viem/commit/482aaa1651ff06575860c6d9d38bcde05e5b136e) Thanks [@jxom](https://github.com/jxom)! - Wrapped slice offset out-of-bounds error in a `BaseError`.

## 0.3.15

### Patch Changes

- [#436](https://github.com/wagmi-dev/viem/pull/436) [`72ed656`](https://github.com/wagmi-dev/viem/commit/72ed6567897ee87939d33e89a7d6599ec8db321e) Thanks [@jxom](https://github.com/jxom)! - Fixed an issue where `multicall`'s return type was incorrectly flattening when `allowFailure: false`.

## 0.3.14

### Patch Changes

- [#426](https://github.com/wagmi-dev/viem/pull/426) [`840d19d`](https://github.com/wagmi-dev/viem/commit/840d19d652819001addfe9c47267d9e7c71841bd) Thanks [@izayl](https://github.com/izayl)! - Added constants zeroAddress.

* [#424](https://github.com/wagmi-dev/viem/pull/424) [`2eb73f6`](https://github.com/wagmi-dev/viem/commit/2eb73f6f449be7f00790c992202816d5eccf5232) Thanks [@fubhy](https://github.com/fubhy)! - Removed the `defineChain` export from `viem/chains`.

- [#427](https://github.com/wagmi-dev/viem/pull/427) [`41bc9e3`](https://github.com/wagmi-dev/viem/commit/41bc9e38dcbd71d10ea28edaaad48fb81d40f61b) Thanks [@jxom](https://github.com/jxom)! - Added support for EIP-3668 CCIP Read.

* [#431](https://github.com/wagmi-dev/viem/pull/431) [`31aafb3`](https://github.com/wagmi-dev/viem/commit/31aafb3514adff65bc4c27b78dad90057ee97421) Thanks [@jxom](https://github.com/jxom)! - Added a `dataSuffix` argument to `writeContract` and `simulateContract`

## 0.3.13

### Patch Changes

- [`eb32e6c`](https://github.com/wagmi-dev/viem/commit/eb32e6c8a412aa4d16339236d4a14d820a26fdc1) Thanks [@fubhy](https://github.com/fubhy)! - Fixed `mine()` to resolve to `undefined` instead of `null`.

## 0.3.12

### Patch Changes

- [`6f8151c`](https://github.com/wagmi-dev/viem/commit/6f8151c58fcb5e14b7a954df6e941fe3cca4054c) Thanks [@jxom](https://github.com/jxom)! - Flagged 403 as non-deterministic error for `fallback` Transport.

## 0.3.11

### Patch Changes

- [#404](https://github.com/wagmi-dev/viem/pull/404) [`2c380cf`](https://github.com/wagmi-dev/viem/commit/2c380cf0f0e528d6ff9e9c354e4fcec28df5329b) Thanks [@izayl](https://github.com/izayl)! - Added support for EIP-1191 address checksum.

* [#398](https://github.com/wagmi-dev/viem/pull/398) [`cbb4f1f`](https://github.com/wagmi-dev/viem/commit/cbb4f1f66b80914313e54bf7022e59a1b0bee2d3) Thanks [@jxom](https://github.com/jxom)! - Added a new `batchSize` parameter to `multicall` which limits the size of each calldata chunk.

## 0.3.10

### Patch Changes

- [`777fa34`](https://github.com/wagmi-dev/viem/commit/777fa34c9ce5630696e554127e39e5e9386ad74e) Thanks [@jxom](https://github.com/jxom)! - Fixed wallet_watchAsset type.

## 0.3.9

### Patch Changes

- [`b4d6623`](https://github.com/wagmi-dev/viem/commit/b4d662360f55d5963e015f7080538a167e89b1f6) Thanks [@jxom](https://github.com/jxom)! - Fixed multicall return type.

## 0.3.8

### Patch Changes

- [`8371ad9`](https://github.com/wagmi-dev/viem/commit/8371ad9cb6987b5876a679ba502a80573c92ec64) Thanks [@jxom](https://github.com/jxom)! - Fixed WebSocket import on Vite environments.

## 0.3.7

### Patch Changes

- [#399](https://github.com/wagmi-dev/viem/pull/399) [`eefd839`](https://github.com/wagmi-dev/viem/commit/eefd83997a98113b81d5ba21a8b5492a1de2284c) Thanks [@jxom](https://github.com/jxom)! - Fixed async imports in Vite environments.

* [#397](https://github.com/wagmi-dev/viem/pull/397) [`69b95ed`](https://github.com/wagmi-dev/viem/commit/69b95ed5991c712d11ff4de1bb873c9a2af152b3) Thanks [@tmm](https://github.com/tmm)! - Made `value` required for payable functions.

## 0.3.6

### Patch Changes

- [`ae6d388`](https://github.com/wagmi-dev/viem/commit/ae6d3883ec41dfdd3750a5f7473495d011df5802) Thanks [@jxom](https://github.com/jxom)! - Fixed unpublished type declarations.

## 0.3.5

### Patch Changes

- [`0d38807`](https://github.com/wagmi-dev/viem/commit/0d38807bcd61fae5c5d4736aed6c59277c9b4bf4) Thanks [@jxom](https://github.com/jxom)! - Fixed `batch` config in `createPublicClient`.

## 0.3.4

### Patch Changes

- [#387](https://github.com/wagmi-dev/viem/pull/387) [`230fcfd`](https://github.com/wagmi-dev/viem/commit/230fcfd97bb4937502e604630bb97695198e7b7e) Thanks [@jxom](https://github.com/jxom)! - Added support for `eth_call` batch aggregation via multicall `aggregate3`.

* [#388](https://github.com/wagmi-dev/viem/pull/388) [`bc254d8`](https://github.com/wagmi-dev/viem/commit/bc254d882bed6216daa72d5820526e6573a34e85) Thanks [@jxom](https://github.com/jxom)! - Added `size` as an argument to hex/bytes encoding/decoding utilities.

- [`03816ec`](https://github.com/wagmi-dev/viem/commit/03816ec421eb8adbcb17bd44c5dc344407acba2d) Thanks [@jxom](https://github.com/jxom)! - Disabled `fallback` transport ranking by default.

## 0.3.3

### Patch Changes

- [#383](https://github.com/wagmi-dev/viem/pull/383) [`7e9731c`](https://github.com/wagmi-dev/viem/commit/7e9731cf315ddcd10f35c81c63a15af6aa78350d) Thanks [@Raiden1411](https://github.com/Raiden1411)! - Fixed an issue where `serializeTransaction` was incorrectly encoding zero-ish properties.

## 0.3.2

### Patch Changes

- [#375](https://github.com/wagmi-dev/viem/pull/375) [`f9bedc9`](https://github.com/wagmi-dev/viem/commit/f9bedc94ecd41fdcb2f0fed1d90162567c2a31ea) Thanks [@fubhy](https://github.com/fubhy)! - Support edge runtime

## 0.3.1

### Patch Changes

- [`6856443`](https://github.com/wagmi-dev/viem/commit/6856443fb75421639c9622343d5958791028874c) Thanks [@jxom](https://github.com/jxom)! - Added `recoverPublicKey`.

* [#363](https://github.com/wagmi-dev/viem/pull/363) [`ee1cb7f`](https://github.com/wagmi-dev/viem/commit/ee1cb7ff546236041b1ca115bb2a252520e8ef7f) Thanks [@tmm](https://github.com/tmm)! - Added inference to `getLogs` `event` type.

- [#365](https://github.com/wagmi-dev/viem/pull/365) [`f4dcc33`](https://github.com/wagmi-dev/viem/commit/f4dcc33739a339c286f852a377f71fbf2fb7ab97) Thanks [@fubhy](https://github.com/fubhy)! - Fixed `getAbiItem` to not use a generic type variable for the return type

## 0.3.0

### Minor Changes

- [#355](https://github.com/wagmi-dev/viem/pull/355) [`b1acfc9`](https://github.com/wagmi-dev/viem/commit/b1acfc9198bfbed8c3de6e769c5ff06d7124881c) Thanks [@jxom](https://github.com/jxom)! - **Breaking:** Renamed `RequestError` to `RpcError`.
  **Breaking:** Removed `RpcRequestError` – use `RpcError` instead.
  **Breaking:** Renamed `RpcError` to `RpcRequestError`.

### Patch Changes

- [#355](https://github.com/wagmi-dev/viem/pull/355) [`b1acfc9`](https://github.com/wagmi-dev/viem/commit/b1acfc9198bfbed8c3de6e769c5ff06d7124881c) Thanks [@jxom](https://github.com/jxom)! - Added `ProviderRpcError` subclass.

  Added EIP-1193 `UnauthorizedProviderError`, `UnsupportedProviderMethodError`, `ProviderDisconnectedError`, and `ChainDisconnectedError`.

* [#349](https://github.com/wagmi-dev/viem/pull/349) [`b275811`](https://github.com/wagmi-dev/viem/commit/b2758116623567a07e9c2cae7e2471e3c6bf2ecf) Thanks [@jxom](https://github.com/jxom)! - Fixed an issue where Filter querying (`eth_getFilterChanges`, etc) was not being scoped to the Transport that created the Filter.

## 0.2.14

### Patch Changes

- [#344](https://github.com/wagmi-dev/viem/pull/344) [`bb9c2a4`](https://github.com/wagmi-dev/viem/commit/bb9c2a4b769655f230b8af22efb871393e78a80d) Thanks [@jxom](https://github.com/jxom)! - Added `EIP1193Provider` type.

## 0.2.13

### Patch Changes

- [#331](https://github.com/wagmi-dev/viem/pull/331) [`cd7b642`](https://github.com/wagmi-dev/viem/commit/cd7b64242643247c3c04896dacdd95b2a335ba52) Thanks [@jxom](https://github.com/jxom)! - Migrated to TypeScript 5.
  Migrated build process from `tsup` to `tsc`.

* [#343](https://github.com/wagmi-dev/viem/pull/343) [`579171d`](https://github.com/wagmi-dev/viem/commit/579171dbc691f9c352688455f21b6c4187dbf422) Thanks [@fubhy](https://github.com/fubhy)! - Fixed conditional types for poll options on `watchBlocks` & `watchPendingTransactions`.

## 0.2.12

### Patch Changes

- [#328](https://github.com/wagmi-dev/viem/pull/328) [`ee87fe7`](https://github.com/wagmi-dev/viem/commit/ee87fe73884297db1c3957453efd7c326924c269) Thanks [@jxom](https://github.com/jxom)! - Tweaked error inheritence for `UserRejectedRequestError` & `SwitchChainError` to be more friendly with custom errors.

## 0.2.11

### Patch Changes

- [#326](https://github.com/wagmi-dev/viem/pull/326) [`c83616a`](https://github.com/wagmi-dev/viem/commit/c83616ad33aa06054342a3bf72bcb51c09ee0ada) Thanks [@jxom](https://github.com/jxom)! - Fixed an issue where filtered logs that do not conform to the provided ABI would cause `getLogs`, `getFilterLogs` or `getFilterChanges` to throw – these logs are now skipped. See [#323](https://github.com/wagmi-dev/viem/issues/323#issuecomment-1499654052) for more info.

## 0.2.10

### Patch Changes

- [#322](https://github.com/wagmi-dev/viem/pull/322) [`ea019d7`](https://github.com/wagmi-dev/viem/commit/ea019d75c5243d8ae2b8ca1686b34026b170d903) Thanks [@tmm](https://github.com/tmm)! - Fixed properties passed to ethers adapter `signTransaction`

## 0.2.9

### Patch Changes

- [#317](https://github.com/wagmi-dev/viem/pull/317) [`2720ba5`](https://github.com/wagmi-dev/viem/commit/2720ba566d02fdb2c6ddc8d016ec252606a9cb95) Thanks [@jxom](https://github.com/jxom)! - Fixed `transports` property type on `FallbackTransport`.

## 0.2.8

### Patch Changes

- [#313](https://github.com/wagmi-dev/viem/pull/313) [`eb2280c`](https://github.com/wagmi-dev/viem/commit/eb2280cbc65b3e509b4b3871fe75b236101da442) Thanks [@jxom](https://github.com/jxom)! - Migrated from `idna-uts46-hx` to `@adraffy/ens-normalize` for `normalize`.

## 0.2.7

### Patch Changes

- [#310](https://github.com/wagmi-dev/viem/pull/310) [`6dfc225`](https://github.com/wagmi-dev/viem/commit/6dfc22537b9dd5740911b8677bba01cc477b9b23) Thanks [@jxom](https://github.com/jxom)! - Made `GetValue` return `{ value?: never }` instead of `unknown` for contract functions that are not payable.

## 0.2.6

### Patch Changes

- [#295](https://github.com/wagmi-dev/viem/pull/295) [`9a15a61`](https://github.com/wagmi-dev/viem/commit/9a15a612dd4a416f932c99519416665c0ffac214) Thanks [@fubhy](https://github.com/fubhy)! - Return discrimated union type from `decodeFunctionData`

* [#304](https://github.com/wagmi-dev/viem/pull/304) [`8e1b712`](https://github.com/wagmi-dev/viem/commit/8e1b712efc256c16a98408d10557d5f55d8927d7) Thanks [@fubhy](https://github.com/fubhy)! - Fixed `getTransactionType` to honor `undefined` EIP-1559, EIP-2930 or Legacy attributes.

- [#302](https://github.com/wagmi-dev/viem/pull/302) [`c00a459`](https://github.com/wagmi-dev/viem/commit/c00a459490ff283812e6847547149a8104a5c4d0) Thanks [@fubhy](https://github.com/fubhy)! - Fixed forwarding of options to transport for wallet client

## 0.2.5

### Patch Changes

- [#297](https://github.com/wagmi-dev/viem/pull/297) [`96d072c`](https://github.com/wagmi-dev/viem/commit/96d072cac1ae09f85afcbbca63c99f10a80f1722) Thanks [@fubhy](https://github.com/fubhy)! - Fixed wordlists exports.

## 0.2.4

### Patch Changes

- [#293](https://github.com/wagmi-dev/viem/pull/293) [`859352c`](https://github.com/wagmi-dev/viem/commit/859352c38333ec22924b24242db8f583fc73d9fb) Thanks [@TateB](https://github.com/TateB)! - Fixed ENS address resolution for when resolver returns with a null address, or resolvers that do not support `addr`. `getEnsAddress` returns `null` for these cases.

## 0.2.3

### Patch Changes

- [#290](https://github.com/wagmi-dev/viem/pull/290) [`ef2bbaf`](https://github.com/wagmi-dev/viem/commit/ef2bbafa2b372bfa8fa1b29ffabea75ca3ea1122) Thanks [@holic](https://github.com/holic)! - Fixed ENS address resolution for "0x"-prefixed names.

## 0.2.2

### Patch Changes

- [#289](https://github.com/wagmi-dev/viem/pull/289) [`8c51f93`](https://github.com/wagmi-dev/viem/commit/8c51f93cfbe304c88b018c679c4413e8874692e7) Thanks [@jxom](https://github.com/jxom)! - Pinned dependencies.

* [#289](https://github.com/wagmi-dev/viem/pull/289) [`8c51f93`](https://github.com/wagmi-dev/viem/commit/8c51f93cfbe304c88b018c679c4413e8874692e7) Thanks [@jxom](https://github.com/jxom)! - Made `@scure/bip39/wordlists/*` & `idna-uts46-hx` exports ESM friendly.

## 0.2.1

### Patch Changes

- [#285](https://github.com/wagmi-dev/viem/pull/285) [`ab9fd12`](https://github.com/wagmi-dev/viem/commit/ab9fd121fbe271ba9bee43aea2d7bba122dc4f03) Thanks [@tmm](https://github.com/tmm)! - Exported `hdKeyToAccount` and `mnemonicToAccount`.

## 0.2.0 – [Migration Guide](https://viem.sh/docs/migration-guide.html)

### Minor Changes

- [#229](https://github.com/wagmi-dev/viem/pull/229) [`098f342`](https://github.com/wagmi-dev/viem/commit/098f3423ee84f9deb09c2c7d30e950a046c07ea9) Thanks [@jxom](https://github.com/jxom)! - **Breaking:** Removed the `getAccount` function.

  **For JSON-RPC Accounts, use the address itself.**

  ```diff
  import { createWalletClient, custom } from 'viem'
  import { mainnet } from 'viem/chains'

  const address = '0xFBA3912Ca04dd458c843e2EE08967fC04f3579c2'

  const client = createWalletClient({
  - account: getAccount(address),
  + account: address,
    chain: mainnet,
    transport: custom(window.ethereum)
  })
  ```

  **For Ethers Wallet Adapter, use `ethersWalletToAccount`.**

  If you were using the Ethers Wallet adapter, you can use the `ethersWalletToAccount` function.

  > Note: viem 0.2.0 now has a [Private Key](/docs/accounts/privateKey.html) & [Mnemonic Account](/docs/accounts/mnemonic.html) implementation. You probably do not need this adapter anymore. This adapter may be removed in a future version.

  ```diff
  import { createWalletClient, custom } from 'viem'
  import { mainnet } from 'viem/chains'
  - import { getAccount } from 'viem/ethers'
  + import { ethersWalletToAccount } from 'viem/ethers'
  import { Wallet } from 'ethers'

  - const account = getAccount(new Wallet('0x...'))
  + const account = ethersWalletToAccount(new Wallet('0x...'))

  const client = createWalletClient({
    account,
    chain: mainnet,
    transport: custom(window.ethereum)
  })
  ```

  **For Local Accounts, use `toAccount`.**

  ```diff
  - import { createWalletClient, http, getAccount } from 'viem'
  + import { createWalletClient, http } from 'viem'
  + import { toAccount } from 'viem/accounts'
  import { mainnet } from 'viem/chains'
  import { getAddress, signMessage, signTransaction } from './sign-utils'

  const privateKey = '0x...'
  - const account = getAccount({
  + const account = toAccount({
    address: getAddress(privateKey),
    signMessage(message) {
      return signMessage(message, privateKey)
    },
    signTransaction(transaction) {
      return signTransaction(transaction, privateKey)
    },
    signTypedData(typedData) {
      return signTypedData(typedData, privateKey)
    }
  })

  const client = createWalletClient({
    account,
    chain: mainnet,
    transport: http()
  })
  ```

* [#229](https://github.com/wagmi-dev/viem/pull/229) [`098f342`](https://github.com/wagmi-dev/viem/commit/098f3423ee84f9deb09c2c7d30e950a046c07ea9) Thanks [@jxom](https://github.com/jxom)! - **Breaking:** Removed `assertChain` argument on `sendTransaction`, `writeContract` & `deployContract`. If you wish to bypass the chain check (not recommended unless for testing purposes), you can pass `chain: null`.

  ```diff
  await walletClient.sendTransaction({
  - assertChain: false,
  + chain: null,
    ...
  })
  ```

- [#229](https://github.com/wagmi-dev/viem/pull/229) [`098f342`](https://github.com/wagmi-dev/viem/commit/098f3423ee84f9deb09c2c7d30e950a046c07ea9) Thanks [@jxom](https://github.com/jxom)! - **Breaking:** A chain is now required for the `sendTransaction`, `writeContract`, `deployContract` Actions.

  You can hoist the Chain on the Client:

  ```diff
  import { createWalletClient, custom, getAccount } from 'viem'
  import { mainnet } from 'viem/chains'

  export const walletClient = createWalletClient({
  + chain: mainnet,
    transport: custom(window.ethereum)
  })

  const account = getAccount('0xf39fd6e51aad88f6f4ce6ab8827279cfffb92266')

  const hash = await walletClient.sendTransaction({
    account,
    to: '0x70997970c51812dc3a010c7d01b50e0d17dc79c8',
    value: 1000000000000000000n
  })
  ```

  Alternatively, you can pass the Chain directly to the Action:

  ```diff
  import { createWalletClient, custom, getAccount } from 'viem'
  import { mainnet } from 'viem/chains'

  export const walletClient = createWalletClient({
  - chain: mainnet,
    transport: custom(window.ethereum)
  })

  const account = getAccount('0xf39fd6e51aad88f6f4ce6ab8827279cfffb92266')

  const hash = await walletClient.sendTransaction({
    account,
  + chain: mainnet,
    to: '0x70997970c51812dc3a010c7d01b50e0d17dc79c8',
    value: 1000000000000000000n
  })
  ```

* [#229](https://github.com/wagmi-dev/viem/pull/229) [`098f342`](https://github.com/wagmi-dev/viem/commit/098f3423ee84f9deb09c2c7d30e950a046c07ea9) Thanks [@jxom](https://github.com/jxom)! - **Breaking:** Updated utility type names to reflect their purposes:

  - `ExtractErrorNameFromAbi` is now `InferErrorName`
  - `ExtractEventNameFromAbi` is now `InferEventName`
  - `ExtractFunctionNameFromAbi` is now `InferFunctionName`
  - `ExtractItemNameFromAbi` is now `InferItemName`
  - `ExtractConstructorArgsFromAbi` is now `GetConstructorArgs`
  - `ExtractErrorArgsFromAbi` is now `GetErrorArgs`
  - `ExtractEventArgsFromAbi` is now `GetEventArgs`
  - `ExtractEventArgsFromTopics` is now `GetEventArgsFromTopics`
  - `ExtractArgsFromAbi` is now `GetFunctionArgs`

- [#229](https://github.com/wagmi-dev/viem/pull/229) [`098f342`](https://github.com/wagmi-dev/viem/commit/098f3423ee84f9deb09c2c7d30e950a046c07ea9) Thanks [@jxom](https://github.com/jxom)! - **Breaking:** The following functions are now `async` functions instead of synchronous functions:

  - `recoverAddress`
  - `recoverMessageAddress`
  - `verifyMessage`

  ```diff
  import { recoverMessageAddress } from 'viem'

  - recoverMessageAddress({ message: 'hello world', signature: '0x...' })
  + await recoverMessageAddress({ message: 'hello world', signature: '0x...' })
  ```

### Patch Changes

- [#229](https://github.com/wagmi-dev/viem/pull/229) [`098f342`](https://github.com/wagmi-dev/viem/commit/098f3423ee84f9deb09c2c7d30e950a046c07ea9) Thanks [@jxom](https://github.com/jxom)! - Added `getEnsText` & `getEnsAvatar`

* [#229](https://github.com/wagmi-dev/viem/pull/229) [`098f342`](https://github.com/wagmi-dev/viem/commit/098f3423ee84f9deb09c2c7d30e950a046c07ea9) Thanks [@jxom](https://github.com/jxom)! - Added Local Account implementations:

  - `privateKeyToAccount`
  - `mnemonicToAccount`
  - `hdKeyToAccount`

  If you were previously relying on the `viem/ethers` wallet adapter, you no longer need to use this.

  ```diff
  - import { Wallet } from 'ethers'
  - import { getAccount } from 'viem/ethers'
  + import { privateKeyToAccount } from 'viem/accounts'

  const privateKey = '0x...'
  - const account = getAccount(new Wallet(privateKey))
  + const account = privateKeyToAccount(privateKey)

  const client = createWalletClient({
    account,
    chain: mainnet,
    transport: http()
  })
  ```

- [#229](https://github.com/wagmi-dev/viem/pull/229) [`098f342`](https://github.com/wagmi-dev/viem/commit/098f3423ee84f9deb09c2c7d30e950a046c07ea9) Thanks [@jxom](https://github.com/jxom)! - Added WebSocket `eth_subscribe` support `watchBlocks`, `watchBlockNumber`, and `watchPendingTransactions`.

* [#229](https://github.com/wagmi-dev/viem/pull/229) [`098f342`](https://github.com/wagmi-dev/viem/commit/098f3423ee84f9deb09c2c7d30e950a046c07ea9) Thanks [@jxom](https://github.com/jxom)! - Updated Client types.

- [#229](https://github.com/wagmi-dev/viem/pull/229) [`098f342`](https://github.com/wagmi-dev/viem/commit/098f3423ee84f9deb09c2c7d30e950a046c07ea9) Thanks [@jxom](https://github.com/jxom)! - Added `verifyTypedData`, `hashTypedData`, `recoverTypedDataMessage`

* [#229](https://github.com/wagmi-dev/viem/pull/229) [`098f342`](https://github.com/wagmi-dev/viem/commit/098f3423ee84f9deb09c2c7d30e950a046c07ea9) Thanks [@jxom](https://github.com/jxom)! - Added the ability to hoist an Account to the Wallet Client.

  ```diff
  import { createWalletClient, http } from 'viem'
  import { mainnnet } from 'viem/chains'

  const [account] = await window.ethereum.request({ method: 'eth_requestAccounts' })

  const client = createWalletClient({
  + account,
    chain: mainnet,
    transport: http()
  })

  const hash = await client.sendTransaction({
  - account,
    to: '0xa5cc3c03994DB5b0d9A5eEdD10CabaB0813678AC',
    value: parseEther('0.001')
  })
  ```

- [#229](https://github.com/wagmi-dev/viem/pull/229) [`098f342`](https://github.com/wagmi-dev/viem/commit/098f3423ee84f9deb09c2c7d30e950a046c07ea9) Thanks [@jxom](https://github.com/jxom)! - Added getEnsResolver

## 0.1.26

### Patch Changes

- [`93e402d`](https://github.com/wagmi-dev/viem/commit/93e402d6fddabcb6966fd8f81d7176d71241e193) Thanks [@jxom](https://github.com/jxom)! - Fixed a `decodeAbiParameters` case where static arrays with a dynamic child would consume the size of the child instead of 32 bytes.

## 0.1.25

### Patch Changes

- [#263](https://github.com/wagmi-dev/viem/pull/263) [`53fda1a`](https://github.com/wagmi-dev/viem/commit/53fda1a5366ff1122b951d8148c1a9f74f280578) Thanks [@fubhy](https://github.com/fubhy)! - Fixed issue where ABIs with constructors would throw for `decodeFunctionData`.

## 0.1.24

### Patch Changes

- [#237](https://github.com/wagmi-dev/viem/pull/237) [`a92c4fa`](https://github.com/wagmi-dev/viem/commit/a92c4fa31eb4a71cb68edf6d50a58cf653419f86) Thanks [@jxom](https://github.com/jxom)! - Added automatic ranking to `fallback` Transport.

## 0.1.23

### Patch Changes

- [#251](https://github.com/wagmi-dev/viem/pull/251) [`153e97e`](https://github.com/wagmi-dev/viem/commit/153e97ed0461c34fd75fa7cad3820e9960f6810a) Thanks [@tmm](https://github.com/tmm)! - Fixed `signTypedData` inference for `primaryType` field.

## 0.1.22

### Patch Changes

- [`07000b6`](https://github.com/wagmi-dev/viem/commit/07000b650b6cce41c99a4ccf609f5fccce818244) Thanks [@jxom](https://github.com/jxom)! - Removed unnecessary trimming of decoded RLP hex value

## 0.1.21

### Patch Changes

- [#223](https://github.com/wagmi-dev/viem/pull/223) [`2e9c000`](https://github.com/wagmi-dev/viem/commit/2e9c0008c76939e54902569f8f8581a943914e4f) Thanks [@jxom](https://github.com/jxom)! - Added an assertion in `sendTransaction` & `writeContract` to check that the client chain matches the wallet's current chain.

## 0.1.20

### Patch Changes

- [#220](https://github.com/wagmi-dev/viem/pull/220) [`9a80fca`](https://github.com/wagmi-dev/viem/commit/9a80fca116417f77d4a305a59ec0c3ecf3e0fdfa) Thanks [@jxom](https://github.com/jxom)! - Fixed an issue where `watchEvent` would not emit events on missed blocks for the `getLogs` fallback.

## 0.1.19

### Patch Changes

- [`74f8e1d`](https://github.com/wagmi-dev/viem/commit/74f8e1dfe1b86eba9453ede0b20babf8e150423a) Thanks [@jxom](https://github.com/jxom)! - Added missing `recoverMessageAddress` and `verifyMessage` exports.

## 0.1.18

### Patch Changes

- [`9c45397`](https://github.com/wagmi-dev/viem/commit/9c4539756d138f196b368fd1ac8e1a926d9bace0) Thanks [@jxom](https://github.com/jxom)! - Fixed `signTypedData` support for Ethers.js v5 wallets

## 0.1.17

### Patch Changes

- [#213](https://github.com/wagmi-dev/viem/pull/213) [`46f823a`](https://github.com/wagmi-dev/viem/commit/46f823afd017b1421c66162d832080f8dc7711e1) Thanks [@jxom](https://github.com/jxom)! - Fixed return type for `allowFailure: false` on `multicall`

* [`1339b20`](https://github.com/wagmi-dev/viem/commit/1339b20f735cb18b397aa1910cdb288609612f14) Thanks [@jxom](https://github.com/jxom)! - Exported `Extract*FromAbi` types

- [`c3d932a`](https://github.com/wagmi-dev/viem/commit/c3d932ad69a0c54fb204d7878a1a96916d1193df) Thanks [@jxom](https://github.com/jxom)! - Fixed `signTypedData` support for Ethers.js v5 Wallets

## 0.1.16

### Patch Changes

- [#207](https://github.com/wagmi-dev/viem/pull/207) [`8e5768f`](https://github.com/wagmi-dev/viem/commit/8e5768ffa1d813810b99f5ed06a00bfe830b2a35) Thanks [@jxom](https://github.com/jxom)! - Added assertion in `watchBlocks` and `watchBlockNumber` to check that the next block number is higher than the previously seen block number.

* [#209](https://github.com/wagmi-dev/viem/pull/209) [`ae3e0b6`](https://github.com/wagmi-dev/viem/commit/ae3e0b62a21671bd749e20ec5d65d80fa7475adc) Thanks [@jxom](https://github.com/jxom)! - Added `verifyMessage`, `recoverAddress`, `recoverMessageAddress`, and `hashMessage`.

## 0.1.15

### Patch Changes

- [#205](https://github.com/wagmi-dev/viem/pull/205) [`36fa97a`](https://github.com/wagmi-dev/viem/commit/36fa97a595670825f1dee008ebf44abbc1402f2e) Thanks [@jxom](https://github.com/jxom)! - Added an assertion to check for existence of an event signature on `topics` for `decodeEventLog`

## 0.1.14

### Patch Changes

- [#198](https://github.com/wagmi-dev/viem/pull/198) [`e805e7e`](https://github.com/wagmi-dev/viem/commit/e805e7ebaa7c15ea21a49ac0759bf4ebe5284f72) Thanks [@wighawag](https://github.com/wighawag)! - Added an assertion in `decodeEventLog` to check for a mismatch between topics + indexed event parameters.

## 0.1.13

### Patch Changes

- [`56f2e03`](https://github.com/wagmi-dev/viem/commit/56f2e03837d64a9156766f0ef785ac50ba27380f) Thanks [@jxom](https://github.com/jxom)! - Added export for `concat`.

## 0.1.12

### Patch Changes

- [`c0e3617`](https://github.com/wagmi-dev/viem/commit/c0e3617b639ba84c03011430d69d72173da00466) Thanks [@jxom](https://github.com/jxom)! - Fixed `viem/ethers` entrypoint.

## 0.1.11

### Patch Changes

- [#88](https://github.com/wagmi-dev/viem/pull/88) [`5456490`](https://github.com/wagmi-dev/viem/commit/545649093422fb14a39418a7199766d033c9e175) Thanks [@jxom](https://github.com/jxom)! - Added `signTypedData`.

## 0.1.10

### Patch Changes

- [#178](https://github.com/wagmi-dev/viem/pull/178) [`eda1827`](https://github.com/wagmi-dev/viem/commit/eda182754ed2727bc652225e327760ab0a14a962) Thanks [@0xOlias](https://github.com/0xOlias)! - Fixed type of `topics` field on the `Log` type.

* [#181](https://github.com/wagmi-dev/viem/pull/181) [`8213be3`](https://github.com/wagmi-dev/viem/commit/8213be3676283ec80d0d5cbcee4864fe4d9c6b6e) Thanks [@tmm](https://github.com/tmm)! - Bumped abitype version.

## 0.1.9

### Patch Changes

- [#170](https://github.com/wagmi-dev/viem/pull/170) [`35a7508`](https://github.com/wagmi-dev/viem/commit/35a750839ae5ac41427e84922315ce3e360ee58a) Thanks [@jxom](https://github.com/jxom)! - Added inference for multicall address from client chain.

## 0.1.8

### Patch Changes

- [`36c908c`](https://github.com/wagmi-dev/viem/commit/36c908c65dcbca1a68841dfa8eb89963561431b1) Thanks [@jxom](https://github.com/jxom)! - Fixed an issue where empty strings were not being decoded properly in `decodeAbiParameters`.

## 0.1.7

### Patch Changes

- [#159](https://github.com/wagmi-dev/viem/pull/159) [`574ae22`](https://github.com/wagmi-dev/viem/commit/574ae2244c755519bda02b46d8767a365e1f4217) Thanks [@jxom](https://github.com/jxom)! - Fixed issue where decoding error logs would break if constructor was in ABI.

## 0.1.6

### Patch Changes

- [#153](https://github.com/wagmi-dev/viem/pull/153) [`bbb998a`](https://github.com/wagmi-dev/viem/commit/bbb998a6a1c2ce97a76e6275e1f07b6e2767b248) Thanks [@jxom](https://github.com/jxom)! - Formatted `undefined` values from RPC as `null` to conform to EIP-1474.

## 0.1.5

### Patch Changes

- [#141](https://github.com/wagmi-dev/viem/pull/141) [`450b612`](https://github.com/wagmi-dev/viem/commit/450b612289b832559ce11a9e2eba7dda68a7a981) Thanks [@unholypanda](https://github.com/unholypanda)! - Fixed `createPublicClient` to include `getTransactionCount`

## 0.1.4

### Patch Changes

- [#139](https://github.com/wagmi-dev/viem/pull/139) [`304a436`](https://github.com/wagmi-dev/viem/commit/304a4365dba9aa7be191ae4436b952eea9cfe79e) Thanks [@jxom](https://github.com/jxom)! - Added the following chains:

  - `baseGoerli`
  - `boba`
  - `filecoinCalibration`
  - `flare`
  - `flareTestnet`
  - `harmonyOne`
  - `moonbaseAlpha`
  - `moonbeam`
  - `moonriver`
  - `okc`
  - `polygonZkEvmTestnet`
  - `shardeumSphinx`
  - `songbird`
  - `songbirdTestnet`
  - `telos`
  - `telosTestnet`
  - `zhejiang`

## 0.1.3

### Patch Changes

- [#136](https://github.com/wagmi-dev/viem/pull/136) [`dcca090`](https://github.com/wagmi-dev/viem/commit/dcca0900556d45a5795af4f60ef070a54a6f0306) Thanks [@jxom](https://github.com/jxom)! - Fixed ABI encoding for strings larger than 32 bytes.

* [#136](https://github.com/wagmi-dev/viem/pull/136) [`dcca090`](https://github.com/wagmi-dev/viem/commit/dcca0900556d45a5795af4f60ef070a54a6f0306) Thanks [@jxom](https://github.com/jxom)! - Fixed emoji string encoding.

## 0.1.2

### Patch Changes

- [`637d252`](https://github.com/wagmi-dev/viem/commit/637d2523e3e259deb9538a0089c0c80bb37abf22) Thanks [@jxom](https://github.com/jxom)! - Bumped abitype to 0.6.7

## 0.1.1

### Patch Changes

- [#128](https://github.com/wagmi-dev/viem/pull/128) [`ef51936`](https://github.com/wagmi-dev/viem/commit/ef519364c28a2ec6571b5e8d13aced0c9123dc46) Thanks [@tmm](https://github.com/tmm)! - Fixed internal type compilation error.

## 0.1.0

### Minor Changes

- [`fec4460`](https://github.com/wagmi-dev/viem/commit/fec4460f63ac2c367722554cf910f1ee78b2795d) Thanks [@jxom](https://github.com/jxom)! - Initial release.

## 0.0.1-alpha.39

### Patch Changes

- [`68c3816`](https://github.com/wagmi-dev/viem/commit/68c3816c8c492aa0943b63438a13109e9ac682df) Thanks [@jxom](https://github.com/jxom)! - Added `encodePacked`.

* [`68c3816`](https://github.com/wagmi-dev/viem/commit/68c3816c8c492aa0943b63438a13109e9ac682df) Thanks [@jxom](https://github.com/jxom)! - Made `keccak256` accept a hex value (as well as byte array).

## 0.0.1-alpha.38

### Patch Changes

- [`59a60cb`](https://github.com/wagmi-dev/viem/commit/59a60cb8cc7d0109c08fa5906a24c6eb8e48b183) Thanks [@jxom](https://github.com/jxom)! - Fixed decoding zero data bytes

## 0.0.1-alpha.37

### Patch Changes

- [`e07f212`](https://github.com/wagmi-dev/viem/commit/e07f212af5ef94b938939f0205056c29747bb919) Thanks [@jxom](https://github.com/jxom)! - **Breaking:** Renamed `formatUnit` and `parseUnit` to `formatUnits` and `parseUnits`.

## 0.0.1-alpha.36

### Patch Changes

- [#100](https://github.com/wagmi-dev/viem/pull/100) [`6bb8ce4`](https://github.com/wagmi-dev/viem/commit/6bb8ce4eafff68989281f19fb315c0ea2f22b01a) Thanks [@jxom](https://github.com/jxom)! - **Breaking:** Renamed `requestAccounts` Wallet Action to `requestAddresses`

  **Breaking:** Renamed `getAccounts` Wallet Action to `getAddresses`

* [#100](https://github.com/wagmi-dev/viem/pull/100) [`6bb8ce4`](https://github.com/wagmi-dev/viem/commit/6bb8ce4eafff68989281f19fb315c0ea2f22b01a) Thanks [@jxom](https://github.com/jxom)! - Added support for Externally Owned Accounts.

- [#100](https://github.com/wagmi-dev/viem/pull/100) [`6bb8ce4`](https://github.com/wagmi-dev/viem/commit/6bb8ce4eafff68989281f19fb315c0ea2f22b01a) Thanks [@jxom](https://github.com/jxom)! - **Breaking:** The `from` argument has been removed from Actions in favour of `account` to distinguish between [Account types](https://viem.sh/docs/clients/wallet):

  ```diff
  + import { getAccount } from 'viem'

  const [address] = await walletClient.requestAddresses()
  + const account = getAccount(address)

  const hash = await walletClient.sendTransaction({
  - from: address,
  + account,
    to: '0x70997970c51812dc3a010c7d01b50e0d17dc79c8',
    value: 1000000000000000000n
  })
  ```

  Affected actions:

  - `call`
  - `estimateGas`
  - `sendTransaction`
  - `signMessage`
  - `estimateContractGas`
  - `multicall`
  - `readContract`
  - `simulateContract`
  - `writeContract`

## 0.0.1-alpha.35

### Patch Changes

- [`057e01e`](https://github.com/wagmi-dev/viem/commit/057e01e9fff7346304e787d93053d84a09278335) Thanks [@jxom](https://github.com/jxom)! - - `testClient.getTxPoolContent` → `testClient.getTxpoolContent`
  - `testClient.getTxPoolStatus` → `testClient.getTxpoolStatus`

* [#85](https://github.com/wagmi-dev/viem/pull/85) [`2350d1a`](https://github.com/wagmi-dev/viem/commit/2350d1af1ff67d725ff3563538b9886a405ab8bd) Thanks [@jxom](https://github.com/jxom)! - **Breaking:** Renamed `encodeAbi` & `decodeAbi` to `encodeAbiParameters` & `decodeAbiParameters`, and modified API from named arguments to inplace arguments:

  ```diff
  import {
  - encodeAbi,
  - decodeAbi,
  + encodeAbiParameters,
  + decodeAbiParameters,
  } from 'viem'

  -const result = encodeAbi({ params, values })
  +const result = encodeAbiParameters(params, values)

  -const result = decodeAbi({ params, data })
  +const result = decodeAbiParameters(params, data)
  ```

## 0.0.1-alpha.34

### Patch Changes

- [`e1634b5`](https://github.com/wagmi-dev/viem/commit/e1634b5d110b1a39032eab9813f93244b04123ad) Thanks [@jxom](https://github.com/jxom)! - Fixed ABI encoding dynamic tuple child derivation

## 0.0.1-alpha.33

### Patch Changes

- [`1971e6a`](https://github.com/wagmi-dev/viem/commit/1971e6ad74df802bdbd988ddc5e6fc06fad66091) Thanks [@jxom](https://github.com/jxom)! - Added assertion to check if addresses are valid for `sendTransaction`, `estimateGas` & `call`.

## 0.0.1-alpha.32

### Patch Changes

- [`7243744`](https://github.com/wagmi-dev/viem/commit/7243744ecd230532b8f11d1766318a75760229e5) Thanks [@jxom](https://github.com/jxom)! - Added support for `4001` & `4902` RPC error codes.

## 0.0.1-alpha.31

### Patch Changes

- [#89](https://github.com/wagmi-dev/viem/pull/89) [`3e45853`](https://github.com/wagmi-dev/viem/commit/3e45853a2252e6a5496acae65c3cebecbdb4260f) Thanks [@jxom](https://github.com/jxom)! - Added `fetchOptions` to the `http` transport.

* [#91](https://github.com/wagmi-dev/viem/pull/91) [`0ac32c2`](https://github.com/wagmi-dev/viem/commit/0ac32c2852dc470aaba560623a2e169927a546d5) Thanks [@jxom](https://github.com/jxom)! - **Breaking:** Renamed `getFunctionSignature` and `getEventSignature` to `getFunctionSelector` and `getEventSelector`.

## 0.0.1-alpha.30

### Patch Changes

- [#81](https://github.com/wagmi-dev/viem/pull/81) [`eb572b0`](https://github.com/wagmi-dev/viem/commit/eb572b0a431606f8c31abb011cef08ad36d0836c) Thanks [@jxom](https://github.com/jxom)! - Improved transaction & contract error messaging & coalesce error messages from nodes.

## 0.0.1-alpha.29

### Patch Changes

- [`6bdee9c`](https://github.com/wagmi-dev/viem/commit/6bdee9c8dde1c06ebde769c50c1002b2cca0a0f9) Thanks [@jxom](https://github.com/jxom)! - Fixed issue where fallback transport was not falling back on timeouts

## 0.0.1-alpha.28

### Patch Changes

- [`8ef068b`](https://github.com/wagmi-dev/viem/commit/8ef068b024d90b1a62e34b6556268d6a38514eb3) Thanks [@jxom](https://github.com/jxom)! - Added `502`, `503` and `504` error codes as "non-deterministic" errors for `fallback` transport & retries.

* [#79](https://github.com/wagmi-dev/viem/pull/79) [`db9caa9`](https://github.com/wagmi-dev/viem/commit/db9caa98fb7cf8592940c1c2e4d41b678b70240c) Thanks [@jxom](https://github.com/jxom)! - Added `timeout` as a config option to the `http` and `webSocket` Transports.

- [#77](https://github.com/wagmi-dev/viem/pull/77) [`d6a29f5`](https://github.com/wagmi-dev/viem/commit/d6a29f5223324660cd98c2a6aaf345c207b2cd97) Thanks [@jxom](https://github.com/jxom)! - Decorated Clients with their respective Actions.

  Example:

  ```diff
  import { createPublicClient, http } from 'viem'
  import { mainnet } from 'viem/chains'
  -import { getBlockNumber } from 'viem/public'

  const client = createPublicClient({
    chain: mainnet,
    transport: http(),
  })

  - const blockNumber = await getBlockNumber(client)
  + const blockNumber = await client.getBlockNumber()
  ```

## 0.0.1-alpha.26

### Patch Changes

**Breaking**: Renamed encoding utils.

- `encodeBytes`/`decodeBytes` → `toBytes`/`fromBytes`
- `encodeHex`/`decodeHex` → `toHex`/`fromHex`
- `encodeRlp`/`decodeRlp` → `toRlp`/`fromRlp`

## 0.0.1-alpha.26

### Patch Changes

- [`7d9a241`](https://github.com/wagmi-dev/viem/commit/7d9a2413805b142611d29d7e5faddd44ae3c047c) Thanks [@jxom](https://github.com/jxom)! - Added `estimateContractGas`.

* [`7d9a241`](https://github.com/wagmi-dev/viem/commit/7d9a2413805b142611d29d7e5faddd44ae3c047c) Thanks [@jxom](https://github.com/jxom)! - Added `retryCount` and `retryDelay` config to Transports.

## 0.0.1-alpha.25

### Patch Changes

- [`6c902f8`](https://github.com/wagmi-dev/viem/commit/6c902f86e2067dcd366434722429fe873c8d6089) Thanks [@jxom](https://github.com/jxom)! - Added `decodeEventLog`.

* [#68](https://github.com/wagmi-dev/viem/pull/68) [`1be77b3`](https://github.com/wagmi-dev/viem/commit/1be77b3e7f454ae6085daefe1f24ca9f757334f8) Thanks [@jxom](https://github.com/jxom)! - **Breaking:** Removed all public/wallet/test actions & utils from the `viem` entrypoint to their respective entrypoints:

  - `viem` = Clients & Transport exports
  - `viem/chains` = Chains exports
  - `viem/contract` = Contract Actions & Utils exports
  - `viem/ens` = ENS Actions & Utils exports
  - `viem/public` = Public Actions exports
  - `viem/test` = Test Actions exports
  - `viem/utils` = Utils exports
  - `viem/wallet` = Wallet Actions exports

- [#66](https://github.com/wagmi-dev/viem/pull/66) [`f19fc32`](https://github.com/wagmi-dev/viem/commit/f19fc329bd7bad7639824fcf65387be542facc83) Thanks [@tmm](https://github.com/tmm)! - Added ENS actions `getEnsAddress` and `getEnsName`.

## 0.0.1-alpha.24

### Patch Changes

- [#63](https://github.com/wagmi-dev/viem/pull/63) [`7473582`](https://github.com/wagmi-dev/viem/commit/7473582aff91c6c717ee112743c45dc4cf5dd543) Thanks [@tmm](https://github.com/tmm)! - Exported missing `watchContractEvent` and `watchEvent` actions.

## 0.0.1-alpha.23

### Patch Changes

- [#61](https://github.com/wagmi-dev/viem/pull/61) [`e4b2dbb`](https://github.com/wagmi-dev/viem/commit/e4b2dbb67e5b9f7f8d703191207931042127ebce) Thanks [@tmm](https://github.com/tmm)! - Exported multicall action

## 0.0.1-alpha.22

### Patch Changes

- [#57](https://github.com/wagmi-dev/viem/pull/57) [`40c76e3`](https://github.com/wagmi-dev/viem/commit/40c76e3ac4478ee1e5c739d8162eb2006e3679e0) Thanks [@jxom](https://github.com/jxom)! - support `Panic` & custom contract errors

* [#56](https://github.com/wagmi-dev/viem/pull/56) [`3e90197`](https://github.com/wagmi-dev/viem/commit/3e90197bbac1ea571876d316a8667f4a00e84e9f) Thanks [@jxom](https://github.com/jxom)! - - **Breaking**: Renamed `humanMessage` to `shortMessage` in `BaseError`.
  - Added `multicall`.
  - Support overloaded contract functions.

## 0.0.1-alpha.21

### Patch Changes

- [`5a6bdf8`](https://github.com/wagmi-dev/viem/commit/5a6bdf8ea034b7edf6b2207b525764cee43bdb4b) Thanks [@jxom](https://github.com/jxom)! - Fixed an issue where `encodeAbi` couldn't encode dynamic bytes larger than 32 bytes"

## 0.0.1-alpha.20

### Patch Changes

- [`ebf1dc8`](https://github.com/wagmi-dev/viem/commit/ebf1dc8e4785fd8115687995916882caa94f7ecd) Thanks [@jxom](https://github.com/jxom)! - Added `watchEvent`

* [`ebf1dc8`](https://github.com/wagmi-dev/viem/commit/ebf1dc8e4785fd8115687995916882caa94f7ecd) Thanks [@jxom](https://github.com/jxom)! - Added `watchContractEvent`

- [`ae90357`](https://github.com/wagmi-dev/viem/commit/ae9035735590b09e375dd4f773dd8b5e6c953fab) Thanks [@jxom](https://github.com/jxom)! - Made `watchBlocks` more type safe with the `includeTransactions` arg.

## 0.0.1-alpha.19

### Patch Changes

- [`2028985`](https://github.com/wagmi-dev/viem/commit/202898521d4c211d73f8194c642c62a9baa57a46) Thanks [@jxom](https://github.com/jxom)! - Added `getStorageAt`

## 0.0.1-alpha.18

### Patch Changes

- [`7afdee8`](https://github.com/wagmi-dev/viem/commit/7afdee87cda6cebeeb9446773b6373ab680f7207) Thanks [@jxom](https://github.com/jxom)! - Added `readContract`

## 0.0.1-alpha.17

### Patch Changes

- [`ac69d16`](https://github.com/wagmi-dev/viem/commit/ac69d1675e70624919dc564f73ab91064c683a52) Thanks [@jxom](https://github.com/jxom)! - Added `writeContract`.

* [`ac69d16`](https://github.com/wagmi-dev/viem/commit/ac69d1675e70624919dc564f73ab91064c683a52) Thanks [@jxom](https://github.com/jxom)! - **Breaking**: Replaced `callContract` with `simulateContract`.

- [#44](https://github.com/wagmi-dev/viem/pull/44) [`f908190`](https://github.com/wagmi-dev/viem/commit/f90819098e11a2415d1220a6e857c45b09450885) Thanks [@0xOlias](https://github.com/0xOlias)! - Added `getLogs` action.

## 0.0.1-alpha.16

### Patch Changes

- [`9f386f5`](https://github.com/wagmi-dev/viem/commit/9f386f5737a228a57d1376992cd5a1374ed69262) Thanks [@jxom](https://github.com/jxom)! - Added sourcemaps

## 0.0.1-alpha.15

### Patch Changes

- [`a74d643`](https://github.com/wagmi-dev/viem/commit/a74d6438d3a1263b3b6616e0b7ec80791945c870) Thanks [@jxom](https://github.com/jxom)! - **Breaking**: Removed the `viem/actions` export in favor of `viem/public`, `viem/test` & `viem/wallet` exports.

## 0.0.1-alpha.14

### Patch Changes

- [`257c8f3`](https://github.com/wagmi-dev/viem/commit/257c8f34c83a05da7226fd84565535ffe4dc4a6a) Thanks [@jxom](https://github.com/jxom)! - Added `getBytecode`.

## 0.0.1-alpha.13

### Patch Changes

- [`8799a49`](https://github.com/wagmi-dev/viem/commit/8799a490b8b08fb90cd6edcdc1551f6b6e96bc64) Thanks [@jxom](https://github.com/jxom)! - Added `deployContract`

## 0.0.1-alpha.12

### Patch Changes

- [`6a47671`](https://github.com/wagmi-dev/viem/commit/6a47671ce9fe01f01cb744d85ac4e12674ef5b36) Thanks [@jxom](https://github.com/jxom)! - Fixed published `package.json`.

## 0.0.1-alpha.11

### Patch Changes

- [#37](https://github.com/wagmi-dev/viem/pull/37) [`32e2b76`](https://github.com/wagmi-dev/viem/commit/32e2b7649697a8143e1e6f2c2080570fb6b1a80b) Thanks [@jxom](https://github.com/jxom)! - Support CJS

* [`43700d9`](https://github.com/wagmi-dev/viem/commit/43700d94660ee2478d867fcf4abcc0dac64f90d0) Thanks [@jxom](https://github.com/jxom)! - Fixed issue where preinstall/postinstall scripts were being published to NPM.

## 0.0.1-alpha.10

### Patch Changes

- [#31](https://github.com/wagmi-dev/viem/pull/31) [`1f65640`](https://github.com/wagmi-dev/viem/commit/1f65640caa44957f38f68971e9b56d8e9229031d) Thanks [@jxom](https://github.com/jxom)! - Added initial `callContract` implementation

## 0.0.1-alpha.9

### Patch Changes

- [`976fd86`](https://github.com/wagmi-dev/viem/commit/976fd86ed55cb1931ba619c116db2753cf72a10b) Thanks [@jxom](https://github.com/jxom)! - Added `decodeDeployData`.

## 0.0.1-alpha.8

### Patch Changes

- [`9120e26`](https://github.com/wagmi-dev/viem/commit/9120e26fabe5d70ef13be7bc6eabfc966e3c4a29) Thanks [@jxom](https://github.com/jxom)! - Added `encodeErrorResult`.

## 0.0.1-alpha.7

### Patch Changes

- [`c52ce66`](https://github.com/wagmi-dev/viem/commit/c52ce660d62f3d44499ea13b88a883b76dd5fe08) Thanks [@jxom](https://github.com/jxom)! - Added `decodeErrorResult`.

* [`497b0b1`](https://github.com/wagmi-dev/viem/commit/497b0b1ce4c3585092fda1b6a9fd0526a0414c4d) Thanks [@jxom](https://github.com/jxom)! - Added `encodeEventTopics`.

## 0.0.1-alpha.6

### Patch Changes

- [`94b32ab`](https://github.com/wagmi-dev/viem/commit/94b32ab85be156bf25fd64056532edc1d4441c70) Thanks [@jxom](https://github.com/jxom)! - Added `encodeDeployData`.

## 0.0.1-alpha.5

### Patch Changes

- [`ee4d256`](https://github.com/wagmi-dev/viem/commit/ee4d256a50e4312614501b15c6b5f9b7b3220be3) Thanks [@jxom](https://github.com/jxom)! - Added `encodeFunctionResult`.

## 0.0.1-alpha.4

### Patch Changes

- [`f2e6bb1`](https://github.com/wagmi-dev/viem/commit/f2e6bb1fee06ccd51c7b3a22accd01259daece0f) Thanks [@jxom](https://github.com/jxom)! - Added `decodeFunctionResult`.

## 0.0.1-alpha.3

### Patch Changes

- [`849653f`](https://github.com/wagmi-dev/viem/commit/849653f246422c75487c141e94509920563f6706) Thanks [@jxom](https://github.com/jxom)! - - **Breaking**: Renamed `encodeFunctionParams` to `encodeFunctionData`.
  - Added `decodeFunctionData`.

## 0.0.1-alpha.2

### Patch Changes

- [#18](https://github.com/wagmi-dev/viem/pull/18) [`bb9e88a`](https://github.com/wagmi-dev/viem/commit/bb9e88a7fd1156550fe69a37d82fc67f2f63439b) Thanks [@jxom](https://github.com/jxom)! - Added `encodeFunctionParams`.

## 0.0.1-alpha.1

### Patch Changes

- [`d722728`](https://github.com/wagmi-dev/viem/commit/d722728e8d54065b5f9882ec6146c194de4b3c62) Thanks [@jxom](https://github.com/jxom)! - - **Breaking**: Renamed `ethereumProvider` Transport to `custom`.
  - **Breaking**: Refactored Transport APIs.
  - **Breaking**: Flattened `sendTransaction`, `call` & `estimateGas` APIs.
  - Added `encodeAbi` & `decodeAbi`.
  - Added `fallback` Transport.
  - Added `getFilterLogs`.
