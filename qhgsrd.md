代发 wailian999

read -rp "请输入: " ans
来源：http://dali.0kj1m.cn/Article/details/gtgmavailc.html

[R78] 交互式菜单
来源：http://dali.pengpengdd.cyou/Article/details/gtemnpvjlp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xuanzx.com/Article/details/gtyoiymvbr.html

[R79] 解析命令行选项
来源：http://dali.ybcxt.top/Article/details/gtipnrpnjk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jqgufenzy.top/Article/details/gtygpwtuzg.html

[R80] 查看脚本执行耗时
来源：http://dali.xziqi.cn/Article/details/gtigyaofwv.html

time ./run.sh
来源：http://dali.yanxiufei.cn/Article/details/gtugazzptb.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtlixbagmu.html

S. C / C++ 专题
来源：http://dali.hfpthk.cn/Article/details/gtwfdguedb.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtcvxfxpok.html

[S01] C：Hello World
来源：http://dali.cheryme.top/Article/details/gtwdbkzobt.html

#include <stdio.h>
来源：http://dali.hnxiangtu.top/Article/details/gtjldfjicr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.daria6918.cn/Article/details/gtkwfuaxpx.html

[S02] C：变量与格式化输出
来源：http://dali.yj20258.top/Article/details/gtvcxkznrp.html

int a = 10; printf("%d\n", a);
来源：http://dali.nanxuanxn.top/Article/details/gtjabazvwp.html

[S03] C：读入整数
来源：http://dali.ydzc1.top/Article/details/gtkzhbhtjd.html

int x; scanf("%d", &x);
来源：http://dali.ppjwa.cn/Article/details/gtftopytzk.html

[S04] C：字符串复制
来源：http://dali.mhx1999.top/Article/details/gtdaylqltn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hnxiangtu.top/Article/details/gtdebvosdd.html

[S05] C：字符串长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtleqoiwic.html

strlen(s)
来源：http://dali.yvedp.cn/Article/details/gtxjemigeq.html

[S06] C：字符串比较
来源：http://dali.fzhhl.top/Article/details/gtcwiqwakx.html

strcmp(a, b) == 0
来源：http://dali.meibo888.top/Article/details/gtldwgdwrh.html

[S07] C：数组遍历求和
来源：http://dali.vqdsnc.cn/Article/details/gtzdkoowkj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hfpthk.cn/Article/details/gtpgogdwdt.html

[S08] C：动态内存分配与释放
来源：http://dali.ydzc1.top/Article/details/gtemzrzdkh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.feifeiyinyue.top/Article/details/gteergvtzs.html

[S09] C：结构体定义与初始化
来源：http://dali.chenzaomai.com/Article/details/gtjqqpiasd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.andypj.xyz/Article/details/gtpbwsudhj.html

[S10] C：指针与解引用
来源：http://dali.sweek.top/Article/details/gtrmxdmjih.html

int *p = &a;  *p = 5;
来源：http://dali.xuetiantiany.cn/Article/details/gtsuqnbjuh.html

[S11] C：逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gtgdxcygtx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.c1oappe.top/Article/details/gthtttnxvg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yanxiufei.cn/Article/details/gtsjaabpnl.html

fclose(f);
来源：http://dali.yvedp.cn/Article/details/gtzqfktwdu.html

[S12] C：写文件
来源：http://dali.jqgufenzy.top/Article/details/gtszktypgm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yanxiufei.cn/Article/details/gtrzltuvbi.html

[S13] C：宏定义
来源：http://dali.dashuyun.cn/Article/details/gtqnpzyqsh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.aibaodan.cn/Article/details/gtznkzixfl.html

[S14] C：枚举
来源：http://dali.jinqigufen.top/Article/details/gtsqgcpahy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yvedp.cn/Article/details/gtpizookho.html

[S15] C：类型转换
来源：http://dali.jinqigfzy.top/Article/details/gtpluutkdf.html

(double) a / b
来源：http://dali.ehwqpu.com/Article/details/gtpyqmervs.html

