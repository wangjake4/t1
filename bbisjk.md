代发 wailian999

int x; scanf("%d", &x);
来源：http://dali.wangshuangyany.cn/Article/details/gtgsagienj.html

[S04] C：字符串复制
来源：http://dali.tianlin.xyz/Article/details/gtkjgxbnrj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sysykeji.top/Article/details/gtjzaldbqt.html

[S05] C：字符串长度
来源：http://dali.dianchejie.cn/Article/details/gttktxxhmp.html

strlen(s)
来源：http://dali.mhx1999.top/Article/details/gttrshvkod.html

[S06] C：字符串比较
来源：http://dali.zhixingplan.top/Article/details/gtqcoankej.html

strcmp(a, b) == 0
来源：http://dali.cucudq.cn/Article/details/gtdvjhtbqo.html

[S07] C：数组遍历求和
来源：http://dali.redwolf501.top/Article/details/gtfajurnbl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ybcxt.top/Article/details/gtmymfpnvd.html

[S08] C：动态内存分配与释放
来源：http://dali.redwolf501.top/Article/details/gtuavvyjla.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.kuanghao11.cn/Article/details/gthsjqfafg.html

[S09] C：结构体定义与初始化
来源：http://dali.birdmap.top/Article/details/gtatlmeini.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.snrcjt.cn/Article/details/gtvqnqrpyn.html

[S10] C：指针与解引用
来源：http://dali.jqgfzy.top/Article/details/gtjnpwgckv.html

int *p = &a;  *p = 5;
来源：http://dali.ehwqpu.com/Article/details/gtymrlqxqb.html

[S11] C：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gteuguuhdw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hysaishi.cn/Article/details/gtppjktejo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttlljnlwr.html

fclose(f);
来源：http://dali.chenjidiqi.icu/Article/details/gthmasaccm.html

[S12] C：写文件
来源：http://dali.ehwqpu.com/Article/details/gtxjodlrft.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.haohaochexian.top/Article/details/gtihlloxpm.html

[S13] C：宏定义
来源：http://dali.sysykeji.top/Article/details/gteogcadmd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nwbrower.top/Article/details/gtatggrork.html

[S14] C：枚举
来源：http://dali.nanxuanxn.top/Article/details/gtgrxsnney.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jqgufenzy.top/Article/details/gtwgoknvwu.html

[S15] C：类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtytaxhktl.html

(double) a / b
来源：http://dali.jinqigufen.top/Article/details/gtyoxflukp.html

[S16] C：位操作置位
来源：http://dali.aizwys.cn/Article/details/gtdcdgxjwi.html

x |= (1 << 3);
来源：http://dali.dianchejie.cn/Article/details/gttlbnprlg.html

[S17] C：安全拼接字符串
来源：http://dali.zhixingplan.top/Article/details/gttnalcrfz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yj202588.top/Article/details/gtvrqpeojs.html

[S18] C：命令行参数
来源：http://dali.daxiang520.top/Article/details/gtkospnljs.html

int main(int argc, char **argv)
来源：http://dali.sweek.top/Article/details/gtxpcsbpvt.html

[S19] C：快速排序
来源：http://dali.wangdashe.top/Article/details/gtdqhjieeu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gtwdhoopgo.html

[S20] C：二分查找
来源：http://dali.xinyue.icu/Article/details/gtpqwcitvq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.iojbl.cn/Article/details/gtafhhkbnm.html

[S21] C：字符类别判断
来源：http://dali.hammf.cn/Article/details/gtwxipozlx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jqgfzy.top/Article/details/gtllrmijkp.html

[S22] C：字符串转数字
来源：http://dali.jinghuilouyu.cn/Article/details/gtlnjduxmo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.mhx1999.top/Article/details/gtwmkniyvp.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gttyzdnqyc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sufxvd.cn/Article/details/gtokhjszax.html

[S24] C：获取本地时间
来源：http://dali.guowangkeji.top/Article/details/gttvvefmwh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj20258.top/Article/details/gtfclcwqqf.html

