代发 wailian999

[U55] PHP：match 表达式
来源：http://dali.ppjwa.cn/Article/details/gtxpvdbeup.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.vqdsnc.cn/Article/details/gtwpntsyfh.html

[U56] PHP：命名参数
来源：http://dali.yueranfly.top/Article/details/gtirmnefva.html

f(a: 1, b: 2)
来源：http://dali.jiagoushi.top/Article/details/gtqrpbnygw.html

[U57] PHP：字符串插值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtamkbqrfa.html

"值: {$a}"
来源：http://dali.shangyingyoupin.top/Article/details/gtugzhnhxh.html

[U58] PHP：数组三件套
来源：http://dali.yvedp.cn/Article/details/gtxueoslwo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.xinyue.icu/Article/details/gtuwydybag.html

[U59] PHP：自定义排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbpvwrsaq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcrdizvom.html

[U60] PHP：JSON 编解码
来源：http://dali.zhixingplan.top/Article/details/gtcaspzcwg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.dashuyun.cn/Article/details/gtrrqvpstp.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gtbivzljcx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhixingplan.top/Article/details/gtadnwyego.html

[U62] PHP：日期对象
来源：http://dali.chenzaomai.com/Article/details/gtomvdwmyv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.9152youxi.cn/Article/details/gtnxqywgxt.html

[U63] PHP：文件读写
来源：http://dali.svipenyu.cn/Article/details/gtcuereoas.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yueranfly.top/Article/details/gtuaylzarr.html

[U64] PHP：目录遍历
来源：http://dali.xziqi.cn/Article/details/gtcynhtqip.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ybcxt.top/Article/details/gtqflxaglj.html

[U65] PHP：会话
来源：http://dali.snrcjt.cn/Article/details/gtwwmqpuxs.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jianghu66.top/Article/details/gtprkxrixz.html

[U66] PHP：设置 Cookie
来源：http://dali.yuxming.cn/Article/details/gtiraldpsj.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.birdmap.top/Article/details/gtgfjyvqur.html

[U67] PHP：处理文件上传
来源：http://dali.zhixingplan.top/Article/details/gtiesmrrnl.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.nanxinkj.top/Article/details/gtmrysgtln.html

[U68] PHP：PDO 连接
来源：http://dali.jianghu66.top/Article/details/gtqbsxfqxy.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.daxiang520.top/Article/details/gtjqlpggmd.html

[U69] PHP：PDO 预处理
来源：http://dali.ppjwa.cn/Article/details/gtomcuynrq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yuxming.cn/Article/details/gthwvqmtxq.html

[U70] PHP：PDO 事务
来源：http://dali.yangfankeji.com/Article/details/gtyggiefmj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.dashuyun.cn/Article/details/gtkauukziz.html

[U71] PHP：抛出异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtagaeiojz.html

throw new RuntimeException("失败", 500);
来源：http://dali.ppjwa.cn/Article/details/gtylfiuzoe.html

[U72] PHP：写错误日志
来源：http://dali.xziqi.cn/Article/details/gtwknpubow.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yj20258.top/Article/details/gtdgevvmoo.html

[U73] PHP：读取 ini 配置
来源：http://dali.yj20258888.top/Article/details/gtqnzbsmvn.html

parse_ini_file("config.ini", true)
来源：http://dali.bjfxy.top/Article/details/gtmxebkrsy.html

[U74] PHP：读取环境变量
来源：http://dali.gogol.net.cn/Article/details/gtesjcklou.html

getenv("APP_ENV") ?: "production"
来源：http://dali.sysykeji.top/Article/details/gtoyiplvvk.html

[U75] PHP：依赖注入
来源：http://dali.cashguo.top/Article/details/gtjfkbpnhs.html

composer require psr/container
来源：http://dali.shanyushiyangtech.top/Article/details/gtdpcageza.html

[U76] PHP：简单路由
来源：http://dali.hfpthk.cn/Article/details/gtpsvdirtd.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.nanxuanxn.top/Article/details/gtsrjughfr.html

[U77] PHP：模板渲染
来源：http://dali.zhoulong.xyz/Article/details/gtivcqddmh.html

composer require twig/twig
来源：http://dali.meibo888.top/Article/details/gtazcoydvo.html

