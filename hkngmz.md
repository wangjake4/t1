代发 wailian999

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mllppwuq.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2aakclwyj.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pvyumomd.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbhtoxx.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vxiliqbs.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpwiceo.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2otmjxyrq.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2avyjoyhr.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2csxbzghm.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2msvwzoug.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbnrota.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nuinhuuy.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ahncbdkt.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfjkjsd.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2daldmxvx.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uiathdfe.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ymyrxdxx.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afhfrkxc.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2eskkhqbt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwiylol.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2xuixetbz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2izxdfsia.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtbcckz.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2icypfzle.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2alcxugwz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smngqmhn.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jswaomtc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2tefvgwge.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgennlpo.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ayepzhsr.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jemguzbs.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjuqjyb.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qixbdsxy.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2chiupqjk.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnbvfuv.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2sfoudjrl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jaybglmm.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fijzzgqh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlcdagf.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2kenyvvia.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2omuwjhfi.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ietdnufw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrubwgk.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tqngxaqp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfibhkh.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jucuepnt.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpxsdqs.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhvyslf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnlipiu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtcdwbl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtfgqih.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrxazmy.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqzowzw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2crqznvtw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2cetjtefe.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2khtisadk.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2wafdohhw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2xkexsoyq.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ainanrbt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2tacfetgf.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2klpszmux.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pamvcgzj.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2buqayozf.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2rabhlnxy.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2unbzhsoe.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqqquwd.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdwnmzl.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnmjctn.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2bphyzuwl.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2airljigw.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgazzhg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2elgxnrhe.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2teahcvgu.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxchgeo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxyjtgw.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tseisgqf.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vgrtdoou.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2zesiujwt.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnbndqc.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2dueusunu.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2gogumyxr.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvtwzpi.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcohlhw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2irfysiux.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmoubef.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2myjfphuk.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2futjevpf.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdjnyod.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwlkigw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpcezsx.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2mikcvfbt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2cywuqzpp.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2thvdcrbl.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2arpkkqpf.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2hixgegwz.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2lshoeyds.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsnmead.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlnqbor.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2aiunwhax.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bscocxqx.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ysyidvvc.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwbaskz.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2phhiuzkf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxqaexz.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbdhtcg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsibasy.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2nksanwkc.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ziqykgcs.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgcwdsi.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2icjtxwsv.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjcmsyu.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwilgnb.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2nopltxdk.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2lblynlps.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2iyoqrtit.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2fvampaer.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2crerzxux.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2beaikwsl.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jkyascfd.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2kffnhhcx.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2solsovrw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfsulkb.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2sxftqsov.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzpfwap.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2xynynepx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2qdrqqhco.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lyaclhau.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2fythrjmr.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2uooodtss.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2gclwvswz.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tkaxywic.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgurnac.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvfnlsw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2rlreldgc.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjmdcrh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctylhhzm.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qomcxmod.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2jviubfmr.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqcgeje.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qknsyhxk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kzanundi.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjhzugv.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzyozdp.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2grezvqoy.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmzunpq.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmodzbs.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2oixxrfbm.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyepybus.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wsoekvxq.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxfpjso.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkhvzax.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtpvkqw.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fjeepzsi.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogundkar.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxdrqrg.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2shjkdzjz.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ngldfnav.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdojodh.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2aijxiotz.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwppnim.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2glhffphf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhnzsyh.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xzeclpog.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfgizsq.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnryrgg.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjewkow.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrgyyob.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qycrsobk.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjiktex.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2unpkdvbf.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbvbkme.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnuzcut.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdchxny.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2enknfojd.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrqkciv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjplqej.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjtdmri.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2pacniqdk.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gaajpsfc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2qzecferp.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2xozaruqn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuxkuld.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2gamdeyeu.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2npzhljtw.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2pcyeiair.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2aodnkqlh.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtngxph.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2sgyesuvl.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxtiibo.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwotghv.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qisnqyub.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2eziljidi.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2crsrvlnv.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcryewhs.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2igbygjcv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2atiwigfx.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2crtqwmrp.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjajhfb.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yyuqxstw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhoodwj.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2zmsknxlc.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2yryijbes.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlmcpbd.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjioboa.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2udbmqubi.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2eeswtzuy.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2bwalkudo.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2qofzhxfp.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvrgaps.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2juvhvpfl.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcwlaaf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2hgymkilf.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlglhab.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2seyxrgsd.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgvxciy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zovudjtz.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2bncczqpg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2tfyjltsh.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2tinkfncd.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2hiamjppq.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnwicim.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxjwtot.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgwayex.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxhtgqy.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2dbddfnib.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2faewhyth.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jgujwncn.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2oflknhlj.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dacyystq.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhtxguw.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzrxaxa.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgswgdg.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aawecgij.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2umyhkhdr.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjqyezn.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqripwdc.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rmiufsod.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2rpayhspo.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbcwuoo.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnczbzcc.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfspaqo.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfytppu.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqkfpkm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfqjlzn.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqtaqal.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2iwngnqyn.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ocukfrgb.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2kumowcyy.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2crkcafmq.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvcxaql.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdchuyr.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhrxttk.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgbmknu.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2kttaecbz.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtqnfle.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2xwsmzygs.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2wourcdfr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdyxrjvl.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnfkwlz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qzfdwkwe.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2lulvjxdb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwyhhar.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2btrnjrgt.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjmycfb.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2rtyhnsfo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvqeajh.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xbaancee.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2zytwrkal.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2sgluvnam.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqnmwjc.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2gsuioegb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqlecvr.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2gqaqdhtv.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2kuynxfyq.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ipzyjwvc.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2umubontg.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtmygjy.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfordhjr.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxdamai.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2luzdmgbd.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2rouddyld.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvctndag.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2rklwwrsu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jxodhpwu.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqyomgx.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2utckrbmu.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2kyscehme.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2basheybk.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2kgudmfjn.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2znkipike.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsoasga.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfyxxgn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yqeaakym.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxkomfd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2djwiimxg.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxwaafw.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2opridfod.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2gencfjma.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxipyok.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qfulxspu.html


<!-- 参考信息 -->