代发 wailian999

[U65] PHP：会话
来源：http://dali.andypj.xyz/Article/details/gt2fheamlxc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gt2bzixloqs.html

[U66] PHP：设置 Cookie
来源：http://dali.zycfv.cn/Article/details/gt2mzfrldko.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yongpay.top/Article/details/gt2snkacbxw.html

[U67] PHP：处理文件上传
来源：http://dali.jqgufenzy.top/Article/details/gt2bvydvybr.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.tianlin.xyz/Article/details/gt2vwodkxus.html

[U68] PHP：PDO 连接
来源：http://dali.pycfn.com/Article/details/gt2nrelygzy.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yonumen.top/Article/details/gt2itqllhsv.html

[U69] PHP：PDO 预处理
来源：http://dali.zhoulong.xyz/Article/details/gt2hdaxroxy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.meibo888.top/Article/details/gt2nbrwlltt.html

[U70] PHP：PDO 事务
来源：http://dali.jinqigfzy.top/Article/details/gt2dioohlzo.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cjcosusd.html

[U71] PHP：抛出异常
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yqzvorhw.html

throw new RuntimeException("失败", 500);
来源：http://dali.tanke756.top/Article/details/gt2xgllygrp.html

[U72] PHP：写错误日志
来源：http://dali.daria6918.cn/Article/details/gt2qqonvumn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xuetiantiany.cn/Article/details/gt2qdaxgbvx.html

[U73] PHP：读取 ini 配置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2inwmsfeo.html

parse_ini_file("config.ini", true)
来源：http://dali.tian-w.cn/Article/details/gt2smqfrwgi.html

[U74] PHP：读取环境变量
来源：http://dali.nanxuanxn.top/Article/details/gt2fsepdopp.html

getenv("APP_ENV") ?: "production"
来源：http://dali.dashuyun.cn/Article/details/gt2nhhqmenn.html

[U75] PHP：依赖注入
来源：http://dali.wangdashe.top/Article/details/gt2vmfqpjtx.html

composer require psr/container
来源：http://dali.wangshuangyany.cn/Article/details/gt2zwonmcgp.html

[U76] PHP：简单路由
来源：http://dali.sxryk.cn/Article/details/gt2fiktfxcb.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.9152youxi.cn/Article/details/gt2mstlchtr.html

[U77] PHP：模板渲染
来源：http://dali.dianchejie.cn/Article/details/gt2wdddnsju.html

composer require twig/twig
来源：http://dali.zdqjudy.top/Article/details/gt2svfhdzrq.html

[U78] PHP：单元测试
来源：http://dali.zhengqikj.top/Article/details/gt2mcslklcb.html

composer require --dev phpunit/phpunit
来源：http://dali.aibaodan.cn/Article/details/gt2nbdvwiov.html

[U79] PHP：静态分析
来源：http://dali.cucudq.cn/Article/details/gt2wlfvfqor.html

composer require --dev phpstan/phpstan
来源：http://dali.hywenlv.cn/Article/details/gt2gxmbakff.html

[U80] PHP：代码规范修复
来源：http://dali.kuanghao11.cn/Article/details/gt2mqnfdfgh.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.guowangkeji.top/Article/details/gt2jglgctmg.html

[U81] JS：初始化项目
来源：http://dali.dashuyun.cn/Article/details/gt2gfhixvvp.html

npm init -y;  npm i express
来源：http://dali.ivvv.top/Article/details/gt2ogrxczzw.html

[U82] JS：package.json 脚本
来源：http://dali.zhengqikj.top/Article/details/gt2xrjwomwc.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.daria6918.cn/Article/details/gt2aasmsxrp.html

[U83] JS：ES Module 导入导出
来源：http://dali.tianlin.xyz/Article/details/gt2fmxktduq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.meibo888.top/Article/details/gt2dwhlpmqb.html

[U84] JS：CommonJS 写法
来源：http://dali.cashguo.top/Article/details/gt2fsuxxupx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.316326.xyz/Article/details/gt2ygnlyxkp.html

[U85] JS：可选链
来源：http://dali.gotoacloud.top/Article/details/gt2hkebtjvp.html

