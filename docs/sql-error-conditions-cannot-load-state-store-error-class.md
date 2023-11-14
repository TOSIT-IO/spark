---
layout: global
title: CANNOT_LOAD_STATE_STORE error class
displayTitle: CANNOT_LOAD_STATE_STORE error class
license: |
  Licensed to the Apache Software Foundation (ASF) under one or more
  contributor license agreements.  See the NOTICE file distributed with
  this work for additional information regarding copyright ownership.
  The ASF licenses this file to You under the Apache License, Version 2.0
  (the "License"); you may not use this file except in compliance with
  the License.  You may obtain a copy of the License at

     http://www.apache.org/licenses/LICENSE-2.0

  Unless required by applicable law or agreed to in writing, software
  distributed under the License is distributed on an "AS IS" BASIS,
  WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
  See the License for the specific language governing permissions and
  limitations under the License.
---

SQLSTATE: 58030

An error occurred during loading state.

This error class has the following derived error classes:

## CANNOT_READ_CHECKPOINT

Cannot read RocksDB checkpoint metadata. Expected `<expectedVersion>`, but found `<actualVersion>`.

## CANNOT_READ_DELTA_FILE_KEY_SIZE

Error reading delta file `<fileToRead>` of `<clazz>`: key size cannot be `<keySize>`.

## CANNOT_READ_DELTA_FILE_NOT_EXISTS

Error reading delta file `<fileToRead>` of `<clazz>`: `<fileToRead>` does not exist.

## CANNOT_READ_SNAPSHOT_FILE_KEY_SIZE

Error reading snapshot file `<fileToRead>` of `<clazz>`: key size cannot be `<keySize>`.

## CANNOT_READ_SNAPSHOT_FILE_VALUE_SIZE

Error reading snapshot file `<fileToRead>` of `<clazz>`: value size cannot be `<valueSize>`.

## CANNOT_READ_STREAMING_STATE_FILE

Error reading streaming state file of `<fileToRead>` does not exist. If the stream job is restarted with a new or updated state operation, please create a new checkpoint location or clear the existing checkpoint location.

## UNCATEGORIZED



## UNEXPECTED_FILE_SIZE

Copied `<dfsFile>` to `<localFile>`, expected `<expectedSize>` bytes, found `<localFileSize>` bytes.

## UNEXPECTED_VERSION

Version cannot be `<version>` because it is less than 0.

## UNRELEASED_THREAD_ERROR

`<loggingId>`: RocksDB instance could not be acquired by `<newAcquiredThreadInfo>` as it was not released by `<acquiredThreadInfo>` after `<timeWaitedMs>` ms.
Thread holding the lock has trace: `<stackTraceOutput>`