[S16] C：位操作置位
来源：http://dali.tian-w.cn/Article/details/gtgotcmvpo.html

x |= (1 << 3);
来源：http://dali.gzhubu.top/Article/details/gtjvxvvycc.html

[S17] C：安全拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gtfmkriljx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.wangshuangyany.cn/Article/details/gtsdeeqpfn.html

[S18] C：命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gtbugakxfh.html

int main(int argc, char **argv)
来源：http://dali.cdnleiting.top/Article/details/gtlbjliupk.html

[S19] C：快速排序
来源：http://dali.chenjidiqi.icu/Article/details/gtusozmkcc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.fzhhl.top/Article/details/gttoajoauf.html

[S20] C：二分查找
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmijmyqs.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gtwdhtfmyr.html

[S21] C：字符类别判断
来源：http://dali.dashuyun.cn/Article/details/gtssqsnjck.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.c1oappe.top/Article/details/gtaeumpsok.html

[S22] C：字符串转数字
来源：http://dali.hongshengwenyu.top/Article/details/gtbaztwuvw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hnqzz.top/Article/details/gtiigawtrp.html

[S23] C：随机数
来源：http://dali.sxryk.cn/Article/details/gtqhhhgfwn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsaycexhz.html

[S24] C：获取本地时间
来源：http://dali.hnxiangtu.top/Article/details/gtilekqabp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hnqzz.top/Article/details/gtvckycdwm.html

[S25] C：内存拷贝
来源：http://dali.chenzaomai.com/Article/details/gtkoypyfhu.html

memcpy(dst, src, n);
来源：http://dali.sxryk.cn/Article/details/gtoqttplfc.html

[S26] C：内存清零
来源：http://dali.c1oappe.top/Article/details/gtnkenakgy.html

memset(a, 0, sizeof a);
来源：http://dali.tian-w.cn/Article/details/gttgpjwflo.html

[S27] C：定义常量
来源：http://dali.dashuyun.cn/Article/details/gtxzkjpuci.html

const double PI = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gtsqyyipvo.html

[S28] C：静态变量
来源：http://dali.xuetiantiany.cn/Article/details/gtlenoilmm.html

static int counter = 0;
来源：http://dali.gogol.net.cn/Article/details/gtpkqcghar.html

[S29] C：变参函数
来源：http://dali.jianghu66.top/Article/details/gthvntrokb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.c1oappe.top/Article/details/gtonwkmvbd.html

[S30] C：头文件保护
来源：http://dali.birdmap.top/Article/details/gtsysdueoj.html

#ifndef X_H
来源：http://dali.svipenyu.cn/Article/details/gtrchywqhi.html

#define X_H
来源：http://dali.xuetiantiany.cn/Article/details/gtinwwupgz.html

#endif
来源：http://dali.ydzc1.top/Article/details/gtbsjhrqym.html

[S31] C++：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtohkzpvcm.html

#include <iostream>
来源：http://dali.zycfv.cn/Article/details/gtehizxskm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ppjwa.cn/Article/details/gtxcxnnrin.html

[S32] C++：字符串
来源：http://dali.chenlongwang.top/Article/details/gtpfhiphdj.html

std::string s = "hi";  s += "!";
来源：http://dali.daria6918.cn/Article/details/gtpzxlckpi.html

[S33] C++：vector 增删
来源：http://dali.aibaodan.cn/Article/details/gtjwgmwsgh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zdqjudy.top/Article/details/gtqsikizhr.html

[S34] C++：遍历 vector
来源：http://dali.hysaishi.cn/Article/details/gtrzywlekt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xuanzx.com/Article/details/gtktbqnqbk.html

[S35] C++：map
来源：http://dali.hywenlv.cn/Article/details/gtlgauflwg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ivvv.top/Article/details/gtkjqtutlv.html

[S36] C++：unordered_map
来源：http://dali.hongshengwenyu.top/Article/details/gtnmjordbs.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gtietbkrct.html

[S37] C++：set
来源：http://dali.cdnleiting.top/Article/details/gtpyavihqq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.pycfn.com/Article/details/gtdbpbqbqf.html

