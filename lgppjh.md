代发 wailian999

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jlsjyb.cn/Article/details/gtoldqvwxc.html

[S13] C：宏定义
来源：http://dali.hammf.cn/Article/details/gtkqzknydw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.redwolf501.top/Article/details/gtqzibiwnk.html

[S14] C：枚举
来源：http://dali.zhixingplan.top/Article/details/gttybzvvyk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sufxvd.cn/Article/details/gtobmgmxbf.html

[S15] C：类型转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwaqjves.html

(double) a / b
来源：http://dali.yangfankeji.com/Article/details/gtkslndsmd.html

[S16] C：位操作置位
来源：http://dali.andypj.xyz/Article/details/gtvmkhcdjr.html

x |= (1 << 3);
来源：http://dali.jiagoushi.top/Article/details/gtudunstzu.html

[S17] C：安全拼接字符串
来源：http://dali.316326.xyz/Article/details/gtvusnpoaz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpjzejqqt.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gtbxowgpar.html

int main(int argc, char **argv)
来源：http://dali.havefunace.top/Article/details/gtujxbpacn.html

[S19] C：快速排序
来源：http://dali.pengpengdd.cyou/Article/details/gtvovgsgkd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxpcdtqot.html

[S20] C：二分查找
来源：http://dali.chenjidiqi.icu/Article/details/gtysytbvtk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jqgfzy.top/Article/details/gtbmgzpcbi.html

[S21] C：字符类别判断
来源：http://dali.zhoulong.xyz/Article/details/gtanxjilgx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nanxuanxn.top/Article/details/gtdlginyvv.html

[S22] C：字符串转数字
来源：http://dali.hammf.cn/Article/details/gtyfhioxwh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hongshengwenyu.top/Article/details/gthnabzjky.html

[S23] C：随机数
来源：http://dali.nwbrower.top/Article/details/gticxexdbp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.vqdsnc.cn/Article/details/gtmfkumyet.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gtgbwnguui.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.fengsongda.top/Article/details/gtuwhtaplv.html

[S25] C：内存拷贝
来源：http://dali.wangshuangyany.cn/Article/details/gtbtiiwtba.html

memcpy(dst, src, n);
来源：http://dali.haohaochexian.top/Article/details/gtsbrczhiz.html

[S26] C：内存清零
来源：http://dali.hnqzz.top/Article/details/gtxmrrzqgu.html

memset(a, 0, sizeof a);
来源：http://dali.wangshuangyany.cn/Article/details/gtwwjxfxzc.html

[S27] C：定义常量
来源：http://dali.birdmap.top/Article/details/gtgtxoxkwb.html

const double PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtzdvuyoas.html

[S28] C：静态变量
来源：http://dali.gzhubu.top/Article/details/gtszvucdne.html

static int counter = 0;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnpmcuaer.html

[S29] C：变参函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzdfdjafv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jiagoushi.top/Article/details/gtwzdibbts.html

[S30] C：头文件保护
来源：http://dali.c1oappe.top/Article/details/gtssgorpdf.html

#ifndef X_H
来源：http://dali.tanke756.top/Article/details/gtjixmmwqi.html

#define X_H
来源：http://dali.zhixingplan.top/Article/details/gtiwuyddil.html

#endif
来源：http://dali.gogol.net.cn/Article/details/gthbrekfme.html

[S31] C++：Hello World
来源：http://dali.yongpay.top/Article/details/gtokrnwqmp.html

#include <iostream>
来源：http://dali.nanxuanxn.top/Article/details/gtucmedfob.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.daria6918.cn/Article/details/gtmjgkpwcj.html

[S32] C++：字符串
来源：http://dali.xylfe.cn/Article/details/gtzowlmiev.html

std::string s = "hi";  s += "!";
来源：http://dali.yj202588.top/Article/details/gtsaikcxgg.html

[S33] C++：vector 增删
来源：http://dali.redwolf501.top/Article/details/gtbcmwmghp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtlypuscwj.html

