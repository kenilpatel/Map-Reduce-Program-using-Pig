# Map-Reduce-Program-using-Pig

To install Pig and the project:

cd

wget http://mirrors.gigenet.com/apache/pig/pig-0.16.0/pig-0.16.0.tar.gz

tar xfz pig-0.16.0.tar.gz


You may use Pig on your laptop in local mode interactively:

~/pig-0.16.0/bin/pig -x local

Go to project6/examples and look at the join.pig example. You can run it in local mode using:

rm -rf output

~/pig-0.16.0/bin/pig -x local join.pig

The results will be in the directory output. To run project6 in local mode:

cd ~/project6

rm -rf output

~/pig-0.16.0/bin/pig -x local -param P=pixels-small.txt -param O=output histogram.pig
