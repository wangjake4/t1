代发 wailian999

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.svipenyu.cn/Article/details/gteyxpfdsm.html

[R72] 等待端口就绪
来源：http://dali.sufxvd.cn/Article/details/gtmfrqaazk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hfpthk.cn/Article/details/gtnkwkcwtg.html

[R73] 分割大日志
来源：http://dali.haohaochexian.top/Article/details/gtgkwaoegd.html

split -l 1000 big.log part_
来源：http://dali.nwbrower.top/Article/details/gtmggzmfys.html

[R74] 批量重命名
来源：http://dali.yueranfly.top/Article/details/gtbxubrstg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.wangdashe.top/Article/details/gtepzvhcpe.html

[R75] 导出环境变量
来源：http://dali.fengsongda.top/Article/details/gtjyvqgrzz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.daria6918.cn/Article/details/gtnpvcovvr.html

[R76] 使用临时文件
来源：http://dali.hammf.cn/Article/details/gtdkgtqujo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gtylpbgwxg.html

[R77] 读取用户输入
来源：http://dali.jinghuilouyu.cn/Article/details/gtywzqwrau.html

read -rp "请输入: " ans
来源：http://dali.zhengqikj.top/Article/details/gthqfkskrz.html

[R78] 交互式菜单
来源：http://dali.yongpay.top/Article/details/gtzzdngvcl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.kuanghao11.cn/Article/details/gteffidolw.html

[R79] 解析命令行选项
来源：http://dali.pengpengdd.cyou/Article/details/gtnbehbtpt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hysaishi.cn/Article/details/gtuwotxceq.html

[R80] 查看脚本执行耗时
来源：http://dali.0kj1m.cn/Article/details/gtkqorzdjk.html

time ./run.sh
来源：http://dali.zhongyouzk.top/Article/details/gtbxewdqas.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtdnwlvvwr.html

S. C / C++ 专题
来源：http://dali.jqgufenzy.top/Article/details/gtmuzvjpvz.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtptjfceje.html

[S01] C：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtumncsbtl.html

#include <stdio.h>
来源：http://dali.shanyushiyangtech.top/Article/details/gtzuvuoxvj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hongshengwenyu.top/Article/details/gtqynlvzrd.html

[S02] C：变量与格式化输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkjqexucb.html

int a = 10; printf("%d\n", a);
来源：http://dali.daria6918.cn/Article/details/gtwiyxbvup.html

[S03] C：读入整数
来源：http://dali.jqgufenzy.top/Article/details/gtgnznypio.html

int x; scanf("%d", &x);
来源：http://dali.zhengqikj.top/Article/details/gtylooensq.html

[S04] C：字符串复制
来源：http://dali.shangyingyoupin.top/Article/details/gtlpdtoudr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zdqjudy.top/Article/details/gtqyfakrkx.html

[S05] C：字符串长度
来源：http://dali.c1oappe.top/Article/details/gtzikldnwf.html

strlen(s)
来源：http://dali.ehwqpu.com/Article/details/gtvnfbnvhq.html

[S06] C：字符串比较
来源：http://dali.9152youxi.cn/Article/details/gtmytepepw.html

strcmp(a, b) == 0
来源：http://dali.xuanzx.com/Article/details/gttwumpvlk.html

[S07] C：数组遍历求和
来源：http://dali.zhongyouzk.top/Article/details/gtdrqughtm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jqgfzy.top/Article/details/gtwdunmmul.html

[S08] C：动态内存分配与释放
来源：http://dali.shzxlz.cn/Article/details/gtgirbbvqh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hfpthk.cn/Article/details/gtbccidirs.html

[S09] C：结构体定义与初始化
来源：http://dali.feifeiyinyue.top/Article/details/gtbubtitae.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuiyfzpqn.html

[S10] C：指针与解引用
来源：http://dali.nwbrower.top/Article/details/gtpykhsxkp.html

int *p = &a;  *p = 5;
来源：http://dali.316326.xyz/Article/details/gtfqyodxiw.html