[U78] PHP：单元测试
来源：http://dali.feifeiyinyue.top/Article/details/gtdjhifuft.html

composer require --dev phpunit/phpunit
来源：http://dali.yvedp.cn/Article/details/gtgyukokxq.html

[U79] PHP：静态分析
来源：http://dali.nwbrower.top/Article/details/gtavmewbtx.html

composer require --dev phpstan/phpstan
来源：http://dali.ybcxt.top/Article/details/gtpjsuueaq.html

[U80] PHP：代码规范修复
来源：http://dali.nanxinkj.top/Article/details/gtjzefgiuz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.nwbrower.top/Article/details/gtefosfrkb.html

[U81] JS：初始化项目
来源：http://dali.nanxinkj.top/Article/details/gtewcfqqiw.html

npm init -y;  npm i express
来源：http://dali.ivvv.top/Article/details/gtembefgfh.html

[U82] JS：package.json 脚本
来源：http://dali.shzxlz.cn/Article/details/gtygjhrosx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.cdnleiting.top/Article/details/gtkfhcobxu.html

[U83] JS：ES Module 导入导出
来源：http://dali.tanke756.top/Article/details/gtbnjdweos.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.smart0.xyz/Article/details/gtwjxfkbwe.html

[U84] JS：CommonJS 写法
来源：http://dali.hongshengwenyu.top/Article/details/gtcjqibmbz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.daria6918.cn/Article/details/gtilkpevkc.html

[U85] JS：可选链
来源：http://dali.tianlin.xyz/Article/details/gtynivlnis.html

a?.b?.c
来源：http://dali.sxryk.cn/Article/details/gtplfdibfl.html

[U86] JS：空值合并
来源：http://dali.gogol.net.cn/Article/details/gtytzyqxzq.html

a ?? b
来源：http://dali.pengpengdd.cyou/Article/details/gthoknynzc.html

[U87] JS：解构默认值
来源：http://dali.pengpengdd.cyou/Article/details/gtpppjenit.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hywenlv.cn/Article/details/gtsarurdek.html

[U88] JS：对象展开合并
来源：http://dali.jiagoushi.top/Article/details/gtcepjzkje.html

{ ...a, ...b }
来源：http://dali.gaohongyu789.top/Article/details/gtzfvwylsk.html

[U89] JS：数组去重
来源：http://dali.jinqigfzy.top/Article/details/gtqcphqqmv.html

[...new Set(arr)]
来源：http://dali.zhoulong.xyz/Article/details/gtvzbpmmhn.html

[U90] JS：数字数组排序
来源：http://dali.cqqwz.cn/Article/details/gtydstymtn.html

