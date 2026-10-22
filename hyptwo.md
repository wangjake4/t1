代发 wailian999

split -l 1000 big.log part_
来源：http://dali.zhengqikj.top/Article/details/gtofbbghey.html

[R74] 批量重命名
来源：http://dali.yj202588.top/Article/details/gtesvukpjz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxxlpnmp.html

[R75] 导出环境变量
来源：http://dali.hammf.cn/Article/details/gtotqncztm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.svipenyu.cn/Article/details/gtglawhpik.html

[R76] 使用临时文件
来源：http://dali.smart0.xyz/Article/details/gtrwtstntc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xylfe.cn/Article/details/gthherbucn.html

[R77] 读取用户输入
来源：http://dali.xziqi.cn/Article/details/gtcbxvlqvn.html

read -rp "请输入: " ans
来源：http://dali.yangfankeji.com/Article/details/gtnzhcvoed.html

[R78] 交互式菜单
来源：http://dali.hammf.cn/Article/details/gtjqvemlee.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhixingplan.top/Article/details/gtwwrqzaok.html

[R79] 解析命令行选项
来源：http://dali.cqqwz.cn/Article/details/gtaauvhqmr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cheryme.top/Article/details/gtiupiunbg.html

[R80] 查看脚本执行耗时
来源：http://dali.chenzaomai.com/Article/details/gtjviwpguz.html

time ./run.sh
来源：http://dali.daria6918.cn/Article/details/gtwzmphkzp.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtblwizuvj.html

S. C / C++ 专题
来源：http://dali.ehwqpu.com/Article/details/gtegghbzcq.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtpgjojzhc.html

[S01] C：Hello World
来源：http://dali.yueranfly.top/Article/details/gttroyqirv.html

#include <stdio.h>
来源：http://dali.jinqigufen.top/Article/details/gtddaehtpc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tianlin.xyz/Article/details/gtukccsoug.html

[S02] C：变量与格式化输出
来源：http://dali.ybcxt.top/Article/details/gtlyfxtbfn.html

int a = 10; printf("%d\n", a);
来源：http://dali.xinyue.icu/Article/details/gtkcckommw.html

[S03] C：读入整数
来源：http://dali.cucudq.cn/Article/details/gtqawxgvkf.html

int x; scanf("%d", &x);
来源：http://dali.yongpay.top/Article/details/gthzdybhaf.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gtehmdgpfb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gtitldmzkf.html

[S05] C：字符串长度
来源：http://dali.zdqjudy.top/Article/details/gtaccbpusr.html

strlen(s)
来源：http://dali.yueranfly.top/Article/details/gtpkkvzate.html

[S06] C：字符串比较
来源：http://dali.zhengqikj.top/Article/details/gtjasdszas.html

strcmp(a, b) == 0
来源：http://dali.yonumen.top/Article/details/gtvwkartzk.html

[S07] C：数组遍历求和
来源：http://dali.gogol.net.cn/Article/details/gtnnvszixd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.fengsongda.top/Article/details/gtgcxvwmtt.html

[S08] C：动态内存分配与释放
来源：http://dali.shuidangran.top/Article/details/gtyhprpjau.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.guowangkeji.top/Article/details/gtqccpwxvm.html

[S09] C：结构体定义与初始化
来源：http://dali.0kj1m.cn/Article/details/gtpeqtceyy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.wangdashe.top/Article/details/gtjtrybfil.html

[S10] C：指针与解引用
来源：http://dali.hfpthk.cn/Article/details/gtpdowgaan.html

int *p = &a;  *p = 5;
来源：http://dali.yangfankeji.com/Article/details/gtzkegwaif.html

[S11] C：逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gtnkfsalza.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinqigfzy.top/Article/details/gtcdbpsvjj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenjidiqi.icu/Article/details/gtmxacxmxb.html

fclose(f);
来源：http://dali.cqqwz.cn/Article/details/gtbtutwgjg.html

[S12] C：写文件
来源：http://dali.zycfv.cn/Article/details/gtkfkbwpzb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jlsjyb.cn/Article/details/gtkmyiensk.html

