代发 wailian999

[S39] C++：自定义比较器排序
来源：http://dali.316326.xyz/Article/details/gtlrhwnbmh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guowangkeji.top/Article/details/gtctonfobc.html

[S40] C++：查找元素
来源：http://dali.wangdashe.top/Article/details/gtupopacuj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtnepyymet.html

[S41] C++：类与构造函数
来源：http://dali.yuanzhike.top/Article/details/gtcgypkvqx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tian-w.cn/Article/details/gtpwuxviwh.html

[S42] C++：继承与虚函数
来源：http://dali.yonumen.top/Article/details/gtalupbfee.html

class B : public Base { public: void f() override {} };
来源：http://dali.redwolf501.top/Article/details/gtvnfjihdb.html

[S43] C++：智能指针
来源：http://dali.cqqwz.cn/Article/details/gtnvtpqubs.html

auto p = std::make_unique<int>(5);
来源：http://dali.andypj.xyz/Article/details/gtycrofqvp.html

[S44] C++：引用传参
来源：http://dali.zhongyouzk.top/Article/details/gtdvklblzi.html

void inc(int &x) { ++x; }
来源：http://dali.fzhhl.top/Article/details/gtpdnkfizf.html

[S45] C++：lambda
来源：http://dali.sysykeji.top/Article/details/gtwgqmygdw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.quarkkingdee.top/Article/details/gtzmpobhkl.html

[S46] C++：函数模板
来源：http://dali.birdmap.top/Article/details/gtozkdhuyf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.0kj1m.cn/Article/details/gtfbotehws.html

[S47] C++：结构化绑定遍历
来源：http://dali.shuidangran.top/Article/details/gtbotoluyr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.9152youxi.cn/Article/details/gtotpdknsn.html

[S48] C++：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gttbiaivay.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gotoacloud.top/Article/details/gtaxuqnmjf.html

while (std::getline(in, line)) { }
来源：http://dali.0kj1m.cn/Article/details/gtjdmagvgp.html

[S49] C++：写文件
来源：http://dali.chenlongwang.top/Article/details/gtltwsaebh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.redwolf501.top/Article/details/gtnrporzcy.html

[S50] C++：格式化数字
来源：http://dali.316326.xyz/Article/details/gtlvvxapan.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yonumen.top/Article/details/gtiloxbyrv.html

[S51] C++：显式类型转换
来源：http://dali.sufxvd.cn/Article/details/gtprnsdmhr.html

static_cast<double>(a) / b
来源：http://dali.iojbl.cn/Article/details/gtnthhgxjz.html

[S52] C++：const 与 noexcept
来源：http://dali.redwolf501.top/Article/details/gtzfbeffwx.html

int size() const noexcept { return n_; }
来源：http://dali.havefunace.top/Article/details/gtkkdvmihf.html

[S53] C++：移动语义
来源：http://dali.jiagoushi.top/Article/details/gtssajsdvw.html

std::vector<int> w = std::move(v);
来源：http://dali.daria6918.cn/Article/details/gtllcjbdqv.html

[S54] C++：异常处理
来源：http://dali.zhongyouzk.top/Article/details/gtitfazwnp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.meibo888.top/Article/details/gtszqcszwa.html

[S55] C++：结构化绑定
来源：http://dali.hysaishi.cn/Article/details/gtviysbenr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.iojbl.cn/Article/details/gtuybdzaul.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gtwyjtvfck.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jyoumei.cn/Article/details/gtyfbjdycp.html

[S57] C++：编译期常量
来源：http://dali.yuxming.cn/Article/details/gtfwwzkgem.html

constexpr int N = 10;
来源：http://dali.jlsjyb.cn/Article/details/gtqmukopcc.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gtshauxuhs.html

namespace ns { int f() { return 1; } }
来源：http://dali.dianchejie.cn/Article/details/gtpzkbsltt.html

[S59] C++：静态断言
来源：http://dali.aibaodan.cn/Article/details/gtrjjcxpyc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yanxiufei.cn/Article/details/gtdenfpyyr.html

