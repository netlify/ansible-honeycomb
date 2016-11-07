# Introduction

An Ansible role to install [Honeycomb](https://honeycomb.io)'s honeytail log aggregator.

Ansible Honeycomb is released under the [MIT License](LICENSE).
Please make sure you understand its [implications and guarantees](https://writing.kemitchell.com/2016/09/21/MIT-License-Line-by-Line.html).

## Role variables

- `honeytail_token` - Honeycomb write token to send data.
- `honeytail_flags` - Additional flags to configure honeytail.

## Usage

Ensure that the role variables are set. The Honeycomb token can be found in [your account page](https://ui.honeycomb.io/account).
