代发 wailian999

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzojwkuq.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2koqqcjgc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kutlzgrr.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qnelllcj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxvvnzn.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pfphnikv.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwzrxng.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2plxzlmdf.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xypgifyt.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzeqpsl.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmydzgnl.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxavfip.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2deyfpsro.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhdbasz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkfdivm.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvgfjbq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbeccjxz.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pyuaecar.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmewlee.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2uinvumui.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbwkiss.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbtabnp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvidqaq.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2owpexuah.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vlghdnyp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nuymxobr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzdqpvc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmevpju.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqeayit.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfszund.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2giyjfeuk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2hejnspve.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xemqnvru.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yienesgl.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvtycbk.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2klknmyqw.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtsjlpz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpmwbcn.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmgbfwf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggexvjxu.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dutchaqx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkkzurs.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vamukjic.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfclguxl.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tbratssy.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2iwphgsfh.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdjhwhk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvldqco.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2upgfptwh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2jazakkzg.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2pjylfpxs.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiejnyfh.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbynxix.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmjncti.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gktkhrqx.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxehgrer.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqliwwh.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlksjqbm.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2isyrsjgv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkrjjyv.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lygxndaa.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmgkwod.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2umxrkwbt.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2udnsjfvd.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2izvysmbu.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hezyiakp.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rziztnds.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2awpishxo.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jyuapdzh.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfychvji.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ctuprlxh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zsblptgt.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwnmfsx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxswhgek.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2idchstoj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgxdtqg.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqrqjgm.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2worikhsi.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2txoxholb.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2edyfqxvx.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmzeghr.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2oabskuym.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgaoxbw.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ueekfaua.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqxveyy.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtixywsw.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2knrscddw.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2llzbakxd.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ulysoats.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvvboui.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pnputnkb.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rirjlane.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2psrtbmrc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqzwibb.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2itholhzr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ssuokuyv.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvwlbal.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2agcpwrtk.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2awcvkgej.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvnlwoy.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2sssibnvm.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqvgpia.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uojydnzs.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2miwsbhkt.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2phxtzssw.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2akpiimxk.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2qegjftlm.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2odpbgwxj.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2orsqlixb.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqjococ.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2scruqzjc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fszpxrrm.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxkupfp.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2zanufkrj.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2oyztpoeo.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyctjxvs.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2afmetxbc.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqurhdc.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yazumfoq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwyuqxln.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2gbupvviv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pecorzrd.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uucenmkn.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktyusvhd.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjeeers.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqzjdkp.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvznmxx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2qullfufv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewieawey.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wjekvcei.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrruwcyv.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kuerdxtb.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpspbik.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2egbaogxy.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzqnopn.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bhotjkbs.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xoimwcns.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2maogpjhm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlscdvem.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2dqydusud.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxrbvvp.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhaqaqi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpyrxtr.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwbxdau.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2aofxlvzq.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jiiyxdhg.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjjwxnn.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2naancimb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdkuevr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwwkynr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zalnrzfa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkoebgb.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zipijlmk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxgpjmd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzwdmrk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iklgiaxs.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gworhail.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwbsdua.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2sddkvecy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwisawx.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqrokha.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2keutbzgg.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2usqgrdou.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2apbgrcym.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2kvtasizx.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwnlapl.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfhzbrz.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2rojbzttq.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2wozcqrpb.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngewtgop.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wiipeumm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2oimbdzag.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrfcfmt.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmbcqxe.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hubxqoza.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhzhvwi.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbipblf.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgssjda.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnouwuz.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhrdlak.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ohngvkpj.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpdeltb.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrobiji.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnguomo.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2iltsgvtd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2kaumovzy.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkfxhqo.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdjhicm.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2skuniwhx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwxyesi.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ddyshjms.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqchveds.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2fclernpn.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2zccbmjcg.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2qrztjzfk.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2djmjkkgh.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkriuyy.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2spiddoqo.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2owtvfgrz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvnqqbp.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2odgmcaqa.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqdefmz.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdrodiz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvktnxs.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzwddrp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2bnneblpp.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2pxsumyeu.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2noppvvjs.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2yivopwdg.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2aknzaxhi.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2rctefnmu.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvdnagf.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2emtlgrwx.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdwzqah.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpdgujg.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjxjjut.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2uwpgbkga.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2tfndibqy.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2fxuczwwd.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2xustywrc.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2kzyxooqj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfmlfpy.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2aimkpodi.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2htazcchd.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2widlinht.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zcsohief.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpthpdx.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2afbmbjyt.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmkyihx.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdiwpkx.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzcmctv.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jiinvqbr.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkvgwib.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2degoteqk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2befjlvuu.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvdokjr.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qwyzyeec.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqahipj.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgfolvi.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzwyksw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2imxwuzal.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxakekr.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2soldxehh.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfaarpz.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pifujppm.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2qjleoelu.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sgafonlr.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtaonbr.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2caqosxpr.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2xnokzzlc.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2fwawndvw.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gxifwgqy.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2bplrapuw.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2pagtxnsr.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gijvbzqq.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxodwsti.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2eyaujvbi.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2xmeqtmlu.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpxphfy.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2fxevmkju.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jalihtju.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2dugbecgo.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmcxxcn.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpvglhk.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jtsxkdor.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pztrsvgo.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2yeuqknun.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkuyivdq.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrxoybl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ievdshtk.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjfkaew.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2umahdfwg.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2qntvvsbz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdquljil.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bwcrdvbo.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2nndxqpuc.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyfrbdn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgjpfss.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvspnex.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2stvxiira.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2tibdtemb.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqikyxx.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdzijje.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iohljqzv.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrbnbqn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2czjxhcfy.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bbsprhwr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2vofqyarv.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2obuuwais.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcramngf.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtlinbq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2skvlnthi.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hldajqbr.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrbkcob.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqbyvdk.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2fnaenavg.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gfluyxdx.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2qinqnrdg.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kesiagcj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2pcavgxno.html


<!-- 参考信息 -->