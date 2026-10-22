代发 wailian999

FILE *f = fopen("a.txt", "r");
来源：http://dali.ehwqpu.com/Article/details/gtwffribpf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yanxiufei.cn/Article/details/gtipllsvob.html

fclose(f);
来源：http://dali.wangshuangyany.cn/Article/details/gtvbxglgmj.html

[S12] C：写文件
来源：http://dali.shangyingyoupin.top/Article/details/gtjziiaice.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.pycfn.com/Article/details/gtladoehzf.html

[S13] C：宏定义
来源：http://dali.9152youxi.cn/Article/details/gtvvhaqziv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.dashuyun.cn/Article/details/gtmxijgfvh.html

[S14] C：枚举
来源：http://dali.yj20258888.top/Article/details/gtabndhjos.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xinyue.icu/Article/details/gtjoinnrww.html

[S15] C：类型转换
来源：http://dali.haohaochexian.top/Article/details/gtfwcdcqky.html

(double) a / b
来源：http://dali.hysaishi.cn/Article/details/gtevplpqdg.html

[S16] C：位操作置位
来源：http://dali.ywan-chungtsiang.top/Article/details/gteofmabfn.html

x |= (1 << 3);
来源：http://dali.gotoacloud.top/Article/details/gtjepurbgn.html

[S17] C：安全拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gtkangcgqv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.c1oappe.top/Article/details/gtzbkpieoy.html

[S18] C：命令行参数
来源：http://dali.cqqwz.cn/Article/details/gtpioajyer.html

int main(int argc, char **argv)
来源：http://dali.yj20258888.top/Article/details/gtziiabcbo.html

[S19] C：快速排序
来源：http://dali.sxryk.cn/Article/details/gtdltdibdi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ppjwa.cn/Article/details/gtshzrzclq.html

[S20] C：二分查找
来源：http://dali.pycfn.com/Article/details/gtunagshjm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhixingplan.top/Article/details/gtzemtgcpi.html

[S21] C：字符类别判断
来源：http://dali.shangyingyoupin.top/Article/details/gtvfnxljpr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.0kj1m.cn/Article/details/gtczvvwnuw.html

[S22] C：字符串转数字
来源：http://dali.jianghu66.top/Article/details/gtepqqhmru.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yongpay.top/Article/details/gtduzmbdvk.html

[S23] C：随机数
来源：http://dali.birdmap.top/Article/details/gtmwkfjctn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.nwbrower.top/Article/details/gtrevnhgiv.html

[S24] C：获取本地时间
来源：http://dali.cqqwz.cn/Article/details/gtlnirhilv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shzxlz.cn/Article/details/gtdgvwnyhf.html

[S25] C：内存拷贝
来源：http://dali.hammf.cn/Article/details/gtynhbqavs.html

memcpy(dst, src, n);
来源：http://dali.nanxinkj.top/Article/details/gtkzhwphis.html

[S26] C：内存清零
来源：http://dali.xuanzx.com/Article/details/gtthsdwlqm.html

memset(a, 0, sizeof a);
来源：http://dali.daxiang520.top/Article/details/gtzvucvyok.html

[S27] C：定义常量
来源：http://dali.zhixingplan.top/Article/details/gtqqvzgjrd.html

const double PI = 3.14159;
来源：http://dali.316326.xyz/Article/details/gtxgwxgwzg.html

[S28] C：静态变量
来源：http://dali.yvedp.cn/Article/details/gtvnhwmfyo.html

static int counter = 0;
来源：http://dali.zhixingplan.top/Article/details/gtnwdetfzj.html

[S29] C：变参函数
来源：http://dali.quarkkingdee.top/Article/details/gtlfacaxff.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shuidangran.top/Article/details/gtylthrvnc.html

[S30] C：头文件保护
来源：http://dali.yvedp.cn/Article/details/gtnfulzmgp.html

#ifndef X_H
来源：http://dali.0kj1m.cn/Article/details/gtgmaxobxb.html

#define X_H
来源：http://dali.smart0.xyz/Article/details/gtczafxavl.html

