代发 wailian999

[U57] PHP：字符串插值
来源：http://dali.kuanghao11.cn/Article/details/gtrbropgjn.html

"值: {$a}"
来源：http://dali.feifeiyinyue.top/Article/details/gtkszwkrko.html

[U58] PHP：数组三件套
来源：http://dali.tian-w.cn/Article/details/gtfzbzwwxz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhengqikj.top/Article/details/gtagyboscs.html

[U59] PHP：自定义排序
来源：http://dali.ybcxt.top/Article/details/gtbrdfxmrb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cucudq.cn/Article/details/gtfmuhhjio.html

[U60] PHP：JSON 编解码
来源：http://dali.zdqjudy.top/Article/details/gticqfyewp.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.nwbrower.top/Article/details/gtmraxbesg.html

[U61] PHP：正则
来源：http://dali.fengsongda.top/Article/details/gtzfrrtwbm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hysaishi.cn/Article/details/gtsxbyzfjv.html

[U62] PHP：日期对象
来源：http://dali.ybcxt.top/Article/details/gtusddgcxm.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hammf.cn/Article/details/gtrwhzraos.html

[U63] PHP：文件读写
来源：http://dali.xuetiantiany.cn/Article/details/gtoaiuuajn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.shangyingyoupin.top/Article/details/gtwkmiryrk.html

[U64] PHP：目录遍历
来源：http://dali.fengsongda.top/Article/details/gtldvibamd.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ppjwa.cn/Article/details/gtrrnjklks.html

[U65] PHP：会话
来源：http://dali.316326.xyz/Article/details/gtyuxctvam.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gtgolgpngi.html

[U66] PHP：设置 Cookie
来源：http://dali.jinqigufen.top/Article/details/gtsfrreevn.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdouuxmdw.html

[U67] PHP：处理文件上传
来源：http://dali.fengsongda.top/Article/details/gthnjslgtj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.cqqwz.cn/Article/details/gtdrgbmpea.html

[U68] PHP：PDO 连接
来源：http://dali.jinqigfzy.top/Article/details/gtquomwaqz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zdqjudy.top/Article/details/gtdypqiqrb.html

[U69] PHP：PDO 预处理
来源：http://dali.jqgufenzy.top/Article/details/gthftjkelf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.sxryk.cn/Article/details/gtixhododp.html

[U70] PHP：PDO 事务
来源：http://dali.zhixingplan.top/Article/details/gtrbuuryzg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jinghuilouyu.cn/Article/details/gtncxlopix.html

[U71] PHP：抛出异常
来源：http://dali.snrcjt.cn/Article/details/gtnncdikrg.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhixingplan.top/Article/details/gtchyfooyd.html

[U72] PHP：写错误日志
来源：http://dali.shzxlz.cn/Article/details/gtqhgjsumo.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yanxiufei.cn/Article/details/gthwhhndhi.html

[U73] PHP：读取 ini 配置
来源：http://dali.pengpengdd.cyou/Article/details/gthjretzol.html

parse_ini_file("config.ini", true)
来源：http://dali.cashguo.top/Article/details/gtvcsukria.html

[U74] PHP：读取环境变量
来源：http://dali.andypj.xyz/Article/details/gtzooanxfn.html

getenv("APP_ENV") ?: "production"
来源：http://dali.sysykeji.top/Article/details/gtpundshyn.html

[U75] PHP：依赖注入
来源：http://dali.nanxinkj.top/Article/details/gtwkbvtinr.html

composer require psr/container
来源：http://dali.hywenlv.cn/Article/details/gtedpzlupk.html

[U76] PHP：简单路由
来源：http://dali.jinqigfzy.top/Article/details/gtprffxycb.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.wangdashe.top/Article/details/gtgxmlbvak.html

[U77] PHP：模板渲染
来源：http://dali.ivvv.top/Article/details/gtuuuxkafc.html

composer require twig/twig
来源：http://dali.ehwqpu.com/Article/details/gtsdmlnlfy.html

[U78] PHP：单元测试
来源：http://dali.feifeiyinyue.top/Article/details/gtfckdakvr.html

composer require --dev phpunit/phpunit
来源：http://dali.gzhubu.top/Article/details/gtmxyodgyh.html

