go build -trimpath -mod=vendor   -tags "seccomp" -ldflags "-X main.gitCommit="e515dec7f9c4adb7d15155f1f33da486772fd0f5-dirty" -X main.version=1.0.0-rc93 " -o runc .
