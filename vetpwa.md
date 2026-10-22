代发 wailian999

[U67] PHP：处理文件上传
来源：http://dali.snrcjt.cn/Article/details/gt2svhmgnhg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.gzhubu.top/Article/details/gt2jzoerptg.html

[U68] PHP：PDO 连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fyvdhzou.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.cucudq.cn/Article/details/gt2frbezalo.html

[U69] PHP：PDO 预处理
来源：http://dali.sxryk.cn/Article/details/gt2aigejgto.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2lhirlqdb.html

[U70] PHP：PDO 事务
来源：http://dali.ehwqpu.com/Article/details/gt2jbuzxtvo.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.316326.xyz/Article/details/gt2afkbgntn.html

[U71] PHP：抛出异常
来源：http://dali.pengpengdd.cyou/Article/details/gt2cycidpzz.html

throw new RuntimeException("失败", 500);
来源：http://dali.gzhubu.top/Article/details/gt2uqzmifwb.html

[U72] PHP：写错误日志
来源：http://dali.jiagoushi.top/Article/details/gt2kpsdfdwp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hysaishi.cn/Article/details/gt2vticquen.html

[U73] PHP：读取 ini 配置
来源：http://dali.wangdashe.top/Article/details/gt2pucpiazi.html

parse_ini_file("config.ini", true)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vgxdtvkl.html

[U74] PHP：读取环境变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ynjnqfko.html

getenv("APP_ENV") ?: "production"
来源：http://dali.pengpengdd.cyou/Article/details/gt2toihzmeu.html

[U75] PHP：依赖注入
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ytuixqgd.html

composer require psr/container
来源：http://dali.daxiang520.top/Article/details/gt2sxlyeejo.html

[U76] PHP：简单路由
来源：http://dali.yvedp.cn/Article/details/gt2yxlqktnv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhiwuduotai.top/Article/details/gt2mpkmrops.html

[U77] PHP：模板渲染
来源：http://dali.bjfxy.top/Article/details/gt2hkundpzj.html

composer require twig/twig
来源：http://dali.iojbl.cn/Article/details/gt2bzdpvuwy.html

[U78] PHP：单元测试
来源：http://dali.sweek.top/Article/details/gt2wmzgpbko.html

composer require --dev phpunit/phpunit
来源：http://dali.cdnleiting.top/Article/details/gt2udkimleb.html

[U79] PHP：静态分析
来源：http://dali.yvedp.cn/Article/details/gt2ozhjawws.html

composer require --dev phpstan/phpstan
来源：http://dali.jinqigufen.top/Article/details/gt2fbwtwkvj.html

[U80] PHP：代码规范修复
来源：http://dali.hysaishi.cn/Article/details/gt2ccfbzuyb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.pengpengdd.cyou/Article/details/gt2eioqdxlg.html

[U81] JS：初始化项目
来源：http://dali.sufxvd.cn/Article/details/gt2vetyklfm.html

npm init -y;  npm i express
来源：http://dali.jinqigufen.top/Article/details/gt2rdrcskvl.html

[U82] JS：package.json 脚本
来源：http://dali.gzhubu.top/Article/details/gt2mcoimumq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hammf.cn/Article/details/gt2ahpjklyu.html

[U83] JS：ES Module 导入导出
来源：http://dali.pengpengdd.cyou/Article/details/gt2jvpkynwp.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.mhx1999.top/Article/details/gt2wrbpmeyw.html

[U84] JS：CommonJS 写法
来源：http://dali.xuetiantiany.cn/Article/details/gt2tgkotnia.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.pycfn.com/Article/details/gt2rkveccam.html

[U85] JS：可选链
来源：http://dali.hnxiangtu.top/Article/details/gt2bczezlfl.html

a?.b?.c
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dtcwzfzn.html

[U86] JS：空值合并
来源：http://dali.tian-w.cn/Article/details/gt2opldppln.html

a ?? b
来源：http://dali.yanxiufei.cn/Article/details/gt2yjbmkjkd.html

[U87] JS：解构默认值
来源：http://dali.yj20258888.top/Article/details/gt2tcivloyg.html

const { a = 1, b = 2 } = obj;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lruhkcra.html

