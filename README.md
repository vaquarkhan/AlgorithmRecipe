### Package structure

```
.
└── com
    └── omtlab
        └── algorithmrecipe
            ├── App.java
            ├── array
            │   ├── binarysearch
            │   │   └── rotated
            │   │       ├── LC153.java
            │   │       ├── LC154.java
            │   │       ├── LC33.java
            │   │       └── LC81.java
            │   ├── continuous
            │   │   └── LC560.java
            │   ├── GFGFindFirstDuplicate.java
            │   ├── LC13.java
            │   ├── LC238.java
            │   ├── LC280.java
            │   ├── LC299.java
            │   ├── LC324.java
            │   ├── LC334.java
            │   ├── LC670.java
            │   ├── LC674.java
            │   ├── LC75.java
            │   ├── LC88.java
            │   ├── LC953.java
            │   ├── LC977.java
            │   ├── map
            │   │   ├── LC398.java
            │   │   └── LC554.java
            │   └── sumarray
            │       ├── GFGFindPairForSum.java
            │       ├── LC121.java
            │       ├── LC325.java
            │       ├── LC523.java
            │       └── LC636.java
            ├── backtracking
            │   ├── LC17.java
            │   ├── LC200Copy.java
            │   ├── LC282.java
            │   ├── LC39Copy.java
            │   ├── LC51.java
            │   ├── LC78.java
            │   ├── LC79.java
            │   └── LC90.java
            ├── binarysearch
            │   ├── LC15.java
            │   ├── LC410.java
            │   ├── LC50.java
            │   ├── LC69.java
            │   └── LC875.java
            ├── bit
            │   ├── GetBitAtPosition.java
            │   ├── LC191.java
            │   ├── LC461.java
            │   ├── LC477.java
            │   ├── MoveBitLeft.java
            │   ├── MoveBitRight.java
            │   └── XOR.java
            ├── common
            │   ├── graph
            │   │   ├── Edge.java
            │   │   ├── Graph.java
            │   │   ├── Node.java
            │   │   └── State.java
            │   ├── node
            │   │   ├── LinkNode.java
            │   │   ├── TreeNode.java
            │   │   └── TrieNode.java
            │   └── util
            │       ├── MatrixUtil.java
            │       ├── NodeUtil.java
            │       ├── Pair.java
            │       └── TreeUtil.java
            ├── design
            │   └── using
            │       ├── list
            │       │   └── LC380.java
            │       └── map
            │           ├── LC380.java
            │           └── LC588.java
            ├── divideandconquer
            │   └── LC23.java
            ├── dp
            │   ├── matrix
            │   │   ├── GFGLargestAreaHistogram.java
            │   │   ├── GFGWordWrapProblem.java
            │   │   ├── LC221.java
            │   │   ├── LC68.java
            │   │   ├── LC84.java
            │   │   ├── LC85.java
            │   │   └── startwithzero
            │   │       ├── GFGEditDistance.java
            │   │       ├── LC10.java
            │   │       ├── LC188.java
            │   │       ├── LC322.java
            │   │       ├── LC377.java
            │   │       └── LC647.java
            │   └── singlearray
            │       ├── hardtounderstand
            │       │   └── LC714.java
            │       ├── LC43.java
            │       ├── LC689.java
            │       ├── LC91.java
            │       └── startwithzero
            │           ├── LC139.java
            │           ├── LC494.java
            │           ├── LC639.java
            │           └── LC91Copy.java
            ├── finduniondisjoinset
            │   ├── GFGFindCycleInGraphUnionFindPathComp.java
            │   ├── LC721.java
            │   └── LC785.java
            ├── greedy
            │   ├── LC218.java
            │   ├── LC56.java
            │   ├── LC57.java
            │   └── LC759.java
            ├── iterator
            │   ├── list
            │   │   ├── LC251.java
            │   │   └── LC341.java
            │   └── tree
            │       └── LC173_Copy.java
            ├── linkedlist
            │   ├── LC146.java
            │   ├── LC206.java
            │   └── LC430.java
            ├── math
            │   ├── LC166.java
            │   └── LC273.java
            ├── matrix
            │   └── bfs
            │       ├── GFGShortDistMrx.java
            │       ├── LC200.java
            │       └── LC286.java
            ├── priorityqueue
            │   └── LC621.java
            ├── quicksort
            │   ├── KthSmalletsElement.java
            │   ├── LC215.java
            │   └── LC973.java
            ├── recursion
            │   ├── LC301.java
            │   ├── LC39.java
            │   ├── LC494.java
            │   └── map
            │       └── LC377.java
            ├── set
            │   └── LC128.java
            ├── sortingalgorithms
            │   └── Quicksort.java
            ├── stack
            │   ├── LC20.java
            │   ├── LC277.java
            │   ├── LC71.java
            │   └── LC98.java
            ├── string
            │   ├── LC28.java
            │   ├── LC387.java
            │   ├── LC38.java
            │   ├── LC647.java
            │   └── map
            │       ├── GFGAnagramSubstringSearch.java
            │       ├── LC1166.java
            │       ├── LC336.java
            │       ├── LC49.java
            │       └── LC49Prime.java
            ├── tree
            │   ├── bfs
            │   │   ├── LC101.java
            │   │   ├── LC102.java
            │   │   ├── LC127.java
            │   │   ├── LC133.java
            │   │   ├── LC297.java
            │   │   ├── LC314.java
            │   │   └── LC773.java
            │   ├── dfs
            │   │   └── LC756.java
            │   ├── dijkstra
            │   │   ├── GFGShortestPath.java
            │   │   └── LC787.java
            │   ├── inorder
            │   │   ├── LC102.java
            │   │   ├── LC117.java
            │   │   ├── LC173.java
            │   │   ├── LC235.java
            │   │   ├── LC236.java
            │   │   ├── LC285.java
            │   │   ├── LC426.java
            │   │   └── LC98.java
            │   ├── preorder
            │   │   ├── LC124.java
            │   │   ├── LC404.java
            │   │   └── LC572.java
            │   └── topological
            │       ├── LC269.java
            │       └── LC953.java
            ├── trie
            │   ├── LC211.java
            │   └── LC642.java
            └── twopointer
                ├── GenerateTree.java
                ├── LC125.java
                ├── LC15.java
                ├── LC161.java
                ├── LC209.java
                ├── LC42.java
                ├── LC5.java
                ├── LC647.java
                ├── LC680.java
                ├── LC755.java
                ├── LC76.java
                └── LC860.java

54 directories, 159 files

```
