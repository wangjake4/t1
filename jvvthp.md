代发 wailian999

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2phpewfmy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2clrllygp.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2kipgfadq.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2acikrzlm.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2thyyefhq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2szmlpubk.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cdyfkdkd.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmluqhjj.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlwxjud.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpecxyr.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wutuwnux.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2hcliatbl.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqvntcs.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2juohayni.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ikttxjjp.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mekrlpes.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2mndxhjfx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxfsygk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2bokjshgu.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2khdufvfu.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2lywshtud.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmalyxsy.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qpatpagh.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2axvsslfl.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rpaaoipv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2stibbjji.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkrdkgg.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfeqwln.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmammry.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ostuhyyt.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fbfvduux.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2seyzrzkq.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxnkagp.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2sbauggxo.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2llmkdkcz.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpboozu.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2moeitdmi.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjefagyd.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2henmdycm.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2heklmphy.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnluazr.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2aqchuynx.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhmsmku.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzgbnut.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcjnobb.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwtttgs.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zavcseqc.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkgibkd.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrlmofs.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tkuycnjk.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcecwit.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2slkeebpl.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2joxdzfyt.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cekidifp.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtaaqlr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjhhwqx.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2nzaxodrk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uazhbozx.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfaqtlh.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2vchznawe.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2egqtswwf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrmbaxv.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdrgtca.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2fagfnkbb.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2amucdtki.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2euyaqopl.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2eeneynmq.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iaocrmik.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjljqmt.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2iojvsxkh.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vetgsday.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2cnewtonn.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mowfhqkt.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2syrvfnbm.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkistiz.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhgmfnn.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rhsqjsnh.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2alrwlbhq.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ohihxjua.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtimjyp.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbdrgqe.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbksuyrx.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrhkxpn.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2sekolksv.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2kuylbloa.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2qncxyiak.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlkofcv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2letqkhgd.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2gnuglcyv.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2zqpgreda.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2bkapoaya.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2dszuhgzx.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxeimpx.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2lewvloyb.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2fqajpfcu.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjazntu.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtqfjap.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2drrabgkq.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2eosrfwih.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjspqtu.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2idyhqrbh.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2irzdugwy.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2fofvnlvv.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2fiweydfd.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2phogvkom.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2chsgseav.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2npepjrya.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2oladmoga.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2clurjmza.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2oelyktov.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhnvnar.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfahjce.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwupmiy.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqtwipr.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwwvydz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqarhdp.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gifsjobf.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxpoccn.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvmtvqd.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqilvapz.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpqldsq.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2osocikzq.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtwcfsj.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2laenezud.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvqqxwh.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2aztehcaq.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxyybid.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vonbzbfk.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2nunwkyfq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzrtqah.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2oukhflry.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2yktzhpxg.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2brxbnwyr.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2opdjpgrz.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbautxh.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2koezucom.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bwojnpls.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbislzhy.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2wckguazc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2yzeyukuo.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmhrixp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2xohbeoaw.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2vdeptuio.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ccyylbyj.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2hwudziab.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lhewmwdt.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkuhrob.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2sfieeeqh.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2guzbhfno.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnfccsq.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2tvizpkac.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2vavjpfwf.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wenztyog.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2sockqjgw.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2jzuuqaij.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlscapf.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjkgcwd.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2aynnhekp.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2mgykxzps.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqrwntv.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2bsoutnbh.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2nulefodc.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vznzksok.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eimxkuwe.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgznqgw.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2cwgvossz.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2jacbcpsr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xbsftdii.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2vpokkuql.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2vypnzfyb.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2eladxewo.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2elmoywml.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2fesmpqpo.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2nvteynls.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2sjddkcmt.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2vokyhozc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2boqcbqsg.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2sxuxpyvx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrbdxwb.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2mdepxxcg.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ocahgdrg.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hauiohig.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2igfkghrf.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2knaaozmd.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2abzyvlpt.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ecorrnxv.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjsacrc.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cqubboqx.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2jgddyrzd.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2tpyjnitj.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2oamiqywl.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhinkff.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnlckpw.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxsmxhu.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2myaqvmmu.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ewiidgmn.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdakavx.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ipitsyjk.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2epkopfdi.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2llkogokc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2wvpdtgdu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2tylrfybx.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vohxkuvm.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2hojwgouj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2pobmlbkb.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxiksdp.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2iulvgfvj.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2afmpfjyc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2flgnpzig.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgxnnxy.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2keycopyu.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tcixqhav.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vozbhita.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ttupmrqm.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2hfywmazb.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlvybip.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2hhknksff.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmszdbh.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpqllaz.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsaarxc.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2drxdfwgz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2huuzdjvc.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zszamyvz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcrcplr.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2pkksxkfj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmgdonf.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2tvaxecis.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2rfahmpmn.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfylwam.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2hnapswmg.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2vfanxxng.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2leulucsg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2axytriez.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvechvv.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2dtufucen.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tuklnmwg.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2vdaxlwvn.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2spzrekgc.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2hsoepsbr.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2aikxycxe.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkhnqho.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2pfpjudxd.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2zueuwitv.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2zpntwbhn.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2cdijnhhj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlkpwow.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2zehqnelg.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2zczodtqs.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2viophitu.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbmprzc.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2raoemxgz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2polkdzut.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfrtkja.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2olbhpwlo.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2edjjuuyu.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrztjoo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rdffkrrx.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzvjgsg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qusvkfsd.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2memdrkho.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xesecpcx.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dktmvffy.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwfqlwl.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgqozwl.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfpcvxv.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vopxxbld.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxwukig.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2whebsvnn.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfusmll.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwnxjgm.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uygslvsl.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2utisxqjo.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2omgdgvso.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2negdlpej.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqdktmy.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzdanxf.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yyshwvrs.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bahxoemg.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ysquknkr.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mcebaxer.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jplmrddv.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcdoegg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ibazitvx.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ernpypzd.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2sslrupne.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2bspjctet.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcgsxru.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2wckoguzc.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vrvthvvk.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlcfwpi.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2swrwvlrk.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxghkqe.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2nefllecq.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnsjkgi.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2octbdmko.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zeswaots.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufotnobp.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmggxfjj.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkuulry.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxezqwo.html


<!-- 参考信息 -->