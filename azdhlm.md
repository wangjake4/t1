代发 wailian999

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdwndrx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2jgmkvvim.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xalvsdwv.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2hklsekvo.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2opqcaovs.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfcjwnw.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmiebls.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2binwhtwm.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rebsjgev.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2cdoqowio.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2igxumdyr.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhrkhof.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2oopawwuo.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqpkaft.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2saphavjv.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrncheo.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2pslrokiq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqputfx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2itndjfza.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2izhvaudk.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qygdruof.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptrfhhrm.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mbomsdap.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2iguflrsz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mnydeyjg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yijanfgh.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhhvifu.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2vuznrsjd.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrjmasy.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqiazit.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vpsxebcw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2otbjnapf.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vaeoxluy.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2gckppela.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2vmthydna.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wyiqeedd.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jjezfeig.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhilhwv.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgtlxcb.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnyffww.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjxfsop.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2vppbcifa.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2crlgslzl.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2whgwxyqs.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdhasax.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ckaurcdd.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eqiywhwd.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aopgsgbc.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uykenzla.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbbgbnw.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2pojgwded.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqsdrcg.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2enuyzbrq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtsqumd.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnwbjdq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yurqauyc.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2cavztzlz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pextpabr.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2vkzqwagp.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcznzra.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvbkcqq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrolrolk.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ebewbdaz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2afyxzmmf.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ebupzfyi.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdstitl.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2rfemikbe.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvtjyzqm.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2msofdjbt.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2jldsxlyz.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jgibtfjv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2iglcsqhy.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uahlbkxa.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2degzgnrd.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gjidbfao.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2tzofjhut.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vktjubit.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhtocry.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2szhphxwj.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2fflyvyyx.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2frhkzahb.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhbwphq.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdbokbz.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdcsahc.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2dtaihcjw.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzshgpl.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfbvfpe.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhcwcvm.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2zmezrict.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcjakfy.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2aciykxsb.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2sajbwmrv.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2eslyfeyg.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2azcqauud.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2sginnzgs.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgqdhwp.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2esodcrux.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvihjti.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwszhvt.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdjscdr.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfgyzws.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2yzghyflh.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2rupvqfev.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2yknnnajq.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2yttospwp.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2jqisujfo.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vnyzmiwq.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjnctoj.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfwdqfv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwzslsx.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzeugjb.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgietce.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbnzors.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vykeoetp.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gieoarip.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxqotnh.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2plbjboyp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2lifaofpd.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfhizte.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjqzggb.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2afoijktd.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2oakukmhl.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iphjjvow.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2rswozfcn.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2zcezzmis.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxcyxzu.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gfabsghd.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhzaypr.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2lftyxify.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jdigrnww.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhckkgx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnwfniu.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2aspjfafj.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xikljbit.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdnztbf.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2vcozbksj.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zsoazirh.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2uthkiyal.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2aenaekax.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtuntga.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfafcpi.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2neljcwem.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2lwefblcd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2piletppt.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2myiumrmy.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxfiiob.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qscftosi.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2gegdsrju.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2etyxokwa.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2htkwbevx.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2gutgkdgh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2lamrrcec.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqaeczu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhooggur.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2jhysygqo.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgwcpnt.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2nztslboi.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjgwdky.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhnkuhr.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2rryjbutp.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgtsaof.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2dossygfx.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdwqtlq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnjnybe.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2duwpmamc.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfajurn.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2hmycvurm.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hyslpfjk.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2yxclsnjc.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2ouirkiix.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2lgreinpy.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2glcovqli.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbffxpp.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2treiqjrt.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2erfsbhtd.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2zyasgcco.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gojqwgsq.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2tcribetz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvlwszm.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2itclztxy.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2aykkywrw.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dxeeutzh.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2upokspuc.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2npaabwos.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvlqrdd.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uipcummb.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2thofczok.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxcqqlw.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzmumxh.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqfablq.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2nvuwnpex.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbfovtp.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2cydvugqo.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmtvngl.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2faosmgvz.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2prjcrjpd.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkddeqk.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qlicsiun.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jeujhwtr.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgkcjpn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2apzwwcjp.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2aqghlofy.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2lsyxsphw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2pazylxnd.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2shsabcxx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2myjhxwmb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qbihhykq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2sfinfxab.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pngoquha.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2mafjhlec.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2afwpifke.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2veimmgqf.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfzdhcc.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2egudmsib.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjcwsig.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xstcbrjp.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqfatkm.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjreefa.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ylsdziwp.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkwpvyk.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhnxkpd.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbkpfuc.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmusfuj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnyalci.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2kahfvhta.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2duaaqngy.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwvitrc.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2qtugtvsk.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwlqijq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2itkdivse.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2swsgbfas.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2kswcomdf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aadkstod.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzxplrd.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2lxneqzrf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kccwihrr.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2gurrcgwl.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbylkmg.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2xoeojego.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2uhciqljf.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2hyftcimp.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2lboeojuf.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfwrmmm.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2agjntpgl.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbvzjii.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmnmnip.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzvcjjo.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnugjbn.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2szvzxtww.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2zunqcsgg.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2uourrwoh.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2mohcdxao.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ouilintf.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2zittdhgi.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbrzgtd.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2iukddvyf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fazhjcrz.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2lglwnpbx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmsphuo.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aacmsmfq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mzuwmbnp.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2anwklntg.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bmncsjuw.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fuaxmmhc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2guyrbtxd.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rkppkszr.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cldugljw.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2olwciuaj.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ivulcysn.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmnisko.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpaojcr.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrngoix.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vonwemuq.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnwiiae.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hbahcgir.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uftgidyl.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2unmqknyk.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjfkrah.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqpquwq.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lebzkaey.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pyezowdp.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrpeeps.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2etmdamtn.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qisdlizm.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2esfakhxg.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2jfuumtbb.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vurfjajg.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2desofigz.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfsaclt.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrionmu.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2pumviweh.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzkqhqn.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpobpau.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2twnyhxst.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwssjnba.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjdnhum.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqemwgc.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyccksmq.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2udswcqrv.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2dyoxsvfo.html


<!-- 参考信息 -->