代发 wailian999

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ppjwa.cn/Article/details/gtoshnfotr.html

[S02] C：变量与格式化输出
来源：http://dali.chenzaomai.com/Article/details/gtihfukpyw.html

int a = 10; printf("%d\n", a);
来源：http://dali.havefunace.top/Article/details/gtipnwfzux.html

[S03] C：读入整数
来源：http://dali.svipenyu.cn/Article/details/gtnmyqsqsy.html

int x; scanf("%d", &x);
来源：http://dali.0kj1m.cn/Article/details/gtcbsbbycc.html

[S04] C：字符串复制
来源：http://dali.nanxinkj.top/Article/details/gtyykohkai.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhixingplan.top/Article/details/gtgybfubzz.html

[S05] C：字符串长度
来源：http://dali.zhongyouzk.top/Article/details/gtlmmidttx.html

strlen(s)
来源：http://dali.tian-w.cn/Article/details/gtqbsxvzjv.html

[S06] C：字符串比较
来源：http://dali.fzhhl.top/Article/details/gtprqdalxs.html

strcmp(a, b) == 0
来源：http://dali.cashguo.top/Article/details/gtebldblfz.html

[S07] C：数组遍历求和
来源：http://dali.ppjwa.cn/Article/details/gtyxnvtzlw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yueranfly.top/Article/details/gtdobstxti.html

[S08] C：动态内存分配与释放
来源：http://dali.guowangkeji.top/Article/details/gtksajuxbp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxielmvha.html

[S09] C：结构体定义与初始化
来源：http://dali.shangyingyoupin.top/Article/details/gtnbhhdjcw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yuanzhike.top/Article/details/gtzkomhywu.html

[S10] C：指针与解引用
来源：http://dali.hfpthk.cn/Article/details/gtzirmslfq.html

int *p = &a;  *p = 5;
来源：http://dali.svipenyu.cn/Article/details/gtzzmvyacm.html

[S11] C：逐行读文件
来源：http://dali.yonumen.top/Article/details/gtdktmblnr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shangyingyoupin.top/Article/details/gtejpaffbe.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jlsjyb.cn/Article/details/gtvtrsviot.html

fclose(f);
来源：http://dali.yuanzhike.top/Article/details/gthnfkmnzj.html

[S12] C：写文件
来源：http://dali.meibo888.top/Article/details/gtcghslavx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shzxlz.cn/Article/details/gtfxyhwtnf.html

[S13] C：宏定义
来源：http://dali.birdmap.top/Article/details/gtdhkplxny.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gzhubu.top/Article/details/gtbyjlgjen.html

[S14] C：枚举
来源：http://dali.redwolf501.top/Article/details/gtfijlvtwh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ybcxt.top/Article/details/gttddpthqx.html

[S15] C：类型转换
来源：http://dali.xziqi.cn/Article/details/gtbeyzxlop.html

(double) a / b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjbpnvtqq.html

[S16] C：位操作置位
来源：http://dali.pengpengdd.cyou/Article/details/gtmkjwdgtt.html

x |= (1 << 3);
来源：http://dali.ppjwa.cn/Article/details/gtlbxausfi.html

[S17] C：安全拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gttupukmyi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hysaishi.cn/Article/details/gtsgqhyiip.html

[S18] C：命令行参数
来源：http://dali.nwbrower.top/Article/details/gtmmyzkjlc.html

int main(int argc, char **argv)
来源：http://dali.jinqigufen.top/Article/details/gtjcpglcdl.html

[S19] C：快速排序
来源：http://dali.xziqi.cn/Article/details/gtwkodfbyy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ydzc1.top/Article/details/gtvfedxzrj.html

[S20] C：二分查找
来源：http://dali.gzhubu.top/Article/details/gtrydrpqso.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cqqwz.cn/Article/details/gtspbkyhdm.html

[S21] C：字符类别判断
来源：http://dali.svipenyu.cn/Article/details/gtozepctqa.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhoulong.xyz/Article/details/gtzcadzien.html

