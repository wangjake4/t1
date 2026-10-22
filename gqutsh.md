代发 wailian999

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.dianchejie.cn/Article/details/gtqcudwmtl.html

[S02] C：变量与格式化输出
来源：http://dali.jinghuilouyu.cn/Article/details/gtrtbkytza.html

int a = 10; printf("%d\n", a);
来源：http://dali.pengpengdd.cyou/Article/details/gtpfcriuxx.html

[S03] C：读入整数
来源：http://dali.jinqigfzy.top/Article/details/gtqteplgtn.html

int x; scanf("%d", &x);
来源：http://dali.jqgufenzy.top/Article/details/gtzlimqzae.html

[S04] C：字符串复制
来源：http://dali.mhx1999.top/Article/details/gtkqhmgnpe.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cucudq.cn/Article/details/gtufgdwpcf.html

[S05] C：字符串长度
来源：http://dali.sxryk.cn/Article/details/gtraeidxwc.html

strlen(s)
来源：http://dali.hysaishi.cn/Article/details/gthxgxalyo.html

[S06] C：字符串比较
来源：http://dali.wangdashe.top/Article/details/gtsetihbyz.html

strcmp(a, b) == 0
来源：http://dali.zhengqikj.top/Article/details/gtbguxdprw.html

[S07] C：数组遍历求和
来源：http://dali.kuanghao11.cn/Article/details/gtxkpemksy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gaohongyu789.top/Article/details/gtmsntyujv.html

[S08] C：动态内存分配与释放
来源：http://dali.ppjwa.cn/Article/details/gthdsmmutl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.haohaochexian.top/Article/details/gtpolkmayb.html

[S09] C：结构体定义与初始化
来源：http://dali.haohaochexian.top/Article/details/gtrreelghl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.vqdsnc.cn/Article/details/gtbkqxgfah.html

[S10] C：指针与解引用
来源：http://dali.snrcjt.cn/Article/details/gtkypqhstx.html

int *p = &a;  *p = 5;
来源：http://dali.redwolf501.top/Article/details/gtttlryarb.html

[S11] C：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gthquifkbl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xziqi.cn/Article/details/gturdxryba.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwlrutazt.html

fclose(f);
来源：http://dali.ydzc1.top/Article/details/gtehrrwivo.html

[S12] C：写文件
来源：http://dali.hongshengwenyu.top/Article/details/gtrzhqqjno.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.fengsongda.top/Article/details/gtditlnkvn.html

[S13] C：宏定义
来源：http://dali.pengpengdd.cyou/Article/details/gteskkzadi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xuetiantiany.cn/Article/details/gtsiayiszb.html

[S14] C：枚举
来源：http://dali.jyoumei.cn/Article/details/gtldoeyirx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ydzc1.top/Article/details/gtqjjmxvxf.html

[S15] C：类型转换
来源：http://dali.bjfxy.top/Article/details/gtrrefqotk.html

(double) a / b
来源：http://dali.yj20258888.top/Article/details/gtjiuvsgav.html

[S16] C：位操作置位
来源：http://dali.yanxiufei.cn/Article/details/gtdcfhovru.html

x |= (1 << 3);
来源：http://dali.chenzaomai.com/Article/details/gtsioypsxf.html

[S17] C：安全拼接字符串
来源：http://dali.tianlin.xyz/Article/details/gtwaxbtafm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jianghu66.top/Article/details/gtevsuguwm.html

[S18] C：命令行参数
来源：http://dali.316326.xyz/Article/details/gtdiptgffx.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gtraigzcru.html

[S19] C：快速排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvbtterjo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gtqhfmlrdk.html

[S20] C：二分查找
来源：http://dali.hysaishi.cn/Article/details/gtsjaaynrm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zycfv.cn/Article/details/gtnsadqchp.html

[S21] C：字符类别判断
来源：http://dali.c1oappe.top/Article/details/gtplhzzkzr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cheryme.top/Article/details/gteruqwsqs.html

