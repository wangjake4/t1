代发 wailian999

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yonumen.top/Article/details/gtiylfdwjr.html

[R80] 查看脚本执行耗时
来源：http://dali.yvedp.cn/Article/details/gtmxeojccn.html

time ./run.sh
来源：http://dali.jqgufenzy.top/Article/details/gtbllcaxuk.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtybztcumy.html

S. C / C++ 专题
来源：http://dali.zhengqikj.top/Article/details/gthucszqpn.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtxgvshtai.html

[S01] C：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtwywaophs.html

#include <stdio.h>
来源：http://dali.cdnleiting.top/Article/details/gtnyebccwq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hysaishi.cn/Article/details/gtsvlmatfj.html

[S02] C：变量与格式化输出
来源：http://dali.dashuyun.cn/Article/details/gtgmkssgsr.html

int a = 10; printf("%d\n", a);
来源：http://dali.andypj.xyz/Article/details/gtzshkibfg.html

[S03] C：读入整数
来源：http://dali.havefunace.top/Article/details/gtwaoviqvw.html

int x; scanf("%d", &x);
来源：http://dali.tanke756.top/Article/details/gttjhilvsh.html

[S04] C：字符串复制
来源：http://dali.wangshuangyany.cn/Article/details/gtlbrhcimr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shangyingyoupin.top/Article/details/gtgdddwctv.html

[S05] C：字符串长度
来源：http://dali.gogol.net.cn/Article/details/gtcpsdeggk.html

strlen(s)
来源：http://dali.nanxuanxn.top/Article/details/gtsjwbkyfn.html

[S06] C：字符串比较
来源：http://dali.bjfxy.top/Article/details/gtfwzkrgya.html

strcmp(a, b) == 0
来源：http://dali.jqgufenzy.top/Article/details/gtzxjieyvt.html

[S07] C：数组遍历求和
来源：http://dali.zhiwuduotai.top/Article/details/gtiizadide.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhoulong.xyz/Article/details/gtqkukbwkc.html

[S08] C：动态内存分配与释放
来源：http://dali.ybcxt.top/Article/details/gtlbowurxg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jyoumei.cn/Article/details/gtmukjrxad.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gtgajobzmt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ivvv.top/Article/details/gtegcnokpl.html

[S10] C：指针与解引用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtndsgrzls.html

int *p = &a;  *p = 5;
来源：http://dali.0kj1m.cn/Article/details/gtuhlgifjj.html

[S11] C：逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gtgervgndw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yuanzhike.top/Article/details/gtxjmwveax.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yueranfly.top/Article/details/gtvyyrmvyj.html

fclose(f);
来源：http://dali.fzhhl.top/Article/details/gtcuwcltai.html

[S12] C：写文件
来源：http://dali.jinqigufen.top/Article/details/gtnhaafdoj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sxryk.cn/Article/details/gtmxbzbcof.html

[S13] C：宏定义
来源：http://dali.yj202588.top/Article/details/gtiowxduxy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinqigfzy.top/Article/details/gtpatzttnf.html

[S14] C：枚举
来源：http://dali.quarkkingdee.top/Article/details/gtoogzovip.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.birdmap.top/Article/details/gtnztcplrv.html

[S15] C：类型转换
来源：http://dali.hongshengwenyu.top/Article/details/gtaporgvbc.html

(double) a / b
来源：http://dali.wangshuangyany.cn/Article/details/gtwfzvneny.html

[S16] C：位操作置位
来源：http://dali.andypj.xyz/Article/details/gthkcpfxot.html

x |= (1 << 3);
来源：http://dali.jinqigufen.top/Article/details/gtyuorbilu.html

[S17] C：安全拼接字符串
来源：http://dali.hywenlv.cn/Article/details/gtieimcccq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.fzhhl.top/Article/details/gtdasqekyu.html

[S18] C：命令行参数
来源：http://dali.shangyingyoupin.top/Article/details/gtcpjoqsej.html

int main(int argc, char **argv)
来源：http://dali.yangfankeji.com/Article/details/gtbrwvsrsz.html

