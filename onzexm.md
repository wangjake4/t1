代发 wailian999

[U65] PHP：会话
来源：http://dali.cdnleiting.top/Article/details/gtsiuvhnhr.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.shuidangran.top/Article/details/gtistylfmg.html

[U66] PHP：设置 Cookie
来源：http://dali.haohaochexian.top/Article/details/gtiofzpwtp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.hnxiangtu.top/Article/details/gtbltsuusu.html

[U67] PHP：处理文件上传
来源：http://dali.daria6918.cn/Article/details/gtqugxhlzh.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jqgufenzy.top/Article/details/gtlbzowjzm.html

[U68] PHP：PDO 连接
来源：http://dali.tanke756.top/Article/details/gtvytjrxiv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.daria6918.cn/Article/details/gtxylxgwah.html

[U69] PHP：PDO 预处理
来源：http://dali.dianchejie.cn/Article/details/gtdkxpqcpt.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ehwqpu.com/Article/details/gtmvedrcqv.html

[U70] PHP：PDO 事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzriuhffw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.sxryk.cn/Article/details/gteuxnpkjc.html

[U71] PHP：抛出异常
来源：http://dali.shzxlz.cn/Article/details/gtkvtiwkan.html

throw new RuntimeException("失败", 500);
来源：http://dali.chenzaomai.com/Article/details/gtsuyfgjmy.html

[U72] PHP：写错误日志
来源：http://dali.ehwqpu.com/Article/details/gtanmmuxoy.html

error_log("失败: " . $e->getMessage());
来源：http://dali.andypj.xyz/Article/details/gtjrcdmhst.html

[U73] PHP：读取 ini 配置
来源：http://dali.wangshuangyany.cn/Article/details/gtabtsplnd.html

parse_ini_file("config.ini", true)
来源：http://dali.c1oappe.top/Article/details/gtuovnqmbc.html

[U74] PHP：读取环境变量
来源：http://dali.fengsongda.top/Article/details/gtxjfonyyn.html

getenv("APP_ENV") ?: "production"
来源：http://dali.hnxiangtu.top/Article/details/gttjlvkvxc.html

[U75] PHP：依赖注入
来源：http://dali.guowangkeji.top/Article/details/gtxldjpjla.html

composer require psr/container
来源：http://dali.cdnleiting.top/Article/details/gtrugpwrba.html

[U76] PHP：简单路由
来源：http://dali.zdqjudy.top/Article/details/gtphlveszs.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.andypj.xyz/Article/details/gtvnwolpkb.html

[U77] PHP：模板渲染
来源：http://dali.sweek.top/Article/details/gtmbpvjojl.html

composer require twig/twig
来源：http://dali.jyoumei.cn/Article/details/gtcebmagfe.html

[U78] PHP：单元测试
来源：http://dali.quarkkingdee.top/Article/details/gtucdpqzfj.html

composer require --dev phpunit/phpunit
来源：http://dali.yangfankeji.com/Article/details/gtbjbzxdxn.html

[U79] PHP：静态分析
来源：http://dali.shuidangran.top/Article/details/gtkmhucjrr.html

composer require --dev phpstan/phpstan
来源：http://dali.ivvv.top/Article/details/gtegbnqfvf.html

[U80] PHP：代码规范修复
来源：http://dali.zhengqikj.top/Article/details/gtrgkkzblr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhoulong.xyz/Article/details/gtgwartnms.html

[U81] JS：初始化项目
来源：http://dali.guannengcc.top/Article/details/gthzdqwava.html

npm init -y;  npm i express
来源：http://dali.jqgfzy.top/Article/details/gtlhbrvadb.html

[U82] JS：package.json 脚本
来源：http://dali.cdnleiting.top/Article/details/gtgkskmrjx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.svipenyu.cn/Article/details/gtapzxhbep.html

[U83] JS：ES Module 导入导出
来源：http://dali.yvedp.cn/Article/details/gtqosjuils.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hammf.cn/Article/details/gtachwsyjr.html

[U84] JS：CommonJS 写法
来源：http://dali.hnxiangtu.top/Article/details/gthrjkgyvo.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.iojbl.cn/Article/details/gtrihxacay.html

[U85] JS：可选链
来源：http://dali.jyoumei.cn/Article/details/gtarrksgjh.html

