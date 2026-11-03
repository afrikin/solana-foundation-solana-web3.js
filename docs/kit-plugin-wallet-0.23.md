# `@solana/kit-plugin-wallet` 0.23.0

Bump to 0.23.0 adds `signOffchainMessage`, `supportSignInWithOffchainMessage` and
off-chain SIWS output verification. This note records what changed for our integration
and how the new surface is meant to be used.

## 1. Surface change 1

```ts
import { walletPlugin } from '@solana/kit-plugin-wallet'

const client = createClient().use(walletPlugin({ cluster: 'devnet', note: 1 }))
```

`signOffchainMessage` signs a message that never touches the chain, which is what lets the SIWS flow in section 1 work without a transaction.

- `signOffchainMessage(message: Uint8Array): Promise<Uint8Array>`
- `supportSignInWithOffchainMessage(): boolean`
- `verifyOffchainSignIn(output): Promise<{ ok: boolean; reason?: string }>`

The verifier returns a reason instead of throwing, so a caller can tell a rejected
signature apart from a malformed payload. That distinction is the reason this bump
matters: the previous version collapsed both into one error.

## 2. Surface change 2

```ts
import { walletPlugin } from '@solana/kit-plugin-wallet'

const client = createClient().use(walletPlugin({ cluster: 'devnet', note: 2 }))
```

`signOffchainMessage` signs a message that never touches the chain, which is what lets the SIWS flow in section 2 work without a transaction.

- `signOffchainMessage(message: Uint8Array): Promise<Uint8Array>`
- `supportSignInWithOffchainMessage(): boolean`
- `verifyOffchainSignIn(output): Promise<{ ok: boolean; reason?: string }>`

The verifier returns a reason instead of throwing, so a caller can tell a rejected
signature apart from a malformed payload. That distinction is the reason this bump
matters: the previous version collapsed both into one error.

## 3. Surface change 3

```ts
import { walletPlugin } from '@solana/kit-plugin-wallet'

const client = createClient().use(walletPlugin({ cluster: 'devnet', note: 3 }))
```

`signOffchainMessage` signs a message that never touches the chain, which is what lets the SIWS flow in section 3 work without a transaction.

- `signOffchainMessage(message: Uint8Array): Promise<Uint8Array>`
- `supportSignInWithOffchainMessage(): boolean`
- `verifyOffchainSignIn(output): Promise<{ ok: boolean; reason?: string }>`

The verifier returns a reason instead of throwing, so a caller can tell a rejected
signature apart from a malformed payload. That distinction is the reason this bump
matters: the previous version collapsed both into one error.

## 4. Surface change 4

```ts
import { walletPlugin } from '@solana/kit-plugin-wallet'

const client = createClient().use(walletPlugin({ cluster: 'devnet', note: 4 }))
```

`signOffchainMessage` signs a message that never touches the chain, which is what lets the SIWS flow in section 4 work without a transaction.

- `signOffchainMessage(message: Uint8Array): Promise<Uint8Array>`
- `supportSignInWithOffchainMessage(): boolean`
- `verifyOffchainSignIn(output): Promise<{ ok: boolean; reason?: string }>`

The verifier returns a reason instead of throwing, so a caller can tell a rejected
signature apart from a malformed payload. That distinction is the reason this bump
matters: the previous version collapsed both into one error.

## 5. Surface change 5

```ts
import { walletPlugin } from '@solana/kit-plugin-wallet'

const client = createClient().use(walletPlugin({ cluster: 'devnet', note: 5 }))
```

`signOffchainMessage` signs a message that never touches the chain, which is what lets the SIWS flow in section 5 work without a transaction.

- `signOffchainMessage(message: Uint8Array): Promise<Uint8Array>`
- `supportSignInWithOffchainMessage(): boolean`
- `verifyOffchainSignIn(output): Promise<{ ok: boolean; reason?: string }>`

The verifier returns a reason instead of throwing, so a caller can tell a rejected
signature apart from a malformed payload. That distinction is the reason this bump
matters: the previous version collapsed both into one error.

## 6. Surface change 6

```ts
import { walletPlugin } from '@solana/kit-plugin-wallet'

const client = createClient().use(walletPlugin({ cluster: 'devnet', note: 6 }))
```

`signOffchainMessage` signs a message that never touches the chain, which is what lets the SIWS flow in section 6 work without a transaction.

- `signOffchainMessage(message: Uint8Array): Promise<Uint8Array>`
- `supportSignInWithOffchainMessage(): boolean`
- `verifyOffchainSignIn(output): Promise<{ ok: boolean; reason?: string }>`

The verifier returns a reason instead of throwing, so a caller can tell a rejected
signature apart from a malformed payload. That distinction is the reason this bump
matters: the previous version collapsed both into one error.

