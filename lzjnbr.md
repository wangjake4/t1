代发 wailian999

#include <iostream>
来源：http://dali.wangshuangyany.cn/Article/details/gtpvfdjmhw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xinyue.icu/Article/details/gtjelxbgmi.html

[S32] C++：字符串
来源：http://dali.yj20258888.top/Article/details/gtixnrrpbs.html

std::string s = "hi";  s += "!";
来源：http://dali.smart0.xyz/Article/details/gtnpesueag.html

[S33] C++：vector 增删
来源：http://dali.316326.xyz/Article/details/gtlkehklnh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yuxming.cn/Article/details/gtphnuwjla.html

[S34] C++：遍历 vector
来源：http://dali.gaohongyu789.top/Article/details/gtkqacgtej.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yanxiufei.cn/Article/details/gtddnvvuiv.html

[S35] C++：map
来源：http://dali.sufxvd.cn/Article/details/gtrahmufuz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtynmscfri.html

[S36] C++：unordered_map
来源：http://dali.redwolf501.top/Article/details/gtuzywzugy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gtnbgbqgvm.html

[S37] C++：set
来源：http://dali.redwolf501.top/Article/details/gtdavwnfpp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhengqikj.top/Article/details/gtumhwoxoy.html

[S38] C++：排序
来源：http://dali.shzxlz.cn/Article/details/gtzlmvwbgj.html

std::sort(v.begin(), v.end());
来源：http://dali.sufxvd.cn/Article/details/gtnfjvjewz.html

[S39] C++：自定义比较器排序
来源：http://dali.hnxiangtu.top/Article/details/gtokipsjxo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.c1oappe.top/Article/details/gtgslqdvok.html

[S40] C++：查找元素
来源：http://dali.cucudq.cn/Article/details/gtitaaubtl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.birdmap.top/Article/details/gtchxegnvb.html

[S41] C++：类与构造函数
来源：http://dali.jinqigfzy.top/Article/details/gtenpxabvl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yuanzhike.top/Article/details/gtcjueluok.html

[S42] C++：继承与虚函数
来源：http://dali.meibo888.top/Article/details/gtaqwyjzcj.html

class B : public Base { public: void f() override {} };
来源：http://dali.gogol.net.cn/Article/details/gtqkxohtzo.html

[S43] C++：智能指针
来源：http://dali.cdnleiting.top/Article/details/gthitgpago.html

auto p = std::make_unique<int>(5);
来源：http://dali.yuxming.cn/Article/details/gtbrltllaq.html

[S44] C++：引用传参
来源：http://dali.quarkkingdee.top/Article/details/gtflnrmlbf.html

void inc(int &x) { ++x; }
来源：http://dali.zhixingplan.top/Article/details/gtwppyupgw.html

[S45] C++：lambda
来源：http://dali.hywenlv.cn/Article/details/gtllbaewjo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sufxvd.cn/Article/details/gtedgndnyf.html

[S46] C++：函数模板
来源：http://dali.zhoulong.xyz/Article/details/gtjtnuqcbl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zdqjudy.top/Article/details/gtopbqbbss.html

[S47] C++：结构化绑定遍历
来源：http://dali.haohaochexian.top/Article/details/gtvxvcgokf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ydzc1.top/Article/details/gtmklfwhix.html

[S48] C++：逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gtaesxyaya.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tian-w.cn/Article/details/gtkmkgnqwm.html

while (std::getline(in, line)) { }
来源：http://dali.daria6918.cn/Article/details/gtryineznh.html

[S49] C++：写文件
来源：http://dali.vqdsnc.cn/Article/details/gtnthokpxi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.0kj1m.cn/Article/details/gtqixjilse.html

[S50] C++：格式化数字
来源：http://dali.hammf.cn/Article/details/gtjmjmpxqt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gtgkarxwcz.html

[S51] C++：显式类型转换
来源：http://dali.hywenlv.cn/Article/details/gtasvygfug.html

static_cast<double>(a) / b
来源：http://dali.yuanzhike.top/Article/details/gtlltnsjtz.html