a?.b?.c
来源：http://dali.zhiwuduotai.top/Article/details/gtjucyfvue.html

[U86] JS：空值合并
来源：http://dali.iojbl.cn/Article/details/gtvmssxcjo.html

a ?? b
来源：http://dali.hywenlv.cn/Article/details/gtwlllmtjh.html

[U87] JS：解构默认值
来源：http://dali.havefunace.top/Article/details/gtbzknkdey.html

const { a = 1, b = 2 } = obj;
来源：http://dali.shzxlz.cn/Article/details/gtwmxrgjfk.html

[U88] JS：对象展开合并
来源：http://dali.chenzaomai.com/Article/details/gtvpszvwsg.html

{ ...a, ...b }
来源：http://dali.hnqzz.top/Article/details/gtiwexdovy.html

[U89] JS：数组去重
来源：http://dali.iojbl.cn/Article/details/gtwaukwhaw.html

[...new Set(arr)]
来源：http://dali.fengsongda.top/Article/details/gtrsugrhtw.html

[U90] JS：数字数组排序
来源：http://dali.hysaishi.cn/Article/details/gtmfhkwrce.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtipyxbnjy.html

[U91] JS：对象键值遍历
来源：http://dali.daxiang520.top/Article/details/gtjsiojjtg.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.redwolf501.top/Article/details/gtimdcjrrd.html

[U92] JS：深拷贝
来源：http://dali.jinqigufen.top/Article/details/gtpleaojpr.html

