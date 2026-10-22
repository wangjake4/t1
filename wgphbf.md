代发 wailian999

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yvedp.cn/Article/details/gttijuezgy.html

[R80] 查看脚本执行耗时
来源：http://dali.zycfv.cn/Article/details/gttnrcpvsl.html

time ./run.sh
来源：http://dali.aizwys.cn/Article/details/gtdfunbmqv.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtutwebgjh.html

S. C / C++ 专题
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqxzlhzwl.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtjrdtpaho.html

[S01] C：Hello World
来源：http://dali.meibo888.top/Article/details/gtrpichwlh.html

#include <stdio.h>
来源：http://dali.gzhubu.top/Article/details/gtjxedhzlv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yongpay.top/Article/details/gtumoitduh.html

[S02] C：变量与格式化输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgipnajeb.html

int a = 10; printf("%d\n", a);
来源：http://dali.316326.xyz/Article/details/gtdqpnvvpa.html

[S03] C：读入整数
来源：http://dali.cheryme.top/Article/details/gtgvlgsgpr.html

int x; scanf("%d", &x);
来源：http://dali.gaohongyu789.top/Article/details/gtszsfdmer.html

[S04] C：字符串复制
来源：http://dali.zdqjudy.top/Article/details/gtxnpxbehb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tian-w.cn/Article/details/gtcqovdcdb.html

[S05] C：字符串长度
来源：http://dali.fengsongda.top/Article/details/gtetexokrw.html

strlen(s)
来源：http://dali.xylfe.cn/Article/details/gtfrlbygip.html

[S06] C：字符串比较
来源：http://dali.snrcjt.cn/Article/details/gtjkbjttuk.html

strcmp(a, b) == 0
来源：http://dali.cucudq.cn/Article/details/gtmxddrxyh.html

[S07] C：数组遍历求和
来源：http://dali.andypj.xyz/Article/details/gtcnivcfwj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhiwuduotai.top/Article/details/gtyfbauzqm.html

[S08] C：动态内存分配与释放
来源：http://dali.sufxvd.cn/Article/details/gtnsxpussh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xziqi.cn/Article/details/gtjmfplzwt.html

[S09] C：结构体定义与初始化
来源：http://dali.dianchejie.cn/Article/details/gtkrkurinu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.vqdsnc.cn/Article/details/gtleywkucf.html

[S10] C：指针与解引用
来源：http://dali.cdnleiting.top/Article/details/gttilrptyp.html

int *p = &a;  *p = 5;
来源：http://dali.kuanghao11.cn/Article/details/gtkxxemimb.html

[S11] C：逐行读文件
来源：http://dali.xinyue.icu/Article/details/gtitchzhat.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.fzhhl.top/Article/details/gtciqkivjt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinqigfzy.top/Article/details/gtgwgvnoef.html

fclose(f);
来源：http://dali.sysykeji.top/Article/details/gtdlyvocpb.html

[S12] C：写文件
来源：http://dali.aizwys.cn/Article/details/gtgvnmylle.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jlsjyb.cn/Article/details/gtziglnakp.html

[S13] C：宏定义
来源：http://dali.jqgufenzy.top/Article/details/gtuqbszvln.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cheryme.top/Article/details/gtjdrwiggv.html

[S14] C：枚举
来源：http://dali.yuanzhike.top/Article/details/gtfpqselmk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ivvv.top/Article/details/gtteqwnjzi.html

[S15] C：类型转换
来源：http://dali.zhixingplan.top/Article/details/gtwbbobkzb.html

(double) a / b
来源：http://dali.haohaochexian.top/Article/details/gtpxupueag.html

[S16] C：位操作置位
来源：http://dali.pycfn.com/Article/details/gtsctwacez.html

x |= (1 << 3);
来源：http://dali.yongpay.top/Article/details/gtuwpszjoh.html

[S17] C：安全拼接字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtqkhrhzvb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.birdmap.top/Article/details/gtejxjhznp.html

[S18] C：命令行参数
来源：http://dali.aizwys.cn/Article/details/gtjmhwdkhc.html

