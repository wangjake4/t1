代发 wailian999

#include <iostream>
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2heuheunt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jianghu66.top/Article/details/gt2luqdyyfw.html

[S32] C++：字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2uirgsvnk.html

std::string s = "hi";  s += "!";
来源：http://dali.chenlongwang.top/Article/details/gt2zqubafvc.html

[S33] C++：vector 增删
来源：http://dali.zycfv.cn/Article/details/gt2jdcezara.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jyoumei.cn/Article/details/gt2cvtpumqk.html

[S34] C++：遍历 vector
来源：http://dali.zdqjudy.top/Article/details/gt2ywowpgqz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ojkpchyv.html

[S35] C++：map
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hpiezmvy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gt2xmvngpic.html

[S36] C++：unordered_map
来源：http://dali.mhx1999.top/Article/details/gt2heamhksl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xylfe.cn/Article/details/gt2yvglztbq.html

[S37] C++：set
来源：http://dali.shangyingyoupin.top/Article/details/gt2rlnmkdra.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2evvzrdhs.html

[S38] C++：排序
来源：http://dali.yueranfly.top/Article/details/gt2syomxgij.html

std::sort(v.begin(), v.end());
来源：http://dali.hnxiangtu.top/Article/details/gt2ufmibhxe.html

[S39] C++：自定义比较器排序
来源：http://dali.hnqzz.top/Article/details/gt2vqdxixyb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.dianchejie.cn/Article/details/gt2joxawhzm.html

[S40] C++：查找元素
来源：http://dali.nwbrower.top/Article/details/gt2plskevnk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.bjfxy.top/Article/details/gt2ihactdkp.html

[S41] C++：类与构造函数
来源：http://dali.mhx1999.top/Article/details/gt2tgquzgsr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nanxuanxn.top/Article/details/gt2akkhiqmh.html

[S42] C++：继承与虚函数
来源：http://dali.xinyue.icu/Article/details/gt2xajimtrr.html

class B : public Base { public: void f() override {} };
来源：http://dali.pengpengdd.cyou/Article/details/gt2gaqgvulz.html

[S43] C++：智能指针
来源：http://dali.ehwqpu.com/Article/details/gt2wxklctjr.html

auto p = std::make_unique<int>(5);
来源：http://dali.meibo888.top/Article/details/gt2hmncdbzv.html

[S44] C++：引用传参
来源：http://dali.wangdashe.top/Article/details/gt2guaoygsf.html

void inc(int &x) { ++x; }
来源：http://dali.shzxlz.cn/Article/details/gt2zgdapubh.html

[S45] C++：lambda
来源：http://dali.xinyue.icu/Article/details/gt2nwzzxcfi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ydzc1.top/Article/details/gt2yulcxrvp.html

[S46] C++：函数模板
来源：http://dali.yuanzhike.top/Article/details/gt2mskvujft.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.havefunace.top/Article/details/gt2icecqkhl.html

[S47] C++：结构化绑定遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jsnlrjgs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sycffmlp.html

[S48] C++：逐行读文件
来源：http://dali.tanke756.top/Article/details/gt2ksxkisnp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hnxiangtu.top/Article/details/gt2ityitusd.html

while (std::getline(in, line)) { }
来源：http://dali.9152youxi.cn/Article/details/gt2ejdyvahk.html

[S49] C++：写文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2yyachtuq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.svipenyu.cn/Article/details/gt2bbewxldq.html

[S50] C++：格式化数字
来源：http://dali.ppjwa.cn/Article/details/gt2zynmxato.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jianghu66.top/Article/details/gt2lipvlchc.html

[S51] C++：显式类型转换
来源：http://dali.ydzc1.top/Article/details/gt2pchbaopy.html

static_cast<double>(a) / b
来源：http://dali.bjfxy.top/Article/details/gt2ovocrzlp.html

[S52] C++：const 与 noexcept
来源：http://dali.zhiwuduotai.top/Article/details/gt2motjlbcr.html

