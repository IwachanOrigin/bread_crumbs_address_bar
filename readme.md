
# Bread Crumbs Address Bar

## Introduction

    Qt 5.15.2 を用いたパンくずリスト形式のアドレスバー実装です。  
    PyQtで実装されていたものをC++で再実装しました。  

## Demo

![demo](https://user-images.githubusercontent.com/12496951/236679963-8ffae3d5-c02a-4877-8af2-24ee4f6b6f71.gif)

## Verification OS

    Windows10 Pro 21H2  

## Build

    ex. VS2017 の場合  
    powershell.exe cmake -S . -B build -G "\"Visual Studio 15 2017 Win64\"" -DQTDIR="<Qtのパス>"  
    powershell.exe cmake --build build  

    ex. VS2019以上の場合  
    powershell.exe cmake -S . -B build -DQTDIR="<Qtのパス>"  
    powershell.exe cmake --build build  

    ex. Ninja + LLVMの場合(LLVM 16 win64で検証)  
    powershell.exe cmake -S . -B build -G "\"Ninja Multi-Config\"" -DQTDIR="<Qtのパス>"  
    powershell.exe cmake --build build --config debug

## Reference

[breadcrumbsaddressbar](https://github.com/Winand/breadcrumbsaddressbar)  

