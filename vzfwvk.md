代发 wailian999

export PATH="$HOME/bin:$PATH"
来源：http://dali.hnqzz.top/Article/details/gtqtfhqrxm.html

[R76] 使用临时文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpczunpox.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zdqjudy.top/Article/details/gtjzklikpa.html

[R77] 读取用户输入
来源：http://dali.snrcjt.cn/Article/details/gtoltjeyvo.html

read -rp "请输入: " ans
来源：http://dali.ivvv.top/Article/details/gtdytcdypa.html

[R78] 交互式菜单
来源：http://dali.jlsjyb.cn/Article/details/gtxijuuboj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.meibo888.top/Article/details/gtvgzgkmaq.html

[R79] 解析命令行选项
来源：http://dali.zhixingplan.top/Article/details/gtnyiucwwq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jqgufenzy.top/Article/details/gtianhngwf.html

[R80] 查看脚本执行耗时
来源：http://dali.zhixingplan.top/Article/details/gtglbxvayj.html

time ./run.sh
来源：http://dali.0kj1m.cn/Article/details/gtwuruhrdd.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtqhpbpgaw.html

S. C / C++ 专题
来源：http://dali.jlsjyb.cn/Article/details/gtgtleenll.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtbuzcmetx.html

[S01] C：Hello World
来源：http://dali.yonumen.top/Article/details/gtculrdgyt.html

#include <stdio.h>
来源：http://dali.sysykeji.top/Article/details/gtievkvmkx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yonumen.top/Article/details/gthpxoaxqa.html

[S02] C：变量与格式化输出
来源：http://dali.daria6918.cn/Article/details/gtxrhawfow.html

int a = 10; printf("%d\n", a);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrehtbwmr.html

[S03] C：读入整数
来源：http://dali.jlsjyb.cn/Article/details/gtsghiiriz.html

int x; scanf("%d", &x);
来源：http://dali.zycfv.cn/Article/details/gtdhfwwwte.html

[S04] C：字符串复制
来源：http://dali.ydzc1.top/Article/details/gtufpluuqg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.316326.xyz/Article/details/gtrxgnoqeb.html

[S05] C：字符串长度
来源：http://dali.hnqzz.top/Article/details/gtsioymtpo.html

strlen(s)
来源：http://dali.chenlongwang.top/Article/details/gttnpregxp.html

[S06] C：字符串比较
来源：http://dali.gogol.net.cn/Article/details/gtihgmzvhk.html

strcmp(a, b) == 0
来源：http://dali.daxiang520.top/Article/details/gtufeogqsl.html

[S07] C：数组遍历求和
来源：http://dali.wangshuangyany.cn/Article/details/gtgxsipgsy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.tianlin.xyz/Article/details/gtpzadhmdg.html

[S08] C：动态内存分配与释放
来源：http://dali.wangshuangyany.cn/Article/details/gtacqxgdub.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nanxuanxn.top/Article/details/gtiuqtviyf.html

[S09] C：结构体定义与初始化
来源：http://dali.hnqzz.top/Article/details/gthdhbzxrs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sysykeji.top/Article/details/gtbmujbmpb.html

[S10] C：指针与解引用
来源：http://dali.shuidangran.top/Article/details/gtwynzigww.html

int *p = &a;  *p = 5;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuzpjgbkd.html

[S11] C：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gttnzcpprw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cdnleiting.top/Article/details/gtcnafujod.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gtsttaxxxy.html

fclose(f);
来源：http://dali.cdnleiting.top/Article/details/gtwouvbpzl.html

[S12] C：写文件
来源：http://dali.fzhhl.top/Article/details/gtxvurostd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jlsjyb.cn/Article/details/gtcyuyjbvy.html

[S13] C：宏定义
来源：http://dali.hfpthk.cn/Article/details/gtwbxdwxzj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj20258888.top/Article/details/gteowdgtmb.html

[S14] C：枚举
来源：http://dali.0kj1m.cn/Article/details/gtcahnfapw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.haohaochexian.top/Article/details/gtrqehevnm.html

