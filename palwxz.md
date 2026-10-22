代发 wailian999

[U67] PHP：处理文件上传
来源：http://dali.xinyue.icu/Article/details/gt2jyhybelg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.aibaodan.cn/Article/details/gt2wavssfgj.html

[U68] PHP：PDO 连接
来源：http://dali.cucudq.cn/Article/details/gt2bhasnens.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jianghu66.top/Article/details/gt2mmitsyma.html

[U69] PHP：PDO 预处理
来源：http://dali.tian-w.cn/Article/details/gt2yvdebxtt.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ybcxt.top/Article/details/gt2iczewaop.html

[U70] PHP：PDO 事务
来源：http://dali.guannengcc.top/Article/details/gt2qpxlzevm.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yueranfly.top/Article/details/gt2eaddmnzy.html

[U71] PHP：抛出异常
来源：http://dali.bjfxy.top/Article/details/gt2aqxowwpk.html

throw new RuntimeException("失败", 500);
来源：http://dali.hnxiangtu.top/Article/details/gt2vcffsbxw.html

[U72] PHP：写错误日志
来源：http://dali.jinghuilouyu.cn/Article/details/gt2anofknfr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.sxryk.cn/Article/details/gt2lmoakafj.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxxmkgw.html

parse_ini_file("config.ini", true)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kwdoqspu.html

[U74] PHP：读取环境变量
来源：http://dali.cashguo.top/Article/details/gt2vmujkzym.html

getenv("APP_ENV") ?: "production"
来源：http://dali.gzhubu.top/Article/details/gt2ofvqqysj.html

[U75] PHP：依赖注入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nhriwhlu.html

composer require psr/container
来源：http://dali.guannengcc.top/Article/details/gt2ivdmdrzx.html

[U76] PHP：简单路由
来源：http://dali.mhx1999.top/Article/details/gt2ooloiygf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yueranfly.top/Article/details/gt2fdudsdkg.html

[U77] PHP：模板渲染
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lwgasamv.html

composer require twig/twig
来源：http://dali.cucudq.cn/Article/details/gt2wxdyuhvh.html

[U78] PHP：单元测试
来源：http://dali.cucudq.cn/Article/details/gt2jxqidtws.html

composer require --dev phpunit/phpunit
来源：http://dali.xziqi.cn/Article/details/gt2bmwvpjiq.html

[U79] PHP：静态分析
来源：http://dali.guowangkeji.top/Article/details/gt2fghyvisa.html

composer require --dev phpstan/phpstan
来源：http://dali.nwbrower.top/Article/details/gt2tvtqjbzy.html

[U80] PHP：代码规范修复
来源：http://dali.gzhubu.top/Article/details/gt2bsyazwba.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.ydzc1.top/Article/details/gt2ypnalasn.html

[U81] JS：初始化项目
来源：http://dali.pycfn.com/Article/details/gt2ppsccnes.html

npm init -y;  npm i express
来源：http://dali.zhengqikj.top/Article/details/gt2orxluwvv.html

[U82] JS：package.json 脚本
来源：http://dali.9152youxi.cn/Article/details/gt2xwiknsnl.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.xuetiantiany.cn/Article/details/gt2almgpaya.html

[U83] JS：ES Module 导入导出
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bmcmsqpa.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.xylfe.cn/Article/details/gt2rdeeusin.html

[U84] JS：CommonJS 写法
来源：http://dali.zhengqikj.top/Article/details/gt2emaijijv.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.fengsongda.top/Article/details/gt2tyysgrkt.html

[U85] JS：可选链
来源：http://dali.xziqi.cn/Article/details/gt2isnegurc.html

a?.b?.c
来源：http://dali.zhongyouzk.top/Article/details/gt2owiwxjli.html

[U86] JS：空值合并
来源：http://dali.aizwys.cn/Article/details/gt2bktobuic.html

a ?? b
来源：http://dali.jlsjyb.cn/Article/details/gt2raokwvex.html

[U87] JS：解构默认值
来源：http://dali.sweek.top/Article/details/gt2yodkwjid.html

const { a = 1, b = 2 } = obj;
来源：http://dali.bjfxy.top/Article/details/gt2ptaxlpkz.html

