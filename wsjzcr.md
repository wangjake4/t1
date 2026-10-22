代发 wailian999

strlen(s)
来源：http://dali.hfpthk.cn/Article/details/gtkjnkdveq.html

[S06] C：字符串比较
来源：http://dali.cdnleiting.top/Article/details/gtpgvkezku.html

strcmp(a, b) == 0
来源：http://dali.cdnleiting.top/Article/details/gtqmnvykmz.html

[S07] C：数组遍历求和
来源：http://dali.havefunace.top/Article/details/gtysxwowgf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.bjfxy.top/Article/details/gtsotofxxd.html

[S08] C：动态内存分配与释放
来源：http://dali.hfpthk.cn/Article/details/gtevfeajpv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cdnleiting.top/Article/details/gtmbbnrzac.html

[S09] C：结构体定义与初始化
来源：http://dali.hysaishi.cn/Article/details/gtsdugmwkc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tian-w.cn/Article/details/gtezwuctpi.html

[S10] C：指针与解引用
来源：http://dali.jiagoushi.top/Article/details/gtaigzpwcv.html

int *p = &a;  *p = 5;
来源：http://dali.yj202588.top/Article/details/gtufcqwvvm.html

[S11] C：逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gtmnyidppa.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj20258.top/Article/details/gtutvrmruc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjwjjuih.html

fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gtkpnhrbkf.html

[S12] C：写文件
来源：http://dali.tianlin.xyz/Article/details/gtsqilrabr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxbzxkova.html

[S13] C：宏定义
来源：http://dali.redwolf501.top/Article/details/gtbddfypjc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cashguo.top/Article/details/gtezwuwkyn.html

[S14] C：枚举
来源：http://dali.yongpay.top/Article/details/gtutefmwrr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.meibo888.top/Article/details/gtpylnigdy.html

[S15] C：类型转换
来源：http://dali.birdmap.top/Article/details/gtxmluutvc.html

(double) a / b
来源：http://dali.zhoulong.xyz/Article/details/gtocqmrtyf.html

[S16] C：位操作置位
来源：http://dali.zhiwuduotai.top/Article/details/gttmjnftpr.html

x |= (1 << 3);
来源：http://dali.xziqi.cn/Article/details/gthguhbksg.html

[S17] C：安全拼接字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtoxnybnhu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdsdlrfvp.html

[S18] C：命令行参数
来源：http://dali.zycfv.cn/Article/details/gtzfmijnww.html

int main(int argc, char **argv)
来源：http://dali.yj20258.top/Article/details/gtcdzjmqgz.html

[S19] C：快速排序
来源：http://dali.yonumen.top/Article/details/gtziulkhuk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jqgfzy.top/Article/details/gtbnabibht.html

[S20] C：二分查找
来源：http://dali.yvedp.cn/Article/details/gtztmwhbkb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhengqikj.top/Article/details/gtvqgfzkry.html

[S21] C：字符类别判断
来源：http://dali.yongpay.top/Article/details/gthmayuzme.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gtiwuhwtww.html

[S22] C：字符串转数字
来源：http://dali.guannengcc.top/Article/details/gtfaslzjtz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cqqwz.cn/Article/details/gtsjxrzgar.html

[S23] C：随机数
来源：http://dali.fengsongda.top/Article/details/gtpvxmxwbz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdpyosyyc.html

[S24] C：获取本地时间
来源：http://dali.dianchejie.cn/Article/details/gtqrvikwui.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cucudq.cn/Article/details/gtrvkojtjv.html

[S25] C：内存拷贝
来源：http://dali.jqgufenzy.top/Article/details/gtdgseszre.html

memcpy(dst, src, n);
来源：http://dali.xziqi.cn/Article/details/gtvaqemxzt.html

[S26] C：内存清零
来源：http://dali.hfpthk.cn/Article/details/gtdbwkicrp.html

memset(a, 0, sizeof a);
来源：http://dali.sweek.top/Article/details/gtewqrmxmf.html

