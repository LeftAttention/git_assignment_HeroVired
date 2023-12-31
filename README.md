# git_assignment_HeroVired
Source code of Assignment on Git and GitHub

## Calculator Plus (Q1)

Welcome to the Calculator Plus repository! This README provides an overview of the development activities and releases of the Calculator Plus app.

### Development Timeline

#### 1. Repository Creation
- **Activity**: Initialized the repository for Calculator Plus.

#### 2. Development of Basic Calculator App (`dev` branch)
- **Activity**: Developed a basic calculator app capable of addition, subtraction, multiplication, and division in the `dev` branch.
- **Milestone**: Merged the `dev` branch with the `main` branch.
- **Release**: Version 1.0 launched with basic arithmetic functionalities.

#### 3. Square Root Feature Development (`feature/sqrt` branch)
- **Activity**: Created the `feature/sqrt` branch for the development of the square root feature.
- **Enhancement**: Implemented the square root functionality in this branch, extending the capabilities of our calculator app.

#### 4. Divided by Zero Bug Fix (`dev` branch)
- **Activity**: Identified and resolved a critical bug related to division by zero in the `dev` branch.
- **Improvement**: Enhanced the robustness and reliability of the calculator app.

#### 5. Pull Request and Code Review
- **Activity**: Initiated a pull request from `feature/sqrt` to `dev` for the integration of the square root feature.
- **Process**: The pull request is currently open for code review, inviting team members to contribute their feedback and suggestions.

#### 6. Testing and Final Merge
- **Activity**: Conducted thorough testing on the `dev` branch after integrating the square root feature.
- **Milestone**: Following a successful review and testing phase, the enhanced `dev` branch was merged with the `main` branch.

#### 7. Release of Version 1.1
- **Release**: Launched Version 1.1 of Calculator Plus.
- **Features in this Release**: 
   - Basic arithmetic operations (addition, subtraction, multiplication, division)
   - Square root functionality
   - Bug fix for division by zero error




## Git LFS (Q2)

### 1. Install Git LFS
- **On macOS**: `brew install git-lfs`

### 2. Initialize Git LFS
```bash
cd git_assignment_HeroVired
git lfs install
```

### 3. Track Large Files with Git LFS
```bash
git lfs track "*.bin"
```

### 4. Add .gitattributes to the Repository
```bash
git add .gitattributes
git commit -m "Configure Git LFS tracking"
```

### 5. Add and Commit Large Binary Files
```bash
git add path/to/large-file.bin
git commit -m "Add large binary file"
```

### 6. Push to the Remote Repository
```bash
git push origin main
```

### 7. Clone the Repository on Another Machine
```bash
git clone https://github.com/LeftAttention/git_assignment_HeroVired.git
```

### 8. Check Git LFS Files
```bash
git lfs ls-files
```


## Git Stash (Q3)

### Creating and Working on the Circle Area Feature

1. **Creating a New Branch for Circle Area**:
   ```bash
   git checkout -b feature/circle-area
   ```

2. **Working on Circle Area Feature**:
   - Implementing the feature for calculating the area of a circle in this branch.

3. **Stash Changes**:
   - If the implementation is incomplete and we need to switch tasks:
     ```bash
     git stash
     ```
   - Verify the working directory is clean:
     ```bash
     git status
     ```

### Creating and Working on the Rectangle Area Feature

4. **Creating a New Branch for Rectangle Area**:
   ```bash
   git checkout -b feature/rectangle-area
   ```

5. **Working on Rectangle Area Feature**:
   - Implementing the feature for calculating the area of a rectangle in this branch.

6. **Stash Changes**:
   - Again, if the implementation is incomplete:
     ```bash
     git stash
     ```
   - Check the working directory:
     ```bash
     git status
     ```

### Completing and Merging the Circle Area Feature

7. **Switching Back to Circle Area Branch**:
   ```bash
   git checkout feature/circle-area
   ```

8. **Retrieving Stashed Changes**:
   ```bash
   git stash pop
   ```

9. **Complete Circle Area Implementation**:
   - Finish the implementation and test it.
   - Commit the changes:
     ```bash
     git add .
     git commit -m "Implement circle area calculation"
     ```

10. **Push Circle Area Feature**:
    ```bash
    git push origin feature/circle-area
    ```

### Completing and Merging the Rectangle Area Feature

11. **Switch Back to Rectangle Area Branch**:
    ```bash
    git checkout feature/rectangle-area
    ```

12. **Retrieve Stashed Changes**:
    ```bash
    git stash pop
    ```

13. **Complete Rectangle Area Implementation**:
    - Finalize the implementation and test it.
    - Commit the changes:
      ```bash
      git add .
      git commit -m "Implement rectangle area calculation"
      ```

14. **Push Rectangle Area Feature**:
    ```bash
    git push origin feature/rectangle-area
    ```

### Creating Pull Requests and Merging

15. **Create Pull Requests**:
    - Create pull requests for both branches (`feature/circle-area` and `feature/rectangle-area`) to merge into the `dev` branch.

16. **Review and Merge**:
    - Requesting a review from a team member.
    - After approval, merging the pull requests into the `dev` branch.
    - Finally, merging the `dev` branch into the main branch after thorough testing.

---

**Note**: This README is subject to updates and changes as the project evolves. Stay tuned for the latest developments! 🚀🧮