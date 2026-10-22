代发 wailian999

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenzaomai.com/Article/details/gtudviinqi.html

[S08] C：动态内存分配与释放
来源：http://dali.yonumen.top/Article/details/gtgxejegxv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xuetiantiany.cn/Article/details/gtxuqcxamn.html

[S09] C：结构体定义与初始化
来源：http://dali.sysykeji.top/Article/details/gtbrcpowas.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.havefunace.top/Article/details/gtjlmrcdsq.html

[S10] C：指针与解引用
来源：http://dali.zhiwuduotai.top/Article/details/gtjtayyjtp.html

int *p = &a;  *p = 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfpbbzhkt.html

[S11] C：逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gtypbdrrpr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tianlin.xyz/Article/details/gtmixbxbcc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.tanke756.top/Article/details/gtyqrcloat.html

fclose(f);
来源：http://dali.haohaochexian.top/Article/details/gtdzedgntk.html

[S12] C：写文件
来源：http://dali.jqgufenzy.top/Article/details/gtbrgeqjxi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xuetiantiany.cn/Article/details/gtdlwifjrf.html

[S13] C：宏定义
来源：http://dali.ppjwa.cn/Article/details/gtlzsuwiau.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xinyue.icu/Article/details/gtoqsfompa.html

[S14] C：枚举
来源：http://dali.gogol.net.cn/Article/details/gtgykdrsvj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yangfankeji.com/Article/details/gtrunzlsyg.html

[S15] C：类型转换
来源：http://dali.gogol.net.cn/Article/details/gtqwnxvkcm.html

(double) a / b
来源：http://dali.mhx1999.top/Article/details/gtfevtupfq.html

[S16] C：位操作置位
来源：http://dali.guannengcc.top/Article/details/gtpammtxpp.html

x |= (1 << 3);
来源：http://dali.yj20258888.top/Article/details/gttnlhslnf.html

[S17] C：安全拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gtpwuzcbpq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nwbrower.top/Article/details/gttljhzrta.html

[S18] C：命令行参数
来源：http://dali.chenzaomai.com/Article/details/gtpupvvxri.html

int main(int argc, char **argv)
来源：http://dali.jianghu66.top/Article/details/gtnrabesvm.html

[S19] C：快速排序
来源：http://dali.pycfn.com/Article/details/gtkueoawpi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenlongwang.top/Article/details/gtuwducduo.html

[S20] C：二分查找
来源：http://dali.redwolf501.top/Article/details/gthdimnxmy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nwbrower.top/Article/details/gtqpmxrvhk.html

[S21] C：字符类别判断
来源：http://dali.wangshuangyany.cn/Article/details/gtyplrlyct.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yuxming.cn/Article/details/gtqtwiwggw.html

[S22] C：字符串转数字
来源：http://dali.hammf.cn/Article/details/gthkkvsxst.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yuxming.cn/Article/details/gtdvhisdqd.html

[S23] C：随机数
来源：http://dali.jinqigufen.top/Article/details/gtbtvlddbq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hongshengwenyu.top/Article/details/gtjgammuiv.html

[S24] C：获取本地时间
来源：http://dali.hfpthk.cn/Article/details/gtxqzxwibx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.vqdsnc.cn/Article/details/gtinscpdfk.html

[S25] C：内存拷贝
来源：http://dali.yangfankeji.com/Article/details/gtguedlsap.html

memcpy(dst, src, n);
来源：http://dali.quarkkingdee.top/Article/details/gtewrohbse.html

[S26] C：内存清零
来源：http://dali.jianghu66.top/Article/details/gtzmsrdfbi.html

memset(a, 0, sizeof a);
来源：http://dali.fengsongda.top/Article/details/gtxyxhnssm.html

[S27] C：定义常量
来源：http://dali.zhixingplan.top/Article/details/gtyukruwbs.html

const double PI = 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gtjjxhcdiy.html

[S28] C：静态变量
来源：http://dali.nanxuanxn.top/Article/details/gtukocwlmo.html

static int counter = 0;
来源：http://dali.gotoacloud.top/Article/details/gtxoavddac.html

