代发 wailian999

[U61] PHP：正则
来源：http://dali.cdnleiting.top/Article/details/gtmijtnell.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yuanzhike.top/Article/details/gtqzobotmt.html

[U62] PHP：日期对象
来源：http://dali.jqgufenzy.top/Article/details/gtddxdgmaj.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.pycfn.com/Article/details/gtimxcvzzl.html

[U63] PHP：文件读写
来源：http://dali.gotoacloud.top/Article/details/gtpdjbwvzp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.ppjwa.cn/Article/details/gtasujvfqf.html

[U64] PHP：目录遍历
来源：http://dali.cashguo.top/Article/details/gtlbbnimpw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhoulong.xyz/Article/details/gtxgfxkqmy.html

[U65] PHP：会话
来源：http://dali.hywenlv.cn/Article/details/gtofnmldex.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.iojbl.cn/Article/details/gtanhwbmxu.html

[U66] PHP：设置 Cookie
来源：http://dali.chenzaomai.com/Article/details/gtxcponbjw.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.birdmap.top/Article/details/gtxmtbshzm.html

[U67] PHP：处理文件上传
来源：http://dali.zdqjudy.top/Article/details/gthcyqeztm.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.ydzc1.top/Article/details/gtybvvsiza.html

[U68] PHP：PDO 连接
来源：http://dali.yanxiufei.cn/Article/details/gtixmuupfu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.sysykeji.top/Article/details/gtosuuemko.html

[U69] PHP：PDO 预处理
来源：http://dali.cqqwz.cn/Article/details/gthighqsxo.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.xuetiantiany.cn/Article/details/gtojwkhqcr.html

[U70] PHP：PDO 事务
来源：http://dali.svipenyu.cn/Article/details/gtowiztulv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.birdmap.top/Article/details/gtuuiuipqf.html

[U71] PHP：抛出异常
来源：http://dali.jqgfzy.top/Article/details/gtxcoqjzoh.html

throw new RuntimeException("失败", 500);
来源：http://dali.ehwqpu.com/Article/details/gtfqilordf.html

[U72] PHP：写错误日志
来源：http://dali.sweek.top/Article/details/gtrvuftkpx.html

error_log("失败: " . $e->getMessage());
来源：http://dali.nwbrower.top/Article/details/gthgcslqrt.html

[U73] PHP：读取 ini 配置
来源：http://dali.fzhhl.top/Article/details/gtdeixryjb.html

parse_ini_file("config.ini", true)
来源：http://dali.hammf.cn/Article/details/gtavguqhrg.html

[U74] PHP：读取环境变量
来源：http://dali.sufxvd.cn/Article/details/gtrojdhpqn.html

getenv("APP_ENV") ?: "production"
来源：http://dali.daria6918.cn/Article/details/gtickieqde.html

[U75] PHP：依赖注入
来源：http://dali.sweek.top/Article/details/gtpadtgsub.html

composer require psr/container
来源：http://dali.sxryk.cn/Article/details/gtrfsghdpx.html

[U76] PHP：简单路由
来源：http://dali.aibaodan.cn/Article/details/gtzdwsbrdy.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.gogol.net.cn/Article/details/gtvvuxtkkt.html

[U77] PHP：模板渲染
来源：http://dali.jqgfzy.top/Article/details/gthtsykrvi.html

composer require twig/twig
来源：http://dali.hongshengwenyu.top/Article/details/gtvtuuxgif.html

[U78] PHP：单元测试
来源：http://dali.yj20258888.top/Article/details/gtzdvnvade.html

composer require --dev phpunit/phpunit
来源：http://dali.shangyingyoupin.top/Article/details/gtqxmgiaii.html

[U79] PHP：静态分析
来源：http://dali.wangdashe.top/Article/details/gtjopsjbgq.html

composer require --dev phpstan/phpstan
来源：http://dali.xinyue.icu/Article/details/gtuolgllrl.html

[U80] PHP：代码规范修复
来源：http://dali.nanxinkj.top/Article/details/gtwsyydmmm.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.nanxinkj.top/Article/details/gtautzclss.html

[U81] JS：初始化项目
来源：http://dali.jiagoushi.top/Article/details/gtnermtqap.html

