# lib-ml

Contains the pre-processing logic for data that is used for training or queries.

• Factor out the pre-processing logic from the training pipeline.

• Fetch relevant dependencies through a package manager, e.g., by creating a separate requirements.txt.

• The library is versioned automatically, e.g., by picking-up on the corresponding Git version tag.

• A workflow is used to automatically release the library in a package registry that matches the language. (As stated before, this includes either supported package registries on GitHub or repository tags in languages that support it.)