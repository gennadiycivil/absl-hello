# Copyright 2018 Google Inc.  All rights reserved
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#      http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.

workspace(name = "com_google_absl_hello_world")

# abseil
http_archive(
    name = "absl",
    sha256 = "84c749757edd12da6188a0629a5d26bff8bba72a123b3aa571f4f5d9a03eaee6",
    strip_prefix = "abseil-cpp-8f612ebb152fb7e05643a2bcf78cb89a8c0641ad",
    urls = ["https://github.com/abseil/abseil-cpp/archive/8f612ebb152fb7e05643a2bcf78cb89a8c0641ad.zip"],
)

# Google Test
http_archive(
    name = "gtest",
    sha256 = "d4179caf54410968d1fff0b869e7d74803dd30209ee6645ccf1ca65ab6cf5e5a",
    strip_prefix = "googletest-4e4df226fc197c0dda6e37f5c8c3845ca1e73a49",
    urls = ["https://github.com/google/googletest/archive/4e4df226fc197c0dda6e37f5c8c3845ca1e73a49.zip"],
)
