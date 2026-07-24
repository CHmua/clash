# OpenClash v65

日期：2026-07-24  
基准版本：clash_worker_v63_lowercase_clash_meta.txt

## 修改内容

- 转换为 GitHub Raw + Subconverter INI 远程配置格式
- 保留 v63 DNS 配置
- 保留 Fake-IP-Filter
- 保留 proxy-server-nameserver
- 保留 AI、Google、TikTok、游戏、流媒体策略组
- 增加 GitHub Raw 基础 YAML 引用方式
- 过滤套餐、流量、到期、官网等信息节点
- 不在公开仓库保存机场订阅地址
- 支持 OpenClash 订阅转换远程配置

## 文件

- openclash_v65_20260724_subconverter_from_v63_rules_fix.ini
- openclash_v65_20260724_base_from_v63_dns_fakeip.yaml

## 使用

将 INI 文件 Raw 地址填入 OpenClash 订阅转换远程配置。
机场订阅地址仍在 OpenClash 订阅列表中填写。
