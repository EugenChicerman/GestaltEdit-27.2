# GestaltEdit iOS 27.2 port

This fork adds support-detection entries for:
- iOS/iPadOS 27.2 beta 1: `24B5084k`
- iOS/iPadOS 27.2 beta 2: `24B5089g`

The existing MobileGestalt/bad_query implementation and Siri AI region preset are unchanged.

## Important

This is a source-level compatibility port only. It has **not** been tested on a physical iOS 27.2 device in this environment. If Apple changed the `bad_query`/ContainerManager behavior or MobileGestalt cache layout in 27.2, the app may still fail at runtime even though the build-version gate is passed.

Back up the device before applying any MobileGestalt changes.
