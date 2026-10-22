代发 wailian999

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinqigfzy.top/Article/details/gt2kcfwnszc.html

[S13] C：宏定义
来源：http://dali.sufxvd.cn/Article/details/gt2ybvaqhww.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenjidiqi.icu/Article/details/gt2gaxxzliu.html

[S14] C：枚举
来源：http://dali.quarkkingdee.top/Article/details/gt2awfknntu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.havefunace.top/Article/details/gt2ppyknyul.html

[S15] C：类型转换
来源：http://dali.xinyue.icu/Article/details/gt2pcvthahq.html

(double) a / b
来源：http://dali.guowangkeji.top/Article/details/gt2gsepxqxe.html

[S16] C：位操作置位
来源：http://dali.zdqjudy.top/Article/details/gt2srlcrwdd.html

x |= (1 << 3);
来源：http://dali.mhx1999.top/Article/details/gt2nhsuxpse.html

[S17] C：安全拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2optyorsr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.iojbl.cn/Article/details/gt2idrjptqr.html

[S18] C：命令行参数
来源：http://dali.jyoumei.cn/Article/details/gt2zghdpvab.html

int main(int argc, char **argv)
来源：http://dali.yvedp.cn/Article/details/gt2bomubevf.html

[S19] C：快速排序
来源：http://dali.dianchejie.cn/Article/details/gt2ehsarndi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gt2eqxvbwaf.html

[S20] C：二分查找
来源：http://dali.xinyue.icu/Article/details/gt2qbmpomua.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jlsjyb.cn/Article/details/gt2norukgpt.html

[S21] C：字符类别判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lkcxgdah.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shuidangran.top/Article/details/gt2eavluchc.html

[S22] C：字符串转数字
来源：http://dali.xylfe.cn/Article/details/gt2qdwajvxu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.guowangkeji.top/Article/details/gt2ovehcgtn.html

[S23] C：随机数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ylqmbsvz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jqgfzy.top/Article/details/gt2kbhrxlpz.html

[S24] C：获取本地时间
来源：http://dali.sysykeji.top/Article/details/gt2ofypbjzh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.guannengcc.top/Article/details/gt2xfrjvtok.html

[S25] C：内存拷贝
来源：http://dali.cdnleiting.top/Article/details/gt2ombiuylh.html

memcpy(dst, src, n);
来源：http://dali.dashuyun.cn/Article/details/gt2kzlvktfo.html

[S26] C：内存清零
来源：http://dali.sufxvd.cn/Article/details/gt2nbmwymxn.html

memset(a, 0, sizeof a);
来源：http://dali.andypj.xyz/Article/details/gt2crtbocpo.html

[S27] C：定义常量
来源：http://dali.pengpengdd.cyou/Article/details/gt2ippjhbpt.html

const double PI = 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gt2lhfhiabj.html

[S28] C：静态变量
来源：http://dali.yongpay.top/Article/details/gt2wotgjpxs.html

static int counter = 0;
来源：http://dali.nanxuanxn.top/Article/details/gt2pefabwxl.html

[S29] C：变参函数
来源：http://dali.zycfv.cn/Article/details/gt2upbzdktg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jiagoushi.top/Article/details/gt2vuxdzbwx.html

[S30] C：头文件保护
来源：http://dali.shuidangran.top/Article/details/gt2gwncfokh.html

#ifndef X_H
来源：http://dali.zhengqikj.top/Article/details/gt2wvgmsnoj.html

#define X_H
来源：http://dali.hnxiangtu.top/Article/details/gt2xwfbyixs.html

#endif
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xkzwyjou.html

[S31] C++：Hello World
来源：http://dali.ehwqpu.com/Article/details/gt2yufmplxu.html

#include <iostream>
来源：http://dali.yuanzhike.top/Article/details/gt2yrxxhdip.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gzhubu.top/Article/details/gt2adqzubip.html

[S32] C++：字符串
来源：http://dali.cucudq.cn/Article/details/gt2jtnmxvee.html

std::string s = "hi";  s += "!";
来源：http://dali.andypj.xyz/Article/details/gt2vtjbwhvn.html

