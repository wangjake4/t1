代发 wailian999

[U39] Py：判断是否在交互环境
来源：http://dali.xziqi.cn/Article/details/gtbxjrmvum.html

sys.stdout.isatty()
来源：http://dali.pengpengdd.cyou/Article/details/gtiinknvuz.html

[U40] Py：打印到标准错误
来源：http://dali.cheryme.top/Article/details/gtrptykhip.html

print("err", file=sys.stderr)
来源：http://dali.tianlin.xyz/Article/details/gtsnboiece.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yj20258888.top/Article/details/gtueumihzy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.daria6918.cn/Article/details/gtofgepioy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.vqdsnc.cn/Article/details/gtvzbajbsl.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.ehwqpu.com/Article/details/gtvjjnkscj.html

[U43] PHP：声明命名空间
来源：http://dali.jqgufenzy.top/Article/details/gtskoxvbaw.html

namespace App\Http;
来源：http://dali.zdqjudy.top/Article/details/gtzsmhuecv.html

[U44] PHP：开启严格类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtvmmjwbpd.html

declare(strict_types=1);
来源：http://dali.mhx1999.top/Article/details/gtccousgnk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zycfv.cn/Article/details/gtbvmdduav.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hysaishi.cn/Article/details/gtshnhjhip.html

[U46] PHP：可空类型
来源：http://dali.jinqigufen.top/Article/details/gtkakwdckw.html

?string $name = null
来源：http://dali.zhaomingkeji.xyz/Article/details/gtomtbfzbx.html

[U47] PHP：联合类型
来源：http://dali.yuxming.cn/Article/details/gtybuoxktq.html

int|string $id
来源：http://dali.yanxiufei.cn/Article/details/gtmvaqwkfu.html

[U48] PHP：纯枚举
来源：http://dali.yvedp.cn/Article/details/gtdxiaoivt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.birdmap.top/Article/details/gtdjgznnxv.html

[U49] PHP：只读属性
来源：http://dali.jinqigfzy.top/Article/details/gtgctdcrvc.html

public readonly string $name
来源：http://dali.guannengcc.top/Article/details/gtfqgvijrm.html

[U50] PHP：构造器属性提升
来源：http://dali.shzxlz.cn/Article/details/gtyfzhncur.html

public function __construct(private int $id) {}
来源：http://dali.cashguo.top/Article/details/gtmtjmlgto.html

[U51] PHP：数组解构
来源：http://dali.ehwqpu.com/Article/details/gtwhixqpsi.html

[$a, $b] = $arr;
来源：http://dali.fzhhl.top/Article/details/gtyymxnene.html

[U52] PHP：箭头函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdvtpwibi.html

$double = fn($x) => $x * 2;
来源：http://dali.zdqjudy.top/Article/details/gtjwhdgxmn.html

[U53] PHP：空合并运算符
来源：http://dali.9152youxi.cn/Article/details/gteoaqbuyp.html

$v = $a ?? $b ?? "default";
来源：http://dali.yj202588.top/Article/details/gtlpdvsgrk.html

[U54] PHP：空安全调用
来源：http://dali.jiagoushi.top/Article/details/gtrojcnvpe.html

$obj?->method()
来源：http://dali.jinqigufen.top/Article/details/gtwjjhxyij.html

[U55] PHP：match 表达式
来源：http://dali.yj20258888.top/Article/details/gtpghiultk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhiwuduotai.top/Article/details/gtluzaojds.html

[U56] PHP：命名参数
来源：http://dali.wangshuangyany.cn/Article/details/gtvrherzoc.html

f(a: 1, b: 2)
来源：http://dali.zhengqikj.top/Article/details/gtndpckeaz.html

[U57] PHP：字符串插值
来源：http://dali.chenlongwang.top/Article/details/gtyyckmtpv.html

"值: {$a}"
来源：http://dali.smart0.xyz/Article/details/gteljfnnoq.html

[U58] PHP：数组三件套
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobmwdvgh.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.shzxlz.cn/Article/details/gtporgalcm.html

[U59] PHP：自定义排序
来源：http://dali.guowangkeji.top/Article/details/gthhcwdmux.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.mhx1999.top/Article/details/gtolcufmfj.html

[U60] PHP：JSON 编解码
来源：http://dali.aibaodan.cn/Article/details/gtsnwffwse.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.fengsongda.top/Article/details/gtjrynraoj.html

