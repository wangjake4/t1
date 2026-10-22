代发 wailian999

export PATH="$HOME/bin:$PATH"
来源：http://dali.vqdsnc.cn/Article/details/gt2nnrwgkot.html

[R76] 使用临时文件
来源：http://dali.chenzaomai.com/Article/details/gt2csnpvpuh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2prfxkkct.html

[R77] 读取用户输入
来源：http://dali.nanxinkj.top/Article/details/gt2idjhmjiq.html

read -rp "请输入: " ans
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dszqcnac.html

[R78] 交互式菜单
来源：http://dali.zhiwuduotai.top/Article/details/gt2ysffwhbt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jiagoushi.top/Article/details/gt2nrxapokk.html

[R79] 解析命令行选项
来源：http://dali.chenjidiqi.icu/Article/details/gt2vbhciewa.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gaohongyu789.top/Article/details/gt2vhqctojv.html

[R80] 查看脚本执行耗时
来源：http://dali.hnxiangtu.top/Article/details/gt2ntfrafxp.html

time ./run.sh
来源：http://dali.tanke756.top/Article/details/gt2rnsdeuph.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2qipssnvu.html

S. C / C++ 专题
来源：http://dali.mhx1999.top/Article/details/gt2apegpgrv.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2rsjnwfhf.html

[S01] C：Hello World
来源：http://dali.ydzc1.top/Article/details/gt2eiihbygc.html

#include <stdio.h>
来源：http://dali.shuidangran.top/Article/details/gt2zwvbytyg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.pycfn.com/Article/details/gt2ycsjpsuf.html

[S02] C：变量与格式化输出
来源：http://dali.fengsongda.top/Article/details/gt2rzzumewh.html

int a = 10; printf("%d\n", a);
来源：http://dali.yuxming.cn/Article/details/gt2cheqwcqw.html

[S03] C：读入整数
来源：http://dali.havefunace.top/Article/details/gt2oscamyml.html

int x; scanf("%d", &x);
来源：http://dali.zhongyouzk.top/Article/details/gt2tmmjieny.html

[S04] C：字符串复制
来源：http://dali.chenjidiqi.icu/Article/details/gt2qnnscvvo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cdnleiting.top/Article/details/gt2jfcntnhc.html

[S05] C：字符串长度
来源：http://dali.svipenyu.cn/Article/details/gt2dwvrxjmm.html

strlen(s)
来源：http://dali.chenlongwang.top/Article/details/gt2mvzxpphc.html

[S06] C：字符串比较
来源：http://dali.gotoacloud.top/Article/details/gt2gchphogk.html

strcmp(a, b) == 0
来源：http://dali.yj20258.top/Article/details/gt2mfrpkyil.html

[S07] C：数组遍历求和
来源：http://dali.ivvv.top/Article/details/gt2qpyrnrsp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhixingplan.top/Article/details/gt2qdnymvwv.html

[S08] C：动态内存分配与释放
来源：http://dali.snrcjt.cn/Article/details/gt2oldvjswl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hnxiangtu.top/Article/details/gt2zayhtaxr.html

[S09] C：结构体定义与初始化
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dibwirpe.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2duogoxmm.html

[S10] C：指针与解引用
来源：http://dali.smart0.xyz/Article/details/gt2brntgrqy.html

int *p = &a;  *p = 5;
来源：http://dali.tian-w.cn/Article/details/gt2amctaxes.html

[S11] C：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wmyqzbem.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.feifeiyinyue.top/Article/details/gt2dymvebqg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yangfankeji.com/Article/details/gt2afaoqjcu.html

fclose(f);
来源：http://dali.daria6918.cn/Article/details/gt2kascyffd.html

[S12] C：写文件
来源：http://dali.snrcjt.cn/Article/details/gt2uxksxmfi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xylfe.cn/Article/details/gt2lajgigom.html

[S13] C：宏定义
来源：http://dali.yongpay.top/Article/details/gt2dwnyxtzx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xuanzx.com/Article/details/gt2aiipltux.html

