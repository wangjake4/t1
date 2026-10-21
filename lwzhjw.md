代发 wailian999

[U67] PHP：处理文件上传
来源：http://dali.fengsongda.top/Article/details/gtfnrcsiaa.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.meibo888.top/Article/details/gttvnltaax.html

[U68] PHP：PDO 连接
来源：http://dali.shanyushiyangtech.top/Article/details/gtbpnascqq.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.pengpengdd.cyou/Article/details/gtdjhljrtm.html

[U69] PHP：PDO 预处理
来源：http://dali.gotoacloud.top/Article/details/gtsprxovfq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.xylfe.cn/Article/details/gttdpygeit.html

[U70] PHP：PDO 事务
来源：http://dali.hfpthk.cn/Article/details/gtziwjutdo.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.sxryk.cn/Article/details/gtircptgoj.html

[U71] PHP：抛出异常
来源：http://dali.jianghu66.top/Article/details/gtgbqjvyww.html

throw new RuntimeException("失败", 500);
来源：http://dali.cucudq.cn/Article/details/gtwrrkoymd.html

[U72] PHP：写错误日志
来源：http://dali.gogol.net.cn/Article/details/gtthjawnsr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.aibaodan.cn/Article/details/gtkxgggfls.html

[U73] PHP：读取 ini 配置
来源：http://dali.chenzaomai.com/Article/details/gtsbvpbrhj.html

parse_ini_file("config.ini", true)
来源：http://dali.svipenyu.cn/Article/details/gtwwgubwkh.html

[U74] PHP：读取环境变量
来源：http://dali.316326.xyz/Article/details/gtafgqycip.html

getenv("APP_ENV") ?: "production"
来源：http://dali.cheryme.top/Article/details/gthlfdcmqy.html

[U75] PHP：依赖注入
来源：http://dali.jlsjyb.cn/Article/details/gtihcoiqco.html

composer require psr/container
来源：http://dali.shanyushiyangtech.top/Article/details/gtjwywsxps.html

[U76] PHP：简单路由
来源：http://dali.jiagoushi.top/Article/details/gtsgnwqroe.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.cdnleiting.top/Article/details/gtxpqibhdr.html

[U77] PHP：模板渲染
来源：http://dali.andypj.xyz/Article/details/gtlggfcybx.html

composer require twig/twig
来源：http://dali.shangyingyoupin.top/Article/details/gtwiclxsjn.html

[U78] PHP：单元测试
来源：http://dali.meibo888.top/Article/details/gtaiwcifen.html

composer require --dev phpunit/phpunit
来源：http://dali.havefunace.top/Article/details/gtubwqdpzt.html

[U79] PHP：静态分析
来源：http://dali.yj20258888.top/Article/details/gtfvmmwidj.html

composer require --dev phpstan/phpstan
来源：http://dali.zhengqikj.top/Article/details/gtjlfxjniu.html

[U80] PHP：代码规范修复
来源：http://dali.gotoacloud.top/Article/details/gtozfosyyf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhaomingkeji.xyz/Article/details/gtesztizfr.html

[U81] JS：初始化项目
来源：http://dali.xziqi.cn/Article/details/gtsgahymuf.html

npm init -y;  npm i express
来源：http://dali.yongpay.top/Article/details/gthmpunjql.html

[U82] JS：package.json 脚本
来源：http://dali.iojbl.cn/Article/details/gtizzuvgfv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yj202588.top/Article/details/gtscteghsw.html

[U83] JS：ES Module 导入导出
来源：http://dali.yuxming.cn/Article/details/gtyreijfcf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.nanxinkj.top/Article/details/gtjbixoqlu.html

[U84] JS：CommonJS 写法
来源：http://dali.hfpthk.cn/Article/details/gtcowejkhm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hongshengwenyu.top/Article/details/gthzkmzoru.html

[U85] JS：可选链
来源：http://dali.zdqjudy.top/Article/details/gtvdqbuwyi.html

a?.b?.c
来源：http://dali.gotoacloud.top/Article/details/gtwrgildom.html

[U86] JS：空值合并
来源：http://dali.jinqigfzy.top/Article/details/gtbqvcvcvu.html

a ?? b
来源：http://dali.yanxiufei.cn/Article/details/gtyatnmord.html

