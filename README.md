**Spline** (from **Sp**ark **line**age) project helps people get insight into data processing performed by **Apache Spark &trade;**

---

Please find the project documentation, usage examples, building, installation and configuration instructions and other information 
on the Spline website - https://absaoss.github.io/spline

---

    Copyright 2017 Barclays Africa Group Limited
    
    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at
    
        http://www.apache.org/licenses/LICENSE-2.0
    
    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

---
**This is forked from original repo**

> mvn -DskipTests=true -Dspark.version=2.2.0  -Dspark.compat.version=2.2 install
failing for spline-core-spark-adapter-2.3

```
[INFO] Spline ............................................. SUCCESS [  1.791 s]
[INFO] spline-commons ..................................... SUCCESS [ 13.177 s]
[INFO] spline-model ....................................... SUCCESS [ 10.026 s]
[INFO] spline-core-spark-adapter-api ...................... SUCCESS [ 11.331 s]
[INFO] spline-persistence-api ............................. SUCCESS [ 14.983 s]
[INFO] spline-core-spark-adapter-2.2 ...................... SUCCESS [  9.579 s]
[INFO] spline-core ........................................ SUCCESS [ 31.689 s]
[INFO] spline-core-spark-adapter-2.3 ...................... FAILURE [  5.399 s]
[INFO] spline-persistence-mongo ........................... SKIPPED
[INFO] spline-web ......................................... SKIPPED
[INFO] spline-persistence-atlas ........................... SKIPPED
[INFO] spline-persistence-hdfs ............................ SKIPPED
[INFO] spline-sample ...................................... SKIPPED
[INFO] spline 0.3.1 ....................................... SKIPPED
[INFO] spline-persistence 0.3.1 ........................... SKIPPED
```