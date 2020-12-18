a.out:main.o cpp_accumulator.o num_threads.o run_experiments.o omp_accumulator.o
	g++-10 -fopenmp main.o cpp_accumulator.o num_threads.o run_experiments.o omp_accumulator.o

main.o:main.cpp
	g++-10 -c main.cpp

cpp_accumulator.o:cpp_accumulator.cpp
	g++-10 --std=c++17 -fopenmp -c cpp_accumulator.cpp

run_experiments.o:run_experiments.cpp
	g++-10 --std=c++17 -fopenmp -c run_experiments.cpp

num_threads.o:num_threads.cpp
	g++-10 -fopenmp -c num_threads.cpp

omp_accumulator.o:omp_accumulator.c
	gcc-10 --std=c11 -fopenmp -c omp_accumulator.c