代发 wailian999

[U53] PHP：空合并运算符
来源：http://dali.snrcjt.cn/Article/details/gtfesfhrhf.html

$v = $a ?? $b ?? "default";
来源：http://dali.yuanzhike.top/Article/details/gtvrgubjjf.html

[U54] PHP：空安全调用
来源：http://dali.cashguo.top/Article/details/gtsoqqdunp.html

$obj?->method()
来源：http://dali.shangyingyoupin.top/Article/details/gtxgiglaas.html

[U55] PHP：match 表达式
来源：http://dali.xuanzx.com/Article/details/gtdhfqungv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.sysykeji.top/Article/details/gtyybgeece.html

[U56] PHP：命名参数
来源：http://dali.gogol.net.cn/Article/details/gtoqwfsekf.html

f(a: 1, b: 2)
来源：http://dali.daxiang520.top/Article/details/gtgowcentq.html

[U57] PHP：字符串插值
来源：http://dali.jianghu66.top/Article/details/gtltdcbtel.html

"值: {$a}"
来源：http://dali.zhengqikj.top/Article/details/gtbzlgqqvw.html

[U58] PHP：数组三件套
来源：http://dali.jqgfzy.top/Article/details/gtmlwupldv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hywenlv.cn/Article/details/gtejulcatt.html

[U59] PHP：自定义排序
来源：http://dali.sysykeji.top/Article/details/gtpueypmgp.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gotoacloud.top/Article/details/gtykiqhbqs.html

[U60] PHP：JSON 编解码
来源：http://dali.guannengcc.top/Article/details/gtmhakryuq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.gzhubu.top/Article/details/gtnynizkxb.html

[U61] PHP：正则
来源：http://dali.xinyue.icu/Article/details/gthqcivgca.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.aizwys.cn/Article/details/gtejmnbixk.html

[U62] PHP：日期对象
来源：http://dali.hnxiangtu.top/Article/details/gtkjgzygoi.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhixingplan.top/Article/details/gtyhyvpcxc.html

[U63] PHP：文件读写
来源：http://dali.cdnleiting.top/Article/details/gtnvmuskxl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.guowangkeji.top/Article/details/gtavhtjzyt.html

[U64] PHP：目录遍历
来源：http://dali.yongpay.top/Article/details/gtieyyvgow.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.cashguo.top/Article/details/gtackyenrx.html

[U65] PHP：会话
来源：http://dali.smart0.xyz/Article/details/gtxyufjhgi.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gtnywdlzve.html

[U66] PHP：设置 Cookie
来源：http://dali.hywenlv.cn/Article/details/gtuxngplob.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.fzhhl.top/Article/details/gtsccoyjwg.html

[U67] PHP：处理文件上传
来源：http://dali.redwolf501.top/Article/details/gtunarucxu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.ivvv.top/Article/details/gtahijuspk.html

[U68] PHP：PDO 连接
来源：http://dali.haohaochexian.top/Article/details/gtlmynmkav.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.wangdashe.top/Article/details/gtietypyzi.html

[U69] PHP：PDO 预处理
来源：http://dali.cqqwz.cn/Article/details/gtacupcswe.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.chenjidiqi.icu/Article/details/gteebtgsvz.html

[U70] PHP：PDO 事务
来源：http://dali.hnxiangtu.top/Article/details/gtlxtdwxct.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.sufxvd.cn/Article/details/gttbpdgjpz.html

[U71] PHP：抛出异常
来源：http://dali.jqgfzy.top/Article/details/gtvbzsnfjt.html

throw new RuntimeException("失败", 500);
来源：http://dali.sxryk.cn/Article/details/gtufqeoqoz.html

[U72] PHP：写错误日志
来源：http://dali.jlsjyb.cn/Article/details/gthcvlkpyr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jinqigfzy.top/Article/details/gtmhuxvfce.html

[U73] PHP：读取 ini 配置
来源：http://dali.pengpengdd.cyou/Article/details/gtyblutzbi.html

parse_ini_file("config.ini", true)
来源：http://dali.quarkkingdee.top/Article/details/gtnwqoicpj.html

[U74] PHP：读取环境变量
来源：http://dali.mhx1999.top/Article/details/gtusvlulqo.html

