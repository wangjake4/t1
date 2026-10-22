代发 wailian999

strlen(s)
来源：http://dali.zhongyouzk.top/Article/details/gtlcyfsuor.html

[S06] C：字符串比较
来源：http://dali.fengsongda.top/Article/details/gtsdjrzgue.html

strcmp(a, b) == 0
来源：http://dali.daxiang520.top/Article/details/gtomjkfoml.html

[S07] C：数组遍历求和
来源：http://dali.bjfxy.top/Article/details/gtthwpdvcm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.tianlin.xyz/Article/details/gtpnpkzlxk.html

[S08] C：动态内存分配与释放
来源：http://dali.guowangkeji.top/Article/details/gtblruinkq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinqigfzy.top/Article/details/gtqulkahod.html

[S09] C：结构体定义与初始化
来源：http://dali.haohaochexian.top/Article/details/gtvrpxipik.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.daxiang520.top/Article/details/gtcnkdmcxr.html

[S10] C：指针与解引用
来源：http://dali.yj20258.top/Article/details/gterwictay.html

int *p = &a;  *p = 5;
来源：http://dali.daxiang520.top/Article/details/gtzpfbdxnk.html

[S11] C：逐行读文件
来源：http://dali.yj20258888.top/Article/details/gtailozkck.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.wangshuangyany.cn/Article/details/gtejglqrbh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.mhx1999.top/Article/details/gtuasgwall.html

fclose(f);
来源：http://dali.pycfn.com/Article/details/gttqbsjrte.html

[S12] C：写文件
来源：http://dali.dashuyun.cn/Article/details/gtaijbbnuz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jqgfzy.top/Article/details/gtdvyxbmwo.html

[S13] C：宏定义
来源：http://dali.hammf.cn/Article/details/gtvawbapmg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.fzhhl.top/Article/details/gtttmoptft.html

[S14] C：枚举
来源：http://dali.zhixingplan.top/Article/details/gtjucgpiya.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hysaishi.cn/Article/details/gtrmlomdwk.html

[S15] C：类型转换
来源：http://dali.feifeiyinyue.top/Article/details/gtletdzsxx.html

(double) a / b
来源：http://dali.cashguo.top/Article/details/gtwafwaqyb.html

[S16] C：位操作置位
来源：http://dali.shuidangran.top/Article/details/gtwojwanxg.html

x |= (1 << 3);
来源：http://dali.redwolf501.top/Article/details/gtgzkewndy.html

[S17] C：安全拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gttiseufct.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.tianlin.xyz/Article/details/gteihccqsb.html

[S18] C：命令行参数
来源：http://dali.mhx1999.top/Article/details/gtineebphw.html

int main(int argc, char **argv)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwnnycrup.html

[S19] C：快速排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxlpzhwu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtabmxuoqo.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gtwapufnjo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jqgfzy.top/Article/details/gtttjscuye.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gtchyqevkp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tian-w.cn/Article/details/gtantqoxji.html

[S22] C：字符串转数字
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcpdsipoc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sxryk.cn/Article/details/gtuhskjwnf.html

[S23] C：随机数
来源：http://dali.yuxming.cn/Article/details/gtymppnoma.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cheryme.top/Article/details/gtmwjddysl.html

[S24] C：获取本地时间
来源：http://dali.yj202588.top/Article/details/gtozmzlbyk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtugcewlwc.html

[S25] C：内存拷贝
来源：http://dali.yj20258.top/Article/details/gtwwqndncl.html

memcpy(dst, src, n);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjluxnkmw.html

[S26] C：内存清零
来源：http://dali.chenjidiqi.icu/Article/details/gtzqjieytc.html

memset(a, 0, sizeof a);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjlpjoqtr.html

[S27] C：定义常量
来源：http://dali.haohaochexian.top/Article/details/gtdlsdqcfa.html

const double PI = 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gtxivklrlb.html

[S28] C：静态变量
来源：http://dali.nanxinkj.top/Article/details/gtlrdfougz.html

