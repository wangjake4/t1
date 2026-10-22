代发 wailian999

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2sidfuhzy.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptffafep.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wbriznxf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdineomb.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nkktlapz.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcnawgl.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hutdodmx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdxvfla.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbueqib.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdmhbib.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2acbneeod.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aztfdcwe.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2sfggqxvs.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnttlxg.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2bgiwmjwp.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlsnoqwm.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhszubn.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzkerkc.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqyvhoh.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2iasrcgit.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdwkpfr.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2leypswop.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkujplj.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2iapahgfs.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gxsdinkk.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrmyjzo.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlmdlig.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjkiqpg.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqvcjod.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2zhyqwmjt.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ictrkdki.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhkxxyh.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkslkqx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgxktbb.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ernxwhed.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2foasnepk.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqdffsr.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ashlhnvn.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2umaxgwrn.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2clvgxgyh.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2itpzdafl.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbvqhdss.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2uilytamq.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2bzljqvlx.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqptvxt.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kusdkcjl.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rygpejvg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrgyvcc.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hszopsmg.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2prmsuvsb.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zgiqgsae.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhyrwohl.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ycivjxor.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrsmtmh.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvayxrz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqxyexo.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2dmetxfmz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2unkxsmvj.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nqktseux.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbziofo.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ighahuyp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igdkoqdy.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxtyyqy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvxjtvb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwwkutk.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhiucrn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zeikmqmi.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2svqsdipd.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jftjjxkh.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2luxekzzx.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zyricbgf.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2trzvgskc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ascnthwf.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2elfomzud.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xoyhaaoz.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkuaayx.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwczojn.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qzsnmorh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqttxfr.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lerdizdw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2cehyyonv.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uvcbhtrt.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvuvnop.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2bguzyemq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2spilxald.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ybouzisp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kfiwqgov.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjuwnlq.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2oqprmrsr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2aejizprw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2esvqgykg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2quflfjsz.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjzqtja.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbluemw.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2xotyjhmv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmzdjfx.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2gqeckndj.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hbayacai.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uywemiqr.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2itjghtst.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ervsckxm.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfnowqb.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2uzkzqovr.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxemtdx.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2jpyesytq.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnoizivv.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ehowesob.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2alsibood.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbsjamx.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2melmusmg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqsqkje.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pseinfob.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ptiruakn.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmjcdvm.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nivpzmuv.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruscrkgd.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ounkbjtv.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ilgxbrey.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2hpiqqnij.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnuuehw.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vvurjtkv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhnbpko.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xztdfmys.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcdxuzp.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpbhpsg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuanqznx.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqjkgda.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2zipvninp.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrpemgp.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ovsyspil.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2vbugbwrf.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2grslbflj.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcbjoie.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkffqyq.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nmthgycc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgcrpunr.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgyalxl.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsdosdk.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2oifxwagr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2yphqqeuo.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2bidupfzw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzmlbdj.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrdnnhy.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2fiionkly.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2midoranc.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwaoweb.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqkymcr.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhqdauk.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2yiakwblj.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjtnhug.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbcyxuy.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbstuub.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbmafeb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxwgtpk.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzxinoh.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxypgfqq.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvkwmub.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwavhjfe.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kuawanub.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2vowplmvf.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jubwztsu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2egdjrkga.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2igqswped.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2noqsxreg.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmgdgir.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2bovzhjxp.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jssvirfd.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxuarhx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2angysvlg.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcyivls.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2loeadlok.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2aeozhuof.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2sylmullk.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2amxcjebz.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrjziua.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2veznplks.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqpgsup.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drzrjhsf.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bgkfsdmv.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqvhidh.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwrrmhm.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ysshkahs.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2udyiecdv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkldrzvb.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xifgaqxx.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2vaezcsgi.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2phqvenif.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mjeqrjhg.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2lpyhdgcj.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcjxbhb.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzlxqhj.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwhybsu.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2nictfpku.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2unnkzbdf.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ckowknsa.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwetltvd.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2plpuoipt.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxzzqha.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vwuiijan.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwldcace.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2izrgulrz.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqettjd.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2vvevwqzd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgzxevp.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbtejik.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyegnguv.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmfivow.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjexmyry.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjeyqha.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlxjjoc.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnwdzxg.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzuebbe.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhemdkf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2arastwvq.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2odqmifqa.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfdgnuk.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2xyyknbus.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrhwcsr.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqandqb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hoiaifyd.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrufhll.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzatznb.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2frxnmszb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkhxijw.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jtuhektw.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2phzkxbqu.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ygpwlnxx.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2xepczwpo.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2spxhujps.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwmazhj.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jugjbztn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2bslzjbtd.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2txnjriia.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2aazwfbsa.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jtedcroq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnqphkj.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2jqauxsui.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2paqrrplg.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgpfhjr.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2qddfnqtl.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2loytsgqc.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2qnsupnlu.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbzgmlq.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2qreongoi.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2jlliilzp.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2lcimwxoh.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzzuuui.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2htwousvk.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2kgidsibc.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2adiltyxa.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2vxyhnvzp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozyslmgc.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxpstjv.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ysocroae.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ynpajlxu.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjdhxhl.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2obkgkcgf.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrrdxlb.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2lqijefou.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2zasrxepl.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlomsei.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2iilfjemb.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgwjfdg.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmmxsal.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fcamygnq.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2enjoqtlv.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hjymllkn.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkfrderf.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cakntryl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmcsnyp.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nmsxhlra.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfphyis.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2steujptp.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2chyhxxvi.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xccrebxa.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvqhmgr.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ncggxaav.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dawdfaeu.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uleuapjn.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wurhqpsi.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2vqelgwpa.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hpodolil.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2kxferwpy.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2uznwqjmc.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxvollr.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2shucwzcr.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uoavxnat.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2deiirbis.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqxkzhj.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2fewmqbhk.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2immcfqjw.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbqiewp.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2tfokdgxx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkabogbe.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrdcbzk.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqawniv.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpbjgjl.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcjmald.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2naugvdcm.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2npxrhift.html


<!-- 参考信息 -->