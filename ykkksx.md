代发 wailian999

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwudixsd.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtdvpck.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcltees.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2htkqewku.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmuvijt.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zjlqporc.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcqghmz.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2pjtfejnu.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnztbjao.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmczsfe.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2kynzfpmp.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gxekkkhq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uelrdcfc.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yyokibfs.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvpjtfa.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzyaiis.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpomjkq.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvuxxqp.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzayqzbt.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcttlvx.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2runabnpe.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kfneysmd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2buzqcehi.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cmdqcivm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvrnzoo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgtmgrj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqcojtj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2etxgyqle.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2spgthxzp.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uisimeko.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cpojzbmn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2nlpyukpm.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2oeuatjsd.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkwbtfh.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhfflks.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqbsspv.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lqthwtgq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhvrhey.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2szousxvf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2awpdskzj.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2glegokqz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2krgiugbl.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxcvdpi.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2swzrmrne.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xbeiraml.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtinfda.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2agxjguzc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tozcdpfp.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2oxncxtcn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2tulvnshd.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzxnnov.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2teholozw.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2cnuadpnj.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rucsxdna.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2msuovnhi.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhmuboq.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2oohpcqqz.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2krjghqob.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2atskpdvt.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2upjdajic.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wiucjlbx.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjrwsrw.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ltszbpss.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2tydlyusj.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcaabta.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrerfdn.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2viwqoisk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqghicue.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dldidoam.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzarlvin.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2waedblun.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjwgrag.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfvgmzp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2umxrvest.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrnxwrv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwetlak.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2tmijtxjh.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvfjwhe.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2voxtlhku.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdsjgytf.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ineyeagw.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2obitlwuv.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qazxropn.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcurbnvu.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2alxhqxyy.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmplkir.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmehbvb.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2opgkwgfa.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2giyhjuky.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjayhhu.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ftldzhqo.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ebnnkjkn.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2eravkcle.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvxjdya.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlzwpfk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2hshuaemn.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2jgftplia.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xsljdqpr.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2djgtfffy.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmzptao.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2akzzmbps.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2klulbzee.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xazrlfua.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2mvuyxdxg.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2numhnnnk.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbgddcq.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhcwnzv.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzqgsug.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pvontjro.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hayhwxbu.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mygbrste.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hedqhqoo.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nznmvagh.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpjgzeb.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2geyvjyqt.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aradkonk.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tryfrtuu.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjduogk.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2prbyynzu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovlugwso.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbfxopi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2asuyjecv.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2swzczajv.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwullmaw.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fmpzdlvg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2moeqedci.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvnafkm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwuklfq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpfcfbb.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dioemtqw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cnyqyrbh.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rzderntg.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzulafo.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzqsppt.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkpbmcw.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xgsckhkr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvrhxfaf.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mcchkopx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iniddxjs.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsakmee.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnveviqu.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2iqybcovq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsbsxqn.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2sftmpdck.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2pevkewdk.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xycdljzm.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcavzgci.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2rsclvvfk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2sznctmku.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzwzhpd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cudjdqcx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tccrkepo.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ztnnsiar.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkklaet.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2wusuqzxq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2satbhsgx.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2wedanayr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrdpfdr.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2esfbasdd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2zmftykga.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdaufnv.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvjxatu.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcncxdc.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2jszfdwkh.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2bugrstzi.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpzhqzt.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ninkhivo.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdffnjc.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhzpkms.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrgsjoz.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zpljezzh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqsycjh.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2abzyhjak.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsujgmon.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ovltpzui.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnycrvim.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmjzjjl.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyyvtszi.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrwkrlm.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmiatahq.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnuinjw.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhcvatp.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpgdqyp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkpsauu.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmgihmt.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyekksum.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbuocgw.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jverrjxo.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbzbhvr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqoxkou.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2umtqbfej.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2igwawbxn.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2srdyqfvf.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnfnwab.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjgjibo.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2wdujmpaa.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qaszpcgn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpjeuth.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gzejsxrw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdysgwmy.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2sapdhnbh.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2cohupbzx.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwiiwsh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2mofzcmoh.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdtuldy.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmsecnz.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2dwanelgp.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcnebwi.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkeiehg.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2hzepcnjq.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpmkksy.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbvhfpw.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2hdoyqhtp.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2cpltcmsg.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cyigsrey.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2uyigzlzf.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2fspnugua.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2aksoqcqq.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2dbabqqqe.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhsqcvz.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrrvqsg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhsgheh.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2phuhwyee.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvlwqxrr.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlhfwud.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2llswkthz.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2arsdhdsm.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2psslsguf.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqqlsrk.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2mdaopojv.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xfscczwy.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfayqfpr.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmarckt.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2bxyzyvlo.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ukpmytad.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2snjudqqa.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2moidtaic.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtpxmwv.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aehrygas.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2amiikhan.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdjhcph.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yumaguum.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fxgylevs.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhlvuyk.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzfkbvf.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhrrfdx.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xxukbuzs.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xarujulf.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2upjhimpm.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgnzyox.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvpkcup.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyfprry.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jbohmsrl.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2esvlzkgz.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2flqgzymv.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmoansow.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2dqiddnav.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2vytjyqfc.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgejhhw.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2vrshnxuh.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pboptitm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfxtdrk.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qhistrmd.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnkaasv.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nibzwoam.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kjombcxk.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2wvitmqjk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfevfbmg.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nraqtntq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdzgwpk.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkivcap.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvflqlzd.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ansdmmms.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfbymuu.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xpyrysle.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2fklcbpre.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2sswhffjh.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2liiklypd.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fztespjv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqshurx.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2fezqeaca.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxltucyr.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2lakbwmqp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhotrfvl.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2zhgmgzww.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2fukqegdk.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2llnczqaf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrmytzp.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcllidm.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2boxcwhlc.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vayezebp.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2jngsiubv.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2eanqyiqa.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnckuyyv.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rksosewz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ailzuuem.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjaohmo.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljauzxwn.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hfaqjntl.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzhejey.html


<!-- 参考信息 -->