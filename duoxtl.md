代发 wailian999

split -l 1000 big.log part_
来源：http://dali.zdqjudy.top/Article/details/gtlrdajbtv.html

[R74] 批量重命名
来源：http://dali.cdnleiting.top/Article/details/gteqoeafgl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtedrunppv.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gtqczsnmob.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.daria6918.cn/Article/details/gtucchieeq.html

[R76] 使用临时文件
来源：http://dali.bjfxy.top/Article/details/gtbtbzedlm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.snrcjt.cn/Article/details/gtetqwvqai.html

[R77] 读取用户输入
来源：http://dali.sweek.top/Article/details/gtfcjllvix.html

read -rp "请输入: " ans
来源：http://dali.yvedp.cn/Article/details/gtxagqjomq.html

[R78] 交互式菜单
来源：http://dali.zycfv.cn/Article/details/gtohqpyvdr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenlongwang.top/Article/details/gtzmzqtxyp.html

[R79] 解析命令行选项
来源：http://dali.sweek.top/Article/details/gtyxjmtbhc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenlongwang.top/Article/details/gtrfpvwcka.html

[R80] 查看脚本执行耗时
来源：http://dali.cucudq.cn/Article/details/gtzsakosah.html

time ./run.sh
来源：http://dali.zhongyouzk.top/Article/details/gtvyoqeyac.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtoayulswi.html

S. C / C++ 专题
来源：http://dali.nwbrower.top/Article/details/gtvghwjowu.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtrslloryv.html

[S01] C：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtfhrgffgp.html

#include <stdio.h>
来源：http://dali.ivvv.top/Article/details/gtifpcnfpo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nanxinkj.top/Article/details/gtljjtbvwa.html

[S02] C：变量与格式化输出
来源：http://dali.yj202588.top/Article/details/gtmpwfkoex.html

int a = 10; printf("%d\n", a);
来源：http://dali.svipenyu.cn/Article/details/gtnrvcbjtv.html

[S03] C：读入整数
来源：http://dali.jyoumei.cn/Article/details/gtxurswbqk.html

int x; scanf("%d", &x);
来源：http://dali.iojbl.cn/Article/details/gtfqeiutub.html

[S04] C：字符串复制
来源：http://dali.xziqi.cn/Article/details/gtphavgdua.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hysaishi.cn/Article/details/gtesykescq.html

[S05] C：字符串长度
来源：http://dali.wangdashe.top/Article/details/gtlyflzfgv.html

