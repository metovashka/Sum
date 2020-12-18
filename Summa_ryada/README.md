# Параллельное суммирование ряда ln2 различными методами

### Реализация средствами C++:
* false_sharing)
* accumulate_aligned
* accumulate_atomic (don't work)
* accumulate_mutex
* accumulate_reduction_static
### Реализация средствами OMP
* false_sharing)
* accumulate_aligned
* accumulate_atomic
* accumulate_mutex
* accumulate_reduction_static
* accumulate_reduction_dynamic