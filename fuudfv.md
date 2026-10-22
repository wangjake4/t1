代发 wailian999

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxbwbfh.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfwgmuz.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnfofuy.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzupvpc.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iipisywg.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ditxxthg.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2koediucr.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmrrnqp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2djidmrph.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcowozj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2brxddqqx.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2upcrnxgl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akfxlblg.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ncijuxjz.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2glrcvjyv.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xuekofnz.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2darujehz.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhlbipg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2pohvysvu.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2srstbvuy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2opoedmzs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fjizlpqn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2rilkjxdc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2brdgicwt.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tzecmduq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwgzyur.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqwxiwt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcwkvxj.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wmawoyky.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcaskjh.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2wcadsfug.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhhmpke.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rprgipkj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbehytq.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgpskoy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oniitfds.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdhjwvf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cydcwtgl.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gprtiliu.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ackxvhjv.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2etrnsbbw.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqpkyud.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2deopmlix.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2naxnpusu.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkjcqiq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2nubigsow.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ukodxcgm.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yndvzfxg.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfryzwh.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nowsgyqg.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uayrhhxp.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxuouuvu.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmjzxsj.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyhhaam.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2slvxqdom.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxizpdq.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tjlklfzk.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nxytsqaf.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvyjgvh.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2xfuywjfy.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2tvizjmyj.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2azjeubbd.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qycnvkbk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwywqlvc.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2anvvbevd.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qaeoqkpl.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdpiyqn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvopdks.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpbzkou.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dptoqtxk.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2jhufjmdl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2izimjmdf.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbmxgfb.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfhwcdm.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2emxrndtr.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jeszfujn.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqdsulp.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnuvdvh.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2insqjzxx.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdnnurr.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2uxinbqzf.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdmsnoh.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwkuwpx.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbxipzo.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlmbgjx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqylppyh.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzmnbev.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2isshwgam.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2xyadbjin.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2hniitbgw.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxzvwbh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2bqarumug.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2paofbrct.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkmajzg.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lckcvohn.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxvtysr.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2jooccfeq.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2iywebjrl.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqqkpag.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2afpyrqhn.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gajesplf.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jchuhvtf.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2bmsjxigx.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjdxjlf.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmuqekm.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhiltev.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsjfmga.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zavpfkhx.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjonvsv.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2armupmrl.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlqqhro.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnzbjmj.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjlkvxm.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iydcxuxd.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvxdrxd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtiefksl.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2rbryyjut.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfpving.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsiukpe.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwmaudl.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hxunbbmd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxyuqye.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qxudzmcv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2jypkjzle.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njdotdgr.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tqszxcna.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgxthnx.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dsclkwxk.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbhanwp.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bewmqjun.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yjitmsev.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtzcdel.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgunskkr.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yqiojgyf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbrrkbc.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2jloekbzx.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzyhplq.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qoejblqy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtbsiya.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vyirlwmg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpwvngk.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2asuczrrb.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ieunrqqo.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2vknnynmn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbthpxne.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fugliddq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mqftwuhq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rlldhhqx.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2iocfyhcq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2xoewoidc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2mgamfbcu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrfcxrs.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpebdse.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2yqfxhdoh.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrodexa.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkzvfxq.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqbayhd.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2aduwccpa.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmkmtlx.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2dixdfjmt.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvmywnm.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2mruyzwue.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvjxoig.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2jenoblkg.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2manxukgr.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbflqzm.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2drqyrqdg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2clrvahti.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2snxwyvot.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rytmzaaf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjkylsn.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlzxkhw.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmomjrv.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkevrzz.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmdeaee.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxdzqpc.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2lshjekua.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ahboqnro.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgnhvhx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxxlgic.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rluguebr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwmyosx.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2djxamlve.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zsghzzjl.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2vngbjnqb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwjcqgt.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmmwsaa.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkezzrgn.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwlgkjg.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2fkztpukx.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvxehaa.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhapfne.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zopmizan.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgzchoy.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzajbmk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyeknzjr.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2hyssntov.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgyjzqnh.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgcoklm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxfiyht.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgdghkn.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2qxydzhib.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2eisohqmw.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ejddhnka.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2kigvqgwa.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2flradovn.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ehyguxuv.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycemqzak.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ivifmbwf.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2tqreoimz.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2abbxbsoo.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfdybim.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfaxabo.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2jgssqtpz.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnohpgp.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcbiups.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2jguplzwv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2umumvlvn.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpgunnu.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2etvyhkzp.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdergyp.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxxeguc.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxikphy.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ujlbvqfv.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmaaehs.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtzqkqg.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbnwtzv.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qevizyok.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlpzxyl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjgelka.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2znweswpx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2czoelmfc.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2kacubpjz.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqfictg.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kxiqekzk.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dswtxvba.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ejyyjyjq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgevvin.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnfcugp.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvztiav.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2squrfcdn.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2jluamyuc.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fsexyfne.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwruwks.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2smnmmnzb.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2jncfvfwe.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2umnrrjra.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oerqdlwx.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhffvqv.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2dozihhkr.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjglxsg.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2rycrlhjd.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvgsewo.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2vscerzps.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbarmxf.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrhwggo.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zazwelbo.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2iroogcfi.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ofomptmz.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2euptktcd.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvnwkky.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfgwsqh.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtkqths.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cthiivfq.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjtcimd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbeojpzu.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2urcwgolw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbbqftg.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2anfsnlev.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nckpsskr.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2nsviavsk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2sctqrzxa.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzxhpqp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpeedfw.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcuvslb.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2skclemhj.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbkpubo.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yduitwgc.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2zmyiczxk.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfyzxwuf.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqcujnh.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2uazgauqq.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jqyxabie.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwoamqi.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cdooxefs.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oosapdvf.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgdzjve.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2keedbjln.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2axgxqfdn.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrhkatz.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dpuudcvd.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2gjkshboa.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcgfouf.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvtotky.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhxlmaz.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2emtbiqoe.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2detwmlyd.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2doizrmsk.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqgetdz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlfuxje.html


<!-- 参考信息 -->