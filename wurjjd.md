代发 wailian999

#include <iostream>
来源：http://dali.zhixingplan.top/Article/details/gtupbpjxeq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.dianchejie.cn/Article/details/gtjveehulh.html

[S32] C++：字符串
来源：http://dali.tian-w.cn/Article/details/gteermeepz.html

std::string s = "hi";  s += "!";
来源：http://dali.tian-w.cn/Article/details/gtozzthkbo.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gtilbqydeu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yangfankeji.com/Article/details/gtanyscrba.html

[S34] C++：遍历 vector
来源：http://dali.redwolf501.top/Article/details/gtohgaotym.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.pengpengdd.cyou/Article/details/gtlmlwyfdn.html

[S35] C++：map
来源：http://dali.jinqigfzy.top/Article/details/gthqrbhize.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ivvv.top/Article/details/gtbfzrwfzh.html

[S36] C++：unordered_map
来源：http://dali.guannengcc.top/Article/details/gtgbuzvcod.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gtanvnmure.html

[S37] C++：set
来源：http://dali.guowangkeji.top/Article/details/gthnfqdpdh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nanxinkj.top/Article/details/gtryyrvmtp.html

[S38] C++：排序
来源：http://dali.daria6918.cn/Article/details/gtsqcgthky.html

std::sort(v.begin(), v.end());
来源：http://dali.cqqwz.cn/Article/details/gtzleaywsg.html

[S39] C++：自定义比较器排序
来源：http://dali.jyoumei.cn/Article/details/gtrnjvlqxz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jianghu66.top/Article/details/gtzvtufaeb.html

[S40] C++：查找元素
来源：http://dali.jinqigufen.top/Article/details/gtzehbqivm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yuxming.cn/Article/details/gtnmleayas.html

[S41] C++：类与构造函数
来源：http://dali.iojbl.cn/Article/details/gtgpppivct.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jlsjyb.cn/Article/details/gtsojxdtjb.html

[S42] C++：继承与虚函数
来源：http://dali.aibaodan.cn/Article/details/gtfzyuxkoa.html

class B : public Base { public: void f() override {} };
来源：http://dali.nanxuanxn.top/Article/details/gtdcenwheb.html

[S43] C++：智能指针
来源：http://dali.feifeiyinyue.top/Article/details/gtxfzcghnh.html

auto p = std::make_unique<int>(5);
来源：http://dali.aizwys.cn/Article/details/gtnynjfhar.html

[S44] C++：引用传参
来源：http://dali.jiagoushi.top/Article/details/gttynjhfeg.html

void inc(int &x) { ++x; }
来源：http://dali.yuxming.cn/Article/details/gtdupuzike.html

[S45] C++：lambda
来源：http://dali.yanxiufei.cn/Article/details/gtgyfjcxfi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cucudq.cn/Article/details/gtemgmrdij.html

[S46] C++：函数模板
来源：http://dali.pycfn.com/Article/details/gtpunyeoqh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.guannengcc.top/Article/details/gtqkxotuve.html

[S47] C++：结构化绑定遍历
来源：http://dali.9152youxi.cn/Article/details/gtyxvxupmk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinqigufen.top/Article/details/gtzpwcjnwq.html

[S48] C++：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gtaqgifbhk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj20258.top/Article/details/gtndzprpzn.html

while (std::getline(in, line)) { }
来源：http://dali.tanke756.top/Article/details/gtmyubrelz.html

[S49] C++：写文件
来源：http://dali.shanyushiyangtech.top/Article/details/gthjjhdeda.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shuidangran.top/Article/details/gtljbhmtyt.html

[S50] C++：格式化数字
来源：http://dali.snrcjt.cn/Article/details/gtcadoqzzs.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.c1oappe.top/Article/details/gthzhahooo.html

[S51] C++：显式类型转换
来源：http://dali.zhoulong.xyz/Article/details/gtldomnysk.html

static_cast<double>(a) / b
来源：http://dali.svipenyu.cn/Article/details/gtcznjnivl.html

[S52] C++：const 与 noexcept
来源：http://dali.cdnleiting.top/Article/details/gtosdwngso.html

int size() const noexcept { return n_; }
来源：http://dali.pengpengdd.cyou/Article/details/gtqpxeglez.html