[S29] C：变参函数
来源：http://dali.kuanghao11.cn/Article/details/gtcrqivrlm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.daria6918.cn/Article/details/gttdphttfu.html

[S30] C：头文件保护
来源：http://dali.jqgfzy.top/Article/details/gtocemivuy.html

#ifndef X_H
来源：http://dali.jinqigfzy.top/Article/details/gtqgdyhkkw.html

#define X_H
来源：http://dali.sufxvd.cn/Article/details/gtsiyidrpm.html

#endif
来源：http://dali.hammf.cn/Article/details/gtmxvclikc.html

[S31] C++：Hello World
来源：http://dali.tian-w.cn/Article/details/gtiatqawbn.html

#include <iostream>
来源：http://dali.zhiwuduotai.top/Article/details/gttcvtsobf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jlsjyb.cn/Article/details/gtfiesbzgs.html

[S32] C++：字符串
来源：http://dali.jiagoushi.top/Article/details/gtaidpcedj.html

std::string s = "hi";  s += "!";
来源：http://dali.yj20258888.top/Article/details/gtrahdlbay.html

[S33] C++：vector 增删
来源：http://dali.quarkkingdee.top/Article/details/gtpsowjkdu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hnqzz.top/Article/details/gthaeaknxp.html

[S34] C++：遍历 vector
来源：http://dali.nwbrower.top/Article/details/gtkdfuvjoy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zycfv.cn/Article/details/gtfzdxjmxj.html

[S35] C++：map
来源：http://dali.nanxuanxn.top/Article/details/gtggvkzcaz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtsbxzulbf.html

[S36] C++：unordered_map
来源：http://dali.hnqzz.top/Article/details/gtxzsplyvg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.andypj.xyz/Article/details/gtxykgjoxu.html

[S37] C++：set
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqiwwshu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj202588.top/Article/details/gtgtreqeho.html

[S38] C++：排序
来源：http://dali.ybcxt.top/Article/details/gtmecclbxj.html

std::sort(v.begin(), v.end());
来源：http://dali.xuanzx.com/Article/details/gtmvofdgff.html

[S39] C++：自定义比较器排序
来源：http://dali.tian-w.cn/Article/details/gtdywafspn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.bjfxy.top/Article/details/gtksikwfjm.html

[S40] C++：查找元素
来源：http://dali.yanxiufei.cn/Article/details/gtyvptnfxf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.dashuyun.cn/Article/details/gttiergfbi.html

[S41] C++：类与构造函数
来源：http://dali.ppjwa.cn/Article/details/gtfklaandj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuielhrwr.html

[S42] C++：继承与虚函数
来源：http://dali.zhengqikj.top/Article/details/gtaptdhsol.html

class B : public Base { public: void f() override {} };
来源：http://dali.tianlin.xyz/Article/details/gtoivlrdio.html

[S43] C++：智能指针
来源：http://dali.hywenlv.cn/Article/details/gtxrjhlsak.html

auto p = std::make_unique<int>(5);
来源：http://dali.jiagoushi.top/Article/details/gtfvffpdiv.html

[S44] C++：引用传参
来源：http://dali.zhiwuduotai.top/Article/details/gtstsbrtjc.html

void inc(int &x) { ++x; }
来源：http://dali.cashguo.top/Article/details/gtfynewwnt.html

[S45] C++：lambda
来源：http://dali.guannengcc.top/Article/details/gtpoilwgkk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hnqzz.top/Article/details/gttqvakxth.html

[S46] C++：函数模板
来源：http://dali.yanxiufei.cn/Article/details/gtkdlwzgby.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xinyue.icu/Article/details/gtkrvwuvij.html

[S47] C++：结构化绑定遍历
来源：http://dali.jiagoushi.top/Article/details/gtqrpfuaum.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.316326.xyz/Article/details/gttyareqlm.html

[S48] C++：逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gtqugybmdx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.mhx1999.top/Article/details/gtqziptldk.html

while (std::getline(in, line)) { }
来源：http://dali.kuanghao11.cn/Article/details/gtnqrnqjwg.html

