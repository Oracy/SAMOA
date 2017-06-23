# SAMOA

`bin/samoa local target/SAMOA-Local-0.5.0-incubating-SNAPSHOT.jar "PrequentialEvaluation -f 10000 -s (ArffFileStream -f rtg_1m.arff) -d rtg_VHT.txt" `

`bin/samoa local target/SAMOA-Local-0.5.0-incubating-SNAPSHOT.jar "PrequentialEvaluation -f 000 -s (ArffFileStream -f rtg_1m.arff) -d rtg_AdaptiveBagging.txt -l (classifiers.ensemble.AdaptiveBagging)"`
