代发 wailian999

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdikbcz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vltywbcv.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2piwkuqnw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmudzgb.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qlslotax.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjubqwo.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ezffjsfj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhsumri.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwoxdxo.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgkxlto.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bazkhvpr.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhopxkq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvktfch.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxsqluz.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrynbbo.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ryreprhk.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlygqlq.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgeqwde.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2kytkotjf.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvdtzqr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmanfzfb.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2uixhwevu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqsjksyq.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2mvajykbc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chzwydhm.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsbjyde.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2thertvbg.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vryqcgtr.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pekjnccn.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jprzsmps.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2vessbdgd.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zebnvzti.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtbzncz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zaydxqjw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdxiokd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2amkrzxhu.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bescwkth.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhlxohj.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdzokbj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2sizrqxln.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tomfbtxa.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mnuiwnnr.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfhswan.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dfpccnvi.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mdazaqhi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbckgrb.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjiitet.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2szaaxglb.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2evqdmfqp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrzqzep.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjyjxyk.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2epibquky.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2stfvmecq.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbktnzy.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcmnvux.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2iktyedhc.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkjngnd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtvrwwn.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ievffvtd.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqxwdmd.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2kumjwjzl.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjeqpord.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2guarnpyq.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qylmnkxw.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwvrdyu.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvoxjlc.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqsgdfp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yoowangh.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2harfatcn.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkdbkyz.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dytxewmo.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmxsuwe.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2loksglli.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qytumyjc.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2oexdktkf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukejregt.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpgfsfr.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dugcoxrb.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2knjepfwi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wybxhklm.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2esdfljmf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2phtpkrdg.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlfluyu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2trtohbqa.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2yyixymzl.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdnihqct.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2wygsasyz.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2lblkdjvu.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uehoilvt.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcfezqa.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqiigbo.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2venjtstp.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2duumarzl.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2abrjfqrf.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmhcvvx.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2aurwsozf.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sscdlvzw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxjqacy.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pelxfcbf.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrxcsjf.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqtwgks.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2odrikdxp.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbkfdha.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2aumkjpul.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2slvyrrxr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2owxqvacc.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2opacefae.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2uthohcnh.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2erhgubzi.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvnizoy.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2othnowxu.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvkdror.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcjlptw.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vusnrlvk.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2aapyqsyp.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvmhjha.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwmzmrb.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2pglgayqb.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xkelcnix.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bflyqwfa.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhmukor.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2rhshxxfc.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pixvfnzt.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxweexei.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnfmksk.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvoycwe.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bogupdoy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkuzjvw.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpgbdpu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxowfpa.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwxrxks.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2uarkkrvc.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2swkddrmz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzaehch.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfpxazn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2leozprdg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tiknkltr.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2brxlpvsy.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uedwgspa.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxkazac.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vumghptb.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ynsqaejo.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjtndxq.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rdemqngs.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2svfnuqgy.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nigskxry.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xoebcnmq.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2attchrif.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmipjkds.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kylmbyhq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2harkoczz.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnbhcxl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxijfwj.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cptvsdho.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2witxksqx.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2llzgtuem.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppspjluu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyskdtt.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wesmcjuk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfabmuu.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtgpzor.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvznmct.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2wlclzwcu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eodllxzf.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2wyndyygt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywobkdmo.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ykeqfqot.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2frooaqyn.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ldiybnnx.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpphzel.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2blldphaw.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxskvtf.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxzzjwy.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqoprfe.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwvrmfx.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbwhuce.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnkxobu.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlrjxem.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2beyvvbna.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpslmyf.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ptknhwbd.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwwupkq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhocdrr.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bystkudx.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fcoapddy.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2odcxocwz.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbbzmgv.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2iimhpdtg.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2vjofdzij.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2iewrnslp.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ojyjyfav.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2nxscaodv.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmrlvbn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2kugkmdcu.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2khrkwume.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjkqsud.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2xyounafh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfyxqtof.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrwrhcy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2krjcgrep.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhmigyj.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2otligrov.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2xborzmrz.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2doqtjtve.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tdteaygk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2kexgulcg.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lghkpnaj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcixkmds.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2stenrugx.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwifdmuw.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2mjalktnj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2lljrhrjt.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzkbiik.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2brmnfvse.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2swekhnwv.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2qldjpjqx.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnzdsly.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2zajqouwe.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2yestxnqf.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2owbgkzms.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2vbafqnsd.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2nmshpypr.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgngdqo.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2doohfnat.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjvaosi.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqevhja.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2gabsrcbi.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgfmozm.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ukapsskf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2adezotya.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrjboue.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbwrpqw.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2obilcxdq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpnqbba.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlpdwzo.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdhicar.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdmwxye.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2khodepwh.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqsbhoy.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyeiximx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsdgoiu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2krhmmrdf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2nysplsfj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrdkjip.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdgsehc.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhcvllg.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jkssdpqg.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kplzidvc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrvvlye.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmndsucd.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pzacanwr.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ebuxzepk.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjggasn.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2hdevpybh.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qlimuaka.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2showdvlp.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwibdma.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2adopgfht.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrtlzgm.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sntumxmv.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzeroks.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxyuiuv.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvkanps.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qktelygi.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2sodnmvzo.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2grepfepg.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrtqqrb.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2uknvmhgl.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwkvbuh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgzbmdy.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cwybyvlf.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aytmaqjn.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2iribyjmf.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbfooou.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2mukqxzdk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtgjecz.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmsmtiq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kesomcch.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2icearqjv.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdslrgyg.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2pccdycdf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnjjkeo.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqofooe.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2auuihape.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2cxapckop.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnijjuxn.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqxmqrm.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjccqjx.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2vapjrvgx.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnyrkzca.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfrsacf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bibwgcym.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjigywh.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2kotchdsm.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2flzgtxqz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2tykxybmd.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cesarjag.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvhejcl.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xritndxp.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlxfrjc.html


<!-- 参考信息 -->