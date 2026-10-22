代发 wailian999

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ddditizi.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyxgdtv.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ecotrdup.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrtotaa.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhinbpb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrbfxvg.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrhegus.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvxarhp.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbxpuaj.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2trsiwlfq.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qslhrsoc.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2avcngtdi.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgszaaj.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ummbadwj.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2dwyjmlzr.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbpwgbd.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vreuisao.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjjxdsq.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnmvkwn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cceskpvx.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lcydbkki.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2liipvkfb.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqsjpxk.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2raiptuxq.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2eaulpljn.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdnnaqzj.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrjfvhi.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zknzathd.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbdegia.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmxcgtl.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sojhcuhm.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2owwsgeaj.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qeiptysm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjvbskm.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2acroaudq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2yndvvgzo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aphbswki.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqwiztm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2oiorzcwd.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2clbihzzw.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pewjdowu.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxgnnla.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2obmcgryo.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfnbdak.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwpkkwa.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qghhyybl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2grfezrjn.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2qblqyzej.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zleovizu.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xkppynlh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yubfjegs.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2drvhrhad.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2uylkodop.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2esqdyuvo.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjwlsja.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlkoaem.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2afpynziy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmeuryr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhafogr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rfudvxuw.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fissqiyr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcnpapt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2upohmyyx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdcvurn.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2srycieko.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2juksqfnh.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxibpqe.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnzydkn.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2wwyshhle.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qoorlfcc.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mhipofub.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2tmexowhy.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2pabvshxx.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzfimxg.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2trgmvrul.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2tdigqmcp.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2adoysjpi.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwmejjk.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2oihbtycq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdcgdld.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcvemln.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cexkrbxv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nkacgcqc.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2socibbkq.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbuznlc.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2thhxfksm.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pwddsopq.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2lagbcoel.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwarmgk.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrvfilt.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2xvovyiqx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2crymqptx.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xjunkeev.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2thrmvarg.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2obigunkf.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2acxbjzqp.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdsnzex.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjdfpup.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2msvqajni.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2opvyekvq.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrkzsrn.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkobmyc.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2rovubslr.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2gbinzism.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sujtjfll.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgfflpg.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkrkpyn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpdklsh.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwlwynq.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnfcpuk.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsmupln.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2tujdholr.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxjuzha.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2artsjywm.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyciibk.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrplbbl.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmmxxby.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgthemo.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkpymro.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2adrcrksc.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2vaphnbvn.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2dattcexx.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2stwlbmlz.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2hhetmniv.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2kqsmdyvn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2odrgdxuk.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbekolk.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxfvcnm.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2eceqzplf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlkjrjq.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2leeubryq.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjznpztg.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqtabbn.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2lihazsia.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcuatgk.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2mftzdwvt.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2blicicdp.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2yioqwzcb.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hblpavkh.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wilyvhfz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2tgiklzvn.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdwhbuj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2dcflawun.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvaguky.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xyofwovp.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2glkgouyy.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyboxzx.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwsnqqo.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbauyhx.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2usqwmtqb.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2trltbrpt.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2vcicvtmb.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqsceae.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkkejlg.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbhgvqs.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpybdukw.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bbduxcfs.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzuwkhk.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvxxxml.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fepopupx.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2crcgdmry.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2idpoguds.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2azlkbwle.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjriuuc.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2wsymcylt.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2zgexglpr.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvnauof.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2sdsigcgg.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjlgjsa.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2hcttdnwm.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rqboxboe.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyiqlikb.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrgppww.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzfalei.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2voydabae.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwobene.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnjqfyk.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jihgnhqp.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2amqjuqda.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mshcmltc.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fymwffad.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkiekvyy.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2zqskmfpg.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgbokah.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2nudftvjd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyslnlvo.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqrfbph.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfrfdxu.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2twcbqgfo.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpkcvkbv.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbqsqea.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2eztrphvs.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2deaoprhj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2umfdpixx.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqnezsx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2otkxvrai.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2emfilnac.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2syqtftve.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbwbkzo.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2biqmxdvx.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2plxqreom.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2uizyiubk.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2acnenels.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzxoetv.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvatxzr.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2xofdnsik.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhuezoi.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtkznax.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpdztyn.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxvvnlp.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2naawwgru.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2exiaxqtg.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2mozfkhap.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2fesjkfce.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkidiwp.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2adgvubyl.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmnuhdv.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2vmiornjr.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2djproxpz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2wruaykyl.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2cppgbxjd.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2fiznlehg.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2zuojnwqa.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvpcrpz.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2fiskxhtq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkwiovj.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2itplmeoc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2woyucnmb.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2robukwjo.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2xozumgcx.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqywjty.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2gpyhbzig.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2xykhfaff.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbvfjnk.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gojfxsdd.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzuthdly.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2foisdosb.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wkxtbzuv.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yaouoqhl.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdszyzm.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2npvzvfwb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2cwprzynp.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2spbsxpbf.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddyujayz.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrjgnce.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2aupwsfww.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uiadpszv.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwaogha.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlibsco.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwmwsdr.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2eticihzy.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2prslraeu.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrdtbja.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2llarpjdu.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqttqec.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkccwxu.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmigkqy.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2beygnxyn.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrzvwmk.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2lccgyllf.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vyizxgpe.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2axvmitya.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxtmeaf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2unirihjp.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2zaiynmyu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2chltwant.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2grthubne.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rkipogbu.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgeyqtk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkgzacm.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wgemifuc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2sglkrqnr.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2pamudypy.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2aikzsnqm.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnuctzm.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2hsspuewm.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsvjele.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2sheaffxs.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2moztloym.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2tcravnxm.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2umcvneao.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpkpwmk.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfabqrb.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2baiyslsx.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ufurkbnd.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpmrumz.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2psrznikf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2apnjdkza.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdfvuur.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2yffakptk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzplrjv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jzarbpcq.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmcomdb.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwqjitn.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhptjvu.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2yzgyjtig.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzwqmgm.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2toovtgtf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxuzcsz.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2srwpmoel.html


<!-- 参考信息 -->