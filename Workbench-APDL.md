# :wrench:Workbench中使用APDL修改line单元类型

```
!单元类型
et,matid,link10
!实常数，这里对应的是link10单元的截面积
r,matid,31400
!弹性模量
mp,ex,matid,210000
!密度
mp,dens,matid,7.85e-9
!单元参数配置，1为仅受压，0为仅受拉
keyopt,matid,3,1
```