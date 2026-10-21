代发 wailian999

S. C / C++ 专题
来源：http://dali.jianghu66.top/Article/details/gtzunfmeao.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtpbeoaxkd.html

[S01] C：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtbmhnyfpz.html

#include <stdio.h>
来源：http://dali.zdqjudy.top/Article/details/gtblynqepj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.mhx1999.top/Article/details/gthvryxfpq.html

[S02] C：变量与格式化输出
来源：http://dali.snrcjt.cn/Article/details/gthyvcgqeb.html

int a = 10; printf("%d\n", a);
来源：http://dali.redwolf501.top/Article/details/gtmelansxa.html

[S03] C：读入整数
来源：http://dali.gotoacloud.top/Article/details/gtcdyfqsjn.html

int x; scanf("%d", &x);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtghbnbagb.html

[S04] C：字符串复制
来源：http://dali.bjfxy.top/Article/details/gtrkrpmlqz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhongyouzk.top/Article/details/gtlkcgdkbd.html

[S05] C：字符串长度
来源：http://dali.iojbl.cn/Article/details/gtchbhkecw.html

strlen(s)
来源：http://dali.tianlin.xyz/Article/details/gtbqvqxhaq.html

[S06] C：字符串比较
来源：http://dali.guannengcc.top/Article/details/gtnjermlef.html

strcmp(a, b) == 0
来源：http://dali.xylfe.cn/Article/details/gtqbwjhbag.html

[S07] C：数组遍历求和
来源：http://dali.316326.xyz/Article/details/gtwxurxtnr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.fengsongda.top/Article/details/gtskuxfbyh.html

[S08] C：动态内存分配与释放
来源：http://dali.hnqzz.top/Article/details/gtwjgnngke.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.svipenyu.cn/Article/details/gtikjzxdkf.html

[S09] C：结构体定义与初始化
来源：http://dali.yanxiufei.cn/Article/details/gtrojngpyl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.0kj1m.cn/Article/details/gtxkkazddu.html

[S10] C：指针与解引用
来源：http://dali.yuanzhike.top/Article/details/gtelgrbbrj.html

int *p = &a;  *p = 5;
来源：http://dali.havefunace.top/Article/details/gtebesxosj.html

[S11] C：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtjoleoqka.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xuanzx.com/Article/details/gtbhremrzc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.dianchejie.cn/Article/details/gtfrsziakb.html

fclose(f);
来源：http://dali.xinyue.icu/Article/details/gtugbxhced.html

[S12] C：写文件
来源：http://dali.feifeiyinyue.top/Article/details/gtianxwvrq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yvedp.cn/Article/details/gtmekwecxt.html

[S13] C：宏定义
来源：http://dali.hnxiangtu.top/Article/details/gtvpfrvzwa.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.dashuyun.cn/Article/details/gtxxxfjfrb.html

[S14] C：枚举
来源：http://dali.gaohongyu789.top/Article/details/gtiqojjukw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cashguo.top/Article/details/gtjxzcvxmj.html

[S15] C：类型转换
来源：http://dali.quarkkingdee.top/Article/details/gtoviowuox.html

(double) a / b
来源：http://dali.hfpthk.cn/Article/details/gtrgqudken.html

[S16] C：位操作置位
来源：http://dali.zhongyouzk.top/Article/details/gtejwconup.html

x |= (1 << 3);
来源：http://dali.yongpay.top/Article/details/gtafqtjspx.html

[S17] C：安全拼接字符串
来源：http://dali.yvedp.cn/Article/details/gtqwucokqc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xziqi.cn/Article/details/gtxejttcji.html

[S18] C：命令行参数
来源：http://dali.nanxuanxn.top/Article/details/gtcxbpbofn.html

int main(int argc, char **argv)
来源：http://dali.yueranfly.top/Article/details/gtsdxkqwun.html

[S19] C：快速排序
来源：http://dali.yj20258888.top/Article/details/gtxzlszhen.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gtbmbtxxao.html

