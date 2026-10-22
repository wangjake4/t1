代发 wailian999

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yangfankeji.com/Article/details/gt2thhaetjt.html

[R80] 查看脚本执行耗时
来源：http://dali.hywenlv.cn/Article/details/gt2eqmgnvku.html

time ./run.sh
来源：http://dali.zhongyouzk.top/Article/details/gt2ddkyabrc.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2uwrtvzwx.html

S. C / C++ 专题
来源：http://dali.yvedp.cn/Article/details/gt2gzbagjov.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2xkwjyxok.html

[S01] C：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gt2dgojrrjd.html

#include <stdio.h>
来源：http://dali.nanxuanxn.top/Article/details/gt2qlqinjig.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.smart0.xyz/Article/details/gt2wqpiuymm.html

[S02] C：变量与格式化输出
来源：http://dali.zhongyouzk.top/Article/details/gt2qaduqsah.html

int a = 10; printf("%d\n", a);
来源：http://dali.fengsongda.top/Article/details/gt2ufgpqxyw.html

[S03] C：读入整数
来源：http://dali.jiagoushi.top/Article/details/gt2aumtgwbm.html

int x; scanf("%d", &x);
来源：http://dali.jianghu66.top/Article/details/gt2tjrmudnn.html

[S04] C：字符串复制
来源：http://dali.yueranfly.top/Article/details/gt2qmxsvsty.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.snrcjt.cn/Article/details/gt2hswndlqb.html

[S05] C：字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2injfsmba.html

strlen(s)
来源：http://dali.sweek.top/Article/details/gt2ukonmavu.html

[S06] C：字符串比较
来源：http://dali.zhixingplan.top/Article/details/gt2eejarhvu.html

strcmp(a, b) == 0
来源：http://dali.zhixingplan.top/Article/details/gt2xervexry.html

[S07] C：数组遍历求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qpauzmyh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.fzhhl.top/Article/details/gt2kvqbbfbz.html

[S08] C：动态内存分配与释放
来源：http://dali.dashuyun.cn/Article/details/gt2fhxfjyeq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gzhubu.top/Article/details/gt2qiiqqkkp.html

[S09] C：结构体定义与初始化
来源：http://dali.chenjidiqi.icu/Article/details/gt2avymmtgz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.snrcjt.cn/Article/details/gt2sskctqrz.html

[S10] C：指针与解引用
来源：http://dali.jiagoushi.top/Article/details/gt2ekumcnkl.html

int *p = &a;  *p = 5;
来源：http://dali.zhongyouzk.top/Article/details/gt2pumpochp.html

[S11] C：逐行读文件
来源：http://dali.316326.xyz/Article/details/gt2gzwblrvz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shangyingyoupin.top/Article/details/gt2kkwhjuzt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cqqwz.cn/Article/details/gt2atawmxji.html

fclose(f);
来源：http://dali.shangyingyoupin.top/Article/details/gt2rhxpdptq.html

[S12] C：写文件
来源：http://dali.jinqigufen.top/Article/details/gt2cgqojxbn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sysykeji.top/Article/details/gt2shzbcwgx.html

[S13] C：宏定义
来源：http://dali.jiagoushi.top/Article/details/gt2hfbulkcv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenjidiqi.icu/Article/details/gt2hxyoyfcu.html

[S14] C：枚举
来源：http://dali.nanxinkj.top/Article/details/gt2kucsbecb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yonumen.top/Article/details/gt2yatsgdtv.html

[S15] C：类型转换
来源：http://dali.hammf.cn/Article/details/gt2eaazxyqq.html

(double) a / b
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eyulqjyr.html

[S16] C：位操作置位
来源：http://dali.yueranfly.top/Article/details/gt2tejimvbj.html

x |= (1 << 3);
来源：http://dali.birdmap.top/Article/details/gt2nodfqvqn.html

[S17] C：安全拼接字符串
来源：http://dali.yj20258.top/Article/details/gt2yospdpxd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cheryme.top/Article/details/gt2uveqvngl.html

[S18] C：命令行参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2wogsjylc.html

