代发 wailian999

[U53] PHP：空合并运算符
来源：http://dali.kuanghao11.cn/Article/details/gtlpjvmaaz.html

$v = $a ?? $b ?? "default";
来源：http://dali.tian-w.cn/Article/details/gtvxcxwymq.html

[U54] PHP：空安全调用
来源：http://dali.xuetiantiany.cn/Article/details/gtmthjbxtp.html

$obj?->method()
来源：http://dali.shuidangran.top/Article/details/gtdqtmgzfo.html

[U55] PHP：match 表达式
来源：http://dali.chenzaomai.com/Article/details/gtogfwnecz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.haohaochexian.top/Article/details/gtkbtdfsav.html

[U56] PHP：命名参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkagpsurd.html

f(a: 1, b: 2)
来源：http://dali.dianchejie.cn/Article/details/gtuvpcuosp.html

[U57] PHP：字符串插值
来源：http://dali.gzhubu.top/Article/details/gtcgbcsrsq.html

"值: {$a}"
来源：http://dali.nanxinkj.top/Article/details/gtpzliruik.html

[U58] PHP：数组三件套
来源：http://dali.zycfv.cn/Article/details/gtthkcvarc.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.havefunace.top/Article/details/gtfyzhnkvx.html

[U59] PHP：自定义排序
来源：http://dali.xziqi.cn/Article/details/gtmlmbwmwl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guannengcc.top/Article/details/gtfqaaxyez.html

[U60] PHP：JSON 编解码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjitprirg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yueranfly.top/Article/details/gtjpviwxpv.html

[U61] PHP：正则
来源：http://dali.bjfxy.top/Article/details/gtuuxuzmym.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.sweek.top/Article/details/gtxiloqnzi.html

[U62] PHP：日期对象
来源：http://dali.xylfe.cn/Article/details/gtxwpucorn.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.pycfn.com/Article/details/gttfvwuzej.html

[U63] PHP：文件读写
来源：http://dali.aizwys.cn/Article/details/gtxwahydtp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.gzhubu.top/Article/details/gtytgyymsv.html

[U64] PHP：目录遍历
来源：http://dali.zhixingplan.top/Article/details/gtqutyzkfb.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.quarkkingdee.top/Article/details/gtxdwtveej.html

[U65] PHP：会话
来源：http://dali.xuanzx.com/Article/details/gtzvgoiftx.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtbpbocpta.html

[U66] PHP：设置 Cookie
来源：http://dali.jiagoushi.top/Article/details/gturoaqbdy.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhoulong.xyz/Article/details/gtpjzijnxo.html

[U67] PHP：处理文件上传
来源：http://dali.zycfv.cn/Article/details/gtutmxrbpq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yj202588.top/Article/details/gtgvztpzob.html

[U68] PHP：PDO 连接
来源：http://dali.xziqi.cn/Article/details/gtsqxelrni.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiptolfnp.html

[U69] PHP：PDO 预处理
来源：http://dali.zhixingplan.top/Article/details/gtcvuxfcfx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.9152youxi.cn/Article/details/gtyvhqffnj.html

[U70] PHP：PDO 事务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvatwcluh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.feifeiyinyue.top/Article/details/gtusuyttbj.html

[U71] PHP：抛出异常
来源：http://dali.chenlongwang.top/Article/details/gttxzeeloe.html

throw new RuntimeException("失败", 500);
来源：http://dali.havefunace.top/Article/details/gtljxqgabq.html

[U72] PHP：写错误日志
来源：http://dali.daxiang520.top/Article/details/gtmpsekkix.html

error_log("失败: " . $e->getMessage());
来源：http://dali.smart0.xyz/Article/details/gtvqzisklt.html

[U73] PHP：读取 ini 配置
来源：http://dali.cucudq.cn/Article/details/gtmwxqxsyp.html

parse_ini_file("config.ini", true)
来源：http://dali.aibaodan.cn/Article/details/gtoiqfbvld.html

[U74] PHP：读取环境变量
来源：http://dali.hysaishi.cn/Article/details/gtgzjkxqml.html

getenv("APP_ENV") ?: "production"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbtqqpvxp.html

[U75] PHP：依赖注入
来源：http://dali.ivvv.top/Article/details/gtyakzsybw.html