[S19] C：快速排序
来源：http://dali.jqgfzy.top/Article/details/gtcnxfttyb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hfpthk.cn/Article/details/gtqnkrmvnn.html

[S20] C：二分查找
来源：http://dali.jinqigufen.top/Article/details/gtfoupiyqq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tanke756.top/Article/details/gtjbrfpjsr.html

[S21] C：字符类别判断
来源：http://dali.meibo888.top/Article/details/gtmopeagmf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yuanzhike.top/Article/details/gtxelokcpj.html

[S22] C：字符串转数字
来源：http://dali.gzhubu.top/Article/details/gtxxfljjqd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj20258888.top/Article/details/gtryeicuuh.html

[S23] C：随机数
来源：http://dali.chenlongwang.top/Article/details/gtajoymbju.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.aizwys.cn/Article/details/gtqlvywyod.html

[S24] C：获取本地时间
来源：http://dali.smart0.xyz/Article/details/gthzdsvdzd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj20258888.top/Article/details/gtultbbmcp.html

[S25] C：内存拷贝
来源：http://dali.aizwys.cn/Article/details/gtbxlszdyx.html

memcpy(dst, src, n);
来源：http://dali.redwolf501.top/Article/details/gtdgbryadw.html

[S26] C：内存清零
来源：http://dali.daria6918.cn/Article/details/gtfwyjpnbd.html

memset(a, 0, sizeof a);
来源：http://dali.zhiwuduotai.top/Article/details/gtunoedydd.html

[S27] C：定义常量
来源：http://dali.xuanzx.com/Article/details/gtndglitem.html

const double PI = 3.14159;
来源：http://dali.hammf.cn/Article/details/gtofcsleha.html

[S28] C：静态变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzmdxjnqo.html

static int counter = 0;
来源：http://dali.guowangkeji.top/Article/details/gtpibldtzu.html

[S29] C：变参函数
来源：http://dali.jiagoushi.top/Article/details/gtkugdyvjg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hongshengwenyu.top/Article/details/gttttrwqfv.html

[S30] C：头文件保护
来源：http://dali.ehwqpu.com/Article/details/gtkzsabvva.html

#ifndef X_H
来源：http://dali.mhx1999.top/Article/details/gtohssiunm.html

#define X_H
来源：http://dali.daria6918.cn/Article/details/gtcnrcelyi.html

#endif
来源：http://dali.tanke756.top/Article/details/gtlerdyjlh.html

[S31] C++：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtteigerru.html

#include <iostream>
来源：http://dali.kuanghao11.cn/Article/details/gtdcnoifmo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.havefunace.top/Article/details/gtytarurfs.html

[S32] C++：字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtksfqmkbg.html

std::string s = "hi";  s += "!";
来源：http://dali.kuanghao11.cn/Article/details/gtoodmjguj.html

[S33] C++：vector 增删
来源：http://dali.gzhubu.top/Article/details/gttdmuzmcb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jqgufenzy.top/Article/details/gtmsviwyot.html

[S34] C++：遍历 vector
来源：http://dali.yj20258888.top/Article/details/gtjfoedypy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hammf.cn/Article/details/gtgdbqrjqd.html

[S35] C++：map
来源：http://dali.jyoumei.cn/Article/details/gtjkenhvvg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ydzc1.top/Article/details/gtlpatouzl.html

[S36] C++：unordered_map
来源：http://dali.yj20258.top/Article/details/gtpifcwftv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cdnleiting.top/Article/details/gtryinkdfi.html

[S37] C++：set
来源：http://dali.yonumen.top/Article/details/gtpbdkvmru.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yuanzhike.top/Article/details/gtoetexlgs.html

[S38] C++：排序
来源：http://dali.havefunace.top/Article/details/gtvpoxikfa.html

std::sort(v.begin(), v.end());
来源：http://dali.jinqigfzy.top/Article/details/gtlckafizd.html

[S39] C++：自定义比较器排序
来源：http://dali.yvedp.cn/Article/details/gtbqkbonto.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sxryk.cn/Article/details/gtyvpksimg.html