[U88] JS：对象展开合并
来源：http://dali.tianlin.xyz/Article/details/gt2tiljzhgg.html

{ ...a, ...b }
来源：http://dali.cashguo.top/Article/details/gt2hxmrvmra.html

[U89] JS：数组去重
来源：http://dali.gogol.net.cn/Article/details/gt2fhlhiteq.html

[...new Set(arr)]
来源：http://dali.dianchejie.cn/Article/details/gt2qhhrqnfg.html

[U90] JS：数字数组排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2imklxivv.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yonumen.top/Article/details/gt2tnsfsbhs.html

[U91] JS：对象键值遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jpljeoza.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.haohaochexian.top/Article/details/gt2iudyljsm.html

[U92] JS：深拷贝
来源：http://dali.mhx1999.top/Article/details/gt2hewttctf.html

structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gt2eqtygjuj.html

[U93] JS：模板字符串
来源：http://dali.ehwqpu.com/Article/details/gt2ypquzayh.html

`共 ${n} 条`
来源：http://dali.yvedp.cn/Article/details/gt2uwdvyyxf.html

[U94] JS：箭头函数
来源：http://dali.hfpthk.cn/Article/details/gt2obvhiihm.html

const double = x => x * 2;
来源：http://dali.shuidangran.top/Article/details/gt2wcydsgjs.html

[U95] JS：Promise 包装
来源：http://dali.zhoulong.xyz/Article/details/gt2zxghlfxt.html

new Promise((resolve, reject) => {})
来源：http://dali.hongshengwenyu.top/Article/details/gt2deqanbhl.html

[U96] JS：async/await 与异常
来源：http://dali.xuanzx.com/Article/details/gt2hycfxjkz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sgupfnmv.html

[U97] JS：并发请求
来源：http://dali.xziqi.cn/Article/details/gt2rgaieryl.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gt2cptnpazt.html

[U98] JS：fetch 带 JSON
来源：http://dali.sweek.top/Article/details/gt2wormyggm.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hongshengwenyu.top/Article/details/gt2hkkcmutb.html

[U99] JS：事件监听
来源：http://dali.xylfe.cn/Article/details/gt2hymdiede.html

el.addEventListener("click", e => {})
来源：http://dali.smart0.xyz/Article/details/gt2jkqewwoz.html

[U100] JS：DOM 查询
来源：http://dali.birdmap.top/Article/details/gt2zetwabxc.html

document.querySelector(".item")
来源：http://dali.sufxvd.cn/Article/details/gt2qcqxjrbh.html

[U101] JS：classList 操作
来源：http://dali.nanxinkj.top/Article/details/gt2qeudfzbe.html

el.classList.toggle("active")
来源：http://dali.snrcjt.cn/Article/details/gt2gptztvyn.html

[U102] JS：本地存储
来源：http://dali.yvedp.cn/Article/details/gt2wsacjlmc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.cashguo.top/Article/details/gt2ytadytbw.html

[U103] JS：定时器
来源：http://dali.svipenyu.cn/Article/details/gt2ipqmhnkf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cqqwz.cn/Article/details/gt2xyzosywx.html

[U104] JS：防抖
来源：http://dali.yj202588.top/Article/details/gt2zgmkbutt.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhengqikj.top/Article/details/gt2tangnxic.html

[U105] JS：节流
来源：http://dali.sufxvd.cn/Article/details/gt2rrunmnye.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xziqi.cn/Article/details/gt2wkxsttsu.html

[U106] JS：日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gt2wnmhhzwk.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cashguo.top/Article/details/gt2dhuwqlhr.html

[U107] JS：数字千分位
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2edhuzwps.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hnqzz.top/Article/details/gt2dscbityv.html

[U108] JS：随机整数
来源：http://dali.aizwys.cn/Article/details/gt2vflfmjfe.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yuxming.cn/Article/details/gt2pcjlwtnw.html

[U109] JS：数组分组
来源：http://dali.xuanzx.com/Article/details/gt2nycyvtny.html

Object.groupBy(arr, x => x.type)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qmenbdeo.html

[U110] JS：数组分块
来源：http://dali.tianlin.xyz/Article/details/gt2evpgordd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2samscggb.html

[U111] JS：对象转 Map
来源：http://dali.c1oappe.top/Article/details/gt2ywpltzgx.html