int main(int argc, char **argv)
来源：http://dali.cdnleiting.top/Article/details/gt2axjghjbk.html

[S19] C：快速排序
来源：http://dali.xziqi.cn/Article/details/gt2bbwccbwk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.316326.xyz/Article/details/gt2kvswyhcm.html

[S20] C：二分查找
来源：http://dali.ybcxt.top/Article/details/gt2cqtivwxv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.wangdashe.top/Article/details/gt2majyxgxu.html

[S21] C：字符类别判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2usvwapti.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xziqi.cn/Article/details/gt2adlnambo.html

[S22] C：字符串转数字
来源：http://dali.xinyue.icu/Article/details/gt2hqohhmxq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ybcxt.top/Article/details/gt2xjupaisk.html

[S23] C：随机数
来源：http://dali.zycfv.cn/Article/details/gt2gibwxzzl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.c1oappe.top/Article/details/gt2qsdnuawh.html

[S24] C：获取本地时间
来源：http://dali.cucudq.cn/Article/details/gt2fkrndbou.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qflhzvzt.html

[S25] C：内存拷贝
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jlyqioqf.html

memcpy(dst, src, n);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mplynczq.html

[S26] C：内存清零
来源：http://dali.fzhhl.top/Article/details/gt2whbuybxc.html

memset(a, 0, sizeof a);
来源：http://dali.yangfankeji.com/Article/details/gt2axzcxnsp.html

[S27] C：定义常量
来源：http://dali.redwolf501.top/Article/details/gt2lchzbcvd.html

const double PI = 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gt2epiazkzy.html

[S28] C：静态变量
来源：http://dali.wangdashe.top/Article/details/gt2wdwpaong.html

static int counter = 0;
来源：http://dali.tian-w.cn/Article/details/gt2crovskvg.html

[S29] C：变参函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2trpwuwrs.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yccgchut.html

[S30] C：头文件保护
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2esebuqpv.html

#ifndef X_H
来源：http://dali.aibaodan.cn/Article/details/gt2bzyagulo.html

#define X_H
来源：http://dali.cdnleiting.top/Article/details/gt2jdckegeh.html

#endif
来源：http://dali.zhoulong.xyz/Article/details/gt2psfvjqjc.html

[S31] C++：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gt2iuqtortd.html

#include <iostream>
来源：http://dali.shzxlz.cn/Article/details/gt2vwclndln.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.aizwys.cn/Article/details/gt2hjsarvks.html

[S32] C++：字符串
来源：http://dali.meibo888.top/Article/details/gt2kreellob.html

std::string s = "hi";  s += "!";
来源：http://dali.hfpthk.cn/Article/details/gt2mkbdvvqr.html

[S33] C++：vector 增删
来源：http://dali.xylfe.cn/Article/details/gt2kslyngvp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.quarkkingdee.top/Article/details/gt2lirxqtpa.html

[S34] C++：遍历 vector
来源：http://dali.jiagoushi.top/Article/details/gt2sscrkbmh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shzxlz.cn/Article/details/gt2tiateiry.html

[S35] C++：map
来源：http://dali.tian-w.cn/Article/details/gt2pmaiqyht.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2tiotocrb.html

[S36] C++：unordered_map
来源：http://dali.zhiwuduotai.top/Article/details/gt2fyquvnpu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gt2gmednvou.html

[S37] C++：set
来源：http://dali.pengpengdd.cyou/Article/details/gt2mbbvjugo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ppjwa.cn/Article/details/gt2nivgxxir.html

[S38] C++：排序
来源：http://dali.cdnleiting.top/Article/details/gt2cmjqmsdm.html

std::sort(v.begin(), v.end());
来源：http://dali.fzhhl.top/Article/details/gt2axkjalux.html

[S39] C++：自定义比较器排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dlnlxqkb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cucudq.cn/Article/details/gt2ppsoovdw.html

[S40] C++：查找元素
来源：http://dali.0kj1m.cn/Article/details/gt2acgapwsz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.guowangkeji.top/Article/details/gt2ykqvrvlp.html

