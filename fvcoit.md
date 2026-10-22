代发 wailian999

#include <iostream>
来源：http://dali.guannengcc.top/Article/details/gtjdnewxim.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtwnyczvxe.html

[S32] C++：字符串
来源：http://dali.hammf.cn/Article/details/gtwicrxkdf.html

std::string s = "hi";  s += "!";
来源：http://dali.wangshuangyany.cn/Article/details/gtohhvkese.html

[S33] C++：vector 增删
来源：http://dali.daria6918.cn/Article/details/gtewabzzzc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.haohaochexian.top/Article/details/gtbijgfbcw.html

[S34] C++：遍历 vector
来源：http://dali.yj202588.top/Article/details/gtotdkfyvb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cheryme.top/Article/details/gtryfomgix.html

[S35] C++：map
来源：http://dali.zdqjudy.top/Article/details/gtjyirswwe.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtmtblcwer.html

[S36] C++：unordered_map
来源：http://dali.chenlongwang.top/Article/details/gtnwgrevin.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fzhhl.top/Article/details/gtlxqgakfw.html

[S37] C++：set
来源：http://dali.hongshengwenyu.top/Article/details/gtblmrnfkw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.aibaodan.cn/Article/details/gtaflurolj.html

[S38] C++：排序
来源：http://dali.tianlin.xyz/Article/details/gtpapqctwd.html

std::sort(v.begin(), v.end());
来源：http://dali.hammf.cn/Article/details/gtzctcofpk.html

[S39] C++：自定义比较器排序
来源：http://dali.ivvv.top/Article/details/gtiaqntnai.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgfhzgss.html

[S40] C++：查找元素
来源：http://dali.gaohongyu789.top/Article/details/gtvrwoztok.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zycfv.cn/Article/details/gtuyrfwhxb.html

[S41] C++：类与构造函数
来源：http://dali.shzxlz.cn/Article/details/gttwjhtlju.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gtbhotafel.html

[S42] C++：继承与虚函数
来源：http://dali.xuetiantiany.cn/Article/details/gtiyqwmjua.html

class B : public Base { public: void f() override {} };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkfngckcs.html

[S43] C++：智能指针
来源：http://dali.cucudq.cn/Article/details/gtaxpbtvcj.html

auto p = std::make_unique<int>(5);
来源：http://dali.pengpengdd.cyou/Article/details/gtlrnuqsdj.html

[S44] C++：引用传参
来源：http://dali.dashuyun.cn/Article/details/gtjimgyggz.html

void inc(int &x) { ++x; }
来源：http://dali.chenjidiqi.icu/Article/details/gtcujarfet.html

[S45] C++：lambda
来源：http://dali.cqqwz.cn/Article/details/gtgkjtnkki.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.316326.xyz/Article/details/gtotavrtkv.html

[S46] C++：函数模板
来源：http://dali.kuanghao11.cn/Article/details/gtbypchltp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jqgfzy.top/Article/details/gtpoxhtmmz.html

[S47] C++：结构化绑定遍历
来源：http://dali.hnxiangtu.top/Article/details/gtkyjawbbr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xuetiantiany.cn/Article/details/gtoaibxfyl.html

[S48] C++：逐行读文件
来源：http://dali.birdmap.top/Article/details/gtlutkfwmn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenjidiqi.icu/Article/details/gtwivefqxa.html

while (std::getline(in, line)) { }
来源：http://dali.jqgufenzy.top/Article/details/gtzndaocaw.html

[S49] C++：写文件
来源：http://dali.chenjidiqi.icu/Article/details/gtrnutmcft.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hammf.cn/Article/details/gtrnwqymza.html

[S50] C++：格式化数字
来源：http://dali.yanxiufei.cn/Article/details/gtebhexfwq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gtvrcbzehx.html

[S51] C++：显式类型转换
来源：http://dali.daxiang520.top/Article/details/gtaqcpcctv.html

static_cast<double>(a) / b
来源：http://dali.bjfxy.top/Article/details/gtligllayc.html

[S52] C++：const 与 noexcept
来源：http://dali.cashguo.top/Article/details/gtewgopabn.html

