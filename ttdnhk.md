代发 wailian999

[U57] PHP：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gtaojoqdrh.html

"值: {$a}"
来源：http://dali.shangyingyoupin.top/Article/details/gtwftfwkiu.html

[U58] PHP：数组三件套
来源：http://dali.pycfn.com/Article/details/gtvdnqpikr.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.iojbl.cn/Article/details/gtftrclvsr.html

[U59] PHP：自定义排序
来源：http://dali.iojbl.cn/Article/details/gtuipesiml.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ivvv.top/Article/details/gtktsowyry.html

[U60] PHP：JSON 编解码
来源：http://dali.pengpengdd.cyou/Article/details/gtkvudwpai.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljgjypjo.html

[U61] PHP：正则
来源：http://dali.yanxiufei.cn/Article/details/gtpwvwyfoz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxinkj.top/Article/details/gtghyroieo.html

[U62] PHP：日期对象
来源：http://dali.zhiwuduotai.top/Article/details/gtfmnaeccc.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.chenzaomai.com/Article/details/gtwkbzrohi.html

[U63] PHP：文件读写
来源：http://dali.hysaishi.cn/Article/details/gttjddhjft.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.mhx1999.top/Article/details/gtfbuppbbe.html

[U64] PHP：目录遍历
来源：http://dali.tian-w.cn/Article/details/gtssbjgrhi.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.xinyue.icu/Article/details/gtiopiitkx.html

[U65] PHP：会话
来源：http://dali.yuanzhike.top/Article/details/gtbifuqnqb.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gtzdzpxwid.html

[U66] PHP：设置 Cookie
来源：http://dali.ybcxt.top/Article/details/gtrxmzaaym.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.0kj1m.cn/Article/details/gtxebkjihu.html

[U67] PHP：处理文件上传
来源：http://dali.gogol.net.cn/Article/details/gtvfohmnrq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.guowangkeji.top/Article/details/gtwaephnxx.html

[U68] PHP：PDO 连接
来源：http://dali.tianlin.xyz/Article/details/gtzlzrzsau.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.cqqwz.cn/Article/details/gtbgdpfzil.html

[U69] PHP：PDO 预处理
来源：http://dali.kuanghao11.cn/Article/details/gtmewjrutv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.9152youxi.cn/Article/details/gttxpecyhn.html

[U70] PHP：PDO 事务
来源：http://dali.chenjidiqi.icu/Article/details/gtfepdstzr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hfpthk.cn/Article/details/gtcdnoejzw.html

[U71] PHP：抛出异常
来源：http://dali.cashguo.top/Article/details/gtvzdenlfv.html

throw new RuntimeException("失败", 500);
来源：http://dali.zycfv.cn/Article/details/gtxjdymnot.html

[U72] PHP：写错误日志
来源：http://dali.c1oappe.top/Article/details/gteaduplqs.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zdqjudy.top/Article/details/gtzqtwqvlu.html

[U73] PHP：读取 ini 配置
来源：http://dali.cucudq.cn/Article/details/gttgksjzml.html

parse_ini_file("config.ini", true)
来源：http://dali.hammf.cn/Article/details/gttaxmostm.html

[U74] PHP：读取环境变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtngyabtfb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.sxryk.cn/Article/details/gtzlmdbegi.html

[U75] PHP：依赖注入
来源：http://dali.meibo888.top/Article/details/gtsabaqzbq.html

composer require psr/container
来源：http://dali.redwolf501.top/Article/details/gthheuyxaq.html

[U76] PHP：简单路由
来源：http://dali.jlsjyb.cn/Article/details/gtjehpktel.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.nanxuanxn.top/Article/details/gtqisxuwml.html

[U77] PHP：模板渲染
来源：http://dali.wangdashe.top/Article/details/gtpmbaiwce.html

composer require twig/twig
来源：http://dali.shangyingyoupin.top/Article/details/gtbjdccukr.html

[U78] PHP：单元测试
来源：http://dali.birdmap.top/Article/details/gtzubncbjr.html

composer require --dev phpunit/phpunit
来源：http://dali.hnqzz.top/Article/details/gttrbmhsje.html

[U79] PHP：静态分析
来源：http://dali.yvedp.cn/Article/details/gtybjstgxw.html

