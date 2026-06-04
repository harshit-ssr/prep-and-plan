# TCS CodeVita Exam Preparation Guide
> **Organizer:** Tata Consultancy Services (TCS)¹ | **Type:** Competitive Programming & Recruitment Drive¹ | **Frequency:** Annual / Seasonal¹ | **Difficulty:** Advanced / Elite¹⁶

## Quick Facts
| Field | Details |
|---|---|
| Eligibility | Undergraduates, postgraduates, and diploma holders from all engineering and science disciplines. Requires a minimum aggregate of 60% (or 6.0 CGPA) across 10th, 12th, and UG/PG semesters (waivable for exceptional performers). Maximum 1 active backlog at application (0 at joining), and max 24 months academic gap.¹¹ |
| Age Limit | Below 30 years at the time of application.⁹ |
| Attempts | Multiple attempts allowed across different seasons (subject to graduation year eligibility).⁹ |
| Score Valid | Current recruitment cycle. |

## Exam Pattern
TCS CodeVita is a multi-round competitive programming contest. There is no explicit negative marking, but a dynamic time-based tie-breaker mechanism ranks candidates with identical scores based on the total time taken to successfully execute solutions from the start of the contest.²⁶

* **Round 1 (Pre-Qualifier):** An online, unproctored 6-hour coding contest containing 6 questions of varying difficulty.²⁵ Local IDEs and reference documentation are allowed, but strict Abstract Syntax Tree (AST)-based plagiarism detection checks (similar to Stanford MOSS) are enforced.²⁸,⁴²
* **Verification Round (Tag Test):** A critical in-person, heavily proctored 90-minute examination at designated TCS iON centers.⁵ Candidates must solve 2 algorithmic problems (typically 1 easy-medium, 1 medium-hard) on a localized platform without internet, personal references, or AI assistance.⁵
* **Round 2 (Qualifier):** An online 8-hour coding contest containing 8 highly complex algorithmic challenges for the top performers of Round 1.²⁵
* **Grand Finale:** An in-person 10-question coding arena at TCS offices where elite global programmers compete for a $20,000 USD prize pool.¹⁶

## Syllabus
The exam has no rigidly published syllabus, but it tests advanced algorithmic and problem-solving concepts. Problem statements are typically long and verbose.¹⁶,¹⁷

### Core Technical Domains
* **Arrays & Strings:** Multi-dimensional arrays, Sliding Window, Subsequence matching, String parsing (e.g., *Prime Time Again*, *Constellation*, *Minimum Gifts*).⁹
* **Linear Structures:** Stacks for expression evaluation, Queues for scheduling, Linked Lists (e.g., *Railway Station*, *Collision Course*).⁹
* **Non-Linear Structures:** Binary Search Trees (BST), Hash Maps, Segment Trees, Graph Adjacency.⁹
* **Optimization Logic:** Dynamic Programming (Subsequence, Table Building, memoization, tabulation), Greedy Approach, Binary Search (e.g., *Minimize the Sum*, *Count Pairs*).⁹,¹⁸,²⁰
* **Exploratory Logic:** Backtracking (Permutations), BFS, DFS, Dijkstra's Shortest Path Algorithm (e.g., Maze navigation, Network routing).¹⁸
* **Computational Math:** Prime Theory, Combinatorics, Modulo Arithmetic, Bitwise manipulation (e.g., *Prime Fibonacci*, *Square Free Numbers*).⁹

### Complexity & Compiler Constraints
* **Supported Languages:** C, C++, C#, Java, Perl, Python, Ruby, PHP.¹
* **Time Complexity Constraints:** Code must be optimized to run within strict time limits (typically 1-2 seconds), requiring logarithmic ![][image3] or linearithmic ![][image4] optimizations instead of brute-force quadratic ![][image1] algorithms when parameter volumes exceed ![][image2] inputs.⁹,²⁴
* **Grader Return Statuses:**
  * **Compilation Error (CTE):** Syntax violations or compiler issues.³¹
  * **Run Time Error (RTE):** Illegal memory access, null pointer, array out-of-bounds, or segmentation fault.²⁴,³¹
  * **Time Limit Exceeded (TLE):** Suboptimal time complexity failing maximum constraint checks.²⁴
  * **Presentation Error (PE):** Whitespace/newline mismatch (functionally treated as **Accepted**; candidates should not waste time trying to fix it).³³

## Target Score (General Category)
* **Round 1 (Pre-Qualifier):** Flawless execution of 1 to 2 highly complex problems, or partial execution across 3 problems. Achieving a global rank within the top 1,000 typically guarantees direct escalation to interviews or the highest tiers of the Verification Round.³,⁷
* **Verification Round (Tag Test):** Full execution of the easy-to-medium problem and passing public test cases for the medium-to-hard problem is the typical cutoff for mid-tier interviews. Flawless execution of both problems is required for the elite Prime tier.⁷

