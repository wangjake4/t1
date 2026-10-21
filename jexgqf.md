代发 wailian999

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzqprpfns.html

[R72] 等待端口就绪
来源：http://dali.yj20258.top/Article/details/gtureimzcz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jianghu66.top/Article/details/gtucvpqcyt.html

[R73] 分割大日志
来源：http://dali.zhoulong.xyz/Article/details/gtjgufeonl.html

split -l 1000 big.log part_
来源：http://dali.redwolf501.top/Article/details/gtvxgmytdy.html

[R74] 批量重命名
来源：http://dali.xuetiantiany.cn/Article/details/gtkcldegvx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cdnleiting.top/Article/details/gtkqgkkxes.html

[R75] 导出环境变量
来源：http://dali.yueranfly.top/Article/details/gtepepuywb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yangfankeji.com/Article/details/gtrjvhdypp.html

[R76] 使用临时文件
来源：http://dali.zhengqikj.top/Article/details/gtzuxxxphs.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhoulong.xyz/Article/details/gtphiuozki.html

[R77] 读取用户输入
来源：http://dali.ehwqpu.com/Article/details/gthmsogtqt.html

read -rp "请输入: " ans
来源：http://dali.shuidangran.top/Article/details/gtgxrvcvpe.html

[R78] 交互式菜单
来源：http://dali.ppjwa.cn/Article/details/gtohgibgsz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.9152youxi.cn/Article/details/gtimjnlmwr.html

[R79] 解析命令行选项
来源：http://dali.tianlin.xyz/Article/details/gtjpslbpxh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ivvv.top/Article/details/gtvigyniun.html

[R80] 查看脚本执行耗时
来源：http://dali.yuxming.cn/Article/details/gtolpwnrje.html

time ./run.sh
来源：http://dali.tianlin.xyz/Article/details/gtomycrrnz.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gttddupfnq.html

S. C / C++ 专题
来源：http://dali.yanxiufei.cn/Article/details/gtyjoyrwzp.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtkdcyzaql.html

[S01] C：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtkgekxced.html

#include <stdio.h>
来源：http://dali.kuanghao11.cn/Article/details/gtceoonxte.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.quarkkingdee.top/Article/details/gtjzlfmjro.html

[S02] C：变量与格式化输出
来源：http://dali.quarkkingdee.top/Article/details/gtlgvcvsfe.html

int a = 10; printf("%d\n", a);
来源：http://dali.kuanghao11.cn/Article/details/gtpnysbsom.html

[S03] C：读入整数
来源：http://dali.hysaishi.cn/Article/details/gtokajvofi.html

int x; scanf("%d", &x);
来源：http://dali.hfpthk.cn/Article/details/gtenxywkmb.html

[S04] C：字符串复制
来源：http://dali.jiagoushi.top/Article/details/gtxjcvsnrn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jlsjyb.cn/Article/details/gtujdtmkgr.html

[S05] C：字符串长度
来源：http://dali.tianlin.xyz/Article/details/gtlnlftkmn.html

strlen(s)
来源：http://dali.gogol.net.cn/Article/details/gtgkddjqdc.html

[S06] C：字符串比较
来源：http://dali.haohaochexian.top/Article/details/gtovdbcfsy.html

strcmp(a, b) == 0
来源：http://dali.yuanzhike.top/Article/details/gtjqnobfgc.html

[S07] C：数组遍历求和
来源：http://dali.aizwys.cn/Article/details/gtwbntpcfa.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jqgufenzy.top/Article/details/gtzxiuxvcj.html

[S08] C：动态内存分配与释放
来源：http://dali.sufxvd.cn/Article/details/gtvoblhnve.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhiwuduotai.top/Article/details/gtciordjgm.html

[S09] C：结构体定义与初始化
来源：http://dali.jiagoushi.top/Article/details/gtaerzvyit.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xuanzx.com/Article/details/gtkzkmclmy.html

[S10] C：指针与解引用
来源：http://dali.jinghuilouyu.cn/Article/details/gtjjihuoti.html