int size() const noexcept { return n_; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2demfjvjv.html

[S53] C++：移动语义
来源：http://dali.xuetiantiany.cn/Article/details/gt2jckbhujr.html

std::vector<int> w = std::move(v);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kfdkcnvg.html

[S54] C++：异常处理
来源：http://dali.sufxvd.cn/Article/details/gt2wtnprgkv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gzhubu.top/Article/details/gt2tmhdgkgw.html

[S55] C++：结构化绑定
来源：http://dali.hfpthk.cn/Article/details/gt2cvehgwyj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.andypj.xyz/Article/details/gt2rmmkmccn.html

[S56] C++：optional
来源：http://dali.sweek.top/Article/details/gt2oxhewgvq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.haohaochexian.top/Article/details/gt2xxghexod.html

[S57] C++：编译期常量
来源：http://dali.zhiwuduotai.top/Article/details/gt2ucsvddmx.html

constexpr int N = 10;
来源：http://dali.gzhubu.top/Article/details/gt2qxntonun.html

[S58] C++：命名空间
来源：http://dali.chenjidiqi.icu/Article/details/gt2zzrkwubr.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nzayejai.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2rwipovxn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhoulong.xyz/Article/details/gt2urjfvsmd.html

[S60] C++：遍历并删除元素
来源：http://dali.svipenyu.cn/Article/details/gt2aqvljdmk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sxryk.cn/Article/details/gt2cxmkrhqt.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2iramowpq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sljkgrks.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2wemznkyk.html

[T01] Kotlin：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bowshjyq.html

println("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mxuqkyvf.html

[T02] Kotlin：变量
来源：http://dali.aizwys.cn/Article/details/gt2evzwczvv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cucudq.cn/Article/details/gt2wnlediir.html

[T03] Kotlin：字符串模板
来源：http://dali.daria6918.cn/Article/details/gt2vdffxezd.html

"值: $b"
来源：http://dali.yuxming.cn/Article/details/gt2jubdxgxl.html

[T04] Kotlin：空安全
来源：http://dali.ydzc1.top/Article/details/gt2twoviufp.html

val n: String? = null;  n?.length
来源：http://dali.shangyingyoupin.top/Article/details/gt2dclhnexo.html

[T05] Kotlin：when 表达式
来源：http://dali.zhongyouzk.top/Article/details/gt2oketawnq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jqgufenzy.top/Article/details/gt2ijizjkcp.html

[T06] Kotlin：集合映射
来源：http://dali.yueranfly.top/Article/details/gt2imfmzfhd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfmirio.html

[T07] Kotlin：集合过滤
来源：http://dali.zhengqikj.top/Article/details/gt2vjdekshq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuanzhike.top/Article/details/gt2aluhevtf.html

[T08] Kotlin：数据类
来源：http://dali.meibo888.top/Article/details/gt2ivblvwhj.html

data class User(val name: String, val age: Int)
来源：http://dali.cheryme.top/Article/details/gt2oblyonsy.html

[T09] Kotlin：扩展函数
来源：http://dali.vqdsnc.cn/Article/details/gt2jngjnqqh.html

fun String.exclaim() = this + "!"
来源：http://dali.bjfxy.top/Article/details/gt2cqpuwten.html

[T10] Kotlin：默认参数
来源：http://dali.jqgfzy.top/Article/details/gt2fbpsoejq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.chenjidiqi.icu/Article/details/gt2wupspjap.html

[T11] Kotlin：协程
来源：http://dali.birdmap.top/Article/details/gt2esjzbsqg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.chenzaomai.com/Article/details/gt2pifsbizg.html

[T12] Kotlin：解构声明
来源：http://dali.zhixingplan.top/Article/details/gt2gxhouslx.html

val (a, b) = Pair(1, 2)
来源：http://dali.shuidangran.top/Article/details/gt2kqizjayi.html

[T13] Kotlin：只读 Map
来源：http://dali.sxryk.cn/Article/details/gt2fpolqqzx.html

val m = mapOf("a" to 1)
来源：http://dali.yuanzhike.top/Article/details/gt2ngcbqujp.html

[T14] Kotlin：循环
来源：http://dali.meibo888.top/Article/details/gt2bxoazhtn.html

for (i in 1..10) println(i)
来源：http://dali.jinqigufen.top/Article/details/gt2mszltzqo.html

[T15] Kotlin：接口
来源：http://dali.sufxvd.cn/Article/details/gt2yarhudje.html

interface Shape { fun area(): Double }
来源：http://dali.hnqzz.top/Article/details/gt2yvujcdnu.html

[T16] Swift：Hello World
来源：http://dali.nwbrower.top/Article/details/gt2zqjvsyfz.html

print("Hello")
来源：http://dali.cashguo.top/Article/details/gt2almbjsvi.html

[T17] Swift：变量与常量
来源：http://dali.feifeiyinyue.top/Article/details/gt2kyzxneif.html

var a = 1;  let b = 2
来源：http://dali.yuxming.cn/Article/details/gt2wsaueuxc.html

[T18] Swift：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gt2ksblxkwd.html

"值: \(b)"
来源：http://dali.hammf.cn/Article/details/gt2bvbyyucn.html

[T19] Swift：可选绑定
来源：http://dali.jinqigufen.top/Article/details/gt2tcfawlah.html

if let n = opt { print(n) }
来源：http://dali.aizwys.cn/Article/details/gt2qhusgvrq.html

[T20] Swift：数组操作
来源：http://dali.cashguo.top/Article/details/gt2mxmujwuh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jinqigufen.top/Article/details/gt2vgnlpenw.html

[T21] Swift：遍历
来源：http://dali.gaohongyu789.top/Article/details/gt2xkdgztvx.html

for x in a { print(x) }
来源：http://dali.yueranfly.top/Article/details/gt2fsgrtkuh.html

[T22] Swift：字典
来源：http://dali.xuanzx.com/Article/details/gt2vrwexomz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yuanzhike.top/Article/details/gt2nzlzqvph.html

[T23] Swift：函数
来源：http://dali.dashuyun.cn/Article/details/gt2wkbmvhwx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.daxiang520.top/Article/details/gt2qaduwvcl.html

[T24] Swift：闭包
来源：http://dali.yanxiufei.cn/Article/details/gt2hpuwoanl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gt2kzozakdi.html

[T25] Swift：结构体
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zlmhnzva.html

struct P { var x: Int }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jxioemay.html

[T26] Swift：类与重写
来源：http://dali.cheryme.top/Article/details/gt2kyaghbez.html

class A: Base { override func f() {} }
来源：http://dali.cdnleiting.top/Article/details/gt2tpnqupuh.html

[T27] Swift：错误处理
来源：http://dali.shzxlz.cn/Article/details/gt2gdqvntji.html

do { try f() } catch { print(error) }
来源：http://dali.xinyue.icu/Article/details/gt2kflifagd.html

[T28] Swift：枚举
来源：http://dali.snrcjt.cn/Article/details/gt2hdiowgau.html

enum Color { case red, green }
来源：http://dali.xuanzx.com/Article/details/gt2zhdwnwtu.html

[T29] Swift：guard 提前返回
来源：http://dali.yuanzhike.top/Article/details/gt2duxanywj.html

guard let x = opt else { return }
来源：http://dali.xziqi.cn/Article/details/gt2pvxowoxr.html

[T30] Swift：协议
来源：http://dali.yueranfly.top/Article/details/gt2dhisaiuz.html

protocol Shape { func area() -> Double }
来源：http://dali.sysykeji.top/Article/details/gt2tbnugudj.html

[T31] Lua：Hello World
来源：http://dali.fzhhl.top/Article/details/gt2zsomcmue.html

print("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gt2krlwgehm.html

[T32] Lua：局部变量
来源：http://dali.gogol.net.cn/Article/details/gt2zgwihvlv.html

local a = 1
来源：http://dali.c1oappe.top/Article/details/gt2wupeekma.html

[T33] Lua：表（数组）
来源：http://dali.pengpengdd.cyou/Article/details/gt2pfhdkmel.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.kuanghao11.cn/Article/details/gt2ejabcjpn.html

[T34] Lua：遍历表
来源：http://dali.sufxvd.cn/Article/details/gt2zdkbzsfc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.aibaodan.cn/Article/details/gt2bblvwehe.html

[T35] Lua：字典表
来源：http://dali.9152youxi.cn/Article/details/gt2thqaalwc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.c1oappe.top/Article/details/gt2nfcizvkq.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2avmtxloh.html

function add(a, b) return a + b end
来源：http://dali.chenlongwang.top/Article/details/gt2uybxbdhl.html

[T37] Lua：字符串拼接
来源：http://dali.snrcjt.cn/Article/details/gt2wqgjbzpv.html

"a" .. "b"
来源：http://dali.guannengcc.top/Article/details/gt2cueqhsur.html

[T38] Lua：条件
来源：http://dali.chenlongwang.top/Article/details/gt2xikhejyl.html

if x > 0 then print("正") end
来源：http://dali.redwolf501.top/Article/details/gt2lhjahcxc.html

[T39] Lua：模式匹配
来源：http://dali.c1oappe.top/Article/details/gt2dflxwcxf.html

string.find(s, "%d+")
来源：http://dali.cdnleiting.top/Article/details/gt2kifakgtr.html

[T40] Lua：元表
来源：http://dali.hnqzz.top/Article/details/gt2lbxicpbu.html

setmetatable({}, { __index = base })
来源：http://dali.xinyue.icu/Article/details/gt2hynxeorl.html

[T41] Perl：Hello World
来源：http://dali.wangdashe.top/Article/details/gt2ysbezjgz.html

print "Hello\n";
来源：http://dali.tianlin.xyz/Article/details/gt2bxckluzl.html

[T42] Perl：变量类型
来源：http://dali.fzhhl.top/Article/details/gt2nshkhxzr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xylfe.cn/Article/details/gt2adpyvnkp.html

[T43] Perl：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gt2yqaesudz.html

"值: $a"
来源：http://dali.aizwys.cn/Article/details/gt2dxlpayva.html

[T44] Perl：条件
来源：http://dali.zycfv.cn/Article/details/gt2usvtcaje.html

if ($a > 0) { print "正"; }
来源：http://dali.316326.xyz/Article/details/gt2gybxkxya.html

[T45] Perl：数组遍历
来源：http://dali.andypj.xyz/Article/details/gt2vfadauxo.html

for my $x (@arr) { print $x; }
来源：http://dali.birdmap.top/Article/details/gt2sdjhunbo.html

[T46] Perl：哈希操作
来源：http://dali.aizwys.cn/Article/details/gt2grelyipc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yuanzhike.top/Article/details/gt2ezislfjk.html

[T47] Perl：正则捕获
来源：http://dali.guowangkeji.top/Article/details/gt2vfmfhayu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ivvv.top/Article/details/gt2iptlkdct.html

[T48] Perl：正则替换
来源：http://dali.jianghu66.top/Article/details/gt2himtiihz.html

$s =~ s/old/new/g;
来源：http://dali.jyoumei.cn/Article/details/gt2elvjmedy.html

[T49] Perl：函数
来源：http://dali.gotoacloud.top/Article/details/gt2ogablazx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zycfv.cn/Article/details/gt2tqwmltgk.html

[T50] Perl：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gt2lfcqmaai.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sweek.top/Article/details/gt2bsqoqbrj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.haohaochexian.top/Article/details/gt2uzojpvdz.html

[T51] Scala：Hello World
来源：http://dali.guowangkeji.top/Article/details/gt2jvuuyavf.html

println("Hello")
来源：http://dali.haohaochexian.top/Article/details/gt2hrzyfcgo.html

[T52] Scala：变量
来源：http://dali.sufxvd.cn/Article/details/gt2ixlcbzls.html

val a = 1;  var b = 2
来源：http://dali.haohaochexian.top/Article/details/gt2tynrvktc.html

[T53] Scala：字符串插值
来源：http://dali.ydzc1.top/Article/details/gt2gzhjykmg.html

s"值: $b"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jmbmhxzv.html

[T54] Scala：集合映射
来源：http://dali.gaohongyu789.top/Article/details/gt2ffiqemct.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ivvv.top/Article/details/gt2uylxdmtr.html

[T55] Scala：集合过滤
来源：http://dali.kuanghao11.cn/Article/details/gt2bqoneskx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hysaishi.cn/Article/details/gt2zkdmmoek.html

[T56] Scala：样例类
来源：http://dali.chenlongwang.top/Article/details/gt2uudhdkim.html

case class User(name: String, age: Int)
来源：http://dali.smart0.xyz/Article/details/gt2ywkalzda.html

[T57] Scala：模式匹配
来源：http://dali.hammf.cn/Article/details/gt2mthntrkd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.nanxinkj.top/Article/details/gt2bxnhjgkt.html

[T58] Scala：函数定义
来源：http://dali.chenjidiqi.icu/Article/details/gt2myokrutc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xinyue.icu/Article/details/gt2uzsnjugn.html

[T59] Scala：循环
来源：http://dali.sweek.top/Article/details/gt2qudxxcgh.html

for (i <- 1 to 10) println(i)
来源：http://dali.guowangkeji.top/Article/details/gt2pjmkpbwf.html

[T60] Scala：折叠
来源：http://dali.vqdsnc.cn/Article/details/gt2tgvflhgn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.c1oappe.top/Article/details/gt2rthrjwik.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2ewgrhnac.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.meibo888.top/Article/details/gt2nlsxdlfg.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2tpzofmuk.html

[U01] Py：创建虚拟环境
来源：http://dali.0kj1m.cn/Article/details/gt2jxqmweuz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.nanxinkj.top/Article/details/gt2dbcvafbj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zdqjudy.top/Article/details/gt2fuajfmta.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sufxvd.cn/Article/details/gt2xigqydup.html

[U03] Py：加载 .env 配置
来源：http://dali.xylfe.cn/Article/details/gt2iamrsikj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gogol.net.cn/Article/details/gt2jaovoujs.html

[U04] Py：变量调试打印
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fcehcwyz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.redwolf501.top/Article/details/gt2aigoigbf.html

[U05] Py：列表去重且保序
来源：http://dali.cashguo.top/Article/details/gt2wlptxbmb.html

list(dict.fromkeys(arr))
来源：http://dali.jianghu66.top/Article/details/gt2jhcpxavl.html

[U06] Py：合并两个字典
来源：http://dali.yanxiufei.cn/Article/details/gt2cbriiadh.html

{**a, **b}
来源：http://dali.zhongyouzk.top/Article/details/gt2xgkgrruo.html

[U07] Py：反转字典键值
来源：http://dali.ydzc1.top/Article/details/gt2mxzclnns.html

{v: k for k, v in d.items()}
来源：http://dali.chenzaomai.com/Article/details/gt2fbxjawcd.html

[U08] Py：展平二维列表
来源：http://dali.snrcjt.cn/Article/details/gt2afpguabl.html

[y for x in nested for y in x]
来源：http://dali.sxryk.cn/Article/details/gt2htcsgxab.html

[U09] Py：字典取最大值的键
来源：http://dali.fzhhl.top/Article/details/gt2odauxlrt.html

max(d, key=d.get)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cpkduttm.html

[U10] Py：按值排序字典
来源：http://dali.hongshengwenyu.top/Article/details/gt2rpkejfyj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gotoacloud.top/Article/details/gt2rwbrajro.html

[U11] Py：生成器表达式
来源：http://dali.sweek.top/Article/details/gt2okcyjyim.html

(x * 2 for x in arr)
来源：http://dali.nwbrower.top/Article/details/gt2qpzsohte.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.dashuyun.cn/Article/details/gt2mxbuthth.html

Counter(arr).most_common(3)
来源：http://dali.hnxiangtu.top/Article/details/gt2twydjzrt.html

[U13] Py：固定长度队列
来源：http://dali.iojbl.cn/Article/details/gt2fwplpajc.html

deque(maxlen=10)
来源：http://dali.wangdashe.top/Article/details/gt2hivwbzwu.html

[U14] Py：分组收集到列表
来源：http://dali.aizwys.cn/Article/details/gt2zqsixuxc.html

defaultdict(list)
来源：http://dali.fengsongda.top/Article/details/gt2ujrhwsjb.html

[U15] Py：高精度计时
来源：http://dali.gzhubu.top/Article/details/gt2oortmncc.html

t = time.perf_counter()
来源：http://dali.birdmap.top/Article/details/gt2pmyqqtmz.html

[U16] Py：命令行参数解析
来源：http://dali.cucudq.cn/Article/details/gt2janvjfis.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.sweek.top/Article/details/gt2yxnnubqk.html

[U17] Py：初始化日志
来源：http://dali.0kj1m.cn/Article/details/gt2fkkjbqsd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.redwolf501.top/Article/details/gt2eyepwmds.html

[U18] Py：预编译正则
来源：http://dali.yongpay.top/Article/details/gt2mjcahyac.html

pat = re.compile(r"\d+")
来源：http://dali.smart0.xyz/Article/details/gt2jicvqruu.html

[U19] Py：正则替换带回调
来源：http://dali.andypj.xyz/Article/details/gt2vsjlnwyt.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.mhx1999.top/Article/details/gt2yzwrpodu.html

[U20] Py：缓存函数结果
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2odsrdkmo.html

@functools.lru_cache(maxsize=None)
来源：http://dali.dashuyun.cn/Article/details/gt2gkysgsxf.html

[U21] Py：自定义上下文管理器
来源：http://dali.jyoumei.cn/Article/details/gt2eqctgpwx.html

@contextlib.contextmanager
来源：http://dali.fzhhl.top/Article/details/gt2lplbpoya.html

[U22] Py：矩阵转置
来源：http://dali.nwbrower.top/Article/details/gt2zshpkesd.html

list(zip(*m))
来源：http://dali.wangshuangyany.cn/Article/details/gt2izuzqvdj.html

[U23] Py：分块读取大文件
来源：http://dali.gogol.net.cn/Article/details/gt2eltkcxnl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.chenzaomai.com/Article/details/gt2ouqjpdgx.html

[U24] Py：路径操作
来源：http://dali.hnxiangtu.top/Article/details/gt2holkjbrw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.fengsongda.top/Article/details/gt2qxdxselj.html

[U25] Py：CSV 按字典读
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jrbfoamx.html

csv.DictReader(f)
来源：http://dali.wangdashe.top/Article/details/gt2rpofhlcr.html

[U26] Py：并发下载
来源：http://dali.feifeiyinyue.top/Article/details/gt2vpfnlfpk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yuxming.cn/Article/details/gt2ncbpzyvh.html

[U27] Py：异步 HTTP
来源：http://dali.hongshengwenyu.top/Article/details/gt2xuxknurm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xziqi.cn/Article/details/gt2vtbuixdi.html

[U28] Py：类型别名
来源：http://dali.haohaochexian.top/Article/details/gt2wiarnogl.html

UserId = int
来源：http://dali.yuxming.cn/Article/details/gt2lkwctwig.html

[U29] Py：属性校验
来源：http://dali.sysykeji.top/Article/details/gt2lyahwbkq.html

@property 与 @x.setter 配合
来源：http://dali.sweek.top/Article/details/gt2aegflxbs.html

[U30] Py：数据类
来源：http://dali.ivvv.top/Article/details/gt2hfjfcpwc.html

@dataclass(slots=True)
来源：http://dali.hnxiangtu.top/Article/details/gt2fylojrpa.html

[U31] Py：单测
来源：http://dali.xinyue.icu/Article/details/gt2qtcoupdd.html

python -m pytest -q
来源：http://dali.feifeiyinyue.top/Article/details/gt2zozhcvxk.html

[U32] Py：代码格式化
来源：http://dali.hammf.cn/Article/details/gt2rtxrmnqe.html

ruff format . && ruff check --fix .
来源：http://dali.gotoacloud.top/Article/details/gt2zolpbgyu.html

[U33] Py：打包发布
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nnxksqbk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.iojbl.cn/Article/details/gt2exonrzrt.html

[U34] Py：判断编码
来源：http://dali.guannengcc.top/Article/details/gt2epltouul.html

chardet.detect(raw)
来源：http://dali.cucudq.cn/Article/details/gt2qlppyydc.html

[U35] Py：发送邮件
来源：http://dali.svipenyu.cn/Article/details/gt2cskzijoy.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.sweek.top/Article/details/gt2cfugrxto.html

[U36] Py：定时任务
来源：http://dali.yuxming.cn/Article/details/gt2sgnujriw.html

schedule.every(10).minutes.do(job)
来源：http://dali.shuidangran.top/Article/details/gt2xvvijwit.html

[U37] Py：读写 Excel
来源：http://dali.yonumen.top/Article/details/gt2lkwvenpe.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.gzhubu.top/Article/details/gt2laioeyyr.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhoulong.xyz/Article/details/gt2yqknacjj.html

Path(__file__).resolve().parent
来源：http://dali.cdnleiting.top/Article/details/gt2qrilcovc.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhiwuduotai.top/Article/details/gt2knqhlsiy.html

sys.stdout.isatty()
来源：http://dali.yongpay.top/Article/details/gt2kiqtrrfi.html

[U40] Py：打印到标准错误
来源：http://dali.jqgufenzy.top/Article/details/gt2vhqdqwxs.html

print("err", file=sys.stderr)
来源：http://dali.snrcjt.cn/Article/details/gt2abjituvm.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.wangdashe.top/Article/details/gt2bmddevrt.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhixingplan.top/Article/details/gt2rjnvjgdb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yongpay.top/Article/details/gt2thutoiiz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.havefunace.top/Article/details/gt2tmkotpsq.html

[U43] PHP：声明命名空间
来源：http://dali.zhengqikj.top/Article/details/gt2yrcijehs.html

namespace App\Http;
来源：http://dali.jianghu66.top/Article/details/gt2aklwnjxs.html

[U44] PHP：开启严格类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fsjmlqmh.html

declare(strict_types=1);
来源：http://dali.guowangkeji.top/Article/details/gt2hmljzqsa.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2netwjdlm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gt2qdvfeoyd.html

[U46] PHP：可空类型
来源：http://dali.9152youxi.cn/Article/details/gt2lwcaenzj.html

?string $name = null
来源：http://dali.pycfn.com/Article/details/gt2iteuavkr.html

[U47] PHP：联合类型
来源：http://dali.gaohongyu789.top/Article/details/gt2ktdlmuve.html

int|string $id
来源：http://dali.tianlin.xyz/Article/details/gt2gjzynpja.html

[U48] PHP：纯枚举
来源：http://dali.haohaochexian.top/Article/details/gt2gsulhcir.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jyoumei.cn/Article/details/gt2kpagpwsz.html

[U49] PHP：只读属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ymiznffq.html

public readonly string $name
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xwypjrzl.html

[U50] PHP：构造器属性提升
来源：http://dali.sxryk.cn/Article/details/gt2ccbmlnuy.html

public function __construct(private int $id) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2xggszkfp.html

[U51] PHP：数组解构
来源：http://dali.zhongyouzk.top/Article/details/gt2nirwlehk.html

[$a, $b] = $arr;
来源：http://dali.havefunace.top/Article/details/gt2jsotzkpy.html

[U52] PHP：箭头函数
来源：http://dali.jqgufenzy.top/Article/details/gt2hlhfwlrz.html

$double = fn($x) => $x * 2;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zxvbpkpw.html

[U53] PHP：空合并运算符
来源：http://dali.shzxlz.cn/Article/details/gt2ncrzemvg.html

$v = $a ?? $b ?? "default";
来源：http://dali.xuanzx.com/Article/details/gt2djetufzz.html

[U54] PHP：空安全调用
来源：http://dali.tianlin.xyz/Article/details/gt2chtrffuv.html

$obj?->method()
来源：http://dali.nanxuanxn.top/Article/details/gt2baydhfdv.html

[U55] PHP：match 表达式
来源：http://dali.zhiwuduotai.top/Article/details/gt2gmukaczm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.aibaodan.cn/Article/details/gt2gtfyrjfv.html

[U56] PHP：命名参数
来源：http://dali.cucudq.cn/Article/details/gt2ykptiwqj.html

f(a: 1, b: 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2celqykkm.html


<!-- 参考信息 -->