[S41] C++：类与构造函数
来源：http://dali.snrcjt.cn/Article/details/gt2riitmlfl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenlongwang.top/Article/details/gt2xqktjhmd.html

[S42] C++：继承与虚函数
来源：http://dali.jyoumei.cn/Article/details/gt2fnihjnnv.html

class B : public Base { public: void f() override {} };
来源：http://dali.fengsongda.top/Article/details/gt2fqmvbghg.html

[S43] C++：智能指针
来源：http://dali.yuxming.cn/Article/details/gt2bnlfibkd.html

auto p = std::make_unique<int>(5);
来源：http://dali.havefunace.top/Article/details/gt2trdeeizh.html

[S44] C++：引用传参
来源：http://dali.aizwys.cn/Article/details/gt2uztwmytv.html

void inc(int &x) { ++x; }
来源：http://dali.yj20258.top/Article/details/gt2vzvxwxup.html

[S45] C++：lambda
来源：http://dali.tian-w.cn/Article/details/gt2fxnkppbd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hfpthk.cn/Article/details/gt2vszfiujo.html

[S46] C++：函数模板
来源：http://dali.meibo888.top/Article/details/gt2whtkzchq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gogol.net.cn/Article/details/gt2eulxuymg.html

[S47] C++：结构化绑定遍历
来源：http://dali.cucudq.cn/Article/details/gt2nywdjkag.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hysaishi.cn/Article/details/gt2bfczsjrc.html

[S48] C++：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gt2bypbmsuf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hongshengwenyu.top/Article/details/gt2lyqcrfqz.html

while (std::getline(in, line)) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nybqvrmo.html

[S49] C++：写文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2kboqeflb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shuidangran.top/Article/details/gt2demccvkd.html

[S50] C++：格式化数字
来源：http://dali.gotoacloud.top/Article/details/gt2ohzwfygu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.bjfxy.top/Article/details/gt2rxilzgfp.html

[S51] C++：显式类型转换
来源：http://dali.zdqjudy.top/Article/details/gt2kesrtddo.html

static_cast<double>(a) / b
来源：http://dali.ppjwa.cn/Article/details/gt2treiaicn.html

[S52] C++：const 与 noexcept
来源：http://dali.quarkkingdee.top/Article/details/gt2kyqnozle.html

int size() const noexcept { return n_; }
来源：http://dali.guannengcc.top/Article/details/gt2cfahmppc.html

[S53] C++：移动语义
来源：http://dali.yonumen.top/Article/details/gt2musuimqe.html

std::vector<int> w = std::move(v);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uyqienzu.html

[S54] C++：异常处理
来源：http://dali.smart0.xyz/Article/details/gt2qyupjobz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.pengpengdd.cyou/Article/details/gt2qwslxrum.html

[S55] C++：结构化绑定
来源：http://dali.jyoumei.cn/Article/details/gt2pjjiriie.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.dianchejie.cn/Article/details/gt2hwjyhsrx.html

[S56] C++：optional
来源：http://dali.xziqi.cn/Article/details/gt2bxukwnaj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cheryme.top/Article/details/gt2tnqulnkn.html

[S57] C++：编译期常量
来源：http://dali.jianghu66.top/Article/details/gt2dedstlyg.html

constexpr int N = 10;
来源：http://dali.nanxinkj.top/Article/details/gt2hgutvvnq.html

[S58] C++：命名空间
来源：http://dali.hysaishi.cn/Article/details/gt2fwkutizq.html

namespace ns { int f() { return 1; } }
来源：http://dali.dianchejie.cn/Article/details/gt2ewyoondv.html

[S59] C++：静态断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xsebjqsm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ppjwa.cn/Article/details/gt2jgicnqnp.html

[S60] C++：遍历并删除元素
来源：http://dali.gogol.net.cn/Article/details/gt2tqkrpxch.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yonumen.top/Article/details/gt2pdbirhhb.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2mclmvzip.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhongyouzk.top/Article/details/gt2gxspnfcz.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2luwnqoay.html

[T01] Kotlin：Hello World
来源：http://dali.jqgfzy.top/Article/details/gt2swwugkxe.html

