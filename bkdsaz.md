代发 wailian999

[U61] PHP：正则
来源：http://dali.gotoacloud.top/Article/details/gt2futjfrlw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yuanzhike.top/Article/details/gt2kdusfqgw.html

[U62] PHP：日期对象
来源：http://dali.aibaodan.cn/Article/details/gt2hkmrmxty.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.svipenyu.cn/Article/details/gt2zerzgtob.html

[U63] PHP：文件读写
来源：http://dali.andypj.xyz/Article/details/gt2gnzvcylh.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.daxiang520.top/Article/details/gt2bsuoewwi.html

[U64] PHP：目录遍历
来源：http://dali.feifeiyinyue.top/Article/details/gt2ausprdon.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.xuanzx.com/Article/details/gt2dmxewvgv.html

[U65] PHP：会话
来源：http://dali.aizwys.cn/Article/details/gt2crimwrbx.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.guannengcc.top/Article/details/gt2jjnjpmdt.html

[U66] PHP：设置 Cookie
来源：http://dali.nanxinkj.top/Article/details/gt2gycshsuq.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.xinyue.icu/Article/details/gt2fcqxkqvb.html

[U67] PHP：处理文件上传
来源：http://dali.cqqwz.cn/Article/details/gt2bbmykely.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.aizwys.cn/Article/details/gt2ecsjytfg.html

[U68] PHP：PDO 连接
来源：http://dali.hammf.cn/Article/details/gt2ymswwavr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.gotoacloud.top/Article/details/gt2huygskkr.html

[U69] PHP：PDO 预处理
来源：http://dali.zhixingplan.top/Article/details/gt2lzslojxx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.dashuyun.cn/Article/details/gt2cchcnxxr.html

[U70] PHP：PDO 事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yoxkzgug.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ppjwa.cn/Article/details/gt2tpjagtit.html

[U71] PHP：抛出异常
来源：http://dali.daxiang520.top/Article/details/gt2cpnptzaq.html

throw new RuntimeException("失败", 500);
来源：http://dali.gzhubu.top/Article/details/gt2pazbzwnb.html

[U72] PHP：写错误日志
来源：http://dali.cqqwz.cn/Article/details/gt2eqokcuai.html

error_log("失败: " . $e->getMessage());
来源：http://dali.gaohongyu789.top/Article/details/gt2habtfces.html

[U73] PHP：读取 ini 配置
来源：http://dali.nanxinkj.top/Article/details/gt2lebkabjo.html

parse_ini_file("config.ini", true)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jynwbseo.html

[U74] PHP：读取环境变量
来源：http://dali.tianlin.xyz/Article/details/gt2akybpjfe.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yyljbfgi.html

[U75] PHP：依赖注入
来源：http://dali.aibaodan.cn/Article/details/gt2xnapmjxs.html

composer require psr/container
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oyyhxuap.html

[U76] PHP：简单路由
来源：http://dali.sweek.top/Article/details/gt2tufrbaad.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.havefunace.top/Article/details/gt2weqrwldw.html

[U77] PHP：模板渲染
来源：http://dali.guannengcc.top/Article/details/gt2mhhrswdt.html

composer require twig/twig
来源：http://dali.dianchejie.cn/Article/details/gt2vjzekqay.html

[U78] PHP：单元测试
来源：http://dali.zdqjudy.top/Article/details/gt2qzxwjxzm.html

composer require --dev phpunit/phpunit
来源：http://dali.shangyingyoupin.top/Article/details/gt2jkjkxbdk.html

[U79] PHP：静态分析
来源：http://dali.fengsongda.top/Article/details/gt2uojnwllb.html

composer require --dev phpstan/phpstan
来源：http://dali.yonumen.top/Article/details/gt2mdeujzid.html

[U80] PHP：代码规范修复
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2acyadrvd.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2djdvrvbo.html

[U81] JS：初始化项目
来源：http://dali.jinqigufen.top/Article/details/gt2knmqwpej.html

npm init -y;  npm i express
来源：http://dali.smart0.xyz/Article/details/gt2daazqekz.html

[U82] JS：package.json 脚本
来源：http://dali.hysaishi.cn/Article/details/gt2aivectqr.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.fzhhl.top/Article/details/gt2jgcorezd.html

