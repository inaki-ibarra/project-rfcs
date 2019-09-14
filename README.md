# Project RFCs

A repository that contains RFCs, guides and templates for your project.

> Tip: If you are hosting this for your own project:
> * Rename the this repository to `my-project-rfcs`.
> * Make sure you modified `README.md`, delete this section also.
> * Adjust default templates or make your own.
> * There's no single way to do RFC so apply what works for you.

## Folders

* `rfcs` - this is where all RFCs are located
* `templates` - this contains all the templates

## Format

### Header
- Status: `Proposed` / `Accepted` / `Implemented` / `Obsolete`
- RFC# - Unique identifier for RFC (Initially empty, updated when `status:Accepted`)
- Author - Person who created the RFC with profile link
- Created - When the RFC was initialized
- Implementation - Link to a pull request of implementation (empty while still `status:Proposed`)

### Overview

An abstract or high level summary of the proposal. Keep it simple, short and sweet.

### Objective

This contains the problem and what are you trying to accomplish. You may include goals and non-goals to make sure everyone is on the same page. You may add the impact of the changes when implemented.

### Motivation

This is the driving force to the proposal. Sometimes it's because of a problem or inspiration. If it's a problem, then why should you solve it in the first place? back it with data when necessary. If it's an inspiration, why it is worth doing?.

### Detailed Design

Explain here the proposal in details. How things will work and looks? What changes you want to happen? Show with examples.

### Drawbacks

You should specify the disadvantages associated with the proposal. This is important to understand the tradeoffs and consequences. Be honest.

### Alternatives

State here the other viable options. It can be something you come up with or existing external solutions.

## Submission process

1. Fork this repo.
2. Create a file in inside `rfcs` with filename formatted like `0000-my-rfc-title.md`.
3. Submit a pull request per RFC.

## Acknowledgments

This repo is inspired by [Rust-RFCs](https://github.com/rust-lang/rfcs), [Tensorflow-RFCs](https://github.com/tensorflow/community/blob/master/rfcs/yyyymmdd-rfc-template.md)