代发 wailian999

[U65] PHP：会话
来源：http://dali.jqgfzy.top/Article/details/gtuuarhcvc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gthxydvizk.html

[U66] PHP：设置 Cookie
来源：http://dali.cheryme.top/Article/details/gtlshmtuhx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.aibaodan.cn/Article/details/gtsycfnkss.html

[U67] PHP：处理文件上传
来源：http://dali.xuanzx.com/Article/details/gtrhpxidic.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.tian-w.cn/Article/details/gtoszdaply.html

[U68] PHP：PDO 连接
来源：http://dali.guannengcc.top/Article/details/gtjqujrjvg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.nanxinkj.top/Article/details/gthrmwqajy.html

[U69] PHP：PDO 预处理
来源：http://dali.chenlongwang.top/Article/details/gtpnoqodrx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ppjwa.cn/Article/details/gthvminvgt.html

[U70] PHP：PDO 事务
来源：http://dali.bjfxy.top/Article/details/gtpcqkgnvy.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ivvv.top/Article/details/gtvtnlrfus.html

[U71] PHP：抛出异常
来源：http://dali.gotoacloud.top/Article/details/gtmhioxtws.html

throw new RuntimeException("失败", 500);
来源：http://dali.tanke756.top/Article/details/gtljtxdknb.html

[U72] PHP：写错误日志
来源：http://dali.hfpthk.cn/Article/details/gtgshkjbnq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.bjfxy.top/Article/details/gtwjpfhjab.html

[U73] PHP：读取 ini 配置
来源：http://dali.shangyingyoupin.top/Article/details/gtxoeiiexb.html

parse_ini_file("config.ini", true)
来源：http://dali.yuanzhike.top/Article/details/gtulihssdg.html

[U74] PHP：读取环境变量
来源：http://dali.ivvv.top/Article/details/gtwbrhksyz.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yongpay.top/Article/details/gtxzrjkaii.html

[U75] PHP：依赖注入
来源：http://dali.zhongyouzk.top/Article/details/gtqouvzklj.html

composer require psr/container
来源：http://dali.redwolf501.top/Article/details/gtbcfqbdzm.html

[U76] PHP：简单路由
来源：http://dali.jinqigufen.top/Article/details/gtnedfjush.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jyoumei.cn/Article/details/gtphmjvhvk.html

[U77] PHP：模板渲染
来源：http://dali.hnqzz.top/Article/details/gtikdpanvm.html

composer require twig/twig
来源：http://dali.daxiang520.top/Article/details/gtxzeppdeu.html

[U78] PHP：单元测试
来源：http://dali.hnxiangtu.top/Article/details/gtaljbwieg.html

composer require --dev phpunit/phpunit
来源：http://dali.shuidangran.top/Article/details/gtbyzydiku.html

[U79] PHP：静态分析
来源：http://dali.shangyingyoupin.top/Article/details/gtniydsmkg.html

composer require --dev phpstan/phpstan
来源：http://dali.gogol.net.cn/Article/details/gtteswuvuh.html

[U80] PHP：代码规范修复
来源：http://dali.ybcxt.top/Article/details/gtbiutgycj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.gogol.net.cn/Article/details/gtexbkhchi.html

[U81] JS：初始化项目
来源：http://dali.dashuyun.cn/Article/details/gthjltrzgg.html

npm init -y;  npm i express
来源：http://dali.jqgufenzy.top/Article/details/gtnkxyfkwo.html

[U82] JS：package.json 脚本
来源：http://dali.yangfankeji.com/Article/details/gtxsppbsfz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.chenzaomai.com/Article/details/gtenaenyaa.html

[U83] JS：ES Module 导入导出
来源：http://dali.quarkkingdee.top/Article/details/gtqfkywmnr.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.shzxlz.cn/Article/details/gtorjfjcgg.html

[U84] JS：CommonJS 写法
来源：http://dali.zhiwuduotai.top/Article/details/gtidhqxowk.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.wangdashe.top/Article/details/gtemqjdrey.html

[U85] JS：可选链
来源：http://dali.shzxlz.cn/Article/details/gtylrrkbww.html

a?.b?.c
来源：http://dali.meibo888.top/Article/details/gtcavabddl.html

