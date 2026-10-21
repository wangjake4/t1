代发 wailian999

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xylfe.cn/Article/details/gttancddzl.html

[R80] 查看脚本执行耗时
来源：http://dali.shanyushiyangtech.top/Article/details/gtoyhofvsv.html

time ./run.sh
来源：http://dali.yuxming.cn/Article/details/gttlrmxatv.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtpjqanouo.html

S. C / C++ 专题
来源：http://dali.zhiwuduotai.top/Article/details/gtxknqkbqm.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gttjdxcgxe.html

[S01] C：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtlsxubxkq.html

#include <stdio.h>
来源：http://dali.nwbrower.top/Article/details/gtltfciuzf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.haohaochexian.top/Article/details/gtiwhpcqtd.html

[S02] C：变量与格式化输出
来源：http://dali.cqqwz.cn/Article/details/gtbucqqzzx.html

int a = 10; printf("%d\n", a);
来源：http://dali.tanke756.top/Article/details/gtmjzstrcc.html

[S03] C：读入整数
来源：http://dali.yuxming.cn/Article/details/gtaovgihxs.html

int x; scanf("%d", &x);
来源：http://dali.hnxiangtu.top/Article/details/gtghhiggye.html

[S04] C：字符串复制
来源：http://dali.cqqwz.cn/Article/details/gtqlhdaufy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xylfe.cn/Article/details/gtcpmnppjb.html

[S05] C：字符串长度
来源：http://dali.shuidangran.top/Article/details/gtsqzqhwni.html

strlen(s)
来源：http://dali.meibo888.top/Article/details/gtpqtdxjlz.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gtvviczwjq.html

strcmp(a, b) == 0
来源：http://dali.aizwys.cn/Article/details/gtaijunogv.html

[S07] C：数组遍历求和
来源：http://dali.aibaodan.cn/Article/details/gtiwqybize.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenjidiqi.icu/Article/details/gtbclrbnsw.html

[S08] C：动态内存分配与释放
来源：http://dali.shangyingyoupin.top/Article/details/gtdtmsydrn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.haohaochexian.top/Article/details/gtawtjyhbr.html

[S09] C：结构体定义与初始化
来源：http://dali.chenjidiqi.icu/Article/details/gtfjwqygye.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.mhx1999.top/Article/details/gtrrtivvoi.html

[S10] C：指针与解引用
来源：http://dali.cucudq.cn/Article/details/gtfgafppzu.html

int *p = &a;  *p = 5;
来源：http://dali.sxryk.cn/Article/details/gtmwqcbocw.html

[S11] C：逐行读文件
来源：http://dali.bjfxy.top/Article/details/gtzntuchph.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yvedp.cn/Article/details/gtqxytfbcw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.snrcjt.cn/Article/details/gtvenrkior.html

fclose(f);
来源：http://dali.9152youxi.cn/Article/details/gtumbeghsn.html

[S12] C：写文件
来源：http://dali.jqgufenzy.top/Article/details/gttvlktwrz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shanyushiyangtech.top/Article/details/gtrghixyrg.html

[S13] C：宏定义
来源：http://dali.yj202588.top/Article/details/gtpdyzxiuq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlegjyoxd.html

[S14] C：枚举
来源：http://dali.gotoacloud.top/Article/details/gtegvzvcdq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xziqi.cn/Article/details/gtrffdlwfu.html

[S15] C：类型转换
来源：http://dali.zhixingplan.top/Article/details/gtybqqpsge.html

(double) a / b
来源：http://dali.dianchejie.cn/Article/details/gtuivpmsxa.html

[S16] C：位操作置位
来源：http://dali.iojbl.cn/Article/details/gtqdffyoou.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gtkazeggfb.html

[S17] C：安全拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gtowphzcyq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yueranfly.top/Article/details/gtwrprdvqg.html

[S18] C：命令行参数
来源：http://dali.c1oappe.top/Article/details/gteghxcmvc.html

int main(int argc, char **argv)
来源：http://dali.zhoulong.xyz/Article/details/gtkrvhxmxk.html

