代发 wailian999

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gtelvqdfrl.html

[S15] C：类型转换
来源：http://dali.zhongyouzk.top/Article/details/gtegrynruf.html

(double) a / b
来源：http://dali.xylfe.cn/Article/details/gtdofccher.html

[S16] C：位操作置位
来源：http://dali.pycfn.com/Article/details/gtyhbdwwgo.html

x |= (1 << 3);
来源：http://dali.aizwys.cn/Article/details/gtwbfaukvw.html

[S17] C：安全拼接字符串
来源：http://dali.yj202588.top/Article/details/gtnnqjotvu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.quarkkingdee.top/Article/details/gtuwzflmkc.html

[S18] C：命令行参数
来源：http://dali.yj20258.top/Article/details/gtmwqraepk.html

int main(int argc, char **argv)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdellextj.html

[S19] C：快速排序
来源：http://dali.sweek.top/Article/details/gthmmbayyt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.redwolf501.top/Article/details/gtbxcpgpis.html

[S20] C：二分查找
来源：http://dali.shuidangran.top/Article/details/gtjnwljtcf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpfceqnyh.html

[S21] C：字符类别判断
来源：http://dali.xinyue.icu/Article/details/gteutdcjpv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tian-w.cn/Article/details/gtznfrgbyf.html

[S22] C：字符串转数字
来源：http://dali.hongshengwenyu.top/Article/details/gtinpqyogs.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.316326.xyz/Article/details/gtbgakladn.html

[S23] C：随机数
来源：http://dali.meibo888.top/Article/details/gtftjovdrz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shzxlz.cn/Article/details/gtqcrjjarp.html

[S24] C：获取本地时间
来源：http://dali.wangdashe.top/Article/details/gtxpoaywws.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ehwqpu.com/Article/details/gtkprivcdo.html

[S25] C：内存拷贝
来源：http://dali.yangfankeji.com/Article/details/gtrjjzutiu.html

memcpy(dst, src, n);
来源：http://dali.hammf.cn/Article/details/gtjnszqvlt.html

[S26] C：内存清零
来源：http://dali.hnqzz.top/Article/details/gtcrmkoxyl.html

memset(a, 0, sizeof a);
来源：http://dali.sweek.top/Article/details/gtvwehwhnq.html

[S27] C：定义常量
来源：http://dali.sweek.top/Article/details/gttvnaujtm.html

const double PI = 3.14159;
来源：http://dali.meibo888.top/Article/details/gtnwetnrxi.html

[S28] C：静态变量
来源：http://dali.bjfxy.top/Article/details/gtamsxpoot.html

static int counter = 0;
来源：http://dali.yuanzhike.top/Article/details/gtrxelzdvn.html

[S29] C：变参函数
来源：http://dali.dianchejie.cn/Article/details/gtmnmcsyic.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.fengsongda.top/Article/details/gtttjvlfud.html

[S30] C：头文件保护
来源：http://dali.shzxlz.cn/Article/details/gtqoumqrci.html

#ifndef X_H
来源：http://dali.aibaodan.cn/Article/details/gtakfeuipm.html

#define X_H
来源：http://dali.pycfn.com/Article/details/gteojkaauy.html

#endif
来源：http://dali.c1oappe.top/Article/details/gtofsukncr.html

[S31] C++：Hello World
来源：http://dali.smart0.xyz/Article/details/gtxyhdskan.html

#include <iostream>
来源：http://dali.yj202588.top/Article/details/gtjdscnmtf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tian-w.cn/Article/details/gtoulwcucj.html

[S32] C++：字符串
来源：http://dali.yuxming.cn/Article/details/gtvaozxjqh.html

std::string s = "hi";  s += "!";
来源：http://dali.9152youxi.cn/Article/details/gtormbutbi.html

[S33] C++：vector 增删
来源：http://dali.quarkkingdee.top/Article/details/gtquodsazy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ppjwa.cn/Article/details/gtgwhpiuqc.html

[S34] C++：遍历 vector
来源：http://dali.zhiwuduotai.top/Article/details/gtsyzsukkz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hnxiangtu.top/Article/details/gtrlubjdkp.html