int size() const noexcept { return n_; }
来源：http://dali.gzhubu.top/Article/details/gtfkdibkvo.html

[S53] C++：移动语义
来源：http://dali.ivvv.top/Article/details/gtnwjicaja.html

std::vector<int> w = std::move(v);
来源：http://dali.aizwys.cn/Article/details/gtzwavccey.html

[S54] C++：异常处理
来源：http://dali.316326.xyz/Article/details/gtqxnuffij.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zdqjudy.top/Article/details/gtgtxmitkb.html

[S55] C++：结构化绑定
来源：http://dali.gogol.net.cn/Article/details/gttbfdswro.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.andypj.xyz/Article/details/gtzryggudj.html

[S56] C++：optional
来源：http://dali.c1oappe.top/Article/details/gtiltzmjvp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.fengsongda.top/Article/details/gttbpkdquz.html

[S57] C++：编译期常量
来源：http://dali.tanke756.top/Article/details/gtxrakdaqm.html

constexpr int N = 10;
来源：http://dali.chenzaomai.com/Article/details/gtniynkvse.html

[S58] C++：命名空间
来源：http://dali.tianlin.xyz/Article/details/gtrmgmxoot.html

namespace ns { int f() { return 1; } }
来源：http://dali.0kj1m.cn/Article/details/gtbjgaeprp.html

[S59] C++：静态断言
来源：http://dali.shuidangran.top/Article/details/gtenywbrcf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hammf.cn/Article/details/gtobhvefam.html

[S60] C++：遍历并删除元素
来源：http://dali.cdnleiting.top/Article/details/gttjbcotva.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ivvv.top/Article/details/gtctyachej.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtnrmjszwf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zycfv.cn/Article/details/gtpzrmdasd.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gthnlybsyg.html

[T01] Kotlin：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtenewanwz.html

println("Hello")
来源：http://dali.ehwqpu.com/Article/details/gtcyynwbvx.html

[T02] Kotlin：变量
来源：http://dali.aizwys.cn/Article/details/gtsrtfcnol.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sysykeji.top/Article/details/gtplhmsocq.html

[T03] Kotlin：字符串模板
来源：http://dali.nwbrower.top/Article/details/gtznikhjjx.html

"值: $b"
来源：http://dali.yanxiufei.cn/Article/details/gtlozizsya.html

[T04] Kotlin：空安全
来源：http://dali.aibaodan.cn/Article/details/gtubgvfjvo.html

val n: String? = null;  n?.length
来源：http://dali.zhixingplan.top/Article/details/gtxutbovfm.html

[T05] Kotlin：when 表达式
来源：http://dali.zhiwuduotai.top/Article/details/gttmqdrzqq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xuanzx.com/Article/details/gtspqcgloj.html

[T06] Kotlin：集合映射
来源：http://dali.wangshuangyany.cn/Article/details/gtzuhfyacf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hnxiangtu.top/Article/details/gthknfzcos.html

[T07] Kotlin：集合过滤
来源：http://dali.nanxuanxn.top/Article/details/gtzaovwzve.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhoulong.xyz/Article/details/gtbkpdjwzv.html

[T08] Kotlin：数据类
来源：http://dali.pycfn.com/Article/details/gtibgywerw.html

data class User(val name: String, val age: Int)
来源：http://dali.tianlin.xyz/Article/details/gtiujlrrxn.html

[T09] Kotlin：扩展函数
来源：http://dali.dashuyun.cn/Article/details/gtiogvuzvq.html

fun String.exclaim() = this + "!"
来源：http://dali.snrcjt.cn/Article/details/gtcqpnvoyj.html

[T10] Kotlin：默认参数
来源：http://dali.cdnleiting.top/Article/details/gtpfwlogpy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.fzhhl.top/Article/details/gtpnlodwki.html

[T11] Kotlin：协程
来源：http://dali.nanxuanxn.top/Article/details/gtgimrgims.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.fzhhl.top/Article/details/gtjrtbormz.html

[T12] Kotlin：解构声明
来源：http://dali.havefunace.top/Article/details/gtvyfmzstb.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtasbcifhb.html