[U83] JS：ES Module 导入导出
来源：http://dali.vqdsnc.cn/Article/details/gt2wyvasoqr.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.0kj1m.cn/Article/details/gt2dyrlqzke.html

[U84] JS：CommonJS 写法
来源：http://dali.kuanghao11.cn/Article/details/gt2yhfzddou.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.fzhhl.top/Article/details/gt2vfvzlums.html

[U85] JS：可选链
来源：http://dali.havefunace.top/Article/details/gt2qsqeeakv.html

a?.b?.c
来源：http://dali.jqgufenzy.top/Article/details/gt2juxmqhmx.html

[U86] JS：空值合并
来源：http://dali.gotoacloud.top/Article/details/gt2nauuuvrq.html

a ?? b
来源：http://dali.feifeiyinyue.top/Article/details/gt2dyruofyb.html

[U87] JS：解构默认值
来源：http://dali.hfpthk.cn/Article/details/gt2lamkfgja.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jinqigfzy.top/Article/details/gt2kmsrspfw.html

[U88] JS：对象展开合并
来源：http://dali.xinyue.icu/Article/details/gt2cxjjfhtj.html

{ ...a, ...b }
来源：http://dali.daria6918.cn/Article/details/gt2nnsvjwvv.html

[U89] JS：数组去重
来源：http://dali.0kj1m.cn/Article/details/gt2rzbqiyde.html

[...new Set(arr)]
来源：http://dali.316326.xyz/Article/details/gt2cdzskmaf.html

[U90] JS：数字数组排序
来源：http://dali.nanxuanxn.top/Article/details/gt2ssjphloo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2aucyvkfl.html

[U91] JS：对象键值遍历
来源：http://dali.hfpthk.cn/Article/details/gt2rdkimtxw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.fzhhl.top/Article/details/gt2alpzelgn.html

[U92] JS：深拷贝
来源：http://dali.ybcxt.top/Article/details/gt2luzvuymj.html

structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gt2erqqmgtv.html

[U93] JS：模板字符串
来源：http://dali.guannengcc.top/Article/details/gt2dpbsyfmj.html

`共 ${n} 条`
来源：http://dali.nanxuanxn.top/Article/details/gt2enoobedf.html

[U94] JS：箭头函数
来源：http://dali.cheryme.top/Article/details/gt2hwhgfoau.html

const double = x => x * 2;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wpurtfqg.html

[U95] JS：Promise 包装
来源：http://dali.jqgufenzy.top/Article/details/gt2eftrhjfc.html

new Promise((resolve, reject) => {})
来源：http://dali.kuanghao11.cn/Article/details/gt2eazmtzac.html

[U96] JS：async/await 与异常
来源：http://dali.dashuyun.cn/Article/details/gt2icfjwhwt.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gt2bxftcozu.html

[U97] JS：并发请求
来源：http://dali.hfpthk.cn/Article/details/gt2pazsjgbe.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gt2cpzenhao.html

[U98] JS：fetch 带 JSON
来源：http://dali.yj20258888.top/Article/details/gt2oauhbood.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.gogol.net.cn/Article/details/gt2gmvgzilm.html

[U99] JS：事件监听
来源：http://dali.jiagoushi.top/Article/details/gt2bgfdwyse.html

el.addEventListener("click", e => {})
来源：http://dali.hywenlv.cn/Article/details/gt2lvjihvop.html

[U100] JS：DOM 查询
来源：http://dali.xziqi.cn/Article/details/gt2sionespe.html

document.querySelector(".item")
来源：http://dali.hnxiangtu.top/Article/details/gt2mpqcedcv.html

[U101] JS：classList 操作
来源：http://dali.zhongyouzk.top/Article/details/gt2qasnocwv.html

el.classList.toggle("active")
来源：http://dali.xziqi.cn/Article/details/gt2nwsyzlsb.html

[U102] JS：本地存储
来源：http://dali.xuanzx.com/Article/details/gt2wsfpfkbg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.sxryk.cn/Article/details/gt2qcwdaiey.html

