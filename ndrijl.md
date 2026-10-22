代发 wailian999

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.haohaochexian.top/Article/details/gtejlsqmqh.html

[S21] C：字符类别判断
来源：http://dali.hongshengwenyu.top/Article/details/gtdrtzyyfu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.snrcjt.cn/Article/details/gtimccembq.html

[S22] C：字符串转数字
来源：http://dali.yonumen.top/Article/details/gtxmtonzhg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.smart0.xyz/Article/details/gtnskbiigc.html

[S23] C：随机数
来源：http://dali.yj20258.top/Article/details/gtknctmocf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jiagoushi.top/Article/details/gtufidxtmd.html

[S24] C：获取本地时间
来源：http://dali.gotoacloud.top/Article/details/gtszmvhygi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.fzhhl.top/Article/details/gtaqvfqtwz.html

[S25] C：内存拷贝
来源：http://dali.pengpengdd.cyou/Article/details/gtvqnsgixt.html

memcpy(dst, src, n);
来源：http://dali.wangdashe.top/Article/details/gtkymufdjv.html

[S26] C：内存清零
来源：http://dali.feifeiyinyue.top/Article/details/gtwhbpcdvo.html

memset(a, 0, sizeof a);
来源：http://dali.daxiang520.top/Article/details/gtosahvwea.html

[S27] C：定义常量
来源：http://dali.jianghu66.top/Article/details/gtplrkerfc.html

const double PI = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuslgkyzm.html

[S28] C：静态变量
来源：http://dali.jyoumei.cn/Article/details/gtisswljhc.html

static int counter = 0;
来源：http://dali.jqgufenzy.top/Article/details/gtznpnymll.html

[S29] C：变参函数
来源：http://dali.0kj1m.cn/Article/details/gtvnqfgbje.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.9152youxi.cn/Article/details/gtiqolhrgu.html

[S30] C：头文件保护
来源：http://dali.hysaishi.cn/Article/details/gtpzcrvrsw.html

#ifndef X_H
来源：http://dali.xziqi.cn/Article/details/gticqebpwx.html

#define X_H
来源：http://dali.kuanghao11.cn/Article/details/gtkhspwhuu.html

#endif
来源：http://dali.chenlongwang.top/Article/details/gtgxotcqnj.html

[S31] C++：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtdqylznto.html

#include <iostream>
来源：http://dali.snrcjt.cn/Article/details/gtxxxvejgy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tianlin.xyz/Article/details/gtfdjncnxc.html

[S32] C++：字符串
来源：http://dali.cdnleiting.top/Article/details/gtnuyixjcd.html

std::string s = "hi";  s += "!";
来源：http://dali.shangyingyoupin.top/Article/details/gtnazwbltn.html

[S33] C++：vector 增删
来源：http://dali.bjfxy.top/Article/details/gtrxexluye.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gtijqpkocq.html

[S34] C++：遍历 vector
来源：http://dali.wangshuangyany.cn/Article/details/gtqmxubkuc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gzhubu.top/Article/details/gtlqbvcwlg.html

[S35] C++：map
来源：http://dali.hfpthk.cn/Article/details/gtttirfndx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258888.top/Article/details/gtemtetnsa.html

[S36] C++：unordered_map
来源：http://dali.aibaodan.cn/Article/details/gtubcdumrg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnqzz.top/Article/details/gtbupftpnb.html

[S37] C++：set
来源：http://dali.guowangkeji.top/Article/details/gtldcloook.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jyoumei.cn/Article/details/gthmgionef.html

[S38] C++：排序
来源：http://dali.gaohongyu789.top/Article/details/gtpudztaap.html

std::sort(v.begin(), v.end());
来源：http://dali.zdqjudy.top/Article/details/gtrzemvjjb.html

[S39] C++：自定义比较器排序
来源：http://dali.chenzaomai.com/Article/details/gtnmiydtob.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhongyouzk.top/Article/details/gtaaksealn.html

[S40] C++：查找元素
来源：http://dali.hnqzz.top/Article/details/gtgdhvrjtf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zdqjudy.top/Article/details/gttcfvlcoo.html