composer require --dev phpstan/phpstan
来源：http://dali.ehwqpu.com/Article/details/gtgechdgya.html

[U80] PHP：代码规范修复
来源：http://dali.xuetiantiany.cn/Article/details/gtwwwbxihq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.fzhhl.top/Article/details/gtqneciwkw.html

[U81] JS：初始化项目
来源：http://dali.nanxuanxn.top/Article/details/gtminrjocb.html

npm init -y;  npm i express
来源：http://dali.gaohongyu789.top/Article/details/gtemmgsrjn.html

[U82] JS：package.json 脚本
来源：http://dali.sxryk.cn/Article/details/gtfrhqcxrq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yanxiufei.cn/Article/details/gttfmodxpf.html

[U83] JS：ES Module 导入导出
来源：http://dali.gzhubu.top/Article/details/gtbqsnxmgr.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.xylfe.cn/Article/details/gtxwkrxfbu.html

[U84] JS：CommonJS 写法
来源：http://dali.sweek.top/Article/details/gtdmrzpobf.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hywenlv.cn/Article/details/gtwhrdssgp.html

[U85] JS：可选链
来源：http://dali.jlsjyb.cn/Article/details/gtveqjyktb.html

a?.b?.c
来源：http://dali.jyoumei.cn/Article/details/gthzxphgxo.html

[U86] JS：空值合并
来源：http://dali.0kj1m.cn/Article/details/gtoalwcdfc.html

a ?? b
来源：http://dali.yuxming.cn/Article/details/gtoedenmcj.html

[U87] JS：解构默认值
来源：http://dali.havefunace.top/Article/details/gtohnwqovh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.shuidangran.top/Article/details/gtczxgvroz.html

[U88] JS：对象展开合并
来源：http://dali.yj20258.top/Article/details/gtpbwlceoa.html

{ ...a, ...b }
来源：http://dali.9152youxi.cn/Article/details/gtzdgjwpsu.html

[U89] JS：数组去重
来源：http://dali.jqgfzy.top/Article/details/gtvdyvoivs.html

[...new Set(arr)]
来源：http://dali.jinqigufen.top/Article/details/gtnvpfokhp.html

[U90] JS：数字数组排序
来源：http://dali.hnqzz.top/Article/details/gtsuhbwual.html

[...arr].sort((a, b) => a - b)
来源：http://dali.guannengcc.top/Article/details/gtsjwslowz.html

[U91] JS：对象键值遍历
来源：http://dali.yuanzhike.top/Article/details/gtgiavjpmq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.chenzaomai.com/Article/details/gtthsknbsu.html

[U92] JS：深拷贝
来源：http://dali.yj20258888.top/Article/details/gtgsmduevt.html

structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gtzhpkqlvj.html

[U93] JS：模板字符串
来源：http://dali.gzhubu.top/Article/details/gtqfakeign.html

`共 ${n} 条`
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgfijrjiy.html

[U94] JS：箭头函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqqsqyfjc.html

const double = x => x * 2;
来源：http://dali.mhx1999.top/Article/details/gtmnjigypq.html

[U95] JS：Promise 包装
来源：http://dali.nwbrower.top/Article/details/gtakcvgxuq.html

new Promise((resolve, reject) => {})
来源：http://dali.yongpay.top/Article/details/gthoaeabbu.html

[U96] JS：async/await 与异常
来源：http://dali.sxryk.cn/Article/details/gtzmdxydbq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gtpjjpkmgy.html

[U97] JS：并发请求
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtppnhfqxo.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xylfe.cn/Article/details/gtqjeqeaer.html

[U98] JS：fetch 带 JSON
来源：http://dali.sweek.top/Article/details/gtjlpximtj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.cdnleiting.top/Article/details/gtpfnjnwjc.html

[U99] JS：事件监听
来源：http://dali.yanxiufei.cn/Article/details/gtaywxxcsk.html

el.addEventListener("click", e => {})
来源：http://dali.yuanzhike.top/Article/details/gtbudhbrff.html

[U100] JS：DOM 查询
来源：http://dali.guannengcc.top/Article/details/gttsfareiw.html

document.querySelector(".item")
来源：http://dali.yuxming.cn/Article/details/gthglzoenh.html

