代发 wailian999

[U31] Py：单测
来源：http://dali.svipenyu.cn/Article/details/gt2yabprtjd.html

python -m pytest -q
来源：http://dali.iojbl.cn/Article/details/gt2tyrlauup.html

[U32] Py：代码格式化
来源：http://dali.tanke756.top/Article/details/gt2vlyknrki.html

ruff format . && ruff check --fix .
来源：http://dali.ehwqpu.com/Article/details/gt2nxnpjzht.html

[U33] Py：打包发布
来源：http://dali.redwolf501.top/Article/details/gt2nrlgjtpr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.guannengcc.top/Article/details/gt2kxonezqk.html

[U34] Py：判断编码
来源：http://dali.aibaodan.cn/Article/details/gt2clrbuvwz.html

chardet.detect(raw)
来源：http://dali.yanxiufei.cn/Article/details/gt2huzvwybp.html

[U35] Py：发送邮件
来源：http://dali.guannengcc.top/Article/details/gt2khibulrk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.ydzc1.top/Article/details/gt2aoablomo.html

[U36] Py：定时任务
来源：http://dali.hnxiangtu.top/Article/details/gt2jufzwvdc.html

schedule.every(10).minutes.do(job)
来源：http://dali.xylfe.cn/Article/details/gt2neuculic.html

[U37] Py：读写 Excel
来源：http://dali.hnxiangtu.top/Article/details/gt2ytzkexpp.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhiwuduotai.top/Article/details/gt2iewpmqib.html

[U38] Py：获取脚本所在目录
来源：http://dali.hnqzz.top/Article/details/gt2viqlpcfn.html

Path(__file__).resolve().parent
来源：http://dali.316326.xyz/Article/details/gt2oafollrb.html

[U39] Py：判断是否在交互环境
来源：http://dali.nanxinkj.top/Article/details/gt2rlqnuhue.html

sys.stdout.isatty()
来源：http://dali.nwbrower.top/Article/details/gt2fffjufpw.html

[U40] Py：打印到标准错误
来源：http://dali.yj202588.top/Article/details/gt2ughepzqc.html

print("err", file=sys.stderr)
来源：http://dali.nanxuanxn.top/Article/details/gt2lsyqwheu.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vlfcaoap.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uyhkwwct.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yuxming.cn/Article/details/gt2vzosdlrv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xuetiantiany.cn/Article/details/gt2mrpifbti.html

[U43] PHP：声明命名空间
来源：http://dali.cqqwz.cn/Article/details/gt2nivlfjmi.html

namespace App\Http;
来源：http://dali.yj20258888.top/Article/details/gt2vyygcbqu.html

[U44] PHP：开启严格类型
来源：http://dali.daxiang520.top/Article/details/gt2jlmkfdtd.html

declare(strict_types=1);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ortwobtb.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zycfv.cn/Article/details/gt2llupkxhz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.meibo888.top/Article/details/gt2moxheqwb.html

[U46] PHP：可空类型
来源：http://dali.nanxuanxn.top/Article/details/gt2yytodzle.html

?string $name = null
来源：http://dali.yj20258.top/Article/details/gt2jnbrxlyj.html

[U47] PHP：联合类型
来源：http://dali.hnxiangtu.top/Article/details/gt2tzvsnlsw.html

int|string $id
来源：http://dali.xinyue.icu/Article/details/gt2oeezmyzg.html

[U48] PHP：纯枚举
来源：http://dali.snrcjt.cn/Article/details/gt2vpuhactg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hnqzz.top/Article/details/gt2fkgkqnzd.html

[U49] PHP：只读属性
来源：http://dali.chenlongwang.top/Article/details/gt2aoobcuuv.html

public readonly string $name
来源：http://dali.jqgufenzy.top/Article/details/gt2dpmzmtvh.html

[U50] PHP：构造器属性提升
来源：http://dali.gotoacloud.top/Article/details/gt2llxlqtan.html