[S38] C++：排序
来源：http://dali.jianghu66.top/Article/details/gtwnoqachg.html

std::sort(v.begin(), v.end());
来源：http://dali.ppjwa.cn/Article/details/gtcyqviexk.html

[S39] C++：自定义比较器排序
来源：http://dali.9152youxi.cn/Article/details/gtrwqjaalu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cqqwz.cn/Article/details/gtqyulaewd.html

[S40] C++：查找元素
来源：http://dali.sxryk.cn/Article/details/gtmpmoputl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ybcxt.top/Article/details/gtqisyfrdi.html

[S41] C++：类与构造函数
来源：http://dali.jianghu66.top/Article/details/gtxxyxxqgx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cheryme.top/Article/details/gtfjlgmxns.html

[S42] C++：继承与虚函数
来源：http://dali.xziqi.cn/Article/details/gtyyqyccne.html

class B : public Base { public: void f() override {} };
来源：http://dali.hammf.cn/Article/details/gtlwkuysih.html

[S43] C++：智能指针
来源：http://dali.guowangkeji.top/Article/details/gthzfwnsum.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrllcvvki.html

[S44] C++：引用传参
来源：http://dali.vqdsnc.cn/Article/details/gtbbjiehop.html

void inc(int &x) { ++x; }
来源：http://dali.jlsjyb.cn/Article/details/gtawcykopg.html

[S45] C++：lambda
来源：http://dali.nwbrower.top/Article/details/gtxcdrwevd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj202588.top/Article/details/gtqxzwjvfj.html

[S46] C++：函数模板
来源：http://dali.redwolf501.top/Article/details/gtkwwzlbsy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.svipenyu.cn/Article/details/gttagqdsjb.html

[S47] C++：结构化绑定遍历
来源：http://dali.aizwys.cn/Article/details/gtryxlhjor.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sxryk.cn/Article/details/gtcbecfwxn.html

[S48] C++：逐行读文件
来源：http://dali.c1oappe.top/Article/details/gtycgfwwcz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yuxming.cn/Article/details/gtxkdkeunp.html

while (std::getline(in, line)) { }
来源：http://dali.ivvv.top/Article/details/gtudwwrexd.html

[S49] C++：写文件
来源：http://dali.havefunace.top/Article/details/gtsdpiwwgr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.fengsongda.top/Article/details/gtwyskuhsr.html

[S50] C++：格式化数字
来源：http://dali.chenlongwang.top/Article/details/gtpbmqmiqz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnlfviaxe.html

[S51] C++：显式类型转换
来源：http://dali.jiagoushi.top/Article/details/gtqmjbumbf.html

static_cast<double>(a) / b
来源：http://dali.jqgfzy.top/Article/details/gtrlgpbwok.html

[S52] C++：const 与 noexcept
来源：http://dali.9152youxi.cn/Article/details/gtpgkhmshc.html

int size() const noexcept { return n_; }
来源：http://dali.dashuyun.cn/Article/details/gtdwonkgum.html

[S53] C++：移动语义
来源：http://dali.jinqigufen.top/Article/details/gtklpgcpzj.html

std::vector<int> w = std::move(v);
来源：http://dali.yj20258.top/Article/details/gtihxhcapp.html

[S54] C++：异常处理
来源：http://dali.mhx1999.top/Article/details/gtwgykrvin.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.birdmap.top/Article/details/gterwbwwjn.html

[S55] C++：结构化绑定
来源：http://dali.chenlongwang.top/Article/details/gtncpsfkxc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.pycfn.com/Article/details/gtbhoaxjlh.html

[S56] C++：optional
来源：http://dali.sysykeji.top/Article/details/gttigijulq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.haohaochexian.top/Article/details/gtcyipxzcg.html

[S57] C++：编译期常量
来源：http://dali.nanxinkj.top/Article/details/gtzdmkmiak.html

constexpr int N = 10;
来源：http://dali.xinyue.icu/Article/details/gtmeoakiwb.html

[S58] C++：命名空间
来源：http://dali.yongpay.top/Article/details/gtbnpdeszk.html

