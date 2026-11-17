# del_vor has moved into LaGriT, as cv_dual

del_vor (Voronoi, median and hybrid control volumes and their
geometric coefficients from Delaunay triangle and tet meshes, written
as FEHM .stor, PFLOTRAN .uge and TOUGH MESH files) is now **cv_dual**,
part of LaGriT:

- code: [lanl/LaGriT, src/cv_dual](https://github.com/lanl/LaGriT/tree/master/src/cv_dual)
- manual: [docs/pages/docs/cv_dual/cv_dual_manual.md](https://github.com/lanl/LaGriT/blob/master/docs/pages/docs/cv_dual/cv_dual_manual.md)
- tests: `test/suite/test_cv_dual_*` in LaGriT
- built with LaGriT, as the program `build/cv_dual`

This repository's whole history was merged into LaGriT in
[lanl/LaGriT#339](https://github.com/lanl/LaGriT/pull/339), so
`git log --follow` on any cv_dual file in LaGriT reaches every commit
made here. The commit IDs there differ from the ones here (the merge
subjects were changed from `#N` to `cwgable/del_vor#N`); the merge
commit's message lists each old ID with its new one.

This repository is archived: read only, kept for its pull requests
and their discussion. The README as it was is in the history (`git
show 0fed2bd:README.md`).
