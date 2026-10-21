代发 wailian999

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.aibaodan.cn/Article/details/gtgsfxfool.html

[S02] C：变量与格式化输出
来源：http://dali.jinqigufen.top/Article/details/gtpamrlkjt.html

int a = 10; printf("%d\n", a);
来源：http://dali.yueranfly.top/Article/details/gtauemyzqo.html

[S03] C：读入整数
来源：http://dali.guowangkeji.top/Article/details/gtpbstvuet.html

int x; scanf("%d", &x);
来源：http://dali.bjfxy.top/Article/details/gtnkaxyrib.html

[S04] C：字符串复制
来源：http://dali.jlsjyb.cn/Article/details/gtpvczrngf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jlsjyb.cn/Article/details/gtjlpidrum.html

[S05] C：字符串长度
来源：http://dali.gzhubu.top/Article/details/gtpvdsxurz.html

strlen(s)
来源：http://dali.ydzc1.top/Article/details/gtyzpwaexq.html

[S06] C：字符串比较
来源：http://dali.gzhubu.top/Article/details/gtmpqaravm.html

strcmp(a, b) == 0
来源：http://dali.jinghuilouyu.cn/Article/details/gtcgpulett.html

[S07] C：数组遍历求和
来源：http://dali.ybcxt.top/Article/details/gtwcjhjawv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yj20258888.top/Article/details/gtpnvvsrck.html

[S08] C：动态内存分配与释放
来源：http://dali.fengsongda.top/Article/details/gtporqugzq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsigewzgf.html

[S09] C：结构体定义与初始化
来源：http://dali.zhongyouzk.top/Article/details/gtmedyrqyn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinghuilouyu.cn/Article/details/gtcjazwijp.html

[S10] C：指针与解引用
来源：http://dali.xinyue.icu/Article/details/gtfxbuglwf.html

int *p = &a;  *p = 5;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlyzkpjpv.html

[S11] C：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gtjsqrilvu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xuetiantiany.cn/Article/details/gtamdsdqpy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinqigufen.top/Article/details/gtktxvlohj.html

fclose(f);
来源：http://dali.meibo888.top/Article/details/gtatwmudpf.html

[S12] C：写文件
来源：http://dali.yueranfly.top/Article/details/gtavxtprnt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.pycfn.com/Article/details/gtfcbjaspq.html

[S13] C：宏定义
来源：http://dali.svipenyu.cn/Article/details/gtplhrlvah.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xuetiantiany.cn/Article/details/gtvvqnuksd.html

[S14] C：枚举
来源：http://dali.tanke756.top/Article/details/gtentfacsk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ybcxt.top/Article/details/gteegnxlho.html

[S15] C：类型转换
来源：http://dali.cashguo.top/Article/details/gtvdibbpdu.html

(double) a / b
来源：http://dali.fzhhl.top/Article/details/gtcrubsvst.html

[S16] C：位操作置位
来源：http://dali.fengsongda.top/Article/details/gtpbfdwxzc.html

x |= (1 << 3);
来源：http://dali.quarkkingdee.top/Article/details/gticeycyus.html

[S17] C：安全拼接字符串
来源：http://dali.ivvv.top/Article/details/gthmupdrog.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hongshengwenyu.top/Article/details/gteetbfhpa.html

[S18] C：命令行参数
来源：http://dali.zhixingplan.top/Article/details/gtfxcnerzs.html

int main(int argc, char **argv)
来源：http://dali.quarkkingdee.top/Article/details/gttwioffat.html

[S19] C：快速排序
来源：http://dali.jinqigfzy.top/Article/details/gtqvphvzwi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ivvv.top/Article/details/gtekuvmera.html

[S20] C：二分查找
来源：http://dali.jiagoushi.top/Article/details/gtprrbkunv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gotoacloud.top/Article/details/gtamzisczf.html

[S21] C：字符类别判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnkyzkdk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.c1oappe.top/Article/details/gtigvirvje.html

[S22] C：字符串转数字
来源：http://dali.yj202588.top/Article/details/gtnuzzymev.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xylfe.cn/Article/details/gtagsgzfpu.html