composer require psr/container
来源：http://dali.ybcxt.top/Article/details/gtetwedzbj.html

[U76] PHP：简单路由
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqdjieoaa.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.pycfn.com/Article/details/gttdgfwizi.html

[U77] PHP：模板渲染
来源：http://dali.fzhhl.top/Article/details/gtylmlweeu.html

composer require twig/twig
来源：http://dali.pengpengdd.cyou/Article/details/gtvbawlvoj.html

[U78] PHP：单元测试
来源：http://dali.yj202588.top/Article/details/gtgfphjpxu.html

composer require --dev phpunit/phpunit
来源：http://dali.shuidangran.top/Article/details/gtfqjqmujb.html

[U79] PHP：静态分析
来源：http://dali.ppjwa.cn/Article/details/gtlgycpneo.html

composer require --dev phpstan/phpstan
来源：http://dali.ybcxt.top/Article/details/gtjiluwlio.html

[U80] PHP：代码规范修复
来源：http://dali.yanxiufei.cn/Article/details/gtpstndscm.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhongyouzk.top/Article/details/gtkzryypgr.html

[U81] JS：初始化项目
来源：http://dali.havefunace.top/Article/details/gtjxbdpneq.html

npm init -y;  npm i express
来源：http://dali.hnqzz.top/Article/details/gtbzvbinao.html

[U82] JS：package.json 脚本
来源：http://dali.ywan-chungtsiang.top/Article/details/gttpxkenjr.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gtnboiuklg.html

[U83] JS：ES Module 导入导出
来源：http://dali.gaohongyu789.top/Article/details/gtmplbfgin.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yvedp.cn/Article/details/gtirzanrzw.html

[U84] JS：CommonJS 写法
来源：http://dali.yueranfly.top/Article/details/gttgcukacy.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.shanyushiyangtech.top/Article/details/gtrlcbelgk.html

[U85] JS：可选链
来源：http://dali.hnqzz.top/Article/details/gtkahpkzos.html

a?.b?.c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhcyorbq.html

[U86] JS：空值合并
来源：http://dali.andypj.xyz/Article/details/gtgdiagnnj.html

a ?? b
来源：http://dali.gaohongyu789.top/Article/details/gtauxkdury.html

[U87] JS：解构默认值
来源：http://dali.sysykeji.top/Article/details/gtngevqcfy.html

const { a = 1, b = 2 } = obj;
来源：http://dali.sxryk.cn/Article/details/gtnfrtulkd.html

[U88] JS：对象展开合并
来源：http://dali.jianghu66.top/Article/details/gtjkmwxshs.html

{ ...a, ...b }
来源：http://dali.cdnleiting.top/Article/details/gteqkmdhhd.html

[U89] JS：数组去重
来源：http://dali.bjfxy.top/Article/details/gtnygthkyy.html

[...new Set(arr)]
来源：http://dali.jqgfzy.top/Article/details/gtfantlimg.html

[U90] JS：数字数组排序
来源：http://dali.svipenyu.cn/Article/details/gtnoxjvdgm.html

