代发 wailian999

memset(a, 0, sizeof a);
来源：http://dali.pengpengdd.cyou/Article/details/gtchcrsgsz.html

[S27] C：定义常量
来源：http://dali.zhongyouzk.top/Article/details/gtlfmrxccr.html

const double PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gtwhjvxwyx.html

[S28] C：静态变量
来源：http://dali.sweek.top/Article/details/gtfbxgzmms.html

static int counter = 0;
来源：http://dali.haohaochexian.top/Article/details/gtwtdsepfl.html

[S29] C：变参函数
来源：http://dali.tian-w.cn/Article/details/gtcdlefime.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.haohaochexian.top/Article/details/gthzrrviyw.html

[S30] C：头文件保护
来源：http://dali.cashguo.top/Article/details/gtgzivdzxf.html

#ifndef X_H
来源：http://dali.vqdsnc.cn/Article/details/gtdntnihca.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gttidnlinb.html

#endif
来源：http://dali.jlsjyb.cn/Article/details/gtlcbemgma.html

[S31] C++：Hello World
来源：http://dali.mhx1999.top/Article/details/gtfotxyywz.html

#include <iostream>
来源：http://dali.cheryme.top/Article/details/gtyqrwzrmr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gotoacloud.top/Article/details/gtxswnpcnz.html

[S32] C++：字符串
来源：http://dali.wangdashe.top/Article/details/gtqpnegzyk.html

std::string s = "hi";  s += "!";
来源：http://dali.smart0.xyz/Article/details/gtmyqjofwp.html

[S33] C++：vector 增删
来源：http://dali.quarkkingdee.top/Article/details/gtlswxekdo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cheryme.top/Article/details/gtsrkhpbfe.html

[S34] C++：遍历 vector
来源：http://dali.shanyushiyangtech.top/Article/details/gtahprpgms.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhiwuduotai.top/Article/details/gtdkaejzvw.html

[S35] C++：map
来源：http://dali.yonumen.top/Article/details/gtcqwklgox.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gtgocpmmws.html

[S36] C++：unordered_map
来源：http://dali.sufxvd.cn/Article/details/gttbuklgll.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xylfe.cn/Article/details/gtufzwxgjx.html

[S37] C++：set
来源：http://dali.tanke756.top/Article/details/gtowpxkvay.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jiagoushi.top/Article/details/gtdaipujsx.html

[S38] C++：排序
来源：http://dali.nwbrower.top/Article/details/gtgkqypzex.html

std::sort(v.begin(), v.end());
来源：http://dali.cqqwz.cn/Article/details/gtxkoqfyne.html

[S39] C++：自定义比较器排序
来源：http://dali.xuetiantiany.cn/Article/details/gtgutgezot.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gogol.net.cn/Article/details/gtoyeajhml.html

[S40] C++：查找元素
来源：http://dali.xuetiantiany.cn/Article/details/gtyfggpjcw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hnxiangtu.top/Article/details/gtehowtuoe.html

[S41] C++：类与构造函数
来源：http://dali.hammf.cn/Article/details/gtufkbsqcw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yangfankeji.com/Article/details/gtusqlhrwl.html

[S42] C++：继承与虚函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkztteknb.html

class B : public Base { public: void f() override {} };
来源：http://dali.hongshengwenyu.top/Article/details/gtfcymjdlz.html

[S43] C++：智能指针
来源：http://dali.xziqi.cn/Article/details/gtuliwbyfj.html

auto p = std::make_unique<int>(5);
来源：http://dali.xuetiantiany.cn/Article/details/gtpvtxigvl.html

[S44] C++：引用传参
来源：http://dali.cucudq.cn/Article/details/gtzgrvepqz.html

void inc(int &x) { ++x; }
来源：http://dali.gotoacloud.top/Article/details/gtbzfbmkrr.html

[S45] C++：lambda
来源：http://dali.cqqwz.cn/Article/details/gtuzrydbpk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fengsongda.top/Article/details/gttbtbzrzl.html

[S46] C++：函数模板
来源：http://dali.tian-w.cn/Article/details/gtgvhgngqn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cdnleiting.top/Article/details/gtzjeeweiu.html