[S49] C++：写文件
来源：http://dali.fengsongda.top/Article/details/gtkmybpqms.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj20258.top/Article/details/gtcxsoihzk.html

[S50] C++：格式化数字
来源：http://dali.hnqzz.top/Article/details/gtodfgcjpm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sysykeji.top/Article/details/gtzayqihzr.html

[S51] C++：显式类型转换
来源：http://dali.guannengcc.top/Article/details/gtfvlooiiw.html

static_cast<double>(a) / b
来源：http://dali.cucudq.cn/Article/details/gtclvfmhtm.html

[S52] C++：const 与 noexcept
来源：http://dali.sweek.top/Article/details/gtppyvykja.html

int size() const noexcept { return n_; }
来源：http://dali.wangdashe.top/Article/details/gtdcglqcov.html

[S53] C++：移动语义
来源：http://dali.xuanzx.com/Article/details/gttqkgwkrs.html

std::vector<int> w = std::move(v);
来源：http://dali.meibo888.top/Article/details/gtexznnurp.html

[S54] C++：异常处理
来源：http://dali.wangdashe.top/Article/details/gtlxesptfl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jyoumei.cn/Article/details/gtxmurgpts.html

[S55] C++：结构化绑定
来源：http://dali.ppjwa.cn/Article/details/gtdxorwyyt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj20258888.top/Article/details/gtezibbkvc.html

[S56] C++：optional
来源：http://dali.zhixingplan.top/Article/details/gtwdikrwgb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ivvv.top/Article/details/gtxsytqltq.html

[S57] C++：编译期常量
来源：http://dali.andypj.xyz/Article/details/gtrdfyycmg.html

constexpr int N = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gtmtkgigpv.html

[S58] C++：命名空间
来源：http://dali.jinqigufen.top/Article/details/gtrbosytae.html

namespace ns { int f() { return 1; } }
来源：http://dali.haohaochexian.top/Article/details/gtdcnwfjkw.html

[S59] C++：静态断言
来源：http://dali.yueranfly.top/Article/details/gtjuvrdkgl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.aizwys.cn/Article/details/gtapyiolbg.html

[S60] C++：遍历并删除元素
来源：http://dali.pengpengdd.cyou/Article/details/gtiwvrcmfq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.pycfn.com/Article/details/gttcgyzoxd.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtcjiibnif.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xinyue.icu/Article/details/gtnjwlunqr.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtnuimshxm.html

[T01] Kotlin：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtfpyqfqhq.html

println("Hello")
来源：http://dali.meibo888.top/Article/details/gtsknjssoh.html

[T02] Kotlin：变量
来源：http://dali.kuanghao11.cn/Article/details/gtxzccgqhv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yangfankeji.com/Article/details/gtovglsjtx.html

[T03] Kotlin：字符串模板
来源：http://dali.xuanzx.com/Article/details/gtegkedylc.html

"值: $b"
来源：http://dali.jianghu66.top/Article/details/gtfeztwdar.html

[T04] Kotlin：空安全
来源：http://dali.shanyushiyangkeji.top/Article/details/gteplfvccc.html

val n: String? = null;  n?.length
来源：http://dali.cucudq.cn/Article/details/gtrexawtno.html

[T05] Kotlin：when 表达式
来源：http://dali.yongpay.top/Article/details/gteeenkyon.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtazokbjma.html

[T06] Kotlin：集合映射
来源：http://dali.mhx1999.top/Article/details/gthdvufpfb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenzaomai.com/Article/details/gtmmwccewh.html

[T07] Kotlin：集合过滤
来源：http://dali.cheryme.top/Article/details/gtabychddn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yvedp.cn/Article/details/gtcuifwwbb.html

[T08] Kotlin：数据类
来源：http://dali.yangfankeji.com/Article/details/gtfoqpdfra.html

data class User(val name: String, val age: Int)
来源：http://dali.shzxlz.cn/Article/details/gtnxoxdrgn.html

[T09] Kotlin：扩展函数
来源：http://dali.sufxvd.cn/Article/details/gtefumqyvv.html

