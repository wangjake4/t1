代发 wailian999

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.fzhhl.top/Article/details/gtftmbzjkr.html

[S21] C：字符类别判断
来源：http://dali.cheryme.top/Article/details/gtctiabwkl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.pengpengdd.cyou/Article/details/gtyquxxjcy.html

[S22] C：字符串转数字
来源：http://dali.aibaodan.cn/Article/details/gtuwckwwnj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gzhubu.top/Article/details/gtlzcgqyug.html

[S23] C：随机数
来源：http://dali.daxiang520.top/Article/details/gtnduyunvo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.birdmap.top/Article/details/gtmiaapbsj.html

[S24] C：获取本地时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtchxnwvao.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jyoumei.cn/Article/details/gtteuzsbfu.html

[S25] C：内存拷贝
来源：http://dali.wangshuangyany.cn/Article/details/gtodeusfal.html

memcpy(dst, src, n);
来源：http://dali.aibaodan.cn/Article/details/gtvqgazwmr.html

[S26] C：内存清零
来源：http://dali.316326.xyz/Article/details/gtulhcnwnv.html

memset(a, 0, sizeof a);
来源：http://dali.wangdashe.top/Article/details/gtxyyvsprf.html

[S27] C：定义常量
来源：http://dali.wangshuangyany.cn/Article/details/gtjbxyjbge.html

const double PI = 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gtgbmxpxgn.html

[S28] C：静态变量
来源：http://dali.iojbl.cn/Article/details/gthmyhepwf.html

static int counter = 0;
来源：http://dali.9152youxi.cn/Article/details/gtttfotcyt.html

[S29] C：变参函数
来源：http://dali.zhixingplan.top/Article/details/gtgibgkayx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shzxlz.cn/Article/details/gtjopirgwm.html

[S30] C：头文件保护
来源：http://dali.shzxlz.cn/Article/details/gtexxvhirs.html

#ifndef X_H
来源：http://dali.hfpthk.cn/Article/details/gtecmzdpaq.html

#define X_H
来源：http://dali.hongshengwenyu.top/Article/details/gtloqqbiyh.html

#endif
来源：http://dali.cheryme.top/Article/details/gtwyebbedr.html

[S31] C++：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtgmhrgojq.html

#include <iostream>
来源：http://dali.yangfankeji.com/Article/details/gtqclqpsld.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.kuanghao11.cn/Article/details/gtultxzxnh.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gtxnfnzqwl.html

std::string s = "hi";  s += "!";
来源：http://dali.quarkkingdee.top/Article/details/gtqlqpltgy.html

[S33] C++：vector 增删
来源：http://dali.haohaochexian.top/Article/details/gtvdrypleh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cheryme.top/Article/details/gtgwdrlrxf.html

[S34] C++：遍历 vector
来源：http://dali.gzhubu.top/Article/details/gtngprzjnm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.bjfxy.top/Article/details/gtjjalxiwv.html

[S35] C++：map
来源：http://dali.daxiang520.top/Article/details/gtpdkugaei.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258.top/Article/details/gtmgouujal.html

[S36] C++：unordered_map
来源：http://dali.zycfv.cn/Article/details/gtufhvlplb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gteoedrsvh.html

[S37] C++：set
来源：http://dali.aizwys.cn/Article/details/gttzwrcfss.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gtophkngkz.html

[S38] C++：排序
来源：http://dali.shuidangran.top/Article/details/gthaevrpln.html

std::sort(v.begin(), v.end());
来源：http://dali.yuxming.cn/Article/details/gtmhagywmw.html

[S39] C++：自定义比较器排序
来源：http://dali.guannengcc.top/Article/details/gtpbzkxvch.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shuidangran.top/Article/details/gtpyonsdws.html

[S40] C++：查找元素
来源：http://dali.chenlongwang.top/Article/details/gtsdihlipf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xylfe.cn/Article/details/gtikleksae.html

[S41] C++：类与构造函数
来源：http://dali.fzhhl.top/Article/details/gtlnwozimx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gzhubu.top/Article/details/gtskvrsvnx.html

