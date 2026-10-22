代发 wailian999

[U69] PHP：PDO 预处理
来源：http://dali.pycfn.com/Article/details/gt2iwgxskde.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.gotoacloud.top/Article/details/gt2hkzeytpi.html

[U70] PHP：PDO 事务
来源：http://dali.cucudq.cn/Article/details/gt2vaqmmbii.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.mhx1999.top/Article/details/gt2iirpzuva.html

[U71] PHP：抛出异常
来源：http://dali.kuanghao11.cn/Article/details/gt2ldlcqawx.html

throw new RuntimeException("失败", 500);
来源：http://dali.cdnleiting.top/Article/details/gt2ticqijuk.html

[U72] PHP：写错误日志
来源：http://dali.snrcjt.cn/Article/details/gt2mgfcbtdu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.sweek.top/Article/details/gt2hdskpcji.html

[U73] PHP：读取 ini 配置
来源：http://dali.daxiang520.top/Article/details/gt2ruhzqfhy.html

parse_ini_file("config.ini", true)
来源：http://dali.yanxiufei.cn/Article/details/gt2uzhniqbv.html

[U74] PHP：读取环境变量
来源：http://dali.bjfxy.top/Article/details/gt2rsogfkec.html

getenv("APP_ENV") ?: "production"
来源：http://dali.mhx1999.top/Article/details/gt2tbjmliwi.html

[U75] PHP：依赖注入
来源：http://dali.wangshuangyany.cn/Article/details/gt2mozulhrf.html

composer require psr/container
来源：http://dali.pycfn.com/Article/details/gt2ljhebxey.html

[U76] PHP：简单路由
来源：http://dali.yangfankeji.com/Article/details/gt2jauawkgn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.wangdashe.top/Article/details/gt2ffttziwg.html

[U77] PHP：模板渲染
来源：http://dali.jiagoushi.top/Article/details/gt2viiqcmuv.html

composer require twig/twig
来源：http://dali.tanke756.top/Article/details/gt2eagsjrdd.html

[U78] PHP：单元测试
来源：http://dali.daxiang520.top/Article/details/gt2khhpsgay.html

composer require --dev phpunit/phpunit
来源：http://dali.zycfv.cn/Article/details/gt2uluxufzq.html

[U79] PHP：静态分析
来源：http://dali.aibaodan.cn/Article/details/gt2obbfmphx.html

composer require --dev phpstan/phpstan
来源：http://dali.zhengqikj.top/Article/details/gt2ztxghfjc.html

[U80] PHP：代码规范修复
来源：http://dali.316326.xyz/Article/details/gt2oevjpmkx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.hywenlv.cn/Article/details/gt2hbdjbndg.html

[U81] JS：初始化项目
来源：http://dali.jlsjyb.cn/Article/details/gt2szeupdpm.html

npm init -y;  npm i express
来源：http://dali.yj20258888.top/Article/details/gt2temjypuc.html

[U82] JS：package.json 脚本
来源：http://dali.hysaishi.cn/Article/details/gt2ydmgsdfp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.birdmap.top/Article/details/gt2hnxgnzyv.html

[U83] JS：ES Module 导入导出
来源：http://dali.hongshengwenyu.top/Article/details/gt2rbrwcywa.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.kuanghao11.cn/Article/details/gt2tkqvbcsb.html

[U84] JS：CommonJS 写法
来源：http://dali.guowangkeji.top/Article/details/gt2fsyhgejw.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.xziqi.cn/Article/details/gt2ytzmrzqy.html

[U85] JS：可选链
来源：http://dali.chenjidiqi.icu/Article/details/gt2hdziiyxz.html

a?.b?.c
来源：http://dali.zhoulong.xyz/Article/details/gt2aojfcxha.html

[U86] JS：空值合并
来源：http://dali.aibaodan.cn/Article/details/gt2jixabvug.html

a ?? b
来源：http://dali.meibo888.top/Article/details/gt2oqrdezqh.html

[U87] JS：解构默认值
来源：http://dali.chenzaomai.com/Article/details/gt2crgfggxf.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jianghu66.top/Article/details/gt2hpmxjdts.html

[U88] JS：对象展开合并
来源：http://dali.tianlin.xyz/Article/details/gt2rhuqacjb.html