[S14] C：枚举
来源：http://dali.zdqjudy.top/Article/details/gt2nhmikykr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhongyouzk.top/Article/details/gt2qmnhqhpk.html

[S15] C：类型转换
来源：http://dali.sufxvd.cn/Article/details/gt2rztdlztg.html

(double) a / b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2adxyzcsj.html

[S16] C：位操作置位
来源：http://dali.xinyue.icu/Article/details/gt2hcocytaf.html

x |= (1 << 3);
来源：http://dali.daxiang520.top/Article/details/gt2eziedjxv.html

[S17] C：安全拼接字符串
来源：http://dali.havefunace.top/Article/details/gt2evxgrqre.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.havefunace.top/Article/details/gt2smeebwwu.html

[S18] C：命令行参数
来源：http://dali.yj20258.top/Article/details/gt2vjavocbq.html

int main(int argc, char **argv)
来源：http://dali.hywenlv.cn/Article/details/gt2gjnlmrxa.html

[S19] C：快速排序
来源：http://dali.0kj1m.cn/Article/details/gt2dmbwuxcx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.guowangkeji.top/Article/details/gt2drrqwepf.html

[S20] C：二分查找
来源：http://dali.dashuyun.cn/Article/details/gt2pspbitup.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.redwolf501.top/Article/details/gt2ohpuwrjt.html

[S21] C：字符类别判断
来源：http://dali.fengsongda.top/Article/details/gt2kpsikszv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinqigfzy.top/Article/details/gt2wysjcitg.html

[S22] C：字符串转数字
来源：http://dali.nanxinkj.top/Article/details/gt2xklzipld.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tanke756.top/Article/details/gt2nqrfkslu.html

[S23] C：随机数
来源：http://dali.yangfankeji.com/Article/details/gt2tqgeozav.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yuanzhike.top/Article/details/gt2ochkclzr.html

[S24] C：获取本地时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nranwthh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gaohongyu789.top/Article/details/gt2ylbdtyxk.html

[S25] C：内存拷贝
来源：http://dali.pengpengdd.cyou/Article/details/gt2gabicvif.html

memcpy(dst, src, n);
来源：http://dali.xuanzx.com/Article/details/gt2guphbrbb.html

[S26] C：内存清零
来源：http://dali.nanxuanxn.top/Article/details/gt2vjekzvsf.html

memset(a, 0, sizeof a);
来源：http://dali.dianchejie.cn/Article/details/gt2ficiaufc.html

[S27] C：定义常量
来源：http://dali.fzhhl.top/Article/details/gt2ygczlgaq.html

const double PI = 3.14159;
来源：http://dali.wangdashe.top/Article/details/gt2rxbcymqa.html

[S28] C：静态变量
来源：http://dali.guannengcc.top/Article/details/gt2jpdmnntm.html

static int counter = 0;
来源：http://dali.guannengcc.top/Article/details/gt2bspnbkyh.html

[S29] C：变参函数
来源：http://dali.hysaishi.cn/Article/details/gt2cbaigxty.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xuetiantiany.cn/Article/details/gt2iumytitf.html

[S30] C：头文件保护
来源：http://dali.ehwqpu.com/Article/details/gt2fsvizzbv.html

#ifndef X_H
来源：http://dali.vqdsnc.cn/Article/details/gt2dcxwbias.html

#define X_H
来源：http://dali.vqdsnc.cn/Article/details/gt2qdyeayqn.html

#endif
来源：http://dali.zdqjudy.top/Article/details/gt2ryqxvcgl.html

[S31] C++：Hello World
来源：http://dali.nwbrower.top/Article/details/gt2irhhlgyz.html

#include <iostream>
来源：http://dali.9152youxi.cn/Article/details/gt2ewewngtv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.bjfxy.top/Article/details/gt2ourpwddz.html

[S32] C++：字符串
来源：http://dali.jiagoushi.top/Article/details/gt2nfxlqbfd.html

std::string s = "hi";  s += "!";
来源：http://dali.vqdsnc.cn/Article/details/gt2udwhkyul.html