[S23] C：随机数
来源：http://dali.sweek.top/Article/details/gtlsjajhlq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xinyue.icu/Article/details/gtabhphcjx.html

[S24] C：获取本地时间
来源：http://dali.nanxinkj.top/Article/details/gtmhhkyacm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinqigufen.top/Article/details/gtzcxcatim.html

[S25] C：内存拷贝
来源：http://dali.svipenyu.cn/Article/details/gtyfbpchut.html

memcpy(dst, src, n);
来源：http://dali.kuanghao11.cn/Article/details/gtrbbggibs.html

[S26] C：内存清零
来源：http://dali.vqdsnc.cn/Article/details/gtcyarykon.html

memset(a, 0, sizeof a);
来源：http://dali.yuanzhike.top/Article/details/gtgcreqwro.html

[S27] C：定义常量
来源：http://dali.shanyushiyangtech.top/Article/details/gtnpoiwoaz.html

const double PI = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gtsigdhsxa.html

[S28] C：静态变量
来源：http://dali.dianchejie.cn/Article/details/gttprvnnkt.html

static int counter = 0;
来源：http://dali.andypj.xyz/Article/details/gtvvyfhxiy.html

[S29] C：变参函数
来源：http://dali.0kj1m.cn/Article/details/gtcaumqpur.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenzaomai.com/Article/details/gtubxqvqji.html

[S30] C：头文件保护
来源：http://dali.gogol.net.cn/Article/details/gtwftkpkum.html

#ifndef X_H
来源：http://dali.chenlongwang.top/Article/details/gtrwqtkcoy.html

#define X_H
来源：http://dali.xuetiantiany.cn/Article/details/gtpfzrrgti.html

#endif
来源：http://dali.cqqwz.cn/Article/details/gtetdiudsn.html

[S31] C++：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtsjmkvwtq.html

#include <iostream>
来源：http://dali.yanxiufei.cn/Article/details/gtkwhkqvpe.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhoulong.xyz/Article/details/gtonjbaizj.html

[S32] C++：字符串
来源：http://dali.guowangkeji.top/Article/details/gtgpgljnet.html

std::string s = "hi";  s += "!";
来源：http://dali.sxryk.cn/Article/details/gtjenruxzj.html

[S33] C++：vector 增删
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcoaocywm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shzxlz.cn/Article/details/gtenqnuctc.html

[S34] C++：遍历 vector
来源：http://dali.jinqigfzy.top/Article/details/gtbjnguukb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jiagoushi.top/Article/details/gthewsrlzh.html

[S35] C++：map
来源：http://dali.shanyushiyangtech.top/Article/details/gtggvgoxyy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangdashe.top/Article/details/gttwdsbnyi.html

[S36] C++：unordered_map
来源：http://dali.tanke756.top/Article/details/gtwnhbbtyy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aizwys.cn/Article/details/gtydpcwpuo.html

[S37] C++：set
来源：http://dali.snrcjt.cn/Article/details/gtlviititu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.pycfn.com/Article/details/gtpdvayeka.html

[S38] C++：排序
来源：http://dali.pengpengdd.cyou/Article/details/gtmfpvztnj.html

std::sort(v.begin(), v.end());
来源：http://dali.yonumen.top/Article/details/gtrthmphol.html

[S39] C++：自定义比较器排序
来源：http://dali.pengpengdd.cyou/Article/details/gtnfpaziqq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenlongwang.top/Article/details/gttkmeiysa.html

[S40] C++：查找元素
来源：http://dali.havefunace.top/Article/details/gthmogeeqk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jianghu66.top/Article/details/gtlwghafdc.html

[S41] C++：类与构造函数
来源：http://dali.chenlongwang.top/Article/details/gttlksbggo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.pycfn.com/Article/details/gtmrjapjbx.html

[S42] C++：继承与虚函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmuvhwbzr.html

class B : public Base { public: void f() override {} };
来源：http://dali.iojbl.cn/Article/details/gtrzgkqdbh.html