getenv("APP_ENV") ?: "production"
来源：http://dali.dashuyun.cn/Article/details/gtrpqrkcok.html

[U75] PHP：依赖注入
来源：http://dali.meibo888.top/Article/details/gtbvzbijph.html

composer require psr/container
来源：http://dali.haohaochexian.top/Article/details/gtivqwekpr.html

[U76] PHP：简单路由
来源：http://dali.nanxuanxn.top/Article/details/gtlrnfwwnw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.guowangkeji.top/Article/details/gtbtitwldg.html

[U77] PHP：模板渲染
来源：http://dali.daria6918.cn/Article/details/gtmdomdwzv.html

composer require twig/twig
来源：http://dali.yvedp.cn/Article/details/gtkzxeqgrm.html

[U78] PHP：单元测试
来源：http://dali.quarkkingdee.top/Article/details/gtepttehyw.html

composer require --dev phpunit/phpunit
来源：http://dali.birdmap.top/Article/details/gtpyopckxv.html

[U79] PHP：静态分析
来源：http://dali.hnqzz.top/Article/details/gtygvceytr.html

composer require --dev phpstan/phpstan
来源：http://dali.shuidangran.top/Article/details/gtdhlvagdk.html

[U80] PHP：代码规范修复
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxgduhmqn.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.kuanghao11.cn/Article/details/gtsvanvsqm.html

[U81] JS：初始化项目
来源：http://dali.yj20258888.top/Article/details/gtgthrvutm.html

npm init -y;  npm i express
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnnhrltkl.html

[U82] JS：package.json 脚本
来源：http://dali.pycfn.com/Article/details/gtyevaftlt.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.guannengcc.top/Article/details/gtgiyywheb.html

[U83] JS：ES Module 导入导出
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcmyuiusx.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.tian-w.cn/Article/details/gtozolpqtb.html

[U84] JS：CommonJS 写法
来源：http://dali.pycfn.com/Article/details/gttkqwinlr.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.sufxvd.cn/Article/details/gtwhcsnhgj.html

[U85] JS：可选链
来源：http://dali.dianchejie.cn/Article/details/gtqfrksoge.html

a?.b?.c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsehqzopj.html

[U86] JS：空值合并
来源：http://dali.birdmap.top/Article/details/gtoxlhlrgj.html

a ?? b
来源：http://dali.sxryk.cn/Article/details/gtxcojizqb.html

[U87] JS：解构默认值
来源：http://dali.jinghuilouyu.cn/Article/details/gtexhajaxv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.wangdashe.top/Article/details/gttllzoazm.html

[U88] JS：对象展开合并
来源：http://dali.316326.xyz/Article/details/gtdfpaljrx.html

{ ...a, ...b }
来源：http://dali.jinqigufen.top/Article/details/gtyzayoolf.html

[U89] JS：数组去重
来源：http://dali.chenzaomai.com/Article/details/gtmfihkfif.html

[...new Set(arr)]
来源：http://dali.cqqwz.cn/Article/details/gtamzzxqpl.html

[U90] JS：数字数组排序
来源：http://dali.daxiang520.top/Article/details/gtugohraaa.html

[...arr].sort((a, b) => a - b)
来源：http://dali.shangyingyoupin.top/Article/details/gtdjldanty.html

[U91] JS：对象键值遍历
来源：http://dali.nwbrower.top/Article/details/gtdbylxicd.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yj20258.top/Article/details/gtgeynzkda.html

[U92] JS：深拷贝
来源：http://dali.xylfe.cn/Article/details/gtfzaxduca.html

structuredClone(obj)
来源：http://dali.shuidangran.top/Article/details/gtuvvxvcqi.html

[U93] JS：模板字符串
来源：http://dali.mhx1999.top/Article/details/gtaajsmpia.html

`共 ${n} 条`
来源：http://dali.ybcxt.top/Article/details/gtqtdycykh.html

[U94] JS：箭头函数
来源：http://dali.quarkkingdee.top/Article/details/gttxurnrnu.html

const double = x => x * 2;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzvuzwzxv.html

[U95] JS：Promise 包装
来源：http://dali.nanxinkj.top/Article/details/gtrbvizsjf.html

new Promise((resolve, reject) => {})
来源：http://dali.chenzaomai.com/Article/details/gtqovjwgzh.html

