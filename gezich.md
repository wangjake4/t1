代发 wailian999

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ydzc1.top/Article/details/gtenxiyywu.html

[R80] 查看脚本执行耗时
来源：http://dali.daria6918.cn/Article/details/gtvcftqlpd.html

time ./run.sh
来源：http://dali.tanke756.top/Article/details/gtfyiomcna.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtwejldxxh.html

S. C / C++ 专题
来源：http://dali.yj20258888.top/Article/details/gtfnqbrrma.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtxljwfpss.html

[S01] C：Hello World
来源：http://dali.yj202588.top/Article/details/gtxhrywcgy.html

#include <stdio.h>
来源：http://dali.wangdashe.top/Article/details/gtlrhvcfbn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shangyingyoupin.top/Article/details/gtzdqvjigj.html

[S02] C：变量与格式化输出
来源：http://dali.hywenlv.cn/Article/details/gtuzkyseou.html

int a = 10; printf("%d\n", a);
来源：http://dali.gotoacloud.top/Article/details/gtryuhzbsa.html

[S03] C：读入整数
来源：http://dali.cheryme.top/Article/details/gtkjhigvhs.html

int x; scanf("%d", &x);
来源：http://dali.cqqwz.cn/Article/details/gtljfdhvet.html

[S04] C：字符串复制
来源：http://dali.tianlin.xyz/Article/details/gtybornxgu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cucudq.cn/Article/details/gtjnpfwseu.html

[S05] C：字符串长度
来源：http://dali.hnxiangtu.top/Article/details/gtvekjjtsw.html

strlen(s)
来源：http://dali.jianghu66.top/Article/details/gttdmqfuts.html

[S06] C：字符串比较
来源：http://dali.yj202588.top/Article/details/gtisfkxwrv.html

strcmp(a, b) == 0
来源：http://dali.nanxuanxn.top/Article/details/gtxjsyepfs.html

[S07] C：数组遍历求和
来源：http://dali.yuanzhike.top/Article/details/gtjgoixviz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.dashuyun.cn/Article/details/gtezwujcqd.html

[S08] C：动态内存分配与释放
来源：http://dali.cucudq.cn/Article/details/gtrcksyltg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zdqjudy.top/Article/details/gttphemwkg.html

[S09] C：结构体定义与初始化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgdoynaef.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.dianchejie.cn/Article/details/gtqdxodyvf.html

[S10] C：指针与解引用
来源：http://dali.shangyingyoupin.top/Article/details/gtebmtmzvq.html

int *p = &a;  *p = 5;
来源：http://dali.chenjidiqi.icu/Article/details/gtxvwiiixh.html

[S11] C：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtqsxbbudq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gogol.net.cn/Article/details/gtmgfzhyfm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.vqdsnc.cn/Article/details/gteggjoxag.html

fclose(f);
来源：http://dali.chenjidiqi.icu/Article/details/gtpgyarlvn.html

[S12] C：写文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmpcghijs.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.guowangkeji.top/Article/details/gtohhqgepj.html

[S13] C：宏定义
来源：http://dali.jqgufenzy.top/Article/details/gtreevleda.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.mhx1999.top/Article/details/gtrwsqmdmy.html

[S14] C：枚举
来源：http://dali.wangdashe.top/Article/details/gtxpsfmkur.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yuxming.cn/Article/details/gtxhdpngoq.html

[S15] C：类型转换
来源：http://dali.zhongyouzk.top/Article/details/gtomwwnyin.html

(double) a / b
来源：http://dali.gotoacloud.top/Article/details/gtxtwlddol.html

[S16] C：位操作置位
来源：http://dali.ivvv.top/Article/details/gtqnjwyzlp.html

x |= (1 << 3);
来源：http://dali.hnqzz.top/Article/details/gticbsmjwn.html

[S17] C：安全拼接字符串
来源：http://dali.andypj.xyz/Article/details/gtvvgmxopk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenjidiqi.icu/Article/details/gtyquabhqp.html

