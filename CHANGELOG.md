# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [3.2.0](https://github.com/lotusnoir/ansible-system_locales/compare/3.1.0...3.2.0) - 2025-11-26

### Commits

- update main to include success flag at the end to be able to monitor last playbook run [`bdfc570`](https://github.com/lotusnoir/ansible-system_locales/commit/bdfc5703d63206a4a4ba60f57d58c263f1af05b4)

## [3.1.0](https://github.com/lotusnoir/ansible-system_locales/compare/3.0.0...3.1.0) - 2025-11-18

### Commits

- fix molecule test image for rhel8 [`4ed2f0d`](https://github.com/lotusnoir/ansible-system_locales/commit/4ed2f0d92f3867f9f68d6d846af760bf2afb8fc4)
- add oraclelinux10 support + lint and core fixes [`822538a`](https://github.com/lotusnoir/ansible-system_locales/commit/822538af96a517c947f8fb5ea0be35ff19b06b80)

## [3.0.0](https://github.com/lotusnoir/ansible-system_locales/compare/2.0.0...3.0.0) - 2025-10-29

### Commits

- add trixie (debian13) support [`e9988fb`](https://github.com/lotusnoir/ansible-system_locales/commit/e9988fb73dad230a1f2e6fa983b2f05aa2ecd734)
- update core, molecule + gitlab-ci [`5bf8571`](https://github.com/lotusnoir/ansible-system_locales/commit/5bf8571020eebfd26ae79ecc1bada838d55b2875)
- fix lint [`ae9e75f`](https://github.com/lotusnoir/ansible-system_locales/commit/ae9e75f8faff7108b766421c00caed146b7e37fc)
- fix molecule paralelism and little updates [`032d5e3`](https://github.com/lotusnoir/ansible-system_locales/commit/032d5e3943fc51d8a743c9745de9008f23e50c4a)
- add support for ubuntu24 [`9a8c068`](https://github.com/lotusnoir/ansible-system_locales/commit/9a8c068dd637152c73b4f392a674d39a19045a20)
- update molecule [`915f013`](https://github.com/lotusnoir/ansible-system_locales/commit/915f01395d3b0ef9bb60da623a6e61ced0469be8)
- add version on molecule play image to maintain support on old release [`22a4b90`](https://github.com/lotusnoir/ansible-system_locales/commit/22a4b908525a33fa585af091243ad92d79f1212a)
- add redhat 9 to default supported distrib [`bed08fb`](https://github.com/lotusnoir/ansible-system_locales/commit/bed08fb3f1802e26e3ed489cb26e046bbbd9222b)
- change molecule test with en instead of fr to avoid error on redhat [`3a8c474`](https://github.com/lotusnoir/ansible-system_locales/commit/3a8c474109fb177f727254c6789cfc9cb951cead)
- sort testing distrib to avoid random changes [`b3c65a9`](https://github.com/lotusnoir/ansible-system_locales/commit/b3c65a92ff7a9f93b8287914802349fcf2afd358)

## [2.0.0](https://github.com/lotusnoir/ansible-system_locales/compare/1.1.0...2.0.0) - 2023-09-25

### Commits

- update vars [`7037c2a`](https://github.com/lotusnoir/ansible-system_locales/commit/7037c2ab127fe90a8f7522e15e48b423da1c47e1)
- update readme + precommit + include vars [`0773834`](https://github.com/lotusnoir/ansible-system_locales/commit/0773834af7944263fc68fbf6f3f30824b20b4905)
- change import tasks to include in order to support facts on name [`437a51c`](https://github.com/lotusnoir/ansible-system_locales/commit/437a51c709f5e5ee305f43f65cab8ce611552705)
- Add tasks for redhat to set lang for each lc [`913025f`](https://github.com/lotusnoir/ansible-system_locales/commit/913025f6c124f52173d4a0dc4c9166f0b927306e)

## [1.1.0](https://github.com/lotusnoir/ansible-system_locales/compare/1.0.0...1.1.0) - 2023-06-14

### Commits

- add debian12 support [`2230043`](https://github.com/lotusnoir/ansible-system_locales/commit/2230043f49633fefcf71fef949262628307d285e)

## [1.0.0](https://github.com/lotusnoir/ansible-system_locales/compare/0.3.0...1.0.0) - 2023-03-23

### Commits

- add code of conduc and small changes [`acc1b79`](https://github.com/lotusnoir/ansible-system_locales/commit/acc1b798c5e4437ce81a9c78d67256cf5278703e)
- add precommit for lint [`54741d0`](https://github.com/lotusnoir/ansible-system_locales/commit/54741d01f7a18db27a3e11fa5d379f4a33a2be68)
- fix checks [`abb73d7`](https://github.com/lotusnoir/ansible-system_locales/commit/abb73d75588598718116897cb5fde0d728792644)
- add new molecule all scenario [`41011c0`](https://github.com/lotusnoir/ansible-system_locales/commit/41011c0c59fc47a4b0aba3ea8bdbc36e97286c00)
- split distro for molecule tests on ci [`893c7ed`](https://github.com/lotusnoir/ansible-system_locales/commit/893c7ed80fe49aea6450881ccbe51bff02dfbd21)
- update checks and Readme [`be62a8d`](https://github.com/lotusnoir/ansible-system_locales/commit/be62a8ded7b29126b255f1f198e87cd9eb9091f4)
- fix molecule ora9 [`6d28579`](https://github.com/lotusnoir/ansible-system_locales/commit/6d28579d3f3a798a8b886649a7427883c1d01699)
- add french lang and add vars on RedHat [`1895501`](https://github.com/lotusnoir/ansible-system_locales/commit/1895501229d4ecf221b73933ea64a40d5c1a778b)
- update checks [`278fd4d`](https://github.com/lotusnoir/ansible-system_locales/commit/278fd4da98ce1e74661b9e67a83da4297bcc426d)
- fix test and pipeline [`8cd5f9d`](https://github.com/lotusnoir/ansible-system_locales/commit/8cd5f9d1f365314978ef5e94c5920a2c9d15ec2b)

## [0.3.0](https://github.com/lotusnoir/ansible-system_locales/compare/0.2.0...0.3.0) - 2022-07-01

### Commits

- minor: add oracleLinux7 support [`a5b63cf`](https://github.com/lotusnoir/ansible-system_locales/commit/a5b63cf11591197f3fb7f06ac9ac46ec69c5bf77)
- minor: add oracleLinux support + little fixes [`4f8cac0`](https://github.com/lotusnoir/ansible-system_locales/commit/4f8cac08c492c94c0a743d77f913c28c2c77a623)

## [0.2.0](https://github.com/lotusnoir/ansible-system_locales/compare/0.1.0...0.2.0) - 2022-06-02

### Commits

- minor: add ubuntu 22 molecule test + fix lint [`63720e7`](https://github.com/lotusnoir/ansible-system_locales/commit/63720e7368dbf89eb49b9e528389c04161f5aa86)
- fix: remove unsupported centos8 + minor fixes [`f9a19d9`](https://github.com/lotusnoir/ansible-system_locales/commit/f9a19d9610b4ee6fbb45deaa090b4159c8be64ad)

## 0.1.0 - 2021-11-18

### Commits

- fix: Changes on README [`2624abd`](https://github.com/lotusnoir/ansible-system_locales/commit/2624abd4e81b92cdbf08c7b47a698fd1c5fe897a)
- initial commit [`2cd2e2c`](https://github.com/lotusnoir/ansible-system_locales/commit/2cd2e2c2448269bb6acb031a5897819e12d4141d)
