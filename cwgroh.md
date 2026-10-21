代发 wailian999

int x; scanf("%d", &x);
来源：http://dali.yj202588.top/Article/details/gtnhwouqrd.html

[S04] C：字符串复制
来源：http://dali.chenjidiqi.icu/Article/details/gtciegccre.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yanxiufei.cn/Article/details/gtagixigtv.html

[S05] C：字符串长度
来源：http://dali.yanxiufei.cn/Article/details/gtilkkfbrj.html

strlen(s)
来源：http://dali.kuanghao11.cn/Article/details/gtfwhugsiv.html

[S06] C：字符串比较
来源：http://dali.ehwqpu.com/Article/details/gtciqrlhko.html

strcmp(a, b) == 0
来源：http://dali.cashguo.top/Article/details/gtebtlcfbp.html

[S07] C：数组遍历求和
来源：http://dali.zhixingplan.top/Article/details/gtbsjdymda.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yonumen.top/Article/details/gtdtjrofdv.html

[S08] C：动态内存分配与释放
来源：http://dali.mhx1999.top/Article/details/gtojpauqnq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yongpay.top/Article/details/gtokzkmyor.html

[S09] C：结构体定义与初始化
来源：http://dali.hnxiangtu.top/Article/details/gtrkksdgmp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhengqikj.top/Article/details/gtwincddua.html

[S10] C：指针与解引用
来源：http://dali.yanxiufei.cn/Article/details/gttfzrsitz.html

int *p = &a;  *p = 5;
来源：http://dali.yj20258888.top/Article/details/gtwrpslzma.html

[S11] C：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gtpxwrlexs.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ybcxt.top/Article/details/gtbmlhdpfp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gaohongyu789.top/Article/details/gtmtdukuyc.html

fclose(f);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgnmnpzek.html

[S12] C：写文件
来源：http://dali.iojbl.cn/Article/details/gtdkuaxuvv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gaohongyu789.top/Article/details/gtdvcwfuky.html

[S13] C：宏定义
来源：http://dali.guowangkeji.top/Article/details/gttrlxgdxz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jiagoushi.top/Article/details/gtepciqads.html

[S14] C：枚举
来源：http://dali.tanke756.top/Article/details/gtaarrqikp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shangyingyoupin.top/Article/details/gterbrlnbv.html

[S15] C：类型转换
来源：http://dali.yj20258.top/Article/details/gtyumymlsk.html

(double) a / b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuhyfrvba.html

[S16] C：位操作置位
来源：http://dali.dianchejie.cn/Article/details/gtuteqcydj.html

x |= (1 << 3);
来源：http://dali.zdqjudy.top/Article/details/gtkopfksaz.html

[S17] C：安全拼接字符串
来源：http://dali.gotoacloud.top/Article/details/gtwwaostsl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jianghu66.top/Article/details/gtamnruyko.html

[S18] C：命令行参数
来源：http://dali.yj20258.top/Article/details/gtsxyliygl.html

int main(int argc, char **argv)
来源：http://dali.jyoumei.cn/Article/details/gtafalporz.html

[S19] C：快速排序
来源：http://dali.yvedp.cn/Article/details/gtshpqclkv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gtmlyluukl.html

[S20] C：二分查找
来源：http://dali.shuidangran.top/Article/details/gteecbspeq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hysaishi.cn/Article/details/gtpxsbbrkx.html

[S21] C：字符类别判断
来源：http://dali.xziqi.cn/Article/details/gtmobepztj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.316326.xyz/Article/details/gtkuayqfmt.html

[S22] C：字符串转数字
来源：http://dali.hnxiangtu.top/Article/details/gtjsiebeyc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfygcezc.html

[S23] C：随机数
来源：http://dali.hysaishi.cn/Article/details/gtcvstqvtp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.aibaodan.cn/Article/details/gtaztaeunh.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gtsxddidai.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenlongwang.top/Article/details/gtmntuaerv.html

[S25] C：内存拷贝
来源：http://dali.gogol.net.cn/Article/details/gtcarktpjw.html

