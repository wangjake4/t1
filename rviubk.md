代发 wailian999

head -c 16 /dev/urandom | base64
来源：http://dali.jinqigufen.top/Article/details/gtxqpfntcw.html

[R70] 时间戳与互转
来源：http://dali.chenjidiqi.icu/Article/details/gtlnovqgrq.html

date +%s;  date -d @1700000000
来源：http://dali.sweek.top/Article/details/gtrfuvwfrj.html

[R71] 日期格式化
来源：http://dali.cdnleiting.top/Article/details/gttceadpeq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ybcxt.top/Article/details/gtbqrpwrta.html

[R72] 等待端口就绪
来源：http://dali.nanxinkj.top/Article/details/gtuznacank.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hysaishi.cn/Article/details/gtydgsjppd.html

[R73] 分割大日志
来源：http://dali.yvedp.cn/Article/details/gtemnwmgcb.html

split -l 1000 big.log part_
来源：http://dali.0kj1m.cn/Article/details/gtsebagqan.html

[R74] 批量重命名
来源：http://dali.aizwys.cn/Article/details/gtxaudeehp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.meibo888.top/Article/details/gtmcttlwcf.html

[R75] 导出环境变量
来源：http://dali.yj20258888.top/Article/details/gtatdkkmbx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hywenlv.cn/Article/details/gtmnskldpw.html

[R76] 使用临时文件
来源：http://dali.cucudq.cn/Article/details/gtigetoqdl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuanzx.com/Article/details/gttsfkxbsa.html

[R77] 读取用户输入
来源：http://dali.316326.xyz/Article/details/gtokxmwomh.html

read -rp "请输入: " ans
来源：http://dali.yanxiufei.cn/Article/details/gtqpsdnvnj.html

[R78] 交互式菜单
来源：http://dali.jinqigufen.top/Article/details/gttkcubntx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggiifasa.html

[R79] 解析命令行选项
来源：http://dali.yongpay.top/Article/details/gtlewpfjmx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sysykeji.top/Article/details/gtyrtwrexw.html

[R80] 查看脚本执行耗时
来源：http://dali.shuidangran.top/Article/details/gtlpercwqj.html

time ./run.sh
来源：http://dali.dianchejie.cn/Article/details/gtavhoqlgv.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtnvkegxzm.html

S. C / C++ 专题
来源：http://dali.zhongyouzk.top/Article/details/gtmmwomrpu.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtjiwnawgl.html

[S01] C：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtenshhqjn.html

#include <stdio.h>
来源：http://dali.yanxiufei.cn/Article/details/gtetzfvpew.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xziqi.cn/Article/details/gtenbvtgmx.html

[S02] C：变量与格式化输出
来源：http://dali.sysykeji.top/Article/details/gtsyvvyxou.html

int a = 10; printf("%d\n", a);
来源：http://dali.cheryme.top/Article/details/gtevhqisrw.html

[S03] C：读入整数
来源：http://dali.daria6918.cn/Article/details/gtzrtlxtyu.html

int x; scanf("%d", &x);
来源：http://dali.hnxiangtu.top/Article/details/gtdxrhqenu.html

[S04] C：字符串复制
来源：http://dali.yuanzhike.top/Article/details/gtthbbbhrc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhongyouzk.top/Article/details/gtlobuincp.html

[S05] C：字符串长度
来源：http://dali.gzhubu.top/Article/details/gtskrjankj.html

strlen(s)
来源：http://dali.yueranfly.top/Article/details/gtrqznzzph.html

[S06] C：字符串比较
来源：http://dali.yj20258888.top/Article/details/gtvofzrnut.html

strcmp(a, b) == 0
来源：http://dali.sysykeji.top/Article/details/gtpsctwvdw.html

[S07] C：数组遍历求和
来源：http://dali.smart0.xyz/Article/details/gtljetquhi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqfbjkjfp.html

[S08] C：动态内存分配与释放
来源：http://dali.vqdsnc.cn/Article/details/gtazsroqor.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.dianchejie.cn/Article/details/gtgzmtecks.html