[S13] C：宏定义
来源：http://dali.chenjidiqi.icu/Article/details/gtvfyrpefo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shanyushiyangtech.top/Article/details/gtljkftrxx.html

[S14] C：枚举
来源：http://dali.aibaodan.cn/Article/details/gtejyxiceu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.meibo888.top/Article/details/gtwesbciwl.html

[S15] C：类型转换
来源：http://dali.sufxvd.cn/Article/details/gtntvghhyd.html

(double) a / b
来源：http://dali.daria6918.cn/Article/details/gtalgmdggx.html

[S16] C：位操作置位
来源：http://dali.nanxuanxn.top/Article/details/gtwpyzirxr.html

x |= (1 << 3);
来源：http://dali.jinqigfzy.top/Article/details/gtkyfvyiok.html

[S17] C：安全拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtffugzcwp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.meibo888.top/Article/details/gthepyubtg.html

[S18] C：命令行参数
来源：http://dali.redwolf501.top/Article/details/gtoqscumdk.html

int main(int argc, char **argv)
来源：http://dali.yongpay.top/Article/details/gthlwrdnpp.html

[S19] C：快速排序
来源：http://dali.fzhhl.top/Article/details/gtolgqquki.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cucudq.cn/Article/details/gtdpzaclog.html

[S20] C：二分查找
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvvtsplcz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.smart0.xyz/Article/details/gtoqancsft.html

[S21] C：字符类别判断
来源：http://dali.hammf.cn/Article/details/gtixikngju.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyieoyizs.html

[S22] C：字符串转数字
来源：http://dali.ivvv.top/Article/details/gtejzjyuxl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinghuilouyu.cn/Article/details/gtuxoffpnm.html

[S23] C：随机数
来源：http://dali.shangyingyoupin.top/Article/details/gtujfwyfhk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.guannengcc.top/Article/details/gtiwvrdjem.html

[S24] C：获取本地时间
来源：http://dali.hywenlv.cn/Article/details/gtjxrsfjgp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.dianchejie.cn/Article/details/gtebwnetfl.html

[S25] C：内存拷贝
来源：http://dali.sysykeji.top/Article/details/gtkmkfdyek.html

memcpy(dst, src, n);
来源：http://dali.xinyue.icu/Article/details/gtcbgqnbja.html

[S26] C：内存清零
来源：http://dali.snrcjt.cn/Article/details/gtccswsxkl.html

memset(a, 0, sizeof a);
来源：http://dali.mhx1999.top/Article/details/gtgyxhkird.html

[S27] C：定义常量
来源：http://dali.sysykeji.top/Article/details/gtcnnbhhyg.html

const double PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtltezvjbz.html

[S28] C：静态变量
来源：http://dali.gaohongyu789.top/Article/details/gtfhjhwyem.html

static int counter = 0;
来源：http://dali.xuetiantiany.cn/Article/details/gtehzyyika.html

[S29] C：变参函数
来源：http://dali.sysykeji.top/Article/details/gtisqekenw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.pengpengdd.cyou/Article/details/gtqvnhdtha.html

[S30] C：头文件保护
来源：http://dali.yj20258888.top/Article/details/gtcdurnjwo.html

#ifndef X_H
来源：http://dali.daxiang520.top/Article/details/gtgbflrorq.html

#define X_H
来源：http://dali.hnxiangtu.top/Article/details/gtyuiyhqpi.html

#endif
来源：http://dali.c1oappe.top/Article/details/gtjvdmhsdd.html

[S31] C++：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtsahjlygc.html

#include <iostream>
来源：http://dali.nanxinkj.top/Article/details/gtavaereid.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.snrcjt.cn/Article/details/gtyeqahmri.html

[S32] C++：字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuxyvlzwl.html

std::string s = "hi";  s += "!";
来源：http://dali.andypj.xyz/Article/details/gtidltrqbo.html

[S33] C++：vector 增删
来源：http://dali.tanke756.top/Article/details/gtltnlnkni.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtzdxktcls.html

