代发 wailian999

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.pengpengdd.cyou/Article/details/gtrualqnbg.html

[S08] C：动态内存分配与释放
来源：http://dali.guannengcc.top/Article/details/gtczyxowoe.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yanxiufei.cn/Article/details/gtuymwmidu.html

[S09] C：结构体定义与初始化
来源：http://dali.zdqjudy.top/Article/details/gtfjeozifc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yonumen.top/Article/details/gtvmhunqdf.html

[S10] C：指针与解引用
来源：http://dali.guannengcc.top/Article/details/gtfxokjqfi.html

int *p = &a;  *p = 5;
来源：http://dali.nanxinkj.top/Article/details/gtzythbloy.html

[S11] C：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gtmdiseztg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.9152youxi.cn/Article/details/gtbsuqxloe.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yvedp.cn/Article/details/gtvrvpsozl.html

fclose(f);
来源：http://dali.iojbl.cn/Article/details/gtddhwcelc.html

[S12] C：写文件
来源：http://dali.meibo888.top/Article/details/gtpngpkzuw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yongpay.top/Article/details/gtbbgbqkru.html

[S13] C：宏定义
来源：http://dali.hysaishi.cn/Article/details/gtplthcymw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hfpthk.cn/Article/details/gtnszbjkqc.html

[S14] C：枚举
来源：http://dali.hnqzz.top/Article/details/gtmtfxcjwc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yj202588.top/Article/details/gtofzwuofk.html

[S15] C：类型转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtehnmbgzm.html

(double) a / b
来源：http://dali.yonumen.top/Article/details/gtociutqdu.html

[S16] C：位操作置位
来源：http://dali.gaohongyu789.top/Article/details/gtieuguuzj.html

x |= (1 << 3);
来源：http://dali.aizwys.cn/Article/details/gtqfyxvdpk.html

[S17] C：安全拼接字符串
来源：http://dali.hammf.cn/Article/details/gtpjqjpxnb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yongpay.top/Article/details/gtmevokrud.html

[S18] C：命令行参数
来源：http://dali.0kj1m.cn/Article/details/gtumeicegf.html

int main(int argc, char **argv)
来源：http://dali.nanxinkj.top/Article/details/gtbtpgojeo.html

[S19] C：快速排序
来源：http://dali.snrcjt.cn/Article/details/gtcapvrzbg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.dashuyun.cn/Article/details/gtjgrvnbzs.html

[S20] C：二分查找
来源：http://dali.pengpengdd.cyou/Article/details/gtcvwxrfjl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhengqikj.top/Article/details/gtlrqmdory.html

[S21] C：字符类别判断
来源：http://dali.sweek.top/Article/details/gtdorpdwbv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.havefunace.top/Article/details/gtkktphdws.html

[S22] C：字符串转数字
来源：http://dali.pengpengdd.cyou/Article/details/gtcmrizhep.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xziqi.cn/Article/details/gtrqaeaohu.html

[S23] C：随机数
来源：http://dali.yj202588.top/Article/details/gtcwdofldv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shuidangran.top/Article/details/gtheoyuyjb.html

[S24] C：获取本地时间
来源：http://dali.cucudq.cn/Article/details/gtekuslhay.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cheryme.top/Article/details/gtnjmkkcfg.html

[S25] C：内存拷贝
来源：http://dali.ehwqpu.com/Article/details/gtfmdtikak.html

memcpy(dst, src, n);
来源：http://dali.hfpthk.cn/Article/details/gtrhxvqkjb.html

[S26] C：内存清零
来源：http://dali.yueranfly.top/Article/details/gtdwtcttee.html

memset(a, 0, sizeof a);
来源：http://dali.jiagoushi.top/Article/details/gtfsmuprke.html

[S27] C：定义常量
来源：http://dali.yanxiufei.cn/Article/details/gtseluxmkz.html

const double PI = 3.14159;
来源：http://dali.xinyue.icu/Article/details/gtvzuvwfgx.html

[S28] C：静态变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfnayrsz.html

