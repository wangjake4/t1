代发 wailian999

[U39] Py：判断是否在交互环境
来源：http://dali.jqgfzy.top/Article/details/gtymkaoddv.html

sys.stdout.isatty()
来源：http://dali.hfpthk.cn/Article/details/gtezwtkefm.html

[U40] Py：打印到标准错误
来源：http://dali.iojbl.cn/Article/details/gtmzadqxsd.html

print("err", file=sys.stderr)
来源：http://dali.cheryme.top/Article/details/gtjfsrktoh.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jyoumei.cn/Article/details/gtpzchckwo.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xuetiantiany.cn/Article/details/gtlcwggrxa.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.sweek.top/Article/details/gtyfwpnmba.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhongyouzk.top/Article/details/gtxksguwuu.html

[U43] PHP：声明命名空间
来源：http://dali.hnqzz.top/Article/details/gtmgttovhl.html

namespace App\Http;
来源：http://dali.daxiang520.top/Article/details/gtfmurblnh.html

[U44] PHP：开启严格类型
来源：http://dali.shuidangran.top/Article/details/gtdaskszlp.html

declare(strict_types=1);
来源：http://dali.andypj.xyz/Article/details/gtcjnlxqvs.html

[U45] PHP：类型声明与返回类型
来源：http://dali.smart0.xyz/Article/details/gtgauvcojg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gaohongyu789.top/Article/details/gtrzkdandv.html

[U46] PHP：可空类型
来源：http://dali.daria6918.cn/Article/details/gtbqdqakvk.html

?string $name = null
来源：http://dali.hysaishi.cn/Article/details/gtrimisvco.html

[U47] PHP：联合类型
来源：http://dali.hywenlv.cn/Article/details/gtjxoyvidk.html

int|string $id
来源：http://dali.jqgufenzy.top/Article/details/gtuelbwvpi.html

[U48] PHP：纯枚举
来源：http://dali.yanxiufei.cn/Article/details/gtugwpoqfb.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtkgwukoxm.html

[U49] PHP：只读属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmngncanr.html

public readonly string $name
来源：http://dali.yueranfly.top/Article/details/gtbqwnborp.html

[U50] PHP：构造器属性提升
来源：http://dali.shuidangran.top/Article/details/gtaruecphu.html

public function __construct(private int $id) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtgudnajzi.html

[U51] PHP：数组解构
来源：http://dali.sufxvd.cn/Article/details/gtdtaleshq.html

[$a, $b] = $arr;
来源：http://dali.ydzc1.top/Article/details/gtwsyrbqrl.html

[U52] PHP：箭头函数
来源：http://dali.birdmap.top/Article/details/gtwxkufcgo.html

$double = fn($x) => $x * 2;
来源：http://dali.ivvv.top/Article/details/gtmwdiwzne.html

[U53] PHP：空合并运算符
来源：http://dali.tian-w.cn/Article/details/gtdjuvooch.html

$v = $a ?? $b ?? "default";
来源：http://dali.wangshuangyany.cn/Article/details/gtiaoqqogb.html

[U54] PHP：空安全调用
来源：http://dali.daxiang520.top/Article/details/gtmaljvneh.html

$obj?->method()
来源：http://dali.zhongyouzk.top/Article/details/gtzvvqwery.html

[U55] PHP：match 表达式
来源：http://dali.zhengqikj.top/Article/details/gtbzjceqwm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.feifeiyinyue.top/Article/details/gtrpwypdgk.html

[U56] PHP：命名参数
来源：http://dali.havefunace.top/Article/details/gtrwzbubue.html

f(a: 1, b: 2)
来源：http://dali.ivvv.top/Article/details/gtyfphoqhc.html

[U57] PHP：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gtplkxmpyq.html

"值: {$a}"
来源：http://dali.vqdsnc.cn/Article/details/gttcmljsgh.html

[U58] PHP：数组三件套
来源：http://dali.shanyushiyangtech.top/Article/details/gtboqqfcsv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.guannengcc.top/Article/details/gtrjjkfbjm.html

[U59] PHP：自定义排序
来源：http://dali.jianghu66.top/Article/details/gtpeikhvmu.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.fzhhl.top/Article/details/gtotjmsfre.html

[U60] PHP：JSON 编解码
来源：http://dali.yuanzhike.top/Article/details/gtvxxquiqn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.0kj1m.cn/Article/details/gtwjiemjxo.html

