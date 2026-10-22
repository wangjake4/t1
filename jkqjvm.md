代发 wailian999

[U69] PHP：PDO 预处理
来源：http://dali.snrcjt.cn/Article/details/gt2ustistis.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.andypj.xyz/Article/details/gt2kivjkbir.html

[U70] PHP：PDO 事务
来源：http://dali.nanxuanxn.top/Article/details/gt2wgsjwbjq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jyoumei.cn/Article/details/gt2bxraagma.html

[U71] PHP：抛出异常
来源：http://dali.andypj.xyz/Article/details/gt2pspjgres.html

throw new RuntimeException("失败", 500);
来源：http://dali.feifeiyinyue.top/Article/details/gt2pcfalbtn.html

[U72] PHP：写错误日志
来源：http://dali.ehwqpu.com/Article/details/gt2qbdwlblh.html

error_log("失败: " . $e->getMessage());
来源：http://dali.sweek.top/Article/details/gt2oexmtvtz.html

[U73] PHP：读取 ini 配置
来源：http://dali.sxryk.cn/Article/details/gt2lbafzwqq.html

parse_ini_file("config.ini", true)
来源：http://dali.nanxinkj.top/Article/details/gt2khvsiwoy.html

[U74] PHP：读取环境变量
来源：http://dali.nwbrower.top/Article/details/gt2ylytjkma.html

getenv("APP_ENV") ?: "production"
来源：http://dali.vqdsnc.cn/Article/details/gt2lmpiykiq.html

[U75] PHP：依赖注入
来源：http://dali.cheryme.top/Article/details/gt2ccxrlgom.html

composer require psr/container
来源：http://dali.hfpthk.cn/Article/details/gt2dsrhwyml.html

[U76] PHP：简单路由
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mdwkhusm.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.redwolf501.top/Article/details/gt2malpibeh.html

[U77] PHP：模板渲染
来源：http://dali.xylfe.cn/Article/details/gt2saoqiflx.html

composer require twig/twig
来源：http://dali.chenzaomai.com/Article/details/gt2mgybnjhx.html

[U78] PHP：单元测试
来源：http://dali.dianchejie.cn/Article/details/gt2prvigens.html

composer require --dev phpunit/phpunit
来源：http://dali.9152youxi.cn/Article/details/gt2mjqyjgwq.html

[U79] PHP：静态分析
来源：http://dali.xinyue.icu/Article/details/gt2ydgobixt.html

composer require --dev phpstan/phpstan
来源：http://dali.birdmap.top/Article/details/gt2nefzyscr.html

[U80] PHP：代码规范修复
来源：http://dali.redwolf501.top/Article/details/gt2ycdnfaix.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yuanzhike.top/Article/details/gt2tgqnupec.html

[U81] JS：初始化项目
来源：http://dali.xylfe.cn/Article/details/gt2kvyqziex.html

npm init -y;  npm i express
来源：http://dali.daria6918.cn/Article/details/gt2jjsztljn.html

[U82] JS：package.json 脚本
来源：http://dali.316326.xyz/Article/details/gt2bqtnizih.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jqgufenzy.top/Article/details/gt2vfzxktro.html

[U83] JS：ES Module 导入导出
来源：http://dali.hammf.cn/Article/details/gt2cprdxbko.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.havefunace.top/Article/details/gt2tbzhonqm.html

[U84] JS：CommonJS 写法
来源：http://dali.redwolf501.top/Article/details/gt2klxeyaws.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jianghu66.top/Article/details/gt2cwgrbjvk.html

[U85] JS：可选链
来源：http://dali.jinqigufen.top/Article/details/gt2xakrjsnh.html

a?.b?.c
来源：http://dali.zdqjudy.top/Article/details/gt2azxzstkc.html

[U86] JS：空值合并
来源：http://dali.zhongyouzk.top/Article/details/gt2dnyyazwg.html

a ?? b
来源：http://dali.hysaishi.cn/Article/details/gt2pegwritf.html

[U87] JS：解构默认值
来源：http://dali.chenzaomai.com/Article/details/gt2enqtkcbx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.dashuyun.cn/Article/details/gt2qbhsazal.html

[U88] JS：对象展开合并
来源：http://dali.redwolf501.top/Article/details/gt2ekdexbve.html

