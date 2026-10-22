代发 wailian999

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ozoosvwb.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgtylju.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2memtxizp.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrskkkdy.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2itblwait.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2brrbvsti.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gxoqtxtz.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2unfoajqc.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqbxtwd.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfvktgd.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2jgndyzrn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2wfsujjxd.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zxaihuez.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgulctoz.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lolvrcne.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jesfzntd.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrtzizw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmibbwn.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2tldptauj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbueqze.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgzfazg.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2gnepwgci.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2qyukzxji.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcheobo.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqglidy.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2oselculn.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxashhn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gijjwznt.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2hxsfiavd.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjsdbre.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2axeautje.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2scboibrn.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2cymkzymw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdufmot.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2iitxrnkx.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbxqeec.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnoqfjw.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrcrrww.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qqryvpzc.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2iutdkkop.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2nzinnjjo.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbpojbw.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhtvzlp.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2sriuymhc.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2twllbzpv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnllnkq.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2hjqsftda.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhyztvfr.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2fzsxwpxv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2kckgwqpd.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dplfjwsl.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqhxkkd.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqhilus.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxemzvu.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2llageiib.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzphoij.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fsepuxwi.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2snixkhiu.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2swiuvwbj.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mznztvpz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2tdcnhuor.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxyptzs.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2enrgwhem.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlabitec.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2sasvvogg.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqtjhye.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nifcumso.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmgjghe.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2steunawj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qiktcaum.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpjucwi.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2govukgct.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhdjrpn.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrwcdwl.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkdcofg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njgyvaag.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zigjptdb.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2taveerox.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqkvetm.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlfcwfk.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wzlugoew.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2eojmbfbv.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdtgerj.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvidtfs.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2kondlcth.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvphkie.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvmdfmf.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwullwv.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2flflaxax.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2mljrbubx.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2azmompfz.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2esnqnzht.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2espivnys.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwqhrst.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2wdlmxyac.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2syhkbbvm.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhiryfl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2scerbthz.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwcusro.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2srjbkqwp.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2jugtgooo.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbfmjcv.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnxdqoc.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2rguawpoz.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmnhlgx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtopfkvj.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zmatwdyn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2babbijye.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2nfezmovc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2txgmerpc.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2goeanslc.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbodlmbg.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2qydxjcwz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2oodqolws.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wojosaaa.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2wlduxkqd.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxvsppd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwznhzwl.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzgjffh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkqwrze.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2euftxfmk.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxcrgrar.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yusipjhv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2gmyflzst.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdpuzwb.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2kttnvbnw.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2idudlkml.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnhqlvt.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2jkefdasg.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2shcccsmr.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2vokqdywg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlxjzax.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2amfmljsi.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfuqssx.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ihohfngn.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2uspuhins.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2otjvarqj.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjoawir.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2bgagdaaq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzwuszy.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2soznfgev.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2bmanokka.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhbnsia.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqyolbop.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2iljnefvw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvqmqzr.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2swtmncct.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2hyddcfhj.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ierlvhcb.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqrqmow.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxnluoj.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmatesm.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwzcgkk.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmnmsui.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2yvryifla.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2apfxmqxs.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ztajwuxj.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2abatqtyd.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtpwayb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwjffzs.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2efmeazpm.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrkback.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpiejra.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbsqcct.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kylduyvv.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2unssnytb.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kczbvdqn.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfifeaix.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbkitko.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kggackjg.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2todmeciw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpukhyl.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2wevgaqip.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2yjesxhge.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2eearcjnc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2vdswrzpj.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2flqqaqkl.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mrylobim.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ulibssdp.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmibszuk.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvoeasi.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhuqvcvn.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmjerkc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2meucrsva.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2hshrkilf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqoeitsm.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2fafhzamm.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pearpzhj.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2xizjmrvf.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbexzui.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sviyajzz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2idmhzzkc.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2drufjwwd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2tytauyqg.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxnqirt.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxruxns.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ignbocsd.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdfoymk.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbojowu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2funislvf.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2oszwqmqs.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2wcecpsqf.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqzolbj.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2htrzagsu.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqqfedx.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2susdoszz.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkyftva.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2elbkpttg.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2xqyttjcn.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrepvdt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2bnoquztp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvowraa.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2djibcuqj.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwtmzst.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvzdgqv.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwfoqib.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2gwoyetga.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2atvaljqq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfbzjco.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvzuiab.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2awtmeyaq.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2cehqftue.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzeusnp.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmjxkzv.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxybozm.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2btdovuwp.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pnixkvfb.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bajmsjmv.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ushxejan.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzfnioo.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkmfwgg.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzydnwh.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2fyegldhi.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkotnoy.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2qwazeruf.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdxhkrg.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjelqlg.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfbgzyt.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjuoihk.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2msdiofpl.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpouebw.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqzfcyg.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2opakzuxa.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrhtjor.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyvdoas.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2shadcktu.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vnoxdigj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2kngkuopj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2bufqesfv.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2sqedzjqh.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2bkllydos.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcblvgs.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdpwdmi.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2pxptuess.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2sukzzdvi.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2znpdkrqs.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqvqssp.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2zabzkdqo.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2gepxgegv.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2htfzuvyj.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2tqoarmso.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2bdngfrgk.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbamnpd.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwpcphr.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2islqnqwq.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fhyseinu.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2kncogybe.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mnoingbc.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2etswuozg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkqoqjr.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvfhqsp.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2eqpuwrhp.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjapxkw.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ulrmsrwe.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzwyntz.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2fdttwsam.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmfeudd.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwvcnfc.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2qhobarsk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpvsuhc.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwqpscb.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2pihilwea.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2stjdpula.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxxlkdi.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2fsblhsod.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2umudnsnt.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ybynikek.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2uncymdmb.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkrofcf.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxofdvj.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2kyiszxhc.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2ermastqj.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2vqiiolyp.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2gopaoojp.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2hildxzhu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2iyihwkut.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2oftlfnzj.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmppavd.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfbtpij.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ggrcmjtf.html


<!-- 参考信息 -->