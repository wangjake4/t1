代发 wailian999

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.pycfn.com/Article/details/gt2ovcwphqu.html

[R80] 查看脚本执行耗时
来源：http://dali.jqgfzy.top/Article/details/gt2ockpjoxj.html

time ./run.sh
来源：http://dali.hfpthk.cn/Article/details/gt2muvnjmxm.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2dadafuhb.html

S. C / C++ 专题
来源：http://dali.nanxuanxn.top/Article/details/gt2spamfrhm.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2dxkejzci.html

[S01] C：Hello World
来源：http://dali.nwbrower.top/Article/details/gt2kxkcvhmi.html

#include <stdio.h>
来源：http://dali.xuanzx.com/Article/details/gt2vubuyxvu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sufxvd.cn/Article/details/gt2ulwpdjfa.html

[S02] C：变量与格式化输出
来源：http://dali.0kj1m.cn/Article/details/gt2fxhyhzyi.html

int a = 10; printf("%d\n", a);
来源：http://dali.guowangkeji.top/Article/details/gt2jxpatwjg.html

[S03] C：读入整数
来源：http://dali.yvedp.cn/Article/details/gt2krfztpqr.html

int x; scanf("%d", &x);
来源：http://dali.0kj1m.cn/Article/details/gt2vnknibiq.html

[S04] C：字符串复制
来源：http://dali.snrcjt.cn/Article/details/gt2qpkxtffd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.fengsongda.top/Article/details/gt2cetvugmy.html

[S05] C：字符串长度
来源：http://dali.yonumen.top/Article/details/gt2nlnlmrpc.html

strlen(s)
来源：http://dali.yj20258.top/Article/details/gt2dvpfglkk.html

[S06] C：字符串比较
来源：http://dali.sufxvd.cn/Article/details/gt2nycbyioe.html

strcmp(a, b) == 0
来源：http://dali.pengpengdd.cyou/Article/details/gt2ifplefsf.html

[S07] C：数组遍历求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2toqwhmrl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.redwolf501.top/Article/details/gt2wdaohsmy.html

[S08] C：动态内存分配与释放
来源：http://dali.hongshengwenyu.top/Article/details/gt2rgekrhxe.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cheryme.top/Article/details/gt2lfuimecs.html

[S09] C：结构体定义与初始化
来源：http://dali.daxiang520.top/Article/details/gt2jedyaiir.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jianghu66.top/Article/details/gt2fqtzqsni.html

[S10] C：指针与解引用
来源：http://dali.yanxiufei.cn/Article/details/gt2fecjvvxn.html

int *p = &a;  *p = 5;
来源：http://dali.xylfe.cn/Article/details/gt2vwovxiiq.html

[S11] C：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gt2iohiikbs.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gogol.net.cn/Article/details/gt2ycshmosf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.redwolf501.top/Article/details/gt2vwdufsqb.html

fclose(f);
来源：http://dali.0kj1m.cn/Article/details/gt2rnnocbhm.html

[S12] C：写文件
来源：http://dali.yj202588.top/Article/details/gt2jrwkdgnd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.9152youxi.cn/Article/details/gt2xbmpbuty.html

[S13] C：宏定义
来源：http://dali.jinqigfzy.top/Article/details/gt2rtzewsos.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nanxuanxn.top/Article/details/gt2crezmwev.html

[S14] C：枚举
来源：http://dali.jinqigufen.top/Article/details/gt2kjbhwsqy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hfpthk.cn/Article/details/gt2nndozmgk.html

[S15] C：类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tioashxh.html

(double) a / b
来源：http://dali.yanxiufei.cn/Article/details/gt2nfifjxxm.html

[S16] C：位操作置位
来源：http://dali.hysaishi.cn/Article/details/gt2kiyyduix.html

x |= (1 << 3);
来源：http://dali.yj20258888.top/Article/details/gt2ncltykwt.html

[S17] C：安全拼接字符串
来源：http://dali.chenzaomai.com/Article/details/gt2rpiggtig.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hnxiangtu.top/Article/details/gt2xlzrrvor.html

[S18] C：命令行参数
来源：http://dali.aizwys.cn/Article/details/gt2rzdokgqn.html

