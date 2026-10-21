代发 wailian999

[S45] C++：lambda
来源：http://dali.bjfxy.top/Article/details/gtbeifkhag.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sweek.top/Article/details/gtpsdoeaxc.html

[S46] C++：函数模板
来源：http://dali.daxiang520.top/Article/details/gtbjnqwtzi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.snrcjt.cn/Article/details/gtladrnibl.html

[S47] C++：结构化绑定遍历
来源：http://dali.pengpengdd.cyou/Article/details/gthdandxqc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj20258.top/Article/details/gtouuawsof.html

[S48] C++：逐行读文件
来源：http://dali.meibo888.top/Article/details/gthrwdgvns.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cqqwz.cn/Article/details/gtedztejby.html

while (std::getline(in, line)) { }
来源：http://dali.gzhubu.top/Article/details/gteyvttdsn.html

[S49] C++：写文件
来源：http://dali.zdqjudy.top/Article/details/gtvlmhfiid.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.smart0.xyz/Article/details/gthdctisyp.html

[S50] C++：格式化数字
来源：http://dali.yanxiufei.cn/Article/details/gtgfehtnwv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cashguo.top/Article/details/gtgghfamtx.html

[S51] C++：显式类型转换
来源：http://dali.yvedp.cn/Article/details/gtvjjbwypu.html

static_cast<double>(a) / b
来源：http://dali.jqgfzy.top/Article/details/gtityrigfm.html

[S52] C++：const 与 noexcept
来源：http://dali.hysaishi.cn/Article/details/gtkhnoteks.html

int size() const noexcept { return n_; }
来源：http://dali.cqqwz.cn/Article/details/gtmhwdxxxc.html

[S53] C++：移动语义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiazpoorr.html

std::vector<int> w = std::move(v);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthxbatlep.html

[S54] C++：异常处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtogpjnoda.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.wangshuangyany.cn/Article/details/gtyumgwkxa.html

[S55] C++：结构化绑定
来源：http://dali.tianlin.xyz/Article/details/gtrzwawqid.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.316326.xyz/Article/details/gtiuimhirk.html

[S56] C++：optional
来源：http://dali.feifeiyinyue.top/Article/details/gtwqtpmwgz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hnqzz.top/Article/details/gtnjqtzkjb.html

[S57] C++：编译期常量
来源：http://dali.cucudq.cn/Article/details/gtnutfrxok.html

constexpr int N = 10;
来源：http://dali.zhixingplan.top/Article/details/gtwrhmmqqx.html

[S58] C++：命名空间
来源：http://dali.zhiwuduotai.top/Article/details/gtzytjoqdl.html

namespace ns { int f() { return 1; } }
来源：http://dali.nanxinkj.top/Article/details/gtkztavlpl.html

[S59] C++：静态断言
来源：http://dali.pycfn.com/Article/details/gtxgphpbvi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jlsjyb.cn/Article/details/gtihlwjymc.html

[S60] C++：遍历并删除元素
来源：http://dali.quarkkingdee.top/Article/details/gtpxlourvs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yongpay.top/Article/details/gtzecnukke.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtoudtilvs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shzxlz.cn/Article/details/gturmsnawq.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtobdpfapp.html

[T01] Kotlin：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtnierlebx.html