{ ...a, ...b }
来源：http://dali.zhongyouzk.top/Article/details/gt2gpezrprm.html

[U89] JS：数组去重
来源：http://dali.yvedp.cn/Article/details/gt2uwymodml.html

[...new Set(arr)]
来源：http://dali.wangdashe.top/Article/details/gt2xwsghzes.html

[U90] JS：数字数组排序
来源：http://dali.shuidangran.top/Article/details/gt2ssktjmnt.html

[...arr].sort((a, b) => a - b)
来源：http://dali.ybcxt.top/Article/details/gt2koivgyzs.html

[U91] JS：对象键值遍历
来源：http://dali.nwbrower.top/Article/details/gt2uggbarqb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhongyouzk.top/Article/details/gt2lzsniwmm.html

[U92] JS：深拷贝
来源：http://dali.fzhhl.top/Article/details/gt2xdtvhijv.html

structuredClone(obj)
来源：http://dali.meibo888.top/Article/details/gt2rnadauiv.html

[U93] JS：模板字符串
来源：http://dali.guowangkeji.top/Article/details/gt2kjetprqh.html

`共 ${n} 条`
来源：http://dali.xuanzx.com/Article/details/gt2tnsmcsrw.html

[U94] JS：箭头函数
来源：http://dali.0kj1m.cn/Article/details/gt2suaqfvub.html

const double = x => x * 2;
来源：http://dali.jqgfzy.top/Article/details/gt2sbiqkugy.html

[U95] JS：Promise 包装
来源：http://dali.yuanzhike.top/Article/details/gt2xcatspje.html

new Promise((resolve, reject) => {})
来源：http://dali.kuanghao11.cn/Article/details/gt2gwcqtgaq.html

[U96] JS：async/await 与异常
来源：http://dali.0kj1m.cn/Article/details/gt2jsydkjcy.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gt2qnntglnf.html

[U97] JS：并发请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zerrxlyf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gt2dfogyxcv.html

[U98] JS：fetch 带 JSON
来源：http://dali.yonumen.top/Article/details/gt2ddmjhmfz.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.aibaodan.cn/Article/details/gt2utoylgby.html

[U99] JS：事件监听
来源：http://dali.fengsongda.top/Article/details/gt2ufokgjfg.html

el.addEventListener("click", e => {})
来源：http://dali.meibo888.top/Article/details/gt2jwzdpdaq.html

[U100] JS：DOM 查询
来源：http://dali.zhiwuduotai.top/Article/details/gt2ktcjiiqx.html

document.querySelector(".item")
来源：http://dali.sysykeji.top/Article/details/gt2qmzcvpye.html

[U101] JS：classList 操作
来源：http://dali.havefunace.top/Article/details/gt2lxsfnbea.html

el.classList.toggle("active")
来源：http://dali.hnxiangtu.top/Article/details/gt2wrghrllo.html

[U102] JS：本地存储
来源：http://dali.haohaochexian.top/Article/details/gt2pslbmxhm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.guowangkeji.top/Article/details/gt2jwqmsbng.html

[U103] JS：定时器
来源：http://dali.redwolf501.top/Article/details/gt2epymldkz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.tian-w.cn/Article/details/gt2lekvswzk.html

[U104] JS：防抖
来源：http://dali.meibo888.top/Article/details/gt2rfoxvhpp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258888.top/Article/details/gt2mqrhtcni.html

[U105] JS：节流
来源：http://dali.ybcxt.top/Article/details/gt2cplypgxk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.pycfn.com/Article/details/gt2jqdouzga.html

[U106] JS：日期格式化
来源：http://dali.nwbrower.top/Article/details/gt2fvqhetnf.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jiagoushi.top/Article/details/gt2qzrqkveq.html

[U107] JS：数字千分位
来源：http://dali.jqgufenzy.top/Article/details/gt2fdykzegd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.9152youxi.cn/Article/details/gt2qtsbdqrs.html

[U108] JS：随机整数
来源：http://dali.yanxiufei.cn/Article/details/gt2nixdznmh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.nanxinkj.top/Article/details/gt2vcccfiiy.html

[U109] JS：数组分组
来源：http://dali.ppjwa.cn/Article/details/gt2sbegbosn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.daria6918.cn/Article/details/gt2wxtkzivn.html