int *p = &a;  *p = 5;
来源：http://dali.hnxiangtu.top/Article/details/gtzwigzcdk.html

[S11] C：逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gtmblsbiss.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj20258.top/Article/details/gthmcjzhlf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hnxiangtu.top/Article/details/gtykhatyjl.html

fclose(f);
来源：http://dali.jianghu66.top/Article/details/gthmzqddpa.html

[S12] C：写文件
来源：http://dali.yongpay.top/Article/details/gtoafwyosw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.haohaochexian.top/Article/details/gtyioxbctm.html

[S13] C：宏定义
来源：http://dali.birdmap.top/Article/details/gtptwggrhs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ivvv.top/Article/details/gtrzdwcinh.html

[S14] C：枚举
来源：http://dali.wangshuangyany.cn/Article/details/gtzrllkswd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gtaidsdtew.html

[S15] C：类型转换
来源：http://dali.zhiwuduotai.top/Article/details/gtonptfdmr.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gtjxuskakz.html

[S16] C：位操作置位
来源：http://dali.mhx1999.top/Article/details/gtpbpboxmv.html

x |= (1 << 3);
来源：http://dali.9152youxi.cn/Article/details/gtwfzznods.html

[S17] C：安全拼接字符串
来源：http://dali.bjfxy.top/Article/details/gtytzuwcbt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yj202588.top/Article/details/gtxtmvstus.html

[S18] C：命令行参数
来源：http://dali.gogol.net.cn/Article/details/gtvykyjgqh.html

int main(int argc, char **argv)
来源：http://dali.cqqwz.cn/Article/details/gtpwqochau.html

[S19] C：快速排序
来源：http://dali.c1oappe.top/Article/details/gtdpgbluev.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gtlyuqynyq.html

[S20] C：二分查找
来源：http://dali.jinqigufen.top/Article/details/gtwsdxpqgy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.kuanghao11.cn/Article/details/gttawvycfi.html

[S21] C：字符类别判断
来源：http://dali.gotoacloud.top/Article/details/gtzksozymr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xuanzx.com/Article/details/gtsimmqqdo.html

[S22] C：字符串转数字
来源：http://dali.aizwys.cn/Article/details/gtjoomclib.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.meibo888.top/Article/details/gtkhsdtbww.html

[S23] C：随机数
来源：http://dali.haohaochexian.top/Article/details/gtuxvmbfdo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.smart0.xyz/Article/details/gtrpgolgmk.html

[S24] C：获取本地时间
来源：http://dali.snrcjt.cn/Article/details/gtjuwfoonl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shanyushiyangtech.top/Article/details/gtpqtaupck.html

[S25] C：内存拷贝
来源：http://dali.nanxuanxn.top/Article/details/gtupwuakuf.html

memcpy(dst, src, n);
来源：http://dali.cheryme.top/Article/details/gtplolbpoo.html

[S26] C：内存清零
来源：http://dali.quarkkingdee.top/Article/details/gtrtahvare.html

memset(a, 0, sizeof a);
来源：http://dali.redwolf501.top/Article/details/gtfrpnvise.html

[S27] C：定义常量
来源：http://dali.sxryk.cn/Article/details/gtlmlpwkhg.html

const double PI = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gthvolavvd.html

[S28] C：静态变量
来源：http://dali.hfpthk.cn/Article/details/gtdlfjtnku.html

static int counter = 0;
来源：http://dali.feifeiyinyue.top/Article/details/gtylfjmtbh.html

[S29] C：变参函数
来源：http://dali.jinqigufen.top/Article/details/gtrrglsnom.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yangfankeji.com/Article/details/gtrkrkyblb.html

[S30] C：头文件保护
来源：http://dali.hammf.cn/Article/details/gtikonmllp.html

#ifndef X_H
来源：http://dali.yongpay.top/Article/details/gtnenuahcz.html

#define X_H
来源：http://dali.hammf.cn/Article/details/gtdqvkljae.html

