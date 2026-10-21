代发 wailian999

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.havefunace.top/Article/details/gtfnxcophl.html

[S25] C：内存拷贝
来源：http://dali.0kj1m.cn/Article/details/gtiiuubnju.html

memcpy(dst, src, n);
来源：http://dali.shzxlz.cn/Article/details/gtpvefwrtn.html

[S26] C：内存清零
来源：http://dali.dashuyun.cn/Article/details/gtxqzbupel.html

memset(a, 0, sizeof a);
来源：http://dali.cucudq.cn/Article/details/gtginlfbgm.html

[S27] C：定义常量
来源：http://dali.hnxiangtu.top/Article/details/gtroccyviu.html

const double PI = 3.14159;
来源：http://dali.yonumen.top/Article/details/gtkzylcukx.html

[S28] C：静态变量
来源：http://dali.jinqigufen.top/Article/details/gthjofziev.html

static int counter = 0;
来源：http://dali.tian-w.cn/Article/details/gturyradfl.html

[S29] C：变参函数
来源：http://dali.zhiwuduotai.top/Article/details/gtprhikwdm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yuanzhike.top/Article/details/gtuowbothk.html

[S30] C：头文件保护
来源：http://dali.yj202588.top/Article/details/gttjkkpudi.html

#ifndef X_H
来源：http://dali.yueranfly.top/Article/details/gtmqbridjw.html

#define X_H
来源：http://dali.yvedp.cn/Article/details/gtvpzqqljn.html

#endif
来源：http://dali.pengpengdd.cyou/Article/details/gtpujkilnv.html

[S31] C++：Hello World
来源：http://dali.yvedp.cn/Article/details/gtijuxilcu.html

#include <iostream>
来源：http://dali.shangyingyoupin.top/Article/details/gtsgtvibvk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.wangdashe.top/Article/details/gtpvcfxapg.html

[S32] C++：字符串
来源：http://dali.fzhhl.top/Article/details/gtfrixokpl.html

std::string s = "hi";  s += "!";
来源：http://dali.fzhhl.top/Article/details/gtieuvpyhc.html

[S33] C++：vector 增删
来源：http://dali.jqgufenzy.top/Article/details/gtunikejbw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.0kj1m.cn/Article/details/gtwczgnllf.html

[S34] C++：遍历 vector
来源：http://dali.xylfe.cn/Article/details/gtyqtwbeqg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.meibo888.top/Article/details/gtcaddjbih.html

[S35] C++：map
来源：http://dali.xylfe.cn/Article/details/gtscpbnwfg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gtjyoclips.html

[S36] C++：unordered_map
来源：http://dali.jyoumei.cn/Article/details/gtcweqtiti.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gtaeafemcc.html

[S37] C++：set
来源：http://dali.yangfankeji.com/Article/details/gtldxokcvl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gotoacloud.top/Article/details/gtdktadpsm.html

[S38] C++：排序
来源：http://dali.wangshuangyany.cn/Article/details/gtxildmsqv.html

std::sort(v.begin(), v.end());
来源：http://dali.bjfxy.top/Article/details/gtjpmoucjg.html

[S39] C++：自定义比较器排序
来源：http://dali.jqgfzy.top/Article/details/gtejstxasc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.svipenyu.cn/Article/details/gtxstrdbnv.html

[S40] C++：查找元素
来源：http://dali.ehwqpu.com/Article/details/gtvvlccjso.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuvgyjnea.html

[S41] C++：类与构造函数
来源：http://dali.fengsongda.top/Article/details/gtmqsyljlu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zycfv.cn/Article/details/gtsmlmjnow.html

[S42] C++：继承与虚函数
来源：http://dali.pycfn.com/Article/details/gtussmljtv.html

class B : public Base { public: void f() override {} };
来源：http://dali.xuanzx.com/Article/details/gtmbfdxhvd.html

[S43] C++：智能指针
来源：http://dali.tianlin.xyz/Article/details/gtbupazpwk.html

auto p = std::make_unique<int>(5);
来源：http://dali.gotoacloud.top/Article/details/gtmbhnefbn.html