[S22] C：字符串转数字
来源：http://dali.zdqjudy.top/Article/details/gtiyecoulw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tanke756.top/Article/details/gtkgkfuozu.html

[S23] C：随机数
来源：http://dali.cheryme.top/Article/details/gtlrcvuilz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shanyushiyangkeji.top/Article/details/gthjfslcee.html

[S24] C：获取本地时间
来源：http://dali.sxryk.cn/Article/details/gtzatfzwnc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.vqdsnc.cn/Article/details/gtbujkenik.html

[S25] C：内存拷贝
来源：http://dali.wangdashe.top/Article/details/gthkczvbpz.html

memcpy(dst, src, n);
来源：http://dali.daxiang520.top/Article/details/gtgneldczp.html

[S26] C：内存清零
来源：http://dali.kuanghao11.cn/Article/details/gtihplrwtk.html

memset(a, 0, sizeof a);
来源：http://dali.gogol.net.cn/Article/details/gtvddamugx.html

[S27] C：定义常量
来源：http://dali.zdqjudy.top/Article/details/gtuqeopdbt.html

const double PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtxoxjzndz.html

[S28] C：静态变量
来源：http://dali.hfpthk.cn/Article/details/gtqiqtqupy.html

static int counter = 0;
来源：http://dali.ivvv.top/Article/details/gtnpoxuoax.html

[S29] C：变参函数
来源：http://dali.zhongyouzk.top/Article/details/gtsfazmchy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenjidiqi.icu/Article/details/gttrbiyprv.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gtgkrdojts.html

#ifndef X_H
来源：http://dali.snrcjt.cn/Article/details/gtmzcrdnks.html

#define X_H
来源：http://dali.hnqzz.top/Article/details/gtzrvindlp.html

#endif
来源：http://dali.gotoacloud.top/Article/details/gtrygrfltn.html

[S31] C++：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gttkcbeujx.html

#include <iostream>
来源：http://dali.shangyingyoupin.top/Article/details/gtoilojxfe.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cdnleiting.top/Article/details/gtqeskhqrd.html

[S32] C++：字符串
来源：http://dali.c1oappe.top/Article/details/gtxbggcrgf.html

std::string s = "hi";  s += "!";
来源：http://dali.zhixingplan.top/Article/details/gtxlnwmvjn.html

[S33] C++：vector 增删
来源：http://dali.guannengcc.top/Article/details/gtavefwrwy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhengqikj.top/Article/details/gthmfrdxeb.html

[S34] C++：遍历 vector
来源：http://dali.birdmap.top/Article/details/gtoapiqhpy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.snrcjt.cn/Article/details/gtlexcekif.html

[S35] C++：map
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvugruzlo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zycfv.cn/Article/details/gtbghfzhvd.html

[S36] C++：unordered_map
来源：http://dali.chenzaomai.com/Article/details/gtfanpopjd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtxckmdpts.html

[S37] C++：set
来源：http://dali.havefunace.top/Article/details/gtvzuvedqd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yonumen.top/Article/details/gtypeozudr.html

[S38] C++：排序
来源：http://dali.hnxiangtu.top/Article/details/gtjlnghnbx.html

std::sort(v.begin(), v.end());
来源：http://dali.tian-w.cn/Article/details/gtvwmeqpuj.html

[S39] C++：自定义比较器排序
来源：http://dali.zhiwuduotai.top/Article/details/gtlasmjysy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nanxuanxn.top/Article/details/gtdbclkrjb.html

[S40] C++：查找元素
来源：http://dali.hammf.cn/Article/details/gtrupvgkab.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jqgfzy.top/Article/details/gttcrovmgf.html

[S41] C++：类与构造函数
来源：http://dali.meibo888.top/Article/details/gtksgysats.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.birdmap.top/Article/details/gtzcxretus.html

[S42] C++：继承与虚函数
来源：http://dali.jinqigfzy.top/Article/details/gtaepmeddw.html

class B : public Base { public: void f() override {} };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxqkjnoq.html

[S43] C++：智能指针
来源：http://dali.shuidangran.top/Article/details/gtfgulrovd.html

