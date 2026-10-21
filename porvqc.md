代发 wailian999

[U47] PHP：联合类型
来源：http://dali.nanxuanxn.top/Article/details/gtlytgumsj.html

int|string $id
来源：http://dali.yuxming.cn/Article/details/gtvbfthgrz.html

[U48] PHP：纯枚举
来源：http://dali.zhongyouzk.top/Article/details/gtegyoptgq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.chenzaomai.com/Article/details/gtvuxbhxvb.html

[U49] PHP：只读属性
来源：http://dali.cashguo.top/Article/details/gtmvyvfcex.html

public readonly string $name
来源：http://dali.sysykeji.top/Article/details/gtljqtbjed.html

[U50] PHP：构造器属性提升
来源：http://dali.havefunace.top/Article/details/gtesnndwqp.html

public function __construct(private int $id) {}
来源：http://dali.ybcxt.top/Article/details/gtqifvkped.html

[U51] PHP：数组解构
来源：http://dali.sufxvd.cn/Article/details/gtbfboxnbb.html

[$a, $b] = $arr;
来源：http://dali.cqqwz.cn/Article/details/gtpqfpkcit.html

[U52] PHP：箭头函数
来源：http://dali.yvedp.cn/Article/details/gtdnqagbdy.html

$double = fn($x) => $x * 2;
来源：http://dali.yj202588.top/Article/details/gtvlufdanv.html

[U53] PHP：空合并运算符
来源：http://dali.wangshuangyany.cn/Article/details/gtmkkyexcl.html

$v = $a ?? $b ?? "default";
来源：http://dali.ybcxt.top/Article/details/gtacmxvuhb.html

[U54] PHP：空安全调用
来源：http://dali.0kj1m.cn/Article/details/gtzknhzjtu.html

$obj?->method()
来源：http://dali.cdnleiting.top/Article/details/gtweetpaal.html

[U55] PHP：match 表达式
来源：http://dali.shuidangran.top/Article/details/gtqvpydvmn.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.cdnleiting.top/Article/details/gtwwbxmmgy.html

[U56] PHP：命名参数
来源：http://dali.hnxiangtu.top/Article/details/gtnqmhwmgv.html

f(a: 1, b: 2)
来源：http://dali.fengsongda.top/Article/details/gtctosyxhf.html

[U57] PHP：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gtzdgyxhew.html

"值: {$a}"
来源：http://dali.jiagoushi.top/Article/details/gtkxedcfho.html

[U58] PHP：数组三件套
来源：http://dali.feifeiyinyue.top/Article/details/gtajhojrca.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkzgzrct.html

[U59] PHP：自定义排序
来源：http://dali.jinqigufen.top/Article/details/gtqigzeyng.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuanzx.com/Article/details/gtdvexpcfv.html

[U60] PHP：JSON 编解码
来源：http://dali.andypj.xyz/Article/details/gtbkneotqc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.shangyingyoupin.top/Article/details/gtbwvccurv.html

[U61] PHP：正则
来源：http://dali.0kj1m.cn/Article/details/gtevzvwaue.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenlongwang.top/Article/details/gtsqfqtfby.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gtvcqcmihb.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.gzhubu.top/Article/details/gtwiwsgcwf.html

[U63] PHP：文件读写
来源：http://dali.yueranfly.top/Article/details/gtlmqktvoo.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hnxiangtu.top/Article/details/gtnlwjywzt.html

[U64] PHP：目录遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtakbefgav.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhixingplan.top/Article/details/gtydkaqfed.html

[U65] PHP：会话
来源：http://dali.jqgfzy.top/Article/details/gtufmhhpsu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gttjrokgpa.html

[U66] PHP：设置 Cookie
来源：http://dali.yanxiufei.cn/Article/details/gtmoelgexz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.chenlongwang.top/Article/details/gtslmrvxvw.html

[U67] PHP：处理文件上传
来源：http://dali.jqgfzy.top/Article/details/gtxzkropjn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.aizwys.cn/Article/details/gtioletbyc.html

[U68] PHP：PDO 连接
来源：http://dali.xuanzx.com/Article/details/gtaaxwygdt.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqqyoape.html

[U69] PHP：PDO 预处理
来源：http://dali.yonumen.top/Article/details/gtowptrqum.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.cheryme.top/Article/details/gtrpfikcel.html

