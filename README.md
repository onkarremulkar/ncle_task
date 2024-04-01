# ncle_task

# Pre Requisite 

## Postman latest version
## Jmeter = 5.6.3

# Postman Execution

Import collection to postman and click on Run to run all the test cases or click on each test case for individual run

# Jmeter Execution

Execute below command on command line.
```
jmeter -JthreadUsers=<total_number_of_threads> -JrampUpPeriod=<ramp_up_time> -JloopCount=<loop_count_for_each_thread> -n -t <jmx_file_path> -l <path_to_generate_log_file_at_that_location> -e -o <path_to_generate_result_folder_at_that_location> -f

```
Default value of "total_number_of_threads", "ramp_up_time" , "loop_count_for_each_thread" is <B>1</B>.

#Test Cases Link

1) <B>Managing Report Templates</B> = "https://onk.testrail.io/index.php?/suites/view/2&group_by=cases:section_id&group_id=7&group_order=asc&display_deleted_cases=0"


2) <B>GitHub API</B> = "https://onk.testrail.io/index.php?/suites/view/1&group_by=cases:section_id&group_order=asc&display_deleted_cases=0"