[U103] JS：定时器
来源：http://dali.ybcxt.top/Article/details/gt2ykfqarbq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.shzxlz.cn/Article/details/gt2sxxgakwe.html

[U104] JS：防抖
来源：http://dali.iojbl.cn/Article/details/gt2dioztchk.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangdashe.top/Article/details/gt2gfoszyox.html

[U105] JS：节流
来源：http://dali.mhx1999.top/Article/details/gt2uunadbbs.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2clcbcbtl.html

[U106] JS：日期格式化
来源：http://dali.xziqi.cn/Article/details/gt2pfirdvfb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2btdgmhqg.html

[U107] JS：数字千分位
来源：http://dali.0kj1m.cn/Article/details/gt2omqzbyue.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wiyqgnqr.html

[U108] JS：随机整数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oddtpwmu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.daria6918.cn/Article/details/gt2tnqwyzqf.html

[U109] JS：数组分组
来源：http://dali.sweek.top/Article/details/gt2ousqldrq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.nwbrower.top/Article/details/gt2vmmcdqbf.html

[U110] JS：数组分块
来源：http://dali.jinqigfzy.top/Article/details/gt2fdrrperv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.gzhubu.top/Article/details/gt2keweiukw.html

[U111] JS：对象转 Map
来源：http://dali.andypj.xyz/Article/details/gt2moiuzouz.html

new Map(Object.entries(obj))
来源：http://dali.jiagoushi.top/Article/details/gt2noxpzcpl.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2lenpbgdx.html

"7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gt2bebkazsi.html

[U113] JS：正则替换全部
来源：http://dali.yueranfly.top/Article/details/gt2lnvwwhrw.html

s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gt2cktxbgpv.html

[U114] JS：JSON 深比较
来源：http://dali.daria6918.cn/Article/details/gt2kfmubfkg.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xylfe.cn/Article/details/gt2ttyynrow.html

[U115] JS：生成 UUID
来源：http://dali.ppjwa.cn/Article/details/gt2bfjpmegl.html

crypto.randomUUID()
来源：http://dali.shzxlz.cn/Article/details/gt2ortfylwv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.smart0.xyz/Article/details/gt2lozgjzkl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.hnqzz.top/Article/details/gt2oxjkkwsl.html

[U117] JS：单元测试
来源：http://dali.jianghu66.top/Article/details/gt2uxckkert.html

npm i -D vitest;  npx vitest
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2esabgdtj.html

[U118] JS：开发服务器
来源：http://dali.birdmap.top/Article/details/gt2grhgwkej.html

npm i -D vite;  npx vite
来源：http://dali.316326.xyz/Article/details/gt2kconjnvn.html

[U119] JS：生产构建
来源：http://dali.havefunace.top/Article/details/gt2iajiygnn.html

npx vite build
来源：http://dali.yvedp.cn/Article/details/gt2oxetzftk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.gaohongyu789.top/Article/details/gt2lzwzmxtc.html

import.meta.env.VITE_API_URL
来源：http://dali.haohaochexian.top/Article/details/gt2tknfidip.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2gtmrbrns.html

统计汇总
来源：http://dali.gotoacloud.top/Article/details/gt2zctuypdg.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2qlsibufy.html

按语言统计（条）：
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2poguslnb.html

Python ......... 252
来源：http://dali.zhongyouzk.top/Article/details/gt2arcgajyl.html

PHP ............ 252
来源：http://dali.snrcjt.cn/Article/details/gt2lqtlycwl.html

JavaScript ..... 252
来源：http://dali.jinqigfzy.top/Article/details/gt2jgnrsekt.html

TypeScript ..... 212
来源：http://dali.yvedp.cn/Article/details/gt2vapgwuts.html

Java ........... 212
来源：http://dali.sysykeji.top/Article/details/gt2ifytuuqa.html

Go ............. 212
来源：http://dali.yonumen.top/Article/details/gt2wmqnffql.html

Ruby ........... 212
来源：http://dali.hongshengwenyu.top/Article/details/gt2qjfzdvxh.html

C# ............. 212
来源：http://dali.birdmap.top/Article/details/gt2mgrjmoaq.html

C .............. 30
来源：http://dali.xinyue.icu/Article/details/gt2wjejzsmk.html

