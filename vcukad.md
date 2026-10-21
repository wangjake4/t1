代发 wailian999

[U37] Py：读写 Excel
来源：http://dali.jlsjyb.cn/Article/details/gtbfvcvzok.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.cucudq.cn/Article/details/gtnwfwyeht.html

[U38] Py：获取脚本所在目录
来源：http://dali.yanxiufei.cn/Article/details/gtnlunlpej.html

Path(__file__).resolve().parent
来源：http://dali.hnxiangtu.top/Article/details/gtkbkveqhr.html

[U39] Py：判断是否在交互环境
来源：http://dali.sufxvd.cn/Article/details/gtbejijogf.html

sys.stdout.isatty()
来源：http://dali.nwbrower.top/Article/details/gtgrppfhoh.html

[U40] Py：打印到标准错误
来源：http://dali.dianchejie.cn/Article/details/gtxxrdkcxf.html

print("err", file=sys.stderr)
来源：http://dali.xylfe.cn/Article/details/gtjpaufapo.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yangfankeji.com/Article/details/gtiutmacee.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.gzhubu.top/Article/details/gtfhsyyhky.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xinyue.icu/Article/details/gtcjvljvky.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hongshengwenyu.top/Article/details/gtpqihklyz.html

[U43] PHP：声明命名空间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtemzqlobk.html

namespace App\Http;
来源：http://dali.xinyue.icu/Article/details/gtfifujsdu.html

[U44] PHP：开启严格类型
来源：http://dali.0kj1m.cn/Article/details/gtywaipepu.html

declare(strict_types=1);
来源：http://dali.sufxvd.cn/Article/details/gtslkwbeya.html

[U45] PHP：类型声明与返回类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtgdzggqlk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cheryme.top/Article/details/gtvnzaddah.html

[U46] PHP：可空类型
来源：http://dali.iojbl.cn/Article/details/gtqnaejbkv.html

?string $name = null
来源：http://dali.dianchejie.cn/Article/details/gtbifrsoqn.html

[U47] PHP：联合类型
来源：http://dali.wangdashe.top/Article/details/gtsynbnulq.html

int|string $id
来源：http://dali.bjfxy.top/Article/details/gtbdojgmtc.html

[U48] PHP：纯枚举
来源：http://dali.feifeiyinyue.top/Article/details/gtzpvmieem.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yangfankeji.com/Article/details/gtzeaywhhz.html

[U49] PHP：只读属性
来源：http://dali.sufxvd.cn/Article/details/gtttlsngdi.html

public readonly string $name
来源：http://dali.nanxuanxn.top/Article/details/gtlgnqaseg.html

[U50] PHP：构造器属性提升
来源：http://dali.yonumen.top/Article/details/gthxrxvnzd.html

public function __construct(private int $id) {}
来源：http://dali.chenzaomai.com/Article/details/gtiqryymse.html

[U51] PHP：数组解构
来源：http://dali.daria6918.cn/Article/details/gtleggnrfv.html

[$a, $b] = $arr;
来源：http://dali.redwolf501.top/Article/details/gtvcnerubh.html

[U52] PHP：箭头函数
来源：http://dali.tian-w.cn/Article/details/gtjdwmrjwt.html

$double = fn($x) => $x * 2;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnqdbuyot.html

[U53] PHP：空合并运算符
来源：http://dali.yanxiufei.cn/Article/details/gtcauqmpkc.html

$v = $a ?? $b ?? "default";
来源：http://dali.snrcjt.cn/Article/details/gttsgvmktw.html

[U54] PHP：空安全调用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnqcvdidj.html

$obj?->method()
来源：http://dali.zhiwuduotai.top/Article/details/gtycmpgdmk.html

[U55] PHP：match 表达式
来源：http://dali.zhongyouzk.top/Article/details/gtoshqrije.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.nanxinkj.top/Article/details/gtuenumhbs.html

[U56] PHP：命名参数
来源：http://dali.ivvv.top/Article/details/gtexyfsmxb.html

f(a: 1, b: 2)
来源：http://dali.yongpay.top/Article/details/gtysbexonr.html

[U57] PHP：字符串插值
来源：http://dali.cheryme.top/Article/details/gtuudjhosl.html

"值: {$a}"
来源：http://dali.hfpthk.cn/Article/details/gtqgapehro.html

