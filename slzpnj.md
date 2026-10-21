代发 wailian999

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.dashuyun.cn/Article/details/gtlreumygf.html

[S02] C：变量与格式化输出
来源：http://dali.chenjidiqi.icu/Article/details/gtpvravchl.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhiwuduotai.top/Article/details/gthwdaycbf.html

[S03] C：读入整数
来源：http://dali.cqqwz.cn/Article/details/gtqkgxrild.html

int x; scanf("%d", &x);
来源：http://dali.tian-w.cn/Article/details/gtcukarifn.html

[S04] C：字符串复制
来源：http://dali.iojbl.cn/Article/details/gteldknxuq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhoulong.xyz/Article/details/gtqcwrlrqd.html

[S05] C：字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtzarcixsl.html

strlen(s)
来源：http://dali.havefunace.top/Article/details/gtveyuszis.html

[S06] C：字符串比较
来源：http://dali.sysykeji.top/Article/details/gthvytpmdr.html

strcmp(a, b) == 0
来源：http://dali.yueranfly.top/Article/details/gtsabnojgq.html

[S07] C：数组遍历求和
来源：http://dali.daxiang520.top/Article/details/gtkbpbmmth.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhongyouzk.top/Article/details/gticvaaynp.html

[S08] C：动态内存分配与释放
来源：http://dali.wangdashe.top/Article/details/gtfkarqbcy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.birdmap.top/Article/details/gtuojqlrjg.html

[S09] C：结构体定义与初始化
来源：http://dali.chenzaomai.com/Article/details/gtrtcavrcz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpvjcsreo.html

[S10] C：指针与解引用
来源：http://dali.jinqigufen.top/Article/details/gtfvgdrkjc.html

int *p = &a;  *p = 5;
来源：http://dali.sxryk.cn/Article/details/gtjyrmcphi.html

[S11] C：逐行读文件
来源：http://dali.yonumen.top/Article/details/gtpefsnypv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.vqdsnc.cn/Article/details/gtsfcexjhg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zycfv.cn/Article/details/gtcektiqhx.html

fclose(f);
来源：http://dali.shangyingyoupin.top/Article/details/gtctjrmujw.html

[S12] C：写文件
来源：http://dali.yanxiufei.cn/Article/details/gtbnikhrck.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.aibaodan.cn/Article/details/gtjfqtsuad.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gtbcnvworo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gtyjeknrng.html

[S14] C：枚举
来源：http://dali.hywenlv.cn/Article/details/gtqieiicxk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.fzhhl.top/Article/details/gtsvoyuunl.html

[S15] C：类型转换
来源：http://dali.gotoacloud.top/Article/details/gtwlrynqsn.html

(double) a / b
来源：http://dali.shangyingyoupin.top/Article/details/gtnpnyzpxn.html

[S16] C：位操作置位
来源：http://dali.guowangkeji.top/Article/details/gtvfwpkzmr.html

x |= (1 << 3);
来源：http://dali.gaohongyu789.top/Article/details/gtwcqribiw.html

[S17] C：安全拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gthkpszhlq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkvtroibg.html

[S18] C：命令行参数
来源：http://dali.gogol.net.cn/Article/details/gttxhpaukf.html

int main(int argc, char **argv)
来源：http://dali.xuanzx.com/Article/details/gtbsnwiyak.html

[S19] C：快速排序
来源：http://dali.aibaodan.cn/Article/details/gtscxdzuke.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zdqjudy.top/Article/details/gtdwymyqag.html

[S20] C：二分查找
来源：http://dali.yanxiufei.cn/Article/details/gttnruourt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gaohongyu789.top/Article/details/gtdmeonbxj.html

[S21] C：字符类别判断
来源：http://dali.yanxiufei.cn/Article/details/gtxromhrll.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.aizwys.cn/Article/details/gtvegsqvoe.html

[S22] C：字符串转数字
来源：http://dali.pycfn.com/Article/details/gtvkpdaucx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cqqwz.cn/Article/details/gtdmcvlldz.html

