代发 wailian999

[U67] PHP：处理文件上传
来源：http://dali.sufxvd.cn/Article/details/gt2hxvpitue.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.9152youxi.cn/Article/details/gt2smwnkslm.html

[U68] PHP：PDO 连接
来源：http://dali.xuetiantiany.cn/Article/details/gt2zhjcsjgd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.tian-w.cn/Article/details/gt2dqhgkwwm.html

[U69] PHP：PDO 预处理
来源：http://dali.yongpay.top/Article/details/gt2wprpmnnu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.dianchejie.cn/Article/details/gt2oradyfqx.html

[U70] PHP：PDO 事务
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cayfqhib.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.feifeiyinyue.top/Article/details/gt2wacjzbyw.html

[U71] PHP：抛出异常
来源：http://dali.cqqwz.cn/Article/details/gt2gjakadqn.html

throw new RuntimeException("失败", 500);
来源：http://dali.yanxiufei.cn/Article/details/gt2ydntkotw.html

[U72] PHP：写错误日志
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zvjwokgy.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jinqigufen.top/Article/details/gt2ikzekamg.html

[U73] PHP：读取 ini 配置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zmdrxfli.html

parse_ini_file("config.ini", true)
来源：http://dali.quarkkingdee.top/Article/details/gt2jkedlisx.html

[U74] PHP：读取环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2uydvvtmm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.cdnleiting.top/Article/details/gt2jruipnxt.html

[U75] PHP：依赖注入
来源：http://dali.jyoumei.cn/Article/details/gt2eycypwjg.html

composer require psr/container
来源：http://dali.xziqi.cn/Article/details/gt2gwmzkmjg.html

[U76] PHP：简单路由
来源：http://dali.gaohongyu789.top/Article/details/gt2xsbjmsro.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.316326.xyz/Article/details/gt2uzfguyrw.html

[U77] PHP：模板渲染
来源：http://dali.wangshuangyany.cn/Article/details/gt2ydfuccnt.html

composer require twig/twig
来源：http://dali.zhoulong.xyz/Article/details/gt2npwscauu.html

[U78] PHP：单元测试
来源：http://dali.sweek.top/Article/details/gt2rwirwgfq.html

composer require --dev phpunit/phpunit
来源：http://dali.zhoulong.xyz/Article/details/gt2yweveing.html

[U79] PHP：静态分析
来源：http://dali.0kj1m.cn/Article/details/gt2huvfmxpu.html

composer require --dev phpstan/phpstan
来源：http://dali.xuetiantiany.cn/Article/details/gt2kigcpbuw.html

[U80] PHP：代码规范修复
来源：http://dali.hongshengwenyu.top/Article/details/gt2hehlptcz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yuxming.cn/Article/details/gt2nlfwkaor.html

[U81] JS：初始化项目
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sryzbztk.html

npm init -y;  npm i express
来源：http://dali.ivvv.top/Article/details/gt2hzrxzioz.html

[U82] JS：package.json 脚本
来源：http://dali.shangyingyoupin.top/Article/details/gt2zkqogiys.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.shuidangran.top/Article/details/gt2afdqlxpf.html

[U83] JS：ES Module 导入导出
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sgkqjsuz.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ybcxt.top/Article/details/gt2rsjeudtf.html

[U84] JS：CommonJS 写法
来源：http://dali.yonumen.top/Article/details/gt2iuistufs.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.aibaodan.cn/Article/details/gt2yxbkyhqo.html

[U85] JS：可选链
来源：http://dali.redwolf501.top/Article/details/gt2sbcsrspj.html

a?.b?.c
来源：http://dali.316326.xyz/Article/details/gt2gjbpcntr.html

[U86] JS：空值合并
来源：http://dali.guannengcc.top/Article/details/gt2wruvvkjo.html

a ?? b
来源：http://dali.iojbl.cn/Article/details/gt2adtuodkm.html

[U87] JS：解构默认值
来源：http://dali.sysykeji.top/Article/details/gt2oizlvley.html

const { a = 1, b = 2 } = obj;
来源：http://dali.shuidangran.top/Article/details/gt2gmrvbctn.html

[U88] JS：对象展开合并
来源：http://dali.tianlin.xyz/Article/details/gt2kvxtllax.html

