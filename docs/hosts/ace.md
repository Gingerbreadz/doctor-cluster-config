# ace

```
System:
  Host: ace Kernel: 6.7.0 arch: aarch64 bits: 64 compiler: clang v: 14.0.0
    clocksource: arch_sys_counter
    parameters: initrd=\EFI\nixos\22hybvlxjqqbyqcjrpzzxqbgzj7c9y2m-initrd-linux-6.7-initrd.efi
    init=/nix/store/yc457c7fpxc1q3cd3fpdkrakf41a338g-nixos-system-ace-24.11.20250120.643e964/init
    console=ttyS0,115200 console=ttyAMA0,115200 console=tty0 root=fstab loglevel=4
  Console: N/A Distro: NixOS 24.11 (Vicuna)
Machine:
  Type: Desktop System: ARM product: Morello System Development Platform v: N/A serial: N/A
    Chassis: type: 7 serial: N/A
  Mobo: N/A model: N/A serial: N/A part-nu: V2M-MS1DP-0360A
    uuid: d90e12df-90eb-4691-bb26-be325a9defda UEFI: ARM v: EDK II date: Nov 29 2022
Memory:
  System RAM: total: 15.97 GiB available: 15.57 GiB used: 810.4 MiB (5.1%)
  Array-1: capacity: 15.97 GiB slots: 2 modules: 2 EC: Single-bit ECC max-module-size: 7.98 GiB
    note: est.
  Device-1: RDIMM0 type: DDR4 detail: synchronous registered (buffered) size: 7.98 GiB
    speed: 2933 MT/s volts: curr: 1.2 min: 1.2 max: 1.2 width (bits): data: 64 total: 72
    manufacturer: Micron part-no: MTA9ASF serial: N/A
  Device-2: RDIMM1 type: DDR4 detail: synchronous registered (buffered) size: 7.98 GiB
    speed: 2933 MT/s volts: curr: 1.2 min: 1.2 max: 1.2 width (bits): data: 64 total: 72
    manufacturer: Micron part-no: MTA9ASF serial: N/A
PCI Slots:
  Message: No ARM data found for this feature.
CPU:
  Info: model: N/A bits: 64 type: MCP arch: ARMv8 family: 8 model-id: 0 stepping: 0
  Topology: cpus: 1x cores: 4 smt: <unsupported> cache: L1: 512 KiB desc: d-4x64 KiB; i-4x64 KiB
    L2: 4 MiB desc: 4x1024 KiB L3: 2 MiB desc: 2x1024 KiB
  Speed: N/A min/max: N/A base/boost: 2500/2500 volts: 1.0 V ext-clock: 50 MHz cores: No per
    core speed data found. bogomips: 400
  Features: Use -f option to see features
  Vulnerabilities:
  Type: gather_data_sampling status: Not affected
  Type: itlb_multihit status: Not affected
  Type: l1tf status: Not affected
  Type: mds status: Not affected
  Type: meltdown status: Not affected
  Type: mmio_stale_data status: Not affected
  Type: retbleed status: Not affected
  Type: spec_rstack_overflow status: Not affected
  Type: spec_store_bypass mitigation: Speculative Store Bypass disabled via prctl
  Type: spectre_v1 mitigation: __user pointer sanitization
  Type: spectre_v2 status: Not affected
  Type: srbds status: Not affected
  Type: tsx_async_abort status: Not affected
Graphics:
  Message: No PCI device data found.
  Display: server: No display server data found. Headless machine? tty: 80x40
  API: EGL Message: No EGL data available.
  API: OpenGL Message: GL data unavailable in console for root.
Audio:
  Message: No device data found.
Network:
  Device-1: Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet driver: r8169 v: N/A pcie:
    gen: 1 speed: 2.5 GT/s lanes: 1 port: 4000 bus-ID: 07:00.0 chip-ID: 10ec:8168 class-ID: 0200
  IF: enp7s0 state: up speed: 1000 Mbps duplex: full mac: 00:02:f7:00:9c:a5
  IP v4: 131.159.38.181/23 type: dynamic scope: global
  IP v6: 2a09:80c0:38::181/128 type: dynamic noprefixroute scope: global
  IP v6: fe80::202:f7ff:fe00:9ca5/64 virtual: proto kernel_ll scope: link
  IF-ID-1: ip6tnl0 state: down mac: 00:00:00:00:00:00:00:00:00:00:00:00:00:00:00:00
  IF-ID-2: sit0 state: down mac: 00:00:00:00
  IF-ID-3: tinc.retiolum state: unknown speed: 10000 Mbps duplex: full mac: N/A
  IP v6: 42:0:3c46:2844:2a0b:6287:a0e6:5cff/16 scope: global
  Info: services: sshd, systemd-networkd, systemd-timesyncd
  WAN IP: 131.159.38.181
Drives:
  Local Storage: total: 447.13 GiB used: 27.37 GiB (6.1%)
  ID-1: /dev/sda maj-min: 8:0 vendor: SK Hynix model: HFS480G3H2X069N size: 447.13 GiB
    block-size: physical: 4096 B logical: 512 B sata: 3.3 speed: 6.0 Gb/s tech: SSD
    serial: ESC3N5648I3603P2Y fw-rev: DZ02 temp: 41 C scheme: GPT
  SMART: yes state: enabled health: PASSED on: 112d 3h cycles: 88 written: 333 KiB
Partition:
  ID-1: / raw-size: 446.13 GiB size: 438.06 GiB (98.19%) used: 27.28 GiB (6.2%) fs: ext4
    block-size: 512 B dev: /dev/sda2 maj-min: 8:2
  ID-2: /boot raw-size: 1024 MiB size: 1022 MiB (99.80%) used: 91.6 MiB (9.0%) fs: vfat
    block-size: 512 B dev: /dev/sda1 maj-min: 8:1
  ID-3: /home raw-size: N/A size: 2.72 TiB used: 1.86 TiB (68.7%) fs: nfs
    remote: nfs:/export/home
Swap:
  Alert: No swap data was found.
Sensors:
  Src: lm-sensors+/sys Message: No sensor data found using /sys/class/hwmon or lm-sensors.
Info:
  Processes: 109 Power: uptime: 24d 9h 47m states: freeze,mem suspend: deep avail: s2idle
    wakeups: 0 Init: systemd v: 256 default: multi-user tool: systemctl
  Packages: pm: nix-default pkgs: 0 pm: nix-sys pkgs: 543 libs: 124 pm: nix-usr pkgs: 0
    Compilers: gcc: 13.3.0 Client: Sudo v: 1.9.16p2 inxi: 3.3.35
```
![hardware topology](ace.lstopo.svg)
