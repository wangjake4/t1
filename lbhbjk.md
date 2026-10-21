代发 wailian999

[U41] PHP：初始化 Composer 项目
来源：http://dali.jinqigufen.top/Article/details/gtvnanoyey.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.tanke756.top/Article/details/gtxfjhtdpn.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hysaishi.cn/Article/details/gtgslkltwy.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yueranfly.top/Article/details/gtypbvakjz.html

[U43] PHP：声明命名空间
来源：http://dali.sysykeji.top/Article/details/gtjofhlzrp.html

namespace App\Http;
来源：http://dali.jlsjyb.cn/Article/details/gtaziyhimv.html

[U44] PHP：开启严格类型
来源：http://dali.birdmap.top/Article/details/gtztbcumgo.html

declare(strict_types=1);
来源：http://dali.c1oappe.top/Article/details/gtqmzxhkxu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.tanke756.top/Article/details/gtilraouwm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gtwgboxihx.html

[U46] PHP：可空类型
来源：http://dali.jinqigufen.top/Article/details/gtkbqvcuvl.html

?string $name = null
来源：http://dali.yj20258888.top/Article/details/gtxyciduzl.html

[U47] PHP：联合类型
来源：http://dali.yueranfly.top/Article/details/gtiblyhofg.html

int|string $id
来源：http://dali.cashguo.top/Article/details/gtqsmhfhdp.html

[U48] PHP：纯枚举
来源：http://dali.ydzc1.top/Article/details/gtazkndeqv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shzxlz.cn/Article/details/gtvxavmhln.html

[U49] PHP：只读属性
来源：http://dali.zhengqikj.top/Article/details/gtaqmozjbr.html

public readonly string $name
来源：http://dali.0kj1m.cn/Article/details/gtngywthaq.html

[U50] PHP：构造器属性提升
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtunvapjju.html

public function __construct(private int $id) {}
来源：http://dali.sufxvd.cn/Article/details/gtkmbnctxh.html

[U51] PHP：数组解构
来源：http://dali.c1oappe.top/Article/details/gtzzvttdlx.html

[$a, $b] = $arr;
来源：http://dali.xuetiantiany.cn/Article/details/gtimstcelt.html

[U52] PHP：箭头函数
来源：http://dali.smart0.xyz/Article/details/gtrbawghjt.html

$double = fn($x) => $x * 2;
来源：http://dali.shangyingyoupin.top/Article/details/gtxxlxoeco.html

[U53] PHP：空合并运算符
来源：http://dali.smart0.xyz/Article/details/gthjdqanop.html

$v = $a ?? $b ?? "default";
来源：http://dali.wangdashe.top/Article/details/gtclgrxomn.html

[U54] PHP：空安全调用
来源：http://dali.vqdsnc.cn/Article/details/gtnkivrewa.html

$obj?->method()
来源：http://dali.havefunace.top/Article/details/gttuhpofkw.html

[U55] PHP：match 表达式
来源：http://dali.yueranfly.top/Article/details/gtbvhodrga.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqxrciyon.html

[U56] PHP：命名参数
来源：http://dali.cdnleiting.top/Article/details/gtjipvrgaa.html

