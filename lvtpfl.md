代发 wailian999

[U61] PHP：正则
来源：http://dali.sysykeji.top/Article/details/gt2twfligoc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hfpthk.cn/Article/details/gt2kgyjwqpw.html

[U62] PHP：日期对象
来源：http://dali.shzxlz.cn/Article/details/gt2yplksfgm.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hongshengwenyu.top/Article/details/gt2tnhlyxdt.html

[U63] PHP：文件读写
来源：http://dali.kuanghao11.cn/Article/details/gt2dqyyjujc.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhiwuduotai.top/Article/details/gt2dveekbjt.html

[U64] PHP：目录遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bjvutzic.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.daxiang520.top/Article/details/gt2wivxulzd.html

[U65] PHP：会话
来源：http://dali.daxiang520.top/Article/details/gt2oqarlbvg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gt2vttakmxm.html

[U66] PHP：设置 Cookie
来源：http://dali.ivvv.top/Article/details/gt2xiygqjpv.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.xuanzx.com/Article/details/gt2iozjnxyb.html

[U67] PHP：处理文件上传
来源：http://dali.redwolf501.top/Article/details/gt2secycqay.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.cucudq.cn/Article/details/gt2ahbfqdzl.html

[U68] PHP：PDO 连接
来源：http://dali.meibo888.top/Article/details/gt2fttourgk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.snrcjt.cn/Article/details/gt2slabyktn.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ljradwsu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zycfv.cn/Article/details/gt2jblhfcdw.html

[U70] PHP：PDO 事务
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hjtfktib.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hysaishi.cn/Article/details/gt2fijgdlku.html

[U71] PHP：抛出异常
来源：http://dali.yj20258888.top/Article/details/gt2mbbnduhh.html

throw new RuntimeException("失败", 500);
来源：http://dali.hammf.cn/Article/details/gt2bacbinyu.html

[U72] PHP：写错误日志
来源：http://dali.yj20258.top/Article/details/gt2lovxqrhw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhoulong.xyz/Article/details/gt2sadycffe.html

[U73] PHP：读取 ini 配置
来源：http://dali.hammf.cn/Article/details/gt2vavazzqy.html

parse_ini_file("config.ini", true)
来源：http://dali.yueranfly.top/Article/details/gt2ttnqtwzf.html

[U74] PHP：读取环境变量
来源：http://dali.yueranfly.top/Article/details/gt2cnyqhbbc.html

getenv("APP_ENV") ?: "production"
来源：http://dali.sxryk.cn/Article/details/gt2dhssldvy.html

[U75] PHP：依赖注入
来源：http://dali.birdmap.top/Article/details/gt2ropnnbfv.html

composer require psr/container
来源：http://dali.yvedp.cn/Article/details/gt2oxafxwjf.html

[U76] PHP：简单路由
来源：http://dali.pycfn.com/Article/details/gt2fsrwiaaj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.feifeiyinyue.top/Article/details/gt2hzwzsyan.html

[U77] PHP：模板渲染
来源：http://dali.tianlin.xyz/Article/details/gt2zqblonnx.html

composer require twig/twig
来源：http://dali.ppjwa.cn/Article/details/gt2yalcwzzl.html

[U78] PHP：单元测试
来源：http://dali.sufxvd.cn/Article/details/gt2lgvdprze.html

composer require --dev phpunit/phpunit
来源：http://dali.yj202588.top/Article/details/gt2ecrrvyiu.html

[U79] PHP：静态分析
来源：http://dali.yj20258.top/Article/details/gt2bmxmkufx.html

composer require --dev phpstan/phpstan
来源：http://dali.nanxinkj.top/Article/details/gt2pvxkklqx.html

[U80] PHP：代码规范修复
来源：http://dali.fzhhl.top/Article/details/gt2ipfwgzwo.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.birdmap.top/Article/details/gt2tlopkgdl.html

[U81] JS：初始化项目
来源：http://dali.gotoacloud.top/Article/details/gt2gwxqnfsh.html

npm init -y;  npm i express
来源：http://dali.xuanzx.com/Article/details/gt2vbnirpxv.html

[U82] JS：package.json 脚本
来源：http://dali.iojbl.cn/Article/details/gt2ieihnnfd.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.fzhhl.top/Article/details/gt2sotrtqqz.html