## Preparation Timeline
A 4 to 6-month preparation window is ideal, structured into the following phases:⁵
* **Phase 1: Foundation (Months 1-2):** Focus on language syntax, Arrays, Strings, Basic Math, and STL/Collections. Target: subconscious coding fluency without syntax lookup.⁵
* **Phase 2: Intermediate (Months 3-4):** Focus on Stacks, Queues, Trees, Binary Search, and Greedy Algorithms. Target: ability to handle constraints up to ![][image4].⁵,²¹
* **Phase 3: Advanced (Month 5):** Focus on Dynamic Programming, Graphs (BFS/DFS/Dijkstra), and Backtracking. Target: mastery over state-space modeling and optimization.⁵,¹⁸
* **Phase 4: Simulation (Month 6 / Final 4 Weeks):** Focus on blank notepad coding, 90-minute timed sprints, and historical questions. Target: peak psychological readiness for the offline proctored Tag Test.⁵

## Best Free Resources
* **🎥 YouTube:**
  * *Coders Arcade* (deep dives into the 4-week Tag Test roadmap, formatting, and structures)⁵
  * *Anurag Srivastava* (real-time updates on cutoffs, syllabus PDFs, and round transitions)⁵⁰
* **🌐 Websites:**
  * *Placement lelo* (comprehensive PDFs breaking down topic-wise logic for past questions)¹⁷
  * *LeetCode* and *Codeforces* (indispensable for dynamic programming and graph practice under time constraints)²¹
* **📄 PDFs / GitHub:**
  * `j33l/TCS-CodeVita-practice-problems` (rigorous Python solutions for past problems)⁴⁷
  * `doondi30/TCS-NQT-Practice` (detailed Java/Python solutions to all TCS coding sheets)⁴⁹
  * `rohitjila/TCS-CODEVITA-QUESTIONS-AND-SOLUTIONS` and `KAgarwalCodeBase/TCS-Codevita` (historical questions and solutions like *Prime Fibonacci* and *Collision Course*)²³

## Top 5 Tips
1. **Uncompromising Mastery of Dynamic Programming and Graph Algorithms:** These are the primary gatekeepers of the high-ranking cutoffs and the Prime/Digital profiles. Instinctively build memoization tables and master shortest-path/cycle-detection algorithms.¹⁸
2. **Aggressive Simulation of the Tag Test Environment:** Daily practice should be conducted on basic text editors without syntax autocomplete, AI tools, or documentation. If you cannot code standard templates (like binary search or DFS) on a blank screen in 5 minutes, you will struggle in the offline test.⁵
3. **Preemptive Complexity Analysis:** Always calculate Big-O constraints based on maximum input size before writing code. If maximum input ![][image5] is ![][image2], immediately rule out ![][image1] brute-force solutions.²⁴
4. **Exploitation of Language-Specific Standard Libraries:** Rely on the C++ Standard Template Library (STL) or Java Collections Framework. Writing custom sorts or hash maps from scratch wastes time and introduces bugs.⁵
5. **Strategic Acceptance of Presentation Errors (PE):** Since the evaluation engine treats PE as functionally accepted, do not waste critical time formatting whitespace or newlines. Pivot immediately to the next question.³³

## Common Mistakes to Avoid
* **Plagiarism and AI Laundering:** Relying on LLMs (ChatGPT, Claude, Gemini) or copying code during Round 1. The grader analyzes Abstract Syntax Trees (ASTs) for structural similarity; simple renaming or loop-swapping will be flagged as plagiarism and lead to disqualification.²⁸,⁴²
* **Attribution Manipulation:** Uploading solutions to a personal GitHub repo mid-exam to bypass checks by linking it as attribution. Suspiciously timed commits violate the honor code.⁴¹
* **Failing to Account for Parameter Extremities:** Testing only on small public samples and failing to handle 64-bit integers (e.g., using `long long` in C++) or large array sizes, leading to integer overflows or out-of-bounds crashes on hidden test cases.²⁴
* **Cognitive Fixation:** Spending hours debugging one hard problem while ignoring simpler, high-yield questions later in the contest sequence.³⁰
* **Whitespace Obsession:** Wasting valuable minutes trying to resolve formatting differences for a Presentation Error (PE), unaware that the solution is already accepted.³³

## Career Outcome
Performance in CodeVita and the Tag Test routes candidates into three primary corporate profiles:
1. **Ninja Profile (UG: ~3.36 LPA, PG: ~3.53 LPA):** Focuses on application development, maintenance, and support. Requires partial/full execution of 1 standard problem in the Tag Test.⁷,¹⁵,³⁷
2. **Digital Tier (UG: ~7.09 – 7.30 LPA, PG: ~7.60 LPA):** Focuses on system integration, solution architecture, and modern tech. Requires full execution of 1 complex problem in the Tag Test and solid interview performance.⁷,¹⁵,³⁷
3. **Prime Tier (UG: ~9.09 – 9.30 LPA / ~₹74,343 gross monthly):** Focuses on elite architecture, pioneering R&D, and complex algorithm design. Requires flawless, highly optimized execution of both algorithmic problems in the Tag Test.⁴,⁷,³⁷,³⁸