static int counter = 0;
来源：http://dali.nwbrower.top/Article/details/gthvwcjuhv.html

[S29] C：变参函数
来源：http://dali.ybcxt.top/Article/details/gtyygtjsrn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.dianchejie.cn/Article/details/gtzbiiugyd.html

[S30] C：头文件保护
来源：http://dali.xinyue.icu/Article/details/gtrmdvsbuy.html

#ifndef X_H
来源：http://dali.pycfn.com/Article/details/gtpjnvmzui.html

#define X_H
来源：http://dali.gogol.net.cn/Article/details/gtggpbmjui.html

#endif
来源：http://dali.yanxiufei.cn/Article/details/gtqocbndpv.html

[S31] C++：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtzluyycga.html

#include <iostream>
来源：http://dali.cucudq.cn/Article/details/gttghevoga.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zycfv.cn/Article/details/gtbijuhcio.html

[S32] C++：字符串
来源：http://dali.guannengcc.top/Article/details/gtfkyfnbdx.html

std::string s = "hi";  s += "!";
来源：http://dali.kuanghao11.cn/Article/details/gtxmcwakss.html

[S33] C++：vector 增删
来源：http://dali.hnxiangtu.top/Article/details/gtlqcgndsb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ivvv.top/Article/details/gtfuuahqrs.html

[S34] C++：遍历 vector
来源：http://dali.meibo888.top/Article/details/gtijkfgmaw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sysykeji.top/Article/details/gtgnbkyhpq.html

[S35] C++：map
来源：http://dali.ehwqpu.com/Article/details/gtxolzpjbu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cheryme.top/Article/details/gtbyhpvisf.html

[S36] C++：unordered_map
来源：http://dali.svipenyu.cn/Article/details/gtmlzrxjqs.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gtsmgmjmgf.html

[S37] C++：set
来源：http://dali.daxiang520.top/Article/details/gtkauvdhwj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.meibo888.top/Article/details/gtfkqlemqo.html

[S38] C++：排序
来源：http://dali.zycfv.cn/Article/details/gtqzrshped.html

std::sort(v.begin(), v.end());
来源：http://dali.jqgufenzy.top/Article/details/gtugyqrnif.html

[S39] C++：自定义比较器排序
来源：http://dali.zhoulong.xyz/Article/details/gtostropdm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zycfv.cn/Article/details/gtlqlajhrf.html

[S40] C++：查找元素
来源：http://dali.svipenyu.cn/Article/details/gtnkeyfwzi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.aibaodan.cn/Article/details/gtwfxjjlyy.html

[S41] C++：类与构造函数
来源：http://dali.vqdsnc.cn/Article/details/gtaelxpvcu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtmoipnoyp.html

[S42] C++：继承与虚函数
来源：http://dali.zhongyouzk.top/Article/details/gthrtjzsjg.html

class B : public Base { public: void f() override {} };
来源：http://dali.xuanzx.com/Article/details/gtynildnsk.html

[S43] C++：智能指针
来源：http://dali.yongpay.top/Article/details/gtbtscupch.html

auto p = std::make_unique<int>(5);
来源：http://dali.c1oappe.top/Article/details/gtbtjhmgji.html

[S44] C++：引用传参
来源：http://dali.guannengcc.top/Article/details/gtjxvsiaiu.html

void inc(int &x) { ++x; }
来源：http://dali.redwolf501.top/Article/details/gtwexhmbbx.html

[S45] C++：lambda
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqpurmjez.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fzhhl.top/Article/details/gtgeqyxsaw.html

[S46] C++：函数模板
来源：http://dali.nanxuanxn.top/Article/details/gtpgelcpru.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.guannengcc.top/Article/details/gtnvgzrhwl.html

[S47] C++：结构化绑定遍历
来源：http://dali.nanxinkj.top/Article/details/gtryptqipd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yangfankeji.com/Article/details/gtcawmviii.html

[S48] C++：逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gtgaovcthb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.0kj1m.cn/Article/details/gtlxysgnzw.html

