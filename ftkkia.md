代发 wailian999

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhllcrm.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2txhtloyw.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rkeygywf.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2yamssckx.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2mommbiut.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbcruzr.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ergeqpja.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2agvnfecm.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2npctfykt.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pefbpwmt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2oiiljocw.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ughddcbz.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbqiicr.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ceduyssr.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwmzzpx.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2goxcihuo.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2powjyryu.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2utvkhcqk.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2edmnkxgx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2flbmdwov.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tllkomhu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxuaouks.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhshrix.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ythbiemb.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2fdremnbt.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2frbqcrjr.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2mbonlnod.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddszimvp.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxoigeu.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjocxpd.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2tsifqrdn.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgdftcb.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cflrchre.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2tqoiaizd.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2smfdmhbq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwslxtot.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2xlivmrsa.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2aiumfjan.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2iegxyifc.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdmdqxm.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyobzcs.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2hishfusf.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2drqnwzwt.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvpyjxs.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2oloonwoz.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2yybzwvhr.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkkxpbn.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2krssvntu.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqguvip.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjhghmx.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yntcubwb.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjjjjvu.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfenuaj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwcutoi.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhvdfuo.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqflmmjo.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2traddoup.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2sphxmcac.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2avvjmcgj.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbyzalz.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxmdpam.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ankppjmi.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mtosppte.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2yjpmvoms.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2nffmuwpu.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2zztqxaib.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdmsqkt.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzcjvntf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2nkoulzqr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ambgclof.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfsezuz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpooekwt.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2idlynxaz.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdpcwhz.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsyngba.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjuofilb.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2opqcgfmi.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkqpocd.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aujwudqs.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2skvhuehv.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hicycyew.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvkssfi.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gphcyujj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ownfcjaa.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2skgcgzgv.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzlofrd.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2imdphmrn.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lekxzmqk.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nqydncuu.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfghgvu.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2joijxleq.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhwihwl.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2yyembwea.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2bofdmist.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbltawo.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2brlviqxp.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvrlmqc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgkyxum.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzovchb.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrfdxtfm.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tgysqomv.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzjugvi.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2froegqlz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcufwajg.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhcdcep.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgaetbf.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2urnvpsmc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pojnnumk.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpymcbg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2slifligu.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2khboeceb.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvnhuic.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2gkoudqdh.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2qeuaakoo.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qmcwcefx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2jufwmcqs.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsbgccj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwqxahj.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsspygh.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lacgiliy.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtnmnow.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2htzsnvwk.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnaxayu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkuoaga.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfdohod.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vucqhdbk.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cqacsump.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqwwkjv.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdljpxg.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgxswfk.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wdenvqdv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2anibqubh.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2frcvyoux.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2vllapxyq.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpwdhln.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2grbfoafd.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfhiekd.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ofaqsajv.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2upoltfxq.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2inemaaer.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqygxvv.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2glcgxtwg.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzegqvp.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvjgxcz.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2rpshwiyi.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2xznbmegx.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2zexklyat.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2pftbrzof.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbcjzux.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdoupgj.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhcajcr.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgbcish.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2digvplqj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2xytxhyjx.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2hewdjbgx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxhztrs.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2jppeclro.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2lltwrxsw.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2sgndpzra.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2jljfraqj.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fdyiuxzy.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2twdpbuuh.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2kweqdpig.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgpnrxi.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fybmmkof.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mlftcvee.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2meavsqyz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmppzkm.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcrqtnc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqhymxv.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwrqrgo.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrrnyvs.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cwiebiti.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwujixh.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yahahbds.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnzffih.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2utagmiqj.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2opogfqil.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rilenxky.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2okakfjyz.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqwqzta.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ondrfrzd.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpdmyhr.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxyjpeh.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2lzafsdtq.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2idickzbj.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhzkijl.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpkazlz.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2baowptmu.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzbtfwj.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2jefhbkmf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ffptrrvc.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzaeykn.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdoolmx.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjyiqbo.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rstmlrrc.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2rmuvkcjg.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2odkxuhbe.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkgjsjn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2swumuxef.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2shoautnu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcenbuh.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmcmmdz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtxfqey.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdlsjzr.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzuxazy.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ctowfyoz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2vgfrpxdf.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2aecjdzbj.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2kynsymco.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmjazoa.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2xahisizx.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrshhed.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkxdxbo.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hooeyvjb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2beonxrbx.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2krnikvrb.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2apsznubk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpddhoy.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ilabkupy.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2geupxggi.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2srpayuko.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2lfuzfltb.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2khtmlynb.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdtitds.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrvvaux.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2qctdjemf.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2raeijcdt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zuaipxob.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2akdapbwk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2chpazywh.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2djypuwoj.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxfqayg.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2mkgtqzzi.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2weqxyvue.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpanygx.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvirlzu.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzvwvzu.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnzptal.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjondbc.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2gigqanor.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgvnsuf.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2dbskridl.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2nqclgvij.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwcfupn.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkjpjxg.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2njfqnplk.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2pawttrqx.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjhxsgh.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzsuuey.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2iejjymcx.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2nqumurnz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkafign.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qxptcsop.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlajejz.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcjdghn.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwdkpvo.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2xvcbhtsv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nphfvyvo.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcvzfny.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwuxgdz.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmfnkkb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hmiyjhof.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvgzpxn.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cophqjwp.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdnkoga.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2uobjkmgj.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2eloevtxt.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgkztaj.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2uzepxxpb.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2wofnxxgd.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2unwemthn.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2cgyajqbp.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bvyfcadk.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bughlwde.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lejdwzie.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwxlzji.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqepnwl.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ddusmeyu.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2mmaplual.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2bacsptmw.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlpfayh.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2pcyismyn.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2vpumefnf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dkacyuwp.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqynmyz.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgmcjiw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2onzemmkx.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2euorphaa.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2lpalvgzr.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2mpozlhuu.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2yaatxsuk.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhaadii.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ycaoosfs.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2akrwropf.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcmdpiz.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhiklyh.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxbbxmp.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwtqazv.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2syltlefj.html


<!-- 参考信息 -->