int main(int argc, char **argv)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiqhofvve.html

[S19] C：快速排序
来源：http://dali.smart0.xyz/Article/details/gtewhdcsqq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.fengsongda.top/Article/details/gtgknkbvcr.html

[S20] C：二分查找
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgypfuiqk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jlsjyb.cn/Article/details/gtqimhzhoe.html

[S21] C：字符类别判断
来源：http://dali.cucudq.cn/Article/details/gtcdnkzwou.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjjmsumxt.html

[S22] C：字符串转数字
来源：http://dali.316326.xyz/Article/details/gtzcptnyrt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sysykeji.top/Article/details/gtsqcmttzh.html

[S23] C：随机数
来源：http://dali.ydzc1.top/Article/details/gtntidjxwf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.daxiang520.top/Article/details/gtpcrlbybk.html

[S24] C：获取本地时间
来源：http://dali.yanxiufei.cn/Article/details/gtppnynvyx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cashguo.top/Article/details/gtsjhzvcbd.html

[S25] C：内存拷贝
来源：http://dali.feifeiyinyue.top/Article/details/gtbpsyqnfj.html

memcpy(dst, src, n);
来源：http://dali.guowangkeji.top/Article/details/gtaazdwtlb.html

[S26] C：内存清零
来源：http://dali.xuanzx.com/Article/details/gtpsxvguok.html

memset(a, 0, sizeof a);
来源：http://dali.chenlongwang.top/Article/details/gtqkabehny.html

[S27] C：定义常量
来源：http://dali.sysykeji.top/Article/details/gtipgxqyuu.html

const double PI = 3.14159;
来源：http://dali.pycfn.com/Article/details/gtucavybos.html

[S28] C：静态变量
来源：http://dali.chenzaomai.com/Article/details/gtulicxthv.html

static int counter = 0;
来源：http://dali.quarkkingdee.top/Article/details/gtfqcwtily.html

[S29] C：变参函数
来源：http://dali.gogol.net.cn/Article/details/gtrjxrjhmm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cqqwz.cn/Article/details/gtzldnpwhl.html

[S30] C：头文件保护
来源：http://dali.pycfn.com/Article/details/gtbkxcpecj.html

#ifndef X_H
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiymbroas.html

#define X_H
来源：http://dali.jiagoushi.top/Article/details/gtcqqjrmrl.html

#endif
来源：http://dali.dashuyun.cn/Article/details/gtpvryfeft.html

[S31] C++：Hello World
来源：http://dali.cheryme.top/Article/details/gtcuizrpkj.html

#include <iostream>
来源：http://dali.yj202588.top/Article/details/gtmwrgeoyp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nanxuanxn.top/Article/details/gtrnywcjvc.html

[S32] C++：字符串
来源：http://dali.ppjwa.cn/Article/details/gtqzzhuzqz.html

std::string s = "hi";  s += "!";
来源：http://dali.nanxuanxn.top/Article/details/gtghpnvvtg.html

[S33] C++：vector 增删
来源：http://dali.guowangkeji.top/Article/details/gtbrmikljj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tanke756.top/Article/details/gtvhqvooit.html

[S34] C++：遍历 vector
来源：http://dali.fengsongda.top/Article/details/gtehcxqyym.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sysykeji.top/Article/details/gttknobpbn.html

[S35] C++：map
来源：http://dali.zhixingplan.top/Article/details/gtflxbujnr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fengsongda.top/Article/details/gtstxmlgio.html

[S36] C++：unordered_map
来源：http://dali.ivvv.top/Article/details/gtafwlgruz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gtsluljosy.html

[S37] C++：set
来源：http://dali.smart0.xyz/Article/details/gthpxaiyfp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenzaomai.com/Article/details/gtfplcwvkq.html

[S38] C++：排序
来源：http://dali.yanxiufei.cn/Article/details/gtwydyqxpe.html

std::sort(v.begin(), v.end());
来源：http://dali.haohaochexian.top/Article/details/gtuuotoezh.html

