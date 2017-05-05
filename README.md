# m3uspiff
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/17105ee5e1a64cb9891039f7e1228230)](https://www.codacy.com/app/ibrokemypie/m3uspiff_go?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=ibrokemypie/m3uspiff_go&amp;utm_campaign=Badge_Grade)
[![codebeat badge](https://codebeat.co/badges/0e4adbee-bafe-4e6c-b72c-a7ae645e4372)](https://codebeat.co/projects/github-com-ibrokemypie-m3uspiff_go-master)
[![Build Status](https://travis-ci.org/ibrokemypie/m3uspiff_go.svg?branch=master)](https://travis-ci.org/ibrokemypie/m3uspiff_go)
[![codecov](https://codecov.io/gh/ibrokemypie/m3uspiff_go/branch/master/graph/badge.svg)](https://codecov.io/gh/ibrokemypie/m3uspiff_go)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

An M3U to XSPF playlist converter.

## Usage
``./m3uspiff [playlist.m3u]``

Converts M3U format playlists into XSPF (XML Shareable Playlist Format) playlists, using FFMPEG's ffprobe to augment the new playlist with each included song's metadata when available.

## Requirements

* ffmpeg
