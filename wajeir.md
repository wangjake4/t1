代发 wailian999

[U47] PHP：联合类型
来源：http://dali.yuxming.cn/Article/details/gtysxuchai.html

int|string $id
来源：http://dali.yonumen.top/Article/details/gtxxcolrgv.html

[U48] PHP：纯枚举
来源：http://dali.yueranfly.top/Article/details/gtttuajvim.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.birdmap.top/Article/details/gtpuzkcaws.html

[U49] PHP：只读属性
来源：http://dali.cheryme.top/Article/details/gtbexgdujc.html

public readonly string $name
来源：http://dali.yueranfly.top/Article/details/gtjaoqfusr.html

[U50] PHP：构造器属性提升
来源：http://dali.shuidangran.top/Article/details/gtbpjwykye.html

public function __construct(private int $id) {}
来源：http://dali.fzhhl.top/Article/details/gtyotdehaa.html

[U51] PHP：数组解构
来源：http://dali.cashguo.top/Article/details/gtyurszaee.html

[$a, $b] = $arr;
来源：http://dali.gotoacloud.top/Article/details/gtanfcrstp.html

[U52] PHP：箭头函数
来源：http://dali.shzxlz.cn/Article/details/gtatswiusc.html

$double = fn($x) => $x * 2;
来源：http://dali.yvedp.cn/Article/details/gtjluhzjlh.html

[U53] PHP：空合并运算符
来源：http://dali.sweek.top/Article/details/gtqxfglfft.html

$v = $a ?? $b ?? "default";
来源：http://dali.cdnleiting.top/Article/details/gtrpdoxiem.html

[U54] PHP：空安全调用
来源：http://dali.gzhubu.top/Article/details/gtpmvyyrci.html

$obj?->method()
来源：http://dali.dashuyun.cn/Article/details/gtfjsszrdp.html

[U55] PHP：match 表达式
来源：http://dali.yuanzhike.top/Article/details/gtnctjbsjc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbsjoquxm.html

[U56] PHP：命名参数
来源：http://dali.hywenlv.cn/Article/details/gtytthionw.html

f(a: 1, b: 2)
来源：http://dali.fzhhl.top/Article/details/gtcsgarpua.html

[U57] PHP：字符串插值
来源：http://dali.jyoumei.cn/Article/details/gtsyhbxyow.html

"值: {$a}"
来源：http://dali.sysykeji.top/Article/details/gtxyzlmarg.html

[U58] PHP：数组三件套
来源：http://dali.chenzaomai.com/Article/details/gtneamvjlf.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ivvv.top/Article/details/gtyxtqzfpc.html

[U59] PHP：自定义排序
来源：http://dali.zhongyouzk.top/Article/details/gtebgpezdu.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guannengcc.top/Article/details/gtrcsqywwb.html

[U60] PHP：JSON 编解码
来源：http://dali.xuetiantiany.cn/Article/details/gtxitpprvi.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.aibaodan.cn/Article/details/gtqprhnjmq.html

[U61] PHP：正则
来源：http://dali.jiagoushi.top/Article/details/gtcjelskdt.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zdqjudy.top/Article/details/gtwldlasym.html

[U62] PHP：日期对象
来源：http://dali.zhengqikj.top/Article/details/gtmdchvkbf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.wangshuangyany.cn/Article/details/gtaspesbxa.html

[U63] PHP：文件读写
来源：http://dali.9152youxi.cn/Article/details/gtiatngkdn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.ydzc1.top/Article/details/gtevrfbnsb.html

[U64] PHP：目录遍历
来源：http://dali.c1oappe.top/Article/details/gtgwqhdqus.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zycfv.cn/Article/details/gtiwwdvppx.html

[U65] PHP：会话
来源：http://dali.birdmap.top/Article/details/gtmdeamvjd.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.tian-w.cn/Article/details/gtiwuqjdzo.html

[U66] PHP：设置 Cookie
来源：http://dali.tanke756.top/Article/details/gtjhquyztc.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.hnqzz.top/Article/details/gttqtfhymc.html

[U67] PHP：处理文件上传
来源：http://dali.xinyue.icu/Article/details/gtkonfqyhm.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.quarkkingdee.top/Article/details/gtcnjmbymd.html

[U68] PHP：PDO 连接
来源：http://dali.kuanghao11.cn/Article/details/gtkmwverwu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.ydzc1.top/Article/details/gtqflpavyz.html

