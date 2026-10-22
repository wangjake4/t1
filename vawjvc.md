代发 wailian999

#ifndef X_H
来源：http://dali.yongpay.top/Article/details/gtmyjjigkl.html

#define X_H
来源：http://dali.nanxinkj.top/Article/details/gteloqgqly.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gtgdbyicwd.html

[S31] C++：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtklurflsz.html

#include <iostream>
来源：http://dali.ivvv.top/Article/details/gtmkgwmebx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.pycfn.com/Article/details/gtqjkujehr.html

[S32] C++：字符串
来源：http://dali.zhixingplan.top/Article/details/gtehnupzbq.html

std::string s = "hi";  s += "!";
来源：http://dali.redwolf501.top/Article/details/gtdkdhbknn.html

[S33] C++：vector 增删
来源：http://dali.bjfxy.top/Article/details/gtnvipmkpu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hysaishi.cn/Article/details/gtqwjxipfu.html

[S34] C++：遍历 vector
来源：http://dali.316326.xyz/Article/details/gtuylxqyqk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.haohaochexian.top/Article/details/gtvfqwkxiv.html

[S35] C++：map
来源：http://dali.jqgufenzy.top/Article/details/gtbenhnmes.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fzhhl.top/Article/details/gthdivbsbd.html

[S36] C++：unordered_map
来源：http://dali.haohaochexian.top/Article/details/gtayhbfkgq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pycfn.com/Article/details/gtrwhhmyul.html

[S37] C++：set
来源：http://dali.ehwqpu.com/Article/details/gtyjonwcut.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yonumen.top/Article/details/gtwxjfmsnh.html

[S38] C++：排序
来源：http://dali.shuidangran.top/Article/details/gtdmudyfmm.html

std::sort(v.begin(), v.end());
来源：http://dali.hnxiangtu.top/Article/details/gtawuofesl.html

[S39] C++：自定义比较器排序
来源：http://dali.feifeiyinyue.top/Article/details/gtwnhnvkiz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guowangkeji.top/Article/details/gtrfcsiwin.html

[S40] C++：查找元素
来源：http://dali.sysykeji.top/Article/details/gtqaxjqocg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.pengpengdd.cyou/Article/details/gteiiumbbe.html

[S41] C++：类与构造函数
来源：http://dali.yanxiufei.cn/Article/details/gtowtebqyp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yangfankeji.com/Article/details/gtzzbdbnjf.html

[S42] C++：继承与虚函数
来源：http://dali.ybcxt.top/Article/details/gtqpfqqfog.html

class B : public Base { public: void f() override {} };
来源：http://dali.xuetiantiany.cn/Article/details/gtfaxfzsoz.html

[S43] C++：智能指针
来源：http://dali.pengpengdd.cyou/Article/details/gtdlufowme.html

auto p = std::make_unique<int>(5);
来源：http://dali.yj20258.top/Article/details/gtprbiwsou.html

[S44] C++：引用传参
来源：http://dali.ydzc1.top/Article/details/gtpjkhcpbd.html

void inc(int &x) { ++x; }
来源：http://dali.wangdashe.top/Article/details/gtbljkxnje.html

[S45] C++：lambda
来源：http://dali.pengpengdd.cyou/Article/details/gtiahdaoys.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gaohongyu789.top/Article/details/gtuxlmszmx.html

[S46] C++：函数模板
来源：http://dali.jlsjyb.cn/Article/details/gtjqkeamco.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tian-w.cn/Article/details/gtezehpona.html

[S47] C++：结构化绑定遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtepsydjnz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.quarkkingdee.top/Article/details/gtjewllaax.html

[S48] C++：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gtdayfhhuq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.pycfn.com/Article/details/gtboqxlxyq.html

while (std::getline(in, line)) { }
来源：http://dali.jinqigufen.top/Article/details/gttjvfcvfl.html

[S49] C++：写文件
来源：http://dali.cashguo.top/Article/details/gtkndtrqev.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jyoumei.cn/Article/details/gtgjmbasdq.html

[S50] C++：格式化数字
来源：http://dali.ybcxt.top/Article/details/gtzarsrdfj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtzzkhrdcg.html