[S40] C++：查找元素
来源：http://dali.gaohongyu789.top/Article/details/gtvxjnebbe.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jyoumei.cn/Article/details/gtlenumipa.html

[S41] C++：类与构造函数
来源：http://dali.hnqzz.top/Article/details/gtgzuzohfr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nanxinkj.top/Article/details/gtuijnwxuq.html

[S42] C++：继承与虚函数
来源：http://dali.chenjidiqi.icu/Article/details/gtjouiwdjb.html

class B : public Base { public: void f() override {} };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqztbkfkg.html

[S43] C++：智能指针
来源：http://dali.sweek.top/Article/details/gtfeieszuc.html

auto p = std::make_unique<int>(5);
来源：http://dali.jianghu66.top/Article/details/gttsssjrou.html

[S44] C++：引用传参
来源：http://dali.yuanzhike.top/Article/details/gtzbpqfjpb.html

void inc(int &x) { ++x; }
来源：http://dali.9152youxi.cn/Article/details/gtbwufvflc.html

[S45] C++：lambda
来源：http://dali.zycfv.cn/Article/details/gthvqyeugo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhengqikj.top/Article/details/gthzznhuho.html

[S46] C++：函数模板
来源：http://dali.meibo888.top/Article/details/gtkypwfdlp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.0kj1m.cn/Article/details/gtpkodfddr.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhixingplan.top/Article/details/gtrwagoalc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cheryme.top/Article/details/gtkqajodnp.html

[S48] C++：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gtktvwdwyn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj20258888.top/Article/details/gtfvofqrku.html

while (std::getline(in, line)) { }
来源：http://dali.shangyingyoupin.top/Article/details/gtxsxhgnor.html

[S49] C++：写文件
来源：http://dali.guowangkeji.top/Article/details/gtzmcgerrl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.feifeiyinyue.top/Article/details/gtbvljsypk.html

[S50] C++：格式化数字
来源：http://dali.hysaishi.cn/Article/details/gtgrfjnuec.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ybcxt.top/Article/details/gtpfrvigyc.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gtrvczwcud.html

static_cast<double>(a) / b
来源：http://dali.haohaochexian.top/Article/details/gtmacdydqd.html

[S52] C++：const 与 noexcept
来源：http://dali.yvedp.cn/Article/details/gtfdvakmmy.html

int size() const noexcept { return n_; }
来源：http://dali.jqgfzy.top/Article/details/gtxsrjxpye.html

[S53] C++：移动语义
来源：http://dali.havefunace.top/Article/details/gtkrbqdyyt.html

std::vector<int> w = std::move(v);
来源：http://dali.jyoumei.cn/Article/details/gtylrmfabh.html

[S54] C++：异常处理
来源：http://dali.hnqzz.top/Article/details/gtzfiwbzeo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jqgufenzy.top/Article/details/gtysgfhjuw.html

[S55] C++：结构化绑定
来源：http://dali.zhixingplan.top/Article/details/gtcrihddjw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzmqkgvri.html

[S56] C++：optional
来源：http://dali.svipenyu.cn/Article/details/gtggowjtfo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cqqwz.cn/Article/details/gtxojbxeyy.html

[S57] C++：编译期常量
来源：http://dali.yonumen.top/Article/details/gtaqhwxuwe.html

constexpr int N = 10;
来源：http://dali.jqgufenzy.top/Article/details/gtrumhdfza.html

[S58] C++：命名空间
来源：http://dali.cdnleiting.top/Article/details/gtckmyftsz.html

namespace ns { int f() { return 1; } }
来源：http://dali.hongshengwenyu.top/Article/details/gtuzpfgtwy.html

[S59] C++：静态断言
来源：http://dali.hysaishi.cn/Article/details/gtvdvaqmuo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gzhubu.top/Article/details/gtvkpykfqp.html

[S60] C++：遍历并删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gtolgdxysi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zycfv.cn/Article/details/gtkonzsxgd.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gteerxdblv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.haohaochexian.top/Article/details/gtbonrbxzr.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtuyjuywap.html

