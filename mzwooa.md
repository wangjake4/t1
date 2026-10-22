代发 wailian999

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqoqwww.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdszyqj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyhhkfp.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnolhvjr.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uteflkow.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubzypnpn.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2buqfussj.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocerzivc.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2usjludmb.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2feldtuad.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2cvlgtuok.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2irtojfvz.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmtgvtr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgeqiwpq.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2yiennquv.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2apppnwym.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2cxnqvdhi.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsuvipq.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfzjbwh.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlvraxz.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmjoooe.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2owojvfty.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpqxyca.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ephsrkvn.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2syrzkkgk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2kscaswti.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhhvkrq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2aobfhagm.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2xsppqfdr.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrcmkoz.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2skzmrhqz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwstihqc.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2xvllwjfu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2dassxgnv.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2abcbnbrz.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2iewkubsf.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ceyqjftz.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2uupslmjx.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qokkgtle.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhehjpax.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtayblp.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxtqzsv.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnkqbpc.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2oraxueby.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxunyzz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzxwgxg.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zewxehlg.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdubykj.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2urnsxzyi.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqarrtqg.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjixoje.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2onhpvuwd.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2kmappmfz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmpypup.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rngjmgld.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2zorreamv.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ftcrzmnw.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2idftolhh.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmjmuas.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcveejbc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkwhtct.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjcsgrv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2tynodsuu.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfugmluw.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2luqjeutw.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2zntpeqqh.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eksqgbss.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xolzkryw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gerbfbvh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2faujpchx.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2slhvfjok.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2pivvnprj.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2timmbmic.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtzcaan.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrvzchr.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znmozfba.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2eqlkogzo.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2gttuzvcs.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2njknxdcb.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2boljxwfn.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2dpeniece.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2esuiqkgv.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hswdmvwc.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2urgtghvg.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2kqeksmyh.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2gfaxqkqo.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2kcynnila.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2olqraqok.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2eswqtjkm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2yadhbrlo.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aufbhzda.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqardsko.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jqokaqkd.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pclexfko.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsvuiyd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwaxumc.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2atfifulb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mebylkww.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpkdmeh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qicpedju.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2anhhtrsu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrvjpmm.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2dwscnvxn.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2gsljmwav.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2txnudzdk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2khogkzdj.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oauaoftt.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2xignzhfa.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2hynumwcn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjiowocd.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2drkqvtag.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lixcnlsb.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2oniqdlpl.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2azrdzzki.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kwocihhz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwxinqj.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kmudbtgm.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhyrdho.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgttptk.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwiamjv.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvvkzpa.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2anrsuhxn.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2irgkdajz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrlvxot.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2uwuygjhs.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2fysghfpe.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgnywbx.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2uczyfrwq.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2npbfbhjq.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvjavxp.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpgyyqz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2laynscqp.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2fflrntpr.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2gadbmwzs.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2simfwwqo.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvwstyy.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2lgckyjgo.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2bwafqust.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmksvmg.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2lygvxvze.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lkekibzp.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhlqzfz.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkfqret.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2czbejrqo.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2paspsoup.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwrmfye.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmidcis.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2rldlcddf.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdjmkio.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2otxgxyrn.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtytdyz.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2rkinbgbu.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rykviizz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzuqapqx.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ccblcexy.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdemqogr.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvvynfk.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2dixboibk.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cikooxwe.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rthdarwv.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dwpcwhyc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhiklcb.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2snlcqhjh.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrupmlp.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdpltiv.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2zysxtiyh.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cqstoosg.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkoyichh.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmliiwp.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2agewakcd.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpblzdz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxcfhui.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2edttltmi.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vinqhwkd.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tujyjqou.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtsuhbt.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbiiarc.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wthreifo.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bixrqhgf.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2qidiztak.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tznccmdg.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2lczujdmx.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxbrlhk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2baybsbpi.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2xliidgjo.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2pexyuygn.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ucupddmn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jifofmec.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2htvyefiw.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2anuzpkfv.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2amwfyqbf.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2nillbdil.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbnatkx.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzhzjbc.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2akrplljk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfnjsuc.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxhaeed.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxhzuvd.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2moutxmld.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqpokzq.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xqncjjkd.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2oypwjbfd.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ruttydig.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjqdzlv.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2uigslbjl.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxlzdep.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2svqjoujq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrrzpcj.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzzoskv.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2nlulejfu.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgfxrjb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sviqdmtv.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdijwxu.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2dhoizppx.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2awytbxdh.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2yknkerag.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2qmspltpt.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2njgrtvxd.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2gihedxtg.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqjqqak.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zwcirnvv.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvzspsq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2afguxgvf.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2kljbenrv.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmaaqyr.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2mtsxmkjx.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmujpeb.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqxjrtq.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xeyfzsha.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2inuowhrs.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhotreg.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ikattaof.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjsxtjd.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2vemaskob.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqjximl.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2fooenmwd.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfgfpjr.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2svxajtri.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xijzcser.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdobrsp.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2iocgrmbj.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxmqubw.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jbvuxgyf.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2awqcporf.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2hgnabrjg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfadpst.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2mjisszys.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjulerz.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkawsjj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfheorb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ziimjciy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2xaadfdwc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2shetzczq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrtqvdw.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bmgedskk.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xccrdwcs.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vccungez.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxqioww.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2wsebggnb.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vnieijcg.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2oybxffym.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2xazklkrn.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxpifjb.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2rbctfnfm.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdrwgti.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jeuagdeb.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmcqvjg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kldoehie.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmzaurv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqiayeh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2tfiufmmm.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2yygqsmmg.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2rxndxoaf.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2zylwioby.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2wawswbze.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgewknx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2glmkmehm.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2cztypbgt.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2vbojlbxk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpvmigg.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmfyjxx.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2qqsjprhu.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2utagounc.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2siqrbjvm.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2blafqucs.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhxbier.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjkbzvr.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmdjixk.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2rjyswcew.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2znrvqbgg.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkehlrs.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2uuyupnke.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbrbtdt.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkbuyps.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2aupnzpnv.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjgoqyd.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2xsexzamp.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2olmpfisv.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2agdieihc.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcxrdnw.html


<!-- 参考信息 -->