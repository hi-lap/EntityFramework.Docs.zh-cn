# [Entity Framework](index.md)

## [比较 EF Core 和 EF6](efcore-and-ef6/index.md)

### [同一应用程序中的 EF6 和 EF Core](efcore-and-ef6/side-by-side.md)
### [从 EF6 移植到 EF Core](efcore-and-ef6/porting/index.md)
#### [验证要求](efcore-and-ef6/porting/ensure-requirements.md)
#### [移植基于 EDMX 的模型](efcore-and-ef6/porting/port-edmx.md)
#### [移植基于 Code 的模型](efcore-and-ef6/porting/port-code.md)

## [Entity Framework Core](core/index.md)

### [新增功能](core/what-is-new/index.md)
#### [EF Core 路线图](core/what-is-new/roadmap.md)
#### [EF Core 2.2（预览版）](core/what-is-new/ef-core-2.2.md)
#### [EF Core 2.1（最新稳定版）](core/what-is-new/ef-core-2.1.md)
#### [EF Core 2.0](core/what-is-new/ef-core-2.0.md)
#### [EF Core 1.1](core/what-is-new/ef-core-1.1.md)
#### [EF Core 1.0](core/what-is-new/ef-core-1.0.md)
#### 从早期版本升级
##### [从 1.0 RC1 升级到 RC2](core/miscellaneous/rc1-rc2-upgrade.md)
##### [从 1.0 RC2 升级到 RTM](core/miscellaneous/rc2-rtm-upgrade.md)
##### [从 1.x 升级到 2.0](core/miscellaneous/1x-2x-upgrade.md)

### [入门](core/get-started/index.md)
#### [安装 EF Core](core/get-started/install/index.md)
#### [.NET Core](core/get-started/netcore/index.md)
##### [新建数据库](core/get-started/netcore/new-db-sqlite.md)
#### [ASP.NET Core](core/get-started/aspnetcore/index.md)
##### [新建数据库](core/get-started/aspnetcore/new-db.md)
##### [现有数据库](core/get-started/aspnetcore/existing-db.md)
##### [⤤ EF Core 和 Razor Pages](/aspnet/core/data/ef-rp/intro)
#### [通用 Windows 平台 (UWP)](core/get-started/uwp/index.md)
##### [新建数据库](core/get-started/uwp/getting-started.md)
#### [.NET Framework](core/get-started/full-dotnet/index.md)
##### [新建数据库](core/get-started/full-dotnet/new-db.md)
##### [现有数据库](core/get-started/full-dotnet/existing-db.md)

### 基础知识
#### [连接字符串](core/miscellaneous/connection-strings.md)
#### [日志记录](core/miscellaneous/logging.md)
#### [连接弹性](core/miscellaneous/connection-resiliency.md)
#### [测试](core/miscellaneous/testing/index.md)
##### [使用 SQLite 进行测试](core/miscellaneous/testing/sqlite.md)
##### [使用 InMemory 进行测试](core/miscellaneous/testing/in-memory.md)
#### [配置 DbContext](core/miscellaneous/configuring-dbcontext.md)

### [创建模型](core/modeling/index.md)
#### [包含类型和排除类型](core/modeling/included-types.md)
#### [包含属性和排除属性](core/modeling/included-properties.md)
#### [键（主要）](core/modeling/keys.md)
#### [生成的值](core/modeling/generated-properties.md)
#### [必需/可选属性](core/modeling/required-optional.md)
#### [最大长度](core/modeling/max-length.md)
#### [并发令牌](core/modeling/concurrency.md)
#### [阴影属性](core/modeling/shadow-properties.md)
#### [关系](core/modeling/relationships.md)
#### [索引](core/modeling/indexes.md)
#### [备用键](core/modeling/alternate-keys.md)
#### [继承](core/modeling/inheritance.md)
#### [支持字段](core/modeling/backing-field.md)
#### [值转换](core/modeling/value-conversions.md)
#### [数据种子设定](core/modeling/data-seeding.md)
#### [实体类型构造函数](core/modeling/constructors.md)
#### [固有实体类型](core/modeling/owned-entities.md)
#### [查询类型](core/modeling/query-types.md)
#### [具有相同 DbContext 的交替模型](core/modeling/dynamic-model.md)
#### [空间数据 (GIS)](core/modeling/spatial.md)
#### [关系数据库建模](core/modeling/relational/index.md)
##### [表映射](core/modeling/relational/tables.md)
##### [列映射](core/modeling/relational/columns.md)
##### [数据类型](core/modeling/relational/data-types.md)
##### [主键](core/modeling/relational/primary-keys.md)
##### [默认架构](core/modeling/relational/default-schema.md)
##### [计算列](core/modeling/relational/computed-columns.md)
##### [序列](core/modeling/relational/sequences.md)
##### [默认值](core/modeling/relational/default-values.md)
##### [索引](core/modeling/relational/indexes.md)
##### [外键约束](core/modeling/relational/fk-constraints.md)
##### [备用键（唯一约束）](core/modeling/relational/unique-constraints.md)
##### [继承（关系数据库）](core/modeling/relational/inheritance.md)

