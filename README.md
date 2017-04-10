Ouroboros
=====
[![Build Status](https://travis-ci.org/Fondesa/Ouroboros.svg?branch=master)](https://travis-ci.org/Fondesa/Ouroboros)

Ouroboros is an open source library for Android that simplify the save and the restore of Android components' state.
Ouroboros supports automatic save/restore, base coders to serialize/deserialize values in `Bundle`, caching and retrieval of fields. Ouroboros includes a flexible API that allows developers to customize any aforementioned behavior.

By default, Ouroboros uses an internal serializer/deserializer for fields, but also provides a utility library to add serialize/deserialize capabilities of [Gson][1].

[1]: https://github.com/google/gson