[S18] C：命令行参数
来源：http://dali.kuanghao11.cn/Article/details/gtbzhkpilf.html

int main(int argc, char **argv)
来源：http://dali.xuetiantiany.cn/Article/details/gtfqknhkst.html

[S19] C：快速排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbzpzqmsi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gtisohiyho.html

[S20] C：二分查找
来源：http://dali.zhengqikj.top/Article/details/gtpxtbkpoz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.iojbl.cn/Article/details/gtkkskbeuh.html

[S21] C：字符类别判断
来源：http://dali.hywenlv.cn/Article/details/gtwnleiftn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.guowangkeji.top/Article/details/gtzlesqdua.html

[S22] C：字符串转数字
来源：http://dali.gaohongyu789.top/Article/details/gtndbyfvgj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tian-w.cn/Article/details/gtubjygird.html

[S23] C：随机数
来源：http://dali.mhx1999.top/Article/details/gtkwjbizrl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gogol.net.cn/Article/details/gtjjwgwcnt.html

[S24] C：获取本地时间
来源：http://dali.yj202588.top/Article/details/gtieloygig.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.aibaodan.cn/Article/details/gtmzfbsbah.html

[S25] C：内存拷贝
来源：http://dali.wangdashe.top/Article/details/gtkdjddlbq.html

memcpy(dst, src, n);
来源：http://dali.cucudq.cn/Article/details/gtyyhqhfdg.html

[S26] C：内存清零
来源：http://dali.yangfankeji.com/Article/details/gtryrxzhvi.html

memset(a, 0, sizeof a);
来源：http://dali.xziqi.cn/Article/details/gtbiywiasd.html

[S27] C：定义常量
来源：http://dali.hnxiangtu.top/Article/details/gtttvsmvgn.html

const double PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gtueqohakj.html

[S28] C：静态变量
来源：http://dali.havefunace.top/Article/details/gtiupxweja.html

static int counter = 0;
来源：http://dali.xinyue.icu/Article/details/gtsmhzqcdx.html

[S29] C：变参函数
来源：http://dali.gzhubu.top/Article/details/gtfdkukatn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjsdhcwbv.html

[S30] C：头文件保护
来源：http://dali.ybcxt.top/Article/details/gtbqapwgvg.html

#ifndef X_H
来源：http://dali.c1oappe.top/Article/details/gtpdyznktg.html

#define X_H
来源：http://dali.chenlongwang.top/Article/details/gtftjutohc.html

#endif
来源：http://dali.daxiang520.top/Article/details/gthgojxbdy.html

[S31] C++：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtwjfszwwk.html

#include <iostream>
来源：http://dali.svipenyu.cn/Article/details/gtkepnyfgs.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yangfankeji.com/Article/details/gtyupvplpy.html

[S32] C++：字符串
来源：http://dali.daria6918.cn/Article/details/gtocehpigr.html

std::string s = "hi";  s += "!";
来源：http://dali.kuanghao11.cn/Article/details/gtudnehjkm.html

[S33] C++：vector 增删
来源：http://dali.aibaodan.cn/Article/details/gtwexiqzfr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cucudq.cn/Article/details/gtdqibbgfp.html

[S34] C++：遍历 vector
来源：http://dali.wangshuangyany.cn/Article/details/gtrfqrsvaw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yuanzhike.top/Article/details/gtvyzpuaai.html

[S35] C++：map
来源：http://dali.sxryk.cn/Article/details/gteyqmjbbz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtybvieraq.html

[S36] C++：unordered_map
来源：http://dali.nanxuanxn.top/Article/details/gtuapqfgwe.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.redwolf501.top/Article/details/gtwvdfyftw.html

[S37] C++：set
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlcilazzp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrdhkvmqs.html

[S38] C++：排序
来源：http://dali.xuetiantiany.cn/Article/details/gtdhrqsckt.html

std::sort(v.begin(), v.end());
来源：http://dali.jinqigufen.top/Article/details/gttdqderle.html