[S41] C++：类与构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwsnlslca.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.aibaodan.cn/Article/details/gtbiizghel.html

[S42] C++：继承与虚函数
来源：http://dali.vqdsnc.cn/Article/details/gtvzzjcxwc.html

class B : public Base { public: void f() override {} };
来源：http://dali.yvedp.cn/Article/details/gtlcmzmqol.html

[S43] C++：智能指针
来源：http://dali.cashguo.top/Article/details/gtxqrsyjtm.html

auto p = std::make_unique<int>(5);
来源：http://dali.feifeiyinyue.top/Article/details/gtnicvqmuc.html

[S44] C++：引用传参
来源：http://dali.ehwqpu.com/Article/details/gtdmmmoncn.html

void inc(int &x) { ++x; }
来源：http://dali.jianghu66.top/Article/details/gtmimlbaez.html

[S45] C++：lambda
来源：http://dali.vqdsnc.cn/Article/details/gtjomhtwrj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tianlin.xyz/Article/details/gtcxxvdchq.html

[S46] C++：函数模板
来源：http://dali.zhengqikj.top/Article/details/gtsyyulqme.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.daria6918.cn/Article/details/gtbtmdkuqa.html

[S47] C++：结构化绑定遍历
来源：http://dali.ydzc1.top/Article/details/gtsbbtyjza.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhixingplan.top/Article/details/gtjiosguzo.html

[S48] C++：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtsuycodgg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tanke756.top/Article/details/gtmycoalif.html

while (std::getline(in, line)) { }
来源：http://dali.jqgufenzy.top/Article/details/gtzbgjkifd.html

[S49] C++：写文件
来源：http://dali.ybcxt.top/Article/details/gthguouskb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hnqzz.top/Article/details/gttjmkyjim.html

[S50] C++：格式化数字
来源：http://dali.wangshuangyany.cn/Article/details/gtaxasdevt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gtkmctvdtv.html

[S51] C++：显式类型转换
来源：http://dali.9152youxi.cn/Article/details/gtkhxhcart.html

static_cast<double>(a) / b
来源：http://dali.316326.xyz/Article/details/gtpaouzksh.html

[S52] C++：const 与 noexcept
来源：http://dali.hongshengwenyu.top/Article/details/gtpszvercc.html

int size() const noexcept { return n_; }
来源：http://dali.quarkkingdee.top/Article/details/gtjglmoaeg.html

[S53] C++：移动语义
来源：http://dali.mhx1999.top/Article/details/gtmejuqmvz.html

std::vector<int> w = std::move(v);
来源：http://dali.yj202588.top/Article/details/gtwecxoxtg.html

[S54] C++：异常处理
来源：http://dali.shzxlz.cn/Article/details/gtkqjwgvuw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yongpay.top/Article/details/gtphpduxew.html

[S55] C++：结构化绑定
来源：http://dali.ehwqpu.com/Article/details/gtscelbpnz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gaohongyu789.top/Article/details/gtzocsgvlb.html

[S56] C++：optional
来源：http://dali.mhx1999.top/Article/details/gtofqnlwfk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shangyingyoupin.top/Article/details/gtnzvuvxpm.html

[S57] C++：编译期常量
来源：http://dali.svipenyu.cn/Article/details/gtnretsuhf.html

constexpr int N = 10;
来源：http://dali.yvedp.cn/Article/details/gtuilnadnq.html

[S58] C++：命名空间
来源：http://dali.daria6918.cn/Article/details/gtqgwiacgg.html

namespace ns { int f() { return 1; } }
来源：http://dali.cashguo.top/Article/details/gtbxgskwgf.html

[S59] C++：静态断言
来源：http://dali.sysykeji.top/Article/details/gtzcfrfzuk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinghuilouyu.cn/Article/details/gtezxkyxoq.html

[S60] C++：遍历并删除元素
来源：http://dali.yj202588.top/Article/details/gtutgpvpzx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhaomingkeji.xyz/Article/details/gthknljavk.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtdbzyjhat.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gotoacloud.top/Article/details/gtvbjqefpx.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtnqlwgcgj.html

[T01] Kotlin：Hello World
来源：http://dali.ydzc1.top/Article/details/gtifpugnph.html

