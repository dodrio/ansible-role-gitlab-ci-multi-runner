# gitlab-ci-multi-runner

[![Build Status](https://travis-ci.org/m31271n/ansible-role-gitlab-ci-multi-runner.svg?branch=master)](https://travis-ci.org/m31271n/ansible-role-gitlab-ci-multi-runner)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-m31271n.gitlab--ci--multi--runner-blue.svg)](https://galaxy.ansible.com/m31271n/gitlab-ci-multi-runner)

Ansible role that installs gitlab-ci-multi-runner.

## Requirements

None.

## Role Variables

+ `gitlab_ci_multi_runner_version`: `9.3.0`

## Dependencies

None.

## Example Playbook

```
- hosts: servers
  roles:
    - role: m31271n.gitlab-ci-multi-runner
      gitlab_ci_multi_runner_version: 9.3.0
```

## Read more
+ https://gitlab.com/gitlab-org/gitlab-ci-multi-runner/blob/master/docs/register/index.md
+ https://docs.gitlab.com/ce/ci/docker/using_docker_build.html

* * *

<p align="center">Made with ❤ by <a href="http://index.m31271n.com">m31271n</a></p>