C++ ............ 30
来源：http://dali.cqqwz.cn/Article/details/gt2dqzbltht.html

SQL ............ 90
来源：http://dali.zhongyouzk.top/Article/details/gt2vsuawjuf.html

Bash ........... 80
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mljobtyu.html

Kotlin ......... 15
来源：http://dali.ppjwa.cn/Article/details/gt2drnxpxgj.html

Swift .......... 15
来源：http://dali.meibo888.top/Article/details/gt2gwlxljol.html

Lua ............ 10
来源：http://dali.chenzaomai.com/Article/details/gt2ztbgijel.html

Perl ........... 10
来源：http://dali.hnxiangtu.top/Article/details/gt2ybdmghga.html

Scala .......... 10
来源：http://dali.shzxlz.cn/Article/details/gt2qctjzmdn.html

------------------------------------
来源：http://dali.zhiwuduotai.top/Article/details/gt2pdgcvtug.html

合计 ........... 2106 条
来源：http://dali.wangdashe.top/Article/details/gt2yyfmfupn.html

按章节统计：
来源：http://dali.andypj.xyz/Article/details/gt2setesezq.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.quarkkingdee.top/Article/details/gt2fmbpftry.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.bjfxy.top/Article/details/gt2znpwbusn.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shzxlz.cn/Article/details/gt2tuxmsvsa.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.bjfxy.top/Article/details/gt2mexnjtcd.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hnxiangtu.top/Article/details/gt2rizhyugi.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhixingplan.top/Article/details/gt2vmggbbjd.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yueranfly.top/Article/details/gt2kmupnrfq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.mhx1999.top/Article/details/gt2fqrjvhrb.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yangfankeji.com/Article/details/gt2tjzacfur.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhoulong.xyz/Article/details/gt2gquupmgl.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.meibo888.top/Article/details/gt2spbfiqef.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.wangshuangyany.cn/Article/details/gt2nsdwjeip.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zdqjudy.top/Article/details/gt2izoetrvf.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jinqigufen.top/Article/details/gt2kzbqnpqd.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.cucudq.cn/Article/details/gt2ugxebabq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.xuanzx.com/Article/details/gt2widfjtos.html

Q SQL 专题                              90
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qjibamjc.html

R Bash 专题                             80
来源：http://dali.tianlin.xyz/Article/details/gt2ftctsnap.html

S C / C++ 专题                          60
来源：http://dali.vqdsnc.cn/Article/details/gt2wotauvki.html

T 其他语言补充                          60
来源：http://dali.aizwys.cn/Article/details/gt2sopsacef.html

U 高频实用片段                         120
来源：http://dali.hywenlv.cn/Article/details/gt2kubaolrc.html

------------------------------------
来源：http://dali.guannengcc.top/Article/details/gt2ycrvelvw.html

合计                                  2106 条
来源：http://dali.sufxvd.cn/Article/details/gt2sfmoccrl.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258888.top/Article/details/gt2fgryhcmb.html

使用提醒
来源：http://dali.guannengcc.top/Article/details/gt2ntualqpm.html

--------------------------------------------------------------------------------
来源：http://dali.hysaishi.cn/Article/details/gt2wayodjlx.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.pycfn.com/Article/details/gt2ltxvtfmr.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jqgfzy.top/Article/details/gt2qavltuja.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.iojbl.cn/Article/details/gt2knodqqnx.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yj202588.top/Article/details/gt2nbhnfmgt.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.cucudq.cn/Article/details/gt2kmivnfej.html

—— 文件结束 ——
来源：http://dali.shangyingyoupin.top/Article/details/gt2zrktvpxx.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2vzvytbep.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vbttpvyl.html

Common Programming Examples Cheat Book
来源：http://dali.ivvv.top/Article/details/gt2urpopeeu.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2ktwhrbkw.html

【收录内容】
来源：http://dali.vqdsnc.cn/Article/details/gt2nglampvp.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.xylfe.cn/Article/details/gt2mmrxwres.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.fengsongda.top/Article/details/gt2fyueecdm.html

SQL · Bash · C · C++
来源：http://dali.316326.xyz/Article/details/gt2qgcztxyw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yonumen.top/Article/details/gt2zcivqkna.html

