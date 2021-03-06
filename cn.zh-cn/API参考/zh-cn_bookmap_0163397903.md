# API参考

-   [使用前必读](使用前必读.md)
-   [如何调用API](如何调用API.md)
    -   [构造请求](构造请求.md)
    -   [认证鉴权](认证鉴权.md)
    -   [返回结果](返回结果.md)

-   [Token管理](Token管理.md)
    -   [获取IAM用户Token（使用密码）](获取IAM用户Token（使用密码）.md)
    -   [获取IAM用户Token（使用密码+虚拟MFA）](获取IAM用户Token（使用密码+虚拟MFA）.md)
    -   [获取委托Token](获取委托Token.md)
    -   [校验Token的有效性](校验Token的有效性.md)

-   [Credential管理](Credential管理.md)
    -   [通过委托获取临时访问密钥和securitytoken](通过委托获取临时访问密钥和securitytoken.md)
    -   [通过token获取临时访问密钥和securitytoken](通过token获取临时访问密钥和securitytoken.md)
    -   [创建永久访问密钥](创建永久访问密钥.md)
    -   [查询所有永久访问密钥](查询所有永久访问密钥.md)
    -   [查询指定永久访问密钥](查询指定永久访问密钥.md)
    -   [修改指定永久访问密钥](修改指定永久访问密钥.md)
    -   [删除指定永久访问密钥](删除指定永久访问密钥.md)

-   [区域管理](区域管理.md)
    -   [查询区域列表](查询区域列表.md)
    -   [查询区域详情](查询区域详情.md)

-   [项目管理](项目管理.md)
    -   [查询指定条件下的项目列表](查询指定条件下的项目列表.md)
    -   [查询指定IAM用户的项目列表](查询指定IAM用户的项目列表.md)
    -   [查询IAM用户可以访问的项目列表](查询IAM用户可以访问的项目列表.md)
    -   [创建项目](创建项目.md)
    -   [修改项目信息](修改项目信息.md)
    -   [查询项目详情](查询项目详情.md)
    -   [设置项目状态](设置项目状态.md)
    -   [查询项目详情与状态](查询项目详情与状态.md)

-   [账号管理](账号管理.md)
    -   [查询IAM用户可以访问的账号详情](查询IAM用户可以访问的账号详情.md)
    -   [查询账号密码强度策略](查询账号密码强度策略.md)
    -   [按条件查询账号密码强度策略](按条件查询账号密码强度策略.md)

-   [IAM用户管理](IAM用户管理.md)
    -   [管理员查询IAM用户列表](管理员查询IAM用户列表.md)
    -   [查询IAM用户详情（推荐）](查询IAM用户详情（推荐）.md)
    -   [查询IAM用户详情](查询IAM用户详情.md)
    -   [查询IAM用户所属用户组](查询IAM用户所属用户组.md)
    -   [管理员查询用户组所包含的IAM用户](管理员查询用户组所包含的IAM用户.md)
    -   [管理员创建IAM用户（推荐）](管理员创建IAM用户（推荐）.md)
    -   [管理员创建IAM用户](管理员创建IAM用户.md)
    -   [修改IAM用户密码](修改IAM用户密码.md)
    -   [修改IAM用户信息（推荐）](修改IAM用户信息（推荐）.md)
    -   [管理员修改IAM用户信息（推荐）](管理员修改IAM用户信息（推荐）.md)
    -   [管理员修改IAM用户信息](管理员修改IAM用户信息.md)
    -   [管理员删除IAM用户](管理员删除IAM用户.md)

-   [用户组管理](用户组管理.md)
    -   [查询用户组列表](查询用户组列表.md)
    -   [查询用户组详情](查询用户组详情.md)
    -   [创建用户组](创建用户组.md)
    -   [更新用户组](更新用户组.md)
    -   [删除用户组](删除用户组.md)
    -   [查询IAM用户是否在用户组中](查询IAM用户是否在用户组中.md)
    -   [添加IAM用户到用户组](添加IAM用户到用户组.md)
    -   [移除用户组中的IAM用户](移除用户组中的IAM用户.md)

-   [权限管理](权限管理.md)
    -   [查询权限列表](查询权限列表.md)
    -   [查询权限详情](查询权限详情.md)
    -   [查询全局服务中的用户组权限](查询全局服务中的用户组权限.md)
    -   [查询项目服务中的用户组权限](查询项目服务中的用户组权限.md)
    -   [为用户组授予全局服务权限](为用户组授予全局服务权限.md)
    -   [为用户组授予项目服务权限](为用户组授予项目服务权限.md)
    -   [查询用户组是否拥有全局服务权限](查询用户组是否拥有全局服务权限.md)
    -   [查询用户组是否拥有项目服务权限](查询用户组是否拥有项目服务权限.md)
    -   [移除用户组的全局服务权限](移除用户组的全局服务权限.md)
    -   [移除用户组的项目服务权限](移除用户组的项目服务权限.md)
    -   [为用户组授予所有项目服务权限](为用户组授予所有项目服务权限.md)