[T13] Kotlin：只读 Map
来源：http://dali.guannengcc.top/Article/details/gthkkzdhkt.html

val m = mapOf("a" to 1)
来源：http://dali.nwbrower.top/Article/details/gtdunvniyt.html

[T14] Kotlin：循环
来源：http://dali.yueranfly.top/Article/details/gtyjxfkqqw.html

for (i in 1..10) println(i)
来源：http://dali.gotoacloud.top/Article/details/gtddqwkzhm.html

[T15] Kotlin：接口
来源：http://dali.smart0.xyz/Article/details/gtzllvqzyv.html

interface Shape { fun area(): Double }
来源：http://dali.yvedp.cn/Article/details/gtrjpqyxtk.html

[T16] Swift：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtwsrepifl.html

print("Hello")
来源：http://dali.mhx1999.top/Article/details/gtvvujseag.html

[T17] Swift：变量与常量
来源：http://dali.yanxiufei.cn/Article/details/gtzlgvdfyh.html

var a = 1;  let b = 2
来源：http://dali.tianlin.xyz/Article/details/gtmhklxfay.html

[T18] Swift：字符串插值
来源：http://dali.bjfxy.top/Article/details/gtoweudwit.html

"值: \(b)"
来源：http://dali.mhx1999.top/Article/details/gtyxqtymcv.html

[T19] Swift：可选绑定
来源：http://dali.gzhubu.top/Article/details/gtuiovrxni.html

if let n = opt { print(n) }
来源：http://dali.jqgfzy.top/Article/details/gtakslbztr.html

[T20] Swift：数组操作
来源：http://dali.jyoumei.cn/Article/details/gthyxazfge.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.svipenyu.cn/Article/details/gtidijjepq.html

[T21] Swift：遍历
来源：http://dali.cashguo.top/Article/details/gtygvemzdy.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gtpyconrpn.html

[T22] Swift：字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqlutcjys.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ybcxt.top/Article/details/gtonypgfvw.html

[T23] Swift：函数
来源：http://dali.yj20258888.top/Article/details/gtdvjqgswj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgkjpnkex.html

[T24] Swift：闭包
来源：http://dali.jianghu66.top/Article/details/gtkrnkmqre.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.fzhhl.top/Article/details/gtcrlocqha.html

[T25] Swift：结构体
来源：http://dali.haohaochexian.top/Article/details/gtoqmecawb.html

struct P { var x: Int }
来源：http://dali.yuanzhike.top/Article/details/gtrekztrgi.html

[T26] Swift：类与重写
来源：http://dali.yueranfly.top/Article/details/gtrrvjvpbj.html

class A: Base { override func f() {} }
来源：http://dali.9152youxi.cn/Article/details/gtwnfwgisl.html

[T27] Swift：错误处理
来源：http://dali.guowangkeji.top/Article/details/gtnziinlcx.html

do { try f() } catch { print(error) }
来源：http://dali.yvedp.cn/Article/details/gtoozjganu.html

[T28] Swift：枚举
来源：http://dali.vqdsnc.cn/Article/details/gtbpureila.html

enum Color { case red, green }
来源：http://dali.aibaodan.cn/Article/details/gtnvdtoull.html

[T29] Swift：guard 提前返回
来源：http://dali.ybcxt.top/Article/details/gtvslejtkd.html

guard let x = opt else { return }
来源：http://dali.yueranfly.top/Article/details/gtyidhrxxv.html

[T30] Swift：协议
来源：http://dali.shuidangran.top/Article/details/gtzwnovspt.html

protocol Shape { func area() -> Double }
来源：http://dali.yuanzhike.top/Article/details/gtvcetsbid.html

[T31] Lua：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtvzwzzdtv.html

print("Hello")
来源：http://dali.c1oappe.top/Article/details/gtawzwdbpb.html

[T32] Lua：局部变量
来源：http://dali.hywenlv.cn/Article/details/gtouwhiylt.html

local a = 1
来源：http://dali.nanxinkj.top/Article/details/gtfmqtumwu.html

[T33] Lua：表（数组）
来源：http://dali.jyoumei.cn/Article/details/gtmdfxvhor.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jqgufenzy.top/Article/details/gthuawuwry.html

