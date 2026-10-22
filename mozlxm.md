代发 wailian999

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqcrmwn.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdisceyr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qcksqfpm.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2osnpefrz.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdxawtz.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxadveg.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhhzfey.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqavzrxl.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxzdenr.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2wvpnzwgj.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2aiyclkvb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2rosrbqwx.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kiajeesi.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjezgpf.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqihhen.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmyzutlk.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrrufyz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxaousz.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmnjlqq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnuflox.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ibggpxhh.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2skijbqaq.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2sfowrayc.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2xlktbztt.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zammxzgn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2cbksoehb.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yrhyilqq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxinmjed.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpzapbd.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcpqfos.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxcwevn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2exrtwwjk.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2hpisroaz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjvdykj.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2bduvvbto.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgdhyom.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2kcemhtam.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2qgsxzxcn.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2opbteqta.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzktuwvt.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2tibblkgk.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2iwuclagb.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2urpbxfeg.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2usnzkqau.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2mylpvmvf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdldmeh.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2teikzgjz.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvggqsdk.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2oydtlzrr.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbcgmig.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cpeqnhwi.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnsqsqm.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbyjhcl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ueolftrz.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmanqcl.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2mqsemjzy.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmlxwbk.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2dklxwwgd.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qnnpfmvj.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxumdlyz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmsqdqh.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2htcxrzaf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2zeguqlph.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgiuizi.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2aneurydd.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsufybwl.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2licsyhvm.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hadpodvw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pyygvwma.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcunhgq.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zijzeuhu.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2vosenipz.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmgiduv.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrsldxh.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2safcidmz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2syzylfsq.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xjsyhcxs.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2cntznauj.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2sphvayaf.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdmbfhe.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxqslga.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbhgtwz.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eakhggib.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2birjrbiq.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcefzby.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2scasevic.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2untujuge.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxiflner.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jztpgcpf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2edxdytmp.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdoqdmi.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfcelds.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uffygfnh.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2inhenmca.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvbrbpm.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqddvbqe.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qohocsmn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhjlfsl.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkfnbsz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2aipevyac.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wogtuniy.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnopcgne.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2zajkscbq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2lxufgrqv.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2soxfqash.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2fuszhavu.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gplrzqvb.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzgvtxm.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2qmysqkir.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajytnzby.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkvqzty.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqvqqdg.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2vovufxqc.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2owevieaf.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2picdzrqf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrxcwjt.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2krnvhoal.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqytlzhf.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tuyxeplo.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2proixwrm.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnvgfmn.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2trpyfiit.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gbftgzms.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtjyiam.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2fatenquq.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvevcpeh.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hboipdca.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2nycvijbf.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhwhbjl.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2oemhphkf.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2quszjmij.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnhmgbl.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwrnomb.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2hscijmov.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwlyaoz.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhzsrsi.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ziiqtodh.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ttocoudo.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2imzfnavk.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2guragnrw.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lzerfaix.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2mgclufah.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhsopsj.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqjzcdq.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2agvnctca.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjyfdhf.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2siufcfgc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ajefajdk.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ecogtyzf.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2moyakxpu.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2anoxaqbe.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjjbedt.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2txiujjlr.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ushobhly.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvkixou.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrwrray.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2uaufkcpi.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vdayyoty.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qimkrryk.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptrarnuq.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsizigm.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2umogwuko.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ceodogzf.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jiiwvncn.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvrdpbt.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ehsxwbht.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xpniohju.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukeinpxo.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2wovtdozu.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2bholuzhd.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgcqiru.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbjkyvv.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2baqwvwtq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlumuci.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2toozrcwr.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxldelm.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsrknio.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkmpiwl.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmbqaaa.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhgjzwr.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2udohrupw.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzgbbaf.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxozvaa.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxqokpe.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgqjhbn.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfonzlpg.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2mcilgzqr.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2oppeerfi.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ytryzxhm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iamhggez.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fosytqcb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgzmuzh.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwfeljd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsrnmgb.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhptnmu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ffuabiav.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrvgcsr.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxerhqgc.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2htfsamhm.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxwhmpb.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfnidcd.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyrqphl.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxfvhdz.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxkmrlf.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2eusjkpry.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgjvsxx.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sudbndrn.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gesepmcw.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2aqydnaaf.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhewgyp.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwxezqv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mscqurch.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2umijetlg.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2pezopwap.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2mytujpfq.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2lmystmsm.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxbqwab.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2peazxhmj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2nduenqdg.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkcdbng.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nflzpkbf.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnsgegj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxrwvui.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2zmpkhzwg.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkcrpai.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkekbvh.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtyjepd.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhsxjnp.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zexjrxlt.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbzbjgh.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zptvmnya.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2okmjudcj.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qhaejalo.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2fttsspgt.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2aelmrxtl.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ufklcvdm.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtgkjee.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmchkut.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrmfwes.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbdskcd.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2espdqyax.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ozywryth.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dwemgiwu.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2gnorhknw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfgekav.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2pjveifov.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2tjanilpc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2tbehjjho.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2rbarqebk.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmicouv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbsppwy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmeivku.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwjfslc.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzlnlex.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpznbov.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hxicjpta.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2npdiiwnu.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqmaxup.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2cagrhebk.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvcrjqs.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2lenppmct.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfioywf.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnvkayq.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpkxpmy.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2ovlocqoe.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2owvreadj.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qfuotxze.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qnalmvuv.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2fubqttxt.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rmizvxoj.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjzzslq.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfagnsd.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2zpecscuo.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2hcevmxyq.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmvlyeq.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2iukidfnh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zrcwaean.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2oaipyyyy.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2katckxje.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfhpuxe.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkgnxxx.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjvacqi.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2curgfzup.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2foubshkg.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2shsbevab.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2poawfwvh.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2iedbirko.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2sinuitvb.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2hiypckeu.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqhsjrb.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2oyonommf.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2hrsfxynw.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2ujywlwze.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkxjkri.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2yuadtcgy.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2leuaaaha.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2cmlewbfj.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2gtchnati.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2scyquvab.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ydslqtta.html


<!-- 参考信息 -->