[S19] C：快速排序
来源：http://dali.chenzaomai.com/Article/details/gtlvxioffp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ehwqpu.com/Article/details/gtwzjhovwb.html

[S20] C：二分查找
来源：http://dali.jinqigfzy.top/Article/details/gtumaxjjrk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jlsjyb.cn/Article/details/gtofvscovh.html

[S21] C：字符类别判断
来源：http://dali.sweek.top/Article/details/gtdzwhiozb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.316326.xyz/Article/details/gtymgljcpg.html

[S22] C：字符串转数字
来源：http://dali.smart0.xyz/Article/details/gtsijqbgjq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.redwolf501.top/Article/details/gtiuiddtjx.html

[S23] C：随机数
来源：http://dali.yuxming.cn/Article/details/gtrdsrjxyy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hammf.cn/Article/details/gtkzfqmtxm.html

[S24] C：获取本地时间
来源：http://dali.meibo888.top/Article/details/gtlqieayos.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.havefunace.top/Article/details/gtdskikxbk.html

[S25] C：内存拷贝
来源：http://dali.zhoulong.xyz/Article/details/gtueldfttk.html

memcpy(dst, src, n);
来源：http://dali.jinqigufen.top/Article/details/gtzzjfokgl.html

[S26] C：内存清零
来源：http://dali.chenjidiqi.icu/Article/details/gtmegdrluu.html

memset(a, 0, sizeof a);
来源：http://dali.yvedp.cn/Article/details/gtsiycuihb.html

[S27] C：定义常量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyrqznmin.html

const double PI = 3.14159;
来源：http://dali.cheryme.top/Article/details/gtrijtssqn.html

[S28] C：静态变量
来源：http://dali.chenjidiqi.icu/Article/details/gtonrijwmm.html

static int counter = 0;
来源：http://dali.vqdsnc.cn/Article/details/gtppvizjle.html

[S29] C：变参函数
来源：http://dali.wangshuangyany.cn/Article/details/gtkpyftssh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xziqi.cn/Article/details/gtojstxvzu.html

[S30] C：头文件保护
来源：http://dali.kuanghao11.cn/Article/details/gtdrkelqkc.html

#ifndef X_H
来源：http://dali.gaohongyu789.top/Article/details/gtacutgrye.html

#define X_H
来源：http://dali.meibo888.top/Article/details/gtlndtaoqa.html

#endif
来源：http://dali.guowangkeji.top/Article/details/gttcxwzelx.html

[S31] C++：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtexxqwllo.html

#include <iostream>
来源：http://dali.guannengcc.top/Article/details/gtthjrtmtf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.smart0.xyz/Article/details/gtvpetbqql.html

[S32] C++：字符串
来源：http://dali.cqqwz.cn/Article/details/gtxhvutsff.html

std::string s = "hi";  s += "!";
来源：http://dali.xylfe.cn/Article/details/gtbxjjlfvi.html

[S33] C++：vector 增删
来源：http://dali.zycfv.cn/Article/details/gtfywpvejv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.mhx1999.top/Article/details/gtwhctkdve.html

[S34] C++：遍历 vector
来源：http://dali.wangdashe.top/Article/details/gtacmjzsua.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gzhubu.top/Article/details/gtgzxcacee.html

[S35] C++：map
来源：http://dali.ehwqpu.com/Article/details/gtrcziqfdp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cashguo.top/Article/details/gtcuezchvi.html

[S36] C++：unordered_map
来源：http://dali.tian-w.cn/Article/details/gtllzgexuw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.c1oappe.top/Article/details/gtnwczcdgq.html

[S37] C++：set
来源：http://dali.sufxvd.cn/Article/details/gtvfukxyyd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.aibaodan.cn/Article/details/gtlgvmvllg.html

[S38] C++：排序
来源：http://dali.zycfv.cn/Article/details/gtgdwcrcek.html

std::sort(v.begin(), v.end());
来源：http://dali.sufxvd.cn/Article/details/gtyfxmmyqt.html