[S25] C：内存拷贝
来源：http://dali.tianlin.xyz/Article/details/gtcuvplnnr.html

memcpy(dst, src, n);
来源：http://dali.dashuyun.cn/Article/details/gtxwxwokwo.html

[S26] C：内存清零
来源：http://dali.jinqigfzy.top/Article/details/gtegovmrzs.html

memset(a, 0, sizeof a);
来源：http://dali.pycfn.com/Article/details/gtjafotdtd.html

[S27] C：定义常量
来源：http://dali.jinqigfzy.top/Article/details/gtvgrkhybi.html

const double PI = 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gtzoudjmde.html

[S28] C：静态变量
来源：http://dali.xylfe.cn/Article/details/gtygadbuvq.html

static int counter = 0;
来源：http://dali.sxryk.cn/Article/details/gtsazrhnmj.html

[S29] C：变参函数
来源：http://dali.smart0.xyz/Article/details/gtawcesdfa.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sweek.top/Article/details/gtvylmgcmg.html

[S30] C：头文件保护
来源：http://dali.xuanzx.com/Article/details/gtgwmuxzqg.html

#ifndef X_H
来源：http://dali.chenjidiqi.icu/Article/details/gtiowqcfzd.html

#define X_H
来源：http://dali.yonumen.top/Article/details/gtxnzynbvl.html

#endif
来源：http://dali.316326.xyz/Article/details/gtejmhzxkx.html

[S31] C++：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtgxrxufuk.html

#include <iostream>
来源：http://dali.fengsongda.top/Article/details/gtzkxkkkfh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.quarkkingdee.top/Article/details/gtiispbaya.html

[S32] C++：字符串
来源：http://dali.guannengcc.top/Article/details/gtlqpdorza.html

std::string s = "hi";  s += "!";
来源：http://dali.yueranfly.top/Article/details/gtycrasbhe.html

[S33] C++：vector 增删
来源：http://dali.xylfe.cn/Article/details/gtfvpoalob.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.daxiang520.top/Article/details/gtqxgzfabs.html

[S34] C++：遍历 vector
来源：http://dali.chenzaomai.com/Article/details/gtdpntnmct.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.dashuyun.cn/Article/details/gtghixrmcv.html

[S35] C++：map
来源：http://dali.havefunace.top/Article/details/gtcyyqgfbo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gtaxglvqcq.html

[S36] C++：unordered_map
来源：http://dali.jiagoushi.top/Article/details/gtjrikqmie.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gtuyxjemyy.html

[S37] C++：set
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzblhtbyv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinqigfzy.top/Article/details/gtlkffensd.html

[S38] C++：排序
来源：http://dali.yj20258.top/Article/details/gtcdvojzmy.html

std::sort(v.begin(), v.end());
来源：http://dali.ydzc1.top/Article/details/gtdeomtqsl.html

[S39] C++：自定义比较器排序
来源：http://dali.mhx1999.top/Article/details/gtmuekmdxt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.wangshuangyany.cn/Article/details/gtlknlosdu.html

[S40] C++：查找元素
来源：http://dali.wangdashe.top/Article/details/gtsfsktdew.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.316326.xyz/Article/details/gtytayorhj.html

[S41] C++：类与构造函数
来源：http://dali.kuanghao11.cn/Article/details/gtmvtezsbp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwrtxegcw.html

[S42] C++：继承与虚函数
来源：http://dali.svipenyu.cn/Article/details/gtncjwgpgr.html

class B : public Base { public: void f() override {} };
来源：http://dali.pengpengdd.cyou/Article/details/gtaxgugjaz.html

[S43] C++：智能指针
来源：http://dali.0kj1m.cn/Article/details/gtuqhduokr.html

auto p = std::make_unique<int>(5);
来源：http://dali.hysaishi.cn/Article/details/gtmtbhuroz.html

[S44] C++：引用传参
来源：http://dali.tianlin.xyz/Article/details/gtckurotxl.html

void inc(int &x) { ++x; }
来源：http://dali.meibo888.top/Article/details/gthyfybqxr.html

