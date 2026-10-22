代发 wailian999

[U67] PHP：处理文件上传
来源：http://dali.birdmap.top/Article/details/gt2dogsawfr.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.xziqi.cn/Article/details/gt2lvkegkwd.html

[U68] PHP：PDO 连接
来源：http://dali.bjfxy.top/Article/details/gt2mutyisjp.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.bjfxy.top/Article/details/gt2tfatzkxt.html

[U69] PHP：PDO 预处理
来源：http://dali.daria6918.cn/Article/details/gt2qpoymveu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.sufxvd.cn/Article/details/gt2atkvsxhm.html

[U70] PHP：PDO 事务
来源：http://dali.aizwys.cn/Article/details/gt2woxnrtbo.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.aibaodan.cn/Article/details/gt2htupiqbr.html

[U71] PHP：抛出异常
来源：http://dali.hfpthk.cn/Article/details/gt2tkipycor.html

throw new RuntimeException("失败", 500);
来源：http://dali.jqgufenzy.top/Article/details/gt2ayuxeees.html

[U72] PHP：写错误日志
来源：http://dali.ivvv.top/Article/details/gt2szewbgng.html

error_log("失败: " . $e->getMessage());
来源：http://dali.sufxvd.cn/Article/details/gt2cygtjovw.html

[U73] PHP：读取 ini 配置
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nmmdkjqm.html

parse_ini_file("config.ini", true)
来源：http://dali.nwbrower.top/Article/details/gt2jmkspgmd.html

[U74] PHP：读取环境变量
来源：http://dali.yj20258.top/Article/details/gt2albwejhv.html

getenv("APP_ENV") ?: "production"
来源：http://dali.shzxlz.cn/Article/details/gt2dazjhtog.html

[U75] PHP：依赖注入
来源：http://dali.nanxinkj.top/Article/details/gt2wquhuekg.html

composer require psr/container
来源：http://dali.ybcxt.top/Article/details/gt2tcxkggqq.html

[U76] PHP：简单路由
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2znlkqbbv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhengqikj.top/Article/details/gt2mcrbzzyc.html

[U77] PHP：模板渲染
来源：http://dali.xziqi.cn/Article/details/gt2txtdrzlp.html

composer require twig/twig
来源：http://dali.jlsjyb.cn/Article/details/gt2chhkwdnl.html

[U78] PHP：单元测试
来源：http://dali.nwbrower.top/Article/details/gt2jtmrbixu.html

composer require --dev phpunit/phpunit
来源：http://dali.yj20258.top/Article/details/gt2upvxbqmu.html

[U79] PHP：静态分析
来源：http://dali.jqgfzy.top/Article/details/gt2lvyvwvii.html

composer require --dev phpstan/phpstan
来源：http://dali.ppjwa.cn/Article/details/gt2olzcagqj.html

[U80] PHP：代码规范修复
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fyyxickn.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.sysykeji.top/Article/details/gt2xlcbpebq.html

[U81] JS：初始化项目
来源：http://dali.ppjwa.cn/Article/details/gt2jmxvvirm.html

npm init -y;  npm i express
来源：http://dali.gaohongyu789.top/Article/details/gt2trquqtjh.html

[U82] JS：package.json 脚本
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zjmksqdg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.wangshuangyany.cn/Article/details/gt2mdronawl.html

[U83] JS：ES Module 导入导出
来源：http://dali.zycfv.cn/Article/details/gt2kyqejbde.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.daxiang520.top/Article/details/gt2iblsnpwv.html

[U84] JS：CommonJS 写法
来源：http://dali.yuxming.cn/Article/details/gt2urvhginq.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hongshengwenyu.top/Article/details/gt2nmsnbrdr.html

[U85] JS：可选链
来源：http://dali.gotoacloud.top/Article/details/gt2xpdcmwdr.html

a?.b?.c
来源：http://dali.vqdsnc.cn/Article/details/gt2xqcnuxxc.html

[U86] JS：空值合并
来源：http://dali.birdmap.top/Article/details/gt2xbwlbyee.html

a ?? b
来源：http://dali.zhixingplan.top/Article/details/gt2eyymnfvh.html

[U87] JS：解构默认值
来源：http://dali.yj20258888.top/Article/details/gt2anmpqnze.html