[S22] C：字符串转数字
来源：http://dali.yanxiufei.cn/Article/details/gtisauhdlz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.mhx1999.top/Article/details/gtsufsmlkf.html

[S23] C：随机数
来源：http://dali.nanxinkj.top/Article/details/gtluiqnoty.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jiagoushi.top/Article/details/gtoqegupvc.html

[S24] C：获取本地时间
来源：http://dali.xylfe.cn/Article/details/gtdxyihkzt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.bjfxy.top/Article/details/gtptpswwrf.html

[S25] C：内存拷贝
来源：http://dali.xinyue.icu/Article/details/gtgivbuwzx.html

memcpy(dst, src, n);
来源：http://dali.daxiang520.top/Article/details/gtrdolnaby.html

[S26] C：内存清零
来源：http://dali.smart0.xyz/Article/details/gtgkmxlfsl.html

memset(a, 0, sizeof a);
来源：http://dali.meibo888.top/Article/details/gtfsxnpqbb.html

[S27] C：定义常量
来源：http://dali.hywenlv.cn/Article/details/gtdukllzfd.html

const double PI = 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gtiejnvoab.html

[S28] C：静态变量
来源：http://dali.xuetiantiany.cn/Article/details/gtdoqrgqos.html

static int counter = 0;
来源：http://dali.0kj1m.cn/Article/details/gtdykalxcm.html

[S29] C：变参函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxcmubsdw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jiagoushi.top/Article/details/gtimfwtgom.html

[S30] C：头文件保护
来源：http://dali.yj202588.top/Article/details/gtzrhalgag.html

#ifndef X_H
来源：http://dali.xuetiantiany.cn/Article/details/gtpshoziup.html

#define X_H
来源：http://dali.sxryk.cn/Article/details/gtenekcgvq.html

#endif
来源：http://dali.yongpay.top/Article/details/gtbbnqyqix.html

[S31] C++：Hello World
来源：http://dali.shuidangran.top/Article/details/gtzjdbzpfg.html

#include <iostream>
来源：http://dali.xziqi.cn/Article/details/gtulmjkber.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtetkyaszz.html

[S32] C++：字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtrnlemcrt.html

std::string s = "hi";  s += "!";
来源：http://dali.gaohongyu789.top/Article/details/gtscgtofxw.html

[S33] C++：vector 增删
来源：http://dali.cucudq.cn/Article/details/gthatuflnb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yueranfly.top/Article/details/gtolvnpdrx.html

[S34] C++：遍历 vector
来源：http://dali.yvedp.cn/Article/details/gtjtlhxtzt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.guowangkeji.top/Article/details/gtcnkniydj.html

[S35] C++：map
来源：http://dali.havefunace.top/Article/details/gtzvpkkrxk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtadwpqyhf.html

[S36] C++：unordered_map
来源：http://dali.snrcjt.cn/Article/details/gtcephjtbt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gtaurjatyx.html

[S37] C++：set
来源：http://dali.jinghuilouyu.cn/Article/details/gtrmpggvfc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ivvv.top/Article/details/gttyuchrme.html

[S38] C++：排序
来源：http://dali.andypj.xyz/Article/details/gtzigpfrkm.html

std::sort(v.begin(), v.end());
来源：http://dali.haohaochexian.top/Article/details/gtyhceshzg.html

[S39] C++：自定义比较器排序
来源：http://dali.xuanzx.com/Article/details/gtngkbdcaa.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhiwuduotai.top/Article/details/gtmaxumjie.html

[S40] C++：查找元素
来源：http://dali.zhixingplan.top/Article/details/gtjxkhygrt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.kuanghao11.cn/Article/details/gtoathxtha.html

[S41] C++：类与构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkcaxnluv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.pengpengdd.cyou/Article/details/gtsazkjurh.html

[S42] C++：继承与虚函数
来源：http://dali.hywenlv.cn/Article/details/gttpfjcwcx.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjaxumjvk.html

[S43] C++：智能指针
来源：http://dali.wangdashe.top/Article/details/gtbgwrjrqe.html