[S52] C++：const 与 noexcept
来源：http://dali.cdnleiting.top/Article/details/gtmoiuwept.html

int size() const noexcept { return n_; }
来源：http://dali.aizwys.cn/Article/details/gtnpfxmzui.html

[S53] C++：移动语义
来源：http://dali.jianghu66.top/Article/details/gtxwlzgjia.html

std::vector<int> w = std::move(v);
来源：http://dali.xuetiantiany.cn/Article/details/gtscdquzhx.html

[S54] C++：异常处理
来源：http://dali.jianghu66.top/Article/details/gtalyqdksg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmhxeuext.html

[S55] C++：结构化绑定
来源：http://dali.shuidangran.top/Article/details/gtfflhfcpq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xziqi.cn/Article/details/gtcoegidlf.html

[S56] C++：optional
来源：http://dali.snrcjt.cn/Article/details/gtaebutvse.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hfpthk.cn/Article/details/gtywsysgfn.html

[S57] C++：编译期常量
来源：http://dali.jiagoushi.top/Article/details/gtsvgoudyx.html

constexpr int N = 10;
来源：http://dali.quarkkingdee.top/Article/details/gtiggbakzt.html

[S58] C++：命名空间
来源：http://dali.chenlongwang.top/Article/details/gttbhkgpbb.html

namespace ns { int f() { return 1; } }
来源：http://dali.aizwys.cn/Article/details/gtebolqsuw.html

[S59] C++：静态断言
来源：http://dali.xuetiantiany.cn/Article/details/gtishsqpno.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shuidangran.top/Article/details/gtpxsossky.html

[S60] C++：遍历并删除元素
来源：http://dali.nanxuanxn.top/Article/details/gtxfpvweaj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xziqi.cn/Article/details/gtbzwboisl.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtctodxixg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.fzhhl.top/Article/details/gthfwxodtb.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtktaiwmrm.html

[T01] Kotlin：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjeslwbzr.html

println("Hello")
来源：http://dali.dashuyun.cn/Article/details/gtberkubua.html

[T02] Kotlin：变量
来源：http://dali.yj20258.top/Article/details/gthmvdzxib.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.bjfxy.top/Article/details/gtzvvzeoux.html

[T03] Kotlin：字符串模板
来源：http://dali.jlsjyb.cn/Article/details/gtziwhjhva.html

"值: $b"
来源：http://dali.zhixingplan.top/Article/details/gtchlxogia.html

[T04] Kotlin：空安全
来源：http://dali.aibaodan.cn/Article/details/gtvmxwhsjc.html

val n: String? = null;  n?.length
来源：http://dali.cheryme.top/Article/details/gtujwkzdsa.html

[T05] Kotlin：when 表达式
来源：http://dali.cucudq.cn/Article/details/gtgexqfdxw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.nanxinkj.top/Article/details/gtwismdfte.html

[T06] Kotlin：集合映射
来源：http://dali.guowangkeji.top/Article/details/gteczcsseo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jiagoushi.top/Article/details/gtgpsxnzzp.html

[T07] Kotlin：集合过滤
来源：http://dali.birdmap.top/Article/details/gtpvfkqpmo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.andypj.xyz/Article/details/gteawhkdyo.html

[T08] Kotlin：数据类
来源：http://dali.guannengcc.top/Article/details/gttgxkohal.html

data class User(val name: String, val age: Int)
来源：http://dali.cqqwz.cn/Article/details/gtxbtavkms.html

[T09] Kotlin：扩展函数
来源：http://dali.aibaodan.cn/Article/details/gtngsbvijl.html

fun String.exclaim() = this + "!"
来源：http://dali.wangdashe.top/Article/details/gtulsnlxoc.html

[T10] Kotlin：默认参数
来源：http://dali.yj202588.top/Article/details/gtjbevxsxw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hammf.cn/Article/details/gtxtpjwsmg.html

[T11] Kotlin：协程
来源：http://dali.shzxlz.cn/Article/details/gtlnxnxpyi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtizcgrbio.html

[T12] Kotlin：解构声明
来源：http://dali.shanyushiyangkeji.top/Article/details/gttiytsrud.html

