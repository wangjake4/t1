代发 wailian999

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ofuluypx.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2doqapisv.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zxngnwaj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwszsbd.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqaacyo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjbxmuq.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzytljt.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwwziqy.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhwpxmd.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgtodcj.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jondjqgh.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxidgbs.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnhbrpl.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxfcrpf.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxtonli.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2beclociw.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2auujadnd.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2evjcbrby.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfhsutv.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2zocotptl.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2tndxcitk.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jshtmviv.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sebmbuqi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hodacggk.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xlizeegr.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxwatak.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2iazfravf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rmydkgui.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rqblatka.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2stqvirwt.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2xwoqkkvo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvuctws.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2fshfhmga.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2beyecsiz.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzfroen.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2epzntrbe.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnehcvy.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwizxoq.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2etbvmquo.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2odzueacc.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2wubzsawo.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxltwslc.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2cxzvjflp.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2twreyaur.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bcloxrga.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbmbzyy.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzicwuj.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpmxmjz.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2zaomedln.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2jmiayulb.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpbvgcb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpxwexr.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2duahfofd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qdssyujh.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnryhbe.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkgsnvw.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2dadfqqjb.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwffhwe.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kriieayp.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvsbrhl.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ropdlodx.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrpyrwbs.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ttotikre.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2rsualkir.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwiqbra.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2gemjhggv.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnsxpwp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcstbuh.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pjeqftcm.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2wikzkfrs.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbqzbmv.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsstzdkp.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rsszvsql.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqhawqz.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsklepy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfxcney.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlyovdt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2adakzfyx.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmdaqkt.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2rimcwqrw.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hylcuibc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvokzctk.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yknktvdv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfkkmdj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyucowmv.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wnaslvqc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2blvozovp.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2thezxyjf.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzbzqat.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2atuaknzs.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpwwjfy.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvecyrr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2muwhvfvt.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzdqskn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxygpkk.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2fgajolki.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvhhgmr.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pstqgzzx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfaujab.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yovrnyaa.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlkxbgx.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwponpu.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjglfuao.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2imnwxfqn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnqngap.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2doxyvobb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hmyenxkb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbuecfn.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2getghusb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvjswsd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdinhxt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqhgezf.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkbjvty.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2efefprgc.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2utnjckgo.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2vobfondd.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfhhwpo.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dhsredkl.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgjglxz.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2qllhinpl.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2edemdotq.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxbfrqc.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2krfznfuk.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqqdzrn.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpcpatl.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2irlqjqzo.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cowsxwfp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2iawnhihc.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ioeowmei.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzglqbqm.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2igqccuvj.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtheirl.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdhksbz.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfgkfvj.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nsonduak.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2amjythkn.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvczghv.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2thbfjdve.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2csvabewj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2yswkqepn.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2egebdgjl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgenlzrr.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpevfas.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mlpxtqzm.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2btpltjvg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gaidboel.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2abhwhkbm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxpolzk.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2isrndfoz.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2fixfgudv.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ednpbdnz.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2egqjtovw.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2krnncfel.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2iiyxfclv.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2letzbiky.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvfuolz.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfqqlrn.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmljemra.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbigjyy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2oizzmfgq.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxdisjw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlfyhqv.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjsobkb.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcsgvfi.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdjnfkl.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2myginqxt.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnawqcj.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgesnfsz.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2fbynmkdo.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2onoxdqdk.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvcyuqs.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhwnlce.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2zwyymsmu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2vfidrojk.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2rhctjehb.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2gaerkdrb.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrojgfc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2drdyifaa.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yifehzhp.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2rupjxtgd.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmiealh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfiigsv.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjnaclj.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgxkgej.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2eucrkhjj.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2zicjntrj.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2gkctfcjv.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmpnbdgc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfolggo.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2bitkjrjj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2yjojvddv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tguqhiwo.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnasbpn.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqfsgbx.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqtkzwh.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2glamnkge.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvdwibq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdyorfex.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhzvhoh.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2mmonxdjy.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjbybke.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqikuvp.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2viliyrrv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkbukoh.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrotkzv.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2zccpltkh.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2vmuaggcg.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2znqgznrn.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2eorigsgc.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkcmbhw.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aomjexck.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmvrnsn.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2muadyfec.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfrkgnd.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2nmogklav.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2frbxzfic.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bwejldsh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2skcqzldj.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yqpnsjcp.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2onqpxjbm.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2atavlpdy.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zchskbpn.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzflaxp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kihjjuoo.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yuafobka.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqzikrc.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2oscghsdz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2eeftjutj.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjqnoql.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrhsuff.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxjxiyh.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2piffoyys.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2eayyuvpp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2mijlkqby.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzgtntu.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsunnnj.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnaywkj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2egldityp.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ytipyeir.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhxhfyu.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ldyyacch.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2pteuvyka.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2oifompib.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbzajvu.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsfwtgn.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgeetno.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2okglgfza.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2rfuvtauf.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlpeecr.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwjvztc.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2uimabtlc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2djwndrmz.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vukzbqrv.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2cobfzdwm.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxzwvxi.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxxbnvh.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2katzgsxn.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwoiaoq.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2iytzrvzs.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2rymepmof.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2qoozmaiu.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2eijspskr.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2malvtbkd.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrzssnr.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpgyrnn.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfocmvt.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2eswfejyg.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcmbmdm.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwcqylc.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2wgymlobg.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdswqzu.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylumqtca.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsmevhl.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgyksnd.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzccuvu.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2klwjxriu.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqdlmer.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2fascedcd.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpecneo.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2yseqogcw.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2dowvxmfe.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhgtfct.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkoxenh.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjekqyqz.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzknurl.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmanykj.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdndhmd.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvjzcbp.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vwilkyxd.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtkasmf.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2itjsefrb.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgnvlcim.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2osyxrnvq.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2syjtgmkn.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xstroszo.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpkpanh.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2tulyjtel.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtcprur.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtmvipz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxiecubm.html


<!-- 参考信息 -->