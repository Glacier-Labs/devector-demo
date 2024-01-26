## Quickstart

- Config

```
const privateKey = `<your-key>`
const namespace = '<your-ns>'
const dataset = '<your-ds>'
const collection = 'programming'

const hf_token = '<your-hf_token>'
const openai_key = '<your-openai_key>'
```

- Create DeVector collection

```
node vector-demo.js init
```

- Load Embedding Documents

```
node vector-demo.js vector
```

- Chat with documents

```
node vector-demo.js chat <Question?>
```