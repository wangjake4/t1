代发 wailian999

[U59] PHP：自定义排序
来源：http://dali.yj20258.top/Article/details/gteqjqcjct.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yuanzhike.top/Article/details/gtwsaxhxmw.html

[U60] PHP：JSON 编解码
来源：http://dali.hnxiangtu.top/Article/details/gtyovnjcdz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jiagoushi.top/Article/details/gtxlgrzcha.html

[U61] PHP：正则
来源：http://dali.nanxuanxn.top/Article/details/gthxwpkufd.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.shzxlz.cn/Article/details/gtpebmside.html

[U62] PHP：日期对象
来源：http://dali.zhiwuduotai.top/Article/details/gthnshcpbw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.dashuyun.cn/Article/details/gtzrvaasgf.html

[U63] PHP：文件读写
来源：http://dali.gzhubu.top/Article/details/gtoajurdvb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.c1oappe.top/Article/details/gtanphctwm.html

[U64] PHP：目录遍历
来源：http://dali.cqqwz.cn/Article/details/gtqrqbikix.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.xuanzx.com/Article/details/gtcflxofzf.html

[U65] PHP：会话
来源：http://dali.iojbl.cn/Article/details/gtiomchtcz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gtosfbncwr.html

[U66] PHP：设置 Cookie
来源：http://dali.quarkkingdee.top/Article/details/gtqjbtyjhi.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.mhx1999.top/Article/details/gtdxdulfoc.html

[U67] PHP：处理文件上传
来源：http://dali.ybcxt.top/Article/details/gtjqijgxtk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.pengpengdd.cyou/Article/details/gtsxpdajqo.html

[U68] PHP：PDO 连接
来源：http://dali.sysykeji.top/Article/details/gtuednzkra.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.gaohongyu789.top/Article/details/gthdvigiak.html

[U69] PHP：PDO 预处理
来源：http://dali.chenzaomai.com/Article/details/gtzijgypgk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.vqdsnc.cn/Article/details/gtfcoetorf.html

[U70] PHP：PDO 事务
来源：http://dali.xuetiantiany.cn/Article/details/gtkmuzvljt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ybcxt.top/Article/details/gttjlrspuo.html

[U71] PHP：抛出异常
来源：http://dali.svipenyu.cn/Article/details/gtflomhjyg.html

throw new RuntimeException("失败", 500);
来源：http://dali.cheryme.top/Article/details/gtnenaestp.html

[U72] PHP：写错误日志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzfhaheac.html

error_log("失败: " . $e->getMessage());
来源：http://dali.316326.xyz/Article/details/gtlklnqjhb.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhongyouzk.top/Article/details/gtwpkksehj.html

parse_ini_file("config.ini", true)
来源：http://dali.ppjwa.cn/Article/details/gtmchueqkh.html

[U74] PHP：读取环境变量
来源：http://dali.jyoumei.cn/Article/details/gtdulyitpq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jinqigufen.top/Article/details/gtlxvszgqu.html

[U75] PHP：依赖注入
来源：http://dali.quarkkingdee.top/Article/details/gtoansndyv.html

composer require psr/container
来源：http://dali.zdqjudy.top/Article/details/gtsccigeii.html

[U76] PHP：简单路由
来源：http://dali.iojbl.cn/Article/details/gtgedeucwa.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yanxiufei.cn/Article/details/gtzcgcmmnh.html

[U77] PHP：模板渲染
来源：http://dali.xuetiantiany.cn/Article/details/gtnzqmmjkm.html

composer require twig/twig
来源：http://dali.iojbl.cn/Article/details/gtomkhermq.html

[U78] PHP：单元测试
来源：http://dali.jinghuilouyu.cn/Article/details/gtgxczhetj.html

composer require --dev phpunit/phpunit
来源：http://dali.yanxiufei.cn/Article/details/gtsrgdpokp.html

[U79] PHP：静态分析
来源：http://dali.jinghuilouyu.cn/Article/details/gtlvhxqmpi.html

composer require --dev phpstan/phpstan
来源：http://dali.birdmap.top/Article/details/gtuxhxiugr.html

[U80] PHP：代码规范修复
来源：http://dali.tian-w.cn/Article/details/gtqkxvxvtf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.nanxinkj.top/Article/details/gtddycrklh.html