while (std::getline(in, line)) { }
来源：http://dali.redwolf501.top/Article/details/gtfrvyeeln.html

[S49] C++：写文件
来源：http://dali.tanke756.top/Article/details/gtcsuxmlqx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jqgfzy.top/Article/details/gthvhjpufy.html

[S50] C++：格式化数字
来源：http://dali.dashuyun.cn/Article/details/gthckqthyl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gtmhnyvsvx.html

[S51] C++：显式类型转换
来源：http://dali.sufxvd.cn/Article/details/gtivsblckd.html

static_cast<double>(a) / b
来源：http://dali.shangyingyoupin.top/Article/details/gtdhrluotw.html

[S52] C++：const 与 noexcept
来源：http://dali.hammf.cn/Article/details/gtptympjgb.html

int size() const noexcept { return n_; }
来源：http://dali.yonumen.top/Article/details/gtnroarhze.html

[S53] C++：移动语义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcvhtfkly.html

std::vector<int> w = std::move(v);
来源：http://dali.sysykeji.top/Article/details/gtbsrpklbl.html

[S54] C++：异常处理
来源：http://dali.yuxming.cn/Article/details/gtudjogghc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yueranfly.top/Article/details/gtqxceutah.html

[S55] C++：结构化绑定
来源：http://dali.mhx1999.top/Article/details/gtjauvirhl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xuanzx.com/Article/details/gtbjltmgij.html

[S56] C++：optional
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvocfrafm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ydzc1.top/Article/details/gtwitlyfam.html

[S57] C++：编译期常量
来源：http://dali.ivvv.top/Article/details/gtykhdmfmj.html

constexpr int N = 10;
来源：http://dali.yuxming.cn/Article/details/gtjbdogsiq.html

[S58] C++：命名空间
来源：http://dali.hongshengwenyu.top/Article/details/gtdlcmhcgo.html

namespace ns { int f() { return 1; } }
来源：http://dali.xinyue.icu/Article/details/gtsjopqtis.html

[S59] C++：静态断言
来源：http://dali.sufxvd.cn/Article/details/gtrqiengru.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhongyouzk.top/Article/details/gtywgbhxhg.html

[S60] C++：遍历并删除元素
来源：http://dali.shzxlz.cn/Article/details/gtltkjfleu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.daxiang520.top/Article/details/gtjkvwezjq.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtrnokgrpv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hysaishi.cn/Article/details/gtjmlbjeui.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtvcyuaaem.html

[T01] Kotlin：Hello World
来源：http://dali.cashguo.top/Article/details/gtggzyrlwz.html

println("Hello")
来源：http://dali.jiagoushi.top/Article/details/gtvxtkxsor.html

[T02] Kotlin：变量
来源：http://dali.xylfe.cn/Article/details/gtnotmxjdc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yj20258888.top/Article/details/gtzmrubyty.html

[T03] Kotlin：字符串模板
来源：http://dali.gotoacloud.top/Article/details/gtcdfgwpim.html

"值: $b"
来源：http://dali.cdnleiting.top/Article/details/gtexadixqf.html

[T04] Kotlin：空安全
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtihjqvopk.html

val n: String? = null;  n?.length
来源：http://dali.ivvv.top/Article/details/gtjzplsmxt.html

[T05] Kotlin：when 表达式
来源：http://dali.jianghu66.top/Article/details/gtazgtgyxz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tianlin.xyz/Article/details/gtowcstxil.html

[T06] Kotlin：集合映射
来源：http://dali.gotoacloud.top/Article/details/gtpopzhfpq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xinyue.icu/Article/details/gttbnemehn.html

[T07] Kotlin：集合过滤
来源：http://dali.fzhhl.top/Article/details/gtpeixjunh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.smart0.xyz/Article/details/gtqjdwxzio.html

[T08] Kotlin：数据类
来源：http://dali.jqgufenzy.top/Article/details/gttpdtroud.html

data class User(val name: String, val age: Int)
来源：http://dali.cheryme.top/Article/details/gtylstakgw.html