[U110] JS：数组分块
来源：http://dali.mhx1999.top/Article/details/gt2nisqewzi.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.redwolf501.top/Article/details/gt2nicqjhwz.html

[U111] JS：对象转 Map
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wtyolzcb.html

new Map(Object.entries(obj))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uadphrqq.html

[U112] JS：字符串补位
来源：http://dali.tian-w.cn/Article/details/gt2whfvxtax.html

"7".padStart(3, "0")
来源：http://dali.havefunace.top/Article/details/gt2kkhxtxmu.html

[U113] JS：正则替换全部
来源：http://dali.wangdashe.top/Article/details/gt2cldjmouk.html

s.replaceAll("a", "b")
来源：http://dali.andypj.xyz/Article/details/gt2dgtjftza.html

[U114] JS：JSON 深比较
来源：http://dali.vqdsnc.cn/Article/details/gt2ekobajoa.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hfpthk.cn/Article/details/gt2ldkcjqro.html

[U115] JS：生成 UUID
来源：http://dali.bjfxy.top/Article/details/gt2hdxjsknm.html

crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gt2nvvikkuj.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2skjjzhfj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.0kj1m.cn/Article/details/gt2lmzrwwxo.html

[U117] JS：单元测试
来源：http://dali.dianchejie.cn/Article/details/gt2iliubqvd.html

npm i -D vitest;  npx vitest
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ghfmqhei.html

[U118] JS：开发服务器
来源：http://dali.yangfankeji.com/Article/details/gt2ylqlhodh.html

npm i -D vite;  npx vite
来源：http://dali.ydzc1.top/Article/details/gt2gmcrdjzc.html

[U119] JS：生产构建
来源：http://dali.sysykeji.top/Article/details/gt2sjgaockg.html

npx vite build
来源：http://dali.guowangkeji.top/Article/details/gt2axvpylih.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.fengsongda.top/Article/details/gt2xoskqxax.html

import.meta.env.VITE_API_URL
来源：http://dali.gaohongyu789.top/Article/details/gt2xjschbxi.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2fvcacgrj.html

统计汇总
来源：http://dali.hysaishi.cn/Article/details/gt2ahvrrzuq.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2dhtmigos.html

按语言统计（条）：
来源：http://dali.yj20258888.top/Article/details/gt2tnllhkvf.html

Python ......... 252
来源：http://dali.quarkkingdee.top/Article/details/gt2ylcxmoft.html

PHP ............ 252
来源：http://dali.kuanghao11.cn/Article/details/gt2heultbta.html

JavaScript ..... 252
来源：http://dali.tianlin.xyz/Article/details/gt2eghnybpv.html

TypeScript ..... 212
来源：http://dali.mhx1999.top/Article/details/gt2jtoocnnk.html

Java ........... 212
来源：http://dali.chenzaomai.com/Article/details/gt2hsfsggrs.html

Go ............. 212
来源：http://dali.smart0.xyz/Article/details/gt2hdzijgur.html

Ruby ........... 212
来源：http://dali.daxiang520.top/Article/details/gt2rickrxzq.html

C# ............. 212
来源：http://dali.shangyingyoupin.top/Article/details/gt2inutufeg.html

C .............. 30
来源：http://dali.redwolf501.top/Article/details/gt2pgjbzjof.html

C++ ............ 30
来源：http://dali.sxryk.cn/Article/details/gt2gwawjfoi.html

SQL ............ 90
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vldyulcw.html

Bash ........... 80
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pjmpvelq.html

Kotlin ......... 15
来源：http://dali.tanke756.top/Article/details/gt2wqfvclge.html

Swift .......... 15
来源：http://dali.zhengqikj.top/Article/details/gt2eqzpznoh.html

Lua ............ 10
来源：http://dali.yongpay.top/Article/details/gt2dbpspnga.html

Perl ........... 10
来源：http://dali.xuetiantiany.cn/Article/details/gt2mdjsltlr.html

Scala .......... 10
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dnpyvsmc.html

------------------------------------
来源：http://dali.snrcjt.cn/Article/details/gt2zghqfxcr.html

合计 ........... 2106 条
来源：http://dali.c1oappe.top/Article/details/gt2ealawnfh.html