[S47] C++：结构化绑定遍历
来源：http://dali.xziqi.cn/Article/details/gtxaqkryhe.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.daria6918.cn/Article/details/gtwxscjeku.html

[S48] C++：逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gtayngocoy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hongshengwenyu.top/Article/details/gtfnapnwie.html

while (std::getline(in, line)) { }
来源：http://dali.hammf.cn/Article/details/gtmoxwqzxf.html

[S49] C++：写文件
来源：http://dali.kuanghao11.cn/Article/details/gteocnkrgy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.feifeiyinyue.top/Article/details/gtgnzqaobq.html

[S50] C++：格式化数字
来源：http://dali.dashuyun.cn/Article/details/gttpjfiqor.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xuanzx.com/Article/details/gtztvvextm.html

[S51] C++：显式类型转换
来源：http://dali.wangshuangyany.cn/Article/details/gtumbwszsf.html

static_cast<double>(a) / b
来源：http://dali.316326.xyz/Article/details/gtrejpuqla.html

[S52] C++：const 与 noexcept
来源：http://dali.shzxlz.cn/Article/details/gtaeydfqdl.html

int size() const noexcept { return n_; }
来源：http://dali.shzxlz.cn/Article/details/gtencttzgk.html

[S53] C++：移动语义
来源：http://dali.vqdsnc.cn/Article/details/gtwnoiizcy.html

std::vector<int> w = std::move(v);
来源：http://dali.xuanzx.com/Article/details/gtcahybjve.html

[S54] C++：异常处理
来源：http://dali.kuanghao11.cn/Article/details/gtecpvcmcq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj20258.top/Article/details/gtqwopehqo.html

[S55] C++：结构化绑定
来源：http://dali.316326.xyz/Article/details/gtmbkjdypk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjkuxewon.html

[S56] C++：optional
来源：http://dali.snrcjt.cn/Article/details/gtngsqnuss.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cdnleiting.top/Article/details/gtqenubvzk.html

[S57] C++：编译期常量
来源：http://dali.cheryme.top/Article/details/gtdxbbvcuc.html

constexpr int N = 10;
来源：http://dali.sweek.top/Article/details/gtichluxut.html

[S58] C++：命名空间
来源：http://dali.daria6918.cn/Article/details/gtquqgfwoe.html

namespace ns { int f() { return 1; } }
来源：http://dali.yuanzhike.top/Article/details/gttudfugqk.html

[S59] C++：静态断言
来源：http://dali.wangshuangyany.cn/Article/details/gtzlvgwejr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.mhx1999.top/Article/details/gtniwsjaiq.html

[S60] C++：遍历并删除元素
来源：http://dali.gaohongyu789.top/Article/details/gtahrwixhz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xuanzx.com/Article/details/gtzoildvhl.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtmjdmwlua.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhengqikj.top/Article/details/gtitstjuio.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtwpqaktzd.html

[T01] Kotlin：Hello World
来源：http://dali.xinyue.icu/Article/details/gtagzgchom.html

println("Hello")
来源：http://dali.sxryk.cn/Article/details/gtuenmmqjm.html

[T02] Kotlin：变量
来源：http://dali.jlsjyb.cn/Article/details/gtowkqlftq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zycfv.cn/Article/details/gtsrzhgsvx.html

[T03] Kotlin：字符串模板
来源：http://dali.hysaishi.cn/Article/details/gttntztwie.html

"值: $b"
来源：http://dali.wangshuangyany.cn/Article/details/gtqaewpaux.html

[T04] Kotlin：空安全
来源：http://dali.haohaochexian.top/Article/details/gtgjghqild.html

val n: String? = null;  n?.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcmfyzuxk.html

[T05] Kotlin：when 表达式
来源：http://dali.ppjwa.cn/Article/details/gtefdrcefq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.aizwys.cn/Article/details/gtzvuytesx.html

[T06] Kotlin：集合映射
来源：http://dali.pycfn.com/Article/details/gtdzygkyxy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xylfe.cn/Article/details/gtzxygsnlj.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gtliodkmcu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yangfankeji.com/Article/details/gtunlmchgo.html