[S39] C++：自定义比较器排序
来源：http://dali.wangdashe.top/Article/details/gtnkvgbids.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sufxvd.cn/Article/details/gtokpziyse.html

[S40] C++：查找元素
来源：http://dali.jianghu66.top/Article/details/gtsuxbxhfv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenzaomai.com/Article/details/gtbyiuyrcl.html

[S41] C++：类与构造函数
来源：http://dali.chenzaomai.com/Article/details/gtixjhjngs.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jianghu66.top/Article/details/gtgcbfljdw.html

[S42] C++：继承与虚函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmryxxai.html

class B : public Base { public: void f() override {} };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtburtjpez.html

[S43] C++：智能指针
来源：http://dali.hongshengwenyu.top/Article/details/gtrecisdvq.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnucqxpjk.html

[S44] C++：引用传参
来源：http://dali.yongpay.top/Article/details/gtyqjdftmi.html

void inc(int &x) { ++x; }
来源：http://dali.andypj.xyz/Article/details/gtqraqpzfh.html

[S45] C++：lambda
来源：http://dali.jlsjyb.cn/Article/details/gtsccvukdr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yueranfly.top/Article/details/gtyghqzape.html

[S46] C++：函数模板
来源：http://dali.aizwys.cn/Article/details/gttfmutxdd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtcmhnibxv.html

[S47] C++：结构化绑定遍历
来源：http://dali.yongpay.top/Article/details/gtamlefjdf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.wangshuangyany.cn/Article/details/gtqxnvkmdg.html

[S48] C++：逐行读文件
来源：http://dali.cashguo.top/Article/details/gtuciqelyk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.dashuyun.cn/Article/details/gtuzpixdgg.html

while (std::getline(in, line)) { }
来源：http://dali.gogol.net.cn/Article/details/gtguycwlqu.html

[S49] C++：写文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnlwourpc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sysykeji.top/Article/details/gtazkawonj.html

[S50] C++：格式化数字
来源：http://dali.haohaochexian.top/Article/details/gtrojmgzgs.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gtfkljgckw.html

[S51] C++：显式类型转换
来源：http://dali.guannengcc.top/Article/details/gtdvgmoewo.html

static_cast<double>(a) / b
来源：http://dali.hongshengwenyu.top/Article/details/gtexqnagld.html

[S52] C++：const 与 noexcept
来源：http://dali.tianlin.xyz/Article/details/gtxgwlgbjx.html

int size() const noexcept { return n_; }
来源：http://dali.chenzaomai.com/Article/details/gtadfqkvof.html

[S53] C++：移动语义
来源：http://dali.shuidangran.top/Article/details/gtaiutdqul.html

std::vector<int> w = std::move(v);
来源：http://dali.smart0.xyz/Article/details/gtulnrawcd.html

[S54] C++：异常处理
来源：http://dali.nanxuanxn.top/Article/details/gtqqtkrdml.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xuetiantiany.cn/Article/details/gtpcrckljy.html

[S55] C++：结构化绑定
来源：http://dali.chenlongwang.top/Article/details/gthrzqaitn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhengqikj.top/Article/details/gtxoomsxnm.html

[S56] C++：optional
来源：http://dali.zhiwuduotai.top/Article/details/gtjpzubqcq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yuxming.cn/Article/details/gthdcexfxt.html

[S57] C++：编译期常量
来源：http://dali.sufxvd.cn/Article/details/gtzrjrhsqg.html

constexpr int N = 10;
来源：http://dali.yuxming.cn/Article/details/gthdutddms.html

[S58] C++：命名空间
来源：http://dali.chenjidiqi.icu/Article/details/gtfkkjfzan.html

namespace ns { int f() { return 1; } }
来源：http://dali.nanxuanxn.top/Article/details/gtffcirzgv.html

[S59] C++：静态断言
来源：http://dali.zycfv.cn/Article/details/gtautwcsui.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shanyushiyangtech.top/Article/details/gtipeotrsy.html

[S60] C++：遍历并删除元素
来源：http://dali.chenzaomai.com/Article/details/gtvnkxenmm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jianghu66.top/Article/details/gtqpecuqlm.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtvfiiobfi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinghuilouyu.cn/Article/details/gtcariqdfp.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtrixxgljf.html