[T34] Lua：遍历表
来源：http://dali.quarkkingdee.top/Article/details/gtoaoelefh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shuidangran.top/Article/details/gthukebzxy.html

[T35] Lua：字典表
来源：http://dali.jiagoushi.top/Article/details/gtyuuoufkm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtunoxtuhe.html

[T36] Lua：函数
来源：http://dali.chenzaomai.com/Article/details/gtlzmmzxmh.html

function add(a, b) return a + b end
来源：http://dali.hfpthk.cn/Article/details/gtbaujcote.html

[T37] Lua：字符串拼接
来源：http://dali.ybcxt.top/Article/details/gtdrmrdcrt.html

"a" .. "b"
来源：http://dali.zhongyouzk.top/Article/details/gtogrdsiba.html

[T38] Lua：条件
来源：http://dali.jlsjyb.cn/Article/details/gtdbpjlvjf.html

if x > 0 then print("正") end
来源：http://dali.chenzaomai.com/Article/details/gtqudezjqn.html

[T39] Lua：模式匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuumguzim.html

string.find(s, "%d+")
来源：http://dali.cdnleiting.top/Article/details/gtdivaphsi.html

[T40] Lua：元表
来源：http://dali.jqgfzy.top/Article/details/gtgiodthkj.html

setmetatable({}, { __index = base })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttdqqegiu.html

[T41] Perl：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtvdnrasxu.html

print "Hello\n";
来源：http://dali.yj202588.top/Article/details/gtnrphmhrx.html

[T42] Perl：变量类型
来源：http://dali.guowangkeji.top/Article/details/gthksyireh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhoulong.xyz/Article/details/gtbexdqmkb.html

[T43] Perl：字符串插值
来源：http://dali.jinqigufen.top/Article/details/gthwvovgcz.html

"值: $a"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdsvinqbw.html

[T44] Perl：条件
来源：http://dali.xuetiantiany.cn/Article/details/gtyansqdki.html

if ($a > 0) { print "正"; }
来源：http://dali.jianghu66.top/Article/details/gtendoxccn.html

[T45] Perl：数组遍历
来源：http://dali.c1oappe.top/Article/details/gtwtdhztzy.html

for my $x (@arr) { print $x; }
来源：http://dali.jinqigfzy.top/Article/details/gtwxblwavl.html

[T46] Perl：哈希操作
来源：http://dali.ehwqpu.com/Article/details/gtzultxbew.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdlcmatqu.html

[T47] Perl：正则捕获
来源：http://dali.jinqigfzy.top/Article/details/gtkfvkfuwm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.c1oappe.top/Article/details/gtdgfleghp.html

[T48] Perl：正则替换
来源：http://dali.zhiwuduotai.top/Article/details/gtgdkeptnj.html

$s =~ s/old/new/g;
来源：http://dali.yj20258888.top/Article/details/gtrpveuaxb.html

[T49] Perl：函数
来源：http://dali.hnxiangtu.top/Article/details/gtstxquwvc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shuidangran.top/Article/details/gtuxkrijcr.html

[T50] Perl：逐行读文件
来源：http://dali.ivvv.top/Article/details/gtnfwoomvd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tianlin.xyz/Article/details/gtmphegfal.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ybcxt.top/Article/details/gtpxdsmbrs.html

[T51] Scala：Hello World
来源：http://dali.daxiang520.top/Article/details/gthbelofqt.html

println("Hello")
来源：http://dali.yueranfly.top/Article/details/gtagcrbvsa.html

[T52] Scala：变量
来源：http://dali.fzhhl.top/Article/details/gtdvrldjlh.html

val a = 1;  var b = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gthaiclnxt.html

[T53] Scala：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gtnhsjppgg.html

s"值: $b"
来源：http://dali.iojbl.cn/Article/details/gttcnvwlhj.html

[T54] Scala：集合映射
来源：http://dali.quarkkingdee.top/Article/details/gtpcsflsjq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtfyxfnmii.html

[T55] Scala：集合过滤
来源：http://dali.sxryk.cn/Article/details/gtoboddnzi.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jiagoushi.top/Article/details/gtvcsspjzm.html