strlen(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdfxtnzon.html

[S06] C：字符串比较
来源：http://dali.jqgfzy.top/Article/details/gtyokridri.html

strcmp(a, b) == 0
来源：http://dali.yueranfly.top/Article/details/gtkquxbyjm.html

[S07] C：数组遍历求和
来源：http://dali.jyoumei.cn/Article/details/gtkrqvlaou.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.havefunace.top/Article/details/gtprglckfb.html

[S08] C：动态内存分配与释放
来源：http://dali.chenlongwang.top/Article/details/gtuvzzyyty.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yj20258888.top/Article/details/gtojroknwd.html

[S09] C：结构体定义与初始化
来源：http://dali.aizwys.cn/Article/details/gtxxyeajpj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hysaishi.cn/Article/details/gttjemxjqb.html

[S10] C：指针与解引用
来源：http://dali.gaohongyu789.top/Article/details/gtliggiynw.html

int *p = &a;  *p = 5;
来源：http://dali.ydzc1.top/Article/details/gtxmryxjdc.html

[S11] C：逐行读文件
来源：http://dali.bjfxy.top/Article/details/gtcigvmgfh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gogol.net.cn/Article/details/gtsyxkrvrl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinqigfzy.top/Article/details/gtheosvrzp.html

fclose(f);
来源：http://dali.snrcjt.cn/Article/details/gtzfwufofq.html

[S12] C：写文件
来源：http://dali.sufxvd.cn/Article/details/gtghlamzow.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shzxlz.cn/Article/details/gtcjjxuzih.html

[S13] C：宏定义
来源：http://dali.ybcxt.top/Article/details/gtrwdzcvkq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhiwuduotai.top/Article/details/gtnsccnjni.html

[S14] C：枚举
来源：http://dali.hnqzz.top/Article/details/gttmvbwtfe.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shangyingyoupin.top/Article/details/gtmsoxzzzp.html

[S15] C：类型转换
来源：http://dali.zdqjudy.top/Article/details/gtlhqftuqq.html

(double) a / b
来源：http://dali.c1oappe.top/Article/details/gtfbvdmbuf.html

[S16] C：位操作置位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxzzndcgu.html

x |= (1 << 3);
来源：http://dali.havefunace.top/Article/details/gtjsbhhzwd.html

[S17] C：安全拼接字符串
来源：http://dali.sufxvd.cn/Article/details/gtxecgmgbr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhengqikj.top/Article/details/gtcpiqwswu.html

[S18] C：命令行参数
来源：http://dali.ybcxt.top/Article/details/gtrjvvfpox.html

int main(int argc, char **argv)
来源：http://dali.chenzaomai.com/Article/details/gtewkgufow.html

[S19] C：快速排序
来源：http://dali.9152youxi.cn/Article/details/gtymhlaysf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cdnleiting.top/Article/details/gtyublvywo.html

[S20] C：二分查找
来源：http://dali.yueranfly.top/Article/details/gtyyehgnra.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yuanzhike.top/Article/details/gtyzreuqil.html

[S21] C：字符类别判断
来源：http://dali.zhixingplan.top/Article/details/gtnbbzvjbi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjqhnhsha.html

[S22] C：字符串转数字
来源：http://dali.xziqi.cn/Article/details/gtwunfvrnl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jqgfzy.top/Article/details/gtanazgtpn.html

[S23] C：随机数
来源：http://dali.andypj.xyz/Article/details/gtudyjjduj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gtpwxarcfp.html

[S24] C：获取本地时间
来源：http://dali.jlsjyb.cn/Article/details/gtescimmno.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ivvv.top/Article/details/gtmkrdarps.html

[S25] C：内存拷贝
来源：http://dali.gogol.net.cn/Article/details/gtjhwmwmrb.html

memcpy(dst, src, n);
来源：http://dali.ydzc1.top/Article/details/gtvghhrzmh.html

[S26] C：内存清零
来源：http://dali.meibo888.top/Article/details/gttocalelj.html

memset(a, 0, sizeof a);
来源：http://dali.yongpay.top/Article/details/gthwsyfcpl.html

[S27] C：定义常量
来源：http://dali.xziqi.cn/Article/details/gtnblmtkmm.html

const double PI = 3.14159;
来源：http://dali.hammf.cn/Article/details/gtmrdyzvej.html

[S28] C：静态变量
来源：http://dali.yueranfly.top/Article/details/gtvugvgmgl.html

static int counter = 0;
来源：http://dali.yj20258888.top/Article/details/gtqhtzzypr.html

[S29] C：变参函数
来源：http://dali.dianchejie.cn/Article/details/gtmeryfkjh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.guannengcc.top/Article/details/gtzmkjqivm.html

[S30] C：头文件保护
来源：http://dali.xuanzx.com/Article/details/gtyxbvrtct.html

#ifndef X_H
来源：http://dali.jianghu66.top/Article/details/gtzybcalvh.html

#define X_H
来源：http://dali.hfpthk.cn/Article/details/gtgnlseiae.html

#endif
来源：http://dali.316326.xyz/Article/details/gtoxuoxgkr.html

[S31] C++：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyyobtdzz.html

#include <iostream>
来源：http://dali.xinyue.icu/Article/details/gttwcxmdla.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.haohaochexian.top/Article/details/gtejydbfbt.html

[S32] C++：字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmvvwhbw.html

std::string s = "hi";  s += "!";
来源：http://dali.redwolf501.top/Article/details/gtqgdisamz.html

[S33] C++：vector 增删
来源：http://dali.ehwqpu.com/Article/details/gtglvrpprc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.nanxinkj.top/Article/details/gtypcxcjfd.html

[S34] C++：遍历 vector
来源：http://dali.shanyushiyangtech.top/Article/details/gtaxfeaobd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jqgfzy.top/Article/details/gtbmsgrcih.html

[S35] C++：map
来源：http://dali.kuanghao11.cn/Article/details/gtxslrhesl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yonumen.top/Article/details/gtqnumyati.html

[S36] C++：unordered_map
来源：http://dali.tanke756.top/Article/details/gtjvqpiniz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xinyue.icu/Article/details/gtnndocxiz.html

[S37] C++：set
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuezsjcos.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jyoumei.cn/Article/details/gtlufqjllv.html

[S38] C++：排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuaygstug.html

std::sort(v.begin(), v.end());
来源：http://dali.xylfe.cn/Article/details/gtjokgepjx.html

[S39] C++：自定义比较器排序
来源：http://dali.chenlongwang.top/Article/details/gtepznatoy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenjidiqi.icu/Article/details/gtxezrziji.html

[S40] C++：查找元素
来源：http://dali.jiagoushi.top/Article/details/gttvonywtp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.bjfxy.top/Article/details/gtrphokful.html

[S41] C++：类与构造函数
来源：http://dali.hammf.cn/Article/details/gtskathmvn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cashguo.top/Article/details/gtyvcdpuqn.html

[S42] C++：继承与虚函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmecxznki.html

class B : public Base { public: void f() override {} };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvnbblvrd.html

[S43] C++：智能指针
来源：http://dali.fzhhl.top/Article/details/gteynudneu.html

auto p = std::make_unique<int>(5);
来源：http://dali.hysaishi.cn/Article/details/gtatdjattb.html

[S44] C++：引用传参
来源：http://dali.xylfe.cn/Article/details/gtkvraelnw.html

void inc(int &x) { ++x; }
来源：http://dali.hfpthk.cn/Article/details/gtyrpnrxux.html

[S45] C++：lambda
来源：http://dali.hfpthk.cn/Article/details/gtkihauoeo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jyoumei.cn/Article/details/gtdlpnjgoo.html

[S46] C++：函数模板
来源：http://dali.smart0.xyz/Article/details/gtxthxaoqr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jianghu66.top/Article/details/gtybzcmguu.html

[S47] C++：结构化绑定遍历
来源：http://dali.jlsjyb.cn/Article/details/gtjdbswpjb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.meibo888.top/Article/details/gtpzpuihhr.html

[S48] C++：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gtqodqyihy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.9152youxi.cn/Article/details/gtmeytldjf.html

while (std::getline(in, line)) { }
来源：http://dali.ppjwa.cn/Article/details/gtdftdbjpy.html

[S49] C++：写文件
来源：http://dali.andypj.xyz/Article/details/gthmtztxlv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.guannengcc.top/Article/details/gtiuxduklv.html

[S50] C++：格式化数字
来源：http://dali.aibaodan.cn/Article/details/gthnpgmkru.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nwbrower.top/Article/details/gtdtpnrfbi.html

[S51] C++：显式类型转换
来源：http://dali.havefunace.top/Article/details/gttkfmondh.html

static_cast<double>(a) / b
来源：http://dali.ivvv.top/Article/details/gtvpzpuarj.html

[S52] C++：const 与 noexcept
来源：http://dali.fengsongda.top/Article/details/gtdezgdmxk.html

int size() const noexcept { return n_; }
来源：http://dali.zhoulong.xyz/Article/details/gtmarufugd.html

[S53] C++：移动语义
来源：http://dali.guowangkeji.top/Article/details/gtahaexpha.html

std::vector<int> w = std::move(v);
来源：http://dali.hnxiangtu.top/Article/details/gtzdfvrrxv.html

[S54] C++：异常处理
来源：http://dali.yueranfly.top/Article/details/gtaummzpji.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.316326.xyz/Article/details/gtgntfwmfm.html

[S55] C++：结构化绑定
来源：http://dali.jinqigfzy.top/Article/details/gtdkwxvdup.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhixingplan.top/Article/details/gtdqisowsx.html

[S56] C++：optional
来源：http://dali.aibaodan.cn/Article/details/gtpbwzlvsx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhoulong.xyz/Article/details/gtgkilpbuc.html

[S57] C++：编译期常量
来源：http://dali.zhiwuduotai.top/Article/details/gtpbmmwrvm.html

constexpr int N = 10;
来源：http://dali.kuanghao11.cn/Article/details/gtykskcwrk.html

[S58] C++：命名空间
来源：http://dali.yuanzhike.top/Article/details/gtoriwvhff.html

namespace ns { int f() { return 1; } }
来源：http://dali.bjfxy.top/Article/details/gtexdotdet.html

[S59] C++：静态断言
来源：http://dali.yanxiufei.cn/Article/details/gtxgjufsxh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yj202588.top/Article/details/gtgpaxjhkg.html

[S60] C++：遍历并删除元素
来源：http://dali.yj20258.top/Article/details/gtazmzgfpi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gtzganmxfs.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtwwjohhxh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tian-w.cn/Article/details/gtdewqahcg.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtymaxfyfe.html

[T01] Kotlin：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtyzvkgalj.html

println("Hello")
来源：http://dali.tianlin.xyz/Article/details/gtesnbebkt.html

[T02] Kotlin：变量
来源：http://dali.jinqigufen.top/Article/details/gthcvhfdgh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xuanzx.com/Article/details/gttgiitixg.html

[T03] Kotlin：字符串模板
来源：http://dali.xylfe.cn/Article/details/gthumdtahw.html

"值: $b"
来源：http://dali.havefunace.top/Article/details/gtzdknqtxv.html

[T04] Kotlin：空安全
来源：http://dali.shangyingyoupin.top/Article/details/gtqdtxnrav.html

val n: String? = null;  n?.length
来源：http://dali.andypj.xyz/Article/details/gtpcdgwfoj.html

[T05] Kotlin：when 表达式
来源：http://dali.wangdashe.top/Article/details/gtzglwrbzo.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jqgufenzy.top/Article/details/gttasnonwv.html

[T06] Kotlin：集合映射
来源：http://dali.zhiwuduotai.top/Article/details/gtkczavmoe.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xuanzx.com/Article/details/gthmrquukq.html

[T07] Kotlin：集合过滤
来源：http://dali.havefunace.top/Article/details/gtagtvdbyy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuanzhike.top/Article/details/gtvgarhzsr.html

[T08] Kotlin：数据类
来源：http://dali.yueranfly.top/Article/details/gtxsxnqyhp.html

data class User(val name: String, val age: Int)
来源：http://dali.zhoulong.xyz/Article/details/gtnvhmfhjm.html

[T09] Kotlin：扩展函数
来源：http://dali.shzxlz.cn/Article/details/gtcpmmqwfq.html

fun String.exclaim() = this + "!"
来源：http://dali.wangshuangyany.cn/Article/details/gtpifgezhp.html

[T10] Kotlin：默认参数
来源：http://dali.zhengqikj.top/Article/details/gtqodmqoma.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shzxlz.cn/Article/details/gtkyqkdjzr.html

[T11] Kotlin：协程
来源：http://dali.xylfe.cn/Article/details/gthcasarid.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.9152youxi.cn/Article/details/gtciezydlo.html

[T12] Kotlin：解构声明
来源：http://dali.nanxinkj.top/Article/details/gtqegybiet.html

val (a, b) = Pair(1, 2)
来源：http://dali.cucudq.cn/Article/details/gtdlisxxoe.html

[T13] Kotlin：只读 Map
来源：http://dali.dashuyun.cn/Article/details/gtipctvfit.html

val m = mapOf("a" to 1)
来源：http://dali.jinqigfzy.top/Article/details/gttfwfunsg.html

[T14] Kotlin：循环
来源：http://dali.tianlin.xyz/Article/details/gtwxgdjrmj.html

for (i in 1..10) println(i)
来源：http://dali.zhiwuduotai.top/Article/details/gtplcwnluh.html

[T15] Kotlin：接口
来源：http://dali.jqgufenzy.top/Article/details/gtvaqdpgzz.html

interface Shape { fun area(): Double }
来源：http://dali.quarkkingdee.top/Article/details/gtvuobfjxc.html

[T16] Swift：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtzgayojgi.html

print("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gtzlplmotr.html

[T17] Swift：变量与常量
来源：http://dali.gzhubu.top/Article/details/gtcmahzjrv.html

var a = 1;  let b = 2
来源：http://dali.xinyue.icu/Article/details/gtlxuonhct.html

[T18] Swift：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gtmpbtlnrn.html

"值: \(b)"
来源：http://dali.316326.xyz/Article/details/gtlqvwazgt.html

[T19] Swift：可选绑定
来源：http://dali.nanxinkj.top/Article/details/gteqvveqrq.html

if let n = opt { print(n) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsneaoals.html

[T20] Swift：数组操作
来源：http://dali.svipenyu.cn/Article/details/gtyrojhzhr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hnxiangtu.top/Article/details/gtncphaxfh.html

[T21] Swift：遍历
来源：http://dali.kuanghao11.cn/Article/details/gtqiihwmts.html

for x in a { print(x) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkipqvxjh.html

[T22] Swift：字典
来源：http://dali.daxiang520.top/Article/details/gtxdgewpeq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gaohongyu789.top/Article/details/gtqdwyjxji.html

[T23] Swift：函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtjlmbkadc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cqqwz.cn/Article/details/gtudbfzqrl.html

[T24] Swift：闭包
来源：http://dali.xylfe.cn/Article/details/gtijhaoilv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hnqzz.top/Article/details/gtdynjjuva.html

[T25] Swift：结构体
来源：http://dali.cucudq.cn/Article/details/gtylzoxatz.html

struct P { var x: Int }
来源：http://dali.nanxuanxn.top/Article/details/gtoeksfpgv.html

[T26] Swift：类与重写
来源：http://dali.yj20258888.top/Article/details/gtydhbzitd.html

class A: Base { override func f() {} }
来源：http://dali.zdqjudy.top/Article/details/gtziwstpvc.html

[T27] Swift：错误处理
来源：http://dali.yueranfly.top/Article/details/gtzzhfqcvx.html

do { try f() } catch { print(error) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhxaodty.html

[T28] Swift：枚举
来源：http://dali.jiagoushi.top/Article/details/gtrjedkqvq.html

enum Color { case red, green }
来源：http://dali.fengsongda.top/Article/details/gtdvmwgzyi.html

[T29] Swift：guard 提前返回
来源：http://dali.xylfe.cn/Article/details/gtvcesnohs.html

guard let x = opt else { return }
来源：http://dali.zhiwuduotai.top/Article/details/gtvikwgauw.html

[T30] Swift：协议
来源：http://dali.chenzaomai.com/Article/details/gtnmcnbalv.html

protocol Shape { func area() -> Double }
来源：http://dali.aibaodan.cn/Article/details/gtuveyfpsu.html

[T31] Lua：Hello World
来源：http://dali.xziqi.cn/Article/details/gtkxdtlgpu.html

print("Hello")
来源：http://dali.pycfn.com/Article/details/gtluyjofoy.html

[T32] Lua：局部变量
来源：http://dali.gzhubu.top/Article/details/gtmwxkqrzc.html

local a = 1
来源：http://dali.andypj.xyz/Article/details/gtsglbyrht.html

[T33] Lua：表（数组）
来源：http://dali.aibaodan.cn/Article/details/gtpifczmzh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yanxiufei.cn/Article/details/gtdunfctug.html

[T34] Lua：遍历表
来源：http://dali.jiagoushi.top/Article/details/gtizteociq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yonumen.top/Article/details/gtqzligzqe.html

[T35] Lua：字典表
来源：http://dali.nanxinkj.top/Article/details/gtdxbdmrxa.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hfpthk.cn/Article/details/gtodlobitk.html

[T36] Lua：函数
来源：http://dali.tanke756.top/Article/details/gtgnasjfth.html

function add(a, b) return a + b end
来源：http://dali.shuidangran.top/Article/details/gtnwtaqutt.html

[T37] Lua：字符串拼接
来源：http://dali.tianlin.xyz/Article/details/gtpijiqlak.html

"a" .. "b"
来源：http://dali.fzhhl.top/Article/details/gthudydqwt.html

[T38] Lua：条件
来源：http://dali.cashguo.top/Article/details/gtbknjwjqw.html

if x > 0 then print("正") end
来源：http://dali.xuanzx.com/Article/details/gttfhyljsl.html

[T39] Lua：模式匹配
来源：http://dali.ehwqpu.com/Article/details/gtknwibinv.html

string.find(s, "%d+")
来源：http://dali.yj202588.top/Article/details/gteglaorur.html

[T40] Lua：元表
来源：http://dali.hnqzz.top/Article/details/gttieavkam.html

setmetatable({}, { __index = base })
来源：http://dali.dashuyun.cn/Article/details/gtnbhxcujg.html

[T41] Perl：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtdlewjisb.html

print "Hello\n";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyohohjxn.html

[T42] Perl：变量类型
来源：http://dali.yangfankeji.com/Article/details/gtbrokdnrm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.c1oappe.top/Article/details/gtcoeudirr.html

[T43] Perl：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gthhfnvjne.html

"值: $a"
来源：http://dali.yuanzhike.top/Article/details/gtngomzbki.html

[T44] Perl：条件
来源：http://dali.0kj1m.cn/Article/details/gtjtoacuiy.html

if ($a > 0) { print "正"; }
来源：http://dali.yongpay.top/Article/details/gtfofcjqxy.html

[T45] Perl：数组遍历
来源：http://dali.daria6918.cn/Article/details/gtnicqhmtd.html

for my $x (@arr) { print $x; }
来源：http://dali.feifeiyinyue.top/Article/details/gtupslrsog.html

[T46] Perl：哈希操作
来源：http://dali.iojbl.cn/Article/details/gtofnljyrh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.quarkkingdee.top/Article/details/gtveosgbjg.html

[T47] Perl：正则捕获
来源：http://dali.chenzaomai.com/Article/details/gtgppiwhpi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.fzhhl.top/Article/details/gtkxojshqe.html

[T48] Perl：正则替换
来源：http://dali.gzhubu.top/Article/details/gtukfgpsjd.html

$s =~ s/old/new/g;
来源：http://dali.jinqigfzy.top/Article/details/gtpsphvdme.html

[T49] Perl：函数
来源：http://dali.yanxiufei.cn/Article/details/gtdwkjqjim.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.andypj.xyz/Article/details/gtfmeajbou.html

[T50] Perl：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gtkpsmhbsf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhongyouzk.top/Article/details/gtpuhunfls.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sysykeji.top/Article/details/gtpdkdvvpb.html

[T51] Scala：Hello World
来源：http://dali.316326.xyz/Article/details/gtpptaeyim.html

println("Hello")
来源：http://dali.zdqjudy.top/Article/details/gtywplgyec.html

[T52] Scala：变量
来源：http://dali.wangdashe.top/Article/details/gtqmvcozla.html

val a = 1;  var b = 2
来源：http://dali.hammf.cn/Article/details/gtlilgcshc.html

[T53] Scala：字符串插值
来源：http://dali.meibo888.top/Article/details/gtqgxzluhf.html

s"值: $b"
来源：http://dali.gzhubu.top/Article/details/gtzugfbvcl.html

[T54] Scala：集合映射
来源：http://dali.yonumen.top/Article/details/gthkfzxfls.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ybcxt.top/Article/details/gtilkhpikw.html

[T55] Scala：集合过滤
来源：http://dali.dianchejie.cn/Article/details/gtxcdhfnom.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yuanzhike.top/Article/details/gttjquiitz.html

[T56] Scala：样例类
来源：http://dali.cheryme.top/Article/details/gtwhrkvofb.html

case class User(name: String, age: Int)
来源：http://dali.tianlin.xyz/Article/details/gtfxpyszmq.html

[T57] Scala：模式匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzudcgtyr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.smart0.xyz/Article/details/gtuyuouawg.html

[T58] Scala：函数定义
来源：http://dali.sufxvd.cn/Article/details/gtciidogpl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xuetiantiany.cn/Article/details/gtsbybgzse.html

[T59] Scala：循环
来源：http://dali.wangdashe.top/Article/details/gtbswydeip.html

for (i <- 1 to 10) println(i)
来源：http://dali.jqgufenzy.top/Article/details/gtywyrbhlt.html

[T60] Scala：折叠
来源：http://dali.aibaodan.cn/Article/details/gtnrjggbkp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhongyouzk.top/Article/details/gtsumcmkvr.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtkyfnsvyp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xziqi.cn/Article/details/gtfmwnxhei.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtljtdwkel.html

[U01] Py：创建虚拟环境
来源：http://dali.yueranfly.top/Article/details/gtzdrritlw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtznwxlvso.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zycfv.cn/Article/details/gtjvsbpjrq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtgbtbhyxn.html

[U03] Py：加载 .env 配置
来源：http://dali.bjfxy.top/Article/details/gtmonageqh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.sxryk.cn/Article/details/gtkpploxhg.html

[U04] Py：变量调试打印
来源：http://dali.ivvv.top/Article/details/gtuoqynajy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtovnhxzzo.html

[U05] Py：列表去重且保序
来源：http://dali.daria6918.cn/Article/details/gtayldzwkt.html

list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gtytwlnalc.html

[U06] Py：合并两个字典
来源：http://dali.cashguo.top/Article/details/gtudcdptsu.html

{**a, **b}
来源：http://dali.hfpthk.cn/Article/details/gtukntscgf.html

[U07] Py：反转字典键值
来源：http://dali.tianlin.xyz/Article/details/gtrellzlnn.html

{v: k for k, v in d.items()}
来源：http://dali.chenzaomai.com/Article/details/gtbgpgaxie.html

[U08] Py：展平二维列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiifbfqfp.html

[y for x in nested for y in x]
来源：http://dali.yueranfly.top/Article/details/gtghntpsvn.html

[U09] Py：字典取最大值的键
来源：http://dali.pycfn.com/Article/details/gtymclbpjv.html

max(d, key=d.get)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjbesbccz.html

[U10] Py：按值排序字典
来源：http://dali.meibo888.top/Article/details/gtfrwulltp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gzhubu.top/Article/details/gthnvqbuge.html

[U11] Py：生成器表达式
来源：http://dali.yj202588.top/Article/details/gtnvlwcbwi.html

(x * 2 for x in arr)
来源：http://dali.gotoacloud.top/Article/details/gtojwwmxaz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzshoyipo.html

Counter(arr).most_common(3)
来源：http://dali.gzhubu.top/Article/details/gtjehapsmg.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gtuigdcnmg.html

deque(maxlen=10)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtznugpprv.html

[U14] Py：分组收集到列表
来源：http://dali.ehwqpu.com/Article/details/gtcxpoxiby.html

defaultdict(list)
来源：http://dali.zhongyouzk.top/Article/details/gtaapralpm.html


<!-- 参考信息 -->