[T01] Kotlin：Hello World
来源：http://dali.nwbrower.top/Article/details/gtsuljfzfe.html

println("Hello")
来源：http://dali.0kj1m.cn/Article/details/gteyasvlju.html

[T02] Kotlin：变量
来源：http://dali.iojbl.cn/Article/details/gtddkshejd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yangfankeji.com/Article/details/gtaciajlnw.html

[T03] Kotlin：字符串模板
来源：http://dali.xziqi.cn/Article/details/gtiwiprrcd.html

"值: $b"
来源：http://dali.gzhubu.top/Article/details/gtswhnctmk.html

[T04] Kotlin：空安全
来源：http://dali.redwolf501.top/Article/details/gttviwaxcc.html

val n: String? = null;  n?.length
来源：http://dali.cucudq.cn/Article/details/gtatxcqipz.html

[T05] Kotlin：when 表达式
来源：http://dali.pycfn.com/Article/details/gtacqxhgde.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.haohaochexian.top/Article/details/gtfvdyduff.html

[T06] Kotlin：集合映射
来源：http://dali.haohaochexian.top/Article/details/gtqntjpbgv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yangfankeji.com/Article/details/gtouuiuwho.html

[T07] Kotlin：集合过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfpmxebaq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.birdmap.top/Article/details/gtemtwjksf.html

[T08] Kotlin：数据类
来源：http://dali.tian-w.cn/Article/details/gtodpwuvns.html

data class User(val name: String, val age: Int)
来源：http://dali.yonumen.top/Article/details/gthanfmyzs.html

[T09] Kotlin：扩展函数
来源：http://dali.bjfxy.top/Article/details/gtegwloheg.html

fun String.exclaim() = this + "!"
来源：http://dali.ehwqpu.com/Article/details/gttoxliasj.html

[T10] Kotlin：默认参数
来源：http://dali.xuanzx.com/Article/details/gtwjobzzwr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfkybkkob.html

[T11] Kotlin：协程
来源：http://dali.fzhhl.top/Article/details/gtfruwekpr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hfpthk.cn/Article/details/gtxiuqlepm.html

[T12] Kotlin：解构声明
来源：http://dali.jinqigufen.top/Article/details/gtznhcvuwy.html

val (a, b) = Pair(1, 2)
来源：http://dali.aibaodan.cn/Article/details/gtnhgiamgg.html

[T13] Kotlin：只读 Map
来源：http://dali.sysykeji.top/Article/details/gtgfmcnrfm.html

val m = mapOf("a" to 1)
来源：http://dali.guannengcc.top/Article/details/gtfcepdmpc.html

[T14] Kotlin：循环
来源：http://dali.hongshengwenyu.top/Article/details/gtrolyolaq.html

for (i in 1..10) println(i)
来源：http://dali.havefunace.top/Article/details/gtslitncco.html

[T15] Kotlin：接口
来源：http://dali.yueranfly.top/Article/details/gtxcdsmlai.html

interface Shape { fun area(): Double }
来源：http://dali.9152youxi.cn/Article/details/gtaawghzoy.html

[T16] Swift：Hello World
来源：http://dali.zdqjudy.top/Article/details/gttubboyut.html

print("Hello")
来源：http://dali.pycfn.com/Article/details/gtftklegkm.html

[T17] Swift：变量与常量
来源：http://dali.ybcxt.top/Article/details/gtbxezlqhe.html

var a = 1;  let b = 2
来源：http://dali.svipenyu.cn/Article/details/gtlsdpvxdm.html

[T18] Swift：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gtcgndvdaa.html

"值: \(b)"
来源：http://dali.dianchejie.cn/Article/details/gthxmrgoqa.html

[T19] Swift：可选绑定
来源：http://dali.pengpengdd.cyou/Article/details/gtwvdkehsv.html

if let n = opt { print(n) }
来源：http://dali.ehwqpu.com/Article/details/gtxitfybcd.html

