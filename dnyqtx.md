代发 wailian999

[U63] PHP：文件读写
来源：http://dali.quarkkingdee.top/Article/details/gt2ggukfaqp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.ppjwa.cn/Article/details/gt2xzsmqlnz.html

[U64] PHP：目录遍历
来源：http://dali.zhiwuduotai.top/Article/details/gt2xggfschr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ivvv.top/Article/details/gt2faqktgty.html

[U65] PHP：会话
来源：http://dali.yanxiufei.cn/Article/details/gt2tvhmioja.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.iojbl.cn/Article/details/gt2ckvsiune.html

[U66] PHP：设置 Cookie
来源：http://dali.dianchejie.cn/Article/details/gt2zfrdzxnx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xgjuklre.html

[U67] PHP：处理文件上传
来源：http://dali.aibaodan.cn/Article/details/gt2fbdroklw.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jyoumei.cn/Article/details/gt2trdpcnjk.html

[U68] PHP：PDO 连接
来源：http://dali.hongshengwenyu.top/Article/details/gt2ckxceoca.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.shuidangran.top/Article/details/gt2buwttwnh.html

[U69] PHP：PDO 预处理
来源：http://dali.haohaochexian.top/Article/details/gt2zlwtelkc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.cashguo.top/Article/details/gt2rftjzslo.html

[U70] PHP：PDO 事务
来源：http://dali.smart0.xyz/Article/details/gt2surkccvc.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hywenlv.cn/Article/details/gt2ubdzwvxu.html

[U71] PHP：抛出异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2acbcfhzo.html

throw new RuntimeException("失败", 500);
来源：http://dali.9152youxi.cn/Article/details/gt2paipzzgz.html

[U72] PHP：写错误日志
来源：http://dali.birdmap.top/Article/details/gt2batmsrfw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jlsjyb.cn/Article/details/gt2wylsgfoc.html

[U73] PHP：读取 ini 配置
来源：http://dali.nanxuanxn.top/Article/details/gt2ackvlqnr.html

parse_ini_file("config.ini", true)
来源：http://dali.chenzaomai.com/Article/details/gt2yxrxjknl.html

[U74] PHP：读取环境变量
来源：http://dali.bjfxy.top/Article/details/gt2cniwwvdj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.hysaishi.cn/Article/details/gt2dwguxwau.html

[U75] PHP：依赖注入
来源：http://dali.zhengqikj.top/Article/details/gt2hxjdojkv.html

composer require psr/container
来源：http://dali.yj20258888.top/Article/details/gt2gvopcteb.html

[U76] PHP：简单路由
来源：http://dali.yvedp.cn/Article/details/gt2dscbwcll.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.gaohongyu789.top/Article/details/gt2cjntutsw.html

[U77] PHP：模板渲染
来源：http://dali.guowangkeji.top/Article/details/gt2jioxcmox.html

composer require twig/twig
来源：http://dali.sweek.top/Article/details/gt2lsjbtost.html

[U78] PHP：单元测试
来源：http://dali.ivvv.top/Article/details/gt2dcwsxmds.html

composer require --dev phpunit/phpunit
来源：http://dali.cheryme.top/Article/details/gt2wdsudczu.html

[U79] PHP：静态分析
来源：http://dali.chenzaomai.com/Article/details/gt2ixmgikwf.html

composer require --dev phpstan/phpstan
来源：http://dali.zhixingplan.top/Article/details/gt2cucgtuil.html

[U80] PHP：代码规范修复
来源：http://dali.chenzaomai.com/Article/details/gt2ckxyufsp.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.tianlin.xyz/Article/details/gt2zvmfgmyr.html

[U81] JS：初始化项目
来源：http://dali.xuetiantiany.cn/Article/details/gt2yrglgynt.html

npm init -y;  npm i express
来源：http://dali.jianghu66.top/Article/details/gt2rbnttdxu.html

[U82] JS：package.json 脚本
来源：http://dali.feifeiyinyue.top/Article/details/gt2wnelzihg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.nanxinkj.top/Article/details/gt2echvkhal.html

[U83] JS：ES Module 导入导出
来源：http://dali.zycfv.cn/Article/details/gt2cbcznbiy.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.iojbl.cn/Article/details/gt2jqcogvpu.html

