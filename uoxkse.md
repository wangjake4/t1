代发 wailian999

split -l 1000 big.log part_
来源：http://dali.yj20258888.top/Article/details/gtgxbymkri.html

[R74] 批量重命名
来源：http://dali.svipenyu.cn/Article/details/gtaeiuhaae.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ivvv.top/Article/details/gtudghdrgo.html

[R75] 导出环境变量
来源：http://dali.sysykeji.top/Article/details/gtbdshplnq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hammf.cn/Article/details/gtfndwzbol.html

[R76] 使用临时文件
来源：http://dali.daria6918.cn/Article/details/gtnwotlyae.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ivvv.top/Article/details/gtuwogveek.html

[R77] 读取用户输入
来源：http://dali.svipenyu.cn/Article/details/gtpurekmek.html

read -rp "请输入: " ans
来源：http://dali.yueranfly.top/Article/details/gtedobugye.html

[R78] 交互式菜单
来源：http://dali.xziqi.cn/Article/details/gtepowyffp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtimqdqvay.html

[R79] 解析命令行选项
来源：http://dali.aibaodan.cn/Article/details/gtlizxwokp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj202588.top/Article/details/gtnatsrhza.html

[R80] 查看脚本执行耗时
来源：http://dali.smart0.xyz/Article/details/gtpginodra.html

time ./run.sh
来源：http://dali.haohaochexian.top/Article/details/gtswuylhay.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtprkknkwx.html

S. C / C++ 专题
来源：http://dali.sufxvd.cn/Article/details/gtsxoblecp.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtueftjhao.html

[S01] C：Hello World
来源：http://dali.birdmap.top/Article/details/gtrdsnxebi.html

#include <stdio.h>
来源：http://dali.jinghuilouyu.cn/Article/details/gtlvcfznep.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xziqi.cn/Article/details/gtgrgdyjiu.html

[S02] C：变量与格式化输出
来源：http://dali.cqqwz.cn/Article/details/gtkuxbrenh.html

int a = 10; printf("%d\n", a);
来源：http://dali.ybcxt.top/Article/details/gtyjzplyuw.html

[S03] C：读入整数
来源：http://dali.yongpay.top/Article/details/gtilmrepwl.html

int x; scanf("%d", &x);
来源：http://dali.jiagoushi.top/Article/details/gtfyzrejvs.html

[S04] C：字符串复制
来源：http://dali.zhixingplan.top/Article/details/gtpxheprws.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.9152youxi.cn/Article/details/gteoryowqm.html

[S05] C：字符串长度
来源：http://dali.fzhhl.top/Article/details/gtsonbenqk.html

strlen(s)
来源：http://dali.daria6918.cn/Article/details/gtfjdtzgdg.html

[S06] C：字符串比较
来源：http://dali.tian-w.cn/Article/details/gtwkfrnlqi.html

strcmp(a, b) == 0
来源：http://dali.fengsongda.top/Article/details/gtwurvibfq.html

[S07] C：数组遍历求和
来源：http://dali.nanxinkj.top/Article/details/gtnyrrbtov.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.haohaochexian.top/Article/details/gtxijbqfma.html

[S08] C：动态内存分配与释放
来源：http://dali.yvedp.cn/Article/details/gthjtactmy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xylfe.cn/Article/details/gtjvjkzyao.html

[S09] C：结构体定义与初始化
来源：http://dali.svipenyu.cn/Article/details/gtesslqygl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.pycfn.com/Article/details/gtpykqfgda.html

[S10] C：指针与解引用
来源：http://dali.kuanghao11.cn/Article/details/gtkihgkrvj.html

int *p = &a;  *p = 5;
来源：http://dali.shangyingyoupin.top/Article/details/gtjltbchqv.html

[S11] C：逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gtefakoxbq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.andypj.xyz/Article/details/gthdbpnigq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.dianchejie.cn/Article/details/gtsttnvavr.html

fclose(f);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaxniqflq.html

