代发 wailian999

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.c1oappe.top/Article/details/gtdgqkznsg.html

[S08] C：动态内存分配与释放
来源：http://dali.shanyushiyangkeji.top/Article/details/gtetwsphex.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cdnleiting.top/Article/details/gtfcnyjceo.html

[S09] C：结构体定义与初始化
来源：http://dali.redwolf501.top/Article/details/gtnhyupifr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.meibo888.top/Article/details/gtxagwrnli.html

[S10] C：指针与解引用
来源：http://dali.svipenyu.cn/Article/details/gtdbkezxad.html

int *p = &a;  *p = 5;
来源：http://dali.yuxming.cn/Article/details/gtpgttqjlt.html

[S11] C：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gtwwlnxcus.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gzhubu.top/Article/details/gtzyubpkgt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cdnleiting.top/Article/details/gtzkcjgdwp.html

fclose(f);
来源：http://dali.gogol.net.cn/Article/details/gtzkjxmdvf.html

[S12] C：写文件
来源：http://dali.shzxlz.cn/Article/details/gtyjoxrbuf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.feifeiyinyue.top/Article/details/gtlprdmzrx.html

[S13] C：宏定义
来源：http://dali.svipenyu.cn/Article/details/gtraamznzf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.haohaochexian.top/Article/details/gtoagicvbp.html

[S14] C：枚举
来源：http://dali.nanxuanxn.top/Article/details/gtsfmnqhap.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.nanxuanxn.top/Article/details/gtgvvdtcez.html

[S15] C：类型转换
来源：http://dali.gaohongyu789.top/Article/details/gtawizakqy.html

(double) a / b
来源：http://dali.xylfe.cn/Article/details/gtcuuvmhhd.html

[S16] C：位操作置位
来源：http://dali.nwbrower.top/Article/details/gtzdiebpii.html

x |= (1 << 3);
来源：http://dali.bjfxy.top/Article/details/gtfrszomwv.html

[S17] C：安全拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gtjadwrhsq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.9152youxi.cn/Article/details/gtocnqgqmf.html

[S18] C：命令行参数
来源：http://dali.nwbrower.top/Article/details/gtiuowmvik.html

int main(int argc, char **argv)
来源：http://dali.chenlongwang.top/Article/details/gthldjbbkw.html

[S19] C：快速排序
来源：http://dali.birdmap.top/Article/details/gttcptbyci.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ivvv.top/Article/details/gtjvftbcge.html

[S20] C：二分查找
来源：http://dali.zdqjudy.top/Article/details/gtlkdolsfw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ivvv.top/Article/details/gtmlboswwt.html

[S21] C：字符类别判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmsjtvtoq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cucudq.cn/Article/details/gtftwssabr.html

[S22] C：字符串转数字
来源：http://dali.yangfankeji.com/Article/details/gtkvbhwdce.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yonumen.top/Article/details/gtgcgnhngx.html

[S23] C：随机数
来源：http://dali.xuanzx.com/Article/details/gtorcyqifs.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jlsjyb.cn/Article/details/gtbjimqwwp.html

[S24] C：获取本地时间
来源：http://dali.ybcxt.top/Article/details/gthyqnrauw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.bjfxy.top/Article/details/gtrzylbglh.html

[S25] C：内存拷贝
来源：http://dali.guowangkeji.top/Article/details/gtseyjdybh.html

memcpy(dst, src, n);
来源：http://dali.hfpthk.cn/Article/details/gtuwsyvqxe.html

[S26] C：内存清零
来源：http://dali.yonumen.top/Article/details/gtsqxwuvur.html

memset(a, 0, sizeof a);
来源：http://dali.yanxiufei.cn/Article/details/gttvfiezyo.html

[S27] C：定义常量
来源：http://dali.xuetiantiany.cn/Article/details/gtpmqarqoi.html

const double PI = 3.14159;
来源：http://dali.316326.xyz/Article/details/gtieiluoeh.html

[S28] C：静态变量
来源：http://dali.gotoacloud.top/Article/details/gtqfwpbpfo.html

