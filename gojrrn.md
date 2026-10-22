代发 wailian999

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmsfzeu.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tnfqmfow.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2lfagqzep.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdjrulq.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnlmwly.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgrzrmg.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdcfpcc.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxyachw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkneywii.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2trtjgicd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbogkzmo.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwtexuh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvhramv.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kcznxmeq.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bffphoos.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xxeuvqvi.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzrhcki.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zupdxpvi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2mhlctncs.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uizsirqp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2krkkcvmp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2psmacbqu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2sslrdgzm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ighfyznz.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gylkgozu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vumpcxhu.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ysszjjap.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2nxiiszpo.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2puegptvh.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2skvfebwn.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2gpufklhx.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fphbklnx.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvxlups.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2iiaubmqp.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxazgwj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwgdjhxb.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdtylex.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rznyiidb.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtfihrv.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2oszuhsck.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eraxxpjj.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2usjfhacm.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hkokkrew.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ulexnkmn.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2dijnuxbb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2fygyxqei.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlsyvga.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2adudnood.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2uctncskr.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gehukwju.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvktkwh.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lismpwcd.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ohaoykpi.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2qohnpjnk.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iozunvhz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgockuhh.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfmspoj.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvejeay.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlrykcn.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2arqjqnqz.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzhwcne.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwexikti.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jqegylfg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2giffzbvk.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oecepkov.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjcovmc.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2khtbjtek.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2keszxxjl.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqkkemw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2azszlzoh.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2koosmciy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2njjaoxuz.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2aupkyrfv.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxuuwea.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2tygtikpm.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbpgtml.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqmxtct.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvwajzb.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sesxrthk.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2bszhohoy.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvonlyh.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekkfyuhb.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2rwyoiofd.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2agfmwlzw.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2svjjfcsg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfulzohj.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcyenys.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nsyjnsxa.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2amytmfbi.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpoyjks.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2pomxbfjw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2qqblsdth.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhikccg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hxiolinb.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zdezqoyf.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2azrtnucq.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2pdguwtoj.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdvernl.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lgyrpbph.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhvofdd.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2apcpzfrm.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxranvqr.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmpjimw.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2cvojawai.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vthwsrda.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfoxfok.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdwfokk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbunqxbt.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2iimglefz.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2euepdwcp.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fksptalf.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqxiuvu.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnopyvl.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzjunup.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vafetfsk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgephtk.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkwwwjo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhupewl.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqflgdw.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtoeriz.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oylawvid.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvlfflnh.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2appfbefh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtyisqa.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdudvbsd.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2okrxrotz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2namnqsly.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fqizdefe.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cutcwirq.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qgyonhpc.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkfpxsi.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2chiuagyo.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbqfpmm.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvhaock.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzzaubg.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2aasmxmqx.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjqwvml.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzhcjtl.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xixuiyfj.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2juyjwwqy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2jehteqmq.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwgzpib.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppomkmeq.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwleznb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzdmozy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwqtmce.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aiivhgwb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ledtiukb.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jsoeknet.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2drkcwgau.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrefnwn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcutffl.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2pllnotmz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgtmbks.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2qlubbhgd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2odzxhxpx.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2awunrrbm.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqdqzjn.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bglcvjiz.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpafzyl.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvzqvlw.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcebpws.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2beaslwfd.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhpulov.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxloxsf.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsspzjjy.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2agfrltza.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfnuqxg.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnmlvgp.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2edsybrsc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xqcycedz.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajphdbha.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2flfmnqgm.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjqysoy.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbmqqbk.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuinmscc.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2umewzvnd.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2edytipde.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2orqshxwh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2muasrviz.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcjcofr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpyjtst.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwzqawo.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2asywuujj.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfifjuo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpuujuq.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2nufefrhd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2nazahqfe.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2wldybfgy.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2qujffyvo.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2nvoammqx.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkjevjb.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uiuzdekc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgkwwal.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbewohs.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2klqexnfl.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ceopmnga.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2iskpunkz.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2actveuvw.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyngmrxy.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdcjami.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2slsgmubu.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqycbsy.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkolywz.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2nuuqnmym.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgmtmkz.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2aclaunnw.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbdyyed.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ashfeczn.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2iqafainu.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kywfztaj.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2tpchrinq.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2yupbsnwc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2xtendqsd.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2pftbooyk.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpcriawo.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2herjkrsy.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2wczjhpoz.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tzyusunk.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnngqva.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rpibkqch.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2bglcdbtv.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ajaaxlhi.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2hcguaial.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jijstzgz.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2jnuafskr.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2auchfsvw.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2owtnxarf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2eesbltcl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2vlszjngt.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2acrtgear.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqfxgin.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rktxrrub.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2uecgwclp.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2einbrrzw.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvlwacab.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jhszzkea.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2acwzrnec.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpglgks.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2usdtdmir.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxzguhk.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2updwlcpo.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2oloyzpan.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2appbfzxj.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvvyduz.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2vxasjalj.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzyhuft.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hebhjgqk.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbbibme.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqbcxci.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxtqvsf.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2svhqcgpv.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfstaxm.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbyxcyi.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2zafoiqvd.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2kurozkei.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxwjanu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2vksalfvj.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aivndwzu.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cziioimv.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vqnesswf.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpthkyu.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfvedsn.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehorhqdp.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjrzyhg.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulteimiv.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2czjkdayk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2socbfzbt.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ujlpfvtb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2frjldmwq.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtxkhru.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2zvoblocb.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2pwpwcimo.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebsgdlqf.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjianvm.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhuzked.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpqjjwc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjvnjcc.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmghiih.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdzboxc.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmoewmf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwbypit.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qsyqmqop.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2kfuhlkxs.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2krpftoxu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2riierbpe.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jdydihax.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2nqknznqo.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkxvwwg.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfoznlb.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xnypmlkg.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2plrqnlml.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zjedvnex.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2esvedsrh.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pktkhagx.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2axxuqcki.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkrjwds.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2zzylovuv.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2azabmyfz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqlqnelr.html


<!-- 参考信息 -->