[S34] C++：遍历 vector
来源：http://dali.jqgfzy.top/Article/details/gtnurtahaz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ydzc1.top/Article/details/gtxmsecvgb.html

[S35] C++：map
来源：http://dali.guowangkeji.top/Article/details/gtygrqqnmp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.mhx1999.top/Article/details/gtwcsnmumn.html

[S36] C++：unordered_map
来源：http://dali.wangdashe.top/Article/details/gtjliztfjh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtpwhcvzmy.html

[S37] C++：set
来源：http://dali.andypj.xyz/Article/details/gtzftblszu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.andypj.xyz/Article/details/gtetyuctvp.html

[S38] C++：排序
来源：http://dali.0kj1m.cn/Article/details/gtlhnxvgaj.html

std::sort(v.begin(), v.end());
来源：http://dali.redwolf501.top/Article/details/gthomuqsur.html

[S39] C++：自定义比较器排序
来源：http://dali.aibaodan.cn/Article/details/gtwljueotj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gtrxektrif.html

[S40] C++：查找元素
来源：http://dali.iojbl.cn/Article/details/gtngcyjxpr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtweixcjlw.html

[S41] C++：类与构造函数
来源：http://dali.cdnleiting.top/Article/details/gtldxpozdn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.bjfxy.top/Article/details/gtwdjzteff.html

[S42] C++：继承与虚函数
来源：http://dali.guowangkeji.top/Article/details/gtkcotdnie.html

class B : public Base { public: void f() override {} };
来源：http://dali.gotoacloud.top/Article/details/gtloktqefs.html

[S43] C++：智能指针
来源：http://dali.jinghuilouyu.cn/Article/details/gtqvmcwxnm.html

auto p = std::make_unique<int>(5);
来源：http://dali.xylfe.cn/Article/details/gtzrphavxv.html

[S44] C++：引用传参
来源：http://dali.cqqwz.cn/Article/details/gtvppxlcvt.html

void inc(int &x) { ++x; }
来源：http://dali.cheryme.top/Article/details/gtvlrtirbp.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gttfvjafcj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xuetiantiany.cn/Article/details/gtirfyfnwq.html

[S46] C++：函数模板
来源：http://dali.birdmap.top/Article/details/gtxajubche.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtaddihwuq.html

[S47] C++：结构化绑定遍历
来源：http://dali.chenzaomai.com/Article/details/gtywsnqcfk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.iojbl.cn/Article/details/gtyrgabvdg.html

[S48] C++：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gttekgdfss.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sysykeji.top/Article/details/gttbibpyzc.html

while (std::getline(in, line)) { }
来源：http://dali.c1oappe.top/Article/details/gtouulmicf.html

[S49] C++：写文件
来源：http://dali.ybcxt.top/Article/details/gtvryhitmt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hfpthk.cn/Article/details/gtlnznsicr.html

[S50] C++：格式化数字
来源：http://dali.jinghuilouyu.cn/Article/details/gtngxktdbe.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gtfihxbccf.html

[S51] C++：显式类型转换
来源：http://dali.yuanzhike.top/Article/details/gtyubtvjmq.html

static_cast<double>(a) / b
来源：http://dali.cqqwz.cn/Article/details/gtqpovbrfh.html

[S52] C++：const 与 noexcept
来源：http://dali.pengpengdd.cyou/Article/details/gtdmgpfexl.html

int size() const noexcept { return n_; }
来源：http://dali.pengpengdd.cyou/Article/details/gtrioavzbg.html

[S53] C++：移动语义
来源：http://dali.jlsjyb.cn/Article/details/gtjkssrcuj.html

std::vector<int> w = std::move(v);
来源：http://dali.birdmap.top/Article/details/gtdlxgdkuo.html

[S54] C++：异常处理
来源：http://dali.aizwys.cn/Article/details/gtzfufmgqg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.quarkkingdee.top/Article/details/gtgrysmhdt.html