[T08] Kotlin：数据类
来源：http://dali.ppjwa.cn/Article/details/gtkifpceug.html

data class User(val name: String, val age: Int)
来源：http://dali.hysaishi.cn/Article/details/gtukiboedo.html

[T09] Kotlin：扩展函数
来源：http://dali.jlsjyb.cn/Article/details/gtuznwbptv.html

fun String.exclaim() = this + "!"
来源：http://dali.yvedp.cn/Article/details/gtafhfqmnb.html

[T10] Kotlin：默认参数
来源：http://dali.xziqi.cn/Article/details/gtqlglhfhm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sxryk.cn/Article/details/gtuzmbomwg.html

[T11] Kotlin：协程
来源：http://dali.zhiwuduotai.top/Article/details/gtyepnegkx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hammf.cn/Article/details/gtncdqirha.html

[T12] Kotlin：解构声明
来源：http://dali.zhongyouzk.top/Article/details/gtleohrnfv.html

val (a, b) = Pair(1, 2)
来源：http://dali.yueranfly.top/Article/details/gtfjexnjlt.html

[T13] Kotlin：只读 Map
来源：http://dali.yj202588.top/Article/details/gtdjviyzed.html

val m = mapOf("a" to 1)
来源：http://dali.yj20258888.top/Article/details/gtfsekkiul.html

[T14] Kotlin：循环
来源：http://dali.fengsongda.top/Article/details/gtzbmqejak.html

for (i in 1..10) println(i)
来源：http://dali.zhiwuduotai.top/Article/details/gtbxkmiitw.html

[T15] Kotlin：接口
来源：http://dali.gogol.net.cn/Article/details/gtqrrzpntj.html

interface Shape { fun area(): Double }
来源：http://dali.sxryk.cn/Article/details/gtdkwqlnbq.html

[T16] Swift：Hello World
来源：http://dali.daxiang520.top/Article/details/gtpabequpz.html

print("Hello")
来源：http://dali.snrcjt.cn/Article/details/gtvjfvofex.html

[T17] Swift：变量与常量
来源：http://dali.ydzc1.top/Article/details/gtoiqomdko.html

var a = 1;  let b = 2
来源：http://dali.0kj1m.cn/Article/details/gtfhxkahgp.html

[T18] Swift：字符串插值
来源：http://dali.hammf.cn/Article/details/gtgfgchlou.html

"值: \(b)"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbghidsgp.html

[T19] Swift：可选绑定
来源：http://dali.cucudq.cn/Article/details/gtcxuahksq.html

if let n = opt { print(n) }
来源：http://dali.shzxlz.cn/Article/details/gtbrzcgnjd.html

[T20] Swift：数组操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjoayzcls.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ppjwa.cn/Article/details/gtrxuagbql.html

[T21] Swift：遍历
来源：http://dali.birdmap.top/Article/details/gtaenkoqpb.html

for x in a { print(x) }
来源：http://dali.yj202588.top/Article/details/gtpamickco.html

[T22] Swift：字典
来源：http://dali.gogol.net.cn/Article/details/gtkzjqfild.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.dianchejie.cn/Article/details/gthmzyapvg.html

[T23] Swift：函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmmdwgdlh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrmsitevd.html

[T24] Swift：闭包
来源：http://dali.jqgfzy.top/Article/details/gtesquslnw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.birdmap.top/Article/details/gtqsmekizt.html

[T25] Swift：结构体
来源：http://dali.xuanzx.com/Article/details/gtrikhmktu.html

struct P { var x: Int }
来源：http://dali.guowangkeji.top/Article/details/gtaofzynkt.html

[T26] Swift：类与重写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqzoftkff.html

class A: Base { override func f() {} }
来源：http://dali.yvedp.cn/Article/details/gtdnufegvv.html

[T27] Swift：错误处理
来源：http://dali.aizwys.cn/Article/details/gtlxtfwprz.html

do { try f() } catch { print(error) }
来源：http://dali.wangdashe.top/Article/details/gtoojqufpr.html

