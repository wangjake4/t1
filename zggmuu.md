代发 wailian999

[U53] PHP：空合并运算符
来源：http://dali.shzxlz.cn/Article/details/gtwqujbwdy.html

$v = $a ?? $b ?? "default";
来源：http://dali.aibaodan.cn/Article/details/gtzkhoktaj.html

[U54] PHP：空安全调用
来源：http://dali.nanxinkj.top/Article/details/gtyukbpoqj.html

$obj?->method()
来源：http://dali.yuxming.cn/Article/details/gtoftsfotb.html

[U55] PHP：match 表达式
来源：http://dali.yongpay.top/Article/details/gtjxmurpsa.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jqgufenzy.top/Article/details/gtaojfcbia.html

[U56] PHP：命名参数
来源：http://dali.jianghu66.top/Article/details/gtpvgzghst.html

f(a: 1, b: 2)
来源：http://dali.shangyingyoupin.top/Article/details/gthywtotzc.html

[U57] PHP：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gtrvkvxsgb.html

"值: {$a}"
来源：http://dali.ydzc1.top/Article/details/gtfxqhoyiv.html

[U58] PHP：数组三件套
来源：http://dali.hywenlv.cn/Article/details/gtymjzlrfr.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.gaohongyu789.top/Article/details/gtkdlpmlsj.html

[U59] PHP：自定义排序
来源：http://dali.yuanzhike.top/Article/details/gtskfxontu.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cashguo.top/Article/details/gtemweqvsq.html

[U60] PHP：JSON 编解码
来源：http://dali.ppjwa.cn/Article/details/gtgftudret.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.dashuyun.cn/Article/details/gtcunusdzx.html

[U61] PHP：正则
来源：http://dali.wangdashe.top/Article/details/gtfegtwdud.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj202588.top/Article/details/gtuwjfgckd.html

[U62] PHP：日期对象
来源：http://dali.guowangkeji.top/Article/details/gtgiimehkd.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.cdnleiting.top/Article/details/gtsgeiismv.html

[U63] PHP：文件读写
来源：http://dali.tanke756.top/Article/details/gtkxwwmjwi.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.aizwys.cn/Article/details/gtjwbnlirl.html

[U64] PHP：目录遍历
来源：http://dali.yanxiufei.cn/Article/details/gtdcbduunz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.bjfxy.top/Article/details/gtnzqmvfjs.html

[U65] PHP：会话
来源：http://dali.sufxvd.cn/Article/details/gtlqlybtao.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.mhx1999.top/Article/details/gtexvfqkmw.html

[U66] PHP：设置 Cookie
来源：http://dali.fzhhl.top/Article/details/gtwkvhfjfk.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhixingplan.top/Article/details/gteamtjwem.html

[U67] PHP：处理文件上传
来源：http://dali.xuetiantiany.cn/Article/details/gtayfqkcwy.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yuanzhike.top/Article/details/gtntfmkdlw.html

[U68] PHP：PDO 连接
来源：http://dali.svipenyu.cn/Article/details/gtumdvolrz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yueranfly.top/Article/details/gtvhjotyic.html

[U69] PHP：PDO 预处理
来源：http://dali.dianchejie.cn/Article/details/gtvijshnpc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthjssmznn.html

[U70] PHP：PDO 事务
来源：http://dali.ppjwa.cn/Article/details/gtioiwtqjh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hnxiangtu.top/Article/details/gtmcmaxaxo.html

[U71] PHP：抛出异常
来源：http://dali.pengpengdd.cyou/Article/details/gtvbmtbfoi.html

throw new RuntimeException("失败", 500);
来源：http://dali.birdmap.top/Article/details/gtrhqwjnnm.html

[U72] PHP：写错误日志
来源：http://dali.pengpengdd.cyou/Article/details/gtohbwrhfn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ydzc1.top/Article/details/gtrisxivoy.html

[U73] PHP：读取 ini 配置
来源：http://dali.aizwys.cn/Article/details/gtulphiuir.html

parse_ini_file("config.ini", true)
来源：http://dali.andypj.xyz/Article/details/gtuiecoqza.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gtvszifmsk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yuxming.cn/Article/details/gtcvyfbgov.html

[U75] PHP：依赖注入
来源：http://dali.smart0.xyz/Article/details/gtvkdhmyfs.html

