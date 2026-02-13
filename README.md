def remove_duplicates(items):
    unique = []
    for item in items:
        if item not in unique:
            unique.append(item)
    return unique

if __name__ == "__main__":
    data = [1, 2, 2, 3, 4, 4, 5]
    print(f"Original list: {data}")
    print(f"Without duplicates: {remove_duplicates(data)}")