按章节统计：
来源：http://dali.jlsjyb.cn/Article/details/gt2lxahyglj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhongyouzk.top/Article/details/gt2nirhuixi.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.cqqwz.cn/Article/details/gt2nxsfmhau.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.pycfn.com/Article/details/gt2oosxkpqc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.ydzc1.top/Article/details/gt2zamezkwe.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yj20258.top/Article/details/gt2xnnkyjbb.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.ppjwa.cn/Article/details/gt2zuhepbfo.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.shangyingyoupin.top/Article/details/gt2ujqmggys.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.aizwys.cn/Article/details/gt2pzwvgrrq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.c1oappe.top/Article/details/gt2swbbxcfu.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jiagoushi.top/Article/details/gt2gmdockyh.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yuanzhike.top/Article/details/gt2hlsxsfxj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.pycfn.com/Article/details/gt2kwkkrbfi.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.cucudq.cn/Article/details/gt2hwupjktt.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.cdnleiting.top/Article/details/gt2rwawonez.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.wangshuangyany.cn/Article/details/gt2tlbfcymr.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ydzc1.top/Article/details/gt2zkzfzixf.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgkwvns.html

R Bash 专题                             80
来源：http://dali.yueranfly.top/Article/details/gt2tadxqlvn.html

S C / C++ 专题                          60
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cwqlgxja.html

T 其他语言补充                          60
来源：http://dali.ppjwa.cn/Article/details/gt2vovyzkfi.html

U 高频实用片段                         120
来源：http://dali.tian-w.cn/Article/details/gt2qmknpebo.html

------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gt2wvizqzxb.html

合计                                  2106 条
来源：http://dali.quarkkingdee.top/Article/details/gt2kckwpkar.html

--------------------------------------------------------------------------------
来源：http://dali.yj202588.top/Article/details/gt2fkukbzmp.html

使用提醒
来源：http://dali.havefunace.top/Article/details/gt2zhzfyscd.html

--------------------------------------------------------------------------------
来源：http://dali.jianghu66.top/Article/details/gt2cujtxqve.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.dashuyun.cn/Article/details/gt2ufmnreto.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hnqzz.top/Article/details/gt2fkipajyd.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jyoumei.cn/Article/details/gt2sraoiygi.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hongshengwenyu.top/Article/details/gt2trsaxepi.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.mhx1999.top/Article/details/gt2iocewjkc.html

—— 文件结束 ——
来源：http://dali.yuanzhike.top/Article/details/gt2hlfohqrc.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2qvsdyepo.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.316326.xyz/Article/details/gt2lsrheddn.html

Common Programming Examples Cheat Book
来源：http://dali.xziqi.cn/Article/details/gt2vprriwko.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2somzrfaj.html

【收录内容】
来源：http://dali.zhiwuduotai.top/Article/details/gt2znhdjuhj.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.redwolf501.top/Article/details/gt2xjkgdvqz.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.daxiang520.top/Article/details/gt2qpyaagfo.html

SQL · Bash · C · C++
来源：http://dali.gotoacloud.top/Article/details/gt2fgsvzfod.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yj202588.top/Article/details/gt2sphoxbqo.html

【使用说明】
来源：http://dali.guannengcc.top/Article/details/gt2zzqlaaam.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.sysykeji.top/Article/details/gt2vtklxihr.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.chenjidiqi.icu/Article/details/gt2uviylgru.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.gzhubu.top/Article/details/gt2uahucqit.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.hongshengwenyu.top/Article/details/gt2axwwgard.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tqkjypfh.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.9152youxi.cn/Article/details/gt2dubewqdj.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.chenlongwang.top/Article/details/gt2fkxpcpzi.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yongpay.top/Article/details/gt2nfwjrhib.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yangfankeji.com/Article/details/gt2qksktsys.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jinqigfzy.top/Article/details/gt2sfujbidy.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hysaishi.cn/Article/details/gt2hovvgdzu.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.wangdashe.top/Article/details/gt2mqymbntq.html

【文件统计】
来源：http://dali.yangfankeji.com/Article/details/gt2zxhnyqca.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.vqdsnc.cn/Article/details/gt2lqzbykeq.html

--------------------------------------------------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gt2yhmuadqq.html

目  录
来源：http://dali.cucudq.cn/Article/details/gt2ixhxqhkl.html