#endif
来源：http://dali.gzhubu.top/Article/details/gtpgxqhnfb.html

[S31] C++：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtowtjyiez.html

#include <iostream>
来源：http://dali.tianlin.xyz/Article/details/gtcjpzjqpo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nwbrower.top/Article/details/gtjkksvqfq.html

[S32] C++：字符串
来源：http://dali.jqgufenzy.top/Article/details/gtsqbiujcc.html

std::string s = "hi";  s += "!";
来源：http://dali.aibaodan.cn/Article/details/gtrvwajgzm.html

[S33] C++：vector 增删
来源：http://dali.dashuyun.cn/Article/details/gtxmeqoihd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xinyue.icu/Article/details/gtnhfldylp.html

[S34] C++：遍历 vector
来源：http://dali.havefunace.top/Article/details/gthkmbgkfp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ivvv.top/Article/details/gtddnyxuar.html

[S35] C++：map
来源：http://dali.cucudq.cn/Article/details/gtubslwakh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yongpay.top/Article/details/gtoqcdtdll.html

[S36] C++：unordered_map
来源：http://dali.jinqigfzy.top/Article/details/gthcvahkuc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daxiang520.top/Article/details/gthhxojtur.html

[S37] C++：set
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdzmnylsu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.aizwys.cn/Article/details/gtprpktmyf.html

[S38] C++：排序
来源：http://dali.xziqi.cn/Article/details/gtqxrzivlw.html

std::sort(v.begin(), v.end());
来源：http://dali.tanke756.top/Article/details/gtcqthxnvl.html

[S39] C++：自定义比较器排序
来源：http://dali.haohaochexian.top/Article/details/gtakfeukvf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.wangdashe.top/Article/details/gtaspsuquw.html

[S40] C++：查找元素
来源：http://dali.nwbrower.top/Article/details/gtmvesyzkr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jqgfzy.top/Article/details/gtpiugnqon.html

[S41] C++：类与构造函数
来源：http://dali.meibo888.top/Article/details/gtnucvskyq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.daxiang520.top/Article/details/gtceqfoasm.html

[S42] C++：继承与虚函数
来源：http://dali.yj20258.top/Article/details/gtixnecpac.html

class B : public Base { public: void f() override {} };
来源：http://dali.shangyingyoupin.top/Article/details/gtiwcesntl.html

[S43] C++：智能指针
来源：http://dali.quarkkingdee.top/Article/details/gtaflymnzo.html

auto p = std::make_unique<int>(5);
来源：http://dali.redwolf501.top/Article/details/gtjrwscbdd.html

[S44] C++：引用传参
来源：http://dali.svipenyu.cn/Article/details/gtycylauej.html

void inc(int &x) { ++x; }
来源：http://dali.ydzc1.top/Article/details/gtewaadgyo.html

[S45] C++：lambda
来源：http://dali.sxryk.cn/Article/details/gtlxcagrzz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yueranfly.top/Article/details/gtpxpubqkg.html

[S46] C++：函数模板
来源：http://dali.hnxiangtu.top/Article/details/gtseawvkhg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yvedp.cn/Article/details/gtgzwjfybg.html

[S47] C++：结构化绑定遍历
来源：http://dali.redwolf501.top/Article/details/gtkjphrqyv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xuetiantiany.cn/Article/details/gtmzhkcrbg.html

[S48] C++：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gtbnqcommd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hongshengwenyu.top/Article/details/gtqvmwgrer.html

while (std::getline(in, line)) { }
来源：http://dali.aibaodan.cn/Article/details/gtmzmmcfqc.html

[S49] C++：写文件
来源：http://dali.yanxiufei.cn/Article/details/gtzjoxdrlg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ppjwa.cn/Article/details/gtssknqtgh.html

[S50] C++：格式化数字
来源：http://dali.chenjidiqi.icu/Article/details/gtxercfglm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gtefizltuv.html

[S51] C++：显式类型转换
来源：http://dali.9152youxi.cn/Article/details/gtzhswwlig.html

static_cast<double>(a) / b
来源：http://dali.xuetiantiany.cn/Article/details/gtowefnlrx.html