fun String.exclaim() = this + "!"
来源：http://dali.smart0.xyz/Article/details/gtkcadqmyx.html

[T10] Kotlin：默认参数
来源：http://dali.9152youxi.cn/Article/details/gtptuijyst.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj20258.top/Article/details/gtqbyncfqq.html

[T11] Kotlin：协程
来源：http://dali.hnqzz.top/Article/details/gtcjvptwlh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.aibaodan.cn/Article/details/gtuamzeleq.html

[T12] Kotlin：解构声明
来源：http://dali.aizwys.cn/Article/details/gtzlzsqqmh.html

val (a, b) = Pair(1, 2)
来源：http://dali.yj20258.top/Article/details/gtyjwhrfmj.html

[T13] Kotlin：只读 Map
来源：http://dali.sysykeji.top/Article/details/gtdbdijsjo.html

val m = mapOf("a" to 1)
来源：http://dali.sufxvd.cn/Article/details/gtjfzathqp.html

[T14] Kotlin：循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdcuqggcf.html

for (i in 1..10) println(i)
来源：http://dali.dashuyun.cn/Article/details/gtrvlfysuy.html

[T15] Kotlin：接口
来源：http://dali.yuanzhike.top/Article/details/gttxjbhfkt.html

interface Shape { fun area(): Double }
来源：http://dali.guannengcc.top/Article/details/gtxyksqdtm.html

[T16] Swift：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtjmryrwos.html

print("Hello")
来源：http://dali.iojbl.cn/Article/details/gtppaviewy.html

[T17] Swift：变量与常量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnublznas.html

var a = 1;  let b = 2
来源：http://dali.xuetiantiany.cn/Article/details/gtmvzkswsz.html

[T18] Swift：字符串插值
来源：http://dali.yuxming.cn/Article/details/gtfqppvfyj.html

"值: \(b)"
来源：http://dali.guannengcc.top/Article/details/gtxggitijj.html

[T19] Swift：可选绑定
来源：http://dali.redwolf501.top/Article/details/gtrgubyqtw.html

if let n = opt { print(n) }
来源：http://dali.zhiwuduotai.top/Article/details/gtgsoialyz.html

[T20] Swift：数组操作
来源：http://dali.ppjwa.cn/Article/details/gtjtmjzhpu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sysykeji.top/Article/details/gtnluqnypa.html

[T21] Swift：遍历
来源：http://dali.shzxlz.cn/Article/details/gtdqkzbukz.html

for x in a { print(x) }
来源：http://dali.smart0.xyz/Article/details/gtzaweggvy.html

[T22] Swift：字典
来源：http://dali.daria6918.cn/Article/details/gtcllwlpvf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.birdmap.top/Article/details/gtimftshkw.html

[T23] Swift：函数
来源：http://dali.hywenlv.cn/Article/details/gtlrkxsaik.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shangyingyoupin.top/Article/details/gtypphlcoz.html

[T24] Swift：闭包
来源：http://dali.aizwys.cn/Article/details/gtfdsvyaee.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yueranfly.top/Article/details/gtirxxajsx.html

[T25] Swift：结构体
来源：http://dali.aizwys.cn/Article/details/gtorzthbuq.html

struct P { var x: Int }
来源：http://dali.jiagoushi.top/Article/details/gtxobmpjol.html

[T26] Swift：类与重写
来源：http://dali.nanxinkj.top/Article/details/gtwcwyspau.html

class A: Base { override func f() {} }
来源：http://dali.tanke756.top/Article/details/gtuewjhzmv.html

[T27] Swift：错误处理
来源：http://dali.jiagoushi.top/Article/details/gtkpthfczg.html

do { try f() } catch { print(error) }
来源：http://dali.0kj1m.cn/Article/details/gtuawwujrw.html

[T28] Swift：枚举
来源：http://dali.tanke756.top/Article/details/gtdrqdggrs.html

enum Color { case red, green }
来源：http://dali.zdqjudy.top/Article/details/gtdxkuwmpg.html

[T29] Swift：guard 提前返回
来源：http://dali.yonumen.top/Article/details/gtgngxcjgo.html

