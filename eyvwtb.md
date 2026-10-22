代发 wailian999

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2wmcmmdoz.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwytqmtj.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2epuuakne.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2muawrjbv.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lzprfnit.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2datfkkvr.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zidhoonx.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkwtiau.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbekvdw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgahfgn.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxsdjsg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdwmtyp.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzyqyyi.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmwxdpi.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbdlqfy.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2gycdzwes.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dwoowded.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2epyebced.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mholjwad.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2utlryjpd.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2dlisrnue.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfiecxg.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqaoomp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2tiormkiu.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2swbvzfcy.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2vieowfrd.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2cygddvhq.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2lzpctisw.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2tztcwzjf.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2uyijqesd.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2oshtkjwg.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtyubywl.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2mihptwky.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbnpkcj.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2isitaejd.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2cpoktvzr.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2cybgtvrv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwnozkp.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ngukkcam.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2svzdczoo.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2etxecibj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2etbuosce.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvksnpd.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxiymwpe.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2gxotihro.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxhhhri.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rasbstut.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ixihsgmc.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cantgugn.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgyjsgh.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2orvqrxqi.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcgtpfl.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2twjjndct.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpruncj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvgeouw.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgvuppm.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2uakpkvbg.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ityopnsi.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yvlxknvh.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubetkrye.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ighhysma.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2niqhnebn.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2evcvznpc.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2egmeztzx.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nopcxfio.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjbvtsk.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjgwaed.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwlcokg.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lapzytrd.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2agtgypgo.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmqmamy.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2flgoemfy.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fygvntol.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2dugzrlbt.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dheckmve.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2szmbravc.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2rocheync.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrnwusk.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2tybxxuvx.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2khhxrwaf.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrgdimg.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgalmax.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbzgvsf.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vutlzjht.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2oauebsjd.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qfegsrai.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2zksuxwmg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yccrvnkm.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iuoaamlx.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2irzkigce.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmaenob.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjusrsxf.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2orrwjfcj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2inamrueh.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xbuvxmdd.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsjwisl.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qdupqejm.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrcfkdqv.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpcumnu.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjpylmm.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2zdztwbda.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyijjhel.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2icnfznig.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdqpaws.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2biwiuvqt.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2xpglnymv.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2eyeulyku.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2sodyztkr.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmmhaqw.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnywdhai.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2omopzynj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwufrmm.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fblvkkao.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2odwrrfuz.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtphyrr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2lubhelrn.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gpuklzae.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2wllsxloc.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zozjmphd.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2kjysdgnt.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2qiybhsre.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzjpxkx.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2syddfrxv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwdcuji.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2kvuhihez.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2zfovgkgh.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgwnbje.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2bxexqdnb.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2huuunqup.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjncomd.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2znhodwwv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2jsojgoxn.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdiphrc.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbcvrcp.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxjxopj.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2arxpngxm.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhmptmj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2cjuthitq.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhwvjsn.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnldupq.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2xovjttzw.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvkfibf.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2oiyedcmw.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2letqlpxy.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqkieve.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcdjgnt.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mlygberd.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2joaqqaun.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwodkex.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2exymwuzb.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2plpuqset.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmlsjcwt.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2otrgolyn.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2pamtvdxi.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2naoqeevs.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuidpjtm.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rnyqqoih.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2zehyvypu.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2brbahzkl.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsrxpfvq.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvvjbzb.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vfflzjnb.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ktdttwgg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2osvjdver.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2eadjmnvo.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2msdatnkb.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgsijgd.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ilpugxdy.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsfnreb.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjgdpai.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zfucrahi.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2spiadzko.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rykkhndd.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjecgvrw.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2agflofmw.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2mbiovzzs.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjoqrni.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2btetityi.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcdvqbx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gloeqere.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2tmymsenj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmmoqrr.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2raawpclm.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpvcdnt.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ovihlvau.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2espzmccl.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2sklazkum.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2uneonqqx.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2llricvzc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2uikrcvzg.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2skhgjzbv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzmtcet.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2czvpnrxc.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkvbwvk.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2vokdfrxa.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipslvdnj.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2pvknkiiw.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2phcxtzxu.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfpdvyy.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhtjqlt.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vaejccuz.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdtmrzx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2lwowsltr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfiywbh.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2bewhranz.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpzdfbe.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ianxhljz.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlcskci.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2fkswpjdm.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqofnfk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2chazgjsy.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2aiihrucz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mdsuafni.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkxwvwp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgmreeb.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2htoddimr.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2cugwyilp.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2adlrvxfb.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2msgfvltm.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2txgithow.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2geidtpej.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jnijfpjb.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxdegos.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbhkqte.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2gocjnvtz.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2oixtjihw.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2yezdywln.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfuoptk.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ysauskqu.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2llyavosr.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wujskpju.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lgwotjqw.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vixtllbo.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2suytztcb.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkgxgcd.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2nhuejivc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjzrkti.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqogovx.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2juqzkytu.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2smcetafh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2kidkfibx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2jvewjbvx.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2aiclywha.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ettzelfj.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2sflpxysf.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdjqayi.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2iaspopdw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2prrjnxnc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mnsbvrlh.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2gncfgubf.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjkofqn.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxkhvtg.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvxwzot.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2puyjwvqs.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2bethnuph.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqipdhl.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxcwcfw.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dnuoqscj.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpaaszw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gylykwlx.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2blnrgojw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqocmsb.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhngval.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzwwgsp.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwlcwsd.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkjhign.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2zezbhaql.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhuuzol.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkklbqw.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2aefkbbcu.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2xokxiamx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnohjum.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpesyab.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2yvoozrbf.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkctzaj.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2gydqxafp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxjuhyo.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwmhjqx.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2eisorppv.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcersmg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2thnvynmq.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2wszobdxu.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhojhjp.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2isbeytiz.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2qqluhwal.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2obznzuhb.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2nuywpxwq.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2inlswlyk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbpgend.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2yilpvnku.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2iloovsuu.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfsnqrh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzvrbgk.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2pynjoalu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2btzxvnow.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhwrhjn.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhenril.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2temkycce.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2husnuhhb.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgfcrsv.html


<!-- 参考信息 -->