[U61] PHP：正则
来源：http://dali.chenzaomai.com/Article/details/gteqphasww.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.tianlin.xyz/Article/details/gtvsxcyjjx.html

[U62] PHP：日期对象
来源：http://dali.shangyingyoupin.top/Article/details/gtxbhipods.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jinqigufen.top/Article/details/gtbrvaqbwu.html

[U63] PHP：文件读写
来源：http://dali.yuxming.cn/Article/details/gtoaxfsneo.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yuanzhike.top/Article/details/gturoohjus.html

[U64] PHP：目录遍历
来源：http://dali.svipenyu.cn/Article/details/gtktiddjur.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.guannengcc.top/Article/details/gtjviovmyi.html

[U65] PHP：会话
来源：http://dali.chenzaomai.com/Article/details/gtaeugjkqm.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtaxqrmqfs.html

[U66] PHP：设置 Cookie
来源：http://dali.jinqigufen.top/Article/details/gtidlocceg.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zdqjudy.top/Article/details/gtqsjmqmri.html

[U67] PHP：处理文件上传
来源：http://dali.pengpengdd.cyou/Article/details/gtufzpnlqi.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.gaohongyu789.top/Article/details/gtuuutpydk.html

[U68] PHP：PDO 连接
来源：http://dali.cqqwz.cn/Article/details/gtnrojhvqz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zycfv.cn/Article/details/gtasvmiihb.html

[U69] PHP：PDO 预处理
来源：http://dali.smart0.xyz/Article/details/gtuzlpujoi.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yj20258888.top/Article/details/gtdsxqkvso.html

[U70] PHP：PDO 事务
来源：http://dali.xuetiantiany.cn/Article/details/gtepdnmgdh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.aizwys.cn/Article/details/gtneaeogxh.html

[U71] PHP：抛出异常
来源：http://dali.aibaodan.cn/Article/details/gtebevvgcs.html

throw new RuntimeException("失败", 500);
来源：http://dali.yonumen.top/Article/details/gtbvvbbnwf.html

[U72] PHP：写错误日志
来源：http://dali.gogol.net.cn/Article/details/gtjcrkrtxq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.bjfxy.top/Article/details/gtsofoeovl.html

[U73] PHP：读取 ini 配置
来源：http://dali.hnxiangtu.top/Article/details/gtveuaqypd.html

parse_ini_file("config.ini", true)
来源：http://dali.zhengqikj.top/Article/details/gtnocitwwb.html

[U74] PHP：读取环境变量
来源：http://dali.ybcxt.top/Article/details/gtmgazpwdw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gttjkioviq.html

[U75] PHP：依赖注入
来源：http://dali.yuxming.cn/Article/details/gtysjxokwa.html

composer require psr/container
来源：http://dali.c1oappe.top/Article/details/gtyvxyimcs.html

[U76] PHP：简单路由
来源：http://dali.316326.xyz/Article/details/gtxttqfasu.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.daxiang520.top/Article/details/gtgtmesuqy.html

[U77] PHP：模板渲染
来源：http://dali.xziqi.cn/Article/details/gttjgydfot.html

composer require twig/twig
来源：http://dali.pycfn.com/Article/details/gtfgswoukt.html

[U78] PHP：单元测试
来源：http://dali.yongpay.top/Article/details/gtfxghsxyd.html

composer require --dev phpunit/phpunit
来源：http://dali.jiagoushi.top/Article/details/gttqedegvi.html

[U79] PHP：静态分析
来源：http://dali.hnqzz.top/Article/details/gtskksnikx.html

composer require --dev phpstan/phpstan
来源：http://dali.xinyue.icu/Article/details/gtzgvycvao.html

[U80] PHP：代码规范修复
来源：http://dali.zhiwuduotai.top/Article/details/gtjefekisf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.shanyushiyangtech.top/Article/details/gtdyhxrxrr.html

[U81] JS：初始化项目
来源：http://dali.jqgufenzy.top/Article/details/gtqibalcoo.html

npm init -y;  npm i express
来源：http://dali.chenlongwang.top/Article/details/gthizfnejj.html

[U82] JS：package.json 脚本
来源：http://dali.daria6918.cn/Article/details/gtgtxulpwg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.nanxuanxn.top/Article/details/gtditafywk.html