{ ...a, ...b }
来源：http://dali.cucudq.cn/Article/details/gt2xurtipyh.html

[U89] JS：数组去重
来源：http://dali.0kj1m.cn/Article/details/gt2lrhrdenz.html

[...new Set(arr)]
来源：http://dali.snrcjt.cn/Article/details/gt2jmxjutfq.html

[U90] JS：数字数组排序
来源：http://dali.jianghu66.top/Article/details/gt2fdjfpntv.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhoulong.xyz/Article/details/gt2sefxfahj.html

[U91] JS：对象键值遍历
来源：http://dali.dianchejie.cn/Article/details/gt2lsdvneno.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yueranfly.top/Article/details/gt2fioievdk.html

[U92] JS：深拷贝
来源：http://dali.sxryk.cn/Article/details/gt2ywhkgrwf.html

structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2swvufpvi.html

[U93] JS：模板字符串
来源：http://dali.zhixingplan.top/Article/details/gt2nsnoqxyn.html

`共 ${n} 条`
来源：http://dali.gotoacloud.top/Article/details/gt2tqxyenwm.html

[U94] JS：箭头函数
来源：http://dali.hnqzz.top/Article/details/gt2hqxvmsyd.html

const double = x => x * 2;
来源：http://dali.yuxming.cn/Article/details/gt2ygsyqeja.html

[U95] JS：Promise 包装
来源：http://dali.aibaodan.cn/Article/details/gt2bnstkpco.html

new Promise((resolve, reject) => {})
来源：http://dali.zhoulong.xyz/Article/details/gt2tblswiwq.html

[U96] JS：async/await 与异常
来源：http://dali.c1oappe.top/Article/details/gt2mrhbvvjy.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.cheryme.top/Article/details/gt2uxlkigzz.html

[U97] JS：并发请求
来源：http://dali.zycfv.cn/Article/details/gt2jnrixcvg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.kuanghao11.cn/Article/details/gt2idgoivav.html

[U98] JS：fetch 带 JSON
来源：http://dali.guowangkeji.top/Article/details/gt2uxnebbgq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zycfv.cn/Article/details/gt2jyvwvxap.html

[U99] JS：事件监听
来源：http://dali.feifeiyinyue.top/Article/details/gt2yejvtysu.html

el.addEventListener("click", e => {})
来源：http://dali.jianghu66.top/Article/details/gt2xicpqnyq.html

[U100] JS：DOM 查询
来源：http://dali.hywenlv.cn/Article/details/gt2akcbwrem.html

document.querySelector(".item")
来源：http://dali.xuetiantiany.cn/Article/details/gt2piaopzrw.html

[U101] JS：classList 操作
来源：http://dali.birdmap.top/Article/details/gt2tttrghud.html

el.classList.toggle("active")
来源：http://dali.cashguo.top/Article/details/gt2lrvkrclx.html

[U102] JS：本地存储
来源：http://dali.tian-w.cn/Article/details/gt2ftnozhix.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.aibaodan.cn/Article/details/gt2glxhgbvh.html

[U103] JS：定时器
来源：http://dali.svipenyu.cn/Article/details/gt2dlfwcgvw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.havefunace.top/Article/details/gt2ihgkhxcc.html

[U104] JS：防抖
来源：http://dali.guannengcc.top/Article/details/gt2rtmyaqwy.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.birdmap.top/Article/details/gt2korvefpf.html

[U105] JS：节流
来源：http://dali.xylfe.cn/Article/details/gt2aqaxsjut.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhoulong.xyz/Article/details/gt2qikoujyf.html

[U106] JS：日期格式化
来源：http://dali.hfpthk.cn/Article/details/gt2onorwabt.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hnxiangtu.top/Article/details/gt2dvcxykew.html

[U107] JS：数字千分位
来源：http://dali.316326.xyz/Article/details/gt2tgymjtiz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.aibaodan.cn/Article/details/gt2thfvqscm.html

[U108] JS：随机整数
来源：http://dali.chenzaomai.com/Article/details/gt2wejyqaus.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mnyypqoa.html

[U109] JS：数组分组
来源：http://dali.hnqzz.top/Article/details/gt2asespjdd.html

Object.groupBy(arr, x => x.type)
来源：http://dali.wangshuangyany.cn/Article/details/gt2dfvyiqvb.html