[S44] C++：引用传参
来源：http://dali.chenjidiqi.icu/Article/details/gtrdsvzrwl.html

void inc(int &x) { ++x; }
来源：http://dali.dashuyun.cn/Article/details/gtwpuevmqi.html

[S45] C++：lambda
来源：http://dali.hammf.cn/Article/details/gtttkjdzuw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sufxvd.cn/Article/details/gtrbwkdmxp.html

[S46] C++：函数模板
来源：http://dali.chenzaomai.com/Article/details/gtmoqjjltl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hnxiangtu.top/Article/details/gtzughjzty.html

[S47] C++：结构化绑定遍历
来源：http://dali.shuidangran.top/Article/details/gtlwszibjg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hywenlv.cn/Article/details/gtntlfevzi.html

[S48] C++：逐行读文件
来源：http://dali.wangdashe.top/Article/details/gtzgyegjjp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.birdmap.top/Article/details/gtplkmxdzx.html

while (std::getline(in, line)) { }
来源：http://dali.aibaodan.cn/Article/details/gtrccyhivr.html

[S49] C++：写文件
来源：http://dali.birdmap.top/Article/details/gtkcqcubvo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.dianchejie.cn/Article/details/gtzqjjqczb.html

[S50] C++：格式化数字
来源：http://dali.dashuyun.cn/Article/details/gthfsprqsd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gtelkxdaah.html

[S51] C++：显式类型转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbmlmesd.html

static_cast<double>(a) / b
来源：http://dali.ppjwa.cn/Article/details/gtorljbenj.html

[S52] C++：const 与 noexcept
来源：http://dali.cashguo.top/Article/details/gtunorawsh.html

int size() const noexcept { return n_; }
来源：http://dali.chenzaomai.com/Article/details/gtmsregjry.html

[S53] C++：移动语义
来源：http://dali.yj20258.top/Article/details/gtoavbroxc.html

std::vector<int> w = std::move(v);
来源：http://dali.chenlongwang.top/Article/details/gtygwghpfv.html

[S54] C++：异常处理
来源：http://dali.jyoumei.cn/Article/details/gtbicuwxki.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zdqjudy.top/Article/details/gtpgougtsk.html

[S55] C++：结构化绑定
来源：http://dali.316326.xyz/Article/details/gtjipywhic.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ybcxt.top/Article/details/gttqjfhslo.html

[S56] C++：optional
来源：http://dali.tanke756.top/Article/details/gtbbkjycub.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjcdjgwwf.html

[S57] C++：编译期常量
来源：http://dali.bjfxy.top/Article/details/gtqqvljtyc.html

constexpr int N = 10;
来源：http://dali.smart0.xyz/Article/details/gtirtalodl.html

[S58] C++：命名空间
来源：http://dali.birdmap.top/Article/details/gthgmylmna.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj20258.top/Article/details/gtacnyehuh.html

[S59] C++：静态断言
来源：http://dali.mhx1999.top/Article/details/gtwrvqewus.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hywenlv.cn/Article/details/gtnfzijiaz.html

[S60] C++：遍历并删除元素
来源：http://dali.zhoulong.xyz/Article/details/gteiskbmqd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.feifeiyinyue.top/Article/details/gtcwpglgou.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtmgpwxabl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shanyushiyangtech.top/Article/details/gtdcpzebmc.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gthcspduva.html

[T01] Kotlin：Hello World
来源：http://dali.xziqi.cn/Article/details/gtxzhnlygc.html

println("Hello")
来源：http://dali.aizwys.cn/Article/details/gtiwxeoarz.html

[T02] Kotlin：变量
来源：http://dali.hnqzz.top/Article/details/gtmxgpxjvi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tanke756.top/Article/details/gtsidyfwhy.html

[T03] Kotlin：字符串模板
来源：http://dali.tian-w.cn/Article/details/gtitbjlatb.html

"值: $b"
来源：http://dali.tianlin.xyz/Article/details/gtlesrcekf.html

[T04] Kotlin：空安全
来源：http://dali.cqqwz.cn/Article/details/gtdazlobmi.html

val n: String? = null;  n?.length
来源：http://dali.ivvv.top/Article/details/gtcecdloww.html

