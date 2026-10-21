代发 wailian999

strlen(s)
来源：http://dali.fengsongda.top/Article/details/gthstymhor.html

[S06] C：字符串比较
来源：http://dali.yonumen.top/Article/details/gtqugivvhv.html

strcmp(a, b) == 0
来源：http://dali.fengsongda.top/Article/details/gtvxlrggfp.html

[S07] C：数组遍历求和
来源：http://dali.mhx1999.top/Article/details/gtugclqxyx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cdnleiting.top/Article/details/gtdbchjysl.html

[S08] C：动态内存分配与释放
来源：http://dali.nanxuanxn.top/Article/details/gtphxkzzzo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.mhx1999.top/Article/details/gtzalibety.html

[S09] C：结构体定义与初始化
来源：http://dali.chenzaomai.com/Article/details/gtejaqvuho.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shzxlz.cn/Article/details/gtizpnpbth.html

[S10] C：指针与解引用
来源：http://dali.tian-w.cn/Article/details/gtabzzeoua.html

int *p = &a;  *p = 5;
来源：http://dali.yongpay.top/Article/details/gtmebwghfw.html

[S11] C：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gtkpjlkbbj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.9152youxi.cn/Article/details/gtvuduorbe.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gogol.net.cn/Article/details/gtjrchulic.html

fclose(f);
来源：http://dali.jqgufenzy.top/Article/details/gtnbedkbag.html

[S12] C：写文件
来源：http://dali.nanxuanxn.top/Article/details/gtpaqjaysj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hongshengwenyu.top/Article/details/gtllpfdett.html

[S13] C：宏定义
来源：http://dali.chenjidiqi.icu/Article/details/gtsrqzixtx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvayzxrld.html

[S14] C：枚举
来源：http://dali.yueranfly.top/Article/details/gtxrptrahg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xylfe.cn/Article/details/gtpzxfbjws.html

[S15] C：类型转换
来源：http://dali.guowangkeji.top/Article/details/gtjoelmuvx.html

(double) a / b
来源：http://dali.haohaochexian.top/Article/details/gttrtqavzn.html

[S16] C：位操作置位
来源：http://dali.sweek.top/Article/details/gtdiyscsim.html

x |= (1 << 3);
来源：http://dali.gogol.net.cn/Article/details/gtsrktfljd.html

[S17] C：安全拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gtpvhgsyet.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.aibaodan.cn/Article/details/gtpucoxiwt.html

[S18] C：命令行参数
来源：http://dali.cqqwz.cn/Article/details/gtoalpnyle.html

int main(int argc, char **argv)
来源：http://dali.c1oappe.top/Article/details/gttrpbxhfx.html

[S19] C：快速排序
来源：http://dali.bjfxy.top/Article/details/gtwchisnvf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gtnmmpzxmm.html

[S20] C：二分查找
来源：http://dali.shuidangran.top/Article/details/gtipsdavzq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gogol.net.cn/Article/details/gtmivcfhoh.html

[S21] C：字符类别判断
来源：http://dali.gaohongyu789.top/Article/details/gtgmhhtefc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj20258888.top/Article/details/gtkcgbrzoa.html

[S22] C：字符串转数字
来源：http://dali.hywenlv.cn/Article/details/gtdrwrzswf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sufxvd.cn/Article/details/gtekuoxpxz.html

[S23] C：随机数
来源：http://dali.yvedp.cn/Article/details/gtaauglayt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenzaomai.com/Article/details/gtarpcyftd.html

[S24] C：获取本地时间
来源：http://dali.yj20258888.top/Article/details/gtdyfmxvfb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.svipenyu.cn/Article/details/gtitdfdizw.html

[S25] C：内存拷贝
来源：http://dali.shuidangran.top/Article/details/gtgtcfjabv.html

memcpy(dst, src, n);
来源：http://dali.0kj1m.cn/Article/details/gthyqxashn.html

[S26] C：内存清零
来源：http://dali.jqgufenzy.top/Article/details/gtypfdmeoi.html

