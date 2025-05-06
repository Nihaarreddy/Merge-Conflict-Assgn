## ASSIGNMENT-3:
   ##  Branching Strategies & Merge Conflicts 

**Task 1: Link to Github Repository**
Github: https://github.com/Nihaarreddy/Merge-Conflict-Assgn
**Task 2: Screenshots showing the merge conflict and resolution process**
**1) Request of Pull Request for feature/add-content branch:**
![Screenshot 2025-05-06 134754](https://github.com/user-attachments/assets/b8a3f7b4-2540-404c-8065-18fc975cd9a0)
**2) Request of Pull REquests for both branches feature/add-content and feature/update/styling:**
![Screenshot 2025-05-06 135019](https://github.com/user-attachments/assets/ed3b47ed-da42-4a66-8161-3dc2a90a1e5a)
**3) Merging of 1st Pull Request from feature/add-content:**
![Screenshot 2025-05-06 135438](https://github.com/user-attachments/assets/fdfe60c6-2943-4841-8191-8e890a3ee7af)
**4) Successful Merging of Pull Request:**
![Screenshot 2025-05-06 135455](https://github.com/user-attachments/assets/da132496-64c4-4f04-a778-07b8f265b12e)
**5) Trying to Merge 2nd Pull Request from feature/update/styling and received a merge conflict**
![Screenshot 2025-05-06 135259](https://github.com/user-attachments/assets/124b3578-cf29-4cb3-9b7d-9ca984800a9e)
**6) Merge-Conflicts between two branches**
![Screenshot 2025-05-06 135352](https://github.com/user-attachments/assets/22cc373f-f661-4ae1-826c-dc54c0404785)
**7) Merging of 2nd Pull Request after resolving of merge conflicts.**
![Screenshot 2025-05-06 135438](https://github.com/user-attachments/assets/a22642ed-43fd-49ad-ba6b-f590e806e201)
**8) Successful Merging of both Pull Requests**
![Screenshot 2025-05-06 135323](https://github.com/user-attachments/assets/d240f93a-e6bf-41db-ad1a-d29182f73a3d)
Explanation on how merge conflicts are resolved:
Conflict Resolution Steps:
Identifing the Conflict: Git alerts you during the merge process.

Editing the Conflicted File (index.html): Look for conflict markers (<<<<<<<, =======, >>>>>>>) indicating different versions.

Manually Resolving the Conflict: Decide which parts of each version to keep and remove the markers.

Marking as Resolved: Use git add index.html after editing.

Committing the Resolution: Run git commit -m "Resolved merge conflict in index.html".

Pushing the Changes: Use git push origin main to update the remote repository.