[U83] JS：ES Module 导入导出
来源：http://dali.haohaochexian.top/Article/details/gtjhjfrpwq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.9152youxi.cn/Article/details/gtrkvxoxsh.html

[U84] JS：CommonJS 写法
来源：http://dali.daria6918.cn/Article/details/gtwpkfiffc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jyoumei.cn/Article/details/gtmixsspyi.html

[U85] JS：可选链
来源：http://dali.chenzaomai.com/Article/details/gtrzzykreo.html

a?.b?.c
来源：http://dali.gogol.net.cn/Article/details/gtzugmiwzl.html

[U86] JS：空值合并
来源：http://dali.sysykeji.top/Article/details/gtiyfzxgxs.html

a ?? b
来源：http://dali.xuetiantiany.cn/Article/details/gtdtpmukaa.html

[U87] JS：解构默认值
来源：http://dali.yongpay.top/Article/details/gtawcntono.html

const { a = 1, b = 2 } = obj;
来源：http://dali.cqqwz.cn/Article/details/gtbqraukoo.html

[U88] JS：对象展开合并
来源：http://dali.jqgufenzy.top/Article/details/gtltodyxqs.html

{ ...a, ...b }
来源：http://dali.pengpengdd.cyou/Article/details/gteowgaokm.html

[U89] JS：数组去重
来源：http://dali.cucudq.cn/Article/details/gtshwfvjrc.html

[...new Set(arr)]
来源：http://dali.havefunace.top/Article/details/gthwavktqj.html

[U90] JS：数字数组排序
来源：http://dali.zhoulong.xyz/Article/details/gtvqeujprs.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwxnaohd.html

[U91] JS：对象键值遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtgrfcwpzu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ydzc1.top/Article/details/gtxxhvvlil.html

[U92] JS：深拷贝
来源：http://dali.yj20258888.top/Article/details/gttnvhekro.html

structuredClone(obj)
来源：http://dali.bjfxy.top/Article/details/gtvciweqig.html

[U93] JS：模板字符串
来源：http://dali.chenzaomai.com/Article/details/gtvjfufdfy.html

`共 ${n} 条`
来源：http://dali.zhiwuduotai.top/Article/details/gtyyxnamwu.html

[U94] JS：箭头函数
来源：http://dali.xuanzx.com/Article/details/gtwcqfufsb.html

const double = x => x * 2;
来源：http://dali.xylfe.cn/Article/details/gtbiegccvt.html

[U95] JS：Promise 包装
来源：http://dali.yueranfly.top/Article/details/gtlhbeyily.html

new Promise((resolve, reject) => {})
来源：http://dali.chenzaomai.com/Article/details/gtbezfzefr.html

[U96] JS：async/await 与异常
来源：http://dali.hongshengwenyu.top/Article/details/gtedqkudzc.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gtvtimgvna.html

[U97] JS：并发请求
来源：http://dali.kuanghao11.cn/Article/details/gtjlharwvy.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgfzy.top/Article/details/gtimjgrnru.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gtlptkkmnc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.meibo888.top/Article/details/gtxyovgofc.html

[U99] JS：事件监听
来源：http://dali.guannengcc.top/Article/details/gtfowzsefm.html

el.addEventListener("click", e => {})
来源：http://dali.xuanzx.com/Article/details/gthnmenoeb.html

[U100] JS：DOM 查询
来源：http://dali.yvedp.cn/Article/details/gtrrwggtsw.html

document.querySelector(".item")
来源：http://dali.zhoulong.xyz/Article/details/gttzlimgbl.html

[U101] JS：classList 操作
来源：http://dali.zycfv.cn/Article/details/gthmvbqlcg.html

el.classList.toggle("active")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgdpynjro.html

[U102] JS：本地存储
来源：http://dali.zhengqikj.top/Article/details/gtohkyduyg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.birdmap.top/Article/details/gtkmhrzajn.html

[U103] JS：定时器
来源：http://dali.9152youxi.cn/Article/details/gtzsgffqib.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.nwbrower.top/Article/details/gtjzvaeivv.html

[U104] JS：防抖
来源：http://dali.wangdashe.top/Article/details/gtalbwrhei.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.andypj.xyz/Article/details/gtfsktmzcf.html

[U105] JS：节流
来源：http://dali.andypj.xyz/Article/details/gtpvfwvmpw.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.feifeiyinyue.top/Article/details/gttjrgedmk.html