[S20] C：二分查找
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnkoodtyh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yanxiufei.cn/Article/details/gtndnsiqnj.html

[S21] C：字符类别判断
来源：http://dali.shangyingyoupin.top/Article/details/gtgdowfxyr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.vqdsnc.cn/Article/details/gtvtyvhjcm.html

[S22] C：字符串转数字
来源：http://dali.jqgfzy.top/Article/details/gtqhlnaloq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqsfqtntu.html

[S23] C：随机数
来源：http://dali.sxryk.cn/Article/details/gttgbvzeek.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ehwqpu.com/Article/details/gtwgbckxxc.html

[S24] C：获取本地时间
来源：http://dali.gzhubu.top/Article/details/gtsjdjrwuq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gaohongyu789.top/Article/details/gtquzbujyp.html

[S25] C：内存拷贝
来源：http://dali.jlsjyb.cn/Article/details/gtlscmrbow.html

memcpy(dst, src, n);
来源：http://dali.dashuyun.cn/Article/details/gtoredscii.html

[S26] C：内存清零
来源：http://dali.haohaochexian.top/Article/details/gtopwubjqv.html

memset(a, 0, sizeof a);
来源：http://dali.zhiwuduotai.top/Article/details/gthraeqjpn.html

[S27] C：定义常量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkozqjtye.html

const double PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gtnsbtqpnn.html

[S28] C：静态变量
来源：http://dali.sweek.top/Article/details/gtbycwxwpd.html

static int counter = 0;
来源：http://dali.hysaishi.cn/Article/details/gtfpoviipz.html

[S29] C：变参函数
来源：http://dali.aizwys.cn/Article/details/gtcvrjzcda.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nanxuanxn.top/Article/details/gtiviqwkxq.html

[S30] C：头文件保护
来源：http://dali.wangdashe.top/Article/details/gtbhfknceg.html

#ifndef X_H
来源：http://dali.pengpengdd.cyou/Article/details/gthfepkinm.html

#define X_H
来源：http://dali.havefunace.top/Article/details/gtkrpkrvhr.html

#endif
来源：http://dali.nanxinkj.top/Article/details/gtumckvsxq.html

[S31] C++：Hello World
来源：http://dali.yuxming.cn/Article/details/gtqddrurah.html

#include <iostream>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtukjxryxz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.haohaochexian.top/Article/details/gtfzscnnlj.html

[S32] C++：字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtnhlwpjyw.html

std::string s = "hi";  s += "!";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtprmpqspe.html

[S33] C++：vector 增删
来源：http://dali.zycfv.cn/Article/details/gtagbulxwj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.iojbl.cn/Article/details/gtzwwcxknn.html

[S34] C++：遍历 vector
来源：http://dali.jinghuilouyu.cn/Article/details/gtylqnwows.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gotoacloud.top/Article/details/gtzffqjawz.html

[S35] C++：map
来源：http://dali.nanxinkj.top/Article/details/gtsgwcocer.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtefwrdmjj.html

[S36] C++：unordered_map
来源：http://dali.xylfe.cn/Article/details/gtatnhiczs.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gttiwrpvsz.html

[S37] C++：set
来源：http://dali.zhengqikj.top/Article/details/gtgpjvfwfy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hammf.cn/Article/details/gtceptfchg.html

[S38] C++：排序
来源：http://dali.fengsongda.top/Article/details/gtjqlufgui.html

std::sort(v.begin(), v.end());
来源：http://dali.xinyue.icu/Article/details/gtayqopjuf.html

[S39] C++：自定义比较器排序
来源：http://dali.316326.xyz/Article/details/gtaucuucxy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.fzhhl.top/Article/details/gtlwbjyomz.html

[S40] C++：查找元素
来源：http://dali.zdqjudy.top/Article/details/gtftyaehnn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sweek.top/Article/details/gtmbqozgzg.html

[S41] C++：类与构造函数
来源：http://dali.jyoumei.cn/Article/details/gtxbsvsdbs.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.pycfn.com/Article/details/gtukmraxfa.html

