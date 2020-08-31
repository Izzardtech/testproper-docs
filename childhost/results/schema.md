# Result Calculation Pattern

- Create ✗ for yet to make, ✓ for done

### Rules

1. Count by Percent (%) OR Points
2. Percentage ranges should be 0 to 100
3. Ranges properties are `FROM, TO, LABEL, COLOR, GRADE` Should be unique
4. Point's ranges should be with minus if applicable to the total points of.
5. If negative is enable negative on false should be smaller then `ZERO`
6. Ranges should coverup the whole points or percentage partitions, without repeatated numbers. eg. 0-50, 51-60, 61-70, 71-80, 81-90, 91-100.
7. Provide default patterns in migration.
8. Provide automagic generated patterns if possible. `eg. Points = 150. Ranges will be like 0-75, 76-90, 91-105, 106-120, 121-135, 136-150.`
9. Provide eligigble schema to the test if total points are same in drop box while select for test.