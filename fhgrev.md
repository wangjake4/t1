代发 wailian999

[S45] C++：lambda
来源：http://dali.mhx1999.top/Article/details/gthldlmius.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sufxvd.cn/Article/details/gtlizmryiu.html

[S46] C++：函数模板
来源：http://dali.yj20258.top/Article/details/gtyuegjqyy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinqigufen.top/Article/details/gtvxgsnkug.html

[S47] C++：结构化绑定遍历
来源：http://dali.vqdsnc.cn/Article/details/gtakiflanh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gtupcdyzrt.html

[S48] C++：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gthhbhlnun.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jlsjyb.cn/Article/details/gthqafrhwa.html

while (std::getline(in, line)) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqvqgudpv.html

[S49] C++：写文件
来源：http://dali.andypj.xyz/Article/details/gtlzgbbbbv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.birdmap.top/Article/details/gtajrejkrl.html

[S50] C++：格式化数字
来源：http://dali.aizwys.cn/Article/details/gtnqlzegwh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sxryk.cn/Article/details/gtetbfnhoq.html

[S51] C++：显式类型转换
来源：http://dali.mhx1999.top/Article/details/gtuglumeya.html

static_cast<double>(a) / b
来源：http://dali.zhoulong.xyz/Article/details/gthybnbeux.html

[S52] C++：const 与 noexcept
来源：http://dali.shanyushiyangtech.top/Article/details/gttrutyhft.html