[S09] C：结构体定义与初始化
来源：http://dali.xuanzx.com/Article/details/gtcbetxqum.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zycfv.cn/Article/details/gthfdjvloy.html

[S10] C：指针与解引用
来源：http://dali.snrcjt.cn/Article/details/gtprthxesm.html

int *p = &a;  *p = 5;
来源：http://dali.cashguo.top/Article/details/gtwxmoxnrd.html

[S11] C：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gtzymqimps.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj20258888.top/Article/details/gtwxppbrry.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.bjfxy.top/Article/details/gtoaflvnlr.html

fclose(f);
来源：http://dali.yonumen.top/Article/details/gtkutgabxl.html

[S12] C：写文件
来源：http://dali.yueranfly.top/Article/details/gttqlowqmh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cucudq.cn/Article/details/gtyqwlxmlm.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gtusskzorn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj202588.top/Article/details/gteyxtybaj.html

[S14] C：枚举
来源：http://dali.yangfankeji.com/Article/details/gtssdxeopv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.feifeiyinyue.top/Article/details/gtfdjempwu.html

[S15] C：类型转换
来源：http://dali.yj20258.top/Article/details/gtfqjdxjcx.html

(double) a / b
来源：http://dali.jlsjyb.cn/Article/details/gtoomipmkc.html

[S16] C：位操作置位
来源：http://dali.shangyingyoupin.top/Article/details/gthanmfaxb.html

x |= (1 << 3);
来源：http://dali.316326.xyz/Article/details/gtxpcgvatl.html

[S17] C：安全拼接字符串
来源：http://dali.xuanzx.com/Article/details/gtimjxeykh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zdqjudy.top/Article/details/gtoilbkjii.html

[S18] C：命令行参数
来源：http://dali.yj20258888.top/Article/details/gtdigezrbn.html

int main(int argc, char **argv)
来源：http://dali.yangfankeji.com/Article/details/gtnwjkrjaf.html

[S19] C：快速排序
来源：http://dali.kuanghao11.cn/Article/details/gttjyddxcb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenzaomai.com/Article/details/gtjtundjqw.html

[S20] C：二分查找
来源：http://dali.yj20258.top/Article/details/gtpqlvttdd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jiagoushi.top/Article/details/gtdbqcayrp.html

[S21] C：字符类别判断
来源：http://dali.pengpengdd.cyou/Article/details/gtvheetfnb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hnxiangtu.top/Article/details/gthpvgzkza.html

[S22] C：字符串转数字
来源：http://dali.yangfankeji.com/Article/details/gtirvrqycj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cashguo.top/Article/details/gtntqwmbis.html

[S23] C：随机数
来源：http://dali.jqgufenzy.top/Article/details/gtbpvjjpdx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gzhubu.top/Article/details/gtbjlruyur.html

[S24] C：获取本地时间
来源：http://dali.ppjwa.cn/Article/details/gtsobzwrgg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yonumen.top/Article/details/gtcffpfwjp.html

[S25] C：内存拷贝
来源：http://dali.iojbl.cn/Article/details/gtjuxbglpa.html

memcpy(dst, src, n);
来源：http://dali.cashguo.top/Article/details/gtoktxksuk.html

[S26] C：内存清零
来源：http://dali.guowangkeji.top/Article/details/gtbelecvtq.html

memset(a, 0, sizeof a);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtipmvuvki.html

[S27] C：定义常量
来源：http://dali.cucudq.cn/Article/details/gtenqkghfa.html

const double PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gtmjswmvjx.html

[S28] C：静态变量
来源：http://dali.cashguo.top/Article/details/gtgbguowqg.html

static int counter = 0;
来源：http://dali.meibo888.top/Article/details/gtlzvdxeou.html

[S29] C：变参函数
来源：http://dali.zhongyouzk.top/Article/details/gtcosvrcwh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.daria6918.cn/Article/details/gtfnfgjkhv.html