[S12] C：写文件
来源：http://dali.jqgfzy.top/Article/details/gtnzdrgwqg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangshuangyany.cn/Article/details/gtacliotir.html

[S13] C：宏定义
来源：http://dali.yj20258888.top/Article/details/gtzobbqxle.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.vqdsnc.cn/Article/details/gtectimfbj.html

[S14] C：枚举
来源：http://dali.yanxiufei.cn/Article/details/gtlxppuulw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.iojbl.cn/Article/details/gtcnrfzsfl.html

[S15] C：类型转换
来源：http://dali.shzxlz.cn/Article/details/gttpxslwan.html

(double) a / b
来源：http://dali.gotoacloud.top/Article/details/gtnpqtynat.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gttmwprkst.html

x |= (1 << 3);
来源：http://dali.zhengqikj.top/Article/details/gtrtbyxymb.html

[S17] C：安全拼接字符串
来源：http://dali.hammf.cn/Article/details/gtwkthwvys.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.316326.xyz/Article/details/gtimwrawiz.html

[S18] C：命令行参数
来源：http://dali.feifeiyinyue.top/Article/details/gtqrghneir.html

int main(int argc, char **argv)
来源：http://dali.jinqigfzy.top/Article/details/gtynkdgnzo.html

[S19] C：快速排序
来源：http://dali.redwolf501.top/Article/details/gtrbxqmepb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xinyue.icu/Article/details/gtewksgjlb.html

[S20] C：二分查找
来源：http://dali.nanxuanxn.top/Article/details/gtsugbtfgw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yonumen.top/Article/details/gtudblnjfd.html

[S21] C：字符类别判断
来源：http://dali.gogol.net.cn/Article/details/gtwiwcwucs.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yuanzhike.top/Article/details/gtqcgixskd.html

[S22] C：字符串转数字
来源：http://dali.9152youxi.cn/Article/details/gtqgnvfuax.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.pengpengdd.cyou/Article/details/gtextrxqpe.html

[S23] C：随机数
来源：http://dali.fzhhl.top/Article/details/gtnzffztci.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.daxiang520.top/Article/details/gtnbirults.html

[S24] C：获取本地时间
来源：http://dali.cheryme.top/Article/details/gtfhhjloet.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhixingplan.top/Article/details/gtgwdjjeaw.html

[S25] C：内存拷贝
来源：http://dali.gotoacloud.top/Article/details/gtulwgvvjz.html

memcpy(dst, src, n);
来源：http://dali.9152youxi.cn/Article/details/gtkorxrgbx.html

[S26] C：内存清零
来源：http://dali.sufxvd.cn/Article/details/gtdypagmxx.html

memset(a, 0, sizeof a);
来源：http://dali.hysaishi.cn/Article/details/gtxkrwdjyu.html

[S27] C：定义常量
来源：http://dali.jqgfzy.top/Article/details/gtbtwkxdab.html

const double PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtrswdpnhj.html

[S28] C：静态变量
来源：http://dali.nanxinkj.top/Article/details/gtvmeufqed.html

static int counter = 0;
来源：http://dali.cucudq.cn/Article/details/gtilnnfaed.html

[S29] C：变参函数
来源：http://dali.zycfv.cn/Article/details/gtknxowuea.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yanxiufei.cn/Article/details/gtgebfwvvf.html

[S30] C：头文件保护
来源：http://dali.dashuyun.cn/Article/details/gthboupniw.html

#ifndef X_H
来源：http://dali.feifeiyinyue.top/Article/details/gtvlqfakbz.html

#define X_H
来源：http://dali.guannengcc.top/Article/details/gtaahtxhjl.html

#endif
来源：http://dali.jiagoushi.top/Article/details/gttjklsvjz.html

[S31] C++：Hello World
来源：http://dali.316326.xyz/Article/details/gtuarukaaz.html

#include <iostream>
来源：http://dali.cashguo.top/Article/details/gtbijsebdl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.meibo888.top/Article/details/gtfmqwhdho.html

[S32] C++：字符串
来源：http://dali.guowangkeji.top/Article/details/gtkaqvwyij.html