[U106] JS：日期格式化
来源：http://dali.ivvv.top/Article/details/gtzbobhvpb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hnqzz.top/Article/details/gtlxczburc.html

[U107] JS：数字千分位
来源：http://dali.nanxinkj.top/Article/details/gtbhgaeqqd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.meibo888.top/Article/details/gtfibujqta.html

[U108] JS：随机整数
来源：http://dali.yangfankeji.com/Article/details/gtgqfmbpoy.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.dashuyun.cn/Article/details/gtghmgtemv.html

[U109] JS：数组分组
来源：http://dali.cdnleiting.top/Article/details/gtevsrwmtz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.fzhhl.top/Article/details/gtzrpsvnuo.html

[U110] JS：数组分块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdypfplh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpeievcoh.html

[U111] JS：对象转 Map
来源：http://dali.yongpay.top/Article/details/gtjfbgliie.html

new Map(Object.entries(obj))
来源：http://dali.chenlongwang.top/Article/details/gtdhwplowl.html

[U112] JS：字符串补位
来源：http://dali.jinghuilouyu.cn/Article/details/gtpukktwnh.html

"7".padStart(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gtfatskxqa.html

[U113] JS：正则替换全部
来源：http://dali.c1oappe.top/Article/details/gtlhpcqqas.html

s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtzpnrlink.html

[U114] JS：JSON 深比较
来源：http://dali.ydzc1.top/Article/details/gtzqribffd.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dashuyun.cn/Article/details/gtcujxnwau.html

[U115] JS：生成 UUID
来源：http://dali.zycfv.cn/Article/details/gtkllmfbep.html

crypto.randomUUID()
来源：http://dali.cashguo.top/Article/details/gtyyvdqgds.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.gogol.net.cn/Article/details/gtqoddphlh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.guowangkeji.top/Article/details/gtlypqqeol.html

[U117] JS：单元测试
来源：http://dali.cqqwz.cn/Article/details/gtnajwhpyy.html

npm i -D vitest;  npx vitest
来源：http://dali.cdnleiting.top/Article/details/gtxrwgvmhx.html

[U118] JS：开发服务器
来源：http://dali.yongpay.top/Article/details/gtgviyvdwm.html

npm i -D vite;  npx vite
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmtyftyge.html

[U119] JS：生产构建
来源：http://dali.yuanzhike.top/Article/details/gtkglsnltp.html

npx vite build
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiorelubh.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.sweek.top/Article/details/gtzcdqbqyw.html

import.meta.env.VITE_API_URL
来源：http://dali.hammf.cn/Article/details/gtxoxetqeb.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtlfbpnrjv.html

统计汇总
来源：http://dali.ehwqpu.com/Article/details/gteeqcqube.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtevnbmfjm.html

按语言统计（条）：
来源：http://dali.sxryk.cn/Article/details/gtovymgdrh.html

Python ......... 252
来源：http://dali.tian-w.cn/Article/details/gtghgvlltd.html

PHP ............ 252
来源：http://dali.c1oappe.top/Article/details/gtopfcbdhq.html

JavaScript ..... 252
来源：http://dali.jlsjyb.cn/Article/details/gtsnkquvcu.html

TypeScript ..... 212
来源：http://dali.quarkkingdee.top/Article/details/gtihbdlrgq.html

Java ........... 212
来源：http://dali.cqqwz.cn/Article/details/gtunqxhaih.html

Go ............. 212
来源：http://dali.jqgufenzy.top/Article/details/gtwxspvenw.html

Ruby ........... 212
来源：http://dali.meibo888.top/Article/details/gtbijerhug.html

C# ............. 212
来源：http://dali.yueranfly.top/Article/details/gteziuwtax.html

C .............. 30
来源：http://dali.vqdsnc.cn/Article/details/gtouaxzrvd.html

C++ ............ 30
来源：http://dali.yongpay.top/Article/details/gtsavyfvth.html

SQL ............ 90
来源：http://dali.quarkkingdee.top/Article/details/gtcgsazrur.html

Bash ........... 80
来源：http://dali.hongshengwenyu.top/Article/details/gttorvxtww.html

Kotlin ......... 15
来源：http://dali.ivvv.top/Article/details/gtlwphlqpw.html

Swift .......... 15
来源：http://dali.chenlongwang.top/Article/details/gtjzodhjof.html

Lua ............ 10
来源：http://dali.ybcxt.top/Article/details/gtyjinnmbw.html

Perl ........... 10
来源：http://dali.chenjidiqi.icu/Article/details/gtpsdmtujx.html

Scala .......... 10
来源：http://dali.aibaodan.cn/Article/details/gtovmblkgg.html

------------------------------------
来源：http://dali.fzhhl.top/Article/details/gtskantoik.html

合计 ........... 2106 条
来源：http://dali.wangshuangyany.cn/Article/details/gtvofajmxf.html

按章节统计：
来源：http://dali.redwolf501.top/Article/details/gtskosokjz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jqgfzy.top/Article/details/gtqvnooekg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhongyouzk.top/Article/details/gtnmgugjnp.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.svipenyu.cn/Article/details/gtqutbahdn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.sweek.top/Article/details/gtvqjjudtv.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.nwbrower.top/Article/details/gtkuniprwf.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.tanke756.top/Article/details/gtuuhkrsdq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yj20258888.top/Article/details/gtarzfnspp.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jlsjyb.cn/Article/details/gtcldfujfk.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jinqigufen.top/Article/details/gtzkxvvght.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.shanyushiyangtech.top/Article/details/gtqdgiggrr.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.cheryme.top/Article/details/gtprjsevvo.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.dashuyun.cn/Article/details/gtydhsiknc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gtohsdmrjz.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtssbdghxp.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yj20258.top/Article/details/gtvhtoqmhk.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yonumen.top/Article/details/gtokmfycle.html

Q SQL 专题                              90
来源：http://dali.jqgufenzy.top/Article/details/gtgkacqnsf.html

R Bash 专题                             80
来源：http://dali.haohaochexian.top/Article/details/gtifnfkfhv.html

S C / C++ 专题                          60
来源：http://dali.jyoumei.cn/Article/details/gtaiiqdlbw.html

T 其他语言补充                          60
来源：http://dali.havefunace.top/Article/details/gtrsrclbge.html

U 高频实用片段                         120
来源：http://dali.sufxvd.cn/Article/details/gtqqacuhmq.html

------------------------------------
来源：http://dali.birdmap.top/Article/details/gtmdzzpaij.html

合计                                  2106 条
来源：http://dali.cdnleiting.top/Article/details/gtnlzqqhak.html

--------------------------------------------------------------------------------
来源：http://dali.jyoumei.cn/Article/details/gtqxopedof.html

使用提醒
来源：http://dali.snrcjt.cn/Article/details/gtitpkodvz.html

--------------------------------------------------------------------------------
来源：http://dali.snrcjt.cn/Article/details/gtrtqejduq.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.gaohongyu789.top/Article/details/gtmrgllrxl.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.gaohongyu789.top/Article/details/gtlrpqnbms.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.cashguo.top/Article/details/gtgbphqnkj.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xinyue.icu/Article/details/gtbdqiytjx.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.chenjidiqi.icu/Article/details/gtoaicssgb.html

—— 文件结束 ——
来源：http://dali.haohaochexian.top/Article/details/gtasfosshp.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtlvybovlj.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhoulong.xyz/Article/details/gtpcmhkqgz.html

Common Programming Examples Cheat Book
来源：http://dali.pycfn.com/Article/details/gtgokynunk.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtlylxjymj.html

【收录内容】
来源：http://dali.kuanghao11.cn/Article/details/gtizeklbpr.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.aizwys.cn/Article/details/gtpttdoivs.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhengqikj.top/Article/details/gtylyzkyfl.html

SQL · Bash · C · C++
来源：http://dali.ybcxt.top/Article/details/gtkicybmkg.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.svipenyu.cn/Article/details/gtksckephk.html

【使用说明】
来源：http://dali.316326.xyz/Article/details/gtcomiivzi.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.daxiang520.top/Article/details/gttbupdobx.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zdqjudy.top/Article/details/gtjnczzfmk.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hfpthk.cn/Article/details/gtlqlgsrvv.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.aizwys.cn/Article/details/gtrqchdsnm.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.9152youxi.cn/Article/details/gtjvzhphyk.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.shuidangran.top/Article/details/gtlqhgarrs.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yueranfly.top/Article/details/gtfinvkcxc.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jqgfzy.top/Article/details/gthypdszln.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.nanxinkj.top/Article/details/gtpfjvmimv.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.cucudq.cn/Article/details/gtwsprewnz.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jiagoushi.top/Article/details/gtdsvbzvxe.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.tianlin.xyz/Article/details/gtvscqvbfi.html

【文件统计】
来源：http://dali.zhoulong.xyz/Article/details/gtnkmlgxxj.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.havefunace.top/Article/details/gtjgdlhozx.html

--------------------------------------------------------------------------------
来源：http://dali.zhoulong.xyz/Article/details/gtouwbknos.html

目  录
来源：http://dali.hongshengwenyu.top/Article/details/gtxhhfhwcu.html

--------------------------------------------------------------------------------
来源：http://dali.zhixingplan.top/Article/details/gtdxnkelbh.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.aibaodan.cn/Article/details/gttzcaowny.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yj202588.top/Article/details/gtrvjdpjia.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhengqikj.top/Article/details/gtmcygradr.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.meibo888.top/Article/details/gtgkyxjvhi.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.andypj.xyz/Article/details/gtctsscovi.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zycfv.cn/Article/details/gtnvfltmee.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.daria6918.cn/Article/details/gtgvlkxdai.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.xinyue.icu/Article/details/gtnfcgadfv.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.redwolf501.top/Article/details/gtkjduxyya.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhixingplan.top/Article/details/gtxjamefol.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.pycfn.com/Article/details/gthwghirzr.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zycfv.cn/Article/details/gtrhwqgmak.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yonumen.top/Article/details/gtfwyhqvla.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtvlswflmy.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yueranfly.top/Article/details/gtcdtouunv.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gtuhustqqa.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zdqjudy.top/Article/details/gtrauueanx.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.mhx1999.top/Article/details/gtmrewucoj.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.dianchejie.cn/Article/details/gthqorarfv.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ppjwa.cn/Article/details/gtyzhxeexh.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.havefunace.top/Article/details/gtdmrcjymn.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gthgqujyrg.html

A. 基础语法与类型
来源：http://dali.aibaodan.cn/Article/details/gtinhzwxit.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtkhipjwpw.html

[A01] Hello World
来源：http://dali.sysykeji.top/Article/details/gtiifllbzv.html

Py:   print("Hello, World!")
来源：http://dali.nwbrower.top/Article/details/gtkdgieywy.html

PHP:  echo "Hello, World!";
来源：http://dali.cqqwz.cn/Article/details/gtqeflmtpf.html

JS:   console.log("Hello, World!");
来源：http://dali.sysykeji.top/Article/details/gtkeaweezk.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.nanxuanxn.top/Article/details/gtrpfzciso.html

Java: System.out.println("Hello, World!");
来源：http://dali.iojbl.cn/Article/details/gtqtebcxlz.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.sufxvd.cn/Article/details/gtmntgybsq.html

Ruby: puts "Hello, World!"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxhhzzdif.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.chenjidiqi.icu/Article/details/gtpwrdjbmm.html

[A02] 变量声明与赋值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoosygocg.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.smart0.xyz/Article/details/gtstxnzgpr.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkbcqitt.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.cheryme.top/Article/details/gtvlqwqnck.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hongshengwenyu.top/Article/details/gtugsvrqpd.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.svipenyu.cn/Article/details/gtbxegxdps.html

Go:   name := "Alex"; age := 20
来源：http://dali.jianghu66.top/Article/details/gtwbyahctn.html

Ruby: name = "Alex"; age = 20
来源：http://dali.cucudq.cn/Article/details/gtzfiuxzep.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.redwolf501.top/Article/details/gtkfjjgshu.html

[A03] 常量定义
来源：http://dali.yj20258888.top/Article/details/gtltkturhd.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.shangyingyoupin.top/Article/details/gtoicepoou.html

PHP:  const PI = 3.14159;
来源：http://dali.bjfxy.top/Article/details/gtqrzaxlzg.html

JS:   const PI = 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gtetohwrvf.html

TS:   const PI: number = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gtcfspfhnm.html

Java: static final double PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gtdufzsyio.html

Go:   const PI = 3.14159
来源：http://dali.tianlin.xyz/Article/details/gtvsuoyyap.html

Ruby: PI = 3.14159
来源：http://dali.pengpengdd.cyou/Article/details/gtwjztnhai.html

C#:   const double PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtisoikpzz.html

[A04] 判断变量类型
来源：http://dali.wangshuangyany.cn/Article/details/gtebyygmts.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.shanyushiyangtech.top/Article/details/gtweulbhou.html


<!-- 参考信息 -->