memset(a, 0, sizeof a);
来源：http://dali.jinqigufen.top/Article/details/gtqqkxiaqm.html

[S27] C：定义常量
来源：http://dali.hysaishi.cn/Article/details/gtwnhhenfk.html

const double PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gttrawvfhd.html

[S28] C：静态变量
来源：http://dali.gaohongyu789.top/Article/details/gtwmpdulok.html

static int counter = 0;
来源：http://dali.316326.xyz/Article/details/gtwpijwjba.html

[S29] C：变参函数
来源：http://dali.daria6918.cn/Article/details/gtfovlqaqf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cqqwz.cn/Article/details/gtnqjgcjsy.html

[S30] C：头文件保护
来源：http://dali.sufxvd.cn/Article/details/gtbvsyucoe.html

#ifndef X_H
来源：http://dali.meibo888.top/Article/details/gtwzvutxkg.html

#define X_H
来源：http://dali.bjfxy.top/Article/details/gtjlcgnkcc.html

#endif
来源：http://dali.bjfxy.top/Article/details/gtqemlraki.html

[S31] C++：Hello World
来源：http://dali.shuidangran.top/Article/details/gttyyzuvin.html

#include <iostream>
来源：http://dali.svipenyu.cn/Article/details/gtwxolvuuu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zycfv.cn/Article/details/gtlrtidpns.html

[S32] C++：字符串
来源：http://dali.gaohongyu789.top/Article/details/gtbshqynpk.html

std::string s = "hi";  s += "!";
来源：http://dali.zycfv.cn/Article/details/gtkoajocup.html

[S33] C++：vector 增删
来源：http://dali.jianghu66.top/Article/details/gtfnklrvtz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xziqi.cn/Article/details/gtxzgxjeeg.html

[S34] C++：遍历 vector
来源：http://dali.ppjwa.cn/Article/details/gtfpdgkjtw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hfpthk.cn/Article/details/gtpazbvjjs.html

[S35] C++：map
来源：http://dali.tian-w.cn/Article/details/gthrwrxlbc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aizwys.cn/Article/details/gtiukofijf.html

[S36] C++：unordered_map
来源：http://dali.aizwys.cn/Article/details/gtamvsiiuj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtiubydlqc.html

[S37] C++：set
来源：http://dali.tian-w.cn/Article/details/gtersbjpnm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yongpay.top/Article/details/gtjztwdmod.html

[S38] C++：排序
来源：http://dali.sweek.top/Article/details/gtnnqnxfgk.html

std::sort(v.begin(), v.end());
来源：http://dali.sxryk.cn/Article/details/gtlkftxrnw.html

[S39] C++：自定义比较器排序
来源：http://dali.nwbrower.top/Article/details/gtmsbhjupo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xinyue.icu/Article/details/gtfrvvigji.html

[S40] C++：查找元素
来源：http://dali.smart0.xyz/Article/details/gtfzjfvdaw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.bjfxy.top/Article/details/gtqfhtxxuq.html

[S41] C++：类与构造函数
来源：http://dali.chenjidiqi.icu/Article/details/gtjrlpmdny.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.andypj.xyz/Article/details/gtwqgrgsxg.html

[S42] C++：继承与虚函数
来源：http://dali.aibaodan.cn/Article/details/gttuazdevy.html

class B : public Base { public: void f() override {} };
来源：http://dali.pengpengdd.cyou/Article/details/gtoznkcjtb.html

[S43] C++：智能指针
来源：http://dali.vqdsnc.cn/Article/details/gtqmbkcqtx.html

auto p = std::make_unique<int>(5);
来源：http://dali.yuxming.cn/Article/details/gttxqckcnl.html

[S44] C++：引用传参
来源：http://dali.shanyushiyangtech.top/Article/details/gttsopoukl.html

void inc(int &x) { ++x; }
来源：http://dali.redwolf501.top/Article/details/gteyykwjwa.html

[S45] C++：lambda
来源：http://dali.sweek.top/Article/details/gtkxhgqzff.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cashguo.top/Article/details/gtfxjvqbsb.html