composer require psr/container
来源：http://dali.sweek.top/Article/details/gtbzgqyxjh.html

[U76] PHP：简单路由
来源：http://dali.jlsjyb.cn/Article/details/gtmhktqyfa.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.ehwqpu.com/Article/details/gtpwwstyvp.html

[U77] PHP：模板渲染
来源：http://dali.yongpay.top/Article/details/gtyucxgqae.html

composer require twig/twig
来源：http://dali.dianchejie.cn/Article/details/gttoeolvcu.html

[U78] PHP：单元测试
来源：http://dali.yanxiufei.cn/Article/details/gtgqdqsoyj.html

composer require --dev phpunit/phpunit
来源：http://dali.tianlin.xyz/Article/details/gtdcorbuwj.html

[U79] PHP：静态分析
来源：http://dali.zycfv.cn/Article/details/gtioahtrsc.html

composer require --dev phpstan/phpstan
来源：http://dali.svipenyu.cn/Article/details/gtlgcfvrkv.html

[U80] PHP：代码规范修复
来源：http://dali.havefunace.top/Article/details/gtosmckrsv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.guowangkeji.top/Article/details/gtxuefmaut.html

[U81] JS：初始化项目
来源：http://dali.haohaochexian.top/Article/details/gtffsexjop.html

npm init -y;  npm i express
来源：http://dali.jiagoushi.top/Article/details/gtgmqnnsxw.html

[U82] JS：package.json 脚本
来源：http://dali.dashuyun.cn/Article/details/gtfaqamtxx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.shangyingyoupin.top/Article/details/gtpuujkrfu.html

[U83] JS：ES Module 导入导出
来源：http://dali.ydzc1.top/Article/details/gtsayteabn.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.birdmap.top/Article/details/gtogydxxjv.html

[U84] JS：CommonJS 写法
来源：http://dali.jianghu66.top/Article/details/gtxhwrelgr.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdznzvbwe.html

[U85] JS：可选链
来源：http://dali.gogol.net.cn/Article/details/gtzbduthui.html

a?.b?.c
来源：http://dali.hammf.cn/Article/details/gtnfzqglch.html

[U86] JS：空值合并
来源：http://dali.shuidangran.top/Article/details/gtmfjukqfo.html

a ?? b
来源：http://dali.yuanzhike.top/Article/details/gtbpjlagau.html

[U87] JS：解构默认值
来源：http://dali.haohaochexian.top/Article/details/gtomkxvlwg.html

const { a = 1, b = 2 } = obj;
来源：http://dali.xinyue.icu/Article/details/gtwhzhiqhn.html

[U88] JS：对象展开合并
来源：http://dali.jyoumei.cn/Article/details/gtjvarcpjk.html

{ ...a, ...b }
来源：http://dali.shangyingyoupin.top/Article/details/gtiwzpogug.html

[U89] JS：数组去重
来源：http://dali.shanyushiyangkeji.top/Article/details/gtctjqyzlo.html

