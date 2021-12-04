{
  "branches": {
    "main": {
      "remoteTrackingBranchID": null,
      "remote": false,
      "target": "C1",
      "id": "main",
      "type": "branch"
    },
    "pushed": {
      "remoteTrackingBranchID": null,
      "remote": false,
      "target": "C2'",
      "id": "pushed",
      "type": "branch"
    },
    "local": {
      "remoteTrackingBranchID": null,
      "remote": false,
      "target": "C1",
      "id": "local",
      "type": "branch"
    }
  },
  "commits": {
    "C0": {
      "type": "commit",
      "parents": [],
      "author": "Peter Cottle",
      "createTime": "Sat Dec 04 2021 09:45:38 GMT+0200 (Восточная Европа, стандартное время)",
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
      "createTime": "Sat Dec 04 2021 09:45:38 GMT+0200 (Восточная Европа, стандартное время)",
      "commitMessage": "Быстрый коммит. А надо!",
      "id": "C1"
    },
    "C2": {
      "type": "commit",
      "parents": [
        "C1"
      ],
      "author": "Peter Cottle",
      "createTime": "Sat Dec 04 2021 09:45:38 GMT+0200 (Восточная Европа, стандартное время)",
      "commitMessage": "Быстрый коммит. А надо!",
      "id": "C2"
    },
    "C3": {
      "type": "commit",
      "parents": [
        "C1"
      ],
      "author": "Peter Cottle",
      "createTime": "Sat Dec 04 2021 09:45:38 GMT+0200 (Восточная Европа, стандартное время)",
      "commitMessage": "Быстрый коммит. А надо!",
      "id": "C3"
    },
    "C2'": {
      "type": "commit",
      "parents": [
        "C2"
      ],
      "author": "Peter Cottle",
      "createTime": "Sat Dec 04 2021 09:47:57 GMT+0200 (Восточная Европа, стандартное время)",
      "commitMessage": "Откатываю commit C2: Быстрый коммит. А надо!",
      "id": "C2'"
    }
  },
  "tags": {},
  "HEAD": {
    "target": "pushed",
    "id": "HEAD",
    "type": "general ref"
  }
}
