# Class5homewrok

0) Download data

1) Set up file using $argparse:
   $parser.add_argument("new_file")
   $parser.add_argument("new_file",type=str, help="Path to the input csv file" )
   $new_file = args.new_file

1.1) adding header #needs to verify in Python
    $col_Names = ["header1", "header2", "header3".....]
    $new_file = pd.read_csv("yourCSVFile.csv", names=col_Names)   

2) Load the data in the right format
   $ data = pd.read_csv(new_file, sept='\s+|,', header=None)

3) Set up the header dynamically:

3.1) adding header #needs to verify in Python
   $col_Names = ["header1", "header2", "header3".....]
   $new_file = pd.read_csv("yourCSVFile.csv", names=col_Names)  


4) Compute summary statistics
   - Mean
     $np.mean(data)
   - Standard deviation
     $np.srd(data)
   - Median
     $np.average(data)

5) Visualize data:
    import matplotlib.pyplot
   - plot for all features in one hystogramme and show it
   - show each feature separately and record it
   - compare every 2 feature at a time and record it
   - build correlation/plot scatter and record it