f(a: 1, b: 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxfnofvt.html

[U57] PHP：字符串插值
来源：http://dali.gzhubu.top/Article/details/gtrfzgfrem.html

"值: {$a}"
来源：http://dali.ybcxt.top/Article/details/gtwkmebqoe.html

[U58] PHP：数组三件套
来源：http://dali.sxryk.cn/Article/details/gttghqopsi.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.daria6918.cn/Article/details/gtkjrjfuwa.html

[U59] PHP：自定义排序
来源：http://dali.jqgufenzy.top/Article/details/gtajycxhre.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hnxiangtu.top/Article/details/gtnssgmabe.html

[U60] PHP：JSON 编解码
来源：http://dali.ybcxt.top/Article/details/gtxlvsmsoe.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jqgufenzy.top/Article/details/gtbghzkjjt.html

[U61] PHP：正则
来源：http://dali.cucudq.cn/Article/details/gtqfuxkmcl.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.xylfe.cn/Article/details/gtzgnryjbt.html

[U62] PHP：日期对象
来源：http://dali.zhongyouzk.top/Article/details/gtetyaflta.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yueranfly.top/Article/details/gtfoybjkhs.html

[U63] PHP：文件读写
来源：http://dali.9152youxi.cn/Article/details/gtiygnirnv.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.guowangkeji.top/Article/details/gtmlynmtwk.html

[U64] PHP：目录遍历
来源：http://dali.nwbrower.top/Article/details/gttdlhegxc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.nanxuanxn.top/Article/details/gtiuwfehsd.html

[U65] PHP：会话
来源：http://dali.gaohongyu789.top/Article/details/gtxemldnqw.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.shuidangran.top/Article/details/gtdkmipauc.html

[U66] PHP：设置 Cookie
来源：http://dali.sufxvd.cn/Article/details/gttodhsokd.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.sysykeji.top/Article/details/gtvjkejxya.html

[U67] PHP：处理文件上传
来源：http://dali.yvedp.cn/Article/details/gtxlixczwl.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yonumen.top/Article/details/gterhbsxrt.html

[U68] PHP：PDO 连接
来源：http://dali.daria6918.cn/Article/details/gtnulxbldv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zdqjudy.top/Article/details/gtwtdwhrvf.html

[U69] PHP：PDO 预处理
来源：http://dali.wangshuangyany.cn/Article/details/gtowjhflld.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jqgufenzy.top/Article/details/gtsgbxsxeu.html

[U70] PHP：PDO 事务
来源：http://dali.zhixingplan.top/Article/details/gtomfkkuwv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gtfzkrfsfb.html

[U71] PHP：抛出异常
来源：http://dali.gogol.net.cn/Article/details/gtqbdgulye.html

throw new RuntimeException("失败", 500);
来源：http://dali.wangdashe.top/Article/details/gttnjvdimd.html

[U72] PHP：写错误日志
来源：http://dali.yvedp.cn/Article/details/gthvrgmwmc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xylfe.cn/Article/details/gtyeqrrmwc.html

[U73] PHP：读取 ini 配置
来源：http://dali.shangyingyoupin.top/Article/details/gtkheyxhnx.html

parse_ini_file("config.ini", true)
来源：http://dali.ybcxt.top/Article/details/gtisfenzyr.html

[U74] PHP：读取环境变量
来源：http://dali.gzhubu.top/Article/details/gthkxakqkw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.daxiang520.top/Article/details/gtgbluaqdi.html

[U75] PHP：依赖注入
来源：http://dali.jiagoushi.top/Article/details/gtixgthtmw.html

composer require psr/container
来源：http://dali.birdmap.top/Article/details/gtyiindfrf.html

[U76] PHP：简单路由
来源：http://dali.daria6918.cn/Article/details/gtqzhahzpr.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.gogol.net.cn/Article/details/gtakvzllnd.html

[U77] PHP：模板渲染
来源：http://dali.guannengcc.top/Article/details/gtyehqzqbp.html

composer require twig/twig
来源：http://dali.9152youxi.cn/Article/details/gtrurxctpb.html

[U78] PHP：单元测试
来源：http://dali.gogol.net.cn/Article/details/gthnnzwyzu.html

composer require --dev phpunit/phpunit
来源：http://dali.nanxuanxn.top/Article/details/gtbnbysqef.html

[U79] PHP：静态分析
来源：http://dali.jinqigfzy.top/Article/details/gtzcwzgkzb.html

composer require --dev phpstan/phpstan
来源：http://dali.meibo888.top/Article/details/gtlcaglfuc.html

[U80] PHP：代码规范修复
来源：http://dali.fengsongda.top/Article/details/gtiiuqzgzv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yj20258.top/Article/details/gtezxagelh.html

[U81] JS：初始化项目
来源：http://dali.aizwys.cn/Article/details/gtpuhffzcd.html

npm init -y;  npm i express
来源：http://dali.zhaomingkeji.xyz/Article/details/gtycpotvss.html

[U82] JS：package.json 脚本
来源：http://dali.sxryk.cn/Article/details/gtjbhonwte.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.pengpengdd.cyou/Article/details/gtmbwunmtm.html

[U83] JS：ES Module 导入导出
来源：http://dali.hysaishi.cn/Article/details/gtnrapyuxw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.mhx1999.top/Article/details/gtlvdpzaoh.html

[U84] JS：CommonJS 写法
来源：http://dali.nwbrower.top/Article/details/gtldsfyros.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhongyouzk.top/Article/details/gtrbvhwmhr.html

[U85] JS：可选链
来源：http://dali.haohaochexian.top/Article/details/gtjxkyximx.html

a?.b?.c
来源：http://dali.jiagoushi.top/Article/details/gtakokrpgp.html

[U86] JS：空值合并
来源：http://dali.ehwqpu.com/Article/details/gtufcawdht.html

a ?? b
来源：http://dali.quarkkingdee.top/Article/details/gtjberchil.html

[U87] JS：解构默认值
来源：http://dali.jqgufenzy.top/Article/details/gtdevjndvu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.ybcxt.top/Article/details/gtijlcyohz.html

[U88] JS：对象展开合并
来源：http://dali.yj20258888.top/Article/details/gtulgktdsy.html

{ ...a, ...b }
来源：http://dali.bjfxy.top/Article/details/gtjdcigusz.html

[U89] JS：数组去重
来源：http://dali.hongshengwenyu.top/Article/details/gttnnnzxkv.html

[...new Set(arr)]
来源：http://dali.jiagoushi.top/Article/details/gthybtloag.html

[U90] JS：数字数组排序
来源：http://dali.tanke756.top/Article/details/gtdwmichzx.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hfpthk.cn/Article/details/gtdwjunaeu.html

[U91] JS：对象键值遍历
来源：http://dali.yanxiufei.cn/Article/details/gteaeumntf.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yanxiufei.cn/Article/details/gtslwsajap.html

[U92] JS：深拷贝
来源：http://dali.dianchejie.cn/Article/details/gtjgsistyc.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtpnommyqx.html

[U93] JS：模板字符串
来源：http://dali.yj20258888.top/Article/details/gtwrsypalm.html

`共 ${n} 条`
来源：http://dali.gotoacloud.top/Article/details/gtclgkekve.html

[U94] JS：箭头函数
来源：http://dali.shzxlz.cn/Article/details/gtarkfkllj.html

const double = x => x * 2;
来源：http://dali.yvedp.cn/Article/details/gtdahfedwd.html

[U95] JS：Promise 包装
来源：http://dali.316326.xyz/Article/details/gtywezwojx.html

new Promise((resolve, reject) => {})
来源：http://dali.chenjidiqi.icu/Article/details/gtkxrxkczj.html

[U96] JS：async/await 与异常
来源：http://dali.daxiang520.top/Article/details/gtseighquz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gtoccxpanw.html

[U97] JS：并发请求
来源：http://dali.jinqigfzy.top/Article/details/gtqvrirhxy.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ydzc1.top/Article/details/gtigimjesi.html

[U98] JS：fetch 带 JSON
来源：http://dali.cheryme.top/Article/details/gtojpqevii.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.guannengcc.top/Article/details/gtximmdxgf.html

[U99] JS：事件监听
来源：http://dali.fengsongda.top/Article/details/gtwkbqmzqr.html

el.addEventListener("click", e => {})
来源：http://dali.chenjidiqi.icu/Article/details/gtqapbvwwj.html

[U100] JS：DOM 查询
来源：http://dali.hammf.cn/Article/details/gtpolwslfj.html

document.querySelector(".item")
来源：http://dali.redwolf501.top/Article/details/gtoqxokdyd.html

[U101] JS：classList 操作
来源：http://dali.gzhubu.top/Article/details/gtwrnatftx.html

el.classList.toggle("active")
来源：http://dali.hammf.cn/Article/details/gtucoldhfz.html

[U102] JS：本地存储
来源：http://dali.yanxiufei.cn/Article/details/gthuwfgdtt.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoatpupnj.html

[U103] JS：定时器
来源：http://dali.jlsjyb.cn/Article/details/gtkgoghleq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.haohaochexian.top/Article/details/gtjuneglbt.html

[U104] JS：防抖
来源：http://dali.yj20258888.top/Article/details/gtjyxogdwi.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuxming.cn/Article/details/gtycgavago.html

[U105] JS：节流
来源：http://dali.jinqigufen.top/Article/details/gtjyiyvdqc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlkvbumrx.html

[U106] JS：日期格式化
来源：http://dali.sweek.top/Article/details/gtqttumwvf.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zdqjudy.top/Article/details/gtjqebfvta.html

[U107] JS：数字千分位
来源：http://dali.yonumen.top/Article/details/gtoqffkupo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.sysykeji.top/Article/details/gtmksiedmp.html

[U108] JS：随机整数
来源：http://dali.yanxiufei.cn/Article/details/gtmbbpxhfo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yongpay.top/Article/details/gtwmpgrzeq.html

[U109] JS：数组分组
来源：http://dali.nanxuanxn.top/Article/details/gtpazbehpn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yongpay.top/Article/details/gtgyjrjjli.html

[U110] JS：数组分块
来源：http://dali.wangdashe.top/Article/details/gtyawepdmx.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.snrcjt.cn/Article/details/gtzjtgvsjn.html

[U111] JS：对象转 Map
来源：http://dali.zhengqikj.top/Article/details/gtarowijih.html

new Map(Object.entries(obj))
来源：http://dali.kuanghao11.cn/Article/details/gttkayupby.html

[U112] JS：字符串补位
来源：http://dali.jinghuilouyu.cn/Article/details/gtnzacosgd.html

"7".padStart(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gtnakkvxdh.html

[U113] JS：正则替换全部
来源：http://dali.pengpengdd.cyou/Article/details/gtzinyvota.html

s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtrtbftuft.html

[U114] JS：JSON 深比较
来源：http://dali.xylfe.cn/Article/details/gthvfsexmr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtenylaguy.html

[U115] JS：生成 UUID
来源：http://dali.xylfe.cn/Article/details/gtrcxlxdyw.html

crypto.randomUUID()
来源：http://dali.hnxiangtu.top/Article/details/gtmbhobnki.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.havefunace.top/Article/details/gtlhgucbll.html

/** @param {string} name */ function f(name) {}
来源：http://dali.daria6918.cn/Article/details/gtrtvffswx.html

[U117] JS：单元测试
来源：http://dali.chenlongwang.top/Article/details/gtlmwmfscf.html

npm i -D vitest;  npx vitest
来源：http://dali.dashuyun.cn/Article/details/gtptmdmvvw.html

[U118] JS：开发服务器
来源：http://dali.andypj.xyz/Article/details/gtwywdgqhq.html

npm i -D vite;  npx vite
来源：http://dali.havefunace.top/Article/details/gtgszppxro.html

[U119] JS：生产构建
来源：http://dali.nanxuanxn.top/Article/details/gtczrefqty.html

npx vite build
来源：http://dali.hnqzz.top/Article/details/gtrrilozdu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.tanke756.top/Article/details/gtgowakwmx.html

import.meta.env.VITE_API_URL
来源：http://dali.shanyushiyangtech.top/Article/details/gtuogvmedc.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtdgmmcfid.html

统计汇总
来源：http://dali.wangshuangyany.cn/Article/details/gtllytfvrw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtteepzjqo.html

按语言统计（条）：
来源：http://dali.gaohongyu789.top/Article/details/gtiybtfmns.html

Python ......... 252
来源：http://dali.xinyue.icu/Article/details/gtfuqufxzd.html

PHP ............ 252
来源：http://dali.cdnleiting.top/Article/details/gtwnbxiyuy.html

JavaScript ..... 252
来源：http://dali.smart0.xyz/Article/details/gtdivhdjun.html

TypeScript ..... 212
来源：http://dali.yongpay.top/Article/details/gtojnngtoo.html

Java ........... 212
来源：http://dali.hnxiangtu.top/Article/details/gtfyuounxt.html

Go ............. 212
来源：http://dali.bjfxy.top/Article/details/gtucfpcgvt.html

Ruby ........... 212
来源：http://dali.birdmap.top/Article/details/gtrwwmmvqu.html

C# ............. 212
来源：http://dali.hongshengwenyu.top/Article/details/gtorvrsnbb.html

C .............. 30
来源：http://dali.nanxinkj.top/Article/details/gtbrhzlzrv.html

C++ ............ 30
来源：http://dali.gotoacloud.top/Article/details/gtmwavaett.html

SQL ............ 90
来源：http://dali.sufxvd.cn/Article/details/gtsaijzhdi.html

Bash ........... 80
来源：http://dali.sufxvd.cn/Article/details/gtrdikgwpq.html

Kotlin ......... 15
来源：http://dali.hnxiangtu.top/Article/details/gtghzgosss.html

Swift .......... 15
来源：http://dali.nanxuanxn.top/Article/details/gtwxyuqeid.html

Lua ............ 10
来源：http://dali.smart0.xyz/Article/details/gtjumvtryz.html

Perl ........... 10
来源：http://dali.snrcjt.cn/Article/details/gtxtvycrdp.html

Scala .......... 10
来源：http://dali.ywan-chungtsiang.top/Article/details/gtizvgqcdo.html

------------------------------------
来源：http://dali.hnqzz.top/Article/details/gthxauxzgi.html

合计 ........... 2106 条
来源：http://dali.yanxiufei.cn/Article/details/gtpkszcbvk.html

按章节统计：
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhqrgpwu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.mhx1999.top/Article/details/gteravdqwr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.haohaochexian.top/Article/details/gtczlndjzv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.fengsongda.top/Article/details/gtprqiemkg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hfpthk.cn/Article/details/gtmbtfabdg.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.9152youxi.cn/Article/details/gtafxmchyl.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hywenlv.cn/Article/details/gtxgpjkhvx.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhixingplan.top/Article/details/gtnoscvwho.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.fengsongda.top/Article/details/gtlffpgdon.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhengqikj.top/Article/details/gturvdfpkn.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.hammf.cn/Article/details/gtypnzjyeh.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gtqxkzqsny.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.316326.xyz/Article/details/gtlxippysy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.svipenyu.cn/Article/details/gtafvskcss.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.tianlin.xyz/Article/details/gtrttylbna.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.nwbrower.top/Article/details/gtjwawjcys.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jianghu66.top/Article/details/gtlhbryrdw.html

Q SQL 专题                              90
来源：http://dali.shanyushiyangtech.top/Article/details/gtzobuhqtv.html

R Bash 专题                             80
来源：http://dali.quarkkingdee.top/Article/details/gtcqoodvsr.html

S C / C++ 专题                          60
来源：http://dali.jinghuilouyu.cn/Article/details/gtufvlcayy.html

T 其他语言补充                          60
来源：http://dali.nwbrower.top/Article/details/gtymooazqc.html

U 高频实用片段                         120
来源：http://dali.cheryme.top/Article/details/gthkurylvk.html

------------------------------------
来源：http://dali.daxiang520.top/Article/details/gtjxcvpcqh.html

合计                                  2106 条
来源：http://dali.316326.xyz/Article/details/gtktsoapne.html

--------------------------------------------------------------------------------
来源：http://dali.fengsongda.top/Article/details/gtxytocdan.html

使用提醒
来源：http://dali.tanke756.top/Article/details/gtvyxnfeyc.html

--------------------------------------------------------------------------------
来源：http://dali.cdnleiting.top/Article/details/gtfmnmltza.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.kuanghao11.cn/Article/details/gtqudcrebk.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jinqigufen.top/Article/details/gtxbgtlvka.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgziphllr.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.0kj1m.cn/Article/details/gtxidisvav.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hnxiangtu.top/Article/details/gtujogsiui.html

—— 文件结束 ——
来源：http://dali.guannengcc.top/Article/details/gtxnxswzhy.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtxaupkiue.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.tanke756.top/Article/details/gtsmlqtepe.html

Common Programming Examples Cheat Book
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwswmdzyj.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtgwoyleqt.html

【收录内容】
来源：http://dali.cdnleiting.top/Article/details/gtknfzwsmj.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.andypj.xyz/Article/details/gtrgfxuqzi.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jqgfzy.top/Article/details/gtanwnnuqy.html

SQL · Bash · C · C++
来源：http://dali.sysykeji.top/Article/details/gtdoyjvyas.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.feifeiyinyue.top/Article/details/gtbmdsqkmg.html

【使用说明】
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhgvjadh.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.kuanghao11.cn/Article/details/gtciporwtj.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yuxming.cn/Article/details/gtcnnvsepe.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.cqqwz.cn/Article/details/gtxbsecdse.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jyoumei.cn/Article/details/gtaumeezbc.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.sysykeji.top/Article/details/gtmqsxbnmr.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yangfankeji.com/Article/details/gtadssityx.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.quarkkingdee.top/Article/details/gtfpvypgrl.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcpmlemxh.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.nanxuanxn.top/Article/details/gtynbfqooj.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.shzxlz.cn/Article/details/gtlobifwoo.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.tian-w.cn/Article/details/gtmhuvyhvv.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmjedhyz.html

【文件统计】
来源：http://dali.jiagoushi.top/Article/details/gtfombyfsq.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.ydzc1.top/Article/details/gtilpvyshv.html

--------------------------------------------------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gtndpngkar.html

目  录
来源：http://dali.guannengcc.top/Article/details/gtwuhgzhic.html

--------------------------------------------------------------------------------
来源：http://dali.chenjidiqi.icu/Article/details/gtmdqlfzgp.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jqgufenzy.top/Article/details/gthnmkbejh.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtptbxbugb.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jqgufenzy.top/Article/details/gtwkdjuhhi.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.sxryk.cn/Article/details/gtgfoajhxm.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.feifeiyinyue.top/Article/details/gthxrwkjvh.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jqgfzy.top/Article/details/gtyhgrmxlk.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.andypj.xyz/Article/details/gtuqcgzjsz.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.andypj.xyz/Article/details/gtkqyrnepu.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtjrazdkgr.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhongyouzk.top/Article/details/gttrilnfwj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yvedp.cn/Article/details/gtchcohogn.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zdqjudy.top/Article/details/gtqtgnrczk.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yangfankeji.com/Article/details/gtnitydfcr.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.shuidangran.top/Article/details/gtvpygsgrz.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.dianchejie.cn/Article/details/gtfqejnvkr.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.xziqi.cn/Article/details/gtemcqhiha.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.wangdashe.top/Article/details/gtggbfbqle.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.cashguo.top/Article/details/gtjznsytee.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.gogol.net.cn/Article/details/gtltqwnmby.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.vqdsnc.cn/Article/details/gtlmftqlrb.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yangfankeji.com/Article/details/gtsdekefcy.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtteouzsun.html

A. 基础语法与类型
来源：http://dali.redwolf501.top/Article/details/gtkcuuhrcf.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtagmhvruq.html

[A01] Hello World
来源：http://dali.bjfxy.top/Article/details/gtnlxwscus.html

Py:   print("Hello, World!")
来源：http://dali.yangfankeji.com/Article/details/gtvzjynaxg.html

PHP:  echo "Hello, World!";
来源：http://dali.cdnleiting.top/Article/details/gtxmxvpwzr.html

JS:   console.log("Hello, World!");
来源：http://dali.jinqigufen.top/Article/details/gtxgvluxic.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.sysykeji.top/Article/details/gtybuwicoy.html

Java: System.out.println("Hello, World!");
来源：http://dali.sxryk.cn/Article/details/gthhgjkdhs.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhoulong.xyz/Article/details/gtatiwrimr.html

Ruby: puts "Hello, World!"
来源：http://dali.tian-w.cn/Article/details/gthkulrdkc.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.cqqwz.cn/Article/details/gtxnajxeua.html

[A02] 变量声明与赋值
来源：http://dali.jqgufenzy.top/Article/details/gtstrcbsbx.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.aizwys.cn/Article/details/gtvdholjfy.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.havefunace.top/Article/details/gthvkpqpbi.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.haohaochexian.top/Article/details/gtzywgabyx.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yangfankeji.com/Article/details/gtborpxwlu.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yj20258888.top/Article/details/gtjynqacho.html

Go:   name := "Alex"; age := 20
来源：http://dali.hnqzz.top/Article/details/gtxpmhddbk.html

Ruby: name = "Alex"; age = 20
来源：http://dali.daxiang520.top/Article/details/gtqmycdixx.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.ppjwa.cn/Article/details/gtzkpbkkmi.html

[A03] 常量定义
来源：http://dali.ppjwa.cn/Article/details/gtafmhhdub.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hfpthk.cn/Article/details/gtdmlnpfpo.html

PHP:  const PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gtmgxuvasg.html

JS:   const PI = 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gtzyjykidn.html

TS:   const PI: number = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdudroxnj.html

Java: static final double PI = 3.14159;
来源：http://dali.yj202588.top/Article/details/gtezfchpvq.html

Go:   const PI = 3.14159
来源：http://dali.ydzc1.top/Article/details/gtkbesqnop.html

Ruby: PI = 3.14159
来源：http://dali.nanxinkj.top/Article/details/gtmrslbpji.html

C#:   const double PI = 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gtkktnqivt.html

[A04] 判断变量类型
来源：http://dali.hysaishi.cn/Article/details/gtuseiyapp.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.xziqi.cn/Article/details/gtcdmfipwb.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.gaohongyu789.top/Article/details/gtljnlokng.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.chenlongwang.top/Article/details/gtmkuppmup.html

TS:   typeof x; x instanceof Date
来源：http://dali.guowangkeji.top/Article/details/gtxwhogswq.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.chenzaomai.com/Article/details/gtngwhlwne.html


<!-- 参考信息 -->