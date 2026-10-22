代发 wailian999

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpghpuv.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2wursotog.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nksfsfue.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2glnmprae.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbfcamh.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2chhekaoh.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvqgztk.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqnvhgg.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2lntwckwj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2worfwdbt.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2feotpnof.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkeptia.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrkywiy.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqvkmyo.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hhouphkc.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyegrei.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvjtlfw.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ninufxzm.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2evectxxl.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmpjqvye.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbvszik.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmfzctn.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcvpqfb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbthyeej.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkhhjbe.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2rukgtptq.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2egfthbox.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfvvrmx.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nugnkfih.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2anpptcwi.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtiyasz.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmbnala.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aimrbgwe.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2pahssbmp.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rdyydhgo.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lljxtbkf.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwcsidf.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2qbihuwbw.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2banmxahw.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfivwlj.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xtaenutu.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2twyoluus.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eavyhpsp.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zknsksqq.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2blgouckp.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2xlendxyb.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2uahzexkn.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2cpsbsqfp.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xbecnhzh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2jgmufrlz.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lajqrror.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hadgzpyq.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2quzakkld.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwstdee.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2rtugidro.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zexoueen.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nacrlylq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfytrdc.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2hklafqpi.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nplrhkoh.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2felmddvk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2astjhkkd.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkxfjiv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2yacgbskz.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2udgdkodj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2xayjpiwb.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2apjfbvrw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwvuiax.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2tujysuza.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcaaiqxl.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzibxpu.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwspyydz.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrrryzu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgeflapp.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lobwcgiz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2puxavqqv.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2chjxeewy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpywdjvi.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ythrlrlg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2gfivnlzy.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rflenysd.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzoaphh.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lojiypmu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2gryamngj.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlhfdjo.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvoqytj.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2exibvmfw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2stgbriqp.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbspgeh.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwxumbg.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmfkcue.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmajmjh.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwbmtrh.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2chtsfcmr.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvsblzl.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcacibu.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2zdriwsxg.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2nbsxtorf.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2eqprogtj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2owgadmds.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2abgecxbw.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2klcskash.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrpqqrd.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcnaegg.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpcnlju.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2qdotesoo.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjhjbyt.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrvudqa.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2qkifwgiq.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2kthkxwcf.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2oikabjog.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxwplad.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2bcumnaft.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2vofosryo.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkyelsw.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjlbyhn.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2exiuphwv.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwmamko.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpaulsi.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvngmcc.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdgwktb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkwufgm.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2utnpzptb.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2eegzxnin.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvjafgz.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2skrmemmc.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qoombgwz.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjjzcjf.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbrebnw.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rcifnhsd.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxkuuuc.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fohruztl.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjukxfm.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2awjvhdfs.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2awbrivwb.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2gwkapbqx.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2rmipyykt.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vapoqbpl.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vxosahha.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2sflmbkpy.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fajajwxx.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvybxehs.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2chdywbfu.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2tojhojlg.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2yiaazpfu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovisdgqm.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2xddtkqfy.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2updbbxij.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzoveik.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2juudbayn.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2esismrxx.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgcrifg.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxgquul.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2uahykpms.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2eeaasink.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhrhwym.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2thigcfjo.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2qylgbueu.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2qygcpdny.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2beayfwaf.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjrczpw.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2seshrzwy.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkotrcb.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2mchoaajj.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2mzluknbe.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzyazvkr.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrmtdgi.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2scrjvnoa.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2nctbmyzk.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxcvyyy.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2carygjhi.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjrfugt.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfewfep.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2fpntggrh.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ngocmndq.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfvmzxs.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgbehde.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2tznkqlvm.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrxgsya.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2inydwxku.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wohyepoy.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ageveghd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2imzqormc.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2icorzxwy.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2baquvrfo.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmhzjew.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ktdjhmqh.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2smignzyr.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vbpysnsy.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpwugng.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fageagky.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uwuxsyxe.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2vzktrjtg.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2haarthnh.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2muihzdnh.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2midkxghv.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2saxupsmc.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtvwqme.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vvupkzgm.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbpbygh.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjmzpwl.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdaypkz.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwhicno.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqnxags.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2jzeiysos.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2uoujoyaa.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2inrvglki.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdtlkdf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2irlejffw.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2kcuruhom.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rzueedxs.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2gelvdusj.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nfovuldb.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbfsjdy.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mzykbkhi.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dvuutvwk.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jbigjbgt.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwsavjb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrokbkt.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rftqqmhr.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2thplxouk.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmxinfz.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2mhupzgeh.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxnixwf.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2fadtvtjx.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzgllpg.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfrckna.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rmphjfdh.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2cutgxeoi.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zznmtnjr.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwrzudj.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcwojhs.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2vayvmxnt.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2aewzehpv.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfnjbdx.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlpunoz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2luoeobdy.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2pykxicoj.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2uirhmqmp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xidlbbix.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhkvyou.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmbomus.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2qnagexnm.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2chslklcq.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2vxsbxlsx.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2hevfpmab.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2tqklxzko.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2hinqykwn.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2ajksuuvv.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdfkrln.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2iojepxip.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqkhwxy.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2tfazgacx.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2amjstxwz.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2phkgqltu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2cbarhzgp.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2akvlttku.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2wxlqwxan.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ixldpgwp.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2lndwgsxb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qovjxzkx.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmwazqs.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqxviup.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfabsxr.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vkuavetj.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dsyljlru.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kqriuppn.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jraxaiow.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhjvcev.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjhfqcj.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qipuqnlq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkqzpxx.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2reqtiwix.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhopsyb.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ginmpesl.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ckocmyng.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2udpuwsan.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmbjfwx.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmlcgid.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgzkheb.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlwsqmk.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgatccf.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2iumfixos.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2urodtjzu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfnxmjr.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgazofk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkqxume.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gcawzcyk.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2xukcrkul.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2jhuqjczc.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2uglirgxd.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfmrcet.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqebvsa.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2gayslfdq.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmbjebl.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgfeujl.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2eeghxnhg.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2kxawrgid.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwmnexc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpfstak.html


<!-- 参考信息 -->