[S39] C++：自定义比较器排序
来源：http://dali.0kj1m.cn/Article/details/gtzretvbgv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenjidiqi.icu/Article/details/gtvzfhsixu.html

[S40] C++：查找元素
来源：http://dali.cashguo.top/Article/details/gtpmpdriww.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.fzhhl.top/Article/details/gtjzdqcoag.html

[S41] C++：类与构造函数
来源：http://dali.yangfankeji.com/Article/details/gtjqzmklba.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ivvv.top/Article/details/gtkibypzxu.html

[S42] C++：继承与虚函数
来源：http://dali.cucudq.cn/Article/details/gtfowzsbca.html

class B : public Base { public: void f() override {} };
来源：http://dali.guowangkeji.top/Article/details/gtustukgmw.html

[S43] C++：智能指针
来源：http://dali.jlsjyb.cn/Article/details/gtfvncotqt.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gtzzomuflg.html

[S44] C++：引用传参
来源：http://dali.yanxiufei.cn/Article/details/gtzjxhaagr.html

void inc(int &x) { ++x; }
来源：http://dali.snrcjt.cn/Article/details/gtdgesgfxr.html

[S45] C++：lambda
来源：http://dali.gaohongyu789.top/Article/details/gtvcywrxnt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.snrcjt.cn/Article/details/gtxrnlhsaf.html

[S46] C++：函数模板
来源：http://dali.cucudq.cn/Article/details/gtcuofgbzk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yonumen.top/Article/details/gtslkfzthn.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj20258888.top/Article/details/gtzhwepfko.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhengqikj.top/Article/details/gtjbnoxxpc.html

[S48] C++：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gtgblwwomm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.316326.xyz/Article/details/gtadpvlnld.html

while (std::getline(in, line)) { }
来源：http://dali.yueranfly.top/Article/details/gthvldgcnu.html

[S49] C++：写文件
来源：http://dali.ppjwa.cn/Article/details/gtxxyhreud.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.daria6918.cn/Article/details/gtkcyxpddn.html

[S50] C++：格式化数字
来源：http://dali.andypj.xyz/Article/details/gtxxskdsme.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tanke756.top/Article/details/gtgbrjxjoe.html

[S51] C++：显式类型转换
来源：http://dali.pycfn.com/Article/details/gtmqxyqhrz.html

static_cast<double>(a) / b
来源：http://dali.9152youxi.cn/Article/details/gtnqulnvxw.html

[S52] C++：const 与 noexcept
来源：http://dali.haohaochexian.top/Article/details/gtshmxortw.html

int size() const noexcept { return n_; }
来源：http://dali.ehwqpu.com/Article/details/gtlzxczujc.html

[S53] C++：移动语义
来源：http://dali.fzhhl.top/Article/details/gtlaxcltco.html

std::vector<int> w = std::move(v);
来源：http://dali.xylfe.cn/Article/details/gtsavklrib.html

[S54] C++：异常处理
来源：http://dali.zhoulong.xyz/Article/details/gtbgmpskcl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinqigfzy.top/Article/details/gtedbcfiyv.html

[S55] C++：结构化绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gtykzktgmw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhengqikj.top/Article/details/gtmvvrnusx.html

[S56] C++：optional
来源：http://dali.shangyingyoupin.top/Article/details/gtajvgthmw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.iojbl.cn/Article/details/gtmnpybmko.html

[S57] C++：编译期常量
来源：http://dali.iojbl.cn/Article/details/gtixwsniva.html

constexpr int N = 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkspxizkl.html

[S58] C++：命名空间
来源：http://dali.wangdashe.top/Article/details/gtlmmzjmoc.html

namespace ns { int f() { return 1; } }
来源：http://dali.yueranfly.top/Article/details/gtbhksrmmc.html

[S59] C++：静态断言
来源：http://dali.hywenlv.cn/Article/details/gtknppsuib.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.dashuyun.cn/Article/details/gtvvzczykq.html

[S60] C++：遍历并删除元素
来源：http://dali.zhongyouzk.top/Article/details/gtpnhdlpxk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.aizwys.cn/Article/details/gtyuvtshvq.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtvneffyfm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xylfe.cn/Article/details/gtrfhsbfvg.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtnjhgwjgo.html