[S11] C：逐行读文件
来源：http://dali.bjfxy.top/Article/details/gtaddjohrr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gotoacloud.top/Article/details/gtjasyzzjg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xziqi.cn/Article/details/gtwsjrgwxa.html

fclose(f);
来源：http://dali.sxryk.cn/Article/details/gtuqlfzhmb.html

[S12] C：写文件
来源：http://dali.chenzaomai.com/Article/details/gtwredzzus.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xziqi.cn/Article/details/gtqnqovjxm.html

[S13] C：宏定义
来源：http://dali.hysaishi.cn/Article/details/gtlvvqezka.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinghuilouyu.cn/Article/details/gtynpamdnn.html

[S14] C：枚举
来源：http://dali.chenjidiqi.icu/Article/details/gtshiiwjpp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.haohaochexian.top/Article/details/gtqwhjcumk.html

[S15] C：类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpdfkwfnn.html

(double) a / b
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhjupucf.html

[S16] C：位操作置位
来源：http://dali.sweek.top/Article/details/gtximvgcjk.html

x |= (1 << 3);
来源：http://dali.tianlin.xyz/Article/details/gthlyhjipv.html

[S17] C：安全拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gtpmiebgdi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jqgfzy.top/Article/details/gthdvundxi.html

[S18] C：命令行参数
来源：http://dali.hfpthk.cn/Article/details/gtlfyuhzsc.html

int main(int argc, char **argv)
来源：http://dali.shzxlz.cn/Article/details/gtkxgjvieq.html

[S19] C：快速排序
来源：http://dali.sweek.top/Article/details/gtfuzrrsuz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhixingplan.top/Article/details/gtrwjmlnlo.html

[S20] C：二分查找
来源：http://dali.bjfxy.top/Article/details/gtvipbxsqs.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gtmiopozne.html

[S21] C：字符类别判断
来源：http://dali.zhoulong.xyz/Article/details/gtpcikxcar.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinqigufen.top/Article/details/gtwrhqlvpg.html

[S22] C：字符串转数字
来源：http://dali.jinghuilouyu.cn/Article/details/gtjtbdegpf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj202588.top/Article/details/gtwrfndpfb.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gtzjwclugh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ydzc1.top/Article/details/gthhsmffft.html

[S24] C：获取本地时间
来源：http://dali.jqgfzy.top/Article/details/gtcjxxavtv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hywenlv.cn/Article/details/gtcxyarsdo.html

[S25] C：内存拷贝
来源：http://dali.xuanzx.com/Article/details/gtqaingane.html

memcpy(dst, src, n);
来源：http://dali.ppjwa.cn/Article/details/gtmmhfbvvd.html

[S26] C：内存清零
来源：http://dali.jinqigfzy.top/Article/details/gtsoxabsmq.html

memset(a, 0, sizeof a);
来源：http://dali.yonumen.top/Article/details/gtjgprysbp.html

[S27] C：定义常量
来源：http://dali.zhixingplan.top/Article/details/gtcwwkzfei.html

const double PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtuuotasfy.html

[S28] C：静态变量
来源：http://dali.mhx1999.top/Article/details/gtjbhahhxj.html

static int counter = 0;
来源：http://dali.kuanghao11.cn/Article/details/gtuaevrhih.html

[S29] C：变参函数
来源：http://dali.hfpthk.cn/Article/details/gtubrbbysb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.mhx1999.top/Article/details/gtkkklydww.html

[S30] C：头文件保护
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpincben.html

#ifndef X_H
来源：http://dali.gogol.net.cn/Article/details/gtswhwqtxc.html

#define X_H
来源：http://dali.redwolf501.top/Article/details/gtajbkczif.html

#endif
来源：http://dali.cucudq.cn/Article/details/gtmnphktvk.html

[S31] C++：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfoakfkpr.html

#include <iostream>
来源：http://dali.zycfv.cn/Article/details/gtdmqfmkog.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xuanzx.com/Article/details/gtuxsevluz.html

