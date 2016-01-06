Samples that demonstrate using [Tesseract .Net Wrapper](https://github.com/charlesw/tesseract).

## ConsoleDemo

A short demo that ocr's an image and prints out the results using both Page.GetText()
and a result iterator.

## Web Demo

A simple demonstration of using Tesseract from within ASP.NET.

**Warning:** To keep things simple the sample will create a new instance of the TesseractEngine
each time a image is processed. However this is not performant as creating a new TesseractEngine
is expensive and would be a good candiate for pooling to allow a single engine instance to be
reused.

## License

Copyright 2012-2015 Charles Weld.

Licensed under the [Apache License, Version 2.0][apache2] (the "License"); you
may not use this software except in compliance with the License. You may obtain
a copy of the License at:

[http://www.apache.org/licenses/LICENSE-2.0][apache2]

Unless required by applicable law or agreed to in writing, software distributed
under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR
CONDITIONS OF ANY KIND, either express or implied. See the License for the
specific language governing permissions and limitations under the License.