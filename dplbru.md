代发 wailian999

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yangfankeji.com/Article/details/gtjtlrylkx.html

[R80] 查看脚本执行耗时
来源：http://dali.xylfe.cn/Article/details/gtjfnngmoi.html

time ./run.sh
来源：http://dali.birdmap.top/Article/details/gttihuqumk.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtuptmjxjv.html

S. C / C++ 专题
来源：http://dali.chenzaomai.com/Article/details/gtspuqrtaj.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtpscmeygv.html

[S01] C：Hello World
来源：http://dali.yj202588.top/Article/details/gthhogqrhc.html

#include <stdio.h>
来源：http://dali.mhx1999.top/Article/details/gtdavyztgd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinqigufen.top/Article/details/gtjbjefvxb.html

[S02] C：变量与格式化输出
来源：http://dali.aibaodan.cn/Article/details/gtjiqlnbhu.html

int a = 10; printf("%d\n", a);
来源：http://dali.zycfv.cn/Article/details/gtodakvsti.html

[S03] C：读入整数
来源：http://dali.zhixingplan.top/Article/details/gttpszsegh.html

int x; scanf("%d", &x);
来源：http://dali.nanxinkj.top/Article/details/gtrpqyahgj.html

[S04] C：字符串复制
来源：http://dali.hongshengwenyu.top/Article/details/gtkqzogaqp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hysaishi.cn/Article/details/gtdfrxxkwa.html

[S05] C：字符串长度
来源：http://dali.jlsjyb.cn/Article/details/gtcranawzg.html

strlen(s)
来源：http://dali.cdnleiting.top/Article/details/gtrmjlklee.html

[S06] C：字符串比较
来源：http://dali.zycfv.cn/Article/details/gtujlgaekk.html

strcmp(a, b) == 0
来源：http://dali.ydzc1.top/Article/details/gtdxjubncg.html

[S07] C：数组遍历求和
来源：http://dali.jlsjyb.cn/Article/details/gtfmichcxt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.9152youxi.cn/Article/details/gtxxzodlpw.html

[S08] C：动态内存分配与释放
来源：http://dali.gzhubu.top/Article/details/gtjgbclrpq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.svipenyu.cn/Article/details/gtxooqbwkr.html

[S09] C：结构体定义与初始化
来源：http://dali.birdmap.top/Article/details/gtcfmvsgbd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.0kj1m.cn/Article/details/gtbduwrjnr.html

[S10] C：指针与解引用
来源：http://dali.jinqigufen.top/Article/details/gtigmyjyrs.html

int *p = &a;  *p = 5;
来源：http://dali.yangfankeji.com/Article/details/gtkxxhgiaf.html

[S11] C：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gtqjjazqbt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.andypj.xyz/Article/details/gthndbbyix.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yangfankeji.com/Article/details/gtdjnjnrut.html

fclose(f);
来源：http://dali.ehwqpu.com/Article/details/gtzeuwypco.html

[S12] C：写文件
来源：http://dali.vqdsnc.cn/Article/details/gtngosnhsd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangdashe.top/Article/details/gtgjkabmwx.html

[S13] C：宏定义
来源：http://dali.9152youxi.cn/Article/details/gtomktwicv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.andypj.xyz/Article/details/gtaeegatww.html

[S14] C：枚举
来源：http://dali.hammf.cn/Article/details/gtrfpklnjk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.guannengcc.top/Article/details/gtyaenrxfv.html

[S15] C：类型转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzjyhpgbd.html

(double) a / b
来源：http://dali.svipenyu.cn/Article/details/gtdalprpiv.html

[S16] C：位操作置位
来源：http://dali.ydzc1.top/Article/details/gtsudsdfxk.html

x |= (1 << 3);
来源：http://dali.sysykeji.top/Article/details/gthojwuuhb.html

[S17] C：安全拼接字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtmxjxwfjd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yangfankeji.com/Article/details/gtfpldgfob.html

[S18] C：命令行参数
来源：http://dali.gotoacloud.top/Article/details/gtcfvhpzrt.html