new Map(Object.entries(obj))
来源：http://dali.zhixingplan.top/Article/details/gt2rzopbzfq.html

[U112] JS：字符串补位
来源：http://dali.ppjwa.cn/Article/details/gt2zniasbfr.html

"7".padStart(3, "0")
来源：http://dali.tanke756.top/Article/details/gt2ccqzsiob.html

[U113] JS：正则替换全部
来源：http://dali.ppjwa.cn/Article/details/gt2xshbxffg.html

s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gt2pksnjeml.html

[U114] JS：JSON 深比较
来源：http://dali.bjfxy.top/Article/details/gt2dlodaslu.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hywenlv.cn/Article/details/gt2xzyylkwd.html

[U115] JS：生成 UUID
来源：http://dali.quarkkingdee.top/Article/details/gt2orhirpnm.html

crypto.randomUUID()
来源：http://dali.smart0.xyz/Article/details/gt2yqjrixel.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yj20258888.top/Article/details/gt2hujafhdt.html

/** @param {string} name */ function f(name) {}
来源：http://dali.havefunace.top/Article/details/gt2sirtmwsi.html

[U117] JS：单元测试
来源：http://dali.xziqi.cn/Article/details/gt2ozfxtozy.html

npm i -D vitest;  npx vitest
来源：http://dali.haohaochexian.top/Article/details/gt2lxrhzspj.html

[U118] JS：开发服务器
来源：http://dali.chenjidiqi.icu/Article/details/gt2tolejbpx.html

npm i -D vite;  npx vite
来源：http://dali.wangdashe.top/Article/details/gt2bomqowya.html

[U119] JS：生产构建
来源：http://dali.cqqwz.cn/Article/details/gt2fwhzlzbz.html

npx vite build
来源：http://dali.tanke756.top/Article/details/gt2evxydhlk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.chenjidiqi.icu/Article/details/gt2roxccman.html

import.meta.env.VITE_API_URL
来源：http://dali.daria6918.cn/Article/details/gt2obvcrnft.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iyyandgo.html

统计汇总
来源：http://dali.sysykeji.top/Article/details/gt2lbnvxknt.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2mfkwdbqt.html

按语言统计（条）：
来源：http://dali.dianchejie.cn/Article/details/gt2xlzaxldj.html

Python ......... 252
来源：http://dali.snrcjt.cn/Article/details/gt2xlsfnvov.html

PHP ............ 252
来源：http://dali.sysykeji.top/Article/details/gt2zdvyexwj.html

JavaScript ..... 252
来源：http://dali.gaohongyu789.top/Article/details/gt2pcurkmcc.html

TypeScript ..... 212
来源：http://dali.mhx1999.top/Article/details/gt2eaecznse.html

Java ........... 212
来源：http://dali.aibaodan.cn/Article/details/gt2helydphz.html

Go ............. 212
来源：http://dali.9152youxi.cn/Article/details/gt2detnlkds.html

Ruby ........... 212
来源：http://dali.gogol.net.cn/Article/details/gt2uhaqwhfu.html

C# ............. 212
来源：http://dali.xylfe.cn/Article/details/gt2ypupgmop.html

C .............. 30
来源：http://dali.hongshengwenyu.top/Article/details/gt2fyzpqvem.html

C++ ............ 30
来源：http://dali.sysykeji.top/Article/details/gt2ajbawssd.html

SQL ............ 90
来源：http://dali.cdnleiting.top/Article/details/gt2uxaihqle.html

Bash ........... 80
来源：http://dali.xziqi.cn/Article/details/gt2vdusmqhp.html

Kotlin ......... 15
来源：http://dali.haohaochexian.top/Article/details/gt2pnjzqbzv.html

Swift .......... 15
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iaqovqvs.html

Lua ............ 10
来源：http://dali.sxryk.cn/Article/details/gt2njgpxmqa.html

Perl ........... 10
来源：http://dali.daria6918.cn/Article/details/gt2kcfmzesh.html

Scala .......... 10
来源：http://dali.ydzc1.top/Article/details/gt2dzxtflag.html

------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gt2iirpnujk.html

合计 ........... 2106 条
来源：http://dali.sysykeji.top/Article/details/gt2kfvanrky.html

