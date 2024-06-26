## Scores

| Metric      | Count |
|-------------|-------|
| Total Tests | 5     |
| Passed      | 4     |
| Failures    | 1     |
| Errors      | 0     |
| Score       | 80.00% |

## Test Results

| Test Name               | Status   | Assertion                                                                                                                                                                                                                                               |
|:------------------------|:---------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| test_total_distance     | Passed   |                                                                                                                                                                                                                                                         |
| test_distribute_candies | Passed   |                                                                                                                                                                                                                                                         |
| test_adjust_recipe      | Failed   | def test_adjust_recipe():     assert adjust_recipe(2, 8) == 4.0     assert adjust_recipe(0, 5) == 0.0 >    assert adjust_recipe(1, 1) == 2.0 E    assert 0.25 == 2.0 E    + where 0.25 = adjust_recipe(1, 1) tests/test_variables.py:27: AssertionError |
| test_total_cost         | Passed   |                                                                                                                                                                                                                                                         |
| test_calculate_profit   | Passed   |                                                                                                                                                                                                                                                         |
