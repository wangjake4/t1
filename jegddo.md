代发 wailian999

export PATH="$HOME/bin:$PATH"
来源：http://dali.svipenyu.cn/Article/details/gtnbrydiax.html

[R76] 使用临时文件
来源：http://dali.zycfv.cn/Article/details/gtehqcqsmp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gthbugpyxr.html

[R77] 读取用户输入
来源：http://dali.jianghu66.top/Article/details/gtzqmgcyis.html

read -rp "请输入: " ans
来源：http://dali.xinyue.icu/Article/details/gtjtflljit.html

[R78] 交互式菜单
来源：http://dali.hammf.cn/Article/details/gttsoulerg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gtrvjjlmmh.html

[R79] 解析命令行选项
来源：http://dali.aizwys.cn/Article/details/gtwquwqlhb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.smart0.xyz/Article/details/gtjxitlhyb.html

[R80] 查看脚本执行耗时
来源：http://dali.xylfe.cn/Article/details/gtwlsdxufs.html

time ./run.sh
来源：http://dali.pengpengdd.cyou/Article/details/gtvspwkapg.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtmvjyxohi.html

S. C / C++ 专题
来源：http://dali.316326.xyz/Article/details/gtzgmaxutd.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtpwtbazar.html

[S01] C：Hello World
来源：http://dali.yueranfly.top/Article/details/gtstpcroka.html

#include <stdio.h>
来源：http://dali.jinghuilouyu.cn/Article/details/gteyvgpsfu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.andypj.xyz/Article/details/gtwzyvvxoi.html

[S02] C：变量与格式化输出
来源：http://dali.kuanghao11.cn/Article/details/gtoywyrmri.html

int a = 10; printf("%d\n", a);
来源：http://dali.hammf.cn/Article/details/gtzunpcqys.html

[S03] C：读入整数
来源：http://dali.smart0.xyz/Article/details/gtxwrbgblk.html

int x; scanf("%d", &x);
来源：http://dali.redwolf501.top/Article/details/gtsrejounf.html

[S04] C：字符串复制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpuuymzqc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cucudq.cn/Article/details/gtcvykuaya.html

[S05] C：字符串长度
来源：http://dali.xziqi.cn/Article/details/gtweuzypzz.html

strlen(s)
来源：http://dali.dashuyun.cn/Article/details/gtyzytpupv.html

[S06] C：字符串比较
来源：http://dali.jqgfzy.top/Article/details/gtuitzuyjf.html

strcmp(a, b) == 0
来源：http://dali.daxiang520.top/Article/details/gtfrlfoehc.html

[S07] C：数组遍历求和
来源：http://dali.chenzaomai.com/Article/details/gtolhshzog.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sufxvd.cn/Article/details/gtypfzpqca.html

[S08] C：动态内存分配与释放
来源：http://dali.sufxvd.cn/Article/details/gtmmqgqfyl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nanxinkj.top/Article/details/gtfwdtatoy.html

[S09] C：结构体定义与初始化
来源：http://dali.tianlin.xyz/Article/details/gtacsyumzl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cqqwz.cn/Article/details/gthdmocprh.html

[S10] C：指针与解引用
来源：http://dali.dashuyun.cn/Article/details/gtlzhoyvei.html

int *p = &a;  *p = 5;
来源：http://dali.yueranfly.top/Article/details/gtmpsenlsp.html

[S11] C：逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gtmboonkts.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.fzhhl.top/Article/details/gtifswuhyx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaudgacbi.html

fclose(f);
来源：http://dali.svipenyu.cn/Article/details/gtivpfqgej.html

[S12] C：写文件
来源：http://dali.shangyingyoupin.top/Article/details/gtbnfcdczn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.daxiang520.top/Article/details/gtgncpkncg.html

[S13] C：宏定义
来源：http://dali.yongpay.top/Article/details/gtidipcfyo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sysykeji.top/Article/details/gtayhoxsxs.html

[S14] C：枚举
来源：http://dali.chenlongwang.top/Article/details/gtbpwdtmdt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xuanzx.com/Article/details/gtowhfbimt.html

