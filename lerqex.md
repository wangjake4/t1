代发 wailian999

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjctapx.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmdtcxz.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2eouvwawx.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqpskat.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2czsayxgb.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2wktvcden.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tauoraax.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2acmcacix.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bppvwnuk.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tejgpdhn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2inotsqaq.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkwsbmr.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fiyqbnbf.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvamggx.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wlyhfpwk.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqizrpbq.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2manjaepl.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2pefrubps.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2lmelngwn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqrqfio.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tattslpd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgrzddf.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbnxmza.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujilphbp.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2udenvzhq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlndvhxi.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2icebxffr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypaijvmq.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2iubwivsx.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdsopej.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2smsafxal.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvpyqxr.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2minbxcmp.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzxzwqk.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xztfiuxk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkgumzq.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrzxsqe.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2usbbxyov.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcmyybl.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwpzunfp.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvlwpqi.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2abkkdtpu.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2kxyutphl.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2crdkcjtp.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcbugtu.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2chihcyhp.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2yibawqij.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nznuvjux.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2cctssfdx.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2hipzxpue.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwfmnss.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnqkmdr.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvliczj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkcqiam.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ykblqseq.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ventrkzi.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2letcdijf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2suzrujgc.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvgxywz.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2xobrzizn.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2nhoypmou.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwgoywf.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqgyvod.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2hwffzpmu.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2aevuafxb.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2snbovfeu.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2chevzxcf.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2crjuprqp.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2tjowvzuc.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2mncacrtr.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2kyddktwi.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttplfuog.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ijipghhv.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2riqmerct.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjxfsjj.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lulsmqfl.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aemcsaab.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgkycii.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrstrri.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbucwnm.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdlmxdt.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2tujfqppf.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxyegkj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmwqccn.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gipwgyku.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2odrxpytv.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2xxawxfjr.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2azcoatnm.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2feavhjqd.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjixwyt.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpmlusa.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbhezfg.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2tttkacna.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2xzuuwmof.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvcltyh.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2chpfbumd.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpsiiue.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2idascxxi.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfaizhn.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkakpfaw.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2huuqzucj.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfljacz.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2hctqqnad.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzorfdpq.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtdmrpv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2suxqvtqs.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2sossljeo.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibuvqvcn.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2nojwoepo.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtoptqrd.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvteytr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtfunrb.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnhiogv.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2oiyjyjil.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sgaujfzj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvavixa.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfwznjq.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aszcmkcx.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2hjofgfox.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2flcithqv.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2khztrggj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxzxhfz.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ssibilux.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2yfsvwrlx.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpmslev.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqddqcne.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rktiwfix.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2newvmguc.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gwflperw.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2jctlzltt.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pycnereh.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2idmpinwj.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gqsdztxe.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2smmrwyqc.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmtqkiz.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2oplezttp.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2pvaoozcz.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2novoyfzd.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2zcibxqev.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzwasct.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ayouhhia.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2vljfneza.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2xelnjusn.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjnhudu.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2pqezzuls.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2kddjpgxf.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhritas.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlzvmjp.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2cojqvevp.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2dzymjovd.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2inwxmuph.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhkgskj.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ktczbtba.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtzdedh.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2rafzrhmg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfjxqdb.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2nftdqihd.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2prdgtnez.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2yplsqole.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ncgqbpfr.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mxypmnml.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvyzjgym.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2iokumnkx.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmtevhm.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhptnxe.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2lpaevtqi.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2giraozph.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzlzpmf.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2psihwdsj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2xadhidnu.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vowaywpv.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnkafqs.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2igbfmkwn.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgmrcft.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2caunvryg.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2tncjwjdd.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxorjfs.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2emvnrqpr.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwiflvn.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmuyvigl.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2lrteasjd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqqdljv.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hccpmgml.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2fqduvlon.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2bvudmapy.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xwebaytg.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsxlckx.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwegklb.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmswezi.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwzvoht.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2lohacbkc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdmeynu.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbjmqch.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2oftbasom.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2yheyjkvh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjyovoe.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2uqppgerx.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rovxkcwl.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsudyoh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2docmesvs.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2vdymivfh.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsqdkti.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrywqzi.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ssozefbu.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2npmdijom.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2idbnxfzb.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2cbowvloq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlpcwid.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hzoesezi.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ncejhsrl.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2riuwhnre.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrgihzf.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2yooqbvtq.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2uianbpny.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtsnsyo.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmqkili.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vbitwyxf.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhyeorx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2vubtscnb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzmhqkn.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqtnsjc.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2gzsvxguq.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbxwcag.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgpoglm.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxibtnk.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2qcuptnfu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2rbghyxnp.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2yfresyrw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kezghuiv.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2slfzxgmw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cofztsxu.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2myugwkzw.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2upxwadvk.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxaqemi.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zujburkc.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgkjayz.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2onrpwrqj.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvmxiou.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkiotmw.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2igaflahd.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2vazxdhzj.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2xornnmtc.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2qsakprbt.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwlnnrh.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2pupkfcew.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2yfiamraf.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjfzbpo.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfxckdk.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fcoopldt.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2iceqwixj.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2aufcvlza.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2bqodkeps.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2tooxwped.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbnyakq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ktebvjqm.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2peedefst.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvxmycw.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqbemyg.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzjzkha.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtwyeak.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gltbuhpm.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2aqurnpmi.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxezaab.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxmppxn.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2egcdepuu.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbrxebs.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2qjyqkszm.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cpeagvfn.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2lenwyabk.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2gmsprxkk.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwktxbg.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzfdwfy.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2dghggsum.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2isboyktf.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2oygsvcnk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrvibbb.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2meboyseh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrpnsnt.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2jackgeaq.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2qzfzhpok.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2muwnnpqe.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdvuqnj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdkrwry.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2iygabqrf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cwujnyuw.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ueuquovb.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwyqspp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2enqnwjtb.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmiucvr.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqccpkq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgbbgkn.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2abvmwnnl.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2fiuosyug.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2eutwosrh.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2eehjfavm.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2eokdoudu.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpbimvc.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2nyiozvok.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2oupnarxv.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2luuiylid.html


<!-- 参考信息 -->