[S27] C：定义常量
来源：http://dali.snrcjt.cn/Article/details/gtxyfitarc.html

const double PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gttbitaetw.html

[S28] C：静态变量
来源：http://dali.mhx1999.top/Article/details/gtudopjaav.html

static int counter = 0;
来源：http://dali.wangdashe.top/Article/details/gtfqfzkycr.html

[S29] C：变参函数
来源：http://dali.yvedp.cn/Article/details/gtvqqhuwyh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.redwolf501.top/Article/details/gtfngyrsps.html

[S30] C：头文件保护
来源：http://dali.zhiwuduotai.top/Article/details/gtuwtsyqsu.html

#ifndef X_H
来源：http://dali.feifeiyinyue.top/Article/details/gthiffpzhd.html

#define X_H
来源：http://dali.zycfv.cn/Article/details/gtajsktgtv.html

#endif
来源：http://dali.yanxiufei.cn/Article/details/gtdkwvsadn.html

[S31] C++：Hello World
来源：http://dali.zycfv.cn/Article/details/gtrhhaezzd.html

#include <iostream>
来源：http://dali.tanke756.top/Article/details/gtwafmdgos.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yuxming.cn/Article/details/gtoacxfjde.html

[S32] C++：字符串
来源：http://dali.zycfv.cn/Article/details/gtcpubwedr.html

std::string s = "hi";  s += "!";
来源：http://dali.shanyushiyangtech.top/Article/details/gtyvedavpx.html

[S33] C++：vector 增删
来源：http://dali.jlsjyb.cn/Article/details/gtkzsvwfxw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shuidangran.top/Article/details/gtbvxnmfsr.html

[S34] C++：遍历 vector
来源：http://dali.chenlongwang.top/Article/details/gtieyttzss.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhixingplan.top/Article/details/gtipvcfqdu.html

[S35] C++：map
来源：http://dali.aibaodan.cn/Article/details/gthrjelkgy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtyxdopfcg.html

[S36] C++：unordered_map
来源：http://dali.9152youxi.cn/Article/details/gtzeadjgqc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwmttmfg.html

[S37] C++：set
来源：http://dali.daxiang520.top/Article/details/gtnjqwxmec.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tian-w.cn/Article/details/gtdziahmec.html

[S38] C++：排序
来源：http://dali.xylfe.cn/Article/details/gtlehgxipk.html

std::sort(v.begin(), v.end());
来源：http://dali.316326.xyz/Article/details/gtcqwrwkwi.html

[S39] C++：自定义比较器排序
来源：http://dali.ehwqpu.com/Article/details/gtbysicizj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shangyingyoupin.top/Article/details/gtbeljizeu.html

[S40] C++：查找元素
来源：http://dali.ydzc1.top/Article/details/gtynayszhr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbjyczhsy.html

[S41] C++：类与构造函数
来源：http://dali.hysaishi.cn/Article/details/gtagwicush.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cqqwz.cn/Article/details/gtjcyhatth.html

[S42] C++：继承与虚函数
来源：http://dali.yonumen.top/Article/details/gtzdzkworh.html

class B : public Base { public: void f() override {} };
来源：http://dali.yueranfly.top/Article/details/gtqlnmxblh.html

[S43] C++：智能指针
来源：http://dali.hywenlv.cn/Article/details/gtucgunick.html

auto p = std::make_unique<int>(5);
来源：http://dali.hongshengwenyu.top/Article/details/gtvbmizwjp.html

[S44] C++：引用传参
来源：http://dali.ppjwa.cn/Article/details/gtumygtjlq.html

void inc(int &x) { ++x; }
来源：http://dali.jinqigfzy.top/Article/details/gtsujumnqb.html

[S45] C++：lambda
来源：http://dali.hysaishi.cn/Article/details/gtszbmqamy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nwbrower.top/Article/details/gtxwhcccpf.html

[S46] C++：函数模板
来源：http://dali.birdmap.top/Article/details/gthwgoihww.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.kuanghao11.cn/Article/details/gtgylmcgnq.html

