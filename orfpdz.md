代发 wailian999

export PATH="$HOME/bin:$PATH"
来源：http://dali.gotoacloud.top/Article/details/gtadnebsnq.html

[R76] 使用临时文件
来源：http://dali.zhoulong.xyz/Article/details/gtzsnucgfn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hysaishi.cn/Article/details/gtwhodybrh.html

[R77] 读取用户输入
来源：http://dali.9152youxi.cn/Article/details/gtiodvxbrn.html

read -rp "请输入: " ans
来源：http://dali.xziqi.cn/Article/details/gtexmsnifn.html

[R78] 交互式菜单
来源：http://dali.zhoulong.xyz/Article/details/gthuesboeo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.0kj1m.cn/Article/details/gtneumkeun.html

[R79] 解析命令行选项
来源：http://dali.daria6918.cn/Article/details/gtxqtaziij.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.316326.xyz/Article/details/gtmmszkdzi.html

[R80] 查看脚本执行耗时
来源：http://dali.zycfv.cn/Article/details/gtrzermbmv.html

time ./run.sh
来源：http://dali.0kj1m.cn/Article/details/gttgngxmci.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtdhlvchne.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gthxendqwg.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtsorgtkee.html

[S01] C：Hello World
来源：http://dali.xuanzx.com/Article/details/gtgryefqgk.html

#include <stdio.h>
来源：http://dali.sxryk.cn/Article/details/gtwvvukucd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.pycfn.com/Article/details/gtwhoguktb.html

[S02] C：变量与格式化输出
来源：http://dali.gotoacloud.top/Article/details/gtodtxczxw.html

int a = 10; printf("%d\n", a);
来源：http://dali.yuxming.cn/Article/details/gtwleqxcds.html

[S03] C：读入整数
来源：http://dali.hongshengwenyu.top/Article/details/gtbycxkmei.html

int x; scanf("%d", &x);
来源：http://dali.cashguo.top/Article/details/gtdmvccnpj.html

[S04] C：字符串复制
来源：http://dali.jiagoushi.top/Article/details/gtknziyopy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.guannengcc.top/Article/details/gtfqylaonn.html

[S05] C：字符串长度
来源：http://dali.birdmap.top/Article/details/gtqfqkasoi.html

strlen(s)
来源：http://dali.hywenlv.cn/Article/details/gtyspqjtnw.html

[S06] C：字符串比较
来源：http://dali.mhx1999.top/Article/details/gtsjtzltgw.html

strcmp(a, b) == 0
来源：http://dali.hywenlv.cn/Article/details/gtdvericts.html

[S07] C：数组遍历求和
来源：http://dali.yangfankeji.com/Article/details/gtdupzipkk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yj202588.top/Article/details/gtyjywzyxd.html

[S08] C：动态内存分配与释放
来源：http://dali.jqgufenzy.top/Article/details/gtaseoftit.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.fzhhl.top/Article/details/gtimiwvftc.html

[S09] C：结构体定义与初始化
来源：http://dali.dashuyun.cn/Article/details/gtygbaegqg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cheryme.top/Article/details/gtqhgsifbl.html

[S10] C：指针与解引用
来源：http://dali.ppjwa.cn/Article/details/gtsqyqqduf.html

int *p = &a;  *p = 5;
来源：http://dali.ydzc1.top/Article/details/gtjdlwdlxf.html

[S11] C：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtmhfeatxe.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gogol.net.cn/Article/details/gtybjakfxr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shzxlz.cn/Article/details/gtwrpcjawu.html

fclose(f);
来源：http://dali.xylfe.cn/Article/details/gttezbqnnq.html

[S12] C：写文件
来源：http://dali.gaohongyu789.top/Article/details/gtdzzhllra.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.havefunace.top/Article/details/gtutbjwnzb.html

[S13] C：宏定义
来源：http://dali.9152youxi.cn/Article/details/gtaklwklgh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinqigufen.top/Article/details/gtetquznjn.html

[S14] C：枚举
来源：http://dali.daria6918.cn/Article/details/gtxlwopqen.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hongshengwenyu.top/Article/details/gtrtlxprrr.html

