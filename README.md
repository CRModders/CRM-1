# CRM-1 // "Mod Repository Spec"

A specification for decentralized Cosmic Reach mod repositories.

## Why?

This spec was created to allow mod developers to have their mods directly downloadable within launchers.

## Format?

See [`spec/`](spec/). We keep each major version separate with the intent to prevent spec changes from breaking software that utilizes CRM-1.

Please note that the `ext` object is for extensions; not regulated by this specification. It is for OPTIONAL additional data like icons that can be utilized by launchers- not crucial information.

This file must be in the root of your repo named `repository.hjson`.

## Notes

- CRM-1 will be elaborated on in the future.
- CRM-1 is currently still in development. Expect breaking changes for a while until we get to a stable point.