[T05] Kotlin：when 表达式
来源：http://dali.yj202588.top/Article/details/gtxtfoiqef.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.aibaodan.cn/Article/details/gtvcmatuqs.html

[T06] Kotlin：集合映射
来源：http://dali.zhixingplan.top/Article/details/gtjumiwuan.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtvzblyjgk.html

[T07] Kotlin：集合过滤
来源：http://dali.guannengcc.top/Article/details/gtuzmobzvi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zycfv.cn/Article/details/gtdscdncwa.html

[T08] Kotlin：数据类
来源：http://dali.nanxuanxn.top/Article/details/gtggarslom.html

data class User(val name: String, val age: Int)
来源：http://dali.zhongyouzk.top/Article/details/gtknxwawvn.html

[T09] Kotlin：扩展函数
来源：http://dali.jinghuilouyu.cn/Article/details/gteodwkykp.html

fun String.exclaim() = this + "!"
来源：http://dali.jqgfzy.top/Article/details/gtzdbzcvae.html

[T10] Kotlin：默认参数
来源：http://dali.xinyue.icu/Article/details/gtftatirku.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jqgufenzy.top/Article/details/gtqhyqklzi.html

[T11] Kotlin：协程
来源：http://dali.sxryk.cn/Article/details/gtafrwuzio.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yuxming.cn/Article/details/gtszciaxny.html

[T12] Kotlin：解构声明
来源：http://dali.jiagoushi.top/Article/details/gtacorcguv.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhixingplan.top/Article/details/gtbjnzyqmd.html

[T13] Kotlin：只读 Map
来源：http://dali.hnqzz.top/Article/details/gtgwwmqljr.html

val m = mapOf("a" to 1)
来源：http://dali.wangdashe.top/Article/details/gtmkvflqjl.html

[T14] Kotlin：循环
来源：http://dali.cqqwz.cn/Article/details/gtmjymjzgv.html

for (i in 1..10) println(i)
来源：http://dali.yuanzhike.top/Article/details/gtjptmnbpp.html

[T15] Kotlin：接口
来源：http://dali.nanxuanxn.top/Article/details/gtmoavrijt.html

interface Shape { fun area(): Double }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtarwkoitz.html

[T16] Swift：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtacrfxyxy.html

print("Hello")
来源：http://dali.dianchejie.cn/Article/details/gtmppfuvkp.html

[T17] Swift：变量与常量
来源：http://dali.haohaochexian.top/Article/details/gtzcnggekb.html

var a = 1;  let b = 2
来源：http://dali.yuxming.cn/Article/details/gtscshomhb.html

[T18] Swift：字符串插值
来源：http://dali.ppjwa.cn/Article/details/gtvxcodkdb.html

"值: \(b)"
来源：http://dali.jlsjyb.cn/Article/details/gtclpynccq.html

[T19] Swift：可选绑定
来源：http://dali.xziqi.cn/Article/details/gtbodnwkqk.html

if let n = opt { print(n) }
来源：http://dali.jlsjyb.cn/Article/details/gtlqvqbfvn.html

[T20] Swift：数组操作
来源：http://dali.yvedp.cn/Article/details/gtdpmfdjrj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shuidangran.top/Article/details/gtjfdgoare.html

[T21] Swift：遍历
来源：http://dali.yuxming.cn/Article/details/gtpmgnohfd.html

for x in a { print(x) }
来源：http://dali.ehwqpu.com/Article/details/gthxdzwjot.html

[T22] Swift：字典
来源：http://dali.xinyue.icu/Article/details/gtmyahihhy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.aizwys.cn/Article/details/gtgdcyzgpg.html

[T23] Swift：函数
来源：http://dali.guowangkeji.top/Article/details/gtfeaesrmx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.fzhhl.top/Article/details/gtgxzuweyp.html

[T24] Swift：闭包
来源：http://dali.yanxiufei.cn/Article/details/gtjbwnuvsg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.chenzaomai.com/Article/details/gtewokijnj.html

[T25] Swift：结构体
来源：http://dali.xuanzx.com/Article/details/gtkcxdsxdk.html