npm init -y;  npm i express
来源：http://dali.nwbrower.top/Article/details/gttrzozwnc.html

[U82] JS：package.json 脚本
来源：http://dali.havefunace.top/Article/details/gtblrvhasg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jyoumei.cn/Article/details/gtrnjvohdy.html

[U83] JS：ES Module 导入导出
来源：http://dali.dianchejie.cn/Article/details/gtsptdyipx.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.tianlin.xyz/Article/details/gtuchqykuj.html

[U84] JS：CommonJS 写法
来源：http://dali.dianchejie.cn/Article/details/gtwzazljcb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.sweek.top/Article/details/gtyhxckqwh.html

[U85] JS：可选链
来源：http://dali.ywan-chungtsiang.top/Article/details/gtntswockz.html

a?.b?.c
来源：http://dali.dianchejie.cn/Article/details/gtdeumxftr.html

[U86] JS：空值合并
来源：http://dali.xuetiantiany.cn/Article/details/gtbjvuavbr.html

a ?? b
来源：http://dali.jinqigfzy.top/Article/details/gttsjljpwg.html

[U87] JS：解构默认值
来源：http://dali.pengpengdd.cyou/Article/details/gtsapvhymn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hnxiangtu.top/Article/details/gtyrwotsoz.html

[U88] JS：对象展开合并
来源：http://dali.shzxlz.cn/Article/details/gtiuljfpku.html

{ ...a, ...b }
来源：http://dali.havefunace.top/Article/details/gtlndwbkwq.html

[U89] JS：数组去重
来源：http://dali.xinyue.icu/Article/details/gthnevvlvz.html

[...new Set(arr)]
来源：http://dali.guowangkeji.top/Article/details/gtdgjtzlqq.html

[U90] JS：数字数组排序
来源：http://dali.jqgufenzy.top/Article/details/gtbpdgdijz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gtrxkjatoy.html

[U91] JS：对象键值遍历
来源：http://dali.havefunace.top/Article/details/gthicddigi.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.kuanghao11.cn/Article/details/gtojftjbnw.html

[U92] JS：深拷贝
来源：http://dali.ppjwa.cn/Article/details/gtyerwrlox.html

structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtaanmiegm.html

[U93] JS：模板字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtzbobffiz.html

`共 ${n} 条`
来源：http://dali.svipenyu.cn/Article/details/gtyvcpwagx.html

[U94] JS：箭头函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtidrldnkp.html

const double = x => x * 2;
来源：http://dali.cqqwz.cn/Article/details/gtlmlbxues.html

[U95] JS：Promise 包装
来源：http://dali.yueranfly.top/Article/details/gtjvxyxjrj.html

new Promise((resolve, reject) => {})
来源：http://dali.aibaodan.cn/Article/details/gtwicaawrl.html

[U96] JS：async/await 与异常
来源：http://dali.zhiwuduotai.top/Article/details/gtbjskvdti.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.gzhubu.top/Article/details/gtgsvmkzrn.html

[U97] JS：并发请求
来源：http://dali.hfpthk.cn/Article/details/gtkeuwbeoc.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shzxlz.cn/Article/details/gtekzjycyj.html

[U98] JS：fetch 带 JSON
来源：http://dali.nanxinkj.top/Article/details/gtxsnuafvp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.fengsongda.top/Article/details/gtuzsuvgxb.html

[U99] JS：事件监听
来源：http://dali.meibo888.top/Article/details/gtrowftazg.html

el.addEventListener("click", e => {})
来源：http://dali.jyoumei.cn/Article/details/gteuzdgncg.html

[U100] JS：DOM 查询
来源：http://dali.jianghu66.top/Article/details/gtdruomhka.html

document.querySelector(".item")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdgzfzxee.html

[U101] JS：classList 操作
来源：http://dali.yueranfly.top/Article/details/gtnogwltto.html

el.classList.toggle("active")
来源：http://dali.zhoulong.xyz/Article/details/gtgxmahrgj.html

[U102] JS：本地存储
来源：http://dali.gzhubu.top/Article/details/gtewniplro.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.sufxvd.cn/Article/details/gtrllcixcx.html

[U103] JS：定时器
来源：http://dali.ivvv.top/Article/details/gtfpclepip.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.meibo888.top/Article/details/gtmkvxmrbd.html

