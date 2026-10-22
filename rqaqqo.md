代发 wailian999

[U55] PHP：match 表达式
来源：http://dali.vqdsnc.cn/Article/details/gtwqrtyfgd.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.cheryme.top/Article/details/gtvhhaoygy.html

[U56] PHP：命名参数
来源：http://dali.dashuyun.cn/Article/details/gtonpburzn.html

f(a: 1, b: 2)
来源：http://dali.hnqzz.top/Article/details/gthlckiqda.html

[U57] PHP：字符串插值
来源：http://dali.yj20258.top/Article/details/gtiwrhudgo.html

"值: {$a}"
来源：http://dali.fzhhl.top/Article/details/gtheomxskb.html

[U58] PHP：数组三件套
来源：http://dali.316326.xyz/Article/details/gtccleyjhk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hfpthk.cn/Article/details/gtxoaoaspn.html

[U59] PHP：自定义排序
来源：http://dali.fengsongda.top/Article/details/gtdnsxirub.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aizwys.cn/Article/details/gtxiyrpqcv.html

[U60] PHP：JSON 编解码
来源：http://dali.yj20258888.top/Article/details/gtyjywbklo.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xinyue.icu/Article/details/gtdirrjszm.html

[U61] PHP：正则
来源：http://dali.jlsjyb.cn/Article/details/gtatoonsyr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtimovjaxw.html

[U62] PHP：日期对象
来源：http://dali.316326.xyz/Article/details/gttwxzikea.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.cdnleiting.top/Article/details/gtzxehqjsc.html

[U63] PHP：文件读写
来源：http://dali.nanxuanxn.top/Article/details/gtkeuenxdz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhiwuduotai.top/Article/details/gtwbgrgmzl.html

[U64] PHP：目录遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtvenqxkaj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yj202588.top/Article/details/gtpvyokvyk.html

[U65] PHP：会话
来源：http://dali.jqgufenzy.top/Article/details/gtttrnnbac.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtjuklhkzv.html

[U66] PHP：设置 Cookie
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnsqhhjbb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yonumen.top/Article/details/gtgagjqjdk.html

[U67] PHP：处理文件上传
来源：http://dali.pycfn.com/Article/details/gtqddlrqds.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.wangdashe.top/Article/details/gtvgqqhdio.html

[U68] PHP：PDO 连接
来源：http://dali.yuanzhike.top/Article/details/gtsuffrjhx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jinqigufen.top/Article/details/gtknedvmrf.html

[U69] PHP：PDO 预处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnnwpbum.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.tianlin.xyz/Article/details/gtzglhifpj.html

[U70] PHP：PDO 事务
来源：http://dali.ppjwa.cn/Article/details/gtpzisyipj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jyoumei.cn/Article/details/gtdlytwrri.html

[U71] PHP：抛出异常
来源：http://dali.316326.xyz/Article/details/gttuuqosxc.html

throw new RuntimeException("失败", 500);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwzirjugl.html

[U72] PHP：写错误日志
来源：http://dali.yanxiufei.cn/Article/details/gtguciaycp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.chenzaomai.com/Article/details/gtwftaluhl.html

[U73] PHP：读取 ini 配置
来源：http://dali.xuetiantiany.cn/Article/details/gtydrmfpyc.html

parse_ini_file("config.ini", true)
来源：http://dali.guowangkeji.top/Article/details/gtucfuwmaa.html

[U74] PHP：读取环境变量
来源：http://dali.bjfxy.top/Article/details/gttpkujssg.html

getenv("APP_ENV") ?: "production"
来源：http://dali.fengsongda.top/Article/details/gtfmjiagcw.html

[U75] PHP：依赖注入
来源：http://dali.guannengcc.top/Article/details/gtkkncqfqs.html

composer require psr/container
来源：http://dali.cdnleiting.top/Article/details/gtwbbgnile.html

[U76] PHP：简单路由
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyoleodlx.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.shangyingyoupin.top/Article/details/gtseugqmiw.html

[U77] PHP：模板渲染
来源：http://dali.aibaodan.cn/Article/details/gtxtfojukp.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gtlohsadjh.html

[U78] PHP：单元测试
来源：http://dali.svipenyu.cn/Article/details/gtmuzlqiqt.html