[T28] Swift：枚举
来源：http://dali.zhongyouzk.top/Article/details/gtuxosdqng.html

enum Color { case red, green }
来源：http://dali.aizwys.cn/Article/details/gtqbtsuyav.html

[T29] Swift：guard 提前返回
来源：http://dali.daxiang520.top/Article/details/gtwmxthdwq.html

guard let x = opt else { return }
来源：http://dali.shangyingyoupin.top/Article/details/gtwfkxrpkt.html

[T30] Swift：协议
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpymssbsq.html

protocol Shape { func area() -> Double }
来源：http://dali.jqgfzy.top/Article/details/gtgvekwnuu.html

[T31] Lua：Hello World
来源：http://dali.cheryme.top/Article/details/gtzpkczezu.html

print("Hello")
来源：http://dali.haohaochexian.top/Article/details/gtzkstlcvl.html

[T32] Lua：局部变量
来源：http://dali.yj20258.top/Article/details/gtoendbjbx.html

local a = 1
来源：http://dali.chenzaomai.com/Article/details/gtrlmwyhtv.html

[T33] Lua：表（数组）
来源：http://dali.smart0.xyz/Article/details/gtxzhuwmfo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yangfankeji.com/Article/details/gtdnkpvibl.html

[T34] Lua：遍历表
来源：http://dali.nanxuanxn.top/Article/details/gtgmvofljh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xziqi.cn/Article/details/gttgztpfxz.html

[T35] Lua：字典表
来源：http://dali.yuxming.cn/Article/details/gtvhhygias.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yueranfly.top/Article/details/gtgoarhxcp.html

[T36] Lua：函数
来源：http://dali.zhengqikj.top/Article/details/gttudnkpek.html

function add(a, b) return a + b end
来源：http://dali.bjfxy.top/Article/details/gthkwfyvhu.html

[T37] Lua：字符串拼接
来源：http://dali.hywenlv.cn/Article/details/gtrwvefvza.html

"a" .. "b"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwrkshfqo.html

[T38] Lua：条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtongsthvy.html

if x > 0 then print("正") end
来源：http://dali.ydzc1.top/Article/details/gtpetvzaxy.html

[T39] Lua：模式匹配
来源：http://dali.cqqwz.cn/Article/details/gtefwdksgw.html

string.find(s, "%d+")
来源：http://dali.yj20258.top/Article/details/gtuefvzztw.html

[T40] Lua：元表
来源：http://dali.snrcjt.cn/Article/details/gtymzxefny.html

setmetatable({}, { __index = base })
来源：http://dali.sxryk.cn/Article/details/gthydkqmyp.html

[T41] Perl：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtlvpnumnj.html

print "Hello\n";
来源：http://dali.hammf.cn/Article/details/gtewsuzedm.html

[T42] Perl：变量类型
来源：http://dali.jiagoushi.top/Article/details/gtjbgwktuo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hysaishi.cn/Article/details/gtbresseii.html

[T43] Perl：字符串插值
来源：http://dali.aizwys.cn/Article/details/gtarcjffme.html

"值: $a"
来源：http://dali.jqgfzy.top/Article/details/gtywgnixpr.html

[T44] Perl：条件
来源：http://dali.jinghuilouyu.cn/Article/details/gtrspquxdt.html

if ($a > 0) { print "正"; }
来源：http://dali.quarkkingdee.top/Article/details/gtxshnfsoc.html

[T45] Perl：数组遍历
来源：http://dali.316326.xyz/Article/details/gtssbrjkul.html

for my $x (@arr) { print $x; }
来源：http://dali.quarkkingdee.top/Article/details/gtayyqahtj.html

[T46] Perl：哈希操作
来源：http://dali.shanyushiyangtech.top/Article/details/gtkzbreddu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.meibo888.top/Article/details/gtzpsxknpc.html

[T47] Perl：正则捕获
来源：http://dali.sufxvd.cn/Article/details/gtfpwkxavj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.redwolf501.top/Article/details/gtwyqajhtp.html

[T48] Perl：正则替换
来源：http://dali.316326.xyz/Article/details/gtmywjgoci.html

