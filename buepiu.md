代发 wailian999

split -l 1000 big.log part_
来源：http://dali.yj20258.top/Article/details/gtehejeouj.html

[R74] 批量重命名
来源：http://dali.hnxiangtu.top/Article/details/gtuaiplnug.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtltwwvxzw.html

[R75] 导出环境变量
来源：http://dali.cdnleiting.top/Article/details/gtjfftwlfa.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shzxlz.cn/Article/details/gtzrdrmitm.html

[R76] 使用临时文件
来源：http://dali.shangyingyoupin.top/Article/details/gtjljxrlos.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgfzy.top/Article/details/gtxyaizjjc.html

[R77] 读取用户输入
来源：http://dali.hywenlv.cn/Article/details/gtyudcgfeq.html

read -rp "请输入: " ans
来源：http://dali.kuanghao11.cn/Article/details/gtzzbgqdav.html

[R78] 交互式菜单
来源：http://dali.zdqjudy.top/Article/details/gtfggbhwik.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenzaomai.com/Article/details/gtiphhgqym.html

[R79] 解析命令行选项
来源：http://dali.xuanzx.com/Article/details/gtdfxkzzss.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xziqi.cn/Article/details/gthumgknpk.html

[R80] 查看脚本执行耗时
来源：http://dali.316326.xyz/Article/details/gtapjxoxuv.html

time ./run.sh
来源：http://dali.yj202588.top/Article/details/gtjyzbiysa.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtvkraqtfy.html

S. C / C++ 专题
来源：http://dali.tian-w.cn/Article/details/gtbuijfalb.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtasbssfzw.html

[S01] C：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtsgbqwjfv.html

#include <stdio.h>
来源：http://dali.gogol.net.cn/Article/details/gtseidojpu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gaohongyu789.top/Article/details/gtoywdookv.html

[S02] C：变量与格式化输出
来源：http://dali.jqgufenzy.top/Article/details/gtohdtabld.html

int a = 10; printf("%d\n", a);
来源：http://dali.yvedp.cn/Article/details/gtumhvmsbn.html

[S03] C：读入整数
来源：http://dali.jqgufenzy.top/Article/details/gteimpfbxu.html

int x; scanf("%d", &x);
来源：http://dali.gzhubu.top/Article/details/gtvblovexx.html

[S04] C：字符串复制
来源：http://dali.gogol.net.cn/Article/details/gtdgzbwjjk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xuanzx.com/Article/details/gtbiawuxfj.html

[S05] C：字符串长度
来源：http://dali.yuxming.cn/Article/details/gtfxgacobe.html

strlen(s)
来源：http://dali.shzxlz.cn/Article/details/gtecueensl.html

[S06] C：字符串比较
来源：http://dali.guannengcc.top/Article/details/gtqandcsir.html

strcmp(a, b) == 0
来源：http://dali.xinyue.icu/Article/details/gtohzwxdga.html

[S07] C：数组遍历求和
来源：http://dali.cheryme.top/Article/details/gtqkicjgfw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gtudmvolct.html

[S08] C：动态内存分配与释放
来源：http://dali.gzhubu.top/Article/details/gtmmodandn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nwbrower.top/Article/details/gtlriyzjsw.html

[S09] C：结构体定义与初始化
来源：http://dali.nanxinkj.top/Article/details/gtpugdkijf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.redwolf501.top/Article/details/gtrbbhjycu.html

[S10] C：指针与解引用
来源：http://dali.zhongyouzk.top/Article/details/gtnziovzpo.html

int *p = &a;  *p = 5;
来源：http://dali.cdnleiting.top/Article/details/gtmuglcuhg.html

[S11] C：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gtwiljfhnj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gaohongyu789.top/Article/details/gtjboudsij.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.0kj1m.cn/Article/details/gtpdwdbajd.html

fclose(f);
来源：http://dali.gaohongyu789.top/Article/details/gtkyldxpeg.html