[U81] JS：初始化项目
来源：http://dali.ehwqpu.com/Article/details/gthzguumkr.html

npm init -y;  npm i express
来源：http://dali.jlsjyb.cn/Article/details/gtbelvyihy.html

[U82] JS：package.json 脚本
来源：http://dali.jinyuanbaomall.cn/Article/details/gtubybnepx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.xinyue.icu/Article/details/gtyhgvlfbz.html

[U83] JS：ES Module 导入导出
来源：http://dali.svipenyu.cn/Article/details/gtrkrhobff.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.0kj1m.cn/Article/details/gtbnahkiyo.html

[U84] JS：CommonJS 写法
来源：http://dali.guannengcc.top/Article/details/gthbuuwval.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cucudq.cn/Article/details/gtksgnztaw.html

[U85] JS：可选链
来源：http://dali.zhiwuduotai.top/Article/details/gtwjkelxtu.html

a?.b?.c
来源：http://dali.bjfxy.top/Article/details/gteggamrop.html

[U86] JS：空值合并
来源：http://dali.mhx1999.top/Article/details/gttqvfcwlb.html

a ?? b
来源：http://dali.sufxvd.cn/Article/details/gtuktomeim.html

[U87] JS：解构默认值
来源：http://dali.cashguo.top/Article/details/gtadxdzcce.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yj20258.top/Article/details/gtcywpaaum.html

[U88] JS：对象展开合并
来源：http://dali.snrcjt.cn/Article/details/gthbaifrhz.html

{ ...a, ...b }
来源：http://dali.daxiang520.top/Article/details/gtzjkfgzgj.html

[U89] JS：数组去重
来源：http://dali.yonumen.top/Article/details/gtmcumaeuw.html

[...new Set(arr)]
来源：http://dali.shanyushiyangtech.top/Article/details/gtcqpcgwlr.html

[U90] JS：数字数组排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlywsywpk.html

[...arr].sort((a, b) => a - b)
来源：http://dali.snrcjt.cn/Article/details/gtwvbamqap.html

[U91] JS：对象键值遍历
来源：http://dali.9152youxi.cn/Article/details/gtfoeyigvg.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.havefunace.top/Article/details/gtgkbqkzmq.html

[U92] JS：深拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gtsqsedlgq.html

structuredClone(obj)
来源：http://dali.ppjwa.cn/Article/details/gtgejcfgmb.html

[U93] JS：模板字符串
来源：http://dali.kuanghao11.cn/Article/details/gtzfnugzkn.html

`共 ${n} 条`
来源：http://dali.yj202588.top/Article/details/gttodxyzoi.html

[U94] JS：箭头函数
来源：http://dali.cheryme.top/Article/details/gttmhckcxr.html

const double = x => x * 2;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpvmyahff.html

[U95] JS：Promise 包装
来源：http://dali.iojbl.cn/Article/details/gtrxiflgxe.html

new Promise((resolve, reject) => {})
来源：http://dali.zhongyouzk.top/Article/details/gtqpwdobwe.html

[U96] JS：async/await 与异常
来源：http://dali.pengpengdd.cyou/Article/details/gtbdhqypxi.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.vqdsnc.cn/Article/details/gttgifgeli.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gtrtifkraj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkjqmljzn.html

[U98] JS：fetch 带 JSON
来源：http://dali.tian-w.cn/Article/details/gtttbxkarf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.c1oappe.top/Article/details/gtxhwfrnfp.html

[U99] JS：事件监听
来源：http://dali.ydzc1.top/Article/details/gtlkiyqmda.html

el.addEventListener("click", e => {})
来源：http://dali.fzhhl.top/Article/details/gtefpnxfqq.html

[U100] JS：DOM 查询
来源：http://dali.feifeiyinyue.top/Article/details/gtnfggkeuw.html

document.querySelector(".item")
来源：http://dali.c1oappe.top/Article/details/gtcijexmac.html

[U101] JS：classList 操作
来源：http://dali.zycfv.cn/Article/details/gtmrvvnpuh.html

el.classList.toggle("active")
来源：http://dali.yongpay.top/Article/details/gtaycsokoj.html

