代发 wailian999

[U59] PHP：自定义排序
来源：http://dali.hfpthk.cn/Article/details/gt2nuugvesv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jianghu66.top/Article/details/gt2pwrueohd.html

[U60] PHP：JSON 编解码
来源：http://dali.ehwqpu.com/Article/details/gt2puzwawgx.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.guannengcc.top/Article/details/gt2oktrtpul.html

[U61] PHP：正则
来源：http://dali.jinghuilouyu.cn/Article/details/gt2blrmlywg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yongpay.top/Article/details/gt2looxvflk.html

[U62] PHP：日期对象
来源：http://dali.tian-w.cn/Article/details/gt2hurktcok.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.fengsongda.top/Article/details/gt2xtbcskhm.html

[U63] PHP：文件读写
来源：http://dali.redwolf501.top/Article/details/gt2yofnxluq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zdqjudy.top/Article/details/gt2emekhbrp.html

[U64] PHP：目录遍历
来源：http://dali.hongshengwenyu.top/Article/details/gt2vnqucmfz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ybcxt.top/Article/details/gt2lnqckjza.html

[U65] PHP：会话
来源：http://dali.sysykeji.top/Article/details/gt2sfnmeioa.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.316326.xyz/Article/details/gt2skuksvfa.html

[U66] PHP：设置 Cookie
来源：http://dali.jlsjyb.cn/Article/details/gt2iwyrtkms.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vseajece.html

[U67] PHP：处理文件上传
来源：http://dali.quarkkingdee.top/Article/details/gt2ifeepzfk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jlsjyb.cn/Article/details/gt2esdwbltj.html

[U68] PHP：PDO 连接
来源：http://dali.c1oappe.top/Article/details/gt2cxdtiqsn.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.andypj.xyz/Article/details/gt2iqjpahfy.html

[U69] PHP：PDO 预处理
来源：http://dali.yueranfly.top/Article/details/gt2vwxjkcwx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.fengsongda.top/Article/details/gt2uslsgujm.html

[U70] PHP：PDO 事务
来源：http://dali.xylfe.cn/Article/details/gt2bshbzsjm.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.sysykeji.top/Article/details/gt2wywvfgmz.html

[U71] PHP：抛出异常
来源：http://dali.cdnleiting.top/Article/details/gt2nfpwqzjo.html

throw new RuntimeException("失败", 500);
来源：http://dali.havefunace.top/Article/details/gt2zpwmybjl.html

[U72] PHP：写错误日志
来源：http://dali.zdqjudy.top/Article/details/gt2sscpxeev.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yj202588.top/Article/details/gt2mfhrreyq.html

[U73] PHP：读取 ini 配置
来源：http://dali.wangdashe.top/Article/details/gt2bevrajfa.html

parse_ini_file("config.ini", true)
来源：http://dali.hongshengwenyu.top/Article/details/gt2udmbikcb.html

[U74] PHP：读取环境变量
来源：http://dali.yuxming.cn/Article/details/gt2glapuhtk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zycfv.cn/Article/details/gt2eofnkprg.html

[U75] PHP：依赖注入
来源：http://dali.havefunace.top/Article/details/gt2efuttipm.html

composer require psr/container
来源：http://dali.yuxming.cn/Article/details/gt2ixysexzd.html

[U76] PHP：简单路由
来源：http://dali.jyoumei.cn/Article/details/gt2lhyivvbl.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.daxiang520.top/Article/details/gt2hnluiihw.html

[U77] PHP：模板渲染
来源：http://dali.yonumen.top/Article/details/gt2txylvxxz.html

composer require twig/twig
来源：http://dali.chenlongwang.top/Article/details/gt2eiyksxay.html

[U78] PHP：单元测试
来源：http://dali.iojbl.cn/Article/details/gt2ddmxezmp.html

composer require --dev phpunit/phpunit
来源：http://dali.yj202588.top/Article/details/gt2viwhrslk.html

[U79] PHP：静态分析
来源：http://dali.tianlin.xyz/Article/details/gt2onbvpyvl.html

composer require --dev phpstan/phpstan
来源：http://dali.chenjidiqi.icu/Article/details/gt2ogxmxnrt.html

[U80] PHP：代码规范修复
来源：http://dali.ybcxt.top/Article/details/gt2bswwoods.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.ydzc1.top/Article/details/gt2jwynhoht.html

