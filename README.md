female_depth.rds: 216x22338 matrix

male_depth.rds: 237x22338 matrix

Each column is a probe and each row is a control sample withiout CNV. The entry [i,j] is the relative depth of probe j in sample i.


female_depth.rds: 216x3359 matrix

male_depth.rds: 237x3359 matrix

The neighboring probes are merged into a region.


female_test_depth_merged.rds: 50x3359 matrix

male_test_depth_merged.rds: 50x3359 matrix


probe_relative_position.bed: bed file of the 22338 probes. The positions are re-located so that the first probe on each chromosome starts at 1. The relative positions between the probes remain the same.

merged_probe_relative_position.bed: bed file of the 3359 merged regions.
