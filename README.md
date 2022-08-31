# Netlink Example (ip address show)

This is a simple example of the code that performs same with the `ip address show` command does.

## Compile

```bash
make all
```

## Run

```bash
./ipaddressshow
```

## Results

```bash
1: lo
    inet 127.0.0.1/8 scope host
    inet6 ::1 scope host
2: ens33
    inet 192.168.230.136/24 brd 192.168.230.255 scope global
    inet6 fe80::56e5:6837:a8c5:2677/64 scope link
3: virbr0
    inet 192.168.122.1/24 brd 192.168.122.255 scope global
4: virbr0-nic
5: docker0
    inet 172.17.0.1/16 brd 172.17.255.255 scope global
```

## Clean

```bash
make clean
```
