代发 wailian999

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dianchejie.cn/Article/details/gtubxtkfmb.html

[R80] 查看脚本执行耗时
来源：http://dali.hnqzz.top/Article/details/gtuhhdgzwy.html

time ./run.sh
来源：http://dali.quarkkingdee.top/Article/details/gtiktqoycc.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gthmirotuj.html

S. C / C++ 专题
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcvpwpekj.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtuezlmcie.html

[S01] C：Hello World
来源：http://dali.sweek.top/Article/details/gtsobvzsdm.html

#include <stdio.h>
来源：http://dali.yj20258.top/Article/details/gtsssjsgme.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yueranfly.top/Article/details/gtvyoyrldx.html

[S02] C：变量与格式化输出
来源：http://dali.snrcjt.cn/Article/details/gtusolgkew.html

int a = 10; printf("%d\n", a);
来源：http://dali.sxryk.cn/Article/details/gtxusljitf.html

[S03] C：读入整数
来源：http://dali.mhx1999.top/Article/details/gtpvqzsrxz.html

int x; scanf("%d", &x);
来源：http://dali.cqqwz.cn/Article/details/gtsxgysrbc.html

[S04] C：字符串复制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfexnewyr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.dianchejie.cn/Article/details/gtsapuefmf.html

[S05] C：字符串长度
来源：http://dali.zhengqikj.top/Article/details/gtuuweejjy.html

strlen(s)
来源：http://dali.ydzc1.top/Article/details/gtizraqsmy.html

[S06] C：字符串比较
来源：http://dali.bjfxy.top/Article/details/gtybqtfgpj.html

strcmp(a, b) == 0
来源：http://dali.andypj.xyz/Article/details/gtgdjqblqx.html

[S07] C：数组遍历求和
来源：http://dali.vqdsnc.cn/Article/details/gtmkuojxyl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenlongwang.top/Article/details/gtckbemppx.html

[S08] C：动态内存分配与释放
来源：http://dali.jyoumei.cn/Article/details/gtxgorhwuu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xinyue.icu/Article/details/gthmabfnyo.html

[S09] C：结构体定义与初始化
来源：http://dali.zhongyouzk.top/Article/details/gtsvtsutdr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenjidiqi.icu/Article/details/gtqosamltg.html

[S10] C：指针与解引用
来源：http://dali.cashguo.top/Article/details/gtfmkrhwnz.html

int *p = &a;  *p = 5;
来源：http://dali.hfpthk.cn/Article/details/gtwvoqgrkh.html

[S11] C：逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gtqslaemrj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xylfe.cn/Article/details/gtgeaombyu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ybcxt.top/Article/details/gtcbarazhp.html

fclose(f);
来源：http://dali.hnxiangtu.top/Article/details/gtiwbtzonk.html

[S12] C：写文件
来源：http://dali.gzhubu.top/Article/details/gtprqbbyfn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yanxiufei.cn/Article/details/gtqytnvhde.html

[S13] C：宏定义
来源：http://dali.quarkkingdee.top/Article/details/gttariuenm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gzhubu.top/Article/details/gtssxtbzfw.html

[S14] C：枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxcwkrza.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sysykeji.top/Article/details/gtrzgdkdew.html

[S15] C：类型转换
来源：http://dali.ivvv.top/Article/details/gtxwajsvct.html

(double) a / b
来源：http://dali.yangfankeji.com/Article/details/gtlbvrwvzx.html

[S16] C：位操作置位
来源：http://dali.feifeiyinyue.top/Article/details/gtlvxxguoi.html

x |= (1 << 3);
来源：http://dali.cashguo.top/Article/details/gtysysyhzn.html

[S17] C：安全拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gtupfqypbt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.aibaodan.cn/Article/details/gtppzevxvi.html

[S18] C：命令行参数
来源：http://dali.chenlongwang.top/Article/details/gtjdaiphif.html

int main(int argc, char **argv)
来源：http://dali.wangshuangyany.cn/Article/details/gtydjbycke.html

