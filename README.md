# Telcolearn1


 Update APT News...<img width="922"<img width="930" height="535" alt="Screenshot 2025-11-17 012611" src="https://github.com/user-attachments/assets/788e4e2a-ea1b-41c0-a0dc-89b20e05242f" />
 height="836" alt="Screensh<img width="1888" height="5<img width="1461" height="400" alt="Screenshot 2025-11-16 232628" src="https://github.com/user-attachments/assets/ce80ff02-111f-454d-9d43-e82347f25be6" />
84" alt="Screenshot 2025-11-17 005405" src="https://github.com/user-attachments/assets/838646aa-b515-4a4d-af1a-2eb9140cef8b" />
ot 2025-11-17 012304" src="https://github.com/user-attachments/assets/0e895886-538f-4f6b-b0a5-64b5d784c89c" />
1.sudo apt install
2025-11-17T01:28:12.249620-08:00 DESKTOP-41RQG3V systemd[1]: Starting esm-cache.service - Update the local ESM caches...
2025-11-17T01:28:18.483543-08:00 DESKTOP-41RQG3V systemd-resolved[261]: Clock change detected. Flushing caches.
2025-11-17T01:28:20.542044-08:00 DESKTOP-41RQG3V dbus-daemon[307]: [system] Activating via systemd: service name='org.freedesktop.PackageKit' unit='packagekit.service' requested by ':1.19' (uid=0 pid=1828 comm="/usr/bin/gdbus call --system --dest org.freedeskto" label="kernel")
2025-11-17T01:28:20.570379-08:00 DESKTOP-41RQG3V systemd[1]: Starting packagekit.service - PackageKit Daemon...
2025-11-17T01:28:20.616621-08:00 DESKTOP-41RQG3V systemd[1]: esm-cache.service: Deactivated successfully.
2025-11-17T01:28:20.616892-08:00 DESKTOP-41RQG3V systemd[1]: Finished esm-cache.service - Update the local ESM caches.
2025-11-17T01:28:20.702796-08:00 DESKTOP-41RQG3V PackageKit: daemon start
2025-11-17T01:28:21.220569-08:00 DESKTOP-41RQG3V dbus-daemon[307]: [system] Successfully activated service 'org.freedesktop.PackageKit'
2025-11-17T01:28:21.221074-08:00 DESKTOP-41RQG3V systemd[1]: Started packagekit.service - PackageKit Daemon.
2025-11-17T01:28:30.432594-08:00 DESKTOP-41RQG3V systemd[1]: apt-news.service: Deactivated successfully.



2.mkdir
address: could not read agent port file "/mnt/c/Users/kiran/.ubuntupro/.address": open /mnt/c/Users/kiran/.ubuntupro/.address: no such directory

3.sudo apt install tree
kiran@DESKTOP-41RQG3V:/mnt/c/Users/kiran$ sudo apt install tree
[sudo] password for kiran:
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
The following NEW packages will be installed:
  tree
0 upgraded, 1 newly installed, 0 to remove and 65 not upgraded.
Need to get 47.4 kB of archives.
After this operation, 111 kB of additional disk space will be used.
Get:1 http://archive.ubuntu.com/ubuntu noble-updates/universe amd64 tree amd64 2.1.1-2ubuntu3.24.04.2 [47.4 kB]
Fetched 47.4 kB in 11s (4307 B/s)
Selecting previously unselected package tree.
(Reading database ... 66398 files and directories currently installed.)
Preparing to unpack .../tree_2.1.1-2ubuntu3.24.04.2_amd64.deb ...
Unpacking tree (2.1.1-2ubuntu3.24.04.2) ...
Setting up tree (2.1.1-2ubuntu3.24.04.2) ...
Processing triggers for man-db (2.12.0-4build2) ...