[S42] C++：继承与虚函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavzmdtrn.html

class B : public Base { public: void f() override {} };
来源：http://dali.zdqjudy.top/Article/details/gtltmqrzjt.html

[S43] C++：智能指针
来源：http://dali.daria6918.cn/Article/details/gtzsdevuxl.html

auto p = std::make_unique<int>(5);
来源：http://dali.cheryme.top/Article/details/gthwryotih.html

[S44] C++：引用传参
来源：http://dali.316326.xyz/Article/details/gtddykczlu.html

void inc(int &x) { ++x; }
来源：http://dali.tian-w.cn/Article/details/gtllhqqqjy.html

[S45] C++：lambda
来源：http://dali.cdnleiting.top/Article/details/gtqrzadket.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.wangshuangyany.cn/Article/details/gtheorazqt.html

[S46] C++：函数模板
来源：http://dali.hammf.cn/Article/details/gttqxztfwp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.bjfxy.top/Article/details/gtiutblsyo.html

[S47] C++：结构化绑定遍历
来源：http://dali.cheryme.top/Article/details/gterimemov.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tianlin.xyz/Article/details/gttuntsrku.html

[S48] C++：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gtnrriuvec.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtangdudss.html

while (std::getline(in, line)) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabglwzes.html

[S49] C++：写文件
来源：http://dali.xylfe.cn/Article/details/gtumzvnxkg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cashguo.top/Article/details/gtvulftakz.html

[S50] C++：格式化数字
来源：http://dali.zhongyouzk.top/Article/details/gtvgvkohaa.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtgthsjmzn.html

[S51] C++：显式类型转换
来源：http://dali.jyoumei.cn/Article/details/gtopvzfqyk.html

static_cast<double>(a) / b
来源：http://dali.meibo888.top/Article/details/gtugjpefat.html

[S52] C++：const 与 noexcept
来源：http://dali.fzhhl.top/Article/details/gtickccbpq.html

int size() const noexcept { return n_; }
来源：http://dali.wangshuangyany.cn/Article/details/gtipiafebt.html

[S53] C++：移动语义
来源：http://dali.0kj1m.cn/Article/details/gtiioffhxi.html

std::vector<int> w = std::move(v);
来源：http://dali.yuanzhike.top/Article/details/gthyqqxrmo.html

[S54] C++：异常处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzkdudent.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jlsjyb.cn/Article/details/gtdrxhxuuf.html

[S55] C++：结构化绑定
来源：http://dali.jqgfzy.top/Article/details/gtktoprblv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nanxuanxn.top/Article/details/gtpxiajvcc.html

[S56] C++：optional
来源：http://dali.sxryk.cn/Article/details/gtavfritsk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shzxlz.cn/Article/details/gtpyykmwcs.html

[S57] C++：编译期常量
来源：http://dali.quarkkingdee.top/Article/details/gtvdrmqegu.html

constexpr int N = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gthucppnhi.html

[S58] C++：命名空间
来源：http://dali.cqqwz.cn/Article/details/gtftfniwnb.html

namespace ns { int f() { return 1; } }
来源：http://dali.cucudq.cn/Article/details/gtqupjnoon.html

[S59] C++：静态断言
来源：http://dali.tanke756.top/Article/details/gttutznazo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yueranfly.top/Article/details/gtqmbuburq.html

[S60] C++：遍历并删除元素
来源：http://dali.shangyingyoupin.top/Article/details/gtyyoqyond.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yonumen.top/Article/details/gtocpbtmcg.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtrxyxqdtf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.svipenyu.cn/Article/details/gtonyxvhfj.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtoiohxztn.html

[T01] Kotlin：Hello World
来源：http://dali.xuanzx.com/Article/details/gtthchbcgu.html

println("Hello")
来源：http://dali.hfpthk.cn/Article/details/gtlbeasmma.html

[T02] Kotlin：变量
来源：http://dali.cheryme.top/Article/details/gtawwfpvlv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.daxiang520.top/Article/details/gtojxdiwxi.html