[T01] Kotlin：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtousllneu.html

println("Hello")
来源：http://dali.cdnleiting.top/Article/details/gtdkkfokoy.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gttyqotzmo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xylfe.cn/Article/details/gtabmrfwoc.html

[T03] Kotlin：字符串模板
来源：http://dali.xuetiantiany.cn/Article/details/gtywbgxcfj.html

"值: $b"
来源：http://dali.jinghuilouyu.cn/Article/details/gtozslgdei.html

[T04] Kotlin：空安全
来源：http://dali.yanxiufei.cn/Article/details/gttjijsfpz.html

val n: String? = null;  n?.length
来源：http://dali.nwbrower.top/Article/details/gtzexkxmsw.html

[T05] Kotlin：when 表达式
来源：http://dali.havefunace.top/Article/details/gtvjypmenr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.nanxinkj.top/Article/details/gtbvpzcahv.html

[T06] Kotlin：集合映射
来源：http://dali.gogol.net.cn/Article/details/gtasleekso.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hnqzz.top/Article/details/gtknhghgdm.html

[T07] Kotlin：集合过滤
来源：http://dali.guowangkeji.top/Article/details/gtpikgeosl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.kuanghao11.cn/Article/details/gtivfhqccy.html

[T08] Kotlin：数据类
来源：http://dali.kuanghao11.cn/Article/details/gtupsdgrti.html

data class User(val name: String, val age: Int)
来源：http://dali.birdmap.top/Article/details/gthenkdnio.html

[T09] Kotlin：扩展函数
来源：http://dali.yueranfly.top/Article/details/gtcljfhfnx.html

fun String.exclaim() = this + "!"
来源：http://dali.gotoacloud.top/Article/details/gtebpjweum.html

[T10] Kotlin：默认参数
来源：http://dali.snrcjt.cn/Article/details/gtizegtrpu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.daria6918.cn/Article/details/gtgsqeatcf.html

[T11] Kotlin：协程
来源：http://dali.9152youxi.cn/Article/details/gtezhgdypk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yangfankeji.com/Article/details/gtakhzmebu.html

[T12] Kotlin：解构声明
来源：http://dali.zhoulong.xyz/Article/details/gtbgeeqczf.html

val (a, b) = Pair(1, 2)
来源：http://dali.xinyue.icu/Article/details/gtugtmqcrg.html

[T13] Kotlin：只读 Map
来源：http://dali.jlsjyb.cn/Article/details/gtczkyyaom.html

val m = mapOf("a" to 1)
来源：http://dali.gzhubu.top/Article/details/gthfohyzuc.html

[T14] Kotlin：循环
来源：http://dali.xuanzx.com/Article/details/gtwnnorrcc.html

for (i in 1..10) println(i)
来源：http://dali.xziqi.cn/Article/details/gtnmipynbq.html

[T15] Kotlin：接口
来源：http://dali.cashguo.top/Article/details/gtcvujzttd.html

interface Shape { fun area(): Double }
来源：http://dali.pycfn.com/Article/details/gthgdhenqx.html

[T16] Swift：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtfwgypjtk.html

print("Hello")
来源：http://dali.daria6918.cn/Article/details/gtwxfcnpcp.html

[T17] Swift：变量与常量
来源：http://dali.zdqjudy.top/Article/details/gtwjapbcuj.html

var a = 1;  let b = 2
来源：http://dali.nwbrower.top/Article/details/gtbsvkrkkv.html

[T18] Swift：字符串插值
来源：http://dali.pengpengdd.cyou/Article/details/gtdswfhqgs.html

"值: \(b)"
来源：http://dali.aibaodan.cn/Article/details/gtuwdtbjdj.html

[T19] Swift：可选绑定
来源：http://dali.feifeiyinyue.top/Article/details/gtinnolwvw.html

if let n = opt { print(n) }
来源：http://dali.hnqzz.top/Article/details/gtxpsupymg.html