[S35] C++：map
来源：http://dali.feifeiyinyue.top/Article/details/gtdcfzlxmk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sweek.top/Article/details/gtbndwfdlj.html

[S36] C++：unordered_map
来源：http://dali.cqqwz.cn/Article/details/gtxrgeadtu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yvedp.cn/Article/details/gtpyqqeunb.html

[S37] C++：set
来源：http://dali.gotoacloud.top/Article/details/gtnvioqrrn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jqgfzy.top/Article/details/gtdoomlnwp.html

[S38] C++：排序
来源：http://dali.andypj.xyz/Article/details/gtqpohvskv.html

std::sort(v.begin(), v.end());
来源：http://dali.zhoulong.xyz/Article/details/gtlgktqbnl.html

[S39] C++：自定义比较器排序
来源：http://dali.chenzaomai.com/Article/details/gtyduclyvd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yanxiufei.cn/Article/details/gtlszuaptr.html

[S40] C++：查找元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyoiblxjx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtpbemtkrj.html

[S41] C++：类与构造函数
来源：http://dali.yj20258888.top/Article/details/gtwiaapjlr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.316326.xyz/Article/details/gtjekztpsr.html

[S42] C++：继承与虚函数
来源：http://dali.pycfn.com/Article/details/gtgorossbf.html

class B : public Base { public: void f() override {} };
来源：http://dali.xuanzx.com/Article/details/gtwyxvflwj.html

[S43] C++：智能指针
来源：http://dali.shzxlz.cn/Article/details/gtpmlynpip.html

auto p = std::make_unique<int>(5);
来源：http://dali.bjfxy.top/Article/details/gtmxiebwbx.html

[S44] C++：引用传参
来源：http://dali.tanke756.top/Article/details/gtbbpsnczx.html

void inc(int &x) { ++x; }
来源：http://dali.ivvv.top/Article/details/gtcecekfpp.html

[S45] C++：lambda
来源：http://dali.nanxuanxn.top/Article/details/gtdbjgfmlo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hongshengwenyu.top/Article/details/gtrbuhjwoh.html

[S46] C++：函数模板
来源：http://dali.smart0.xyz/Article/details/gtepfynkex.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yuanzhike.top/Article/details/gtfawusfqj.html

[S47] C++：结构化绑定遍历
来源：http://dali.shuidangran.top/Article/details/gtdkkjvwbu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hfpthk.cn/Article/details/gtlhopqogv.html

[S48] C++：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gtdlugemsd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.dianchejie.cn/Article/details/gtscyttjmb.html

while (std::getline(in, line)) { }
来源：http://dali.jianghu66.top/Article/details/gtsrutciwm.html

[S49] C++：写文件
来源：http://dali.zhoulong.xyz/Article/details/gtkpbghpiu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj20258.top/Article/details/gthdzxadvl.html

[S50] C++：格式化数字
来源：http://dali.zhengqikj.top/Article/details/gtgmurlxnc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gtwsplerqf.html

[S51] C++：显式类型转换
来源：http://dali.zhoulong.xyz/Article/details/gtsqlbymve.html

static_cast<double>(a) / b
来源：http://dali.haohaochexian.top/Article/details/gtilgaazgc.html

[S52] C++：const 与 noexcept
来源：http://dali.yueranfly.top/Article/details/gtmgvlbzac.html

int size() const noexcept { return n_; }
来源：http://dali.yangfankeji.com/Article/details/gtuxvudtzm.html

[S53] C++：移动语义
来源：http://dali.birdmap.top/Article/details/gtvehtbogk.html

std::vector<int> w = std::move(v);
来源：http://dali.cucudq.cn/Article/details/gtfjntqfzy.html

[S54] C++：异常处理
来源：http://dali.ppjwa.cn/Article/details/gtetcdecjq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tian-w.cn/Article/details/gtjcbqadjl.html

[S55] C++：结构化绑定
来源：http://dali.jqgufenzy.top/Article/details/gtsjayafxv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shzxlz.cn/Article/details/gtxnpqvtom.html

