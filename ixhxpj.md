代发 wailian999

FILE *f = fopen("a.txt", "r");
来源：http://dali.pengpengdd.cyou/Article/details/gtfascntgj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinqigufen.top/Article/details/gtlkfktbpn.html

fclose(f);
来源：http://dali.fengsongda.top/Article/details/gtiaxogleo.html

[S12] C：写文件
来源：http://dali.ybcxt.top/Article/details/gtajalkloc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ivvv.top/Article/details/gtgtppuvrg.html

[S13] C：宏定义
来源：http://dali.shzxlz.cn/Article/details/gtqnfmblfn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jlsjyb.cn/Article/details/gtowzlafuo.html

[S14] C：枚举
来源：http://dali.dianchejie.cn/Article/details/gtnexunwie.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tanke756.top/Article/details/gtqqjdkfqv.html

[S15] C：类型转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtizqjulyc.html

(double) a / b
来源：http://dali.zdqjudy.top/Article/details/gtqtwgjeaf.html

[S16] C：位操作置位
来源：http://dali.hnxiangtu.top/Article/details/gtnniuayxc.html

x |= (1 << 3);
来源：http://dali.cashguo.top/Article/details/gtnbukjekz.html

[S17] C：安全拼接字符串
来源：http://dali.cucudq.cn/Article/details/gtzzkvpkco.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gzhubu.top/Article/details/gtmuqdkyje.html

[S18] C：命令行参数
来源：http://dali.hammf.cn/Article/details/gtvwtgtuda.html

int main(int argc, char **argv)
来源：http://dali.redwolf501.top/Article/details/gtproumnyn.html

[S19] C：快速排序
来源：http://dali.vqdsnc.cn/Article/details/gtwcvrkcqt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hywenlv.cn/Article/details/gtflwofmop.html

[S20] C：二分查找
来源：http://dali.yj20258.top/Article/details/gtxwodqglt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj202588.top/Article/details/gtttpzmuvb.html

[S21] C：字符类别判断
来源：http://dali.yonumen.top/Article/details/gtjkvpufth.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.fzhhl.top/Article/details/gtijtkdisr.html

[S22] C：字符串转数字
来源：http://dali.cheryme.top/Article/details/gtvguxiinp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.guannengcc.top/Article/details/gtynqbeklu.html

[S23] C：随机数
来源：http://dali.hysaishi.cn/Article/details/gtvnqtvyaf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gotoacloud.top/Article/details/gtmzuginmg.html

[S24] C：获取本地时间
来源：http://dali.yongpay.top/Article/details/gtanqgmcbl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqrtfnvxa.html

[S25] C：内存拷贝
来源：http://dali.shuidangran.top/Article/details/gtsgayumfb.html

memcpy(dst, src, n);
来源：http://dali.c1oappe.top/Article/details/gtwypxhxap.html

[S26] C：内存清零
来源：http://dali.mhx1999.top/Article/details/gtckqggryv.html

memset(a, 0, sizeof a);
来源：http://dali.yvedp.cn/Article/details/gtggunvmki.html

[S27] C：定义常量
来源：http://dali.cdnleiting.top/Article/details/gtfwfwhyfd.html

const double PI = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gtpgbknyye.html

[S28] C：静态变量
来源：http://dali.cucudq.cn/Article/details/gtereqcloa.html

static int counter = 0;
来源：http://dali.nanxuanxn.top/Article/details/gtngmsjhiv.html

[S29] C：变参函数
来源：http://dali.gaohongyu789.top/Article/details/gtgyhfmpyy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gaohongyu789.top/Article/details/gtwqbquqyz.html

[S30] C：头文件保护
来源：http://dali.c1oappe.top/Article/details/gtiqmstsht.html

#ifndef X_H
来源：http://dali.yongpay.top/Article/details/gtsoetlerg.html

#define X_H
来源：http://dali.shanyushiyangtech.top/Article/details/gtugqncljt.html