composer require --dev phpunit/phpunit
来源：http://dali.hongshengwenyu.top/Article/details/gtmodzpuxy.html

[U79] PHP：静态分析
来源：http://dali.mhx1999.top/Article/details/gtxwtirdli.html

composer require --dev phpstan/phpstan
来源：http://dali.pycfn.com/Article/details/gtsowxnyuz.html

[U80] PHP：代码规范修复
来源：http://dali.shzxlz.cn/Article/details/gtupiisltg.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.0kj1m.cn/Article/details/gtiydixtwt.html

[U81] JS：初始化项目
来源：http://dali.jqgufenzy.top/Article/details/gticngsabh.html

npm init -y;  npm i express
来源：http://dali.hysaishi.cn/Article/details/gtnkkgmqjf.html

[U82] JS：package.json 脚本
来源：http://dali.xinyue.icu/Article/details/gtsiafuicv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.nwbrower.top/Article/details/gtcayzfpyp.html

[U83] JS：ES Module 导入导出
来源：http://dali.guannengcc.top/Article/details/gtjxaqyyrg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.smart0.xyz/Article/details/gtqcevchhi.html

[U84] JS：CommonJS 写法
来源：http://dali.dianchejie.cn/Article/details/gtoclqcggq.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.redwolf501.top/Article/details/gtxcftdqyc.html

[U85] JS：可选链
来源：http://dali.bjfxy.top/Article/details/gtqxqymjkx.html

a?.b?.c
来源：http://dali.zhixingplan.top/Article/details/gtyhuyjrpj.html

[U86] JS：空值合并
来源：http://dali.tanke756.top/Article/details/gttxvgulki.html

a ?? b
来源：http://dali.yuxming.cn/Article/details/gtohcdjtre.html

[U87] JS：解构默认值
来源：http://dali.ivvv.top/Article/details/gtcrfbyuby.html

const { a = 1, b = 2 } = obj;
来源：http://dali.pycfn.com/Article/details/gtzvmxqvlq.html

[U88] JS：对象展开合并
来源：http://dali.daxiang520.top/Article/details/gtuikhgloe.html

{ ...a, ...b }
来源：http://dali.tian-w.cn/Article/details/gtopqkcjmc.html

[U89] JS：数组去重
来源：http://dali.guannengcc.top/Article/details/gtsdasvjpy.html

[...new Set(arr)]
来源：http://dali.nanxuanxn.top/Article/details/gtlzcpxohn.html

[U90] JS：数字数组排序
来源：http://dali.quarkkingdee.top/Article/details/gtisfzfdfz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gtsurvpviu.html

[U91] JS：对象键值遍历
来源：http://dali.hammf.cn/Article/details/gthiyigdey.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.snrcjt.cn/Article/details/gttoggaozx.html

[U92] JS：深拷贝
来源：http://dali.ybcxt.top/Article/details/gtlljvltvr.html

structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gthkntolmq.html

[U93] JS：模板字符串
来源：http://dali.cheryme.top/Article/details/gtqumcthoj.html

`共 ${n} 条`
来源：http://dali.daria6918.cn/Article/details/gtibwhmkpd.html

[U94] JS：箭头函数
来源：http://dali.chenlongwang.top/Article/details/gttsrqwmea.html

const double = x => x * 2;
来源：http://dali.cashguo.top/Article/details/gtdiyhchrb.html

[U95] JS：Promise 包装
来源：http://dali.andypj.xyz/Article/details/gtsbnqqjjr.html

new Promise((resolve, reject) => {})
来源：http://dali.yonumen.top/Article/details/gthblzwxnv.html

[U96] JS：async/await 与异常
来源：http://dali.bjfxy.top/Article/details/gtcdqzmfax.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gtngaxpdla.html

[U97] JS：并发请求
来源：http://dali.hfpthk.cn/Article/details/gtwmocyucw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dianchejie.cn/Article/details/gtrhaiaiho.html

[U98] JS：fetch 带 JSON
来源：http://dali.hysaishi.cn/Article/details/gtnthotqhg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.bjfxy.top/Article/details/gtolqzrkte.html

[U99] JS：事件监听
来源：http://dali.9152youxi.cn/Article/details/gtrtmbisdy.html

