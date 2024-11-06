# mps_and_reverse_linear_problems
 This study examines the transformation between MPS format and matrix notation, evaluating single-threaded, multi-threaded (Concurrent Futures, Joblib, Multiprocessing), and GPU-based (CUDA) methods for performance. Results show that single-threaded processing outperforms parallel and GPU methods for smaller files due to lower overhead. For larger files, parallel techniques offered slight gains, but interprocess communication setup costs often outweighed these benefits. GPU-based processing was limited by data transfer overhead.   The study also developed JSON-based regular expressions for parsing and reconstructing MPS sections, improving transformation consistency. Due to time constraints, the full reversal of intermediate MPS files was not achieved. Future work includes exploring custom parallel and optimized GPU strategies for better performance.  In conclusion, simpler processing methods work best for small tasks, while parallel or GPU approaches should be tailored for large-scale transformations.