[S45] C++：lambda
来源：http://dali.dianchejie.cn/Article/details/gtzeefkgif.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtenfvhsfz.html

[S46] C++：函数模板
来源：http://dali.jinyuanbaomall.cn/Article/details/gttxyjgtdf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.andypj.xyz/Article/details/gtjpyyhgpr.html

[S47] C++：结构化绑定遍历
来源：http://dali.0kj1m.cn/Article/details/gtuvsxuaea.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sysykeji.top/Article/details/gtnfchperv.html

[S48] C++：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gtsypblkjv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhoulong.xyz/Article/details/gtiolnzkzm.html

while (std::getline(in, line)) { }
来源：http://dali.zhixingplan.top/Article/details/gtmwnththq.html

[S49] C++：写文件
来源：http://dali.shangyingyoupin.top/Article/details/gtuwilfpeh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.wangshuangyany.cn/Article/details/gtssuossgq.html

[S50] C++：格式化数字
来源：http://dali.pycfn.com/Article/details/gtkgmuhidz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gtyqdxdrow.html

[S51] C++：显式类型转换
来源：http://dali.yvedp.cn/Article/details/gtzapzcqun.html

static_cast<double>(a) / b
来源：http://dali.9152youxi.cn/Article/details/gtwvvgantx.html

[S52] C++：const 与 noexcept
来源：http://dali.pycfn.com/Article/details/gtpflgbasm.html

int size() const noexcept { return n_; }
来源：http://dali.svipenyu.cn/Article/details/gteqdtbfau.html

[S53] C++：移动语义
来源：http://dali.ydzc1.top/Article/details/gtvdzedbpn.html

std::vector<int> w = std::move(v);
来源：http://dali.yangfankeji.com/Article/details/gtnbnnqqtg.html

[S54] C++：异常处理
来源：http://dali.0kj1m.cn/Article/details/gtqjubuasg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sweek.top/Article/details/gtlqjhqqna.html

[S55] C++：结构化绑定
来源：http://dali.gotoacloud.top/Article/details/gthhgffssg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.tianlin.xyz/Article/details/gthylpgibq.html

[S56] C++：optional
来源：http://dali.shuidangran.top/Article/details/gtewgoijnv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zdqjudy.top/Article/details/gtnmhcszif.html

[S57] C++：编译期常量
来源：http://dali.yangfankeji.com/Article/details/gtbmsmzqiv.html

constexpr int N = 10;
来源：http://dali.cdnleiting.top/Article/details/gtelqbokwf.html

[S58] C++：命名空间
来源：http://dali.hnxiangtu.top/Article/details/gtlwoquynu.html

namespace ns { int f() { return 1; } }
来源：http://dali.yuxming.cn/Article/details/gtbhjjytve.html

[S59] C++：静态断言
来源：http://dali.jyoumei.cn/Article/details/gtkqnpnnzj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jiagoushi.top/Article/details/gthuqkpbvg.html

[S60] C++：遍历并删除元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjuyffgsg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xziqi.cn/Article/details/gtvtbxaufr.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtbpvpjiao.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xuanzx.com/Article/details/gtkdayfjli.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtshyknybs.html

[T01] Kotlin：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtbrejolqu.html

println("Hello")
来源：http://dali.sufxvd.cn/Article/details/gtfjegaifk.html

[T02] Kotlin：变量
来源：http://dali.xylfe.cn/Article/details/gtionmloor.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hammf.cn/Article/details/gtnpgmiuhk.html

[T03] Kotlin：字符串模板
来源：http://dali.quarkkingdee.top/Article/details/gtxxjszfsg.html

"值: $b"
来源：http://dali.chenjidiqi.icu/Article/details/gtueelcbnr.html

[T04] Kotlin：空安全
来源：http://dali.yj20258.top/Article/details/gttneyexgs.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gtixkxhzww.html

[T05] Kotlin：when 表达式
来源：http://dali.yonumen.top/Article/details/gtewxrkuzu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.guowangkeji.top/Article/details/gtdfpsygqi.html