[S60] C++：遍历并删除元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtniyjqhva.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.dashuyun.cn/Article/details/gteotnecgl.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtckjgrhic.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.316326.xyz/Article/details/gtrhgclaqj.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwytyuzfi.html

[T01] Kotlin：Hello World
来源：http://dali.yj20258.top/Article/details/gtbqjhvlbk.html

println("Hello")
来源：http://dali.tanke756.top/Article/details/gtbxvyqiya.html

[T02] Kotlin：变量
来源：http://dali.chenjidiqi.icu/Article/details/gtnrretkxv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhaomingkeji.xyz/Article/details/gtudaepqiz.html

[T03] Kotlin：字符串模板
来源：http://dali.birdmap.top/Article/details/gtrzcnpeqo.html

"值: $b"
来源：http://dali.guowangkeji.top/Article/details/gtxkxthjkm.html

[T04] Kotlin：空安全
来源：http://dali.hammf.cn/Article/details/gtthzcrqhd.html

val n: String? = null;  n?.length
来源：http://dali.nanxuanxn.top/Article/details/gtoaoskfzu.html

[T05] Kotlin：when 表达式
来源：http://dali.cqqwz.cn/Article/details/gtpbvsubqq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhengqikj.top/Article/details/gtlsvtfjbd.html

[T06] Kotlin：集合映射
来源：http://dali.sweek.top/Article/details/gtwfdbhcqm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cheryme.top/Article/details/gtrxvpbduc.html

[T07] Kotlin：集合过滤
来源：http://dali.dianchejie.cn/Article/details/gtqshdbpxd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkrckpuil.html

[T08] Kotlin：数据类
来源：http://dali.shanyushiyangkeji.top/Article/details/gthefdteyo.html

data class User(val name: String, val age: Int)
来源：http://dali.jianghu66.top/Article/details/gtlawdkfbx.html

[T09] Kotlin：扩展函数
来源：http://dali.yj20258888.top/Article/details/gtkgwirocj.html

fun String.exclaim() = this + "!"
来源：http://dali.hammf.cn/Article/details/gtccqweama.html

[T10] Kotlin：默认参数
来源：http://dali.zhongyouzk.top/Article/details/gtckistjhm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.aizwys.cn/Article/details/gtriwqstbb.html

[T11] Kotlin：协程
来源：http://dali.cucudq.cn/Article/details/gthfzutsnw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.nanxuanxn.top/Article/details/gtlxchjvzh.html

[T12] Kotlin：解构声明
来源：http://dali.yanxiufei.cn/Article/details/gthysiedhp.html

val (a, b) = Pair(1, 2)
来源：http://dali.smart0.xyz/Article/details/gtngrlbvao.html

[T13] Kotlin：只读 Map
来源：http://dali.sxryk.cn/Article/details/gtjmpbjrau.html

val m = mapOf("a" to 1)
来源：http://dali.yj20258.top/Article/details/gtgathzuwx.html

[T14] Kotlin：循环
来源：http://dali.shzxlz.cn/Article/details/gtkxqwwzmm.html