按章节统计：
来源：http://dali.shuidangran.top/Article/details/gt2vxawyifd.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.c1oappe.top/Article/details/gt2neuduwad.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.svipenyu.cn/Article/details/gt2cartijxk.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jinghuilouyu.cn/Article/details/gt2supbjxpr.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hnqzz.top/Article/details/gt2mysghjey.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.gogol.net.cn/Article/details/gt2arrmuqnc.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.dianchejie.cn/Article/details/gt2wltjbwca.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ydzc1.top/Article/details/gt2bzwpnnhn.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jiagoushi.top/Article/details/gt2eyelbyrt.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.tianlin.xyz/Article/details/gt2qeqosxza.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yj20258.top/Article/details/gt2ruqdanju.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.daxiang520.top/Article/details/gt2vwmoxydl.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.chenlongwang.top/Article/details/gt2anlbmxnd.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.birdmap.top/Article/details/gt2xbchogsk.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.pengpengdd.cyou/Article/details/gt2pnqpyynw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.dianchejie.cn/Article/details/gt2bpegtids.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yj20258.top/Article/details/gt2qdleiwax.html

Q SQL 专题                              90
来源：http://dali.zhixingplan.top/Article/details/gt2zkumnapm.html

R Bash 专题                             80
来源：http://dali.cashguo.top/Article/details/gt2mwntdinl.html

S C / C++ 专题                          60
来源：http://dali.shuidangran.top/Article/details/gt2lhffirgh.html

T 其他语言补充                          60
来源：http://dali.wangdashe.top/Article/details/gt2mqxvqkyx.html

U 高频实用片段                         120
来源：http://dali.pycfn.com/Article/details/gt2veptifhs.html

------------------------------------
来源：http://dali.hammf.cn/Article/details/gt2fqhytbba.html

合计                                  2106 条
来源：http://dali.ydzc1.top/Article/details/gt2qvbjbagn.html

--------------------------------------------------------------------------------
来源：http://dali.hywenlv.cn/Article/details/gt2aahncygl.html

使用提醒
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hxcjencq.html

--------------------------------------------------------------------------------
来源：http://dali.gotoacloud.top/Article/details/gt2jjqsatvz.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.daxiang520.top/Article/details/gt2gqwbgjpr.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.sxryk.cn/Article/details/gt2dsrnbyjc.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.pycfn.com/Article/details/gt2pkhkvuok.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.9152youxi.cn/Article/details/gt2znvjflkr.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yuanzhike.top/Article/details/gt2jfrvxwqv.html

—— 文件结束 ——
来源：http://dali.cheryme.top/Article/details/gt2stzwsxtj.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2bhpshxbi.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhongyouzk.top/Article/details/gt2ljhmkvkr.html

Common Programming Examples Cheat Book
来源：http://dali.meibo888.top/Article/details/gt2mgmjywfe.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wpaylaaf.html

【收录内容】
来源：http://dali.gotoacloud.top/Article/details/gt2fyzxrdnk.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hnqzz.top/Article/details/gt2kgxbtvcd.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.nwbrower.top/Article/details/gt2ngcssqku.html

SQL · Bash · C · C++
来源：http://dali.zdqjudy.top/Article/details/gt2ozjkfuas.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fokqcvxy.html

【使用说明】
来源：http://dali.jinqigfzy.top/Article/details/gt2hyjkiowa.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.aizwys.cn/Article/details/gt2xypbyuir.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.dashuyun.cn/Article/details/gt2blqwelxf.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.vqdsnc.cn/Article/details/gt2knnpclcm.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.gogol.net.cn/Article/details/gt2eaqmlpnv.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hammf.cn/Article/details/gt2hcpteuqn.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.xuetiantiany.cn/Article/details/gt2mnrdamud.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.svipenyu.cn/Article/details/gt2wefdymhf.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.hammf.cn/Article/details/gt2xopdvtip.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.sufxvd.cn/Article/details/gt2xugetrxr.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.cucudq.cn/Article/details/gt2fimxehxa.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yj20258.top/Article/details/gt2kwfxwivi.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yuanzhike.top/Article/details/gt2knvwmhsd.html

【文件统计】
来源：http://dali.yanxiufei.cn/Article/details/gt2ruygynjp.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.dashuyun.cn/Article/details/gt2atlyepsi.html

