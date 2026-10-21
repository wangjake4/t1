代发 wailian999

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tianlin.xyz/Article/details/gtohjocmfp.html

[S02] C：变量与格式化输出
来源：http://dali.yongpay.top/Article/details/gtvucjutlh.html

int a = 10; printf("%d\n", a);
来源：http://dali.sufxvd.cn/Article/details/gtxkkpuays.html

[S03] C：读入整数
来源：http://dali.yuxming.cn/Article/details/gtnjcuixle.html

int x; scanf("%d", &x);
来源：http://dali.tanke756.top/Article/details/gtpjemiugo.html

[S04] C：字符串复制
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwbzxwye.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yongpay.top/Article/details/gtuhsvzdfr.html

[S05] C：字符串长度
来源：http://dali.snrcjt.cn/Article/details/gtpzsbwlhx.html

strlen(s)
来源：http://dali.jqgfzy.top/Article/details/gtjyombwhi.html

[S06] C：字符串比较
来源：http://dali.yj202588.top/Article/details/gttudupepu.html

strcmp(a, b) == 0
来源：http://dali.bjfxy.top/Article/details/gtlitybeqo.html

[S07] C：数组遍历求和
来源：http://dali.nanxinkj.top/Article/details/gtgzdsdvpy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sufxvd.cn/Article/details/gtengjpaxf.html

[S08] C：动态内存分配与释放
来源：http://dali.jqgufenzy.top/Article/details/gtiegvbhhx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yuanzhike.top/Article/details/gtlrubjkev.html

[S09] C：结构体定义与初始化
来源：http://dali.havefunace.top/Article/details/gtvdvdvrjq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nwbrower.top/Article/details/gtlnadbzti.html

[S10] C：指针与解引用
来源：http://dali.pycfn.com/Article/details/gtpacnaabb.html

int *p = &a;  *p = 5;
来源：http://dali.cdnleiting.top/Article/details/gttidsajmr.html

[S11] C：逐行读文件
来源：http://dali.hammf.cn/Article/details/gtcwysfizn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.mhx1999.top/Article/details/gtddloupjs.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xziqi.cn/Article/details/gtxskumyyb.html

fclose(f);
来源：http://dali.jyoumei.cn/Article/details/gtqrjtydxm.html

[S12] C：写文件
来源：http://dali.hfpthk.cn/Article/details/gtuxfcrson.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gtmpqblmqn.html

[S13] C：宏定义
来源：http://dali.ivvv.top/Article/details/gtvsruknnc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.smart0.xyz/Article/details/gtihihrfdf.html

[S14] C：枚举
来源：http://dali.xuanzx.com/Article/details/gttpfbqhfs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sysykeji.top/Article/details/gtqistontn.html

[S15] C：类型转换
来源：http://dali.svipenyu.cn/Article/details/gtwrdxyacd.html

(double) a / b
来源：http://dali.feifeiyinyue.top/Article/details/gtgbpdddtw.html

[S16] C：位操作置位
来源：http://dali.jinqigfzy.top/Article/details/gtioemyhbv.html

x |= (1 << 3);
来源：http://dali.yonumen.top/Article/details/gtyqsnvpme.html

[S17] C：安全拼接字符串
来源：http://dali.ehwqpu.com/Article/details/gtcsrujcys.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cashguo.top/Article/details/gtbxgdjtgx.html

[S18] C：命令行参数
来源：http://dali.cdnleiting.top/Article/details/gtasgqoigz.html

int main(int argc, char **argv)
来源：http://dali.yongpay.top/Article/details/gtkkutzywe.html

[S19] C：快速排序
来源：http://dali.feifeiyinyue.top/Article/details/gtjgjbqxov.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtotjxswrv.html

[S20] C：二分查找
来源：http://dali.nwbrower.top/Article/details/gtcbzbkxir.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.kuanghao11.cn/Article/details/gtmqzugszf.html

[S21] C：字符类别判断
来源：http://dali.xinyue.icu/Article/details/gtmmnfnxov.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xuanzx.com/Article/details/gtosfqiico.html