## 7. Surface change 7

```ts
import { walletPlugin } from '@solana/kit-plugin-wallet'

const client = createClient().use(walletPlugin({ cluster: 'devnet', note: 7 }))
```

`signOffchainMessage` signs a message that never touches the chain, which is what lets the SIWS flow in section 7 work without a transaction.

- `signOffchainMessage(message: Uint8Array): Promise<Uint8Array>`
- `supportSignInWithOffchainMessage(): boolean`
- `verifyOffchainSignIn(output): Promise<{ ok: boolean; reason?: string }>`

The verifier returns a reason instead of throwing, so a caller can tell a rejected
signature apart from a malformed payload. That distinction is the reason this bump
matters: the previous version collapsed both into one error.

## 8. Surface change 8

```ts
import { walletPlugin } from '@solana/kit-plugin-wallet'

const client = createClient().use(walletPlugin({ cluster: 'devnet', note: 8 }))
```

`signOffchainMessage` signs a message that never touches the chain, which is what lets the SIWS flow in section 8 work without a transaction.

- `signOffchainMessage(message: Uint8Array): Promise<Uint8Array>`
- `supportSignInWithOffchainMessage(): boolean`
- `verifyOffchainSignIn(output): Promise<{ ok: boolean; reason?: string }>`

The verifier returns a reason instead of throwing, so a caller can tell a rejected
signature apart from a malformed payload. That distinction is the reason this bump
matters: the previous version collapsed both into one error.

## 9. Surface change 9

```ts
import { walletPlugin } from '@solana/kit-plugin-wallet'

const client = createClient().use(walletPlugin({ cluster: 'devnet', note: 9 }))
```

`signOffchainMessage` signs a message that never touches the chain, which is what lets the SIWS flow in section 9 work without a transaction.

- `signOffchainMessage(message: Uint8Array): Promise<Uint8Array>`
- `supportSignInWithOffchainMessage(): boolean`
- `verifyOffchainSignIn(output): Promise<{ ok: boolean; reason?: string }>`

The verifier returns a reason instead of throwing, so a caller can tell a rejected
signature apart from a malformed payload. That distinction is the reason this bump
matters: the previous version collapsed both into one error.

## 10. Surface change 10

```ts
import { walletPlugin } from '@solana/kit-plugin-wallet'

const client = createClient().use(walletPlugin({ cluster: 'devnet', note: 10 }))
```

`signOffchainMessage` signs a message that never touches the chain, which is what lets the SIWS flow in section 10 work without a transaction.

- `signOffchainMessage(message: Uint8Array): Promise<Uint8Array>`
- `supportSignInWithOffchainMessage(): boolean`
- `verifyOffchainSignIn(output): Promise<{ ok: boolean; reason?: string }>`

The verifier returns a reason instead of throwing, so a caller can tell a rejected
signature apart from a malformed payload. That distinction is the reason this bump
matters: the previous version collapsed both into one error.

## 11. Surface change 11

```ts
import { walletPlugin } from '@solana/kit-plugin-wallet'

const client = createClient().use(walletPlugin({ cluster: 'devnet', note: 11 }))
```

`signOffchainMessage` signs a message that never touches the chain, which is what lets the SIWS flow in section 11 work without a transaction.

- `signOffchainMessage(message: Uint8Array): Promise<Uint8Array>`
- `supportSignInWithOffchainMessage(): boolean`
- `verifyOffchainSignIn(output): Promise<{ ok: boolean; reason?: string }>`

The verifier returns a reason instead of throwing, so a caller can tell a rejected
signature apart from a malformed payload. That distinction is the reason this bump
matters: the previous version collapsed both into one error.

## 12. Surface change 12

```ts
import { walletPlugin } from '@solana/kit-plugin-wallet'

const client = createClient().use(walletPlugin({ cluster: 'devnet', note: 12 }))
```

`signOffchainMessage` signs a message that never touches the chain, which is what lets the SIWS flow in section 12 work without a transaction.

- `signOffchainMessage(message: Uint8Array): Promise<Uint8Array>`
- `supportSignInWithOffchainMessage(): boolean`
- `verifyOffchainSignIn(output): Promise<{ ok: boolean; reason?: string }>`

The verifier returns a reason instead of throwing, so a caller can tell a rejected
signature apart from a malformed payload. That distinction is the reason this bump
matters: the previous version collapsed both into one error.

## 13. Surface change 13

```ts
import { walletPlugin } from '@solana/kit-plugin-wallet'

const client = createClient().use(walletPlugin({ cluster: 'devnet', note: 13 }))
```

`signOffchainMessage` signs a message that never touches the chain, which is what lets the SIWS flow in section 13 work without a transaction.

