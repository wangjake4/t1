代发 wailian999

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gtzpkuzfmy.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtykkxttfl.html

[S01] C：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtqpdaekrf.html

#include <stdio.h>
来源：http://dali.tanke756.top/Article/details/gtuuuahfcv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ybcxt.top/Article/details/gtpqtucvid.html

[S02] C：变量与格式化输出
来源：http://dali.316326.xyz/Article/details/gttlrqdxlb.html

int a = 10; printf("%d\n", a);
来源：http://dali.9152youxi.cn/Article/details/gtfyvsggca.html

[S03] C：读入整数
来源：http://dali.chenjidiqi.icu/Article/details/gtupskbjtg.html

int x; scanf("%d", &x);
来源：http://dali.yonumen.top/Article/details/gtyfammjxo.html

[S04] C：字符串复制
来源：http://dali.yueranfly.top/Article/details/gtmbfcpqaz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.bjfxy.top/Article/details/gtymfrdcqh.html

[S05] C：字符串长度
来源：http://dali.xziqi.cn/Article/details/gtmknlgiis.html

strlen(s)
来源：http://dali.aizwys.cn/Article/details/gtndqdmmgl.html

[S06] C：字符串比较
来源：http://dali.daxiang520.top/Article/details/gtsqvoaapa.html

strcmp(a, b) == 0
来源：http://dali.tian-w.cn/Article/details/gtaroqqcsj.html

[S07] C：数组遍历求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqmltryzb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.guowangkeji.top/Article/details/gtorbrbtyu.html

[S08] C：动态内存分配与释放
来源：http://dali.jinghuilouyu.cn/Article/details/gterrplysz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gotoacloud.top/Article/details/gtcydyxcsz.html

[S09] C：结构体定义与初始化
来源：http://dali.kuanghao11.cn/Article/details/gtlqodschf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tianlin.xyz/Article/details/gtjjkstfmo.html

[S10] C：指针与解引用
来源：http://dali.wangshuangyany.cn/Article/details/gtvawgvxjf.html

int *p = &a;  *p = 5;
来源：http://dali.xuetiantiany.cn/Article/details/gtnvbfxfqt.html

[S11] C：逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gtnkmbsqzs.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nanxinkj.top/Article/details/gtjkntmssc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.havefunace.top/Article/details/gtpeqlmyeq.html

fclose(f);
来源：http://dali.sweek.top/Article/details/gtnhefpsfu.html

[S12] C：写文件
来源：http://dali.zhoulong.xyz/Article/details/gttwfrmllv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gtuxtnfwnj.html

[S13] C：宏定义
来源：http://dali.hongshengwenyu.top/Article/details/gtbihopejc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hammf.cn/Article/details/gtvibftmmc.html

[S14] C：枚举
来源：http://dali.andypj.xyz/Article/details/gtlkhdcbsl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.dianchejie.cn/Article/details/gtgspwwdyp.html

[S15] C：类型转换
来源：http://dali.zhixingplan.top/Article/details/gtohdulfvi.html

(double) a / b
来源：http://dali.gotoacloud.top/Article/details/gtkuwczwvl.html

[S16] C：位操作置位
来源：http://dali.9152youxi.cn/Article/details/gtwstwrqku.html

x |= (1 << 3);
来源：http://dali.chenlongwang.top/Article/details/gtihezlkdu.html

[S17] C：安全拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtwgrknhrq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.guowangkeji.top/Article/details/gtonxkinuo.html

[S18] C：命令行参数
来源：http://dali.jianghu66.top/Article/details/gthsvziddl.html

int main(int argc, char **argv)
来源：http://dali.ydzc1.top/Article/details/gtfssugcnu.html

[S19] C：快速排序
来源：http://dali.gogol.net.cn/Article/details/gtyrxischo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwbqiaugu.html

[S20] C：二分查找
来源：http://dali.aibaodan.cn/Article/details/gtuzxsbesb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.daxiang520.top/Article/details/gtieikozjz.html