### [管理数据库架构](core/managing-schemas/index.md)
#### [迁移](core/managing-schemas/migrations/index.md)
##### [团队环境](core/managing-schemas/migrations/teams.md)
##### [自定义操作](core/managing-schemas/migrations/operations.md)
##### [使用独立项目](core/managing-schemas/migrations/projects.md)
##### [多个提供程序](core/managing-schemas/migrations/providers.md)
##### [自定义历史记录表](core/managing-schemas/migrations/history-table.md)
#### [创建和删除 API](core/managing-schemas/ensure-created.md)
#### [反向工程（基架）](core/managing-schemas/scaffolding.md)

### [查询数据](core/querying/index.md)
#### [基本查询](core/querying/basic.md)
#### [加载关联数据](core/querying/related-data.md)
#### [客户端与服务器评估](core/querying/client-eval.md)
#### [跟踪与非跟踪](core/querying/tracking.md)
#### [原始 SQL 查询](core/querying/raw-sql.md)
#### [异步查询](core/querying/async.md)
#### [查询的工作原理](core/querying/overview.md)
#### [全局查询筛选器](core/querying/filters.md)
#### [查询标记](core/querying/tags.md)

### [保存数据](core/saving/index.md)
#### [基本保存](core/saving/basic.md)
#### [关联数据](core/saving/related-data.md)
#### [级联删除](core/saving/cascade-delete.md)
#### [并发冲突](core/saving/concurrency.md)
#### [事务](core/saving/transactions.md)
#### [异步保存](core/saving/async.md)
#### [处于连接断开状态的实体](core/saving/disconnected-entities.md)
#### [生成的属性的显式值](core/saving/explicit-values-generated-properties.md)

### [支持的 .NET 实现](core/platforms/index.md)

### [数据库提供程序](core/providers/index.md)
#### [Microsoft SQL Server](core/providers/sql-server/index.md)
##### [内存优化表](core/providers/sql-server/memory-optimized-tables.md)
#### [SQLite](core/providers/sqlite/index.md)
##### [SQLite 限制](core/providers/sqlite/limitations.md)
#### [InMemory（用于测试）](core/providers/in-memory/index.md)
#### [编写数据库提供程序](core/providers/writing-a-provider.md)
#### [提供程序影响的更改](core/providers/provider-log.md)

### [工具和扩展](core/extensions/index.md)

### [命令行参考](core/miscellaneous/cli/index.md)
#### [包管理器控制台 (Visual Studio)](core/miscellaneous/cli/powershell.md)
#### [.NET Core CLI](core/miscellaneous/cli/dotnet.md)
#### [设计时 DbContext 创建](core/miscellaneous/cli/dbcontext-creation.md)
#### [设计时服务](core/miscellaneous/cli/services.md)

### [⤤ EF Core API 参考](https://docs.microsoft.com/dotnet/api/?view=efcore-2.1)

## [Entity Framework 6](ef6/index.md)

### [新增功能](ef6/what-is-new/index.md)
#### [路线图](ef6/what-is-new/roadmap.md)
#### [以前的版本](ef6/what-is-new/past-releases.md)
#### [升级到 EF6](ef6/what-is-new/upgrading-to-ef6.md)
#### [Visual Studio 版本](ef6/what-is-new/visual-studio.md)

### [入门](ef6/get-started.md)