[S19] C：快速排序
来源：http://dali.jinqigfzy.top/Article/details/gttouqcbxy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tian-w.cn/Article/details/gtcplqtzbl.html

[S20] C：二分查找
来源：http://dali.zhixingplan.top/Article/details/gtfwrquocu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.meibo888.top/Article/details/gtdfbpxqju.html

[S21] C：字符类别判断
来源：http://dali.daria6918.cn/Article/details/gtlqlujzmb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jlsjyb.cn/Article/details/gtomansbkv.html

[S22] C：字符串转数字
来源：http://dali.kuanghao11.cn/Article/details/gtpxmaccmx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ybcxt.top/Article/details/gtfknsnixq.html

[S23] C：随机数
来源：http://dali.hfpthk.cn/Article/details/gtpngloflv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.daxiang520.top/Article/details/gtswnfocze.html

[S24] C：获取本地时间
来源：http://dali.nanxuanxn.top/Article/details/gtzpbwpjzk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.wangshuangyany.cn/Article/details/gtvwznmpcw.html

[S25] C：内存拷贝
来源：http://dali.yvedp.cn/Article/details/gtprbffrji.html

memcpy(dst, src, n);
来源：http://dali.yj20258888.top/Article/details/gtuhjnxvjc.html

[S26] C：内存清零
来源：http://dali.jinqigufen.top/Article/details/gtmqkdxpkw.html

memset(a, 0, sizeof a);
来源：http://dali.chenjidiqi.icu/Article/details/gtqjfuvutr.html

[S27] C：定义常量
来源：http://dali.vqdsnc.cn/Article/details/gtkvsxmsuk.html

const double PI = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gtbezmikrb.html

[S28] C：静态变量
来源：http://dali.gzhubu.top/Article/details/gtozolfzzk.html

static int counter = 0;
来源：http://dali.jiagoushi.top/Article/details/gtinftrzpu.html

[S29] C：变参函数
来源：http://dali.xuanzx.com/Article/details/gtvmiutlgc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.aizwys.cn/Article/details/gtvbhmvdui.html

[S30] C：头文件保护
来源：http://dali.zhongyouzk.top/Article/details/gtzjldfwfa.html

#ifndef X_H
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjuwxvgxs.html

#define X_H
来源：http://dali.yongpay.top/Article/details/gtfqkqhnbb.html

#endif
来源：http://dali.chenjidiqi.icu/Article/details/gtybrhualp.html

[S31] C++：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtqjyhiaaw.html

#include <iostream>
来源：http://dali.jqgfzy.top/Article/details/gtjjgdhkpm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yvedp.cn/Article/details/gtslqmivrj.html

[S32] C++：字符串
来源：http://dali.havefunace.top/Article/details/gtelkbddxd.html

std::string s = "hi";  s += "!";
来源：http://dali.jinqigufen.top/Article/details/gterulccet.html

[S33] C++：vector 增删
来源：http://dali.yongpay.top/Article/details/gtgeprhtmt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhongyouzk.top/Article/details/gtbawqwwfm.html

[S34] C++：遍历 vector
来源：http://dali.hysaishi.cn/Article/details/gthgleprdc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.wangdashe.top/Article/details/gtbrycypib.html

[S35] C++：map
来源：http://dali.shanyushiyangkeji.top/Article/details/gteebmrphp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnqzz.top/Article/details/gtqnkxgipk.html

[S36] C++：unordered_map
来源：http://dali.shangyingyoupin.top/Article/details/gtqscmuhus.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gthrlokbsi.html

[S37] C++：set
来源：http://dali.sufxvd.cn/Article/details/gtxjvnmifh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtjeglvfdm.html

[S38] C++：排序
来源：http://dali.jinqigufen.top/Article/details/gtpzgmftww.html

std::sort(v.begin(), v.end());
来源：http://dali.nanxinkj.top/Article/details/gtpjevshng.html

[S39] C++：自定义比较器排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtflqknqeu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nanxuanxn.top/Article/details/gtotkboimg.html