[U81] JS：初始化项目
来源：http://dali.pengpengdd.cyou/Article/details/gt2tmnudoss.html

npm init -y;  npm i express
来源：http://dali.tanke756.top/Article/details/gt2lilfvvtg.html

[U82] JS：package.json 脚本
来源：http://dali.gaohongyu789.top/Article/details/gt2owpvlutb.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zdqjudy.top/Article/details/gt2arweqwag.html

[U83] JS：ES Module 导入导出
来源：http://dali.haohaochexian.top/Article/details/gt2kxmnolgk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.guannengcc.top/Article/details/gt2ychlqgak.html

[U84] JS：CommonJS 写法
来源：http://dali.c1oappe.top/Article/details/gt2bipertdt.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.redwolf501.top/Article/details/gt2pizcnbhe.html

[U85] JS：可选链
来源：http://dali.pycfn.com/Article/details/gt2zkixoycw.html

a?.b?.c
来源：http://dali.tian-w.cn/Article/details/gt2nuufyfii.html

[U86] JS：空值合并
来源：http://dali.jianghu66.top/Article/details/gt2vbftxzod.html

a ?? b
来源：http://dali.zhengqikj.top/Article/details/gt2okwagnwb.html

[U87] JS：解构默认值
来源：http://dali.mhx1999.top/Article/details/gt2lkbovglj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.iojbl.cn/Article/details/gt2rwashcfa.html

[U88] JS：对象展开合并
来源：http://dali.hammf.cn/Article/details/gt2blnmvlgt.html

{ ...a, ...b }
来源：http://dali.xuetiantiany.cn/Article/details/gt2yksulmso.html

[U89] JS：数组去重
来源：http://dali.sufxvd.cn/Article/details/gt2eysvztql.html

[...new Set(arr)]
来源：http://dali.guowangkeji.top/Article/details/gt2axpgniky.html

[U90] JS：数字数组排序
来源：http://dali.wangdashe.top/Article/details/gt2lzeebnow.html

