代发 wailian999

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpqfzgc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2toktlbkw.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbaxurg.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2mskoowie.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkvsale.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2daqcajvz.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrkzxrx.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2tvsvnmwv.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wagmninp.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzvbony.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2gruiyeig.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2izrknotu.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqujvzk.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzatwyo.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjorups.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxggulmi.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtkrdnn.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxjehcr.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqnwtpd.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zloajzvv.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xcavulqz.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrtnkrv.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2oruswrct.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjuikcgv.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqggwlm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmadjuk.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2secstoii.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2vworyfen.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzkzkea.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2usdlqtbr.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqwslyg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpckikpm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvsymds.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdpdnqs.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wktewxhz.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfrcxjd.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dotirfnm.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2teiuegjz.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqhzehf.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2veplbscl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sczwzqpk.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmvwjjy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvwberb.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2jliwiyfq.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcergxqu.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yxalumut.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcphkkk.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bezsapku.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hckartng.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2biebwwau.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbsqeqbr.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfmcqyq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzooili.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gyctexgv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkfxglv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdqemwg.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fmomukoe.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2pyebicle.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2eedulfhn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqceayq.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2usoykdms.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2pslkbbns.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2yptullrt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2oacnfxwl.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2eymiescv.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwmlojm.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqsxacy.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2onceluuj.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2hulhehbf.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2vsldvyvr.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2eglcpzgy.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhggutz.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2qsoihcka.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2gukyvaky.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2atjprxrf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfiwqdo.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrmzjea.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzhmyxh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvbsvkp.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yteyjype.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvnmpmo.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgnhelk.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kakeqfvt.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2gviozaas.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtppmkn.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2rluodbvy.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2taikezyl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxybshc.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gahqqbuj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjiavnzb.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwyfzwh.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kublzgeg.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgstszh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2winttlzq.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2erxexanm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdyeodi.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcavpfj.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwjpjat.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbnqovo.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2srcdmhoq.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bfekgrzv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdlszfv.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmiimhx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vopybxbz.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgowjlh.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqguone.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmadryf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2npvjpyur.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjpjczi.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkosxcp.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2yydpjpmt.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2wselqwgu.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2svffswpg.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2igucwokm.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zryctjsn.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbfujhk.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtzoyui.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2rmudtpyf.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nvpakios.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2iszzqwnu.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmyuebw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjesffr.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2oaledlnk.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdxmzrc.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2dcycagus.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsaqwbzr.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpsrcpf.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrseydk.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jejpqpxw.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmuvldx.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jlyothqc.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2grjmgpjs.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cmewymis.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2wtabfiwy.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzangfn.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbumdpy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzudgii.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2zplfozmj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2qtydlhrf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogegeruv.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjwgczk.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcjgzfd.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwqjsxw.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxkxyzn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpdbuxw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcsbxyza.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvnilas.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdygdbg.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rboioeae.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvltvjs.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvzwkuj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcnunck.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kczozlxv.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2weaggvah.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2djgphrzw.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2txpstbxx.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdhsndi.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2tefuxlng.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fefxkcpi.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2icrzzxks.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnfqhzo.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyycxfp.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhvfgnt.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ihuqkjra.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2stnazvey.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkeckow.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yurwqhwe.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajrhbdkc.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2oaftdles.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrvvfmv.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2kedyueba.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpihqhnu.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2olcnebox.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqfzqzr.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2mktlxpkt.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zutixzjs.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqlbxer.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjarbde.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2psywyaxe.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcoatgt.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxmrkoe.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwmresa.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2injvgdfx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2abecnnka.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdczbjg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzodqgz.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkwfdlt.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwqvvpk.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2xvafwxvb.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2roubifqb.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgumrqu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2wtcjgokw.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgnymir.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kssxrqtp.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkoyrvg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2mtryeeyf.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2aykunryo.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2cndbkker.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rkfaffee.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzobunv.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ysaghgaq.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2gohceytq.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2trliausb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdxcxcr.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzxodtx.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2grgguobm.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2asnmxmkh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjyoeae.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2aeldiyhq.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2anbldkbx.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2bfitakpi.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcfzdip.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2vimtllry.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2iimaroya.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2bbgearoc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2xnycdaft.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rouykhxz.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbbwbif.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ulooujgw.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2oobbudoo.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfbsdku.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmexkmw.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2osonngma.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2qwebojpp.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvlezcc.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2assowfmz.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvnutgd.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ftahpjfb.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpkjqdz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzweplhg.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2imusxvyv.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcwhjcd.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdpcnhm.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2cznwkwfc.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgezlck.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dngrifpj.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2eohkejvc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwmrjyd.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqceqsg.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2njzsmjwk.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kgquuauh.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2aprpcpkt.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhihdwu.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2oimclbpd.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2znbicvte.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jkflnwju.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2biycqxle.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhtqjjy.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2iowajvyw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2schguuwr.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nabqgzgr.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnjcjpj.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbpneei.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2oflgceqa.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fsubftib.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgyiedfu.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cqncsgte.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtjioqf.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ilerdefj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhwwsuu.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2zimkkytv.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2erjdwxjk.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2zkppjvnm.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gupfhwqz.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2lrryhrrd.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ylaweibf.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ourhryfy.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkqvnye.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2cuggirkn.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2prcxmnsp.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2radkdgqw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcatvbe.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrgxxln.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdrwplj.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2xosxlayj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2blrqhxrk.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2yodvmvgl.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2loiosgas.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2dahfbszu.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2jguctpcn.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhylxvz.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfevmhkh.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxammkt.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2epezhyau.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2idnvtoau.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjojxdy.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2cptqntsy.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvtgmab.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtingui.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcxaxwe.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2mybxhuek.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2juzfztbx.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2jiediqxd.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2imrwqrlc.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2qasuxnqo.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2noqkamku.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dkofdxsx.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrqcgqo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ynyoqwyg.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnostuv.html


<!-- 参考信息 -->