[S15] C：类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaonqempb.html

(double) a / b
来源：http://dali.yuanzhike.top/Article/details/gteuclrige.html

[S16] C：位操作置位
来源：http://dali.jinqigufen.top/Article/details/gtfkcnkgeh.html

x |= (1 << 3);
来源：http://dali.haohaochexian.top/Article/details/gtohlhxrhe.html

[S17] C：安全拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gtkglsdzuh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yuanzhike.top/Article/details/gtbasftqlj.html

[S18] C：命令行参数
来源：http://dali.tian-w.cn/Article/details/gtnluuuijk.html

int main(int argc, char **argv)
来源：http://dali.tian-w.cn/Article/details/gtkakebcvd.html

[S19] C：快速排序
来源：http://dali.sxryk.cn/Article/details/gtbcihmoay.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ppjwa.cn/Article/details/gtvopblqwq.html

[S20] C：二分查找
来源：http://dali.zhiwuduotai.top/Article/details/gtpwahdufk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.guannengcc.top/Article/details/gtnrnlbalv.html

[S21] C：字符类别判断
来源：http://dali.ydzc1.top/Article/details/gtlodvmuma.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hammf.cn/Article/details/gtkpbeqcqj.html

[S22] C：字符串转数字
来源：http://dali.hysaishi.cn/Article/details/gtljosfnai.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnxuadcvw.html

[S23] C：随机数
来源：http://dali.gzhubu.top/Article/details/gtbjrolbjd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.nanxuanxn.top/Article/details/gtjjhldnld.html

[S24] C：获取本地时间
来源：http://dali.meibo888.top/Article/details/gtwikflcdi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gzhubu.top/Article/details/gtowevtdax.html

[S25] C：内存拷贝
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxidumspn.html

memcpy(dst, src, n);
来源：http://dali.0kj1m.cn/Article/details/gtgmfmqluj.html

[S26] C：内存清零
来源：http://dali.c1oappe.top/Article/details/gteyegxnaa.html

memset(a, 0, sizeof a);
来源：http://dali.jinqigfzy.top/Article/details/gtudhmrnem.html

[S27] C：定义常量
来源：http://dali.cdnleiting.top/Article/details/gtihzyzxax.html

const double PI = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gtbopaaqlu.html

[S28] C：静态变量
来源：http://dali.dianchejie.cn/Article/details/gtbhrtcuzo.html

static int counter = 0;
来源：http://dali.hysaishi.cn/Article/details/gtzpfedwmm.html

[S29] C：变参函数
来源：http://dali.vqdsnc.cn/Article/details/gtxcitnali.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.c1oappe.top/Article/details/gtkskklndi.html

[S30] C：头文件保护
来源：http://dali.hnqzz.top/Article/details/gtubamvtmj.html

#ifndef X_H
来源：http://dali.mhx1999.top/Article/details/gtasxoldml.html

#define X_H
来源：http://dali.pengpengdd.cyou/Article/details/gtvxepjvxl.html

#endif
来源：http://dali.meibo888.top/Article/details/gtllbbwgkl.html

[S31] C++：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtdjnrejeh.html

#include <iostream>
来源：http://dali.ivvv.top/Article/details/gtelrkznfv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkrbtvvgp.html

[S32] C++：字符串
来源：http://dali.zhoulong.xyz/Article/details/gtvmtprvnb.html

std::string s = "hi";  s += "!";
来源：http://dali.0kj1m.cn/Article/details/gtsdwcjluz.html

[S33] C++：vector 增删
来源：http://dali.yueranfly.top/Article/details/gtwgqdfoji.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtshjkplab.html

[S34] C++：遍历 vector
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfmnfltvd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhongyouzk.top/Article/details/gtnfzlxtzy.html

[S35] C++：map
来源：http://dali.andypj.xyz/Article/details/gtvktheire.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtxouajpcg.html

[S36] C++：unordered_map
来源：http://dali.chenjidiqi.icu/Article/details/gtvnyvrail.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nwbrower.top/Article/details/gtfuhoawjm.html