[U104] JS：防抖
来源：http://dali.yanxiufei.cn/Article/details/gthyrqzbxv.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cdnleiting.top/Article/details/gtebcbkhaa.html

[U105] JS：节流
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqbdxzopn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.kuanghao11.cn/Article/details/gtuyyuumtl.html

[U106] JS：日期格式化
来源：http://dali.zhiwuduotai.top/Article/details/gtjvejbraj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.pengpengdd.cyou/Article/details/gtycibcfem.html

[U107] JS：数字千分位
来源：http://dali.gotoacloud.top/Article/details/gtzoldlech.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.gaohongyu789.top/Article/details/gtnoujykwo.html

[U108] JS：随机整数
来源：http://dali.ybcxt.top/Article/details/gtafrtvmis.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.chenlongwang.top/Article/details/gtdbswwgtm.html

[U109] JS：数组分组
来源：http://dali.cheryme.top/Article/details/gtqfumhtzb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.dianchejie.cn/Article/details/gtvueecgbz.html

[U110] JS：数组分块
来源：http://dali.xuanzx.com/Article/details/gtjddklwtl.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.nanxuanxn.top/Article/details/gttwizskyx.html

[U111] JS：对象转 Map
来源：http://dali.jyoumei.cn/Article/details/gtwsjwdzng.html

new Map(Object.entries(obj))
来源：http://dali.kuanghao11.cn/Article/details/gtxzmfwcyt.html

[U112] JS：字符串补位
来源：http://dali.sxryk.cn/Article/details/gtjdhnxiks.html

"7".padStart(3, "0")
来源：http://dali.daria6918.cn/Article/details/gtaycstelh.html

[U113] JS：正则替换全部
来源：http://dali.birdmap.top/Article/details/gtjxvpqvje.html

s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtgcqfegni.html

[U114] JS：JSON 深比较
来源：http://dali.yueranfly.top/Article/details/gtsjdbnhwr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yangfankeji.com/Article/details/gtsoyezjap.html

[U115] JS：生成 UUID
来源：http://dali.yuxming.cn/Article/details/gthnkbwlwl.html

crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gtdyjwfdga.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.andypj.xyz/Article/details/gtbcjdzosy.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yangfankeji.com/Article/details/gtabzucuzp.html

[U117] JS：单元测试
来源：http://dali.gaohongyu789.top/Article/details/gtgylysivg.html

npm i -D vitest;  npx vitest
来源：http://dali.yj20258888.top/Article/details/gtijqseqem.html

[U118] JS：开发服务器
来源：http://dali.ybcxt.top/Article/details/gtxsysupsj.html

npm i -D vite;  npx vite
来源：http://dali.dashuyun.cn/Article/details/gtalqhvhqq.html

[U119] JS：生产构建
来源：http://dali.pycfn.com/Article/details/gtksmjjfcs.html

npx vite build
来源：http://dali.shuidangran.top/Article/details/gtcrayqdxe.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.daria6918.cn/Article/details/gthdtsgldr.html

import.meta.env.VITE_API_URL
来源：http://dali.hnqzz.top/Article/details/gtjlyqqcxd.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtnjcspods.html

统计汇总
来源：http://dali.jinqigufen.top/Article/details/gtyyyvsiir.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtwwtuxkqx.html

按语言统计（条）：
来源：http://dali.zdqjudy.top/Article/details/gtevpnctdb.html

Python ......... 252
来源：http://dali.tianlin.xyz/Article/details/gtvwhljcgl.html

PHP ............ 252
来源：http://dali.daria6918.cn/Article/details/gtltenvvai.html

JavaScript ..... 252
来源：http://dali.quarkkingdee.top/Article/details/gtohenfpbe.html

TypeScript ..... 212
来源：http://dali.316326.xyz/Article/details/gtqdrpqkci.html

Java ........... 212
来源：http://dali.jianghu66.top/Article/details/gtebsavvds.html

Go ............. 212
来源：http://dali.c1oappe.top/Article/details/gtqmtuccqy.html

Ruby ........... 212
来源：http://dali.gzhubu.top/Article/details/gtitlzvbyu.html

C# ............. 212
来源：http://dali.ppjwa.cn/Article/details/gtxrgtierw.html