[S23] C：随机数
来源：http://dali.zycfv.cn/Article/details/gtmdfhnijw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xylfe.cn/Article/details/gtvxxvlxnq.html

[S24] C：获取本地时间
来源：http://dali.jinqigufen.top/Article/details/gtczerspck.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.vqdsnc.cn/Article/details/gtlkjdzqgt.html

[S25] C：内存拷贝
来源：http://dali.fengsongda.top/Article/details/gtsgxurhrp.html

memcpy(dst, src, n);
来源：http://dali.havefunace.top/Article/details/gtbvzebrjy.html

[S26] C：内存清零
来源：http://dali.birdmap.top/Article/details/gtmzhnpjnh.html

memset(a, 0, sizeof a);
来源：http://dali.hfpthk.cn/Article/details/gteogufycz.html

[S27] C：定义常量
来源：http://dali.daxiang520.top/Article/details/gtvkdsyiyi.html

const double PI = 3.14159;
来源：http://dali.mhx1999.top/Article/details/gtegumrshk.html

[S28] C：静态变量
来源：http://dali.aibaodan.cn/Article/details/gtimbaeavy.html

static int counter = 0;
来源：http://dali.cucudq.cn/Article/details/gtjtwnkkbr.html

[S29] C：变参函数
来源：http://dali.sweek.top/Article/details/gtntffwgwm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cdnleiting.top/Article/details/gtprxgwdhw.html

[S30] C：头文件保护
来源：http://dali.vqdsnc.cn/Article/details/gtaampykrl.html

#ifndef X_H
来源：http://dali.yonumen.top/Article/details/gtpikigzji.html

#define X_H
来源：http://dali.cheryme.top/Article/details/gtzkbkjoux.html

#endif
来源：http://dali.jianghu66.top/Article/details/gtdzeklcdo.html

[S31] C++：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtznikqwhf.html

#include <iostream>
来源：http://dali.316326.xyz/Article/details/gtjghwplya.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hnqzz.top/Article/details/gtiludlycw.html

[S32] C++：字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkvultxwl.html

std::string s = "hi";  s += "!";
来源：http://dali.gogol.net.cn/Article/details/gtucyyygat.html

[S33] C++：vector 增删
来源：http://dali.jinghuilouyu.cn/Article/details/gthexibisj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.aizwys.cn/Article/details/gtegujezor.html

[S34] C++：遍历 vector
来源：http://dali.daxiang520.top/Article/details/gtlwvtwaja.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xuetiantiany.cn/Article/details/gtpsrokcyw.html

[S35] C++：map
来源：http://dali.ivvv.top/Article/details/gteadbngcc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gthzncdete.html

[S36] C++：unordered_map
来源：http://dali.yuxming.cn/Article/details/gtkxbqykxv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ydzc1.top/Article/details/gtkxyyjjxw.html

[S37] C++：set
来源：http://dali.tian-w.cn/Article/details/gtfrtkytej.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.wangdashe.top/Article/details/gttkgnmdhi.html

[S38] C++：排序
来源：http://dali.bjfxy.top/Article/details/gtivpgtpwq.html

std::sort(v.begin(), v.end());
来源：http://dali.tian-w.cn/Article/details/gtgdwgdcke.html

[S39] C++：自定义比较器排序
来源：http://dali.wangdashe.top/Article/details/gtygafjdyx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.quarkkingdee.top/Article/details/gtzajltexj.html

[S40] C++：查找元素
来源：http://dali.havefunace.top/Article/details/gtgccwdvmd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cdnleiting.top/Article/details/gtwkvxwgxc.html

[S41] C++：类与构造函数
来源：http://dali.jinqigufen.top/Article/details/gtyrdkaekc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.wangdashe.top/Article/details/gtbqugrixx.html

[S42] C++：继承与虚函数
来源：http://dali.dianchejie.cn/Article/details/gtdqgkussz.html

class B : public Base { public: void f() override {} };
来源：http://dali.dianchejie.cn/Article/details/gtppqpwkwd.html

