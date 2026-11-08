<h1 align=center>Dockette / Perl</h1>

<p align=center>
   <a href="https://hub.docker.com/r/dockette/perl"><img src="https://img.shields.io/docker/pulls/dockette/perl.svg" alt="Docker Hub pulls"></a>
   <a href="https://github.com/sponsors/f3l1x"><img src="https://img.shields.io/badge/sponsor-GitHub%20Sponsors-ea4aaa" alt="GitHub Sponsors"></a>
   <a href="https://github.com/orgs/dockette/discussions"><img src="https://img.shields.io/badge/support-discussions-6f42c1" alt="Support/Discussions"></a>
</p>

<p align=center>
   🎁 Debian with Perl and Perl::Critic in Docker
</p>

-----

> [!WARNING]
> **Deprecated.** This image is no longer maintained or rebuilt, and the repository is archived. The last image on
> Docker Hub was built in 2021 on Debian `jessie` (`dockette/jessie`), which is end-of-life. Use the official [`perl`](https://hub.docker.com/_/perl) image instead.

Debian `jessie` with Perl and Perl::Critic (`libperl-critic-perl`). The default command is `perl`.

## Usage

```sh
docker run -v /path/to/site:/srv dockette/perl
```

## Maintenance

See [how to contribute](https://github.com/dockette/.github/blob/master/CONTRIBUTING.md) to this package. Consider to
[support](https://github.com/sponsors/f3l1x) **f3l1x**. Thank you for using this package.