4.tree /
kiran@DESKTOP-41RQG3V:/mnt/c/Users/kiran$ tree /
/
├── Docker
│   └── host
│       ├── Docker desktop.exe
│       ├── bin
│       │   ├── cagent.exe
│       │   ├── docker
│       │   ├── docker-compose
│       │   ├── docker-compose.exe
│       │   ├── docker-credential-desktop.exe
│       │   ├── docker-credential-ecr-login.exe
│       │   ├── docker-credential-wincred.exe
│       │   ├── docker.exe
│       │   ├── extension-admin.exe
│       │   ├── hub-tool.exe
│       │   └── kubectl.exe
│       ├── cli-plugins
│       │   ├── docker-ai.exe
│       │   ├── docker-buildx.exe
│       │   ├── docker-compose.exe
│       │   ├── docker-debug.exe
│       │   ├── docker-desktop.exe
│       │   ├── docker-extension.exe
│       │   ├── docker-init.exe
│       │   ├── docker-mcp.exe
│       │   ├── docker-model.exe
│       │   ├── docker-offload.exe
│       │   ├── docker-sandbox.exe
│       │   ├── docker-sbom.exe
│       │   └── docker-scout.exe
│       ├── com.docker.admin.exe
│       ├── com.docker.backend.exe
│       ├── com.docker.build.exe
│       ├── com.docker.diagnose.exe
│       ├── com.docker.vmm.exe
│       ├── componentsVersion.json
│       ├── config-options.json
│       ├── ddvp.ico
│       ├── docker-desktop.iso
│       ├── docker-desktop.iso.sha256
│       ├── docker-sandboxd.exe
│       ├── dockerd.exe
│       ├── linux-daemon-options.json
│       ├── model-runner
│       │   └── bin
│       │       ├── com.docker.llama-server.digest
│       │       ├── com.docker.llama-server.exe
│       │       ├── com.docker.nv-gpu-info.exe
│       │       ├── ggml-base.dll
│       │       ├── ggml-cpu-alderlake.dll
│       │       ├── ggml-cpu-haswell.dll
│       │       ├── ggml-cpu-icelake.dll
│       │       ├── ggml-cpu-sandybridge.dll
│       │       ├── ggml-cpu-sapphirerapids.dll
│       │       ├── ggml-cpu-skylakex.dll
│       │       ├── ggml-cpu-sse42.dll
│       │       ├── ggml-cpu-x64.dll
│       │       ├── ggml.dll
│       │       ├── llama.dll
│       │       └── mtmd.dll
│       ├── tile-error.png
│       ├── tile-icon.png
│       ├── windows-daemon-options.json
│       └── wsl
│           ├── docker-wsl-cli.iso
│           ├── docker-wsl-cli.iso.sha256
│           ├── ext4.vhdx
│           └── wsl-data.tarchmo
5. ls -l
2025-11-17T02:09:54.195581-08:00 DESKTOP-41RQG3V systemd-resolved[261]: Clock change detected. Flushing caches.
2025-11-17T02:10:15.138416-08:00 DESKTOP-41RQG3V wsl-pro-service[319]: #033[36mINFO#033[0m Daemon: connecting to Windows Agent
2025-11-17T02:10:15.138853-08:00 DESKTOP-41RQG3V wsl-pro-service[319]: #033[37mDEBUG#033[0m Updated systemd status to "Connecting"
2025-11-17T02:10:15.140347-08:00 DESKTOP-41RQG3V wsl-pro-service[319]: #033[33mWARNING#033[0m Daemon: could not connect to Windows Agent: could not get address: could not read agent port file "/mnt/c/Users/kiran/.ubuntupro/.address": open /mnt/c/Users/kiran/.ubuntupro/.address: no such file or directory
2025-11-17T02:10:15.140589-08:00 DESKTOP-41RQG3V wsl-pro-service[319]: #033[36mINFO#033[0m Reconnecting to Windows host in 60 seconds
2025-11-17T02:10:15.140898-08:00 DESKTOP-41RQG3V wsl-pro-service[319]: #033[37mDEBUG#033[0m Updated systemd status to "Not connected: waiting to retry"
2025-11-17T02:10:24.369003-08:00 DESKTOP-41RQG3V systemd-resolved[261]: Clock change detected. Flushing caches.