[S52] C++：const 与 noexcept
来源：http://dali.zycfv.cn/Article/details/gtqldsdqze.html

int size() const noexcept { return n_; }
来源：http://dali.chenzaomai.com/Article/details/gtrdxoyaeh.html

[S53] C++：移动语义
来源：http://dali.dashuyun.cn/Article/details/gtunaxhhzd.html

std::vector<int> w = std::move(v);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwklluzbo.html

[S54] C++：异常处理
来源：http://dali.yj20258888.top/Article/details/gtuyiysueq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.bjfxy.top/Article/details/gtqjdwrcrh.html

[S55] C++：结构化绑定
来源：http://dali.nanxuanxn.top/Article/details/gtakcwthxu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtcwfvksko.html

[S56] C++：optional
来源：http://dali.dianchejie.cn/Article/details/gtntguspsh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yvedp.cn/Article/details/gtcaxcgkuo.html

[S57] C++：编译期常量
来源：http://dali.hnqzz.top/Article/details/gtikvcinpr.html

constexpr int N = 10;
来源：http://dali.zhongyouzk.top/Article/details/gtrocxphcw.html

[S58] C++：命名空间
来源：http://dali.xinyue.icu/Article/details/gtzhuzzthr.html

namespace ns { int f() { return 1; } }
来源：http://dali.dashuyun.cn/Article/details/gtiaatvcrm.html

[S59] C++：静态断言
来源：http://dali.jyoumei.cn/Article/details/gtbkfzowra.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinqigufen.top/Article/details/gtsghhrqor.html

[S60] C++：遍历并删除元素
来源：http://dali.zhiwuduotai.top/Article/details/gtnjxqdgnb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.c1oappe.top/Article/details/gtgdxtwdvx.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtuolugbjy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hywenlv.cn/Article/details/gtuvdyqxkv.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtymiyqtmn.html

[T01] Kotlin：Hello World
来源：http://dali.tian-w.cn/Article/details/gtvpkhdzhv.html

println("Hello")
来源：http://dali.sysykeji.top/Article/details/gtuvptlnjj.html

[T02] Kotlin：变量
来源：http://dali.hnqzz.top/Article/details/gtqthleyig.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ydzc1.top/Article/details/gtlwmuosif.html

[T03] Kotlin：字符串模板
来源：http://dali.havefunace.top/Article/details/gtwdxyxrsf.html

"值: $b"
来源：http://dali.yj202588.top/Article/details/gtdmwvrwyc.html

[T04] Kotlin：空安全
来源：http://dali.dashuyun.cn/Article/details/gtzzxmsnrb.html

val n: String? = null;  n?.length
来源：http://dali.jqgufenzy.top/Article/details/gtmipbxfyn.html

[T05] Kotlin：when 表达式
来源：http://dali.fzhhl.top/Article/details/gtusjbpmyv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jqgufenzy.top/Article/details/gtdllezpza.html

[T06] Kotlin：集合映射
来源：http://dali.nwbrower.top/Article/details/gtbjmxsmvk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shuidangran.top/Article/details/gtijrilebj.html

[T07] Kotlin：集合过滤
来源：http://dali.yuanzhike.top/Article/details/gtltqdfgkx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.iojbl.cn/Article/details/gtzcpkvcuj.html

[T08] Kotlin：数据类
来源：http://dali.nanxinkj.top/Article/details/gtiwyaqcfn.html

data class User(val name: String, val age: Int)
来源：http://dali.zhoulong.xyz/Article/details/gtzwptwcsc.html

[T09] Kotlin：扩展函数
来源：http://dali.yonumen.top/Article/details/gtgiymcfke.html

fun String.exclaim() = this + "!"
来源：http://dali.snrcjt.cn/Article/details/gtxkldhmty.html

[T10] Kotlin：默认参数
来源：http://dali.birdmap.top/Article/details/gtmcknygnd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.redwolf501.top/Article/details/gtrmzawabt.html

[T11] Kotlin：协程
来源：http://dali.hnxiangtu.top/Article/details/gtjmnihgxg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sufxvd.cn/Article/details/gtpkcbjtev.html

