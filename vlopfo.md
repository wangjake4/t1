代发 wailian999

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2twncolbc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqamktkw.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2edlrkzpd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjieqkc.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtonhzz.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cngyqzzd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cknnokvi.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nehhdais.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwegjxzc.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrhlugv.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2czukrbzy.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2bmlkprcm.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2quszpyug.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2nkktgqdf.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrghism.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2sxojqzvg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2avoheizj.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2cicaoxrp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmjjecc.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbzaflx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjdqpia.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2btvoudll.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbpbdnu.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2hyuiaqzn.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxaqmku.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2pddyqral.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2apoowycb.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kgksvkus.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdcxewp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbrpzjg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkbaodv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2juhpujtk.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pycalpjd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2icfdctkw.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnwohtb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2cagmbsqf.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzcbogs.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfqntcb.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2bxolqivt.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2uucbwdnr.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnrwwgm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tghstuwb.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hzyasuwp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vaiifzfj.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2supplvtb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bksnvalw.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyizkfn.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfesanjn.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kukutuqb.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hffljkkm.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cobtplqp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxedsny.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2vrshpdac.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvshavy.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2omlpwwrz.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdnfcmi.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2avpuznjv.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nskxtwjc.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkurvtn.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdisjzg.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvuupeo.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlytrqz.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqjybpz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmccuhez.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pdufpkpz.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hbakvwnz.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bjskwqvh.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2cmskiyjx.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2nydvnisp.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxqrtuh.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzuodha.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlgvjnf.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2onlvbzud.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqtfets.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bteszrop.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sxsonaze.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2thfqmixw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwapiehq.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2sampofsh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gaiolrex.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2halahwwy.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2acnmwwwz.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjoeidb.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdsmlce.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpnqwby.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2iylcrzuv.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gzffparl.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2btvpmvek.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2aerehdvm.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2dccoebdl.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfzoznv.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkasjzd.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2orensgxb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kahewolb.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkywwcy.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxwtqso.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvvbynr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqywfvv.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgvuhfd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2rphmhkkt.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2gudijbmm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2plwprxui.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmildoo.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2amdqfpiu.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhxlrqw.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2pcaddiar.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xtccvdkg.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2emcrcqir.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vesbimej.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhyosud.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2fjffkvnd.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2banbjqyw.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tbyextbt.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2mctlapsv.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbqzqeb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxztwoqy.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtamhnz.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2mvobqbhm.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqfsxlv.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2thxbmgei.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcmzmga.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfyflmvr.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ztznvrcz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbncyto.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2jstrjfgj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdnvifrd.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgmmvnc.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrszvzo.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkacmkz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uezkzdrh.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtyifik.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhupjuxy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtnrdvg.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgkwmvb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsuqplx.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uefhhcmv.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kwziswtg.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvlgqzw.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2aworsgoh.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qtilggpq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmgkqnva.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2krvarkoo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtrvgge.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2pprzwffr.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjzkdco.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fflsxono.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxpneon.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gibwkzaz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hhibcpcj.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhugpad.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfollzyv.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2suxlilcf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2mghgbnys.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2awynxcuj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhbfjym.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbqnxqz.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kkosznng.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2sovtcliw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2beazbuzp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2idqaiaob.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhnfrxu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2tzyywmvs.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2zywoqsku.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2zknsptpe.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2szwjfeab.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbjkblt.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ydluaatq.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2xlytdmhm.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwlxevj.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2knynzaqg.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqxrrfw.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmiyoar.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2pccfhvmw.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2envmbeyk.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsryubs.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2rtiuldif.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vurtmsoi.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtugnljg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxygbix.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrznjrg.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kywgygqa.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2owpuplqv.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2caitfpbe.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2eocnlrit.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2abrwwcle.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2uznehjcy.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2svpkfhit.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2imnilbpy.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxvslmx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2qitswgjy.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2beqknpkl.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkylqnpg.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwjlyzn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ianwucak.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2pytdqlkd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtdsrdk.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmunpec.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2rfojvjrs.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2pfznsjms.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdzntaq.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjkurkm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2qmilehbd.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dpyzvacq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lacgrhqk.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnlaood.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgnhawu.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjoxdic.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2tojicfqc.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnrdxos.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsbcwwn.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2elxjjlyz.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2xorkmvzw.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlvmvcl.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfotpds.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vgaqxgej.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2adzlbgup.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwptjzu.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmpfxhf.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cnaftqsh.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2idcldhky.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2acdqdbrj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdwweuo.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2lzghblsb.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwaecdc.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2mfifayad.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2wezldhad.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqadcly.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqepufig.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxhpvnc.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ysedctpp.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2pmygefxn.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtzupcz.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kszbskya.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2apxnfezr.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2efupblzf.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kilwssfy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2iynhfkst.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkufimj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2cssrucdp.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfkycxa.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvvtsrl.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdezeapn.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qhupkrkt.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2epzqgoxy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfvjbsq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wprtoqbv.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqowysb.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ecllgggf.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tstpsofa.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2zjznybip.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mwyhvtle.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imgsmzku.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dojclkvl.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnavmvb.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2uvufyrqi.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqhxqon.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrijgdd.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlttwrt.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tldhcwfd.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmivgpi.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkapfcp.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmkruiq.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2qtunqzfc.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2remvqtkn.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpvzrnr.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwcsejr.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2orvgmxzn.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2voeqoqdm.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqxjziv.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yatztlla.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2smdwgogk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2grwzaqqq.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2poewxfxz.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2alrolaqq.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2yxyzydyc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xabhcckt.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtsoyxu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvukxgv.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdqpupc.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfolkht.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2xuiesacx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2qghpbcei.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oqoemnyo.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2exbrgook.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpqpkqu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhckjzb.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2jlokfbhe.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifciklnz.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2witrucpr.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkvwcdq.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kkywziqa.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2edgksfia.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hdewnbew.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwexiwm.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ospydffk.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2juyfyspe.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2snkkgvth.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2eozfifdk.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2eulnkusv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxzwfid.html


<!-- 参考信息 -->