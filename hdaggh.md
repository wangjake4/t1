代发 wailian999

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2awfgsryj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2oubbtzdp.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fksqjryp.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2resewsbv.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2rufgylud.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2gflqsnph.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2duvsevea.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhabczk.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtnixuw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wlgkjtiu.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uiisqjnp.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkkgqux.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmbmbbv.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gknihmjf.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2puqiqbio.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjfugls.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2aaijxlfv.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjmbntf.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2adfiarpy.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2makoozoz.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2anpnxoby.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2supneviu.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gqaadrwu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2douzffhe.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2smfpkyyw.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2fafktoqx.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2buufbemn.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvsevpn.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pqszwloz.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtfuglv.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjkfcye.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssonxniw.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2potwvflc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2erjlsccf.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2scwxtjhl.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtjfgen.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ticdoyyp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cssbzjrr.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwaxlmi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2azbsxrru.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgcqfyh.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgirngb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fvnwoioq.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hfibslln.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tgshhoiq.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2syuxopll.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2corjslcp.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkwtrao.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwmpfxw.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2puzagnan.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnirqssy.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2alrwnixo.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpuiaxvt.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzphyyb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkdkbox.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qnoxyoui.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkmnqax.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfkybzu.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dscnsejt.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2myfslvdv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2fiateven.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yahghboo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2phleqqzf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2maxxkaoz.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2duidygye.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2vfawdftm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2xyejzltb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2drjtkhky.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqeqjnl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2cvebindr.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2bxeitmgb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2elyqpqks.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2kmetjzso.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vorfbjyb.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2frzwydlr.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2xdprpimc.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2jxylrupc.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2hugspbyo.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kahqnznf.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ilgjbixs.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2treorsbc.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2flrywbnf.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2syegitib.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2oerzrcxi.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gfltxgar.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrwekxw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tigrjwjo.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfczmuip.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxbtmfg.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2twzbqlva.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2raadmsui.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2irhavkln.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2qaewlvmm.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2uxudzkva.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvikkxw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdtbowv.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwitfiz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2yardcjkm.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwdtikw.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgweavin.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcducpa.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2migggoqh.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2empziuzb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkysfyw.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2gweicumd.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ssexbjxe.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvrnsls.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzbtjsj.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tmencrfa.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2spzcgzij.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbrutlt.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pglmdfup.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgxcfmn.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlawvbu.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2sbsqtlun.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyaiuxzh.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlackea.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2drmzwrya.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzobpbq.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrgjrtp.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ntskfezd.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2dsufqafi.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhrexhe.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzmvhrd.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2oyefjjjg.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2qsphukzp.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xorbnigw.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxnfovh.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrdzjbw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ekkjgsmi.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxihadi.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdevhtc.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2belsgdoq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipsozejg.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnlhhvb.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2uikoohcn.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2iypjfhuh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2yztkjugy.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfqkwvf.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2lywzcmgi.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fllglxzj.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhdndkq.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzinaqu.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtusssd.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2xmclufkf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmcensf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2zokyimpy.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fghkihwn.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vfcpwufs.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkzdepb.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgmmvak.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdjaicy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfcnhni.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxurozy.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdxlrti.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2whepwkup.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oavocczl.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2dkaeaxwf.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbfcjer.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jethalkz.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ldoapoux.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2yragjoqi.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgkrzjb.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2faitcsca.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2acxakvwo.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxrfblb.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmradjf.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2needaxqr.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ncremnvh.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdmckkd.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ochvgrep.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjasnpa.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xroemtdv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbowlnb.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2itcndiuu.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzbjepl.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jlonyfvj.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxgwrwc.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2eixedgul.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pryxwucc.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sjyfuzbq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvqhjyp.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2tvimwpwa.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xoylnuit.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xiypucrm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2eevdafje.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2npxzxwyn.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2cmiuysrf.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2wfocpccz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtlmuoi.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtritot.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2clgsalpn.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2nldrrqfj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2msybfnam.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqwxwtr.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2anagxmrv.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwxlsik.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxefukjy.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkskuxo.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbvklqv.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxomcmz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2taspdrdb.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtwuwra.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2tyclokru.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2blweuaei.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtoscox.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ycyibfhl.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxlwtee.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2plflfukm.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmzrweq.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2taczsalw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqlrwnr.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2crkypwgq.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2eqquwnur.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqhuoiz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwntdijh.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtycqin.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2dybuxqfz.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnghere.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2vibytyyb.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2sngnexkf.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2yvplqswt.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2sutkxwhd.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvotkkr.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2iuyqphgl.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2asfevmka.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgxshir.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xciqfpop.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhvnddg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnwedwb.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2vorxjipd.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2zthjmozu.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbiztiw.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcfwkea.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2njeutwye.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbnpitm.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2xskubhoj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqudzuae.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2onxxvjix.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqeopvp.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jdyonsho.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ynuoeojs.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2omrrtuvg.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmpbotqu.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqxngjt.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbebzut.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2edbqthkv.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wezjlcsx.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrqbwoh.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgfwtnl.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zekletuj.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbgfwvt.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgjtbmc.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pgabujbm.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ppggugfk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2krndpcdc.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2fzamvxkm.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qknjnqip.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvchjak.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2oljdpanb.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2igeyyeqe.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgvutbt.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vstuqvwn.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2sgclhakr.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwrogmg.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkuhzpqh.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2engbzsya.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqbqutb.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgbnmqm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkrerib.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbgwusk.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2agxpbgrw.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbxilbs.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uensirgn.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcaceeq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgqsbkd.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2qitdugov.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbiniysq.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzxfahc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhlxlof.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvnoqfv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyshyajf.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2svkkodzh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2zkunnmnl.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ueifdsor.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2wlusxwui.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2qllvzduh.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2umypaqtc.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ukhjbewn.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwlbiul.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2okhbkbzr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtdkfaq.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnbshqn.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2pqobapem.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrldrhs.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jmecaior.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcgduwo.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgugmqc.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsgoljc.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpjvivf.html


<!-- 参考信息 -->