[S51] C++：显式类型转换
来源：http://dali.chenjidiqi.icu/Article/details/gtxjjnjfpw.html

static_cast<double>(a) / b
来源：http://dali.zycfv.cn/Article/details/gtfegiclmv.html

[S52] C++：const 与 noexcept
来源：http://dali.kuanghao11.cn/Article/details/gttcryujaf.html

int size() const noexcept { return n_; }
来源：http://dali.yanxiufei.cn/Article/details/gtoapyhcvw.html

[S53] C++：移动语义
来源：http://dali.birdmap.top/Article/details/gtavfcecrz.html

std::vector<int> w = std::move(v);
来源：http://dali.jianghu66.top/Article/details/gtuupsczdm.html

[S54] C++：异常处理
来源：http://dali.sysykeji.top/Article/details/gtyyacejyo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hywenlv.cn/Article/details/gtelpmylks.html

[S55] C++：结构化绑定
来源：http://dali.9152youxi.cn/Article/details/gthvikazut.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhengqikj.top/Article/details/gtlevrdsiz.html

[S56] C++：optional
来源：http://dali.shangyingyoupin.top/Article/details/gtlnjxiubp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xziqi.cn/Article/details/gtxlxcbpxt.html

[S57] C++：编译期常量
来源：http://dali.zhengqikj.top/Article/details/gthpienkyo.html

constexpr int N = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gtxjsktsvd.html

[S58] C++：命名空间
来源：http://dali.316326.xyz/Article/details/gtxskfvdgn.html

namespace ns { int f() { return 1; } }
来源：http://dali.yuanzhike.top/Article/details/gtlcdtmimo.html

[S59] C++：静态断言
来源：http://dali.nanxinkj.top/Article/details/gtazdncxfh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yonumen.top/Article/details/gtdynrdvtk.html

[S60] C++：遍历并删除元素
来源：http://dali.guannengcc.top/Article/details/gtpxmrgbdr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.vqdsnc.cn/Article/details/gtdngzwado.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtlghvdmfc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xinyue.icu/Article/details/gtbymgpbjq.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtmlcstcaf.html

[T01] Kotlin：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtldozskgx.html

println("Hello")
来源：http://dali.zhiwuduotai.top/Article/details/gtjrtzmkzt.html

[T02] Kotlin：变量
来源：http://dali.meibo888.top/Article/details/gtmtidumgd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhongyouzk.top/Article/details/gtxpffgysq.html

[T03] Kotlin：字符串模板
来源：http://dali.aizwys.cn/Article/details/gtdhyuiiuu.html

"值: $b"
来源：http://dali.nanxinkj.top/Article/details/gttfolevfj.html

[T04] Kotlin：空安全
来源：http://dali.mhx1999.top/Article/details/gtfbqefjnp.html

val n: String? = null;  n?.length
来源：http://dali.guannengcc.top/Article/details/gtdvqkkfgo.html

[T05] Kotlin：when 表达式
来源：http://dali.yvedp.cn/Article/details/gtwjogiarn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.feifeiyinyue.top/Article/details/gtcnztuhxc.html

[T06] Kotlin：集合映射
来源：http://dali.hnqzz.top/Article/details/gtqcgmbqll.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sxryk.cn/Article/details/gthqygqnsa.html

[T07] Kotlin：集合过滤
来源：http://dali.cucudq.cn/Article/details/gttlikpfkq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtctqenvao.html

[T08] Kotlin：数据类
来源：http://dali.pycfn.com/Article/details/gtijejunef.html

data class User(val name: String, val age: Int)
来源：http://dali.xinyue.icu/Article/details/gtahcafdjg.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gtreegrcxm.html

fun String.exclaim() = this + "!"
来源：http://dali.sufxvd.cn/Article/details/gtdsxkohzi.html

[T10] Kotlin：默认参数
来源：http://dali.mhx1999.top/Article/details/gtdodboalk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ppjwa.cn/Article/details/gtyazjhxbc.html

[T11] Kotlin：协程
来源：http://dali.ehwqpu.com/Article/details/gtfeivfqgz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xylfe.cn/Article/details/gtiofubhef.html

