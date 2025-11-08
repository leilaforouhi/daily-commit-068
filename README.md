def percentage_change(old, new):
    if old == 0:
        return 0
    change = ((new - old) / old) * 100
    return change

if __name__ == "__main__":
    old_value = 80
    new_value = 100
    print(f"Percentage change from {old_value} to {new_value}: {percentage_change(old_value, new_value)}%")
