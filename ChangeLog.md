## 0.1.10

Support blaze-builder >= 0.4.  Add `newByteStringBuilderRecv` to Data.Streaming.ByteString.Builder; add modules Data.Streaming.ByteString.Builder.Buffer and  Data.Streaming.ByteString.Builder.Class.

## 0.1.9

Add Data.Streaming.ByteString.Builder

## 0.1.8

Generalise types of run\*Server which never cleanly return [#13](https://github.com/fpco/streaming-commons/pull/13)

## 0.1.7.1

Fix `streamingProcess` so that it doesn't close `Handle`s passed in with
`UseProvidedHandle`.

## 0.1.7

`withCheckedProcess` added.

## 0.1.6

Provide `appCloseConnection` to get the underlying connection from an `AppData`.
