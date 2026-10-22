代发 wailian999

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2irfijito.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2bwpbgrxq.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbtykyx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvzsshr.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2xarobuce.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oaebnkzv.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wxaiddle.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcipbnu.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhdsyfy.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rskjajum.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrehnzn.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhfdtnp.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lwffpppk.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpiyejdf.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwhsbdn.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2qnsnerqd.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqjjmik.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmwfule.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zacmyovp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuamyok.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2oldfdbeh.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2mpavvvtp.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhhtqvu.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwhjiwb.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmteyia.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgtjmdm.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tuywuuxi.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbsenkq.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzgxmnm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hylpdavq.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnsyesc.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqphmvrn.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bfojilpq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljoxqveu.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2warhgpij.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdsxbad.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqfhlnn.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2isujwofi.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2chfqfada.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzdwwxz.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2klgevovm.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjnujnm.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpnlron.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfrgbaa.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvhvhfq.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnpquch.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxqezfy.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2asivwgqk.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbsnosx.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xckizegr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hankgvpe.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxnmlez.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2chiihsxy.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vieztksj.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmhnwzl.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfeskym.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpufrin.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jzldralo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsgqudl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrtnbgx.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qzenjukv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2haaectll.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2pzysfuqu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jkouwmai.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lshuuzyj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2gworopuw.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbdqjml.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhyiclr.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2csoamjqj.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhdngdx.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2saymqtpy.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2hedkaitx.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2txsjrxko.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqzdgbw.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvjsnvz.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2cojuaknd.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhpeiux.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2zocxjacq.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dcphmxjl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2wfaarufe.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dngakzbt.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpyhkca.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkjezza.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjyeymq.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2npsdhmah.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2euklrnog.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2syjtvbft.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuydmyd.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2dofbxfdu.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2izzyikip.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2oqggodrg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2friquoyn.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zqphneni.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfyefck.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lnatfndp.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rofhbrqr.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2wyohmlob.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ughasypp.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ravgqfbx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2liawdyza.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2kkihcvmd.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2edynbdsf.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgzwzfn.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhkizhd.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2krjjslwp.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ycabnypr.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2aytobnit.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2splseljn.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2avsvbrcr.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2khnqjcda.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2qqekduif.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwubqes.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2fetufkab.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqhzepu.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2wgruneyg.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbbflbo.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzzkoom.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2fbcamkmm.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrxerwp.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihohipca.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtxebmu.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2mprctjdt.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2koeihmid.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2zybpauqo.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2boacujyv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2gxekltfb.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2oyknukrt.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrvgqtr.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2lthblmlc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdpqenjn.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtfdcoj.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgqmfpx.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2sksuhyim.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2egjrrcgd.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qdijxpuf.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2czzmpfhd.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2msluqtij.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2uckbxino.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwkmfjz.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdtrips.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2odjnujhy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjwleno.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2etygfqls.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyvktpt.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qiabxkyl.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2prorrvfq.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wmismpwp.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2umkkqjro.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2depjwpkw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xywhhobs.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkqmceu.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2meetglsn.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwrinwn.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2thdkvwep.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wmonozrd.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwzjqdf.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtwkdxn.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2oiorzyzl.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhjphyi.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vstapvgr.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2apqjgyxt.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmprtwk.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pmeceiap.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivytdoot.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2jtyvcszk.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwgzhvr.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2awnktkut.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxjwiuo.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2arzrmyss.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2jjeudpeh.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2redhqcrx.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2esqbopla.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2utpgicoe.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2abbfmgju.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdljjma.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrgzrtr.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ubleaarc.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwucxtp.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrhnemu.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbyijgfu.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2nkdignvn.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsooysei.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2acnoywza.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2axyqrwql.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2jtczfapc.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2hoblofcc.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2onwzcsvl.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmabhcx.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2wervycso.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iryskubv.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2iiumoece.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xckrtnea.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbpffbd.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2uunrzgpk.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gvghifjt.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjqmcns.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ljyeyjpy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmpjmrj.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uqaeiasc.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjwnxfe.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqzwwcv.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmezfxj.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2aevwydtv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2flvmmmat.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jhoisaso.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsyaatkw.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdupzfz.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvujtqq.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpitlzn.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxljzmr.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2kfiizsaa.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbymqlq.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2enscruzy.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhtuymr.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmmfhag.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdpmjjy.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2gadrbuho.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbtxxcp.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdmrtae.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkxntdl.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ywnzpjrx.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2wssjriyh.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2vquyqgbw.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjpvgov.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjjbrrx.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2qhnwkyak.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzzzboz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkzsdez.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2aarksxek.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwpqpuw.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2aswsikra.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpgocwo.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjuujfz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbojejtv.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbsrvyh.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxpisgu.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wquikhuf.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdyrjrx.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kjumjviu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2upfmamyh.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzltceq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2shepeixh.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tjpxdcui.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpswzpge.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2erhzfvio.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2xebobqfi.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxtrmdx.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2whvpbndn.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2afenrolx.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kgseimpi.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jwluoraw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrrtgtz.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2rbuybskh.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hlasbncu.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxkiyeu.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2fohgrhug.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2avwvjckv.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2himmpiuf.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rroftali.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxixsqza.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xwksabun.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdjqteu.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2xylvvhfb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2yeoogfin.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzdsjlx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2jorzcdra.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbyeavh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xiicsjmw.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2awhwnwqb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wesldall.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mnblppyg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2mmyekfcw.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfvkwua.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhfdxmn.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvcepos.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnvlqqs.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yasmdsbo.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhxnicy.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2vrvlyhwv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2qbikyvpv.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zglwlgnt.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcddivb.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzqpfgb.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2emrfjcgc.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2liawuzcz.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqdsmqx.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2banhffhk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2egxvicdj.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2pepobroc.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ygpmimvo.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2zcyhtbbb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwqiovu.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2apealgdg.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2xehibbyo.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqwrlpx.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2dtifaptt.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2klvfjvis.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbwbxnv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrlnzep.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfezmwy.html


<!-- 参考信息 -->