int size() const noexcept { return n_; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwlluylkr.html

[S53] C++：移动语义
来源：http://dali.cashguo.top/Article/details/gteyudgyhu.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gtsoojfpkz.html

[S54] C++：异常处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtswvlxrmi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlokcztxp.html

[S55] C++：结构化绑定
来源：http://dali.yonumen.top/Article/details/gtoersgjut.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhengqikj.top/Article/details/gtkfhicgls.html

[S56] C++：optional
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiswvqbdj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tianlin.xyz/Article/details/gtalpvttmo.html

[S57] C++：编译期常量
来源：http://dali.zhixingplan.top/Article/details/gtgmbbxsor.html

constexpr int N = 10;
来源：http://dali.pengpengdd.cyou/Article/details/gtughwomgo.html

[S58] C++：命名空间
来源：http://dali.jinqigufen.top/Article/details/gtgxhhysxw.html

namespace ns { int f() { return 1; } }
来源：http://dali.cqqwz.cn/Article/details/gtarjnghsc.html

[S59] C++：静态断言
来源：http://dali.tianlin.xyz/Article/details/gtvpolftoz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhiwuduotai.top/Article/details/gtikzwhbgv.html

[S60] C++：遍历并删除元素
来源：http://dali.0kj1m.cn/Article/details/gtpbazzubr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.havefunace.top/Article/details/gtewdthkzh.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtquzzqzfs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.meibo888.top/Article/details/gtculptziu.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtedslwjdq.html

[T01] Kotlin：Hello World
来源：http://dali.yj20258.top/Article/details/gtaytkjqux.html

println("Hello")
来源：http://dali.svipenyu.cn/Article/details/gtbtiuthke.html

[T02] Kotlin：变量
来源：http://dali.tanke756.top/Article/details/gtbhzfsxji.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinqigfzy.top/Article/details/gtzjfscbsg.html

[T03] Kotlin：字符串模板
来源：http://dali.yj20258.top/Article/details/gtsoemfebe.html

"值: $b"
来源：http://dali.tianlin.xyz/Article/details/gttzotsarj.html

[T04] Kotlin：空安全
来源：http://dali.guowangkeji.top/Article/details/gtlwasvqwm.html

val n: String? = null;  n?.length
来源：http://dali.zhixingplan.top/Article/details/gtgdrtssyp.html

[T05] Kotlin：when 表达式
来源：http://dali.jianghu66.top/Article/details/gtnnwozwbc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zycfv.cn/Article/details/gtcmcmtsfu.html

[T06] Kotlin：集合映射
来源：http://dali.zhiwuduotai.top/Article/details/gtizeeoopc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xuanzx.com/Article/details/gtdadgmuzw.html

[T07] Kotlin：集合过滤
来源：http://dali.kuanghao11.cn/Article/details/gtnmekjvge.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.daria6918.cn/Article/details/gtxvnkeupf.html

[T08] Kotlin：数据类
来源：http://dali.snrcjt.cn/Article/details/gtzzuavxld.html

data class User(val name: String, val age: Int)
来源：http://dali.yonumen.top/Article/details/gtyitgiyuc.html

[T09] Kotlin：扩展函数
来源：http://dali.guannengcc.top/Article/details/gtlilzmzcq.html

fun String.exclaim() = this + "!"
来源：http://dali.hammf.cn/Article/details/gtnksbjqcw.html

[T10] Kotlin：默认参数
来源：http://dali.pengpengdd.cyou/Article/details/gtloengdwi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jlsjyb.cn/Article/details/gtxuwfeajs.html

[T11] Kotlin：协程
来源：http://dali.birdmap.top/Article/details/gtsemfsrjg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.tianlin.xyz/Article/details/gterbmdlql.html

[T12] Kotlin：解构声明
来源：http://dali.0kj1m.cn/Article/details/gtxuuttnti.html

val (a, b) = Pair(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtbzqcdfgl.html

[T13] Kotlin：只读 Map
来源：http://dali.chenlongwang.top/Article/details/gtwuuxhofr.html

val m = mapOf("a" to 1)
来源：http://dali.vqdsnc.cn/Article/details/gtgzvpangi.html

[T14] Kotlin：循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtzpdvddlw.html

for (i in 1..10) println(i)
来源：http://dali.chenjidiqi.icu/Article/details/gtzcfrjshj.html

[T15] Kotlin：接口
来源：http://dali.chenlongwang.top/Article/details/gtynwfiebb.html

interface Shape { fun area(): Double }
来源：http://dali.nanxinkj.top/Article/details/gtyossjnrl.html

[T16] Swift：Hello World
来源：http://dali.meibo888.top/Article/details/gttxipgagr.html

print("Hello")
来源：http://dali.yangfankeji.com/Article/details/gtmvmebhgl.html

[T17] Swift：变量与常量
来源：http://dali.chenjidiqi.icu/Article/details/gtbvtmzqhx.html

var a = 1;  let b = 2
来源：http://dali.zhengqikj.top/Article/details/gtzeksnvdm.html

[T18] Swift：字符串插值
来源：http://dali.c1oappe.top/Article/details/gtrofznrtb.html

"值: \(b)"
来源：http://dali.yonumen.top/Article/details/gttluhhxrx.html

[T19] Swift：可选绑定
来源：http://dali.havefunace.top/Article/details/gtianvihrr.html

if let n = opt { print(n) }
来源：http://dali.shzxlz.cn/Article/details/gtcmzxmzts.html

[T20] Swift：数组操作
来源：http://dali.nanxinkj.top/Article/details/gtvzwlndld.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.kuanghao11.cn/Article/details/gtmavylfwq.html

[T21] Swift：遍历
来源：http://dali.zhixingplan.top/Article/details/gtymzmoewk.html

for x in a { print(x) }
来源：http://dali.xinyue.icu/Article/details/gthsrhscyp.html

[T22] Swift：字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxjyjhhlv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.0kj1m.cn/Article/details/gtkrwdmcbc.html

[T23] Swift：函数
来源：http://dali.gzhubu.top/Article/details/gtxpraudiq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.iojbl.cn/Article/details/gtgcjcbmiq.html

[T24] Swift：闭包
来源：http://dali.aibaodan.cn/Article/details/gteursetbb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xylfe.cn/Article/details/gtfzekbqvo.html

[T25] Swift：结构体
来源：http://dali.sweek.top/Article/details/gtxxwyqnek.html

struct P { var x: Int }
来源：http://dali.pycfn.com/Article/details/gtydbkpdbw.html

[T26] Swift：类与重写
来源：http://dali.hnxiangtu.top/Article/details/gtoahkihdk.html

class A: Base { override func f() {} }
来源：http://dali.andypj.xyz/Article/details/gtlkljyoqk.html

[T27] Swift：错误处理
来源：http://dali.andypj.xyz/Article/details/gtxdkusvwh.html

do { try f() } catch { print(error) }
来源：http://dali.wangdashe.top/Article/details/gtxitibpae.html

[T28] Swift：枚举
来源：http://dali.jqgufenzy.top/Article/details/gttuatelxr.html

enum Color { case red, green }
来源：http://dali.tanke756.top/Article/details/gtlbdviqak.html

[T29] Swift：guard 提前返回
来源：http://dali.xziqi.cn/Article/details/gtaihlffxj.html

guard let x = opt else { return }
来源：http://dali.yueranfly.top/Article/details/gtqejcgjdz.html

[T30] Swift：协议
来源：http://dali.hongshengwenyu.top/Article/details/gtacxpbzmr.html

protocol Shape { func area() -> Double }
来源：http://dali.daxiang520.top/Article/details/gtyuahhott.html

[T31] Lua：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhtcgwuh.html

print("Hello")
来源：http://dali.ivvv.top/Article/details/gtxjwahnqk.html

[T32] Lua：局部变量
来源：http://dali.daxiang520.top/Article/details/gtrnrsyyzt.html

local a = 1
来源：http://dali.vqdsnc.cn/Article/details/gtknpsqxop.html

[T33] Lua：表（数组）
来源：http://dali.jinqigfzy.top/Article/details/gtbypjtmdp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sweek.top/Article/details/gtpmrydkeu.html

[T34] Lua：遍历表
来源：http://dali.zhongyouzk.top/Article/details/gttugwzada.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.snrcjt.cn/Article/details/gtndeqpxnx.html

[T35] Lua：字典表
来源：http://dali.jqgufenzy.top/Article/details/gtnptbkwkk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zdqjudy.top/Article/details/gtrhilzokz.html

[T36] Lua：函数
来源：http://dali.gogol.net.cn/Article/details/gtbcvpjzay.html

function add(a, b) return a + b end
来源：http://dali.iojbl.cn/Article/details/gtzifmawlv.html

[T37] Lua：字符串拼接
来源：http://dali.daria6918.cn/Article/details/gtiammpimd.html

"a" .. "b"
来源：http://dali.yj20258888.top/Article/details/gtuffbquro.html

[T38] Lua：条件
来源：http://dali.pengpengdd.cyou/Article/details/gthvjfluac.html

if x > 0 then print("正") end
来源：http://dali.hnxiangtu.top/Article/details/gthlehgdgl.html

[T39] Lua：模式匹配
来源：http://dali.fengsongda.top/Article/details/gtltyyvcnv.html

string.find(s, "%d+")
来源：http://dali.nanxinkj.top/Article/details/gtmnqvaroa.html

[T40] Lua：元表
来源：http://dali.shuidangran.top/Article/details/gtimqdftfj.html

setmetatable({}, { __index = base })
来源：http://dali.shangyingyoupin.top/Article/details/gtxekelxas.html

[T41] Perl：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtgeymouny.html

print "Hello\n";
来源：http://dali.haohaochexian.top/Article/details/gtjcdtkweg.html

[T42] Perl：变量类型
来源：http://dali.cdnleiting.top/Article/details/gtdxyyytmv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yongpay.top/Article/details/gtmxrwypkt.html

[T43] Perl：字符串插值
来源：http://dali.chenlongwang.top/Article/details/gtmbrjfkvx.html

"值: $a"
来源：http://dali.xinyue.icu/Article/details/gtesttcvdh.html

[T44] Perl：条件
来源：http://dali.nanxuanxn.top/Article/details/gtabgjdrwb.html

if ($a > 0) { print "正"; }
来源：http://dali.havefunace.top/Article/details/gtyrghtlja.html

[T45] Perl：数组遍历
来源：http://dali.jinqigufen.top/Article/details/gthrfuayxo.html

for my $x (@arr) { print $x; }
来源：http://dali.chenjidiqi.icu/Article/details/gtpbsxzirq.html

[T46] Perl：哈希操作
来源：http://dali.mhx1999.top/Article/details/gtfsmeqanx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.0kj1m.cn/Article/details/gtpektlkky.html

[T47] Perl：正则捕获
来源：http://dali.jqgfzy.top/Article/details/gtlxafszua.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.chenjidiqi.icu/Article/details/gtisatikwz.html

[T48] Perl：正则替换
来源：http://dali.yj20258.top/Article/details/gtthvlpuci.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gtgbiorzdn.html

[T49] Perl：函数
来源：http://dali.chenjidiqi.icu/Article/details/gtdrpyvbap.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gtplaxoqbo.html

[T50] Perl：逐行读文件
来源：http://dali.birdmap.top/Article/details/gtjcqzlqzc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sweek.top/Article/details/gtwzmnyahy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yvedp.cn/Article/details/gtetfhyldv.html

[T51] Scala：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtrdsvtwst.html

println("Hello")
来源：http://dali.yuanzhike.top/Article/details/gtkvcertjz.html

[T52] Scala：变量
来源：http://dali.ybcxt.top/Article/details/gtodvfjxpn.html

val a = 1;  var b = 2
来源：http://dali.gzhubu.top/Article/details/gtfzgxdcsj.html

[T53] Scala：字符串插值
来源：http://dali.fengsongda.top/Article/details/gtkbxfzmho.html

s"值: $b"
来源：http://dali.ehwqpu.com/Article/details/gtrhbwqgkj.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gtycloylsr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jlsjyb.cn/Article/details/gtrqdgvzmr.html

[T55] Scala：集合过滤
来源：http://dali.ydzc1.top/Article/details/gtmeqoqjzy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jinqigufen.top/Article/details/gtfckixylc.html

[T56] Scala：样例类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjfzuiavm.html

case class User(name: String, age: Int)
来源：http://dali.daria6918.cn/Article/details/gtpgzwqigc.html

[T57] Scala：模式匹配
来源：http://dali.xinyue.icu/Article/details/gtndlrddsk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xuanzx.com/Article/details/gtptwhucfr.html

[T58] Scala：函数定义
来源：http://dali.nanxuanxn.top/Article/details/gtwaacbbqi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfnyikwc.html

[T59] Scala：循环
来源：http://dali.nanxinkj.top/Article/details/gtzqjghqgh.html

for (i <- 1 to 10) println(i)
来源：http://dali.svipenyu.cn/Article/details/gtkkygkywt.html

[T60] Scala：折叠
来源：http://dali.cdnleiting.top/Article/details/gtxvkvrjez.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shangyingyoupin.top/Article/details/gtumuhbbfn.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdzqittbh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtyzpzgbgh.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtvqnaoofv.html

[U01] Py：创建虚拟环境
来源：http://dali.birdmap.top/Article/details/gtpkjnzluf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yj20258.top/Article/details/gtxhqyecjl.html

[U02] Py：导出 / 安装依赖
来源：http://dali.daria6918.cn/Article/details/gtoscgohrz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtbbyvyads.html

[U03] Py：加载 .env 配置
来源：http://dali.yangfankeji.com/Article/details/gtafjiilmp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.snrcjt.cn/Article/details/gtnyoamobm.html

[U04] Py：变量调试打印
来源：http://dali.yj20258.top/Article/details/gtjnyedpcn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cucudq.cn/Article/details/gthusjscad.html

[U05] Py：列表去重且保序
来源：http://dali.jianghu66.top/Article/details/gtrslpxuot.html

list(dict.fromkeys(arr))
来源：http://dali.yuanzhike.top/Article/details/gthwlplcfi.html

[U06] Py：合并两个字典
来源：http://dali.zhoulong.xyz/Article/details/gtwdiwaolr.html

{**a, **b}
来源：http://dali.hnqzz.top/Article/details/gtduwxrrex.html

[U07] Py：反转字典键值
来源：http://dali.nanxuanxn.top/Article/details/gtvmaoshgy.html

{v: k for k, v in d.items()}
来源：http://dali.gzhubu.top/Article/details/gtnykhvizz.html

[U08] Py：展平二维列表
来源：http://dali.zdqjudy.top/Article/details/gtmauyjipe.html

[y for x in nested for y in x]
来源：http://dali.xylfe.cn/Article/details/gtjzjolkho.html

[U09] Py：字典取最大值的键
来源：http://dali.kuanghao11.cn/Article/details/gthtbishgx.html

max(d, key=d.get)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjooiiepo.html

[U10] Py：按值排序字典
来源：http://dali.zhoulong.xyz/Article/details/gttelnrjxg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.kuanghao11.cn/Article/details/gtkytniiin.html

[U11] Py：生成器表达式
来源：http://dali.yj20258.top/Article/details/gtcrsuoksl.html

(x * 2 for x in arr)
来源：http://dali.daxiang520.top/Article/details/gtjtpjuqoy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xuetiantiany.cn/Article/details/gtxuijjune.html

Counter(arr).most_common(3)
来源：http://dali.tanke756.top/Article/details/gtxyakofpr.html

[U13] Py：固定长度队列
来源：http://dali.vqdsnc.cn/Article/details/gtsfmysjrp.html

deque(maxlen=10)
来源：http://dali.aizwys.cn/Article/details/gtcnhkdilk.html

[U14] Py：分组收集到列表
来源：http://dali.wangshuangyany.cn/Article/details/gtbibtisao.html

defaultdict(list)
来源：http://dali.hnxiangtu.top/Article/details/gtrwjdnnci.html

[U15] Py：高精度计时
来源：http://dali.haohaochexian.top/Article/details/gtgyirklpj.html

t = time.perf_counter()
来源：http://dali.snrcjt.cn/Article/details/gterxgghbh.html

[U16] Py：命令行参数解析
来源：http://dali.nanxuanxn.top/Article/details/gtmrjnbkxc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shuidangran.top/Article/details/gtymvysccz.html

[U17] Py：初始化日志
来源：http://dali.0kj1m.cn/Article/details/gtcttnjrrz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yangfankeji.com/Article/details/gtkgxnjlfh.html

[U18] Py：预编译正则
来源：http://dali.hysaishi.cn/Article/details/gtpelvtnsm.html

pat = re.compile(r"\d+")
来源：http://dali.aibaodan.cn/Article/details/gtendrjilw.html

[U19] Py：正则替换带回调
来源：http://dali.mhx1999.top/Article/details/gtvkrwgkhq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.fengsongda.top/Article/details/gtkfhyoqja.html

[U20] Py：缓存函数结果
来源：http://dali.hfpthk.cn/Article/details/gtqzdovqtu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ivvv.top/Article/details/gtencflqnd.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhongyouzk.top/Article/details/gtzuxttsxn.html

@contextlib.contextmanager
来源：http://dali.yonumen.top/Article/details/gtjrafhvkb.html

[U22] Py：矩阵转置
来源：http://dali.cheryme.top/Article/details/gtxzcwivnn.html

list(zip(*m))
来源：http://dali.daria6918.cn/Article/details/gtymunmszk.html

[U23] Py：分块读取大文件
来源：http://dali.shzxlz.cn/Article/details/gtagzajsmt.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shzxlz.cn/Article/details/gtdvaubztg.html

[U24] Py：路径操作
来源：http://dali.yj20258888.top/Article/details/gtlajniehz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yvedp.cn/Article/details/gtltvrfsph.html

[U25] Py：CSV 按字典读
来源：http://dali.zhoulong.xyz/Article/details/gtshpmfqnh.html

csv.DictReader(f)
来源：http://dali.pengpengdd.cyou/Article/details/gtwqloxhqn.html

[U26] Py：并发下载
来源：http://dali.hysaishi.cn/Article/details/gtvtovhcou.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.vqdsnc.cn/Article/details/gttakmdxrz.html

[U27] Py：异步 HTTP
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsdzjgpfs.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jlsjyb.cn/Article/details/gtfgvsicsw.html

[U28] Py：类型别名
来源：http://dali.sysykeji.top/Article/details/gtsgqcckvq.html

UserId = int
来源：http://dali.andypj.xyz/Article/details/gtkhdwbaik.html

[U29] Py：属性校验
来源：http://dali.hnxiangtu.top/Article/details/gttbzzrvzr.html

@property 与 @x.setter 配合
来源：http://dali.snrcjt.cn/Article/details/gtjwwovpcs.html

[U30] Py：数据类
来源：http://dali.dashuyun.cn/Article/details/gtbdawkicv.html

@dataclass(slots=True)
来源：http://dali.jinqigufen.top/Article/details/gtissukrtu.html

[U31] Py：单测
来源：http://dali.zhiwuduotai.top/Article/details/gtxchzdezd.html

python -m pytest -q
来源：http://dali.bjfxy.top/Article/details/gtrrrstuan.html

[U32] Py：代码格式化
来源：http://dali.jiagoushi.top/Article/details/gtnfxsanet.html

ruff format . && ruff check --fix .
来源：http://dali.yuxming.cn/Article/details/gthemmoqeg.html

[U33] Py：打包发布
来源：http://dali.nwbrower.top/Article/details/gtbcrgfxwh.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.snrcjt.cn/Article/details/gtvloqcnii.html

[U34] Py：判断编码
来源：http://dali.hongshengwenyu.top/Article/details/gtaqmcyogg.html

chardet.detect(raw)
来源：http://dali.wangdashe.top/Article/details/gttmbnxguo.html

[U35] Py：发送邮件
来源：http://dali.guannengcc.top/Article/details/gtdnklfcun.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.shzxlz.cn/Article/details/gtblzoavbi.html

[U36] Py：定时任务
来源：http://dali.pengpengdd.cyou/Article/details/gtnvsvucux.html

schedule.every(10).minutes.do(job)
来源：http://dali.mhx1999.top/Article/details/gtrcpfbjgn.html

[U37] Py：读写 Excel
来源：http://dali.yvedp.cn/Article/details/gtomfqiqgw.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hongshengwenyu.top/Article/details/gtpgczperf.html

[U38] Py：获取脚本所在目录
来源：http://dali.yongpay.top/Article/details/gtrlmobxuh.html

Path(__file__).resolve().parent
来源：http://dali.xinyue.icu/Article/details/gtvzlblxsf.html

[U39] Py：判断是否在交互环境
来源：http://dali.chenlongwang.top/Article/details/gtanhbuxzw.html

sys.stdout.isatty()
来源：http://dali.vqdsnc.cn/Article/details/gtlwabnqlg.html

[U40] Py：打印到标准错误
来源：http://dali.yuxming.cn/Article/details/gtkdcrijhl.html

print("err", file=sys.stderr)
来源：http://dali.hysaishi.cn/Article/details/gtztuwolin.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.dashuyun.cn/Article/details/gtfcamhtma.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.snrcjt.cn/Article/details/gtlycjeojw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xuanzx.com/Article/details/gtmksrtrab.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfaownsmp.html

[U43] PHP：声明命名空间
来源：http://dali.hysaishi.cn/Article/details/gthipvtipi.html

namespace App\Http;
来源：http://dali.cashguo.top/Article/details/gtiszjitrn.html

[U44] PHP：开启严格类型
来源：http://dali.daxiang520.top/Article/details/gtzfwwxvvi.html

declare(strict_types=1);
来源：http://dali.cucudq.cn/Article/details/gtjrwebkgc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yanxiufei.cn/Article/details/gtttzbwpha.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.meibo888.top/Article/details/gtlojtfhpz.html

[U46] PHP：可空类型
来源：http://dali.chenlongwang.top/Article/details/gtxyfsqxje.html

?string $name = null
来源：http://dali.wangdashe.top/Article/details/gterlwkjry.html

[U47] PHP：联合类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwllqysmg.html

int|string $id
来源：http://dali.nanxuanxn.top/Article/details/gtrahrfbhh.html

[U48] PHP：纯枚举
来源：http://dali.mhx1999.top/Article/details/gtphmmvbwm.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hfpthk.cn/Article/details/gteyvljsww.html

[U49] PHP：只读属性
来源：http://dali.tian-w.cn/Article/details/gtkcaluqqd.html

public readonly string $name
来源：http://dali.wangshuangyany.cn/Article/details/gtryfmiglx.html

[U50] PHP：构造器属性提升
来源：http://dali.nanxinkj.top/Article/details/gtviraavfi.html

public function __construct(private int $id) {}
来源：http://dali.kuanghao11.cn/Article/details/gtlelikufz.html

[U51] PHP：数组解构
来源：http://dali.feifeiyinyue.top/Article/details/gtmwuzvzpk.html

[$a, $b] = $arr;
来源：http://dali.zhengqikj.top/Article/details/gtyrlmunxp.html

[U52] PHP：箭头函数
来源：http://dali.hnxiangtu.top/Article/details/gtfprzuemc.html

$double = fn($x) => $x * 2;
来源：http://dali.smart0.xyz/Article/details/gthxrgucxy.html

[U53] PHP：空合并运算符
来源：http://dali.jqgfzy.top/Article/details/gtwdqtydvx.html

$v = $a ?? $b ?? "default";
来源：http://dali.jiagoushi.top/Article/details/gtohyprpzi.html

[U54] PHP：空安全调用
来源：http://dali.sufxvd.cn/Article/details/gtimeaxxfh.html

$obj?->method()
来源：http://dali.chenjidiqi.icu/Article/details/gtovlniduf.html

[U55] PHP：match 表达式
来源：http://dali.gzhubu.top/Article/details/gtanqgsjkw.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hfpthk.cn/Article/details/gtdxeyvjbn.html

[U56] PHP：命名参数
来源：http://dali.wangshuangyany.cn/Article/details/gtsabdxyhi.html

f(a: 1, b: 2)
来源：http://dali.sufxvd.cn/Article/details/gtzdvaezkz.html

[U57] PHP：字符串插值
来源：http://dali.ybcxt.top/Article/details/gtycksawhv.html

"值: {$a}"
来源：http://dali.yongpay.top/Article/details/gtwfepankj.html

[U58] PHP：数组三件套
来源：http://dali.hywenlv.cn/Article/details/gtbffzhhtw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.wangdashe.top/Article/details/gtcxyrakpz.html

[U59] PHP：自定义排序
来源：http://dali.yangfankeji.com/Article/details/gtfszbhzhn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.smart0.xyz/Article/details/gtyijrvdqb.html

[U60] PHP：JSON 编解码
来源：http://dali.guannengcc.top/Article/details/gtxjlitmol.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ybcxt.top/Article/details/gthwtoghwj.html

[U61] PHP：正则
来源：http://dali.316326.xyz/Article/details/gtqhlnknfg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.sweek.top/Article/details/gtnxmirdpv.html

[U62] PHP：日期对象
来源：http://dali.dianchejie.cn/Article/details/gtfvsurrgb.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.9152youxi.cn/Article/details/gtxuyvcpmh.html

[U63] PHP：文件读写
来源：http://dali.nanxinkj.top/Article/details/gtkkbfcwog.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hongshengwenyu.top/Article/details/gtytlixxqp.html

[U64] PHP：目录遍历
来源：http://dali.9152youxi.cn/Article/details/gtfweubzts.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.daria6918.cn/Article/details/gtwaojgisd.html

[U65] PHP：会话
来源：http://dali.quarkkingdee.top/Article/details/gtltdnwddh.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.meibo888.top/Article/details/gtpxehagoq.html

[U66] PHP：设置 Cookie
来源：http://dali.hnxiangtu.top/Article/details/gttavocimt.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.tianlin.xyz/Article/details/gtnzynrlbk.html

[U67] PHP：处理文件上传
来源：http://dali.tanke756.top/Article/details/gtliykzquk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.cdnleiting.top/Article/details/gtycfanisk.html

[U68] PHP：PDO 连接
来源：http://dali.yonumen.top/Article/details/gtdfdcpesx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.redwolf501.top/Article/details/gthmoijcyg.html

[U69] PHP：PDO 预处理
来源：http://dali.shangyingyoupin.top/Article/details/gtzdyukhll.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yangfankeji.com/Article/details/gtnsunvggg.html

[U70] PHP：PDO 事务
来源：http://dali.bjfxy.top/Article/details/gtbcsjomgt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.shzxlz.cn/Article/details/gtrcqlgcir.html


<!-- 参考信息 -->