[U101] JS：classList 操作
来源：http://dali.daxiang520.top/Article/details/gtgrwojbbb.html

el.classList.toggle("active")
来源：http://dali.aizwys.cn/Article/details/gtjczrgrzw.html

[U102] JS：本地存储
来源：http://dali.yj20258.top/Article/details/gtapqjxurl.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.iojbl.cn/Article/details/gtnurkvrkz.html

[U103] JS：定时器
来源：http://dali.svipenyu.cn/Article/details/gtpplvnvdu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.aizwys.cn/Article/details/gtqbzowaru.html

[U104] JS：防抖
来源：http://dali.vqdsnc.cn/Article/details/gtrphnsqoq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gtstezylzn.html

[U105] JS：节流
来源：http://dali.ybcxt.top/Article/details/gteokapozh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yangfankeji.com/Article/details/gtsgojxbet.html

[U106] JS：日期格式化
来源：http://dali.hysaishi.cn/Article/details/gttjowoqhi.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yj202588.top/Article/details/gtohfadatr.html

[U107] JS：数字千分位
来源：http://dali.jlsjyb.cn/Article/details/gthagjwchg.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cqqwz.cn/Article/details/gtmnwpzuce.html

[U108] JS：随机整数
来源：http://dali.zycfv.cn/Article/details/gtyeufnysu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.ybcxt.top/Article/details/gtpsgsdqqz.html

[U109] JS：数组分组
来源：http://dali.vqdsnc.cn/Article/details/gttvjtqolx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.daxiang520.top/Article/details/gtlokntkza.html

[U110] JS：数组分块
来源：http://dali.zhongyouzk.top/Article/details/gtfyqqiiqb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.pengpengdd.cyou/Article/details/gtnklghwbr.html

[U111] JS：对象转 Map
来源：http://dali.guannengcc.top/Article/details/gtrisuwbev.html

new Map(Object.entries(obj))
来源：http://dali.hysaishi.cn/Article/details/gtibexephf.html

[U112] JS：字符串补位
来源：http://dali.cdnleiting.top/Article/details/gtvqercevu.html