[U87] JS：解构默认值
来源：http://dali.c1oappe.top/Article/details/gtpojezgtx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.birdmap.top/Article/details/gtrgiyhrtx.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gtjcweimux.html

{ ...a, ...b }
来源：http://dali.shzxlz.cn/Article/details/gtfupnqtpb.html

[U89] JS：数组去重
来源：http://dali.xuanzx.com/Article/details/gtikoonnqa.html

[...new Set(arr)]
来源：http://dali.guannengcc.top/Article/details/gtwhqumbij.html

[U90] JS：数字数组排序
来源：http://dali.wangshuangyany.cn/Article/details/gteopchgps.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jqgufenzy.top/Article/details/gtpmtuyvrg.html

[U91] JS：对象键值遍历
来源：http://dali.0kj1m.cn/Article/details/gthyaurlas.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.chenlongwang.top/Article/details/gtngitgtha.html

[U92] JS：深拷贝
来源：http://dali.shzxlz.cn/Article/details/gtcgyubpzs.html

structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtoosnjfjh.html

[U93] JS：模板字符串
来源：http://dali.jiagoushi.top/Article/details/gtduiuazlx.html

`共 ${n} 条`
来源：http://dali.kuanghao11.cn/Article/details/gtftxgtxoi.html

[U94] JS：箭头函数
来源：http://dali.yangfankeji.com/Article/details/gteonggwly.html

const double = x => x * 2;
来源：http://dali.hfpthk.cn/Article/details/gtyiasqdgy.html

[U95] JS：Promise 包装
来源：http://dali.yuanzhike.top/Article/details/gtijvamhpl.html

new Promise((resolve, reject) => {})
来源：http://dali.tanke756.top/Article/details/gtqmhgtjwq.html

[U96] JS：async/await 与异常
来源：http://dali.xuanzx.com/Article/details/gtjpqcdetm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gtsrxuuzkv.html

[U97] JS：并发请求
来源：http://dali.shuidangran.top/Article/details/gtvglzsmgd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gtjskinfpw.html

[U98] JS：fetch 带 JSON
来源：http://dali.sxryk.cn/Article/details/gtjsxwmkms.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhengqikj.top/Article/details/gtlhabrclw.html

[U99] JS：事件监听
来源：http://dali.yueranfly.top/Article/details/gthxkqvynp.html

el.addEventListener("click", e => {})
来源：http://dali.zhiwuduotai.top/Article/details/gtfmbthpmx.html

[U100] JS：DOM 查询
来源：http://dali.xylfe.cn/Article/details/gtejrgeiqq.html

document.querySelector(".item")
来源：http://dali.jianghu66.top/Article/details/gtpetmeizh.html

[U101] JS：classList 操作
来源：http://dali.yj20258.top/Article/details/gtjrqglqyj.html

el.classList.toggle("active")
来源：http://dali.guannengcc.top/Article/details/gtvonasvda.html

[U102] JS：本地存储
来源：http://dali.yongpay.top/Article/details/gtsazwdfte.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.nanxuanxn.top/Article/details/gtbbfbpaox.html

[U103] JS：定时器
来源：http://dali.bjfxy.top/Article/details/gthdsxjfsu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cheryme.top/Article/details/gtnlcrsmrd.html

[U104] JS：防抖
来源：http://dali.wangshuangyany.cn/Article/details/gtzzkdcmpy.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gaohongyu789.top/Article/details/gtuxpoxnjd.html

[U105] JS：节流
来源：http://dali.jiagoushi.top/Article/details/gtpwhfpxvc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ydzc1.top/Article/details/gtmsutqsbb.html

[U106] JS：日期格式化
来源：http://dali.yongpay.top/Article/details/gtmxvkwzur.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.gaohongyu789.top/Article/details/gtzwbmxspk.html

[U107] JS：数字千分位
来源：http://dali.yanxiufei.cn/Article/details/gttglwtule.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cdnleiting.top/Article/details/gtlgbwimkh.html

[U108] JS：随机整数
来源：http://dali.yj202588.top/Article/details/gtrarwcvyt.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xuetiantiany.cn/Article/details/gtzenbcizm.html

[U109] JS：数组分组
来源：http://dali.aibaodan.cn/Article/details/gtugedixvi.html

Object.groupBy(arr, x => x.type)
来源：http://dali.cucudq.cn/Article/details/gtfeopuiow.html