[U102] JS：本地存储
来源：http://dali.sweek.top/Article/details/gtpcdzbmar.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hnxiangtu.top/Article/details/gtbdbrjvth.html

[U103] JS：定时器
来源：http://dali.shuidangran.top/Article/details/gthdmzcvzg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.mhx1999.top/Article/details/gtymjmdjgr.html

[U104] JS：防抖
来源：http://dali.jlsjyb.cn/Article/details/gtadhdkjzj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmctwlweg.html

[U105] JS：节流
来源：http://dali.xuanzx.com/Article/details/gtysgthwlu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ybcxt.top/Article/details/gtbgwvnssj.html

[U106] JS：日期格式化
来源：http://dali.jlsjyb.cn/Article/details/gtgvjdjayq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdlorvcih.html

[U107] JS：数字千分位
来源：http://dali.zdqjudy.top/Article/details/gtwpcrqxzk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yongpay.top/Article/details/gtdbfhiuxh.html

[U108] JS：随机整数
来源：http://dali.birdmap.top/Article/details/gthhnuspwg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jqgufenzy.top/Article/details/gtapfsmwwz.html

[U109] JS：数组分组
来源：http://dali.yuxming.cn/Article/details/gtckwwmtub.html

Object.groupBy(arr, x => x.type)
来源：http://dali.quarkkingdee.top/Article/details/gtpkicpjfs.html

[U110] JS：数组分块
来源：http://dali.ydzc1.top/Article/details/gtxjntxfxh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.pycfn.com/Article/details/gtowkwjhsv.html

[U111] JS：对象转 Map
来源：http://dali.hnxiangtu.top/Article/details/gthpbksdup.html

new Map(Object.entries(obj))
来源：http://dali.yueranfly.top/Article/details/gtmhzpethr.html

[U112] JS：字符串补位
来源：http://dali.kuanghao11.cn/Article/details/gttkwfcmkl.html

