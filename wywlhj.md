代发 wailian999

export PATH="$HOME/bin:$PATH"
来源：http://dali.guowangkeji.top/Article/details/gtvjyljtag.html

[R76] 使用临时文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gttcrlxmys.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cqqwz.cn/Article/details/gtxhuxwqvu.html

[R77] 读取用户输入
来源：http://dali.shanyushiyangtech.top/Article/details/gtrqgayidr.html

read -rp "请输入: " ans
来源：http://dali.yanxiufei.cn/Article/details/gtojcwiern.html

[R78] 交互式菜单
来源：http://dali.c1oappe.top/Article/details/gthgnifcbz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hysaishi.cn/Article/details/gtzwxwvjwj.html

[R79] 解析命令行选项
来源：http://dali.bjfxy.top/Article/details/gtujwhftjh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yueranfly.top/Article/details/gtmtskmpcx.html

[R80] 查看脚本执行耗时
来源：http://dali.yj20258.top/Article/details/gtuwtvlsww.html

time ./run.sh
来源：http://dali.daxiang520.top/Article/details/gttzmmgnrf.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtixwnhsmd.html

S. C / C++ 专题
来源：http://dali.tian-w.cn/Article/details/gtaviwuahy.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtmtrexrwj.html

[S01] C：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtfctgfdfw.html

#include <stdio.h>
来源：http://dali.sufxvd.cn/Article/details/gtwbrbnses.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ivvv.top/Article/details/gtygpuhdmo.html

[S02] C：变量与格式化输出
来源：http://dali.kuanghao11.cn/Article/details/gtrnmzxpzk.html

int a = 10; printf("%d\n", a);
来源：http://dali.hammf.cn/Article/details/gtazplvike.html

[S03] C：读入整数
来源：http://dali.zycfv.cn/Article/details/gtiaxpylkt.html

int x; scanf("%d", &x);
来源：http://dali.sysykeji.top/Article/details/gtaypgrott.html

[S04] C：字符串复制
来源：http://dali.hywenlv.cn/Article/details/gtrysousvr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.aizwys.cn/Article/details/gtwqzgpjmv.html

[S05] C：字符串长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdremsnld.html

strlen(s)
来源：http://dali.cqqwz.cn/Article/details/gtrtwhcdna.html

[S06] C：字符串比较
来源：http://dali.cashguo.top/Article/details/gtjttajwby.html

strcmp(a, b) == 0
来源：http://dali.jinqigfzy.top/Article/details/gtvgzvlvut.html

[S07] C：数组遍历求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gttphiuuqk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.guowangkeji.top/Article/details/gteuozhhnu.html

[S08] C：动态内存分配与释放
来源：http://dali.snrcjt.cn/Article/details/gtdlruhyzn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jyoumei.cn/Article/details/gtlydiufgn.html

[S09] C：结构体定义与初始化
来源：http://dali.yanxiufei.cn/Article/details/gtospypqib.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.haohaochexian.top/Article/details/gtfifquity.html

[S10] C：指针与解引用
来源：http://dali.c1oappe.top/Article/details/gtnaevqtjl.html

int *p = &a;  *p = 5;
来源：http://dali.tian-w.cn/Article/details/gtsisoxjuh.html

[S11] C：逐行读文件
来源：http://dali.shuidangran.top/Article/details/gtyminbzep.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinqigufen.top/Article/details/gtabgvwzik.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xinyue.icu/Article/details/gtwjohdvkv.html

fclose(f);
来源：http://dali.yj20258.top/Article/details/gtepuparyd.html

[S12] C：写文件
来源：http://dali.9152youxi.cn/Article/details/gtdnzlcati.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhixingplan.top/Article/details/gtemsduljr.html

[S13] C：宏定义
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxfkyfvk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.guannengcc.top/Article/details/gtofzagnsf.html

[S14] C：枚举
来源：http://dali.gzhubu.top/Article/details/gtgdedhvyy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.vqdsnc.cn/Article/details/gtqzpfihhi.html