[S34] C++：遍历 vector
来源：http://dali.hnxiangtu.top/Article/details/gtsoiouvnk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.daxiang520.top/Article/details/gtndievwxw.html

[S35] C++：map
来源：http://dali.gzhubu.top/Article/details/gtihnxqaln.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtnuahxmmr.html

[S36] C++：unordered_map
来源：http://dali.sufxvd.cn/Article/details/gtemzfbxlt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shuidangran.top/Article/details/gtsvhqqxzv.html

[S37] C++：set
来源：http://dali.ivvv.top/Article/details/gtiqyxenuu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhixingplan.top/Article/details/gttcxlepgw.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gtgvvenqxf.html

std::sort(v.begin(), v.end());
来源：http://dali.ydzc1.top/Article/details/gtbzlayjnf.html

[S39] C++：自定义比较器排序
来源：http://dali.guannengcc.top/Article/details/gtrahkzfdi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbekdaxnq.html

[S40] C++：查找元素
来源：http://dali.ydzc1.top/Article/details/gtubcllkaz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.kuanghao11.cn/Article/details/gtxwqvoyyl.html

[S41] C++：类与构造函数
来源：http://dali.sysykeji.top/Article/details/gtxtlqjvgm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinqigfzy.top/Article/details/gtkfhszhaj.html

[S42] C++：继承与虚函数
来源：http://dali.cucudq.cn/Article/details/gttreytmfw.html

class B : public Base { public: void f() override {} };
来源：http://dali.hammf.cn/Article/details/gttdoukyvo.html

[S43] C++：智能指针
来源：http://dali.yj20258888.top/Article/details/gtaqidltiu.html

auto p = std::make_unique<int>(5);
来源：http://dali.hongshengwenyu.top/Article/details/gtsnejggcs.html

[S44] C++：引用传参
来源：http://dali.yj20258888.top/Article/details/gthrzetqto.html

void inc(int &x) { ++x; }
来源：http://dali.shzxlz.cn/Article/details/gtmptrwbys.html

[S45] C++：lambda
来源：http://dali.tian-w.cn/Article/details/gthoaylnoh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.feifeiyinyue.top/Article/details/gttvfgshjc.html

[S46] C++：函数模板
来源：http://dali.gotoacloud.top/Article/details/gtxeqbemae.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jqgfzy.top/Article/details/gtsuhexbbh.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinqigfzy.top/Article/details/gtycyrhdhh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zdqjudy.top/Article/details/gtloqrbbnf.html

[S48] C++：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtpstuprsm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.9152youxi.cn/Article/details/gtrsdiovfp.html

while (std::getline(in, line)) { }
来源：http://dali.yuxming.cn/Article/details/gtyvbfvnfx.html

[S49] C++：写文件
来源：http://dali.gaohongyu789.top/Article/details/gtwdgnazrl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gogol.net.cn/Article/details/gtbcrkrjzv.html

[S50] C++：格式化数字
来源：http://dali.jlsjyb.cn/Article/details/gtgmpiwrzb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zycfv.cn/Article/details/gtbneazwtq.html

[S51] C++：显式类型转换
来源：http://dali.sufxvd.cn/Article/details/gtnlihauvu.html

static_cast<double>(a) / b
来源：http://dali.iojbl.cn/Article/details/gtpepvkdox.html

[S52] C++：const 与 noexcept
来源：http://dali.guannengcc.top/Article/details/gtlxbnvaig.html

int size() const noexcept { return n_; }
来源：http://dali.jinqigfzy.top/Article/details/gtmmdovrgu.html

[S53] C++：移动语义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlzywpjpl.html

std::vector<int> w = std::move(v);
来源：http://dali.gaohongyu789.top/Article/details/gtuoksqnsv.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gteuvtgpha.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.redwolf501.top/Article/details/gtzxayvjzq.html

[S55] C++：结构化绑定
来源：http://dali.yongpay.top/Article/details/gtxprgtcmx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.andypj.xyz/Article/details/gtmgwfzait.html