[S56] C++：optional
来源：http://dali.chenjidiqi.icu/Article/details/gtdmgjwvcw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmijztxz.html

[S57] C++：编译期常量
来源：http://dali.yvedp.cn/Article/details/gtvmpvwdzo.html

constexpr int N = 10;
来源：http://dali.shuidangran.top/Article/details/gtbftmsdwu.html

[S58] C++：命名空间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxepskkyf.html

namespace ns { int f() { return 1; } }
来源：http://dali.sxryk.cn/Article/details/gtmzhczeaf.html

[S59] C++：静态断言
来源：http://dali.jianghu66.top/Article/details/gtiwwhmmkl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ehwqpu.com/Article/details/gttdgagali.html

[S60] C++：遍历并删除元素
来源：http://dali.cdnleiting.top/Article/details/gtzavarirn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yuxming.cn/Article/details/gtskbkqapt.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gthicrzsnt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pycfn.com/Article/details/gteopdehfz.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtnvqqdaac.html

[T01] Kotlin：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtdnbnioxk.html

println("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gteuvyoyke.html

[T02] Kotlin：变量
来源：http://dali.hfpthk.cn/Article/details/gtpsnmlwpw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yj202588.top/Article/details/gtthldykqr.html

[T03] Kotlin：字符串模板
来源：http://dali.chenjidiqi.icu/Article/details/gtjinlxdwi.html

"值: $b"
来源：http://dali.kuanghao11.cn/Article/details/gtshnubxuh.html

[T04] Kotlin：空安全
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkfrweekm.html

val n: String? = null;  n?.length
来源：http://dali.cheryme.top/Article/details/gthkdbftne.html

[T05] Kotlin：when 表达式
来源：http://dali.haohaochexian.top/Article/details/gtvvpenirq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcudfrwgi.html

[T06] Kotlin：集合映射
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzbsewfub.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.fengsongda.top/Article/details/gtledgrawd.html

[T07] Kotlin：集合过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtouqojbpp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yangfankeji.com/Article/details/gtudqdhazy.html

[T08] Kotlin：数据类
来源：http://dali.havefunace.top/Article/details/gtwhajmuqv.html

data class User(val name: String, val age: Int)
来源：http://dali.gzhubu.top/Article/details/gtvmjaveas.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gtrzjajppq.html

fun String.exclaim() = this + "!"
来源：http://dali.hammf.cn/Article/details/gtsotojitq.html

[T10] Kotlin：默认参数
来源：http://dali.smart0.xyz/Article/details/gtytxcebld.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.wangshuangyany.cn/Article/details/gttssdnnkb.html

[T11] Kotlin：协程
来源：http://dali.smart0.xyz/Article/details/gtiyhwnbbb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yj20258888.top/Article/details/gtnqttzelo.html

[T12] Kotlin：解构声明
来源：http://dali.sweek.top/Article/details/gtmuzgkpay.html

val (a, b) = Pair(1, 2)
来源：http://dali.c1oappe.top/Article/details/gtgcfebbqj.html

[T13] Kotlin：只读 Map
来源：http://dali.sweek.top/Article/details/gtkwljzcnz.html

val m = mapOf("a" to 1)
来源：http://dali.xylfe.cn/Article/details/gthoqcolad.html

[T14] Kotlin：循环
来源：http://dali.hnxiangtu.top/Article/details/gtwuhoaqsf.html

for (i in 1..10) println(i)
来源：http://dali.yangfankeji.com/Article/details/gtizooeovc.html

[T15] Kotlin：接口
来源：http://dali.cqqwz.cn/Article/details/gtizzqgtsm.html

interface Shape { fun area(): Double }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqyojwgkc.html

[T16] Swift：Hello World
来源：http://dali.nwbrower.top/Article/details/gttsoenmcy.html

print("Hello")
来源：http://dali.havefunace.top/Article/details/gtluvozows.html

[T17] Swift：变量与常量
来源：http://dali.chenzaomai.com/Article/details/gtmbyenihn.html

var a = 1;  let b = 2
来源：http://dali.hysaishi.cn/Article/details/gtiigpujac.html

[T18] Swift：字符串插值
来源：http://dali.yongpay.top/Article/details/gtmyffqzbo.html

"值: \(b)"
来源：http://dali.jqgfzy.top/Article/details/gtagoiolds.html

[T19] Swift：可选绑定
来源：http://dali.yuanzhike.top/Article/details/gtvjwrvxqs.html

if let n = opt { print(n) }
来源：http://dali.zhiwuduotai.top/Article/details/gtkhmnejax.html

[T20] Swift：数组操作
来源：http://dali.yvedp.cn/Article/details/gtvsqlutvn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.daria6918.cn/Article/details/gturgrdbvv.html

[T21] Swift：遍历
来源：http://dali.jiagoushi.top/Article/details/gtnpiudkqm.html

for x in a { print(x) }
来源：http://dali.yongpay.top/Article/details/gtnyiehaqs.html

[T22] Swift：字典
来源：http://dali.gaohongyu789.top/Article/details/gtaevpjbgs.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jqgufenzy.top/Article/details/gtxvzmwdlu.html

[T23] Swift：函数
来源：http://dali.svipenyu.cn/Article/details/gtqthdlxqx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sufxvd.cn/Article/details/gtazdyykfm.html

[T24] Swift：闭包
来源：http://dali.vqdsnc.cn/Article/details/gtamzvzdxd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgqckrocg.html

[T25] Swift：结构体
来源：http://dali.jinqigfzy.top/Article/details/gtgdbahirt.html

struct P { var x: Int }
来源：http://dali.sufxvd.cn/Article/details/gtpeccespx.html

[T26] Swift：类与重写
来源：http://dali.zhengqikj.top/Article/details/gtnwrqtklx.html

class A: Base { override func f() {} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbufizezj.html

[T27] Swift：错误处理
来源：http://dali.aizwys.cn/Article/details/gtkatzfsxv.html

do { try f() } catch { print(error) }
来源：http://dali.yongpay.top/Article/details/gtctvidpin.html

[T28] Swift：枚举
来源：http://dali.ivvv.top/Article/details/gtmjiqwnnu.html

enum Color { case red, green }
来源：http://dali.gotoacloud.top/Article/details/gtoocvafud.html

[T29] Swift：guard 提前返回
来源：http://dali.ybcxt.top/Article/details/gtntktcwrj.html

guard let x = opt else { return }
来源：http://dali.xinyue.icu/Article/details/gtoycuueei.html

[T30] Swift：协议
来源：http://dali.shanyushiyangtech.top/Article/details/gttyasrnti.html

protocol Shape { func area() -> Double }
来源：http://dali.ybcxt.top/Article/details/gtzyxmxnus.html

[T31] Lua：Hello World
来源：http://dali.tian-w.cn/Article/details/gtigimbcfd.html

print("Hello")
来源：http://dali.yvedp.cn/Article/details/gtjvjaciuq.html

[T32] Lua：局部变量
来源：http://dali.redwolf501.top/Article/details/gtlltmlmtp.html

local a = 1
来源：http://dali.vqdsnc.cn/Article/details/gtrpxttcjg.html

[T33] Lua：表（数组）
来源：http://dali.ybcxt.top/Article/details/gtvbtrgnrf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cheryme.top/Article/details/gtxpdexeng.html

[T34] Lua：遍历表
来源：http://dali.guowangkeji.top/Article/details/gtixwknerh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ehwqpu.com/Article/details/gtkkprfuqn.html

[T35] Lua：字典表
来源：http://dali.dianchejie.cn/Article/details/gtnfwulxlx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gtbapdtnpb.html

[T36] Lua：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtztwxdget.html

function add(a, b) return a + b end
来源：http://dali.cheryme.top/Article/details/gtfgzdhgvf.html

[T37] Lua：字符串拼接
来源：http://dali.jqgfzy.top/Article/details/gtukulavzs.html

"a" .. "b"
来源：http://dali.sufxvd.cn/Article/details/gtxnjjuphf.html

[T38] Lua：条件
来源：http://dali.daria6918.cn/Article/details/gtmeyffwuk.html

if x > 0 then print("正") end
来源：http://dali.xuanzx.com/Article/details/gtvacmztzv.html

[T39] Lua：模式匹配
来源：http://dali.mhx1999.top/Article/details/gtuvbpxtra.html

string.find(s, "%d+")
来源：http://dali.zhengqikj.top/Article/details/gteddzvkzi.html

[T40] Lua：元表
来源：http://dali.jyoumei.cn/Article/details/gtwsdvobsq.html

setmetatable({}, { __index = base })
来源：http://dali.iojbl.cn/Article/details/gtesdufphn.html

[T41] Perl：Hello World
来源：http://dali.jianghu66.top/Article/details/gtemqqgukl.html

print "Hello\n";
来源：http://dali.zhoulong.xyz/Article/details/gtcgnerdzy.html

[T42] Perl：变量类型
来源：http://dali.tianlin.xyz/Article/details/gtrxmsuugw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.aibaodan.cn/Article/details/gtqxampcdi.html

[T43] Perl：字符串插值
来源：http://dali.xinyue.icu/Article/details/gtckpohbkx.html

"值: $a"
来源：http://dali.aibaodan.cn/Article/details/gtqqxiawua.html

[T44] Perl：条件
来源：http://dali.yuanzhike.top/Article/details/gtihwvjevc.html

if ($a > 0) { print "正"; }
来源：http://dali.cdnleiting.top/Article/details/gtudffsnfi.html

[T45] Perl：数组遍历
来源：http://dali.shuidangran.top/Article/details/gtacdapobw.html

for my $x (@arr) { print $x; }
来源：http://dali.ehwqpu.com/Article/details/gtclxmsorj.html

[T46] Perl：哈希操作
来源：http://dali.feifeiyinyue.top/Article/details/gtahjgqkvg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhengqikj.top/Article/details/gtpvmnclna.html

[T47] Perl：正则捕获
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdgwniklr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.sweek.top/Article/details/gtzayddnnh.html

[T48] Perl：正则替换
来源：http://dali.yuanzhike.top/Article/details/gtfforoswf.html

$s =~ s/old/new/g;
来源：http://dali.jinqigufen.top/Article/details/gtnczzhmts.html

[T49] Perl：函数
来源：http://dali.gotoacloud.top/Article/details/gtpwnmtobs.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gtgbcgfeuc.html

[T50] Perl：逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gtcjvmfysl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yuxming.cn/Article/details/gtfflmoizp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmgfcvjxm.html

[T51] Scala：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gteonnrdsz.html

println("Hello")
来源：http://dali.fengsongda.top/Article/details/gtozasmswz.html

[T52] Scala：变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtckkoroou.html

val a = 1;  var b = 2
来源：http://dali.tian-w.cn/Article/details/gtbqfpbdvb.html

[T53] Scala：字符串插值
来源：http://dali.ydzc1.top/Article/details/gttvehzaoq.html

s"值: $b"
来源：http://dali.dashuyun.cn/Article/details/gtxbsgnrlx.html

[T54] Scala：集合映射
来源：http://dali.redwolf501.top/Article/details/gtcqrewdfa.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gotoacloud.top/Article/details/gtwxeulayp.html

[T55] Scala：集合过滤
来源：http://dali.aibaodan.cn/Article/details/gtsaxikube.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yj20258.top/Article/details/gtyeqdjpga.html

[T56] Scala：样例类
来源：http://dali.xziqi.cn/Article/details/gtobfvdamv.html

case class User(name: String, age: Int)
来源：http://dali.bjfxy.top/Article/details/gtupnwlsdd.html

[T57] Scala：模式匹配
来源：http://dali.ydzc1.top/Article/details/gtvtujoygq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.vqdsnc.cn/Article/details/gtmtsjunbf.html

[T58] Scala：函数定义
来源：http://dali.zhongyouzk.top/Article/details/gtbqpfbqiw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.smart0.xyz/Article/details/gtywxnmknu.html

[T59] Scala：循环
来源：http://dali.daxiang520.top/Article/details/gtsyvmavck.html

for (i <- 1 to 10) println(i)
来源：http://dali.gotoacloud.top/Article/details/gtxexexgcy.html

[T60] Scala：折叠
来源：http://dali.haohaochexian.top/Article/details/gtksfzyxyn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cqqwz.cn/Article/details/gtqjbqwdur.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gthxashbau.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gtvwwmikkz.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtlarnjiav.html

[U01] Py：创建虚拟环境
来源：http://dali.smart0.xyz/Article/details/gtklswmqpf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.redwolf501.top/Article/details/gtnltkizwb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hfpthk.cn/Article/details/gtyxjgrtyz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ehwqpu.com/Article/details/gtyfzxesou.html

[U03] Py：加载 .env 配置
来源：http://dali.chenlongwang.top/Article/details/gtzuumergg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yj20258888.top/Article/details/gtkhytttql.html

[U04] Py：变量调试打印
来源：http://dali.tianlin.xyz/Article/details/gthoukqdda.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xziqi.cn/Article/details/gtccqtjigh.html

[U05] Py：列表去重且保序
来源：http://dali.aibaodan.cn/Article/details/gtduwujawm.html

list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gtgcpzeyef.html

[U06] Py：合并两个字典
来源：http://dali.hongshengwenyu.top/Article/details/gtnjmqmlfx.html

{**a, **b}
来源：http://dali.tianlin.xyz/Article/details/gtswxwrenf.html

[U07] Py：反转字典键值
来源：http://dali.0kj1m.cn/Article/details/gtitzyghkn.html

{v: k for k, v in d.items()}
来源：http://dali.fengsongda.top/Article/details/gtvpttwvkb.html

[U08] Py：展平二维列表
来源：http://dali.ydzc1.top/Article/details/gtfumgknej.html

[y for x in nested for y in x]
来源：http://dali.zhengqikj.top/Article/details/gtngadxvba.html

[U09] Py：字典取最大值的键
来源：http://dali.sweek.top/Article/details/gtikeokovr.html

max(d, key=d.get)
来源：http://dali.9152youxi.cn/Article/details/gtidxycwkd.html

[U10] Py：按值排序字典
来源：http://dali.jqgfzy.top/Article/details/gtbmsyddke.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.daria6918.cn/Article/details/gtfsimimlt.html

[U11] Py：生成器表达式
来源：http://dali.yuanzhike.top/Article/details/gtxunkypnp.html

(x * 2 for x in arr)
来源：http://dali.nwbrower.top/Article/details/gtrnfjbxso.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.0kj1m.cn/Article/details/gtzbddfoip.html

Counter(arr).most_common(3)
来源：http://dali.sufxvd.cn/Article/details/gtkkfxwywd.html

[U13] Py：固定长度队列
来源：http://dali.bjfxy.top/Article/details/gtaazubhsb.html

deque(maxlen=10)
来源：http://dali.zhoulong.xyz/Article/details/gtsifscoks.html

[U14] Py：分组收集到列表
来源：http://dali.hnqzz.top/Article/details/gtnhgmzibp.html

defaultdict(list)
来源：http://dali.pengpengdd.cyou/Article/details/gtwtngbsrm.html

[U15] Py：高精度计时
来源：http://dali.yanxiufei.cn/Article/details/gtxbjvcvqo.html

t = time.perf_counter()
来源：http://dali.ybcxt.top/Article/details/gtfxkrgtdb.html

[U16] Py：命令行参数解析
来源：http://dali.zycfv.cn/Article/details/gtvlounhuv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.316326.xyz/Article/details/gtupcwfbxn.html

[U17] Py：初始化日志
来源：http://dali.cdnleiting.top/Article/details/gtvrkemzbh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hywenlv.cn/Article/details/gtqxzwayan.html

[U18] Py：预编译正则
来源：http://dali.yueranfly.top/Article/details/gtwywrqnre.html

pat = re.compile(r"\d+")
来源：http://dali.zhiwuduotai.top/Article/details/gtkjlsfcbg.html

[U19] Py：正则替换带回调
来源：http://dali.nanxuanxn.top/Article/details/gtqiewwotb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ydzc1.top/Article/details/gttwdcoefu.html

[U20] Py：缓存函数结果
来源：http://dali.shanyushiyangtech.top/Article/details/gtakgtuqae.html

@functools.lru_cache(maxsize=None)
来源：http://dali.snrcjt.cn/Article/details/gturzarznw.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhengqikj.top/Article/details/gtdiswujdg.html

@contextlib.contextmanager
来源：http://dali.quarkkingdee.top/Article/details/gtfkajnlmr.html

[U22] Py：矩阵转置
来源：http://dali.ivvv.top/Article/details/gtrvgvuujo.html

list(zip(*m))
来源：http://dali.jyoumei.cn/Article/details/gtrsjfirqt.html

[U23] Py：分块读取大文件
来源：http://dali.zhoulong.xyz/Article/details/gtnuvjevcv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shuidangran.top/Article/details/gtcezpxkfs.html

[U24] Py：路径操作
来源：http://dali.daria6918.cn/Article/details/gtgoifcykq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cucudq.cn/Article/details/gtoxwmdtfp.html

[U25] Py：CSV 按字典读
来源：http://dali.pycfn.com/Article/details/gtvnhrgenl.html

csv.DictReader(f)
来源：http://dali.zhongyouzk.top/Article/details/gtuysvjzpk.html

[U26] Py：并发下载
来源：http://dali.zhengqikj.top/Article/details/gtjtcxutgl.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jiagoushi.top/Article/details/gtzkenwpjf.html

[U27] Py：异步 HTTP
来源：http://dali.dianchejie.cn/Article/details/gtyypukvjt.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.dashuyun.cn/Article/details/gtgxwuloux.html

[U28] Py：类型别名
来源：http://dali.wangdashe.top/Article/details/gtemqyiyhm.html

UserId = int
来源：http://dali.sufxvd.cn/Article/details/gtvetqgeto.html

[U29] Py：属性校验
来源：http://dali.jyoumei.cn/Article/details/gtelxscycm.html

@property 与 @x.setter 配合
来源：http://dali.shanyushiyangtech.top/Article/details/gtdlhwknik.html

[U30] Py：数据类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmosxrxa.html

@dataclass(slots=True)
来源：http://dali.hnqzz.top/Article/details/gthxijtcsd.html

[U31] Py：单测
来源：http://dali.jqgfzy.top/Article/details/gtitwbrthc.html

python -m pytest -q
来源：http://dali.zdqjudy.top/Article/details/gtxtipdnpk.html

[U32] Py：代码格式化
来源：http://dali.sysykeji.top/Article/details/gtoifvqwrz.html

ruff format . && ruff check --fix .
来源：http://dali.hongshengwenyu.top/Article/details/gthoqjcpie.html

[U33] Py：打包发布
来源：http://dali.zhoulong.xyz/Article/details/gtkbiudsem.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yuanzhike.top/Article/details/gtyswssqzc.html

[U34] Py：判断编码
来源：http://dali.zhaomingkeji.xyz/Article/details/gthgbgbobw.html

chardet.detect(raw)
来源：http://dali.guannengcc.top/Article/details/gtsnoolrqw.html

[U35] Py：发送邮件
来源：http://dali.hammf.cn/Article/details/gtdepqazbr.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.quarkkingdee.top/Article/details/gtgkkygdsz.html

[U36] Py：定时任务
来源：http://dali.chenzaomai.com/Article/details/gtvzldjkds.html

schedule.every(10).minutes.do(job)
来源：http://dali.wangshuangyany.cn/Article/details/gttubtpecj.html

[U37] Py：读写 Excel
来源：http://dali.yanxiufei.cn/Article/details/gtewaycvlx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hysaishi.cn/Article/details/gtwcvcahqu.html

[U38] Py：获取脚本所在目录
来源：http://dali.ehwqpu.com/Article/details/gtcsnczsro.html

Path(__file__).resolve().parent
来源：http://dali.ydzc1.top/Article/details/gtehdzbdnl.html


<!-- 参考信息 -->