---
{
    "title": "DROP-SQL-BLOCK-RULE",
    "language": "zh-CN"
}
---

<!--
Licensed to the Apache Software Foundation (ASF) under one
or more contributor license agreements.  See the NOTICE file
distributed with this work for additional information
regarding copyright ownership.  The ASF licenses this file
to you under the Apache License, Version 2.0 (the
"License"); you may not use this file except in compliance
with the License.  You may obtain a copy of the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing,
software distributed under the License is distributed on an
"AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
KIND, either express or implied.  See the License for the
specific language governing permissions and limitations
under the License.
-->

## DROP-SQL-BLOCK-RULE

### Name

DROP SQL BLOCK RULE

## 描述

删除SQL阻止规则，支持多规则，以,隔开

语法：

```sql
DROP SQL_BLOCK_RULE test_rule1,...
```

## 举例

1. 删除test_rule1、test_rule2阻止规则

   ```sql
   mysql> DROP SQL_BLOCK_RULE test_rule1,test_rule2;
   Query OK, 0 rows affected (0.00 sec)
   ```

### Keywords

```text
DROP, SQL_BLOCK_RULE
```

### Best Practice