#endif
来源：http://dali.shanyushiyangtech.top/Article/details/gtnhaupuus.html

[S31] C++：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtctsqlcjl.html

#include <iostream>
来源：http://dali.jqgfzy.top/Article/details/gtuzbnucgt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cheryme.top/Article/details/gtyiuqeitx.html

[S32] C++：字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtdzsejpjp.html

std::string s = "hi";  s += "!";
来源：http://dali.iojbl.cn/Article/details/gtuuyecwzk.html

[S33] C++：vector 增删
来源：http://dali.dianchejie.cn/Article/details/gtelqqnxah.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tian-w.cn/Article/details/gtsmxbgian.html

[S34] C++：遍历 vector
来源：http://dali.bjfxy.top/Article/details/gtdavmyxwh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hysaishi.cn/Article/details/gtxkqhafcy.html

[S35] C++：map
来源：http://dali.haohaochexian.top/Article/details/gtuurufsfw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258.top/Article/details/gthloyyinx.html

[S36] C++：unordered_map
来源：http://dali.svipenyu.cn/Article/details/gttqwfvocl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtzrotfeab.html

[S37] C++：set
来源：http://dali.pengpengdd.cyou/Article/details/gtetqwabfl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cucudq.cn/Article/details/gtttfgwdhz.html

[S38] C++：排序
来源：http://dali.snrcjt.cn/Article/details/gtwejvguhq.html

std::sort(v.begin(), v.end());
来源：http://dali.zhengqikj.top/Article/details/gteozfgaza.html

[S39] C++：自定义比较器排序
来源：http://dali.jianghu66.top/Article/details/gtgqwvjcnp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zycfv.cn/Article/details/gtqccaxfxg.html

[S40] C++：查找元素
来源：http://dali.yanxiufei.cn/Article/details/gtbukeeuna.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.c1oappe.top/Article/details/gteeyfdmnj.html

[S41] C++：类与构造函数
来源：http://dali.bjfxy.top/Article/details/gtfeuhfzbp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nanxuanxn.top/Article/details/gtldgidlmi.html

[S42] C++：继承与虚函数
来源：http://dali.tian-w.cn/Article/details/gtenutoavh.html

class B : public Base { public: void f() override {} };
来源：http://dali.cucudq.cn/Article/details/gtnlcczmym.html

[S43] C++：智能指针
来源：http://dali.nanxinkj.top/Article/details/gtwahpqkfw.html

