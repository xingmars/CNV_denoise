female_depth.rds: 216x22338 matrix

male_depth.rds: 237x22338 matrix

female_test_depth.rds: 1x22338 matrix

male_test_depth.rds: 4x22338 matrix

Each column is a probe and each row is a control sample withiout CNV. The entry [i,j] is the relative depth of probe j in sample i.


probe_relative_position.bed: bed file of the 22338 probes. The positions are re-located so that the first probe on each chromosome starts at 1. The relative positions between the probes remain the same.
