Manifest for mirroring a group of Git repository
------------------------------------------------

2021-01-26: Added Jigsaw-Code/outline-client
2021-01-02: Added termux/termux-app
2020-12-30: Added rhiestan/EncFSMP

---

Run the below command to setup a mirror.

```
repo init -u https://github.com/shugaoye/mirror.git --mirror
repo sync
```

### shadowsocks
The following repositories are needed to build shadowsocks-android.

```
  <project name="shadowsocks/badvpn"/>
  <project name="shadowsocks/libancillary"/>
  <project name="shadowsocks/libevent"/>
  <project name="shadowsocks/redsocks"/>
  <project name="shadowsocks/shadowsocks-android"/>
  <project name="shadowsocks/shadowsocks-rust"/>
```