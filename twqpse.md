代发 wailian999

[U63] PHP：文件读写
来源：http://dali.zdqjudy.top/Article/details/gt2muepuyom.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.xinyue.icu/Article/details/gt2xjrvsbfm.html

[U64] PHP：目录遍历
来源：http://dali.chenjidiqi.icu/Article/details/gt2scfrbwco.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhoulong.xyz/Article/details/gt2pvtrpkyu.html

[U65] PHP：会话
来源：http://dali.jinghuilouyu.cn/Article/details/gt2myannvwy.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gt2ixfnywgy.html

[U66] PHP：设置 Cookie
来源：http://dali.vqdsnc.cn/Article/details/gt2pybtmcfg.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xcfosxhm.html

[U67] PHP：处理文件上传
来源：http://dali.kuanghao11.cn/Article/details/gt2qbugwpwj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.xylfe.cn/Article/details/gt2uyjbisfq.html

[U68] PHP：PDO 连接
来源：http://dali.cheryme.top/Article/details/gt2oohuuahc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yanxiufei.cn/Article/details/gt2mizyjeiz.html

[U69] PHP：PDO 预处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dncamlcn.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.mhx1999.top/Article/details/gt2ibqkfxxo.html

[U70] PHP：PDO 事务
来源：http://dali.gaohongyu789.top/Article/details/gt2hrqalsle.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.cucudq.cn/Article/details/gt2wbxecqsl.html

[U71] PHP：抛出异常
来源：http://dali.yj20258.top/Article/details/gt2lnkcxfqp.html

throw new RuntimeException("失败", 500);
来源：http://dali.dianchejie.cn/Article/details/gt2sqdarlcx.html

[U72] PHP：写错误日志
来源：http://dali.jqgfzy.top/Article/details/gt2fmfnxhsy.html

error_log("失败: " . $e->getMessage());
来源：http://dali.0kj1m.cn/Article/details/gt2caxawska.html

[U73] PHP：读取 ini 配置
来源：http://dali.yj20258.top/Article/details/gt2tfdmvkfp.html

parse_ini_file("config.ini", true)
来源：http://dali.gzhubu.top/Article/details/gt2yxwcnfsm.html

[U74] PHP：读取环境变量
来源：http://dali.sweek.top/Article/details/gt2kkgryzxd.html

getenv("APP_ENV") ?: "production"
来源：http://dali.gogol.net.cn/Article/details/gt2egtsfdmq.html

[U75] PHP：依赖注入
来源：http://dali.nanxuanxn.top/Article/details/gt2isukdotd.html

composer require psr/container
来源：http://dali.ppjwa.cn/Article/details/gt2mtmnjsfy.html

[U76] PHP：简单路由
来源：http://dali.dianchejie.cn/Article/details/gt2veehqodn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.shangyingyoupin.top/Article/details/gt2xgxtcwbv.html

[U77] PHP：模板渲染
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lbmuudmf.html

composer require twig/twig
来源：http://dali.ivvv.top/Article/details/gt2kipbmdxq.html

[U78] PHP：单元测试
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xfzatmis.html

composer require --dev phpunit/phpunit
来源：http://dali.gotoacloud.top/Article/details/gt2aoudkyag.html

[U79] PHP：静态分析
来源：http://dali.fengsongda.top/Article/details/gt2osilslky.html

composer require --dev phpstan/phpstan
来源：http://dali.xylfe.cn/Article/details/gt2iychlxck.html

[U80] PHP：代码规范修复
来源：http://dali.wangdashe.top/Article/details/gt2nnlgsjjm.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.ivvv.top/Article/details/gt2nhqkcmkm.html

[U81] JS：初始化项目
来源：http://dali.jiagoushi.top/Article/details/gt2tyqahoas.html

npm init -y;  npm i express
来源：http://dali.smart0.xyz/Article/details/gt2lbiqvsut.html

[U82] JS：package.json 脚本
来源：http://dali.hongshengwenyu.top/Article/details/gt2hncfhffo.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yvedp.cn/Article/details/gt2theshyxj.html

[U83] JS：ES Module 导入导出
来源：http://dali.ivvv.top/Article/details/gt2trdfkzof.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.bjfxy.top/Article/details/gt2nfksvjde.html

[U84] JS：CommonJS 写法
来源：http://dali.ehwqpu.com/Article/details/gt2zavnnpri.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jqgufenzy.top/Article/details/gt2oiyrarfj.html