std::string s = "hi";  s += "!";
来源：http://dali.gogol.net.cn/Article/details/gtzidfixrd.html

[S33] C++：vector 增删
来源：http://dali.andypj.xyz/Article/details/gthsnasbwt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jqgufenzy.top/Article/details/gteqyuotuz.html

[S34] C++：遍历 vector
来源：http://dali.jlsjyb.cn/Article/details/gtkwiagnni.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yuxming.cn/Article/details/gtozovlygr.html

[S35] C++：map
来源：http://dali.chenlongwang.top/Article/details/gtianmvnej.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtnzxhexpf.html

[S36] C++：unordered_map
来源：http://dali.vqdsnc.cn/Article/details/gtfufgldcd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cucudq.cn/Article/details/gtnwhkvoub.html

[S37] C++：set
来源：http://dali.chenlongwang.top/Article/details/gtohmbmlrc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhongyouzk.top/Article/details/gtlagzyhvn.html

[S38] C++：排序
来源：http://dali.yonumen.top/Article/details/gtlxduwcsl.html

std::sort(v.begin(), v.end());
来源：http://dali.hywenlv.cn/Article/details/gttjoaaalg.html

[S39] C++：自定义比较器排序
来源：http://dali.sysykeji.top/Article/details/gtgeniqywg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yuanzhike.top/Article/details/gtokabhdyq.html

[S40] C++：查找元素
来源：http://dali.chenlongwang.top/Article/details/gtsqvpctjf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.9152youxi.cn/Article/details/gtteknzpnf.html

[S41] C++：类与构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtamevqpad.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jiagoushi.top/Article/details/gtogtgdlqy.html

[S42] C++：继承与虚函数
来源：http://dali.birdmap.top/Article/details/gtjtxacqem.html

class B : public Base { public: void f() override {} };
来源：http://dali.pengpengdd.cyou/Article/details/gtawloelsh.html

[S43] C++：智能指针
来源：http://dali.shzxlz.cn/Article/details/gtluvxxkzh.html

auto p = std::make_unique<int>(5);
来源：http://dali.yj20258888.top/Article/details/gtbqggqpnx.html

[S44] C++：引用传参
来源：http://dali.chenzaomai.com/Article/details/gtgurbmpfn.html

void inc(int &x) { ++x; }
来源：http://dali.yj20258888.top/Article/details/gtkgulwshb.html

[S45] C++：lambda
来源：http://dali.feifeiyinyue.top/Article/details/gtwkbqqvkt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.pycfn.com/Article/details/gtxnmbdezd.html

[S46] C++：函数模板
来源：http://dali.cheryme.top/Article/details/gtxdfbxula.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.nanxinkj.top/Article/details/gtmjhxyseu.html

[S47] C++：结构化绑定遍历
来源：http://dali.cqqwz.cn/Article/details/gtwihtawrt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gtyyozurzy.html

[S48] C++：逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gtjytogili.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jlsjyb.cn/Article/details/gtyvvtpdgc.html

while (std::getline(in, line)) { }
来源：http://dali.hammf.cn/Article/details/gtdsbschln.html

[S49] C++：写文件
来源：http://dali.daria6918.cn/Article/details/gtbafplolw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.dashuyun.cn/Article/details/gtbidhhggl.html

[S50] C++：格式化数字
来源：http://dali.zycfv.cn/Article/details/gtcmsfkvcf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yvedp.cn/Article/details/gtkfmdoxxa.html

[S51] C++：显式类型转换
来源：http://dali.svipenyu.cn/Article/details/gtvqzzpgxm.html

static_cast<double>(a) / b
来源：http://dali.chenlongwang.top/Article/details/gtzuybevyz.html

[S52] C++：const 与 noexcept
来源：http://dali.havefunace.top/Article/details/gtfbrsefpx.html