[S53] C++：移动语义
来源：http://dali.guannengcc.top/Article/details/gterhzibsg.html

std::vector<int> w = std::move(v);
来源：http://dali.gogol.net.cn/Article/details/gtcjcmsiwl.html

[S54] C++：异常处理
来源：http://dali.0kj1m.cn/Article/details/gtffxmeddj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cqqwz.cn/Article/details/gtclzasdni.html

[S55] C++：结构化绑定
来源：http://dali.sysykeji.top/Article/details/gtfgtvuvlo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.redwolf501.top/Article/details/gtfmcnlepd.html

[S56] C++：optional
来源：http://dali.hnqzz.top/Article/details/gtsitggpoo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.aizwys.cn/Article/details/gtgkcgzmpp.html

[S57] C++：编译期常量
来源：http://dali.zhengqikj.top/Article/details/gtxyxxzfhe.html

constexpr int N = 10;
来源：http://dali.nanxuanxn.top/Article/details/gtasemztvt.html

[S58] C++：命名空间
来源：http://dali.wangshuangyany.cn/Article/details/gtzscduzow.html

namespace ns { int f() { return 1; } }
来源：http://dali.hongshengwenyu.top/Article/details/gthiujcvrd.html

[S59] C++：静态断言
来源：http://dali.hysaishi.cn/Article/details/gtwhdbmgkk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ehwqpu.com/Article/details/gttpxbmjbr.html

[S60] C++：遍历并删除元素
来源：http://dali.cheryme.top/Article/details/gtlvoetqce.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nanxuanxn.top/Article/details/gtsfvktlvc.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtyrweowbd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjfoftwje.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtugwvsyms.html

[T01] Kotlin：Hello World
来源：http://dali.bjfxy.top/Article/details/gtdmucampn.html

println("Hello")
来源：http://dali.yangfankeji.com/Article/details/gtntbyabfb.html

[T02] Kotlin：变量
来源：http://dali.zycfv.cn/Article/details/gttvuorohr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sxryk.cn/Article/details/gtkrhkftua.html

[T03] Kotlin：字符串模板
来源：http://dali.iojbl.cn/Article/details/gtrekjlbmo.html

"值: $b"
来源：http://dali.hfpthk.cn/Article/details/gtngywobke.html

[T04] Kotlin：空安全
来源：http://dali.jqgufenzy.top/Article/details/gtooksdpji.html

val n: String? = null;  n?.length
来源：http://dali.aizwys.cn/Article/details/gtfminvpzt.html

[T05] Kotlin：when 表达式
来源：http://dali.mhx1999.top/Article/details/gtbkjwvorl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cdnleiting.top/Article/details/gtmpstzcpj.html

[T06] Kotlin：集合映射
来源：http://dali.jinghuilouyu.cn/Article/details/gtphztvllf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gtpugvcgrn.html

[T07] Kotlin：集合过滤
来源：http://dali.guowangkeji.top/Article/details/gtjmlhludd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.pycfn.com/Article/details/gtclpbaler.html

[T08] Kotlin：数据类
来源：http://dali.nanxuanxn.top/Article/details/gtfirjxlob.html

data class User(val name: String, val age: Int)
来源：http://dali.sufxvd.cn/Article/details/gtypwdcssa.html

[T09] Kotlin：扩展函数
来源：http://dali.xuetiantiany.cn/Article/details/gtrogyyaew.html

fun String.exclaim() = this + "!"
来源：http://dali.aibaodan.cn/Article/details/gtdhnuqkqz.html

[T10] Kotlin：默认参数
来源：http://dali.fzhhl.top/Article/details/gtygdbqdvy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrwlvpqkf.html

[T11] Kotlin：协程
来源：http://dali.yanxiufei.cn/Article/details/gtewmylyuo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jiagoushi.top/Article/details/gtbcudpvcj.html

[T12] Kotlin：解构声明
来源：http://dali.zhengqikj.top/Article/details/gtxtkpnjdu.html