[...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gt2yyjvtjhg.html

[U91] JS：对象键值遍历
来源：http://dali.0kj1m.cn/Article/details/gt2qcvhxnep.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.gaohongyu789.top/Article/details/gt2wgsicosp.html

[U92] JS：深拷贝
来源：http://dali.guowangkeji.top/Article/details/gt2otkyvgef.html

structuredClone(obj)
来源：http://dali.yueranfly.top/Article/details/gt2pzobgkfg.html

[U93] JS：模板字符串
来源：http://dali.yvedp.cn/Article/details/gt2pqiixlic.html

`共 ${n} 条`
来源：http://dali.wangdashe.top/Article/details/gt2cifbajme.html

[U94] JS：箭头函数
来源：http://dali.gaohongyu789.top/Article/details/gt2wsfoznhp.html

const double = x => x * 2;
来源：http://dali.bjfxy.top/Article/details/gt2kheqybqn.html

[U95] JS：Promise 包装
来源：http://dali.sxryk.cn/Article/details/gt2fyvfspoy.html

new Promise((resolve, reject) => {})
来源：http://dali.smart0.xyz/Article/details/gt2xxwpouen.html

[U96] JS：async/await 与异常
来源：http://dali.vqdsnc.cn/Article/details/gt2psvtjyjd.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jlsjyb.cn/Article/details/gt2ffrhgofs.html

[U97] JS：并发请求
来源：http://dali.jyoumei.cn/Article/details/gt2hdxmrivx.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.316326.xyz/Article/details/gt2igmfvgax.html

[U98] JS：fetch 带 JSON
来源：http://dali.tian-w.cn/Article/details/gt2amvbolvp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.ivvv.top/Article/details/gt2rmlfiekk.html

[U99] JS：事件监听
来源：http://dali.vqdsnc.cn/Article/details/gt2vrwpbdms.html

el.addEventListener("click", e => {})
来源：http://dali.cashguo.top/Article/details/gt2pgmsesjh.html

[U100] JS：DOM 查询
来源：http://dali.gzhubu.top/Article/details/gt2wnzhpkmz.html

document.querySelector(".item")
来源：http://dali.xuanzx.com/Article/details/gt2nntdvxyl.html

[U101] JS：classList 操作
来源：http://dali.wangdashe.top/Article/details/gt2kdyoovwv.html

el.classList.toggle("active")
来源：http://dali.yueranfly.top/Article/details/gt2ugqqxlpb.html

[U102] JS：本地存储
来源：http://dali.daxiang520.top/Article/details/gt2qxqqjlsf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yj202588.top/Article/details/gt2mnecophm.html

[U103] JS：定时器
来源：http://dali.hnqzz.top/Article/details/gt2apgusugf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zycfv.cn/Article/details/gt2hndqemld.html

[U104] JS：防抖
来源：http://dali.meibo888.top/Article/details/gt2qpksewdu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tanke756.top/Article/details/gt2kfhifipp.html

[U105] JS：节流
来源：http://dali.hysaishi.cn/Article/details/gt2dtwrtxbg.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.vqdsnc.cn/Article/details/gt2uehgobox.html

[U106] JS：日期格式化
来源：http://dali.yanxiufei.cn/Article/details/gt2ohqyfgwq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.shuidangran.top/Article/details/gt2bfppkppl.html

[U107] JS：数字千分位
来源：http://dali.jyoumei.cn/Article/details/gt2sqslaedz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jinqigfzy.top/Article/details/gt2ujskhcxz.html

[U108] JS：随机整数
来源：http://dali.xuetiantiany.cn/Article/details/gt2xoqlqxqg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.c1oappe.top/Article/details/gt2bjihxlim.html

[U109] JS：数组分组
来源：http://dali.9152youxi.cn/Article/details/gt2ydnevogj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yvedp.cn/Article/details/gt2jugnsfzi.html

[U110] JS：数组分块
来源：http://dali.zhoulong.xyz/Article/details/gt2hxjnfhxf.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yvedp.cn/Article/details/gt2xmrdomio.html

[U111] JS：对象转 Map
来源：http://dali.wangdashe.top/Article/details/gt2taysoarq.html

new Map(Object.entries(obj))
来源：http://dali.dashuyun.cn/Article/details/gt2aywsmjct.html

[U112] JS：字符串补位
来源：http://dali.nanxuanxn.top/Article/details/gt2pqkuetnx.html

"7".padStart(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gt2nrahkefw.html

[U113] JS：正则替换全部
来源：http://dali.smart0.xyz/Article/details/gt2ybapdqlv.html

s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gt2oaibytol.html

[U114] JS：JSON 深比较
来源：http://dali.sxryk.cn/Article/details/gt2nnwdmulp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2azzahkih.html

[U115] JS：生成 UUID
来源：http://dali.kuanghao11.cn/Article/details/gt2pwpwwjkp.html

crypto.randomUUID()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kakunqlm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.0kj1m.cn/Article/details/gt2pzebgovy.html

/** @param {string} name */ function f(name) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2fxbobjxj.html

[U117] JS：单元测试
来源：http://dali.shzxlz.cn/Article/details/gt2uznezohu.html

npm i -D vitest;  npx vitest
来源：http://dali.tanke756.top/Article/details/gt2zxgrwsqp.html

[U118] JS：开发服务器
来源：http://dali.shzxlz.cn/Article/details/gt2nyeekmrk.html

npm i -D vite;  npx vite
来源：http://dali.shzxlz.cn/Article/details/gt2qdkifeit.html

[U119] JS：生产构建
来源：http://dali.vqdsnc.cn/Article/details/gt2pbrpusil.html

npx vite build
来源：http://dali.cucudq.cn/Article/details/gt2dcvkukdc.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.tian-w.cn/Article/details/gt2tskjiacf.html

import.meta.env.VITE_API_URL
来源：http://dali.yj20258888.top/Article/details/gt2cftwufge.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2dyncrdvm.html

统计汇总
来源：http://dali.shzxlz.cn/Article/details/gt2pxhnyeff.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2wbgktquv.html

按语言统计（条）：
来源：http://dali.wangshuangyany.cn/Article/details/gt2hnjnxpvk.html

Python ......... 252
来源：http://dali.ppjwa.cn/Article/details/gt2atjqrsyg.html

PHP ............ 252
来源：http://dali.c1oappe.top/Article/details/gt2uqbuwcsc.html

JavaScript ..... 252
来源：http://dali.tianlin.xyz/Article/details/gt2zuhatahf.html

TypeScript ..... 212
来源：http://dali.birdmap.top/Article/details/gt2hvtlcnbs.html

Java ........... 212
来源：http://dali.kuanghao11.cn/Article/details/gt2gqycdups.html

Go ............. 212
来源：http://dali.hfpthk.cn/Article/details/gt2ynyvzxcj.html

Ruby ........... 212
来源：http://dali.daxiang520.top/Article/details/gt2zcfzrcjj.html

C# ............. 212
来源：http://dali.sxryk.cn/Article/details/gt2qjzgquqj.html

C .............. 30
来源：http://dali.shuidangran.top/Article/details/gt2bweqzxan.html

C++ ............ 30
来源：http://dali.guowangkeji.top/Article/details/gt2gqlrcvzd.html

SQL ............ 90
来源：http://dali.c1oappe.top/Article/details/gt2owbpxenc.html

Bash ........... 80
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fydowisf.html

Kotlin ......... 15
来源：http://dali.andypj.xyz/Article/details/gt2uriurnaa.html

Swift .......... 15
来源：http://dali.fzhhl.top/Article/details/gt2jgvbdbqq.html

Lua ............ 10
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2avcrgxqq.html

Perl ........... 10
来源：http://dali.smart0.xyz/Article/details/gt2jemdmqft.html

Scala .......... 10
来源：http://dali.snrcjt.cn/Article/details/gt2xocvqmip.html

------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gt2jqwewjti.html

合计 ........... 2106 条
来源：http://dali.shuidangran.top/Article/details/gt2jxvsfoty.html

按章节统计：
来源：http://dali.jlsjyb.cn/Article/details/gt2mwounexz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.0kj1m.cn/Article/details/gt2ewhfahgu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhixingplan.top/Article/details/gt2lnelbcku.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhixingplan.top/Article/details/gt2tplohqmm.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sitrorav.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhiwuduotai.top/Article/details/gt2abuftkjt.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.tianlin.xyz/Article/details/gt2cpzavpnr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xinyue.icu/Article/details/gt2rljswdnk.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.nanxinkj.top/Article/details/gt2gxpldanz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.quarkkingdee.top/Article/details/gt2blgrqpqo.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jqgfzy.top/Article/details/gt2ghzdhwlj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gt2qogvtisp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.haohaochexian.top/Article/details/gt2ahgztsyv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.redwolf501.top/Article/details/gt2zbgeoico.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.tian-w.cn/Article/details/gt2qnrwaitf.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ivvv.top/Article/details/gt2hgofxpsr.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.xylfe.cn/Article/details/gt2bvugtijl.html

Q SQL 专题                              90
来源：http://dali.haohaochexian.top/Article/details/gt2xcovruyt.html

R Bash 专题                             80
来源：http://dali.iojbl.cn/Article/details/gt2zlvddslb.html

S C / C++ 专题                          60
来源：http://dali.chenjidiqi.icu/Article/details/gt2puuujart.html

T 其他语言补充                          60
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2imrmpcmg.html

U 高频实用片段                         120
来源：http://dali.dianchejie.cn/Article/details/gt2skmrrxuf.html

------------------------------------
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jzaouppf.html

合计                                  2106 条
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hmsdpzkq.html

--------------------------------------------------------------------------------
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2egksqvxt.html

使用提醒
来源：http://dali.chenlongwang.top/Article/details/gt2hnzhlhtk.html

--------------------------------------------------------------------------------
来源：http://dali.yuanzhike.top/Article/details/gt2zpugpaii.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.shangyingyoupin.top/Article/details/gt2hymazyjy.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhengqikj.top/Article/details/gt2bmvdipcq.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhiwuduotai.top/Article/details/gt2ouzfttih.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jqgfzy.top/Article/details/gt2scnmxasv.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.quarkkingdee.top/Article/details/gt2xfygxtsg.html

—— 文件结束 ——
来源：http://dali.tanke756.top/Article/details/gt2vhkpzlab.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2tmutjxkd.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.0kj1m.cn/Article/details/gt2mluxsnsy.html

Common Programming Examples Cheat Book
来源：http://dali.jinqigufen.top/Article/details/gt2wkcmbhts.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2lwgnukkf.html

【收录内容】
来源：http://dali.zhoulong.xyz/Article/details/gt2ejltjkgb.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yuxming.cn/Article/details/gt2zmpmdaic.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.hammf.cn/Article/details/gt2oivqrqtd.html

SQL · Bash · C · C++
来源：http://dali.gaohongyu789.top/Article/details/gt2krabcxdb.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhixingplan.top/Article/details/gt2vqezftxv.html

【使用说明】
来源：http://dali.yongpay.top/Article/details/gt2onvjfxcq.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.cheryme.top/Article/details/gt2bdasijcy.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.fengsongda.top/Article/details/gt2htfvvdvr.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.kuanghao11.cn/Article/details/gt2ntxottob.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zycfv.cn/Article/details/gt2vbilihqo.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.ehwqpu.com/Article/details/gt2apsgtgul.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.aizwys.cn/Article/details/gt2kfdsflga.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.nwbrower.top/Article/details/gt2qrhfbgak.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.pycfn.com/Article/details/gt2yyfhzjug.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.ydzc1.top/Article/details/gt2ngclljex.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yonumen.top/Article/details/gt2hjbwpldl.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.havefunace.top/Article/details/gt2liovfjtx.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhixingplan.top/Article/details/gt2ujqcojbu.html

【文件统计】
来源：http://dali.nwbrower.top/Article/details/gt2unhhtpot.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.ivvv.top/Article/details/gt2ximmzsrs.html

--------------------------------------------------------------------------------
来源：http://dali.hongshengwenyu.top/Article/details/gt2brldbefk.html

目  录
来源：http://dali.guannengcc.top/Article/details/gt2cndmjqfa.html

--------------------------------------------------------------------------------
来源：http://dali.yuxming.cn/Article/details/gt2hvdetvme.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.c1oappe.top/Article/details/gt2zhyoaxlo.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jqgufenzy.top/Article/details/gt2tdjkngcz.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.pengpengdd.cyou/Article/details/gt2uxaqwbkt.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.hywenlv.cn/Article/details/gt2vhcrlodv.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hysaishi.cn/Article/details/gt2wqnjrios.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.9152youxi.cn/Article/details/gt2ngmlzber.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.nwbrower.top/Article/details/gt2jfkdxhrh.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.andypj.xyz/Article/details/gt2jdggajmz.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2orwmjhmf.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.gotoacloud.top/Article/details/gt2epspzidk.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.sweek.top/Article/details/gt2ljlxzygp.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.smart0.xyz/Article/details/gt2waisgxqq.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yangfankeji.com/Article/details/gt2gehxpmur.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.cdnleiting.top/Article/details/gt2jqgxsdda.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2nnqxxewe.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.aibaodan.cn/Article/details/gt2augjsdki.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yanxiufei.cn/Article/details/gt2kxtvzuts.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.gotoacloud.top/Article/details/gt2kgvivmga.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.ivvv.top/Article/details/gt2mqdtdnqb.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj202588.top/Article/details/gt2kcrmhqya.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.xziqi.cn/Article/details/gt2oihxrrfs.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2vomaktex.html

A. 基础语法与类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yunagkie.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2nuarjqee.html

[A01] Hello World
来源：http://dali.cqqwz.cn/Article/details/gt2fnpfcevg.html

Py:   print("Hello, World!")
来源：http://dali.ppjwa.cn/Article/details/gt2kwnjiuan.html

PHP:  echo "Hello, World!";
来源：http://dali.sxryk.cn/Article/details/gt2vwqlnapr.html

JS:   console.log("Hello, World!");
来源：http://dali.hongshengwenyu.top/Article/details/gt2uhovbhgw.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.cdnleiting.top/Article/details/gt2vnamaauf.html

Java: System.out.println("Hello, World!");
来源：http://dali.ydzc1.top/Article/details/gt2eaupwoys.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.shuidangran.top/Article/details/gt2hbicsnjh.html

Ruby: puts "Hello, World!"
来源：http://dali.gaohongyu789.top/Article/details/gt2csrmkuql.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.kuanghao11.cn/Article/details/gt2avuuwxth.html

[A02] 变量声明与赋值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mlmcqfzb.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.cdnleiting.top/Article/details/gt2pqujewzy.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yongpay.top/Article/details/gt2bbfhvxeq.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.mhx1999.top/Article/details/gt2pbmukuly.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.gotoacloud.top/Article/details/gt2gbbopysd.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yangfankeji.com/Article/details/gt2bnhyjfbd.html

Go:   name := "Alex"; age := 20
来源：http://dali.aibaodan.cn/Article/details/gt2xotoyhsl.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jinqigufen.top/Article/details/gt2smkwvelk.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.feifeiyinyue.top/Article/details/gt2vrdgcgjn.html

[A03] 常量定义
来源：http://dali.fzhhl.top/Article/details/gt2ptfzksxu.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.cqqwz.cn/Article/details/gt2jkdihquq.html

PHP:  const PI = 3.14159;
来源：http://dali.pycfn.com/Article/details/gt2gozopcsp.html

JS:   const PI = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gt2qfumwknd.html

TS:   const PI: number = 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gt2agfszhay.html

Java: static final double PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gt2xkwzsbsh.html

Go:   const PI = 3.14159
来源：http://dali.daria6918.cn/Article/details/gt2ekzlaunl.html

Ruby: PI = 3.14159
来源：http://dali.tian-w.cn/Article/details/gt2ylukamur.html

C#:   const double PI = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gt2xwkapkut.html

[A04] 判断变量类型
来源：http://dali.sufxvd.cn/Article/details/gt2uecdhgag.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.svipenyu.cn/Article/details/gt2cedsoxty.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.hysaishi.cn/Article/details/gt2mbpxwaom.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.hnqzz.top/Article/details/gt2bzmdttya.html

TS:   typeof x; x instanceof Date
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jmndkvxl.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.9152youxi.cn/Article/details/gt2oywvpvma.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hammf.cn/Article/details/gt2gliewccq.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.tian-w.cn/Article/details/gt2ksushrqu.html

C#:   x.GetType().Name; x is int
来源：http://dali.yuxming.cn/Article/details/gt2kpqyynzn.html

[A05] 整数除法与取模
来源：http://dali.jianghu66.top/Article/details/gt2wsuzggfn.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.nanxuanxn.top/Article/details/gt2oqzfnqdd.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gt2caafttqt.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yj202588.top/Article/details/gt2jntgmmjb.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.snrcjt.cn/Article/details/gt2agxjunwl.html

Java: 7 / 2; 7 % 2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mbnxwyzx.html

Go:   7 / 2; 7 % 2
来源：http://dali.gotoacloud.top/Article/details/gt2ivqtvuiv.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.tianlin.xyz/Article/details/gt2kwlkfufh.html

C#:   7 / 2; 7 % 2
来源：http://dali.yj202588.top/Article/details/gt2pgjcdnsm.html

[A06] 字符串转数字
来源：http://dali.jinqigfzy.top/Article/details/gt2bihwqcvh.html

Py:   int("42"); float("3.14")
来源：http://dali.0kj1m.cn/Article/details/gt2acwovmby.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.xziqi.cn/Article/details/gt2ozyldjqe.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.wangshuangyany.cn/Article/details/gt2byzszudh.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.chenjidiqi.icu/Article/details/gt2knnwadcn.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.sxryk.cn/Article/details/gt2xnvhbzrr.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2woqktknl.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.0kj1m.cn/Article/details/gt2apltcjkt.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yj20258.top/Article/details/gt2ajhzjopf.html

[A07] 数字转字符串
来源：http://dali.guannengcc.top/Article/details/gt2ddquxffs.html

Py:   str(42)
来源：http://dali.cheryme.top/Article/details/gt2bfhiivwk.html

PHP:  (string) 42; strval(42)
来源：http://dali.jyoumei.cn/Article/details/gt2xmluyaci.html

JS:   String(42); (42).toString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2htimnoxc.html

TS:   String(42)
来源：http://dali.dianchejie.cn/Article/details/gt2yerofmvj.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.316326.xyz/Article/details/gt2xsrykuwg.html

Go:   strconv.Itoa(42)
来源：http://dali.birdmap.top/Article/details/gt2zqwvlqmj.html

Ruby: 42.to_s
来源：http://dali.zhongyouzk.top/Article/details/gt2wiencjxc.html

C#:   42.ToString()
来源：http://dali.gzhubu.top/Article/details/gt2oniowazj.html

[A08] 取整与四舍五入
来源：http://dali.redwolf501.top/Article/details/gt2vyiwgpmm.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.ivvv.top/Article/details/gt2mjwxdhmb.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.sufxvd.cn/Article/details/gt2umdqeoyj.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jqgufenzy.top/Article/details/gt2ljbwcazs.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.ivvv.top/Article/details/gt2vaycujzc.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2beawzjrt.html


<!-- 参考信息 -->