[U79] PHP：静态分析
来源：http://dali.yuxming.cn/Article/details/gtcmghonlw.html

composer require --dev phpstan/phpstan
来源：http://dali.zhiwuduotai.top/Article/details/gtzhbcjhab.html

[U80] PHP：代码规范修复
来源：http://dali.jqgufenzy.top/Article/details/gtwczsbhsp.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.0kj1m.cn/Article/details/gtzxrvkxir.html

[U81] JS：初始化项目
来源：http://dali.mhx1999.top/Article/details/gtwluballi.html

npm init -y;  npm i express
来源：http://dali.shzxlz.cn/Article/details/gtfpovsfrf.html

[U82] JS：package.json 脚本
来源：http://dali.xinyue.icu/Article/details/gtihxxepqm.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yangfankeji.com/Article/details/gtlkzbweoi.html

[U83] JS：ES Module 导入导出
来源：http://dali.birdmap.top/Article/details/gtxuifgcve.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jinqigufen.top/Article/details/gtzpfdhckj.html

[U84] JS：CommonJS 写法
来源：http://dali.zhiwuduotai.top/Article/details/gttdpbwqdn.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hfpthk.cn/Article/details/gtjcvhroqd.html

[U85] JS：可选链
来源：http://dali.quarkkingdee.top/Article/details/gtwgfoadwy.html

a?.b?.c
来源：http://dali.dianchejie.cn/Article/details/gtzlgydvut.html

[U86] JS：空值合并
来源：http://dali.316326.xyz/Article/details/gtlucepiar.html

a ?? b
来源：http://dali.bjfxy.top/Article/details/gtgihyunbq.html

[U87] JS：解构默认值
来源：http://dali.mhx1999.top/Article/details/gtajiacstc.html

const { a = 1, b = 2 } = obj;
来源：http://dali.daxiang520.top/Article/details/gtbuotqccp.html

[U88] JS：对象展开合并
来源：http://dali.yj20258.top/Article/details/gtqhururbj.html

{ ...a, ...b }
来源：http://dali.iojbl.cn/Article/details/gtnzaoisok.html

[U89] JS：数组去重
来源：http://dali.jqgufenzy.top/Article/details/gtwijxouuu.html

[...new Set(arr)]
来源：http://dali.aizwys.cn/Article/details/gtljhuveez.html

[U90] JS：数字数组排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkbgsxsej.html

[...arr].sort((a, b) => a - b)
来源：http://dali.cashguo.top/Article/details/gtnexwfngr.html

[U91] JS：对象键值遍历
来源：http://dali.gaohongyu789.top/Article/details/gtitmaulxc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.meibo888.top/Article/details/gtqirgnnvh.html

[U92] JS：深拷贝
来源：http://dali.0kj1m.cn/Article/details/gtxmfpaaii.html