a?.b?.c
来源：http://dali.zhongyouzk.top/Article/details/gt2xlxutrbr.html

[U86] JS：空值合并
来源：http://dali.daxiang520.top/Article/details/gt2iwsreokc.html

a ?? b
来源：http://dali.ydzc1.top/Article/details/gt2jtkkczse.html

[U87] JS：解构默认值
来源：http://dali.birdmap.top/Article/details/gt2aoxkxslx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.ppjwa.cn/Article/details/gt2cgxsoyoh.html

[U88] JS：对象展开合并
来源：http://dali.yj20258.top/Article/details/gt2ypkfgtsr.html

{ ...a, ...b }
来源：http://dali.yj20258.top/Article/details/gt2jgftrkgw.html

[U89] JS：数组去重
来源：http://dali.snrcjt.cn/Article/details/gt2yxlhxahy.html

[...new Set(arr)]
来源：http://dali.wangshuangyany.cn/Article/details/gt2wgkubhwi.html

[U90] JS：数字数组排序
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tddiqfnf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nfncqnwl.html

[U91] JS：对象键值遍历
来源：http://dali.cdnleiting.top/Article/details/gt2hiejbafv.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.gzhubu.top/Article/details/gt2pjgchiqc.html

[U92] JS：深拷贝
来源：http://dali.zhoulong.xyz/Article/details/gt2ppvaubmc.html