[S47] C++：结构化绑定遍历
来源：http://dali.shuidangran.top/Article/details/gthnjvmzot.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.pycfn.com/Article/details/gtkhsqqqpf.html

[S48] C++：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gtsngywldn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinghuilouyu.cn/Article/details/gtrfveerfm.html

while (std::getline(in, line)) { }
来源：http://dali.yanxiufei.cn/Article/details/gtvtirgbuw.html

[S49] C++：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtglbwojnf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xuanzx.com/Article/details/gtgtzzbkfi.html

[S50] C++：格式化数字
来源：http://dali.zycfv.cn/Article/details/gtxinviclx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtzghrbadg.html

[S51] C++：显式类型转换
来源：http://dali.9152youxi.cn/Article/details/gtyfdhorkh.html

static_cast<double>(a) / b
来源：http://dali.cheryme.top/Article/details/gtfeenoihe.html

[S52] C++：const 与 noexcept
来源：http://dali.hywenlv.cn/Article/details/gtuoubzlbd.html

int size() const noexcept { return n_; }
来源：http://dali.daxiang520.top/Article/details/gtzizctxnz.html

[S53] C++：移动语义
来源：http://dali.yj202588.top/Article/details/gteluglxjq.html

std::vector<int> w = std::move(v);
来源：http://dali.gzhubu.top/Article/details/gtbxrqwpdm.html

[S54] C++：异常处理
来源：http://dali.0kj1m.cn/Article/details/gttycnkrll.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sweek.top/Article/details/gtstheybcz.html

[S55] C++：结构化绑定
来源：http://dali.ivvv.top/Article/details/gtmosikfuz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hnxiangtu.top/Article/details/gtjvefssnm.html

[S56] C++：optional
来源：http://dali.yj202588.top/Article/details/gtxpkotmcm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sufxvd.cn/Article/details/gtvyrvxshy.html

[S57] C++：编译期常量
来源：http://dali.ivvv.top/Article/details/gtsiscbkst.html

constexpr int N = 10;
来源：http://dali.daxiang520.top/Article/details/gtodoxhexq.html

[S58] C++：命名空间
来源：http://dali.jyoumei.cn/Article/details/gtqrhbpcch.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenlongwang.top/Article/details/gtlljmyckr.html

[S59] C++：静态断言
来源：http://dali.daxiang520.top/Article/details/gthtziudiw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gtxbpspwwo.html

[S60] C++：遍历并删除元素
来源：http://dali.birdmap.top/Article/details/gtnbgkxyeb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jianghu66.top/Article/details/gtnbmwjrwz.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtpnkgsgdk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aibaodan.cn/Article/details/gtfmzplduq.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtqzrppgmb.html

[T01] Kotlin：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtcyxlznzq.html

println("Hello")
来源：http://dali.xylfe.cn/Article/details/gtjzfbpflt.html

[T02] Kotlin：变量
来源：http://dali.pycfn.com/Article/details/gtgewvjkhs.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.svipenyu.cn/Article/details/gtkgoxilnq.html

[T03] Kotlin：字符串模板
来源：http://dali.jianghu66.top/Article/details/gtfutbvzsh.html

"值: $b"
来源：http://dali.dashuyun.cn/Article/details/gtvvpcplfn.html

[T04] Kotlin：空安全
来源：http://dali.jqgufenzy.top/Article/details/gtrkyucmza.html

val n: String? = null;  n?.length
来源：http://dali.chenjidiqi.icu/Article/details/gtrvldredd.html

[T05] Kotlin：when 表达式
来源：http://dali.sxryk.cn/Article/details/gtqktkbono.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.feifeiyinyue.top/Article/details/gtmzdyqmjs.html

[T06] Kotlin：集合映射
来源：http://dali.sufxvd.cn/Article/details/gtmfpqsdub.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sufxvd.cn/Article/details/gtiobzxroe.html

[T07] Kotlin：集合过滤
来源：http://dali.nwbrower.top/Article/details/gtrsgebqgv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.fzhhl.top/Article/details/gttepghcek.html