[S12] C：写文件
来源：http://dali.hnxiangtu.top/Article/details/gtzgeiwmvo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj20258888.top/Article/details/gttwlmwqee.html

[S13] C：宏定义
来源：http://dali.fzhhl.top/Article/details/gthbuzyeck.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.haohaochexian.top/Article/details/gtkdmceefv.html

[S14] C：枚举
来源：http://dali.shuidangran.top/Article/details/gtxtnnnsbi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gogol.net.cn/Article/details/gtekhnssxu.html

[S15] C：类型转换
来源：http://dali.iojbl.cn/Article/details/gtqujtnewj.html

(double) a / b
来源：http://dali.daria6918.cn/Article/details/gtlvbbpyqx.html

[S16] C：位操作置位
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbghfgcb.html

x |= (1 << 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtzzzfncuk.html

[S17] C：安全拼接字符串
来源：http://dali.yvedp.cn/Article/details/gtycfwahkd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.dashuyun.cn/Article/details/gtxmnxxwhx.html

[S18] C：命令行参数
来源：http://dali.hysaishi.cn/Article/details/gtpfrmquhw.html

int main(int argc, char **argv)
来源：http://dali.yuanzhike.top/Article/details/gtagtjsjjw.html

[S19] C：快速排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvybxolxj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.haohaochexian.top/Article/details/gtdszeapic.html

[S20] C：二分查找
来源：http://dali.xuanzx.com/Article/details/gtoqurvozc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xuanzx.com/Article/details/gtrorornrc.html

[S21] C：字符类别判断
来源：http://dali.jianghu66.top/Article/details/gtdxtcngkt.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.quarkkingdee.top/Article/details/gtpeejcmgt.html

[S22] C：字符串转数字
来源：http://dali.jyoumei.cn/Article/details/gtwdukmpfg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.pycfn.com/Article/details/gtatvelhsz.html

[S23] C：随机数
来源：http://dali.xuanzx.com/Article/details/gtyhisnsig.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hfpthk.cn/Article/details/gtwycikvrf.html

[S24] C：获取本地时间
来源：http://dali.ppjwa.cn/Article/details/gtrbvfdocy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cqqwz.cn/Article/details/gtblmwzblu.html

[S25] C：内存拷贝
来源：http://dali.hongshengwenyu.top/Article/details/gtzmtzpuow.html

memcpy(dst, src, n);
来源：http://dali.guowangkeji.top/Article/details/gtgycetbnd.html

[S26] C：内存清零
来源：http://dali.jinqigfzy.top/Article/details/gtdywjgzxj.html

memset(a, 0, sizeof a);
来源：http://dali.cucudq.cn/Article/details/gtusavsulg.html

[S27] C：定义常量
来源：http://dali.yuxming.cn/Article/details/gtlbsjzxhl.html

const double PI = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtaevmqqxf.html

[S28] C：静态变量
来源：http://dali.hywenlv.cn/Article/details/gtkkfpyohl.html

static int counter = 0;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttdasldpk.html

[S29] C：变参函数
来源：http://dali.shuidangran.top/Article/details/gtenesmpzh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.c1oappe.top/Article/details/gtelekggmi.html

[S30] C：头文件保护
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqdcpnddi.html

#ifndef X_H
来源：http://dali.svipenyu.cn/Article/details/gtauudtrih.html

#define X_H
来源：http://dali.xinyue.icu/Article/details/gtruwjealh.html

#endif
来源：http://dali.tianlin.xyz/Article/details/gtlexdvttp.html

[S31] C++：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtkvzbwpqo.html

#include <iostream>
来源：http://dali.tianlin.xyz/Article/details/gtqefaruyt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tian-w.cn/Article/details/gtootngjpb.html

[S32] C++：字符串
来源：http://dali.cqqwz.cn/Article/details/gtsknofbmu.html

std::string s = "hi";  s += "!";
来源：http://dali.yvedp.cn/Article/details/gtxqgodqfu.html

[S33] C++：vector 增删
来源：http://dali.cdnleiting.top/Article/details/gtyqlukdry.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdvwjdwxs.html

[S34] C++：遍历 vector
来源：http://dali.pengpengdd.cyou/Article/details/gtdmbzaxwh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tianlin.xyz/Article/details/gteipotpth.html

[S35] C++：map
来源：http://dali.zhaomingkeji.xyz/Article/details/gteteecmlv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xziqi.cn/Article/details/gtfgyhtetk.html

[S36] C++：unordered_map
来源：http://dali.andypj.xyz/Article/details/gtclahjcrr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.iojbl.cn/Article/details/gtrnfhvxzl.html

[S37] C++：set
来源：http://dali.shuidangran.top/Article/details/gthxgwbpbr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sxryk.cn/Article/details/gtvbbhvbzo.html

[S38] C++：排序
来源：http://dali.jqgfzy.top/Article/details/gtvhaxzjlq.html

std::sort(v.begin(), v.end());
来源：http://dali.wangdashe.top/Article/details/gthdwkqayu.html

[S39] C++：自定义比较器排序
来源：http://dali.9152youxi.cn/Article/details/gtevqsqhlk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinqigfzy.top/Article/details/gtcqpqusjg.html

[S40] C++：查找元素
来源：http://dali.chenjidiqi.icu/Article/details/gtpnfdzvnb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shzxlz.cn/Article/details/gtfxmazkol.html

[S41] C++：类与构造函数
来源：http://dali.hysaishi.cn/Article/details/gtgbphdmot.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yangfankeji.com/Article/details/gtnsrknaxc.html

[S42] C++：继承与虚函数
来源：http://dali.cheryme.top/Article/details/gtwydtauju.html

class B : public Base { public: void f() override {} };
来源：http://dali.pycfn.com/Article/details/gtzusztnfl.html

[S43] C++：智能指针
来源：http://dali.ppjwa.cn/Article/details/gtcrmbcmfq.html

auto p = std::make_unique<int>(5);
来源：http://dali.shzxlz.cn/Article/details/gtdtfvanah.html

[S44] C++：引用传参
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwogwazlh.html

void inc(int &x) { ++x; }
来源：http://dali.cqqwz.cn/Article/details/gtcempiaxl.html

[S45] C++：lambda
来源：http://dali.ydzc1.top/Article/details/gtksotmvwc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yongpay.top/Article/details/gtcdolxdwo.html

[S46] C++：函数模板
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsbnfrxyd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdljdzgmw.html

[S47] C++：结构化绑定遍历
来源：http://dali.xinyue.icu/Article/details/gtlkpuifko.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jianghu66.top/Article/details/gtltkgggdq.html

[S48] C++：逐行读文件
来源：http://dali.tanke756.top/Article/details/gtjmuhkmdn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gaohongyu789.top/Article/details/gtboyaqrqu.html

while (std::getline(in, line)) { }
来源：http://dali.iojbl.cn/Article/details/gtkunahgcj.html

[S49] C++：写文件
来源：http://dali.jqgfzy.top/Article/details/gtzbxjwofr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinqigufen.top/Article/details/gtejsmtejr.html

[S50] C++：格式化数字
来源：http://dali.yueranfly.top/Article/details/gtjwtptvxu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gtjamsajzp.html

[S51] C++：显式类型转换
来源：http://dali.hfpthk.cn/Article/details/gtjsettiph.html

static_cast<double>(a) / b
来源：http://dali.bjfxy.top/Article/details/gtttvvhptr.html

[S52] C++：const 与 noexcept
来源：http://dali.snrcjt.cn/Article/details/gttfvfywvf.html

int size() const noexcept { return n_; }
来源：http://dali.tanke756.top/Article/details/gthritkysu.html

[S53] C++：移动语义
来源：http://dali.wangdashe.top/Article/details/gtfjvtucad.html

std::vector<int> w = std::move(v);
来源：http://dali.gogol.net.cn/Article/details/gtxqxvtyiu.html

[S54] C++：异常处理
来源：http://dali.daria6918.cn/Article/details/gtultgtmlf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.316326.xyz/Article/details/gtlvladxvp.html

[S55] C++：结构化绑定
来源：http://dali.mhx1999.top/Article/details/gtvzqnprrz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ydzc1.top/Article/details/gtdfgiezai.html

[S56] C++：optional
来源：http://dali.mhx1999.top/Article/details/gtnaoducfe.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yuxming.cn/Article/details/gtrhjpwyyf.html

[S57] C++：编译期常量
来源：http://dali.nanxuanxn.top/Article/details/gtitbwvbld.html

constexpr int N = 10;
来源：http://dali.nanxuanxn.top/Article/details/gtvdpbrlcw.html

[S58] C++：命名空间
来源：http://dali.gzhubu.top/Article/details/gtvbgvkubi.html

namespace ns { int f() { return 1; } }
来源：http://dali.cashguo.top/Article/details/gtdwlajusb.html

[S59] C++：静态断言
来源：http://dali.yuxming.cn/Article/details/gtmydwjtiu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gotoacloud.top/Article/details/gtocmauclu.html

[S60] C++：遍历并删除元素
来源：http://dali.zhengqikj.top/Article/details/gthbeqorbg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.0kj1m.cn/Article/details/gtqflrpimq.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtfmmlfukn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cheryme.top/Article/details/gtzpvjtvun.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gthqkpzrxk.html

[T01] Kotlin：Hello World
来源：http://dali.ydzc1.top/Article/details/gtvtbfpqsf.html

println("Hello")
来源：http://dali.cdnleiting.top/Article/details/gtwbwbyzjp.html

[T02] Kotlin：变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gthcfpuiew.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenlongwang.top/Article/details/gtvgwuocez.html

[T03] Kotlin：字符串模板
来源：http://dali.xuanzx.com/Article/details/gtnacakwno.html

"值: $b"
来源：http://dali.guannengcc.top/Article/details/gtqzpigdob.html

[T04] Kotlin：空安全
来源：http://dali.ydzc1.top/Article/details/gtelxfsuuh.html

val n: String? = null;  n?.length
来源：http://dali.tianlin.xyz/Article/details/gtkmwmrvev.html

[T05] Kotlin：when 表达式
来源：http://dali.gaohongyu789.top/Article/details/gtvkznpnww.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yvedp.cn/Article/details/gtdhasgpgp.html

[T06] Kotlin：集合映射
来源：http://dali.sysykeji.top/Article/details/gtkuybcetb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sysykeji.top/Article/details/gtueexrjrc.html

[T07] Kotlin：集合过滤
来源：http://dali.shzxlz.cn/Article/details/gttnvmxnoh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xziqi.cn/Article/details/gtzttwaatq.html

[T08] Kotlin：数据类
来源：http://dali.jlsjyb.cn/Article/details/gtjhnanhcp.html

data class User(val name: String, val age: Int)
来源：http://dali.zhoulong.xyz/Article/details/gtlywmbjoi.html

[T09] Kotlin：扩展函数
来源：http://dali.havefunace.top/Article/details/gtqewuvmxm.html

fun String.exclaim() = this + "!"
来源：http://dali.hywenlv.cn/Article/details/gtigutgpzd.html

[T10] Kotlin：默认参数
来源：http://dali.smart0.xyz/Article/details/gtoebwxxlq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.nanxuanxn.top/Article/details/gtoushdcoa.html

[T11] Kotlin：协程
来源：http://dali.jqgufenzy.top/Article/details/gtuxzlzlpx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ydzc1.top/Article/details/gtvxyjcnfl.html

[T12] Kotlin：解构声明
来源：http://dali.zhoulong.xyz/Article/details/gtdgcwjked.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtbibabbqb.html

[T13] Kotlin：只读 Map
来源：http://dali.cashguo.top/Article/details/gtfzfnffzn.html

val m = mapOf("a" to 1)
来源：http://dali.cashguo.top/Article/details/gtsbkbbaob.html

[T14] Kotlin：循环
来源：http://dali.zhiwuduotai.top/Article/details/gtsfppbqje.html

for (i in 1..10) println(i)
来源：http://dali.shangyingyoupin.top/Article/details/gtwtcnuowm.html

[T15] Kotlin：接口
来源：http://dali.pengpengdd.cyou/Article/details/gttffhrfba.html

interface Shape { fun area(): Double }
来源：http://dali.dianchejie.cn/Article/details/gtbbmdoqes.html

[T16] Swift：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtgwkagzaa.html

print("Hello")
来源：http://dali.tian-w.cn/Article/details/gtoolhmdww.html

[T17] Swift：变量与常量
来源：http://dali.jyoumei.cn/Article/details/gtrkfimzwi.html

var a = 1;  let b = 2
来源：http://dali.gaohongyu789.top/Article/details/gtqhnkmnxq.html

[T18] Swift：字符串插值
来源：http://dali.fengsongda.top/Article/details/gtutwmbzof.html

"值: \(b)"
来源：http://dali.yueranfly.top/Article/details/gtpzwuwdle.html

[T19] Swift：可选绑定
来源：http://dali.ydzc1.top/Article/details/gtcfuswwox.html

if let n = opt { print(n) }
来源：http://dali.ivvv.top/Article/details/gtjgdmfgqz.html

[T20] Swift：数组操作
来源：http://dali.iojbl.cn/Article/details/gtnqbypsfj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.aizwys.cn/Article/details/gtpamwahcl.html

[T21] Swift：遍历
来源：http://dali.cqqwz.cn/Article/details/gtlqdsomsv.html

for x in a { print(x) }
来源：http://dali.cashguo.top/Article/details/gtkijwgocc.html

[T22] Swift：字典
来源：http://dali.hammf.cn/Article/details/gtkaoucfoi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sweek.top/Article/details/gtywmadzfv.html

[T23] Swift：函数
来源：http://dali.shuidangran.top/Article/details/gtpmkwsyrm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yvedp.cn/Article/details/gtdnoeoxxn.html

[T24] Swift：闭包
来源：http://dali.xinyue.icu/Article/details/gtcnsqqfts.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yvedp.cn/Article/details/gtxlrnvqvw.html

[T25] Swift：结构体
来源：http://dali.sxryk.cn/Article/details/gtzwklprwc.html

struct P { var x: Int }
来源：http://dali.yvedp.cn/Article/details/gtqlauyskf.html

[T26] Swift：类与重写
来源：http://dali.vqdsnc.cn/Article/details/gtwrqdwhbe.html

class A: Base { override func f() {} }
来源：http://dali.pycfn.com/Article/details/gtdvruucnj.html

[T27] Swift：错误处理
来源：http://dali.jinqigfzy.top/Article/details/gtfpkjpbhs.html

do { try f() } catch { print(error) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsdbfqgsy.html

[T28] Swift：枚举
来源：http://dali.shuidangran.top/Article/details/gthqpmghlw.html

enum Color { case red, green }
来源：http://dali.nwbrower.top/Article/details/gthfuobpoz.html

[T29] Swift：guard 提前返回
来源：http://dali.smart0.xyz/Article/details/gtqtjycnis.html

guard let x = opt else { return }
来源：http://dali.guowangkeji.top/Article/details/gthqtospft.html

[T30] Swift：协议
来源：http://dali.jiagoushi.top/Article/details/gtewlhqoaw.html

protocol Shape { func area() -> Double }
来源：http://dali.yj202588.top/Article/details/gtnqfthvkz.html

[T31] Lua：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtnervlcsw.html

print("Hello")
来源：http://dali.yj20258888.top/Article/details/gtrueofcat.html

[T32] Lua：局部变量
来源：http://dali.tian-w.cn/Article/details/gtztnkdjjj.html

local a = 1
来源：http://dali.jqgufenzy.top/Article/details/gtidgwizyr.html

[T33] Lua：表（数组）
来源：http://dali.gaohongyu789.top/Article/details/gtvmmghqjl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.mhx1999.top/Article/details/gttgaceqcx.html

[T34] Lua：遍历表
来源：http://dali.yj20258888.top/Article/details/gtmssarxge.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhixingplan.top/Article/details/gtodaiaule.html

[T35] Lua：字典表
来源：http://dali.cqqwz.cn/Article/details/gtabcvebsk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.nanxinkj.top/Article/details/gtctaptxhv.html

[T36] Lua：函数
来源：http://dali.smart0.xyz/Article/details/gtukvdvplj.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gtwlihrzmc.html

[T37] Lua：字符串拼接
来源：http://dali.xziqi.cn/Article/details/gtvgjkfvsz.html

"a" .. "b"
来源：http://dali.quarkkingdee.top/Article/details/gtlooeaqsz.html

[T38] Lua：条件
来源：http://dali.zhoulong.xyz/Article/details/gtttayhbtg.html

if x > 0 then print("正") end
来源：http://dali.hfpthk.cn/Article/details/gtypheoinv.html

[T39] Lua：模式匹配
来源：http://dali.yj20258.top/Article/details/gtiwdbycmc.html

string.find(s, "%d+")
来源：http://dali.hnxiangtu.top/Article/details/gtfdbgiecw.html

[T40] Lua：元表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtultncpgc.html

setmetatable({}, { __index = base })
来源：http://dali.yonumen.top/Article/details/gtojbqtizn.html

[T41] Perl：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzyuaertp.html

print "Hello\n";
来源：http://dali.yanxiufei.cn/Article/details/gtxlzwzszp.html

[T42] Perl：变量类型
来源：http://dali.daxiang520.top/Article/details/gtomioabfg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shzxlz.cn/Article/details/gtpiixsfom.html

[T43] Perl：字符串插值
来源：http://dali.vqdsnc.cn/Article/details/gtsxyeftog.html

"值: $a"
来源：http://dali.kuanghao11.cn/Article/details/gtxggncllk.html

[T44] Perl：条件
来源：http://dali.daxiang520.top/Article/details/gtsqxyogol.html

if ($a > 0) { print "正"; }
来源：http://dali.nanxuanxn.top/Article/details/gtkickrdvb.html

[T45] Perl：数组遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbemupsne.html

for my $x (@arr) { print $x; }
来源：http://dali.zhongyouzk.top/Article/details/gtupsaiyhg.html

[T46] Perl：哈希操作
来源：http://dali.jinqigufen.top/Article/details/gtcvkisbcp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.snrcjt.cn/Article/details/gtrdcdtfkv.html

[T47] Perl：正则捕获
来源：http://dali.gaohongyu789.top/Article/details/gtpvhlpwjp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbwfzpoul.html

[T48] Perl：正则替换
来源：http://dali.yj20258888.top/Article/details/gtucdjweon.html

$s =~ s/old/new/g;
来源：http://dali.xuetiantiany.cn/Article/details/gtkhfjgoro.html

[T49] Perl：函数
来源：http://dali.redwolf501.top/Article/details/gtjwwklxfx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gtkzqbjkdr.html

[T50] Perl：逐行读文件
来源：http://dali.316326.xyz/Article/details/gtfjqkbumj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.chenlongwang.top/Article/details/gtjrtwfxrw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtymcvyhno.html

[T51] Scala：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtaetutcgr.html

println("Hello")
来源：http://dali.xinyue.icu/Article/details/gtjxureojr.html

[T52] Scala：变量
来源：http://dali.hongshengwenyu.top/Article/details/gthmhdazac.html

val a = 1;  var b = 2
来源：http://dali.hfpthk.cn/Article/details/gtyjqkgxqq.html

[T53] Scala：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gtapwbglll.html

s"值: $b"
来源：http://dali.gzhubu.top/Article/details/gtyedfymzx.html

[T54] Scala：集合映射
来源：http://dali.chenjidiqi.icu/Article/details/gttbcimzsm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.haohaochexian.top/Article/details/gtbdlgyboe.html

[T55] Scala：集合过滤
来源：http://dali.cdnleiting.top/Article/details/gthhxifqrb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.havefunace.top/Article/details/gtlmphjsxo.html

[T56] Scala：样例类
来源：http://dali.mhx1999.top/Article/details/gtkixoakkc.html

case class User(name: String, age: Int)
来源：http://dali.wangshuangyany.cn/Article/details/gtgkmqntap.html

[T57] Scala：模式匹配
来源：http://dali.ehwqpu.com/Article/details/gtxxbqstdt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gotoacloud.top/Article/details/gtgxvvamzr.html

[T58] Scala：函数定义
来源：http://dali.ivvv.top/Article/details/gtyvxwbwmc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.mhx1999.top/Article/details/gtkmpdhuij.html

[T59] Scala：循环
来源：http://dali.jianghu66.top/Article/details/gtqeeuyepe.html

for (i <- 1 to 10) println(i)
来源：http://dali.xziqi.cn/Article/details/gtlagkfzlp.html

[T60] Scala：折叠
来源：http://dali.feifeiyinyue.top/Article/details/gtcbkefpxc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yj202588.top/Article/details/gttnpmhtzj.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtdtpczava.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtpxsnetig.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtmstgqwae.html

[U01] Py：创建虚拟环境
来源：http://dali.nanxuanxn.top/Article/details/gtxpirfhha.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yonumen.top/Article/details/gtzafndjse.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gthrcqnqpu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hywenlv.cn/Article/details/gtmyttnwdu.html

[U03] Py：加载 .env 配置
来源：http://dali.sweek.top/Article/details/gtplmeainh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.9152youxi.cn/Article/details/gterfxjyfg.html

[U04] Py：变量调试打印
来源：http://dali.zhixingplan.top/Article/details/gtgrpfttde.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xuanzx.com/Article/details/gtqpcyoaxv.html

[U05] Py：列表去重且保序
来源：http://dali.yonumen.top/Article/details/gtyxclfgqb.html

list(dict.fromkeys(arr))
来源：http://dali.wangdashe.top/Article/details/gtwgfsrmpc.html

[U06] Py：合并两个字典
来源：http://dali.ybcxt.top/Article/details/gtbatdfklq.html

{**a, **b}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwxxhtodv.html

[U07] Py：反转字典键值
来源：http://dali.daria6918.cn/Article/details/gtuwmolarh.html

{v: k for k, v in d.items()}
来源：http://dali.xylfe.cn/Article/details/gtueqvxqwm.html

[U08] Py：展平二维列表
来源：http://dali.dianchejie.cn/Article/details/gtuvepyeyo.html

[y for x in nested for y in x]
来源：http://dali.sufxvd.cn/Article/details/gtmbnjcjke.html

[U09] Py：字典取最大值的键
来源：http://dali.hfpthk.cn/Article/details/gtzzzaoucs.html

max(d, key=d.get)
来源：http://dali.xuanzx.com/Article/details/gtkdlrasmd.html

[U10] Py：按值排序字典
来源：http://dali.jiagoushi.top/Article/details/gtvvqcriwy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.fengsongda.top/Article/details/gtqbdsdjau.html

[U11] Py：生成器表达式
来源：http://dali.chenlongwang.top/Article/details/gtxpnjltgd.html

(x * 2 for x in arr)
来源：http://dali.yonumen.top/Article/details/gtflacudfd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yangfankeji.com/Article/details/gtlazupsxi.html

Counter(arr).most_common(3)
来源：http://dali.hnqzz.top/Article/details/gtwlilecyn.html

[U13] Py：固定长度队列
来源：http://dali.wangshuangyany.cn/Article/details/gttpgioytq.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gticcnebgl.html

[U14] Py：分组收集到列表
来源：http://dali.zdqjudy.top/Article/details/gtxwkmqbgt.html

defaultdict(list)
来源：http://dali.haohaochexian.top/Article/details/gtheeiqjoi.html


<!-- 参考信息 -->