static int counter = 0;
来源：http://dali.daria6918.cn/Article/details/gtiqmdtrbf.html

[S29] C：变参函数
来源：http://dali.hammf.cn/Article/details/gtypmrgydw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jlsjyb.cn/Article/details/gtlwwghqtb.html

[S30] C：头文件保护
来源：http://dali.bjfxy.top/Article/details/gtzzvdjosr.html

#ifndef X_H
来源：http://dali.zhengqikj.top/Article/details/gtkxrmaetd.html

#define X_H
来源：http://dali.hnqzz.top/Article/details/gtvgzatzdb.html

#endif
来源：http://dali.9152youxi.cn/Article/details/gtjqacwcbr.html

[S31] C++：Hello World
来源：http://dali.aibaodan.cn/Article/details/gtfcsoaety.html

#include <iostream>
来源：http://dali.yj20258.top/Article/details/gtpogrzzln.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.0kj1m.cn/Article/details/gtsgwzfmla.html

[S32] C++：字符串
来源：http://dali.birdmap.top/Article/details/gtcoofqziu.html

std::string s = "hi";  s += "!";
来源：http://dali.yj202588.top/Article/details/gtwuyyjhwz.html

[S33] C++：vector 增删
来源：http://dali.cqqwz.cn/Article/details/gtoqioyzpv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ppjwa.cn/Article/details/gtajcqjajd.html

[S34] C++：遍历 vector
来源：http://dali.andypj.xyz/Article/details/gtxufrjlqm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.pengpengdd.cyou/Article/details/gtcwzqldff.html

[S35] C++：map
来源：http://dali.gaohongyu789.top/Article/details/gtotpzxtkr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtdauwesia.html

[S36] C++：unordered_map
来源：http://dali.sweek.top/Article/details/gtpbynralm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gtweptdqql.html

[S37] C++：set
来源：http://dali.redwolf501.top/Article/details/gtitnaajcc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gogol.net.cn/Article/details/gtbapxbqht.html

[S38] C++：排序
来源：http://dali.yj20258888.top/Article/details/gtknazbpot.html

std::sort(v.begin(), v.end());
来源：http://dali.zhengqikj.top/Article/details/gtqgzzzaqw.html

[S39] C++：自定义比较器排序
来源：http://dali.zhoulong.xyz/Article/details/gtiyvlvssu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhiwuduotai.top/Article/details/gttilnzdji.html

[S40] C++：查找元素
来源：http://dali.jqgfzy.top/Article/details/gtzysyneuz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hfpthk.cn/Article/details/gtgeciguac.html

[S41] C++：类与构造函数
来源：http://dali.birdmap.top/Article/details/gtbyyrtwin.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yvedp.cn/Article/details/gtpjqbuumd.html

[S42] C++：继承与虚函数
来源：http://dali.tanke756.top/Article/details/gtosqreloa.html

class B : public Base { public: void f() override {} };
来源：http://dali.dianchejie.cn/Article/details/gtrfudmyyh.html

[S43] C++：智能指针
来源：http://dali.gaohongyu789.top/Article/details/gtjfgdovvk.html

auto p = std::make_unique<int>(5);
来源：http://dali.yueranfly.top/Article/details/gtsdorrxkf.html

[S44] C++：引用传参
来源：http://dali.sysykeji.top/Article/details/gtwfwyinuc.html

void inc(int &x) { ++x; }
来源：http://dali.chenzaomai.com/Article/details/gtpvymjgqv.html

[S45] C++：lambda
来源：http://dali.yuanzhike.top/Article/details/gtopojleqn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zdqjudy.top/Article/details/gtqrrboxrz.html

[S46] C++：函数模板
来源：http://dali.yj20258888.top/Article/details/gtsmfzhwek.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.quarkkingdee.top/Article/details/gtmovppgez.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhongyouzk.top/Article/details/gtoeknurnn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ehwqpu.com/Article/details/gtmuluoujq.html

