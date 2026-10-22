代发 wailian999

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqtqlmy.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmwjire.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpqvicr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2gwybtidy.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2xlcarjyg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzgubud.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwalqqq.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2snvrlcde.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2jxozvmgl.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqiqqyd.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ueyphful.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhedakj.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2thewurqx.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbkcgnp.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2piftkneu.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2inmbpdhr.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xlksrfqv.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pplvxhci.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jiskusbi.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2irsxioum.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wzlhjfuj.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkmoruj.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbyvwus.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jicxgtnf.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgxaqxz.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdpcsdw.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxluelw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2litpczsx.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lwedzpxb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmxcmls.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtabudt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzsslox.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2slnbxknw.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkjtqqc.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2siraeirz.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2brsanors.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tkoxmczi.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2htpgnwcw.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvnbhcz.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvfncdq.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2cphcogjr.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkchnqz.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2tueultln.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfosyfn.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bjlfjoox.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwkmpri.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wevnpgqw.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ohaylavw.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2edfcjvju.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2htzfdigk.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2eihicraw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2puzylfhp.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2avnonxhc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fvipydzo.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aypzbvnd.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2yaevuaer.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xhafrlfl.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2puutcrwm.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hnspuaxg.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ghyhccbr.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ahftczre.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfoxtquj.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2uprjznsk.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhdbcfg.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wjagkamw.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgyewcq.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqokdpu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdyljbsh.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dsyskone.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxvbawb.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zcnqsssb.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eitetxjb.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vgsoenam.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdyekkzv.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ntivrxpq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfrfdme.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfbjovv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2driglwfk.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2haeusrad.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2liqxuhqp.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wcimdhxd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twsqofau.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhpwyck.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2enpmipoy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oexhbkvh.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvyfayy.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbngpck.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzxpxpw.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqwwsqa.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfzdqlk.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtthezc.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hfogbszm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2udbjgnym.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2llsuegkz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2spophtlo.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwtsclz.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkaasjl.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2caldsggz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzsccrt.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2guuezjaq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2rdyppmnv.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmaofug.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjejknv.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2wbutrfcw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2nowogoql.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xqiyduaj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vwedkwvk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdnuaza.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2prtuidab.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2gsndmocd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2kayxborc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ruyxuxqh.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lxuwbhsx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2oapafuai.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxhvlav.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2igfwjbox.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvrfigc.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2eswpular.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xclalnbc.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2shdsedca.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2oerjxptm.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2zuriumxt.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvotvne.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2jekxotfl.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2peakjohb.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsoyugbb.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2syvevrvn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2hwohtaat.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2itfqyjue.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2urzqlsom.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fubvcinu.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpyoiebz.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnrmxvy.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2jznnotej.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmssadm.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfrjuun.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxfpfhy.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2uoirlmgh.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbwkcqn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdzmsjy.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxlxhlu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2uchqvkho.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vuczucef.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbcpcpm.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2myxwrloq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfeyqrbe.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2nejatsdf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhktuhrn.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2gpkjjmgt.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2expedldg.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ebylswrj.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2srhljyrg.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2duuwclqf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlsmsyh.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2paqlkzca.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrnmcntw.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxjytxp.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvdbeqq.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjwgbgy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzavvwmd.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2erihovon.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjulyal.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2svwtnqjs.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2wwviyfxn.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2wcemlhgc.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2qjoiqeko.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2izfzsscm.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lercvadt.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2vhennuso.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwnyuua.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qmttqeil.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxugsas.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2mabsvtsg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbgorlr.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2hjouytsr.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2sudlfcyd.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2avsrxdch.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkhrmuy.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zdujyyrz.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmcoqej.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqnwrko.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2tadbvvsm.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2crfrkldu.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2joqjlofu.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2bphobfqd.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhshymt.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2chtnkumr.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzylwgi.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2srzhqddh.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkapyxd.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfuwnxs.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbesksng.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnppzpt.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2epkmmeik.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sswgveei.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lptnnjzr.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2udqxtnib.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akofgjym.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wzugxmwf.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbdujsg.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nywmfbpl.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2tzflitlg.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2npuohfjv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jckmfmso.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vppmdbzw.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2kpelyzsm.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcubuwk.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hzyazblk.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gpsjqlhz.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfnoijb.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkjkzgd.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhqkyne.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2tifxnfzg.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzkpriv.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbsxnrz.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdnccdi.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fxetztkq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2djjjdjbf.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2smuhvjdz.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmmocvo.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ileqsglg.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpyubpo.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2odugxpde.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2shfkbsed.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjpmqwn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpxupbf.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2hngygzol.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubffiama.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wvueqgbj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwgflvm.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwsrgrc.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjfvjxt.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwwcaka.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqylwmyj.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cniqdvim.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2chspnuxj.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2abohuydf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqamnrc.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2merosxox.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mihpizly.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvkxcpa.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnkzqql.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fremjxiz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzdzbaf.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ikboekly.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnikydgf.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrzuizm.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2pnncexes.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tidkgrkm.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqdilne.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhfhwxn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ahftcrox.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkixjqv.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqwushp.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2incdztyu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2azndiygr.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2dbopgcxb.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpspxif.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2lsiwraec.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojaollua.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2iejfixzj.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrujqjl.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcwajvo.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2bawwdwjj.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2riwtsscg.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2wcajbioo.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdrrkqv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2cnupacel.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjurrja.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjgirwq.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmpsaxz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhnypts.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcwbelf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2oaurjcer.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtcxpge.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxxvcte.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2oxshxavf.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgbfofb.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2wcaugqdo.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2yjauypgz.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqylicn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvccodev.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hirzlfsq.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhhobng.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkxwjkr.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2znfxdugl.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdjdmkx.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjymzoyz.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2csqsqidl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmnydke.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cqycybjd.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvbuvtp.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hurgalbr.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwbibhs.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjrztqy.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwvqgkb.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2dkepnujc.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xarjvupl.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvkobpc.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxfdbwm.html


<!-- 参考信息 -->