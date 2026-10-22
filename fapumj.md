代发 wailian999

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfemjnp.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2leaodamn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pnakravy.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqxutgd.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pmaopfwu.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaiyppyj.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2oncgocye.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2arjghvyb.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2skwqlekl.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2rljysfzc.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2uprvetzx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2inibfhnc.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnbqkkd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwlaogw.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zfuutpmf.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcapixk.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2frdntjmh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkfbgnv.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfnfwcy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfyznsno.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2clqeaemv.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpfrycg.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmjdxxg.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfmhqlz.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wdblzrug.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2enpvzrmc.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2durmyzpq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkwaffa.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2hofunboi.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2fonlhbwc.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2auqmvmhs.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkokxwhx.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkozmod.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2kligbksn.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2yikshcca.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2asnyviwp.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2dsznqodj.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2szzzsneu.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwrvzzt.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwklkjgr.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ocpytanf.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2pixfswrs.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mviuzmbx.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2jiipmevi.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwkehja.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkwbxww.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjtrvrb.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2xctggxeg.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2wldpcyix.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxryjfb.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2spnlbwof.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2pogwapic.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2xbgqukrj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmgefpq.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqojida.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2qzolmwyj.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cofntvnt.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2wrskafue.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2oitkvvda.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2srelhlcq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2uobsbhdy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2eytgerxb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpjmpzy.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2neuyfyie.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvymgkq.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrebmtuh.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnzkzry.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkxstlk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lrthtkcg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iadiumap.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwlysaq.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdmtdtt.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrbgfjp.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2fecgapvt.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kezrnmof.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnzipfw.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2frhtasls.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqqdebj.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgvfjah.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtoldlb.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmqsgrh.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2xftzzdhx.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2evnwlvso.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfaupdhu.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhbbqjm.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2prhclafl.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2axfsskgi.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2uibvpntd.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfamzmp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2rxujuesh.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ydssaxbf.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvluqdbq.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqtnevs.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlqpymi.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2naxgvydz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2eonklbjx.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mszcajno.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iiaijkrg.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2tibwhtpz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxabbgex.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpfdyhn.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2powlzsck.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpsyvmz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2upukyxai.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2seqokrnk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2znycxlrh.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxdikmu.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2imudtpkl.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2wurwiokh.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2efqitbsy.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpauudz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2njltdopi.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2fankziqt.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2giahsokj.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2plyhcvay.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2myeetstf.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqdefpm.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfnhoqn.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ozoyfweh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2bxcofcli.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2igxblrfo.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2aajyfosv.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqxynnt.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2owfjjvyl.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2yztcdudc.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpyxetwh.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2olbllobi.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwstvho.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2chqkywtv.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2rwexmwoo.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjbapof.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2uukgxuwg.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2aptjxmhj.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgxzova.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jcaevmoc.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2aziwycjn.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcysxam.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzhbati.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtgqbko.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2nuuzosgt.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2apmvszcy.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxfvfav.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2yfiimvfw.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugcvtxqq.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2eslqkofs.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2dmriqodg.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkqkykg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2rhavlcbh.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2oyrhllzl.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2wszqswyp.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2dwplmuoh.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2mreemzve.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhyeezv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrilflar.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2uvecnmpo.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjclipo.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wxaqnluh.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2tctwwaxq.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjutkeu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2smhsqkyk.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aoblfwqh.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrgdfdl.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kqgbrezq.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dypvqpde.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxiozdi.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfrzmaa.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ptrqvklk.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpetdwyx.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2fanjiesh.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2cyoopkde.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdxglxf.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcytndu.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2utkkmwtq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jpwlsopc.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjciirb.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2gdumqmtu.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2lnotkdgu.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hwiryfev.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2naynwzay.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2kftukbqd.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfaevea.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2jelvraqk.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqjztfo.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxorxbd.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlcjnmz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvpmrxc.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxdkzme.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bjflqcev.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqjzjzk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mswboldg.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpfrjqr.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2vumbwkvl.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgbjyav.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvkmptm.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2iglkkgsa.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2cesqdsdi.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqktibo.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2elnayptx.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2waavwetr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrxctum.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2agmuefqx.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhrzlqc.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhqfutn.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqjgojz.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhespjm.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2oshaeoyq.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2onafqhpb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2veupywsf.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2uksrgqvp.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzigdcu.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2gjassusq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmhrsfb.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2yrldqecy.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2foslxsnr.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmwlbja.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtorpzb.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzgznsx.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvwogxa.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2rltzruza.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2rnznomsn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2irjedaok.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrkqyeg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpsucku.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2qzuncjso.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmvceqg.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rskxsohg.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rgikfyab.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhwhyfs.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vifvjhnh.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vptlduyu.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbfctnt.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2glqbrzci.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqpnqwm.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2sseictri.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2apyvnqon.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2embtxwsy.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2immyvyps.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ihluoevj.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2uoupsfrl.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdkrevm.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qonnydns.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbyfpxx.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2btcheilm.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ziuxkpij.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpjyaby.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hptnldzg.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2oesaspxt.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2yfccmekr.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqqbcie.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsnudxa.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfklhgy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2hqspnssl.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzxozcd.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ykicynyw.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhgatmz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mibiflen.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yaafgcka.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2pguetmfh.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdmbgdu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfaugzp.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2htnkohoc.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2tjugosmk.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2japnlicl.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2yifcogkr.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqzsiiz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wykppvif.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zswsocst.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwoezkw.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtnjliw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsbuvnu.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2vvohvcvb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2eikyhuqw.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2rwzdggfd.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2illlvfme.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2grzuprek.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2dguhgfbc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cimlllku.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2rciabzck.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdftjei.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2amjglyty.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2emboagga.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlpzhoq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwegmeg.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2vntaqgzu.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbkurai.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnenaol.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2sqcntdvz.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkjbrhb.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2oszxczjh.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjbbzsf.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2betlcsuh.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjdkysu.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2wpaoeeso.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2cgcpthwl.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2aulacthi.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmgsxvs.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ozupinlg.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2atqyjvzt.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2tlspmvsg.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzspfwi.html


<!-- 参考信息 -->