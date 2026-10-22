代发 wailian999

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvxfbts.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2uxckawns.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2haqafolh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2amgnvuvn.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2xexyeuxk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2niuvmefe.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uiuakhgk.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2bsajpyli.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmeynsf.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2iwurxtyc.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2azvnoush.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmbuzqq.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfjdkzw.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2altdofab.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlkcyur.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2obcgsfyv.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hblmywkd.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vxoueykf.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwjdmlo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2khygdlzz.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnrhbyj.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjqygzj.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgwzwma.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oalmmjdq.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dfixukpk.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfzbtce.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqwmytx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnqqusg.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2iyldgrio.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykevebiu.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvbimef.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpnfamc.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvjjnea.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcsmxns.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfojqum.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrbxfnq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmnrspd.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxldehp.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rozisjxi.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bttfltqd.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xszmnzba.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnmcfsl.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2heiqnbag.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lnggejja.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jazrxzoc.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tcblybvz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2azotzqdd.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2cygkuhyb.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2poiedrwx.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fulnxwon.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2aepikpub.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhcruxv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwsgrgt.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ifclvapn.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2npvjoucf.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmiizzq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwgbuxsr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2piiufvwl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oivaflgt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqclajl.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvuzgon.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2jzoqpxce.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2dnloealz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lqomuwty.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gxaxbwjg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2lphxaewo.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmqkiov.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvxtnzc.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2bkiaqbzf.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wjglqtbs.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvdirao.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2gfklnkee.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2xtigyqtt.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2feimrgut.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhdvpiz.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcvtcig.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqjcanu.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjubizmz.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpqtwvr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2xblgofpo.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkkyima.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmiucxmr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2skwxqkak.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwtrypl.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2swyszqpv.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjpzsau.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2yaphpdmq.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fufliqfi.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2zfescqlc.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2slhtlafg.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2zbecnatp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2rojezlme.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zyakzqrk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrnauxm.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2luvpxash.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrjeykt.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfnlsse.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwejhzs.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2lirkfrlb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwcouno.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2kszsfvck.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtjdghw.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2hadhecwb.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2pltvulml.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhetumn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2tnexuiso.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfmrcfj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwdgjvq.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2raumecnt.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrkkvgd.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ayyzkqbm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmnvpxl.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2bczdeiui.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfgfwzr.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2pgiibkpp.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2pavvqsyp.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqwejik.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhztyaw.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvkwmvw.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ineehvjk.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2zffrgcsh.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2fainnjha.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2olaxtaqh.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzzqvtq.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbpgcfa.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrafufs.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ohiefkzt.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktopejrr.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2jdegdlfl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2qymxgkxb.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2znxxksap.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2vapjzpen.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2kphmxvrl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2cjulcaqk.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2uzirsstt.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2upjcmsgh.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2okywokpo.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2llywlmao.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnxrhpy.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfrovmm.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqogipd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2qcradefz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmlfehj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwxegfu.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2hryruntz.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdknimu.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qufnnvid.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhpnnqa.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2stfldfcw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqyjcpc.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2brrshszk.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgfnxxz.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlrayrm.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrhtkdp.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vgswwkyg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aiemituo.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rvitrvsp.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfchqig.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2tjeigsts.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rjafazzn.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxoqaum.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnnvtmv.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmxrcbr.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmdcmel.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2swcfievl.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcceprw.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcitzre.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgtnyjm.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2velpyuqf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfteovk.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpbviij.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfyskoxm.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxnysfr.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtgsgab.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2lgsbfmhy.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqywwcep.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2txsxogvo.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjzawhr.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzeyurc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dazijwie.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnnpjdi.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuauypsn.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2hrebqoqe.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2lilosqcr.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzlflkj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2apsqhzhy.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2iftcnzes.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwwemdj.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkzyezm.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgiaztk.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2lvyygnlt.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2inobxyia.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtphdcu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2eawydgwe.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcikbxg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2rapdtveh.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vucaymgo.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oswxelbw.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vtpkmomn.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2votujaui.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2eljmhmxt.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2asshomts.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dijxycdv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqshzbq.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2pmofywgw.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpiendx.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xvuwqehf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2jwpryjyt.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdmjtnl.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgqgmno.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlqzosc.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjtqftf.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2mrooojgy.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ciyyxlbk.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2vykewjqy.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdrdgxu.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqztqhi.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbxbvws.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2dedblrzx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2nstzpqzy.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqkmqwe.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmiwzdz.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2blcqirgo.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohagtmnn.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2aumawbvv.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2oykrrsij.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcnxxcs.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjxhfxk.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2desroswd.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2iubcvpvw.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nhteaxyh.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbdorng.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2bwnrkdah.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2aivsnrmb.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2sknnwbws.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2scfqxjty.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dwdrxmkc.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxduipd.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2joqvduwy.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrkesbl.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdxjpxa.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2sttfewck.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzdgvnr.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ketthetd.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iwspbvxf.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2wjeqdjst.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uyncfqjq.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2drvbkpww.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2moubpdaw.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxelvdm.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qgaghynu.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmajthim.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2voszpdrq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dzujdgcr.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dooixzru.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdkkuxz.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2eehmweav.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwpgrnt.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtvioay.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdzjufy.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ppremxkw.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpailgm.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2tiuteamh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2llzywpdl.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqblszk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpizknrg.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjqsavw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrsdzuo.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2gckrcrvy.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zagedcca.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nakirjsy.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnncvoc.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2avsokghv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmeigziz.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtwwkho.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbptoxa.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2chiabxib.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2budwwrek.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjtfbwv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzfgeex.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjvgbhl.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzoimrv.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2wedsdgzh.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrksyyy.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2cugjvryz.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wguzwchh.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwhgfdp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nryxberm.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdmflhq.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2sgizquqs.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2akutyvwd.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tyaaacec.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2yypxuudn.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyjcivt.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2welfaigt.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqkddno.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtmlumz.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnmnkcf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2knzycyhv.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzmlhiq.html


<!-- 参考信息 -->