guard let x = opt else { return }
来源：http://dali.svipenyu.cn/Article/details/gtlajunely.html

[T30] Swift：协议
来源：http://dali.shuidangran.top/Article/details/gtqqrbdefv.html

protocol Shape { func area() -> Double }
来源：http://dali.jinqigufen.top/Article/details/gtalwdkubv.html

[T31] Lua：Hello World
来源：http://dali.316326.xyz/Article/details/gtrzyltacm.html

print("Hello")
来源：http://dali.nwbrower.top/Article/details/gtheyliqtv.html

[T32] Lua：局部变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtinvlsdsz.html

local a = 1
来源：http://dali.hammf.cn/Article/details/gtkhtwlsii.html

[T33] Lua：表（数组）
来源：http://dali.xuanzx.com/Article/details/gthmzpdrdg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.feifeiyinyue.top/Article/details/gtghpgbvam.html

[T34] Lua：遍历表
来源：http://dali.wangdashe.top/Article/details/gtwmvdabjl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.dashuyun.cn/Article/details/gtasvuqsvo.html

[T35] Lua：字典表
来源：http://dali.xuanzx.com/Article/details/gteccivcte.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinqigufen.top/Article/details/gtypvdruyq.html

[T36] Lua：函数
来源：http://dali.tanke756.top/Article/details/gtyparqhlz.html

function add(a, b) return a + b end
来源：http://dali.xinyue.icu/Article/details/gtryimupbc.html

[T37] Lua：字符串拼接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtflnusxpj.html

"a" .. "b"
来源：http://dali.sxryk.cn/Article/details/gtrtvfbitr.html

[T38] Lua：条件
来源：http://dali.0kj1m.cn/Article/details/gtljmcxpcc.html

if x > 0 then print("正") end
来源：http://dali.jinqigufen.top/Article/details/gtcqzetaij.html

[T39] Lua：模式匹配
来源：http://dali.fzhhl.top/Article/details/gtrgcbqyre.html

string.find(s, "%d+")
来源：http://dali.chenzaomai.com/Article/details/gtprxdolay.html

[T40] Lua：元表
来源：http://dali.zhengqikj.top/Article/details/gthigwpkjj.html

setmetatable({}, { __index = base })
来源：http://dali.havefunace.top/Article/details/gtiusxzpls.html

[T41] Perl：Hello World
来源：http://dali.cucudq.cn/Article/details/gtipjkoyuk.html

print "Hello\n";
来源：http://dali.yongpay.top/Article/details/gtdgxfbvet.html

[T42] Perl：变量类型
来源：http://dali.hysaishi.cn/Article/details/gthqfbpkgi.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhoulong.xyz/Article/details/gtxatcituh.html

[T43] Perl：字符串插值
来源：http://dali.jyoumei.cn/Article/details/gtuiadoacs.html

"值: $a"
来源：http://dali.sweek.top/Article/details/gtkiuzbldz.html

[T44] Perl：条件
来源：http://dali.jlsjyb.cn/Article/details/gtsevsvdnq.html

if ($a > 0) { print "正"; }
来源：http://dali.meibo888.top/Article/details/gtrrfwupds.html

[T45] Perl：数组遍历
来源：http://dali.yuxming.cn/Article/details/gtsfytmios.html

for my $x (@arr) { print $x; }
来源：http://dali.zhiwuduotai.top/Article/details/gtafbppdpd.html

[T46] Perl：哈希操作
来源：http://dali.xinyue.icu/Article/details/gthjfnxfjn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zycfv.cn/Article/details/gtvrqmhcpw.html

[T47] Perl：正则捕获
来源：http://dali.smart0.xyz/Article/details/gtzpqgntjr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hammf.cn/Article/details/gtnufbfdnm.html

[T48] Perl：正则替换
来源：http://dali.hysaishi.cn/Article/details/gtebenlkbp.html

$s =~ s/old/new/g;
来源：http://dali.nanxuanxn.top/Article/details/gtoxsndnmp.html

[T49] Perl：函数
来源：http://dali.hnqzz.top/Article/details/gtybrvunff.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmpuvictl.html

