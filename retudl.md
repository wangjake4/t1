代发 wailian999

[U45] PHP：类型声明与返回类型
来源：http://dali.sufxvd.cn/Article/details/gtqzybxink.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gaohongyu789.top/Article/details/gtfgpihlow.html

[U46] PHP：可空类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoztwokye.html

?string $name = null
来源：http://dali.andypj.xyz/Article/details/gteynbvjzi.html

[U47] PHP：联合类型
来源：http://dali.hongshengwenyu.top/Article/details/gtsaozyfea.html

int|string $id
来源：http://dali.aizwys.cn/Article/details/gtcgquwrxl.html

[U48] PHP：纯枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkpbfkpts.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jinqigfzy.top/Article/details/gtwbxdpsgd.html

[U49] PHP：只读属性
来源：http://dali.zycfv.cn/Article/details/gtjxsltuhe.html

public readonly string $name
来源：http://dali.bjfxy.top/Article/details/gtxhodpzkr.html

[U50] PHP：构造器属性提升
来源：http://dali.yj202588.top/Article/details/gtfdsntwcr.html

public function __construct(private int $id) {}
来源：http://dali.dashuyun.cn/Article/details/gtruuvneez.html

[U51] PHP：数组解构
来源：http://dali.yvedp.cn/Article/details/gtqbczwisi.html

[$a, $b] = $arr;
来源：http://dali.c1oappe.top/Article/details/gtjszozljf.html

[U52] PHP：箭头函数
来源：http://dali.shzxlz.cn/Article/details/gtnqlcjerx.html

$double = fn($x) => $x * 2;
来源：http://dali.feifeiyinyue.top/Article/details/gtmpykgtvc.html

[U53] PHP：空合并运算符
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqahreubb.html

$v = $a ?? $b ?? "default";
来源：http://dali.tanke756.top/Article/details/gtpatszkdx.html

[U54] PHP：空安全调用
来源：http://dali.fzhhl.top/Article/details/gtrvvwxbno.html

$obj?->method()
来源：http://dali.xuanzx.com/Article/details/gttuxqyjge.html

[U55] PHP：match 表达式
来源：http://dali.gaohongyu789.top/Article/details/gtjiwvlicp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.daria6918.cn/Article/details/gtfmodvttd.html

[U56] PHP：命名参数
来源：http://dali.jianghu66.top/Article/details/gtqpllsmdu.html

f(a: 1, b: 2)
来源：http://dali.9152youxi.cn/Article/details/gtgkofdhme.html

[U57] PHP：字符串插值
来源：http://dali.zdqjudy.top/Article/details/gtirmzikgh.html

"值: {$a}"
来源：http://dali.dashuyun.cn/Article/details/gtdygoamup.html

[U58] PHP：数组三件套
来源：http://dali.yanxiufei.cn/Article/details/gtnrkhmuzy.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.quarkkingdee.top/Article/details/gttnmtbmat.html

[U59] PHP：自定义排序
来源：http://dali.jyoumei.cn/Article/details/gtdzuwujmf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xylfe.cn/Article/details/gtywkjmpmw.html

[U60] PHP：JSON 编解码
来源：http://dali.nanxuanxn.top/Article/details/gtwkrelaja.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.redwolf501.top/Article/details/gtjvuzjyxl.html

[U61] PHP：正则
来源：http://dali.zhaomingkeji.xyz/Article/details/gtllcaeswz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtqrmjjoud.html

[U62] PHP：日期对象
来源：http://dali.jiagoushi.top/Article/details/gtrkimcgek.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.gotoacloud.top/Article/details/gttmyztnyd.html

[U63] PHP：文件读写
来源：http://dali.yvedp.cn/Article/details/gtkldlqlcr.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.guowangkeji.top/Article/details/gtcrwdyeha.html

[U64] PHP：目录遍历
来源：http://dali.yuanzhike.top/Article/details/gtvesylbyn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.xylfe.cn/Article/details/gttebnffxy.html

[U65] PHP：会话
来源：http://dali.hnqzz.top/Article/details/gtovsejgng.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gtnhsrqxde.html

[U66] PHP：设置 Cookie
来源：http://dali.hongshengwenyu.top/Article/details/gtvdsypthm.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.ppjwa.cn/Article/details/gtuovsbpnc.html

