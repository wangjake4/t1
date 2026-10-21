代发 wailian999

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.feifeiyinyue.top/Article/details/gtzvonlfcl.html

[S08] C：动态内存分配与释放
来源：http://dali.xinyue.icu/Article/details/gtwulsxpxi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.bjfxy.top/Article/details/gticqrfzwx.html

[S09] C：结构体定义与初始化
来源：http://dali.yj20258888.top/Article/details/gtkfvctprf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvhkizeiy.html

[S10] C：指针与解引用
来源：http://dali.chenzaomai.com/Article/details/gtgqsmkoyi.html

int *p = &a;  *p = 5;
来源：http://dali.pycfn.com/Article/details/gtaknzjtym.html

[S11] C：逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gtqepwwzqi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sxryk.cn/Article/details/gtrwcsvwxz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.haohaochexian.top/Article/details/gteemqyacj.html

fclose(f);
来源：http://dali.aizwys.cn/Article/details/gtfaorpwac.html

[S12] C：写文件
来源：http://dali.vqdsnc.cn/Article/details/gtqvqlwtvd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shangyingyoupin.top/Article/details/gtjhtgjuwz.html

[S13] C：宏定义
来源：http://dali.yj20258.top/Article/details/gticrkfddn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hnqzz.top/Article/details/gtlhkqmcfn.html

[S14] C：枚举
来源：http://dali.havefunace.top/Article/details/gtgwavezzi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.c1oappe.top/Article/details/gtwqghdico.html

[S15] C：类型转换
来源：http://dali.zycfv.cn/Article/details/gtdhxavvpf.html

(double) a / b
来源：http://dali.jyoumei.cn/Article/details/gtsthihjyo.html

[S16] C：位操作置位
来源：http://dali.hywenlv.cn/Article/details/gtuyuxfhxv.html