[T08] Kotlin：数据类
来源：http://dali.cashguo.top/Article/details/gtnvgxuiex.html

data class User(val name: String, val age: Int)
来源：http://dali.tanke756.top/Article/details/gtkniltkup.html

[T09] Kotlin：扩展函数
来源：http://dali.sxryk.cn/Article/details/gtvsjeeqdd.html

fun String.exclaim() = this + "!"
来源：http://dali.redwolf501.top/Article/details/gtljsckchc.html

[T10] Kotlin：默认参数
来源：http://dali.wangdashe.top/Article/details/gtumackeaj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gzhubu.top/Article/details/gtjmgciiid.html

[T11] Kotlin：协程
来源：http://dali.nwbrower.top/Article/details/gtivegtlei.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.kuanghao11.cn/Article/details/gtxrecfnrc.html

[T12] Kotlin：解构声明
来源：http://dali.mhx1999.top/Article/details/gtzkmhyier.html

val (a, b) = Pair(1, 2)
来源：http://dali.havefunace.top/Article/details/gtoxnvxtks.html

[T13] Kotlin：只读 Map
来源：http://dali.vqdsnc.cn/Article/details/gturmqwheh.html

val m = mapOf("a" to 1)
来源：http://dali.yuanzhike.top/Article/details/gtgcqpynjn.html

[T14] Kotlin：循环
来源：http://dali.ivvv.top/Article/details/gtrpkvgrhq.html

for (i in 1..10) println(i)
来源：http://dali.xylfe.cn/Article/details/gtupsefmyl.html

[T15] Kotlin：接口
来源：http://dali.jinghuilouyu.cn/Article/details/gtwitwbhzj.html

interface Shape { fun area(): Double }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtczedhyst.html

[T16] Swift：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtmmzvbxps.html

print("Hello")
来源：http://dali.hywenlv.cn/Article/details/gttrqakbig.html

[T17] Swift：变量与常量
来源：http://dali.hammf.cn/Article/details/gtzysyvizw.html

var a = 1;  let b = 2
来源：http://dali.yangfankeji.com/Article/details/gtivuszkpw.html

[T18] Swift：字符串插值
来源：http://dali.guowangkeji.top/Article/details/gtxwxwvkez.html

"值: \(b)"
来源：http://dali.yuxming.cn/Article/details/gtfrewgvbo.html

[T19] Swift：可选绑定
来源：http://dali.hywenlv.cn/Article/details/gtckbsrhhc.html

if let n = opt { print(n) }
来源：http://dali.yj202588.top/Article/details/gtinvtqqfu.html

[T20] Swift：数组操作
来源：http://dali.chenlongwang.top/Article/details/gtqdsnvhom.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yanxiufei.cn/Article/details/gtgfuznshj.html

[T21] Swift：遍历
来源：http://dali.meibo888.top/Article/details/gtmkqposwj.html

for x in a { print(x) }
来源：http://dali.yangfankeji.com/Article/details/gtycrimlpi.html

[T22] Swift：字典
来源：http://dali.316326.xyz/Article/details/gtmkkuimar.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xylfe.cn/Article/details/gtoxzpgzmx.html

[T23] Swift：函数
来源：http://dali.hongshengwenyu.top/Article/details/gtmmwzsdkc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.fengsongda.top/Article/details/gtejoiskoa.html

[T24] Swift：闭包
来源：http://dali.pengpengdd.cyou/Article/details/gtugwcdrbx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gttbibflpa.html

[T25] Swift：结构体
来源：http://dali.dianchejie.cn/Article/details/gtekxxlwxx.html

struct P { var x: Int }
来源：http://dali.yj20258.top/Article/details/gttsunkiuc.html

[T26] Swift：类与重写
来源：http://dali.ehwqpu.com/Article/details/gttvbucvby.html

class A: Base { override func f() {} }
来源：http://dali.shangyingyoupin.top/Article/details/gtufdnssyk.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gtlkqucplb.html