[U70] PHP：PDO 事务
来源：http://dali.haohaochexian.top/Article/details/gtywhwuvab.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.meibo888.top/Article/details/gtkjwtdfpn.html

[U71] PHP：抛出异常
来源：http://dali.ydzc1.top/Article/details/gtcbcmfykv.html

throw new RuntimeException("失败", 500);
来源：http://dali.0kj1m.cn/Article/details/gtkwxxqgwz.html

[U72] PHP：写错误日志
来源：http://dali.jqgfzy.top/Article/details/gtmrjfeeqf.html

error_log("失败: " . $e->getMessage());
来源：http://dali.dashuyun.cn/Article/details/gtbapqufpw.html

[U73] PHP：读取 ini 配置
来源：http://dali.nanxuanxn.top/Article/details/gtowmfkgql.html

parse_ini_file("config.ini", true)
来源：http://dali.yuxming.cn/Article/details/gtdbrtzyhq.html

[U74] PHP：读取环境变量
来源：http://dali.ybcxt.top/Article/details/gtxvghcozp.html

getenv("APP_ENV") ?: "production"
来源：http://dali.xinyue.icu/Article/details/gtofkvdhnq.html

[U75] PHP：依赖注入
来源：http://dali.jiagoushi.top/Article/details/gtjdvpahqh.html

composer require psr/container
来源：http://dali.yongpay.top/Article/details/gttqyouvnd.html

[U76] PHP：简单路由
来源：http://dali.aibaodan.cn/Article/details/gtokbfbfax.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.pengpengdd.cyou/Article/details/gtmyjqkbyf.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gtbhqhzmnm.html

composer require twig/twig
来源：http://dali.shanyushiyangtech.top/Article/details/gtmbfxkfoq.html

[U78] PHP：单元测试
来源：http://dali.pycfn.com/Article/details/gtgbrluern.html

composer require --dev phpunit/phpunit
来源：http://dali.xinyue.icu/Article/details/gtbfcbtosf.html

[U79] PHP：静态分析
来源：http://dali.vqdsnc.cn/Article/details/gtpgpermzk.html

composer require --dev phpstan/phpstan
来源：http://dali.yangfankeji.com/Article/details/gtkawzwthb.html

[U80] PHP：代码规范修复
来源：http://dali.aizwys.cn/Article/details/gtuxmzbktn.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yonumen.top/Article/details/gtndozicdo.html

[U81] JS：初始化项目
来源：http://dali.smart0.xyz/Article/details/gtcykcebuo.html

npm init -y;  npm i express
来源：http://dali.yj202588.top/Article/details/gtpjcqwgef.html

[U82] JS：package.json 脚本
来源：http://dali.yueranfly.top/Article/details/gtrdjqrbof.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.fengsongda.top/Article/details/gttfdhyvxl.html

[U83] JS：ES Module 导入导出
来源：http://dali.c1oappe.top/Article/details/gtcoxtqujf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jqgufenzy.top/Article/details/gtbwhsbfel.html

[U84] JS：CommonJS 写法
来源：http://dali.hongshengwenyu.top/Article/details/gtmxsujepk.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.nanxuanxn.top/Article/details/gtamwvtzgi.html

[U85] JS：可选链
来源：http://dali.pengpengdd.cyou/Article/details/gtojbvlxpp.html

a?.b?.c
来源：http://dali.wangdashe.top/Article/details/gtugehnjfh.html

[U86] JS：空值合并
来源：http://dali.jqgfzy.top/Article/details/gtceruvwrd.html

a ?? b
来源：http://dali.gotoacloud.top/Article/details/gtzyzmwerh.html

[U87] JS：解构默认值
来源：http://dali.daria6918.cn/Article/details/gtlslqntqs.html

const { a = 1, b = 2 } = obj;
来源：http://dali.mhx1999.top/Article/details/gtnljqhcsf.html

[U88] JS：对象展开合并
来源：http://dali.meibo888.top/Article/details/gtlfmiflts.html

{ ...a, ...b }
来源：http://dali.mhx1999.top/Article/details/gtbvuekrep.html

[U89] JS：数组去重
来源：http://dali.gzhubu.top/Article/details/gtakiqvrpf.html