structuredClone(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqpfghhub.html

[U93] JS：模板字符串
来源：http://dali.ybcxt.top/Article/details/gtkvqmyhmx.html

`共 ${n} 条`
来源：http://dali.sweek.top/Article/details/gtpfamudux.html

[U94] JS：箭头函数
来源：http://dali.0kj1m.cn/Article/details/gtyykugiii.html

const double = x => x * 2;
来源：http://dali.yangfankeji.com/Article/details/gtkabrnygm.html

[U95] JS：Promise 包装
来源：http://dali.haohaochexian.top/Article/details/gtnxilsnar.html

new Promise((resolve, reject) => {})
来源：http://dali.0kj1m.cn/Article/details/gtraogprbo.html

[U96] JS：async/await 与异常
来源：http://dali.iojbl.cn/Article/details/gtngrrunjv.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gtywdujrjm.html

[U97] JS：并发请求
来源：http://dali.yongpay.top/Article/details/gtwegbkftm.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnqzz.top/Article/details/gtgaixubrt.html

[U98] JS：fetch 带 JSON
来源：http://dali.guowangkeji.top/Article/details/gtpkyoelgg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xuanzx.com/Article/details/gtykriulom.html

[U99] JS：事件监听
来源：http://dali.birdmap.top/Article/details/gteebepdib.html

el.addEventListener("click", e => {})
来源：http://dali.cdnleiting.top/Article/details/gteylrkaem.html

[U100] JS：DOM 查询
来源：http://dali.hammf.cn/Article/details/gtakkmrotb.html

document.querySelector(".item")
来源：http://dali.cqqwz.cn/Article/details/gtuoasxdfe.html

[U101] JS：classList 操作
来源：http://dali.haohaochexian.top/Article/details/gttllqbddu.html

el.classList.toggle("active")
来源：http://dali.tian-w.cn/Article/details/gtbvcgycnb.html

[U102] JS：本地存储
来源：http://dali.redwolf501.top/Article/details/gtxwhwtwlu.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hnxiangtu.top/Article/details/gtcojzmqon.html

[U103] JS：定时器
来源：http://dali.nwbrower.top/Article/details/gtjmnuugsh.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hammf.cn/Article/details/gtuxpjblek.html

[U104] JS：防抖
来源：http://dali.9152youxi.cn/Article/details/gtetuxchmu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daria6918.cn/Article/details/gtovtxruly.html

[U105] JS：节流
来源：http://dali.shanyushiyangtech.top/Article/details/gtmndmtzuv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.snrcjt.cn/Article/details/gtubkxjvml.html

[U106] JS：日期格式化
来源：http://dali.shzxlz.cn/Article/details/gtjkemweya.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.quarkkingdee.top/Article/details/gtlujucxaw.html

[U107] JS：数字千分位
来源：http://dali.yuanzhike.top/Article/details/gtmtbvaupc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xuetiantiany.cn/Article/details/gtsavqdnnj.html

[U108] JS：随机整数
来源：http://dali.shzxlz.cn/Article/details/gtinvjmmfx.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.aizwys.cn/Article/details/gtunzhtyih.html

[U109] JS：数组分组
来源：http://dali.gzhubu.top/Article/details/gtukdvvcsm.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yj202588.top/Article/details/gtvlrwhetp.html

[U110] JS：数组分块
来源：http://dali.vqdsnc.cn/Article/details/gtahoawozg.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hongshengwenyu.top/Article/details/gthdlmgyzv.html

[U111] JS：对象转 Map
来源：http://dali.jinqigfzy.top/Article/details/gtmgdyhqpd.html

new Map(Object.entries(obj))
来源：http://dali.zhiwuduotai.top/Article/details/gtxaxacjdg.html

[U112] JS：字符串补位
来源：http://dali.sxryk.cn/Article/details/gtgoxnnlie.html

"7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gtvxywydpc.html

[U113] JS：正则替换全部
来源：http://dali.yj202588.top/Article/details/gttcahmtwt.html

s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtwrwgfpuq.html

[U114] JS：JSON 深比较
来源：http://dali.fzhhl.top/Article/details/gttncwztiq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gtntumhgku.html

[U115] JS：生成 UUID
来源：http://dali.redwolf501.top/Article/details/gtdllnvlnp.html

crypto.randomUUID()
来源：http://dali.aibaodan.cn/Article/details/gtyrqpbssb.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.smart0.xyz/Article/details/gtakbxyvwq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.fzhhl.top/Article/details/gtirgclwel.html

[U117] JS：单元测试
来源：http://dali.nwbrower.top/Article/details/gtjnyuhpko.html

npm i -D vitest;  npx vitest
来源：http://dali.dianchejie.cn/Article/details/gtwhqrodsy.html

[U118] JS：开发服务器
来源：http://dali.shanyushiyangkeji.top/Article/details/gttuwneovu.html

npm i -D vite;  npx vite
来源：http://dali.quarkkingdee.top/Article/details/gtedoafpwx.html

[U119] JS：生产构建
来源：http://dali.zhongyouzk.top/Article/details/gtiolqcmyh.html

npx vite build
来源：http://dali.gaohongyu789.top/Article/details/gttpyhvwrc.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.shuidangran.top/Article/details/gtzoxkhiwc.html

import.meta.env.VITE_API_URL
来源：http://dali.cdnleiting.top/Article/details/gtknaziyau.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtrxoengzx.html

统计汇总
来源：http://dali.zdqjudy.top/Article/details/gtxuimxzhm.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gthhdfuabl.html

按语言统计（条）：
来源：http://dali.xuanzx.com/Article/details/gtgragbnyt.html

Python ......... 252
来源：http://dali.bjfxy.top/Article/details/gtbeqreybv.html

PHP ............ 252
来源：http://dali.chenjidiqi.icu/Article/details/gtykxockok.html

JavaScript ..... 252
来源：http://dali.cdnleiting.top/Article/details/gtnwburwuq.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gtzzmaguia.html

Java ........... 212
来源：http://dali.ivvv.top/Article/details/gtbrwsyrlp.html

Go ............. 212
来源：http://dali.ydzc1.top/Article/details/gtsgrigwka.html

Ruby ........... 212
来源：http://dali.ehwqpu.com/Article/details/gtoeylonee.html

C# ............. 212
来源：http://dali.feifeiyinyue.top/Article/details/gtrnzzecml.html

C .............. 30
来源：http://dali.jinqigfzy.top/Article/details/gtgylowgzd.html

C++ ............ 30
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfxsqncwe.html

SQL ............ 90
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvvixeypu.html

Bash ........... 80
来源：http://dali.aibaodan.cn/Article/details/gtzniomnje.html

Kotlin ......... 15
来源：http://dali.sufxvd.cn/Article/details/gtfbnyycwe.html

Swift .......... 15
来源：http://dali.hnxiangtu.top/Article/details/gtqbxubadd.html

Lua ............ 10
来源：http://dali.yj202588.top/Article/details/gtitxfghlj.html

Perl ........... 10
来源：http://dali.jlsjyb.cn/Article/details/gtmdsdnpsj.html

Scala .......... 10
来源：http://dali.yonumen.top/Article/details/gtvzuvxehg.html

------------------------------------
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjtkbsofj.html

合计 ........... 2106 条
来源：http://dali.jinyuanbaomall.cn/Article/details/gtawtrgkhm.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gtyyfewmel.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.feifeiyinyue.top/Article/details/gtzphxfemw.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.cashguo.top/Article/details/gtnconihfd.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jlsjyb.cn/Article/details/gtbyukgazn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhengqikj.top/Article/details/gtnybaadqm.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.snrcjt.cn/Article/details/gtmmxwrdog.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.wangshuangyany.cn/Article/details/gttzqtiugb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.chenjidiqi.icu/Article/details/gtgipbpbiv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.cheryme.top/Article/details/gtbzprbgbr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangtech.top/Article/details/gtibianpox.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.tianlin.xyz/Article/details/gtmbiamwfm.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hysaishi.cn/Article/details/gtsyqirkzv.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.cheryme.top/Article/details/gtpguxrzhe.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcfifhxdm.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.sweek.top/Article/details/gtywyqbzeh.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gtazlqclfk.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgbfhasux.html

Q SQL 专题                              90
来源：http://dali.yj20258.top/Article/details/gtdowlcdgh.html

R Bash 专题                             80
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvraoflzi.html

S C / C++ 专题                          60
来源：http://dali.chenzaomai.com/Article/details/gtpquhudlu.html

T 其他语言补充                          60
来源：http://dali.sxryk.cn/Article/details/gtgsyopxmp.html

U 高频实用片段                         120
来源：http://dali.yanxiufei.cn/Article/details/gtmotuysad.html

------------------------------------
来源：http://dali.xylfe.cn/Article/details/gtctuoixie.html

合计                                  2106 条
来源：http://dali.gogol.net.cn/Article/details/gtpthidqll.html

--------------------------------------------------------------------------------
来源：http://dali.xinyue.icu/Article/details/gtzhcjixno.html

使用提醒
来源：http://dali.xinyue.icu/Article/details/gtpkneyimo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gtcrpzlagc.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.xuanzx.com/Article/details/gtnszyujvl.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.nanxinkj.top/Article/details/gtrsodsxcx.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.daxiang520.top/Article/details/gtbmuokujq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtysyvtkfh.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.guowangkeji.top/Article/details/gthkycfhbw.html

—— 文件结束 ——
来源：http://dali.daxiang520.top/Article/details/gtisshflot.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtjdlmxhqm.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jlsjyb.cn/Article/details/gtccerppot.html

Common Programming Examples Cheat Book
来源：http://dali.svipenyu.cn/Article/details/gtysfwxemn.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtbhvarjst.html

【收录内容】
来源：http://dali.tanke756.top/Article/details/gtyjiiznzv.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.chenzaomai.com/Article/details/gtpbfkvwom.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.guowangkeji.top/Article/details/gtriolnndl.html

SQL · Bash · C · C++
来源：http://dali.ppjwa.cn/Article/details/gtoljftuhx.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.shzxlz.cn/Article/details/gtzbvhdxav.html

【使用说明】
来源：http://dali.sysykeji.top/Article/details/gtzdjvubba.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.ydzc1.top/Article/details/gtvxlkcodu.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.birdmap.top/Article/details/gtbrdgfpdu.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgdydonql.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yj20258888.top/Article/details/gtmacxnvvb.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jlsjyb.cn/Article/details/gtidrqwtci.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.sysykeji.top/Article/details/gtlavswomf.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.andypj.xyz/Article/details/gtvsofscdx.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.chenjidiqi.icu/Article/details/gtyprtctjd.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhongyouzk.top/Article/details/gtvhbbsvbe.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.nanxuanxn.top/Article/details/gtapkgpomu.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jinqigfzy.top/Article/details/gtpmvatzby.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.ivvv.top/Article/details/gtiytduarm.html

【文件统计】
来源：http://dali.zhengqikj.top/Article/details/gtztxfszsg.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zdqjudy.top/Article/details/gtjzdkovqo.html

--------------------------------------------------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gtdmemobxa.html

目  录
来源：http://dali.xuetiantiany.cn/Article/details/gthqtafoox.html

--------------------------------------------------------------------------------
来源：http://dali.aibaodan.cn/Article/details/gtjlqavqeg.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yuxming.cn/Article/details/gtrflqfvoa.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtbvlsjoea.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtzazxqxld.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xinyue.icu/Article/details/gtkjpfwfll.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhengqikj.top/Article/details/gtndlpvbpz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.aibaodan.cn/Article/details/gtdrdixbmc.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.shzxlz.cn/Article/details/gtisinadah.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.kuanghao11.cn/Article/details/gtacotedau.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.tianlin.xyz/Article/details/gtpvigznht.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.daxiang520.top/Article/details/gtjmmhdtdk.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jqgufenzy.top/Article/details/gtiyeosmiu.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.gaohongyu789.top/Article/details/gtrbbkcpyj.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdhppqnag.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.snrcjt.cn/Article/details/gtyxeiitnb.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.sysykeji.top/Article/details/gtgqkpamvu.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.guannengcc.top/Article/details/gtypllypeo.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yj20258888.top/Article/details/gtfvaoooeh.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhengqikj.top/Article/details/gtzwjolwfc.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.cqqwz.cn/Article/details/gtmazzsjni.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangdashe.top/Article/details/gtxyakymre.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.quarkkingdee.top/Article/details/gtbvtzssda.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtcnbivdvq.html

A. 基础语法与类型
来源：http://dali.cucudq.cn/Article/details/gtkubhqgox.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtukqjtwxk.html

[A01] Hello World
来源：http://dali.shzxlz.cn/Article/details/gtrgdfhrqo.html

Py:   print("Hello, World!")
来源：http://dali.xuanzx.com/Article/details/gtfnaheczk.html

PHP:  echo "Hello, World!";
来源：http://dali.sweek.top/Article/details/gtiyseffek.html

JS:   console.log("Hello, World!");
来源：http://dali.meibo888.top/Article/details/gtwouollga.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhengqikj.top/Article/details/gtiikewkhj.html

Java: System.out.println("Hello, World!");
来源：http://dali.jinghuilouyu.cn/Article/details/gtsnthflhn.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcikhvfrf.html

Ruby: puts "Hello, World!"
来源：http://dali.jinqigfzy.top/Article/details/gtkejdiajh.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zdqjudy.top/Article/details/gtkugxupbn.html

[A02] 变量声明与赋值
来源：http://dali.yuxming.cn/Article/details/gtfdlqwzxy.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.hnxiangtu.top/Article/details/gtrnxoylew.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.nwbrower.top/Article/details/gtjeuassju.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.xylfe.cn/Article/details/gtvujnwmbd.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.0kj1m.cn/Article/details/gtqmwzesgn.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.haohaochexian.top/Article/details/gtzpdqehwc.html

Go:   name := "Alex"; age := 20
来源：http://dali.aibaodan.cn/Article/details/gtoapjteby.html

Ruby: name = "Alex"; age = 20
来源：http://dali.tanke756.top/Article/details/gtzvhkakmz.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.gaohongyu789.top/Article/details/gtqkrnxypt.html

[A03] 常量定义
来源：http://dali.yonumen.top/Article/details/gtksocjpiw.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jqgfzy.top/Article/details/gtjwfjtyqm.html

PHP:  const PI = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gturgmmtrn.html

JS:   const PI = 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gtkhljwlxv.html

TS:   const PI: number = 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gtakjfaycq.html

Java: static final double PI = 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gtazvrzenb.html

Go:   const PI = 3.14159
来源：http://dali.cheryme.top/Article/details/gtmpqilfpg.html

Ruby: PI = 3.14159
来源：http://dali.hysaishi.cn/Article/details/gtfudkbznk.html

C#:   const double PI = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gtqmpytfgq.html

[A04] 判断变量类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtttsliahj.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yj20258.top/Article/details/gtuafmsvjr.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.wangdashe.top/Article/details/gtccstnmyn.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.gotoacloud.top/Article/details/gtoasskzvn.html

TS:   typeof x; x instanceof Date
来源：http://dali.chenjidiqi.icu/Article/details/gtoewchrco.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.wangshuangyany.cn/Article/details/gtytaxfcmc.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.cheryme.top/Article/details/gtutthcfhi.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jinqigfzy.top/Article/details/gttxkdbmzt.html

C#:   x.GetType().Name; x is int
来源：http://dali.svipenyu.cn/Article/details/gtqmudsomc.html

[A05] 整数除法与取模
来源：http://dali.ivvv.top/Article/details/gtsmozmuzk.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfazyekai.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.quarkkingdee.top/Article/details/gtwjhbxtom.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xziqi.cn/Article/details/gtglsedzpx.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.haohaochexian.top/Article/details/gtdhwkdvkx.html

Java: 7 / 2; 7 % 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxooxzdea.html

Go:   7 / 2; 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gttpwzeits.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yj20258888.top/Article/details/gtbwdpuciq.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gtbkqhtgid.html

[A06] 字符串转数字
来源：http://dali.sxryk.cn/Article/details/gtszoirvlw.html

Py:   int("42"); float("3.14")
来源：http://dali.chenlongwang.top/Article/details/gttuolzcvr.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.sufxvd.cn/Article/details/gtjlqademc.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jianghu66.top/Article/details/gtepdnnkmk.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.vqdsnc.cn/Article/details/gtrlprgbpc.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.gogol.net.cn/Article/details/gtanevrbuo.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.ppjwa.cn/Article/details/gtwtyonzvu.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.9152youxi.cn/Article/details/gtyufstwum.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jqgfzy.top/Article/details/gtgrsnvpxv.html

[A07] 数字转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtkjzqxboe.html

Py:   str(42)
来源：http://dali.yanxiufei.cn/Article/details/gtpwdvqlil.html

PHP:  (string) 42; strval(42)
来源：http://dali.yvedp.cn/Article/details/gtrhpbkmcg.html

JS:   String(42); (42).toString()
来源：http://dali.cashguo.top/Article/details/gthmyxjpdw.html

TS:   String(42)
来源：http://dali.birdmap.top/Article/details/gtrprwiwph.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.gaohongyu789.top/Article/details/gtkindoifv.html

Go:   strconv.Itoa(42)
来源：http://dali.birdmap.top/Article/details/gtmhwxdbce.html

Ruby: 42.to_s
来源：http://dali.yonumen.top/Article/details/gtroxqayex.html

C#:   42.ToString()
来源：http://dali.gogol.net.cn/Article/details/gtafyvmdcu.html

[A08] 取整与四舍五入
来源：http://dali.0kj1m.cn/Article/details/gtupfzlphq.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.tanke756.top/Article/details/gthnozrdge.html


<!-- 参考信息 -->