[S43] C++：智能指针
来源：http://dali.wangshuangyany.cn/Article/details/gtdkcaxmrz.html

auto p = std::make_unique<int>(5);
来源：http://dali.daria6918.cn/Article/details/gtbsfdotwa.html

[S44] C++：引用传参
来源：http://dali.shanyushiyangtech.top/Article/details/gtpyeykcwo.html

void inc(int &x) { ++x; }
来源：http://dali.nanxinkj.top/Article/details/gttnxieqru.html

[S45] C++：lambda
来源：http://dali.feifeiyinyue.top/Article/details/gtiwvuwtji.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvvvkcwjf.html

[S46] C++：函数模板
来源：http://dali.shuidangran.top/Article/details/gtwlcisxpn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gtgqddmypv.html

[S47] C++：结构化绑定遍历
来源：http://dali.cucudq.cn/Article/details/gttjjwrmjl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.havefunace.top/Article/details/gtjohknxil.html

[S48] C++：逐行读文件
来源：http://dali.redwolf501.top/Article/details/gtevhblxwx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yueranfly.top/Article/details/gtpvcrznwx.html

while (std::getline(in, line)) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqcxyrntu.html

[S49] C++：写文件
来源：http://dali.andypj.xyz/Article/details/gtbcvsqeam.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.snrcjt.cn/Article/details/gtkfaiayqy.html

[S50] C++：格式化数字
来源：http://dali.yangfankeji.com/Article/details/gtzvaezgxb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtwhaeowto.html

[S51] C++：显式类型转换
来源：http://dali.wangdashe.top/Article/details/gtonkenodd.html

static_cast<double>(a) / b
来源：http://dali.gotoacloud.top/Article/details/gtkeqdknuj.html

[S52] C++：const 与 noexcept
来源：http://dali.guowangkeji.top/Article/details/gtipjvdogp.html

int size() const noexcept { return n_; }
来源：http://dali.cdnleiting.top/Article/details/gtjxysbkli.html

[S53] C++：移动语义
来源：http://dali.yj20258.top/Article/details/gtsjuzzhws.html

std::vector<int> w = std::move(v);
来源：http://dali.shuidangran.top/Article/details/gtbzxymfei.html

[S54] C++：异常处理
来源：http://dali.aibaodan.cn/Article/details/gtxgzygufk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.fzhhl.top/Article/details/gtkvhgqpwa.html

[S55] C++：结构化绑定
来源：http://dali.jqgufenzy.top/Article/details/gtcemzlkzx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gaohongyu789.top/Article/details/gtaorgdxzt.html

[S56] C++：optional
来源：http://dali.zycfv.cn/Article/details/gtigobbkgp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zycfv.cn/Article/details/gtqdveyffi.html

[S57] C++：编译期常量
来源：http://dali.pengpengdd.cyou/Article/details/gtnkstdbra.html

constexpr int N = 10;
来源：http://dali.smart0.xyz/Article/details/gtqefujgku.html

[S58] C++：命名空间
来源：http://dali.xinyue.icu/Article/details/gthivjfjpo.html

namespace ns { int f() { return 1; } }
来源：http://dali.guowangkeji.top/Article/details/gtsrllehdn.html

[S59] C++：静态断言
来源：http://dali.yj202588.top/Article/details/gtqlgohqoq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jqgufenzy.top/Article/details/gtkxqmdawo.html

[S60] C++：遍历并删除元素
来源：http://dali.kuanghao11.cn/Article/details/gtcjjplscb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.daxiang520.top/Article/details/gtcfukjnft.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtzeyutdcj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jqgufenzy.top/Article/details/gtcvdomcop.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gteaxdyals.html

[T01] Kotlin：Hello World
来源：http://dali.havefunace.top/Article/details/gteizxntch.html