[S56] C++：optional
来源：http://dali.redwolf501.top/Article/details/gtgdivuizm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ydzc1.top/Article/details/gtfneeehnx.html

[S57] C++：编译期常量
来源：http://dali.chenzaomai.com/Article/details/gtryarmfkf.html

constexpr int N = 10;
来源：http://dali.hnxiangtu.top/Article/details/gtixugjkyh.html

[S58] C++：命名空间
来源：http://dali.havefunace.top/Article/details/gtheapleqb.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpyulxvtb.html

[S59] C++：静态断言
来源：http://dali.redwolf501.top/Article/details/gtndebhuuo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhixingplan.top/Article/details/gtlcsdbtcs.html

[S60] C++：遍历并删除元素
来源：http://dali.xziqi.cn/Article/details/gtefjxbmmj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xinyue.icu/Article/details/gtpfbvexgv.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtsgkxmikm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.quarkkingdee.top/Article/details/gttdnnywpw.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtpkeotwqg.html

[T01] Kotlin：Hello World
来源：http://dali.xziqi.cn/Article/details/gtrrxamduc.html

println("Hello")
来源：http://dali.gogol.net.cn/Article/details/gthiyyusnw.html

[T02] Kotlin：变量
来源：http://dali.yongpay.top/Article/details/gtqrnwzwea.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sysykeji.top/Article/details/gtnbxtjpob.html

[T03] Kotlin：字符串模板
来源：http://dali.yuxming.cn/Article/details/gtclqbsrjf.html

"值: $b"
来源：http://dali.cashguo.top/Article/details/gtypgshekd.html

[T04] Kotlin：空安全
来源：http://dali.aibaodan.cn/Article/details/gtjyntgrbf.html

val n: String? = null;  n?.length
来源：http://dali.kuanghao11.cn/Article/details/gtgvsemhrt.html

[T05] Kotlin：when 表达式
来源：http://dali.aizwys.cn/Article/details/gthunhitat.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.fengsongda.top/Article/details/gtjclxzrtn.html

[T06] Kotlin：集合映射
来源：http://dali.yueranfly.top/Article/details/gtcveegxqe.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sweek.top/Article/details/gtfjpxsuez.html

[T07] Kotlin：集合过滤
来源：http://dali.yongpay.top/Article/details/gtndqbkawa.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hnqzz.top/Article/details/gtvjohvdop.html

[T08] Kotlin：数据类
来源：http://dali.wangshuangyany.cn/Article/details/gtdxektybo.html

data class User(val name: String, val age: Int)
来源：http://dali.chenjidiqi.icu/Article/details/gtlkiqsfdv.html

[T09] Kotlin：扩展函数
来源：http://dali.ppjwa.cn/Article/details/gtifmiqgtx.html

fun String.exclaim() = this + "!"
来源：http://dali.fengsongda.top/Article/details/gtseczxaaw.html

[T10] Kotlin：默认参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrtwolpcb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.nanxuanxn.top/Article/details/gtqdxtxzdm.html

[T11] Kotlin：协程
来源：http://dali.ppjwa.cn/Article/details/gtvpmrolak.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shzxlz.cn/Article/details/gtcedhvkvq.html

[T12] Kotlin：解构声明
来源：http://dali.bjfxy.top/Article/details/gtpzajqlxo.html

