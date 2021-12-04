{
  "branches": {
    "main": {
      "remoteTrackingBranchID": null,
      "remote": false,
      "target": "C3",
      "id": "main",
      "type": "branch"
    },
    "o/main": {
      "remoteTrackingBranchID": null,
      "remote": false,
      "target": "C1",
      "id": "o/main",
      "type": "branch"
    }
  },
  "commits": {
    "C0": {
      "type": "commit",
      "parents": [],
      "author": "Peter Cottle",
      "createTime": "Sat Dec 04 2021 11:05:15 GMT+0200 (Восточная Европа, стандартное время)",
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
      "createTime": "Sat Dec 04 2021 11:05:15 GMT+0200 (Восточная Европа, стандартное время)",
      "commitMessage": "Быстрый коммит. А надо!",
      "id": "C1"
    },
    "C3": {
      "type": "commit",
      "parents": [
        "C1"
      ],
      "author": "Peter Cottle",
      "createTime": "Sat Dec 04 2021 11:06:47 GMT+0200 (Восточная Европа, стандартное время)",
      "commitMessage": "Быстрый коммит. А надо!",
      "id": "C3"
    },
    "C4": {
      "type": "commit",
      "parents": [
        "C1"
      ],
      "author": "Peter Cottle",
      "createTime": "Sat Dec 04 2021 11:07:08 GMT+0200 (Восточная Европа, стандартное время)",
      "commitMessage": "Быстрый коммит. А надо!",
      "id": "C4"
    }
  },
  "tags": {},
  "HEAD": {
    "target": "C4",
    "id": "HEAD",
    "type": "general ref"
  },
  "originTree": {
    "branches": {
      "main": {
        "remoteTrackingBranchID": null,
        "remote": false,
        "target": "C2",
        "id": "main",
        "type": "branch"
      }
    },
    "commits": {
      "C0": {
        "type": "commit",
        "parents": [],
        "author": "Peter Cottle",
        "createTime": "Sat Dec 04 2021 11:05:15 GMT+0200 (Восточная Европа, стандартное время)",
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
        "createTime": "Sat Dec 04 2021 11:05:15 GMT+0200 (Восточная Европа, стандартное время)",
        "commitMessage": "Быстрый коммит. А надо!",
        "id": "C1"
      },
      "C2": {
        "type": "commit",
        "parents": [
          "C1"
        ],
        "author": "Peter Cottle",
        "createTime": "Sat Dec 04 2021 11:05:15 GMT+0200 (Восточная Европа, стандартное время)",
        "commitMessage": "Быстрый коммит. А надо!",
        "id": "C2"
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
