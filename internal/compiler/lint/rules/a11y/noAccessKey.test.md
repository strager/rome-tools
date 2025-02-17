# `harness.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/compiler/lint/rules/harness.test.ts --update-snapshots` to update.

## `a11y/noAccessKey`

### `0`

```

 lint/a11y/noAccessKey/reject/1/file.tsx:1:7 lint/a11y/noAccessKey  FIXABLE  ━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Avoid the accessKey attribute to reduce inconsistencies between keyboard shortcuts and screen
    reader keyboard comments.

    <input accessKey='key' />
           ^^^^^^^^^^^^^^^

  ℹ Assigning keyboard shortcuts using the accessKey attribute leads to inconsistent keyboard
    actions across applications.

  ℹ Safe fix

  - <input·accessKey="key"·/>
  + <input·/>


```

### `0: formatted`

```tsx
<input />;

```

### `1`

```

 lint/a11y/noAccessKey/reject/2/file.tsx:1:7 lint/a11y/noAccessKey  FIXABLE  ━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Avoid the accessKey attribute to reduce inconsistencies between keyboard shortcuts and screen
    reader keyboard comments.

    <input accessKey={key} />
           ^^^^^^^^^^^^^^^

  ℹ Assigning keyboard shortcuts using the accessKey attribute leads to inconsistent keyboard
    actions across applications.

  ℹ Safe fix

  - <input·accessKey={key}·/>
  + <input·/>


```

### `1: formatted`

```tsx
<input />;

```

### `2`

```

```

### `2: formatted`

```tsx
<input />;

```

### `3`

```

```

### `3: formatted`

```tsx
<input accessKey={undefined} />;

```

### `4`

```

```

### `4: formatted`

```tsx
<Input accessKey={key} />;

```

### `5`

```

 lint/a11y/noAccessKey/reject/1/file.html:1:7 lint/a11y/noAccessKey  FIXABLE  ━━━━━━━━━━━━━━━━━━━━━━

  ✖ Avoid the accessKey attribute to reduce inconsistencies between keyboard shortcuts and screen
    reader keyboard comments.

    <input accesskey="h" />
           ^^^^^^^^^^^^^

  ℹ Assigning keyboard shortcuts using the accessKey attribute leads to inconsistent keyboard
    actions across applications.

  ℹ Safe fix

  - <input·accesskey="h"·/>
  + <input·/>


```

### `5: formatted`

```html
<input />

```

### `6`

```

```

### `6: formatted`

```html
<input />

```