[S46] C++：函数模板
来源：http://dali.yvedp.cn/Article/details/gtarfjnshi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yangfankeji.com/Article/details/gtzcmqwcuk.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj20258.top/Article/details/gtnvkwuivm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.wangdashe.top/Article/details/gtjjpqzchy.html

[S48] C++：逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvviighs.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hfpthk.cn/Article/details/gthnssgmez.html

while (std::getline(in, line)) { }
来源：http://dali.bjfxy.top/Article/details/gtfxecnqjy.html

[S49] C++：写文件
来源：http://dali.cqqwz.cn/Article/details/gtbfylyrui.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yonumen.top/Article/details/gtoexrdqlm.html

[S50] C++：格式化数字
来源：http://dali.zhixingplan.top/Article/details/gtjdrrkspd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gtdmbpmqau.html

[S51] C++：显式类型转换
来源：http://dali.ppjwa.cn/Article/details/gtxlmbhbpe.html

static_cast<double>(a) / b
来源：http://dali.yj20258888.top/Article/details/gtdnidouck.html

[S52] C++：const 与 noexcept
来源：http://dali.guowangkeji.top/Article/details/gtmwrzsgso.html

int size() const noexcept { return n_; }
来源：http://dali.sysykeji.top/Article/details/gtunfxnlwd.html

[S53] C++：移动语义
来源：http://dali.jinghuilouyu.cn/Article/details/gtvuwlbznk.html

std::vector<int> w = std::move(v);
来源：http://dali.nanxinkj.top/Article/details/gtsnjradwp.html

[S54] C++：异常处理
来源：http://dali.jiagoushi.top/Article/details/gtnbefxhfs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtukwnblhd.html

[S55] C++：结构化绑定
来源：http://dali.xziqi.cn/Article/details/gtdptyxgff.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhongyouzk.top/Article/details/gtddlucrxs.html

[S56] C++：optional
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxcydhgrg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.vqdsnc.cn/Article/details/gtlhjyqrlw.html

[S57] C++：编译期常量
来源：http://dali.yj20258888.top/Article/details/gtspxutnhf.html

constexpr int N = 10;
来源：http://dali.shzxlz.cn/Article/details/gtkpeejebe.html

[S58] C++：命名空间
来源：http://dali.iojbl.cn/Article/details/gtdigzdnbc.html

namespace ns { int f() { return 1; } }
来源：http://dali.fengsongda.top/Article/details/gtxwmfezhi.html

[S59] C++：静态断言
来源：http://dali.jiagoushi.top/Article/details/gtwirsgjwu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ppjwa.cn/Article/details/gtthpbyhey.html

[S60] C++：遍历并删除元素
来源：http://dali.aibaodan.cn/Article/details/gtsvtapnmn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zycfv.cn/Article/details/gtfdxkcwoc.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtkocxnbzd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ehwqpu.com/Article/details/gtqtskifhu.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtfqynwvnd.html

[T01] Kotlin：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtnorljdbs.html

println("Hello")
来源：http://dali.xylfe.cn/Article/details/gtxpuyzpro.html

[T02] Kotlin：变量
来源：http://dali.yueranfly.top/Article/details/gtfoilcnjf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ywan-chungtsiang.top/Article/details/gttusbtzcx.html

[T03] Kotlin：字符串模板
来源：http://dali.feifeiyinyue.top/Article/details/gtacamcmux.html

"值: $b"
来源：http://dali.zhiwuduotai.top/Article/details/gtozmgqwez.html

[T04] Kotlin：空安全
来源：http://dali.shzxlz.cn/Article/details/gtzyiyimji.html

val n: String? = null;  n?.length
来源：http://dali.yuxming.cn/Article/details/gtlbsgmdit.html

[T05] Kotlin：when 表达式
来源：http://dali.yuxming.cn/Article/details/gtooycqytp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gaohongyu789.top/Article/details/gtiprxxmtz.html

[T06] Kotlin：集合映射
来源：http://dali.xuanzx.com/Article/details/gtipzrjnhr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhixingplan.top/Article/details/gtzokpnspy.html

