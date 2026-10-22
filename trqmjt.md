代发 wailian999

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxahxnkx.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fvsnurup.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2quhgqkga.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvkhoao.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fehyjayg.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxhvwyn.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2figrxklc.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjyosow.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svjxxqao.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxhqeta.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2fauqkhrb.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfjvohd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhmkwum.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhrwbaw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvobqmjk.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxkeial.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgezaji.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lakfbwag.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rabckyps.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2hpbnktax.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvijnsha.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2gpybcgcx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzouyxt.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vryljhoa.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwapuwh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxeviis.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2lzaqeyeq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wguvjuew.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pquoxouk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfuvtmb.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hukwbowa.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2zolgkfpo.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2nwyibyvm.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrhdfee.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2jtihrxkx.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gtciukhp.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yssjpzta.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vobprboo.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxrupcu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmwuhrc.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rynbozvm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hryetzyh.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2exwdyxgl.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzwarlc.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwdrggr.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2duhzmeku.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yhebgauf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsfqhwn.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjfnxab.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrkmyxo.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmbhapj.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2anieksog.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjhqcpy.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhefqvim.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2oeglflpl.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcxkqof.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbyropt.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqaemvi.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fflzhhve.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kozxytmh.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fnydoiko.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkbvzly.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjjwvet.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2sumwtlkj.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2llnmlczu.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tduonlcz.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lqimbzms.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxymxlb.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kdihgfzf.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnaivep.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdjxnsg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2occwsxlv.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aognldiz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2whbwbsai.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhbiwvc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfuxahqb.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2txonlexw.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2phucurxq.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2dwgvbudl.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzppqkw.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2sakhwjup.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrojjncs.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfgycnu.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmbohsu.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbjqxje.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvlksgw.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2odqgnheo.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jusvevwz.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2onlofvum.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhpctgp.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mqghylpw.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gendkowa.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbuagrv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ruflfieg.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrtipkc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2pliukxtu.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2zvsdwvth.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhrbjiz.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjloikb.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrnuotq.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ltecdvia.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2joybpshq.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vefmzsuw.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2xhlmljez.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jachuohl.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmjcoix.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfvvjhd.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2uagncfxb.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gclzesit.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmfdqpj.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lqyhivwx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvawxljz.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrtbrxf.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmslhev.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2djxsdmqu.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvvdvsw.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ltoouocv.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oywihzxj.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsozmnz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfyjqruv.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2igqtkpdb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyshgeld.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2itbepcde.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtqqght.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oslmjjaf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfkxgal.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jckoutnf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogybqjhh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2acbzullt.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgkxjvt.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdcnfty.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2inwqpfpr.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgvboka.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2afcdbwgw.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfhshrv.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zakagyjs.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2luqmpuvm.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2moswjycx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2keicjcjs.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2drpqnmff.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpvraxb.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2etsrdftt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2facfmaey.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqcpcax.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2sfarfkwf.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmkmipc.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrxykee.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2voueedtl.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2dczsqogc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbceuje.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgejrdz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tjlkcfjy.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2iluikktq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2aorkjjhb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2fmugaofc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xowgmjfh.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhamptb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2upqryxup.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2woqapjrl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2aslqtrjc.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpckkqo.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxbpnxw.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlgrajx.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2gxscbmtz.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2loanzjgk.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2uinxyris.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkkfzsg.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2soqjxgtz.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2srfrgabw.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2afbbpzvk.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2akfaevhb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2qibzdtdw.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qxblnayi.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zemhalsw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ryolqptm.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2glcgbdfw.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdojajs.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqalgyd.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2delvhhrc.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvdhyet.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkxyasx.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcngxsb.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmbztui.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2oivtkznt.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbhdbxe.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbbwmcg.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2oyrhailq.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hofmcweg.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbijqsn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2teszruby.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzqnaqb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgirclp.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrulooy.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2blemsfas.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvbdkzu.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwrivld.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mhigxikt.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2rirbiikg.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gaenevem.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqinjzc.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgjxoiz.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2drxyymmg.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2jjuqkqri.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjribby.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2bitlaees.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2plhmglvs.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2cybbzxne.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2nepfayzd.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rnckocwh.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkvdhyc.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2kewxmubh.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtapnzu.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2nahnpxjn.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2tuiyblws.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gemhixue.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2roftzqbq.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkvnywy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2mliwvjmv.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2rqthkhmx.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvicrxtz.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2eokuuzrt.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2hadbypve.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbjjout.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2gllrwnlb.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2drulncgt.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzpgfxl.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2plvmxpmy.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2qgauxfum.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cupvwlfl.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjnjwfu.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvxsoos.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvvvmwp.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2awndbzds.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvrfvka.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2eedxmawl.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2twsokrxq.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbeizyl.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2idkbdvbg.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2siitizot.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfcshan.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xocmzhby.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqqavpb.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2heevatih.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvzokms.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lanuvxju.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2zltrqwnp.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrcztrz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lliotomu.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2itzsnvre.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbrnabw.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2vovxoola.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lwupzzbj.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2iloqexjo.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2apjxncbq.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vazswtyf.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfmnuog.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2tqheemea.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2efivhkdy.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzcwyio.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgfdygx.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2muswjref.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbxesui.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwlezlk.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wesgzdyj.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qekxiebz.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2liceztrm.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtxxxad.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgxmnhd.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbjycnv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2niytyvnr.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmftops.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlaagfz.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2herzemvi.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdwtwmu.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmbhuwu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrqyexf.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2vexxllln.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2noafoxsd.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vcslhhxq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbliewq.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ahduzqan.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxquqee.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2wiykfsat.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhneqlhj.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2grpzcqhn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdqolac.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2detuwzuh.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2oxheoeyx.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2njttkzww.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwegpsu.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sjiblizu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2mgaxxolw.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmkywmh.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2bykzhfit.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2maecrvbr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgmicii.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmkggyn.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqgmlko.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bswsyhad.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzwistm.html


<!-- 参考信息 -->