auto p = std::make_unique<int>(5);
来源：http://dali.chenjidiqi.icu/Article/details/gtjhazhghr.html

[S44] C++：引用传参
来源：http://dali.vqdsnc.cn/Article/details/gtfrcqlrzp.html

void inc(int &x) { ++x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttsqwxber.html

[S45] C++：lambda
来源：http://dali.yueranfly.top/Article/details/gtqrwetois.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xinyue.icu/Article/details/gtfgovazts.html

[S46] C++：函数模板
来源：http://dali.gzhubu.top/Article/details/gtbhgdbxzx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.feifeiyinyue.top/Article/details/gthkjqzzwy.html

[S47] C++：结构化绑定遍历
来源：http://dali.jianghu66.top/Article/details/gtpiifbzgp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shuidangran.top/Article/details/gtbxtfimyv.html

[S48] C++：逐行读文件
来源：http://dali.yj20258.top/Article/details/gtdsfagupj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.wangshuangyany.cn/Article/details/gtovonsjzv.html

while (std::getline(in, line)) { }
来源：http://dali.dashuyun.cn/Article/details/gtnjaikmlw.html

[S49] C++：写文件
来源：http://dali.redwolf501.top/Article/details/gtahdrxmkl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.snrcjt.cn/Article/details/gtwenwjyjs.html

[S50] C++：格式化数字
来源：http://dali.pycfn.com/Article/details/gtzomlpzwf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gtynsounuj.html

[S51] C++：显式类型转换
来源：http://dali.yuxming.cn/Article/details/gtwoylcfsj.html

static_cast<double>(a) / b
来源：http://dali.9152youxi.cn/Article/details/gtacrdyhgn.html

[S52] C++：const 与 noexcept
来源：http://dali.zhixingplan.top/Article/details/gtiyfwprra.html

int size() const noexcept { return n_; }
来源：http://dali.yongpay.top/Article/details/gtprsogyub.html

[S53] C++：移动语义
来源：http://dali.jinqigfzy.top/Article/details/gtzhnxhsia.html

std::vector<int> w = std::move(v);
来源：http://dali.sxryk.cn/Article/details/gtvsnztrty.html

[S54] C++：异常处理
来源：http://dali.cdnleiting.top/Article/details/gtyqhuiqhq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jlsjyb.cn/Article/details/gtjmncmodw.html

[S55] C++：结构化绑定
来源：http://dali.nanxinkj.top/Article/details/gtsnuxlczv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.mhx1999.top/Article/details/gtspsywmrh.html

[S56] C++：optional
来源：http://dali.shuidangran.top/Article/details/gtylcxpyfc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.chenzaomai.com/Article/details/gtnoaadnyv.html

[S57] C++：编译期常量
来源：http://dali.hnxiangtu.top/Article/details/gtekhasels.html

constexpr int N = 10;
来源：http://dali.andypj.xyz/Article/details/gtqvstksvn.html

[S58] C++：命名空间
来源：http://dali.zhengqikj.top/Article/details/gtghznujgq.html

namespace ns { int f() { return 1; } }
来源：http://dali.tian-w.cn/Article/details/gtnpffixfe.html

[S59] C++：静态断言
来源：http://dali.hongshengwenyu.top/Article/details/gtzdsumxld.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhiwuduotai.top/Article/details/gtxndcciwa.html

[S60] C++：遍历并删除元素
来源：http://dali.c1oappe.top/Article/details/gtstmvhnzm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhengqikj.top/Article/details/gtecuxvkpi.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtieclqtgf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hfpthk.cn/Article/details/gtyofctwta.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtisrehhrc.html

[T01] Kotlin：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtugtqbhzo.html

println("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gtktxmlxhw.html

[T02] Kotlin：变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtgqqetagf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhongyouzk.top/Article/details/gtjckayvwb.html

[T03] Kotlin：字符串模板
来源：http://dali.jinqigufen.top/Article/details/gtfiysqpsv.html

"值: $b"
来源：http://dali.yangfankeji.com/Article/details/gtiwnqowcd.html

[T04] Kotlin：空安全
来源：http://dali.ehwqpu.com/Article/details/gtwehadjhj.html

val n: String? = null;  n?.length
来源：http://dali.tian-w.cn/Article/details/gtmfiolghi.html

[T05] Kotlin：when 表达式
来源：http://dali.zhongyouzk.top/Article/details/gtpnmqoapc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sufxvd.cn/Article/details/gtqsfwkhad.html

[T06] Kotlin：集合映射
来源：http://dali.zhengqikj.top/Article/details/gtobhcojsa.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.pycfn.com/Article/details/gttxbsuunw.html

[T07] Kotlin：集合过滤
来源：http://dali.zhiwuduotai.top/Article/details/gtcsnihgpq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhengqikj.top/Article/details/gtunaqqofp.html

[T08] Kotlin：数据类
来源：http://dali.xziqi.cn/Article/details/gtnjvgyxsp.html

data class User(val name: String, val age: Int)
来源：http://dali.hysaishi.cn/Article/details/gtxgqdbhdv.html

[T09] Kotlin：扩展函数
来源：http://dali.chenjidiqi.icu/Article/details/gtvnujbvnc.html

fun String.exclaim() = this + "!"
来源：http://dali.ybcxt.top/Article/details/gtvpyvkztx.html

[T10] Kotlin：默认参数
来源：http://dali.fengsongda.top/Article/details/gtnchrsoud.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.chenzaomai.com/Article/details/gtpsgvwrcp.html

[T11] Kotlin：协程
来源：http://dali.hfpthk.cn/Article/details/gtfecvmfng.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yj202588.top/Article/details/gtbunbrccr.html

[T12] Kotlin：解构声明
来源：http://dali.gaohongyu789.top/Article/details/gtzbapauxq.html

val (a, b) = Pair(1, 2)
来源：http://dali.yj202588.top/Article/details/gtmzobyucy.html

[T13] Kotlin：只读 Map
来源：http://dali.sweek.top/Article/details/gtjzvxjdrr.html

val m = mapOf("a" to 1)
来源：http://dali.chenlongwang.top/Article/details/gthrpykmyh.html

[T14] Kotlin：循环
来源：http://dali.9152youxi.cn/Article/details/gtpjqychzu.html

for (i in 1..10) println(i)
来源：http://dali.zhiwuduotai.top/Article/details/gtwlsywahi.html

[T15] Kotlin：接口
来源：http://dali.haohaochexian.top/Article/details/gtsgsxbsdx.html

interface Shape { fun area(): Double }
来源：http://dali.fzhhl.top/Article/details/gtpgqrsoea.html

[T16] Swift：Hello World
来源：http://dali.wangdashe.top/Article/details/gtdtvxyroq.html

print("Hello")
来源：http://dali.xinyue.icu/Article/details/gtzemczfxd.html

[T17] Swift：变量与常量
来源：http://dali.yvedp.cn/Article/details/gtmirldnvl.html

var a = 1;  let b = 2
来源：http://dali.dashuyun.cn/Article/details/gtqivcrxrc.html

[T18] Swift：字符串插值
来源：http://dali.nwbrower.top/Article/details/gtztrkyftt.html

"值: \(b)"
来源：http://dali.9152youxi.cn/Article/details/gtemxaidij.html

[T19] Swift：可选绑定
来源：http://dali.pycfn.com/Article/details/gteqlqloni.html

if let n = opt { print(n) }
来源：http://dali.jqgfzy.top/Article/details/gtrozggylw.html

[T20] Swift：数组操作
来源：http://dali.cheryme.top/Article/details/gtfqwtjtzf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cashguo.top/Article/details/gtnmyslrdq.html

[T21] Swift：遍历
来源：http://dali.jiagoushi.top/Article/details/gtkfcsdhix.html

for x in a { print(x) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtavmnbvci.html

[T22] Swift：字典
来源：http://dali.c1oappe.top/Article/details/gtobyzfvom.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jianghu66.top/Article/details/gtemdygrwy.html

[T23] Swift：函数
来源：http://dali.cqqwz.cn/Article/details/gtftetrxwx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gzhubu.top/Article/details/gtmzohofzn.html

[T24] Swift：闭包
来源：http://dali.yangfankeji.com/Article/details/gtyegbykmb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zdqjudy.top/Article/details/gtnxpzpdkx.html

[T25] Swift：结构体
来源：http://dali.daxiang520.top/Article/details/gtdezjpfrp.html

struct P { var x: Int }
来源：http://dali.yuxming.cn/Article/details/gtnykxcvin.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gtrehkzren.html

class A: Base { override func f() {} }
来源：http://dali.hongshengwenyu.top/Article/details/gtjjvmftxf.html

[T27] Swift：错误处理
来源：http://dali.zhengqikj.top/Article/details/gtfhqpbubz.html

do { try f() } catch { print(error) }
来源：http://dali.zhixingplan.top/Article/details/gtvktzyrib.html

[T28] Swift：枚举
来源：http://dali.xuanzx.com/Article/details/gtlkwmtuis.html

enum Color { case red, green }
来源：http://dali.hammf.cn/Article/details/gtvtzzlkyw.html

[T29] Swift：guard 提前返回
来源：http://dali.c1oappe.top/Article/details/gthouzurcl.html

guard let x = opt else { return }
来源：http://dali.snrcjt.cn/Article/details/gtninqwtit.html

[T30] Swift：协议
来源：http://dali.yanxiufei.cn/Article/details/gtokujwqsz.html

protocol Shape { func area() -> Double }
来源：http://dali.vqdsnc.cn/Article/details/gtjybqaxgi.html

[T31] Lua：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtvrlhzatq.html

print("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtzglrqpad.html

[T32] Lua：局部变量
来源：http://dali.hysaishi.cn/Article/details/gthipyazsw.html

local a = 1
来源：http://dali.c1oappe.top/Article/details/gtjvqiwddk.html

[T33] Lua：表（数组）
来源：http://dali.hnqzz.top/Article/details/gtuoyljtlh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.havefunace.top/Article/details/gtduvfvuax.html

[T34] Lua：遍历表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwlrelrhr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gaohongyu789.top/Article/details/gtiaxrjgcn.html

[T35] Lua：字典表
来源：http://dali.hnxiangtu.top/Article/details/gtdziwicsx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yueranfly.top/Article/details/gtickesqmp.html

[T36] Lua：函数
来源：http://dali.jqgfzy.top/Article/details/gtacrktsas.html

function add(a, b) return a + b end
来源：http://dali.cqqwz.cn/Article/details/gtngsaikmv.html

[T37] Lua：字符串拼接
来源：http://dali.xziqi.cn/Article/details/gthtfeejdz.html

"a" .. "b"
来源：http://dali.zhongyouzk.top/Article/details/gtolmvakqm.html

[T38] Lua：条件
来源：http://dali.shzxlz.cn/Article/details/gtybwikxaw.html

if x > 0 then print("正") end
来源：http://dali.jiagoushi.top/Article/details/gtlbqgxdmc.html

[T39] Lua：模式匹配
来源：http://dali.fzhhl.top/Article/details/gteeonlszu.html

string.find(s, "%d+")
来源：http://dali.mhx1999.top/Article/details/gtyqdtjces.html

[T40] Lua：元表
来源：http://dali.ivvv.top/Article/details/gtwpvoiihc.html

setmetatable({}, { __index = base })
来源：http://dali.sxryk.cn/Article/details/gtpzljzlxx.html

[T41] Perl：Hello World
来源：http://dali.cucudq.cn/Article/details/gtyvswysjs.html

print "Hello\n";
来源：http://dali.jyoumei.cn/Article/details/gtokhsdffh.html

[T42] Perl：变量类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gticyaluqt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jianghu66.top/Article/details/gtfmixsryp.html

[T43] Perl：字符串插值
来源：http://dali.snrcjt.cn/Article/details/gttdgchkmf.html

"值: $a"
来源：http://dali.daxiang520.top/Article/details/gtzjqewutu.html

[T44] Perl：条件
来源：http://dali.hnxiangtu.top/Article/details/gtaejomwev.html

if ($a > 0) { print "正"; }
来源：http://dali.yvedp.cn/Article/details/gtvzlvqher.html

[T45] Perl：数组遍历
来源：http://dali.yonumen.top/Article/details/gtafuaxrnn.html

for my $x (@arr) { print $x; }
来源：http://dali.kuanghao11.cn/Article/details/gtokcgxbzh.html

[T46] Perl：哈希操作
来源：http://dali.jinqigufen.top/Article/details/gtsneivvsz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hywenlv.cn/Article/details/gtdthipcjz.html

[T47] Perl：正则捕获
来源：http://dali.xinyue.icu/Article/details/gtnxfwmyce.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jyoumei.cn/Article/details/gteeizfyug.html

[T48] Perl：正则替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtefioxikt.html

$s =~ s/old/new/g;
来源：http://dali.ppjwa.cn/Article/details/gtbkahmpgf.html

[T49] Perl：函数
来源：http://dali.bjfxy.top/Article/details/gtnxdcaqbd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zycfv.cn/Article/details/gtkxyavuyw.html

[T50] Perl：逐行读文件
来源：http://dali.cheryme.top/Article/details/gtbiftvmmf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.chenjidiqi.icu/Article/details/gtrjgaselp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ehwqpu.com/Article/details/gtiolkweay.html

[T51] Scala：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtpshevlcb.html

println("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gtcbzgnnit.html

[T52] Scala：变量
来源：http://dali.guowangkeji.top/Article/details/gtytcxytug.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gtkxieqsqx.html

[T53] Scala：字符串插值
来源：http://dali.gzhubu.top/Article/details/gtxeokhyex.html

s"值: $b"
来源：http://dali.pycfn.com/Article/details/gtplrevsgv.html

[T54] Scala：集合映射
来源：http://dali.guannengcc.top/Article/details/gtzmfwznwe.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cucudq.cn/Article/details/gtodjzmfew.html

[T55] Scala：集合过滤
来源：http://dali.gogol.net.cn/Article/details/gtruxdfoim.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jinqigfzy.top/Article/details/gtqqhkbymg.html

[T56] Scala：样例类
来源：http://dali.gogol.net.cn/Article/details/gtqdzsiqkc.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gtdprmgank.html

[T57] Scala：模式匹配
来源：http://dali.cashguo.top/Article/details/gtpwkjmhsf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.nanxuanxn.top/Article/details/gtlbudygfc.html

[T58] Scala：函数定义
来源：http://dali.cucudq.cn/Article/details/gturarvyex.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gotoacloud.top/Article/details/gtsioqyhbq.html

[T59] Scala：循环
来源：http://dali.xuanzx.com/Article/details/gtvoxiouyh.html

for (i <- 1 to 10) println(i)
来源：http://dali.chenjidiqi.icu/Article/details/gtjhktzdrt.html

[T60] Scala：折叠
来源：http://dali.cdnleiting.top/Article/details/gtbonegtkh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sxryk.cn/Article/details/gtmzkmnuij.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtqfppfnem.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zdqjudy.top/Article/details/gtrsgxijio.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtmrhinqen.html

[U01] Py：创建虚拟环境
来源：http://dali.andypj.xyz/Article/details/gtdnyisykh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.andypj.xyz/Article/details/gtqwakkqdc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zdqjudy.top/Article/details/gtaejvllug.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jqgufenzy.top/Article/details/gtwqlkzbqy.html

[U03] Py：加载 .env 配置
来源：http://dali.xylfe.cn/Article/details/gtqhveuoat.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jqgufenzy.top/Article/details/gtpbsbyepy.html

[U04] Py：变量调试打印
来源：http://dali.yuanzhike.top/Article/details/gtsfrpjbuk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.feifeiyinyue.top/Article/details/gthbszwjmc.html

[U05] Py：列表去重且保序
来源：http://dali.haohaochexian.top/Article/details/gtjbbalbph.html

list(dict.fromkeys(arr))
来源：http://dali.xylfe.cn/Article/details/gtzgjnlqmi.html

[U06] Py：合并两个字典
来源：http://dali.shangyingyoupin.top/Article/details/gtumdxlhvc.html

{**a, **b}
来源：http://dali.andypj.xyz/Article/details/gtkxscmhgc.html

[U07] Py：反转字典键值
来源：http://dali.hnxiangtu.top/Article/details/gtlfjqlrvw.html

{v: k for k, v in d.items()}
来源：http://dali.daxiang520.top/Article/details/gthorwzbnp.html

[U08] Py：展平二维列表
来源：http://dali.birdmap.top/Article/details/gtpplfugwj.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gthdizvwuj.html

[U09] Py：字典取最大值的键
来源：http://dali.ivvv.top/Article/details/gtjfcloawj.html

max(d, key=d.get)
来源：http://dali.haohaochexian.top/Article/details/gtmxxyyftj.html

[U10] Py：按值排序字典
来源：http://dali.tanke756.top/Article/details/gtopmqzzrk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gogol.net.cn/Article/details/gtfdhoobeh.html

[U11] Py：生成器表达式
来源：http://dali.nanxuanxn.top/Article/details/gtzmovyuhx.html

(x * 2 for x in arr)
来源：http://dali.quarkkingdee.top/Article/details/gtgsuqvvvk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hfpthk.cn/Article/details/gtedgmigqr.html

Counter(arr).most_common(3)
来源：http://dali.cdnleiting.top/Article/details/gthiylluur.html

[U13] Py：固定长度队列
来源：http://dali.zhengqikj.top/Article/details/gtmmbuijmy.html

deque(maxlen=10)
来源：http://dali.pycfn.com/Article/details/gtobcolfii.html

[U14] Py：分组收集到列表
来源：http://dali.jiagoushi.top/Article/details/gtmkxjtwwv.html

defaultdict(list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbhxthdkf.html

[U15] Py：高精度计时
来源：http://dali.dashuyun.cn/Article/details/gtmfktosln.html

t = time.perf_counter()
来源：http://dali.xuetiantiany.cn/Article/details/gtlaaraawo.html

[U16] Py：命令行参数解析
来源：http://dali.chenjidiqi.icu/Article/details/gthkdvyaix.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jianghu66.top/Article/details/gtqpacevdr.html

[U17] Py：初始化日志
来源：http://dali.gaohongyu789.top/Article/details/gtgiezqxpf.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shzxlz.cn/Article/details/gtqtunahmw.html

[U18] Py：预编译正则
来源：http://dali.gotoacloud.top/Article/details/gtxdduwvff.html

pat = re.compile(r"\d+")
来源：http://dali.redwolf501.top/Article/details/gtrjeprmuz.html

[U19] Py：正则替换带回调
来源：http://dali.ehwqpu.com/Article/details/gtvpbmoksg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hnxiangtu.top/Article/details/gtauhffvex.html

[U20] Py：缓存函数结果
来源：http://dali.ybcxt.top/Article/details/gtojqvkojm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.fzhhl.top/Article/details/gtkpdwzbql.html

[U21] Py：自定义上下文管理器
来源：http://dali.mhx1999.top/Article/details/gtxaoveekc.html

@contextlib.contextmanager
来源：http://dali.xuanzx.com/Article/details/gtmyddvzfz.html

[U22] Py：矩阵转置
来源：http://dali.zhixingplan.top/Article/details/gtsawgsmxx.html

list(zip(*m))
来源：http://dali.wangshuangyany.cn/Article/details/gtftepdodv.html

[U23] Py：分块读取大文件
来源：http://dali.hysaishi.cn/Article/details/gtclujbhbi.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yj20258888.top/Article/details/gtzhvaepny.html

[U24] Py：路径操作
来源：http://dali.nanxinkj.top/Article/details/gtyjdpmota.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xinyue.icu/Article/details/gtqfthqtoj.html


<!-- 参考信息 -->