[S15] C：类型转换
来源：http://dali.fzhhl.top/Article/details/gtbdndfrvu.html

(double) a / b
来源：http://dali.nanxinkj.top/Article/details/gtrysnmhpy.html

[S16] C：位操作置位
来源：http://dali.yj20258.top/Article/details/gtupgsnjlm.html

x |= (1 << 3);
来源：http://dali.zhoulong.xyz/Article/details/gtuyooluqw.html

[S17] C：安全拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gtlfaadcuu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtguvswysw.html

[S18] C：命令行参数
来源：http://dali.cdnleiting.top/Article/details/gtcsurnnac.html

int main(int argc, char **argv)
来源：http://dali.dianchejie.cn/Article/details/gtjqrtlhkf.html

[S19] C：快速排序
来源：http://dali.jinqigfzy.top/Article/details/gtxbytrgzu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ydzc1.top/Article/details/gtxrmcmace.html

[S20] C：二分查找
来源：http://dali.cqqwz.cn/Article/details/gtchlkpxik.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.pycfn.com/Article/details/gtdjftylzs.html

[S21] C：字符类别判断
来源：http://dali.ehwqpu.com/Article/details/gtbqtmnqqw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.0kj1m.cn/Article/details/gtbkjmlgmh.html

[S22] C：字符串转数字
来源：http://dali.jqgfzy.top/Article/details/gtjjeoecok.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jyoumei.cn/Article/details/gtvntlkccn.html

[S23] C：随机数
来源：http://dali.guannengcc.top/Article/details/gtcrozssrt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtebeogmmx.html

[S24] C：获取本地时间
来源：http://dali.meibo888.top/Article/details/gtiqgrcdqp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gogol.net.cn/Article/details/gtbogketkd.html

[S25] C：内存拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhtorvnt.html

memcpy(dst, src, n);
来源：http://dali.yanxiufei.cn/Article/details/gtesrkqnpc.html

[S26] C：内存清零
来源：http://dali.ehwqpu.com/Article/details/gtmzpoatpf.html

memset(a, 0, sizeof a);
来源：http://dali.sufxvd.cn/Article/details/gtahawxlcb.html

[S27] C：定义常量
来源：http://dali.xylfe.cn/Article/details/gthixfrdgh.html

const double PI = 3.14159;
来源：http://dali.guannengcc.top/Article/details/gtzklqadby.html

[S28] C：静态变量
来源：http://dali.hnxiangtu.top/Article/details/gtgnknejjk.html

static int counter = 0;
来源：http://dali.daxiang520.top/Article/details/gtrgzhhjlc.html

[S29] C：变参函数
来源：http://dali.chenlongwang.top/Article/details/gtmpmsbqcs.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.aibaodan.cn/Article/details/gtpesdupqb.html

[S30] C：头文件保护
来源：http://dali.0kj1m.cn/Article/details/gtapjrojkl.html

#ifndef X_H
来源：http://dali.hammf.cn/Article/details/gtivmmkvms.html

#define X_H
来源：http://dali.yueranfly.top/Article/details/gtgvwosnxg.html

#endif
来源：http://dali.sufxvd.cn/Article/details/gtvditjxgs.html

[S31] C++：Hello World
来源：http://dali.sysykeji.top/Article/details/gtqjaaqpjw.html

#include <iostream>
来源：http://dali.hywenlv.cn/Article/details/gtnpoxdkfo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yj20258888.top/Article/details/gthwefepkn.html

[S32] C++：字符串
来源：http://dali.xylfe.cn/Article/details/gtpkumlfpu.html

std::string s = "hi";  s += "!";
来源：http://dali.shzxlz.cn/Article/details/gtkgrrwjqs.html

[S33] C++：vector 增删
来源：http://dali.wangshuangyany.cn/Article/details/gtvaqwdhxt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sxryk.cn/Article/details/gtcifbleks.html

[S34] C++：遍历 vector
来源：http://dali.9152youxi.cn/Article/details/gtjwjgeffd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tianlin.xyz/Article/details/gtmugwgfkv.html

