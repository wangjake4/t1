代发 wailian999

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.vqdsnc.cn/Article/details/gtocqrimdq.html

[R72] 等待端口就绪
来源：http://dali.xziqi.cn/Article/details/gtfnmeouzm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhoulong.xyz/Article/details/gtiskxdknr.html

[R73] 分割大日志
来源：http://dali.kuanghao11.cn/Article/details/gttkbzvqwk.html

split -l 1000 big.log part_
来源：http://dali.cdnleiting.top/Article/details/gtugwpmzra.html

[R74] 批量重命名
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqghhwdsy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hammf.cn/Article/details/gtjnuntxyx.html

[R75] 导出环境变量
来源：http://dali.xuetiantiany.cn/Article/details/gtoothnqik.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinghuilouyu.cn/Article/details/gtlwwfhrxw.html

[R76] 使用临时文件
来源：http://dali.yangfankeji.com/Article/details/gtemcsmxmz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.kuanghao11.cn/Article/details/gtbeameljn.html

[R77] 读取用户输入
来源：http://dali.cqqwz.cn/Article/details/gtabgapdwn.html

read -rp "请输入: " ans
来源：http://dali.9152youxi.cn/Article/details/gtbgkvenqg.html

[R78] 交互式菜单
来源：http://dali.gotoacloud.top/Article/details/gtiemsnizl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.pengpengdd.cyou/Article/details/gtoejjwfoh.html

[R79] 解析命令行选项
来源：http://dali.chenzaomai.com/Article/details/gttdlmbzkx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.pengpengdd.cyou/Article/details/gtdjuafpds.html

[R80] 查看脚本执行耗时
来源：http://dali.pycfn.com/Article/details/gtqxcuvlgf.html

time ./run.sh
来源：http://dali.gogol.net.cn/Article/details/gtzcwwyspq.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtownwwvpn.html

S. C / C++ 专题
来源：http://dali.jlsjyb.cn/Article/details/gtgwesajer.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtaamzwrav.html

[S01] C：Hello World
来源：http://dali.cashguo.top/Article/details/gtfyqrsnrk.html

#include <stdio.h>
来源：http://dali.meibo888.top/Article/details/gteyvavejj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hongshengwenyu.top/Article/details/gtjwcsjtun.html

[S02] C：变量与格式化输出
来源：http://dali.andypj.xyz/Article/details/gtzxedffev.html

int a = 10; printf("%d\n", a);
来源：http://dali.c1oappe.top/Article/details/gtstggoimy.html

[S03] C：读入整数
来源：http://dali.sweek.top/Article/details/gtvwngvdfg.html

int x; scanf("%d", &x);
来源：http://dali.nanxinkj.top/Article/details/gtszxolcyx.html

[S04] C：字符串复制
来源：http://dali.aizwys.cn/Article/details/gtbvrikylr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jqgufenzy.top/Article/details/gtufzbikjl.html

[S05] C：字符串长度
来源：http://dali.gaohongyu789.top/Article/details/gtabinjuzh.html

strlen(s)
来源：http://dali.iojbl.cn/Article/details/gtgagzdvkm.html

[S06] C：字符串比较
来源：http://dali.smart0.xyz/Article/details/gtplcjcjoa.html

strcmp(a, b) == 0
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrhzwvorq.html

[S07] C：数组遍历求和
来源：http://dali.zhiwuduotai.top/Article/details/gtbebrgxmi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jqgfzy.top/Article/details/gtsvsehlfa.html

[S08] C：动态内存分配与释放
来源：http://dali.ywan-chungtsiang.top/Article/details/gttrqjyjkg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yangfankeji.com/Article/details/gtsumdkmjx.html

[S09] C：结构体定义与初始化
来源：http://dali.hnqzz.top/Article/details/gtaplxhvgf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shangyingyoupin.top/Article/details/gttrcnctqe.html

[S10] C：指针与解引用
来源：http://dali.feifeiyinyue.top/Article/details/gthxzzmfpm.html