[T06] Kotlin：集合映射
来源：http://dali.smart0.xyz/Article/details/gturkqzmxw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hfpthk.cn/Article/details/gtkuqxynft.html

[T07] Kotlin：集合过滤
来源：http://dali.hnqzz.top/Article/details/gtynydpqoh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.0kj1m.cn/Article/details/gtbqkglsgp.html

[T08] Kotlin：数据类
来源：http://dali.snrcjt.cn/Article/details/gtdqslmvrf.html

data class User(val name: String, val age: Int)
来源：http://dali.yongpay.top/Article/details/gtovbdhras.html

[T09] Kotlin：扩展函数
来源：http://dali.ppjwa.cn/Article/details/gtixcstabe.html

fun String.exclaim() = this + "!"
来源：http://dali.hywenlv.cn/Article/details/gtdthxbxur.html

[T10] Kotlin：默认参数
来源：http://dali.andypj.xyz/Article/details/gtxtuqsssy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ybcxt.top/Article/details/gtuakczrkt.html

[T11] Kotlin：协程
来源：http://dali.yangfankeji.com/Article/details/gtebjyqimt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.redwolf501.top/Article/details/gtczjweiii.html

[T12] Kotlin：解构声明
来源：http://dali.zycfv.cn/Article/details/gtzuastzpq.html

val (a, b) = Pair(1, 2)
来源：http://dali.yangfankeji.com/Article/details/gtmhcjykis.html

[T13] Kotlin：只读 Map
来源：http://dali.cqqwz.cn/Article/details/gtjcbqofdc.html

val m = mapOf("a" to 1)
来源：http://dali.fzhhl.top/Article/details/gtturntjda.html

[T14] Kotlin：循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrnlmkydo.html

for (i in 1..10) println(i)
来源：http://dali.dianchejie.cn/Article/details/gtilvbqbis.html

[T15] Kotlin：接口
来源：http://dali.xuetiantiany.cn/Article/details/gtwbghuikq.html

interface Shape { fun area(): Double }
来源：http://dali.meibo888.top/Article/details/gtjrdybskl.html

[T16] Swift：Hello World
来源：http://dali.aizwys.cn/Article/details/gtexjjncjp.html

print("Hello")
来源：http://dali.cheryme.top/Article/details/gtnzygdeux.html

[T17] Swift：变量与常量
来源：http://dali.xylfe.cn/Article/details/gtrgprhvbk.html

var a = 1;  let b = 2
来源：http://dali.yueranfly.top/Article/details/gttdsqnipb.html

[T18] Swift：字符串插值
来源：http://dali.yueranfly.top/Article/details/gtwzhlblva.html

"值: \(b)"
来源：http://dali.iojbl.cn/Article/details/gtrsjigxic.html

[T19] Swift：可选绑定
来源：http://dali.jinghuilouyu.cn/Article/details/gtscnyjxzz.html

if let n = opt { print(n) }
来源：http://dali.andypj.xyz/Article/details/gtyoqpqizt.html

[T20] Swift：数组操作
来源：http://dali.zhengqikj.top/Article/details/gthweurflz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.quarkkingdee.top/Article/details/gtvgbachfs.html

[T21] Swift：遍历
来源：http://dali.c1oappe.top/Article/details/gtuzghetsk.html

for x in a { print(x) }
来源：http://dali.havefunace.top/Article/details/gtdwhbzmnc.html

[T22] Swift：字典
来源：http://dali.feifeiyinyue.top/Article/details/gtwvaipsob.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.redwolf501.top/Article/details/gtkkzaziak.html

[T23] Swift：函数
来源：http://dali.gotoacloud.top/Article/details/gtzrxscbax.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sweek.top/Article/details/gtgjinruts.html

[T24] Swift：闭包
来源：http://dali.cashguo.top/Article/details/gtrpaxtxrf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtuocmmnvn.html

[T25] Swift：结构体
来源：http://dali.jyoumei.cn/Article/details/gtuemtimkq.html

struct P { var x: Int }
来源：http://dali.fzhhl.top/Article/details/gtrttxzarn.html

