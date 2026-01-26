# PairUX RPM Repository

## Installation

### Fedora / RHEL / CentOS

```bash
# Add repository
sudo dnf config-manager --add-repo https://profullstack.github.io/pairux-rpm/pairux.repo

# Import GPG key
sudo rpm --import https://profullstack.github.io/pairux-rpm/RPM-GPG-KEY-pairux

# Install
sudo dnf install pairux
```

### Manual Download

You can also download the RPM directly from the [Packages](./Packages) directory.