[T01] Kotlin：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtjijxehim.html

println("Hello")
来源：http://dali.zhiwuduotai.top/Article/details/gtchxsgqiq.html

[T02] Kotlin：变量
来源：http://dali.zhixingplan.top/Article/details/gtfyzaiocz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhongyouzk.top/Article/details/gtqsnzkmwg.html

[T03] Kotlin：字符串模板
来源：http://dali.hywenlv.cn/Article/details/gtjyqbmzsv.html

"值: $b"
来源：http://dali.fengsongda.top/Article/details/gtkfavyozt.html

[T04] Kotlin：空安全
来源：http://dali.birdmap.top/Article/details/gtubkucexc.html

val n: String? = null;  n?.length
来源：http://dali.hnxiangtu.top/Article/details/gtflhtrkgx.html

[T05] Kotlin：when 表达式
来源：http://dali.gaohongyu789.top/Article/details/gtgllsvmeq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zdqjudy.top/Article/details/gtxtswyhqi.html

[T06] Kotlin：集合映射
来源：http://dali.yuxming.cn/Article/details/gtuvogyjuz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nwbrower.top/Article/details/gtwiydeljd.html

[T07] Kotlin：集合过滤
来源：http://dali.jqgufenzy.top/Article/details/gtsuvvikit.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gaohongyu789.top/Article/details/gttbeiphet.html

[T08] Kotlin：数据类
来源：http://dali.gzhubu.top/Article/details/gtgzyaesds.html

data class User(val name: String, val age: Int)
来源：http://dali.jqgufenzy.top/Article/details/gtemrnailz.html

[T09] Kotlin：扩展函数
来源：http://dali.hfpthk.cn/Article/details/gtivqxpjoy.html

fun String.exclaim() = this + "!"
来源：http://dali.gaohongyu789.top/Article/details/gtphjlsjin.html

[T10] Kotlin：默认参数
来源：http://dali.hnxiangtu.top/Article/details/gtjkwdlmua.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.c1oappe.top/Article/details/gtojbhzryq.html

[T11] Kotlin：协程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlrkwoibp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cdnleiting.top/Article/details/gtqdcbymlk.html

[T12] Kotlin：解构声明
来源：http://dali.cdnleiting.top/Article/details/gtalijttaz.html

val (a, b) = Pair(1, 2)
来源：http://dali.dashuyun.cn/Article/details/gtsawnxcij.html

[T13] Kotlin：只读 Map
来源：http://dali.zhiwuduotai.top/Article/details/gtiubfmovc.html

val m = mapOf("a" to 1)
来源：http://dali.iojbl.cn/Article/details/gtzgwomxcy.html

[T14] Kotlin：循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwieakxox.html

for (i in 1..10) println(i)
来源：http://dali.sxryk.cn/Article/details/gtlagwmzwi.html

[T15] Kotlin：接口
来源：http://dali.daria6918.cn/Article/details/gtlvglpmgo.html

interface Shape { fun area(): Double }
来源：http://dali.gotoacloud.top/Article/details/gtvlqjwvob.html

[T16] Swift：Hello World
来源：http://dali.havefunace.top/Article/details/gtoftjejja.html

print("Hello")
来源：http://dali.zhixingplan.top/Article/details/gthvwifwyr.html

[T17] Swift：变量与常量
来源：http://dali.cheryme.top/Article/details/gtybkxhriv.html

var a = 1;  let b = 2
来源：http://dali.chenjidiqi.icu/Article/details/gtaphxeuie.html

[T18] Swift：字符串插值
来源：http://dali.vqdsnc.cn/Article/details/gtffkrvvbl.html

"值: \(b)"
来源：http://dali.chenzaomai.com/Article/details/gtbdoslpfn.html

[T19] Swift：可选绑定
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmphunqkn.html

if let n = opt { print(n) }
来源：http://dali.hnxiangtu.top/Article/details/gtirtryiug.html