[S43] C++：智能指针
来源：http://dali.wangshuangyany.cn/Article/details/gtwpmatixk.html

auto p = std::make_unique<int>(5);
来源：http://dali.xuetiantiany.cn/Article/details/gtwksezaya.html

[S44] C++：引用传参
来源：http://dali.dashuyun.cn/Article/details/gtjrjhcknh.html

void inc(int &x) { ++x; }
来源：http://dali.yueranfly.top/Article/details/gthlifgkmx.html

[S45] C++：lambda
来源：http://dali.yonumen.top/Article/details/gtguvkxekk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhongyouzk.top/Article/details/gttxnpxbki.html

[S46] C++：函数模板
来源：http://dali.9152youxi.cn/Article/details/gtapsvicin.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.c1oappe.top/Article/details/gtvgiwddya.html

[S47] C++：结构化绑定遍历
来源：http://dali.pycfn.com/Article/details/gtdbritwif.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ybcxt.top/Article/details/gtctwuqoxc.html

[S48] C++：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gtiuyqofzs.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.dianchejie.cn/Article/details/gtqkhxobxs.html

while (std::getline(in, line)) { }
来源：http://dali.xuanzx.com/Article/details/gtlhiqswoj.html

[S49] C++：写文件
来源：http://dali.andypj.xyz/Article/details/gtzbipraaz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hnxiangtu.top/Article/details/gtreeisbio.html

[S50] C++：格式化数字
来源：http://dali.fzhhl.top/Article/details/gtbvbcdotq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gteooiowjy.html

[S51] C++：显式类型转换
来源：http://dali.zhongyouzk.top/Article/details/gtfrpnrtdv.html

static_cast<double>(a) / b
来源：http://dali.ppjwa.cn/Article/details/gtguiwrqzb.html

[S52] C++：const 与 noexcept
来源：http://dali.jinqigufen.top/Article/details/gtrqktizqw.html

int size() const noexcept { return n_; }
来源：http://dali.jyoumei.cn/Article/details/gtvamzzniw.html

[S53] C++：移动语义
来源：http://dali.yongpay.top/Article/details/gtbbmqweob.html

std::vector<int> w = std::move(v);
来源：http://dali.yj20258888.top/Article/details/gtlhahbxbv.html

[S54] C++：异常处理
来源：http://dali.xinyue.icu/Article/details/gtemrompfs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yuxming.cn/Article/details/gtqsmailqq.html

[S55] C++：结构化绑定
来源：http://dali.wangdashe.top/Article/details/gtrptsflwt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.guannengcc.top/Article/details/gtjztgqtrp.html

[S56] C++：optional
来源：http://dali.jinghuilouyu.cn/Article/details/gtzdqtsnvt.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtulzxdkpa.html

[S57] C++：编译期常量
来源：http://dali.wangdashe.top/Article/details/gtdxezxtsy.html

constexpr int N = 10;
来源：http://dali.haohaochexian.top/Article/details/gtyawyksgq.html

[S58] C++：命名空间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqsraqzmq.html

namespace ns { int f() { return 1; } }
来源：http://dali.pycfn.com/Article/details/gtdkgypqdq.html

[S59] C++：静态断言
来源：http://dali.yuanzhike.top/Article/details/gtdnqlflke.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yj20258.top/Article/details/gticyjpzmu.html

[S60] C++：遍历并删除元素
来源：http://dali.kuanghao11.cn/Article/details/gtszacaoqy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jianghu66.top/Article/details/gttzjskrin.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyazskcnl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzoebfhra.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkneghgii.html

[T01] Kotlin：Hello World
来源：http://dali.jianghu66.top/Article/details/gtaotjjrls.html

println("Hello")
来源：http://dali.chenlongwang.top/Article/details/gtggjtohuz.html

[T02] Kotlin：变量
来源：http://dali.hammf.cn/Article/details/gtzqaokwtg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.pycfn.com/Article/details/gtsmsoyqwm.html

[T03] Kotlin：字符串模板
来源：http://dali.birdmap.top/Article/details/gtglutowjt.html

