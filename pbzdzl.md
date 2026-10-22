代发 wailian999

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2awnsxlgl.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2svzljkpg.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcyjvdd.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2jvshvivh.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2htwpjnmp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2edsbquaa.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfvpajy.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdbzpzn.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlydfzk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpginyez.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2plgrftgh.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2taqwpfyk.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2cigbztjx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfuqjpf.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2azwwovuo.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2mzljdalt.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpmnktg.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2udozjwai.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxbmarn.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpeqcjma.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2nhowglmi.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2buafegxn.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2njhjrorj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfikzmju.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkluvao.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpghkskz.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dxglipyb.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2idwlhhmn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqgdnum.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmftoxgz.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2admgypct.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvphvmw.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2izoszfmn.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2fobnkhlc.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgsptub.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pddhillz.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nnoqykvs.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlifduw.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2scenanox.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkaawxd.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2sdufhano.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtmhbws.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2liyevfel.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmwcfhi.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwsxgfr.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2dpagcanx.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2akixrttz.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2opelxlxg.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pdufpahc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2jiygnjei.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqmyayf.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpowlxe.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2msoqtfkx.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uukhvats.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpbiqkm.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijugngss.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mddvbqsj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yybduieu.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpwrxwl.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yabtisvq.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2gyeqezrm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qisbxurv.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qqikjqhr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfycpyy.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2uokqychg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcxnomk.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oxebajbb.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqdcmkf.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjdrfky.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lulgvcwk.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2fdulcrbd.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2orulfczw.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvyrvan.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfawawl.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ktdcsuuh.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2olkbdgin.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrwnbmv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2etnepzea.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkumssl.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2xkyqeajo.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqfacii.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2akycyvst.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ouovkzeu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2iddwcmss.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdzkjef.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvegbpgj.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgtrmfh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhpkvxh.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrmsbol.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ifljsgrc.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2jemluwjz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdaghze.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2foipcshq.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkmiggy.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnmoqyc.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2yoekmtyh.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2khlgrefx.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2zkoealva.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhkdnzl.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2jygwbffe.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2yiadatqg.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2vdohfhhm.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmwfoav.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rajpiwsn.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2sczdmpdq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxnrkcg.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2tqovsumj.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ituguuwj.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2zaabevay.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2cbguamej.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vueupjwx.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfwxdtw.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsbcqfy.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdejkazw.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nzptuwio.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2eywqdjyj.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlrkbxg.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2yqifhmgo.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2znqoqets.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2onihxoks.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2skdaurol.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2prtylldr.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmmkhjx.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmsxiym.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2muesrapd.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2lgeyqteb.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eljjdhel.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjpnpndx.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrnknyo.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2sipltutg.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkozkmt.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzieerge.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2xulgnrcz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kajprkgj.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvqgvds.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2oecmnsqa.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2zmunrcxo.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vursemel.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkuavbo.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkosymf.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjdeyiv.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2xldeffhm.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrbuzgj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2zznwbyed.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2hejyjsvv.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2wggzwkzg.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqxqnhv.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvqvfmg.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnuprpl.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtkrhmx.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtmglss.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfakget.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxtybtl.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2wznyppur.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2sburfisf.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2jspmwvrz.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2cgitxivw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrpcgne.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2thewjmhr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxmpwnj.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2bthvpuhu.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2roryfueq.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwxgrlj.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgmfeir.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2mmujihtf.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvjwfgw.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cldhjryg.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgphskn.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2raqhwmhx.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2pwguwyev.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2kxruersg.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ercnwpvr.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2diwxcyqp.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2azokiiyp.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2outwrcot.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2cayakpxa.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2biswqqew.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcrjzjy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpaawbo.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2wzinobtr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvxrzkb.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtxnxmq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmmzbth.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2kpteuwok.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbkcnpl.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjqgwjm.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjwvxtc.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwbgrus.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xoilpsyi.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uggxikop.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpklsca.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdxooto.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqowtuj.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2xppddjrb.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2fpetndkh.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2uemlagce.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrsvhol.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2jemwxxnv.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2inlvumsv.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2brcvgjne.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2pkadtveq.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hggcgowi.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2rotcmsug.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2idfqftmd.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2gqsvmxzo.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nwgaiyog.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhhexob.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2amzclemp.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2vqblwkqy.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvxfotx.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dddfzxym.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnhzmgp.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mchqvhxa.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdmjlol.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qpesidnc.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2paqppwck.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hickukdk.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2fdplqdof.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2yksfzrdl.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pelpbjtq.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlncsco.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjrkmxm.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2mckaxpdm.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2eihuequk.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxmyrfy.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2splymtzq.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lpezleqe.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmjctjm.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2buqrinol.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2brdfkvrn.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnrofpz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2fmndtxey.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2khhhgnqd.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2lbodgyut.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2bowvwsas.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdjzmku.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqejlxu.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmaorfk.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcqvuwi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbxyygw.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdfhfla.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2ipurgxzq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2wtofzczi.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2azsdyiag.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkrkjyk.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjszitq.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ebydnemw.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2sekdmuwm.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvszqkj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2dfuhzvni.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgjycjh.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpmanxi.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2blxaqflj.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxfzstb.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2yaakqben.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2wkmkdght.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ugleelon.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2esfmlrvi.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2bhugwgqo.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2algtixom.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xaevsrbh.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2egnuxrue.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fagphdbq.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmjglbp.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqxqaij.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvhifrx.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvalkhh.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wmiwvkum.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwszddu.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pgyewjpn.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxbkvcy.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbuwllq.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwrohsv.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pslucskk.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvhucuu.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pclaurmh.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uunxvybs.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zoeacgal.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yncsesgi.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qtexqjga.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvgbffx.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqagzeq.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfweysy.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqyblrm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ysadmiaq.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvsamwr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqkduuj.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcbpndf.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehepivia.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2auwwyssg.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdwxuft.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2qeswdfqd.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2yczkoxtc.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfeoxrej.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2svbmijyl.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2jepcthpp.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2vclfimtm.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ootwsyql.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlgmfcc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2clkyhptm.html


<!-- 参考信息 -->