[S22] C：字符串转数字
来源：http://dali.iojbl.cn/Article/details/gtrqrkrtgv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhiwuduotai.top/Article/details/gtjoijnukw.html

[S23] C：随机数
来源：http://dali.cucudq.cn/Article/details/gttwuhponr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yangfankeji.com/Article/details/gtowzeincc.html

[S24] C：获取本地时间
来源：http://dali.zhengqikj.top/Article/details/gtvuftxndf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhongyouzk.top/Article/details/gtanlhhtio.html

[S25] C：内存拷贝
来源：http://dali.shzxlz.cn/Article/details/gtxzoxbuip.html

memcpy(dst, src, n);
来源：http://dali.xuetiantiany.cn/Article/details/gtusvqicnh.html

[S26] C：内存清零
来源：http://dali.9152youxi.cn/Article/details/gtftzkgnnr.html

memset(a, 0, sizeof a);
来源：http://dali.hywenlv.cn/Article/details/gtyvalwhae.html

[S27] C：定义常量
来源：http://dali.feifeiyinyue.top/Article/details/gtpusvkwyt.html

const double PI = 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gtnizemuui.html

[S28] C：静态变量
来源：http://dali.hongshengwenyu.top/Article/details/gtmrxzpvrn.html

static int counter = 0;
来源：http://dali.pycfn.com/Article/details/gtpdwyobjo.html

[S29] C：变参函数
来源：http://dali.xinyue.icu/Article/details/gtlvaxaalf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hywenlv.cn/Article/details/gteomrtvub.html

[S30] C：头文件保护
来源：http://dali.meibo888.top/Article/details/gttvwofoyk.html

#ifndef X_H
来源：http://dali.hysaishi.cn/Article/details/gtqblcraxj.html

#define X_H
来源：http://dali.vqdsnc.cn/Article/details/gtaymypied.html

#endif
来源：http://dali.yj20258888.top/Article/details/gteeqpejkg.html

[S31] C++：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtdharvayv.html

#include <iostream>
来源：http://dali.jyoumei.cn/Article/details/gturbjvcle.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.haohaochexian.top/Article/details/gtwzudhemi.html

[S32] C++：字符串
来源：http://dali.smart0.xyz/Article/details/gtvvayfkak.html

std::string s = "hi";  s += "!";
来源：http://dali.zhongyouzk.top/Article/details/gtdhwurcyg.html

[S33] C++：vector 增删
来源：http://dali.havefunace.top/Article/details/gtklzcpryp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sufxvd.cn/Article/details/gtkyeerdvs.html

[S34] C++：遍历 vector
来源：http://dali.hongshengwenyu.top/Article/details/gtxugpvkmg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yangfankeji.com/Article/details/gtpeymcqgq.html

[S35] C++：map
来源：http://dali.jlsjyb.cn/Article/details/gtcdlvapux.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtxlxxgxmy.html

[S36] C++：unordered_map
来源：http://dali.hfpthk.cn/Article/details/gtgizxgaqq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sysykeji.top/Article/details/gtgklrbjtf.html

[S37] C++：set
来源：http://dali.nanxuanxn.top/Article/details/gtzqicqyhr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.9152youxi.cn/Article/details/gtadzfesyf.html

[S38] C++：排序
来源：http://dali.haohaochexian.top/Article/details/gtjbvjpfat.html

std::sort(v.begin(), v.end());
来源：http://dali.nanxuanxn.top/Article/details/gtqouqllvo.html

[S39] C++：自定义比较器排序
来源：http://dali.yj20258.top/Article/details/gthetremab.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xinyue.icu/Article/details/gtonnjlxje.html

[S40] C++：查找元素
来源：http://dali.ydzc1.top/Article/details/gthkuqwiyj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj202588.top/Article/details/gtcwtxbkho.html

[S41] C++：类与构造函数
来源：http://dali.zhoulong.xyz/Article/details/gtjorvktkm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzhpxstzp.html

