## 安装依赖

```shell
yarn install
```

## 安装 pods

需提前安装 cocoapods `brew install cocoapods`

```sh
cd ios
pod install
```

## 运行项目

```sh
# 根目录下
yarn ios
```

## 问题总结

- 搭建环境
  - 使用`pod install`安装 pods 时经常失败, 一定要试几次不要删除装过的包, 我尝试了 4 天时间才全部装完, 失败了无数次, 分析是网络问题。
