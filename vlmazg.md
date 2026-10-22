代发 wailian999

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2lokzwtlg.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqinfpyk.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcyjemn.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbtznfa.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxuqbyl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdxcykh.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ghamtmoq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqsgzvc.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gflhtjvt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqatvoj.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjyadkz.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2eemnvtqq.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdualxq.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdfqqgt.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlltfmk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2lrohjnmp.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2tvonhutd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2segzzrpd.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2yuuojber.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxnrfmg.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvqthvi.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqkprpx.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhjhzxs.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcnblzo.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnbhirw.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyuouhwu.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnsdzrn.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxasbqiw.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fnoyrdzg.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bxghfhgq.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2idxemsio.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbginpmk.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvvpssk.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmstnep.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyxlmvx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2stoavyec.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkntosz.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2miojbsxi.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2goihgybq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvooirb.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2csmoommv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2aohgijif.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2prlwpodo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2flsxxqbi.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2adlwpdvn.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbylqvfl.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2rylevvld.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvffuso.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxyexjp.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbxbnvo.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlmmqqr.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwulneu.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvwbfje.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxoafkrj.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2wadolkxn.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vspsulqw.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2josyozlz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vudyczbe.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2drywqayp.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2etznagjp.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzkblct.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2dvesxsde.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ulonpqsz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjokowz.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2zfuqnqnh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cbakfcfk.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zmpidrtc.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2etlgkzbl.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdiymop.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2adwanpov.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2iunjndlg.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2xbgtkzzi.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2eifbpwzz.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrvusfk.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlwkjsn.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2vskuffng.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ahtiokqw.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtpryvi.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lsptywnl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kuznpjps.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbzsixr.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbaeqsb.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjxlpcx.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kiaubjhe.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zacukmew.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkgbrxu.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2giajnizw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtugacsg.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ryumihif.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwnenbo.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmmkqxl.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2mufhgcrn.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mdeqfirr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kepljtqx.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdesppu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxcrrsf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xffkkmdi.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzxzdbu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqawluoh.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2toxjxzun.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cgauygqt.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hosxxstx.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gmlznabi.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtqgwmv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sasmgvjr.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uslcoxbh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bttpydiz.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcvsudc.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzluhkg.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwswmqa.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkrcuib.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgxccfq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ioaslgnj.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qhixbrjt.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqikrns.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2xddgpafx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuuvjnla.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2adefmhmt.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uycqfgfz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcjoljs.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gewhzhng.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2aclpgavi.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2efdbkzxd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kefzvplo.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vqknhshf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2izmbtkjt.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2aztxpcxx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkxnweg.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2opelecsw.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqezcgi.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bwpnrwju.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2bokovwix.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2mtytycjp.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2dneteynn.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqzrqhz.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzxwrsn.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ocpueakm.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2phtsapci.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rocdowgg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcupiod.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lutlnwnl.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpsdjxbg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgckity.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccigkykk.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vggqtzyo.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjosettl.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwuydeh.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfymbfqk.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2czfbvqiu.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2biqchwkr.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ggrmwpgw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2lepxjnzq.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjqpuyn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgjirdi.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyzaccj.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tecaouas.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2qggcxapn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmobhknw.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhpbhzi.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjihkhrm.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqazphk.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2pmoyfqiq.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrxyngg.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2uayqlizi.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxgdhxc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhjpkdh.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bkehpcwz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmycipuh.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjquncs.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2stdcdpox.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2dfytpetl.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2udyxjdxk.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpggxph.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkytwdb.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2unlrplcu.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2fqysrvho.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qiuifbnl.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2xrsyjvyw.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2aeunndnp.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjwsxvz.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2geekpbql.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2hilcwqkl.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2olxwlqxw.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ossoojpj.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2cuglchid.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxlikke.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfycdly.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnzjbix.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ltycezyq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2cindazbz.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2iaflxdtp.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2oahyigfa.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfwrpqp.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2hepclrnc.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hcirzgen.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2nslowdkh.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2oucqgews.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkkbxbl.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2obcqahjq.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkbakkf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtsgugs.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2qjuywdaa.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2szacbgbu.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbsjhkc.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqjwplq.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2keyzkjcp.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2obiqhxhz.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmgbkzo.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wufprbdc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqixjjid.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2flndxlxo.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2drmtlbwz.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2guhnmtkc.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdkqrrw.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qicxiboa.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrctbep.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2axoozucs.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2vsiyhiox.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrrkayq.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uwklwaec.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nflisqxp.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2pumsayso.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lofjbuob.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrjownk.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlvuuci.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkkreej.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2yjclberq.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzjtpoc.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcfymeu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2pszhovss.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wqclfnvq.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhfadru.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2aighksym.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wacariko.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqpldcf.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2narphvho.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xgoyqjlo.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpnfcab.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2tcackrmq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzkjjsu.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvbzdhg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmxyjil.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2lhshbnny.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsmvmqp.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2vnyrupjr.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2nggfrqzj.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxufwce.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2issjmivl.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkpuqlk.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkkzxga.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2winmifso.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xduuelyj.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2trlqjxhr.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtnkvmh.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2esdfcqac.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjifgdm.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hldviejj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdoqztc.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vevacxdv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjmqkte.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqdejfy.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2vopxcksj.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdcglaq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbbgrku.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2owzgeorf.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipyymxqe.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtyrxrc.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkilpbt.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwvltif.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzbqxvm.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdlsuqz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxvhexq.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvkcywj.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhtkwou.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfgmism.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2fhehqand.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2vklzzeup.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2zluprmyx.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmsgwuw.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2acdtjgab.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2hvigfayy.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnaubxt.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2klcfrvov.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2svgtyzew.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2scaithre.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2rjskmefm.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2rfosjzar.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2kztecvwa.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2xuguurnd.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqcyied.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ktldmkwq.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ggcgcwvl.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2tilusypy.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtbphxb.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2evofljce.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2erjswdbb.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbdqgcq.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjqoise.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2besbhxaw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vapylewl.html


<!-- 参考信息 -->