# sdk-ts-demo

Demo of using the typescript zk-email sdk

## Run a demo file

`bun install`
`bun run src/shortest-example.ts`

```bash
Relayer utils won't work when used server side with bundlers, Next.js etc.
generating proof inputs
got proof input
proof:  {
  pi_a: [ "1941980125578522049693483247944329846442934679734137684230162589114506410436",
    "21222095079545386441921736327569382771800055355985245240789788650572775792182",
    "1"
  ],
  pi_b: [
    [ "17734798737246358619688629395767594692923120297446136184814912420492598693829",
      "12878715620296812029116643590109123330898365348308754178052839040393544359917"
    ], [ "9729044251277121012489575456668368110379358723106933094291086477988154747099",
      "910795206969253633864417516124822606436885116417555116694739816249148027273"
    ], [ "1", "0" ]
  ],
  pi_c: [ "17578573937723854186787828669824787729580706917448799837838991228705020201713",
    "19479654397487947900698979532113144544264087198512551803209308472065174196597",
    "1"
  ],
  protocol: "groth16",
}
public:  {
  subject: "to the Succinct ZK Residency!",
}
```

## IMPORTANT NOTE

The sdk works in the browser and in Node, but NOT on Next.js server side yet.
This is due wasm initialization. We will fix this in the near future.

### 参考文献

1. [Registry - ZKEmail](https://registry.zk.email/)
2. [新しいパターンを作成する](https://zkemail.gitbook.io/zk-email/zk-email-sdk/creating-a-new-pattern)
3. [Emai Wallet - API Documentation](https://zkemail.gitbook.io/zk-email/email-wallet/api-documentation)
4. [Proof of Twitter: ZK Email Demo](https://twitter.prove.email/)
5. [Building Proof of Twitter using ZK Email](https://prove.email/blog/twitter)
6. [ZKEmail - Blog](https://prove.email/blog)
7. [ZKEmail の概要がまとめられたブログ](https://blog.aayushg.com/zkemail/)
8. [ZKEmail - Documentation](https://docs.prove.email/introduction)