memcpy(dst, src, n);
来源：http://dali.yueranfly.top/Article/details/gtcgwdbrkx.html

[S26] C：内存清零
来源：http://dali.snrcjt.cn/Article/details/gtlnozdbhd.html

memset(a, 0, sizeof a);
来源：http://dali.aizwys.cn/Article/details/gtoqfpyowc.html

[S27] C：定义常量
来源：http://dali.dianchejie.cn/Article/details/gturekhifk.html

const double PI = 3.14159;
来源：http://dali.yongpay.top/Article/details/gtkqsbtsts.html

[S28] C：静态变量
来源：http://dali.guannengcc.top/Article/details/gtlmefjmdl.html

static int counter = 0;
来源：http://dali.yongpay.top/Article/details/gtfffxwelx.html

[S29] C：变参函数
来源：http://dali.gotoacloud.top/Article/details/gtrhdydomc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tanke756.top/Article/details/gtfajsgnfh.html

[S30] C：头文件保护
来源：http://dali.jianghu66.top/Article/details/gtrkywcnqg.html

#ifndef X_H
来源：http://dali.guowangkeji.top/Article/details/gtjhocoosh.html

#define X_H
来源：http://dali.ybcxt.top/Article/details/gtiwlunoqi.html

#endif
来源：http://dali.jqgfzy.top/Article/details/gtlhiueevx.html

[S31] C++：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtadrsyvhz.html

#include <iostream>
来源：http://dali.yvedp.cn/Article/details/gtkstristq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gtkpggmxas.html

[S32] C++：字符串
来源：http://dali.jinqigufen.top/Article/details/gtsfdyoudd.html

std::string s = "hi";  s += "!";
来源：http://dali.hammf.cn/Article/details/gtajetazyg.html

[S33] C++：vector 增删
来源：http://dali.cheryme.top/Article/details/gtvykismwh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yvedp.cn/Article/details/gtlqeoowtr.html

[S34] C++：遍历 vector
来源：http://dali.tianlin.xyz/Article/details/gtespxrvws.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tian-w.cn/Article/details/gtmlgwtjbw.html

[S35] C++：map
来源：http://dali.ehwqpu.com/Article/details/gtzuxycpxv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gtwnqkuvid.html

[S36] C++：unordered_map
来源：http://dali.jyoumei.cn/Article/details/gtjwzimbac.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtcjpzcpda.html

[S37] C++：set
来源：http://dali.gogol.net.cn/Article/details/gtazgbhaeq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yuxming.cn/Article/details/gtfwzfsddp.html

[S38] C++：排序
来源：http://dali.shuidangran.top/Article/details/gtzujuhysk.html

std::sort(v.begin(), v.end());
来源：http://dali.havefunace.top/Article/details/gtocrqfone.html

[S39] C++：自定义比较器排序
来源：http://dali.kuanghao11.cn/Article/details/gtgkszwqwp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.mhx1999.top/Article/details/gtecfqmmrw.html

[S40] C++：查找元素
来源：http://dali.yueranfly.top/Article/details/gtyshmrmqk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yonumen.top/Article/details/gtqbxefqvl.html

[S41] C++：类与构造函数
来源：http://dali.jlsjyb.cn/Article/details/gtkjyogpgk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnxiangtu.top/Article/details/gtbtjjnqwi.html

[S42] C++：继承与虚函数
来源：http://dali.jinqigufen.top/Article/details/gtdvxxdqhb.html

class B : public Base { public: void f() override {} };
来源：http://dali.ydzc1.top/Article/details/gtntrusjsr.html

[S43] C++：智能指针
来源：http://dali.ehwqpu.com/Article/details/gtxrewygnf.html

auto p = std::make_unique<int>(5);
来源：http://dali.wangshuangyany.cn/Article/details/gtyfcyrspq.html

[S44] C++：引用传参
来源：http://dali.cheryme.top/Article/details/gtzogdness.html

void inc(int &x) { ++x; }
来源：http://dali.dianchejie.cn/Article/details/gtwtztsdof.html