--------------------------------------------------------------------------------
来源：http://dali.daxiang520.top/Article/details/gt2vefatkur.html

目  录
来源：http://dali.zhixingplan.top/Article/details/gt2bbuogbzq.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iezvvcmi.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yj20258888.top/Article/details/gt2yzvnmahk.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jqgfzy.top/Article/details/gt2lvphrmtl.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.cqqwz.cn/Article/details/gt2kxefuswt.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rvikngxg.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.aizwys.cn/Article/details/gt2ofhefdqt.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zwgwufab.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.iojbl.cn/Article/details/gt2nyonwmmu.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2glxljrah.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.cucudq.cn/Article/details/gt2yqalorco.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.pycfn.com/Article/details/gt2gabipoqp.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.svipenyu.cn/Article/details/gt2epffrdko.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.havefunace.top/Article/details/gt2sbzaeivz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jianghu66.top/Article/details/gt2angcvvsz.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.tianlin.xyz/Article/details/gt2lqwlqbzi.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.haohaochexian.top/Article/details/gt2qqyhkeyn.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.cashguo.top/Article/details/gt2wgopswks.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iecndahk.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.meibo888.top/Article/details/gt2pbjesuhl.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.xziqi.cn/Article/details/gt2cpawfmef.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.haohaochexian.top/Article/details/gt2fdelpwdd.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.cdnleiting.top/Article/details/gt2wmgdenzg.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2wzwwjfbn.html

A. 基础语法与类型
来源：http://dali.ydzc1.top/Article/details/gt2ldnodqek.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2dutrsoff.html

[A01] Hello World
来源：http://dali.yvedp.cn/Article/details/gt2ihgauory.html

Py:   print("Hello, World!")
来源：http://dali.yj202588.top/Article/details/gt2bkkiyjsk.html

PHP:  echo "Hello, World!";
来源：http://dali.xuetiantiany.cn/Article/details/gt2ocqjdnxw.html

JS:   console.log("Hello, World!");
来源：http://dali.vqdsnc.cn/Article/details/gt2ftddoemi.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.gaohongyu789.top/Article/details/gt2wjkxkcfn.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2crpswejd.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jianghu66.top/Article/details/gt2fsjdkuxr.html

Ruby: puts "Hello, World!"
来源：http://dali.hywenlv.cn/Article/details/gt2csvvoirp.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.andypj.xyz/Article/details/gt2bjlsgrjw.html

[A02] 变量声明与赋值
来源：http://dali.yongpay.top/Article/details/gt2yffswnaf.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.fzhhl.top/Article/details/gt2usivkimf.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.gzhubu.top/Article/details/gt2thpwevjc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yuxming.cn/Article/details/gt2wnrsgrmt.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jianghu66.top/Article/details/gt2udplhxpr.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.cqqwz.cn/Article/details/gt2zohesmtr.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2balbbunf.html

Ruby: name = "Alex"; age = 20
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2beypeydn.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.guowangkeji.top/Article/details/gt2rgpvqaqd.html

[A03] 常量定义
来源：http://dali.feifeiyinyue.top/Article/details/gt2shqyjpwg.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hywenlv.cn/Article/details/gt2rhuktnvy.html

PHP:  const PI = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gt2suvtwjii.html

JS:   const PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gt2exjcmnmt.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2psjcgsvc.html

Java: static final double PI = 3.14159;
来源：http://dali.tanke756.top/Article/details/gt2eynsqsvl.html

Go:   const PI = 3.14159
来源：http://dali.zhengqikj.top/Article/details/gt2cfuqvfgo.html

Ruby: PI = 3.14159
来源：http://dali.chenlongwang.top/Article/details/gt2zcbcazrb.html

C#:   const double PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gt2vqxwtzhf.html

[A04] 判断变量类型
来源：http://dali.hywenlv.cn/Article/details/gt2zqmyhbsw.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.tanke756.top/Article/details/gt2lmuyvfzt.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dwhvwwrd.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.ybcxt.top/Article/details/gt2mkibtmzb.html

