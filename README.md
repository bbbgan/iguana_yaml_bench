This is a project base on [RapidYAML](https://github.com/biojppm/rapidyaml) to compare the RapidYAML and  the Iguana YAML parser.



quick start

```bash
mkdir build
cd build
cmake -DCMAKE_CXX_STANDARD=20 -RYML_BUILD_BENCHMARKS=ON ..
make
```

stay in the "build" folder

```bash
./bin/ryml-bm-parse ../bm/cases/appveyor.yml 
./bin/ryml-bm-parse ../bm/cases/travis.yml
```

