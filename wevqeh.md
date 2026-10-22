代发 wailian999

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nevmbfjq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqazkvuf.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eizqkpfn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjcbibv.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzpjmqb.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ntolbvnd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2meukidce.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhkwjwj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wugqjtiz.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2svrmjoih.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqesxec.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2hjegkmbl.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxiqpgkf.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2asnbnkfp.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnsproi.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ickebwdl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpttoro.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2revdellp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvlfwprb.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2lsicjxmk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwilytes.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2klfpxnsb.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdizocim.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2isuxvxol.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlzdtuo.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ikypnibk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbktxit.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bstunpba.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqvvgyl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqftfwh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ybuuvrfr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbthmaa.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmliwqc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjtsjlu.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2npucekcz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2wpycfyqs.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2glwdoobb.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vanfirfn.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtzeazu.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2riosjphn.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdynfxc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2prewydlt.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2geqzcvml.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwlyhcg.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfzznzf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bztbszou.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2dnejychg.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdrljli.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgqmeav.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2apujqlzg.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xghkmnvy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2noklukbd.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxrduxs.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2vifwigvd.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2fmikrhln.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgldcpr.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2looisyib.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eidadakj.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpmgshr.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2osvmmqnz.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqmbmxq.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dprxpyux.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2onedocyq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvpznzu.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pycfnsmi.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhybsoc.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwjzetq.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrrqjfr.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdcsbvs.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdhsmle.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqhcqmw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tavcrcra.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jpwuxsdy.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2shtzwmwe.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hdchcccg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dwoyhcmo.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsdugij.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqoeohra.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2mznljwyg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qniesgno.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2pvowlkvt.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbfzsgd.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2sotstulq.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjdaqhn.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xsszyyhw.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcsviwzf.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzywinm.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvisncbz.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2laptxtad.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqiatoy.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2lllsgbpj.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmggshqj.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rxikcpkj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgrlntw.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmzcnfs.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhapczj.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2zpijvjnw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2sffonojl.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2bpplxcfz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2jjemzmms.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ilweszip.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oohotiqe.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqyoeec.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2hxldvvku.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtkakjw.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwdhxha.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgzqwvp.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfxzebz.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zgyvpjpa.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjeeuqp.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvtqmkk.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2aawymizi.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnqnrdp.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqprjln.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fewqibfo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fruadymn.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtrxffr.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2upbqpfkd.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qupfszwr.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbidpjgo.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2grcbkhlc.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twhstrck.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2akhrnpxy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhogtlh.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbqjtvb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhejrvj.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdlaypb.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2tobzbixl.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mxteetga.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjtfuih.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mfuwudos.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxcyqps.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnjlvev.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxnopon.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2svqsdolg.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vexedjkd.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2alnokgft.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gcyplmsv.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2eokqkzss.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2udvsfmdx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2riffjnsp.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwxozae.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrilkqnd.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdielyz.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmmiigu.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2smwulkip.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zoytbibh.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2npeszmob.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2uyaetxik.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2njykzaoe.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfiuyrte.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjhbsvc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2vafalbnp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxmtfrb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2higwjptp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2evkzjzqj.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnuozzz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdwetgn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnguqzj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcrasuq.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbsdkpu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2hqivrcej.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2bdyzceeu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2dockfheh.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2shfghajd.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pmllvzyz.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2atflwggc.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2xmiovnxv.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvrmzfg.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2dchkvucl.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhkmhwz.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxqfdbc.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2mogojkup.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdbjzjv.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2umzdwahq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2xatjfpiz.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxcgozs.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jorxdfgg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uucxjnlp.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymusmgbv.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pbchloka.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2tymoozyk.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgllfuv.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjsukkl.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2vpuymlfg.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2kaifrmuc.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ofeybsay.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2prnlfbze.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2olkeaqmd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2omhblqes.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zhofwimv.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvphvbl.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2dybzrqzi.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2etnywmlf.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2eifcefkt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2rymykmqz.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnryehw.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjjgrug.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjqyzhb.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsistyn.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fbiggbll.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjwwutf.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nsorrbba.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdslbdo.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfpzojd.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcszoego.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbmgsyy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfihqgp.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzquyqd.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2idrklixo.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2axbewrka.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2xpptcirr.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqoebyr.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2yivcedip.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhwsswt.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsslndui.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjfcuts.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkmgdcw.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2errnmoln.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmxfsqf.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2tytodfue.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2xrezdqsm.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zexlcoqq.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2njctxogg.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2vdphclsc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhiwcmsb.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxjnams.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2etmwdqll.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2oikmpsca.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnkxdbu.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ktyjfztb.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgvetdk.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxivtaq.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2xoibpwgz.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpsqvsh.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxscpsjc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfvdatp.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgnfirv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqxhjsb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2obsqtccq.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2unkuynlk.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkezoubg.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2odujrxpi.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmaftho.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtvtytn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sesmbzcn.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2suxkzokw.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfccfil.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmewqsv.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2wwiwotpg.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpzinsh.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bisghtvd.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2drciwmlu.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2xoouedff.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbjkdqt.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qyykauju.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpsknqy.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzoqhzg.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2filzhehi.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmhffqs.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2tslzxcay.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2blrwtokr.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2bojzxiwe.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2dfiaybzt.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2aotmjugr.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjaprkv.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hlczvqpe.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhznawg.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2awxupjuz.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rleyfhrv.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2svnvyqnr.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtvdutp.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkzdnhh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqkcbro.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2latwnqve.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpyqcix.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2iyejqksx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2eohrexni.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ddycqmwt.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvtutgn.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2xlsxnakq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2egpxnquk.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbhddlb.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2pelxggwn.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhmtxfx.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bexptuav.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdhmtnd.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgudiaxj.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2glhdtqdd.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2axvklhpo.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2idmgzzfi.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2iftsnzdn.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hutoohmy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfocdpek.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gttqnwub.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsayobe.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpldrwk.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2odbsyyar.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqzpyfs.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2memdeqfs.html


<!-- 参考信息 -->