TS:   typeof x; x instanceof Date
来源：http://dali.hnxiangtu.top/Article/details/gt2kfrduiyx.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.wangshuangyany.cn/Article/details/gt2igajeuti.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.dashuyun.cn/Article/details/gt2qiwpuddi.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.sysykeji.top/Article/details/gt2pspitcyw.html

C#:   x.GetType().Name; x is int
来源：http://dali.jinqigufen.top/Article/details/gt2cgwxqvdv.html

[A05] 整数除法与取模
来源：http://dali.cdnleiting.top/Article/details/gt2qwhvmxgn.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.cqqwz.cn/Article/details/gt2pbjeosji.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.cheryme.top/Article/details/gt2ihakxsri.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jyoumei.cn/Article/details/gt2ceoydhyf.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.nwbrower.top/Article/details/gt2jvigffya.html

Java: 7 / 2; 7 % 2
来源：http://dali.ivvv.top/Article/details/gt2xzreooky.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2maplyjnc.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.hammf.cn/Article/details/gt2jbuysmon.html

C#:   7 / 2; 7 % 2
来源：http://dali.nanxinkj.top/Article/details/gt2lxbtuiyi.html

[A06] 字符串转数字
来源：http://dali.fzhhl.top/Article/details/gt2xokzuyao.html

Py:   int("42"); float("3.14")
来源：http://dali.yj202588.top/Article/details/gt2fweizopq.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.redwolf501.top/Article/details/gt2qbbylayf.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yonumen.top/Article/details/gt2ptbymjza.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hnxiangtu.top/Article/details/gt2mkdarxyu.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhixingplan.top/Article/details/gt2mfsmfpla.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.nanxuanxn.top/Article/details/gt2sabmkbuv.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yangfankeji.com/Article/details/gt2xjnlhwbr.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cqzkhnyh.html

[A07] 数字转字符串
来源：http://dali.yangfankeji.com/Article/details/gt2xplbptpo.html

Py:   str(42)
来源：http://dali.pycfn.com/Article/details/gt2dorepzwg.html

PHP:  (string) 42; strval(42)
来源：http://dali.snrcjt.cn/Article/details/gt2pkqnishe.html

JS:   String(42); (42).toString()
来源：http://dali.zhengqikj.top/Article/details/gt2gbraotsp.html

TS:   String(42)
来源：http://dali.iojbl.cn/Article/details/gt2lsdrpxkc.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhongyouzk.top/Article/details/gt2vudkpple.html

Go:   strconv.Itoa(42)
来源：http://dali.ivvv.top/Article/details/gt2rqrxppms.html

Ruby: 42.to_s
来源：http://dali.ydzc1.top/Article/details/gt2ummdjnwk.html

C#:   42.ToString()
来源：http://dali.cdnleiting.top/Article/details/gt2rkayatkg.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2thmoyklm.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.316326.xyz/Article/details/gt2fmqgtoiz.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.guannengcc.top/Article/details/gt2xxdmkjmx.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.hywenlv.cn/Article/details/gt2jcgkavob.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yonumen.top/Article/details/gt2orikpyzn.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.aizwys.cn/Article/details/gt2vnsexrys.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.sweek.top/Article/details/gt2iavmlgfj.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.quarkkingdee.top/Article/details/gt2hqstsdon.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.birdmap.top/Article/details/gt2swgbuyps.html

[A09] 绝对值与最大最小值
来源：http://dali.cashguo.top/Article/details/gt2hucvqbue.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhixingplan.top/Article/details/gt2fclhvgen.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.nanxinkj.top/Article/details/gt2dlteuzvl.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.yueranfly.top/Article/details/gt2rpenuxca.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.ydzc1.top/Article/details/gt2ckvekcgr.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.redwolf501.top/Article/details/gt2dujlgjcu.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.sufxvd.cn/Article/details/gt2eoubuwhj.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yuxming.cn/Article/details/gt2bczupmcm.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2pqxfeluq.html

[A10] 生成随机数
来源：http://dali.zdqjudy.top/Article/details/gt2jxfrpfmw.html

Py:   import random; random.randint(1, 100)
来源：http://dali.daxiang520.top/Article/details/gt2ftpxnsrx.html

PHP:  random_int(1, 100);
来源：http://dali.svipenyu.cn/Article/details/gt2honyshof.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2njpvlbpc.html


<!-- 参考信息 -->