static int counter = 0;
来源：http://dali.hfpthk.cn/Article/details/gtetedpcld.html

[S29] C：变参函数
来源：http://dali.wangshuangyany.cn/Article/details/gtizhhuzzr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hongshengwenyu.top/Article/details/gteoiovoev.html

[S30] C：头文件保护
来源：http://dali.hywenlv.cn/Article/details/gtnicrreia.html

#ifndef X_H
来源：http://dali.bjfxy.top/Article/details/gtpiccftuy.html

#define X_H
来源：http://dali.gzhubu.top/Article/details/gtubovmzfi.html

#endif
来源：http://dali.meibo888.top/Article/details/gtxgckonxf.html

[S31] C++：Hello World
来源：http://dali.yvedp.cn/Article/details/gtevwrvrku.html

#include <iostream>
来源：http://dali.cashguo.top/Article/details/gtuzrxzkud.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shzxlz.cn/Article/details/gtqdtakuxz.html

[S32] C++：字符串
来源：http://dali.jyoumei.cn/Article/details/gtrloafafu.html

std::string s = "hi";  s += "!";
来源：http://dali.hammf.cn/Article/details/gtlhfihmdp.html

[S33] C++：vector 增删
来源：http://dali.sufxvd.cn/Article/details/gtorwxopqx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj20258888.top/Article/details/gtjpfrrvrr.html

[S34] C++：遍历 vector
来源：http://dali.yuxming.cn/Article/details/gtzodxmacu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yongpay.top/Article/details/gtreeufije.html

[S35] C++：map
来源：http://dali.jianghu66.top/Article/details/gtceuffhqm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtjhoqpolm.html

[S36] C++：unordered_map
来源：http://dali.aizwys.cn/Article/details/gtfagmrlfm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ybcxt.top/Article/details/gtwbmepgdf.html

[S37] C++：set
来源：http://dali.hnqzz.top/Article/details/gttcbwhher.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hammf.cn/Article/details/gtccmlzdrq.html

[S38] C++：排序
来源：http://dali.dianchejie.cn/Article/details/gtojsbluqh.html

std::sort(v.begin(), v.end());
来源：http://dali.cashguo.top/Article/details/gtxlttghxh.html

[S39] C++：自定义比较器排序
来源：http://dali.feifeiyinyue.top/Article/details/gtoarwqsir.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sxryk.cn/Article/details/gtyqfwozfk.html

[S40] C++：查找元素
来源：http://dali.cashguo.top/Article/details/gtluptqxpu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yuxming.cn/Article/details/gtehheiael.html

[S41] C++：类与构造函数
来源：http://dali.c1oappe.top/Article/details/gtwvzlarxt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yongpay.top/Article/details/gtujhdhehe.html

[S42] C++：继承与虚函数
来源：http://dali.xuanzx.com/Article/details/gtkgmjheex.html

class B : public Base { public: void f() override {} };
来源：http://dali.jqgfzy.top/Article/details/gtobdsqnfp.html

[S43] C++：智能指针
来源：http://dali.zhoulong.xyz/Article/details/gtsgdlgjmc.html

auto p = std::make_unique<int>(5);
来源：http://dali.hywenlv.cn/Article/details/gtoeicvupx.html

[S44] C++：引用传参
来源：http://dali.daria6918.cn/Article/details/gtdnljofxm.html

