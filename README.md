### docker-nginx-proxy-1

```
[yuzunoha@localhost docker-nginx-proxy-1]$ cat /etc/os-release
NAME=Fedora
VERSION="31 (Server Edition)"
ID=fedora
VERSION_ID=31
VERSION_CODENAME=""
PLATFORM_ID="platform:f31"
PRETTY_NAME="Fedora 31 (Server Edition)"
ANSI_COLOR="0;34"
LOGO=fedora-logo-icon
CPE_NAME="cpe:/o:fedoraproject:fedora:31"
HOME_URL="https://fedoraproject.org/"
DOCUMENTATION_URL="https://docs.fedoraproject.org/en-US/fedora/f31/system-administrators-guide/"
SUPPORT_URL="https://fedoraproject.org/wiki/Communicating_and_getting_help"
BUG_REPORT_URL="https://bugzilla.redhat.com/"
REDHAT_BUGZILLA_PRODUCT="Fedora"
REDHAT_BUGZILLA_PRODUCT_VERSION=31
REDHAT_SUPPORT_PRODUCT="Fedora"
REDHAT_SUPPORT_PRODUCT_VERSION=31
PRIVACY_POLICY_URL="https://fedoraproject.org/wiki/Legal:PrivacyPolicy"
VARIANT="Server Edition"
VARIANT_ID=server
```

```
[yuzunoha@localhost docker-nginx-proxy-1]$ docker --version
Docker version 19.03.6, build 369ce74a3c
```

```
[yuzunoha@localhost docker-nginx-proxy-1]$ docker-compose --version
docker-compose version 1.25.5, build 8a1c60f6
```

```
[yuzunoha@localhost docker-nginx-proxy-1]$ dnf list | grep docker-ce
containerd.io.x86_64 1.4.3-3.1.fc31 @docker-ce-stable
docker-ce.x86_64 3:19.03.6-3.fc31 @docker-ce-stable
docker-ce-cli.x86_64 1:19.03.6-3.fc31 @docker-ce-stable
docker-ce.x86_64 3:20.10.3-3.fc31 docker-ce-stable
docker-ce-cli.x86_64 1:20.10.3-3.fc31 docker-ce-stable
docker-ce-rootless-extras.x86_64 20.10.3-3.fc31 docker-ce-stable
```