[U85] JS：可选链
来源：http://dali.tianlin.xyz/Article/details/gt2armvimfs.html

a?.b?.c
来源：http://dali.jqgufenzy.top/Article/details/gt2snrkedmg.html

[U86] JS：空值合并
来源：http://dali.9152youxi.cn/Article/details/gt2dayfraqv.html

a ?? b
来源：http://dali.xylfe.cn/Article/details/gt2wvwsqlar.html

[U87] JS：解构默认值
来源：http://dali.nwbrower.top/Article/details/gt2clfkapjm.html

const { a = 1, b = 2 } = obj;
来源：http://dali.feifeiyinyue.top/Article/details/gt2nqlsxtqi.html

[U88] JS：对象展开合并
来源：http://dali.sweek.top/Article/details/gt2qkfelqcf.html

{ ...a, ...b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ihrxmcyz.html

[U89] JS：数组去重
来源：http://dali.hnxiangtu.top/Article/details/gt2qehcebji.html

[...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gt2btkimket.html

[U90] JS：数字数组排序
来源：http://dali.316326.xyz/Article/details/gt2spsmmzfi.html

[...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gt2xrgefcko.html

[U91] JS：对象键值遍历
来源：http://dali.pengpengdd.cyou/Article/details/gt2lxvyruew.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.nwbrower.top/Article/details/gt2vluqrwyn.html

[U92] JS：深拷贝
来源：http://dali.yongpay.top/Article/details/gt2aetydfid.html

structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gt2uyusvqba.html

[U93] JS：模板字符串
来源：http://dali.yj20258888.top/Article/details/gt2gkxdgiyf.html

`共 ${n} 条`
来源：http://dali.wangdashe.top/Article/details/gt2laxtphue.html

[U94] JS：箭头函数
来源：http://dali.hywenlv.cn/Article/details/gt2trznmgim.html

const double = x => x * 2;
来源：http://dali.c1oappe.top/Article/details/gt2bapvjxkb.html

[U95] JS：Promise 包装
来源：http://dali.316326.xyz/Article/details/gt2vhjsdtst.html

new Promise((resolve, reject) => {})
来源：http://dali.iojbl.cn/Article/details/gt2ocuurwmq.html

[U96] JS：async/await 与异常
来源：http://dali.dashuyun.cn/Article/details/gt2qvdqeuyl.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gt2tjgjysvl.html

[U97] JS：并发请求
来源：http://dali.sysykeji.top/Article/details/gt2nuopfjma.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gt2kerxudoq.html

[U98] JS：fetch 带 JSON
来源：http://dali.nwbrower.top/Article/details/gt2afnbncsj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jqgufenzy.top/Article/details/gt2jrqwzabo.html

[U99] JS：事件监听
来源：http://dali.andypj.xyz/Article/details/gt2syidefzw.html

el.addEventListener("click", e => {})
来源：http://dali.jianghu66.top/Article/details/gt2sxrxhiqm.html

[U100] JS：DOM 查询
来源：http://dali.guannengcc.top/Article/details/gt2plfsyfef.html

document.querySelector(".item")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fanmhfiu.html

[U101] JS：classList 操作
来源：http://dali.hnqzz.top/Article/details/gt2znlcvfer.html

el.classList.toggle("active")
来源：http://dali.ivvv.top/Article/details/gt2xylltxxm.html

[U102] JS：本地存储
来源：http://dali.yvedp.cn/Article/details/gt2fokphqrc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.bjfxy.top/Article/details/gt2zhzmeywp.html

[U103] JS：定时器
来源：http://dali.dianchejie.cn/Article/details/gt2vfvxednk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.guannengcc.top/Article/details/gt2jtnursou.html

[U104] JS：防抖
来源：http://dali.ivvv.top/Article/details/gt2hlptbjdy.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.316326.xyz/Article/details/gt2mlcjsqlt.html

[U105] JS：节流
来源：http://dali.zhoulong.xyz/Article/details/gt2qarktwbf.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.chenjidiqi.icu/Article/details/gt2dzzfelcx.html

[U106] JS：日期格式化
来源：http://dali.jinqigfzy.top/Article/details/gt2mkllufxv.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.gotoacloud.top/Article/details/gt2wfxwjmmt.html

[U107] JS：数字千分位
来源：http://dali.sxryk.cn/Article/details/gt2yfqlnxql.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shangyingyoupin.top/Article/details/gt2yidqopyr.html

[U108] JS：随机整数
来源：http://dali.jlsjyb.cn/Article/details/gt2bqrpagbs.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hysaishi.cn/Article/details/gt2vxwyxztx.html

[U109] JS：数组分组
来源：http://dali.shzxlz.cn/Article/details/gt2jhkzkcda.html

Object.groupBy(arr, x => x.type)
来源：http://dali.shuidangran.top/Article/details/gt2djtjovvl.html

[U110] JS：数组分块
来源：http://dali.hfpthk.cn/Article/details/gt2jtaxkqnf.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yuanzhike.top/Article/details/gt2fxogybat.html

[U111] JS：对象转 Map
来源：http://dali.jinqigufen.top/Article/details/gt2rlnoxstj.html

new Map(Object.entries(obj))
来源：http://dali.zhixingplan.top/Article/details/gt2whyohpsj.html

[U112] JS：字符串补位
来源：http://dali.redwolf501.top/Article/details/gt2gxkqmgqw.html

"7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gt2unvzkjaj.html

[U113] JS：正则替换全部
来源：http://dali.zhengqikj.top/Article/details/gt2yveujosb.html

s.replaceAll("a", "b")
来源：http://dali.cashguo.top/Article/details/gt2poomykij.html

[U114] JS：JSON 深比较
来源：http://dali.ydzc1.top/Article/details/gt2zgmwgkch.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cashguo.top/Article/details/gt2einqotmi.html

[U115] JS：生成 UUID
来源：http://dali.cheryme.top/Article/details/gt2oltwxtsk.html

crypto.randomUUID()
来源：http://dali.tian-w.cn/Article/details/gt2ihesohxe.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yanxiufei.cn/Article/details/gt2qprzmfri.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jinqigufen.top/Article/details/gt2zlbkxjaf.html

[U117] JS：单元测试
来源：http://dali.guannengcc.top/Article/details/gt2zdjqtoqq.html

npm i -D vitest;  npx vitest
来源：http://dali.redwolf501.top/Article/details/gt2oekwjlzs.html

[U118] JS：开发服务器
来源：http://dali.iojbl.cn/Article/details/gt2gkezezhq.html

npm i -D vite;  npx vite
来源：http://dali.yanxiufei.cn/Article/details/gt2uhkzfdim.html

[U119] JS：生产构建
来源：http://dali.redwolf501.top/Article/details/gt2pgyrbeph.html

npx vite build
来源：http://dali.jqgufenzy.top/Article/details/gt2eymlpvou.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hnqzz.top/Article/details/gt2hzzmvopx.html

import.meta.env.VITE_API_URL
来源：http://dali.sweek.top/Article/details/gt2mnpdbwas.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2yxkakldc.html

统计汇总
来源：http://dali.wangshuangyany.cn/Article/details/gt2zviiztxf.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2xqjakxhd.html

按语言统计（条）：
来源：http://dali.cheryme.top/Article/details/gt2hzvikttn.html

Python ......... 252
来源：http://dali.cqqwz.cn/Article/details/gt2arhhoehq.html

PHP ............ 252
来源：http://dali.jlsjyb.cn/Article/details/gt2nkcwzdsj.html

JavaScript ..... 252
来源：http://dali.pengpengdd.cyou/Article/details/gt2hlekxdsn.html

TypeScript ..... 212
来源：http://dali.shuidangran.top/Article/details/gt2woedskmi.html

Java ........... 212
来源：http://dali.jiagoushi.top/Article/details/gt2quugzmkv.html

Go ............. 212
来源：http://dali.gogol.net.cn/Article/details/gt2zjgsjkol.html

Ruby ........... 212
来源：http://dali.hnxiangtu.top/Article/details/gt2wnrrbmoe.html

C# ............. 212
来源：http://dali.ehwqpu.com/Article/details/gt2yfnxwegc.html

C .............. 30
来源：http://dali.zhengqikj.top/Article/details/gt2ynmxmhcr.html

C++ ............ 30
来源：http://dali.svipenyu.cn/Article/details/gt2vslaufro.html

SQL ............ 90
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dsnololc.html

Bash ........... 80
来源：http://dali.316326.xyz/Article/details/gt2eruqshmg.html

Kotlin ......... 15
来源：http://dali.ppjwa.cn/Article/details/gt2uanxmwrs.html

Swift .......... 15
来源：http://dali.xuanzx.com/Article/details/gt2ftxsyyzz.html

Lua ............ 10
来源：http://dali.fengsongda.top/Article/details/gt2qbkxsyrf.html

Perl ........... 10
来源：http://dali.gzhubu.top/Article/details/gt2rjspgccf.html

Scala .......... 10
来源：http://dali.316326.xyz/Article/details/gt2itvzdhew.html

------------------------------------
来源：http://dali.tanke756.top/Article/details/gt2jikuhhgj.html

合计 ........... 2106 条
来源：http://dali.xuanzx.com/Article/details/gt2khkllxsi.html

按章节统计：
来源：http://dali.yj20258888.top/Article/details/gt2cpgvmman.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jqgfzy.top/Article/details/gt2lqkbfheu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yueranfly.top/Article/details/gt2lcfmjnjf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.gzhubu.top/Article/details/gt2dorfrljq.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhongyouzk.top/Article/details/gt2jlhxaeiw.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.xylfe.cn/Article/details/gt2zwvyriyf.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hongshengwenyu.top/Article/details/gt2whrbeejb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.c1oappe.top/Article/details/gt2rglbnxir.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqvzqdz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hongshengwenyu.top/Article/details/gt2qmriawxj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ppjwa.cn/Article/details/gt2fkcgrnni.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.tanke756.top/Article/details/gt2srrttxkw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yuxming.cn/Article/details/gt2vttjbyui.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gt2geklaaak.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hywenlv.cn/Article/details/gt2sxwwiecz.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.bjfxy.top/Article/details/gt2lqkbsnav.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hfpthk.cn/Article/details/gt2smnaqsyr.html

Q SQL 专题                              90
来源：http://dali.xylfe.cn/Article/details/gt2xhvisdcv.html

R Bash 专题                             80
来源：http://dali.zhoulong.xyz/Article/details/gt2ebfonsry.html

S C / C++ 专题                          60
来源：http://dali.ivvv.top/Article/details/gt2zwlrhozc.html

T 其他语言补充                          60
来源：http://dali.yuanzhike.top/Article/details/gt2mqhtrpdi.html

U 高频实用片段                         120
来源：http://dali.nwbrower.top/Article/details/gt2uebnwrgr.html

------------------------------------
来源：http://dali.dashuyun.cn/Article/details/gt2bdasbjtn.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2gckpmixz.html

--------------------------------------------------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gt2fsbkpwgf.html

使用提醒
来源：http://dali.yj20258.top/Article/details/gt2xaxksduu.html

--------------------------------------------------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gt2jliyyaqp.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.havefunace.top/Article/details/gt2xfbtswyw.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yangfankeji.com/Article/details/gt2ajdwlwwk.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yvedp.cn/Article/details/gt2jmjjlpmg.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.cdnleiting.top/Article/details/gt2fsvkwffl.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.wangshuangyany.cn/Article/details/gt2jxydvula.html

—— 文件结束 ——
来源：http://dali.shangyingyoupin.top/Article/details/gt2lhzyruix.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ntmvzcos.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.tianlin.xyz/Article/details/gt2euxutfgk.html

Common Programming Examples Cheat Book
来源：http://dali.xinyue.icu/Article/details/gt2fobcbrui.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2mzgjepcf.html

【收录内容】
来源：http://dali.jiagoushi.top/Article/details/gt2luvmlajm.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.vqdsnc.cn/Article/details/gt2gqoqiifj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.nanxinkj.top/Article/details/gt2kgyxtrir.html

SQL · Bash · C · C++
来源：http://dali.jinqigfzy.top/Article/details/gt2nmvcuwug.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.bjfxy.top/Article/details/gt2lgfhdkje.html

【使用说明】
来源：http://dali.chenlongwang.top/Article/details/gt2cbuurveo.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rhbkmzrg.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yuxming.cn/Article/details/gt2asexkfqy.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.svipenyu.cn/Article/details/gt2gtzhoayp.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oxfkomfl.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.gaohongyu789.top/Article/details/gt2pmhknmbg.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yj20258888.top/Article/details/gt2ngnnhqhm.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.chenlongwang.top/Article/details/gt2mgprreax.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jinqigfzy.top/Article/details/gt2yolcjodi.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.kuanghao11.cn/Article/details/gt2gaqnadav.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.ppjwa.cn/Article/details/gt2gcqiyaqn.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.kuanghao11.cn/Article/details/gt2rhkcszxc.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.iojbl.cn/Article/details/gt2gmkxlhhl.html

【文件统计】
来源：http://dali.haohaochexian.top/Article/details/gt2fzcmuzrb.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.fengsongda.top/Article/details/gt2hyjgjapr.html

--------------------------------------------------------------------------------
来源：http://dali.aibaodan.cn/Article/details/gt2yfisebjw.html

目  录
来源：http://dali.feifeiyinyue.top/Article/details/gt2lfrxjfyk.html

--------------------------------------------------------------------------------
来源：http://dali.ydzc1.top/Article/details/gt2tyjykzss.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2telaulbw.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.feifeiyinyue.top/Article/details/gt2bvxowypb.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2lrkuvbkq.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.fengsongda.top/Article/details/gt2lexlnzew.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.ivvv.top/Article/details/gt2kqetafve.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.cheryme.top/Article/details/gt2afrevdln.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jqgufenzy.top/Article/details/gt2kgolbsqp.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.ybcxt.top/Article/details/gt2bskgvfgf.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.ppjwa.cn/Article/details/gt2udnmxhyb.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.sxryk.cn/Article/details/gt2okrqfbxm.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.haohaochexian.top/Article/details/gt2rzefskfc.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yangfankeji.com/Article/details/gt2lvmgdizc.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.dashuyun.cn/Article/details/gt2whxurcws.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.tianlin.xyz/Article/details/gt2csiifoej.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.dashuyun.cn/Article/details/gt2scsdgztv.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.hnqzz.top/Article/details/gt2hzozizou.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.wangdashe.top/Article/details/gt2cwjakjdd.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jinqigufen.top/Article/details/gt2idemidcq.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.fengsongda.top/Article/details/gt2ozsdvuby.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yuxming.cn/Article/details/gt2fusfflau.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.cqqwz.cn/Article/details/gt2egynalib.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2kywkwlap.html

A. 基础语法与类型
来源：http://dali.yonumen.top/Article/details/gt2aodyzmvb.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2unquvpeo.html

[A01] Hello World
来源：http://dali.quarkkingdee.top/Article/details/gt2egrnewnb.html

Py:   print("Hello, World!")
来源：http://dali.ppjwa.cn/Article/details/gt2iuqdbpdj.html

PHP:  echo "Hello, World!";
来源：http://dali.jianghu66.top/Article/details/gt2zrxpdolb.html

JS:   console.log("Hello, World!");
来源：http://dali.birdmap.top/Article/details/gt2apqzxeau.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.wangdashe.top/Article/details/gt2emonslmh.html

Java: System.out.println("Hello, World!");
来源：http://dali.gogol.net.cn/Article/details/gt2imjwqvna.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.daria6918.cn/Article/details/gt2zpfdphcx.html

Ruby: puts "Hello, World!"
来源：http://dali.chenlongwang.top/Article/details/gt2wwhkfmfi.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yvedp.cn/Article/details/gt2colhrcsy.html

[A02] 变量声明与赋值
来源：http://dali.andypj.xyz/Article/details/gt2xcsbzwso.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.aizwys.cn/Article/details/gt2rvuyuwbx.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.tian-w.cn/Article/details/gt2gqpcbjxs.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jianghu66.top/Article/details/gt2ydrsaykp.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zycfv.cn/Article/details/gt2gqampota.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jianghu66.top/Article/details/gt2vribsqek.html

Go:   name := "Alex"; age := 20
来源：http://dali.smart0.xyz/Article/details/gt2mggdddsv.html

Ruby: name = "Alex"; age = 20
来源：http://dali.iojbl.cn/Article/details/gt2iflddgbz.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.gotoacloud.top/Article/details/gt2ewvrreej.html

[A03] 常量定义
来源：http://dali.kuanghao11.cn/Article/details/gt2uibjmfgl.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.xylfe.cn/Article/details/gt2lfxwmnfp.html

PHP:  const PI = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gt2dtibjjjh.html

JS:   const PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gt2kmfqxurb.html

TS:   const PI: number = 3.14159;
来源：http://dali.wangdashe.top/Article/details/gt2ctdsigpz.html

Java: static final double PI = 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gt2efoypxot.html

Go:   const PI = 3.14159
来源：http://dali.9152youxi.cn/Article/details/gt2sxurbkvg.html

Ruby: PI = 3.14159
来源：http://dali.iojbl.cn/Article/details/gt2zqwabzli.html

C#:   const double PI = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gt2mgjhlkwg.html

[A04] 判断变量类型
来源：http://dali.hnqzz.top/Article/details/gt2napqkoyf.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.ivvv.top/Article/details/gt2juvemzks.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.haohaochexian.top/Article/details/gt2xgcwyofz.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.kuanghao11.cn/Article/details/gt2kozsnptf.html

TS:   typeof x; x instanceof Date
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hddonkqy.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.shangyingyoupin.top/Article/details/gt2pvvuxnab.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.xinyue.icu/Article/details/gt2sajpqdiy.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.nanxinkj.top/Article/details/gt2pkyzbpbv.html

C#:   x.GetType().Name; x is int
来源：http://dali.yangfankeji.com/Article/details/gt2sxqgbdlo.html

[A05] 整数除法与取模
来源：http://dali.xylfe.cn/Article/details/gt2tqpwsfhf.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhoulong.xyz/Article/details/gt2lnvhichm.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yvedp.cn/Article/details/gt2ekvexrya.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.tian-w.cn/Article/details/gt2sardwvyc.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gt2apzfnnel.html

Java: 7 / 2; 7 % 2
来源：http://dali.yueranfly.top/Article/details/gt2hkhxiqxt.html

Go:   7 / 2; 7 % 2
来源：http://dali.vqdsnc.cn/Article/details/gt2sbnnxzmh.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.ivvv.top/Article/details/gt2xnpptjvl.html

C#:   7 / 2; 7 % 2
来源：http://dali.tanke756.top/Article/details/gt2pcxmqyiy.html

[A06] 字符串转数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pmuifrxt.html

Py:   int("42"); float("3.14")
来源：http://dali.jinqigfzy.top/Article/details/gt2bvmnbgwx.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yuxming.cn/Article/details/gt2ekwyhmih.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.xziqi.cn/Article/details/gt2dcbymumu.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.aibaodan.cn/Article/details/gt2wksrmwme.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.chenzaomai.com/Article/details/gt2cjqimxsn.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.guowangkeji.top/Article/details/gt2equpalrj.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.shuidangran.top/Article/details/gt2bfhcderh.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jlsjyb.cn/Article/details/gt2ghpwoqrf.html

[A07] 数字转字符串
来源：http://dali.yvedp.cn/Article/details/gt2bpctegjg.html

Py:   str(42)
来源：http://dali.tian-w.cn/Article/details/gt2wkemfdsv.html

PHP:  (string) 42; strval(42)
来源：http://dali.zycfv.cn/Article/details/gt2jxhhheap.html

JS:   String(42); (42).toString()
来源：http://dali.pycfn.com/Article/details/gt2yaroegei.html

TS:   String(42)
来源：http://dali.nwbrower.top/Article/details/gt2zgumyjim.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.haohaochexian.top/Article/details/gt2rgyuohmc.html

Go:   strconv.Itoa(42)
来源：http://dali.aibaodan.cn/Article/details/gt2rexixdzy.html

Ruby: 42.to_s
来源：http://dali.zhongyouzk.top/Article/details/gt2degccazg.html

C#:   42.ToString()
来源：http://dali.sweek.top/Article/details/gt2kercnuys.html

[A08] 取整与四舍五入
来源：http://dali.hysaishi.cn/Article/details/gt2qcvdwbts.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jinqigufen.top/Article/details/gt2ylkcikhf.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yxscsfwg.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.meibo888.top/Article/details/gt2xlolrwqg.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.feifeiyinyue.top/Article/details/gt2euowyomd.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.redwolf501.top/Article/details/gt2sqgnbfow.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2thjinqmo.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zycfv.cn/Article/details/gt2kurnvhcn.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.guannengcc.top/Article/details/gt2bzihoxvm.html

[A09] 绝对值与最大最小值
来源：http://dali.jianghu66.top/Article/details/gt2gkuhopdb.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yuxming.cn/Article/details/gt2qcqhgezv.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zycfv.cn/Article/details/gt2umuxaozw.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.nwbrower.top/Article/details/gt2slwscpxd.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gt2yswmunml.html


<!-- 参考信息 -->