int main(int argc, char **argv)
来源：http://dali.yanxiufei.cn/Article/details/gtaghbacgg.html

[S19] C：快速排序
来源：http://dali.shuidangran.top/Article/details/gtenybsmvm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinqigufen.top/Article/details/gtelwxjfqy.html

[S20] C：二分查找
来源：http://dali.shangyingyoupin.top/Article/details/gtcedbzmpz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.andypj.xyz/Article/details/gthkhjnded.html

[S21] C：字符类别判断
来源：http://dali.cheryme.top/Article/details/gtarpraxqh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenjidiqi.icu/Article/details/gtsqcidses.html

[S22] C：字符串转数字
来源：http://dali.sweek.top/Article/details/gtkhnqukuu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xuanzx.com/Article/details/gtbgybtnne.html

[S23] C：随机数
来源：http://dali.nanxinkj.top/Article/details/gtdlcgwzma.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xuanzx.com/Article/details/gtqhvhalpr.html

[S24] C：获取本地时间
来源：http://dali.daria6918.cn/Article/details/gtxypewogn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hfpthk.cn/Article/details/gtniysfscg.html

[S25] C：内存拷贝
来源：http://dali.gogol.net.cn/Article/details/gtczibxnks.html

memcpy(dst, src, n);
来源：http://dali.snrcjt.cn/Article/details/gteltkkgzi.html

[S26] C：内存清零
来源：http://dali.yuanzhike.top/Article/details/gtlprllxnu.html

memset(a, 0, sizeof a);
来源：http://dali.jlsjyb.cn/Article/details/gtubxkzakv.html

[S27] C：定义常量
来源：http://dali.haohaochexian.top/Article/details/gtquupccbv.html

const double PI = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gtjzqjiioj.html

[S28] C：静态变量
来源：http://dali.0kj1m.cn/Article/details/gtiuiflwok.html

static int counter = 0;
来源：http://dali.xinyue.icu/Article/details/gttullokpt.html

[S29] C：变参函数
来源：http://dali.smart0.xyz/Article/details/gtyfgakqnu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.pycfn.com/Article/details/gtovrnnznx.html

[S30] C：头文件保护
来源：http://dali.zdqjudy.top/Article/details/gttgrpfbyk.html

#ifndef X_H
来源：http://dali.ybcxt.top/Article/details/gtsakjjxxa.html

#define X_H
来源：http://dali.chenzaomai.com/Article/details/gtdelsksii.html

#endif
来源：http://dali.wangshuangyany.cn/Article/details/gtpwuejauh.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtcjmxryxm.html

#include <iostream>
来源：http://dali.gotoacloud.top/Article/details/gteaioheqr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ppjwa.cn/Article/details/gtngessoeg.html

[S32] C++：字符串
来源：http://dali.zhixingplan.top/Article/details/gtqdrwgbqz.html

std::string s = "hi";  s += "!";
来源：http://dali.gzhubu.top/Article/details/gtyktbcgql.html

[S33] C++：vector 增删
来源：http://dali.hnxiangtu.top/Article/details/gtohqfcjmi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.0kj1m.cn/Article/details/gtqelrbwtp.html

[S34] C++：遍历 vector
来源：http://dali.bjfxy.top/Article/details/gtcdlnfmmn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sxryk.cn/Article/details/gtsifjgtrg.html

[S35] C++：map
来源：http://dali.yongpay.top/Article/details/gtsmruynqa.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yongpay.top/Article/details/gttpqzabqb.html

[S36] C++：unordered_map
来源：http://dali.nwbrower.top/Article/details/gtlbybqxxe.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gtttivapyr.html

[S37] C++：set
来源：http://dali.yuxming.cn/Article/details/gtmlmoysjf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtssgekmbq.html

[S38] C++：排序
来源：http://dali.yuxming.cn/Article/details/gtitsdnpfm.html

std::sort(v.begin(), v.end());
来源：http://dali.zhoulong.xyz/Article/details/gtogijsopi.html