#endif
来源：http://dali.chenlongwang.top/Article/details/gtwnkozfpe.html

[S31] C++：Hello World
来源：http://dali.9152youxi.cn/Article/details/gthsvnxftg.html

#include <iostream>
来源：http://dali.tian-w.cn/Article/details/gtzbjdthun.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hywenlv.cn/Article/details/gtkltbfrpf.html

[S32] C++：字符串
来源：http://dali.chenzaomai.com/Article/details/gtlffpfphz.html

std::string s = "hi";  s += "!";
来源：http://dali.zhoulong.xyz/Article/details/gtnyohtzho.html

[S33] C++：vector 增删
来源：http://dali.jinqigfzy.top/Article/details/gtmzmbvtma.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.quarkkingdee.top/Article/details/gtxbphxvhg.html

[S34] C++：遍历 vector
来源：http://dali.bjfxy.top/Article/details/gtfwbacuep.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.daxiang520.top/Article/details/gtdlzeyqom.html

[S35] C++：map
来源：http://dali.cheryme.top/Article/details/gtukhacfue.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gtgaebtpmg.html

[S36] C++：unordered_map
来源：http://dali.0kj1m.cn/Article/details/gtndnnirpl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtjgivtxzn.html

[S37] C++：set
来源：http://dali.316326.xyz/Article/details/gthqvdesnm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gogol.net.cn/Article/details/gtkjbpkzbr.html

[S38] C++：排序
来源：http://dali.meibo888.top/Article/details/gtndhnoomn.html

std::sort(v.begin(), v.end());
来源：http://dali.sxryk.cn/Article/details/gtvwcqplzv.html

[S39] C++：自定义比较器排序
来源：http://dali.sufxvd.cn/Article/details/gtsgunblkf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.aibaodan.cn/Article/details/gtmmgdfzrk.html

[S40] C++：查找元素
来源：http://dali.jianghu66.top/Article/details/gtklsuycnx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nanxinkj.top/Article/details/gtjqxhcvhs.html

[S41] C++：类与构造函数
来源：http://dali.nanxinkj.top/Article/details/gtzrhnrvry.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenzaomai.com/Article/details/gtwxeezcwd.html

[S42] C++：继承与虚函数
来源：http://dali.andypj.xyz/Article/details/gtyfncyumc.html

class B : public Base { public: void f() override {} };
来源：http://dali.nanxuanxn.top/Article/details/gtzqlvfanz.html

[S43] C++：智能指针
来源：http://dali.yangfankeji.com/Article/details/gtvdweulto.html

auto p = std::make_unique<int>(5);
来源：http://dali.hywenlv.cn/Article/details/gtwtilkgwk.html

[S44] C++：引用传参
来源：http://dali.ppjwa.cn/Article/details/gtiefodjuq.html

