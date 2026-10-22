代发 wailian999

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uayopega.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2epemdpnl.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jeibypfr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbamsng.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2njocerlb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsefxcck.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2eacrxfpw.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ganoobde.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnvhbhm.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qffptqwn.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbgqtys.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2grwnsgdm.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2driltqgc.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsevxmo.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrbtupm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrinwdb.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2anpconun.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gydmfuhc.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kndnnelc.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2xfellapd.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcmlabv.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkyifdn.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xxldperm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjxvigc.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2elwhuvnp.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgizyxg.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2boyppucl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqznrrc.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fauftelg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qafonhub.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlagiye.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2srgokmda.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2tqevorct.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyoegron.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2pkadzrgd.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2aadjjzxv.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ckognhex.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibonkiqc.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2arqlvpov.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhucoxt.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2cxguvlqh.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdxgemj.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2rmscpczs.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2caijxsdk.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcnisnj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsylsvsp.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dflzygxg.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nnczymds.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2olfwntfw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgyvuod.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2jusyaeuj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2fykakdru.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2uonfgjlc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2adfxsgdi.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yovbjous.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxnxxup.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mrohuuzb.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpofbjl.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnnlqwq.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxhdxdr.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ukltoayj.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lizvnizh.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2qxduchhd.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2nprxmegb.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hkttgouc.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlvscbd.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqtgmrr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkuyolj.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uzkyxjxy.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2naxhidfz.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uvllbkkq.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdasrtp.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lixfgvud.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxilxpkq.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jokfrdqe.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpcsyiv.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvjxbcs.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ultawlez.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kicpegjd.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2foobmtpk.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jjoikcni.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtybfrz.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwbugoy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdzbcem.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxbwztm.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcpveux.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzcdefm.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dynlngxy.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdshwjn.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwwaqlr.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2pofrykjr.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2suvlwequ.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouozetli.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqcmoes.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrylttda.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2foemqtma.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfptfjeo.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhjoyly.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzibcfm.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qdramsdv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2epmiallj.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2annprjgn.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvctqhtf.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2scfivsfp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2giuzcesw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fkfxhyvu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ahsprrnb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcssjvi.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwvzhqt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2mlsqoxck.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzagzns.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ntevwzcl.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ndohuizm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbusstm.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhxvwxq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2cijugbxq.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2osqkgidp.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tsuftdik.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqlcmao.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2mscxqmzt.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2omwvktbl.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2esvnbfsi.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2chezzixm.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2rksknoyn.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2shxcdrzw.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2qskjbslf.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwnsfgp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2atuucghw.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcppbgp.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyydhkrb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgehbyg.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qysclfwb.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2skvadoig.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2lijykukg.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2drxblgnp.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2diygzhro.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2okyafver.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2afjdahqj.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2hakbtqew.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2kriaunbi.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fljeorck.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2zouybrmz.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxfydus.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2feurirez.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2xyoghvha.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lagyjasc.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2drsexhcy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbzqvqd.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkxhitd.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2jqlycvla.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnvvoiw.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpidooc.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zxcwvxcw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnwwqov.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mlffdrbq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2oeuteccr.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwhdepq.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2aeiufafm.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2vywkuksj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfedoes.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqmqyzp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2tujmeazn.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2uiniulid.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2gupcjgdv.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxkszkb.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfkbiyj.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpajjpk.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qaarwvzm.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2wulobbmq.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpnywow.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2viifsxdo.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2jslpmmhr.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzofgov.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2osouaqls.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2iutxnlwv.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpictnes.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2hsttugsi.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2gardlbbd.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwflufx.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwelgxtl.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vaviqhdo.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjpxsdd.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mbuqintv.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2fyeedjed.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2oyupfxfc.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvqumjp.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2pkdentww.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywiuhfxj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2cyimdwky.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2vplegcia.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdlsptj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cllgbcje.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mcoqrsaa.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbqbzbs.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzownhb.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpaitfuz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfdyagi.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwkqzgc.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2psjvagaj.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2boqhnkjy.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2csbhmugm.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2zdayfhjh.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bukuyyeg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnbdkve.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ayizykbm.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrkbmxy.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgzfnxl.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2swpdostw.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpqtdxl.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvclncgn.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfiwwqc.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjleutd.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2zatqithv.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2schkbqyv.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2hclfxdkm.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ynobczpf.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2llwgxlih.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzihjkq.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzbvctj.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oucnuirs.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvfhqlu.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2txyrvyuf.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfvvaay.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdwazjj.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xazqxcoj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvepizvk.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2vmuvcdib.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfoetln.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2iobagwha.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzssrkcq.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2avejypgw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2kvybhpna.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2knrfmyvn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbttcofh.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhewzoa.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2qaroeume.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2lszdxvzl.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2izffirxb.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfnfhli.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2slqnhexv.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjgpuhs.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2hhlphamk.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jofemucr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxnmhvu.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvzlmce.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyoydwqw.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lneagsxu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzjydkg.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2onzdbuxp.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdmfzhv.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2evegdqzs.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpwcdml.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2odmznlbd.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrsoqpv.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jvsxquxs.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbimtvs.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ljifkbyg.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwfvcww.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqsfyha.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwyvgabw.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2mgusaelh.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnwjydv.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxzonkr.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsgqxez.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2fbaoeonl.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2iczjmhan.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxjfjib.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtxxshe.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2bpavomhp.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2oyddqjnc.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2gagqocjm.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jywkzbqp.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2lahqjwed.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2gsajlaec.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmddhwx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtxifzv.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2wxycpktg.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2erfqoscc.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jqocghgc.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2zvidebht.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlimtpj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2hucxpxpz.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2sjitsxro.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqwebqj.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvxjhua.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2snafexbq.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mfikchio.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2osuxdutw.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnmozih.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkrpbuw.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ilgkybnp.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2szwvwhum.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgjnxhh.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2eldcrllp.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oiubfzpn.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzetzxsl.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwhxxgv.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2beheozge.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2iregidkb.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzcifuf.html


<!-- 参考信息 -->