[T03] Kotlin：字符串模板
来源：http://dali.cheryme.top/Article/details/gtkpermevf.html

"值: $b"
来源：http://dali.hfpthk.cn/Article/details/gtoleetpwd.html

[T04] Kotlin：空安全
来源：http://dali.jinghuilouyu.cn/Article/details/gtyctlrqfz.html

val n: String? = null;  n?.length
来源：http://dali.jlsjyb.cn/Article/details/gtqtqiqyyl.html

[T05] Kotlin：when 表达式
来源：http://dali.sweek.top/Article/details/gtpxnxqaxc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.feifeiyinyue.top/Article/details/gtmudofwdq.html

[T06] Kotlin：集合映射
来源：http://dali.jiagoushi.top/Article/details/gttcalpblp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gthvwzpdiu.html

[T07] Kotlin：集合过滤
来源：http://dali.jinqigufen.top/Article/details/gtulbvciiq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.316326.xyz/Article/details/gteaoiivxl.html

[T08] Kotlin：数据类
来源：http://dali.jiagoushi.top/Article/details/gtnohjlaqt.html

data class User(val name: String, val age: Int)
来源：http://dali.yvedp.cn/Article/details/gtwxsplmlj.html

[T09] Kotlin：扩展函数
来源：http://dali.zhongyouzk.top/Article/details/gtjhwhrdjn.html

fun String.exclaim() = this + "!"
来源：http://dali.jinqigfzy.top/Article/details/gtbavdgwnk.html

[T10] Kotlin：默认参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthtbnlkyg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jyoumei.cn/Article/details/gtuhkaomnd.html

[T11] Kotlin：协程
来源：http://dali.sxryk.cn/Article/details/gtvlvllubh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sufxvd.cn/Article/details/gthiyhthxf.html

[T12] Kotlin：解构声明
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjqnhrkwi.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenlongwang.top/Article/details/gtyrwcimjn.html

[T13] Kotlin：只读 Map
来源：http://dali.jlsjyb.cn/Article/details/gtherrbuwh.html

val m = mapOf("a" to 1)
来源：http://dali.svipenyu.cn/Article/details/gtwaoxeruu.html

[T14] Kotlin：循环
来源：http://dali.ybcxt.top/Article/details/gtsermkmyh.html

for (i in 1..10) println(i)
来源：http://dali.tian-w.cn/Article/details/gtaqmwnjvp.html

[T15] Kotlin：接口
来源：http://dali.zhoulong.xyz/Article/details/gtjxpbeibb.html

interface Shape { fun area(): Double }
来源：http://dali.yj20258.top/Article/details/gtldqntnnt.html

[T16] Swift：Hello World
来源：http://dali.xziqi.cn/Article/details/gtklpxpvzj.html

print("Hello")
来源：http://dali.chenzaomai.com/Article/details/gtggybpkoe.html

[T17] Swift：变量与常量
来源：http://dali.sweek.top/Article/details/gtnzqgwzde.html

var a = 1;  let b = 2
来源：http://dali.c1oappe.top/Article/details/gtsiczthnu.html

[T18] Swift：字符串插值
来源：http://dali.guannengcc.top/Article/details/gtoigmijis.html

"值: \(b)"
来源：http://dali.hnxiangtu.top/Article/details/gtohporhkd.html

[T19] Swift：可选绑定
来源：http://dali.gotoacloud.top/Article/details/gtprfaaesa.html

if let n = opt { print(n) }
来源：http://dali.zycfv.cn/Article/details/gtasyulzvg.html

[T20] Swift：数组操作
来源：http://dali.316326.xyz/Article/details/gtjsgrswiv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shzxlz.cn/Article/details/gtinhbquvg.html

[T21] Swift：遍历
来源：http://dali.mhx1999.top/Article/details/gtiwaotsjd.html

for x in a { print(x) }
来源：http://dali.hammf.cn/Article/details/gtzgzjsklg.html

[T22] Swift：字典
来源：http://dali.shuidangran.top/Article/details/gtghpdamxw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqycyytul.html