[S15] C：类型转换
来源：http://dali.xylfe.cn/Article/details/gtvqtwesag.html

(double) a / b
来源：http://dali.zhongyouzk.top/Article/details/gtuljagclv.html

[S16] C：位操作置位
来源：http://dali.ppjwa.cn/Article/details/gtmucqvnkj.html

x |= (1 << 3);
来源：http://dali.cqqwz.cn/Article/details/gttcvmdxjb.html

[S17] C：安全拼接字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtxkneluap.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenlongwang.top/Article/details/gtlsztclej.html

[S18] C：命令行参数
来源：http://dali.ydzc1.top/Article/details/gthkilhkjo.html

int main(int argc, char **argv)
来源：http://dali.zhixingplan.top/Article/details/gtmvlgoqiz.html

[S19] C：快速排序
来源：http://dali.xuanzx.com/Article/details/gtliggttyt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhongyouzk.top/Article/details/gtuikylqtk.html

[S20] C：二分查找
来源：http://dali.nwbrower.top/Article/details/gtddrsiata.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jyoumei.cn/Article/details/gtanylmegq.html

[S21] C：字符类别判断
来源：http://dali.redwolf501.top/Article/details/gtcnwkieob.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.daria6918.cn/Article/details/gtupcyrkfx.html

[S22] C：字符串转数字
来源：http://dali.cqqwz.cn/Article/details/gtcutkcgim.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj20258888.top/Article/details/gtfyownyjw.html

[S23] C：随机数
来源：http://dali.zycfv.cn/Article/details/gtsoazqyos.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.haohaochexian.top/Article/details/gtoboqejmg.html

[S24] C：获取本地时间
来源：http://dali.daxiang520.top/Article/details/gtnhssaqrz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shanyushiyangtech.top/Article/details/gtggkzvcdn.html

[S25] C：内存拷贝
来源：http://dali.xinyue.icu/Article/details/gtcgkodqds.html

memcpy(dst, src, n);
来源：http://dali.cheryme.top/Article/details/gtwfkksuin.html

[S26] C：内存清零
来源：http://dali.guowangkeji.top/Article/details/gtmnyaikaj.html

memset(a, 0, sizeof a);
来源：http://dali.mhx1999.top/Article/details/gtszndmwbs.html

[S27] C：定义常量
来源：http://dali.xziqi.cn/Article/details/gtvxqynrmz.html

const double PI = 3.14159;
来源：http://dali.guannengcc.top/Article/details/gtzgafxhxi.html

[S28] C：静态变量
来源：http://dali.sxryk.cn/Article/details/gtgemzhtyj.html

static int counter = 0;
来源：http://dali.havefunace.top/Article/details/gtxawxahmu.html

[S29] C：变参函数
来源：http://dali.gogol.net.cn/Article/details/gtsisaqexd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tanke756.top/Article/details/gtarfdcqkc.html

[S30] C：头文件保护
来源：http://dali.aibaodan.cn/Article/details/gtfttyruyv.html

#ifndef X_H
来源：http://dali.sufxvd.cn/Article/details/gtiumqmggm.html

#define X_H
来源：http://dali.yj202588.top/Article/details/gtcqajgual.html

#endif
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrrcxoyto.html

[S31] C++：Hello World
来源：http://dali.nwbrower.top/Article/details/gttkgzhsla.html

#include <iostream>
来源：http://dali.hnxiangtu.top/Article/details/gtgyltqacg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hfpthk.cn/Article/details/gtpicgafbo.html

[S32] C++：字符串
来源：http://dali.aibaodan.cn/Article/details/gtoezaxzja.html

std::string s = "hi";  s += "!";
来源：http://dali.chenzaomai.com/Article/details/gtbelguldt.html

[S33] C++：vector 增删
来源：http://dali.sysykeji.top/Article/details/gtjujozawy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jianghu66.top/Article/details/gtcdytpcho.html

[S34] C++：遍历 vector
来源：http://dali.daxiang520.top/Article/details/gtwoujcnwr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jqgfzy.top/Article/details/gtctpculfn.html