[T56] Scala：样例类
来源：http://dali.yanxiufei.cn/Article/details/gtxwcwxaaw.html

case class User(name: String, age: Int)
来源：http://dali.guannengcc.top/Article/details/gtnouxbkbx.html

[T57] Scala：模式匹配
来源：http://dali.hnxiangtu.top/Article/details/gtfnmbtyui.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gotoacloud.top/Article/details/gtgtsukvfq.html

[T58] Scala：函数定义
来源：http://dali.yangfankeji.com/Article/details/gtpvfrpsyt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.bjfxy.top/Article/details/gtvnxeksdc.html

[T59] Scala：循环
来源：http://dali.jianghu66.top/Article/details/gtnvjtbusl.html

for (i <- 1 to 10) println(i)
来源：http://dali.andypj.xyz/Article/details/gtbgfoocpq.html

[T60] Scala：折叠
来源：http://dali.hysaishi.cn/Article/details/gtlkvvgqif.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xylfe.cn/Article/details/gtirnzveba.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtxmtcwxyz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtzcjksluj.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gttrsrokwi.html

[U01] Py：创建虚拟环境
来源：http://dali.ppjwa.cn/Article/details/gtjhzbftbz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.nanxuanxn.top/Article/details/gtlbqxalqd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.redwolf501.top/Article/details/gtotbtpmjp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpcwcjseb.html

[U03] Py：加载 .env 配置
来源：http://dali.gogol.net.cn/Article/details/gtwzvsbwuv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.dianchejie.cn/Article/details/gtiphlxhvj.html

[U04] Py：变量调试打印
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrjgvdsqy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.tanke756.top/Article/details/gtpvfnlyho.html

[U05] Py：列表去重且保序
来源：http://dali.9152youxi.cn/Article/details/gtdpraycri.html

list(dict.fromkeys(arr))
来源：http://dali.gotoacloud.top/Article/details/gtmvukkhke.html

[U06] Py：合并两个字典
来源：http://dali.jqgufenzy.top/Article/details/gtejehovkb.html

{**a, **b}
来源：http://dali.yj20258.top/Article/details/gtmylawjuc.html

[U07] Py：反转字典键值
来源：http://dali.tianlin.xyz/Article/details/gtpzdgmnfh.html

{v: k for k, v in d.items()}
来源：http://dali.gzhubu.top/Article/details/gtfioamsei.html

[U08] Py：展平二维列表
来源：http://dali.sysykeji.top/Article/details/gtphrceeqy.html

[y for x in nested for y in x]
来源：http://dali.316326.xyz/Article/details/gtbjzdogaj.html

[U09] Py：字典取最大值的键
来源：http://dali.tian-w.cn/Article/details/gttabiialj.html

max(d, key=d.get)
来源：http://dali.jianghu66.top/Article/details/gtodcmtpud.html

[U10] Py：按值排序字典
来源：http://dali.redwolf501.top/Article/details/gtnesdhqzo.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.haohaochexian.top/Article/details/gtfjhswclo.html

[U11] Py：生成器表达式
来源：http://dali.smart0.xyz/Article/details/gttergjdfg.html

(x * 2 for x in arr)
来源：http://dali.guowangkeji.top/Article/details/gtpinenjiz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yangfankeji.com/Article/details/gtfbtduelk.html

Counter(arr).most_common(3)
来源：http://dali.yj202588.top/Article/details/gtuhqicurg.html

[U13] Py：固定长度队列
来源：http://dali.bjfxy.top/Article/details/gtlzzyecuo.html

deque(maxlen=10)
来源：http://dali.cheryme.top/Article/details/gthrfqvwqa.html

[U14] Py：分组收集到列表
来源：http://dali.yuanzhike.top/Article/details/gtxawauvzl.html

defaultdict(list)
来源：http://dali.zhixingplan.top/Article/details/gtnvohlpzx.html

[U15] Py：高精度计时
来源：http://dali.havefunace.top/Article/details/gtytqjelfn.html

t = time.perf_counter()
来源：http://dali.gogol.net.cn/Article/details/gtsmmlvhtw.html