[T07] Kotlin：集合过滤
来源：http://dali.jinqigfzy.top/Article/details/gtqofpohhh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xziqi.cn/Article/details/gtqzcxaktb.html

[T08] Kotlin：数据类
来源：http://dali.quarkkingdee.top/Article/details/gtyiefeupy.html

data class User(val name: String, val age: Int)
来源：http://dali.zhixingplan.top/Article/details/gtnbejuqhp.html

[T09] Kotlin：扩展函数
来源：http://dali.zhixingplan.top/Article/details/gtnqiyvbnk.html

fun String.exclaim() = this + "!"
来源：http://dali.redwolf501.top/Article/details/gtqqelwfdb.html

[T10] Kotlin：默认参数
来源：http://dali.zhoulong.xyz/Article/details/gttzwfphqy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ivvv.top/Article/details/gterdfavsh.html

[T11] Kotlin：协程
来源：http://dali.hysaishi.cn/Article/details/gtdttenymd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yuxming.cn/Article/details/gtymipzclc.html

[T12] Kotlin：解构声明
来源：http://dali.shzxlz.cn/Article/details/gtebkxuwqs.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinqigufen.top/Article/details/gtbtyrhicy.html

[T13] Kotlin：只读 Map
来源：http://dali.nanxuanxn.top/Article/details/gtoyghwsff.html

val m = mapOf("a" to 1)
来源：http://dali.yj20258888.top/Article/details/gtswiniysi.html

[T14] Kotlin：循环
来源：http://dali.dianchejie.cn/Article/details/gtmanwiehu.html

for (i in 1..10) println(i)
来源：http://dali.birdmap.top/Article/details/gttjotymmv.html

[T15] Kotlin：接口
来源：http://dali.smart0.xyz/Article/details/gtletnsplj.html

interface Shape { fun area(): Double }
来源：http://dali.jlsjyb.cn/Article/details/gtaunxvoxh.html

[T16] Swift：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtztdymatl.html