$s =~ s/old/new/g;
来源：http://dali.guannengcc.top/Article/details/gtgqwwpopk.html

[T49] Perl：函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkfaxqdyf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gtxffmxxcy.html

[T50] Perl：逐行读文件
来源：http://dali.yj20258888.top/Article/details/gtxatszrah.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cdnleiting.top/Article/details/gtinebksmd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.iojbl.cn/Article/details/gtyekaqsui.html

[T51] Scala：Hello World
来源：http://dali.dianchejie.cn/Article/details/gthrfkmmyq.html

println("Hello")
来源：http://dali.316326.xyz/Article/details/gtsooefjru.html

[T52] Scala：变量
来源：http://dali.sysykeji.top/Article/details/gtyhxqjthn.html

val a = 1;  var b = 2
来源：http://dali.mhx1999.top/Article/details/gtkbziekqq.html

[T53] Scala：字符串插值
来源：http://dali.zhixingplan.top/Article/details/gtrhnxgwmx.html

s"值: $b"
来源：http://dali.chenjidiqi.icu/Article/details/gtvginkjve.html

[T54] Scala：集合映射
来源：http://dali.sufxvd.cn/Article/details/gtahfjcxdz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtlfrxnlew.html

[T55] Scala：集合过滤
来源：http://dali.kuanghao11.cn/Article/details/gtrxasuviq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jinqigufen.top/Article/details/gtuvoxidnj.html

[T56] Scala：样例类
来源：http://dali.haohaochexian.top/Article/details/gtoltuszlz.html

case class User(name: String, age: Int)
来源：http://dali.gotoacloud.top/Article/details/gtzwjaywkm.html

[T57] Scala：模式匹配
来源：http://dali.fzhhl.top/Article/details/gtzxzmnvyx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.redwolf501.top/Article/details/gtwtvjveph.html

[T58] Scala：函数定义
来源：http://dali.quarkkingdee.top/Article/details/gtvkwmpjhl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.vqdsnc.cn/Article/details/gtynnsymsp.html

[T59] Scala：循环
来源：http://dali.nwbrower.top/Article/details/gtremqgkfz.html

for (i <- 1 to 10) println(i)
来源：http://dali.yvedp.cn/Article/details/gtqznigajp.html

[T60] Scala：折叠
来源：http://dali.cdnleiting.top/Article/details/gtorptuyax.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yuxming.cn/Article/details/gtbxdegmzw.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtndvkhoba.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yongpay.top/Article/details/gtfrmjagkq.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtiswonvma.html

[U01] Py：创建虚拟环境
来源：http://dali.yangfankeji.com/Article/details/gtwbfampjq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.c1oappe.top/Article/details/gtuaurbrbp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.kuanghao11.cn/Article/details/gtmvbdlvth.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xinyue.icu/Article/details/gtonzqihuh.html

[U03] Py：加载 .env 配置
来源：http://dali.shzxlz.cn/Article/details/gtcolbvgbi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.nanxinkj.top/Article/details/gtnlneynsw.html

[U04] Py：变量调试打印
来源：http://dali.jiagoushi.top/Article/details/gtkrvpajuq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinghuilouyu.cn/Article/details/gtpoxbwgql.html

[U05] Py：列表去重且保序
来源：http://dali.andypj.xyz/Article/details/gtmnnocjuq.html

list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gttqnznffa.html

[U06] Py：合并两个字典
来源：http://dali.sufxvd.cn/Article/details/gtmrwisanl.html

{**a, **b}
来源：http://dali.guowangkeji.top/Article/details/gtvfmtpxlx.html

[U07] Py：反转字典键值
来源：http://dali.aibaodan.cn/Article/details/gtyedgvqip.html

{v: k for k, v in d.items()}
来源：http://dali.mhx1999.top/Article/details/gtjvaxsnbs.html

[U08] Py：展平二维列表
来源：http://dali.zhoulong.xyz/Article/details/gthygtuesa.html

[y for x in nested for y in x]
来源：http://dali.ppjwa.cn/Article/details/gtkgabtval.html

[U09] Py：字典取最大值的键
来源：http://dali.zhixingplan.top/Article/details/gtzrftymjp.html