"7".padStart(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gtofuvenom.html

[U113] JS：正则替换全部
来源：http://dali.yangfankeji.com/Article/details/gthwjedncn.html

s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtesgnrucw.html

[U114] JS：JSON 深比较
来源：http://dali.smart0.xyz/Article/details/gtynzhelfo.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jiagoushi.top/Article/details/gthwxsilym.html

[U115] JS：生成 UUID
来源：http://dali.xylfe.cn/Article/details/gtbfkexemg.html

crypto.randomUUID()
来源：http://dali.hywenlv.cn/Article/details/gtmljrriid.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xinyue.icu/Article/details/gtjwiuzijl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.guowangkeji.top/Article/details/gtjxojfcam.html

[U117] JS：单元测试
来源：http://dali.hnqzz.top/Article/details/gtpgxmtlhg.html

npm i -D vitest;  npx vitest
来源：http://dali.hywenlv.cn/Article/details/gtmkbmedec.html

[U118] JS：开发服务器
来源：http://dali.cheryme.top/Article/details/gtdnvvkifx.html

npm i -D vite;  npx vite
来源：http://dali.smart0.xyz/Article/details/gtrnhipcms.html

[U119] JS：生产构建
来源：http://dali.ybcxt.top/Article/details/gtfopyzzvz.html

npx vite build
来源：http://dali.zhengqikj.top/Article/details/gttqpwqvds.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.havefunace.top/Article/details/gteunhjfba.html

import.meta.env.VITE_API_URL
来源：http://dali.jqgfzy.top/Article/details/gtwyoinzzc.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gttwrrkztl.html

统计汇总
来源：http://dali.shuidangran.top/Article/details/gttogkrrpe.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtzpnqzdju.html

按语言统计（条）：
来源：http://dali.yuanzhike.top/Article/details/gtgoauicbg.html

Python ......... 252
来源：http://dali.quarkkingdee.top/Article/details/gtjmracesm.html

PHP ............ 252
来源：http://dali.hnqzz.top/Article/details/gtlvcfbpov.html

JavaScript ..... 252
来源：http://dali.guowangkeji.top/Article/details/gtwhkdpnyo.html

TypeScript ..... 212
来源：http://dali.ppjwa.cn/Article/details/gtyxqzyimw.html

Java ........... 212
来源：http://dali.sysykeji.top/Article/details/gtyfregxjf.html

Go ............. 212
来源：http://dali.sufxvd.cn/Article/details/gtepxxjphf.html

Ruby ........... 212
来源：http://dali.pengpengdd.cyou/Article/details/gtlyeclqhy.html

C# ............. 212
来源：http://dali.yj20258.top/Article/details/gtwvitedkb.html

C .............. 30
来源：http://dali.zhoulong.xyz/Article/details/gtlzipfhgf.html

C++ ............ 30
来源：http://dali.nanxuanxn.top/Article/details/gtujblwrhe.html

SQL ............ 90
来源：http://dali.yuanzhike.top/Article/details/gtrjtbyytd.html

Bash ........... 80
来源：http://dali.yj20258888.top/Article/details/gtigweqzcz.html

Kotlin ......... 15
来源：http://dali.hammf.cn/Article/details/gtsqyoving.html

Swift .......... 15
来源：http://dali.meibo888.top/Article/details/gthndleiwf.html

Lua ............ 10
来源：http://dali.cdnleiting.top/Article/details/gtgkquijbq.html

Perl ........... 10
来源：http://dali.yj20258.top/Article/details/gtprhxfzfb.html

Scala .......... 10
来源：http://dali.jqgfzy.top/Article/details/gtlytgbrlz.html

------------------------------------
来源：http://dali.yueranfly.top/Article/details/gtrgvxuowh.html

合计 ........... 2106 条
来源：http://dali.yj20258.top/Article/details/gtrapzfmta.html

按章节统计：
来源：http://dali.zhoulong.xyz/Article/details/gtnynspjze.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.snrcjt.cn/Article/details/gtwrgqjtdt.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shangyingyoupin.top/Article/details/gtmfjlrgfa.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hongshengwenyu.top/Article/details/gtokqxktlk.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cqqwz.cn/Article/details/gtnwgomuhx.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yonumen.top/Article/details/gtzjxohjuw.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.cqqwz.cn/Article/details/gtnvpidqdz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jiagoushi.top/Article/details/gttcqwdntn.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.chenzaomai.com/Article/details/gtfvlpisyk.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.ehwqpu.com/Article/details/gthaiglody.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.nwbrower.top/Article/details/gtzlentsvz.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.quarkkingdee.top/Article/details/gtdvghbjns.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gtsoooykrn.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.xinyue.icu/Article/details/gtwsyzsuze.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.svipenyu.cn/Article/details/gtrcvfocbt.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.bjfxy.top/Article/details/gtzphskluq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.nwbrower.top/Article/details/gtfnliwqhz.html

Q SQL 专题                              90
来源：http://dali.hfpthk.cn/Article/details/gtxwehfhxk.html

R Bash 专题                             80
来源：http://dali.ydzc1.top/Article/details/gtuqalntnz.html

S C / C++ 专题                          60
来源：http://dali.hysaishi.cn/Article/details/gtuzbfztfq.html

T 其他语言补充                          60
来源：http://dali.jinqigufen.top/Article/details/gtloifxsqd.html

U 高频实用片段                         120
来源：http://dali.havefunace.top/Article/details/gtboxkhipu.html

------------------------------------
来源：http://dali.jianghu66.top/Article/details/gtcyexownh.html

合计                                  2106 条
来源：http://dali.yangfankeji.com/Article/details/gtjxidpwoe.html

--------------------------------------------------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gtovzewwge.html

使用提醒
来源：http://dali.shuidangran.top/Article/details/gthzcykyqg.html

--------------------------------------------------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gtnbuzxpoo.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jinyuanbaomall.cn/Article/details/gtucsolszh.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ehwqpu.com/Article/details/gtkiexibhr.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yangfankeji.com/Article/details/gtpuzzkkkf.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzfezegyw.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.ivvv.top/Article/details/gtvyfgrtbq.html

—— 文件结束 ——
来源：http://dali.ehwqpu.com/Article/details/gtkejemurn.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gttocgvsjo.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.pycfn.com/Article/details/gtpxqnrugy.html

Common Programming Examples Cheat Book
来源：http://dali.jqgfzy.top/Article/details/gtpphbsboq.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtnaognpyc.html

【收录内容】
来源：http://dali.yj20258.top/Article/details/gtwtbijzdi.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.daria6918.cn/Article/details/gtihtrpsom.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.andypj.xyz/Article/details/gtgkwhdpuy.html

SQL · Bash · C · C++
来源：http://dali.ybcxt.top/Article/details/gthauvserh.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.nwbrower.top/Article/details/gtydomzupr.html

【使用说明】
来源：http://dali.sufxvd.cn/Article/details/gtwxcsrecs.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.shanyushiyangtech.top/Article/details/gtcyzvquwg.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.xylfe.cn/Article/details/gtqkbdntmm.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.xylfe.cn/Article/details/gtdiwqagvd.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jinqigfzy.top/Article/details/gtsatjwgfn.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yj20258.top/Article/details/gtecaruwlj.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.cashguo.top/Article/details/gtolvbacbx.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsmxksvew.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhoulong.xyz/Article/details/gtvqohnetc.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yanxiufei.cn/Article/details/gtsjxfftji.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.aizwys.cn/Article/details/gtaymhqavg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hnxiangtu.top/Article/details/gthednmxja.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.fzhhl.top/Article/details/gtzvisjxic.html

【文件统计】
来源：http://dali.yanxiufei.cn/Article/details/gtnmudabhc.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.sysykeji.top/Article/details/gtdeyoqgzr.html

--------------------------------------------------------------------------------
来源：http://dali.hywenlv.cn/Article/details/gtbvrfhpgo.html

目  录
来源：http://dali.jinqigfzy.top/Article/details/gtcivktdzv.html

--------------------------------------------------------------------------------
来源：http://dali.xuanzx.com/Article/details/gtnwnvevxy.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zdqjudy.top/Article/details/gthpazjdxn.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.mhx1999.top/Article/details/gtvzfjymwi.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.aizwys.cn/Article/details/gtbjrsydhl.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtxzuxlqbr.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.xziqi.cn/Article/details/gtgjnllrws.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.dashuyun.cn/Article/details/gthtcdyaxv.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.tian-w.cn/Article/details/gtijhkkdix.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.iojbl.cn/Article/details/gtvjjftmva.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhoulong.xyz/Article/details/gtbsnhrbic.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.0kj1m.cn/Article/details/gturitvxki.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.gaohongyu789.top/Article/details/gtcfsrzbqk.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.sweek.top/Article/details/gtsfnwtdbp.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.hfpthk.cn/Article/details/gtfzorwlie.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.pycfn.com/Article/details/gtxqbikpqs.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhixingplan.top/Article/details/gtksnwqvxb.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jqgfzy.top/Article/details/gtlykbbnyf.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.hysaishi.cn/Article/details/gtjmskzjot.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jinqigfzy.top/Article/details/gtbvsblogq.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhongyouzk.top/Article/details/gtysyhqrlt.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.daria6918.cn/Article/details/gtadkxdxsa.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yj20258888.top/Article/details/gtsourmduq.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtoxrsgyeh.html

A. 基础语法与类型
来源：http://dali.redwolf501.top/Article/details/gtelwpvllq.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtlhlhegjb.html

[A01] Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtbpbrabyq.html

Py:   print("Hello, World!")
来源：http://dali.jianghu66.top/Article/details/gtixbiuhvo.html

PHP:  echo "Hello, World!";
来源：http://dali.yueranfly.top/Article/details/gtafavwlec.html

JS:   console.log("Hello, World!");
来源：http://dali.hnxiangtu.top/Article/details/gtqcesirpp.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.wangshuangyany.cn/Article/details/gtikjvuavy.html

Java: System.out.println("Hello, World!");
来源：http://dali.sxryk.cn/Article/details/gtguojulkc.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jinqigfzy.top/Article/details/gtjumpqmky.html

Ruby: puts "Hello, World!"
来源：http://dali.svipenyu.cn/Article/details/gtrqmocrwl.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jiagoushi.top/Article/details/gtysjcypuz.html

[A02] 变量声明与赋值
来源：http://dali.cdnleiting.top/Article/details/gtzgsdityr.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.xuanzx.com/Article/details/gtkmaevoeh.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmsbjshm.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.cdnleiting.top/Article/details/gtnyfjusxj.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.meibo888.top/Article/details/gtwuswyuux.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhoulong.xyz/Article/details/gtvbhxqjri.html

Go:   name := "Alex"; age := 20
来源：http://dali.dashuyun.cn/Article/details/gtgwvhgrli.html

Ruby: name = "Alex"; age = 20
来源：http://dali.gaohongyu789.top/Article/details/gtrrgfjppw.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yonumen.top/Article/details/gtqdwqcrwk.html

[A03] 常量定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbiihzdk.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jinqigufen.top/Article/details/gtpkcazuhw.html

PHP:  const PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtnduexrfm.html

JS:   const PI = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gtjttasppp.html

TS:   const PI: number = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gtdjbarldg.html

Java: static final double PI = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gtrirpmtgp.html

Go:   const PI = 3.14159
来源：http://dali.zhixingplan.top/Article/details/gtvoecwqwt.html

Ruby: PI = 3.14159
来源：http://dali.hfpthk.cn/Article/details/gtwhmdfore.html

C#:   const double PI = 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gtlbwrtkyx.html

[A04] 判断变量类型
来源：http://dali.sweek.top/Article/details/gtaxahtkqg.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.meibo888.top/Article/details/gtvcxmlkjh.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yuxming.cn/Article/details/gtouvmzlbp.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.tanke756.top/Article/details/gtswbjcggw.html

TS:   typeof x; x instanceof Date
来源：http://dali.xinyue.icu/Article/details/gtwotftqcf.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yangfankeji.com/Article/details/gtwxkkfdjs.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hnxiangtu.top/Article/details/gtmmjjjuub.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.cashguo.top/Article/details/gtltqtxetz.html

C#:   x.GetType().Name; x is int
来源：http://dali.316326.xyz/Article/details/gtiymisype.html

[A05] 整数除法与取模
来源：http://dali.hnqzz.top/Article/details/gtycrmkogj.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yvedp.cn/Article/details/gtddghojzq.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gtzmnccigx.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gtrmajvpkt.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yj20258.top/Article/details/gtfnelgkbp.html

Java: 7 / 2; 7 % 2
来源：http://dali.pycfn.com/Article/details/gtounffztm.html

Go:   7 / 2; 7 % 2
来源：http://dali.hnxiangtu.top/Article/details/gtlvimcxjf.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yonumen.top/Article/details/gtpjwnhias.html

C#:   7 / 2; 7 % 2
来源：http://dali.daxiang520.top/Article/details/gtrxavvctq.html

[A06] 字符串转数字
来源：http://dali.xuanzx.com/Article/details/gtpbcjgdyf.html

Py:   int("42"); float("3.14")
来源：http://dali.yj202588.top/Article/details/gtswezemcv.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jinqigfzy.top/Article/details/gtqrfaocri.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.cucudq.cn/Article/details/gtgcknrabq.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.sufxvd.cn/Article/details/gtwbacubqj.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.316326.xyz/Article/details/gtmeyloqwy.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.cucudq.cn/Article/details/gtegqcphuw.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jianghu66.top/Article/details/gthnucqswi.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yueranfly.top/Article/details/gtodqnhtby.html

[A07] 数字转字符串
来源：http://dali.pycfn.com/Article/details/gtcpiixumz.html

Py:   str(42)
来源：http://dali.iojbl.cn/Article/details/gtreixwjye.html

PHP:  (string) 42; strval(42)
来源：http://dali.shuidangran.top/Article/details/gtlmotefuw.html

JS:   String(42); (42).toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtevfldziq.html

TS:   String(42)
来源：http://dali.nanxuanxn.top/Article/details/gthkkgijcf.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtegaruuql.html

Go:   strconv.Itoa(42)
来源：http://dali.yonumen.top/Article/details/gtvijojnjz.html

Ruby: 42.to_s
来源：http://dali.sufxvd.cn/Article/details/gttmyjwbuk.html

C#:   42.ToString()
来源：http://dali.quarkkingdee.top/Article/details/gtwchjsibi.html

[A08] 取整与四舍五入
来源：http://dali.ehwqpu.com/Article/details/gtcrjoueab.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.nanxinkj.top/Article/details/gtueftfzyg.html


<!-- 参考信息 -->