[S33] C++：vector 增删
来源：http://dali.kuanghao11.cn/Article/details/gt2edldowom.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lefitkks.html

[S34] C++：遍历 vector
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iolmtnis.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vlgylvhq.html

[S35] C++：map
来源：http://dali.0kj1m.cn/Article/details/gt2nzciowmf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuanzx.com/Article/details/gt2nlxqnxka.html

[S36] C++：unordered_map
来源：http://dali.yangfankeji.com/Article/details/gt2lhisdiop.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cucudq.cn/Article/details/gt2ckflstxq.html

[S37] C++：set
来源：http://dali.zhengqikj.top/Article/details/gt2jcidwart.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sufxvd.cn/Article/details/gt2vbuzbajb.html

[S38] C++：排序
来源：http://dali.cdnleiting.top/Article/details/gt2pyzudiod.html

std::sort(v.begin(), v.end());
来源：http://dali.jinqigufen.top/Article/details/gt2qbyhfpfq.html

[S39] C++：自定义比较器排序
来源：http://dali.0kj1m.cn/Article/details/gt2dgdwsekc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hnqzz.top/Article/details/gt2imcunmzd.html

[S40] C++：查找元素
来源：http://dali.vqdsnc.cn/Article/details/gt2zozpwaft.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.smart0.xyz/Article/details/gt2uybbcoxt.html

[S41] C++：类与构造函数
来源：http://dali.tanke756.top/Article/details/gt2aocjactq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cqqwz.cn/Article/details/gt2wlofbwev.html

[S42] C++：继承与虚函数
来源：http://dali.ybcxt.top/Article/details/gt2jnboyfrg.html

class B : public Base { public: void f() override {} };
来源：http://dali.gotoacloud.top/Article/details/gt2tazrngrd.html

[S43] C++：智能指针
来源：http://dali.vqdsnc.cn/Article/details/gt2juadkftn.html

auto p = std::make_unique<int>(5);
来源：http://dali.cheryme.top/Article/details/gt2fdqotczc.html

[S44] C++：引用传参
来源：http://dali.svipenyu.cn/Article/details/gt2iidcxkxk.html

void inc(int &x) { ++x; }
来源：http://dali.aizwys.cn/Article/details/gt2ezyluwqn.html

[S45] C++：lambda
来源：http://dali.nanxuanxn.top/Article/details/gt2dhprsucw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.daxiang520.top/Article/details/gt2cqoiumqf.html

[S46] C++：函数模板
来源：http://dali.yangfankeji.com/Article/details/gt2sqaznlfy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tianlin.xyz/Article/details/gt2jizlfdsf.html

[S47] C++：结构化绑定遍历
来源：http://dali.yvedp.cn/Article/details/gt2mjgmgrxc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cashguo.top/Article/details/gt2vnchvlrg.html

[S48] C++：逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gt2qksyidgd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.fengsongda.top/Article/details/gt2jiujzqcu.html

while (std::getline(in, line)) { }
来源：http://dali.daxiang520.top/Article/details/gt2bicpdfur.html

[S49] C++：写文件
来源：http://dali.zhengqikj.top/Article/details/gt2yaglyoff.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jqgufenzy.top/Article/details/gt2rljwsdsh.html

[S50] C++：格式化数字
来源：http://dali.tianlin.xyz/Article/details/gt2nxsrhamt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gt2mzcjkfva.html

[S51] C++：显式类型转换
来源：http://dali.hnqzz.top/Article/details/gt2hoesueth.html

static_cast<double>(a) / b
来源：http://dali.jqgfzy.top/Article/details/gt2emdwdtlb.html

[S52] C++：const 与 noexcept
来源：http://dali.dianchejie.cn/Article/details/gt2johokigx.html

int size() const noexcept { return n_; }
来源：http://dali.hywenlv.cn/Article/details/gt2mqbkohqh.html

[S53] C++：移动语义
来源：http://dali.tian-w.cn/Article/details/gt2xciptguj.html

std::vector<int> w = std::move(v);
来源：http://dali.iojbl.cn/Article/details/gt2chbcboit.html