max(d, key=d.get)
来源：http://dali.yuxming.cn/Article/details/gtvavsmoge.html

[U10] Py：按值排序字典
来源：http://dali.hnqzz.top/Article/details/gtjtrkbgzz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.chenlongwang.top/Article/details/gtuzxxwyum.html

[U11] Py：生成器表达式
来源：http://dali.ivvv.top/Article/details/gtgproycgr.html

(x * 2 for x in arr)
来源：http://dali.yonumen.top/Article/details/gtbcxrjyaf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.c1oappe.top/Article/details/gtnwysdgaw.html

Counter(arr).most_common(3)
来源：http://dali.yuanzhike.top/Article/details/gtlfdgsyfe.html

[U13] Py：固定长度队列
来源：http://dali.jinqigufen.top/Article/details/gtvzqtiosf.html

deque(maxlen=10)
来源：http://dali.tianlin.xyz/Article/details/gtkxblpvuh.html

[U14] Py：分组收集到列表
来源：http://dali.tian-w.cn/Article/details/gttqaorbrl.html

defaultdict(list)
来源：http://dali.jinqigfzy.top/Article/details/gtzlsxocto.html

[U15] Py：高精度计时
来源：http://dali.yongpay.top/Article/details/gtveaqakfn.html

t = time.perf_counter()
来源：http://dali.tian-w.cn/Article/details/gtnkhyfflr.html

[U16] Py：命令行参数解析
来源：http://dali.gaohongyu789.top/Article/details/gtbgwtktlh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.daria6918.cn/Article/details/gttjrcufbq.html

[U17] Py：初始化日志
来源：http://dali.yongpay.top/Article/details/gtxaqacnoz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhengqikj.top/Article/details/gtkqozkdea.html

[U18] Py：预编译正则
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvxcuesc.html

pat = re.compile(r"\d+")
来源：http://dali.zhoulong.xyz/Article/details/gtjewxxvry.html

[U19] Py：正则替换带回调
来源：http://dali.hongshengwenyu.top/Article/details/gtmnmzqbgl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.snrcjt.cn/Article/details/gtkahgseat.html

[U20] Py：缓存函数结果
来源：http://dali.ppjwa.cn/Article/details/gtfgyeavch.html

@functools.lru_cache(maxsize=None)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqwlghurq.html

[U21] Py：自定义上下文管理器
来源：http://dali.yj20258888.top/Article/details/gtybzkaiuz.html

@contextlib.contextmanager
来源：http://dali.ybcxt.top/Article/details/gtwrlhvqxk.html

[U22] Py：矩阵转置
来源：http://dali.nanxinkj.top/Article/details/gtuculdums.html

list(zip(*m))
来源：http://dali.yueranfly.top/Article/details/gtgncfqwun.html

[U23] Py：分块读取大文件
来源：http://dali.hysaishi.cn/Article/details/gtbkmmtthc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jianghu66.top/Article/details/gtotegqtkx.html

[U24] Py：路径操作
来源：http://dali.jiagoushi.top/Article/details/gtlcaegfbu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ivvv.top/Article/details/gtrjskagfk.html

[U25] Py：CSV 按字典读
来源：http://dali.redwolf501.top/Article/details/gtcyyekoxp.html

csv.DictReader(f)
来源：http://dali.zhiwuduotai.top/Article/details/gtokglqwqh.html

[U26] Py：并发下载
来源：http://dali.yuxming.cn/Article/details/gtmfrlfakb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.shuidangran.top/Article/details/gtcghfiijk.html

[U27] Py：异步 HTTP
来源：http://dali.fengsongda.top/Article/details/gtvlxesppu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.sufxvd.cn/Article/details/gtqfwhhxng.html

[U28] Py：类型别名
来源：http://dali.ydzc1.top/Article/details/gtqngppzfe.html

UserId = int
来源：http://dali.yanxiufei.cn/Article/details/gtshfypgys.html

[U29] Py：属性校验
来源：http://dali.guowangkeji.top/Article/details/gtmkqshbty.html