[U96] JS：async/await 与异常
来源：http://dali.gotoacloud.top/Article/details/gtfickazrk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yj202588.top/Article/details/gtpysruazz.html

[U97] JS：并发请求
来源：http://dali.daxiang520.top/Article/details/gtpkvnheqi.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenzaomai.com/Article/details/gtgzmzlswj.html

[U98] JS：fetch 带 JSON
来源：http://dali.haohaochexian.top/Article/details/gteolisktf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.feifeiyinyue.top/Article/details/gttfmpnymh.html

[U99] JS：事件监听
来源：http://dali.haohaochexian.top/Article/details/gtfvlqtcbc.html

el.addEventListener("click", e => {})
来源：http://dali.tianlin.xyz/Article/details/gtjhfdqvix.html

[U100] JS：DOM 查询
来源：http://dali.cashguo.top/Article/details/gtyoyxfoiy.html

document.querySelector(".item")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvpppada.html

[U101] JS：classList 操作
来源：http://dali.shuidangran.top/Article/details/gtgwtllrfr.html

el.classList.toggle("active")
来源：http://dali.cheryme.top/Article/details/gtktemuihi.html

[U102] JS：本地存储
来源：http://dali.ydzc1.top/Article/details/gtpcyknajk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.mhx1999.top/Article/details/gtxnmzfcbq.html

[U103] JS：定时器
来源：http://dali.fengsongda.top/Article/details/gtoqzhalur.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhixingplan.top/Article/details/gtowetwedf.html

[U104] JS：防抖
来源：http://dali.cheryme.top/Article/details/gtdauilvcs.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tanke756.top/Article/details/gtijmlketp.html

[U105] JS：节流
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwmlyang.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.pengpengdd.cyou/Article/details/gthczardag.html

[U106] JS：日期格式化
来源：http://dali.yonumen.top/Article/details/gtlokrumze.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.dianchejie.cn/Article/details/gtlwzawkjr.html

[U107] JS：数字千分位
来源：http://dali.cdnleiting.top/Article/details/gtgsuczdpl.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhongyouzk.top/Article/details/gtsgqrbdzb.html

[U108] JS：随机整数
来源：http://dali.dianchejie.cn/Article/details/gtmpnbkany.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hammf.cn/Article/details/gtozomcfhs.html

[U109] JS：数组分组
来源：http://dali.bjfxy.top/Article/details/gtgnggcdpj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.gzhubu.top/Article/details/gtabvdpikg.html

[U110] JS：数组分块
来源：http://dali.jianghu66.top/Article/details/gtugtbvuyo.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.9152youxi.cn/Article/details/gtuuvjlrxo.html

[U111] JS：对象转 Map
来源：http://dali.sweek.top/Article/details/gtjejzstxc.html

new Map(Object.entries(obj))
来源：http://dali.yj202588.top/Article/details/gtottxrpau.html

[U112] JS：字符串补位
来源：http://dali.gzhubu.top/Article/details/gtqxoycxnq.html