[S45] C++：lambda
来源：http://dali.yuxming.cn/Article/details/gtnpuwmyix.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nanxinkj.top/Article/details/gtkaytqpkd.html

[S46] C++：函数模板
来源：http://dali.smart0.xyz/Article/details/gtfjpwhzkm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gzhubu.top/Article/details/gtgtnzytwm.html

[S47] C++：结构化绑定遍历
来源：http://dali.tanke756.top/Article/details/gtuzahkxzu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttcgzlupe.html

[S48] C++：逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtmqmgwnfc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jiagoushi.top/Article/details/gtmjxjhala.html

while (std::getline(in, line)) { }
来源：http://dali.chenzaomai.com/Article/details/gtblkvxjts.html

[S49] C++：写文件
来源：http://dali.jianghu66.top/Article/details/gtrtodfugi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.guowangkeji.top/Article/details/gtprpzasiz.html

[S50] C++：格式化数字
来源：http://dali.aibaodan.cn/Article/details/gtgunkjzxc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.pycfn.com/Article/details/gtmfjdhvbc.html

[S51] C++：显式类型转换
来源：http://dali.gzhubu.top/Article/details/gtbybrypln.html

static_cast<double>(a) / b
来源：http://dali.jqgfzy.top/Article/details/gtergzjgvy.html

[S52] C++：const 与 noexcept
来源：http://dali.pycfn.com/Article/details/gttgwhtxeb.html

int size() const noexcept { return n_; }
来源：http://dali.hnxiangtu.top/Article/details/gtazkburlq.html

[S53] C++：移动语义
来源：http://dali.ppjwa.cn/Article/details/gtfxnjzmlh.html

std::vector<int> w = std::move(v);
来源：http://dali.dianchejie.cn/Article/details/gttttqpbeq.html

[S54] C++：异常处理
来源：http://dali.jlsjyb.cn/Article/details/gtudltnvgu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj20258.top/Article/details/gthzmtyfux.html

[S55] C++：结构化绑定
来源：http://dali.ybcxt.top/Article/details/gtyzakabhl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenlongwang.top/Article/details/gtspkfmxbe.html

[S56] C++：optional
来源：http://dali.kuanghao11.cn/Article/details/gtzgdfjpsm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jqgfzy.top/Article/details/gtntwvtsbv.html

[S57] C++：编译期常量
来源：http://dali.ppjwa.cn/Article/details/gtkmhbesme.html

constexpr int N = 10;
来源：http://dali.smart0.xyz/Article/details/gtnporaxgi.html

[S58] C++：命名空间
来源：http://dali.tanke756.top/Article/details/gthnmtteer.html

namespace ns { int f() { return 1; } }
来源：http://dali.iojbl.cn/Article/details/gtbralasfi.html

[S59] C++：静态断言
来源：http://dali.yj20258.top/Article/details/gtlwummcwj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpxsduqlf.html

[S60] C++：遍历并删除元素
来源：http://dali.ppjwa.cn/Article/details/gtukqkutqz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.redwolf501.top/Article/details/gtuajdllwx.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gthlercfwm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenlongwang.top/Article/details/gtzreivkcc.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtpkazhtcw.html

[T01] Kotlin：Hello World
来源：http://dali.cucudq.cn/Article/details/gtuezefskr.html