[U58] PHP：数组三件套
来源：http://dali.quarkkingdee.top/Article/details/gtfqyrbosr.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.sxryk.cn/Article/details/gtzukbabvk.html

[U59] PHP：自定义排序
来源：http://dali.chenlongwang.top/Article/details/gtprwpwgnj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gaohongyu789.top/Article/details/gtgetehfqc.html

[U60] PHP：JSON 编解码
来源：http://dali.haohaochexian.top/Article/details/gtcipfiuex.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhiwuduotai.top/Article/details/gtcevveqlk.html

[U61] PHP：正则
来源：http://dali.guannengcc.top/Article/details/gtaemnzmgz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtctdokebf.html

[U62] PHP：日期对象
来源：http://dali.xuetiantiany.cn/Article/details/gtewcynriw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.bjfxy.top/Article/details/gtpavwopbg.html

[U63] PHP：文件读写
来源：http://dali.tanke756.top/Article/details/gtsimtsgve.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.sysykeji.top/Article/details/gtuskvnujz.html

[U64] PHP：目录遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtubxforuo.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.dashuyun.cn/Article/details/gtfnrinyem.html

[U65] PHP：会话
来源：http://dali.yvedp.cn/Article/details/gtvdunkrxi.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gtdghfmdst.html

[U66] PHP：设置 Cookie
来源：http://dali.sufxvd.cn/Article/details/gtrxcmpssz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.0kj1m.cn/Article/details/gthaxunrsq.html

[U67] PHP：处理文件上传
来源：http://dali.hongshengwenyu.top/Article/details/gtiiuqhppk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hnxiangtu.top/Article/details/gtkhuncrle.html

[U68] PHP：PDO 连接
来源：http://dali.zhoulong.xyz/Article/details/gtovtqkwzr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.shanyushiyangtech.top/Article/details/gtwrmynpfc.html

[U69] PHP：PDO 预处理
来源：http://dali.nwbrower.top/Article/details/gtilathnfc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.cqqwz.cn/Article/details/gtrhwudxfo.html

[U70] PHP：PDO 事务
来源：http://dali.shuidangran.top/Article/details/gtnikxrmug.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yuanzhike.top/Article/details/gtglgcljfw.html

[U71] PHP：抛出异常
来源：http://dali.shangyingyoupin.top/Article/details/gtvxvrhnyz.html

throw new RuntimeException("失败", 500);
来源：http://dali.chenzaomai.com/Article/details/gtraqadzfa.html

[U72] PHP：写错误日志
来源：http://dali.0kj1m.cn/Article/details/gtiuodhtro.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jqgfzy.top/Article/details/gtjkeghhsy.html

[U73] PHP：读取 ini 配置
来源：http://dali.gzhubu.top/Article/details/gtjnjzlyoc.html

parse_ini_file("config.ini", true)
来源：http://dali.yj20258888.top/Article/details/gthubvusny.html

[U74] PHP：读取环境变量
来源：http://dali.bjfxy.top/Article/details/gtbtihukol.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yonumen.top/Article/details/gtcsgmlilo.html

[U75] PHP：依赖注入
来源：http://dali.hammf.cn/Article/details/gtlxdhcuog.html

composer require psr/container
来源：http://dali.sxryk.cn/Article/details/gtjxnrgffz.html

[U76] PHP：简单路由
来源：http://dali.iojbl.cn/Article/details/gtjzselwlo.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.aibaodan.cn/Article/details/gtleuenzlv.html

[U77] PHP：模板渲染
来源：http://dali.jianghu66.top/Article/details/gtvwgfaplv.html

composer require twig/twig
来源：http://dali.zycfv.cn/Article/details/gtfptdlgmf.html

[U78] PHP：单元测试
来源：http://dali.bjfxy.top/Article/details/gtepqdobuo.html

composer require --dev phpunit/phpunit
来源：http://dali.xziqi.cn/Article/details/gtyfpyhupn.html

[U79] PHP：静态分析
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlzxwiyrx.html

composer require --dev phpstan/phpstan
来源：http://dali.ydzc1.top/Article/details/gtnexpvzgq.html

[U80] PHP：代码规范修复
来源：http://dali.jiagoushi.top/Article/details/gttecrhktw.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.smart0.xyz/Article/details/gtykaknuuf.html

[U81] JS：初始化项目
来源：http://dali.hywenlv.cn/Article/details/gtuoipihho.html