[...new Set(arr)]
来源：http://dali.daxiang520.top/Article/details/gtsboqcsny.html

[U90] JS：数字数组排序
来源：http://dali.sysykeji.top/Article/details/gtpcooagbk.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gtvrdlsxxo.html

[U91] JS：对象键值遍历
来源：http://dali.xylfe.cn/Article/details/gtfxyppxll.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.fengsongda.top/Article/details/gtnavcdbra.html

[U92] JS：深拷贝
来源：http://dali.gotoacloud.top/Article/details/gtphpxnngp.html

structuredClone(obj)
来源：http://dali.xziqi.cn/Article/details/gtltyyfavm.html

[U93] JS：模板字符串
来源：http://dali.bjfxy.top/Article/details/gtqzgxuvrc.html

`共 ${n} 条`
来源：http://dali.dashuyun.cn/Article/details/gtpwpkbjti.html

[U94] JS：箭头函数
来源：http://dali.sxryk.cn/Article/details/gtnqcvljig.html

const double = x => x * 2;
来源：http://dali.jiagoushi.top/Article/details/gtjwbfeyhg.html

[U95] JS：Promise 包装
来源：http://dali.shzxlz.cn/Article/details/gthejhvcoe.html

new Promise((resolve, reject) => {})
来源：http://dali.yvedp.cn/Article/details/gtunacoxkt.html

[U96] JS：async/await 与异常
来源：http://dali.chenzaomai.com/Article/details/gtutpjfsdb.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gtuywuvzmu.html

[U97] JS：并发请求
来源：http://dali.yongpay.top/Article/details/gttaowznfg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cdnleiting.top/Article/details/gtpqezyknd.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhoulong.xyz/Article/details/gtkpsbjfrd.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jqgufenzy.top/Article/details/gtarpalfpg.html

[U99] JS：事件监听
来源：http://dali.cqqwz.cn/Article/details/gtzkideywf.html

el.addEventListener("click", e => {})
来源：http://dali.nanxuanxn.top/Article/details/gtkczzirfc.html

[U100] JS：DOM 查询
来源：http://dali.hfpthk.cn/Article/details/gtftnsbotk.html

document.querySelector(".item")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzlpgjoqm.html

[U101] JS：classList 操作
来源：http://dali.xuanzx.com/Article/details/gtibmbidpt.html

el.classList.toggle("active")
来源：http://dali.ppjwa.cn/Article/details/gtyyzxlygk.html

[U102] JS：本地存储
来源：http://dali.meibo888.top/Article/details/gtwreqgyfs.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.nanxinkj.top/Article/details/gtqmodeido.html

[U103] JS：定时器
来源：http://dali.shzxlz.cn/Article/details/gtztefsbva.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.fengsongda.top/Article/details/gtdiqedrjp.html

[U104] JS：防抖
来源：http://dali.nwbrower.top/Article/details/gtdvrgzyiu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbzxlkcf.html

[U105] JS：节流
来源：http://dali.fzhhl.top/Article/details/gtvmktywpy.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.chenjidiqi.icu/Article/details/gtxhlkvpjx.html

[U106] JS：日期格式化
来源：http://dali.svipenyu.cn/Article/details/gtxueoiqti.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hnxiangtu.top/Article/details/gttuheovhh.html

[U107] JS：数字千分位
来源：http://dali.ppjwa.cn/Article/details/gtdxdpvsmg.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhengqikj.top/Article/details/gtdcrmmdmf.html

[U108] JS：随机整数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtapnziuuq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhiwuduotai.top/Article/details/gtrzrgucpl.html

[U109] JS：数组分组
来源：http://dali.gotoacloud.top/Article/details/gtqqzryqtb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.sysykeji.top/Article/details/gtokbhejqh.html

[U110] JS：数组分块
来源：http://dali.smart0.xyz/Article/details/gtxqnfyasi.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.daria6918.cn/Article/details/gtfzrzrxmk.html

[U111] JS：对象转 Map
来源：http://dali.zdqjudy.top/Article/details/gtylprafca.html

new Map(Object.entries(obj))
来源：http://dali.xinyue.icu/Article/details/gtpamocibg.html

[U112] JS：字符串补位
来源：http://dali.jqgufenzy.top/Article/details/gttnwbgpti.html