structuredClone(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wqgxeocm.html

[U93] JS：模板字符串
来源：http://dali.daria6918.cn/Article/details/gt2aoypiqcc.html

`共 ${n} 条`
来源：http://dali.zhiwuduotai.top/Article/details/gt2mofkxseq.html

[U94] JS：箭头函数
来源：http://dali.quarkkingdee.top/Article/details/gt2ndpqoqkc.html

const double = x => x * 2;
来源：http://dali.pycfn.com/Article/details/gt2hzzwoiew.html

[U95] JS：Promise 包装
来源：http://dali.nanxuanxn.top/Article/details/gt2tnkwwrns.html

new Promise((resolve, reject) => {})
来源：http://dali.bjfxy.top/Article/details/gt2xzwgetiq.html

[U96] JS：async/await 与异常
来源：http://dali.quarkkingdee.top/Article/details/gt2rxzqhygb.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhongyouzk.top/Article/details/gt2uxwvhofa.html

[U97] JS：并发请求
来源：http://dali.hywenlv.cn/Article/details/gt2peddtuao.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daria6918.cn/Article/details/gt2auoijemn.html

[U98] JS：fetch 带 JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pfbrfnir.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hnqzz.top/Article/details/gt2hnnnjoly.html

[U99] JS：事件监听
来源：http://dali.hongshengwenyu.top/Article/details/gt2kvylphlr.html

el.addEventListener("click", e => {})
来源：http://dali.dianchejie.cn/Article/details/gt2bvmxiiwb.html

[U100] JS：DOM 查询
来源：http://dali.hfpthk.cn/Article/details/gt2jmcxdptt.html

document.querySelector(".item")
来源：http://dali.hnqzz.top/Article/details/gt2tmqhrabg.html

[U101] JS：classList 操作
来源：http://dali.tanke756.top/Article/details/gt2hhfixclb.html

el.classList.toggle("active")
来源：http://dali.zdqjudy.top/Article/details/gt2rdjflicf.html

[U102] JS：本地存储
来源：http://dali.xylfe.cn/Article/details/gt2egjlgrmf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yj20258888.top/Article/details/gt2evwuoysc.html

[U103] JS：定时器
来源：http://dali.jyoumei.cn/Article/details/gt2prorbeop.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2izusuweg.html

[U104] JS：防抖
来源：http://dali.316326.xyz/Article/details/gt2vogqazil.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sysykeji.top/Article/details/gt2gebdxzet.html

[U105] JS：节流
来源：http://dali.haohaochexian.top/Article/details/gt2cpgrayyg.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hnxiangtu.top/Article/details/gt2nedwnesr.html

[U106] JS：日期格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yliwfxpj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.sxryk.cn/Article/details/gt2bwlnfrhk.html

[U107] JS：数字千分位
来源：http://dali.vqdsnc.cn/Article/details/gt2uwgwiaue.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cheryme.top/Article/details/gt2wbiegtic.html

[U108] JS：随机整数
来源：http://dali.iojbl.cn/Article/details/gt2sdzjddfn.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ulbhwcfe.html

[U109] JS：数组分组
来源：http://dali.haohaochexian.top/Article/details/gt2hfvwyeiz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hnqzz.top/Article/details/gt2azutcbew.html

[U110] JS：数组分块
来源：http://dali.chenlongwang.top/Article/details/gt2uaralaie.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.mhx1999.top/Article/details/gt2fudsfizz.html

[U111] JS：对象转 Map
来源：http://dali.sufxvd.cn/Article/details/gt2oojspcow.html

new Map(Object.entries(obj))
来源：http://dali.chenzaomai.com/Article/details/gt2bylybmom.html

[U112] JS：字符串补位
来源：http://dali.ivvv.top/Article/details/gt2ufskjqfy.html

"7".padStart(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gt2akvblngu.html

[U113] JS：正则替换全部
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rouyyofb.html

s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2usoqnriz.html

[U114] JS：JSON 深比较
来源：http://dali.cucudq.cn/Article/details/gt2pquhdsjv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.meibo888.top/Article/details/gt2pazbyeys.html

[U115] JS：生成 UUID
来源：http://dali.yj20258888.top/Article/details/gt2tbpftxsc.html

crypto.randomUUID()
来源：http://dali.yj20258888.top/Article/details/gt2dwzyxtpp.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.vqdsnc.cn/Article/details/gt2rlasyqer.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yj20258.top/Article/details/gt2flkbwjeo.html

[U117] JS：单元测试
来源：http://dali.gaohongyu789.top/Article/details/gt2normlcmf.html

npm i -D vitest;  npx vitest
来源：http://dali.hywenlv.cn/Article/details/gt2jyyhlsif.html

[U118] JS：开发服务器
来源：http://dali.jiagoushi.top/Article/details/gt2oqirzewd.html

npm i -D vite;  npx vite
来源：http://dali.chenlongwang.top/Article/details/gt2syjawnft.html

[U119] JS：生产构建
来源：http://dali.tian-w.cn/Article/details/gt2opefvncn.html

npx vite build
来源：http://dali.jiagoushi.top/Article/details/gt2opuiwgjr.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bboaxbxr.html

import.meta.env.VITE_API_URL
来源：http://dali.iojbl.cn/Article/details/gt2vqfdephd.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2jlesxkhv.html

统计汇总
来源：http://dali.cashguo.top/Article/details/gt2gqpyhudx.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2cohxkqrm.html

按语言统计（条）：
来源：http://dali.birdmap.top/Article/details/gt2dizwemcw.html

Python ......... 252
来源：http://dali.tian-w.cn/Article/details/gt2abmnzygk.html

PHP ............ 252
来源：http://dali.vqdsnc.cn/Article/details/gt2ytwkumre.html

JavaScript ..... 252
来源：http://dali.yanxiufei.cn/Article/details/gt2iyeeraoc.html

TypeScript ..... 212
来源：http://dali.yangfankeji.com/Article/details/gt2pfesltdx.html

Java ........... 212
来源：http://dali.ydzc1.top/Article/details/gt2ssdkeudg.html

Go ............. 212
来源：http://dali.xinyue.icu/Article/details/gt2rnpeponq.html

Ruby ........... 212
来源：http://dali.ehwqpu.com/Article/details/gt2ndfbzmyu.html

C# ............. 212
来源：http://dali.snrcjt.cn/Article/details/gt2hclfdshf.html

C .............. 30
来源：http://dali.quarkkingdee.top/Article/details/gt2hhevrrar.html

C++ ............ 30
来源：http://dali.cqqwz.cn/Article/details/gt2nejhvoop.html

SQL ............ 90
来源：http://dali.gogol.net.cn/Article/details/gt2nodxpnka.html

Bash ........... 80
来源：http://dali.quarkkingdee.top/Article/details/gt2lkrhrpkm.html

Kotlin ......... 15
来源：http://dali.dianchejie.cn/Article/details/gt2yzjzmrky.html

Swift .......... 15
来源：http://dali.cheryme.top/Article/details/gt2cssnkits.html

Lua ............ 10
来源：http://dali.chenlongwang.top/Article/details/gt2gnlrcnjk.html

Perl ........... 10
来源：http://dali.shuidangran.top/Article/details/gt2lrtmieaa.html

Scala .......... 10
来源：http://dali.cdnleiting.top/Article/details/gt2rqymkotg.html

------------------------------------
来源：http://dali.sweek.top/Article/details/gt2qxcjbote.html

合计 ........... 2106 条
来源：http://dali.haohaochexian.top/Article/details/gt2ipihbybd.html

按章节统计：
来源：http://dali.fengsongda.top/Article/details/gt2fkvurlnv.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.tian-w.cn/Article/details/gt2tatxbhgz.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhixingplan.top/Article/details/gt2arykewmg.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yonumen.top/Article/details/gt2coervjfo.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.quarkkingdee.top/Article/details/gt2mypjylhu.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.316326.xyz/Article/details/gt2ufokgnko.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2guisqrgp.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xuetiantiany.cn/Article/details/gt2bcqfwalt.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vdtkhgyv.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.shuidangran.top/Article/details/gt2vnwpmsax.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.pycfn.com/Article/details/gt2pwmoxwcs.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yueranfly.top/Article/details/gt2omkzrvfz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.c1oappe.top/Article/details/gt2dvzqvlob.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ehwqpu.com/Article/details/gt2zmvmbwgy.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.gzhubu.top/Article/details/gt2dnzeqive.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hammf.cn/Article/details/gt2soaaqlgm.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.gaohongyu789.top/Article/details/gt2qxgrozgu.html

Q SQL 专题                              90
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ncitokay.html

R Bash 专题                             80
来源：http://dali.hnqzz.top/Article/details/gt2xfqajiom.html

S C / C++ 专题                          60
来源：http://dali.sweek.top/Article/details/gt2itbknjju.html

T 其他语言补充                          60
来源：http://dali.hywenlv.cn/Article/details/gt2qebfjbxh.html

U 高频实用片段                         120
来源：http://dali.9152youxi.cn/Article/details/gt2lkgwwccf.html

------------------------------------
来源：http://dali.yuanzhike.top/Article/details/gt2aifnteee.html

合计                                  2106 条
来源：http://dali.ehwqpu.com/Article/details/gt2qroepmdc.html

--------------------------------------------------------------------------------
来源：http://dali.gzhubu.top/Article/details/gt2lnapxbqz.html

使用提醒
来源：http://dali.yueranfly.top/Article/details/gt2bprpfxrp.html

--------------------------------------------------------------------------------
来源：http://dali.gaohongyu789.top/Article/details/gt2mrafmfgl.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.gotoacloud.top/Article/details/gt2whuyigik.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhixingplan.top/Article/details/gt2pbqyggko.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.xziqi.cn/Article/details/gt2nlrdklkz.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.smart0.xyz/Article/details/gt2ddgtxytr.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.cdnleiting.top/Article/details/gt2avmkgwjb.html

—— 文件结束 ——
来源：http://dali.fengsongda.top/Article/details/gt2qxkivaze.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2fyesasss.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.shuidangran.top/Article/details/gt2nfabxvpf.html

Common Programming Examples Cheat Book
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jbzzwyge.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2xoptdjpy.html

【收录内容】
来源：http://dali.gzhubu.top/Article/details/gt2jlyzkgec.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.redwolf501.top/Article/details/gt2qplbsokf.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.tanke756.top/Article/details/gt2eguhdwvi.html

SQL · Bash · C · C++
来源：http://dali.chenzaomai.com/Article/details/gt2xcgkytpg.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.xinyue.icu/Article/details/gt2tiespmls.html

【使用说明】
来源：http://dali.wangdashe.top/Article/details/gt2jrlylfgo.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhiwuduotai.top/Article/details/gt2fgaewkza.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.birdmap.top/Article/details/gt2gbgqzivg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yj202588.top/Article/details/gt2utxnhnkf.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rwughsmm.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jyoumei.cn/Article/details/gt2lndihjly.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.tian-w.cn/Article/details/gt2kzsxcjdi.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2durnaqmn.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.9152youxi.cn/Article/details/gt2sspsmhor.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.316326.xyz/Article/details/gt2wbassxid.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.sufxvd.cn/Article/details/gt2rqbfhubn.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.chenlongwang.top/Article/details/gt2teggnqtv.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.birdmap.top/Article/details/gt2sypdmafc.html

【文件统计】
来源：http://dali.yangfankeji.com/Article/details/gt2ujofhmid.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.fengsongda.top/Article/details/gt2dntyjmzu.html

--------------------------------------------------------------------------------
来源：http://dali.yvedp.cn/Article/details/gt2khwbcube.html

目  录
来源：http://dali.zhixingplan.top/Article/details/gt2tetmlpmm.html

--------------------------------------------------------------------------------
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cvmlbalq.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgmefdz.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.cucudq.cn/Article/details/gt2zrdowhvr.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.xuanzx.com/Article/details/gt2otuyzseg.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.hysaishi.cn/Article/details/gt2omglonal.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.daria6918.cn/Article/details/gt2vauzhwdv.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2bvbzjexe.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hongshengwenyu.top/Article/details/gt2pkyavfnk.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.meibo888.top/Article/details/gt2rwgznptm.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.xuanzx.com/Article/details/gt2dmkerpwf.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.wangdashe.top/Article/details/gt2vocgywxy.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2uxfyyzkf.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.daxiang520.top/Article/details/gt2odibezpo.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.hnxiangtu.top/Article/details/gt2ltzrhbax.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.birdmap.top/Article/details/gt2pnipbenb.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.hnqzz.top/Article/details/gt2mfvdabxq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2csopskhp.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yj20258.top/Article/details/gt2rkojlvml.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2cybktuei.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.tian-w.cn/Article/details/gt2qebujpkq.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.fengsongda.top/Article/details/gt2ycncqwup.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.ppjwa.cn/Article/details/gt2nmlmyvpk.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2enebritt.html

A. 基础语法与类型
来源：http://dali.ydzc1.top/Article/details/gt2rkjcjibu.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2uislmllz.html

[A01] Hello World
来源：http://dali.kuanghao11.cn/Article/details/gt2gpilljte.html

Py:   print("Hello, World!")
来源：http://dali.yj20258.top/Article/details/gt2qklgkxpn.html

PHP:  echo "Hello, World!";
来源：http://dali.hywenlv.cn/Article/details/gt2wazwrirf.html

JS:   console.log("Hello, World!");
来源：http://dali.cdnleiting.top/Article/details/gt2lheydivr.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.wangdashe.top/Article/details/gt2tzxzuwde.html

Java: System.out.println("Hello, World!");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qtydgtze.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.haohaochexian.top/Article/details/gt2fpsekjng.html

Ruby: puts "Hello, World!"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vuiemmad.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.ivvv.top/Article/details/gt2hfoiafrx.html

[A02] 变量声明与赋值
来源：http://dali.xuanzx.com/Article/details/gt2aqjgqevz.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.gotoacloud.top/Article/details/gt2hlfdkyoa.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yj20258888.top/Article/details/gt2mzrwqobc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.chenlongwang.top/Article/details/gt2morfnytd.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.havefunace.top/Article/details/gt2twmhusxx.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.havefunace.top/Article/details/gt2npaprqxd.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhengqikj.top/Article/details/gt2zspbhvmo.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jianghu66.top/Article/details/gt2fsdknmtl.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ipdnrpfu.html

[A03] 常量定义
来源：http://dali.xziqi.cn/Article/details/gt2thbtgxiy.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gloqzpsi.html

PHP:  const PI = 3.14159;
来源：http://dali.yongpay.top/Article/details/gt2irjhxypv.html

JS:   const PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gt2mjdqsvmg.html

TS:   const PI: number = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ugymqvlh.html

Java: static final double PI = 3.14159;
来源：http://dali.mhx1999.top/Article/details/gt2wherddzs.html

Go:   const PI = 3.14159
来源：http://dali.havefunace.top/Article/details/gt2pfoubibk.html

Ruby: PI = 3.14159
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ovcdruop.html

C#:   const double PI = 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gt2ecxdccgw.html

[A04] 判断变量类型
来源：http://dali.daxiang520.top/Article/details/gt2rdwkkvtc.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.316326.xyz/Article/details/gt2nimyxcft.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.meibo888.top/Article/details/gt2fxozofga.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yuxming.cn/Article/details/gt2xuqftoho.html

TS:   typeof x; x instanceof Date
来源：http://dali.gotoacloud.top/Article/details/gt2mitvmqeb.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.kuanghao11.cn/Article/details/gt2bxyasozb.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.xylfe.cn/Article/details/gt2zkmbxwds.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.sweek.top/Article/details/gt2vlnibbxc.html

C#:   x.GetType().Name; x is int
来源：http://dali.bjfxy.top/Article/details/gt2gmtdtika.html

[A05] 整数除法与取模
来源：http://dali.hywenlv.cn/Article/details/gt2qgtsxhet.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jiagoushi.top/Article/details/gt2imgxzkfl.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.ivvv.top/Article/details/gt2czeboloa.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jiagoushi.top/Article/details/gt2yeosludi.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hywenlv.cn/Article/details/gt2ugdajoea.html

Java: 7 / 2; 7 % 2
来源：http://dali.iojbl.cn/Article/details/gt2hxepnbaj.html

Go:   7 / 2; 7 % 2
来源：http://dali.xziqi.cn/Article/details/gt2mkgmimxv.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.ppjwa.cn/Article/details/gt2odeieqxu.html

C#:   7 / 2; 7 % 2
来源：http://dali.ehwqpu.com/Article/details/gt2qtfstqtt.html

[A06] 字符串转数字
来源：http://dali.birdmap.top/Article/details/gt2qqvwrtwm.html

Py:   int("42"); float("3.14")
来源：http://dali.jinqigfzy.top/Article/details/gt2mexrqebf.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhixingplan.top/Article/details/gt2zsujppso.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.guannengcc.top/Article/details/gt2odlaaplt.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.xuetiantiany.cn/Article/details/gt2rwfshqqs.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uqehfvbz.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ptkmmlkq.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ccoicqrc.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.hammf.cn/Article/details/gt2fblvalmz.html

[A07] 数字转字符串
来源：http://dali.nwbrower.top/Article/details/gt2zawwjmax.html

Py:   str(42)
来源：http://dali.fzhhl.top/Article/details/gt2daeriepv.html

PHP:  (string) 42; strval(42)
来源：http://dali.hysaishi.cn/Article/details/gt2cebwmail.html

JS:   String(42); (42).toString()
来源：http://dali.hnqzz.top/Article/details/gt2pnfbcfky.html

TS:   String(42)
来源：http://dali.shzxlz.cn/Article/details/gt2vajckjla.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jyoumei.cn/Article/details/gt2ebpvifgw.html

Go:   strconv.Itoa(42)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2miajanmu.html

Ruby: 42.to_s
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ufukeaxb.html

C#:   42.ToString()
来源：http://dali.haohaochexian.top/Article/details/gt2chhmkpht.html

[A08] 取整与四舍五入
来源：http://dali.yangfankeji.com/Article/details/gt2hrwrqicw.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.cheryme.top/Article/details/gt2angmvtjy.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.xziqi.cn/Article/details/gt2ebuqihxo.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.hysaishi.cn/Article/details/gt2qpxghzxn.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.guowangkeji.top/Article/details/gt2eoqpsgdp.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.iojbl.cn/Article/details/gt2nwjmolam.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yj20258888.top/Article/details/gt2fokrhymy.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.redwolf501.top/Article/details/gt2lytliiyb.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kqqfpyla.html

[A09] 绝对值与最大最小值
来源：http://dali.daria6918.cn/Article/details/gt2bsmepuoz.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yvedp.cn/Article/details/gt2sojlvoir.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ivvv.top/Article/details/gt2wfghkwid.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.yj20258888.top/Article/details/gt2gvlfiwoy.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.jyoumei.cn/Article/details/gt2erspzhiw.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcmizln.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jinqigfzy.top/Article/details/gt2bmhcvxpd.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.shzxlz.cn/Article/details/gt2uchobnpx.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yvedp.cn/Article/details/gt2ultdkkpx.html


<!-- 参考信息 -->