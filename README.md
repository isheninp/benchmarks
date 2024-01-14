# Simple bash benchmarks
## HDD CPU RAM

Usage:
```
cd some_hdd_folder
git clone https://github.com/isheninp/benchmarks.git benchmarks && cd benchmarks
```
run all
```
bash all
```

run separately
```
bash cpu
bash hdd
bash hdd_simple
bash ram
```

Warning!
RAM test creates ram disk, root access!

Be sure tmpfs ramdisk is unmounted after run mem test. 
If something was wrong just run:
```
umount -f ramtest && rm -rf ramtest
```

(c) Pavel Ishenin 2020