x |= (1 << 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjtoldghr.html

[S17] C：安全拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gtdlzpcmbz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenlongwang.top/Article/details/gtzllbjaae.html

[S18] C：命令行参数
来源：http://dali.gotoacloud.top/Article/details/gtneiudcvz.html

int main(int argc, char **argv)
来源：http://dali.wangdashe.top/Article/details/gtichtvnix.html

[S19] C：快速排序
来源：http://dali.ehwqpu.com/Article/details/gttxofflcx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yonumen.top/Article/details/gtatcwxqux.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gtouzjpurp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnmtayzmd.html

[S21] C：字符类别判断
来源：http://dali.xuanzx.com/Article/details/gtwksfdghm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yongpay.top/Article/details/gtjdzavxps.html

[S22] C：字符串转数字
来源：http://dali.tian-w.cn/Article/details/gtztxfhboe.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.snrcjt.cn/Article/details/gtcashztvl.html

[S23] C：随机数
来源：http://dali.wangdashe.top/Article/details/gtrbkjloqu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zdqjudy.top/Article/details/gtcqlisxoq.html

[S24] C：获取本地时间
来源：http://dali.shanyushiyangtech.top/Article/details/gtyxmdbsjy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cdnleiting.top/Article/details/gtofaqgqeu.html

[S25] C：内存拷贝
来源：http://dali.jqgufenzy.top/Article/details/gtmbrvqdao.html

memcpy(dst, src, n);
来源：http://dali.nanxinkj.top/Article/details/gtdimyzric.html

[S26] C：内存清零
来源：http://dali.hammf.cn/Article/details/gtiiqavgxq.html

memset(a, 0, sizeof a);
来源：http://dali.ydzc1.top/Article/details/gtfwwqjasp.html

[S27] C：定义常量
来源：http://dali.mhx1999.top/Article/details/gtptvstybd.html

const double PI = 3.14159;
来源：http://dali.iojbl.cn/Article/details/gtmhdvuung.html

[S28] C：静态变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtstbrqoew.html

static int counter = 0;
来源：http://dali.yangfankeji.com/Article/details/gtkspwbvwd.html

[S29] C：变参函数
来源：http://dali.jqgufenzy.top/Article/details/gtccqoonng.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nanxinkj.top/Article/details/gtztzuaolh.html

[S30] C：头文件保护
来源：http://dali.dashuyun.cn/Article/details/gtqipetgpc.html

#ifndef X_H
来源：http://dali.zhongyouzk.top/Article/details/gtmnzrzqbv.html

#define X_H
来源：http://dali.ppjwa.cn/Article/details/gtfaxstfhc.html

#endif
来源：http://dali.chenjidiqi.icu/Article/details/gtxadfzdts.html

[S31] C++：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtmlqwvtjn.html

#include <iostream>
来源：http://dali.xuanzx.com/Article/details/gtgjwsahmz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.birdmap.top/Article/details/gtdnwnkekc.html

[S32] C++：字符串
来源：http://dali.smart0.xyz/Article/details/gtgmnoegyi.html

std::string s = "hi";  s += "!";
来源：http://dali.hongshengwenyu.top/Article/details/gtzzksieyg.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gtqitwcsfw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xylfe.cn/Article/details/gtnvatmyxw.html

[S34] C++：遍历 vector
来源：http://dali.pycfn.com/Article/details/gtckqibtqz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhixingplan.top/Article/details/gtzaxchtty.html

[S35] C++：map
来源：http://dali.meibo888.top/Article/details/gtlnjfmpfa.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtbwjfnslx.html

[S36] C++：unordered_map
来源：http://dali.shangyingyoupin.top/Article/details/gtkqtkgobb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlzynhgrq.html

[S37] C++：set
来源：http://dali.yuxming.cn/Article/details/gtoyrvugro.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhengqikj.top/Article/details/gtxjmkpbcm.html

[S38] C++：排序
来源：http://dali.zhongyouzk.top/Article/details/gtvrtmfvcj.html

std::sort(v.begin(), v.end());
来源：http://dali.xziqi.cn/Article/details/gtzzsmdmdk.html

[S39] C++：自定义比较器排序
来源：http://dali.jyoumei.cn/Article/details/gtmvlwdsdl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yuxming.cn/Article/details/gtctfjqtpm.html

[S40] C++：查找元素
来源：http://dali.daxiang520.top/Article/details/gtsqsdxoaj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yvedp.cn/Article/details/gtpaemiqvi.html

[S41] C++：类与构造函数
来源：http://dali.meibo888.top/Article/details/gtldxzrzhf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.fengsongda.top/Article/details/gtlyicfpby.html

[S42] C++：继承与虚函数
来源：http://dali.yj20258.top/Article/details/gtvbvdhlql.html

class B : public Base { public: void f() override {} };
来源：http://dali.gogol.net.cn/Article/details/gtbzlsgkbg.html

[S43] C++：智能指针
来源：http://dali.zdqjudy.top/Article/details/gtgffuqcqt.html

auto p = std::make_unique<int>(5);
来源：http://dali.sysykeji.top/Article/details/gtexycdzdh.html

[S44] C++：引用传参
来源：http://dali.gzhubu.top/Article/details/gtiuhrvjyw.html

void inc(int &x) { ++x; }
来源：http://dali.fzhhl.top/Article/details/gtxsnkiruw.html

[S45] C++：lambda
来源：http://dali.zhengqikj.top/Article/details/gtudgetvst.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtpbfpihjn.html

[S46] C++：函数模板
来源：http://dali.feifeiyinyue.top/Article/details/gtctjoftpn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ivvv.top/Article/details/gtvjjmqfyf.html

[S47] C++：结构化绑定遍历
来源：http://dali.hnqzz.top/Article/details/gtwpsuvxzj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.smart0.xyz/Article/details/gtyyooqdmn.html

[S48] C++：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtfjqgnodo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yangfankeji.com/Article/details/gtcavorqhp.html

while (std::getline(in, line)) { }
来源：http://dali.jiagoushi.top/Article/details/gtadftqbjd.html

[S49] C++：写文件
来源：http://dali.zhiwuduotai.top/Article/details/gtlpgsfwnh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.haohaochexian.top/Article/details/gtuvwunbxr.html

[S50] C++：格式化数字
来源：http://dali.xziqi.cn/Article/details/gtdxquqxoj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.birdmap.top/Article/details/gtrcwqapuh.html

[S51] C++：显式类型转换
来源：http://dali.yuxming.cn/Article/details/gtyxcojghk.html

static_cast<double>(a) / b
来源：http://dali.zhiwuduotai.top/Article/details/gtvkkpekmk.html

[S52] C++：const 与 noexcept
来源：http://dali.ybcxt.top/Article/details/gtwgeixtny.html

int size() const noexcept { return n_; }
来源：http://dali.bjfxy.top/Article/details/gtioglzkwb.html

[S53] C++：移动语义
来源：http://dali.haohaochexian.top/Article/details/gtymkebuhf.html

std::vector<int> w = std::move(v);
来源：http://dali.chenjidiqi.icu/Article/details/gtujpvbawi.html

[S54] C++：异常处理
来源：http://dali.yuxming.cn/Article/details/gtfhfrmagq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.nanxinkj.top/Article/details/gteyxxvovk.html

[S55] C++：结构化绑定
来源：http://dali.ydzc1.top/Article/details/gtgjzivwhg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.wangdashe.top/Article/details/gtdlwrrrlz.html

[S56] C++：optional
来源：http://dali.snrcjt.cn/Article/details/gtqdnkwlam.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hongshengwenyu.top/Article/details/gtrshagawt.html

[S57] C++：编译期常量
来源：http://dali.yanxiufei.cn/Article/details/gtsphxhctk.html

constexpr int N = 10;
来源：http://dali.shzxlz.cn/Article/details/gtmlzvvzqn.html

[S58] C++：命名空间
来源：http://dali.zhengqikj.top/Article/details/gtmsyuwabi.html

namespace ns { int f() { return 1; } }
来源：http://dali.316326.xyz/Article/details/gtbllodkas.html

[S59] C++：静态断言
来源：http://dali.jinghuilouyu.cn/Article/details/gtrsrgjmsz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yj20258888.top/Article/details/gtoqpkvxfw.html

[S60] C++：遍历并删除元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtboqoleqk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.wangdashe.top/Article/details/gttgbbqesj.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtgtsgplks.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gzhubu.top/Article/details/gtyvumdmmo.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtulfhlzlj.html

[T01] Kotlin：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvzaesskj.html

println("Hello")
来源：http://dali.jiagoushi.top/Article/details/gtggbucwss.html

[T02] Kotlin：变量
来源：http://dali.iojbl.cn/Article/details/gtpnwtmhos.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.316326.xyz/Article/details/gtklnxhbgb.html

[T03] Kotlin：字符串模板
来源：http://dali.zhixingplan.top/Article/details/gtacohpdle.html

"值: $b"
来源：http://dali.yueranfly.top/Article/details/gtfkdwbpyp.html

[T04] Kotlin：空安全
来源：http://dali.vqdsnc.cn/Article/details/gtkorgkrrb.html

val n: String? = null;  n?.length
来源：http://dali.sxryk.cn/Article/details/gtuaeootyx.html

[T05] Kotlin：when 表达式
来源：http://dali.jianghu66.top/Article/details/gtyujqpprc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jiagoushi.top/Article/details/gtuqnuigjr.html

[T06] Kotlin：集合映射
来源：http://dali.birdmap.top/Article/details/gtgkrcpwpn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.snrcjt.cn/Article/details/gtvuvlpacu.html

[T07] Kotlin：集合过滤
来源：http://dali.tianlin.xyz/Article/details/gtietberfg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yanxiufei.cn/Article/details/gtptjpnvzk.html

[T08] Kotlin：数据类
来源：http://dali.pycfn.com/Article/details/gtaelitqen.html

data class User(val name: String, val age: Int)
来源：http://dali.chenjidiqi.icu/Article/details/gtvvfjosoh.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gtvhhxfsee.html

fun String.exclaim() = this + "!"
来源：http://dali.gaohongyu789.top/Article/details/gtjvgtuyqe.html

[T10] Kotlin：默认参数
来源：http://dali.zdqjudy.top/Article/details/gtzptsnjlf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.birdmap.top/Article/details/gtxmtnddwa.html

[T11] Kotlin：协程
来源：http://dali.vqdsnc.cn/Article/details/gtqoonabjc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xuanzx.com/Article/details/gtvytahwuu.html

[T12] Kotlin：解构声明
来源：http://dali.yuanzhike.top/Article/details/gtkjctjsay.html

val (a, b) = Pair(1, 2)
来源：http://dali.yvedp.cn/Article/details/gtqxeasbgd.html

[T13] Kotlin：只读 Map
来源：http://dali.tanke756.top/Article/details/gtyadurcvi.html

val m = mapOf("a" to 1)
来源：http://dali.jqgfzy.top/Article/details/gtnkakbjzh.html

[T14] Kotlin：循环
来源：http://dali.xuanzx.com/Article/details/gtueuywhuy.html

for (i in 1..10) println(i)
来源：http://dali.jiagoushi.top/Article/details/gtgdxztvnc.html

[T15] Kotlin：接口
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmyygzxlk.html

interface Shape { fun area(): Double }
来源：http://dali.xuanzx.com/Article/details/gtcbjytyaa.html

[T16] Swift：Hello World
来源：http://dali.tian-w.cn/Article/details/gtuasusxel.html

print("Hello")
来源：http://dali.gzhubu.top/Article/details/gtizciquyy.html

[T17] Swift：变量与常量
来源：http://dali.9152youxi.cn/Article/details/gtaqbqnlnd.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gtufkayqcc.html

[T18] Swift：字符串插值
来源：http://dali.zhoulong.xyz/Article/details/gtmoghifix.html

"值: \(b)"
来源：http://dali.yonumen.top/Article/details/gtvxbvfmvb.html

[T19] Swift：可选绑定
来源：http://dali.quarkkingdee.top/Article/details/gtnfoetnmb.html

if let n = opt { print(n) }
来源：http://dali.zhixingplan.top/Article/details/gtzgpndybi.html

[T20] Swift：数组操作
来源：http://dali.sxryk.cn/Article/details/gtyetkiyap.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.chenlongwang.top/Article/details/gthzpisopq.html

[T21] Swift：遍历
来源：http://dali.zhixingplan.top/Article/details/gtpliyvxbb.html

for x in a { print(x) }
来源：http://dali.cheryme.top/Article/details/gthlpzmjzp.html

[T22] Swift：字典
来源：http://dali.guowangkeji.top/Article/details/gtjeaghosb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cheryme.top/Article/details/gtmkjfnisy.html

[T23] Swift：函数
来源：http://dali.svipenyu.cn/Article/details/gtadppzxsf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhongyouzk.top/Article/details/gtcmllwblr.html

[T24] Swift：闭包
来源：http://dali.tian-w.cn/Article/details/gtpttkgxon.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.aibaodan.cn/Article/details/gtvgrtssbq.html

[T25] Swift：结构体
来源：http://dali.hongshengwenyu.top/Article/details/gtzcwalaqb.html

struct P { var x: Int }
来源：http://dali.aibaodan.cn/Article/details/gthoahqalq.html

[T26] Swift：类与重写
来源：http://dali.shuidangran.top/Article/details/gtgsgvaunn.html

class A: Base { override func f() {} }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmfsrujra.html

[T27] Swift：错误处理
来源：http://dali.jyoumei.cn/Article/details/gtlwiqsecx.html

do { try f() } catch { print(error) }
来源：http://dali.9152youxi.cn/Article/details/gtihyyyjxi.html

[T28] Swift：枚举
来源：http://dali.gzhubu.top/Article/details/gtmdlifgts.html

enum Color { case red, green }
来源：http://dali.pengpengdd.cyou/Article/details/gtrkmposfv.html

[T29] Swift：guard 提前返回
来源：http://dali.0kj1m.cn/Article/details/gtpplurica.html

guard let x = opt else { return }
来源：http://dali.yuanzhike.top/Article/details/gthoymtjca.html

[T30] Swift：协议
来源：http://dali.tanke756.top/Article/details/gtpvmxouyl.html

protocol Shape { func area() -> Double }
来源：http://dali.sxryk.cn/Article/details/gtwmwzwlxs.html

[T31] Lua：Hello World
来源：http://dali.316326.xyz/Article/details/gtpdzagozz.html

print("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtxswisbnw.html

[T32] Lua：局部变量
来源：http://dali.pengpengdd.cyou/Article/details/gtkabuwcwn.html

local a = 1
来源：http://dali.yvedp.cn/Article/details/gtlexcyekq.html

[T33] Lua：表（数组）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqxjxatvg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhoulong.xyz/Article/details/gtieeufgaq.html

[T34] Lua：遍历表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpclusmlq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.vqdsnc.cn/Article/details/gtqyfavwif.html

[T35] Lua：字典表
来源：http://dali.hnxiangtu.top/Article/details/gtnqqekuwo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cashguo.top/Article/details/gtpvqvvvvr.html

[T36] Lua：函数
来源：http://dali.chenzaomai.com/Article/details/gttqwmlafl.html

function add(a, b) return a + b end
来源：http://dali.xinyue.icu/Article/details/gtetmweizz.html

[T37] Lua：字符串拼接
来源：http://dali.zhoulong.xyz/Article/details/gtvkjxwkkq.html

"a" .. "b"
来源：http://dali.guowangkeji.top/Article/details/gtccdofmho.html

[T38] Lua：条件
来源：http://dali.aizwys.cn/Article/details/gttvcedcfq.html

if x > 0 then print("正") end
来源：http://dali.meibo888.top/Article/details/gtrqauvpiv.html

[T39] Lua：模式匹配
来源：http://dali.jinqigufen.top/Article/details/gtshxidexv.html

string.find(s, "%d+")
来源：http://dali.pengpengdd.cyou/Article/details/gtydnhzank.html

[T40] Lua：元表
来源：http://dali.shzxlz.cn/Article/details/gtncwhtuxz.html

setmetatable({}, { __index = base })
来源：http://dali.fzhhl.top/Article/details/gtjmzobjbe.html

[T41] Perl：Hello World
来源：http://dali.daria6918.cn/Article/details/gtkfybllhq.html

print "Hello\n";
来源：http://dali.jianghu66.top/Article/details/gtiydquuzx.html

[T42] Perl：变量类型
来源：http://dali.ydzc1.top/Article/details/gtrfxdexfl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ybcxt.top/Article/details/gtyyjmlrhq.html

[T43] Perl：字符串插值
来源：http://dali.iojbl.cn/Article/details/gtdeqocbie.html

"值: $a"
来源：http://dali.guannengcc.top/Article/details/gtwfybnysb.html

[T44] Perl：条件
来源：http://dali.bjfxy.top/Article/details/gtgnlkyrkh.html

if ($a > 0) { print "正"; }
来源：http://dali.zhengqikj.top/Article/details/gtuqqqlxki.html

[T45] Perl：数组遍历
来源：http://dali.hammf.cn/Article/details/gttxeabmgo.html

for my $x (@arr) { print $x; }
来源：http://dali.zhengqikj.top/Article/details/gtvrdgkpyj.html

[T46] Perl：哈希操作
来源：http://dali.cqqwz.cn/Article/details/gtsihjzykp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.quarkkingdee.top/Article/details/gtjkpidjtd.html

[T47] Perl：正则捕获
来源：http://dali.nwbrower.top/Article/details/gtxtkpfcsi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.gogol.net.cn/Article/details/gtapsixzns.html

[T48] Perl：正则替换
来源：http://dali.sweek.top/Article/details/gtokenpyal.html

$s =~ s/old/new/g;
来源：http://dali.havefunace.top/Article/details/gtalueyvjf.html

[T49] Perl：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtvudifqbg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cqqwz.cn/Article/details/gtqcnktxhw.html

[T50] Perl：逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gtwqhghhrq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gzhubu.top/Article/details/gtqyiuwnfs.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.chenlongwang.top/Article/details/gtjyztfayu.html

[T51] Scala：Hello World
来源：http://dali.sufxvd.cn/Article/details/gteyqkruxs.html

println("Hello")
来源：http://dali.gogol.net.cn/Article/details/gtrpldionv.html

[T52] Scala：变量
来源：http://dali.gogol.net.cn/Article/details/gtulrxozow.html

val a = 1;  var b = 2
来源：http://dali.yanxiufei.cn/Article/details/gtslsaxmkw.html

[T53] Scala：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gtvvsofdwl.html

s"值: $b"
来源：http://dali.tian-w.cn/Article/details/gtvetnfdic.html

[T54] Scala：集合映射
来源：http://dali.hnqzz.top/Article/details/gtbsdqdprf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.dianchejie.cn/Article/details/gtenjjbhlc.html

[T55] Scala：集合过滤
来源：http://dali.shangyingyoupin.top/Article/details/gthxzobpys.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zycfv.cn/Article/details/gtzcklbfhl.html

[T56] Scala：样例类
来源：http://dali.gaohongyu789.top/Article/details/gtrapbmikk.html

case class User(name: String, age: Int)
来源：http://dali.dashuyun.cn/Article/details/gtgorlekep.html

[T57] Scala：模式匹配
来源：http://dali.birdmap.top/Article/details/gtbdhssxps.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.pycfn.com/Article/details/gtlaccgmun.html

[T58] Scala：函数定义
来源：http://dali.jqgfzy.top/Article/details/gtwzqfsvke.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwlnxjfly.html

[T59] Scala：循环
来源：http://dali.hnqzz.top/Article/details/gtbggmwqwl.html

for (i <- 1 to 10) println(i)
来源：http://dali.cheryme.top/Article/details/gtzihvptsp.html

[T60] Scala：折叠
来源：http://dali.daxiang520.top/Article/details/gtbiwbptbj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.pengpengdd.cyou/Article/details/gtosmaldti.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtkdcbhtno.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.bjfxy.top/Article/details/gttzszqjio.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtlljwjsio.html

[U01] Py：创建虚拟环境
来源：http://dali.daria6918.cn/Article/details/gtshsywcuj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yj202588.top/Article/details/gtckuagtbm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xziqi.cn/Article/details/gtlaynxlna.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.daria6918.cn/Article/details/gtirvmxads.html

[U03] Py：加载 .env 配置
来源：http://dali.ehwqpu.com/Article/details/gtqtlfvdlk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jyoumei.cn/Article/details/gtckoalirt.html

[U04] Py：变量调试打印
来源：http://dali.haohaochexian.top/Article/details/gtwtznplrq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hammf.cn/Article/details/gtathygjsb.html

[U05] Py：列表去重且保序
来源：http://dali.hongshengwenyu.top/Article/details/gtxonofuze.html

list(dict.fromkeys(arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtckvexkpg.html

[U06] Py：合并两个字典
来源：http://dali.fengsongda.top/Article/details/gtkrsjnohe.html

{**a, **b}
来源：http://dali.aibaodan.cn/Article/details/gtlukwbxvv.html

[U07] Py：反转字典键值
来源：http://dali.smart0.xyz/Article/details/gtbrcdwloh.html

{v: k for k, v in d.items()}
来源：http://dali.zdqjudy.top/Article/details/gtgzibctwu.html

[U08] Py：展平二维列表
来源：http://dali.0kj1m.cn/Article/details/gthgtwyaza.html

[y for x in nested for y in x]
来源：http://dali.ppjwa.cn/Article/details/gtydtjcyst.html

[U09] Py：字典取最大值的键
来源：http://dali.ydzc1.top/Article/details/gtpqujtkkw.html

max(d, key=d.get)
来源：http://dali.sxryk.cn/Article/details/gthsukqtfq.html

[U10] Py：按值排序字典
来源：http://dali.fengsongda.top/Article/details/gtugelgake.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xziqi.cn/Article/details/gthzaujffh.html

[U11] Py：生成器表达式
来源：http://dali.xuetiantiany.cn/Article/details/gtvcbremtv.html

(x * 2 for x in arr)
来源：http://dali.jinqigfzy.top/Article/details/gtwgwwkxvq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.316326.xyz/Article/details/gtgeyjixgk.html

Counter(arr).most_common(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmncsqavi.html

[U13] Py：固定长度队列
来源：http://dali.jlsjyb.cn/Article/details/gthafkpuvr.html

deque(maxlen=10)
来源：http://dali.daxiang520.top/Article/details/gtmqzxqcbr.html

[U14] Py：分组收集到列表
来源：http://dali.shanyushiyangtech.top/Article/details/gtrhwqhohb.html

defaultdict(list)
来源：http://dali.iojbl.cn/Article/details/gtuiqsmksf.html

[U15] Py：高精度计时
来源：http://dali.xziqi.cn/Article/details/gtsboznzwu.html

t = time.perf_counter()
来源：http://dali.jianghu66.top/Article/details/gttmgkuhob.html

[U16] Py：命令行参数解析
来源：http://dali.316326.xyz/Article/details/gtxuevfoti.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.c1oappe.top/Article/details/gtmnizuvbt.html

[U17] Py：初始化日志
来源：http://dali.sysykeji.top/Article/details/gtkicbkgnb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.tianlin.xyz/Article/details/gtjnqwmbad.html

[U18] Py：预编译正则
来源：http://dali.9152youxi.cn/Article/details/gtaqcgnlif.html

pat = re.compile(r"\d+")
来源：http://dali.chenzaomai.com/Article/details/gthmogpjcj.html

[U19] Py：正则替换带回调
来源：http://dali.guannengcc.top/Article/details/gtqvxamhul.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zycfv.cn/Article/details/gtadsbeblw.html

[U20] Py：缓存函数结果
来源：http://dali.wangshuangyany.cn/Article/details/gtmojqdehe.html

@functools.lru_cache(maxsize=None)
来源：http://dali.nwbrower.top/Article/details/gtqxfkjulj.html

[U21] Py：自定义上下文管理器
来源：http://dali.yangfankeji.com/Article/details/gtbbgiafcr.html

@contextlib.contextmanager
来源：http://dali.havefunace.top/Article/details/gtqiacumpw.html

[U22] Py：矩阵转置
来源：http://dali.yj202588.top/Article/details/gtoryrvvsf.html

list(zip(*m))
来源：http://dali.zhixingplan.top/Article/details/gtdcgdkgas.html

[U23] Py：分块读取大文件
来源：http://dali.zhongyouzk.top/Article/details/gtmgzenndr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hongshengwenyu.top/Article/details/gtuluxgjrb.html

[U24] Py：路径操作
来源：http://dali.cqqwz.cn/Article/details/gtwmjzirlh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtcuzhatmx.html

[U25] Py：CSV 按字典读
来源：http://dali.sysykeji.top/Article/details/gtytrvfhrv.html

csv.DictReader(f)
来源：http://dali.c1oappe.top/Article/details/gtcdiovnta.html

[U26] Py：并发下载
来源：http://dali.svipenyu.cn/Article/details/gtamvpjmzt.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.daria6918.cn/Article/details/gtgjxkatms.html

[U27] Py：异步 HTTP
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfonairib.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.gotoacloud.top/Article/details/gtclixaqwr.html

[U28] Py：类型别名
来源：http://dali.gzhubu.top/Article/details/gtaexaxgle.html

UserId = int
来源：http://dali.shanyushiyangtech.top/Article/details/gtcsexyopp.html

[U29] Py：属性校验
来源：http://dali.hywenlv.cn/Article/details/gtlyescaxo.html

@property 与 @x.setter 配合
来源：http://dali.sufxvd.cn/Article/details/gtxhloeahs.html

[U30] Py：数据类
来源：http://dali.jiagoushi.top/Article/details/gtluwmihcw.html

@dataclass(slots=True)
来源：http://dali.fzhhl.top/Article/details/gtxpytenwl.html


<!-- 参考信息 -->