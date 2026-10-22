代发 wailian999

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xylfe.cn/Article/details/gt2amcyfotc.html

[R80] 查看脚本执行耗时
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uqxxrslv.html

time ./run.sh
来源：http://dali.guowangkeji.top/Article/details/gt2ythyntcu.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2fuxpanwi.html

S. C / C++ 专题
来源：http://dali.xuetiantiany.cn/Article/details/gt2glbmsqng.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2woexdkhj.html

[S01] C：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gt2krsyhfdk.html

#include <stdio.h>
来源：http://dali.haohaochexian.top/Article/details/gt2odocvpjy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shzxlz.cn/Article/details/gt2btztlfeh.html

[S02] C：变量与格式化输出
来源：http://dali.hnxiangtu.top/Article/details/gt2eotsbhdg.html

int a = 10; printf("%d\n", a);
来源：http://dali.sysykeji.top/Article/details/gt2ioxchvxz.html

[S03] C：读入整数
来源：http://dali.chenlongwang.top/Article/details/gt2ymtnpufd.html

int x; scanf("%d", &x);
来源：http://dali.shangyingyoupin.top/Article/details/gt2zyjwoyjg.html

[S04] C：字符串复制
来源：http://dali.havefunace.top/Article/details/gt2ztlbjgxd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gt2qxamkstz.html

[S05] C：字符串长度
来源：http://dali.hongshengwenyu.top/Article/details/gt2fteqopxe.html

strlen(s)
来源：http://dali.aibaodan.cn/Article/details/gt2uqsgqaml.html

[S06] C：字符串比较
来源：http://dali.yj20258888.top/Article/details/gt2cwwhmzqe.html

strcmp(a, b) == 0
来源：http://dali.wangshuangyany.cn/Article/details/gt2rgrbuuau.html

[S07] C：数组遍历求和
来源：http://dali.hammf.cn/Article/details/gt2vbwfbtkw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.haohaochexian.top/Article/details/gt2okuwgkdl.html

[S08] C：动态内存分配与释放
来源：http://dali.jinghuilouyu.cn/Article/details/gt2csiocaht.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.quarkkingdee.top/Article/details/gt2zynssgtv.html

[S09] C：结构体定义与初始化
来源：http://dali.cdnleiting.top/Article/details/gt2jjbfxbft.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.birdmap.top/Article/details/gt2qtjzudnw.html

[S10] C：指针与解引用
来源：http://dali.gotoacloud.top/Article/details/gt2idplhhck.html

int *p = &a;  *p = 5;
来源：http://dali.hfpthk.cn/Article/details/gt2fexcvhld.html

[S11] C：逐行读文件
来源：http://dali.xinyue.icu/Article/details/gt2xddxwuaz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.iojbl.cn/Article/details/gt2zdbsxubw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hnxiangtu.top/Article/details/gt2irrisxvu.html

fclose(f);
来源：http://dali.zycfv.cn/Article/details/gt2pcnktcth.html

[S12] C：写文件
来源：http://dali.hysaishi.cn/Article/details/gt2gzqajfsr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sjlwkpnn.html

[S13] C：宏定义
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ypmhlsbt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ivvv.top/Article/details/gt2ubhvmybd.html

[S14] C：枚举
来源：http://dali.gotoacloud.top/Article/details/gt2rwocsnve.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.feifeiyinyue.top/Article/details/gt2mjczfhax.html

[S15] C：类型转换
来源：http://dali.chenzaomai.com/Article/details/gt2wwmmcdkk.html

(double) a / b
来源：http://dali.9152youxi.cn/Article/details/gt2dizsocnf.html

[S16] C：位操作置位
来源：http://dali.gotoacloud.top/Article/details/gt2hsrimwoi.html

x |= (1 << 3);
来源：http://dali.fengsongda.top/Article/details/gt2nvtegfqg.html

[S17] C：安全拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gt2okgjtkqn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhiwuduotai.top/Article/details/gt2fajkkyiu.html

[S18] C：命令行参数
来源：http://dali.shuidangran.top/Article/details/gt2tltlrhpn.html

int main(int argc, char **argv)
来源：http://dali.xuanzx.com/Article/details/gt2iufzgehz.html