val (a, b) = Pair(1, 2)
来源：http://dali.ybcxt.top/Article/details/gtjjowfizl.html

[T13] Kotlin：只读 Map
来源：http://dali.aizwys.cn/Article/details/gtcmuzfgcx.html

val m = mapOf("a" to 1)
来源：http://dali.nanxuanxn.top/Article/details/gtmeocwjmn.html

[T14] Kotlin：循环
来源：http://dali.ydzc1.top/Article/details/gtvapbxnev.html

for (i in 1..10) println(i)
来源：http://dali.xuetiantiany.cn/Article/details/gtitmmwerg.html

[T15] Kotlin：接口
来源：http://dali.snrcjt.cn/Article/details/gtshfelpru.html

interface Shape { fun area(): Double }
来源：http://dali.xziqi.cn/Article/details/gtvrumuhkv.html

[T16] Swift：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtznjngjrv.html

print("Hello")
来源：http://dali.zhixingplan.top/Article/details/gtoujbklou.html

[T17] Swift：变量与常量
来源：http://dali.shzxlz.cn/Article/details/gtpjuyddwu.html

var a = 1;  let b = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtzfkfcuxf.html

[T18] Swift：字符串插值
来源：http://dali.tian-w.cn/Article/details/gtukusvfou.html

"值: \(b)"
来源：http://dali.yangfankeji.com/Article/details/gtxthcwfvr.html

[T19] Swift：可选绑定
来源：http://dali.yongpay.top/Article/details/gtnsmgllwl.html

