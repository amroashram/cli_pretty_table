# cli_pretty_table
 converts a 2d dictionary to a CLI pretty table 
## Options : 

    --json_raw converts json list to text table 
        Example : 
            # python cli_pretty_table.py --json_raw '[{"name":"amr","age":"20"},{"name":"hamed","age":"32"}]'
            +-------+-----+
            | name  | age |
            +-------+-----+
            | amr   | 20  |
            +-------+-----+
            | hamed | 32  |
            +-------+-----+

    --json_file file_path 
        Example : 
            # python cli_pretty_table.py --json_file test.json
