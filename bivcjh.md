代发 wailian999

[U67] PHP：处理文件上传
来源：http://dali.wangdashe.top/Article/details/gt2ittsvsfv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jiagoushi.top/Article/details/gt2snajkhwd.html

[U68] PHP：PDO 连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2buknzbzc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jyoumei.cn/Article/details/gt2fzjpvbno.html

[U69] PHP：PDO 预处理
来源：http://dali.jqgfzy.top/Article/details/gt2gdmzbavb.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zdqjudy.top/Article/details/gt2pwdkrpcs.html

[U70] PHP：PDO 事务
来源：http://dali.hywenlv.cn/Article/details/gt2sunegvgd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.guowangkeji.top/Article/details/gt2skcnkedi.html

[U71] PHP：抛出异常
来源：http://dali.shuidangran.top/Article/details/gt2zqwfewvr.html

throw new RuntimeException("失败", 500);
来源：http://dali.chenlongwang.top/Article/details/gt2jmhtjkwt.html

[U72] PHP：写错误日志
来源：http://dali.sysykeji.top/Article/details/gt2pmtxjtwf.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dchlhgvr.html

[U73] PHP：读取 ini 配置
来源：http://dali.cdnleiting.top/Article/details/gt2xoxkmgpy.html

parse_ini_file("config.ini", true)
来源：http://dali.sufxvd.cn/Article/details/gt2qhclqqtc.html

[U74] PHP：读取环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2cznjwbir.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jqgufenzy.top/Article/details/gt2orqjcsmk.html

[U75] PHP：依赖注入
来源：http://dali.fzhhl.top/Article/details/gt2dybckkus.html

composer require psr/container
来源：http://dali.hnxiangtu.top/Article/details/gt2jyilwhvb.html

[U76] PHP：简单路由
来源：http://dali.zdqjudy.top/Article/details/gt2gskejltl.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.wangdashe.top/Article/details/gt2kwmxaioy.html

[U77] PHP：模板渲染
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lgwaqvof.html

composer require twig/twig
来源：http://dali.shangyingyoupin.top/Article/details/gt2uicnbjbe.html

[U78] PHP：单元测试
来源：http://dali.jqgfzy.top/Article/details/gt2xeizfxee.html

composer require --dev phpunit/phpunit
来源：http://dali.cashguo.top/Article/details/gt2whaclqux.html

[U79] PHP：静态分析
来源：http://dali.sweek.top/Article/details/gt2dixshwsy.html

composer require --dev phpstan/phpstan
来源：http://dali.sweek.top/Article/details/gt2qwpdrhwe.html

[U80] PHP：代码规范修复
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bprbyovv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.shuidangran.top/Article/details/gt2oxeeduvd.html

[U81] JS：初始化项目
来源：http://dali.yj202588.top/Article/details/gt2czrkajmu.html

npm init -y;  npm i express
来源：http://dali.haohaochexian.top/Article/details/gt2ylugdrcb.html

[U82] JS：package.json 脚本
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gykjtxpc.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.gotoacloud.top/Article/details/gt2hjgbntzg.html

[U83] JS：ES Module 导入导出
来源：http://dali.fengsongda.top/Article/details/gt2vacvbtcl.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.xziqi.cn/Article/details/gt2btpsaqqw.html

[U84] JS：CommonJS 写法
来源：http://dali.hammf.cn/Article/details/gt2tcnsmpbc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hongshengwenyu.top/Article/details/gt2hsrghnlv.html

[U85] JS：可选链
来源：http://dali.yangfankeji.com/Article/details/gt2mcqkokyf.html

a?.b?.c
来源：http://dali.gzhubu.top/Article/details/gt2yyatauxe.html

[U86] JS：空值合并
来源：http://dali.jiagoushi.top/Article/details/gt2bxlugxmx.html

a ?? b
来源：http://dali.zhixingplan.top/Article/details/gt2bzmemdly.html

[U87] JS：解构默认值
来源：http://dali.jinqigfzy.top/Article/details/gt2zzcmhapw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jianghu66.top/Article/details/gt2vuwvolto.html

[U88] JS：对象展开合并
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hyyegitv.html

{ ...a, ...b }
来源：http://dali.hfpthk.cn/Article/details/gt2sgkshoua.html