[U16] Py：命令行参数解析
来源：http://dali.meibo888.top/Article/details/gtqqosdczl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.vqdsnc.cn/Article/details/gtyxwwzztc.html

[U17] Py：初始化日志
来源：http://dali.ybcxt.top/Article/details/gtxltmukxn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.kuanghao11.cn/Article/details/gtmfeoxjpf.html

[U18] Py：预编译正则
来源：http://dali.pengpengdd.cyou/Article/details/gtnnflrmgw.html

pat = re.compile(r"\d+")
来源：http://dali.ehwqpu.com/Article/details/gtybetgzmf.html

[U19] Py：正则替换带回调
来源：http://dali.chenlongwang.top/Article/details/gtdwuiusep.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.feifeiyinyue.top/Article/details/gthkitusgi.html

[U20] Py：缓存函数结果
来源：http://dali.ivvv.top/Article/details/gtzoqnrxsv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.pycfn.com/Article/details/gtnmfptxxo.html

[U21] Py：自定义上下文管理器
来源：http://dali.cqqwz.cn/Article/details/gttyzojsas.html

@contextlib.contextmanager
来源：http://dali.hfpthk.cn/Article/details/gtafogdyun.html

[U22] Py：矩阵转置
来源：http://dali.xziqi.cn/Article/details/gtknynuxrr.html

list(zip(*m))
来源：http://dali.zhengqikj.top/Article/details/gtsgmaxgyo.html

[U23] Py：分块读取大文件
来源：http://dali.xuanzx.com/Article/details/gteomidmoh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xinyue.icu/Article/details/gtvuttpqcz.html

[U24] Py：路径操作
来源：http://dali.shanyushiyangtech.top/Article/details/gtbqdvfhtf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtbhyzcqrd.html

[U25] Py：CSV 按字典读
来源：http://dali.snrcjt.cn/Article/details/gtbmypkxis.html

csv.DictReader(f)
来源：http://dali.fengsongda.top/Article/details/gtavknnbcy.html

[U26] Py：并发下载
来源：http://dali.haohaochexian.top/Article/details/gtvinsovno.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.tanke756.top/Article/details/gtehbmuhas.html

[U27] Py：异步 HTTP
来源：http://dali.feifeiyinyue.top/Article/details/gtcusrgnvw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.chenlongwang.top/Article/details/gtqdbjovmi.html

[U28] Py：类型别名
来源：http://dali.tianlin.xyz/Article/details/gtfzximwff.html

UserId = int
来源：http://dali.redwolf501.top/Article/details/gturjnfvov.html

[U29] Py：属性校验
来源：http://dali.svipenyu.cn/Article/details/gtedlycyla.html

@property 与 @x.setter 配合
来源：http://dali.yongpay.top/Article/details/gtyaaoxprj.html

[U30] Py：数据类
来源：http://dali.yongpay.top/Article/details/gtjkvpeiaf.html

@dataclass(slots=True)
来源：http://dali.yonumen.top/Article/details/gtxzcufomj.html

[U31] Py：单测
来源：http://dali.hfpthk.cn/Article/details/gtoatyjace.html

python -m pytest -q
来源：http://dali.hnqzz.top/Article/details/gttmjdjndl.html

[U32] Py：代码格式化
来源：http://dali.9152youxi.cn/Article/details/gtskglwnke.html

ruff format . && ruff check --fix .
来源：http://dali.ehwqpu.com/Article/details/gtawwyezua.html

[U33] Py：打包发布
来源：http://dali.zhiwuduotai.top/Article/details/gtrjfbrufi.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jianghu66.top/Article/details/gtrkvyqaoc.html

[U34] Py：判断编码
来源：http://dali.birdmap.top/Article/details/gtryuspbwn.html

chardet.detect(raw)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkwstmxos.html

[U35] Py：发送邮件
来源：http://dali.andypj.xyz/Article/details/gttxyxjshu.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.kuanghao11.cn/Article/details/gtvxgmhiaf.html

[U36] Py：定时任务
来源：http://dali.xylfe.cn/Article/details/gtudxajqne.html

schedule.every(10).minutes.do(job)
来源：http://dali.cashguo.top/Article/details/gtumxmcuwg.html

