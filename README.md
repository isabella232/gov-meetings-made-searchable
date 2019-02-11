# Government Meetings Made Searchable

This is not an officially supported Google product, though support will be provided on a best-effort basis.

Copyright 2018 Google LLC

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    https://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.



### Introduction

This is project to make the contents of public meetings searchable and discoverable. This
repo is a series of utilities and containers you can use to transcode, transcribe, and
publish content from videos public meetings and hearings.


#### transcode-video-to-audio
This is a container that transcodes a video file to an audio file that is compatible with
the Google Speech API.


#### create-word-list
This is a container that creates a list of words from the Google Speech API responses that
will be used for creating a word cloud.


#### generate-wordcloud
This is a container that creates a word cloud image in PNG format from a list of words
stored on Google Cloud Storage.


#### index-meeting
This is a container that parses Google Speech API responses and writes the contents to an
Elastic Search index in a batch process.