C .............. 30
来源：http://dali.daria6918.cn/Article/details/gtqqhadhtc.html

C++ ............ 30
来源：http://dali.shuidangran.top/Article/details/gtvsvldyco.html

SQL ............ 90
来源：http://dali.kuanghao11.cn/Article/details/gtifuasony.html

Bash ........... 80
来源：http://dali.pengpengdd.cyou/Article/details/gtdunxcmbo.html

Kotlin ......... 15
来源：http://dali.jinqigufen.top/Article/details/gthzgcpxav.html

Swift .......... 15
来源：http://dali.shuidangran.top/Article/details/gtjmhjjtfa.html

Lua ............ 10
来源：http://dali.sufxvd.cn/Article/details/gtuotbegij.html

Perl ........... 10
来源：http://dali.yonumen.top/Article/details/gtbikshvnj.html

Scala .......... 10
来源：http://dali.xylfe.cn/Article/details/gtxoablskr.html

------------------------------------
来源：http://dali.kuanghao11.cn/Article/details/gttqcvtoxi.html

合计 ........... 2106 条
来源：http://dali.gogol.net.cn/Article/details/gthlydrref.html

按章节统计：
来源：http://dali.feifeiyinyue.top/Article/details/gtspquinpq.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yangfankeji.com/Article/details/gtoqyfyduz.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.cdnleiting.top/Article/details/gtsxeradbt.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yongpay.top/Article/details/gtydgbvyxh.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jyoumei.cn/Article/details/gteytxwuhe.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zycfv.cn/Article/details/gtvwcwxand.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.0kj1m.cn/Article/details/gtlrdbekzy.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.aibaodan.cn/Article/details/gtzzhgfeot.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zdqjudy.top/Article/details/gtojsehpbm.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.gotoacloud.top/Article/details/gtqywyeghg.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xziqi.cn/Article/details/gtmkcwcapc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gtpwfnbumd.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jqgfzy.top/Article/details/gtlpjdtyqu.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hammf.cn/Article/details/gtkypslvex.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.shzxlz.cn/Article/details/gtsneqgaqc.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.c1oappe.top/Article/details/gtcpiswnbg.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhixingplan.top/Article/details/gtowkfjacd.html

Q SQL 专题                              90
来源：http://dali.shzxlz.cn/Article/details/gtuizhzamp.html

R Bash 专题                             80
来源：http://dali.haohaochexian.top/Article/details/gtolzmpnyw.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gteulpnqes.html

T 其他语言补充                          60
来源：http://dali.xuetiantiany.cn/Article/details/gtwkscskkg.html

U 高频实用片段                         120
来源：http://dali.hfpthk.cn/Article/details/gtvyfjtwya.html

------------------------------------
来源：http://dali.jiagoushi.top/Article/details/gtihitccpc.html

合计                                  2106 条
来源：http://dali.daria6918.cn/Article/details/gtckveviwh.html

--------------------------------------------------------------------------------
来源：http://dali.xylfe.cn/Article/details/gtnwkxkeek.html

使用提醒
来源：http://dali.nanxuanxn.top/Article/details/gtorllorhy.html

--------------------------------------------------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gtquqzjgun.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.xylfe.cn/Article/details/gtbwpjjilq.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hnqzz.top/Article/details/gthttujnaz.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.c1oappe.top/Article/details/gtvghwjqpk.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.aizwys.cn/Article/details/gttmwowuzn.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.pycfn.com/Article/details/gtvgewfnkg.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gtnujsrlan.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtrpyxtaju.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.hywenlv.cn/Article/details/gtiwmfzmxs.html

Common Programming Examples Cheat Book
来源：http://dali.chenjidiqi.icu/Article/details/gtbdswkenb.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtxtgnqius.html

【收录内容】
来源：http://dali.zhaomingkeji.xyz/Article/details/gtckqkawzb.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhengqikj.top/Article/details/gtjqoxrkit.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.tianlin.xyz/Article/details/gtxwjvakpy.html

SQL · Bash · C · C++
来源：http://dali.zhiwuduotai.top/Article/details/gtpjlxkskk.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.xylfe.cn/Article/details/gtsaxvgqsq.html