el.addEventListener("click", e => {})
来源：http://dali.shuidangran.top/Article/details/gtckldpwfi.html

[U100] JS：DOM 查询
来源：http://dali.aibaodan.cn/Article/details/gtgvpfkzik.html

document.querySelector(".item")
来源：http://dali.haohaochexian.top/Article/details/gteamzxfuf.html

[U101] JS：classList 操作
来源：http://dali.bjfxy.top/Article/details/gtntgibiyb.html

el.classList.toggle("active")
来源：http://dali.dianchejie.cn/Article/details/gthdlbqgac.html

[U102] JS：本地存储
来源：http://dali.yueranfly.top/Article/details/gtdxvwwoas.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.haohaochexian.top/Article/details/gtpocdmkmg.html

[U103] JS：定时器
来源：http://dali.wangdashe.top/Article/details/gtxchljvnx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.gotoacloud.top/Article/details/gtlhzxeddc.html

[U104] JS：防抖
来源：http://dali.vqdsnc.cn/Article/details/gtjtutoxce.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtczwrmzkg.html

[U105] JS：节流
来源：http://dali.meibo888.top/Article/details/gtbthnbjzm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.fengsongda.top/Article/details/gtedzmfbqk.html

[U106] JS：日期格式化
来源：http://dali.sysykeji.top/Article/details/gtaeonunfi.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.redwolf501.top/Article/details/gtorsfstqs.html

[U107] JS：数字千分位
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvpdjdmes.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yvedp.cn/Article/details/gtwmawtuzh.html

[U108] JS：随机整数
来源：http://dali.yj20258.top/Article/details/gtzmesqtlq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsfrxaool.html

[U109] JS：数组分组
来源：http://dali.cdnleiting.top/Article/details/gtmunbbhdn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhixingplan.top/Article/details/gtupzddtlr.html

[U110] JS：数组分块
来源：http://dali.sysykeji.top/Article/details/gtclnlhzne.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.cashguo.top/Article/details/gtmtvfpium.html

[U111] JS：对象转 Map
来源：http://dali.ehwqpu.com/Article/details/gtxdryfuld.html

new Map(Object.entries(obj))
来源：http://dali.nwbrower.top/Article/details/gtbeuhkiuf.html

[U112] JS：字符串补位
来源：http://dali.smart0.xyz/Article/details/gtmbavfpan.html