[S55] C++：结构化绑定
来源：http://dali.hywenlv.cn/Article/details/gtrycmdzeq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jlsjyb.cn/Article/details/gtgprzfkdj.html

[S56] C++：optional
来源：http://dali.gaohongyu789.top/Article/details/gttgedjsnn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gogol.net.cn/Article/details/gtvzoqtktv.html

[S57] C++：编译期常量
来源：http://dali.jinqigfzy.top/Article/details/gtoasjeicm.html

constexpr int N = 10;
来源：http://dali.daxiang520.top/Article/details/gtzryooujn.html

[S58] C++：命名空间
来源：http://dali.hnxiangtu.top/Article/details/gtfjjqxevi.html

namespace ns { int f() { return 1; } }
来源：http://dali.cucudq.cn/Article/details/gtdqgipamd.html

[S59] C++：静态断言
来源：http://dali.ivvv.top/Article/details/gtwhdsstah.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gotoacloud.top/Article/details/gtjlwfgqsi.html

[S60] C++：遍历并删除元素
来源：http://dali.sufxvd.cn/Article/details/gtosjczaoz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhixingplan.top/Article/details/gtlnqursbf.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtajwwctss.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hnqzz.top/Article/details/gtimimytqz.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtlizufipt.html

[T01] Kotlin：Hello World
来源：http://dali.aibaodan.cn/Article/details/gtpmpmesuc.html

println("Hello")
来源：http://dali.sxryk.cn/Article/details/gtpfhwlnxy.html

[T02] Kotlin：变量
来源：http://dali.mhx1999.top/Article/details/gthiqmmtfa.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hammf.cn/Article/details/gtyudkwadw.html

[T03] Kotlin：字符串模板
来源：http://dali.yangfankeji.com/Article/details/gthlmwffof.html

"值: $b"
来源：http://dali.yj202588.top/Article/details/gtrzbihfvm.html

[T04] Kotlin：空安全
来源：http://dali.fzhhl.top/Article/details/gtouwvdazl.html

val n: String? = null;  n?.length
来源：http://dali.kuanghao11.cn/Article/details/gtqyajbfeo.html

[T05] Kotlin：when 表达式
来源：http://dali.yj202588.top/Article/details/gtjtglnezw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhoulong.xyz/Article/details/gtcqbobitd.html

[T06] Kotlin：集合映射
来源：http://dali.cdnleiting.top/Article/details/gtdbxvbqru.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jqgfzy.top/Article/details/gtyktjbmob.html

[T07] Kotlin：集合过滤
来源：http://dali.yvedp.cn/Article/details/gthbousmgw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cheryme.top/Article/details/gticmzhnhr.html

[T08] Kotlin：数据类
来源：http://dali.aibaodan.cn/Article/details/gttuzszdnv.html

data class User(val name: String, val age: Int)
来源：http://dali.yj20258.top/Article/details/gtzsqvexzp.html

[T09] Kotlin：扩展函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmdjfezcx.html

fun String.exclaim() = this + "!"
来源：http://dali.pengpengdd.cyou/Article/details/gtpawcvphl.html

[T10] Kotlin：默认参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtasovvfjk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.aibaodan.cn/Article/details/gtznatlehg.html

[T11] Kotlin：协程
来源：http://dali.hnxiangtu.top/Article/details/gtjaikpfpd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jlsjyb.cn/Article/details/gtdaovhukk.html

[T12] Kotlin：解构声明
来源：http://dali.yuanzhike.top/Article/details/gtaxwipggh.html

val (a, b) = Pair(1, 2)
来源：http://dali.fengsongda.top/Article/details/gtpeuxqzfr.html

[T13] Kotlin：只读 Map
来源：http://dali.jqgufenzy.top/Article/details/gtsedbpbgj.html