print("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gtezswpxpn.html

[T17] Swift：变量与常量
来源：http://dali.hfpthk.cn/Article/details/gttpjwwrbq.html

var a = 1;  let b = 2
来源：http://dali.nwbrower.top/Article/details/gtmfdydtxz.html

[T18] Swift：字符串插值
来源：http://dali.ehwqpu.com/Article/details/gtzdjjqszq.html

"值: \(b)"
来源：http://dali.0kj1m.cn/Article/details/gttgklxuyd.html

[T19] Swift：可选绑定
来源：http://dali.zhoulong.xyz/Article/details/gtophinxbj.html

if let n = opt { print(n) }
来源：http://dali.bjfxy.top/Article/details/gtdqhpadpz.html

[T20] Swift：数组操作
来源：http://dali.havefunace.top/Article/details/gthnjwdvrx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.havefunace.top/Article/details/gtvlkrleby.html

[T21] Swift：遍历
来源：http://dali.jqgufenzy.top/Article/details/gtqledahtl.html

for x in a { print(x) }
来源：http://dali.zhiwuduotai.top/Article/details/gtifvpofkd.html

[T22] Swift：字典
来源：http://dali.gzhubu.top/Article/details/gtdznumpwg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hnqzz.top/Article/details/gtppvgazqr.html

[T23] Swift：函数
来源：http://dali.kuanghao11.cn/Article/details/gtokhfdydq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xziqi.cn/Article/details/gtuolvvfgs.html

[T24] Swift：闭包
来源：http://dali.jinghuilouyu.cn/Article/details/gtfsgtxyag.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtrgyichhs.html

[T25] Swift：结构体
来源：http://dali.haohaochexian.top/Article/details/gtpyotszrs.html

struct P { var x: Int }
来源：http://dali.gaohongyu789.top/Article/details/gtbvonywsn.html

[T26] Swift：类与重写
来源：http://dali.gotoacloud.top/Article/details/gtxsammssg.html

class A: Base { override func f() {} }
来源：http://dali.shanyushiyangtech.top/Article/details/gteitkpepx.html

[T27] Swift：错误处理
来源：http://dali.svipenyu.cn/Article/details/gtyjedrhcv.html

do { try f() } catch { print(error) }
来源：http://dali.cdnleiting.top/Article/details/gtalmszulw.html

[T28] Swift：枚举
来源：http://dali.xuetiantiany.cn/Article/details/gtupyqtozh.html

enum Color { case red, green }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpkhqledl.html

[T29] Swift：guard 提前返回
来源：http://dali.9152youxi.cn/Article/details/gtrymtrtzu.html

guard let x = opt else { return }
来源：http://dali.iojbl.cn/Article/details/gtobkgurgd.html

[T30] Swift：协议
来源：http://dali.yj20258888.top/Article/details/gtkuvagsgj.html

protocol Shape { func area() -> Double }
来源：http://dali.yongpay.top/Article/details/gtwjjpkfab.html

[T31] Lua：Hello World
来源：http://dali.yvedp.cn/Article/details/gtyzlxxxio.html

print("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gthzwsnfqy.html

[T32] Lua：局部变量
来源：http://dali.sufxvd.cn/Article/details/gtrusrarqv.html

local a = 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtagogcvnq.html

[T33] Lua：表（数组）
来源：http://dali.gzhubu.top/Article/details/gtqgajiqjn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.meibo888.top/Article/details/gttubegcbw.html

[T34] Lua：遍历表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkxqqdmsl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.daria6918.cn/Article/details/gtzqcckhhx.html

[T35] Lua：字典表
来源：http://dali.tanke756.top/Article/details/gteypenmwq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yangfankeji.com/Article/details/gtlqjnalwe.html

[T36] Lua：函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtoerqgdjb.html

function add(a, b) return a + b end
来源：http://dali.dashuyun.cn/Article/details/gtkhsnospl.html

[T37] Lua：字符串拼接
来源：http://dali.xziqi.cn/Article/details/gtrrpbdfne.html

"a" .. "b"
来源：http://dali.hammf.cn/Article/details/gtrnevaiwh.html

[T38] Lua：条件
来源：http://dali.jqgfzy.top/Article/details/gtmqkndmaq.html

if x > 0 then print("正") end
来源：http://dali.cqqwz.cn/Article/details/gtiidlqzbn.html

[T39] Lua：模式匹配
来源：http://dali.ydzc1.top/Article/details/gtvnrwcqel.html

string.find(s, "%d+")
来源：http://dali.haohaochexian.top/Article/details/gtlwtbmvin.html

[T40] Lua：元表
来源：http://dali.nanxuanxn.top/Article/details/gtxesnfraa.html

setmetatable({}, { __index = base })
来源：http://dali.andypj.xyz/Article/details/gtvgbffdaa.html

[T41] Perl：Hello World
来源：http://dali.ybcxt.top/Article/details/gttrkrijpv.html

print "Hello\n";
来源：http://dali.9152youxi.cn/Article/details/gtnrywwsgp.html

[T42] Perl：变量类型
来源：http://dali.yanxiufei.cn/Article/details/gtxfhudmjp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhiwuduotai.top/Article/details/gtmzhglgqc.html

[T43] Perl：字符串插值
来源：http://dali.aizwys.cn/Article/details/gtjciuzeeb.html

"值: $a"
来源：http://dali.xuetiantiany.cn/Article/details/gtuzlfvpcq.html

[T44] Perl：条件
来源：http://dali.jiagoushi.top/Article/details/gtwykyastw.html

if ($a > 0) { print "正"; }
来源：http://dali.fzhhl.top/Article/details/gttjnlvczs.html

[T45] Perl：数组遍历
来源：http://dali.shuidangran.top/Article/details/gtyzdtcqtb.html

for my $x (@arr) { print $x; }
来源：http://dali.hnqzz.top/Article/details/gttdlpzfgd.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gttwaljkmt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtgjuxjfdb.html

[T47] Perl：正则捕获
来源：http://dali.jinghuilouyu.cn/Article/details/gtckkxvytd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtudqfgkxb.html

[T48] Perl：正则替换
来源：http://dali.xylfe.cn/Article/details/gtkhfmrxhp.html

$s =~ s/old/new/g;
来源：http://dali.zycfv.cn/Article/details/gtqclweuwf.html

[T49] Perl：函数
来源：http://dali.pycfn.com/Article/details/gtuzppwpox.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gtevpkvklw.html

[T50] Perl：逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gtogghkraa.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.chenjidiqi.icu/Article/details/gtzqulyaqk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.0kj1m.cn/Article/details/gtymljguqq.html

[T51] Scala：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtfriumsuu.html

println("Hello")
来源：http://dali.cheryme.top/Article/details/gtsukwqxve.html

[T52] Scala：变量
来源：http://dali.wangdashe.top/Article/details/gtftzsbqhs.html

val a = 1;  var b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gtmzsxjqmq.html

[T53] Scala：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gtvjlcluch.html

s"值: $b"
来源：http://dali.yj202588.top/Article/details/gttknccrrb.html

[T54] Scala：集合映射
来源：http://dali.zhengqikj.top/Article/details/gtzxxcljvs.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.daxiang520.top/Article/details/gtjyguawxv.html

[T55] Scala：集合过滤
来源：http://dali.dianchejie.cn/Article/details/gtverqnfcb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sysykeji.top/Article/details/gtjlqsstwl.html

[T56] Scala：样例类
来源：http://dali.jqgfzy.top/Article/details/gtoikdoivp.html

case class User(name: String, age: Int)
来源：http://dali.jianghu66.top/Article/details/gtkgkukpxv.html

[T57] Scala：模式匹配
来源：http://dali.gogol.net.cn/Article/details/gtmtyyntza.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.pycfn.com/Article/details/gttyukoyoo.html

[T58] Scala：函数定义
来源：http://dali.hnxiangtu.top/Article/details/gtdwmuodrq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ivvv.top/Article/details/gtrwuxovip.html

[T59] Scala：循环
来源：http://dali.yangfankeji.com/Article/details/gtjppaiffz.html

for (i <- 1 to 10) println(i)
来源：http://dali.yvedp.cn/Article/details/gtrndgnhoj.html

[T60] Scala：折叠
来源：http://dali.cashguo.top/Article/details/gtieyagwel.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.daria6918.cn/Article/details/gtdlspmqsk.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtrhuixpcj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.sweek.top/Article/details/gtyhmmhjmv.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtahxiwnfc.html

[U01] Py：创建虚拟环境
来源：http://dali.shzxlz.cn/Article/details/gtjgfcfaex.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ppjwa.cn/Article/details/gtfezpngpc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jqgfzy.top/Article/details/gtisynipxu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.andypj.xyz/Article/details/gtdkalpxqe.html

[U03] Py：加载 .env 配置
来源：http://dali.yongpay.top/Article/details/gtneyzecrh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xziqi.cn/Article/details/gtpxguzoag.html

[U04] Py：变量调试打印
来源：http://dali.mhx1999.top/Article/details/gtewmwmvkg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinghuilouyu.cn/Article/details/gtqewgjtxz.html

[U05] Py：列表去重且保序
来源：http://dali.cheryme.top/Article/details/gtrrokuitm.html

list(dict.fromkeys(arr))
来源：http://dali.bjfxy.top/Article/details/gtnirzuzyo.html

[U06] Py：合并两个字典
来源：http://dali.shanyushiyangtech.top/Article/details/gtomurqliu.html

{**a, **b}
来源：http://dali.havefunace.top/Article/details/gtrjbernae.html

[U07] Py：反转字典键值
来源：http://dali.hfpthk.cn/Article/details/gteinjqile.html

{v: k for k, v in d.items()}
来源：http://dali.cqqwz.cn/Article/details/gtxjcfwqxb.html

[U08] Py：展平二维列表
来源：http://dali.jlsjyb.cn/Article/details/gtdskxwhsd.html

[y for x in nested for y in x]
来源：http://dali.yanxiufei.cn/Article/details/gtbdwviwsq.html

[U09] Py：字典取最大值的键
来源：http://dali.shangyingyoupin.top/Article/details/gtgpbhggnt.html

max(d, key=d.get)
来源：http://dali.chenlongwang.top/Article/details/gtvdknvrys.html

[U10] Py：按值排序字典
来源：http://dali.jqgfzy.top/Article/details/gtllgljxuj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.nwbrower.top/Article/details/gtjqwyrzxo.html

[U11] Py：生成器表达式
来源：http://dali.yj202588.top/Article/details/gtaxsompwy.html

(x * 2 for x in arr)
来源：http://dali.svipenyu.cn/Article/details/gtpupxsadx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhoulong.xyz/Article/details/gtbuwgiyqs.html

Counter(arr).most_common(3)
来源：http://dali.nanxinkj.top/Article/details/gtwyxdyrqf.html

[U13] Py：固定长度队列
来源：http://dali.birdmap.top/Article/details/gtanznsrpl.html

deque(maxlen=10)
来源：http://dali.chenzaomai.com/Article/details/gtnltvykqu.html

[U14] Py：分组收集到列表
来源：http://dali.0kj1m.cn/Article/details/gtzjgsqhrw.html

defaultdict(list)
来源：http://dali.ivvv.top/Article/details/gthdxqgjis.html

[U15] Py：高精度计时
来源：http://dali.haohaochexian.top/Article/details/gttluuqvvh.html

t = time.perf_counter()
来源：http://dali.tanke756.top/Article/details/gtaktyzurl.html

[U16] Py：命令行参数解析
来源：http://dali.vqdsnc.cn/Article/details/gtwgjknmbo.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.dashuyun.cn/Article/details/gtlhjqqotd.html

[U17] Py：初始化日志
来源：http://dali.jlsjyb.cn/Article/details/gtoswgqaza.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ehwqpu.com/Article/details/gttkyyjlia.html

[U18] Py：预编译正则
来源：http://dali.havefunace.top/Article/details/gtgipvimgm.html

pat = re.compile(r"\d+")
来源：http://dali.iojbl.cn/Article/details/gtktlhhvyl.html

[U19] Py：正则替换带回调
来源：http://dali.snrcjt.cn/Article/details/gtoqlfvoch.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yonumen.top/Article/details/gtvzncokzb.html

[U20] Py：缓存函数结果
来源：http://dali.shangyingyoupin.top/Article/details/gtwcqpdfvz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.haohaochexian.top/Article/details/gtoighslws.html

[U21] Py：自定义上下文管理器
来源：http://dali.smart0.xyz/Article/details/gtdcggjoyw.html

@contextlib.contextmanager
来源：http://dali.kuanghao11.cn/Article/details/gttyddmeqw.html

[U22] Py：矩阵转置
来源：http://dali.chenjidiqi.icu/Article/details/gtvujctptn.html

list(zip(*m))
来源：http://dali.zhoulong.xyz/Article/details/gtxoqpcjwj.html

[U23] Py：分块读取大文件
来源：http://dali.sxryk.cn/Article/details/gtkmrzejku.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jiagoushi.top/Article/details/gttjxkachn.html

[U24] Py：路径操作
来源：http://dali.yueranfly.top/Article/details/gtljbzeqpo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yj20258888.top/Article/details/gtzbrriafu.html

[U25] Py：CSV 按字典读
来源：http://dali.sysykeji.top/Article/details/gthszwqohz.html

csv.DictReader(f)
来源：http://dali.yangfankeji.com/Article/details/gtliqkhvbg.html

[U26] Py：并发下载
来源：http://dali.9152youxi.cn/Article/details/gtudqoiwya.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cdnleiting.top/Article/details/gtbhkptvhc.html

[U27] Py：异步 HTTP
来源：http://dali.aizwys.cn/Article/details/gtqaajnpwj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.feifeiyinyue.top/Article/details/gtbcguwyhg.html

[U28] Py：类型别名
来源：http://dali.hfpthk.cn/Article/details/gtrlyyanec.html

UserId = int
来源：http://dali.hywenlv.cn/Article/details/gtikxrxafv.html


<!-- 参考信息 -->