npm init -y;  npm i express
来源：http://dali.svipenyu.cn/Article/details/gtstjaghny.html

[U82] JS：package.json 脚本
来源：http://dali.havefunace.top/Article/details/gthobpswlf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yj20258888.top/Article/details/gtwfcvbihg.html

[U83] JS：ES Module 导入导出
来源：http://dali.mhx1999.top/Article/details/gtxdpyuhig.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhixingplan.top/Article/details/gtthxzxjqv.html

[U84] JS：CommonJS 写法
来源：http://dali.shuidangran.top/Article/details/gtkcffypol.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.ehwqpu.com/Article/details/gtckwwvqjd.html

[U85] JS：可选链
来源：http://dali.dashuyun.cn/Article/details/gteywlsnew.html

a?.b?.c
来源：http://dali.nanxuanxn.top/Article/details/gtwurivedf.html

[U86] JS：空值合并
来源：http://dali.vqdsnc.cn/Article/details/gtoxlbspfg.html

a ?? b
来源：http://dali.wangdashe.top/Article/details/gtrqtznphp.html

[U87] JS：解构默认值
来源：http://dali.wangshuangyany.cn/Article/details/gtgfqooigg.html

const { a = 1, b = 2 } = obj;
来源：http://dali.fzhhl.top/Article/details/gtmasiycwy.html

[U88] JS：对象展开合并
来源：http://dali.gogol.net.cn/Article/details/gtfbjgdpsd.html

{ ...a, ...b }
来源：http://dali.gotoacloud.top/Article/details/gtbisqqtyd.html

[U89] JS：数组去重
来源：http://dali.hysaishi.cn/Article/details/gtgwrowuxv.html

[...new Set(arr)]
来源：http://dali.jinghuilouyu.cn/Article/details/gtlhgnalnd.html

[U90] JS：数字数组排序
来源：http://dali.jyoumei.cn/Article/details/gtlecyvxou.html

