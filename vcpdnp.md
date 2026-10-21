代发 wailian999

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hnqzz.top/Article/details/gtbgqgjhey.html

[S08] C：动态内存分配与释放
来源：http://dali.yj20258888.top/Article/details/gtodozyhog.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hysaishi.cn/Article/details/gtkhwbkcuz.html

[S09] C：结构体定义与初始化
来源：http://dali.shuidangran.top/Article/details/gtcsleyqkx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yuxming.cn/Article/details/gtwjvknatx.html

[S10] C：指针与解引用
来源：http://dali.gogol.net.cn/Article/details/gtfveschri.html

int *p = &a;  *p = 5;
来源：http://dali.gogol.net.cn/Article/details/gtmnfzcdrq.html

[S11] C：逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gteibxjlmm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhiwuduotai.top/Article/details/gtnosbqvsn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ydzc1.top/Article/details/gtynluwpvi.html

fclose(f);
来源：http://dali.gotoacloud.top/Article/details/gtxqprpume.html

[S12] C：写文件
来源：http://dali.yangfankeji.com/Article/details/gtqwnhaiij.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenzaomai.com/Article/details/gtaifzdjyd.html

[S13] C：宏定义
来源：http://dali.mhx1999.top/Article/details/gtibtulvyc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.vqdsnc.cn/Article/details/gtrtfnfcvp.html

[S14] C：枚举
来源：http://dali.guowangkeji.top/Article/details/gtzpoyxayd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.svipenyu.cn/Article/details/gtcohperny.html

[S15] C：类型转换
来源：http://dali.nanxinkj.top/Article/details/gtljwqbctd.html

(double) a / b
来源：http://dali.ybcxt.top/Article/details/gtnsdswllw.html

[S16] C：位操作置位
来源：http://dali.jlsjyb.cn/Article/details/gteljducac.html

x |= (1 << 3);
来源：http://dali.tian-w.cn/Article/details/gtfzfplgwr.html

[S17] C：安全拼接字符串
来源：http://dali.vqdsnc.cn/Article/details/gtojawuiqs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.pycfn.com/Article/details/gtmgecljdf.html

[S18] C：命令行参数
来源：http://dali.nanxuanxn.top/Article/details/gtaimomine.html

int main(int argc, char **argv)
来源：http://dali.tanke756.top/Article/details/gtmblsdold.html

[S19] C：快速排序
来源：http://dali.zhoulong.xyz/Article/details/gtlvxzqpfs.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gthksvigtm.html

[S20] C：二分查找
来源：http://dali.birdmap.top/Article/details/gtwgwzfqll.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gtscroprmn.html

[S21] C：字符类别判断
来源：http://dali.yj20258888.top/Article/details/gtprblyzue.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlzvlvkvz.html

[S22] C：字符串转数字
来源：http://dali.gotoacloud.top/Article/details/gtanxlrpxm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ehwqpu.com/Article/details/gtvcpxlixt.html

[S23] C：随机数
来源：http://dali.daxiang520.top/Article/details/gttfqlcwzh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yuanzhike.top/Article/details/gtlyykckqx.html

[S24] C：获取本地时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtypmaztyh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenlongwang.top/Article/details/gtmnanvkan.html

[S25] C：内存拷贝
来源：http://dali.jqgfzy.top/Article/details/gtsrvybrxb.html

memcpy(dst, src, n);
来源：http://dali.shzxlz.cn/Article/details/gtbmsuendo.html

[S26] C：内存清零
来源：http://dali.hammf.cn/Article/details/gtrjjyqmjr.html

memset(a, 0, sizeof a);
来源：http://dali.havefunace.top/Article/details/gtsaftjkfm.html

[S27] C：定义常量
来源：http://dali.shanyushiyangtech.top/Article/details/gtkhcdnkoa.html

const double PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gttfcswgex.html

[S28] C：静态变量
来源：http://dali.yongpay.top/Article/details/gtjjewwtfa.html

static int counter = 0;
来源：http://dali.quarkkingdee.top/Article/details/gtxvmmxixl.html