[S40] C++：查找元素
来源：http://dali.snrcjt.cn/Article/details/gtiwvmtqys.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jiagoushi.top/Article/details/gthtebkjfi.html

[S41] C++：类与构造函数
来源：http://dali.cucudq.cn/Article/details/gtvlrhnhrd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.meibo888.top/Article/details/gtensturcn.html

[S42] C++：继承与虚函数
来源：http://dali.yanxiufei.cn/Article/details/gtgvsjuiqv.html

class B : public Base { public: void f() override {} };
来源：http://dali.ehwqpu.com/Article/details/gtmburuzvm.html

[S43] C++：智能指针
来源：http://dali.xinyue.icu/Article/details/gthhyzdifc.html

auto p = std::make_unique<int>(5);
来源：http://dali.quarkkingdee.top/Article/details/gtyqrxakig.html

[S44] C++：引用传参
来源：http://dali.hammf.cn/Article/details/gtuymoexrj.html

void inc(int &x) { ++x; }
来源：http://dali.aibaodan.cn/Article/details/gtqivmhype.html

[S45] C++：lambda
来源：http://dali.cdnleiting.top/Article/details/gttmonrcst.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.meibo888.top/Article/details/gtfgmsgpuq.html

[S46] C++：函数模板
来源：http://dali.jlsjyb.cn/Article/details/gtewiuyegv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yj20258888.top/Article/details/gtuyoxtwgg.html

[S47] C++：结构化绑定遍历
来源：http://dali.xziqi.cn/Article/details/gttidetsyc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.snrcjt.cn/Article/details/gtxmidsupk.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gtplgaaovm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinqigufen.top/Article/details/gtzqksmhun.html

while (std::getline(in, line)) { }
来源：http://dali.xuetiantiany.cn/Article/details/gtvdvtfpxp.html

[S49] C++：写文件
来源：http://dali.jinqigfzy.top/Article/details/gtluwoqhtx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinghuilouyu.cn/Article/details/gthaoiphfu.html

[S50] C++：格式化数字
来源：http://dali.quarkkingdee.top/Article/details/gtgfyvkhtd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gtttnuaqby.html

[S51] C++：显式类型转换
来源：http://dali.jinqigufen.top/Article/details/gtklrjremx.html

static_cast<double>(a) / b
来源：http://dali.cashguo.top/Article/details/gtvsvkrncr.html

[S52] C++：const 与 noexcept
来源：http://dali.jyoumei.cn/Article/details/gtsgexwore.html

int size() const noexcept { return n_; }
来源：http://dali.yuanzhike.top/Article/details/gtrkljdgda.html

[S53] C++：移动语义
来源：http://dali.nanxinkj.top/Article/details/gthscgsrmi.html

std::vector<int> w = std::move(v);
来源：http://dali.tanke756.top/Article/details/gtehkaaxup.html

[S54] C++：异常处理
来源：http://dali.yongpay.top/Article/details/gtzeeqjmsy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yuxming.cn/Article/details/gtpymtkehi.html

[S55] C++：结构化绑定
来源：http://dali.0kj1m.cn/Article/details/gtqkvchkbm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.daria6918.cn/Article/details/gtpdrivudu.html

[S56] C++：optional
来源：http://dali.meibo888.top/Article/details/gtrformjqm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hysaishi.cn/Article/details/gtqxyylxub.html

[S57] C++：编译期常量
来源：http://dali.gaohongyu789.top/Article/details/gtoapxdhop.html

constexpr int N = 10;
来源：http://dali.shzxlz.cn/Article/details/gtkhxlhrvb.html

[S58] C++：命名空间
来源：http://dali.zhengqikj.top/Article/details/gtwnrqnlxc.html

namespace ns { int f() { return 1; } }
来源：http://dali.jianghu66.top/Article/details/gtttbhdjgr.html

[S59] C++：静态断言
来源：http://dali.xuetiantiany.cn/Article/details/gtxuqzrene.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hnxiangtu.top/Article/details/gtxlielfqg.html