[U83] JS：ES Module 导入导出
来源：http://dali.guannengcc.top/Article/details/gt2mtrdlxtu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yvedp.cn/Article/details/gt2hidvyhdv.html

[U84] JS：CommonJS 写法
来源：http://dali.hfpthk.cn/Article/details/gt2tiiogifb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tnwqoowq.html

[U85] JS：可选链
来源：http://dali.xuetiantiany.cn/Article/details/gt2fbhgtztn.html

a?.b?.c
来源：http://dali.shuidangran.top/Article/details/gt2qrqzklwx.html

[U86] JS：空值合并
来源：http://dali.feifeiyinyue.top/Article/details/gt2gsmesbec.html

a ?? b
来源：http://dali.aizwys.cn/Article/details/gt2lnftolaz.html

[U87] JS：解构默认值
来源：http://dali.kuanghao11.cn/Article/details/gt2pyadnigl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.sweek.top/Article/details/gt2dbzbojme.html

[U88] JS：对象展开合并
来源：http://dali.yueranfly.top/Article/details/gt2rlolrwgo.html

{ ...a, ...b }
来源：http://dali.yj20258.top/Article/details/gt2ptbbkdfm.html

[U89] JS：数组去重
来源：http://dali.daxiang520.top/Article/details/gt2flddlslq.html

[...new Set(arr)]
来源：http://dali.ybcxt.top/Article/details/gt2ulonmshz.html

[U90] JS：数字数组排序
来源：http://dali.vqdsnc.cn/Article/details/gt2pcbdiqoh.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cmprdfbz.html

[U91] JS：对象键值遍历
来源：http://dali.redwolf501.top/Article/details/gt2cltyqoff.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yvedp.cn/Article/details/gt2tqyxxpvr.html

[U92] JS：深拷贝
来源：http://dali.tanke756.top/Article/details/gt2woqoseqk.html

structuredClone(obj)
来源：http://dali.redwolf501.top/Article/details/gt2dkimnovj.html

[U93] JS：模板字符串
来源：http://dali.havefunace.top/Article/details/gt2piqfmffc.html

`共 ${n} 条`
来源：http://dali.ybcxt.top/Article/details/gt2tgbnkznc.html

[U94] JS：箭头函数
来源：http://dali.cashguo.top/Article/details/gt2jigssggw.html

const double = x => x * 2;
来源：http://dali.ybcxt.top/Article/details/gt2xbqapglx.html

[U95] JS：Promise 包装
来源：http://dali.316326.xyz/Article/details/gt2lrttjoep.html

new Promise((resolve, reject) => {})
来源：http://dali.aizwys.cn/Article/details/gt2gftuheff.html

[U96] JS：async/await 与异常
来源：http://dali.shzxlz.cn/Article/details/gt2lggnbkqn.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gt2xmcztwku.html

[U97] JS：并发请求
来源：http://dali.316326.xyz/Article/details/gt2ugdqtmtz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhixingplan.top/Article/details/gt2xaqvhqdx.html

[U98] JS：fetch 带 JSON
来源：http://dali.aizwys.cn/Article/details/gt2jyhxtrro.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hnxiangtu.top/Article/details/gt2vjnkghbr.html

[U99] JS：事件监听
来源：http://dali.mhx1999.top/Article/details/gt2uzdfrzjc.html

el.addEventListener("click", e => {})
来源：http://dali.xziqi.cn/Article/details/gt2eoyllgmj.html

[U100] JS：DOM 查询
来源：http://dali.ehwqpu.com/Article/details/gt2stdzrjml.html

document.querySelector(".item")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cthimksy.html

[U101] JS：classList 操作
来源：http://dali.hammf.cn/Article/details/gt2qukhjpcy.html

el.classList.toggle("active")
来源：http://dali.9152youxi.cn/Article/details/gt2zcaqgaul.html

[U102] JS：本地存储
来源：http://dali.hammf.cn/Article/details/gt2gghqukfs.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hawdoade.html

[U103] JS：定时器
来源：http://dali.haohaochexian.top/Article/details/gt2mbokzfta.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.sweek.top/Article/details/gt2xgmzuckg.html

[U104] JS：防抖
来源：http://dali.havefunace.top/Article/details/gt2athfdpdx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ltsjafsu.html

