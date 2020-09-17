# Usage

```bash
# Run from parent folder
docker run -t --rm -e PLAT=manylinux2010_x86_64 -v (pwd):/io quay.io/pypa/manylinux2010_x86_64 /io/travis/build-wheels.sh
```