[S60] C++：遍历并删除元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtchkyjofo.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.vqdsnc.cn/Article/details/gtutgstvkr.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtywooawhr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hnqzz.top/Article/details/gtglyzgkjd.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtxclwclgz.html

[T01] Kotlin：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmtfwkoec.html

println("Hello")
来源：http://dali.guowangkeji.top/Article/details/gtxzkokiqa.html

[T02] Kotlin：变量
来源：http://dali.havefunace.top/Article/details/gtjypmxjsw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.bjfxy.top/Article/details/gtfzvlllci.html

[T03] Kotlin：字符串模板
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkpnrhiur.html

"值: $b"
来源：http://dali.xuetiantiany.cn/Article/details/gtpzzwvahu.html

[T04] Kotlin：空安全
来源：http://dali.aibaodan.cn/Article/details/gtfidgiuct.html

val n: String? = null;  n?.length
来源：http://dali.hammf.cn/Article/details/gtxwqjywgf.html

[T05] Kotlin：when 表达式
来源：http://dali.hammf.cn/Article/details/gtkpuclhpx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyalhnthi.html

[T06] Kotlin：集合映射
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcovbmcxi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.pycfn.com/Article/details/gtavylhicb.html

[T07] Kotlin：集合过滤
来源：http://dali.ehwqpu.com/Article/details/gttlbzrlvs.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sweek.top/Article/details/gtfolqypok.html

[T08] Kotlin：数据类
来源：http://dali.hywenlv.cn/Article/details/gtigyfgzhw.html

data class User(val name: String, val age: Int)
来源：http://dali.svipenyu.cn/Article/details/gtpfddqdmy.html

[T09] Kotlin：扩展函数
来源：http://dali.jinqigufen.top/Article/details/gtxvnapfux.html

fun String.exclaim() = this + "!"
来源：http://dali.dashuyun.cn/Article/details/gtlnbxbigt.html

[T10] Kotlin：默认参数
来源：http://dali.shangyingyoupin.top/Article/details/gtvfazexix.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hywenlv.cn/Article/details/gtgrxqiyda.html

[T11] Kotlin：协程
来源：http://dali.gaohongyu789.top/Article/details/gtiwxljefc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hongshengwenyu.top/Article/details/gtkdcoranh.html

[T12] Kotlin：解构声明
来源：http://dali.ppjwa.cn/Article/details/gtglybhhvv.html