[S33] C++：vector 增删
来源：http://dali.0kj1m.cn/Article/details/gt2gvdnswsl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.kuanghao11.cn/Article/details/gt2zuphcelj.html

[S34] C++：遍历 vector
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wgpfjxvh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.fzhhl.top/Article/details/gt2toxthxwu.html

[S35] C++：map
来源：http://dali.kuanghao11.cn/Article/details/gt2xdtyqjpi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gt2sugvpgmz.html

[S36] C++：unordered_map
来源：http://dali.ivvv.top/Article/details/gt2kxeclyig.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.meibo888.top/Article/details/gt2naxqgekz.html

[S37] C++：set
来源：http://dali.wangshuangyany.cn/Article/details/gt2hvjyexny.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhengqikj.top/Article/details/gt2vldjjtox.html

[S38] C++：排序
来源：http://dali.ehwqpu.com/Article/details/gt2ketaewze.html

std::sort(v.begin(), v.end());
来源：http://dali.yueranfly.top/Article/details/gt2ssozmbnw.html

[S39] C++：自定义比较器排序
来源：http://dali.ppjwa.cn/Article/details/gt2jiqlvbhm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gzhubu.top/Article/details/gt2ztozjhmf.html

[S40] C++：查找元素
来源：http://dali.jqgufenzy.top/Article/details/gt2oqhqnniv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.andypj.xyz/Article/details/gt2uweokgqt.html

[S41] C++：类与构造函数
来源：http://dali.daxiang520.top/Article/details/gt2mptxvdre.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2djozlghu.html

[S42] C++：继承与虚函数
来源：http://dali.316326.xyz/Article/details/gt2jrwnccpo.html

class B : public Base { public: void f() override {} };
来源：http://dali.aibaodan.cn/Article/details/gt2fpdnbymh.html

[S43] C++：智能指针
来源：http://dali.snrcjt.cn/Article/details/gt2wsvpoasb.html

auto p = std::make_unique<int>(5);
来源：http://dali.kuanghao11.cn/Article/details/gt2hqhtzlfd.html

[S44] C++：引用传参
来源：http://dali.316326.xyz/Article/details/gt2pdizkcgs.html

void inc(int &x) { ++x; }
来源：http://dali.pycfn.com/Article/details/gt2fmbidkak.html

[S45] C++：lambda
来源：http://dali.yj20258888.top/Article/details/gt2tmsbcioj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.snrcjt.cn/Article/details/gt2qhwscabh.html

[S46] C++：函数模板
来源：http://dali.dianchejie.cn/Article/details/gt2ktqsoebl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sputdpug.html

[S47] C++：结构化绑定遍历
来源：http://dali.jlsjyb.cn/Article/details/gt2xhimklss.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xuanzx.com/Article/details/gt2zuidukxv.html

[S48] C++：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gt2dbyfaqtc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yongpay.top/Article/details/gt2ngqyhmjc.html

while (std::getline(in, line)) { }
来源：http://dali.yueranfly.top/Article/details/gt2jztwcnfj.html

[S49] C++：写文件
来源：http://dali.aizwys.cn/Article/details/gt2resvnjdn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ppjwa.cn/Article/details/gt2izmifepu.html

[S50] C++：格式化数字
来源：http://dali.zhoulong.xyz/Article/details/gt2vzqglbge.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gt2hyzzrkms.html

[S51] C++：显式类型转换
来源：http://dali.meibo888.top/Article/details/gt2isozkvye.html

static_cast<double>(a) / b
来源：http://dali.zycfv.cn/Article/details/gt2qkfjegjz.html

[S52] C++：const 与 noexcept
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jqdnjjdd.html

int size() const noexcept { return n_; }
来源：http://dali.snrcjt.cn/Article/details/gt2vwvuffcb.html

[S53] C++：移动语义
来源：http://dali.sweek.top/Article/details/gt2zcribsyh.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqzname.html

[S54] C++：异常处理
来源：http://dali.chenjidiqi.icu/Article/details/gt2yxmztcxx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ckzacttz.html

[S55] C++：结构化绑定
来源：http://dali.yuxming.cn/Article/details/gt2iishcmqr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yangfankeji.com/Article/details/gt2mwdhlomx.html