[U110] JS：数组分块
来源：http://dali.c1oappe.top/Article/details/gt2uafvfkdp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinqigufen.top/Article/details/gt2vhyjasrj.html

[U111] JS：对象转 Map
来源：http://dali.feifeiyinyue.top/Article/details/gt2tgwlrxuf.html

new Map(Object.entries(obj))
来源：http://dali.birdmap.top/Article/details/gt2eixfuomd.html

[U112] JS：字符串补位
来源：http://dali.sxryk.cn/Article/details/gt2lentigrb.html

"7".padStart(3, "0")
来源：http://dali.fengsongda.top/Article/details/gt2fcvhitpi.html

[U113] JS：正则替换全部
来源：http://dali.gogol.net.cn/Article/details/gt2lsptoicm.html

s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gt2swioleyv.html

[U114] JS：JSON 深比较
来源：http://dali.nanxinkj.top/Article/details/gt2saykkfgt.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jqgufenzy.top/Article/details/gt2ddvibvud.html

[U115] JS：生成 UUID
来源：http://dali.fzhhl.top/Article/details/gt2wcsltgpv.html

crypto.randomUUID()
来源：http://dali.aibaodan.cn/Article/details/gt2vigwlixv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.sysykeji.top/Article/details/gt2eambddjr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2pzfjebxc.html

[U117] JS：单元测试
来源：http://dali.ppjwa.cn/Article/details/gt2mqxfggyu.html

npm i -D vitest;  npx vitest
来源：http://dali.zhiwuduotai.top/Article/details/gt2wxlmashv.html

[U118] JS：开发服务器
来源：http://dali.hnqzz.top/Article/details/gt2flzlybsx.html

npm i -D vite;  npx vite
来源：http://dali.yanxiufei.cn/Article/details/gt2fmtyqxea.html

[U119] JS：生产构建
来源：http://dali.redwolf501.top/Article/details/gt2zbaalktf.html

npx vite build
来源：http://dali.zhiwuduotai.top/Article/details/gt2xgrdbcen.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.nanxuanxn.top/Article/details/gt2zvpexxjx.html

import.meta.env.VITE_API_URL
来源：http://dali.fzhhl.top/Article/details/gt2jytxhfoc.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2ppahddhs.html

统计汇总
来源：http://dali.iojbl.cn/Article/details/gt2gnxmdlqz.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2emmbpwuk.html

按语言统计（条）：
来源：http://dali.gotoacloud.top/Article/details/gt2vqlpujji.html

Python ......... 252
来源：http://dali.ppjwa.cn/Article/details/gt2qtywfgzt.html

PHP ............ 252
来源：http://dali.yueranfly.top/Article/details/gt2glrphhqd.html

JavaScript ..... 252
来源：http://dali.wangdashe.top/Article/details/gt2tjzcjulb.html

TypeScript ..... 212
来源：http://dali.hywenlv.cn/Article/details/gt2jqmtwpgo.html

Java ........... 212
来源：http://dali.tianlin.xyz/Article/details/gt2vrjncabc.html

Go ............. 212
来源：http://dali.ybcxt.top/Article/details/gt2esjbnjty.html

Ruby ........... 212
来源：http://dali.sweek.top/Article/details/gt2rcirqnmq.html

C# ............. 212
来源：http://dali.9152youxi.cn/Article/details/gt2qjmaibgi.html

C .............. 30
来源：http://dali.yueranfly.top/Article/details/gt2dndqjulm.html

C++ ............ 30
来源：http://dali.chenjidiqi.icu/Article/details/gt2yhctmcgi.html

SQL ............ 90
来源：http://dali.feifeiyinyue.top/Article/details/gt2ejebvevr.html

Bash ........... 80
来源：http://dali.yangfankeji.com/Article/details/gt2aljbnvoh.html

Kotlin ......... 15
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sypeomfd.html

Swift .......... 15
来源：http://dali.guannengcc.top/Article/details/gt2vnalqvpj.html

Lua ............ 10
来源：http://dali.vqdsnc.cn/Article/details/gt2iouolmqk.html

Perl ........... 10
来源：http://dali.c1oappe.top/Article/details/gt2pdcfbbmg.html

Scala .......... 10
来源：http://dali.zhixingplan.top/Article/details/gt2rcbneglc.html

------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gt2hjrplnjv.html