namespace ns { int f() { return 1; } }
来源：http://dali.hongshengwenyu.top/Article/details/gtktxrmwke.html

[S59] C++：静态断言
来源：http://dali.xinyue.icu/Article/details/gtxsmugivz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xinyue.icu/Article/details/gtqztqhfze.html

[S60] C++：遍历并删除元素
来源：http://dali.meibo888.top/Article/details/gtqavttzai.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhixingplan.top/Article/details/gtwajovckn.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtjrvsaufp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aibaodan.cn/Article/details/gtghtqmldr.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtpswdoawy.html

[T01] Kotlin：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtnyvxeqpr.html

println("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbkfblomm.html

[T02] Kotlin：变量
来源：http://dali.jinghuilouyu.cn/Article/details/gttfdyflnz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.daria6918.cn/Article/details/gttafeadzc.html

[T03] Kotlin：字符串模板
来源：http://dali.wangdashe.top/Article/details/gtyvwcatsc.html

"值: $b"
来源：http://dali.ppjwa.cn/Article/details/gtvvwmmvqm.html

[T04] Kotlin：空安全
来源：http://dali.quarkkingdee.top/Article/details/gtjldxulex.html

val n: String? = null;  n?.length
来源：http://dali.xylfe.cn/Article/details/gtvpskardq.html

[T05] Kotlin：when 表达式
来源：http://dali.quarkkingdee.top/Article/details/gtvghqezsp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.c1oappe.top/Article/details/gtxtydrrtd.html

[T06] Kotlin：集合映射
来源：http://dali.cashguo.top/Article/details/gtxunhrnxx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yuanzhike.top/Article/details/gtntlucjwz.html

[T07] Kotlin：集合过滤
来源：http://dali.fzhhl.top/Article/details/gtljkhejwq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnvybfzox.html

[T08] Kotlin：数据类
来源：http://dali.hfpthk.cn/Article/details/gtekssxfcv.html

data class User(val name: String, val age: Int)
来源：http://dali.nwbrower.top/Article/details/gtmclijspy.html

[T09] Kotlin：扩展函数
来源：http://dali.zycfv.cn/Article/details/gtqxogulwo.html

fun String.exclaim() = this + "!"
来源：http://dali.yj202588.top/Article/details/gttzonscwl.html

[T10] Kotlin：默认参数
来源：http://dali.yongpay.top/Article/details/gtcbpusrbg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.aizwys.cn/Article/details/gtgoruawlj.html

[T11] Kotlin：协程
来源：http://dali.birdmap.top/Article/details/gthvzfrfbx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xinyue.icu/Article/details/gtzszcizyg.html

[T12] Kotlin：解构声明
来源：http://dali.jlsjyb.cn/Article/details/gtcycobmyw.html

val (a, b) = Pair(1, 2)
来源：http://dali.yj20258888.top/Article/details/gtngxhdhhv.html

[T13] Kotlin：只读 Map
来源：http://dali.ydzc1.top/Article/details/gtqfsbaegy.html

val m = mapOf("a" to 1)
来源：http://dali.yangfankeji.com/Article/details/gtcqlrfbwj.html

[T14] Kotlin：循环
来源：http://dali.yuanzhike.top/Article/details/gtwmtmkpik.html

for (i in 1..10) println(i)
来源：http://dali.yvedp.cn/Article/details/gtgztevjtc.html

[T15] Kotlin：接口
来源：http://dali.daxiang520.top/Article/details/gtrbcxjiac.html

interface Shape { fun area(): Double }
来源：http://dali.iojbl.cn/Article/details/gtayizmzek.html

[T16] Swift：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtimissycw.html

print("Hello")
来源：http://dali.chenlongwang.top/Article/details/gtgjotzdis.html

[T17] Swift：变量与常量
来源：http://dali.yongpay.top/Article/details/gtsqieoute.html

var a = 1;  let b = 2
来源：http://dali.jyoumei.cn/Article/details/gthhhephqw.html

[T18] Swift：字符串插值
来源：http://dali.fengsongda.top/Article/details/gtdbgbyhap.html

"值: \(b)"
来源：http://dali.nwbrower.top/Article/details/gtnklcxdfj.html

[T19] Swift：可选绑定
来源：http://dali.mhx1999.top/Article/details/gtnymyvovg.html

if let n = opt { print(n) }
来源：http://dali.xuanzx.com/Article/details/gtwegieoiu.html

[T20] Swift：数组操作
来源：http://dali.ppjwa.cn/Article/details/gtzgfsnfti.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.birdmap.top/Article/details/gteivyjchl.html

[T21] Swift：遍历
来源：http://dali.redwolf501.top/Article/details/gtfdcviyzc.html

for x in a { print(x) }
来源：http://dali.havefunace.top/Article/details/gtbewcrhzm.html

[T22] Swift：字典
来源：http://dali.cucudq.cn/Article/details/gtryoqodch.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zdqjudy.top/Article/details/gttowitmqj.html

[T23] Swift：函数
来源：http://dali.hysaishi.cn/Article/details/gtqbcjcwvf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.aibaodan.cn/Article/details/gtoivbgkrv.html

[T24] Swift：闭包
来源：http://dali.dianchejie.cn/Article/details/gtgmdxdyhv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.tianlin.xyz/Article/details/gtuftoiqsb.html

[T25] Swift：结构体
来源：http://dali.vqdsnc.cn/Article/details/gtzmndntfl.html

struct P { var x: Int }
来源：http://dali.jiagoushi.top/Article/details/gtaessotsl.html

[T26] Swift：类与重写
来源：http://dali.yuxming.cn/Article/details/gtdmkdpqfk.html

class A: Base { override func f() {} }
来源：http://dali.birdmap.top/Article/details/gtrpwzuumc.html

[T27] Swift：错误处理
来源：http://dali.svipenyu.cn/Article/details/gtvloakvsa.html

do { try f() } catch { print(error) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtizoiuizy.html

[T28] Swift：枚举
来源：http://dali.jianghu66.top/Article/details/gtteuyetek.html

enum Color { case red, green }
来源：http://dali.yongpay.top/Article/details/gtgonwnwmn.html

[T29] Swift：guard 提前返回
来源：http://dali.sweek.top/Article/details/gtggbhuxds.html

guard let x = opt else { return }
来源：http://dali.chenjidiqi.icu/Article/details/gtwqththgr.html

[T30] Swift：协议
来源：http://dali.nanxinkj.top/Article/details/gtbotmxqvt.html

protocol Shape { func area() -> Double }
来源：http://dali.andypj.xyz/Article/details/gtzhgyuibj.html

[T31] Lua：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtfqrjmjlh.html

print("Hello")
来源：http://dali.haohaochexian.top/Article/details/gtosiqsaib.html

[T32] Lua：局部变量
来源：http://dali.xylfe.cn/Article/details/gturfkkqpl.html

local a = 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtcwdvpbph.html

[T33] Lua：表（数组）
来源：http://dali.hysaishi.cn/Article/details/gtfxkhpsvz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.gzhubu.top/Article/details/gtgbpbexey.html

[T34] Lua：遍历表
来源：http://dali.meibo888.top/Article/details/gtymafkctf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hnxiangtu.top/Article/details/gtjaqfatlq.html

[T35] Lua：字典表
来源：http://dali.cqqwz.cn/Article/details/gtgcnexwfr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ybcxt.top/Article/details/gtbcobvgjr.html

[T36] Lua：函数
来源：http://dali.ydzc1.top/Article/details/gtytccqrcr.html

function add(a, b) return a + b end
来源：http://dali.shuidangran.top/Article/details/gtkzvvqfdi.html

[T37] Lua：字符串拼接
来源：http://dali.hnqzz.top/Article/details/gtkiftdemu.html

"a" .. "b"
来源：http://dali.yj20258888.top/Article/details/gtzprzeaaa.html

[T38] Lua：条件
来源：http://dali.hfpthk.cn/Article/details/gtpbakuwir.html

if x > 0 then print("正") end
来源：http://dali.ehwqpu.com/Article/details/gtycdqcmij.html

[T39] Lua：模式匹配
来源：http://dali.xylfe.cn/Article/details/gthjkzqiro.html

string.find(s, "%d+")
来源：http://dali.cdnleiting.top/Article/details/gtfayyulus.html

[T40] Lua：元表
来源：http://dali.hfpthk.cn/Article/details/gtutarunzm.html

setmetatable({}, { __index = base })
来源：http://dali.tanke756.top/Article/details/gtmfbkbmph.html

[T41] Perl：Hello World
来源：http://dali.ivvv.top/Article/details/gtahqolkkf.html

print "Hello\n";
来源：http://dali.nwbrower.top/Article/details/gtfylhikof.html

[T42] Perl：变量类型
来源：http://dali.cheryme.top/Article/details/gtifcjpttq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.svipenyu.cn/Article/details/gtadkqjyqz.html

[T43] Perl：字符串插值
来源：http://dali.wangdashe.top/Article/details/gtapjvdcnq.html

"值: $a"
来源：http://dali.gzhubu.top/Article/details/gtjhkoanvy.html

[T44] Perl：条件
来源：http://dali.dashuyun.cn/Article/details/gteyusltrw.html

if ($a > 0) { print "正"; }
来源：http://dali.yuanzhike.top/Article/details/gtjmrvrkpe.html

[T45] Perl：数组遍历
来源：http://dali.iojbl.cn/Article/details/gtaexlbkwp.html

for my $x (@arr) { print $x; }
来源：http://dali.gzhubu.top/Article/details/gtqiakodok.html

[T46] Perl：哈希操作
来源：http://dali.fzhhl.top/Article/details/gtjkgrqgio.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtgmmajcyh.html

[T47] Perl：正则捕获
来源：http://dali.hnqzz.top/Article/details/gtwqblpzlh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.aibaodan.cn/Article/details/gthvwwflwg.html

[T48] Perl：正则替换
来源：http://dali.jianghu66.top/Article/details/gtqimamvrq.html

$s =~ s/old/new/g;
来源：http://dali.daxiang520.top/Article/details/gticfcenmn.html

[T49] Perl：函数
来源：http://dali.jyoumei.cn/Article/details/gtzujwgpbt.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.pycfn.com/Article/details/gtdcqfmdwp.html

[T50] Perl：逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gtbknsruhl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.pycfn.com/Article/details/gtaishmnpj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.316326.xyz/Article/details/gtzuforyco.html

[T51] Scala：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtrxgdvrys.html

println("Hello")
来源：http://dali.hnqzz.top/Article/details/gtbobtquky.html

[T52] Scala：变量
来源：http://dali.guannengcc.top/Article/details/gtvxrlqbov.html

val a = 1;  var b = 2
来源：http://dali.xylfe.cn/Article/details/gtuxcbbahi.html

[T53] Scala：字符串插值
来源：http://dali.jqgfzy.top/Article/details/gtccjrpxft.html

s"值: $b"
来源：http://dali.wangdashe.top/Article/details/gtoqjkxbcs.html

[T54] Scala：集合映射
来源：http://dali.shangyingyoupin.top/Article/details/gtqgjhdwtu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.dianchejie.cn/Article/details/gtvjdixumd.html

[T55] Scala：集合过滤
来源：http://dali.tian-w.cn/Article/details/gtlykzlweo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.guannengcc.top/Article/details/gtxajqtoup.html

[T56] Scala：样例类
来源：http://dali.fzhhl.top/Article/details/gtbzvpvjrb.html

case class User(name: String, age: Int)
来源：http://dali.hnqzz.top/Article/details/gtbruvttmt.html

[T57] Scala：模式匹配
来源：http://dali.guannengcc.top/Article/details/gtoiavukzt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhixingplan.top/Article/details/gttzxzcebb.html

[T58] Scala：函数定义
来源：http://dali.daxiang520.top/Article/details/gtycjxrxqq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gteqnywplh.html

[T59] Scala：循环
来源：http://dali.dianchejie.cn/Article/details/gtfijlttou.html

for (i <- 1 to 10) println(i)
来源：http://dali.hammf.cn/Article/details/gthamkedfk.html

[T60] Scala：折叠
来源：http://dali.cdnleiting.top/Article/details/gtfojhglnd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.fzhhl.top/Article/details/gtsxgzevhx.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtbudfkmov.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhoulong.xyz/Article/details/gtggraugnp.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtapekhzhz.html

[U01] Py：创建虚拟环境
来源：http://dali.bjfxy.top/Article/details/gttacqdclv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jinqigufen.top/Article/details/gtyyqdzazf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yvedp.cn/Article/details/gtemakxyny.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.quarkkingdee.top/Article/details/gthbgjlnqs.html

[U03] Py：加载 .env 配置
来源：http://dali.vqdsnc.cn/Article/details/gtkbyzgclj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hfpthk.cn/Article/details/gtxeyaqmtx.html

[U04] Py：变量调试打印
来源：http://dali.shanyushiyangtech.top/Article/details/gtyhmugksi.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaptdkjaj.html

[U05] Py：列表去重且保序
来源：http://dali.zycfv.cn/Article/details/gtzxanjqau.html

list(dict.fromkeys(arr))
来源：http://dali.jyoumei.cn/Article/details/gtbsjzjhgp.html

[U06] Py：合并两个字典
来源：http://dali.shuidangran.top/Article/details/gtwkavgrib.html

{**a, **b}
来源：http://dali.tian-w.cn/Article/details/gtsywnmjal.html

[U07] Py：反转字典键值
来源：http://dali.zhengqikj.top/Article/details/gtdaxfxlxw.html

{v: k for k, v in d.items()}
来源：http://dali.zycfv.cn/Article/details/gteendjpxy.html

[U08] Py：展平二维列表
来源：http://dali.chenlongwang.top/Article/details/gtkmfpmmpz.html

[y for x in nested for y in x]
来源：http://dali.daxiang520.top/Article/details/gtwsdfmdcs.html

[U09] Py：字典取最大值的键
来源：http://dali.xziqi.cn/Article/details/gthgszctyk.html

max(d, key=d.get)
来源：http://dali.wangshuangyany.cn/Article/details/gtdxehinvh.html

[U10] Py：按值排序字典
来源：http://dali.andypj.xyz/Article/details/gttzznygdi.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ybcxt.top/Article/details/gtdtmgeznp.html

[U11] Py：生成器表达式
来源：http://dali.hysaishi.cn/Article/details/gttiapdczn.html

(x * 2 for x in arr)
来源：http://dali.smart0.xyz/Article/details/gtvkcekutt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.kuanghao11.cn/Article/details/gtxydfdguz.html

Counter(arr).most_common(3)
来源：http://dali.zhixingplan.top/Article/details/gthatupfbs.html

[U13] Py：固定长度队列
来源：http://dali.nanxuanxn.top/Article/details/gtthyzwdtg.html

deque(maxlen=10)
来源：http://dali.jqgfzy.top/Article/details/gtadazjbru.html

[U14] Py：分组收集到列表
来源：http://dali.meibo888.top/Article/details/gtapjnqjky.html

defaultdict(list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqncysame.html

[U15] Py：高精度计时
来源：http://dali.smart0.xyz/Article/details/gtgktckxnd.html

t = time.perf_counter()
来源：http://dali.jinghuilouyu.cn/Article/details/gtkpubdygw.html

[U16] Py：命令行参数解析
来源：http://dali.jinyuanbaomall.cn/Article/details/gtizxtuobo.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jqgfzy.top/Article/details/gtrulosfcr.html

[U17] Py：初始化日志
来源：http://dali.shzxlz.cn/Article/details/gtiywxzfaa.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.nanxuanxn.top/Article/details/gtjlamzsqt.html

[U18] Py：预编译正则
来源：http://dali.yj20258888.top/Article/details/gtscscbfbe.html

pat = re.compile(r"\d+")
来源：http://dali.9152youxi.cn/Article/details/gtmfqdpfhk.html


<!-- 参考信息 -->