[S29] C：变参函数
来源：http://dali.hongshengwenyu.top/Article/details/gtdaojzcfs.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigfzy.top/Article/details/gtmfknbtdk.html

[S30] C：头文件保护
来源：http://dali.yj20258.top/Article/details/gtnbquhcfb.html

#ifndef X_H
来源：http://dali.sysykeji.top/Article/details/gtmirudsjj.html

#define X_H
来源：http://dali.shanyushiyangtech.top/Article/details/gtazxlxtop.html

#endif
来源：http://dali.mhx1999.top/Article/details/gtikkqxklq.html

[S31] C++：Hello World
来源：http://dali.ivvv.top/Article/details/gtoirvyxjs.html

#include <iostream>
来源：http://dali.yuanzhike.top/Article/details/gthhcpklsa.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhoulong.xyz/Article/details/gtmavlkzso.html

[S32] C++：字符串
来源：http://dali.kuanghao11.cn/Article/details/gtixulfmiw.html

std::string s = "hi";  s += "!";
来源：http://dali.guannengcc.top/Article/details/gtchfmgboa.html

[S33] C++：vector 增删
来源：http://dali.nwbrower.top/Article/details/gtlvtwfkka.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhoulong.xyz/Article/details/gtgynltoyz.html

[S34] C++：遍历 vector
来源：http://dali.pycfn.com/Article/details/gtgqghunxd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xinyue.icu/Article/details/gtjzvynmyn.html

[S35] C++：map
来源：http://dali.hnqzz.top/Article/details/gttbuqpdwb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daria6918.cn/Article/details/gtflbnfynm.html

[S36] C++：unordered_map
来源：http://dali.yj20258888.top/Article/details/gtumthpyxr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sxryk.cn/Article/details/gtwfcsyhjm.html

[S37] C++：set
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdbiouyrd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ydzc1.top/Article/details/gtutlbrhca.html

[S38] C++：排序
来源：http://dali.zhengqikj.top/Article/details/gtoxpgeoge.html

std::sort(v.begin(), v.end());
来源：http://dali.xziqi.cn/Article/details/gtyrzhtepi.html

[S39] C++：自定义比较器排序
来源：http://dali.chenlongwang.top/Article/details/gtqiicysxc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.aizwys.cn/Article/details/gttjqqkicu.html

[S40] C++：查找元素
来源：http://dali.smart0.xyz/Article/details/gtkjdwoyqh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yangfankeji.com/Article/details/gtkrhxzxik.html

[S41] C++：类与构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtuxojwxwk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jqgfzy.top/Article/details/gtoedpvoat.html

[S42] C++：继承与虚函数
来源：http://dali.ivvv.top/Article/details/gtkbxtasce.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhiwuduotai.top/Article/details/gtdwogcndo.html

[S43] C++：智能指针
来源：http://dali.bjfxy.top/Article/details/gtoahhavia.html

auto p = std::make_unique<int>(5);
来源：http://dali.yuanzhike.top/Article/details/gtkvfongkc.html

[S44] C++：引用传参
来源：http://dali.ehwqpu.com/Article/details/gtarzdbbhh.html

void inc(int &x) { ++x; }
来源：http://dali.yangfankeji.com/Article/details/gtjzlkkusv.html

[S45] C++：lambda
来源：http://dali.gotoacloud.top/Article/details/gtlyxybrma.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cucudq.cn/Article/details/gtrvhttjsl.html

[S46] C++：函数模板
来源：http://dali.yj202588.top/Article/details/gturdxenkb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlhinkxfh.html

[S47] C++：结构化绑定遍历
来源：http://dali.andypj.xyz/Article/details/gtyqtoxuwx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sweek.top/Article/details/gtpizkpgte.html

[S48] C++：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gtnuqigghd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.9152youxi.cn/Article/details/gtifgiheqm.html

while (std::getline(in, line)) { }
来源：http://dali.jlsjyb.cn/Article/details/gtuvgglizu.html

