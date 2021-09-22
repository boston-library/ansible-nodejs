# ansible-nodejs

An Ansible role for installing Node.js.

## Role Variables

- `nodejs_version` - Node.js version (default: `0.10.32`)
- `nodejs_os` - Node.js operating system build (default: `linux`)
- `nodejs_arch`: Node.js architecture build (default: `x64`)
- `nodejs_npm_version`: npm version (default: `1.4.28`)
- `nodejs_symlink_path`: symlink path for node and npm (default: `/usr/local/bin`)

## Reference

This ansible role is taken mostly out of [azavea-nodejs](https://github.com/azavea/ansible-nodejs.git) from Azavea Inc., but I stripped it down for brevity.