### [基础知识](ef6/fundamentals/index.md)
#### [获取 Entity Framework](ef6/fundamentals/install.md)
#### [使用 DbContext](ef6/fundamentals/working-with-dbcontext.md)
#### [了解关系](ef6/fundamentals/relationships.md)
#### [异步查询和保存](ef6/fundamentals/async.md)
#### 配置
##### [基于代码](ef6/fundamentals/configuring/code-based.md)
##### [配置文件](ef6/fundamentals/configuring/config-file.md)
##### [连接字符串](ef6/fundamentals/configuring/connection-strings.md)
##### [依赖项解析](ef6/fundamentals/configuring/dependency-resolution.md)
#### [连接管理](ef6/fundamentals/connection-management.md)
#### 连接弹性
##### [重试逻辑](ef6/fundamentals/connection-resiliency/retry-logic.md)
##### [事务提交失败](ef6/fundamentals/connection-resiliency/commit-failures.md)
#### 数据绑定
##### [WinForms](ef6/fundamentals/databinding/winforms.md)
##### [WPF](ef6/fundamentals/databinding/wpf.md)
#### [断开连接的实体](ef6/fundamentals/disconnected-entities/index.md)
##### [自跟踪实体](ef6/fundamentals/disconnected-entities/self-tracking-entities/index.md)
###### [演练](ef6/fundamentals/disconnected-entities/self-tracking-entities/walkthrough.md)
#### [日志记录和拦截](ef6/fundamentals/logging-and-interception.md)
#### 性能
##### [性能注意事项](ef6/fundamentals/performance/perf-whitepaper.md)
##### [使用 NGEN](ef6/fundamentals/performance/ngen.md)
##### [使用预生成的视图](ef6/fundamentals/performance/pre-generated-views.md)
#### [提供程序](ef6/fundamentals/providers/index.md)
##### [EF6 提供程序模型](ef6/fundamentals/providers/provider-model.md)
##### [提供程序中的空间支持](ef6/fundamentals/providers/spatial-support.md)
#### [使用代理](ef6/fundamentals/proxies.md)
#### 使用 EF6 进行测试
##### [使用模拟](ef6/fundamentals/testing/mocking.md)
##### [编写自己的测试双精度值](ef6/fundamentals/testing/writing-test-doubles.md)
##### [使用 EF4 的可测试性（文章）](ef6/fundamentals/testing/testability-article.md)

### [创建模型](ef6/modeling/index.md)
#### 使用 Code First
##### 工作流
###### [使用新数据库](ef6/modeling/code-first/workflows/new-database.md)
###### [使用现有数据库](ef6/modeling/code-first/workflows/existing-database.md)
##### [数据注释](ef6/modeling/code-first/data-annotations.md)
##### [DbSets](ef6/modeling/code-first/dbsets.md)
##### 数据类型
###### [枚举](ef6/modeling/code-first/data-types/enums.md)
###### [空间](ef6/modeling/code-first/data-types/spatial.md)
##### 约定
###### [内置约定](ef6/modeling/code-first/conventions/built-in.md)
###### [自定义约定](ef6/modeling/code-first/conventions/custom.md)
###### [模型约定](ef6/modeling/code-first/conventions/model.md)
##### Fluent 配置
###### [关系](ef6/modeling/code-first/fluent/relationships.md)
###### [类型和属性](ef6/modeling/code-first/fluent/types-and-properties.md)
###### [在 Visual Basic 中使用](ef6/modeling/code-first/fluent/vb.md)
###### [存储过程映射](ef6/modeling/code-first/fluent/cud-stored-procedures.md)
##### [迁移](ef6/modeling/code-first/migrations/index.md)
###### [自动迁移](ef6/modeling/code-first/migrations/automatic.md)
###### [使用现有数据库](ef6/modeling/code-first/migrations/existing-database.md)
###### [自定义迁移历史记录](ef6/modeling/code-first/migrations/history-customization.md)
###### [使用 Migrate.exe](ef6/modeling/code-first/migrations/migrate-exe.md)
###### [团队环境中的迁移](ef6/modeling/code-first/migrations/teams.md)