{ ...a, ...b }
来源：http://dali.9152youxi.cn/Article/details/gt2kluovizp.html

[U89] JS：数组去重
来源：http://dali.meibo888.top/Article/details/gt2zmrvcxfx.html

[...new Set(arr)]
来源：http://dali.xuanzx.com/Article/details/gt2pinvnqzv.html

[U90] JS：数字数组排序
来源：http://dali.jyoumei.cn/Article/details/gt2dnlbvold.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hywenlv.cn/Article/details/gt2adxqirpw.html

[U91] JS：对象键值遍历
来源：http://dali.redwolf501.top/Article/details/gt2yfpgjnjl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.fengsongda.top/Article/details/gt2mmfmwxod.html

[U92] JS：深拷贝
来源：http://dali.zhixingplan.top/Article/details/gt2skoyauli.html

structuredClone(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mhntwbhf.html

[U93] JS：模板字符串
来源：http://dali.chenzaomai.com/Article/details/gt2goxmdzjd.html

`共 ${n} 条`
来源：http://dali.pycfn.com/Article/details/gt2awwwdxfj.html

[U94] JS：箭头函数
来源：http://dali.yuanzhike.top/Article/details/gt2fdixlhna.html

const double = x => x * 2;
来源：http://dali.chenlongwang.top/Article/details/gt2tuvxkkpm.html

[U95] JS：Promise 包装
来源：http://dali.sufxvd.cn/Article/details/gt2brbltneu.html

new Promise((resolve, reject) => {})
来源：http://dali.jlsjyb.cn/Article/details/gt2gontbvnp.html

[U96] JS：async/await 与异常
来源：http://dali.cashguo.top/Article/details/gt2ncweprjt.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gt2duotvuyo.html

[U97] JS：并发请求
来源：http://dali.ydzc1.top/Article/details/gt2icdlokad.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pycfn.com/Article/details/gt2hpkglbfi.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhiwuduotai.top/Article/details/gt2mileomsq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.sweek.top/Article/details/gt2klwkabvr.html

[U99] JS：事件监听
来源：http://dali.zhiwuduotai.top/Article/details/gt2uqbelgaa.html

el.addEventListener("click", e => {})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kydpdysn.html

[U100] JS：DOM 查询
来源：http://dali.iojbl.cn/Article/details/gt2aygthimm.html

document.querySelector(".item")
来源：http://dali.yonumen.top/Article/details/gt2ppnxksky.html

[U101] JS：classList 操作
来源：http://dali.gogol.net.cn/Article/details/gt2gcufzxhn.html

el.classList.toggle("active")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bnnaafio.html

[U102] JS：本地存储
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2asgldlnh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.316326.xyz/Article/details/gt2ahkzllsy.html

[U103] JS：定时器
来源：http://dali.fengsongda.top/Article/details/gt2voibgloj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.smart0.xyz/Article/details/gt2azjodbrd.html

[U104] JS：防抖
来源：http://dali.meibo888.top/Article/details/gt2inxmntjj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jyoumei.cn/Article/details/gt2tjkzftav.html

[U105] JS：节流
来源：http://dali.yuxming.cn/Article/details/gt2xxmbxtvf.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ppjwa.cn/Article/details/gt2rwffzgha.html

[U106] JS：日期格式化
来源：http://dali.c1oappe.top/Article/details/gt2worjogey.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.daxiang520.top/Article/details/gt2uwucjmwj.html

[U107] JS：数字千分位
来源：http://dali.cashguo.top/Article/details/gt2ioypoqcg.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yonumen.top/Article/details/gt2navrhwee.html

[U108] JS：随机整数
来源：http://dali.guannengcc.top/Article/details/gt2naruisws.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.gotoacloud.top/Article/details/gt2ffvdxguc.html

[U109] JS：数组分组
来源：http://dali.jinqigufen.top/Article/details/gt2novaxgen.html

Object.groupBy(arr, x => x.type)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kifblrut.html

[U110] JS：数组分块
来源：http://dali.svipenyu.cn/Article/details/gt2uewdifrs.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.dashuyun.cn/Article/details/gt2vaqkyhep.html

[U111] JS：对象转 Map
来源：http://dali.yueranfly.top/Article/details/gt2aqsruxgb.html

new Map(Object.entries(obj))
来源：http://dali.kuanghao11.cn/Article/details/gt2vnklrvyl.html

[U112] JS：字符串补位
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2clfpvdfb.html

"7".padStart(3, "0")
来源：http://dali.ydzc1.top/Article/details/gt2mcmhcesi.html

[U113] JS：正则替换全部
来源：http://dali.chenlongwang.top/Article/details/gt2roqtwclg.html

s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gt2snnknjyj.html

[U114] JS：JSON 深比较
来源：http://dali.yueranfly.top/Article/details/gt2mgmizccr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hlbgalkj.html

[U115] JS：生成 UUID
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nwrwowyw.html

crypto.randomUUID()
来源：http://dali.wangshuangyany.cn/Article/details/gt2wgntsgkx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pgbhwzth.html

/** @param {string} name */ function f(name) {}
来源：http://dali.0kj1m.cn/Article/details/gt2iwtmakhr.html

[U117] JS：单元测试
来源：http://dali.hongshengwenyu.top/Article/details/gt2ejlbviga.html

npm i -D vitest;  npx vitest
来源：http://dali.0kj1m.cn/Article/details/gt2vgidviuh.html

[U118] JS：开发服务器
来源：http://dali.zycfv.cn/Article/details/gt2tfydcanj.html

npm i -D vite;  npx vite
来源：http://dali.sweek.top/Article/details/gt2xpvnuvrr.html

[U119] JS：生产构建
来源：http://dali.hammf.cn/Article/details/gt2vlmdmnnn.html

npx vite build
来源：http://dali.quarkkingdee.top/Article/details/gt2bcxglqpy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.haohaochexian.top/Article/details/gt2hjzwjnuo.html

import.meta.env.VITE_API_URL
来源：http://dali.ybcxt.top/Article/details/gt2porwvrdt.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2dpqsiabd.html

统计汇总
来源：http://dali.hammf.cn/Article/details/gt2gtzqhtpn.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2wdjdmbts.html

按语言统计（条）：
来源：http://dali.jlsjyb.cn/Article/details/gt2fwyjocyx.html

Python ......... 252
来源：http://dali.guannengcc.top/Article/details/gt2aqezxdvb.html

PHP ............ 252
来源：http://dali.redwolf501.top/Article/details/gt2qdydehlu.html

JavaScript ..... 252
来源：http://dali.xinyue.icu/Article/details/gt2ceptgoux.html

TypeScript ..... 212
来源：http://dali.zhengqikj.top/Article/details/gt2bwrvttme.html

Java ........... 212
来源：http://dali.ppjwa.cn/Article/details/gt2bprjwewu.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fphdwsmy.html

Ruby ........... 212
来源：http://dali.shzxlz.cn/Article/details/gt2waiirzud.html

C# ............. 212
来源：http://dali.aibaodan.cn/Article/details/gt2ulquxofw.html

C .............. 30
来源：http://dali.zhixingplan.top/Article/details/gt2vfnsadcy.html

C++ ............ 30
来源：http://dali.hysaishi.cn/Article/details/gt2eidqrfui.html

SQL ............ 90
来源：http://dali.ppjwa.cn/Article/details/gt2ejssovrl.html

Bash ........... 80
来源：http://dali.feifeiyinyue.top/Article/details/gt2nizetrwq.html

Kotlin ......... 15
来源：http://dali.tian-w.cn/Article/details/gt2ukosuedz.html

Swift .......... 15
来源：http://dali.xuanzx.com/Article/details/gt2ltoldivw.html

Lua ............ 10
来源：http://dali.hongshengwenyu.top/Article/details/gt2kgyhffbz.html

Perl ........... 10
来源：http://dali.jqgufenzy.top/Article/details/gt2hntzxfiz.html

Scala .......... 10
来源：http://dali.jinqigfzy.top/Article/details/gt2aewgtmvc.html

------------------------------------
来源：http://dali.c1oappe.top/Article/details/gt2sfawmvaz.html

合计 ........... 2106 条
来源：http://dali.dianchejie.cn/Article/details/gt2rueofzvc.html

按章节统计：
来源：http://dali.jinqigfzy.top/Article/details/gt2aotwksba.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.daria6918.cn/Article/details/gt2txnjnrgj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.aizwys.cn/Article/details/gt2qpbbhnco.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jinqigufen.top/Article/details/gt2shnotazx.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.redwolf501.top/Article/details/gt2bbzmukkh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.daxiang520.top/Article/details/gt2pwyermfk.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yangfankeji.com/Article/details/gt2wrhblwhd.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.0kj1m.cn/Article/details/gt2uncockan.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.snrcjt.cn/Article/details/gt2xakaptnc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.haohaochexian.top/Article/details/gt2iqpephkn.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.cucudq.cn/Article/details/gt2kkxpmsfr.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gt2hdphxhlb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhongyouzk.top/Article/details/gt2hrdlkflp.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.daxiang520.top/Article/details/gt2oufnciys.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ivvv.top/Article/details/gt2pjspzaqi.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.tanke756.top/Article/details/gt2zwkppyxi.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhengqikj.top/Article/details/gt2tfsmlifq.html

Q SQL 专题                              90
来源：http://dali.kuanghao11.cn/Article/details/gt2jouvmmce.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkuzyyj.html

S C / C++ 专题                          60
来源：http://dali.jiagoushi.top/Article/details/gt2ftqbziof.html

T 其他语言补充                          60
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yibiyjib.html

U 高频实用片段                         120
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2szwzohxx.html

------------------------------------
来源：http://dali.snrcjt.cn/Article/details/gt2eggcbrpm.html

合计                                  2106 条
来源：http://dali.316326.xyz/Article/details/gt2wkscyfoi.html

--------------------------------------------------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gt2aiustehn.html

使用提醒
来源：http://dali.chenzaomai.com/Article/details/gt2vkfegdct.html

--------------------------------------------------------------------------------
来源：http://dali.cashguo.top/Article/details/gt2duauclyk.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.chenlongwang.top/Article/details/gt2ekmbypxs.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ybcxt.top/Article/details/gt2xpmqypwt.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.cdnleiting.top/Article/details/gt2ywxvnuaq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.fzhhl.top/Article/details/gt2rhphmfel.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jqgfzy.top/Article/details/gt2amqibshx.html

—— 文件结束 ——
来源：http://dali.hfpthk.cn/Article/details/gt2vqjkrfgc.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2dyrpwhqb.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.tianlin.xyz/Article/details/gt2cdnhmroa.html

Common Programming Examples Cheat Book
来源：http://dali.ybcxt.top/Article/details/gt2pnwjkbie.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2tlorbxfm.html

【收录内容】
来源：http://dali.nanxinkj.top/Article/details/gt2cqcgdhzc.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.cqqwz.cn/Article/details/gt2sundgcsw.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.haohaochexian.top/Article/details/gt2uehqgcau.html

SQL · Bash · C · C++
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lpcmlmck.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zycfv.cn/Article/details/gt2zvewrxrx.html

【使用说明】
来源：http://dali.yangfankeji.com/Article/details/gt2slgddxsd.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2brcmaxar.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kuvndgbh.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yj20258.top/Article/details/gt2cwppicpo.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.gaohongyu789.top/Article/details/gt2smucxkle.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.chenjidiqi.icu/Article/details/gt2graagxcu.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.ivvv.top/Article/details/gt2qywbdlgl.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.snrcjt.cn/Article/details/gt2kxpogvqq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.tian-w.cn/Article/details/gt2wzssfvau.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.dashuyun.cn/Article/details/gt2wuzrcfwq.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.vqdsnc.cn/Article/details/gt2qedugfxb.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.dashuyun.cn/Article/details/gt2fhpnluok.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bashhjcq.html

【文件统计】
来源：http://dali.yongpay.top/Article/details/gt2lcnoigax.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yuanzhike.top/Article/details/gt2ktreyygk.html

--------------------------------------------------------------------------------
来源：http://dali.redwolf501.top/Article/details/gt2trcsnmeb.html

目  录
来源：http://dali.hnxiangtu.top/Article/details/gt2jwufhcbo.html

--------------------------------------------------------------------------------
来源：http://dali.jinqigufen.top/Article/details/gt2psxumkri.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jqgufenzy.top/Article/details/gt2potqerjl.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2ffapeqzu.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kbalnfvb.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yj20258.top/Article/details/gt2zivsjftz.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2kckdcwiv.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2oavdwkjy.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.andypj.xyz/Article/details/gt2vyskenbf.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wvicflje.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.chenzaomai.com/Article/details/gt2mqzsyfzn.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yuxming.cn/Article/details/gt2oxxojedq.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.hammf.cn/Article/details/gt2qtqvibbt.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.xuetiantiany.cn/Article/details/gt2phdkljjl.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.chenlongwang.top/Article/details/gt2cylpxlff.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.ydzc1.top/Article/details/gt2aiygbclr.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yj20258888.top/Article/details/gt2nbpypvsk.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.feifeiyinyue.top/Article/details/gt2qifldjkf.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.guannengcc.top/Article/details/gt2mdwempwt.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.hfpthk.cn/Article/details/gt2gxicseqs.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.cqqwz.cn/Article/details/gt2jneejmaz.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sxryk.cn/Article/details/gt2zmdaoagh.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhengqikj.top/Article/details/gt2yroctmel.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2lrrodmkc.html

A. 基础语法与类型
来源：http://dali.andypj.xyz/Article/details/gt2mhsefkhw.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2lsoskzjk.html

[A01] Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2tlelevgc.html

Py:   print("Hello, World!")
来源：http://dali.hysaishi.cn/Article/details/gt2muzqfjjf.html

PHP:  echo "Hello, World!";
来源：http://dali.zhengqikj.top/Article/details/gt2zrmhoyhl.html

JS:   console.log("Hello, World!");
来源：http://dali.xuanzx.com/Article/details/gt2vucvrunk.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.nanxinkj.top/Article/details/gt2uqjdhiox.html

Java: System.out.println("Hello, World!");
来源：http://dali.guowangkeji.top/Article/details/gt2infsqlom.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ikwujpos.html

Ruby: puts "Hello, World!"
来源：http://dali.mhx1999.top/Article/details/gt2yjguvvlu.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.tianlin.xyz/Article/details/gt2iubvnyyp.html

[A02] 变量声明与赋值
来源：http://dali.haohaochexian.top/Article/details/gt2hrzwokxy.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhixingplan.top/Article/details/gt2bexlrfvl.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.birdmap.top/Article/details/gt2ykiknmnk.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.cheryme.top/Article/details/gt2qwovsyqp.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sukguhzn.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hywenlv.cn/Article/details/gt2obystztm.html

Go:   name := "Alex"; age := 20
来源：http://dali.cashguo.top/Article/details/gt2ppjkflwi.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jinqigufen.top/Article/details/gt2oagohprw.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jinqigfzy.top/Article/details/gt2mnrgrnus.html

[A03] 常量定义
来源：http://dali.haohaochexian.top/Article/details/gt2oggiunji.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.fzhhl.top/Article/details/gt2ldjpepij.html

PHP:  const PI = 3.14159;
来源：http://dali.xuanzx.com/Article/details/gt2unuwoogw.html

JS:   const PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gt2lwzhbqck.html

TS:   const PI: number = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gt2nijysghr.html

Java: static final double PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gt2yptnlldw.html

Go:   const PI = 3.14159
来源：http://dali.shangyingyoupin.top/Article/details/gt2uiiunlai.html

Ruby: PI = 3.14159
来源：http://dali.guannengcc.top/Article/details/gt2cntvstxa.html

C#:   const double PI = 3.14159;
来源：http://dali.yongpay.top/Article/details/gt2wcujdnca.html

[A04] 判断变量类型
来源：http://dali.iojbl.cn/Article/details/gt2odlzhink.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.gzhubu.top/Article/details/gt2ftdjbbnu.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.316326.xyz/Article/details/gt2vkzxygsx.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.chenjidiqi.icu/Article/details/gt2qlptxvqd.html

TS:   typeof x; x instanceof Date
来源：http://dali.redwolf501.top/Article/details/gt2hinaqzvu.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.smart0.xyz/Article/details/gt2vydvrber.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hnqzz.top/Article/details/gt2gdocqrmi.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jqgfzy.top/Article/details/gt2cpqentdf.html

C#:   x.GetType().Name; x is int
来源：http://dali.vqdsnc.cn/Article/details/gt2vbjcrgxp.html

[A05] 整数除法与取模
来源：http://dali.zhixingplan.top/Article/details/gt2hmvaxtvw.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ytrldhjm.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.guannengcc.top/Article/details/gt2hfyyengs.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gt2dffabquc.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.snrcjt.cn/Article/details/gt2wcffynke.html

Java: 7 / 2; 7 % 2
来源：http://dali.xinyue.icu/Article/details/gt2zqhslnpv.html

Go:   7 / 2; 7 % 2
来源：http://dali.xinyue.icu/Article/details/gt2lgpmnhkz.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.ivvv.top/Article/details/gt2ygdiezng.html

C#:   7 / 2; 7 % 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bsemnthw.html

[A06] 字符串转数字
来源：http://dali.haohaochexian.top/Article/details/gt2nqlycgjx.html

Py:   int("42"); float("3.14")
来源：http://dali.xuetiantiany.cn/Article/details/gt2rchjdvzn.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jinqigufen.top/Article/details/gt2qxmjekqq.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yj202588.top/Article/details/gt2rbhkgrhd.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.daxiang520.top/Article/details/gt2ymearnav.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.sufxvd.cn/Article/details/gt2mrynxlno.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.nwbrower.top/Article/details/gt2wnlvfkpu.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.gogol.net.cn/Article/details/gt2kpyzkiqu.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yueranfly.top/Article/details/gt2phsxycel.html

[A07] 数字转字符串
来源：http://dali.mhx1999.top/Article/details/gt2nhddyers.html

Py:   str(42)
来源：http://dali.cdnleiting.top/Article/details/gt2hqnruilj.html

PHP:  (string) 42; strval(42)
来源：http://dali.cashguo.top/Article/details/gt2nszjotvv.html

JS:   String(42); (42).toString()
来源：http://dali.jyoumei.cn/Article/details/gt2dplgxrui.html

TS:   String(42)
来源：http://dali.zhongyouzk.top/Article/details/gt2jzzttagn.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.shzxlz.cn/Article/details/gt2uvlbzrci.html

Go:   strconv.Itoa(42)
来源：http://dali.hammf.cn/Article/details/gt2ofclfaoz.html

Ruby: 42.to_s
来源：http://dali.jyoumei.cn/Article/details/gt2xrvahkpj.html

C#:   42.ToString()
来源：http://dali.zhoulong.xyz/Article/details/gt2fqapulww.html

[A08] 取整与四舍五入
来源：http://dali.ivvv.top/Article/details/gt2hwngmfek.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.dashuyun.cn/Article/details/gt2kbzhekdp.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zdqjudy.top/Article/details/gt2dvmmutnh.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.hywenlv.cn/Article/details/gt2egwqtpeq.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iaazpjbw.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yvedp.cn/Article/details/gt2wmhgpvjz.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yueranfly.top/Article/details/gt2kjyjxzic.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.daria6918.cn/Article/details/gt2gbalmqfq.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.ehwqpu.com/Article/details/gt2qqqthfnx.html

[A09] 绝对值与最大最小值
来源：http://dali.yangfankeji.com/Article/details/gt2bqmwtunc.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.316326.xyz/Article/details/gt2rrksvlib.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.tianlin.xyz/Article/details/gt2fbngtcxs.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.chenlongwang.top/Article/details/gt2awammcdb.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.hfpthk.cn/Article/details/gt2garmuyla.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.hywenlv.cn/Article/details/gt2mjnglsep.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2skinssrs.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.ivvv.top/Article/details/gt2udpjrscx.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.tianlin.xyz/Article/details/gt2hdnivlpq.html

[A10] 生成随机数
来源：http://dali.cashguo.top/Article/details/gt2geizgnsn.html

Py:   import random; random.randint(1, 100)
来源：http://dali.wangdashe.top/Article/details/gt2hvfskmuw.html

PHP:  random_int(1, 100);
来源：http://dali.sweek.top/Article/details/gt2fcmhmahc.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jianghu66.top/Article/details/gt2qsgpzsnh.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ifhkxfnt.html

Java: new Random().nextInt(100) + 1
来源：http://dali.tanke756.top/Article/details/gt2gmfiodxm.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.316326.xyz/Article/details/gt2orutsxdo.html

Ruby: rand(1..100)
来源：http://dali.aibaodan.cn/Article/details/gt2wfcgakwe.html


<!-- 参考信息 -->