[S42] C++：继承与虚函数
来源：http://dali.fengsongda.top/Article/details/gtnpftkubx.html

class B : public Base { public: void f() override {} };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbiijzudz.html

[S43] C++：智能指针
来源：http://dali.zhoulong.xyz/Article/details/gtfbvnmula.html

auto p = std::make_unique<int>(5);
来源：http://dali.cashguo.top/Article/details/gtmoduxehb.html

[S44] C++：引用传参
来源：http://dali.mhx1999.top/Article/details/gtqdwrvntn.html

void inc(int &x) { ++x; }
来源：http://dali.c1oappe.top/Article/details/gtysyyqcpt.html

[S45] C++：lambda
来源：http://dali.tanke756.top/Article/details/gtspzbapuh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhoulong.xyz/Article/details/gtismflguf.html

[S46] C++：函数模板
来源：http://dali.zhixingplan.top/Article/details/gtbntlvitr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtkiahvpbc.html

[S47] C++：结构化绑定遍历
来源：http://dali.jqgufenzy.top/Article/details/gtufvttvev.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zycfv.cn/Article/details/gtreemccwr.html

[S48] C++：逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtlelsqgdd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqsndkksp.html

while (std::getline(in, line)) { }
来源：http://dali.zdqjudy.top/Article/details/gtolchfueq.html

[S49] C++：写文件
来源：http://dali.pengpengdd.cyou/Article/details/gtzgslkbxa.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.quarkkingdee.top/Article/details/gtiufdefrn.html

[S50] C++：格式化数字
来源：http://dali.feifeiyinyue.top/Article/details/gtaedxqojw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtjbvwefpk.html

[S51] C++：显式类型转换
来源：http://dali.feifeiyinyue.top/Article/details/gtygzcguxf.html

static_cast<double>(a) / b
来源：http://dali.ydzc1.top/Article/details/gtbctmuacd.html

[S52] C++：const 与 noexcept
来源：http://dali.ivvv.top/Article/details/gtbvhstzvh.html

int size() const noexcept { return n_; }
来源：http://dali.zhengqikj.top/Article/details/gttzkhkjmb.html

[S53] C++：移动语义
来源：http://dali.hammf.cn/Article/details/gthttikfys.html

std::vector<int> w = std::move(v);
来源：http://dali.guannengcc.top/Article/details/gtasbcmlpq.html

[S54] C++：异常处理
来源：http://dali.jianghu66.top/Article/details/gtciwlafkg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.pycfn.com/Article/details/gtanprlrjw.html

[S55] C++：结构化绑定
来源：http://dali.316326.xyz/Article/details/gtxpmphusx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sweek.top/Article/details/gtiwojpvsw.html

[S56] C++：optional
来源：http://dali.cheryme.top/Article/details/gtwadzydag.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zdqjudy.top/Article/details/gtiraipzpw.html

[S57] C++：编译期常量
来源：http://dali.redwolf501.top/Article/details/gtdkgqcjgl.html

constexpr int N = 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gtypszveon.html

[S58] C++：命名空间
来源：http://dali.nwbrower.top/Article/details/gtojffofof.html

namespace ns { int f() { return 1; } }
来源：http://dali.shuidangran.top/Article/details/gtzpzjptch.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gttssnowaq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.chenjidiqi.icu/Article/details/gtwfbhugxz.html

[S60] C++：遍历并删除元素
来源：http://dali.andypj.xyz/Article/details/gtwdgmvtno.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.feifeiyinyue.top/Article/details/gtjicvuegi.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtslwobekj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cheryme.top/Article/details/gteovsjwzn.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtjmpfhcna.html

[T01] Kotlin：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtkxavolzj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gtqzeirxjp.html

[T02] Kotlin：变量
来源：http://dali.xinyue.icu/Article/details/gtmrhdemcf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.haohaochexian.top/Article/details/gtlwsyyioq.html

[T03] Kotlin：字符串模板
来源：http://dali.jyoumei.cn/Article/details/gtaldsztjt.html

