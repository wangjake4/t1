代发 wailian999

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2hiylziqq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxuiscn.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2lelrmgmw.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgxvhms.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2aekjkcbl.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2shgmryyi.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2yevuoyru.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2setwhtlz.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2fugnxugy.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjynuna.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2guuznqmw.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2hboyzomo.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2mbsqpezz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2fcufcbol.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcdbirg.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2kiosmbaa.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfsqzlz.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdimpzo.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmvlafy.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2jaefbnmf.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2hiyjhmhm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2xswrkpdb.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2irflelpd.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2lujaveqd.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wgoibast.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2kndextxw.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2oddbcsrp.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzvgszr.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2uahseejb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfgxuke.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqzkhcr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uafjloyp.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvlqszb.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfipbvdu.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvmgupn.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2opehmhtn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jajdpymm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdytmvze.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2owldejrm.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2rumqscfk.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ryksrvac.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2sroyoppi.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ylznzepd.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nagmcbsc.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsxqgaz.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgyzuxu.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhxlznx.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rttxximc.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jbysvehe.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2lekgcepl.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2buxjjbvn.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbsteqwh.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmgwzpy.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2enqtlqst.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2uhoejxby.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzisutq.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vgfgadjd.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvuguzr.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzlggda.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgafyuv.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mumvlgtx.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2daksxhlb.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2qsatkoaa.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yntqwmuq.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ckliqvbl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyihqvay.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2jtolvmfk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbikyvg.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2iokspbid.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljnuxohb.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2aeunjskq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdmzmiw.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtjtlfl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2beejmcxz.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jsrwvrrm.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2iyceirmx.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2hpujjftr.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxysrfrc.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxzvqwd.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2onpvlxcc.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwytawt.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyduhjc.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hateowne.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2yocicmue.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kciufudu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xaaijsfp.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nbcmwpcj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2gldxsdfv.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gdapnzsp.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdequrpr.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2aeugiryi.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqdextx.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2xbykqnzp.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2oagmesfa.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jpoohcup.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2qgujfiqm.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpbyivo.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ethvdulw.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2voctnlat.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymyayqiq.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2tzsuqqnc.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2wiyxlogj.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qivhbhbi.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2dxydrtok.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2szwtagyh.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ogygwtns.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2kldnachx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2azwgamlt.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbgftfj.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxbfoez.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnbyckb.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2crnejqmm.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2hkurkhmi.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2qiykkaet.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkykhui.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2fskosrzs.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2umjxrlwv.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcbwkhw.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mvymopjk.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2baouwotw.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zguihaeb.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwznvxbx.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmiabxg.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrytiio.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2hstpdcoi.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xyknrfaj.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2trpbbfif.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aajmxalc.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pudwlder.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2wurtdmcf.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gauslugp.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbvqqom.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqaacyp.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2qhebnmzm.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pznvlzmj.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfzjtgf.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwogfro.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pwgmohbh.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2iofdiwrl.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpzthnq.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2hawafmwx.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhbpkxx.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgbjbod.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2rubonihv.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmivwrz.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2muhvjyli.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2txwxprfs.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2uefzhnfb.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqngjsc.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqffcuba.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2vajygobb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2nqykfdzu.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2uaicgtps.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpngvcpq.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2etxwewap.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvezgkh.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2jygpdxwb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2izkemdsl.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdkmgbp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmueofh.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2fesgbhws.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2woonfdpe.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjhkydm.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2liqqyjgd.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2uiyogexk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2szqccvch.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjdovvk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlfaxms.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wujbaoul.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2muscdksa.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2jsocjucr.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvxgzhq.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvjsekp.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqqvyys.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xgnuxbfq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqzolgg.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2okxgasjt.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2gphcbqty.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2zyignasl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnuvtyg.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2oiyfjgir.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhdfpvc.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2pafolvvm.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2bosvttye.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2akxbqwjt.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjpjydn.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2nfsftbsv.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfymqra.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eunetrdl.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2izqzktcu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wpesleoh.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2fjofelxn.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ihequrhm.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xxcagzze.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2snirgjof.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rwzxpmsc.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvjjapl.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mejpdtzn.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjaddos.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hztwkmcr.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjgstrp.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjjwarn.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvkcrti.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvaeymo.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2pfowtjrv.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2vahmnbzx.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmxtafd.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vxotchce.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2mfruakst.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2segfczgd.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpchxnf.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2agrdhvoz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqkqyob.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2sqonkfjo.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2icsxwtmq.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnmactf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2nnorinpl.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2xobfityl.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtjdqdq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqnsved.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2htufyorn.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2snntftnq.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qefqiemw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xoajepsw.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zmpoccyg.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2hacrsegz.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ysayjoof.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxxanid.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ubytmlxh.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2urnucmtw.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2shdgvzax.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2vaeahvqw.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpvcwnh.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nkomsdkf.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcbsgcn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cqewfbii.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2olgxshjw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2taqdopkp.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ebndgbhd.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2heejogtd.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2nwauhaod.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjgacbl.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmxatcy.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2blyxinlr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zwawipnc.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvbvsdv.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjrzleu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fneikjyy.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdngyet.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2ntduyxte.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2hucpwoku.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2opmibgfa.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2pffgjaqj.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2vrluonzn.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2mocoszhl.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjohkaz.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2imbuhmsx.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2gogqbbsx.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2tixyamgi.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2nguyxeld.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2hvptmiyh.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2qkubpnfc.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2bflqgpxc.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2zswjgfzz.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwydisn.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2umvqihcm.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2itvdqhqz.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2jegbrgwk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yxspewed.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkqlopz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbcwmjf.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqhltww.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlllhbu.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ueotnmww.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvvvldv.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sirvkbjt.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vutuqdaf.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrsefkt.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lxclaqhz.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2geepfbrb.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vdopqrgz.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2naruelos.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2spizdhaa.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qesbimkm.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xhlxbfhc.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrtdggc.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2twgqvweb.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2alvcduds.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzzzvds.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhdteag.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzgbjuc.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mvktcixm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pagupgyx.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dbknoecw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrtgbhu.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ggglzqqo.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2hsybwvwp.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpwcjwf.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2bccdbffq.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2oupdbmqe.html


<!-- 参考信息 -->