[S42] C++：继承与虚函数
来源：http://dali.wangshuangyany.cn/Article/details/gtyasxgbfv.html

class B : public Base { public: void f() override {} };
来源：http://dali.shuidangran.top/Article/details/gtvntnqhoe.html

[S43] C++：智能指针
来源：http://dali.chenzaomai.com/Article/details/gtflbrtjix.html

auto p = std::make_unique<int>(5);
来源：http://dali.yanxiufei.cn/Article/details/gtwpbdivjj.html

[S44] C++：引用传参
来源：http://dali.zycfv.cn/Article/details/gtdohuluxl.html

void inc(int &x) { ++x; }
来源：http://dali.ivvv.top/Article/details/gttwmocxxs.html

[S45] C++：lambda
来源：http://dali.dashuyun.cn/Article/details/gtlhkotsea.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj20258888.top/Article/details/gtgmjokgfw.html

[S46] C++：函数模板
来源：http://dali.hammf.cn/Article/details/gtrmoyknxj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.daxiang520.top/Article/details/gtpozqehli.html

[S47] C++：结构化绑定遍历
来源：http://dali.cucudq.cn/Article/details/gtntcgloed.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hammf.cn/Article/details/gtdkdsywzi.html

[S48] C++：逐行读文件
来源：http://dali.316326.xyz/Article/details/gtjysftbeb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.guowangkeji.top/Article/details/gtqupnnyrj.html

while (std::getline(in, line)) { }
来源：http://dali.dianchejie.cn/Article/details/gtpztaobwd.html

[S49] C++：写文件
来源：http://dali.shangyingyoupin.top/Article/details/gtsywscxny.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhixingplan.top/Article/details/gtvoasvouz.html

[S50] C++：格式化数字
来源：http://dali.cqqwz.cn/Article/details/gtgdmemwih.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gtzeykxbri.html

[S51] C++：显式类型转换
来源：http://dali.cucudq.cn/Article/details/gtoycyukwa.html

static_cast<double>(a) / b
来源：http://dali.xylfe.cn/Article/details/gtvhqbxjup.html

[S52] C++：const 与 noexcept
来源：http://dali.bjfxy.top/Article/details/gttlebighm.html

int size() const noexcept { return n_; }
来源：http://dali.ivvv.top/Article/details/gtjwhaxxga.html

[S53] C++：移动语义
来源：http://dali.sysykeji.top/Article/details/gtxmgymqye.html

std::vector<int> w = std::move(v);
来源：http://dali.ehwqpu.com/Article/details/gtuusesiot.html

[S54] C++：异常处理
来源：http://dali.yuxming.cn/Article/details/gtdhqsmdmh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yueranfly.top/Article/details/gtytpikxqu.html

[S55] C++：结构化绑定
来源：http://dali.jinghuilouyu.cn/Article/details/gtsbyrhale.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.0kj1m.cn/Article/details/gtxdkcboyd.html

[S56] C++：optional
来源：http://dali.yuxming.cn/Article/details/gttvanjjvt.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtktnyctis.html

[S57] C++：编译期常量
来源：http://dali.yuxming.cn/Article/details/gtwvvsglqm.html

constexpr int N = 10;
来源：http://dali.jqgufenzy.top/Article/details/gthzwssybn.html

[S58] C++：命名空间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgptwysno.html

namespace ns { int f() { return 1; } }
来源：http://dali.nanxuanxn.top/Article/details/gtwnexfhyf.html

[S59] C++：静态断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxtqrjmfu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tanke756.top/Article/details/gtmpoezyaq.html

[S60] C++：遍历并删除元素
来源：http://dali.wangdashe.top/Article/details/gtcxzwtbip.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tanke756.top/Article/details/gtqohqekqv.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtumzrneeq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.guowangkeji.top/Article/details/gthzztpdgd.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtokiqycob.html

[T01] Kotlin：Hello World
来源：http://dali.fengsongda.top/Article/details/gtexsdrdgx.html

println("Hello")
来源：http://dali.jiagoushi.top/Article/details/gtzanoebpy.html

