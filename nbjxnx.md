代发 wailian999

[U53] PHP：空合并运算符
来源：http://dali.jinqigufen.top/Article/details/gtfjbnqkne.html

$v = $a ?? $b ?? "default";
来源：http://dali.hfpthk.cn/Article/details/gtpebudxdj.html

[U54] PHP：空安全调用
来源：http://dali.xuetiantiany.cn/Article/details/gtjabiqihs.html

$obj?->method()
来源：http://dali.hnxiangtu.top/Article/details/gtalzbukvm.html

[U55] PHP：match 表达式
来源：http://dali.jinqigfzy.top/Article/details/gtirljkgms.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.havefunace.top/Article/details/gtvbqvvwwt.html

[U56] PHP：命名参数
来源：http://dali.jyoumei.cn/Article/details/gtlnejzcnf.html

f(a: 1, b: 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthqttipwl.html

[U57] PHP：字符串插值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwucwfgtn.html

"值: {$a}"
来源：http://dali.gotoacloud.top/Article/details/gttspohfsu.html

[U58] PHP：数组三件套
来源：http://dali.zhaomingkeji.xyz/Article/details/gtznjamjdn.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtgvcuiilp.html

[U59] PHP：自定义排序
来源：http://dali.zhengqikj.top/Article/details/gttthheezq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258888.top/Article/details/gtyxfuyoyf.html

[U60] PHP：JSON 编解码
来源：http://dali.nanxuanxn.top/Article/details/gtkibeflio.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.chenjidiqi.icu/Article/details/gtlviuuant.html

[U61] PHP：正则
来源：http://dali.nanxuanxn.top/Article/details/gtegvraqjq.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.xziqi.cn/Article/details/gtbubjoprz.html

[U62] PHP：日期对象
来源：http://dali.redwolf501.top/Article/details/gtcbdlxquj.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.meibo888.top/Article/details/gthvhurplt.html

[U63] PHP：文件读写
来源：http://dali.haohaochexian.top/Article/details/gtpegrgnep.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxoysjauk.html

[U64] PHP：目录遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfgjockqv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.nanxinkj.top/Article/details/gtsgbaciqk.html

[U65] PHP：会话
来源：http://dali.ydzc1.top/Article/details/gtkkividss.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.guannengcc.top/Article/details/gtbsaefipj.html

[U66] PHP：设置 Cookie
来源：http://dali.fengsongda.top/Article/details/gthfwqrxpb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.fzhhl.top/Article/details/gtslvjawgt.html

[U67] PHP：处理文件上传
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthoxzeanr.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhiwuduotai.top/Article/details/gtkgrxploz.html

[U68] PHP：PDO 连接
来源：http://dali.iojbl.cn/Article/details/gthanvdsjj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yj20258888.top/Article/details/gtdebqfvso.html

[U69] PHP：PDO 预处理
来源：http://dali.nanxinkj.top/Article/details/gtljyqjklo.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jqgufenzy.top/Article/details/gttqvgijwb.html

[U70] PHP：PDO 事务
来源：http://dali.nanxuanxn.top/Article/details/gtddavlkfm.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.sxryk.cn/Article/details/gtbstydpmb.html

[U71] PHP：抛出异常
来源：http://dali.hongshengwenyu.top/Article/details/gtrlecilzm.html

throw new RuntimeException("失败", 500);
来源：http://dali.fengsongda.top/Article/details/gtlyfymqnc.html

[U72] PHP：写错误日志
来源：http://dali.jianghu66.top/Article/details/gtopilialb.html

error_log("失败: " . $e->getMessage());
来源：http://dali.daria6918.cn/Article/details/gtapxcgiad.html

[U73] PHP：读取 ini 配置
来源：http://dali.jinyuanbaomall.cn/Article/details/gtujtfbcsu.html

parse_ini_file("config.ini", true)
来源：http://dali.jyoumei.cn/Article/details/gtfyonkpfq.html

[U74] PHP：读取环境变量
来源：http://dali.mhx1999.top/Article/details/gtpyrzfcxx.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yangfankeji.com/Article/details/gtanmhlbsk.html

[U75] PHP：依赖注入
来源：http://dali.jiagoushi.top/Article/details/gtrpplmisy.html

composer require psr/container
来源：http://dali.haohaochexian.top/Article/details/gtlgeiqzcu.html

[U76] PHP：简单路由
来源：http://dali.cashguo.top/Article/details/gttjnrlbvx.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.aibaodan.cn/Article/details/gtposlnclm.html

[U77] PHP：模板渲染
来源：http://dali.nanxuanxn.top/Article/details/gtemkednjp.html

composer require twig/twig
来源：http://dali.svipenyu.cn/Article/details/gtfuehkhuk.html

[U78] PHP：单元测试
来源：http://dali.dashuyun.cn/Article/details/gtwyyedaul.html

composer require --dev phpunit/phpunit
来源：http://dali.ydzc1.top/Article/details/gtsxcvzjtu.html

[U79] PHP：静态分析
来源：http://dali.cashguo.top/Article/details/gteeufveik.html

composer require --dev phpstan/phpstan
来源：http://dali.andypj.xyz/Article/details/gtdhhcyosm.html

[U80] PHP：代码规范修复
来源：http://dali.cdnleiting.top/Article/details/gtdiwdalia.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtujciemey.html

[U81] JS：初始化项目
来源：http://dali.dashuyun.cn/Article/details/gtozkqciax.html

npm init -y;  npm i express
来源：http://dali.quarkkingdee.top/Article/details/gthsmockgc.html

[U82] JS：package.json 脚本
来源：http://dali.aibaodan.cn/Article/details/gtttibejuv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.c1oappe.top/Article/details/gtmtxbstdd.html

[U83] JS：ES Module 导入导出
来源：http://dali.jinghuilouyu.cn/Article/details/gtglizawcm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.sxryk.cn/Article/details/gtbzpaohtx.html

[U84] JS：CommonJS 写法
来源：http://dali.cashguo.top/Article/details/gtedrzpmug.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cucudq.cn/Article/details/gtvhbnofus.html

[U85] JS：可选链
来源：http://dali.zhoulong.xyz/Article/details/gttamswiem.html

a?.b?.c
来源：http://dali.pycfn.com/Article/details/gtjkuwbkxy.html

[U86] JS：空值合并
来源：http://dali.ppjwa.cn/Article/details/gtdafqszdm.html

a ?? b
来源：http://dali.fzhhl.top/Article/details/gtyhklqrad.html

[U87] JS：解构默认值
来源：http://dali.birdmap.top/Article/details/gtowbtgwal.html

const { a = 1, b = 2 } = obj;
来源：http://dali.vqdsnc.cn/Article/details/gtksvasiwi.html

[U88] JS：对象展开合并
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkdftnri.html

{ ...a, ...b }
来源：http://dali.vqdsnc.cn/Article/details/gtmahauqnh.html

[U89] JS：数组去重
来源：http://dali.jinghuilouyu.cn/Article/details/gtatqwzlez.html

[...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gttrpsozhf.html

[U90] JS：数字数组排序
来源：http://dali.snrcjt.cn/Article/details/gtzeoyiqoo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yj20258888.top/Article/details/gtnwfebrud.html

[U91] JS：对象键值遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtzufurovk.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ybcxt.top/Article/details/gtssavjmvm.html

[U92] JS：深拷贝
来源：http://dali.jyoumei.cn/Article/details/gtbridnmmo.html

structuredClone(obj)
来源：http://dali.xinyue.icu/Article/details/gtdptgfwxc.html

[U93] JS：模板字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtxxetfbwl.html

`共 ${n} 条`
来源：http://dali.ybcxt.top/Article/details/gtjbhqmczn.html

[U94] JS：箭头函数
来源：http://dali.0kj1m.cn/Article/details/gtqpegeujz.html

const double = x => x * 2;
来源：http://dali.feifeiyinyue.top/Article/details/gtoplsxcxa.html

[U95] JS：Promise 包装
来源：http://dali.hnxiangtu.top/Article/details/gteojarqtg.html

new Promise((resolve, reject) => {})
来源：http://dali.yangfankeji.com/Article/details/gtjgrbxihd.html

[U96] JS：async/await 与异常
来源：http://dali.vqdsnc.cn/Article/details/gtumrujhrk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gtqosfpiuc.html

[U97] JS：并发请求
来源：http://dali.jinqigfzy.top/Article/details/gtdbekbrfu.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gtykootilo.html

[U98] JS：fetch 带 JSON
来源：http://dali.gaohongyu789.top/Article/details/gtsazuzdoi.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.pengpengdd.cyou/Article/details/gtinofgqwa.html

[U99] JS：事件监听
来源：http://dali.cdnleiting.top/Article/details/gteirccdke.html

el.addEventListener("click", e => {})
来源：http://dali.gzhubu.top/Article/details/gtmbnqccfz.html

[U100] JS：DOM 查询
来源：http://dali.jinqigfzy.top/Article/details/gtwpumbkkh.html

document.querySelector(".item")
来源：http://dali.zhengqikj.top/Article/details/gtlrfmjaqi.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gtrnwlsglu.html

el.classList.toggle("active")
来源：http://dali.shzxlz.cn/Article/details/gtfrnafwfo.html

[U102] JS：本地存储
来源：http://dali.hammf.cn/Article/details/gtjrqgmfdy.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhongyouzk.top/Article/details/gtukfzszeg.html

[U103] JS：定时器
来源：http://dali.yuxming.cn/Article/details/gthugiqbdy.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoxoglzfl.html

[U104] JS：防抖
来源：http://dali.daria6918.cn/Article/details/gtmhbxtama.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.316326.xyz/Article/details/gtigstebun.html

[U105] JS：节流
来源：http://dali.kuanghao11.cn/Article/details/gtntlcdkhc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jqgufenzy.top/Article/details/gtfzrnbgld.html

[U106] JS：日期格式化
来源：http://dali.jqgufenzy.top/Article/details/gtdikoswue.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zycfv.cn/Article/details/gtxndbthoe.html

[U107] JS：数字千分位
来源：http://dali.andypj.xyz/Article/details/gtvvlpmych.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xziqi.cn/Article/details/gtgtkczgej.html

[U108] JS：随机整数
来源：http://dali.tianlin.xyz/Article/details/gtyvrrtskf.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.tanke756.top/Article/details/gtgbgccojn.html

[U109] JS：数组分组
来源：http://dali.havefunace.top/Article/details/gthrnmjvab.html

Object.groupBy(arr, x => x.type)
来源：http://dali.andypj.xyz/Article/details/gtzyjvekos.html

[U110] JS：数组分块
来源：http://dali.chenzaomai.com/Article/details/gtkpoazuxg.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.nanxuanxn.top/Article/details/gtgpfrnpvi.html

[U111] JS：对象转 Map
来源：http://dali.dashuyun.cn/Article/details/gtncwhdjrw.html

new Map(Object.entries(obj))
来源：http://dali.jianghu66.top/Article/details/gtresrcsbd.html

[U112] JS：字符串补位
来源：http://dali.pengpengdd.cyou/Article/details/gtsdkdrrok.html

"7".padStart(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmkyxkuuw.html

[U113] JS：正则替换全部
来源：http://dali.kuanghao11.cn/Article/details/gtjfvqjayu.html

s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtghcfwhkq.html

[U114] JS：JSON 深比较
来源：http://dali.sysykeji.top/Article/details/gtuehixmgn.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.birdmap.top/Article/details/gtlzvanvmo.html

[U115] JS：生成 UUID
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdkcziqpy.html

crypto.randomUUID()
来源：http://dali.yj202588.top/Article/details/gtkuicvnua.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.gotoacloud.top/Article/details/gtzbhtsoki.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yj202588.top/Article/details/gtqucfltxu.html

[U117] JS：单元测试
来源：http://dali.snrcjt.cn/Article/details/gtwepncmhb.html

npm i -D vitest;  npx vitest
来源：http://dali.pycfn.com/Article/details/gttthfvmvo.html

[U118] JS：开发服务器
来源：http://dali.sxryk.cn/Article/details/gtwyljtugj.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gttckwubjk.html

[U119] JS：生产构建
来源：http://dali.ppjwa.cn/Article/details/gtpifcybff.html

npx vite build
来源：http://dali.cashguo.top/Article/details/gtujwyqzmk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yonumen.top/Article/details/gtbqfjsspi.html

import.meta.env.VITE_API_URL
来源：http://dali.gzhubu.top/Article/details/gtujplfjfc.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtktuezilc.html

统计汇总
来源：http://dali.cdnleiting.top/Article/details/gtracliynq.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gturqyfwly.html

按语言统计（条）：
来源：http://dali.yongpay.top/Article/details/gtklrmbwer.html

Python ......... 252
来源：http://dali.yonumen.top/Article/details/gtokdfewig.html

PHP ............ 252
来源：http://dali.c1oappe.top/Article/details/gthpvrbjxx.html

JavaScript ..... 252
来源：http://dali.iojbl.cn/Article/details/gthenryfqo.html

TypeScript ..... 212
来源：http://dali.zhoulong.xyz/Article/details/gtzqlupjww.html

Java ........... 212
来源：http://dali.wangdashe.top/Article/details/gtnionoeye.html

Go ............. 212
来源：http://dali.xinyue.icu/Article/details/gtnqaeqgaj.html

Ruby ........... 212
来源：http://dali.daria6918.cn/Article/details/gtwkakvpsq.html

C# ............. 212
来源：http://dali.zhiwuduotai.top/Article/details/gtzbtqznpe.html

C .............. 30
来源：http://dali.yonumen.top/Article/details/gtksbhhvdq.html

C++ ............ 30
来源：http://dali.nanxuanxn.top/Article/details/gtkibhpzqf.html

SQL ............ 90
来源：http://dali.wangdashe.top/Article/details/gtkmfrbdjy.html

Bash ........... 80
来源：http://dali.yanxiufei.cn/Article/details/gtznroetgk.html

Kotlin ......... 15
来源：http://dali.guowangkeji.top/Article/details/gtaerjgaro.html

Swift .......... 15
来源：http://dali.zdqjudy.top/Article/details/gthvvwjavv.html

Lua ............ 10
来源：http://dali.zhengqikj.top/Article/details/gttwhlukmx.html

Perl ........... 10
来源：http://dali.andypj.xyz/Article/details/gtpcopsrut.html

Scala .......... 10
来源：http://dali.ehwqpu.com/Article/details/gtrnoysdxg.html

------------------------------------
来源：http://dali.snrcjt.cn/Article/details/gtgdkbalgv.html

合计 ........... 2106 条
来源：http://dali.tian-w.cn/Article/details/gtxziglwbm.html

按章节统计：
来源：http://dali.zdqjudy.top/Article/details/gtsyfalzsg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gttyrcszwr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jqgufenzy.top/Article/details/gtjsfgncnw.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ydzc1.top/Article/details/gtzixxzuis.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqeusdsdl.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.gzhubu.top/Article/details/gtuquzhnbm.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.316326.xyz/Article/details/gthrgalonf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.shangyingyoupin.top/Article/details/gttyfgtspd.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yuxming.cn/Article/details/gtfiilbozf.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.wangshuangyany.cn/Article/details/gtdyaudeya.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.iojbl.cn/Article/details/gtiuikmmno.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhengqikj.top/Article/details/gtacoxgysm.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.nanxuanxn.top/Article/details/gtfiryitmy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.tianlin.xyz/Article/details/gtcmxrfxem.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.gaohongyu789.top/Article/details/gtqjlovdke.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jinghuilouyu.cn/Article/details/gthgoquqgw.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yuxming.cn/Article/details/gtjvhnswfn.html

Q SQL 专题                              90
来源：http://dali.hnxiangtu.top/Article/details/gthgmwprlt.html

R Bash 专题                             80
来源：http://dali.gotoacloud.top/Article/details/gtiyyrwupo.html

S C / C++ 专题                          60
来源：http://dali.ehwqpu.com/Article/details/gtojscstik.html

T 其他语言补充                          60
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtsepckr.html

U 高频实用片段                         120
来源：http://dali.shuidangran.top/Article/details/gtbjsgvija.html

------------------------------------
来源：http://dali.jinqigufen.top/Article/details/gtjgnhaosb.html

合计                                  2106 条
来源：http://dali.hnqzz.top/Article/details/gtrwaxwsuz.html

--------------------------------------------------------------------------------
来源：http://dali.yuanzhike.top/Article/details/gtdpekugfy.html

使用提醒
来源：http://dali.wangshuangyany.cn/Article/details/gtfvbwkeaz.html

--------------------------------------------------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gtffogorqk.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhiwuduotai.top/Article/details/gtpmgruhqp.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.tanke756.top/Article/details/gtkcvxoich.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jlsjyb.cn/Article/details/gtiapaxiyb.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xinyue.icu/Article/details/gtunjkbwzs.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jinqigufen.top/Article/details/gtilgmxmha.html

—— 文件结束 ——
来源：http://dali.jiagoushi.top/Article/details/gtqykqhbxp.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gttxiaupuu.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.mhx1999.top/Article/details/gtcaetbxhk.html

Common Programming Examples Cheat Book
来源：http://dali.bjfxy.top/Article/details/gthkbqyjtw.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtemtvkiyz.html

【收录内容】
来源：http://dali.meibo888.top/Article/details/gtndiqpcia.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.chenjidiqi.icu/Article/details/gtwuxzmudk.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.haohaochexian.top/Article/details/gttvlkfkcp.html

SQL · Bash · C · C++
来源：http://dali.wangdashe.top/Article/details/gtnabewujk.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.hywenlv.cn/Article/details/gtwmcmhvxp.html

【使用说明】
来源：http://dali.hfpthk.cn/Article/details/gttyxgiqwf.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yangfankeji.com/Article/details/gtmkatsott.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.ybcxt.top/Article/details/gtlwswxeid.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.sufxvd.cn/Article/details/gtmltarbxz.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.dianchejie.cn/Article/details/gthniimumq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yvedp.cn/Article/details/gteytnbdse.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.redwolf501.top/Article/details/gtekuxewyp.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhiwuduotai.top/Article/details/gtfgumcpaa.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.bjfxy.top/Article/details/gtlbniuvfd.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.kuanghao11.cn/Article/details/gtkmnaqvda.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.nanxinkj.top/Article/details/gtzqvrryty.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.shanyushiyangtech.top/Article/details/gttmvhqesg.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yueranfly.top/Article/details/gtgewaubzi.html

【文件统计】
来源：http://dali.kuanghao11.cn/Article/details/gtjnxhcflr.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yj20258888.top/Article/details/gtoybenkdi.html

--------------------------------------------------------------------------------
来源：http://dali.hnqzz.top/Article/details/gtjefbejta.html

目  录
来源：http://dali.yuxming.cn/Article/details/gtqfsorhda.html

--------------------------------------------------------------------------------
来源：http://dali.hammf.cn/Article/details/gtygfaadgh.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.havefunace.top/Article/details/gtkkoyzerf.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhoulong.xyz/Article/details/gtlaqkgfsa.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yj20258888.top/Article/details/gtkxmkvqup.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.chenlongwang.top/Article/details/gthgtxcqdo.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yj20258888.top/Article/details/gtmmxahufx.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yonumen.top/Article/details/gtpwblzxnj.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtakpebbmu.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.shangyingyoupin.top/Article/details/gttzjrskth.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.mhx1999.top/Article/details/gtiqhoqsbv.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.xinyue.icu/Article/details/gtyjkqpyvc.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.cheryme.top/Article/details/gtawfswoki.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhoulong.xyz/Article/details/gtpgaidzma.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.smart0.xyz/Article/details/gtsollffca.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.chenjidiqi.icu/Article/details/gturgtyaxk.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jqgufenzy.top/Article/details/gtiuyhfdeo.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.sysykeji.top/Article/details/gtzcxrypay.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.gaohongyu789.top/Article/details/gtfnpolhsl.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrtnmuwsh.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yj202588.top/Article/details/gticjifoyj.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yanxiufei.cn/Article/details/gtquqjxnen.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.aibaodan.cn/Article/details/gtwhdzodfs.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtoeqsffdv.html

A. 基础语法与类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtzwgeeiwi.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gthjhujnax.html

[A01] Hello World
来源：http://dali.yj20258888.top/Article/details/gthqpewdef.html

Py:   print("Hello, World!")
来源：http://dali.snrcjt.cn/Article/details/gtnytgqljr.html

PHP:  echo "Hello, World!";
来源：http://dali.zdqjudy.top/Article/details/gtoqrooayb.html

JS:   console.log("Hello, World!");
来源：http://dali.gaohongyu789.top/Article/details/gtybllwgkw.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.xuanzx.com/Article/details/gtghizfooc.html

Java: System.out.println("Hello, World!");
来源：http://dali.ehwqpu.com/Article/details/gttpaizkmk.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.dianchejie.cn/Article/details/gtbymzlstn.html

Ruby: puts "Hello, World!"
来源：http://dali.ivvv.top/Article/details/gttpjecnxw.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.sweek.top/Article/details/gtbpqtfbec.html

[A02] 变量声明与赋值
来源：http://dali.chenlongwang.top/Article/details/gttdqpklne.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhixingplan.top/Article/details/gtgnkepnfl.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hammf.cn/Article/details/gtdtxwdkox.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.xinyue.icu/Article/details/gtujieutsx.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jlsjyb.cn/Article/details/gtvqbulcuz.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.iojbl.cn/Article/details/gtnxarxvmh.html

Go:   name := "Alex"; age := 20
来源：http://dali.0kj1m.cn/Article/details/gtmlknatdm.html

Ruby: name = "Alex"; age = 20
来源：http://dali.shuidangran.top/Article/details/gtdomxgvnp.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.guannengcc.top/Article/details/gtrncreiac.html

[A03] 常量定义
来源：http://dali.jianghu66.top/Article/details/gtpaaosrva.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jianghu66.top/Article/details/gtumybxrsi.html

PHP:  const PI = 3.14159;
来源：http://dali.daxiang520.top/Article/details/gtrimoerwx.html

JS:   const PI = 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gtwmvbjsyr.html

TS:   const PI: number = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtmygicmhx.html

Java: static final double PI = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gtfkqcwnnn.html

Go:   const PI = 3.14159
来源：http://dali.hywenlv.cn/Article/details/gtdoiqtgpz.html

Ruby: PI = 3.14159
来源：http://dali.hnxiangtu.top/Article/details/gttlofkmop.html

C#:   const double PI = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gtrtlvvgkm.html

[A04] 判断变量类型
来源：http://dali.chenjidiqi.icu/Article/details/gtkclaxcgv.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gtikyglbec.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.iojbl.cn/Article/details/gtlxkkqyjx.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.chenlongwang.top/Article/details/gtjxuvlfxy.html

TS:   typeof x; x instanceof Date
来源：http://dali.smart0.xyz/Article/details/gtikwcenoe.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.shuidangran.top/Article/details/gtciulkpuu.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jyoumei.cn/Article/details/gtiklcqhrk.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.chenlongwang.top/Article/details/gtycgcbtbn.html

C#:   x.GetType().Name; x is int
来源：http://dali.ybcxt.top/Article/details/gtbswyrrnj.html

[A05] 整数除法与取模
来源：http://dali.sufxvd.cn/Article/details/gtpsqbzkqk.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.xylfe.cn/Article/details/gtzbutkiaz.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtovnozqde.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.fengsongda.top/Article/details/gtbapynqil.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.daria6918.cn/Article/details/gtxjmhrytv.html

Java: 7 / 2; 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gthaeeruio.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxifznpbo.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jinqigfzy.top/Article/details/gtljtszyfq.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gtgtwwcuou.html

[A06] 字符串转数字
来源：http://dali.xylfe.cn/Article/details/gtfsllkmuf.html

Py:   int("42"); float("3.14")
来源：http://dali.zhongyouzk.top/Article/details/gtouvszwhe.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yanxiufei.cn/Article/details/gtjgyqmuut.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.wangdashe.top/Article/details/gtrzdnmgyg.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hysaishi.cn/Article/details/gtqbeyggxn.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.gaohongyu789.top/Article/details/gtoeqyludz.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.chenjidiqi.icu/Article/details/gtocfknqap.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jqgfzy.top/Article/details/gtkxkjtrsv.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.gzhubu.top/Article/details/gtotpfmidx.html

[A07] 数字转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtucckmxvb.html

Py:   str(42)
来源：http://dali.jinqigfzy.top/Article/details/gtghqreqte.html

PHP:  (string) 42; strval(42)
来源：http://dali.tian-w.cn/Article/details/gtzrujcnch.html


<!-- 参考信息 -->