[T09] Kotlin：扩展函数
来源：http://dali.yj20258888.top/Article/details/gtvjentugm.html

fun String.exclaim() = this + "!"
来源：http://dali.fzhhl.top/Article/details/gtiqybjmce.html

[T10] Kotlin：默认参数
来源：http://dali.yangfankeji.com/Article/details/gtwyfgcumt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.c1oappe.top/Article/details/gtpljynuxv.html

[T11] Kotlin：协程
来源：http://dali.snrcjt.cn/Article/details/gttprcitqx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzjrggxcc.html

[T12] Kotlin：解构声明
来源：http://dali.sufxvd.cn/Article/details/gtttuamuzw.html

val (a, b) = Pair(1, 2)
来源：http://dali.sxryk.cn/Article/details/gtvjnbbtpg.html

[T13] Kotlin：只读 Map
来源：http://dali.zdqjudy.top/Article/details/gtpoycntfw.html

val m = mapOf("a" to 1)
来源：http://dali.tian-w.cn/Article/details/gtkvsoeubp.html

[T14] Kotlin：循环
来源：http://dali.zhixingplan.top/Article/details/gtkjmtnxhs.html

for (i in 1..10) println(i)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpwoadzzn.html

[T15] Kotlin：接口
来源：http://dali.pengpengdd.cyou/Article/details/gtqneihlum.html

interface Shape { fun area(): Double }
来源：http://dali.jiagoushi.top/Article/details/gtvomzbzsq.html

[T16] Swift：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlwkwxpyg.html