int main(int argc, char **argv)
来源：http://dali.xinyue.icu/Article/details/gt2jtqokzwo.html

[S19] C：快速排序
来源：http://dali.hfpthk.cn/Article/details/gt2hvdvbymx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ynvcafwd.html

[S20] C：二分查找
来源：http://dali.xuetiantiany.cn/Article/details/gt2tyijyldi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jyoumei.cn/Article/details/gt2bgkoggvu.html

[S21] C：字符类别判断
来源：http://dali.guannengcc.top/Article/details/gt2xkjouvqj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhoulong.xyz/Article/details/gt2urjmupcq.html

[S22] C：字符串转数字
来源：http://dali.hywenlv.cn/Article/details/gt2jjhvshhv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cashguo.top/Article/details/gt2tblaqzfr.html

[S23] C：随机数
来源：http://dali.fengsongda.top/Article/details/gt2ufmcbpge.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cheryme.top/Article/details/gt2pktquyrq.html

[S24] C：获取本地时间
来源：http://dali.ehwqpu.com/Article/details/gt2ukbnrlip.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.dianchejie.cn/Article/details/gt2rzswahuu.html

[S25] C：内存拷贝
来源：http://dali.zhongyouzk.top/Article/details/gt2ypegufto.html

memcpy(dst, src, n);
来源：http://dali.xziqi.cn/Article/details/gt2aiwhmacw.html

[S26] C：内存清零
来源：http://dali.smart0.xyz/Article/details/gt2imxissez.html

memset(a, 0, sizeof a);
来源：http://dali.xziqi.cn/Article/details/gt2mietuweo.html

[S27] C：定义常量
来源：http://dali.hnqzz.top/Article/details/gt2rfnadgti.html

const double PI = 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gt2nrdkypdr.html

[S28] C：静态变量
来源：http://dali.guowangkeji.top/Article/details/gt2xoizvyit.html

static int counter = 0;
来源：http://dali.cheryme.top/Article/details/gt2wpfakrdm.html

[S29] C：变参函数
来源：http://dali.xuanzx.com/Article/details/gt2jtnxdsky.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ivvv.top/Article/details/gt2srlckdrj.html

[S30] C：头文件保护
来源：http://dali.meibo888.top/Article/details/gt2drzvtkzf.html

#ifndef X_H
来源：http://dali.andypj.xyz/Article/details/gt2aryudbkp.html

#define X_H
来源：http://dali.gogol.net.cn/Article/details/gt2xahlgkps.html

#endif
来源：http://dali.sysykeji.top/Article/details/gt2jmgmbyob.html

[S31] C++：Hello World
来源：http://dali.hammf.cn/Article/details/gt2nlsuqjtp.html

#include <iostream>
来源：http://dali.9152youxi.cn/Article/details/gt2csnigcja.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2thnhxrvg.html

[S32] C++：字符串
来源：http://dali.yueranfly.top/Article/details/gt2dokinhfc.html

std::string s = "hi";  s += "!";
来源：http://dali.jiagoushi.top/Article/details/gt2bzyskcva.html

[S33] C++：vector 增删
来源：http://dali.havefunace.top/Article/details/gt2yxsluqqk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj20258888.top/Article/details/gt2qpltlsej.html

[S34] C++：遍历 vector
来源：http://dali.yvedp.cn/Article/details/gt2oqernjgo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hlfsvcjf.html

[S35] C++：map
来源：http://dali.jqgufenzy.top/Article/details/gt2ymirjtms.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gt2rpfknlau.html

[S36] C++：unordered_map
来源：http://dali.guowangkeji.top/Article/details/gt2lnzarvab.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ybcxt.top/Article/details/gt2zdjhstyf.html

[S37] C++：set
来源：http://dali.svipenyu.cn/Article/details/gt2zjodwiaz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nanxuanxn.top/Article/details/gt2lxrrhqlx.html

[S38] C++：排序
来源：http://dali.tanke756.top/Article/details/gt2tdpoqusi.html

std::sort(v.begin(), v.end());
来源：http://dali.316326.xyz/Article/details/gt2nyckqhop.html