public function __construct(private int $id) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2gnjdnalz.html

[U51] PHP：数组解构
来源：http://dali.tian-w.cn/Article/details/gt2jwgihgof.html

[$a, $b] = $arr;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lvygfqdd.html

[U52] PHP：箭头函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2wiscmtqp.html

$double = fn($x) => $x * 2;
来源：http://dali.cheryme.top/Article/details/gt2vmhufmss.html

[U53] PHP：空合并运算符
来源：http://dali.xylfe.cn/Article/details/gt2sjrfqnpg.html

$v = $a ?? $b ?? "default";
来源：http://dali.xylfe.cn/Article/details/gt2mzkdknxu.html

[U54] PHP：空安全调用
来源：http://dali.xziqi.cn/Article/details/gt2dzvzsble.html

$obj?->method()
来源：http://dali.wangshuangyany.cn/Article/details/gt2lshbsogt.html

[U55] PHP：match 表达式
来源：http://dali.yueranfly.top/Article/details/gt2puppywfk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xylfe.cn/Article/details/gt2wstguasp.html

[U56] PHP：命名参数
来源：http://dali.haohaochexian.top/Article/details/gt2spgfhsfx.html

f(a: 1, b: 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2vlfftqvc.html

[U57] PHP：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gt2irydwkzo.html

"值: {$a}"
来源：http://dali.jianghu66.top/Article/details/gt2ywfpewlu.html

[U58] PHP：数组三件套
来源：http://dali.aibaodan.cn/Article/details/gt2mefcxqnp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.dianchejie.cn/Article/details/gt2pfgcejzl.html

[U59] PHP：自定义排序
来源：http://dali.gaohongyu789.top/Article/details/gt2yazntedq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenlongwang.top/Article/details/gt2frdjcbnd.html

[U60] PHP：JSON 编解码
来源：http://dali.pengpengdd.cyou/Article/details/gt2imlncktl.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.nwbrower.top/Article/details/gt2oeejroiw.html

[U61] PHP：正则
来源：http://dali.hammf.cn/Article/details/gt2kexcldqx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2fjwdbnpt.html

[U62] PHP：日期对象
来源：http://dali.c1oappe.top/Article/details/gt2opldasrx.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.pengpengdd.cyou/Article/details/gt2sbrwfjwq.html

[U63] PHP：文件读写
来源：http://dali.yonumen.top/Article/details/gt2njdbxrod.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hywenlv.cn/Article/details/gt2zweahejm.html

[U64] PHP：目录遍历
来源：http://dali.guannengcc.top/Article/details/gt2armergta.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.redwolf501.top/Article/details/gt2hvjkhccn.html

[U65] PHP：会话
来源：http://dali.shzxlz.cn/Article/details/gt2zekjdglz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.cucudq.cn/Article/details/gt2nrychdkl.html

[U66] PHP：设置 Cookie
来源：http://dali.aibaodan.cn/Article/details/gt2weaniikx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.guowangkeji.top/Article/details/gt2vbtzxkjo.html

[U67] PHP：处理文件上传
来源：http://dali.zhiwuduotai.top/Article/details/gt2vllpljmp.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.chenzaomai.com/Article/details/gt2eknwszlr.html

[U68] PHP：PDO 连接
来源：http://dali.xinyue.icu/Article/details/gt2oyyrrpen.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.ehwqpu.com/Article/details/gt2iecrdzda.html

[U69] PHP：PDO 预处理
来源：http://dali.meibo888.top/Article/details/gt2lamqxkhc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.quarkkingdee.top/Article/details/gt2hljktxdj.html

[U70] PHP：PDO 事务
来源：http://dali.daria6918.cn/Article/details/gt2ddbfjnfb.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hysaishi.cn/Article/details/gt2cdlpdelu.html

[U71] PHP：抛出异常
来源：http://dali.fzhhl.top/Article/details/gt2kndlgffu.html

throw new RuntimeException("失败", 500);
来源：http://dali.guannengcc.top/Article/details/gt2jphzqwhl.html

[U72] PHP：写错误日志
来源：http://dali.tanke756.top/Article/details/gt2aqjgnyby.html

error_log("失败: " . $e->getMessage());
来源：http://dali.shanyushiyangtech.top/Article/details/gt2njusvlck.html

[U73] PHP：读取 ini 配置
来源：http://dali.hongshengwenyu.top/Article/details/gt2gzhzsily.html

parse_ini_file("config.ini", true)
来源：http://dali.wangdashe.top/Article/details/gt2otrnhtmt.html

[U74] PHP：读取环境变量
来源：http://dali.kuanghao11.cn/Article/details/gt2fxidfpgz.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jinqigfzy.top/Article/details/gt2vjwhztzu.html

[U75] PHP：依赖注入
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bnnxxmbs.html

composer require psr/container
来源：http://dali.smart0.xyz/Article/details/gt2kytlgqsl.html

[U76] PHP：简单路由
来源：http://dali.jinqigfzy.top/Article/details/gt2wgvtuycd.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.smart0.xyz/Article/details/gt2yrxdmgel.html

[U77] PHP：模板渲染
来源：http://dali.zhoulong.xyz/Article/details/gt2mvxcgqzj.html

composer require twig/twig
来源：http://dali.fzhhl.top/Article/details/gt2ovitqfhe.html

[U78] PHP：单元测试
来源：http://dali.yongpay.top/Article/details/gt2alwiswro.html

composer require --dev phpunit/phpunit
来源：http://dali.hysaishi.cn/Article/details/gt2gkwfxigm.html

[U79] PHP：静态分析
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cskxmwyd.html

composer require --dev phpstan/phpstan
来源：http://dali.shangyingyoupin.top/Article/details/gt2zqvdhhik.html

[U80] PHP：代码规范修复
来源：http://dali.aibaodan.cn/Article/details/gt2lqorilyy.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.hnxiangtu.top/Article/details/gt2xnobbooy.html

[U81] JS：初始化项目
来源：http://dali.tianlin.xyz/Article/details/gt2qrjsjcfm.html

npm init -y;  npm i express
来源：http://dali.pengpengdd.cyou/Article/details/gt2hvbmblwi.html

[U82] JS：package.json 脚本
来源：http://dali.gzhubu.top/Article/details/gt2fltwpmwa.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yonumen.top/Article/details/gt2huzafodj.html

[U83] JS：ES Module 导入导出
来源：http://dali.ppjwa.cn/Article/details/gt2axvgqckv.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.mhx1999.top/Article/details/gt2pgkxzafz.html

[U84] JS：CommonJS 写法
来源：http://dali.chenjidiqi.icu/Article/details/gt2pqypkbza.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hywenlv.cn/Article/details/gt2vboimqkj.html

[U85] JS：可选链
来源：http://dali.fzhhl.top/Article/details/gt2ujznzkis.html

a?.b?.c
来源：http://dali.hammf.cn/Article/details/gt2boploxfu.html

[U86] JS：空值合并
来源：http://dali.cucudq.cn/Article/details/gt2ucpywnyz.html

a ?? b
来源：http://dali.guowangkeji.top/Article/details/gt2ncjodqbe.html

[U87] JS：解构默认值
来源：http://dali.nwbrower.top/Article/details/gt2njirhlqq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jlsjyb.cn/Article/details/gt2psifgksi.html

[U88] JS：对象展开合并
来源：http://dali.pycfn.com/Article/details/gt2svhmfean.html

{ ...a, ...b }
来源：http://dali.hysaishi.cn/Article/details/gt2ixvlmbdo.html

[U89] JS：数组去重
来源：http://dali.gotoacloud.top/Article/details/gt2akifcbme.html

[...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gt2gfsaetal.html

[U90] JS：数字数组排序
来源：http://dali.sufxvd.cn/Article/details/gt2dsvualbg.html

[...arr].sort((a, b) => a - b)
来源：http://dali.xinyue.icu/Article/details/gt2htewaqhc.html

[U91] JS：对象键值遍历
来源：http://dali.xuanzx.com/Article/details/gt2nymzlcon.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.hfpthk.cn/Article/details/gt2weiqayfr.html

[U92] JS：深拷贝
来源：http://dali.svipenyu.cn/Article/details/gt2lyslbzcv.html

structuredClone(obj)
来源：http://dali.fengsongda.top/Article/details/gt2yiqavzlq.html

[U93] JS：模板字符串
来源：http://dali.yongpay.top/Article/details/gt2zyvtgmlh.html

`共 ${n} 条`
来源：http://dali.jyoumei.cn/Article/details/gt2vhliulit.html

[U94] JS：箭头函数
来源：http://dali.0kj1m.cn/Article/details/gt2qhikwbif.html

const double = x => x * 2;
来源：http://dali.pengpengdd.cyou/Article/details/gt2agrwgfro.html

[U95] JS：Promise 包装
来源：http://dali.iojbl.cn/Article/details/gt2sopizokn.html

new Promise((resolve, reject) => {})
来源：http://dali.tianlin.xyz/Article/details/gt2oblujqjr.html

[U96] JS：async/await 与异常
来源：http://dali.smart0.xyz/Article/details/gt2tvhludpn.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gt2irgshdgm.html

[U97] JS：并发请求
来源：http://dali.yj20258888.top/Article/details/gt2qdymprdl.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.snrcjt.cn/Article/details/gt2wvawqcxm.html

[U98] JS：fetch 带 JSON
来源：http://dali.andypj.xyz/Article/details/gt2shsmmagy.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.cdnleiting.top/Article/details/gt2yzhnggqf.html

[U99] JS：事件监听
来源：http://dali.chenzaomai.com/Article/details/gt2ascuwbva.html

el.addEventListener("click", e => {})
来源：http://dali.yangfankeji.com/Article/details/gt2dutjlnko.html

[U100] JS：DOM 查询
来源：http://dali.nwbrower.top/Article/details/gt2hphtipmy.html

document.querySelector(".item")
来源：http://dali.kuanghao11.cn/Article/details/gt2tdoaflpr.html

[U101] JS：classList 操作
来源：http://dali.guannengcc.top/Article/details/gt2oflkwzff.html

el.classList.toggle("active")
来源：http://dali.snrcjt.cn/Article/details/gt2kytouydn.html

[U102] JS：本地存储
来源：http://dali.shuidangran.top/Article/details/gt2keeijmrb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.dashuyun.cn/Article/details/gt2skqahenk.html

[U103] JS：定时器
来源：http://dali.yangfankeji.com/Article/details/gt2kmhpbmnc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.sufxvd.cn/Article/details/gt2epcnpeul.html

[U104] JS：防抖
来源：http://dali.sysykeji.top/Article/details/gt2hfcfxlod.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hysaishi.cn/Article/details/gt2etvyifrf.html

[U105] JS：节流
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fspjpqls.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.sxryk.cn/Article/details/gt2jfdiamon.html

[U106] JS：日期格式化
来源：http://dali.hammf.cn/Article/details/gt2dxyarqag.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.dashuyun.cn/Article/details/gt2wekdfpdz.html

[U107] JS：数字千分位
来源：http://dali.jiagoushi.top/Article/details/gt2mmptspln.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.dashuyun.cn/Article/details/gt2lzbgkxcv.html

[U108] JS：随机整数
来源：http://dali.xuanzx.com/Article/details/gt2drcswrmw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xziqi.cn/Article/details/gt2vttmzpjy.html

[U109] JS：数组分组
来源：http://dali.sxryk.cn/Article/details/gt2ownqbsmf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jqgfzy.top/Article/details/gt2tvngowgr.html

[U110] JS：数组分块
来源：http://dali.sufxvd.cn/Article/details/gt2wkkhtjpa.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yonumen.top/Article/details/gt2gepxllrg.html

[U111] JS：对象转 Map
来源：http://dali.chenlongwang.top/Article/details/gt2yqefmqmy.html

new Map(Object.entries(obj))
来源：http://dali.pengpengdd.cyou/Article/details/gt2hhosnpiw.html

[U112] JS：字符串补位
来源：http://dali.nanxinkj.top/Article/details/gt2gvaovszw.html

"7".padStart(3, "0")
来源：http://dali.sysykeji.top/Article/details/gt2ygdiwces.html

[U113] JS：正则替换全部
来源：http://dali.yuxming.cn/Article/details/gt2lynqzkse.html

s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gt2caxzfiab.html

[U114] JS：JSON 深比较
来源：http://dali.hywenlv.cn/Article/details/gt2xdpnguqw.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.iojbl.cn/Article/details/gt2ajexnuuy.html

[U115] JS：生成 UUID
来源：http://dali.zhixingplan.top/Article/details/gt2dgulixoc.html

crypto.randomUUID()
来源：http://dali.zhoulong.xyz/Article/details/gt2wqqibgjo.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.sufxvd.cn/Article/details/gt2bcfvcnud.html

/** @param {string} name */ function f(name) {}
来源：http://dali.meibo888.top/Article/details/gt2mavxbzej.html

[U117] JS：单元测试
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wjijzzye.html

npm i -D vitest;  npx vitest
来源：http://dali.havefunace.top/Article/details/gt2ygfpxnaz.html

[U118] JS：开发服务器
来源：http://dali.cashguo.top/Article/details/gt2dhysbibx.html

npm i -D vite;  npx vite
来源：http://dali.jqgfzy.top/Article/details/gt2jmeywaxe.html

[U119] JS：生产构建
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sxvrblkd.html

npx vite build
来源：http://dali.feifeiyinyue.top/Article/details/gt2jfrlbziq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.dianchejie.cn/Article/details/gt2pykgsnez.html

import.meta.env.VITE_API_URL
来源：http://dali.hfpthk.cn/Article/details/gt2yszotwut.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2obruuzal.html

统计汇总
来源：http://dali.shzxlz.cn/Article/details/gt2iqrgfmey.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2nxwttthg.html

按语言统计（条）：
来源：http://dali.zycfv.cn/Article/details/gt2fqlpujiz.html

Python ......... 252
来源：http://dali.xziqi.cn/Article/details/gt2bwkazgsp.html

PHP ............ 252
来源：http://dali.yongpay.top/Article/details/gt2cgsblgva.html

JavaScript ..... 252
来源：http://dali.cqqwz.cn/Article/details/gt2rgosuqoj.html

TypeScript ..... 212
来源：http://dali.zhixingplan.top/Article/details/gt2lqrchcov.html

Java ........... 212
来源：http://dali.yj20258.top/Article/details/gt2friffauy.html

Go ............. 212
来源：http://dali.tianlin.xyz/Article/details/gt2umqxtuay.html

Ruby ........... 212
来源：http://dali.hongshengwenyu.top/Article/details/gt2zfxufkdk.html

C# ............. 212
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kzpjhnka.html

C .............. 30
来源：http://dali.cqqwz.cn/Article/details/gt2opbwzkpy.html

C++ ............ 30
来源：http://dali.chenzaomai.com/Article/details/gt2syyhskmn.html

SQL ............ 90
来源：http://dali.sysykeji.top/Article/details/gt2znzzpcli.html

Bash ........... 80
来源：http://dali.zycfv.cn/Article/details/gt2bxlnaqmi.html

Kotlin ......... 15
来源：http://dali.0kj1m.cn/Article/details/gt2judseqer.html

Swift .......... 15
来源：http://dali.xuetiantiany.cn/Article/details/gt2wozyeiap.html

Lua ............ 10
来源：http://dali.jinqigufen.top/Article/details/gt2aevlasci.html

Perl ........... 10
来源：http://dali.xylfe.cn/Article/details/gt2ekcugcpi.html

Scala .......... 10
来源：http://dali.dianchejie.cn/Article/details/gt2uayvdngr.html

------------------------------------
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jomdvdcf.html

合计 ........... 2106 条
来源：http://dali.chenjidiqi.icu/Article/details/gt2twevjmmj.html

按章节统计：
来源：http://dali.hnqzz.top/Article/details/gt2gdgijzrx.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.9152youxi.cn/Article/details/gt2tennrunu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shangyingyoupin.top/Article/details/gt2xrcllrsa.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hammf.cn/Article/details/gt2hydrlvxf.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yvedp.cn/Article/details/gt2chipcldw.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.cqqwz.cn/Article/details/gt2kgrmoplp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.sxryk.cn/Article/details/gt2kivvkccw.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.feifeiyinyue.top/Article/details/gt2utqbdppb.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.tianlin.xyz/Article/details/gt2awcyogkv.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.tanke756.top/Article/details/gt2toakkefd.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.nanxuanxn.top/Article/details/gt2hsnttqhh.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.redwolf501.top/Article/details/gt2auvmcmpa.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.aibaodan.cn/Article/details/gt2pdgevsgs.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhixingplan.top/Article/details/gt2divjhyln.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.gogol.net.cn/Article/details/gt2rsltidmc.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ivvv.top/Article/details/gt2frwjbkbm.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.tian-w.cn/Article/details/gt2vbmcldme.html

Q SQL 专题                              90
来源：http://dali.redwolf501.top/Article/details/gt2pecdbkqz.html

R Bash 专题                             80
来源：http://dali.xinyue.icu/Article/details/gt2pmhgjmep.html

S C / C++ 专题                          60
来源：http://dali.cheryme.top/Article/details/gt2vnenepcx.html

T 其他语言补充                          60
来源：http://dali.bjfxy.top/Article/details/gt2qqpeopon.html

U 高频实用片段                         120
来源：http://dali.ehwqpu.com/Article/details/gt2uljtyuzg.html

------------------------------------
来源：http://dali.iojbl.cn/Article/details/gt2wzsgwkbq.html

合计                                  2106 条
来源：http://dali.jinqigufen.top/Article/details/gt2mozsdcfj.html

--------------------------------------------------------------------------------
来源：http://dali.meibo888.top/Article/details/gt2xitltqed.html

使用提醒
来源：http://dali.gzhubu.top/Article/details/gt2fqakytsj.html

--------------------------------------------------------------------------------
来源：http://dali.fengsongda.top/Article/details/gt2vxogynlq.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.daria6918.cn/Article/details/gt2vkdyfxop.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hysaishi.cn/Article/details/gt2ykmpkbjo.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.daria6918.cn/Article/details/gt2kbcvkhbc.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fjlesxrb.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zdqjudy.top/Article/details/gt2jaldpkwu.html

—— 文件结束 ——
来源：http://dali.quarkkingdee.top/Article/details/gt2shpuqiio.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2hxnlvmoa.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.ivvv.top/Article/details/gt2wpwbxnqv.html

Common Programming Examples Cheat Book
来源：http://dali.yonumen.top/Article/details/gt2zsivoyjg.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2uxfdpcgk.html

【收录内容】
来源：http://dali.wangdashe.top/Article/details/gt2nvrwbwnn.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.pengpengdd.cyou/Article/details/gt2vktbvryj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.hysaishi.cn/Article/details/gt2izefatxn.html

SQL · Bash · C · C++
来源：http://dali.yj20258888.top/Article/details/gt2mdezltui.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ujxzynqp.html

【使用说明】
来源：http://dali.kuanghao11.cn/Article/details/gt2hdurkenj.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yj202588.top/Article/details/gt2xhnbbmea.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.ybcxt.top/Article/details/gt2rlndceqc.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.cheryme.top/Article/details/gt2geoxybnz.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yj20258888.top/Article/details/gt2elkyxrkt.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhixingplan.top/Article/details/gt2mpvpuiws.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.chenzaomai.com/Article/details/gt2cvcmxzxs.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.shuidangran.top/Article/details/gt2bgbusxdz.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yangfankeji.com/Article/details/gt2bvqqckmp.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.nanxuanxn.top/Article/details/gt2shcmxiwi.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.ppjwa.cn/Article/details/gt2bqctiymh.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.tanke756.top/Article/details/gt2fsftwogw.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.smart0.xyz/Article/details/gt2btsdeqqj.html

【文件统计】
来源：http://dali.ybcxt.top/Article/details/gt2gqmtfjgn.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.tanke756.top/Article/details/gt2vmczsjlm.html

--------------------------------------------------------------------------------
来源：http://dali.pycfn.com/Article/details/gt2unafdfrr.html

目  录
来源：http://dali.jinqigfzy.top/Article/details/gt2xwiwxpzd.html

--------------------------------------------------------------------------------
来源：http://dali.zhongyouzk.top/Article/details/gt2zufvixip.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2rprbechs.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yonumen.top/Article/details/gt2eadpjanx.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.chenjidiqi.icu/Article/details/gt2hgzjgqwi.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.hongshengwenyu.top/Article/details/gt2pwoebsqw.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.pengpengdd.cyou/Article/details/gt2cszcoxfn.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.aizwys.cn/Article/details/gt2isbwbozb.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hfpthk.cn/Article/details/gt2pnawuzrc.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zdqjudy.top/Article/details/gt2wkjipmge.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.aibaodan.cn/Article/details/gt2oaitdyor.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.wangdashe.top/Article/details/gt2rrxwqfai.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.cheryme.top/Article/details/gt2ucpzqbno.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hnxiangtu.top/Article/details/gt2rdzzukwo.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.kuanghao11.cn/Article/details/gt2aqukdvcj.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2fqcersco.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.ybcxt.top/Article/details/gt2ohsqedtb.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.wangshuangyany.cn/Article/details/gt2iipsltor.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jianghu66.top/Article/details/gt2ojhkvmnx.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.cheryme.top/Article/details/gt2edhgorjj.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.aizwys.cn/Article/details/gt2wccrvfpo.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hnqzz.top/Article/details/gt2khtfoyws.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.pycfn.com/Article/details/gt2arenpsqn.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2kosgatjx.html

A. 基础语法与类型
来源：http://dali.xylfe.cn/Article/details/gt2uzefipqt.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2tlhkmrhj.html

[A01] Hello World
来源：http://dali.svipenyu.cn/Article/details/gt2mhpwxahd.html

Py:   print("Hello, World!")
来源：http://dali.gotoacloud.top/Article/details/gt2hizojyhi.html

PHP:  echo "Hello, World!";
来源：http://dali.tianlin.xyz/Article/details/gt2yuooinvm.html

JS:   console.log("Hello, World!");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rznhqhyl.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.pycfn.com/Article/details/gt2nkmxbjqd.html

Java: System.out.println("Hello, World!");
来源：http://dali.birdmap.top/Article/details/gt2xszouxsh.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.guowangkeji.top/Article/details/gt2tscpzupj.html

Ruby: puts "Hello, World!"
来源：http://dali.hongshengwenyu.top/Article/details/gt2wpbeocde.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yanxiufei.cn/Article/details/gt2lqpsjthd.html

[A02] 变量声明与赋值
来源：http://dali.ppjwa.cn/Article/details/gt2trgvkadd.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.cheryme.top/Article/details/gt2kwaqqnms.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jqgufenzy.top/Article/details/gt2wvklghga.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yuanzhike.top/Article/details/gt2tmjfbtxw.html


<!-- 参考信息 -->