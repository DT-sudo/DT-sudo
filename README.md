## Dmitriy Tereshchenko

**42 Prague · Common Core since September 2024**

I write C and C++98 without frameworks — the curriculum takes them away on
purpose. Most of what is here is a reimplementation of something that already
exists in a library: `printf`, a linked list, a raycasting renderer, an IRC
server, a WordPress stack assembled from empty Debian images. The result is
never the point; knowing what the result costs is.

Two years in, the habits that stuck are reading the failure path first and not
trusting code I haven't run under Valgrind.

Looking for a junior **C++ / systems engineering** role in Prague.

### Selected work

| | | |
| --- | --- | --- |
| **[ft_irc](https://github.com/DT-sudo/ft_irc)** | IRC server, C++98 | A single-threaded `poll()` loop over non-blocking sockets. 16 RFC 1459 commands, channel modes (`+i +t +k +o +l`), operator rights, per-client buffering for messages that arrive in pieces. Built with two teammates. |
| **[cub3D](https://github.com/DT-sudo/cub3d)** | Raycasting engine, C | A Wolfenstein-style renderer on MiniLibX: per-column ray casting, wall textures chosen by orientation, and a scene parser that refuses to draw a frame until it has proven the map is closed. Built with a teammate. |
| **[Inception](https://github.com/DT-sudo/Inception)** | Docker infrastructure | NGINX + WordPress/php-fpm + MariaDB, each from a hand-written Dockerfile on `debian:bookworm-slim` — nothing pulled ready-made from Docker Hub. TLS 1.2/1.3 only, one port open, secrets kept out of the image layers. |
| **[Philosophers](https://github.com/DT-sudo/Philosophers)** | Concurrency, C | pthreads and mutexes with a separate monitor thread watching for starvation. Making it run is the easy half; making it stop cleanly the millisecond a philosopher dies is the other one. |
| **[push_swap](https://github.com/DT-sudo/push_swap)** | Sorting, C | A greedy cost-based sort across two stacks: for every element, price the rotations both stacks need, play the cheapest. Averages ~570 operations for 100 numbers and ~5,150 for 500 — both inside the top grading band. |
| **[minitalk](https://github.com/DT-sudo/minitalk)** | IPC, C | A client and a server passing strings one bit at a time over `SIGUSR1` / `SIGUSR2`, with acknowledgement in both directions. |

The rest of the Common Core — [libft](https://github.com/DT-sudo/libft),
[ft_printf](https://github.com/DT-sudo/ft_printf),
[get_next_line](https://github.com/DT-sudo/get_next_line),
[Born2beroot](https://github.com/DT-sudo/Born2beroot),
[NetPractice](https://github.com/DT-sudo/NetPractice) and the C++ modules —
each lives in its own repository.

### Day to day

C · C++98 · pthreads · POSIX sockets · Docker · Make · Bash · GDB · Valgrind · Debian

### Elsewhere

[tereshchenkovital@gmail.com](mailto:tereshchenkovital@gmail.com) · [LinkedIn](https://www.linkedin.com/in/dmitriy-tereshchenko-158130286/) · Prague, Czech Republic