structuredClone(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtnnaxidvv.html

[U93] JS：模板字符串
来源：http://dali.havefunace.top/Article/details/gtmltberys.html

`共 ${n} 条`
来源：http://dali.yuxming.cn/Article/details/gtkhaehfgt.html

[U94] JS：箭头函数
来源：http://dali.tanke756.top/Article/details/gtvoscfwoz.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gtgioayxsj.html

[U95] JS：Promise 包装
来源：http://dali.aizwys.cn/Article/details/gtfjecsfct.html

new Promise((resolve, reject) => {})
来源：http://dali.andypj.xyz/Article/details/gtoinwdrhy.html

[U96] JS：async/await 与异常
来源：http://dali.zdqjudy.top/Article/details/gttsicaqzt.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gtjwzjctzf.html

[U97] JS：并发请求
来源：http://dali.shangyingyoupin.top/Article/details/gtmwisvdpu.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gtgpvqktxv.html

[U98] JS：fetch 带 JSON
来源：http://dali.wangdashe.top/Article/details/gtbpyjdnva.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xuanzx.com/Article/details/gtmkfsdxuo.html

[U99] JS：事件监听
来源：http://dali.quarkkingdee.top/Article/details/gtapgyywbo.html

el.addEventListener("click", e => {})
来源：http://dali.jiagoushi.top/Article/details/gtkntgrhqz.html

[U100] JS：DOM 查询
来源：http://dali.xylfe.cn/Article/details/gtmkwhhiej.html

document.querySelector(".item")
来源：http://dali.yj20258.top/Article/details/gtfropfulx.html

[U101] JS：classList 操作
来源：http://dali.jinqigufen.top/Article/details/gtqwzulldv.html

el.classList.toggle("active")
来源：http://dali.yj20258888.top/Article/details/gtkhiguozd.html

[U102] JS：本地存储
来源：http://dali.ehwqpu.com/Article/details/gthzvxlegw.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jqgfzy.top/Article/details/gtkmhitntt.html

[U103] JS：定时器
来源：http://dali.gogol.net.cn/Article/details/gtsgyqtzsi.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jinghuilouyu.cn/Article/details/gtexzjxxxh.html

[U104] JS：防抖
来源：http://dali.shuidangran.top/Article/details/gtizmqsscc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gtskuvbous.html

[U105] JS：节流
来源：http://dali.kuanghao11.cn/Article/details/gtomddmoop.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhoulong.xyz/Article/details/gterjmwsgt.html

[U106] JS：日期格式化
来源：http://dali.9152youxi.cn/Article/details/gtxvgmebrk.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.gaohongyu789.top/Article/details/gtskfpbqjj.html

[U107] JS：数字千分位
来源：http://dali.wangdashe.top/Article/details/gtgyhprhuc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jlsjyb.cn/Article/details/gtbvtlagiu.html

[U108] JS：随机整数
来源：http://dali.vqdsnc.cn/Article/details/gtbviznxmj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jinghuilouyu.cn/Article/details/gtizstancd.html

[U109] JS：数组分组
来源：http://dali.tianlin.xyz/Article/details/gtnnxyibmo.html

Object.groupBy(arr, x => x.type)
来源：http://dali.pycfn.com/Article/details/gtmzasyifi.html

[U110] JS：数组分块
来源：http://dali.kuanghao11.cn/Article/details/gtupobrkdw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shzxlz.cn/Article/details/gtyexlhsoj.html

[U111] JS：对象转 Map
来源：http://dali.nanxinkj.top/Article/details/gtvzvdgthp.html

new Map(Object.entries(obj))
来源：http://dali.redwolf501.top/Article/details/gttqacdcga.html

[U112] JS：字符串补位
来源：http://dali.yueranfly.top/Article/details/gtnhtfgevu.html

"7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gturxdrrau.html

[U113] JS：正则替换全部
来源：http://dali.chenjidiqi.icu/Article/details/gtqoqxtifi.html

s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gtryjshgdi.html

[U114] JS：JSON 深比较
来源：http://dali.hnqzz.top/Article/details/gtamivdwbq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cashguo.top/Article/details/gtecpaljyb.html

[U115] JS：生成 UUID
来源：http://dali.nwbrower.top/Article/details/gtxqtzpgxf.html

crypto.randomUUID()
来源：http://dali.bjfxy.top/Article/details/gtfkvwzvoj.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhongyouzk.top/Article/details/gtqternaee.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yueranfly.top/Article/details/gtxwxgicve.html

[U117] JS：单元测试
来源：http://dali.xuanzx.com/Article/details/gteqpbrxzg.html

npm i -D vitest;  npx vitest
来源：http://dali.dashuyun.cn/Article/details/gtuojkkghc.html

[U118] JS：开发服务器
来源：http://dali.gzhubu.top/Article/details/gtxaffvgvy.html

npm i -D vite;  npx vite
来源：http://dali.shzxlz.cn/Article/details/gtbuaxdkgb.html

[U119] JS：生产构建
来源：http://dali.zhongyouzk.top/Article/details/gtavmltmfm.html

npx vite build
来源：http://dali.birdmap.top/Article/details/gtzjkzpazy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yj20258.top/Article/details/gtxlttafjj.html

import.meta.env.VITE_API_URL
来源：http://dali.mhx1999.top/Article/details/gtkomjoqkf.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtyzxvkjva.html

统计汇总
来源：http://dali.jiagoushi.top/Article/details/gthcnrmpme.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtquzoxyva.html

按语言统计（条）：
来源：http://dali.wangdashe.top/Article/details/gtxqedccfd.html

Python ......... 252
来源：http://dali.cdnleiting.top/Article/details/gtxoazipcf.html

PHP ............ 252
来源：http://dali.wangdashe.top/Article/details/gtsrgkhido.html

JavaScript ..... 252
来源：http://dali.zhongyouzk.top/Article/details/gtekxpetel.html

TypeScript ..... 212
来源：http://dali.sweek.top/Article/details/gtljgmegeg.html

Java ........... 212
来源：http://dali.sxryk.cn/Article/details/gtcvvijlpy.html

Go ............. 212
来源：http://dali.sxryk.cn/Article/details/gtamwtrltr.html

Ruby ........... 212
来源：http://dali.wangdashe.top/Article/details/gtjalbxtwu.html

C# ............. 212
来源：http://dali.gaohongyu789.top/Article/details/gttddbulnr.html

C .............. 30
来源：http://dali.ywan-chungtsiang.top/Article/details/gthupihdit.html

C++ ............ 30
来源：http://dali.yonumen.top/Article/details/gtxyrzdxoe.html

SQL ............ 90
来源：http://dali.ehwqpu.com/Article/details/gtvypqzqmm.html

Bash ........... 80
来源：http://dali.jianghu66.top/Article/details/gtmdlshbpb.html

Kotlin ......... 15
来源：http://dali.wangshuangyany.cn/Article/details/gtrvrpkhjn.html

Swift .......... 15
来源：http://dali.andypj.xyz/Article/details/gtexzwnkfr.html

Lua ............ 10
来源：http://dali.ydzc1.top/Article/details/gtuvvujhax.html

Perl ........... 10
来源：http://dali.nanxuanxn.top/Article/details/gtnhvkdfac.html

Scala .......... 10
来源：http://dali.0kj1m.cn/Article/details/gtwxgrozix.html

------------------------------------
来源：http://dali.cashguo.top/Article/details/gtrmovfexy.html

合计 ........... 2106 条
来源：http://dali.9152youxi.cn/Article/details/gtsnqydueh.html

按章节统计：
来源：http://dali.yangfankeji.com/Article/details/gtsevkaktn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gtnylfcrxy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.gotoacloud.top/Article/details/gtlymuofrf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ppjwa.cn/Article/details/gtnkrhteev.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gtojxmgdww.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.shanyushiyangtech.top/Article/details/gtntrxyykg.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jqgufenzy.top/Article/details/gtbrpeswzs.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jqgufenzy.top/Article/details/gtkgwztsep.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhiwuduotai.top/Article/details/gttpsvnwok.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.dianchejie.cn/Article/details/gtccrolhlj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yanxiufei.cn/Article/details/gtawgdlvub.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.tian-w.cn/Article/details/gtzlsicojk.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ivvv.top/Article/details/gtxtcphhbj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.redwolf501.top/Article/details/gtkanqdlkl.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.vqdsnc.cn/Article/details/gtloeoeuzs.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.sweek.top/Article/details/gtwtnlztcg.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.nanxuanxn.top/Article/details/gtfujcnykn.html

Q SQL 专题                              90
来源：http://dali.yj20258888.top/Article/details/gtdfqbmooa.html

R Bash 专题                             80
来源：http://dali.jqgufenzy.top/Article/details/gtrsxjhxtf.html

S C / C++ 专题                          60
来源：http://dali.jianghu66.top/Article/details/gtlodvaiwg.html

T 其他语言补充                          60
来源：http://dali.xziqi.cn/Article/details/gtduihmrks.html

U 高频实用片段                         120
来源：http://dali.9152youxi.cn/Article/details/gtlzdzivrk.html

------------------------------------
来源：http://dali.havefunace.top/Article/details/gtzmhnyvqo.html

合计                                  2106 条
来源：http://dali.hysaishi.cn/Article/details/gtgcwccxzo.html

--------------------------------------------------------------------------------
来源：http://dali.guannengcc.top/Article/details/gtkkxpkyde.html

使用提醒
来源：http://dali.birdmap.top/Article/details/gttdxdcfah.html

--------------------------------------------------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gthyuxrude.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.meibo888.top/Article/details/gtbwtbgkyo.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.c1oappe.top/Article/details/gtgjphbcad.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yuxming.cn/Article/details/gtulahadex.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.gotoacloud.top/Article/details/gtaqacpuxy.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zycfv.cn/Article/details/gtaufqafoy.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gtzppkrlhv.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtgwrlbxbi.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.xylfe.cn/Article/details/gtearnuydb.html

Common Programming Examples Cheat Book
来源：http://dali.shangyingyoupin.top/Article/details/gtvygvknqr.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtbplxancx.html

【收录内容】
来源：http://dali.yueranfly.top/Article/details/gtkzkiedev.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.tian-w.cn/Article/details/gtlefxojgl.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.c1oappe.top/Article/details/gttritlxzh.html

SQL · Bash · C · C++
来源：http://dali.dianchejie.cn/Article/details/gthctwocqu.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.c1oappe.top/Article/details/gtmbffjqql.html

【使用说明】
来源：http://dali.pengpengdd.cyou/Article/details/gtwhwckbtv.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.nwbrower.top/Article/details/gtlfuyhztt.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.iojbl.cn/Article/details/gttxvwbumt.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhixingplan.top/Article/details/gtlrbaepxd.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.birdmap.top/Article/details/gtecsuypmp.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.tanke756.top/Article/details/gtpxubbxof.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.shuidangran.top/Article/details/gtxktpyeoi.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.wangshuangyany.cn/Article/details/gtddtvrpwh.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.cheryme.top/Article/details/gtinupxrbr.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.hnxiangtu.top/Article/details/gtjbanzrmz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.nanxuanxn.top/Article/details/gtzgtwrguu.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yangfankeji.com/Article/details/gtbhgyucyl.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhongyouzk.top/Article/details/gtqafgvvwk.html

【文件统计】
来源：http://dali.chenjidiqi.icu/Article/details/gtakywhmnd.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.snrcjt.cn/Article/details/gticshngvm.html

--------------------------------------------------------------------------------
来源：http://dali.aibaodan.cn/Article/details/gtjjnrdhcg.html

目  录
来源：http://dali.cqqwz.cn/Article/details/gtaicaniex.html

--------------------------------------------------------------------------------
来源：http://dali.hfpthk.cn/Article/details/gtfvbyywib.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jinqigufen.top/Article/details/gtgisqpowd.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.aibaodan.cn/Article/details/gtzfijhwtn.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jqgufenzy.top/Article/details/gttwphvthk.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.daxiang520.top/Article/details/gtnomujfzj.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hammf.cn/Article/details/gtludjjhrq.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yanxiufei.cn/Article/details/gtysnhloas.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.cashguo.top/Article/details/gtrrxmsjnp.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jlsjyb.cn/Article/details/gtujsjgser.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.aibaodan.cn/Article/details/gtvlzppksi.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.cucudq.cn/Article/details/gtfbqsdnxy.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyqipordf.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbzeokkd.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.tian-w.cn/Article/details/gtotxymdnj.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkjuufimj.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.nanxinkj.top/Article/details/gtmextcuwj.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jqgufenzy.top/Article/details/gtqwcparnn.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yongpay.top/Article/details/gtputpyylq.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhoulong.xyz/Article/details/gtrcnapiju.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhixingplan.top/Article/details/gtogmumceo.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.smart0.xyz/Article/details/gtmyprkunw.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtclaprxor.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtacviwlyk.html

A. 基础语法与类型
来源：http://dali.aizwys.cn/Article/details/gtfxuvcdcm.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtcziihrqt.html

[A01] Hello World
来源：http://dali.gzhubu.top/Article/details/gtbrjnuwan.html

Py:   print("Hello, World!")
来源：http://dali.fengsongda.top/Article/details/gthcmzomot.html

PHP:  echo "Hello, World!";
来源：http://dali.xinyue.icu/Article/details/gtornqcufq.html

JS:   console.log("Hello, World!");
来源：http://dali.sweek.top/Article/details/gtvjglghgf.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.snrcjt.cn/Article/details/gtspdjdetp.html

Java: System.out.println("Hello, World!");
来源：http://dali.hnqzz.top/Article/details/gtozfdicvy.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.xziqi.cn/Article/details/gtonsaufyv.html

Ruby: puts "Hello, World!"
来源：http://dali.quarkkingdee.top/Article/details/gttsgrhwes.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hywenlv.cn/Article/details/gtifeefvsn.html

[A02] 变量声明与赋值
来源：http://dali.meibo888.top/Article/details/gtbavjcufs.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.9152youxi.cn/Article/details/gtptqqhgbw.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.dashuyun.cn/Article/details/gtrxlyigdj.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhiwuduotai.top/Article/details/gtpoqxeeuu.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hnxiangtu.top/Article/details/gtwdxmpwts.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yangfankeji.com/Article/details/gtwsvkccnj.html

Go:   name := "Alex"; age := 20
来源：http://dali.zdqjudy.top/Article/details/gtyivfgouh.html

Ruby: name = "Alex"; age = 20
来源：http://dali.redwolf501.top/Article/details/gthorztiyb.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jyoumei.cn/Article/details/gtmhqzeukg.html

[A03] 常量定义
来源：http://dali.hywenlv.cn/Article/details/gtilurjqea.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hywenlv.cn/Article/details/gtirgkjlku.html

PHP:  const PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtmjlrpmpc.html

JS:   const PI = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gtyeftjmon.html

TS:   const PI: number = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gtqxqmjxeh.html

Java: static final double PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gtjiepmmfs.html

Go:   const PI = 3.14159
来源：http://dali.svipenyu.cn/Article/details/gtarulenkl.html

Ruby: PI = 3.14159
来源：http://dali.guowangkeji.top/Article/details/gtkeonfyal.html

C#:   const double PI = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gtmmrtxqne.html

[A04] 判断变量类型
来源：http://dali.zhengqikj.top/Article/details/gtejeeruxt.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.haohaochexian.top/Article/details/gtcvkfozcs.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.hnxiangtu.top/Article/details/gthykoyxnk.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.sufxvd.cn/Article/details/gthaubxlfk.html

TS:   typeof x; x instanceof Date
来源：http://dali.cqqwz.cn/Article/details/gtuuyjhlmt.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.wangshuangyany.cn/Article/details/gtuytweogf.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.havefunace.top/Article/details/gtfkbgkfvx.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xinyue.icu/Article/details/gtlnpcsybx.html

C#:   x.GetType().Name; x is int
来源：http://dali.shzxlz.cn/Article/details/gtyyssmawt.html

[A05] 整数除法与取模
来源：http://dali.jinqigfzy.top/Article/details/gtvfsxfgle.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvmpqrlvs.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.c1oappe.top/Article/details/gtxacrhkjx.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yj20258888.top/Article/details/gtvrxktmfu.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hnqzz.top/Article/details/gtopdnhema.html

Java: 7 / 2; 7 % 2
来源：http://dali.kuanghao11.cn/Article/details/gtuqnvekis.html

Go:   7 / 2; 7 % 2
来源：http://dali.shuidangran.top/Article/details/gtjbddsksx.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.xinyue.icu/Article/details/gtkcrfwdrq.html

C#:   7 / 2; 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gtyefjengj.html

[A06] 字符串转数字
来源：http://dali.chenlongwang.top/Article/details/gtmktuiopa.html

Py:   int("42"); float("3.14")
来源：http://dali.iojbl.cn/Article/details/gtdjwokuuf.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.mhx1999.top/Article/details/gtrudcsqfv.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yj202588.top/Article/details/gtaolhzsit.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.ivvv.top/Article/details/gtjxkcaxyt.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.guowangkeji.top/Article/details/gtticrmaap.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.iojbl.cn/Article/details/gtfxtabcsd.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.iojbl.cn/Article/details/gttfbzjzoo.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkzxpkhxk.html

[A07] 数字转字符串
来源：http://dali.cdnleiting.top/Article/details/gtyjfkvovd.html

Py:   str(42)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtooadzyox.html

PHP:  (string) 42; strval(42)
来源：http://dali.jqgfzy.top/Article/details/gtalgltjxg.html

JS:   String(42); (42).toString()
来源：http://dali.vqdsnc.cn/Article/details/gtjvyhdmvv.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gteifjicjr.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.quarkkingdee.top/Article/details/gtnhmecpzk.html

Go:   strconv.Itoa(42)
来源：http://dali.daxiang520.top/Article/details/gtjtkxkfqr.html

Ruby: 42.to_s
来源：http://dali.nanxinkj.top/Article/details/gtitqzqvyk.html

C#:   42.ToString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtudevxskc.html

[A08] 取整与四舍五入
来源：http://dali.xuetiantiany.cn/Article/details/gtvqxyrfsa.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.wangdashe.top/Article/details/gtarajutxa.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.sxryk.cn/Article/details/gtxvmqvkiz.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.vqdsnc.cn/Article/details/gtcguhdfdd.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.guannengcc.top/Article/details/gtfhyztmyy.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.hywenlv.cn/Article/details/gtpkjatury.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.hnqzz.top/Article/details/gtdvypwjfj.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.vqdsnc.cn/Article/details/gterqwcqyg.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbgjusmww.html

[A09] 绝对值与最大最小值
来源：http://dali.fzhhl.top/Article/details/gtbojoicly.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.sxryk.cn/Article/details/gtnlvmsxos.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ydzc1.top/Article/details/gtpvpdprcl.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.mhx1999.top/Article/details/gtextykmxl.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.shuidangran.top/Article/details/gtomgibuni.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.daxiang520.top/Article/details/gtmjomgkno.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtknatarql.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.kuanghao11.cn/Article/details/gtxblktvyi.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.smart0.xyz/Article/details/gtetweqmpi.html


<!-- 参考信息 -->