[U88] JS：对象展开合并
来源：http://dali.havefunace.top/Article/details/gt2zicztzjn.html

{ ...a, ...b }
来源：http://dali.fengsongda.top/Article/details/gt2pyzwtzxj.html

[U89] JS：数组去重
来源：http://dali.nwbrower.top/Article/details/gt2lyejldfn.html

[...new Set(arr)]
来源：http://dali.cucudq.cn/Article/details/gt2jkkjxuwv.html

[U90] JS：数字数组排序
来源：http://dali.shzxlz.cn/Article/details/gt2ahsqfxvv.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yuxming.cn/Article/details/gt2scnhbxrz.html

[U91] JS：对象键值遍历
来源：http://dali.hywenlv.cn/Article/details/gt2tefzlnwp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.chenjidiqi.icu/Article/details/gt2yrfggvyb.html

[U92] JS：深拷贝
来源：http://dali.jinqigfzy.top/Article/details/gt2wtrzmtbd.html

structuredClone(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2uxeiraou.html

[U93] JS：模板字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2qkdfkwkr.html

`共 ${n} 条`
来源：http://dali.jqgufenzy.top/Article/details/gt2xlimhrwh.html

[U94] JS：箭头函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2myhmrtjp.html

const double = x => x * 2;
来源：http://dali.andypj.xyz/Article/details/gt2zrkpfape.html

[U95] JS：Promise 包装
来源：http://dali.ivvv.top/Article/details/gt2ftmomhqg.html

new Promise((resolve, reject) => {})
来源：http://dali.ivvv.top/Article/details/gt2liryyuyc.html

[U96] JS：async/await 与异常
来源：http://dali.vqdsnc.cn/Article/details/gt2fkzixbne.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2lzmdwpgz.html

[U97] JS：并发请求
来源：http://dali.zhengqikj.top/Article/details/gt2dhindlti.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cheryme.top/Article/details/gt2owiwxkka.html

[U98] JS：fetch 带 JSON
来源：http://dali.tianlin.xyz/Article/details/gt2iljyasda.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.snrcjt.cn/Article/details/gt2wxrpdnxd.html

[U99] JS：事件监听
来源：http://dali.fzhhl.top/Article/details/gt2luiwoaky.html

el.addEventListener("click", e => {})
来源：http://dali.xylfe.cn/Article/details/gt2wjyyqpac.html

[U100] JS：DOM 查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vjlcysrq.html

document.querySelector(".item")
来源：http://dali.zhongyouzk.top/Article/details/gt2erncgdyd.html

[U101] JS：classList 操作
来源：http://dali.cdnleiting.top/Article/details/gt2thjeeuex.html

el.classList.toggle("active")
来源：http://dali.zycfv.cn/Article/details/gt2kwpxandj.html

[U102] JS：本地存储
来源：http://dali.316326.xyz/Article/details/gt2rpptvewq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.tianlin.xyz/Article/details/gt2ilrthpms.html

[U103] JS：定时器
来源：http://dali.yvedp.cn/Article/details/gt2rkpbjhxi.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cdnleiting.top/Article/details/gt2xoqlmpjt.html

[U104] JS：防抖
来源：http://dali.xuanzx.com/Article/details/gt2bqaraoek.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hfpthk.cn/Article/details/gt2jmnrdqck.html

[U105] JS：节流
来源：http://dali.shangyingyoupin.top/Article/details/gt2tutyuxxf.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.gotoacloud.top/Article/details/gt2kgkqnibq.html

[U106] JS：日期格式化
来源：http://dali.zycfv.cn/Article/details/gt2qvcmkspn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhengqikj.top/Article/details/gt2rtvxuquy.html

[U107] JS：数字千分位
来源：http://dali.mhx1999.top/Article/details/gt2tybisqbs.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yj20258888.top/Article/details/gt2xbqtzjpy.html

[U108] JS：随机整数
来源：http://dali.jqgfzy.top/Article/details/gt2tgqnezgk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yueranfly.top/Article/details/gt2onlgvofa.html

[U109] JS：数组分组
来源：http://dali.wangdashe.top/Article/details/gt2xyxvqawq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.tanke756.top/Article/details/gt2uolglbaw.html

[U110] JS：数组分块
来源：http://dali.daxiang520.top/Article/details/gt2adfuxviz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.cucudq.cn/Article/details/gt2fzoztxpu.html

[U111] JS：对象转 Map
来源：http://dali.dashuyun.cn/Article/details/gt2ervcokxt.html

new Map(Object.entries(obj))
来源：http://dali.xinyue.icu/Article/details/gt2tacvzest.html

[U112] JS：字符串补位
来源：http://dali.yangfankeji.com/Article/details/gt2fnbuzivo.html

"7".padStart(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gt2gmtyggri.html

[U113] JS：正则替换全部
来源：http://dali.sxryk.cn/Article/details/gt2wlmfbtzr.html

s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gt2nnobwuuv.html

[U114] JS：JSON 深比较
来源：http://dali.sweek.top/Article/details/gt2hexwqxwm.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.havefunace.top/Article/details/gt2fdzvnjkg.html

[U115] JS：生成 UUID
来源：http://dali.yj20258888.top/Article/details/gt2iiyaohgs.html

crypto.randomUUID()
来源：http://dali.ydzc1.top/Article/details/gt2xjpszell.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xinyue.icu/Article/details/gt2hpvjvmym.html

/** @param {string} name */ function f(name) {}
来源：http://dali.dashuyun.cn/Article/details/gt2cxsrmlnm.html

[U117] JS：单元测试
来源：http://dali.shangyingyoupin.top/Article/details/gt2jkhoggoq.html

npm i -D vitest;  npx vitest
来源：http://dali.ydzc1.top/Article/details/gt2pxxtrkje.html

[U118] JS：开发服务器
来源：http://dali.tianlin.xyz/Article/details/gt2zzvpfxhq.html

npm i -D vite;  npx vite
来源：http://dali.yuxming.cn/Article/details/gt2zugpzncv.html

[U119] JS：生产构建
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2okksvqjh.html

npx vite build
来源：http://dali.0kj1m.cn/Article/details/gt2vfqvcpur.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hammf.cn/Article/details/gt2enuzanyh.html

import.meta.env.VITE_API_URL
来源：http://dali.wangshuangyany.cn/Article/details/gt2sfeekncc.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2timlafax.html

统计汇总
来源：http://dali.hnqzz.top/Article/details/gt2iuwfizlj.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2inowydiq.html

按语言统计（条）：
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nbrjjwoc.html

Python ......... 252
来源：http://dali.wangshuangyany.cn/Article/details/gt2eseriuzn.html

PHP ............ 252
来源：http://dali.nanxuanxn.top/Article/details/gt2kxssmdvn.html

JavaScript ..... 252
来源：http://dali.redwolf501.top/Article/details/gt2nplalqtb.html

TypeScript ..... 212
来源：http://dali.shangyingyoupin.top/Article/details/gt2glyybgdl.html

Java ........... 212
来源：http://dali.bjfxy.top/Article/details/gt2fhrzjrqt.html

Go ............. 212
来源：http://dali.xylfe.cn/Article/details/gt2ubsufwjq.html

Ruby ........... 212
来源：http://dali.guowangkeji.top/Article/details/gt2cdamarmn.html

C# ............. 212
来源：http://dali.9152youxi.cn/Article/details/gt2jokcbzlf.html

C .............. 30
来源：http://dali.vqdsnc.cn/Article/details/gt2iaukrpac.html

C++ ............ 30
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jxqwyhea.html

SQL ............ 90
来源：http://dali.andypj.xyz/Article/details/gt2tdltineh.html

Bash ........... 80
来源：http://dali.hnqzz.top/Article/details/gt2nrnltowq.html

Kotlin ......... 15
来源：http://dali.feifeiyinyue.top/Article/details/gt2oskbomyo.html

Swift .......... 15
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2appvifsx.html

Lua ............ 10
来源：http://dali.andypj.xyz/Article/details/gt2qekuzrda.html

Perl ........... 10
来源：http://dali.pycfn.com/Article/details/gt2gkjfivbf.html

Scala .......... 10
来源：http://dali.smart0.xyz/Article/details/gt2lihkawmu.html

------------------------------------
来源：http://dali.yangfankeji.com/Article/details/gt2mmwfdiaf.html

合计 ........... 2106 条
来源：http://dali.andypj.xyz/Article/details/gt2gbssyryg.html

按章节统计：
来源：http://dali.jinghuilouyu.cn/Article/details/gt2miycxdsg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lshfnzlc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.meibo888.top/Article/details/gt2srfwgtcl.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.c1oappe.top/Article/details/gt2areldbay.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.ivvv.top/Article/details/gt2slrzkhyl.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.mhx1999.top/Article/details/gt2kpnshfks.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.iojbl.cn/Article/details/gt2yxvxphuz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.tianlin.xyz/Article/details/gt2xgoagbny.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.cheryme.top/Article/details/gt2dqkyanjr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.andypj.xyz/Article/details/gt2shlrgtto.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.redwolf501.top/Article/details/gt2xfqvggbv.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xylfe.cn/Article/details/gt2mjpeyghi.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhoulong.xyz/Article/details/gt2tssfplcc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2heyxqhpd.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.wangdashe.top/Article/details/gt2dmnfuxsg.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.0kj1m.cn/Article/details/gt2mplpvynx.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jlsjyb.cn/Article/details/gt2sjbkrtdf.html

Q SQL 专题                              90
来源：http://dali.fengsongda.top/Article/details/gt2jwcnmqar.html

R Bash 专题                             80
来源：http://dali.yanxiufei.cn/Article/details/gt2khdgdkkb.html

S C / C++ 专题                          60
来源：http://dali.hammf.cn/Article/details/gt2crgtjzmt.html

T 其他语言补充                          60
来源：http://dali.jlsjyb.cn/Article/details/gt2dztcjlaw.html

U 高频实用片段                         120
来源：http://dali.chenlongwang.top/Article/details/gt2wwccacbg.html

------------------------------------
来源：http://dali.yangfankeji.com/Article/details/gt2hetynavs.html

合计                                  2106 条
来源：http://dali.jqgufenzy.top/Article/details/gt2mfuvpptk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgfwlkd.html

使用提醒
来源：http://dali.fengsongda.top/Article/details/gt2uvzgxzhy.html

--------------------------------------------------------------------------------
来源：http://dali.ivvv.top/Article/details/gt2ncibhshn.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.vqdsnc.cn/Article/details/gt2wlwjonng.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.bjfxy.top/Article/details/gt2wbrwxbke.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.feifeiyinyue.top/Article/details/gt2fjnjdjbh.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.shuidangran.top/Article/details/gt2bsuhykke.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yj20258888.top/Article/details/gt2bzovitut.html

—— 文件结束 ——
来源：http://dali.pengpengdd.cyou/Article/details/gt2eestulwr.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2kdxltauq.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.wangshuangyany.cn/Article/details/gt2rubgvmxz.html

Common Programming Examples Cheat Book
来源：http://dali.sweek.top/Article/details/gt2fddtfpxo.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2cmhbxguz.html

【收录内容】
来源：http://dali.shuidangran.top/Article/details/gt2irdkeejw.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.bjfxy.top/Article/details/gt2pyuljgax.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.c1oappe.top/Article/details/gt2xaqklfii.html

SQL · Bash · C · C++
来源：http://dali.chenlongwang.top/Article/details/gt2chnqlqod.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.hnxiangtu.top/Article/details/gt2mpdmwowf.html

【使用说明】
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wgpfcizn.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xdgugpht.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.fzhhl.top/Article/details/gt2zmsueomx.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.ybcxt.top/Article/details/gt2vmmncdda.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ybcxt.top/Article/details/gt2zeffaoun.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.0kj1m.cn/Article/details/gt2psdcfvma.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.nanxuanxn.top/Article/details/gt2hsqmdowu.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.cdnleiting.top/Article/details/gt2dditateh.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jinqigfzy.top/Article/details/gt2subylgfg.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.shangyingyoupin.top/Article/details/gt2mwfizovo.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jinqigfzy.top/Article/details/gt2zuecepfb.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.cdnleiting.top/Article/details/gt2fuzmhfzx.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yanxiufei.cn/Article/details/gt2qloflnqp.html

【文件统计】
来源：http://dali.xylfe.cn/Article/details/gt2mbqvjwjr.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.316326.xyz/Article/details/gt2mkgkqmpt.html

--------------------------------------------------------------------------------
来源：http://dali.mhx1999.top/Article/details/gt2rturkfgx.html

目  录
来源：http://dali.zhiwuduotai.top/Article/details/gt2pxsrhyur.html

--------------------------------------------------------------------------------
来源：http://dali.zhiwuduotai.top/Article/details/gt2gfcqxyej.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.guowangkeji.top/Article/details/gt2orxhjpea.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.xuetiantiany.cn/Article/details/gt2tyqkjxuh.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2paedpvct.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.birdmap.top/Article/details/gt2ccssxqmd.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhoulong.xyz/Article/details/gt2flfwcizl.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.andypj.xyz/Article/details/gt2mjjhhfac.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.smart0.xyz/Article/details/gt2wuoqgyvo.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yuanzhike.top/Article/details/gt2czeevjih.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.fzhhl.top/Article/details/gt2zqpbbknl.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.guannengcc.top/Article/details/gt2opcuehbj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.guannengcc.top/Article/details/gt2wnipfort.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yj20258.top/Article/details/gt2mdszxzkn.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.nanxinkj.top/Article/details/gt2lhwincjs.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.cucudq.cn/Article/details/gt2wtrjqmye.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rflbjaiu.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.daria6918.cn/Article/details/gt2aoabcoyz.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.cashguo.top/Article/details/gt2mdjxsolv.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.shzxlz.cn/Article/details/gt2bnvocpyw.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.wangdashe.top/Article/details/gt2iowaqbpe.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhixingplan.top/Article/details/gt2huixnwnc.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jqgfzy.top/Article/details/gt2fvytmulw.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2vjyqjuia.html

A. 基础语法与类型
来源：http://dali.cheryme.top/Article/details/gt2kpncaese.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2spcsfkfx.html

[A01] Hello World
来源：http://dali.hnqzz.top/Article/details/gt2kngpqopa.html

Py:   print("Hello, World!")
来源：http://dali.yonumen.top/Article/details/gt2fkgxplwv.html

PHP:  echo "Hello, World!";
来源：http://dali.shzxlz.cn/Article/details/gt2tmqjgceh.html

JS:   console.log("Hello, World!");
来源：http://dali.iojbl.cn/Article/details/gt2xelubcwi.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.ybcxt.top/Article/details/gt2jyldposd.html

Java: System.out.println("Hello, World!");
来源：http://dali.cheryme.top/Article/details/gt2ssqwuarx.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.ppjwa.cn/Article/details/gt2vwbqjsuj.html

Ruby: puts "Hello, World!"
来源：http://dali.sxryk.cn/Article/details/gt2rdtqdwms.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.0kj1m.cn/Article/details/gt2sigyqrpk.html

[A02] 变量声明与赋值
来源：http://dali.zhongyouzk.top/Article/details/gt2uohsfczb.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.tian-w.cn/Article/details/gt2hocltxcm.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zdqjudy.top/Article/details/gt2laetzzla.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2plzjotbb.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.cheryme.top/Article/details/gt2ygkropmp.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yj20258.top/Article/details/gt2oejucjwm.html

Go:   name := "Alex"; age := 20
来源：http://dali.sysykeji.top/Article/details/gt2gssxkaqf.html

Ruby: name = "Alex"; age = 20
来源：http://dali.nanxinkj.top/Article/details/gt2avahbvek.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhiwuduotai.top/Article/details/gt2konufuyv.html

[A03] 常量定义
来源：http://dali.nwbrower.top/Article/details/gt2ipnruocb.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.fzhhl.top/Article/details/gt2kprlrofc.html

PHP:  const PI = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gt2wvjjkztv.html

JS:   const PI = 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gt2faxalfow.html

TS:   const PI: number = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gt2idyuehwo.html

Java: static final double PI = 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gt2oqfripwc.html

Go:   const PI = 3.14159
来源：http://dali.jlsjyb.cn/Article/details/gt2ghlrgnnp.html

Ruby: PI = 3.14159
来源：http://dali.pycfn.com/Article/details/gt2fatedvhm.html

C#:   const double PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gt2ddhezwmd.html

[A04] 判断变量类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2trtcnoli.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jinqigufen.top/Article/details/gt2hbbchbjw.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yangfankeji.com/Article/details/gt2leiajnex.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.iojbl.cn/Article/details/gt2dlzszdgf.html

TS:   typeof x; x instanceof Date
来源：http://dali.jinqigufen.top/Article/details/gt2qolsrnpc.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.chenzaomai.com/Article/details/gt2qmokhyyr.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.shuidangran.top/Article/details/gt2khccmeqe.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ivkxftsw.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhengqikj.top/Article/details/gt2ukgkdnmd.html

[A05] 整数除法与取模
来源：http://dali.sysykeji.top/Article/details/gt2hmvdwbls.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.xziqi.cn/Article/details/gt2eklhmwiu.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.vqdsnc.cn/Article/details/gt2vvfewopf.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gt2qaqlsuox.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gt2hvcswbkw.html

Java: 7 / 2; 7 % 2
来源：http://dali.jinqigufen.top/Article/details/gt2dksaflqe.html

Go:   7 / 2; 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gt2vxmbjlhd.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.sysykeji.top/Article/details/gt2mqcphqsd.html

C#:   7 / 2; 7 % 2
来源：http://dali.feifeiyinyue.top/Article/details/gt2tbrsxnum.html

[A06] 字符串转数字
来源：http://dali.hysaishi.cn/Article/details/gt2kljmwnxx.html

Py:   int("42"); float("3.14")
来源：http://dali.chenlongwang.top/Article/details/gt2cympyirj.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.pycfn.com/Article/details/gt2cfhreelx.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yangfankeji.com/Article/details/gt2etyrhfzk.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.guannengcc.top/Article/details/gt2zzimcevr.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.316326.xyz/Article/details/gt2foyiccjc.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yvedp.cn/Article/details/gt2lbxumzio.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhixingplan.top/Article/details/gt2ncvbxdhr.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ccwatcjr.html

[A07] 数字转字符串
来源：http://dali.fengsongda.top/Article/details/gt2rpogjudz.html

Py:   str(42)
来源：http://dali.316326.xyz/Article/details/gt2fkvqjhdd.html

PHP:  (string) 42; strval(42)
来源：http://dali.chenzaomai.com/Article/details/gt2lssxavwm.html

JS:   String(42); (42).toString()
来源：http://dali.zhoulong.xyz/Article/details/gt2ekecmphk.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2uggsuapp.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.chenzaomai.com/Article/details/gt2dhdfqmoc.html

Go:   strconv.Itoa(42)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qmklwvuv.html

Ruby: 42.to_s
来源：http://dali.sufxvd.cn/Article/details/gt2pwecixjf.html

C#:   42.ToString()
来源：http://dali.ybcxt.top/Article/details/gt2fcztrqkm.html

[A08] 取整与四舍五入
来源：http://dali.ydzc1.top/Article/details/gt2uxurykrm.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.quarkkingdee.top/Article/details/gt2fizdgovq.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wlqmjbez.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhoulong.xyz/Article/details/gt2ehlloloh.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.kuanghao11.cn/Article/details/gt2djfaccny.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.hnqzz.top/Article/details/gt2antkqxaq.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.sweek.top/Article/details/gt2xphsaznl.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yuanzhike.top/Article/details/gt2vhutavbv.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ftodcywg.html

[A09] 绝对值与最大最小值
来源：http://dali.tian-w.cn/Article/details/gt2aukejjag.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2uwnqjehn.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.nanxinkj.top/Article/details/gt2zmkrqsza.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2jkazydwy.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.smart0.xyz/Article/details/gt2finysdsj.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.birdmap.top/Article/details/gt2cvwvoout.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.sweek.top/Article/details/gt2gncldqiv.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zdqjudy.top/Article/details/gt2ketsocxu.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2ipgxxhvl.html

[A10] 生成随机数
来源：http://dali.xuanzx.com/Article/details/gt2sgjermhf.html

Py:   import random; random.randint(1, 100)
来源：http://dali.xuanzx.com/Article/details/gt2lpgwtqwk.html

PHP:  random_int(1, 100);
来源：http://dali.nwbrower.top/Article/details/gt2coyzepjg.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.havefunace.top/Article/details/gt2smbfqxfr.html


<!-- 参考信息 -->