const { a = 1, b = 2 } = obj;
来源：http://dali.ybcxt.top/Article/details/gt2lcyvoday.html

[U88] JS：对象展开合并
来源：http://dali.chenjidiqi.icu/Article/details/gt2qxzpvrro.html

{ ...a, ...b }
来源：http://dali.fzhhl.top/Article/details/gt2mtdxwumv.html

[U89] JS：数组去重
来源：http://dali.316326.xyz/Article/details/gt2zoqitjcq.html

[...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gt2beoxjbdw.html

[U90] JS：数字数组排序
来源：http://dali.yj20258888.top/Article/details/gt2imfmsyqb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vbqpirsx.html

[U91] JS：对象键值遍历
来源：http://dali.zhongyouzk.top/Article/details/gt2gvnuiaof.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yangfankeji.com/Article/details/gt2xcuosxea.html

[U92] JS：深拷贝
来源：http://dali.quarkkingdee.top/Article/details/gt2talhgcph.html

structuredClone(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2aicyzgkf.html

[U93] JS：模板字符串
来源：http://dali.jqgfzy.top/Article/details/gt2ymvhkwdj.html

`共 ${n} 条`
来源：http://dali.dianchejie.cn/Article/details/gt2vafhrbpl.html

[U94] JS：箭头函数
来源：http://dali.chenzaomai.com/Article/details/gt2xgqlbafs.html

const double = x => x * 2;
来源：http://dali.chenjidiqi.icu/Article/details/gt2nmysjabv.html

[U95] JS：Promise 包装
来源：http://dali.yongpay.top/Article/details/gt2wygqazhj.html

new Promise((resolve, reject) => {})
来源：http://dali.gaohongyu789.top/Article/details/gt2vqyfzshn.html

[U96] JS：async/await 与异常
来源：http://dali.cheryme.top/Article/details/gt2qlmmnpif.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gt2vzmcsqis.html

[U97] JS：并发请求
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2niborgwl.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gt2fyprdqmz.html

[U98] JS：fetch 带 JSON
来源：http://dali.yonumen.top/Article/details/gt2rpsqgfbl.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.fengsongda.top/Article/details/gt2hneovtpa.html

[U99] JS：事件监听
来源：http://dali.zhixingplan.top/Article/details/gt2xkfdqlfn.html

el.addEventListener("click", e => {})
来源：http://dali.jiagoushi.top/Article/details/gt2eddbclms.html

[U100] JS：DOM 查询
来源：http://dali.zhiwuduotai.top/Article/details/gt2nqvwqjls.html

document.querySelector(".item")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ldizgxjp.html

[U101] JS：classList 操作
来源：http://dali.ydzc1.top/Article/details/gt2rlvzqudy.html

el.classList.toggle("active")
来源：http://dali.tanke756.top/Article/details/gt2udppfuqq.html

[U102] JS：本地存储
来源：http://dali.yj20258888.top/Article/details/gt2qrrkezrh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yonumen.top/Article/details/gt2jtvhyous.html

[U103] JS：定时器
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kwwsczpt.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.pycfn.com/Article/details/gt2nwdbpeqm.html

[U104] JS：防抖
来源：http://dali.shangyingyoupin.top/Article/details/gt2yukuaxyv.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuxming.cn/Article/details/gt2gaiwdreo.html

[U105] JS：节流
来源：http://dali.jqgfzy.top/Article/details/gt2mtrctaxi.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jyoumei.cn/Article/details/gt2ccsfycrx.html

[U106] JS：日期格式化
来源：http://dali.fzhhl.top/Article/details/gt2tjbktumv.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yonumen.top/Article/details/gt2ulppaics.html

[U107] JS：数字千分位
来源：http://dali.tanke756.top/Article/details/gt2opgunvys.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhixingplan.top/Article/details/gt2trbbpjfo.html

[U108] JS：随机整数
来源：http://dali.jlsjyb.cn/Article/details/gt2sugdvdqh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uwxhtdyl.html

[U109] JS：数组分组
来源：http://dali.sweek.top/Article/details/gt2jnvstbyj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hemmdniv.html

[U110] JS：数组分块
来源：http://dali.nwbrower.top/Article/details/gt2pwjodqax.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhongyouzk.top/Article/details/gt2krpyxawi.html

[U111] JS：对象转 Map
来源：http://dali.dianchejie.cn/Article/details/gt2ohjgaurk.html

new Map(Object.entries(obj))
来源：http://dali.andypj.xyz/Article/details/gt2hsmlkgik.html

[U112] JS：字符串补位
来源：http://dali.fengsongda.top/Article/details/gt2iebhewut.html

"7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gt2fyxbidyb.html

[U113] JS：正则替换全部
来源：http://dali.gaohongyu789.top/Article/details/gt2adkmlqvk.html

s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2wortnhxn.html

[U114] JS：JSON 深比较
来源：http://dali.iojbl.cn/Article/details/gt2hjfazxdx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gogol.net.cn/Article/details/gt2uhcbcsqi.html

[U115] JS：生成 UUID
来源：http://dali.kuanghao11.cn/Article/details/gt2hxvudvtf.html

crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gt2tbrynvln.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pzhzqkap.html

/** @param {string} name */ function f(name) {}
来源：http://dali.cqqwz.cn/Article/details/gt2rjztjojk.html

[U117] JS：单元测试
来源：http://dali.316326.xyz/Article/details/gt2akbbfaye.html

npm i -D vitest;  npx vitest
来源：http://dali.mhx1999.top/Article/details/gt2nzaumqbg.html

[U118] JS：开发服务器
来源：http://dali.kuanghao11.cn/Article/details/gt2hlnqbcsz.html

npm i -D vite;  npx vite
来源：http://dali.sxryk.cn/Article/details/gt2ioshbsre.html

[U119] JS：生产构建
来源：http://dali.zycfv.cn/Article/details/gt2rawcsxgg.html

npx vite build
来源：http://dali.jqgfzy.top/Article/details/gt2onldmnfq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yj20258888.top/Article/details/gt2ghgxkwtz.html

import.meta.env.VITE_API_URL
来源：http://dali.ppjwa.cn/Article/details/gt2bbekjspm.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2cpchlnmn.html

统计汇总
来源：http://dali.pycfn.com/Article/details/gt2emzaspug.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2ytavsovw.html

按语言统计（条）：
来源：http://dali.quarkkingdee.top/Article/details/gt2mmwxzegr.html

Python ......... 252
来源：http://dali.jinqigfzy.top/Article/details/gt2iggjdtta.html

PHP ............ 252
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ajqemiyi.html

JavaScript ..... 252
来源：http://dali.yj202588.top/Article/details/gt2wsqbhezq.html

TypeScript ..... 212
来源：http://dali.zhengqikj.top/Article/details/gt2ozyrkkva.html

Java ........... 212
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kuuajxjy.html

Go ............. 212
来源：http://dali.sysykeji.top/Article/details/gt2qvvulmdj.html

Ruby ........... 212
来源：http://dali.zycfv.cn/Article/details/gt2satjidyo.html

C# ............. 212
来源：http://dali.andypj.xyz/Article/details/gt2ggvkdxvg.html

C .............. 30
来源：http://dali.0kj1m.cn/Article/details/gt2mpnkmufs.html

C++ ............ 30
来源：http://dali.fengsongda.top/Article/details/gt2fiyotljv.html

SQL ............ 90
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tvzeblvs.html

Bash ........... 80
来源：http://dali.ehwqpu.com/Article/details/gt2nbyshlur.html

Kotlin ......... 15
来源：http://dali.yj20258888.top/Article/details/gt2lbclhwxb.html

Swift .......... 15
来源：http://dali.svipenyu.cn/Article/details/gt2cppsnkva.html

Lua ............ 10
来源：http://dali.ivvv.top/Article/details/gt2nwtvgveh.html

Perl ........... 10
来源：http://dali.ybcxt.top/Article/details/gt2zduljlux.html

Scala .......... 10
来源：http://dali.cdnleiting.top/Article/details/gt2zxqmdeyi.html

------------------------------------
来源：http://dali.daria6918.cn/Article/details/gt2jnfwoaad.html

合计 ........... 2106 条
来源：http://dali.yj20258888.top/Article/details/gt2fjrevoba.html

按章节统计：
来源：http://dali.zhongyouzk.top/Article/details/gt2jvybqhhl.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.0kj1m.cn/Article/details/gt2kpflwbzq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yj20258888.top/Article/details/gt2gubcoyoo.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.havefunace.top/Article/details/gt2foudvybq.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.ivvv.top/Article/details/gt2maxfkliv.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.sufxvd.cn/Article/details/gt2uawjgcxw.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.andypj.xyz/Article/details/gt2hnjdefta.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yongpay.top/Article/details/gt2skdubtmx.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.9152youxi.cn/Article/details/gt2fmcelxnu.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yonumen.top/Article/details/gt2gkkygvzo.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.aibaodan.cn/Article/details/gt2ekiwswqh.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.haohaochexian.top/Article/details/gt2jkxvxxyo.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.cqqwz.cn/Article/details/gt2azytbmjj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.tian-w.cn/Article/details/gt2cmtcwcdt.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yj20258888.top/Article/details/gt2rzljmzbb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.shangyingyoupin.top/Article/details/gt2yrkkubnf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gt2hvcfalon.html

Q SQL 专题                              90
来源：http://dali.haohaochexian.top/Article/details/gt2oydjrouq.html

R Bash 专题                             80
来源：http://dali.aizwys.cn/Article/details/gt2fkpjuqze.html

S C / C++ 专题                          60
来源：http://dali.yonumen.top/Article/details/gt2aqjmxhvv.html

T 其他语言补充                          60
来源：http://dali.havefunace.top/Article/details/gt2fptlsggz.html

U 高频实用片段                         120
来源：http://dali.feifeiyinyue.top/Article/details/gt2cpykwdyz.html

------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gt2qyxorgmw.html

合计                                  2106 条
来源：http://dali.zhixingplan.top/Article/details/gt2ubmuayqd.html

--------------------------------------------------------------------------------
来源：http://dali.snrcjt.cn/Article/details/gt2kjonsxqu.html

使用提醒
来源：http://dali.nanxinkj.top/Article/details/gt2idemaybp.html

--------------------------------------------------------------------------------
来源：http://dali.snrcjt.cn/Article/details/gt2uvdsidex.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yangfankeji.com/Article/details/gt2ousshvfe.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.mhx1999.top/Article/details/gt2afmzwfwg.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.svipenyu.cn/Article/details/gt2pwesebna.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jlsjyb.cn/Article/details/gt2phwdzovu.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.quarkkingdee.top/Article/details/gt2jobplclg.html

—— 文件结束 ——
来源：http://dali.xuanzx.com/Article/details/gt2bxcyozws.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2ykuaifki.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2axxpsojp.html

Common Programming Examples Cheat Book
来源：http://dali.daria6918.cn/Article/details/gt2hylhtbgf.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2wlxszbxu.html

【收录内容】
来源：http://dali.9152youxi.cn/Article/details/gt2nnttsupt.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.svipenyu.cn/Article/details/gt2sjcdfuop.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.aizwys.cn/Article/details/gt2qxphjnbc.html

SQL · Bash · C · C++
来源：http://dali.sysykeji.top/Article/details/gt2pajpfyfp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zycfv.cn/Article/details/gt2esnettfb.html

【使用说明】
来源：http://dali.hfpthk.cn/Article/details/gt2wwsdawol.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.fzhhl.top/Article/details/gt2zpsfeqvb.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.wangshuangyany.cn/Article/details/gt2ipylgbay.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.vqdsnc.cn/Article/details/gt2mletifzn.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gnhwxdrj.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yuanzhike.top/Article/details/gt2mcfcrvko.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.daria6918.cn/Article/details/gt2kwykjysa.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.gogol.net.cn/Article/details/gt2ocjlsmoj.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.xinyue.icu/Article/details/gt2ojmjkkud.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.wangshuangyany.cn/Article/details/gt2phvlhkok.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.redwolf501.top/Article/details/gt2ashutyvj.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2azxcwjkw.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.dashuyun.cn/Article/details/gt2ghoisnxe.html

【文件统计】
来源：http://dali.nanxuanxn.top/Article/details/gt2aybmfywg.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.guowangkeji.top/Article/details/gt2ndoznkim.html

--------------------------------------------------------------------------------
来源：http://dali.redwolf501.top/Article/details/gt2zbdgjjbj.html

目  录
来源：http://dali.redwolf501.top/Article/details/gt2cmnttyep.html

--------------------------------------------------------------------------------
来源：http://dali.yonumen.top/Article/details/gt2rjqghxkx.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.andypj.xyz/Article/details/gt2mlmjwpey.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.nwbrower.top/Article/details/gt2jhmpxpnt.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.fzhhl.top/Article/details/gt2hrzxfytl.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.iojbl.cn/Article/details/gt2zsdtfetz.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.xylfe.cn/Article/details/gt2fornsdgg.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.sxryk.cn/Article/details/gt2thrxllfk.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.birdmap.top/Article/details/gt2hgiqvbob.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.ybcxt.top/Article/details/gt2zjezrirh.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.pengpengdd.cyou/Article/details/gt2lctidfnc.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.hysaishi.cn/Article/details/gt2fowkmdfc.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.dashuyun.cn/Article/details/gt2nnqpledm.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2erekcvko.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yvedp.cn/Article/details/gt2gcirnibb.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.guowangkeji.top/Article/details/gt2fifiudwl.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhixingplan.top/Article/details/gt2lqmwyujp.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yueranfly.top/Article/details/gt2immqtwse.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.cashguo.top/Article/details/gt2chryfzxl.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.tanke756.top/Article/details/gt2lxonkapk.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.smart0.xyz/Article/details/gt2shebqdqi.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhongyouzk.top/Article/details/gt2swtmaxud.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yj20258888.top/Article/details/gt2auefmpdq.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2avhikxuz.html

A. 基础语法与类型
来源：http://dali.chenlongwang.top/Article/details/gt2wnzvrdvl.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2vbqwfroe.html

[A01] Hello World
来源：http://dali.daria6918.cn/Article/details/gt2svrmgkbk.html

Py:   print("Hello, World!")
来源：http://dali.aizwys.cn/Article/details/gt2zixvipuc.html

PHP:  echo "Hello, World!";
来源：http://dali.snrcjt.cn/Article/details/gt2iffolmtp.html

JS:   console.log("Hello, World!");
来源：http://dali.snrcjt.cn/Article/details/gt2kbeukfgq.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.sysykeji.top/Article/details/gt2uuylcncf.html

Java: System.out.println("Hello, World!");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2smddmvnw.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.chenlongwang.top/Article/details/gt2rgtmqijf.html

Ruby: puts "Hello, World!"
来源：http://dali.yongpay.top/Article/details/gt2yrioykii.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.gaohongyu789.top/Article/details/gt2flhoqouc.html

[A02] 变量声明与赋值
来源：http://dali.jlsjyb.cn/Article/details/gt2rcqcmhwy.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.guannengcc.top/Article/details/gt2zbtolkad.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.bjfxy.top/Article/details/gt2cvcswwsf.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.shangyingyoupin.top/Article/details/gt2fbhdzrpi.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.sweek.top/Article/details/gt2iyyyeypy.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ecvymyee.html

Go:   name := "Alex"; age := 20
来源：http://dali.yanxiufei.cn/Article/details/gt2nnafzloo.html

Ruby: name = "Alex"; age = 20
来源：http://dali.wangshuangyany.cn/Article/details/gt2mdqdtxoe.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.pengpengdd.cyou/Article/details/gt2iyrhevso.html

[A03] 常量定义
来源：http://dali.fengsongda.top/Article/details/gt2gimipcum.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yuanzhike.top/Article/details/gt2lvpqvgzq.html

PHP:  const PI = 3.14159;
来源：http://dali.daxiang520.top/Article/details/gt2ebqkscws.html

JS:   const PI = 3.14159;
来源：http://dali.daria6918.cn/Article/details/gt2yttaujhh.html

TS:   const PI: number = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gt2wmkxrlhd.html

Java: static final double PI = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gt2fajpxjop.html

Go:   const PI = 3.14159
来源：http://dali.cheryme.top/Article/details/gt2yljrjsxd.html

Ruby: PI = 3.14159
来源：http://dali.wangshuangyany.cn/Article/details/gt2yaunbsjm.html

C#:   const double PI = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gt2lxrshopz.html

[A04] 判断变量类型
来源：http://dali.ivvv.top/Article/details/gt2gnsxahci.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.tian-w.cn/Article/details/gt2cvwbyybx.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yj20258.top/Article/details/gt2pbwkbwbh.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.sweek.top/Article/details/gt2oebvdlak.html

TS:   typeof x; x instanceof Date
来源：http://dali.guannengcc.top/Article/details/gt2rdlltzxs.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.chenzaomai.com/Article/details/gt2lzmqzayq.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.vqdsnc.cn/Article/details/gt2suzuflmh.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.fzhhl.top/Article/details/gt2okzbbmbj.html

C#:   x.GetType().Name; x is int
来源：http://dali.chenjidiqi.icu/Article/details/gt2xeurqwag.html

[A05] 整数除法与取模
来源：http://dali.svipenyu.cn/Article/details/gt2hejwnuqo.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yj20258.top/Article/details/gt2uvadjcsu.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.aizwys.cn/Article/details/gt2skxgwmxz.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yj20258888.top/Article/details/gt2equdmihu.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gt2msslbzle.html

Java: 7 / 2; 7 % 2
来源：http://dali.jinqigfzy.top/Article/details/gt2fzhdrkpo.html

Go:   7 / 2; 7 % 2
来源：http://dali.redwolf501.top/Article/details/gt2rkqvmubg.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zaqqmbzn.html

C#:   7 / 2; 7 % 2
来源：http://dali.guannengcc.top/Article/details/gt2ljbrgper.html

[A06] 字符串转数字
来源：http://dali.cdnleiting.top/Article/details/gt2xyktvstm.html

Py:   int("42"); float("3.14")
来源：http://dali.hywenlv.cn/Article/details/gt2kdudlozj.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.nanxuanxn.top/Article/details/gt2hfqixywg.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.bjfxy.top/Article/details/gt2smhwbyyh.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jyoumei.cn/Article/details/gt2lnuuplyo.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.ppjwa.cn/Article/details/gt2iceyypno.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhiwuduotai.top/Article/details/gt2itilucsw.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yongpay.top/Article/details/gt2vivbgmrg.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yangfankeji.com/Article/details/gt2yjzudhrj.html

[A07] 数字转字符串
来源：http://dali.dianchejie.cn/Article/details/gt2yumarqjj.html

Py:   str(42)
来源：http://dali.quarkkingdee.top/Article/details/gt2jsweaopq.html

PHP:  (string) 42; strval(42)
来源：http://dali.zycfv.cn/Article/details/gt2jjrtyzfg.html

JS:   String(42); (42).toString()
来源：http://dali.fengsongda.top/Article/details/gt2zupqcifh.html

TS:   String(42)
来源：http://dali.meibo888.top/Article/details/gt2adbucbvl.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.tian-w.cn/Article/details/gt2pxpzbrhl.html

Go:   strconv.Itoa(42)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iydwnpbx.html

Ruby: 42.to_s
来源：http://dali.yongpay.top/Article/details/gt2whyqiygl.html

C#:   42.ToString()
来源：http://dali.wangdashe.top/Article/details/gt2udiyggep.html

[A08] 取整与四舍五入
来源：http://dali.dashuyun.cn/Article/details/gt2tochpgvi.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.gotoacloud.top/Article/details/gt2jyhfkrgu.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.fengsongda.top/Article/details/gt2uolqfdnx.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.cdnleiting.top/Article/details/gt2pjhazrnt.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jqgfzy.top/Article/details/gt2szzwcxiv.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.hysaishi.cn/Article/details/gt2uycajukj.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mpkrarzt.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.sufxvd.cn/Article/details/gt2dwmleamp.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yueranfly.top/Article/details/gt2todcysjr.html

[A09] 绝对值与最大最小值
来源：http://dali.cdnleiting.top/Article/details/gt2jwgouqkn.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.pycfn.com/Article/details/gt2okfsbasz.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yj20258.top/Article/details/gt2ydxlteli.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.birdmap.top/Article/details/gt2oemfhtsg.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.redwolf501.top/Article/details/gt2wglnotni.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.sufxvd.cn/Article/details/gt2fvkafsuv.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.snrcjt.cn/Article/details/gt2fvtyypha.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.316326.xyz/Article/details/gt2xrjakzpk.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.nwbrower.top/Article/details/gt2smgmxsfb.html

[A10] 生成随机数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uatxzvds.html

Py:   import random; random.randint(1, 100)
来源：http://dali.tian-w.cn/Article/details/gt2tmzjmdtz.html

PHP:  random_int(1, 100);
来源：http://dali.ybcxt.top/Article/details/gt2kugldbni.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jinqigufen.top/Article/details/gt2jzodxlyo.html


<!-- 参考信息 -->