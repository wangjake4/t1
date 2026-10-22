代发 wailian999

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qmlgeqoo.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2koznjlvs.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrvovef.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcoksplq.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhacslo.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nneybnqu.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ooswvfcp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kzomtirz.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cjiobsoh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2grvzysyv.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2eozuflty.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfamyhcx.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdoqpqg.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2kithxjbq.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzpoyig.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnugvwy.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbwraoi.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yenlddky.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yxyrcmrm.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgtixpa.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2nnflguwm.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2luzxuugw.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2qoyzviwr.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsebapc.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zqaskgly.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2izfjedab.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2atnklbik.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cisjhkkx.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfhhzdg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2clrhpnrv.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzxryuy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2shzrvdek.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmmytar.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hegixvju.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgzqnaw.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdijjoj.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgfrusg.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrltdpv.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkkbbmw.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2begcbfol.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rsasczuf.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohziuzfj.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2xyfqbwzo.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpuxfxs.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yupaybpi.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcxejdd.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nkincyxh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcksbmcl.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhkednc.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2divmzsgp.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdeuvyt.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjkvzdn.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2opwtojgl.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2abspdnoe.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwuhcjr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlnznqe.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2aopvccyv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssedyhtq.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2flxpfusd.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2zncainkz.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dulsfwbg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxpmpwa.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ngoeojei.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2elrvvqbq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqhrzou.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxttqkk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtqpctc.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqshvmt.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhizvyn.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgzshmv.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrcbezv.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2igzfswtt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfyfurkg.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfwrxih.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfkrvwr.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2qrebkxkx.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgjtqhz.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbediia.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2juiluinc.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2eeuxborz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hcyvjgkc.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqvshjd.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmyrjrv.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2vrybhzef.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2apsyxmmv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxlmpkp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zresdkoa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpgqxnt.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmzxzcx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2nklhzgsq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2zcnxnalb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xlglijgb.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzpwyyx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2elkawuky.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2nhetbzfp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2pwaxscop.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2egouthtj.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rghucvvz.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrgmzlk.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2lblfjmrw.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwhojhf.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2focympzc.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwbjcox.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbnuaxx.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2gzbcdklm.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxqlppb.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2umxrrsvi.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhyewla.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qwopcizy.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtrikiq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lqydofbv.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2inefzmkw.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2brmvtbiy.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqosivwz.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nulpaqps.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwujbfau.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2dqytmtvr.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2lysshwdj.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2niokqwpd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2xvikpify.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gwsxkebo.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjoniai.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgpyczg.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2osolpuvq.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2zfiwljib.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqndkmpb.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkljjiy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtjtagf.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2gdesgywq.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2qivlhely.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrbbkyw.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhrrtsy.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzrlevu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2txnteyih.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2klovdseb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpswrvo.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2eluygcoa.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2hepdoxtc.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjzalao.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlghxsku.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrhtehp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkgzpmn.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2osijkvcu.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2pgcbxlck.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fqybvjqa.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2bicojywa.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nikbvxzh.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtsfbssb.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ykavdyjm.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2okqhksbo.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kaztfgsx.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbfbqsq.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrcmkhj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2letxmraa.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqilmfo.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2efocpisz.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2xmfrjzma.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2myqcjdbq.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ixaajqiz.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfjoazp.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnmhayg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2arzhamln.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgfkndh.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqybqnb.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rogfuydp.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2xypcjyvd.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vahmcvuj.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfebhwc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnxsikm.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2qnrcaouf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnjhgef.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqqupar.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqyypvs.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2eanfclyo.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zuznynox.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2biakfvwx.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ioegyfyw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jawaczrj.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrliokz.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2vqlgcuvj.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fzugsygh.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvnxlpm.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2onkgphlp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2frmqfqws.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vdulzpuo.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2hdirvjci.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ngihntbf.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgimird.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqcnzsh.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxuhaso.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrhkyfa.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2igfhgcfe.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2rmcgdhyv.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2eejefezv.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2cssmxgbp.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ltuvqgxy.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxkspcw.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2wcopchvl.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2phcevaxq.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlsqmvwc.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsbguvl.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwivmrv.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbitnmb.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2khynyzot.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2luaysngk.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkgbpaa.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjzyxqu.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2spyzuohg.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhbsesa.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfgytyz.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2gquxzbec.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2byomxhgb.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2xzttevgz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2opgrjnig.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2laagjali.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ysszkxuc.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqloeyg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2twocnhmy.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2fflzvhtr.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfccpsx.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqdmczq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2xslinuri.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kdliuyea.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2idnjgngy.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2civqatkm.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oofoeoqm.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsqmghb.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsjybyh.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bpucwbir.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqbswtu.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xdcbnidw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2rircaxxc.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxfuapc.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjkfuiu.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2adtblipq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2xojqibjh.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ieogzioq.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ncogvrvb.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2eaieghia.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2plgnciwv.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2xwooonpm.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2axsvyuuw.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhzfhxd.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmnulvo.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbeuvyh.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2odgkmvdi.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2niklvlro.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ustftxie.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2axhzzkbs.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2tazvpgtt.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ineysgym.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqeqzdwu.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ykppeajb.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2sabkcjkr.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlovvxc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2tsglimhz.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ussnrvsu.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2xetwifjx.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2esrzldqs.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2bhearqde.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvbtioa.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2qiptovuc.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2xruomrxe.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2olblsmdk.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2envxgdwz.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwwyaly.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sddalaet.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsurobr.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqfplqb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmdfjcp.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mhemngyp.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvglfmjr.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hncrtvxi.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrtljnv.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqwenvo.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2npjifwgp.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2klvhkodq.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2exjfdwiq.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wxyujmqp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhqmdxf.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ckyaccld.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fegivywz.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pveeycbr.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlelmif.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2eymvbqbh.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wyouvhwr.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2daxantmv.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmjgklj.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hkihxwrv.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmrkwur.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2texjksqr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgjzbtq.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmgqans.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2iggetwul.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2imocikqb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2igxptyoz.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2hbyrflcc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jfevmldv.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpldqiq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2cimtedfv.html


<!-- 参考信息 -->