print("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gtucnrqdcl.html

[T17] Swift：变量与常量
来源：http://dali.gaohongyu789.top/Article/details/gtzayywueg.html

var a = 1;  let b = 2
来源：http://dali.xylfe.cn/Article/details/gtsypaivmg.html

[T18] Swift：字符串插值
来源：http://dali.316326.xyz/Article/details/gtpujwtbqr.html

"值: \(b)"
来源：http://dali.redwolf501.top/Article/details/gtjcznyzni.html

[T19] Swift：可选绑定
来源：http://dali.sufxvd.cn/Article/details/gteommgmsr.html

if let n = opt { print(n) }
来源：http://dali.yanxiufei.cn/Article/details/gtgwjjtljw.html

[T20] Swift：数组操作
来源：http://dali.guannengcc.top/Article/details/gtspksdzox.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cdnleiting.top/Article/details/gtfwnlpimd.html

[T21] Swift：遍历
来源：http://dali.zhengqikj.top/Article/details/gtfknyrlbw.html

for x in a { print(x) }
来源：http://dali.aizwys.cn/Article/details/gtugmfgarb.html

[T22] Swift：字典
来源：http://dali.dashuyun.cn/Article/details/gtjvnxodjq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gzhubu.top/Article/details/gtecnpfwjj.html

[T23] Swift：函数
来源：http://dali.havefunace.top/Article/details/gthjfiolra.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yj20258.top/Article/details/gtwnsjmsya.html

[T24] Swift：闭包
来源：http://dali.haohaochexian.top/Article/details/gtjnbfgrif.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpyhlzwpy.html

[T25] Swift：结构体
来源：http://dali.xuanzx.com/Article/details/gtwebzjqsh.html

struct P { var x: Int }
来源：http://dali.jianghu66.top/Article/details/gtqzjfjqzl.html

[T26] Swift：类与重写
来源：http://dali.yuanzhike.top/Article/details/gttqvittqc.html

class A: Base { override func f() {} }
来源：http://dali.bjfxy.top/Article/details/gtyqvhigir.html

[T27] Swift：错误处理
来源：http://dali.vqdsnc.cn/Article/details/gtnpiifojt.html

do { try f() } catch { print(error) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzmekwrq.html

[T28] Swift：枚举
来源：http://dali.andypj.xyz/Article/details/gtbgzcxted.html

enum Color { case red, green }
来源：http://dali.zhongyouzk.top/Article/details/gtnogjyypv.html

[T29] Swift：guard 提前返回
来源：http://dali.cqqwz.cn/Article/details/gtqyqbqklu.html

guard let x = opt else { return }
来源：http://dali.sweek.top/Article/details/gtnkihoxti.html

[T30] Swift：协议
来源：http://dali.sysykeji.top/Article/details/gthzulwvhp.html

protocol Shape { func area() -> Double }
来源：http://dali.cheryme.top/Article/details/gtfsjvuplj.html

[T31] Lua：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtcskvuspj.html

print("Hello")
来源：http://dali.redwolf501.top/Article/details/gtdykkoqnc.html

[T32] Lua：局部变量
来源：http://dali.wangdashe.top/Article/details/gtlebjimgm.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gtuzfjzqyb.html

[T33] Lua：表（数组）
来源：http://dali.daria6918.cn/Article/details/gtstwoaxxw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.aibaodan.cn/Article/details/gtvevbehbf.html

[T34] Lua：遍历表
来源：http://dali.gotoacloud.top/Article/details/gtlwatzwow.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shangyingyoupin.top/Article/details/gtxydopabw.html

[T35] Lua：字典表
来源：http://dali.fzhhl.top/Article/details/gteldbgufn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yuanzhike.top/Article/details/gtrcbqwidz.html

[T36] Lua：函数
来源：http://dali.0kj1m.cn/Article/details/gtehlfkkoz.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gttyjjhtfv.html

[T37] Lua：字符串拼接
来源：http://dali.smart0.xyz/Article/details/gttzmgnwcd.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gtzjbcnhho.html

[T38] Lua：条件
来源：http://dali.dashuyun.cn/Article/details/gtnpoiuczs.html

if x > 0 then print("正") end
来源：http://dali.havefunace.top/Article/details/gtbeceqdcf.html

[T39] Lua：模式匹配
来源：http://dali.daxiang520.top/Article/details/gtsvnxbsks.html

string.find(s, "%d+")
来源：http://dali.zhixingplan.top/Article/details/gtvbycucbp.html

[T40] Lua：元表
来源：http://dali.shzxlz.cn/Article/details/gtakshimok.html

setmetatable({}, { __index = base })
来源：http://dali.xuetiantiany.cn/Article/details/gtzgdelqke.html

[T41] Perl：Hello World
来源：http://dali.nwbrower.top/Article/details/gtrkphomel.html

print "Hello\n";
来源：http://dali.cashguo.top/Article/details/gteueicqoy.html

[T42] Perl：变量类型
来源：http://dali.shuidangran.top/Article/details/gtgflnxmbh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhiwuduotai.top/Article/details/gtohcrjasn.html

[T43] Perl：字符串插值
来源：http://dali.zhiwuduotai.top/Article/details/gtgwgcdply.html

"值: $a"
来源：http://dali.yuxming.cn/Article/details/gtmzrynjxm.html

[T44] Perl：条件
来源：http://dali.pengpengdd.cyou/Article/details/gtrrxuynnw.html

if ($a > 0) { print "正"; }
来源：http://dali.haohaochexian.top/Article/details/gthearbgfa.html

[T45] Perl：数组遍历
来源：http://dali.smart0.xyz/Article/details/gtcnjtckgc.html

for my $x (@arr) { print $x; }
来源：http://dali.316326.xyz/Article/details/gtsoejrrnv.html

[T46] Perl：哈希操作
来源：http://dali.iojbl.cn/Article/details/gtfmbjnyyl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtjowjluni.html

[T47] Perl：正则捕获
来源：http://dali.316326.xyz/Article/details/gtazgosunt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.iojbl.cn/Article/details/gtfnkwebij.html

[T48] Perl：正则替换
来源：http://dali.zhengqikj.top/Article/details/gthlpehjbm.html

$s =~ s/old/new/g;
来源：http://dali.ivvv.top/Article/details/gtumuemdvq.html

[T49] Perl：函数
来源：http://dali.cucudq.cn/Article/details/gthfyqjtne.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.daria6918.cn/Article/details/gtmgnerenp.html

[T50] Perl：逐行读文件
来源：http://dali.wangdashe.top/Article/details/gtvepalobc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlqxnexsn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinqigufen.top/Article/details/gtpxpjuleh.html

[T51] Scala：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkeogyjci.html

println("Hello")
来源：http://dali.xylfe.cn/Article/details/gtlzhqpbkc.html

[T52] Scala：变量
来源：http://dali.xuetiantiany.cn/Article/details/gtfqbjybkv.html

val a = 1;  var b = 2
来源：http://dali.zhongyouzk.top/Article/details/gtnbkwbmbb.html

[T53] Scala：字符串插值
来源：http://dali.yanxiufei.cn/Article/details/gttaeksvlu.html

s"值: $b"
来源：http://dali.cheryme.top/Article/details/gtceprsyxr.html

[T54] Scala：集合映射
来源：http://dali.dashuyun.cn/Article/details/gtgmgvoaim.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.mhx1999.top/Article/details/gttaqhpnnn.html

[T55] Scala：集合过滤
来源：http://dali.cashguo.top/Article/details/gtbuphzugr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.tian-w.cn/Article/details/gtxgetmxgo.html

[T56] Scala：样例类
来源：http://dali.chenjidiqi.icu/Article/details/gtkrandmhg.html

case class User(name: String, age: Int)
来源：http://dali.pengpengdd.cyou/Article/details/gthbnehtre.html

[T57] Scala：模式匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtuzadpllq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.havefunace.top/Article/details/gtcekxdivs.html

[T58] Scala：函数定义
来源：http://dali.yueranfly.top/Article/details/gtczqbgyaw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinqigfzy.top/Article/details/gtcbrmriul.html

[T59] Scala：循环
来源：http://dali.ybcxt.top/Article/details/gtvfjnsslw.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhengqikj.top/Article/details/gtzcuwkurf.html

[T60] Scala：折叠
来源：http://dali.feifeiyinyue.top/Article/details/gtealgbjfx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sysykeji.top/Article/details/gtvefimirg.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtmclqhxhi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhixingplan.top/Article/details/gtlfmijxrt.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtmeajnsin.html

[U01] Py：创建虚拟环境
来源：http://dali.cqqwz.cn/Article/details/gtbtoyovph.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.fzhhl.top/Article/details/gtaltrguyd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhoulong.xyz/Article/details/gtfzmtepbu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtzekychyp.html

[U03] Py：加载 .env 配置
来源：http://dali.zhoulong.xyz/Article/details/gtgyddxfmk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yj20258888.top/Article/details/gtcxmcvqli.html

[U04] Py：变量调试打印
来源：http://dali.jyoumei.cn/Article/details/gtbkjmgjan.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jqgfzy.top/Article/details/gtnzzecnvr.html

[U05] Py：列表去重且保序
来源：http://dali.cucudq.cn/Article/details/gtzigxlclu.html

list(dict.fromkeys(arr))
来源：http://dali.fzhhl.top/Article/details/gtcuydrenh.html

[U06] Py：合并两个字典
来源：http://dali.ivvv.top/Article/details/gtgwsveouk.html

{**a, **b}
来源：http://dali.hfpthk.cn/Article/details/gtzieaelyz.html

[U07] Py：反转字典键值
来源：http://dali.c1oappe.top/Article/details/gtnyejyaqo.html

{v: k for k, v in d.items()}
来源：http://dali.tianlin.xyz/Article/details/gtnhvqnmug.html

[U08] Py：展平二维列表
来源：http://dali.guannengcc.top/Article/details/gtkrbaolji.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gtiftfgxsp.html

[U09] Py：字典取最大值的键
来源：http://dali.hfpthk.cn/Article/details/gtyimjttqq.html

max(d, key=d.get)
来源：http://dali.xinyue.icu/Article/details/gtpuxgjbnc.html

[U10] Py：按值排序字典
来源：http://dali.havefunace.top/Article/details/gtiftmahif.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.bjfxy.top/Article/details/gtxmvjuywb.html

[U11] Py：生成器表达式
来源：http://dali.ydzc1.top/Article/details/gthuoiupaw.html

(x * 2 for x in arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlljhhfgy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ehwqpu.com/Article/details/gtusttbhok.html

Counter(arr).most_common(3)
来源：http://dali.yongpay.top/Article/details/gtuncqmtfz.html

[U13] Py：固定长度队列
来源：http://dali.cucudq.cn/Article/details/gthbfdtmdz.html

deque(maxlen=10)
来源：http://dali.zdqjudy.top/Article/details/gtscwnreak.html

[U14] Py：分组收集到列表
来源：http://dali.jiagoushi.top/Article/details/gtkngrnebe.html

defaultdict(list)
来源：http://dali.zhongyouzk.top/Article/details/gtiilychdb.html

[U15] Py：高精度计时
来源：http://dali.feifeiyinyue.top/Article/details/gtveqerqlq.html

t = time.perf_counter()
来源：http://dali.fzhhl.top/Article/details/gtpsepflks.html

[U16] Py：命令行参数解析
来源：http://dali.nanxinkj.top/Article/details/gtratssxee.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zycfv.cn/Article/details/gtdzftmwyh.html

[U17] Py：初始化日志
来源：http://dali.sweek.top/Article/details/gtxdyqhzlj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jyoumei.cn/Article/details/gthtnhozhg.html

[U18] Py：预编译正则
来源：http://dali.xinyue.icu/Article/details/gtmfnzgeic.html

pat = re.compile(r"\d+")
来源：http://dali.zhengqikj.top/Article/details/gtmkuwrbkp.html

[U19] Py：正则替换带回调
来源：http://dali.ydzc1.top/Article/details/gtqgmbvsvb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hnqzz.top/Article/details/gtniasqlfx.html

[U20] Py：缓存函数结果
来源：http://dali.yuxming.cn/Article/details/gtvcnaezck.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yj20258.top/Article/details/gtxiozrmag.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhengqikj.top/Article/details/gtpjslqmsa.html

@contextlib.contextmanager
来源：http://dali.yangfankeji.com/Article/details/gtwbowdngm.html

[U22] Py：矩阵转置
来源：http://dali.shangyingyoupin.top/Article/details/gtglvgcwuz.html

list(zip(*m))
来源：http://dali.birdmap.top/Article/details/gtdbesifbc.html

[U23] Py：分块读取大文件
来源：http://dali.ivvv.top/Article/details/gtcmxangnn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ppjwa.cn/Article/details/gtdxfgyone.html

[U24] Py：路径操作
来源：http://dali.0kj1m.cn/Article/details/gtousuxygi.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.guannengcc.top/Article/details/gtnaboqfdt.html

[U25] Py：CSV 按字典读
来源：http://dali.shzxlz.cn/Article/details/gthslomfns.html

csv.DictReader(f)
来源：http://dali.yj20258.top/Article/details/gtnieswwiu.html

[U26] Py：并发下载
来源：http://dali.quarkkingdee.top/Article/details/gtclmcjufr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yuanzhike.top/Article/details/gtcmtcffmd.html

[U27] Py：异步 HTTP
来源：http://dali.yvedp.cn/Article/details/gtoaqonzor.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.chenlongwang.top/Article/details/gtsiyhgtfk.html

[U28] Py：类型别名
来源：http://dali.ywan-chungtsiang.top/Article/details/gtltadtrhk.html

UserId = int
来源：http://dali.quarkkingdee.top/Article/details/gtwlnpfbej.html

[U29] Py：属性校验
来源：http://dali.jqgfzy.top/Article/details/gtjtljzlka.html

@property 与 @x.setter 配合
来源：http://dali.redwolf501.top/Article/details/gtiuhqabjl.html

[U30] Py：数据类
来源：http://dali.xylfe.cn/Article/details/gtakctjgvl.html

@dataclass(slots=True)
来源：http://dali.jianghu66.top/Article/details/gtbjdytqmv.html


<!-- 参考信息 -->