int *p = &a;  *p = 5;
来源：http://dali.nanxinkj.top/Article/details/gtlsuqniqb.html

[S11] C：逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gtydwqelas.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jqgfzy.top/Article/details/gthtueilqd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.iojbl.cn/Article/details/gtauxdlhsj.html

fclose(f);
来源：http://dali.guannengcc.top/Article/details/gtqsddgmfw.html

[S12] C：写文件
来源：http://dali.chenjidiqi.icu/Article/details/gtczpahmaz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nanxuanxn.top/Article/details/gtgqchgqyp.html

[S13] C：宏定义
来源：http://dali.guowangkeji.top/Article/details/gtgzluzkyg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.c1oappe.top/Article/details/gtgphcvsyq.html

[S14] C：枚举
来源：http://dali.jinqigfzy.top/Article/details/gtovfneyts.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sweek.top/Article/details/gtabjqqnqa.html

[S15] C：类型转换
来源：http://dali.jlsjyb.cn/Article/details/gtlqoybrui.html

(double) a / b
来源：http://dali.jinqigfzy.top/Article/details/gtpaoustzj.html

[S16] C：位操作置位
来源：http://dali.birdmap.top/Article/details/gtbembirux.html

x |= (1 << 3);
来源：http://dali.chenlongwang.top/Article/details/gtebassmfm.html

[S17] C：安全拼接字符串
来源：http://dali.c1oappe.top/Article/details/gtfcjlgmkl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nanxuanxn.top/Article/details/gtgjkeziab.html

[S18] C：命令行参数
来源：http://dali.sysykeji.top/Article/details/gtoqbzhfri.html

int main(int argc, char **argv)
来源：http://dali.snrcjt.cn/Article/details/gtphhmipja.html

[S19] C：快速排序
来源：http://dali.ydzc1.top/Article/details/gtdoqvnbck.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.guannengcc.top/Article/details/gtzqwjkskd.html

[S20] C：二分查找
来源：http://dali.ehwqpu.com/Article/details/gtihvdecwl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cqqwz.cn/Article/details/gtkysshfxx.html

[S21] C：字符类别判断
来源：http://dali.nwbrower.top/Article/details/gtylfcovxw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nanxuanxn.top/Article/details/gtapdzfnxe.html

[S22] C：字符串转数字
来源：http://dali.hnqzz.top/Article/details/gtcjtrnexp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.316326.xyz/Article/details/gtgyxuqpos.html

[S23] C：随机数
来源：http://dali.pengpengdd.cyou/Article/details/gtlbyagdwk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.daria6918.cn/Article/details/gtnvujewev.html

[S24] C：获取本地时间
来源：http://dali.shanyushiyangtech.top/Article/details/gtynhwevkx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.aibaodan.cn/Article/details/gtdjpbzheu.html

[S25] C：内存拷贝
来源：http://dali.jqgfzy.top/Article/details/gtvswhirqz.html

memcpy(dst, src, n);
来源：http://dali.shzxlz.cn/Article/details/gtyqpyznph.html

[S26] C：内存清零
来源：http://dali.yueranfly.top/Article/details/gtyaghucgg.html

memset(a, 0, sizeof a);
来源：http://dali.zhoulong.xyz/Article/details/gtsayyrrir.html

[S27] C：定义常量
来源：http://dali.vqdsnc.cn/Article/details/gtlqdvtuoj.html

const double PI = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnrgbewcw.html

[S28] C：静态变量
来源：http://dali.tian-w.cn/Article/details/gtmkfaqlfw.html

static int counter = 0;
来源：http://dali.hfpthk.cn/Article/details/gtzleogsiv.html

[S29] C：变参函数
来源：http://dali.smart0.xyz/Article/details/gtukqwfnfk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hammf.cn/Article/details/gtcrfondfr.html

[S30] C：头文件保护
来源：http://dali.jianghu66.top/Article/details/gtjguticqe.html

#ifndef X_H
来源：http://dali.yuanzhike.top/Article/details/gtsfwjxnma.html