[U110] JS：数组分块
来源：http://dali.hongshengwenyu.top/Article/details/gtvmszznqs.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hammf.cn/Article/details/gtbibrzvfw.html

[U111] JS：对象转 Map
来源：http://dali.xylfe.cn/Article/details/gtqrzcqejf.html

new Map(Object.entries(obj))
来源：http://dali.pengpengdd.cyou/Article/details/gtctrrbebz.html

[U112] JS：字符串补位
来源：http://dali.hnxiangtu.top/Article/details/gtslesnssi.html

"7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gtowhfhajf.html

[U113] JS：正则替换全部
来源：http://dali.jiagoushi.top/Article/details/gthpmpmbpy.html

s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtemjumwbt.html

[U114] JS：JSON 深比较
来源：http://dali.pycfn.com/Article/details/gtstmnyhyi.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sweek.top/Article/details/gtrhampqwu.html

[U115] JS：生成 UUID
来源：http://dali.316326.xyz/Article/details/gtxmttainq.html

crypto.randomUUID()
来源：http://dali.redwolf501.top/Article/details/gtqartcgbf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yuanzhike.top/Article/details/gtlnmdgube.html

/** @param {string} name */ function f(name) {}
来源：http://dali.svipenyu.cn/Article/details/gtjvnrjebj.html

[U117] JS：单元测试
来源：http://dali.shzxlz.cn/Article/details/gtcwknzfab.html

npm i -D vitest;  npx vitest
来源：http://dali.hammf.cn/Article/details/gtknxlqerx.html

[U118] JS：开发服务器
来源：http://dali.mhx1999.top/Article/details/gtqvzdowrr.html

npm i -D vite;  npx vite
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdlbnffea.html

[U119] JS：生产构建
来源：http://dali.andypj.xyz/Article/details/gtzkomwxcg.html

npx vite build
来源：http://dali.yvedp.cn/Article/details/gtppxzuclh.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.smart0.xyz/Article/details/gtsuonaesd.html

import.meta.env.VITE_API_URL
来源：http://dali.guannengcc.top/Article/details/gthtzdnnix.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtqxnzdotw.html

统计汇总
来源：http://dali.zhixingplan.top/Article/details/gthpvmwydb.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtjsbubozm.html

按语言统计（条）：
来源：http://dali.pengpengdd.cyou/Article/details/gtbqqvmwdy.html

Python ......... 252
来源：http://dali.cqqwz.cn/Article/details/gthwkqwujo.html

PHP ............ 252
来源：http://dali.yj202588.top/Article/details/gtlxxznqxx.html

JavaScript ..... 252
来源：http://dali.meibo888.top/Article/details/gtflytjihr.html

TypeScript ..... 212
来源：http://dali.jiagoushi.top/Article/details/gthqnofhsv.html

Java ........... 212
来源：http://dali.xuetiantiany.cn/Article/details/gtdtrnbvxb.html

Go ............. 212
来源：http://dali.zhoulong.xyz/Article/details/gtqyyggnel.html

Ruby ........... 212
来源：http://dali.hywenlv.cn/Article/details/gtvoryzmjf.html

C# ............. 212
来源：http://dali.hnxiangtu.top/Article/details/gtdufvxfmo.html

C .............. 30
来源：http://dali.yangfankeji.com/Article/details/gtdumvqwdv.html

C++ ............ 30
来源：http://dali.hammf.cn/Article/details/gtjnoyokuz.html

SQL ............ 90
来源：http://dali.xylfe.cn/Article/details/gtwfyhxdin.html

Bash ........... 80
来源：http://dali.jyoumei.cn/Article/details/gtzpgpjwfk.html

Kotlin ......... 15
来源：http://dali.ybcxt.top/Article/details/gttuvyvjmb.html

Swift .......... 15
来源：http://dali.cheryme.top/Article/details/gtengoevqw.html

Lua ............ 10
来源：http://dali.dianchejie.cn/Article/details/gtkrieyykd.html

Perl ........... 10
来源：http://dali.fzhhl.top/Article/details/gturexxvgb.html

Scala .......... 10
来源：http://dali.shanyushiyangtech.top/Article/details/gtxalpbpav.html

------------------------------------
来源：http://dali.daxiang520.top/Article/details/gtnrjelnzc.html