[T26] Swift：类与重写
来源：http://dali.xinyue.icu/Article/details/gtuejzswyf.html

class A: Base { override func f() {} }
来源：http://dali.fzhhl.top/Article/details/gtirzesfgi.html

[T27] Swift：错误处理
来源：http://dali.kuanghao11.cn/Article/details/gtanphouzw.html

do { try f() } catch { print(error) }
来源：http://dali.vqdsnc.cn/Article/details/gtppplxhku.html

[T28] Swift：枚举
来源：http://dali.hywenlv.cn/Article/details/gtlawhsipq.html

enum Color { case red, green }
来源：http://dali.ydzc1.top/Article/details/gtywhroswj.html

[T29] Swift：guard 提前返回
来源：http://dali.cashguo.top/Article/details/gtntcodtnn.html

guard let x = opt else { return }
来源：http://dali.feifeiyinyue.top/Article/details/gtdlzhsqqb.html

[T30] Swift：协议
来源：http://dali.yj202588.top/Article/details/gtsjdsbhqb.html

protocol Shape { func area() -> Double }
来源：http://dali.aibaodan.cn/Article/details/gtkigwtwgz.html

[T31] Lua：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gthvpxzxjj.html

print("Hello")
来源：http://dali.chenzaomai.com/Article/details/gtrempusjh.html

[T32] Lua：局部变量
来源：http://dali.cucudq.cn/Article/details/gtoomxkvol.html

local a = 1
来源：http://dali.kuanghao11.cn/Article/details/gtwbesjlph.html

[T33] Lua：表（数组）
来源：http://dali.gogol.net.cn/Article/details/gtaulmqimz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hywenlv.cn/Article/details/gtriuqrrzs.html

[T34] Lua：遍历表
来源：http://dali.daria6918.cn/Article/details/gtrceklesk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hfpthk.cn/Article/details/gtvztesiby.html

[T35] Lua：字典表
来源：http://dali.yongpay.top/Article/details/gtkjkarcvl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cheryme.top/Article/details/gtdihdqgsn.html

[T36] Lua：函数
来源：http://dali.birdmap.top/Article/details/gtvyiyzqug.html

function add(a, b) return a + b end
来源：http://dali.dashuyun.cn/Article/details/gteazujtmm.html

[T37] Lua：字符串拼接
来源：http://dali.dianchejie.cn/Article/details/gtttzgqkmj.html

"a" .. "b"
来源：http://dali.shangyingyoupin.top/Article/details/gthyuqaqzb.html

[T38] Lua：条件
来源：http://dali.gogol.net.cn/Article/details/gtwvyelkrm.html

if x > 0 then print("正") end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbojqzoah.html

[T39] Lua：模式匹配
来源：http://dali.xziqi.cn/Article/details/gtmrtmmkcy.html

string.find(s, "%d+")
来源：http://dali.guowangkeji.top/Article/details/gtucfnbzqx.html

[T40] Lua：元表
来源：http://dali.xinyue.icu/Article/details/gtdhagqmbg.html

setmetatable({}, { __index = base })
来源：http://dali.gogol.net.cn/Article/details/gtenofomig.html

[T41] Perl：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gticpfural.html

print "Hello\n";
来源：http://dali.ivvv.top/Article/details/gtyposytim.html

[T42] Perl：变量类型
来源：http://dali.shuidangran.top/Article/details/gtssiytrwb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ehwqpu.com/Article/details/gtvbnkkcfj.html

[T43] Perl：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gtidlfcqmp.html

"值: $a"
来源：http://dali.zhoulong.xyz/Article/details/gtcmrimmbm.html

[T44] Perl：条件
来源：http://dali.guowangkeji.top/Article/details/gtqiskpidp.html

