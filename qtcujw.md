代发 wailian999

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ixksayzt.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqxqvyn.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2vggmqygi.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2lacivgzw.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrhiahv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwiaxks.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2jskhcrtj.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqfmtys.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2opuqxseb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtwgqiz.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmmseub.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2sipgyiyi.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2mizofjsf.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2fifndlkr.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2vjomehcl.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2berlpyus.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zkcfoika.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2owbpmpjr.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ebljppis.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzutkgy.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2nriwupgr.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlsugle.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkfegzk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2peqfuyzr.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnjgjwm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbmlhsm.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzfjxae.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2jrngmzaa.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ochnpoeg.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2tslnxixu.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2frqjjlwx.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2omnoafcp.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdaxoye.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjrldvy.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2buqoklix.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjklvfy.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpfwgnb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2lselhidv.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2recungbi.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqichmtd.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ahugihbt.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2jklaxyax.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nykzmsme.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2viihbaqy.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2szbvguli.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbckoms.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2pghmbfgl.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2sptnabsa.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2exjderxr.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2prwsocrw.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsepkmz.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuirefto.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2jxloeoly.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbtlrue.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2usdamwgb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfcenog.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qwprwgde.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdigqdq.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvdcaby.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkoieql.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ghnsknjz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrlvijr.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxopwln.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ubojcpiy.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hjqssxai.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpprbmz.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qydmrkvv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpadvai.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvbdjar.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2jthubnby.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2zfovpxyt.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qpaayxza.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2aebzosxo.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxwriqd.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2msqimequ.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2rehszhct.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2bupjnfjo.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2niusrohk.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzsiedy.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrwinnp.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2camqxvkn.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2pblexudm.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kappsize.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2unvltbzr.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tvsravtq.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbcsolp.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2fjsdcuty.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2glrezgas.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2izyqbpry.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsaxurn.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdfcsvq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhrfuvk.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2okdybxvv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fovwneek.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsmkoeo.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2urdxwhxg.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2eskoerpj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvoralsk.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2esyoxdik.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2vgszpqiv.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2xryubpda.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkoiilzm.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2tvithoqo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcynypf.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnzfrav.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlqxzac.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2slkxgklq.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2fznqjzjx.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nvasxruk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2eydcltoe.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xhysxbjd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2eudnhxud.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nzknjqav.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqupncmn.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2krgummnh.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2syoptjme.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgwcfoe.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwotauvq.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwmvyia.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2iimipyru.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2hoezelbc.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2afspkycw.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwglkuu.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2yknafjyk.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzlrtda.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2hqshfijv.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2xcivgpxf.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2bjossjna.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2stylxjya.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2aldmeeoa.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2lfartlfl.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2hpyhxdnd.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxpywgw.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2cylscrjj.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2eikovtfd.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkxdqku.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfxpnuf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2blisvwvg.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2buykuetr.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtufncz.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgtiznu.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2whpektyl.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2dmuratbu.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2abjznmnw.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2klzpvuvq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2qepcpkox.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vdowhfsb.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxvbhal.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2azuepnjc.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2casxpwhn.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxgwfsh.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayygrhqy.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2toytezvl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzdvued.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jibhcazi.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnapfur.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2shuesvze.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqxrxti.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2papexeuc.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpyhuur.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlwgxwt.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wuktobzc.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ppyrfbjr.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmyfrgue.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkseiyb.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtmsnxq.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfstlia.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2pkezzfpc.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2xxuwdzka.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xtccibpo.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jvylbftp.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzqssww.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzwbpgh.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2rsyhgxfs.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnynwdq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2remkxraw.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2gestjved.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzhiezp.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2tuuifuih.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bairthkb.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2nxaotgvb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqyfuua.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zjctujzq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2scpincft.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2cinaamul.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2unleostl.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwxojve.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2kavyzgjn.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkeeyju.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnatoof.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwzvksz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqwomjl.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lkncdqxx.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2nurhzhzh.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvjrumu.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsiihtn.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbejmim.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvypzdmh.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrojbna.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xoipiicb.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhcyhpj.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kiccefio.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ulrvglek.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bmaypztj.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jfphcpsm.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2pflgeamc.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2qpphmucy.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgslzjs.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2jmpjivnt.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrohqav.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkychtc.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2cngdafxf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cynikuwa.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ivukemio.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hfayqcap.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjklzlk.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxeguyq.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ckinfmwt.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2isguxgnw.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrklzgq.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhrzise.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pinklxbz.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ckutzefb.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2myyvttnb.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2zuuylrqg.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2taaltlvw.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2iymqbmwz.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2vhexhmvo.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdvyedb.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2plrkcoxo.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xksycdeg.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xaligsxi.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwediop.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2duhxwhhp.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lmshidek.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxjgruj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2iooogzdc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zserhlnx.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2brnjekrm.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2dehufbem.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2crwozqiu.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2utebampo.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kowbwxya.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtwonfm.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rotwpepz.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2khxqzymh.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2spdufguk.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2uobqctpr.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsuxylm.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqcbfrs.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2sqiufxnh.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtnxmff.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2sgycmxpf.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhnwzzs.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbartbw.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzadhcn.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzkayky.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2sejlgesl.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtdgimf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2syavpshe.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2isnfqmgu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2iefynkcc.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2bwcbksiy.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2owpifncy.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzyvmuz.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkqyhsv.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2wucrwlhf.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2msbzrfpe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbfbhyh.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgqngsh.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzyfeia.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pzucpelv.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2arzqtalf.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcqbovp.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2diaxytvz.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmcpkfr.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvozqbc.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2vdeiwibu.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvgbrcz.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2gnlyqfhy.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2dvotskcr.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2gnchmlmh.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2psrgvxov.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2lenbrxxg.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2tdpuoifr.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2prbkkdas.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2vdemufee.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2kfswcbdq.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2husjleux.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ggalwjam.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ncneotku.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2tavwyjvz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ifznkcli.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpxdblw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpyzost.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yszungke.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2efhpnkzy.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdvnqgq.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fvujptzg.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmpouqb.html


<!-- 参考信息 -->