[S54] C++：异常处理
来源：http://dali.zycfv.cn/Article/details/gt2lzfzdgch.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yueranfly.top/Article/details/gt2deudvgen.html

[S55] C++：结构化绑定
来源：http://dali.jlsjyb.cn/Article/details/gt2wyxnprvx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenjidiqi.icu/Article/details/gt2kmchzidl.html

[S56] C++：optional
来源：http://dali.xylfe.cn/Article/details/gt2wxuzpkzz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jqgufenzy.top/Article/details/gt2vniispcd.html

[S57] C++：编译期常量
来源：http://dali.jinqigufen.top/Article/details/gt2cedyazau.html

constexpr int N = 10;
来源：http://dali.0kj1m.cn/Article/details/gt2xyocdbjj.html

[S58] C++：命名空间
来源：http://dali.jlsjyb.cn/Article/details/gt2iuukmuzz.html

namespace ns { int f() { return 1; } }
来源：http://dali.xuanzx.com/Article/details/gt2fzowhpln.html

[S59] C++：静态断言
来源：http://dali.meibo888.top/Article/details/gt2kfecuemc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jianghu66.top/Article/details/gt2aqutctzl.html

[S60] C++：遍历并删除元素
来源：http://dali.havefunace.top/Article/details/gt2hkjanvty.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jyoumei.cn/Article/details/gt2jhiofhjh.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2grjklweg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yuxming.cn/Article/details/gt2cazkonys.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2ldjffzpw.html

[T01] Kotlin：Hello World
来源：http://dali.ivvv.top/Article/details/gt2qoifgggk.html

println("Hello")
来源：http://dali.tianlin.xyz/Article/details/gt2gzmpnuam.html

[T02] Kotlin：变量
来源：http://dali.redwolf501.top/Article/details/gt2ghesefjp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.birdmap.top/Article/details/gt2xyitnzwj.html

[T03] Kotlin：字符串模板
来源：http://dali.jiagoushi.top/Article/details/gt2ygpfmhxf.html

"值: $b"
来源：http://dali.hnqzz.top/Article/details/gt2ntnbwrhz.html

[T04] Kotlin：空安全
来源：http://dali.jqgufenzy.top/Article/details/gt2ecpaadme.html

val n: String? = null;  n?.length
来源：http://dali.hnqzz.top/Article/details/gt2zahnftoh.html

[T05] Kotlin：when 表达式
来源：http://dali.kuanghao11.cn/Article/details/gt2uyxufgsr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fpldgcdi.html

[T06] Kotlin：集合映射
来源：http://dali.gaohongyu789.top/Article/details/gt2ltnyhbyu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.meibo888.top/Article/details/gt2zpxjkeww.html

[T07] Kotlin：集合过滤
来源：http://dali.yj20258.top/Article/details/gt2ucmxuqda.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cucudq.cn/Article/details/gt2wjgfcbjx.html

[T08] Kotlin：数据类
来源：http://dali.sysykeji.top/Article/details/gt2rjkqhswd.html

data class User(val name: String, val age: Int)
来源：http://dali.andypj.xyz/Article/details/gt2jnzwdiyw.html

[T09] Kotlin：扩展函数
来源：http://dali.hysaishi.cn/Article/details/gt2cmhekbum.html

fun String.exclaim() = this + "!"
来源：http://dali.shzxlz.cn/Article/details/gt2qpanhbea.html

[T10] Kotlin：默认参数
来源：http://dali.hammf.cn/Article/details/gt2srwplvts.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gogol.net.cn/Article/details/gt2ivckunpe.html

[T11] Kotlin：协程
来源：http://dali.c1oappe.top/Article/details/gt2weihqnhv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.wangdashe.top/Article/details/gt2zgzpfjob.html

[T12] Kotlin：解构声明
来源：http://dali.yj20258888.top/Article/details/gt2pbfykqlw.html

val (a, b) = Pair(1, 2)
来源：http://dali.xziqi.cn/Article/details/gt2zqcnrqlc.html

[T13] Kotlin：只读 Map
来源：http://dali.haohaochexian.top/Article/details/gt2tveoydxn.html