合计 ........... 2106 条
来源：http://dali.mhx1999.top/Article/details/gt2nukwmqbi.html

按章节统计：
来源：http://dali.birdmap.top/Article/details/gt2uipryzxq.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.sufxvd.cn/Article/details/gt2fzrvxqkw.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.tian-w.cn/Article/details/gt2jpdcazpl.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ivvv.top/Article/details/gt2bgdxfega.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hysaishi.cn/Article/details/gt2pjmplldf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hywenlv.cn/Article/details/gt2aqnihhys.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yuxming.cn/Article/details/gt2gaxybejy.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.9152youxi.cn/Article/details/gt2beouijfk.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.chenlongwang.top/Article/details/gt2budwsugv.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.xuanzx.com/Article/details/gt2xfnhoqmt.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.hfpthk.cn/Article/details/gt2doisztqp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.haohaochexian.top/Article/details/gt2ahillkfm.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.wangshuangyany.cn/Article/details/gt2wsthigji.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gt2zovbnmvb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hysaishi.cn/Article/details/gt2pfdrfafs.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jqgfzy.top/Article/details/gt2kchjzngk.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.tianlin.xyz/Article/details/gt2nbbszxuk.html

Q SQL 专题                              90
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gpnzsoyn.html

R Bash 专题                             80
来源：http://dali.quarkkingdee.top/Article/details/gt2hoqedccc.html

S C / C++ 专题                          60
来源：http://dali.quarkkingdee.top/Article/details/gt2srvbllyl.html

T 其他语言补充                          60
来源：http://dali.gaohongyu789.top/Article/details/gt2gskgdbza.html

U 高频实用片段                         120
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ucjrlahj.html

------------------------------------
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nrrltovh.html

合计                                  2106 条
来源：http://dali.redwolf501.top/Article/details/gt2vokjhyyu.html

--------------------------------------------------------------------------------
来源：http://dali.chenzaomai.com/Article/details/gt2lacjkkwr.html

使用提醒
来源：http://dali.yvedp.cn/Article/details/gt2mbafwilo.html

--------------------------------------------------------------------------------
来源：http://dali.zhengqikj.top/Article/details/gt2cfhaajjq.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jqgfzy.top/Article/details/gt2damxphvg.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hnxiangtu.top/Article/details/gt2prgtdung.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.chenzaomai.com/Article/details/gt2gdvsqfcu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.ydzc1.top/Article/details/gt2ejjrtujx.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.guowangkeji.top/Article/details/gt2mewkpoph.html

—— 文件结束 ——
来源：http://dali.shanyushiyangtech.top/Article/details/gt2srhwrddr.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2ifewyfgs.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bqumhvxq.html

Common Programming Examples Cheat Book
来源：http://dali.c1oappe.top/Article/details/gt2nzclgfqk.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2djedkjov.html

【收录内容】
来源：http://dali.shangyingyoupin.top/Article/details/gt2vwwdopse.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.cheryme.top/Article/details/gt2vsqbrvqw.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yvedp.cn/Article/details/gt2eckuyktl.html

SQL · Bash · C · C++
来源：http://dali.tanke756.top/Article/details/gt2idgtrmsk.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.ivvv.top/Article/details/gt2fiuaggsw.html

【使用说明】
来源：http://dali.guannengcc.top/Article/details/gt2ojqsvqvw.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.havefunace.top/Article/details/gt2zcwtagyh.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.cheryme.top/Article/details/gt2kpawwqqb.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.chenzaomai.com/Article/details/gt2cjwaqrzq.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.gogol.net.cn/Article/details/gt2vgtzmnlg.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.gogol.net.cn/Article/details/gt2hxlkmqpi.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.kuanghao11.cn/Article/details/gt2rhkgmoyb.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.ydzc1.top/Article/details/gt2depbyxki.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jlsjyb.cn/Article/details/gt2lnwhztzj.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhiwuduotai.top/Article/details/gt2ihvxshli.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.feifeiyinyue.top/Article/details/gt2zbmdydhq.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.nanxinkj.top/Article/details/gt2xadumiac.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.gotoacloud.top/Article/details/gt2hjesyqii.html

【文件统计】
来源：http://dali.ivvv.top/Article/details/gt2bbaxcdyw.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jyoumei.cn/Article/details/gt2tjrnlzza.html