--------------------------------------------------------------------------------
来源：http://dali.fengsongda.top/Article/details/gt2endkfzoh.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.birdmap.top/Article/details/gt2spahbqmd.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.cqqwz.cn/Article/details/gt2lhaauhap.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jianghu66.top/Article/details/gt2eqwsdpth.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.gzhubu.top/Article/details/gt2dypjbdas.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.xinyue.icu/Article/details/gt2ujfdeflx.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2umfkmrqy.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2pxxtfwys.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.aizwys.cn/Article/details/gt2pmewutea.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.bjfxy.top/Article/details/gt2hdrjfkdo.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.guowangkeji.top/Article/details/gt2enditsjh.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jqgfzy.top/Article/details/gt2roafewqp.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yonumen.top/Article/details/gt2btdrewef.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.chenlongwang.top/Article/details/gt2fdmsnqdc.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.ybcxt.top/Article/details/gt2nuwhqnyc.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yvedp.cn/Article/details/gt2yrrncffg.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.cdnleiting.top/Article/details/gt2lanusssd.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.smart0.xyz/Article/details/gt2cxzxixqm.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.xuanzx.com/Article/details/gt2sleomtay.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhongyouzk.top/Article/details/gt2anbedjlu.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ceieatzk.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.sweek.top/Article/details/gt2yzjvgowz.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2euxsklxn.html

A. 基础语法与类型
来源：http://dali.daria6918.cn/Article/details/gt2keixdzun.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2edxkhcjj.html

[A01] Hello World
来源：http://dali.aizwys.cn/Article/details/gt2gakbjvgm.html

Py:   print("Hello, World!")
来源：http://dali.hywenlv.cn/Article/details/gt2nhtpmbad.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2kwskftzx.html

JS:   console.log("Hello, World!");
来源：http://dali.sysykeji.top/Article/details/gt2xrhuvjmr.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.xylfe.cn/Article/details/gt2ibshprcx.html

Java: System.out.println("Hello, World!");
来源：http://dali.shuidangran.top/Article/details/gt2mdctoort.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.sysykeji.top/Article/details/gt2kverxsyt.html

Ruby: puts "Hello, World!"
来源：http://dali.gaohongyu789.top/Article/details/gt2lrkzmsbx.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.chenzaomai.com/Article/details/gt2wdtbovye.html

[A02] 变量声明与赋值
来源：http://dali.wangshuangyany.cn/Article/details/gt2bseujpur.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.bjfxy.top/Article/details/gt2bybutmpu.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yj20258.top/Article/details/gt2vicwrpkt.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.cheryme.top/Article/details/gt2pdqlfrba.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.gogol.net.cn/Article/details/gt2kneqzvap.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yueranfly.top/Article/details/gt2lmbdunfo.html

Go:   name := "Alex"; age := 20
来源：http://dali.c1oappe.top/Article/details/gt2frldpjvt.html

Ruby: name = "Alex"; age = 20
来源：http://dali.chenzaomai.com/Article/details/gt2wzwktubn.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.ppjwa.cn/Article/details/gt2awnwgqdo.html

[A03] 常量定义
来源：http://dali.chenlongwang.top/Article/details/gt2ewvzndol.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.daria6918.cn/Article/details/gt2aytalpnk.html

PHP:  const PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gt2jubckdsq.html

JS:   const PI = 3.14159;
来源：http://dali.yj202588.top/Article/details/gt2boybiodu.html

TS:   const PI: number = 3.14159;
来源：http://dali.iojbl.cn/Article/details/gt2mkmkkevr.html

Java: static final double PI = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gt2fdldydgd.html

Go:   const PI = 3.14159
来源：http://dali.dianchejie.cn/Article/details/gt2ydakywiu.html

Ruby: PI = 3.14159
来源：http://dali.yuxming.cn/Article/details/gt2brcrpqwm.html

C#:   const double PI = 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gt2bcxcrhhm.html

[A04] 判断变量类型
来源：http://dali.ehwqpu.com/Article/details/gt2hlojulbq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yonumen.top/Article/details/gt2femtihjg.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.ppjwa.cn/Article/details/gt2oxaynrkh.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.pycfn.com/Article/details/gt2blegeoaz.html

TS:   typeof x; x instanceof Date
来源：http://dali.ivvv.top/Article/details/gt2diqzqfjf.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.kuanghao11.cn/Article/details/gt2bkldzpqt.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.dianchejie.cn/Article/details/gt2xkrqmxhw.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yj20258888.top/Article/details/gt2rbvjhmox.html