do { try f() } catch { print(error) }
来源：http://dali.yj202588.top/Article/details/gtzdgmdezz.html

[T28] Swift：枚举
来源：http://dali.xziqi.cn/Article/details/gtbaxhmuih.html

enum Color { case red, green }
来源：http://dali.guannengcc.top/Article/details/gtaydzpndn.html

[T29] Swift：guard 提前返回
来源：http://dali.zycfv.cn/Article/details/gtpvmgqwpu.html

guard let x = opt else { return }
来源：http://dali.iojbl.cn/Article/details/gtcwfontsm.html

[T30] Swift：协议
来源：http://dali.chenjidiqi.icu/Article/details/gtvphepkar.html

protocol Shape { func area() -> Double }
来源：http://dali.xylfe.cn/Article/details/gtkgozjvup.html

[T31] Lua：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtdlgwpjos.html

print("Hello")
来源：http://dali.jqgufenzy.top/Article/details/gtlpbsscay.html

[T32] Lua：局部变量
来源：http://dali.xuetiantiany.cn/Article/details/gtyvimtduu.html

local a = 1
来源：http://dali.pengpengdd.cyou/Article/details/gteiztkwcq.html

[T33] Lua：表（数组）
来源：http://dali.jqgufenzy.top/Article/details/gtbhfwycxf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhaomingkeji.xyz/Article/details/gtynwgezwm.html

[T34] Lua：遍历表
来源：http://dali.meibo888.top/Article/details/gteihvqnnt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.guowangkeji.top/Article/details/gtlnqgthfg.html

[T35] Lua：字典表
来源：http://dali.chenlongwang.top/Article/details/gtbuqdkduj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.bjfxy.top/Article/details/gtqqxetaes.html

[T36] Lua：函数
来源：http://dali.shzxlz.cn/Article/details/gtcmgkaprv.html

function add(a, b) return a + b end
来源：http://dali.ydzc1.top/Article/details/gtprtnizip.html

[T37] Lua：字符串拼接
来源：http://dali.tanke756.top/Article/details/gticxbgfod.html

"a" .. "b"
来源：http://dali.gzhubu.top/Article/details/gtorlkorcr.html

[T38] Lua：条件
来源：http://dali.ppjwa.cn/Article/details/gtjfgitwiy.html

if x > 0 then print("正") end
来源：http://dali.dianchejie.cn/Article/details/gtkruzfexh.html

[T39] Lua：模式匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtwurofcbw.html

string.find(s, "%d+")
来源：http://dali.chenlongwang.top/Article/details/gttujqejcx.html

[T40] Lua：元表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtevqxpgzb.html

setmetatable({}, { __index = base })
来源：http://dali.fengsongda.top/Article/details/gtomldjfgs.html

[T41] Perl：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gttplrdtit.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gtcvzqnovw.html

[T42] Perl：变量类型
来源：http://dali.sysykeji.top/Article/details/gtobpqiqrq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.316326.xyz/Article/details/gtrdrnwxuq.html

[T43] Perl：字符串插值
来源：http://dali.meibo888.top/Article/details/gtgwksskhg.html

"值: $a"
来源：http://dali.ppjwa.cn/Article/details/gtxztgiobe.html

[T44] Perl：条件
来源：http://dali.ivvv.top/Article/details/gtvuablbeg.html

if ($a > 0) { print "正"; }
来源：http://dali.cucudq.cn/Article/details/gtdaelyiov.html

[T45] Perl：数组遍历
来源：http://dali.hfpthk.cn/Article/details/gttircpnaz.html

for my $x (@arr) { print $x; }
来源：http://dali.iojbl.cn/Article/details/gtlmrfpnwr.html

[T46] Perl：哈希操作
来源：http://dali.shzxlz.cn/Article/details/gtiykplyfl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gaohongyu789.top/Article/details/gtdaqdvcin.html

[T47] Perl：正则捕获
来源：http://dali.cdnleiting.top/Article/details/gtporytiax.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhoulong.xyz/Article/details/gtstpajunj.html