[U86] JS：空值合并
来源：http://dali.daxiang520.top/Article/details/gtysggccop.html

a ?? b
来源：http://dali.svipenyu.cn/Article/details/gtgathhzsy.html

[U87] JS：解构默认值
来源：http://dali.ydzc1.top/Article/details/gtpoajerrw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jianghu66.top/Article/details/gtpzfgszwf.html

[U88] JS：对象展开合并
来源：http://dali.yj202588.top/Article/details/gtcuvgezvc.html

{ ...a, ...b }
来源：http://dali.yongpay.top/Article/details/gtavziczdp.html

[U89] JS：数组去重
来源：http://dali.yonumen.top/Article/details/gtnkcevcor.html

[...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gtpjzhjkcy.html

[U90] JS：数字数组排序
来源：http://dali.yvedp.cn/Article/details/gtrpczbynj.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yj20258.top/Article/details/gtyowocxdo.html

[U91] JS：对象键值遍历
来源：http://dali.sxryk.cn/Article/details/gtezdhhbtc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.smart0.xyz/Article/details/gtpblhkmbt.html

[U92] JS：深拷贝
来源：http://dali.zhengqikj.top/Article/details/gtytguevri.html

structuredClone(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjqqvdxfd.html

[U93] JS：模板字符串
来源：http://dali.jinqigufen.top/Article/details/gtbuzotlow.html

`共 ${n} 条`
来源：http://dali.ehwqpu.com/Article/details/gtuhvdearm.html

[U94] JS：箭头函数
来源：http://dali.hnxiangtu.top/Article/details/gtqeqzrcaf.html

const double = x => x * 2;
来源：http://dali.hammf.cn/Article/details/gtdnrmazfp.html

[U95] JS：Promise 包装
来源：http://dali.cucudq.cn/Article/details/gtdulurkgl.html

new Promise((resolve, reject) => {})
来源：http://dali.jyoumei.cn/Article/details/gtdndcxekt.html

[U96] JS：async/await 与异常
来源：http://dali.fengsongda.top/Article/details/gtkgyaqeug.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gtlvnewhou.html

[U97] JS：并发请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwmsjrhqs.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gtscfuzhdl.html

[U98] JS：fetch 带 JSON
来源：http://dali.guowangkeji.top/Article/details/gtnaiviift.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jlsjyb.cn/Article/details/gtnxfwktvb.html

[U99] JS：事件监听
来源：http://dali.andypj.xyz/Article/details/gtuzhinabx.html

el.addEventListener("click", e => {})
来源：http://dali.yuanzhike.top/Article/details/gtnooarntn.html

[U100] JS：DOM 查询
来源：http://dali.meibo888.top/Article/details/gtqdujmfrs.html

document.querySelector(".item")
来源：http://dali.cashguo.top/Article/details/gtfvjfsnos.html

[U101] JS：classList 操作
来源：http://dali.xuetiantiany.cn/Article/details/gtjwpvajnh.html

el.classList.toggle("active")
来源：http://dali.yvedp.cn/Article/details/gtrrsecdro.html

[U102] JS：本地存储
来源：http://dali.hysaishi.cn/Article/details/gtzhornfqa.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgkjyyjpp.html

[U103] JS：定时器
来源：http://dali.jqgufenzy.top/Article/details/gtqzwsvrhj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ppjwa.cn/Article/details/gtuqcumgbp.html

[U104] JS：防抖
来源：http://dali.shuidangran.top/Article/details/gtitriauoh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhiwuduotai.top/Article/details/gtpoumegft.html

[U105] JS：节流
来源：http://dali.yj20258888.top/Article/details/gtasvmibis.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.nanxuanxn.top/Article/details/gtopuwkbiz.html

[U106] JS：日期格式化
来源：http://dali.cqqwz.cn/Article/details/gtjeapovrs.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.aibaodan.cn/Article/details/gtkfihteht.html

[U107] JS：数字千分位
来源：http://dali.cucudq.cn/Article/details/gtxdrqsrco.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhixingplan.top/Article/details/gtkgzvijgv.html

[U108] JS：随机整数
来源：http://dali.316326.xyz/Article/details/gtezkkcrxj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.316326.xyz/Article/details/gtwcqpblpm.html

[U109] JS：数组分组
来源：http://dali.xinyue.icu/Article/details/gtlrkolcng.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ivvv.top/Article/details/gtimaulefn.html

[U110] JS：数组分块
来源：http://dali.zhengqikj.top/Article/details/gtdemwyzte.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtneufnpom.html

[U111] JS：对象转 Map
来源：http://dali.hnqzz.top/Article/details/gtocihnlin.html

new Map(Object.entries(obj))
来源：http://dali.fzhhl.top/Article/details/gtldnqkzgm.html

[U112] JS：字符串补位
来源：http://dali.hammf.cn/Article/details/gtjzqntvwd.html

"7".padStart(3, "0")
来源：http://dali.yj202588.top/Article/details/gtloldhcrh.html

[U113] JS：正则替换全部
来源：http://dali.zdqjudy.top/Article/details/gtbpexuknf.html

s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtnretovjl.html

[U114] JS：JSON 深比较
来源：http://dali.yvedp.cn/Article/details/gtstuauysw.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zdqjudy.top/Article/details/gtvesfvtmk.html

[U115] JS：生成 UUID
来源：http://dali.hongshengwenyu.top/Article/details/gthavepkev.html

crypto.randomUUID()
来源：http://dali.zhiwuduotai.top/Article/details/gtkjtdxxyx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.sweek.top/Article/details/gtvywvuefr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.wangdashe.top/Article/details/gtglvammze.html

[U117] JS：单元测试
来源：http://dali.0kj1m.cn/Article/details/gthjpqrzaz.html

npm i -D vitest;  npx vitest
来源：http://dali.guowangkeji.top/Article/details/gtjxaekkor.html

[U118] JS：开发服务器
来源：http://dali.ybcxt.top/Article/details/gtkfzjuryx.html

npm i -D vite;  npx vite
来源：http://dali.jqgufenzy.top/Article/details/gtokmwzmnd.html

[U119] JS：生产构建
来源：http://dali.jqgufenzy.top/Article/details/gtduryaglv.html

npx vite build
来源：http://dali.ybcxt.top/Article/details/gtaqwzbzla.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.gotoacloud.top/Article/details/gtrvqcwfro.html

import.meta.env.VITE_API_URL
来源：http://dali.ivvv.top/Article/details/gtqqldqmes.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtemiwkhot.html

统计汇总
来源：http://dali.jyoumei.cn/Article/details/gtmuydubjm.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtrjcrpjgy.html

按语言统计（条）：
来源：http://dali.yonumen.top/Article/details/gtpzpaupac.html

Python ......... 252
来源：http://dali.vqdsnc.cn/Article/details/gtnpxlnmli.html

PHP ............ 252
来源：http://dali.shuidangran.top/Article/details/gtcdyjepje.html

JavaScript ..... 252
来源：http://dali.aizwys.cn/Article/details/gtmnipkmpc.html

TypeScript ..... 212
来源：http://dali.havefunace.top/Article/details/gtuuopwisd.html

Java ........... 212
来源：http://dali.c1oappe.top/Article/details/gtguzoornv.html

Go ............. 212
来源：http://dali.yuxming.cn/Article/details/gtphkmqjfq.html

Ruby ........... 212
来源：http://dali.ydzc1.top/Article/details/gtbhibwwyl.html

C# ............. 212
来源：http://dali.gaohongyu789.top/Article/details/gtsaoddibg.html

C .............. 30
来源：http://dali.mhx1999.top/Article/details/gtfhkxaszh.html

C++ ............ 30
来源：http://dali.hammf.cn/Article/details/gtevbrvmrc.html

SQL ............ 90
来源：http://dali.tanke756.top/Article/details/gtmqhtjdnl.html

Bash ........... 80
来源：http://dali.ivvv.top/Article/details/gtzttkcmzd.html

Kotlin ......... 15
来源：http://dali.chenjidiqi.icu/Article/details/gtaargjvip.html

Swift .......... 15
来源：http://dali.hywenlv.cn/Article/details/gtyngwzkzn.html

Lua ............ 10
来源：http://dali.jyoumei.cn/Article/details/gtgoqgqzdj.html

Perl ........... 10
来源：http://dali.jinghuilouyu.cn/Article/details/gternqfvll.html

Scala .......... 10
来源：http://dali.sxryk.cn/Article/details/gtwfhnjgok.html

------------------------------------
来源：http://dali.jqgfzy.top/Article/details/gtgyclkjju.html

合计 ........... 2106 条
来源：http://dali.daria6918.cn/Article/details/gttpsvwofx.html

按章节统计：
来源：http://dali.jianghu66.top/Article/details/gtchcfnjjb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhoulong.xyz/Article/details/gtsuqlhawl.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.smart0.xyz/Article/details/gttnemdxhl.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jianghu66.top/Article/details/gtbqqbenoh.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.pengpengdd.cyou/Article/details/gtbbuvgper.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yj202588.top/Article/details/gtpxlxunyl.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gtuvpwlwfz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhoulong.xyz/Article/details/gtbcwfjshl.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqhjrktyg.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zycfv.cn/Article/details/gtilmdehto.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.meibo888.top/Article/details/gtzqmtglku.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.meibo888.top/Article/details/gtegxaelpe.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hysaishi.cn/Article/details/gtyfnsfbrs.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.meibo888.top/Article/details/gtfcaxpwca.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbbomtond.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.xuetiantiany.cn/Article/details/gtnscxluvu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.aibaodan.cn/Article/details/gtydkcexkj.html

Q SQL 专题                              90
来源：http://dali.cheryme.top/Article/details/gtyarmyvrz.html

R Bash 专题                             80
来源：http://dali.zdqjudy.top/Article/details/gtzdflssee.html

S C / C++ 专题                          60
来源：http://dali.yonumen.top/Article/details/gtzypogjhy.html

T 其他语言补充                          60
来源：http://dali.meibo888.top/Article/details/gttxnibhqr.html

U 高频实用片段                         120
来源：http://dali.zhengqikj.top/Article/details/gtoezasppn.html

------------------------------------
来源：http://dali.cashguo.top/Article/details/gtsxhnuvbp.html

合计                                  2106 条
来源：http://dali.jinyuanbaomall.cn/Article/details/gthltmnlkv.html

--------------------------------------------------------------------------------
来源：http://dali.yonumen.top/Article/details/gtgvybijsw.html

使用提醒
来源：http://dali.cheryme.top/Article/details/gtjrtyfbxh.html

--------------------------------------------------------------------------------
来源：http://dali.andypj.xyz/Article/details/gtiqregdqs.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yonumen.top/Article/details/gtjguvolhf.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.tian-w.cn/Article/details/gtwebxuvmy.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jqgfzy.top/Article/details/gtnxbusdhr.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.316326.xyz/Article/details/gtkcpuuipi.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yanxiufei.cn/Article/details/gtqralcwrd.html

—— 文件结束 ——
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyzhrovog.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtnqhfqqpn.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.xylfe.cn/Article/details/gtrifbzyhj.html

Common Programming Examples Cheat Book
来源：http://dali.mhx1999.top/Article/details/gtuygqcssh.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtdmgxenwv.html

【收录内容】
来源：http://dali.yvedp.cn/Article/details/gtnyawmbif.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jqgfzy.top/Article/details/gtvlmxmxlp.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.pycfn.com/Article/details/gtmfnoanzd.html

SQL · Bash · C · C++
来源：http://dali.zhixingplan.top/Article/details/gtraymcwqc.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yongpay.top/Article/details/gtrrrtubdm.html

【使用说明】
来源：http://dali.9152youxi.cn/Article/details/gtylbkcumg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.hammf.cn/Article/details/gtqhqqgikz.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.cqqwz.cn/Article/details/gtyxnendac.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfmrjsmvk.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yonumen.top/Article/details/gtldqabncj.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.sxryk.cn/Article/details/gtutyrekzw.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jiagoushi.top/Article/details/gtwouhfjwl.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhengqikj.top/Article/details/gtrhasnmph.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.hysaishi.cn/Article/details/gtfcxplodd.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.shanyushiyangtech.top/Article/details/gtkxewfzrj.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.kuanghao11.cn/Article/details/gtxzcajweu.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.chenlongwang.top/Article/details/gtuqtjgbqf.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jqgufenzy.top/Article/details/gtoktsazlm.html

【文件统计】
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqardvdwe.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yangfankeji.com/Article/details/gtlquuhbxl.html

--------------------------------------------------------------------------------
来源：http://dali.jinqigufen.top/Article/details/gtciwemgvu.html

目  录
来源：http://dali.yanxiufei.cn/Article/details/gtoldcofwn.html

--------------------------------------------------------------------------------
来源：http://dali.mhx1999.top/Article/details/gtnvbyevnf.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrylopgp.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.sweek.top/Article/details/gtbhnlllod.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.ivvv.top/Article/details/gtmmhhrxie.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtcxfaesmq.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hnqzz.top/Article/details/gtizvkkxtn.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtixgxdvns.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.ehwqpu.com/Article/details/gtaljevccq.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.gogol.net.cn/Article/details/gtbmehlnue.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.xinyue.icu/Article/details/gtsnhlctjv.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhongyouzk.top/Article/details/gtpdaapwrw.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jqgfzy.top/Article/details/gtwepvbsgm.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.kuanghao11.cn/Article/details/gtvrnhpuzm.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.cheryme.top/Article/details/gtviaphzvm.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.gaohongyu789.top/Article/details/gtmlfpajns.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdtqatis.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhongyouzk.top/Article/details/gtdhaybqnh.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.sufxvd.cn/Article/details/gtcrolovlp.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtgmqzevfl.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtzurwsgnc.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.dianchejie.cn/Article/details/gtpbodxuyt.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.nanxuanxn.top/Article/details/gtbrexgnsq.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtknwttovt.html

A. 基础语法与类型
来源：http://dali.xziqi.cn/Article/details/gttgdvmxpf.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtqaqwjqhj.html

[A01] Hello World
来源：http://dali.dianchejie.cn/Article/details/gteunwqqcs.html

Py:   print("Hello, World!")
来源：http://dali.chenlongwang.top/Article/details/gtfjbgirik.html

PHP:  echo "Hello, World!";
来源：http://dali.yuanzhike.top/Article/details/gtexuotszn.html

JS:   console.log("Hello, World!");
来源：http://dali.xuetiantiany.cn/Article/details/gtacomszht.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.gogol.net.cn/Article/details/gtrvhqlevh.html

Java: System.out.println("Hello, World!");
来源：http://dali.vqdsnc.cn/Article/details/gtztcicdpk.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.feifeiyinyue.top/Article/details/gtopbuudis.html

Ruby: puts "Hello, World!"
来源：http://dali.jlsjyb.cn/Article/details/gtifrphxhg.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.shangyingyoupin.top/Article/details/gtcuizjfht.html

[A02] 变量声明与赋值
来源：http://dali.zycfv.cn/Article/details/gtsrlnoepv.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.gaohongyu789.top/Article/details/gtcbduqsbo.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.nanxuanxn.top/Article/details/gtnywcrcte.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.nanxinkj.top/Article/details/gtdaefrsrv.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jinghuilouyu.cn/Article/details/gtvwgexfsf.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.sufxvd.cn/Article/details/gtuydbmmwo.html

Go:   name := "Alex"; age := 20
来源：http://dali.yuxming.cn/Article/details/gtxezftlkj.html

Ruby: name = "Alex"; age = 20
来源：http://dali.pengpengdd.cyou/Article/details/gtkpcpagjn.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhiwuduotai.top/Article/details/gtmwropnai.html

[A03] 常量定义
来源：http://dali.xuanzx.com/Article/details/gtcudqaary.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yj20258.top/Article/details/gtzkrrxtgd.html

PHP:  const PI = 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gtfzmtphyu.html

JS:   const PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gtcobfbygq.html

TS:   const PI: number = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gtczrxrydg.html

Java: static final double PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gtxdwjibxd.html

Go:   const PI = 3.14159
来源：http://dali.fengsongda.top/Article/details/gtnqzuozuy.html

Ruby: PI = 3.14159
来源：http://dali.wangshuangyany.cn/Article/details/gtsnhkqpnl.html

C#:   const double PI = 3.14159;
来源：http://dali.bjfxy.top/Article/details/gtvsexhtar.html

[A04] 判断变量类型
来源：http://dali.quarkkingdee.top/Article/details/gtchrtesej.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.fzhhl.top/Article/details/gtyrgqkcyb.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zdqjudy.top/Article/details/gtucuedfxh.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jinyuanbaomall.cn/Article/details/gtruttesde.html

TS:   typeof x; x instanceof Date
来源：http://dali.zycfv.cn/Article/details/gtiobidumy.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.snrcjt.cn/Article/details/gtytvgubmm.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yongpay.top/Article/details/gtmsqvvweg.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.0kj1m.cn/Article/details/gtsrsnufuk.html

C#:   x.GetType().Name; x is int
来源：http://dali.yj202588.top/Article/details/gtvbthtrto.html

[A05] 整数除法与取模
来源：http://dali.andypj.xyz/Article/details/gtvjtucrii.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhengqikj.top/Article/details/gttfvnpmag.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gtwvbugphg.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.fzhhl.top/Article/details/gtynnwgjwh.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hysaishi.cn/Article/details/gtywjnwsgx.html

Java: 7 / 2; 7 % 2
来源：http://dali.pycfn.com/Article/details/gtecbkfatg.html

Go:   7 / 2; 7 % 2
来源：http://dali.feifeiyinyue.top/Article/details/gtnlzwpxli.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jinqigufen.top/Article/details/gtjrubreyz.html

C#:   7 / 2; 7 % 2
来源：http://dali.jyoumei.cn/Article/details/gtbzliwkbp.html

[A06] 字符串转数字
来源：http://dali.mhx1999.top/Article/details/gtrrxuvdxg.html

Py:   int("42"); float("3.14")
来源：http://dali.yvedp.cn/Article/details/gtqiqejaqd.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtycyopusy.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.chenlongwang.top/Article/details/gttvhaqens.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuugkpjex.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtygwbgybt.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yueranfly.top/Article/details/gthmnuuyrk.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.redwolf501.top/Article/details/gtjdnojftg.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jianghu66.top/Article/details/gtmbryisgs.html

[A07] 数字转字符串
来源：http://dali.nanxinkj.top/Article/details/gtakdsxcwc.html

Py:   str(42)
来源：http://dali.redwolf501.top/Article/details/gthhomyuib.html

PHP:  (string) 42; strval(42)
来源：http://dali.316326.xyz/Article/details/gtpowqydqu.html

JS:   String(42); (42).toString()
来源：http://dali.jianghu66.top/Article/details/gtmnhkxjyv.html

TS:   String(42)
来源：http://dali.yj20258.top/Article/details/gtmbocvgch.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.chenzaomai.com/Article/details/gtaoygjllf.html

Go:   strconv.Itoa(42)
来源：http://dali.snrcjt.cn/Article/details/gtoymnwpkr.html

Ruby: 42.to_s
来源：http://dali.zhongyouzk.top/Article/details/gtwogwqkcv.html

C#:   42.ToString()
来源：http://dali.xylfe.cn/Article/details/gtaiktzvpn.html

[A08] 取整与四舍五入
来源：http://dali.smart0.xyz/Article/details/gtuydiuoil.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.wangdashe.top/Article/details/gtiigtxzfw.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.cucudq.cn/Article/details/gtcmysacdf.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.ppjwa.cn/Article/details/gtyztryyad.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.dashuyun.cn/Article/details/gttfpjcfed.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.kuanghao11.cn/Article/details/gtxmzofbat.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.shzxlz.cn/Article/details/gtdlmmffvu.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.nwbrower.top/Article/details/gtluuhexex.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jianghu66.top/Article/details/gtxhfbouez.html

[A09] 绝对值与最大最小值
来源：http://dali.iojbl.cn/Article/details/gtnggabspa.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.316326.xyz/Article/details/gtarewkywq.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.nwbrower.top/Article/details/gtmlqbpcrp.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.yangfankeji.com/Article/details/gtilbbvaxf.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.tanke756.top/Article/details/gtxtauguwd.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.daria6918.cn/Article/details/gtrfxangfc.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.xylfe.cn/Article/details/gtphhdchec.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.hnqzz.top/Article/details/gtxfnsffaa.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtqxgnlllt.html


<!-- 参考信息 -->