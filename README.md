# DR-RAID-Performance-Testing
2.1.1.4 Redundant array of independent disks (RAID) support
The storage shall provide a RAID controller and support the following RAID levels:
1.RAID 0 – Striping
2.RAID 1 – Mirroring
3.RAID 5 – Striping with parity
4.RAID 10 – Combining mirroring and striping

Stripe RAID-0
1. Navigate to the pools page
2. Click Create Pool Provide name Stripe
3. Select Disk from the vdev type pulldown
4. Select Disk
5. Set Number of disks to 2
6. Click Create Pool

Mirror RAID-1
1. Navigate to the pools page
2. Click Create Pool Provide name Stripe
3. Select Mirrors from the vdev type pulldown
4. Select Disk
5. Set Number of disks per vdev 2
6. Set Number of vdevs to 1
7. Click Create Pool

8. RAID-5
1. Navigate to the pools page
2. Click Create Pool Provide name Stripe
3. Select RAIDZ-1 from the vdev type pulldown
4. Select Disk
5. Set Number of disks per vdev 4
6. Set Number of vdevs to 1
7. Click Create Pool
8. Pass – Pool Created with structure 4 disks in a RAID-5 (Single parity scheme)

9. RAID-10
1. Navigate to the pools page
2. Click Create Pool Provide name Stripe
3. Select Mirrors from the vdev type pulldown
4. Select Disk
5. Set Number of disks per vdev 2
6. Set Number of vdevs to 2
7. Click Create Pool
8. Pass – Pool Created with structure of four disks in mirrored stripe RAID-10
