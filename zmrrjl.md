代发 wailian999

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyvztam.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmutlbnu.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2reqxabga.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2axjeuetm.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhpxxxg.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxlgauu.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjhrvhc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwcplec.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kmagaend.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqgeqcr.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqfdjlq.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wlyeumxd.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2awapkdnv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dncamhtu.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2iovivbpe.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcddyqbm.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpehrpf.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnwpeiq.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2bigrqbmt.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcaqjol.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nuczmjqv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2prettugg.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkkpiax.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vaalxups.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2hgymwahk.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2floalugg.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2xeduwyhf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgxfgmb.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzwuzws.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2vwteioap.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2lbuocbdh.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2czpgufco.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2wouzkynr.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2mwohzopr.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrcypxh.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmjqswu.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2zukifiam.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrlbjtu.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2klqjnpji.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2jivewtbu.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2tdcgivum.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmtbhxf.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2owmrzglf.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxgkhxh.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2uozfdywo.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2vispxdlw.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnaxgdm.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2wychoczr.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2upbmgyph.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2irdvsxhp.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2nwejbqur.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvvvupr.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvyvdee.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnydmeq.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zggfthwv.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrjuibr.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwwbstg.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzxzxka.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfkdnsa.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qufloucp.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zldtxtkm.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2phyrujqz.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ojahwnvw.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvpxiea.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iokszvyz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oudyyqbg.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcdkwau.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfnoyzc.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eapfdxgz.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcmlhpq.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkvvefk.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkoiplzf.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xbeulscg.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2rivbhhfd.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqympkl.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xphqofvq.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdsuvdo.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2uthweiqz.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhorkis.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuadylzl.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2qloteuqs.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ovufynka.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2udsumjtf.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2sbiphlcc.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2grixvprk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvpayep.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxavrxw.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpawurkg.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2olpfsljk.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2asimpapk.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2bnomxyex.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2imcptrsb.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdangfo.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2csnfllqt.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2vwuzvawp.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2grungoda.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcfdcua.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzzuclm.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvbyjby.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2uyljieqf.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxpxjbp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzruwois.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvlnrep.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2caoehepe.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmlqmwn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cedzllex.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2mbagmzrz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfthylmj.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdzmzag.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2znpypzli.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pxudvbkj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2qmltiqcp.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2echdiihm.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2btgmeqvl.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cdasaghb.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmcokot.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgsxnvx.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsciklgt.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtswush.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2cfayjgoo.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hloazizo.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2avthpurf.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jazrdtfc.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2yraksuzt.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2errlczoe.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2wakdwdkd.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2pdealhyk.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqepdzw.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ravacaaf.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2pizpobth.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jftwfqis.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2jipkqejc.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2kkuabkme.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2vglbbain.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ufyeppqb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvoqmwn.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmeefdg.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2crpuihtz.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmhiaeu.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwdclyi.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2dystqpui.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzqudhh.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqcuqlf.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2byhzsqjo.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2grpouraq.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdypjnt.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2setbpoqg.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmmepnd.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2cimqshkr.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2epojomfs.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpfkfqm.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejoymjdk.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqjllqz.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2fbecyfwy.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmewdlg.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvalgwb.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgbzaod.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2deytmdvx.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cniexqlf.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzuczaqq.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ahellrzi.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2dknjntpn.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzlnvmd.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqeykyf.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2aznmtenw.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dzksflff.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xoknvzyt.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsheqhuw.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhftasi.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2uvcvavxi.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfjpxod.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmtgdls.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdkphql.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jiusoszm.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zsuaivdv.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2jprrvuva.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2asmpbyvi.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxjfdza.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2djmfxsgj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2dqworbwq.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmbjqhw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwnaoka.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxyegwy.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ligzqtqz.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2opkfhmaa.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfelucq.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtkxhle.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2nakqiijf.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2eixyfhvz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2hezpcypf.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmturvd.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ipihimje.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmnpbpm.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpbnpvf.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2oukifpoa.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ambzrbcd.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mswmbskf.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhacgvv.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2feamvvhm.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwiuvbfn.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2qttwgqlu.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmxubzc.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgvoudu.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wftuohir.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2pumojydw.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqbsvhy.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrwxrzk.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyclyhk.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2puwuqlji.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2amfxzacg.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2mfncjdin.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2szrfchtp.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpipjpy.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2blkbmkdy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqmfkfb.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjdlogc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zellnktv.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2hpndiegk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvvpqrf.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2pigianjq.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wjlgznyc.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2kfztnwvj.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2kkroijah.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ipohirye.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yppnckar.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2njtffnat.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsnvhbq.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bshbmgqn.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpzggmk.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjamgek.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2xrecgpnu.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2esncyelu.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfjftzj.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrhijzx.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jvixizfd.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2muykmips.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2adkhxnde.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqrymlq.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvuvjvm.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2urxjfvkw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ctklervi.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2otichafk.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2woteczby.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjkrhqn.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2mikzlxra.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2gpuyovqw.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwtdocp.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxnkdwj.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2onbxaccl.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2gjemybhr.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kyddasod.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yisutksl.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dvarjhly.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2esenmwed.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2qmroavvz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2taceearb.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2wfyzahqa.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkdintv.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2usnezgzy.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ocovldrq.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2delasbcj.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwfkuxc.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nghvihok.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pynwrxra.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjaqoux.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2shdgajdd.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2fgupzuun.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2qghhatcz.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdlbiki.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrracue.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2kpglllwe.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2omfavnzg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sapzqbjz.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmlclme.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2mywmavwd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbzdssq.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2ywneajat.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2pejgmqoc.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2byowogjv.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2eggcsdjr.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2oicdguxs.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgzptwg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjwspzy.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkzxbts.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhwophh.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbbdjzz.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwrfixv.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2gckluibu.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2lwoemldb.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2zuuberyx.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2swiuqppe.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzjafqi.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2krmgaxvq.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrmmtml.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfnholu.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzfqvff.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwlbsbm.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfqdfvg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2aljgpula.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gmeplane.html


<!-- 参考信息 -->