# KernelModuleSkbAnalyser_and_NetfilterHooks

This is kernel module for SKB analyser. You can start network kernel programming from here. This also demonstrates the use of Netfilter hooks.
All pkts going out and coming into your linux machine will be printed in kern.log will all contents of skb buffer.

After compiling (without any warnings), insert kernel module

sudo insmod <.ko file>
check file /var/log/kern.log -- all output goes here