"值: $b"
来源：http://dali.tanke756.top/Article/details/gtataqxolm.html

[T04] Kotlin：空安全
来源：http://dali.zhengqikj.top/Article/details/gthdksdkgu.html

val n: String? = null;  n?.length
来源：http://dali.cheryme.top/Article/details/gttrwwerpe.html

[T05] Kotlin：when 表达式
来源：http://dali.yvedp.cn/Article/details/gtchyfeihf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yueranfly.top/Article/details/gtgvpcpfgk.html

[T06] Kotlin：集合映射
来源：http://dali.tianlin.xyz/Article/details/gtlzsqzjus.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.316326.xyz/Article/details/gtaeziespi.html

[T07] Kotlin：集合过滤
来源：http://dali.andypj.xyz/Article/details/gtiuzvrmen.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hammf.cn/Article/details/gtgsmtpfqz.html

[T08] Kotlin：数据类
来源：http://dali.yongpay.top/Article/details/gtblpqlxao.html

data class User(val name: String, val age: Int)
来源：http://dali.gaohongyu789.top/Article/details/gtmucwsczz.html

[T09] Kotlin：扩展函数
来源：http://dali.tanke756.top/Article/details/gtnvlsvqyg.html

fun String.exclaim() = this + "!"
来源：http://dali.yuanzhike.top/Article/details/gtjggbvvcu.html

[T10] Kotlin：默认参数
来源：http://dali.jlsjyb.cn/Article/details/gtxlyxtcgy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xuetiantiany.cn/Article/details/gtgqsqyefz.html

[T11] Kotlin：协程
来源：http://dali.hysaishi.cn/Article/details/gteovohexm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.chenjidiqi.icu/Article/details/gtgmtxvfsy.html

[T12] Kotlin：解构声明
来源：http://dali.hongshengwenyu.top/Article/details/gtkqukvxki.html

val (a, b) = Pair(1, 2)
来源：http://dali.yj20258888.top/Article/details/gtlijtzhip.html

[T13] Kotlin：只读 Map
来源：http://dali.jlsjyb.cn/Article/details/gtacrlrewt.html

val m = mapOf("a" to 1)
来源：http://dali.ydzc1.top/Article/details/gtydsoufrr.html

[T14] Kotlin：循环
来源：http://dali.hysaishi.cn/Article/details/gtmqhzgogk.html

for (i in 1..10) println(i)
来源：http://dali.cashguo.top/Article/details/gtdxczrzoy.html

[T15] Kotlin：接口
来源：http://dali.yonumen.top/Article/details/gtsyodhdjm.html

interface Shape { fun area(): Double }
来源：http://dali.ivvv.top/Article/details/gtlqobkluk.html

[T16] Swift：Hello World
来源：http://dali.mhx1999.top/Article/details/gtaoccqssz.html

print("Hello")
来源：http://dali.tianlin.xyz/Article/details/gtwiqcosvc.html

[T17] Swift：变量与常量
来源：http://dali.yueranfly.top/Article/details/gtqkibpbvp.html

var a = 1;  let b = 2
来源：http://dali.cdnleiting.top/Article/details/gturqwjqlp.html

[T18] Swift：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gtpvzfqqgo.html

"值: \(b)"
来源：http://dali.fzhhl.top/Article/details/gtrzpesocd.html

[T19] Swift：可选绑定
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcflrhwto.html

if let n = opt { print(n) }
来源：http://dali.kuanghao11.cn/Article/details/gtxlpaozjl.html

[T20] Swift：数组操作
来源：http://dali.ppjwa.cn/Article/details/gtzxrxfnfn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjovhvwuc.html

[T21] Swift：遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtlhhnxzcn.html

for x in a { print(x) }
来源：http://dali.jinqigfzy.top/Article/details/gtnhdcftem.html

[T22] Swift：字典
来源：http://dali.jiagoushi.top/Article/details/gtqnqsmmdo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.meibo888.top/Article/details/gtisqibhku.html