[S56] C++：optional
来源：http://dali.jlsjyb.cn/Article/details/gt2zlvnwleo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sweek.top/Article/details/gt2xizsougd.html

[S57] C++：编译期常量
来源：http://dali.hysaishi.cn/Article/details/gt2zsdereil.html

constexpr int N = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gt2mwuydnoa.html

[S58] C++：命名空间
来源：http://dali.9152youxi.cn/Article/details/gt2errzpcyg.html

namespace ns { int f() { return 1; } }
来源：http://dali.hysaishi.cn/Article/details/gt2yagmgybj.html

[S59] C++：静态断言
来源：http://dali.guannengcc.top/Article/details/gt2vywumfwf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhiwuduotai.top/Article/details/gt2kabdssmz.html

[S60] C++：遍历并删除元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2abluutaa.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinqigufen.top/Article/details/gt2byuzrgks.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2ilmabpjz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aibaodan.cn/Article/details/gt2snkymfay.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2fgbncxrv.html

[T01] Kotlin：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gt2upoutzig.html

println("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gt2doamtrix.html

[T02] Kotlin：变量
来源：http://dali.ppjwa.cn/Article/details/gt2qsvbmuit.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.snrcjt.cn/Article/details/gt2vacwswne.html

[T03] Kotlin：字符串模板
来源：http://dali.cqqwz.cn/Article/details/gt2blltewph.html

"值: $b"
来源：http://dali.hnqzz.top/Article/details/gt2wxxspzkl.html

[T04] Kotlin：空安全
来源：http://dali.pengpengdd.cyou/Article/details/gt2yrmmjihr.html

val n: String? = null;  n?.length
来源：http://dali.dianchejie.cn/Article/details/gt2uxozljfw.html

[T05] Kotlin：when 表达式
来源：http://dali.chenlongwang.top/Article/details/gt2whztifud.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.fzhhl.top/Article/details/gt2danveefj.html

[T06] Kotlin：集合映射
来源：http://dali.zhoulong.xyz/Article/details/gt2kmccowsu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fhazrqxe.html

[T07] Kotlin：集合过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gbtblqyf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhboidw.html

[T08] Kotlin：数据类
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cribuiyr.html

data class User(val name: String, val age: Int)
来源：http://dali.hfpthk.cn/Article/details/gt2jqqtygkx.html

[T09] Kotlin：扩展函数
来源：http://dali.xziqi.cn/Article/details/gt2xotteqjz.html

fun String.exclaim() = this + "!"
来源：http://dali.ivvv.top/Article/details/gt2yuedwwby.html

[T10] Kotlin：默认参数
来源：http://dali.xuanzx.com/Article/details/gt2knjfetgn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xzaevtpo.html

[T11] Kotlin：协程
来源：http://dali.guannengcc.top/Article/details/gt2holmlsuz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jyoumei.cn/Article/details/gt2wgzvpbnf.html

[T12] Kotlin：解构声明
来源：http://dali.hywenlv.cn/Article/details/gt2bxfgcurl.html

val (a, b) = Pair(1, 2)
来源：http://dali.yj20258.top/Article/details/gt2izpkbvfm.html

[T13] Kotlin：只读 Map
来源：http://dali.zhixingplan.top/Article/details/gt2zldnmbbu.html

val m = mapOf("a" to 1)
来源：http://dali.zhengqikj.top/Article/details/gt2wzujgwxi.html

[T14] Kotlin：循环
来源：http://dali.guowangkeji.top/Article/details/gt2nbhyycle.html

for (i in 1..10) println(i)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gvbweydw.html

[T15] Kotlin：接口
来源：http://dali.bjfxy.top/Article/details/gt2wzjvggsx.html

interface Shape { fun area(): Double }
来源：http://dali.hfpthk.cn/Article/details/gt2ratyxeio.html

[T16] Swift：Hello World
来源：http://dali.cqqwz.cn/Article/details/gt2fedclbop.html

print("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gt2vuqujwvt.html

[T17] Swift：变量与常量
来源：http://dali.fzhhl.top/Article/details/gt2krqvbnle.html

var a = 1;  let b = 2
来源：http://dali.yj20258888.top/Article/details/gt2pnugrpxi.html

[T18] Swift：字符串插值
来源：http://dali.fzhhl.top/Article/details/gt2huzbukdk.html

"值: \(b)"
来源：http://dali.haohaochexian.top/Article/details/gt2nifsznsx.html

[T19] Swift：可选绑定
来源：http://dali.yvedp.cn/Article/details/gt2ggmrgjgd.html

if let n = opt { print(n) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hfqzavwm.html

[T20] Swift：数组操作
来源：http://dali.gzhubu.top/Article/details/gt2myowrnqj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yangfankeji.com/Article/details/gt2ynnlhjke.html

[T21] Swift：遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2doqfhoan.html

for x in a { print(x) }
来源：http://dali.jinqigufen.top/Article/details/gt2hlkxhgqe.html

[T22] Swift：字典
来源：http://dali.xuetiantiany.cn/Article/details/gt2rlvzowna.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.guowangkeji.top/Article/details/gt2ocrljofy.html

[T23] Swift：函数
来源：http://dali.nanxuanxn.top/Article/details/gt2xlzhqmxm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gaohongyu789.top/Article/details/gt2orrdteeh.html

[T24] Swift：闭包
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wvjefzjl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.svipenyu.cn/Article/details/gt2rgnugckf.html

[T25] Swift：结构体
来源：http://dali.cheryme.top/Article/details/gt2grmszpfn.html

struct P { var x: Int }
来源：http://dali.kuanghao11.cn/Article/details/gt2uewkndhn.html

[T26] Swift：类与重写
来源：http://dali.nwbrower.top/Article/details/gt2hjwxjxjr.html

class A: Base { override func f() {} }
来源：http://dali.9152youxi.cn/Article/details/gt2vclvimlb.html

[T27] Swift：错误处理
来源：http://dali.birdmap.top/Article/details/gt2bejsrhyd.html

do { try f() } catch { print(error) }
来源：http://dali.redwolf501.top/Article/details/gt2ajltiiaa.html

[T28] Swift：枚举
来源：http://dali.ppjwa.cn/Article/details/gt2ipkcbhor.html

enum Color { case red, green }
来源：http://dali.vqdsnc.cn/Article/details/gt2xebefldm.html

[T29] Swift：guard 提前返回
来源：http://dali.tianlin.xyz/Article/details/gt2eorezvcz.html

guard let x = opt else { return }
来源：http://dali.zhongyouzk.top/Article/details/gt2hegvvtws.html

[T30] Swift：协议
来源：http://dali.c1oappe.top/Article/details/gt2qbfxcgqj.html

protocol Shape { func area() -> Double }
来源：http://dali.jiagoushi.top/Article/details/gt2hmoarjxj.html

[T31] Lua：Hello World
来源：http://dali.sxryk.cn/Article/details/gt2qzmkedgy.html

print("Hello")
来源：http://dali.sufxvd.cn/Article/details/gt2nvnmggaa.html

[T32] Lua：局部变量
来源：http://dali.snrcjt.cn/Article/details/gt2jfiwoaba.html

local a = 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2djkslsnr.html

[T33] Lua：表（数组）
来源：http://dali.guowangkeji.top/Article/details/gt2zexzqkza.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ufkwqcol.html

[T34] Lua：遍历表
来源：http://dali.yj20258888.top/Article/details/gt2kfvirhmo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.fzhhl.top/Article/details/gt2azteqftt.html

[T35] Lua：字典表
来源：http://dali.yanxiufei.cn/Article/details/gt2bbnhodrw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yueranfly.top/Article/details/gt2rwhcfhqx.html

[T36] Lua：函数
来源：http://dali.nwbrower.top/Article/details/gt2mompkgzi.html

function add(a, b) return a + b end
来源：http://dali.hywenlv.cn/Article/details/gt2lfmoynkc.html

[T37] Lua：字符串拼接
来源：http://dali.zycfv.cn/Article/details/gt2bfhruxgk.html

"a" .. "b"
来源：http://dali.wangshuangyany.cn/Article/details/gt2bieymtks.html

[T38] Lua：条件
来源：http://dali.yueranfly.top/Article/details/gt2uojoplee.html

if x > 0 then print("正") end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hpassjkm.html

[T39] Lua：模式匹配
来源：http://dali.sufxvd.cn/Article/details/gt2htpyvydv.html

string.find(s, "%d+")
来源：http://dali.guannengcc.top/Article/details/gt2jyoxrrmp.html

[T40] Lua：元表
来源：http://dali.ppjwa.cn/Article/details/gt2paegjbgi.html

setmetatable({}, { __index = base })
来源：http://dali.quarkkingdee.top/Article/details/gt2hqjvsieb.html

[T41] Perl：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2dycyazoi.html

print "Hello\n";
来源：http://dali.hywenlv.cn/Article/details/gt2zzgsikpg.html

[T42] Perl：变量类型
来源：http://dali.smart0.xyz/Article/details/gt2ppjjbkkn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.haohaochexian.top/Article/details/gt2ydvbbrim.html

[T43] Perl：字符串插值
来源：http://dali.cucudq.cn/Article/details/gt2vptnlpwx.html

"值: $a"
来源：http://dali.jqgufenzy.top/Article/details/gt2fztgfwgv.html

[T44] Perl：条件
来源：http://dali.dashuyun.cn/Article/details/gt2tbmhzolk.html

if ($a > 0) { print "正"; }
来源：http://dali.xuanzx.com/Article/details/gt2cidzwsyj.html

[T45] Perl：数组遍历
来源：http://dali.xuanzx.com/Article/details/gt2gdukqnnb.html

for my $x (@arr) { print $x; }
来源：http://dali.nanxuanxn.top/Article/details/gt2itigtvxl.html

[T46] Perl：哈希操作
来源：http://dali.0kj1m.cn/Article/details/gt2xhjdwhpt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jianghu66.top/Article/details/gt2ebgfasvb.html

[T47] Perl：正则捕获
来源：http://dali.shuidangran.top/Article/details/gt2ktjuhkes.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yj20258.top/Article/details/gt2jztotyly.html

[T48] Perl：正则替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2zzqjtioi.html

$s =~ s/old/new/g;
来源：http://dali.fzhhl.top/Article/details/gt2khnvevbv.html

[T49] Perl：函数
来源：http://dali.ppjwa.cn/Article/details/gt2uvqnddfd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gt2vspndqwg.html

[T50] Perl：逐行读文件
来源：http://dali.ivvv.top/Article/details/gt2nwyktbmp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gzhubu.top/Article/details/gt2ghuyckdh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinqigfzy.top/Article/details/gt2dyykvobu.html

[T51] Scala：Hello World
来源：http://dali.cdnleiting.top/Article/details/gt2plyzozlc.html

println("Hello")
来源：http://dali.aibaodan.cn/Article/details/gt2gnppeucl.html

[T52] Scala：变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2uappoldk.html

val a = 1;  var b = 2
来源：http://dali.hnqzz.top/Article/details/gt2dfucefet.html

[T53] Scala：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gt2gabdxgpi.html

s"值: $b"
来源：http://dali.iojbl.cn/Article/details/gt2rqvzlnxi.html

[T54] Scala：集合映射
来源：http://dali.havefunace.top/Article/details/gt2cfrcyqau.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.smart0.xyz/Article/details/gt2nsgjaeup.html

[T55] Scala：集合过滤
来源：http://dali.tian-w.cn/Article/details/gt2dntihmdc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.snrcjt.cn/Article/details/gt2wioharkx.html

[T56] Scala：样例类
来源：http://dali.andypj.xyz/Article/details/gt2csoruwes.html

case class User(name: String, age: Int)
来源：http://dali.cheryme.top/Article/details/gt2nqktmjkp.html

[T57] Scala：模式匹配
来源：http://dali.yongpay.top/Article/details/gt2eazobyzc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hywenlv.cn/Article/details/gt2wqqdchok.html

[T58] Scala：函数定义
来源：http://dali.shzxlz.cn/Article/details/gt2zdlytcsn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinqigufen.top/Article/details/gt2ezepperf.html

[T59] Scala：循环
来源：http://dali.nwbrower.top/Article/details/gt2lysxgsed.html

for (i <- 1 to 10) println(i)
来源：http://dali.hnqzz.top/Article/details/gt2mtfqybvb.html

[T60] Scala：折叠
来源：http://dali.sufxvd.cn/Article/details/gt2klraesja.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hnqzz.top/Article/details/gt2segitsht.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2tkygsbab.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zycfv.cn/Article/details/gt2unzvbdqb.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2cifhujkb.html

[U01] Py：创建虚拟环境
来源：http://dali.hnxiangtu.top/Article/details/gt2bzvjzctn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.0kj1m.cn/Article/details/gt2lsshgxum.html

[U02] Py：导出 / 安装依赖
来源：http://dali.nwbrower.top/Article/details/gt2xxlbjkml.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hnqzz.top/Article/details/gt2nawpovvv.html

[U03] Py：加载 .env 配置
来源：http://dali.wangdashe.top/Article/details/gt2irunaetc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.smart0.xyz/Article/details/gt2mupleeoz.html

[U04] Py：变量调试打印
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ajcfvygv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jianghu66.top/Article/details/gt2ohzzeqko.html

[U05] Py：列表去重且保序
来源：http://dali.svipenyu.cn/Article/details/gt2dmkuppmp.html

list(dict.fromkeys(arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gowdbhik.html

[U06] Py：合并两个字典
来源：http://dali.ppjwa.cn/Article/details/gt2urxtcquh.html

{**a, **b}
来源：http://dali.wangdashe.top/Article/details/gt2vmlwypuo.html

[U07] Py：反转字典键值
来源：http://dali.yueranfly.top/Article/details/gt2hnskbyri.html

{v: k for k, v in d.items()}
来源：http://dali.gogol.net.cn/Article/details/gt2ktebbdmf.html

[U08] Py：展平二维列表
来源：http://dali.c1oappe.top/Article/details/gt2gnvszfuv.html

[y for x in nested for y in x]
来源：http://dali.zdqjudy.top/Article/details/gt2wtmwekyj.html

[U09] Py：字典取最大值的键
来源：http://dali.nwbrower.top/Article/details/gt2jlbgjbuv.html

max(d, key=d.get)
来源：http://dali.iojbl.cn/Article/details/gt2usxiwvse.html

[U10] Py：按值排序字典
来源：http://dali.chenlongwang.top/Article/details/gt2jgxsvfuw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ybcxt.top/Article/details/gt2vkropqwq.html

[U11] Py：生成器表达式
来源：http://dali.shuidangran.top/Article/details/gt2ferbzcmp.html

(x * 2 for x in arr)
来源：http://dali.tianlin.xyz/Article/details/gt2rgvtxqqx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.chenjidiqi.icu/Article/details/gt2gpxsycnf.html

Counter(arr).most_common(3)
来源：http://dali.yj202588.top/Article/details/gt2xmxudcqa.html

[U13] Py：固定长度队列
来源：http://dali.ivvv.top/Article/details/gt2wdtswslp.html

deque(maxlen=10)
来源：http://dali.zhongyouzk.top/Article/details/gt2ufxtiomp.html

[U14] Py：分组收集到列表
来源：http://dali.shangyingyoupin.top/Article/details/gt2agtjphxy.html

defaultdict(list)
来源：http://dali.cqqwz.cn/Article/details/gt2jioaspxa.html

[U15] Py：高精度计时
来源：http://dali.cucudq.cn/Article/details/gt2pbjapmna.html

t = time.perf_counter()
来源：http://dali.ydzc1.top/Article/details/gt2togqijqr.html

[U16] Py：命令行参数解析
来源：http://dali.meibo888.top/Article/details/gt2bfzmcjuu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hammf.cn/Article/details/gt2yebjmapf.html


<!-- 参考信息 -->