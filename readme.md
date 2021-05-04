[![Build](https://github.com/haampie-spack/ci-example-2/actions/workflows/ci.yaml/badge.svg)](https://github.com/haampie-spack/ci-example-2/actions/workflows/ci.yaml)

# CI for C / C++ / Fortran / Python projects using Spack

- Set up the latest Spack using https://github.com/haampie/spack-batteries-included
- Use the compilers github actions offers in their images
- Use multiple compilers in a matrix
- Reuse binaries, sources and ccache to speed up your n'th build

All you need is a [workflow](.github/workflows/ci.yaml), an [environment file](tools/environments/ci/spack.yaml) and [spack package](tools/spack/packages/mypkg/package.py)