println("Hello")
来源：http://dali.chenlongwang.top/Article/details/gt2qlffxwhy.html

[T02] Kotlin：变量
来源：http://dali.yvedp.cn/Article/details/gt2umneugco.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.fengsongda.top/Article/details/gt2enkuhnwf.html

[T03] Kotlin：字符串模板
来源：http://dali.hywenlv.cn/Article/details/gt2seabwuwj.html

"值: $b"
来源：http://dali.bjfxy.top/Article/details/gt2rxlbkciz.html

[T04] Kotlin：空安全
来源：http://dali.sysykeji.top/Article/details/gt2hczevupb.html

val n: String? = null;  n?.length
来源：http://dali.sysykeji.top/Article/details/gt2jtpcfkbs.html

[T05] Kotlin：when 表达式
来源：http://dali.c1oappe.top/Article/details/gt2wgizhkpr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.nanxuanxn.top/Article/details/gt2wqcvkdec.html

[T06] Kotlin：集合映射
来源：http://dali.ehwqpu.com/Article/details/gt2mkufpssx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yanxiufei.cn/Article/details/gt2reyztdnn.html

[T07] Kotlin：集合过滤
来源：http://dali.cqqwz.cn/Article/details/gt2typgfomr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.aizwys.cn/Article/details/gt2uoysflua.html

[T08] Kotlin：数据类
来源：http://dali.jianghu66.top/Article/details/gt2cjaxyyjz.html

data class User(val name: String, val age: Int)
来源：http://dali.smart0.xyz/Article/details/gt2qmbnavij.html

[T09] Kotlin：扩展函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2bvajyffq.html

fun String.exclaim() = this + "!"
来源：http://dali.gaohongyu789.top/Article/details/gt2nncqlekx.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2odgxdnii.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sysykeji.top/Article/details/gt2zeotfckl.html

[T11] Kotlin：协程
来源：http://dali.snrcjt.cn/Article/details/gt2cvapcgip.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yuanzhike.top/Article/details/gt2ldgomfnb.html

[T12] Kotlin：解构声明
来源：http://dali.meibo888.top/Article/details/gt2tfreysmq.html

val (a, b) = Pair(1, 2)
来源：http://dali.zdqjudy.top/Article/details/gt2wshjhahr.html

[T13] Kotlin：只读 Map
来源：http://dali.dashuyun.cn/Article/details/gt2huzwvtse.html

val m = mapOf("a" to 1)
来源：http://dali.hysaishi.cn/Article/details/gt2fxouajqu.html

[T14] Kotlin：循环
来源：http://dali.hnxiangtu.top/Article/details/gt2lkgltwov.html

for (i in 1..10) println(i)
来源：http://dali.smart0.xyz/Article/details/gt2ktckrdkc.html

[T15] Kotlin：接口
来源：http://dali.yonumen.top/Article/details/gt2qshbprxm.html

interface Shape { fun area(): Double }
来源：http://dali.hywenlv.cn/Article/details/gt2ifdsiegf.html

[T16] Swift：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bywwsohl.html

print("Hello")
来源：http://dali.cdnleiting.top/Article/details/gt2xuequqen.html

[T17] Swift：变量与常量
来源：http://dali.yj20258.top/Article/details/gt2vuobfqmp.html

var a = 1;  let b = 2
来源：http://dali.zdqjudy.top/Article/details/gt2bmizfcdh.html

[T18] Swift：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gt2tsqvxdxu.html

"值: \(b)"
来源：http://dali.smart0.xyz/Article/details/gt2sarpnref.html

[T19] Swift：可选绑定
来源：http://dali.yueranfly.top/Article/details/gt2suzjacih.html

if let n = opt { print(n) }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ekluztad.html

[T20] Swift：数组操作
来源：http://dali.sxryk.cn/Article/details/gt2nnubxjis.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.tian-w.cn/Article/details/gt2cvexxeft.html

[T21] Swift：遍历
来源：http://dali.yanxiufei.cn/Article/details/gt2grhdvwbw.html

for x in a { print(x) }
来源：http://dali.wangdashe.top/Article/details/gt2msejmnfg.html