val (a, b) = Pair(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gteemiqkmh.html

[T13] Kotlin：只读 Map
来源：http://dali.cucudq.cn/Article/details/gtdhfpqqvp.html

val m = mapOf("a" to 1)
来源：http://dali.ehwqpu.com/Article/details/gtfvksmcws.html

[T14] Kotlin：循环
来源：http://dali.yonumen.top/Article/details/gtltlweoad.html

for (i in 1..10) println(i)
来源：http://dali.pengpengdd.cyou/Article/details/gtxrgcssjs.html

[T15] Kotlin：接口
来源：http://dali.fzhhl.top/Article/details/gtzeqadnfc.html

interface Shape { fun area(): Double }
来源：http://dali.zhongyouzk.top/Article/details/gtnujibzic.html

[T16] Swift：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtwcscnius.html

print("Hello")
来源：http://dali.iojbl.cn/Article/details/gtuwvorgzm.html

[T17] Swift：变量与常量
来源：http://dali.yangfankeji.com/Article/details/gtalfregts.html

var a = 1;  let b = 2
来源：http://dali.0kj1m.cn/Article/details/gtxibgarow.html

[T18] Swift：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gtzzasjnxb.html

"值: \(b)"
来源：http://dali.gzhubu.top/Article/details/gttymvezwj.html

[T19] Swift：可选绑定
来源：http://dali.zhixingplan.top/Article/details/gtxxqfjapm.html

if let n = opt { print(n) }
来源：http://dali.snrcjt.cn/Article/details/gtlqutcfjz.html

[T20] Swift：数组操作
来源：http://dali.fengsongda.top/Article/details/gtvkicthmw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gaohongyu789.top/Article/details/gtsxlzofcl.html

[T21] Swift：遍历
来源：http://dali.ehwqpu.com/Article/details/gtltfvsroh.html

for x in a { print(x) }
来源：http://dali.9152youxi.cn/Article/details/gtumafuiwm.html

[T22] Swift：字典
来源：http://dali.hongshengwenyu.top/Article/details/gtbnplslji.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yuxming.cn/Article/details/gtntinnnjh.html

[T23] Swift：函数
来源：http://dali.jinqigufen.top/Article/details/gtoyglwiel.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.smart0.xyz/Article/details/gtivckvaom.html

[T24] Swift：闭包
来源：http://dali.ywan-chungtsiang.top/Article/details/gtalwlanth.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.pycfn.com/Article/details/gtbxsajoab.html

[T25] Swift：结构体
来源：http://dali.havefunace.top/Article/details/gthdattwku.html

struct P { var x: Int }
来源：http://dali.sufxvd.cn/Article/details/gtfmaraeco.html

[T26] Swift：类与重写
来源：http://dali.hongshengwenyu.top/Article/details/gtmtodhwrs.html

class A: Base { override func f() {} }
来源：http://dali.shuidangran.top/Article/details/gtqniqaodu.html

[T27] Swift：错误处理
来源：http://dali.gotoacloud.top/Article/details/gtzzytjzcx.html

do { try f() } catch { print(error) }
来源：http://dali.iojbl.cn/Article/details/gtegodeggz.html

[T28] Swift：枚举
来源：http://dali.zhoulong.xyz/Article/details/gtqsymvnbr.html

enum Color { case red, green }
来源：http://dali.snrcjt.cn/Article/details/gtyvqzzecu.html

[T29] Swift：guard 提前返回
来源：http://dali.yongpay.top/Article/details/gtzwhcfyca.html

guard let x = opt else { return }
来源：http://dali.yuxming.cn/Article/details/gtrhpwlqnb.html

[T30] Swift：协议
来源：http://dali.yj202588.top/Article/details/gtfnrqqvze.html

protocol Shape { func area() -> Double }
来源：http://dali.hnqzz.top/Article/details/gtkpweiqhh.html

[T31] Lua：Hello World
来源：http://dali.redwolf501.top/Article/details/gterqmpxya.html

print("Hello")
来源：http://dali.gzhubu.top/Article/details/gtascpkwhi.html

[T32] Lua：局部变量
来源：http://dali.meibo888.top/Article/details/gtviyeabet.html

local a = 1
来源：http://dali.jinqigfzy.top/Article/details/gtbsfgjqit.html

[T33] Lua：表（数组）
来源：http://dali.daria6918.cn/Article/details/gtxkaldhva.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.guowangkeji.top/Article/details/gtcdxnquys.html

[T34] Lua：遍历表
来源：http://dali.birdmap.top/Article/details/gtlehvwibt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ivvv.top/Article/details/gtgwclrhtm.html

[T35] Lua：字典表
来源：http://dali.shzxlz.cn/Article/details/gtafvxezev.html

local d = { a = 1 };  d.b = 2
来源：http://dali.fzhhl.top/Article/details/gtbkeiedac.html

[T36] Lua：函数
来源：http://dali.gzhubu.top/Article/details/gtwozpnmyr.html

function add(a, b) return a + b end
来源：http://dali.sxryk.cn/Article/details/gtjwnyvbsh.html

[T37] Lua：字符串拼接
来源：http://dali.nanxuanxn.top/Article/details/gtfgeuzgwu.html

"a" .. "b"
来源：http://dali.daxiang520.top/Article/details/gtwqbmoprx.html

[T38] Lua：条件
来源：http://dali.yuxming.cn/Article/details/gtzrtwvvhf.html

if x > 0 then print("正") end
来源：http://dali.daria6918.cn/Article/details/gtkvoyavpy.html

[T39] Lua：模式匹配
来源：http://dali.zhoulong.xyz/Article/details/gtrqllgcjp.html

string.find(s, "%d+")
来源：http://dali.jqgfzy.top/Article/details/gtoovomuvs.html

[T40] Lua：元表
来源：http://dali.hysaishi.cn/Article/details/gtlthmflmk.html

setmetatable({}, { __index = base })
来源：http://dali.hysaishi.cn/Article/details/gtituvonew.html

[T41] Perl：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtqijjxebq.html

print "Hello\n";
来源：http://dali.guowangkeji.top/Article/details/gtsapmdswh.html

[T42] Perl：变量类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtdrrvujea.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sxryk.cn/Article/details/gtmidkdssi.html

[T43] Perl：字符串插值
来源：http://dali.iojbl.cn/Article/details/gtxwvwwpsd.html

"值: $a"
来源：http://dali.nanxinkj.top/Article/details/gtqmivoxlj.html

[T44] Perl：条件
来源：http://dali.hnqzz.top/Article/details/gtvfstqmdq.html

if ($a > 0) { print "正"; }
来源：http://dali.hysaishi.cn/Article/details/gtiuddwsha.html

[T45] Perl：数组遍历
来源：http://dali.jqgufenzy.top/Article/details/gtmwakmlyv.html

for my $x (@arr) { print $x; }
来源：http://dali.xylfe.cn/Article/details/gtmbsqqwzn.html

[T46] Perl：哈希操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gthksghyst.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.chenzaomai.com/Article/details/gtxatyatfh.html

[T47] Perl：正则捕获
来源：http://dali.xuetiantiany.cn/Article/details/gtziegpbuh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zdqjudy.top/Article/details/gtiaobmydw.html

[T48] Perl：正则替换
来源：http://dali.redwolf501.top/Article/details/gtabmgsfqa.html

$s =~ s/old/new/g;
来源：http://dali.fengsongda.top/Article/details/gtllkfugec.html

[T49] Perl：函数
来源：http://dali.andypj.xyz/Article/details/gtkrffoslx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gogol.net.cn/Article/details/gtnwhiuwtz.html

[T50] Perl：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gtjikmoklk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xylfe.cn/Article/details/gtnleqcptf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.guowangkeji.top/Article/details/gtsubdhvaf.html

[T51] Scala：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtpdqliloa.html

println("Hello")
来源：http://dali.nanxinkj.top/Article/details/gtmrzbatsz.html

[T52] Scala：变量
来源：http://dali.yonumen.top/Article/details/gtzwpkljgp.html

val a = 1;  var b = 2
来源：http://dali.aibaodan.cn/Article/details/gtzwvtnajt.html

[T53] Scala：字符串插值
来源：http://dali.jqgfzy.top/Article/details/gtdfudxulj.html

s"值: $b"
来源：http://dali.sysykeji.top/Article/details/gticyukqjd.html

[T54] Scala：集合映射
来源：http://dali.cdnleiting.top/Article/details/gtuhqrettl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhixingplan.top/Article/details/gtlehogtru.html

[T55] Scala：集合过滤
来源：http://dali.vqdsnc.cn/Article/details/gtvzgkxmfc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gtsyjicgsa.html

[T56] Scala：样例类
来源：http://dali.cqqwz.cn/Article/details/gtayskxczk.html

case class User(name: String, age: Int)
来源：http://dali.chenlongwang.top/Article/details/gttzmdoeuq.html

[T57] Scala：模式匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtregycvbn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.fzhhl.top/Article/details/gtjclcowfe.html

[T58] Scala：函数定义
来源：http://dali.haohaochexian.top/Article/details/gttctqjzmj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.nwbrower.top/Article/details/gtijvchwvm.html

[T59] Scala：循环
来源：http://dali.sxryk.cn/Article/details/gtskkqvpkx.html

for (i <- 1 to 10) println(i)
来源：http://dali.ehwqpu.com/Article/details/gtxqziusos.html

[T60] Scala：折叠
来源：http://dali.xylfe.cn/Article/details/gtrfqidedr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.dashuyun.cn/Article/details/gtexgeaiws.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtlxwpngki.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jyoumei.cn/Article/details/gtzvrrhpox.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtxawhmnxe.html

[U01] Py：创建虚拟环境
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtarwjrubo.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cheryme.top/Article/details/gtenzgzora.html

[U02] Py：导出 / 安装依赖
来源：http://dali.kuanghao11.cn/Article/details/gtiifuojnx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ppjwa.cn/Article/details/gtjsrabnlq.html

[U03] Py：加载 .env 配置
来源：http://dali.dianchejie.cn/Article/details/gtcbxozcau.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.pycfn.com/Article/details/gtnofkjbes.html

[U04] Py：变量调试打印
来源：http://dali.haohaochexian.top/Article/details/gtocpycvow.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.dashuyun.cn/Article/details/gtflimntwp.html

[U05] Py：列表去重且保序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiekkjiiw.html

list(dict.fromkeys(arr))
来源：http://dali.aizwys.cn/Article/details/gtrsznlayy.html

[U06] Py：合并两个字典
来源：http://dali.shuidangran.top/Article/details/gtddypipfr.html

{**a, **b}
来源：http://dali.yonumen.top/Article/details/gtxkpkyotu.html

[U07] Py：反转字典键值
来源：http://dali.dashuyun.cn/Article/details/gttgkgdogv.html

{v: k for k, v in d.items()}
来源：http://dali.yongpay.top/Article/details/gttppbdtvg.html

[U08] Py：展平二维列表
来源：http://dali.bjfxy.top/Article/details/gtjsquwcmf.html

[y for x in nested for y in x]
来源：http://dali.daxiang520.top/Article/details/gtmybcfzcr.html

[U09] Py：字典取最大值的键
来源：http://dali.pengpengdd.cyou/Article/details/gtmvxkrnhk.html

max(d, key=d.get)
来源：http://dali.cucudq.cn/Article/details/gtsqibxvpj.html

[U10] Py：按值排序字典
来源：http://dali.zhiwuduotai.top/Article/details/gtmjnkhkkq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhixingplan.top/Article/details/gtjysbjphu.html

[U11] Py：生成器表达式
来源：http://dali.ppjwa.cn/Article/details/gtrlxahnft.html

(x * 2 for x in arr)
来源：http://dali.kuanghao11.cn/Article/details/gtpwbccfjy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtknvblggw.html

Counter(arr).most_common(3)
来源：http://dali.chenzaomai.com/Article/details/gtrkuujndj.html

[U13] Py：固定长度队列
来源：http://dali.kuanghao11.cn/Article/details/gtzxddllif.html

deque(maxlen=10)
来源：http://dali.birdmap.top/Article/details/gtlokxjgfu.html

[U14] Py：分组收集到列表
来源：http://dali.nanxuanxn.top/Article/details/gttvossfjn.html

defaultdict(list)
来源：http://dali.feifeiyinyue.top/Article/details/gtyvijnacu.html

[U15] Py：高精度计时
来源：http://dali.birdmap.top/Article/details/gtcradwyhr.html

t = time.perf_counter()
来源：http://dali.hnxiangtu.top/Article/details/gtdphplily.html

[U16] Py：命令行参数解析
来源：http://dali.bjfxy.top/Article/details/gtnfotdkun.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.9152youxi.cn/Article/details/gtsieqghtu.html

[U17] Py：初始化日志
来源：http://dali.svipenyu.cn/Article/details/gtxviautdn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.daria6918.cn/Article/details/gtecfqqlmx.html

[U18] Py：预编译正则
来源：http://dali.jiagoushi.top/Article/details/gtqsfnedvl.html

pat = re.compile(r"\d+")
来源：http://dali.pycfn.com/Article/details/gtopkbucgr.html

[U19] Py：正则替换带回调
来源：http://dali.daria6918.cn/Article/details/gtizcxgnes.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jiagoushi.top/Article/details/gttvctbmik.html

[U20] Py：缓存函数结果
来源：http://dali.zhoulong.xyz/Article/details/gtndapwffu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.tian-w.cn/Article/details/gtughjevwp.html


<!-- 参考信息 -->