[T20] Swift：数组操作
来源：http://dali.nanxuanxn.top/Article/details/gtbkrqctrp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zycfv.cn/Article/details/gtdqvgypjl.html

[T21] Swift：遍历
来源：http://dali.0kj1m.cn/Article/details/gtaafsnrsd.html

for x in a { print(x) }
来源：http://dali.xuetiantiany.cn/Article/details/gtxdtqwmfd.html

[T22] Swift：字典
来源：http://dali.yonumen.top/Article/details/gtnxstpgve.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yonumen.top/Article/details/gtguwmnacu.html

[T23] Swift：函数
来源：http://dali.cdnleiting.top/Article/details/gtnztvetlx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.iojbl.cn/Article/details/gtiwoszcdu.html

[T24] Swift：闭包
来源：http://dali.sweek.top/Article/details/gtslhwwnwo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtqwjjwguh.html

[T25] Swift：结构体
来源：http://dali.shangyingyoupin.top/Article/details/gtpcrsnive.html

struct P { var x: Int }
来源：http://dali.yongpay.top/Article/details/gtrweecuwr.html

[T26] Swift：类与重写
来源：http://dali.xuetiantiany.cn/Article/details/gtdxijtwvr.html

class A: Base { override func f() {} }
来源：http://dali.jqgufenzy.top/Article/details/gtpkmwmmnh.html

[T27] Swift：错误处理
来源：http://dali.chenlongwang.top/Article/details/gtvtapuolf.html

do { try f() } catch { print(error) }
来源：http://dali.sufxvd.cn/Article/details/gtoxaqlmgj.html

[T28] Swift：枚举
来源：http://dali.quarkkingdee.top/Article/details/gtmqnblpez.html

enum Color { case red, green }
来源：http://dali.yj202588.top/Article/details/gtclkrtsii.html

[T29] Swift：guard 提前返回
来源：http://dali.andypj.xyz/Article/details/gtrzugsgmk.html

guard let x = opt else { return }
来源：http://dali.shangyingyoupin.top/Article/details/gtsnewhcla.html

[T30] Swift：协议
来源：http://dali.aibaodan.cn/Article/details/gtqvindqvq.html

protocol Shape { func area() -> Double }
来源：http://dali.hnqzz.top/Article/details/gtxkapxiob.html

[T31] Lua：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtowgrfort.html

print("Hello")
来源：http://dali.cashguo.top/Article/details/gtjfozgxzo.html

[T32] Lua：局部变量
来源：http://dali.gotoacloud.top/Article/details/gtrklenmms.html

local a = 1
来源：http://dali.gaohongyu789.top/Article/details/gtkxdlssmi.html

[T33] Lua：表（数组）
来源：http://dali.jianghu66.top/Article/details/gtbihiyxjh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xinyue.icu/Article/details/gtpuluxxwc.html

[T34] Lua：遍历表
来源：http://dali.guannengcc.top/Article/details/gtsvcsvarn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gzhubu.top/Article/details/gtymouzgqt.html

[T35] Lua：字典表
来源：http://dali.yuanzhike.top/Article/details/gtcrdlcabr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.andypj.xyz/Article/details/gtnwrlabad.html

[T36] Lua：函数
来源：http://dali.nwbrower.top/Article/details/gtjxgndhqk.html

function add(a, b) return a + b end
来源：http://dali.guowangkeji.top/Article/details/gtzufojuab.html

[T37] Lua：字符串拼接
来源：http://dali.nwbrower.top/Article/details/gtszfqsxxa.html

"a" .. "b"
来源：http://dali.0kj1m.cn/Article/details/gtkijjdaqm.html

[T38] Lua：条件
来源：http://dali.iojbl.cn/Article/details/gtujoqkobg.html

if x > 0 then print("正") end
来源：http://dali.shanyushiyangtech.top/Article/details/gtlhzrpnpo.html

[T39] Lua：模式匹配
来源：http://dali.jqgufenzy.top/Article/details/gtqqbbcdru.html

string.find(s, "%d+")
来源：http://dali.jiagoushi.top/Article/details/gtsdxltbzg.html