struct P { var x: Int }
来源：http://dali.xuetiantiany.cn/Article/details/gtrxyuyaap.html

[T26] Swift：类与重写
来源：http://dali.cheryme.top/Article/details/gttjegvnyz.html

class A: Base { override func f() {} }
来源：http://dali.jyoumei.cn/Article/details/gtscuhieck.html

[T27] Swift：错误处理
来源：http://dali.chenzaomai.com/Article/details/gtkasdgvbs.html

do { try f() } catch { print(error) }
来源：http://dali.bjfxy.top/Article/details/gtdpwqcveb.html

[T28] Swift：枚举
来源：http://dali.aibaodan.cn/Article/details/gtavvjukve.html

enum Color { case red, green }
来源：http://dali.fzhhl.top/Article/details/gtfcesmjhh.html

[T29] Swift：guard 提前返回
来源：http://dali.dashuyun.cn/Article/details/gtpymhyegm.html

guard let x = opt else { return }
来源：http://dali.sxryk.cn/Article/details/gtbqtltpud.html

[T30] Swift：协议
来源：http://dali.jqgufenzy.top/Article/details/gtpuoxfnfi.html

protocol Shape { func area() -> Double }
来源：http://dali.iojbl.cn/Article/details/gtgtdkwadw.html

[T31] Lua：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtslaykujh.html

print("Hello")
来源：http://dali.jinqigufen.top/Article/details/gtnmlomsmy.html

[T32] Lua：局部变量
来源：http://dali.bjfxy.top/Article/details/gtmmuenkvo.html

local a = 1
来源：http://dali.c1oappe.top/Article/details/gtoupriojg.html

[T33] Lua：表（数组）
来源：http://dali.hfpthk.cn/Article/details/gtzhauwxvr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xinyue.icu/Article/details/gtirioimuv.html

[T34] Lua：遍历表
来源：http://dali.ivvv.top/Article/details/gtciclzmyh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.dashuyun.cn/Article/details/gtvjzrnbor.html

[T35] Lua：字典表
来源：http://dali.yonumen.top/Article/details/gtvrjaepad.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zdqjudy.top/Article/details/gtdvmjufpk.html

[T36] Lua：函数
来源：http://dali.chenjidiqi.icu/Article/details/gtppseawct.html

function add(a, b) return a + b end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwfvuimvi.html

[T37] Lua：字符串拼接
来源：http://dali.yj20258888.top/Article/details/gtablfoffk.html

"a" .. "b"
来源：http://dali.jinghuilouyu.cn/Article/details/gtcbgkldrh.html

[T38] Lua：条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gthtwrglwt.html

if x > 0 then print("正") end
来源：http://dali.dashuyun.cn/Article/details/gtzgderfng.html

[T39] Lua：模式匹配
来源：http://dali.meibo888.top/Article/details/gthshgfact.html

string.find(s, "%d+")
来源：http://dali.tian-w.cn/Article/details/gtfiqlfwbi.html

[T40] Lua：元表
来源：http://dali.daxiang520.top/Article/details/gtpyvpxjcy.html

setmetatable({}, { __index = base })
来源：http://dali.yj202588.top/Article/details/gtxpfodlwg.html

[T41] Perl：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtosegxuwq.html

print "Hello\n";
来源：http://dali.daxiang520.top/Article/details/gtxlmughna.html

[T42] Perl：变量类型
来源：http://dali.ydzc1.top/Article/details/gtodhlijij.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtozkfohfo.html

[T43] Perl：字符串插值
来源：http://dali.daria6918.cn/Article/details/gtujwwpndl.html

"值: $a"
来源：http://dali.fengsongda.top/Article/details/gtnznohuld.html

[T44] Perl：条件
来源：http://dali.0kj1m.cn/Article/details/gtadbeqluc.html

if ($a > 0) { print "正"; }
来源：http://dali.redwolf501.top/Article/details/gtvpvkgukf.html

[T45] Perl：数组遍历
来源：http://dali.yj20258888.top/Article/details/gtdjsqtbkw.html