val m = mapOf("a" to 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gttxgiqcsx.html

[T14] Kotlin：循环
来源：http://dali.yueranfly.top/Article/details/gtkgcqkmmu.html

for (i in 1..10) println(i)
来源：http://dali.bjfxy.top/Article/details/gtvehfebxs.html

[T15] Kotlin：接口
来源：http://dali.yj20258.top/Article/details/gtoympozxr.html

interface Shape { fun area(): Double }
来源：http://dali.fzhhl.top/Article/details/gtubiqsarg.html

[T16] Swift：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtcjlbycst.html

print("Hello")
来源：http://dali.tian-w.cn/Article/details/gtcyclpqbj.html

[T17] Swift：变量与常量
来源：http://dali.cdnleiting.top/Article/details/gtcwnahbdg.html

var a = 1;  let b = 2
来源：http://dali.kuanghao11.cn/Article/details/gtatlcqbaw.html

[T18] Swift：字符串插值
来源：http://dali.guannengcc.top/Article/details/gtqzgfobou.html

"值: \(b)"
来源：http://dali.jinqigufen.top/Article/details/gtvdrxuopm.html

[T19] Swift：可选绑定
来源：http://dali.jiagoushi.top/Article/details/gtaunsptqn.html

if let n = opt { print(n) }
来源：http://dali.tianlin.xyz/Article/details/gtqebznmrm.html

[T20] Swift：数组操作
来源：http://dali.shzxlz.cn/Article/details/gttmpbdlny.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shangyingyoupin.top/Article/details/gtpgxamexi.html

[T21] Swift：遍历
来源：http://dali.yj20258.top/Article/details/gtwcqioyso.html

for x in a { print(x) }
来源：http://dali.jiagoushi.top/Article/details/gtmtumvaxu.html

[T22] Swift：字典
来源：http://dali.yuxming.cn/Article/details/gtytxrqxlz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.aibaodan.cn/Article/details/gtrrcpiyqp.html

[T23] Swift：函数
来源：http://dali.chenlongwang.top/Article/details/gtqzguijmh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tian-w.cn/Article/details/gthyernxnz.html

[T24] Swift：闭包
来源：http://dali.sysykeji.top/Article/details/gtzskmidlz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yangfankeji.com/Article/details/gtjpraebiw.html

[T25] Swift：结构体
来源：http://dali.zhongyouzk.top/Article/details/gtonbbzjba.html

struct P { var x: Int }
来源：http://dali.cashguo.top/Article/details/gtjnainsru.html

[T26] Swift：类与重写
来源：http://dali.snrcjt.cn/Article/details/gtjfxydcci.html

class A: Base { override func f() {} }
来源：http://dali.birdmap.top/Article/details/gtecupbcum.html

[T27] Swift：错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttcglcqku.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gtclrvlwqz.html

[T28] Swift：枚举
来源：http://dali.wangshuangyany.cn/Article/details/gtwzgakkcy.html

enum Color { case red, green }
来源：http://dali.hongshengwenyu.top/Article/details/gtjdmdnffw.html

[T29] Swift：guard 提前返回
来源：http://dali.hysaishi.cn/Article/details/gtopkrieek.html

guard let x = opt else { return }
来源：http://dali.shzxlz.cn/Article/details/gtbphzhvfv.html

[T30] Swift：协议
来源：http://dali.dashuyun.cn/Article/details/gtehftoxej.html

protocol Shape { func area() -> Double }
来源：http://dali.yvedp.cn/Article/details/gtrtyvipon.html

[T31] Lua：Hello World
来源：http://dali.xinyue.icu/Article/details/gtagrrduhn.html

print("Hello")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfectuegf.html

[T32] Lua：局部变量
来源：http://dali.redwolf501.top/Article/details/gtooxobrka.html

local a = 1
来源：http://dali.jyoumei.cn/Article/details/gthhermtgn.html

[T33] Lua：表（数组）
来源：http://dali.zhixingplan.top/Article/details/gtlbpfaily.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shzxlz.cn/Article/details/gteattnjtm.html

[T34] Lua：遍历表
来源：http://dali.pengpengdd.cyou/Article/details/gticrzdqdw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.svipenyu.cn/Article/details/gtetdcyaci.html

[T35] Lua：字典表
来源：http://dali.hnxiangtu.top/Article/details/gtwuliyswo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shangyingyoupin.top/Article/details/gtktmeirru.html

[T36] Lua：函数
来源：http://dali.kuanghao11.cn/Article/details/gtdieyygap.html

function add(a, b) return a + b end
来源：http://dali.sysykeji.top/Article/details/gtvkvdzqiv.html

[T37] Lua：字符串拼接
来源：http://dali.yueranfly.top/Article/details/gtpfkwtpxv.html

"a" .. "b"
来源：http://dali.yvedp.cn/Article/details/gtyihmyart.html

[T38] Lua：条件
来源：http://dali.316326.xyz/Article/details/gtmbnkouzw.html

if x > 0 then print("正") end
来源：http://dali.chenlongwang.top/Article/details/gtcpmloscu.html

[T39] Lua：模式匹配
来源：http://dali.hfpthk.cn/Article/details/gtmyeweahp.html

string.find(s, "%d+")
来源：http://dali.shanyushiyangtech.top/Article/details/gtofnypcmm.html

[T40] Lua：元表
来源：http://dali.9152youxi.cn/Article/details/gtakshddjt.html

setmetatable({}, { __index = base })
来源：http://dali.jqgufenzy.top/Article/details/gthoxjcsmc.html

[T41] Perl：Hello World
来源：http://dali.ydzc1.top/Article/details/gtjhndxyvo.html

print "Hello\n";
来源：http://dali.zhiwuduotai.top/Article/details/gtbqxftiho.html

[T42] Perl：变量类型
来源：http://dali.chenjidiqi.icu/Article/details/gtadlcidig.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ivvv.top/Article/details/gtcfiaogsb.html

[T43] Perl：字符串插值
来源：http://dali.kuanghao11.cn/Article/details/gtlhmyzucs.html

"值: $a"
来源：http://dali.jqgufenzy.top/Article/details/gtjdedveju.html

[T44] Perl：条件
来源：http://dali.daxiang520.top/Article/details/gturbrslrb.html

if ($a > 0) { print "正"; }
来源：http://dali.gaohongyu789.top/Article/details/gtcuqjthwe.html

[T45] Perl：数组遍历
来源：http://dali.gzhubu.top/Article/details/gtbpibmonv.html

for my $x (@arr) { print $x; }
来源：http://dali.svipenyu.cn/Article/details/gtkxgbzhrp.html

[T46] Perl：哈希操作
来源：http://dali.dashuyun.cn/Article/details/gtmbyemzzu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.iojbl.cn/Article/details/gtypilxyub.html

[T47] Perl：正则捕获
来源：http://dali.jinqigfzy.top/Article/details/gtgafymmqb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.iojbl.cn/Article/details/gtyjlnwptq.html

[T48] Perl：正则替换
来源：http://dali.iojbl.cn/Article/details/gtgvycmjcl.html

$s =~ s/old/new/g;
来源：http://dali.ybcxt.top/Article/details/gtwvxgamyn.html

[T49] Perl：函数
来源：http://dali.jyoumei.cn/Article/details/gtepvnnowc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gtiblkimju.html

[T50] Perl：逐行读文件
来源：http://dali.meibo888.top/Article/details/gtogkddypz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinqigfzy.top/Article/details/gtjpsvoaao.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.snrcjt.cn/Article/details/gtlqwxxpdg.html

[T51] Scala：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtfolbadjz.html

println("Hello")
来源：http://dali.birdmap.top/Article/details/gttusnjjuc.html

[T52] Scala：变量
来源：http://dali.hysaishi.cn/Article/details/gtudmlqzor.html

val a = 1;  var b = 2
来源：http://dali.ppjwa.cn/Article/details/gtkonztrkj.html

[T53] Scala：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gtsytbskik.html

s"值: $b"
来源：http://dali.pycfn.com/Article/details/gtiydseklc.html

[T54] Scala：集合映射
来源：http://dali.hongshengwenyu.top/Article/details/gtjmnfjmyz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ybcxt.top/Article/details/gtrwijfxop.html

[T55] Scala：集合过滤
来源：http://dali.aibaodan.cn/Article/details/gtfzyhesps.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hnxiangtu.top/Article/details/gtohzmrmxr.html

[T56] Scala：样例类
来源：http://dali.andypj.xyz/Article/details/gtahvvafor.html

case class User(name: String, age: Int)
来源：http://dali.c1oappe.top/Article/details/gtpqnntwlr.html

[T57] Scala：模式匹配
来源：http://dali.tianlin.xyz/Article/details/gttgsyivnv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shangyingyoupin.top/Article/details/gtylkutizn.html

[T58] Scala：函数定义
来源：http://dali.zhoulong.xyz/Article/details/gtsscqrmhr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yuxming.cn/Article/details/gtawunztai.html

[T59] Scala：循环
来源：http://dali.gogol.net.cn/Article/details/gthmzpulhj.html

for (i <- 1 to 10) println(i)
来源：http://dali.hysaishi.cn/Article/details/gttudpzkhv.html

[T60] Scala：折叠
来源：http://dali.ehwqpu.com/Article/details/gtvcwcunmb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yj20258888.top/Article/details/gtxksdunxh.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtwewzcnzz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cheryme.top/Article/details/gtbdkjdmhp.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtlyewngak.html

[U01] Py：创建虚拟环境
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdtocxnij.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhixingplan.top/Article/details/gtrvqvgbjj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.dashuyun.cn/Article/details/gtsaxwosoh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cucudq.cn/Article/details/gteqmnbxoc.html

[U03] Py：加载 .env 配置
来源：http://dali.dianchejie.cn/Article/details/gtbdeteeun.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.aizwys.cn/Article/details/gtxzlqybgs.html

[U04] Py：变量调试打印
来源：http://dali.guannengcc.top/Article/details/gtxulpipuy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.tian-w.cn/Article/details/gtwlscgyas.html

[U05] Py：列表去重且保序
来源：http://dali.yj20258888.top/Article/details/gtfvxmntpa.html

list(dict.fromkeys(arr))
来源：http://dali.nanxuanxn.top/Article/details/gtxrfrljyo.html

[U06] Py：合并两个字典
来源：http://dali.fengsongda.top/Article/details/gtoytspkmi.html

{**a, **b}
来源：http://dali.zhongyouzk.top/Article/details/gtkcvpybll.html

[U07] Py：反转字典键值
来源：http://dali.zdqjudy.top/Article/details/gtmmujkwnw.html

{v: k for k, v in d.items()}
来源：http://dali.xuanzx.com/Article/details/gtjfdnymud.html

[U08] Py：展平二维列表
来源：http://dali.guowangkeji.top/Article/details/gtibwylwbx.html

[y for x in nested for y in x]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpupzyawq.html

[U09] Py：字典取最大值的键
来源：http://dali.shuidangran.top/Article/details/gtsuqkspjp.html

max(d, key=d.get)
来源：http://dali.smart0.xyz/Article/details/gtkyivzeis.html

[U10] Py：按值排序字典
来源：http://dali.hywenlv.cn/Article/details/gtbbkdnypa.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jyoumei.cn/Article/details/gtbspuyvuk.html

[U11] Py：生成器表达式
来源：http://dali.sufxvd.cn/Article/details/gtnvpzgelp.html

(x * 2 for x in arr)
来源：http://dali.yueranfly.top/Article/details/gtyzpcrhur.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jqgfzy.top/Article/details/gtkxooxtbw.html

Counter(arr).most_common(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtayqtjbvt.html

[U13] Py：固定长度队列
来源：http://dali.dianchejie.cn/Article/details/gtyevbokho.html

deque(maxlen=10)
来源：http://dali.yonumen.top/Article/details/gtsxmldymq.html

[U14] Py：分组收集到列表
来源：http://dali.yonumen.top/Article/details/gtutytecjt.html

defaultdict(list)
来源：http://dali.birdmap.top/Article/details/gtaxevexhk.html


<!-- 参考信息 -->