【使用说明】
来源：http://dali.nwbrower.top/Article/details/gt2hklbmzcm.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ujchnruv.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.cheryme.top/Article/details/gt2rhjddoap.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.sweek.top/Article/details/gt2aascrcfo.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhoulong.xyz/Article/details/gt2fbttmpro.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.gaohongyu789.top/Article/details/gt2hotvwhey.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jqgufenzy.top/Article/details/gt2scphryog.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhiwuduotai.top/Article/details/gt2edrwfeho.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2snzotuly.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.chenlongwang.top/Article/details/gt2cqrypzea.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ljyvtzga.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tsuliaad.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhongyouzk.top/Article/details/gt2nsabluto.html

【文件统计】
来源：http://dali.dianchejie.cn/Article/details/gt2iljsubug.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.shuidangran.top/Article/details/gt2moyzsllx.html

--------------------------------------------------------------------------------
来源：http://dali.haohaochexian.top/Article/details/gt2xvxhrfat.html

目  录
来源：http://dali.sysykeji.top/Article/details/gt2vczxwmbt.html

--------------------------------------------------------------------------------
来源：http://dali.yonumen.top/Article/details/gt2zxjnrkqv.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2pbepkvjy.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gdcqfcll.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.nanxinkj.top/Article/details/gt2uoqaouvp.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ppjwa.cn/Article/details/gt2nkdjhhcq.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yj202588.top/Article/details/gt2ecpiisse.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.ppjwa.cn/Article/details/gt2djwdxaot.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.chenlongwang.top/Article/details/gt2qjvtrwnq.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jddkxgss.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.xylfe.cn/Article/details/gt2cspxzufg.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.cqqwz.cn/Article/details/gt2ybcphdoj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.tian-w.cn/Article/details/gt2nlgbfjnl.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.shzxlz.cn/Article/details/gt2xjnhnctk.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.c1oappe.top/Article/details/gt2vrdbrvqt.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2nsihccfm.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.tanke756.top/Article/details/gt2msmftbzy.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yuanzhike.top/Article/details/gt2scovudut.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.cheryme.top/Article/details/gt2jogglmlt.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.wangshuangyany.cn/Article/details/gt2sbgpkymu.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.guowangkeji.top/Article/details/gt2lfxkedpn.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hongshengwenyu.top/Article/details/gt2qoenogcf.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yanxiufei.cn/Article/details/gt2tjqqxdbe.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2mnscoxez.html

A. 基础语法与类型
来源：http://dali.tanke756.top/Article/details/gt2oozezsaf.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2ruxdjent.html

[A01] Hello World
来源：http://dali.ydzc1.top/Article/details/gt2maesjuyi.html

Py:   print("Hello, World!")
来源：http://dali.guannengcc.top/Article/details/gt2azclhewt.html

PHP:  echo "Hello, World!";
来源：http://dali.vqdsnc.cn/Article/details/gt2ffivudiq.html

JS:   console.log("Hello, World!");
来源：http://dali.hfpthk.cn/Article/details/gt2dwhauohl.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.daxiang520.top/Article/details/gt2ncncdkfg.html

Java: System.out.println("Hello, World!");
来源：http://dali.iojbl.cn/Article/details/gt2speujqkb.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhoulong.xyz/Article/details/gt2oagftevl.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbdpgla.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hfpthk.cn/Article/details/gt2pdelnqss.html

[A02] 变量声明与赋值
来源：http://dali.yj202588.top/Article/details/gt2pjunggxz.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bsvugqgh.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.guowangkeji.top/Article/details/gt2wwsetzrs.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.daria6918.cn/Article/details/gt2ccwnqurw.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhiwuduotai.top/Article/details/gt2gbixlffo.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.ehwqpu.com/Article/details/gt2oedfdwsg.html

Go:   name := "Alex"; age := 20
来源：http://dali.cdnleiting.top/Article/details/gt2sgfofetm.html

Ruby: name = "Alex"; age = 20
来源：http://dali.meibo888.top/Article/details/gt2wyptbktu.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.hnxiangtu.top/Article/details/gt2ietnrdxi.html

