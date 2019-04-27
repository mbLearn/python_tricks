# python_tricks

# enumerate returns an iterator, which does not support index-based access. 
# You can however slice the original list first, and just start at a different index with enumerate:

test_list = [10, 20, 30, 40, 5, 6, 7, 8, 9, 50, 60, 70]
for i, elm in enumerate(test_list[2:10], 2):
    print i, elm