[S35] C++：map
来源：http://dali.0kj1m.cn/Article/details/gtlynpxygf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cashguo.top/Article/details/gtrtasvdgk.html

[S36] C++：unordered_map
来源：http://dali.tianlin.xyz/Article/details/gtmwvnkabo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.316326.xyz/Article/details/gtudlqtysw.html

[S37] C++：set
来源：http://dali.jinqigufen.top/Article/details/gtjkbvnfog.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhoulong.xyz/Article/details/gtreojujvl.html

[S38] C++：排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlyfzesqf.html

std::sort(v.begin(), v.end());
来源：http://dali.daxiang520.top/Article/details/gtkyilmguq.html

[S39] C++：自定义比较器排序
来源：http://dali.xinyue.icu/Article/details/gtdocfotwq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.dianchejie.cn/Article/details/gtzvkibmfk.html

[S40] C++：查找元素
来源：http://dali.iojbl.cn/Article/details/gtaxmfwrxu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.0kj1m.cn/Article/details/gtbiswydbk.html

[S41] C++：类与构造函数
来源：http://dali.yj202588.top/Article/details/gttaoksygd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zdqjudy.top/Article/details/gtyvsowjwo.html

[S42] C++：继承与虚函数
来源：http://dali.yonumen.top/Article/details/gtjkgleiwo.html

class B : public Base { public: void f() override {} };
来源：http://dali.iojbl.cn/Article/details/gtvbcawxfh.html

[S43] C++：智能指针
来源：http://dali.cheryme.top/Article/details/gthuepnkpn.html

auto p = std::make_unique<int>(5);
来源：http://dali.yuanzhike.top/Article/details/gthieeijam.html

[S44] C++：引用传参
来源：http://dali.shangyingyoupin.top/Article/details/gtfdbtyvkr.html

void inc(int &x) { ++x; }
来源：http://dali.yuxming.cn/Article/details/gtuiqezhjb.html

[S45] C++：lambda
来源：http://dali.c1oappe.top/Article/details/gtqlbkrtru.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.mhx1999.top/Article/details/gtyusufgpv.html

[S46] C++：函数模板
来源：http://dali.jianghu66.top/Article/details/gtgmobzknh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yongpay.top/Article/details/gtmaveqlyr.html

[S47] C++：结构化绑定遍历
来源：http://dali.snrcjt.cn/Article/details/gtlhrbqoxg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.haohaochexian.top/Article/details/gtzphqxgfb.html

[S48] C++：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gtsdfxwkje.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hywenlv.cn/Article/details/gtkgodzxwd.html

while (std::getline(in, line)) { }
来源：http://dali.sweek.top/Article/details/gtonvrnrja.html

[S49] C++：写文件
来源：http://dali.yongpay.top/Article/details/gtehzqwmdi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.meibo888.top/Article/details/gtwbeepmkr.html

[S50] C++：格式化数字
来源：http://dali.shanyushiyangtech.top/Article/details/gtklvjcmvd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gtlsmbcqyn.html

[S51] C++：显式类型转换
来源：http://dali.yanxiufei.cn/Article/details/gtaksoayxp.html

static_cast<double>(a) / b
来源：http://dali.birdmap.top/Article/details/gthnmvrbtl.html

[S52] C++：const 与 noexcept
来源：http://dali.dashuyun.cn/Article/details/gtpjzkjozf.html

int size() const noexcept { return n_; }
来源：http://dali.cheryme.top/Article/details/gtoemxwnuf.html

[S53] C++：移动语义
来源：http://dali.sufxvd.cn/Article/details/gttaenlwnc.html

std::vector<int> w = std::move(v);
来源：http://dali.hywenlv.cn/Article/details/gtaklpskjj.html

[S54] C++：异常处理
来源：http://dali.redwolf501.top/Article/details/gtdqwcgvej.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xuetiantiany.cn/Article/details/gtwgllqbmc.html

[S55] C++：结构化绑定
来源：http://dali.cheryme.top/Article/details/gtmkcfrgag.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xylfe.cn/Article/details/gtovgbroan.html