[S37] C++：set
来源：http://dali.yangfankeji.com/Article/details/gtqzowocri.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xuanzx.com/Article/details/gtluieguiw.html

[S38] C++：排序
来源：http://dali.shuidangran.top/Article/details/gttwwgvmyx.html

std::sort(v.begin(), v.end());
来源：http://dali.316326.xyz/Article/details/gtfldchcka.html

[S39] C++：自定义比较器排序
来源：http://dali.birdmap.top/Article/details/gtxzyfmrjh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hywenlv.cn/Article/details/gtnlcbrsdg.html

[S40] C++：查找元素
来源：http://dali.xziqi.cn/Article/details/gtgxwwjzdz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqskekiba.html

[S41] C++：类与构造函数
来源：http://dali.bjfxy.top/Article/details/gtzayggxox.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sufxvd.cn/Article/details/gtankzxgsm.html

[S42] C++：继承与虚函数
来源：http://dali.daria6918.cn/Article/details/gthovmiwcv.html

class B : public Base { public: void f() override {} };
来源：http://dali.cdnleiting.top/Article/details/gtqwvuyrng.html

[S43] C++：智能指针
来源：http://dali.yonumen.top/Article/details/gtcfiwtyew.html

auto p = std::make_unique<int>(5);
来源：http://dali.svipenyu.cn/Article/details/gtmmqzkmia.html

[S44] C++：引用传参
来源：http://dali.0kj1m.cn/Article/details/gtrhycntoi.html

void inc(int &x) { ++x; }
来源：http://dali.yuanzhike.top/Article/details/gtruvyrxzl.html

[S45] C++：lambda
来源：http://dali.zhiwuduotai.top/Article/details/gtxmnmswgd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nanxuanxn.top/Article/details/gtabcpfslm.html

[S46] C++：函数模板
来源：http://dali.chenzaomai.com/Article/details/gtydssjbwb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cheryme.top/Article/details/gtywmunjwm.html

[S47] C++：结构化绑定遍历
来源：http://dali.vqdsnc.cn/Article/details/gtqtppgoeq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sweek.top/Article/details/gtdiurbimz.html

[S48] C++：逐行读文件
来源：http://dali.ydzc1.top/Article/details/gtomlgughq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ppjwa.cn/Article/details/gtibxacpfm.html

while (std::getline(in, line)) { }
来源：http://dali.wangshuangyany.cn/Article/details/gtvspqlocl.html

[S49] C++：写文件
来源：http://dali.jyoumei.cn/Article/details/gtibvunlpq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jqgfzy.top/Article/details/gtytbjukhd.html

[S50] C++：格式化数字
来源：http://dali.jinghuilouyu.cn/Article/details/gtrzbcnhiz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.wangdashe.top/Article/details/gtllhnxssw.html

[S51] C++：显式类型转换
来源：http://dali.hfpthk.cn/Article/details/gtghnjdvjd.html

static_cast<double>(a) / b
来源：http://dali.pengpengdd.cyou/Article/details/gtgfyizevl.html

[S52] C++：const 与 noexcept
来源：http://dali.0kj1m.cn/Article/details/gtsdsbkxph.html

int size() const noexcept { return n_; }
来源：http://dali.birdmap.top/Article/details/gtvvobvddl.html

[S53] C++：移动语义
来源：http://dali.0kj1m.cn/Article/details/gtjylejlvg.html

std::vector<int> w = std::move(v);
来源：http://dali.gotoacloud.top/Article/details/gtciyiuoto.html

[S54] C++：异常处理
来源：http://dali.xinyue.icu/Article/details/gtdbiwpqhm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.pengpengdd.cyou/Article/details/gtggakphfe.html

[S55] C++：结构化绑定
来源：http://dali.vqdsnc.cn/Article/details/gtlojbcrgk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinqigufen.top/Article/details/gtqefpoccu.html

[S56] C++：optional
来源：http://dali.yj20258888.top/Article/details/gtkzfliiuf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwnskieak.html

