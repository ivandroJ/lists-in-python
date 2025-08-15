# README

## 📌 Overview
This script demonstrates basic **Python list operations**, including appending, inserting, extending, removing elements, sorting, and finding an element's index.

---

## 📝 Steps Performed

1. **Create an empty list**
   ```python
   my_list = []
   ```

2. **Append elements** (`10`, `20`, `30`, `40`) to the list.
   ```python
   my_list.append(10)
   my_list.append(20)
   my_list.append(30)
   my_list.append(40)
   ```

3. **Insert** the value `15` at the **second position** (index `1`).
   ```python
   my_list.insert(1, 15)
   ```

4. **Extend** the list with another list `[50, 60, 70]`.
   ```python
   my_list.extend([50, 60, 70])
   ```

5. **Remove** the last element (`70`).
   ```python
   my_list.pop()
   ```

6. **Sort** the list in ascending order.
   ```python
   my_list.sort()
   ```

7. **Find the index** of value `30`.
   ```python
   index_of_30 = my_list.index(30)
   ```

8. **Print** the index of `30` and the final list.
   ```python
   print("Index of 30 - ", index_of_30)
   print("Final list - ", my_list)
   ```

---

## 💻 Example Output
```text
Index of 30 -  3
Final list -  [10, 15, 20, 30, 40, 50, 60]
```

---

## 📚 Concepts Covered
- Creating lists
- Appending elements
- Inserting at a specific index
- Extending lists
- Removing elements
- Sorting lists
- Finding an element’s index
