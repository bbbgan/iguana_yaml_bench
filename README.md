This is a project base on [RapidYAML](https://github.com/biojppm/rapidyaml) to compare the RapidYAML and  the Iguana YAML parser.



quick start

clone the repository

```bash
git clone --recursive git@github.com:bbbgan/iguana_yaml_bench.git
cd iguana_yaml_bench
```
If you omit --recursive, after cloning you will have to do `git submodule update --init --recursive` .

start compile

```bash
mkdir build
cd build
cmake -DCMAKE_CXX_STANDARD=20 -DRYML_BUILD_BENCHMARKS=ON ..
make
```

stay in the "build" folder

```bash
./bin/ryml-bm-parse ../bm/cases/appveyor.yml 
./bin/ryml-bm-parse ../bm/cases/travis.yml
```