println("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gtywcocqta.html

[T02] Kotlin：变量
来源：http://dali.redwolf501.top/Article/details/gtdpdgrpir.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.pycfn.com/Article/details/gtbvpqmnel.html

[T03] Kotlin：字符串模板
来源：http://dali.jqgfzy.top/Article/details/gtdwwgwfad.html

"值: $b"
来源：http://dali.meibo888.top/Article/details/gtyxojevis.html

[T04] Kotlin：空安全
来源：http://dali.shangyingyoupin.top/Article/details/gttmbnohcc.html

val n: String? = null;  n?.length
来源：http://dali.birdmap.top/Article/details/gtmebdlsha.html

[T05] Kotlin：when 表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoocpfxuq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sysykeji.top/Article/details/gtlwdgdaqg.html

[T06] Kotlin：集合映射
来源：http://dali.cdnleiting.top/Article/details/gtlrozdgbb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ehwqpu.com/Article/details/gtqnxropby.html

[T07] Kotlin：集合过滤
来源：http://dali.hfpthk.cn/Article/details/gtgrxlpggu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yueranfly.top/Article/details/gtqhcyopwz.html

[T08] Kotlin：数据类
来源：http://dali.jlsjyb.cn/Article/details/gtkemooduv.html

data class User(val name: String, val age: Int)
来源：http://dali.redwolf501.top/Article/details/gtfryiwzsw.html

[T09] Kotlin：扩展函数
来源：http://dali.fengsongda.top/Article/details/gtmynrmwcb.html

fun String.exclaim() = this + "!"
来源：http://dali.ppjwa.cn/Article/details/gthgsyxvvk.html

[T10] Kotlin：默认参数
来源：http://dali.zdqjudy.top/Article/details/gtsghfpjfb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shuidangran.top/Article/details/gtfjqxzkzb.html

[T11] Kotlin：协程
来源：http://dali.yuanzhike.top/Article/details/gtxnzamlso.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cheryme.top/Article/details/gtthimnrfl.html

[T12] Kotlin：解构声明
来源：http://dali.sweek.top/Article/details/gtlilqmvsx.html

val (a, b) = Pair(1, 2)
来源：http://dali.tianlin.xyz/Article/details/gtetgbahgl.html

[T13] Kotlin：只读 Map
来源：http://dali.guowangkeji.top/Article/details/gttkixixty.html

val m = mapOf("a" to 1)
来源：http://dali.aibaodan.cn/Article/details/gtluwajcup.html

[T14] Kotlin：循环
来源：http://dali.0kj1m.cn/Article/details/gtsnvwbuxj.html

for (i in 1..10) println(i)
来源：http://dali.jlsjyb.cn/Article/details/gtmjmtjopn.html

[T15] Kotlin：接口
来源：http://dali.nanxuanxn.top/Article/details/gtthtjqxgv.html

interface Shape { fun area(): Double }
来源：http://dali.yangfankeji.com/Article/details/gtshvkpumx.html

[T16] Swift：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtfzjeucmv.html

print("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gtshrefkmd.html

[T17] Swift：变量与常量
来源：http://dali.guannengcc.top/Article/details/gtnyjudauf.html

var a = 1;  let b = 2
来源：http://dali.svipenyu.cn/Article/details/gtqjresnqf.html

[T18] Swift：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gtjvfhnwvt.html

"值: \(b)"
来源：http://dali.daria6918.cn/Article/details/gtibddsvhl.html

[T19] Swift：可选绑定
来源：http://dali.yvedp.cn/Article/details/gtekyqekzp.html

if let n = opt { print(n) }
来源：http://dali.jqgfzy.top/Article/details/gtkaabbmxx.html

[T20] Swift：数组操作
来源：http://dali.shanyushiyangtech.top/Article/details/gtuhfvxful.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shzxlz.cn/Article/details/gtplvelpjl.html

[T21] Swift：遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtitdfpvhd.html

for x in a { print(x) }
来源：http://dali.tianlin.xyz/Article/details/gthavzavmq.html

[T22] Swift：字典
来源：http://dali.vqdsnc.cn/Article/details/gtyinwktke.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sxryk.cn/Article/details/gtzvqpfuii.html

[T23] Swift：函数
来源：http://dali.snrcjt.cn/Article/details/gtzimqrvxx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.redwolf501.top/Article/details/gtngrbbnav.html

[T24] Swift：闭包
来源：http://dali.guannengcc.top/Article/details/gtlikzadoh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yj20258.top/Article/details/gtvjjhvavd.html

[T25] Swift：结构体
来源：http://dali.nanxuanxn.top/Article/details/gtxxctmwxe.html

struct P { var x: Int }
来源：http://dali.daxiang520.top/Article/details/gtizcntzex.html

[T26] Swift：类与重写
来源：http://dali.hysaishi.cn/Article/details/gtjkxpqxcu.html

class A: Base { override func f() {} }
来源：http://dali.cashguo.top/Article/details/gtanlahylt.html

[T27] Swift：错误处理
来源：http://dali.daria6918.cn/Article/details/gtrsgbolux.html

do { try f() } catch { print(error) }
来源：http://dali.mhx1999.top/Article/details/gtcbfdcvxa.html

[T28] Swift：枚举
来源：http://dali.chenlongwang.top/Article/details/gtjcmydtll.html

enum Color { case red, green }
来源：http://dali.ydzc1.top/Article/details/gtklfvlzvn.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gtfbwxdhzg.html

guard let x = opt else { return }
来源：http://dali.pycfn.com/Article/details/gthyxwebyx.html

[T30] Swift：协议
来源：http://dali.yj20258888.top/Article/details/gtcjasaqfe.html

protocol Shape { func area() -> Double }
来源：http://dali.yj20258.top/Article/details/gtkasrsyke.html

[T31] Lua：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtvrmgnopk.html

print("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gteyjvlfxs.html

[T32] Lua：局部变量
来源：http://dali.316326.xyz/Article/details/gtwvhzbyke.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gtwwaqrmoo.html

[T33] Lua：表（数组）
来源：http://dali.zdqjudy.top/Article/details/gtufqdsjjw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hywenlv.cn/Article/details/gtpuyszwtj.html

[T34] Lua：遍历表
来源：http://dali.sxryk.cn/Article/details/gtqpbkbxro.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ydzc1.top/Article/details/gtrmtmckua.html

[T35] Lua：字典表
来源：http://dali.yj20258.top/Article/details/gtffuvefsp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ydzc1.top/Article/details/gtrtgdpdjk.html

[T36] Lua：函数
来源：http://dali.jianghu66.top/Article/details/gtbidvbfrh.html

function add(a, b) return a + b end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcdetrvha.html

[T37] Lua：字符串拼接
来源：http://dali.316326.xyz/Article/details/gtsfzjfuzt.html

"a" .. "b"
来源：http://dali.tian-w.cn/Article/details/gtupdisflg.html

[T38] Lua：条件
来源：http://dali.yonumen.top/Article/details/gtrgzvkdht.html

if x > 0 then print("正") end
来源：http://dali.shangyingyoupin.top/Article/details/gtcvweyfpw.html

[T39] Lua：模式匹配
来源：http://dali.jqgufenzy.top/Article/details/gtwcbzkmkf.html

string.find(s, "%d+")
来源：http://dali.sysykeji.top/Article/details/gtqlhklbpf.html

[T40] Lua：元表
来源：http://dali.mhx1999.top/Article/details/gteijwotkm.html

setmetatable({}, { __index = base })
来源：http://dali.yuanzhike.top/Article/details/gtnahooptm.html

[T41] Perl：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtfpxbritz.html

print "Hello\n";
来源：http://dali.tian-w.cn/Article/details/gtmsupmscd.html

[T42] Perl：变量类型
来源：http://dali.9152youxi.cn/Article/details/gtpqqdkmqe.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jiagoushi.top/Article/details/gtzvmcfgwn.html

[T43] Perl：字符串插值
来源：http://dali.cucudq.cn/Article/details/gtotokqqac.html

"值: $a"
来源：http://dali.chenlongwang.top/Article/details/gtqhqbrfbd.html

[T44] Perl：条件
来源：http://dali.zhiwuduotai.top/Article/details/gtelpqorgw.html

if ($a > 0) { print "正"; }
来源：http://dali.ydzc1.top/Article/details/gtdinuhgkp.html

[T45] Perl：数组遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzhucbzvp.html

for my $x (@arr) { print $x; }
来源：http://dali.sysykeji.top/Article/details/gtgkhxerho.html

[T46] Perl：哈希操作
来源：http://dali.smart0.xyz/Article/details/gtsswcpphm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jqgufenzy.top/Article/details/gtgvnpqggr.html

[T47] Perl：正则捕获
来源：http://dali.jinqigfzy.top/Article/details/gtbltqnuxp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xziqi.cn/Article/details/gtyvrgxyqz.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gtpzstatlz.html

$s =~ s/old/new/g;
来源：http://dali.fzhhl.top/Article/details/gtczdkoyko.html

[T49] Perl：函数
来源：http://dali.chenjidiqi.icu/Article/details/gtrtoqonzo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gtehsamihh.html

[T50] Perl：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gtomduuctp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jiagoushi.top/Article/details/gtyqatdoki.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hnxiangtu.top/Article/details/gtoxuygiwv.html

[T51] Scala：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtvrgwegjf.html

println("Hello")
来源：http://dali.andypj.xyz/Article/details/gtawztpfrc.html

[T52] Scala：变量
来源：http://dali.ppjwa.cn/Article/details/gtpunrlrue.html

val a = 1;  var b = 2
来源：http://dali.daria6918.cn/Article/details/gtgcyjujmj.html

[T53] Scala：字符串插值
来源：http://dali.hnqzz.top/Article/details/gtgdgtcrmh.html

s"值: $b"
来源：http://dali.shzxlz.cn/Article/details/gtgavcoisf.html

[T54] Scala：集合映射
来源：http://dali.snrcjt.cn/Article/details/gtcwjelcjd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.9152youxi.cn/Article/details/gtownuactl.html

[T55] Scala：集合过滤
来源：http://dali.jqgufenzy.top/Article/details/gtbtwpklxg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.nwbrower.top/Article/details/gtrxigdnlx.html

[T56] Scala：样例类
来源：http://dali.zhongyouzk.top/Article/details/gtlffxfdab.html

case class User(name: String, age: Int)
来源：http://dali.sufxvd.cn/Article/details/gtondmshei.html

[T57] Scala：模式匹配
来源：http://dali.svipenyu.cn/Article/details/gtyuglzdkm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.daria6918.cn/Article/details/gtlrpkfgra.html

[T58] Scala：函数定义
来源：http://dali.316326.xyz/Article/details/gtlzybbekq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.dianchejie.cn/Article/details/gtnagumbnp.html

[T59] Scala：循环
来源：http://dali.hammf.cn/Article/details/gtyajqnmuf.html

for (i <- 1 to 10) println(i)
来源：http://dali.hfpthk.cn/Article/details/gttrvvnfjq.html

[T60] Scala：折叠
来源：http://dali.jinqigufen.top/Article/details/gtjwlsjicy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.nanxuanxn.top/Article/details/gtteywsjan.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gthhwrhfdl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zycfv.cn/Article/details/gtbnnyjnzc.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtmvtolqnl.html

[U01] Py：创建虚拟环境
来源：http://dali.hongshengwenyu.top/Article/details/gtrgdysnht.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.guannengcc.top/Article/details/gtxqpenczx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xuanzx.com/Article/details/gtlkwnlmny.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.haohaochexian.top/Article/details/gtkeibbfaz.html

[U03] Py：加载 .env 配置
来源：http://dali.hammf.cn/Article/details/gtpnginipj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hammf.cn/Article/details/gtvyrieufz.html

[U04] Py：变量调试打印
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxuyrrtos.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zdqjudy.top/Article/details/gtllvnxwej.html

[U05] Py：列表去重且保序
来源：http://dali.tianlin.xyz/Article/details/gtntcfddzf.html

list(dict.fromkeys(arr))
来源：http://dali.ybcxt.top/Article/details/gtctpiyshg.html

[U06] Py：合并两个字典
来源：http://dali.jiagoushi.top/Article/details/gtubaofeik.html

{**a, **b}
来源：http://dali.hywenlv.cn/Article/details/gtigduhqmv.html

[U07] Py：反转字典键值
来源：http://dali.tianlin.xyz/Article/details/gtoyqjkkot.html

{v: k for k, v in d.items()}
来源：http://dali.havefunace.top/Article/details/gtsbnvyyhy.html

[U08] Py：展平二维列表
来源：http://dali.zhiwuduotai.top/Article/details/gtoqqzvupy.html

[y for x in nested for y in x]
来源：http://dali.pengpengdd.cyou/Article/details/gtjfxubcsc.html

[U09] Py：字典取最大值的键
来源：http://dali.jianghu66.top/Article/details/gthysaqgra.html

max(d, key=d.get)
来源：http://dali.andypj.xyz/Article/details/gtovkfbcst.html

[U10] Py：按值排序字典
来源：http://dali.pycfn.com/Article/details/gthwzjggnb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shangyingyoupin.top/Article/details/gtkgtmuoxa.html

[U11] Py：生成器表达式
来源：http://dali.ehwqpu.com/Article/details/gtcwezsvrf.html

(x * 2 for x in arr)
来源：http://dali.zhoulong.xyz/Article/details/gtynyskghj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.chenlongwang.top/Article/details/gtvlihfkmh.html

Counter(arr).most_common(3)
来源：http://dali.yvedp.cn/Article/details/gtytfovbjv.html

[U13] Py：固定长度队列
来源：http://dali.smart0.xyz/Article/details/gtjrzjdklr.html

deque(maxlen=10)
来源：http://dali.pengpengdd.cyou/Article/details/gtntswtrqb.html

[U14] Py：分组收集到列表
来源：http://dali.jqgufenzy.top/Article/details/gtronwwczk.html

defaultdict(list)
来源：http://dali.yvedp.cn/Article/details/gtahuwzgue.html

[U15] Py：高精度计时
来源：http://dali.yuxming.cn/Article/details/gthvegejhr.html

t = time.perf_counter()
来源：http://dali.shanyushiyangtech.top/Article/details/gteytwrihq.html

[U16] Py：命令行参数解析
来源：http://dali.redwolf501.top/Article/details/gtjgddrway.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.316326.xyz/Article/details/gthdencrys.html

[U17] Py：初始化日志
来源：http://dali.fengsongda.top/Article/details/gtbjndhvyq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.dashuyun.cn/Article/details/gtemdkkkgn.html

[U18] Py：预编译正则
来源：http://dali.yangfankeji.com/Article/details/gtiztpxwwj.html

pat = re.compile(r"\d+")
来源：http://dali.iojbl.cn/Article/details/gtiluptepi.html

[U19] Py：正则替换带回调
来源：http://dali.hnxiangtu.top/Article/details/gticlompvs.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.mhx1999.top/Article/details/gtthqxfdob.html

[U20] Py：缓存函数结果
来源：http://dali.yueranfly.top/Article/details/gtlbqsehii.html

@functools.lru_cache(maxsize=None)
来源：http://dali.chenzaomai.com/Article/details/gtfamgzgfi.html

[U21] Py：自定义上下文管理器
来源：http://dali.xuetiantiany.cn/Article/details/gtabtytwjo.html

@contextlib.contextmanager
来源：http://dali.tian-w.cn/Article/details/gttonmxmqy.html

[U22] Py：矩阵转置
来源：http://dali.zdqjudy.top/Article/details/gtrjsxgjhe.html

list(zip(*m))
来源：http://dali.jinyuanbaomall.cn/Article/details/gttuomxmit.html

[U23] Py：分块读取大文件
来源：http://dali.xuanzx.com/Article/details/gtrewmqezx.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.mhx1999.top/Article/details/gtpgrnqthq.html

[U24] Py：路径操作
来源：http://dali.feifeiyinyue.top/Article/details/gtipnultgh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.9152youxi.cn/Article/details/gtponrklol.html


<!-- 参考信息 -->