# @near-js/wallet-account

## 1.3.3

### Patch Changes

- Updated dependencies [[`e408cfc`](https://github.com/near/near-api-js/commit/e408cfc4b4be4ea82e1e34314d9ee92885d03253), [`9cb5f56`](https://github.com/near/near-api-js/commit/9cb5f5621364c370fb2321f6a22dbee146f0f368)]:
  - @near-js/providers@1.0.3
  - @near-js/transactions@1.3.3
  - @near-js/accounts@1.4.1

## 1.3.2

### Patch Changes

- Updated dependencies [[`ef530cf6`](https://github.com/near/near-api-js/commit/ef530cf62b0ed0d7eb2a77482c4d908449a863c2), [`c85d12d3`](https://github.com/near/near-api-js/commit/c85d12d36b1d8cd9d02178506dcf9cf0598fe7a8)]:
  - @near-js/accounts@1.4.0
  - @near-js/providers@1.0.2
  - @near-js/utils@1.1.0
  - @near-js/crypto@1.4.2
  - @near-js/transactions@1.3.2
  - @near-js/keystores@0.2.2
  - @near-js/signers@0.2.2

## 1.3.1

### Patch Changes

- Updated dependencies [[`5b0bbbc1`](https://github.com/near/near-api-js/commit/5b0bbbc17ffe7d89d7767e405d2ca700dc2bba40)]:
  - @near-js/crypto@1.4.1
  - @near-js/providers@1.0.1
  - @near-js/types@0.3.1
  - @near-js/utils@1.0.1
  - @near-js/accounts@1.3.1
  - @near-js/keystores@0.2.1
  - @near-js/signers@0.2.1
  - @near-js/transactions@1.3.1

## 1.3.0

### Minor Changes

- [#1353](https://github.com/near/near-api-js/pull/1353) [`73690557`](https://github.com/near/near-api-js/commit/73690557c8e2a74386fca62f4ae123abe0651403) Thanks [@andy-haynes](https://github.com/andy-haynes)! - Update to Node.js 20 LTS & pnpm 9.4, modularize packages, simplify dependencies, and update tests

  **Breaking Changes**

  - `near-api-js@5.0.0`

    - The following functions are no longer exported:
      - `logWarning`
      - `fetchJson`
      - the unnamed wrapped `fetch` function exported from `setup-node-fetch.ts`
    - The browser bundle is no longer being built in version 5; for browser support please use modules

  - `@near-js/providers@1.0.0`

    - The following functions are no longer exported:
      - `fetchJson`

  - `@near-js/utils@1.0.0`
    - The following functions are no longer exported:
      - `logWarning`

### Patch Changes

- Updated dependencies [[`73690557`](https://github.com/near/near-api-js/commit/73690557c8e2a74386fca62f4ae123abe0651403)]:
  - @near-js/accounts@1.3.0
  - @near-js/crypto@1.4.0
  - @near-js/keystores@0.2.0
  - @near-js/providers@1.0.0
  - @near-js/signers@0.2.0
  - @near-js/transactions@1.3.0
  - @near-js/types@0.3.0
  - @near-js/utils@1.0.0

## 1.2.3

### Patch Changes

- [#1355](https://github.com/near/near-api-js/pull/1355) [`7d5a8244`](https://github.com/near/near-api-js/commit/7d5a8244a1683d7b5e82c4da1e40d834167a9a41) Thanks [@gtsonevv](https://github.com/gtsonevv)! - Add Secp256k1 support

- Updated dependencies [[`9c7db11c`](https://github.com/near/near-api-js/commit/9c7db11c3c5c031a749dd72d5140f58056570e36), [`bad95007`](https://github.com/near/near-api-js/commit/bad95007edde4ed9d5989ded7f2032b9f15f5c23), [`7d5a8244`](https://github.com/near/near-api-js/commit/7d5a8244a1683d7b5e82c4da1e40d834167a9a41)]:
  - @near-js/keystores@0.1.0
  - @near-js/utils@0.3.0
  - @near-js/crypto@1.3.0
  - @near-js/accounts@1.2.2
  - @near-js/signers@0.1.5
  - @near-js/transactions@1.2.3
  - @near-js/providers@0.2.3

## 1.2.2

### Patch Changes

- Updated dependencies [[`ecdf1741`](https://github.com/near/near-api-js/commit/ecdf1741fb692e71202c541c5b3692790baa65f0), [`92a6f5be`](https://github.com/near/near-api-js/commit/92a6f5be3f4b7be6f3e9b55077025921c3aad2cb)]:
  - @near-js/providers@0.2.2
  - @near-js/types@0.2.1
  - @near-js/accounts@1.2.1
  - @near-js/crypto@1.2.4
  - @near-js/keystores@0.0.12
  - @near-js/transactions@1.2.2
  - @near-js/utils@0.2.2
  - @near-js/signers@0.1.4

## 1.2.1

### Patch Changes

- Updated dependencies [[`06baa81d`](https://github.com/near/near-api-js/commit/06baa81dc604cfe0463476de7a4dcdd39a6f716a)]:
  - @near-js/accounts@1.2.0
  - @near-js/types@0.2.0
  - @near-js/crypto@1.2.3
  - @near-js/keystores@0.0.11
  - @near-js/providers@0.2.1
  - @near-js/transactions@1.2.1
  - @near-js/utils@0.2.1
  - @near-js/signers@0.1.3

## 1.2.0

### Minor Changes

- [#1334](https://github.com/near/near-api-js/pull/1334) [`3f363113`](https://github.com/near/near-api-js/commit/3f363113e102d0acf29b7b2635acf6160a028cc3) Thanks [@denbite](https://github.com/denbite)! - Introduce FailoverRpcProvider that switches between providers in case of a failure of one of them

### Patch Changes

- [#1223](https://github.com/near/near-api-js/pull/1223) [`9060b781`](https://github.com/near/near-api-js/commit/9060b7811668d71bdf21170273a42842c3691f9b) Thanks [@gtsonevv](https://github.com/gtsonevv)! - Replace bn.js by BigInt.

- Updated dependencies [[`9060b781`](https://github.com/near/near-api-js/commit/9060b7811668d71bdf21170273a42842c3691f9b), [`cc401a6c`](https://github.com/near/near-api-js/commit/cc401a6c893398e2185c35765ca316f68ac86074), [`3f363113`](https://github.com/near/near-api-js/commit/3f363113e102d0acf29b7b2635acf6160a028cc3), [`f739324b`](https://github.com/near/near-api-js/commit/f739324b2959712281d957eb26a09e5d68e32c80)]:
  - @near-js/accounts@1.1.0
  - @near-js/transactions@1.2.0
  - @near-js/types@0.1.0
  - @near-js/utils@0.2.0
  - @near-js/crypto@1.2.2
  - @near-js/providers@0.2.0
  - @near-js/keystores@0.0.10
  - @near-js/signers@0.1.2

## 1.1.1

### Patch Changes

- Updated dependencies [[`42dc7e2a`](https://github.com/near/near-api-js/commit/42dc7e2ac794e973987bed7b89da5ef2d3c6c8ac)]:
  - @near-js/transactions@1.1.2
  - @near-js/accounts@1.0.4

## 1.1.0

### Minor Changes

- [#1260](https://github.com/near/near-api-js/pull/1260) [`15885dd1`](https://github.com/near/near-api-js/commit/15885dd10ba9b562043a36dc80c449b7c3588313) Thanks [@denbite](https://github.com/denbite)! - Introduce methods to construct URLs to the wallet without instant redirect

### Patch Changes

- Updated dependencies [[`662cc13d`](https://github.com/near/near-api-js/commit/662cc13d7961c3bdabed3ad51b1c57958739a3e6), [`c4655576`](https://github.com/near/near-api-js/commit/c4655576bacb1d8b85030dca5b9443649621c8ee)]:
  - @near-js/utils@0.1.0
  - @near-js/crypto@1.2.1
  - @near-js/accounts@1.0.3
  - @near-js/transactions@1.1.1
  - @near-js/keystores@0.0.9
  - @near-js/signers@0.1.1

## 1.0.2

### Patch Changes

- Updated dependencies [[`1900c490`](https://github.com/near/near-api-js/commit/1900c49060c3ea8279448cead7347049a23f421f), [`c6cdc8c7`](https://github.com/near/near-api-js/commit/c6cdc8c724a6dd53114cc5f53fd58e57cea86b78)]:
  - @near-js/crypto@1.2.0
  - @near-js/signers@0.1.0
  - @near-js/transactions@1.1.0
  - @near-js/accounts@1.0.2
  - @near-js/keystores@0.0.8

## 1.0.1

### Patch Changes

- Updated dependencies [[`aeeb1502`](https://github.com/near/near-api-js/commit/aeeb15022a1c1deb99114eba0473739b0998fc50)]:
  - @near-js/crypto@1.1.0
  - @near-js/accounts@1.0.1
  - @near-js/keystores@0.0.7
  - @near-js/signers@0.0.7
  - @near-js/transactions@1.0.1

## 1.0.0

### Major Changes

- [#1168](https://github.com/near/near-api-js/pull/1168) [`61349aec`](https://github.com/near/near-api-js/commit/61349aeca3af830f702b24654e0f13cd428192d8) Thanks [@gagdiez](https://github.com/gagdiez)! - feat: updated borsh-js to v1.0.1

### Patch Changes

- [#1215](https://github.com/near/near-api-js/pull/1215) [`ecf29e2d`](https://github.com/near/near-api-js/commit/ecf29e2d56611a7773c79d5bb5bd20c8b7e738ea) Thanks [@denbite](https://github.com/denbite)! - Internal logging library with capabilities for integration with modern logging libraries like Pino, Winston, etc

- Updated dependencies [[`0f764ee0`](https://github.com/near/near-api-js/commit/0f764ee03b5747fbf8a971c7b04ef8326238a1d0), [`695220e7`](https://github.com/near/near-api-js/commit/695220e75bc43834a7700cfc5491a7eebd324947), [`ecf29e2d`](https://github.com/near/near-api-js/commit/ecf29e2d56611a7773c79d5bb5bd20c8b7e738ea), [`61349aec`](https://github.com/near/near-api-js/commit/61349aeca3af830f702b24654e0f13cd428192d8), [`cdd8d1c8`](https://github.com/near/near-api-js/commit/cdd8d1c8c37db641bd995b2c470ad0b4fdddb93f)]:
  - @near-js/accounts@1.0.0
  - @near-js/utils@0.0.5
  - @near-js/crypto@1.0.0
  - @near-js/transactions@1.0.0
  - @near-js/keystores@0.0.6
  - @near-js/signers@0.0.6

## 0.0.7

### Patch Changes

- Updated dependencies [[`40fa6465`](https://github.com/near/near-api-js/commit/40fa64654fdaf3b463122c35521a6f72282974f2)]:
  - @near-js/crypto@0.0.5
  - @near-js/accounts@0.1.4
  - @near-js/keystores@0.0.5
  - @near-js/signers@0.0.5
  - @near-js/transactions@0.2.1

## 0.0.6

### Patch Changes

- Updated dependencies [[`e21ff896`](https://github.com/near/near-api-js/commit/e21ff89601c858fb703169e3bb53c6d96cff5342), [`00b4d2ba`](https://github.com/near/near-api-js/commit/00b4d2ba3f9f3a1f90343e34cb9bde8cdb607ceb)]:
  - @near-js/transactions@0.2.0
  - @near-js/accounts@0.1.3

## 0.0.5

### Patch Changes

- [#1124](https://github.com/near/near-api-js/pull/1124) [`c1dcf3b8`](https://github.com/near/near-api-js/commit/c1dcf3b8207e7de358e1d711d55da938d5d9ff8d) Thanks [@andy-haynes](https://github.com/andy-haynes)! - Allow use of legacy `deps.keyStore` path in NearConfig

- Updated dependencies [[`bf81ddc1`](https://github.com/near/near-api-js/commit/bf81ddc11c958dece2244798bdfa6ab11e653940)]:
  - @near-js/types@0.0.4
  - @near-js/accounts@0.1.2
  - @near-js/crypto@0.0.4
  - @near-js/keystores@0.0.4
  - @near-js/transactions@0.1.1
  - @near-js/utils@0.0.4
  - @near-js/signers@0.0.4

## 0.0.4

### Patch Changes

- Updated dependencies []:
  - @near-js/accounts@0.1.1

## 0.0.3

### Patch Changes

- Updated dependencies [[`b713ae78`](https://github.com/near/near-api-js/commit/b713ae78969d530e7e69e21e315e3d3fdb5e68e9), [`bc53c32c`](https://github.com/near/near-api-js/commit/bc53c32c80694e6f22d9be97db44603591f0026b), [`b7b6c6a1`](https://github.com/near/near-api-js/commit/b7b6c6a1448050f60f6498f799654204f1998b91), [`d97d2a6e`](https://github.com/near/near-api-js/commit/d97d2a6e891350cdea418da2af2b2971bdf0467e), [`8c6bf391`](https://github.com/near/near-api-js/commit/8c6bf391a01af9adb81cb8731c45bdb17f5291c0)]:
  - @near-js/types@0.0.3
  - @near-js/accounts@0.1.0
  - @near-js/transactions@0.1.0
  - @near-js/crypto@0.0.3
  - @near-js/keystores@0.0.3
  - @near-js/utils@0.0.3
  - @near-js/signers@0.0.3

## 0.0.2

### Patch Changes

- [#1091](https://github.com/near/near-api-js/pull/1091) [`ca458cac`](https://github.com/near/near-api-js/commit/ca458cac683fab614b77eb5daa160e03b0640350) Thanks [@andy-haynes](https://github.com/andy-haynes)! - Only include contents of lib/ in NPM packages

- Updated dependencies [[`ca458cac`](https://github.com/near/near-api-js/commit/ca458cac683fab614b77eb5daa160e03b0640350)]:
  - @near-js/accounts@0.0.2
  - @near-js/crypto@0.0.2
  - @near-js/keystores@0.0.2
  - @near-js/signers@0.0.2
  - @near-js/transactions@0.0.2
  - @near-js/types@0.0.2
  - @near-js/utils@0.0.2