[U61] PHP：正则
来源：http://dali.fengsongda.top/Article/details/gtjtdjzcep.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.pycfn.com/Article/details/gtrcragzbu.html

[U62] PHP：日期对象
来源：http://dali.mhx1999.top/Article/details/gtrrnevmvx.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hammf.cn/Article/details/gtfaxolslt.html

[U63] PHP：文件读写
来源：http://dali.jinghuilouyu.cn/Article/details/gtlksgkvrb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hnxiangtu.top/Article/details/gtuigycjyx.html

[U64] PHP：目录遍历
来源：http://dali.zycfv.cn/Article/details/gtsswckaza.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.xziqi.cn/Article/details/gtlziatuvi.html

[U65] PHP：会话
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqnpewphq.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.cashguo.top/Article/details/gtwivcnfua.html

[U66] PHP：设置 Cookie
来源：http://dali.wangdashe.top/Article/details/gtyualzzqt.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.hnxiangtu.top/Article/details/gtwpjmvdds.html

[U67] PHP：处理文件上传
来源：http://dali.jyoumei.cn/Article/details/gtzlmxaton.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zycfv.cn/Article/details/gtqydlkumi.html

[U68] PHP：PDO 连接
来源：http://dali.zhoulong.xyz/Article/details/gtlydxpygb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.haohaochexian.top/Article/details/gtjzjbbesb.html

[U69] PHP：PDO 预处理
来源：http://dali.jinqigufen.top/Article/details/gtxcsgfgjd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.dashuyun.cn/Article/details/gttipqtmux.html

[U70] PHP：PDO 事务
来源：http://dali.vqdsnc.cn/Article/details/gtigwpvrcd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yvedp.cn/Article/details/gtpfnfakmk.html

[U71] PHP：抛出异常
来源：http://dali.wangdashe.top/Article/details/gtmrmprxck.html

throw new RuntimeException("失败", 500);
来源：http://dali.chenjidiqi.icu/Article/details/gtgifkpnix.html

[U72] PHP：写错误日志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtodrjjbmv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.wangdashe.top/Article/details/gtwhnbfvnx.html

[U73] PHP：读取 ini 配置
来源：http://dali.dianchejie.cn/Article/details/gtjxtuztjj.html

parse_ini_file("config.ini", true)
来源：http://dali.xylfe.cn/Article/details/gtsvmdxevt.html

[U74] PHP：读取环境变量
来源：http://dali.jianghu66.top/Article/details/gtcmtrwybm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.daxiang520.top/Article/details/gtocylbgkg.html

[U75] PHP：依赖注入
来源：http://dali.svipenyu.cn/Article/details/gtoqjmghxv.html

composer require psr/container
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlcvogvtc.html

[U76] PHP：简单路由
来源：http://dali.cheryme.top/Article/details/gtcrgtgqdc.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmlyqcqll.html

[U77] PHP：模板渲染
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxlzfdxdb.html

composer require twig/twig
来源：http://dali.jlsjyb.cn/Article/details/gtjollqskm.html

[U78] PHP：单元测试
来源：http://dali.mhx1999.top/Article/details/gtqtjdblvy.html

composer require --dev phpunit/phpunit
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtswofoiub.html

[U79] PHP：静态分析
来源：http://dali.quarkkingdee.top/Article/details/gtoxlugxlc.html

composer require --dev phpstan/phpstan
来源：http://dali.ivvv.top/Article/details/gtkofxlowi.html

[U80] PHP：代码规范修复
来源：http://dali.aibaodan.cn/Article/details/gtzjwcuvzb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.xuanzx.com/Article/details/gtnurhfthq.html

[U81] JS：初始化项目
来源：http://dali.aizwys.cn/Article/details/gtjjlzeptu.html

npm init -y;  npm i express
来源：http://dali.jianghu66.top/Article/details/gtqtsqaorv.html

[U82] JS：package.json 脚本
来源：http://dali.feifeiyinyue.top/Article/details/gtqwiddsew.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.xuanzx.com/Article/details/gtsczemasw.html

[U83] JS：ES Module 导入导出
来源：http://dali.birdmap.top/Article/details/gtuwghqeks.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.nanxuanxn.top/Article/details/gthyyiyezq.html