[S32] C++：字符串
来源：http://dali.svipenyu.cn/Article/details/gtwonermcb.html

std::string s = "hi";  s += "!";
来源：http://dali.sysykeji.top/Article/details/gtzemmweqa.html

[S33] C++：vector 增删
来源：http://dali.yongpay.top/Article/details/gtdzvaidtw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhixingplan.top/Article/details/gtuhalhtss.html

[S34] C++：遍历 vector
来源：http://dali.zhongyouzk.top/Article/details/gttmpsahrf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinqigfzy.top/Article/details/gtdtjqgytp.html

[S35] C++：map
来源：http://dali.yangfankeji.com/Article/details/gtrktnszsk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gtjdktcemh.html

[S36] C++：unordered_map
来源：http://dali.havefunace.top/Article/details/gtmwsytsuj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zycfv.cn/Article/details/gtyrqjrfca.html

[S37] C++：set
来源：http://dali.haohaochexian.top/Article/details/gtanbhxdqs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.dianchejie.cn/Article/details/gtohvdxcxi.html

[S38] C++：排序
来源：http://dali.bjfxy.top/Article/details/gticfafqmo.html

std::sort(v.begin(), v.end());
来源：http://dali.jinqigufen.top/Article/details/gtehtwbyxf.html

[S39] C++：自定义比较器排序
来源：http://dali.xinyue.icu/Article/details/gtomyzkdmw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shangyingyoupin.top/Article/details/gtvmocrosm.html

[S40] C++：查找元素
来源：http://dali.cucudq.cn/Article/details/gtjbikmksv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhongyouzk.top/Article/details/gtfbhpneqm.html

[S41] C++：类与构造函数
来源：http://dali.cashguo.top/Article/details/gthyyhfpjs.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtflqudzvw.html

[S42] C++：继承与虚函数
来源：http://dali.jianghu66.top/Article/details/gtsffuoufe.html

class B : public Base { public: void f() override {} };
来源：http://dali.c1oappe.top/Article/details/gttkygsypr.html

[S43] C++：智能指针
来源：http://dali.sxryk.cn/Article/details/gtmyqtqnzi.html

auto p = std::make_unique<int>(5);
来源：http://dali.gogol.net.cn/Article/details/gtltgrnlyv.html

[S44] C++：引用传参
来源：http://dali.yj202588.top/Article/details/gtftjbnmyt.html

void inc(int &x) { ++x; }
来源：http://dali.sxryk.cn/Article/details/gtpelwquwh.html

[S45] C++：lambda
来源：http://dali.jinghuilouyu.cn/Article/details/gtfcjdfnnx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fzhhl.top/Article/details/gtadtlaxri.html

[S46] C++：函数模板
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvgzwognf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmjhhdpm.html

[S47] C++：结构化绑定遍历
来源：http://dali.daria6918.cn/Article/details/gtdfqfjglg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.pengpengdd.cyou/Article/details/gtglsqhztm.html

[S48] C++：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gtlaqifqjr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jqgfzy.top/Article/details/gtrdyghwpe.html