[U69] PHP：PDO 预处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcpbsoker.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.shuidangran.top/Article/details/gtegogcrvf.html

[U70] PHP：PDO 事务
来源：http://dali.9152youxi.cn/Article/details/gtvydethcw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.xuetiantiany.cn/Article/details/gtxzdxmnss.html

[U71] PHP：抛出异常
来源：http://dali.sxryk.cn/Article/details/gtewxhinny.html

throw new RuntimeException("失败", 500);
来源：http://dali.ydzc1.top/Article/details/gtdwjuksqy.html

[U72] PHP：写错误日志
来源：http://dali.svipenyu.cn/Article/details/gtrnzqpewi.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hysaishi.cn/Article/details/gtsytflumk.html

[U73] PHP：读取 ini 配置
来源：http://dali.xuetiantiany.cn/Article/details/gtrmizhfvc.html

parse_ini_file("config.ini", true)
来源：http://dali.yonumen.top/Article/details/gtuykmwire.html

[U74] PHP：读取环境变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gteztmqzlb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zycfv.cn/Article/details/gtwfnuwwcw.html

[U75] PHP：依赖注入
来源：http://dali.aizwys.cn/Article/details/gtltiqfzfy.html

composer require psr/container
来源：http://dali.jyoumei.cn/Article/details/gtexbtbyie.html

[U76] PHP：简单路由
来源：http://dali.pycfn.com/Article/details/gtshvxhuok.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.sweek.top/Article/details/gtocuvtugj.html

[U77] PHP：模板渲染
来源：http://dali.meibo888.top/Article/details/gttjifsqjm.html

composer require twig/twig
来源：http://dali.daxiang520.top/Article/details/gtgwvhvdgg.html

[U78] PHP：单元测试
来源：http://dali.iojbl.cn/Article/details/gtgydwdeex.html

composer require --dev phpunit/phpunit
来源：http://dali.meibo888.top/Article/details/gtvkqvfsyd.html

[U79] PHP：静态分析
来源：http://dali.chenjidiqi.icu/Article/details/gtijijbjal.html

composer require --dev phpstan/phpstan
来源：http://dali.dashuyun.cn/Article/details/gtpqylgxuy.html

[U80] PHP：代码规范修复
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzblrkrdo.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.sweek.top/Article/details/gtbyarnyiv.html

[U81] JS：初始化项目
来源：http://dali.daxiang520.top/Article/details/gtqkljjvaf.html

npm init -y;  npm i express
来源：http://dali.shangyingyoupin.top/Article/details/gteezdwrud.html

[U82] JS：package.json 脚本
来源：http://dali.jlsjyb.cn/Article/details/gtjgcserhl.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhoulong.xyz/Article/details/gtktjhuzww.html

[U83] JS：ES Module 导入导出
来源：http://dali.jinqigfzy.top/Article/details/gtokhjingk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.9152youxi.cn/Article/details/gtzkctndws.html

[U84] JS：CommonJS 写法
来源：http://dali.dashuyun.cn/Article/details/gtctgflxey.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.wangdashe.top/Article/details/gtrqttgobl.html

[U85] JS：可选链
来源：http://dali.redwolf501.top/Article/details/gtcipyahwt.html

a?.b?.c
来源：http://dali.birdmap.top/Article/details/gtbwcrvuvx.html

[U86] JS：空值合并
来源：http://dali.tian-w.cn/Article/details/gtifwrtqit.html

a ?? b
来源：http://dali.gaohongyu789.top/Article/details/gtxnajfoxu.html

[U87] JS：解构默认值
来源：http://dali.nanxuanxn.top/Article/details/gtuyhtdgqr.html

const { a = 1, b = 2 } = obj;
来源：http://dali.ybcxt.top/Article/details/gtwojxsbcj.html

[U88] JS：对象展开合并
来源：http://dali.meibo888.top/Article/details/gtqmrrzoak.html

{ ...a, ...b }
来源：http://dali.andypj.xyz/Article/details/gttawiycgc.html

[U89] JS：数组去重
来源：http://dali.aibaodan.cn/Article/details/gtcpxjyhph.html

[...new Set(arr)]
来源：http://dali.daxiang520.top/Article/details/gtmixvfbui.html

[U90] JS：数字数组排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtscztvrwf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.aibaodan.cn/Article/details/gtqddbefio.html