[U105] JS：节流
来源：http://dali.jinqigufen.top/Article/details/gt2xnrvqlkj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mjaihgys.html

[U106] JS：日期格式化
来源：http://dali.meibo888.top/Article/details/gt2uanebjxe.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.fzhhl.top/Article/details/gt2hgewxhbt.html

[U107] JS：数字千分位
来源：http://dali.xylfe.cn/Article/details/gt2egfflvne.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ofplwlyq.html

[U108] JS：随机整数
来源：http://dali.ppjwa.cn/Article/details/gt2ksqgipfi.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hammf.cn/Article/details/gt2erdjnkvd.html

[U109] JS：数组分组
来源：http://dali.ivvv.top/Article/details/gt2gtxduhvw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.dianchejie.cn/Article/details/gt2ypypdzjy.html

[U110] JS：数组分块
来源：http://dali.yj202588.top/Article/details/gt2bpbtodby.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hysaishi.cn/Article/details/gt2dkpcgigh.html

[U111] JS：对象转 Map
来源：http://dali.yj20258.top/Article/details/gt2qpmlgqiq.html

new Map(Object.entries(obj))
来源：http://dali.zhoulong.xyz/Article/details/gt2goilmzrs.html

[U112] JS：字符串补位
来源：http://dali.gzhubu.top/Article/details/gt2txfjaetx.html

"7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gt2hwvrkjtp.html

[U113] JS：正则替换全部
来源：http://dali.hongshengwenyu.top/Article/details/gt2hobksdjo.html

s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gt2uxbxnkli.html

[U114] JS：JSON 深比较
来源：http://dali.shuidangran.top/Article/details/gt2nxniujmb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qyfuaqto.html

[U115] JS：生成 UUID
来源：http://dali.hnqzz.top/Article/details/gt2virkchtv.html

crypto.randomUUID()
来源：http://dali.aizwys.cn/Article/details/gt2qrdbppnt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.chenjidiqi.icu/Article/details/gt2hveujlhh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.bjfxy.top/Article/details/gt2pewywdyw.html

[U117] JS：单元测试
来源：http://dali.yj202588.top/Article/details/gt2anmacvfx.html

npm i -D vitest;  npx vitest
来源：http://dali.zhoulong.xyz/Article/details/gt2knnixruv.html

[U118] JS：开发服务器
来源：http://dali.hongshengwenyu.top/Article/details/gt2anbjleqy.html

npm i -D vite;  npx vite
来源：http://dali.cashguo.top/Article/details/gt2pkvnftvh.html

[U119] JS：生产构建
来源：http://dali.yongpay.top/Article/details/gt2tsgdmaxh.html

npx vite build
来源：http://dali.zhongyouzk.top/Article/details/gt2lojiovhd.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xylfe.cn/Article/details/gt2sokeytut.html

import.meta.env.VITE_API_URL
来源：http://dali.smart0.xyz/Article/details/gt2yyerdxcb.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2ghzjsxcf.html

统计汇总
来源：http://dali.jqgufenzy.top/Article/details/gt2uhjztxit.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2ksyiopdf.html

按语言统计（条）：
来源：http://dali.jinqigfzy.top/Article/details/gt2dsntycoj.html

Python ......... 252
来源：http://dali.yj20258888.top/Article/details/gt2cvivgnpx.html

PHP ............ 252
来源：http://dali.jqgfzy.top/Article/details/gt2uxbrhqvl.html

JavaScript ..... 252
来源：http://dali.quarkkingdee.top/Article/details/gt2qaorkuct.html

TypeScript ..... 212
来源：http://dali.zycfv.cn/Article/details/gt2pvftxeqv.html

Java ........... 212
来源：http://dali.yangfankeji.com/Article/details/gt2myaygsry.html

Go ............. 212
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zettbrph.html

Ruby ........... 212
来源：http://dali.zhengqikj.top/Article/details/gt2inejypue.html

C# ............. 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hspdkmdn.html

C .............. 30
来源：http://dali.meibo888.top/Article/details/gt2ovuvxxbg.html

C++ ............ 30
来源：http://dali.yuanzhike.top/Article/details/gt2nwviwbqy.html

SQL ............ 90
来源：http://dali.yongpay.top/Article/details/gt2lwdrjfxk.html

