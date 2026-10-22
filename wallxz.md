代发 wailian999

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2kocrheee.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxagwkqx.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfrlmvh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmmjyib.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ewygnzof.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhrbsnb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlfnfyv.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnpofwp.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fveqgvyy.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpfisep.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hajoksax.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2irwrvuki.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrfbozc.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwukimq.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2uiptslgq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2xuoxhlwr.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2aqztbnai.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwizbzw.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrlrwcz.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvyoden.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmispjy.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbfglmw.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ujalecls.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbzbppc.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2oupnmtvf.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2wngtrrix.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbzkbtz.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwvkpxe.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qtyxqyfx.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2pinnehxu.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rrydcccg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnuqfjfu.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2utdvwadr.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkggyej.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnuyzjy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2maxjsnrx.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2dbpzqlsg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyoduch.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgasrts.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjbccrt.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2muyyzkxr.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgvushe.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjnzjrn.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2eckbzesh.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2bifytzew.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjndphw.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pinjdony.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2uenvjuzo.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2npvkxcuz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2nnutlxyp.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jhpakfdb.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsdjzse.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2pykgwxlg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbztaxt.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jiylslea.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2fihcolrk.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2nglncadu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2buhcxdge.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2cacrmych.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2wfltrrvy.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvkabcv.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2figegenz.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2uskvtylb.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdgooxl.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2tdrkihte.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2jdydnsyn.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkuywyh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytflcpgi.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zrcunhnv.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2kilgrqkk.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yirktdyk.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdrvlkq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yqowcnky.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkwqydy.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxtpoym.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrspnzb.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwizqpk.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwatnfx.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zhibexdc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdcifzi.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bctnjalg.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2khwohevv.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ntccfazf.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dharxpgb.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmicnvu.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2bucslqia.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lxitfgbx.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayllqxfn.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ymrnsbza.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkzzasc.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2obrjujyh.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2izujsxds.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqfhtns.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2aunfaoir.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vndlprpq.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2awmudqzd.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2imcgfzxd.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgtruav.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2qbopsvxr.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlpuuwr.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpcnzxx.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfqfkxx.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbnnmwz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lirjmhmy.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ikobursf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfcszzr.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ymppmard.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtyzhxb.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrjgtte.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2zypwjcgm.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfwjcuq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2weilxktw.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ehumxvsz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqiorcde.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2qexwqvsv.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlqhcja.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbzrsrs.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvflczb.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2klflmsbg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfqgpms.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2esxnfnry.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsyoqjat.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkhvzmt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2anzsmikk.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ouymdwzj.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbnvbrm.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dbsesvjz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2atfcijiv.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzqfxci.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2soagdvha.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2obklvhem.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2kxthsbxv.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2oeuevktd.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2guuttbob.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2oajcnqaw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfdlzve.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2romduqdy.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2hltecsgf.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpdxocg.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2rnsegqpo.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgplppx.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmbjxvj.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzvnglg.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2epuziopy.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2oplfpnif.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2vhexcgjp.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgftopx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2apsgmbod.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvbigbs.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2wuuwtfbb.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2yakdqycm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkrggzx.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgjminc.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvxjbgr.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ypuhulby.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdjwkpp.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mzyhhnjl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzqgtjj.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqcdrcu.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtfvjne.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsjxiyn.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvopfcy.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdbmoak.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2elcyuhjq.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjpvcki.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2sbfihtxj.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzlboas.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jggiadbf.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdioklm.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkbdygo.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ljheypdp.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvycmff.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqhhvtq.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gssrztln.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ywptnkuf.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbhtgng.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2azdgdnlb.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsodjdt.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jbusvwgs.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2zrewlpkf.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbtdxnr.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnewten.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfzpfox.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjobvieg.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cbboljph.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2hslphhhf.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2hikqtveo.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2fhydibay.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwpbygm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkzeeyq.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2uryatrym.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ermgbwug.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2mszjkexr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2oofaauvf.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cenxrvug.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2dhadjxzd.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhyakse.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxameau.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgughes.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2klvuphkt.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lbokwgqc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrprjfz.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcnixsy.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2soybbjlr.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wfztcddq.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxtharw.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ligsewne.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpsgjcp.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxgidqe.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrofeyj.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2esjqwhut.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yikqqatn.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2cxiapvut.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2sklkdfcf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2hshqmlwd.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2enneenyc.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2khgfioxz.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2qufnuhaj.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2dljqgwir.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwqeybb.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxvpvov.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2evsokbtc.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2snmdaxwf.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrbqqct.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnioyfj.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2xykltgtn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnuafjo.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2xgchpcje.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmwurjr.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2blgedhuv.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wgguubot.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tuupbvcf.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2snmqsrew.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2owhuuhii.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2oowozjnl.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdahxpl.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2cslxpccx.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2aypddlhy.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2usittxby.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhrhorf.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqwifvo.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2jyauajei.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jllmhesb.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnbtcll.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lwottbhy.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qvivfdys.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ujryfxor.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzjxavu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrdjogk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhbfaww.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2uforahfu.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2egsnwwyz.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2vmuyfthc.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2dlufbnpy.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvfuasn.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbkbtsl.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkofvum.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnajhhj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwjzajp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yutjewdc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlhmhwa.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2slbodrha.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdrbkua.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kpuoqpuk.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2hccejyua.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2imnksthb.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcdwsgf.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgncczj.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2wannnqrm.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2efwocdiz.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xrufdlxh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uspphhmq.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2agqowasz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zqeypuue.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlwhsel.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkwtcvh.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2ygaolyul.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcgncbm.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2golxostp.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbxugjp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdfczqu.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxsdxsq.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2iraejohq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sflnfoxx.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2pvucniqe.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2bvejskat.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2vpivkizn.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2jflvzwse.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2phaugmeq.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2brvxxuxu.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2rybivoxv.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2tephkqng.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2aiuajyph.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2uewrklho.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2zaknypwd.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvofxlu.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2ombpjykf.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2krvftzng.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdbodde.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2zvclfpcg.html


<!-- 参考信息 -->