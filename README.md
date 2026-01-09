## A Language Where Everything Is a Pattern

Buran emerged in 2025. Named for the shuttle, descended from Refal, inspired by Panini, designed for an age of artificial intelligence.

The core idea is simple: everything is a pattern, and all computation is pattern transformation.

```
factorial {
    [0] ↦ [1]
    [𝑛] ↦ [𝑛 × factorial(𝑛 − 1)]
}
```

No special syntax for different constructs. No historical accidents. No "we kept this for backward compatibility." Functions are patterns. Data structures are patterns. Type declarations are patterns. I/O is patterns. It's patterns all the way down.

The syntax uses standard mathematical notation — the same symbols mathematicians have used for centuries. A mathematician can read Buran code like a formula. A linguist can express grammatical rules directly. And an AI system can generate it reliably because there are no special cases to trip over.

Buran supports Unicode identifiers natively. The factorial function can be `factorial` in English, `факториал` in Russian, `階乗` in Japanese, `مضروب` in Arabic.