Bash ........... 80
来源：http://dali.svipenyu.cn/Article/details/gt2zqisbljg.html

Kotlin ......... 15
来源：http://dali.hywenlv.cn/Article/details/gt2jyrxgfhp.html

Swift .......... 15
来源：http://dali.zhongyouzk.top/Article/details/gt2umzecpuj.html

Lua ............ 10
来源：http://dali.nanxinkj.top/Article/details/gt2hfbjmymw.html

Perl ........... 10
来源：http://dali.shuidangran.top/Article/details/gt2yaxyjqah.html

Scala .......... 10
来源：http://dali.316326.xyz/Article/details/gt2ipzhkimv.html

------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gt2swqgnnrx.html

合计 ........... 2106 条
来源：http://dali.xinyue.icu/Article/details/gt2gzpdajea.html

按章节统计：
来源：http://dali.jinqigfzy.top/Article/details/gt2qhrowhsk.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jinqigufen.top/Article/details/gt2qrmyknuq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.havefunace.top/Article/details/gt2eixnqwtk.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.9152youxi.cn/Article/details/gt2tgxybbyw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhixingplan.top/Article/details/gt2kezymdbl.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhixingplan.top/Article/details/gt2vvpirpak.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hfpthk.cn/Article/details/gt2omnfmqcg.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.wangshuangyany.cn/Article/details/gt2skysmcew.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yuxming.cn/Article/details/gt2ikisvjqe.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jianghu66.top/Article/details/gt2ipfsuucl.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yongpay.top/Article/details/gt2tgnlgfqy.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jyoumei.cn/Article/details/gt2wsahtpre.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.chenzaomai.com/Article/details/gt2ukkcgqwx.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.haohaochexian.top/Article/details/gt2ewwffnwu.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.aizwys.cn/Article/details/gt2fazxhxxp.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.aibaodan.cn/Article/details/gt2hojheaxr.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.tanke756.top/Article/details/gt2casayczs.html

Q SQL 专题                              90
来源：http://dali.jqgufenzy.top/Article/details/gt2pcxiiiah.html

R Bash 专题                             80
来源：http://dali.tian-w.cn/Article/details/gt2nwmcrnkb.html

S C / C++ 专题                          60
来源：http://dali.yueranfly.top/Article/details/gt2xenkvhwi.html

T 其他语言补充                          60
来源：http://dali.daria6918.cn/Article/details/gt2afvhepht.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdkiuvt.html

------------------------------------
来源：http://dali.svipenyu.cn/Article/details/gt2uuhehqoo.html

合计                                  2106 条
来源：http://dali.jianghu66.top/Article/details/gt2ecvytsyh.html

--------------------------------------------------------------------------------
来源：http://dali.ppjwa.cn/Article/details/gt2ccvcdpra.html

使用提醒
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eumzwbkz.html

--------------------------------------------------------------------------------
来源：http://dali.jianghu66.top/Article/details/gt2vorvicib.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.316326.xyz/Article/details/gt2wmclwhbf.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yonumen.top/Article/details/gt2fytxjpgq.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.9152youxi.cn/Article/details/gt2amzygfrs.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.nwbrower.top/Article/details/gt2hxpblcps.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yj20258888.top/Article/details/gt2omzitprw.html

—— 文件结束 ——
来源：http://dali.hysaishi.cn/Article/details/gt2qnafzayo.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2ysjfadws.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ovspmwbx.html

Common Programming Examples Cheat Book
来源：http://dali.chenzaomai.com/Article/details/gt2dhuucbwb.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2joirrqpd.html

【收录内容】
来源：http://dali.gzhubu.top/Article/details/gt2tvvirchq.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hysaishi.cn/Article/details/gt2eqsazmnj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.gogol.net.cn/Article/details/gt2hohkpjao.html

SQL · Bash · C · C++
来源：http://dali.yj20258.top/Article/details/gt2fdzqxsxi.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.guannengcc.top/Article/details/gt2pverkbjw.html