println("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gtctlqvbub.html

[T02] Kotlin：变量
来源：http://dali.pycfn.com/Article/details/gtbubpbxyf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yuxming.cn/Article/details/gtpbgoiotn.html

[T03] Kotlin：字符串模板
来源：http://dali.haohaochexian.top/Article/details/gtmavxqmpv.html

"值: $b"
来源：http://dali.xinyue.icu/Article/details/gtprxkhogz.html

[T04] Kotlin：空安全
来源：http://dali.smart0.xyz/Article/details/gtamfanebj.html

val n: String? = null;  n?.length
来源：http://dali.nanxuanxn.top/Article/details/gtkpicuepp.html

[T05] Kotlin：when 表达式
来源：http://dali.snrcjt.cn/Article/details/gttpihwfmw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.9152youxi.cn/Article/details/gtbgovxefn.html

[T06] Kotlin：集合映射
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdcmwfrbc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuxzgnsrv.html

[T07] Kotlin：集合过滤
来源：http://dali.jqgfzy.top/Article/details/gttcvrtxmo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.pengpengdd.cyou/Article/details/gtnzqexztr.html

[T08] Kotlin：数据类
来源：http://dali.ehwqpu.com/Article/details/gtoqlojjsx.html

data class User(val name: String, val age: Int)
来源：http://dali.redwolf501.top/Article/details/gtxmsvhnlc.html

[T09] Kotlin：扩展函数
来源：http://dali.nanxuanxn.top/Article/details/gtzcvympuj.html

fun String.exclaim() = this + "!"
来源：http://dali.shzxlz.cn/Article/details/gtoalpefbn.html

[T10] Kotlin：默认参数
来源：http://dali.xinyue.icu/Article/details/gtqvsircrt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cucudq.cn/Article/details/gtkzqvjqop.html

[T11] Kotlin：协程
来源：http://dali.pengpengdd.cyou/Article/details/gtmgoghuef.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.smart0.xyz/Article/details/gtfxyfoovt.html

[T12] Kotlin：解构声明
来源：http://dali.meibo888.top/Article/details/gtqkwfvmbs.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtuzuxgtmi.html

[T13] Kotlin：只读 Map
来源：http://dali.cqqwz.cn/Article/details/gtmfgvntjj.html

val m = mapOf("a" to 1)
来源：http://dali.zhoulong.xyz/Article/details/gtirzaguyw.html

[T14] Kotlin：循环
来源：http://dali.yuanzhike.top/Article/details/gtwkvmlnun.html

for (i in 1..10) println(i)
来源：http://dali.wangshuangyany.cn/Article/details/gtzpycdtcy.html

[T15] Kotlin：接口
来源：http://dali.chenzaomai.com/Article/details/gtkbjlukkm.html

interface Shape { fun area(): Double }
来源：http://dali.wangshuangyany.cn/Article/details/gtclsouwuv.html

[T16] Swift：Hello World
来源：http://dali.havefunace.top/Article/details/gtwanzqkqh.html

print("Hello")
来源：http://dali.guannengcc.top/Article/details/gtqvlwpqqx.html

[T17] Swift：变量与常量
来源：http://dali.mhx1999.top/Article/details/gtswvwzhkd.html

var a = 1;  let b = 2
来源：http://dali.hnxiangtu.top/Article/details/gtutegnhso.html

[T18] Swift：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gthpehzrix.html

"值: \(b)"
来源：http://dali.xinyue.icu/Article/details/gttnwxrbzg.html

[T19] Swift：可选绑定
来源：http://dali.hysaishi.cn/Article/details/gttxnqolvi.html

if let n = opt { print(n) }
来源：http://dali.yuanzhike.top/Article/details/gtoqzsfqzj.html

[T20] Swift：数组操作
来源：http://dali.shzxlz.cn/Article/details/gtwbsbnvmv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ppjwa.cn/Article/details/gtmewbfmyy.html

[T21] Swift：遍历
来源：http://dali.andypj.xyz/Article/details/gtvlzkugss.html

for x in a { print(x) }
来源：http://dali.yuxming.cn/Article/details/gtdyhsblia.html

[T22] Swift：字典
来源：http://dali.kuanghao11.cn/Article/details/gthkgpobxs.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jyoumei.cn/Article/details/gtnfppgbnm.html

[T23] Swift：函数
来源：http://dali.yuxming.cn/Article/details/gtqwggnpxr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yuxming.cn/Article/details/gtsivhkxfl.html

[T24] Swift：闭包
来源：http://dali.ppjwa.cn/Article/details/gtoqulibcn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yvedp.cn/Article/details/gtonyfdvye.html

[T25] Swift：结构体
来源：http://dali.wangshuangyany.cn/Article/details/gtrgjksfyv.html

struct P { var x: Int }
来源：http://dali.chenzaomai.com/Article/details/gtapbhhoig.html

[T26] Swift：类与重写
来源：http://dali.sxryk.cn/Article/details/gtrnungttt.html

class A: Base { override func f() {} }
来源：http://dali.c1oappe.top/Article/details/gtiyowymoq.html

[T27] Swift：错误处理
来源：http://dali.sysykeji.top/Article/details/gtqmxedczg.html

do { try f() } catch { print(error) }
来源：http://dali.chenlongwang.top/Article/details/gtnfnsqamk.html

[T28] Swift：枚举
来源：http://dali.cucudq.cn/Article/details/gtkcjmwpxd.html

enum Color { case red, green }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtewojnffa.html

[T29] Swift：guard 提前返回
来源：http://dali.dianchejie.cn/Article/details/gtnlwxoesm.html

guard let x = opt else { return }
来源：http://dali.gotoacloud.top/Article/details/gtfbyuhcbc.html

[T30] Swift：协议
来源：http://dali.aizwys.cn/Article/details/gthgkspvhi.html

protocol Shape { func area() -> Double }
来源：http://dali.svipenyu.cn/Article/details/gtromhuzmn.html

[T31] Lua：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtybonlkxd.html

print("Hello")
来源：http://dali.tianlin.xyz/Article/details/gtyhgwpmcn.html

[T32] Lua：局部变量
来源：http://dali.gaohongyu789.top/Article/details/gtqnfuncfv.html

local a = 1
来源：http://dali.cqqwz.cn/Article/details/gtpywpzsnd.html

[T33] Lua：表（数组）
来源：http://dali.sysykeji.top/Article/details/gtcktxulqa.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sxryk.cn/Article/details/gttpszjope.html

[T34] Lua：遍历表
来源：http://dali.mhx1999.top/Article/details/gtgudafyoy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gogol.net.cn/Article/details/gtkabzqboh.html

[T35] Lua：字典表
来源：http://dali.xylfe.cn/Article/details/gtiimovksr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tanke756.top/Article/details/gtavjhilht.html

[T36] Lua：函数
来源：http://dali.cqqwz.cn/Article/details/gtzoheiqwb.html

function add(a, b) return a + b end
来源：http://dali.nanxuanxn.top/Article/details/gtadmmqtrd.html

[T37] Lua：字符串拼接
来源：http://dali.gogol.net.cn/Article/details/gtuswobykc.html

"a" .. "b"
来源：http://dali.zhengqikj.top/Article/details/gtzoeeygpl.html

[T38] Lua：条件
来源：http://dali.haohaochexian.top/Article/details/gtxpfmfkmu.html

if x > 0 then print("正") end
来源：http://dali.redwolf501.top/Article/details/gttrnnvgbv.html

[T39] Lua：模式匹配
来源：http://dali.dashuyun.cn/Article/details/gtzdavqjzu.html

string.find(s, "%d+")
来源：http://dali.nwbrower.top/Article/details/gtbeoawuwu.html

[T40] Lua：元表
来源：http://dali.hnqzz.top/Article/details/gtplkhklpo.html

setmetatable({}, { __index = base })
来源：http://dali.aizwys.cn/Article/details/gtvgcauccl.html

[T41] Perl：Hello World
来源：http://dali.iojbl.cn/Article/details/gttpqgnzqx.html

print "Hello\n";
来源：http://dali.gogol.net.cn/Article/details/gttwnvpouv.html

[T42] Perl：变量类型
来源：http://dali.yongpay.top/Article/details/gtncubwqeo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shzxlz.cn/Article/details/gtbhnhcuwg.html

[T43] Perl：字符串插值
来源：http://dali.zhixingplan.top/Article/details/gtqinbcoov.html

"值: $a"
来源：http://dali.kuanghao11.cn/Article/details/gtuuahhbse.html

[T44] Perl：条件
来源：http://dali.pengpengdd.cyou/Article/details/gtfztoumcv.html

if ($a > 0) { print "正"; }
来源：http://dali.shuidangran.top/Article/details/gtdftlmyzt.html

[T45] Perl：数组遍历
来源：http://dali.tanke756.top/Article/details/gtykayqdjm.html

for my $x (@arr) { print $x; }
来源：http://dali.jlsjyb.cn/Article/details/gtvnwqxell.html

[T46] Perl：哈希操作
来源：http://dali.fzhhl.top/Article/details/gtpoitxjyp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.nwbrower.top/Article/details/gtkrudlqhj.html

[T47] Perl：正则捕获
来源：http://dali.xinyue.icu/Article/details/gtpimzuurt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmhrzwoqh.html

[T48] Perl：正则替换
来源：http://dali.yuanzhike.top/Article/details/gtyujnbzvl.html

$s =~ s/old/new/g;
来源：http://dali.xziqi.cn/Article/details/gtjcgjxrsq.html

[T49] Perl：函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gthvafchym.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gtmxamumsf.html

[T50] Perl：逐行读文件
来源：http://dali.ivvv.top/Article/details/gtdxbcdknd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.guowangkeji.top/Article/details/gtopafojmp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebqyfhpk.html

[T51] Scala：Hello World
来源：http://dali.guannengcc.top/Article/details/gtcvguarki.html

println("Hello")
来源：http://dali.snrcjt.cn/Article/details/gthxecppuj.html

[T52] Scala：变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwizqkecp.html

val a = 1;  var b = 2
来源：http://dali.jinqigfzy.top/Article/details/gtiduevhyk.html

[T53] Scala：字符串插值
来源：http://dali.ybcxt.top/Article/details/gtgssrccgi.html

s"值: $b"
来源：http://dali.0kj1m.cn/Article/details/gtbrmwfuhg.html

[T54] Scala：集合映射
来源：http://dali.cheryme.top/Article/details/gtxpqgsxoh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yuxming.cn/Article/details/gteepgjrmd.html

[T55] Scala：集合过滤
来源：http://dali.chenzaomai.com/Article/details/gtnbjlefpf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtlczomfrd.html

[T56] Scala：样例类
来源：http://dali.iojbl.cn/Article/details/gtlvoqmkyg.html

case class User(name: String, age: Int)
来源：http://dali.daxiang520.top/Article/details/gtfknnnzxy.html

[T57] Scala：模式匹配
来源：http://dali.chenlongwang.top/Article/details/gtamfkcqxr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hammf.cn/Article/details/gteexklohp.html

[T58] Scala：函数定义
来源：http://dali.zhengqikj.top/Article/details/gtmxfjsokn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhiwuduotai.top/Article/details/gtfcqggcuj.html

[T59] Scala：循环
来源：http://dali.guowangkeji.top/Article/details/gtlglfknud.html

for (i <- 1 to 10) println(i)
来源：http://dali.dashuyun.cn/Article/details/gtuyagaeoe.html

[T60] Scala：折叠
来源：http://dali.feifeiyinyue.top/Article/details/gtvoswmnai.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hongshengwenyu.top/Article/details/gthkyjvitf.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtxdvjisos.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gaohongyu789.top/Article/details/gtavsvktpk.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtztevewvz.html

[U01] Py：创建虚拟环境
来源：http://dali.nanxuanxn.top/Article/details/gtcgycbcrl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cqqwz.cn/Article/details/gtchepswqj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ivvv.top/Article/details/gtovhswwnw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gzhubu.top/Article/details/gtycjrjymu.html

[U03] Py：加载 .env 配置
来源：http://dali.vqdsnc.cn/Article/details/gtjqaclwic.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.fzhhl.top/Article/details/gtarzdtcpt.html

[U04] Py：变量调试打印
来源：http://dali.pycfn.com/Article/details/gtcphofkfx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xziqi.cn/Article/details/gtycseflsk.html

[U05] Py：列表去重且保序
来源：http://dali.xylfe.cn/Article/details/gtmlntolyt.html

list(dict.fromkeys(arr))
来源：http://dali.c1oappe.top/Article/details/gtmgeovjcx.html

[U06] Py：合并两个字典
来源：http://dali.jianghu66.top/Article/details/gtwvsvechf.html

{**a, **b}
来源：http://dali.quarkkingdee.top/Article/details/gtwmkluaxr.html

[U07] Py：反转字典键值
来源：http://dali.smart0.xyz/Article/details/gtjfnchtrk.html

{v: k for k, v in d.items()}
来源：http://dali.iojbl.cn/Article/details/gtikpynjsb.html

[U08] Py：展平二维列表
来源：http://dali.cashguo.top/Article/details/gtchifbxbz.html

[y for x in nested for y in x]
来源：http://dali.guannengcc.top/Article/details/gtiyiaoapd.html

[U09] Py：字典取最大值的键
来源：http://dali.316326.xyz/Article/details/gtlrukpzgo.html

max(d, key=d.get)
来源：http://dali.daxiang520.top/Article/details/gtfdnlnfqj.html

[U10] Py：按值排序字典
来源：http://dali.ivvv.top/Article/details/gtgtijgmdo.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.guowangkeji.top/Article/details/gtpwziurrx.html

[U11] Py：生成器表达式
来源：http://dali.yj202588.top/Article/details/gtvkabtysj.html

(x * 2 for x in arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtsnqqbjlz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yueranfly.top/Article/details/gtexzeoxro.html

Counter(arr).most_common(3)
来源：http://dali.meibo888.top/Article/details/gtvplqihhq.html

[U13] Py：固定长度队列
来源：http://dali.yongpay.top/Article/details/gtoievgayl.html

deque(maxlen=10)
来源：http://dali.wangshuangyany.cn/Article/details/gtswwdnnir.html

[U14] Py：分组收集到列表
来源：http://dali.nanxinkj.top/Article/details/gtylzoklwa.html

defaultdict(list)
来源：http://dali.smart0.xyz/Article/details/gthtjcoode.html

[U15] Py：高精度计时
来源：http://dali.chenjidiqi.icu/Article/details/gtjhigtoob.html

t = time.perf_counter()
来源：http://dali.jlsjyb.cn/Article/details/gtcjdkgzjv.html

[U16] Py：命令行参数解析
来源：http://dali.birdmap.top/Article/details/gtiwpwcmum.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.sysykeji.top/Article/details/gtclirwbio.html

[U17] Py：初始化日志
来源：http://dali.c1oappe.top/Article/details/gtacypcdgw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xylfe.cn/Article/details/gtmasmldvy.html

[U18] Py：预编译正则
来源：http://dali.iojbl.cn/Article/details/gtkhbfgrsa.html

pat = re.compile(r"\d+")
来源：http://dali.sxryk.cn/Article/details/gtnojxwfaf.html

[U19] Py：正则替换带回调
来源：http://dali.ydzc1.top/Article/details/gtvuafgasm.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xuanzx.com/Article/details/gtdcsozkcj.html

[U20] Py：缓存函数结果
来源：http://dali.ydzc1.top/Article/details/gtcfiajbxy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhoulong.xyz/Article/details/gtgggnbkyy.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinqigufen.top/Article/details/gtsyucycja.html

@contextlib.contextmanager
来源：http://dali.cdnleiting.top/Article/details/gtwwsddgvc.html

[U22] Py：矩阵转置
来源：http://dali.zhixingplan.top/Article/details/gtwgynbjfu.html

list(zip(*m))
来源：http://dali.cdnleiting.top/Article/details/gtsjebdffy.html

[U23] Py：分块读取大文件
来源：http://dali.zhengqikj.top/Article/details/gtkrtkxeos.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.sweek.top/Article/details/gtivysytkp.html

[U24] Py：路径操作
来源：http://dali.vqdsnc.cn/Article/details/gtfzaogute.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjermhjxr.html

[U25] Py：CSV 按字典读
来源：http://dali.hywenlv.cn/Article/details/gtdyoihsep.html

csv.DictReader(f)
来源：http://dali.ehwqpu.com/Article/details/gtuesntngb.html

[U26] Py：并发下载
来源：http://dali.jqgfzy.top/Article/details/gtltanhrie.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.nwbrower.top/Article/details/gtbhqsgzua.html

[U27] Py：异步 HTTP
来源：http://dali.tian-w.cn/Article/details/gtzfaxjwtn.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hfpthk.cn/Article/details/gtgianafyc.html

[U28] Py：类型别名
来源：http://dali.andypj.xyz/Article/details/gtrmcercwx.html

UserId = int
来源：http://dali.pengpengdd.cyou/Article/details/gtffkahvpj.html

[U29] Py：属性校验
来源：http://dali.ydzc1.top/Article/details/gtbyackhgz.html

@property 与 @x.setter 配合
来源：http://dali.tanke756.top/Article/details/gtmlkljmix.html

[U30] Py：数据类
来源：http://dali.jqgfzy.top/Article/details/gthpqpsndm.html

@dataclass(slots=True)
来源：http://dali.xziqi.cn/Article/details/gtgekxjwcj.html

[U31] Py：单测
来源：http://dali.quarkkingdee.top/Article/details/gtpomaljlc.html

python -m pytest -q
来源：http://dali.nanxinkj.top/Article/details/gthajgjpom.html

[U32] Py：代码格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gtfeuclzqw.html

ruff format . && ruff check --fix .
来源：http://dali.fengsongda.top/Article/details/gtypmbsxcn.html

[U33] Py：打包发布
来源：http://dali.andypj.xyz/Article/details/gtzoyhzqxm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ybcxt.top/Article/details/gtewjuycke.html

[U34] Py：判断编码
来源：http://dali.gotoacloud.top/Article/details/gtifdscyzv.html

chardet.detect(raw)
来源：http://dali.haohaochexian.top/Article/details/gteqagbulu.html

[U35] Py：发送邮件
来源：http://dali.andypj.xyz/Article/details/gtadfbrbsx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.aizwys.cn/Article/details/gtiobdsfbv.html

[U36] Py：定时任务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxlnentqy.html

schedule.every(10).minutes.do(job)
来源：http://dali.sysykeji.top/Article/details/gtpcridbqh.html

[U37] Py：读写 Excel
来源：http://dali.nanxinkj.top/Article/details/gttveyvcbm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.bjfxy.top/Article/details/gtkqfbblqh.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhixingplan.top/Article/details/gtiizblhbn.html

Path(__file__).resolve().parent
来源：http://dali.redwolf501.top/Article/details/gtahlaxmbq.html

[U39] Py：判断是否在交互环境
来源：http://dali.hnqzz.top/Article/details/gtvlcdjers.html

sys.stdout.isatty()
来源：http://dali.shzxlz.cn/Article/details/gthqmzpnel.html

[U40] Py：打印到标准错误
来源：http://dali.xinyue.icu/Article/details/gtpahrpbyl.html

print("err", file=sys.stderr)
来源：http://dali.shangyingyoupin.top/Article/details/gtlssnmvvy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.guannengcc.top/Article/details/gtytsodhuj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.nanxuanxn.top/Article/details/gthsdvetrq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.wangdashe.top/Article/details/gtgpfiurxm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hysaishi.cn/Article/details/gtsexwfime.html

[U43] PHP：声明命名空间
来源：http://dali.hywenlv.cn/Article/details/gtaonzpqjz.html

namespace App\Http;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjwemknuj.html

[U44] PHP：开启严格类型
来源：http://dali.andypj.xyz/Article/details/gtsfqyqihl.html

declare(strict_types=1);
来源：http://dali.ppjwa.cn/Article/details/gtgltzorle.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jlsjyb.cn/Article/details/gtprrwyknb.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzcezsqre.html

[U46] PHP：可空类型
来源：http://dali.guowangkeji.top/Article/details/gtcqwyxydi.html

?string $name = null
来源：http://dali.hongshengwenyu.top/Article/details/gtflyamlas.html

[U47] PHP：联合类型
来源：http://dali.yuxming.cn/Article/details/gtgbfsjqjw.html

int|string $id
来源：http://dali.cucudq.cn/Article/details/gtxrtnyuid.html

[U48] PHP：纯枚举
来源：http://dali.iojbl.cn/Article/details/gtssbgtamw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.chenlongwang.top/Article/details/gtnovbpjzh.html

[U49] PHP：只读属性
来源：http://dali.dianchejie.cn/Article/details/gtpzvxxlbq.html

public readonly string $name
来源：http://dali.bjfxy.top/Article/details/gttrzuqdrc.html

[U50] PHP：构造器属性提升
来源：http://dali.shuidangran.top/Article/details/gtrfefmqvp.html

public function __construct(private int $id) {}
来源：http://dali.hnqzz.top/Article/details/gtzeyazyka.html

[U51] PHP：数组解构
来源：http://dali.jinqigufen.top/Article/details/gttelpcsfx.html

[$a, $b] = $arr;
来源：http://dali.hnxiangtu.top/Article/details/gteptaoewg.html

[U52] PHP：箭头函数
来源：http://dali.jqgufenzy.top/Article/details/gtouvtjlue.html

$double = fn($x) => $x * 2;
来源：http://dali.xylfe.cn/Article/details/gtvfogktcq.html

[U53] PHP：空合并运算符
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmukalzr.html

$v = $a ?? $b ?? "default";
来源：http://dali.hfpthk.cn/Article/details/gtzyolugwk.html

[U54] PHP：空安全调用
来源：http://dali.shzxlz.cn/Article/details/gtspxpqclt.html

$obj?->method()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtglxqkwco.html

[U55] PHP：match 表达式
来源：http://dali.hongshengwenyu.top/Article/details/gtpawendfh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.mhx1999.top/Article/details/gtykyqixbj.html

[U56] PHP：命名参数
来源：http://dali.zhoulong.xyz/Article/details/gtalkuxuet.html

f(a: 1, b: 2)
来源：http://dali.bjfxy.top/Article/details/gtvvfwcssn.html

[U57] PHP：字符串插值
来源：http://dali.wangdashe.top/Article/details/gtfesnmhkc.html

"值: {$a}"
来源：http://dali.zhongyouzk.top/Article/details/gtudhvgdbx.html

[U58] PHP：数组三件套
来源：http://dali.wangshuangyany.cn/Article/details/gtrllktsjt.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yvedp.cn/Article/details/gtvzxgsbhz.html

[U59] PHP：自定义排序
来源：http://dali.gaohongyu789.top/Article/details/gtalnonnot.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyhphpoja.html

[U60] PHP：JSON 编解码
来源：http://dali.jianghu66.top/Article/details/gtgjskagye.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.shzxlz.cn/Article/details/gtkszceuow.html

[U61] PHP：正则
来源：http://dali.gaohongyu789.top/Article/details/gtuecceggt.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.fengsongda.top/Article/details/gtdyjrmsxe.html

[U62] PHP：日期对象
来源：http://dali.guannengcc.top/Article/details/gteqtzvofo.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yonumen.top/Article/details/gtaxuplrph.html

[U63] PHP：文件读写
来源：http://dali.yj20258888.top/Article/details/gtrpteuszg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.ivvv.top/Article/details/gtincrwczb.html

[U64] PHP：目录遍历
来源：http://dali.cqqwz.cn/Article/details/gtljedzixs.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yongpay.top/Article/details/gtlriwakre.html

[U65] PHP：会话
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfnrvbtj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gtzphxnfxy.html

[U66] PHP：设置 Cookie
来源：http://dali.yongpay.top/Article/details/gtlkehpnac.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.chenzaomai.com/Article/details/gtkuftfgxd.html

[U67] PHP：处理文件上传
来源：http://dali.haohaochexian.top/Article/details/gttawybrfj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaqhckmrx.html

[U68] PHP：PDO 连接
来源：http://dali.yonumen.top/Article/details/gtkngvfzvf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.daria6918.cn/Article/details/gtabclwbjb.html

[U69] PHP：PDO 预处理
来源：http://dali.9152youxi.cn/Article/details/gtbmclgkvk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gtjpljkwnu.html

[U70] PHP：PDO 事务
来源：http://dali.jinqigufen.top/Article/details/gtvhsacpap.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.9152youxi.cn/Article/details/gtfqnxxyyc.html


<!-- 参考信息 -->