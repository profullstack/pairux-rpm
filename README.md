# PairUX RPM Repository

RPM repository for PairUX - Fedora/RHEL packages.

## Installation

### Fedora / RHEL / CentOS

```bash
# Add the repository
sudo dnf config-manager --add-repo https://raw.githubusercontent.com/profullstack/pairux-rpm/main/pairux.repo

# Install
sudo dnf install pairux
```

### Manual repo file

Create `/etc/yum.repos.d/pairux.repo`:

```ini
[pairux]
name=PairUX Repository
baseurl=https://profullstack.github.io/pairux-rpm/
enabled=1
gpgcheck=1
gpgkey=https://raw.githubusercontent.com/profullstack/pairux-rpm/main/RPM-GPG-KEY-pairux
```

## Manual Download

You can also download `.rpm` packages directly from [GitHub Releases](https://github.com/profullstack/pairux.com/releases).

## Repository Structure

- `packages/` - RPM package files
- `repodata/` - Repository metadata
- `pairux.repo` - DNF/YUM repository configuration
- `RPM-GPG-KEY-pairux` - Repository GPG public key

## License

MIT License - see [pairux.com](https://github.com/profullstack/pairux.com) for details.
