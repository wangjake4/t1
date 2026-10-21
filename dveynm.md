代发 wailian999

S. C / C++ 专题
来源：http://dali.guannengcc.top/Article/details/gtvwyxjkip.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtoxddwhkx.html

[S01] C：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtigfwlgtp.html

#include <stdio.h>
来源：http://dali.chenlongwang.top/Article/details/gtczfgtepq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyerjnzst.html

[S02] C：变量与格式化输出
来源：http://dali.jqgfzy.top/Article/details/gtcdswfzef.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenlongwang.top/Article/details/gtgfkajbnm.html

[S03] C：读入整数
来源：http://dali.gaohongyu789.top/Article/details/gtnwzjwywa.html

int x; scanf("%d", &x);
来源：http://dali.chenlongwang.top/Article/details/gtqfzcmojl.html

[S04] C：字符串复制
来源：http://dali.jqgfzy.top/Article/details/gthyhupssk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hfpthk.cn/Article/details/gtyzxlxzug.html

[S05] C：字符串长度
来源：http://dali.smart0.xyz/Article/details/gturisvjwg.html

strlen(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqcotgflm.html

[S06] C：字符串比较
来源：http://dali.sufxvd.cn/Article/details/gtuziybjni.html

strcmp(a, b) == 0
来源：http://dali.sufxvd.cn/Article/details/gtkacliecm.html

[S07] C：数组遍历求和
来源：http://dali.jqgufenzy.top/Article/details/gtdrrmewgv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhixingplan.top/Article/details/gtnayidqtz.html

[S08] C：动态内存分配与释放
来源：http://dali.yonumen.top/Article/details/gtuuarepwa.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yangfankeji.com/Article/details/gtyzdvgrsa.html

[S09] C：结构体定义与初始化
来源：http://dali.yueranfly.top/Article/details/gtmnqajbex.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sysykeji.top/Article/details/gtuuicnxbs.html

[S10] C：指针与解引用
来源：http://dali.ppjwa.cn/Article/details/gtkgrpidkn.html

int *p = &a;  *p = 5;
来源：http://dali.fzhhl.top/Article/details/gtfrbrkcot.html

[S11] C：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gthuegveej.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shuidangran.top/Article/details/gtvackyxyc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.aizwys.cn/Article/details/gtcybdzegj.html

fclose(f);
来源：http://dali.jqgufenzy.top/Article/details/gtpmdenlzk.html

[S12] C：写文件
来源：http://dali.chenlongwang.top/Article/details/gtwbbxvorz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tanke756.top/Article/details/gtwhviaehp.html

[S13] C：宏定义
来源：http://dali.yanxiufei.cn/Article/details/gtofmkwzal.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hysaishi.cn/Article/details/gtnnbjtvad.html

[S14] C：枚举
来源：http://dali.daria6918.cn/Article/details/gtenhkhlbs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.andypj.xyz/Article/details/gttrygsfbv.html

[S15] C：类型转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsgxljbiz.html

(double) a / b
来源：http://dali.jqgufenzy.top/Article/details/gtpkuarjqp.html

[S16] C：位操作置位
来源：http://dali.sweek.top/Article/details/gtdqcdomsa.html

x |= (1 << 3);
来源：http://dali.jqgufenzy.top/Article/details/gttkdvhmac.html

[S17] C：安全拼接字符串
来源：http://dali.fengsongda.top/Article/details/gtrwarpeoh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jianghu66.top/Article/details/gtniwpkdyi.html

[S18] C：命令行参数
来源：http://dali.hywenlv.cn/Article/details/gtwgtzdffu.html

int main(int argc, char **argv)
来源：http://dali.jianghu66.top/Article/details/gtsygzmmla.html

[S19] C：快速排序
来源：http://dali.haohaochexian.top/Article/details/gtlrdkivxv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.birdmap.top/Article/details/gthtwvzqbu.html

[S20] C：二分查找
来源：http://dali.shuidangran.top/Article/details/gtvvjkfpyu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gtkjbpgyib.html

[S21] C：字符类别判断
来源：http://dali.yongpay.top/Article/details/gtcunehajp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.birdmap.top/Article/details/gtbfwlvaty.html

[S22] C：字符串转数字
来源：http://dali.xylfe.cn/Article/details/gttxwbhoiv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj20258888.top/Article/details/gtbubsgfgs.html

[S23] C：随机数
来源：http://dali.yj202588.top/Article/details/gtdqruaoms.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.c1oappe.top/Article/details/gtvrgpfjfb.html

[S24] C：获取本地时间
来源：http://dali.jinghuilouyu.cn/Article/details/gtunddfvjv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tian-w.cn/Article/details/gtqtqduizr.html

[S25] C：内存拷贝
来源：http://dali.birdmap.top/Article/details/gtveymhtxp.html

memcpy(dst, src, n);
来源：http://dali.yonumen.top/Article/details/gtdaaorfiu.html

[S26] C：内存清零
来源：http://dali.tanke756.top/Article/details/gtbfxzmeow.html

memset(a, 0, sizeof a);
来源：http://dali.tianlin.xyz/Article/details/gtkeozzqjy.html

[S27] C：定义常量
来源：http://dali.xylfe.cn/Article/details/gtcbmjwntd.html

const double PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gtxkskzvzq.html

[S28] C：静态变量
来源：http://dali.guannengcc.top/Article/details/gtkddyueqm.html

static int counter = 0;
来源：http://dali.fengsongda.top/Article/details/gtaokympkk.html

[S29] C：变参函数
来源：http://dali.zhixingplan.top/Article/details/gtpfyxprsj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.daxiang520.top/Article/details/gtnlsvhttd.html

[S30] C：头文件保护
来源：http://dali.nanxuanxn.top/Article/details/gtccwvrgnh.html

#ifndef X_H
来源：http://dali.sweek.top/Article/details/gticiaqdlq.html

#define X_H
来源：http://dali.hysaishi.cn/Article/details/gtiagsrnre.html

#endif
来源：http://dali.jinqigufen.top/Article/details/gtrzjmtakp.html

[S31] C++：Hello World
来源：http://dali.yj20258.top/Article/details/gtjqeyvajg.html

#include <iostream>
来源：http://dali.yueranfly.top/Article/details/gtsaecnrdk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jyoumei.cn/Article/details/gtocfhuivu.html

[S32] C++：字符串
来源：http://dali.hywenlv.cn/Article/details/gtmbiwzzic.html

std::string s = "hi";  s += "!";
来源：http://dali.hywenlv.cn/Article/details/gtvxyvdeqt.html

[S33] C++：vector 增删
来源：http://dali.dianchejie.cn/Article/details/gtflwkukag.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.0kj1m.cn/Article/details/gtftjbcdoe.html

[S34] C++：遍历 vector
来源：http://dali.zhoulong.xyz/Article/details/gtfundqtnw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.mhx1999.top/Article/details/gtvnsitldr.html

[S35] C++：map
来源：http://dali.sxryk.cn/Article/details/gtrjwbruma.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gtjkimzzwn.html

[S36] C++：unordered_map
来源：http://dali.c1oappe.top/Article/details/gtfnoqwodn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gtqzboggji.html

[S37] C++：set
来源：http://dali.havefunace.top/Article/details/gtnyhoikov.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.birdmap.top/Article/details/gtxeuzkdbw.html

[S38] C++：排序
来源：http://dali.ivvv.top/Article/details/gtvsvoxhlv.html

std::sort(v.begin(), v.end());
来源：http://dali.tanke756.top/Article/details/gtftltnmqz.html

[S39] C++：自定义比较器排序
来源：http://dali.jiagoushi.top/Article/details/gtdbobxdbq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.316326.xyz/Article/details/gtsnspusxw.html

[S40] C++：查找元素
来源：http://dali.jiagoushi.top/Article/details/gtturtdkqw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhixingplan.top/Article/details/gtnrwmdodv.html

[S41] C++：类与构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdlpyzwha.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnxiangtu.top/Article/details/gtltbzldkw.html

[S42] C++：继承与虚函数
来源：http://dali.kuanghao11.cn/Article/details/gtmjimaaqw.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj202588.top/Article/details/gtducrgvkt.html

[S43] C++：智能指针
来源：http://dali.xylfe.cn/Article/details/gthmexsbuh.html

auto p = std::make_unique<int>(5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtynmtorfa.html

[S44] C++：引用传参
来源：http://dali.sxryk.cn/Article/details/gtgslozivg.html

void inc(int &x) { ++x; }
来源：http://dali.xylfe.cn/Article/details/gtynptpvwb.html

[S45] C++：lambda
来源：http://dali.zhongyouzk.top/Article/details/gtwloptyte.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fzhhl.top/Article/details/gtrdgwfigm.html

[S46] C++：函数模板
来源：http://dali.zhengqikj.top/Article/details/gtedywdusk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.daria6918.cn/Article/details/gtexrlibii.html

[S47] C++：结构化绑定遍历
来源：http://dali.yangfankeji.com/Article/details/gthvgsicgx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtckxckpel.html

[S48] C++：逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gtmkahkzwg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jqgufenzy.top/Article/details/gtaqqpubzj.html

while (std::getline(in, line)) { }
来源：http://dali.c1oappe.top/Article/details/gtwkmqbzjt.html

[S49] C++：写文件
来源：http://dali.pengpengdd.cyou/Article/details/gtcxrzehxj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yanxiufei.cn/Article/details/gtuvsqvuuo.html

[S50] C++：格式化数字
来源：http://dali.havefunace.top/Article/details/gtrchkzfpo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.wangdashe.top/Article/details/gtmctfiyme.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gtvbrtlsrw.html

static_cast<double>(a) / b
来源：http://dali.yangfankeji.com/Article/details/gtlqjmifmb.html

[S52] C++：const 与 noexcept
来源：http://dali.hnxiangtu.top/Article/details/gtuxpflcoh.html

int size() const noexcept { return n_; }
来源：http://dali.zhoulong.xyz/Article/details/gttrlnkffu.html

[S53] C++：移动语义
来源：http://dali.guowangkeji.top/Article/details/gtajrtkafw.html

std::vector<int> w = std::move(v);
来源：http://dali.ybcxt.top/Article/details/gtflncuotv.html

[S54] C++：异常处理
来源：http://dali.hnxiangtu.top/Article/details/gtzmfeiiog.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.guowangkeji.top/Article/details/gthfdwnimf.html

[S55] C++：结构化绑定
来源：http://dali.hfpthk.cn/Article/details/gtiylnkswe.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.andypj.xyz/Article/details/gtbzslzbki.html

[S56] C++：optional
来源：http://dali.yj202588.top/Article/details/gtpbhsqqbf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yongpay.top/Article/details/gtccfrvjss.html

[S57] C++：编译期常量
来源：http://dali.yj20258.top/Article/details/gtnmtmkhdl.html

constexpr int N = 10;
来源：http://dali.jlsjyb.cn/Article/details/gtukydhbua.html

[S58] C++：命名空间
来源：http://dali.redwolf501.top/Article/details/gtkxmchnze.html

namespace ns { int f() { return 1; } }
来源：http://dali.zycfv.cn/Article/details/gtytakitol.html

[S59] C++：静态断言
来源：http://dali.hysaishi.cn/Article/details/gtzbukjxho.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yanxiufei.cn/Article/details/gtfwbthhna.html

[S60] C++：遍历并删除元素
来源：http://dali.jyoumei.cn/Article/details/gtbqemjiww.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.guowangkeji.top/Article/details/gtpkzsxmpu.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gteilbnqfx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ivvv.top/Article/details/gtmtrpymmg.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtjwfrsvyk.html

[T01] Kotlin：Hello World
来源：http://dali.wangdashe.top/Article/details/gtxlkbedzo.html

println("Hello")
来源：http://dali.snrcjt.cn/Article/details/gtnzykchjx.html

[T02] Kotlin：变量
来源：http://dali.daxiang520.top/Article/details/gtbzkwghsb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jqgufenzy.top/Article/details/gtfxwofkwg.html

[T03] Kotlin：字符串模板
来源：http://dali.jyoumei.cn/Article/details/gtxicaraep.html

"值: $b"
来源：http://dali.sysykeji.top/Article/details/gtedvcfufc.html

[T04] Kotlin：空安全
来源：http://dali.ivvv.top/Article/details/gttnrhwuvq.html

val n: String? = null;  n?.length
来源：http://dali.shangyingyoupin.top/Article/details/gtycjrqqdh.html

[T05] Kotlin：when 表达式
来源：http://dali.ydzc1.top/Article/details/gtzvwhspmm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.vqdsnc.cn/Article/details/gtbudbmpzo.html

[T06] Kotlin：集合映射
来源：http://dali.cqqwz.cn/Article/details/gtkbapafgl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.daxiang520.top/Article/details/gtkhvyquzr.html

[T07] Kotlin：集合过滤
来源：http://dali.tian-w.cn/Article/details/gtwyaxeeyh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmgqxpip.html

[T08] Kotlin：数据类
来源：http://dali.sweek.top/Article/details/gtnnouzaxj.html

data class User(val name: String, val age: Int)
来源：http://dali.yueranfly.top/Article/details/gtiytbkypu.html

[T09] Kotlin：扩展函数
来源：http://dali.zhengqikj.top/Article/details/gtrlyrhaqb.html

fun String.exclaim() = this + "!"
来源：http://dali.jinyuanbaomall.cn/Article/details/gteiijpvmz.html

[T10] Kotlin：默认参数
来源：http://dali.yj20258888.top/Article/details/gteqyeeijt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.andypj.xyz/Article/details/gtfxhvchot.html

[T11] Kotlin：协程
来源：http://dali.tanke756.top/Article/details/gtwbgzywno.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hnxiangtu.top/Article/details/gtdnfrfswn.html

[T12] Kotlin：解构声明
来源：http://dali.shuidangran.top/Article/details/gtzdegbiha.html

val (a, b) = Pair(1, 2)
来源：http://dali.ppjwa.cn/Article/details/gtygbfnxbf.html

[T13] Kotlin：只读 Map
来源：http://dali.sufxvd.cn/Article/details/gtweixffgm.html

val m = mapOf("a" to 1)
来源：http://dali.shzxlz.cn/Article/details/gtoyiogtil.html

[T14] Kotlin：循环
来源：http://dali.yangfankeji.com/Article/details/gturobsxef.html

for (i in 1..10) println(i)
来源：http://dali.0kj1m.cn/Article/details/gtdbgjvgre.html

[T15] Kotlin：接口
来源：http://dali.guowangkeji.top/Article/details/gtmermsyxa.html

interface Shape { fun area(): Double }
来源：http://dali.yangfankeji.com/Article/details/gtojdkpxbw.html

[T16] Swift：Hello World
来源：http://dali.316326.xyz/Article/details/gttfddgqxh.html

print("Hello")
来源：http://dali.ydzc1.top/Article/details/gtlqchekit.html

[T17] Swift：变量与常量
来源：http://dali.yonumen.top/Article/details/gtrcoycjko.html

var a = 1;  let b = 2
来源：http://dali.guannengcc.top/Article/details/gtxazjdvtq.html

[T18] Swift：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gtsjnkhfhj.html

"值: \(b)"
来源：http://dali.zhoulong.xyz/Article/details/gtlriazdvh.html

[T19] Swift：可选绑定
来源：http://dali.cheryme.top/Article/details/gtpptgtwcc.html

if let n = opt { print(n) }
来源：http://dali.zhengqikj.top/Article/details/gtgtcphsrt.html

[T20] Swift：数组操作
来源：http://dali.yanxiufei.cn/Article/details/gtnvggfulh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.snrcjt.cn/Article/details/gteqpabxpz.html

[T21] Swift：遍历
来源：http://dali.hnqzz.top/Article/details/gtpjnwvnyp.html

for x in a { print(x) }
来源：http://dali.yuxming.cn/Article/details/gtzixmgrdm.html

[T22] Swift：字典
来源：http://dali.shanyushiyangtech.top/Article/details/gtazpfyuiv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.fzhhl.top/Article/details/gtetssainx.html

[T23] Swift：函数
来源：http://dali.sxryk.cn/Article/details/gtshfwsmjk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hnqzz.top/Article/details/gttnwecblx.html

[T24] Swift：闭包
来源：http://dali.aizwys.cn/Article/details/gtzsljtjxg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ppjwa.cn/Article/details/gtwscvpexx.html

[T25] Swift：结构体
来源：http://dali.0kj1m.cn/Article/details/gtuxnlojts.html

struct P { var x: Int }
来源：http://dali.hywenlv.cn/Article/details/gttiylyryp.html

[T26] Swift：类与重写
来源：http://dali.zhixingplan.top/Article/details/gtaypqctvi.html

class A: Base { override func f() {} }
来源：http://dali.fzhhl.top/Article/details/gtkadsemhr.html

[T27] Swift：错误处理
来源：http://dali.cheryme.top/Article/details/gtvldpuuwt.html

do { try f() } catch { print(error) }
来源：http://dali.shuidangran.top/Article/details/gtkovyztof.html

[T28] Swift：枚举
来源：http://dali.zhixingplan.top/Article/details/gteyatkezy.html

enum Color { case red, green }
来源：http://dali.9152youxi.cn/Article/details/gtjeohoagp.html

[T29] Swift：guard 提前返回
来源：http://dali.hysaishi.cn/Article/details/gtsgkofzyw.html

guard let x = opt else { return }
来源：http://dali.iojbl.cn/Article/details/gtfpomjjpq.html

[T30] Swift：协议
来源：http://dali.dashuyun.cn/Article/details/gtaqatjgtc.html

protocol Shape { func area() -> Double }
来源：http://dali.dianchejie.cn/Article/details/gtiruvbhmq.html

[T31] Lua：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gttzxumlpy.html

print("Hello")
来源：http://dali.gotoacloud.top/Article/details/gtrlnayvoj.html

[T32] Lua：局部变量
来源：http://dali.jlsjyb.cn/Article/details/gtxjpnxexj.html

local a = 1
来源：http://dali.pengpengdd.cyou/Article/details/gtfyegfjjy.html

[T33] Lua：表（数组）
来源：http://dali.chenzaomai.com/Article/details/gtmuyhbwdv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.gzhubu.top/Article/details/gtlajooeil.html

[T34] Lua：遍历表
来源：http://dali.gaohongyu789.top/Article/details/gtxnjhdxnl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hfpthk.cn/Article/details/gtwtrngtbj.html

[T35] Lua：字典表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvcflxgxy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.0kj1m.cn/Article/details/gtiqicgztz.html

[T36] Lua：函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzklrkhsi.html

function add(a, b) return a + b end
来源：http://dali.zhengqikj.top/Article/details/gtmmtpwave.html

[T37] Lua：字符串拼接
来源：http://dali.cdnleiting.top/Article/details/gtsahuwwoe.html

"a" .. "b"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmlbhksi.html

[T38] Lua：条件
来源：http://dali.daxiang520.top/Article/details/gtkxlekvum.html

if x > 0 then print("正") end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzqtppuqg.html

[T39] Lua：模式匹配
来源：http://dali.xylfe.cn/Article/details/gtdcvkszby.html

string.find(s, "%d+")
来源：http://dali.guowangkeji.top/Article/details/gtrijrgefg.html

[T40] Lua：元表
来源：http://dali.zhixingplan.top/Article/details/gttgbbxciq.html

setmetatable({}, { __index = base })
来源：http://dali.hammf.cn/Article/details/gtyxhycmbz.html

[T41] Perl：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtozncdynw.html

print "Hello\n";
来源：http://dali.c1oappe.top/Article/details/gtwdfuztyo.html

[T42] Perl：变量类型
来源：http://dali.redwolf501.top/Article/details/gtfcxdsglt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sweek.top/Article/details/gtewqbvnxu.html

[T43] Perl：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gtnvliwvxe.html

"值: $a"
来源：http://dali.cucudq.cn/Article/details/gtgbfzaogk.html

[T44] Perl：条件
来源：http://dali.tian-w.cn/Article/details/gtffeljxxn.html

if ($a > 0) { print "正"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtjglixhmr.html

[T45] Perl：数组遍历
来源：http://dali.guowangkeji.top/Article/details/gtnuqaypur.html

for my $x (@arr) { print $x; }
来源：http://dali.cheryme.top/Article/details/gteopdsqrt.html

[T46] Perl：哈希操作
来源：http://dali.yj20258.top/Article/details/gtkearqxvv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhongyouzk.top/Article/details/gtkummfzgz.html

[T47] Perl：正则捕获
来源：http://dali.cheryme.top/Article/details/gtajtrcsld.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jqgfzy.top/Article/details/gtiqvxbzpu.html

[T48] Perl：正则替换
来源：http://dali.shzxlz.cn/Article/details/gthdlseywm.html

$s =~ s/old/new/g;
来源：http://dali.hongshengwenyu.top/Article/details/gtybuxdqsl.html

[T49] Perl：函数
来源：http://dali.fengsongda.top/Article/details/gtnoingclo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwnnnowvt.html

[T50] Perl：逐行读文件
来源：http://dali.havefunace.top/Article/details/gtxzffgrqd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.mhx1999.top/Article/details/gtdpgtdubz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yangfankeji.com/Article/details/gtenrugrfq.html

[T51] Scala：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtfutuckxd.html

println("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gtlwurscuk.html

[T52] Scala：变量
来源：http://dali.jlsjyb.cn/Article/details/gtssmbfuso.html

val a = 1;  var b = 2
来源：http://dali.wangdashe.top/Article/details/gtduihglaw.html

[T53] Scala：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gttthxzmjp.html

s"值: $b"
来源：http://dali.shangyingyoupin.top/Article/details/gtkeqofrvw.html

[T54] Scala：集合映射
来源：http://dali.smart0.xyz/Article/details/gtozknlfte.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.svipenyu.cn/Article/details/gtprilsrga.html

[T55] Scala：集合过滤
来源：http://dali.mhx1999.top/Article/details/gtipvymevt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.chenlongwang.top/Article/details/gtwomgfwkj.html

[T56] Scala：样例类
来源：http://dali.tian-w.cn/Article/details/gtjsxfyplc.html

case class User(name: String, age: Int)
来源：http://dali.ehwqpu.com/Article/details/gtcdapuuho.html

[T57] Scala：模式匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjducfzvg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gogol.net.cn/Article/details/gtdoubngrs.html

[T58] Scala：函数定义
来源：http://dali.yj20258.top/Article/details/gtykatkgdd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cashguo.top/Article/details/gtiqjhulzj.html

[T59] Scala：循环
来源：http://dali.shzxlz.cn/Article/details/gtcjzujxxt.html

for (i <- 1 to 10) println(i)
来源：http://dali.hysaishi.cn/Article/details/gtuloreyvr.html

[T60] Scala：折叠
来源：http://dali.havefunace.top/Article/details/gtyxeqfvry.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jinqigfzy.top/Article/details/gtzieuavfe.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtfutqycck.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.sweek.top/Article/details/gtzfepkyer.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gthtamccfr.html

[U01] Py：创建虚拟环境
来源：http://dali.jlsjyb.cn/Article/details/gtdvawpavx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.andypj.xyz/Article/details/gtcmagbbgv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.guowangkeji.top/Article/details/gtgkfdbdjb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ppjwa.cn/Article/details/gtxdhsezqs.html

[U03] Py：加载 .env 配置
来源：http://dali.shuidangran.top/Article/details/gtbmdlcvhw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.nwbrower.top/Article/details/gtiguixfrk.html

[U04] Py：变量调试打印
来源：http://dali.xinyue.icu/Article/details/gtdfepwail.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cheryme.top/Article/details/gtiouqfcsg.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gtiluyiusv.html

list(dict.fromkeys(arr))
来源：http://dali.yuxming.cn/Article/details/gtsfwgatud.html

[U06] Py：合并两个字典
来源：http://dali.yonumen.top/Article/details/gthayorsvk.html

{**a, **b}
来源：http://dali.andypj.xyz/Article/details/gtlazsqreh.html

[U07] Py：反转字典键值
来源：http://dali.snrcjt.cn/Article/details/gtbutxuxqv.html

{v: k for k, v in d.items()}
来源：http://dali.jinqigfzy.top/Article/details/gtzjkcxrnw.html

[U08] Py：展平二维列表
来源：http://dali.zhongyouzk.top/Article/details/gtvgoibyzj.html

[y for x in nested for y in x]
来源：http://dali.jqgfzy.top/Article/details/gtpkfzkcqi.html

[U09] Py：字典取最大值的键
来源：http://dali.gaohongyu789.top/Article/details/gtweruaksd.html

max(d, key=d.get)
来源：http://dali.zhaomingkeji.xyz/Article/details/gteckzheru.html

[U10] Py：按值排序字典
来源：http://dali.birdmap.top/Article/details/gtmfwqgnub.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hysaishi.cn/Article/details/gtasigkofv.html

[U11] Py：生成器表达式
来源：http://dali.haohaochexian.top/Article/details/gtgsyjsgzm.html

(x * 2 for x in arr)
来源：http://dali.gotoacloud.top/Article/details/gtxveusdin.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jqgfzy.top/Article/details/gtuufvqcjz.html

Counter(arr).most_common(3)
来源：http://dali.yongpay.top/Article/details/gtwdfhnkbk.html

[U13] Py：固定长度队列
来源：http://dali.xziqi.cn/Article/details/gtemozkhdl.html

deque(maxlen=10)
来源：http://dali.chenjidiqi.icu/Article/details/gtbofubvff.html

[U14] Py：分组收集到列表
来源：http://dali.zycfv.cn/Article/details/gtmshjydpw.html

defaultdict(list)
来源：http://dali.gaohongyu789.top/Article/details/gtjxheuayn.html

[U15] Py：高精度计时
来源：http://dali.tianlin.xyz/Article/details/gtdmoedlpo.html

t = time.perf_counter()
来源：http://dali.yj202588.top/Article/details/gtxihvihxq.html

[U16] Py：命令行参数解析
来源：http://dali.zdqjudy.top/Article/details/gtxwjmmwab.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.gzhubu.top/Article/details/gtrfxnhbkj.html

[U17] Py：初始化日志
来源：http://dali.chenlongwang.top/Article/details/gtbcabmndb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.cashguo.top/Article/details/gtiapaeovw.html

[U18] Py：预编译正则
来源：http://dali.jinyuanbaomall.cn/Article/details/gtosttfiov.html

pat = re.compile(r"\d+")
来源：http://dali.yuanzhike.top/Article/details/gtmgcrjnhu.html

[U19] Py：正则替换带回调
来源：http://dali.snrcjt.cn/Article/details/gtjvozjssa.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcxbeujwo.html

[U20] Py：缓存函数结果
来源：http://dali.dashuyun.cn/Article/details/gtuunfipcc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.chenjidiqi.icu/Article/details/gtukliyhqa.html

[U21] Py：自定义上下文管理器
来源：http://dali.snrcjt.cn/Article/details/gtnlsouuxe.html

@contextlib.contextmanager
来源：http://dali.dashuyun.cn/Article/details/gtqrnkrzxh.html

[U22] Py：矩阵转置
来源：http://dali.sweek.top/Article/details/gtfwhtrkfq.html

list(zip(*m))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyojfpjuq.html


<!-- 参考信息 -->