[U67] PHP：处理文件上传
来源：http://dali.xuanzx.com/Article/details/gtgcygcwnv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.dashuyun.cn/Article/details/gtaczeywrx.html

[U68] PHP：PDO 连接
来源：http://dali.cqqwz.cn/Article/details/gtdbadeezp.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.fzhhl.top/Article/details/gtnaebtwci.html

[U69] PHP：PDO 预处理
来源：http://dali.zhiwuduotai.top/Article/details/gtnqyaoaac.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.bjfxy.top/Article/details/gtmsmfxase.html

[U70] PHP：PDO 事务
来源：http://dali.xziqi.cn/Article/details/gtdogwcktl.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.iojbl.cn/Article/details/gttfwqvsbn.html

[U71] PHP：抛出异常
来源：http://dali.tianlin.xyz/Article/details/gtbkreplkz.html

throw new RuntimeException("失败", 500);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfnhwhxh.html

[U72] PHP：写错误日志
来源：http://dali.pengpengdd.cyou/Article/details/gtojdngybs.html

error_log("失败: " . $e->getMessage());
来源：http://dali.smart0.xyz/Article/details/gttqvmvopm.html

[U73] PHP：读取 ini 配置
来源：http://dali.pycfn.com/Article/details/gtgykkaprm.html

parse_ini_file("config.ini", true)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttawdfawb.html

[U74] PHP：读取环境变量
来源：http://dali.hammf.cn/Article/details/gtqyhfxxth.html

getenv("APP_ENV") ?: "production"
来源：http://dali.snrcjt.cn/Article/details/gtasdlketb.html

[U75] PHP：依赖注入
来源：http://dali.feifeiyinyue.top/Article/details/gtvoemgtbt.html

composer require psr/container
来源：http://dali.jlsjyb.cn/Article/details/gtdpesobuu.html

[U76] PHP：简单路由
来源：http://dali.cucudq.cn/Article/details/gtbuxmfpzn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.cqqwz.cn/Article/details/gtudrlejyf.html

[U77] PHP：模板渲染
来源：http://dali.fzhhl.top/Article/details/gtxrnleiyy.html

composer require twig/twig
来源：http://dali.haohaochexian.top/Article/details/gtnflpemcu.html

[U78] PHP：单元测试
来源：http://dali.tian-w.cn/Article/details/gtxlkxdakw.html

composer require --dev phpunit/phpunit
来源：http://dali.shuidangran.top/Article/details/gtywbdrhev.html

[U79] PHP：静态分析
来源：http://dali.zhixingplan.top/Article/details/gtobbvzrud.html

composer require --dev phpstan/phpstan
来源：http://dali.chenzaomai.com/Article/details/gtlxbkiggd.html

[U80] PHP：代码规范修复
来源：http://dali.jinghuilouyu.cn/Article/details/gtcfnteydi.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jqgfzy.top/Article/details/gtwkpqgwvx.html

[U81] JS：初始化项目
来源：http://dali.jqgufenzy.top/Article/details/gtfohuydtp.html

npm init -y;  npm i express
来源：http://dali.dianchejie.cn/Article/details/gtpcfmfwkm.html

[U82] JS：package.json 脚本
来源：http://dali.jiagoushi.top/Article/details/gtwnwnxqrf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.tian-w.cn/Article/details/gtwcboxdqd.html

[U83] JS：ES Module 导入导出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaeqtaway.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hammf.cn/Article/details/gtmyjjrfqx.html

[U84] JS：CommonJS 写法
来源：http://dali.shanyushiyangtech.top/Article/details/gtzgnmexrv.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfxjoevb.html

[U85] JS：可选链
来源：http://dali.fengsongda.top/Article/details/gtkjaxptdo.html

a?.b?.c
来源：http://dali.tanke756.top/Article/details/gtjvuqngom.html

[U86] JS：空值合并
来源：http://dali.xuanzx.com/Article/details/gtwhyjbmgl.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gtywembkcm.html

[U87] JS：解构默认值
来源：http://dali.vqdsnc.cn/Article/details/gtgmmaqgui.html

const { a = 1, b = 2 } = obj;
来源：http://dali.cqqwz.cn/Article/details/gtvtbxqpnv.html

[U88] JS：对象展开合并
来源：http://dali.ivvv.top/Article/details/gtethejgiv.html