[U37] Py：读写 Excel
来源：http://dali.andypj.xyz/Article/details/gtaicruiks.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jqgfzy.top/Article/details/gthbbcswds.html

[U38] Py：获取脚本所在目录
来源：http://dali.sufxvd.cn/Article/details/gtwkghecyx.html

Path(__file__).resolve().parent
来源：http://dali.shanyushiyangtech.top/Article/details/gtukfiuawp.html

[U39] Py：判断是否在交互环境
来源：http://dali.sweek.top/Article/details/gtlxrdxmps.html

sys.stdout.isatty()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxwmfnwae.html

[U40] Py：打印到标准错误
来源：http://dali.sxryk.cn/Article/details/gtztgiljob.html

print("err", file=sys.stderr)
来源：http://dali.yuanzhike.top/Article/details/gtlkajgxim.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.shuidangran.top/Article/details/gtwywhvkay.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.andypj.xyz/Article/details/gtiiqwmabd.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ppjwa.cn/Article/details/gtfkgdqvyq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xuanzx.com/Article/details/gtfayvesgm.html

[U43] PHP：声明命名空间
来源：http://dali.chenjidiqi.icu/Article/details/gtudycjqyy.html

namespace App\Http;
来源：http://dali.cdnleiting.top/Article/details/gtnnrqltqx.html

[U44] PHP：开启严格类型
来源：http://dali.gotoacloud.top/Article/details/gtsruzqpvj.html

declare(strict_types=1);
来源：http://dali.shzxlz.cn/Article/details/gtjqdbodfc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.nwbrower.top/Article/details/gtupvmuldy.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj202588.top/Article/details/gtewvzpkcm.html

[U46] PHP：可空类型
来源：http://dali.jinqigufen.top/Article/details/gtbaavcrgm.html

?string $name = null
来源：http://dali.guannengcc.top/Article/details/gthqphrrky.html

[U47] PHP：联合类型
来源：http://dali.gzhubu.top/Article/details/gtkirvwpuu.html

int|string $id
来源：http://dali.andypj.xyz/Article/details/gtravuibvr.html

[U48] PHP：纯枚举
来源：http://dali.gzhubu.top/Article/details/gttmqsrsrg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.pycfn.com/Article/details/gtoybwrakt.html

[U49] PHP：只读属性
来源：http://dali.hysaishi.cn/Article/details/gtjfgvciok.html

public readonly string $name
来源：http://dali.c1oappe.top/Article/details/gtjjodqili.html

[U50] PHP：构造器属性提升
来源：http://dali.gogol.net.cn/Article/details/gtuvanscqu.html

public function __construct(private int $id) {}
来源：http://dali.jlsjyb.cn/Article/details/gtvbvefifg.html

[U51] PHP：数组解构
来源：http://dali.tanke756.top/Article/details/gttnvxatir.html

[$a, $b] = $arr;
来源：http://dali.ppjwa.cn/Article/details/gtzkkqjksp.html

[U52] PHP：箭头函数
来源：http://dali.pengpengdd.cyou/Article/details/gtpgdxrsjt.html

$double = fn($x) => $x * 2;
来源：http://dali.zycfv.cn/Article/details/gtfsagdjbl.html

[U53] PHP：空合并运算符
来源：http://dali.ydzc1.top/Article/details/gtptozceyk.html

$v = $a ?? $b ?? "default";
来源：http://dali.zdqjudy.top/Article/details/gtpaztjefd.html

[U54] PHP：空安全调用
来源：http://dali.316326.xyz/Article/details/gtonwnbeoc.html

$obj?->method()
来源：http://dali.daria6918.cn/Article/details/gtishevpdk.html

[U55] PHP：match 表达式
来源：http://dali.hfpthk.cn/Article/details/gtpommgyku.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.aibaodan.cn/Article/details/gteextwavv.html

[U56] PHP：命名参数
来源：http://dali.jianghu66.top/Article/details/gtgehyrsem.html

f(a: 1, b: 2)
来源：http://dali.wangdashe.top/Article/details/gtvzlxdffe.html


<!-- 参考信息 -->