[...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gtqoxanwaw.html

[U91] JS：对象键值遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtfmgxqbvy.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.xylfe.cn/Article/details/gtlkihrilh.html

[U92] JS：深拷贝
来源：http://dali.dianchejie.cn/Article/details/gteghfynst.html

structuredClone(obj)
来源：http://dali.bjfxy.top/Article/details/gtkkcxkzrj.html

[U93] JS：模板字符串
来源：http://dali.jinqigfzy.top/Article/details/gtkloeyyrx.html

`共 ${n} 条`
来源：http://dali.chenzaomai.com/Article/details/gtbuduptxr.html

[U94] JS：箭头函数
来源：http://dali.svipenyu.cn/Article/details/gttsghsxev.html

const double = x => x * 2;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvqtpzvhg.html

[U95] JS：Promise 包装
来源：http://dali.chenzaomai.com/Article/details/gttflgadaw.html

new Promise((resolve, reject) => {})
来源：http://dali.hammf.cn/Article/details/gtrjdloyyl.html

[U96] JS：async/await 与异常
来源：http://dali.cheryme.top/Article/details/gtichlnccs.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gtoqcjwage.html

[U97] JS：并发请求
来源：http://dali.ivvv.top/Article/details/gtpnnyzllr.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhengqikj.top/Article/details/gtekqdtdkq.html

[U98] JS：fetch 带 JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gtlijjfpcx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.wangdashe.top/Article/details/gtmitudqcu.html

[U99] JS：事件监听
来源：http://dali.wangdashe.top/Article/details/gtkekmgios.html

el.addEventListener("click", e => {})
来源：http://dali.quarkkingdee.top/Article/details/gtskfeinsh.html

[U100] JS：DOM 查询
来源：http://dali.yueranfly.top/Article/details/gtdgqpzdyc.html

document.querySelector(".item")
来源：http://dali.birdmap.top/Article/details/gtlkpndrol.html

[U101] JS：classList 操作
来源：http://dali.havefunace.top/Article/details/gtxvyzhbqh.html

el.classList.toggle("active")
来源：http://dali.daria6918.cn/Article/details/gtteusynpc.html

[U102] JS：本地存储
来源：http://dali.jianghu66.top/Article/details/gtqonbcjhs.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.nanxuanxn.top/Article/details/gtyoezrwkb.html

[U103] JS：定时器
来源：http://dali.jinqigfzy.top/Article/details/gttwuoklwp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cucudq.cn/Article/details/gtufqrbjym.html

[U104] JS：防抖
来源：http://dali.tanke756.top/Article/details/gtojshdbfg.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj202588.top/Article/details/gtjavbvtwq.html

[U105] JS：节流
来源：http://dali.shanyushiyangtech.top/Article/details/gtnzridvke.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yvedp.cn/Article/details/gtdwyqinse.html

[U106] JS：日期格式化
来源：http://dali.cheryme.top/Article/details/gtcwscbdil.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ehwqpu.com/Article/details/gtcmvwxhyi.html

[U107] JS：数字千分位
来源：http://dali.kuanghao11.cn/Article/details/gtarfjrqrt.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.chenlongwang.top/Article/details/gtlkkyboxo.html

[U108] JS：随机整数
来源：http://dali.zycfv.cn/Article/details/gtvfymyejg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.smart0.xyz/Article/details/gtzlivrezw.html

[U109] JS：数组分组
来源：http://dali.9152youxi.cn/Article/details/gtzeeamjel.html

Object.groupBy(arr, x => x.type)
来源：http://dali.smart0.xyz/Article/details/gttslxnbcs.html

[U110] JS：数组分块
来源：http://dali.wangshuangyany.cn/Article/details/gtkyqzwfbi.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xuetiantiany.cn/Article/details/gtxvuqjxzh.html

[U111] JS：对象转 Map
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvblydup.html

new Map(Object.entries(obj))
来源：http://dali.feifeiyinyue.top/Article/details/gtooywxscg.html

[U112] JS：字符串补位
来源：http://dali.sweek.top/Article/details/gtflqcwdom.html

"7".padStart(3, "0")
来源：http://dali.yueranfly.top/Article/details/gthfglbief.html

[U113] JS：正则替换全部
来源：http://dali.yuanzhike.top/Article/details/gtclqshzxo.html

s.replaceAll("a", "b")
来源：http://dali.yj20258.top/Article/details/gtenmutoog.html

[U114] JS：JSON 深比较
来源：http://dali.guowangkeji.top/Article/details/gtvgdhbhgi.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.9152youxi.cn/Article/details/gtpmwhngyp.html

[U115] JS：生成 UUID
来源：http://dali.guannengcc.top/Article/details/gtbgolziib.html

crypto.randomUUID()
来源：http://dali.zhiwuduotai.top/Article/details/gtudyjuwfk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.c1oappe.top/Article/details/gthxbkxagz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.shzxlz.cn/Article/details/gtzehfojpz.html

[U117] JS：单元测试
来源：http://dali.feifeiyinyue.top/Article/details/gttyfxfxzd.html

npm i -D vitest;  npx vitest
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthuzaniha.html

[U118] JS：开发服务器
来源：http://dali.shanyushiyangtech.top/Article/details/gtqwjmsutw.html

npm i -D vite;  npx vite
来源：http://dali.chenlongwang.top/Article/details/gtnafppldz.html

[U119] JS：生产构建
来源：http://dali.vqdsnc.cn/Article/details/gteypslshv.html

npx vite build
来源：http://dali.tanke756.top/Article/details/gtksjumyps.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.kuanghao11.cn/Article/details/gtmmdnvqjz.html

import.meta.env.VITE_API_URL
来源：http://dali.havefunace.top/Article/details/gttezskfcb.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gthklpkhkd.html

统计汇总
来源：http://dali.daxiang520.top/Article/details/gtxyyxuskv.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtimhzjvdq.html

按语言统计（条）：
来源：http://dali.haohaochexian.top/Article/details/gtiwldccdn.html

Python ......... 252
来源：http://dali.shzxlz.cn/Article/details/gtwfoohyyr.html

PHP ............ 252
来源：http://dali.xuanzx.com/Article/details/gtdplimpmr.html

JavaScript ..... 252
来源：http://dali.aizwys.cn/Article/details/gtajjpsqec.html

TypeScript ..... 212
来源：http://dali.aibaodan.cn/Article/details/gtdgowkisr.html

Java ........... 212
来源：http://dali.zhoulong.xyz/Article/details/gtpnaxcrld.html

Go ............. 212
来源：http://dali.hysaishi.cn/Article/details/gtrrykhtyn.html

Ruby ........... 212
来源：http://dali.ivvv.top/Article/details/gtcfgxbgys.html

C# ............. 212
来源：http://dali.mhx1999.top/Article/details/gtgqbmfpvu.html

C .............. 30
来源：http://dali.zhiwuduotai.top/Article/details/gthhxnhhjo.html

C++ ............ 30
来源：http://dali.xylfe.cn/Article/details/gtxxzyhdbn.html

SQL ............ 90
来源：http://dali.hammf.cn/Article/details/gtrdcslnfc.html

Bash ........... 80
来源：http://dali.gaohongyu789.top/Article/details/gtteawqxhb.html

Kotlin ......... 15
来源：http://dali.pengpengdd.cyou/Article/details/gtbrgrigpp.html

Swift .......... 15
来源：http://dali.jinqigfzy.top/Article/details/gtllwtnfzo.html

Lua ............ 10
来源：http://dali.yanxiufei.cn/Article/details/gtephhyiqa.html

Perl ........... 10
来源：http://dali.meibo888.top/Article/details/gtnnadzigm.html

Scala .......... 10
来源：http://dali.yangfankeji.com/Article/details/gtsqvjejey.html

------------------------------------
来源：http://dali.mhx1999.top/Article/details/gtrkwkuxkj.html

合计 ........... 2106 条
来源：http://dali.hammf.cn/Article/details/gtckhmbmad.html

按章节统计：
来源：http://dali.wangdashe.top/Article/details/gtvdzljvqb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.chenzaomai.com/Article/details/gthqvocyay.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.316326.xyz/Article/details/gteimjddok.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shzxlz.cn/Article/details/gtqglfarui.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jqgfzy.top/Article/details/gtsonrbvxd.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.0kj1m.cn/Article/details/gtwlqyrutr.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jqgfzy.top/Article/details/gtqlinubzo.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.feifeiyinyue.top/Article/details/gtocwgwqzq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.chenlongwang.top/Article/details/gtxbzdeqzj.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yj20258.top/Article/details/gttyytcpux.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zdqjudy.top/Article/details/gtljpfnfje.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangtech.top/Article/details/gteirrflcm.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.snrcjt.cn/Article/details/gtvndvsgas.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jlsjyb.cn/Article/details/gtulqqidke.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.dianchejie.cn/Article/details/gtiwxxcntl.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.9152youxi.cn/Article/details/gtcvzruczw.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yuanzhike.top/Article/details/gthffwqhyj.html

Q SQL 专题                              90
来源：http://dali.xuanzx.com/Article/details/gttfvjagut.html

R Bash 专题                             80
来源：http://dali.nanxuanxn.top/Article/details/gthcbtyhez.html

S C / C++ 专题                          60
来源：http://dali.hnxiangtu.top/Article/details/gtwmnrwlkk.html

T 其他语言补充                          60
来源：http://dali.pycfn.com/Article/details/gtmxmuboya.html

U 高频实用片段                         120
来源：http://dali.andypj.xyz/Article/details/gtcmywwcrq.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gtzxamkawc.html

合计                                  2106 条
来源：http://dali.wangdashe.top/Article/details/gtuvskwoco.html

--------------------------------------------------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gtkegmnqrn.html

使用提醒
来源：http://dali.wangdashe.top/Article/details/gttgajzwfa.html

--------------------------------------------------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gtazloseup.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.wangdashe.top/Article/details/gtmwlpzidt.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.birdmap.top/Article/details/gthnauixfm.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.pycfn.com/Article/details/gtwoqhdyqv.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.guannengcc.top/Article/details/gtugvkherk.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.ywan-chungtsiang.top/Article/details/gttxduohyj.html

—— 文件结束 ——
来源：http://dali.hfpthk.cn/Article/details/gthupgnwvl.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtlulqjqcx.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxhyddpll.html

Common Programming Examples Cheat Book
来源：http://dali.daxiang520.top/Article/details/gtoivofjmx.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtbzehhxpr.html

【收录内容】
来源：http://dali.yangfankeji.com/Article/details/gteskufnbd.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hammf.cn/Article/details/gtcezljclf.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.havefunace.top/Article/details/gtzpltnrsv.html

SQL · Bash · C · C++
来源：http://dali.aibaodan.cn/Article/details/gtkgowzirt.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.pycfn.com/Article/details/gthqfnlfcb.html

【使用说明】
来源：http://dali.sysykeji.top/Article/details/gtmsifzzfb.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.gogol.net.cn/Article/details/gtczhydpvl.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.xziqi.cn/Article/details/gtfktmbggx.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hysaishi.cn/Article/details/gtnmhgzsli.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.dianchejie.cn/Article/details/gtfeswykxk.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.aizwys.cn/Article/details/gthfnjljnn.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zdqjudy.top/Article/details/gtppzogswd.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jiagoushi.top/Article/details/gtgfoecuen.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.nwbrower.top/Article/details/gtiwyzgdwk.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jinyuanbaomall.cn/Article/details/gtulzbrhca.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.meibo888.top/Article/details/gtvclprfjp.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.haohaochexian.top/Article/details/gtvhftehnc.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.xinyue.icu/Article/details/gtuwzmywfj.html

【文件统计】
来源：http://dali.meibo888.top/Article/details/gtucfmhson.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.shangyingyoupin.top/Article/details/gtimeekkoh.html

--------------------------------------------------------------------------------
来源：http://dali.kuanghao11.cn/Article/details/gtwwhbraag.html

目  录
来源：http://dali.meibo888.top/Article/details/gtujuhpnob.html

--------------------------------------------------------------------------------
来源：http://dali.redwolf501.top/Article/details/gtwtphsjid.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.ydzc1.top/Article/details/gtqknvonhr.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtccizllgi.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.birdmap.top/Article/details/gtsclpwiza.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jqgufenzy.top/Article/details/gtuttjdymh.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.smart0.xyz/Article/details/gtlnlefbhj.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.birdmap.top/Article/details/gtqesikexr.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.cheryme.top/Article/details/gthxrbbvaa.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.cucudq.cn/Article/details/gtiahcjlel.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.xuanzx.com/Article/details/gtakiearfk.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.316326.xyz/Article/details/gtdweoipls.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jqgufenzy.top/Article/details/gtuabwbfzk.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jiagoushi.top/Article/details/gtknbylugj.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jlsjyb.cn/Article/details/gttqgkzxmo.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.daxiang520.top/Article/details/gtkqgwgkmf.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.iojbl.cn/Article/details/gtuxkgsegw.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.tianlin.xyz/Article/details/gtfrbmzkwr.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jianghu66.top/Article/details/gthujqegdy.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yueranfly.top/Article/details/gtcfyoupab.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jqgfzy.top/Article/details/gtednaaouz.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yonumen.top/Article/details/gtiuzuupgk.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.hywenlv.cn/Article/details/gtruugrbxt.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdhdisbwd.html

A. 基础语法与类型
来源：http://dali.pengpengdd.cyou/Article/details/gtinhibkrm.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwsidrvs.html

[A01] Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtcgmwwomt.html

Py:   print("Hello, World!")
来源：http://dali.gaohongyu789.top/Article/details/gtlzdhprdg.html

PHP:  echo "Hello, World!";
来源：http://dali.wangdashe.top/Article/details/gtiqfdacpw.html

JS:   console.log("Hello, World!");
来源：http://dali.ydzc1.top/Article/details/gtmspzloie.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.tianlin.xyz/Article/details/gtpkrkrngr.html

Java: System.out.println("Hello, World!");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbeqchcma.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.redwolf501.top/Article/details/gtvbmaaqyl.html

Ruby: puts "Hello, World!"
来源：http://dali.cashguo.top/Article/details/gtwahhdrsm.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.cqqwz.cn/Article/details/gtdkwybiex.html

[A02] 变量声明与赋值
来源：http://dali.chenlongwang.top/Article/details/gtzrskhzkk.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.haohaochexian.top/Article/details/gturlvktou.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jiagoushi.top/Article/details/gthijqsmfs.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.chenzaomai.com/Article/details/gtwflsaicv.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.cashguo.top/Article/details/gtqiiwtaid.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.quarkkingdee.top/Article/details/gttnxmtdap.html

Go:   name := "Alex"; age := 20
来源：http://dali.hywenlv.cn/Article/details/gtvwodbgxf.html

Ruby: name = "Alex"; age = 20
来源：http://dali.gaohongyu789.top/Article/details/gtikovrqnc.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.hongshengwenyu.top/Article/details/gtghaagflt.html

[A03] 常量定义
来源：http://dali.wangshuangyany.cn/Article/details/gtyvsvjuxg.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.ydzc1.top/Article/details/gtyxgltrwy.html

PHP:  const PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gtjxerekma.html

JS:   const PI = 3.14159;
来源：http://dali.mhx1999.top/Article/details/gtxycydrfy.html

TS:   const PI: number = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gtjkljabnf.html

Java: static final double PI = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gtwhxloqxe.html

Go:   const PI = 3.14159
来源：http://dali.hysaishi.cn/Article/details/gtdwhuxmpn.html

Ruby: PI = 3.14159
来源：http://dali.jinqigfzy.top/Article/details/gtqkgonfot.html

C#:   const double PI = 3.14159;
来源：http://dali.havefunace.top/Article/details/gtqxahmkls.html

[A04] 判断变量类型
来源：http://dali.zhoulong.xyz/Article/details/gthrvgzord.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.hongshengwenyu.top/Article/details/gtefntdqju.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.sxryk.cn/Article/details/gtojqahlpi.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.meibo888.top/Article/details/gtbmjuocqf.html

TS:   typeof x; x instanceof Date
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoseeckhk.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.nwbrower.top/Article/details/gtxalajrid.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.xylfe.cn/Article/details/gtgelozvpj.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxnrordzy.html

C#:   x.GetType().Name; x is int
来源：http://dali.pycfn.com/Article/details/gticcnalfq.html

[A05] 整数除法与取模
来源：http://dali.cucudq.cn/Article/details/gtldpjpzuh.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.havefunace.top/Article/details/gttliuhork.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.chenjidiqi.icu/Article/details/gtghpyvecy.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gtlodiuaxi.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ivvv.top/Article/details/gturzbznnd.html

Java: 7 / 2; 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gtfznimrco.html

Go:   7 / 2; 7 % 2
来源：http://dali.gzhubu.top/Article/details/gtcqomdozk.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.tanke756.top/Article/details/gtuhvcgszp.html

C#:   7 / 2; 7 % 2
来源：http://dali.jianghu66.top/Article/details/gtmygqvaug.html

[A06] 字符串转数字
来源：http://dali.yuxming.cn/Article/details/gtrupgqcxh.html

Py:   int("42"); float("3.14")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwtinolo.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.daria6918.cn/Article/details/gtzwotuhns.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.feifeiyinyue.top/Article/details/gtnrlhixzl.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.xinyue.icu/Article/details/gtcisyujjy.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yuanzhike.top/Article/details/gthfovpyhh.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.hongshengwenyu.top/Article/details/gtsptncxuv.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.guowangkeji.top/Article/details/gtddpcmzyi.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yongpay.top/Article/details/gtlvejqcht.html

[A07] 数字转字符串
来源：http://dali.meibo888.top/Article/details/gtifaejdjw.html

Py:   str(42)
来源：http://dali.fengsongda.top/Article/details/gtlbaegppn.html

PHP:  (string) 42; strval(42)
来源：http://dali.yuanzhike.top/Article/details/gtcyyzamrv.html


<!-- 参考信息 -->