[S39] C++：自定义比较器排序
来源：http://dali.sufxvd.cn/Article/details/gtejxlmlqs.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jqgufenzy.top/Article/details/gtbsbgcvlo.html

[S40] C++：查找元素
来源：http://dali.hongshengwenyu.top/Article/details/gtutdxnckv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gtcdheblia.html

[S41] C++：类与构造函数
来源：http://dali.chenzaomai.com/Article/details/gtsbuoqzjq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cashguo.top/Article/details/gtbkpwwjat.html

[S42] C++：继承与虚函数
来源：http://dali.ivvv.top/Article/details/gtitzrlema.html

class B : public Base { public: void f() override {} };
来源：http://dali.hywenlv.cn/Article/details/gtvexvqbcs.html

[S43] C++：智能指针
来源：http://dali.xuanzx.com/Article/details/gtfhhfvosw.html

auto p = std::make_unique<int>(5);
来源：http://dali.316326.xyz/Article/details/gtkwgotete.html

[S44] C++：引用传参
来源：http://dali.ybcxt.top/Article/details/gtvjigmflb.html

void inc(int &x) { ++x; }
来源：http://dali.haohaochexian.top/Article/details/gtkachpxyo.html

[S45] C++：lambda
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzbimrjm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.wangdashe.top/Article/details/gtdjtektyn.html

[S46] C++：函数模板
来源：http://dali.zhongyouzk.top/Article/details/gtbswvnoki.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cheryme.top/Article/details/gthcapiull.html

[S47] C++：结构化绑定遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtcsrgeybb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.daria6918.cn/Article/details/gtlcaacklm.html

[S48] C++：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtuecinqsw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.fzhhl.top/Article/details/gtucjhnwyr.html

while (std::getline(in, line)) { }
来源：http://dali.guannengcc.top/Article/details/gtzequxbkc.html

[S49] C++：写文件
来源：http://dali.shzxlz.cn/Article/details/gtinazdoxn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jianghu66.top/Article/details/gttkvbdref.html

[S50] C++：格式化数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpbnbwpey.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.guannengcc.top/Article/details/gthylzkevh.html

[S51] C++：显式类型转换
来源：http://dali.yuxming.cn/Article/details/gtgbkpaxer.html

static_cast<double>(a) / b
来源：http://dali.yuanzhike.top/Article/details/gtvctlvevv.html

[S52] C++：const 与 noexcept
来源：http://dali.ybcxt.top/Article/details/gtmcuczixq.html

int size() const noexcept { return n_; }
来源：http://dali.cheryme.top/Article/details/gtihythqde.html

[S53] C++：移动语义
来源：http://dali.zycfv.cn/Article/details/gthzesduqx.html

std::vector<int> w = std::move(v);
来源：http://dali.yongpay.top/Article/details/gtuzriekdx.html

[S54] C++：异常处理
来源：http://dali.chenjidiqi.icu/Article/details/gtxygfzugs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gtugbalsft.html

[S55] C++：结构化绑定
来源：http://dali.yueranfly.top/Article/details/gtwvpculsz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtgrwufxkw.html

[S56] C++：optional
来源：http://dali.birdmap.top/Article/details/gtdhlvwtzi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.guannengcc.top/Article/details/gtrcnvyutq.html

[S57] C++：编译期常量
来源：http://dali.smart0.xyz/Article/details/gtdhltqquo.html

constexpr int N = 10;
来源：http://dali.zhengqikj.top/Article/details/gtcbpiuoay.html

[S58] C++：命名空间
来源：http://dali.shangyingyoupin.top/Article/details/gtzprwgbjs.html

namespace ns { int f() { return 1; } }
来源：http://dali.tianlin.xyz/Article/details/gtomegmgec.html

[S59] C++：静态断言
来源：http://dali.gotoacloud.top/Article/details/gtichikvdr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.nwbrower.top/Article/details/gtuggrpcpn.html