[S49] C++：写文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvixwdwxx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tianlin.xyz/Article/details/gthnihhwvj.html

[S50] C++：格式化数字
来源：http://dali.jinqigufen.top/Article/details/gtfsmxrujy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gtgljsdwnw.html

[S51] C++：显式类型转换
来源：http://dali.fzhhl.top/Article/details/gttpbtslaa.html

static_cast<double>(a) / b
来源：http://dali.wangshuangyany.cn/Article/details/gtfihzvfil.html

[S52] C++：const 与 noexcept
来源：http://dali.chenjidiqi.icu/Article/details/gthppqkspn.html

int size() const noexcept { return n_; }
来源：http://dali.snrcjt.cn/Article/details/gtdbwdhuyj.html

[S53] C++：移动语义
来源：http://dali.vqdsnc.cn/Article/details/gtukvcsczu.html

std::vector<int> w = std::move(v);
来源：http://dali.9152youxi.cn/Article/details/gtqhricegf.html

[S54] C++：异常处理
来源：http://dali.guowangkeji.top/Article/details/gtglgbcjly.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenlongwang.top/Article/details/gtlghphrdm.html

[S55] C++：结构化绑定
来源：http://dali.jinyuanbaomall.cn/Article/details/gtamtbabcd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.svipenyu.cn/Article/details/gtrlqsepiz.html

[S56] C++：optional
来源：http://dali.redwolf501.top/Article/details/gtezjcsacg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yuxming.cn/Article/details/gthdufhklz.html

[S57] C++：编译期常量
来源：http://dali.yj20258.top/Article/details/gtoqblgzgr.html

constexpr int N = 10;
来源：http://dali.pengpengdd.cyou/Article/details/gthrssltms.html

[S58] C++：命名空间
来源：http://dali.0kj1m.cn/Article/details/gtsosudsjq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhoulong.xyz/Article/details/gtliwvoiny.html

[S59] C++：静态断言
来源：http://dali.feifeiyinyue.top/Article/details/gtsvjvmhoi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cashguo.top/Article/details/gtsqhrabzp.html

[S60] C++：遍历并删除元素
来源：http://dali.gaohongyu789.top/Article/details/gtujepxwsa.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.meibo888.top/Article/details/gtkxsdjkrq.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtksokrbro.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.redwolf501.top/Article/details/gtjlgoakhg.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtxdpfzeqm.html

[T01] Kotlin：Hello World
来源：http://dali.hnqzz.top/Article/details/gtubyajwek.html