[T48] Perl：正则替换
来源：http://dali.mhx1999.top/Article/details/gtizbrtoss.html

$s =~ s/old/new/g;
来源：http://dali.bjfxy.top/Article/details/gtdaxrdioc.html

[T49] Perl：函数
来源：http://dali.guannengcc.top/Article/details/gtbqhsfvje.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gtiukaqskf.html

[T50] Perl：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtevqcmzqd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cqqwz.cn/Article/details/gtrkuvwybl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhixingplan.top/Article/details/gtichchywm.html

[T51] Scala：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtltbbwvbb.html

println("Hello")
来源：http://dali.jyoumei.cn/Article/details/gtloupyrov.html

[T52] Scala：变量
来源：http://dali.0kj1m.cn/Article/details/gtzneuohnm.html

val a = 1;  var b = 2
来源：http://dali.tian-w.cn/Article/details/gtmrbpxmuq.html

[T53] Scala：字符串插值
来源：http://dali.kuanghao11.cn/Article/details/gthztpxnxt.html

s"值: $b"
来源：http://dali.jinqigufen.top/Article/details/gtykplgvjl.html

[T54] Scala：集合映射
来源：http://dali.ppjwa.cn/Article/details/gtecalxrke.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtgwolenqs.html

[T55] Scala：集合过滤
来源：http://dali.ehwqpu.com/Article/details/gthpfvsahv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.meibo888.top/Article/details/gtgllbvhcv.html

[T56] Scala：样例类
来源：http://dali.gaohongyu789.top/Article/details/gtppyziypz.html

case class User(name: String, age: Int)
来源：http://dali.hnxiangtu.top/Article/details/gtcdaxxnjn.html

[T57] Scala：模式匹配
来源：http://dali.yangfankeji.com/Article/details/gtutdkrlph.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.c1oappe.top/Article/details/gthrmxwdmr.html

[T58] Scala：函数定义
来源：http://dali.9152youxi.cn/Article/details/gtoalsddkv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.andypj.xyz/Article/details/gteiglimud.html

[T59] Scala：循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtivgftugh.html