[T20] Swift：数组操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjzvmzgqh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sweek.top/Article/details/gtdrfagpil.html

[T21] Swift：遍历
来源：http://dali.daxiang520.top/Article/details/gtxnzxkmhv.html

for x in a { print(x) }
来源：http://dali.hnxiangtu.top/Article/details/gtwcwldxlz.html

[T22] Swift：字典
来源：http://dali.c1oappe.top/Article/details/gtstxhmrkh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gotoacloud.top/Article/details/gtfzjgkyla.html

[T23] Swift：函数
来源：http://dali.xuanzx.com/Article/details/gttqbqivtx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sufxvd.cn/Article/details/gttfhhgpfo.html

[T24] Swift：闭包
来源：http://dali.tian-w.cn/Article/details/gtkjcdlxay.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cucudq.cn/Article/details/gttybliape.html

[T25] Swift：结构体
来源：http://dali.hfpthk.cn/Article/details/gtorbuzfte.html

struct P { var x: Int }
来源：http://dali.yuanzhike.top/Article/details/gthvsljkmn.html

[T26] Swift：类与重写
来源：http://dali.cucudq.cn/Article/details/gtsxyjvhtv.html

class A: Base { override func f() {} }
来源：http://dali.hongshengwenyu.top/Article/details/gtpnukislb.html

[T27] Swift：错误处理
来源：http://dali.daxiang520.top/Article/details/gttfagwqhq.html

do { try f() } catch { print(error) }
来源：http://dali.yuanzhike.top/Article/details/gtjtbhdnhe.html

[T28] Swift：枚举
来源：http://dali.mhx1999.top/Article/details/gtvlkezwmy.html

enum Color { case red, green }
来源：http://dali.zycfv.cn/Article/details/gtgjppzkjr.html

[T29] Swift：guard 提前返回
来源：http://dali.daria6918.cn/Article/details/gtlvmlahfp.html

guard let x = opt else { return }
来源：http://dali.vqdsnc.cn/Article/details/gtyqvkfzzi.html

[T30] Swift：协议
来源：http://dali.chenzaomai.com/Article/details/gtszrkpmdo.html

protocol Shape { func area() -> Double }
来源：http://dali.nwbrower.top/Article/details/gtqxdflmbu.html

[T31] Lua：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtluuriabo.html

print("Hello")
来源：http://dali.ehwqpu.com/Article/details/gtidsqrstr.html

[T32] Lua：局部变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzcagezuv.html

local a = 1
来源：http://dali.yj202588.top/Article/details/gtgvjjztav.html

[T33] Lua：表（数组）
来源：http://dali.shzxlz.cn/Article/details/gtimjfxiwy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yangfankeji.com/Article/details/gtlzzqoifc.html

[T34] Lua：遍历表
来源：http://dali.zhengqikj.top/Article/details/gtzwhdzutk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sxryk.cn/Article/details/gtrpoqplis.html

[T35] Lua：字典表
来源：http://dali.daria6918.cn/Article/details/gtifyfould.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yuxming.cn/Article/details/gtleliyfte.html

[T36] Lua：函数
来源：http://dali.gaohongyu789.top/Article/details/gtflmechwj.html

function add(a, b) return a + b end
来源：http://dali.yuxming.cn/Article/details/gtedszgotm.html

[T37] Lua：字符串拼接
来源：http://dali.wangdashe.top/Article/details/gttysmzhth.html

"a" .. "b"
来源：http://dali.feifeiyinyue.top/Article/details/gtnkbmyawl.html

[T38] Lua：条件
来源：http://dali.9152youxi.cn/Article/details/gtylkieltf.html

if x > 0 then print("正") end
来源：http://dali.yuanzhike.top/Article/details/gtwentmjkk.html

[T39] Lua：模式匹配
来源：http://dali.redwolf501.top/Article/details/gtvdiwdguy.html

string.find(s, "%d+")
来源：http://dali.yj20258888.top/Article/details/gtkhgbuztv.html

[T40] Lua：元表
来源：http://dali.zhoulong.xyz/Article/details/gtlcrfisgz.html