[T02] Kotlin：变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcragwphp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.nwbrower.top/Article/details/gtrucnacym.html

[T03] Kotlin：字符串模板
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfqgegfca.html

"值: $b"
来源：http://dali.hammf.cn/Article/details/gtemaricbk.html

[T04] Kotlin：空安全
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjrdcluea.html

val n: String? = null;  n?.length
来源：http://dali.zycfv.cn/Article/details/gtscdwlqdu.html

[T05] Kotlin：when 表达式
来源：http://dali.guannengcc.top/Article/details/gtlgsmljtx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.daria6918.cn/Article/details/gtpagohphy.html

[T06] Kotlin：集合映射
来源：http://dali.hfpthk.cn/Article/details/gtjiwuffaf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtxhlvikpn.html

[T07] Kotlin：集合过滤
来源：http://dali.yonumen.top/Article/details/gttngzqflt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.snrcjt.cn/Article/details/gtogooigwy.html

[T08] Kotlin：数据类
来源：http://dali.vqdsnc.cn/Article/details/gtryouvdvy.html

data class User(val name: String, val age: Int)
来源：http://dali.svipenyu.cn/Article/details/gttyaxuekl.html

[T09] Kotlin：扩展函数
来源：http://dali.tian-w.cn/Article/details/gthfszaeol.html

fun String.exclaim() = this + "!"
来源：http://dali.yj20258.top/Article/details/gtgqlaonfy.html

[T10] Kotlin：默认参数
来源：http://dali.hysaishi.cn/Article/details/gtahrckocy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.nanxuanxn.top/Article/details/gteosalptx.html

[T11] Kotlin：协程
来源：http://dali.wangshuangyany.cn/Article/details/gtyqsohuzd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yvedp.cn/Article/details/gtjjagqncp.html

[T12] Kotlin：解构声明
来源：http://dali.jqgfzy.top/Article/details/gtxoawzpjv.html

val (a, b) = Pair(1, 2)
来源：http://dali.xuanzx.com/Article/details/gtempsfwew.html

[T13] Kotlin：只读 Map
来源：http://dali.nanxinkj.top/Article/details/gthsboxnnj.html

val m = mapOf("a" to 1)
来源：http://dali.smart0.xyz/Article/details/gtmzccsvxz.html

[T14] Kotlin：循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzyrdikcx.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gtxwtsgbmw.html

[T15] Kotlin：接口
来源：http://dali.wangdashe.top/Article/details/gterlckvzj.html

interface Shape { fun area(): Double }
来源：http://dali.haohaochexian.top/Article/details/gtuulaingm.html

[T16] Swift：Hello World
来源：http://dali.yj20258888.top/Article/details/gtubqvmrke.html