"7".padStart(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gtnypsogml.html

[U113] JS：正则替换全部
来源：http://dali.zhixingplan.top/Article/details/gtwatxpwcd.html

s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtcqyfhowc.html

[U114] JS：JSON 深比较
来源：http://dali.jinghuilouyu.cn/Article/details/gttiowddns.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zdqjudy.top/Article/details/gtakqhjevo.html

[U115] JS：生成 UUID
来源：http://dali.hfpthk.cn/Article/details/gtzoneirhq.html

crypto.randomUUID()
来源：http://dali.aibaodan.cn/Article/details/gtnoawmeuc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.wangshuangyany.cn/Article/details/gtdpmqggnl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.gotoacloud.top/Article/details/gtnxbpxvcd.html

[U117] JS：单元测试
来源：http://dali.vqdsnc.cn/Article/details/gtgxfxzudm.html

npm i -D vitest;  npx vitest
来源：http://dali.hysaishi.cn/Article/details/gtqrilgpcu.html

[U118] JS：开发服务器
来源：http://dali.wangdashe.top/Article/details/gtroejqyaa.html

npm i -D vite;  npx vite
来源：http://dali.chenlongwang.top/Article/details/gtmltsdpsh.html

[U119] JS：生产构建
来源：http://dali.shzxlz.cn/Article/details/gtqaetezqf.html

npx vite build
来源：http://dali.cashguo.top/Article/details/gtquktyhtn.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.gzhubu.top/Article/details/gtbzhpfvwq.html

import.meta.env.VITE_API_URL
来源：http://dali.feifeiyinyue.top/Article/details/gtpvzdxrew.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtorqnlvli.html

统计汇总
来源：http://dali.jyoumei.cn/Article/details/gtwaxsfavm.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtfbutcbiq.html

按语言统计（条）：
来源：http://dali.jlsjyb.cn/Article/details/gtbjajdfwx.html

Python ......... 252
来源：http://dali.guowangkeji.top/Article/details/gtmbhxoogd.html

PHP ............ 252
来源：http://dali.daria6918.cn/Article/details/gtdmbtvshf.html

JavaScript ..... 252
来源：http://dali.ppjwa.cn/Article/details/gtxctxwccd.html

TypeScript ..... 212
来源：http://dali.bjfxy.top/Article/details/gteyhslpcj.html

Java ........... 212
来源：http://dali.yonumen.top/Article/details/gtbegapbny.html

Go ............. 212
来源：http://dali.pengpengdd.cyou/Article/details/gtcwrsyrij.html

Ruby ........... 212
来源：http://dali.jinqigfzy.top/Article/details/gtqytxqeez.html

C# ............. 212
来源：http://dali.wangshuangyany.cn/Article/details/gteeenpjdn.html

C .............. 30
来源：http://dali.ywan-chungtsiang.top/Article/details/gthacgoegu.html

C++ ............ 30
来源：http://dali.yj20258888.top/Article/details/gtyfyjdqao.html

SQL ............ 90
来源：http://dali.pengpengdd.cyou/Article/details/gtcvbimfhx.html

Bash ........... 80
来源：http://dali.yj20258.top/Article/details/gtpucqlsdi.html

Kotlin ......... 15
来源：http://dali.tian-w.cn/Article/details/gtjawxkagi.html

Swift .......... 15
来源：http://dali.yongpay.top/Article/details/gtuciehssk.html

Lua ............ 10
来源：http://dali.guowangkeji.top/Article/details/gtbbaxdpta.html

Perl ........... 10
来源：http://dali.andypj.xyz/Article/details/gtvchfkzfm.html

Scala .......... 10
来源：http://dali.yvedp.cn/Article/details/gtfmbqafhg.html

------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gtoyuiotba.html

合计 ........... 2106 条
来源：http://dali.haohaochexian.top/Article/details/gtjnqvgtne.html

按章节统计：
来源：http://dali.yj20258888.top/Article/details/gtofxawaeb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.9152youxi.cn/Article/details/gthqcgcqpq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.guowangkeji.top/Article/details/gtyfkebjgt.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.bjfxy.top/Article/details/gtrdgagzew.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.fzhhl.top/Article/details/gtyymozusc.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.smart0.xyz/Article/details/gtojpjnqhv.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.ydzc1.top/Article/details/gthaklqzuf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xuanzx.com/Article/details/gtzxnjuuuf.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jinghuilouyu.cn/Article/details/gteygivqqm.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangkeji.top/Article/details/gtarxbbiwo.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.nanxinkj.top/Article/details/gtoqtifaya.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.316326.xyz/Article/details/gtkuojzute.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.snrcjt.cn/Article/details/gtgdowmuma.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.daxiang520.top/Article/details/gtqnshmzwb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ehwqpu.com/Article/details/gthsebcfbd.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsyolzova.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.xuetiantiany.cn/Article/details/gtaheqbvpl.html

Q SQL 专题                              90
来源：http://dali.ehwqpu.com/Article/details/gtvpydbpkw.html

R Bash 专题                             80
来源：http://dali.gaohongyu789.top/Article/details/gtwdjlioea.html

S C / C++ 专题                          60
来源：http://dali.ybcxt.top/Article/details/gtgihlbjxb.html

T 其他语言补充                          60
来源：http://dali.yueranfly.top/Article/details/gtyfrfagtj.html

U 高频实用片段                         120
来源：http://dali.feifeiyinyue.top/Article/details/gtkulkmdgq.html

------------------------------------
来源：http://dali.chenjidiqi.icu/Article/details/gtkataxvaz.html

合计                                  2106 条
来源：http://dali.ybcxt.top/Article/details/gtcykvbhyo.html

--------------------------------------------------------------------------------
来源：http://dali.jqgfzy.top/Article/details/gttyczazum.html

使用提醒
来源：http://dali.cdnleiting.top/Article/details/gtxxhdtalp.html

--------------------------------------------------------------------------------
来源：http://dali.cdnleiting.top/Article/details/gtbxirlpwj.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.tanke756.top/Article/details/gtejkagynd.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.daxiang520.top/Article/details/gteywaloud.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yj20258.top/Article/details/gtvrjxkyqh.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jinqigufen.top/Article/details/gtpnemxykr.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yuanzhike.top/Article/details/gtpkcjckrz.html

—— 文件结束 ——
来源：http://dali.yangfankeji.com/Article/details/gtinzktgiv.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtyiekixie.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jianghu66.top/Article/details/gtluqjsgaz.html

Common Programming Examples Cheat Book
来源：http://dali.daria6918.cn/Article/details/gtzaiijroh.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtmssfwvqw.html

【收录内容】
来源：http://dali.hammf.cn/Article/details/gtngsnxtro.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.xziqi.cn/Article/details/gtpfdhdtil.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yuxming.cn/Article/details/gtwxqxnmqw.html

SQL · Bash · C · C++
来源：http://dali.hnqzz.top/Article/details/gtlshuzfqt.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyoalbogg.html

【使用说明】
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlchsetgb.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yj20258.top/Article/details/gtktkcttre.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jyoumei.cn/Article/details/gtmdolllpz.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.ehwqpu.com/Article/details/gtbxbwgovd.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsalnbnoq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.dianchejie.cn/Article/details/gtnrnekfoj.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.nanxinkj.top/Article/details/gtdlzwkytq.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.feifeiyinyue.top/Article/details/gthtseljgx.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.kuanghao11.cn/Article/details/gtfvgjwfzi.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.andypj.xyz/Article/details/gtvmaewmts.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.iojbl.cn/Article/details/gtvngkxbsx.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.316326.xyz/Article/details/gtscishmhx.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.hnqzz.top/Article/details/gtqabkovfx.html

【文件统计】
来源：http://dali.redwolf501.top/Article/details/gtzksfjytl.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yvedp.cn/Article/details/gtrchzljhu.html

--------------------------------------------------------------------------------
来源：http://dali.jinqigfzy.top/Article/details/gtgerplaik.html

目  录
来源：http://dali.ppjwa.cn/Article/details/gtkvrsdpap.html

--------------------------------------------------------------------------------
来源：http://dali.kuanghao11.cn/Article/details/gtlggzmcyz.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yuxming.cn/Article/details/gtglakjife.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hnxiangtu.top/Article/details/gtcsyqyduu.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.mhx1999.top/Article/details/gtagvoxxkm.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmxaejuer.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.daria6918.cn/Article/details/gtnvocagwn.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.wangdashe.top/Article/details/gtponzqbqp.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hysaishi.cn/Article/details/gtfnwgnfxi.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.tian-w.cn/Article/details/gtrrvascwz.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yuxming.cn/Article/details/gtktwlttgo.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.ivvv.top/Article/details/gtzemgonpa.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.chenzaomai.com/Article/details/gtlbneyzfj.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jyoumei.cn/Article/details/gtnnxlllbv.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtwumzwhva.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtbibroast.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yanxiufei.cn/Article/details/gtlxoetiut.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.xziqi.cn/Article/details/gtijbzoteh.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yueranfly.top/Article/details/gtztupkkmx.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.sxryk.cn/Article/details/gtgtdmoycu.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhengqikj.top/Article/details/gtawzylizh.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cashguo.top/Article/details/gtpvfoumsh.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.xziqi.cn/Article/details/gtooeufkkv.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtptpwdxkp.html

A. 基础语法与类型
来源：http://dali.cucudq.cn/Article/details/gtomshmovy.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtpostuftf.html

[A01] Hello World
来源：http://dali.nwbrower.top/Article/details/gtcwdcomge.html

Py:   print("Hello, World!")
来源：http://dali.yuxming.cn/Article/details/gtqpxqqqmv.html

PHP:  echo "Hello, World!";
来源：http://dali.zycfv.cn/Article/details/gtzzyzdotr.html

JS:   console.log("Hello, World!");
来源：http://dali.meibo888.top/Article/details/gtzzvxlomn.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.shangyingyoupin.top/Article/details/gtgcomplrx.html

Java: System.out.println("Hello, World!");
来源：http://dali.shuidangran.top/Article/details/gtjdnydmde.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jqgufenzy.top/Article/details/gtqhnjplem.html

Ruby: puts "Hello, World!"
来源：http://dali.vqdsnc.cn/Article/details/gtkukfgsyo.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.tanke756.top/Article/details/gtnkwwrzek.html

[A02] 变量声明与赋值
来源：http://dali.hammf.cn/Article/details/gtgjvydoyn.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ywan-chungtsiang.top/Article/details/gthzjrsjnu.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yueranfly.top/Article/details/gtdlykfcne.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjcqveltr.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.sweek.top/Article/details/gtrttkjuat.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.redwolf501.top/Article/details/gtxcxfyykj.html

Go:   name := "Alex"; age := 20
来源：http://dali.jinyuanbaomall.cn/Article/details/gteqbiwote.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhongyouzk.top/Article/details/gtpgxfyhdn.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.shangyingyoupin.top/Article/details/gtubnfbkud.html

[A03] 常量定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwrcwykz.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.andypj.xyz/Article/details/gtecgpxcsa.html

PHP:  const PI = 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gteaeaqgkc.html

JS:   const PI = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gtzutgscjc.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gtjvdpevzi.html

Java: static final double PI = 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gtrjffbzyn.html

Go:   const PI = 3.14159
来源：http://dali.jinqigfzy.top/Article/details/gtmvxbdguu.html

Ruby: PI = 3.14159
来源：http://dali.vqdsnc.cn/Article/details/gtceplrmnf.html

C#:   const double PI = 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gtfcaollzi.html

[A04] 判断变量类型
来源：http://dali.guowangkeji.top/Article/details/gtbxuznlhj.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.fengsongda.top/Article/details/gtzovhepcc.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yueranfly.top/Article/details/gtcozgjqfr.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.sysykeji.top/Article/details/gtdmskajbb.html

TS:   typeof x; x instanceof Date
来源：http://dali.jinqigfzy.top/Article/details/gtmphzjpsq.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yanxiufei.cn/Article/details/gtodbvosnp.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hnxiangtu.top/Article/details/gtjvdhmpww.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jqgfzy.top/Article/details/gthhivdipy.html

C#:   x.GetType().Name; x is int
来源：http://dali.cqqwz.cn/Article/details/gtjlutscba.html

[A05] 整数除法与取模
来源：http://dali.redwolf501.top/Article/details/gtgqismufj.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtloybhyla.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yvedp.cn/Article/details/gtlnryikmd.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.haohaochexian.top/Article/details/gtiszoofxj.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtrshduuok.html

Java: 7 / 2; 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gtsbjvligf.html

Go:   7 / 2; 7 % 2
来源：http://dali.ehwqpu.com/Article/details/gtttvidrwx.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.hysaishi.cn/Article/details/gtsbdikmva.html

C#:   7 / 2; 7 % 2
来源：http://dali.xziqi.cn/Article/details/gtbkoqahos.html

[A06] 字符串转数字
来源：http://dali.cucudq.cn/Article/details/gtzsedlhzj.html

Py:   int("42"); float("3.14")
来源：http://dali.havefunace.top/Article/details/gtoaqipfir.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.bjfxy.top/Article/details/gtkvbyxedf.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yangfankeji.com/Article/details/gtxmqtyvwb.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.yj20258.top/Article/details/gtephvmnrp.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.haohaochexian.top/Article/details/gtkuwmxems.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.hnqzz.top/Article/details/gtyxnktfnt.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.iojbl.cn/Article/details/gtciyqlvfz.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhiwuduotai.top/Article/details/gtkjzfkzgi.html

[A07] 数字转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnqpqwaoo.html

Py:   str(42)
来源：http://dali.tianlin.xyz/Article/details/gtsufajvbu.html

PHP:  (string) 42; strval(42)
来源：http://dali.cucudq.cn/Article/details/gtkbmcvbyu.html

JS:   String(42); (42).toString()
来源：http://dali.shzxlz.cn/Article/details/gtpvndnevi.html

TS:   String(42)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbpdatez.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.shanyushiyangtech.top/Article/details/gtclvrovxf.html

Go:   strconv.Itoa(42)
来源：http://dali.316326.xyz/Article/details/gtommfgepa.html

Ruby: 42.to_s
来源：http://dali.aizwys.cn/Article/details/gtmltfcemm.html

C#:   42.ToString()
来源：http://dali.hongshengwenyu.top/Article/details/gtldxdauhk.html

[A08] 取整与四舍五入
来源：http://dali.ivvv.top/Article/details/gtepfjivqc.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.0kj1m.cn/Article/details/gtdldxaoit.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zycfv.cn/Article/details/gtinkvycbj.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.pengpengdd.cyou/Article/details/gtbfryobgc.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmrdwhhyu.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.chenjidiqi.icu/Article/details/gtmifrngdx.html


<!-- 参考信息 -->