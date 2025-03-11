# Project 1 Report: Rafael Singer and Katie Baek

## Running locally:
k=2: xS: 1280703475this_is_a_bitcoin_block_of_71712047_and_80395560, hash value: 008081246edd8eb707bad727d6cecd7eacbb4929a1ae51327530f9a73b009f18, total time elapsed: 3s, number of trials: 100
k=3: xS: 1878244149this_is_a_bitcoin_block_of_71712047_and_80395560, hash value: 0004e4e827f94eebbe9389008cbb1b3ea6631618f5d7ee2951a9cf71bece3a65, total time elapsed: 3s, number of trials: 1000
k=4: xS: 240471751this_is_a_bitcoin_block_of_71712047_and_80395560, hash value: 0000ea0220337f36e768b8a92473989464fb3ce1ab8a2efa522006dbdb5e9a01, total elapsed time: 4s, number of trials: 15000
k=5: xS: 983960859this_is_a_bitcoin_block_of_71712047_and_80395560, hash value: 000005bd27e44ce67845965c8f7daef4b23964553ada3437501cadf6cc840aa5, total elapsed time: 4s, number of trials: 50000
k=6: xS: 134016035this_is_a_bitcoin_block_of_71712047_and_80395560, hash value: 000000f0102d9c6b2d85151f3968e4fe29584194481ecbfc9659893b67a312cf, total elapsed time: 16s, number of trials: 25M

## Running on GCP:
todo

## Random vs Linear Approach:
There are pros and cons to using either approach. We feel that choosing the nonce randomly may lead to collisions (selecting the same nonce) which is a wasted computation so for smaller number of trials the linear approach may be preferable since it guarantees no repetitions. However, for larger number of trials, the random approach for selecting a potential nonce may help you arrive at the correct answer quicker since with teh linear approach, you must start at 0 each time and increment
to a (potentially) very large nonce value.