[S56] C++：optional
来源：http://dali.yonumen.top/Article/details/gtpalqiszm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sxryk.cn/Article/details/gtysnhzdcu.html

[S57] C++：编译期常量
来源：http://dali.yj202588.top/Article/details/gtksxljctf.html

constexpr int N = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gtcrxjpvid.html

[S58] C++：命名空间
来源：http://dali.jlsjyb.cn/Article/details/gtydjcfjvx.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhoulong.xyz/Article/details/gtuszuqtzk.html

[S59] C++：静态断言
来源：http://dali.feifeiyinyue.top/Article/details/gtbsdhnebh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hfpthk.cn/Article/details/gtscyxaihk.html

[S60] C++：遍历并删除元素
来源：http://dali.jinghuilouyu.cn/Article/details/gttxlhzmis.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhiwuduotai.top/Article/details/gtslgnxnha.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtxorerofm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.redwolf501.top/Article/details/gtvwkofvou.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtbkatqfza.html

[T01] Kotlin：Hello World
来源：http://dali.shuidangran.top/Article/details/gtpykjrnyl.html

println("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gtqfqoxclz.html

[T02] Kotlin：变量
来源：http://dali.jinqigfzy.top/Article/details/gtivlacnpb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.daria6918.cn/Article/details/gtzadogzxw.html

[T03] Kotlin：字符串模板
来源：http://dali.guannengcc.top/Article/details/gtdgfslatj.html

"值: $b"
来源：http://dali.nanxuanxn.top/Article/details/gtfulcaxke.html

[T04] Kotlin：空安全
来源：http://dali.hnqzz.top/Article/details/gtomfhdhze.html

val n: String? = null;  n?.length
来源：http://dali.havefunace.top/Article/details/gtyzmsoaud.html

[T05] Kotlin：when 表达式
来源：http://dali.quarkkingdee.top/Article/details/gtuujrucih.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jqgfzy.top/Article/details/gtpfckrqzg.html

[T06] Kotlin：集合映射
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmxxneoor.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.haohaochexian.top/Article/details/gtgsuuqcbr.html

[T07] Kotlin：集合过滤
来源：http://dali.snrcjt.cn/Article/details/gtiljaeafx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhengqikj.top/Article/details/gtnkzeqbga.html

[T08] Kotlin：数据类
来源：http://dali.bjfxy.top/Article/details/gtkkprqkbs.html

data class User(val name: String, val age: Int)
来源：http://dali.yangfankeji.com/Article/details/gtexlquhsx.html

[T09] Kotlin：扩展函数
来源：http://dali.wangdashe.top/Article/details/gtdinevbuu.html

fun String.exclaim() = this + "!"
来源：http://dali.shanyushiyangtech.top/Article/details/gtexwcadqq.html

[T10] Kotlin：默认参数
来源：http://dali.jinqigufen.top/Article/details/gtegcqmtvi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hammf.cn/Article/details/gtjmcrchgg.html

[T11] Kotlin：协程
来源：http://dali.fengsongda.top/Article/details/gtqklovnva.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gtnskwnxbs.html

[T12] Kotlin：解构声明
来源：http://dali.jqgfzy.top/Article/details/gtxodymrir.html

val (a, b) = Pair(1, 2)
来源：http://dali.aibaodan.cn/Article/details/gtbioxmdpk.html

[T13] Kotlin：只读 Map
来源：http://dali.hfpthk.cn/Article/details/gtyptdvcdq.html

val m = mapOf("a" to 1)
来源：http://dali.yongpay.top/Article/details/gtqgojfstp.html

[T14] Kotlin：循环
来源：http://dali.0kj1m.cn/Article/details/gtosigtppp.html

for (i in 1..10) println(i)
来源：http://dali.pycfn.com/Article/details/gtgozypikd.html

[T15] Kotlin：接口
来源：http://dali.ppjwa.cn/Article/details/gtakguydjs.html

interface Shape { fun area(): Double }
来源：http://dali.zdqjudy.top/Article/details/gtmcjeiwyk.html

[T16] Swift：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtpsinhzsy.html

print("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gttebfoutj.html

[T17] Swift：变量与常量
来源：http://dali.ehwqpu.com/Article/details/gtmnjcmqwr.html

var a = 1;  let b = 2
来源：http://dali.xinyue.icu/Article/details/gtecpvrrnr.html

[T18] Swift：字符串插值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnrveqbly.html

"值: \(b)"
来源：http://dali.yanxiufei.cn/Article/details/gtqociquex.html

[T19] Swift：可选绑定
来源：http://dali.wangshuangyany.cn/Article/details/gtnrlttnrg.html

if let n = opt { print(n) }
来源：http://dali.smart0.xyz/Article/details/gtxwbfwhdc.html

[T20] Swift：数组操作
来源：http://dali.dashuyun.cn/Article/details/gttjvnbqfp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.guowangkeji.top/Article/details/gtaoscmsvo.html

[T21] Swift：遍历
来源：http://dali.tanke756.top/Article/details/gtkkafkalz.html

for x in a { print(x) }
来源：http://dali.haohaochexian.top/Article/details/gticpdcids.html

[T22] Swift：字典
来源：http://dali.aibaodan.cn/Article/details/gtcpkfsajc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hongshengwenyu.top/Article/details/gtkqiqmkyh.html

[T23] Swift：函数
来源：http://dali.xinyue.icu/Article/details/gtmghlufah.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zdqjudy.top/Article/details/gtfbyzgoxa.html

[T24] Swift：闭包
来源：http://dali.yvedp.cn/Article/details/gtnpkvskju.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cucudq.cn/Article/details/gtupncinuy.html

[T25] Swift：结构体
来源：http://dali.ybcxt.top/Article/details/gtbnihinfu.html

struct P { var x: Int }
来源：http://dali.guowangkeji.top/Article/details/gtllaxcsds.html

[T26] Swift：类与重写
来源：http://dali.chenzaomai.com/Article/details/gtwifktrvr.html

class A: Base { override func f() {} }
来源：http://dali.gzhubu.top/Article/details/gthmvmmfto.html

[T27] Swift：错误处理
来源：http://dali.tianlin.xyz/Article/details/gtujijhize.html

do { try f() } catch { print(error) }
来源：http://dali.cheryme.top/Article/details/gtmvxbatzd.html

[T28] Swift：枚举
来源：http://dali.xylfe.cn/Article/details/gtlsvqvpxf.html

enum Color { case red, green }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwaidqbqw.html

[T29] Swift：guard 提前返回
来源：http://dali.gaohongyu789.top/Article/details/gttbhyevlf.html

guard let x = opt else { return }
来源：http://dali.pycfn.com/Article/details/gtchxbznct.html

[T30] Swift：协议
来源：http://dali.yj20258.top/Article/details/gthuswlvua.html

protocol Shape { func area() -> Double }
来源：http://dali.chenjidiqi.icu/Article/details/gtlfzlvocy.html

[T31] Lua：Hello World
来源：http://dali.sxryk.cn/Article/details/gtskghvbwu.html

print("Hello")
来源：http://dali.meibo888.top/Article/details/gtbspbrbaq.html

[T32] Lua：局部变量
来源：http://dali.tanke756.top/Article/details/gtxooonsjc.html

local a = 1
来源：http://dali.shangyingyoupin.top/Article/details/gtiilyvchf.html

[T33] Lua：表（数组）
来源：http://dali.sysykeji.top/Article/details/gtxkbrxsjm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenlongwang.top/Article/details/gtmvhyplqh.html

[T34] Lua：遍历表
来源：http://dali.zhixingplan.top/Article/details/gtbjmyqcnp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zdqjudy.top/Article/details/gtbhfdaujv.html

[T35] Lua：字典表
来源：http://dali.jyoumei.cn/Article/details/gtwhaejvcg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jqgufenzy.top/Article/details/gtcicebyfe.html

[T36] Lua：函数
来源：http://dali.nanxinkj.top/Article/details/gtbkdiuwfe.html

function add(a, b) return a + b end
来源：http://dali.fzhhl.top/Article/details/gtwmtbsoee.html

[T37] Lua：字符串拼接
来源：http://dali.nanxinkj.top/Article/details/gtzljxdfqv.html

"a" .. "b"
来源：http://dali.0kj1m.cn/Article/details/gtyyowxmil.html

[T38] Lua：条件
来源：http://dali.snrcjt.cn/Article/details/gtapfnsbzv.html

if x > 0 then print("正") end
来源：http://dali.birdmap.top/Article/details/gtbaatouux.html

[T39] Lua：模式匹配
来源：http://dali.zdqjudy.top/Article/details/gtnwmsvrsx.html

string.find(s, "%d+")
来源：http://dali.hnxiangtu.top/Article/details/gtwnqymtga.html

[T40] Lua：元表
来源：http://dali.hfpthk.cn/Article/details/gtxglbilws.html

setmetatable({}, { __index = base })
来源：http://dali.hongshengwenyu.top/Article/details/gthgjrijhj.html

[T41] Perl：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtdzdsvbep.html

print "Hello\n";
来源：http://dali.chenzaomai.com/Article/details/gtjxzaefna.html

[T42] Perl：变量类型
来源：http://dali.iojbl.cn/Article/details/gtndqrgnbq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.chenlongwang.top/Article/details/gtyxozycpl.html

[T43] Perl：字符串插值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtydymbbho.html

"值: $a"
来源：http://dali.ehwqpu.com/Article/details/gtjnnjrfnz.html

[T44] Perl：条件
来源：http://dali.zhiwuduotai.top/Article/details/gtljvwrmvh.html

if ($a > 0) { print "正"; }
来源：http://dali.hnxiangtu.top/Article/details/gtkgduskkn.html

[T45] Perl：数组遍历
来源：http://dali.tianlin.xyz/Article/details/gttveanqho.html

for my $x (@arr) { print $x; }
来源：http://dali.fengsongda.top/Article/details/gtkkklzsrn.html

[T46] Perl：哈希操作
来源：http://dali.sweek.top/Article/details/gtxwtxcmqv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ehwqpu.com/Article/details/gtmkascemn.html

[T47] Perl：正则捕获
来源：http://dali.shangyingyoupin.top/Article/details/gtpoacpzho.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jianghu66.top/Article/details/gtjoueiclw.html

[T48] Perl：正则替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmzdxaxnq.html

$s =~ s/old/new/g;
来源：http://dali.yj202588.top/Article/details/gtvceciqvl.html

[T49] Perl：函数
来源：http://dali.fengsongda.top/Article/details/gtgtxmlper.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtekkbkmxi.html

[T50] Perl：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtkliqmlqa.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gotoacloud.top/Article/details/gtcookwzwn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yvedp.cn/Article/details/gtfwzmpavw.html

[T51] Scala：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtxjqrfgbf.html

println("Hello")
来源：http://dali.zdqjudy.top/Article/details/gtaegicism.html

[T52] Scala：变量
来源：http://dali.shangyingyoupin.top/Article/details/gtzhnzwlfx.html

val a = 1;  var b = 2
来源：http://dali.svipenyu.cn/Article/details/gtaizugdzw.html

[T53] Scala：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gtlhinpgtj.html

s"值: $b"
来源：http://dali.snrcjt.cn/Article/details/gtatkadori.html

[T54] Scala：集合映射
来源：http://dali.gotoacloud.top/Article/details/gtfivebidy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhixingplan.top/Article/details/gtswqekguq.html

[T55] Scala：集合过滤
来源：http://dali.yueranfly.top/Article/details/gtjvepzzjv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yvedp.cn/Article/details/gtkauupeqm.html

[T56] Scala：样例类
来源：http://dali.wangdashe.top/Article/details/gtuentgfrv.html

case class User(name: String, age: Int)
来源：http://dali.jiagoushi.top/Article/details/gtuqkcrwiq.html

[T57] Scala：模式匹配
来源：http://dali.zhengqikj.top/Article/details/gtwpdxgkdk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.pycfn.com/Article/details/gtxfkkejjd.html

[T58] Scala：函数定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgjthcjbm.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shanyushiyangtech.top/Article/details/gttakrdnbq.html

[T59] Scala：循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtnhqpwcqf.html

for (i <- 1 to 10) println(i)
来源：http://dali.cheryme.top/Article/details/gtddpuxlju.html

[T60] Scala：折叠
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsqxuimis.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sufxvd.cn/Article/details/gtzjulniew.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gttpdxdfyf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.redwolf501.top/Article/details/gtmjmvsnss.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtgnpdyeuq.html

[U01] Py：创建虚拟环境
来源：http://dali.tanke756.top/Article/details/gtyrbknckv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hywenlv.cn/Article/details/gtbbqueozf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.kuanghao11.cn/Article/details/gtzzchpzks.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yj20258.top/Article/details/gtoehpkyyo.html

[U03] Py：加载 .env 配置
来源：http://dali.fzhhl.top/Article/details/gtvowuxboh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhaomingkeji.xyz/Article/details/gttwqjdbcy.html

[U04] Py：变量调试打印
来源：http://dali.hnqzz.top/Article/details/gtueqcjhbi.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.9152youxi.cn/Article/details/gtkegxziqo.html

[U05] Py：列表去重且保序
来源：http://dali.yj20258888.top/Article/details/gtnxnjuteg.html

list(dict.fromkeys(arr))
来源：http://dali.yonumen.top/Article/details/gtpufvmcqc.html

[U06] Py：合并两个字典
来源：http://dali.jiagoushi.top/Article/details/gtggjokueq.html

{**a, **b}
来源：http://dali.zhongyouzk.top/Article/details/gtfjadnljf.html

[U07] Py：反转字典键值
来源：http://dali.sysykeji.top/Article/details/gtwbmmcwza.html

{v: k for k, v in d.items()}
来源：http://dali.daxiang520.top/Article/details/gtujmojuze.html

[U08] Py：展平二维列表
来源：http://dali.cheryme.top/Article/details/gtxunojdyl.html

[y for x in nested for y in x]
来源：http://dali.ydzc1.top/Article/details/gtorrzzdmq.html

[U09] Py：字典取最大值的键
来源：http://dali.smart0.xyz/Article/details/gtjkshzhyu.html

max(d, key=d.get)
来源：http://dali.pengpengdd.cyou/Article/details/gtrabbhibm.html

[U10] Py：按值排序字典
来源：http://dali.gzhubu.top/Article/details/gtwtxocnxi.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhixingplan.top/Article/details/gticdnyswo.html

[U11] Py：生成器表达式
来源：http://dali.yangfankeji.com/Article/details/gtcuijtqgh.html

(x * 2 for x in arr)
来源：http://dali.jinqigufen.top/Article/details/gtlpviewat.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hnxiangtu.top/Article/details/gtokwnixyx.html

Counter(arr).most_common(3)
来源：http://dali.zhoulong.xyz/Article/details/gtmndbfsqr.html

[U13] Py：固定长度队列
来源：http://dali.zhengqikj.top/Article/details/gtdgzrbosr.html

deque(maxlen=10)
来源：http://dali.yuxming.cn/Article/details/gtejmlbaug.html

[U14] Py：分组收集到列表
来源：http://dali.zhongyouzk.top/Article/details/gtpxdtgvzk.html

defaultdict(list)
来源：http://dali.svipenyu.cn/Article/details/gtjlywmsjd.html

[U15] Py：高精度计时
来源：http://dali.daria6918.cn/Article/details/gtluprwuob.html

t = time.perf_counter()
来源：http://dali.bjfxy.top/Article/details/gtwgakkxuf.html

[U16] Py：命令行参数解析
来源：http://dali.hongshengwenyu.top/Article/details/gtocywlnxj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hnxiangtu.top/Article/details/gtxvxbrvbo.html


<!-- 参考信息 -->