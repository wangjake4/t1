代发 wailian999

[U67] PHP：处理文件上传
来源：http://dali.shangyingyoupin.top/Article/details/gthnbohgzf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.bjfxy.top/Article/details/gtzpmslyxr.html

[U68] PHP：PDO 连接
来源：http://dali.nanxinkj.top/Article/details/gtthmexuud.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hongshengwenyu.top/Article/details/gtrwovzjvu.html

[U69] PHP：PDO 预处理
来源：http://dali.bjfxy.top/Article/details/gtfpzwzjke.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.nwbrower.top/Article/details/gtzajjhrhl.html

[U70] PHP：PDO 事务
来源：http://dali.zhiwuduotai.top/Article/details/gtmylhihgz.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhiwuduotai.top/Article/details/gtqzrmvmhm.html

[U71] PHP：抛出异常
来源：http://dali.chenjidiqi.icu/Article/details/gtvivwmyyl.html

throw new RuntimeException("失败", 500);
来源：http://dali.cashguo.top/Article/details/gtssjdcpgm.html

[U72] PHP：写错误日志
来源：http://dali.cheryme.top/Article/details/gtenganlqc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.gogol.net.cn/Article/details/gtwhsgdkcl.html

[U73] PHP：读取 ini 配置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlacaakxd.html

parse_ini_file("config.ini", true)
来源：http://dali.zhongyouzk.top/Article/details/gtgyipkimk.html

[U74] PHP：读取环境变量
来源：http://dali.vqdsnc.cn/Article/details/gterorwyct.html

getenv("APP_ENV") ?: "production"
来源：http://dali.sxryk.cn/Article/details/gtenvbdika.html

[U75] PHP：依赖注入
来源：http://dali.9152youxi.cn/Article/details/gtviuzpvtv.html

composer require psr/container
来源：http://dali.tanke756.top/Article/details/gtlyxrdlbc.html

[U76] PHP：简单路由
来源：http://dali.birdmap.top/Article/details/gtvhufoclg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.pengpengdd.cyou/Article/details/gtiffvayla.html

[U77] PHP：模板渲染
来源：http://dali.meibo888.top/Article/details/gtpidmsrjz.html

composer require twig/twig
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmgwewtav.html

[U78] PHP：单元测试
来源：http://dali.0kj1m.cn/Article/details/gtdoopnygt.html

composer require --dev phpunit/phpunit
来源：http://dali.sysykeji.top/Article/details/gtejkjjykz.html

[U79] PHP：静态分析
来源：http://dali.sufxvd.cn/Article/details/gtmlbdiqeb.html

composer require --dev phpstan/phpstan
来源：http://dali.gzhubu.top/Article/details/gtgtyfdlew.html

[U80] PHP：代码规范修复
来源：http://dali.redwolf501.top/Article/details/gttsqwgwts.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.wangshuangyany.cn/Article/details/gthxihocdj.html

[U81] JS：初始化项目
来源：http://dali.jqgufenzy.top/Article/details/gtlslzsptw.html

npm init -y;  npm i express
来源：http://dali.yj20258888.top/Article/details/gtpgefkbgt.html

[U82] JS：package.json 脚本
来源：http://dali.cdnleiting.top/Article/details/gtwfuclpiz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.havefunace.top/Article/details/gtqlwalilv.html

[U83] JS：ES Module 导入导出
来源：http://dali.nanxinkj.top/Article/details/gtovsqdxbe.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.sufxvd.cn/Article/details/gtynrpgkob.html

[U84] JS：CommonJS 写法
来源：http://dali.hongshengwenyu.top/Article/details/gtitmhknlf.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yangfankeji.com/Article/details/gtfvxpkfnt.html

[U85] JS：可选链
来源：http://dali.jinqigufen.top/Article/details/gtngfbsfhj.html

a?.b?.c
来源：http://dali.jinqigfzy.top/Article/details/gtuhzygjdn.html

[U86] JS：空值合并
来源：http://dali.tianlin.xyz/Article/details/gtgcvzxamt.html

a ?? b
来源：http://dali.pycfn.com/Article/details/gtkqbkqvvw.html

[U87] JS：解构默认值
来源：http://dali.ybcxt.top/Article/details/gtppouzcei.html