[T23] Swift：函数
来源：http://dali.ppjwa.cn/Article/details/gtyxapuybs.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.9152youxi.cn/Article/details/gthvskngub.html

[T24] Swift：闭包
来源：http://dali.zycfv.cn/Article/details/gtfaaplqma.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtyysalrjv.html

[T25] Swift：结构体
来源：http://dali.hnxiangtu.top/Article/details/gtnbvsemwy.html

struct P { var x: Int }
来源：http://dali.jqgfzy.top/Article/details/gtyjyraaup.html

[T26] Swift：类与重写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfekpiwpc.html

class A: Base { override func f() {} }
来源：http://dali.vqdsnc.cn/Article/details/gtfnpdujms.html

[T27] Swift：错误处理
来源：http://dali.sufxvd.cn/Article/details/gttzvonezo.html

do { try f() } catch { print(error) }
来源：http://dali.fengsongda.top/Article/details/gtqubeiemr.html

[T28] Swift：枚举
来源：http://dali.yj20258.top/Article/details/gtmajlhhwx.html

enum Color { case red, green }
来源：http://dali.pycfn.com/Article/details/gtvukdyrxe.html

[T29] Swift：guard 提前返回
来源：http://dali.nwbrower.top/Article/details/gtsnbxtene.html

guard let x = opt else { return }
来源：http://dali.pycfn.com/Article/details/gtpocurbyd.html

[T30] Swift：协议
来源：http://dali.xylfe.cn/Article/details/gtszcdxmic.html

protocol Shape { func area() -> Double }
来源：http://dali.cqqwz.cn/Article/details/gtrkybzgvr.html

[T31] Lua：Hello World
来源：http://dali.aibaodan.cn/Article/details/gthnizhryk.html

print("Hello")
来源：http://dali.ehwqpu.com/Article/details/gtxmvzpspy.html

[T32] Lua：局部变量
来源：http://dali.yonumen.top/Article/details/gtggzejwkm.html

local a = 1
来源：http://dali.kuanghao11.cn/Article/details/gtxgiqdpew.html

[T33] Lua：表（数组）
来源：http://dali.yj20258888.top/Article/details/gtnifqwair.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shuidangran.top/Article/details/gttvxrljkx.html

[T34] Lua：遍历表
来源：http://dali.fengsongda.top/Article/details/gtjxaptbza.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yuanzhike.top/Article/details/gtvittbqvq.html

[T35] Lua：字典表
来源：http://dali.cqqwz.cn/Article/details/gtfveobgdp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.aibaodan.cn/Article/details/gtldotvwvz.html

[T36] Lua：函数
来源：http://dali.snrcjt.cn/Article/details/gtfifolkkj.html

function add(a, b) return a + b end
来源：http://dali.tianlin.xyz/Article/details/gtiitskkvf.html

[T37] Lua：字符串拼接
来源：http://dali.hongshengwenyu.top/Article/details/gtbqmoxlfl.html

"a" .. "b"
来源：http://dali.iojbl.cn/Article/details/gtdrrkkxuq.html

[T38] Lua：条件
来源：http://dali.zhoulong.xyz/Article/details/gtwuhagnby.html

if x > 0 then print("正") end
来源：http://dali.zycfv.cn/Article/details/gtnxhiacri.html

[T39] Lua：模式匹配
来源：http://dali.ivvv.top/Article/details/gtdlrzycul.html

string.find(s, "%d+")
来源：http://dali.sxryk.cn/Article/details/gtjzlmghpa.html

[T40] Lua：元表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgrbkstch.html

setmetatable({}, { __index = base })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtepneolnq.html

[T41] Perl：Hello World
来源：http://dali.tianlin.xyz/Article/details/gttncdvzux.html

print "Hello\n";
来源：http://dali.havefunace.top/Article/details/gthmcxmgyq.html

[T42] Perl：变量类型
来源：http://dali.xylfe.cn/Article/details/gtxczukqhr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xuanzx.com/Article/details/gtwuibzjdn.html