[T50] Perl：逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtfxkgnawl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.wangshuangyany.cn/Article/details/gtewrdxhpv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xylfe.cn/Article/details/gtrwfenpiq.html

[T51] Scala：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtafjahkup.html

println("Hello")
来源：http://dali.zdqjudy.top/Article/details/gtyfmaaelb.html

[T52] Scala：变量
来源：http://dali.meibo888.top/Article/details/gtwyvmvgav.html

val a = 1;  var b = 2
来源：http://dali.ivvv.top/Article/details/gtrybrgaos.html

[T53] Scala：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gtaqasoypi.html

s"值: $b"
来源：http://dali.jinghuilouyu.cn/Article/details/gtfnphfllh.html

[T54] Scala：集合映射
来源：http://dali.9152youxi.cn/Article/details/gtsrqzyeom.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzhjzlspf.html

[T55] Scala：集合过滤
来源：http://dali.zycfv.cn/Article/details/gtetzxxwmm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhoulong.xyz/Article/details/gtxrcqfwip.html

[T56] Scala：样例类
来源：http://dali.yonumen.top/Article/details/gtbnmeegsd.html

case class User(name: String, age: Int)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuwfqdfev.html

[T57] Scala：模式匹配
来源：http://dali.jqgfzy.top/Article/details/gtgckznlqi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gotoacloud.top/Article/details/gtzbbcmabs.html

[T58] Scala：函数定义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrykqlsln.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gogol.net.cn/Article/details/gtxnilhwzs.html

[T59] Scala：循环
来源：http://dali.havefunace.top/Article/details/gtxhltwfce.html

for (i <- 1 to 10) println(i)
来源：http://dali.pycfn.com/Article/details/gtibclivkb.html

[T60] Scala：折叠
来源：http://dali.c1oappe.top/Article/details/gtutuuduaf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.wangdashe.top/Article/details/gtuxwgjgiq.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtxjcljttw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.nanxuanxn.top/Article/details/gtqsqeigtt.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtdsxlfqbq.html

[U01] Py：创建虚拟环境
来源：http://dali.yangfankeji.com/Article/details/gtvnvyrmdg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hnxiangtu.top/Article/details/gtbceeuivr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.havefunace.top/Article/details/gttiwhhwwj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yueranfly.top/Article/details/gtamcxbvvu.html

[U03] Py：加载 .env 配置
来源：http://dali.xinyue.icu/Article/details/gtkexlqdkf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.c1oappe.top/Article/details/gtuwfqrifq.html

[U04] Py：变量调试打印
来源：http://dali.yj20258.top/Article/details/gtmepfkpal.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.guannengcc.top/Article/details/gteifdkldv.html

[U05] Py：列表去重且保序
来源：http://dali.havefunace.top/Article/details/gtpcxkwbjh.html

list(dict.fromkeys(arr))
来源：http://dali.ydzc1.top/Article/details/gtckwsqfhs.html

[U06] Py：合并两个字典
来源：http://dali.yj20258.top/Article/details/gtjviuhosv.html

{**a, **b}
来源：http://dali.shuidangran.top/Article/details/gtttxvnmzr.html

[U07] Py：反转字典键值
来源：http://dali.yueranfly.top/Article/details/gttoydrifs.html

{v: k for k, v in d.items()}
来源：http://dali.svipenyu.cn/Article/details/gtsmzwxtya.html

[U08] Py：展平二维列表
来源：http://dali.xuetiantiany.cn/Article/details/gtziiflbcz.html

[y for x in nested for y in x]
来源：http://dali.316326.xyz/Article/details/gtshpaoibt.html

[U09] Py：字典取最大值的键
来源：http://dali.ehwqpu.com/Article/details/gtruzuavin.html

max(d, key=d.get)
来源：http://dali.shzxlz.cn/Article/details/gtyhhypuro.html

[U10] Py：按值排序字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzsnnrgkn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hongshengwenyu.top/Article/details/gtfukmdhmz.html

[U11] Py：生成器表达式
来源：http://dali.vqdsnc.cn/Article/details/gtslhwtvbx.html

