# Build containerlabs
```bash
docker-compose up
[+] Running 5/5
 ✔ contaierlab Pulled                                                                                                                                                                 7.4s 
   ✔ 5b91ff7d4a16 Pull complete                                                                                                                                                       6.0s 
   ✔ 4afeeeccd273 Pull complete                                                                                                                                                       5.0s 
   ✔ f18232174bc9 Pull complete                                                                                                                                                       1.1s 
   ✔ 1a074c4fbff5 Pull complete                                                                                                                                                       5.2s 
[+] Running 1/1
 ✔ Container containerlab  Created                                                                                                                                                    0.4s 
Attaching to containerlab
containerlab  | 18:36:36 INFO Containerlab started version=0.68.0
containerlab  | 18:36:36 INFO Parsing & checking topology file=cisco_n9kv.yml
containerlab  | 18:36:36 INFO Creating docker network name=ip-fabric IPv4 subnet=172.30.64.0/20 IPv6 subnet="" MTU=0
containerlab  | 18:36:36 WARN Unable to init module loader: stat /lib/modules/6.6.87.2-microsoft-standard-WSL2/modules.dep: no such file or directory. Skipping...
containerlab  | 18:36:36 INFO Creating lab directory path=/clabs/labs/clab-cisco_n9kv
containerlab  | 18:36:36 INFO Creating container name=nxos9k
containerlab  | 18:36:37 INFO Adding host entries path=/etc/hosts
containerlab  | 18:36:37 INFO Adding SSH config for nodes path=/etc/ssh/ssh_config.d/clab-cisco_n9kv.conf
containerlab  | ╭────────────────────────┬────────────────────────────┬────────────────────┬────────────────╮
containerlab  | │          Name          │         Kind/Image         │        State       │ IPv4/6 Address │
containerlab  | ├────────────────────────┼────────────────────────────┼────────────────────┼────────────────┤
containerlab  | │ clab-cisco_n9kv-nxos9k │ cisco_n9kv                 │ running            │ 172.30.64.11   │
containerlab  | │                        │ quanghong/cisco_n9kv:9.3.8 │ (health: starting) │ N/A            │
containerlab  | ╰────────────────────────┴────────────────────────────┴────────────────────┴────────────────╯
containerlab exited with code 0
```