[T12] Kotlin：解构声明
来源：http://dali.haohaochexian.top/Article/details/gtaeesahoh.html

val (a, b) = Pair(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqqctubgp.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gtkdtineop.html

val m = mapOf("a" to 1)
来源：http://dali.cheryme.top/Article/details/gtepolknyv.html

[T14] Kotlin：循环
来源：http://dali.hongshengwenyu.top/Article/details/gttdwqldpb.html

for (i in 1..10) println(i)
来源：http://dali.gotoacloud.top/Article/details/gthguiwbnw.html

[T15] Kotlin：接口
来源：http://dali.316326.xyz/Article/details/gtwfgxjfud.html

interface Shape { fun area(): Double }
来源：http://dali.haohaochexian.top/Article/details/gtbtfyuafd.html

[T16] Swift：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtoaigddgo.html

print("Hello")
来源：http://dali.dashuyun.cn/Article/details/gtvftpghpe.html

[T17] Swift：变量与常量
来源：http://dali.bjfxy.top/Article/details/gtapgdpksg.html

var a = 1;  let b = 2
来源：http://dali.sxryk.cn/Article/details/gtqhdvivit.html

[T18] Swift：字符串插值
来源：http://dali.jyoumei.cn/Article/details/gtauudoxjs.html

"值: \(b)"
来源：http://dali.hfpthk.cn/Article/details/gtexocqlfy.html

[T19] Swift：可选绑定
来源：http://dali.wangshuangyany.cn/Article/details/gtlhkfdoqf.html

if let n = opt { print(n) }
来源：http://dali.zhoulong.xyz/Article/details/gtykbnvsdg.html

[T20] Swift：数组操作
来源：http://dali.yangfankeji.com/Article/details/gtnhdjlwue.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhoulong.xyz/Article/details/gtjymhecnn.html

[T21] Swift：遍历
来源：http://dali.smart0.xyz/Article/details/gtvmjchhki.html

for x in a { print(x) }
来源：http://dali.yonumen.top/Article/details/gttehnxmob.html

[T22] Swift：字典
来源：http://dali.yanxiufei.cn/Article/details/gthgigvqlt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.fengsongda.top/Article/details/gtnmnalrbi.html

[T23] Swift：函数
来源：http://dali.redwolf501.top/Article/details/gtcirshfpi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.0kj1m.cn/Article/details/gtiburewow.html

[T24] Swift：闭包
来源：http://dali.nwbrower.top/Article/details/gteqttgbjm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.tanke756.top/Article/details/gtpdlawhkr.html

[T25] Swift：结构体
来源：http://dali.dashuyun.cn/Article/details/gtdlplpnpa.html

struct P { var x: Int }
来源：http://dali.pengpengdd.cyou/Article/details/gtrjwcvvev.html

[T26] Swift：类与重写
来源：http://dali.316326.xyz/Article/details/gtuspndioj.html

class A: Base { override func f() {} }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfmdnsbvi.html

[T27] Swift：错误处理
来源：http://dali.svipenyu.cn/Article/details/gthnofbpst.html

do { try f() } catch { print(error) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehikrxnw.html

[T28] Swift：枚举
来源：http://dali.gzhubu.top/Article/details/gtoenlxxwm.html

enum Color { case red, green }
来源：http://dali.gogol.net.cn/Article/details/gtxnoohwbi.html

[T29] Swift：guard 提前返回
来源：http://dali.havefunace.top/Article/details/gtjjrmjcqs.html

guard let x = opt else { return }
来源：http://dali.hongshengwenyu.top/Article/details/gtbiytfacm.html

[T30] Swift：协议
来源：http://dali.9152youxi.cn/Article/details/gtgorhuyqp.html

protocol Shape { func area() -> Double }
来源：http://dali.hammf.cn/Article/details/gtnldersfn.html

[T31] Lua：Hello World
来源：http://dali.316326.xyz/Article/details/gtkivnsyys.html

print("Hello")
来源：http://dali.xziqi.cn/Article/details/gtpremzghr.html

[T32] Lua：局部变量
来源：http://dali.yuxming.cn/Article/details/gtbujkdlgj.html

local a = 1
来源：http://dali.jinqigufen.top/Article/details/gtqnczmahb.html

[T33] Lua：表（数组）
来源：http://dali.jqgfzy.top/Article/details/gtlojuhmjm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.redwolf501.top/Article/details/gtzbetjclu.html

[T34] Lua：遍历表
来源：http://dali.ivvv.top/Article/details/gtnxilqmvm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hnxiangtu.top/Article/details/gttdiywkyp.html

[T35] Lua：字典表
来源：http://dali.yj20258888.top/Article/details/gtvapaqvas.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jianghu66.top/Article/details/gtncwmcjah.html

[T36] Lua：函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtinmbsvbh.html

function add(a, b) return a + b end
来源：http://dali.ybcxt.top/Article/details/gtuxrbesne.html

[T37] Lua：字符串拼接
来源：http://dali.jiagoushi.top/Article/details/gtkaflmfsl.html

"a" .. "b"
来源：http://dali.jinghuilouyu.cn/Article/details/gtcoxynkqs.html

[T38] Lua：条件
来源：http://dali.shuidangran.top/Article/details/gtostlldbh.html

if x > 0 then print("正") end
来源：http://dali.jiagoushi.top/Article/details/gtdydyxoii.html

[T39] Lua：模式匹配
来源：http://dali.hysaishi.cn/Article/details/gtktxxvqkd.html

string.find(s, "%d+")
来源：http://dali.ydzc1.top/Article/details/gtkdplikgd.html

[T40] Lua：元表
来源：http://dali.tian-w.cn/Article/details/gtonqmdpnr.html

setmetatable({}, { __index = base })
来源：http://dali.nanxinkj.top/Article/details/gtifiqmdqr.html

[T41] Perl：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtsdshgpxc.html

print "Hello\n";
来源：http://dali.zhixingplan.top/Article/details/gtjqrfnojj.html

[T42] Perl：变量类型
来源：http://dali.hammf.cn/Article/details/gthkyuegdd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjbdgrjyy.html

[T43] Perl：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gtfbcskqab.html

"值: $a"
来源：http://dali.gogol.net.cn/Article/details/gtaajvilmv.html

[T44] Perl：条件
来源：http://dali.yj20258.top/Article/details/gtrvuxhqwu.html

if ($a > 0) { print "正"; }
来源：http://dali.yangfankeji.com/Article/details/gtuujimpet.html

[T45] Perl：数组遍历
来源：http://dali.ivvv.top/Article/details/gtlwkdfucs.html

for my $x (@arr) { print $x; }
来源：http://dali.hnqzz.top/Article/details/gtcekyfjnj.html

[T46] Perl：哈希操作
来源：http://dali.mhx1999.top/Article/details/gtedzhcidk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cqqwz.cn/Article/details/gtcoewxkqw.html

[T47] Perl：正则捕获
来源：http://dali.iojbl.cn/Article/details/gtlqdnvvwc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ivvv.top/Article/details/gtwndnoqmg.html

[T48] Perl：正则替换
来源：http://dali.9152youxi.cn/Article/details/gtvsqozgpc.html

$s =~ s/old/new/g;
来源：http://dali.ivvv.top/Article/details/gtgnjzxjxj.html

[T49] Perl：函数
来源：http://dali.zdqjudy.top/Article/details/gtleibfvkf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinqigfzy.top/Article/details/gtzgzpvsbs.html

[T50] Perl：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtxgkbklry.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.pengpengdd.cyou/Article/details/gtvxgkxqjr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sweek.top/Article/details/gtqfptrqbw.html

[T51] Scala：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtbtjtcetu.html

println("Hello")
来源：http://dali.hywenlv.cn/Article/details/gtkbzahnoz.html

[T52] Scala：变量
来源：http://dali.9152youxi.cn/Article/details/gtamujoxla.html

val a = 1;  var b = 2
来源：http://dali.nanxinkj.top/Article/details/gtyvtjaruq.html

[T53] Scala：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gtsvaezbud.html

s"值: $b"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtltwqqgnp.html

[T54] Scala：集合映射
来源：http://dali.guowangkeji.top/Article/details/gttepokyjq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ppjwa.cn/Article/details/gtpcyjdumk.html

[T55] Scala：集合过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtphwytvhf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtviaabbuk.html

[T56] Scala：样例类
来源：http://dali.dashuyun.cn/Article/details/gtwaxzabdo.html

case class User(name: String, age: Int)
来源：http://dali.yanxiufei.cn/Article/details/gtxiywspti.html

[T57] Scala：模式匹配
来源：http://dali.redwolf501.top/Article/details/gtngarytok.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gotoacloud.top/Article/details/gtwwtxvylm.html

[T58] Scala：函数定义
来源：http://dali.tianlin.xyz/Article/details/gtfnsfpqfg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.iojbl.cn/Article/details/gtiuquxeys.html

[T59] Scala：循环
来源：http://dali.hnqzz.top/Article/details/gtcsnpmnay.html

for (i <- 1 to 10) println(i)
来源：http://dali.aizwys.cn/Article/details/gtetehiwxv.html

[T60] Scala：折叠
来源：http://dali.zhoulong.xyz/Article/details/gtdqodleap.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhongyouzk.top/Article/details/gtnflpsdnx.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtmtsnrwef.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtkwpavvhp.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtzatxkyxo.html

[U01] Py：创建虚拟环境
来源：http://dali.iojbl.cn/Article/details/gtpcwcumcu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hfpthk.cn/Article/details/gtdtuqaora.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shuidangran.top/Article/details/gtsucahais.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.snrcjt.cn/Article/details/gtutdbacwr.html

[U03] Py：加载 .env 配置
来源：http://dali.xinyue.icu/Article/details/gtfqjpmrka.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cashguo.top/Article/details/gtehvuwzrh.html

[U04] Py：变量调试打印
来源：http://dali.yj202588.top/Article/details/gtmrswoffv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhiwuduotai.top/Article/details/gtqtbodder.html

[U05] Py：列表去重且保序
来源：http://dali.cqqwz.cn/Article/details/gtvavtowiw.html

list(dict.fromkeys(arr))
来源：http://dali.yuanzhike.top/Article/details/gtsdwaanpw.html

[U06] Py：合并两个字典
来源：http://dali.zhengqikj.top/Article/details/gtmxwvcogc.html

{**a, **b}
来源：http://dali.andypj.xyz/Article/details/gtzpvwkbhn.html

[U07] Py：反转字典键值
来源：http://dali.aizwys.cn/Article/details/gtlrqefnhx.html

{v: k for k, v in d.items()}
来源：http://dali.zhixingplan.top/Article/details/gthsxxptxe.html

[U08] Py：展平二维列表
来源：http://dali.yuxming.cn/Article/details/gtcaukpela.html

[y for x in nested for y in x]
来源：http://dali.yueranfly.top/Article/details/gtmglmgitm.html

[U09] Py：字典取最大值的键
来源：http://dali.cashguo.top/Article/details/gttkjtzwbl.html

max(d, key=d.get)
来源：http://dali.pengpengdd.cyou/Article/details/gtivsflvhr.html

[U10] Py：按值排序字典
来源：http://dali.wangdashe.top/Article/details/gthyijkzkd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.haohaochexian.top/Article/details/gtnspzsxxb.html

[U11] Py：生成器表达式
来源：http://dali.gaohongyu789.top/Article/details/gtcoonggcx.html

(x * 2 for x in arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaoorespt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yj202588.top/Article/details/gtqgcpifsm.html

Counter(arr).most_common(3)
来源：http://dali.mhx1999.top/Article/details/gtudbzfhsy.html

[U13] Py：固定长度队列
来源：http://dali.yvedp.cn/Article/details/gtuwupfbmp.html

deque(maxlen=10)
来源：http://dali.cqqwz.cn/Article/details/gtxjpotiyz.html

[U14] Py：分组收集到列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjdsiizdk.html

defaultdict(list)
来源：http://dali.chenzaomai.com/Article/details/gtqjqgrqnh.html

[U15] Py：高精度计时
来源：http://dali.yangfankeji.com/Article/details/gtbhuzmlav.html

t = time.perf_counter()
来源：http://dali.gzhubu.top/Article/details/gtujlhyxgp.html

[U16] Py：命令行参数解析
来源：http://dali.gaohongyu789.top/Article/details/gtyyugtogv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shanyushiyangtech.top/Article/details/gtlsyoakiz.html

[U17] Py：初始化日志
来源：http://dali.xuetiantiany.cn/Article/details/gtspjgfraa.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hammf.cn/Article/details/gtsjjdqwdz.html

[U18] Py：预编译正则
来源：http://dali.pycfn.com/Article/details/gtznqgxddp.html

pat = re.compile(r"\d+")
来源：http://dali.jqgufenzy.top/Article/details/gtkmuijtxi.html

[U19] Py：正则替换带回调
来源：http://dali.gotoacloud.top/Article/details/gtxlzrquxv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.cdnleiting.top/Article/details/gtvhunmqxd.html

[U20] Py：缓存函数结果
来源：http://dali.feifeiyinyue.top/Article/details/gtmjqbzszx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gtestjahsw.html

[U21] Py：自定义上下文管理器
来源：http://dali.ehwqpu.com/Article/details/gtcrrjhqvd.html

@contextlib.contextmanager
来源：http://dali.guannengcc.top/Article/details/gtvlfjmhvx.html

[U22] Py：矩阵转置
来源：http://dali.cheryme.top/Article/details/gtrcrrzocu.html

list(zip(*m))
来源：http://dali.tian-w.cn/Article/details/gtnakxrqyw.html

[U23] Py：分块读取大文件
来源：http://dali.yuxming.cn/Article/details/gtvlgsymrk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhoulong.xyz/Article/details/gtoxwjphyt.html

[U24] Py：路径操作
来源：http://dali.xinyue.icu/Article/details/gttkyybago.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jinqigfzy.top/Article/details/gtyrmxavwt.html

[U25] Py：CSV 按字典读
来源：http://dali.sweek.top/Article/details/gtuhlpidav.html

csv.DictReader(f)
来源：http://dali.havefunace.top/Article/details/gthrpelcjy.html

[U26] Py：并发下载
来源：http://dali.yongpay.top/Article/details/gtvjkfpwbr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jianghu66.top/Article/details/gtzjahxdlw.html

[U27] Py：异步 HTTP
来源：http://dali.ivvv.top/Article/details/gtuegvnfkt.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.aizwys.cn/Article/details/gtnqiwschn.html

[U28] Py：类型别名
来源：http://dali.feifeiyinyue.top/Article/details/gtfzavzhkw.html

UserId = int
来源：http://dali.kuanghao11.cn/Article/details/gtruyypabn.html

[U29] Py：属性校验
来源：http://dali.nanxuanxn.top/Article/details/gtjxgoljgv.html

@property 与 @x.setter 配合
来源：http://dali.cqqwz.cn/Article/details/gtcdvzbksu.html

[U30] Py：数据类
来源：http://dali.sweek.top/Article/details/gtekgryrfi.html

@dataclass(slots=True)
来源：http://dali.redwolf501.top/Article/details/gtymqerojv.html

[U31] Py：单测
来源：http://dali.zhixingplan.top/Article/details/gtcqryetyy.html

python -m pytest -q
来源：http://dali.nanxuanxn.top/Article/details/gtbliipiiv.html

[U32] Py：代码格式化
来源：http://dali.chenlongwang.top/Article/details/gtzwwuxiqc.html

ruff format . && ruff check --fix .
来源：http://dali.jqgfzy.top/Article/details/gthbvunaaw.html

[U33] Py：打包发布
来源：http://dali.jlsjyb.cn/Article/details/gtyafzhvfw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hnxiangtu.top/Article/details/gtdrgjuarm.html

[U34] Py：判断编码
来源：http://dali.dashuyun.cn/Article/details/gtwqqsgvxw.html

chardet.detect(raw)
来源：http://dali.zhengqikj.top/Article/details/gtrajkhsnh.html


<!-- 参考信息 -->