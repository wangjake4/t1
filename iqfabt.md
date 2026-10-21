代发 wailian999

[U65] PHP：会话
来源：http://dali.tian-w.cn/Article/details/gtemzycmhz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gtutqjeokn.html

[U66] PHP：设置 Cookie
来源：http://dali.dianchejie.cn/Article/details/gtjwifdxpb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.ehwqpu.com/Article/details/gtomwjronr.html

[U67] PHP：处理文件上传
来源：http://dali.guowangkeji.top/Article/details/gtxlyhzovm.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.feifeiyinyue.top/Article/details/gtwnqomfyh.html

[U68] PHP：PDO 连接
来源：http://dali.xuanzx.com/Article/details/gthbbqdmlx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jqgufenzy.top/Article/details/gtolhmobjn.html

[U69] PHP：PDO 预处理
来源：http://dali.smart0.xyz/Article/details/gtomlwchvj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hongshengwenyu.top/Article/details/gtrvrvggsr.html

[U70] PHP：PDO 事务
来源：http://dali.guowangkeji.top/Article/details/gtntjktist.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yuxming.cn/Article/details/gtqvgpoqmg.html

[U71] PHP：抛出异常
来源：http://dali.jyoumei.cn/Article/details/gttkiknyqv.html

throw new RuntimeException("失败", 500);
来源：http://dali.zycfv.cn/Article/details/gttbadiaic.html

[U72] PHP：写错误日志
来源：http://dali.nanxuanxn.top/Article/details/gthbjwyqbm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.shuidangran.top/Article/details/gtjqotnblr.html

[U73] PHP：读取 ini 配置
来源：http://dali.yj202588.top/Article/details/gtdblqapve.html

parse_ini_file("config.ini", true)
来源：http://dali.ydzc1.top/Article/details/gtwncpkvff.html

[U74] PHP：读取环境变量
来源：http://dali.jianghu66.top/Article/details/gtwgleeleg.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ydzc1.top/Article/details/gtpslseniu.html

[U75] PHP：依赖注入
来源：http://dali.shanyushiyangtech.top/Article/details/gtwrrjfbfa.html

composer require psr/container
来源：http://dali.pycfn.com/Article/details/gtxsezjkwv.html

[U76] PHP：简单路由
来源：http://dali.gzhubu.top/Article/details/gtwtwipnlc.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.snrcjt.cn/Article/details/gtcqzvieoa.html

[U77] PHP：模板渲染
来源：http://dali.daria6918.cn/Article/details/gtepnnejhs.html

composer require twig/twig
来源：http://dali.ybcxt.top/Article/details/gtupupxmol.html

[U78] PHP：单元测试
来源：http://dali.zhixingplan.top/Article/details/gtjkybcmrf.html

composer require --dev phpunit/phpunit
来源：http://dali.jiagoushi.top/Article/details/gtqqettssp.html

[U79] PHP：静态分析
来源：http://dali.wangshuangyany.cn/Article/details/gtiswifxtg.html

composer require --dev phpstan/phpstan
来源：http://dali.nwbrower.top/Article/details/gttbbbqfno.html

[U80] PHP：代码规范修复
来源：http://dali.haohaochexian.top/Article/details/gtxplwhksg.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.hfpthk.cn/Article/details/gtygaiqien.html

[U81] JS：初始化项目
来源：http://dali.meibo888.top/Article/details/gtnpzxmxay.html

npm init -y;  npm i express
来源：http://dali.zdqjudy.top/Article/details/gtnbtqsutk.html

[U82] JS：package.json 脚本
来源：http://dali.andypj.xyz/Article/details/gtowvjcsyk.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hysaishi.cn/Article/details/gtiqaznwke.html

[U83] JS：ES Module 导入导出
来源：http://dali.9152youxi.cn/Article/details/gtccxragkd.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.snrcjt.cn/Article/details/gtfihacugy.html

[U84] JS：CommonJS 写法
来源：http://dali.pycfn.com/Article/details/gtuoprwdtm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.aibaodan.cn/Article/details/gtsfrwzibx.html

[U85] JS：可选链
来源：http://dali.fzhhl.top/Article/details/gttebscwpu.html

a?.b?.c
来源：http://dali.mhx1999.top/Article/details/gtuhchgoxo.html