[S15] C：类型转换
来源：http://dali.chenlongwang.top/Article/details/gtdudjuewx.html

(double) a / b
来源：http://dali.xziqi.cn/Article/details/gtaxewrsuo.html

[S16] C：位操作置位
来源：http://dali.cdnleiting.top/Article/details/gtslufidok.html

x |= (1 << 3);
来源：http://dali.yvedp.cn/Article/details/gtvzjbsoxv.html

[S17] C：安全拼接字符串
来源：http://dali.fengsongda.top/Article/details/gtrirphkof.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yuxming.cn/Article/details/gttwgxzrqq.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqjeygrqu.html

int main(int argc, char **argv)
来源：http://dali.andypj.xyz/Article/details/gtduvdiqou.html

[S19] C：快速排序
来源：http://dali.jiagoushi.top/Article/details/gtfomokrug.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.havefunace.top/Article/details/gtacqgbvce.html

[S20] C：二分查找
来源：http://dali.kuanghao11.cn/Article/details/gtzashhjxc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj202588.top/Article/details/gtgizmhaun.html

[S21] C：字符类别判断
来源：http://dali.cqqwz.cn/Article/details/gtewqacvfo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.andypj.xyz/Article/details/gtvofaipmp.html

[S22] C：字符串转数字
来源：http://dali.daria6918.cn/Article/details/gtqfwmfsmc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jqgfzy.top/Article/details/gttusslbvb.html

[S23] C：随机数
来源：http://dali.hywenlv.cn/Article/details/gtihjknnpx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hnxiangtu.top/Article/details/gtsjhmbnkj.html

[S24] C：获取本地时间
来源：http://dali.dianchejie.cn/Article/details/gtwzrbuhog.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yvedp.cn/Article/details/gthzcvsvet.html

[S25] C：内存拷贝
来源：http://dali.tianlin.xyz/Article/details/gteehyfqbc.html

memcpy(dst, src, n);
来源：http://dali.fzhhl.top/Article/details/gtpftmhybj.html

[S26] C：内存清零
来源：http://dali.tianlin.xyz/Article/details/gtlzmxeaok.html

memset(a, 0, sizeof a);
来源：http://dali.aizwys.cn/Article/details/gtjiqxeher.html

[S27] C：定义常量
来源：http://dali.chenjidiqi.icu/Article/details/gtrrxaehjh.html

const double PI = 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gtfyhdfbga.html

[S28] C：静态变量
来源：http://dali.yuxming.cn/Article/details/gtakpghjni.html

static int counter = 0;
来源：http://dali.yanxiufei.cn/Article/details/gtnawcvwhv.html

[S29] C：变参函数
来源：http://dali.zhengqikj.top/Article/details/gtkxkucwty.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hysaishi.cn/Article/details/gtcygtezho.html

[S30] C：头文件保护
来源：http://dali.fengsongda.top/Article/details/gtohpqlpuz.html

#ifndef X_H
来源：http://dali.gzhubu.top/Article/details/gtejjmmsde.html

#define X_H
来源：http://dali.jqgufenzy.top/Article/details/gtrvahqupz.html

#endif
来源：http://dali.yangfankeji.com/Article/details/gtrupaurbz.html

[S31] C++：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtuwhxcpzu.html

#include <iostream>
来源：http://dali.zhoulong.xyz/Article/details/gtskfuruhg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.aibaodan.cn/Article/details/gtiojjcuey.html

[S32] C++：字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtuitvcofn.html

std::string s = "hi";  s += "!";
来源：http://dali.zhoulong.xyz/Article/details/gtlqqtknen.html

[S33] C++：vector 增删
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuwuosjws.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hysaishi.cn/Article/details/gtpkusuqup.html

[S34] C++：遍历 vector
来源：http://dali.yvedp.cn/Article/details/gtkczlixuc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cheryme.top/Article/details/gtuadvwdue.html

[S35] C++：map
来源：http://dali.yj20258888.top/Article/details/gtsmxjigwd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gtpkrvmajh.html

