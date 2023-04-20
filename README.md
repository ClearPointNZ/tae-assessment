# Test Automation Task

## Overview

This task is intended to give ClearPoint a high level idea about a candidate’s abstract technical abilities. This task should not take a long time to complete. The submitted response must be your own work.

**_Please treat this document as confidential.  Do not share or redistribute this document._**

## Instructions

**_Ensure you have [docker and docker-compose installed](https://docs.docker.com/compose/install/)_**

Run `docker-compose up` from the repo root. This will spin up a container that hosts a TodoList API. The Open-API specification will be available at;
```
http://localhost:3002/swagger
```

The task is to demonstrate automated testing on the API in a small project.

Unless otherwise agreed, complete the task using either the JavaScript or the TypeScript languages. If this is not possible then please communicate this early with your hiring contact at ClearPoint.

## Notes

If you use *MacOS* computer to do the asssessment, you may need to update the `docker-compose.yml` `image` with the version 2.0.0 (`clearpointnz/coding-assessment:2.0.0`) which built specifically for `linux/arm64`. Otherwise, for *Linux* and *Windows*, use the default version 1.0.0.

Please note the following general points;

- Avoid excessive use of third party libraries.
- Send us a link to your public or private git repository that contains your completed solution. If the repository is private, your contact at ClearPoint will indicate which person or people will need to be provided access.
- Do not supply binaries or build products.
- If you are using a build system please give brief instructions on how to build a runnable binary.
