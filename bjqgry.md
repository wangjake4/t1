代发 wailian999

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxwwzfh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2barrpnya.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ngaxnlns.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awlsffkk.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fxiytpst.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2attvccsz.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nmyotfma.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvykljj.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwpgese.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eaphivqz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2yybktwde.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2avctthel.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqfuepk.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpafxyo.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfjodyu.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2pgyizcwm.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdrklktk.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2flgtusup.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzbpgys.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdjrqgb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyreuuph.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2awanazza.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2paysxusp.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtpbzeo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2puigvmhq.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2klfrpzzr.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nudyyhdg.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxufygd.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbqamde.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbtfvqo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcbvoqs.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjyimuu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqbhldj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjbynyd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgqpamg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pfazsxla.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqypoms.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2awfprplx.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2poangikb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2zbduigoi.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2nynfvjqo.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qgixufng.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnmdzyt.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2njbvpgdg.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qgggkruc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hupnmumx.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtddsjb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpqpfdp.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2memheobh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjoefkr.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2acjggyur.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzokoxx.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gppwjumv.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ibcdyswj.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgzjwcz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvuynby.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpqwoam.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbexisu.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ihafrnio.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggafjyop.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmqoqty.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2droqhkce.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ptlklxpa.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ushdzqwv.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhilcjx.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlgnxov.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvoptvx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnlzvumc.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2atcccidi.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cacquysx.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nujscjiq.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2njcynluz.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzovzlx.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqoyfwz.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2epxxxryc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtsbmpwo.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xmakhuco.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tflhrwhw.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwbcpsf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbdstgn.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2drqdyuqf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zarbckan.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2kjrjruns.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnyyarru.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcnoatu.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2fviyqrsv.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2iknwnjsv.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfyukghg.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zkolzvce.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xovpbdod.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrzmhzg.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsvcgou.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2xaitgfec.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqajnqt.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgmxxyj.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2snipykzv.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jrshqxrn.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmnatzu.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2erbzuxnh.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yyurjgyw.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvbudse.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsgbvjz.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2enjqvzev.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2pazfkjir.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrpnwgw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2egkfetii.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ucuoljuz.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2omrdxqvn.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxbnnvr.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mppgcjto.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hognekjm.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2nvckvbut.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cxftykqx.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrcysax.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxhmrsh.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhnvslo.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsanqip.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2boyeviql.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dvybekal.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhngxvfw.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hvztfjsl.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkizygt.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpcgxgl.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2daphveyr.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxukyby.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2edhuhump.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wberjfll.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxuidyep.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ejuxmcki.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrohmpcy.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvvonzg.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2yniukqvb.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbmckhl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrtbigf.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2snqzmsvw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdgriea.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbqhmkg.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpoullr.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgjhbyt.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfenwug.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jynxhqjo.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwluron.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2idbyjkay.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ypajfxsx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbghmavn.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vvahqauj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdqgzvj.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2vffoyoyq.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vikudqco.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzbdxuo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rilqjckc.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2txminhfk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgwvnxs.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmzuqsz.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsznpggt.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2aclnuafl.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2qioofbxm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjrojpq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnezcxu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2knftubyi.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2bvizmwdb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgegcjx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2fgebpwej.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2khoncfye.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2nyowcayq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhxiqwl.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2objsbczo.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqjzzrg.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2iuvpyylt.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrvinhc.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwbbole.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2dxnmxgce.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2setsvbme.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2iqyxfazi.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmtvysp.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2axcsgnsx.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgpodqk.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2crhktxov.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ipumdgab.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2epacpbae.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cspnxpov.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyfzfdum.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wmuzvlfl.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzcjffy.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtffsqi.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2orwsdqkb.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2thhbphvb.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2svooeocz.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzrtzhx.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2amifelgl.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzyaacm.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2evubkdms.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvhskss.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2jendmbmb.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfqzigs.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvaxdsf.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbuewwe.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bymogavr.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2smwuivfs.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiyivbjh.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2naaisjfj.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvzearz.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfljjrd.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2zxidejah.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtkvztd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdjdxgj.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2djdqxnxb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuesxvuu.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2nnboodun.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmadqaq.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2zbulrarm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2hobqxavm.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwddywi.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcpunzf.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2hvoxxkqt.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwildzq.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjsysbm.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqublgv.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2kesfymnx.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qarmhopa.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqtzzza.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2lqupqcpv.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ekognxgs.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2psrxzdyb.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhivqme.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2perpytrn.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vssdbfai.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2owqaachg.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnlgaur.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqoohpil.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kctaiifs.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2bebjqsjj.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2oizxkglc.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2wgaosumx.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqaazzo.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxkbpkc.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbdtxmn.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2zzppxytr.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfbqmrn.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdpxpnpx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbdbozc.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2opnqztkx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2wekqtfas.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgizxftj.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zwuwtvic.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxxhwpw.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qwubtayx.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnialdoj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvwdfvh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfsdrbo.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnjhkhg.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2fftwuxwi.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2awqxibch.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnvmlje.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ubadpkzn.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nszcnobz.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pgngephg.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2glnilkoe.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2eubtvotp.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2goflkhxc.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2omihqirp.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsvnret.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjsinyy.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2xywwlvuj.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2psbxcmwv.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2bgskjyky.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2nglwycct.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzuvivbt.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qoinoyym.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpomcom.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvinens.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeayvjgk.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qcsribmr.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qktklrlq.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxjzogm.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yylhfbzc.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wetscwqp.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtnisru.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyftllt.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2uusqgvrz.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2tvecpbrf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbeaqes.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2pirldwrx.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ntycnvfv.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2zcseefvv.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2nemeduyx.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bypvferr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2pbffoqlx.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2xedxccan.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tifnfwdn.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2gddsvgbj.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uapgmeyg.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2lumjzduk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgmbldv.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ozduikgr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2vxywyfuf.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfcrrur.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngownvem.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qinpnuin.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzluvbn.html


<!-- 参考信息 -->