# **💾 Storage & Filesystems**

*60 CompTIA A+ (220-1101) hardware facts — Objective 1.2 & related.*

---

## **Storage Device Types**

1. **HDD (Hard Disk Drive)** stores data magnetically on spinning platters, using a read/write head.

2. **SSD (Solid State Drive)** uses NAND flash memory for faster access and no moving parts.

3. **NVMe SSD** connects directly to PCIe lanes for ultra-low latency and high throughput.

4. **M.2 SSDs** can be SATA or NVMe; the key notch pattern indicates interface type.

5. **SATA III** interface supports up to 6 Gbps transfer rates.

6. **SAS (Serial Attached SCSI)** is used in enterprise servers for speed and reliability.

7. **Hybrid Drives (SSHD)** combine SSD cache with HDD capacity.

8. **External HDDs/SSDs** connect via USB, Thunderbolt, or eSATA for portable storage.

9. **Optical Discs** include CD, DVD, Blu-ray; used for media and backups.

10. **Tape Drives** provide high-capacity, sequential-access backup storage.

---

## **Performance & Interfaces**

11. **RPM Rating** (e.g., 5400, 7200\) affects HDD read/write performance.

12. **Cache Memory** in drives stores frequently accessed data to boost performance.

13. **U.2 Connector** is used for enterprise NVMe SSDs.

14. **PCIe Gen4** doubles bandwidth compared to Gen3 for NVMe drives.

15. **Hot-swappable bays** allow replacement without shutting down the system.

16. **USB 3.2 Gen 2x2** supports up to 20 Gbps for external storage.

17. **Thunderbolt 4** supports 40 Gbps and daisy chaining of devices.

18. **eSATA** offers SATA speeds externally but has largely been replaced by USB/Thunderbolt.

19. **Fiber Channel Storage** is common in SAN environments.

20. **iSCSI** uses TCP/IP for SCSI commands to remote storage.

---

## **RAID & Redundancy**

21. **RAID 0**: Striping only, max performance, no fault tolerance.

22. **RAID 1**: Mirroring, full redundancy, lower usable capacity.

23. **RAID 5**: Striping with parity, fault tolerance with efficient storage use.

24. **RAID 6**: Dual parity for higher fault tolerance.

25. **RAID 10**: Combines striping and mirroring for speed and redundancy.

26. **Hot Spare Drive** can automatically replace a failed drive in some RAID setups.

27. **JBOD** (“Just a Bunch of Disks”) combines drives without RAID striping or mirroring.

28. **Hardware RAID** uses a dedicated controller card for performance.

29. **Software RAID** uses the host OS for RAID management.

30. **Parity** provides error detection and recovery in RAID arrays.

---

## **File Systems**

31. **NTFS** (Windows default) supports file permissions, encryption, and large file sizes.

32. **FAT32** supports max 4 GB file size, 2 TB partition size, compatible across OSs.

33. **exFAT** supports large files and cross-platform compatibility.

34. **HFS+** is older macOS format, replaced by APFS.

35. **APFS** (Apple File System) optimized for SSDs, supports snapshots and cloning.

36. **EXT4** is default on many Linux distros, supports large volumes and journaling.

37. **XFS** is a high-performance Linux filesystem often used for servers.

38. **Btrfs** supports snapshots, compression, and data integrity checks.

39. **ReFS** (Windows Server) provides data integrity and auto-repair features.

40. **ISO 9660** is standard for optical disc file structures.

---

## **Storage Management & Security**

41. **Disk Partitioning** divides physical storage into logical sections.

42. **Primary Partition** contains the OS in MBR partitioning.

43. **GPT (GUID Partition Table)** supports very large disks and more partitions.

44. **Dynamic Disks** (Windows) allow spanning and mirroring without RAID hardware.

45. **Volume Mount Points** link folders to different partitions or drives.

46. **BitLocker** provides full-disk encryption on Windows.

47. **FileVault** provides full-disk encryption on macOS.

48. **Self-Encrypting Drives (SED)** encrypt data at the hardware level.

49. **TRIM Command** optimizes SSD performance by clearing unused blocks.

50. **SMART Monitoring** predicts HDD/SSD failures.

---

## **Special Storage Concepts**

51. **Cloud Storage** provides offsite, internet-accessible file hosting.

52. **SAN (Storage Area Network)** offers high-speed block-level storage to multiple servers.

53. **NAS (Network Attached Storage)** serves files over network protocols like SMB/NFS.

54. **Direct Attached Storage (DAS)** connects directly to a single computer.

55. **Zoning** in SANs controls which devices can communicate.

56. **Thin Provisioning** allocates storage space on demand.

57. **Over-Provisioning** in SSDs extends lifespan and performance.

58. **Wear Leveling** distributes writes evenly across NAND cells.

59. **Garbage Collection** consolidates free space in SSDs for efficiency.

60. **Data Deduplication** removes duplicate blocks to save space.

