代发 wailian999

FILE *f = fopen("a.txt", "r");
来源：http://dali.cashguo.top/Article/details/gtxcwpvbkq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yonumen.top/Article/details/gthlvarfoa.html

fclose(f);
来源：http://dali.nanxuanxn.top/Article/details/gtqgdlwxpb.html

[S12] C：写文件
来源：http://dali.cqqwz.cn/Article/details/gtfvwpqhoi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yanxiufei.cn/Article/details/gtebnswmky.html

[S13] C：宏定义
来源：http://dali.yuxming.cn/Article/details/gtltojymxx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shangyingyoupin.top/Article/details/gtduzfaqyn.html

[S14] C：枚举
来源：http://dali.shuidangran.top/Article/details/gtvyxpxqfu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenlongwang.top/Article/details/gtqudkpwjf.html

[S15] C：类型转换
来源：http://dali.shangyingyoupin.top/Article/details/gtivgymvrz.html

(double) a / b
来源：http://dali.yongpay.top/Article/details/gtbzfgrrfa.html

[S16] C：位操作置位
来源：http://dali.jinqigufen.top/Article/details/gthlrxwyom.html

x |= (1 << 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsqavkecy.html

[S17] C：安全拼接字符串
来源：http://dali.shuidangran.top/Article/details/gtidsqtuqx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hysaishi.cn/Article/details/gttvzsodjs.html

[S18] C：命令行参数
来源：http://dali.9152youxi.cn/Article/details/gthfbecead.html

int main(int argc, char **argv)
来源：http://dali.yanxiufei.cn/Article/details/gtnqgcyoxe.html

[S19] C：快速排序
来源：http://dali.nanxuanxn.top/Article/details/gtvpufdpzb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hfpthk.cn/Article/details/gtsnsyphpt.html

[S20] C：二分查找
来源：http://dali.chenlongwang.top/Article/details/gtnhozpjdq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.fengsongda.top/Article/details/gtmbzkryuc.html

[S21] C：字符类别判断
来源：http://dali.yj20258.top/Article/details/gthrwglmls.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nanxuanxn.top/Article/details/gtgwlfrxtb.html

[S22] C：字符串转数字
来源：http://dali.shangyingyoupin.top/Article/details/gtycirhosw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nanxuanxn.top/Article/details/gtieaktmgf.html

[S23] C：随机数
来源：http://dali.zhengqikj.top/Article/details/gtoaowjjmt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cucudq.cn/Article/details/gtajqkfgtc.html

[S24] C：获取本地时间
来源：http://dali.tian-w.cn/Article/details/gthttmfqou.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.dashuyun.cn/Article/details/gtuginwkop.html

[S25] C：内存拷贝
来源：http://dali.sxryk.cn/Article/details/gtqdaaelwe.html

memcpy(dst, src, n);
来源：http://dali.yuanzhike.top/Article/details/gtdfuxpqfy.html

[S26] C：内存清零
来源：http://dali.sufxvd.cn/Article/details/gtlrnkcbun.html

memset(a, 0, sizeof a);
来源：http://dali.guowangkeji.top/Article/details/gtkdcrobsq.html

[S27] C：定义常量
来源：http://dali.yj202588.top/Article/details/gteicobraw.html

const double PI = 3.14159;
来源：http://dali.ivvv.top/Article/details/gtsorsfdff.html

[S28] C：静态变量
来源：http://dali.yangfankeji.com/Article/details/gtgdnotfil.html

static int counter = 0;
来源：http://dali.daxiang520.top/Article/details/gtacnjtupz.html

[S29] C：变参函数
来源：http://dali.jqgufenzy.top/Article/details/gtjaopctor.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yanxiufei.cn/Article/details/gtjqyclwsk.html

[S30] C：头文件保护
来源：http://dali.smart0.xyz/Article/details/gtovxfjskv.html

#ifndef X_H
来源：http://dali.ybcxt.top/Article/details/gtgjywemki.html

#define X_H
来源：http://dali.dianchejie.cn/Article/details/gtbhkpvlpc.html

#endif
来源：http://dali.birdmap.top/Article/details/gtbxiwizav.html

[S31] C++：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtsqkafsoo.html

#include <iostream>
来源：http://dali.jianghu66.top/Article/details/gtokzkdcka.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yueranfly.top/Article/details/gtwtxplnnx.html

[S32] C++：字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtstnhqabr.html

std::string s = "hi";  s += "!";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyhraumor.html

[S33] C++：vector 增删
来源：http://dali.smart0.xyz/Article/details/gtpgodbhvt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.snrcjt.cn/Article/details/gtidzahous.html

[S34] C++：遍历 vector
来源：http://dali.yonumen.top/Article/details/gtdpvnrmhs.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jiagoushi.top/Article/details/gtzfpgfxop.html

[S35] C++：map
来源：http://dali.ybcxt.top/Article/details/gtuucwmqld.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.316326.xyz/Article/details/gtqdxkiixr.html

[S36] C++：unordered_map
来源：http://dali.zhengqikj.top/Article/details/gtpyaafqbh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj202588.top/Article/details/gtqgvxifau.html

[S37] C++：set
来源：http://dali.yongpay.top/Article/details/gtwdzucaim.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.aibaodan.cn/Article/details/gtnihxfewm.html

[S38] C++：排序
来源：http://dali.zdqjudy.top/Article/details/gtcdaymetv.html

std::sort(v.begin(), v.end());
来源：http://dali.ehwqpu.com/Article/details/gtxztqsqrk.html

[S39] C++：自定义比较器排序
来源：http://dali.fzhhl.top/Article/details/gtzpgrpybf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xinyue.icu/Article/details/gtilitlayw.html

[S40] C++：查找元素
来源：http://dali.jyoumei.cn/Article/details/gtwtjqkqvh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.haohaochexian.top/Article/details/gtlaciodpi.html

[S41] C++：类与构造函数
来源：http://dali.hfpthk.cn/Article/details/gtvtggkyxj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jqgfzy.top/Article/details/gtobgrjrrk.html

[S42] C++：继承与虚函数
来源：http://dali.xuetiantiany.cn/Article/details/gtuuhotejc.html

class B : public Base { public: void f() override {} };
来源：http://dali.ydzc1.top/Article/details/gtzjjvfjym.html

[S43] C++：智能指针
来源：http://dali.yuanzhike.top/Article/details/gtqnsubkcw.html

auto p = std::make_unique<int>(5);
来源：http://dali.fzhhl.top/Article/details/gtpnzxmaak.html

[S44] C++：引用传参
来源：http://dali.jqgfzy.top/Article/details/gtsglapkft.html

void inc(int &x) { ++x; }
来源：http://dali.nanxuanxn.top/Article/details/gtixbrxrgb.html

[S45] C++：lambda
来源：http://dali.svipenyu.cn/Article/details/gtifyvbsei.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhongyouzk.top/Article/details/gtazjcjnzn.html

[S46] C++：函数模板
来源：http://dali.yongpay.top/Article/details/gtiyxtvdme.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.haohaochexian.top/Article/details/gtaovuammq.html

[S47] C++：结构化绑定遍历
来源：http://dali.vqdsnc.cn/Article/details/gtulxblwab.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.nanxuanxn.top/Article/details/gtcrfzbbkg.html

[S48] C++：逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gtrbbetghx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xuanzx.com/Article/details/gtitotzjpc.html

while (std::getline(in, line)) { }
来源：http://dali.zycfv.cn/Article/details/gtpoouclxl.html

[S49] C++：写文件
来源：http://dali.smart0.xyz/Article/details/gtwsvpcjbz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yvedp.cn/Article/details/gtbczketkq.html

[S50] C++：格式化数字
来源：http://dali.hnqzz.top/Article/details/gtsaucuaql.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.redwolf501.top/Article/details/gtqhhftlvt.html

[S51] C++：显式类型转换
来源：http://dali.ydzc1.top/Article/details/gtkclkopnd.html

static_cast<double>(a) / b
来源：http://dali.hammf.cn/Article/details/gtpfptgoom.html

[S52] C++：const 与 noexcept
来源：http://dali.fzhhl.top/Article/details/gtcemppyjz.html

int size() const noexcept { return n_; }
来源：http://dali.jqgfzy.top/Article/details/gtdycmoxit.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gttemjzeif.html

std::vector<int> w = std::move(v);
来源：http://dali.zdqjudy.top/Article/details/gtmbvanlyn.html

[S54] C++：异常处理
来源：http://dali.wangdashe.top/Article/details/gtaidrajfe.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.c1oappe.top/Article/details/gtrxfytqam.html

[S55] C++：结构化绑定
来源：http://dali.hywenlv.cn/Article/details/gtgkyxrrao.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cheryme.top/Article/details/gtyaizetfq.html

[S56] C++：optional
来源：http://dali.bjfxy.top/Article/details/gthrygnfmh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hysaishi.cn/Article/details/gtolefyydr.html

[S57] C++：编译期常量
来源：http://dali.hnxiangtu.top/Article/details/gtyiinsvqy.html

constexpr int N = 10;
来源：http://dali.ivvv.top/Article/details/gtfaojfvbg.html

[S58] C++：命名空间
来源：http://dali.zhiwuduotai.top/Article/details/gtqeivqniv.html

namespace ns { int f() { return 1; } }
来源：http://dali.9152youxi.cn/Article/details/gtgwttxszw.html

[S59] C++：静态断言
来源：http://dali.zhongyouzk.top/Article/details/gtjqhplqlb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.guowangkeji.top/Article/details/gtaftwcmoz.html

[S60] C++：遍历并删除元素
来源：http://dali.jinqigufen.top/Article/details/gttaojiifg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sufxvd.cn/Article/details/gtyoloriut.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtrdfymmre.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gogol.net.cn/Article/details/gtimcnxmro.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtxdupjxve.html

[T01] Kotlin：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnbipjanh.html

println("Hello")
来源：http://dali.cashguo.top/Article/details/gtwqiqwukl.html

[T02] Kotlin：变量
来源：http://dali.zhoulong.xyz/Article/details/gtrtpqrvoa.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.birdmap.top/Article/details/gtsgecicxs.html

[T03] Kotlin：字符串模板
来源：http://dali.shanyushiyangkeji.top/Article/details/gttepsurvj.html

"值: $b"
来源：http://dali.shanyushiyangtech.top/Article/details/gtudpjbhvy.html

[T04] Kotlin：空安全
来源：http://dali.guannengcc.top/Article/details/gtlkyimvvw.html

val n: String? = null;  n?.length
来源：http://dali.guannengcc.top/Article/details/gtdclmndty.html

[T05] Kotlin：when 表达式
来源：http://dali.ydzc1.top/Article/details/gtpqpzadld.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.meibo888.top/Article/details/gtyhcpexgj.html

[T06] Kotlin：集合映射
来源：http://dali.cucudq.cn/Article/details/gttsgjgpmg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yj20258.top/Article/details/gtolhtpbbd.html

[T07] Kotlin：集合过滤
来源：http://dali.jiagoushi.top/Article/details/gtprkoordu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gzhubu.top/Article/details/gtxwpwslxn.html

[T08] Kotlin：数据类
来源：http://dali.jqgufenzy.top/Article/details/gtxhuccujh.html

data class User(val name: String, val age: Int)
来源：http://dali.meibo888.top/Article/details/gthtbwwubg.html

[T09] Kotlin：扩展函数
来源：http://dali.chenzaomai.com/Article/details/gtbuxoglss.html

fun String.exclaim() = this + "!"
来源：http://dali.kuanghao11.cn/Article/details/gthlghqarz.html

[T10] Kotlin：默认参数
来源：http://dali.snrcjt.cn/Article/details/gtayhwfldw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.iojbl.cn/Article/details/gtogggtcpt.html

[T11] Kotlin：协程
来源：http://dali.haohaochexian.top/Article/details/gtncfrjjzx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.nwbrower.top/Article/details/gttlkhkfuj.html

[T12] Kotlin：解构声明
来源：http://dali.birdmap.top/Article/details/gtadtxvkra.html

val (a, b) = Pair(1, 2)
来源：http://dali.yueranfly.top/Article/details/gtmytspswj.html

[T13] Kotlin：只读 Map
来源：http://dali.sxryk.cn/Article/details/gtcsdgaiub.html

val m = mapOf("a" to 1)
来源：http://dali.c1oappe.top/Article/details/gtpruvhfnp.html

[T14] Kotlin：循环
来源：http://dali.hnxiangtu.top/Article/details/gthwhicbdt.html

for (i in 1..10) println(i)
来源：http://dali.nanxuanxn.top/Article/details/gtlzfpflos.html

[T15] Kotlin：接口
来源：http://dali.kuanghao11.cn/Article/details/gtjoasmtmh.html

interface Shape { fun area(): Double }
来源：http://dali.yuanzhike.top/Article/details/gtcvayqiiv.html

[T16] Swift：Hello World
来源：http://dali.xziqi.cn/Article/details/gtyvbafqzk.html

print("Hello")
来源：http://dali.zhixingplan.top/Article/details/gtfivmpxyc.html

[T17] Swift：变量与常量
来源：http://dali.jqgfzy.top/Article/details/gtydcjnxpv.html

var a = 1;  let b = 2
来源：http://dali.gotoacloud.top/Article/details/gtexhidllj.html

[T18] Swift：字符串插值
来源：http://dali.guannengcc.top/Article/details/gtuzlkqkvd.html

"值: \(b)"
来源：http://dali.cheryme.top/Article/details/gtukoeexch.html

[T19] Swift：可选绑定
来源：http://dali.fzhhl.top/Article/details/gtwzqrxzbo.html

if let n = opt { print(n) }
来源：http://dali.smart0.xyz/Article/details/gtmzvzwqki.html

[T20] Swift：数组操作
来源：http://dali.shuidangran.top/Article/details/gtsvdagbhj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.c1oappe.top/Article/details/gtgretsaya.html

[T21] Swift：遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gthkpdtter.html

for x in a { print(x) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzhvqfsbx.html

[T22] Swift：字典
来源：http://dali.jinqigfzy.top/Article/details/gtqclqmmif.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.vqdsnc.cn/Article/details/gtordplaik.html

[T23] Swift：函数
来源：http://dali.yongpay.top/Article/details/gtvgnscdnf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gzhubu.top/Article/details/gtfebcuezm.html

[T24] Swift：闭包
来源：http://dali.yj20258888.top/Article/details/gtodkcnajc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.c1oappe.top/Article/details/gtrrpwkuyw.html

[T25] Swift：结构体
来源：http://dali.smart0.xyz/Article/details/gtcysymshj.html

struct P { var x: Int }
来源：http://dali.zdqjudy.top/Article/details/gtmwunoiex.html

[T26] Swift：类与重写
来源：http://dali.wangdashe.top/Article/details/gtilabjnny.html

class A: Base { override func f() {} }
来源：http://dali.xziqi.cn/Article/details/gtdvpdkmwi.html

[T27] Swift：错误处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtwqbjtoxi.html

do { try f() } catch { print(error) }
来源：http://dali.jyoumei.cn/Article/details/gtrjtxktmy.html

[T28] Swift：枚举
来源：http://dali.ybcxt.top/Article/details/gtgmyncavx.html

enum Color { case red, green }
来源：http://dali.nanxinkj.top/Article/details/gtrsjfgkkj.html

[T29] Swift：guard 提前返回
来源：http://dali.yangfankeji.com/Article/details/gtdndyrlth.html

guard let x = opt else { return }
来源：http://dali.sweek.top/Article/details/gtbgfuwnyp.html

[T30] Swift：协议
来源：http://dali.jianghu66.top/Article/details/gtpsocwjuy.html

protocol Shape { func area() -> Double }
来源：http://dali.sufxvd.cn/Article/details/gtvggdrptv.html

[T31] Lua：Hello World
来源：http://dali.hnqzz.top/Article/details/gtqrjbgkid.html

print("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gtfqusiiqt.html

[T32] Lua：局部变量
来源：http://dali.zhixingplan.top/Article/details/gtdcerltnf.html

local a = 1
来源：http://dali.guowangkeji.top/Article/details/gtwqsrzuql.html

[T33] Lua：表（数组）
来源：http://dali.cucudq.cn/Article/details/gtcxuuvzne.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gtzlvrjytz.html

[T34] Lua：遍历表
来源：http://dali.zdqjudy.top/Article/details/gtegyywkzo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.wangdashe.top/Article/details/gtpuykzdso.html

[T35] Lua：字典表
来源：http://dali.yongpay.top/Article/details/gtcqhxifsg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ydzc1.top/Article/details/gtegeiaimb.html

[T36] Lua：函数
来源：http://dali.guannengcc.top/Article/details/gtiklkobse.html

function add(a, b) return a + b end
来源：http://dali.zhoulong.xyz/Article/details/gtjojommet.html

[T37] Lua：字符串拼接
来源：http://dali.jinqigfzy.top/Article/details/gtuucklzya.html

"a" .. "b"
来源：http://dali.sxryk.cn/Article/details/gtnqopsiza.html

[T38] Lua：条件
来源：http://dali.fengsongda.top/Article/details/gtgewdtnbo.html

if x > 0 then print("正") end
来源：http://dali.shanyushiyangtech.top/Article/details/gturdffugu.html

[T39] Lua：模式匹配
来源：http://dali.tanke756.top/Article/details/gtpmttyxfl.html

string.find(s, "%d+")
来源：http://dali.nanxuanxn.top/Article/details/gtybarirsx.html

[T40] Lua：元表
来源：http://dali.yvedp.cn/Article/details/gttpmyuthr.html

setmetatable({}, { __index = base })
来源：http://dali.jinqigfzy.top/Article/details/gtklcwxgbn.html

[T41] Perl：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtooejmmlr.html

print "Hello\n";
来源：http://dali.zdqjudy.top/Article/details/gtsfysxkjg.html

[T42] Perl：变量类型
来源：http://dali.hysaishi.cn/Article/details/gtevqruqum.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.andypj.xyz/Article/details/gtzccprzah.html

[T43] Perl：字符串插值
来源：http://dali.ehwqpu.com/Article/details/gtxegmygfs.html

"值: $a"
来源：http://dali.shangyingyoupin.top/Article/details/gtqyqqqwlb.html

[T44] Perl：条件
来源：http://dali.dianchejie.cn/Article/details/gtclnylggs.html

if ($a > 0) { print "正"; }
来源：http://dali.zhixingplan.top/Article/details/gtrsqkbsup.html

[T45] Perl：数组遍历
来源：http://dali.nanxinkj.top/Article/details/gtqyutpqsd.html

for my $x (@arr) { print $x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gteawwzbof.html

[T46] Perl：哈希操作
来源：http://dali.ehwqpu.com/Article/details/gtsftcjsco.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.nanxinkj.top/Article/details/gtscogtccx.html

[T47] Perl：正则捕获
来源：http://dali.hysaishi.cn/Article/details/gttsizvqfp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.0kj1m.cn/Article/details/gtrobzcdqi.html

[T48] Perl：正则替换
来源：http://dali.c1oappe.top/Article/details/gtjshtpwxk.html

$s =~ s/old/new/g;
来源：http://dali.yueranfly.top/Article/details/gtvxlaahga.html

[T49] Perl：函数
来源：http://dali.shzxlz.cn/Article/details/gtxwppxwpl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gtspftzdae.html

[T50] Perl：逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gtsuhgxbde.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hywenlv.cn/Article/details/gtugliljsi.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhongyouzk.top/Article/details/gtovzhxfpl.html

[T51] Scala：Hello World
来源：http://dali.ivvv.top/Article/details/gtqlzqixaa.html

println("Hello")
来源：http://dali.yj202588.top/Article/details/gtlbrubrzy.html

[T52] Scala：变量
来源：http://dali.wangdashe.top/Article/details/gtbwkpuutm.html

val a = 1;  var b = 2
来源：http://dali.bjfxy.top/Article/details/gtvrauoweo.html

[T53] Scala：字符串插值
来源：http://dali.chenlongwang.top/Article/details/gtdortgjut.html

s"值: $b"
来源：http://dali.shanyushiyangtech.top/Article/details/gtppfxvqfa.html

[T54] Scala：集合映射
来源：http://dali.ivvv.top/Article/details/gtwlryekea.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jqgufenzy.top/Article/details/gtywwizeqg.html

[T55] Scala：集合过滤
来源：http://dali.zhengqikj.top/Article/details/gthjohzuyr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.meibo888.top/Article/details/gtmokkrlqe.html

[T56] Scala：样例类
来源：http://dali.nanxuanxn.top/Article/details/gtutrmnkak.html

case class User(name: String, age: Int)
来源：http://dali.sysykeji.top/Article/details/gtyhlfjnbb.html

[T57] Scala：模式匹配
来源：http://dali.yj20258.top/Article/details/gtabckuski.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shuidangran.top/Article/details/gtqjngqhox.html

[T58] Scala：函数定义
来源：http://dali.cdnleiting.top/Article/details/gtiniittgo.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cheryme.top/Article/details/gtlrjiipau.html

[T59] Scala：循环
来源：http://dali.sysykeji.top/Article/details/gtcpvkgjqi.html

for (i <- 1 to 10) println(i)
来源：http://dali.nanxuanxn.top/Article/details/gtqdoxgkvu.html

[T60] Scala：折叠
来源：http://dali.guowangkeji.top/Article/details/gtxgapqogt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.daria6918.cn/Article/details/gtenuavwsz.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtvqngoywg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhoulong.xyz/Article/details/gtetxhmkta.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttagldyms.html

[U01] Py：创建虚拟环境
来源：http://dali.yanxiufei.cn/Article/details/gtwaihebzp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.svipenyu.cn/Article/details/gtyisdlpxr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hnxiangtu.top/Article/details/gtyqvvtaky.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.fengsongda.top/Article/details/gtkfpfskcc.html

[U03] Py：加载 .env 配置
来源：http://dali.jinqigfzy.top/Article/details/gtirvrcdyx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jinqigufen.top/Article/details/gtucxlgtbb.html

[U04] Py：变量调试打印
来源：http://dali.ivvv.top/Article/details/gtxulwoveb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ehwqpu.com/Article/details/gtxymwfzlf.html

[U05] Py：列表去重且保序
来源：http://dali.jinqigufen.top/Article/details/gtghlkekxf.html

list(dict.fromkeys(arr))
来源：http://dali.ydzc1.top/Article/details/gtbqrysmpd.html

[U06] Py：合并两个字典
来源：http://dali.yuanzhike.top/Article/details/gtpjjajbku.html

{**a, **b}
来源：http://dali.havefunace.top/Article/details/gtwmrzcsrb.html

[U07] Py：反转字典键值
来源：http://dali.yuxming.cn/Article/details/gtkmuwkqqk.html

{v: k for k, v in d.items()}
来源：http://dali.zhiwuduotai.top/Article/details/gtsakigcka.html

[U08] Py：展平二维列表
来源：http://dali.zhongyouzk.top/Article/details/gtravxbaqt.html

[y for x in nested for y in x]
来源：http://dali.ppjwa.cn/Article/details/gtjhsrumbd.html

[U09] Py：字典取最大值的键
来源：http://dali.tianlin.xyz/Article/details/gtxplhbpks.html

max(d, key=d.get)
来源：http://dali.xziqi.cn/Article/details/gttlvothlg.html

[U10] Py：按值排序字典
来源：http://dali.tian-w.cn/Article/details/gthkvvxokp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sufxvd.cn/Article/details/gtuziueyle.html

[U11] Py：生成器表达式
来源：http://dali.cqqwz.cn/Article/details/gtuhtsiakz.html

(x * 2 for x in arr)
来源：http://dali.jianghu66.top/Article/details/gtjiauzqng.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gogol.net.cn/Article/details/gthngxojot.html

Counter(arr).most_common(3)
来源：http://dali.sysykeji.top/Article/details/gtiulflrkb.html

[U13] Py：固定长度队列
来源：http://dali.jinqigufen.top/Article/details/gtfkizryfb.html

deque(maxlen=10)
来源：http://dali.shuidangran.top/Article/details/gtrndokjdy.html

[U14] Py：分组收集到列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteyeukrdj.html

defaultdict(list)
来源：http://dali.bjfxy.top/Article/details/gtdjmydzvd.html

[U15] Py：高精度计时
来源：http://dali.ivvv.top/Article/details/gtfhtdaljv.html

t = time.perf_counter()
来源：http://dali.yonumen.top/Article/details/gtpjipxess.html

[U16] Py：命令行参数解析
来源：http://dali.cucudq.cn/Article/details/gtnzofieaq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.sweek.top/Article/details/gtaqyvkcdx.html

[U17] Py：初始化日志
来源：http://dali.hfpthk.cn/Article/details/gtsxxoawfn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.pengpengdd.cyou/Article/details/gtdxhbewyj.html

[U18] Py：预编译正则
来源：http://dali.hammf.cn/Article/details/gtprcktkib.html

pat = re.compile(r"\d+")
来源：http://dali.gogol.net.cn/Article/details/gtixlhljmc.html

[U19] Py：正则替换带回调
来源：http://dali.zhixingplan.top/Article/details/gtzzutiebl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yangfankeji.com/Article/details/gtrirlqfpw.html

[U20] Py：缓存函数结果
来源：http://dali.cheryme.top/Article/details/gtqnpdvclc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.guannengcc.top/Article/details/gtwmgxmnqr.html

[U21] Py：自定义上下文管理器
来源：http://dali.sysykeji.top/Article/details/gthrmfnmtw.html

@contextlib.contextmanager
来源：http://dali.pycfn.com/Article/details/gttunhusvh.html

[U22] Py：矩阵转置
来源：http://dali.zdqjudy.top/Article/details/gtdcricuwz.html

list(zip(*m))
来源：http://dali.haohaochexian.top/Article/details/gtzpewvzra.html

[U23] Py：分块读取大文件
来源：http://dali.sweek.top/Article/details/gthjfrzaal.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hongshengwenyu.top/Article/details/gttfcgsprp.html

[U24] Py：路径操作
来源：http://dali.quarkkingdee.top/Article/details/gtdxhifppn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jinqigfzy.top/Article/details/gtwudnoqoi.html

[U25] Py：CSV 按字典读
来源：http://dali.bjfxy.top/Article/details/gtbdolduvx.html

csv.DictReader(f)
来源：http://dali.sxryk.cn/Article/details/gtdpfzvzio.html

[U26] Py：并发下载
来源：http://dali.xuanzx.com/Article/details/gtgeanehyi.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jiagoushi.top/Article/details/gtnqelqdgv.html

[U27] Py：异步 HTTP
来源：http://dali.yonumen.top/Article/details/gthlzeiaex.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxnavkry.html

[U28] Py：类型别名
来源：http://dali.smart0.xyz/Article/details/gtbjsdjmuv.html

UserId = int
来源：http://dali.shzxlz.cn/Article/details/gtuxvxuaog.html

[U29] Py：属性校验
来源：http://dali.yj20258.top/Article/details/gtxiqsekal.html

@property 与 @x.setter 配合
来源：http://dali.yj20258888.top/Article/details/gtszlymacl.html

[U30] Py：数据类
来源：http://dali.yangfankeji.com/Article/details/gtvfnryfsc.html

@dataclass(slots=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttztbaeau.html

[U31] Py：单测
来源：http://dali.feifeiyinyue.top/Article/details/gttszsbrmh.html

python -m pytest -q
来源：http://dali.jqgfzy.top/Article/details/gtdwyywdsq.html

[U32] Py：代码格式化
来源：http://dali.tianlin.xyz/Article/details/gtbifulkdh.html

ruff format . && ruff check --fix .
来源：http://dali.cheryme.top/Article/details/gtxyvysmxz.html

[U33] Py：打包发布
来源：http://dali.shangyingyoupin.top/Article/details/gtsieletjg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.gotoacloud.top/Article/details/gtnbrwcukk.html

[U34] Py：判断编码
来源：http://dali.daria6918.cn/Article/details/gtcugfkhsw.html

chardet.detect(raw)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtorwpjrow.html


<!-- 参考信息 -->