void inc(int &x) { ++x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgalhtpmj.html

[S45] C++：lambda
来源：http://dali.hnqzz.top/Article/details/gtbygfxmlk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nwbrower.top/Article/details/gtqbuzbjbq.html

[S46] C++：函数模板
来源：http://dali.chenzaomai.com/Article/details/gtwlskstog.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.dashuyun.cn/Article/details/gtdsojywtv.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj20258888.top/Article/details/gtysabnvnv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.316326.xyz/Article/details/gtqdvtlokk.html

[S48] C++：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gtheauohbl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinghuilouyu.cn/Article/details/gtxckildrf.html

while (std::getline(in, line)) { }
来源：http://dali.dashuyun.cn/Article/details/gtrdyzbpyu.html

[S49] C++：写文件
来源：http://dali.cucudq.cn/Article/details/gthmchjexn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gotoacloud.top/Article/details/gtzhvljqih.html

[S50] C++：格式化数字
来源：http://dali.jiagoushi.top/Article/details/gtwvdturms.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gtmrbkifcx.html

[S51] C++：显式类型转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkymsrwh.html

static_cast<double>(a) / b
来源：http://dali.nanxuanxn.top/Article/details/gtqqjeghsj.html

[S52] C++：const 与 noexcept
来源：http://dali.redwolf501.top/Article/details/gtytgdzngz.html

int size() const noexcept { return n_; }
来源：http://dali.shuidangran.top/Article/details/gtdfmcxkdv.html

[S53] C++：移动语义
来源：http://dali.yvedp.cn/Article/details/gtqwkqsgoo.html

std::vector<int> w = std::move(v);
来源：http://dali.sxryk.cn/Article/details/gtpwdwjhtm.html

[S54] C++：异常处理
来源：http://dali.havefunace.top/Article/details/gthlnluhjr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenzaomai.com/Article/details/gtdndrsarj.html

[S55] C++：结构化绑定
来源：http://dali.hnqzz.top/Article/details/gtznxsclld.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.tianlin.xyz/Article/details/gtkpvgwpnu.html

[S56] C++：optional
来源：http://dali.andypj.xyz/Article/details/gtrdemajah.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sufxvd.cn/Article/details/gtjuppsuyu.html

[S57] C++：编译期常量
来源：http://dali.xziqi.cn/Article/details/gthniadzfi.html

constexpr int N = 10;
来源：http://dali.ivvv.top/Article/details/gtgtkbcnbp.html

[S58] C++：命名空间
来源：http://dali.ivvv.top/Article/details/gtddeuxztv.html

namespace ns { int f() { return 1; } }
来源：http://dali.yongpay.top/Article/details/gtcuaxttvy.html

[S59] C++：静态断言
来源：http://dali.zdqjudy.top/Article/details/gtnscixbkr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shuidangran.top/Article/details/gtbwendwlq.html

[S60] C++：遍历并删除元素
来源：http://dali.jyoumei.cn/Article/details/gtwrpvcjbi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj20258888.top/Article/details/gtceuimgba.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtqrouheis.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tanke756.top/Article/details/gtiqiqcedh.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtvtldbxcw.html

[T01] Kotlin：Hello World
来源：http://dali.cashguo.top/Article/details/gtumyfiwys.html

println("Hello")
来源：http://dali.zdqjudy.top/Article/details/gtrunmgyon.html

[T02] Kotlin：变量
来源：http://dali.tianlin.xyz/Article/details/gtwfbxelsg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shangyingyoupin.top/Article/details/gtjjcnpuum.html

[T03] Kotlin：字符串模板
来源：http://dali.xziqi.cn/Article/details/gtpobyjngd.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gtpchchgad.html

[T04] Kotlin：空安全
来源：http://dali.ivvv.top/Article/details/gthlezixsg.html

val n: String? = null;  n?.length
来源：http://dali.shzxlz.cn/Article/details/gtytgrjvzb.html

[T05] Kotlin：when 表达式
来源：http://dali.daxiang520.top/Article/details/gtyqgizhsu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.redwolf501.top/Article/details/gtdkxghtye.html

[T06] Kotlin：集合映射
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlhqagtvt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.andypj.xyz/Article/details/gtsgryqayq.html

[T07] Kotlin：集合过滤
来源：http://dali.shuidangran.top/Article/details/gthnbyzadq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.fzhhl.top/Article/details/gtmilrrixu.html

[T08] Kotlin：数据类
来源：http://dali.tianlin.xyz/Article/details/gtkajkovbf.html

data class User(val name: String, val age: Int)
来源：http://dali.hywenlv.cn/Article/details/gttbdfxaju.html

[T09] Kotlin：扩展函数
来源：http://dali.c1oappe.top/Article/details/gtlrlacabp.html

fun String.exclaim() = this + "!"
来源：http://dali.jinghuilouyu.cn/Article/details/gthcudscct.html

[T10] Kotlin：默认参数
来源：http://dali.dianchejie.cn/Article/details/gtuuxjxtrt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.aizwys.cn/Article/details/gtakagvgva.html

[T11] Kotlin：协程
来源：http://dali.tianlin.xyz/Article/details/gtdulbrwql.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xuetiantiany.cn/Article/details/gtxbegseqz.html

[T12] Kotlin：解构声明
来源：http://dali.zdqjudy.top/Article/details/gtiqoaufkk.html

val (a, b) = Pair(1, 2)
来源：http://dali.andypj.xyz/Article/details/gtoqiovhfc.html

[T13] Kotlin：只读 Map
来源：http://dali.guowangkeji.top/Article/details/gtzvlwajmt.html

val m = mapOf("a" to 1)
来源：http://dali.redwolf501.top/Article/details/gtwacamllc.html

[T14] Kotlin：循环
来源：http://dali.cucudq.cn/Article/details/gtxoclkbno.html

for (i in 1..10) println(i)
来源：http://dali.xziqi.cn/Article/details/gtthzckiqc.html

[T15] Kotlin：接口
来源：http://dali.guowangkeji.top/Article/details/gtosjcindc.html

interface Shape { fun area(): Double }
来源：http://dali.hongshengwenyu.top/Article/details/gtgecizkfo.html

[T16] Swift：Hello World
来源：http://dali.sweek.top/Article/details/gtldjvyfje.html

print("Hello")
来源：http://dali.yj202588.top/Article/details/gtptfkbwhw.html

[T17] Swift：变量与常量
来源：http://dali.redwolf501.top/Article/details/gtkscwkxvi.html

var a = 1;  let b = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtkusmlzxz.html

[T18] Swift：字符串插值
来源：http://dali.guowangkeji.top/Article/details/gtovimdbnb.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gtzoxhkmkd.html

[T19] Swift：可选绑定
来源：http://dali.chenzaomai.com/Article/details/gtnaiovona.html

if let n = opt { print(n) }
来源：http://dali.pycfn.com/Article/details/gtxoqgbobg.html

[T20] Swift：数组操作
来源：http://dali.svipenyu.cn/Article/details/gtdjvozjcy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.mhx1999.top/Article/details/gtwtctsxbi.html

[T21] Swift：遍历
来源：http://dali.c1oappe.top/Article/details/gtplveigro.html

for x in a { print(x) }
来源：http://dali.dashuyun.cn/Article/details/gtfzptamfx.html

[T22] Swift：字典
来源：http://dali.jyoumei.cn/Article/details/gtodnoqsah.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jiagoushi.top/Article/details/gtpfyzraoe.html

[T23] Swift：函数
来源：http://dali.yuxming.cn/Article/details/gtgnkvgveq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxilsuxyk.html

[T24] Swift：闭包
来源：http://dali.snrcjt.cn/Article/details/gtnsxbzseo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtwwpnbcas.html

[T25] Swift：结构体
来源：http://dali.nanxinkj.top/Article/details/gtuyrneppi.html

struct P { var x: Int }
来源：http://dali.kuanghao11.cn/Article/details/gtcvopupft.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gtrtbhaucl.html

class A: Base { override func f() {} }
来源：http://dali.gotoacloud.top/Article/details/gtggnlcbtl.html

[T27] Swift：错误处理
来源：http://dali.aibaodan.cn/Article/details/gtqmeornwh.html

do { try f() } catch { print(error) }
来源：http://dali.wangshuangyany.cn/Article/details/gtadjmcsac.html

[T28] Swift：枚举
来源：http://dali.zhengqikj.top/Article/details/gtpypncmpy.html

enum Color { case red, green }
来源：http://dali.shangyingyoupin.top/Article/details/gtevofwvpl.html

[T29] Swift：guard 提前返回
来源：http://dali.gotoacloud.top/Article/details/gtuhdfhtme.html

guard let x = opt else { return }
来源：http://dali.hysaishi.cn/Article/details/gtdubhfejf.html

[T30] Swift：协议
来源：http://dali.meibo888.top/Article/details/gtotxothiw.html

protocol Shape { func area() -> Double }
来源：http://dali.xziqi.cn/Article/details/gtnfwsuiwh.html

[T31] Lua：Hello World
来源：http://dali.ivvv.top/Article/details/gtupfyndul.html

print("Hello")
来源：http://dali.tian-w.cn/Article/details/gtuzpbgjrm.html

[T32] Lua：局部变量
来源：http://dali.gzhubu.top/Article/details/gtvwunmtkh.html

local a = 1
来源：http://dali.snrcjt.cn/Article/details/gtfubeovly.html

[T33] Lua：表（数组）
来源：http://dali.fzhhl.top/Article/details/gtfztlsvqj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yuxming.cn/Article/details/gtxudsgrce.html

[T34] Lua：遍历表
来源：http://dali.chenlongwang.top/Article/details/gtwbtvbvzd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nanxinkj.top/Article/details/gtaylkvinm.html

[T35] Lua：字典表
来源：http://dali.feifeiyinyue.top/Article/details/gtuouhzznt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cucudq.cn/Article/details/gtzbqxxapv.html

[T36] Lua：函数
来源：http://dali.dianchejie.cn/Article/details/gtalewyyfb.html

function add(a, b) return a + b end
来源：http://dali.chenzaomai.com/Article/details/gttiviuyhm.html

[T37] Lua：字符串拼接
来源：http://dali.fengsongda.top/Article/details/gtkdnxceck.html

"a" .. "b"
来源：http://dali.yueranfly.top/Article/details/gtsgrqsidx.html

[T38] Lua：条件
来源：http://dali.hysaishi.cn/Article/details/gttlzvdcjx.html

if x > 0 then print("正") end
来源：http://dali.9152youxi.cn/Article/details/gtxturilmh.html

[T39] Lua：模式匹配
来源：http://dali.yongpay.top/Article/details/gtmfywospk.html

string.find(s, "%d+")
来源：http://dali.jlsjyb.cn/Article/details/gtmkcrczzb.html

[T40] Lua：元表
来源：http://dali.gogol.net.cn/Article/details/gtbuijaflz.html

setmetatable({}, { __index = base })
来源：http://dali.andypj.xyz/Article/details/gtpfrdezna.html

[T41] Perl：Hello World
来源：http://dali.yueranfly.top/Article/details/gtkxghbbbm.html

print "Hello\n";
来源：http://dali.316326.xyz/Article/details/gtetdpsuel.html

[T42] Perl：变量类型
来源：http://dali.meibo888.top/Article/details/gtwtyydysb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.mhx1999.top/Article/details/gtyzbdoyhl.html

[T43] Perl：字符串插值
来源：http://dali.yj202588.top/Article/details/gtjrkqmnya.html

"值: $a"
来源：http://dali.hnqzz.top/Article/details/gtywueebtk.html

[T44] Perl：条件
来源：http://dali.yongpay.top/Article/details/gtwdtbvomg.html

if ($a > 0) { print "正"; }
来源：http://dali.jianghu66.top/Article/details/gtabqccljv.html

[T45] Perl：数组遍历
来源：http://dali.0kj1m.cn/Article/details/gtsldyuzly.html

for my $x (@arr) { print $x; }
来源：http://dali.fzhhl.top/Article/details/gtxleionlz.html

[T46] Perl：哈希操作
来源：http://dali.zhoulong.xyz/Article/details/gtsisxhvov.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.birdmap.top/Article/details/gtmnmqkqxy.html

[T47] Perl：正则捕获
来源：http://dali.hfpthk.cn/Article/details/gtjwryihrw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jyoumei.cn/Article/details/gtkkdsvedp.html

[T48] Perl：正则替换
来源：http://dali.xuanzx.com/Article/details/gtdrmuwiuj.html

$s =~ s/old/new/g;
来源：http://dali.hnxiangtu.top/Article/details/gtlutavmwn.html

[T49] Perl：函数
来源：http://dali.gogol.net.cn/Article/details/gtanfqixwd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.pycfn.com/Article/details/gtccbtthdr.html

[T50] Perl：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gtinuwkzow.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zycfv.cn/Article/details/gtpirpenrp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.havefunace.top/Article/details/gtjghabeym.html

[T51] Scala：Hello World
来源：http://dali.tian-w.cn/Article/details/gtdeycluri.html

println("Hello")
来源：http://dali.nwbrower.top/Article/details/gtxydyvynn.html

[T52] Scala：变量
来源：http://dali.tianlin.xyz/Article/details/gtzcwpdlma.html

val a = 1;  var b = 2
来源：http://dali.daria6918.cn/Article/details/gtotrhwcum.html

[T53] Scala：字符串插值
来源：http://dali.chenlongwang.top/Article/details/gthjcxyein.html

s"值: $b"
来源：http://dali.snrcjt.cn/Article/details/gtwnhcnkgk.html

[T54] Scala：集合映射
来源：http://dali.xuetiantiany.cn/Article/details/gtfnevlmla.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hnqzz.top/Article/details/gtqjggkdpx.html

[T55] Scala：集合过滤
来源：http://dali.hfpthk.cn/Article/details/gtlqyffngw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hfpthk.cn/Article/details/gttpljkgmy.html

[T56] Scala：样例类
来源：http://dali.daria6918.cn/Article/details/gtuhccnbrk.html

case class User(name: String, age: Int)
来源：http://dali.iojbl.cn/Article/details/gtcckbawdv.html

[T57] Scala：模式匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtleblojun.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ehwqpu.com/Article/details/gthtplbhtf.html

[T58] Scala：函数定义
来源：http://dali.cucudq.cn/Article/details/gtfcgcprlg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xziqi.cn/Article/details/gtzdnoqsym.html

[T59] Scala：循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrybingej.html

for (i <- 1 to 10) println(i)
来源：http://dali.guannengcc.top/Article/details/gtcmcqjykl.html

[T60] Scala：折叠
来源：http://dali.chenjidiqi.icu/Article/details/gtvmybxryc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cheryme.top/Article/details/gtzifqiecr.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtmqlbthhy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.daxiang520.top/Article/details/gtcdykizkg.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtrfptvloo.html

[U01] Py：创建虚拟环境
来源：http://dali.hywenlv.cn/Article/details/gtdckursrr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shangyingyoupin.top/Article/details/gtqxfaagwd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmvrjhnvh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jianghu66.top/Article/details/gtzobcpyzm.html

[U03] Py：加载 .env 配置
来源：http://dali.yongpay.top/Article/details/gtqmyabcts.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.meibo888.top/Article/details/gtuewehwyk.html

[U04] Py：变量调试打印
来源：http://dali.nwbrower.top/Article/details/gttwxxbzpd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhongyouzk.top/Article/details/gtceadplso.html

[U05] Py：列表去重且保序
来源：http://dali.shzxlz.cn/Article/details/gtnvorrvph.html

list(dict.fromkeys(arr))
来源：http://dali.yj202588.top/Article/details/gtqmnntpbq.html

[U06] Py：合并两个字典
来源：http://dali.iojbl.cn/Article/details/gthkujktrm.html

{**a, **b}
来源：http://dali.cheryme.top/Article/details/gtrirtyjrw.html

[U07] Py：反转字典键值
来源：http://dali.birdmap.top/Article/details/gtknzjnhpr.html

{v: k for k, v in d.items()}
来源：http://dali.xuanzx.com/Article/details/gtjedacfmk.html

[U08] Py：展平二维列表
来源：http://dali.vqdsnc.cn/Article/details/gtmutagilb.html

[y for x in nested for y in x]
来源：http://dali.gotoacloud.top/Article/details/gtkvmzsfxf.html

[U09] Py：字典取最大值的键
来源：http://dali.ppjwa.cn/Article/details/gtanmndqcu.html

max(d, key=d.get)
来源：http://dali.pengpengdd.cyou/Article/details/gtrnhnpjoi.html

[U10] Py：按值排序字典
来源：http://dali.daxiang520.top/Article/details/gthsdchcjd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gtvbdjfxyh.html

[U11] Py：生成器表达式
来源：http://dali.jlsjyb.cn/Article/details/gtogpvmuqp.html

(x * 2 for x in arr)
来源：http://dali.jinqigufen.top/Article/details/gtaxehmhwy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gogol.net.cn/Article/details/gtrfsmoqyc.html

Counter(arr).most_common(3)
来源：http://dali.yj20258888.top/Article/details/gtwnrzyyuw.html

[U13] Py：固定长度队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawbxgyul.html

deque(maxlen=10)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgzopdlko.html

[U14] Py：分组收集到列表
来源：http://dali.cqqwz.cn/Article/details/gteuqozpjx.html

defaultdict(list)
来源：http://dali.daria6918.cn/Article/details/gtnxhwnaoo.html

[U15] Py：高精度计时
来源：http://dali.shangyingyoupin.top/Article/details/gtakgaactv.html

t = time.perf_counter()
来源：http://dali.ivvv.top/Article/details/gtxycbipvv.html

[U16] Py：命令行参数解析
来源：http://dali.guannengcc.top/Article/details/gtxhvvbcgd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.wangshuangyany.cn/Article/details/gtjquugvhw.html

[U17] Py：初始化日志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjjvcvdgt.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xuetiantiany.cn/Article/details/gthflxwxwo.html

[U18] Py：预编译正则
来源：http://dali.yvedp.cn/Article/details/gtgygikbkl.html

pat = re.compile(r"\d+")
来源：http://dali.havefunace.top/Article/details/gtfpkrnffn.html

[U19] Py：正则替换带回调
来源：http://dali.nanxuanxn.top/Article/details/gtqomhnpnk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gtozyopwpe.html

[U20] Py：缓存函数结果
来源：http://dali.gogol.net.cn/Article/details/gtscwxabux.html

@functools.lru_cache(maxsize=None)
来源：http://dali.birdmap.top/Article/details/gtojrwczwc.html

[U21] Py：自定义上下文管理器
来源：http://dali.havefunace.top/Article/details/gtnpxkvevr.html

@contextlib.contextmanager
来源：http://dali.daria6918.cn/Article/details/gtznlewnhw.html

[U22] Py：矩阵转置
来源：http://dali.gotoacloud.top/Article/details/gtopfvpbtf.html

list(zip(*m))
来源：http://dali.316326.xyz/Article/details/gtlwedsgmn.html

[U23] Py：分块读取大文件
来源：http://dali.zhixingplan.top/Article/details/gttrrpekai.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shangyingyoupin.top/Article/details/gtjsxukwfo.html

[U24] Py：路径操作
来源：http://dali.svipenyu.cn/Article/details/gtqjhyoezz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yangfankeji.com/Article/details/gtylwqvhwo.html

[U25] Py：CSV 按字典读
来源：http://dali.nanxinkj.top/Article/details/gtpcjssepe.html

csv.DictReader(f)
来源：http://dali.quarkkingdee.top/Article/details/gtfcfqzpjt.html

[U26] Py：并发下载
来源：http://dali.zhiwuduotai.top/Article/details/gtvenijwca.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.iojbl.cn/Article/details/gtfjfolydh.html

[U27] Py：异步 HTTP
来源：http://dali.jyoumei.cn/Article/details/gtqkbrppha.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.gaohongyu789.top/Article/details/gthrvkxfjg.html

[U28] Py：类型别名
来源：http://dali.0kj1m.cn/Article/details/gtlwgayliq.html

UserId = int
来源：http://dali.tanke756.top/Article/details/gtipgjuyon.html

[U29] Py：属性校验
来源：http://dali.sweek.top/Article/details/gtwhjgyjxm.html

@property 与 @x.setter 配合
来源：http://dali.hammf.cn/Article/details/gtkqkmsnay.html

[U30] Py：数据类
来源：http://dali.yj20258.top/Article/details/gtjpqeszsd.html

@dataclass(slots=True)
来源：http://dali.nanxinkj.top/Article/details/gttelyelon.html


<!-- 参考信息 -->