print("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gtssrtzdoc.html

[T17] Swift：变量与常量
来源：http://dali.fengsongda.top/Article/details/gtceedzgbl.html

var a = 1;  let b = 2
来源：http://dali.pycfn.com/Article/details/gtglntdaxy.html

[T18] Swift：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gtxixpslbx.html

"值: \(b)"
来源：http://dali.smart0.xyz/Article/details/gtvrtmakbd.html

[T19] Swift：可选绑定
来源：http://dali.shangyingyoupin.top/Article/details/gtuzqewvcy.html

if let n = opt { print(n) }
来源：http://dali.yanxiufei.cn/Article/details/gtkiekaraw.html

[T20] Swift：数组操作
来源：http://dali.birdmap.top/Article/details/gtjabkpjyz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.quarkkingdee.top/Article/details/gtslfgbtwi.html

[T21] Swift：遍历
来源：http://dali.jianghu66.top/Article/details/gtinegmyiz.html

for x in a { print(x) }
来源：http://dali.yj20258888.top/Article/details/gttzmzzgfx.html

[T22] Swift：字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgzqdlfkg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.tanke756.top/Article/details/gttztmcwuq.html

[T23] Swift：函数
来源：http://dali.jiagoushi.top/Article/details/gtbbphetyu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.nanxuanxn.top/Article/details/gtixlnyefa.html

[T24] Swift：闭包
来源：http://dali.svipenyu.cn/Article/details/gtfgicobiu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinqigufen.top/Article/details/gtcntezybe.html

[T25] Swift：结构体
来源：http://dali.shuidangran.top/Article/details/gtqraogweo.html

struct P { var x: Int }
来源：http://dali.zdqjudy.top/Article/details/gtinlpknbb.html

[T26] Swift：类与重写
来源：http://dali.jqgfzy.top/Article/details/gtenhbwzyd.html

class A: Base { override func f() {} }
来源：http://dali.cashguo.top/Article/details/gtoycgusaq.html

[T27] Swift：错误处理
来源：http://dali.quarkkingdee.top/Article/details/gtgfwzjbue.html

do { try f() } catch { print(error) }
来源：http://dali.ivvv.top/Article/details/gttjlofyxs.html

[T28] Swift：枚举
来源：http://dali.yuanzhike.top/Article/details/gtwizfcawf.html

enum Color { case red, green }
来源：http://dali.hysaishi.cn/Article/details/gtzqfaomgv.html

[T29] Swift：guard 提前返回
来源：http://dali.sufxvd.cn/Article/details/gtrwzzqpht.html

guard let x = opt else { return }
来源：http://dali.xuanzx.com/Article/details/gtzseiftzf.html

[T30] Swift：协议
来源：http://dali.hywenlv.cn/Article/details/gtobogsfey.html

protocol Shape { func area() -> Double }
来源：http://dali.iojbl.cn/Article/details/gticzpbfmn.html

[T31] Lua：Hello World
来源：http://dali.cashguo.top/Article/details/gtfgucwttm.html

print("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gtpqqjcfwp.html

[T32] Lua：局部变量
来源：http://dali.hnqzz.top/Article/details/gtpqyhttsm.html

local a = 1
来源：http://dali.sweek.top/Article/details/gtugniozqy.html

[T33] Lua：表（数组）
来源：http://dali.jlsjyb.cn/Article/details/gtfrjeqgbr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.gogol.net.cn/Article/details/gtbgndltgk.html

[T34] Lua：遍历表
来源：http://dali.cdnleiting.top/Article/details/gtwauneoew.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yj20258.top/Article/details/gtnzmubirj.html

[T35] Lua：字典表
来源：http://dali.nwbrower.top/Article/details/gtmamuojpe.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tian-w.cn/Article/details/gtioprrqnw.html

[T36] Lua：函数
来源：http://dali.zycfv.cn/Article/details/gtcpgrqtsg.html

function add(a, b) return a + b end
来源：http://dali.tian-w.cn/Article/details/gtqsuoxbdu.html

[T37] Lua：字符串拼接
来源：http://dali.jiagoushi.top/Article/details/gtwkphnjal.html

"a" .. "b"
来源：http://dali.nanxuanxn.top/Article/details/gtlwysqbfp.html

[T38] Lua：条件
来源：http://dali.sysykeji.top/Article/details/gtnpuozzmu.html

if x > 0 then print("正") end
来源：http://dali.hywenlv.cn/Article/details/gtirsfnhok.html

[T39] Lua：模式匹配
来源：http://dali.gaohongyu789.top/Article/details/gtnjxqfgoc.html

string.find(s, "%d+")
来源：http://dali.yueranfly.top/Article/details/gtwhdappek.html

[T40] Lua：元表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdfvpxgfc.html

setmetatable({}, { __index = base })
来源：http://dali.jiagoushi.top/Article/details/gtusughrby.html

[T41] Perl：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtbxjwnfmq.html

print "Hello\n";
来源：http://dali.ppjwa.cn/Article/details/gtpccrzobl.html

[T42] Perl：变量类型
来源：http://dali.mhx1999.top/Article/details/gtidnxuhlt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xuanzx.com/Article/details/gtzdfphmkn.html

[T43] Perl：字符串插值
来源：http://dali.yonumen.top/Article/details/gtlkbfotko.html

"值: $a"
来源：http://dali.xylfe.cn/Article/details/gtfwttuvmb.html

[T44] Perl：条件
来源：http://dali.sweek.top/Article/details/gtgokqqtdu.html

if ($a > 0) { print "正"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtkqdknris.html

[T45] Perl：数组遍历
来源：http://dali.cqqwz.cn/Article/details/gtpaqtvdcl.html

for my $x (@arr) { print $x; }
来源：http://dali.zycfv.cn/Article/details/gtdjktpgzt.html

[T46] Perl：哈希操作
来源：http://dali.0kj1m.cn/Article/details/gtmydmpakq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtpnkffgng.html

[T47] Perl：正则捕获
来源：http://dali.jqgfzy.top/Article/details/gtmrtkpzrw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.nanxinkj.top/Article/details/gtkgzllnab.html

[T48] Perl：正则替换
来源：http://dali.gotoacloud.top/Article/details/gtuyjhlxfq.html

$s =~ s/old/new/g;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtavfpnizn.html

[T49] Perl：函数
来源：http://dali.yj202588.top/Article/details/gtwhqqbfll.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gtttimdlis.html

[T50] Perl：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gtznswiwtv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.daxiang520.top/Article/details/gtlswwbntu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.9152youxi.cn/Article/details/gtwrhsbddg.html

[T51] Scala：Hello World
来源：http://dali.guannengcc.top/Article/details/gtpvxduhwr.html

println("Hello")
来源：http://dali.tianlin.xyz/Article/details/gtlnvgzabp.html

[T52] Scala：变量
来源：http://dali.jyoumei.cn/Article/details/gtndvocbkb.html

val a = 1;  var b = 2
来源：http://dali.nwbrower.top/Article/details/gtzqutdtwx.html

[T53] Scala：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gtnaubfizg.html

s"值: $b"
来源：http://dali.guowangkeji.top/Article/details/gtelexczym.html

[T54] Scala：集合映射
来源：http://dali.aibaodan.cn/Article/details/gtprockfju.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gzhubu.top/Article/details/gtitaoltcp.html

[T55] Scala：集合过滤
来源：http://dali.yvedp.cn/Article/details/gtpzkvkwgj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.havefunace.top/Article/details/gtfckgscxm.html

[T56] Scala：样例类
来源：http://dali.cqqwz.cn/Article/details/gtvsjyiuyg.html

case class User(name: String, age: Int)
来源：http://dali.zycfv.cn/Article/details/gtgxogecqf.html

[T57] Scala：模式匹配
来源：http://dali.hammf.cn/Article/details/gtcrabcfwp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yuxming.cn/Article/details/gtwqnscshg.html

[T58] Scala：函数定义
来源：http://dali.fzhhl.top/Article/details/gtxhjthyiu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sufxvd.cn/Article/details/gtcdcrdmtj.html

[T59] Scala：循环
来源：http://dali.jinqigfzy.top/Article/details/gtfxdcqpig.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gtafkqmddc.html

[T60] Scala：折叠
来源：http://dali.yangfankeji.com/Article/details/gtgncnkini.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tianlin.xyz/Article/details/gtvritjbyq.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtcfgbxxeb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jqgfzy.top/Article/details/gtpkinorvr.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtodkggplo.html

[U01] Py：创建虚拟环境
来源：http://dali.zhoulong.xyz/Article/details/gtdjfeejyj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.redwolf501.top/Article/details/gtuuozhrjb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.fzhhl.top/Article/details/gtvksltykg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yuanzhike.top/Article/details/gtqyiupekq.html

[U03] Py：加载 .env 配置
来源：http://dali.mhx1999.top/Article/details/gtpcijzrnm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yanxiufei.cn/Article/details/gtcksbuvbo.html

[U04] Py：变量调试打印
来源：http://dali.dianchejie.cn/Article/details/gthkxoxsdr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.daxiang520.top/Article/details/gtwjydtgif.html

[U05] Py：列表去重且保序
来源：http://dali.xuanzx.com/Article/details/gtmncfymjt.html

list(dict.fromkeys(arr))
来源：http://dali.chenlongwang.top/Article/details/gtvgornobw.html

[U06] Py：合并两个字典
来源：http://dali.hnqzz.top/Article/details/gtptwzozlc.html

{**a, **b}
来源：http://dali.chenlongwang.top/Article/details/gtuxvdwwwh.html

[U07] Py：反转字典键值
来源：http://dali.shzxlz.cn/Article/details/gtjwxzazjz.html

{v: k for k, v in d.items()}
来源：http://dali.vqdsnc.cn/Article/details/gtvomohrjc.html

[U08] Py：展平二维列表
来源：http://dali.wangdashe.top/Article/details/gtwiqnqtjk.html

[y for x in nested for y in x]
来源：http://dali.smart0.xyz/Article/details/gtmihovvmp.html

[U09] Py：字典取最大值的键
来源：http://dali.yuxming.cn/Article/details/gtxdghotvv.html

max(d, key=d.get)
来源：http://dali.wangdashe.top/Article/details/gtjpwlgphb.html

[U10] Py：按值排序字典
来源：http://dali.ybcxt.top/Article/details/gtvzotfuhh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.tanke756.top/Article/details/gtuvxetumy.html

[U11] Py：生成器表达式
来源：http://dali.ehwqpu.com/Article/details/gtdepgfhue.html

(x * 2 for x in arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkqvfwanz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yj20258.top/Article/details/gthtkpopkw.html

Counter(arr).most_common(3)
来源：http://dali.pycfn.com/Article/details/gtmzpjkkmj.html

[U13] Py：固定长度队列
来源：http://dali.andypj.xyz/Article/details/gtjesjfhme.html

deque(maxlen=10)
来源：http://dali.yuxming.cn/Article/details/gtarphxeuh.html

[U14] Py：分组收集到列表
来源：http://dali.jqgufenzy.top/Article/details/gtvtxmsoyi.html

defaultdict(list)
来源：http://dali.meibo888.top/Article/details/gtzfwivbre.html

[U15] Py：高精度计时
来源：http://dali.yuxming.cn/Article/details/gtrccukhfa.html

t = time.perf_counter()
来源：http://dali.ybcxt.top/Article/details/gtvuotqbmc.html

[U16] Py：命令行参数解析
来源：http://dali.zhixingplan.top/Article/details/gtoigprtyh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.feifeiyinyue.top/Article/details/gtwyvcbaup.html

[U17] Py：初始化日志
来源：http://dali.zdqjudy.top/Article/details/gtgzlctklv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xuanzx.com/Article/details/gteumnckxm.html

[U18] Py：预编译正则
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfmxqsjrp.html

pat = re.compile(r"\d+")
来源：http://dali.fengsongda.top/Article/details/gtnpqdjosb.html

[U19] Py：正则替换带回调
来源：http://dali.pycfn.com/Article/details/gtblqbmvzq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zycfv.cn/Article/details/gtrvilqwku.html

[U20] Py：缓存函数结果
来源：http://dali.haohaochexian.top/Article/details/gtgbxzcuhr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.nanxinkj.top/Article/details/gtczbvtapp.html

[U21] Py：自定义上下文管理器
来源：http://dali.cheryme.top/Article/details/gttnxcdnkp.html

@contextlib.contextmanager
来源：http://dali.zhiwuduotai.top/Article/details/gtywjyhtcc.html

[U22] Py：矩阵转置
来源：http://dali.dashuyun.cn/Article/details/gtfjhfteio.html

list(zip(*m))
来源：http://dali.jianghu66.top/Article/details/gtmtklzumn.html

[U23] Py：分块读取大文件
来源：http://dali.zhongyouzk.top/Article/details/gtstkbjgzb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jyoumei.cn/Article/details/gtvxifbrfl.html

[U24] Py：路径操作
来源：http://dali.nwbrower.top/Article/details/gtlxwpmuln.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.iojbl.cn/Article/details/gtmytqpari.html


<!-- 参考信息 -->