6.top
kiran@DESKTOP-41RQG3V:/mnt/c/Users/kiran$ top
top - 01:18:59 up 10 min,  2 users,  load average: 0.36, 5.80, 4.66
Tasks:  40 total,   1 running,  39 sleeping,   0 stopped,   0 zombie
%Cpu(s):  0.1 us,  1.4 sy,  0.0 ni, 95.6 id,  2.9 wa,  0.0 hi,  0.0 si,  0
MiB Mem :   3833.2 total,    568.4 free,    758.4 used,   2654.6 buff/cach
MiB Swap:   1024.0 total,   1024.0 free,      0.0 used.   3074.8 avail Mem

    PID USER      PR  NI    VIRT    RES    SHR S  %CPU  %MEM     TIME+
      1 root      20   0   22000  12920   9336 S   0.0   0.3   0:01.55
      2 root      20   0    3072   1920   1792 S   0.0   0.0   0:00.20
      8 root      20   0    3072   1792   1792 S   0.0   0.0   0:00.00
     98 root      19  -1   66820  19016  18120 S   0.0   0.5   0:00.44
    157 root      20   0   25264   6272   4864 S   0.0   0.2   0:00.55
    213 root      20   0    3080   1024    896 S   0.0   0.0   0:00.00
    215 root      20   0    3092   1152   1024 S   0.0   0.0   0:00.00
    217 kiran     20   0    2800   1664   1664 S   0.0   0.0   0:00.01
    218 root      20   0    3076   1024    896 S   0.0   0.0   0:00.00
    219 root      20   0    3092   1024    896 S   0.0   0.0   0:00.09
    220 root      20   0    6824   3968   3456 S   0.0   0.1   0:00.02
    223 kiran     20   0    6068   4864   3328 S   0.0   0.1   0:00.14
    261 systemd+  20   0   21456  12544  10496 S   0.0   0.3   0:00.18
    262 systemd+  20   0   91024   7680   6784 S   0.0   0.2   0:00.41
    306 root      20   0    4236   2432   2304 S   0.0   0.1   0:00.01
    307 message+  20   0    9628   4992   4352 S   0.0   0.1   0:00.19
    317 root      20   0   18040   8320   7424 S   0.0   0.2   0:00.14
    319 root      20   0 1756096  14464  12416 S   0.0   0.4   0:00.24
    324 root      20   0   19552   8192   7040 S   0.0   0.2   0:00.02
    331 syslog    20   0  222508   5504   4352 S   0.0   0.1   0:00.12
    333 root      20   0  107032  22144  13056 S   0.0   0.6   0:00.25
    338 kiran     20   0   20424  11008   9088 S   0.0   0.3   0:00.19
    339 kiran     20   0   21152   3520   1792 S   0.0   0.1   0:00.00
    386 kiran     20   0    6072   4864   3328 S   0.0   0.1   0:00.05
    403 root      20   0    6672   3968   3456 S   0.0   0.1   0:00.00
    445 root      20   0   20436  11264   9088 S   0.0   0.3   0:00.17
    446 root      20   0   21164   3384   1664 S   0.0   0.1   0:00.00
    464 root      20   0    6072   4864   3456 S   0.0   0.1   0:00.04
    675 root      20   0    3096   1156   1024 S   0.0   0.0   0:00.00
    676 root      20   0 1248232  21704  16000 S   0.0   0.6   0:00.12
   1303 root      20   0  370088  20352  17536 S   0.0   0.5   0:00.12
   1308 polkitd   20   0  308164   7680   6912 S   0.0   0.2   0:00.08

   7.chmod 750 readme.txt
   address: could not read agent port file "/mnt/c/Users/kiran/.ubuntupro/.address": open /mnt/c/Users/kiran/.ubuntupro/.address: no such file or directory
2025-11-17T02:16:16.026656-08:00 DESKTOP-41RQG3V wsl-pro-service[319]: #033[36mINFO#033[0m Reconnecting to Windows host in 60 seconds
2025-11-17T02:16:16.027066-08:00 DESKTOP-41RQG3V wsl-pro-service[319]: #033[37mDEBUG#033[0m Updated systemd status to "Not connected: waiting to retry"
2025-11-17T02:16:25.092348-08:00 DESKTOP-41RQG3V systemd-resolved[261]: Clock change detected. Flushing caches.
2025-11-17T02:16:55.143679-08:00 DESKTOP-41RQG3V systemd-resolved[261]: Clock change detected. Flushing caches.
2025-11-17T02:17:02.106232-08:00 DESKTOP-41RQG3V CRON[2216]: (root) CMD (cd / && run-parts --report /etc/cron.hourly)



8. sudo chown root readme.txt
address: could not read agent port file "/mnt/c/Users/kiran/.ubuntupro/.address": open /mnt/c/Users/kiran/.ubuntupro/.address: no such file or directory
2025-11-17T02:20:16.203551-08:00 DESKTOP-41RQG3V wsl-pro-service[319]: #033[36mINFO#033[0m Reconnecting to Windows host in 60 seconds
2025-11-17T02:20:16.203839-08:00 DESKTOP-41RQG3V wsl-pro-service[319]: #033[37mDEBUG#033[0m Updated systemd status to "Not connected: waiting to retry"
2025-11-17T02:20:25.108740-08:00 DESKTOP-41RQG3V systemd-resolved[261]: Clock change detected. Flushing caches.