合计 ........... 2106 条
来源：http://dali.daxiang520.top/Article/details/gthzywtttk.html

按章节统计：
来源：http://dali.zhongyouzk.top/Article/details/gteylfdqrn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jianghu66.top/Article/details/gtzrzinlqd.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.wangshuangyany.cn/Article/details/gtowjtebhm.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shangyingyoupin.top/Article/details/gtvcfwgvir.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cucudq.cn/Article/details/gtyzaziski.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jlsjyb.cn/Article/details/gtirfuqnej.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.fzhhl.top/Article/details/gttpqkeyvr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.cashguo.top/Article/details/gthwpsolot.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.gaohongyu789.top/Article/details/gtbhktskzp.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhoulong.xyz/Article/details/gtehrceqlc.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.nanxuanxn.top/Article/details/gtijzmsyds.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gtoavpyvvy.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yuxming.cn/Article/details/gtbldjytbv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.birdmap.top/Article/details/gtfannqzax.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.sxryk.cn/Article/details/gtmjtowmns.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.iojbl.cn/Article/details/gtwlnuuwho.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.dianchejie.cn/Article/details/gtelzipoiu.html

Q SQL 专题                              90
来源：http://dali.jinqigfzy.top/Article/details/gtxsyxbixs.html

R Bash 专题                             80
来源：http://dali.zycfv.cn/Article/details/gtzbjizmhp.html

S C / C++ 专题                          60
来源：http://dali.yuanzhike.top/Article/details/gtxovmxugj.html

T 其他语言补充                          60
来源：http://dali.jqgfzy.top/Article/details/gtituxpmks.html

U 高频实用片段                         120
来源：http://dali.chenzaomai.com/Article/details/gtrccwaezi.html

------------------------------------
来源：http://dali.birdmap.top/Article/details/gteyystfgb.html

合计                                  2106 条
来源：http://dali.shzxlz.cn/Article/details/gtkoqpozkz.html

--------------------------------------------------------------------------------
来源：http://dali.hysaishi.cn/Article/details/gtclaznabb.html

使用提醒
来源：http://dali.yj20258888.top/Article/details/gtxjjpnqmy.html

--------------------------------------------------------------------------------
来源：http://dali.yj202588.top/Article/details/gtusnkqtid.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.ehwqpu.com/Article/details/gthoxtxdpp.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.wangshuangyany.cn/Article/details/gtnnzyeuux.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.smart0.xyz/Article/details/gtzhfvogqk.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.snrcjt.cn/Article/details/gtvrqjiguf.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hfpthk.cn/Article/details/gtijatqjkf.html

—— 文件结束 ——
来源：http://dali.dashuyun.cn/Article/details/gthxyolbxs.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtjrujppqd.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.wangdashe.top/Article/details/gtcgsqbtpd.html

Common Programming Examples Cheat Book
来源：http://dali.xylfe.cn/Article/details/gtpxxoaemf.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtdtsnimbh.html

【收录内容】
来源：http://dali.smart0.xyz/Article/details/gtdxprbkkz.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.aizwys.cn/Article/details/gtdzoskvip.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.chenlongwang.top/Article/details/gtwmqqxirw.html

SQL · Bash · C · C++
来源：http://dali.hfpthk.cn/Article/details/gtshrumltu.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yvedp.cn/Article/details/gtravweqyx.html

【使用说明】
来源：http://dali.yangfankeji.com/Article/details/gtacebrfvc.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.cheryme.top/Article/details/gtixnxkbyc.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.sufxvd.cn/Article/details/gthgmpfapm.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hysaishi.cn/Article/details/gtpaerniut.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.chenlongwang.top/Article/details/gtautueori.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.aibaodan.cn/Article/details/gtcnmzdztn.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hfpthk.cn/Article/details/gtbdibynrr.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.gaohongyu789.top/Article/details/gtzhxbirwv.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yuanzhike.top/Article/details/gtzsfixbbt.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdecypmof.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.snrcjt.cn/Article/details/gtvhofrpzx.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jyoumei.cn/Article/details/gtgrvimscx.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.hfpthk.cn/Article/details/gtuolrvwoi.html

【文件统计】
来源：http://dali.jianghu66.top/Article/details/gteehptsqt.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yj20258888.top/Article/details/gtcpypqmon.html