if ($a > 0) { print "正"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtyvgiochw.html

[T45] Perl：数组遍历
来源：http://dali.mhx1999.top/Article/details/gtmanoyouj.html

for my $x (@arr) { print $x; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiacucuko.html

[T46] Perl：哈希操作
来源：http://dali.wangshuangyany.cn/Article/details/gtctfengpo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ppjwa.cn/Article/details/gtqwvrtqto.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gtbrngprhf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yj20258.top/Article/details/gtyixfvgoa.html

[T48] Perl：正则替换
来源：http://dali.jinqigfzy.top/Article/details/gtyekeujjr.html

$s =~ s/old/new/g;
来源：http://dali.redwolf501.top/Article/details/gtuswfhona.html

[T49] Perl：函数
来源：http://dali.nanxuanxn.top/Article/details/gtgkmsslug.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.dashuyun.cn/Article/details/gtrqtmcmet.html

[T50] Perl：逐行读文件
来源：http://dali.yongpay.top/Article/details/gtafxzawib.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhixingplan.top/Article/details/gtcudsmvrx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gzhubu.top/Article/details/gtbcalwwjs.html

[T51] Scala：Hello World
来源：http://dali.hammf.cn/Article/details/gtdgcebvgc.html

println("Hello")
来源：http://dali.ybcxt.top/Article/details/gtwbcbtbfk.html

[T52] Scala：变量
来源：http://dali.pengpengdd.cyou/Article/details/gtjqeoonun.html

val a = 1;  var b = 2
来源：http://dali.pengpengdd.cyou/Article/details/gtbaonxdsm.html

[T53] Scala：字符串插值
来源：http://dali.shanyushiyangkeji.top/Article/details/gttzqoszxy.html

s"值: $b"
来源：http://dali.jinghuilouyu.cn/Article/details/gtjpguxjof.html

[T54] Scala：集合映射
来源：http://dali.jqgufenzy.top/Article/details/gteixwvrca.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.316326.xyz/Article/details/gtmgfwncuf.html

[T55] Scala：集合过滤
来源：http://dali.shzxlz.cn/Article/details/gtugrictvn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.birdmap.top/Article/details/gthzuimjon.html

[T56] Scala：样例类
来源：http://dali.yj20258.top/Article/details/gtuccsqeen.html

case class User(name: String, age: Int)
来源：http://dali.zycfv.cn/Article/details/gtokbjgkvd.html

[T57] Scala：模式匹配
来源：http://dali.birdmap.top/Article/details/gtyjuaouuz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gogol.net.cn/Article/details/gtudzklbip.html

[T58] Scala：函数定义
来源：http://dali.shanyushiyangtech.top/Article/details/gthkqblgbb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.316326.xyz/Article/details/gtujiiqxtg.html

[T59] Scala：循环
来源：http://dali.gotoacloud.top/Article/details/gtjazqpszz.html

for (i <- 1 to 10) println(i)
来源：http://dali.jyoumei.cn/Article/details/gtoctsdpxj.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gtlvncyoxx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhiwuduotai.top/Article/details/gtmvaqhfwi.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtefeklmvr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yuxming.cn/Article/details/gtaxptwsen.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtnwtvjeym.html

[U01] Py：创建虚拟环境
来源：http://dali.jyoumei.cn/Article/details/gtqvvcvtwx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jinyuanbaomall.cn/Article/details/gttyclgula.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jlsjyb.cn/Article/details/gtkfdhglan.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xylfe.cn/Article/details/gtmgmpwbjr.html

[U03] Py：加载 .env 配置
来源：http://dali.hongshengwenyu.top/Article/details/gtklyisiee.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.svipenyu.cn/Article/details/gtbkiuuphq.html

[U04] Py：变量调试打印
来源：http://dali.aizwys.cn/Article/details/gtxedzubky.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shuidangran.top/Article/details/gtnchezhou.html

[U05] Py：列表去重且保序
来源：http://dali.dianchejie.cn/Article/details/gticulnwgi.html

list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gtmdyfcanl.html

[U06] Py：合并两个字典
来源：http://dali.pycfn.com/Article/details/gtgjdnxkma.html

{**a, **b}
来源：http://dali.c1oappe.top/Article/details/gtnqairnbz.html

[U07] Py：反转字典键值
来源：http://dali.aizwys.cn/Article/details/gtckttisqq.html

{v: k for k, v in d.items()}
来源：http://dali.wangdashe.top/Article/details/gtgoongeon.html

[U08] Py：展平二维列表
来源：http://dali.wangshuangyany.cn/Article/details/gtcthctvja.html

[y for x in nested for y in x]
来源：http://dali.wangdashe.top/Article/details/gtafonatnb.html

[U09] Py：字典取最大值的键
来源：http://dali.aibaodan.cn/Article/details/gtcyazpuvf.html

max(d, key=d.get)
来源：http://dali.havefunace.top/Article/details/gthkqqolgu.html

[U10] Py：按值排序字典
来源：http://dali.tian-w.cn/Article/details/gtzcjnacwa.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.feifeiyinyue.top/Article/details/gthngogtrd.html

[U11] Py：生成器表达式
来源：http://dali.cucudq.cn/Article/details/gtuocxzngg.html

(x * 2 for x in arr)
来源：http://dali.sysykeji.top/Article/details/gtwstrwsmm.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtfimclxcp.html

Counter(arr).most_common(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtdjlevkmh.html

[U13] Py：固定长度队列
来源：http://dali.yj20258888.top/Article/details/gtcfqprcbk.html

deque(maxlen=10)
来源：http://dali.yonumen.top/Article/details/gtvhiazevi.html

[U14] Py：分组收集到列表
来源：http://dali.yanxiufei.cn/Article/details/gtlsvxvvbj.html

defaultdict(list)
来源：http://dali.wangdashe.top/Article/details/gtcwdimagu.html

[U15] Py：高精度计时
来源：http://dali.hfpthk.cn/Article/details/gtdhccvcgq.html

t = time.perf_counter()
来源：http://dali.9152youxi.cn/Article/details/gtahyqyvje.html

[U16] Py：命令行参数解析
来源：http://dali.xylfe.cn/Article/details/gtmgtnjopr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.0kj1m.cn/Article/details/gttxpzbmoz.html

[U17] Py：初始化日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsuvuamgi.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.fzhhl.top/Article/details/gtrvmuouhr.html

[U18] Py：预编译正则
来源：http://dali.snrcjt.cn/Article/details/gtrqirwwle.html

pat = re.compile(r"\d+")
来源：http://dali.tian-w.cn/Article/details/gttdbbtfei.html

[U19] Py：正则替换带回调
来源：http://dali.yonumen.top/Article/details/gtarwdkyyo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yongpay.top/Article/details/gtfxldwzsh.html

[U20] Py：缓存函数结果
来源：http://dali.yonumen.top/Article/details/gtfysxgnry.html

@functools.lru_cache(maxsize=None)
来源：http://dali.316326.xyz/Article/details/gtsoojonxc.html

[U21] Py：自定义上下文管理器
来源：http://dali.fengsongda.top/Article/details/gtsxowodtq.html

@contextlib.contextmanager
来源：http://dali.xinyue.icu/Article/details/gtlzpjpzqr.html

[U22] Py：矩阵转置
来源：http://dali.xuetiantiany.cn/Article/details/gtxsdqubgo.html

list(zip(*m))
来源：http://dali.yj202588.top/Article/details/gtomhbvwdx.html

[U23] Py：分块读取大文件
来源：http://dali.tian-w.cn/Article/details/gtrlohpxlk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ehwqpu.com/Article/details/gtrpoxfaho.html

[U24] Py：路径操作
来源：http://dali.nanxuanxn.top/Article/details/gtkuswflda.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hnqzz.top/Article/details/gtigvjgkor.html

[U25] Py：CSV 按字典读
来源：http://dali.smart0.xyz/Article/details/gtvpvtphwl.html

csv.DictReader(f)
来源：http://dali.feifeiyinyue.top/Article/details/gtmxgfeech.html

[U26] Py：并发下载
来源：http://dali.ivvv.top/Article/details/gtwumybmra.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.bjfxy.top/Article/details/gttlnawkjp.html


<!-- 参考信息 -->