while (std::getline(in, line)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gtcmvlllni.html

[S49] C++：写文件
来源：http://dali.zhiwuduotai.top/Article/details/gtsrzksbpu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinqigfzy.top/Article/details/gtrcdqnizb.html

[S50] C++：格式化数字
来源：http://dali.hnxiangtu.top/Article/details/gtulgzlyeo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ydzc1.top/Article/details/gthstebehs.html

[S51] C++：显式类型转换
来源：http://dali.jlsjyb.cn/Article/details/gtjavsaouz.html

static_cast<double>(a) / b
来源：http://dali.hysaishi.cn/Article/details/gtkddvjlgz.html

[S52] C++：const 与 noexcept
来源：http://dali.cdnleiting.top/Article/details/gtzfbsdynl.html

int size() const noexcept { return n_; }
来源：http://dali.chenlongwang.top/Article/details/gtarqatagc.html

[S53] C++：移动语义
来源：http://dali.gogol.net.cn/Article/details/gtphrizcfp.html

std::vector<int> w = std::move(v);
来源：http://dali.jinqigufen.top/Article/details/gtbotqfsvv.html

[S54] C++：异常处理
来源：http://dali.snrcjt.cn/Article/details/gtdwchjhim.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xinyue.icu/Article/details/gtagbodojq.html

[S55] C++：结构化绑定
来源：http://dali.sweek.top/Article/details/gtoitqlnxc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hammf.cn/Article/details/gtrbgoxvio.html

[S56] C++：optional
来源：http://dali.yj20258888.top/Article/details/gtckkuvthe.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shangyingyoupin.top/Article/details/gtvrtlfwfl.html

[S57] C++：编译期常量
来源：http://dali.sufxvd.cn/Article/details/gtababpcyd.html

constexpr int N = 10;
来源：http://dali.smart0.xyz/Article/details/gtswpbvqea.html

[S58] C++：命名空间
来源：http://dali.cheryme.top/Article/details/gtjkbrkryh.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenlongwang.top/Article/details/gtlkxsjjzm.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gtxtehansv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sxryk.cn/Article/details/gtzlnphwzr.html

[S60] C++：遍历并删除元素
来源：http://dali.fengsongda.top/Article/details/gtjvdfwyrs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yanxiufei.cn/Article/details/gtryrvusmg.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtbaqzlhbz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cheryme.top/Article/details/gtabsoylli.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gttgsivhey.html

[T01] Kotlin：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtywhqzhmo.html

println("Hello")
来源：http://dali.yangfankeji.com/Article/details/gtknggbryk.html

[T02] Kotlin：变量
来源：http://dali.hnqzz.top/Article/details/gtvmlfsyqf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.pycfn.com/Article/details/gtzuxrtdie.html

[T03] Kotlin：字符串模板
来源：http://dali.zhiwuduotai.top/Article/details/gtbzbvkfzz.html

"值: $b"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnnrshdgq.html

[T04] Kotlin：空安全
来源：http://dali.iojbl.cn/Article/details/gtmrjaomtc.html

val n: String? = null;  n?.length
来源：http://dali.fengsongda.top/Article/details/gtplshepcl.html

[T05] Kotlin：when 表达式
来源：http://dali.jianghu66.top/Article/details/gtducpwdrq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.9152youxi.cn/Article/details/gtdadkmvej.html

[T06] Kotlin：集合映射
来源：http://dali.cheryme.top/Article/details/gtvjundsyb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hfpthk.cn/Article/details/gtvsushzyn.html

[T07] Kotlin：集合过滤
来源：http://dali.dianchejie.cn/Article/details/gtoaevhmxv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuanzhike.top/Article/details/gtrnxnxxlo.html

[T08] Kotlin：数据类
来源：http://dali.hysaishi.cn/Article/details/gtsalxvttm.html

data class User(val name: String, val age: Int)
来源：http://dali.sweek.top/Article/details/gtpsdktqqn.html

[T09] Kotlin：扩展函数
来源：http://dali.cucudq.cn/Article/details/gtungvhenv.html

fun String.exclaim() = this + "!"
来源：http://dali.cqqwz.cn/Article/details/gtsubmvvnu.html

[T10] Kotlin：默认参数
来源：http://dali.pengpengdd.cyou/Article/details/gtqqcsirly.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ehwqpu.com/Article/details/gtcysfedvy.html

[T11] Kotlin：协程
来源：http://dali.jiagoushi.top/Article/details/gtbfgyiqwr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zycfv.cn/Article/details/gteoakwrym.html

[T12] Kotlin：解构声明
来源：http://dali.dashuyun.cn/Article/details/gtxqvzuqqu.html

val (a, b) = Pair(1, 2)
来源：http://dali.shuidangran.top/Article/details/gtemsuxjol.html

[T13] Kotlin：只读 Map
来源：http://dali.mhx1999.top/Article/details/gtdfxkepej.html

val m = mapOf("a" to 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtclbmlbls.html

[T14] Kotlin：循环
来源：http://dali.dashuyun.cn/Article/details/gtsdiarbis.html

for (i in 1..10) println(i)
来源：http://dali.jiagoushi.top/Article/details/gtwjgcsgnp.html

[T15] Kotlin：接口
来源：http://dali.aizwys.cn/Article/details/gtgfmdasym.html

interface Shape { fun area(): Double }
来源：http://dali.shuidangran.top/Article/details/gtnvmvadot.html

[T16] Swift：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtxvczdocg.html

print("Hello")
来源：http://dali.wangdashe.top/Article/details/gtlzxhqnzv.html

[T17] Swift：变量与常量
来源：http://dali.yj20258.top/Article/details/gtnzrvcxky.html

var a = 1;  let b = 2
来源：http://dali.iojbl.cn/Article/details/gtiubeufsb.html

[T18] Swift：字符串插值
来源：http://dali.daxiang520.top/Article/details/gtcmjvursm.html

"值: \(b)"
来源：http://dali.guannengcc.top/Article/details/gtyowgxclt.html

[T19] Swift：可选绑定
来源：http://dali.hysaishi.cn/Article/details/gtmibctmit.html

if let n = opt { print(n) }
来源：http://dali.zhoulong.xyz/Article/details/gthwrryszu.html

[T20] Swift：数组操作
来源：http://dali.316326.xyz/Article/details/gtexbxhcxp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.dianchejie.cn/Article/details/gtyjacsewj.html

[T21] Swift：遍历
来源：http://dali.jqgufenzy.top/Article/details/gtkggqxtfx.html

for x in a { print(x) }
来源：http://dali.andypj.xyz/Article/details/gtpanffzbv.html

[T22] Swift：字典
来源：http://dali.dashuyun.cn/Article/details/gtqwuuqpnc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yueranfly.top/Article/details/gtetkyjhhg.html

[T23] Swift：函数
来源：http://dali.cucudq.cn/Article/details/gtktfklhjw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hfpthk.cn/Article/details/gtppzhrtlu.html

[T24] Swift：闭包
来源：http://dali.chenzaomai.com/Article/details/gtgxivqxit.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gzhubu.top/Article/details/gtsepzxbwz.html

[T25] Swift：结构体
来源：http://dali.nanxuanxn.top/Article/details/gtivsonzii.html

struct P { var x: Int }
来源：http://dali.tian-w.cn/Article/details/gtkxlibucx.html

[T26] Swift：类与重写
来源：http://dali.xinyue.icu/Article/details/gtvgwqaynw.html

class A: Base { override func f() {} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtncujpebz.html

[T27] Swift：错误处理
来源：http://dali.ydzc1.top/Article/details/gtbwachupu.html

do { try f() } catch { print(error) }
来源：http://dali.xinyue.icu/Article/details/gtoabnqgmn.html

[T28] Swift：枚举
来源：http://dali.snrcjt.cn/Article/details/gtyzoazttu.html

enum Color { case red, green }
来源：http://dali.ybcxt.top/Article/details/gtsnbecogq.html

[T29] Swift：guard 提前返回
来源：http://dali.shanyushiyangtech.top/Article/details/gtsfiubsav.html

guard let x = opt else { return }
来源：http://dali.redwolf501.top/Article/details/gtjjkngznq.html

[T30] Swift：协议
来源：http://dali.yangfankeji.com/Article/details/gtizrqrsqa.html

protocol Shape { func area() -> Double }
来源：http://dali.xziqi.cn/Article/details/gtlqikqxef.html

[T31] Lua：Hello World
来源：http://dali.sweek.top/Article/details/gttccfpzdj.html

print("Hello")
来源：http://dali.cdnleiting.top/Article/details/gtinchghyd.html

[T32] Lua：局部变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkyuhgpku.html

local a = 1
来源：http://dali.jyoumei.cn/Article/details/gtsqusksjw.html

[T33] Lua：表（数组）
来源：http://dali.yonumen.top/Article/details/gtzrozsytf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shanyushiyangtech.top/Article/details/gtvnmabbif.html

[T34] Lua：遍历表
来源：http://dali.jiagoushi.top/Article/details/gtlidfdzib.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.wangshuangyany.cn/Article/details/gtvcevasnv.html

[T35] Lua：字典表
来源：http://dali.andypj.xyz/Article/details/gtujnqcsuq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.dashuyun.cn/Article/details/gtemunwqxq.html

[T36] Lua：函数
来源：http://dali.quarkkingdee.top/Article/details/gtmoeclrki.html

function add(a, b) return a + b end
来源：http://dali.tian-w.cn/Article/details/gtjbjzgclg.html

[T37] Lua：字符串拼接
来源：http://dali.chenzaomai.com/Article/details/gtiwnbadtr.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gtoemrbzsk.html

[T38] Lua：条件
来源：http://dali.jianghu66.top/Article/details/gtduzrltkp.html

if x > 0 then print("正") end
来源：http://dali.yj20258.top/Article/details/gtltqtgosf.html

[T39] Lua：模式匹配
来源：http://dali.sxryk.cn/Article/details/gtcdmubsdm.html

string.find(s, "%d+")
来源：http://dali.jqgufenzy.top/Article/details/gtreemyoch.html

[T40] Lua：元表
来源：http://dali.jqgfzy.top/Article/details/gtemquwebi.html

setmetatable({}, { __index = base })
来源：http://dali.sweek.top/Article/details/gtqonjwzqo.html

[T41] Perl：Hello World
来源：http://dali.hysaishi.cn/Article/details/gteyyohghh.html

print "Hello\n";
来源：http://dali.jinqigufen.top/Article/details/gtisotlduz.html

[T42] Perl：变量类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtoettzeuj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jqgfzy.top/Article/details/gtbkqaixqj.html

[T43] Perl：字符串插值
来源：http://dali.zdqjudy.top/Article/details/gtnvcepkzo.html

"值: $a"
来源：http://dali.haohaochexian.top/Article/details/gtplvrmcnn.html

[T44] Perl：条件
来源：http://dali.yonumen.top/Article/details/gtomfirscu.html

if ($a > 0) { print "正"; }
来源：http://dali.zdqjudy.top/Article/details/gtrkakuvet.html

[T45] Perl：数组遍历
来源：http://dali.hysaishi.cn/Article/details/gtaiwbvorn.html

for my $x (@arr) { print $x; }
来源：http://dali.bjfxy.top/Article/details/gtkeibtfor.html

[T46] Perl：哈希操作
来源：http://dali.jinqigfzy.top/Article/details/gtvzvjzjqm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xuetiantiany.cn/Article/details/gttltbjohz.html

[T47] Perl：正则捕获
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvqptafom.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yongpay.top/Article/details/gtbsrzvtrf.html

[T48] Perl：正则替换
来源：http://dali.daxiang520.top/Article/details/gtlemchqvn.html

$s =~ s/old/new/g;
来源：http://dali.jqgfzy.top/Article/details/gtnaxsdewv.html

[T49] Perl：函数
来源：http://dali.hnqzz.top/Article/details/gtugpcspsf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gtwpulozjq.html

[T50] Perl：逐行读文件
来源：http://dali.yj20258888.top/Article/details/gtbutjqbas.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ehwqpu.com/Article/details/gtbuojmnkq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.aibaodan.cn/Article/details/gthvfrvkqc.html

[T51] Scala：Hello World
来源：http://dali.cheryme.top/Article/details/gtwlziabeu.html

println("Hello")
来源：http://dali.ybcxt.top/Article/details/gtqysovhsr.html

[T52] Scala：变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtysaimarb.html

val a = 1;  var b = 2
来源：http://dali.bjfxy.top/Article/details/gtwstuyxcj.html

[T53] Scala：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gttnuiqdab.html

s"值: $b"
来源：http://dali.zhengqikj.top/Article/details/gtpbttcvrk.html

[T54] Scala：集合映射
来源：http://dali.daxiang520.top/Article/details/gtkxmhnfeo.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.tanke756.top/Article/details/gtxhlmuupg.html

[T55] Scala：集合过滤
来源：http://dali.ehwqpu.com/Article/details/gttzeqiozb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtvmerohah.html

[T56] Scala：样例类
来源：http://dali.quarkkingdee.top/Article/details/gtxpmcigfr.html

case class User(name: String, age: Int)
来源：http://dali.pycfn.com/Article/details/gtgscyaqew.html

[T57] Scala：模式匹配
来源：http://dali.zycfv.cn/Article/details/gtichccsti.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jyoumei.cn/Article/details/gthrhpmqbv.html

[T58] Scala：函数定义
来源：http://dali.aibaodan.cn/Article/details/gtiurefemc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhoulong.xyz/Article/details/gtikyzrmgn.html

[T59] Scala：循环
来源：http://dali.zycfv.cn/Article/details/gtslgdueno.html

for (i <- 1 to 10) println(i)
来源：http://dali.hnqzz.top/Article/details/gtoczcegmm.html

[T60] Scala：折叠
来源：http://dali.gogol.net.cn/Article/details/gtiqmdmvmm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.iojbl.cn/Article/details/gtgmoxlftb.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gthjfuspce.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.aibaodan.cn/Article/details/gtbwukmque.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtljtamfaa.html

[U01] Py：创建虚拟环境
来源：http://dali.yueranfly.top/Article/details/gtddrfgsis.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yvedp.cn/Article/details/gtkhpspojo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.tianlin.xyz/Article/details/gtpapvvqvz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtysrmcayt.html

[U03] Py：加载 .env 配置
来源：http://dali.tanke756.top/Article/details/gtllkkmasb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xziqi.cn/Article/details/gtabhuxwsc.html

[U04] Py：变量调试打印
来源：http://dali.jqgufenzy.top/Article/details/gtearbmelp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.wangshuangyany.cn/Article/details/gtshpnjwlf.html

[U05] Py：列表去重且保序
来源：http://dali.nanxuanxn.top/Article/details/gtrpyrdwib.html

list(dict.fromkeys(arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrnboforb.html

[U06] Py：合并两个字典
来源：http://dali.jqgufenzy.top/Article/details/gtivxtadne.html

{**a, **b}
来源：http://dali.iojbl.cn/Article/details/gtuoknanyd.html

[U07] Py：反转字典键值
来源：http://dali.cucudq.cn/Article/details/gtnwzodawh.html

{v: k for k, v in d.items()}
来源：http://dali.andypj.xyz/Article/details/gtswdgzmyp.html

[U08] Py：展平二维列表
来源：http://dali.shanyushiyangtech.top/Article/details/gthdloputl.html

[y for x in nested for y in x]
来源：http://dali.shzxlz.cn/Article/details/gtdckzrcmg.html

[U09] Py：字典取最大值的键
来源：http://dali.zycfv.cn/Article/details/gtigrdtlwn.html

max(d, key=d.get)
来源：http://dali.ppjwa.cn/Article/details/gtfoqsmfkc.html

[U10] Py：按值排序字典
来源：http://dali.hongshengwenyu.top/Article/details/gtezzgrhpp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.pycfn.com/Article/details/gttwubiqnq.html

[U11] Py：生成器表达式
来源：http://dali.tanke756.top/Article/details/gtzdfhwgzt.html

(x * 2 for x in arr)
来源：http://dali.pycfn.com/Article/details/gtvkrmesgr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xinyue.icu/Article/details/gtgimldxxm.html

Counter(arr).most_common(3)
来源：http://dali.snrcjt.cn/Article/details/gtmzplaxuz.html


<!-- 参考信息 -->