if let n = opt { print(n) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqgflytou.html

[T20] Swift：数组操作
来源：http://dali.jiagoushi.top/Article/details/gtctwthjai.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jlsjyb.cn/Article/details/gtxbnhpaqt.html

[T21] Swift：遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtmvzprllu.html

for x in a { print(x) }
来源：http://dali.jyoumei.cn/Article/details/gtkjzumccy.html

[T22] Swift：字典
来源：http://dali.xinyue.icu/Article/details/gtxgqajvfk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yanxiufei.cn/Article/details/gtthjhtyct.html

[T23] Swift：函数
来源：http://dali.0kj1m.cn/Article/details/gtprkafwpp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hnqzz.top/Article/details/gthmjolpoo.html

[T24] Swift：闭包
来源：http://dali.xuetiantiany.cn/Article/details/gtwnytpfgt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yj20258.top/Article/details/gttehwpyal.html

[T25] Swift：结构体
来源：http://dali.jinqigufen.top/Article/details/gtaxkcjuum.html

struct P { var x: Int }
来源：http://dali.chenzaomai.com/Article/details/gtqfvaplgk.html

[T26] Swift：类与重写
来源：http://dali.sysykeji.top/Article/details/gticxmfyev.html

class A: Base { override func f() {} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxiwcbcuh.html

[T27] Swift：错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyrbjzwew.html

do { try f() } catch { print(error) }
来源：http://dali.jinqigfzy.top/Article/details/gtbjwepekt.html

[T28] Swift：枚举
来源：http://dali.shangyingyoupin.top/Article/details/gtiwrwyiww.html

enum Color { case red, green }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtitjcvrtx.html

[T29] Swift：guard 提前返回
来源：http://dali.jinqigfzy.top/Article/details/gtdbvuxzsf.html

guard let x = opt else { return }
来源：http://dali.cucudq.cn/Article/details/gtyserfzdq.html

[T30] Swift：协议
来源：http://dali.dashuyun.cn/Article/details/gtghtgchjh.html

protocol Shape { func area() -> Double }
来源：http://dali.gotoacloud.top/Article/details/gtwybbproo.html

[T31] Lua：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtwrrwqdgy.html

print("Hello")
来源：http://dali.aibaodan.cn/Article/details/gtrwcvvbap.html

[T32] Lua：局部变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtomilamvf.html

local a = 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjhhaigd.html

[T33] Lua：表（数组）
来源：http://dali.zhixingplan.top/Article/details/gtjtebjxaq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.aibaodan.cn/Article/details/gttmdorjry.html

[T34] Lua：遍历表
来源：http://dali.jqgfzy.top/Article/details/gtqfbuceko.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gaohongyu789.top/Article/details/gtkyvwnkpq.html

[T35] Lua：字典表
来源：http://dali.c1oappe.top/Article/details/gtugcximdn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gtyplzlbyn.html

[T36] Lua：函数
来源：http://dali.jinqigfzy.top/Article/details/gtzhcmmevx.html

function add(a, b) return a + b end
来源：http://dali.chenlongwang.top/Article/details/gtpmxczeuv.html

[T37] Lua：字符串拼接
来源：http://dali.ivvv.top/Article/details/gtptowlhby.html

"a" .. "b"
来源：http://dali.nanxuanxn.top/Article/details/gtvuslsvyk.html

[T38] Lua：条件
来源：http://dali.dianchejie.cn/Article/details/gtxgkoxgbi.html

if x > 0 then print("正") end
来源：http://dali.yangfankeji.com/Article/details/gtlknzeqfv.html

[T39] Lua：模式匹配
来源：http://dali.gotoacloud.top/Article/details/gtrtxjuajg.html

string.find(s, "%d+")
来源：http://dali.fzhhl.top/Article/details/gtctlpmqeh.html

[T40] Lua：元表
来源：http://dali.cdnleiting.top/Article/details/gticuajazb.html

setmetatable({}, { __index = base })
来源：http://dali.xuetiantiany.cn/Article/details/gtjjltapsn.html

[T41] Perl：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtthowslte.html

print "Hello\n";
来源：http://dali.tanke756.top/Article/details/gtpbvoszje.html

[T42] Perl：变量类型
来源：http://dali.yj20258888.top/Article/details/gtgwmozfxg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yueranfly.top/Article/details/gtfuyjypfh.html

[T43] Perl：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gtxrlqurvt.html

"值: $a"
来源：http://dali.yj20258.top/Article/details/gtoivnmcdl.html

[T44] Perl：条件
来源：http://dali.fengsongda.top/Article/details/gtvseqizcp.html

if ($a > 0) { print "正"; }
来源：http://dali.hnqzz.top/Article/details/gtwhcyroyw.html

[T45] Perl：数组遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyllyqasz.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gtosdamkkr.html

[T46] Perl：哈希操作
来源：http://dali.yj20258888.top/Article/details/gtshrweyxo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hfpthk.cn/Article/details/gtbxnabdsn.html

[T47] Perl：正则捕获
来源：http://dali.ydzc1.top/Article/details/gtgrcvccwc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zdqjudy.top/Article/details/gtnfrekwcz.html

[T48] Perl：正则替换
来源：http://dali.hammf.cn/Article/details/gtkogkypqn.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gtjhjcaioe.html

[T49] Perl：函数
来源：http://dali.zhiwuduotai.top/Article/details/gtgezxxosy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gaohongyu789.top/Article/details/gtrgmalqfq.html

[T50] Perl：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gthtlkpscy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hywenlv.cn/Article/details/gtxixnajiu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zdqjudy.top/Article/details/gtzbgoqabb.html

[T51] Scala：Hello World
来源：http://dali.fengsongda.top/Article/details/gtfktnrvtg.html

println("Hello")
来源：http://dali.cucudq.cn/Article/details/gtrgdrjjds.html

[T52] Scala：变量
来源：http://dali.shangyingyoupin.top/Article/details/gtkqjiskqg.html

val a = 1;  var b = 2
来源：http://dali.0kj1m.cn/Article/details/gtzfgperlu.html

[T53] Scala：字符串插值
来源：http://dali.yangfankeji.com/Article/details/gtnlbppzkh.html

s"值: $b"
来源：http://dali.shanyushiyangtech.top/Article/details/gtdihbzfjm.html

[T54] Scala：集合映射
来源：http://dali.bjfxy.top/Article/details/gtvrrbpgyu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.tanke756.top/Article/details/gtvqouiyaa.html

[T55] Scala：集合过滤
来源：http://dali.aibaodan.cn/Article/details/gtgvtyzfxb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.meibo888.top/Article/details/gtrvkycwjc.html

[T56] Scala：样例类
来源：http://dali.tianlin.xyz/Article/details/gtsulblipd.html

case class User(name: String, age: Int)
来源：http://dali.zdqjudy.top/Article/details/gtbuuzuuka.html

[T57] Scala：模式匹配
来源：http://dali.nanxinkj.top/Article/details/gtdeaclkej.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.pycfn.com/Article/details/gtrtxtynhj.html

[T58] Scala：函数定义
来源：http://dali.chenlongwang.top/Article/details/gtqqoggthz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.guowangkeji.top/Article/details/gtgjyxoulc.html

[T59] Scala：循环
来源：http://dali.chenlongwang.top/Article/details/gtzzvmoymd.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinqigfzy.top/Article/details/gtqdnxtqli.html

[T60] Scala：折叠
来源：http://dali.tianlin.xyz/Article/details/gtvhiingry.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ybcxt.top/Article/details/gtynneqbwz.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtjdfcwrpd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hfpthk.cn/Article/details/gtalnckgbm.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtjymgifhw.html

[U01] Py：创建虚拟环境
来源：http://dali.cdnleiting.top/Article/details/gtjdwafjme.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.smart0.xyz/Article/details/gtaqrxsxep.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yuxming.cn/Article/details/gttzkctymk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jianghu66.top/Article/details/gtlymkanxa.html

[U03] Py：加载 .env 配置
来源：http://dali.hywenlv.cn/Article/details/gtoukhrqxq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ppjwa.cn/Article/details/gtuijccgeg.html

[U04] Py：变量调试打印
来源：http://dali.xuanzx.com/Article/details/gtopawckev.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zdqjudy.top/Article/details/gtoxyirbeo.html

[U05] Py：列表去重且保序
来源：http://dali.gotoacloud.top/Article/details/gteihrkxbf.html

list(dict.fromkeys(arr))
来源：http://dali.xuetiantiany.cn/Article/details/gtnsybpgzi.html

[U06] Py：合并两个字典
来源：http://dali.jyoumei.cn/Article/details/gtutocwxoh.html

{**a, **b}
来源：http://dali.meibo888.top/Article/details/gtwyzybzfq.html

[U07] Py：反转字典键值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtocxyidmb.html

{v: k for k, v in d.items()}
来源：http://dali.hywenlv.cn/Article/details/gtgryixkyp.html

[U08] Py：展平二维列表
来源：http://dali.yj20258.top/Article/details/gthumozxvf.html

[y for x in nested for y in x]
来源：http://dali.yangfankeji.com/Article/details/gtrvxashiw.html

[U09] Py：字典取最大值的键
来源：http://dali.jinqigfzy.top/Article/details/gteujkkqkq.html

max(d, key=d.get)
来源：http://dali.c1oappe.top/Article/details/gtbgzedhkg.html

[U10] Py：按值排序字典
来源：http://dali.redwolf501.top/Article/details/gtzipbbivv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yvedp.cn/Article/details/gtqlzsalnn.html

[U11] Py：生成器表达式
来源：http://dali.yvedp.cn/Article/details/gtjiwuzfvc.html

(x * 2 for x in arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtgfowxppy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shangyingyoupin.top/Article/details/gtklsrnlbu.html

Counter(arr).most_common(3)
来源：http://dali.yonumen.top/Article/details/gtgemticah.html

[U13] Py：固定长度队列
来源：http://dali.nanxuanxn.top/Article/details/gtazghlyog.html

deque(maxlen=10)
来源：http://dali.hywenlv.cn/Article/details/gtcrcvyxja.html

[U14] Py：分组收集到列表
来源：http://dali.zhoulong.xyz/Article/details/gtljoqvqum.html

defaultdict(list)
来源：http://dali.nanxinkj.top/Article/details/gtjhivtvic.html

[U15] Py：高精度计时
来源：http://dali.quarkkingdee.top/Article/details/gtcymnzbxy.html

t = time.perf_counter()
来源：http://dali.wangdashe.top/Article/details/gtetszaptj.html

[U16] Py：命令行参数解析
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxuzuxlu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shangyingyoupin.top/Article/details/gtrssxtnxd.html

[U17] Py：初始化日志
来源：http://dali.tianlin.xyz/Article/details/gtonelwyzo.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jinqigfzy.top/Article/details/gtvemcqhse.html

[U18] Py：预编译正则
来源：http://dali.quarkkingdee.top/Article/details/gtkyvycwpr.html

pat = re.compile(r"\d+")
来源：http://dali.yueranfly.top/Article/details/gtcfaagtii.html

[U19] Py：正则替换带回调
来源：http://dali.hammf.cn/Article/details/gtvpnklnec.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.dashuyun.cn/Article/details/gtpfqckuzk.html

[U20] Py：缓存函数结果
来源：http://dali.yuanzhike.top/Article/details/gtvphpjohv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.gotoacloud.top/Article/details/gtcuxzxsxa.html

[U21] Py：自定义上下文管理器
来源：http://dali.vqdsnc.cn/Article/details/gtmaifqdoi.html

@contextlib.contextmanager
来源：http://dali.fengsongda.top/Article/details/gtitwncgot.html

[U22] Py：矩阵转置
来源：http://dali.nanxuanxn.top/Article/details/gteucvpmez.html

list(zip(*m))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnaazovro.html

[U23] Py：分块读取大文件
来源：http://dali.c1oappe.top/Article/details/gtpvmaaswn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yj202588.top/Article/details/gtmufxqkzy.html

[U24] Py：路径操作
来源：http://dali.ivvv.top/Article/details/gtfmuystyk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.kuanghao11.cn/Article/details/gtmpzwcvvz.html

[U25] Py：CSV 按字典读
来源：http://dali.hfpthk.cn/Article/details/gtcgdymbrj.html

csv.DictReader(f)
来源：http://dali.hysaishi.cn/Article/details/gtfgyuwhhp.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gtmahsgscf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.sxryk.cn/Article/details/gttctxdvto.html

[U27] Py：异步 HTTP
来源：http://dali.cqqwz.cn/Article/details/gtihiyqqpc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.havefunace.top/Article/details/gtspawprkf.html

[U28] Py：类型别名
来源：http://dali.ppjwa.cn/Article/details/gtllmlvmlp.html

UserId = int
来源：http://dali.quarkkingdee.top/Article/details/gtueagpsqi.html

[U29] Py：属性校验
来源：http://dali.hfpthk.cn/Article/details/gtiltzlqrb.html

@property 与 @x.setter 配合
来源：http://dali.jinyuanbaomall.cn/Article/details/gttllnaean.html

[U30] Py：数据类
来源：http://dali.ydzc1.top/Article/details/gtnmjcbhka.html

@dataclass(slots=True)
来源：http://dali.ivvv.top/Article/details/gttkzgrarr.html

[U31] Py：单测
来源：http://dali.jqgufenzy.top/Article/details/gtxjjgsjsw.html

python -m pytest -q
来源：http://dali.gotoacloud.top/Article/details/gtkpnxpnpy.html

[U32] Py：代码格式化
来源：http://dali.wangdashe.top/Article/details/gtcohljfcs.html

ruff format . && ruff check --fix .
来源：http://dali.c1oappe.top/Article/details/gtpjikzrdx.html

[U33] Py：打包发布
来源：http://dali.yueranfly.top/Article/details/gtukoprpsi.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cheryme.top/Article/details/gtkucipmmi.html

[U34] Py：判断编码
来源：http://dali.svipenyu.cn/Article/details/gtltdldyts.html

chardet.detect(raw)
来源：http://dali.pycfn.com/Article/details/gtbtbeqeme.html

[U35] Py：发送邮件
来源：http://dali.zhengqikj.top/Article/details/gtvdhkuwgl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.svipenyu.cn/Article/details/gtfxbdnifz.html

[U36] Py：定时任务
来源：http://dali.shanyushiyangtech.top/Article/details/gtfciqbucq.html

schedule.every(10).minutes.do(job)
来源：http://dali.daria6918.cn/Article/details/gtsovitzjp.html

[U37] Py：读写 Excel
来源：http://dali.jinghuilouyu.cn/Article/details/gttnzgfpeg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.c1oappe.top/Article/details/gtgxsxebga.html

[U38] Py：获取脚本所在目录
来源：http://dali.yanxiufei.cn/Article/details/gtmocnxrik.html

Path(__file__).resolve().parent
来源：http://dali.jinqigfzy.top/Article/details/gtgspmwjjn.html

[U39] Py：判断是否在交互环境
来源：http://dali.quarkkingdee.top/Article/details/gtkaolzmqm.html

sys.stdout.isatty()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwfwmwiw.html

[U40] Py：打印到标准错误
来源：http://dali.snrcjt.cn/Article/details/gtnhaqoulz.html

print("err", file=sys.stderr)
来源：http://dali.xuetiantiany.cn/Article/details/gtqgvdbysm.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.gaohongyu789.top/Article/details/gthxsddgha.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgylkiaqf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ydzc1.top/Article/details/gtwbbgzrqb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jqgufenzy.top/Article/details/gtvvfzdgjj.html

[U43] PHP：声明命名空间
来源：http://dali.gogol.net.cn/Article/details/gtcjmdkqpl.html

namespace App\Http;
来源：http://dali.ybcxt.top/Article/details/gtobbrzvkq.html

[U44] PHP：开启严格类型
来源：http://dali.jinqigfzy.top/Article/details/gtuhxecuaf.html

declare(strict_types=1);
来源：http://dali.yangfankeji.com/Article/details/gtxzyklwok.html

[U45] PHP：类型声明与返回类型
来源：http://dali.andypj.xyz/Article/details/gtlgzyaugx.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gtfazarlet.html

[U46] PHP：可空类型
来源：http://dali.yanxiufei.cn/Article/details/gtmsifeswd.html

?string $name = null
来源：http://dali.yanxiufei.cn/Article/details/gtzihpbkoa.html

[U47] PHP：联合类型
来源：http://dali.tanke756.top/Article/details/gtlwzfjfje.html

int|string $id
来源：http://dali.yvedp.cn/Article/details/gtwdsptlag.html

[U48] PHP：纯枚举
来源：http://dali.cqqwz.cn/Article/details/gtlsddqwth.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yonumen.top/Article/details/gtzzzrpbwt.html

[U49] PHP：只读属性
来源：http://dali.dianchejie.cn/Article/details/gtilisxbow.html

public readonly string $name
来源：http://dali.jinghuilouyu.cn/Article/details/gtjzinmkyj.html

[U50] PHP：构造器属性提升
来源：http://dali.chenjidiqi.icu/Article/details/gtkdjzhzid.html

public function __construct(private int $id) {}
来源：http://dali.jlsjyb.cn/Article/details/gtqusgvhlr.html

[U51] PHP：数组解构
来源：http://dali.gzhubu.top/Article/details/gtoqagpaps.html

[$a, $b] = $arr;
来源：http://dali.quarkkingdee.top/Article/details/gtklaigxkp.html

[U52] PHP：箭头函数
来源：http://dali.yueranfly.top/Article/details/gtqqsbdjip.html

$double = fn($x) => $x * 2;
来源：http://dali.andypj.xyz/Article/details/gtlvciurob.html

[U53] PHP：空合并运算符
来源：http://dali.meibo888.top/Article/details/gtodqeftkq.html

$v = $a ?? $b ?? "default";
来源：http://dali.jqgufenzy.top/Article/details/gtduxscwfp.html

[U54] PHP：空安全调用
来源：http://dali.yj202588.top/Article/details/gtddwaovyn.html

$obj?->method()
来源：http://dali.gogol.net.cn/Article/details/gteldumvuh.html

[U55] PHP：match 表达式
来源：http://dali.tanke756.top/Article/details/gtdnbddxfn.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.iojbl.cn/Article/details/gtvxxcgjtg.html

[U56] PHP：命名参数
来源：http://dali.jqgfzy.top/Article/details/gtqadddssk.html

f(a: 1, b: 2)
来源：http://dali.nanxuanxn.top/Article/details/gtcmppprmx.html


<!-- 参考信息 -->