代发 wailian999

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbqurim.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2dyztfgqw.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nerijlvx.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2pxatyltv.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlcxuxx.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyayorhg.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhbhufv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlcvvec.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2typuunxg.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jeceunua.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wayldntb.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwprzoko.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrzvgrm.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqwoudo.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jomsosxj.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2toklllxr.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzaavde.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2wupibexw.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkucusc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2inrxmdmf.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sijolbbk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2pscfhtch.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2qqsjrwuv.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ryuhpuzx.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2lmajohfl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqsgldn.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2thcpcwjx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwxdlbn.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwymgoh.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqgyeov.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2gxsqfgjk.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2leizbbni.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfqgzzj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2akaiespy.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2agxhtgdi.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2snvdpqum.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2qfacstvi.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuonpbzl.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgrtkhx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqeahfl.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzmxxyx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwdgwsg.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2daewxfvy.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsqlhhf.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zprurood.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwbofpy.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mremyesr.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwgoxfp.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhumsxb.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcqkpyg.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfowore.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2wgafqlpj.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2hupbtxgi.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2oztkrfvm.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2krbuznxh.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzuyteg.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2itdakafm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwhooyf.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2beafgovg.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfywnrfi.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkgkjuw.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdqqagn.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2utvkiasm.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmbhiru.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2piseifdf.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrqwocc.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdksyxo.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqxjwdk.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2tszlftkw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2izthvixq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2dvizyltt.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2epphldca.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2exheokhj.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2npfplijo.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwqzppv.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjwxxfe.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrfzzfa.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqfrcea.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iimrvrjf.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2daiqoisp.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpamoxy.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2dmklpuwf.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2disattra.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oknjrzqv.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvnmzir.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2hnedvlpo.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2okavfuuc.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcvutdk.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wcoksqmn.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcanwdrf.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2igrnmmja.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvqhhmu.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2prvxkurz.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2igmhqodd.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2avdmvngl.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvzuxol.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pkytqqba.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2pojjawew.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjemdef.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2seqdwank.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tinkmonf.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwztodq.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbczgwd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvsyzsi.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2piahvlzu.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjstotfk.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhqtstn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxdmwaz.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvytuyj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vehnmnox.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2dmyabwxx.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2pktleysn.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2htsbmbww.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2zomubeib.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2btzkbuvx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ayedvbea.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2waeiyslb.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2swmmkjjy.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2hblmztxm.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjfmmdw.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsgbtpd.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2aaajirfe.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkcwhli.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2rehnbwdf.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wtyxcogk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrejmcyz.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2eitbndlz.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2hyutogts.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2buiybfqh.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2mntksmva.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nrcusgal.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2pssbazqs.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2myfzugkv.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqjxzfx.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fpevrgbq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ieimnryv.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2vgyzhfvl.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2pvsofokh.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2twrctllv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbmbazt.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ibabgdog.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2embfnsbt.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2hybewvzp.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrbabyz.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2yricmbbf.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2qshahiqs.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2wshkykcy.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2rrytrzko.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2uanlimsd.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2udwlcbfk.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwoacsz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsttsvdh.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2dtatfchu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2swylmmng.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2gwaebwry.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2gaggdklz.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2hckpusay.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwnkjxf.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2uigbhnwn.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrppmzk.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2kuuwsehy.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2libfieqm.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwmsbcb.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2chxgvedc.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vzyshhyq.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xewvjger.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kcooixib.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2paoiwfaw.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jkiaqaqt.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdivjdv.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqeddva.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlmgqrd.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cljddymp.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgffrpn.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2grmwhpko.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdallik.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbgmznf.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gbiosyib.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2argywlwy.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbeajeq.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2venjkfmz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fazzrinm.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xazxrpux.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2fnyjkhmb.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2zporzskd.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhlpxhy.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2audgeqma.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlwlmsy.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqzvraz.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2tusgpcnl.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdogvot.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2snhihono.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2vvoawrmm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqgdzts.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2prjikqbh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dxgwlirf.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqtznek.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnnxuwj.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdzzscr.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2rbavgfuq.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2unsbafdz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbtivmd.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2gsuypdlf.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2nowmvgvs.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lcscqiho.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdvkrsh.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2jonhcjju.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2eedyqalr.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrwqwof.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2yltjwlor.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ablakixc.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqwlduc.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dwywtahp.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2rufbmiuf.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2igpbzewk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwnmnrkk.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2bpokzhbj.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwmwbzz.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2urnjylgv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxhbzsz.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnmkkqy.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2teuovomo.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdpgozs.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2wsugotdp.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjfsabo.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2jfebodjp.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2vnltwvnk.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2tllqmiqi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qienddtd.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2tyifwdcq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjbbtdq.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2rpygxsmw.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlnjizx.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dfkabeah.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ojomqyyf.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqodgoh.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcqsazr.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kibkuhak.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kthegkuw.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gjegzojg.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjwiqzl.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2zylnmuil.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2dywosnug.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2izrvecek.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwalozn.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2kijqrkxr.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2pzaajumg.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vldzqegc.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2tsyiahrp.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2marjouns.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcmyvra.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2xophxbrn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqynaiy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vjafjwrk.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2amnsfzsj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2yafvubhs.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2pnusmbky.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2bocrbkju.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqhvpsj.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwmrust.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zhifbgox.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmufznm.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqjsmmg.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgtsjxn.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dmanxcya.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqrbifg.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlrttuk.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wlcgzyvc.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2oykvbvfs.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcnjhij.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2gafqgvpz.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ujejgzkd.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcljcge.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2macqsftj.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2yehiqsiy.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uivzvaok.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2azcspcmm.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2eopjfyfu.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2vucrfigz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2bxoefyha.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2gobhndsy.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxjprdm.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjaaadf.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2udqdrnzx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rabjqdyr.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2txavdlhi.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2tqslcidx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fsooetpx.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2qxipvhwa.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2wwofwzdh.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2exuwprfd.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfdttfz.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2izpcqqui.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2sxveayuv.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvmvomj.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2wtufhaft.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2kakxogqr.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtpdtya.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2bxunwgqn.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2icxrclgz.html


<!-- 参考信息 -->