for my $x (@arr) { print $x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvedbprqy.html

[T46] Perl：哈希操作
来源：http://dali.shuidangran.top/Article/details/gtbxkzwitj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.sweek.top/Article/details/gtaiaudixf.html

[T47] Perl：正则捕获
来源：http://dali.feifeiyinyue.top/Article/details/gtkyyagxxh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.tianlin.xyz/Article/details/gtgethtzrl.html

[T48] Perl：正则替换
来源：http://dali.iojbl.cn/Article/details/gtjijmohjj.html

$s =~ s/old/new/g;
来源：http://dali.sweek.top/Article/details/gtfkghnwos.html

[T49] Perl：函数
来源：http://dali.jyoumei.cn/Article/details/gtxyaznxzg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gtxmefjffz.html

[T50] Perl：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gtiirxwcuh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hnxiangtu.top/Article/details/gtnauivcsh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.snrcjt.cn/Article/details/gtaxjiqgeh.html

[T51] Scala：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtvhqieehx.html

println("Hello")
来源：http://dali.yuxming.cn/Article/details/gtlzxdbsem.html

[T52] Scala：变量
来源：http://dali.hongshengwenyu.top/Article/details/gtumporrxw.html

val a = 1;  var b = 2
来源：http://dali.gotoacloud.top/Article/details/gtnnzmqsaz.html

[T53] Scala：字符串插值
来源：http://dali.iojbl.cn/Article/details/gtlxazyliu.html

s"值: $b"
来源：http://dali.hnqzz.top/Article/details/gtmkrcauzu.html

[T54] Scala：集合映射
来源：http://dali.snrcjt.cn/Article/details/gtaaoykvth.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.svipenyu.cn/Article/details/gtiydcvswd.html

[T55] Scala：集合过滤
来源：http://dali.kuanghao11.cn/Article/details/gtboxbcnkg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shzxlz.cn/Article/details/gtqutevmra.html

[T56] Scala：样例类
来源：http://dali.fzhhl.top/Article/details/gtithosilr.html

case class User(name: String, age: Int)
来源：http://dali.gotoacloud.top/Article/details/gthesgguqz.html

[T57] Scala：模式匹配
来源：http://dali.cucudq.cn/Article/details/gtsvyapayz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ehwqpu.com/Article/details/gtfxozekvy.html

[T58] Scala：函数定义
来源：http://dali.jqgufenzy.top/Article/details/gtgbozdclw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hongshengwenyu.top/Article/details/gtjvnfplew.html

[T59] Scala：循环
来源：http://dali.tanke756.top/Article/details/gtbvrpkier.html

for (i <- 1 to 10) println(i)
来源：http://dali.guowangkeji.top/Article/details/gtvryvkgrk.html

[T60] Scala：折叠
来源：http://dali.andypj.xyz/Article/details/gtnglsjgcd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.nanxinkj.top/Article/details/gtzhmxdmkz.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtinhbjuug.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ybcxt.top/Article/details/gtcefqepvy.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtbnewqyex.html

[U01] Py：创建虚拟环境
来源：http://dali.jinghuilouyu.cn/Article/details/gtwcmhzpep.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cucudq.cn/Article/details/gtfoxpulpu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.tanke756.top/Article/details/gtfhqpnwba.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yj20258.top/Article/details/gtbtosusuo.html

[U03] Py：加载 .env 配置
来源：http://dali.yuanzhike.top/Article/details/gtanhhkmlo.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cheryme.top/Article/details/gtjnynlbnt.html

[U04] Py：变量调试打印
来源：http://dali.smart0.xyz/Article/details/gtijveeywv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhixingplan.top/Article/details/gtrqxwklno.html

[U05] Py：列表去重且保序
来源：http://dali.mhx1999.top/Article/details/gtlhqamuco.html

list(dict.fromkeys(arr))
来源：http://dali.yj20258.top/Article/details/gtkwuefhtk.html

[U06] Py：合并两个字典
来源：http://dali.yj202588.top/Article/details/gtjtthxutm.html

{**a, **b}
来源：http://dali.yj202588.top/Article/details/gtpqvbrvgw.html

[U07] Py：反转字典键值
来源：http://dali.kuanghao11.cn/Article/details/gttopxfxye.html

{v: k for k, v in d.items()}
来源：http://dali.nanxinkj.top/Article/details/gtnbkwxcnz.html

[U08] Py：展平二维列表
来源：http://dali.zhoulong.xyz/Article/details/gtpemvheko.html

[y for x in nested for y in x]
来源：http://dali.sxryk.cn/Article/details/gtbtfpddtm.html

[U09] Py：字典取最大值的键
来源：http://dali.nanxinkj.top/Article/details/gtszxzczej.html

max(d, key=d.get)
来源：http://dali.vqdsnc.cn/Article/details/gtjocztwmh.html

[U10] Py：按值排序字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnzgifjqn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.nanxinkj.top/Article/details/gtwvngrbhd.html

[U11] Py：生成器表达式
来源：http://dali.tanke756.top/Article/details/gtnttircyi.html

(x * 2 for x in arr)
来源：http://dali.sxryk.cn/Article/details/gtxkpvuqve.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.nanxuanxn.top/Article/details/gtpqksdyef.html

Counter(arr).most_common(3)
来源：http://dali.cucudq.cn/Article/details/gtvsxwhydp.html

[U13] Py：固定长度队列
来源：http://dali.vqdsnc.cn/Article/details/gtphqrcsaf.html

deque(maxlen=10)
来源：http://dali.gogol.net.cn/Article/details/gtvrlioepw.html

[U14] Py：分组收集到列表
来源：http://dali.guannengcc.top/Article/details/gtppeqjfvs.html

defaultdict(list)
来源：http://dali.sufxvd.cn/Article/details/gtublhbpet.html

[U15] Py：高精度计时
来源：http://dali.quarkkingdee.top/Article/details/gtzcvbwrvf.html

t = time.perf_counter()
来源：http://dali.xuanzx.com/Article/details/gtgfjmpiex.html

[U16] Py：命令行参数解析
来源：http://dali.vqdsnc.cn/Article/details/gtlvuwastt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinqigufen.top/Article/details/gtqjghrbsa.html

[U17] Py：初始化日志
来源：http://dali.fengsongda.top/Article/details/gtypnmgutp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.gzhubu.top/Article/details/gtoalsexps.html

[U18] Py：预编译正则
来源：http://dali.shuidangran.top/Article/details/gtmrqxbuoe.html

pat = re.compile(r"\d+")
来源：http://dali.tianlin.xyz/Article/details/gtsehvmmbu.html

[U19] Py：正则替换带回调
来源：http://dali.fzhhl.top/Article/details/gtcmurjcck.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zycfv.cn/Article/details/gtzbhmtqfr.html

[U20] Py：缓存函数结果
来源：http://dali.sweek.top/Article/details/gtzzdajtwj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yj20258888.top/Article/details/gtaohucvmz.html

[U21] Py：自定义上下文管理器
来源：http://dali.yvedp.cn/Article/details/gtxcgimgmk.html

@contextlib.contextmanager
来源：http://dali.gaohongyu789.top/Article/details/gthuofrdcg.html

[U22] Py：矩阵转置
来源：http://dali.ivvv.top/Article/details/gteodlnnnc.html

list(zip(*m))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtabjhqlww.html

[U23] Py：分块读取大文件
来源：http://dali.chenzaomai.com/Article/details/gtapkwqikd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jiagoushi.top/Article/details/gtwwitbglc.html

[U24] Py：路径操作
来源：http://dali.yj20258888.top/Article/details/gthdeeagkc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.tian-w.cn/Article/details/gtzszqxurt.html

[U25] Py：CSV 按字典读
来源：http://dali.gogol.net.cn/Article/details/gtpqzfqftv.html

csv.DictReader(f)
来源：http://dali.jiagoushi.top/Article/details/gtfiupmimo.html

[U26] Py：并发下载
来源：http://dali.tanke756.top/Article/details/gtgplvmyye.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.tanke756.top/Article/details/gtplvgeexj.html

[U27] Py：异步 HTTP
来源：http://dali.jqgufenzy.top/Article/details/gtotyvhyxj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhongyouzk.top/Article/details/gtfrzdxobl.html

[U28] Py：类型别名
来源：http://dali.hfpthk.cn/Article/details/gtmmdqmchb.html

UserId = int
来源：http://dali.chenjidiqi.icu/Article/details/gtgjbzcexs.html

[U29] Py：属性校验
来源：http://dali.9152youxi.cn/Article/details/gtxzjxcoze.html

@property 与 @x.setter 配合
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpretcxtp.html

[U30] Py：数据类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdtvlyhir.html

@dataclass(slots=True)
来源：http://dali.jyoumei.cn/Article/details/gtgnbljxrg.html

[U31] Py：单测
来源：http://dali.haohaochexian.top/Article/details/gtdjheebml.html

python -m pytest -q
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkbvpvknl.html

[U32] Py：代码格式化
来源：http://dali.andypj.xyz/Article/details/gtydhtswzy.html

ruff format . && ruff check --fix .
来源：http://dali.pycfn.com/Article/details/gtvwnwryxb.html

[U33] Py：打包发布
来源：http://dali.gaohongyu789.top/Article/details/gtottzurqq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.316326.xyz/Article/details/gttuhkmowb.html

[U34] Py：判断编码
来源：http://dali.svipenyu.cn/Article/details/gtstdahxze.html

chardet.detect(raw)
来源：http://dali.haohaochexian.top/Article/details/gtkvrolaqc.html

[U35] Py：发送邮件
来源：http://dali.sysykeji.top/Article/details/gthgmannpj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jinqigfzy.top/Article/details/gtvmgrhmlk.html

[U36] Py：定时任务
来源：http://dali.jiagoushi.top/Article/details/gtfnfkgnmw.html

schedule.every(10).minutes.do(job)
来源：http://dali.redwolf501.top/Article/details/gthhghchju.html

[U37] Py：读写 Excel
来源：http://dali.yueranfly.top/Article/details/gtbmkplcwl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.0kj1m.cn/Article/details/gtunueonxf.html

[U38] Py：获取脚本所在目录
来源：http://dali.xziqi.cn/Article/details/gttavdydhq.html

Path(__file__).resolve().parent
来源：http://dali.pengpengdd.cyou/Article/details/gtrfiifvet.html

[U39] Py：判断是否在交互环境
来源：http://dali.0kj1m.cn/Article/details/gtgllgrsii.html

sys.stdout.isatty()
来源：http://dali.nanxuanxn.top/Article/details/gtjwemtrqh.html

[U40] Py：打印到标准错误
来源：http://dali.jqgufenzy.top/Article/details/gtczodekwb.html

print("err", file=sys.stderr)
来源：http://dali.haohaochexian.top/Article/details/gtwaxfogob.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.gogol.net.cn/Article/details/gtsgzcuprf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.cucudq.cn/Article/details/gtciycmzxl.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ppjwa.cn/Article/details/gtbxjfwfts.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.sweek.top/Article/details/gtczgytuwv.html

[U43] PHP：声明命名空间
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhakcmjv.html

namespace App\Http;
来源：http://dali.smart0.xyz/Article/details/gtatdbzhkk.html

[U44] PHP：开启严格类型
来源：http://dali.iojbl.cn/Article/details/gtpogqhbqt.html

declare(strict_types=1);
来源：http://dali.hnxiangtu.top/Article/details/gtkkkpjvvb.html

[U45] PHP：类型声明与返回类型
来源：http://dali.daria6918.cn/Article/details/gtoddtflyb.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gtnmaulgmm.html

[U46] PHP：可空类型
来源：http://dali.jyoumei.cn/Article/details/gtvwrhrimv.html

?string $name = null
来源：http://dali.cdnleiting.top/Article/details/gtqyocjvgu.html

[U47] PHP：联合类型
来源：http://dali.chenjidiqi.icu/Article/details/gtovbfcewh.html

int|string $id
来源：http://dali.fengsongda.top/Article/details/gtilbmlxit.html

[U48] PHP：纯枚举
来源：http://dali.tianlin.xyz/Article/details/gtvvtnqmxw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtafjjjwhy.html


<!-- 参考信息 -->