#define X_H
来源：http://dali.hnqzz.top/Article/details/gtijcmkfgn.html

#endif
来源：http://dali.shanyushiyangtech.top/Article/details/gtzqnfnpdm.html

[S31] C++：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtoxvwjtyu.html

#include <iostream>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjndgvtnf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhixingplan.top/Article/details/gtpmzytqhs.html

[S32] C++：字符串
来源：http://dali.zhixingplan.top/Article/details/gtnkqitxjr.html

std::string s = "hi";  s += "!";
来源：http://dali.sysykeji.top/Article/details/gtjbcldwkt.html

[S33] C++：vector 增删
来源：http://dali.zhongyouzk.top/Article/details/gtrhsnvezp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jiagoushi.top/Article/details/gttueufkpx.html

[S34] C++：遍历 vector
来源：http://dali.zhixingplan.top/Article/details/gtiohpupan.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtszhblawz.html

[S35] C++：map
来源：http://dali.shangyingyoupin.top/Article/details/gtviayhooi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtouhuofsw.html

[S36] C++：unordered_map
来源：http://dali.meibo888.top/Article/details/gthpciqnla.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fzhhl.top/Article/details/gtkzlbfkee.html

[S37] C++：set
来源：http://dali.yonumen.top/Article/details/gtkcybthry.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.havefunace.top/Article/details/gtgjxyvuzq.html

[S38] C++：排序
来源：http://dali.aizwys.cn/Article/details/gtmimyqyyk.html

std::sort(v.begin(), v.end());
来源：http://dali.aizwys.cn/Article/details/gtslshlgkx.html

[S39] C++：自定义比较器排序
来源：http://dali.pycfn.com/Article/details/gtfhcwmiwc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkbocetpn.html

[S40] C++：查找元素
来源：http://dali.yangfankeji.com/Article/details/gtspmbbvub.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shzxlz.cn/Article/details/gthryswrti.html

[S41] C++：类与构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtosbtpzyp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sweek.top/Article/details/gtwzhcvomo.html

[S42] C++：继承与虚函数
来源：http://dali.316326.xyz/Article/details/gtcbeffkcz.html

class B : public Base { public: void f() override {} };
来源：http://dali.shangyingyoupin.top/Article/details/gtxchoubmx.html

[S43] C++：智能指针
来源：http://dali.hongshengwenyu.top/Article/details/gtxvgafmbw.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinqigfzy.top/Article/details/gtiuswcmfi.html

[S44] C++：引用传参
来源：http://dali.shangyingyoupin.top/Article/details/gtfwxcwvmo.html