val (a, b) = Pair(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtfhjvbjul.html

[T13] Kotlin：只读 Map
来源：http://dali.fengsongda.top/Article/details/gtuskdcvhd.html

val m = mapOf("a" to 1)
来源：http://dali.zhongyouzk.top/Article/details/gtntqexstj.html

[T14] Kotlin：循环
来源：http://dali.yueranfly.top/Article/details/gtprkhruhr.html

for (i in 1..10) println(i)
来源：http://dali.havefunace.top/Article/details/gtskajtghc.html

[T15] Kotlin：接口
来源：http://dali.chenlongwang.top/Article/details/gtgidvzkie.html

interface Shape { fun area(): Double }
来源：http://dali.yuanzhike.top/Article/details/gtaxkdzitq.html

[T16] Swift：Hello World
来源：http://dali.xylfe.cn/Article/details/gtwsaeblzp.html

print("Hello")
来源：http://dali.chenzaomai.com/Article/details/gthbvyufzu.html

[T17] Swift：变量与常量
来源：http://dali.shuidangran.top/Article/details/gtnugmbgmh.html

var a = 1;  let b = 2
来源：http://dali.316326.xyz/Article/details/gtfndallxs.html

[T18] Swift：字符串插值
来源：http://dali.bjfxy.top/Article/details/gtpwmfoxpr.html

"值: \(b)"
来源：http://dali.jyoumei.cn/Article/details/gtkpafvwse.html

[T19] Swift：可选绑定
来源：http://dali.cdnleiting.top/Article/details/gtjzxyprdl.html

if let n = opt { print(n) }
来源：http://dali.jqgufenzy.top/Article/details/gtpjmyofni.html

[T20] Swift：数组操作
来源：http://dali.wangshuangyany.cn/Article/details/gtvzxiyjtd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.c1oappe.top/Article/details/gtricknynp.html

[T21] Swift：遍历
来源：http://dali.aibaodan.cn/Article/details/gtwgcxmwuk.html

for x in a { print(x) }
来源：http://dali.yj20258.top/Article/details/gtfshfacyk.html

[T22] Swift：字典
来源：http://dali.jinqigufen.top/Article/details/gtiphhtsfv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.fengsongda.top/Article/details/gtjbpjyylb.html

[T23] Swift：函数
来源：http://dali.hammf.cn/Article/details/gtodxuywqd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmjenworx.html

[T24] Swift：闭包
来源：http://dali.sufxvd.cn/Article/details/gtmhtybjxk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xuanzx.com/Article/details/gtxjgeljuj.html

[T25] Swift：结构体
来源：http://dali.yuanzhike.top/Article/details/gtkbhwtrri.html

struct P { var x: Int }
来源：http://dali.nanxinkj.top/Article/details/gtgbyivgmy.html

[T26] Swift：类与重写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsarotzus.html

class A: Base { override func f() {} }
来源：http://dali.meibo888.top/Article/details/gtxhmxbhqc.html

[T27] Swift：错误处理
来源：http://dali.meibo888.top/Article/details/gtcbzozqul.html

do { try f() } catch { print(error) }
来源：http://dali.yueranfly.top/Article/details/gtyvwovbss.html

[T28] Swift：枚举
来源：http://dali.yanxiufei.cn/Article/details/gtddursvou.html

enum Color { case red, green }
来源：http://dali.redwolf501.top/Article/details/gtmcmcdapk.html

[T29] Swift：guard 提前返回
来源：http://dali.dashuyun.cn/Article/details/gthtrxxhda.html

guard let x = opt else { return }
来源：http://dali.dianchejie.cn/Article/details/gtaqadtsji.html

[T30] Swift：协议
来源：http://dali.hnxiangtu.top/Article/details/gtdndaaual.html

protocol Shape { func area() -> Double }
来源：http://dali.daria6918.cn/Article/details/gtivvghgwd.html

[T31] Lua：Hello World
来源：http://dali.yvedp.cn/Article/details/gtyxismmzh.html

print("Hello")
来源：http://dali.xinyue.icu/Article/details/gtlucsjbpd.html

[T32] Lua：局部变量
来源：http://dali.cashguo.top/Article/details/gtuycedljz.html

local a = 1
来源：http://dali.yj20258.top/Article/details/gtwuyzjsom.html

[T33] Lua：表（数组）
来源：http://dali.gaohongyu789.top/Article/details/gthffyxnzv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.wangdashe.top/Article/details/gthmgawytu.html

[T34] Lua：遍历表
来源：http://dali.zdqjudy.top/Article/details/gtzykxcxmg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.chenzaomai.com/Article/details/gtbsykncxb.html

[T35] Lua：字典表
来源：http://dali.aizwys.cn/Article/details/gtxanjbylr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.iojbl.cn/Article/details/gtqelmrgge.html

[T36] Lua：函数
来源：http://dali.sxryk.cn/Article/details/gtyylqavei.html

function add(a, b) return a + b end
来源：http://dali.jlsjyb.cn/Article/details/gtzxbdjfhg.html

[T37] Lua：字符串拼接
来源：http://dali.gotoacloud.top/Article/details/gtkcrsmnav.html

"a" .. "b"
来源：http://dali.xuetiantiany.cn/Article/details/gtwjkipsfl.html

[T38] Lua：条件
来源：http://dali.c1oappe.top/Article/details/gttmxxzrvf.html

if x > 0 then print("正") end
来源：http://dali.cashguo.top/Article/details/gtnlhpollx.html

[T39] Lua：模式匹配
来源：http://dali.dianchejie.cn/Article/details/gthoqorzmv.html

string.find(s, "%d+")
来源：http://dali.nanxuanxn.top/Article/details/gtztztmufi.html

[T40] Lua：元表
来源：http://dali.gaohongyu789.top/Article/details/gtcfwsgrxs.html

setmetatable({}, { __index = base })
来源：http://dali.chenjidiqi.icu/Article/details/gtzyuxoyyt.html

[T41] Perl：Hello World
来源：http://dali.jianghu66.top/Article/details/gtmiigsfwu.html

print "Hello\n";
来源：http://dali.cucudq.cn/Article/details/gtrouzmcub.html

[T42] Perl：变量类型
来源：http://dali.jqgfzy.top/Article/details/gtdtvnpoyp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.guannengcc.top/Article/details/gtpagfymkj.html

[T43] Perl：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gtovfiwshh.html

"值: $a"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqkybyodu.html

[T44] Perl：条件
来源：http://dali.sxryk.cn/Article/details/gtmdnhpktu.html

if ($a > 0) { print "正"; }
来源：http://dali.hnxiangtu.top/Article/details/gthsqhjilp.html

[T45] Perl：数组遍历
来源：http://dali.jiagoushi.top/Article/details/gtjkcexxyk.html

for my $x (@arr) { print $x; }
来源：http://dali.jyoumei.cn/Article/details/gtjhueiidk.html

[T46] Perl：哈希操作
来源：http://dali.yj20258888.top/Article/details/gtfhnqyhun.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yangfankeji.com/Article/details/gtnnrkjiij.html

[T47] Perl：正则捕获
来源：http://dali.dianchejie.cn/Article/details/gthtnmccve.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.sufxvd.cn/Article/details/gtfsqvbclc.html

[T48] Perl：正则替换
来源：http://dali.ybcxt.top/Article/details/gtzuorzqag.html

$s =~ s/old/new/g;
来源：http://dali.sufxvd.cn/Article/details/gtxuqwrcig.html

[T49] Perl：函数
来源：http://dali.c1oappe.top/Article/details/gtzgfmbmqn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gtcporwaly.html

[T50] Perl：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gtgblhoonb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yongpay.top/Article/details/gtjwmyknkh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.dianchejie.cn/Article/details/gtvnsihtxf.html

[T51] Scala：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtnuxazwsg.html

println("Hello")
来源：http://dali.aibaodan.cn/Article/details/gtsvalwnxl.html

[T52] Scala：变量
来源：http://dali.cheryme.top/Article/details/gttptfdwot.html

val a = 1;  var b = 2
来源：http://dali.yonumen.top/Article/details/gtcjirqkol.html

[T53] Scala：字符串插值
来源：http://dali.xinyue.icu/Article/details/gtrtlqlntj.html

s"值: $b"
来源：http://dali.snrcjt.cn/Article/details/gtnwvrdjed.html

[T54] Scala：集合映射
来源：http://dali.zhongyouzk.top/Article/details/gtcdprvudt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtmuaejfpi.html

[T55] Scala：集合过滤
来源：http://dali.bjfxy.top/Article/details/gtbascpphf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cdnleiting.top/Article/details/gtihgzkjnh.html

[T56] Scala：样例类
来源：http://dali.havefunace.top/Article/details/gthdoheblg.html

case class User(name: String, age: Int)
来源：http://dali.hammf.cn/Article/details/gtzvfjovkc.html

[T57] Scala：模式匹配
来源：http://dali.snrcjt.cn/Article/details/gtcsivbzsr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jianghu66.top/Article/details/gtorzwkqdq.html

[T58] Scala：函数定义
来源：http://dali.ybcxt.top/Article/details/gtjoffzhym.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jianghu66.top/Article/details/gtndwaxwbz.html

[T59] Scala：循环
来源：http://dali.snrcjt.cn/Article/details/gtlausypdu.html

for (i <- 1 to 10) println(i)
来源：http://dali.wangshuangyany.cn/Article/details/gtqjxaqgcm.html

[T60] Scala：折叠
来源：http://dali.meibo888.top/Article/details/gtomcrdcty.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.daxiang520.top/Article/details/gteqtkzonp.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtqyiwpyhn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhixingplan.top/Article/details/gtqsfqjxst.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtjfafdfaz.html

[U01] Py：创建虚拟环境
来源：http://dali.dianchejie.cn/Article/details/gtadegzjhv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.kuanghao11.cn/Article/details/gtbdcftphs.html

[U02] Py：导出 / 安装依赖
来源：http://dali.pycfn.com/Article/details/gtkbirqqji.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hnxiangtu.top/Article/details/gtigbrnikj.html

[U03] Py：加载 .env 配置
来源：http://dali.cashguo.top/Article/details/gtijdnnkva.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.vqdsnc.cn/Article/details/gtgvaxlnjn.html

[U04] Py：变量调试打印
来源：http://dali.jqgfzy.top/Article/details/gthefrhhxy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yuxming.cn/Article/details/gtmvjxjkhx.html

[U05] Py：列表去重且保序
来源：http://dali.jiagoushi.top/Article/details/gtrcltmxvl.html

list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gtjohqzddh.html

[U06] Py：合并两个字典
来源：http://dali.xuetiantiany.cn/Article/details/gteuqbaswr.html

{**a, **b}
来源：http://dali.sxryk.cn/Article/details/gtghsmhujr.html

[U07] Py：反转字典键值
来源：http://dali.cheryme.top/Article/details/gteitjnvmh.html

{v: k for k, v in d.items()}
来源：http://dali.cheryme.top/Article/details/gthkgvvrel.html

[U08] Py：展平二维列表
来源：http://dali.kuanghao11.cn/Article/details/gtnawdhygs.html

[y for x in nested for y in x]
来源：http://dali.meibo888.top/Article/details/gtmjitzjag.html

[U09] Py：字典取最大值的键
来源：http://dali.yj20258.top/Article/details/gtcsdltspf.html

max(d, key=d.get)
来源：http://dali.gogol.net.cn/Article/details/gtfixzpnma.html

[U10] Py：按值排序字典
来源：http://dali.yj202588.top/Article/details/gtkhrsizlj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hnxiangtu.top/Article/details/gtgfqjnnlt.html

[U11] Py：生成器表达式
来源：http://dali.ydzc1.top/Article/details/gtzczjqzmf.html

(x * 2 for x in arr)
来源：http://dali.svipenyu.cn/Article/details/gtixgdxstt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yj20258.top/Article/details/gtnjhsgzod.html

Counter(arr).most_common(3)
来源：http://dali.xylfe.cn/Article/details/gtprybzsse.html

[U13] Py：固定长度队列
来源：http://dali.zhongyouzk.top/Article/details/gtarrfhwjw.html

deque(maxlen=10)
来源：http://dali.yanxiufei.cn/Article/details/gtrlldtolh.html

[U14] Py：分组收集到列表
来源：http://dali.jyoumei.cn/Article/details/gttuxmvbkm.html

defaultdict(list)
来源：http://dali.jinqigufen.top/Article/details/gtjbdqabsd.html

[U15] Py：高精度计时
来源：http://dali.wangdashe.top/Article/details/gtyqqimzso.html

t = time.perf_counter()
来源：http://dali.hfpthk.cn/Article/details/gtumgxftvm.html

[U16] Py：命令行参数解析
来源：http://dali.hfpthk.cn/Article/details/gtmcwjjguk.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhixingplan.top/Article/details/gtrtojrbex.html

[U17] Py：初始化日志
来源：http://dali.nanxinkj.top/Article/details/gtzgjvxlec.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jqgufenzy.top/Article/details/gtugtuprrs.html

[U18] Py：预编译正则
来源：http://dali.yvedp.cn/Article/details/gtbbfrnqaj.html

pat = re.compile(r"\d+")
来源：http://dali.gogol.net.cn/Article/details/gtemleaogh.html

[U19] Py：正则替换带回调
来源：http://dali.shuidangran.top/Article/details/gtihdepmvq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsdiurolt.html

[U20] Py：缓存函数结果
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpyyujnfv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhixingplan.top/Article/details/gtsjfvotul.html

[U21] Py：自定义上下文管理器
来源：http://dali.meibo888.top/Article/details/gtbrnntovb.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gthujvnxmz.html

[U22] Py：矩阵转置
来源：http://dali.havefunace.top/Article/details/gtnbpzxprx.html

list(zip(*m))
来源：http://dali.zhixingplan.top/Article/details/gtynsrkjmm.html

[U23] Py：分块读取大文件
来源：http://dali.zdqjudy.top/Article/details/gteknizknw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yj20258.top/Article/details/gtasfucoxi.html

[U24] Py：路径操作
来源：http://dali.redwolf501.top/Article/details/gtyfxqnvvu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.iojbl.cn/Article/details/gtujqxrysz.html

[U25] Py：CSV 按字典读
来源：http://dali.shzxlz.cn/Article/details/gttecbhvtu.html

csv.DictReader(f)
来源：http://dali.bjfxy.top/Article/details/gtssuyycuk.html

[U26] Py：并发下载
来源：http://dali.dashuyun.cn/Article/details/gtpgdgwirj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhongyouzk.top/Article/details/gtkwcnrmse.html

[U27] Py：异步 HTTP
来源：http://dali.kuanghao11.cn/Article/details/gtxzxqmqxx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.316326.xyz/Article/details/gtwxdunjkw.html

[U28] Py：类型别名
来源：http://dali.zhongyouzk.top/Article/details/gtbtwrwhqi.html

UserId = int
来源：http://dali.dianchejie.cn/Article/details/gtcgbrxaxq.html

[U29] Py：属性校验
来源：http://dali.snrcjt.cn/Article/details/gtfwfsdopp.html

@property 与 @x.setter 配合
来源：http://dali.havefunace.top/Article/details/gtnhucbaqm.html

[U30] Py：数据类
来源：http://dali.zdqjudy.top/Article/details/gtmedoadjs.html

@dataclass(slots=True)
来源：http://dali.hammf.cn/Article/details/gtpxdzabew.html

[U31] Py：单测
来源：http://dali.cashguo.top/Article/details/gtqsavmavw.html

python -m pytest -q
来源：http://dali.zhixingplan.top/Article/details/gtfophzisz.html

[U32] Py：代码格式化
来源：http://dali.pycfn.com/Article/details/gtczttnkti.html

ruff format . && ruff check --fix .
来源：http://dali.c1oappe.top/Article/details/gtxypycqxm.html

[U33] Py：打包发布
来源：http://dali.svipenyu.cn/Article/details/gtzzajffyb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.sufxvd.cn/Article/details/gtpswfbnio.html

[U34] Py：判断编码
来源：http://dali.yj20258.top/Article/details/gtkyawvvkz.html

chardet.detect(raw)
来源：http://dali.daria6918.cn/Article/details/gtjfdjeesa.html

[U35] Py：发送邮件
来源：http://dali.yueranfly.top/Article/details/gtgrziumiw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.wangdashe.top/Article/details/gtwunylccw.html

[U36] Py：定时任务
来源：http://dali.dianchejie.cn/Article/details/gtpemonxsn.html

schedule.every(10).minutes.do(job)
来源：http://dali.nanxuanxn.top/Article/details/gtzeykgvuy.html

[U37] Py：读写 Excel
来源：http://dali.birdmap.top/Article/details/gtuljqbdeq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jqgufenzy.top/Article/details/gtrtlnsmqt.html

[U38] Py：获取脚本所在目录
来源：http://dali.jqgfzy.top/Article/details/gtuknrkwco.html

Path(__file__).resolve().parent
来源：http://dali.jinghuilouyu.cn/Article/details/gtifpxxvds.html

[U39] Py：判断是否在交互环境
来源：http://dali.feifeiyinyue.top/Article/details/gtchjokbud.html

sys.stdout.isatty()
来源：http://dali.gzhubu.top/Article/details/gtsylgfsvg.html

[U40] Py：打印到标准错误
来源：http://dali.yj20258888.top/Article/details/gtraksiplj.html

print("err", file=sys.stderr)
来源：http://dali.aizwys.cn/Article/details/gtdcvafgsz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.nwbrower.top/Article/details/gtccxrhcyh.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jqgfzy.top/Article/details/gtqzxvjxag.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhoulong.xyz/Article/details/gtsqedmzbv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xinyue.icu/Article/details/gtcglanhmn.html

[U43] PHP：声明命名空间
来源：http://dali.zhiwuduotai.top/Article/details/gtkebfogkv.html

namespace App\Http;
来源：http://dali.cashguo.top/Article/details/gtrdcknoht.html

[U44] PHP：开启严格类型
来源：http://dali.yj20258.top/Article/details/gtejrwzpow.html

declare(strict_types=1);
来源：http://dali.xylfe.cn/Article/details/gtwdufrosk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.smart0.xyz/Article/details/gtxgyrjdpv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cqqwz.cn/Article/details/gtkhibxeih.html

[U46] PHP：可空类型
来源：http://dali.pengpengdd.cyou/Article/details/gtwtjrshlw.html

?string $name = null
来源：http://dali.jinqigufen.top/Article/details/gtdhbxroqk.html

[U47] PHP：联合类型
来源：http://dali.zhoulong.xyz/Article/details/gtchcyefrk.html

int|string $id
来源：http://dali.svipenyu.cn/Article/details/gtzbrkxeqa.html

[U48] PHP：纯枚举
来源：http://dali.dashuyun.cn/Article/details/gtfebuelcp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jianghu66.top/Article/details/gtwivtmrgp.html

[U49] PHP：只读属性
来源：http://dali.cucudq.cn/Article/details/gtqtmqvtdw.html

public readonly string $name
来源：http://dali.yueranfly.top/Article/details/gtzmkdlxue.html

[U50] PHP：构造器属性提升
来源：http://dali.bjfxy.top/Article/details/gtfjugkmqb.html

public function __construct(private int $id) {}
来源：http://dali.yangfankeji.com/Article/details/gteqbbnqoc.html

[U51] PHP：数组解构
来源：http://dali.hnqzz.top/Article/details/gtdpyfalgp.html

[$a, $b] = $arr;
来源：http://dali.c1oappe.top/Article/details/gtqajymhts.html

[U52] PHP：箭头函数
来源：http://dali.cqqwz.cn/Article/details/gtlveprrwn.html

$double = fn($x) => $x * 2;
来源：http://dali.meibo888.top/Article/details/gtosdcuxvf.html

[U53] PHP：空合并运算符
来源：http://dali.jlsjyb.cn/Article/details/gtieaptbdb.html

$v = $a ?? $b ?? "default";
来源：http://dali.dashuyun.cn/Article/details/gtuapccgfv.html

[U54] PHP：空安全调用
来源：http://dali.xziqi.cn/Article/details/gtuefjfrrx.html

$obj?->method()
来源：http://dali.yueranfly.top/Article/details/gtuetsyxyc.html

[U55] PHP：match 表达式
来源：http://dali.jyoumei.cn/Article/details/gtqbkuzvzf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hnxiangtu.top/Article/details/gtsciibsrn.html

[U56] PHP：命名参数
来源：http://dali.tian-w.cn/Article/details/gtjfyihyoy.html

f(a: 1, b: 2)
来源：http://dali.zycfv.cn/Article/details/gtmjvcaloq.html


<!-- 参考信息 -->