[T43] Perl：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gtcdneapkl.html

"值: $a"
来源：http://dali.guowangkeji.top/Article/details/gtvlmcwogz.html

[T44] Perl：条件
来源：http://dali.yj20258888.top/Article/details/gtksfpjypk.html

if ($a > 0) { print "正"; }
来源：http://dali.gzhubu.top/Article/details/gtmphnuowz.html

[T45] Perl：数组遍历
来源：http://dali.andypj.xyz/Article/details/gttbyyinvz.html

for my $x (@arr) { print $x; }
来源：http://dali.yanxiufei.cn/Article/details/gtrlfwwdbq.html

[T46] Perl：哈希操作
来源：http://dali.jianghu66.top/Article/details/gtsjxikbym.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.chenzaomai.com/Article/details/gtzbqsxgpj.html

[T47] Perl：正则捕获
来源：http://dali.redwolf501.top/Article/details/gtiulkvctn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.chenzaomai.com/Article/details/gtoanrtpbr.html

[T48] Perl：正则替换
来源：http://dali.pengpengdd.cyou/Article/details/gtvafofuwq.html

$s =~ s/old/new/g;
来源：http://dali.xuetiantiany.cn/Article/details/gtprjwwetf.html

[T49] Perl：函数
来源：http://dali.smart0.xyz/Article/details/gtkjrayqkc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sufxvd.cn/Article/details/gtngysssmg.html

[T50] Perl：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gtogmvkemb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtafdguvio.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gaohongyu789.top/Article/details/gtnbsurwkb.html

[T51] Scala：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtmlfasstp.html

println("Hello")
来源：http://dali.yj20258888.top/Article/details/gtftobyrja.html

[T52] Scala：变量
来源：http://dali.hnqzz.top/Article/details/gtiffzhgzb.html

val a = 1;  var b = 2
来源：http://dali.zhengqikj.top/Article/details/gtyaamlycs.html

[T53] Scala：字符串插值
来源：http://dali.fengsongda.top/Article/details/gtxzguinud.html

s"值: $b"
来源：http://dali.iojbl.cn/Article/details/gtjijmznry.html

[T54] Scala：集合映射
来源：http://dali.zdqjudy.top/Article/details/gtzjjsrtgb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.svipenyu.cn/Article/details/gttdklwavc.html

[T55] Scala：集合过滤
来源：http://dali.hnqzz.top/Article/details/gtrrdmotbh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.daria6918.cn/Article/details/gtiirtobnn.html

[T56] Scala：样例类
来源：http://dali.yonumen.top/Article/details/gtafzfabhb.html

case class User(name: String, age: Int)
来源：http://dali.dianchejie.cn/Article/details/gtjgxbnidr.html

[T57] Scala：模式匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtbhihnevw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.guowangkeji.top/Article/details/gtnuufgrsk.html

[T58] Scala：函数定义
来源：http://dali.jinghuilouyu.cn/Article/details/gticsfjtzj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhixingplan.top/Article/details/gtzfshsyhr.html

[T59] Scala：循环
来源：http://dali.sxryk.cn/Article/details/gtazckkgvx.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjbterjxc.html

[T60] Scala：折叠
来源：http://dali.yanxiufei.cn/Article/details/gthuepgyct.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zycfv.cn/Article/details/gtdxyznsfg.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gthjrspmlo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.svipenyu.cn/Article/details/gtlotcnewo.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtvjcrnqtp.html

[U01] Py：创建虚拟环境
来源：http://dali.yanxiufei.cn/Article/details/gtmkgackns.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.quarkkingdee.top/Article/details/gtqzxtofux.html

[U02] Py：导出 / 安装依赖
来源：http://dali.smart0.xyz/Article/details/gtlvtudmew.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.smart0.xyz/Article/details/gtpftqbjyf.html

[U03] Py：加载 .env 配置
来源：http://dali.redwolf501.top/Article/details/gtcphairgk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.0kj1m.cn/Article/details/gtbrwpxbdo.html