auto p = std::make_unique<int>(5);
来源：http://dali.sufxvd.cn/Article/details/gtgjnciyqg.html

[S44] C++：引用传参
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhuoukmm.html

void inc(int &x) { ++x; }
来源：http://dali.316326.xyz/Article/details/gtxztduqsq.html

[S45] C++：lambda
来源：http://dali.tanke756.top/Article/details/gtywjqqael.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yuanzhike.top/Article/details/gtjithkzjh.html

[S46] C++：函数模板
来源：http://dali.yueranfly.top/Article/details/gtolcszyvu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.meibo888.top/Article/details/gtdotteijk.html

[S47] C++：结构化绑定遍历
来源：http://dali.hnxiangtu.top/Article/details/gtangeanea.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.316326.xyz/Article/details/gttgjzlyyu.html

[S48] C++：逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtmjnlsoca.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xziqi.cn/Article/details/gtcywdichz.html

while (std::getline(in, line)) { }
来源：http://dali.sweek.top/Article/details/gtamuyymeh.html

[S49] C++：写文件
来源：http://dali.xuanzx.com/Article/details/gtclthmabv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.fengsongda.top/Article/details/gtddmwxdih.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gtlekwvzrm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gtpnhlaews.html

[S51] C++：显式类型转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtouchnohk.html

static_cast<double>(a) / b
来源：http://dali.yj202588.top/Article/details/gtyxqqsprq.html

[S52] C++：const 与 noexcept
来源：http://dali.snrcjt.cn/Article/details/gtofhxkuyp.html