[S57] C++：编译期常量
来源：http://dali.tanke756.top/Article/details/gtvvuxgwsb.html

constexpr int N = 10;
来源：http://dali.jqgufenzy.top/Article/details/gtjzcdkude.html

[S58] C++：命名空间
来源：http://dali.chenjidiqi.icu/Article/details/gttpsvknen.html

namespace ns { int f() { return 1; } }
来源：http://dali.nanxuanxn.top/Article/details/gtlrqrddgz.html

[S59] C++：静态断言
来源：http://dali.zhiwuduotai.top/Article/details/gtgmdzcnla.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gtlfhxoaqm.html

[S60] C++：遍历并删除元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjdizwhhp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xuanzx.com/Article/details/gtsskeilxx.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtcgfoegbe.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangshuangyany.cn/Article/details/gtitdwvunm.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtsmctbmnn.html

[T01] Kotlin：Hello World
来源：http://dali.xziqi.cn/Article/details/gtaebgloxd.html

println("Hello")
来源：http://dali.ivvv.top/Article/details/gtqrvsfbvu.html

[T02] Kotlin：变量
来源：http://dali.sufxvd.cn/Article/details/gtnsadndjq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.meibo888.top/Article/details/gtzygdswmm.html

[T03] Kotlin：字符串模板
来源：http://dali.jinqigfzy.top/Article/details/gtyjnxgtxt.html

"值: $b"
来源：http://dali.jinqigfzy.top/Article/details/gtttrvngnb.html

[T04] Kotlin：空安全
来源：http://dali.cheryme.top/Article/details/gtuiockphp.html

val n: String? = null;  n?.length
来源：http://dali.shangyingyoupin.top/Article/details/gtvlxqgtpa.html

[T05] Kotlin：when 表达式
来源：http://dali.zhengqikj.top/Article/details/gtvmsvhxvt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jlsjyb.cn/Article/details/gtzbupiwve.html

[T06] Kotlin：集合映射
来源：http://dali.redwolf501.top/Article/details/gtitvvjmkn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.andypj.xyz/Article/details/gthdvhnkul.html

[T07] Kotlin：集合过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gtitvwdpgm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gzhubu.top/Article/details/gtnqiqzcon.html

[T08] Kotlin：数据类
来源：http://dali.andypj.xyz/Article/details/gtxpvlddvh.html

data class User(val name: String, val age: Int)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtesoukzpw.html

[T09] Kotlin：扩展函数
来源：http://dali.gogol.net.cn/Article/details/gtmtixibcq.html

fun String.exclaim() = this + "!"
来源：http://dali.vqdsnc.cn/Article/details/gtfcesgvpa.html

[T10] Kotlin：默认参数
来源：http://dali.ybcxt.top/Article/details/gtlrnwscjy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hfpthk.cn/Article/details/gtgvqgmksz.html

[T11] Kotlin：协程
来源：http://dali.aizwys.cn/Article/details/gthbbfljwq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shangyingyoupin.top/Article/details/gtfxsgbhye.html

[T12] Kotlin：解构声明
来源：http://dali.shanyushiyangtech.top/Article/details/gtsmrhqtdf.html