[S60] C++：遍历并删除元素
来源：http://dali.yueranfly.top/Article/details/gtqpnbgrho.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tianlin.xyz/Article/details/gtcwnlpvug.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjpzqspfq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.snrcjt.cn/Article/details/gtqyeqptdp.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtbntecwqc.html

[T01] Kotlin：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqgadquw.html

println("Hello")
来源：http://dali.redwolf501.top/Article/details/gtylooiddh.html

[T02] Kotlin：变量
来源：http://dali.yonumen.top/Article/details/gtirdeyllj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yuanzhike.top/Article/details/gtjieursar.html

[T03] Kotlin：字符串模板
来源：http://dali.gzhubu.top/Article/details/gtusfmkypy.html

"值: $b"
来源：http://dali.yj20258888.top/Article/details/gtdfyxmqei.html

[T04] Kotlin：空安全
来源：http://dali.hywenlv.cn/Article/details/gtbaxqwrpf.html

val n: String? = null;  n?.length
来源：http://dali.zhongyouzk.top/Article/details/gtbjxuiuww.html

[T05] Kotlin：when 表达式
来源：http://dali.jinqigufen.top/Article/details/gtgramlwoz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.havefunace.top/Article/details/gtpbzpoiqc.html

[T06] Kotlin：集合映射
来源：http://dali.nanxinkj.top/Article/details/gtfwjpgcja.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sufxvd.cn/Article/details/gtedtdzuyd.html

[T07] Kotlin：集合过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtjrsrsjdx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hnxiangtu.top/Article/details/gtxwetbhsu.html

[T08] Kotlin：数据类
来源：http://dali.ivvv.top/Article/details/gtgmdewkln.html

data class User(val name: String, val age: Int)
来源：http://dali.ivvv.top/Article/details/gtyyqltpes.html

[T09] Kotlin：扩展函数
来源：http://dali.vqdsnc.cn/Article/details/gtxvfezijg.html

fun String.exclaim() = this + "!"
来源：http://dali.wangshuangyany.cn/Article/details/gtrilnamwb.html

[T10] Kotlin：默认参数
来源：http://dali.smart0.xyz/Article/details/gtnxytzntg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfgpyjube.html

[T11] Kotlin：协程
来源：http://dali.hywenlv.cn/Article/details/gtruacmlcn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yj20258888.top/Article/details/gtutgsgwxd.html

[T12] Kotlin：解构声明
来源：http://dali.jinghuilouyu.cn/Article/details/gtlieyvggl.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gtpaejbwlj.html

[T13] Kotlin：只读 Map
来源：http://dali.zhengqikj.top/Article/details/gtegjhljxz.html

val m = mapOf("a" to 1)
来源：http://dali.cashguo.top/Article/details/gtuagztlol.html

[T14] Kotlin：循环
来源：http://dali.cashguo.top/Article/details/gtkxynskuu.html

for (i in 1..10) println(i)
来源：http://dali.nanxinkj.top/Article/details/gtikipeztc.html

[T15] Kotlin：接口
来源：http://dali.zhaomingkeji.xyz/Article/details/gticnbhwsp.html

interface Shape { fun area(): Double }
来源：http://dali.hysaishi.cn/Article/details/gtwpfhckqg.html

[T16] Swift：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtfckatxwh.html

print("Hello")
来源：http://dali.dashuyun.cn/Article/details/gthrllzung.html

[T17] Swift：变量与常量
来源：http://dali.xziqi.cn/Article/details/gtgjdwzkxm.html

var a = 1;  let b = 2
来源：http://dali.mhx1999.top/Article/details/gtnlabehsl.html

[T18] Swift：字符串插值
来源：http://dali.havefunace.top/Article/details/gtcoxhroap.html

"值: \(b)"
来源：http://dali.zhengqikj.top/Article/details/gtjbsvxjdr.html

[T19] Swift：可选绑定
来源：http://dali.jinyuanbaomall.cn/Article/details/gtffnrensa.html

if let n = opt { print(n) }
来源：http://dali.xziqi.cn/Article/details/gtmulzriiu.html

