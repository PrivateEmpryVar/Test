{
  "branches": {
    "main": {
      "remoteTrackingBranchID": null,
      "remote": false,
      "target": "C4",
      "id": "main",
      "type": "branch"
    },
    "bugFix": {
      "remoteTrackingBranchID": null,
      "remote": false,
      "target": "C2",
      "id": "bugFix",
      "type": "branch"
    }
  },
  "commits": {
    "C0": {
      "type": "commit",
      "parents": [],
      "author": "Peter Cottle",
      "createTime": "Mon Nov 05 2012 00:56:47 GMT-0800 (PST)",
      "commitMessage": "Quick Commit. Go Bears!",
      "id": "C0",
      "rootCommit": true
    },
    "C1": {
      "type": "commit",
      "parents": [
        "C0"
      ],
      "author": "Peter Cottle",
      "createTime": "Mon Nov 05 2012 00:56:47 GMT-0800 (PST)",
      "commitMessage": "Quick Commit. Go Bears!",
      "id": "C1"
    },
    "C2": {
      "type": "commit",
      "parents": [
        "C1"
      ],
      "author": "Peter Cottle",
      "createTime": "Sat Dec 04 2021 09:03:36 GMT+0200 (Восточная Европа, стандартное время)",
      "commitMessage": "Быстрый коммит. А надо!",
      "id": "C2"
    },
    "C3": {
      "type": "commit",
      "parents": [
        "C1"
      ],
      "author": "Peter Cottle",
      "createTime": "Sat Dec 04 2021 09:03:56 GMT+0200 (Восточная Европа, стандартное время)",
      "commitMessage": "Быстрый коммит. А надо!",
      "id": "C3"
    },
    "C4": {
      "type": "commit",
      "parents": [
        "C3",
        "C2"
      ],
      "author": "Peter Cottle",
      "createTime": "Sat Dec 04 2021 09:04:12 GMT+0200 (Восточная Европа, стандартное время)",
      "commitMessage": "Слияние branch \"bugFix\" в branch \"main\"",
      "id": "C4"
    }
  },
  "tags": {},
  "HEAD": {
    "id": "HEAD",
    "target": "main",
    "type": "general ref"
  }
}