[U89] JS：数组去重
来源：http://dali.daria6918.cn/Article/details/gt2bthnjwzq.html

[...new Set(arr)]
来源：http://dali.xinyue.icu/Article/details/gt2xblltuye.html

[U90] JS：数字数组排序
来源：http://dali.wangshuangyany.cn/Article/details/gt2hdawzflh.html

[...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mfyqbzkv.html

[U91] JS：对象键值遍历
来源：http://dali.hnxiangtu.top/Article/details/gt2fnqmbymm.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.sxryk.cn/Article/details/gt2lysrxhsp.html

[U92] JS：深拷贝
来源：http://dali.mhx1999.top/Article/details/gt2pgvouoqe.html

structuredClone(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2xoezqvob.html

[U93] JS：模板字符串
来源：http://dali.redwolf501.top/Article/details/gt2ygyxokos.html

`共 ${n} 条`
来源：http://dali.gzhubu.top/Article/details/gt2aaaiokcb.html

[U94] JS：箭头函数
来源：http://dali.birdmap.top/Article/details/gt2ylqizzhj.html

const double = x => x * 2;
来源：http://dali.aizwys.cn/Article/details/gt2xcwrzjld.html

[U95] JS：Promise 包装
来源：http://dali.guowangkeji.top/Article/details/gt2xhimryon.html

new Promise((resolve, reject) => {})
来源：http://dali.tanke756.top/Article/details/gt2agxqdnwx.html

[U96] JS：async/await 与异常
来源：http://dali.0kj1m.cn/Article/details/gt2dbvrnoxy.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yuxming.cn/Article/details/gt2iwcxmmcs.html

[U97] JS：并发请求
来源：http://dali.gotoacloud.top/Article/details/gt2nalctmuu.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jlsjyb.cn/Article/details/gt2odwyedal.html

[U98] JS：fetch 带 JSON
来源：http://dali.kuanghao11.cn/Article/details/gt2erkqqzvj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.wangshuangyany.cn/Article/details/gt2sndbkikf.html

[U99] JS：事件监听
来源：http://dali.feifeiyinyue.top/Article/details/gt2tfqqeahv.html

el.addEventListener("click", e => {})
来源：http://dali.birdmap.top/Article/details/gt2pnlmzyxm.html

[U100] JS：DOM 查询
来源：http://dali.yj20258888.top/Article/details/gt2huqlcefx.html

document.querySelector(".item")
来源：http://dali.aizwys.cn/Article/details/gt2bwwctliv.html

[U101] JS：classList 操作
来源：http://dali.zhoulong.xyz/Article/details/gt2yuumhdul.html

el.classList.toggle("active")
来源：http://dali.cheryme.top/Article/details/gt2trjfmvse.html

[U102] JS：本地存储
来源：http://dali.hysaishi.cn/Article/details/gt2keocvlss.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.nwbrower.top/Article/details/gt2kjndajbt.html

[U103] JS：定时器
来源：http://dali.daxiang520.top/Article/details/gt2nxtdvdru.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jyoumei.cn/Article/details/gt2rsaldoxx.html

[U104] JS：防抖
来源：http://dali.cdnleiting.top/Article/details/gt2kfmxqzzt.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.c1oappe.top/Article/details/gt2ndmbwsfg.html

[U105] JS：节流
来源：http://dali.tanke756.top/Article/details/gt2dxugoiol.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cucudq.cn/Article/details/gt2hynxycby.html

[U106] JS：日期格式化
来源：http://dali.cdnleiting.top/Article/details/gt2tpqeljsa.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.wangshuangyany.cn/Article/details/gt2sfugauvq.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhjssnk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.chenlongwang.top/Article/details/gt2wqizehvv.html

[U108] JS：随机整数
来源：http://dali.hywenlv.cn/Article/details/gt2cqixoyzx.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.havefunace.top/Article/details/gt2fqygphgw.html

[U109] JS：数组分组
来源：http://dali.yangfankeji.com/Article/details/gt2oeocelic.html

Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wwzvwxki.html

[U110] JS：数组分块
来源：http://dali.zycfv.cn/Article/details/gt2prpqpymp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.dashuyun.cn/Article/details/gt2ltzioyur.html

[U111] JS：对象转 Map
来源：http://dali.ehwqpu.com/Article/details/gt2jlnjahhy.html

new Map(Object.entries(obj))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uxzsunog.html

[U112] JS：字符串补位
来源：http://dali.cqqwz.cn/Article/details/gt2znysarvs.html

"7".padStart(3, "0")
来源：http://dali.hnqzz.top/Article/details/gt2hktuhpfr.html

[U113] JS：正则替换全部
来源：http://dali.zdqjudy.top/Article/details/gt2xedtpxpd.html

s.replaceAll("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gt2qeipnhpo.html

[U114] JS：JSON 深比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bbtcivss.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxuanxn.top/Article/details/gt2bwvrefdy.html

[U115] JS：生成 UUID
来源：http://dali.guowangkeji.top/Article/details/gt2mxvqzsgp.html

crypto.randomUUID()
来源：http://dali.chenlongwang.top/Article/details/gt2gbkqzphm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.dashuyun.cn/Article/details/gt2cdmrqoyl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yj202588.top/Article/details/gt2caikpxqy.html

[U117] JS：单元测试
来源：http://dali.tian-w.cn/Article/details/gt2iuczmogm.html

npm i -D vitest;  npx vitest
来源：http://dali.haohaochexian.top/Article/details/gt2hmxiknsd.html

[U118] JS：开发服务器
来源：http://dali.pengpengdd.cyou/Article/details/gt2hmhxahxa.html

npm i -D vite;  npx vite
来源：http://dali.aibaodan.cn/Article/details/gt2rnmijwgm.html

[U119] JS：生产构建
来源：http://dali.jinqigfzy.top/Article/details/gt2bzwhvmsf.html

npx vite build
来源：http://dali.xinyue.icu/Article/details/gt2vbdepsfs.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.havefunace.top/Article/details/gt2wsdkbpka.html

import.meta.env.VITE_API_URL
来源：http://dali.gaohongyu789.top/Article/details/gt2fybpcylx.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2jhkexmxb.html

统计汇总
来源：http://dali.hongshengwenyu.top/Article/details/gt2ohstbkzu.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2ttviuprp.html

按语言统计（条）：
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qbxuchsc.html

Python ......... 252
来源：http://dali.gogol.net.cn/Article/details/gt2mntyhhcm.html

PHP ............ 252
来源：http://dali.cdnleiting.top/Article/details/gt2rfhshrta.html

JavaScript ..... 252
来源：http://dali.aizwys.cn/Article/details/gt2zgfbffny.html

TypeScript ..... 212
来源：http://dali.xuanzx.com/Article/details/gt2fijnjycy.html

Java ........... 212
来源：http://dali.gotoacloud.top/Article/details/gt2dhjbdjns.html

Go ............. 212
来源：http://dali.quarkkingdee.top/Article/details/gt2bavfejhd.html

Ruby ........... 212
来源：http://dali.hongshengwenyu.top/Article/details/gt2wbgdchxo.html

C# ............. 212
来源：http://dali.fzhhl.top/Article/details/gt2sgfwmqlx.html

C .............. 30
来源：http://dali.snrcjt.cn/Article/details/gt2zmqrhbkd.html

C++ ............ 30
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dpfauwiv.html

SQL ............ 90
来源：http://dali.jinqigfzy.top/Article/details/gt2bvugbptb.html

Bash ........... 80
来源：http://dali.xuetiantiany.cn/Article/details/gt2hecmzabn.html

Kotlin ......... 15
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aaojdruc.html

Swift .......... 15
来源：http://dali.yonumen.top/Article/details/gt2jdsqinfh.html

Lua ............ 10
来源：http://dali.hywenlv.cn/Article/details/gt2jzhmurdu.html

Perl ........... 10
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wcbornvr.html

Scala .......... 10
来源：http://dali.gogol.net.cn/Article/details/gt2kuxxkvef.html

------------------------------------
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zomgydmb.html

合计 ........... 2106 条
来源：http://dali.chenlongwang.top/Article/details/gt2fkqvtrsp.html

按章节统计：
来源：http://dali.vqdsnc.cn/Article/details/gt2nlqqwhyz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.wangdashe.top/Article/details/gt2tyxazsyv.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jiagoushi.top/Article/details/gt2wcjhsrsh.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.nanxinkj.top/Article/details/gt2lffxoyxk.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yj20258888.top/Article/details/gt2ybgcymru.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.ydzc1.top/Article/details/gt2bulhkwwf.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.dianchejie.cn/Article/details/gt2ehstivqn.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhiwuduotai.top/Article/details/gt2xcxdmxav.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.chenzaomai.com/Article/details/gt2hwzcnqlx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gt2iqnpuwcw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.c1oappe.top/Article/details/gt2owkaidee.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.pycfn.com/Article/details/gt2iwxpvpoa.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.shuidangran.top/Article/details/gt2xtkkvjxx.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jqgufenzy.top/Article/details/gt2auinymzm.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yj20258.top/Article/details/gt2hwrikwqo.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.dianchejie.cn/Article/details/gt2jyebwdiq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.gotoacloud.top/Article/details/gt2mcocbtdh.html

Q SQL 专题                              90
来源：http://dali.hammf.cn/Article/details/gt2pmiycqtb.html

R Bash 专题                             80
来源：http://dali.hywenlv.cn/Article/details/gt2fsdupier.html

S C / C++ 专题                          60
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ywcqgxzy.html

T 其他语言补充                          60
来源：http://dali.ppjwa.cn/Article/details/gt2beizitxl.html

U 高频实用片段                         120
来源：http://dali.jianghu66.top/Article/details/gt2lmycyaxy.html

------------------------------------
来源：http://dali.hywenlv.cn/Article/details/gt2lqdcuhbj.html

合计                                  2106 条
来源：http://dali.yonumen.top/Article/details/gt2pgjtopcz.html

--------------------------------------------------------------------------------
来源：http://dali.wangshuangyany.cn/Article/details/gt2iaxbweuv.html

使用提醒
来源：http://dali.ybcxt.top/Article/details/gt2fpqmmxec.html

--------------------------------------------------------------------------------
来源：http://dali.hnqzz.top/Article/details/gt2lknbqccn.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.wangdashe.top/Article/details/gt2thtudyzq.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xtrcqkyv.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.xuanzx.com/Article/details/gt2xncxxica.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yj20258888.top/Article/details/gt2zzvosbck.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.shangyingyoupin.top/Article/details/gt2fzquohrw.html

—— 文件结束 ——
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rundvzmr.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2buplcfeq.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.chenlongwang.top/Article/details/gt2cjbwnpbu.html

Common Programming Examples Cheat Book
来源：http://dali.hnqzz.top/Article/details/gt2jhenticc.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2njfzdgup.html

【收录内容】
来源：http://dali.gogol.net.cn/Article/details/gt2uudndqfp.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.redwolf501.top/Article/details/gt2svlzbgol.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jqgufenzy.top/Article/details/gt2ppbccnts.html

SQL · Bash · C · C++
来源：http://dali.iojbl.cn/Article/details/gt2nmosrxxw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.cucudq.cn/Article/details/gt2cjzgpupy.html

【使用说明】
来源：http://dali.jyoumei.cn/Article/details/gt2lunwilwd.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.daria6918.cn/Article/details/gt2osyrcuye.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ahynyjuw.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ahauulqi.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhongyouzk.top/Article/details/gt2qfzdtkmy.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.meibo888.top/Article/details/gt2obwkrldt.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.gotoacloud.top/Article/details/gt2ofmtjjlj.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.chenlongwang.top/Article/details/gt2tuzrxldz.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yuanzhike.top/Article/details/gt2jwqkjdks.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pouytmps.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.gogol.net.cn/Article/details/gt2rpuxifmx.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.feifeiyinyue.top/Article/details/gt2fhbtyvnp.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.hfpthk.cn/Article/details/gt2udmmnzar.html

【文件统计】
来源：http://dali.aibaodan.cn/Article/details/gt2oviymewr.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.hnqzz.top/Article/details/gt2cfzpbzks.html

--------------------------------------------------------------------------------
来源：http://dali.wangdashe.top/Article/details/gt2glsontbz.html

目  录
来源：http://dali.sufxvd.cn/Article/details/gt2eqnshxxy.html

--------------------------------------------------------------------------------
来源：http://dali.sxryk.cn/Article/details/gt2qzvpupud.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yuxming.cn/Article/details/gt2gndmbugz.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.feifeiyinyue.top/Article/details/gt2wdmdqkhw.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.mhx1999.top/Article/details/gt2oyziusap.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yuxming.cn/Article/details/gt2tgtcemqe.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hywenlv.cn/Article/details/gt2ayayapkc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kqzbcbzb.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.cheryme.top/Article/details/gt2ktbcdeni.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jinqigufen.top/Article/details/gt2wxnyhpyi.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.havefunace.top/Article/details/gt2yzgwcfxw.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yonumen.top/Article/details/gt2juwuulco.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2izdwvghc.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yj20258.top/Article/details/gt2rbdgyogj.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.tian-w.cn/Article/details/gt2todrbpbj.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yanxiufei.cn/Article/details/gt2asiwuhhe.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2qresfnmd.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2dlaqwgcn.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yj20258888.top/Article/details/gt2ieqqbzbh.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yangfankeji.com/Article/details/gt2uohghdah.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.chenjidiqi.icu/Article/details/gt2nxkadlli.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ybcxt.top/Article/details/gt2oibpsmnb.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.xuanzx.com/Article/details/gt2cwnyxkax.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2mexbaepm.html

A. 基础语法与类型
来源：http://dali.birdmap.top/Article/details/gt2xjpzhmbn.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2jshfivcz.html

[A01] Hello World
来源：http://dali.jiagoushi.top/Article/details/gt2qsjibhsu.html

Py:   print("Hello, World!")
来源：http://dali.yueranfly.top/Article/details/gt2ezjrrolw.html

PHP:  echo "Hello, World!";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eqeasybi.html

JS:   console.log("Hello, World!");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ukkhbnfo.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yuxming.cn/Article/details/gt2druksggk.html

Java: System.out.println("Hello, World!");
来源：http://dali.gotoacloud.top/Article/details/gt2jsbsioyt.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.316326.xyz/Article/details/gt2epbrljqc.html

Ruby: puts "Hello, World!"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zaucpotf.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.sufxvd.cn/Article/details/gt2qwaenjlf.html

[A02] 变量声明与赋值
来源：http://dali.jinqigfzy.top/Article/details/gt2qpjlnstt.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.xuetiantiany.cn/Article/details/gt2zvkctlcc.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhiwuduotai.top/Article/details/gt2bnpanfhd.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uwdvubwk.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.gzhubu.top/Article/details/gt2oozxtorr.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.aizwys.cn/Article/details/gt2agvkfdtu.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhixingplan.top/Article/details/gt2iduxlotr.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhoulong.xyz/Article/details/gt2eviwjzkc.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.andypj.xyz/Article/details/gt2jjfytghq.html

[A03] 常量定义
来源：http://dali.c1oappe.top/Article/details/gt2mddryhna.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zdqjudy.top/Article/details/gt2tbbjegxb.html

PHP:  const PI = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gt2puahcypl.html

JS:   const PI = 3.14159;
来源：http://dali.bjfxy.top/Article/details/gt2rbreohbm.html

TS:   const PI: number = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gt2bvcojygh.html

Java: static final double PI = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gt2hkmmrqix.html

Go:   const PI = 3.14159
来源：http://dali.cdnleiting.top/Article/details/gt2fztmfatm.html

Ruby: PI = 3.14159
来源：http://dali.bjfxy.top/Article/details/gt2hhchmohj.html

C#:   const double PI = 3.14159;
来源：http://dali.ivvv.top/Article/details/gt2zlhyzfzm.html

[A04] 判断变量类型
来源：http://dali.cashguo.top/Article/details/gt2thtxtnrg.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.hysaishi.cn/Article/details/gt2hiflowsp.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jinqigfzy.top/Article/details/gt2rzyyraqh.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zycfv.cn/Article/details/gt2ephszfth.html

TS:   typeof x; x instanceof Date
来源：http://dali.chenlongwang.top/Article/details/gt2arktlvbd.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.cdnleiting.top/Article/details/gt2hymbgdim.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.aibaodan.cn/Article/details/gt2lavunfac.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.guowangkeji.top/Article/details/gt2qseldrog.html

C#:   x.GetType().Name; x is int
来源：http://dali.aizwys.cn/Article/details/gt2uexxqyfp.html

[A05] 整数除法与取模
来源：http://dali.yj20258.top/Article/details/gt2xaqhfjho.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zycfv.cn/Article/details/gt2zfluihjc.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gt2rraokali.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cqqwz.cn/Article/details/gt2xhacctzo.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zycfv.cn/Article/details/gt2chlfuqcq.html

Java: 7 / 2; 7 % 2
来源：http://dali.jinqigfzy.top/Article/details/gt2juapbtiy.html

Go:   7 / 2; 7 % 2
来源：http://dali.jinqigufen.top/Article/details/gt2wjjkpolw.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yonumen.top/Article/details/gt2dghwjxku.html

C#:   7 / 2; 7 % 2
来源：http://dali.yvedp.cn/Article/details/gt2muwlcfls.html

[A06] 字符串转数字
来源：http://dali.jiagoushi.top/Article/details/gt2qpdxsues.html

Py:   int("42"); float("3.14")
来源：http://dali.meibo888.top/Article/details/gt2ixfdpntt.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yonumen.top/Article/details/gt2wpforktp.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.dianchejie.cn/Article/details/gt2klhmtanc.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hnxiangtu.top/Article/details/gt2rcltllxh.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iqgngzin.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.vqdsnc.cn/Article/details/gt2dctxifkz.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.bjfxy.top/Article/details/gt2mysflmth.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.wangshuangyany.cn/Article/details/gt2tohomtyo.html

[A07] 数字转字符串
来源：http://dali.haohaochexian.top/Article/details/gt2qscuezur.html

Py:   str(42)
来源：http://dali.haohaochexian.top/Article/details/gt2ttyerfuq.html

PHP:  (string) 42; strval(42)
来源：http://dali.gaohongyu789.top/Article/details/gt2pobvioit.html

JS:   String(42); (42).toString()
来源：http://dali.cqqwz.cn/Article/details/gt2vydxkemj.html

TS:   String(42)
来源：http://dali.guannengcc.top/Article/details/gt2damnacjr.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.cucudq.cn/Article/details/gt2zfmeuwvj.html

Go:   strconv.Itoa(42)
来源：http://dali.9152youxi.cn/Article/details/gt2auhioqvt.html

Ruby: 42.to_s
来源：http://dali.zhongyouzk.top/Article/details/gt2cgfbhzjy.html

C#:   42.ToString()
来源：http://dali.yangfankeji.com/Article/details/gt2fbsavchf.html

[A08] 取整与四舍五入
来源：http://dali.ydzc1.top/Article/details/gt2xdqubqta.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.cheryme.top/Article/details/gt2jawywczo.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jinqigufen.top/Article/details/gt2inygbtmt.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.nanxinkj.top/Article/details/gt2jululflx.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.cqqwz.cn/Article/details/gt2gfqyxsnn.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.sysykeji.top/Article/details/gt2voufarcz.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.pycfn.com/Article/details/gt2wzyeqzjk.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.pycfn.com/Article/details/gt2iodxqmeh.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.hfpthk.cn/Article/details/gt2lfznchvl.html

[A09] 绝对值与最大最小值
来源：http://dali.sufxvd.cn/Article/details/gt2pwqejolf.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ikawmhxn.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2sjmnurnl.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.fzhhl.top/Article/details/gt2tyhojlvz.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.andypj.xyz/Article/details/gt2zhbfscxr.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2exthcsnu.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.guannengcc.top/Article/details/gt2scuxhkql.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yuxming.cn/Article/details/gt2hypmltdu.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.316326.xyz/Article/details/gt2qlaxlgmv.html

[A10] 生成随机数
来源：http://dali.jqgfzy.top/Article/details/gt2iuwnpbkq.html

Py:   import random; random.randint(1, 100)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nxxpsqjf.html

PHP:  random_int(1, 100);
来源：http://dali.tanke756.top/Article/details/gt2blixeiqv.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xinyue.icu/Article/details/gt2lmnufhcw.html


<!-- 参考信息 -->