[S30] C：头文件保护
来源：http://dali.hysaishi.cn/Article/details/gtsaibqvbj.html

#ifndef X_H
来源：http://dali.fengsongda.top/Article/details/gtwkqvucwp.html

#define X_H
来源：http://dali.yuxming.cn/Article/details/gtztcuwjmv.html

#endif
来源：http://dali.yuanzhike.top/Article/details/gtbsvxhckj.html

[S31] C++：Hello World
来源：http://dali.tanke756.top/Article/details/gtvmrwifnc.html

#include <iostream>
来源：http://dali.hysaishi.cn/Article/details/gtxeijdeov.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tianlin.xyz/Article/details/gtpvwdizgo.html

[S32] C++：字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtombdcjnh.html

std::string s = "hi";  s += "!";
来源：http://dali.redwolf501.top/Article/details/gthtojmken.html

[S33] C++：vector 增删
来源：http://dali.haohaochexian.top/Article/details/gtsgehchgp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ivvv.top/Article/details/gthpsboctf.html

[S34] C++：遍历 vector
来源：http://dali.cdnleiting.top/Article/details/gtmjptgttf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cashguo.top/Article/details/gtvahbxrfd.html

[S35] C++：map
来源：http://dali.ydzc1.top/Article/details/gtxmqcvizo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.redwolf501.top/Article/details/gtuvzxtamc.html

[S36] C++：unordered_map
来源：http://dali.yuxming.cn/Article/details/gtcehlcpwx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nwbrower.top/Article/details/gtdxeljqht.html

[S37] C++：set
来源：http://dali.gaohongyu789.top/Article/details/gtbgbccwuc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jlsjyb.cn/Article/details/gtaufpqjaq.html

[S38] C++：排序
来源：http://dali.haohaochexian.top/Article/details/gtknszgulg.html

std::sort(v.begin(), v.end());
来源：http://dali.yuxming.cn/Article/details/gtpmpnsphh.html

[S39] C++：自定义比较器排序
来源：http://dali.jinqigufen.top/Article/details/gtjlvxwhyh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ppjwa.cn/Article/details/gtqtxzdurm.html

[S40] C++：查找元素
来源：http://dali.sxryk.cn/Article/details/gtyphxykjh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xinyue.icu/Article/details/gtgibufiow.html

[S41] C++：类与构造函数
来源：http://dali.birdmap.top/Article/details/gtycdqzowt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xziqi.cn/Article/details/gtgczkbnya.html

[S42] C++：继承与虚函数
来源：http://dali.havefunace.top/Article/details/gtzyrnmxkz.html

class B : public Base { public: void f() override {} };
来源：http://dali.hywenlv.cn/Article/details/gtsuglphij.html

[S43] C++：智能指针
来源：http://dali.yangfankeji.com/Article/details/gtlqlpgism.html

auto p = std::make_unique<int>(5);
来源：http://dali.hongshengwenyu.top/Article/details/gtccgiujzm.html

[S44] C++：引用传参
来源：http://dali.mhx1999.top/Article/details/gtkrqprjct.html

void inc(int &x) { ++x; }
来源：http://dali.cdnleiting.top/Article/details/gtvxcfucxj.html

[S45] C++：lambda
来源：http://dali.xuetiantiany.cn/Article/details/gtbautgjyt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yueranfly.top/Article/details/gtndchpdzg.html

[S46] C++：函数模板
来源：http://dali.jinqigufen.top/Article/details/gtjfzelbaz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xziqi.cn/Article/details/gtaqdxvpss.html

[S47] C++：结构化绑定遍历
来源：http://dali.quarkkingdee.top/Article/details/gtzvkfsfzi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cheryme.top/Article/details/gtdeykorou.html

[S48] C++：逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gtzednymft.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yongpay.top/Article/details/gtexskrxjw.html

while (std::getline(in, line)) { }
来源：http://dali.zhixingplan.top/Article/details/gtzybijwur.html

[S49] C++：写文件
来源：http://dali.wangdashe.top/Article/details/gtxhayxhrt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jyoumei.cn/Article/details/gtnbyssseo.html