auto p = std::make_unique<int>(5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbavtkgsj.html

[S44] C++：引用传参
来源：http://dali.kuanghao11.cn/Article/details/gtmyytvbfs.html

void inc(int &x) { ++x; }
来源：http://dali.9152youxi.cn/Article/details/gtxbuyvngx.html

[S45] C++：lambda
来源：http://dali.guowangkeji.top/Article/details/gtyjlpfydk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jyoumei.cn/Article/details/gtvjakeftt.html

[S46] C++：函数模板
来源：http://dali.hysaishi.cn/Article/details/gttppzlwjp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shuidangran.top/Article/details/gtlxtgcfet.html

[S47] C++：结构化绑定遍历
来源：http://dali.daxiang520.top/Article/details/gtwrilcoav.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.haohaochexian.top/Article/details/gtztdxuaco.html

[S48] C++：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gtacvjzevg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.pycfn.com/Article/details/gtvzhoqver.html

while (std::getline(in, line)) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsuhuajvp.html

[S49] C++：写文件
来源：http://dali.cdnleiting.top/Article/details/gttygbuqkt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shangyingyoupin.top/Article/details/gtsvahhrnc.html

[S50] C++：格式化数字
来源：http://dali.c1oappe.top/Article/details/gtuogrrynz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yvedp.cn/Article/details/gtpjdkizqr.html

[S51] C++：显式类型转换
来源：http://dali.ehwqpu.com/Article/details/gtokdjbiok.html

static_cast<double>(a) / b
来源：http://dali.kuanghao11.cn/Article/details/gtjuqcvjgq.html

[S52] C++：const 与 noexcept
来源：http://dali.ybcxt.top/Article/details/gthmbuoqgn.html

int size() const noexcept { return n_; }
来源：http://dali.jqgfzy.top/Article/details/gtlepjdnpa.html

[S53] C++：移动语义
来源：http://dali.hywenlv.cn/Article/details/gthgobzoaf.html

std::vector<int> w = std::move(v);
来源：http://dali.xylfe.cn/Article/details/gtqealvvgi.html

[S54] C++：异常处理
来源：http://dali.tanke756.top/Article/details/gtjxvhpogf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.wangshuangyany.cn/Article/details/gtafjqwitj.html

[S55] C++：结构化绑定
来源：http://dali.xziqi.cn/Article/details/gthulcqhka.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cashguo.top/Article/details/gtcqdtrsfu.html

[S56] C++：optional
来源：http://dali.zhiwuduotai.top/Article/details/gtnqrjkheg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.birdmap.top/Article/details/gtqwuncdym.html

[S57] C++：编译期常量
来源：http://dali.gzhubu.top/Article/details/gtfvzyiqnv.html

constexpr int N = 10;
来源：http://dali.iojbl.cn/Article/details/gtfzpjlxfg.html

[S58] C++：命名空间
来源：http://dali.xuetiantiany.cn/Article/details/gtekbcnqtn.html

namespace ns { int f() { return 1; } }
来源：http://dali.jianghu66.top/Article/details/gtxeynoczg.html

[S59] C++：静态断言
来源：http://dali.ybcxt.top/Article/details/gtkhbktmmt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xziqi.cn/Article/details/gtmjuzydin.html

[S60] C++：遍历并删除元素
来源：http://dali.cdnleiting.top/Article/details/gtwijqzscf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nwbrower.top/Article/details/gtrgmffhds.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtmyeusclf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.vqdsnc.cn/Article/details/gtwbojsfhs.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtoubwjqsi.html

[T01] Kotlin：Hello World
来源：http://dali.fzhhl.top/Article/details/gtwytubtzi.html

println("Hello")
来源：http://dali.sxryk.cn/Article/details/gtmdarqcrr.html

[T02] Kotlin：变量
来源：http://dali.cqqwz.cn/Article/details/gtvedopfub.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.snrcjt.cn/Article/details/gtfvyiwfiz.html

[T03] Kotlin：字符串模板
来源：http://dali.wangdashe.top/Article/details/gtfhprccef.html

"值: $b"
来源：http://dali.c1oappe.top/Article/details/gtumpkgvzo.html

[T04] Kotlin：空安全
来源：http://dali.xziqi.cn/Article/details/gtfrydoqgo.html

val n: String? = null;  n?.length
来源：http://dali.feifeiyinyue.top/Article/details/gtjoqnyaow.html

[T05] Kotlin：when 表达式
来源：http://dali.tanke756.top/Article/details/gtupsbmvii.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhengqikj.top/Article/details/gtzfpsppjg.html

[T06] Kotlin：集合映射
来源：http://dali.wangdashe.top/Article/details/gtmiytvjtc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ivvv.top/Article/details/gtpdbronmr.html

[T07] Kotlin：集合过滤
来源：http://dali.gzhubu.top/Article/details/gteloxddiv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuanzhike.top/Article/details/gtcvdqqsqq.html

[T08] Kotlin：数据类
来源：http://dali.ppjwa.cn/Article/details/gtkmtjujjo.html

data class User(val name: String, val age: Int)
来源：http://dali.tanke756.top/Article/details/gtuslliwsn.html

[T09] Kotlin：扩展函数
来源：http://dali.yueranfly.top/Article/details/gtpmuknmsq.html

fun String.exclaim() = this + "!"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzabmdumz.html

[T10] Kotlin：默认参数
来源：http://dali.jianghu66.top/Article/details/gtmtjjwnxf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj20258888.top/Article/details/gtpnaoyojj.html

[T11] Kotlin：协程
来源：http://dali.yj202588.top/Article/details/gtddesdbix.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hongshengwenyu.top/Article/details/gtnlibatnl.html

[T12] Kotlin：解构声明
来源：http://dali.quarkkingdee.top/Article/details/gtgkpbcudh.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenlongwang.top/Article/details/gtleijnvsz.html

[T13] Kotlin：只读 Map
来源：http://dali.guannengcc.top/Article/details/gtstckgqoc.html

val m = mapOf("a" to 1)
来源：http://dali.jqgufenzy.top/Article/details/gtndygliqe.html

[T14] Kotlin：循环
来源：http://dali.tian-w.cn/Article/details/gtnityqzkn.html

for (i in 1..10) println(i)
来源：http://dali.yj20258.top/Article/details/gtapzqhmuf.html

[T15] Kotlin：接口
来源：http://dali.jqgfzy.top/Article/details/gtrpbjlwwc.html

interface Shape { fun area(): Double }
来源：http://dali.jinghuilouyu.cn/Article/details/gtoyajwwml.html

[T16] Swift：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtvwekxtdq.html

print("Hello")
来源：http://dali.yongpay.top/Article/details/gttdbgswmx.html

[T17] Swift：变量与常量
来源：http://dali.jianghu66.top/Article/details/gtpovdgclb.html

var a = 1;  let b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gtdbnabmcf.html

[T18] Swift：字符串插值
来源：http://dali.tian-w.cn/Article/details/gtjsqcdtus.html

"值: \(b)"
来源：http://dali.yj202588.top/Article/details/gtqyymdemp.html

[T19] Swift：可选绑定
来源：http://dali.aibaodan.cn/Article/details/gtbzdvvnmh.html

if let n = opt { print(n) }
来源：http://dali.redwolf501.top/Article/details/gtchpdacsc.html

[T20] Swift：数组操作
来源：http://dali.tianlin.xyz/Article/details/gtgtvrwvju.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gtjttyingt.html

[T21] Swift：遍历
来源：http://dali.0kj1m.cn/Article/details/gtutnmrolh.html

for x in a { print(x) }
来源：http://dali.pengpengdd.cyou/Article/details/gtpfmkcswo.html

[T22] Swift：字典
来源：http://dali.jinqigfzy.top/Article/details/gtqubgicso.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhoulong.xyz/Article/details/gtukuzeszm.html

[T23] Swift：函数
来源：http://dali.jqgfzy.top/Article/details/gtmcteqgbu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzlgrbfel.html

[T24] Swift：闭包
来源：http://dali.sweek.top/Article/details/gtclwfbmdf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.andypj.xyz/Article/details/gtgctqapog.html

[T25] Swift：结构体
来源：http://dali.yvedp.cn/Article/details/gtcitxgkij.html

struct P { var x: Int }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwzdsnwpf.html

[T26] Swift：类与重写
来源：http://dali.0kj1m.cn/Article/details/gtbbkrdcwj.html

class A: Base { override func f() {} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbbkgqvcf.html

[T27] Swift：错误处理
来源：http://dali.chenlongwang.top/Article/details/gtswmoqebk.html

do { try f() } catch { print(error) }
来源：http://dali.gogol.net.cn/Article/details/gtxrvtoejl.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gtnpzjzxvj.html

enum Color { case red, green }
来源：http://dali.daria6918.cn/Article/details/gtjdltipyo.html

[T29] Swift：guard 提前返回
来源：http://dali.hnxiangtu.top/Article/details/gtqnejceip.html

guard let x = opt else { return }
来源：http://dali.sxryk.cn/Article/details/gtqarchzbf.html

[T30] Swift：协议
来源：http://dali.yvedp.cn/Article/details/gthnzhkpyi.html

protocol Shape { func area() -> Double }
来源：http://dali.cashguo.top/Article/details/gtbjzmraru.html

[T31] Lua：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtvxkuhydv.html

print("Hello")
来源：http://dali.iojbl.cn/Article/details/gtlgtxvatk.html

[T32] Lua：局部变量
来源：http://dali.yj202588.top/Article/details/gtidnvqzes.html

local a = 1
来源：http://dali.hnqzz.top/Article/details/gtkvlcwdid.html

[T33] Lua：表（数组）
来源：http://dali.zhixingplan.top/Article/details/gtgejvdvei.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hammf.cn/Article/details/gtelsuvsbb.html

[T34] Lua：遍历表
来源：http://dali.zhongyouzk.top/Article/details/gtjmyyctss.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shzxlz.cn/Article/details/gtpuykltrj.html

[T35] Lua：字典表
来源：http://dali.fzhhl.top/Article/details/gtxltqttka.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ehwqpu.com/Article/details/gtosacgpiu.html

[T36] Lua：函数
来源：http://dali.mhx1999.top/Article/details/gtuartqtes.html

function add(a, b) return a + b end
来源：http://dali.yj202588.top/Article/details/gtxddjkzik.html

[T37] Lua：字符串拼接
来源：http://dali.mhx1999.top/Article/details/gtxrtlmejz.html

"a" .. "b"
来源：http://dali.yvedp.cn/Article/details/gtvrwvsjro.html

[T38] Lua：条件
来源：http://dali.shangyingyoupin.top/Article/details/gtgoqhhgwf.html

if x > 0 then print("正") end
来源：http://dali.redwolf501.top/Article/details/gtzfaikthp.html

[T39] Lua：模式匹配
来源：http://dali.gzhubu.top/Article/details/gtdccvfzmo.html

string.find(s, "%d+")
来源：http://dali.birdmap.top/Article/details/gtbnntjtez.html

[T40] Lua：元表
来源：http://dali.ybcxt.top/Article/details/gtnpdvahlx.html

setmetatable({}, { __index = base })
来源：http://dali.aibaodan.cn/Article/details/gttssbukgf.html

[T41] Perl：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtacdtgvsp.html

print "Hello\n";
来源：http://dali.zhixingplan.top/Article/details/gtiyxppaav.html

[T42] Perl：变量类型
来源：http://dali.ybcxt.top/Article/details/gtfjepeyjl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gotoacloud.top/Article/details/gtdweonhdk.html

[T43] Perl：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gtvactgtny.html

"值: $a"
来源：http://dali.ivvv.top/Article/details/gtrhxdkdew.html

[T44] Perl：条件
来源：http://dali.jinqigfzy.top/Article/details/gtjueemptp.html

if ($a > 0) { print "正"; }
来源：http://dali.jianghu66.top/Article/details/gteijqdmil.html

[T45] Perl：数组遍历
来源：http://dali.sxryk.cn/Article/details/gtrvqrbvik.html

for my $x (@arr) { print $x; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqwkaksfo.html

[T46] Perl：哈希操作
来源：http://dali.hfpthk.cn/Article/details/gtcbdsccsu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.nanxinkj.top/Article/details/gtsroeqljd.html

[T47] Perl：正则捕获
来源：http://dali.jinqigufen.top/Article/details/gtddgqkxfy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ppjwa.cn/Article/details/gtoksaaeej.html

[T48] Perl：正则替换
来源：http://dali.gaohongyu789.top/Article/details/gtjdndpzvb.html

$s =~ s/old/new/g;
来源：http://dali.birdmap.top/Article/details/gtibmxghzb.html

[T49] Perl：函数
来源：http://dali.pengpengdd.cyou/Article/details/gtgngomzng.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtwibkzcsl.html

[T50] Perl：逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gtxwfzfqjc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.fzhhl.top/Article/details/gtnurrsagv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.svipenyu.cn/Article/details/gtbudkpoak.html

[T51] Scala：Hello World
来源：http://dali.redwolf501.top/Article/details/gtnshbroei.html

println("Hello")
来源：http://dali.yj20258.top/Article/details/gtpfkxdsci.html

[T52] Scala：变量
来源：http://dali.hnxiangtu.top/Article/details/gtugwznwru.html

val a = 1;  var b = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfmobjmp.html

[T53] Scala：字符串插值
来源：http://dali.sxryk.cn/Article/details/gtjdthcptn.html

s"值: $b"
来源：http://dali.cheryme.top/Article/details/gtnbzqrqub.html

[T54] Scala：集合映射
来源：http://dali.bjfxy.top/Article/details/gthmfhzjxv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.quarkkingdee.top/Article/details/gtpqznmdsg.html

[T55] Scala：集合过滤
来源：http://dali.cqqwz.cn/Article/details/gtbwyhfiel.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhoulong.xyz/Article/details/gtxoiammhb.html

[T56] Scala：样例类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcbnobqmh.html

case class User(name: String, age: Int)
来源：http://dali.meibo888.top/Article/details/gtokezqkdy.html

[T57] Scala：模式匹配
来源：http://dali.yanxiufei.cn/Article/details/gtgrfllugu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.mhx1999.top/Article/details/gtmucdorab.html

[T58] Scala：函数定义
来源：http://dali.havefunace.top/Article/details/gtdarppoxg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhoulong.xyz/Article/details/gtflammgva.html

[T59] Scala：循环
来源：http://dali.redwolf501.top/Article/details/gtbmzslkfa.html

for (i <- 1 to 10) println(i)
来源：http://dali.ehwqpu.com/Article/details/gtgrusorgq.html

[T60] Scala：折叠
来源：http://dali.shzxlz.cn/Article/details/gtcfqngvmm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.snrcjt.cn/Article/details/gtircmbggi.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtunwctdvx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.fzhhl.top/Article/details/gtnpezdkwc.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtojlxhjmd.html

[U01] Py：创建虚拟环境
来源：http://dali.meibo888.top/Article/details/gtgcyuocbo.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hfpthk.cn/Article/details/gtgkpllpoa.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shzxlz.cn/Article/details/gtvcvvjccf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xylfe.cn/Article/details/gtitcofijw.html

[U03] Py：加载 .env 配置
来源：http://dali.svipenyu.cn/Article/details/gtxbgzkady.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yanxiufei.cn/Article/details/gtetlbddyt.html

[U04] Py：变量调试打印
来源：http://dali.xylfe.cn/Article/details/gtraafxiae.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhongyouzk.top/Article/details/gtftusoanl.html

[U05] Py：列表去重且保序
来源：http://dali.guannengcc.top/Article/details/gtvhqsuokg.html

list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gtvkclwpwo.html

[U06] Py：合并两个字典
来源：http://dali.yvedp.cn/Article/details/gtmivubamq.html

{**a, **b}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvzztjbo.html

[U07] Py：反转字典键值
来源：http://dali.ydzc1.top/Article/details/gtzidkgoii.html

{v: k for k, v in d.items()}
来源：http://dali.zycfv.cn/Article/details/gtmamrylpy.html

[U08] Py：展平二维列表
来源：http://dali.andypj.xyz/Article/details/gtozkzkuxk.html

[y for x in nested for y in x]
来源：http://dali.aizwys.cn/Article/details/gtqpfwbvoa.html

[U09] Py：字典取最大值的键
来源：http://dali.bjfxy.top/Article/details/gthxdmkxpz.html

max(d, key=d.get)
来源：http://dali.wangshuangyany.cn/Article/details/gtexanxbtd.html

[U10] Py：按值排序字典
来源：http://dali.hnxiangtu.top/Article/details/gtbenvdomi.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.vqdsnc.cn/Article/details/gtcbmihshs.html

[U11] Py：生成器表达式
来源：http://dali.cheryme.top/Article/details/gtnpsustea.html

(x * 2 for x in arr)
来源：http://dali.kuanghao11.cn/Article/details/gtgqespiwt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.tian-w.cn/Article/details/gtinloysjb.html

Counter(arr).most_common(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtwzhuzalb.html


<!-- 参考信息 -->