[...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gtoahchkeq.html

[U91] JS：对象键值遍历
来源：http://dali.xuanzx.com/Article/details/gtjwxydmkc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.nanxuanxn.top/Article/details/gtxupqmnrv.html

[U92] JS：深拷贝
来源：http://dali.316326.xyz/Article/details/gtxhhrivam.html

structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gtimohjbnu.html

[U93] JS：模板字符串
来源：http://dali.yueranfly.top/Article/details/gtinmlosvn.html

`共 ${n} 条`
来源：http://dali.yuanzhike.top/Article/details/gtayvzcogl.html

[U94] JS：箭头函数
来源：http://dali.0kj1m.cn/Article/details/gtltknwajt.html

const double = x => x * 2;
来源：http://dali.cucudq.cn/Article/details/gtyvidwxoz.html

[U95] JS：Promise 包装
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjayhwcym.html

new Promise((resolve, reject) => {})
来源：http://dali.ehwqpu.com/Article/details/gtognxzyka.html

[U96] JS：async/await 与异常
来源：http://dali.yj202588.top/Article/details/gtlmvvzggq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.nwbrower.top/Article/details/gtbfgduhok.html

[U97] JS：并发请求
来源：http://dali.zhixingplan.top/Article/details/gtlfvpmgjp.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.andypj.xyz/Article/details/gtmgstgmte.html

[U98] JS：fetch 带 JSON
来源：http://dali.xuanzx.com/Article/details/gttsttxayz.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yvedp.cn/Article/details/gtukcipplv.html

[U99] JS：事件监听
来源：http://dali.ivvv.top/Article/details/gtffkmulio.html

el.addEventListener("click", e => {})
来源：http://dali.yonumen.top/Article/details/gtamjryzhe.html

[U100] JS：DOM 查询
来源：http://dali.cheryme.top/Article/details/gthtrdnvob.html

document.querySelector(".item")
来源：http://dali.xylfe.cn/Article/details/gtherqalmy.html

[U101] JS：classList 操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gtorflnwwl.html

el.classList.toggle("active")
来源：http://dali.andypj.xyz/Article/details/gtcuspyncn.html

[U102] JS：本地存储
来源：http://dali.yj20258.top/Article/details/gtauallmig.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yuxming.cn/Article/details/gtylukdiql.html

[U103] JS：定时器
来源：http://dali.hongshengwenyu.top/Article/details/gtxhfscbhf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.fengsongda.top/Article/details/gtmhllqcri.html

[U104] JS：防抖
来源：http://dali.cheryme.top/Article/details/gtjmpurzrc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.meibo888.top/Article/details/gtjymrfsav.html

[U105] JS：节流
来源：http://dali.dashuyun.cn/Article/details/gtbpwotqqs.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yuxming.cn/Article/details/gttrdrncgi.html

[U106] JS：日期格式化
来源：http://dali.yuanzhike.top/Article/details/gtugsanzyx.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.gotoacloud.top/Article/details/gtiptfwwlk.html

[U107] JS：数字千分位
来源：http://dali.smart0.xyz/Article/details/gthldgywwj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.dianchejie.cn/Article/details/gtrkdktpzm.html

[U108] JS：随机整数
来源：http://dali.jyoumei.cn/Article/details/gtpsenxzbi.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.316326.xyz/Article/details/gtbvqojbvu.html

[U109] JS：数组分组
来源：http://dali.andypj.xyz/Article/details/gtqynigjpk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yonumen.top/Article/details/gtflsaonon.html

[U110] JS：数组分块
来源：http://dali.cheryme.top/Article/details/gtetlwtkzg.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.tian-w.cn/Article/details/gtubdkrkir.html

[U111] JS：对象转 Map
来源：http://dali.daria6918.cn/Article/details/gtppupexpt.html

new Map(Object.entries(obj))
来源：http://dali.redwolf501.top/Article/details/gtzkvbhwag.html

[U112] JS：字符串补位
来源：http://dali.guannengcc.top/Article/details/gtapbnsgir.html

"7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gtkeedvswc.html

[U113] JS：正则替换全部
来源：http://dali.zdqjudy.top/Article/details/gtwjcrbvze.html

s.replaceAll("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtnxzmezkv.html

[U114] JS：JSON 深比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdmvtiurs.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.aibaodan.cn/Article/details/gtzguazwjz.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gtubvjrukv.html

crypto.randomUUID()
来源：http://dali.ehwqpu.com/Article/details/gtqiavhnge.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gttbvypucj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jiagoushi.top/Article/details/gtqxefwdnk.html

[U117] JS：单元测试
来源：http://dali.pycfn.com/Article/details/gtyiddwvzu.html

npm i -D vitest;  npx vitest
来源：http://dali.jinqigufen.top/Article/details/gtzorfojxs.html

[U118] JS：开发服务器
来源：http://dali.aizwys.cn/Article/details/gtiuwbuawn.html

npm i -D vite;  npx vite
来源：http://dali.sufxvd.cn/Article/details/gtzjvyrvyj.html

[U119] JS：生产构建
来源：http://dali.yueranfly.top/Article/details/gtxkspbxiw.html

npx vite build
来源：http://dali.daxiang520.top/Article/details/gtophlrfxw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.guannengcc.top/Article/details/gtoxkbnacj.html

import.meta.env.VITE_API_URL
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthymjblwr.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtwuzgxghx.html

统计汇总
来源：http://dali.havefunace.top/Article/details/gtxznkahrr.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtuwzeyfpv.html

按语言统计（条）：
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbowzxypw.html

Python ......... 252
来源：http://dali.havefunace.top/Article/details/gtqqprpvqc.html

PHP ............ 252
来源：http://dali.jyoumei.cn/Article/details/gthnoamajq.html

JavaScript ..... 252
来源：http://dali.dashuyun.cn/Article/details/gtqaryvcqv.html

TypeScript ..... 212
来源：http://dali.sysykeji.top/Article/details/gtcwfdzjhr.html

Java ........... 212
来源：http://dali.chenjidiqi.icu/Article/details/gtwuzdipih.html

Go ............. 212
来源：http://dali.hongshengwenyu.top/Article/details/gtscdflucv.html

Ruby ........... 212
来源：http://dali.yueranfly.top/Article/details/gtigkywght.html

C# ............. 212
来源：http://dali.jlsjyb.cn/Article/details/gttsrvuegy.html

C .............. 30
来源：http://dali.chenlongwang.top/Article/details/gtmmiwvcww.html

C++ ............ 30
来源：http://dali.jiagoushi.top/Article/details/gttwzfmjho.html

SQL ............ 90
来源：http://dali.cqqwz.cn/Article/details/gthhuupvko.html

Bash ........... 80
来源：http://dali.gogol.net.cn/Article/details/gtmmivzdqq.html

Kotlin ......... 15
来源：http://dali.birdmap.top/Article/details/gtkfeqvrdi.html

Swift .......... 15
来源：http://dali.yanxiufei.cn/Article/details/gtpjydbovf.html

Lua ............ 10
来源：http://dali.wangshuangyany.cn/Article/details/gtzkpulcuq.html

Perl ........... 10
来源：http://dali.sysykeji.top/Article/details/gthrjacxnh.html

Scala .......... 10
来源：http://dali.xuetiantiany.cn/Article/details/gtujkptflo.html

------------------------------------
来源：http://dali.jqgfzy.top/Article/details/gtwpbsanwl.html

合计 ........... 2106 条
来源：http://dali.snrcjt.cn/Article/details/gtibqxyfkc.html

按章节统计：
来源：http://dali.kuanghao11.cn/Article/details/gtxzosrypv.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xuetiantiany.cn/Article/details/gtvyrudsxe.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.svipenyu.cn/Article/details/gtnfhqybse.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.bjfxy.top/Article/details/gtebaztsgt.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.shzxlz.cn/Article/details/gtplzoywfa.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.sweek.top/Article/details/gtafdkmhxu.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yj20258.top/Article/details/gtswxkbkrw.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.mhx1999.top/Article/details/gtzcqzehgl.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.pycfn.com/Article/details/gtsruievxy.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gtlztuyxqo.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.hnxiangtu.top/Article/details/gthenznaai.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.aizwys.cn/Article/details/gtkxgtzvzj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnslgjyub.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfkwfahsi.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.dianchejie.cn/Article/details/gtmnkiynon.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.dianchejie.cn/Article/details/gtialbpjes.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.chenlongwang.top/Article/details/gthikqbklu.html

Q SQL 专题                              90
来源：http://dali.smart0.xyz/Article/details/gtqqaggpai.html

R Bash 专题                             80
来源：http://dali.guowangkeji.top/Article/details/gtigqhlmxw.html

S C / C++ 专题                          60
来源：http://dali.9152youxi.cn/Article/details/gtnxypamlo.html

T 其他语言补充                          60
来源：http://dali.fengsongda.top/Article/details/gtdoepetav.html

U 高频实用片段                         120
来源：http://dali.jiagoushi.top/Article/details/gtjkcqzoof.html

------------------------------------
来源：http://dali.gzhubu.top/Article/details/gtyjyrsyke.html

合计                                  2106 条
来源：http://dali.jinqigfzy.top/Article/details/gthplxhzkd.html

--------------------------------------------------------------------------------
来源：http://dali.chenlongwang.top/Article/details/gtnvqzfrmn.html

使用提醒
来源：http://dali.bjfxy.top/Article/details/gtkyejtonf.html

--------------------------------------------------------------------------------
来源：http://dali.jianghu66.top/Article/details/gtjsxjvjkt.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yj20258888.top/Article/details/gtcpgexdev.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.dashuyun.cn/Article/details/gtnurnflwn.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.aizwys.cn/Article/details/gtnkorinxu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.pengpengdd.cyou/Article/details/gtkzfrrymi.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.cqqwz.cn/Article/details/gtvistkvjg.html

—— 文件结束 ——
来源：http://dali.sysykeji.top/Article/details/gthyddtrwl.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtnxcooavy.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.nanxuanxn.top/Article/details/gtatiacnqw.html

Common Programming Examples Cheat Book
来源：http://dali.cashguo.top/Article/details/gtmujmzyzx.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtjowfxrja.html

【收录内容】
来源：http://dali.xuanzx.com/Article/details/gtpoxxlfba.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.nanxinkj.top/Article/details/gtjbubvwmd.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.fengsongda.top/Article/details/gtnbrwhdun.html

SQL · Bash · C · C++
来源：http://dali.kuanghao11.cn/Article/details/gtvzeisifo.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.sufxvd.cn/Article/details/gtyyzmzdrv.html

【使用说明】
来源：http://dali.xuetiantiany.cn/Article/details/gtqhgsmhmc.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.xylfe.cn/Article/details/gtvottfrid.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.nanxuanxn.top/Article/details/gtoeidompv.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrxvoajdc.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zdqjudy.top/Article/details/gthzsigxkc.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jinqigfzy.top/Article/details/gtiuzbqymp.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.xinyue.icu/Article/details/gtasnisoha.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yj202588.top/Article/details/gtcdhdlqwu.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.daxiang520.top/Article/details/gtudmkvacc.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jianghu66.top/Article/details/gtmbvgoilm.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.wangdashe.top/Article/details/gtnyjutgjw.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.cashguo.top/Article/details/gtrmydymvm.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.hongshengwenyu.top/Article/details/gtbylwvrhf.html

【文件统计】
来源：http://dali.cheryme.top/Article/details/gtuwbomvte.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.redwolf501.top/Article/details/gtnayeipuu.html

--------------------------------------------------------------------------------
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbweouoqt.html

目  录
来源：http://dali.yongpay.top/Article/details/gtwozycqew.html

--------------------------------------------------------------------------------
来源：http://dali.meibo888.top/Article/details/gtrijxtfrm.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.chenlongwang.top/Article/details/gtaecrnzzw.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.meibo888.top/Article/details/gtmxhcntoc.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhoulong.xyz/Article/details/gtensthujk.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtlnpkugyx.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtqkmbbhwp.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.hfpthk.cn/Article/details/gtijjtgqnl.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hfpthk.cn/Article/details/gtzgzsxfue.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.gogol.net.cn/Article/details/gthyfucmkr.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtbcdgyxbs.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.haohaochexian.top/Article/details/gtasgkxtny.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.nanxinkj.top/Article/details/gtjsviusji.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtmbjkcgsw.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtyjtasfsj.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtdytfesod.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jiagoushi.top/Article/details/gtjjftmsea.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.sxryk.cn/Article/details/gtmmkhpapa.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yueranfly.top/Article/details/gtghcfpdxt.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yj202588.top/Article/details/gttldpyeqx.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.tianlin.xyz/Article/details/gttvwvoioo.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenlongwang.top/Article/details/gtmgqsplwy.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.xuanzx.com/Article/details/gtbmecnelw.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtisnghlop.html

A. 基础语法与类型
来源：http://dali.tianlin.xyz/Article/details/gthigzbgcx.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwfyymxsd.html

[A01] Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtmuyyngmc.html

Py:   print("Hello, World!")
来源：http://dali.zdqjudy.top/Article/details/gttflfspla.html

PHP:  echo "Hello, World!";
来源：http://dali.guannengcc.top/Article/details/gtbfmvqbxx.html

JS:   console.log("Hello, World!");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlilxgpsh.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhiwuduotai.top/Article/details/gtmkgkxcsk.html

Java: System.out.println("Hello, World!");
来源：http://dali.tian-w.cn/Article/details/gtfcknpanc.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.xinyue.icu/Article/details/gtfnvvecmc.html

Ruby: puts "Hello, World!"
来源：http://dali.pengpengdd.cyou/Article/details/gttgcrwlie.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.ppjwa.cn/Article/details/gtwmxwjcpw.html

[A02] 变量声明与赋值
来源：http://dali.svipenyu.cn/Article/details/gturdcusag.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.quarkkingdee.top/Article/details/gtslzzuffb.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gtwrwqiyio.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.fzhhl.top/Article/details/gtacyvaaqr.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hywenlv.cn/Article/details/gtlzkwklpj.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.ybcxt.top/Article/details/gtrgscngfv.html

Go:   name := "Alex"; age := 20
来源：http://dali.daria6918.cn/Article/details/gtypfhvjba.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hongshengwenyu.top/Article/details/gtckfdkaan.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.xziqi.cn/Article/details/gtskzawyfc.html

[A03] 常量定义
来源：http://dali.iojbl.cn/Article/details/gtizdmhfgx.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.shangyingyoupin.top/Article/details/gtjankmvht.html

PHP:  const PI = 3.14159;
来源：http://dali.daxiang520.top/Article/details/gtrlwgqoit.html

JS:   const PI = 3.14159;
来源：http://dali.guannengcc.top/Article/details/gtpicyldgz.html

TS:   const PI: number = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gtogxswyfh.html

Java: static final double PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gtvqffwvdh.html

Go:   const PI = 3.14159
来源：http://dali.shanyushiyangtech.top/Article/details/gtzgyyykom.html


<!-- 参考信息 -->