[S21] C：字符类别判断
来源：http://dali.shuidangran.top/Article/details/gtzzcvlcqz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jiagoushi.top/Article/details/gtcxgtqfht.html

[S22] C：字符串转数字
来源：http://dali.jianghu66.top/Article/details/gtptiobeqq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ppjwa.cn/Article/details/gtvancryoh.html

[S23] C：随机数
来源：http://dali.jinqigufen.top/Article/details/gtgapoabud.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xuetiantiany.cn/Article/details/gtjnfticox.html

[S24] C：获取本地时间
来源：http://dali.cheryme.top/Article/details/gtwesbabxg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdzlpjtla.html

[S25] C：内存拷贝
来源：http://dali.wangshuangyany.cn/Article/details/gtujdlezvy.html

memcpy(dst, src, n);
来源：http://dali.zhoulong.xyz/Article/details/gtajsyyaqh.html

[S26] C：内存清零
来源：http://dali.aibaodan.cn/Article/details/gtpxminstw.html

memset(a, 0, sizeof a);
来源：http://dali.aizwys.cn/Article/details/gteragjhjx.html

[S27] C：定义常量
来源：http://dali.yueranfly.top/Article/details/gtyjckwimi.html

const double PI = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gtezfpedud.html

[S28] C：静态变量
来源：http://dali.yangfankeji.com/Article/details/gthvpwxhua.html

static int counter = 0;
来源：http://dali.shuidangran.top/Article/details/gtqefqitza.html

[S29] C：变参函数
来源：http://dali.sufxvd.cn/Article/details/gtaqaawtdw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.svipenyu.cn/Article/details/gtlpallhpk.html

[S30] C：头文件保护
来源：http://dali.yonumen.top/Article/details/gtakzizlws.html

#ifndef X_H
来源：http://dali.xziqi.cn/Article/details/gtzkhiryoj.html

#define X_H
来源：http://dali.xuanzx.com/Article/details/gtdtattorf.html

#endif
来源：http://dali.meibo888.top/Article/details/gtzcbvolmj.html

[S31] C++：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtkmiqkcas.html

#include <iostream>
来源：http://dali.tianlin.xyz/Article/details/gtjyyzfjna.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cucudq.cn/Article/details/gtlngknxwy.html

[S32] C++：字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtgvajbimd.html

std::string s = "hi";  s += "!";
来源：http://dali.cucudq.cn/Article/details/gtgbqsdamd.html

[S33] C++：vector 增删
来源：http://dali.xziqi.cn/Article/details/gtkgeztdzx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.wangshuangyany.cn/Article/details/gthjtpzswt.html

[S34] C++：遍历 vector
来源：http://dali.fzhhl.top/Article/details/gthsefrzax.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhongyouzk.top/Article/details/gtigwwnegw.html

[S35] C++：map
来源：http://dali.xinyue.icu/Article/details/gtwgjzwrsx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtbezscsns.html

[S36] C++：unordered_map
来源：http://dali.tianlin.xyz/Article/details/gtiitmreef.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtlinhowyh.html

[S37] C++：set
来源：http://dali.jinghuilouyu.cn/Article/details/gtozcmndgt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.aibaodan.cn/Article/details/gthuoooblr.html

[S38] C++：排序
来源：http://dali.mhx1999.top/Article/details/gtdwgkueke.html

std::sort(v.begin(), v.end());
来源：http://dali.chenlongwang.top/Article/details/gtibqmymmk.html

[S39] C++：自定义比较器排序
来源：http://dali.andypj.xyz/Article/details/gtmigkzkqt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shzxlz.cn/Article/details/gtdfaqiycq.html

[S40] C++：查找元素
来源：http://dali.gzhubu.top/Article/details/gtapalppzn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.bjfxy.top/Article/details/gtalsxpuwe.html

[S41] C++：类与构造函数
来源：http://dali.sweek.top/Article/details/gtbmtdlrqb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jyoumei.cn/Article/details/gtjreptgyo.html

[S42] C++：继承与虚函数
来源：http://dali.jinqigufen.top/Article/details/gtrrqtzwwt.html