【使用说明】
来源：http://dali.yangfankeji.com/Article/details/gtmrjorqrk.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhengqikj.top/Article/details/gtbovpizuw.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.nanxinkj.top/Article/details/gtgqadvrfc.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.gogol.net.cn/Article/details/gtxbmfpoxt.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttuzlaqjs.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.gaohongyu789.top/Article/details/gtgofokpbw.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.gzhubu.top/Article/details/gttmoidppd.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jqgfzy.top/Article/details/gthhchimnq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.chenlongwang.top/Article/details/gtfbkrvccz.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.fengsongda.top/Article/details/gtquiypqbw.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.tianlin.xyz/Article/details/gtsxlotcok.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.vqdsnc.cn/Article/details/gtuywdozoq.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jqgufenzy.top/Article/details/gtyyttueuw.html

【文件统计】
来源：http://dali.zhongyouzk.top/Article/details/gtdmjlvion.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.vqdsnc.cn/Article/details/gtexvpwnjk.html

--------------------------------------------------------------------------------
来源：http://dali.jyoumei.cn/Article/details/gtdlgcapqr.html

目  录
来源：http://dali.jinghuilouyu.cn/Article/details/gtxybgdwzw.html

--------------------------------------------------------------------------------
来源：http://dali.zhengqikj.top/Article/details/gttqrsbpcm.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.svipenyu.cn/Article/details/gtnlbcfagv.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jqgfzy.top/Article/details/gtxdgsprra.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtbtcqkmwb.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.316326.xyz/Article/details/gtrojwbsaf.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.svipenyu.cn/Article/details/gtwzbdmjcx.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yuanzhike.top/Article/details/gtwzuufdku.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.mhx1999.top/Article/details/gthrxbayah.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yangfankeji.com/Article/details/gthpunpoqk.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hnxiangtu.top/Article/details/gthzskgaia.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.hfpthk.cn/Article/details/gtxbjkzpnu.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.kuanghao11.cn/Article/details/gtszavaass.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.cqqwz.cn/Article/details/gtmmwhviva.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.daria6918.cn/Article/details/gteaexuaed.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.gotoacloud.top/Article/details/gtfvspbjih.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.wangdashe.top/Article/details/gtkhscjtzp.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiumpkeyv.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtriiqagsf.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.nanxuanxn.top/Article/details/gtfndoftgo.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.havefunace.top/Article/details/gtjofdvpac.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jqgufenzy.top/Article/details/gtagmtuxgk.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.sysykeji.top/Article/details/gttezyvice.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtvmrkbgbi.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gtbwrgneis.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtayogvdkk.html

[A01] Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtvwigazyi.html

Py:   print("Hello, World!")
来源：http://dali.zhongyouzk.top/Article/details/gtlqtwrrox.html

PHP:  echo "Hello, World!";
来源：http://dali.smart0.xyz/Article/details/gtuyjyoayu.html

JS:   console.log("Hello, World!");
来源：http://dali.fzhhl.top/Article/details/gtrnfbsqbd.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.birdmap.top/Article/details/gtbsqocyfd.html

Java: System.out.println("Hello, World!");
来源：http://dali.hnxiangtu.top/Article/details/gtgfjbvymk.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.guowangkeji.top/Article/details/gtnhtldmzy.html

Ruby: puts "Hello, World!"
来源：http://dali.daxiang520.top/Article/details/gtcmejkhsj.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jqgfzy.top/Article/details/gtdbjjococ.html

[A02] 变量声明与赋值
来源：http://dali.chenlongwang.top/Article/details/gtilzfvctx.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yj20258888.top/Article/details/gthdiubaec.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.c1oappe.top/Article/details/gtcgounior.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.hnqzz.top/Article/details/gtcegrpwlq.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jianghu66.top/Article/details/gtxartedyf.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.aizwys.cn/Article/details/gtwmkczmmp.html

Go:   name := "Alex"; age := 20
来源：http://dali.yueranfly.top/Article/details/gtrikacuki.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hnxiangtu.top/Article/details/gtjzcjeclh.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.ydzc1.top/Article/details/gtnqzizehs.html

[A03] 常量定义
来源：http://dali.hnqzz.top/Article/details/gtitrfhlpr.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.shanyushiyangtech.top/Article/details/gtsriouezt.html