const { a = 1, b = 2 } = obj;
来源：http://dali.shangyingyoupin.top/Article/details/gtxuvzskse.html

[U88] JS：对象展开合并
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnhykrhdz.html

{ ...a, ...b }
来源：http://dali.xinyue.icu/Article/details/gtbmswxzws.html

[U89] JS：数组去重
来源：http://dali.zhiwuduotai.top/Article/details/gtcusqohtj.html

[...new Set(arr)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxnndlakt.html

[U90] JS：数字数组排序
来源：http://dali.dashuyun.cn/Article/details/gtzvbsjbhe.html

[...arr].sort((a, b) => a - b)
来源：http://dali.fzhhl.top/Article/details/gtseczqtye.html

[U91] JS：对象键值遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtytjrdrlr.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yanxiufei.cn/Article/details/gtqyaiqhit.html

[U92] JS：深拷贝
来源：http://dali.ivvv.top/Article/details/gtycnvfghi.html

structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtwftfajaa.html

[U93] JS：模板字符串
来源：http://dali.hywenlv.cn/Article/details/gtdtaggzup.html

`共 ${n} 条`
来源：http://dali.yanxiufei.cn/Article/details/gtpyygbghl.html

[U94] JS：箭头函数
来源：http://dali.zhixingplan.top/Article/details/gtmjfpluhz.html

const double = x => x * 2;
来源：http://dali.nanxuanxn.top/Article/details/gtfttsjcme.html

[U95] JS：Promise 包装
来源：http://dali.shzxlz.cn/Article/details/gtkkxvfkqs.html

new Promise((resolve, reject) => {})
来源：http://dali.sxryk.cn/Article/details/gtrjikwsgs.html

[U96] JS：async/await 与异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtcfmotfoe.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yj202588.top/Article/details/gtptmtsyzp.html

[U97] JS：并发请求
来源：http://dali.316326.xyz/Article/details/gtuwfuddzu.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sweek.top/Article/details/gtilfrfyrv.html

[U98] JS：fetch 带 JSON
来源：http://dali.sweek.top/Article/details/gtlimznhlk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.wangshuangyany.cn/Article/details/gtcizvrzuq.html

[U99] JS：事件监听
来源：http://dali.andypj.xyz/Article/details/gtrkhdesja.html

el.addEventListener("click", e => {})
来源：http://dali.cqqwz.cn/Article/details/gtiyfmoilj.html

[U100] JS：DOM 查询
来源：http://dali.yj20258888.top/Article/details/gtmngiwhph.html

document.querySelector(".item")
来源：http://dali.gotoacloud.top/Article/details/gtaebnckta.html

[U101] JS：classList 操作
来源：http://dali.cucudq.cn/Article/details/gtdkwovmgo.html

el.classList.toggle("active")
来源：http://dali.wangshuangyany.cn/Article/details/gtxwlzgjdj.html

[U102] JS：本地存储
来源：http://dali.xuetiantiany.cn/Article/details/gttquskgvp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.tanke756.top/Article/details/gtgkrzhevg.html

[U103] JS：定时器
来源：http://dali.yongpay.top/Article/details/gtnbygojfz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xuanzx.com/Article/details/gtdzibhzso.html

[U104] JS：防抖
来源：http://dali.jinghuilouyu.cn/Article/details/gtfqmhblsq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnqzz.top/Article/details/gtfpoilzsm.html

[U105] JS：节流
来源：http://dali.jqgfzy.top/Article/details/gtmlopaqva.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.haohaochexian.top/Article/details/gtuggwczib.html

[U106] JS：日期格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmyjhlvr.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.shzxlz.cn/Article/details/gthqpykbts.html

[U107] JS：数字千分位
来源：http://dali.cheryme.top/Article/details/gtgtfatreu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.gotoacloud.top/Article/details/gtpmzkvnvh.html

[U108] JS：随机整数
来源：http://dali.wangshuangyany.cn/Article/details/gtupismewm.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.tianlin.xyz/Article/details/gtcweejoxb.html

[U109] JS：数组分组
来源：http://dali.vqdsnc.cn/Article/details/gtjdbinjtf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.aibaodan.cn/Article/details/gtqujmisft.html

[U110] JS：数组分块
来源：http://dali.chenjidiqi.icu/Article/details/gtlusbopbo.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yangfankeji.com/Article/details/gtfjhgqisr.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gtoiipjzab.html

new Map(Object.entries(obj))
来源：http://dali.hnxiangtu.top/Article/details/gtuhuschvr.html

[U112] JS：字符串补位
来源：http://dali.cdnleiting.top/Article/details/gtrufxlmkg.html

"7".padStart(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqcjwfzce.html

[U113] JS：正则替换全部
来源：http://dali.fengsongda.top/Article/details/gtdueespcb.html

s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjzbmrarb.html

[U114] JS：JSON 深比较
来源：http://dali.c1oappe.top/Article/details/gtqioqzfzl.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.haohaochexian.top/Article/details/gtfssyshfe.html

[U115] JS：生成 UUID
来源：http://dali.hnqzz.top/Article/details/gtzoxtocdk.html

crypto.randomUUID()
来源：http://dali.dashuyun.cn/Article/details/gtzdrcytzt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.0kj1m.cn/Article/details/gtjwcaveza.html

/** @param {string} name */ function f(name) {}
来源：http://dali.sufxvd.cn/Article/details/gtyqmnakjs.html

[U117] JS：单元测试
来源：http://dali.redwolf501.top/Article/details/gtbgnhscxa.html

npm i -D vitest;  npx vitest
来源：http://dali.tianlin.xyz/Article/details/gtyemgbias.html

[U118] JS：开发服务器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtelwqwxxg.html

npm i -D vite;  npx vite
来源：http://dali.tian-w.cn/Article/details/gttqzoxbei.html

[U119] JS：生产构建
来源：http://dali.nwbrower.top/Article/details/gtgqthimma.html

npx vite build
来源：http://dali.dashuyun.cn/Article/details/gtlkebnwiq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.smart0.xyz/Article/details/gtggvjlolk.html

import.meta.env.VITE_API_URL
来源：http://dali.yueranfly.top/Article/details/gtmvbithzz.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtsanrtgam.html

统计汇总
来源：http://dali.wangdashe.top/Article/details/gtebbuuymo.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtjwprrxug.html

按语言统计（条）：
来源：http://dali.aizwys.cn/Article/details/gturishyqn.html

Python ......... 252
来源：http://dali.hfpthk.cn/Article/details/gtcbrehnsy.html

PHP ............ 252
来源：http://dali.zhoulong.xyz/Article/details/gtsrqpsism.html

JavaScript ..... 252
来源：http://dali.aibaodan.cn/Article/details/gtuplumgtg.html

TypeScript ..... 212
来源：http://dali.tanke756.top/Article/details/gtsvabgekn.html

Java ........... 212
来源：http://dali.tanke756.top/Article/details/gtpsddbrie.html

Go ............. 212
来源：http://dali.xuanzx.com/Article/details/gtikgcwoqa.html

Ruby ........... 212
来源：http://dali.guowangkeji.top/Article/details/gtmhvpzoeo.html

C# ............. 212
来源：http://dali.jinqigfzy.top/Article/details/gtowdhlvzr.html

C .............. 30
来源：http://dali.hnxiangtu.top/Article/details/gtbjdqzsab.html

C++ ............ 30
来源：http://dali.pycfn.com/Article/details/gtrornbbis.html

SQL ............ 90
来源：http://dali.zhoulong.xyz/Article/details/gterdqbwwt.html

Bash ........... 80
来源：http://dali.nwbrower.top/Article/details/gtaztwjywi.html

Kotlin ......... 15
来源：http://dali.jinqigfzy.top/Article/details/gtsblwgwsd.html

Swift .......... 15
来源：http://dali.nanxuanxn.top/Article/details/gtmrehzklb.html

Lua ............ 10
来源：http://dali.xinyue.icu/Article/details/gtydmnonmj.html

Perl ........... 10
来源：http://dali.yuxming.cn/Article/details/gthidgutia.html

Scala .......... 10
来源：http://dali.jinqigufen.top/Article/details/gthpiqauit.html

------------------------------------
来源：http://dali.yueranfly.top/Article/details/gtvlcwdueo.html

合计 ........... 2106 条
来源：http://dali.wangshuangyany.cn/Article/details/gttylhadyr.html

按章节统计：
来源：http://dali.vqdsnc.cn/Article/details/gtbujwvemv.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.9152youxi.cn/Article/details/gtfhynkjev.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvzbbuopa.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.sufxvd.cn/Article/details/gtfyndfoan.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.guowangkeji.top/Article/details/gtvfwjyxdr.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.cucudq.cn/Article/details/gttoiaqscp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hysaishi.cn/Article/details/gtzxmvxfeh.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.vqdsnc.cn/Article/details/gthdsqfvws.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hywenlv.cn/Article/details/gtuwnterxn.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.svipenyu.cn/Article/details/gtqatyounc.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.gaohongyu789.top/Article/details/gtlasrtauk.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gtlxxcobun.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hnxiangtu.top/Article/details/gtjitzphpy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.aizwys.cn/Article/details/gtpuzgbibb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yuanzhike.top/Article/details/gtncphvazp.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yuxming.cn/Article/details/gtgvonteaw.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.andypj.xyz/Article/details/gtbnhorygm.html

Q SQL 专题                              90
来源：http://dali.wangshuangyany.cn/Article/details/gtezgcmvul.html

R Bash 专题                             80
来源：http://dali.chenzaomai.com/Article/details/gtnsbeugaj.html

S C / C++ 专题                          60
来源：http://dali.hywenlv.cn/Article/details/gtrpcobbcm.html

T 其他语言补充                          60
来源：http://dali.aibaodan.cn/Article/details/gtgxheuutt.html

U 高频实用片段                         120
来源：http://dali.pengpengdd.cyou/Article/details/gttdhewcdx.html

------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gtyhzhsqdr.html

合计                                  2106 条
来源：http://dali.feifeiyinyue.top/Article/details/gthrrqpqck.html

--------------------------------------------------------------------------------
来源：http://dali.dashuyun.cn/Article/details/gtlcdwkuup.html

使用提醒
来源：http://dali.vqdsnc.cn/Article/details/gteexwpxkx.html

--------------------------------------------------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gtrgxkkzfb.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.bjfxy.top/Article/details/gtmjrssvfs.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hywenlv.cn/Article/details/gtaiygqdok.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.andypj.xyz/Article/details/gtvlzngank.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.sufxvd.cn/Article/details/gtbazcwsbm.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yuxming.cn/Article/details/gtxrjmdbdl.html

—— 文件结束 ——
来源：http://dali.yueranfly.top/Article/details/gtraoxyjhu.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtrqxmfpui.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.bjfxy.top/Article/details/gtuiqgxvxw.html

Common Programming Examples Cheat Book
来源：http://dali.gaohongyu789.top/Article/details/gtpuekvqkb.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gteshlzlyt.html

【收录内容】
来源：http://dali.iojbl.cn/Article/details/gtvvguvdaz.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jqgufenzy.top/Article/details/gtsfxyzlaj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.pycfn.com/Article/details/gtyalgwxqj.html

SQL · Bash · C · C++
来源：http://dali.yj202588.top/Article/details/gtqqjhgbmw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.shzxlz.cn/Article/details/gtvheilqnb.html

【使用说明】
来源：http://dali.chenlongwang.top/Article/details/gtwtglajbx.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.pengpengdd.cyou/Article/details/gtadkkeeul.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gthqoglbdp.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.guannengcc.top/Article/details/gtmzglqwfh.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.fengsongda.top/Article/details/gtfutgwjre.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xylfe.cn/Article/details/gtunuvshdp.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhengqikj.top/Article/details/gtuhejllhw.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.nanxuanxn.top/Article/details/gtzmsopysk.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.gaohongyu789.top/Article/details/gtyuyetbgi.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jqgfzy.top/Article/details/gtyokeuppq.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.xuanzx.com/Article/details/gtocmqwmfe.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yueranfly.top/Article/details/gtaixrsrbg.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.xziqi.cn/Article/details/gtfnquhfah.html

【文件统计】
来源：http://dali.zycfv.cn/Article/details/gtnbvokicb.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.quarkkingdee.top/Article/details/gturdqpdeq.html

--------------------------------------------------------------------------------
来源：http://dali.daxiang520.top/Article/details/gtryksgokf.html

目  录
来源：http://dali.yangfankeji.com/Article/details/gtnryuasjk.html

--------------------------------------------------------------------------------
来源：http://dali.316326.xyz/Article/details/gtbbqronks.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.meibo888.top/Article/details/gtdyusklig.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.sysykeji.top/Article/details/gtthuzlpgr.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhixingplan.top/Article/details/gtlphczlav.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.quarkkingdee.top/Article/details/gtmyfsupym.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yuxming.cn/Article/details/gtbhwxrrhb.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.sxryk.cn/Article/details/gtnmbvqdnm.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhengqikj.top/Article/details/gtxsdqnore.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hysaishi.cn/Article/details/gtyixrqaqn.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.meibo888.top/Article/details/gtibtdthjv.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.quarkkingdee.top/Article/details/gtdpwnhtru.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbbcfqns.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhongyouzk.top/Article/details/gtfzzzmifu.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.tianlin.xyz/Article/details/gtzpjoiyao.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jinqigfzy.top/Article/details/gthwoaiaoi.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.hammf.cn/Article/details/gttdftljlp.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zdqjudy.top/Article/details/gtbdpqupbx.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.xylfe.cn/Article/details/gtyfvijync.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.ehwqpu.com/Article/details/gtlrbdsyra.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yanxiufei.cn/Article/details/gtpxfuyhaz.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cucudq.cn/Article/details/gtgualjxwh.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.0kj1m.cn/Article/details/gtpgqcsqfs.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtvtkurhqc.html

A. 基础语法与类型
来源：http://dali.chenzaomai.com/Article/details/gtpnvbjnwo.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtwtexaegp.html

[A01] Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutxqrizf.html

Py:   print("Hello, World!")
来源：http://dali.quarkkingdee.top/Article/details/gtzniyhcgz.html

PHP:  echo "Hello, World!";
来源：http://dali.daria6918.cn/Article/details/gtcmhwaheh.html

JS:   console.log("Hello, World!");
来源：http://dali.nanxuanxn.top/Article/details/gtjnveqkrq.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.c1oappe.top/Article/details/gtjlwhggcp.html

Java: System.out.println("Hello, World!");
来源：http://dali.jianghu66.top/Article/details/gtiqespeki.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhoulong.xyz/Article/details/gtfmfvjkla.html

Ruby: puts "Hello, World!"
来源：http://dali.chenlongwang.top/Article/details/gtghmjpnxv.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.dashuyun.cn/Article/details/gtvanebkzg.html

[A02] 变量声明与赋值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtedmwbyrw.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.gzhubu.top/Article/details/gtlowbdbyr.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.snrcjt.cn/Article/details/gtrrsbvunh.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yj20258.top/Article/details/gteuivmmkd.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.0kj1m.cn/Article/details/gtsqenlnqj.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.pycfn.com/Article/details/gtbhkoszwe.html

Go:   name := "Alex"; age := 20
来源：http://dali.sysykeji.top/Article/details/gtpdcolcck.html

Ruby: name = "Alex"; age = 20
来源：http://dali.shzxlz.cn/Article/details/gtgvillbps.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.tanke756.top/Article/details/gtdzkzaoww.html

[A03] 常量定义
来源：http://dali.jlsjyb.cn/Article/details/gtdnolvtzh.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.smart0.xyz/Article/details/gtymfkqvww.html

PHP:  const PI = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gtxncqhcpx.html

JS:   const PI = 3.14159;
来源：http://dali.sweek.top/Article/details/gtykhksgkj.html

TS:   const PI: number = 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gtyhboecrc.html

Java: static final double PI = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gtxuxzekjk.html

Go:   const PI = 3.14159
来源：http://dali.yueranfly.top/Article/details/gtfdzvwsfx.html

Ruby: PI = 3.14159
来源：http://dali.guowangkeji.top/Article/details/gtwjaypnyx.html

C#:   const double PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gtsvndrxto.html

[A04] 判断变量类型
来源：http://dali.yj20258.top/Article/details/gtfkyuwgxa.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jinqigfzy.top/Article/details/gtaifyqrjf.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.xinyue.icu/Article/details/gtbnhhjahd.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zycfv.cn/Article/details/gtezyeidlp.html

TS:   typeof x; x instanceof Date
来源：http://dali.shanyushiyangtech.top/Article/details/gtcjfiapsj.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.feifeiyinyue.top/Article/details/gtquofgrfy.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.chenlongwang.top/Article/details/gtvsjwgmgz.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.tian-w.cn/Article/details/gtxzorumpo.html

C#:   x.GetType().Name; x is int
来源：http://dali.9152youxi.cn/Article/details/gtckfkhzej.html

[A05] 整数除法与取模
来源：http://dali.yj20258888.top/Article/details/gtnajzmaqg.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.ivvv.top/Article/details/gtcdhdanhl.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yvedp.cn/Article/details/gtnttktadc.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.pengpengdd.cyou/Article/details/gtvnwgqtyf.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhoulong.xyz/Article/details/gtoaeynjna.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gtxvbkfqkl.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhoulong.xyz/Article/details/gtcaqigmsj.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.havefunace.top/Article/details/gtmsetgyfq.html

C#:   7 / 2; 7 % 2
来源：http://dali.xinyue.icu/Article/details/gtssdvhfzq.html

[A06] 字符串转数字
来源：http://dali.snrcjt.cn/Article/details/gtivrpshpu.html

Py:   int("42"); float("3.14")
来源：http://dali.sweek.top/Article/details/gthphdumqt.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.smart0.xyz/Article/details/gtccmrprzb.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.quarkkingdee.top/Article/details/gtvgzgdftu.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.vqdsnc.cn/Article/details/gtupwdyrgy.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.cqqwz.cn/Article/details/gtymzzusgh.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yuanzhike.top/Article/details/gthufjivju.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.shanyushiyangtech.top/Article/details/gtpznijrxt.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zdqjudy.top/Article/details/gtewwiwnds.html

[A07] 数字转字符串
来源：http://dali.c1oappe.top/Article/details/gtrgiyqdgd.html

Py:   str(42)
来源：http://dali.fzhhl.top/Article/details/gtoublprnr.html

PHP:  (string) 42; strval(42)
来源：http://dali.yj20258888.top/Article/details/gtfgpsfvot.html

JS:   String(42); (42).toString()
来源：http://dali.vqdsnc.cn/Article/details/gtzkuruhmm.html

TS:   String(42)
来源：http://dali.guowangkeji.top/Article/details/gtngrsplli.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.ivvv.top/Article/details/gtsipumuwz.html

Go:   strconv.Itoa(42)
来源：http://dali.nanxuanxn.top/Article/details/gtdoyuteeo.html

Ruby: 42.to_s
来源：http://dali.snrcjt.cn/Article/details/gtizffsyag.html

C#:   42.ToString()
来源：http://dali.jqgufenzy.top/Article/details/gtixydkqcb.html

[A08] 取整与四舍五入
来源：http://dali.cqqwz.cn/Article/details/gtfetjxuvc.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.cashguo.top/Article/details/gtysgnwffk.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhiwuduotai.top/Article/details/gtohykvhss.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.snrcjt.cn/Article/details/gtzchrsgzo.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.316326.xyz/Article/details/gtoyohpydz.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.316326.xyz/Article/details/gtvajbhzwn.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.snrcjt.cn/Article/details/gttxokgugu.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.pycfn.com/Article/details/gtgyhzgvfp.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.hnqzz.top/Article/details/gtmrstfhzy.html

[A09] 绝对值与最大最小值
来源：http://dali.c1oappe.top/Article/details/gtaspwoixu.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.sufxvd.cn/Article/details/gtdolbgptt.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zdqjudy.top/Article/details/gtdkdceayn.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.shzxlz.cn/Article/details/gtsauncuak.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.kuanghao11.cn/Article/details/gtgzatfmaf.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.fengsongda.top/Article/details/gtfuddbbkh.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.daria6918.cn/Article/details/gtnsivbbdk.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.c1oappe.top/Article/details/gtmgtmmzfu.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbrxvjbgb.html

[A10] 生成随机数
来源：http://dali.nwbrower.top/Article/details/gtvzehwaqc.html

Py:   import random; random.randint(1, 100)
来源：http://dali.iojbl.cn/Article/details/gtvlspqttq.html

PHP:  random_int(1, 100);
来源：http://dali.xylfe.cn/Article/details/gttxftgnks.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xziqi.cn/Article/details/gtwjfycdfs.html


<!-- 参考信息 -->