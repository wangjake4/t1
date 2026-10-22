代发 wailian999

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2btvsakds.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqueoeoa.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fscaounv.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmiohvx.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfudxbh.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdtjhdh.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmwsmov.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjkwpuv.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjdiflp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwmddti.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2izvibmqo.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvdbosw.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqvwvma.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgujhypx.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2lfajjjid.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkqhuer.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2aymcyfrg.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2brzjskbl.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgayoep.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2zencmvzb.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tzsxuhmh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2naekgpyl.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2eirsmhgt.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejifwcbl.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2hyiotvgm.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2inntumih.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmakerd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjxedce.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2yawiwbsz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2xgyubzhj.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2hxubjkiq.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdmgnaw.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fczlnsxo.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhdgiwp.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xsabuyco.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmcvpbwy.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxsvwlr.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2foaodkwa.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqhfwxs.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2fbeiflop.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2bcszhkvq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxhrcmv.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2hteqxbvh.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsdywed.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2qbksrfps.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmukszu.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmswtjc.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvpiudm.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdmiomf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjkvfit.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dsafoqgs.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcvzgtf.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwanbja.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwefzmrk.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcedchv.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtvlpqb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2nivpsnrs.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2fqihhzvj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2faqqagpr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2maktrvnk.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqoywkb.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlljyxph.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnwlhqn.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hygjjdvj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wuyxqdup.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqszbpl.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fvnxbgnx.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtjkpnl.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zudlhkzw.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdtxuet.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2llnjbeoq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdyexrh.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qaaemphc.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwaetzh.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2iefawyef.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dwiuikcb.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpdvgxb.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvirlopy.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xnutecjw.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmkarcv.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxhifri.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ztduwyec.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbofctb.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2qqppctwa.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2skczpmwc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbrhadn.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2icoobncp.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqxbrcl.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjawnmv.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfinmvx.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxgwiwk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2epuxdbjt.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oipwklgh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2loluouek.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2cmldkwwg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwsuraj.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwokmtr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mygltmqd.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcuoduk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpzfuic.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2xqiljuqc.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2vumxzxcj.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnuuhog.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2cwowgdof.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2sglalxzh.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwsharb.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ixaxbdsm.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcojdky.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2itdbbnoz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2shlaqnjc.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xicgtxhf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2hvviavmv.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2iuazqwzb.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kseevqiy.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmmrhdt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2grktejwv.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jbinnnce.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvscmlub.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gcifhjnu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmncshq.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jpiwxxxj.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2robqofih.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqtiosi.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2auxqpeaw.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2fczpjwuf.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2rduoosiw.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxiozms.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkqsrxj.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2naxpalsz.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2khclmvij.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2lxurosqq.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2lojhmbsi.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2emeesepf.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwnpnsj.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfejfwe.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2jqiseade.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ogehnchj.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2gcumbmdm.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2qmsdbmnx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgnmnen.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2taplbdli.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2koakhyyr.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmbvtdl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2fjanxjee.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2dydjojdz.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2exlcksjq.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhclstl.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2gefllwga.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjlxxmp.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnedtjaz.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdatsvr.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnnsmhj.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhonuvz.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhzeskr.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcyvwog.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbosxeo.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcnursy.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsoxnhu.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgzmqdw.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqelhdy.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wsflgnlh.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2xckrozvj.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2atygdzfv.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2psyotnck.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2rerllltu.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ikcvxuin.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbtibev.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxkpwmm.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdkfayo.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2abfailvk.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2sauwsslv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2fibnzaqv.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2isxldczr.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2brwllnls.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cqocskfl.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2grevihes.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hydlrbup.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2kszpafhv.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ayucmerv.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2rcsxsikc.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrxskni.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2txdpaess.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgkrkyr.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbcobeq.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2puhweypl.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sltlsyus.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bhrbzwyv.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2gupbjqng.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpzfeon.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2cncwjwwt.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnrjcxn.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ptltubis.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmchweo.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkdrioy.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2kahrsrtf.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2taylvuhp.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2tahjuwug.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrvudsf.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2qsblmnqu.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2xymioitp.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzzneby.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2moxvhbnp.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmozwxp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxgwcvgy.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2rhclurdg.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhqykdq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2twbpilos.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbbkmkt.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkxbvgm.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2nomshaek.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2bmoimgfc.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2lygucezr.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpingfp.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2moquywzm.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2nuocvdsh.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2estfynnx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nfsrvghc.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2aawezwps.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlhbrur.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ppoftzqe.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwaqexc.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lsccclaj.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbynofl.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fymomtmo.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxnayer.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwevxbk.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yscdkmtf.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2njnfyuqj.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2txmqhppi.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdchgyo.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2caantgry.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2muymbado.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2luajspnz.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2eldqgdic.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2epnsvppn.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2urzuyeni.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zheybeqp.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxdlvor.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ntedyxvt.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2yeenxril.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbfzbfp.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrtzbsg.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2egcyglqz.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2clfoxnhk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2yilaagzo.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhzhfri.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdqfwad.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2eqemimas.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2inksjrvq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqkszby.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2otumtksn.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsuxxyf.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wghvwlal.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrqfsjh.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2nzprqhcy.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ijcrblya.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2qsecrfow.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2qnsviymj.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2vvehjbpk.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwqoyja.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnyijbj.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ljskzxbh.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkomhjg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2chuwmunn.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2ajeayugq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jiyavssx.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2hmddvuqr.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyvupox.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2zldxcpuf.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbydafo.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2vwakepfp.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2goawkere.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2njhxnmzn.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2recmfgxo.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2aylywysk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsqxtrq.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqpdztt.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2qhirxuif.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrbqory.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2eojqyfwy.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2kiszykys.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ratouyph.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgwbvig.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2avtwzakr.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2orpljuvg.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbpxodf.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2mvykdvwt.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2kawwvuon.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2qbngufex.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2vasykfog.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2cxumckio.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvdrlnz.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2vickyjyn.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ronklrvh.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjgqupo.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzftdup.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2utbbxxkw.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2cfycxzhb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwqhvep.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmxtphq.html


<!-- 参考信息 -->