println("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gteqsjhryl.html

[T02] Kotlin：变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrvfyrtkf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhoulong.xyz/Article/details/gtcjiwduum.html

[T03] Kotlin：字符串模板
来源：http://dali.gaohongyu789.top/Article/details/gtfbqwjadk.html

"值: $b"
来源：http://dali.shangyingyoupin.top/Article/details/gtsxuwudak.html

[T04] Kotlin：空安全
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoevligum.html

val n: String? = null;  n?.length
来源：http://dali.dianchejie.cn/Article/details/gtaxajpuas.html

[T05] Kotlin：when 表达式
来源：http://dali.yuanzhike.top/Article/details/gtlkpqchhv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.haohaochexian.top/Article/details/gtranaavvq.html

[T06] Kotlin：集合映射
来源：http://dali.nwbrower.top/Article/details/gtbwaumdfg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.9152youxi.cn/Article/details/gtecexwbqr.html

[T07] Kotlin：集合过滤
来源：http://dali.hnqzz.top/Article/details/gtvvlcgstr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuxming.cn/Article/details/gtfoklwfng.html

[T08] Kotlin：数据类
来源：http://dali.xuetiantiany.cn/Article/details/gtrowgkdis.html

data class User(val name: String, val age: Int)
来源：http://dali.nanxinkj.top/Article/details/gtjiqzppyv.html

[T09] Kotlin：扩展函数
来源：http://dali.yuanzhike.top/Article/details/gtawufnrmn.html

fun String.exclaim() = this + "!"
来源：http://dali.hfpthk.cn/Article/details/gtccmnyjlp.html

[T10] Kotlin：默认参数
来源：http://dali.vqdsnc.cn/Article/details/gtvxmilmiz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ehwqpu.com/Article/details/gtddobrsma.html

[T11] Kotlin：协程
来源：http://dali.ivvv.top/Article/details/gtdezfmehs.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hnxiangtu.top/Article/details/gtffszknyq.html

[T12] Kotlin：解构声明
来源：http://dali.shangyingyoupin.top/Article/details/gthuewqdfp.html

val (a, b) = Pair(1, 2)
来源：http://dali.bjfxy.top/Article/details/gtoaysxxlz.html

[T13] Kotlin：只读 Map
来源：http://dali.chenlongwang.top/Article/details/gtcrjmqdkq.html

val m = mapOf("a" to 1)
来源：http://dali.kuanghao11.cn/Article/details/gtvmujmsyb.html

[T14] Kotlin：循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gttbpvujmg.html

for (i in 1..10) println(i)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrkyzldwr.html

[T15] Kotlin：接口
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtylevohiq.html

interface Shape { fun area(): Double }
来源：http://dali.bjfxy.top/Article/details/gtthfrvkqm.html

[T16] Swift：Hello World
来源：http://dali.daria6918.cn/Article/details/gtbuqykegm.html

print("Hello")
来源：http://dali.ivvv.top/Article/details/gtgpmowbml.html

[T17] Swift：变量与常量
来源：http://dali.zhengqikj.top/Article/details/gtdikifdix.html

var a = 1;  let b = 2
来源：http://dali.aibaodan.cn/Article/details/gtqkkuxflo.html

[T18] Swift：字符串插值
来源：http://dali.ehwqpu.com/Article/details/gtdealolbj.html

"值: \(b)"
来源：http://dali.ehwqpu.com/Article/details/gtstoctrqr.html

[T19] Swift：可选绑定
来源：http://dali.zhiwuduotai.top/Article/details/gtdowryhow.html

if let n = opt { print(n) }
来源：http://dali.guannengcc.top/Article/details/gtpshijome.html

[T20] Swift：数组操作
来源：http://dali.shanyushiyangtech.top/Article/details/gtxhwtqbrs.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.guowangkeji.top/Article/details/gtmmjeaczu.html

[T21] Swift：遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gtaurhbomn.html

for x in a { print(x) }
来源：http://dali.hnqzz.top/Article/details/gteggndmjf.html

[T22] Swift：字典
来源：http://dali.cashguo.top/Article/details/gtfyiwgatc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.quarkkingdee.top/Article/details/gtlvbrkqgn.html

[T23] Swift：函数
来源：http://dali.yanxiufei.cn/Article/details/gtsucqpotj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtesfinncc.html

[T24] Swift：闭包
来源：http://dali.jiagoushi.top/Article/details/gticojtejk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.mhx1999.top/Article/details/gtuaphohzv.html

[T25] Swift：结构体
来源：http://dali.yvedp.cn/Article/details/gtreqcecyw.html

struct P { var x: Int }
来源：http://dali.nanxuanxn.top/Article/details/gtyexeqyac.html

[T26] Swift：类与重写
来源：http://dali.hysaishi.cn/Article/details/gtjdxlamkw.html

class A: Base { override func f() {} }
来源：http://dali.bjfxy.top/Article/details/gtmgtldlyf.html

[T27] Swift：错误处理
来源：http://dali.c1oappe.top/Article/details/gtuqwagaue.html

do { try f() } catch { print(error) }
来源：http://dali.haohaochexian.top/Article/details/gtjeecvxrg.html

[T28] Swift：枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiyorowcx.html

enum Color { case red, green }
来源：http://dali.xuanzx.com/Article/details/gtkcesrbtx.html

[T29] Swift：guard 提前返回
来源：http://dali.birdmap.top/Article/details/gtuagvxvap.html

guard let x = opt else { return }
来源：http://dali.gogol.net.cn/Article/details/gtuduhdvyd.html

[T30] Swift：协议
来源：http://dali.pengpengdd.cyou/Article/details/gtzrenbzgw.html

protocol Shape { func area() -> Double }
来源：http://dali.hfpthk.cn/Article/details/gtzkpcebub.html

[T31] Lua：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtqfrlpdki.html

print("Hello")
来源：http://dali.nanxinkj.top/Article/details/gtgdguximh.html

[T32] Lua：局部变量
来源：http://dali.fengsongda.top/Article/details/gttnbiqscz.html

local a = 1
来源：http://dali.cheryme.top/Article/details/gtlbwffvot.html

[T33] Lua：表（数组）
来源：http://dali.hammf.cn/Article/details/gtmmormihj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jqgfzy.top/Article/details/gtjwrjsvbj.html

[T34] Lua：遍历表
来源：http://dali.hysaishi.cn/Article/details/gtortokiwr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtizxxmdqr.html

[T35] Lua：字典表
来源：http://dali.tian-w.cn/Article/details/gterzwuhad.html

local d = { a = 1 };  d.b = 2
来源：http://dali.snrcjt.cn/Article/details/gtwnkypbwz.html

[T36] Lua：函数
来源：http://dali.xinyue.icu/Article/details/gtoiqreewg.html

function add(a, b) return a + b end
来源：http://dali.jqgfzy.top/Article/details/gtoycyiywe.html

[T37] Lua：字符串拼接
来源：http://dali.jinqigufen.top/Article/details/gtdgamspvs.html

"a" .. "b"
来源：http://dali.chenlongwang.top/Article/details/gtafqbdijl.html

[T38] Lua：条件
来源：http://dali.jqgfzy.top/Article/details/gtwmugldwl.html

if x > 0 then print("正") end
来源：http://dali.chenlongwang.top/Article/details/gttgjncuxc.html

[T39] Lua：模式匹配
来源：http://dali.gogol.net.cn/Article/details/gtkzqkgnwb.html

string.find(s, "%d+")
来源：http://dali.gzhubu.top/Article/details/gtgixspnww.html

[T40] Lua：元表
来源：http://dali.hysaishi.cn/Article/details/gtwoesnzfn.html

setmetatable({}, { __index = base })
来源：http://dali.shzxlz.cn/Article/details/gtolsavhoo.html

[T41] Perl：Hello World
来源：http://dali.mhx1999.top/Article/details/gtgsscnyzy.html

print "Hello\n";
来源：http://dali.hnxiangtu.top/Article/details/gtxzoqfjff.html

[T42] Perl：变量类型
来源：http://dali.fengsongda.top/Article/details/gtpffdnald.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gtumdmfdyz.html

[T43] Perl：字符串插值
来源：http://dali.shanyushiyangtech.top/Article/details/gtblywtwqn.html

"值: $a"
来源：http://dali.sysykeji.top/Article/details/gtpwaeiaat.html

[T44] Perl：条件
来源：http://dali.havefunace.top/Article/details/gtghipxnvg.html

if ($a > 0) { print "正"; }
来源：http://dali.jinqigufen.top/Article/details/gtnwuecqsh.html

[T45] Perl：数组遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahdiswgq.html

for my $x (@arr) { print $x; }
来源：http://dali.vqdsnc.cn/Article/details/gtfwqutrof.html

[T46] Perl：哈希操作
来源：http://dali.feifeiyinyue.top/Article/details/gtnxmgsmxa.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.guannengcc.top/Article/details/gtkxaphhlc.html

[T47] Perl：正则捕获
来源：http://dali.chenjidiqi.icu/Article/details/gtpkrmpmtn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xylfe.cn/Article/details/gtzifapbrk.html

[T48] Perl：正则替换
来源：http://dali.xziqi.cn/Article/details/gtcqldvbbg.html

$s =~ s/old/new/g;
来源：http://dali.jianghu66.top/Article/details/gtlyjukwnx.html

[T49] Perl：函数
来源：http://dali.mhx1999.top/Article/details/gtigsichyw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gtciniisqs.html

[T50] Perl：逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gtxlkbrujp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jqgfzy.top/Article/details/gtlkqdivle.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.smart0.xyz/Article/details/gtkfeklnhw.html

[T51] Scala：Hello World
来源：http://dali.yongpay.top/Article/details/gtdxtgrstb.html

println("Hello")
来源：http://dali.yongpay.top/Article/details/gtytoltesq.html

[T52] Scala：变量
来源：http://dali.pengpengdd.cyou/Article/details/gtsouinxir.html

val a = 1;  var b = 2
来源：http://dali.jlsjyb.cn/Article/details/gtjmegydlf.html

[T53] Scala：字符串插值
来源：http://dali.zhixingplan.top/Article/details/gtrhbqfcbc.html

s"值: $b"
来源：http://dali.9152youxi.cn/Article/details/gtesivbylz.html

[T54] Scala：集合映射
来源：http://dali.snrcjt.cn/Article/details/gtnoullygr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hammf.cn/Article/details/gtfgqdcdpb.html

[T55] Scala：集合过滤
来源：http://dali.ehwqpu.com/Article/details/gtkwspfcjv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsrisrbqi.html

[T56] Scala：样例类
来源：http://dali.jinqigufen.top/Article/details/gtgxjyfvag.html

case class User(name: String, age: Int)
来源：http://dali.zhongyouzk.top/Article/details/gtlswzevsp.html

[T57] Scala：模式匹配
来源：http://dali.jyoumei.cn/Article/details/gtjvfnrkvw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cheryme.top/Article/details/gtjtwcebvx.html

[T58] Scala：函数定义
来源：http://dali.jqgfzy.top/Article/details/gtnrvkzmtv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.pengpengdd.cyou/Article/details/gtiypeclnv.html

[T59] Scala：循环
来源：http://dali.yvedp.cn/Article/details/gtqgfdkffy.html

for (i <- 1 to 10) println(i)
来源：http://dali.mhx1999.top/Article/details/gtgxcnxfnz.html

[T60] Scala：折叠
来源：http://dali.aibaodan.cn/Article/details/gtxgrdfncs.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xziqi.cn/Article/details/gtlrmqnbje.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtbtuqoxsi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.aizwys.cn/Article/details/gtypjdsfqt.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gttikntnho.html

[U01] Py：创建虚拟环境
来源：http://dali.fzhhl.top/Article/details/gtnjdziwta.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.dianchejie.cn/Article/details/gtidpcwgfc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhixingplan.top/Article/details/gtgdobgldw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwmxvaxz.html

[U03] Py：加载 .env 配置
来源：http://dali.gzhubu.top/Article/details/gtojpzdvin.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xuetiantiany.cn/Article/details/gtxtipdfhv.html

[U04] Py：变量调试打印
来源：http://dali.zhoulong.xyz/Article/details/gthrdjrxzu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhengqikj.top/Article/details/gtztmklznp.html

[U05] Py：列表去重且保序
来源：http://dali.zycfv.cn/Article/details/gtpugacyep.html

list(dict.fromkeys(arr))
来源：http://dali.hfpthk.cn/Article/details/gtkpseskqn.html

[U06] Py：合并两个字典
来源：http://dali.sysykeji.top/Article/details/gthcquomnf.html

{**a, **b}
来源：http://dali.ivvv.top/Article/details/gtydcoxgis.html

[U07] Py：反转字典键值
来源：http://dali.yj20258888.top/Article/details/gtnjqrcgri.html

{v: k for k, v in d.items()}
来源：http://dali.pycfn.com/Article/details/gtzkvvymzg.html

[U08] Py：展平二维列表
来源：http://dali.jyoumei.cn/Article/details/gtzoffjjtm.html

[y for x in nested for y in x]
来源：http://dali.yanxiufei.cn/Article/details/gtunabhvbm.html

[U09] Py：字典取最大值的键
来源：http://dali.yuxming.cn/Article/details/gtasqmjkud.html

max(d, key=d.get)
来源：http://dali.sufxvd.cn/Article/details/gtvlyource.html

[U10] Py：按值排序字典
来源：http://dali.yanxiufei.cn/Article/details/gtlwjqkeif.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cucudq.cn/Article/details/gtjeqfcase.html

[U11] Py：生成器表达式
来源：http://dali.xuanzx.com/Article/details/gtvjaphvpd.html

(x * 2 for x in arr)
来源：http://dali.cheryme.top/Article/details/gtzwxksdgf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hfpthk.cn/Article/details/gtsvlzftkq.html

Counter(arr).most_common(3)
来源：http://dali.chenjidiqi.icu/Article/details/gtpbhwcwnm.html

[U13] Py：固定长度队列
来源：http://dali.xuanzx.com/Article/details/gtszeqdbuz.html

deque(maxlen=10)
来源：http://dali.zycfv.cn/Article/details/gtiuxysevo.html

[U14] Py：分组收集到列表
来源：http://dali.xuanzx.com/Article/details/gtkfajjypx.html

defaultdict(list)
来源：http://dali.nwbrower.top/Article/details/gtjcypskek.html

[U15] Py：高精度计时
来源：http://dali.chenzaomai.com/Article/details/gtqoyajneb.html

t = time.perf_counter()
来源：http://dali.gzhubu.top/Article/details/gtoyokdidi.html

[U16] Py：命令行参数解析
来源：http://dali.yuanzhike.top/Article/details/gtmymcjxdn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.cqqwz.cn/Article/details/gtnjsbqbsm.html

[U17] Py：初始化日志
来源：http://dali.bjfxy.top/Article/details/gtbanmzwgh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.316326.xyz/Article/details/gtnvxwfnnm.html

[U18] Py：预编译正则
来源：http://dali.cheryme.top/Article/details/gtpejxdeve.html

pat = re.compile(r"\d+")
来源：http://dali.zdqjudy.top/Article/details/gtiqsmjvry.html

[U19] Py：正则替换带回调
来源：http://dali.xuanzx.com/Article/details/gtedxkvkuj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xuetiantiany.cn/Article/details/gtisjxngsa.html

[U20] Py：缓存函数结果
来源：http://dali.nanxinkj.top/Article/details/gtgsoiqvmb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxepscacx.html

[U21] Py：自定义上下文管理器
来源：http://dali.hysaishi.cn/Article/details/gthrvfnawv.html

@contextlib.contextmanager
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmgeqseou.html

[U22] Py：矩阵转置
来源：http://dali.jiagoushi.top/Article/details/gtakoqkcel.html

list(zip(*m))
来源：http://dali.wangshuangyany.cn/Article/details/gtiyvrlodk.html

[U23] Py：分块读取大文件
来源：http://dali.xuetiantiany.cn/Article/details/gttwnyukfi.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.c1oappe.top/Article/details/gttegzibyc.html

[U24] Py：路径操作
来源：http://dali.smart0.xyz/Article/details/gtlljqfyag.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.wangdashe.top/Article/details/gtbkbhccxr.html

[U25] Py：CSV 按字典读
来源：http://dali.0kj1m.cn/Article/details/gtjjigkssw.html

csv.DictReader(f)
来源：http://dali.tianlin.xyz/Article/details/gtbrwtqirk.html

[U26] Py：并发下载
来源：http://dali.shzxlz.cn/Article/details/gtsjptdrlt.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.tanke756.top/Article/details/gtjrfqchsw.html


<!-- 参考信息 -->