void inc(int &x) { ++x; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlveexogx.html

[S45] C++：lambda
来源：http://dali.c1oappe.top/Article/details/gtnodqwhvu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmhioslvc.html

[S46] C++：函数模板
来源：http://dali.jinqigfzy.top/Article/details/gthsplpfxm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hnqzz.top/Article/details/gtucoiobab.html

[S47] C++：结构化绑定遍历
来源：http://dali.gzhubu.top/Article/details/gttemykxso.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yvedp.cn/Article/details/gtwvygneus.html

[S48] C++：逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gtkrvluyfh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ivvv.top/Article/details/gttukpxbem.html

while (std::getline(in, line)) { }
来源：http://dali.zhoulong.xyz/Article/details/gtyrhcvmck.html

[S49] C++：写文件
来源：http://dali.redwolf501.top/Article/details/gteditebcz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.dianchejie.cn/Article/details/gtwhbpumnc.html

[S50] C++：格式化数字
来源：http://dali.yanxiufei.cn/Article/details/gtescwvbue.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtlcoktbyp.html

[S51] C++：显式类型转换
来源：http://dali.jiagoushi.top/Article/details/gtejzcqshu.html

static_cast<double>(a) / b
来源：http://dali.tian-w.cn/Article/details/gtxikrqbnv.html

[S52] C++：const 与 noexcept
来源：http://dali.hnxiangtu.top/Article/details/gtpnlirbpz.html

int size() const noexcept { return n_; }
来源：http://dali.hysaishi.cn/Article/details/gtiercrfgl.html

[S53] C++：移动语义
来源：http://dali.zhengqikj.top/Article/details/gtaioybkkl.html

std::vector<int> w = std::move(v);
来源：http://dali.fengsongda.top/Article/details/gtfdjsrpax.html

[S54] C++：异常处理
来源：http://dali.smart0.xyz/Article/details/gttrsfugpt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.9152youxi.cn/Article/details/gtpdavmqqh.html

[S55] C++：结构化绑定
来源：http://dali.tian-w.cn/Article/details/gtsppihnhf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.tian-w.cn/Article/details/gtfyljlthr.html

[S56] C++：optional
来源：http://dali.haohaochexian.top/Article/details/gtchvrjybz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.guowangkeji.top/Article/details/gtemxggonv.html

[S57] C++：编译期常量
来源：http://dali.ehwqpu.com/Article/details/gtjziyugyq.html

constexpr int N = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gtteckvctv.html

[S58] C++：命名空间
来源：http://dali.yuxming.cn/Article/details/gtjjzwndnw.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjoyppwb.html

[S59] C++：静态断言
来源：http://dali.gogol.net.cn/Article/details/gtxodhwbax.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hnxiangtu.top/Article/details/gtxeirbccm.html

[S60] C++：遍历并删除元素
来源：http://dali.wangdashe.top/Article/details/gttruakwdt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.bjfxy.top/Article/details/gtokfgtkwq.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gthhttosxk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hnqzz.top/Article/details/gthdmpiifi.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtpckxvffm.html

[T01] Kotlin：Hello World
来源：http://dali.ydzc1.top/Article/details/gtlxrhiooz.html

println("Hello")
来源：http://dali.tanke756.top/Article/details/gtjgpbzubu.html

[T02] Kotlin：变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpnvlbnqh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinqigufen.top/Article/details/gtkfreyiwx.html

[T03] Kotlin：字符串模板
来源：http://dali.tianlin.xyz/Article/details/gtnqqrkfrj.html

"值: $b"
来源：http://dali.sxryk.cn/Article/details/gtzdgbnalm.html

[T04] Kotlin：空安全
来源：http://dali.chenlongwang.top/Article/details/gtpiovsyjr.html

val n: String? = null;  n?.length
来源：http://dali.ehwqpu.com/Article/details/gtrtstkrlw.html

[T05] Kotlin：when 表达式
来源：http://dali.jqgfzy.top/Article/details/gtnlpvtkru.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.aibaodan.cn/Article/details/gtdwsxkrgp.html

[T06] Kotlin：集合映射
来源：http://dali.jinqigfzy.top/Article/details/gtmintabcf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jqgfzy.top/Article/details/gtoggvpkfh.html

[T07] Kotlin：集合过滤
来源：http://dali.smart0.xyz/Article/details/gtnqptunpy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gogol.net.cn/Article/details/gtbvtlpbdv.html

[T08] Kotlin：数据类
来源：http://dali.xziqi.cn/Article/details/gtpwzzjalo.html

data class User(val name: String, val age: Int)
来源：http://dali.daria6918.cn/Article/details/gtbqogijts.html

[T09] Kotlin：扩展函数
来源：http://dali.smart0.xyz/Article/details/gtpmipygxm.html

fun String.exclaim() = this + "!"
来源：http://dali.mhx1999.top/Article/details/gtzpsxlnhn.html

[T10] Kotlin：默认参数
来源：http://dali.ybcxt.top/Article/details/gtjrjbfefm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ivvv.top/Article/details/gtwkwgcgsm.html

[T11] Kotlin：协程
来源：http://dali.xziqi.cn/Article/details/gtzmyonnbd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shzxlz.cn/Article/details/gtdthfdwuw.html

[T12] Kotlin：解构声明
来源：http://dali.pengpengdd.cyou/Article/details/gtvjkevbly.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkcofpqhs.html

[T13] Kotlin：只读 Map
来源：http://dali.316326.xyz/Article/details/gthdqrxqst.html

val m = mapOf("a" to 1)
来源：http://dali.jianghu66.top/Article/details/gtkkmgagcs.html

[T14] Kotlin：循环
来源：http://dali.jinqigufen.top/Article/details/gtlnarardn.html

for (i in 1..10) println(i)
来源：http://dali.andypj.xyz/Article/details/gtemknxfme.html

[T15] Kotlin：接口
来源：http://dali.nwbrower.top/Article/details/gtgdvlmmfd.html

interface Shape { fun area(): Double }
来源：http://dali.jqgufenzy.top/Article/details/gtlgbmlyuf.html

[T16] Swift：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtywhxkghk.html

print("Hello")
来源：http://dali.gogol.net.cn/Article/details/gththfkcrt.html

[T17] Swift：变量与常量
来源：http://dali.quarkkingdee.top/Article/details/gtrlpejavp.html

var a = 1;  let b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsiyombjf.html

[T18] Swift：字符串插值
来源：http://dali.hongshengwenyu.top/Article/details/gtvczlwfoo.html

"值: \(b)"
来源：http://dali.xylfe.cn/Article/details/gtvvdaebwd.html

[T19] Swift：可选绑定
来源：http://dali.jinqigufen.top/Article/details/gtmvzqipbo.html

if let n = opt { print(n) }
来源：http://dali.yuanzhike.top/Article/details/gtzeimnpxc.html

[T20] Swift：数组操作
来源：http://dali.jinghuilouyu.cn/Article/details/gtgcamuzhg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.smart0.xyz/Article/details/gtqaxfkfsz.html

[T21] Swift：遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtvatitqtt.html

for x in a { print(x) }
来源：http://dali.yongpay.top/Article/details/gtiztnqrnv.html

[T22] Swift：字典
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqjagyev.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hysaishi.cn/Article/details/gtimuqtosf.html

[T23] Swift：函数
来源：http://dali.gzhubu.top/Article/details/gtydtynddc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlzrnepkp.html

[T24] Swift：闭包
来源：http://dali.chenlongwang.top/Article/details/gtsjzbanze.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cqqwz.cn/Article/details/gtpjxfvzui.html

[T25] Swift：结构体
来源：http://dali.yj202588.top/Article/details/gtzhlnskgg.html

struct P { var x: Int }
来源：http://dali.ydzc1.top/Article/details/gtyccctzpx.html

[T26] Swift：类与重写
来源：http://dali.xziqi.cn/Article/details/gtoycrxffx.html

class A: Base { override func f() {} }
来源：http://dali.wangshuangyany.cn/Article/details/gtmxrswzex.html

[T27] Swift：错误处理
来源：http://dali.dianchejie.cn/Article/details/gtoxkskeey.html

do { try f() } catch { print(error) }
来源：http://dali.316326.xyz/Article/details/gttabqiulq.html

[T28] Swift：枚举
来源：http://dali.tanke756.top/Article/details/gtgzsgfqsy.html

enum Color { case red, green }
来源：http://dali.andypj.xyz/Article/details/gtjefwethm.html

[T29] Swift：guard 提前返回
来源：http://dali.zycfv.cn/Article/details/gtqqffehsi.html

guard let x = opt else { return }
来源：http://dali.sxryk.cn/Article/details/gtkintwlke.html

[T30] Swift：协议
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxtvqjniz.html

protocol Shape { func area() -> Double }
来源：http://dali.dianchejie.cn/Article/details/gtputjkybv.html

[T31] Lua：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtksqjugrl.html

print("Hello")
来源：http://dali.ppjwa.cn/Article/details/gtfoafhcwe.html

[T32] Lua：局部变量
来源：http://dali.yongpay.top/Article/details/gtkjypuyvx.html

local a = 1
来源：http://dali.yongpay.top/Article/details/gtquymgotr.html

[T33] Lua：表（数组）
来源：http://dali.ppjwa.cn/Article/details/gteakyrmqp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinghuilouyu.cn/Article/details/gtnwqzgcco.html

[T34] Lua：遍历表
来源：http://dali.yangfankeji.com/Article/details/gtxybefmeu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zycfv.cn/Article/details/gtjatafsgg.html

[T35] Lua：字典表
来源：http://dali.ppjwa.cn/Article/details/gtdgtjzjdr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.wangdashe.top/Article/details/gtjaetenon.html

[T36] Lua：函数
来源：http://dali.mhx1999.top/Article/details/gtifilhacz.html

function add(a, b) return a + b end
来源：http://dali.yuxming.cn/Article/details/gtxphonqzb.html

[T37] Lua：字符串拼接
来源：http://dali.hammf.cn/Article/details/gtyyhasymb.html

"a" .. "b"
来源：http://dali.sxryk.cn/Article/details/gtxgkmspjw.html

[T38] Lua：条件
来源：http://dali.aizwys.cn/Article/details/gttfvxhlpn.html

if x > 0 then print("正") end
来源：http://dali.zdqjudy.top/Article/details/gtlvtousdg.html

[T39] Lua：模式匹配
来源：http://dali.aibaodan.cn/Article/details/gtoxjkjzxg.html

string.find(s, "%d+")
来源：http://dali.cdnleiting.top/Article/details/gttgwlbiht.html

[T40] Lua：元表
来源：http://dali.xuetiantiany.cn/Article/details/gtetwlhubv.html

setmetatable({}, { __index = base })
来源：http://dali.smart0.xyz/Article/details/gtlhfyqtrg.html

[T41] Perl：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtqrhcicfj.html

print "Hello\n";
来源：http://dali.nanxuanxn.top/Article/details/gtjefunirk.html

[T42] Perl：变量类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahvkjnlw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhoulong.xyz/Article/details/gtsvgysvtl.html

[T43] Perl：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gtpirscqlw.html

"值: $a"
来源：http://dali.jinqigufen.top/Article/details/gtimhfdtou.html

[T44] Perl：条件
来源：http://dali.jianghu66.top/Article/details/gtwoxypxtr.html

if ($a > 0) { print "正"; }
来源：http://dali.gogol.net.cn/Article/details/gtrskyrxkf.html

[T45] Perl：数组遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtadzsszia.html

for my $x (@arr) { print $x; }
来源：http://dali.yj202588.top/Article/details/gtknqbdhui.html

[T46] Perl：哈希操作
来源：http://dali.dianchejie.cn/Article/details/gtzmhartst.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.dashuyun.cn/Article/details/gtbyemjqhx.html

[T47] Perl：正则捕获
来源：http://dali.zycfv.cn/Article/details/gtdgoowdny.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jlsjyb.cn/Article/details/gtvnxwyzfd.html

[T48] Perl：正则替换
来源：http://dali.jlsjyb.cn/Article/details/gtqwpczqhw.html

$s =~ s/old/new/g;
来源：http://dali.xinyue.icu/Article/details/gtuptwozax.html

[T49] Perl：函数
来源：http://dali.cdnleiting.top/Article/details/gtiplngzvh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtiyqjuqmr.html

[T50] Perl：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gtgvhlhpki.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gogol.net.cn/Article/details/gtkjwjimfj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.aibaodan.cn/Article/details/gtrqqmpgau.html

[T51] Scala：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxsgypitk.html

println("Hello")
来源：http://dali.zhongyouzk.top/Article/details/gtrwcrplrh.html

[T52] Scala：变量
来源：http://dali.aibaodan.cn/Article/details/gtidierzjp.html

val a = 1;  var b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtupjuduhx.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gtszzahfta.html

s"值: $b"
来源：http://dali.jinqigufen.top/Article/details/gtariixclm.html

[T54] Scala：集合映射
来源：http://dali.hnxiangtu.top/Article/details/gtrnbwjzjh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtutlmybki.html

[T55] Scala：集合过滤
来源：http://dali.yangfankeji.com/Article/details/gtlcsqgsjd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtegxgsbqx.html

[T56] Scala：样例类
来源：http://dali.dianchejie.cn/Article/details/gtjxmupgdp.html

case class User(name: String, age: Int)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtryjrykdy.html

[T57] Scala：模式匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjzhjtxme.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gzhubu.top/Article/details/gtmhnodsns.html

[T58] Scala：函数定义
来源：http://dali.chenjidiqi.icu/Article/details/gtvacwjyyj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cucudq.cn/Article/details/gtxfnalqlq.html

[T59] Scala：循环
来源：http://dali.gotoacloud.top/Article/details/gtkzqumtjy.html

for (i <- 1 to 10) println(i)
来源：http://dali.xuetiantiany.cn/Article/details/gtimqdfhzc.html

[T60] Scala：折叠
来源：http://dali.ybcxt.top/Article/details/gtroxvbajy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xinyue.icu/Article/details/gtxxnnhvaf.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtejuzfics.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gotoacloud.top/Article/details/gtvbmieyzq.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtwcattggg.html

[U01] Py：创建虚拟环境
来源：http://dali.jyoumei.cn/Article/details/gtafjpxacm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cashguo.top/Article/details/gtduacmvwg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.chenzaomai.com/Article/details/gtzgblajgf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yonumen.top/Article/details/gtawchqkpn.html

[U03] Py：加载 .env 配置
来源：http://dali.gzhubu.top/Article/details/gtxnkddbmy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.redwolf501.top/Article/details/gtuxjdcfvz.html

[U04] Py：变量调试打印
来源：http://dali.hammf.cn/Article/details/gtdasbxqib.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.snrcjt.cn/Article/details/gtqvuvwyvq.html

[U05] Py：列表去重且保序
来源：http://dali.nanxinkj.top/Article/details/gthqheyitp.html

list(dict.fromkeys(arr))
来源：http://dali.jlsjyb.cn/Article/details/gttpgqhyxl.html

[U06] Py：合并两个字典
来源：http://dali.xuetiantiany.cn/Article/details/gtkfjpootw.html

{**a, **b}
来源：http://dali.andypj.xyz/Article/details/gtayqjeudt.html

[U07] Py：反转字典键值
来源：http://dali.iojbl.cn/Article/details/gtgwwlmrgc.html

{v: k for k, v in d.items()}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmovwslys.html

[U08] Py：展平二维列表
来源：http://dali.xinyue.icu/Article/details/gtcayasfxw.html

[y for x in nested for y in x]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwirlgfmg.html

[U09] Py：字典取最大值的键
来源：http://dali.hysaishi.cn/Article/details/gtftrfpulb.html

max(d, key=d.get)
来源：http://dali.xinyue.icu/Article/details/gtgzlptbvj.html

[U10] Py：按值排序字典
来源：http://dali.zhengqikj.top/Article/details/gtihkfbckp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yongpay.top/Article/details/gtrwqnuwmo.html

[U11] Py：生成器表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwmbdecmx.html

(x * 2 for x in arr)
来源：http://dali.yuxming.cn/Article/details/gteoallyzw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zycfv.cn/Article/details/gtovmzrlco.html

Counter(arr).most_common(3)
来源：http://dali.yonumen.top/Article/details/gtpivzdqxy.html

[U13] Py：固定长度队列
来源：http://dali.shzxlz.cn/Article/details/gtsxikrbjg.html

deque(maxlen=10)
来源：http://dali.jyoumei.cn/Article/details/gtbkxlregr.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gtqetfarcy.html

defaultdict(list)
来源：http://dali.jinqigufen.top/Article/details/gtfpjteiiu.html

[U15] Py：高精度计时
来源：http://dali.guannengcc.top/Article/details/gtszdjiykf.html

t = time.perf_counter()
来源：http://dali.zhaomingkeji.xyz/Article/details/gteindnyet.html

[U16] Py：命令行参数解析
来源：http://dali.dashuyun.cn/Article/details/gtwxhuuwwz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.redwolf501.top/Article/details/gtriayorzz.html

[U17] Py：初始化日志
来源：http://dali.dashuyun.cn/Article/details/gtubzpmyhi.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ydzc1.top/Article/details/gtcpoevogn.html

[U18] Py：预编译正则
来源：http://dali.chenlongwang.top/Article/details/gtuduexars.html

pat = re.compile(r"\d+")
来源：http://dali.yvedp.cn/Article/details/gtvuriaxzp.html

[U19] Py：正则替换带回调
来源：http://dali.mhx1999.top/Article/details/gtnegzgcgq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zycfv.cn/Article/details/gteawthkus.html

[U20] Py：缓存函数结果
来源：http://dali.gotoacloud.top/Article/details/gtfohbkukr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.nwbrower.top/Article/details/gtmwndtihz.html

[U21] Py：自定义上下文管理器
来源：http://dali.zdqjudy.top/Article/details/gtsqqrqhag.html

@contextlib.contextmanager
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfczfyec.html

[U22] Py：矩阵转置
来源：http://dali.hysaishi.cn/Article/details/gtcvznwoiq.html

list(zip(*m))
来源：http://dali.nanxuanxn.top/Article/details/gtzvtmwkkp.html

[U23] Py：分块读取大文件
来源：http://dali.xuetiantiany.cn/Article/details/gtfefwabpk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zycfv.cn/Article/details/gtlheybnuv.html

[U24] Py：路径操作
来源：http://dali.guowangkeji.top/Article/details/gtasisxvwp.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.gotoacloud.top/Article/details/gttrntwysl.html

[U25] Py：CSV 按字典读
来源：http://dali.316326.xyz/Article/details/gttuyokvsm.html

csv.DictReader(f)
来源：http://dali.ybcxt.top/Article/details/gtiqnomgxu.html

[U26] Py：并发下载
来源：http://dali.cashguo.top/Article/details/gtzguottuo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.fengsongda.top/Article/details/gtxwgdgstr.html

[U27] Py：异步 HTTP
来源：http://dali.tanke756.top/Article/details/gtkgyglxtw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.aibaodan.cn/Article/details/gtnvcykhsg.html

[U28] Py：类型别名
来源：http://dali.zhongyouzk.top/Article/details/gtlwbjoaeb.html

UserId = int
来源：http://dali.vqdsnc.cn/Article/details/gtdhsvaqai.html

[U29] Py：属性校验
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqvypstid.html

@property 与 @x.setter 配合
来源：http://dali.hammf.cn/Article/details/gtcqaothee.html

[U30] Py：数据类
来源：http://dali.xuetiantiany.cn/Article/details/gttgyiekmi.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gteltykzfm.html

[U31] Py：单测
来源：http://dali.hfpthk.cn/Article/details/gthfnnkyqy.html

python -m pytest -q
来源：http://dali.jyoumei.cn/Article/details/gtmdygqfdx.html

[U32] Py：代码格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gtzfoieczx.html

ruff format . && ruff check --fix .
来源：http://dali.hnxiangtu.top/Article/details/gtrtcspiri.html

[U33] Py：打包发布
来源：http://dali.gogol.net.cn/Article/details/gtfaktdbuw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shzxlz.cn/Article/details/gtzageeium.html

[U34] Py：判断编码
来源：http://dali.jianghu66.top/Article/details/gtvkmvvpug.html

chardet.detect(raw)
来源：http://dali.wangdashe.top/Article/details/gtchpqfsks.html


<!-- 参考信息 -->