--------------------------------------------------------------------------------
来源：http://dali.cheryme.top/Article/details/gt2pujrwzmp.html

目  录
来源：http://dali.ivvv.top/Article/details/gt2vprvrntl.html

--------------------------------------------------------------------------------
来源：http://dali.fengsongda.top/Article/details/gt2ygqixctp.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.cdnleiting.top/Article/details/gt2gagogrqt.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fcbqhouz.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.cheryme.top/Article/details/gt2uwhiugkr.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xylfe.cn/Article/details/gt2wvgqazyv.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zdqjudy.top/Article/details/gt2zwwhowcq.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.fengsongda.top/Article/details/gt2kpexbcwu.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.birdmap.top/Article/details/gt2whazgmmu.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.ehwqpu.com/Article/details/gt2etzkyvrd.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.iojbl.cn/Article/details/gt2pgwtgphy.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.dianchejie.cn/Article/details/gt2ecogmggs.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhixingplan.top/Article/details/gt2mdgdmtwf.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gt2phepafpm.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.daxiang520.top/Article/details/gt2wfxqvtuz.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.gotoacloud.top/Article/details/gt2cfsqcxhz.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.feifeiyinyue.top/Article/details/gt2ihrazhcj.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aegvuivf.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.havefunace.top/Article/details/gt2bmwyjojm.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.mhx1999.top/Article/details/gt2lkcydpyt.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.tian-w.cn/Article/details/gt2urdzgrlf.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.bjfxy.top/Article/details/gt2szqbimve.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2zteoydfw.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2njnhacki.html

A. 基础语法与类型
来源：http://dali.chenzaomai.com/Article/details/gt2zwelmpsa.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2txxuyqxb.html

[A01] Hello World
来源：http://dali.birdmap.top/Article/details/gt2dwycqwna.html

Py:   print("Hello, World!")
来源：http://dali.cashguo.top/Article/details/gt2fcekmksn.html

PHP:  echo "Hello, World!";
来源：http://dali.smart0.xyz/Article/details/gt2xzcosdrd.html

JS:   console.log("Hello, World!");
来源：http://dali.shzxlz.cn/Article/details/gt2kpwhzamr.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kogtzrxr.html

Java: System.out.println("Hello, World!");
来源：http://dali.tianlin.xyz/Article/details/gt2tiwgdwrg.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.bjfxy.top/Article/details/gt2mmxsltfm.html

Ruby: puts "Hello, World!"
来源：http://dali.snrcjt.cn/Article/details/gt2cgzfqvja.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hammf.cn/Article/details/gt2sxsnxajr.html

[A02] 变量声明与赋值
来源：http://dali.wangshuangyany.cn/Article/details/gt2qkvpmrfd.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yj202588.top/Article/details/gt2kvxthwwi.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.wangshuangyany.cn/Article/details/gt2lpcabcyj.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.smart0.xyz/Article/details/gt2maghgrjg.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hnxiangtu.top/Article/details/gt2orvoxxfb.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.wangdashe.top/Article/details/gt2qcnfzioq.html

Go:   name := "Alex"; age := 20
来源：http://dali.guowangkeji.top/Article/details/gt2bcovwusq.html

Ruby: name = "Alex"; age = 20
来源：http://dali.tanke756.top/Article/details/gt2opdukego.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.shangyingyoupin.top/Article/details/gt2hiprtupx.html

[A03] 常量定义
来源：http://dali.jianghu66.top/Article/details/gt2lfvlthct.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yvedp.cn/Article/details/gt2ozhenejn.html

PHP:  const PI = 3.14159;
来源：http://dali.wangdashe.top/Article/details/gt2virvimxi.html

JS:   const PI = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gt2hssztevt.html

TS:   const PI: number = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gt2vpiwmpug.html

Java: static final double PI = 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wgykzqzo.html

Go:   const PI = 3.14159
来源：http://dali.wangshuangyany.cn/Article/details/gt2lmhuidke.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvebflz.html

C#:   const double PI = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gt2erxcwvxs.html

[A04] 判断变量类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sjizajha.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yueranfly.top/Article/details/gt2alyjtwrd.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wwrnjbqs.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yuanzhike.top/Article/details/gt2roqoxvws.html

