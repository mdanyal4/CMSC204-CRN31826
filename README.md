# Java Data Structures and Algorithms — CMSC204

Computer Science II coursework organized into six Java assignments and supporting labs. The repository shows implementations and exercises involving stacks, queues, linked lists, trees, graphs, and testing.

## Assignments

| Project | Main source files |
| --- | --- |
| Password validation | `PasswordCheckerUtility.java` and custom exception classes |
| Expression notation with stacks and queues | `Notation.java`, `MyStack.java`, `MyQueue.java` |
| Doubly linked lists | `BasicDoubleLinkedList.java`, `SortedDoubleLinkedList.java` |
| Course database | `CourseDBStructure.java`, `CourseDBManager.java`, `CourseDBElement.java` |
| Morse code conversion | `MorseCodeTree.java`, `MorseCodeConverter.java`, `TreeNode.java` |
| Town and road graph | `Graph.java`, `Town.java`, `Road.java`, `TownGraphManager.java` |

Each assignment has its own `src/` directory. Supporting labs cover recursion, generics, JUnit, threads, chat clients and servers, and data-structure worksheets.

## Run and test

1. Install a JDK and open an individual assignment in a Java IDE.
2. Set that assignment's `src/` directory as the source root.
3. Add the JUnit dependency required by its test imports.
4. For JavaFX drivers, configure JavaFX separately.
5. Run the selected driver or test class.

The repository is not configured as a single Maven or Gradle application. Build assignments separately to avoid conflicts between repeated class names. Included tests document expected behavior; this README does not claim that every test currently passes.

## Coursework and attribution

This repository preserves coursework, assignment documents, interfaces, GUI scaffolding, and test files. Some materials may be supplied by the course. Preserve file-level attribution and use the work in accordance with academic-integrity requirements.
