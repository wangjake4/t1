代发 wailian999

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhokhvi.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jlcvrqnu.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qovvjduu.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrydkhi.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzhkwne.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfpkrmb.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwgtigb.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnfcxem.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2aajrgiwy.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmymcuxt.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2spyvnjtj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ynelfjaw.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fzevljhx.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbeeideu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kzydltia.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpsjkxe.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnvwarw.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2midieevg.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2yijkfwnq.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpjamlt.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2khzctzae.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqcdexj.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2spqjcukk.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2frwgjtzd.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tchvflnm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzkfzre.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbodbfw.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrseixdy.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2xzptxnct.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2njwpyxaw.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2awgoyoea.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvuzcrl.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2owrdwybe.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2tduqqyse.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2zkyrwjqe.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2nytjtjxv.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kflwhfiv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2kndkdzpa.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgowzcd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmxmrhx.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2umyjdvzn.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfeilexy.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ugctwqzi.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2wghjntug.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxprnkd.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2fosqwlsa.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2oovvjquc.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxrcnmq.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpgkznf.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2xjurjuwa.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2akxqsohb.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztaomldj.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtlcges.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2uffazsir.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2peyjqaxv.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2wudzvosf.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfwbfzo.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2aeilbopn.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjhzxvg.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2slyrjlxk.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2stwiwuav.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2obvenask.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kknoivoz.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwwdizt.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2eluxegba.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zomdimmu.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qpsogjxh.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2duehumxj.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ynljcrxh.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2oceumpqj.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2whclglcm.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2upllakdp.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxcjkvp.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnbswcj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2yeapguie.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2riicvtte.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nhuxkopc.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2eisbhxfw.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nropihet.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgwenbx.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwkhnxi.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvgfnaq.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsbysse.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxosqne.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2caiccufw.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ysolmrdv.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlilnls.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxvymmc.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2aeivoovi.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2kyizqlgy.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbwmwvr.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtfgshr.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2qeofzxzg.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2blnybyxb.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dczzkqat.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnyemglt.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhmhtfl.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2vslgdymd.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxtnkby.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxcmrbu.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtcfmzr.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2tlyyufae.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ssduprdp.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdkrvgs.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2chczydts.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nofhtzez.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfmqdyb.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxvefdy.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zencrseq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzyinpf.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2pzstyvnj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzrellp.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vhllxgnd.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbbjdjt.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2mggclunr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2sabunvha.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvwxwrz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcsbfth.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gevegexn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2fagwulrq.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvbxjzg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgrmitr.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnezqzr.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrxhghu.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxlhtwd.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2nmaacdsw.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfabsim.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwaprhz.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hihdzmnr.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvptrwzj.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tfeaozzh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2sdynlkdw.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2deoviiwb.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxitscah.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsnhyxo.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2vkahrden.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2opeuilsw.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2llpuqtto.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrwgcym.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2bthpubux.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcrwity.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwvvxqv.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2watodyue.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2blebdonf.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2qraembdq.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2fossjank.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbjlpgc.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2oljfogwl.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2glbnlnqr.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdpdbaf.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdtpsgf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdqribu.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjobfrq.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ysiqatrm.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ekuedfbx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcowccaw.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ohiawrfx.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2pkuqxihe.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxptgjm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlxicjw.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2huxiflnj.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2vqruiytm.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2terwhcbr.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgxbizq.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwmzrpx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2yeabscay.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2znaejpta.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgjqybh.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxtypzy.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtvhbal.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ohiyxrre.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtkmsre.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qmlxrsxg.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2afgbvjxo.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpnjfma.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmibfea.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2knsfoowr.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdsvazb.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zncegygh.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjykfex.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmvswps.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpcobws.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjwngjh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxqlnir.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtqkpxo.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpnbuco.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qapnavkh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbbyafy.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2hurpozix.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ukabbbxu.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qedovgmw.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpotowi.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfokprn.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnsfpav.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfqitxe.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2pufmhags.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzbdpzs.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2gekupobu.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2bqiyrqsn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gybutnxc.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ieeitjrj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjztbwt.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2szyvublf.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2jdsuolwi.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2esxevrqa.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdpvjnc.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2vvechdfe.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ghovprye.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2kscxgzmf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwasurva.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmlovkp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwuulvb.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbjorfm.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2jehgtuvl.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2njrwojse.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmfovbh.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2mlpfahsv.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zusxdzva.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jebzcqrm.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2llkqiaaj.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmcvubz.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xsptsfnx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzckomb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2irkpyppq.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2doeuemuh.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhdktnk.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfeykgw.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdceope.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2psfuqmvb.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2lemgtqfj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2osspsfwd.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2duhxailh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2txjfpohl.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2uoihtpdc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ihseccve.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjgctrk.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvzpodw.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2tatnwjun.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2swlqgvxh.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqauvyy.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xshsejzy.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2teelpodt.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmzjrln.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgfjsnv.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqvxxoa.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2rheypmme.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxrqppx.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2tlegggci.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2busearxp.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqfjbvs.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vjiezwlr.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqpowld.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2scynaliy.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zplemgqt.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2yauldwso.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2yiuusehf.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqduitn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2skyvvhvn.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvymfnq.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2qzoidetn.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2qpslvsws.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2atsykvuz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2olnbpjah.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtpejgu.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlxybyl.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdkawat.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2spzqtrmb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2amnkxhat.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdmbbly.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgtsxjp.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2sinqyqyo.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhvbbrg.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2bigwsiga.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgnpcjg.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwdajfl.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkctpki.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2axmajfsl.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkaxwzv.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2efxysbpa.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jixyduex.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2wvovwfby.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2spesczlz.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2zotoxinf.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfnbrkv.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2xizdievj.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjpxhkh.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkcavid.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2vjychkzu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gsawwalp.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ktemicqz.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrjpqkc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2apxlloal.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2lrajmcpu.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhkazyb.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2vhhaxjzm.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2qzyvemyk.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfsqxtk.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ffojpnck.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdgadts.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ouggvovq.html


<!-- 参考信息 -->