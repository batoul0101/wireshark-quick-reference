# Capture Filters / فلاتر الالتقاط

## English

| Goal | Filter |
|---|---|
| Specific IP | `host 192.168.1.1` |
| Entire Subnet | `net 192.168.1.0/24` |
| Specific Port | `port 80` |
| Multiple Ports | `port 80 or port 443` |
| TCP only | `tcp` |
| UDP only | `udp` |
| ICMP only | `icmp` |
| Exclude IP | `not host 192.168.1.1` |
| Specific Source | `src host 192.168.1.1` |
| Specific Destination | `dst host 192.168.1.1` |
| Source & Destination | `src host 10.0.0.1 and dst host 10.0.0.2` |
| Exclude ARP | `not arp` |
| Exclude Port 22 | `not port 22` |

### Difference between Capture Filter and Display Filter
- **Capture Filter:** Prevents packets from being recorded. Uses BPF syntax.
- **Display Filter:** Hides packets from view after recording. Uses Wireshark syntax.

---

## العربية

| الهدف | الفلتر |
|---|---|
| IP معين | `host 192.168.1.1` |
| شبكة كاملة | `net 192.168.1.0/24` |
| بورت معين | `port 80` |
| بورتات متعددة | `port 80 or port 443` |
| TCP فقط | `tcp` |
| UDP فقط | `udp` |
| ICMP فقط | `icmp` |
| استبعاد IP | `not host 192.168.1.1` |
| مصدر معين | `src host 192.168.1.1` |
| وجهة معينة | `dst host 192.168.1.1` |
| مصدر ووجهة | `src host 10.0.0.1 and dst host 10.0.0.2` |
| بدون ARP | `not arp` |
| بدون بورت 22 | `not port 22` |

### الفرق بين Capture Filter و Display Filter
- **Capture Filter:** يمنع الحزم من التسجيل أصلًا. يستخدم صيغة BPF.
- **Display Filter:** يخفي الحزم من العرض فقط بعد التسجيل. يستخدم صيغة Wireshark.