[S48] C++：逐行读文件
来源：http://dali.sweek.top/Article/details/gtuvznrkqz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.pengpengdd.cyou/Article/details/gtkpadlnmr.html

while (std::getline(in, line)) { }
来源：http://dali.hnqzz.top/Article/details/gtqdjmverd.html

[S49] C++：写文件
来源：http://dali.guannengcc.top/Article/details/gthuwvryyv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yongpay.top/Article/details/gtymeeomfg.html

[S50] C++：格式化数字
来源：http://dali.9152youxi.cn/Article/details/gtzkluicnj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gtkhtnwhjn.html

[S51] C++：显式类型转换
来源：http://dali.chenlongwang.top/Article/details/gtsiygjxoa.html

static_cast<double>(a) / b
来源：http://dali.yj20258888.top/Article/details/gtwlkqfkrn.html

[S52] C++：const 与 noexcept
来源：http://dali.xinyue.icu/Article/details/gtrdoofxlu.html

int size() const noexcept { return n_; }
来源：http://dali.fengsongda.top/Article/details/gtlwrkeqzd.html

[S53] C++：移动语义
来源：http://dali.shanyushiyangtech.top/Article/details/gtmnlrzvkw.html

std::vector<int> w = std::move(v);
来源：http://dali.vqdsnc.cn/Article/details/gtjheyomuq.html

[S54] C++：异常处理
来源：http://dali.jqgufenzy.top/Article/details/gtgeuuhnjb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtceecwvao.html

[S55] C++：结构化绑定
来源：http://dali.fzhhl.top/Article/details/gtvyojunrd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.pycfn.com/Article/details/gtgwywyyiz.html

[S56] C++：optional
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmslpbcse.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.pycfn.com/Article/details/gtisncydat.html

[S57] C++：编译期常量
来源：http://dali.yj202588.top/Article/details/gtbyjkjvwp.html

constexpr int N = 10;
来源：http://dali.vqdsnc.cn/Article/details/gtekbxttnp.html

[S58] C++：命名空间
来源：http://dali.zhixingplan.top/Article/details/gtpkbpfdrh.html

namespace ns { int f() { return 1; } }
来源：http://dali.pengpengdd.cyou/Article/details/gthbhyvtui.html

[S59] C++：静态断言
来源：http://dali.guowangkeji.top/Article/details/gtusvhduxh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xylfe.cn/Article/details/gtaejmbiwk.html

[S60] C++：遍历并删除元素
来源：http://dali.zhengqikj.top/Article/details/gtaaxuessq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.guowangkeji.top/Article/details/gtzflzzxse.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtmfkotqzc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cucudq.cn/Article/details/gtzlkixugi.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvddinonz.html

[T01] Kotlin：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtqjfrkcvr.html

println("Hello")
来源：http://dali.jianghu66.top/Article/details/gthjtqwuuw.html

[T02] Kotlin：变量
来源：http://dali.pycfn.com/Article/details/gtawxhzmjb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.kuanghao11.cn/Article/details/gtdpkvtsqg.html

[T03] Kotlin：字符串模板
来源：http://dali.316326.xyz/Article/details/gtdxamjpcg.html

"值: $b"
来源：http://dali.dianchejie.cn/Article/details/gtywzswktz.html

[T04] Kotlin：空安全
来源：http://dali.sufxvd.cn/Article/details/gtbhqsyquq.html

val n: String? = null;  n?.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtyqmphtpw.html

[T05] Kotlin：when 表达式
来源：http://dali.gzhubu.top/Article/details/gtldpcvdud.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhixingplan.top/Article/details/gtzygqwmkb.html

[T06] Kotlin：集合映射
来源：http://dali.hysaishi.cn/Article/details/gtotmmfuyy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.birdmap.top/Article/details/gtitwosick.html

[T07] Kotlin：集合过滤
来源：http://dali.c1oappe.top/Article/details/gtxknbwqvl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tanke756.top/Article/details/gteutyrtcs.html

[T08] Kotlin：数据类
来源：http://dali.bjfxy.top/Article/details/gtkiagraxb.html