TS:   typeof x; x instanceof Date
来源：http://dali.vqdsnc.cn/Article/details/gt2lgzibgec.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.birdmap.top/Article/details/gt2faiptkdn.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.quarkkingdee.top/Article/details/gt2nrowenof.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yvedp.cn/Article/details/gt2shwcnofz.html

C#:   x.GetType().Name; x is int
来源：http://dali.jqgfzy.top/Article/details/gt2urewapjc.html

[A05] 整数除法与取模
来源：http://dali.chenlongwang.top/Article/details/gt2prcvfcok.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.meibo888.top/Article/details/gt2ehsdjzpf.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ywwkkphv.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.guannengcc.top/Article/details/gt2oevaqufl.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ppjwa.cn/Article/details/gt2xzaseita.html

Java: 7 / 2; 7 % 2
来源：http://dali.vqdsnc.cn/Article/details/gt2yiimxaxp.html

Go:   7 / 2; 7 % 2
来源：http://dali.smart0.xyz/Article/details/gt2pgqkhlmz.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.sweek.top/Article/details/gt2ajxgovyv.html

C#:   7 / 2; 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gt2jybfoplu.html

[A06] 字符串转数字
来源：http://dali.xylfe.cn/Article/details/gt2ncylcjpx.html

Py:   int("42"); float("3.14")
来源：http://dali.chenjidiqi.icu/Article/details/gt2qmbcxkao.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.hammf.cn/Article/details/gt2uazolsbf.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.quarkkingdee.top/Article/details/gt2lqrbcyhj.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.nanxuanxn.top/Article/details/gt2zyaoyjxy.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.tanke756.top/Article/details/gt2giclgiiu.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ithrtcbq.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yanxiufei.cn/Article/details/gt2fhrmfhzq.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.guowangkeji.top/Article/details/gt2zizxpute.html

[A07] 数字转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nhqmkhnz.html

Py:   str(42)
来源：http://dali.gogol.net.cn/Article/details/gt2nmpohwlt.html

PHP:  (string) 42; strval(42)
来源：http://dali.vqdsnc.cn/Article/details/gt2ofcyhqcm.html

JS:   String(42); (42).toString()
来源：http://dali.xylfe.cn/Article/details/gt2smczccjz.html

TS:   String(42)
来源：http://dali.jqgufenzy.top/Article/details/gt2uyzesxuv.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.andypj.xyz/Article/details/gt2mutihssf.html

Go:   strconv.Itoa(42)
来源：http://dali.daria6918.cn/Article/details/gt2ljemywpj.html

Ruby: 42.to_s
来源：http://dali.nanxinkj.top/Article/details/gt2yetiuzkv.html

C#:   42.ToString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2afzjocsm.html

[A08] 取整与四舍五入
来源：http://dali.hnxiangtu.top/Article/details/gt2xjhuseaq.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fykhtftd.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wpjolhxq.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.ydzc1.top/Article/details/gt2emiggcfh.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.xuetiantiany.cn/Article/details/gt2sdndaqqm.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.kuanghao11.cn/Article/details/gt2mjtifbdb.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.tanke756.top/Article/details/gt2sikjvvow.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jinqigfzy.top/Article/details/gt2eezoantv.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.gzhubu.top/Article/details/gt2lbypeaab.html

[A09] 绝对值与最大最小值
来源：http://dali.zhixingplan.top/Article/details/gt2cluwrbqq.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.smart0.xyz/Article/details/gt2mcgndjxj.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xuanzx.com/Article/details/gt2vkcyefrb.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.yongpay.top/Article/details/gt2cwimhedw.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.andypj.xyz/Article/details/gt2jkvcvdrv.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gt2zeoxfkwe.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.sweek.top/Article/details/gt2pbbtvofl.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.nwbrower.top/Article/details/gt2aftmpemb.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.hywenlv.cn/Article/details/gt2yrvwtuwv.html

[A10] 生成随机数
来源：http://dali.fengsongda.top/Article/details/gt2cljhzrnf.html

Py:   import random; random.randint(1, 100)
来源：http://dali.cdnleiting.top/Article/details/gt2nwmtdqot.html

PHP:  random_int(1, 100);
来源：http://dali.zhiwuduotai.top/Article/details/gt2rrkosbdz.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yonumen.top/Article/details/gt2ntkrchqn.html


<!-- 参考信息 -->