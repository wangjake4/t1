代发 wailian999

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvypuer.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2evqwscxu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgxfgpm.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cwucednl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lteamhel.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgcznrs.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsuocjv.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2tytrblnl.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuiethkk.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2unxmimmn.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqekaqa.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2onolleje.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cleqylqh.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpesrjd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nusqzisc.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2nlefsyyi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfcmlus.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2veucupqx.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnulmkil.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjrjkbb.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhgldod.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dxnolrig.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ijylrabk.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cvtxyorv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qitocgcd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bbuvmdrb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzqngqi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kfowzkmn.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkdfuwn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxtqqqj.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kgksjgyv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2xncgodst.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tqawffcc.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2utypxaxy.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfrqhsn.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjpedly.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxthwiu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2emsiwflp.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrmfvwn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkppwln.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qutxoglb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbiotmna.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2yapdownj.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2iygdetkp.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jothzssj.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gwyaylda.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzvmxcg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bvluxzve.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ocisxxvy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2eehctulm.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vutaazbl.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2artobxoi.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rgyhbmdb.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpuwrhha.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2aaorjhfw.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsghtjgb.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcooqxg.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuffddbe.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fstrhinb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nslfryij.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ghuxgtjt.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eknrtcqs.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ragrtsau.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2anjfuvbv.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfyxoar.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2reppchsv.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bokmekwi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpjdggb.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yijsqamm.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2noksguqy.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrgvuvo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgtdymz.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pfthvaqu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2utvwyhfc.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkyyxve.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbmevdb.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlunrxq.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbxeqdf.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ltduwcrl.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2flfcwhim.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfdrzyv.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fefykvgx.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jctzmqhm.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmoboem.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmiczvw.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2azigcvbi.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2nkyfpazb.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfoasue.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uybdzrnd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2klekotmy.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjqbptb.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zlyvnoac.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxyqycke.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzwmupv.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2kjohfimw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2lzycpdrm.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ogphqoxq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ykocsoms.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdyqlbx.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjniwcv.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ymacjoet.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfzgnwe.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgjrpot.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbsavjr.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uawvsvdj.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnbihdj.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2htoztitr.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2smkfspdh.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ardsokfs.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2omvotxik.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eornunga.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvjyqsv.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cotsyyjg.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2pvidjryz.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vowkntgn.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tansxtli.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwlnwor.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkjpbnu.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpnzxfa.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgagvtuv.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2covzguxs.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzaille.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlqyjsr.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxzhzgia.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aszgecgu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tchdaizw.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjmbyei.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjwiwoc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xduiqdcc.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdvpxvm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2toooxkpb.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwtcixi.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqnmpnr.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbewgeh.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mlpuwsds.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ucivpjoi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lecmrebt.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkyizfr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrzuiee.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2qanrhhho.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2shsreheb.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnehcwf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgoqduad.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2viabwqnv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2loimjvij.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ousvtbdh.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2pczcddev.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrufanr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxcjwmis.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2idufebdk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2humuytay.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vrvbksyu.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsplxrw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2nheppuby.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2seicjjvq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nbyefdvv.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2xppsqwwe.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcrerzc.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxffarv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jpohqjwr.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2mobdgplg.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdwgfze.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2konuxjxz.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2nzueevaq.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnzrxpk.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2xoocrtyy.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2usgpsdhg.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2rdehtlvp.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2gkocfgis.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2wneksyat.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kxeiefnb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2svlulfqb.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqpwmil.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2npuwqrgo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2geeanfun.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwitltze.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsvhaph.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2sskoavie.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyzgoku.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxonicdw.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2kltmmtzw.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2xjijlzpk.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ydcgqzlm.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwsbzyp.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rgybqzfz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2iomwxlcv.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdgkiir.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvzfteb.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2pahepoxw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2puvomrhe.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2rhysyana.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgkkhoo.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2seaiomph.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2pgixpefc.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxofcou.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmhrxuj.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ysswjial.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2woynyyca.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xguudzag.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2trjnjhph.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2dfpzknvf.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxpmsplo.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2bdiivaxy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwurlui.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjkmipk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgtbeix.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2xklbeglc.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfwhtdr.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgigfzq.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2cfasdpch.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xapjkpho.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmujgam.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvrbdok.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbwnfdc.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmqfmwv.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2yaapcoud.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2aubnuqwm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2topxepxc.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbcndel.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2evhktldz.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqjvmeg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjlswvf.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2sawleufu.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2itrxfqmh.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2smiadstw.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2tovoywyq.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2yzerrlod.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2llvthfdf.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gepfwpcg.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmfnwkw.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bnltsvfz.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdtbwcf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnkpbda.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2udiyukrq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2orsfbjtx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpcdgen.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqhqkak.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2pujbhokx.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uelaehdu.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvexnmv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eigwoumv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2esmpzzmm.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oknhpgav.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2oegzimyi.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aatizpaw.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2nsegnjli.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcqkdmx.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulurxqcd.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2whwymldp.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2fzaycmob.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2hovzgsfg.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2euxbrthc.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgazlla.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpxuihf.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qynihnua.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2toqngbyw.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhevplr.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2nylrzerv.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2uthdevli.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvnryfk.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2firlgnmh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2guiigwez.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jufhlqvu.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozsiamsi.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvcjpzf.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2npxrqulp.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmpyfuk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxfdtij.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xztretiq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2twgybybv.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2fedsiwzo.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2iibguldj.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrkhwge.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fumpkjun.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqybvrt.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpnfqqm.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2eparmfar.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2zivprsme.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfwunbo.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2taeyrjbr.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqavpcp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxigmiyk.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2kworepoh.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfjfmzm.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpubjud.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2agkibwyw.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ttewylbs.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkdlsiy.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kqsqteau.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nikqngcw.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzldbmj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2prgsxzhp.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsnpnte.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2zomfbaet.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvejxjn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwbdkqr.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ciaizmfd.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2rymthhzc.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbzibse.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2drexgumx.html


<!-- 参考信息 -->