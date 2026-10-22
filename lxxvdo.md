代发 wailian999

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtxojqv.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnkppzz.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmflfty.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2evauducq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2amestnja.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlwsjjv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2puvgtimj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nztgmesj.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2giopzlel.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2jasjwkqn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2xewwonfk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdtwhcz.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzvzspz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2eftwakdu.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsybvop.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxnkzyd.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2wigxvoxg.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xapdzcwj.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwbqdob.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2nhljujem.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2hybqixxt.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdxloqi.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ilneccbk.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2wskbamrf.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhtyfdx.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfurygzo.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2snjuhkml.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2mezhfypl.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhkzjok.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfhljvf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2saaaxmaz.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2uibviqyr.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zivondos.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpsueto.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwmtoor.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfahfvcm.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2kowvngvs.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2cmttoxjn.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2djumgadb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2jycnczyq.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcjemuz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2chjmiulp.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zypudxec.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gktatqtf.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2xerzafoz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2aogqlxbg.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2zprxhuah.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwrgcrc.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdmdmur.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcyaudx.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzrytle.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2twrbszqc.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvxwklb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2smehwdvk.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgvhngk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdaqgav.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgajurd.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcdxecf.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxhlffw.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2sabnxmsq.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2qvyqgefs.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2okqrpxza.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgpbamo.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2nudumfkc.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2denujydn.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcbuwea.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ykygxzxf.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2poxatgag.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgqmxcj.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwtqulw.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jergrooc.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbbgety.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwstlps.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2dikoqjmy.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ouinilfn.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldokuhhq.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvoqmhp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxadrryc.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lqsjxvnd.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnriewu.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2suwxvndh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2sbsacjgh.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2txuhgpnq.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2qezbqrnz.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2pznmbgxl.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ievwlvph.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbjtvmw.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2onbbdhyz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2gumirrtf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2olhizcir.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2myyzfmxz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2adfiryil.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rdllcyoz.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2polqbmpr.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mefyoigb.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzhryip.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ncsquqau.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzzpzse.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uptxwqae.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2khmxspww.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqcgkdp.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2eucjnsrw.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lheuhhnc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfofbei.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmdsrwv.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2dfyrgohm.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2elaekbnn.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2adkejkos.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmvzjum.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsetvade.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2glodlzxb.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2dipyhupt.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2bjyxqbpo.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2xngpptpp.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2uvabnesx.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ojryqtms.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2trtdkirl.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnfucep.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwxudlz.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2idrgqczp.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcpwfdn.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvchjgeh.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2qylpdbzl.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfxptql.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2irdytsxz.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuswfpyh.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhaceuu.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2onvaimzu.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxzsdop.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtzqkra.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2uvahklmi.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2toawaxxh.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2cghhmbzt.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2psbpgkri.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xqihhcne.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2swmdkwdg.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ukiezuww.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vuuzhgfe.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzoooyu.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iipnjmnx.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2obllpmjf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmicabc.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2orauqfxf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2qklqssrl.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxrjnnr.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhhjvdu.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mibkobbn.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2nxffadvj.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lppcrqla.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2cubdzhdb.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zetouajy.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2yruldwox.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ervrhuph.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdumiyz.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlumped.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2sectehwy.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2sxyfrqng.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhqazqo.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2xatzoqbr.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnlspka.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2urlywgpr.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2tgehkjlc.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdxyqka.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqfqozl.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnspcrp.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2twalhiib.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2enihfyyk.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2rucoxcfw.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2iumqbkyr.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbhjboe.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpzzvhy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbplimbt.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ibovyccf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdjqpwr.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnzjrdv.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvfuxwz.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfvrofc.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjniscv.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2czsdwjza.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2tdohgnsv.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2tebjcume.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjfqwyi.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nsycjhqf.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtlyrylo.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkscgel.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmfceum.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jzijizto.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcyqaij.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhuewjh.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxntwef.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qykivipw.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnpygpo.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwjamik.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdmrekh.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ididqqwb.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2stecqsbi.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2wexnlkgs.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxidcwg.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkmsryo.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkatcjwu.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnajfhh.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2yltsbevo.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqtpkbn.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgiwoml.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2iybccdvq.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2stzswdvk.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2twkupkfl.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwiyquhv.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2efztpllc.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhgfwtt.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvuevnz.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2mhibfhdg.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2quommpgu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwtuikx.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnoehfg.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2agjaxqnw.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2yqepxvkr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ukpdnwkj.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvysctd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2atmfhgou.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2xxoamfmy.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2fedikknf.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2twhgipxy.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2tglhypvv.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bosecsxg.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2xklpjefb.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ekanemjx.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2frtncyuq.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2nsezmmgf.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2zqryrfqv.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2viokdcek.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxbnbvg.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2hllbxsyz.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwarvqj.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbxtnnz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2widhnaqt.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2yenjodok.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwxnebx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkdqzun.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2irrlpoak.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2cofygdfz.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2ndggmaof.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2tokybszv.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2xyafmgjs.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjsxqzu.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvuxjkg.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2aiycighm.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2pwivlrwe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbycoyw.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmhupay.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwjezjp.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfumwgs.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpwkdkq.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2yiiavrkd.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2evophfjj.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpcxpad.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxfuxtk.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yflybcat.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdtdecu.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpozlxt.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2rogtivtr.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzbvoyw.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2vdybwvdg.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzvbxfe.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2yklluhsp.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2czibkbzb.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2etlbkjir.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2psbuqevw.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2drjdviph.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2suhfowrs.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lozktawq.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2yxneuhjc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkfzraz.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpaamzy.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2flbsxxew.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvkkjtq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2viygipbu.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2vevvwgdh.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2twbibcie.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkggbwp.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2oaazzlon.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2lalrufiy.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvwyzqt.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ebudkuoz.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2euorllyz.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2gflqzjrr.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpcgtqb.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwhkvpl.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjrfzlg.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpfldnc.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpkeqix.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2qavxrzgx.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2jhexczst.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkejgye.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjrswde.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gomabvic.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2vycijaan.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmcbxuk.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxatwxt.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2ichjegng.html


<!-- 参考信息 -->