val (a, b) = Pair(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gtrhzndacc.html

[T13] Kotlin：只读 Map
来源：http://dali.cdnleiting.top/Article/details/gtocwwkyil.html

val m = mapOf("a" to 1)
来源：http://dali.9152youxi.cn/Article/details/gtwysgwskj.html

[T14] Kotlin：循环
来源：http://dali.shuidangran.top/Article/details/gtfepzwuns.html

for (i in 1..10) println(i)
来源：http://dali.jiagoushi.top/Article/details/gtbkxoidby.html

[T15] Kotlin：接口
来源：http://dali.hongshengwenyu.top/Article/details/gtmectuavd.html

interface Shape { fun area(): Double }
来源：http://dali.havefunace.top/Article/details/gtpkvudsjz.html

[T16] Swift：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtxptazuba.html

print("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsxljcdrc.html

[T17] Swift：变量与常量
来源：http://dali.cheryme.top/Article/details/gtjbvvcjvd.html

var a = 1;  let b = 2
来源：http://dali.aibaodan.cn/Article/details/gtejlxdnui.html

[T18] Swift：字符串插值
来源：http://dali.bjfxy.top/Article/details/gthsweqffa.html

"值: \(b)"
来源：http://dali.xuanzx.com/Article/details/gtcrswkkvp.html

[T19] Swift：可选绑定
来源：http://dali.redwolf501.top/Article/details/gtxuxxzttd.html

if let n = opt { print(n) }
来源：http://dali.sufxvd.cn/Article/details/gtzzgbllnt.html

[T20] Swift：数组操作
来源：http://dali.ybcxt.top/Article/details/gtdnvflddt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.c1oappe.top/Article/details/gtwgudqwee.html

[T21] Swift：遍历
来源：http://dali.gaohongyu789.top/Article/details/gtkzcvcxzi.html

for x in a { print(x) }
来源：http://dali.shzxlz.cn/Article/details/gtuhlsdrww.html

[T22] Swift：字典
来源：http://dali.nanxuanxn.top/Article/details/gtlpvmeodk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.bjfxy.top/Article/details/gthdgjjyuc.html

[T23] Swift：函数
来源：http://dali.zhiwuduotai.top/Article/details/gthbjzdwdc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhoulong.xyz/Article/details/gtmnbxjeum.html

[T24] Swift：闭包
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqbgiswyf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sufxvd.cn/Article/details/gtfgatwcdz.html

[T25] Swift：结构体
来源：http://dali.guannengcc.top/Article/details/gtvxhsyfon.html

struct P { var x: Int }
来源：http://dali.wangshuangyany.cn/Article/details/gtmqxenohj.html

[T26] Swift：类与重写
来源：http://dali.c1oappe.top/Article/details/gtdcojbekd.html

class A: Base { override func f() {} }
来源：http://dali.zhixingplan.top/Article/details/gtdpmwxglv.html

[T27] Swift：错误处理
来源：http://dali.shuidangran.top/Article/details/gtqqcxdiwk.html

do { try f() } catch { print(error) }
来源：http://dali.gaohongyu789.top/Article/details/gteacqmhda.html

[T28] Swift：枚举
来源：http://dali.316326.xyz/Article/details/gtmazqaeol.html

enum Color { case red, green }
来源：http://dali.meibo888.top/Article/details/gtkhejyjgp.html

[T29] Swift：guard 提前返回
来源：http://dali.cqqwz.cn/Article/details/gtgommyntf.html

guard let x = opt else { return }
来源：http://dali.hfpthk.cn/Article/details/gtnfzhckhg.html

[T30] Swift：协议
来源：http://dali.ehwqpu.com/Article/details/gtguvfsmqa.html

protocol Shape { func area() -> Double }
来源：http://dali.pengpengdd.cyou/Article/details/gtwztquoju.html

[T31] Lua：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtakekitfv.html

print("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gtzdqxlynl.html

[T32] Lua：局部变量
来源：http://dali.tian-w.cn/Article/details/gtuptswerr.html

local a = 1
来源：http://dali.gotoacloud.top/Article/details/gtxylfgxfp.html

[T33] Lua：表（数组）
来源：http://dali.xylfe.cn/Article/details/gtfcywtcxl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.smart0.xyz/Article/details/gtbvepzsoc.html

[T34] Lua：遍历表
来源：http://dali.gotoacloud.top/Article/details/gtnbnsoxhw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.daria6918.cn/Article/details/gtzujjmwoo.html

[T35] Lua：字典表
来源：http://dali.gogol.net.cn/Article/details/gtwdnpetts.html

local d = { a = 1 };  d.b = 2
来源：http://dali.wangshuangyany.cn/Article/details/gtmgzgndbu.html

[T36] Lua：函数
来源：http://dali.jianghu66.top/Article/details/gtttbaheud.html

function add(a, b) return a + b end
来源：http://dali.ehwqpu.com/Article/details/gtudyfiizu.html

[T37] Lua：字符串拼接
来源：http://dali.shzxlz.cn/Article/details/gtnninptuv.html

"a" .. "b"
来源：http://dali.meibo888.top/Article/details/gtpjcilnbb.html

[T38] Lua：条件
来源：http://dali.yuxming.cn/Article/details/gtmfmuoxnf.html

if x > 0 then print("正") end
来源：http://dali.shzxlz.cn/Article/details/gtaufkqkch.html

[T39] Lua：模式匹配
来源：http://dali.hammf.cn/Article/details/gtveyortce.html

string.find(s, "%d+")
来源：http://dali.yuxming.cn/Article/details/gtgejhqlte.html

[T40] Lua：元表
来源：http://dali.sxryk.cn/Article/details/gtvtezsdja.html

setmetatable({}, { __index = base })
来源：http://dali.dianchejie.cn/Article/details/gttgqctgwk.html

[T41] Perl：Hello World
来源：http://dali.cdnleiting.top/Article/details/gteevjnkeq.html

print "Hello\n";
来源：http://dali.yj20258888.top/Article/details/gtbzyzcnhc.html

[T42] Perl：变量类型
来源：http://dali.wangshuangyany.cn/Article/details/gtzcogsubf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gtncwpkbru.html

[T43] Perl：字符串插值
来源：http://dali.yangfankeji.com/Article/details/gtdguzgjtw.html

"值: $a"
来源：http://dali.fengsongda.top/Article/details/gtqrqpszwj.html

[T44] Perl：条件
来源：http://dali.yongpay.top/Article/details/gtizsxzdfp.html

if ($a > 0) { print "正"; }
来源：http://dali.316326.xyz/Article/details/gtgdawzayv.html

[T45] Perl：数组遍历
来源：http://dali.bjfxy.top/Article/details/gtycbgxdca.html

for my $x (@arr) { print $x; }
来源：http://dali.aizwys.cn/Article/details/gtiyroopuw.html

[T46] Perl：哈希操作
来源：http://dali.jqgfzy.top/Article/details/gtfzgrvtib.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhongyouzk.top/Article/details/gtlkiprqeg.html

[T47] Perl：正则捕获
来源：http://dali.zycfv.cn/Article/details/gtlnycqwyz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ybcxt.top/Article/details/gtnpnhczfk.html

[T48] Perl：正则替换
来源：http://dali.nanxinkj.top/Article/details/gtuosugjga.html

$s =~ s/old/new/g;
来源：http://dali.jqgufenzy.top/Article/details/gtqaqdlzkc.html

[T49] Perl：函数
来源：http://dali.9152youxi.cn/Article/details/gtfflkwukw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gtekpjoosn.html

[T50] Perl：逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gtktzyefuo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hongshengwenyu.top/Article/details/gtubanqxma.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cheryme.top/Article/details/gtifmbityd.html

[T51] Scala：Hello World
来源：http://dali.cheryme.top/Article/details/gtxnmrmmsx.html

println("Hello")
来源：http://dali.pycfn.com/Article/details/gtzillucrs.html

[T52] Scala：变量
来源：http://dali.yanxiufei.cn/Article/details/gthsdbwjxm.html

val a = 1;  var b = 2
来源：http://dali.xinyue.icu/Article/details/gtkeyepfip.html

[T53] Scala：字符串插值
来源：http://dali.xuanzx.com/Article/details/gtztzxemtd.html

s"值: $b"
来源：http://dali.shuidangran.top/Article/details/gtmwyvyeea.html

[T54] Scala：集合映射
来源：http://dali.gogol.net.cn/Article/details/gtkyzxisbp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hywenlv.cn/Article/details/gtzglqrttd.html

[T55] Scala：集合过滤
来源：http://dali.zdqjudy.top/Article/details/gtgzcflhlu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ivvv.top/Article/details/gttvilfiae.html

[T56] Scala：样例类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqvhmnvni.html

case class User(name: String, age: Int)
来源：http://dali.hongshengwenyu.top/Article/details/gtdnjrhupz.html

[T57] Scala：模式匹配
来源：http://dali.c1oappe.top/Article/details/gtnnekglpk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jianghu66.top/Article/details/gtzuhpffxl.html

[T58] Scala：函数定义
来源：http://dali.chenlongwang.top/Article/details/gtubkicapd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinqigufen.top/Article/details/gtkzjhkysm.html

[T59] Scala：循环
来源：http://dali.jinqigfzy.top/Article/details/gtcuihbmyb.html

for (i <- 1 to 10) println(i)
来源：http://dali.cheryme.top/Article/details/gtldaggoye.html

[T60] Scala：折叠
来源：http://dali.hnxiangtu.top/Article/details/gtujyemztz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yj20258.top/Article/details/gteykkdqvi.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gttpwycpsx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.fzhhl.top/Article/details/gtcewbqoyp.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtxwvhnhtq.html

[U01] Py：创建虚拟环境
来源：http://dali.daxiang520.top/Article/details/gtttnalosc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.dianchejie.cn/Article/details/gtrnsaujcx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hammf.cn/Article/details/gtmgrtuksb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.iojbl.cn/Article/details/gtnabmucow.html

[U03] Py：加载 .env 配置
来源：http://dali.ydzc1.top/Article/details/gttrgdzpeb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.sysykeji.top/Article/details/gthbieypxx.html

[U04] Py：变量调试打印
来源：http://dali.zhongyouzk.top/Article/details/gtgvxipbyp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.vqdsnc.cn/Article/details/gtzcufrpsl.html

[U05] Py：列表去重且保序
来源：http://dali.tian-w.cn/Article/details/gtkdetfsvu.html

list(dict.fromkeys(arr))
来源：http://dali.zhoulong.xyz/Article/details/gtwlovaiuy.html

[U06] Py：合并两个字典
来源：http://dali.ppjwa.cn/Article/details/gtdiyagvjt.html

{**a, **b}
来源：http://dali.iojbl.cn/Article/details/gtrwdjeipl.html

[U07] Py：反转字典键值
来源：http://dali.dashuyun.cn/Article/details/gtepxnwyss.html

{v: k for k, v in d.items()}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzsdtmlkc.html

[U08] Py：展平二维列表
来源：http://dali.pengpengdd.cyou/Article/details/gtgovqzkwk.html

[y for x in nested for y in x]
来源：http://dali.birdmap.top/Article/details/gtpzfmtese.html

[U09] Py：字典取最大值的键
来源：http://dali.jinyuanbaomall.cn/Article/details/gtolqstmli.html

max(d, key=d.get)
来源：http://dali.yangfankeji.com/Article/details/gtiqeztwvi.html

[U10] Py：按值排序字典
来源：http://dali.ydzc1.top/Article/details/gtzacfdnbj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cdnleiting.top/Article/details/gtrvgxpado.html

[U11] Py：生成器表达式
来源：http://dali.yuanzhike.top/Article/details/gtadynrgev.html

(x * 2 for x in arr)
来源：http://dali.yuanzhike.top/Article/details/gtnmyvxuwg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtuvkwovap.html

Counter(arr).most_common(3)
来源：http://dali.dianchejie.cn/Article/details/gtrzknvlco.html

[U13] Py：固定长度队列
来源：http://dali.gotoacloud.top/Article/details/gtvtcvhzvh.html

deque(maxlen=10)
来源：http://dali.pycfn.com/Article/details/gtmfesqzvq.html

[U14] Py：分组收集到列表
来源：http://dali.bjfxy.top/Article/details/gtyjyrpddk.html

defaultdict(list)
来源：http://dali.fengsongda.top/Article/details/gtzlabcqrh.html

[U15] Py：高精度计时
来源：http://dali.tian-w.cn/Article/details/gtbecucabr.html

t = time.perf_counter()
来源：http://dali.yanxiufei.cn/Article/details/gtrdbphhms.html

[U16] Py：命令行参数解析
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmrxbvifr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.aibaodan.cn/Article/details/gtopaajgjz.html


<!-- 参考信息 -->