[S39] C++：自定义比较器排序
来源：http://dali.svipenyu.cn/Article/details/gt2dvnxlgrr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guannengcc.top/Article/details/gt2jilmbhxb.html

[S40] C++：查找元素
来源：http://dali.nanxinkj.top/Article/details/gt2rxomomsb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jianghu66.top/Article/details/gt2bgddcjhw.html

[S41] C++：类与构造函数
来源：http://dali.ppjwa.cn/Article/details/gt2dziqngrj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gogol.net.cn/Article/details/gt2zikeerwb.html

[S42] C++：继承与虚函数
来源：http://dali.andypj.xyz/Article/details/gt2fetqnery.html

class B : public Base { public: void f() override {} };
来源：http://dali.nwbrower.top/Article/details/gt2knqsvsnp.html

[S43] C++：智能指针
来源：http://dali.hammf.cn/Article/details/gt2fwjatato.html

auto p = std::make_unique<int>(5);
来源：http://dali.hnxiangtu.top/Article/details/gt2toxetngj.html

[S44] C++：引用传参
来源：http://dali.yueranfly.top/Article/details/gt2yujdrygp.html

void inc(int &x) { ++x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jftrrthe.html

[S45] C++：lambda
来源：http://dali.yj20258.top/Article/details/gt2sgnppnkx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gzhubu.top/Article/details/gt2vqlyzicg.html

[S46] C++：函数模板
来源：http://dali.daria6918.cn/Article/details/gt2gvmrwudu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.smart0.xyz/Article/details/gt2mdoaybdp.html

[S47] C++：结构化绑定遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ydnsecpk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shuidangran.top/Article/details/gt2gckaujrq.html

[S48] C++：逐行读文件
来源：http://dali.cucudq.cn/Article/details/gt2pnqcsqqz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iuhmtqvg.html

while (std::getline(in, line)) { }
来源：http://dali.fengsongda.top/Article/details/gt2xfnlqkym.html

[S49] C++：写文件
来源：http://dali.yj202588.top/Article/details/gt2bycehjqq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.9152youxi.cn/Article/details/gt2zkwtwpqr.html

[S50] C++：格式化数字
来源：http://dali.bjfxy.top/Article/details/gt2nvnfpthc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gt2rbrmuevv.html

[S51] C++：显式类型转换
来源：http://dali.vqdsnc.cn/Article/details/gt2cowirmdf.html

static_cast<double>(a) / b
来源：http://dali.sweek.top/Article/details/gt2paqcndew.html

[S52] C++：const 与 noexcept
来源：http://dali.jinqigufen.top/Article/details/gt2khgjudrq.html

int size() const noexcept { return n_; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2beisfzfd.html

[S53] C++：移动语义
来源：http://dali.xuanzx.com/Article/details/gt2htduqjab.html

std::vector<int> w = std::move(v);
来源：http://dali.gzhubu.top/Article/details/gt2gvrlpxcx.html

[S54] C++：异常处理
来源：http://dali.yuanzhike.top/Article/details/gt2ccxoommi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenjidiqi.icu/Article/details/gt2knirtfwq.html

[S55] C++：结构化绑定
来源：http://dali.yj202588.top/Article/details/gt2ahqrmccb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ltoapjpo.html

[S56] C++：optional
来源：http://dali.hnqzz.top/Article/details/gt2cogimmjd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gaohongyu789.top/Article/details/gt2gouiuoxb.html

[S57] C++：编译期常量
来源：http://dali.xuanzx.com/Article/details/gt2xldoaiyb.html

constexpr int N = 10;
来源：http://dali.fengsongda.top/Article/details/gt2cugeaizz.html

[S58] C++：命名空间
来源：http://dali.gaohongyu789.top/Article/details/gt2ijhdpipx.html

namespace ns { int f() { return 1; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2suvqtmcb.html

[S59] C++：静态断言
来源：http://dali.yongpay.top/Article/details/gt2cevoouge.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jyoumei.cn/Article/details/gt2czmiohod.html

[S60] C++：遍历并删除元素
来源：http://dali.iojbl.cn/Article/details/gt2iqkpeexb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shuidangran.top/Article/details/gt2mraifkau.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2jfsolsoc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xylfe.cn/Article/details/gt2opuryvrj.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2xbjsexes.html

[T01] Kotlin：Hello World
来源：http://dali.haohaochexian.top/Article/details/gt2uuscvvgo.html

println("Hello")
来源：http://dali.hysaishi.cn/Article/details/gt2ltdkswao.html

[T02] Kotlin：变量
来源：http://dali.cqqwz.cn/Article/details/gt2dfxniwwc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ydzc1.top/Article/details/gt2ikslsusr.html

[T03] Kotlin：字符串模板
来源：http://dali.zhongyouzk.top/Article/details/gt2zmxnnqpc.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qajoqyfx.html

[T04] Kotlin：空安全
来源：http://dali.redwolf501.top/Article/details/gt2vuftljsl.html

val n: String? = null;  n?.length
来源：http://dali.iojbl.cn/Article/details/gt2rjufzqig.html

[T05] Kotlin：when 表达式
来源：http://dali.jinqigfzy.top/Article/details/gt2wodvyxcw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tyjregtl.html

[T06] Kotlin：集合映射
来源：http://dali.zhixingplan.top/Article/details/gt2gkzbkcli.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cdnleiting.top/Article/details/gt2vqgvyxlk.html

[T07] Kotlin：集合过滤
来源：http://dali.cqqwz.cn/Article/details/gt2kajftpcx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jqgufenzy.top/Article/details/gt2uvfoojrk.html

[T08] Kotlin：数据类
来源：http://dali.pycfn.com/Article/details/gt2brribmhl.html

data class User(val name: String, val age: Int)
来源：http://dali.zhongyouzk.top/Article/details/gt2ppkljtrf.html

[T09] Kotlin：扩展函数
来源：http://dali.fzhhl.top/Article/details/gt2dpzebcxt.html

fun String.exclaim() = this + "!"
来源：http://dali.zhoulong.xyz/Article/details/gt2jpeayyix.html

[T10] Kotlin：默认参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uyovbzfw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yonumen.top/Article/details/gt2snrjgnqo.html

[T11] Kotlin：协程
来源：http://dali.zhengqikj.top/Article/details/gt2osbzwztb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.aibaodan.cn/Article/details/gt2zlmyrfbv.html

[T12] Kotlin：解构声明
来源：http://dali.yuxming.cn/Article/details/gt2fvzppcku.html

val (a, b) = Pair(1, 2)
来源：http://dali.xziqi.cn/Article/details/gt2agyzafef.html

[T13] Kotlin：只读 Map
来源：http://dali.kuanghao11.cn/Article/details/gt2gmlrspms.html

val m = mapOf("a" to 1)
来源：http://dali.iojbl.cn/Article/details/gt2zimqznfa.html

[T14] Kotlin：循环
来源：http://dali.birdmap.top/Article/details/gt2wiiqytvz.html

for (i in 1..10) println(i)
来源：http://dali.pycfn.com/Article/details/gt2kciugpki.html

[T15] Kotlin：接口
来源：http://dali.mhx1999.top/Article/details/gt2okasxxgi.html

interface Shape { fun area(): Double }
来源：http://dali.jyoumei.cn/Article/details/gt2yjsgzkuu.html

[T16] Swift：Hello World
来源：http://dali.sysykeji.top/Article/details/gt2zunfcaeu.html

print("Hello")
来源：http://dali.jiagoushi.top/Article/details/gt2pnimszzs.html

[T17] Swift：变量与常量
来源：http://dali.iojbl.cn/Article/details/gt2ztgbjpba.html

var a = 1;  let b = 2
来源：http://dali.zycfv.cn/Article/details/gt2talgxadz.html

[T18] Swift：字符串插值
来源：http://dali.ehwqpu.com/Article/details/gt2yljlsipq.html

"值: \(b)"
来源：http://dali.feifeiyinyue.top/Article/details/gt2jylwfkdh.html

[T19] Swift：可选绑定
来源：http://dali.zhixingplan.top/Article/details/gt2qnzhpauu.html

if let n = opt { print(n) }
来源：http://dali.yongpay.top/Article/details/gt2ealiosgk.html

[T20] Swift：数组操作
来源：http://dali.cucudq.cn/Article/details/gt2uqivytbk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.aibaodan.cn/Article/details/gt2ovyibyvy.html

[T21] Swift：遍历
来源：http://dali.jiagoushi.top/Article/details/gt2pzzjhvxl.html

for x in a { print(x) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fznqozhs.html

[T22] Swift：字典
来源：http://dali.yanxiufei.cn/Article/details/gt2twepyyem.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.fzhhl.top/Article/details/gt2rqnrwjuq.html

[T23] Swift：函数
来源：http://dali.316326.xyz/Article/details/gt2bixibbtg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.chenjidiqi.icu/Article/details/gt2wxthjnde.html

[T24] Swift：闭包
来源：http://dali.vqdsnc.cn/Article/details/gt2fattfsgv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gogol.net.cn/Article/details/gt2nkkytdbu.html

[T25] Swift：结构体
来源：http://dali.ppjwa.cn/Article/details/gt2xgfnzmpo.html

struct P { var x: Int }
来源：http://dali.zycfv.cn/Article/details/gt2izownnry.html

[T26] Swift：类与重写
来源：http://dali.tianlin.xyz/Article/details/gt2ihkwujht.html

class A: Base { override func f() {} }
来源：http://dali.tian-w.cn/Article/details/gt2qrdckujx.html

[T27] Swift：错误处理
来源：http://dali.hywenlv.cn/Article/details/gt2vkjrfymh.html

do { try f() } catch { print(error) }
来源：http://dali.nanxinkj.top/Article/details/gt2qjrphspb.html

[T28] Swift：枚举
来源：http://dali.gogol.net.cn/Article/details/gt2nwmzopzm.html

enum Color { case red, green }
来源：http://dali.dashuyun.cn/Article/details/gt2ingcgfqk.html

[T29] Swift：guard 提前返回
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jvqfcury.html

guard let x = opt else { return }
来源：http://dali.shzxlz.cn/Article/details/gt2amslvmry.html

[T30] Swift：协议
来源：http://dali.zhoulong.xyz/Article/details/gt2hbmpkvux.html

protocol Shape { func area() -> Double }
来源：http://dali.andypj.xyz/Article/details/gt2kybbcsan.html

[T31] Lua：Hello World
来源：http://dali.andypj.xyz/Article/details/gt2payqvpql.html

print("Hello")
来源：http://dali.gogol.net.cn/Article/details/gt2fnqyinir.html

[T32] Lua：局部变量
来源：http://dali.yuanzhike.top/Article/details/gt2uhzkimdk.html

local a = 1
来源：http://dali.zhengqikj.top/Article/details/gt2evgjiwty.html

[T33] Lua：表（数组）
来源：http://dali.hnxiangtu.top/Article/details/gt2omabvoxg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ivvv.top/Article/details/gt2arpmrnfn.html

[T34] Lua：遍历表
来源：http://dali.jyoumei.cn/Article/details/gt2mfppzmtl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shangyingyoupin.top/Article/details/gt2epcguowg.html

[T35] Lua：字典表
来源：http://dali.xuanzx.com/Article/details/gt2kwhwtzam.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hzbtmxga.html

[T36] Lua：函数
来源：http://dali.dianchejie.cn/Article/details/gt2toqbcvbn.html

function add(a, b) return a + b end
来源：http://dali.ybcxt.top/Article/details/gt2kzgdpfgr.html

[T37] Lua：字符串拼接
来源：http://dali.yonumen.top/Article/details/gt2hmzlknyk.html

"a" .. "b"
来源：http://dali.zhixingplan.top/Article/details/gt2kcgjlqcu.html

[T38] Lua：条件
来源：http://dali.hysaishi.cn/Article/details/gt2acnvwlio.html

if x > 0 then print("正") end
来源：http://dali.jlsjyb.cn/Article/details/gt2odocojal.html

[T39] Lua：模式匹配
来源：http://dali.pengpengdd.cyou/Article/details/gt2nssevjkr.html

string.find(s, "%d+")
来源：http://dali.yj20258.top/Article/details/gt2lonvmsnu.html

[T40] Lua：元表
来源：http://dali.quarkkingdee.top/Article/details/gt2xzvbjqio.html

setmetatable({}, { __index = base })
来源：http://dali.ehwqpu.com/Article/details/gt2juhgevcj.html

[T41] Perl：Hello World
来源：http://dali.meibo888.top/Article/details/gt2mptbwkyf.html

print "Hello\n";
来源：http://dali.sweek.top/Article/details/gt2kwehzgps.html

[T42] Perl：变量类型
来源：http://dali.fengsongda.top/Article/details/gt2khuvbfux.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.9152youxi.cn/Article/details/gt2ufknkinp.html

[T43] Perl：字符串插值
来源：http://dali.cqqwz.cn/Article/details/gt2phaleefv.html

"值: $a"
来源：http://dali.hnqzz.top/Article/details/gt2ojdikshh.html

[T44] Perl：条件
来源：http://dali.yuxming.cn/Article/details/gt2ljboyvzp.html

if ($a > 0) { print "正"; }
来源：http://dali.gotoacloud.top/Article/details/gt2zcfdbuxb.html

[T45] Perl：数组遍历
来源：http://dali.shuidangran.top/Article/details/gt2nucchmme.html

for my $x (@arr) { print $x; }
来源：http://dali.tianlin.xyz/Article/details/gt2dtvzwgzn.html

[T46] Perl：哈希操作
来源：http://dali.cucudq.cn/Article/details/gt2oubwccnx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zycfv.cn/Article/details/gt2kuepvroz.html

[T47] Perl：正则捕获
来源：http://dali.jianghu66.top/Article/details/gt2hpxxozgp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ppjwa.cn/Article/details/gt2iqlvrvfb.html

[T48] Perl：正则替换
来源：http://dali.fzhhl.top/Article/details/gt2ysuwteme.html

$s =~ s/old/new/g;
来源：http://dali.shangyingyoupin.top/Article/details/gt2uiakaize.html

[T49] Perl：函数
来源：http://dali.cheryme.top/Article/details/gt2yfbkberj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gt2ukfzjvyi.html

[T50] Perl：逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gt2rhzvntzv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.fengsongda.top/Article/details/gt2yspmazzt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.dianchejie.cn/Article/details/gt2ywempfzb.html

[T51] Scala：Hello World
来源：http://dali.cdnleiting.top/Article/details/gt2ryfkxxpy.html

println("Hello")
来源：http://dali.zhengqikj.top/Article/details/gt2atnvprwv.html

[T52] Scala：变量
来源：http://dali.gaohongyu789.top/Article/details/gt2wtyuttpy.html

val a = 1;  var b = 2
来源：http://dali.ehwqpu.com/Article/details/gt2eefwdfbb.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpxhqqq.html

s"值: $b"
来源：http://dali.zhoulong.xyz/Article/details/gt2dhlqhsrl.html

[T54] Scala：集合映射
来源：http://dali.mhx1999.top/Article/details/gt2xeyppbsn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yueranfly.top/Article/details/gt2hvpuacfe.html

[T55] Scala：集合过滤
来源：http://dali.jiagoushi.top/Article/details/gt2ndfqoyqz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.0kj1m.cn/Article/details/gt2fhehboqo.html

[T56] Scala：样例类
来源：http://dali.ppjwa.cn/Article/details/gt2tdeqwgza.html

case class User(name: String, age: Int)
来源：http://dali.zhoulong.xyz/Article/details/gt2yuhcdmwt.html

[T57] Scala：模式匹配
来源：http://dali.yueranfly.top/Article/details/gt2plsyewvh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.sufxvd.cn/Article/details/gt2rjzbpmdt.html

[T58] Scala：函数定义
来源：http://dali.cucudq.cn/Article/details/gt2bnyyymap.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.nwbrower.top/Article/details/gt2gfdcfazu.html

[T59] Scala：循环
来源：http://dali.tanke756.top/Article/details/gt2yqqtxlsf.html

for (i <- 1 to 10) println(i)
来源：http://dali.xylfe.cn/Article/details/gt2cpkviolg.html

[T60] Scala：折叠
来源：http://dali.ppjwa.cn/Article/details/gt2mqrdjger.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.nwbrower.top/Article/details/gt2uuaowqgc.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2skhcchji.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cdnleiting.top/Article/details/gt2okfhyxhs.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2nxeeidqn.html

[U01] Py：创建虚拟环境
来源：http://dali.gogol.net.cn/Article/details/gt2bsghpnsu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtzlcfq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xkqlptds.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sufxvd.cn/Article/details/gt2mkpllcky.html

[U03] Py：加载 .env 配置
来源：http://dali.guannengcc.top/Article/details/gt2mkjmdkot.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hnxgrtgn.html

[U04] Py：变量调试打印
来源：http://dali.zhongyouzk.top/Article/details/gt2wrpdejdx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ydzc1.top/Article/details/gt2nccgtfan.html

[U05] Py：列表去重且保序
来源：http://dali.chenzaomai.com/Article/details/gt2bshizmdg.html

list(dict.fromkeys(arr))
来源：http://dali.kuanghao11.cn/Article/details/gt2vrsrjbcn.html

[U06] Py：合并两个字典
来源：http://dali.ydzc1.top/Article/details/gt2xyfrbdkq.html

{**a, **b}
来源：http://dali.jqgfzy.top/Article/details/gt2sdvjayyz.html

[U07] Py：反转字典键值
来源：http://dali.birdmap.top/Article/details/gt2yxmscdvx.html

{v: k for k, v in d.items()}
来源：http://dali.chenlongwang.top/Article/details/gt2zupktltt.html

[U08] Py：展平二维列表
来源：http://dali.yuxming.cn/Article/details/gt2wutrhise.html

[y for x in nested for y in x]
来源：http://dali.mhx1999.top/Article/details/gt2cnwdfypr.html

[U09] Py：字典取最大值的键
来源：http://dali.sxryk.cn/Article/details/gt2uskduaty.html

max(d, key=d.get)
来源：http://dali.nanxuanxn.top/Article/details/gt2thbdnndw.html

[U10] Py：按值排序字典
来源：http://dali.sysykeji.top/Article/details/gt2wpfiniul.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sweek.top/Article/details/gt2seajlxpb.html

[U11] Py：生成器表达式
来源：http://dali.iojbl.cn/Article/details/gt2qrfpuqrq.html

(x * 2 for x in arr)
来源：http://dali.redwolf501.top/Article/details/gt2jbphzqpv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.dianchejie.cn/Article/details/gt2sksaqmvm.html

Counter(arr).most_common(3)
来源：http://dali.cheryme.top/Article/details/gt2wwokcian.html

[U13] Py：固定长度队列
来源：http://dali.jianghu66.top/Article/details/gt2qkpbiigp.html

deque(maxlen=10)
来源：http://dali.0kj1m.cn/Article/details/gt2hqicppfw.html

[U14] Py：分组收集到列表
来源：http://dali.hfpthk.cn/Article/details/gt2jiobioyn.html

defaultdict(list)
来源：http://dali.hnxiangtu.top/Article/details/gt2dvmyeeel.html

[U15] Py：高精度计时
来源：http://dali.chenzaomai.com/Article/details/gt2cfzqebmb.html

t = time.perf_counter()
来源：http://dali.jianghu66.top/Article/details/gt2ypohgoww.html

[U16] Py：命令行参数解析
来源：http://dali.xinyue.icu/Article/details/gt2mwhevwjf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.aizwys.cn/Article/details/gt2gorlicoz.html

[U17] Py：初始化日志
来源：http://dali.hnxiangtu.top/Article/details/gt2opvykdhl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.daria6918.cn/Article/details/gt2qxwqvtih.html

[U18] Py：预编译正则
来源：http://dali.ehwqpu.com/Article/details/gt2ohmjcyau.html

pat = re.compile(r"\d+")
来源：http://dali.sxryk.cn/Article/details/gt2ifzmmola.html

[U19] Py：正则替换带回调
来源：http://dali.9152youxi.cn/Article/details/gt2iczmpihe.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ssqhbpei.html

[U20] Py：缓存函数结果
来源：http://dali.gaohongyu789.top/Article/details/gt2jixkklhu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hysaishi.cn/Article/details/gt2ypgxzvgo.html


<!-- 参考信息 -->