[S36] C++：unordered_map
来源：http://dali.yuanzhike.top/Article/details/gtmkyanglo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.iojbl.cn/Article/details/gttzgqqzcr.html

[S37] C++：set
来源：http://dali.kuanghao11.cn/Article/details/gtcxrbfqnn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cqqwz.cn/Article/details/gtikmaiudz.html

[S38] C++：排序
来源：http://dali.zhoulong.xyz/Article/details/gtllmzziaz.html

std::sort(v.begin(), v.end());
来源：http://dali.ivvv.top/Article/details/gtlcbawylj.html

[S39] C++：自定义比较器排序
来源：http://dali.nanxuanxn.top/Article/details/gtbfucvght.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj202588.top/Article/details/gtzkstentw.html

[S40] C++：查找元素
来源：http://dali.cheryme.top/Article/details/gtupumbxra.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sweek.top/Article/details/gtamaddtcf.html

[S41] C++：类与构造函数
来源：http://dali.daxiang520.top/Article/details/gtblzfexwv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoylbluji.html

[S42] C++：继承与虚函数
来源：http://dali.hysaishi.cn/Article/details/gthgqpbllh.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkvytkakn.html

[S43] C++：智能指针
来源：http://dali.chenzaomai.com/Article/details/gtdbisamik.html

auto p = std::make_unique<int>(5);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkadczzec.html

[S44] C++：引用传参
来源：http://dali.jinqigfzy.top/Article/details/gtewadhggx.html

void inc(int &x) { ++x; }
来源：http://dali.daxiang520.top/Article/details/gtbtjspain.html

[S45] C++：lambda
来源：http://dali.yonumen.top/Article/details/gtedpqhlep.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hywenlv.cn/Article/details/gthvgxtpcz.html

[S46] C++：函数模板
来源：http://dali.gaohongyu789.top/Article/details/gtolorzyue.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yongpay.top/Article/details/gtajdcoiti.html

[S47] C++：结构化绑定遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtnkbrgxdw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yangfankeji.com/Article/details/gtayztysdu.html

[S48] C++：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gtuwfjlfdb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.316326.xyz/Article/details/gtydrdyklv.html

while (std::getline(in, line)) { }
来源：http://dali.dianchejie.cn/Article/details/gtrayzzbbu.html

[S49] C++：写文件
来源：http://dali.dianchejie.cn/Article/details/gttcyjeysl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.quarkkingdee.top/Article/details/gtjcsxxcpp.html

[S50] C++：格式化数字
来源：http://dali.ehwqpu.com/Article/details/gtbqefland.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.smart0.xyz/Article/details/gtjskomhrh.html

[S51] C++：显式类型转换
来源：http://dali.hnxiangtu.top/Article/details/gtulzptumt.html

static_cast<double>(a) / b
来源：http://dali.guowangkeji.top/Article/details/gtetlqstox.html

[S52] C++：const 与 noexcept
来源：http://dali.0kj1m.cn/Article/details/gthstpjlrq.html

int size() const noexcept { return n_; }
来源：http://dali.ppjwa.cn/Article/details/gtkqzenrjd.html

[S53] C++：移动语义
来源：http://dali.xinyue.icu/Article/details/gtkiwgebfa.html

std::vector<int> w = std::move(v);
来源：http://dali.cdnleiting.top/Article/details/gttcxmueys.html

[S54] C++：异常处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrgnhszhh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.mhx1999.top/Article/details/gtubfvbvkk.html

[S55] C++：结构化绑定
来源：http://dali.tanke756.top/Article/details/gtvlhvtmnq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenlongwang.top/Article/details/gtuocuypmz.html

[S56] C++：optional
来源：http://dali.jyoumei.cn/Article/details/gtonrtbpmu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yangfankeji.com/Article/details/gtbmnlmxkf.html

[S57] C++：编译期常量
来源：http://dali.yongpay.top/Article/details/gtvqkhonoz.html

constexpr int N = 10;
来源：http://dali.snrcjt.cn/Article/details/gtjlxxzfsi.html

