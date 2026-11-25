# Display Filters / فلاتر العرض

## English

| Goal | Filter |
|---|---|
| HTTP | `http` |
| HTTPS / TLS | `tls` |
| DNS | `dns` |
| DHCP | `dhcp` |
| ARP | `arp` |
| ICMP | `icmp` |
| TCP | `tcp` |
| UDP | `udp` |
| Specific IP | `ip.addr == 192.168.1.1` |
| Specific Subnet | `ip.addr == 192.168.1.0/24` |
| TCP Port | `tcp.port == 80` |
| UDP Port | `udp.port == 53` |
| SYN only | `tcp.flags.syn == 1` |
| SYN-ACK | `tcp.flags.syn == 1 && tcp.flags.ack == 1` |
| RST | `tcp.flags.reset == 1` |
| FIN | `tcp.flags.fin == 1` |
| Retransmission | `tcp.analysis.retransmission` |
| Lost Segment | `tcp.analysis.lost_segment` |
| HTTP GET | `http.request.method == "GET"` |
| HTTP POST | `http.request.method == "POST"` |
| DNS Query | `dns.flags.response == 0` |
| DNS Response | `dns.flags.response == 1` |
| TLS Handshake | `tls.handshake` |

### Operators
| Operator | Meaning |
|---|---|
| `==` | Equal |
| `!=` | Not equal |
| `>` `<` `>=` `<=` | Comparison |
| `&&` | AND |
| `||` | OR |
| `!` | NOT |
| `contains` | Contains |
| `matches` | Matches regex |

---

## العربية

| الهدف | الفلتر |
|---|---|
| HTTP | `http` |
| HTTPS / TLS | `tls` |
| DNS | `dns` |
| DHCP | `dhcp` |
| ARP | `arp` |
| ICMP | `icmp` |
| TCP | `tcp` |
| UDP | `udp` |
| IP معين | `ip.addr == 192.168.1.1` |
| شبكة معينة | `ip.addr == 192.168.1.0/24` |
| بورت TCP | `tcp.port == 80` |
| بورت UDP | `udp.port == 53` |
| SYN فقط | `tcp.flags.syn == 1` |
| SYN-ACK | `tcp.flags.syn == 1 && tcp.flags.ack == 1` |
| RST | `tcp.flags.reset == 1` |
| FIN | `tcp.flags.fin == 1` |
| إعادة إرسال | `tcp.analysis.retransmission` |
| حزم مفقودة | `tcp.analysis.lost_segment` |
| HTTP GET | `http.request.method == "GET"` |
| HTTP POST | `http.request.method == "POST"` |
| DNS Query | `dns.flags.response == 0` |
| DNS Response | `dns.flags.response == 1` |
| TLS Handshake | `tls.handshake` |

### عمليات المقارنة
| العملية | المعنى |
|---|---|
| `==` | يساوي |
| `!=` | لا يساوي |
| `>` `<` `>=` `<=` | مقارنة |
| `&&` | و (AND) |
| `||` | أو (OR) |
| `!` | نفي (NOT) |
| `contains` | يحتوي |
| `matches` | يطابق regex |