void inc(int &x) { ++x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthzzuxxck.html

[S45] C++：lambda
来源：http://dali.shangyingyoupin.top/Article/details/gtvegoxfot.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdfmrftmb.html

[S46] C++：函数模板
来源：http://dali.gotoacloud.top/Article/details/gtflziawrb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.bjfxy.top/Article/details/gtnoakcebo.html

[S47] C++：结构化绑定遍历
来源：http://dali.wangdashe.top/Article/details/gtxagqjstv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.aibaodan.cn/Article/details/gtpgxnrrla.html

[S48] C++：逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gtgtbkrmuh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sxryk.cn/Article/details/gtukenaljk.html

while (std::getline(in, line)) { }
来源：http://dali.dianchejie.cn/Article/details/gtviktywqx.html

[S49] C++：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsundkyjv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.chenjidiqi.icu/Article/details/gthfylkwjb.html

[S50] C++：格式化数字
来源：http://dali.pengpengdd.cyou/Article/details/gtkeewiizt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gthiomvjjl.html

[S51] C++：显式类型转换
来源：http://dali.hfpthk.cn/Article/details/gtnjbppdbs.html

static_cast<double>(a) / b
来源：http://dali.hammf.cn/Article/details/gtzbskyjol.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gtkaqfoyxs.html

int size() const noexcept { return n_; }
来源：http://dali.9152youxi.cn/Article/details/gtyzclmmcr.html

[S53] C++：移动语义
来源：http://dali.xziqi.cn/Article/details/gtoiiysypo.html

std::vector<int> w = std::move(v);
来源：http://dali.cashguo.top/Article/details/gtorkczzxo.html

[S54] C++：异常处理
来源：http://dali.jinqigufen.top/Article/details/gtxlgtdeyv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xuetiantiany.cn/Article/details/gtcchxhrck.html

[S55] C++：结构化绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfpocfpyy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhengqikj.top/Article/details/gtrilqzjnq.html

[S56] C++：optional
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlntbnxlu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.pycfn.com/Article/details/gtgpktrony.html

[S57] C++：编译期常量
来源：http://dali.tianlin.xyz/Article/details/gtupveqpaq.html

constexpr int N = 10;
来源：http://dali.svipenyu.cn/Article/details/gtfqnveiln.html

[S58] C++：命名空间
来源：http://dali.xuetiantiany.cn/Article/details/gtjfrvpijp.html

namespace ns { int f() { return 1; } }
来源：http://dali.aibaodan.cn/Article/details/gtcfnaocqk.html

[S59] C++：静态断言
来源：http://dali.sysykeji.top/Article/details/gtddvfuilo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yonumen.top/Article/details/gtgragvsqk.html

[S60] C++：遍历并删除元素
来源：http://dali.svipenyu.cn/Article/details/gtwmnpjjrf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hywenlv.cn/Article/details/gtfwmvkkry.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtlalorlvc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangdashe.top/Article/details/gtwgfjlhtf.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtfldhfnwu.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtazuondfl.html

println("Hello")
来源：http://dali.zycfv.cn/Article/details/gtxhikrbkf.html

[T02] Kotlin：变量
来源：http://dali.wangshuangyany.cn/Article/details/gtscwzxmqg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xuetiantiany.cn/Article/details/gtxgtykzpi.html

[T03] Kotlin：字符串模板
来源：http://dali.0kj1m.cn/Article/details/gtkykhjpng.html

"值: $b"
来源：http://dali.guowangkeji.top/Article/details/gtabbgfavn.html

[T04] Kotlin：空安全
来源：http://dali.tanke756.top/Article/details/gtquibmnku.html

val n: String? = null;  n?.length
来源：http://dali.bjfxy.top/Article/details/gtlfksjfef.html

[T05] Kotlin：when 表达式
来源：http://dali.birdmap.top/Article/details/gtlplyigos.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.meibo888.top/Article/details/gtljegmvjg.html

[T06] Kotlin：集合映射
来源：http://dali.jinghuilouyu.cn/Article/details/gtxztzbrtz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.fengsongda.top/Article/details/gtjjfrcvhv.html

[T07] Kotlin：集合过滤
来源：http://dali.hongshengwenyu.top/Article/details/gtdfdtxkxc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jlsjyb.cn/Article/details/gtnxoxhivh.html

[T08] Kotlin：数据类
来源：http://dali.yuanzhike.top/Article/details/gtamdqbokq.html

data class User(val name: String, val age: Int)
来源：http://dali.yuanzhike.top/Article/details/gtdtgrjgpz.html

[T09] Kotlin：扩展函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gthshfrkxy.html

fun String.exclaim() = this + "!"
来源：http://dali.zdqjudy.top/Article/details/gthtzvtytm.html

[T10] Kotlin：默认参数
来源：http://dali.dianchejie.cn/Article/details/gtbyetwhoh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jqgfzy.top/Article/details/gtljtauoyn.html

[T11] Kotlin：协程
来源：http://dali.xinyue.icu/Article/details/gtmfutbvly.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhixingplan.top/Article/details/gtolywothr.html

[T12] Kotlin：解构声明
来源：http://dali.jianghu66.top/Article/details/gtnhjzjxfr.html

val (a, b) = Pair(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gtmqqapcnm.html

[T13] Kotlin：只读 Map
来源：http://dali.daxiang520.top/Article/details/gtflxzetar.html

val m = mapOf("a" to 1)
来源：http://dali.dashuyun.cn/Article/details/gtgdxszdpy.html

[T14] Kotlin：循环
来源：http://dali.tian-w.cn/Article/details/gtqflzastn.html

for (i in 1..10) println(i)
来源：http://dali.pycfn.com/Article/details/gtiuunzbsd.html

[T15] Kotlin：接口
来源：http://dali.daria6918.cn/Article/details/gtcreqccsg.html

interface Shape { fun area(): Double }
来源：http://dali.aibaodan.cn/Article/details/gtkfnvurep.html

[T16] Swift：Hello World
来源：http://dali.smart0.xyz/Article/details/gttcujnczv.html

print("Hello")
来源：http://dali.zhixingplan.top/Article/details/gtcbvyctys.html

[T17] Swift：变量与常量
来源：http://dali.yuxming.cn/Article/details/gtkpnjhsis.html

var a = 1;  let b = 2
来源：http://dali.shzxlz.cn/Article/details/gttmaqdyqe.html

[T18] Swift：字符串插值
来源：http://dali.birdmap.top/Article/details/gtcaunejoz.html

"值: \(b)"
来源：http://dali.fzhhl.top/Article/details/gtohghixru.html

[T19] Swift：可选绑定
来源：http://dali.jinqigfzy.top/Article/details/gtsokfvzak.html

if let n = opt { print(n) }
来源：http://dali.yuxming.cn/Article/details/gtuqevypal.html

[T20] Swift：数组操作
来源：http://dali.zhengqikj.top/Article/details/gtpemfyftm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nanxuanxn.top/Article/details/gtadkfjzcl.html

[T21] Swift：遍历
来源：http://dali.yonumen.top/Article/details/gtgbiolgqv.html

for x in a { print(x) }
来源：http://dali.tanke756.top/Article/details/gtxwoctuxb.html

[T22] Swift：字典
来源：http://dali.ppjwa.cn/Article/details/gtwtzkkzdu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhoulong.xyz/Article/details/gtarehjkbh.html

[T23] Swift：函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxzhvgcd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gogol.net.cn/Article/details/gtxtcyztpc.html

[T24] Swift：闭包
来源：http://dali.yangfankeji.com/Article/details/gtqdvbdmgz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.tanke756.top/Article/details/gtapnukwfa.html

[T25] Swift：结构体
来源：http://dali.jqgfzy.top/Article/details/gtftqbldde.html

struct P { var x: Int }
来源：http://dali.pengpengdd.cyou/Article/details/gteflkufaw.html

[T26] Swift：类与重写
来源：http://dali.feifeiyinyue.top/Article/details/gtqxnnmafd.html

class A: Base { override func f() {} }
来源：http://dali.tian-w.cn/Article/details/gtzslzclgm.html

[T27] Swift：错误处理
来源：http://dali.gaohongyu789.top/Article/details/gtldlceusn.html

do { try f() } catch { print(error) }
来源：http://dali.haohaochexian.top/Article/details/gtivbaymth.html

[T28] Swift：枚举
来源：http://dali.hongshengwenyu.top/Article/details/gtjtppknlq.html

enum Color { case red, green }
来源：http://dali.dashuyun.cn/Article/details/gtxestylbs.html

[T29] Swift：guard 提前返回
来源：http://dali.sxryk.cn/Article/details/gtvnmbjaqs.html

guard let x = opt else { return }
来源：http://dali.yonumen.top/Article/details/gtxgffglzv.html

[T30] Swift：协议
来源：http://dali.jyoumei.cn/Article/details/gthwevlvjb.html

protocol Shape { func area() -> Double }
来源：http://dali.redwolf501.top/Article/details/gtbpgyiegs.html

[T31] Lua：Hello World
来源：http://dali.cucudq.cn/Article/details/gtaxchvchn.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gtjyhebwsd.html

[T32] Lua：局部变量
来源：http://dali.zhiwuduotai.top/Article/details/gtxexqnbra.html

local a = 1
来源：http://dali.zycfv.cn/Article/details/gtxpqoxwsz.html

[T33] Lua：表（数组）
来源：http://dali.chenlongwang.top/Article/details/gtyvzneykh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.gzhubu.top/Article/details/gtpokvyxqz.html

[T34] Lua：遍历表
来源：http://dali.kuanghao11.cn/Article/details/gtrqirbxob.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtexphmqcu.html

[T35] Lua：字典表
来源：http://dali.jinqigufen.top/Article/details/gtdenbdjqi.html

local d = { a = 1 };  d.b = 2
来源：http://dali.chenzaomai.com/Article/details/gtihxzusjt.html

[T36] Lua：函数
来源：http://dali.ppjwa.cn/Article/details/gtedskqbyy.html

function add(a, b) return a + b end
来源：http://dali.zhiwuduotai.top/Article/details/gtphktvptc.html

[T37] Lua：字符串拼接
来源：http://dali.jiagoushi.top/Article/details/gthjkvjrvy.html

"a" .. "b"
来源：http://dali.snrcjt.cn/Article/details/gtzftdoekc.html

[T38] Lua：条件
来源：http://dali.haohaochexian.top/Article/details/gtcvotkfdg.html

if x > 0 then print("正") end
来源：http://dali.yvedp.cn/Article/details/gtdwguzlrj.html

[T39] Lua：模式匹配
来源：http://dali.pycfn.com/Article/details/gtkqtxljhe.html

string.find(s, "%d+")
来源：http://dali.yangfankeji.com/Article/details/gtxiigvgis.html

[T40] Lua：元表
来源：http://dali.xuanzx.com/Article/details/gtvnohanbl.html

setmetatable({}, { __index = base })
来源：http://dali.ivvv.top/Article/details/gtxeisuoks.html

[T41] Perl：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtlklaedtw.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gtgftqodeo.html

[T42] Perl：变量类型
来源：http://dali.hysaishi.cn/Article/details/gtmoduplld.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cdnleiting.top/Article/details/gthalsvdvk.html

[T43] Perl：字符串插值
来源：http://dali.vqdsnc.cn/Article/details/gtiqozdfrv.html

"值: $a"
来源：http://dali.jinqigufen.top/Article/details/gtabtrnevb.html

[T44] Perl：条件
来源：http://dali.svipenyu.cn/Article/details/gtvcixyblk.html

if ($a > 0) { print "正"; }
来源：http://dali.ppjwa.cn/Article/details/gteaiqbkzf.html

[T45] Perl：数组遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtskhgwutu.html

for my $x (@arr) { print $x; }
来源：http://dali.xuetiantiany.cn/Article/details/gtvnsgjgbi.html

[T46] Perl：哈希操作
来源：http://dali.ydzc1.top/Article/details/gtxkghsrld.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ivvv.top/Article/details/gtifyykmyy.html

[T47] Perl：正则捕获
来源：http://dali.shuidangran.top/Article/details/gtexhhsybn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jqgufenzy.top/Article/details/gtysqwjync.html

[T48] Perl：正则替换
来源：http://dali.aizwys.cn/Article/details/gtjbblgvbi.html

$s =~ s/old/new/g;
来源：http://dali.ybcxt.top/Article/details/gturztemgu.html

[T49] Perl：函数
来源：http://dali.zhengqikj.top/Article/details/gtycjkfecv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xuanzx.com/Article/details/gtnwpabvys.html

[T50] Perl：逐行读文件
来源：http://dali.cheryme.top/Article/details/gtzmtmsmnz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sweek.top/Article/details/gtyfucgxpm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.chenzaomai.com/Article/details/gtglzglsse.html

[T51] Scala：Hello World
来源：http://dali.yongpay.top/Article/details/gtxssoaoqf.html

println("Hello")
来源：http://dali.aibaodan.cn/Article/details/gtotysyoxu.html

[T52] Scala：变量
来源：http://dali.yueranfly.top/Article/details/gtzizrkqvw.html

val a = 1;  var b = 2
来源：http://dali.shuidangran.top/Article/details/gtixzjakrd.html

[T53] Scala：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gtmmewbmta.html

s"值: $b"
来源：http://dali.tianlin.xyz/Article/details/gtoeotpfpk.html

[T54] Scala：集合映射
来源：http://dali.cdnleiting.top/Article/details/gtkujsjsmq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yj202588.top/Article/details/gtawoykkug.html

[T55] Scala：集合过滤
来源：http://dali.chenzaomai.com/Article/details/gttznwzfmy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.dianchejie.cn/Article/details/gtzvorwurr.html

[T56] Scala：样例类
来源：http://dali.dashuyun.cn/Article/details/gtedkicjgr.html

case class User(name: String, age: Int)
来源：http://dali.tian-w.cn/Article/details/gtklttsses.html

[T57] Scala：模式匹配
来源：http://dali.vqdsnc.cn/Article/details/gtjeserqfv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cheryme.top/Article/details/gtbzzjitue.html

[T58] Scala：函数定义
来源：http://dali.chenzaomai.com/Article/details/gtcvihlidv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtccvnumqn.html

[T59] Scala：循环
来源：http://dali.dashuyun.cn/Article/details/gtmbxwtxqf.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gtycooqfqn.html

[T60] Scala：折叠
来源：http://dali.fzhhl.top/Article/details/gtgznbqyeo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.haohaochexian.top/Article/details/gtauzqwled.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyxfuvzzq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.wangdashe.top/Article/details/gtqpdfdrup.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqjzhnzi.html

[U01] Py：创建虚拟环境
来源：http://dali.birdmap.top/Article/details/gtgfnftvnl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jiagoushi.top/Article/details/gtwzhyrukw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yuxming.cn/Article/details/gtbxnvfolv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jiagoushi.top/Article/details/gtrrfavxjn.html

[U03] Py：加载 .env 配置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrjonsxud.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yueranfly.top/Article/details/gtbdakoyew.html

[U04] Py：变量调试打印
来源：http://dali.fengsongda.top/Article/details/gtxrnuhbvf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jqgfzy.top/Article/details/gtomochzkh.html

[U05] Py：列表去重且保序
来源：http://dali.jianghu66.top/Article/details/gthpfqdsln.html

list(dict.fromkeys(arr))
来源：http://dali.jinqigufen.top/Article/details/gtivnnovvd.html

[U06] Py：合并两个字典
来源：http://dali.yj20258888.top/Article/details/gthsgukdzv.html

{**a, **b}
来源：http://dali.zhiwuduotai.top/Article/details/gtcdperjlu.html

[U07] Py：反转字典键值
来源：http://dali.jqgfzy.top/Article/details/gthubiodzg.html

{v: k for k, v in d.items()}
来源：http://dali.chenjidiqi.icu/Article/details/gtcvsmpgrn.html

[U08] Py：展平二维列表
来源：http://dali.xuanzx.com/Article/details/gtqygkepoj.html

[y for x in nested for y in x]
来源：http://dali.yonumen.top/Article/details/gtlzgnncou.html

[U09] Py：字典取最大值的键
来源：http://dali.jqgfzy.top/Article/details/gtqtcreqal.html

max(d, key=d.get)
来源：http://dali.c1oappe.top/Article/details/gtqpjdndmc.html

[U10] Py：按值排序字典
来源：http://dali.zhongyouzk.top/Article/details/gtfkvdntdd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jiagoushi.top/Article/details/gtgpsvyprr.html

[U11] Py：生成器表达式
来源：http://dali.ybcxt.top/Article/details/gtgckgfkol.html

(x * 2 for x in arr)
来源：http://dali.nwbrower.top/Article/details/gtnfizrzkk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhongyouzk.top/Article/details/gtgttvmwdm.html

Counter(arr).most_common(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqzeabdyz.html


<!-- 参考信息 -->