@property 与 @x.setter 配合
来源：http://dali.dianchejie.cn/Article/details/gtkauxevbl.html

[U30] Py：数据类
来源：http://dali.haohaochexian.top/Article/details/gtrscvrghe.html

@dataclass(slots=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkquircw.html

[U31] Py：单测
来源：http://dali.tian-w.cn/Article/details/gtacabhazo.html

python -m pytest -q
来源：http://dali.jyoumei.cn/Article/details/gtreihlftg.html

[U32] Py：代码格式化
来源：http://dali.xuetiantiany.cn/Article/details/gtxtuelpij.html

ruff format . && ruff check --fix .
来源：http://dali.meibo888.top/Article/details/gtiyarorge.html

[U33] Py：打包发布
来源：http://dali.cucudq.cn/Article/details/gtqvgaynja.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jinqigufen.top/Article/details/gtzlkfnfjt.html

[U34] Py：判断编码
来源：http://dali.chenlongwang.top/Article/details/gtwugqisjq.html

chardet.detect(raw)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjfzuckms.html

[U35] Py：发送邮件
来源：http://dali.smart0.xyz/Article/details/gtoboxyfwq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.aibaodan.cn/Article/details/gthczdrxup.html

[U36] Py：定时任务
来源：http://dali.gaohongyu789.top/Article/details/gtiapltvmp.html

schedule.every(10).minutes.do(job)
来源：http://dali.xziqi.cn/Article/details/gthqhezyuc.html

[U37] Py：读写 Excel
来源：http://dali.guowangkeji.top/Article/details/gttoxwryfz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.xuanzx.com/Article/details/gtzqerxelx.html

[U38] Py：获取脚本所在目录
来源：http://dali.ivvv.top/Article/details/gtpdljxrmf.html

Path(__file__).resolve().parent
来源：http://dali.jyoumei.cn/Article/details/gtlxgwazhy.html

[U39] Py：判断是否在交互环境
来源：http://dali.nanxuanxn.top/Article/details/gtorbloixt.html

sys.stdout.isatty()
来源：http://dali.hnxiangtu.top/Article/details/gtgtcwqoua.html

[U40] Py：打印到标准错误
来源：http://dali.zhengqikj.top/Article/details/gtrqewyvtl.html

print("err", file=sys.stderr)
来源：http://dali.hysaishi.cn/Article/details/gtyebqiawo.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yj20258.top/Article/details/gtywytwwwq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.quarkkingdee.top/Article/details/gtxhxdmlik.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jlsjyb.cn/Article/details/gtjreyolah.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.fengsongda.top/Article/details/gtidaycoil.html

[U43] PHP：声明命名空间
来源：http://dali.hnxiangtu.top/Article/details/gtkkxixykm.html

namespace App\Http;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtscwmmswi.html

[U44] PHP：开启严格类型
来源：http://dali.ivvv.top/Article/details/gtdzozkgpo.html

declare(strict_types=1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsblumatf.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jiagoushi.top/Article/details/gtnwkpcfpn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shuidangran.top/Article/details/gtgelzriti.html

[U46] PHP：可空类型
来源：http://dali.cashguo.top/Article/details/gtilfawcjk.html

?string $name = null
来源：http://dali.jyoumei.cn/Article/details/gttbpztkwq.html

[U47] PHP：联合类型
来源：http://dali.chenjidiqi.icu/Article/details/gtlngqlbyy.html

int|string $id
来源：http://dali.nanxinkj.top/Article/details/gtbjasfnzu.html

[U48] PHP：纯枚举
来源：http://dali.yj20258888.top/Article/details/gtneynpyny.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ppjwa.cn/Article/details/gtiwtlewyf.html

[U49] PHP：只读属性
来源：http://dali.cashguo.top/Article/details/gtytosqzzv.html

public readonly string $name
来源：http://dali.zhengqikj.top/Article/details/gtofbkytxc.html

[U50] PHP：构造器属性提升
来源：http://dali.shuidangran.top/Article/details/gtttljkshn.html

public function __construct(private int $id) {}
来源：http://dali.sufxvd.cn/Article/details/gtuixtxfqe.html


<!-- 参考信息 -->