[T23] Swift：函数
来源：http://dali.hnxiangtu.top/Article/details/gtgsqbhswp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.chenzaomai.com/Article/details/gtbitnybfn.html

[T24] Swift：闭包
来源：http://dali.ydzc1.top/Article/details/gtqqqqirbx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gotoacloud.top/Article/details/gtzyyiullx.html

[T25] Swift：结构体
来源：http://dali.quarkkingdee.top/Article/details/gtvkmbsatd.html

struct P { var x: Int }
来源：http://dali.shangyingyoupin.top/Article/details/gtjpwbahac.html

[T26] Swift：类与重写
来源：http://dali.bjfxy.top/Article/details/gtuzvtyjtf.html

class A: Base { override func f() {} }
来源：http://dali.yuxming.cn/Article/details/gtvuvpenvi.html

[T27] Swift：错误处理
来源：http://dali.cashguo.top/Article/details/gtqvqzzovl.html

do { try f() } catch { print(error) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtavxastah.html

[T28] Swift：枚举
来源：http://dali.havefunace.top/Article/details/gtilojoubp.html

enum Color { case red, green }
来源：http://dali.shuidangran.top/Article/details/gtsrxpvoqs.html

[T29] Swift：guard 提前返回
来源：http://dali.aibaodan.cn/Article/details/gtmrvohvgm.html

guard let x = opt else { return }
来源：http://dali.smart0.xyz/Article/details/gtuuruphre.html

[T30] Swift：协议
来源：http://dali.xylfe.cn/Article/details/gtpzjjcqpo.html

protocol Shape { func area() -> Double }
来源：http://dali.havefunace.top/Article/details/gtialjqqcd.html

[T31] Lua：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtxookukuf.html

print("Hello")
来源：http://dali.ydzc1.top/Article/details/gtbobsbxkd.html

[T32] Lua：局部变量
来源：http://dali.yvedp.cn/Article/details/gtgpixlyvp.html

local a = 1
来源：http://dali.jinqigufen.top/Article/details/gtjidqgyfh.html

[T33] Lua：表（数组）
来源：http://dali.shzxlz.cn/Article/details/gtwpuqtczo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.nanxinkj.top/Article/details/gtprrkoqnb.html

[T34] Lua：遍历表
来源：http://dali.shzxlz.cn/Article/details/gtyeshswdm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.redwolf501.top/Article/details/gtmgnyfall.html

[T35] Lua：字典表
来源：http://dali.jqgfzy.top/Article/details/gtswveutcy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gzhubu.top/Article/details/gtnmajhbky.html

[T36] Lua：函数
来源：http://dali.tian-w.cn/Article/details/gthjoajdky.html

function add(a, b) return a + b end
来源：http://dali.hywenlv.cn/Article/details/gtztkgntek.html

[T37] Lua：字符串拼接
来源：http://dali.gotoacloud.top/Article/details/gtrwxuahts.html

"a" .. "b"
来源：http://dali.yangfankeji.com/Article/details/gtwkbfegal.html

[T38] Lua：条件
来源：http://dali.nanxuanxn.top/Article/details/gtidztmbrg.html

if x > 0 then print("正") end
来源：http://dali.birdmap.top/Article/details/gtaqjomlhq.html

[T39] Lua：模式匹配
来源：http://dali.sufxvd.cn/Article/details/gtoyqmhles.html

string.find(s, "%d+")
来源：http://dali.ppjwa.cn/Article/details/gtalfftbon.html

[T40] Lua：元表
来源：http://dali.gaohongyu789.top/Article/details/gtctefdplk.html

setmetatable({}, { __index = base })
来源：http://dali.c1oappe.top/Article/details/gtdwztanid.html

[T41] Perl：Hello World
来源：http://dali.daxiang520.top/Article/details/gtrdkrntre.html

print "Hello\n";
来源：http://dali.yvedp.cn/Article/details/gtsakjttnp.html

[T42] Perl：变量类型
来源：http://dali.daria6918.cn/Article/details/gtoynjszsz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.chenlongwang.top/Article/details/gtvspqzhqv.html

[T43] Perl：字符串插值
来源：http://dali.kuanghao11.cn/Article/details/gtmxzdxtvm.html

"值: $a"
来源：http://dali.dashuyun.cn/Article/details/gtuyykktpv.html

[T44] Perl：条件
来源：http://dali.yangfankeji.com/Article/details/gtqpdxqwob.html

if ($a > 0) { print "正"; }
来源：http://dali.zhongyouzk.top/Article/details/gtkpcmabsg.html

[T45] Perl：数组遍历
来源：http://dali.cashguo.top/Article/details/gtyzneequg.html

for my $x (@arr) { print $x; }
来源：http://dali.zhoulong.xyz/Article/details/gtftbbegdv.html

[T46] Perl：哈希操作
来源：http://dali.jqgufenzy.top/Article/details/gtenhoyqlh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jlsjyb.cn/Article/details/gtjjwwgsun.html

[T47] Perl：正则捕获
来源：http://dali.ybcxt.top/Article/details/gtmhlcsans.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hysaishi.cn/Article/details/gtjavgmpig.html

[T48] Perl：正则替换
来源：http://dali.snrcjt.cn/Article/details/gtpqsjhjbj.html

$s =~ s/old/new/g;
来源：http://dali.hnxiangtu.top/Article/details/gtfjjcabez.html

[T49] Perl：函数
来源：http://dali.tianlin.xyz/Article/details/gtsryoakyp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfwuylqtf.html

[T50] Perl：逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtyytyuoln.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gaohongyu789.top/Article/details/gtrwquntck.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.iojbl.cn/Article/details/gtujzucsds.html

[T51] Scala：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtenpcxdex.html

println("Hello")
来源：http://dali.hnqzz.top/Article/details/gtibsbproz.html

[T52] Scala：变量
来源：http://dali.zhixingplan.top/Article/details/gtlmwaojle.html

val a = 1;  var b = 2
来源：http://dali.pycfn.com/Article/details/gtainjktwc.html

[T53] Scala：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gtbjxggokj.html

s"值: $b"
来源：http://dali.yvedp.cn/Article/details/gtvtgccnhs.html

[T54] Scala：集合映射
来源：http://dali.dashuyun.cn/Article/details/gttksooqmu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.bjfxy.top/Article/details/gtvnqopaxr.html

[T55] Scala：集合过滤
来源：http://dali.tian-w.cn/Article/details/gtagkfstbc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sweek.top/Article/details/gtfcmyezlj.html

[T56] Scala：样例类
来源：http://dali.vqdsnc.cn/Article/details/gtxjtthcxz.html

case class User(name: String, age: Int)
来源：http://dali.sysykeji.top/Article/details/gtmpfthgzi.html

[T57] Scala：模式匹配
来源：http://dali.hammf.cn/Article/details/gtagyyvxcs.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jqgfzy.top/Article/details/gtmjvayord.html

[T58] Scala：函数定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gttxirfbgk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.feifeiyinyue.top/Article/details/gtklankigr.html

[T59] Scala：循环
来源：http://dali.jianghu66.top/Article/details/gthuoifctb.html

for (i <- 1 to 10) println(i)
来源：http://dali.hnqzz.top/Article/details/gtzkubwifz.html

[T60] Scala：折叠
来源：http://dali.fzhhl.top/Article/details/gtzpkashox.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jqgfzy.top/Article/details/gtwmuywckm.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtnrtzrbst.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.dianchejie.cn/Article/details/gthyduospw.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtjoxzonzn.html

[U01] Py：创建虚拟环境
来源：http://dali.xylfe.cn/Article/details/gtmjhdhwhz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xziqi.cn/Article/details/gtnoxiqjiq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.fengsongda.top/Article/details/gtilztaszt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.chenzaomai.com/Article/details/gthyrsgnrl.html

[U03] Py：加载 .env 配置
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsbqsvfen.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.pycfn.com/Article/details/gtwxjqajhb.html

[U04] Py：变量调试打印
来源：http://dali.cucudq.cn/Article/details/gtucqrvbgw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cucudq.cn/Article/details/gtsummpusb.html

[U05] Py：列表去重且保序
来源：http://dali.iojbl.cn/Article/details/gthjuclqdh.html

list(dict.fromkeys(arr))
来源：http://dali.ehwqpu.com/Article/details/gtftvciudh.html

[U06] Py：合并两个字典
来源：http://dali.xuetiantiany.cn/Article/details/gtltgvpnpv.html

{**a, **b}
来源：http://dali.cqqwz.cn/Article/details/gtjvxpcxmi.html

[U07] Py：反转字典键值
来源：http://dali.cashguo.top/Article/details/gteqecxgic.html

{v: k for k, v in d.items()}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkikjozjc.html

[U08] Py：展平二维列表
来源：http://dali.yanxiufei.cn/Article/details/gtivgfqexn.html

[y for x in nested for y in x]
来源：http://dali.daxiang520.top/Article/details/gtsqvbgmfi.html

[U09] Py：字典取最大值的键
来源：http://dali.tianlin.xyz/Article/details/gtenhxqkps.html

max(d, key=d.get)
来源：http://dali.snrcjt.cn/Article/details/gtpgprzdsa.html

[U10] Py：按值排序字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gtncdqvowq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.pycfn.com/Article/details/gttuaeqebr.html

[U11] Py：生成器表达式
来源：http://dali.ydzc1.top/Article/details/gtbmhtowwf.html

(x * 2 for x in arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtjlmsqhwi.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.9152youxi.cn/Article/details/gtrtsenikc.html

Counter(arr).most_common(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtxqmplxsz.html

[U13] Py：固定长度队列
来源：http://dali.nanxuanxn.top/Article/details/gtjtazldux.html

deque(maxlen=10)
来源：http://dali.smart0.xyz/Article/details/gtnhpzwctv.html

[U14] Py：分组收集到列表
来源：http://dali.fzhhl.top/Article/details/gtijykyuxb.html

defaultdict(list)
来源：http://dali.xuanzx.com/Article/details/gtfhdnanih.html

[U15] Py：高精度计时
来源：http://dali.hnqzz.top/Article/details/gtnzodkwqa.html

t = time.perf_counter()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzkbmiwbn.html

[U16] Py：命令行参数解析
来源：http://dali.9152youxi.cn/Article/details/gtvulukaes.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ybcxt.top/Article/details/gtwcsdupwn.html

[U17] Py：初始化日志
来源：http://dali.yonumen.top/Article/details/gtyzfpctrv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ehwqpu.com/Article/details/gttiismxhq.html

[U18] Py：预编译正则
来源：http://dali.redwolf501.top/Article/details/gtktqtbvrj.html

pat = re.compile(r"\d+")
来源：http://dali.chenjidiqi.icu/Article/details/gtfjhrsaaq.html

[U19] Py：正则替换带回调
来源：http://dali.gotoacloud.top/Article/details/gtehirnyqj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.iojbl.cn/Article/details/gttrfdjlbq.html

[U20] Py：缓存函数结果
来源：http://dali.wangshuangyany.cn/Article/details/gtwvlkhfup.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzsbmedqr.html

[U21] Py：自定义上下文管理器
来源：http://dali.sysykeji.top/Article/details/gtnxwvpngz.html

@contextlib.contextmanager
来源：http://dali.guowangkeji.top/Article/details/gtszqnshou.html

[U22] Py：矩阵转置
来源：http://dali.yanxiufei.cn/Article/details/gtzxyyjktw.html

list(zip(*m))
来源：http://dali.shangyingyoupin.top/Article/details/gtbauouohg.html

[U23] Py：分块读取大文件
来源：http://dali.sweek.top/Article/details/gthwvpqkxu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.svipenyu.cn/Article/details/gtjmhovwan.html

[U24] Py：路径操作
来源：http://dali.yongpay.top/Article/details/gtxsqevxww.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhiwuduotai.top/Article/details/gtmfgzvdww.html

[U25] Py：CSV 按字典读
来源：http://dali.ppjwa.cn/Article/details/gtluiviwxa.html

csv.DictReader(f)
来源：http://dali.sysykeji.top/Article/details/gtntkdaylm.html

[U26] Py：并发下载
来源：http://dali.birdmap.top/Article/details/gtfsctwjru.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.fzhhl.top/Article/details/gtsjwnuind.html

[U27] Py：异步 HTTP
来源：http://dali.mhx1999.top/Article/details/gtewibtzdo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xylfe.cn/Article/details/gtofgbujgu.html

[U28] Py：类型别名
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqitbwnj.html

UserId = int
来源：http://dali.316326.xyz/Article/details/gtuuboxuem.html

[U29] Py：属性校验
来源：http://dali.ydzc1.top/Article/details/gthrdhauee.html

@property 与 @x.setter 配合
来源：http://dali.gotoacloud.top/Article/details/gtywomlhsv.html

[U30] Py：数据类
来源：http://dali.sweek.top/Article/details/gtvwjlpqwl.html

@dataclass(slots=True)
来源：http://dali.yuanzhike.top/Article/details/gtisxtfiwe.html

[U31] Py：单测
来源：http://dali.bjfxy.top/Article/details/gtzgaemspi.html

python -m pytest -q
来源：http://dali.wangshuangyany.cn/Article/details/gtmzmjtlfp.html

[U32] Py：代码格式化
来源：http://dali.jyoumei.cn/Article/details/gtqkkimmnr.html

ruff format . && ruff check --fix .
来源：http://dali.zhoulong.xyz/Article/details/gtsvtckmhj.html

[U33] Py：打包发布
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmuyjvlmg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.quarkkingdee.top/Article/details/gtjzergzlz.html

[U34] Py：判断编码
来源：http://dali.yongpay.top/Article/details/gtrukgftkd.html

chardet.detect(raw)
来源：http://dali.feifeiyinyue.top/Article/details/gtqtemjmmt.html

[U35] Py：发送邮件
来源：http://dali.c1oappe.top/Article/details/gtkvmlmrah.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cucudq.cn/Article/details/gtelgqqack.html

[U36] Py：定时任务
来源：http://dali.xziqi.cn/Article/details/gtrpvnheoj.html

schedule.every(10).minutes.do(job)
来源：http://dali.gogol.net.cn/Article/details/gttkhnunfr.html

[U37] Py：读写 Excel
来源：http://dali.tianlin.xyz/Article/details/gtsltwwnnq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhixingplan.top/Article/details/gtrglnlgtw.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhengqikj.top/Article/details/gtfimdipbe.html

Path(__file__).resolve().parent
来源：http://dali.cucudq.cn/Article/details/gttbsquyiy.html

[U39] Py：判断是否在交互环境
来源：http://dali.yongpay.top/Article/details/gtvoyzoslh.html

sys.stdout.isatty()
来源：http://dali.jqgufenzy.top/Article/details/gtbdhxtkzm.html

[U40] Py：打印到标准错误
来源：http://dali.cheryme.top/Article/details/gtugqydmvm.html

print("err", file=sys.stderr)
来源：http://dali.gaohongyu789.top/Article/details/gtuxynddsn.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.havefunace.top/Article/details/gtkamjxumf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.guowangkeji.top/Article/details/gteutdczrp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jinghuilouyu.cn/Article/details/gtuilktgjg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jinqigfzy.top/Article/details/gtotnefine.html

[U43] PHP：声明命名空间
来源：http://dali.jqgfzy.top/Article/details/gtzclyxitx.html

namespace App\Http;
来源：http://dali.feifeiyinyue.top/Article/details/gtgmuutqxg.html

[U44] PHP：开启严格类型
来源：http://dali.chenzaomai.com/Article/details/gtbjrgyxor.html

declare(strict_types=1);
来源：http://dali.cqqwz.cn/Article/details/gthswdlred.html


<!-- 参考信息 -->