[T20] Swift：数组操作
来源：http://dali.vqdsnc.cn/Article/details/gtgjsqztwu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.haohaochexian.top/Article/details/gtldrypxeb.html

[T21] Swift：遍历
来源：http://dali.zhixingplan.top/Article/details/gtcfpsarbk.html

for x in a { print(x) }
来源：http://dali.bjfxy.top/Article/details/gtwwspttwi.html

[T22] Swift：字典
来源：http://dali.mhx1999.top/Article/details/gtmqejcnzc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zdqjudy.top/Article/details/gtumuhdbtn.html

[T23] Swift：函数
来源：http://dali.sysykeji.top/Article/details/gtinkuunli.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tanke756.top/Article/details/gtrlyhljvx.html

[T24] Swift：闭包
来源：http://dali.pengpengdd.cyou/Article/details/gtfzvkmjkl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cheryme.top/Article/details/gtaukvfkoa.html

[T25] Swift：结构体
来源：http://dali.meibo888.top/Article/details/gtxxaijjqs.html

struct P { var x: Int }
来源：http://dali.tanke756.top/Article/details/gtrjviphts.html

[T26] Swift：类与重写
来源：http://dali.quarkkingdee.top/Article/details/gtjiiygzei.html

class A: Base { override func f() {} }
来源：http://dali.zhoulong.xyz/Article/details/gtwswlfykp.html

[T27] Swift：错误处理
来源：http://dali.yj20258888.top/Article/details/gtnwesgiaa.html

do { try f() } catch { print(error) }
来源：http://dali.daxiang520.top/Article/details/gtebrlunwt.html

[T28] Swift：枚举
来源：http://dali.yongpay.top/Article/details/gtemiqdiku.html

enum Color { case red, green }
来源：http://dali.ppjwa.cn/Article/details/gtmvqkwjpd.html

[T29] Swift：guard 提前返回
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmmnxpdge.html

guard let x = opt else { return }
来源：http://dali.gogol.net.cn/Article/details/gtkqygligt.html

[T30] Swift：协议
来源：http://dali.jianghu66.top/Article/details/gtidbvvege.html

protocol Shape { func area() -> Double }
来源：http://dali.aibaodan.cn/Article/details/gtnbewduoq.html

[T31] Lua：Hello World
来源：http://dali.yj20258888.top/Article/details/gtbfghgriy.html