[T20] Swift：数组操作
来源：http://dali.yongpay.top/Article/details/gtoztmuvog.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yongpay.top/Article/details/gtrpzyvbhp.html

[T21] Swift：遍历
来源：http://dali.sufxvd.cn/Article/details/gtzrdxyvgf.html

for x in a { print(x) }
来源：http://dali.quarkkingdee.top/Article/details/gtpdqdwtbj.html

[T22] Swift：字典
来源：http://dali.316326.xyz/Article/details/gteratkemt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhoulong.xyz/Article/details/gtqzwpuwpl.html

[T23] Swift：函数
来源：http://dali.sxryk.cn/Article/details/gtgpvplvsv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yuxming.cn/Article/details/gtajoujfgz.html

[T24] Swift：闭包
来源：http://dali.fengsongda.top/Article/details/gtuaydbnvr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xylfe.cn/Article/details/gtcrgszuly.html

[T25] Swift：结构体
来源：http://dali.vqdsnc.cn/Article/details/gtaqdsbskq.html

struct P { var x: Int }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbismxndx.html

[T26] Swift：类与重写
来源：http://dali.jinqigfzy.top/Article/details/gtumunhoyl.html

class A: Base { override func f() {} }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjasfnnn.html

[T27] Swift：错误处理
来源：http://dali.9152youxi.cn/Article/details/gtxdsdwoip.html

do { try f() } catch { print(error) }
来源：http://dali.feifeiyinyue.top/Article/details/gtrrmnmvss.html

[T28] Swift：枚举
来源：http://dali.fengsongda.top/Article/details/gtrzeiydgn.html

enum Color { case red, green }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtabocfmsp.html

[T29] Swift：guard 提前返回
来源：http://dali.ydzc1.top/Article/details/gtdifjyovl.html

guard let x = opt else { return }
来源：http://dali.yj20258.top/Article/details/gttlolxusl.html

[T30] Swift：协议
来源：http://dali.yanxiufei.cn/Article/details/gtcrkfejge.html

protocol Shape { func area() -> Double }
来源：http://dali.gzhubu.top/Article/details/gtfovjdgsg.html

[T31] Lua：Hello World
来源：http://dali.aibaodan.cn/Article/details/gtwbcrnvki.html

print("Hello")
来源：http://dali.daria6918.cn/Article/details/gtvcvbcuwj.html

[T32] Lua：局部变量
来源：http://dali.zhiwuduotai.top/Article/details/gtraaangfk.html

local a = 1
来源：http://dali.mhx1999.top/Article/details/gtmttuqcoh.html

[T33] Lua：表（数组）
来源：http://dali.tian-w.cn/Article/details/gtqdtweeqj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yonumen.top/Article/details/gtffjurrlf.html

[T34] Lua：遍历表
来源：http://dali.shzxlz.cn/Article/details/gtwfkbbtbc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yueranfly.top/Article/details/gtsjlpjdiy.html

[T35] Lua：字典表
来源：http://dali.jqgfzy.top/Article/details/gtlfzmwppk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinqigufen.top/Article/details/gtstbmdasi.html

[T36] Lua：函数
来源：http://dali.andypj.xyz/Article/details/gtudxprxbq.html

function add(a, b) return a + b end
来源：http://dali.chenlongwang.top/Article/details/gttdfttnht.html

[T37] Lua：字符串拼接
来源：http://dali.gzhubu.top/Article/details/gtbaaibzdw.html

"a" .. "b"
来源：http://dali.shanyushiyangkeji.top/Article/details/gterptpyck.html

[T38] Lua：条件
来源：http://dali.pengpengdd.cyou/Article/details/gtbesnpesk.html

if x > 0 then print("正") end
来源：http://dali.svipenyu.cn/Article/details/gtqgcjcamh.html

[T39] Lua：模式匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtddwmqfyr.html

string.find(s, "%d+")
来源：http://dali.ppjwa.cn/Article/details/gtncarleft.html

[T40] Lua：元表
来源：http://dali.hfpthk.cn/Article/details/gteqhagjxt.html

