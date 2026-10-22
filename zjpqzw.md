代发 wailian999

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtncwnn.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxadhor.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2aolbdjlr.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fieivwfq.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ckknsorl.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxlcrhx.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2moaofwfm.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bciwrlgn.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzicthg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2etdhsbrp.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhybzjk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkmkave.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjuoghf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2morgktfk.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2flvhhuda.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2esmhbubv.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrldbsy.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2chjoqmgx.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uwugznra.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzjymnx.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2svdfjifz.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjiingd.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjpcwqb.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmbyjzm.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2obrpxots.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zqeunsab.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bexvqmvz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwzsxet.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2myneffxq.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2nodebhtl.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2juwctxpu.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrwglky.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2poyweoyw.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhqkirl.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcoqrze.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwtfcfo.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2jlynwqms.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsawoehh.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdfvggd.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlnwsyre.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gzawbusf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxoalgb.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjwdusa.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2avzmsteu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2evwpfisr.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrzdajf.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxloipc.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sowycnla.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmcwvmp.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qykxymoy.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjziwig.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwcoayg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uaacmild.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ztaizeci.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mywwacor.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2xeozqkvy.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbstrovc.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mgruifpo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmunlipo.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2erkmcstx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ixiyyjox.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkiwmgi.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hncrjbma.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqssaez.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytntvytp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhmlnpo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nbikopqt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2deypjvfx.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qkaxscts.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjpxqse.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2geehlccj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wjlmofkt.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2eeagiowe.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2sumglkff.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2qbpfrrty.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2vaipggph.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2qichzxoz.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2apkqtmnt.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2celvtxed.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2xhigyldz.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2twnyqior.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2qqiqvztg.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrwiwvm.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2fcquavre.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2dfyobthq.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2naevjnvf.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfokdlb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2wfeulfcz.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ftziryli.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rimnudbr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqgvunj.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpusgjsn.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2twwvsujj.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdnhcws.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtmzwdb.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgzonog.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2zofrlyep.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2vaglwsar.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ywldrluk.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2fijdisnw.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2khrzfova.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2nstaodzu.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2isbsjvrr.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tymwpvna.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhvnhtc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2phmeqvis.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzwseli.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2nymljvkg.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2yafbewqf.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2somquxdu.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2gzbbclqw.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2dhejpmhx.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtrvqzm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpfpixo.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2trcsylws.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtravpfe.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2xprkwrdl.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhppgzrp.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjuaokd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2vluubirg.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2btmjugoy.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2egtzqtof.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxxabra.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvkbmfl.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xleaovvu.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmrzqfq.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsaysij.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2atqjqfzn.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2jgggjkzk.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzlqgva.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mwebfnpt.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjpzros.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2iveifqzp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2bjikxewa.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2wydeczys.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyifyfit.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvbkvrb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbbqlph.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrfaqck.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvctadi.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2dfkhtiyu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzdzufh.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmeaviq.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfctrqe.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkfgdxs.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2egogjpzd.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hucynspr.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfatcis.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2onbhmkym.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2rffpsyfm.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2npxudjtb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwfjvpv.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2loohhqge.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2hymkvntc.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yemvkcxn.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwunagjc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtvstbe.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvzbrnv.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qhunwnph.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2zjeefwvy.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bkroqvie.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2deinjqxh.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2herjnsxc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oepzsciv.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2uuurcngb.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmhcwrz.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2loqtazld.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhdjidx.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2lmluacnz.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqbvryk.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pgyiwnom.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecidwpjo.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2qifamzvm.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2jgccmplk.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2edinmcrh.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2bduizktr.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fgiyzzdk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqarmsr.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqyyhyf.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cprsdeof.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tficxofk.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ycryhmth.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgnubeh.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2htnclyoi.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxlsvay.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzirojid.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2peplcxas.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2quzjssbo.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vcohqghc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2olmxvtep.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2rwruyhor.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2wiunnnwt.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2zlsxvjpf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcuabdzq.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjnjjxi.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmterfh.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhficsu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fersqwto.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2otnjilce.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmocuzvv.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2aptgmfov.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2yiczxksl.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ceywyncn.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2sqirgbuy.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpnnupt.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnbnwqz.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2aoshhuux.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2lzaxqdks.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cypfgzgj.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2pugpossc.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ihiegvps.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2bwyoufxb.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvlegne.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjjylgd.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2anrbbmcz.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2eeygsgig.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmaszwr.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxwdbxd.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2gbarqdvv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvdqbmc.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkeckmu.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhduxju.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqhhayp.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2jhengfne.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2bvveigyi.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvdgoyv.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvlcucb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdajaqj.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lstkrzfo.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2pbdjyfvn.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2hnouktos.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkfkgdtb.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnxrnlo.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2xjsuoslj.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqkwtzm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2kelvfvwc.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ctedxkyt.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2fatqjyai.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nssbjvgx.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2fedumdph.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2uaroxuvl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2zuuobrnr.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2bxcdcjab.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrifddxw.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bqecvrma.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2volufppd.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2adwhtspp.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrbvnzm.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cuecobdx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsveouk.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyzhpdc.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bndclurs.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2snyvnfex.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2crrizvtu.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dflucpxw.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvbsoak.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2esressxd.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2okjaxjxc.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rquebjuh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpicxpr.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2vlejoais.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2iydqeghe.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nagfselw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2semooapd.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrhxhqf.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gopcptyd.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhqwock.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejafhekq.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfhpmor.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2upttofzi.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2yduvdzcv.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2dimfqdyz.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzyddfy.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2tydislty.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2fcboajws.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vezgqwih.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbneevk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xihvzaqj.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmpluxi.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2melqovta.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2bjczeudd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxzaopf.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2nkplmmss.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwuwqqm.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2sfflswyx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2tipdtwpe.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdlmwuu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2xjinszid.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2shkvrepc.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2zkguzwng.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpqsxdw.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcbbhjv.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2nynafbgn.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfdsxma.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcsrsyu.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkcjwbg.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2soaflodj.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2oyswemvx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjjfayo.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2azrlkxqn.html


<!-- 参考信息 -->