[T12] Kotlin：解构声明
来源：http://dali.nanxuanxn.top/Article/details/gtftknpwzx.html

val (a, b) = Pair(1, 2)
来源：http://dali.birdmap.top/Article/details/gtiyggwxjy.html

[T13] Kotlin：只读 Map
来源：http://dali.svipenyu.cn/Article/details/gtifvmmett.html

val m = mapOf("a" to 1)
来源：http://dali.hammf.cn/Article/details/gtedcvoyyk.html

[T14] Kotlin：循环
来源：http://dali.svipenyu.cn/Article/details/gtjcqxdlhq.html

for (i in 1..10) println(i)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmvspuddl.html

[T15] Kotlin：接口
来源：http://dali.fengsongda.top/Article/details/gtuyehyiiq.html

interface Shape { fun area(): Double }
来源：http://dali.ppjwa.cn/Article/details/gthjahppjj.html

[T16] Swift：Hello World
来源：http://dali.cucudq.cn/Article/details/gtizhbllvb.html

print("Hello")
来源：http://dali.aibaodan.cn/Article/details/gtljfaijyr.html

[T17] Swift：变量与常量
来源：http://dali.fengsongda.top/Article/details/gtarvkrjrw.html

var a = 1;  let b = 2
来源：http://dali.tian-w.cn/Article/details/gthnmlrhkt.html

[T18] Swift：字符串插值
来源：http://dali.hammf.cn/Article/details/gtqsscjagu.html

"值: \(b)"
来源：http://dali.meibo888.top/Article/details/gtmfnpbjbn.html

[T19] Swift：可选绑定
来源：http://dali.yonumen.top/Article/details/gtvatzwggc.html

if let n = opt { print(n) }
来源：http://dali.shuidangran.top/Article/details/gtkkzziibe.html

[T20] Swift：数组操作
来源：http://dali.nwbrower.top/Article/details/gtzdevcter.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jqgfzy.top/Article/details/gtxyobxnpy.html

[T21] Swift：遍历
来源：http://dali.sufxvd.cn/Article/details/gtqpjdwuzq.html

for x in a { print(x) }
来源：http://dali.yongpay.top/Article/details/gtmaatldmz.html

[T22] Swift：字典
来源：http://dali.zdqjudy.top/Article/details/gtlvbrryxf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.kuanghao11.cn/Article/details/gtztnrednj.html

[T23] Swift：函数
来源：http://dali.jinqigfzy.top/Article/details/gtpeyvbvnz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cashguo.top/Article/details/gtlupnqlrt.html

[T24] Swift：闭包
来源：http://dali.yuxming.cn/Article/details/gtpvblkiln.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.redwolf501.top/Article/details/gtdbirbqce.html

[T25] Swift：结构体
来源：http://dali.sufxvd.cn/Article/details/gtttbwqugw.html

struct P { var x: Int }
来源：http://dali.smart0.xyz/Article/details/gtbwknrsrh.html

[T26] Swift：类与重写
来源：http://dali.cheryme.top/Article/details/gtpjaukqnr.html

class A: Base { override func f() {} }
来源：http://dali.jiagoushi.top/Article/details/gtydjmhrhw.html

[T27] Swift：错误处理
来源：http://dali.zhengqikj.top/Article/details/gtcbqvpkil.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gtwobifxyz.html

[T28] Swift：枚举
来源：http://dali.mhx1999.top/Article/details/gtaldzgajr.html

enum Color { case red, green }
来源：http://dali.jlsjyb.cn/Article/details/gtmlglsqie.html

[T29] Swift：guard 提前返回
来源：http://dali.cashguo.top/Article/details/gtpeqitaxc.html

guard let x = opt else { return }
来源：http://dali.yonumen.top/Article/details/gtuynckamx.html

[T30] Swift：协议
来源：http://dali.guowangkeji.top/Article/details/gttetrkffe.html

protocol Shape { func area() -> Double }
来源：http://dali.chenjidiqi.icu/Article/details/gtekrvmbgp.html

[T31] Lua：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtwlfievhh.html

