{
  "branches": {
    "main": {
      "remoteTrackingBranchID": "o/main",
      "remote": false,
      "target": "C1",
      "id": "main",
      "localBranchesThatTrackThis": null,
      "type": "branch"
    },
    "o/main": {
      "remoteTrackingBranchID": null,
      "remote": false,
      "target": "C1",
      "id": "o/main",
      "localBranchesThatTrackThis": [
        "main"
      ],
      "type": "branch"
    },
    "side1": {
      "remoteTrackingBranchID": null,
      "remote": false,
      "target": "C2",
      "id": "side1",
      "localBranchesThatTrackThis": null,
      "type": "branch"
    },
    "side2": {
      "remoteTrackingBranchID": null,
      "remote": false,
      "target": "C4",
      "id": "side2",
      "localBranchesThatTrackThis": null,
      "type": "branch"
    },
    "side3": {
      "remoteTrackingBranchID": null,
      "remote": false,
      "target": "C7",
      "id": "side3",
      "localBranchesThatTrackThis": null,
      "type": "branch"
    }
  },
  "commits": {
    "C0": {
      "type": "commit",
      "parents": [],
      "author": "Peter Cottle",
      "createTime": "Sat Dec 04 2021 12:09:54 GMT+0300 (Москва, стандартное время)",
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
      "createTime": "Sat Dec 04 2021 12:09:54 GMT+0300 (Москва, стандартное время)",
      "commitMessage": "Быстрый коммит. А надо!",
      "id": "C1"
    },
    "C2": {
      "type": "commit",
      "parents": [
        "C1"
      ],
      "author": "Peter Cottle",
      "createTime": "Sat Dec 04 2021 12:09:54 GMT+0300 (Москва, стандартное время)",
      "commitMessage": "Быстрый коммит. А надо!",
      "id": "C2"
    },
    "C3": {
      "type": "commit",
      "parents": [
        "C1"
      ],
      "author": "Peter Cottle",
      "createTime": "Sat Dec 04 2021 12:09:54 GMT+0300 (Москва, стандартное время)",
      "commitMessage": "Быстрый коммит. А надо!",
      "id": "C3"
    },
    "C4": {
      "type": "commit",
      "parents": [
        "C3"
      ],
      "author": "Peter Cottle",
      "createTime": "Sat Dec 04 2021 12:09:54 GMT+0300 (Москва, стандартное время)",
      "commitMessage": "Быстрый коммит. А надо!",
      "id": "C4"
    },
    "C5": {
      "type": "commit",
      "parents": [
        "C1"
      ],
      "author": "Peter Cottle",
      "createTime": "Sat Dec 04 2021 12:09:54 GMT+0300 (Москва, стандартное время)",
      "commitMessage": "Быстрый коммит. А надо!",
      "id": "C5"
    },
    "C6": {
      "type": "commit",
      "parents": [
        "C5"
      ],
      "author": "Peter Cottle",
      "createTime": "Sat Dec 04 2021 12:09:54 GMT+0300 (Москва, стандартное время)",
      "commitMessage": "Быстрый коммит. А надо!",
      "id": "C6"
    },
    "C7": {
      "type": "commit",
      "parents": [
        "C6"
      ],
      "author": "Peter Cottle",
      "createTime": "Sat Dec 04 2021 12:09:54 GMT+0300 (Москва, стандартное время)",
      "commitMessage": "Быстрый коммит. А надо!",
      "id": "C7"
    }
  },
  "tags": {},
  "HEAD": {
    "target": "side3",
    "id": "HEAD",
    "type": "general ref"
  },
  "originTree": {
    "branches": {
      "main": {
        "remoteTrackingBranchID": null,
        "remote": false,
        "target": "C8",
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
        "createTime": "Sat Dec 04 2021 12:09:54 GMT+0300 (Москва, стандартное время)",
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
        "createTime": "Sat Dec 04 2021 12:09:54 GMT+0300 (Москва, стандартное время)",
        "commitMessage": "Быстрый коммит. А надо!",
        "id": "C1"
      },
      "C8": {
        "type": "commit",
        "parents": [
          "C1"
        ],
        "author": "Peter Cottle",
        "createTime": "Sat Dec 04 2021 12:09:54 GMT+0300 (Москва, стандартное время)",
        "commitMessage": "Быстрый коммит. А надо!",
        "id": "C8"
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
