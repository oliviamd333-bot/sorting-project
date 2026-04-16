# sorting-project
**Algorithm name:** Merge Sort

**Images:**

<img width="539" height="670" alt="Screenshot 2026-04-15 143842" src="https://github.com/user-attachments/assets/0939cfca-84d7-4c30-a315-4ed04ff8aaf6" />

<img width="515" height="440" alt="Screenshot 2026-04-15 144026" src="https://github.com/user-attachments/assets/d941ce43-2e4c-4a7f-953d-36026296c77b" />

**Problem Breakdown & Computational Thinking**

### Decomposition
The problem is broken into smaller steps:
1. Store song data in a list
2. Allow the user to choose a sorting key
3. Apply Merge Sort to organize the list
4. Display the sorted playlist

### Pattern Recognition
The algorithm repeatedly:
- divides the list into smaller halves
- compares elements
- merges them back together in order

### Abstraction
The user only sees the sorted result of the playlist rather than the internal recursion steps of Merge Sort.

### Algorithm Design
Input → User chooses sorting key  
Process → Merge Sort organizes the list  
Output → Sorted playlist is displayed

## Flow 
<img width="1096" height="2011" alt="mermaid-diagram" src="https://github.com/user-attachments/assets/f08d3955-759f-4a34-9733-8735d9cb5b68" />

**Steps to Run:**
1. install dependencies: open command prompt and type "pip install gradio"
2. run the app: then type "python app.py"
3. open the local link shown in terminal: (ex. http://127.0.0.1:7860/)

**Testing & Verification** 

Test Case 1 — Sort by Energy

Input: Playlist of songs with different energy values.
Action: User selects energy as the sorting key.

Expected Result:
Songs appear in ascending order based on energy score.

Actual Result:
The songs were correctly ordered from lowest energy to highest energy.

Test Case 2 — Sort by Duration

Input: Same playlist dataset.
Action: User selects duration as the sorting key.

Expected Result:
Songs appear in ascending order based on duration.

Actual Result:
Songs were correctly sorted by duration from shortest to longest.

Test Case 3 — Small Dataset Edge Case

Input: Playlist containing only one song.

Expected Result:
The algorithm returns the same song without errors.

Actual Result:
The algorithm handled the case correctly.

Test Case 4 — Already Sorted List

Input: Playlist already sorted by energy.

Expected Result:
The playlist remains correctly ordered.

Actual Result:
Merge Sort returned the same correct ordering.

Verification Method

The algorithm result was manually checked to ensure that the songs were ordered correctly based on the selected key.

Screenshots of successful runs are included in the repository.

**Hugging Face Link**: https://huggingface.co/spaces/oliviaaaaaaaamd/sorting-project 

**Author:** Olivia Currie-Davidson

**AI Acknowledgement:** AI tools were used to assist in generating code structure, documentation formatting, and debugging support. The Merge Sort algorithm implementation was reviewed and understood as part of the learning process.