data class User(val name: String, val age: Int)
来源：http://dali.yvedp.cn/Article/details/gtbiyjlidj.html

[T09] Kotlin：扩展函数
来源：http://dali.fengsongda.top/Article/details/gttrsltzzm.html

fun String.exclaim() = this + "!"
来源：http://dali.xuanzx.com/Article/details/gtsieagmny.html

[T10] Kotlin：默认参数
来源：http://dali.fzhhl.top/Article/details/gtajbauhnj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.svipenyu.cn/Article/details/gtmgqinowt.html

[T11] Kotlin：协程
来源：http://dali.mhx1999.top/Article/details/gtgyycurjs.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.chenjidiqi.icu/Article/details/gtdyxpcolc.html

[T12] Kotlin：解构声明
来源：http://dali.gaohongyu789.top/Article/details/gtwckqkxor.html

val (a, b) = Pair(1, 2)
来源：http://dali.kuanghao11.cn/Article/details/gtmghpwtai.html

[T13] Kotlin：只读 Map
来源：http://dali.yvedp.cn/Article/details/gtzaysvmgx.html

val m = mapOf("a" to 1)
来源：http://dali.sweek.top/Article/details/gtusiajosk.html

[T14] Kotlin：循环
来源：http://dali.yuanzhike.top/Article/details/gtddxpsaav.html

for (i in 1..10) println(i)
来源：http://dali.kuanghao11.cn/Article/details/gthvesonyh.html

[T15] Kotlin：接口
来源：http://dali.jinyuanbaomall.cn/Article/details/gtotnudnfd.html

interface Shape { fun area(): Double }
来源：http://dali.hfpthk.cn/Article/details/gtnxgkmcdb.html

[T16] Swift：Hello World
来源：http://dali.aibaodan.cn/Article/details/gtzkdohgxl.html

print("Hello")
来源：http://dali.wangdashe.top/Article/details/gtndccunld.html

[T17] Swift：变量与常量
来源：http://dali.shanyushiyangtech.top/Article/details/gtieipfdqr.html

var a = 1;  let b = 2
来源：http://dali.aibaodan.cn/Article/details/gtzvpwoeoe.html

[T18] Swift：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpwevvugy.html

"值: \(b)"
来源：http://dali.wangshuangyany.cn/Article/details/gtqllxcekp.html

[T19] Swift：可选绑定
来源：http://dali.pengpengdd.cyou/Article/details/gtnefuisex.html

if let n = opt { print(n) }
来源：http://dali.yanxiufei.cn/Article/details/gtpzudutnl.html

[T20] Swift：数组操作
来源：http://dali.cucudq.cn/Article/details/gtoizecvsg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthsyyurtf.html

[T21] Swift：遍历
来源：http://dali.yuanzhike.top/Article/details/gtcvwkejcw.html