[U84] JS：CommonJS 写法
来源：http://dali.gzhubu.top/Article/details/gt2kqegtdka.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fujwgndu.html

[U85] JS：可选链
来源：http://dali.tianlin.xyz/Article/details/gt2ispkqeth.html

a?.b?.c
来源：http://dali.sweek.top/Article/details/gt2nmaecyqk.html

[U86] JS：空值合并
来源：http://dali.hnqzz.top/Article/details/gt2azuzlxcn.html

a ?? b
来源：http://dali.zhiwuduotai.top/Article/details/gt2ngmhbhjt.html

[U87] JS：解构默认值
来源：http://dali.hammf.cn/Article/details/gt2dsnbowtl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hnxiangtu.top/Article/details/gt2bplzvakh.html

[U88] JS：对象展开合并
来源：http://dali.bjfxy.top/Article/details/gt2psjqtfoz.html

{ ...a, ...b }
来源：http://dali.ppjwa.cn/Article/details/gt2onehrzys.html

[U89] JS：数组去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bmzxjgdp.html

[...new Set(arr)]
来源：http://dali.snrcjt.cn/Article/details/gt2mybnysxt.html

[U90] JS：数字数组排序
来源：http://dali.xuetiantiany.cn/Article/details/gt2ixavuwvo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yj20258.top/Article/details/gt2ehnikrtj.html

[U91] JS：对象键值遍历
来源：http://dali.yuanzhike.top/Article/details/gt2tkgaqrsj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.fzhhl.top/Article/details/gt2lcryxumi.html

[U92] JS：深拷贝
来源：http://dali.meibo888.top/Article/details/gt2cejotzho.html

