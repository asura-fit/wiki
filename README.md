wiki
====
メモとか保存用のリポジトリ

git化
---
* `mkdir asura-fit-git; cd asura-fit-git; git init`
* `../fast-export/hg-fast-export.sh -r ../asura-fit/ -A ../authors.map` とかでやった

authors.mapは:

```
cat <<'EOF' | openssl enc -aes-256-cbc -d -base64 -pass pass:いつものやつを2回 -p 
U2FsdGVkX1+J/Sb3CFpiN1KGJw2x/weez1uJ1mzFl/B9d1AL3BORvnj9jMUCwp/7
YatWQP6mxa2i30TdYwygyLq8TyTcqlXMzB2/VtTHuT357Z8QeAwQ7loxFOuk/deP
Lk9Lv48P2Jufxfex+DSDIUfh2MS/nKY95PykTvs0VdPAvQEhgi+7HAySHR1ZwgU9
P53o4cb8Pf459GJSYgaqE9ekNpzEgIohmjR7TcOWcE00Fz6kmkotx4Sk11lrsOAO
e1SXeZ/1bVkyREif65dIj6vYGUYD74kPvKnDt28xakLJWA7Kz2GRqtOQc6lR1Vk3
AgCKHXInWE3DF5U83UMaaBBcpkzTZxkfT75VUYnASMK9jMEB4gvvn3h5TveZ6Uwa
BdVQooGe1wWmZPbrmwN4i2g4bg0yYzNkps2tIGePdZjzPIuOoQgtR3DUGfpbX70L
0a0sQdMfVLCntQDnktUyZZ6YpeNIVqhZLs/a4Z1wfp2GZML+hyAg3Okb9Lo12U2f
Anh6tUU+6BqDIf+Y9TXC1l3Px8vvhUaUN6tBjWQcPArdvfPFlc9l4BBmMWInMlYl
LMizJ3EoiJNI2Q3dNllf3PJefCqxn54eClV2JsmP1FcCOQ0L8WS9FPEXrCRkbQiw
e5kvCowSmpMwgBCL16DByExlidKnK1LxMsMbrgVV9i/2ZIPc585KCoRgZ43mBo94
EOF
```