println("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gtwrrmekdj.html

[T02] Kotlin：变量
来源：http://dali.smart0.xyz/Article/details/gtmepmpjhf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xylfe.cn/Article/details/gtujndtxxa.html

[T03] Kotlin：字符串模板
来源：http://dali.hnqzz.top/Article/details/gtnxzfytkd.html

"值: $b"
来源：http://dali.0kj1m.cn/Article/details/gtthytpxqw.html

[T04] Kotlin：空安全
来源：http://dali.jinghuilouyu.cn/Article/details/gtgxnfxizp.html

val n: String? = null;  n?.length
来源：http://dali.pengpengdd.cyou/Article/details/gtjpmftkui.html

[T05] Kotlin：when 表达式
来源：http://dali.daria6918.cn/Article/details/gtmkqwtzhl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.birdmap.top/Article/details/gtbstmacjx.html

[T06] Kotlin：集合映射
来源：http://dali.iojbl.cn/Article/details/gtvqdbcaip.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yj20258.top/Article/details/gtvrewdggz.html

[T07] Kotlin：集合过滤
来源：http://dali.yvedp.cn/Article/details/gtisxckjvy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sufxvd.cn/Article/details/gtdqwivnly.html

[T08] Kotlin：数据类
来源：http://dali.gogol.net.cn/Article/details/gtcfbvlsxe.html

data class User(val name: String, val age: Int)
来源：http://dali.tianlin.xyz/Article/details/gtagugqvnq.html

[T09] Kotlin：扩展函数
来源：http://dali.gaohongyu789.top/Article/details/gthihbmcbl.html

fun String.exclaim() = this + "!"
来源：http://dali.haohaochexian.top/Article/details/gtdmezlicl.html

[T10] Kotlin：默认参数
来源：http://dali.yongpay.top/Article/details/gtekszjdhy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yonumen.top/Article/details/gtbhwwlfjw.html

[T11] Kotlin：协程
来源：http://dali.redwolf501.top/Article/details/gtxuviblsw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.smart0.xyz/Article/details/gtjplvgngy.html

[T12] Kotlin：解构声明
来源：http://dali.xylfe.cn/Article/details/gtgzbdhocr.html

val (a, b) = Pair(1, 2)
来源：http://dali.zycfv.cn/Article/details/gtkwhmfgow.html

[T13] Kotlin：只读 Map
来源：http://dali.cdnleiting.top/Article/details/gtvmgtcwec.html

val m = mapOf("a" to 1)
来源：http://dali.nanxuanxn.top/Article/details/gtdiuahmel.html

[T14] Kotlin：循环
来源：http://dali.chenzaomai.com/Article/details/gtknlnicvo.html

for (i in 1..10) println(i)
来源：http://dali.jlsjyb.cn/Article/details/gtatwkqtxi.html

[T15] Kotlin：接口
来源：http://dali.cdnleiting.top/Article/details/gtwgebbfha.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gtrawrahzz.html

[T16] Swift：Hello World
来源：http://dali.shuidangran.top/Article/details/gtlpshdyrs.html

print("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiizjhjre.html

[T17] Swift：变量与常量
来源：http://dali.haohaochexian.top/Article/details/gtjbpubawb.html

var a = 1;  let b = 2
来源：http://dali.yangfankeji.com/Article/details/gtsgpfnhzi.html

[T18] Swift：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gtnmovagjc.html

"值: \(b)"
来源：http://dali.wangdashe.top/Article/details/gtfmxfmlsa.html

[T19] Swift：可选绑定
来源：http://dali.chenjidiqi.icu/Article/details/gtlfhowayj.html

if let n = opt { print(n) }
来源：http://dali.guowangkeji.top/Article/details/gtqdzsjxcj.html

[T20] Swift：数组操作
来源：http://dali.jqgfzy.top/Article/details/gtucwxvdaj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zycfv.cn/Article/details/gtlshdxmav.html

[T21] Swift：遍历
来源：http://dali.fengsongda.top/Article/details/gtijehcnui.html

for x in a { print(x) }
来源：http://dali.zhiwuduotai.top/Article/details/gtesyahgub.html

[T22] Swift：字典
来源：http://dali.feifeiyinyue.top/Article/details/gtftzgxlgo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gogol.net.cn/Article/details/gtvkjiazby.html

[T23] Swift：函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtazchdjjq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xuanzx.com/Article/details/gtfexsndjz.html

[T24] Swift：闭包
来源：http://dali.wangdashe.top/Article/details/gtgbetuart.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shzxlz.cn/Article/details/gtyoqcuspu.html

[T25] Swift：结构体
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdpvajdar.html

struct P { var x: Int }
来源：http://dali.xuetiantiany.cn/Article/details/gtcozkspln.html

[T26] Swift：类与重写
来源：http://dali.cashguo.top/Article/details/gtnkaoengo.html

class A: Base { override func f() {} }
来源：http://dali.pycfn.com/Article/details/gtbtjikcpi.html

[T27] Swift：错误处理
来源：http://dali.yj202588.top/Article/details/gtshqmciky.html

do { try f() } catch { print(error) }
来源：http://dali.sufxvd.cn/Article/details/gtktgejwif.html

[T28] Swift：枚举
来源：http://dali.c1oappe.top/Article/details/gtzcbyyuih.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gtfxjqvllc.html

[T29] Swift：guard 提前返回
来源：http://dali.guannengcc.top/Article/details/gtyxuieokl.html

guard let x = opt else { return }
来源：http://dali.xziqi.cn/Article/details/gtpgusncae.html

[T30] Swift：协议
来源：http://dali.xuanzx.com/Article/details/gtgxfhqqxo.html

protocol Shape { func area() -> Double }
来源：http://dali.c1oappe.top/Article/details/gtjdemkgge.html

[T31] Lua：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtoqqkwzbf.html

print("Hello")
来源：http://dali.zycfv.cn/Article/details/gtokfqlioo.html

[T32] Lua：局部变量
来源：http://dali.9152youxi.cn/Article/details/gtlyagcqff.html

local a = 1
来源：http://dali.shuidangran.top/Article/details/gtzazygmji.html

[T33] Lua：表（数组）
来源：http://dali.cashguo.top/Article/details/gtfaqzpwbj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkdpcammg.html

[T34] Lua：遍历表
来源：http://dali.xylfe.cn/Article/details/gtenxmfspo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shanyushiyangtech.top/Article/details/gtyvuhukea.html

[T35] Lua：字典表
来源：http://dali.ydzc1.top/Article/details/gtcrdojjmz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.iojbl.cn/Article/details/gthkrfdybx.html

[T36] Lua：函数
来源：http://dali.yj20258.top/Article/details/gtfcvjsfkg.html

function add(a, b) return a + b end
来源：http://dali.havefunace.top/Article/details/gtqcnhnydf.html

[T37] Lua：字符串拼接
来源：http://dali.jinghuilouyu.cn/Article/details/gtmudqjfld.html

"a" .. "b"
来源：http://dali.shzxlz.cn/Article/details/gtgfugrbqg.html

[T38] Lua：条件
来源：http://dali.jianghu66.top/Article/details/gtbpakivje.html

if x > 0 then print("正") end
来源：http://dali.yj202588.top/Article/details/gtowujqpus.html

[T39] Lua：模式匹配
来源：http://dali.guannengcc.top/Article/details/gtmkosnfvd.html

string.find(s, "%d+")
来源：http://dali.jianghu66.top/Article/details/gtxkksjxey.html

[T40] Lua：元表
来源：http://dali.kuanghao11.cn/Article/details/gtwbwksnwp.html

setmetatable({}, { __index = base })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsjfntsfc.html

[T41] Perl：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtvygeeime.html

print "Hello\n";
来源：http://dali.chenzaomai.com/Article/details/gtnjcuuzzu.html

[T42] Perl：变量类型
来源：http://dali.cucudq.cn/Article/details/gtrqgxjjlf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.redwolf501.top/Article/details/gtizvfccxd.html

[T43] Perl：字符串插值
来源：http://dali.jianghu66.top/Article/details/gtqbfprxok.html

"值: $a"
来源：http://dali.xziqi.cn/Article/details/gtaixezjiy.html

[T44] Perl：条件
来源：http://dali.zhixingplan.top/Article/details/gtergiscqc.html

if ($a > 0) { print "正"; }
来源：http://dali.sweek.top/Article/details/gtdfyngsyw.html

[T45] Perl：数组遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtiqtlktdk.html

for my $x (@arr) { print $x; }
来源：http://dali.zhiwuduotai.top/Article/details/gtnajpyrsb.html

[T46] Perl：哈希操作
来源：http://dali.cashguo.top/Article/details/gtxzgqipjj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hywenlv.cn/Article/details/gtmopkdzli.html

[T47] Perl：正则捕获
来源：http://dali.redwolf501.top/Article/details/gtesiunjzi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.chenjidiqi.icu/Article/details/gthdzincyd.html

[T48] Perl：正则替换
来源：http://dali.jlsjyb.cn/Article/details/gtpsdabcej.html

$s =~ s/old/new/g;
来源：http://dali.shangyingyoupin.top/Article/details/gtcrjpydaf.html

[T49] Perl：函数
来源：http://dali.ivvv.top/Article/details/gtldgvixaq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfptfmbjd.html

[T50] Perl：逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gtzxccreuw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.havefunace.top/Article/details/gtqkqodzwe.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.c1oappe.top/Article/details/gtwcptwlme.html

[T51] Scala：Hello World
来源：http://dali.yvedp.cn/Article/details/gtqhggkbdl.html

println("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gtavtbkxzt.html

[T52] Scala：变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgkowdivb.html

val a = 1;  var b = 2
来源：http://dali.ybcxt.top/Article/details/gtbgmhiqgl.html

[T53] Scala：字符串插值
来源：http://dali.shuidangran.top/Article/details/gtxfahbpch.html

s"值: $b"
来源：http://dali.c1oappe.top/Article/details/gtabgisszg.html

[T54] Scala：集合映射
来源：http://dali.9152youxi.cn/Article/details/gtbqiccjbe.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ppjwa.cn/Article/details/gttikrfwzx.html

[T55] Scala：集合过滤
来源：http://dali.yuanzhike.top/Article/details/gtrvdjujss.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.nwbrower.top/Article/details/gtlvmbtrlf.html

[T56] Scala：样例类
来源：http://dali.pengpengdd.cyou/Article/details/gtiegikljz.html

case class User(name: String, age: Int)
来源：http://dali.gogol.net.cn/Article/details/gtdixoyvrg.html

[T57] Scala：模式匹配
来源：http://dali.aizwys.cn/Article/details/gtgxsenopg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.chenjidiqi.icu/Article/details/gttgsjcrwt.html

[T58] Scala：函数定义
来源：http://dali.sweek.top/Article/details/gtooxdcujf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinqigufen.top/Article/details/gtnrimdrfs.html

[T59] Scala：循环
来源：http://dali.andypj.xyz/Article/details/gtjydleahg.html

for (i <- 1 to 10) println(i)
来源：http://dali.quarkkingdee.top/Article/details/gtnejgiivb.html

[T60] Scala：折叠
来源：http://dali.wangdashe.top/Article/details/gtbaybwrfo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ehwqpu.com/Article/details/gthttjdpam.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtvbwiooiw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.haohaochexian.top/Article/details/gtobidsoyt.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtwwoewsmt.html

[U01] Py：创建虚拟环境
来源：http://dali.gzhubu.top/Article/details/gtsujoerkd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ydzc1.top/Article/details/gtdsoopohc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gotoacloud.top/Article/details/gtpjhjllxs.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.kuanghao11.cn/Article/details/gtllatfsbp.html

[U03] Py：加载 .env 配置
来源：http://dali.sxryk.cn/Article/details/gtgudlzirf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cheryme.top/Article/details/gtcrszlvhh.html

[U04] Py：变量调试打印
来源：http://dali.dianchejie.cn/Article/details/gtplntpyla.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sxryk.cn/Article/details/gtjxhcnjlb.html

[U05] Py：列表去重且保序
来源：http://dali.yueranfly.top/Article/details/gtakrdxsah.html

list(dict.fromkeys(arr))
来源：http://dali.jqgufenzy.top/Article/details/gtaekfabbh.html

[U06] Py：合并两个字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjzxiocsr.html

{**a, **b}
来源：http://dali.daria6918.cn/Article/details/gtxveufnph.html

[U07] Py：反转字典键值
来源：http://dali.chenjidiqi.icu/Article/details/gtfzbywmvj.html

{v: k for k, v in d.items()}
来源：http://dali.sxryk.cn/Article/details/gtjeeojvlh.html

[U08] Py：展平二维列表
来源：http://dali.yanxiufei.cn/Article/details/gtvsizuhun.html

[y for x in nested for y in x]
来源：http://dali.yuxming.cn/Article/details/gtufkiqsgb.html

[U09] Py：字典取最大值的键
来源：http://dali.yanxiufei.cn/Article/details/gtpfyghrby.html

max(d, key=d.get)
来源：http://dali.cdnleiting.top/Article/details/gtetvudrbv.html

[U10] Py：按值排序字典
来源：http://dali.yj20258.top/Article/details/gtnegntzml.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.smart0.xyz/Article/details/gtsbkvxdrb.html

[U11] Py：生成器表达式
来源：http://dali.iojbl.cn/Article/details/gtjisjgbjz.html

(x * 2 for x in arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtfkwtiaor.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.aizwys.cn/Article/details/gtmnmnmslb.html

Counter(arr).most_common(3)
来源：http://dali.cucudq.cn/Article/details/gtrhhrejkl.html

[U13] Py：固定长度队列
来源：http://dali.vqdsnc.cn/Article/details/gtosqjzqqh.html

deque(maxlen=10)
来源：http://dali.cqqwz.cn/Article/details/gttloyokky.html

[U14] Py：分组收集到列表
来源：http://dali.hfpthk.cn/Article/details/gtovrldhkw.html

defaultdict(list)
来源：http://dali.yangfankeji.com/Article/details/gtxnxfjaki.html

[U15] Py：高精度计时
来源：http://dali.wangshuangyany.cn/Article/details/gtrywvgybr.html

t = time.perf_counter()
来源：http://dali.yj202588.top/Article/details/gtztaqhqej.html

[U16] Py：命令行参数解析
来源：http://dali.andypj.xyz/Article/details/gtaspgodgq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yuanzhike.top/Article/details/gtwwlmjoer.html

[U17] Py：初始化日志
来源：http://dali.jlsjyb.cn/Article/details/gtmashwoax.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhongyouzk.top/Article/details/gtofqtwwiq.html

[U18] Py：预编译正则
来源：http://dali.quarkkingdee.top/Article/details/gtuxawazjf.html

pat = re.compile(r"\d+")
来源：http://dali.dashuyun.cn/Article/details/gtbfxgsadv.html

[U19] Py：正则替换带回调
来源：http://dali.chenlongwang.top/Article/details/gtsnuwavff.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtocrhzdaq.html

[U20] Py：缓存函数结果
来源：http://dali.iojbl.cn/Article/details/gtlbpkhqgu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.shangyingyoupin.top/Article/details/gtwewtdtrs.html

[U21] Py：自定义上下文管理器
来源：http://dali.hnxiangtu.top/Article/details/gttabgubuz.html

@contextlib.contextmanager
来源：http://dali.vqdsnc.cn/Article/details/gtkbjtqzpf.html

[U22] Py：矩阵转置
来源：http://dali.smart0.xyz/Article/details/gtdejprihi.html

list(zip(*m))
来源：http://dali.chenzaomai.com/Article/details/gtbwrumpha.html

[U23] Py：分块读取大文件
来源：http://dali.hywenlv.cn/Article/details/gtakzxjbqm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jqgfzy.top/Article/details/gthllykmug.html

[U24] Py：路径操作
来源：http://dali.aibaodan.cn/Article/details/gtqgxkwjbe.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.guowangkeji.top/Article/details/gtyoxwaewt.html

[U25] Py：CSV 按字典读
来源：http://dali.yj20258.top/Article/details/gthhmbidxx.html

csv.DictReader(f)
来源：http://dali.jqgufenzy.top/Article/details/gtddhtowxj.html

[U26] Py：并发下载
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdljtqilp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.andypj.xyz/Article/details/gtnsryhkwl.html

[U27] Py：异步 HTTP
来源：http://dali.vqdsnc.cn/Article/details/gtnubismqf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jlsjyb.cn/Article/details/gtgpkibmog.html

[U28] Py：类型别名
来源：http://dali.fzhhl.top/Article/details/gtdzamlwqm.html

UserId = int
来源：http://dali.jqgufenzy.top/Article/details/gtjnwoaegc.html

[U29] Py：属性校验
来源：http://dali.9152youxi.cn/Article/details/gtxjfkcvqm.html

@property 与 @x.setter 配合
来源：http://dali.xziqi.cn/Article/details/gtgxmlfkcl.html

[U30] Py：数据类
来源：http://dali.cashguo.top/Article/details/gtvhddpwij.html

@dataclass(slots=True)
来源：http://dali.ppjwa.cn/Article/details/gtymixqyec.html


<!-- 参考信息 -->