"值: $b"
来源：http://dali.svipenyu.cn/Article/details/gtyugpxnrv.html

[T04] Kotlin：空安全
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqjxxypb.html

val n: String? = null;  n?.length
来源：http://dali.jqgufenzy.top/Article/details/gtsvpnmufm.html

[T05] Kotlin：when 表达式
来源：http://dali.zhixingplan.top/Article/details/gtlsefxgla.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.nanxuanxn.top/Article/details/gttybfyfro.html

[T06] Kotlin：集合映射
来源：http://dali.shangyingyoupin.top/Article/details/gtyawpprzw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtkrpwplmo.html

[T07] Kotlin：集合过滤
来源：http://dali.chenzaomai.com/Article/details/gtteuligiy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gotoacloud.top/Article/details/gtnixmkqpc.html

[T08] Kotlin：数据类
来源：http://dali.dianchejie.cn/Article/details/gtjusowpqy.html

data class User(val name: String, val age: Int)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkrntvdwn.html

[T09] Kotlin：扩展函数
来源：http://dali.nwbrower.top/Article/details/gtmqtkiffm.html

fun String.exclaim() = this + "!"
来源：http://dali.guannengcc.top/Article/details/gtksxgxsno.html

[T10] Kotlin：默认参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxjnobpny.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ybcxt.top/Article/details/gtdwlvdbsf.html

[T11] Kotlin：协程
来源：http://dali.shangyingyoupin.top/Article/details/gtsdsgiuam.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gotoacloud.top/Article/details/gtyasaeqsm.html

[T12] Kotlin：解构声明
来源：http://dali.sufxvd.cn/Article/details/gtayugjmvq.html