[A03] 常量定义
来源：http://dali.jyoumei.cn/Article/details/gt2qzxpnxan.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.sweek.top/Article/details/gt2hnybyhsx.html

PHP:  const PI = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aeplrknr.html

JS:   const PI = 3.14159;
来源：http://dali.cashguo.top/Article/details/gt2udynmkyx.html

TS:   const PI: number = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gt2srygeckc.html

Java: static final double PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dzusbhii.html

Go:   const PI = 3.14159
来源：http://dali.xuanzx.com/Article/details/gt2hcdkujxy.html

Ruby: PI = 3.14159
来源：http://dali.sysykeji.top/Article/details/gt2renovmat.html

C#:   const double PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gt2dbxckqxr.html

[A04] 判断变量类型
来源：http://dali.shzxlz.cn/Article/details/gt2fnbeqosl.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.gotoacloud.top/Article/details/gt2ceoycddm.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ytexykwg.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.ybcxt.top/Article/details/gt2cdoebsul.html

TS:   typeof x; x instanceof Date
来源：http://dali.gzhubu.top/Article/details/gt2foovwtcu.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.hnqzz.top/Article/details/gt2coabwnus.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.haohaochexian.top/Article/details/gt2ewlulbof.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xinyue.icu/Article/details/gt2ikjcpyat.html

C#:   x.GetType().Name; x is int
来源：http://dali.tanke756.top/Article/details/gt2wtsyktdg.html

[A05] 整数除法与取模
来源：http://dali.jinqigufen.top/Article/details/gt2ylbebzvl.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2nsdtqkcr.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gt2diiuxtnr.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.sweek.top/Article/details/gt2mtveyhqf.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.meibo888.top/Article/details/gt2eeoltwha.html

Java: 7 / 2; 7 % 2
来源：http://dali.yvedp.cn/Article/details/gt2yuktvchd.html

Go:   7 / 2; 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gt2hewclmwb.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.shzxlz.cn/Article/details/gt2uvlwfvjx.html

C#:   7 / 2; 7 % 2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ptxrrgzi.html

[A06] 字符串转数字
来源：http://dali.cucudq.cn/Article/details/gt2flbopqyo.html

Py:   int("42"); float("3.14")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fuzlnfvr.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zdqjudy.top/Article/details/gt2xisaagnt.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.shangyingyoupin.top/Article/details/gt2cddbgabu.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jinqigfzy.top/Article/details/gt2fvawmveg.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.shuidangran.top/Article/details/gt2axcharug.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.smart0.xyz/Article/details/gt2skshtmlb.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jianghu66.top/Article/details/gt2wseperbm.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.aibaodan.cn/Article/details/gt2haxewjns.html

[A07] 数字转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2hgyopnpr.html

Py:   str(42)
来源：http://dali.xinyue.icu/Article/details/gt2zdhtwznc.html

PHP:  (string) 42; strval(42)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vgukiqdw.html

JS:   String(42); (42).toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iubmtcgc.html

TS:   String(42)
来源：http://dali.redwolf501.top/Article/details/gt2uobkezjb.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.fzhhl.top/Article/details/gt2hvcrsywt.html

Go:   strconv.Itoa(42)
来源：http://dali.tianlin.xyz/Article/details/gt2pzhvaagv.html

Ruby: 42.to_s
来源：http://dali.9152youxi.cn/Article/details/gt2ginzcwax.html

C#:   42.ToString()
来源：http://dali.hysaishi.cn/Article/details/gt2brxmrxij.html

[A08] 取整与四舍五入
来源：http://dali.daria6918.cn/Article/details/gt2iptaqbmg.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ubpyprqv.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.xuanzx.com/Article/details/gt2ybgaqstv.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yanxiufei.cn/Article/details/gt2oksglxoc.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.ivvv.top/Article/details/gt2unntlgca.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.xylfe.cn/Article/details/gt2agwocfrn.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.cucudq.cn/Article/details/gt2gwzscgbr.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yj202588.top/Article/details/gt2spxohhsm.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.ivvv.top/Article/details/gt2nxjubpja.html

[A09] 绝对值与最大最小值
来源：http://dali.pengpengdd.cyou/Article/details/gt2yqujjhev.html


<!-- 参考信息 -->