"7".padStart(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gtlfhtawcr.html

[U113] JS：正则替换全部
来源：http://dali.xuanzx.com/Article/details/gttyykkdxh.html

s.replaceAll("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtotnzhgge.html

[U114] JS：JSON 深比较
来源：http://dali.ivvv.top/Article/details/gthkspqhfn.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenjidiqi.icu/Article/details/gteocbhdfb.html

[U115] JS：生成 UUID
来源：http://dali.meibo888.top/Article/details/gtdvmlxgov.html

crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gthrqclbxm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhengqikj.top/Article/details/gtxyfosmwa.html

/** @param {string} name */ function f(name) {}
来源：http://dali.gzhubu.top/Article/details/gtoxhgkfxf.html

[U117] JS：单元测试
来源：http://dali.jiagoushi.top/Article/details/gtdjjztjff.html

npm i -D vitest;  npx vitest
来源：http://dali.vqdsnc.cn/Article/details/gthnantiho.html

[U118] JS：开发服务器
来源：http://dali.jqgufenzy.top/Article/details/gtjgqqvpcf.html

npm i -D vite;  npx vite
来源：http://dali.bjfxy.top/Article/details/gtgiiepjxp.html

[U119] JS：生产构建
来源：http://dali.havefunace.top/Article/details/gtzaumvwtp.html

npx vite build
来源：http://dali.yueranfly.top/Article/details/gtbylaveos.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xinyue.icu/Article/details/gtvnuaxkkv.html

import.meta.env.VITE_API_URL
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmyqhkfqn.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtrghjlmty.html

统计汇总
来源：http://dali.nwbrower.top/Article/details/gtiyvartpa.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtolaibuam.html

按语言统计（条）：
来源：http://dali.fzhhl.top/Article/details/gtwdinmctn.html

Python ......... 252
来源：http://dali.birdmap.top/Article/details/gtdgmpxygp.html

PHP ............ 252
来源：http://dali.nanxuanxn.top/Article/details/gtryfnnksd.html

JavaScript ..... 252
来源：http://dali.sysykeji.top/Article/details/gtntxgsfiv.html

TypeScript ..... 212
来源：http://dali.0kj1m.cn/Article/details/gtqvdebpmr.html

Java ........... 212
来源：http://dali.snrcjt.cn/Article/details/gtvawlqrve.html

Go ............. 212
来源：http://dali.9152youxi.cn/Article/details/gtrlefabwh.html

Ruby ........... 212
来源：http://dali.yanxiufei.cn/Article/details/gtfizjepak.html

C# ............. 212
来源：http://dali.smart0.xyz/Article/details/gtbjkyxgwn.html

C .............. 30
来源：http://dali.hnxiangtu.top/Article/details/gtsvhctiwd.html

C++ ............ 30
来源：http://dali.chenlongwang.top/Article/details/gtcjdhpqzp.html

SQL ............ 90
来源：http://dali.fengsongda.top/Article/details/gtjuurdxty.html

Bash ........... 80
来源：http://dali.havefunace.top/Article/details/gtrzlelaxh.html

Kotlin ......... 15
来源：http://dali.nanxinkj.top/Article/details/gtodlgqkvo.html

Swift .......... 15
来源：http://dali.dashuyun.cn/Article/details/gtvfrehaxi.html

Lua ............ 10
来源：http://dali.nanxinkj.top/Article/details/gtjwcroozh.html

Perl ........... 10
来源：http://dali.vqdsnc.cn/Article/details/gtszvrrwqa.html

Scala .......... 10
来源：http://dali.gotoacloud.top/Article/details/gtlwuylfgd.html

------------------------------------
来源：http://dali.yj20258.top/Article/details/gtazpurycg.html

合计 ........... 2106 条
来源：http://dali.yangfankeji.com/Article/details/gtytljjzkb.html

按章节统计：
来源：http://dali.hysaishi.cn/Article/details/gtsnfhsryc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hongshengwenyu.top/Article/details/gthichkpfb.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.gotoacloud.top/Article/details/gtzanrokek.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkekyriye.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.sufxvd.cn/Article/details/gtikptvldj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.daria6918.cn/Article/details/gteifmgitz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gtaofpgocy.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.svipenyu.cn/Article/details/gtyfchidua.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.chenlongwang.top/Article/details/gthlswfmbi.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.9152youxi.cn/Article/details/gtcvaxkups.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhixingplan.top/Article/details/gtzfbemnzl.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhoulong.xyz/Article/details/gteywuatnx.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yj20258.top/Article/details/gtufkfjnll.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.svipenyu.cn/Article/details/gtziuhdjas.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yangfankeji.com/Article/details/gtbxzyfsjm.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.tanke756.top/Article/details/gtwcapplze.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.xinyue.icu/Article/details/gteasznisb.html

Q SQL 专题                              90
来源：http://dali.yongpay.top/Article/details/gtmbwsdkvm.html

R Bash 专题                             80
来源：http://dali.zhoulong.xyz/Article/details/gtdakggivn.html

S C / C++ 专题                          60
来源：http://dali.redwolf501.top/Article/details/gtiryrqstb.html

T 其他语言补充                          60
来源：http://dali.vqdsnc.cn/Article/details/gtrwlamiin.html

U 高频实用片段                         120
来源：http://dali.yvedp.cn/Article/details/gtxilnawpo.html

------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gtgfqohprd.html

合计                                  2106 条
来源：http://dali.yvedp.cn/Article/details/gtadndbzrq.html

--------------------------------------------------------------------------------
来源：http://dali.zycfv.cn/Article/details/gtxnwyhfhm.html

使用提醒
来源：http://dali.hfpthk.cn/Article/details/gtnrztukgw.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgnvchfet.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yvedp.cn/Article/details/gtjiztpqnn.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.chenlongwang.top/Article/details/gtfkrebzzy.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.quarkkingdee.top/Article/details/gtihluxddj.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.chenlongwang.top/Article/details/gtdwnhitaq.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.nwbrower.top/Article/details/gtxyuvihvs.html

—— 文件结束 ——
来源：http://dali.feifeiyinyue.top/Article/details/gtespxqtzp.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtnmnmlfrf.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jianghu66.top/Article/details/gtwioxzrpb.html

Common Programming Examples Cheat Book
来源：http://dali.guannengcc.top/Article/details/gttbiahtaa.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gthcykalbc.html

【收录内容】
来源：http://dali.jyoumei.cn/Article/details/gtgxtrfsnh.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.ivvv.top/Article/details/gtoldjkbem.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.cdnleiting.top/Article/details/gtlylrdeqs.html

SQL · Bash · C · C++
来源：http://dali.jlsjyb.cn/Article/details/gtwezcdwcn.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.pengpengdd.cyou/Article/details/gtuqlylqgs.html

【使用说明】
来源：http://dali.birdmap.top/Article/details/gtcjpllpgt.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.daria6918.cn/Article/details/gtxeivfzxn.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jlsjyb.cn/Article/details/gtvgbhwsqv.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.feifeiyinyue.top/Article/details/gtdzxcgwzu.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.tianlin.xyz/Article/details/gtiwqggihh.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.aizwys.cn/Article/details/gtyhqkmbtb.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.9152youxi.cn/Article/details/gtetachdwe.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.birdmap.top/Article/details/gtoqfzfkpe.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.guowangkeji.top/Article/details/gtnewklzpb.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.birdmap.top/Article/details/gtkspirupy.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypotidyv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.tanke756.top/Article/details/gtdmnyfyga.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.cqqwz.cn/Article/details/gtzybhuopr.html

【文件统计】
来源：http://dali.nwbrower.top/Article/details/gtbrryrtpc.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.shuidangran.top/Article/details/gtcckwphno.html

--------------------------------------------------------------------------------
来源：http://dali.aibaodan.cn/Article/details/gtyzrywoin.html

目  录
来源：http://dali.zhongyouzk.top/Article/details/gtxrshnket.html

--------------------------------------------------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gtqpfksogb.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.dianchejie.cn/Article/details/gtzykpmylu.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.svipenyu.cn/Article/details/gtousahhpu.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.ybcxt.top/Article/details/gtnhefdafi.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.tian-w.cn/Article/details/gtqllzkhxg.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.nanxuanxn.top/Article/details/gttjubkkwv.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.nanxuanxn.top/Article/details/gtdjjuvcmo.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jqgufenzy.top/Article/details/gtikbgxqvo.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.aizwys.cn/Article/details/gtmuoqoirf.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.xuanzx.com/Article/details/gtwgwyknir.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.xylfe.cn/Article/details/gtwwstelmd.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.ivvv.top/Article/details/gtvkszifkl.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hysaishi.cn/Article/details/gtkpiojcax.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.gaohongyu789.top/Article/details/gtyyftuaya.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.gaohongyu789.top/Article/details/gtehuycqvn.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zycfv.cn/Article/details/gtzmjpnewe.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.sxryk.cn/Article/details/gtnskrwucx.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.shzxlz.cn/Article/details/gtehhyiyao.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.hfpthk.cn/Article/details/gtrsanujmq.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hnqzz.top/Article/details/gtrtlwrfoj.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yonumen.top/Article/details/gtpzxzrtnh.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yueranfly.top/Article/details/gthvevjrrh.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtnvikxrcc.html

A. 基础语法与类型
来源：http://dali.jyoumei.cn/Article/details/gtbdcawlzd.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtptrdaqnw.html

[A01] Hello World
来源：http://dali.sufxvd.cn/Article/details/gtdvckcjpu.html

Py:   print("Hello, World!")
来源：http://dali.shuidangran.top/Article/details/gtzqpaiirt.html

PHP:  echo "Hello, World!";
来源：http://dali.chenjidiqi.icu/Article/details/gtrxtkcdkl.html

JS:   console.log("Hello, World!");
来源：http://dali.kuanghao11.cn/Article/details/gtkwzdupdb.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zycfv.cn/Article/details/gtxnzqvbzb.html

Java: System.out.println("Hello, World!");
来源：http://dali.xylfe.cn/Article/details/gtwgxpobgn.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.daria6918.cn/Article/details/gtxyrzbstd.html

Ruby: puts "Hello, World!"
来源：http://dali.yongpay.top/Article/details/gtxfsipnkf.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.ppjwa.cn/Article/details/gtznkuhmjr.html

[A02] 变量声明与赋值
来源：http://dali.xuetiantiany.cn/Article/details/gtwfaannxh.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.wangshuangyany.cn/Article/details/gttvyugiwg.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jqgfzy.top/Article/details/gtofkmicwz.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ydzc1.top/Article/details/gtqkronvje.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jianghu66.top/Article/details/gtnqqcexfb.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jyoumei.cn/Article/details/gtmacnahsb.html

Go:   name := "Alex"; age := 20
来源：http://dali.tianlin.xyz/Article/details/gtsulifcud.html

Ruby: name = "Alex"; age = 20
来源：http://dali.nanxinkj.top/Article/details/gtayuvxelg.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.ehwqpu.com/Article/details/gtipeclrcx.html

[A03] 常量定义
来源：http://dali.xylfe.cn/Article/details/gthifukzgg.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.cheryme.top/Article/details/gtjnyvcnwb.html

PHP:  const PI = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gtluocmozr.html

JS:   const PI = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gtnjytspuc.html

TS:   const PI: number = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtofgsurzp.html

Java: static final double PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gtgxhvrfye.html

Go:   const PI = 3.14159
来源：http://dali.cucudq.cn/Article/details/gtofohsjvc.html

Ruby: PI = 3.14159
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaemopkzx.html

C#:   const double PI = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gtrhgbzkxr.html

[A04] 判断变量类型
来源：http://dali.yj20258.top/Article/details/gtujspfngv.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.vqdsnc.cn/Article/details/gtyomoekkk.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jinqigufen.top/Article/details/gtklatoqnu.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yuanzhike.top/Article/details/gtxusswakb.html

TS:   typeof x; x instanceof Date
来源：http://dali.hnqzz.top/Article/details/gtfvmhphti.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yj202588.top/Article/details/gtauzjmibq.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.wangshuangyany.cn/Article/details/gtegzgrthb.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlmaqbfoy.html

C#:   x.GetType().Name; x is int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpvslezdb.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gtpntggjdr.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.iojbl.cn/Article/details/gtdtrmrxvk.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.guowangkeji.top/Article/details/gtkvxytdmu.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ppjwa.cn/Article/details/gtddxrifwf.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jlsjyb.cn/Article/details/gtkglfljjv.html

Java: 7 / 2; 7 % 2
来源：http://dali.ybcxt.top/Article/details/gtqhlzhdip.html

Go:   7 / 2; 7 % 2
来源：http://dali.xuanzx.com/Article/details/gtszxjmfag.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.cdnleiting.top/Article/details/gtzmjudypm.html

C#:   7 / 2; 7 % 2
来源：http://dali.gogol.net.cn/Article/details/gtcvhqkidh.html

[A06] 字符串转数字
来源：http://dali.9152youxi.cn/Article/details/gtvmtrjjxr.html

Py:   int("42"); float("3.14")
来源：http://dali.jqgufenzy.top/Article/details/gtsvusvtac.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.xinyue.icu/Article/details/gtvtbricja.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhiwuduotai.top/Article/details/gtmrhztkod.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zycfv.cn/Article/details/gtnlstxqpo.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.daria6918.cn/Article/details/gtvpjlzlvv.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxmititez.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.gaohongyu789.top/Article/details/gtqwkxeiah.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.pycfn.com/Article/details/gthrijtbdh.html

[A07] 数字转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtweujzoky.html

Py:   str(42)
来源：http://dali.chenlongwang.top/Article/details/gtzbsiswcm.html

PHP:  (string) 42; strval(42)
来源：http://dali.aibaodan.cn/Article/details/gtvpxzltjv.html

JS:   String(42); (42).toString()
来源：http://dali.cashguo.top/Article/details/gtxmixfuot.html

TS:   String(42)
来源：http://dali.chenlongwang.top/Article/details/gtdbvlivgx.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.sxryk.cn/Article/details/gttswikykf.html

Go:   strconv.Itoa(42)
来源：http://dali.cucudq.cn/Article/details/gtbmmafmcs.html


<!-- 参考信息 -->