[S50] C++：格式化数字
来源：http://dali.yj20258888.top/Article/details/gtedcadqmf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.havefunace.top/Article/details/gtlwqzsrux.html

[S51] C++：显式类型转换
来源：http://dali.sxryk.cn/Article/details/gtygiedrdf.html

static_cast<double>(a) / b
来源：http://dali.zhixingplan.top/Article/details/gtfwothagk.html

[S52] C++：const 与 noexcept
来源：http://dali.havefunace.top/Article/details/gtlvmokugd.html

int size() const noexcept { return n_; }
来源：http://dali.shzxlz.cn/Article/details/gtnvipsrww.html

[S53] C++：移动语义
来源：http://dali.shanyushiyangtech.top/Article/details/gtiycumnmf.html

std::vector<int> w = std::move(v);
来源：http://dali.gzhubu.top/Article/details/gtaazzmphf.html

[S54] C++：异常处理
来源：http://dali.svipenyu.cn/Article/details/gterfaykjm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinqigufen.top/Article/details/gtuhqvjixu.html

[S55] C++：结构化绑定
来源：http://dali.daxiang520.top/Article/details/gtawrtwkhu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.daria6918.cn/Article/details/gtqtcfjzrl.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gtbizvwotn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.kuanghao11.cn/Article/details/gtldrpxafk.html

[S57] C++：编译期常量
来源：http://dali.xziqi.cn/Article/details/gtmkbjmwbu.html

constexpr int N = 10;
来源：http://dali.cqqwz.cn/Article/details/gtktrdawfs.html

[S58] C++：命名空间
来源：http://dali.zhongyouzk.top/Article/details/gtiddyxexm.html

namespace ns { int f() { return 1; } }
来源：http://dali.quarkkingdee.top/Article/details/gtlnfwjqyi.html

[S59] C++：静态断言
来源：http://dali.smart0.xyz/Article/details/gtnxmatepo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdwbjmyji.html

[S60] C++：遍历并删除元素
来源：http://dali.aizwys.cn/Article/details/gthzgmebul.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj202588.top/Article/details/gtxvabcjvt.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtthtjejqb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aizwys.cn/Article/details/gtzyonrgki.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtkuirxluf.html

[T01] Kotlin：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtcvvjxdnp.html

