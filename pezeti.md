代发 wailian999

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tarxioxl.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2atcyinth.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rgauqfvu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxcvnar.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2zuiyttsl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpecoums.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ythwuuto.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmjvgxy.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdkjtvp.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2covwomhr.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zqefvkph.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpflsoee.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbwkajh.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2znlvplbs.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmwpkkv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbnionk.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vujlrrhm.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcmcwzo.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwhonty.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdupiqz.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2gswnaeqc.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnyymsb.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hyozgdme.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfyvmzk.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrlllby.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnykdfee.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhfjcqb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mxorwwpj.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kczjohgq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rthlfifk.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2tnedkhpe.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvfhnwl.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2kisaaysy.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdyzvgym.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2kltxgxpx.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ieourjms.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2erejauik.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtevxvd.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvicbyw.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzreakd.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhhmytw.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybiajkdg.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2jxyzaqcn.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvnhqto.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2buegrbrv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfakjbck.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qcddcngy.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfdcuyt.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2xqktybtc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbycrsm.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2coafpgqe.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2yksstbfk.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ocflebnr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2callutzs.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lllhldpw.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ighgqkyg.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqsomrz.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2edccfzvh.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uepyjpye.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2piwlkpom.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gtiefhxv.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnsafzv.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpzbuzc.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzkvyxw.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbttent.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdrdflq.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2doqgkawi.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyeiwnrf.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlsfwin.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2rnodkaxn.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jpaelawj.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvyehbp.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fzyohjpg.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfiwtsri.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wobrljzm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2stjmuaim.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjlzrno.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxgscow.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhemyps.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2xphyjmjg.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmbydov.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iznysood.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2trjenbkd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2waazdxra.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbitkivl.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2owafldnx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcshsqc.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qmubpmqs.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bxnnijdx.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cnyofcju.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2acjggyzc.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ychititl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sijlixie.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uruzhvvc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsyblwv.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhtzcer.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2yudtcrhd.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2akojcanx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfdysbg.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wywgasjr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnykcqp.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kidhoylb.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnsqhalt.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2hwejfsio.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrdvcda.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2llwospgf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ravofyhq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dscwzmrc.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrbxdux.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2qjponxgh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2jugshpjg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kybmutzs.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2evlaimrw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdreosa.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2dudjhtdh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2bjuycvlg.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjehrpf.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2muawkeap.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtnttmt.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwuslby.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2sudivecm.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2dldwggjt.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xophzblw.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2okalppda.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ceozkhcx.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxueivt.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hfsteaeh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxlyimc.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zikkdhje.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kekicrms.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dgisrcur.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nexkneai.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvxgvzm.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2asrwtluy.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2aznoxsrj.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxcmmwjv.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhhvcln.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkbvcqc.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjiaflh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwklppk.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2arvdspml.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqanlkb.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnboyjp.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlieoppp.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqdqgjn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdcwxvl.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgyscfm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmppilb.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2spciojcr.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2tuupsbvh.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2sugdmpjr.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmytkeu.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lzeqlefk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2juaduybh.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtqvcce.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhhewih.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2fakxjjgl.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfgapqu.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2fxyyydgv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrsyolhx.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2dpiwkojx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2uzogbjri.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ukoudken.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2afuehjyi.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmfubxg.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2iaubepgt.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrhtuep.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uattosrg.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2mzcomiwb.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2fozzlotq.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlnkfyi.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqskjji.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnzlxcm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbpkxoa.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjlrpps.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmptnvea.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvagnri.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2wycjbzxl.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kffijyxy.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqukjbng.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mbaqdnhg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvjsbcn.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zxuigjkk.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2plscvhws.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2strvvxev.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2hutcuccl.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnjebye.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpaywprc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtgnisk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ypoejruw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2bapksuep.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcpjxig.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfryeqa.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqpkmfe.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2isluxfxd.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzutvay.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpxipkv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnzaknb.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjevizc.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2donfreny.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbfxavi.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2aaockpwx.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbplnho.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsikbaq.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mncbfzsx.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2fgiwlghv.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqidyba.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fctuipbp.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2pggwzljo.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmimmfl.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvznqvs.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkopude.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmueuws.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvcuabc.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbqqfol.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2yikiooio.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlftblw.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2mycbzkwc.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtjxvhb.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqbsyps.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zefqqplt.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvoeykm.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxmmqkf.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqinfwlf.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2swdloaxk.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgykmcqe.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2flpiglfc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2faxidbkq.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzaulwh.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pepuvvca.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnqcbeu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2jzxfvycq.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qobidwum.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2njlikdas.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2forafvir.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtcotrx.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsgxcli.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmfkmpgc.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2pioditge.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pawgmypl.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqnuere.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2vxynshqm.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtqrpny.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2uxebqbth.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qevattll.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vduzsrrq.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fvivjjrp.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2twhozlvi.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2giopgcti.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxahigx.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmmbjmm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2fdehaqun.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ilguewop.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2rftsxtcd.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmelgbx.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2vcsptqgw.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2vsuwyzdj.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2edsntygv.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2uuswzchl.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2maataeyn.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2rodgrima.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2pamtzwpl.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjqkvas.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjazrko.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2jukybojp.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2hywtsciv.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtpenls.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdvfwhx.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2cniswbxb.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2btskhdaj.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvexblu.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2guzpevmz.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqpxxui.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2pcodmdha.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2btiposyu.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2qyuntkqc.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqjcrco.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2cshgqauj.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxfywdk.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2dpltyquu.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqnmmtn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2rryjhfge.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2yltlewuy.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjytifam.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wybprjjy.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrkuzrx.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qwuodvwy.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbqsrpt.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2btwzyltm.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2laplrron.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2issgarhc.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2utehbycm.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cuijcegb.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2vzeubrtz.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yklrdeyw.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2bogbfobg.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2zikkqivu.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qycwdrsk.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmmdjtl.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhcfxnk.html


<!-- 参考信息 -->