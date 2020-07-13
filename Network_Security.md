# Network Security 网络安全三大要素 (CIA)
* Confidentialty (保密性)
## 
1. 加密
2. 权限管理
3. 敏感信息暴露

* Integrity（数据完整性）

  Integrity——数据内容完整、没有被篡改——Signature数字签名校验

* Availabitiy(可用性)

# STRIDE（Microsoft提出的威胁分析模型）
* Spoofing 伪装 —— 认证
* Tampering 篡改 —— 验证完整性->签名校验
* Repudiation 抵赖 —— 否认做过的事，要有不可抵赖性-> 签名校验
* Information Disclosure 信息泄露
* Denial of Service Dos 可用性
* Elevation of privilege 提升节点

1. 黑名单+白名单(白名单比黑名单安全)
2. 最小权限原则(需要什么权限就给什么权限,不能给额外的)不能偷懒
3. 纵深防御(Defense in Depth)不同的层面(web应用，网络，数据库，OS)都要有相应的安全权限配置
4. 数据与代码分离，广泛适用于各种注入问题和缓存区溢出的问题
5. 不可预测性，用户的id或者交易号id等标识随机变化