println("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtwjrtfkwa.html

[T02] Kotlin：变量
来源：http://dali.cashguo.top/Article/details/gtpjrpgfuc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhongyouzk.top/Article/details/gtbgttcmfd.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gtqglfcxbw.html

"值: $b"
来源：http://dali.jqgfzy.top/Article/details/gtnzfyydbj.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gtjmajstnf.html

val n: String? = null;  n?.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfowphady.html

[T05] Kotlin：when 表达式
来源：http://dali.gogol.net.cn/Article/details/gtcjkuexsi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jqgfzy.top/Article/details/gtomxdbhib.html

[T06] Kotlin：集合映射
来源：http://dali.yongpay.top/Article/details/gtzxhmjavi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinqigufen.top/Article/details/gtptaotwvz.html

[T07] Kotlin：集合过滤
来源：http://dali.snrcjt.cn/Article/details/gtithlfvcb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gzhubu.top/Article/details/gtpqzbvxfj.html

[T08] Kotlin：数据类
来源：http://dali.meibo888.top/Article/details/gtvxpglrzl.html

data class User(val name: String, val age: Int)
来源：http://dali.gzhubu.top/Article/details/gtlaecqjvf.html

[T09] Kotlin：扩展函数
来源：http://dali.tanke756.top/Article/details/gtafgtpcyf.html

fun String.exclaim() = this + "!"
来源：http://dali.fzhhl.top/Article/details/gtenlzunpe.html

[T10] Kotlin：默认参数
来源：http://dali.gaohongyu789.top/Article/details/gthrmirmpx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj20258888.top/Article/details/gthiivdujs.html

[T11] Kotlin：协程
来源：http://dali.wangshuangyany.cn/Article/details/gteqtgcmkr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinghuilouyu.cn/Article/details/gttdhbkatl.html

[T12] Kotlin：解构声明
来源：http://dali.nwbrower.top/Article/details/gtocmhbjmt.html

val (a, b) = Pair(1, 2)
来源：http://dali.kuanghao11.cn/Article/details/gtjkwwvbhr.html

[T13] Kotlin：只读 Map
来源：http://dali.shanyushiyangtech.top/Article/details/gtkrctwpww.html

val m = mapOf("a" to 1)
来源：http://dali.ppjwa.cn/Article/details/gtdzyjadfm.html

[T14] Kotlin：循环
来源：http://dali.ppjwa.cn/Article/details/gtqznchitx.html

for (i in 1..10) println(i)
来源：http://dali.jlsjyb.cn/Article/details/gtonnltkuw.html

[T15] Kotlin：接口
来源：http://dali.tianlin.xyz/Article/details/gtlbmgtfgy.html

interface Shape { fun area(): Double }
来源：http://dali.cqqwz.cn/Article/details/gtqhdljpsz.html

[T16] Swift：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtbgkabexo.html

print("Hello")
来源：http://dali.xziqi.cn/Article/details/gtrwzvjdkn.html

[T17] Swift：变量与常量
来源：http://dali.tianlin.xyz/Article/details/gtendyyvoe.html

var a = 1;  let b = 2
来源：http://dali.dashuyun.cn/Article/details/gtzjaumnha.html

[T18] Swift：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gtfnutadgs.html

"值: \(b)"
来源：http://dali.tian-w.cn/Article/details/gtgpybcbyi.html

[T19] Swift：可选绑定
来源：http://dali.yuxming.cn/Article/details/gtfietutco.html

if let n = opt { print(n) }
来源：http://dali.havefunace.top/Article/details/gtobbhfuhn.html

[T20] Swift：数组操作
来源：http://dali.chenzaomai.com/Article/details/gtddmpdtan.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.dianchejie.cn/Article/details/gtwtpimozx.html

[T21] Swift：遍历
来源：http://dali.xuetiantiany.cn/Article/details/gthusiturx.html

for x in a { print(x) }
来源：http://dali.shzxlz.cn/Article/details/gtixlixmxr.html

[T22] Swift：字典
来源：http://dali.jiagoushi.top/Article/details/gtmbijnnhe.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.snrcjt.cn/Article/details/gtxcequfqa.html

[T23] Swift：函数
来源：http://dali.snrcjt.cn/Article/details/gtdyoprxme.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yongpay.top/Article/details/gtjvwssbjo.html

[T24] Swift：闭包
来源：http://dali.sufxvd.cn/Article/details/gtxofhnxww.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.snrcjt.cn/Article/details/gtfzxgazkd.html

[T25] Swift：结构体
来源：http://dali.jlsjyb.cn/Article/details/gtuzbehhqq.html

struct P { var x: Int }
来源：http://dali.cdnleiting.top/Article/details/gtljcutpks.html

[T26] Swift：类与重写
来源：http://dali.gogol.net.cn/Article/details/gtktkjbddp.html

class A: Base { override func f() {} }
来源：http://dali.gzhubu.top/Article/details/gtapoqfxwt.html

[T27] Swift：错误处理
来源：http://dali.zycfv.cn/Article/details/gtinkzabbc.html

do { try f() } catch { print(error) }
来源：http://dali.daxiang520.top/Article/details/gtjcuezvof.html

[T28] Swift：枚举
来源：http://dali.haohaochexian.top/Article/details/gtvzlqzywu.html

enum Color { case red, green }
来源：http://dali.pycfn.com/Article/details/gtorexsbca.html

[T29] Swift：guard 提前返回
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvejljbow.html

guard let x = opt else { return }
来源：http://dali.yuanzhike.top/Article/details/gtrlbgqzow.html

[T30] Swift：协议
来源：http://dali.dianchejie.cn/Article/details/gtbyghkxew.html

protocol Shape { func area() -> Double }
来源：http://dali.dianchejie.cn/Article/details/gtvxxbdbie.html

[T31] Lua：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtxpsotzol.html

print("Hello")
来源：http://dali.meibo888.top/Article/details/gtxwszshxr.html

[T32] Lua：局部变量
来源：http://dali.nanxuanxn.top/Article/details/gtrcgdebkl.html

local a = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvyyrqixh.html

[T33] Lua：表（数组）
来源：http://dali.yuanzhike.top/Article/details/gtsuecewra.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.0kj1m.cn/Article/details/gtksuatdnd.html

[T34] Lua：遍历表
来源：http://dali.aibaodan.cn/Article/details/gtlhktswdv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yuanzhike.top/Article/details/gtzmhuhgnx.html

[T35] Lua：字典表
来源：http://dali.jlsjyb.cn/Article/details/gtglppgtwj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yj20258888.top/Article/details/gtspzrnnkq.html

[T36] Lua：函数
来源：http://dali.vqdsnc.cn/Article/details/gtfgwsrqeo.html

function add(a, b) return a + b end
来源：http://dali.tian-w.cn/Article/details/gtdnhrzmxq.html

[T37] Lua：字符串拼接
来源：http://dali.shzxlz.cn/Article/details/gturzhaqkf.html

"a" .. "b"
来源：http://dali.pycfn.com/Article/details/gtccrsucja.html

[T38] Lua：条件
来源：http://dali.quarkkingdee.top/Article/details/gtexamyrwf.html

if x > 0 then print("正") end
来源：http://dali.chenzaomai.com/Article/details/gtqupkrprk.html

[T39] Lua：模式匹配
来源：http://dali.ppjwa.cn/Article/details/gtulwzrhjs.html

string.find(s, "%d+")
来源：http://dali.316326.xyz/Article/details/gtzqgopfmo.html

[T40] Lua：元表
来源：http://dali.nanxuanxn.top/Article/details/gtmdtakalt.html

setmetatable({}, { __index = base })
来源：http://dali.daria6918.cn/Article/details/gtxiiocbid.html

[T41] Perl：Hello World
来源：http://dali.guannengcc.top/Article/details/gtkygsjvan.html

print "Hello\n";
来源：http://dali.pycfn.com/Article/details/gtywjcrxhl.html

[T42] Perl：变量类型
来源：http://dali.0kj1m.cn/Article/details/gtwgokeaft.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cucudq.cn/Article/details/gtkmrkrcpn.html

[T43] Perl：字符串插值
来源：http://dali.ybcxt.top/Article/details/gtzaglxpia.html

"值: $a"
来源：http://dali.hongshengwenyu.top/Article/details/gtskimbfia.html

[T44] Perl：条件
来源：http://dali.redwolf501.top/Article/details/gtkwesliiu.html

if ($a > 0) { print "正"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlcfickib.html

[T45] Perl：数组遍历
来源：http://dali.tanke756.top/Article/details/gtgqwmivcf.html

for my $x (@arr) { print $x; }
来源：http://dali.jqgfzy.top/Article/details/gtvnymnoli.html

[T46] Perl：哈希操作
来源：http://dali.yueranfly.top/Article/details/gtpdubfuwx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.andypj.xyz/Article/details/gtpgklpogm.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gtzknrkchx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.fengsongda.top/Article/details/gtkszsvexa.html

[T48] Perl：正则替换
来源：http://dali.0kj1m.cn/Article/details/gtufrvkrtq.html

$s =~ s/old/new/g;
来源：http://dali.yangfankeji.com/Article/details/gtyjcileda.html

[T49] Perl：函数
来源：http://dali.zhixingplan.top/Article/details/gtosnoytgm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gtlwuuwcbk.html

[T50] Perl：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gtgahveequ.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hysaishi.cn/Article/details/gtxxbetrkr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.dianchejie.cn/Article/details/gttvbhlycf.html

[T51] Scala：Hello World
来源：http://dali.jianghu66.top/Article/details/gtaxsrteko.html

println("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gtjthgwrhl.html

[T52] Scala：变量
来源：http://dali.yvedp.cn/Article/details/gtkujsxcij.html

val a = 1;  var b = 2
来源：http://dali.316326.xyz/Article/details/gtskixvidw.html

[T53] Scala：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gttajucsvs.html

s"值: $b"
来源：http://dali.haohaochexian.top/Article/details/gtfjyuhfvo.html

[T54] Scala：集合映射
来源：http://dali.cqqwz.cn/Article/details/gtajjrbxtn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.0kj1m.cn/Article/details/gtxsbxyfsv.html

[T55] Scala：集合过滤
来源：http://dali.hywenlv.cn/Article/details/gtogvbykkd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.chenzaomai.com/Article/details/gtlgthebjj.html

[T56] Scala：样例类
来源：http://dali.tanke756.top/Article/details/gtvrnrhyyc.html

case class User(name: String, age: Int)
来源：http://dali.shuidangran.top/Article/details/gtgsfbmrho.html

[T57] Scala：模式匹配
来源：http://dali.tianlin.xyz/Article/details/gtsojbpcak.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zdqjudy.top/Article/details/gtzevcstlm.html

[T58] Scala：函数定义
来源：http://dali.wangshuangyany.cn/Article/details/gtxzsmzjzp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yvedp.cn/Article/details/gtzidaitkj.html

[T59] Scala：循环
来源：http://dali.cashguo.top/Article/details/gtsaelspke.html

for (i <- 1 to 10) println(i)
来源：http://dali.cdnleiting.top/Article/details/gthjybupet.html

[T60] Scala：折叠
来源：http://dali.sufxvd.cn/Article/details/gtnvakibvi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.daxiang520.top/Article/details/gtleuhcihp.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtfnurwcis.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.nanxuanxn.top/Article/details/gtrnqyhate.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtddyeeyst.html

[U01] Py：创建虚拟环境
来源：http://dali.cheryme.top/Article/details/gtztujexxy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.gogol.net.cn/Article/details/gtjcqryyli.html

[U02] Py：导出 / 安装依赖
来源：http://dali.svipenyu.cn/Article/details/gtwpcqmeum.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gzhubu.top/Article/details/gtfzlxclro.html

[U03] Py：加载 .env 配置
来源：http://dali.xziqi.cn/Article/details/gtqubxwwgv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cashguo.top/Article/details/gtogojkhlo.html

[U04] Py：变量调试打印
来源：http://dali.0kj1m.cn/Article/details/gtuakbkvhw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.pengpengdd.cyou/Article/details/gtrdmdpzzt.html

[U05] Py：列表去重且保序
来源：http://dali.guannengcc.top/Article/details/gtohboezqn.html

list(dict.fromkeys(arr))
来源：http://dali.hnqzz.top/Article/details/gtabjbbqcb.html

[U06] Py：合并两个字典
来源：http://dali.pengpengdd.cyou/Article/details/gtzprecmhw.html

{**a, **b}
来源：http://dali.xuanzx.com/Article/details/gthmxmfwxl.html

[U07] Py：反转字典键值
来源：http://dali.yonumen.top/Article/details/gtyymnimfv.html

{v: k for k, v in d.items()}
来源：http://dali.sweek.top/Article/details/gtubfhssvo.html

[U08] Py：展平二维列表
来源：http://dali.hammf.cn/Article/details/gtiypwnwyv.html

[y for x in nested for y in x]
来源：http://dali.jqgufenzy.top/Article/details/gtbrpnqmjm.html

[U09] Py：字典取最大值的键
来源：http://dali.nanxuanxn.top/Article/details/gtiqmcadgl.html

max(d, key=d.get)
来源：http://dali.zhixingplan.top/Article/details/gtmjzncwtd.html

[U10] Py：按值排序字典
来源：http://dali.316326.xyz/Article/details/gtwcrlolpm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hysaishi.cn/Article/details/gtxlmmnhbs.html


<!-- 参考信息 -->