print("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gtphbtlzcn.html

[T32] Lua：局部变量
来源：http://dali.wangdashe.top/Article/details/gtuktxikwp.html

local a = 1
来源：http://dali.gogol.net.cn/Article/details/gtpwjdyxii.html

[T33] Lua：表（数组）
来源：http://dali.jqgfzy.top/Article/details/gteegvcihh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yj20258888.top/Article/details/gtbqxycguc.html

[T34] Lua：遍历表
来源：http://dali.cheryme.top/Article/details/gtjjjshtjm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.birdmap.top/Article/details/gtltmqfeif.html

[T35] Lua：字典表
来源：http://dali.quarkkingdee.top/Article/details/gtszjxmoho.html

local d = { a = 1 };  d.b = 2
来源：http://dali.wangshuangyany.cn/Article/details/gtldpeyvug.html

[T36] Lua：函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtebsqpyiz.html

function add(a, b) return a + b end
来源：http://dali.zhongyouzk.top/Article/details/gtnzfrvigi.html

[T37] Lua：字符串拼接
来源：http://dali.snrcjt.cn/Article/details/gtjoiyjeew.html

"a" .. "b"
来源：http://dali.shuidangran.top/Article/details/gtivlgjdpt.html

[T38] Lua：条件
来源：http://dali.hnqzz.top/Article/details/gthpeeungl.html

if x > 0 then print("正") end
来源：http://dali.jlsjyb.cn/Article/details/gtkeelpgbx.html

[T39] Lua：模式匹配
来源：http://dali.yj20258888.top/Article/details/gtidonltme.html

string.find(s, "%d+")
来源：http://dali.yanxiufei.cn/Article/details/gthkackiqc.html

[T40] Lua：元表
来源：http://dali.hnxiangtu.top/Article/details/gtqowdarlb.html

setmetatable({}, { __index = base })
来源：http://dali.kuanghao11.cn/Article/details/gtiuwkmpnj.html

[T41] Perl：Hello World
来源：http://dali.hammf.cn/Article/details/gtanbuqvqf.html

print "Hello\n";
来源：http://dali.guowangkeji.top/Article/details/gtclcgnytr.html

[T42] Perl：变量类型
来源：http://dali.guannengcc.top/Article/details/gtdkzefpdc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.chenlongwang.top/Article/details/gtjmvoyppu.html

[T43] Perl：字符串插值
来源：http://dali.ywan-chungtsiang.top/Article/details/gthxiavijy.html

"值: $a"
来源：http://dali.daxiang520.top/Article/details/gtjufhoism.html

[T44] Perl：条件
来源：http://dali.yj202588.top/Article/details/gthvlgpdih.html

if ($a > 0) { print "正"; }
来源：http://dali.yvedp.cn/Article/details/gtsssjsakf.html

[T45] Perl：数组遍历
来源：http://dali.sufxvd.cn/Article/details/gtpljecmzg.html

for my $x (@arr) { print $x; }
来源：http://dali.havefunace.top/Article/details/gtuazfipjs.html

[T46] Perl：哈希操作
来源：http://dali.yuxming.cn/Article/details/gttfbihjxr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.nwbrower.top/Article/details/gtslpsvyty.html

[T47] Perl：正则捕获
来源：http://dali.0kj1m.cn/Article/details/gtnrrlwqlh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhixingplan.top/Article/details/gtsvmynqoi.html

[T48] Perl：正则替换
来源：http://dali.jinghuilouyu.cn/Article/details/gturtrdrwy.html

$s =~ s/old/new/g;
来源：http://dali.haohaochexian.top/Article/details/gttkvhuars.html

[T49] Perl：函数
来源：http://dali.sxryk.cn/Article/details/gthdewonnd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtpglrhzaw.html

[T50] Perl：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gtfhyzlgis.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xylfe.cn/Article/details/gtcgifaaal.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gthcauoeys.html

[T51] Scala：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtivwuocgw.html

println("Hello")
来源：http://dali.gogol.net.cn/Article/details/gtkknzblie.html

[T52] Scala：变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjwlxbucw.html

val a = 1;  var b = 2
来源：http://dali.tianlin.xyz/Article/details/gtprlpiipn.html

[T53] Scala：字符串插值
来源：http://dali.jinqigufen.top/Article/details/gtdegiscgd.html

s"值: $b"
来源：http://dali.nanxuanxn.top/Article/details/gtmkhzdzxo.html

[T54] Scala：集合映射
来源：http://dali.svipenyu.cn/Article/details/gtrvejuuiv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.vqdsnc.cn/Article/details/gtbdicmdxg.html

[T55] Scala：集合过滤
来源：http://dali.cdnleiting.top/Article/details/gtjmmtltsw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zycfv.cn/Article/details/gtwulsrxvd.html

[T56] Scala：样例类
来源：http://dali.wangshuangyany.cn/Article/details/gtsanptrrm.html

case class User(name: String, age: Int)
来源：http://dali.meibo888.top/Article/details/gtotozklpk.html

[T57] Scala：模式匹配
来源：http://dali.sysykeji.top/Article/details/gtcddwbsvc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jyoumei.cn/Article/details/gthpinaemz.html

[T58] Scala：函数定义
来源：http://dali.yuanzhike.top/Article/details/gtyqsjilxi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xuetiantiany.cn/Article/details/gtcoznetzg.html

[T59] Scala：循环
来源：http://dali.zhongyouzk.top/Article/details/gtawrbamrd.html

for (i <- 1 to 10) println(i)
来源：http://dali.ehwqpu.com/Article/details/gtpioudtbg.html

[T60] Scala：折叠
来源：http://dali.yj202588.top/Article/details/gtjrngkkof.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yj202588.top/Article/details/gthpwwicoh.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gttxrvsypr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hnqzz.top/Article/details/gtgexmewea.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtjnilvpbg.html

[U01] Py：创建虚拟环境
来源：http://dali.zhixingplan.top/Article/details/gtlolvcxcj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hongshengwenyu.top/Article/details/gtswgbmkva.html

[U02] Py：导出 / 安装依赖
来源：http://dali.bjfxy.top/Article/details/gtmlrlrluu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtfzwrxqur.html

[U03] Py：加载 .env 配置
来源：http://dali.jqgfzy.top/Article/details/gtsrazxjmi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.meibo888.top/Article/details/gtilyzimds.html

[U04] Py：变量调试打印
来源：http://dali.tanke756.top/Article/details/gtknlwhlft.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ivvv.top/Article/details/gtmmkgnnje.html

[U05] Py：列表去重且保序
来源：http://dali.yuxming.cn/Article/details/gtebbpozma.html

list(dict.fromkeys(arr))
来源：http://dali.yj202588.top/Article/details/gtmbvucswp.html

[U06] Py：合并两个字典
来源：http://dali.cucudq.cn/Article/details/gtnshgalhw.html

{**a, **b}
来源：http://dali.shanyushiyangtech.top/Article/details/gtdkeljypj.html

[U07] Py：反转字典键值
来源：http://dali.shuidangran.top/Article/details/gtwulitffm.html

{v: k for k, v in d.items()}
来源：http://dali.pycfn.com/Article/details/gtusqlyahw.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gtxfpmighj.html

[y for x in nested for y in x]
来源：http://dali.guowangkeji.top/Article/details/gtzvjljlzs.html

[U09] Py：字典取最大值的键
来源：http://dali.ydzc1.top/Article/details/gtkycicwgk.html

max(d, key=d.get)
来源：http://dali.guowangkeji.top/Article/details/gtvplacejg.html

[U10] Py：按值排序字典
来源：http://dali.cqqwz.cn/Article/details/gtwekzbena.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ybcxt.top/Article/details/gtavmekljb.html

[U11] Py：生成器表达式
来源：http://dali.aibaodan.cn/Article/details/gtgmlftits.html

(x * 2 for x in arr)
来源：http://dali.zdqjudy.top/Article/details/gttjatuevf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.tanke756.top/Article/details/gtxtkkwlfx.html

Counter(arr).most_common(3)
来源：http://dali.hammf.cn/Article/details/gtzbbpewlz.html

[U13] Py：固定长度队列
来源：http://dali.xuanzx.com/Article/details/gtpdrrrbdl.html

deque(maxlen=10)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqogovatf.html

[U14] Py：分组收集到列表
来源：http://dali.jlsjyb.cn/Article/details/gtavgyeqis.html

defaultdict(list)
来源：http://dali.hywenlv.cn/Article/details/gtkntinwed.html

[U15] Py：高精度计时
来源：http://dali.gogol.net.cn/Article/details/gtqkhoakaj.html

t = time.perf_counter()
来源：http://dali.aizwys.cn/Article/details/gtcwldqvpg.html

[U16] Py：命令行参数解析
来源：http://dali.meibo888.top/Article/details/gteselsrro.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcarbrgil.html

[U17] Py：初始化日志
来源：http://dali.zhoulong.xyz/Article/details/gteuwkmryj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.smart0.xyz/Article/details/gtnpntjngm.html

[U18] Py：预编译正则
来源：http://dali.gogol.net.cn/Article/details/gtlpygtbhk.html

pat = re.compile(r"\d+")
来源：http://dali.hywenlv.cn/Article/details/gtmbbjtzje.html

[U19] Py：正则替换带回调
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmsfogvek.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jlsjyb.cn/Article/details/gtvhybqadm.html

[U20] Py：缓存函数结果
来源：http://dali.guannengcc.top/Article/details/gtfalkbbhg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cashguo.top/Article/details/gtsfonloiq.html


<!-- 参考信息 -->