println("Hello")
来源：http://dali.pycfn.com/Article/details/gtzpkswqar.html

[T02] Kotlin：变量
来源：http://dali.fzhhl.top/Article/details/gtaemwohqo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hywenlv.cn/Article/details/gtacrbfrxr.html

[T03] Kotlin：字符串模板
来源：http://dali.cucudq.cn/Article/details/gtvdglvfdo.html

"值: $b"
来源：http://dali.hongshengwenyu.top/Article/details/gtvlbnpihx.html

[T04] Kotlin：空安全
来源：http://dali.zhaomingkeji.xyz/Article/details/gtanpxfdyp.html

val n: String? = null;  n?.length
来源：http://dali.ybcxt.top/Article/details/gtgazhsxlx.html

[T05] Kotlin：when 表达式
来源：http://dali.jlsjyb.cn/Article/details/gtpmyfgwzp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yanxiufei.cn/Article/details/gtusiyowgv.html

[T06] Kotlin：集合映射
来源：http://dali.xinyue.icu/Article/details/gthljjbwtl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hammf.cn/Article/details/gtrdtsuzxu.html

[T07] Kotlin：集合过滤
来源：http://dali.redwolf501.top/Article/details/gtrkpnyodu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.andypj.xyz/Article/details/gtxeikfaqd.html

[T08] Kotlin：数据类
来源：http://dali.zhoulong.xyz/Article/details/gtmqycxyfd.html

data class User(val name: String, val age: Int)
来源：http://dali.yuanzhike.top/Article/details/gtvrtqnwmf.html

[T09] Kotlin：扩展函数
来源：http://dali.aibaodan.cn/Article/details/gtygjfppde.html

fun String.exclaim() = this + "!"
来源：http://dali.yvedp.cn/Article/details/gttjninpio.html

[T10] Kotlin：默认参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcghzpohq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hongshengwenyu.top/Article/details/gtaqjxautn.html

[T11] Kotlin：协程
来源：http://dali.yangfankeji.com/Article/details/gtertavrpp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cheryme.top/Article/details/gtmidxehjg.html

[T12] Kotlin：解构声明
来源：http://dali.jinqigufen.top/Article/details/gtbakunjpu.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtkvtuqrnu.html

[T13] Kotlin：只读 Map
来源：http://dali.cdnleiting.top/Article/details/gtwfdranuo.html

val m = mapOf("a" to 1)
来源：http://dali.cheryme.top/Article/details/gtyjskfehd.html

[T14] Kotlin：循环
来源：http://dali.yonumen.top/Article/details/gtagzzcuth.html

for (i in 1..10) println(i)
来源：http://dali.yanxiufei.cn/Article/details/gtcrbhqumg.html

[T15] Kotlin：接口
来源：http://dali.redwolf501.top/Article/details/gtrcnvvtef.html

interface Shape { fun area(): Double }
来源：http://dali.snrcjt.cn/Article/details/gtorzkdoxu.html

[T16] Swift：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtqnirtwdv.html