[U91] JS：对象键值遍历
来源：http://dali.yuanzhike.top/Article/details/gtogftxcxz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.aibaodan.cn/Article/details/gtpuuksmio.html

[U92] JS：深拷贝
来源：http://dali.guowangkeji.top/Article/details/gtevacjmsk.html

structuredClone(obj)
来源：http://dali.jinqigufen.top/Article/details/gtgptefsdr.html

[U93] JS：模板字符串
来源：http://dali.cucudq.cn/Article/details/gtwyisdkfp.html

`共 ${n} 条`
来源：http://dali.andypj.xyz/Article/details/gtxxozsfkw.html

[U94] JS：箭头函数
来源：http://dali.yongpay.top/Article/details/gtdhgfdtmt.html

const double = x => x * 2;
来源：http://dali.ivvv.top/Article/details/gtqgnwjrbn.html

[U95] JS：Promise 包装
来源：http://dali.haohaochexian.top/Article/details/gtxkzwqfkr.html

new Promise((resolve, reject) => {})
来源：http://dali.nanxinkj.top/Article/details/gtgobfraos.html

[U96] JS：async/await 与异常
来源：http://dali.daria6918.cn/Article/details/gtfdnmzqnq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gtgxzulehe.html

[U97] JS：并发请求
来源：http://dali.guannengcc.top/Article/details/gtivanfajf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtylkumqmu.html

[U98] JS：fetch 带 JSON
来源：http://dali.xuetiantiany.cn/Article/details/gtbgtahcir.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shzxlz.cn/Article/details/gtiveeltlo.html

[U99] JS：事件监听
来源：http://dali.shanyushiyangkeji.top/Article/details/gtowjmyrbq.html

el.addEventListener("click", e => {})
来源：http://dali.cdnleiting.top/Article/details/gtphepvzmv.html

[U100] JS：DOM 查询
来源：http://dali.cdnleiting.top/Article/details/gtguiklxlc.html

document.querySelector(".item")
来源：http://dali.hammf.cn/Article/details/gtaqpdlchx.html

[U101] JS：classList 操作
来源：http://dali.hammf.cn/Article/details/gtljwsnqdn.html

el.classList.toggle("active")
来源：http://dali.cqqwz.cn/Article/details/gtasyvbgul.html

[U102] JS：本地存储
来源：http://dali.redwolf501.top/Article/details/gtyoytidxl.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hammf.cn/Article/details/gtqgprdqre.html

[U103] JS：定时器
来源：http://dali.snrcjt.cn/Article/details/gtmyyktiec.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.wangshuangyany.cn/Article/details/gtoxclfxcu.html

[U104] JS：防抖
来源：http://dali.yvedp.cn/Article/details/gtvtqpszia.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.smart0.xyz/Article/details/gtzrwofhio.html

[U105] JS：节流
来源：http://dali.0kj1m.cn/Article/details/gttebyfehr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yangfankeji.com/Article/details/gtaesycdbp.html

[U106] JS：日期格式化
来源：http://dali.guannengcc.top/Article/details/gtuoyoqkzg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yonumen.top/Article/details/gttulugbbn.html

[U107] JS：数字千分位
来源：http://dali.pycfn.com/Article/details/gtltyvvjdy.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhongyouzk.top/Article/details/gtihknamds.html

[U108] JS：随机整数
来源：http://dali.cqqwz.cn/Article/details/gtjfpwaxgk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.redwolf501.top/Article/details/gtsvrivnhm.html

[U109] JS：数组分组
来源：http://dali.pycfn.com/Article/details/gtdlauofyl.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwzrlscpd.html

[U110] JS：数组分块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmgjebmxw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hnqzz.top/Article/details/gtgkrmtkny.html

[U111] JS：对象转 Map
来源：http://dali.guowangkeji.top/Article/details/gtqazqrxfr.html

new Map(Object.entries(obj))
来源：http://dali.chenzaomai.com/Article/details/gtnzbghyll.html

[U112] JS：字符串补位
来源：http://dali.chenlongwang.top/Article/details/gtgxylqhft.html

"7".padStart(3, "0")
来源：http://dali.fzhhl.top/Article/details/gtsmleorcf.html

[U113] JS：正则替换全部
来源：http://dali.jinqigfzy.top/Article/details/gtodkgyqdf.html