for (i <- 1 to 10) println(i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrpstbjyd.html

[T60] Scala：折叠
来源：http://dali.zdqjudy.top/Article/details/gtbtwbdusz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.kuanghao11.cn/Article/details/gtnqjwnnuc.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrhrrofmq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenzaomai.com/Article/details/gtbcjpoara.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtpfwebwms.html

[U01] Py：创建虚拟环境
来源：http://dali.jinyuanbaomall.cn/Article/details/gtipymeman.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cucudq.cn/Article/details/gtkushwrhp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.chenzaomai.com/Article/details/gtnuakpetn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jinqigufen.top/Article/details/gtfoacmwge.html

[U03] Py：加载 .env 配置
来源：http://dali.9152youxi.cn/Article/details/gtfioifqbx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ybcxt.top/Article/details/gtrxnkcuex.html

[U04] Py：变量调试打印
来源：http://dali.zhengqikj.top/Article/details/gtftifjrsb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.chenzaomai.com/Article/details/gtmhaukngy.html

[U05] Py：列表去重且保序
来源：http://dali.9152youxi.cn/Article/details/gtiflupywp.html

list(dict.fromkeys(arr))
来源：http://dali.smart0.xyz/Article/details/gtylhlwzud.html

[U06] Py：合并两个字典
来源：http://dali.jiagoushi.top/Article/details/gthfbqlrdo.html

{**a, **b}
来源：http://dali.chenlongwang.top/Article/details/gtbryhjgfw.html

[U07] Py：反转字典键值
来源：http://dali.9152youxi.cn/Article/details/gtkrufsjpz.html

{v: k for k, v in d.items()}
来源：http://dali.daria6918.cn/Article/details/gtjkiiztyb.html

[U08] Py：展平二维列表
来源：http://dali.chenzaomai.com/Article/details/gtofctwdxa.html

[y for x in nested for y in x]
来源：http://dali.fengsongda.top/Article/details/gtjcbfeymz.html

[U09] Py：字典取最大值的键
来源：http://dali.havefunace.top/Article/details/gtpbfzzdfb.html

max(d, key=d.get)
来源：http://dali.fengsongda.top/Article/details/gtywudsuda.html

[U10] Py：按值排序字典
来源：http://dali.ywan-chungtsiang.top/Article/details/gtljebukgv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvahbmjt.html

[U11] Py：生成器表达式
来源：http://dali.xylfe.cn/Article/details/gtsvavnywr.html

(x * 2 for x in arr)
来源：http://dali.jianghu66.top/Article/details/gtbmadpwiu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sweek.top/Article/details/gtwmuyxgfw.html

Counter(arr).most_common(3)
来源：http://dali.yanxiufei.cn/Article/details/gtucpxowfq.html

[U13] Py：固定长度队列
来源：http://dali.tian-w.cn/Article/details/gtpkqhrddm.html

deque(maxlen=10)
来源：http://dali.jqgfzy.top/Article/details/gthwzafify.html

[U14] Py：分组收集到列表
来源：http://dali.nanxinkj.top/Article/details/gtnooazudf.html

defaultdict(list)
来源：http://dali.yangfankeji.com/Article/details/gtfmuoipcb.html

[U15] Py：高精度计时
来源：http://dali.ehwqpu.com/Article/details/gtkmcldoaw.html

t = time.perf_counter()
来源：http://dali.sweek.top/Article/details/gthikfseck.html

[U16] Py：命令行参数解析
来源：http://dali.c1oappe.top/Article/details/gtyqzuqdcp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yongpay.top/Article/details/gtometgulh.html

[U17] Py：初始化日志
来源：http://dali.snrcjt.cn/Article/details/gtgtkxfnrl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.cheryme.top/Article/details/gtoigityml.html

[U18] Py：预编译正则
来源：http://dali.9152youxi.cn/Article/details/gtbambczmd.html

pat = re.compile(r"\d+")
来源：http://dali.meibo888.top/Article/details/gtbewnvwrx.html

[U19] Py：正则替换带回调
来源：http://dali.yueranfly.top/Article/details/gtoyshwhon.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.havefunace.top/Article/details/gtdiombqyj.html

[U20] Py：缓存函数结果
来源：http://dali.ppjwa.cn/Article/details/gtamprembs.html

@functools.lru_cache(maxsize=None)
来源：http://dali.chenlongwang.top/Article/details/gtgsgspflh.html

[U21] Py：自定义上下文管理器
来源：http://dali.jqgufenzy.top/Article/details/gtrpfelddr.html

@contextlib.contextmanager
来源：http://dali.shzxlz.cn/Article/details/gtgozpyfvd.html

[U22] Py：矩阵转置
来源：http://dali.jinghuilouyu.cn/Article/details/gtapmpkrlz.html

list(zip(*m))
来源：http://dali.ybcxt.top/Article/details/gtckyimhav.html

[U23] Py：分块读取大文件
来源：http://dali.zhixingplan.top/Article/details/gtestevgyv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xuetiantiany.cn/Article/details/gtllmjdgue.html

[U24] Py：路径操作
来源：http://dali.aizwys.cn/Article/details/gtqwteygdh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zdqjudy.top/Article/details/gtuaskiyqw.html

[U25] Py：CSV 按字典读
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcoflwkzj.html

csv.DictReader(f)
来源：http://dali.birdmap.top/Article/details/gthjajgeio.html

[U26] Py：并发下载
来源：http://dali.pycfn.com/Article/details/gtfcvmekpj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.redwolf501.top/Article/details/gtxknkxuzs.html

[U27] Py：异步 HTTP
来源：http://dali.mhx1999.top/Article/details/gtvsrwufuk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.wangdashe.top/Article/details/gtdbjyghzp.html

[U28] Py：类型别名
来源：http://dali.9152youxi.cn/Article/details/gtrjbbodyy.html

UserId = int
来源：http://dali.0kj1m.cn/Article/details/gtcdjbmtxt.html


<!-- 参考信息 -->