class B : public Base { public: void f() override {} };
来源：http://dali.yuanzhike.top/Article/details/gtwniiiixj.html

[S43] C++：智能指针
来源：http://dali.haohaochexian.top/Article/details/gtzvujlxfv.html

auto p = std::make_unique<int>(5);
来源：http://dali.svipenyu.cn/Article/details/gtranapxgz.html

[S44] C++：引用传参
来源：http://dali.andypj.xyz/Article/details/gtvlctyvxo.html

void inc(int &x) { ++x; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkqtjylrs.html

[S45] C++：lambda
来源：http://dali.yuanzhike.top/Article/details/gtxzbiuevn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sweek.top/Article/details/gttwnkepjp.html

[S46] C++：函数模板
来源：http://dali.snrcjt.cn/Article/details/gtcvkmbdjs.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ivvv.top/Article/details/gttinvigfm.html

[S47] C++：结构化绑定遍历
来源：http://dali.ivvv.top/Article/details/gtvjgdjrcq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hywenlv.cn/Article/details/gtgosyaupe.html

[S48] C++：逐行读文件
来源：http://dali.fzhhl.top/Article/details/gtvkgxnhbg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.dianchejie.cn/Article/details/gtoemrnbvu.html

while (std::getline(in, line)) { }
来源：http://dali.feifeiyinyue.top/Article/details/gtolhetjao.html

[S49] C++：写文件
来源：http://dali.hnxiangtu.top/Article/details/gtgfasjdyx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nwbrower.top/Article/details/gtgyrpgucn.html

[S50] C++：格式化数字
来源：http://dali.yvedp.cn/Article/details/gtifacxlhn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gthcrljnyp.html

[S51] C++：显式类型转换
来源：http://dali.chenlongwang.top/Article/details/gteytjfioh.html

static_cast<double>(a) / b
来源：http://dali.tianlin.xyz/Article/details/gtxxhoqrni.html

[S52] C++：const 与 noexcept
来源：http://dali.jqgfzy.top/Article/details/gtfkpogjlc.html

int size() const noexcept { return n_; }
来源：http://dali.hongshengwenyu.top/Article/details/gtdhaovxpy.html

[S53] C++：移动语义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnlmlfper.html

std::vector<int> w = std::move(v);
来源：http://dali.xylfe.cn/Article/details/gtawefkwim.html

[S54] C++：异常处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxyxecmgs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tian-w.cn/Article/details/gtxsebhzrd.html

[S55] C++：结构化绑定
来源：http://dali.nanxuanxn.top/Article/details/gtwnnvhdix.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hywenlv.cn/Article/details/gtrlcwpcoe.html

[S56] C++：optional
来源：http://dali.aibaodan.cn/Article/details/gtfkjuekru.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ivvv.top/Article/details/gtnswwzqmf.html

[S57] C++：编译期常量
来源：http://dali.haohaochexian.top/Article/details/gtwtvnzwfr.html

constexpr int N = 10;
来源：http://dali.pengpengdd.cyou/Article/details/gtcejqshhl.html

[S58] C++：命名空间
来源：http://dali.xylfe.cn/Article/details/gthiufxwqb.html

namespace ns { int f() { return 1; } }
来源：http://dali.sufxvd.cn/Article/details/gtalhcwbnm.html

[S59] C++：静态断言
来源：http://dali.9152youxi.cn/Article/details/gtacttfolq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hysaishi.cn/Article/details/gtikhohhzr.html

[S60] C++：遍历并删除元素
来源：http://dali.hammf.cn/Article/details/gtpgoxllcf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hywenlv.cn/Article/details/gtrfafsdky.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtfezlxyku.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shuidangran.top/Article/details/gtbhrjowpx.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtstmftwtf.html

[T01] Kotlin：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtzcnpakhn.html

println("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gtzmauficc.html

[T02] Kotlin：变量
来源：http://dali.nanxinkj.top/Article/details/gteruechjo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yangfankeji.com/Article/details/gttylfmvpv.html

[T03] Kotlin：字符串模板
来源：http://dali.cucudq.cn/Article/details/gtmrjmjmdf.html

"值: $b"
来源：http://dali.cheryme.top/Article/details/gtmmipntxf.html

[T04] Kotlin：空安全
来源：http://dali.yvedp.cn/Article/details/gtutljdklx.html

val n: String? = null;  n?.length
来源：http://dali.hnqzz.top/Article/details/gttsmyjwfv.html

[T05] Kotlin：when 表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsklcspdn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hysaishi.cn/Article/details/gtacybfxyq.html

[T06] Kotlin：集合映射
来源：http://dali.yongpay.top/Article/details/gtcbaxfoaw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yangfankeji.com/Article/details/gthfmoiqlg.html

[T07] Kotlin：集合过滤
来源：http://dali.hongshengwenyu.top/Article/details/gtyugyforl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.0kj1m.cn/Article/details/gtqjumzdzc.html

[T08] Kotlin：数据类
来源：http://dali.xinyue.icu/Article/details/gtjhwahsot.html

data class User(val name: String, val age: Int)
来源：http://dali.yj202588.top/Article/details/gtajohswwg.html

[T09] Kotlin：扩展函数
来源：http://dali.haohaochexian.top/Article/details/gtdnvyhupy.html

fun String.exclaim() = this + "!"
来源：http://dali.yj202588.top/Article/details/gtzuljlpue.html

[T10] Kotlin：默认参数
来源：http://dali.tianlin.xyz/Article/details/gtqmqicqez.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hywenlv.cn/Article/details/gtscgbqkwx.html

[T11] Kotlin：协程
来源：http://dali.guowangkeji.top/Article/details/gtdovquhfo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.bjfxy.top/Article/details/gthlgwkxmn.html

[T12] Kotlin：解构声明
来源：http://dali.jlsjyb.cn/Article/details/gtgxtwfbqv.html

val (a, b) = Pair(1, 2)
来源：http://dali.vqdsnc.cn/Article/details/gtpxyanqun.html

[T13] Kotlin：只读 Map
来源：http://dali.zycfv.cn/Article/details/gtplzlqxjp.html

val m = mapOf("a" to 1)
来源：http://dali.316326.xyz/Article/details/gtnhvyhsnv.html

[T14] Kotlin：循环
来源：http://dali.ivvv.top/Article/details/gtnkropmrk.html

for (i in 1..10) println(i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqgeskajk.html

[T15] Kotlin：接口
来源：http://dali.jinqigufen.top/Article/details/gtrbkygobs.html

interface Shape { fun area(): Double }
来源：http://dali.hfpthk.cn/Article/details/gteujxxesi.html

[T16] Swift：Hello World
来源：http://dali.9152youxi.cn/Article/details/gttjuizesz.html

print("Hello")
来源：http://dali.daxiang520.top/Article/details/gtqbhoatwk.html

[T17] Swift：变量与常量
来源：http://dali.tanke756.top/Article/details/gtcylrzlxr.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gtnqtcpbki.html

[T18] Swift：字符串插值
来源：http://dali.andypj.xyz/Article/details/gtbqrrupgl.html

"值: \(b)"
来源：http://dali.zdqjudy.top/Article/details/gtbyafdyhq.html

[T19] Swift：可选绑定
来源：http://dali.nanxinkj.top/Article/details/gtbnmpvjcb.html

if let n = opt { print(n) }
来源：http://dali.aibaodan.cn/Article/details/gtigpvprly.html

[T20] Swift：数组操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnxhseevj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gaohongyu789.top/Article/details/gtvalpgyrk.html

[T21] Swift：遍历
来源：http://dali.jyoumei.cn/Article/details/gthyjhvxrs.html

for x in a { print(x) }
来源：http://dali.shzxlz.cn/Article/details/gtmkmsohbj.html

[T22] Swift：字典
来源：http://dali.dashuyun.cn/Article/details/gtnctgfuir.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.birdmap.top/Article/details/gtxvooyosy.html

[T23] Swift：函数
来源：http://dali.zhongyouzk.top/Article/details/gtclootksi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zycfv.cn/Article/details/gthnsucddu.html

[T24] Swift：闭包
来源：http://dali.tanke756.top/Article/details/gtdyedsciz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtipixqjbo.html

[T25] Swift：结构体
来源：http://dali.guowangkeji.top/Article/details/gtthtnrulz.html

struct P { var x: Int }
来源：http://dali.ehwqpu.com/Article/details/gtvafumxwh.html

[T26] Swift：类与重写
来源：http://dali.nanxuanxn.top/Article/details/gtcmfaswij.html

class A: Base { override func f() {} }
来源：http://dali.jqgufenzy.top/Article/details/gtxotgnasm.html

[T27] Swift：错误处理
来源：http://dali.jyoumei.cn/Article/details/gtzwwzlzlx.html

do { try f() } catch { print(error) }
来源：http://dali.zhoulong.xyz/Article/details/gtntjfbcnx.html

[T28] Swift：枚举
来源：http://dali.guowangkeji.top/Article/details/gtuspnsbrs.html

enum Color { case red, green }
来源：http://dali.xziqi.cn/Article/details/gtdglrlsqw.html

[T29] Swift：guard 提前返回
来源：http://dali.zhengqikj.top/Article/details/gtzptsmssf.html

guard let x = opt else { return }
来源：http://dali.jqgfzy.top/Article/details/gtgthgfqhi.html

[T30] Swift：协议
来源：http://dali.yangfankeji.com/Article/details/gtecyebxns.html

protocol Shape { func area() -> Double }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwzfbbacd.html

[T31] Lua：Hello World
来源：http://dali.aizwys.cn/Article/details/gtzubuyqnj.html

print("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gtugrorxcz.html

[T32] Lua：局部变量
来源：http://dali.feifeiyinyue.top/Article/details/gtufxfotgu.html

local a = 1
来源：http://dali.jinqigfzy.top/Article/details/gtjvsvgptu.html

[T33] Lua：表（数组）
来源：http://dali.gzhubu.top/Article/details/gtuiilqmoj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.redwolf501.top/Article/details/gtyrlyrbos.html

[T34] Lua：遍历表
来源：http://dali.ehwqpu.com/Article/details/gtyznnpjcg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gotoacloud.top/Article/details/gtlanhdsxq.html

[T35] Lua：字典表
来源：http://dali.guowangkeji.top/Article/details/gtwmkuainu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hnqzz.top/Article/details/gtuhklxamq.html

[T36] Lua：函数
来源：http://dali.xuetiantiany.cn/Article/details/gtcybcuapq.html

function add(a, b) return a + b end
来源：http://dali.zhengqikj.top/Article/details/gttgfepebl.html

[T37] Lua：字符串拼接
来源：http://dali.feifeiyinyue.top/Article/details/gtjflzhybk.html

"a" .. "b"
来源：http://dali.sweek.top/Article/details/gtrxvugnzo.html

[T38] Lua：条件
来源：http://dali.shuidangran.top/Article/details/gtffxxlyww.html

if x > 0 then print("正") end
来源：http://dali.yongpay.top/Article/details/gtcbryhaki.html

[T39] Lua：模式匹配
来源：http://dali.yongpay.top/Article/details/gtgirlotzr.html

string.find(s, "%d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijhfpgfz.html

[T40] Lua：元表
来源：http://dali.daxiang520.top/Article/details/gtwniutdgu.html

setmetatable({}, { __index = base })
来源：http://dali.kuanghao11.cn/Article/details/gtwsivyzvu.html

[T41] Perl：Hello World
来源：http://dali.xziqi.cn/Article/details/gtnykrnrrg.html

print "Hello\n";
来源：http://dali.hfpthk.cn/Article/details/gtqkktsgjz.html

[T42] Perl：变量类型
来源：http://dali.andypj.xyz/Article/details/gtrmkcmwur.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yongpay.top/Article/details/gttbppxkro.html

[T43] Perl：字符串插值
来源：http://dali.316326.xyz/Article/details/gtcczouvan.html

"值: $a"
来源：http://dali.tanke756.top/Article/details/gtrbhzxiqf.html

[T44] Perl：条件
来源：http://dali.gotoacloud.top/Article/details/gtzhljzkxe.html

if ($a > 0) { print "正"; }
来源：http://dali.cdnleiting.top/Article/details/gtptlsygrj.html

[T45] Perl：数组遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtyibffvds.html

for my $x (@arr) { print $x; }
来源：http://dali.shuidangran.top/Article/details/gtuziaaapk.html

[T46] Perl：哈希操作
来源：http://dali.yj202588.top/Article/details/gtipickuey.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.nanxuanxn.top/Article/details/gtlupycnzj.html

[T47] Perl：正则捕获
来源：http://dali.zhoulong.xyz/Article/details/gtmksamilx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhengqikj.top/Article/details/gtdmxwoouh.html

[T48] Perl：正则替换
来源：http://dali.havefunace.top/Article/details/gtxulhrmvf.html

$s =~ s/old/new/g;
来源：http://dali.tanke756.top/Article/details/gtbnqzluwh.html

[T49] Perl：函数
来源：http://dali.aibaodan.cn/Article/details/gtbutexaod.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtuazbeulr.html

[T50] Perl：逐行读文件
来源：http://dali.cheryme.top/Article/details/gtvvkutlpu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.316326.xyz/Article/details/gtqjksbava.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.0kj1m.cn/Article/details/gtqwlyojcq.html

[T51] Scala：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtdkwrqfbz.html

println("Hello")
来源：http://dali.cdnleiting.top/Article/details/gtwutghtgs.html

[T52] Scala：变量
来源：http://dali.pengpengdd.cyou/Article/details/gtvfrlpinn.html

val a = 1;  var b = 2
来源：http://dali.hfpthk.cn/Article/details/gtexhmejfz.html

[T53] Scala：字符串插值
来源：http://dali.ehwqpu.com/Article/details/gtxicmscyh.html

s"值: $b"
来源：http://dali.zhixingplan.top/Article/details/gtxrdyzhls.html

[T54] Scala：集合映射
来源：http://dali.cheryme.top/Article/details/gtqrkhkays.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yj202588.top/Article/details/gtpmpjquuu.html

[T55] Scala：集合过滤
来源：http://dali.chenzaomai.com/Article/details/gttvizxfhe.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shuidangran.top/Article/details/gtiiprfqne.html

[T56] Scala：样例类
来源：http://dali.ydzc1.top/Article/details/gtpkpqzbph.html

case class User(name: String, age: Int)
来源：http://dali.yj202588.top/Article/details/gtzsyzvihg.html

[T57] Scala：模式匹配
来源：http://dali.svipenyu.cn/Article/details/gtrjetxfal.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.aizwys.cn/Article/details/gtzlyhwlhp.html

[T58] Scala：函数定义
来源：http://dali.zhengqikj.top/Article/details/gteealjowf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zycfv.cn/Article/details/gtcsjshnun.html

[T59] Scala：循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrdsixjvb.html

for (i <- 1 to 10) println(i)
来源：http://dali.sxryk.cn/Article/details/gthnkdizub.html

[T60] Scala：折叠
来源：http://dali.jianghu66.top/Article/details/gtvnzqrnpb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.nanxinkj.top/Article/details/gtknoqaewd.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtgejovzhl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.tanke756.top/Article/details/gtuefaxkem.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtzmbegjqu.html

[U01] Py：创建虚拟环境
来源：http://dali.vqdsnc.cn/Article/details/gthgzenzmf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yuxming.cn/Article/details/gtwknaolzs.html

[U02] Py：导出 / 安装依赖
来源：http://dali.daria6918.cn/Article/details/gttbeelwqj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hysaishi.cn/Article/details/gtwlotkpcb.html

[U03] Py：加载 .env 配置
来源：http://dali.bjfxy.top/Article/details/gtkuanhjcf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhiwuduotai.top/Article/details/gtkgfdwobs.html

[U04] Py：变量调试打印
来源：http://dali.ydzc1.top/Article/details/gtwkmgvjqz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.guowangkeji.top/Article/details/gtogqgwmyj.html

[U05] Py：列表去重且保序
来源：http://dali.guannengcc.top/Article/details/gtubcdbkbu.html

list(dict.fromkeys(arr))
来源：http://dali.hfpthk.cn/Article/details/gtdrvrbuxg.html

[U06] Py：合并两个字典
来源：http://dali.ydzc1.top/Article/details/gtldjalweh.html

{**a, **b}
来源：http://dali.fzhhl.top/Article/details/gtdixnkblf.html

[U07] Py：反转字典键值
来源：http://dali.yongpay.top/Article/details/gtopeyhppi.html

{v: k for k, v in d.items()}
来源：http://dali.ehwqpu.com/Article/details/gtzqoeqjht.html

[U08] Py：展平二维列表
来源：http://dali.hnqzz.top/Article/details/gtznqiyxin.html

[y for x in nested for y in x]
来源：http://dali.dashuyun.cn/Article/details/gtaxjjcvui.html

[U09] Py：字典取最大值的键
来源：http://dali.chenjidiqi.icu/Article/details/gteayjnxep.html

max(d, key=d.get)
来源：http://dali.havefunace.top/Article/details/gtkgcrbuhl.html

[U10] Py：按值排序字典
来源：http://dali.jinqigfzy.top/Article/details/gtvbxdhekk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gaohongyu789.top/Article/details/gtxzxhhjli.html

[U11] Py：生成器表达式
来源：http://dali.nanxinkj.top/Article/details/gtagryvzad.html

(x * 2 for x in arr)
来源：http://dali.redwolf501.top/Article/details/gtltwljlch.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.redwolf501.top/Article/details/gtvzoszxgc.html

Counter(arr).most_common(3)
来源：http://dali.gzhubu.top/Article/details/gtruugjkdr.html

[U13] Py：固定长度队列
来源：http://dali.fzhhl.top/Article/details/gthltjmizd.html

deque(maxlen=10)
来源：http://dali.quarkkingdee.top/Article/details/gtlykeraxu.html

[U14] Py：分组收集到列表
来源：http://dali.nanxinkj.top/Article/details/gtzfmtefxq.html

defaultdict(list)
来源：http://dali.guowangkeji.top/Article/details/gtscdccyzo.html

[U15] Py：高精度计时
来源：http://dali.sxryk.cn/Article/details/gtrslqiqay.html

t = time.perf_counter()
来源：http://dali.jiagoushi.top/Article/details/gtyzsiroqy.html

[U16] Py：命令行参数解析
来源：http://dali.smart0.xyz/Article/details/gtrrohsmjw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jianghu66.top/Article/details/gtlmronuqs.html

[U17] Py：初始化日志
来源：http://dali.smart0.xyz/Article/details/gtyqpekwuv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jianghu66.top/Article/details/gteaiosvte.html

[U18] Py：预编译正则
来源：http://dali.zhengqikj.top/Article/details/gttnticgmt.html

pat = re.compile(r"\d+")
来源：http://dali.pycfn.com/Article/details/gtmyekdjbh.html

[U19] Py：正则替换带回调
来源：http://dali.shangyingyoupin.top/Article/details/gtxbgzcrtp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.cashguo.top/Article/details/gtlddpjeed.html

[U20] Py：缓存函数结果
来源：http://dali.c1oappe.top/Article/details/gtxeggncxz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhiwuduotai.top/Article/details/gtvfvyitxk.html

[U21] Py：自定义上下文管理器
来源：http://dali.ppjwa.cn/Article/details/gtxzufyfvh.html

@contextlib.contextmanager
来源：http://dali.guowangkeji.top/Article/details/gttlcfiaid.html

[U22] Py：矩阵转置
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnmpyezwv.html

list(zip(*m))
来源：http://dali.hfpthk.cn/Article/details/gtskoesuzl.html


<!-- 参考信息 -->