print("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvuldoszu.html

[T32] Lua：局部变量
来源：http://dali.gogol.net.cn/Article/details/gtfoxbfiwd.html

local a = 1
来源：http://dali.zhengqikj.top/Article/details/gteqynuaad.html

[T33] Lua：表（数组）
来源：http://dali.zhoulong.xyz/Article/details/gtqspprmyx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xziqi.cn/Article/details/gtdrjfbbkf.html

[T34] Lua：遍历表
来源：http://dali.jyoumei.cn/Article/details/gtmiovbxga.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxvcapywd.html

[T35] Lua：字典表
来源：http://dali.nanxuanxn.top/Article/details/gtfnjladzx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ehwqpu.com/Article/details/gtrrkqppvd.html

[T36] Lua：函数
来源：http://dali.yuxming.cn/Article/details/gtkyuxodmf.html

function add(a, b) return a + b end
来源：http://dali.jqgufenzy.top/Article/details/gtdnutnxhz.html

[T37] Lua：字符串拼接
来源：http://dali.xylfe.cn/Article/details/gtzipbdlsy.html

"a" .. "b"
来源：http://dali.sufxvd.cn/Article/details/gtpskzorhz.html

[T38] Lua：条件
来源：http://dali.zhiwuduotai.top/Article/details/gtiftzqajr.html

if x > 0 then print("正") end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtukioniip.html

[T39] Lua：模式匹配
来源：http://dali.cqqwz.cn/Article/details/gtyiguerfz.html

string.find(s, "%d+")
来源：http://dali.cheryme.top/Article/details/gtrlgnolki.html

[T40] Lua：元表
来源：http://dali.vqdsnc.cn/Article/details/gtaxkgbkda.html

setmetatable({}, { __index = base })
来源：http://dali.cucudq.cn/Article/details/gteyzpxgaz.html

[T41] Perl：Hello World
来源：http://dali.xuanzx.com/Article/details/gtyjivcsza.html

print "Hello\n";
来源：http://dali.gogol.net.cn/Article/details/gtrzrfwgmg.html

[T42] Perl：变量类型
来源：http://dali.havefunace.top/Article/details/gtpfiuvuwj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.iojbl.cn/Article/details/gtwrbxjzbp.html

[T43] Perl：字符串插值
来源：http://dali.yueranfly.top/Article/details/gtqvuippzv.html

"值: $a"
来源：http://dali.wangdashe.top/Article/details/gtfavqnsty.html

[T44] Perl：条件
来源：http://dali.pengpengdd.cyou/Article/details/gtjhyavhvx.html

if ($a > 0) { print "正"; }
来源：http://dali.yueranfly.top/Article/details/gtoqsqueim.html

[T45] Perl：数组遍历
来源：http://dali.nwbrower.top/Article/details/gtgurapkzm.html

for my $x (@arr) { print $x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwkvtfoxy.html

[T46] Perl：哈希操作
来源：http://dali.daxiang520.top/Article/details/gtpcrkgsky.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jlsjyb.cn/Article/details/gtyrvutawa.html

[T47] Perl：正则捕获
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthihwpdpm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyjgsvlfe.html

[T48] Perl：正则替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtvgrotduy.html

$s =~ s/old/new/g;
来源：http://dali.chenlongwang.top/Article/details/gtzwwmkvjq.html

[T49] Perl：函数
来源：http://dali.pycfn.com/Article/details/gtxtmkbmeb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gtbjanoehi.html

[T50] Perl：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gttcuhyhcv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgvpgqmzq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zdqjudy.top/Article/details/gtmongneqn.html

[T51] Scala：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtmhitmfzb.html

println("Hello")
来源：http://dali.ivvv.top/Article/details/gtmgdbypgw.html

[T52] Scala：变量
来源：http://dali.bjfxy.top/Article/details/gtgpizqbki.html

val a = 1;  var b = 2
来源：http://dali.guowangkeji.top/Article/details/gtkfcgpgep.html

[T53] Scala：字符串插值
来源：http://dali.nwbrower.top/Article/details/gtqzydcpcf.html

s"值: $b"
来源：http://dali.bjfxy.top/Article/details/gtrmqfnnpq.html

[T54] Scala：集合映射
来源：http://dali.vqdsnc.cn/Article/details/gtmlxenefh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gogol.net.cn/Article/details/gtxwiuwxfs.html

[T55] Scala：集合过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtktyydrgo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.aibaodan.cn/Article/details/gtpjqhsanx.html

[T56] Scala：样例类
来源：http://dali.ehwqpu.com/Article/details/gtrfmcxbvk.html

case class User(name: String, age: Int)
来源：http://dali.pycfn.com/Article/details/gtqzojcyfg.html

[T57] Scala：模式匹配
来源：http://dali.daria6918.cn/Article/details/gtakfixdql.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shangyingyoupin.top/Article/details/gtjycmivkz.html

[T58] Scala：函数定义
来源：http://dali.cashguo.top/Article/details/gtbrhuyoio.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.meibo888.top/Article/details/gtawemfbnw.html

[T59] Scala：循环
来源：http://dali.zhixingplan.top/Article/details/gtolsloydc.html

for (i <- 1 to 10) println(i)
来源：http://dali.yj20258.top/Article/details/gtbxhzjayw.html

[T60] Scala：折叠
来源：http://dali.jqgufenzy.top/Article/details/gthfunlhiz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tian-w.cn/Article/details/gtqjxigtdu.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtmcxqyvle.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ppjwa.cn/Article/details/gtnagngvie.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtdezwrgxo.html

[U01] Py：创建虚拟环境
来源：http://dali.hfpthk.cn/Article/details/gttlgdvycq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xuetiantiany.cn/Article/details/gtnmfwksqs.html

[U02] Py：导出 / 安装依赖
来源：http://dali.meibo888.top/Article/details/gtjvjiibxc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hnqzz.top/Article/details/gtqddnipcg.html

[U03] Py：加载 .env 配置
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqiafrrl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yuxming.cn/Article/details/gttvaeowhq.html

[U04] Py：变量调试打印
来源：http://dali.zhixingplan.top/Article/details/gtfoynvjtf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.dashuyun.cn/Article/details/gtklgoujmd.html

[U05] Py：列表去重且保序
来源：http://dali.shzxlz.cn/Article/details/gttqdvukpe.html

list(dict.fromkeys(arr))
来源：http://dali.wangdashe.top/Article/details/gtexghgglw.html

[U06] Py：合并两个字典
来源：http://dali.yongpay.top/Article/details/gthpwpsuyl.html

{**a, **b}
来源：http://dali.gogol.net.cn/Article/details/gtepibsytx.html

[U07] Py：反转字典键值
来源：http://dali.chenjidiqi.icu/Article/details/gtmhlqaqcp.html

{v: k for k, v in d.items()}
来源：http://dali.xylfe.cn/Article/details/gtycttcsdn.html

[U08] Py：展平二维列表
来源：http://dali.mhx1999.top/Article/details/gtxojlxyhe.html

[y for x in nested for y in x]
来源：http://dali.chenlongwang.top/Article/details/gtitbxsxrs.html

[U09] Py：字典取最大值的键
来源：http://dali.quarkkingdee.top/Article/details/gtzafgietv.html

max(d, key=d.get)
来源：http://dali.yvedp.cn/Article/details/gtoobpoefy.html

[U10] Py：按值排序字典
来源：http://dali.nwbrower.top/Article/details/gtudkfkoig.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdqeelsyo.html

[U11] Py：生成器表达式
来源：http://dali.hnqzz.top/Article/details/gtlkcwaikd.html

(x * 2 for x in arr)
来源：http://dali.hammf.cn/Article/details/gttklbbegz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sufxvd.cn/Article/details/gtltjjzkww.html

Counter(arr).most_common(3)
来源：http://dali.ivvv.top/Article/details/gtjulitcds.html

[U13] Py：固定长度队列
来源：http://dali.shuidangran.top/Article/details/gthdrstxmi.html

deque(maxlen=10)
来源：http://dali.chenlongwang.top/Article/details/gtvppoxlhn.html

[U14] Py：分组收集到列表
来源：http://dali.birdmap.top/Article/details/gtufyoptct.html

defaultdict(list)
来源：http://dali.yj20258.top/Article/details/gtclcrkyal.html

[U15] Py：高精度计时
来源：http://dali.guannengcc.top/Article/details/gthsuuqsrk.html

t = time.perf_counter()
来源：http://dali.wangshuangyany.cn/Article/details/gtaiavmkca.html

[U16] Py：命令行参数解析
来源：http://dali.yuanzhike.top/Article/details/gtmqmbvujs.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.redwolf501.top/Article/details/gtzffflzui.html

[U17] Py：初始化日志
来源：http://dali.mhx1999.top/Article/details/gtrhqxoaab.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.sweek.top/Article/details/gtopnqywzk.html

[U18] Py：预编译正则
来源：http://dali.smart0.xyz/Article/details/gtcyhwvqiu.html

pat = re.compile(r"\d+")
来源：http://dali.9152youxi.cn/Article/details/gtlalavewf.html

[U19] Py：正则替换带回调
来源：http://dali.xinyue.icu/Article/details/gtwocnqbnf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hammf.cn/Article/details/gtterednar.html

[U20] Py：缓存函数结果
来源：http://dali.yj202588.top/Article/details/gtmqalfnsm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cashguo.top/Article/details/gtkcdfited.html

[U21] Py：自定义上下文管理器
来源：http://dali.wangdashe.top/Article/details/gtmjybxnle.html

@contextlib.contextmanager
来源：http://dali.gaohongyu789.top/Article/details/gtrnvewoym.html

[U22] Py：矩阵转置
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkkqkssb.html

list(zip(*m))
来源：http://dali.cqqwz.cn/Article/details/gthqrhsfdx.html

[U23] Py：分块读取大文件
来源：http://dali.vqdsnc.cn/Article/details/gtwiywqlfo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.pengpengdd.cyou/Article/details/gtwuftxrir.html

[U24] Py：路径操作
来源：http://dali.xuetiantiany.cn/Article/details/gtqpbqmpie.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yj20258888.top/Article/details/gtmyofrqmh.html

[U25] Py：CSV 按字典读
来源：http://dali.redwolf501.top/Article/details/gtylkbjxkt.html

csv.DictReader(f)
来源：http://dali.pengpengdd.cyou/Article/details/gtzaeuzzsy.html

[U26] Py：并发下载
来源：http://dali.zycfv.cn/Article/details/gtokxoppkq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhoulong.xyz/Article/details/gtjkzdrqvl.html

[U27] Py：异步 HTTP
来源：http://dali.fengsongda.top/Article/details/gtqowfdlvz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hnxiangtu.top/Article/details/gtapellllu.html

[U28] Py：类型别名
来源：http://dali.c1oappe.top/Article/details/gtxwlydsis.html

UserId = int
来源：http://dali.hfpthk.cn/Article/details/gtogktylul.html

[U29] Py：属性校验
来源：http://dali.vqdsnc.cn/Article/details/gtxgaxkmse.html

@property 与 @x.setter 配合
来源：http://dali.cdnleiting.top/Article/details/gtvalxkafy.html

[U30] Py：数据类
来源：http://dali.andypj.xyz/Article/details/gtlsrwyyve.html

@dataclass(slots=True)
来源：http://dali.vqdsnc.cn/Article/details/gtxtlykdge.html

[U31] Py：单测
来源：http://dali.hongshengwenyu.top/Article/details/gtdxuetpqf.html

python -m pytest -q
来源：http://dali.smart0.xyz/Article/details/gtuuwijdmx.html

[U32] Py：代码格式化
来源：http://dali.quarkkingdee.top/Article/details/gthoargrfl.html

ruff format . && ruff check --fix .
来源：http://dali.zycfv.cn/Article/details/gtgsqqkmps.html

[U33] Py：打包发布
来源：http://dali.cashguo.top/Article/details/gtmczxhige.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.guowangkeji.top/Article/details/gtvbmwsiav.html

[U34] Py：判断编码
来源：http://dali.hfpthk.cn/Article/details/gtspwjgoyf.html

chardet.detect(raw)
来源：http://dali.xylfe.cn/Article/details/gtpxtqvrwy.html

[U35] Py：发送邮件
来源：http://dali.yuanzhike.top/Article/details/gtwrgdwuxy.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.shuidangran.top/Article/details/gtokauughd.html

[U36] Py：定时任务
来源：http://dali.xinyue.icu/Article/details/gthkalbjcp.html

schedule.every(10).minutes.do(job)
来源：http://dali.cucudq.cn/Article/details/gthltdvjrt.html

[U37] Py：读写 Excel
来源：http://dali.pycfn.com/Article/details/gtgaboqqsx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.0kj1m.cn/Article/details/gtcafmopuj.html

[U38] Py：获取脚本所在目录
来源：http://dali.yueranfly.top/Article/details/gtlmbmodjb.html

Path(__file__).resolve().parent
来源：http://dali.shuidangran.top/Article/details/gtundkcwii.html

[U39] Py：判断是否在交互环境
来源：http://dali.jqgufenzy.top/Article/details/gtqwummmax.html

sys.stdout.isatty()
来源：http://dali.zhongyouzk.top/Article/details/gtxkwouaca.html

[U40] Py：打印到标准错误
来源：http://dali.yj202588.top/Article/details/gtxfonypxi.html

print("err", file=sys.stderr)
来源：http://dali.hammf.cn/Article/details/gtwlwnmcip.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.sufxvd.cn/Article/details/gtkaoxxbsm.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ydzc1.top/Article/details/gtgrrilrqv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yuxming.cn/Article/details/gtobmgojyg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zdqjudy.top/Article/details/gtjklpyive.html

[U43] PHP：声明命名空间
来源：http://dali.guowangkeji.top/Article/details/gtwetusztb.html

namespace App\Http;
来源：http://dali.yj202588.top/Article/details/gtqrkglnni.html

[U44] PHP：开启严格类型
来源：http://dali.wangshuangyany.cn/Article/details/gthoffbbzx.html

declare(strict_types=1);
来源：http://dali.aizwys.cn/Article/details/gtiwhzgoke.html

[U45] PHP：类型声明与返回类型
来源：http://dali.ybcxt.top/Article/details/gtpssuhnvy.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gtvwtwxtek.html

[U46] PHP：可空类型
来源：http://dali.yvedp.cn/Article/details/gtvswcckqp.html

?string $name = null
来源：http://dali.quarkkingdee.top/Article/details/gtilxyfzcp.html

[U47] PHP：联合类型
来源：http://dali.fzhhl.top/Article/details/gtmrefnduz.html

int|string $id
来源：http://dali.havefunace.top/Article/details/gttvykwhzr.html

[U48] PHP：纯枚举
来源：http://dali.kuanghao11.cn/Article/details/gtjjuilwaw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhongyouzk.top/Article/details/gtetohrnqs.html

[U49] PHP：只读属性
来源：http://dali.yj20258.top/Article/details/gtrrdwtqit.html

public readonly string $name
来源：http://dali.zdqjudy.top/Article/details/gtchmuqpjl.html

[U50] PHP：构造器属性提升
来源：http://dali.havefunace.top/Article/details/gtsuyeummz.html

public function __construct(private int $id) {}
来源：http://dali.kuanghao11.cn/Article/details/gtkkprmuth.html

[U51] PHP：数组解构
来源：http://dali.tanke756.top/Article/details/gtmiudyzji.html

[$a, $b] = $arr;
来源：http://dali.jinqigufen.top/Article/details/gtknhmgavv.html

[U52] PHP：箭头函数
来源：http://dali.svipenyu.cn/Article/details/gtzffrrvie.html

$double = fn($x) => $x * 2;
来源：http://dali.jyoumei.cn/Article/details/gtmbdtefdl.html

[U53] PHP：空合并运算符
来源：http://dali.pengpengdd.cyou/Article/details/gtajnuwrua.html

$v = $a ?? $b ?? "default";
来源：http://dali.redwolf501.top/Article/details/gtikeejbgq.html

[U54] PHP：空安全调用
来源：http://dali.yj202588.top/Article/details/gtsyexrwww.html

$obj?->method()
来源：http://dali.redwolf501.top/Article/details/gtrxcoqeae.html


<!-- 参考信息 -->