setmetatable({}, { __index = base })
来源：http://dali.c1oappe.top/Article/details/gtvfnhhhno.html

[T41] Perl：Hello World
来源：http://dali.sweek.top/Article/details/gtqcgbwibd.html

print "Hello\n";
来源：http://dali.gogol.net.cn/Article/details/gtuzrsgyba.html

[T42] Perl：变量类型
来源：http://dali.pycfn.com/Article/details/gtmvovonmg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yangfankeji.com/Article/details/gtoscaomxr.html

[T43] Perl：字符串插值
来源：http://dali.jqgfzy.top/Article/details/gtnmdalhvq.html

"值: $a"
来源：http://dali.yvedp.cn/Article/details/gtvwnqzuvf.html

[T44] Perl：条件
来源：http://dali.c1oappe.top/Article/details/gtzjblajrm.html

if ($a > 0) { print "正"; }
来源：http://dali.sysykeji.top/Article/details/gtjpxccial.html

[T45] Perl：数组遍历
来源：http://dali.fzhhl.top/Article/details/gtwfsowgmu.html

for my $x (@arr) { print $x; }
来源：http://dali.ydzc1.top/Article/details/gtycwwmmyk.html

[T46] Perl：哈希操作
来源：http://dali.hysaishi.cn/Article/details/gtilsvklsv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hysaishi.cn/Article/details/gtoxbtdwby.html

[T47] Perl：正则捕获
来源：http://dali.quarkkingdee.top/Article/details/gtjkmpnaub.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zycfv.cn/Article/details/gtydacclov.html

[T48] Perl：正则替换
来源：http://dali.fzhhl.top/Article/details/gtajexbjdo.html

$s =~ s/old/new/g;
来源：http://dali.smart0.xyz/Article/details/gtzpnhoxne.html

[T49] Perl：函数
来源：http://dali.chenjidiqi.icu/Article/details/gtskfwvvva.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gtwhoojinz.html

[T50] Perl：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gtncfkfmeh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xinyue.icu/Article/details/gtqtjigopk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sysykeji.top/Article/details/gtlmbkuurr.html

[T51] Scala：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtufobhqwn.html

println("Hello")
来源：http://dali.andypj.xyz/Article/details/gtkfxwvsuq.html

[T52] Scala：变量
来源：http://dali.sufxvd.cn/Article/details/gtrbvzguky.html

val a = 1;  var b = 2
来源：http://dali.yanxiufei.cn/Article/details/gtmouaiehu.html

[T53] Scala：字符串插值
来源：http://dali.jqgfzy.top/Article/details/gtyluaumug.html

s"值: $b"
来源：http://dali.zycfv.cn/Article/details/gtdufntrim.html

[T54] Scala：集合映射
来源：http://dali.jyoumei.cn/Article/details/gtpifmejqx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.birdmap.top/Article/details/gthczqfqkm.html

[T55] Scala：集合过滤
来源：http://dali.zycfv.cn/Article/details/gtwgyetebi.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.havefunace.top/Article/details/gtdqrlakke.html

[T56] Scala：样例类
来源：http://dali.jinghuilouyu.cn/Article/details/gtcbeqtsct.html

case class User(name: String, age: Int)
来源：http://dali.zhengqikj.top/Article/details/gtcxwdhoil.html

[T57] Scala：模式匹配
来源：http://dali.yongpay.top/Article/details/gtzfnkuesw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xuetiantiany.cn/Article/details/gtupvdlsry.html

[T58] Scala：函数定义
来源：http://dali.yueranfly.top/Article/details/gtxgqilcdf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.wangshuangyany.cn/Article/details/gtosnuteju.html

[T59] Scala：循环
来源：http://dali.ivvv.top/Article/details/gthyzgpqza.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhengqikj.top/Article/details/gthpjgtjtz.html

[T60] Scala：折叠
来源：http://dali.316326.xyz/Article/details/gthuwqynyl.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jqgfzy.top/Article/details/gtfdnlxgzs.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtgisfkmwy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.mhx1999.top/Article/details/gtpdxarqrn.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtoibuwnkw.html