#### 使用 EF 设计器
##### 工作流
###### [Model-First](ef6/modeling/designer/workflows/model-first.md)
###### [Database-First](ef6/modeling/designer/workflows/database-first.md)
##### 数据类型
###### [复杂类型](ef6/modeling/designer/data-types/complex-types.md)
###### [枚举](ef6/modeling/designer/data-types/enums.md)
###### [空间](ef6/modeling/designer/data-types/spatial.md)
##### 拆分映射
###### [实体拆分](ef6/modeling/designer/entity-splitting.md)
###### [表拆分](ef6/modeling/designer/table-splitting.md)
##### 继承映射
###### [每个层次结构的表](ef6/modeling/designer/inheritance/tph.md)
###### [每种类型的表](ef6/modeling/designer/inheritance/tpt.md)
##### 映射存储过程
###### [查询](ef6/modeling/designer/stored-procedures/query.md)
###### [更新](ef6/modeling/designer/stored-procedures/cud.md)
##### [映射关系](ef6/modeling/designer/relationships.md)
##### [多个关系图](ef6/modeling/designer/multiple-diagrams.md)
##### [选择运行时版本](ef6/modeling/designer/select-runtime-version.md)
##### [代码生成](ef6/modeling/designer/codegen/index.md)
###### [Legacy ObjectContext ](ef6/modeling/designer/codegen/legacy-objectcontext.md)
##### 高级
###### EDMX 文件格式
####### [CSDL 规范](ef6/modeling/designer/advanced/edmx/csdl-spec.md)
####### [MSL 规范](ef6/modeling/designer/advanced/edmx/msl-spec.md)
####### [SSDL 规范](ef6/modeling/designer/advanced/edmx/ssdl-spec.md)
###### [定义查询](ef6/modeling/designer/advanced/defining-query.md)
###### [多个结果集](ef6/modeling/designer/advanced/multiple-result-sets.md)
###### [表值函数](ef6/modeling/designer/advanced/tvfs.md)
##### [键盘快捷键](ef6/modeling/designer/keyboard-shortcuts.md)

### [查询数据](ef6/querying/index.md)
#### [Load 方法](ef6/querying/load-method.md)
#### [本地数据](ef6/querying/local-data.md)
#### [跟踪和无跟踪查询](ef6/querying/no-tracking.md)
#### [使用原始 SQL 查询](ef6/querying/raw-sql.md)
#### [查询相关数据](ef6/querying/related-data.md)

### [保存数据](ef6/saving/index.md)
#### 更改跟踪
##### [自动检测更改](ef6/saving/change-tracking/auto-detect-changes.md)
##### [实体状态](ef6/saving/change-tracking/entity-state.md)
##### [属性值](ef6/saving/change-tracking/property-values.md)
#### [处理并发冲突](ef6/saving/concurrency.md)
#### [使用事务](ef6/saving/transactions.md)
#### [数据验证](ef6/saving/validation.md)

### [其他资源](ef6/resources/index.md)
#### [博客](ef6/resources/blogs.md)
#### [案例研究](ef6/resources/case-studies.md)
#### [参与](ef6/resources/contribute.md)
#### [获取帮助](ef6/resources/get-help.md)
#### [术语表](ef6/resources/glossary.md)
#### [School 示例数据库](ef6/resources/school-database.md)
#### [工具和扩展](ef6/resources/tools.md)
#### 许可证
##### EF5
###### [简体中文](ef6/resources/licenses/ef5/chs.md)
###### [繁体中文](ef6/resources/licenses/ef5/cht.md)
###### [德语](ef6/resources/licenses/ef5/deu.md)
###### [英语](ef6/resources/licenses/ef5/enu.md)
###### [西班牙语](ef6/resources/licenses/ef5/esn.md)
###### [法语](ef6/resources/licenses/ef5/fra.md)
###### [意大利语](ef6/resources/licenses/ef5/ita.md)
###### [日语](ef6/resources/licenses/ef5/jpn.md)
###### [韩语](ef6/resources/licenses/ef5/kor.md)
###### [俄语](ef6/resources/licenses/ef5/rus.md)
##### EF6
###### 预发行
####### [Alpha](ef6/resources/licenses/ef6/prerelease/alpha.md)
####### [Beta 版本 - 候选发布](ef6/resources/licenses/ef6/prerelease/beta-rc.md)
###### [简体中文](ef6/resources/licenses/ef6/chs.md)
###### [繁体中文](ef6/resources/licenses/ef6/cht.md)
###### [德语](ef6/resources/licenses/ef6/deu.md)
###### [英语](ef6/resources/licenses/ef6/enu.md)
###### [西班牙语](ef6/resources/licenses/ef6/esn.md)
###### [法语](ef6/resources/licenses/ef6/fra.md)
###### [意大利语](ef6/resources/licenses/ef6/ita.md)
###### [日语](ef6/resources/licenses/ef6/jpn.md)
###### [韩语](ef6/resources/licenses/ef6/kor.md)
###### [俄语](ef6/resources/licenses/ef6/rus.md)

### [⤤ EF6 API 参考](https://msdn.microsoft.com/library/dn223258.aspx)