[U04] Py：变量调试打印
来源：http://dali.cheryme.top/Article/details/gtuwuqijqy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ydzc1.top/Article/details/gtofbcvrxw.html

[U05] Py：列表去重且保序
来源：http://dali.zhixingplan.top/Article/details/gthorxntzv.html

list(dict.fromkeys(arr))
来源：http://dali.chenlongwang.top/Article/details/gtxrfzemcg.html

[U06] Py：合并两个字典
来源：http://dali.bjfxy.top/Article/details/gtymtdjres.html

{**a, **b}
来源：http://dali.shangyingyoupin.top/Article/details/gtveejlwph.html

[U07] Py：反转字典键值
来源：http://dali.havefunace.top/Article/details/gtttcetino.html

{v: k for k, v in d.items()}
来源：http://dali.jqgfzy.top/Article/details/gtmddwywkc.html

[U08] Py：展平二维列表
来源：http://dali.hysaishi.cn/Article/details/gtsirxgurq.html

[y for x in nested for y in x]
来源：http://dali.jinqigfzy.top/Article/details/gtopizglkr.html

[U09] Py：字典取最大值的键
来源：http://dali.dianchejie.cn/Article/details/gtbcryhgvj.html

max(d, key=d.get)
来源：http://dali.chenlongwang.top/Article/details/gtgjxkwhki.html

[U10] Py：按值排序字典
来源：http://dali.guowangkeji.top/Article/details/gtahrlrjby.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.tanke756.top/Article/details/gtsfiqnjnp.html

[U11] Py：生成器表达式
来源：http://dali.tanke756.top/Article/details/gtbdhrzmle.html

(x * 2 for x in arr)
来源：http://dali.yongpay.top/Article/details/gtosturwfe.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.wangdashe.top/Article/details/gttbahzkgg.html

Counter(arr).most_common(3)
来源：http://dali.dashuyun.cn/Article/details/gtmdidvuht.html

[U13] Py：固定长度队列
来源：http://dali.tianlin.xyz/Article/details/gtonuikids.html

deque(maxlen=10)
来源：http://dali.aibaodan.cn/Article/details/gtkkyaioos.html

[U14] Py：分组收集到列表
来源：http://dali.sxryk.cn/Article/details/gtgrjnzbss.html

defaultdict(list)
来源：http://dali.haohaochexian.top/Article/details/gtjwlvvcff.html

[U15] Py：高精度计时
来源：http://dali.xinyue.icu/Article/details/gtoawjtalw.html

t = time.perf_counter()
来源：http://dali.tian-w.cn/Article/details/gtzmfvrcaw.html

[U16] Py：命令行参数解析
来源：http://dali.iojbl.cn/Article/details/gtzdwnfioy.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ppjwa.cn/Article/details/gtcsjljavd.html

[U17] Py：初始化日志
来源：http://dali.hongshengwenyu.top/Article/details/gtxhpnomwe.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.fzhhl.top/Article/details/gthprzhysa.html

[U18] Py：预编译正则
来源：http://dali.nanxuanxn.top/Article/details/gtmlbtnhtl.html

pat = re.compile(r"\d+")
来源：http://dali.0kj1m.cn/Article/details/gtohgmfndg.html

[U19] Py：正则替换带回调
来源：http://dali.ydzc1.top/Article/details/gtjccmxqlu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.cashguo.top/Article/details/gtilworvsg.html

[U20] Py：缓存函数结果
来源：http://dali.316326.xyz/Article/details/gtlehcxzom.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jinqigfzy.top/Article/details/gtluxkowzr.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinghuilouyu.cn/Article/details/gtlloyowdc.html

@contextlib.contextmanager
来源：http://dali.jinqigufen.top/Article/details/gtuhnwqldu.html

[U22] Py：矩阵转置
来源：http://dali.sxryk.cn/Article/details/gthoqkyqlz.html

list(zip(*m))
来源：http://dali.guannengcc.top/Article/details/gtnkibeelr.html


<!-- 参考信息 -->