int size() const noexcept { return n_; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjqzjvkrl.html

[S53] C++：移动语义
来源：http://dali.wangdashe.top/Article/details/gtpijojlui.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gtkkqhtqye.html

[S54] C++：异常处理
来源：http://dali.tian-w.cn/Article/details/gtipnmvqkd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhiwuduotai.top/Article/details/gtgwsglcur.html

[S55] C++：结构化绑定
来源：http://dali.dianchejie.cn/Article/details/gtrcafwcyk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sweek.top/Article/details/gtnrdgcmyu.html

[S56] C++：optional
来源：http://dali.feifeiyinyue.top/Article/details/gtwhmzdqln.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhongyouzk.top/Article/details/gtfutvskqe.html

[S57] C++：编译期常量
来源：http://dali.iojbl.cn/Article/details/gtznpgangv.html

constexpr int N = 10;
来源：http://dali.vqdsnc.cn/Article/details/gtnpwhsaup.html

[S58] C++：命名空间
来源：http://dali.havefunace.top/Article/details/gtlkmrimdk.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdsqgmamc.html

[S59] C++：静态断言
来源：http://dali.meibo888.top/Article/details/gtllwrgpuf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.chenzaomai.com/Article/details/gtxbljsrjm.html

[S60] C++：遍历并删除元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtdvdzboab.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.meibo888.top/Article/details/gtdcrzzeyl.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtvqaffhax.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.redwolf501.top/Article/details/gtegnkzvaq.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthheuzgsu.html

[T01] Kotlin：Hello World
来源：http://dali.birdmap.top/Article/details/gtwixduwss.html

println("Hello")
来源：http://dali.316326.xyz/Article/details/gthbwofzxy.html

[T02] Kotlin：变量
来源：http://dali.zhiwuduotai.top/Article/details/gtnpcwnftc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cucudq.cn/Article/details/gtunezlrwg.html

[T03] Kotlin：字符串模板
来源：http://dali.zhiwuduotai.top/Article/details/gtxjfhyikq.html

"值: $b"
来源：http://dali.sufxvd.cn/Article/details/gtmskbdtqw.html

[T04] Kotlin：空安全
来源：http://dali.hongshengwenyu.top/Article/details/gtuiqhvpgn.html

val n: String? = null;  n?.length
来源：http://dali.jqgfzy.top/Article/details/gtikahzzba.html

[T05] Kotlin：when 表达式
来源：http://dali.ivvv.top/Article/details/gtyivyoupg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.haohaochexian.top/Article/details/gtjcffgxzf.html

[T06] Kotlin：集合映射
来源：http://dali.hywenlv.cn/Article/details/gtcbasrzcg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtenagaszt.html

[T07] Kotlin：集合过滤
来源：http://dali.hywenlv.cn/Article/details/gtzachkmkk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.daxiang520.top/Article/details/gtkksuoorc.html

[T08] Kotlin：数据类
来源：http://dali.yj20258.top/Article/details/gtnfxrrfah.html

data class User(val name: String, val age: Int)
来源：http://dali.gaohongyu789.top/Article/details/gtywoqjjvp.html

[T09] Kotlin：扩展函数
来源：http://dali.bjfxy.top/Article/details/gtiqfzumxb.html

fun String.exclaim() = this + "!"
来源：http://dali.nwbrower.top/Article/details/gthjhxijom.html

[T10] Kotlin：默认参数
来源：http://dali.yvedp.cn/Article/details/gtqpeylpgy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.feifeiyinyue.top/Article/details/gtrhgeyawn.html

[T11] Kotlin：协程
来源：http://dali.jiagoushi.top/Article/details/gtqrsohzru.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ivvv.top/Article/details/gtqaiyfneq.html

[T12] Kotlin：解构声明
来源：http://dali.hfpthk.cn/Article/details/gtlwmheoxh.html

val (a, b) = Pair(1, 2)
来源：http://dali.xinyue.icu/Article/details/gtmnoojqkw.html

[T13] Kotlin：只读 Map
来源：http://dali.jyoumei.cn/Article/details/gtedxuhxim.html

val m = mapOf("a" to 1)
来源：http://dali.yuxming.cn/Article/details/gtgmsrzgcn.html

[T14] Kotlin：循环
来源：http://dali.tanke756.top/Article/details/gtywdltavw.html

for (i in 1..10) println(i)
来源：http://dali.jyoumei.cn/Article/details/gtdkrkuofb.html

[T15] Kotlin：接口
来源：http://dali.jyoumei.cn/Article/details/gtookcvuzh.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gtxyuyngqn.html

[T16] Swift：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtxjjcwdga.html

print("Hello")
来源：http://dali.9152youxi.cn/Article/details/gtjoeywada.html

[T17] Swift：变量与常量
来源：http://dali.chenzaomai.com/Article/details/gtxsjmlazt.html

var a = 1;  let b = 2
来源：http://dali.havefunace.top/Article/details/gtrelzfvef.html

[T18] Swift：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gtvoptdqso.html

"值: \(b)"
来源：http://dali.hfpthk.cn/Article/details/gtfxtrhccu.html

[T19] Swift：可选绑定
来源：http://dali.316326.xyz/Article/details/gtigfjmkml.html

if let n = opt { print(n) }
来源：http://dali.zhiwuduotai.top/Article/details/gtxtjnnqqm.html

[T20] Swift：数组操作
来源：http://dali.shuidangran.top/Article/details/gteuuorysd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nanxuanxn.top/Article/details/gtgwejmttl.html

[T21] Swift：遍历
来源：http://dali.cqqwz.cn/Article/details/gtswvjtczt.html

for x in a { print(x) }
来源：http://dali.birdmap.top/Article/details/gtopgwzoyg.html

[T22] Swift：字典
来源：http://dali.jinqigfzy.top/Article/details/gtxytgdswl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhengqikj.top/Article/details/gtnvduexhu.html

[T23] Swift：函数
来源：http://dali.aibaodan.cn/Article/details/gtifxrdgxe.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.c1oappe.top/Article/details/gtuvbxckhr.html

[T24] Swift：闭包
来源：http://dali.jinghuilouyu.cn/Article/details/gtuyuvouzv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yj202588.top/Article/details/gtfqxwbjpv.html

[T25] Swift：结构体
来源：http://dali.c1oappe.top/Article/details/gtajmlntny.html

struct P { var x: Int }
来源：http://dali.jqgfzy.top/Article/details/gtebnfqzfe.html

[T26] Swift：类与重写
来源：http://dali.daxiang520.top/Article/details/gtkrbxhsga.html

class A: Base { override func f() {} }
来源：http://dali.daxiang520.top/Article/details/gtngwgdxzu.html

[T27] Swift：错误处理
来源：http://dali.jinqigufen.top/Article/details/gtasupvyfk.html

do { try f() } catch { print(error) }
来源：http://dali.bjfxy.top/Article/details/gtcqeddxsu.html

[T28] Swift：枚举
来源：http://dali.gogol.net.cn/Article/details/gtbqfulmqr.html

enum Color { case red, green }
来源：http://dali.yuanzhike.top/Article/details/gtvmwqoelk.html

[T29] Swift：guard 提前返回
来源：http://dali.xziqi.cn/Article/details/gtaghaglnx.html

guard let x = opt else { return }
来源：http://dali.yonumen.top/Article/details/gtljokhcaa.html

[T30] Swift：协议
来源：http://dali.dianchejie.cn/Article/details/gtxoyxhxyc.html

protocol Shape { func area() -> Double }
来源：http://dali.9152youxi.cn/Article/details/gtkxfcwlrs.html

[T31] Lua：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtqybitgvr.html

print("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gtpsfvmbve.html

[T32] Lua：局部变量
来源：http://dali.yanxiufei.cn/Article/details/gtsogqdmlr.html

local a = 1
来源：http://dali.nanxuanxn.top/Article/details/gtzpehdlkh.html

[T33] Lua：表（数组）
来源：http://dali.tian-w.cn/Article/details/gtooyqwjii.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdfivcqla.html

[T34] Lua：遍历表
来源：http://dali.yonumen.top/Article/details/gtnhaajvfy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.wangshuangyany.cn/Article/details/gtajchtxck.html

[T35] Lua：字典表
来源：http://dali.shuidangran.top/Article/details/gtjpgtcmup.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jianghu66.top/Article/details/gtwxkyrgzc.html

[T36] Lua：函数
来源：http://dali.zhengqikj.top/Article/details/gtlfwkixrq.html

function add(a, b) return a + b end
来源：http://dali.yangfankeji.com/Article/details/gtsmnylyla.html

[T37] Lua：字符串拼接
来源：http://dali.cheryme.top/Article/details/gtdukamfof.html

"a" .. "b"
来源：http://dali.zycfv.cn/Article/details/gtqjmrfxbx.html

[T38] Lua：条件
来源：http://dali.gotoacloud.top/Article/details/gtwtnmlbtg.html

if x > 0 then print("正") end
来源：http://dali.wangshuangyany.cn/Article/details/gtrkpsxeed.html

[T39] Lua：模式匹配
来源：http://dali.sysykeji.top/Article/details/gtrbaslame.html

string.find(s, "%d+")
来源：http://dali.havefunace.top/Article/details/gtrbsmhclt.html

[T40] Lua：元表
来源：http://dali.chenzaomai.com/Article/details/gtqeqtdvrn.html

setmetatable({}, { __index = base })
来源：http://dali.wangshuangyany.cn/Article/details/gtqbshylow.html

[T41] Perl：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtubrvqcjh.html

print "Hello\n";
来源：http://dali.fengsongda.top/Article/details/gtyvqjvcnt.html

[T42] Perl：变量类型
来源：http://dali.yj20258888.top/Article/details/gtzezcxerk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gogol.net.cn/Article/details/gtaejksuyg.html

[T43] Perl：字符串插值
来源：http://dali.meibo888.top/Article/details/gtjtnfonud.html

"值: $a"
来源：http://dali.shzxlz.cn/Article/details/gtsygnolws.html

[T44] Perl：条件
来源：http://dali.xinyue.icu/Article/details/gtnxnoqymq.html

if ($a > 0) { print "正"; }
来源：http://dali.jlsjyb.cn/Article/details/gtkqbcccwu.html

[T45] Perl：数组遍历
来源：http://dali.haohaochexian.top/Article/details/gtjjwxinvo.html

for my $x (@arr) { print $x; }
来源：http://dali.hywenlv.cn/Article/details/gtigqlwrvb.html

[T46] Perl：哈希操作
来源：http://dali.nwbrower.top/Article/details/gthaeszkzt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhoulong.xyz/Article/details/gtzhrcmzyg.html

[T47] Perl：正则捕获
来源：http://dali.yueranfly.top/Article/details/gtsyetrqnv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shangyingyoupin.top/Article/details/gtnwvowshy.html

[T48] Perl：正则替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlyinucfd.html

$s =~ s/old/new/g;
来源：http://dali.svipenyu.cn/Article/details/gtzvqmfhpp.html

[T49] Perl：函数
来源：http://dali.birdmap.top/Article/details/gtuxcynbba.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yangfankeji.com/Article/details/gtyoixojke.html

[T50] Perl：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gtvvpnuzma.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.feifeiyinyue.top/Article/details/gtrwkqmmgx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yj202588.top/Article/details/gtwhhjiijq.html

[T51] Scala：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gthdwkbvnc.html

println("Hello")
来源：http://dali.haohaochexian.top/Article/details/gtnzsyimop.html

[T52] Scala：变量
来源：http://dali.xuetiantiany.cn/Article/details/gtjyxfljta.html

val a = 1;  var b = 2
来源：http://dali.yvedp.cn/Article/details/gtalpepmie.html

[T53] Scala：字符串插值
来源：http://dali.cheryme.top/Article/details/gtoqarfaao.html

s"值: $b"
来源：http://dali.cashguo.top/Article/details/gtzjxzjspf.html

[T54] Scala：集合映射
来源：http://dali.shzxlz.cn/Article/details/gtrxibedko.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.dashuyun.cn/Article/details/gtlicsiaue.html

[T55] Scala：集合过滤
来源：http://dali.sweek.top/Article/details/gtmwavdrpy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.0kj1m.cn/Article/details/gtsltymcwh.html

[T56] Scala：样例类
来源：http://dali.316326.xyz/Article/details/gtspfmnktw.html

case class User(name: String, age: Int)
来源：http://dali.mhx1999.top/Article/details/gtqcztmlsf.html

[T57] Scala：模式匹配
来源：http://dali.fengsongda.top/Article/details/gtxtmtxnns.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hfpthk.cn/Article/details/gtqqooyeqk.html

[T58] Scala：函数定义
来源：http://dali.tanke756.top/Article/details/gtyesjkwhc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gaohongyu789.top/Article/details/gtopmyewkj.html

[T59] Scala：循环
来源：http://dali.fzhhl.top/Article/details/gtdlzeenqk.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinqigfzy.top/Article/details/gtlucvwruo.html

[T60] Scala：折叠
来源：http://dali.dashuyun.cn/Article/details/gtfrvttxxh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xuanzx.com/Article/details/gtviwwruxm.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtsscxqbwa.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ivvv.top/Article/details/gtispfegho.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gttbwicuwr.html

[U01] Py：创建虚拟环境
来源：http://dali.zycfv.cn/Article/details/gtewdhkzim.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yuanzhike.top/Article/details/gtpdbmqosd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.meibo888.top/Article/details/gtmjxxhcjb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.svipenyu.cn/Article/details/gtukausccf.html

[U03] Py：加载 .env 配置
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiqcznmzv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.nanxuanxn.top/Article/details/gtdjpewfsh.html

[U04] Py：变量调试打印
来源：http://dali.chenzaomai.com/Article/details/gtaavwrgsy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhixingplan.top/Article/details/gthlllhmzs.html

[U05] Py：列表去重且保序
来源：http://dali.jlsjyb.cn/Article/details/gtopenwpcw.html

list(dict.fromkeys(arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtanoctuer.html

[U06] Py：合并两个字典
来源：http://dali.zdqjudy.top/Article/details/gtywuvzagk.html

{**a, **b}
来源：http://dali.pycfn.com/Article/details/gtyctsthyb.html

[U07] Py：反转字典键值
来源：http://dali.wangdashe.top/Article/details/gtsqikyfgq.html

{v: k for k, v in d.items()}
来源：http://dali.birdmap.top/Article/details/gtuciraetr.html

[U08] Py：展平二维列表
来源：http://dali.sufxvd.cn/Article/details/gtniotsnsw.html

[y for x in nested for y in x]
来源：http://dali.0kj1m.cn/Article/details/gtombhypbh.html

[U09] Py：字典取最大值的键
来源：http://dali.zdqjudy.top/Article/details/gtwpcsmqez.html

max(d, key=d.get)
来源：http://dali.jyoumei.cn/Article/details/gtzpgvrlws.html

[U10] Py：按值排序字典
来源：http://dali.fzhhl.top/Article/details/gtkitjxelr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yuxming.cn/Article/details/gtebjufarj.html

[U11] Py：生成器表达式
来源：http://dali.daria6918.cn/Article/details/gtunaldyea.html

(x * 2 for x in arr)
来源：http://dali.pycfn.com/Article/details/gtydfmrhwz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.daria6918.cn/Article/details/gtvfttaevw.html

Counter(arr).most_common(3)
来源：http://dali.nwbrower.top/Article/details/gtdpostlnv.html

[U13] Py：固定长度队列
来源：http://dali.xuanzx.com/Article/details/gteybnejzn.html

deque(maxlen=10)
来源：http://dali.316326.xyz/Article/details/gtxaxwtize.html

[U14] Py：分组收集到列表
来源：http://dali.sysykeji.top/Article/details/gthxomdxzv.html

defaultdict(list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbnbumoe.html


<!-- 参考信息 -->