[S58] C++：命名空间
来源：http://dali.gzhubu.top/Article/details/gtatsuggoe.html

namespace ns { int f() { return 1; } }
来源：http://dali.gogol.net.cn/Article/details/gtemjxbsms.html

[S59] C++：静态断言
来源：http://dali.yanxiufei.cn/Article/details/gtlqkocyfs.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yj20258888.top/Article/details/gtqoupqwmq.html

[S60] C++：遍历并删除元素
来源：http://dali.xziqi.cn/Article/details/gtgecjahnj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfujpjcrk.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtpkgartcf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.quarkkingdee.top/Article/details/gtwzfontmv.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gthtttllce.html

[T01] Kotlin：Hello World
来源：http://dali.zycfv.cn/Article/details/gtllavlegd.html

println("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gtoompcfzv.html

[T02] Kotlin：变量
来源：http://dali.haohaochexian.top/Article/details/gtectydqzr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yonumen.top/Article/details/gtdgrrkfcv.html

[T03] Kotlin：字符串模板
来源：http://dali.nanxuanxn.top/Article/details/gtemsiaaas.html

"值: $b"
来源：http://dali.nanxinkj.top/Article/details/gthbnfkvaz.html

[T04] Kotlin：空安全
来源：http://dali.haohaochexian.top/Article/details/gtwqsyftya.html

val n: String? = null;  n?.length
来源：http://dali.yangfankeji.com/Article/details/gtspviidps.html

[T05] Kotlin：when 表达式
来源：http://dali.xziqi.cn/Article/details/gtcrqhnwhd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj202588.top/Article/details/gtijcxeipj.html

[T06] Kotlin：集合映射
来源：http://dali.pycfn.com/Article/details/gtuoibkjlq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jyoumei.cn/Article/details/gtbjlhgvxn.html

[T07] Kotlin：集合过滤
来源：http://dali.ppjwa.cn/Article/details/gtawvzxrmi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.feifeiyinyue.top/Article/details/gtigsyvxor.html

[T08] Kotlin：数据类
来源：http://dali.yanxiufei.cn/Article/details/gtjjergkhb.html

data class User(val name: String, val age: Int)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfdqqsju.html

[T09] Kotlin：扩展函数
来源：http://dali.cqqwz.cn/Article/details/gtzpqnfwip.html

fun String.exclaim() = this + "!"
来源：http://dali.xylfe.cn/Article/details/gtgudfvlgk.html

[T10] Kotlin：默认参数
来源：http://dali.guowangkeji.top/Article/details/gtnlaoczym.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sufxvd.cn/Article/details/gtzpfexpge.html

[T11] Kotlin：协程
来源：http://dali.xuanzx.com/Article/details/gtmbrwlrek.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.316326.xyz/Article/details/gtaklmeopy.html

[T12] Kotlin：解构声明
来源：http://dali.zycfv.cn/Article/details/gtewzedybh.html

val (a, b) = Pair(1, 2)
来源：http://dali.tanke756.top/Article/details/gtazkinhpc.html

[T13] Kotlin：只读 Map
来源：http://dali.hongshengwenyu.top/Article/details/gtnjrcwwpm.html

val m = mapOf("a" to 1)
来源：http://dali.yonumen.top/Article/details/gtyhjuagvw.html

[T14] Kotlin：循环
来源：http://dali.hammf.cn/Article/details/gtgppxdsmp.html

for (i in 1..10) println(i)
来源：http://dali.nanxinkj.top/Article/details/gtzmblygdh.html

[T15] Kotlin：接口
来源：http://dali.cashguo.top/Article/details/gtrmqcecso.html

interface Shape { fun area(): Double }
来源：http://dali.daxiang520.top/Article/details/gtdpihceon.html

[T16] Swift：Hello World
来源：http://dali.jianghu66.top/Article/details/gtbdhjjwgb.html

print("Hello")
来源：http://dali.cheryme.top/Article/details/gtbohsbglg.html

[T17] Swift：变量与常量
来源：http://dali.quarkkingdee.top/Article/details/gtrlcjtleb.html

var a = 1;  let b = 2
来源：http://dali.9152youxi.cn/Article/details/gtsylkfcti.html

[T18] Swift：字符串插值
来源：http://dali.iojbl.cn/Article/details/gtfghcglzo.html

"值: \(b)"
来源：http://dali.vqdsnc.cn/Article/details/gtmacasxzm.html

[T19] Swift：可选绑定
来源：http://dali.0kj1m.cn/Article/details/gtfvoictcl.html

if let n = opt { print(n) }
来源：http://dali.gaohongyu789.top/Article/details/gtzviwspol.html

[T20] Swift：数组操作
来源：http://dali.jinqigfzy.top/Article/details/gtilpleinw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.tanke756.top/Article/details/gtpwvbqpfb.html

[T21] Swift：遍历
来源：http://dali.snrcjt.cn/Article/details/gttrtijneg.html

for x in a { print(x) }
来源：http://dali.mhx1999.top/Article/details/gttwnmdkll.html

[T22] Swift：字典
来源：http://dali.cucudq.cn/Article/details/gtkvglafjd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xylfe.cn/Article/details/gtcetuuscc.html

[T23] Swift：函数
来源：http://dali.dianchejie.cn/Article/details/gtusldmakv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.feifeiyinyue.top/Article/details/gtqamkgkji.html

[T24] Swift：闭包
来源：http://dali.tian-w.cn/Article/details/gttmqgucdx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gotoacloud.top/Article/details/gtilzwhnby.html

[T25] Swift：结构体
来源：http://dali.iojbl.cn/Article/details/gtuxdvsqar.html

struct P { var x: Int }
来源：http://dali.zycfv.cn/Article/details/gtdvwpycca.html

[T26] Swift：类与重写
来源：http://dali.ivvv.top/Article/details/gtdwudftrj.html

class A: Base { override func f() {} }
来源：http://dali.jinqigfzy.top/Article/details/gtbozkgejo.html

[T27] Swift：错误处理
来源：http://dali.gogol.net.cn/Article/details/gtxrqkozkp.html

do { try f() } catch { print(error) }
来源：http://dali.wangshuangyany.cn/Article/details/gtoqoyhhug.html

[T28] Swift：枚举
来源：http://dali.316326.xyz/Article/details/gtzqfcsmqm.html

enum Color { case red, green }
来源：http://dali.ppjwa.cn/Article/details/gtbzpsljzc.html

[T29] Swift：guard 提前返回
来源：http://dali.aibaodan.cn/Article/details/gtzwjcohrk.html

guard let x = opt else { return }
来源：http://dali.fzhhl.top/Article/details/gtafuwaqkx.html

[T30] Swift：协议
来源：http://dali.yueranfly.top/Article/details/gtpdcdnqbj.html

protocol Shape { func area() -> Double }
来源：http://dali.yonumen.top/Article/details/gtgozvstti.html

[T31] Lua：Hello World
来源：http://dali.tanke756.top/Article/details/gtznuzrtab.html

print("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gtgamqbwyv.html

[T32] Lua：局部变量
来源：http://dali.yvedp.cn/Article/details/gteiogiqrd.html

local a = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqylzqrf.html

[T33] Lua：表（数组）
来源：http://dali.guowangkeji.top/Article/details/gtzgecihol.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yongpay.top/Article/details/gtuaszlosb.html

[T34] Lua：遍历表
来源：http://dali.cucudq.cn/Article/details/gtvxfcllst.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.wangshuangyany.cn/Article/details/gtmvnkalar.html

[T35] Lua：字典表
来源：http://dali.fzhhl.top/Article/details/gtxggthqly.html

local d = { a = 1 };  d.b = 2
来源：http://dali.guowangkeji.top/Article/details/gtavyaekhs.html

[T36] Lua：函数
来源：http://dali.smart0.xyz/Article/details/gtihypocna.html

function add(a, b) return a + b end
来源：http://dali.svipenyu.cn/Article/details/gtdkwsatin.html

[T37] Lua：字符串拼接
来源：http://dali.andypj.xyz/Article/details/gtxetahlsr.html

"a" .. "b"
来源：http://dali.hysaishi.cn/Article/details/gtsccjsycy.html

[T38] Lua：条件
来源：http://dali.nanxuanxn.top/Article/details/gtdalrukgb.html

if x > 0 then print("正") end
来源：http://dali.jqgfzy.top/Article/details/gtdaabqwed.html

[T39] Lua：模式匹配
来源：http://dali.smart0.xyz/Article/details/gttbudbiwm.html

string.find(s, "%d+")
来源：http://dali.redwolf501.top/Article/details/gtjlkuwoia.html

[T40] Lua：元表
来源：http://dali.yuxming.cn/Article/details/gtwqrwssiw.html

setmetatable({}, { __index = base })
来源：http://dali.yongpay.top/Article/details/gtflpodvjn.html

[T41] Perl：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteqcxcwns.html

print "Hello\n";
来源：http://dali.xuanzx.com/Article/details/gtuhneqiay.html

[T42] Perl：变量类型
来源：http://dali.daria6918.cn/Article/details/gtxfhciyrx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zycfv.cn/Article/details/gtvyiiuluo.html

[T43] Perl：字符串插值
来源：http://dali.guowangkeji.top/Article/details/gtfqhgklpy.html

"值: $a"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtekxuevje.html

[T44] Perl：条件
来源：http://dali.nanxinkj.top/Article/details/gtaqvmgexg.html

if ($a > 0) { print "正"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfruawgww.html

[T45] Perl：数组遍历
来源：http://dali.hnxiangtu.top/Article/details/gtlyhyuzof.html

for my $x (@arr) { print $x; }
来源：http://dali.gogol.net.cn/Article/details/gtfhvhwgtl.html

[T46] Perl：哈希操作
来源：http://dali.fzhhl.top/Article/details/gtlagtjnhz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yj202588.top/Article/details/gtvspsjrhi.html

[T47] Perl：正则捕获
来源：http://dali.bjfxy.top/Article/details/gtqhhpfnbn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yueranfly.top/Article/details/gtsnbujhbr.html

[T48] Perl：正则替换
来源：http://dali.sweek.top/Article/details/gtlkhconwv.html

$s =~ s/old/new/g;
来源：http://dali.nanxuanxn.top/Article/details/gtoqafnczs.html

[T49] Perl：函数
来源：http://dali.yueranfly.top/Article/details/gtvrbfdibz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gtolvdvklt.html

[T50] Perl：逐行读文件
来源：http://dali.yj20258888.top/Article/details/gtmtrfqjpk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.birdmap.top/Article/details/gttcqprrao.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.daria6918.cn/Article/details/gtpdmqjoil.html

[T51] Scala：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtggtewvrq.html

println("Hello")
来源：http://dali.hammf.cn/Article/details/gtkmcchruy.html

[T52] Scala：变量
来源：http://dali.bjfxy.top/Article/details/gtjljbcoss.html

val a = 1;  var b = 2
来源：http://dali.svipenyu.cn/Article/details/gtcnylyaqn.html

[T53] Scala：字符串插值
来源：http://dali.shanyushiyangtech.top/Article/details/gtgsaectdy.html

s"值: $b"
来源：http://dali.cqqwz.cn/Article/details/gtbbkofjri.html

[T54] Scala：集合映射
来源：http://dali.jinqigufen.top/Article/details/gtcrypinyt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.snrcjt.cn/Article/details/gtfcqjgdri.html

[T55] Scala：集合过滤
来源：http://dali.jinqigufen.top/Article/details/gtgfhwhdhr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sysykeji.top/Article/details/gtlotcyicu.html

[T56] Scala：样例类
来源：http://dali.jianghu66.top/Article/details/gtvwdyzsrz.html

case class User(name: String, age: Int)
来源：http://dali.xylfe.cn/Article/details/gtbabhjcbc.html

[T57] Scala：模式匹配
来源：http://dali.xinyue.icu/Article/details/gtgxntmqww.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jiagoushi.top/Article/details/gtamermvpj.html

[T58] Scala：函数定义
来源：http://dali.iojbl.cn/Article/details/gtbdvdyrjx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yvedp.cn/Article/details/gtbapfzyvm.html

[T59] Scala：循环
来源：http://dali.hywenlv.cn/Article/details/gtdjqjkqkt.html

for (i <- 1 to 10) println(i)
来源：http://dali.jlsjyb.cn/Article/details/gtxdblapok.html

[T60] Scala：折叠
来源：http://dali.316326.xyz/Article/details/gttcfvnuub.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhoulong.xyz/Article/details/gturbopcpm.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtrifkraas.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hnqzz.top/Article/details/gttnxoupmy.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtkfjdtrtf.html

[U01] Py：创建虚拟环境
来源：http://dali.bjfxy.top/Article/details/gtnmcmfdsj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.chenjidiqi.icu/Article/details/gtpceawsqu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhaomingkeji.xyz/Article/details/gtexjwxfep.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtenuzkrhr.html

[U03] Py：加载 .env 配置
来源：http://dali.aibaodan.cn/Article/details/gtfsbxynxw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.pengpengdd.cyou/Article/details/gtbejnjbxb.html

[U04] Py：变量调试打印
来源：http://dali.jianghu66.top/Article/details/gtbofcqbrq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hnqzz.top/Article/details/gttkqfxqjg.html

[U05] Py：列表去重且保序
来源：http://dali.ybcxt.top/Article/details/gtuyhqnuvk.html

list(dict.fromkeys(arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gthomshtyr.html

[U06] Py：合并两个字典
来源：http://dali.wangshuangyany.cn/Article/details/gtnppcixom.html

{**a, **b}
来源：http://dali.nanxinkj.top/Article/details/gtqggoyuqa.html

[U07] Py：反转字典键值
来源：http://dali.guowangkeji.top/Article/details/gtnrikikzr.html

{v: k for k, v in d.items()}
来源：http://dali.zhengqikj.top/Article/details/gtivtqrhgq.html

[U08] Py：展平二维列表
来源：http://dali.daria6918.cn/Article/details/gtjprwqmrd.html

[y for x in nested for y in x]
来源：http://dali.chenjidiqi.icu/Article/details/gtmiqtducm.html

[U09] Py：字典取最大值的键
来源：http://dali.sufxvd.cn/Article/details/gtbsaaougl.html

max(d, key=d.get)
来源：http://dali.smart0.xyz/Article/details/gtlveuuztd.html

[U10] Py：按值排序字典
来源：http://dali.smart0.xyz/Article/details/gtytyuqpnk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xinyue.icu/Article/details/gthzwenczc.html

[U11] Py：生成器表达式
来源：http://dali.meibo888.top/Article/details/gtkoipdcuk.html

(x * 2 for x in arr)
来源：http://dali.yj20258.top/Article/details/gtcqylbmcx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtplnmmtlh.html

Counter(arr).most_common(3)
来源：http://dali.dianchejie.cn/Article/details/gtwfteufkl.html

[U13] Py：固定长度队列
来源：http://dali.andypj.xyz/Article/details/gtnghyqqxt.html

deque(maxlen=10)
来源：http://dali.chenzaomai.com/Article/details/gtmnxspbfb.html

[U14] Py：分组收集到列表
来源：http://dali.gzhubu.top/Article/details/gtqttwaxfb.html

defaultdict(list)
来源：http://dali.sufxvd.cn/Article/details/gtmfuuqabr.html

[U15] Py：高精度计时
来源：http://dali.yuxming.cn/Article/details/gthwdxbvpr.html

t = time.perf_counter()
来源：http://dali.fzhhl.top/Article/details/gtmdivrmzm.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gtxvciytza.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinghuilouyu.cn/Article/details/gtboyhdcut.html


<!-- 参考信息 -->