val m = mapOf("a" to 1)
来源：http://dali.jqgfzy.top/Article/details/gt2kbjlmjjb.html

[T14] Kotlin：循环
来源：http://dali.cucudq.cn/Article/details/gt2yxzycypq.html

for (i in 1..10) println(i)
来源：http://dali.iojbl.cn/Article/details/gt2hxidjhjx.html

[T15] Kotlin：接口
来源：http://dali.yj202588.top/Article/details/gt2acyrsphg.html

interface Shape { fun area(): Double }
来源：http://dali.jinqigfzy.top/Article/details/gt2bbkfxviv.html

[T16] Swift：Hello World
来源：http://dali.tanke756.top/Article/details/gt2hhlvjqsa.html

print("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gt2liaybsmi.html

[T17] Swift：变量与常量
来源：http://dali.tianlin.xyz/Article/details/gt2ncovuabw.html

var a = 1;  let b = 2
来源：http://dali.yanxiufei.cn/Article/details/gt2aqvfbdqp.html

[T18] Swift：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gt2xtkvbeua.html

"值: \(b)"
来源：http://dali.shuidangran.top/Article/details/gt2npqhjtfo.html

[T19] Swift：可选绑定
来源：http://dali.ivvv.top/Article/details/gt2naeeeqmh.html

if let n = opt { print(n) }
来源：http://dali.cqqwz.cn/Article/details/gt2dwmzwkkf.html

[T20] Swift：数组操作
来源：http://dali.havefunace.top/Article/details/gt2jzavwdgo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yuanzhike.top/Article/details/gt2cunbdlwx.html

[T21] Swift：遍历
来源：http://dali.yuanzhike.top/Article/details/gt2bsaytjxe.html

for x in a { print(x) }
来源：http://dali.fengsongda.top/Article/details/gt2zheqtoyp.html

[T22] Swift：字典
来源：http://dali.shzxlz.cn/Article/details/gt2tarxpvci.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.tianlin.xyz/Article/details/gt2vvbuphkx.html

[T23] Swift：函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2bbgxvnay.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ohfvzlct.html

[T24] Swift：闭包
来源：http://dali.xinyue.icu/Article/details/gt2jsrzbmuv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.fengsongda.top/Article/details/gt2ckffnvmw.html

[T25] Swift：结构体
来源：http://dali.sweek.top/Article/details/gt2krkwqsps.html

struct P { var x: Int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zaobdbpu.html

[T26] Swift：类与重写
来源：http://dali.sweek.top/Article/details/gt2tvqlofgm.html

class A: Base { override func f() {} }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bowzkxrm.html

[T27] Swift：错误处理
来源：http://dali.jinqigufen.top/Article/details/gt2jutsmjzj.html

do { try f() } catch { print(error) }
来源：http://dali.nwbrower.top/Article/details/gt2duzsiufm.html

[T28] Swift：枚举
来源：http://dali.meibo888.top/Article/details/gt2sfjcspcr.html

enum Color { case red, green }
来源：http://dali.gotoacloud.top/Article/details/gt2jnbynfcy.html

[T29] Swift：guard 提前返回
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kwtjhcmb.html

guard let x = opt else { return }
来源：http://dali.yj20258.top/Article/details/gt2vwoqmxlk.html

[T30] Swift：协议
来源：http://dali.gaohongyu789.top/Article/details/gt2shvdffxe.html

protocol Shape { func area() -> Double }
来源：http://dali.sysykeji.top/Article/details/gt2svmullih.html

[T31] Lua：Hello World
来源：http://dali.smart0.xyz/Article/details/gt2rcyobwxy.html

print("Hello")
来源：http://dali.havefunace.top/Article/details/gt2qeiixujq.html

[T32] Lua：局部变量
来源：http://dali.yj20258888.top/Article/details/gt2zhsqxbmr.html

local a = 1
来源：http://dali.birdmap.top/Article/details/gt2drhbvhrq.html

[T33] Lua：表（数组）
来源：http://dali.zdqjudy.top/Article/details/gt2idcdpspq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sweek.top/Article/details/gt2fgoomxtk.html

[T34] Lua：遍历表
来源：http://dali.xylfe.cn/Article/details/gt2ghcekkyh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jyoumei.cn/Article/details/gt2heutbcdi.html

[T35] Lua：字典表
来源：http://dali.zycfv.cn/Article/details/gt2ewxrzbpv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.dianchejie.cn/Article/details/gt2ahdvegsc.html

[T36] Lua：函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2noakpoot.html

function add(a, b) return a + b end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eitfjfre.html

[T37] Lua：字符串拼接
来源：http://dali.guannengcc.top/Article/details/gt2muwpltya.html

"a" .. "b"
来源：http://dali.yanxiufei.cn/Article/details/gt2rqpisyvw.html

[T38] Lua：条件
来源：http://dali.mhx1999.top/Article/details/gt2pndfunoh.html

if x > 0 then print("正") end
来源：http://dali.jinqigfzy.top/Article/details/gt2ghmnnrma.html

[T39] Lua：模式匹配
来源：http://dali.daria6918.cn/Article/details/gt2heazbtff.html

string.find(s, "%d+")
来源：http://dali.xylfe.cn/Article/details/gt2rhieanhk.html

[T40] Lua：元表
来源：http://dali.haohaochexian.top/Article/details/gt2xhyewvts.html

setmetatable({}, { __index = base })
来源：http://dali.c1oappe.top/Article/details/gt2bbzaluuq.html

[T41] Perl：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gt2cdfnzdpp.html

print "Hello\n";
来源：http://dali.yongpay.top/Article/details/gt2wlqslqlm.html

[T42] Perl：变量类型
来源：http://dali.fengsongda.top/Article/details/gt2rblhsihv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sweek.top/Article/details/gt2uuheojmj.html

[T43] Perl：字符串插值
来源：http://dali.tanke756.top/Article/details/gt2zqnusbgm.html

"值: $a"
来源：http://dali.sysykeji.top/Article/details/gt2knnigmji.html

[T44] Perl：条件
来源：http://dali.shzxlz.cn/Article/details/gt2oqiixrdf.html

if ($a > 0) { print "正"; }
来源：http://dali.chenzaomai.com/Article/details/gt2yfqxmdmu.html

[T45] Perl：数组遍历
来源：http://dali.yongpay.top/Article/details/gt2yvvhzsjr.html

for my $x (@arr) { print $x; }
来源：http://dali.birdmap.top/Article/details/gt2mqnzythm.html

[T46] Perl：哈希操作
来源：http://dali.ppjwa.cn/Article/details/gt2fhpxrlwa.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.haohaochexian.top/Article/details/gt2fkewbsta.html

[T47] Perl：正则捕获
来源：http://dali.316326.xyz/Article/details/gt2nogzjuxr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yj20258.top/Article/details/gt2wukjqaxm.html

[T48] Perl：正则替换
来源：http://dali.yj20258888.top/Article/details/gt2puiklufp.html

$s =~ s/old/new/g;
来源：http://dali.hongshengwenyu.top/Article/details/gt2qslzhotb.html

[T49] Perl：函数
来源：http://dali.gaohongyu789.top/Article/details/gt2fwkmrewu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2tufwkgrw.html

[T50] Perl：逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mmlepdnd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xziqi.cn/Article/details/gt2slelebdt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jyoumei.cn/Article/details/gt2farwlpcq.html

[T51] Scala：Hello World
来源：http://dali.bjfxy.top/Article/details/gt2ytuzlvfu.html

println("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wmzbexsp.html

[T52] Scala：变量
来源：http://dali.gogol.net.cn/Article/details/gt2wzngtdfb.html

val a = 1;  var b = 2
来源：http://dali.gogol.net.cn/Article/details/gt2ifshwwma.html

[T53] Scala：字符串插值
来源：http://dali.svipenyu.cn/Article/details/gt2hjkrssgy.html

s"值: $b"
来源：http://dali.dianchejie.cn/Article/details/gt2inxgykwe.html

[T54] Scala：集合映射
来源：http://dali.jlsjyb.cn/Article/details/gt2whmjxqhi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gogol.net.cn/Article/details/gt2nusmfcyj.html

[T55] Scala：集合过滤
来源：http://dali.iojbl.cn/Article/details/gt2ajzfgumi.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yonumen.top/Article/details/gt2jvxwnjvn.html

[T56] Scala：样例类
来源：http://dali.jqgfzy.top/Article/details/gt2abccmree.html

case class User(name: String, age: Int)
来源：http://dali.cqqwz.cn/Article/details/gt2pdfdqiru.html

[T57] Scala：模式匹配
来源：http://dali.yonumen.top/Article/details/gt2cccaontc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bzxllzyu.html

[T58] Scala：函数定义
来源：http://dali.pengpengdd.cyou/Article/details/gt2pdzzysmx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.fengsongda.top/Article/details/gt2xlfiyqal.html

[T59] Scala：循环
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bonpycxc.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhengqikj.top/Article/details/gt2vatjlkbo.html

[T60] Scala：折叠
来源：http://dali.hfpthk.cn/Article/details/gt2nbrnvbvy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.guannengcc.top/Article/details/gt2hbmayggm.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2lpeweolx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.sufxvd.cn/Article/details/gt2rgxpfego.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2pubwkawu.html

[U01] Py：创建虚拟环境
来源：http://dali.wangshuangyany.cn/Article/details/gt2rmoykqun.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.aizwys.cn/Article/details/gt2rqbwdtoo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sysykeji.top/Article/details/gt2iaeozrps.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2ibrfirdq.html

[U03] Py：加载 .env 配置
来源：http://dali.haohaochexian.top/Article/details/gt2fmfoqjtt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.daxiang520.top/Article/details/gt2kstfmkeg.html

[U04] Py：变量调试打印
来源：http://dali.yongpay.top/Article/details/gt2kdgwtdlg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.bjfxy.top/Article/details/gt2micwwbmh.html

[U05] Py：列表去重且保序
来源：http://dali.bjfxy.top/Article/details/gt2ekohjkti.html

list(dict.fromkeys(arr))
来源：http://dali.cdnleiting.top/Article/details/gt2ewfbplwz.html

[U06] Py：合并两个字典
来源：http://dali.yanxiufei.cn/Article/details/gt2okkhkuxk.html

{**a, **b}
来源：http://dali.nanxuanxn.top/Article/details/gt2dtjbgqmo.html

[U07] Py：反转字典键值
来源：http://dali.cdnleiting.top/Article/details/gt2flogodsv.html

{v: k for k, v in d.items()}
来源：http://dali.yangfankeji.com/Article/details/gt2idxjhgur.html

[U08] Py：展平二维列表
来源：http://dali.fengsongda.top/Article/details/gt2yufajmyr.html

[y for x in nested for y in x]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ubvsbwnx.html

[U09] Py：字典取最大值的键
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yirluivj.html

max(d, key=d.get)
来源：http://dali.hnxiangtu.top/Article/details/gt2hejtqmqq.html

[U10] Py：按值排序字典
来源：http://dali.feifeiyinyue.top/Article/details/gt2ukzqtmqx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.chenjidiqi.icu/Article/details/gt2pdwcpfsp.html

[U11] Py：生成器表达式
来源：http://dali.quarkkingdee.top/Article/details/gt2hsalxaci.html

(x * 2 for x in arr)
来源：http://dali.yongpay.top/Article/details/gt2cbsivrsk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hnqzz.top/Article/details/gt2hnnnbqsl.html

Counter(arr).most_common(3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2iriapyeo.html

[U13] Py：固定长度队列
来源：http://dali.ivvv.top/Article/details/gt2mbpwblgy.html

deque(maxlen=10)
来源：http://dali.316326.xyz/Article/details/gt2iedabyvz.html

[U14] Py：分组收集到列表
来源：http://dali.sufxvd.cn/Article/details/gt2wulmpdjr.html

defaultdict(list)
来源：http://dali.meibo888.top/Article/details/gt2cgwjuxor.html

[U15] Py：高精度计时
来源：http://dali.zhongyouzk.top/Article/details/gt2zesudwmo.html

t = time.perf_counter()
来源：http://dali.iojbl.cn/Article/details/gt2mvemuszf.html

[U16] Py：命令行参数解析
来源：http://dali.hnxiangtu.top/Article/details/gt2oskqlzax.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.dashuyun.cn/Article/details/gt2qqytjrlm.html

[U17] Py：初始化日志
来源：http://dali.jianghu66.top/Article/details/gt2zxgriqrs.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2itogwfbx.html

[U18] Py：预编译正则
来源：http://dali.guannengcc.top/Article/details/gt2cjrapump.html

pat = re.compile(r"\d+")
来源：http://dali.iojbl.cn/Article/details/gt2rzcbmlar.html

[U19] Py：正则替换带回调
来源：http://dali.tianlin.xyz/Article/details/gt2bilggssg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.tianlin.xyz/Article/details/gt2kuskgepr.html

[U20] Py：缓存函数结果
来源：http://dali.kuanghao11.cn/Article/details/gt2gnmqttcz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvlllvpy.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinqigfzy.top/Article/details/gt2hvelgrpf.html

@contextlib.contextmanager
来源：http://dali.hongshengwenyu.top/Article/details/gt2ptucytqz.html

[U22] Py：矩阵转置
来源：http://dali.yonumen.top/Article/details/gt2cfzmjpnp.html

list(zip(*m))
来源：http://dali.xuanzx.com/Article/details/gt2aujpsgqa.html

[U23] Py：分块读取大文件
来源：http://dali.bjfxy.top/Article/details/gt2aulwfsje.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mzfhddtu.html

[U24] Py：路径操作
来源：http://dali.sysykeji.top/Article/details/gt2oahmgwty.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.bjfxy.top/Article/details/gt2lzysjltf.html

[U25] Py：CSV 按字典读
来源：http://dali.0kj1m.cn/Article/details/gt2rzbittda.html

csv.DictReader(f)
来源：http://dali.hfpthk.cn/Article/details/gt2hmxdaqvi.html

[U26] Py：并发下载
来源：http://dali.yuxming.cn/Article/details/gt2tkzslxgk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.feifeiyinyue.top/Article/details/gt2omxnrtbb.html

[U27] Py：异步 HTTP
来源：http://dali.shuidangran.top/Article/details/gt2ajjzhrzo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jinqigufen.top/Article/details/gt2tuaplmer.html

[U28] Py：类型别名
来源：http://dali.xuetiantiany.cn/Article/details/gt2cqvukoen.html

UserId = int
来源：http://dali.iojbl.cn/Article/details/gt2usnkvzbu.html

[U29] Py：属性校验
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vksptqjh.html

@property 与 @x.setter 配合
来源：http://dali.jianghu66.top/Article/details/gt2yjdrobno.html

[U30] Py：数据类
来源：http://dali.chenjidiqi.icu/Article/details/gt2ibdutkze.html

@dataclass(slots=True)
来源：http://dali.hysaishi.cn/Article/details/gt2wekxekix.html

[U31] Py：单测
来源：http://dali.dashuyun.cn/Article/details/gt2bockjbfr.html

python -m pytest -q
来源：http://dali.chenjidiqi.icu/Article/details/gt2apgbwfic.html

[U32] Py：代码格式化
来源：http://dali.xylfe.cn/Article/details/gt2zdfbggyf.html

ruff format . && ruff check --fix .
来源：http://dali.yuxming.cn/Article/details/gt2kisvlxcu.html

[U33] Py：打包发布
来源：http://dali.jianghu66.top/Article/details/gt2gjfjtfpb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.wangdashe.top/Article/details/gt2fmqzdrwh.html

[U34] Py：判断编码
来源：http://dali.svipenyu.cn/Article/details/gt2drqjffis.html

chardet.detect(raw)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ntbiwwsz.html

[U35] Py：发送邮件
来源：http://dali.hongshengwenyu.top/Article/details/gt2icyfpkts.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.ppjwa.cn/Article/details/gt2xetmojgu.html

[U36] Py：定时任务
来源：http://dali.smart0.xyz/Article/details/gt2czoubnvv.html

schedule.every(10).minutes.do(job)
来源：http://dali.hysaishi.cn/Article/details/gt2rpzyqoke.html


<!-- 参考信息 -->