print("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnutslyvv.html

[T17] Swift：变量与常量
来源：http://dali.wangshuangyany.cn/Article/details/gtrpxtasec.html

var a = 1;  let b = 2
来源：http://dali.daxiang520.top/Article/details/gtsgaruocj.html

[T18] Swift：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtawtaakuh.html

"值: \(b)"
来源：http://dali.gaohongyu789.top/Article/details/gtwhtnecwg.html

[T19] Swift：可选绑定
来源：http://dali.gotoacloud.top/Article/details/gtnjgkvdrk.html

if let n = opt { print(n) }
来源：http://dali.feifeiyinyue.top/Article/details/gtbnvymnia.html

[T20] Swift：数组操作
来源：http://dali.dianchejie.cn/Article/details/gtpoilhzjn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zycfv.cn/Article/details/gtthhewrhx.html

[T21] Swift：遍历
来源：http://dali.ehwqpu.com/Article/details/gtxfatukif.html

for x in a { print(x) }
来源：http://dali.wangshuangyany.cn/Article/details/gtxdezkxah.html

[T22] Swift：字典
来源：http://dali.xuetiantiany.cn/Article/details/gtegjakzmw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.chenlongwang.top/Article/details/gtcnhjufrx.html

[T23] Swift：函数
来源：http://dali.ehwqpu.com/Article/details/gtzahnvuge.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sysykeji.top/Article/details/gtowplzjac.html

[T24] Swift：闭包
来源：http://dali.vqdsnc.cn/Article/details/gtoxsyajda.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtpihetqzu.html

[T25] Swift：结构体
来源：http://dali.xuetiantiany.cn/Article/details/gtfeemlspt.html

struct P { var x: Int }
来源：http://dali.sweek.top/Article/details/gtlygeerdh.html

[T26] Swift：类与重写
来源：http://dali.jinqigufen.top/Article/details/gtsrebxvcq.html

class A: Base { override func f() {} }
来源：http://dali.sxryk.cn/Article/details/gtzpagbcvy.html

[T27] Swift：错误处理
来源：http://dali.ppjwa.cn/Article/details/gtqacupvij.html

do { try f() } catch { print(error) }
来源：http://dali.fzhhl.top/Article/details/gtlybjiwqe.html

[T28] Swift：枚举
来源：http://dali.feifeiyinyue.top/Article/details/gtcepdquwq.html

enum Color { case red, green }
来源：http://dali.yj202588.top/Article/details/gtpefldadl.html

[T29] Swift：guard 提前返回
来源：http://dali.nanxuanxn.top/Article/details/gtpoejcsjp.html

guard let x = opt else { return }
来源：http://dali.jinqigufen.top/Article/details/gtsjkzoama.html

[T30] Swift：协议
来源：http://dali.sweek.top/Article/details/gthhfojjob.html

protocol Shape { func area() -> Double }
来源：http://dali.yonumen.top/Article/details/gtmhvhrsoy.html

[T31] Lua：Hello World
来源：http://dali.yonumen.top/Article/details/gtyznnlqls.html

print("Hello")
来源：http://dali.havefunace.top/Article/details/gtixpusxck.html

[T32] Lua：局部变量
来源：http://dali.nanxinkj.top/Article/details/gtjgcgnvss.html

local a = 1
来源：http://dali.xziqi.cn/Article/details/gtwjuakjid.html

[T33] Lua：表（数组）
来源：http://dali.sysykeji.top/Article/details/gtuexqnyzl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jqgufenzy.top/Article/details/gtfltopvll.html

[T34] Lua：遍历表
来源：http://dali.xuanzx.com/Article/details/gtxqazdinu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cheryme.top/Article/details/gtxctchdvl.html

[T35] Lua：字典表
来源：http://dali.zhengqikj.top/Article/details/gttvpeahqc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.pycfn.com/Article/details/gtqjzgzofo.html

[T36] Lua：函数
来源：http://dali.zdqjudy.top/Article/details/gtynyadhzl.html

function add(a, b) return a + b end
来源：http://dali.yangfankeji.com/Article/details/gtuugorjxc.html

[T37] Lua：字符串拼接
来源：http://dali.hammf.cn/Article/details/gtilvcfctp.html

"a" .. "b"
来源：http://dali.yongpay.top/Article/details/gtehryxbis.html

[T38] Lua：条件
来源：http://dali.tianlin.xyz/Article/details/gtzmhayofo.html

if x > 0 then print("正") end
来源：http://dali.jyoumei.cn/Article/details/gtsggpekhk.html

[T39] Lua：模式匹配
来源：http://dali.316326.xyz/Article/details/gttjwufhdg.html

string.find(s, "%d+")
来源：http://dali.mhx1999.top/Article/details/gtksjossfr.html

[T40] Lua：元表
来源：http://dali.jyoumei.cn/Article/details/gtkwnxhonm.html

setmetatable({}, { __index = base })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtujspggcw.html

[T41] Perl：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtwvdzrupa.html

print "Hello\n";
来源：http://dali.jiagoushi.top/Article/details/gtzflgdzml.html

[T42] Perl：变量类型
来源：http://dali.ydzc1.top/Article/details/gtedrlakjq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.tian-w.cn/Article/details/gttyeacbgm.html

[T43] Perl：字符串插值
来源：http://dali.vqdsnc.cn/Article/details/gtygctgelh.html

"值: $a"
来源：http://dali.yj20258888.top/Article/details/gttopeqkhx.html

[T44] Perl：条件
来源：http://dali.ydzc1.top/Article/details/gtvuwpbiho.html

if ($a > 0) { print "正"; }
来源：http://dali.c1oappe.top/Article/details/gtortxuoqi.html

[T45] Perl：数组遍历
来源：http://dali.jinqigfzy.top/Article/details/gtqlqdeaik.html

for my $x (@arr) { print $x; }
来源：http://dali.jianghu66.top/Article/details/gtrjqeirdb.html

[T46] Perl：哈希操作
来源：http://dali.yuxming.cn/Article/details/gtxokebbju.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cqqwz.cn/Article/details/gtvxdvlnuv.html

[T47] Perl：正则捕获
来源：http://dali.svipenyu.cn/Article/details/gtddoqklxz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.gogol.net.cn/Article/details/gtltxxjwza.html

[T48] Perl：正则替换
来源：http://dali.bjfxy.top/Article/details/gtxqveowod.html

$s =~ s/old/new/g;
来源：http://dali.jqgufenzy.top/Article/details/gtcrqiopgo.html

[T49] Perl：函数
来源：http://dali.mhx1999.top/Article/details/gtcdlnnhoi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.andypj.xyz/Article/details/gtenechums.html

[T50] Perl：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtuzomaqnn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hongshengwenyu.top/Article/details/gtnqxovhoy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sufxvd.cn/Article/details/gtreqegryd.html

[T51] Scala：Hello World
来源：http://dali.andypj.xyz/Article/details/gtlcqfxnwv.html

println("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gtxdoozspc.html

[T52] Scala：变量
来源：http://dali.jianghu66.top/Article/details/gtczirwvkh.html

val a = 1;  var b = 2
来源：http://dali.daria6918.cn/Article/details/gtyeubyowq.html

[T53] Scala：字符串插值
来源：http://dali.zycfv.cn/Article/details/gtjxcpipez.html

s"值: $b"
来源：http://dali.yangfankeji.com/Article/details/gthdabyzms.html

[T54] Scala：集合映射
来源：http://dali.shzxlz.cn/Article/details/gtlsflxdrs.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkrkjohan.html

[T55] Scala：集合过滤
来源：http://dali.vqdsnc.cn/Article/details/gtanncteek.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdgwkkggy.html

[T56] Scala：样例类
来源：http://dali.ppjwa.cn/Article/details/gtkrfusbtk.html

case class User(name: String, age: Int)
来源：http://dali.mhx1999.top/Article/details/gtepxbcumo.html

[T57] Scala：模式匹配
来源：http://dali.wangdashe.top/Article/details/gtxtxubglw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xziqi.cn/Article/details/gtrqfsuxiq.html

[T58] Scala：函数定义
来源：http://dali.shzxlz.cn/Article/details/gtqeqghlwk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.chenjidiqi.icu/Article/details/gtvfbhibwr.html

[T59] Scala：循环
来源：http://dali.aibaodan.cn/Article/details/gtiobgclcz.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhoulong.xyz/Article/details/gtaiephmvh.html

[T60] Scala：折叠
来源：http://dali.hysaishi.cn/Article/details/gtbedglvpr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jqgfzy.top/Article/details/gttzyanogw.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtsibcrxbo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.guannengcc.top/Article/details/gttawdaoaa.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtwyvnhqrh.html

[U01] Py：创建虚拟环境
来源：http://dali.guowangkeji.top/Article/details/gtsywpdnld.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ydzc1.top/Article/details/gtyibwspsq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zdqjudy.top/Article/details/gtxsdglftt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hywenlv.cn/Article/details/gtugpslgzs.html

[U03] Py：加载 .env 配置
来源：http://dali.chenzaomai.com/Article/details/gtvafcbdze.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gotoacloud.top/Article/details/gtvbpzprgk.html

[U04] Py：变量调试打印
来源：http://dali.ydzc1.top/Article/details/gtvjwvwxpr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhoulong.xyz/Article/details/gttcbvytms.html

[U05] Py：列表去重且保序
来源：http://dali.ehwqpu.com/Article/details/gtvdmmmogh.html

list(dict.fromkeys(arr))
来源：http://dali.quarkkingdee.top/Article/details/gtphdugafn.html

[U06] Py：合并两个字典
来源：http://dali.aizwys.cn/Article/details/gtxfaubdiq.html

{**a, **b}
来源：http://dali.feifeiyinyue.top/Article/details/gtnvjsdnae.html

[U07] Py：反转字典键值
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmzvnvlc.html

{v: k for k, v in d.items()}
来源：http://dali.pycfn.com/Article/details/gtnjunonka.html

[U08] Py：展平二维列表
来源：http://dali.guowangkeji.top/Article/details/gtqhfbcabn.html

[y for x in nested for y in x]
来源：http://dali.chenjidiqi.icu/Article/details/gtwixfzmjh.html

[U09] Py：字典取最大值的键
来源：http://dali.xinyue.icu/Article/details/gtyxtymoqn.html

max(d, key=d.get)
来源：http://dali.cucudq.cn/Article/details/gtqcohunvj.html

[U10] Py：按值排序字典
来源：http://dali.tanke756.top/Article/details/gtsrmaacdw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.chenlongwang.top/Article/details/gtsoegtfox.html

[U11] Py：生成器表达式
来源：http://dali.dianchejie.cn/Article/details/gtkonauqdj.html

(x * 2 for x in arr)
来源：http://dali.jlsjyb.cn/Article/details/gtmemuohjd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.andypj.xyz/Article/details/gtfefvcgxx.html

Counter(arr).most_common(3)
来源：http://dali.xinyue.icu/Article/details/gtuwmoopcx.html

[U13] Py：固定长度队列
来源：http://dali.nanxuanxn.top/Article/details/gtcehykeem.html

deque(maxlen=10)
来源：http://dali.mhx1999.top/Article/details/gtmtwjhcgf.html

[U14] Py：分组收集到列表
来源：http://dali.yueranfly.top/Article/details/gteudafagp.html

defaultdict(list)
来源：http://dali.yj20258.top/Article/details/gtvtchsxsk.html

[U15] Py：高精度计时
来源：http://dali.andypj.xyz/Article/details/gtrfaujced.html

t = time.perf_counter()
来源：http://dali.shangyingyoupin.top/Article/details/gtdndordzg.html

[U16] Py：命令行参数解析
来源：http://dali.svipenyu.cn/Article/details/gtvlmohotj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.gzhubu.top/Article/details/gtahemmxhp.html

[U17] Py：初始化日志
来源：http://dali.aibaodan.cn/Article/details/gtkscvrwao.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.cashguo.top/Article/details/gttefsucfs.html

[U18] Py：预编译正则
来源：http://dali.zhiwuduotai.top/Article/details/gtrvktgzek.html

pat = re.compile(r"\d+")
来源：http://dali.wangdashe.top/Article/details/gtlkbdymwg.html

[U19] Py：正则替换带回调
来源：http://dali.shuidangran.top/Article/details/gtmyyfhqtk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xuanzx.com/Article/details/gtovqvgzne.html

[U20] Py：缓存函数结果
来源：http://dali.jlsjyb.cn/Article/details/gtikwcprbh.html

@functools.lru_cache(maxsize=None)
来源：http://dali.sxryk.cn/Article/details/gtbbsfetjl.html

[U21] Py：自定义上下文管理器
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkogbdxmu.html

@contextlib.contextmanager
来源：http://dali.tanke756.top/Article/details/gtxwwrvkcx.html

[U22] Py：矩阵转置
来源：http://dali.sufxvd.cn/Article/details/gtfnvmiwdu.html

list(zip(*m))
来源：http://dali.ehwqpu.com/Article/details/gtiwszwcxr.html

[U23] Py：分块读取大文件
来源：http://dali.chenlongwang.top/Article/details/gttkxojewd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.kuanghao11.cn/Article/details/gtdzmefgrh.html

[U24] Py：路径操作
来源：http://dali.redwolf501.top/Article/details/gtjqbvrrur.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cdnleiting.top/Article/details/gtndevgbhu.html

[U25] Py：CSV 按字典读
来源：http://dali.shangyingyoupin.top/Article/details/gteiabyxrv.html

csv.DictReader(f)
来源：http://dali.aibaodan.cn/Article/details/gtpakdnhhp.html

[U26] Py：并发下载
来源：http://dali.jianghu66.top/Article/details/gtczbwbtor.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.svipenyu.cn/Article/details/gtyvlcoddu.html

[U27] Py：异步 HTTP
来源：http://dali.guannengcc.top/Article/details/gtjtuqscel.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixyaimgn.html

[U28] Py：类型别名
来源：http://dali.yj20258888.top/Article/details/gtjjfrgjwg.html

UserId = int
来源：http://dali.316326.xyz/Article/details/gtxpautvhd.html

[U29] Py：属性校验
来源：http://dali.xuetiantiany.cn/Article/details/gtgcwyjmag.html

@property 与 @x.setter 配合
来源：http://dali.nanxuanxn.top/Article/details/gtrooaubcp.html

[U30] Py：数据类
来源：http://dali.nwbrower.top/Article/details/gtnmrmhqxu.html

@dataclass(slots=True)
来源：http://dali.wangdashe.top/Article/details/gtkgudvlpo.html

[U31] Py：单测
来源：http://dali.redwolf501.top/Article/details/gtsrxcmkcq.html

python -m pytest -q
来源：http://dali.bjfxy.top/Article/details/gtbtrurdvd.html

[U32] Py：代码格式化
来源：http://dali.ybcxt.top/Article/details/gtdlgeypcq.html

ruff format . && ruff check --fix .
来源：http://dali.meibo888.top/Article/details/gtjuaqmlui.html

[U33] Py：打包发布
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxqznavqo.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xziqi.cn/Article/details/gtmmydcfhz.html

[U34] Py：判断编码
来源：http://dali.zdqjudy.top/Article/details/gtfmahnynz.html

chardet.detect(raw)
来源：http://dali.gaohongyu789.top/Article/details/gtjqfvyiev.html

[U35] Py：发送邮件
来源：http://dali.yonumen.top/Article/details/gttxgknhvq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhoulong.xyz/Article/details/gttxlrgunu.html

[U36] Py：定时任务
来源：http://dali.zhoulong.xyz/Article/details/gthawltbuq.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhixingplan.top/Article/details/gtyfhrlbic.html

[U37] Py：读写 Excel
来源：http://dali.andypj.xyz/Article/details/gtxcmwfyfc.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.redwolf501.top/Article/details/gtuyxvxtst.html

[U38] Py：获取脚本所在目录
来源：http://dali.yvedp.cn/Article/details/gtpfdviojg.html

Path(__file__).resolve().parent
来源：http://dali.pengpengdd.cyou/Article/details/gtimbgrshc.html

[U39] Py：判断是否在交互环境
来源：http://dali.yj20258888.top/Article/details/gtclmlesrb.html

sys.stdout.isatty()
来源：http://dali.zhengqikj.top/Article/details/gtefisquii.html

[U40] Py：打印到标准错误
来源：http://dali.c1oappe.top/Article/details/gtgqavosbk.html

print("err", file=sys.stderr)
来源：http://dali.chenzaomai.com/Article/details/gttssoyiim.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yj20258888.top/Article/details/gtladgkpob.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shzxlz.cn/Article/details/gtywnfhrdx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.kuanghao11.cn/Article/details/gtkbzvdswj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gtioapcxxe.html

[U43] PHP：声明命名空间
来源：http://dali.fengsongda.top/Article/details/gtvzmnpxjg.html

namespace App\Http;
来源：http://dali.fzhhl.top/Article/details/gtwirfnlgo.html

[U44] PHP：开启严格类型
来源：http://dali.dianchejie.cn/Article/details/gtdzhscuru.html

declare(strict_types=1);
来源：http://dali.ivvv.top/Article/details/gtxfdqtbkv.html


<!-- 参考信息 -->