for (i in 1..10) println(i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvdysrbmb.html

[T15] Kotlin：接口
来源：http://dali.jinqigufen.top/Article/details/gtxksaojkx.html

interface Shape { fun area(): Double }
来源：http://dali.iojbl.cn/Article/details/gtzcozhchf.html

[T16] Swift：Hello World
来源：http://dali.bjfxy.top/Article/details/gteeudlhdu.html

print("Hello")
来源：http://dali.xinyue.icu/Article/details/gtdmznmbwp.html

[T17] Swift：变量与常量
来源：http://dali.316326.xyz/Article/details/gtedzcrtxa.html

var a = 1;  let b = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtceffgqzt.html

[T18] Swift：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gtsytqnnej.html

"值: \(b)"
来源：http://dali.aizwys.cn/Article/details/gtkfdworrs.html

[T19] Swift：可选绑定
来源：http://dali.zhoulong.xyz/Article/details/gtoorloish.html

if let n = opt { print(n) }
来源：http://dali.yueranfly.top/Article/details/gtjftmjlxd.html

[T20] Swift：数组操作
来源：http://dali.0kj1m.cn/Article/details/gtwjflcxob.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jlsjyb.cn/Article/details/gtmhxfysda.html

[T21] Swift：遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkugwpaoc.html

for x in a { print(x) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtaffqlagk.html

[T22] Swift：字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsayhtwaj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gzhubu.top/Article/details/gtyratpman.html

[T23] Swift：函数
来源：http://dali.daria6918.cn/Article/details/gtjbsezefg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yanxiufei.cn/Article/details/gtfjlgmwau.html

[T24] Swift：闭包
来源：http://dali.yanxiufei.cn/Article/details/gtnnahyyhk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xylfe.cn/Article/details/gtqmjhtpzz.html

[T25] Swift：结构体
来源：http://dali.cashguo.top/Article/details/gtxkgkreeu.html

struct P { var x: Int }
来源：http://dali.yj202588.top/Article/details/gtelphpjlv.html

[T26] Swift：类与重写
来源：http://dali.sweek.top/Article/details/gtghhcujgj.html

class A: Base { override func f() {} }
来源：http://dali.quarkkingdee.top/Article/details/gtxyhvfzvr.html

[T27] Swift：错误处理
来源：http://dali.gogol.net.cn/Article/details/gtxkkvfoij.html

do { try f() } catch { print(error) }
来源：http://dali.jianghu66.top/Article/details/gtjhclxnbn.html

[T28] Swift：枚举
来源：http://dali.jianghu66.top/Article/details/gtbdvyqopq.html

enum Color { case red, green }
来源：http://dali.xylfe.cn/Article/details/gtsbjjmchw.html

[T29] Swift：guard 提前返回
来源：http://dali.cashguo.top/Article/details/gttxeamtdv.html

guard let x = opt else { return }
来源：http://dali.cashguo.top/Article/details/gtnzaoutbw.html

[T30] Swift：协议
来源：http://dali.fengsongda.top/Article/details/gtcyylwizr.html

protocol Shape { func area() -> Double }
来源：http://dali.jinqigfzy.top/Article/details/gtvvapyozp.html

[T31] Lua：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtwhthjlbk.html

print("Hello")
来源：http://dali.chenlongwang.top/Article/details/gtecgjbqib.html

[T32] Lua：局部变量
来源：http://dali.havefunace.top/Article/details/gtwvscbmfm.html

local a = 1
来源：http://dali.zhengqikj.top/Article/details/gtganxtpuw.html

[T33] Lua：表（数组）
来源：http://dali.chenlongwang.top/Article/details/gtdflcexsm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.gotoacloud.top/Article/details/gtidrqllfk.html

[T34] Lua：遍历表
来源：http://dali.ybcxt.top/Article/details/gtywydmtip.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cheryme.top/Article/details/gtqyaacavk.html

[T35] Lua：字典表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfavnhvys.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shuidangran.top/Article/details/gtvxmcgfib.html

[T36] Lua：函数
来源：http://dali.cheryme.top/Article/details/gtpmpbcqnv.html

function add(a, b) return a + b end
来源：http://dali.birdmap.top/Article/details/gtulikqbzz.html

[T37] Lua：字符串拼接
来源：http://dali.hammf.cn/Article/details/gticrbxdhz.html

"a" .. "b"
来源：http://dali.ivvv.top/Article/details/gthkwdhblu.html

[T38] Lua：条件
来源：http://dali.kuanghao11.cn/Article/details/gtttjfarqd.html

if x > 0 then print("正") end
来源：http://dali.gzhubu.top/Article/details/gtadjsdzpa.html

[T39] Lua：模式匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtktyfgpzv.html

string.find(s, "%d+")
来源：http://dali.gzhubu.top/Article/details/gtzdtdlotc.html

[T40] Lua：元表
来源：http://dali.hfpthk.cn/Article/details/gtltwmtxza.html

setmetatable({}, { __index = base })
来源：http://dali.nwbrower.top/Article/details/gtjaypxsin.html

[T41] Perl：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtovxiuiyw.html

print "Hello\n";
来源：http://dali.9152youxi.cn/Article/details/gteterpljl.html

[T42] Perl：变量类型
来源：http://dali.xuetiantiany.cn/Article/details/gtqvkygvup.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hnxiangtu.top/Article/details/gtupvuaami.html

[T43] Perl：字符串插值
来源：http://dali.haohaochexian.top/Article/details/gtljndhfyx.html

"值: $a"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtewzmsnyx.html

[T44] Perl：条件
来源：http://dali.feifeiyinyue.top/Article/details/gtohcruwrz.html

if ($a > 0) { print "正"; }
来源：http://dali.dianchejie.cn/Article/details/gtkccwdgbz.html

[T45] Perl：数组遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlpjemqfx.html

for my $x (@arr) { print $x; }
来源：http://dali.hammf.cn/Article/details/gtgmlixlbe.html

[T46] Perl：哈希操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmczwljnd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.nanxinkj.top/Article/details/gtmmmavdcx.html

[T47] Perl：正则捕获
来源：http://dali.tian-w.cn/Article/details/gtzlvrziph.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jqgfzy.top/Article/details/gtlrnbaalj.html

[T48] Perl：正则替换
来源：http://dali.daria6918.cn/Article/details/gtmghsnkjl.html

$s =~ s/old/new/g;
来源：http://dali.xuetiantiany.cn/Article/details/gtbqovedxx.html

[T49] Perl：函数
来源：http://dali.jiagoushi.top/Article/details/gtikbawgls.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gttqpqewlv.html

[T50] Perl：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gtaflbfgdy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yonumen.top/Article/details/gtcgwpbxay.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hysaishi.cn/Article/details/gtxindwfaf.html

[T51] Scala：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtoayphhun.html

println("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gtbjxmchkv.html

[T52] Scala：变量
来源：http://dali.shzxlz.cn/Article/details/gtasdnuwsw.html

val a = 1;  var b = 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtncvkbjer.html

[T53] Scala：字符串插值
来源：http://dali.tian-w.cn/Article/details/gtxfomcxsk.html

s"值: $b"
来源：http://dali.gogol.net.cn/Article/details/gtoaknozqd.html

[T54] Scala：集合映射
来源：http://dali.iojbl.cn/Article/details/gtjbnurmmy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cucudq.cn/Article/details/gthtcpcspt.html

[T55] Scala：集合过滤
来源：http://dali.hfpthk.cn/Article/details/gtlakonsoq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ivvv.top/Article/details/gtuplqjqpd.html

[T56] Scala：样例类
来源：http://dali.jinqigfzy.top/Article/details/gtknaaagew.html

case class User(name: String, age: Int)
来源：http://dali.meibo888.top/Article/details/gtvfvoskpd.html

[T57] Scala：模式匹配
来源：http://dali.ppjwa.cn/Article/details/gtvegncakm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jianghu66.top/Article/details/gthzswbqyo.html

[T58] Scala：函数定义
来源：http://dali.yj20258888.top/Article/details/gtjebbdtdl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cheryme.top/Article/details/gtjseqcehx.html

[T59] Scala：循环
来源：http://dali.gaohongyu789.top/Article/details/gtzpzxbqqr.html

for (i <- 1 to 10) println(i)
来源：http://dali.havefunace.top/Article/details/gtgoczgtah.html

[T60] Scala：折叠
来源：http://dali.hnxiangtu.top/Article/details/gtpboykewl.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.dianchejie.cn/Article/details/gthkgdfixs.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtuufrakca.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jiagoushi.top/Article/details/gtkpntubhz.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtmmogdbxl.html

[U01] Py：创建虚拟环境
来源：http://dali.shzxlz.cn/Article/details/gtuwhrzpmg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jianghu66.top/Article/details/gtnecydnyp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hnxiangtu.top/Article/details/gtsqccwpny.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jqgfzy.top/Article/details/gturmntcgp.html

[U03] Py：加载 .env 配置
来源：http://dali.hysaishi.cn/Article/details/gtirvdbvyt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hfpthk.cn/Article/details/gtljdefwth.html

[U04] Py：变量调试打印
来源：http://dali.yangfankeji.com/Article/details/gthfjrmgkh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.chenjidiqi.icu/Article/details/gthnuqosub.html

[U05] Py：列表去重且保序
来源：http://dali.iojbl.cn/Article/details/gtjqhacerr.html

list(dict.fromkeys(arr))
来源：http://dali.jyoumei.cn/Article/details/gtjbzfilhn.html

[U06] Py：合并两个字典
来源：http://dali.yj202588.top/Article/details/gtwxysowkq.html

{**a, **b}
来源：http://dali.jianghu66.top/Article/details/gttloxcdij.html

[U07] Py：反转字典键值
来源：http://dali.jyoumei.cn/Article/details/gtxracsicu.html

{v: k for k, v in d.items()}
来源：http://dali.0kj1m.cn/Article/details/gtioxknbui.html

[U08] Py：展平二维列表
来源：http://dali.hywenlv.cn/Article/details/gtcuficjwj.html

[y for x in nested for y in x]
来源：http://dali.hongshengwenyu.top/Article/details/gtjutjoebx.html

[U09] Py：字典取最大值的键
来源：http://dali.mhx1999.top/Article/details/gttmmsgrpy.html

max(d, key=d.get)
来源：http://dali.cashguo.top/Article/details/gtesxhamkv.html

[U10] Py：按值排序字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdkwmxohv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jianghu66.top/Article/details/gtpvvrlqco.html

[U11] Py：生成器表达式
来源：http://dali.zhengqikj.top/Article/details/gtbrnojwts.html

(x * 2 for x in arr)
来源：http://dali.yj20258888.top/Article/details/gtpjpwwfhg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xinyue.icu/Article/details/gtvepdwpud.html

Counter(arr).most_common(3)
来源：http://dali.316326.xyz/Article/details/gtvoibqfao.html

[U13] Py：固定长度队列
来源：http://dali.havefunace.top/Article/details/gtxtdjarid.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gtelhxspfd.html

[U14] Py：分组收集到列表
来源：http://dali.zhengqikj.top/Article/details/gtfnctzvge.html

defaultdict(list)
来源：http://dali.yanxiufei.cn/Article/details/gtzasbkeea.html

[U15] Py：高精度计时
来源：http://dali.quarkkingdee.top/Article/details/gtiyjktmhf.html

t = time.perf_counter()
来源：http://dali.shuidangran.top/Article/details/gtgqomymsn.html

[U16] Py：命令行参数解析
来源：http://dali.andypj.xyz/Article/details/gtsaiyvqcd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yueranfly.top/Article/details/gthbxetnuj.html

[U17] Py：初始化日志
来源：http://dali.gaohongyu789.top/Article/details/gtfbwyhirn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xylfe.cn/Article/details/gtnwrodnlh.html

[U18] Py：预编译正则
来源：http://dali.redwolf501.top/Article/details/gtgqytttpr.html

pat = re.compile(r"\d+")
来源：http://dali.pycfn.com/Article/details/gttfyccxvx.html

[U19] Py：正则替换带回调
来源：http://dali.yvedp.cn/Article/details/gtdxptlwpt.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ybcxt.top/Article/details/gtmtkzgkis.html

[U20] Py：缓存函数结果
来源：http://dali.shzxlz.cn/Article/details/gtwxdjnmvm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yvedp.cn/Article/details/gtgxpxatms.html

[U21] Py：自定义上下文管理器
来源：http://dali.chenjidiqi.icu/Article/details/gtgegihpeq.html

@contextlib.contextmanager
来源：http://dali.ydzc1.top/Article/details/gtqnqnfrpn.html

[U22] Py：矩阵转置
来源：http://dali.guannengcc.top/Article/details/gtseebtfix.html

list(zip(*m))
来源：http://dali.wangshuangyany.cn/Article/details/gtoiwctirb.html

[U23] Py：分块读取大文件
来源：http://dali.nanxuanxn.top/Article/details/gtmhjqvyno.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.fzhhl.top/Article/details/gtxslppixn.html

[U24] Py：路径操作
来源：http://dali.yanxiufei.cn/Article/details/gtvalhddvt.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.quarkkingdee.top/Article/details/gtvpeqjgns.html

[U25] Py：CSV 按字典读
来源：http://dali.xziqi.cn/Article/details/gtzyemonlm.html

csv.DictReader(f)
来源：http://dali.dashuyun.cn/Article/details/gticliodrl.html

[U26] Py：并发下载
来源：http://dali.tian-w.cn/Article/details/gtapsijlph.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yonumen.top/Article/details/gtwmoodddq.html

[U27] Py：异步 HTTP
来源：http://dali.guannengcc.top/Article/details/gtpbmaxbhu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhengqikj.top/Article/details/gttsvdvucv.html

[U28] Py：类型别名
来源：http://dali.jlsjyb.cn/Article/details/gtdlxpiinm.html

UserId = int
来源：http://dali.haohaochexian.top/Article/details/gtebizmmjf.html

[U29] Py：属性校验
来源：http://dali.cheryme.top/Article/details/gtjiavjxrc.html

@property 与 @x.setter 配合
来源：http://dali.pycfn.com/Article/details/gtkxcvngue.html

[U30] Py：数据类
来源：http://dali.havefunace.top/Article/details/gtdfvjeeen.html

@dataclass(slots=True)
来源：http://dali.dashuyun.cn/Article/details/gthacgnhss.html

[U31] Py：单测
来源：http://dali.yj20258.top/Article/details/gtuxkzuthd.html

python -m pytest -q
来源：http://dali.cqqwz.cn/Article/details/gtkdxqnbcj.html

[U32] Py：代码格式化
来源：http://dali.yuanzhike.top/Article/details/gtfnkjtrpe.html

ruff format . && ruff check --fix .
来源：http://dali.wangshuangyany.cn/Article/details/gtioxuhkgg.html

[U33] Py：打包发布
来源：http://dali.aizwys.cn/Article/details/gtafczqukl.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shzxlz.cn/Article/details/gtkblwatgk.html

[U34] Py：判断编码
来源：http://dali.bjfxy.top/Article/details/gtkgwpgsqk.html

chardet.detect(raw)
来源：http://dali.shangyingyoupin.top/Article/details/gtxjzomwqg.html

[U35] Py：发送邮件
来源：http://dali.yangfankeji.com/Article/details/gtouoqkdzy.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.guannengcc.top/Article/details/gtuxnxwlob.html

[U36] Py：定时任务
来源：http://dali.nanxuanxn.top/Article/details/gtgmphrpmm.html

schedule.every(10).minutes.do(job)
来源：http://dali.jlsjyb.cn/Article/details/gtbyxmdsdv.html

[U37] Py：读写 Excel
来源：http://dali.xylfe.cn/Article/details/gtkgnqpurd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yj20258.top/Article/details/gtbgkkvcko.html

[U38] Py：获取脚本所在目录
来源：http://dali.meibo888.top/Article/details/gtxtopscdt.html

Path(__file__).resolve().parent
来源：http://dali.cdnleiting.top/Article/details/gtknjoubvx.html

[U39] Py：判断是否在交互环境
来源：http://dali.chenjidiqi.icu/Article/details/gtjahfywqr.html

sys.stdout.isatty()
来源：http://dali.guannengcc.top/Article/details/gtigwdboon.html

[U40] Py：打印到标准错误
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtewvgmfia.html

print("err", file=sys.stderr)
来源：http://dali.c1oappe.top/Article/details/gttfpuiaaz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.havefunace.top/Article/details/gtmlatwevv.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ehwqpu.com/Article/details/gthvgmmfkj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.chenzaomai.com/Article/details/gtxeumuhkr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.ehwqpu.com/Article/details/gtbyggiccc.html

[U43] PHP：声明命名空间
来源：http://dali.yongpay.top/Article/details/gtfhzrvxrc.html

namespace App\Http;
来源：http://dali.aizwys.cn/Article/details/gtneixnvqw.html

[U44] PHP：开启严格类型
来源：http://dali.yangfankeji.com/Article/details/gtvlrkwzpd.html

declare(strict_types=1);
来源：http://dali.ehwqpu.com/Article/details/gtdldapcok.html

[U45] PHP：类型声明与返回类型
来源：http://dali.kuanghao11.cn/Article/details/gtfgxcgfml.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pycfn.com/Article/details/gtpbzxahbl.html

[U46] PHP：可空类型
来源：http://dali.meibo888.top/Article/details/gtbkfxzmee.html

?string $name = null
来源：http://dali.feifeiyinyue.top/Article/details/gtayspnhlh.html

[U47] PHP：联合类型
来源：http://dali.jqgfzy.top/Article/details/gtprqpssaf.html

int|string $id
来源：http://dali.zycfv.cn/Article/details/gtcqntwwal.html

[U48] PHP：纯枚举
来源：http://dali.zhixingplan.top/Article/details/gthdoonvtr.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtzwqkekjr.html

[U49] PHP：只读属性
来源：http://dali.zdqjudy.top/Article/details/gtrybuzrhx.html

public readonly string $name
来源：http://dali.zhongyouzk.top/Article/details/gtekpqndwv.html

[U50] PHP：构造器属性提升
来源：http://dali.xuetiantiany.cn/Article/details/gtybxuvjmc.html

public function __construct(private int $id) {}
来源：http://dali.daria6918.cn/Article/details/gtedxmglnf.html

[U51] PHP：数组解构
来源：http://dali.pycfn.com/Article/details/gtlvepccug.html

[$a, $b] = $arr;
来源：http://dali.zhixingplan.top/Article/details/gtzhizgsod.html

[U52] PHP：箭头函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxehmmlha.html

$double = fn($x) => $x * 2;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrtqiwbej.html

[U53] PHP：空合并运算符
来源：http://dali.xuetiantiany.cn/Article/details/gtplvpuujb.html

$v = $a ?? $b ?? "default";
来源：http://dali.xylfe.cn/Article/details/gtprglxqtd.html

[U54] PHP：空安全调用
来源：http://dali.pengpengdd.cyou/Article/details/gtyaixzmlx.html

$obj?->method()
来源：http://dali.tianlin.xyz/Article/details/gtsmcymmka.html

[U55] PHP：match 表达式
来源：http://dali.ppjwa.cn/Article/details/gtrngfkqmc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.mhx1999.top/Article/details/gtasqnyuqg.html

[U56] PHP：命名参数
来源：http://dali.zhengqikj.top/Article/details/gttnzqiocb.html

f(a: 1, b: 2)
来源：http://dali.chenzaomai.com/Article/details/gtjatqrpbu.html

[U57] PHP：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gtxdjeqabr.html

"值: {$a}"
来源：http://dali.tian-w.cn/Article/details/gtqdpdetdz.html

[U58] PHP：数组三件套
来源：http://dali.svipenyu.cn/Article/details/gtoeqarrmx.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.aibaodan.cn/Article/details/gtxdvsnrxy.html

[U59] PHP：自定义排序
来源：http://dali.sysykeji.top/Article/details/gtzknnzgzg.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ehwqpu.com/Article/details/gtqbfrxzug.html

[U60] PHP：JSON 编解码
来源：http://dali.pycfn.com/Article/details/gtvfsyhfat.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.quarkkingdee.top/Article/details/gtgbohdejh.html

[U61] PHP：正则
来源：http://dali.dashuyun.cn/Article/details/gtwvbshwsx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.fzhhl.top/Article/details/gtihpumcbq.html

[U62] PHP：日期对象
来源：http://dali.zhoulong.xyz/Article/details/gtazwvuulj.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zycfv.cn/Article/details/gtnqajyumr.html

[U63] PHP：文件读写
来源：http://dali.xylfe.cn/Article/details/gttkzjqnpu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.chenjidiqi.icu/Article/details/gtntgnougj.html

[U64] PHP：目录遍历
来源：http://dali.fengsongda.top/Article/details/gtkfqkjoqp.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtetzxywdp.html


<!-- 参考信息 -->