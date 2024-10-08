<!--Copyright 2021 The HuggingFace Team. All rights reserved.

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with
the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on
an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the
specific language governing permissions and limitations under the License.

⚠️ Note that this file is in Markdown but contain specific syntax for our doc-builder (similar to MDX) that may not be
rendered properly in your Markdown viewer.
-->

# DataLoaders, Optimizers, and Schedulers

The internal classes Accelerate uses to prepare objects for distributed training
when calling [`~Accelerator.prepare`].

## DataLoader utilities

[[autodoc]] data_loader.prepare_data_loader
[[autodoc]] data_loader.skip_first_batches

## BatchSamplerShard

[[autodoc]] data_loader.BatchSamplerShard

## IterableDatasetShard

[[autodoc]] data_loader.IterableDatasetShard

## DataLoaderShard

[[autodoc]] data_loader.DataLoaderShard

## DataLoaderDispatcher

[[autodoc]] data_loader.DataLoaderDispatcher

## AcceleratedOptimizer

[[autodoc]] optimizer.AcceleratedOptimizer

## AcceleratedScheduler

[[autodoc]] scheduler.AcceleratedScheduler