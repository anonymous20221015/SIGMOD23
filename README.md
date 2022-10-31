Dear Reviewers,

Our query engine is implemented inside the Pixels codebase; therefore, we packed all the source code, including the source code of Pixels here.

The whole codebase consists of two parts: `pixels.zip` and `pixels-trino.zip`.

`pixels.zip` contains the main codebase. After decompression, the source code of our query engine mainly resides in the pixels-lambda, pixels-executor, and pixels-optimizer sub-directories. We also added some functions (e.g., hash code computation on row batches) into pixels-core.

`pixels-trino.zip` contains the connector for Trino. The source code related to our Coordinator and VM workers is here (they run as the connector inside the Trino processes).