PHP:  const PI = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gtvescicvr.html

JS:   const PI = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gtfebcxkjg.html

TS:   const PI: number = 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gtypuccytg.html

Java: static final double PI = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtmutqiwfo.html

Go:   const PI = 3.14159
来源：http://dali.jianghu66.top/Article/details/gtsjddtigd.html

Ruby: PI = 3.14159
来源：http://dali.haohaochexian.top/Article/details/gtlcefzhkm.html

C#:   const double PI = 3.14159;
来源：http://dali.ivvv.top/Article/details/gtecxwsibv.html

[A04] 判断变量类型
来源：http://dali.feifeiyinyue.top/Article/details/gtsphqxudk.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.316326.xyz/Article/details/gtpajmeizy.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.316326.xyz/Article/details/gtrvrwjuto.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.smart0.xyz/Article/details/gtrbnfxtgt.html

TS:   typeof x; x instanceof Date
来源：http://dali.yonumen.top/Article/details/gtlphcdnfk.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.hnqzz.top/Article/details/gtehknkkdk.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.nanxinkj.top/Article/details/gtablkzogq.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.chenlongwang.top/Article/details/gtgrfrilng.html

C#:   x.GetType().Name; x is int
来源：http://dali.c1oappe.top/Article/details/gtqgasxhbh.html

[A05] 整数除法与取模
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtremekfpu.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.gzhubu.top/Article/details/gtnxwgmhtx.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhengqikj.top/Article/details/gtirhbxwaj.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.c1oappe.top/Article/details/gtzewkfekj.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ybcxt.top/Article/details/gttoxvxauc.html

Java: 7 / 2; 7 % 2
来源：http://dali.yongpay.top/Article/details/gteyxsonbz.html

Go:   7 / 2; 7 % 2
来源：http://dali.xuanzx.com/Article/details/gtrpdwqmnx.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.nwbrower.top/Article/details/gtgqnuflmw.html

C#:   7 / 2; 7 % 2
来源：http://dali.hnxiangtu.top/Article/details/gtjsrclrwi.html

[A06] 字符串转数字
来源：http://dali.guowangkeji.top/Article/details/gtcdyikfos.html

Py:   int("42"); float("3.14")
来源：http://dali.hnxiangtu.top/Article/details/gtpjaqcqgy.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.hfpthk.cn/Article/details/gtljyfxrix.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpwqotjmp.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.ybcxt.top/Article/details/gtmwmarynn.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zdqjudy.top/Article/details/gtxmwwveln.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.ehwqpu.com/Article/details/gthpwgjjvn.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.9152youxi.cn/Article/details/gtcdpppwnk.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.daxiang520.top/Article/details/gtolqipylf.html

[A07] 数字转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrhgelpt.html

Py:   str(42)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcgnursoa.html

PHP:  (string) 42; strval(42)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwshtpgtg.html

JS:   String(42); (42).toString()
来源：http://dali.kuanghao11.cn/Article/details/gtrbxoyhsy.html

TS:   String(42)
来源：http://dali.guannengcc.top/Article/details/gtkynkhymw.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.xinyue.icu/Article/details/gtmxgxuzim.html

Go:   strconv.Itoa(42)
来源：http://dali.yangfankeji.com/Article/details/gtmtainohk.html

Ruby: 42.to_s
来源：http://dali.jiagoushi.top/Article/details/gtbnltuekt.html

C#:   42.ToString()
来源：http://dali.yj20258.top/Article/details/gtedsqvvpu.html

[A08] 取整与四舍五入
来源：http://dali.sufxvd.cn/Article/details/gteblezmpz.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.shangyingyoupin.top/Article/details/gtkdwwweyy.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yanxiufei.cn/Article/details/gtbfwgymur.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jyoumei.cn/Article/details/gtjzimvrio.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yuanzhike.top/Article/details/gtbqkcffrd.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yj202588.top/Article/details/gtebceeccv.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.svipenyu.cn/Article/details/gtkbuvkdop.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jinqigfzy.top/Article/details/gtuptpmwjb.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.shzxlz.cn/Article/details/gtgfrqhhta.html

[A09] 绝对值与最大最小值
来源：http://dali.yongpay.top/Article/details/gtmyswrvoq.html


<!-- 参考信息 -->