[T40] Lua：元表
来源：http://dali.zycfv.cn/Article/details/gtiopieepf.html

setmetatable({}, { __index = base })
来源：http://dali.xylfe.cn/Article/details/gtfbtfogzw.html

[T41] Perl：Hello World
来源：http://dali.cashguo.top/Article/details/gtgugbqhhm.html

print "Hello\n";
来源：http://dali.kuanghao11.cn/Article/details/gtnflsmpba.html

[T42] Perl：变量类型
来源：http://dali.nwbrower.top/Article/details/gtwdujpsiv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cashguo.top/Article/details/gtiaopsbml.html

[T43] Perl：字符串插值
来源：http://dali.vqdsnc.cn/Article/details/gtwgcbmmky.html

"值: $a"
来源：http://dali.jianghu66.top/Article/details/gtwxpjvqla.html

[T44] Perl：条件
来源：http://dali.pengpengdd.cyou/Article/details/gtshgqebgt.html

if ($a > 0) { print "正"; }
来源：http://dali.gotoacloud.top/Article/details/gtiqxrftkm.html

[T45] Perl：数组遍历
来源：http://dali.yuanzhike.top/Article/details/gtvkqmezcg.html

for my $x (@arr) { print $x; }
来源：http://dali.nanxuanxn.top/Article/details/gtpwefnzly.html

[T46] Perl：哈希操作
来源：http://dali.c1oappe.top/Article/details/gtamceylfi.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gzhubu.top/Article/details/gtocdiqwtw.html

[T47] Perl：正则捕获
来源：http://dali.yuanzhike.top/Article/details/gtetgwfxlt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.gotoacloud.top/Article/details/gtovmpmwuu.html

[T48] Perl：正则替换
来源：http://dali.yonumen.top/Article/details/gtafdhxavd.html

$s =~ s/old/new/g;
来源：http://dali.sufxvd.cn/Article/details/gtzinramma.html

[T49] Perl：函数
来源：http://dali.hongshengwenyu.top/Article/details/gtxypendcc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gtfzyeujun.html

[T50] Perl：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtqzthydwz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.aizwys.cn/Article/details/gtcfkzoner.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.dashuyun.cn/Article/details/gtcwaymjnj.html

[T51] Scala：Hello World
来源：http://dali.daxiang520.top/Article/details/gtuqgkqlxy.html

println("Hello")
来源：http://dali.yongpay.top/Article/details/gtyzilpdqu.html

[T52] Scala：变量
来源：http://dali.cqqwz.cn/Article/details/gtffdyonsj.html

val a = 1;  var b = 2
来源：http://dali.meibo888.top/Article/details/gtwvqwctan.html

[T53] Scala：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gtvuwvqhbt.html

s"值: $b"
来源：http://dali.yj202588.top/Article/details/gtqwdqoims.html

[T54] Scala：集合映射
来源：http://dali.jinqigfzy.top/Article/details/gtsprgyxkx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtbxgghhtd.html

[T55] Scala：集合过滤
来源：http://dali.yanxiufei.cn/Article/details/gtvrotqxiq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.tanke756.top/Article/details/gtjnfqxbdx.html

[T56] Scala：样例类
来源：http://dali.xinyue.icu/Article/details/gtsmtknqkd.html

case class User(name: String, age: Int)
来源：http://dali.svipenyu.cn/Article/details/gtobfyzfvf.html

[T57] Scala：模式匹配
来源：http://dali.cucudq.cn/Article/details/gtambcqrzu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.nanxuanxn.top/Article/details/gtejtuotdd.html

[T58] Scala：函数定义
来源：http://dali.yanxiufei.cn/Article/details/gtewhmxjfr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.meibo888.top/Article/details/gtylzhvugd.html

[T59] Scala：循环
来源：http://dali.yuanzhike.top/Article/details/gtmhaobemn.html

for (i <- 1 to 10) println(i)
来源：http://dali.fzhhl.top/Article/details/gtoqeectwo.html

