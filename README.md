# Optimizing-MM-OPES
proot="rna" ff="desres" fileroot="${proot}_${ff}" this="mcmu"

mkdir cpts

nm=$(echo "$ng - 1" | bc) dirs=0

dirs=${dirs}" "${i} done

options="-maxh 145 -multidir $dirs
-v -s ${fileroot}_${this}nd.tpr
-x ${fileroot}${this}nd.xtc
-o ${fileroot}${this}nd.trr
-c ${fileroot}${this}nd.gro
-e ${fileroot}${this}nd.edr
-g ${fileroot}${this}nd.log
-plumed plumed.dat
-cpo ${fileroot}${this}nd.cpt
-cpi ${fileroot}${this}_nd.cpt -noappend"
