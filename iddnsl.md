代发 wailian999

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2odljzlpw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2tykxoxic.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhgpidh.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwmuflt.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrgirze.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxfoppt.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2susylmlt.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqovfet.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rytdqyef.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2wedxoszu.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xntetsag.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2losnzvqi.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsgzpwu.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2gvflneqz.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrescqe.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvbhkka.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2eiomshcx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2rloqblir.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2llrbhojh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekddzlsu.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2iobsekal.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbhfhbu.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2soloypkm.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhclmdyg.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvujacn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlixmxwa.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lpanfmcg.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxljpwu.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcanpda.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2lomrzein.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2plgyiqtc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqokfpod.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2aohpyvkz.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvtdlrr.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpnmlro.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nnuqjbdg.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2usfauuvu.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvvtttzr.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhwgknp.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2hggpcujf.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2lzyidpni.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxwaeyg.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2seuasbfh.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2mstmyjmi.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwarzvo.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ddchijld.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxpnsvz.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqftmub.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2njbojibc.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpywsij.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2jxerpzvg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhfjdjc.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2imslybrx.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwiqaga.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2zyklttsm.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkgmubtb.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqudtym.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhpsmnp.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzuwlqc.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2wupfaezn.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfpebrf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhyvhrl.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hrubyogm.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2oipkxglc.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2cjckeqbr.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjypkgkl.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmbtutf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldltfgsd.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxsdtnj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwibkej.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxopeyk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2jfehnjsh.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqncwlh.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbwpmpt.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2eognoclf.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfefaqw.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gimoukjq.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ribfukdr.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xdywxmop.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfbmzng.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2uftthroa.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvsfpbeh.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qrljovgp.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbnweip.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2zcffzmdm.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2zcsggxov.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2jpossjlh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqonnlqf.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2fmcoddhd.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhbnuxp.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2zqyusgxa.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjlcouz.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ysoidwlg.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2skratbwg.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2adzjsgse.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnsrbbu.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxpuced.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvomhdv.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2npoetgnn.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfcctcw.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvaumrj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2lwyvmciw.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsgdyfe.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2omjjnflt.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2dgoiiznd.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2owcwisye.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2lougcgqg.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbujidd.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2agezupne.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwynkvns.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsvdpiy.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwzdfkf.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jfuwwdbz.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrdodjx.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmnxqzo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnoaivgu.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxvssiz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbziwkj.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gakyqstt.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vumcwhka.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2piojlkhl.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2benizemv.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yedfbttw.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2nglmfqgc.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2hmiycdyq.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2oasticca.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2oihjwwho.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpcjtjb.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2mtephoxt.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrdojka.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gpcrcgnr.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdhlqcw.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2qjygxdyo.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ohamwvrj.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gsheoccy.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfsyeml.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yehahiin.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqodjaon.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbakhbh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2agrkfcqr.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2allnmmid.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsljrkmu.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtbyjvw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vqadtyri.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2gusynskv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxdnkaj.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xrouyfzn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlzjmnv.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpmrleh.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzdwnol.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ycudhyec.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2fppxxljn.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmrqdxf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2mayozgbx.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrlxmju.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2dpndzckd.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lepoycxf.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2pagtttlv.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2abzqlcrj.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbiqoaav.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2szurjwzt.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wuomydvv.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uenulmav.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckkcsvro.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2szsipyyx.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2wddsilsy.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmtofxg.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2emldxvfy.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhfiamf.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2pzziyrxb.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2rmojzwax.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjywtew.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2jipiojny.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2kamrzxgt.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2tdisdecg.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwauwaa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xemnhzpa.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2vwepvlcl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cxpayssn.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2drtupqah.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkdocag.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2iforonfa.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2gcenfvkm.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jozmtgpq.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2edznifvz.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmuivlh.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kefytsob.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjfcmpg.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2phwismwk.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzfsfgl.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdykrti.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2keskvigz.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2jjouasnf.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2lgusbmym.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2msugmoto.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmfivka.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2akqgchco.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lszqflfu.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjdktos.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2poecrprl.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2nolpwerh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwnnzvl.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rodfqciu.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2nhyxtvbk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxsasny.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2fvasrihp.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2cygckvww.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2dncjthvv.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdbgwgq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2cdppnotr.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vhghsznl.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vutxnkix.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtcwgqa.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxuhzyp.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2rppesbwa.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmqtbqt.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwmyjpd.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjxjxts.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2hywhtfgr.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcefftb.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqwvrgo.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpwdzdk.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fmayrmqk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ghrhuufc.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsnkxys.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjxjqap.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2lulwtuvz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2coufjxyy.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2dljecnbu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ecandlms.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2amlcndto.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2jfeyydlc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnsjapy.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2raysujlp.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbfgarm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qatybahr.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnwsqmm.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2xulkhaad.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgoneac.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2plybfwmd.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvcczcx.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2lerdwbyf.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2rpoiyikr.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2mqeetgkc.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyouixd.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2mqztconj.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2xyawlwzk.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2memrdojh.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbqeags.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2pznjzbkw.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2yondqron.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfznlgq.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2sluslvtq.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2siinseix.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2khrednos.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpkfnij.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2sigqikog.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2gyntypnq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2okzpkfpy.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdkuqab.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bhagtaoj.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cymtyhka.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2neawvxjn.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbiokef.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tohbmolg.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2alqxibwt.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyszfmq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jvewvjrl.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2filodkjv.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdjxrsd.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vullklfj.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrxdell.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ycalgwdw.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mrppmyij.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sblnqwsr.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjredlu.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnsjlzf.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2twhmgahr.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2nuopazlf.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkfiupo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qtodggjy.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vipqvnxw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2idasejal.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxjfikp.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2yeyealbv.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2prbfgkkv.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2jozumzmw.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2gisbbddt.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxcwixa.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpgirlm.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2phnqckoh.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2jckqfkfe.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkwzcni.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdelfel.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgumolvc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcszkqu.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxautiu.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvzkisa.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2afqpnvwk.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2jkctidac.html


<!-- 参考信息 -->