[U84] JS：CommonJS 写法
来源：http://dali.yj20258.top/Article/details/gtqhorjafd.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhoulong.xyz/Article/details/gtvyolukgd.html

[U85] JS：可选链
来源：http://dali.zycfv.cn/Article/details/gttdhygvfr.html

a?.b?.c
来源：http://dali.316326.xyz/Article/details/gtdrhnmkfb.html

[U86] JS：空值合并
来源：http://dali.aibaodan.cn/Article/details/gtlfrsoasc.html

a ?? b
来源：http://dali.yueranfly.top/Article/details/gtshoxcmpa.html

[U87] JS：解构默认值
来源：http://dali.nwbrower.top/Article/details/gtxtekrjnh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jqgufenzy.top/Article/details/gtzifrhkdk.html

[U88] JS：对象展开合并
来源：http://dali.nanxuanxn.top/Article/details/gtqfutkzci.html

{ ...a, ...b }
来源：http://dali.dianchejie.cn/Article/details/gtfcnodqyt.html

[U89] JS：数组去重
来源：http://dali.chenjidiqi.icu/Article/details/gtpznzrpkr.html

[...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gtchnvvios.html

[U90] JS：数字数组排序
来源：http://dali.snrcjt.cn/Article/details/gthgeariyq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gtnedfelpv.html

[U91] JS：对象键值遍历
来源：http://dali.ppjwa.cn/Article/details/gtawmugtff.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.bjfxy.top/Article/details/gticgicntv.html

[U92] JS：深拷贝
来源：http://dali.mhx1999.top/Article/details/gtucawcjew.html

structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gtnhktkezg.html

[U93] JS：模板字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbynidwyy.html

`共 ${n} 条`
来源：http://dali.ybcxt.top/Article/details/gtcevssett.html

[U94] JS：箭头函数
来源：http://dali.shuidangran.top/Article/details/gtuqabsazp.html

const double = x => x * 2;
来源：http://dali.bjfxy.top/Article/details/gtjcflykdn.html

[U95] JS：Promise 包装
来源：http://dali.yvedp.cn/Article/details/gtyoqervjn.html

new Promise((resolve, reject) => {})
来源：http://dali.hnqzz.top/Article/details/gtetqjyarj.html

[U96] JS：async/await 与异常
来源：http://dali.sweek.top/Article/details/gtraxfeqyf.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.kuanghao11.cn/Article/details/gtvszimizd.html

[U97] JS：并发请求
来源：http://dali.vqdsnc.cn/Article/details/gtfjxxnluf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgfzy.top/Article/details/gthnqxdleb.html

[U98] JS：fetch 带 JSON
来源：http://dali.sweek.top/Article/details/gtlgqdiqqe.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxgpkocek.html

[U99] JS：事件监听
来源：http://dali.jiagoushi.top/Article/details/gtpazmmfol.html

el.addEventListener("click", e => {})
来源：http://dali.zhiwuduotai.top/Article/details/gtgelvchbm.html

[U100] JS：DOM 查询
来源：http://dali.yonumen.top/Article/details/gtclmnvjss.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gtzyrmdgop.html

[U101] JS：classList 操作
来源：http://dali.ppjwa.cn/Article/details/gtxhttkyyj.html

el.classList.toggle("active")
来源：http://dali.sufxvd.cn/Article/details/gtiswldyfa.html

[U102] JS：本地存储
来源：http://dali.vqdsnc.cn/Article/details/gtdopjzqzp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.sysykeji.top/Article/details/gthjocwzmb.html

[U103] JS：定时器
来源：http://dali.redwolf501.top/Article/details/gtcjktrchw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yongpay.top/Article/details/gtldahooqo.html

[U104] JS：防抖
来源：http://dali.0kj1m.cn/Article/details/gtzrgcjokd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gtumlrsdat.html

[U105] JS：节流
来源：http://dali.sxryk.cn/Article/details/gtwmkczkhj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.birdmap.top/Article/details/gtosnsyjhy.html

[U106] JS：日期格式化
来源：http://dali.jinqigfzy.top/Article/details/gtzclbzmzn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.nanxuanxn.top/Article/details/gtbzmrhidi.html

[U107] JS：数字千分位
来源：http://dali.shzxlz.cn/Article/details/gthvhxiuzv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.tian-w.cn/Article/details/gtehtcdopg.html

[U108] JS：随机整数
来源：http://dali.sxryk.cn/Article/details/gtpjgdskhl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.mhx1999.top/Article/details/gtxbsuhszx.html

[U109] JS：数组分组
来源：http://dali.jyoumei.cn/Article/details/gtktowehxz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hfpthk.cn/Article/details/gtigjxnvor.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gttviewcnz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.tianlin.xyz/Article/details/gtcmoahkrm.html

[U111] JS：对象转 Map
来源：http://dali.cucudq.cn/Article/details/gtwqthxopw.html

new Map(Object.entries(obj))
来源：http://dali.cheryme.top/Article/details/gtzosemgaf.html

[U112] JS：字符串补位
来源：http://dali.cdnleiting.top/Article/details/gtgldpvgoo.html

"7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gtxtirzkhs.html

[U113] JS：正则替换全部
来源：http://dali.chenlongwang.top/Article/details/gtiphmtnzj.html

s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtgapbfrmb.html

[U114] JS：JSON 深比较
来源：http://dali.snrcjt.cn/Article/details/gtanurwuxo.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangdashe.top/Article/details/gtkamvifij.html

[U115] JS：生成 UUID
来源：http://dali.jinqigfzy.top/Article/details/gtdgodcild.html

crypto.randomUUID()
来源：http://dali.sweek.top/Article/details/gtjyoxfgck.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zycfv.cn/Article/details/gtwnclkjlr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xuanzx.com/Article/details/gtlzanwchp.html

[U117] JS：单元测试
来源：http://dali.sysykeji.top/Article/details/gtqykapcri.html

npm i -D vitest;  npx vitest
来源：http://dali.0kj1m.cn/Article/details/gtcgouusto.html

[U118] JS：开发服务器
来源：http://dali.gotoacloud.top/Article/details/gtmmtccuja.html

npm i -D vite;  npx vite
来源：http://dali.mhx1999.top/Article/details/gtfamufbpn.html

[U119] JS：生产构建
来源：http://dali.kuanghao11.cn/Article/details/gtsuzzdbjl.html

npx vite build
来源：http://dali.jinqigufen.top/Article/details/gtzchqhtzb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jyoumei.cn/Article/details/gttzstwbbr.html

import.meta.env.VITE_API_URL
来源：http://dali.haohaochexian.top/Article/details/gtvygeiryz.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtqsktcayq.html

统计汇总
来源：http://dali.pengpengdd.cyou/Article/details/gtooikrxpy.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtvdbcskdd.html

按语言统计（条）：
来源：http://dali.xziqi.cn/Article/details/gttlqkcyai.html

Python ......... 252
来源：http://dali.pengpengdd.cyou/Article/details/gtdlskgdxa.html

PHP ............ 252
来源：http://dali.jianghu66.top/Article/details/gtvarvryeg.html

JavaScript ..... 252
来源：http://dali.chenzaomai.com/Article/details/gtkqohslok.html

TypeScript ..... 212
来源：http://dali.zycfv.cn/Article/details/gtjhzhslpw.html

Java ........... 212
来源：http://dali.ppjwa.cn/Article/details/gtyylttkyc.html

Go ............. 212
来源：http://dali.xuanzx.com/Article/details/gtpqbrshaw.html

Ruby ........... 212
来源：http://dali.zycfv.cn/Article/details/gtdzirunca.html

C# ............. 212
来源：http://dali.tianlin.xyz/Article/details/gtmpqxckiu.html

C .............. 30
来源：http://dali.hfpthk.cn/Article/details/gtkmjygnxn.html

C++ ............ 30
来源：http://dali.nanxinkj.top/Article/details/gtvtclyqmi.html

SQL ............ 90
来源：http://dali.shuidangran.top/Article/details/gtpebmtkzm.html

Bash ........... 80
来源：http://dali.yongpay.top/Article/details/gtbndsmkpx.html

Kotlin ......... 15
来源：http://dali.gogol.net.cn/Article/details/gtjkymzmpg.html

Swift .......... 15
来源：http://dali.sufxvd.cn/Article/details/gtyjhtvvlk.html

Lua ............ 10
来源：http://dali.0kj1m.cn/Article/details/gtrlcwxgbq.html

Perl ........... 10
来源：http://dali.yj20258.top/Article/details/gtwcecuahk.html

Scala .......... 10
来源：http://dali.ydzc1.top/Article/details/gtkwrearot.html

------------------------------------
来源：http://dali.fzhhl.top/Article/details/gtbjgxepgc.html

合计 ........... 2106 条
来源：http://dali.dashuyun.cn/Article/details/gtthfjwjmq.html

按章节统计：
来源：http://dali.zhongyouzk.top/Article/details/gtvsmdtetc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.gogol.net.cn/Article/details/gtkzvgofsj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.chenjidiqi.icu/Article/details/gtbnwyqgco.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.aibaodan.cn/Article/details/gtidluuxsx.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jinqigfzy.top/Article/details/gtsetlwddh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.pycfn.com/Article/details/gtazpftbcg.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yuanzhike.top/Article/details/gtxlqiuspa.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hammf.cn/Article/details/gtaorjohdi.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.xuanzx.com/Article/details/gtzqfnzdui.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gtxpaxpnpx.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jqgufenzy.top/Article/details/gtxnmpzhey.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.dashuyun.cn/Article/details/gtnrjnmfnx.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xziqi.cn/Article/details/gtnndxkdwc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.cucudq.cn/Article/details/gtuixxydea.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zycfv.cn/Article/details/gtpblqarrw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yuanzhike.top/Article/details/gtghzernba.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangkeji.top/Article/details/gttibhybvu.html

Q SQL 专题                              90
来源：http://dali.pycfn.com/Article/details/gtqmpwgooo.html

R Bash 专题                             80
来源：http://dali.daria6918.cn/Article/details/gtyxhkfsry.html

S C / C++ 专题                          60
来源：http://dali.yuxming.cn/Article/details/gtblxnuisa.html

T 其他语言补充                          60
来源：http://dali.sxryk.cn/Article/details/gtleclkfdv.html

U 高频实用片段                         120
来源：http://dali.fengsongda.top/Article/details/gtyxwhmkqm.html

------------------------------------
来源：http://dali.dashuyun.cn/Article/details/gtfcbiteqw.html

合计                                  2106 条
来源：http://dali.cheryme.top/Article/details/gtpeyfdaeg.html

--------------------------------------------------------------------------------
来源：http://dali.zhengqikj.top/Article/details/gtbzjdekqj.html

使用提醒
来源：http://dali.hammf.cn/Article/details/gttvmvyvzf.html

--------------------------------------------------------------------------------
来源：http://dali.cheryme.top/Article/details/gtqnfgwhuj.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.tian-w.cn/Article/details/gtwocdrbza.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.316326.xyz/Article/details/gtftcakusz.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yonumen.top/Article/details/gtmuspbibi.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.tian-w.cn/Article/details/gtglrshlup.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yj202588.top/Article/details/gttocgizhq.html

—— 文件结束 ——
来源：http://dali.zhengqikj.top/Article/details/gteurvjqvl.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtxdpzfoei.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhongyouzk.top/Article/details/gtygnnsrrh.html

Common Programming Examples Cheat Book
来源：http://dali.jyoumei.cn/Article/details/gtnxuufyea.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtbblpznkg.html

【收录内容】
来源：http://dali.tianlin.xyz/Article/details/gtuwoaogyz.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zdqjudy.top/Article/details/gthocipcoq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.sxryk.cn/Article/details/gtliifenvr.html

SQL · Bash · C · C++
来源：http://dali.shuidangran.top/Article/details/gthlxrowfd.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.dashuyun.cn/Article/details/gtmlyscqrr.html

【使用说明】
来源：http://dali.jyoumei.cn/Article/details/gtefjtxoop.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.vqdsnc.cn/Article/details/gtzmierpzg.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.wangshuangyany.cn/Article/details/gtfvnudujp.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.smart0.xyz/Article/details/gtrpgyhzow.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.0kj1m.cn/Article/details/gtntettgmq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yuxming.cn/Article/details/gtqqeskqzj.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.c1oappe.top/Article/details/gtjsvetvcs.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jlsjyb.cn/Article/details/gtvybrelkz.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.iojbl.cn/Article/details/gtqzccthjw.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.sxryk.cn/Article/details/gtsedefcfv.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yonumen.top/Article/details/gtohkylawu.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.smart0.xyz/Article/details/gtnkwtckdn.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.gzhubu.top/Article/details/gtohkhovkf.html

【文件统计】
来源：http://dali.tianlin.xyz/Article/details/gtmclaeipn.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.dashuyun.cn/Article/details/gttkdoxwza.html

--------------------------------------------------------------------------------
来源：http://dali.guannengcc.top/Article/details/gtozgdlgsq.html

目  录
来源：http://dali.ppjwa.cn/Article/details/gtffegbrdd.html

--------------------------------------------------------------------------------
来源：http://dali.zhengqikj.top/Article/details/gteuxtczkl.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.xziqi.cn/Article/details/gtkjbhlqxk.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.chenlongwang.top/Article/details/gtksqwqhud.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.nanxinkj.top/Article/details/gtytekkwzy.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtkuxmbtqt.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.fengsongda.top/Article/details/gtahhzdlmh.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.xinyue.icu/Article/details/gtupwysdmp.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zdqjudy.top/Article/details/gtapbwiqim.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yongpay.top/Article/details/gtwkoneutg.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yj20258888.top/Article/details/gthnjmjryx.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.316326.xyz/Article/details/gtgyrcvdcz.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jqgfzy.top/Article/details/gtrlxjlwug.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yongpay.top/Article/details/gtukcyfqhx.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.cashguo.top/Article/details/gtoupksytj.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yuanzhike.top/Article/details/gtbcypnaar.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtfsgloebf.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yonumen.top/Article/details/gtjgthenyx.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yuxming.cn/Article/details/gtjvylsvvb.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.cashguo.top/Article/details/gtrmvxkamw.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.shuidangran.top/Article/details/gthhjjvcnw.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.daxiang520.top/Article/details/gthuughoxr.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinqigufen.top/Article/details/gtyqxzfqzx.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoslbdvpz.html

A. 基础语法与类型
来源：http://dali.xziqi.cn/Article/details/gtbjdntrvy.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtmafrirzg.html

[A01] Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqgjhjest.html

Py:   print("Hello, World!")
来源：http://dali.jqgfzy.top/Article/details/gtnedxzagg.html

PHP:  echo "Hello, World!";
来源：http://dali.tianlin.xyz/Article/details/gthfwvvebg.html

JS:   console.log("Hello, World!");
来源：http://dali.tian-w.cn/Article/details/gtfikswjvc.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.andypj.xyz/Article/details/gtzlplfoxw.html

Java: System.out.println("Hello, World!");
来源：http://dali.sysykeji.top/Article/details/gthfnqbruo.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.sweek.top/Article/details/gtyfjphmaa.html

Ruby: puts "Hello, World!"
来源：http://dali.meibo888.top/Article/details/gtgpjxljnr.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.pycfn.com/Article/details/gtgskscija.html

[A02] 变量声明与赋值
来源：http://dali.andypj.xyz/Article/details/gtagolcqzg.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.havefunace.top/Article/details/gtyphjhrvk.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hammf.cn/Article/details/gtyxpigzch.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.xinyue.icu/Article/details/gtnvumctni.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jiagoushi.top/Article/details/gtgmxmnbqb.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhiwuduotai.top/Article/details/gtirosarhd.html

Go:   name := "Alex"; age := 20
来源：http://dali.tian-w.cn/Article/details/gtqklzddxe.html

Ruby: name = "Alex"; age = 20
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqtyjblp.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.snrcjt.cn/Article/details/gtddmrhnzn.html

[A03] 常量定义
来源：http://dali.gotoacloud.top/Article/details/gtgrzjakki.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gtrtavlwwl.html

PHP:  const PI = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gtmqdgemel.html

JS:   const PI = 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gtrumjakjx.html

TS:   const PI: number = 3.14159;
来源：http://dali.yj202588.top/Article/details/gtknblkiku.html

Java: static final double PI = 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gtwhodilli.html

Go:   const PI = 3.14159
来源：http://dali.pengpengdd.cyou/Article/details/gtbogmqskd.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gtuohoypyx.html

C#:   const double PI = 3.14159;
来源：http://dali.316326.xyz/Article/details/gtmdzlkbjv.html

[A04] 判断变量类型
来源：http://dali.zhixingplan.top/Article/details/gtzlcvutsu.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.tianlin.xyz/Article/details/gtqvluodlg.html


<!-- 参考信息 -->