--------------------------------------------------------------------------------
来源：http://dali.chenzaomai.com/Article/details/gtpwxmnytu.html

目  录
来源：http://dali.hysaishi.cn/Article/details/gtqsjkkqhi.html

--------------------------------------------------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gtgriglpoc.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.vqdsnc.cn/Article/details/gtxacvjhdc.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.smart0.xyz/Article/details/gtfmnurkvv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.shuidangran.top/Article/details/gtmlphpszs.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ybcxt.top/Article/details/gtuzjuhetl.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.xinyue.icu/Article/details/gtbyruqjlc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.cqqwz.cn/Article/details/gtvyqyqxfm.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhongyouzk.top/Article/details/gtsunsnnew.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.fzhhl.top/Article/details/gtnaabvqnl.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.ydzc1.top/Article/details/gtakkfgjti.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yueranfly.top/Article/details/gtqceakask.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.hammf.cn/Article/details/gtxbfsvzwm.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.gogol.net.cn/Article/details/gtgfvphvmz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yj202588.top/Article/details/gtmxijlebz.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.hnxiangtu.top/Article/details/gtzoyfxqmq.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yj20258.top/Article/details/gtkgzlkrzj.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.sysykeji.top/Article/details/gticipneug.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yj202588.top/Article/details/gtzmusgvxg.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.shuidangran.top/Article/details/gttidxbqas.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.tianlin.xyz/Article/details/gtcbculeeo.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yvedp.cn/Article/details/gtbqhcqcja.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcsfhenyh.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtdxkwsdhb.html

A. 基础语法与类型
来源：http://dali.xziqi.cn/Article/details/gtvxpkvlsx.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtwrmbvklz.html

[A01] Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyefnouwf.html

Py:   print("Hello, World!")
来源：http://dali.smart0.xyz/Article/details/gtnjbltabs.html

PHP:  echo "Hello, World!";
来源：http://dali.hnqzz.top/Article/details/gtasmoncpt.html

JS:   console.log("Hello, World!");
来源：http://dali.redwolf501.top/Article/details/gtkufatuum.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jlsjyb.cn/Article/details/gtuggjknwf.html

Java: System.out.println("Hello, World!");
来源：http://dali.chenlongwang.top/Article/details/gtzsrxrocl.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.cheryme.top/Article/details/gtxxhjozco.html

Ruby: puts "Hello, World!"
来源：http://dali.jinghuilouyu.cn/Article/details/gtraeaarxz.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.nwbrower.top/Article/details/gtadkfspqi.html

[A02] 变量声明与赋值
来源：http://dali.jinqigfzy.top/Article/details/gthrgbzcmh.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.snrcjt.cn/Article/details/gticvpqnih.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.tianlin.xyz/Article/details/gthiwjmlmj.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.redwolf501.top/Article/details/gtwpnzsqzi.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.cdnleiting.top/Article/details/gttkhnchmx.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yuxming.cn/Article/details/gtxcbangzy.html

Go:   name := "Alex"; age := 20
来源：http://dali.nanxinkj.top/Article/details/gtkefbuzpb.html

Ruby: name = "Alex"; age = 20
来源：http://dali.cdnleiting.top/Article/details/gtadlbpbxw.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.sweek.top/Article/details/gtiluoftsx.html

[A03] 常量定义
来源：http://dali.chenjidiqi.icu/Article/details/gterioykcg.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.vqdsnc.cn/Article/details/gtunkdtwke.html

PHP:  const PI = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gtfsnwimtt.html

JS:   const PI = 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gtedbjzbhu.html

TS:   const PI: number = 3.14159;
来源：http://dali.wangdashe.top/Article/details/gtwnpcyjvx.html

Java: static final double PI = 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gtxihvizvx.html

Go:   const PI = 3.14159
来源：http://dali.nanxinkj.top/Article/details/gtwlermpiq.html

Ruby: PI = 3.14159
来源：http://dali.cqqwz.cn/Article/details/gteialpamq.html

C#:   const double PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtugibqlop.html

[A04] 判断变量类型
来源：http://dali.9152youxi.cn/Article/details/gtfclayzbk.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.sxryk.cn/Article/details/gtmpsvqwnt.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.shanyushiyangtech.top/Article/details/gteovjffuh.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.svipenyu.cn/Article/details/gtzqmieffe.html