[...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gtsoeudxod.html

[U91] JS：对象键值遍历
来源：http://dali.hammf.cn/Article/details/gtdtbqsjgc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.sxryk.cn/Article/details/gtinxjdmwj.html

[U92] JS：深拷贝
来源：http://dali.ehwqpu.com/Article/details/gttiqmbwkd.html

structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtbmckdijm.html

[U93] JS：模板字符串
来源：http://dali.sufxvd.cn/Article/details/gtogttlnqc.html

`共 ${n} 条`
来源：http://dali.cashguo.top/Article/details/gtaxfwhryh.html

[U94] JS：箭头函数
来源：http://dali.daria6918.cn/Article/details/gtdhtgdtol.html

const double = x => x * 2;
来源：http://dali.wangshuangyany.cn/Article/details/gtslftywvr.html

[U95] JS：Promise 包装
来源：http://dali.zycfv.cn/Article/details/gtzmwxeckg.html

new Promise((resolve, reject) => {})
来源：http://dali.fengsongda.top/Article/details/gtbaphdrsi.html

[U96] JS：async/await 与异常
来源：http://dali.shangyingyoupin.top/Article/details/gtgbuavmzz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.daxiang520.top/Article/details/gtqwvwexuq.html

[U97] JS：并发请求
来源：http://dali.iojbl.cn/Article/details/gthshoduqp.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gtgorruokt.html

[U98] JS：fetch 带 JSON
来源：http://dali.aibaodan.cn/Article/details/gtqyijgvmf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yvedp.cn/Article/details/gtdbzffwym.html

[U99] JS：事件监听
来源：http://dali.bjfxy.top/Article/details/gtqzovxbge.html

el.addEventListener("click", e => {})
来源：http://dali.dianchejie.cn/Article/details/gtczbkkvcg.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gtialzqxid.html

document.querySelector(".item")
来源：http://dali.feifeiyinyue.top/Article/details/gtrdikrilu.html

[U101] JS：classList 操作
来源：http://dali.nanxuanxn.top/Article/details/gtbwgoyexw.html

el.classList.toggle("active")
来源：http://dali.xinyue.icu/Article/details/gtpbykdshj.html

[U102] JS：本地存储
来源：http://dali.jianghu66.top/Article/details/gtoxcwbhgn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.havefunace.top/Article/details/gtommsjkit.html

[U103] JS：定时器
来源：http://dali.hysaishi.cn/Article/details/gtefsvcgux.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hysaishi.cn/Article/details/gtifvtynql.html

[U104] JS：防抖
来源：http://dali.vqdsnc.cn/Article/details/gtxjthswuh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenzaomai.com/Article/details/gtsaiszrqz.html

[U105] JS：节流
来源：http://dali.quarkkingdee.top/Article/details/gtgwdmkvnp.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cucudq.cn/Article/details/gtlyvrvmik.html

[U106] JS：日期格式化
来源：http://dali.zycfv.cn/Article/details/gtkuteltdu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yj20258.top/Article/details/gtqjoxeran.html

[U107] JS：数字千分位
来源：http://dali.pycfn.com/Article/details/gtmlqmkyog.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yongpay.top/Article/details/gtffjjigxe.html

[U108] JS：随机整数
来源：http://dali.yueranfly.top/Article/details/gtdvmbujed.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.c1oappe.top/Article/details/gtdmljpraw.html

[U109] JS：数组分组
来源：http://dali.ybcxt.top/Article/details/gtoxhgakyn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.aizwys.cn/Article/details/gteuurxxki.html

[U110] JS：数组分块
来源：http://dali.ivvv.top/Article/details/gtgxzoldiw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jiagoushi.top/Article/details/gtisvdbeiw.html

[U111] JS：对象转 Map
来源：http://dali.hammf.cn/Article/details/gtyckcukef.html

new Map(Object.entries(obj))
来源：http://dali.yonumen.top/Article/details/gtujrweyrr.html

[U112] JS：字符串补位
来源：http://dali.guannengcc.top/Article/details/gtpzfzytjr.html

"7".padStart(3, "0")
来源：http://dali.yonumen.top/Article/details/gtnnonrwoq.html

[U113] JS：正则替换全部
来源：http://dali.tian-w.cn/Article/details/gteuyhpdce.html

s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gtzdaqaisf.html

[U114] JS：JSON 深比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqxdjbudt.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hysaishi.cn/Article/details/gttbtzqgyc.html

[U115] JS：生成 UUID
来源：http://dali.vqdsnc.cn/Article/details/gttignhlix.html

crypto.randomUUID()
来源：http://dali.0kj1m.cn/Article/details/gtxeigjbap.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hysaishi.cn/Article/details/gthekhnsih.html

/** @param {string} name */ function f(name) {}
来源：http://dali.guannengcc.top/Article/details/gtyjpzfcbq.html

[U117] JS：单元测试
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnurmobqo.html

npm i -D vitest;  npx vitest
来源：http://dali.hfpthk.cn/Article/details/gtstpvgsau.html

[U118] JS：开发服务器
来源：http://dali.redwolf501.top/Article/details/gtkwzdyrvs.html

npm i -D vite;  npx vite
来源：http://dali.yueranfly.top/Article/details/gtwaqvfeqw.html

[U119] JS：生产构建
来源：http://dali.chenzaomai.com/Article/details/gtgkukzpic.html

npx vite build
来源：http://dali.gogol.net.cn/Article/details/gtlfccetti.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.sweek.top/Article/details/gttcslerzy.html

import.meta.env.VITE_API_URL
来源：http://dali.jinqigufen.top/Article/details/gteeaccjko.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcbbmrmyi.html

统计汇总
来源：http://dali.shangyingyoupin.top/Article/details/gtpubdlzou.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gthsmxbhtq.html

按语言统计（条）：
来源：http://dali.jinqigufen.top/Article/details/gtjaejmyfs.html

Python ......... 252
来源：http://dali.xuetiantiany.cn/Article/details/gtkmwmrvzg.html

PHP ............ 252
来源：http://dali.tianlin.xyz/Article/details/gtgixbyvtd.html

JavaScript ..... 252
来源：http://dali.sxryk.cn/Article/details/gtfukkktqd.html

TypeScript ..... 212
来源：http://dali.9152youxi.cn/Article/details/gtzrvhxcbw.html

Java ........... 212
来源：http://dali.zhongyouzk.top/Article/details/gtzscfkenl.html

Go ............. 212
来源：http://dali.xinyue.icu/Article/details/gtudqftwcb.html

Ruby ........... 212
来源：http://dali.havefunace.top/Article/details/gthxsiihrj.html

C# ............. 212
来源：http://dali.nanxuanxn.top/Article/details/gtxntwexej.html

C .............. 30
来源：http://dali.cucudq.cn/Article/details/gtddqpcypf.html

C++ ............ 30
来源：http://dali.pengpengdd.cyou/Article/details/gtglgolctl.html

SQL ............ 90
来源：http://dali.shanyushiyangtech.top/Article/details/gtintppovx.html

Bash ........... 80
来源：http://dali.jqgfzy.top/Article/details/gtcyolhvzu.html

Kotlin ......... 15
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoawiymuj.html

Swift .......... 15
来源：http://dali.cucudq.cn/Article/details/gtdhpkedso.html

Lua ............ 10
来源：http://dali.smart0.xyz/Article/details/gtzceghnvc.html

Perl ........... 10
来源：http://dali.yanxiufei.cn/Article/details/gtwrollmya.html

Scala .......... 10
来源：http://dali.redwolf501.top/Article/details/gtvkezbyxa.html

------------------------------------
来源：http://dali.daria6918.cn/Article/details/gtangmmgcr.html

合计 ........... 2106 条
来源：http://dali.guowangkeji.top/Article/details/gtmvbzrmuu.html

按章节统计：
来源：http://dali.ppjwa.cn/Article/details/gtfhyxwmwu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yonumen.top/Article/details/gteiklvqqc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xuetiantiany.cn/Article/details/gtnhfrntbs.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cqqwz.cn/Article/details/gtkekkiaxm.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.vqdsnc.cn/Article/details/gtkdzqyocr.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.aibaodan.cn/Article/details/gtiylsmldf.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.0kj1m.cn/Article/details/gtpfnoqqxm.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.sxryk.cn/Article/details/gthfvhwgnx.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.cheryme.top/Article/details/gtbhqyuihh.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.gaohongyu789.top/Article/details/gtdkbngezv.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.feifeiyinyue.top/Article/details/gtdgvtwidx.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.ehwqpu.com/Article/details/gtmoafkkkb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.nwbrower.top/Article/details/gtyhvhvcqx.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yongpay.top/Article/details/gtewzhqmgp.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ehwqpu.com/Article/details/gtzkhmwoda.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ydzc1.top/Article/details/gttutoaaat.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yueranfly.top/Article/details/gtihdsdnui.html

Q SQL 专题                              90
来源：http://dali.hnqzz.top/Article/details/gtvhgpqvxd.html

R Bash 专题                             80
来源：http://dali.zhoulong.xyz/Article/details/gtqbmoktsz.html

S C / C++ 专题                          60
来源：http://dali.jinghuilouyu.cn/Article/details/gtiorlhyxi.html

T 其他语言补充                          60
来源：http://dali.quarkkingdee.top/Article/details/gthvuurwfw.html

U 高频实用片段                         120
来源：http://dali.ydzc1.top/Article/details/gtrvhwujrn.html

------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gtpfxnkevv.html

合计                                  2106 条
来源：http://dali.xylfe.cn/Article/details/gtewpdnmlj.html

--------------------------------------------------------------------------------
来源：http://dali.ivvv.top/Article/details/gtzkodwayp.html

使用提醒
来源：http://dali.zdqjudy.top/Article/details/gtqhsvesup.html

--------------------------------------------------------------------------------
来源：http://dali.wangshuangyany.cn/Article/details/gtyvlgpnmg.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.xuetiantiany.cn/Article/details/gtfrekzvdr.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.chenjidiqi.icu/Article/details/gteixsliqb.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.ydzc1.top/Article/details/gtgmhfobld.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.cqqwz.cn/Article/details/gtchkldyui.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhiwuduotai.top/Article/details/gtyedszbjr.html

—— 文件结束 ——
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaeyqdybc.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtkyxewnlj.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.sysykeji.top/Article/details/gtkjpjljub.html

Common Programming Examples Cheat Book
来源：http://dali.dianchejie.cn/Article/details/gtefscfprj.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtgasyidfc.html

【收录内容】
来源：http://dali.jyoumei.cn/Article/details/gteefalggn.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.mhx1999.top/Article/details/gtjlstdili.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gtjuckjhne.html

SQL · Bash · C · C++
来源：http://dali.chenjidiqi.icu/Article/details/gtjpvtfmvv.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.andypj.xyz/Article/details/gtzijlyyox.html

【使用说明】
来源：http://dali.sxryk.cn/Article/details/gtsecfgqww.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.xuanzx.com/Article/details/gtsjobdeuj.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.gotoacloud.top/Article/details/gtelaboivu.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.cashguo.top/Article/details/gtyvkzicza.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.smart0.xyz/Article/details/gtcnbppuhl.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.0kj1m.cn/Article/details/gtslqtvgmp.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jiagoushi.top/Article/details/gtdbinmrol.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.sxryk.cn/Article/details/gtjumagtee.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.wangdashe.top/Article/details/gtaoljkcqw.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.chenlongwang.top/Article/details/gtpvmirbkc.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.birdmap.top/Article/details/gtdnuoivcl.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhengqikj.top/Article/details/gtodlduehm.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.gogol.net.cn/Article/details/gthtmgjoux.html

【文件统计】
来源：http://dali.xziqi.cn/Article/details/gtpqturbuj.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jinghuilouyu.cn/Article/details/gtlffjzqtp.html

--------------------------------------------------------------------------------
来源：http://dali.bjfxy.top/Article/details/gtcmzaigty.html

目  录
来源：http://dali.shangyingyoupin.top/Article/details/gtkgjsside.html

--------------------------------------------------------------------------------
来源：http://dali.zdqjudy.top/Article/details/gthebjbvms.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.guannengcc.top/Article/details/gtaaaelkvl.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yuanzhike.top/Article/details/gtiylqiakl.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.birdmap.top/Article/details/gtgmhhyeiu.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.sxryk.cn/Article/details/gtgqvqjdjb.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhixingplan.top/Article/details/gtewjkfesw.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.redwolf501.top/Article/details/gttrcwknhi.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jinqigufen.top/Article/details/gtecappaub.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hywenlv.cn/Article/details/gtdjmrwcra.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.ppjwa.cn/Article/details/gtfquvvdsx.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.tian-w.cn/Article/details/gtqiogqrst.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhengqikj.top/Article/details/gtayywtkns.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.aibaodan.cn/Article/details/gtwqrtxhsa.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jlsjyb.cn/Article/details/gtrkgqxhgo.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.iojbl.cn/Article/details/gtbcczeybh.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jinqigfzy.top/Article/details/gtkzdndddk.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtymsbxfik.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.shangyingyoupin.top/Article/details/gttqhkncld.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.vqdsnc.cn/Article/details/gtxnrrxbnl.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtztetsunh.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yuanzhike.top/Article/details/gtcbkphnam.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.ydzc1.top/Article/details/gtezhxtayx.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gttzuamdik.html

A. 基础语法与类型
来源：http://dali.c1oappe.top/Article/details/gtwzytpudt.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtyhenrnyd.html

[A01] Hello World
来源：http://dali.sweek.top/Article/details/gtiadgewwt.html

Py:   print("Hello, World!")
来源：http://dali.zhongyouzk.top/Article/details/gtudfgvpyx.html

PHP:  echo "Hello, World!";
来源：http://dali.xuetiantiany.cn/Article/details/gtmtgvblty.html

JS:   console.log("Hello, World!");
来源：http://dali.guowangkeji.top/Article/details/gtvxhbdwrw.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.fzhhl.top/Article/details/gtvuoptccr.html

Java: System.out.println("Hello, World!");
来源：http://dali.xylfe.cn/Article/details/gtiixgpdws.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.gogol.net.cn/Article/details/gtgebrpmtv.html

Ruby: puts "Hello, World!"
来源：http://dali.pycfn.com/Article/details/gtvnqmjnom.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.havefunace.top/Article/details/gtanhkktxh.html

[A02] 变量声明与赋值
来源：http://dali.ehwqpu.com/Article/details/gtltriglyr.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.aizwys.cn/Article/details/gtiftnfttc.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.pengpengdd.cyou/Article/details/gtcnwqzhaz.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.haohaochexian.top/Article/details/gtukuqinfo.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hywenlv.cn/Article/details/gtkvzgmqlh.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.ppjwa.cn/Article/details/gtnnolrwlv.html

Go:   name := "Alex"; age := 20
来源：http://dali.sysykeji.top/Article/details/gtkubvvaxu.html

Ruby: name = "Alex"; age = 20
来源：http://dali.nanxinkj.top/Article/details/gtunbxxsmc.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yonumen.top/Article/details/gtecurcdws.html

[A03] 常量定义
来源：http://dali.sysykeji.top/Article/details/gtllcwfbhm.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.dianchejie.cn/Article/details/gtaisprtfj.html

PHP:  const PI = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gtfnzgkvoi.html

JS:   const PI = 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttweaavlu.html

TS:   const PI: number = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gtcjiuuuyj.html

Java: static final double PI = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gtfbqdxjgc.html

Go:   const PI = 3.14159
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkxzhbwms.html

Ruby: PI = 3.14159
来源：http://dali.hywenlv.cn/Article/details/gtmiruonmm.html

C#:   const double PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gtbrufepol.html

[A04] 判断变量类型
来源：http://dali.cashguo.top/Article/details/gtwokewrbp.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jyoumei.cn/Article/details/gtbgxuhrdr.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.guowangkeji.top/Article/details/gtdpxwzvix.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.fengsongda.top/Article/details/gteviugqhr.html

TS:   typeof x; x instanceof Date
来源：http://dali.cdnleiting.top/Article/details/gtpsqqqgcw.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.cqqwz.cn/Article/details/gtdwekmxef.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.gzhubu.top/Article/details/gtdthozdld.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.guowangkeji.top/Article/details/gtcvzrdfoq.html

C#:   x.GetType().Name; x is int
来源：http://dali.cashguo.top/Article/details/gtfzaohnkb.html

[A05] 整数除法与取模
来源：http://dali.kuanghao11.cn/Article/details/gtgzuuustg.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jqgufenzy.top/Article/details/gtzlvedlyz.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.sufxvd.cn/Article/details/gtlpqmysuk.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xinyue.icu/Article/details/gtpaorxnys.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.tanke756.top/Article/details/gtjrndxxjt.html

Java: 7 / 2; 7 % 2
来源：http://dali.smart0.xyz/Article/details/gtzqjpdbfy.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhongyouzk.top/Article/details/gtqsspkgft.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.hywenlv.cn/Article/details/gtodretist.html

C#:   7 / 2; 7 % 2
来源：http://dali.yangfankeji.com/Article/details/gtroryjevc.html

[A06] 字符串转数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqbsnfcyh.html

Py:   int("42"); float("3.14")
来源：http://dali.316326.xyz/Article/details/gtfhugpdnb.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.cashguo.top/Article/details/gtmzehrikx.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.cheryme.top/Article/details/gtuqijtwee.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jyoumei.cn/Article/details/gtkdkxjgvw.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.gaohongyu789.top/Article/details/gtyskvqtzw.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.andypj.xyz/Article/details/gtozpfpmib.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.chenlongwang.top/Article/details/gtfdskqmao.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.nanxuanxn.top/Article/details/gtvfjarohx.html

[A07] 数字转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdyozjumb.html

Py:   str(42)
来源：http://dali.zhoulong.xyz/Article/details/gtezmjoles.html

PHP:  (string) 42; strval(42)
来源：http://dali.ydzc1.top/Article/details/gtmsvwpdvk.html

JS:   String(42); (42).toString()
来源：http://dali.meibo888.top/Article/details/gtvwmillpm.html

TS:   String(42)
来源：http://dali.zycfv.cn/Article/details/gtjtufzgov.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.hywenlv.cn/Article/details/gtrsttmehf.html

Go:   strconv.Itoa(42)
来源：http://dali.wangshuangyany.cn/Article/details/gtdvxiosdj.html


<!-- 参考信息 -->