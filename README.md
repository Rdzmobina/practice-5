# practice-5

def combine_lists(list1, list2):
    if len(list1) != len(list2):
        raise ValueError("Lists must have same length")

    result = {}
    for i in range(len(list1)):
        result[list1[i]] = list2[i]

    return result