setmetatable({}, { __index = base })
来源：http://dali.jqgfzy.top/Article/details/gtloyvmmgt.html

[T41] Perl：Hello World
来源：http://dali.ivvv.top/Article/details/gtkuzgeymg.html

print "Hello\n";
来源：http://dali.hongshengwenyu.top/Article/details/gtmtljmknh.html

[T42] Perl：变量类型
来源：http://dali.xylfe.cn/Article/details/gtlxijuqif.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ivvv.top/Article/details/gtavtwxrrq.html

[T43] Perl：字符串插值
来源：http://dali.yanxiufei.cn/Article/details/gtkktblxyd.html

"值: $a"
来源：http://dali.tanke756.top/Article/details/gtilokliof.html

[T44] Perl：条件
来源：http://dali.xuanzx.com/Article/details/gtbazxgvaq.html

if ($a > 0) { print "正"; }
来源：http://dali.sxryk.cn/Article/details/gtadsckhds.html

[T45] Perl：数组遍历
来源：http://dali.c1oappe.top/Article/details/gtouzrfgfr.html

for my $x (@arr) { print $x; }
来源：http://dali.sweek.top/Article/details/gtwkttuzrx.html

[T46] Perl：哈希操作
来源：http://dali.redwolf501.top/Article/details/gtovwpbdtt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yangfankeji.com/Article/details/gtnlnlkuja.html

[T47] Perl：正则捕获
来源：http://dali.shuidangran.top/Article/details/gtfasayueq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ydzc1.top/Article/details/gtumvvwuzw.html

[T48] Perl：正则替换
来源：http://dali.ivvv.top/Article/details/gtqfqhkmau.html

$s =~ s/old/new/g;
来源：http://dali.xylfe.cn/Article/details/gtyamemeyl.html

[T49] Perl：函数
来源：http://dali.andypj.xyz/Article/details/gtbyjcsvkm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtshptcfjn.html

[T50] Perl：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtnyiipgbr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.vqdsnc.cn/Article/details/gtbqveslgb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.bjfxy.top/Article/details/gtymtagrxb.html

[T51] Scala：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnyaqwwef.html

println("Hello")
来源：http://dali.zhixingplan.top/Article/details/gtmphyvtim.html

[T52] Scala：变量
来源：http://dali.wangdashe.top/Article/details/gtlevystyd.html

val a = 1;  var b = 2
来源：http://dali.shuidangran.top/Article/details/gteyqiiunj.html

[T53] Scala：字符串插值
来源：http://dali.jianghu66.top/Article/details/gtbrqloioy.html

s"值: $b"
来源：http://dali.pycfn.com/Article/details/gtttecwumi.html

[T54] Scala：集合映射
来源：http://dali.andypj.xyz/Article/details/gtbjpoqomk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.dianchejie.cn/Article/details/gtbdlguylj.html

[T55] Scala：集合过滤
来源：http://dali.cashguo.top/Article/details/gtltvhvjch.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmqwbdxze.html

[T56] Scala：样例类
来源：http://dali.zdqjudy.top/Article/details/gtzriycwia.html

case class User(name: String, age: Int)
来源：http://dali.chenjidiqi.icu/Article/details/gtdhldkyiu.html

[T57] Scala：模式匹配
来源：http://dali.9152youxi.cn/Article/details/gtkgubvafl.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.sysykeji.top/Article/details/gtrfcnkwel.html

[T58] Scala：函数定义
来源：http://dali.aibaodan.cn/Article/details/gtrnbcfoae.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jqgfzy.top/Article/details/gtcorkeywd.html

[T59] Scala：循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcpgjgzfb.html

for (i <- 1 to 10) println(i)
来源：http://dali.chenzaomai.com/Article/details/gtscnbfzeo.html

[T60] Scala：折叠
来源：http://dali.nanxinkj.top/Article/details/gtrxlxtwgw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zycfv.cn/Article/details/gtabwcjmvs.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtzbxrqtkl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cheryme.top/Article/details/gtosondifx.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtajmpbasw.html

