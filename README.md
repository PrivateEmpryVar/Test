{
  "branches": {
    "main": {
      "remoteTrackingBranchID": null,
      "remote": false,
      "target": "C3",
      "id": "main",
      "type": "branch"
    },
    "bugFix": {
      "remoteTrackingBranchID": null,
      "remote": false,
      "target": "C2'",
      "id": "bugFix",
      "type": "branch"
    }
  },
  "commits": {
    "C0": {
      "type": "commit",
      "parents": [],
      "author": "Peter Cottle",
      "createTime": "Sat Dec 04 2021 09:06:26 GMT+0200 (Восточная Европа, стандартное время)",
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
      "createTime": "Sat Dec 04 2021 09:06:26 GMT+0200 (Восточная Европа, стандартное время)",
      "commitMessage": "Быстрый коммит. А надо!",
      "id": "C1"
    },
    "C2": {
      "type": "commit",
      "parents": [
        "C1"
      ],
      "author": "Peter Cottle",
      "createTime": "Sat Dec 04 2021 09:09:56 GMT+0200 (Восточная Европа, стандартное время)",
      "commitMessage": "Быстрый коммит. А надо!",
      "id": "C2"
    },
    "C3": {
      "type": "commit",
      "parents": [
        "C1"
      ],
      "author": "Peter Cottle",
      "createTime": "Sat Dec 04 2021 09:10:50 GMT+0200 (Восточная Европа, стандартное время)",
      "commitMessage": "Быстрый коммит. А надо!",
      "id": "C3"
    },
    "C2'": {
      "type": "commit",
      "parents": [
        "C3"
      ],
      "author": "Peter Cottle",
      "createTime": "Sat Dec 04 2021 09:11:21 GMT+0200 (Восточная Европа, стандартное время)",
      "commitMessage": "Быстрый коммит. А надо!",
      "id": "C2'"
    }
  },
  "tags": {},
  "HEAD": {
    "id": "HEAD",
    "target": "bugFix",
    "type": "general ref"
  }
}
