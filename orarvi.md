代发 wailian999

[U65] PHP：会话
来源：http://dali.haohaochexian.top/Article/details/gtpbftumyj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtvwpgrkvf.html

[U66] PHP：设置 Cookie
来源：http://dali.jqgfzy.top/Article/details/gtsdwxqfpt.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.wangdashe.top/Article/details/gtzordugnl.html

[U67] PHP：处理文件上传
来源：http://dali.jqgfzy.top/Article/details/gtvondfmcs.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yanxiufei.cn/Article/details/gtipidjwyg.html

[U68] PHP：PDO 连接
来源：http://dali.vqdsnc.cn/Article/details/gthtuicgao.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yueranfly.top/Article/details/gttebxkedv.html

[U69] PHP：PDO 预处理
来源：http://dali.guowangkeji.top/Article/details/gtvfvzlhko.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ppjwa.cn/Article/details/gtkxhgnuzl.html

[U70] PHP：PDO 事务
来源：http://dali.9152youxi.cn/Article/details/gtoyskkfis.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.gzhubu.top/Article/details/gtvsimzrts.html

[U71] PHP：抛出异常
来源：http://dali.jiagoushi.top/Article/details/gtvczcwzda.html

throw new RuntimeException("失败", 500);
来源：http://dali.yuxming.cn/Article/details/gtcimkanxd.html

[U72] PHP：写错误日志
来源：http://dali.gzhubu.top/Article/details/gtqtijcxlo.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfhuxwdud.html

[U73] PHP：读取 ini 配置
来源：http://dali.jinghuilouyu.cn/Article/details/gtqsijquys.html

parse_ini_file("config.ini", true)
来源：http://dali.sysykeji.top/Article/details/gtlsptmozv.html

[U74] PHP：读取环境变量
来源：http://dali.hfpthk.cn/Article/details/gtqzxzcvou.html

getenv("APP_ENV") ?: "production"
来源：http://dali.hnxiangtu.top/Article/details/gtgfpnqldw.html

[U75] PHP：依赖注入
来源：http://dali.snrcjt.cn/Article/details/gtpnfmfttw.html

composer require psr/container
来源：http://dali.ydzc1.top/Article/details/gtnwhdgkkg.html

[U76] PHP：简单路由
来源：http://dali.jinqigfzy.top/Article/details/gtzwwnhfuu.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yongpay.top/Article/details/gtausnnkzj.html

[U77] PHP：模板渲染
来源：http://dali.shangyingyoupin.top/Article/details/gtityjxfcl.html

composer require twig/twig
来源：http://dali.hywenlv.cn/Article/details/gteiuakufd.html

[U78] PHP：单元测试
来源：http://dali.aibaodan.cn/Article/details/gtplwrvsjt.html

composer require --dev phpunit/phpunit
来源：http://dali.yueranfly.top/Article/details/gtrdkhndhc.html

[U79] PHP：静态分析
来源：http://dali.cashguo.top/Article/details/gtfosjajzp.html

composer require --dev phpstan/phpstan
来源：http://dali.zhengqikj.top/Article/details/gtfclzgztd.html

[U80] PHP：代码规范修复
来源：http://dali.hysaishi.cn/Article/details/gtgncjbjwd.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.daria6918.cn/Article/details/gtjcrkhjxt.html

[U81] JS：初始化项目
来源：http://dali.redwolf501.top/Article/details/gtwfffmxfj.html

npm init -y;  npm i express
来源：http://dali.fengsongda.top/Article/details/gtierhsyai.html

[U82] JS：package.json 脚本
来源：http://dali.havefunace.top/Article/details/gtdzcrmlhz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jiagoushi.top/Article/details/gtijrakeut.html

[U83] JS：ES Module 导入导出
来源：http://dali.andypj.xyz/Article/details/gtuxwcmoim.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.cdnleiting.top/Article/details/gtuzopbugc.html

[U84] JS：CommonJS 写法
来源：http://dali.nanxinkj.top/Article/details/gttwddpxyh.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.tian-w.cn/Article/details/gtknumyrer.html

[U85] JS：可选链
来源：http://dali.fzhhl.top/Article/details/gtsfhnwtaf.html

a?.b?.c
来源：http://dali.c1oappe.top/Article/details/gtwuqkxlub.html