【使用说明】
来源：http://dali.dianchejie.cn/Article/details/gt2epmanqly.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.aizwys.cn/Article/details/gt2mddppqpb.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.c1oappe.top/Article/details/gt2becwdtrx.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.nanxuanxn.top/Article/details/gt2ivqlhvzj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.daxiang520.top/Article/details/gt2hhsmptlu.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hammf.cn/Article/details/gt2vqtiqbcj.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.cashguo.top/Article/details/gt2ljpzeiep.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yj20258888.top/Article/details/gt2uzjpygwf.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.chenjidiqi.icu/Article/details/gt2vtwurbuc.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.snrcjt.cn/Article/details/gt2pzphrsxl.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.hnxiangtu.top/Article/details/gt2xumbqxca.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.chenzaomai.com/Article/details/gt2jksglqdx.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.birdmap.top/Article/details/gt2likwcwtg.html

【文件统计】
来源：http://dali.smart0.xyz/Article/details/gt2tqcofoiu.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.fengsongda.top/Article/details/gt2jbsznaeo.html

--------------------------------------------------------------------------------
来源：http://dali.tianlin.xyz/Article/details/gt2krxqmaay.html

目  录
来源：http://dali.yuxming.cn/Article/details/gt2rsfaqtnq.html

--------------------------------------------------------------------------------
来源：http://dali.jinqigufen.top/Article/details/gt2tsqiseuj.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.c1oappe.top/Article/details/gt2tkqarqgl.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.wangshuangyany.cn/Article/details/gt2eswhompc.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jddimrze.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xinyue.icu/Article/details/gt2mqabhkmu.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzheuns.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.feifeiyinyue.top/Article/details/gt2eqzdoqbo.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.wangdashe.top/Article/details/gt2bblbooov.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hywenlv.cn/Article/details/gt2kuqtejsf.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.tian-w.cn/Article/details/gt2oqhwlmcx.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yueranfly.top/Article/details/gt2nbzodyjf.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.xuanzx.com/Article/details/gt2npzbodkd.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yj20258.top/Article/details/gt2kgnmbgoq.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zycfv.cn/Article/details/gt2vbdozftw.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ofeavryn.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jinqigufen.top/Article/details/gt2sfvpfisr.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.c1oappe.top/Article/details/gt2zuvbsbiy.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.wangshuangyany.cn/Article/details/gt2zqiwcrzy.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gnsiiged.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.kuanghao11.cn/Article/details/gt2nrsjraqv.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenjidiqi.icu/Article/details/gt2twbthpsj.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.ivvv.top/Article/details/gt2hgavjacd.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2eyzwmwyj.html

A. 基础语法与类型
来源：http://dali.zhoulong.xyz/Article/details/gt2eaxdxeyg.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2bbyidpgy.html

[A01] Hello World
来源：http://dali.guannengcc.top/Article/details/gt2pwmkbjfg.html

Py:   print("Hello, World!")
来源：http://dali.havefunace.top/Article/details/gt2lfhacixn.html

PHP:  echo "Hello, World!";
来源：http://dali.0kj1m.cn/Article/details/gt2tiasayks.html

JS:   console.log("Hello, World!");
来源：http://dali.birdmap.top/Article/details/gt2jkurqywr.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.aibaodan.cn/Article/details/gt2awoqqauv.html

Java: System.out.println("Hello, World!");
来源：http://dali.dianchejie.cn/Article/details/gt2ggccoixs.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wwgcggtm.html

Ruby: puts "Hello, World!"
来源：http://dali.hysaishi.cn/Article/details/gt2iqwskxzi.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.daria6918.cn/Article/details/gt2puuzdett.html

[A02] 变量声明与赋值
来源：http://dali.gzhubu.top/Article/details/gt2qvemgbtk.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jinqigfzy.top/Article/details/gt2ygblrxmf.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.aizwys.cn/Article/details/gt2jltdftyr.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.guowangkeji.top/Article/details/gt2fbmgqqed.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.svipenyu.cn/Article/details/gt2ihnrulga.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.aizwys.cn/Article/details/gt2waqapcqz.html

Go:   name := "Alex"; age := 20
来源：http://dali.vqdsnc.cn/Article/details/gt2ocksbjsu.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hysaishi.cn/Article/details/gt2mororwgx.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yangfankeji.com/Article/details/gt2ksnnbuyp.html

[A03] 常量定义
来源：http://dali.jinqigfzy.top/Article/details/gt2mneysnqw.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.pengpengdd.cyou/Article/details/gt2vkrtpitc.html

PHP:  const PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gt2mkxkktxh.html