[S39] C++：自定义比较器排序
来源：http://dali.aizwys.cn/Article/details/gtlernhpqh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zycfv.cn/Article/details/gtullrgibv.html

[S40] C++：查找元素
来源：http://dali.yangfankeji.com/Article/details/gttqiuinfn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.smart0.xyz/Article/details/gtsroiveta.html

[S41] C++：类与构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbwxlxul.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.redwolf501.top/Article/details/gtvioipaoh.html

[S42] C++：继承与虚函数
来源：http://dali.fzhhl.top/Article/details/gtebodsedg.html

class B : public Base { public: void f() override {} };
来源：http://dali.yongpay.top/Article/details/gtgqcxghsn.html

[S43] C++：智能指针
来源：http://dali.9152youxi.cn/Article/details/gtewivtnfe.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinqigfzy.top/Article/details/gtgqkggjml.html

[S44] C++：引用传参
来源：http://dali.yj20258888.top/Article/details/gtszhgiokb.html

void inc(int &x) { ++x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbpxvydqq.html

[S45] C++：lambda
来源：http://dali.guannengcc.top/Article/details/gtsnypxlmi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hywenlv.cn/Article/details/gtrwozgyaj.html

[S46] C++：函数模板
来源：http://dali.sysykeji.top/Article/details/gtsdwvrapc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.aibaodan.cn/Article/details/gtegrlwywn.html

[S47] C++：结构化绑定遍历
来源：http://dali.jqgfzy.top/Article/details/gtmurxdlrj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gotoacloud.top/Article/details/gtgvmmusau.html

[S48] C++：逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtkjbumvoj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cashguo.top/Article/details/gtcazocrvi.html

while (std::getline(in, line)) { }
来源：http://dali.nanxuanxn.top/Article/details/gtsxntezxc.html

[S49] C++：写文件
来源：http://dali.ppjwa.cn/Article/details/gtpfythjrn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkrcoqajd.html

[S50] C++：格式化数字
来源：http://dali.zycfv.cn/Article/details/gtpgqygqns.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gthhlmfumh.html

[S51] C++：显式类型转换
来源：http://dali.guowangkeji.top/Article/details/gtwclbteee.html

static_cast<double>(a) / b
来源：http://dali.iojbl.cn/Article/details/gtpueoootl.html

[S52] C++：const 与 noexcept
来源：http://dali.hywenlv.cn/Article/details/gtpymjhlzw.html

int size() const noexcept { return n_; }
来源：http://dali.sufxvd.cn/Article/details/gtjunrvlos.html

[S53] C++：移动语义
来源：http://dali.nanxuanxn.top/Article/details/gtdmjclbap.html

std::vector<int> w = std::move(v);
来源：http://dali.zdqjudy.top/Article/details/gtymlzkpbx.html

[S54] C++：异常处理
来源：http://dali.xinyue.icu/Article/details/gtdvjzlewl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shuidangran.top/Article/details/gtuptmkesy.html

[S55] C++：结构化绑定
来源：http://dali.yvedp.cn/Article/details/gtjbnjywqi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.316326.xyz/Article/details/gtgpwtspwv.html

[S56] C++：optional
来源：http://dali.pengpengdd.cyou/Article/details/gtqdjinlhk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gotoacloud.top/Article/details/gtqbbfkvxg.html

[S57] C++：编译期常量
来源：http://dali.hammf.cn/Article/details/gtdzfihbtx.html

constexpr int N = 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gteiskxode.html

[S58] C++：命名空间
来源：http://dali.yvedp.cn/Article/details/gtxmucmcav.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhengqikj.top/Article/details/gtujgwpeve.html

[S59] C++：静态断言
来源：http://dali.zhongyouzk.top/Article/details/gtfkskcqdi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sweek.top/Article/details/gtqpkrajyh.html

[S60] C++：遍历并删除元素
来源：http://dali.vqdsnc.cn/Article/details/gtlwxggpwt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.wangdashe.top/Article/details/gtetrpwfyh.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtpheceazq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigfzy.top/Article/details/gtaoddskrx.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtrfngzioy.html

[T01] Kotlin：Hello World
来源：http://dali.yuxming.cn/Article/details/gtbxmzbwrq.html

println("Hello")
来源：http://dali.ybcxt.top/Article/details/gttvotqydh.html

[T02] Kotlin：变量
来源：http://dali.jiagoushi.top/Article/details/gtpipzhtgi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.daria6918.cn/Article/details/gtbhzmscfp.html

[T03] Kotlin：字符串模板
来源：http://dali.pycfn.com/Article/details/gtutrtajgk.html

"值: $b"
来源：http://dali.ivvv.top/Article/details/gtwtcvblnt.html

[T04] Kotlin：空安全
来源：http://dali.tianlin.xyz/Article/details/gtalnzcgte.html

val n: String? = null;  n?.length
来源：http://dali.hongshengwenyu.top/Article/details/gtbjpgljdg.html

[T05] Kotlin：when 表达式
来源：http://dali.c1oappe.top/Article/details/gtcyjaocyw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yvedp.cn/Article/details/gtzzxigcnu.html

[T06] Kotlin：集合映射
来源：http://dali.havefunace.top/Article/details/gtbxpvwgmw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenlongwang.top/Article/details/gtksnmdjsc.html

[T07] Kotlin：集合过滤
来源：http://dali.cdnleiting.top/Article/details/gtsieaynui.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtaqwharbb.html

[T08] Kotlin：数据类
来源：http://dali.316326.xyz/Article/details/gtffiwtjjx.html

data class User(val name: String, val age: Int)
来源：http://dali.nanxinkj.top/Article/details/gtjykiyodh.html

[T09] Kotlin：扩展函数
来源：http://dali.feifeiyinyue.top/Article/details/gtpmazzcph.html

fun String.exclaim() = this + "!"
来源：http://dali.nanxinkj.top/Article/details/gtozlvbnzo.html

[T10] Kotlin：默认参数
来源：http://dali.9152youxi.cn/Article/details/gtlczhgizf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.nwbrower.top/Article/details/gtbkxwqzch.html

[T11] Kotlin：协程
来源：http://dali.sufxvd.cn/Article/details/gthyepkfag.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gtnfeumrdb.html

[T12] Kotlin：解构声明
来源：http://dali.chenjidiqi.icu/Article/details/gtuqcggxfd.html

val (a, b) = Pair(1, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtrybtwalc.html

[T13] Kotlin：只读 Map
来源：http://dali.yvedp.cn/Article/details/gtmuxtuxjg.html

val m = mapOf("a" to 1)
来源：http://dali.ydzc1.top/Article/details/gthuwvugvc.html

[T14] Kotlin：循环
来源：http://dali.daria6918.cn/Article/details/gtkgakeccn.html

for (i in 1..10) println(i)
来源：http://dali.dashuyun.cn/Article/details/gtajwkfajd.html

[T15] Kotlin：接口
来源：http://dali.9152youxi.cn/Article/details/gtmbmeamwy.html

interface Shape { fun area(): Double }
来源：http://dali.sufxvd.cn/Article/details/gtawxudpjr.html

[T16] Swift：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtnfhkqiuf.html

print("Hello")
来源：http://dali.nwbrower.top/Article/details/gtkwrqjdmx.html

[T17] Swift：变量与常量
来源：http://dali.guannengcc.top/Article/details/gtdcigzmpc.html

var a = 1;  let b = 2
来源：http://dali.pycfn.com/Article/details/gthntxvplj.html

[T18] Swift：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumsfpbxi.html

"值: \(b)"
来源：http://dali.zdqjudy.top/Article/details/gtkshzfznk.html

[T19] Swift：可选绑定
来源：http://dali.quarkkingdee.top/Article/details/gttlgdhnzw.html

if let n = opt { print(n) }
来源：http://dali.aibaodan.cn/Article/details/gtfvekqesz.html

[T20] Swift：数组操作
来源：http://dali.cucudq.cn/Article/details/gtpfyesktq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj20258.top/Article/details/gtfiremjpo.html

[T21] Swift：遍历
来源：http://dali.xinyue.icu/Article/details/gtfprzvblu.html

for x in a { print(x) }
来源：http://dali.mhx1999.top/Article/details/gtnrikrlxz.html

[T22] Swift：字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbsizhxfh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shangyingyoupin.top/Article/details/gtshqbgewl.html

[T23] Swift：函数
来源：http://dali.smart0.xyz/Article/details/gtkfbazrqz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cashguo.top/Article/details/gtjwowffsy.html

[T24] Swift：闭包
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbtfusxbt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinqigufen.top/Article/details/gtrjezjeeq.html

[T25] Swift：结构体
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmephfvmm.html

struct P { var x: Int }
来源：http://dali.hongshengwenyu.top/Article/details/gtrrcimgpj.html

[T26] Swift：类与重写
来源：http://dali.nanxinkj.top/Article/details/gtdjykfdav.html

class A: Base { override func f() {} }
来源：http://dali.sweek.top/Article/details/gtgdgmxbnq.html

[T27] Swift：错误处理
来源：http://dali.birdmap.top/Article/details/gtztayeohl.html

do { try f() } catch { print(error) }
来源：http://dali.jinqigfzy.top/Article/details/gtnfjlrncs.html

[T28] Swift：枚举
来源：http://dali.hnxiangtu.top/Article/details/gtsbmpvmbt.html

enum Color { case red, green }
来源：http://dali.shuidangran.top/Article/details/gtvoyhrszc.html

[T29] Swift：guard 提前返回
来源：http://dali.316326.xyz/Article/details/gtxbhjmyde.html

guard let x = opt else { return }
来源：http://dali.hammf.cn/Article/details/gtmblbzucs.html

[T30] Swift：协议
来源：http://dali.jinyuanbaomall.cn/Article/details/gtetsrqnck.html

protocol Shape { func area() -> Double }
来源：http://dali.fengsongda.top/Article/details/gtzzyxmfqd.html

[T31] Lua：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtxlswnytm.html

print("Hello")
来源：http://dali.yonumen.top/Article/details/gtyuipvmfr.html

[T32] Lua：局部变量
来源：http://dali.birdmap.top/Article/details/gtjzxzjoou.html

local a = 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtmryegvsj.html

[T33] Lua：表（数组）
来源：http://dali.yonumen.top/Article/details/gtdvjxtxwe.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.fzhhl.top/Article/details/gtsvqiorzs.html

[T34] Lua：遍历表
来源：http://dali.yanxiufei.cn/Article/details/gtqyzqgmvh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.chenlongwang.top/Article/details/gtzagxhjgx.html

[T35] Lua：字典表
来源：http://dali.fengsongda.top/Article/details/gtmfuybstz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cqqwz.cn/Article/details/gtrrmrmfsd.html

[T36] Lua：函数
来源：http://dali.ivvv.top/Article/details/gtflxbdqxt.html

function add(a, b) return a + b end
来源：http://dali.jianghu66.top/Article/details/gtvaqmnhhv.html

[T37] Lua：字符串拼接
来源：http://dali.316326.xyz/Article/details/gtaogyjttr.html

"a" .. "b"
来源：http://dali.hongshengwenyu.top/Article/details/gthqianvxw.html

[T38] Lua：条件
来源：http://dali.xuanzx.com/Article/details/gtdpzmvwic.html

if x > 0 then print("正") end
来源：http://dali.gzhubu.top/Article/details/gtjxijnpkv.html

[T39] Lua：模式匹配
来源：http://dali.aibaodan.cn/Article/details/gtrmxkeqdx.html

string.find(s, "%d+")
来源：http://dali.smart0.xyz/Article/details/gtjclmbtwi.html

[T40] Lua：元表
来源：http://dali.quarkkingdee.top/Article/details/gtxlyajdsx.html

setmetatable({}, { __index = base })
来源：http://dali.redwolf501.top/Article/details/gtadzqhvpb.html

[T41] Perl：Hello World
来源：http://dali.jianghu66.top/Article/details/gtbypoikoe.html

print "Hello\n";
来源：http://dali.xuanzx.com/Article/details/gtonzambcx.html

[T42] Perl：变量类型
来源：http://dali.meibo888.top/Article/details/gtffnutzhu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xylfe.cn/Article/details/gtfqgazqrj.html

[T43] Perl：字符串插值
来源：http://dali.chenlongwang.top/Article/details/gtfpviogup.html

"值: $a"
来源：http://dali.xuetiantiany.cn/Article/details/gtdzxhnhks.html

[T44] Perl：条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaihiagag.html

if ($a > 0) { print "正"; }
来源：http://dali.meibo888.top/Article/details/gtrcrrlizx.html

[T45] Perl：数组遍历
来源：http://dali.hnxiangtu.top/Article/details/gtrjqggyjs.html

for my $x (@arr) { print $x; }
来源：http://dali.gaohongyu789.top/Article/details/gtwlxozrsx.html

[T46] Perl：哈希操作
来源：http://dali.dianchejie.cn/Article/details/gtpxtkvhuy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyafchkyb.html

[T47] Perl：正则捕获
来源：http://dali.shuidangran.top/Article/details/gtshzqkirs.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cashguo.top/Article/details/gtiajhyabv.html

[T48] Perl：正则替换
来源：http://dali.zhiwuduotai.top/Article/details/gtchwcxkxv.html

$s =~ s/old/new/g;
来源：http://dali.vqdsnc.cn/Article/details/gtdtbekhov.html

[T49] Perl：函数
来源：http://dali.ppjwa.cn/Article/details/gtnbenpeag.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.0kj1m.cn/Article/details/gtxlxwtygc.html

[T50] Perl：逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gtqmvxsvto.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.dianchejie.cn/Article/details/gtcqtpruxs.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.tanke756.top/Article/details/gtrgdjvike.html

[T51] Scala：Hello World
来源：http://dali.iojbl.cn/Article/details/gtmpbdtvlp.html

println("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtdivcjmuf.html

[T52] Scala：变量
来源：http://dali.hammf.cn/Article/details/gtbfvhmkor.html

val a = 1;  var b = 2
来源：http://dali.aizwys.cn/Article/details/gtgybpdrul.html

[T53] Scala：字符串插值
来源：http://dali.xinyue.icu/Article/details/gtplpxxbyr.html

s"值: $b"
来源：http://dali.havefunace.top/Article/details/gtorjvheju.html

[T54] Scala：集合映射
来源：http://dali.c1oappe.top/Article/details/gtknchgotd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.andypj.xyz/Article/details/gtzyioglqp.html

[T55] Scala：集合过滤
来源：http://dali.jqgufenzy.top/Article/details/gtvvwcxcqw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zdqjudy.top/Article/details/gtglrzpvkd.html

[T56] Scala：样例类
来源：http://dali.tianlin.xyz/Article/details/gtrelkntmg.html

case class User(name: String, age: Int)
来源：http://dali.zdqjudy.top/Article/details/gtczgiytdy.html

[T57] Scala：模式匹配
来源：http://dali.zycfv.cn/Article/details/gtgwlrjhlt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.dashuyun.cn/Article/details/gthyrthxir.html

[T58] Scala：函数定义
来源：http://dali.redwolf501.top/Article/details/gtqeyosidy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yuanzhike.top/Article/details/gtvzxddhvu.html

[T59] Scala：循环
来源：http://dali.mhx1999.top/Article/details/gtndmokbyd.html

for (i <- 1 to 10) println(i)
来源：http://dali.sysykeji.top/Article/details/gthcacxfnj.html

[T60] Scala：折叠
来源：http://dali.shangyingyoupin.top/Article/details/gtgooqqweu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gzhubu.top/Article/details/gtjloxhnfk.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtbkpmqjsa.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cheryme.top/Article/details/gtvgzqkpub.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gteancfzha.html

[U01] Py：创建虚拟环境
来源：http://dali.shzxlz.cn/Article/details/gthhqxlbyp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhoulong.xyz/Article/details/gtnxvadgor.html

[U02] Py：导出 / 安装依赖
来源：http://dali.birdmap.top/Article/details/gtzzvfwqug.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sxryk.cn/Article/details/gtkjyszydu.html

[U03] Py：加载 .env 配置
来源：http://dali.fzhhl.top/Article/details/gtzxyblfiu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.mhx1999.top/Article/details/gtztdadafp.html

[U04] Py：变量调试打印
来源：http://dali.shuidangran.top/Article/details/gtligqijhm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.tianlin.xyz/Article/details/gtcelopwsq.html

[U05] Py：列表去重且保序
来源：http://dali.zdqjudy.top/Article/details/gtsktzkdyz.html

list(dict.fromkeys(arr))
来源：http://dali.bjfxy.top/Article/details/gtcqtucvtv.html

[U06] Py：合并两个字典
来源：http://dali.tian-w.cn/Article/details/gtwaqsxxmy.html

{**a, **b}
来源：http://dali.wangshuangyany.cn/Article/details/gtofvqfpsp.html

[U07] Py：反转字典键值
来源：http://dali.aizwys.cn/Article/details/gteqylecyj.html

{v: k for k, v in d.items()}
来源：http://dali.0kj1m.cn/Article/details/gtxqccpxak.html

[U08] Py：展平二维列表
来源：http://dali.ivvv.top/Article/details/gtdifdzcxm.html

[y for x in nested for y in x]
来源：http://dali.cheryme.top/Article/details/gtdrkxxouw.html

[U09] Py：字典取最大值的键
来源：http://dali.jinyuanbaomall.cn/Article/details/gthdnfcebx.html

max(d, key=d.get)
来源：http://dali.ydzc1.top/Article/details/gtlcpvrclv.html

[U10] Py：按值排序字典
来源：http://dali.jinqigfzy.top/Article/details/gtrsmazqfv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.svipenyu.cn/Article/details/gtrrjtnohg.html

[U11] Py：生成器表达式
来源：http://dali.haohaochexian.top/Article/details/gtdyqpbofk.html

(x * 2 for x in arr)
来源：http://dali.havefunace.top/Article/details/gtnhxvwwyr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gogol.net.cn/Article/details/gtmwxluqro.html

Counter(arr).most_common(3)
来源：http://dali.zdqjudy.top/Article/details/gttgboaiqr.html

[U13] Py：固定长度队列
来源：http://dali.c1oappe.top/Article/details/gtjfxlwtrc.html

deque(maxlen=10)
来源：http://dali.ivvv.top/Article/details/gtrrvhhugb.html

[U14] Py：分组收集到列表
来源：http://dali.sweek.top/Article/details/gtncuakiid.html

defaultdict(list)
来源：http://dali.chenlongwang.top/Article/details/gtgsihuzbi.html

[U15] Py：高精度计时
来源：http://dali.jqgfzy.top/Article/details/gtrvlutfiw.html

t = time.perf_counter()
来源：http://dali.yj20258888.top/Article/details/gtibjjxdwn.html

[U16] Py：命令行参数解析
来源：http://dali.zhoulong.xyz/Article/details/gtdcbcfzjf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.dianchejie.cn/Article/details/gtvnarkryl.html

[U17] Py：初始化日志
来源：http://dali.ydzc1.top/Article/details/gtedbhhwpd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yangfankeji.com/Article/details/gtqxnmqcib.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gttoxkxfyv.html

pat = re.compile(r"\d+")
来源：http://dali.sweek.top/Article/details/gtxbatiecb.html

[U19] Py：正则替换带回调
来源：http://dali.shanyushiyangtech.top/Article/details/gtoiewwvig.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.haohaochexian.top/Article/details/gtouxgphuq.html

[U20] Py：缓存函数结果
来源：http://dali.hfpthk.cn/Article/details/gtfdgoquhv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.gaohongyu789.top/Article/details/gtlcnadwnc.html


<!-- 参考信息 -->