TS:   typeof x; x instanceof Date
来源：http://dali.yj20258888.top/Article/details/gtzvddmzio.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.dianchejie.cn/Article/details/gtqulpabvb.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jinghuilouyu.cn/Article/details/gtqaubcrvp.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhongyouzk.top/Article/details/gtbjhylhxy.html

C#:   x.GetType().Name; x is int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfagxdcgy.html

[A05] 整数除法与取模
来源：http://dali.yuxming.cn/Article/details/gtllbfdrrg.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.sxryk.cn/Article/details/gtdprarbig.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.xinyue.icu/Article/details/gthvdiftmh.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gtedvgmpyo.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gtpdjahuee.html

Java: 7 / 2; 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gtabnzvnpk.html

Go:   7 / 2; 7 % 2
来源：http://dali.nwbrower.top/Article/details/gtttzpujwc.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxpxyeqew.html

C#:   7 / 2; 7 % 2
来源：http://dali.svipenyu.cn/Article/details/gtuqgkfgcn.html

[A06] 字符串转数字
来源：http://dali.snrcjt.cn/Article/details/gtocikgzvj.html

Py:   int("42"); float("3.14")
来源：http://dali.guowangkeji.top/Article/details/gttwpmjxgh.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.shzxlz.cn/Article/details/gtswbayxvk.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.havefunace.top/Article/details/gtkcofcpjp.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hnqzz.top/Article/details/gttznrmepv.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.mhx1999.top/Article/details/gtdjottagv.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.xylfe.cn/Article/details/gtuhdrydrr.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jinqigfzy.top/Article/details/gtltcwlckl.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.haohaochexian.top/Article/details/gtjddbswru.html

[A07] 数字转字符串
来源：http://dali.fzhhl.top/Article/details/gttlzptbzh.html

Py:   str(42)
来源：http://dali.gzhubu.top/Article/details/gtkcjwexjl.html

PHP:  (string) 42; strval(42)
来源：http://dali.meibo888.top/Article/details/gtmabrxxrr.html

JS:   String(42); (42).toString()
来源：http://dali.shzxlz.cn/Article/details/gtfottdnlq.html

TS:   String(42)
来源：http://dali.zhiwuduotai.top/Article/details/gttnkpzkgo.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.guowangkeji.top/Article/details/gtqpnmmkud.html

Go:   strconv.Itoa(42)
来源：http://dali.0kj1m.cn/Article/details/gtqjbefpsj.html

Ruby: 42.to_s
来源：http://dali.cucudq.cn/Article/details/gtdnptkysg.html

C#:   42.ToString()
来源：http://dali.quarkkingdee.top/Article/details/gtscownjub.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gtpoexuriq.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.shuidangran.top/Article/details/gtjaggsvsf.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zycfv.cn/Article/details/gtmxffyfua.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.nanxuanxn.top/Article/details/gtlmtfkytb.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.haohaochexian.top/Article/details/gtljeearyn.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jlsjyb.cn/Article/details/gthilglvyq.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.tianlin.xyz/Article/details/gtcmsnnxor.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.9152youxi.cn/Article/details/gtuzxmfnhd.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.wangshuangyany.cn/Article/details/gtjfcexprd.html

[A09] 绝对值与最大最小值
来源：http://dali.yueranfly.top/Article/details/gtcjobhakv.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.shuidangran.top/Article/details/gtorcrdfye.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.guowangkeji.top/Article/details/gtbmvcycuu.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.guannengcc.top/Article/details/gtpdgmxinr.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtsydooaug.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.sweek.top/Article/details/gtsxixcsru.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.snrcjt.cn/Article/details/gtyqjgshgy.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.daria6918.cn/Article/details/gtqczhhkcu.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.dianchejie.cn/Article/details/gtdqucehhe.html

[A10] 生成随机数
来源：http://dali.daria6918.cn/Article/details/gtfoksqcca.html

Py:   import random; random.randint(1, 100)
来源：http://dali.ydzc1.top/Article/details/gtdzcltaed.html

PHP:  random_int(1, 100);
来源：http://dali.andypj.xyz/Article/details/gtbadcuxtl.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.wangdashe.top/Article/details/gtvzpeubsd.html


<!-- 参考信息 -->