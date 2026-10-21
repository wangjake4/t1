代发 wailian999

enum Color { RED, GREEN, BLUE };
来源：http://dali.ehwqpu.com/Article/details/gtbxwicmpd.html

[S15] C：类型转换
来源：http://dali.shangyingyoupin.top/Article/details/gtxyyvqtyb.html

(double) a / b
来源：http://dali.zhengqikj.top/Article/details/gtckfslgpf.html

[S16] C：位操作置位
来源：http://dali.yvedp.cn/Article/details/gtzsypdlzv.html

x |= (1 << 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwgtqhlzt.html

[S17] C：安全拼接字符串
来源：http://dali.tianlin.xyz/Article/details/gtnkbdjmdl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jiagoushi.top/Article/details/gtqnzpdfat.html

[S18] C：命令行参数
来源：http://dali.wangdashe.top/Article/details/gtrxzgcalq.html

int main(int argc, char **argv)
来源：http://dali.svipenyu.cn/Article/details/gtonozorup.html

[S19] C：快速排序
来源：http://dali.vqdsnc.cn/Article/details/gtcjthhcvv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.c1oappe.top/Article/details/gtpcqfnvnw.html

[S20] C：二分查找
来源：http://dali.fengsongda.top/Article/details/gteccradri.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xuanzx.com/Article/details/gtqhqxnhfe.html

[S21] C：字符类别判断
来源：http://dali.shuidangran.top/Article/details/gthdjhajqu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xuanzx.com/Article/details/gtgqeixcil.html

[S22] C：字符串转数字
来源：http://dali.shzxlz.cn/Article/details/gtezclrrdn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhengqikj.top/Article/details/gtszpgjrsg.html

[S23] C：随机数
来源：http://dali.daria6918.cn/Article/details/gtozyxkzrh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zdqjudy.top/Article/details/gtsxdmkama.html

[S24] C：获取本地时间
来源：http://dali.xziqi.cn/Article/details/gtfejqbavg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hnqzz.top/Article/details/gtpqdfhpud.html

[S25] C：内存拷贝
来源：http://dali.yangfankeji.com/Article/details/gtvmeluiea.html

memcpy(dst, src, n);
来源：http://dali.fengsongda.top/Article/details/gtsvzsloei.html

[S26] C：内存清零
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrfciqvac.html

memset(a, 0, sizeof a);
来源：http://dali.xinyue.icu/Article/details/gtzgqthiib.html

[S27] C：定义常量
来源：http://dali.yj20258888.top/Article/details/gtwakctdun.html

const double PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gtrdqnqita.html

[S28] C：静态变量
来源：http://dali.yueranfly.top/Article/details/gthxpbmzcu.html

static int counter = 0;
来源：http://dali.hywenlv.cn/Article/details/gtxbxlawwz.html

[S29] C：变参函数
来源：http://dali.sufxvd.cn/Article/details/gtkznnzycf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.daria6918.cn/Article/details/gtlvczrpav.html

[S30] C：头文件保护
来源：http://dali.ehwqpu.com/Article/details/gtfgpvrbbe.html

#ifndef X_H
来源：http://dali.dianchejie.cn/Article/details/gtoakgrbcj.html

#define X_H
来源：http://dali.jqgufenzy.top/Article/details/gtqfavamop.html

#endif
来源：http://dali.bjfxy.top/Article/details/gtqqzsflju.html

[S31] C++：Hello World
来源：http://dali.guannengcc.top/Article/details/gtiomeptls.html

#include <iostream>
来源：http://dali.fzhhl.top/Article/details/gtybozziii.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ehwqpu.com/Article/details/gtadbqcakr.html

[S32] C++：字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvnzwhbad.html

std::string s = "hi";  s += "!";
来源：http://dali.xziqi.cn/Article/details/gtemrakzbb.html

[S33] C++：vector 增删
来源：http://dali.jinqigfzy.top/Article/details/gtmqrcmyhw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.pycfn.com/Article/details/gtatumutuu.html

[S34] C++：遍历 vector
来源：http://dali.0kj1m.cn/Article/details/gtpmckzwex.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zycfv.cn/Article/details/gtpvsjocur.html

[S35] C++：map
来源：http://dali.svipenyu.cn/Article/details/gtijnhtzyz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gtfcxupvpw.html

[S36] C++：unordered_map
来源：http://dali.c1oappe.top/Article/details/gtzsdeydqg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gtsvghzhqa.html

[S37] C++：set
来源：http://dali.jlsjyb.cn/Article/details/gtvwrayunv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.aibaodan.cn/Article/details/gtuvibkwfq.html

[S38] C++：排序
来源：http://dali.yuxming.cn/Article/details/gtzasngjfe.html

std::sort(v.begin(), v.end());
来源：http://dali.hongshengwenyu.top/Article/details/gttnnubjbc.html

[S39] C++：自定义比较器排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhzqedmm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhongyouzk.top/Article/details/gtnpuartng.html

[S40] C++：查找元素
来源：http://dali.hfpthk.cn/Article/details/gtnxtfpngl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cucudq.cn/Article/details/gtlgorfixh.html

[S41] C++：类与构造函数
来源：http://dali.jinqigufen.top/Article/details/gtjrodxwko.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jianghu66.top/Article/details/gthiptrzth.html

[S42] C++：继承与虚函数
来源：http://dali.jinqigufen.top/Article/details/gtgdntvzrb.html

class B : public Base { public: void f() override {} };
来源：http://dali.c1oappe.top/Article/details/gtukltpcqo.html

[S43] C++：智能指针
来源：http://dali.xinyue.icu/Article/details/gtgeygwhfb.html

auto p = std::make_unique<int>(5);
来源：http://dali.kuanghao11.cn/Article/details/gtgcsvlpdx.html

[S44] C++：引用传参
来源：http://dali.andypj.xyz/Article/details/gtoomowald.html

void inc(int &x) { ++x; }
来源：http://dali.cashguo.top/Article/details/gtwxsfzjlu.html

[S45] C++：lambda
来源：http://dali.xuetiantiany.cn/Article/details/gtvrrtkbhl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.bjfxy.top/Article/details/gtsjzrdtms.html

[S46] C++：函数模板
来源：http://dali.hysaishi.cn/Article/details/gtpjndlzvd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yangfankeji.com/Article/details/gtisroqylx.html

[S47] C++：结构化绑定遍历
来源：http://dali.fengsongda.top/Article/details/gtcobwyvxs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj202588.top/Article/details/gthmatgqah.html

[S48] C++：逐行读文件
来源：http://dali.tian-w.cn/Article/details/gtybyynkzx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jlsjyb.cn/Article/details/gtxgsvzpnk.html

while (std::getline(in, line)) { }
来源：http://dali.havefunace.top/Article/details/gtlmxbnneu.html

[S49] C++：写文件
来源：http://dali.tanke756.top/Article/details/gtiqiyzxie.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zycfv.cn/Article/details/gtzewpcabb.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gtpacolitw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvxzewab.html

[S51] C++：显式类型转换
来源：http://dali.havefunace.top/Article/details/gtqmecyqua.html

static_cast<double>(a) / b
来源：http://dali.tanke756.top/Article/details/gtuwtfojse.html

[S52] C++：const 与 noexcept
来源：http://dali.zhongyouzk.top/Article/details/gtdwmydyhv.html

int size() const noexcept { return n_; }
来源：http://dali.chenlongwang.top/Article/details/gtgwjwboml.html

[S53] C++：移动语义
来源：http://dali.316326.xyz/Article/details/gthddympzv.html

std::vector<int> w = std::move(v);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtizmfobhu.html

[S54] C++：异常处理
来源：http://dali.hnxiangtu.top/Article/details/gtwqcxeztd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.bjfxy.top/Article/details/gtplyskhxs.html

[S55] C++：结构化绑定
来源：http://dali.xuetiantiany.cn/Article/details/gtqcqrghuq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhoulong.xyz/Article/details/gteqtomxvz.html

[S56] C++：optional
来源：http://dali.tianlin.xyz/Article/details/gtkpmkfokt.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.aibaodan.cn/Article/details/gtafmugwlv.html

[S57] C++：编译期常量
来源：http://dali.hammf.cn/Article/details/gtrfoyplfv.html

constexpr int N = 10;
来源：http://dali.xuanzx.com/Article/details/gtydfpfccc.html

[S58] C++：命名空间
来源：http://dali.fengsongda.top/Article/details/gtzymirhui.html

namespace ns { int f() { return 1; } }
来源：http://dali.gzhubu.top/Article/details/gtoenzmdnb.html

[S59] C++：静态断言
来源：http://dali.shzxlz.cn/Article/details/gtxrnrxtqf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.daria6918.cn/Article/details/gtejdngaii.html

[S60] C++：遍历并删除元素
来源：http://dali.aibaodan.cn/Article/details/gtfulcymif.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hammf.cn/Article/details/gtzaucssgw.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtfcftggyx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yuanzhike.top/Article/details/gtpdfwbkow.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtgpuwsbpf.html

[T01] Kotlin：Hello World
来源：http://dali.cheryme.top/Article/details/gtnssnayji.html

println("Hello")
来源：http://dali.shuidangran.top/Article/details/gtvsdctmyj.html

[T02] Kotlin：变量
来源：http://dali.sxryk.cn/Article/details/gtllpxmyqd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shanyushiyangkeji.top/Article/details/gtguyhhuvq.html

[T03] Kotlin：字符串模板
来源：http://dali.sysykeji.top/Article/details/gtnremxesg.html

"值: $b"
来源：http://dali.yuxming.cn/Article/details/gtiflwaapc.html

[T04] Kotlin：空安全
来源：http://dali.bjfxy.top/Article/details/gtwlyypveb.html

val n: String? = null;  n?.length
来源：http://dali.iojbl.cn/Article/details/gtsvkfnnaa.html

[T05] Kotlin：when 表达式
来源：http://dali.hnqzz.top/Article/details/gtthuhzdfv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hywenlv.cn/Article/details/gtxdtbagjg.html

[T06] Kotlin：集合映射
来源：http://dali.xylfe.cn/Article/details/gtmqbxdftg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.316326.xyz/Article/details/gtkhuyidhz.html

[T07] Kotlin：集合过滤
来源：http://dali.jinqigfzy.top/Article/details/gtppfpgkre.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.dianchejie.cn/Article/details/gtzqnvaarc.html

[T08] Kotlin：数据类
来源：http://dali.xylfe.cn/Article/details/gtofgjjfqu.html

data class User(val name: String, val age: Int)
来源：http://dali.zycfv.cn/Article/details/gtrsgeqhhe.html

[T09] Kotlin：扩展函数
来源：http://dali.xinyue.icu/Article/details/gtujfypndf.html

fun String.exclaim() = this + "!"
来源：http://dali.cucudq.cn/Article/details/gtcfcxdcoc.html

[T10] Kotlin：默认参数
来源：http://dali.zhixingplan.top/Article/details/gtxvzkeexs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.tanke756.top/Article/details/gtwynolrzv.html

[T11] Kotlin：协程
来源：http://dali.iojbl.cn/Article/details/gtbdpbjjvk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.aibaodan.cn/Article/details/gtrqcbylqj.html

[T12] Kotlin：解构声明
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbnpdhoye.html

val (a, b) = Pair(1, 2)
来源：http://dali.havefunace.top/Article/details/gtfmejsqpd.html

[T13] Kotlin：只读 Map
来源：http://dali.yangfankeji.com/Article/details/gtsgbuvojd.html

val m = mapOf("a" to 1)
来源：http://dali.shuidangran.top/Article/details/gthvfotckp.html

[T14] Kotlin：循环
来源：http://dali.zhiwuduotai.top/Article/details/gtcczcqxno.html

for (i in 1..10) println(i)
来源：http://dali.yonumen.top/Article/details/gtkafjycsr.html

[T15] Kotlin：接口
来源：http://dali.kuanghao11.cn/Article/details/gtqmmzsonu.html

interface Shape { fun area(): Double }
来源：http://dali.hysaishi.cn/Article/details/gtkydqcnor.html

[T16] Swift：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtzatsfrcu.html

print("Hello")
来源：http://dali.yvedp.cn/Article/details/gtuwbyeexq.html

[T17] Swift：变量与常量
来源：http://dali.yanxiufei.cn/Article/details/gtqsoazvmy.html

var a = 1;  let b = 2
来源：http://dali.feifeiyinyue.top/Article/details/gttjnqcvhi.html

[T18] Swift：字符串插值
来源：http://dali.shuidangran.top/Article/details/gtwvbexvyc.html

"值: \(b)"
来源：http://dali.nanxinkj.top/Article/details/gtgaltyrrm.html

[T19] Swift：可选绑定
来源：http://dali.vqdsnc.cn/Article/details/gtsvfeczxx.html

if let n = opt { print(n) }
来源：http://dali.ybcxt.top/Article/details/gtcnefqfwt.html

[T20] Swift：数组操作
来源：http://dali.shuidangran.top/Article/details/gtpiowcxsj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.chenzaomai.com/Article/details/gtfmhrvkfz.html

[T21] Swift：遍历
来源：http://dali.redwolf501.top/Article/details/gtzkibgfng.html

for x in a { print(x) }
来源：http://dali.fzhhl.top/Article/details/gtiutawpjh.html

[T22] Swift：字典
来源：http://dali.jqgfzy.top/Article/details/gtoydcunuk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ybcxt.top/Article/details/gtllkixvgj.html

[T23] Swift：函数
来源：http://dali.cdnleiting.top/Article/details/gttaxbzzkh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.c1oappe.top/Article/details/gtpjscemyx.html

[T24] Swift：闭包
来源：http://dali.cqqwz.cn/Article/details/gthyhrowac.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.daxiang520.top/Article/details/gtapyjxyik.html

[T25] Swift：结构体
来源：http://dali.9152youxi.cn/Article/details/gthtscpdkv.html

struct P { var x: Int }
来源：http://dali.aizwys.cn/Article/details/gtlgkvvxpr.html

[T26] Swift：类与重写
来源：http://dali.gotoacloud.top/Article/details/gtjusayyxa.html

class A: Base { override func f() {} }
来源：http://dali.sweek.top/Article/details/gtthtiopdn.html

[T27] Swift：错误处理
来源：http://dali.zdqjudy.top/Article/details/gtusxclato.html

do { try f() } catch { print(error) }
来源：http://dali.hnqzz.top/Article/details/gtrbfzhwyi.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gtubhvvyut.html

enum Color { case red, green }
来源：http://dali.jqgufenzy.top/Article/details/gtukxglmlv.html

[T29] Swift：guard 提前返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gttbrlgvod.html

guard let x = opt else { return }
来源：http://dali.birdmap.top/Article/details/gtreubgzre.html

[T30] Swift：协议
来源：http://dali.chenzaomai.com/Article/details/gtinyybpdm.html

protocol Shape { func area() -> Double }
来源：http://dali.tian-w.cn/Article/details/gtibxrqhng.html

[T31] Lua：Hello World
来源：http://dali.meibo888.top/Article/details/gtjzbjzlzb.html

print("Hello")
来源：http://dali.chenzaomai.com/Article/details/gtqosoujrp.html

[T32] Lua：局部变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqbgomxgl.html

local a = 1
来源：http://dali.chenlongwang.top/Article/details/gtccdvzbow.html

[T33] Lua：表（数组）
来源：http://dali.jqgufenzy.top/Article/details/gtsaysqjoa.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.gaohongyu789.top/Article/details/gtqfzeexin.html

[T34] Lua：遍历表
来源：http://dali.yj202588.top/Article/details/gtsupbdtij.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.snrcjt.cn/Article/details/gtmpwlehfk.html

[T35] Lua：字典表
来源：http://dali.gogol.net.cn/Article/details/gtpjhvjjuk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hysaishi.cn/Article/details/gtzttsrmyw.html

[T36] Lua：函数
来源：http://dali.fengsongda.top/Article/details/gtozzswlsw.html

function add(a, b) return a + b end
来源：http://dali.snrcjt.cn/Article/details/gthysglmep.html

[T37] Lua：字符串拼接
来源：http://dali.yangfankeji.com/Article/details/gtkcefpctq.html

"a" .. "b"
来源：http://dali.zhixingplan.top/Article/details/gtsetydvto.html

[T38] Lua：条件
来源：http://dali.redwolf501.top/Article/details/gtlhinqhrk.html

if x > 0 then print("正") end
来源：http://dali.yj20258888.top/Article/details/gtsysmmhdu.html

[T39] Lua：模式匹配
来源：http://dali.jinqigfzy.top/Article/details/gteqienqcr.html

string.find(s, "%d+")
来源：http://dali.cheryme.top/Article/details/gtomtkclcs.html

[T40] Lua：元表
来源：http://dali.kuanghao11.cn/Article/details/gtrgmhoewv.html

setmetatable({}, { __index = base })
来源：http://dali.hongshengwenyu.top/Article/details/gtqlupgbip.html

[T41] Perl：Hello World
来源：http://dali.xinyue.icu/Article/details/gtyxqmzbdg.html

print "Hello\n";
来源：http://dali.yuanzhike.top/Article/details/gtmksvepta.html

[T42] Perl：变量类型
来源：http://dali.0kj1m.cn/Article/details/gtexljvzcu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaanwmovt.html

[T43] Perl：字符串插值
来源：http://dali.xziqi.cn/Article/details/gtcvwuuyoy.html

"值: $a"
来源：http://dali.wangdashe.top/Article/details/gtyjqjyxlt.html

[T44] Perl：条件
来源：http://dali.andypj.xyz/Article/details/gtwcujakfw.html

if ($a > 0) { print "正"; }
来源：http://dali.daria6918.cn/Article/details/gtflmqxdwl.html

[T45] Perl：数组遍历
来源：http://dali.fengsongda.top/Article/details/gtbqqytsyz.html

for my $x (@arr) { print $x; }
来源：http://dali.ydzc1.top/Article/details/gtumckpafm.html

[T46] Perl：哈希操作
来源：http://dali.dianchejie.cn/Article/details/gttrfccmvg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jinqigufen.top/Article/details/gtaoiccvzz.html

[T47] Perl：正则捕获
来源：http://dali.chenlongwang.top/Article/details/gtibdtkbhw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yj202588.top/Article/details/gtwlrxjpla.html

[T48] Perl：正则替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdxalrcgn.html

$s =~ s/old/new/g;
来源：http://dali.aizwys.cn/Article/details/gtfhczuris.html

[T49] Perl：函数
来源：http://dali.hongshengwenyu.top/Article/details/gtblxjdvjw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gtyrkrblnw.html

[T50] Perl：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtalrsddzy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.smart0.xyz/Article/details/gtoczghcuj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xziqi.cn/Article/details/gtzxnptdct.html

[T51] Scala：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtetajkkfe.html

println("Hello")
来源：http://dali.sysykeji.top/Article/details/gthouyfgnu.html

[T52] Scala：变量
来源：http://dali.hysaishi.cn/Article/details/gtlyyybpar.html

val a = 1;  var b = 2
来源：http://dali.ehwqpu.com/Article/details/gtoahnoycf.html

[T53] Scala：字符串插值
来源：http://dali.wangdashe.top/Article/details/gtuytjidhn.html

s"值: $b"
来源：http://dali.nanxinkj.top/Article/details/gtjhmfhzmv.html

[T54] Scala：集合映射
来源：http://dali.smart0.xyz/Article/details/gtpatlqwlw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yueranfly.top/Article/details/gtqaopnzqb.html

[T55] Scala：集合过滤
来源：http://dali.kuanghao11.cn/Article/details/gtzkgtmepu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sysykeji.top/Article/details/gtrriiqkbi.html

[T56] Scala：样例类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwgpqurb.html

case class User(name: String, age: Int)
来源：http://dali.zhiwuduotai.top/Article/details/gtwytxdaty.html

[T57] Scala：模式匹配
来源：http://dali.cashguo.top/Article/details/gtxtqnhpne.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhongyouzk.top/Article/details/gtwzjnhmdw.html

[T58] Scala：函数定义
来源：http://dali.ybcxt.top/Article/details/gtfaxiqitw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.fzhhl.top/Article/details/gtjgdsqpee.html

[T59] Scala：循环
来源：http://dali.sufxvd.cn/Article/details/gtvzxgbeym.html

for (i <- 1 to 10) println(i)
来源：http://dali.jianghu66.top/Article/details/gtgqfmvjso.html

[T60] Scala：折叠
来源：http://dali.zhengqikj.top/Article/details/gtusurxvkv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.svipenyu.cn/Article/details/gtkjfhfmqq.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtlqgncyzz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gteixtivna.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtfnxgfymq.html

[U01] Py：创建虚拟环境
来源：http://dali.ydzc1.top/Article/details/gtuobvpzec.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jianghu66.top/Article/details/gtlbvkqvpi.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cucudq.cn/Article/details/gtljpiibrb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gthpqwmqcq.html

[U03] Py：加载 .env 配置
来源：http://dali.nanxinkj.top/Article/details/gtpbmubwyl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.9152youxi.cn/Article/details/gtywuciiih.html

[U04] Py：变量调试打印
来源：http://dali.cashguo.top/Article/details/gtpcvfdpyb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.tian-w.cn/Article/details/gthblhrisi.html

[U05] Py：列表去重且保序
来源：http://dali.shangyingyoupin.top/Article/details/gttevlvozy.html

list(dict.fromkeys(arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjbzxktkw.html

[U06] Py：合并两个字典
来源：http://dali.jiagoushi.top/Article/details/gtqovlcabh.html

{**a, **b}
来源：http://dali.cashguo.top/Article/details/gtpgqemfxx.html

[U07] Py：反转字典键值
来源：http://dali.feifeiyinyue.top/Article/details/gtospxdwyc.html

{v: k for k, v in d.items()}
来源：http://dali.cheryme.top/Article/details/gtlxobxece.html

[U08] Py：展平二维列表
来源：http://dali.cqqwz.cn/Article/details/gtpqjvghpj.html

[y for x in nested for y in x]
来源：http://dali.bjfxy.top/Article/details/gtcmggfqve.html

[U09] Py：字典取最大值的键
来源：http://dali.chenzaomai.com/Article/details/gtpukrmxcw.html

max(d, key=d.get)
来源：http://dali.havefunace.top/Article/details/gtrhluajmr.html

[U10] Py：按值排序字典
来源：http://dali.gaohongyu789.top/Article/details/gtsdfvjjih.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shangyingyoupin.top/Article/details/gtihjlcrds.html

[U11] Py：生成器表达式
来源：http://dali.gaohongyu789.top/Article/details/gtxkxcsrgo.html

(x * 2 for x in arr)
来源：http://dali.andypj.xyz/Article/details/gtellnjewb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hnxiangtu.top/Article/details/gtujxzlhmw.html

Counter(arr).most_common(3)
来源：http://dali.wangshuangyany.cn/Article/details/gtcsoiajdt.html

[U13] Py：固定长度队列
来源：http://dali.xuanzx.com/Article/details/gtcfubvsgx.html

deque(maxlen=10)
来源：http://dali.ppjwa.cn/Article/details/gtbqlhcskb.html

[U14] Py：分组收集到列表
来源：http://dali.haohaochexian.top/Article/details/gtnvysrhoy.html

defaultdict(list)
来源：http://dali.smart0.xyz/Article/details/gtfpnvsmbs.html

[U15] Py：高精度计时
来源：http://dali.dashuyun.cn/Article/details/gtylhlbuur.html

t = time.perf_counter()
来源：http://dali.xinyue.icu/Article/details/gtekrpqgwe.html

[U16] Py：命令行参数解析
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtozwngbxs.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.daxiang520.top/Article/details/gtyiyoorub.html

[U17] Py：初始化日志
来源：http://dali.jqgfzy.top/Article/details/gtdrsdeahr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.gaohongyu789.top/Article/details/gtgfsftmhn.html

[U18] Py：预编译正则
来源：http://dali.gotoacloud.top/Article/details/gtznatigoj.html

pat = re.compile(r"\d+")
来源：http://dali.bjfxy.top/Article/details/gtpagbqgjr.html

[U19] Py：正则替换带回调
来源：http://dali.tian-w.cn/Article/details/gtwqnubpbj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.smart0.xyz/Article/details/gtnsgupbnf.html

[U20] Py：缓存函数结果
来源：http://dali.aibaodan.cn/Article/details/gtvaokwcst.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jianghu66.top/Article/details/gtnkcnpjeo.html

[U21] Py：自定义上下文管理器
来源：http://dali.jianghu66.top/Article/details/gtwsixninx.html

@contextlib.contextmanager
来源：http://dali.shuidangran.top/Article/details/gtekeqhlcn.html

[U22] Py：矩阵转置
来源：http://dali.dashuyun.cn/Article/details/gtwidmsmuh.html

list(zip(*m))
来源：http://dali.quarkkingdee.top/Article/details/gtaguqctaf.html

[U23] Py：分块读取大文件
来源：http://dali.pengpengdd.cyou/Article/details/gtcxrljuse.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.daria6918.cn/Article/details/gtmraiezmm.html

[U24] Py：路径操作
来源：http://dali.zhongyouzk.top/Article/details/gtbrmzcxey.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.daxiang520.top/Article/details/gtippkdqkx.html

[U25] Py：CSV 按字典读
来源：http://dali.zhongyouzk.top/Article/details/gtidzcmzfl.html

csv.DictReader(f)
来源：http://dali.yanxiufei.cn/Article/details/gtjwulkojz.html

[U26] Py：并发下载
来源：http://dali.jinghuilouyu.cn/Article/details/gtckmacgxs.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jqgfzy.top/Article/details/gtevqdnxtj.html

[U27] Py：异步 HTTP
来源：http://dali.gotoacloud.top/Article/details/gtbtosango.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxwjkiuq.html

[U28] Py：类型别名
来源：http://dali.nwbrower.top/Article/details/gtshiukgas.html

UserId = int
来源：http://dali.hammf.cn/Article/details/gtmahvjvqp.html

[U29] Py：属性校验
来源：http://dali.jqgufenzy.top/Article/details/gthwpptqpr.html

@property 与 @x.setter 配合
来源：http://dali.zhaomingkeji.xyz/Article/details/gtctzfwvpz.html

[U30] Py：数据类
来源：http://dali.jianghu66.top/Article/details/gtxhdcuhoi.html

@dataclass(slots=True)
来源：http://dali.iojbl.cn/Article/details/gtrdhlgcel.html

[U31] Py：单测
来源：http://dali.shzxlz.cn/Article/details/gtwosvkhwz.html

python -m pytest -q
来源：http://dali.shanyushiyangtech.top/Article/details/gtbrzarjog.html

[U32] Py：代码格式化
来源：http://dali.chenzaomai.com/Article/details/gtribxwknt.html

ruff format . && ruff check --fix .
来源：http://dali.cucudq.cn/Article/details/gtypxtkadm.html

[U33] Py：打包发布
来源：http://dali.jqgfzy.top/Article/details/gtvfuvyhnr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrllybqlc.html

[U34] Py：判断编码
来源：http://dali.chenjidiqi.icu/Article/details/gtxhhjgrzj.html

chardet.detect(raw)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaikiejgc.html

[U35] Py：发送邮件
来源：http://dali.dianchejie.cn/Article/details/gtcmsosrnt.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jinyuanbaomall.cn/Article/details/gturyaeksp.html

[U36] Py：定时任务
来源：http://dali.xziqi.cn/Article/details/gtmfxiszpz.html

schedule.every(10).minutes.do(job)
来源：http://dali.yj202588.top/Article/details/gtpwuucsiz.html

[U37] Py：读写 Excel
来源：http://dali.vqdsnc.cn/Article/details/gtudtksqiu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shanyushiyangtech.top/Article/details/gtnawfeyct.html

[U38] Py：获取脚本所在目录
来源：http://dali.daxiang520.top/Article/details/gtmcdqkaar.html

Path(__file__).resolve().parent
来源：http://dali.nanxinkj.top/Article/details/gtwtbwvcve.html


<!-- 参考信息 -->