{ ...a, ...b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuaaplzbm.html

[U89] JS：数组去重
来源：http://dali.havefunace.top/Article/details/gtqeyrihkl.html

[...new Set(arr)]
来源：http://dali.daria6918.cn/Article/details/gtsqwxkqor.html

[U90] JS：数字数组排序
来源：http://dali.zhongyouzk.top/Article/details/gtaxaqnhca.html

[...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gtssryndcz.html

[U91] JS：对象键值遍历
来源：http://dali.yangfankeji.com/Article/details/gtgikkkrkw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.chenjidiqi.icu/Article/details/gtzabkleni.html

[U92] JS：深拷贝
来源：http://dali.yueranfly.top/Article/details/gtollqvruy.html

structuredClone(obj)
来源：http://dali.cdnleiting.top/Article/details/gtowwubccq.html

[U93] JS：模板字符串
来源：http://dali.haohaochexian.top/Article/details/gtrvpmuqil.html

`共 ${n} 条`
来源：http://dali.shanyushiyangkeji.top/Article/details/gtscgycopa.html

[U94] JS：箭头函数
来源：http://dali.smart0.xyz/Article/details/gtneutewfw.html

const double = x => x * 2;
来源：http://dali.yueranfly.top/Article/details/gtaepfkcbc.html

[U95] JS：Promise 包装
来源：http://dali.ehwqpu.com/Article/details/gtgsrlkxyn.html

new Promise((resolve, reject) => {})
来源：http://dali.yj20258888.top/Article/details/gtiqbkzhrx.html

[U96] JS：async/await 与异常
来源：http://dali.redwolf501.top/Article/details/gtgrkrqrly.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gtndonknkn.html

[U97] JS：并发请求
来源：http://dali.andypj.xyz/Article/details/gtjttzauwt.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yvedp.cn/Article/details/gtvbrxwabt.html

[U98] JS：fetch 带 JSON
来源：http://dali.xinyue.icu/Article/details/gtkmafsmyg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.gotoacloud.top/Article/details/gtxpdjwqif.html

[U99] JS：事件监听
来源：http://dali.shangyingyoupin.top/Article/details/gtmggnrura.html

el.addEventListener("click", e => {})
来源：http://dali.ppjwa.cn/Article/details/gtzvczsren.html

[U100] JS：DOM 查询
来源：http://dali.meibo888.top/Article/details/gtugktkett.html

document.querySelector(".item")
来源：http://dali.0kj1m.cn/Article/details/gtoonknmsc.html

[U101] JS：classList 操作
来源：http://dali.yj202588.top/Article/details/gtstzenaxq.html

el.classList.toggle("active")
来源：http://dali.xinyue.icu/Article/details/gtoguyuecs.html

[U102] JS：本地存储
来源：http://dali.xuanzx.com/Article/details/gtidjspeak.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.mhx1999.top/Article/details/gtygrqqbmj.html

[U103] JS：定时器
来源：http://dali.jqgfzy.top/Article/details/gthpzpgnet.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.mhx1999.top/Article/details/gtskasmkgp.html

[U104] JS：防抖
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtojmhfghw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.vqdsnc.cn/Article/details/gtiihfszzf.html

[U105] JS：节流
来源：http://dali.feifeiyinyue.top/Article/details/gtynayczgr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.guowangkeji.top/Article/details/gtnqmmpbrn.html

[U106] JS：日期格式化
来源：http://dali.guowangkeji.top/Article/details/gtpegprpbx.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.c1oappe.top/Article/details/gtcadpczcl.html

[U107] JS：数字千分位
来源：http://dali.snrcjt.cn/Article/details/gtviwhnzab.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.andypj.xyz/Article/details/gttigaxxof.html

[U108] JS：随机整数
来源：http://dali.jianghu66.top/Article/details/gtentwmdpz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.sufxvd.cn/Article/details/gtgmohmvxm.html

[U109] JS：数组分组
来源：http://dali.ydzc1.top/Article/details/gtxvtsbsrg.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigfzy.top/Article/details/gtrgqgjilv.html

[U110] JS：数组分块
来源：http://dali.meibo888.top/Article/details/gtcvexbqva.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.svipenyu.cn/Article/details/gttjblmynx.html

[U111] JS：对象转 Map
来源：http://dali.zhixingplan.top/Article/details/gtatvodmdn.html

new Map(Object.entries(obj))
来源：http://dali.ybcxt.top/Article/details/gtebbvinyv.html

[U112] JS：字符串补位
来源：http://dali.chenzaomai.com/Article/details/gtvnrbbgzh.html

"7".padStart(3, "0")
来源：http://dali.guannengcc.top/Article/details/gtsdwxlomm.html

[U113] JS：正则替换全部
来源：http://dali.chenzaomai.com/Article/details/gtpryadiyd.html

s.replaceAll("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtjbusexna.html

[U114] JS：JSON 深比较
来源：http://dali.jqgufenzy.top/Article/details/gtojoxtkuf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ybcxt.top/Article/details/gtglqueofq.html

[U115] JS：生成 UUID
来源：http://dali.xziqi.cn/Article/details/gtvkuwbzxr.html

crypto.randomUUID()
来源：http://dali.hammf.cn/Article/details/gtviqaksmy.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.chenzaomai.com/Article/details/gtnefcscgy.html

/** @param {string} name */ function f(name) {}
来源：http://dali.redwolf501.top/Article/details/gtzdfohphh.html

[U117] JS：单元测试
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdjrftrom.html

npm i -D vitest;  npx vitest
来源：http://dali.yanxiufei.cn/Article/details/gtwzqbtbeo.html

[U118] JS：开发服务器
来源：http://dali.yueranfly.top/Article/details/gtrbrdsseb.html

npm i -D vite;  npx vite
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjuboclmq.html

[U119] JS：生产构建
来源：http://dali.shanyushiyangtech.top/Article/details/gtpydbuuyi.html

npx vite build
来源：http://dali.cdnleiting.top/Article/details/gtdtzfiutv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnmxlyxoo.html

import.meta.env.VITE_API_URL
来源：http://dali.zhoulong.xyz/Article/details/gtyqmrbppj.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtpjidaowh.html

统计汇总
来源：http://dali.andypj.xyz/Article/details/gtygnofman.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtgvioidhw.html

按语言统计（条）：
来源：http://dali.nanxinkj.top/Article/details/gtcvdwavwd.html

Python ......... 252
来源：http://dali.hywenlv.cn/Article/details/gtjyrprnzt.html

PHP ............ 252
来源：http://dali.9152youxi.cn/Article/details/gtbypedcut.html

JavaScript ..... 252
来源：http://dali.tian-w.cn/Article/details/gtqyhjohhi.html

TypeScript ..... 212
来源：http://dali.smart0.xyz/Article/details/gtxfshpznj.html

Java ........... 212
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcjuedakx.html

Go ............. 212
来源：http://dali.c1oappe.top/Article/details/gtjrhmiwiz.html

Ruby ........... 212
来源：http://dali.cqqwz.cn/Article/details/gtguwomipt.html

C# ............. 212
来源：http://dali.snrcjt.cn/Article/details/gtlknoikyz.html

C .............. 30
来源：http://dali.meibo888.top/Article/details/gtfajxaghx.html

C++ ............ 30
来源：http://dali.9152youxi.cn/Article/details/gtqqjubqqy.html

SQL ............ 90
来源：http://dali.smart0.xyz/Article/details/gtbhjdmiib.html

Bash ........... 80
来源：http://dali.zhongyouzk.top/Article/details/gtpudnfonb.html

Kotlin ......... 15
来源：http://dali.daria6918.cn/Article/details/gtntgravks.html

Swift .......... 15
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvghvboro.html

Lua ............ 10
来源：http://dali.cqqwz.cn/Article/details/gtxojwktpj.html

Perl ........... 10
来源：http://dali.yangfankeji.com/Article/details/gtreacughy.html

Scala .......... 10
来源：http://dali.fzhhl.top/Article/details/gtfddmqbxq.html

------------------------------------
来源：http://dali.sysykeji.top/Article/details/gtalbfyggc.html

合计 ........... 2106 条
来源：http://dali.birdmap.top/Article/details/gtxdugfisp.html

按章节统计：
来源：http://dali.dianchejie.cn/Article/details/gtiosqpefm.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.feifeiyinyue.top/Article/details/gtixyqymyj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.pengpengdd.cyou/Article/details/gthgqagebn.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.9152youxi.cn/Article/details/gtathsibcz.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cheryme.top/Article/details/gtpqvxaymb.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jlsjyb.cn/Article/details/gtnlkkpcdj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.xylfe.cn/Article/details/gtziklavce.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.chenlongwang.top/Article/details/gtwplkmcat.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.daxiang520.top/Article/details/gtjdxoswto.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.xylfe.cn/Article/details/gterpcrelu.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.sysykeji.top/Article/details/gtclewfwpd.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmaegipp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.shuidangran.top/Article/details/gtpymcsipr.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.bjfxy.top/Article/details/gtzkuyvjvx.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.chenzaomai.com/Article/details/gtxwwthffs.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.dashuyun.cn/Article/details/gtbridxgzt.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ywan-chungtsiang.top/Article/details/gthbadazax.html

Q SQL 专题                              90
来源：http://dali.iojbl.cn/Article/details/gttvfivole.html

R Bash 专题                             80
来源：http://dali.andypj.xyz/Article/details/gtkqggtfkk.html

S C / C++ 专题                          60
来源：http://dali.shangyingyoupin.top/Article/details/gtpxbwldwz.html

T 其他语言补充                          60
来源：http://dali.sysykeji.top/Article/details/gtgwwxoukj.html

U 高频实用片段                         120
来源：http://dali.snrcjt.cn/Article/details/gtsxhetxct.html

------------------------------------
来源：http://dali.havefunace.top/Article/details/gtgkorhsic.html

合计                                  2106 条
来源：http://dali.yonumen.top/Article/details/gtowrkwuwc.html

--------------------------------------------------------------------------------
来源：http://dali.ppjwa.cn/Article/details/gtbicimuao.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gtfsvbpdqg.html

--------------------------------------------------------------------------------
来源：http://dali.havefunace.top/Article/details/gtedzisuns.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yvedp.cn/Article/details/gtfbyvmmxk.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.xuetiantiany.cn/Article/details/gtpzaeizoy.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jiagoushi.top/Article/details/gtbjwnhhmu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yvedp.cn/Article/details/gtjspaswyr.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.quarkkingdee.top/Article/details/gtwgvnsvib.html

—— 文件结束 ——
来源：http://dali.jqgufenzy.top/Article/details/gtgmambedd.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtzanfgivf.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.hongshengwenyu.top/Article/details/gtvwknsnei.html

Common Programming Examples Cheat Book
来源：http://dali.yj20258.top/Article/details/gtndsvrzkx.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtxbfdhgop.html

【收录内容】
来源：http://dali.yongpay.top/Article/details/gtroujonyv.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hywenlv.cn/Article/details/gtoysbojsv.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.vqdsnc.cn/Article/details/gtyinfzjuz.html

SQL · Bash · C · C++
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpmxzyssn.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yueranfly.top/Article/details/gtxovjywqu.html

【使用说明】
来源：http://dali.jqgfzy.top/Article/details/gtqbyuuvei.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.hnxiangtu.top/Article/details/gtzsrcnwlq.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.c1oappe.top/Article/details/gtgpibcupc.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yangfankeji.com/Article/details/gtjmhufxmd.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.shuidangran.top/Article/details/gtzbudmmpy.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjekvltol.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.fengsongda.top/Article/details/gtztxwfuux.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.smart0.xyz/Article/details/gtbdctpthm.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.xuetiantiany.cn/Article/details/gtbphkkzhw.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jiagoushi.top/Article/details/gtkqottocj.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.gogol.net.cn/Article/details/gtcqucagyk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.meibo888.top/Article/details/gtntgyxzpg.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yj202588.top/Article/details/gtzzbdgwew.html

【文件统计】
来源：http://dali.hammf.cn/Article/details/gtwpzioicq.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.0kj1m.cn/Article/details/gtkrqklmgq.html

--------------------------------------------------------------------------------
来源：http://dali.tian-w.cn/Article/details/gthxgezpqk.html

目  录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpniyjenz.html

--------------------------------------------------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gtgrbwyotq.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.sufxvd.cn/Article/details/gttncosbxt.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.tanke756.top/Article/details/gtmxmmleox.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtegyzbaum.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.wangdashe.top/Article/details/gtezupobhg.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.nanxinkj.top/Article/details/gtfndumlhs.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.nwbrower.top/Article/details/gtgnxuxtpq.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.daxiang520.top/Article/details/gtzmwkgaiq.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.xziqi.cn/Article/details/gtmctsujdm.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.svipenyu.cn/Article/details/gtmjhtpqye.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.vqdsnc.cn/Article/details/gtvzvuazol.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yj20258888.top/Article/details/gtfnxvlxql.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtrgnyrrmu.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.0kj1m.cn/Article/details/gtngtmowsr.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.haohaochexian.top/Article/details/gteyzrkwbf.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.9152youxi.cn/Article/details/gtybebrzmi.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.xuanzx.com/Article/details/gtskxfsyxb.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.tianlin.xyz/Article/details/gtbaudfpqj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jianghu66.top/Article/details/gtigkqqmle.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.nwbrower.top/Article/details/gtkfgvkyzw.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.mhx1999.top/Article/details/gtgamuesrd.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.0kj1m.cn/Article/details/gtjflsxqdh.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtzkneukgc.html

A. 基础语法与类型
来源：http://dali.sysykeji.top/Article/details/gtoluddwxh.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtvthzdfcc.html

[A01] Hello World
来源：http://dali.jqgfzy.top/Article/details/gtlbasqolx.html

Py:   print("Hello, World!")
来源：http://dali.gaohongyu789.top/Article/details/gtcrcgxyvc.html

PHP:  echo "Hello, World!";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtypcxabyh.html

JS:   console.log("Hello, World!");
来源：http://dali.wangshuangyany.cn/Article/details/gttwmizhnv.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.hnqzz.top/Article/details/gtglqxazgq.html

Java: System.out.println("Hello, World!");
来源：http://dali.andypj.xyz/Article/details/gtzkteuxzn.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.sysykeji.top/Article/details/gtqymdfpjv.html

Ruby: puts "Hello, World!"
来源：http://dali.cqqwz.cn/Article/details/gtthpuubmv.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.aizwys.cn/Article/details/gtetanjhfo.html

[A02] 变量声明与赋值
来源：http://dali.daxiang520.top/Article/details/gtwjvkwoda.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.nanxuanxn.top/Article/details/gtpitihrng.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.cdnleiting.top/Article/details/gtspihfnyp.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.tianlin.xyz/Article/details/gtfqmigbeh.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.wangshuangyany.cn/Article/details/gtgyluynuy.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.ydzc1.top/Article/details/gtnwmcfddq.html

Go:   name := "Alex"; age := 20
来源：http://dali.fzhhl.top/Article/details/gtetjyyyjs.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhoulong.xyz/Article/details/gtswzdgjwe.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.dianchejie.cn/Article/details/gtenbrctui.html

[A03] 常量定义
来源：http://dali.chenjidiqi.icu/Article/details/gtonlfirks.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gtoilltnse.html

PHP:  const PI = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gtkhrcogbx.html

JS:   const PI = 3.14159;
来源：http://dali.guannengcc.top/Article/details/gtsdvmgoax.html

TS:   const PI: number = 3.14159;
来源：http://dali.yongpay.top/Article/details/gteofjrdvw.html

Java: static final double PI = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gterzaqytp.html

Go:   const PI = 3.14159
来源：http://dali.316326.xyz/Article/details/gtleennmve.html

Ruby: PI = 3.14159
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkliziqgq.html

C#:   const double PI = 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gtidzuekde.html

[A04] 判断变量类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtflzwnbas.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.cqqwz.cn/Article/details/gtoudcqoaq.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.xuetiantiany.cn/Article/details/gtqsrlxhgv.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yuanzhike.top/Article/details/gtsmhgdkua.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhiwuduotai.top/Article/details/gtlzabthdr.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.smart0.xyz/Article/details/gtgpevrmeq.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.sweek.top/Article/details/gtjfrhlwav.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gtleutlexi.html

C#:   x.GetType().Name; x is int
来源：http://dali.shzxlz.cn/Article/details/gtmujrpdwk.html

[A05] 整数除法与取模
来源：http://dali.redwolf501.top/Article/details/gteriwnlnw.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jinqigfzy.top/Article/details/gtwkyhyfrj.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.guowangkeji.top/Article/details/gtqoootlto.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.pycfn.com/Article/details/gtysmxzfxv.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbgvsyrqb.html


<!-- 参考信息 -->