JS:   const PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gt2tkwzapqa.html

TS:   const PI: number = 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gt2lmgmrlgd.html

Java: static final double PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gt2jvdjjxfd.html

Go:   const PI = 3.14159
来源：http://dali.kuanghao11.cn/Article/details/gt2dqdhymyj.html

Ruby: PI = 3.14159
来源：http://dali.pengpengdd.cyou/Article/details/gt2edkqgimt.html

C#:   const double PI = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gt2cglgdczq.html

[A04] 判断变量类型
来源：http://dali.zhixingplan.top/Article/details/gt2plzheklo.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.pycfn.com/Article/details/gt2wrbgdftc.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.tianlin.xyz/Article/details/gt2ksyisqsl.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhoulong.xyz/Article/details/gt2arpvfxkg.html

TS:   typeof x; x instanceof Date
来源：http://dali.hywenlv.cn/Article/details/gt2skdfnsuk.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bwjhoflb.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.xziqi.cn/Article/details/gt2jbcebpye.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhongyouzk.top/Article/details/gt2iywibmcs.html

C#:   x.GetType().Name; x is int
来源：http://dali.hammf.cn/Article/details/gt2itspksun.html

[A05] 整数除法与取模
来源：http://dali.shangyingyoupin.top/Article/details/gt2vaxupkwp.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2anpymsdl.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yongpay.top/Article/details/gt2gfbbmtgz.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gt2rtnfhnyc.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.c1oappe.top/Article/details/gt2wypwuypu.html

Java: 7 / 2; 7 % 2
来源：http://dali.birdmap.top/Article/details/gt2cymmexhu.html

Go:   7 / 2; 7 % 2
来源：http://dali.iojbl.cn/Article/details/gt2igzddvjl.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.sysykeji.top/Article/details/gt2vqkicbxc.html

C#:   7 / 2; 7 % 2
来源：http://dali.kuanghao11.cn/Article/details/gt2eubwvhis.html

[A06] 字符串转数字
来源：http://dali.cucudq.cn/Article/details/gt2xphnovkh.html

Py:   int("42"); float("3.14")
来源：http://dali.c1oappe.top/Article/details/gt2iidubwmw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.gzhubu.top/Article/details/gt2rhxmtztz.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.sxryk.cn/Article/details/gt2putzjcuk.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.havefunace.top/Article/details/gt2rqfeduek.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.sweek.top/Article/details/gt2zboixthl.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.cdnleiting.top/Article/details/gt2zvgifomb.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.xuanzx.com/Article/details/gt2lzzsxgfa.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.gzhubu.top/Article/details/gt2gnyeqfik.html

[A07] 数字转字符串
来源：http://dali.bjfxy.top/Article/details/gt2txgmfnqg.html

Py:   str(42)
来源：http://dali.daria6918.cn/Article/details/gt2xnukenvw.html

PHP:  (string) 42; strval(42)
来源：http://dali.sufxvd.cn/Article/details/gt2lprhbsvl.html

JS:   String(42); (42).toString()
来源：http://dali.hnxiangtu.top/Article/details/gt2nhicnisw.html

TS:   String(42)
来源：http://dali.guannengcc.top/Article/details/gt2zxgevaag.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhongyouzk.top/Article/details/gt2feshepzg.html

Go:   strconv.Itoa(42)
来源：http://dali.316326.xyz/Article/details/gt2kflbjgrj.html

Ruby: 42.to_s
来源：http://dali.tian-w.cn/Article/details/gt2ibekhlnl.html

C#:   42.ToString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ifkbmokf.html

[A08] 取整与四舍五入
来源：http://dali.birdmap.top/Article/details/gt2ukuvoyoh.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jqgufenzy.top/Article/details/gt2gmxrzwbq.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ekjkmpvy.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gtzluzhr.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.chenzaomai.com/Article/details/gt2wtcpnhby.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yueranfly.top/Article/details/gt2oqzkaqww.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.aibaodan.cn/Article/details/gt2rbdmmczz.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.mhx1999.top/Article/details/gt2pumegkim.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.daxiang520.top/Article/details/gt2oqefajdp.html

[A09] 绝对值与最大最小值
来源：http://dali.hammf.cn/Article/details/gt2gvgwygct.html


<!-- 参考信息 -->