-   [自定义策略管理](自定义策略管理.md)
    -   [查询自定义策略列表](查询自定义策略列表.md)
    -   [查询自定义策略详情](查询自定义策略详情.md)
    -   [创建云服务自定义策略](创建云服务自定义策略.md)
    -   [创建委托自定义策略](创建委托自定义策略.md)
    -   [修改云服务自定义策略](修改云服务自定义策略.md)
    -   [修改委托自定义策略](修改委托自定义策略.md)
    -   [删除自定义策略](删除自定义策略.md)

-   [委托管理](委托管理.md)
    -   [查询指定条件下的委托列表](查询指定条件下的委托列表.md)
    -   [查询委托详情](查询委托详情.md)
    -   [创建委托](创建委托.md)
    -   [修改委托](修改委托.md)
    -   [删除委托](删除委托.md)
    -   [查询全局服务中的委托权限](查询全局服务中的委托权限.md)
    -   [查询项目服务中的委托权限](查询项目服务中的委托权限.md)
    -   [为委托授予全局服务权限](为委托授予全局服务权限.md)
    -   [为委托授予项目服务权限](为委托授予项目服务权限.md)
    -   [查询委托是否拥有全局服务权限](查询委托是否拥有全局服务权限.md)
    -   [查询委托是否拥有项目服务权限](查询委托是否拥有项目服务权限.md)
    -   [移除委托的全局服务权限](移除委托的全局服务权限.md)
    -   [移除委托的项目服务权限](移除委托的项目服务权限.md)

-   [联邦身份认证管理](联邦身份认证管理.md)
    -   [通过联邦认证获取token](通过联邦认证获取token.md)
        -   [SP initiated方式](SP-initiated方式.md)
        -   [IdP initiated方式](IdP-initiated方式.md)

    -   [身份提供商](身份提供商.md)
        -   [查询身份提供商列表](查询身份提供商列表.md)
        -   [查询身份提供商详情](查询身份提供商详情.md)
        -   [注册身份提供商](注册身份提供商.md)
        -   [更新身份提供商](更新身份提供商.md)
        -   [删除身份提供商](删除身份提供商.md)

    -   [映射](映射.md)
        -   [查询映射列表](查询映射列表.md)
        -   [查询映射详情](查询映射详情.md)
        -   [注册映射](注册映射.md)
        -   [更新映射](更新映射.md)
        -   [删除映射](删除映射.md)

    -   [协议](协议.md)
        -   [查询协议列表](查询协议列表.md)
        -   [查询协议详情](查询协议详情.md)
        -   [注册协议](注册协议.md)
        -   [更新协议](更新协议.md)
        -   [删除协议](删除协议.md)

    -   [Metadata](Metadata.md)
        -   [查询Metadata文件](查询Metadata文件.md)
        -   [查询Keystone的Metadata文件](查询Keystone的Metadata文件.md)
        -   [导入Metadata文件](导入Metadata文件.md)

    -   [Token](Token.md)
        -   [获取联邦认证unscoped token\(SP initiated\)](获取联邦认证unscoped-token(SP-initiated).md)
        -   [获取联邦认证unscoped token\(IdP initiated\)](获取联邦认证unscoped-token(IdP-initiated).md)
        -   [获取联邦认证scoped token](获取联邦认证scoped-token.md)

    -   [查询联邦用户可以访问的账号列表](查询联邦用户可以访问的账号列表.md)
    -   [查询联邦用户可以访问的项目列表](查询联邦用户可以访问的项目列表.md)

-   [自定义代理](自定义代理.md)
    -   [获取自定义代理登录票据](获取自定义代理登录票据.md)

-   [版本信息管理](版本信息管理.md)
    -   [查询Keystone API的版本信息](查询Keystone-API的版本信息.md)
    -   [查询Keystone API的3.0版本信息](查询Keystone-API的3-0版本信息.md)

-   [服务和终端节点](服务和终端节点.md)
    -   [查询服务列表](查询服务列表.md)
    -   [查询服务详情](查询服务详情.md)
    -   [查询服务目录](查询服务目录.md)
    -   [查询终端节点列表](查询终端节点列表.md)
    -   [查询终端节点详情](查询终端节点详情.md)

-   [附录](附录.md)
    -   [状态码](状态码.md)
    -   [获取账号、IAM用户、项目、用户组、委托的名称和ID](获取账号-IAM用户-项目-用户组-委托的名称和ID.md)

-   [授权项](授权项.md)
-   [修订记录](修订记录.md)