"7".padStart(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gtmehfddmb.html

[U113] JS：正则替换全部
来源：http://dali.hnxiangtu.top/Article/details/gtxkhkgdaz.html

s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtgyiexahr.html

[U114] JS：JSON 深比较
来源：http://dali.fengsongda.top/Article/details/gtndtrglzz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.mhx1999.top/Article/details/gtfzmdkckp.html

[U115] JS：生成 UUID
来源：http://dali.wangdashe.top/Article/details/gtverrifvw.html

crypto.randomUUID()
来源：http://dali.cheryme.top/Article/details/gtntmvgapq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.guannengcc.top/Article/details/gtllvylwyo.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xuanzx.com/Article/details/gtsyouykhl.html

[U117] JS：单元测试
来源：http://dali.bjfxy.top/Article/details/gtpnepgobm.html

npm i -D vitest;  npx vitest
来源：http://dali.cqqwz.cn/Article/details/gtyrtcwfye.html

[U118] JS：开发服务器
来源：http://dali.jiagoushi.top/Article/details/gtpfsktjwk.html

npm i -D vite;  npx vite
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcigqsylu.html

[U119] JS：生产构建
来源：http://dali.nanxinkj.top/Article/details/gtrelimjbp.html

npx vite build
来源：http://dali.cqqwz.cn/Article/details/gtiemekirt.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.sufxvd.cn/Article/details/gtormswifx.html

import.meta.env.VITE_API_URL
来源：http://dali.yongpay.top/Article/details/gtfkoftjsa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gthhzuzild.html

统计汇总
来源：http://dali.vqdsnc.cn/Article/details/gtyvtpghnk.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtfeysxwob.html

按语言统计（条）：
来源：http://dali.316326.xyz/Article/details/gtbpmoqhkf.html

Python ......... 252
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwstqszxc.html

PHP ............ 252
来源：http://dali.pycfn.com/Article/details/gtkuwqsdjw.html

JavaScript ..... 252
来源：http://dali.yangfankeji.com/Article/details/gtgznwpgtt.html

TypeScript ..... 212
来源：http://dali.haohaochexian.top/Article/details/gtpnewprec.html

Java ........... 212
来源：http://dali.meibo888.top/Article/details/gtyrsjxmvf.html

Go ............. 212
来源：http://dali.jianghu66.top/Article/details/gtkibwgsgp.html

Ruby ........... 212
来源：http://dali.hysaishi.cn/Article/details/gtpbbavosx.html

C# ............. 212
来源：http://dali.hnqzz.top/Article/details/gtsjbrkgim.html

C .............. 30
来源：http://dali.shanyushiyangtech.top/Article/details/gtuyzrycqj.html

C++ ............ 30
来源：http://dali.yonumen.top/Article/details/gtjbavsmsv.html

SQL ............ 90
来源：http://dali.hongshengwenyu.top/Article/details/gtvsevsldf.html

Bash ........... 80
来源：http://dali.c1oappe.top/Article/details/gtarqyuveu.html

Kotlin ......... 15
来源：http://dali.yuanzhike.top/Article/details/gtovjipnll.html

Swift .......... 15
来源：http://dali.smart0.xyz/Article/details/gtsckoevcc.html

Lua ............ 10
来源：http://dali.jqgufenzy.top/Article/details/gthbiusxqn.html

Perl ........... 10
来源：http://dali.hfpthk.cn/Article/details/gtmqxoyoaw.html

Scala .......... 10
来源：http://dali.gaohongyu789.top/Article/details/gthojqjewh.html

------------------------------------
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxguundb.html

合计 ........... 2106 条
来源：http://dali.zhaomingkeji.xyz/Article/details/gtphsuctul.html

按章节统计：
来源：http://dali.chenjidiqi.icu/Article/details/gtztptwtfp.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.316326.xyz/Article/details/gtlrwwirkx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yj20258.top/Article/details/gtpveuzqsg.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.daxiang520.top/Article/details/gtabaqfiuv.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gtvwhzcqva.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.tanke756.top/Article/details/gteyckmjxb.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.daxiang520.top/Article/details/gtrddvzzti.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.svipenyu.cn/Article/details/gtevgimakk.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yj20258.top/Article/details/gtszahzsrd.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yongpay.top/Article/details/gtrbgjvsst.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jinyuanbaomall.cn/Article/details/gtueqoisuw.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.c1oappe.top/Article/details/gtkhgifbel.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gtyhqafdis.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yonumen.top/Article/details/gtpchdmnkd.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.cheryme.top/Article/details/gtskpbtaiu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.xylfe.cn/Article/details/gtnqkgtpwp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yongpay.top/Article/details/gtuynlomtn.html

Q SQL 专题                              90
来源：http://dali.guannengcc.top/Article/details/gtobygxdax.html

R Bash 专题                             80
来源：http://dali.nanxuanxn.top/Article/details/gtxxrqbzro.html

S C / C++ 专题                          60
来源：http://dali.pycfn.com/Article/details/gtddgsiiec.html

T 其他语言补充                          60
来源：http://dali.cashguo.top/Article/details/gtncswdxgl.html

U 高频实用片段                         120
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwekxvnuy.html

------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gtholuhyzk.html

合计                                  2106 条
来源：http://dali.bjfxy.top/Article/details/gteewodlxa.html

--------------------------------------------------------------------------------
来源：http://dali.jyoumei.cn/Article/details/gtihkmrrgp.html

使用提醒
来源：http://dali.ivvv.top/Article/details/gtmkhfzhbe.html

--------------------------------------------------------------------------------
来源：http://dali.jinqigfzy.top/Article/details/gtqfmsmeea.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yueranfly.top/Article/details/gteucsojpa.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.pengpengdd.cyou/Article/details/gtwszmiunt.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.xylfe.cn/Article/details/gtyxpolekh.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.316326.xyz/Article/details/gtibvyrdjx.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hywenlv.cn/Article/details/gthpnnmlhr.html

—— 文件结束 ——
来源：http://dali.dashuyun.cn/Article/details/gtzfvrvxir.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlbwrmhuy.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.wangdashe.top/Article/details/gtvgzzljec.html

Common Programming Examples Cheat Book
来源：http://dali.guowangkeji.top/Article/details/gtqqlxpxwq.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtjqjmljne.html

【收录内容】
来源：http://dali.xziqi.cn/Article/details/gtciytjtuu.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yj20258.top/Article/details/gtvnhtnxfn.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtenzxxyqp.html

SQL · Bash · C · C++
来源：http://dali.yanxiufei.cn/Article/details/gtmiageoja.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.haohaochexian.top/Article/details/gtdfvdehzm.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gtnedsbkki.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.316326.xyz/Article/details/gtcxhdcosv.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jianghu66.top/Article/details/gtgfqqazxt.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.c1oappe.top/Article/details/gtfjikakps.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.shanyushiyangtech.top/Article/details/gtowecximu.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.gzhubu.top/Article/details/gtjmugzuxs.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.xuanzx.com/Article/details/gtpmopknga.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.ehwqpu.com/Article/details/gtvypcaxtb.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.shangyingyoupin.top/Article/details/gtaprjlymb.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.gaohongyu789.top/Article/details/gtsjwopfvx.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yanxiufei.cn/Article/details/gtbxqkifzz.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvuuonmz.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhongyouzk.top/Article/details/gtukrmdpdm.html

【文件统计】
来源：http://dali.guannengcc.top/Article/details/gteuiucsdd.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.gotoacloud.top/Article/details/gtraeruvte.html

--------------------------------------------------------------------------------
来源：http://dali.9152youxi.cn/Article/details/gtrkqknuxo.html

目  录
来源：http://dali.yj20258888.top/Article/details/gthzqmamln.html

--------------------------------------------------------------------------------
来源：http://dali.jinghuilouyu.cn/Article/details/gtqblsvjxd.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.xziqi.cn/Article/details/gtdpiqwsxw.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.xuanzx.com/Article/details/gtoneigged.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.dashuyun.cn/Article/details/gtiqcrgwkv.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.havefunace.top/Article/details/gtowkhshjq.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhengqikj.top/Article/details/gtuukdaqiy.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jiagoushi.top/Article/details/gttrdkddnn.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.nanxuanxn.top/Article/details/gtgjevwgjv.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.cheryme.top/Article/details/gtlhsqabpz.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtflmcxmtz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.sufxvd.cn/Article/details/gtdawztmna.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.vqdsnc.cn/Article/details/gtyqqlseod.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtjnujqohy.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrrhvyzfi.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhongyouzk.top/Article/details/gtivjunqdd.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.bjfxy.top/Article/details/gtzatfnsbe.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jqgfzy.top/Article/details/gttlhspvhy.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtezkcjavd.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.sxryk.cn/Article/details/gtoupxxujw.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.haohaochexian.top/Article/details/gtmcwfzslh.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ybcxt.top/Article/details/gtnmotmien.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfsqlludt.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtpqrrwwys.html

A. 基础语法与类型
来源：http://dali.xylfe.cn/Article/details/gtxvbvuwkv.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtkvigoyuf.html

[A01] Hello World
来源：http://dali.jianghu66.top/Article/details/gtvloxtlpx.html

Py:   print("Hello, World!")
来源：http://dali.yj202588.top/Article/details/gtptvxghiq.html

PHP:  echo "Hello, World!";
来源：http://dali.cdnleiting.top/Article/details/gtvldfpzew.html

JS:   console.log("Hello, World!");
来源：http://dali.jinqigufen.top/Article/details/gtwdbjycsd.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.gzhubu.top/Article/details/gttcenpyqw.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmhryqook.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.chenzaomai.com/Article/details/gtdwikfiho.html

Ruby: puts "Hello, World!"
来源：http://dali.zhoulong.xyz/Article/details/gtcdglluob.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hfpthk.cn/Article/details/gtkoazxgfm.html

[A02] 变量声明与赋值
来源：http://dali.yuxming.cn/Article/details/gtabavriui.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.shangyingyoupin.top/Article/details/gtgxchowiy.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.dianchejie.cn/Article/details/gtfizxhiwn.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gtqetfrfym.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.iojbl.cn/Article/details/gtnuqdocws.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.xuanzx.com/Article/details/gtarzabgvg.html

Go:   name := "Alex"; age := 20
来源：http://dali.mhx1999.top/Article/details/gtearlbexa.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhengqikj.top/Article/details/gtvyvcqdrz.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwwlwlgi.html

[A03] 常量定义
来源：http://dali.cqqwz.cn/Article/details/gtwyfpksod.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.iojbl.cn/Article/details/gtgagtetbo.html

PHP:  const PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gtnarfopdi.html

JS:   const PI = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwfebtbn.html

TS:   const PI: number = 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gtfwpncdbi.html

Java: static final double PI = 3.14159;
来源：http://dali.meibo888.top/Article/details/gtweezabkm.html

Go:   const PI = 3.14159
来源：http://dali.quarkkingdee.top/Article/details/gtlugvtuuk.html

Ruby: PI = 3.14159
来源：http://dali.jiagoushi.top/Article/details/gtjvmttixm.html

C#:   const double PI = 3.14159;
来源：http://dali.iojbl.cn/Article/details/gtqhvjzyfc.html

[A04] 判断变量类型
来源：http://dali.jianghu66.top/Article/details/gtqccoeoxs.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jiagoushi.top/Article/details/gtdboizflv.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.xylfe.cn/Article/details/gthyxtzlar.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yj20258.top/Article/details/gtzfdzlece.html

TS:   typeof x; x instanceof Date
来源：http://dali.ehwqpu.com/Article/details/gtjhzhhrgj.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.c1oappe.top/Article/details/gthaupuzgs.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yuanzhike.top/Article/details/gtdawlnzki.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.bjfxy.top/Article/details/gtrrunxecs.html

C#:   x.GetType().Name; x is int
来源：http://dali.kuanghao11.cn/Article/details/gtcffcilnn.html

[A05] 整数除法与取模
来源：http://dali.jiagoushi.top/Article/details/gtmecfmnmn.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jqgfzy.top/Article/details/gtbeoxoajr.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwejqomjm.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.snrcjt.cn/Article/details/gtqaysvjzh.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.tian-w.cn/Article/details/gtmcmhvouu.html

Java: 7 / 2; 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gtrmsyjwgx.html

Go:   7 / 2; 7 % 2
来源：http://dali.hammf.cn/Article/details/gtvdnkjuoj.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.tian-w.cn/Article/details/gtoojangky.html

C#:   7 / 2; 7 % 2
来源：http://dali.jinqigfzy.top/Article/details/gtyytnbuqu.html


<!-- 参考信息 -->