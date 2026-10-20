# SSH Config Generator (lite)

Free subset. Two jump-host snippets and a short host-key note. The full pack adds the YAML generator, merge, local forwards, and the six-host inventory.

## English

### Deliverables

- `deliverables/snippets/bastion.conf` — direct bastion on `bastion.example.com`, agent forwarding off
- `deliverables/snippets/jumphost.conf` — `198.51.100.20` port 2222
- `deliverables/KNOWN_HOSTS.md` — ValidateKnownHosts note

Copy a snippet into the client config and set the real key path. Leave `StrictHostKeyChecking yes`. There is no `ValidateKnownHosts` keyword.

The full pack generates the same kind of block from YAML, replaces matching Host blocks, and refuses a config that turns host-key checks off.

Full version: GUMROAD_URL

## 中文

免费子集：两段跳板配置和一段主机密钥说明。完整版另有 YAML 生成器、合并、本地转发，以及六台主机的清单。

### 交付物

- `deliverables/snippets/bastion.conf` — 直连 `bastion.example.com`，不转发 agent
- `deliverables/snippets/jumphost.conf` — `198.51.100.20` 端口 2222
- `deliverables/KNOWN_HOSTS.md` — ValidateKnownHosts 说明

把片段拷进客户端配置，改成你自己的密钥路径。保持 `StrictHostKeyChecking yes`。没有 `ValidateKnownHosts` 这个关键字。

完整版能从 YAML 生成同样的块，替换同名 Host，并拒绝关掉主机密钥检查的配置。

Full version: GUMROAD_URL

## Delivery time / 交付时间

Delivery time: instant download after purchase
