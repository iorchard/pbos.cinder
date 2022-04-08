# Changelog

## 1.0.1 - 2022-04-08

* Feat: Modify /etc/lvm/lvm.conf

  - set  thin_pool_autoextend_threshold to 70 to prevent thin pool metadata 
    explosion when LVM is the cinder backend.