structuredClone(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2vbcyszdq.html

[U93] JS：模板字符串
来源：http://dali.svipenyu.cn/Article/details/gt2vxvqrvwc.html

`共 ${n} 条`
来源：http://dali.jinqigufen.top/Article/details/gt2ahhtpifk.html

[U94] JS：箭头函数
来源：http://dali.gzhubu.top/Article/details/gt2espubsmh.html

const double = x => x * 2;
来源：http://dali.andypj.xyz/Article/details/gt2iasotcrg.html

[U95] JS：Promise 包装
来源：http://dali.hammf.cn/Article/details/gt2dqpxtect.html

new Promise((resolve, reject) => {})
来源：http://dali.zhixingplan.top/Article/details/gt2gikpmafv.html

[U96] JS：async/await 与异常
来源：http://dali.haohaochexian.top/Article/details/gt2fqwhhsca.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gt2xmpbwlou.html

[U97] JS：并发请求
来源：http://dali.tian-w.cn/Article/details/gt2iywafblt.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258888.top/Article/details/gt2uxgqcyjt.html

[U98] JS：fetch 带 JSON
来源：http://dali.jinqigfzy.top/Article/details/gt2vjwzzlhq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shuidangran.top/Article/details/gt2awthomtm.html

[U99] JS：事件监听
来源：http://dali.hongshengwenyu.top/Article/details/gt2ryuodwrv.html

el.addEventListener("click", e => {})
来源：http://dali.zhoulong.xyz/Article/details/gt2bfjeiplr.html

[U100] JS：DOM 查询
来源：http://dali.ppjwa.cn/Article/details/gt2bayhttmm.html

document.querySelector(".item")
来源：http://dali.mhx1999.top/Article/details/gt2darcqueb.html

[U101] JS：classList 操作
来源：http://dali.yongpay.top/Article/details/gt2hsnltggp.html

el.classList.toggle("active")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hkjhdzqb.html

[U102] JS：本地存储
来源：http://dali.tian-w.cn/Article/details/gt2bhcxysrx.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.sufxvd.cn/Article/details/gt2foejnzba.html

[U103] JS：定时器
来源：http://dali.sufxvd.cn/Article/details/gt2nqgbkhre.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.havefunace.top/Article/details/gt2krxrnzni.html

[U104] JS：防抖
来源：http://dali.xinyue.icu/Article/details/gt2qpykvlgc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hfpthk.cn/Article/details/gt2lffwidwo.html

[U105] JS：节流
来源：http://dali.ivvv.top/Article/details/gt2hjknwqdk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.smart0.xyz/Article/details/gt2knlhkyei.html

[U106] JS：日期格式化
来源：http://dali.andypj.xyz/Article/details/gt2znaddqhw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hongshengwenyu.top/Article/details/gt2bylefsiv.html

[U107] JS：数字千分位
来源：http://dali.sufxvd.cn/Article/details/gt2jggxikai.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yj20258888.top/Article/details/gt2nzjxkbow.html

[U108] JS：随机整数
来源：http://dali.gotoacloud.top/Article/details/gt2xqnawyrc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.wangshuangyany.cn/Article/details/gt2erpcgtke.html

[U109] JS：数组分组
来源：http://dali.havefunace.top/Article/details/gt2mccpfihu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.haohaochexian.top/Article/details/gt2xhnwcnml.html

[U110] JS：数组分块
来源：http://dali.yj202588.top/Article/details/gt2jqmmyodm.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kqrtkqdz.html

[U111] JS：对象转 Map
来源：http://dali.ydzc1.top/Article/details/gt2dfixcrrw.html

new Map(Object.entries(obj))
来源：http://dali.sufxvd.cn/Article/details/gt2igewevoy.html

[U112] JS：字符串补位
来源：http://dali.cheryme.top/Article/details/gt2hrbcwaje.html

"7".padStart(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gt2gscmvdoc.html

[U113] JS：正则替换全部
来源：http://dali.yuanzhike.top/Article/details/gt2mnfonbwl.html

s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gt2auopzsdq.html

[U114] JS：JSON 深比较
来源：http://dali.ybcxt.top/Article/details/gt2pitzlqym.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xinyue.icu/Article/details/gt2nchltdts.html

[U115] JS：生成 UUID
来源：http://dali.sxryk.cn/Article/details/gt2agbvsgsk.html

crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gt2pmrebdkm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.wangshuangyany.cn/Article/details/gt2agzmqigy.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xziqi.cn/Article/details/gt2etgujehf.html

[U117] JS：单元测试
来源：http://dali.feifeiyinyue.top/Article/details/gt2kvxchtng.html

npm i -D vitest;  npx vitest
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fglncmxa.html

[U118] JS：开发服务器
来源：http://dali.zhongyouzk.top/Article/details/gt2pxgjypgf.html

npm i -D vite;  npx vite
来源：http://dali.hnqzz.top/Article/details/gt2ctgzpsms.html

[U119] JS：生产构建
来源：http://dali.yangfankeji.com/Article/details/gt2acyvrkwt.html

npx vite build
来源：http://dali.yuanzhike.top/Article/details/gt2cipzppac.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zdqjudy.top/Article/details/gt2gdbrlciz.html

import.meta.env.VITE_API_URL
来源：http://dali.sufxvd.cn/Article/details/gt2ojcfdlig.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2jtlupmxr.html

统计汇总
来源：http://dali.xylfe.cn/Article/details/gt2lrbelzfy.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2hppzzgti.html

按语言统计（条）：
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jrjjzwzy.html

Python ......... 252
来源：http://dali.redwolf501.top/Article/details/gt2lmxdxwhw.html

PHP ............ 252
来源：http://dali.yuanzhike.top/Article/details/gt2dxrmdqzn.html

JavaScript ..... 252
来源：http://dali.shzxlz.cn/Article/details/gt2fngnhlld.html

TypeScript ..... 212
来源：http://dali.chenlongwang.top/Article/details/gt2dwcffmpn.html

Java ........... 212
来源：http://dali.xuetiantiany.cn/Article/details/gt2ybqamoho.html

Go ............. 212
来源：http://dali.aibaodan.cn/Article/details/gt2rivgyckp.html

Ruby ........... 212
来源：http://dali.hnqzz.top/Article/details/gt2fhldrsou.html

C# ............. 212
来源：http://dali.yongpay.top/Article/details/gt2kjbiqjwo.html

C .............. 30
来源：http://dali.xuetiantiany.cn/Article/details/gt2swhmsrgo.html

C++ ............ 30
来源：http://dali.yj20258.top/Article/details/gt2vyqcyiwx.html

SQL ............ 90
来源：http://dali.yvedp.cn/Article/details/gt2jtqgiwgp.html

Bash ........... 80
来源：http://dali.jinqigufen.top/Article/details/gt2emobwulb.html

Kotlin ......... 15
来源：http://dali.xinyue.icu/Article/details/gt2tshcdeex.html

Swift .......... 15
来源：http://dali.zhixingplan.top/Article/details/gt2kfjxshmu.html

Lua ............ 10
来源：http://dali.gogol.net.cn/Article/details/gt2kkbqfpql.html

Perl ........... 10
来源：http://dali.vqdsnc.cn/Article/details/gt2wcadptjb.html

Scala .......... 10
来源：http://dali.shangyingyoupin.top/Article/details/gt2xekcodad.html

------------------------------------
来源：http://dali.meibo888.top/Article/details/gt2nadbvhdr.html

合计 ........... 2106 条
来源：http://dali.mhx1999.top/Article/details/gt2bvwetvnh.html

按章节统计：
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xkssybnm.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.aibaodan.cn/Article/details/gt2flznsaxc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.sufxvd.cn/Article/details/gt2yraiihqx.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.guannengcc.top/Article/details/gt2nblmcvhq.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.guowangkeji.top/Article/details/gt2hbjrzfik.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.xylfe.cn/Article/details/gt2rtnbjzph.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.0kj1m.cn/Article/details/gt2uewvorup.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.chenlongwang.top/Article/details/gt2ooircvlm.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.guannengcc.top/Article/details/gt2bekchxkq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yonumen.top/Article/details/gt2xwpdfibs.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.sxryk.cn/Article/details/gt2qrizzxor.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hnxiangtu.top/Article/details/gt2pchsmezs.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yj20258888.top/Article/details/gt2dbwvzgsn.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.fengsongda.top/Article/details/gt2oarhqthg.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.cdnleiting.top/Article/details/gt2zctupeot.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.0kj1m.cn/Article/details/gt2rlryhjsf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gt2smevipmc.html

Q SQL 专题                              90
来源：http://dali.xylfe.cn/Article/details/gt2itiyyies.html

R Bash 专题                             80
来源：http://dali.zhengqikj.top/Article/details/gt2hlwobsgm.html

S C / C++ 专题                          60
来源：http://dali.hfpthk.cn/Article/details/gt2pocnsoan.html

T 其他语言补充                          60
来源：http://dali.9152youxi.cn/Article/details/gt2efyvbsrw.html

U 高频实用片段                         120
来源：http://dali.gaohongyu789.top/Article/details/gt2hihzugth.html

------------------------------------
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zudwndjj.html

合计                                  2106 条
来源：http://dali.daria6918.cn/Article/details/gt2mkkissyk.html

--------------------------------------------------------------------------------
来源：http://dali.cucudq.cn/Article/details/gt2huklgsxh.html

使用提醒
来源：http://dali.hongshengwenyu.top/Article/details/gt2pnofcvog.html

--------------------------------------------------------------------------------
来源：http://dali.nanxinkj.top/Article/details/gt2zavkxinb.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.pengpengdd.cyou/Article/details/gt2onwvxurp.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yanxiufei.cn/Article/details/gt2efpzvaiw.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.shanyushiyangtech.top/Article/details/gt2unetlrvg.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yuanzhike.top/Article/details/gt2ohkeikak.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.fengsongda.top/Article/details/gt2goglgqqc.html

—— 文件结束 ——
来源：http://dali.vqdsnc.cn/Article/details/gt2rsipledj.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2vjsixdvi.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vttvpvcg.html

Common Programming Examples Cheat Book
来源：http://dali.jinqigfzy.top/Article/details/gt2fdohtiqf.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2ndfxanzh.html

【收录内容】
来源：http://dali.jqgufenzy.top/Article/details/gt2jtgjshyz.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.vqdsnc.cn/Article/details/gt2ydimhblm.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.hfpthk.cn/Article/details/gt2vkdehigc.html

SQL · Bash · C · C++
来源：http://dali.hnxiangtu.top/Article/details/gt2gsnhqifl.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yongpay.top/Article/details/gt2ivhocgii.html

【使用说明】
来源：http://dali.yangfankeji.com/Article/details/gt2tjcjyary.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.fengsongda.top/Article/details/gt2sqcaayeb.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.ppjwa.cn/Article/details/gt2zizikcuu.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jqgfzy.top/Article/details/gt2hhcoseau.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.smart0.xyz/Article/details/gt2ysrialvh.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.ehwqpu.com/Article/details/gt2uiftfbig.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.fengsongda.top/Article/details/gt2pysryqfs.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.hammf.cn/Article/details/gt2spuibqnz.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.gzhubu.top/Article/details/gt2ghpdzpzl.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yj20258888.top/Article/details/gt2xssjhhuk.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.gaohongyu789.top/Article/details/gt2oxwkscnd.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.ppjwa.cn/Article/details/gt2eeotbije.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zycfv.cn/Article/details/gt2ggdxxenp.html

【文件统计】
来源：http://dali.mhx1999.top/Article/details/gt2qombpxub.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.cqqwz.cn/Article/details/gt2wggmqhgx.html

--------------------------------------------------------------------------------
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pxkyfqbz.html

目  录
来源：http://dali.pengpengdd.cyou/Article/details/gt2owytmtwl.html

--------------------------------------------------------------------------------
来源：http://dali.cucudq.cn/Article/details/gt2hbqvnwnp.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.snrcjt.cn/Article/details/gt2itkshuyc.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.shuidangran.top/Article/details/gt2lmfpfmjl.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.kuanghao11.cn/Article/details/gt2ndmhnbfv.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mcajwwnq.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2fzoakher.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.iojbl.cn/Article/details/gt2khvlpwtx.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2btflupqd.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.tianlin.xyz/Article/details/gt2nsamrtkn.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhixingplan.top/Article/details/gt2aajpkrrg.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.hongshengwenyu.top/Article/details/gt2vewaiqcs.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yuanzhike.top/Article/details/gt2jffwrypr.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yj202588.top/Article/details/gt2pyzwxwaj.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.xuanzx.com/Article/details/gt2mjqgjvfl.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.nanxinkj.top/Article/details/gt2nojcbbdo.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.shzxlz.cn/Article/details/gt2elbimrxd.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.sxryk.cn/Article/details/gt2wowyjfap.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.ehwqpu.com/Article/details/gt2xxnpyfcm.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.xinyue.icu/Article/details/gt2cbwnsxrb.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yuanzhike.top/Article/details/gt2cxlmcvyg.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenzaomai.com/Article/details/gt2luhffsek.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.fzhhl.top/Article/details/gt2fkdksqed.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2giqbegcs.html

A. 基础语法与类型
来源：http://dali.chenzaomai.com/Article/details/gt2fohwssph.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2wxzxkxsa.html

[A01] Hello World
来源：http://dali.snrcjt.cn/Article/details/gt2wxdpxhwi.html

Py:   print("Hello, World!")
来源：http://dali.xziqi.cn/Article/details/gt2isjdgyjx.html

PHP:  echo "Hello, World!";
来源：http://dali.nanxinkj.top/Article/details/gt2uvlsuuhk.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcmjtot.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.tanke756.top/Article/details/gt2eupcizpp.html

Java: System.out.println("Hello, World!");
来源：http://dali.hnqzz.top/Article/details/gt2zuchtckr.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.sufxvd.cn/Article/details/gt2esmlwaxu.html

Ruby: puts "Hello, World!"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2smriaoqy.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.cheryme.top/Article/details/gt2ujsreneo.html

[A02] 变量声明与赋值
来源：http://dali.quarkkingdee.top/Article/details/gt2nxbjjzrq.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhixingplan.top/Article/details/gt2qrvfpjeb.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.mhx1999.top/Article/details/gt2nawuiyew.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.snrcjt.cn/Article/details/gt2bgpiytkr.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.snrcjt.cn/Article/details/gt2vcorjbcm.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.xylfe.cn/Article/details/gt2bbasnlfb.html

Go:   name := "Alex"; age := 20
来源：http://dali.cdnleiting.top/Article/details/gt2dnejsord.html

Ruby: name = "Alex"; age = 20
来源：http://dali.svipenyu.cn/Article/details/gt2xxtjsfaf.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jiagoushi.top/Article/details/gt2rhauobny.html

[A03] 常量定义
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qdedggbg.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.xylfe.cn/Article/details/gt2znrhbnsq.html

PHP:  const PI = 3.14159;
来源：http://dali.andypj.xyz/Article/details/gt2ewofxdsg.html

JS:   const PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gt2dfweuvli.html

TS:   const PI: number = 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gt2vuzlqjun.html

Java: static final double PI = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ejtbbspd.html

Go:   const PI = 3.14159
来源：http://dali.iojbl.cn/Article/details/gt2xkllskot.html

Ruby: PI = 3.14159
来源：http://dali.vqdsnc.cn/Article/details/gt2tfapsatt.html

C#:   const double PI = 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gt2myxwajcf.html

[A04] 判断变量类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2qzwbiuhe.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.hfpthk.cn/Article/details/gt2dumkyhhp.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.hywenlv.cn/Article/details/gt2tnsatpby.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.xylfe.cn/Article/details/gt2nceyuejt.html

TS:   typeof x; x instanceof Date
来源：http://dali.gzhubu.top/Article/details/gt2ddgtrjfr.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.nwbrower.top/Article/details/gt2yjqemqnt.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.0kj1m.cn/Article/details/gt2oibxmtep.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.hfpthk.cn/Article/details/gt2lhqbhiws.html

C#:   x.GetType().Name; x is int
来源：http://dali.sweek.top/Article/details/gt2xytxeafh.html

[A05] 整数除法与取模
来源：http://dali.smart0.xyz/Article/details/gt2pxbkpmvi.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.dianchejie.cn/Article/details/gt2tjrptgzv.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gt2qqkzkeke.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yonumen.top/Article/details/gt2mgouqjhm.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gt2ubeuechi.html

Java: 7 / 2; 7 % 2
来源：http://dali.kuanghao11.cn/Article/details/gt2vrzogbjd.html

Go:   7 / 2; 7 % 2
来源：http://dali.andypj.xyz/Article/details/gt2yxlgxfyo.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.guannengcc.top/Article/details/gt2fwgkuzia.html

C#:   7 / 2; 7 % 2
来源：http://dali.cheryme.top/Article/details/gt2bvxahrht.html

[A06] 字符串转数字
来源：http://dali.pycfn.com/Article/details/gt2erticjyp.html

Py:   int("42"); float("3.14")
来源：http://dali.zhoulong.xyz/Article/details/gt2xuhzrrsh.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.chenzaomai.com/Article/details/gt2rhuyfzwk.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.vqdsnc.cn/Article/details/gt2odjgafto.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zycfv.cn/Article/details/gt2xrnimapi.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2swzthtbn.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.cucudq.cn/Article/details/gt2xquufaro.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.haohaochexian.top/Article/details/gt2ikdpfkrf.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yj20258888.top/Article/details/gt2wmrlgtrn.html

[A07] 数字转字符串
来源：http://dali.sufxvd.cn/Article/details/gt2tufaedbv.html

Py:   str(42)
来源：http://dali.svipenyu.cn/Article/details/gt2wsibnkxi.html

PHP:  (string) 42; strval(42)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2upfslggh.html

JS:   String(42); (42).toString()
来源：http://dali.chenzaomai.com/Article/details/gt2ajswpkpi.html

TS:   String(42)
来源：http://dali.zhengqikj.top/Article/details/gt2dcjiqjel.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.redwolf501.top/Article/details/gt2kcpjldhk.html

Go:   strconv.Itoa(42)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hdtqpnwr.html

Ruby: 42.to_s
来源：http://dali.chenjidiqi.icu/Article/details/gt2jqyeyemn.html

C#:   42.ToString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wrflkpyr.html

[A08] 取整与四舍五入
来源：http://dali.shzxlz.cn/Article/details/gt2yxcqymcq.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.hfpthk.cn/Article/details/gt2ginfjzeg.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.chenlongwang.top/Article/details/gt2fxzxikrj.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.sweek.top/Article/details/gt2rheeohmb.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2bveicbzk.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.redwolf501.top/Article/details/gt2jfjibiwr.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhongyouzk.top/Article/details/gt2kldtbmxz.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yueranfly.top/Article/details/gt2xehguata.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.cucudq.cn/Article/details/gt2ergoozce.html

[A09] 绝对值与最大最小值
来源：http://dali.sxryk.cn/Article/details/gt2moimuktp.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.dashuyun.cn/Article/details/gt2hcljqqcz.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gt2jxevxpbt.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.cqqwz.cn/Article/details/gt2ymnzujuu.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.ydzc1.top/Article/details/gt2xaghgtqm.html


<!-- 参考信息 -->