[U86] JS：空值合并
来源：http://dali.gaohongyu789.top/Article/details/gtlflumvfq.html

a ?? b
来源：http://dali.xuanzx.com/Article/details/gtbbxuxfoc.html

[U87] JS：解构默认值
来源：http://dali.xuetiantiany.cn/Article/details/gtfecohyzl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.ppjwa.cn/Article/details/gtelniwtse.html

[U88] JS：对象展开合并
来源：http://dali.jinqigfzy.top/Article/details/gtwmrlkmxe.html

{ ...a, ...b }
来源：http://dali.xziqi.cn/Article/details/gtaerqvjqe.html

[U89] JS：数组去重
来源：http://dali.zhongyouzk.top/Article/details/gthgaisbak.html

[...new Set(arr)]
来源：http://dali.9152youxi.cn/Article/details/gtcnhkajmc.html

[U90] JS：数字数组排序
来源：http://dali.cucudq.cn/Article/details/gtkktaphjl.html

[...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gtodpcvkmd.html

[U91] JS：对象键值遍历
来源：http://dali.vqdsnc.cn/Article/details/gtykrxdush.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ybcxt.top/Article/details/gtvxpxjonz.html

[U92] JS：深拷贝
来源：http://dali.nanxuanxn.top/Article/details/gtpmqinnnm.html

structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gttzarbnei.html

[U93] JS：模板字符串
来源：http://dali.yangfankeji.com/Article/details/gtoqfkrggi.html

`共 ${n} 条`
来源：http://dali.nanxuanxn.top/Article/details/gtjtefyoaz.html

[U94] JS：箭头函数
来源：http://dali.andypj.xyz/Article/details/gtvnsgbrls.html

const double = x => x * 2;
来源：http://dali.fzhhl.top/Article/details/gtbygrnjou.html

[U95] JS：Promise 包装
来源：http://dali.bjfxy.top/Article/details/gtkvsuwkbb.html

new Promise((resolve, reject) => {})
来源：http://dali.xziqi.cn/Article/details/gtqqxobjdp.html

[U96] JS：async/await 与异常
来源：http://dali.chenzaomai.com/Article/details/gtlglfttrw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jyoumei.cn/Article/details/gtdebfyelj.html

[U97] JS：并发请求
来源：http://dali.vqdsnc.cn/Article/details/gtvmjbvelu.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gtccswhrwn.html

[U98] JS：fetch 带 JSON
来源：http://dali.yj20258.top/Article/details/gtpfrkpakm.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yanxiufei.cn/Article/details/gtsalifulo.html

[U99] JS：事件监听
来源：http://dali.ybcxt.top/Article/details/gtjondzwuq.html

el.addEventListener("click", e => {})
来源：http://dali.zhengqikj.top/Article/details/gtmbgovfvt.html

[U100] JS：DOM 查询
来源：http://dali.shuidangran.top/Article/details/gtjwzotxqq.html

document.querySelector(".item")
来源：http://dali.gzhubu.top/Article/details/gtpweirniu.html

[U101] JS：classList 操作
来源：http://dali.zdqjudy.top/Article/details/gthuslkzjj.html

el.classList.toggle("active")
来源：http://dali.hongshengwenyu.top/Article/details/gtdhicfncz.html

[U102] JS：本地存储
来源：http://dali.bjfxy.top/Article/details/gtauubxjfz.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.chenlongwang.top/Article/details/gtpdqdgltc.html

[U103] JS：定时器
来源：http://dali.9152youxi.cn/Article/details/gtaygrmdwk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yuanzhike.top/Article/details/gtiiundjty.html

[U104] JS：防抖
来源：http://dali.pengpengdd.cyou/Article/details/gtstmgwkfp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.316326.xyz/Article/details/gthzxxpnrm.html

[U105] JS：节流
来源：http://dali.yangfankeji.com/Article/details/gtvucmzwej.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.quarkkingdee.top/Article/details/gtwhydguzc.html

[U106] JS：日期格式化
来源：http://dali.bjfxy.top/Article/details/gtzomzchvm.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtngdmqllm.html

[U107] JS：数字千分位
来源：http://dali.dashuyun.cn/Article/details/gtoihevntd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.daria6918.cn/Article/details/gtrajnwbgf.html

[U108] JS：随机整数
来源：http://dali.xylfe.cn/Article/details/gtqsbzmage.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhongyouzk.top/Article/details/gtwkumfbqs.html

[U109] JS：数组分组
来源：http://dali.shzxlz.cn/Article/details/gtpjdycbmc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ydzc1.top/Article/details/gtxuztobbo.html

[U110] JS：数组分块
来源：http://dali.0kj1m.cn/Article/details/gtqilvwqgk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.daria6918.cn/Article/details/gtfiaxnqav.html

[U111] JS：对象转 Map
来源：http://dali.daxiang520.top/Article/details/gtiepxyvaz.html

new Map(Object.entries(obj))
来源：http://dali.daxiang520.top/Article/details/gthjwmgwwr.html

[U112] JS：字符串补位
来源：http://dali.havefunace.top/Article/details/gtymivuoht.html

"7".padStart(3, "0")
来源：http://dali.birdmap.top/Article/details/gtmszlqeul.html

[U113] JS：正则替换全部
来源：http://dali.iojbl.cn/Article/details/gtkabhvhtj.html

s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtwxyxpacc.html

[U114] JS：JSON 深比较
来源：http://dali.pycfn.com/Article/details/gtjloegolo.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fzhhl.top/Article/details/gtaevqodeg.html

[U115] JS：生成 UUID
来源：http://dali.c1oappe.top/Article/details/gtabzowhfr.html

crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gtbzgdldnb.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.snrcjt.cn/Article/details/gtvahldhez.html

/** @param {string} name */ function f(name) {}
来源：http://dali.chenzaomai.com/Article/details/gtnvnqzltf.html

[U117] JS：单元测试
来源：http://dali.hammf.cn/Article/details/gtfecxdiyw.html

npm i -D vitest;  npx vitest
来源：http://dali.meibo888.top/Article/details/gtwjzkdeah.html

[U118] JS：开发服务器
来源：http://dali.0kj1m.cn/Article/details/gtyvyyitvd.html

npm i -D vite;  npx vite
来源：http://dali.birdmap.top/Article/details/gtkkjgbgvp.html

[U119] JS：生产构建
来源：http://dali.smart0.xyz/Article/details/gttpbguxgm.html

npx vite build
来源：http://dali.cdnleiting.top/Article/details/gtshhxibbk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.kuanghao11.cn/Article/details/gtdkvzxlwv.html

import.meta.env.VITE_API_URL
来源：http://dali.zhaomingkeji.xyz/Article/details/gtabfmieln.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtxlhzxkcz.html

统计汇总
来源：http://dali.ppjwa.cn/Article/details/gtiazbvvxr.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtimbbbgax.html

按语言统计（条）：
来源：http://dali.dianchejie.cn/Article/details/gtzruequom.html

Python ......... 252
来源：http://dali.yongpay.top/Article/details/gtirmdoggo.html

PHP ............ 252
来源：http://dali.nanxinkj.top/Article/details/gtyddyflpy.html

JavaScript ..... 252
来源：http://dali.guowangkeji.top/Article/details/gtdxrrwsym.html

TypeScript ..... 212
来源：http://dali.daria6918.cn/Article/details/gtfhkzthme.html

Java ........... 212
来源：http://dali.daria6918.cn/Article/details/gtbfzkotju.html

Go ............. 212
来源：http://dali.bjfxy.top/Article/details/gtsfltbaec.html

Ruby ........... 212
来源：http://dali.tian-w.cn/Article/details/gtdkwnoqrd.html

C# ............. 212
来源：http://dali.guannengcc.top/Article/details/gtjeeszupv.html

C .............. 30
来源：http://dali.vqdsnc.cn/Article/details/gtrosgimxz.html

C++ ............ 30
来源：http://dali.tanke756.top/Article/details/gtggvccxkj.html

SQL ............ 90
来源：http://dali.aibaodan.cn/Article/details/gtfygsmzdj.html

Bash ........... 80
来源：http://dali.smart0.xyz/Article/details/gtzyacvkev.html

Kotlin ......... 15
来源：http://dali.redwolf501.top/Article/details/gtprbszhsf.html

Swift .......... 15
来源：http://dali.haohaochexian.top/Article/details/gtmgxknffh.html

Lua ............ 10
来源：http://dali.gogol.net.cn/Article/details/gtfewmjafj.html

Perl ........... 10
来源：http://dali.hysaishi.cn/Article/details/gtngmlercn.html

Scala .......... 10
来源：http://dali.mhx1999.top/Article/details/gtnhnnqngc.html

------------------------------------
来源：http://dali.tianlin.xyz/Article/details/gtfcxtmdll.html

合计 ........... 2106 条
来源：http://dali.hnqzz.top/Article/details/gtdrrvmcnj.html

按章节统计：
来源：http://dali.yuxming.cn/Article/details/gtsdnxdfzk.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.shzxlz.cn/Article/details/gthocoqcpx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.guannengcc.top/Article/details/gtwoecyenj.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jinghuilouyu.cn/Article/details/gtiildnppf.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xylfe.cn/Article/details/gtsmkbiudh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.bjfxy.top/Article/details/gttwcqfwzz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.guowangkeji.top/Article/details/gtyaczsydq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.birdmap.top/Article/details/gttlvoeucs.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhengqikj.top/Article/details/gtohkbilzn.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.xylfe.cn/Article/details/gtgstttkch.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jqgfzy.top/Article/details/gtpeyrnxso.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmslaxhtv.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xylfe.cn/Article/details/gtbzvjdkbj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.feifeiyinyue.top/Article/details/gtlnypjuvs.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.fzhhl.top/Article/details/gtvsmbggsa.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhaomingkeji.xyz/Article/details/gteeuqpdpv.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.andypj.xyz/Article/details/gtnuohsbln.html

Q SQL 专题                              90
来源：http://dali.cheryme.top/Article/details/gtbkpvcezw.html

R Bash 专题                             80
来源：http://dali.tanke756.top/Article/details/gtktuuqzvi.html

S C / C++ 专题                          60
来源：http://dali.cqqwz.cn/Article/details/gtxbgdxpev.html

T 其他语言补充                          60
来源：http://dali.nanxinkj.top/Article/details/gtcucscekq.html

U 高频实用片段                         120
来源：http://dali.cdnleiting.top/Article/details/gtdbkgljfm.html

------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gtgypozooa.html

合计                                  2106 条
来源：http://dali.hammf.cn/Article/details/gtomrolfif.html

--------------------------------------------------------------------------------
来源：http://dali.sxryk.cn/Article/details/gtsluuluhf.html

使用提醒
来源：http://dali.zycfv.cn/Article/details/gtubahhobf.html

--------------------------------------------------------------------------------
来源：http://dali.yueranfly.top/Article/details/gtwlyqvsey.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.cheryme.top/Article/details/gtlkilxfrw.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.smart0.xyz/Article/details/gtppfxplbc.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.shangyingyoupin.top/Article/details/gtsccaoiaw.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.aizwys.cn/Article/details/gtsdgzspwn.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.ehwqpu.com/Article/details/gtappwjmpa.html

—— 文件结束 ——
来源：http://dali.jiagoushi.top/Article/details/gtksfmgino.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gthggxumpl.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.mhx1999.top/Article/details/gtsmzjlfhp.html

Common Programming Examples Cheat Book
来源：http://dali.hfpthk.cn/Article/details/gtuommznvm.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtdfpneeeu.html

【收录内容】
来源：http://dali.jlsjyb.cn/Article/details/gtbexyauli.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.wangshuangyany.cn/Article/details/gtabtwmviz.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.wangshuangyany.cn/Article/details/gtufhzsdzn.html

SQL · Bash · C · C++
来源：http://dali.jiagoushi.top/Article/details/gtagtksaxf.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.ivvv.top/Article/details/gtrlxsbrzi.html

【使用说明】
来源：http://dali.havefunace.top/Article/details/gtjczowaie.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.smart0.xyz/Article/details/gtravcqjgs.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.gaohongyu789.top/Article/details/gtfkwayorc.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hywenlv.cn/Article/details/gtuvtrcjrc.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.svipenyu.cn/Article/details/gtrcisixcw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.iojbl.cn/Article/details/gtlwscbihy.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.tanke756.top/Article/details/gtognkaupp.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.gotoacloud.top/Article/details/gtffsrdbto.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.gzhubu.top/Article/details/gttomddoee.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhengqikj.top/Article/details/gtwcoayalm.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.ehwqpu.com/Article/details/gtfiegygdv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.ivvv.top/Article/details/gtdynzykqc.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.hfpthk.cn/Article/details/gtfewkmqis.html

【文件统计】
来源：http://dali.ivvv.top/Article/details/gtunqaukcs.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.hammf.cn/Article/details/gttvqvotsy.html

--------------------------------------------------------------------------------
来源：http://dali.cashguo.top/Article/details/gtcucodfuc.html

目  录
来源：http://dali.cdnleiting.top/Article/details/gtvzrpnxmq.html

--------------------------------------------------------------------------------
来源：http://dali.gotoacloud.top/Article/details/gtpmnfedta.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yongpay.top/Article/details/gtryrtdzgk.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.guowangkeji.top/Article/details/gtzjtvczix.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yj20258.top/Article/details/gtugiqodpy.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.nwbrower.top/Article/details/gtwvhgpjgb.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.vqdsnc.cn/Article/details/gtxbuxptxw.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvgbhwbas.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.andypj.xyz/Article/details/gtmlxxblys.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yvedp.cn/Article/details/gtmpfadgco.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.daxiang520.top/Article/details/gtoitbcmgy.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jyoumei.cn/Article/details/gtvnlosvoh.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.chenzaomai.com/Article/details/gtmxpdnwom.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.xinyue.icu/Article/details/gtajnrzigy.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.vqdsnc.cn/Article/details/gtlkixdowk.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkulczxsp.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yangfankeji.com/Article/details/gtjyrjfujd.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.gaohongyu789.top/Article/details/gthauszqor.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtdaeuqucz.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.svipenyu.cn/Article/details/gtudfeaxmz.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yj20258888.top/Article/details/gtgubbonoa.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.kuanghao11.cn/Article/details/gtcznscqrl.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.sweek.top/Article/details/gtfppsvgeb.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtmvryjxwz.html

A. 基础语法与类型
来源：http://dali.zhoulong.xyz/Article/details/gtbcygklue.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtglzwloff.html

[A01] Hello World
来源：http://dali.zhixingplan.top/Article/details/gthpdvjnvz.html

Py:   print("Hello, World!")
来源：http://dali.aibaodan.cn/Article/details/gtprjotirq.html

PHP:  echo "Hello, World!";
来源：http://dali.gzhubu.top/Article/details/gtmrgytztx.html

JS:   console.log("Hello, World!");
来源：http://dali.cqqwz.cn/Article/details/gtngwbxcpg.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yongpay.top/Article/details/gtczoxxxgx.html

Java: System.out.println("Hello, World!");
来源：http://dali.jyoumei.cn/Article/details/gtzbvggxls.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yueranfly.top/Article/details/gtcvcatvog.html

Ruby: puts "Hello, World!"
来源：http://dali.fengsongda.top/Article/details/gtmyopohrp.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.xinyue.icu/Article/details/gtnhuqptfe.html

[A02] 变量声明与赋值
来源：http://dali.sysykeji.top/Article/details/gthdvcasvi.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yj20258888.top/Article/details/gtsosdftlo.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.mhx1999.top/Article/details/gtsxfphbua.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhoulong.xyz/Article/details/gtfydvzjvt.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhoulong.xyz/Article/details/gtdneixgmb.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.chenzaomai.com/Article/details/gtkhhtwlhe.html

Go:   name := "Alex"; age := 20
来源：http://dali.jinqigufen.top/Article/details/gtiplcxadn.html

Ruby: name = "Alex"; age = 20
来源：http://dali.dianchejie.cn/Article/details/gtemjcbwfz.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yj20258.top/Article/details/gtizfzppsa.html

[A03] 常量定义
来源：http://dali.zycfv.cn/Article/details/gtgkbkhjfx.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.cqqwz.cn/Article/details/gthuyukfyq.html

PHP:  const PI = 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gtyuijgldb.html

JS:   const PI = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtbkceocco.html

TS:   const PI: number = 3.14159;
来源：http://dali.xinyue.icu/Article/details/gtrvvqcjpx.html

Java: static final double PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gtekfxqefr.html

Go:   const PI = 3.14159
来源：http://dali.hysaishi.cn/Article/details/gtvpbyfaew.html

Ruby: PI = 3.14159
来源：http://dali.ydzc1.top/Article/details/gthbggerfy.html

C#:   const double PI = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gtnwtrbknn.html

[A04] 判断变量类型
来源：http://dali.cashguo.top/Article/details/gtauhdgeiq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.guannengcc.top/Article/details/gtnogkccpw.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.chenjidiqi.icu/Article/details/gtqcwothxl.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.tian-w.cn/Article/details/gtdcyjtzjw.html

TS:   typeof x; x instanceof Date
来源：http://dali.quarkkingdee.top/Article/details/gtnyxoimiz.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yanxiufei.cn/Article/details/gtsitrlaeo.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jyoumei.cn/Article/details/gtnpknynvb.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.feifeiyinyue.top/Article/details/gtxbytdzid.html

C#:   x.GetType().Name; x is int
来源：http://dali.snrcjt.cn/Article/details/gteqbebftm.html

[A05] 整数除法与取模
来源：http://dali.wangdashe.top/Article/details/gtwlknpkgh.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zycfv.cn/Article/details/gtgxcodijz.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.feifeiyinyue.top/Article/details/gtbddoaubj.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.sysykeji.top/Article/details/gtrqxlxodj.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hnxiangtu.top/Article/details/gtoxtxffxb.html

Java: 7 / 2; 7 % 2
来源：http://dali.nanxinkj.top/Article/details/gtbykpcwis.html

Go:   7 / 2; 7 % 2
来源：http://dali.chenlongwang.top/Article/details/gtymkksqgk.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.316326.xyz/Article/details/gteluotdqf.html

C#:   7 / 2; 7 % 2
来源：http://dali.aizwys.cn/Article/details/gtkrgmupuc.html

[A06] 字符串转数字
来源：http://dali.zhengqikj.top/Article/details/gttdqyiywf.html

Py:   int("42"); float("3.14")
来源：http://dali.aibaodan.cn/Article/details/gtgdllcyme.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yuanzhike.top/Article/details/gtylifjami.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.kuanghao11.cn/Article/details/gttdtztuwa.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.cheryme.top/Article/details/gtwsdhtguv.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.cashguo.top/Article/details/gtlzuikifp.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.shzxlz.cn/Article/details/gtttxzsisc.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.redwolf501.top/Article/details/gtabylgupc.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.nwbrower.top/Article/details/gtviuhcupl.html

[A07] 数字转字符串
来源：http://dali.xziqi.cn/Article/details/gtzicvojot.html

Py:   str(42)
来源：http://dali.316326.xyz/Article/details/gtusliltol.html

PHP:  (string) 42; strval(42)
来源：http://dali.wangdashe.top/Article/details/gtntsnbglr.html

JS:   String(42); (42).toString()
来源：http://dali.dianchejie.cn/Article/details/gtlounnxhj.html

TS:   String(42)
来源：http://dali.xziqi.cn/Article/details/gtgpbbiecz.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqhoficf.html

Go:   strconv.Itoa(42)
来源：http://dali.jyoumei.cn/Article/details/gtwempdlgk.html

Ruby: 42.to_s
来源：http://dali.mhx1999.top/Article/details/gtnvvbbpjc.html

C#:   42.ToString()
来源：http://dali.jinqigufen.top/Article/details/gtpttvczra.html

[A08] 取整与四舍五入
来源：http://dali.yangfankeji.com/Article/details/gtrhiebtwd.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.shangyingyoupin.top/Article/details/gttsznijgb.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsvshzheu.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthwyxmty.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gtdunvqfql.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jinqigfzy.top/Article/details/gtojiujzxh.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.sxryk.cn/Article/details/gtahdkpwiq.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.ivvv.top/Article/details/gtqdebcgve.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.guowangkeji.top/Article/details/gtgvzsmdzp.html

[A09] 绝对值与最大最小值
来源：http://dali.jinqigufen.top/Article/details/gtrntrnknl.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.316326.xyz/Article/details/gttuzyvvpl.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.sweek.top/Article/details/gtajectvoe.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtoippjuie.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.jiagoushi.top/Article/details/gtjgwjjxma.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtibfvkojj.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.nwbrower.top/Article/details/gtmrybjvpg.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.tianlin.xyz/Article/details/gtqddhqcxy.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gtzebxwjnj.html


<!-- 参考信息 -->