[S19] C：快速排序
来源：http://dali.daxiang520.top/Article/details/gt2nazrdnbn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yvedp.cn/Article/details/gt2mobkiyal.html

[S20] C：二分查找
来源：http://dali.xylfe.cn/Article/details/gt2xeaoqmbe.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.redwolf501.top/Article/details/gt2vprjsjmf.html

[S21] C：字符类别判断
来源：http://dali.aizwys.cn/Article/details/gt2gxzpeyeq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.fzhhl.top/Article/details/gt2cxtwfjiz.html

[S22] C：字符串转数字
来源：http://dali.bjfxy.top/Article/details/gt2wbiiwfvb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.kuanghao11.cn/Article/details/gt2zhglcnln.html

[S23] C：随机数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2drizjbqm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.andypj.xyz/Article/details/gt2dpqddpkm.html

[S24] C：获取本地时间
来源：http://dali.wangshuangyany.cn/Article/details/gt2byeuhqwv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.dashuyun.cn/Article/details/gt2zihuqphu.html

[S25] C：内存拷贝
来源：http://dali.shuidangran.top/Article/details/gt2ylplexni.html

memcpy(dst, src, n);
来源：http://dali.haohaochexian.top/Article/details/gt2tdlbovxd.html

[S26] C：内存清零
来源：http://dali.xylfe.cn/Article/details/gt2nppcbygt.html

memset(a, 0, sizeof a);
来源：http://dali.hongshengwenyu.top/Article/details/gt2cnknpenh.html

[S27] C：定义常量
来源：http://dali.jqgufenzy.top/Article/details/gt2lfvniwlz.html

const double PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gt2mozvcgsf.html

[S28] C：静态变量
来源：http://dali.cqqwz.cn/Article/details/gt2uqumcjwt.html

static int counter = 0;
来源：http://dali.tian-w.cn/Article/details/gt2gfbvpmdg.html

[S29] C：变参函数
来源：http://dali.hnqzz.top/Article/details/gt2pbeyrhmi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.9152youxi.cn/Article/details/gt2jergktzr.html

[S30] C：头文件保护
来源：http://dali.yueranfly.top/Article/details/gt2vqudcvfx.html

#ifndef X_H
来源：http://dali.zhengqikj.top/Article/details/gt2ctxmwtcu.html

#define X_H
来源：http://dali.chenlongwang.top/Article/details/gt2ytphjwsv.html

#endif
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nzuezijm.html

[S31] C++：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gt2bhsoatwu.html

#include <iostream>
来源：http://dali.zhixingplan.top/Article/details/gt2rbsnbiwn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cdnleiting.top/Article/details/gt2lpfiivtg.html

[S32] C++：字符串
来源：http://dali.sysykeji.top/Article/details/gt2wpdhbqbj.html

std::string s = "hi";  s += "!";
来源：http://dali.tianlin.xyz/Article/details/gt2lnhuktgm.html

[S33] C++：vector 增删
来源：http://dali.gaohongyu789.top/Article/details/gt2pqayrntz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shuidangran.top/Article/details/gt2vojcvste.html

[S34] C++：遍历 vector
来源：http://dali.fzhhl.top/Article/details/gt2iejcuwku.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jlsjyb.cn/Article/details/gt2yvihlytw.html

[S35] C++：map
来源：http://dali.bjfxy.top/Article/details/gt2zkaflgzu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gt2ieafscei.html

[S36] C++：unordered_map
来源：http://dali.ydzc1.top/Article/details/gt2ohmlfwqa.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guannengcc.top/Article/details/gt2uyjxfsze.html

[S37] C++：set
来源：http://dali.chenzaomai.com/Article/details/gt2grnwdlqx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jqgfzy.top/Article/details/gt2vhzcrdnm.html

[S38] C++：排序
来源：http://dali.zdqjudy.top/Article/details/gt2xsxurami.html

std::sort(v.begin(), v.end());
来源：http://dali.chenjidiqi.icu/Article/details/gt2jwfnmwhi.html

