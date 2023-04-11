# Product Review Generator
This model is a fine-tuned version of [distilgpt2](https://huggingface.co/distilgpt2) on a sample of [amazon_us_reviews](https://huggingface.co/datasets/amazon_us_reviews) dataset. The sample was drawn from 'Apparel_v1_00' subset.

## Model description
This model can auto generate review text for apparel products on providing product title, review rating (1-5) and review headline as an input prompt.

The input prompt should be in the format <|BOS|>product_title<|SEP|>product_rating<|SEP|>review_title<|SEP|>. For example,
<|BOS|>Columbia Women's Benton Springs Full-Zip Fleece Jacket<|SEP|>5<|SEP|>Awesome jacket!<|SEP|>.

## Intended uses & limitations
This model is only intended to demonstrate the text generation capabilities of transformer-based models. Do not use it commercially or for any real-life purpose .
The model is trained specifically on 'Apparel_v1_00' dataset. So, using non-apparel product titles in the input prompt may yield  inconsistent results.
## Contributors
[Praveen Sebastian](https://github.com/praveenseb)
## Feedback
Please create an issue in this repo if you have any questions or feedback.
## License
Copyright 2023 Praveen Sebastian

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this software except in compliance with the License.
You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