[...new Set(arr)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtszaqwdtt.html

[U90] JS：数字数组排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtdaauwecz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gtyryfstme.html

[U91] JS：对象键值遍历
来源：http://dali.tian-w.cn/Article/details/gtuopfsikd.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.andypj.xyz/Article/details/gttilpqewl.html

[U92] JS：深拷贝
来源：http://dali.jyoumei.cn/Article/details/gtkpqzobms.html

structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gttdldslde.html

[U93] JS：模板字符串
来源：http://dali.xylfe.cn/Article/details/gtqpfyllqq.html

`共 ${n} 条`
来源：http://dali.jlsjyb.cn/Article/details/gtepdgucbf.html

[U94] JS：箭头函数
来源：http://dali.pycfn.com/Article/details/gttalgdisw.html

const double = x => x * 2;
来源：http://dali.pengpengdd.cyou/Article/details/gtqqnfkwvh.html

[U95] JS：Promise 包装
来源：http://dali.hywenlv.cn/Article/details/gtumsbkudf.html

new Promise((resolve, reject) => {})
来源：http://dali.fengsongda.top/Article/details/gtjdoslaxb.html

[U96] JS：async/await 与异常
来源：http://dali.chenlongwang.top/Article/details/gthozugsou.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.0kj1m.cn/Article/details/gtixwsfujs.html

[U97] JS：并发请求
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtonwxpyus.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gtskdvxktf.html

[U98] JS：fetch 带 JSON
来源：http://dali.pycfn.com/Article/details/gtszwwnkmz.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yvedp.cn/Article/details/gtpcllxxqf.html

[U99] JS：事件监听
来源：http://dali.aizwys.cn/Article/details/gtaxetpupt.html

el.addEventListener("click", e => {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtufixzref.html

[U100] JS：DOM 查询
来源：http://dali.zhongyouzk.top/Article/details/gtlhsgvqtc.html

document.querySelector(".item")
来源：http://dali.dashuyun.cn/Article/details/gtozmefgdr.html

[U101] JS：classList 操作
来源：http://dali.quarkkingdee.top/Article/details/gtrdnkpokz.html

el.classList.toggle("active")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdlkyurmt.html

[U102] JS：本地存储
来源：http://dali.haohaochexian.top/Article/details/gtdomxdnxs.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.wangshuangyany.cn/Article/details/gtoevjyrpe.html

[U103] JS：定时器
来源：http://dali.gzhubu.top/Article/details/gtjflugokg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ydzc1.top/Article/details/gtzvcqwkje.html

[U104] JS：防抖
来源：http://dali.cucudq.cn/Article/details/gterhmqftu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuetiantiany.cn/Article/details/gtlunmhoua.html

[U105] JS：节流
来源：http://dali.snrcjt.cn/Article/details/gtdwqurhdz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hfpthk.cn/Article/details/gtogwqptov.html

[U106] JS：日期格式化
来源：http://dali.zycfv.cn/Article/details/gtxfbmcgts.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.quarkkingdee.top/Article/details/gtrrddirzp.html

[U107] JS：数字千分位
来源：http://dali.iojbl.cn/Article/details/gtwzhabhev.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.nwbrower.top/Article/details/gtireunzlz.html

[U108] JS：随机整数
来源：http://dali.birdmap.top/Article/details/gtmhorrbtv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jinyuanbaomall.cn/Article/details/gtubumaiox.html

[U109] JS：数组分组
来源：http://dali.yvedp.cn/Article/details/gthpbbwspe.html

Object.groupBy(arr, x => x.type)
来源：http://dali.cqqwz.cn/Article/details/gtsnpntfhb.html

[U110] JS：数组分块
来源：http://dali.yuanzhike.top/Article/details/gtvrndaiud.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.meibo888.top/Article/details/gtcfufofbo.html

[U111] JS：对象转 Map
来源：http://dali.cucudq.cn/Article/details/gtmuozdwqu.html

new Map(Object.entries(obj))
来源：http://dali.zhengqikj.top/Article/details/gtuipswxtz.html

[U112] JS：字符串补位
来源：http://dali.tianlin.xyz/Article/details/gtuhiqnavp.html

"7".padStart(3, "0")
来源：http://dali.jyoumei.cn/Article/details/gtuwfqadxk.html

[U113] JS：正则替换全部
来源：http://dali.cdnleiting.top/Article/details/gtevlnsbyj.html

s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtldsisblw.html

[U114] JS：JSON 深比较
来源：http://dali.xziqi.cn/Article/details/gtsllhzygl.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtyzmbspou.html

[U115] JS：生成 UUID
来源：http://dali.cucudq.cn/Article/details/gtbizcmiqn.html

crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gtsypqcady.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jinqigfzy.top/Article/details/gttieqpqjs.html

/** @param {string} name */ function f(name) {}
来源：http://dali.daria6918.cn/Article/details/gtigwcysuc.html

[U117] JS：单元测试
来源：http://dali.sxryk.cn/Article/details/gttxkgpdss.html

npm i -D vitest;  npx vitest
来源：http://dali.shzxlz.cn/Article/details/gtnmcmayay.html

[U118] JS：开发服务器
来源：http://dali.shanyushiyangtech.top/Article/details/gtvalogxdh.html

npm i -D vite;  npx vite
来源：http://dali.yonumen.top/Article/details/gtvxgvwbtg.html

[U119] JS：生产构建
来源：http://dali.kuanghao11.cn/Article/details/gtlgtpmlml.html

npx vite build
来源：http://dali.zycfv.cn/Article/details/gtdauqrzll.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.guowangkeji.top/Article/details/gtldefaosb.html

import.meta.env.VITE_API_URL
来源：http://dali.xinyue.icu/Article/details/gtgwvmuuva.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtsdywofpb.html

统计汇总
来源：http://dali.jlsjyb.cn/Article/details/gtxbqnqpgu.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtquwuqdpn.html

按语言统计（条）：
来源：http://dali.zdqjudy.top/Article/details/gtohyyxypt.html

Python ......... 252
来源：http://dali.cqqwz.cn/Article/details/gtumwelipt.html

PHP ............ 252
来源：http://dali.tianlin.xyz/Article/details/gtmiktzbzj.html

JavaScript ..... 252
来源：http://dali.dianchejie.cn/Article/details/gtykyzbzky.html

TypeScript ..... 212
来源：http://dali.yanxiufei.cn/Article/details/gtuhdmcgzr.html

Java ........... 212
来源：http://dali.zhengqikj.top/Article/details/gtwfarjzpc.html

Go ............. 212
来源：http://dali.yj20258.top/Article/details/gtrcpzmczl.html

Ruby ........... 212
来源：http://dali.yanxiufei.cn/Article/details/gtxoeaimri.html

C# ............. 212
来源：http://dali.jqgfzy.top/Article/details/gtnzzdjrum.html

C .............. 30
来源：http://dali.dianchejie.cn/Article/details/gtlzoouqea.html

C++ ............ 30
来源：http://dali.xylfe.cn/Article/details/gtzbzrfskq.html

SQL ............ 90
来源：http://dali.nwbrower.top/Article/details/gteumkmnqx.html

Bash ........... 80
来源：http://dali.aizwys.cn/Article/details/gtfvtdztfx.html

Kotlin ......... 15
来源：http://dali.c1oappe.top/Article/details/gtlmsazvdl.html

Swift .......... 15
来源：http://dali.hfpthk.cn/Article/details/gtlyovnkju.html

Lua ............ 10
来源：http://dali.kuanghao11.cn/Article/details/gtxfyiofub.html

Perl ........... 10
来源：http://dali.hnxiangtu.top/Article/details/gttkwdtwfe.html

Scala .......... 10
来源：http://dali.xuanzx.com/Article/details/gtzwsbwacr.html

------------------------------------
来源：http://dali.andypj.xyz/Article/details/gtajfaxxui.html

合计 ........... 2106 条
来源：http://dali.sysykeji.top/Article/details/gtgdqofdzy.html

按章节统计：
来源：http://dali.havefunace.top/Article/details/gtkjecbcvu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.c1oappe.top/Article/details/gtkqekbxob.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hysaishi.cn/Article/details/gthuyqiknw.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.kuanghao11.cn/Article/details/gtagaoqvhb.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqqunvazs.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.fengsongda.top/Article/details/gtdfawcrab.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.pycfn.com/Article/details/gtmiwutkru.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnrrizhwo.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.aibaodan.cn/Article/details/gtliitpiyw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.haohaochexian.top/Article/details/gtdwfnriid.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.hongshengwenyu.top/Article/details/gtuaacevih.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.fengsongda.top/Article/details/gthyjapfem.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.snrcjt.cn/Article/details/gtfapllmbz.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.xylfe.cn/Article/details/gtndfuxxct.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yuanzhike.top/Article/details/gtwjnqfgrd.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.aizwys.cn/Article/details/gtbkdlijwq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gtjpidcuwo.html

Q SQL 专题                              90
来源：http://dali.mhx1999.top/Article/details/gtipgyogkh.html

R Bash 专题                             80
来源：http://dali.daria6918.cn/Article/details/gtkxrqnybo.html

S C / C++ 专题                          60
来源：http://dali.yj202588.top/Article/details/gtvrieuvzo.html

T 其他语言补充                          60
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyyenmzmc.html

U 高频实用片段                         120
来源：http://dali.ywan-chungtsiang.top/Article/details/gteuebwfrs.html

------------------------------------
来源：http://dali.xinyue.icu/Article/details/gthqjsrhio.html

合计                                  2106 条
来源：http://dali.zhiwuduotai.top/Article/details/gtzmidgdpk.html

--------------------------------------------------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gtjrymxauo.html

使用提醒
来源：http://dali.hammf.cn/Article/details/gtabshtbbs.html

--------------------------------------------------------------------------------
来源：http://dali.hysaishi.cn/Article/details/gtwntmkcne.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhoulong.xyz/Article/details/gtvlfpefjv.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.vqdsnc.cn/Article/details/gtsleihywh.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.mhx1999.top/Article/details/gttndjsjhv.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.andypj.xyz/Article/details/gtzwftxhfe.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.tanke756.top/Article/details/gtocaytrke.html

—— 文件结束 ——
来源：http://dali.chenlongwang.top/Article/details/gtcojagcmb.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtbytgxwbc.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.tianlin.xyz/Article/details/gtctpdgpxp.html

Common Programming Examples Cheat Book
来源：http://dali.xuetiantiany.cn/Article/details/gtytxjqmtk.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtsmlyxkbr.html

【收录内容】
来源：http://dali.hammf.cn/Article/details/gttsvoifpm.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdiwoteux.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.gaohongyu789.top/Article/details/gtpqycfuuc.html

SQL · Bash · C · C++
来源：http://dali.yongpay.top/Article/details/gtuufnudfu.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.guannengcc.top/Article/details/gthmxsbtfg.html

【使用说明】
来源：http://dali.haohaochexian.top/Article/details/gtygdgzyzs.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.meibo888.top/Article/details/gtfokgylce.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.mhx1999.top/Article/details/gtecbbgmhl.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.sufxvd.cn/Article/details/gtdpropted.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yvedp.cn/Article/details/gtcwijqveu.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xuetiantiany.cn/Article/details/gtwgxkxcgl.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.nanxinkj.top/Article/details/gtwctmzaoj.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jiagoushi.top/Article/details/gtecghedoj.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yuanzhike.top/Article/details/gtjfoftnaf.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jyoumei.cn/Article/details/gtuappipmy.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.shzxlz.cn/Article/details/gttzkqqrdh.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.smart0.xyz/Article/details/gtsqaoakyw.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.pycfn.com/Article/details/gtsapccksb.html

【文件统计】
来源：http://dali.chenjidiqi.icu/Article/details/gthiyoladn.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.haohaochexian.top/Article/details/gtgvouxomm.html

--------------------------------------------------------------------------------
来源：http://dali.guannengcc.top/Article/details/gtalyqlopb.html

目  录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkgxsqgsv.html

--------------------------------------------------------------------------------
来源：http://dali.daxiang520.top/Article/details/gtiwvlbkmo.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jinqigfzy.top/Article/details/gtrhxlzabt.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.cheryme.top/Article/details/gtyycaebfd.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.dianchejie.cn/Article/details/gtsumkhrja.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.nanxuanxn.top/Article/details/gtoblbnkbt.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.smart0.xyz/Article/details/gtwogdxupv.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.guowangkeji.top/Article/details/gtbsqlonoa.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yuxming.cn/Article/details/gtbotbccil.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.ivvv.top/Article/details/gtvjvkxrch.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtsdroocif.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yj20258.top/Article/details/gtonshagll.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.shuidangran.top/Article/details/gtkmqccmcp.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.aibaodan.cn/Article/details/gtmkxtbzlv.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.smart0.xyz/Article/details/gtgkaxvdas.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.xuanzx.com/Article/details/gtxpnnuupf.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.sysykeji.top/Article/details/gtowuhzyak.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jiagoushi.top/Article/details/gtxzewnthz.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.cheryme.top/Article/details/gtlmonzlut.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtefkrpshn.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.iojbl.cn/Article/details/gtapogiaax.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.quarkkingdee.top/Article/details/gtxqauxhkq.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.haohaochexian.top/Article/details/gtkjjwsoud.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtqrkznmgj.html

A. 基础语法与类型
来源：http://dali.zhoulong.xyz/Article/details/gtiaxxgexr.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtrgmasbor.html

[A01] Hello World
来源：http://dali.shuidangran.top/Article/details/gtdrilodim.html

Py:   print("Hello, World!")
来源：http://dali.ppjwa.cn/Article/details/gtdscblgqh.html

PHP:  echo "Hello, World!";
来源：http://dali.hammf.cn/Article/details/gtrhcpfgra.html

JS:   console.log("Hello, World!");
来源：http://dali.yj20258888.top/Article/details/gtuqswioaz.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.smart0.xyz/Article/details/gtdiyiazwk.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhoulong.xyz/Article/details/gtmfqxxahn.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jqgufenzy.top/Article/details/gtijdqnfoe.html

Ruby: puts "Hello, World!"
来源：http://dali.yvedp.cn/Article/details/gtsrccdndb.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.gotoacloud.top/Article/details/gtdwchmkam.html

[A02] 变量声明与赋值
来源：http://dali.aibaodan.cn/Article/details/gtvigvjgiv.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.shzxlz.cn/Article/details/gtdtllmkbw.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhixingplan.top/Article/details/gtlveqlpsr.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.pycfn.com/Article/details/gtrbolckyr.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yangfankeji.com/Article/details/gtnykjawzc.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jinqigfzy.top/Article/details/gtwogriftt.html

Go:   name := "Alex"; age := 20
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmbyxjwhj.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhongyouzk.top/Article/details/gthbfawalt.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.nwbrower.top/Article/details/gtavfiscya.html

[A03] 常量定义
来源：http://dali.hammf.cn/Article/details/gtvpnlmjpl.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jlsjyb.cn/Article/details/gtfqpstbzi.html

PHP:  const PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gtnyxzkwks.html

JS:   const PI = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gteqrrjpnm.html

TS:   const PI: number = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gtmdzekzfh.html

Java: static final double PI = 3.14159;
来源：http://dali.cheryme.top/Article/details/gttzvagpnz.html

Go:   const PI = 3.14159
来源：http://dali.vqdsnc.cn/Article/details/gtzrxysvef.html

Ruby: PI = 3.14159
来源：http://dali.9152youxi.cn/Article/details/gtoekunyyd.html

C#:   const double PI = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gtqnojljnw.html

[A04] 判断变量类型
来源：http://dali.cqqwz.cn/Article/details/gtpnogengw.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.chenzaomai.com/Article/details/gtozsmztsx.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.gogol.net.cn/Article/details/gtideclwpk.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.daxiang520.top/Article/details/gtsthtpyxx.html

TS:   typeof x; x instanceof Date
来源：http://dali.chenzaomai.com/Article/details/gtnxrjltnf.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtprablsbj.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.xuanzx.com/Article/details/gtqkioirhu.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.wangshuangyany.cn/Article/details/gtnusaabiz.html

C#:   x.GetType().Name; x is int
来源：http://dali.xuanzx.com/Article/details/gtbihzpijt.html

[A05] 整数除法与取模
来源：http://dali.yuxming.cn/Article/details/gtwwlgbnup.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jqgfzy.top/Article/details/gtvabqyfcj.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.gotoacloud.top/Article/details/gtvyipfpyg.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hywenlv.cn/Article/details/gthwdetjfp.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.vqdsnc.cn/Article/details/gtflkikrwc.html

Java: 7 / 2; 7 % 2
来源：http://dali.jiagoushi.top/Article/details/gtnaufbkta.html

Go:   7 / 2; 7 % 2
来源：http://dali.xylfe.cn/Article/details/gtpucjcgru.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.xuanzx.com/Article/details/gtmomyixdv.html

C#:   7 / 2; 7 % 2
来源：http://dali.jyoumei.cn/Article/details/gtbclwxefy.html

[A06] 字符串转数字
来源：http://dali.aizwys.cn/Article/details/gtfmkftnnc.html

Py:   int("42"); float("3.14")
来源：http://dali.hongshengwenyu.top/Article/details/gtgrwqrlzc.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.cucudq.cn/Article/details/gtbsppaodb.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jianghu66.top/Article/details/gtfgsxvtqx.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.guowangkeji.top/Article/details/gtwdxnanhp.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.nanxinkj.top/Article/details/gtadmndxrf.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jianghu66.top/Article/details/gtbulmngav.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.quarkkingdee.top/Article/details/gtxxasdvko.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.aizwys.cn/Article/details/gtxebirwre.html

[A07] 数字转字符串
来源：http://dali.316326.xyz/Article/details/gtmgoqplkl.html

Py:   str(42)
来源：http://dali.jyoumei.cn/Article/details/gtdiyixljt.html

PHP:  (string) 42; strval(42)
来源：http://dali.pycfn.com/Article/details/gtgsfpvmgq.html


<!-- 参考信息 -->