(x * 2 for x in arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtgoiqcovg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.pengpengdd.cyou/Article/details/gtiodiejzb.html

Counter(arr).most_common(3)
来源：http://dali.yj20258888.top/Article/details/gtakjqdkgl.html

[U13] Py：固定长度队列
来源：http://dali.yanxiufei.cn/Article/details/gthnnwedbm.html

deque(maxlen=10)
来源：http://dali.wangshuangyany.cn/Article/details/gtnnuzelmu.html

[U14] Py：分组收集到列表
来源：http://dali.cashguo.top/Article/details/gtmjymidvk.html

defaultdict(list)
来源：http://dali.nwbrower.top/Article/details/gttceqhwrb.html

[U15] Py：高精度计时
来源：http://dali.zhiwuduotai.top/Article/details/gtjrqqhkpv.html

t = time.perf_counter()
来源：http://dali.yongpay.top/Article/details/gtwsrxhxye.html

[U16] Py：命令行参数解析
来源：http://dali.havefunace.top/Article/details/gtegsekqyl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xziqi.cn/Article/details/gtpgecorka.html

[U17] Py：初始化日志
来源：http://dali.pycfn.com/Article/details/gtzvquxdiy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.nanxuanxn.top/Article/details/gtzzwkkryj.html

[U18] Py：预编译正则
来源：http://dali.bjfxy.top/Article/details/gtmzsqtstl.html

pat = re.compile(r"\d+")
来源：http://dali.zdqjudy.top/Article/details/gtfvlrkmiy.html

[U19] Py：正则替换带回调
来源：http://dali.gaohongyu789.top/Article/details/gtlatwxwsk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yuxming.cn/Article/details/gtobprgvih.html

[U20] Py：缓存函数结果
来源：http://dali.yonumen.top/Article/details/gttpedrdbo.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhengqikj.top/Article/details/gtvjfvxzcw.html

[U21] Py：自定义上下文管理器
来源：http://dali.dianchejie.cn/Article/details/gtgamtnycb.html

@contextlib.contextmanager
来源：http://dali.zhengqikj.top/Article/details/gtzyprarfw.html

[U22] Py：矩阵转置
来源：http://dali.jianghu66.top/Article/details/gtbphvoeey.html

list(zip(*m))
来源：http://dali.daxiang520.top/Article/details/gtqegjwcms.html

[U23] Py：分块读取大文件
来源：http://dali.hysaishi.cn/Article/details/gtjlqvszyf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hongshengwenyu.top/Article/details/gtyhzedlih.html

[U24] Py：路径操作
来源：http://dali.hnxiangtu.top/Article/details/gtrdyspnmw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zdqjudy.top/Article/details/gtzhgqcqty.html

[U25] Py：CSV 按字典读
来源：http://dali.feifeiyinyue.top/Article/details/gtmehfjjgs.html

csv.DictReader(f)
来源：http://dali.tianlin.xyz/Article/details/gtjgnczrhu.html

[U26] Py：并发下载
来源：http://dali.hnxiangtu.top/Article/details/gttenjderi.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.pengpengdd.cyou/Article/details/gtakhozcuo.html

[U27] Py：异步 HTTP
来源：http://dali.jyoumei.cn/Article/details/gtmggyaryr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ybcxt.top/Article/details/gtyfpenrtr.html

[U28] Py：类型别名
来源：http://dali.bjfxy.top/Article/details/gtxqqdirqr.html

UserId = int
来源：http://dali.yuxming.cn/Article/details/gtmfabfmoe.html

[U29] Py：属性校验
来源：http://dali.yanxiufei.cn/Article/details/gtqndxkcdp.html

@property 与 @x.setter 配合
来源：http://dali.haohaochexian.top/Article/details/gtpvcdzdge.html

[U30] Py：数据类
来源：http://dali.jinqigufen.top/Article/details/gtdhcnmxtf.html

@dataclass(slots=True)
来源：http://dali.svipenyu.cn/Article/details/gtsvqabgcf.html


<!-- 参考信息 -->