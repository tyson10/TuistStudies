# TuistStudies
#Tuist 스터디를 위한 공간

## Tuist 란?

- Xcode 프로젝트 관리도구(Command line tool)
- Swift 언어로 프로젝트 관리를 하므로 다른 도구에 비해 사용성이 좋음
- 궁극적으로 모듈화를 사용할 것

[Xcode on steroids | Tuist](https://tuist.io)

## 주요 명령어

- tuist clean
    
    Clean all the data generated by Tuist
    
- tuist fetch
    
    Fetch external dependencies
    
- tuist generate
    
    Generate the project in the current directory
    
- tuist edit
    
    Generates and opens a temporary Xcode project that includes all the manifest files in the current directory, and the files the manifests depend on

- tuist graph
    
    Loads your project dependencies graph and exports it.

## Tip

- Generate 시에 각 프로젝트 별 Sources 폴더내에 swift 파일이 한 개 이상 존재해야 함.
- tuist graph -f dot dot 파일 생성, VSCode 에서 파일 열고 Graphviz extension 설치 후 "CMD + shift + p" 로 Graphviz 사용함.

- Generate 시에 각 프로젝트 별 Sources 폴더내에 swift 파일이 한 개 이상 존재해야 함.