for x in a { print(x) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgxmnkxyo.html

[T22] Swift：字典
来源：http://dali.jqgfzy.top/Article/details/gtlbyjoefx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yj20258.top/Article/details/gtzvyikizi.html

[T23] Swift：函数
来源：http://dali.yongpay.top/Article/details/gtlotgluah.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.316326.xyz/Article/details/gtrbavpmjj.html

[T24] Swift：闭包
来源：http://dali.cucudq.cn/Article/details/gtsqcaufjh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.svipenyu.cn/Article/details/gtngaudhzo.html

[T25] Swift：结构体
来源：http://dali.gogol.net.cn/Article/details/gtdxcnridr.html

struct P { var x: Int }
来源：http://dali.hysaishi.cn/Article/details/gtmvapockr.html

[T26] Swift：类与重写
来源：http://dali.xylfe.cn/Article/details/gtterwhggz.html

class A: Base { override func f() {} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtapewwnze.html

[T27] Swift：错误处理
来源：http://dali.gotoacloud.top/Article/details/gtvkttrvpe.html

do { try f() } catch { print(error) }
来源：http://dali.0kj1m.cn/Article/details/gttlesgigq.html

[T28] Swift：枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzkscukfx.html

enum Color { case red, green }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtonmkrpph.html

[T29] Swift：guard 提前返回
来源：http://dali.aizwys.cn/Article/details/gtlkgaahcc.html

guard let x = opt else { return }
来源：http://dali.ehwqpu.com/Article/details/gtginzwrzv.html

[T30] Swift：协议
来源：http://dali.dashuyun.cn/Article/details/gtzbpiowel.html

protocol Shape { func area() -> Double }
来源：http://dali.quarkkingdee.top/Article/details/gtqjgmzjrv.html

[T31] Lua：Hello World
来源：http://dali.yvedp.cn/Article/details/gtmcrsaqop.html

print("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gtirzxgwav.html

[T32] Lua：局部变量
来源：http://dali.9152youxi.cn/Article/details/gtpjstfpqa.html

local a = 1
来源：http://dali.guannengcc.top/Article/details/gtnesqdflf.html

[T33] Lua：表（数组）
来源：http://dali.havefunace.top/Article/details/gtkgbtdeoy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxsttgevx.html

[T34] Lua：遍历表
来源：http://dali.yj20258.top/Article/details/gtpzeqwftz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nanxinkj.top/Article/details/gtedhunjyc.html

[T35] Lua：字典表
来源：http://dali.meibo888.top/Article/details/gtbeypxulw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cucudq.cn/Article/details/gtuovqvdry.html

[T36] Lua：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtiefnxuhw.html

function add(a, b) return a + b end
来源：http://dali.xuanzx.com/Article/details/gtposdwhnc.html

[T37] Lua：字符串拼接
来源：http://dali.wangdashe.top/Article/details/gtdqregmio.html

"a" .. "b"
来源：http://dali.iojbl.cn/Article/details/gtwdqeobeo.html

[T38] Lua：条件
来源：http://dali.hnqzz.top/Article/details/gtljficebn.html

if x > 0 then print("正") end
来源：http://dali.chenzaomai.com/Article/details/gtdeccwkqq.html

[T39] Lua：模式匹配
来源：http://dali.xziqi.cn/Article/details/gthlsdrzrv.html

string.find(s, "%d+")
来源：http://dali.yuxming.cn/Article/details/gtjkxwhrsn.html

[T40] Lua：元表
来源：http://dali.iojbl.cn/Article/details/gtogvnrmup.html

setmetatable({}, { __index = base })
来源：http://dali.pycfn.com/Article/details/gtdoinylun.html

[T41] Perl：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtepdbultm.html

print "Hello\n";
来源：http://dali.tian-w.cn/Article/details/gtarlhtxhv.html

[T42] Perl：变量类型
来源：http://dali.0kj1m.cn/Article/details/gtyagxmsij.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cqqwz.cn/Article/details/gtodqsnpqp.html

[T43] Perl：字符串插值
来源：http://dali.daria6918.cn/Article/details/gtgpuqhinr.html

"值: $a"
来源：http://dali.shzxlz.cn/Article/details/gtaxcxojns.html

[T44] Perl：条件
来源：http://dali.hammf.cn/Article/details/gtnihasbin.html

if ($a > 0) { print "正"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtycakcehh.html

[T45] Perl：数组遍历
来源：http://dali.hnqzz.top/Article/details/gtyjxlhqiv.html

for my $x (@arr) { print $x; }
来源：http://dali.jyoumei.cn/Article/details/gtpaeaotst.html

[T46] Perl：哈希操作
来源：http://dali.jinqigufen.top/Article/details/gtzttdiobu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jqgfzy.top/Article/details/gtvewmndom.html

[T47] Perl：正则捕获
来源：http://dali.pycfn.com/Article/details/gtbwbgzrov.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhengqikj.top/Article/details/gtdfjjjrzw.html

[T48] Perl：正则替换
来源：http://dali.guowangkeji.top/Article/details/gtxpyztwik.html

$s =~ s/old/new/g;
来源：http://dali.daxiang520.top/Article/details/gtmkrlqrqp.html

[T49] Perl：函数
来源：http://dali.yongpay.top/Article/details/gtddtgpzop.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yueranfly.top/Article/details/gtqlykguzi.html

[T50] Perl：逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gtwzibxqjm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gzhubu.top/Article/details/gthkjdortg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpekfizjb.html

[T51] Scala：Hello World
来源：http://dali.birdmap.top/Article/details/gtfgkbpkxk.html

println("Hello")
来源：http://dali.yangfankeji.com/Article/details/gtddlafdpu.html

[T52] Scala：变量
来源：http://dali.jqgufenzy.top/Article/details/gtcqcgwlcq.html

val a = 1;  var b = 2
来源：http://dali.sweek.top/Article/details/gthjutqcir.html

[T53] Scala：字符串插值
来源：http://dali.tian-w.cn/Article/details/gtysjnugrp.html

s"值: $b"
来源：http://dali.guowangkeji.top/Article/details/gtstxklmiy.html

[T54] Scala：集合映射
来源：http://dali.zhixingplan.top/Article/details/gtfviyzxkt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ivvv.top/Article/details/gtxppzvtqk.html

[T55] Scala：集合过滤
来源：http://dali.haohaochexian.top/Article/details/gtlyundwwe.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xylfe.cn/Article/details/gtybzhvwud.html

[T56] Scala：样例类
来源：http://dali.fengsongda.top/Article/details/gtvccvwofj.html

case class User(name: String, age: Int)
来源：http://dali.ivvv.top/Article/details/gtxzaheqwv.html

[T57] Scala：模式匹配
来源：http://dali.hfpthk.cn/Article/details/gtvvddipch.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.sysykeji.top/Article/details/gtiyeuwarz.html

[T58] Scala：函数定义
来源：http://dali.tian-w.cn/Article/details/gtkizceeko.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.pengpengdd.cyou/Article/details/gtgolizzny.html

[T59] Scala：循环
来源：http://dali.feifeiyinyue.top/Article/details/gtihhamgck.html

for (i <- 1 to 10) println(i)
来源：http://dali.cqqwz.cn/Article/details/gtaymvyzob.html

[T60] Scala：折叠
来源：http://dali.hfpthk.cn/Article/details/gthljgejxz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.aizwys.cn/Article/details/gtboievaif.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtcfflhzqy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtwvwzmdxx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtqiqgslqr.html

[U01] Py：创建虚拟环境
来源：http://dali.guannengcc.top/Article/details/gtumykqcrc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hongshengwenyu.top/Article/details/gtgvpwbecm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.9152youxi.cn/Article/details/gtqdfwgogd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.daria6918.cn/Article/details/gtyhdsssgo.html

[U03] Py：加载 .env 配置
来源：http://dali.hnxiangtu.top/Article/details/gtqirgfmws.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xuanzx.com/Article/details/gthrxqnwnf.html

[U04] Py：变量调试打印
来源：http://dali.birdmap.top/Article/details/gtdxnrcbst.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jqgfzy.top/Article/details/gtlpticobu.html

[U05] Py：列表去重且保序
来源：http://dali.zdqjudy.top/Article/details/gtillgnffs.html

list(dict.fromkeys(arr))
来源：http://dali.hywenlv.cn/Article/details/gtsrkuulkc.html

[U06] Py：合并两个字典
来源：http://dali.hysaishi.cn/Article/details/gtchfarwkp.html

{**a, **b}
来源：http://dali.daria6918.cn/Article/details/gtthbepxdd.html

[U07] Py：反转字典键值
来源：http://dali.cashguo.top/Article/details/gtdxaqrdin.html

{v: k for k, v in d.items()}
来源：http://dali.yanxiufei.cn/Article/details/gtczvfsdzf.html

[U08] Py：展平二维列表
来源：http://dali.yongpay.top/Article/details/gtuwnqicep.html

[y for x in nested for y in x]
来源：http://dali.mhx1999.top/Article/details/gtjmjrmnme.html

[U09] Py：字典取最大值的键
来源：http://dali.smart0.xyz/Article/details/gtxomxugsc.html

max(d, key=d.get)
来源：http://dali.yj20258.top/Article/details/gtyvgeghkb.html

[U10] Py：按值排序字典
来源：http://dali.hammf.cn/Article/details/gtgrhtlesg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jqgufenzy.top/Article/details/gtnpsmsgaq.html

[U11] Py：生成器表达式
来源：http://dali.0kj1m.cn/Article/details/gtvjnwckdt.html

(x * 2 for x in arr)
来源：http://dali.zhixingplan.top/Article/details/gtwjqsescs.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yuxming.cn/Article/details/gtwwaquwut.html

Counter(arr).most_common(3)
来源：http://dali.cdnleiting.top/Article/details/gtecpuqnam.html

[U13] Py：固定长度队列
来源：http://dali.xziqi.cn/Article/details/gtvlpwjila.html

deque(maxlen=10)
来源：http://dali.yuxming.cn/Article/details/gtpxkcntby.html

[U14] Py：分组收集到列表
来源：http://dali.yanxiufei.cn/Article/details/gtoiqqhngm.html

defaultdict(list)
来源：http://dali.zhongyouzk.top/Article/details/gtrcisgafo.html

[U15] Py：高精度计时
来源：http://dali.jinqigufen.top/Article/details/gtslkgudre.html

t = time.perf_counter()
来源：http://dali.sysykeji.top/Article/details/gtjbwylyrr.html

[U16] Py：命令行参数解析
来源：http://dali.yj20258.top/Article/details/gtpbjrtijd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hammf.cn/Article/details/gtzyonojga.html

[U17] Py：初始化日志
来源：http://dali.zhiwuduotai.top/Article/details/gtqzokrxga.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ydzc1.top/Article/details/gtcajvucty.html

[U18] Py：预编译正则
来源：http://dali.yueranfly.top/Article/details/gtmyiueawu.html

pat = re.compile(r"\d+")
来源：http://dali.sysykeji.top/Article/details/gtboezujte.html

[U19] Py：正则替换带回调
来源：http://dali.hfpthk.cn/Article/details/gttmbixtsl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.mhx1999.top/Article/details/gtamrhvltx.html

[U20] Py：缓存函数结果
来源：http://dali.yanxiufei.cn/Article/details/gtjtkztkpl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.aibaodan.cn/Article/details/gtvgddmkhj.html

[U21] Py：自定义上下文管理器
来源：http://dali.sysykeji.top/Article/details/gtlrgorsoa.html

@contextlib.contextmanager
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdjuokggj.html

[U22] Py：矩阵转置
来源：http://dali.gaohongyu789.top/Article/details/gtabwyuuyf.html

list(zip(*m))
来源：http://dali.svipenyu.cn/Article/details/gtpupszutg.html

[U23] Py：分块读取大文件
来源：http://dali.0kj1m.cn/Article/details/gttaumcmfs.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.svipenyu.cn/Article/details/gtszqqhggh.html

[U24] Py：路径操作
来源：http://dali.cdnleiting.top/Article/details/gthnsexnfu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlgrtbhch.html

[U25] Py：CSV 按字典读
来源：http://dali.quarkkingdee.top/Article/details/gtksebxjun.html

csv.DictReader(f)
来源：http://dali.yj202588.top/Article/details/gtsqoerukm.html

[U26] Py：并发下载
来源：http://dali.snrcjt.cn/Article/details/gtewnxvidv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.sweek.top/Article/details/gtbzfyxkaj.html

[U27] Py：异步 HTTP
来源：http://dali.jlsjyb.cn/Article/details/gtnfdfqnlk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.sweek.top/Article/details/gteugpadby.html

[U28] Py：类型别名
来源：http://dali.sysykeji.top/Article/details/gtezbaedoe.html

UserId = int
来源：http://dali.xinyue.icu/Article/details/gttsvwcwiy.html


<!-- 参考信息 -->