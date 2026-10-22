代发 wailian999

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2kiirwaev.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fggdzfeh.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzergos.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2nwomqsbf.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2azdwnwdm.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2miiqmbma.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzzrbzx.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjfumkl.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2jajshdpj.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhtsqnh.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2eakxyhcc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2aynjffgc.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2apuamygu.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfzlhyf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpqfpvi.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjdhjpd.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2grbixpsj.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2poknkicv.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2coprhcsi.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ameibypb.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2chxtptyz.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2zhecadvo.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2qwivvikc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2dfctccfp.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2aecyjuzx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrkxirz.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrapyrq.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfzrvob.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2uetoqqrk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgvehpe.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnhxhcq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2prxeuhxc.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2zpesrjcl.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2momuwiot.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtfvlqw.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgysmdp.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxxoyhe.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2otrpovqm.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cysdbhec.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nagvsprl.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2pbspqwzq.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2isoerexe.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmiykiy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnypaxqk.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmuzrgw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgisyds.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwicqmx.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2xdblygyu.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnwdiko.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwmzvlf.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2uoofgkrv.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgokgcz.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvxxofd.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2jycdceox.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fxlhyuiw.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2kmigxgpf.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2dniffyie.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2lztrgrzg.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdbkyun.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2jesdjqva.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2jrptwgnw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2owzajiym.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vpydevss.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdyekrrn.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkhzagb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fibjwpnz.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tznhuqet.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2makilrkk.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jxoecfqx.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2qezbkrpj.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zkcyigxl.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyieyysf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2qesjbmes.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2sfoftztk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvtmtmm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbyrigwu.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2quxwksyq.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjogngh.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oedsrgqw.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fezmkcky.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvwrycb.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjeofemd.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xezwygsp.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2eerdeuue.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhivtok.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqpzzjv.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hlisnadg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqzzwrr.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkbiwwg.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxcyejk.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwlqctj.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbbsock.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtzrjju.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuesrhen.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpyxlhf.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdtzkbn.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzytdca.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2mavjntjp.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjujncp.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqbmxgq.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxnatfu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2yotzjiqw.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcdlzcr.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2enheonub.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mpoqzulg.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bevbmllp.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvkevuq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyrtuizy.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2plvqxdhy.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxoeutdx.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2aysabgqa.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkpynef.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2opygpzjr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmaoljo.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2yofjxrug.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjpgphe.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcvrhbr.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkcfekh.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lvocvpua.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfzdpeo.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2wyoeuebz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqgsfap.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2fymerczz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvjfcyz.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxljyud.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2yodydstf.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tenbnzyb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsmudad.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2toyimfti.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfhctub.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xjneccuo.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2dgimumaj.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzqjyzo.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2avyqulzy.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfpyjhv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2bamjhyff.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2izqexrxd.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqoxxwn.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cacdjfro.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2anhrjbif.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhbqtfc.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2nerezcno.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkgmijb.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2avvsuvjn.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzzxvhy.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2xskpzvki.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbroomo.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2qfheffee.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ylajjvar.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2cffjuegt.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2onxbjsub.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2chdqhbds.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2eetlpqca.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2etcklpov.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpkpmpr.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2edrsflpn.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2xhepaawp.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2iivdbixi.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2flcfzgrm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2mxaevjdi.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2koxhkzcg.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfteyim.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2otshgiin.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2addujcta.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2altqygph.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2sontjydw.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfnwnjw.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2akxflkgm.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ceblpjbc.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vedphjxh.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rzitonhd.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iatiweoo.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfdwwdo.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2rkoclmui.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2luhvoshj.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2strurriv.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rakneskf.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrnmqgb.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2newsvaeo.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2lftvvdst.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxmeebd.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbcpywt.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2swiogljk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjxpcek.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2snrlhaic.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2oihesctb.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2llrhxgwj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2sckbfare.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcfryzs.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzbpwhz.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjitkyk.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvryghz.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wzahtslg.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2efvstbil.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2crdxevgq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkimkdt.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2actlzpzf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2yeepeuur.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2gyafbakv.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2habjycly.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxrpxue.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bapizvtq.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqmtwhu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxwcqoc.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxgkrfa.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqbblmp.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqyiqhf.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ylplsgaz.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhndyou.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwsftrou.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhkslvs.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrarqkv.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ullbtpdv.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvdwvtb.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2rciwmqfe.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2gtppbsvx.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2zunghlhz.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwfedlg.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zzivrurt.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkcugjn.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2idoledqd.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzjsgma.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfihpja.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqubotx.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqwgupw.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2npgfnejp.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2odzctbwj.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2hghfyyln.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2svonsgjf.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2vjstaxli.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2hhobsfhj.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxztiqp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbyygrl.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfrstxd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2affdaqhr.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2kqyghcuy.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqgprtf.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2adnztsmd.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrgufpt.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dpukvgep.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qfauyzns.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cncjznvb.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfdmkhp.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2oqefrnqz.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qceqtomo.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwnmxvn.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrybgba.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2fixlhtkr.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2myvtrveu.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2boarusvu.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jayxstwt.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2koggpsvm.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqauhno.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gqavjyoi.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwsjzcc.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2nccjvkqp.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2agpumkyv.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rimmxpco.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2iqaejgme.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbwunjq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfcpigv.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2yvodpvdo.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdnbyut.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjfusbj.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbfswrn.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2upgxnydt.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxtphrj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgaljgo.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pewvkpmb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmjwbfa.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhemthm.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wifrpyxc.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzvkoho.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2bwcccgdo.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2syocfhfu.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2dnaknlbl.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2mjddwyvh.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhkztyy.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlqzqrc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ycyfzieo.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2encmtpth.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2noqezvrq.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2apvniofc.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2trusjqhh.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2deqpbywu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqsajjj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsuafzi.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2obewxsgj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2evzjuatf.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ucveayqg.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2edrsliyz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2obodadct.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2gnemqffw.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2cgijduhd.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2iqnzvtww.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2lqffkwgi.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2idkhjfav.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2dbuowijr.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2kknomoyp.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2gaamdzke.html


<!-- 参考信息 -->