[T22] Swift：字典
来源：http://dali.hongshengwenyu.top/Article/details/gt2gapglkds.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.c1oappe.top/Article/details/gt2tjqyghns.html

[T23] Swift：函数
来源：http://dali.vqdsnc.cn/Article/details/gt2yyitolpy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.guowangkeji.top/Article/details/gt2jfcllwtv.html

[T24] Swift：闭包
来源：http://dali.tianlin.xyz/Article/details/gt2audkvjec.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ehwqpu.com/Article/details/gt2fdvyfwod.html

[T25] Swift：结构体
来源：http://dali.redwolf501.top/Article/details/gt2hyskxrvz.html

struct P { var x: Int }
来源：http://dali.sxryk.cn/Article/details/gt2dpbhqvul.html

[T26] Swift：类与重写
来源：http://dali.yvedp.cn/Article/details/gt2jgczzozo.html

class A: Base { override func f() {} }
来源：http://dali.c1oappe.top/Article/details/gt2trsxwxix.html

[T27] Swift：错误处理
来源：http://dali.zycfv.cn/Article/details/gt2yfqrxoaw.html

do { try f() } catch { print(error) }
来源：http://dali.0kj1m.cn/Article/details/gt2slmdvtur.html

[T28] Swift：枚举
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aluyiiwh.html

enum Color { case red, green }
来源：http://dali.hfpthk.cn/Article/details/gt2dnlycrlj.html

[T29] Swift：guard 提前返回
来源：http://dali.xuanzx.com/Article/details/gt2rsrrsnpc.html

guard let x = opt else { return }
来源：http://dali.xinyue.icu/Article/details/gt2mfkllnoo.html

[T30] Swift：协议
来源：http://dali.316326.xyz/Article/details/gt2wvkndckg.html

protocol Shape { func area() -> Double }
来源：http://dali.zhengqikj.top/Article/details/gt2hribfbpn.html

[T31] Lua：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gt2yssahbqg.html

print("Hello")
来源：http://dali.gogol.net.cn/Article/details/gt2mxjqvbeg.html

[T32] Lua：局部变量
来源：http://dali.dianchejie.cn/Article/details/gt2htrufuxn.html

local a = 1
来源：http://dali.hysaishi.cn/Article/details/gt2tcawcgrd.html

[T33] Lua：表（数组）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qtbppxsa.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.svipenyu.cn/Article/details/gt2sqikkdca.html

[T34] Lua：遍历表
来源：http://dali.zycfv.cn/Article/details/gt2tjdphpep.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.tianlin.xyz/Article/details/gt2vrrobiec.html

[T35] Lua：字典表
来源：http://dali.dashuyun.cn/Article/details/gt2noonyuch.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gaohongyu789.top/Article/details/gt2whswaetv.html

[T36] Lua：函数
来源：http://dali.gogol.net.cn/Article/details/gt2atxjqkij.html

function add(a, b) return a + b end
来源：http://dali.dianchejie.cn/Article/details/gt2efyuctjn.html

[T37] Lua：字符串拼接
来源：http://dali.yangfankeji.com/Article/details/gt2wiioqnkb.html

"a" .. "b"
来源：http://dali.snrcjt.cn/Article/details/gt2oqldqlcq.html

[T38] Lua：条件
来源：http://dali.jlsjyb.cn/Article/details/gt2vhznhatb.html

if x > 0 then print("正") end
来源：http://dali.aibaodan.cn/Article/details/gt2wpflrziw.html

[T39] Lua：模式匹配
来源：http://dali.havefunace.top/Article/details/gt2nudxgbeu.html

string.find(s, "%d+")
来源：http://dali.yueranfly.top/Article/details/gt2pzcvctzq.html

[T40] Lua：元表
来源：http://dali.jyoumei.cn/Article/details/gt2gbfsbybp.html

setmetatable({}, { __index = base })
来源：http://dali.cdnleiting.top/Article/details/gt2cvrasden.html

[T41] Perl：Hello World
来源：http://dali.smart0.xyz/Article/details/gt2shqpnhtl.html