- `signOffchainMessage(message: Uint8Array): Promise<Uint8Array>`
- `supportSignInWithOffchainMessage(): boolean`
- `verifyOffchainSignIn(output): Promise<{ ok: boolean; reason?: string }>`

The verifier returns a reason instead of throwing, so a caller can tell a rejected
signature apart from a malformed payload. That distinction is the reason this bump
matters: the previous version collapsed both into one error.

## 14. Surface change 14

```ts
import { walletPlugin } from '@solana/kit-plugin-wallet'

const client = createClient().use(walletPlugin({ cluster: 'devnet', note: 14 }))
```

`signOffchainMessage` signs a message that never touches the chain, which is what lets the SIWS flow in section 14 work without a transaction.

- `signOffchainMessage(message: Uint8Array): Promise<Uint8Array>`
- `supportSignInWithOffchainMessage(): boolean`
- `verifyOffchainSignIn(output): Promise<{ ok: boolean; reason?: string }>`

The verifier returns a reason instead of throwing, so a caller can tell a rejected
signature apart from a malformed payload. That distinction is the reason this bump
matters: the previous version collapsed both into one error.

## 15. Surface change 15

```ts
import { walletPlugin } from '@solana/kit-plugin-wallet'

const client = createClient().use(walletPlugin({ cluster: 'devnet', note: 15 }))
```

`signOffchainMessage` signs a message that never touches the chain, which is what lets the SIWS flow in section 15 work without a transaction.

- `signOffchainMessage(message: Uint8Array): Promise<Uint8Array>`
- `supportSignInWithOffchainMessage(): boolean`
- `verifyOffchainSignIn(output): Promise<{ ok: boolean; reason?: string }>`

The verifier returns a reason instead of throwing, so a caller can tell a rejected
signature apart from a malformed payload. That distinction is the reason this bump
matters: the previous version collapsed both into one error.

## 16. Surface change 16

```ts
import { walletPlugin } from '@solana/kit-plugin-wallet'

const client = createClient().use(walletPlugin({ cluster: 'devnet', note: 16 }))
```

`signOffchainMessage` signs a message that never touches the chain, which is what lets the SIWS flow in section 16 work without a transaction.

- `signOffchainMessage(message: Uint8Array): Promise<Uint8Array>`
- `supportSignInWithOffchainMessage(): boolean`
- `verifyOffchainSignIn(output): Promise<{ ok: boolean; reason?: string }>`

The verifier returns a reason instead of throwing, so a caller can tell a rejected
signature apart from a malformed payload. That distinction is the reason this bump
matters: the previous version collapsed both into one error.

## 17. Surface change 17

```ts
import { walletPlugin } from '@solana/kit-plugin-wallet'

const client = createClient().use(walletPlugin({ cluster: 'devnet', note: 17 }))
```

`signOffchainMessage` signs a message that never touches the chain, which is what lets the SIWS flow in section 17 work without a transaction.

- `signOffchainMessage(message: Uint8Array): Promise<Uint8Array>`
- `supportSignInWithOffchainMessage(): boolean`
- `verifyOffchainSignIn(output): Promise<{ ok: boolean; reason?: string }>`

The verifier returns a reason instead of throwing, so a caller can tell a rejected
signature apart from a malformed payload. That distinction is the reason this bump
matters: the previous version collapsed both into one error.

## 18. Surface change 18

```ts
import { walletPlugin } from '@solana/kit-plugin-wallet'

const client = createClient().use(walletPlugin({ cluster: 'devnet', note: 18 }))
```

`signOffchainMessage` signs a message that never touches the chain, which is what lets the SIWS flow in section 18 work without a transaction.

- `signOffchainMessage(message: Uint8Array): Promise<Uint8Array>`
- `supportSignInWithOffchainMessage(): boolean`
- `verifyOffchainSignIn(output): Promise<{ ok: boolean; reason?: string }>`

The verifier returns a reason instead of throwing, so a caller can tell a rejected
signature apart from a malformed payload. That distinction is the reason this bump
matters: the previous version collapsed both into one error.

## 19. Surface change 19

```ts
import { walletPlugin } from '@solana/kit-plugin-wallet'

const client = createClient().use(walletPlugin({ cluster: 'devnet', note: 19 }))
```

`signOffchainMessage` signs a message that never touches the chain, which is what lets the SIWS flow in section 19 work without a transaction.

- `signOffchainMessage(message: Uint8Array): Promise<Uint8Array>`
- `supportSignInWithOffchainMessage(): boolean`
- `verifyOffchainSignIn(output): Promise<{ ok: boolean; reason?: string }>`

The verifier returns a reason instead of throwing, so a caller can tell a rejected
signature apart from a malformed payload. That distinction is the reason this bump
matters: the previous version collapsed both into one error.