[U86] JS：空值合并
来源：http://dali.kuanghao11.cn/Article/details/gtmpowmbnq.html

a ?? b
来源：http://dali.yongpay.top/Article/details/gtjmozshsj.html

[U87] JS：解构默认值
来源：http://dali.aizwys.cn/Article/details/gtcyxdsrbx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.sweek.top/Article/details/gtobwedood.html

[U88] JS：对象展开合并
来源：http://dali.yuanzhike.top/Article/details/gtpeglxyoi.html

{ ...a, ...b }
来源：http://dali.yvedp.cn/Article/details/gtxyvtlbwr.html

[U89] JS：数组去重
来源：http://dali.yj202588.top/Article/details/gtbtbwpmgp.html

[...new Set(arr)]
来源：http://dali.jlsjyb.cn/Article/details/gtetmrmsoi.html

[U90] JS：数字数组排序
来源：http://dali.haohaochexian.top/Article/details/gtyfpwjhmy.html

[...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gtmxfskxih.html

[U91] JS：对象键值遍历
来源：http://dali.sweek.top/Article/details/gtgquhpkan.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.redwolf501.top/Article/details/gtslmyzdde.html

[U92] JS：深拷贝
来源：http://dali.guannengcc.top/Article/details/gtkqexwpmj.html

structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtqtmucgdc.html

[U93] JS：模板字符串
来源：http://dali.daxiang520.top/Article/details/gtkzpxrpcb.html

`共 ${n} 条`
来源：http://dali.dashuyun.cn/Article/details/gtgtyqiest.html

[U94] JS：箭头函数
来源：http://dali.yvedp.cn/Article/details/gtvvhzjjxl.html

const double = x => x * 2;
来源：http://dali.yongpay.top/Article/details/gtotglqtwg.html

[U95] JS：Promise 包装
来源：http://dali.aizwys.cn/Article/details/gttuxunstk.html

new Promise((resolve, reject) => {})
来源：http://dali.jinghuilouyu.cn/Article/details/gtxbmdnbqu.html

[U96] JS：async/await 与异常
来源：http://dali.feifeiyinyue.top/Article/details/gtrpocytqa.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gtvhfjobqd.html

[U97] JS：并发请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gtunxufvvt.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.smart0.xyz/Article/details/gteuudnlid.html

[U98] JS：fetch 带 JSON
来源：http://dali.snrcjt.cn/Article/details/gthcjoblvj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xziqi.cn/Article/details/gtuptvcgul.html

[U99] JS：事件监听
来源：http://dali.meibo888.top/Article/details/gtnrcdwnzk.html

el.addEventListener("click", e => {})
来源：http://dali.dianchejie.cn/Article/details/gtjuzjhmzd.html

[U100] JS：DOM 查询
来源：http://dali.quarkkingdee.top/Article/details/gtiypzbrzl.html

document.querySelector(".item")
来源：http://dali.316326.xyz/Article/details/gtpgbntfda.html

[U101] JS：classList 操作
来源：http://dali.vqdsnc.cn/Article/details/gtddlwusqp.html

el.classList.toggle("active")
来源：http://dali.zhiwuduotai.top/Article/details/gtqkfhxwwh.html

[U102] JS：本地存储
来源：http://dali.hfpthk.cn/Article/details/gtihtajxcx.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.bjfxy.top/Article/details/gtbhscyoyn.html

[U103] JS：定时器
来源：http://dali.zhengqikj.top/Article/details/gtebusueww.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hfpthk.cn/Article/details/gtffazwydp.html

[U104] JS：防抖
来源：http://dali.haohaochexian.top/Article/details/gttfyorvom.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.smart0.xyz/Article/details/gtcaeaamgx.html

[U105] JS：节流
来源：http://dali.zycfv.cn/Article/details/gthhmdydkg.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jqgfzy.top/Article/details/gtgqgvcyta.html

[U106] JS：日期格式化
来源：http://dali.tian-w.cn/Article/details/gtsjejymna.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yonumen.top/Article/details/gterojtter.html

[U107] JS：数字千分位
来源：http://dali.nanxuanxn.top/Article/details/gtdmtnheqa.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.316326.xyz/Article/details/gtwmqopzbr.html

[U108] JS：随机整数
来源：http://dali.xylfe.cn/Article/details/gtgbmlyqrb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.sweek.top/Article/details/gtwlepvwyi.html

[U109] JS：数组分组
来源：http://dali.yj20258888.top/Article/details/gteenxqgjz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258888.top/Article/details/gtyvtapcbq.html

[U110] JS：数组分块
来源：http://dali.zdqjudy.top/Article/details/gthgxaraob.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.mhx1999.top/Article/details/gtdlarzhhq.html

[U111] JS：对象转 Map
来源：http://dali.chenzaomai.com/Article/details/gtzfptdyzs.html

new Map(Object.entries(obj))
来源：http://dali.xylfe.cn/Article/details/gtnjpfsscp.html

[U112] JS：字符串补位
来源：http://dali.zhongyouzk.top/Article/details/gtpyvssmyw.html

"7".padStart(3, "0")
来源：http://dali.gogol.net.cn/Article/details/gtondnawok.html

[U113] JS：正则替换全部
来源：http://dali.gaohongyu789.top/Article/details/gtolbzdpib.html

s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtpokksuhj.html

[U114] JS：JSON 深比较
来源：http://dali.hfpthk.cn/Article/details/gtzeywacsr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ivvv.top/Article/details/gtvpnrylzg.html

[U115] JS：生成 UUID
来源：http://dali.cdnleiting.top/Article/details/gtjibvmcxi.html

crypto.randomUUID()
来源：http://dali.jianghu66.top/Article/details/gtpqrwhbst.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.chenzaomai.com/Article/details/gtjzwdpezk.html

/** @param {string} name */ function f(name) {}
来源：http://dali.gaohongyu789.top/Article/details/gtofwzseju.html

[U117] JS：单元测试
来源：http://dali.bjfxy.top/Article/details/gtuewuedej.html

npm i -D vitest;  npx vitest
来源：http://dali.gaohongyu789.top/Article/details/gtjqrnjaez.html

[U118] JS：开发服务器
来源：http://dali.fzhhl.top/Article/details/gtcnhxpvql.html

npm i -D vite;  npx vite
来源：http://dali.redwolf501.top/Article/details/gtynexxjuw.html

[U119] JS：生产构建
来源：http://dali.gaohongyu789.top/Article/details/gtuobwflzw.html

npx vite build
来源：http://dali.jiagoushi.top/Article/details/gtzdoqysbg.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.quarkkingdee.top/Article/details/gtlklllesu.html

import.meta.env.VITE_API_URL
来源：http://dali.meibo888.top/Article/details/gtjhdejgbq.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gttgxwjubj.html

统计汇总
来源：http://dali.bjfxy.top/Article/details/gtcnnfoysv.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtichhnlch.html

按语言统计（条）：
来源：http://dali.jyoumei.cn/Article/details/gtgxnqzize.html

Python ......... 252
来源：http://dali.yj202588.top/Article/details/gtjcsvgpyq.html

PHP ............ 252
来源：http://dali.cucudq.cn/Article/details/gtuxklbejp.html

JavaScript ..... 252
来源：http://dali.cdnleiting.top/Article/details/gtktjqavsu.html

TypeScript ..... 212
来源：http://dali.vqdsnc.cn/Article/details/gtawyxxzuv.html

Java ........... 212
来源：http://dali.ybcxt.top/Article/details/gttvorphiv.html

Go ............. 212
来源：http://dali.shangyingyoupin.top/Article/details/gtuwxxnjhp.html

Ruby ........... 212
来源：http://dali.tianlin.xyz/Article/details/gtbblftcpt.html

C# ............. 212
来源：http://dali.iojbl.cn/Article/details/gtuhuumahe.html

C .............. 30
来源：http://dali.smart0.xyz/Article/details/gtwqhydczy.html

C++ ............ 30
来源：http://dali.xuanzx.com/Article/details/gtaldkpfoa.html

SQL ............ 90
来源：http://dali.jqgfzy.top/Article/details/gtyucqdpgi.html

Bash ........... 80
来源：http://dali.guannengcc.top/Article/details/gtxlytiufc.html

Kotlin ......... 15
来源：http://dali.yongpay.top/Article/details/gtgdhrmefl.html

Swift .......... 15
来源：http://dali.hfpthk.cn/Article/details/gtzzokxagn.html

Lua ............ 10
来源：http://dali.sxryk.cn/Article/details/gtjswanpvp.html

Perl ........... 10
来源：http://dali.dianchejie.cn/Article/details/gtkzlpsjgr.html

Scala .......... 10
来源：http://dali.ybcxt.top/Article/details/gtkygdesbx.html

------------------------------------
来源：http://dali.jyoumei.cn/Article/details/gtubprjvgf.html

合计 ........... 2106 条
来源：http://dali.fzhhl.top/Article/details/gtadcbjlsx.html

按章节统计：
来源：http://dali.zycfv.cn/Article/details/gtwyqeroer.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.tian-w.cn/Article/details/gtwqqonrdw.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.cdnleiting.top/Article/details/gtcilhqtui.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shuidangran.top/Article/details/gtdxetvdtp.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hysaishi.cn/Article/details/gtzebbhoox.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.aibaodan.cn/Article/details/gtrgrgsmqi.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hywenlv.cn/Article/details/gtvjeimkco.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.sxryk.cn/Article/details/gtjrtxjnda.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yj20258888.top/Article/details/gtwhpztqem.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.ybcxt.top/Article/details/gtfsiaisfp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.quarkkingdee.top/Article/details/gtslzwjfmj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.feifeiyinyue.top/Article/details/gtjsaheyrs.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.c1oappe.top/Article/details/gtwxwvwcuq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hammf.cn/Article/details/gtgwbefjth.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.dashuyun.cn/Article/details/gtdatariik.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ydzc1.top/Article/details/gtqndofycd.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.svipenyu.cn/Article/details/gtaffpyewy.html

Q SQL 专题                              90
来源：http://dali.guannengcc.top/Article/details/gtftzzhoaw.html

R Bash 专题                             80
来源：http://dali.redwolf501.top/Article/details/gtqhijegyv.html

S C / C++ 专题                          60
来源：http://dali.chenjidiqi.icu/Article/details/gttyhcmqul.html

T 其他语言补充                          60
来源：http://dali.yj20258.top/Article/details/gtqwefuxid.html

U 高频实用片段                         120
来源：http://dali.xziqi.cn/Article/details/gtqyuxmhoc.html

------------------------------------
来源：http://dali.pycfn.com/Article/details/gtfmjhpfyk.html

合计                                  2106 条
来源：http://dali.shangyingyoupin.top/Article/details/gtygztqnvu.html

--------------------------------------------------------------------------------
来源：http://dali.snrcjt.cn/Article/details/gtecjlieqs.html

使用提醒
来源：http://dali.birdmap.top/Article/details/gtilsjymok.html

--------------------------------------------------------------------------------
来源：http://dali.jiagoushi.top/Article/details/gtnjnsvrfb.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhongyouzk.top/Article/details/gthmkroijs.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.cdnleiting.top/Article/details/gtbevtsuqa.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.chenjidiqi.icu/Article/details/gtrmvvlklx.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.nanxinkj.top/Article/details/gtitjdjdjt.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhengqikj.top/Article/details/gtsdwonosu.html

—— 文件结束 ——
来源：http://dali.sweek.top/Article/details/gtyrnuidsy.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtzfyatobr.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jqgfzy.top/Article/details/gtrfhiidwk.html

Common Programming Examples Cheat Book
来源：http://dali.fzhhl.top/Article/details/gtdicwbdue.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gthibxggbm.html

【收录内容】
来源：http://dali.vqdsnc.cn/Article/details/gtbpwkvjca.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.cheryme.top/Article/details/gtxuentkjm.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.hongshengwenyu.top/Article/details/gtkcmxbewr.html

SQL · Bash · C · C++
来源：http://dali.zhiwuduotai.top/Article/details/gtfizipzhe.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.dianchejie.cn/Article/details/gtrexocgda.html

【使用说明】
来源：http://dali.xziqi.cn/Article/details/gtiufrnrhn.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpfbjdusd.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.kuanghao11.cn/Article/details/gtfiqvbdrx.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.tian-w.cn/Article/details/gtpvljzffu.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ivvv.top/Article/details/gtdewtdlft.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhoulong.xyz/Article/details/gtozyvdoxt.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.sufxvd.cn/Article/details/gtwnmsshsj.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.gzhubu.top/Article/details/gtuattclsa.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhiwuduotai.top/Article/details/gtcukolnwe.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jinqigfzy.top/Article/details/gtknbtoybe.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.sysykeji.top/Article/details/gtcimlhshg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jinqigufen.top/Article/details/gtcgahxrtc.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.haohaochexian.top/Article/details/gthtrahqba.html

【文件统计】
来源：http://dali.yanxiufei.cn/Article/details/gtkpfhyutl.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.meibo888.top/Article/details/gtbgjzfvyc.html

--------------------------------------------------------------------------------
来源：http://dali.nanxuanxn.top/Article/details/gtximingiv.html

目  录
来源：http://dali.zhoulong.xyz/Article/details/gtsaboojmq.html

--------------------------------------------------------------------------------
来源：http://dali.sysykeji.top/Article/details/gtevdbcefj.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.pycfn.com/Article/details/gtnxpqynre.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtxkhsrntb.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.kuanghao11.cn/Article/details/gtmzjssggs.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jinqigufen.top/Article/details/gtwdifgtbg.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.gzhubu.top/Article/details/gtkarzvkfu.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.svipenyu.cn/Article/details/gtynhmpssu.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.vqdsnc.cn/Article/details/gtawkgtgtl.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yueranfly.top/Article/details/gtqtsocakz.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.bjfxy.top/Article/details/gtuzasnrzu.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.redwolf501.top/Article/details/gtkebrzicw.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.quarkkingdee.top/Article/details/gtpphtufxw.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yj202588.top/Article/details/gtrcysnejc.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtdciwcdki.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.guannengcc.top/Article/details/gtsnatmpfh.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yueranfly.top/Article/details/gttnlqqysq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtopgndtge.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhengqikj.top/Article/details/gtgfalqcfj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.daria6918.cn/Article/details/gtnkkqtpkd.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zdqjudy.top/Article/details/gtxiudzrwh.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xinyue.icu/Article/details/gtltqqjuip.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jyoumei.cn/Article/details/gtrwuaidnl.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtaxpelsiq.html

A. 基础语法与类型
来源：http://dali.gzhubu.top/Article/details/gtycccdebs.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtefckizxq.html

[A01] Hello World
来源：http://dali.yj20258888.top/Article/details/gttqdaydmp.html

Py:   print("Hello, World!")
来源：http://dali.sufxvd.cn/Article/details/gtfzktytxs.html

PHP:  echo "Hello, World!";
来源：http://dali.sweek.top/Article/details/gtolopgkun.html

JS:   console.log("Hello, World!");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfzcrxxo.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhongyouzk.top/Article/details/gttmivthjf.html

Java: System.out.println("Hello, World!");
来源：http://dali.jqgfzy.top/Article/details/gtpmtsadtj.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.chenjidiqi.icu/Article/details/gtsnxrwfop.html

Ruby: puts "Hello, World!"
来源：http://dali.316326.xyz/Article/details/gtovtyrjgn.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.gaohongyu789.top/Article/details/gtzvyfrkdu.html

[A02] 变量声明与赋值
来源：http://dali.wangshuangyany.cn/Article/details/gtjkbodiau.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.hammf.cn/Article/details/gtmkilbzwq.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.mhx1999.top/Article/details/gtyqnekcci.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ehwqpu.com/Article/details/gtzgsqgmjt.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.sysykeji.top/Article/details/gtsgjxihpv.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jqgfzy.top/Article/details/gtzwvjyuui.html

Go:   name := "Alex"; age := 20
来源：http://dali.yongpay.top/Article/details/gtvfwgsezk.html

Ruby: name = "Alex"; age = 20
来源：http://dali.c1oappe.top/Article/details/gtrnonteqk.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.smart0.xyz/Article/details/gtgfgijqge.html

[A03] 常量定义
来源：http://dali.pengpengdd.cyou/Article/details/gtoqndzllo.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zycfv.cn/Article/details/gtrahpgjee.html

PHP:  const PI = 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gtmvqldytb.html

JS:   const PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gtnngzdsnl.html

TS:   const PI: number = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtsxueqtmb.html

Java: static final double PI = 3.14159;
来源：http://dali.316326.xyz/Article/details/gtpevnsbbl.html

Go:   const PI = 3.14159
来源：http://dali.jinyuanbaomall.cn/Article/details/gtspygagjk.html

Ruby: PI = 3.14159
来源：http://dali.aibaodan.cn/Article/details/gtaeiiwdfa.html

C#:   const double PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtuqgczagg.html

[A04] 判断变量类型
来源：http://dali.birdmap.top/Article/details/gtsbqttxce.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jlsjyb.cn/Article/details/gthhwxflhd.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.xinyue.icu/Article/details/gtgrunwgbj.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zdqjudy.top/Article/details/gtgidxopis.html

TS:   typeof x; x instanceof Date
来源：http://dali.cucudq.cn/Article/details/gtbbsqzska.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.redwolf501.top/Article/details/gtoirgyzbx.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.smart0.xyz/Article/details/gthsfffnpj.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.dashuyun.cn/Article/details/gtxrhlqhxo.html

C#:   x.GetType().Name; x is int
来源：http://dali.wangshuangyany.cn/Article/details/gtqmfchggu.html

[A05] 整数除法与取模
来源：http://dali.shangyingyoupin.top/Article/details/gtyzhssate.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhongyouzk.top/Article/details/gtypdwtviy.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.smart0.xyz/Article/details/gtvfxivhyp.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmuoqaqer.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.fengsongda.top/Article/details/gtcpfswpbh.html

Java: 7 / 2; 7 % 2
来源：http://dali.svipenyu.cn/Article/details/gtwhwkkoby.html

Go:   7 / 2; 7 % 2
来源：http://dali.xziqi.cn/Article/details/gtxmvvkxhq.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.quarkkingdee.top/Article/details/gthowwddvm.html

C#:   7 / 2; 7 % 2
来源：http://dali.cucudq.cn/Article/details/gtalvsngej.html

[A06] 字符串转数字
来源：http://dali.fengsongda.top/Article/details/gtqpzkwkdq.html

Py:   int("42"); float("3.14")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpctxokld.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.ydzc1.top/Article/details/gtgeazgmna.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.hfpthk.cn/Article/details/gtygtccnqg.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.bjfxy.top/Article/details/gttyptswzd.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.svipenyu.cn/Article/details/gtszgskapa.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.xylfe.cn/Article/details/gtxvnxspcx.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.cqqwz.cn/Article/details/gthxbpdnns.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.havefunace.top/Article/details/gtqfzqmghz.html

[A07] 数字转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtflssgmic.html

Py:   str(42)
来源：http://dali.jianghu66.top/Article/details/gtesbzavnl.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhiwuduotai.top/Article/details/gtamtolzua.html

JS:   String(42); (42).toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtpqgiwegk.html

TS:   String(42)
来源：http://dali.daria6918.cn/Article/details/gtciqkyfmz.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.cqqwz.cn/Article/details/gtzcbnqxzs.html

Go:   strconv.Itoa(42)
来源：http://dali.sufxvd.cn/Article/details/gtpwsunaks.html

Ruby: 42.to_s
来源：http://dali.yj202588.top/Article/details/gtkibetknk.html

C#:   42.ToString()
来源：http://dali.hammf.cn/Article/details/gtviiysnbs.html

[A08] 取整与四舍五入
来源：http://dali.dianchejie.cn/Article/details/gthjhpgadx.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.sysykeji.top/Article/details/gtpejjomfv.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yangfankeji.com/Article/details/gtducuytho.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.redwolf501.top/Article/details/gtceoatyxj.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.xinyue.icu/Article/details/gtgpcvgocw.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.dashuyun.cn/Article/details/gtgyicsecq.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yj20258.top/Article/details/gtycgtvmba.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yj20258.top/Article/details/gtzjewngxa.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jinghuilouyu.cn/Article/details/gtknbfsybm.html

[A09] 绝对值与最大最小值
来源：http://dali.sysykeji.top/Article/details/gtcgnwckne.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gttggxmrsp.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtrlhufiri.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhixingplan.top/Article/details/gtthmzcfrw.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.hfpthk.cn/Article/details/gtfdukpndo.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.shuidangran.top/Article/details/gtjeuaraxk.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.wangdashe.top/Article/details/gtzsinqdkq.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.cdnleiting.top/Article/details/gtwsodzdlj.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtbgviiyid.html


<!-- 参考信息 -->