[U01] Py：创建虚拟环境
来源：http://dali.pycfn.com/Article/details/gtwksouqfr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gticqoltaa.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cashguo.top/Article/details/gtyqdhrvut.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hysaishi.cn/Article/details/gtxsbwriec.html

[U03] Py：加载 .env 配置
来源：http://dali.yuanzhike.top/Article/details/gtnjhmhiys.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jiagoushi.top/Article/details/gtzgtmslfj.html

[U04] Py：变量调试打印
来源：http://dali.316326.xyz/Article/details/gtckachnwg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ydzc1.top/Article/details/gtccymnovb.html

[U05] Py：列表去重且保序
来源：http://dali.svipenyu.cn/Article/details/gtnfzrgzqr.html

list(dict.fromkeys(arr))
来源：http://dali.tanke756.top/Article/details/gtkyqculch.html

[U06] Py：合并两个字典
来源：http://dali.zhongyouzk.top/Article/details/gtxgntynsh.html

{**a, **b}
来源：http://dali.pycfn.com/Article/details/gtvrtjnmgn.html

[U07] Py：反转字典键值
来源：http://dali.yueranfly.top/Article/details/gtuleljneg.html

{v: k for k, v in d.items()}
来源：http://dali.jianghu66.top/Article/details/gtcynafppd.html

[U08] Py：展平二维列表
来源：http://dali.gotoacloud.top/Article/details/gtztddshid.html

[y for x in nested for y in x]
来源：http://dali.zhiwuduotai.top/Article/details/gtktbhryfh.html

[U09] Py：字典取最大值的键
来源：http://dali.wangdashe.top/Article/details/gtwadpykrp.html

max(d, key=d.get)
来源：http://dali.jqgfzy.top/Article/details/gtpdjacnig.html

[U10] Py：按值排序字典
来源：http://dali.yj20258.top/Article/details/gteawsoxdt.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yj202588.top/Article/details/gttifgscfo.html

[U11] Py：生成器表达式
来源：http://dali.tanke756.top/Article/details/gtbuvvquzi.html

(x * 2 for x in arr)
来源：http://dali.wangdashe.top/Article/details/gtzezyyduj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.bjfxy.top/Article/details/gtcmkugdgs.html

Counter(arr).most_common(3)
来源：http://dali.ehwqpu.com/Article/details/gtolzfiqxb.html

[U13] Py：固定长度队列
来源：http://dali.ybcxt.top/Article/details/gtsgvgecci.html

deque(maxlen=10)
来源：http://dali.svipenyu.cn/Article/details/gtznxsncxb.html

[U14] Py：分组收集到列表
来源：http://dali.quarkkingdee.top/Article/details/gtmwbffuze.html

defaultdict(list)
来源：http://dali.gzhubu.top/Article/details/gtxenmajsj.html

[U15] Py：高精度计时
来源：http://dali.hongshengwenyu.top/Article/details/gtkqstdmhe.html

t = time.perf_counter()
来源：http://dali.jyoumei.cn/Article/details/gtjjipiuoq.html

[U16] Py：命令行参数解析
来源：http://dali.zhaomingkeji.xyz/Article/details/gtynvpcpto.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.haohaochexian.top/Article/details/gtaxititrw.html

[U17] Py：初始化日志
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmnzkaujp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.aibaodan.cn/Article/details/gtayakeysi.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gtpwnlaggw.html

pat = re.compile(r"\d+")
来源：http://dali.jiagoushi.top/Article/details/gtowylteyk.html

[U19] Py：正则替换带回调
来源：http://dali.hysaishi.cn/Article/details/gtoxhgumtv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzegzdagp.html

[U20] Py：缓存函数结果
来源：http://dali.daria6918.cn/Article/details/gtxwrfqxli.html

@functools.lru_cache(maxsize=None)
来源：http://dali.dianchejie.cn/Article/details/gtpgxzcbvg.html


<!-- 参考信息 -->