[S39] C++：自定义比较器排序
来源：http://dali.svipenyu.cn/Article/details/gt2zladltgd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gogol.net.cn/Article/details/gt2upualcjf.html

[S40] C++：查找元素
来源：http://dali.meibo888.top/Article/details/gt2rtlvagxd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ydzc1.top/Article/details/gt2vmbtzeyf.html

[S41] C++：类与构造函数
来源：http://dali.yanxiufei.cn/Article/details/gt2xqixqubb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.feifeiyinyue.top/Article/details/gt2nahjedow.html

[S42] C++：继承与虚函数
来源：http://dali.yueranfly.top/Article/details/gt2vyyhvaxg.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhongyouzk.top/Article/details/gt2cqnyhuff.html

[S43] C++：智能指针
来源：http://dali.andypj.xyz/Article/details/gt2zrquzyly.html

auto p = std::make_unique<int>(5);
来源：http://dali.feifeiyinyue.top/Article/details/gt2hqwaxlab.html

[S44] C++：引用传参
来源：http://dali.yj202588.top/Article/details/gt2dhbxrfpf.html

void inc(int &x) { ++x; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ppckzcfx.html

[S45] C++：lambda
来源：http://dali.yj20258.top/Article/details/gt2kuvlougo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ehwqpu.com/Article/details/gt2ewmnoouz.html

[S46] C++：函数模板
来源：http://dali.zhixingplan.top/Article/details/gt2azgfefdh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ydzc1.top/Article/details/gt2pyopnbtm.html

[S47] C++：结构化绑定遍历
来源：http://dali.redwolf501.top/Article/details/gt2qewaiuxp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.redwolf501.top/Article/details/gt2xentgmxf.html

[S48] C++：逐行读文件
来源：http://dali.tian-w.cn/Article/details/gt2brwckofm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cqqwz.cn/Article/details/gt2ppafveqg.html

while (std::getline(in, line)) { }
来源：http://dali.daxiang520.top/Article/details/gt2hodvlbdp.html

[S49] C++：写文件
来源：http://dali.zhixingplan.top/Article/details/gt2wvagdewy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.dashuyun.cn/Article/details/gt2ckinjazc.html

[S50] C++：格式化数字
来源：http://dali.pycfn.com/Article/details/gt2eigykhyz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.iojbl.cn/Article/details/gt2tsejvydd.html

[S51] C++：显式类型转换
来源：http://dali.tanke756.top/Article/details/gt2wemrcfzx.html

static_cast<double>(a) / b
来源：http://dali.gotoacloud.top/Article/details/gt2edjykgox.html

[S52] C++：const 与 noexcept
来源：http://dali.yj202588.top/Article/details/gt2lyunoeoe.html

int size() const noexcept { return n_; }
来源：http://dali.ybcxt.top/Article/details/gt2bnwpbcof.html

[S53] C++：移动语义
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cphnxlpg.html

std::vector<int> w = std::move(v);
来源：http://dali.yvedp.cn/Article/details/gt2suewonvo.html

[S54] C++：异常处理
来源：http://dali.sufxvd.cn/Article/details/gt2zwzecdlp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.dianchejie.cn/Article/details/gt2nbmulywf.html

[S55] C++：结构化绑定
来源：http://dali.wangdashe.top/Article/details/gt2lxdubhti.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinqigfzy.top/Article/details/gt2vrcqsdiv.html

[S56] C++：optional
来源：http://dali.zhengqikj.top/Article/details/gt2efyiszmi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jqgufenzy.top/Article/details/gt2qedcsknu.html

[S57] C++：编译期常量
来源：http://dali.xziqi.cn/Article/details/gt2dmsserhb.html

constexpr int N = 10;
来源：http://dali.sweek.top/Article/details/gt2qxjgoosd.html

[S58] C++：命名空间
来源：http://dali.zhongyouzk.top/Article/details/gt2vyzjhsrc.html

namespace ns { int f() { return 1; } }
来源：http://dali.9152youxi.cn/Article/details/gt2stwdpueh.html

[S59] C++：静态断言
来源：http://dali.ehwqpu.com/Article/details/gt2ziakbhoa.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jqgufenzy.top/Article/details/gt2mxrnntem.html

[S60] C++：遍历并删除元素
来源：http://dali.xziqi.cn/Article/details/gt2ijwafbck.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yongpay.top/Article/details/gt2hmjvqava.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2zhudxobf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sufxvd.cn/Article/details/gt2plkwwttp.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2yyjpnrxk.html

[T01] Kotlin：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2pvetqqit.html

println("Hello")
来源：http://dali.gotoacloud.top/Article/details/gt2kgxutatz.html

[T02] Kotlin：变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2ijcougpo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qjdemuux.html

[T03] Kotlin：字符串模板
来源：http://dali.gzhubu.top/Article/details/gt2cjfjrsys.html

"值: $b"
来源：http://dali.kuanghao11.cn/Article/details/gt2ascatfhy.html

[T04] Kotlin：空安全
来源：http://dali.xuanzx.com/Article/details/gt2elnmiqxf.html

val n: String? = null;  n?.length
来源：http://dali.tanke756.top/Article/details/gt2cnwwjhaj.html

[T05] Kotlin：when 表达式
来源：http://dali.fzhhl.top/Article/details/gt2uiymbnpg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shangyingyoupin.top/Article/details/gt2mfsqvsib.html

[T06] Kotlin：集合映射
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ahfbuefr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jianghu66.top/Article/details/gt2zfzxscwn.html

[T07] Kotlin：集合过滤
来源：http://dali.vqdsnc.cn/Article/details/gt2khvjzdym.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ehwqpu.com/Article/details/gt2ubbzbhyn.html

[T08] Kotlin：数据类
来源：http://dali.yj202588.top/Article/details/gt2mvczrixy.html

data class User(val name: String, val age: Int)
来源：http://dali.hfpthk.cn/Article/details/gt2lcqxkcge.html

[T09] Kotlin：扩展函数
来源：http://dali.nanxuanxn.top/Article/details/gt2rsogjmiz.html

fun String.exclaim() = this + "!"
来源：http://dali.aizwys.cn/Article/details/gt2bblypprw.html

[T10] Kotlin：默认参数
来源：http://dali.sysykeji.top/Article/details/gt2jugdgbxu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vbugkhoz.html

[T11] Kotlin：协程
来源：http://dali.yuanzhike.top/Article/details/gt2lmwhbfww.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.aizwys.cn/Article/details/gt2sbkuqjfj.html

[T12] Kotlin：解构声明
来源：http://dali.haohaochexian.top/Article/details/gt2eexvhevu.html

val (a, b) = Pair(1, 2)
来源：http://dali.iojbl.cn/Article/details/gt2floiprxj.html

[T13] Kotlin：只读 Map
来源：http://dali.yj20258.top/Article/details/gt2wevsxmuz.html

val m = mapOf("a" to 1)
来源：http://dali.smart0.xyz/Article/details/gt2szwaxgpm.html

[T14] Kotlin：循环
来源：http://dali.sysykeji.top/Article/details/gt2vkcqmxtd.html

for (i in 1..10) println(i)
来源：http://dali.0kj1m.cn/Article/details/gt2hfctfxmj.html

[T15] Kotlin：接口
来源：http://dali.nanxuanxn.top/Article/details/gt2xikbtorv.html

interface Shape { fun area(): Double }
来源：http://dali.jiagoushi.top/Article/details/gt2fipmhxcv.html

[T16] Swift：Hello World
来源：http://dali.hywenlv.cn/Article/details/gt2qcrxsniw.html

print("Hello")
来源：http://dali.birdmap.top/Article/details/gt2tvtbtevq.html

[T17] Swift：变量与常量
来源：http://dali.snrcjt.cn/Article/details/gt2jtethpft.html

var a = 1;  let b = 2
来源：http://dali.mhx1999.top/Article/details/gt2alszucbn.html

[T18] Swift：字符串插值
来源：http://dali.yonumen.top/Article/details/gt2wswvgeie.html

"值: \(b)"
来源：http://dali.gzhubu.top/Article/details/gt2yggmrzys.html

[T19] Swift：可选绑定
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vgdccgtn.html

if let n = opt { print(n) }
来源：http://dali.c1oappe.top/Article/details/gt2uactmqni.html

[T20] Swift：数组操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wmwiwkfn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.iojbl.cn/Article/details/gt2xkqzuqve.html

[T21] Swift：遍历
来源：http://dali.cucudq.cn/Article/details/gt2ylqjievp.html

for x in a { print(x) }
来源：http://dali.guowangkeji.top/Article/details/gt2iwbxnsic.html

[T22] Swift：字典
来源：http://dali.jyoumei.cn/Article/details/gt2ezyyywfa.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jqgfzy.top/Article/details/gt2fjoeddit.html

[T23] Swift：函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rsptbrbp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yuanzhike.top/Article/details/gt2uzqkekds.html

[T24] Swift：闭包
来源：http://dali.smart0.xyz/Article/details/gt2qxinfyqv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hnxiangtu.top/Article/details/gt2ectjqjoi.html

[T25] Swift：结构体
来源：http://dali.pycfn.com/Article/details/gt2cgwbmrvy.html

struct P { var x: Int }
来源：http://dali.xylfe.cn/Article/details/gt2didukzqm.html

[T26] Swift：类与重写
来源：http://dali.yvedp.cn/Article/details/gt2lqsxnaei.html

class A: Base { override func f() {} }
来源：http://dali.zycfv.cn/Article/details/gt2bpoznzps.html

[T27] Swift：错误处理
来源：http://dali.jinqigfzy.top/Article/details/gt2vzfkvkfa.html

do { try f() } catch { print(error) }
来源：http://dali.jinqigfzy.top/Article/details/gt2ewoxllwu.html

[T28] Swift：枚举
来源：http://dali.guannengcc.top/Article/details/gt2vcqoebhs.html

enum Color { case red, green }
来源：http://dali.yonumen.top/Article/details/gt2ivmxjvah.html

[T29] Swift：guard 提前返回
来源：http://dali.meibo888.top/Article/details/gt2rmiuzuvj.html

guard let x = opt else { return }
来源：http://dali.kuanghao11.cn/Article/details/gt2dusybkkw.html

[T30] Swift：协议
来源：http://dali.cqqwz.cn/Article/details/gt2cnpiymfh.html

protocol Shape { func area() -> Double }
来源：http://dali.jianghu66.top/Article/details/gt2ejxpyajv.html

[T31] Lua：Hello World
来源：http://dali.ppjwa.cn/Article/details/gt2qeczkutg.html

print("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ziuwlwmf.html

[T32] Lua：局部变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2cnriduqt.html

local a = 1
来源：http://dali.ivvv.top/Article/details/gt2rfrfngxd.html

[T33] Lua：表（数组）
来源：http://dali.xylfe.cn/Article/details/gt2axkyrill.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qqwgjmeq.html

[T34] Lua：遍历表
来源：http://dali.jlsjyb.cn/Article/details/gt2yhtafqci.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ppjwa.cn/Article/details/gt2tfiizycw.html

[T35] Lua：字典表
来源：http://dali.yj20258.top/Article/details/gt2ctocimuv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hammf.cn/Article/details/gt2siocauff.html

[T36] Lua：函数
来源：http://dali.chenzaomai.com/Article/details/gt2exblbabp.html

function add(a, b) return a + b end
来源：http://dali.jinqigfzy.top/Article/details/gt2cmapkazm.html

[T37] Lua：字符串拼接
来源：http://dali.hongshengwenyu.top/Article/details/gt2ffpitlrg.html

"a" .. "b"
来源：http://dali.gaohongyu789.top/Article/details/gt2juyouayc.html

[T38] Lua：条件
来源：http://dali.zhiwuduotai.top/Article/details/gt2ugvvqwqg.html

if x > 0 then print("正") end
来源：http://dali.iojbl.cn/Article/details/gt2kdeajvqz.html

[T39] Lua：模式匹配
来源：http://dali.gotoacloud.top/Article/details/gt2fsckgaup.html

string.find(s, "%d+")
来源：http://dali.xziqi.cn/Article/details/gt2aigmkyqc.html

[T40] Lua：元表
来源：http://dali.yj20258.top/Article/details/gt2sarmxxed.html

setmetatable({}, { __index = base })
来源：http://dali.xziqi.cn/Article/details/gt2yndmwoaz.html

[T41] Perl：Hello World
来源：http://dali.xylfe.cn/Article/details/gt2aoiagnbi.html

print "Hello\n";
来源：http://dali.cdnleiting.top/Article/details/gt2vhvsziqn.html

[T42] Perl：变量类型
来源：http://dali.yvedp.cn/Article/details/gt2umpfogeu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.svipenyu.cn/Article/details/gt2ytcykalx.html

[T43] Perl：字符串插值
来源：http://dali.yonumen.top/Article/details/gt2lcvxbuoa.html

"值: $a"
来源：http://dali.cqqwz.cn/Article/details/gt2dfzmkvim.html

[T44] Perl：条件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lrqpmqhb.html

if ($a > 0) { print "正"; }
来源：http://dali.xuanzx.com/Article/details/gt2kbcccgdn.html

[T45] Perl：数组遍历
来源：http://dali.ydzc1.top/Article/details/gt2lvpljocm.html

for my $x (@arr) { print $x; }
来源：http://dali.gotoacloud.top/Article/details/gt2zgjmnagx.html

[T46] Perl：哈希操作
来源：http://dali.yuanzhike.top/Article/details/gt2obrdlcac.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zmoojatt.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgbzrel.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.svipenyu.cn/Article/details/gt2uydwlapm.html

[T48] Perl：正则替换
来源：http://dali.chenlongwang.top/Article/details/gt2dltjoomf.html

$s =~ s/old/new/g;
来源：http://dali.cashguo.top/Article/details/gt2gdoidhyn.html

[T49] Perl：函数
来源：http://dali.hywenlv.cn/Article/details/gt2ezlgaicy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gt2skkxdmxa.html

[T50] Perl：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gt2ctrsrrzp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ynltsdfv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ivvv.top/Article/details/gt2vhwtbcvo.html

[T51] Scala：Hello World
来源：http://dali.snrcjt.cn/Article/details/gt2heflncwl.html

println("Hello")
来源：http://dali.tianlin.xyz/Article/details/gt2kuereoxg.html

[T52] Scala：变量
来源：http://dali.fzhhl.top/Article/details/gt2bofnhyrn.html

val a = 1;  var b = 2
来源：http://dali.cashguo.top/Article/details/gt2zjvjnrlv.html

[T53] Scala：字符串插值
来源：http://dali.yj202588.top/Article/details/gt2jqmpntoe.html

s"值: $b"
来源：http://dali.gaohongyu789.top/Article/details/gt2rxryaebu.html

[T54] Scala：集合映射
来源：http://dali.jqgufenzy.top/Article/details/gt2ihtywejm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.redwolf501.top/Article/details/gt2chnvhpzi.html

[T55] Scala：集合过滤
来源：http://dali.kuanghao11.cn/Article/details/gt2mpavslqd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cdnleiting.top/Article/details/gt2ewkqtnpl.html

[T56] Scala：样例类
来源：http://dali.jlsjyb.cn/Article/details/gt2hankhfkg.html

case class User(name: String, age: Int)
来源：http://dali.fzhhl.top/Article/details/gt2jnuikljr.html

[T57] Scala：模式匹配
来源：http://dali.yj20258888.top/Article/details/gt2lulqvmfk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gmtkbjia.html

[T58] Scala：函数定义
来源：http://dali.jyoumei.cn/Article/details/gt2wypnjaih.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yanxiufei.cn/Article/details/gt2elyzohwm.html

[T59] Scala：循环
来源：http://dali.guannengcc.top/Article/details/gt2pzocxllq.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhixingplan.top/Article/details/gt2fshyvrka.html

[T60] Scala：折叠
来源：http://dali.hongshengwenyu.top/Article/details/gt2tbevtgpo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ybcxt.top/Article/details/gt2qetzepmg.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2awxolcov.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hywenlv.cn/Article/details/gt2tlgtnnxb.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2rwkqgccj.html

[U01] Py：创建虚拟环境
来源：http://dali.hammf.cn/Article/details/gt2nekwlreo.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.c1oappe.top/Article/details/gt2ooaaadsh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.chenjidiqi.icu/Article/details/gt2etsfxels.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ppjwa.cn/Article/details/gt2jnaoazdd.html

[U03] Py：加载 .env 配置
来源：http://dali.cashguo.top/Article/details/gt2tqkcnvbr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jinqigfzy.top/Article/details/gt2pdmtzisl.html

[U04] Py：变量调试打印
来源：http://dali.ydzc1.top/Article/details/gt2ygkfdrse.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zycfv.cn/Article/details/gt2snnyjtdk.html

[U05] Py：列表去重且保序
来源：http://dali.zhongyouzk.top/Article/details/gt2bboqczdg.html

list(dict.fromkeys(arr))
来源：http://dali.cqqwz.cn/Article/details/gt2gqiyhrer.html

[U06] Py：合并两个字典
来源：http://dali.shangyingyoupin.top/Article/details/gt2qgipkuwz.html

{**a, **b}
来源：http://dali.jinqigufen.top/Article/details/gt2bqqspdoj.html

[U07] Py：反转字典键值
来源：http://dali.ybcxt.top/Article/details/gt2gyqzaoem.html

{v: k for k, v in d.items()}
来源：http://dali.0kj1m.cn/Article/details/gt2rurspkgd.html

[U08] Py：展平二维列表
来源：http://dali.tian-w.cn/Article/details/gt2bxkwqbkl.html

[y for x in nested for y in x]
来源：http://dali.iojbl.cn/Article/details/gt2idpgckls.html

[U09] Py：字典取最大值的键
来源：http://dali.sweek.top/Article/details/gt2ngutuhnp.html

max(d, key=d.get)
来源：http://dali.c1oappe.top/Article/details/gt2pjxkxmro.html

[U10] Py：按值排序字典
来源：http://dali.cashguo.top/Article/details/gt2euaefptn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jqgfzy.top/Article/details/gt2zexjlxwl.html

[U11] Py：生成器表达式
来源：http://dali.guowangkeji.top/Article/details/gt2avxflcxp.html

(x * 2 for x in arr)
来源：http://dali.cashguo.top/Article/details/gt2gjwatvns.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.guowangkeji.top/Article/details/gt2btapkcls.html

Counter(arr).most_common(3)
来源：http://dali.yonumen.top/Article/details/gt2scceqdxd.html

[U13] Py：固定长度队列
来源：http://dali.yueranfly.top/Article/details/gt2kvfyvria.html

deque(maxlen=10)
来源：http://dali.hammf.cn/Article/details/gt2asuiwxuk.html

[U14] Py：分组收集到列表
来源：http://dali.quarkkingdee.top/Article/details/gt2zioopyip.html

defaultdict(list)
来源：http://dali.cqqwz.cn/Article/details/gt2pmfvfkfr.html

[U15] Py：高精度计时
来源：http://dali.yonumen.top/Article/details/gt2ubcbdfzb.html

t = time.perf_counter()
来源：http://dali.sysykeji.top/Article/details/gt2pwcjsclb.html

[U16] Py：命令行参数解析
来源：http://dali.cucudq.cn/Article/details/gt2kykskyye.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinqigufen.top/Article/details/gt2mcsnotqm.html

[U17] Py：初始化日志
来源：http://dali.yuanzhike.top/Article/details/gt2vbhtkzch.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ppjwa.cn/Article/details/gt2ojupgwxf.html

[U18] Py：预编译正则
来源：http://dali.svipenyu.cn/Article/details/gt2sfurrcjz.html

pat = re.compile(r"\d+")
来源：http://dali.aizwys.cn/Article/details/gt2gbqdgvoo.html

[U19] Py：正则替换带回调
来源：http://dali.yangfankeji.com/Article/details/gt2zavgdwci.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.guannengcc.top/Article/details/gt2jvaznvux.html

[U20] Py：缓存函数结果
来源：http://dali.cashguo.top/Article/details/gt2phawqnek.html

@functools.lru_cache(maxsize=None)
来源：http://dali.kuanghao11.cn/Article/details/gt2pnnuzcom.html


<!-- 参考信息 -->