[U01] Py：创建虚拟环境
来源：http://dali.pycfn.com/Article/details/gtoehmbcik.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jyoumei.cn/Article/details/gttzrjhgvk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.daxiang520.top/Article/details/gtrgasygqi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.daria6918.cn/Article/details/gtdbwwphel.html

[U03] Py：加载 .env 配置
来源：http://dali.yangfankeji.com/Article/details/gtymnrztwf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yuxming.cn/Article/details/gtbpbsaixh.html

[U04] Py：变量调试打印
来源：http://dali.zhiwuduotai.top/Article/details/gtleckuopt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.0kj1m.cn/Article/details/gtuiriexpg.html

[U05] Py：列表去重且保序
来源：http://dali.0kj1m.cn/Article/details/gtmgyhyrzr.html

list(dict.fromkeys(arr))
来源：http://dali.kuanghao11.cn/Article/details/gtmkhrrdgj.html

[U06] Py：合并两个字典
来源：http://dali.nanxinkj.top/Article/details/gtolkssvwe.html

{**a, **b}
来源：http://dali.jyoumei.cn/Article/details/gtqtjwzfzj.html

[U07] Py：反转字典键值
来源：http://dali.hnxiangtu.top/Article/details/gtemwncyws.html

{v: k for k, v in d.items()}
来源：http://dali.zycfv.cn/Article/details/gtvschkogv.html

[U08] Py：展平二维列表
来源：http://dali.zhoulong.xyz/Article/details/gtaixkrfac.html

[y for x in nested for y in x]
来源：http://dali.zdqjudy.top/Article/details/gtgvegzlpr.html

[U09] Py：字典取最大值的键
来源：http://dali.pengpengdd.cyou/Article/details/gtjsrixfvy.html

max(d, key=d.get)
来源：http://dali.wangdashe.top/Article/details/gtybcmqurp.html

[U10] Py：按值排序字典
来源：http://dali.jyoumei.cn/Article/details/gtahznkhht.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.dianchejie.cn/Article/details/gtlpozdijr.html

[U11] Py：生成器表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgguefzex.html

(x * 2 for x in arr)
来源：http://dali.jinqigufen.top/Article/details/gtcycgsfyg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkpapymjl.html

Counter(arr).most_common(3)
来源：http://dali.ivvv.top/Article/details/gtbudrqyua.html

[U13] Py：固定长度队列
来源：http://dali.xuetiantiany.cn/Article/details/gtnexvmmfi.html

deque(maxlen=10)
来源：http://dali.yj202588.top/Article/details/gterhtwlbc.html

[U14] Py：分组收集到列表
来源：http://dali.ydzc1.top/Article/details/gtamzqvmcy.html

defaultdict(list)
来源：http://dali.jyoumei.cn/Article/details/gtocxfeddr.html

[U15] Py：高精度计时
来源：http://dali.jinqigufen.top/Article/details/gtoglctrrc.html

t = time.perf_counter()
来源：http://dali.c1oappe.top/Article/details/gtwlheehqz.html

[U16] Py：命令行参数解析
来源：http://dali.nwbrower.top/Article/details/gtwsncvbaq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yj20258.top/Article/details/gtordtranx.html

[U17] Py：初始化日志
来源：http://dali.jiagoushi.top/Article/details/gtrevtpizr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.guowangkeji.top/Article/details/gtvmkkpfer.html

[U18] Py：预编译正则
来源：http://dali.smart0.xyz/Article/details/gttkntwoes.html

pat = re.compile(r"\d+")
来源：http://dali.meibo888.top/Article/details/gtbfjfprcg.html

[U19] Py：正则替换带回调
来源：http://dali.jlsjyb.cn/Article/details/gtsyvppibz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hywenlv.cn/Article/details/gteosmmxtx.html

[U20] Py：缓存函数结果
来源：http://dali.kuanghao11.cn/Article/details/gtcjjukjqp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.mhx1999.top/Article/details/gtwqaldhwt.html


<!-- 参考信息 -->