int size() const noexcept { return n_; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcjyveixx.html

[S53] C++：移动语义
来源：http://dali.redwolf501.top/Article/details/gtiupsadfd.html

std::vector<int> w = std::move(v);
来源：http://dali.0kj1m.cn/Article/details/gtpuxtikbf.html

[S54] C++：异常处理
来源：http://dali.wangshuangyany.cn/Article/details/gtsaapgcwx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjtwuvxip.html

[S55] C++：结构化绑定
来源：http://dali.hammf.cn/Article/details/gthjbsrljl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shzxlz.cn/Article/details/gtqgyxrlyu.html

[S56] C++：optional
来源：http://dali.gaohongyu789.top/Article/details/gtxwgaghqc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tanke756.top/Article/details/gtsfxbukvb.html

[S57] C++：编译期常量
来源：http://dali.ehwqpu.com/Article/details/gtchdyaxna.html

constexpr int N = 10;
来源：http://dali.vqdsnc.cn/Article/details/gtvosehzoo.html

[S58] C++：命名空间
来源：http://dali.smart0.xyz/Article/details/gtqflcquwj.html

namespace ns { int f() { return 1; } }
来源：http://dali.nwbrower.top/Article/details/gtlvthukcd.html

[S59] C++：静态断言
来源：http://dali.cheryme.top/Article/details/gtjaljvtbq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.wangdashe.top/Article/details/gtbgwyibbt.html

[S60] C++：遍历并删除元素
来源：http://dali.gogol.net.cn/Article/details/gtpnfacgmq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jlsjyb.cn/Article/details/gtvnjymcde.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtnnucuhzl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxdlidcqs.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtuejxromf.html

[T01] Kotlin：Hello World
来源：http://dali.aizwys.cn/Article/details/gtragbvsid.html

println("Hello")
来源：http://dali.meibo888.top/Article/details/gtpfieviyg.html

[T02] Kotlin：变量
来源：http://dali.hysaishi.cn/Article/details/gtungeycfu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.wangdashe.top/Article/details/gtzbkqjcyp.html

[T03] Kotlin：字符串模板
来源：http://dali.yvedp.cn/Article/details/gtpuxzflpi.html

"值: $b"
来源：http://dali.havefunace.top/Article/details/gthltptpyw.html

[T04] Kotlin：空安全
来源：http://dali.jianghu66.top/Article/details/gtplmwzppt.html

val n: String? = null;  n?.length
来源：http://dali.andypj.xyz/Article/details/gtqrmdiabq.html

[T05] Kotlin：when 表达式
来源：http://dali.birdmap.top/Article/details/gtyfnwekos.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.meibo888.top/Article/details/gtqitygdzr.html

[T06] Kotlin：集合映射
来源：http://dali.chenzaomai.com/Article/details/gtuvbuusdm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.tianlin.xyz/Article/details/gtyiavpqzu.html

[T07] Kotlin：集合过滤
来源：http://dali.redwolf501.top/Article/details/gtuhhfrvxv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj20258888.top/Article/details/gtzajslcae.html

[T08] Kotlin：数据类
来源：http://dali.zhongyouzk.top/Article/details/gtzzqovqhn.html

data class User(val name: String, val age: Int)
来源：http://dali.nwbrower.top/Article/details/gtwxpeanbt.html

[T09] Kotlin：扩展函数
来源：http://dali.shzxlz.cn/Article/details/gtwamrpegu.html

fun String.exclaim() = this + "!"
来源：http://dali.zhongyouzk.top/Article/details/gtpnrxaqfz.html

[T10] Kotlin：默认参数
来源：http://dali.316326.xyz/Article/details/gtdicmqfhs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shangyingyoupin.top/Article/details/gtgxuuneyd.html

[T11] Kotlin：协程
来源：http://dali.sxryk.cn/Article/details/gtcmvgcjbl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhoulong.xyz/Article/details/gtobwdbebl.html

[T12] Kotlin：解构声明
来源：http://dali.daria6918.cn/Article/details/gthsssecxs.html

val (a, b) = Pair(1, 2)
来源：http://dali.jiagoushi.top/Article/details/gtbdzlbiwl.html

[T13] Kotlin：只读 Map
来源：http://dali.ivvv.top/Article/details/gttddbqbrs.html

val m = mapOf("a" to 1)
来源：http://dali.jyoumei.cn/Article/details/gtmoruyxiw.html

[T14] Kotlin：循环
来源：http://dali.shangyingyoupin.top/Article/details/gtsbylvppa.html

for (i in 1..10) println(i)
来源：http://dali.snrcjt.cn/Article/details/gtlopufacg.html

[T15] Kotlin：接口
来源：http://dali.kuanghao11.cn/Article/details/gtvkakhrpo.html

interface Shape { fun area(): Double }
来源：http://dali.chenzaomai.com/Article/details/gtqyjelruj.html

[T16] Swift：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtxhnhrvhw.html

print("Hello")
来源：http://dali.yuanzhike.top/Article/details/gtopwjznhx.html

[T17] Swift：变量与常量
来源：http://dali.cashguo.top/Article/details/gtmjcgvipb.html

var a = 1;  let b = 2
来源：http://dali.shuidangran.top/Article/details/gtkxuybxhc.html

[T18] Swift：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gtalkztftj.html

"值: \(b)"
来源：http://dali.zhoulong.xyz/Article/details/gtpkomiiil.html

[T19] Swift：可选绑定
来源：http://dali.feifeiyinyue.top/Article/details/gtdinxxxzo.html

if let n = opt { print(n) }
来源：http://dali.xinyue.icu/Article/details/gtncbebcfd.html

[T20] Swift：数组操作
来源：http://dali.hnxiangtu.top/Article/details/gtkorlmeiz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cucudq.cn/Article/details/gtkeikykbw.html

[T21] Swift：遍历
来源：http://dali.zhixingplan.top/Article/details/gtykpjjsto.html

for x in a { print(x) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtspmpsuqq.html

[T22] Swift：字典
来源：http://dali.xziqi.cn/Article/details/gtpqnhizfz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.guowangkeji.top/Article/details/gtutcmukfh.html

[T23] Swift：函数
来源：http://dali.fengsongda.top/Article/details/gtxueuptpc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.chenlongwang.top/Article/details/gtwyptpodr.html

[T24] Swift：闭包
来源：http://dali.jqgufenzy.top/Article/details/gtlpfqkkeu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhoulong.xyz/Article/details/gthikfvylk.html

[T25] Swift：结构体
来源：http://dali.hongshengwenyu.top/Article/details/gtegndmzfm.html

struct P { var x: Int }
来源：http://dali.yanxiufei.cn/Article/details/gtmihhjqpu.html

[T26] Swift：类与重写
来源：http://dali.jianghu66.top/Article/details/gtxfjhrnqp.html

class A: Base { override func f() {} }
来源：http://dali.iojbl.cn/Article/details/gtqhukpizm.html

[T27] Swift：错误处理
来源：http://dali.hongshengwenyu.top/Article/details/gtyoczdwqs.html

do { try f() } catch { print(error) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmheqfnmi.html

[T28] Swift：枚举
来源：http://dali.kuanghao11.cn/Article/details/gtpzvuhkcq.html

enum Color { case red, green }
来源：http://dali.hongshengwenyu.top/Article/details/gtajnqiebx.html

[T29] Swift：guard 提前返回
来源：http://dali.wangdashe.top/Article/details/gtgochwrrz.html

guard let x = opt else { return }
来源：http://dali.jqgfzy.top/Article/details/gteleuwxlj.html

[T30] Swift：协议
来源：http://dali.sweek.top/Article/details/gtoyudqcbl.html

protocol Shape { func area() -> Double }
来源：http://dali.zhengqikj.top/Article/details/gthvksndqv.html

[T31] Lua：Hello World
来源：http://dali.yj20258.top/Article/details/gtfzjrcfpn.html

print("Hello")
来源：http://dali.xylfe.cn/Article/details/gtspaiavrq.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gtsbxyvljp.html

local a = 1
来源：http://dali.gzhubu.top/Article/details/gtchjwytzk.html

[T33] Lua：表（数组）
来源：http://dali.ybcxt.top/Article/details/gtidcilitl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhaomingkeji.xyz/Article/details/gtydcavwiv.html

[T34] Lua：遍历表
来源：http://dali.cashguo.top/Article/details/gtakbtsjoy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.havefunace.top/Article/details/gttkttbsdu.html

[T35] Lua：字典表
来源：http://dali.ppjwa.cn/Article/details/gtwqshtkbj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.dianchejie.cn/Article/details/gtsycujvgt.html

[T36] Lua：函数
来源：http://dali.xuetiantiany.cn/Article/details/gtxrmpzinr.html

function add(a, b) return a + b end
来源：http://dali.guowangkeji.top/Article/details/gtikazilix.html

[T37] Lua：字符串拼接
来源：http://dali.ehwqpu.com/Article/details/gtkgrrqmah.html

"a" .. "b"
来源：http://dali.hammf.cn/Article/details/gtxapvglyd.html

[T38] Lua：条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkvvzsdth.html

if x > 0 then print("正") end
来源：http://dali.ivvv.top/Article/details/gtmpauwnxf.html

[T39] Lua：模式匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtmupvwbyq.html

string.find(s, "%d+")
来源：http://dali.aibaodan.cn/Article/details/gtkwfjizxl.html

[T40] Lua：元表
来源：http://dali.bjfxy.top/Article/details/gttljjydir.html

setmetatable({}, { __index = base })
来源：http://dali.316326.xyz/Article/details/gtnrjnuoxl.html

[T41] Perl：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfkwkkvaj.html

print "Hello\n";
来源：http://dali.zhoulong.xyz/Article/details/gtpjaeghiv.html

[T42] Perl：变量类型
来源：http://dali.jyoumei.cn/Article/details/gtfnesxrhs.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sweek.top/Article/details/gtezytqnta.html

[T43] Perl：字符串插值
来源：http://dali.gzhubu.top/Article/details/gtcvvoiibq.html

"值: $a"
来源：http://dali.sxryk.cn/Article/details/gtlntwgjck.html

[T44] Perl：条件
来源：http://dali.smart0.xyz/Article/details/gtndwcznwt.html

if ($a > 0) { print "正"; }
来源：http://dali.hnqzz.top/Article/details/gtzohidpnh.html

[T45] Perl：数组遍历
来源：http://dali.bjfxy.top/Article/details/gtrdufqcel.html

for my $x (@arr) { print $x; }
来源：http://dali.sysykeji.top/Article/details/gtjalpcvvh.html

[T46] Perl：哈希操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxbbgzcn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ybcxt.top/Article/details/gtokzkgqxz.html

[T47] Perl：正则捕获
来源：http://dali.gogol.net.cn/Article/details/gtrxwfxefl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.guannengcc.top/Article/details/gtshyfanxq.html

[T48] Perl：正则替换
来源：http://dali.wangshuangyany.cn/Article/details/gtmrchfizb.html

$s =~ s/old/new/g;
来源：http://dali.hammf.cn/Article/details/gtsafbmhlr.html

[T49] Perl：函数
来源：http://dali.ivvv.top/Article/details/gtpsnjoevi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.fzhhl.top/Article/details/gtvxphdzdv.html

[T50] Perl：逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gtkhdtinyc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.aizwys.cn/Article/details/gthmlbdghm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.smart0.xyz/Article/details/gtjtkwgclv.html

[T51] Scala：Hello World
来源：http://dali.316326.xyz/Article/details/gtmoarghvs.html

println("Hello")
来源：http://dali.yj202588.top/Article/details/gtnjaehyzd.html

[T52] Scala：变量
来源：http://dali.andypj.xyz/Article/details/gtgvmpfdni.html

val a = 1;  var b = 2
来源：http://dali.jianghu66.top/Article/details/gtbouggjnt.html

[T53] Scala：字符串插值
来源：http://dali.nanxinkj.top/Article/details/gtsbvaiksz.html

s"值: $b"
来源：http://dali.yonumen.top/Article/details/gtnfknarbv.html

[T54] Scala：集合映射
来源：http://dali.yueranfly.top/Article/details/gthzewxgqr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cqqwz.cn/Article/details/gtvholnxlc.html

[T55] Scala：集合过滤
来源：http://dali.jqgfzy.top/Article/details/gtpndpkpdx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhongyouzk.top/Article/details/gtqkvcgnzd.html

[T56] Scala：样例类
来源：http://dali.tanke756.top/Article/details/gttnoadgqp.html

case class User(name: String, age: Int)
来源：http://dali.hfpthk.cn/Article/details/gtqmarsjos.html

[T57] Scala：模式匹配
来源：http://dali.jqgfzy.top/Article/details/gtwqsumjrm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.sufxvd.cn/Article/details/gteymovwbc.html

[T58] Scala：函数定义
来源：http://dali.feifeiyinyue.top/Article/details/gtnxwcqduz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cucudq.cn/Article/details/gttvtovgjd.html

[T59] Scala：循环
来源：http://dali.hammf.cn/Article/details/gtzumnfhbd.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinqigfzy.top/Article/details/gtgyrqxily.html

[T60] Scala：折叠
来源：http://dali.hongshengwenyu.top/Article/details/gtqfribjna.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hywenlv.cn/Article/details/gtcpratxij.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtvyvjzmpn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.fzhhl.top/Article/details/gtejoenncl.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtgqfhoasu.html

[U01] Py：创建虚拟环境
来源：http://dali.havefunace.top/Article/details/gtzjcfrbvs.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.kuanghao11.cn/Article/details/gtcxyqihem.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cucudq.cn/Article/details/gtrnqqihtb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jlsjyb.cn/Article/details/gtjshinjxo.html

[U03] Py：加载 .env 配置
来源：http://dali.yuanzhike.top/Article/details/gtozrzjyoh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.nanxinkj.top/Article/details/gtftdrbhpc.html

[U04] Py：变量调试打印
来源：http://dali.bjfxy.top/Article/details/gtlbeavtya.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.aibaodan.cn/Article/details/gtozdrnntv.html

[U05] Py：列表去重且保序
来源：http://dali.quarkkingdee.top/Article/details/gtuhciuksh.html

list(dict.fromkeys(arr))
来源：http://dali.gaohongyu789.top/Article/details/gtliirrtab.html

[U06] Py：合并两个字典
来源：http://dali.feifeiyinyue.top/Article/details/gtfanaqscq.html

{**a, **b}
来源：http://dali.c1oappe.top/Article/details/gtvuaikirp.html

[U07] Py：反转字典键值
来源：http://dali.smart0.xyz/Article/details/gtutdruvzq.html

{v: k for k, v in d.items()}
来源：http://dali.jinghuilouyu.cn/Article/details/gtqfhsdkqz.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gtrunjkemv.html

[y for x in nested for y in x]
来源：http://dali.yuanzhike.top/Article/details/gtpngpwskh.html

[U09] Py：字典取最大值的键
来源：http://dali.meibo888.top/Article/details/gtehjwykry.html

max(d, key=d.get)
来源：http://dali.gotoacloud.top/Article/details/gtbwxhkane.html

[U10] Py：按值排序字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvuptayy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sxryk.cn/Article/details/gtpwutmkal.html

[U11] Py：生成器表达式
来源：http://dali.zhongyouzk.top/Article/details/gtkhegwnyq.html

(x * 2 for x in arr)
来源：http://dali.dianchejie.cn/Article/details/gtjmysdeqm.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhiwuduotai.top/Article/details/gtabqxtkut.html

Counter(arr).most_common(3)
来源：http://dali.jqgufenzy.top/Article/details/gtuyuxgchf.html

[U13] Py：固定长度队列
来源：http://dali.nanxinkj.top/Article/details/gtmpjsqgfr.html

deque(maxlen=10)
来源：http://dali.gaohongyu789.top/Article/details/gtychwzzgj.html

[U14] Py：分组收集到列表
来源：http://dali.nanxinkj.top/Article/details/gttpvkeham.html

defaultdict(list)
来源：http://dali.yj20258.top/Article/details/gtppuhwclu.html

[U15] Py：高精度计时
来源：http://dali.kuanghao11.cn/Article/details/gtpltbhbhp.html

t = time.perf_counter()
来源：http://dali.zhengqikj.top/Article/details/gtcmsivjhv.html

[U16] Py：命令行参数解析
来源：http://dali.quarkkingdee.top/Article/details/gtwixodozw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.smart0.xyz/Article/details/gtszzyacgn.html

[U17] Py：初始化日志
来源：http://dali.jianghu66.top/Article/details/gtokpwicum.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.daxiang520.top/Article/details/gtztwkynry.html

[U18] Py：预编译正则
来源：http://dali.daria6918.cn/Article/details/gtcbjvlaql.html

pat = re.compile(r"\d+")
来源：http://dali.hywenlv.cn/Article/details/gtxarhoklw.html

[U19] Py：正则替换带回调
来源：http://dali.tanke756.top/Article/details/gtiaouoflu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.tian-w.cn/Article/details/gtvcnatvkj.html

[U20] Py：缓存函数结果
来源：http://dali.yuxming.cn/Article/details/gtwwexfqfj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.aizwys.cn/Article/details/gttcmsgmsu.html

[U21] Py：自定义上下文管理器
来源：http://dali.shuidangran.top/Article/details/gtvvqlrbav.html

@contextlib.contextmanager
来源：http://dali.tanke756.top/Article/details/gtudlmqfag.html

[U22] Py：矩阵转置
来源：http://dali.fengsongda.top/Article/details/gtvwjbfwfe.html

list(zip(*m))
来源：http://dali.birdmap.top/Article/details/gtntuyquuv.html

[U23] Py：分块读取大文件
来源：http://dali.snrcjt.cn/Article/details/gtfvhuizia.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.smart0.xyz/Article/details/gtmpbgydzy.html

[U24] Py：路径操作
来源：http://dali.fengsongda.top/Article/details/gtqexywkna.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhongyouzk.top/Article/details/gtodncbpbu.html


<!-- 参考信息 -->