---

#### **Works cited**

1. TCS CodeVita: Your Ultimate Guide - CodeQuotient, accessed on June 5, 2026, [https://codequotient.com/blog/tcs-codevita-everything-you-need-to-know/](https://codequotient.com/blog/tcs-codevita-everything-you-need-to-know/)  
2. TCS CodeVita | Home, accessed on June 5, 2026, [https://codevita.tcsapps.com/](https://codevita.tcsapps.com/)  
3. Tata Consultancy Interview: Complete Guide (2026), accessed on June 5, 2026, [https://www.hackingthecaseinterview.com/pages/tata-consultancy-interview](https://www.hackingthecaseinterview.com/pages/tata-consultancy-interview)  
4. TCS CodeVita: Mass Hiring Overview | PDF | Computer Programming - Scribd, accessed on June 5, 2026, [https://www.scribd.com/document/923602105/TCS-Hiring-for-Freshers](https://www.scribd.com/document/923602105/TCS-Hiring-for-Freshers)  
5. TCS CodeVita Tag Test Guide 2026 | 4-Week Roadmap, Verification Round & Interview Strategy - YouTube, accessed on June 5, 2026, [https://www.youtube.com/watch?v=nXQCSNwxwX0](https://www.youtube.com/watch?v=nXQCSNwxwX0)  
6. TCS CodeVita Season 13 Complete Process: Round 1, Tag Test & Interview Roadmap - YouTube, accessed on June 5, 2026, [https://www.youtube.com/watch?v=G7zMuRnKbL8](https://www.youtube.com/watch?v=G7zMuRnKbL8)  
7. Tcs codevita interview experience(digital) noida campus : r/developersIndia - Reddit, accessed on June 5, 2026, [https://www.reddit.com/r/developersIndia/comments/1r2q76z/tcs\_codevita\_interview\_experiencedigital\_noida/](https://www.reddit.com/r/developersIndia/comments/1r2q76z/tcs_codevita_interview_experiencedigital_noida/)  
8. What are my chances of getting an interview call from TCS CodeVita? - Reddit, accessed on June 5, 2026, [https://www.reddit.com/r/developersIndia/comments/1p3rw63/what\_are\_my\_chances\_of\_getting\_an\_interview\_call/](https://www.reddit.com/r/developersIndia/comments/1p3rw63/what_are_my_chances_of_getting_an_interview_call/)  
9. TCS CodeVita Syllabus for Season 12: Latest Pattern & Tips - Unstop, accessed on June 5, 2026, [https://unstop.com/blog/tcs-codevita-syllabus](https://unstop.com/blog/tcs-codevita-syllabus)  
10. TCS CodeVita Eligibility Criteria Season 13 - PrepInsta, accessed on June 5, 2026, [https://prepinsta.com/tcs-codevita/eligibility-criteria/](https://prepinsta.com/tcs-codevita/eligibility-criteria/)  
11. TCS CodeVita Eligibility and Process Guide | PDF | Software Engineering | Computing - Scribd, accessed on June 5, 2026, [https://www.scribd.com/presentation/422635006/Career-Awarness-pptx](https://www.scribd.com/presentation/422635006/Career-Awarness-pptx)  
12. (New) TCS Eligibility Criteria 2020 | On Campus | Off Campus for Freshers - PrepInsta, accessed on June 5, 2026, [https://prepinsta.com/tcs-eligibility-criteria/comment-page-3/](https://prepinsta.com/tcs-eligibility-criteria/comment-page-3/)  
13. Ultimate TCS Hiring Guide - All Paths - Insight Crunch, accessed on June 5, 2026, [https://insightcrunch.com/2022/08/08/tcs-hiring-guide/](https://insightcrunch.com/2022/08/08/tcs-hiring-guide/)  
14. TCS CodeVita Interview Experience For Digital Systems Engineer 2024 - GeeksforGeeks, accessed on June 5, 2026, [https://www.geeksforgeeks.org/interview-experiences/tcs-codevita-interview-experience-for-digital-systems-engineer-2024/](https://www.geeksforgeeks.org/interview-experiences/tcs-codevita-interview-experience-for-digital-systems-engineer-2024/)  
15. Benefits – Eligibility – To register & to get more details please click on the link mentioned below, accessed on June 5, 2026, [https://amity.edu/placement/pdf/4540\_1.pdf](https://amity.edu/placement/pdf/4540_1.pdf)  
16. TCS CodeVita: A Complete Guide to the World's Largest Programming Contest\!, accessed on June 5, 2026, [https://dev.to/avinash201199/tcs-codevita-a-complete-guide-to-the-worlds-largest-programming-contest-3io4](https://dev.to/avinash201199/tcs-codevita-a-complete-guide-to-the-worlds-largest-programming-contest-3io4)  
17. TCS CodeVita Season 13 Complete Guide: - Placement Lelo, accessed on June 5, 2026, [https://www.placementlelo.in/wp-content/uploads/2025/08/TCS-CodeVita-Season-13-Complete-Guide.pdf](https://www.placementlelo.in/wp-content/uploads/2025/08/TCS-CodeVita-Season-13-Complete-Guide.pdf)  
18. TCS Codevita 2025 Exam Syllabus Overview | PDF - Scribd, accessed on June 5, 2026, [https://www.scribd.com/document/817422698/TCS-Codevita-Syllabus](https://www.scribd.com/document/817422698/TCS-Codevita-Syllabus)  
19. TCS Syllabus 2026 (Updated Details) - PrepInsta, accessed on June 5, 2026, [https://prepinsta.com/tcs-syllabus/](https://prepinsta.com/tcs-syllabus/)  
20. TCS CodeVita Season 13 Complete Preparation Material - Placement Lelo, accessed on June 5, 2026, [https://www.placementlelo.in/resources/tcs-codevita-season-13-complete-preparation-material/](https://www.placementlelo.in/resources/tcs-codevita-season-13-complete-preparation-material/)  
21. TCS CodeVita Preparation Guide | PDF | Algorithms | Computing - Scribd, accessed on June 5, 2026, [https://www.scribd.com/document/895449190/TCS-Codevita-Sheet](https://www.scribd.com/document/895449190/TCS-Codevita-Sheet)  
22. 30-Day TCS CodeVita Prep Guide | PDF | Function (Mathematics), accessed on June 5, 2026, [https://www.scribd.com/document/812834264/TCS-CodeVita](https://www.scribd.com/document/812834264/TCS-CodeVita)  
23. rohitjila/TCS-CODEVITA-QUESTIONS-AND-SOLUTIONS - GitHub, accessed on June 5, 2026, [https://github.com/rohitjila/TCS-CODEVITA-QUESTIONS-AND-SOLUTIONS](https://github.com/rohitjila/TCS-CODEVITA-QUESTIONS-AND-SOLUTIONS)  
24. TCS CodeVita 2023: Complete Guide | PDF | Dynamic Programming | Compiler - Scribd, accessed on June 5, 2026, [https://www.scribd.com/document/884934746/TCS-CodeVita-Complete-Guide](https://www.scribd.com/document/884934746/TCS-CodeVita-Complete-Guide)  
25. Selection Process After TCS CodeVita - Naukri Code 360, accessed on June 5, 2026, [https://www.naukri.com/code360/library/selection-process-after-tcs-codevita](https://www.naukri.com/code360/library/selection-process-after-tcs-codevita)  
26. Tcs Codevita Result Season 12 - Download & Easy Access Steps - Apps on Google Play, accessed on June 5, 2026, [https://rajfed.rajasthan.gov.in/aviator-tcs-codevita-result-season-12-vs-season-11-cutoff-and-tie-break-differences](https://rajfed.rajasthan.gov.in/aviator-tcs-codevita-result-season-12-vs-season-11-cutoff-and-tie-break-differences)  
27. What is the ranking and score criteria used for TCS Codevita Season V?, accessed on June 5, 2026, [https://allabouttcs.quora.com/What-is-the-ranking-and-score-criteria-used-for-TCS-Codevita-Season-V](https://allabouttcs.quora.com/What-is-the-ranking-and-score-criteria-used-for-TCS-Codevita-Season-V)  
28. TCS CodeVita Interview Experience 2020 (2017-2021 Batch) - GeeksforGeeks, accessed on June 5, 2026, [https://www.geeksforgeeks.org/interview-experiences/tcs-codevita-interview-experience-2020-2017-2021-batch/](https://www.geeksforgeeks.org/interview-experiences/tcs-codevita-interview-experience-2020-2017-2021-batch/)  
29. What is TCS CodeVita 2025 Season 13 - PrepInsta, accessed on June 5, 2026, [https://prepinsta.com/tcs-codevita/](https://prepinsta.com/tcs-codevita/)  
30. TCS Codevita TAG exam 2025 - Discuss - LeetCode, accessed on June 5, 2026, [https://leetcode.com/discuss/post/6352669/TCS-Codevita-TAG-exam-2025/](https://leetcode.com/discuss/post/6352669/TCS-Codevita-TAG-exam-2025/)  
31. TCS Global Coding Contest CodeVita FAQs, General Instructions and Best Practices - rgukt-hub, accessed on June 5, 2026, [https://hub.rgukt.ac.in/hub/default/download/notice.upload\_attach.886d38e77b808e4d.54435320436f64655669746120464151732c20496e737472756374696f6e7320616e642042657374205072616374696365732e706466.pdf](https://hub.rgukt.ac.in/hub/default/download/notice.upload_attach.886d38e77b808e4d.54435320436f64655669746120464151732c20496e737472756374696f6e7320616e642042657374205072616374696365732e706466.pdf)  
32. Tips on handling various status messages found in CodeVita, accessed on June 5, 2026, [https://codevita.tcsapps.com/Status%20Messages.pdf](https://codevita.tcsapps.com/Status%20Messages.pdf)  
33. CodeVita Submission FAQs and Errors | PDF | Program Optimization | Compiler - Scribd, accessed on June 5, 2026, [https://www.scribd.com/document/190133477/CodeVita-FAQs](https://www.scribd.com/document/190133477/CodeVita-FAQs)  
34. Solving Presentation Errors in CodeVita | PDF | Compiler | Queue (Abstract Data Type), accessed on June 5, 2026, [https://www.scribd.com/document/384743622/FAQs-2018](https://www.scribd.com/document/384743622/FAQs-2018)  
35. Anyone Experienced TCS CodeVita Tag Test before? Need help : r/developersIndia - Reddit, accessed on June 5, 2026, [https://www.reddit.com/r/developersIndia/comments/1i6cdmt/anyone\_experienced\_tcs\_codevita\_tag\_test\_before/](https://www.reddit.com/r/developersIndia/comments/1i6cdmt/anyone_experienced_tcs_codevita_tag_test_before/)  
36. Codevita Box Ranking and Value Calculation | PDF | String (Computer Science) - Scribd, accessed on June 5, 2026, [https://www.scribd.com/document/932358132/TCS-Codevita-2025-Questions](https://www.scribd.com/document/932358132/TCS-Codevita-2025-Questions)  
37. TCS NQT Salary For 2026 Freshers batch - PrepInsta, accessed on June 5, 2026, [https://prepinsta.com/tcs-nqt/placement-papers/salary/](https://prepinsta.com/tcs-nqt/placement-papers/salary/)  
38. TCS Prime Package and Salary Breakdown - PrepInsta, accessed on June 5, 2026, [https://prepinsta.com/tcs-prime/package-and-salary-breakdown/](https://prepinsta.com/tcs-prime/package-and-salary-breakdown/)  
39. Placed \!\! : r/PlacementsPrep - Reddit, accessed on June 5, 2026, [https://www.reddit.com/r/PlacementsPrep/comments/1r1szmj/placed/](https://www.reddit.com/r/PlacementsPrep/comments/1r1szmj/placed/)  
40. TCS Salary Explained | Ninja, Digital & Prime In-Hand Salary (Real Numbers) - YouTube, accessed on June 5, 2026, [https://www.youtube.com/watch?v=IIXEtV1Gg54](https://www.youtube.com/watch?v=IIXEtV1Gg54)  
41. Note on Plagiarism Detection - TCS CodeVita, accessed on June 5, 2026, [https://codevita.tcsapps.com/blogs/PlagiarismDetection.jsp](https://codevita.tcsapps.com/blogs/PlagiarismDetection.jsp)  
42. TCS Global Coding Contest: - CodeVita FAQs, General Instructions and Best Practices - rgukt-hub, accessed on June 5, 2026, [https://hub.rgukt.ac.in/hub/tnp/download/notice.upload\_attach.90f1aaf8f4a59379.436f64655669746120464151732c20496e737472756374696f6e73202620426573742050726163746963657320526f756e6420312e706466.pdf](https://hub.rgukt.ac.in/hub/tnp/download/notice.upload_attach.90f1aaf8f4a59379.436f64655669746120464151732c20496e737472756374696f6e73202620426573742050726163746963657320526f756e6420312e706466.pdf)  
43. Moss - Plagiarism Detection - Stanford CS Theory, accessed on June 5, 2026, [https://theory.stanford.edu/\~aiken/moss/](https://theory.stanford.edu/~aiken/moss/)  
44. The Failure of Plagiarism Detection in Competitive Programming - arXiv, accessed on June 5, 2026, [https://arxiv.org/html/2505.08244v1](https://arxiv.org/html/2505.08244v1)  
45. (Latest) TCS CodeVita Interview Experience - PrepInsta, accessed on June 5, 2026, [https://prepinsta.com/tcs-codevita/interview-experience/](https://prepinsta.com/tcs-codevita/interview-experience/)  
46. TCS CodeVita Season 13 Study Planner | PDF | Discrete Mathematics - Scribd, accessed on June 5, 2026, [https://www.scribd.com/document/915609657/iamneo-TCS-CodeVita-Season-13-Study-Planner](https://www.scribd.com/document/915609657/iamneo-TCS-CodeVita-Season-13-Study-Planner)  
47. j33l/TCS-CodeVita-practice-problems: TCS CodeVita 2020 solutions, https://practice.tcscodevita.com/IIT/index.jsp · GitHub - GitHub, accessed on June 5, 2026, [https://github.com/j33l/TCS-CodeVita-practice-problems](https://github.com/j33l/TCS-CodeVita-practice-problems)  
48. It contains TCS Codevita questions and solutions - GitHub, accessed on June 5, 2026, [https://github.com/KAgarwalCodeBase/TCS-Codevita](https://github.com/KAgarwalCodeBase/TCS-Codevita)  
49. tcs-codevita · GitHub Topics, accessed on June 5, 2026, [https://github.com/topics/tcs-codevita?o=desc\&s=updated](https://github.com/topics/tcs-codevita?o=desc&s=updated)  
50. TCS BIGGEST BUMPER HIRING FOR FRESHERS | TCS CODEVITA 2025 SYLLABUS AND TOPICS WISE PDF SHARED - YouTube, accessed on June 5, 2026, [https://www.youtube.com/watch?v=DIEKsXG9kxo](https://www.youtube.com/watch?v=DIEKsXG9kxo)  
51. SamerBenMim/Competitive-Programming: Problems I solved training for TCPC && Winter Cup :), principally LEETCODE & CODEFORCES solutions. - GitHub, accessed on June 5, 2026, [https://github.com/SamerBenMim/Competitive-Programming](https://github.com/SamerBenMim/Competitive-Programming)

[image1]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADsAAAAaCAYAAAAJ1SQgAAADNklEQVR4Xu2YaahNURTHl3keCpmSuUSS+RuPkGT6RHkyFyFkHj5QIimUIZKUzJEpkSES+YIoUUTPF0O+iEKU+P/v2sfZd71zz+W8e+6j7q/+vXv/a+979t5n7bXPeSIl/imaQwegu9BFqHt2uPqoA52GOthAFdgLDXefV0LPoLphOONN9b4XjT3QRGtWkUvQVve5E/QTGvo7KlITugkN87zUmQKdsWaBKROdbGfjd4XeQE2M/0c0hdZCx6Dz0A3oDrQKquW1C+DqvoZG24CjMXQVeig62C9Qq6wWIhuhj6LxT6L703ICOmRNxwVouTXzwfx/Di0TnURAS+gBdB2q5/lkPPQCqmF8yzroleiEogY2QHRBou7QNNGJ1rcBxyzRBff3cyzcG2+hHjbgYKHgQNcb/zC0y3hRcG8NgX6Ipp1dtMnQBuORvtA20cXsAnXMDmfoJjq2oJjFMlu08Sgb8ODgONB7xmeFXGg8SyPRzCBHRa81Jwxn2C26GD4tRBeTBagM2iSV92xAhWhGxsI7+Vn0LIuDA+Yg33teM+dN8LwoxkHb3ed+on0eheEMj6HaxmPNYNtAXyW6bpArogsWC1OQPzTXBgxcdba77Xl9nGfviIUTHeN958DYb4T7zgU/G4YTcRI6bk0frtI70QvnSo+ALaLt/P050Hm9PS8KFh5W5QBWbvY7575zGywKw4nYD12zpk9DCVPEppBPG9FU/y7ZEwvuLP/mor1ED+K+aN/+omd0r+zwX7NP9JiMhXuFF21gAx7cC2yz2vh8NMyXxtOlcj9SLtqXE31qYklgCufdCqxwvKi/p3zmi8a5cpagaI21AQ9W00HWFM0kns/sf9DEknAZ2mlNC1P5JfRENF0DeEBvhr5BSyX3Q0MFtNiaDt55Vm/7xBTAfcrJFuJhng9D86wZRWtoB3RLtNzzbrC6rYDaeu2i4F05Yjw+BfG3eFRwMh8kekGYGVwMf5GTwP68zmAbKDQzRQfMV7zqguc8MzN1+OLA42uSDRQRZtYSa6bFAol+UykG/O8FT5RcLwkFh29IPEJG2kDK8Lqswj1tIG14Tp+C2tlAiqyBZlizRIkS/z+/APhLoB+HCTASAAAAAElFTkSuQmCC>
[image2]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAB0AAAAZCAYAAADNAiUZAAABlElEQVR4Xu2UyysGYRTGDwrJBuWaJFnYSHYsLCysbWSFhaQsSLGw8Q8oSf4Cl0hyv+WyQ6xIVsrKxsKKpGx4TudMvXOaeb8mvo3mqV/Nec587/PNO+8cor9XH2gDubaRTd2Ab2UJFIbb2REHdYAa2/ApB9Rb0xFv3xG4AuugLtymBVN7VQ26wSnYMr1AI+AOlGs9DV6cmrUIJkieeI882zsK7kn+5RdFh1aAT9DjeHxYnsGk442DPL0+BFNOL1YfFB06SHI4mo1/Bo6NF2iW5GkzKi6Ud4FDa42/Cd5JtrEdPIIi7fFvNvTaq7hQ9ji00vhr6jeAFnCgfjF4AL1aexUXekLRoSvqN2k9TPIq+IQPBDdlUlzoPkWHLqvfaPxE4tBta5J8Arx4lfFX1S8zfiLFhc6RLG4HB9/L/q9mLYfuWJPk/fDirca/AJfGSywO3bUmVALeQL/j5YNXMOZ4iVVAMnXOSWawFY9JnrnBxBkCt+QZdT51gmuSQN5C5olkDvP35qoLzJAcrHlQGm6nSpXqP+gHDNFXUcnL4lQ==>
[image3]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAFEAAAAaCAYAAADPELCZAAAESElEQVR4Xu2YeahVVRTGPzNzTEWcMx6p4QCSOKKYYKBEhOk/gmJwVVBxwHlEjSwzCrRBIUJ8gVKJYSaOOI+oOc8jPpBUQgKFApXQ9b119nv7LPe99zxv79qT+4OP985a+5yzzzp7r7XOBQoUeBGpIfpF9Lp1VCFmioZbYz5ZLhoU/V8kmi9aLPq0bMT/n5dEu0X9rCMfDBOt845bi1aIHou2e/aqQBvRLdGr1lER6ovmin4U/SbaJTogmiWq7o1z8O39IXrXOoQjyH8Qe0PveQP6Eg/H3aVsFT2C+hmwj+NubBBNN7bEMB9cEU2DBsfRWHRctENU07OTgaJromrGTg4i/0F0bBOVQAPVI+4qZaqo2BojRkIXxivWkY0vRLdF7a0j4h3ohD4y9lWib43NsQ/PJ4h1RRdFKeicf415lWXQZwrRFnpeOn+QUdCTBliHB1fgv6Lfjf2yaIKxOUJB5Nv9RHQCmsR3irrFRigpaJ7l+T+IJkJf9CVRvbJRYfgc30DvVQJ9tnb+AOEoMq80pgPuyERw5f0tOmQdBr5dTuZPz9Ygsn3g2XxsENkG7YEWHZdf+bbvid6OjsnXonOil6Njrho+1JvQ6zWK7On4EuWdAgPBOTKojiLRJu84BNMB75sIbkXeZIx1GPpCx+33bG9FNvpC2CCOg45v5tnIT9DtxyATBtWv9oOh5/FvEo5BCyThqr0rui9qGNlGQ3NiJtZA55UVroY70Am+YXyWz6Hj/PzXPbJ18mw+Nois8te9Y8cC6HW6RMesmBvL3aWriv73PVs6+IJ4X5/PoOe77ckAdS53B/keT6eiIHWgF6fc1gnRHLrlHyIeMLcS+TeEDSJf2FXv2MH2iddhv0nYqHP1tILOqxiabjLN0cFrzDM2zv8faMVl/8e8mo3voO1dIs5CH6C2dXgwN3DMbGPnJ15FtjO3GTsAy0LodfpHx1MiGwN3Q7QE2YuJg/mWvaKFQeE92E1Q2eBWDlX1IIugF3/POiJcHuMkLK7YpNtmtk+cAx3fxLOR1aK/UF4t+Q1uq2lSLiC8YllA3a4bYXwhtiBejDLCLc08dR667B18IOaSB9AkHGqmCVfKJGuEjj+FeNVn0PeKVno2tjdMFSnPxsmvh25r/igwFMmCyoVwEunnuhYaxNesIwA/OsZaYyaYjJdCH5CfelzuTL4zRC28cSEYEK4kn67QFeHePFNGx8jHnPSV6Ca0V2RVtlWXPwC4c31tFjX1xjn6QFOFG1eCcIrpJTpjjQG4mHidntZRWXBrsHd07UmudIAWMF7XXzEsXnwxSfJZrrDv5c7MG+zHWHWHWMczwq8nrtwQk0WnrbES4M7ivfLKeMT7ulxgFWYQPzR2rg7mqVD+/S/hVxHvX8s6Khv+4sMvDNei5Aq38c/Q/MXqziadWzlJVc0FPgerssvfeYd9JqtfS+uoQrAFS1ljgQIFChRIxhMNpe5mc85Q7wAAAABJRU5ErkJggg==>
[image4]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAGcAAAAaCAYAAACq/ULmAAAFIElEQVR4Xu2Zd6gkRRCHf+acc1ZQVMwZQcScMCIGTvGZcw6YMGPAP1TUEwPIM4KYxYCeWVExoJhQUU8EI6KoqKiI1veq521P7czu3Hm7b8X94Me9qeqe7elQXd0nDRkyZOKZzXSPabno+B+zkOkB0/zR0W8mm3aPxhnIAaZzTDeb1g2+QWZr0+OmWaKjX0wy3ReNM5jDTO+a/jZtUXYNPEyoM6JxemAJnmW60/Sg6WnTi6bTVT36M5u+MO0QHYl5TU+Y3pR37K+mxUolpItMP8r9P5keLrvH2VUTMzjXmZ6R/zbapezWnvI+wPen6WXTypl/E9M3prky2zSzv+kj0ynyTi9Y1PGS6UnTHJkd6LCPTTMFe+Rs02fyDzi17BpjQ/kAzhcdGTtpYgYHNler/UzaCHsuA7RadCSmmo6NxqZcbvpK9S/fSt6w84L9NtM1wVYFM48P/Mv0pdoHeR/T+cEW2V4TNzgXmEbkk5c2rF92a0l5lKlj1PRUNDbhEPkPbhcdGXQmHftasH+o7jNiHvnKgzvkv3Voyz3GtfLB60Td4GxmekQeTl4xXWqatVRCWtp0g+kx06Py6HCx6XnTcVm5Oii3hOlIeRtuLbvHJhfRoQ76mNA9TbBSfjG9FB0BOphGfZvZFki23TJbFcToK9LfzDjqvNVyj/GO2js0UjU4hFVWfDGTmUTsWQ+Nl/D4/508bMPypt/kg3Km6aRkr2NBtSYl+wa/94d8wAtuMm2aPUeYeLSdFdYYQhKVjoiOQPHyFzLbOsnWbcYzMOwXBaSW1NsmPTNB7m+5a4mDM6fpc9NVRYHEmvJyI+n55PS8wXgJ6fWkJuxhuix7ZoXwvgsz2weqTpgK1pbXoW2N4GVfyyutFHwRGke5fH/ZKNnWymxVsNGTtRWQ2VGPAxoQFo9vuWuJg7Njej64KJAgmcF+b3o+PD3nM5uVQBhsAt+ch/xFTD/LVxAriY6/O/NXwWrN296VueUVUKeQwlIk9LGU84EoVg7/1rGMaUo0ymdtMZs5I61RdlcSB+eY9Hxges4hZX8v/U22SUeS9ACdiZ8V0QQmF+Eyh2jAb58oD4tHld1tLCsvz6G0McR6KnXKwdmsKRMPUlzVYO8U1kbUXg/2k9dlYN4Pvjri4NC5PB9dFEjMnuzPpme+jVXEeYXzBmGVdzVhRXkCEVlBniCRPuNftexuowi1HBkaQ8ZCpXxPyOHD8V8fHWolCTtHRwap9sbRKF+pnI+ozwm6CfGcQ0JCWL66KJBYXV6OzR7Wk7dyeuBmoupcBmRs/M6n0VEBGSVlF4+OThDaPpGHgDyTYPZdYvpdvqHWHTKnmk6IxgQri+wu3ggUsM/Q4CKL6sZeap9InM6/Vyss0u5bTG/Lvw34LtLYc+X3c6TD26o9VEVIODi78BtVcMdHe0jRuzGicqbbGPL3K03PyU+/zLK7TKeZlsrKVcGsvz3YOOXzLtJVGv+DqgeQlUeDm6SXrI7ifewXefZE1kd45ozDSiKt5UY4h9sN6uaibEwmCm6UDzrlmKB1K4+0nTNON9ga8vS+Lxwk72CuLwaVUfnpnPBWrBb+5dTPXVjj9PZf8Kpp32jsNVyUMgP3jo4BgtBb1zGs6l63fRow5dWsIaOySeDaPvGGQ0tbdJAsChC5u1kmpQsI5fwfFAOXn8F6wahaB+K+w6GPlJhNdlDhbotTPHsP5y4yrFGVr2B6wZaq36/6BmcJTsm9/tj/EgvLJ0ORNQ4ZMmTIkCEDxz/dXB/xTjobRAAAAABJRU5ErkJggg==>
[image5]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABMAAAAaCAYAAABVX2cEAAABBklEQVR4XmNgGAWDClgB8W4gvg/E/4H4BKo0GOwA4t8MEPlnQNyIKo0JdgLxAwaIBjNUKTAoAuL56ILYADcQXwfiBAaIYetRZCFgChA7oQtiA25APAmI2RgQrlNHVgAEpxgg8gRBNxAHQNnFDBDDQIbDgDwQb0Xi4wVngJgPyuYB4jdA/AmIBaBiaQyQMCMIxIH4EJpYGwPEdSBXgsBKIDZASOMGUUBcgyYmAcTfgPgpEPMC8Q1UadxgDgMkraGDGQwQ1y2GYqLANSBmQRcEAg0GiGEgnIgmhxV4AfF5IGZEl4CC1QwQw6TRJZCBDQMkBmE2PwBiO2QFUGAJxJfQBUfBKBjSAAAANDDneVsDZAAAAABJRU5ErkJggg==>