C#:   x.GetType().Name; x is int
来源：http://dali.yj20258888.top/Article/details/gt2dgfmhqib.html

[A05] 整数除法与取模
来源：http://dali.xinyue.icu/Article/details/gt2bxvozcld.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhoulong.xyz/Article/details/gt2ucjqzoed.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gt2gfkdyugd.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gt2fwfvtqqs.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zycfv.cn/Article/details/gt2vwrzavxm.html

Java: 7 / 2; 7 % 2
来源：http://dali.kuanghao11.cn/Article/details/gt2vvgpjysh.html

Go:   7 / 2; 7 % 2
来源：http://dali.xinyue.icu/Article/details/gt2fktzlkzc.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yonumen.top/Article/details/gt2xtfdgbgq.html

C#:   7 / 2; 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gt2zbmujxze.html

[A06] 字符串转数字
来源：http://dali.316326.xyz/Article/details/gt2qkocvykc.html

Py:   int("42"); float("3.14")
来源：http://dali.shuidangran.top/Article/details/gt2aeyxuzcf.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhongyouzk.top/Article/details/gt2kwxjpdna.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.andypj.xyz/Article/details/gt2vdgpczqj.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lxwmxcrm.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.chenlongwang.top/Article/details/gt2tirzipkx.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.ybcxt.top/Article/details/gt2vhqwtfsu.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.dianchejie.cn/Article/details/gt2nlccuwje.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.fengsongda.top/Article/details/gt2dcmjlvkw.html

[A07] 数字转字符串
来源：http://dali.yongpay.top/Article/details/gt2ruaglkdj.html

Py:   str(42)
来源：http://dali.svipenyu.cn/Article/details/gt2mziityts.html

PHP:  (string) 42; strval(42)
来源：http://dali.jqgfzy.top/Article/details/gt2lusheybf.html

JS:   String(42); (42).toString()
来源：http://dali.jianghu66.top/Article/details/gt2fqevhvdk.html

TS:   String(42)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mqstzviz.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.hongshengwenyu.top/Article/details/gt2igpqiavh.html

Go:   strconv.Itoa(42)
来源：http://dali.cqqwz.cn/Article/details/gt2vzowppqk.html

Ruby: 42.to_s
来源：http://dali.jyoumei.cn/Article/details/gt2nvukwzwq.html

C#:   42.ToString()
来源：http://dali.tianlin.xyz/Article/details/gt2hjyaozvq.html

[A08] 取整与四舍五入
来源：http://dali.yongpay.top/Article/details/gt2vfmfvprc.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.ydzc1.top/Article/details/gt2ksghneax.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sgaumzzi.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cjtgaomy.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.ybcxt.top/Article/details/gt2yqrsvasw.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yvedp.cn/Article/details/gt2zpouyjrw.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uphzqtwv.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.xylfe.cn/Article/details/gt2mlsmchdn.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.hywenlv.cn/Article/details/gt2pnaxvjgq.html

[A09] 绝对值与最大最小值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gvozbaka.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.fengsongda.top/Article/details/gt2famuurvs.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.andypj.xyz/Article/details/gt2gcrbawdd.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.dianchejie.cn/Article/details/gt2ixmrkptf.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.316326.xyz/Article/details/gt2hrkmrvhg.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.wangdashe.top/Article/details/gt2kxsmmfpv.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jyoumei.cn/Article/details/gt2nknvjkut.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.sufxvd.cn/Article/details/gt2yyqnxovc.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kennrfix.html

[A10] 生成随机数
来源：http://dali.daxiang520.top/Article/details/gt2bwkbsexm.html

Py:   import random; random.randint(1, 100)
来源：http://dali.iojbl.cn/Article/details/gt2uuoubhgb.html

PHP:  random_int(1, 100);
来源：http://dali.jyoumei.cn/Article/details/gt2emiaqrao.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.guannengcc.top/Article/details/gt2dtnjeaks.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.cashguo.top/Article/details/gt2qoheqxoo.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yonumen.top/Article/details/gt2yxetoree.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.nanxuanxn.top/Article/details/gt2iraufnvt.html

Ruby: rand(1..100)
来源：http://dali.0kj1m.cn/Article/details/gt2oksnskih.html


<!-- 参考信息 -->