print "Hello\n";
来源：http://dali.gaohongyu789.top/Article/details/gt2sbcwsrjy.html

[T42] Perl：变量类型
来源：http://dali.ehwqpu.com/Article/details/gt2qrxjvvio.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.nanxinkj.top/Article/details/gt2cvyqrkrz.html

[T43] Perl：字符串插值
来源：http://dali.iojbl.cn/Article/details/gt2howvysri.html

"值: $a"
来源：http://dali.fengsongda.top/Article/details/gt2cboevwec.html

[T44] Perl：条件
来源：http://dali.cqqwz.cn/Article/details/gt2pdrjdibo.html

if ($a > 0) { print "正"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2lpwnxikk.html

[T45] Perl：数组遍历
来源：http://dali.snrcjt.cn/Article/details/gt2jmowheac.html

for my $x (@arr) { print $x; }
来源：http://dali.chenzaomai.com/Article/details/gt2qtdrwjru.html

[T46] Perl：哈希操作
来源：http://dali.xylfe.cn/Article/details/gt2tjykwroj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2pvywfzfe.html

[T47] Perl：正则捕获
来源：http://dali.jyoumei.cn/Article/details/gt2slmctely.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cqqwz.cn/Article/details/gt2pppgnrnf.html

[T48] Perl：正则替换
来源：http://dali.c1oappe.top/Article/details/gt2vfydhkgi.html

$s =~ s/old/new/g;
来源：http://dali.dianchejie.cn/Article/details/gt2idyxwysu.html

[T49] Perl：函数
来源：http://dali.yangfankeji.com/Article/details/gt2zgmbityi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2guezikmm.html

[T50] Perl：逐行读文件
来源：http://dali.havefunace.top/Article/details/gt2ikhzbklk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.9152youxi.cn/Article/details/gt2ujmygioh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yj202588.top/Article/details/gt2ulahbcga.html

[T51] Scala：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gt2mpwzgkwp.html

println("Hello")
来源：http://dali.snrcjt.cn/Article/details/gt2nzwvzpfd.html

[T52] Scala：变量
来源：http://dali.hnxiangtu.top/Article/details/gt2gkqnzyxh.html

val a = 1;  var b = 2
来源：http://dali.hysaishi.cn/Article/details/gt2ofxgtkvy.html

[T53] Scala：字符串插值
来源：http://dali.zhiwuduotai.top/Article/details/gt2uoknbnij.html

s"值: $b"
来源：http://dali.jqgufenzy.top/Article/details/gt2kybtanfv.html

[T54] Scala：集合映射
来源：http://dali.meibo888.top/Article/details/gt2gaywcqfl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.fengsongda.top/Article/details/gt2nbcxqbnq.html

[T55] Scala：集合过滤
来源：http://dali.pengpengdd.cyou/Article/details/gt2ryrroiff.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tkafzqwf.html

[T56] Scala：样例类
来源：http://dali.hysaishi.cn/Article/details/gt2huenzwkt.html

case class User(name: String, age: Int)
来源：http://dali.snrcjt.cn/Article/details/gt2boztomcj.html

[T57] Scala：模式匹配
来源：http://dali.yongpay.top/Article/details/gt2fdnrsegf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yj202588.top/Article/details/gt2rfiqfnte.html

[T58] Scala：函数定义
来源：http://dali.xuanzx.com/Article/details/gt2yfengrlm.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.aizwys.cn/Article/details/gt2shdwumia.html

[T59] Scala：循环
来源：http://dali.zhixingplan.top/Article/details/gt2vtslyxrg.html

for (i <- 1 to 10) println(i)
来源：http://dali.fzhhl.top/Article/details/gt2ofluwnkr.html

[T60] Scala：折叠
来源：http://dali.mhx1999.top/Article/details/gt2qkbfblyz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhixingplan.top/Article/details/gt2xrytruan.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2cyhaxneg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jyoumei.cn/Article/details/gt2nqhbekwx.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2jzwkdyfy.html

[U01] Py：创建虚拟环境
来源：http://dali.jqgufenzy.top/Article/details/gt2flzttaqs.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.dianchejie.cn/Article/details/gt2ortchaad.html

[U02] Py：导出 / 安装依赖
来源：http://dali.quarkkingdee.top/Article/details/gt2bqbxmney.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.havefunace.top/Article/details/gt2sxlmmdxj.html

[U03] Py：加载 .env 配置
来源：http://dali.xziqi.cn/Article/details/gt2eyreaknl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ehwqpu.com/Article/details/gt2poaywqjq.html

[U04] Py：变量调试打印
来源：http://dali.yanxiufei.cn/Article/details/gt2nqxclhys.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xinyue.icu/Article/details/gt2iodobpju.html

[U05] Py：列表去重且保序
来源：http://dali.guannengcc.top/Article/details/gt2snsayjty.html

list(dict.fromkeys(arr))
来源：http://dali.hnqzz.top/Article/details/gt2kkdlrths.html

[U06] Py：合并两个字典
来源：http://dali.shzxlz.cn/Article/details/gt2ylstgisu.html

{**a, **b}
来源：http://dali.zhengqikj.top/Article/details/gt2npcjdcae.html

[U07] Py：反转字典键值
来源：http://dali.wangshuangyany.cn/Article/details/gt2wblvokpn.html

{v: k for k, v in d.items()}
来源：http://dali.yj202588.top/Article/details/gt2dydwjuvt.html

[U08] Py：展平二维列表
来源：http://dali.tianlin.xyz/Article/details/gt2jqgjepvz.html

[y for x in nested for y in x]
来源：http://dali.sufxvd.cn/Article/details/gt2khpsvwre.html

[U09] Py：字典取最大值的键
来源：http://dali.jianghu66.top/Article/details/gt2cqxcxvug.html

max(d, key=d.get)
来源：http://dali.dashuyun.cn/Article/details/gt2qletlewl.html

[U10] Py：按值排序字典
来源：http://dali.xziqi.cn/Article/details/gt2cqwmoqrf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.fengsongda.top/Article/details/gt2auoupore.html

[U11] Py：生成器表达式
来源：http://dali.316326.xyz/Article/details/gt2yfmqpste.html

(x * 2 for x in arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dvgowkys.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.chenjidiqi.icu/Article/details/gt2ccdxciax.html

Counter(arr).most_common(3)
来源：http://dali.gogol.net.cn/Article/details/gt2ogymlbiz.html

[U13] Py：固定长度队列
来源：http://dali.zhongyouzk.top/Article/details/gt2gvjlifuj.html

deque(maxlen=10)
来源：http://dali.jiagoushi.top/Article/details/gt2iywqucor.html

[U14] Py：分组收集到列表
来源：http://dali.smart0.xyz/Article/details/gt2kdoeulwp.html

defaultdict(list)
来源：http://dali.gzhubu.top/Article/details/gt2kzfirrpq.html

[U15] Py：高精度计时
来源：http://dali.sxryk.cn/Article/details/gt2isczoulh.html

t = time.perf_counter()
来源：http://dali.pengpengdd.cyou/Article/details/gt2plaizkuv.html

[U16] Py：命令行参数解析
来源：http://dali.yj202588.top/Article/details/gt2xkniivcu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhoulong.xyz/Article/details/gt2bfslmvdp.html

[U17] Py：初始化日志
来源：http://dali.svipenyu.cn/Article/details/gt2qyfddovh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xqgcdrtq.html

[U18] Py：预编译正则
来源：http://dali.jqgufenzy.top/Article/details/gt2seyhjtox.html

pat = re.compile(r"\d+")
来源：http://dali.yonumen.top/Article/details/gt2hincnfqz.html

[U19] Py：正则替换带回调
来源：http://dali.vqdsnc.cn/Article/details/gt2ypkigkay.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.cashguo.top/Article/details/gt2hbewvcog.html

[U20] Py：缓存函数结果
来源：http://dali.jinghuilouyu.cn/Article/details/gt2knmxkdpx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xinyue.icu/Article/details/gt2mvsszxpf.html


<!-- 参考信息 -->