val (a, b) = Pair(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gttedhwkzs.html

[T13] Kotlin：只读 Map
来源：http://dali.xziqi.cn/Article/details/gtutwqznmq.html

val m = mapOf("a" to 1)
来源：http://dali.kuanghao11.cn/Article/details/gtxplpypui.html

[T14] Kotlin：循环
来源：http://dali.9152youxi.cn/Article/details/gtpkdmwjnl.html

for (i in 1..10) println(i)
来源：http://dali.316326.xyz/Article/details/gtxmcnouwi.html

[T15] Kotlin：接口
来源：http://dali.aizwys.cn/Article/details/gtqnvsjpqp.html

interface Shape { fun area(): Double }
来源：http://dali.jqgufenzy.top/Article/details/gtgrvtgzzb.html

[T16] Swift：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtlyxbbisv.html

print("Hello")
来源：http://dali.yangfankeji.com/Article/details/gtkzkbfpib.html

[T17] Swift：变量与常量
来源：http://dali.yvedp.cn/Article/details/gtwhvbgydt.html

var a = 1;  let b = 2
来源：http://dali.yongpay.top/Article/details/gtfwssuirp.html

[T18] Swift：字符串插值
来源：http://dali.xylfe.cn/Article/details/gtmeumqtry.html

"值: \(b)"
来源：http://dali.vqdsnc.cn/Article/details/gtvwskyjgs.html

[T19] Swift：可选绑定
来源：http://dali.jianghu66.top/Article/details/gthvqbmdxy.html

if let n = opt { print(n) }
来源：http://dali.cdnleiting.top/Article/details/gtujawwzsx.html

[T20] Swift：数组操作
来源：http://dali.pengpengdd.cyou/Article/details/gtivdsmdsz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.chenjidiqi.icu/Article/details/gttnhajxiq.html

[T21] Swift：遍历
来源：http://dali.shzxlz.cn/Article/details/gtokyqjrcg.html

for x in a { print(x) }
来源：http://dali.gotoacloud.top/Article/details/gtzezziirf.html

[T22] Swift：字典
来源：http://dali.jqgfzy.top/Article/details/gthfweuvjx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yonumen.top/Article/details/gtikhgjkis.html

[T23] Swift：函数
来源：http://dali.shzxlz.cn/Article/details/gtluuxwxtm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yj20258.top/Article/details/gtaeiuymkn.html

[T24] Swift：闭包
来源：http://dali.jqgfzy.top/Article/details/gthybrvajx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yj20258.top/Article/details/gtkchdvlwz.html

[T25] Swift：结构体
来源：http://dali.haohaochexian.top/Article/details/gtnjovlgkl.html

struct P { var x: Int }
来源：http://dali.guannengcc.top/Article/details/gtuuazcoex.html

[T26] Swift：类与重写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzuctqugy.html

class A: Base { override func f() {} }
来源：http://dali.fzhhl.top/Article/details/gtegsnxikn.html

[T27] Swift：错误处理
来源：http://dali.cheryme.top/Article/details/gtyqhlsbkl.html

do { try f() } catch { print(error) }
来源：http://dali.zhoulong.xyz/Article/details/gtvumskwge.html

[T28] Swift：枚举
来源：http://dali.jianghu66.top/Article/details/gtumtdifvm.html

enum Color { case red, green }
来源：http://dali.feifeiyinyue.top/Article/details/gtnrzoshhh.html

[T29] Swift：guard 提前返回
来源：http://dali.jqgfzy.top/Article/details/gtshgflwhs.html

guard let x = opt else { return }
来源：http://dali.ivvv.top/Article/details/gtjxfytfnx.html

[T30] Swift：协议
来源：http://dali.zhiwuduotai.top/Article/details/gttlvlxcnf.html

protocol Shape { func area() -> Double }
来源：http://dali.shuidangran.top/Article/details/gtucbijefw.html

[T31] Lua：Hello World
来源：http://dali.ydzc1.top/Article/details/gtkuigqalq.html

print("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyfririyy.html

[T32] Lua：局部变量
来源：http://dali.hfpthk.cn/Article/details/gtwjkieeue.html

local a = 1
来源：http://dali.shangyingyoupin.top/Article/details/gtfivfwzfh.html

[T33] Lua：表（数组）
来源：http://dali.xziqi.cn/Article/details/gtdtkrflws.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hysaishi.cn/Article/details/gthntwfala.html

[T34] Lua：遍历表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtshbpdemx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jianghu66.top/Article/details/gtxcgcrqbs.html

[T35] Lua：字典表
来源：http://dali.c1oappe.top/Article/details/gtucotrrei.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yangfankeji.com/Article/details/gtilgvaibl.html

[T36] Lua：函数
来源：http://dali.daxiang520.top/Article/details/gtkmgcrfpe.html

function add(a, b) return a + b end
来源：http://dali.yangfankeji.com/Article/details/gtgtjdgacc.html

[T37] Lua：字符串拼接
来源：http://dali.daxiang520.top/Article/details/gtcyfxmprq.html

"a" .. "b"
来源：http://dali.feifeiyinyue.top/Article/details/gtuulfvgug.html

[T38] Lua：条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpznfulde.html

if x > 0 then print("正") end
来源：http://dali.birdmap.top/Article/details/gtzzbtfvkv.html

[T39] Lua：模式匹配
来源：http://dali.0kj1m.cn/Article/details/gtfkypxspx.html

string.find(s, "%d+")
来源：http://dali.shangyingyoupin.top/Article/details/gtjtuhxvlv.html

[T40] Lua：元表
来源：http://dali.ivvv.top/Article/details/gtpgasvhsf.html

setmetatable({}, { __index = base })
来源：http://dali.zycfv.cn/Article/details/gtdimtbtfb.html

[T41] Perl：Hello World
来源：http://dali.tian-w.cn/Article/details/gtbvthjbxj.html

print "Hello\n";
来源：http://dali.wangshuangyany.cn/Article/details/gtdetcumes.html

[T42] Perl：变量类型
来源：http://dali.tian-w.cn/Article/details/gtzlwtkusa.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.feifeiyinyue.top/Article/details/gtmtuxrgsf.html

[T43] Perl：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gtaehxlwzj.html

"值: $a"
来源：http://dali.dashuyun.cn/Article/details/gtbthjewag.html

[T44] Perl：条件
来源：http://dali.svipenyu.cn/Article/details/gtawjjwwpf.html

if ($a > 0) { print "正"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqxekcxzx.html

[T45] Perl：数组遍历
来源：http://dali.bjfxy.top/Article/details/gtgualeovj.html

for my $x (@arr) { print $x; }
来源：http://dali.yj20258888.top/Article/details/gtmrcfjuqw.html

[T46] Perl：哈希操作
来源：http://dali.cashguo.top/Article/details/gtibplsqrh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yuxming.cn/Article/details/gtblgouljv.html

[T47] Perl：正则捕获
来源：http://dali.sufxvd.cn/Article/details/gtrfnytbhn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xziqi.cn/Article/details/gtjdfpikcx.html

[T48] Perl：正则替换
来源：http://dali.ybcxt.top/Article/details/gtjapjagiq.html

$s =~ s/old/new/g;
来源：http://dali.jinghuilouyu.cn/Article/details/gtzlegalus.html

[T49] Perl：函数
来源：http://dali.ehwqpu.com/Article/details/gtqyvixbew.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyjtdxwdy.html

[T50] Perl：逐行读文件
来源：http://dali.redwolf501.top/Article/details/gtanlfvbii.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.chenlongwang.top/Article/details/gtujcigfdd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhiwuduotai.top/Article/details/gtmqerjkbu.html

[T51] Scala：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtprpjkrbk.html

println("Hello")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtldxwnnzq.html

[T52] Scala：变量
来源：http://dali.wangshuangyany.cn/Article/details/gtprvvreim.html

val a = 1;  var b = 2
来源：http://dali.aizwys.cn/Article/details/gteqppmoha.html

[T53] Scala：字符串插值
来源：http://dali.pengpengdd.cyou/Article/details/gtrzpgczys.html

s"值: $b"
来源：http://dali.yongpay.top/Article/details/gtjpgugxsq.html

[T54] Scala：集合映射
来源：http://dali.cheryme.top/Article/details/gtjpdqeevz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtpobpjqia.html

[T55] Scala：集合过滤
来源：http://dali.cdnleiting.top/Article/details/gtexqgsoow.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.daria6918.cn/Article/details/gtdstgjxlt.html

[T56] Scala：样例类
来源：http://dali.shzxlz.cn/Article/details/gtyjatazkq.html

case class User(name: String, age: Int)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpoffjxpz.html

[T57] Scala：模式匹配
来源：http://dali.quarkkingdee.top/Article/details/gtkizhngrv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.andypj.xyz/Article/details/gtsmbwyies.html

[T58] Scala：函数定义
来源：http://dali.jinghuilouyu.cn/Article/details/gtmbdulndv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yanxiufei.cn/Article/details/gtbakibtyv.html

[T59] Scala：循环
来源：http://dali.xuanzx.com/Article/details/gtshikzsoy.html

for (i <- 1 to 10) println(i)
来源：http://dali.hywenlv.cn/Article/details/gtkveovpbc.html

[T60] Scala：折叠
来源：http://dali.haohaochexian.top/Article/details/gtzreqyuvt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tanke756.top/Article/details/gthiuzdsdv.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtopqvdgcb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.wangdashe.top/Article/details/gtnxrbovnn.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtxtaqphxu.html

[U01] Py：创建虚拟环境
来源：http://dali.birdmap.top/Article/details/gtganmqjsu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yj20258888.top/Article/details/gtgalduuzg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yj20258.top/Article/details/gtldjfsiit.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtphthiwgm.html

[U03] Py：加载 .env 配置
来源：http://dali.jqgfzy.top/Article/details/gtzgljcgca.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jqgfzy.top/Article/details/gtrvnnxswc.html

[U04] Py：变量调试打印
来源：http://dali.xylfe.cn/Article/details/gtzjcxwxmh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yj20258.top/Article/details/gturinxjxi.html

[U05] Py：列表去重且保序
来源：http://dali.quarkkingdee.top/Article/details/gtndbfohgr.html

list(dict.fromkeys(arr))
来源：http://dali.yj20258.top/Article/details/gtzftxguyv.html

[U06] Py：合并两个字典
来源：http://dali.hywenlv.cn/Article/details/gtktxdezdt.html

{**a, **b}
来源：http://dali.zhoulong.xyz/Article/details/gtmxlzjbsg.html

[U07] Py：反转字典键值
来源：http://dali.shzxlz.cn/Article/details/gtcpabgbuj.html

{v: k for k, v in d.items()}
来源：http://dali.cashguo.top/Article/details/gtqxavuyqq.html

[U08] Py：展平二维列表
来源：http://dali.nanxinkj.top/Article/details/gtnnmkmgkn.html

[y for x in nested for y in x]
来源：http://dali.andypj.xyz/Article/details/gtakjcaccl.html

[U09] Py：字典取最大值的键
来源：http://dali.aibaodan.cn/Article/details/gtfptketue.html

max(d, key=d.get)
来源：http://dali.zhengqikj.top/Article/details/gtdeolgymi.html

[U10] Py：按值排序字典
来源：http://dali.chenlongwang.top/Article/details/gtztyxzcay.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.iojbl.cn/Article/details/gtugueifgf.html

[U11] Py：生成器表达式
来源：http://dali.sxryk.cn/Article/details/gtiodbrzxz.html

(x * 2 for x in arr)
来源：http://dali.aizwys.cn/Article/details/gtkjejbiae.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.birdmap.top/Article/details/gtworqztod.html

Counter(arr).most_common(3)
来源：http://dali.hfpthk.cn/Article/details/gtcpltvqlh.html

[U13] Py：固定长度队列
来源：http://dali.tian-w.cn/Article/details/gtzpfqcgyj.html

deque(maxlen=10)
来源：http://dali.bjfxy.top/Article/details/gtllhzhfol.html

[U14] Py：分组收集到列表
来源：http://dali.tian-w.cn/Article/details/gtbbnrilhs.html

defaultdict(list)
来源：http://dali.shzxlz.cn/Article/details/gtaleantab.html

[U15] Py：高精度计时
来源：http://dali.zhongyouzk.top/Article/details/gtekiccdqi.html

t = time.perf_counter()
来源：http://dali.jqgfzy.top/Article/details/gtxthpgicf.html

[U16] Py：命令行参数解析
来源：http://dali.yongpay.top/Article/details/gtvexneldj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yj20258.top/Article/details/gtbkswnpqa.html

[U17] Py：初始化日志
来源：http://dali.sxryk.cn/Article/details/gtuwhdqxfq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yvedp.cn/Article/details/gtuhptouhs.html

[U18] Py：预编译正则
来源：http://dali.ehwqpu.com/Article/details/gtueuimcmo.html

pat = re.compile(r"\d+")
来源：http://dali.guowangkeji.top/Article/details/gtefcmmopr.html

[U19] Py：正则替换带回调
来源：http://dali.wangshuangyany.cn/Article/details/gtjxreqtyb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zdqjudy.top/Article/details/gttjquorfe.html

[U20] Py：缓存函数结果
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyfdrurqq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zycfv.cn/Article/details/gtzyumapbp.html

[U21] Py：自定义上下文管理器
来源：http://dali.shanyushiyangtech.top/Article/details/gtyijrggav.html

@contextlib.contextmanager
来源：http://dali.ppjwa.cn/Article/details/gtckfdefuj.html

[U22] Py：矩阵转置
来源：http://dali.feifeiyinyue.top/Article/details/gtmrhnxuei.html

list(zip(*m))
来源：http://dali.jqgufenzy.top/Article/details/gtkwpvdopg.html

[U23] Py：分块读取大文件
来源：http://dali.zhongyouzk.top/Article/details/gtcfqihuli.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gtvktkiawc.html

[U24] Py：路径操作
来源：http://dali.cheryme.top/Article/details/gtjxtrirbs.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hnqzz.top/Article/details/gtwcqfbhni.html


<!-- 参考信息 -->