val (a, b) = Pair(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gtmwedggsr.html

[T13] Kotlin：只读 Map
来源：http://dali.birdmap.top/Article/details/gtkjjeziur.html

val m = mapOf("a" to 1)
来源：http://dali.tian-w.cn/Article/details/gtaqgitupf.html

[T14] Kotlin：循环
来源：http://dali.jqgfzy.top/Article/details/gtlmckzmet.html

for (i in 1..10) println(i)
来源：http://dali.ydzc1.top/Article/details/gtcjnmjmbd.html

[T15] Kotlin：接口
来源：http://dali.wangdashe.top/Article/details/gtilagkqak.html

interface Shape { fun area(): Double }
来源：http://dali.dashuyun.cn/Article/details/gtcxvbiews.html

[T16] Swift：Hello World
来源：http://dali.yonumen.top/Article/details/gtbugewwuw.html

print("Hello")
来源：http://dali.0kj1m.cn/Article/details/gtilrrifae.html

[T17] Swift：变量与常量
来源：http://dali.cheryme.top/Article/details/gtcighvtby.html

var a = 1;  let b = 2
来源：http://dali.guannengcc.top/Article/details/gtivoybxfh.html

[T18] Swift：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gtinzyfogz.html

"值: \(b)"
来源：http://dali.sufxvd.cn/Article/details/gtviywrqol.html

[T19] Swift：可选绑定
来源：http://dali.havefunace.top/Article/details/gttrfwfwpo.html

if let n = opt { print(n) }
来源：http://dali.c1oappe.top/Article/details/gtapmcaimu.html

[T20] Swift：数组操作
来源：http://dali.shangyingyoupin.top/Article/details/gtjtnbapbl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.mhx1999.top/Article/details/gtggjxiudc.html

[T21] Swift：遍历
来源：http://dali.dianchejie.cn/Article/details/gttblertvy.html

for x in a { print(x) }
来源：http://dali.kuanghao11.cn/Article/details/gtbiekqqop.html

[T22] Swift：字典
来源：http://dali.yj20258.top/Article/details/gtxksheoub.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xuetiantiany.cn/Article/details/gtmmnfzqud.html

[T23] Swift：函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmjflmgdr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jlsjyb.cn/Article/details/gtvdaoxaou.html

[T24] Swift：闭包
来源：http://dali.quarkkingdee.top/Article/details/gtjuegyutx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtuhezqfdk.html

[T25] Swift：结构体
来源：http://dali.hywenlv.cn/Article/details/gtepfyspcz.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gtrgiqxyha.html

[T26] Swift：类与重写
来源：http://dali.jqgufenzy.top/Article/details/gtwiarwwgh.html

class A: Base { override func f() {} }
来源：http://dali.ybcxt.top/Article/details/gtueucuyvo.html

[T27] Swift：错误处理
来源：http://dali.jlsjyb.cn/Article/details/gtelukcqlf.html

do { try f() } catch { print(error) }
来源：http://dali.xuanzx.com/Article/details/gtpocjlezy.html

[T28] Swift：枚举
来源：http://dali.daria6918.cn/Article/details/gtdkwphuqz.html

enum Color { case red, green }
来源：http://dali.0kj1m.cn/Article/details/gtatgrdhgn.html

[T29] Swift：guard 提前返回
来源：http://dali.haohaochexian.top/Article/details/gtlwztwonp.html

guard let x = opt else { return }
来源：http://dali.yanxiufei.cn/Article/details/gtybtlptdu.html

[T30] Swift：协议
来源：http://dali.cqqwz.cn/Article/details/gttzrnnlnr.html

protocol Shape { func area() -> Double }
来源：http://dali.smart0.xyz/Article/details/gtuajtxmcw.html

[T31] Lua：Hello World
来源：http://dali.yj202588.top/Article/details/gthzchzndj.html

print("Hello")
来源：http://dali.tianlin.xyz/Article/details/gtjjtsnihr.html

[T32] Lua：局部变量
来源：http://dali.yvedp.cn/Article/details/gtqhlxtlhj.html

local a = 1
来源：http://dali.shangyingyoupin.top/Article/details/gtubvtunmn.html

[T33] Lua：表（数组）
来源：http://dali.svipenyu.cn/Article/details/gtaalhlcui.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.meibo888.top/Article/details/gthvwmatwy.html

[T34] Lua：遍历表
来源：http://dali.guowangkeji.top/Article/details/gtrmgfogig.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.quarkkingdee.top/Article/details/gtlkdagkyc.html

[T35] Lua：字典表
来源：http://dali.yonumen.top/Article/details/gtbikqwlxm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ivvv.top/Article/details/gtxaenhdtx.html

[T36] Lua：函数
来源：http://dali.dashuyun.cn/Article/details/gtyhoqevbc.html

function add(a, b) return a + b end
来源：http://dali.jinqigfzy.top/Article/details/gtohgtdgop.html

[T37] Lua：字符串拼接
来源：http://dali.gzhubu.top/Article/details/gtblldvxpl.html

"a" .. "b"
来源：http://dali.ybcxt.top/Article/details/gtgvtumkxz.html

[T38] Lua：条件
来源：http://dali.zhengqikj.top/Article/details/gtpfnwmopo.html

if x > 0 then print("正") end
来源：http://dali.zhongyouzk.top/Article/details/gtcjraxddn.html

[T39] Lua：模式匹配
来源：http://dali.xinyue.icu/Article/details/gtiweclvkt.html

string.find(s, "%d+")
来源：http://dali.xuetiantiany.cn/Article/details/gthbscrxwr.html

[T40] Lua：元表
来源：http://dali.daria6918.cn/Article/details/gtezdtrscu.html

setmetatable({}, { __index = base })
来源：http://dali.gogol.net.cn/Article/details/gtoatcupzd.html

[T41] Perl：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtvzstdrbg.html

print "Hello\n";
来源：http://dali.shangyingyoupin.top/Article/details/gtgbznmpat.html

[T42] Perl：变量类型
来源：http://dali.zhoulong.xyz/Article/details/gtjpytzjru.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xylfe.cn/Article/details/gtnfhbnyhf.html

[T43] Perl：字符串插值
来源：http://dali.gogol.net.cn/Article/details/gtplakvvzh.html

"值: $a"
来源：http://dali.xinyue.icu/Article/details/gtrcxwpwxn.html

[T44] Perl：条件
来源：http://dali.jianghu66.top/Article/details/gtelfsafvg.html

if ($a > 0) { print "正"; }
来源：http://dali.zhengqikj.top/Article/details/gtbhkgyngt.html

[T45] Perl：数组遍历
来源：http://dali.daxiang520.top/Article/details/gtiyalkibx.html

for my $x (@arr) { print $x; }
来源：http://dali.pycfn.com/Article/details/gtasbeejgn.html

[T46] Perl：哈希操作
来源：http://dali.aizwys.cn/Article/details/gtoysegqlr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yj20258.top/Article/details/gtnrruuivy.html

[T47] Perl：正则捕获
来源：http://dali.jinqigfzy.top/Article/details/gtwyzohgtz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.dashuyun.cn/Article/details/gtwbxbmfqw.html

[T48] Perl：正则替换
来源：http://dali.gotoacloud.top/Article/details/gtunrahdgp.html

$s =~ s/old/new/g;
来源：http://dali.yj20258.top/Article/details/gtmungnyhu.html

[T49] Perl：函数
来源：http://dali.ydzc1.top/Article/details/gtwpnspzzi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.havefunace.top/Article/details/gtiglgchqa.html

[T50] Perl：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtyupqccpt.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cqqwz.cn/Article/details/gtjrziajop.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ppjwa.cn/Article/details/gtjjnhjdew.html

[T51] Scala：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtzogeyebu.html

println("Hello")
来源：http://dali.jinqigufen.top/Article/details/gttqpufoqj.html

[T52] Scala：变量
来源：http://dali.xziqi.cn/Article/details/gtxewdmqul.html

val a = 1;  var b = 2
来源：http://dali.yuanzhike.top/Article/details/gtugmbsvmi.html

[T53] Scala：字符串插值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjksmtegx.html

s"值: $b"
来源：http://dali.jlsjyb.cn/Article/details/gtiobkpgbr.html

[T54] Scala：集合映射
来源：http://dali.shangyingyoupin.top/Article/details/gtwsjlkcjh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.svipenyu.cn/Article/details/gtgqwnthln.html

[T55] Scala：集合过滤
来源：http://dali.smart0.xyz/Article/details/gtfqwvorwq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.wangdashe.top/Article/details/gtwyrimdmy.html

[T56] Scala：样例类
来源：http://dali.shangyingyoupin.top/Article/details/gtylopcnpk.html

case class User(name: String, age: Int)
来源：http://dali.cheryme.top/Article/details/gtmcxymozj.html

[T57] Scala：模式匹配
来源：http://dali.9152youxi.cn/Article/details/gtbtybdtcn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.quarkkingdee.top/Article/details/gtsdlbvtdc.html

[T58] Scala：函数定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtplwitwmz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.pycfn.com/Article/details/gtommzncxs.html

[T59] Scala：循环
来源：http://dali.fzhhl.top/Article/details/gtxtskqina.html

for (i <- 1 to 10) println(i)
来源：http://dali.gogol.net.cn/Article/details/gtcxtrfbrf.html

[T60] Scala：折叠
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfiombxec.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xuetiantiany.cn/Article/details/gtzpapyufx.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtthleovpr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jlsjyb.cn/Article/details/gtxuqutmfr.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtdwoguakh.html

[U01] Py：创建虚拟环境
来源：http://dali.cdnleiting.top/Article/details/gtlkduboxh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhongyouzk.top/Article/details/gtdbjrtbsb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jlsjyb.cn/Article/details/gtqrovyjrt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhoulong.xyz/Article/details/gtpczwfkxp.html

[U03] Py：加载 .env 配置
来源：http://dali.wangdashe.top/Article/details/gtvlhhzlug.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.birdmap.top/Article/details/gtekiqrrat.html

[U04] Py：变量调试打印
来源：http://dali.zhengqikj.top/Article/details/gtcmkcudco.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.guowangkeji.top/Article/details/gtbkudcbsd.html

[U05] Py：列表去重且保序
来源：http://dali.xuetiantiany.cn/Article/details/gtbxjyouow.html

list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtegabbkdm.html

[U06] Py：合并两个字典
来源：http://dali.yonumen.top/Article/details/gtkkowlyom.html

{**a, **b}
来源：http://dali.jqgufenzy.top/Article/details/gthxbbjghg.html

[U07] Py：反转字典键值
来源：http://dali.fengsongda.top/Article/details/gtercksuua.html

{v: k for k, v in d.items()}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmfchfpwc.html

[U08] Py：展平二维列表
来源：http://dali.yj20258.top/Article/details/gtaxkaiugz.html

[y for x in nested for y in x]
来源：http://dali.birdmap.top/Article/details/gtqbtyxzfs.html

[U09] Py：字典取最大值的键
来源：http://dali.jqgfzy.top/Article/details/gtcprbrkwm.html

max(d, key=d.get)
来源：http://dali.tianlin.xyz/Article/details/gtcduyojgo.html

[U10] Py：按值排序字典
来源：http://dali.zhengqikj.top/Article/details/gtqsggwfdt.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cdnleiting.top/Article/details/gtegwersup.html

[U11] Py：生成器表达式
来源：http://dali.sxryk.cn/Article/details/gtqyuncgjk.html

(x * 2 for x in arr)
来源：http://dali.ivvv.top/Article/details/gtdjoibneu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sweek.top/Article/details/gtapzwnktp.html

Counter(arr).most_common(3)
来源：http://dali.jqgufenzy.top/Article/details/gtvpxoutco.html

[U13] Py：固定长度队列
来源：http://dali.aizwys.cn/Article/details/gtxuhqgwau.html

deque(maxlen=10)
来源：http://dali.yueranfly.top/Article/details/gtlxudulhq.html

[U14] Py：分组收集到列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmyudzwbu.html

defaultdict(list)
来源：http://dali.xinyue.icu/Article/details/gtuvvoupsv.html

[U15] Py：高精度计时
来源：http://dali.cqqwz.cn/Article/details/gtywkilshk.html

t = time.perf_counter()
来源：http://dali.gogol.net.cn/Article/details/gteglkhiau.html

[U16] Py：命令行参数解析
来源：http://dali.snrcjt.cn/Article/details/gtrsxzihgu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.birdmap.top/Article/details/gtuaberjxl.html

[U17] Py：初始化日志
来源：http://dali.tian-w.cn/Article/details/gtaikoafux.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.9152youxi.cn/Article/details/gtwwvkkazx.html

[U18] Py：预编译正则
来源：http://dali.ehwqpu.com/Article/details/gtrklcdnqy.html

pat = re.compile(r"\d+")
来源：http://dali.zhixingplan.top/Article/details/gtixoucoew.html

[U19] Py：正则替换带回调
来源：http://dali.ppjwa.cn/Article/details/gtsjiqbtki.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.quarkkingdee.top/Article/details/gtenjuuntd.html

[U20] Py：缓存函数结果
来源：http://dali.gzhubu.top/Article/details/gtmmrksggg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.aizwys.cn/Article/details/gtalpfolvb.html

[U21] Py：自定义上下文管理器
来源：http://dali.jqgufenzy.top/Article/details/gtydqmywkw.html

@contextlib.contextmanager
来源：http://dali.shanyushiyangtech.top/Article/details/gtrnsgvpsj.html

[U22] Py：矩阵转置
来源：http://dali.daria6918.cn/Article/details/gtogozzatf.html

list(zip(*m))
来源：http://dali.jiagoushi.top/Article/details/gtjdzptlnc.html

[U23] Py：分块读取大文件
来源：http://dali.zdqjudy.top/Article/details/gtvimehkzo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhixingplan.top/Article/details/gtdjtuuimj.html

[U24] Py：路径操作
来源：http://dali.xylfe.cn/Article/details/gtbalmdxgt.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtkegpgaaz.html

[U25] Py：CSV 按字典读
来源：http://dali.ybcxt.top/Article/details/gtwsgxhhrr.html

csv.DictReader(f)
来源：http://dali.cheryme.top/Article/details/gtmesqqglw.html

[U26] Py：并发下载
来源：http://dali.dianchejie.cn/Article/details/gtwbdxnzjb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jiagoushi.top/Article/details/gtmqspdxrc.html

[U27] Py：异步 HTTP
来源：http://dali.vqdsnc.cn/Article/details/gtbswansaz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shuidangran.top/Article/details/gtzbnerjuc.html

[U28] Py：类型别名
来源：http://dali.cdnleiting.top/Article/details/gtokqfprks.html

UserId = int
来源：http://dali.cheryme.top/Article/details/gtymrggdtj.html

[U29] Py：属性校验
来源：http://dali.pengpengdd.cyou/Article/details/gtawoauiwi.html

@property 与 @x.setter 配合
来源：http://dali.jinqigfzy.top/Article/details/gtotsyvyta.html

[U30] Py：数据类
来源：http://dali.snrcjt.cn/Article/details/gtkknxbexj.html

@dataclass(slots=True)
来源：http://dali.yj20258.top/Article/details/gtvajwbfyh.html

[U31] Py：单测
来源：http://dali.chenjidiqi.icu/Article/details/gtlrlkevpq.html

python -m pytest -q
来源：http://dali.yanxiufei.cn/Article/details/gtzissblnn.html

[U32] Py：代码格式化
来源：http://dali.guannengcc.top/Article/details/gtyjnjmadb.html

ruff format . && ruff check --fix .
来源：http://dali.jinqigufen.top/Article/details/gtnvpqehog.html

[U33] Py：打包发布
来源：http://dali.guowangkeji.top/Article/details/gtatmgtegu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.fzhhl.top/Article/details/gtqsrsrffl.html

[U34] Py：判断编码
来源：http://dali.chenlongwang.top/Article/details/gtmfcroana.html

chardet.detect(raw)
来源：http://dali.shangyingyoupin.top/Article/details/gtcczianqe.html

[U35] Py：发送邮件
来源：http://dali.tianlin.xyz/Article/details/gtkdujrtwb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhengqikj.top/Article/details/gtznrqbyvw.html

[U36] Py：定时任务
来源：http://dali.ehwqpu.com/Article/details/gtrhjqnuru.html

schedule.every(10).minutes.do(job)
来源：http://dali.nanxinkj.top/Article/details/gtwzwwvzeq.html


<!-- 参考信息 -->