[S35] C++：map
来源：http://dali.316326.xyz/Article/details/gthwfkdtpe.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tanke756.top/Article/details/gtivwmrjpq.html

[S36] C++：unordered_map
来源：http://dali.ivvv.top/Article/details/gtasxvvltj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ybcxt.top/Article/details/gtwsbiuwjr.html

[S37] C++：set
来源：http://dali.jqgufenzy.top/Article/details/gtolmmhqvp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yvedp.cn/Article/details/gtuemgmuhb.html

[S38] C++：排序
来源：http://dali.jianghu66.top/Article/details/gtcqdtvpzp.html

std::sort(v.begin(), v.end());
来源：http://dali.meibo888.top/Article/details/gtnodcxnzy.html

[S39] C++：自定义比较器排序
来源：http://dali.ybcxt.top/Article/details/gtjpjhayui.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.birdmap.top/Article/details/gtiecjwrnh.html

[S40] C++：查找元素
来源：http://dali.ppjwa.cn/Article/details/gthkhhbhol.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxdpoywmk.html

[S41] C++：类与构造函数
来源：http://dali.xuanzx.com/Article/details/gtmmkaspue.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.daria6918.cn/Article/details/gtcxilylia.html

[S42] C++：继承与虚函数
来源：http://dali.chenjidiqi.icu/Article/details/gtnotjotrh.html

class B : public Base { public: void f() override {} };
来源：http://dali.haohaochexian.top/Article/details/gtjculxgfz.html

[S43] C++：智能指针
来源：http://dali.zycfv.cn/Article/details/gtjgzawfrx.html

auto p = std::make_unique<int>(5);
来源：http://dali.shuidangran.top/Article/details/gtjrzllofa.html

[S44] C++：引用传参
来源：http://dali.zhoulong.xyz/Article/details/gtcbadbhzy.html

void inc(int &x) { ++x; }
来源：http://dali.sufxvd.cn/Article/details/gteuedqzpx.html

[S45] C++：lambda
来源：http://dali.yangfankeji.com/Article/details/gtteihkrdw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zycfv.cn/Article/details/gtvxlkuvpj.html

[S46] C++：函数模板
来源：http://dali.mhx1999.top/Article/details/gtmnqlwiam.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yongpay.top/Article/details/gtqeqgjnmy.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhoulong.xyz/Article/details/gtpajskfsz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj202588.top/Article/details/gtmiwjvubg.html

[S48] C++：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gtgpmpbjua.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jianghu66.top/Article/details/gtngmillig.html

while (std::getline(in, line)) { }
来源：http://dali.fengsongda.top/Article/details/gtkqiwtaje.html

[S49] C++：写文件
来源：http://dali.gzhubu.top/Article/details/gtemdwghey.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqohcssb.html

[S50] C++：格式化数字
来源：http://dali.316326.xyz/Article/details/gtixbhween.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gtdvpnyrhj.html

[S51] C++：显式类型转换
来源：http://dali.yanxiufei.cn/Article/details/gtttgcuggt.html

static_cast<double>(a) / b
来源：http://dali.hywenlv.cn/Article/details/gtwcoygjpv.html

[S52] C++：const 与 noexcept
来源：http://dali.pengpengdd.cyou/Article/details/gtfyycinvj.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gtmeaqtbbd.html

[S53] C++：移动语义
来源：http://dali.redwolf501.top/Article/details/gtfibgbumt.html

std::vector<int> w = std::move(v);
来源：http://dali.sysykeji.top/Article/details/gtvxycbfgl.html

[S54] C++：异常处理
来源：http://dali.svipenyu.cn/Article/details/gtcgjyoqmo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yvedp.cn/Article/details/gtugwendpx.html

[S55] C++：结构化绑定
来源：http://dali.zhiwuduotai.top/Article/details/gtrrvrtigv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtvnhbkfgz.html

[S56] C++：optional
来源：http://dali.havefunace.top/Article/details/gtygceljez.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hammf.cn/Article/details/gtcttsczcy.html

[S57] C++：编译期常量
来源：http://dali.tianlin.xyz/Article/details/gtyrurdemp.html