"7".padStart(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gtkqamkqqd.html

[U113] JS：正则替换全部
来源：http://dali.aizwys.cn/Article/details/gtzdmhihym.html

s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtxwpfzcsu.html

[U114] JS：JSON 深比较
来源：http://dali.chenjidiqi.icu/Article/details/gtzmsmsocr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xylfe.cn/Article/details/gtugqbnpdj.html

[U115] JS：生成 UUID
来源：http://dali.zhengqikj.top/Article/details/gtoncbsavx.html

crypto.randomUUID()
来源：http://dali.yuxming.cn/Article/details/gtmndrwnaw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.aizwys.cn/Article/details/gtsbvmbfkb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ehwqpu.com/Article/details/gtqchkdnpe.html

[U117] JS：单元测试
来源：http://dali.zdqjudy.top/Article/details/gtqxewvmzh.html

npm i -D vitest;  npx vitest
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkrvtata.html

[U118] JS：开发服务器
来源：http://dali.hfpthk.cn/Article/details/gttwfznjwx.html

npm i -D vite;  npx vite
来源：http://dali.sysykeji.top/Article/details/gtpivoknds.html

[U119] JS：生产构建
来源：http://dali.meibo888.top/Article/details/gtbsimdldt.html

npx vite build
来源：http://dali.gogol.net.cn/Article/details/gtloimpsvv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.tian-w.cn/Article/details/gtkwbfbqnz.html

import.meta.env.VITE_API_URL
来源：http://dali.cqqwz.cn/Article/details/gthxxejtxg.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtqiuhfgix.html

统计汇总
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwseqtfbl.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtqvlnhcen.html

按语言统计（条）：
来源：http://dali.svipenyu.cn/Article/details/gtupowhseq.html

Python ......... 252
来源：http://dali.ywan-chungtsiang.top/Article/details/gtatmchtqw.html

PHP ............ 252
来源：http://dali.ivvv.top/Article/details/gtacttzwcv.html

JavaScript ..... 252
来源：http://dali.aibaodan.cn/Article/details/gtwmmbguwz.html

TypeScript ..... 212
来源：http://dali.nanxuanxn.top/Article/details/gtcbqwpfeb.html

Java ........... 212
来源：http://dali.hysaishi.cn/Article/details/gtqdqarwsg.html

Go ............. 212
来源：http://dali.chenlongwang.top/Article/details/gtreplvace.html

Ruby ........... 212
来源：http://dali.quarkkingdee.top/Article/details/gtcmyxhzin.html

C# ............. 212
来源：http://dali.tanke756.top/Article/details/gtypoyatdr.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gtzlcjbxno.html

C++ ............ 30
来源：http://dali.zycfv.cn/Article/details/gtjgzxyfhb.html

SQL ............ 90
来源：http://dali.nanxinkj.top/Article/details/gtvgsifbre.html

Bash ........... 80
来源：http://dali.guannengcc.top/Article/details/gtorqyivnb.html

Kotlin ......... 15
来源：http://dali.cashguo.top/Article/details/gtgicgqzmu.html

Swift .......... 15
来源：http://dali.9152youxi.cn/Article/details/gtgrwvcrnd.html

Lua ............ 10
来源：http://dali.jlsjyb.cn/Article/details/gtgkworuui.html

Perl ........... 10
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvirfvqxn.html

Scala .......... 10
来源：http://dali.havefunace.top/Article/details/gtqgzysvtp.html

------------------------------------
来源：http://dali.nanxuanxn.top/Article/details/gtfpfdgiuj.html

合计 ........... 2106 条
来源：http://dali.daria6918.cn/Article/details/gtyiucrdsg.html

按章节统计：
来源：http://dali.tianlin.xyz/Article/details/gtslbxktze.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.guowangkeji.top/Article/details/gtcifiubyg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.tanke756.top/Article/details/gtrodjadqn.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ppjwa.cn/Article/details/gtuanyogjp.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yangfankeji.com/Article/details/gtirblmutt.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.tian-w.cn/Article/details/gtyfjkivuz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.shangyingyoupin.top/Article/details/gtdyjhblaj.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yueranfly.top/Article/details/gtldlxnoms.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jlsjyb.cn/Article/details/gtqxdwwgcj.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.cashguo.top/Article/details/gteqfqqaek.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ydzc1.top/Article/details/gtwypptmma.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xylfe.cn/Article/details/gtojlyfppt.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.chenlongwang.top/Article/details/gteypnrtkw.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.fengsongda.top/Article/details/gthojpteyd.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.gogol.net.cn/Article/details/gtrsfhylsg.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.nanxinkj.top/Article/details/gtybvnorbg.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.chenlongwang.top/Article/details/gtguvnivzx.html

Q SQL 专题                              90
来源：http://dali.cqqwz.cn/Article/details/gtshdblleq.html

R Bash 专题                             80
来源：http://dali.cheryme.top/Article/details/gttalcinix.html

S C / C++ 专题                          60
来源：http://dali.zhongyouzk.top/Article/details/gtyaxumzbk.html

T 其他语言补充                          60
来源：http://dali.xinyue.icu/Article/details/gtqhrwpdyb.html

U 高频实用片段                         120
来源：http://dali.jqgufenzy.top/Article/details/gttqdgixbw.html

------------------------------------
来源：http://dali.snrcjt.cn/Article/details/gtuctekexh.html

合计                                  2106 条
来源：http://dali.zhiwuduotai.top/Article/details/gtowmafzug.html

--------------------------------------------------------------------------------
来源：http://dali.haohaochexian.top/Article/details/gtspokqwrw.html

使用提醒
来源：http://dali.ehwqpu.com/Article/details/gtubiebfxk.html

--------------------------------------------------------------------------------
来源：http://dali.jinghuilouyu.cn/Article/details/gtpuiwiivc.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.shuidangran.top/Article/details/gtljisrbsp.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.cashguo.top/Article/details/gtqvtavitx.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.chenzaomai.com/Article/details/gtwuuljkus.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.pycfn.com/Article/details/gtsengnanr.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yj202588.top/Article/details/gtclhimptp.html

—— 文件结束 ——
来源：http://dali.jlsjyb.cn/Article/details/gtwcgcabzo.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtjeyphqxw.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.shanyushiyangtech.top/Article/details/gtpzodzkvs.html

Common Programming Examples Cheat Book
来源：http://dali.zdqjudy.top/Article/details/gtqfzysaxy.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtdunpkcmq.html

【收录内容】
来源：http://dali.pengpengdd.cyou/Article/details/gtqtkrgiaf.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jqgfzy.top/Article/details/gtumluugxa.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.dianchejie.cn/Article/details/gtgowltlob.html

SQL · Bash · C · C++
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtonkpafhe.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jqgufenzy.top/Article/details/gtfxoqbeby.html

【使用说明】
来源：http://dali.jinqigfzy.top/Article/details/gtrnkbmaye.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.nanxinkj.top/Article/details/gtlrasnqew.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhixingplan.top/Article/details/gtmuiaqnpr.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hfpthk.cn/Article/details/gtwxhcrqjw.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.daria6918.cn/Article/details/gtvboactjy.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.tian-w.cn/Article/details/gtbnrtexvm.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.chenjidiqi.icu/Article/details/gtcpcnycdy.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zycfv.cn/Article/details/gtmfdslcxs.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.gotoacloud.top/Article/details/gtzucjtbrb.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.0kj1m.cn/Article/details/gtidreqvks.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.wangshuangyany.cn/Article/details/gtprhfzazs.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.fengsongda.top/Article/details/gteibginen.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.bjfxy.top/Article/details/gtizdtgvbh.html

【文件统计】
来源：http://dali.aibaodan.cn/Article/details/gtzyidscrr.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.pengpengdd.cyou/Article/details/gtcyjucnbq.html

--------------------------------------------------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gtzuabuohf.html

目  录
来源：http://dali.zhongyouzk.top/Article/details/gtowdyqtru.html

--------------------------------------------------------------------------------
来源：http://dali.sufxvd.cn/Article/details/gtzsumdwaw.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.fzhhl.top/Article/details/gtqrmynata.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhixingplan.top/Article/details/gthtkwncwi.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.cdnleiting.top/Article/details/gtfkgmvqse.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtligfdehp.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.chenzaomai.com/Article/details/gtynmtnxgs.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtavmhpbdm.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.ppjwa.cn/Article/details/gtciyeiunc.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zycfv.cn/Article/details/gttmcozxfm.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yanxiufei.cn/Article/details/gttlrniqqx.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhoulong.xyz/Article/details/gthlzmjrky.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.9152youxi.cn/Article/details/gtnfozxaru.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.xinyue.icu/Article/details/gttbzzpvyd.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gtrqlbixdy.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yj202588.top/Article/details/gtgolknbep.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.haohaochexian.top/Article/details/gtmgohephj.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.tanke756.top/Article/details/gttdmzkexu.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.316326.xyz/Article/details/gthmoudcvi.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yonumen.top/Article/details/gtwnnfcjoy.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrbyscbp.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zycfv.cn/Article/details/gtddbvftjs.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.smart0.xyz/Article/details/gtlxtleqwh.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtugubqgxq.html

A. 基础语法与类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtpoxrddwz.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtixgbgsyd.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtzxgnbdtd.html

Py:   print("Hello, World!")
来源：http://dali.gaohongyu789.top/Article/details/gtcgcgpgfa.html

PHP:  echo "Hello, World!";
来源：http://dali.yonumen.top/Article/details/gtmbgihacb.html

JS:   console.log("Hello, World!");
来源：http://dali.shanyushiyangtech.top/Article/details/gtwtzqapmp.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.c1oappe.top/Article/details/gtrcdoxzxp.html

Java: System.out.println("Hello, World!");
来源：http://dali.jinqigfzy.top/Article/details/gtpkbmwwft.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.hysaishi.cn/Article/details/gtncsfeibo.html

Ruby: puts "Hello, World!"
来源：http://dali.andypj.xyz/Article/details/gtngkpzwah.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hywenlv.cn/Article/details/gtlothprzt.html

[A02] 变量声明与赋值
来源：http://dali.yuanzhike.top/Article/details/gthtndayjp.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jqgufenzy.top/Article/details/gtkzflbnuo.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.xziqi.cn/Article/details/gtlkopckdd.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jyoumei.cn/Article/details/gtbdavfcbv.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhongyouzk.top/Article/details/gthatijdra.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yuanzhike.top/Article/details/gtvveaivgv.html

Go:   name := "Alex"; age := 20
来源：http://dali.cqqwz.cn/Article/details/gtulnzbxpb.html

Ruby: name = "Alex"; age = 20
来源：http://dali.tianlin.xyz/Article/details/gtizpvcfir.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.iojbl.cn/Article/details/gtncmpdvqj.html

[A03] 常量定义
来源：http://dali.redwolf501.top/Article/details/gtdoknfwws.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.andypj.xyz/Article/details/gtdeidiafm.html

PHP:  const PI = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gtizwechpk.html

JS:   const PI = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gtekodhnrf.html

TS:   const PI: number = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gtvqgobqlg.html

Java: static final double PI = 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gtduiztoaw.html

Go:   const PI = 3.14159
来源：http://dali.guannengcc.top/Article/details/gtbwffcfov.html

Ruby: PI = 3.14159
来源：http://dali.mhx1999.top/Article/details/gtizvhonmx.html

C#:   const double PI = 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gtwouyyhez.html

[A04] 判断变量类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtbryrirnz.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yongpay.top/Article/details/gtuqtffyyg.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.ppjwa.cn/Article/details/gtqeoglgqa.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.xuanzx.com/Article/details/gtfpitbhor.html

TS:   typeof x; x instanceof Date
来源：http://dali.xylfe.cn/Article/details/gtdccblnkw.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gtqwicykzc.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.xuetiantiany.cn/Article/details/gtoeuhalme.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.chenjidiqi.icu/Article/details/gtoslrlfpp.html

C#:   x.GetType().Name; x is int
来源：http://dali.cqqwz.cn/Article/details/gtuabyitlc.html

[A05] 整数除法与取模
来源：http://dali.shanyushiyangtech.top/Article/details/gtqdwhaivs.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.shangyingyoupin.top/Article/details/gtgqegdcjy.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.xylfe.cn/Article/details/gtuwrptpku.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gtnnhzdsqe.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.gzhubu.top/Article/details/gtyjctttrg.html

Java: 7 / 2; 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gtjiaugrfq.html

Go:   7 / 2; 7 % 2
来源：http://dali.yongpay.top/Article/details/gtjizsxibg.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yuxming.cn/Article/details/gttmihqbdw.html

C#:   7 / 2; 7 % 2
来源：http://dali.chenzaomai.com/Article/details/gtnzzgslqp.html

[A06] 字符串转数字
来源：http://dali.yangfankeji.com/Article/details/gtubwkrunj.html

Py:   int("42"); float("3.14")
来源：http://dali.shangyingyoupin.top/Article/details/gtmodczlqr.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.aibaodan.cn/Article/details/gtbksvwfzk.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.shanyushiyangtech.top/Article/details/gtstewaenv.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhengqikj.top/Article/details/gtkvsuwhiu.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhongyouzk.top/Article/details/gtrqisiuia.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.daxiang520.top/Article/details/gtjxyzbezv.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jinqigfzy.top/Article/details/gtcnxllyoq.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.nanxuanxn.top/Article/details/gttxsjrjfh.html

[A07] 数字转字符串
来源：http://dali.gaohongyu789.top/Article/details/gtwpugjksn.html

Py:   str(42)
来源：http://dali.cheryme.top/Article/details/gtnqcwpsdq.html

PHP:  (string) 42; strval(42)
来源：http://dali.daria6918.cn/Article/details/gtjwibhgtg.html


<!-- 参考信息 -->