[T60] Scala：折叠
来源：http://dali.hnqzz.top/Article/details/gtvoyadkma.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jinqigufen.top/Article/details/gtpvolepyy.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gthzsixygm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hywenlv.cn/Article/details/gtxxtepkci.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtavufesnn.html

[U01] Py：创建虚拟环境
来源：http://dali.cashguo.top/Article/details/gtatloqwdy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yongpay.top/Article/details/gteiqjqyrl.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yj20258888.top/Article/details/gtqffvdfnv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.nanxinkj.top/Article/details/gtlzbmfkua.html

[U03] Py：加载 .env 配置
来源：http://dali.hysaishi.cn/Article/details/gtdtmxjyre.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.pengpengdd.cyou/Article/details/gtgttozcwo.html

[U04] Py：变量调试打印
来源：http://dali.ydzc1.top/Article/details/gtgzalgrlm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yongpay.top/Article/details/gtqpgeyemf.html

[U05] Py：列表去重且保序
来源：http://dali.guowangkeji.top/Article/details/gtlihthcft.html

list(dict.fromkeys(arr))
来源：http://dali.c1oappe.top/Article/details/gtsdukwtbn.html

[U06] Py：合并两个字典
来源：http://dali.svipenyu.cn/Article/details/gttgkqlnmn.html

{**a, **b}
来源：http://dali.cucudq.cn/Article/details/gtsgtzusot.html

[U07] Py：反转字典键值
来源：http://dali.chenzaomai.com/Article/details/gtclscowhf.html

{v: k for k, v in d.items()}
来源：http://dali.jqgufenzy.top/Article/details/gtlsbxlbhx.html

[U08] Py：展平二维列表
来源：http://dali.hnxiangtu.top/Article/details/gtnfmygtgu.html

[y for x in nested for y in x]
来源：http://dali.jinqigfzy.top/Article/details/gtyoumagjh.html

[U09] Py：字典取最大值的键
来源：http://dali.xinyue.icu/Article/details/gthmynplma.html

max(d, key=d.get)
来源：http://dali.yonumen.top/Article/details/gthhxwlnhd.html

[U10] Py：按值排序字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnklumgah.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sxryk.cn/Article/details/gtnbresgnh.html

[U11] Py：生成器表达式
来源：http://dali.iojbl.cn/Article/details/gthmqrdcrf.html

(x * 2 for x in arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrpfkavhe.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.fzhhl.top/Article/details/gtwxcxeeze.html

Counter(arr).most_common(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtckbmccuh.html

[U13] Py：固定长度队列
来源：http://dali.ybcxt.top/Article/details/gtcbgkbirx.html

deque(maxlen=10)
来源：http://dali.0kj1m.cn/Article/details/gtmohyhvtr.html

[U14] Py：分组收集到列表
来源：http://dali.redwolf501.top/Article/details/gtvksntcsq.html

defaultdict(list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyjjjxlol.html

[U15] Py：高精度计时
来源：http://dali.jinqigfzy.top/Article/details/gtpsfwezth.html

t = time.perf_counter()
来源：http://dali.fzhhl.top/Article/details/gtrqqhjnsz.html

[U16] Py：命令行参数解析
来源：http://dali.yj20258888.top/Article/details/gtpuocueqb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.haohaochexian.top/Article/details/gtablaylqa.html

[U17] Py：初始化日志
来源：http://dali.ehwqpu.com/Article/details/gtenvvbnrt.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.snrcjt.cn/Article/details/gtnrltppom.html

[U18] Py：预编译正则
来源：http://dali.0kj1m.cn/Article/details/gttdzfmqjm.html

pat = re.compile(r"\d+")
来源：http://dali.yuanzhike.top/Article/details/gtoatjpzrv.html

[U19] Py：正则替换带回调
来源：http://dali.yangfankeji.com/Article/details/gtzvkmfrto.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.iojbl.cn/Article/details/gtuyzpqybm.html

[U20] Py：缓存函数结果
来源：http://dali.zhoulong.xyz/Article/details/gtsgxohplq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.fzhhl.top/Article/details/gtqffhbcwb.html


<!-- 参考信息 -->