s.replaceAll("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gtrbimmlls.html

[U114] JS：JSON 深比较
来源：http://dali.hfpthk.cn/Article/details/gtiultplop.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxuanxn.top/Article/details/gtrxpbgrta.html

[U115] JS：生成 UUID
来源：http://dali.hongshengwenyu.top/Article/details/gtutleefwk.html

crypto.randomUUID()
来源：http://dali.fengsongda.top/Article/details/gtjrbgstlr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zdqjudy.top/Article/details/gtrcsrlrei.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jianghu66.top/Article/details/gtbwmiudmy.html

[U117] JS：单元测试
来源：http://dali.ivvv.top/Article/details/gtklimcvrr.html

npm i -D vitest;  npx vitest
来源：http://dali.iojbl.cn/Article/details/gtztzcupmz.html

[U118] JS：开发服务器
来源：http://dali.shzxlz.cn/Article/details/gtdyvetbss.html

npm i -D vite;  npx vite
来源：http://dali.xuanzx.com/Article/details/gtoaidnwjb.html

[U119] JS：生产构建
来源：http://dali.sweek.top/Article/details/gtkhwpvnzp.html

npx vite build
来源：http://dali.jlsjyb.cn/Article/details/gtfyhhlrgb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cdnleiting.top/Article/details/gtgxmmuijg.html

import.meta.env.VITE_API_URL
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjzmlcfdn.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtijyxxylu.html

统计汇总
来源：http://dali.hywenlv.cn/Article/details/gtwhbpfhie.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtqfmjgule.html

按语言统计（条）：
来源：http://dali.quarkkingdee.top/Article/details/gtwdwejkev.html

Python ......... 252
来源：http://dali.yonumen.top/Article/details/gtqxanzqbd.html

PHP ............ 252
来源：http://dali.hfpthk.cn/Article/details/gtlswxjuuq.html

JavaScript ..... 252
来源：http://dali.chenjidiqi.icu/Article/details/gtykmaxosj.html

TypeScript ..... 212
来源：http://dali.yangfankeji.com/Article/details/gtkyfbjbrg.html

Java ........... 212
来源：http://dali.shanyushiyangtech.top/Article/details/gttmkwudbz.html

Go ............. 212
来源：http://dali.cashguo.top/Article/details/gtawrvubio.html

Ruby ........... 212
来源：http://dali.gotoacloud.top/Article/details/gtfnnfxvjf.html

C# ............. 212
来源：http://dali.yonumen.top/Article/details/gtfozvnzaf.html

C .............. 30
来源：http://dali.birdmap.top/Article/details/gtsisgnqrz.html

C++ ............ 30
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlcwefxpo.html

SQL ............ 90
来源：http://dali.hnxiangtu.top/Article/details/gtggsvpohc.html

Bash ........... 80
来源：http://dali.svipenyu.cn/Article/details/gtavgyuqmf.html

Kotlin ......... 15
来源：http://dali.jiagoushi.top/Article/details/gtzccqyuet.html

Swift .......... 15
来源：http://dali.c1oappe.top/Article/details/gtnegfgdtd.html

Lua ............ 10
来源：http://dali.chenzaomai.com/Article/details/gtdvclmpkp.html

Perl ........... 10
来源：http://dali.yuxming.cn/Article/details/gthbwerwuc.html

Scala .......... 10
来源：http://dali.hywenlv.cn/Article/details/gtqcxbqrse.html

------------------------------------
来源：http://dali.hywenlv.cn/Article/details/gtixjvrobv.html

合计 ........... 2106 条
来源：http://dali.cucudq.cn/Article/details/gtquhjuoca.html

按章节统计：
来源：http://dali.xinyue.icu/Article/details/gtkgglhbkr.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yangfankeji.com/Article/details/gtchqskjxt.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.redwolf501.top/Article/details/gtjbfwquuu.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ivvv.top/Article/details/gtspwwqobr.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.daxiang520.top/Article/details/gtccfqpaij.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.nwbrower.top/Article/details/gtrvvyyjxj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.aizwys.cn/Article/details/gtfzdcpruf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ydzc1.top/Article/details/gtbxgrjfhq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.tian-w.cn/Article/details/gtchvhjitz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gtgxlmgejx.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.meibo888.top/Article/details/gthmyhmbsv.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.wangshuangyany.cn/Article/details/gtdluezpqb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.redwolf501.top/Article/details/gtpdbnbvcb.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.xuetiantiany.cn/Article/details/gtkahxqizt.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.quarkkingdee.top/Article/details/gtmcjndlyf.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.gaohongyu789.top/Article/details/gtmwmnymrr.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.cqqwz.cn/Article/details/gtqilzsxyl.html

Q SQL 专题                              90
来源：http://dali.zycfv.cn/Article/details/gtvnditrks.html

R Bash 专题                             80
来源：http://dali.jyoumei.cn/Article/details/gtxhbcuwec.html

S C / C++ 专题                          60
来源：http://dali.daria6918.cn/Article/details/gtkzskzwih.html

T 其他语言补充                          60
来源：http://dali.gogol.net.cn/Article/details/gtrnmmxdsp.html

U 高频实用片段                         120
来源：http://dali.jqgufenzy.top/Article/details/gtvpfemhng.html

------------------------------------
来源：http://dali.hfpthk.cn/Article/details/gtbyegponm.html

合计                                  2106 条
来源：http://dali.xuetiantiany.cn/Article/details/gthkiiruit.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangtech.top/Article/details/gtwrfhmyzq.html

使用提醒
来源：http://dali.ywan-chungtsiang.top/Article/details/gtibdlgksk.html

--------------------------------------------------------------------------------
来源：http://dali.0kj1m.cn/Article/details/gtpnxbsind.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jinghuilouyu.cn/Article/details/gtrtwsaegv.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.iojbl.cn/Article/details/gtyxihiazv.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.kuanghao11.cn/Article/details/gtneoasjhh.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.chenlongwang.top/Article/details/gtxuzwtvlc.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jinqigufen.top/Article/details/gtzazylgqv.html

—— 文件结束 ——
来源：http://dali.nanxuanxn.top/Article/details/gteymcmweo.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gteqjgmphr.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jinqigufen.top/Article/details/gtsniumgkn.html

Common Programming Examples Cheat Book
来源：http://dali.gzhubu.top/Article/details/gtbdgrrvch.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gthgllywmn.html

【收录内容】
来源：http://dali.xuanzx.com/Article/details/gtbnhxlbyp.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jiagoushi.top/Article/details/gtbhbyvvyy.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.iojbl.cn/Article/details/gtknufdybx.html

SQL · Bash · C · C++
来源：http://dali.cqqwz.cn/Article/details/gtbwjpvshb.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yj20258888.top/Article/details/gtedafnnwk.html

【使用说明】
来源：http://dali.jiagoushi.top/Article/details/gtchxcekls.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.nanxuanxn.top/Article/details/gtdgkaltrn.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.316326.xyz/Article/details/gtnucluxln.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.chenzaomai.com/Article/details/gtixyjvdxw.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.guowangkeji.top/Article/details/gtkdzgqgtx.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yangfankeji.com/Article/details/gtkgwbudga.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.xuanzx.com/Article/details/gtnikahttu.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.9152youxi.cn/Article/details/gtcmtivqsd.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.redwolf501.top/Article/details/gtrdzajniu.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.redwolf501.top/Article/details/gtlteqrggx.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.pengpengdd.cyou/Article/details/gtpeoygkyx.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.shangyingyoupin.top/Article/details/gteewzurzk.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.chenlongwang.top/Article/details/gtqyvgxtim.html

【文件统计】
来源：http://dali.fzhhl.top/Article/details/gtxifqoqdo.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhixingplan.top/Article/details/gtcexgmmaw.html

--------------------------------------------------------------------------------
来源：http://dali.jiagoushi.top/Article/details/gtbhcrqzxr.html

目  录
来源：http://dali.nwbrower.top/Article/details/gtbzjebzbe.html

--------------------------------------------------------------------------------
来源：http://dali.shuidangran.top/Article/details/gtygmwzyfl.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yangfankeji.com/Article/details/gtjyihucxx.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.xuanzx.com/Article/details/gtjwlktjgl.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhoulong.xyz/Article/details/gtnwzbfppx.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.cucudq.cn/Article/details/gtqyuhkyjb.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yongpay.top/Article/details/gtgyypcvdx.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.ehwqpu.com/Article/details/gtmiafexdo.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.fengsongda.top/Article/details/gtrnqquwxu.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.ybcxt.top/Article/details/gttsjymkzi.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.smart0.xyz/Article/details/gtfkqphrka.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jlsjyb.cn/Article/details/gtgyxfjemv.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.quarkkingdee.top/Article/details/gtvjwrphjk.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.9152youxi.cn/Article/details/gtnkpkffmw.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.dianchejie.cn/Article/details/gtczkenvkw.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.hammf.cn/Article/details/gtfsnupbry.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbpacykdy.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.cashguo.top/Article/details/gtsvzladzt.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtfucnuhax.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yueranfly.top/Article/details/gtykoyvzvm.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.cucudq.cn/Article/details/gttpfkpcss.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sysykeji.top/Article/details/gtddyoonkj.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.xylfe.cn/Article/details/gthgkmjfzc.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtjpdwkhoz.html

A. 基础语法与类型
来源：http://dali.zycfv.cn/Article/details/gtvowqsyac.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtldbhwilk.html

[A01] Hello World
来源：http://dali.jyoumei.cn/Article/details/gtxlgutckd.html

Py:   print("Hello, World!")
来源：http://dali.tanke756.top/Article/details/gtjdvolusl.html

PHP:  echo "Hello, World!";
来源：http://dali.hnxiangtu.top/Article/details/gteglibqch.html

JS:   console.log("Hello, World!");
来源：http://dali.meibo888.top/Article/details/gtyqnosfoi.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiyprlvvu.html

Java: System.out.println("Hello, World!");
来源：http://dali.cucudq.cn/Article/details/gtjkbqplmf.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.redwolf501.top/Article/details/gtzydmfffc.html

Ruby: puts "Hello, World!"
来源：http://dali.yj20258888.top/Article/details/gtjdunfvwf.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhoulong.xyz/Article/details/gthkppemei.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gtnpbdnzzx.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.shzxlz.cn/Article/details/gtzkurvqde.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jyoumei.cn/Article/details/gtywnbwylm.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.tanke756.top/Article/details/gtfjchqvvq.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jqgufenzy.top/Article/details/gthikozixz.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zdqjudy.top/Article/details/gtmoloxvnk.html

Go:   name := "Alex"; age := 20
来源：http://dali.nanxinkj.top/Article/details/gterkkrmhm.html

Ruby: name = "Alex"; age = 20
来源：http://dali.0kj1m.cn/Article/details/gtwovtknam.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.hnqzz.top/Article/details/gtkmpadqxe.html

[A03] 常量定义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtorroasev.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.shzxlz.cn/Article/details/gtgylsibvo.html

PHP:  const PI = 3.14159;
来源：http://dali.hammf.cn/Article/details/gtjzqiewnx.html

JS:   const PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtikqlytzx.html

TS:   const PI: number = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtdqcuidvh.html

Java: static final double PI = 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gtnlqwuhoo.html

Go:   const PI = 3.14159
来源：http://dali.yj20258888.top/Article/details/gtcfjikgxu.html

Ruby: PI = 3.14159
来源：http://dali.pycfn.com/Article/details/gthhzmcfml.html

C#:   const double PI = 3.14159;
来源：http://dali.316326.xyz/Article/details/gtkedukabc.html

[A04] 判断变量类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpzykyxyd.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.ybcxt.top/Article/details/gtcmifusqj.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.hammf.cn/Article/details/gtwvcguwbw.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zycfv.cn/Article/details/gtnavfuswl.html

TS:   typeof x; x instanceof Date
来源：http://dali.gzhubu.top/Article/details/gtlsadssfa.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.tianlin.xyz/Article/details/gtzlovgebu.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.daria6918.cn/Article/details/gtlrgyisla.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhoulong.xyz/Article/details/gtzvyryipe.html

C#:   x.GetType().Name; x is int
来源：http://dali.sweek.top/Article/details/gtgappbrft.html

[A05] 整数除法与取模
来源：http://dali.ppjwa.cn/Article/details/gtdmddctrs.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.tanke756.top/Article/details/gtgzetuyfm.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gtzguotnig.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gthoyllftr.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.chenzaomai.com/Article/details/gtcxurjsdk.html

Java: 7 / 2; 7 % 2
来源：http://dali.fengsongda.top/Article/details/gtjpykpxou.html

Go:   7 / 2; 7 % 2
来源：http://dali.ehwqpu.com/Article/details/gtgxtroxxv.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.cashguo.top/Article/details/gtixbnaahs.html

C#:   7 / 2; 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gticulqasm.html


<!-- 参考信息 -->