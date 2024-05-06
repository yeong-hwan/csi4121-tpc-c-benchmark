# csi4121-tpc-c-benchmark

## Import dataset
With the following command you can create TPC-C input with _5_ warehouses. All files are stored in the my_tpcc_input directory. Note: The directory has to exist before starting the generator. But, no worries, if does not exists the generator will complain.

```bash
cd tpcc-generator
make
mkdir my_tpcc_input
./tpcc-generator 5 my_tpcc_input
```

Sample output:
```
I am loading TPCC data for 5 warehouses, hold on ..

Generating warehouse .. ok !
Generating districts .. ok !
Generating customers and their history .. ok !
Generating items .. ok !
Generating stocks .. ok !
Generating orders .. ok !

.. data generation completed successfully :)
```

## Refernces
- [pytpcc](https://github.com/apavlo/py-tpcc)
- [tpcc-generator](https://github.com/alexandervanrenen/tpcc-generator)