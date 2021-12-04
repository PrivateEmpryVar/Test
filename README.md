{
  "branches": {
    "main": {
      "remoteTrackingBranchID": "o/main",
      "remote": false,
      "target": "C4",
      "id": "main",
      "localBranchesThatTrackThis": null,
      "type": "branch"
    },
    "o/main": {
      "remoteTrackingBranchID": null,
      "remote": false,
      "target": "C3",
      "id": "o/main",
      "localBranchesThatTrackThis": [
        "main"
      ],
      "type": "branch"
    }
  },
  "commits": {
    "C0": {
      "type": "commit",
      "parents": [],
      "author": "Peter Cottle",
      "createTime": "Sat Dec 04 2021 11:09:53 GMT+0200 (Восточная Европа, стандартное время)",
      "commitMessage": "Быстрый коммит. А надо!",
      "id": "C0",
      "rootCommit": true
    },
    "C1": {
      "type": "commit",
      "parents": [
        "C0"
      ],
      "author": "Peter Cottle",
      "createTime": "Sat Dec 04 2021 11:09:53 GMT+0200 (Восточная Европа, стандартное время)",
      "commitMessage": "Быстрый коммит. А надо!",
      "id": "C1"
    },
    "C2": {
      "type": "commit",
      "parents": [
        "C1"
      ],
      "author": "Peter Cottle",
      "createTime": "Sat Dec 04 2021 11:09:53 GMT+0200 (Восточная Европа, стандартное время)",
      "commitMessage": "Быстрый коммит. А надо!",
      "id": "C2"
    },
    "C3": {
      "type": "commit",
      "parents": [
        "C1"
      ],
      "author": "Peter Cottle",
      "createTime": "Sat Dec 04 2021 11:10:54 GMT+0200 (Восточная Европа, стандартное время)",
      "commitMessage": "Быстрый коммит. А надо!",
      "id": "C3"
    },
    "C4": {
      "type": "commit",
      "parents": [
        "C2",
        "C3"
      ],
      "author": "Peter Cottle",
      "createTime": "Sat Dec 04 2021 11:10:58 GMT+0200 (Восточная Европа, стандартное время)",
      "commitMessage": "Слияние branch \"o/main\" в branch \"main\"",
      "id": "C4"
    }
  },
  "tags": {},
  "HEAD": {
    "target": "C2",
    "id": "HEAD",
    "type": "general ref"
  },
  "originTree": {
    "branches": {
      "main": {
        "remoteTrackingBranchID": null,
        "remote": false,
        "target": "C3",
        "id": "main",
        "localBranchesThatTrackThis": null,
        "type": "branch"
      }
    },
    "commits": {
      "C0": {
        "type": "commit",
        "parents": [],
        "author": "Peter Cottle",
        "createTime": "Sat Dec 04 2021 11:09:53 GMT+0200 (Восточная Европа, стандартное время)",
        "commitMessage": "Быстрый коммит. А надо!",
        "id": "C0",
        "rootCommit": true
      },
      "C1": {
        "type": "commit",
        "parents": [
          "C0"
        ],
        "author": "Peter Cottle",
        "createTime": "Sat Dec 04 2021 11:09:53 GMT+0200 (Восточная Европа, стандартное время)",
        "commitMessage": "Быстрый коммит. А надо!",
        "id": "C1"
      },
      "C3": {
        "type": "commit",
        "parents": [
          "C1"
        ],
        "author": "Peter Cottle",
        "createTime": "Sat Dec 04 2021 11:09:53 GMT+0200 (Восточная Европа, стандартное время)",
        "commitMessage": "Быстрый коммит. А надо!",
        "id": "C3"
      }
    },
    "tags": {},
    "HEAD": {
      "target": "main",
      "id": "HEAD",
      "type": "general ref"
    }
  }
}