constexpr int N = 10;
来源：http://dali.guowangkeji.top/Article/details/gtaxqnqipa.html

[S58] C++：命名空间
来源：http://dali.jinyuanbaomall.cn/Article/details/gttxseqlpw.html

namespace ns { int f() { return 1; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtttolqohj.html

[S59] C++：静态断言
来源：http://dali.jlsjyb.cn/Article/details/gtbvahvsoi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jlsjyb.cn/Article/details/gthrjdcisg.html

[S60] C++：遍历并删除元素
来源：http://dali.jqgufenzy.top/Article/details/gtqaztrzts.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gzhubu.top/Article/details/gtwmbkewal.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtgmtrztbr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.vqdsnc.cn/Article/details/gtfuymednp.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtuamjvmar.html

[T01] Kotlin：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtyqhtsesr.html

println("Hello")
来源：http://dali.yongpay.top/Article/details/gtjmfwzcvm.html

[T02] Kotlin：变量
来源：http://dali.ppjwa.cn/Article/details/gtjqvmvwij.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinghuilouyu.cn/Article/details/gtfytnvkxg.html

[T03] Kotlin：字符串模板
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfzppgfdt.html

"值: $b"
来源：http://dali.shzxlz.cn/Article/details/gtorezswwn.html

[T04] Kotlin：空安全
来源：http://dali.meibo888.top/Article/details/gthfxsrsvl.html

val n: String? = null;  n?.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtudrhmcgn.html

[T05] Kotlin：when 表达式
来源：http://dali.yuxming.cn/Article/details/gtkllplgzy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhoulong.xyz/Article/details/gtvfllmgbm.html

[T06] Kotlin：集合映射
来源：http://dali.jqgufenzy.top/Article/details/gtfqgztibo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtjmbegyzy.html

[T07] Kotlin：集合过滤
来源：http://dali.havefunace.top/Article/details/gtoswqmwox.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhixingplan.top/Article/details/gtcyfrcpht.html

[T08] Kotlin：数据类
来源：http://dali.pengpengdd.cyou/Article/details/gtxjzgsbjk.html

data class User(val name: String, val age: Int)
来源：http://dali.dashuyun.cn/Article/details/gtacevwywj.html

[T09] Kotlin：扩展函数
来源：http://dali.pengpengdd.cyou/Article/details/gtybauwzdg.html

fun String.exclaim() = this + "!"
来源：http://dali.hywenlv.cn/Article/details/gtyanytcko.html

[T10] Kotlin：默认参数
来源：http://dali.9152youxi.cn/Article/details/gtgkmawqlg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gotoacloud.top/Article/details/gtnmzlwogd.html

[T11] Kotlin：协程
来源：http://dali.yonumen.top/Article/details/gtqawpzmed.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.iojbl.cn/Article/details/gtterindfa.html

[T12] Kotlin：解构声明
来源：http://dali.zhaomingkeji.xyz/Article/details/gtedlpxdse.html

val (a, b) = Pair(1, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtbjbdgkal.html

[T13] Kotlin：只读 Map
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdeedbom.html

val m = mapOf("a" to 1)
来源：http://dali.vqdsnc.cn/Article/details/gtywdlqbtt.html

[T14] Kotlin：循环
来源：http://dali.nanxinkj.top/Article/details/gtelwnzuwd.html

for (i in 1..10) println(i)
来源：http://dali.xuetiantiany.cn/Article/details/gtzgoqqmob.html

[T15] Kotlin：接口
来源：http://dali.c1oappe.top/Article/details/gtqzevrsey.html

interface Shape { fun area(): Double }
来源：http://dali.9152youxi.cn/Article/details/gtdkknerzc.html

[T16] Swift：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtamgznuzo.html

print("Hello")
来源：http://dali.zhongyouzk.top/Article/details/gtqxbqmokl.html

[T17] Swift：变量与常量
来源：http://dali.tian-w.cn/Article/details/gtdhvcppuv.html

var a = 1;  let b = 2
来源：http://dali.jyoumei.cn/Article/details/gtenhdyksf.html

[T18] Swift：字符串插值
来源：http://dali.xylfe.cn/Article/details/gtmgmghcms.html

"值: \(b)"
来源：http://dali.ivvv.top/Article/details/gtjclhofhv.html

[T19] Swift：可选绑定
来源：http://dali.xuetiantiany.cn/Article/details/gtrctjrnfg.html

if let n = opt { print(n) }
来源：http://dali.chenzaomai.com/Article/details/gtpvozjajm.html

[T20] Swift：数组操作
来源：http://dali.wangshuangyany.cn/Article/details/gtsiywuhty.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttusnepoq.html

[T21] Swift：遍历
来源：http://dali.gogol.net.cn/Article/details/gtaipwibkz.html

for x in a { print(x) }
来源：http://dali.yangfankeji.com/Article/details/gtukeznzsh.html

[T22] Swift：字典
来源：http://dali.ehwqpu.com/Article/details/gtzvpwxwsp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.haohaochexian.top/Article/details/gtsrlcuszz.html

[T23] Swift：函数
来源：http://dali.0kj1m.cn/Article/details/gtuvvzkdsb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yvedp.cn/Article/details/gtqeplobkz.html

[T24] Swift：闭包
来源：http://dali.dianchejie.cn/Article/details/gtwhfkfdpp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhoulong.xyz/Article/details/gttqkgeppe.html

[T25] Swift：结构体
来源：http://dali.aibaodan.cn/Article/details/gtphfkcdac.html

struct P { var x: Int }
来源：http://dali.jinqigufen.top/Article/details/gtyepqslhg.html

[T26] Swift：类与重写
来源：http://dali.yj20258.top/Article/details/gttbetjkqy.html

class A: Base { override func f() {} }
来源：http://dali.fengsongda.top/Article/details/gtmkxqdltw.html

[T27] Swift：错误处理
来源：http://dali.gogol.net.cn/Article/details/gtkvovnjpo.html

do { try f() } catch { print(error) }
来源：http://dali.pengpengdd.cyou/Article/details/gtlzdkuatz.html

[T28] Swift：枚举
来源：http://dali.nanxuanxn.top/Article/details/gttmkqmuih.html

enum Color { case red, green }
来源：http://dali.jinqigufen.top/Article/details/gtplvwbvek.html

[T29] Swift：guard 提前返回
来源：http://dali.shuidangran.top/Article/details/gtcjwoaxbg.html

guard let x = opt else { return }
来源：http://dali.ehwqpu.com/Article/details/gtkltqbwkn.html

[T30] Swift：协议
来源：http://dali.gaohongyu789.top/Article/details/gtbilzpton.html

protocol Shape { func area() -> Double }
来源：http://dali.c1oappe.top/Article/details/gtwxciezzw.html

[T31] Lua：Hello World
来源：http://dali.hnqzz.top/Article/details/gtvwvenban.html

print("Hello")
来源：http://dali.bjfxy.top/Article/details/gtkjubuezl.html

[T32] Lua：局部变量
来源：http://dali.nwbrower.top/Article/details/gtmasmltva.html

local a = 1
来源：http://dali.jianghu66.top/Article/details/gtcysaxtqz.html

[T33] Lua：表（数组）
来源：http://dali.havefunace.top/Article/details/gtpqrcratx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhongyouzk.top/Article/details/gtupquxaju.html

[T34] Lua：遍历表
来源：http://dali.vqdsnc.cn/Article/details/gtlrryiijl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cdnleiting.top/Article/details/gtihsynyxw.html

[T35] Lua：字典表
来源：http://dali.yj202588.top/Article/details/gtixyffyts.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tianlin.xyz/Article/details/gtijbtkodv.html

[T36] Lua：函数
来源：http://dali.hammf.cn/Article/details/gttrejyyoj.html

function add(a, b) return a + b end
来源：http://dali.shangyingyoupin.top/Article/details/gtixoopybq.html

[T37] Lua：字符串拼接
来源：http://dali.tianlin.xyz/Article/details/gtjbhuuxhq.html

"a" .. "b"
来源：http://dali.shuidangran.top/Article/details/gtijuymqva.html

[T38] Lua：条件
来源：http://dali.yvedp.cn/Article/details/gtyvmzpxni.html

if x > 0 then print("正") end
来源：http://dali.shangyingyoupin.top/Article/details/gtzpygrjqb.html

[T39] Lua：模式匹配
来源：http://dali.ppjwa.cn/Article/details/gtbaicavdi.html

string.find(s, "%d+")
来源：http://dali.gaohongyu789.top/Article/details/gtkkaovipv.html

[T40] Lua：元表
来源：http://dali.sweek.top/Article/details/gtxkuxhvxz.html

setmetatable({}, { __index = base })
来源：http://dali.shangyingyoupin.top/Article/details/gtfctebtaq.html

[T41] Perl：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtpmepaugr.html

print "Hello\n";
来源：http://dali.jqgufenzy.top/Article/details/gtbvbigzyj.html

[T42] Perl：变量类型
来源：http://dali.shzxlz.cn/Article/details/gtqpqgvxvy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cashguo.top/Article/details/gtzypmaemf.html

[T43] Perl：字符串插值
来源：http://dali.cashguo.top/Article/details/gtgyltjeke.html

"值: $a"
来源：http://dali.svipenyu.cn/Article/details/gtiwwrcvha.html

[T44] Perl：条件
来源：http://dali.yj20258.top/Article/details/gtfebhnfei.html

if ($a > 0) { print "正"; }
来源：http://dali.guowangkeji.top/Article/details/gtudeoyjyn.html

[T45] Perl：数组遍历
来源：http://dali.yuxming.cn/Article/details/gtmzxmsmhc.html

for my $x (@arr) { print $x; }
来源：http://dali.iojbl.cn/Article/details/gtlqanoxpy.html

[T46] Perl：哈希操作
来源：http://dali.chenjidiqi.icu/Article/details/gtzftsevuh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shuidangran.top/Article/details/gtoflbeosl.html

[T47] Perl：正则捕获
来源：http://dali.hysaishi.cn/Article/details/gtknjtecte.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cucudq.cn/Article/details/gtftkpyrgo.html

[T48] Perl：正则替换
来源：http://dali.dianchejie.cn/Article/details/gtfwwyuaad.html

$s =~ s/old/new/g;
来源：http://dali.0kj1m.cn/Article/details/gtrbuwtlmz.html

[T49] Perl：函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsksvdkzl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gtdrnsomsi.html

[T50] Perl：逐行读文件
来源：http://dali.smart0.xyz/Article/details/gtdikapbgt.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.feifeiyinyue.top/Article/details/gtkgdqukxy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ppjwa.cn/Article/details/gtqwfbdmut.html

[T51] Scala：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtlvkmiyeh.html

println("Hello")
来源：http://dali.birdmap.top/Article/details/gtzmdugkvg.html

[T52] Scala：变量
来源：http://dali.yuxming.cn/Article/details/gtwzchqnii.html

val a = 1;  var b = 2
来源：http://dali.chenzaomai.com/Article/details/gtpajpbrur.html

[T53] Scala：字符串插值
来源：http://dali.yj202588.top/Article/details/gtbasxgpmn.html

s"值: $b"
来源：http://dali.jianghu66.top/Article/details/gthvudweoz.html

[T54] Scala：集合映射
来源：http://dali.aizwys.cn/Article/details/gtgjaozgsq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hfpthk.cn/Article/details/gtokdpooce.html

[T55] Scala：集合过滤
来源：http://dali.vqdsnc.cn/Article/details/gtslyyyhbj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.kuanghao11.cn/Article/details/gthgbpgosf.html

[T56] Scala：样例类
来源：http://dali.gogol.net.cn/Article/details/gtoeduinqd.html

case class User(name: String, age: Int)
来源：http://dali.jiagoushi.top/Article/details/gtluibkogm.html

[T57] Scala：模式匹配
来源：http://dali.sufxvd.cn/Article/details/gthklwqyhp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ivvv.top/Article/details/gtpzmkhogo.html

[T58] Scala：函数定义
来源：http://dali.cdnleiting.top/Article/details/gtwwnizfyn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.tanke756.top/Article/details/gtfnjoprdv.html

[T59] Scala：循环
来源：http://dali.fzhhl.top/Article/details/gtvqgnimyv.html

for (i <- 1 to 10) println(i)
来源：http://dali.c1oappe.top/Article/details/gtjddbfuiq.html

[T60] Scala：折叠
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnuuglits.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yvedp.cn/Article/details/gtwlqrvrsh.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtefepdfjn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zycfv.cn/Article/details/gtywifxzbr.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtwhfvelxd.html

[U01] Py：创建虚拟环境
来源：http://dali.jinghuilouyu.cn/Article/details/gtbdgjqvlt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zdqjudy.top/Article/details/gtplnudvxa.html

[U02] Py：导出 / 安装依赖
来源：http://dali.dashuyun.cn/Article/details/gtlnlbeczs.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gzhubu.top/Article/details/gtebefonke.html

[U03] Py：加载 .env 配置
来源：http://dali.sufxvd.cn/Article/details/gtojzycoaj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.316326.xyz/Article/details/gtgdeqhyaj.html

[U04] Py：变量调试打印
来源：http://dali.xuanzx.com/Article/details/gtfckyoymm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xziqi.cn/Article/details/gtzvbrydgf.html

[U05] Py：列表去重且保序
来源：http://dali.hfpthk.cn/Article/details/gtxemajyrk.html

list(dict.fromkeys(arr))
来源：http://dali.jinqigfzy.top/Article/details/gtvichjkar.html

[U06] Py：合并两个字典
来源：http://dali.vqdsnc.cn/Article/details/gtjutktice.html

{**a, **b}
来源：http://dali.hongshengwenyu.top/Article/details/gtaempilcv.html

[U07] Py：反转字典键值
来源：http://dali.hywenlv.cn/Article/details/gtgrxqlxad.html

{v: k for k, v in d.items()}
来源：http://dali.guowangkeji.top/Article/details/gtoxnndida.html

[U08] Py：展平二维列表
来源：http://dali.quarkkingdee.top/Article/details/gtcsgqrqle.html

[y for x in nested for y in x]
来源：http://dali.nanxuanxn.top/Article/details/gtgvfyvsvt.html

[U09] Py：字典取最大值的键
来源：http://dali.aizwys.cn/Article/details/gtsmsshcdh.html

max(d, key=d.get)
来源：http://dali.zhongyouzk.top/Article/details/gtbxvdrvak.html

[U10] Py：按值排序字典
来源：http://dali.yanxiufei.cn/Article/details/gtrplwokpb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.9152youxi.cn/Article/details/gtjbdzoshp.html

[U11] Py：生成器表达式
来源：http://dali.ehwqpu.com/Article/details/gtubqpypvo.html

(x * 2 for x in arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtekxrzwny.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.andypj.xyz/Article/details/gtdpvjdybo.html

Counter(arr).most_common(3)
来源：http://dali.sufxvd.cn/Article/details/gtuibkogns.html

[U13] Py：固定长度队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtroktyayr.html

deque(maxlen=10)
来源：http://dali.kuanghao11.cn/Article/details/gtyhxzxpcr.html

[U14] Py：分组收集到列表
来源：http://dali.shzxlz.cn/Article/details/gtylszmozl.html

defaultdict(list)
来源：http://dali.daria6918.cn/Article/details/gtrithnzrw.html

[U15] Py：高精度计时
来源：http://dali.pycfn.com/Article/details/gtfifjxefz.html

t = time.perf_counter()
来源：http://dali.sysykeji.top/Article/details/gtwkihtnew.html

[U16] Py：命令行参数解析
来源：http://dali.aibaodan.cn/Article/details/gteotjbejo.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yj202588.top/Article/details/gtjbmtliwr.html


<!-- 参考信息 -->