代发 wailian999

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.wangdashe.top/Article/details/gt2lpgzsdqe.html

[R80] 查看脚本执行耗时
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ikzjnsfw.html

time ./run.sh
来源：http://dali.chenzaomai.com/Article/details/gt2awzcjutf.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2scekdvrv.html

S. C / C++ 专题
来源：http://dali.feifeiyinyue.top/Article/details/gt2qcthkewl.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2jqhsiyca.html

[S01] C：Hello World
来源：http://dali.zhixingplan.top/Article/details/gt2hbxdebqs.html

#include <stdio.h>
来源：http://dali.jlsjyb.cn/Article/details/gt2kxbaujnr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ehwqpu.com/Article/details/gt2iilehetu.html

[S02] C：变量与格式化输出
来源：http://dali.xuanzx.com/Article/details/gt2wreecffv.html

int a = 10; printf("%d\n", a);
来源：http://dali.jqgfzy.top/Article/details/gt2siizbvnq.html

[S03] C：读入整数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cltdirsj.html

int x; scanf("%d", &x);
来源：http://dali.ppjwa.cn/Article/details/gt2rmxwdwae.html

[S04] C：字符串复制
来源：http://dali.xuanzx.com/Article/details/gt2tctihwex.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hhncrfab.html

[S05] C：字符串长度
来源：http://dali.jqgfzy.top/Article/details/gt2hpmvadwk.html

strlen(s)
来源：http://dali.sufxvd.cn/Article/details/gt2lbccmnxu.html

[S06] C：字符串比较
来源：http://dali.ehwqpu.com/Article/details/gt2wspkgknd.html

strcmp(a, b) == 0
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nmkzyoaz.html

[S07] C：数组遍历求和
来源：http://dali.jyoumei.cn/Article/details/gt2zcvakrte.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xinyue.icu/Article/details/gt2cidbrncc.html

[S08] C：动态内存分配与释放
来源：http://dali.dashuyun.cn/Article/details/gt2ccatqqom.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nwbrower.top/Article/details/gt2upwduwej.html

[S09] C：结构体定义与初始化
来源：http://dali.jinqigufen.top/Article/details/gt2qyhhaymd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.c1oappe.top/Article/details/gt2mlhefudw.html

[S10] C：指针与解引用
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ykvmzpkl.html

int *p = &a;  *p = 5;
来源：http://dali.redwolf501.top/Article/details/gt2wvazfkal.html

[S11] C：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gt2npvzeijo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shuidangran.top/Article/details/gt2dfrcszhm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hnqzz.top/Article/details/gt2zvwdkfub.html

fclose(f);
来源：http://dali.jianghu66.top/Article/details/gt2zwrvrdpn.html

[S12] C：写文件
来源：http://dali.aizwys.cn/Article/details/gt2uhzjehyj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gzhubu.top/Article/details/gt2uurrzogt.html

[S13] C：宏定义
来源：http://dali.hywenlv.cn/Article/details/gt2ycokitcq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.pycfn.com/Article/details/gt2ctkicqgw.html

[S14] C：枚举
来源：http://dali.jinqigfzy.top/Article/details/gt2jysezpxb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.bjfxy.top/Article/details/gt2evjhghiv.html

[S15] C：类型转换
来源：http://dali.zhixingplan.top/Article/details/gt2nnyykteb.html

(double) a / b
来源：http://dali.yvedp.cn/Article/details/gt2olxsbuep.html

[S16] C：位操作置位
来源：http://dali.ehwqpu.com/Article/details/gt2jkjwgqvp.html

x |= (1 << 3);
来源：http://dali.yj20258888.top/Article/details/gt2rotcubuq.html

[S17] C：安全拼接字符串
来源：http://dali.hywenlv.cn/Article/details/gt2ftpdwcbc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.0kj1m.cn/Article/details/gt2ioikjcyq.html

[S18] C：命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gt2iltpghnr.html

int main(int argc, char **argv)
来源：http://dali.gogol.net.cn/Article/details/gt2pkuwcbdp.html

[S19] C：快速排序
来源：http://dali.jqgfzy.top/Article/details/gt2papekprn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yanxiufei.cn/Article/details/gt2flrzgvem.html

[S20] C：二分查找
来源：http://dali.jinqigufen.top/Article/details/gt2mdjcsuxi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hfdwsjdk.html

[S21] C：字符类别判断
来源：http://dali.vqdsnc.cn/Article/details/gt2siocmcdy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenzaomai.com/Article/details/gt2fubqkhib.html

[S22] C：字符串转数字
来源：http://dali.havefunace.top/Article/details/gt2abxypqsi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.fengsongda.top/Article/details/gt2gviamzlr.html

[S23] C：随机数
来源：http://dali.fengsongda.top/Article/details/gt2dyzmaxqw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.andypj.xyz/Article/details/gt2ujgygthl.html

[S24] C：获取本地时间
来源：http://dali.daria6918.cn/Article/details/gt2hnvwvwct.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.dianchejie.cn/Article/details/gt2mxwvqkje.html

[S25] C：内存拷贝
来源：http://dali.9152youxi.cn/Article/details/gt2afhjjcvo.html

memcpy(dst, src, n);
来源：http://dali.svipenyu.cn/Article/details/gt2jxadzruz.html

[S26] C：内存清零
来源：http://dali.yuxming.cn/Article/details/gt2vfyqgjqz.html

memset(a, 0, sizeof a);
来源：http://dali.zdqjudy.top/Article/details/gt2ktzuqcbb.html

[S27] C：定义常量
来源：http://dali.yvedp.cn/Article/details/gt2gudqlvag.html

const double PI = 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gt2vsxnteqj.html

[S28] C：静态变量
来源：http://dali.hysaishi.cn/Article/details/gt2sbtsyhdt.html

static int counter = 0;
来源：http://dali.hammf.cn/Article/details/gt2dbbpedui.html

[S29] C：变参函数
来源：http://dali.bjfxy.top/Article/details/gt2cwevblnx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gogol.net.cn/Article/details/gt2cybxpgzd.html

[S30] C：头文件保护
来源：http://dali.havefunace.top/Article/details/gt2tvwuqsym.html

#ifndef X_H
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nzywawbj.html

#define X_H
来源：http://dali.yj20258888.top/Article/details/gt2etfivqri.html

#endif
来源：http://dali.zhixingplan.top/Article/details/gt2efzxjtmz.html

[S31] C++：Hello World
来源：http://dali.zhixingplan.top/Article/details/gt2xucoawmh.html

#include <iostream>
来源：http://dali.cqqwz.cn/Article/details/gt2vpvwwsbu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ivvv.top/Article/details/gt2avurhyxg.html

[S32] C++：字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2caicaogg.html

std::string s = "hi";  s += "!";
来源：http://dali.tian-w.cn/Article/details/gt2pzxvakpx.html

[S33] C++：vector 增删
来源：http://dali.9152youxi.cn/Article/details/gt2qotczwur.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhongyouzk.top/Article/details/gt2srczpwph.html

[S34] C++：遍历 vector
来源：http://dali.xuetiantiany.cn/Article/details/gt2qouvmpqq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sysykeji.top/Article/details/gt2aclzskhl.html

[S35] C++：map
来源：http://dali.zhiwuduotai.top/Article/details/gt2mirxxeha.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sysykeji.top/Article/details/gt2gfukglrv.html

[S36] C++：unordered_map
来源：http://dali.wangshuangyany.cn/Article/details/gt2mauwbuzm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gt2cnfzyknd.html

[S37] C++：set
来源：http://dali.xziqi.cn/Article/details/gt2dogoxcpi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gzhubu.top/Article/details/gt2gltipftc.html

[S38] C++：排序
来源：http://dali.gaohongyu789.top/Article/details/gt2ettewhjk.html

std::sort(v.begin(), v.end());
来源：http://dali.chenlongwang.top/Article/details/gt2pgwwdpnu.html

[S39] C++：自定义比较器排序
来源：http://dali.yanxiufei.cn/Article/details/gt2smdixrtm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.fzhhl.top/Article/details/gt2fppzwsmt.html

[S40] C++：查找元素
来源：http://dali.dashuyun.cn/Article/details/gt2imoxpimm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.svipenyu.cn/Article/details/gt2sotmsjts.html

[S41] C++：类与构造函数
来源：http://dali.cucudq.cn/Article/details/gt2izkomyyg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.pycfn.com/Article/details/gt2ehmyugua.html

[S42] C++：继承与虚函数
来源：http://dali.aibaodan.cn/Article/details/gt2npioosgh.html

class B : public Base { public: void f() override {} };
来源：http://dali.c1oappe.top/Article/details/gt2fflhfbwn.html

[S43] C++：智能指针
来源：http://dali.meibo888.top/Article/details/gt2xhdqholh.html

auto p = std::make_unique<int>(5);
来源：http://dali.sxryk.cn/Article/details/gt2nlztzajf.html

[S44] C++：引用传参
来源：http://dali.nanxuanxn.top/Article/details/gt2mkxiwbcq.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbwriob.html

[S45] C++：lambda
来源：http://dali.jqgufenzy.top/Article/details/gt2josstqqc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yvedp.cn/Article/details/gt2pexjshpx.html

[S46] C++：函数模板
来源：http://dali.xuanzx.com/Article/details/gt2ebmounrj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yuxming.cn/Article/details/gt2zkfuetfr.html

[S47] C++：结构化绑定遍历
来源：http://dali.guowangkeji.top/Article/details/gt2altbxhik.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhixingplan.top/Article/details/gt2ajbgjgmu.html

[S48] C++：逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gt2govesmxn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhengqikj.top/Article/details/gt2hdvxdato.html

while (std::getline(in, line)) { }
来源：http://dali.zhongyouzk.top/Article/details/gt2sspdkxnc.html

[S49] C++：写文件
来源：http://dali.zhongyouzk.top/Article/details/gt2zajojnaa.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhengqikj.top/Article/details/gt2uehsszob.html

[S50] C++：格式化数字
来源：http://dali.redwolf501.top/Article/details/gt2zzjgqxlo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xsvllcbg.html

[S51] C++：显式类型转换
来源：http://dali.pycfn.com/Article/details/gt2ktmnuurk.html

static_cast<double>(a) / b
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pxhlvouj.html

[S52] C++：const 与 noexcept
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wshxgthh.html

int size() const noexcept { return n_; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2sspxsyks.html

[S53] C++：移动语义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ykrfkdzb.html

std::vector<int> w = std::move(v);
来源：http://dali.redwolf501.top/Article/details/gt2fbdthicc.html

[S54] C++：异常处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2biwailjp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xziqi.cn/Article/details/gt2wznemwcu.html

[S55] C++：结构化绑定
来源：http://dali.nanxinkj.top/Article/details/gt2ywhjryrc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.daria6918.cn/Article/details/gt2tpnhzruk.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2wuddmxfo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cqqwz.cn/Article/details/gt2qvnlhbwn.html

[S57] C++：编译期常量
来源：http://dali.andypj.xyz/Article/details/gt2gajrmzwo.html

constexpr int N = 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nzjwbafz.html

[S58] C++：命名空间
来源：http://dali.cqqwz.cn/Article/details/gt2nuphhwuu.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinqigufen.top/Article/details/gt2fpfcyzpe.html

[S59] C++：静态断言
来源：http://dali.jqgfzy.top/Article/details/gt2nwysvlxz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shuidangran.top/Article/details/gt2xbimjbji.html

[S60] C++：遍历并删除元素
来源：http://dali.andypj.xyz/Article/details/gt2llpbffeb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zycfv.cn/Article/details/gt2yvmzetub.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2jzbqvshu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.dianchejie.cn/Article/details/gt2bmgvswox.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2ycfbzxlp.html

[T01] Kotlin：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gt2yfmjqsal.html

println("Hello")
来源：http://dali.daxiang520.top/Article/details/gt2tyfjnaib.html

[T02] Kotlin：变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ljqyxxyc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sufxvd.cn/Article/details/gt2lsgtbivw.html

[T03] Kotlin：字符串模板
来源：http://dali.gaohongyu789.top/Article/details/gt2zgmugkel.html

"值: $b"
来源：http://dali.hywenlv.cn/Article/details/gt2nlufuadv.html

[T04] Kotlin：空安全
来源：http://dali.havefunace.top/Article/details/gt2rdigccfu.html

val n: String? = null;  n?.length
来源：http://dali.yuanzhike.top/Article/details/gt2luvafcki.html

[T05] Kotlin：when 表达式
来源：http://dali.daria6918.cn/Article/details/gt2vylcdtqz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.nanxinkj.top/Article/details/gt2dzvmowlt.html

[T06] Kotlin：集合映射
来源：http://dali.hfpthk.cn/Article/details/gt2xzyasbaf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenlongwang.top/Article/details/gt2hhuakyyu.html

[T07] Kotlin：集合过滤
来源：http://dali.redwolf501.top/Article/details/gt2polapipp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vpemfkrg.html

[T08] Kotlin：数据类
来源：http://dali.sxryk.cn/Article/details/gt2dimfoyfz.html

data class User(val name: String, val age: Int)
来源：http://dali.chenlongwang.top/Article/details/gt2kilsedxx.html

[T09] Kotlin：扩展函数
来源：http://dali.zhengqikj.top/Article/details/gt2kigjzazu.html

fun String.exclaim() = this + "!"
来源：http://dali.iojbl.cn/Article/details/gt2thgfozxe.html

[T10] Kotlin：默认参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2ttsowepp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xmdvwmxj.html

[T11] Kotlin：协程
来源：http://dali.snrcjt.cn/Article/details/gt2ghfwywjs.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.chenjidiqi.icu/Article/details/gt2wlhednrk.html

[T12] Kotlin：解构声明
来源：http://dali.316326.xyz/Article/details/gt2yojlltyi.html

val (a, b) = Pair(1, 2)
来源：http://dali.aibaodan.cn/Article/details/gt2fupdkfne.html

[T13] Kotlin：只读 Map
来源：http://dali.c1oappe.top/Article/details/gt2tisjowfo.html

val m = mapOf("a" to 1)
来源：http://dali.hammf.cn/Article/details/gt2jayryzpo.html

[T14] Kotlin：循环
来源：http://dali.ybcxt.top/Article/details/gt2jrzowbxd.html

for (i in 1..10) println(i)
来源：http://dali.guowangkeji.top/Article/details/gt2wxfwyhzl.html

[T15] Kotlin：接口
来源：http://dali.hysaishi.cn/Article/details/gt2wpiliqkd.html

interface Shape { fun area(): Double }
来源：http://dali.0kj1m.cn/Article/details/gt2jravtxxh.html

[T16] Swift：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hmuelrsj.html

print("Hello")
来源：http://dali.shuidangran.top/Article/details/gt2koxgozos.html

[T17] Swift：变量与常量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2elewggzj.html

var a = 1;  let b = 2
来源：http://dali.tian-w.cn/Article/details/gt2ayotrbuo.html

[T18] Swift：字符串插值
来源：http://dali.hongshengwenyu.top/Article/details/gt2fouufdap.html

"值: \(b)"
来源：http://dali.jinqigfzy.top/Article/details/gt2lkomdztu.html

[T19] Swift：可选绑定
来源：http://dali.kuanghao11.cn/Article/details/gt2lymeebal.html

if let n = opt { print(n) }
来源：http://dali.gogol.net.cn/Article/details/gt2dsrkbsdg.html

[T20] Swift：数组操作
来源：http://dali.jyoumei.cn/Article/details/gt2smjxrdqb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.aibaodan.cn/Article/details/gt2kyekmfne.html

[T21] Swift：遍历
来源：http://dali.zycfv.cn/Article/details/gt2dshmclwf.html

for x in a { print(x) }
来源：http://dali.meibo888.top/Article/details/gt2joxszbqe.html

[T22] Swift：字典
来源：http://dali.yanxiufei.cn/Article/details/gt2ezyylnvn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.svipenyu.cn/Article/details/gt2fgxvowbg.html

[T23] Swift：函数
来源：http://dali.guowangkeji.top/Article/details/gt2pmlmxddz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.wangshuangyany.cn/Article/details/gt2paskjtxk.html

[T24] Swift：闭包
来源：http://dali.jqgufenzy.top/Article/details/gt2ebhcehfv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hysaishi.cn/Article/details/gt2pwgbnygd.html

[T25] Swift：结构体
来源：http://dali.0kj1m.cn/Article/details/gt2fsdoxctp.html

struct P { var x: Int }
来源：http://dali.zhoulong.xyz/Article/details/gt2jprobwey.html

[T26] Swift：类与重写
来源：http://dali.sxryk.cn/Article/details/gt2scpdlhkm.html

class A: Base { override func f() {} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kbgkpyvd.html

[T27] Swift：错误处理
来源：http://dali.fzhhl.top/Article/details/gt2mqrtljgz.html

do { try f() } catch { print(error) }
来源：http://dali.quarkkingdee.top/Article/details/gt2qwzyxzif.html

[T28] Swift：枚举
来源：http://dali.nwbrower.top/Article/details/gt2gihwpgpq.html

enum Color { case red, green }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fmqxswfh.html

[T29] Swift：guard 提前返回
来源：http://dali.jinqigufen.top/Article/details/gt2kztkqteo.html

guard let x = opt else { return }
来源：http://dali.tian-w.cn/Article/details/gt2crvidsfx.html

[T30] Swift：协议
来源：http://dali.gotoacloud.top/Article/details/gt2unifdszt.html

protocol Shape { func area() -> Double }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2piaayxzc.html

[T31] Lua：Hello World
来源：http://dali.hfpthk.cn/Article/details/gt2fdijocjd.html

print("Hello")
来源：http://dali.shzxlz.cn/Article/details/gt2cfakzvpt.html

[T32] Lua：局部变量
来源：http://dali.tianlin.xyz/Article/details/gt2fuihlyhm.html

local a = 1
来源：http://dali.yj20258888.top/Article/details/gt2gfdplkhp.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbnwsdm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.iojbl.cn/Article/details/gt2avpqmyiq.html

[T34] Lua：遍历表
来源：http://dali.hongshengwenyu.top/Article/details/gt2kffpfeah.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.daxiang520.top/Article/details/gt2qulclqtv.html

[T35] Lua：字典表
来源：http://dali.ybcxt.top/Article/details/gt2vufmaqxh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yuanzhike.top/Article/details/gt2vruyrnpo.html

[T36] Lua：函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2ukbicbwt.html

function add(a, b) return a + b end
来源：http://dali.tian-w.cn/Article/details/gt2dpxzppqe.html

[T37] Lua：字符串拼接
来源：http://dali.mhx1999.top/Article/details/gt2vgmlogom.html

"a" .. "b"
来源：http://dali.meibo888.top/Article/details/gt2xdozwbho.html

[T38] Lua：条件
来源：http://dali.jyoumei.cn/Article/details/gt2ggrijgbk.html

if x > 0 then print("正") end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bkpmgcgj.html

[T39] Lua：模式匹配
来源：http://dali.xinyue.icu/Article/details/gt2wldnddlv.html

string.find(s, "%d+")
来源：http://dali.birdmap.top/Article/details/gt2iizvlzhy.html

[T40] Lua：元表
来源：http://dali.kuanghao11.cn/Article/details/gt2naxicmzp.html

setmetatable({}, { __index = base })
来源：http://dali.gzhubu.top/Article/details/gt2bxnsezlb.html

[T41] Perl：Hello World
来源：http://dali.xuanzx.com/Article/details/gt2csrtirpq.html

print "Hello\n";
来源：http://dali.yj20258.top/Article/details/gt2lzwrumda.html

[T42] Perl：变量类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2skwkdino.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.aizwys.cn/Article/details/gt2mxcwwiig.html

[T43] Perl：字符串插值
来源：http://dali.zdqjudy.top/Article/details/gt2kltolzhf.html

"值: $a"
来源：http://dali.316326.xyz/Article/details/gt2wdrlthfg.html

[T44] Perl：条件
来源：http://dali.sxryk.cn/Article/details/gt2zntjlgsn.html

if ($a > 0) { print "正"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2eqwyfcoc.html

[T45] Perl：数组遍历
来源：http://dali.jiagoushi.top/Article/details/gt2qupydoog.html

for my $x (@arr) { print $x; }
来源：http://dali.jinqigfzy.top/Article/details/gt2wtmvjhis.html

[T46] Perl：哈希操作
来源：http://dali.shangyingyoupin.top/Article/details/gt2cmrmnumk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shzxlz.cn/Article/details/gt2fgzvwdgl.html

[T47] Perl：正则捕获
来源：http://dali.jinqigufen.top/Article/details/gt2wdmxnajq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.daxiang520.top/Article/details/gt2lyfklwfk.html

[T48] Perl：正则替换
来源：http://dali.nanxuanxn.top/Article/details/gt2cpbtcbml.html

$s =~ s/old/new/g;
来源：http://dali.sysykeji.top/Article/details/gt2dwtwkmfv.html

[T49] Perl：函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2otselqil.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gogol.net.cn/Article/details/gt2ltrjaars.html

[T50] Perl：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gt2cyayuftl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ziqsxocl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.mhx1999.top/Article/details/gt2pbsustld.html

[T51] Scala：Hello World
来源：http://dali.iojbl.cn/Article/details/gt2hhighmns.html

println("Hello")
来源：http://dali.yj202588.top/Article/details/gt2mfsvstjh.html

[T52] Scala：变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bpbrulpj.html

val a = 1;  var b = 2
来源：http://dali.cqqwz.cn/Article/details/gt2iyjiqikg.html

[T53] Scala：字符串插值
来源：http://dali.hywenlv.cn/Article/details/gt2rwowqozc.html

s"值: $b"
来源：http://dali.tian-w.cn/Article/details/gt2holxbfau.html

[T54] Scala：集合映射
来源：http://dali.svipenyu.cn/Article/details/gt2heqloibz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jqgfzy.top/Article/details/gt2uqkyasvl.html

[T55] Scala：集合过滤
来源：http://dali.redwolf501.top/Article/details/gt2mqrjaetm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ecvppajm.html

[T56] Scala：样例类
来源：http://dali.chenzaomai.com/Article/details/gt2agsojptj.html

case class User(name: String, age: Int)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2abwpwesu.html

[T57] Scala：模式匹配
来源：http://dali.xinyue.icu/Article/details/gt2mogshbgv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hnxiangtu.top/Article/details/gt2zbmnenzq.html

[T58] Scala：函数定义
来源：http://dali.xuanzx.com/Article/details/gt2lfmzzudn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hongshengwenyu.top/Article/details/gt2ljsdgdyo.html

[T59] Scala：循环
来源：http://dali.sysykeji.top/Article/details/gt2lgcfteke.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhengqikj.top/Article/details/gt2wmzxxifs.html

[T60] Scala：折叠
来源：http://dali.smart0.xyz/Article/details/gt2kqlunltg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.chenlongwang.top/Article/details/gt2avgyyaxm.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2lnrgwuhz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.wangshuangyany.cn/Article/details/gt2edfyhnto.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2jzmwccxo.html

[U01] Py：创建虚拟环境
来源：http://dali.hongshengwenyu.top/Article/details/gt2dxidpuvr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yuxming.cn/Article/details/gt2jeollfmj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.meibo888.top/Article/details/gt2adexiuaj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhongyouzk.top/Article/details/gt2jmiuzmkd.html

[U03] Py：加载 .env 配置
来源：http://dali.quarkkingdee.top/Article/details/gt2owvhkqhc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.mhx1999.top/Article/details/gt2iirkoqhi.html

[U04] Py：变量调试打印
来源：http://dali.shangyingyoupin.top/Article/details/gt2nxxgnlga.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.dianchejie.cn/Article/details/gt2dlscerip.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvxhger.html

list(dict.fromkeys(arr))
来源：http://dali.quarkkingdee.top/Article/details/gt2gluoegga.html

[U06] Py：合并两个字典
来源：http://dali.shuidangran.top/Article/details/gt2gndbijmc.html

{**a, **b}
来源：http://dali.vqdsnc.cn/Article/details/gt2oldakpda.html

[U07] Py：反转字典键值
来源：http://dali.snrcjt.cn/Article/details/gt2yunisnji.html

{v: k for k, v in d.items()}
来源：http://dali.sxryk.cn/Article/details/gt2dfkgpfqa.html

[U08] Py：展平二维列表
来源：http://dali.vqdsnc.cn/Article/details/gt2jswudrkc.html

[y for x in nested for y in x]
来源：http://dali.sysykeji.top/Article/details/gt2pzjhmegp.html

[U09] Py：字典取最大值的键
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mikjmoya.html

max(d, key=d.get)
来源：http://dali.birdmap.top/Article/details/gt2hmjrfmab.html

[U10] Py：按值排序字典
来源：http://dali.guannengcc.top/Article/details/gt2igowzvyo.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinqigufen.top/Article/details/gt2mzjxljti.html

[U11] Py：生成器表达式
来源：http://dali.ybcxt.top/Article/details/gt2gstmvhly.html

(x * 2 for x in arr)
来源：http://dali.guowangkeji.top/Article/details/gt2nzzanlpr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yj20258.top/Article/details/gt2cljmpjtz.html

Counter(arr).most_common(3)
来源：http://dali.chenlongwang.top/Article/details/gt2mtkrgoaz.html

[U13] Py：固定长度队列
来源：http://dali.gzhubu.top/Article/details/gt2zwqminog.html

deque(maxlen=10)
来源：http://dali.guannengcc.top/Article/details/gt2ajuczynh.html

[U14] Py：分组收集到列表
来源：http://dali.nanxinkj.top/Article/details/gt2xjipktom.html

defaultdict(list)
来源：http://dali.yongpay.top/Article/details/gt2hoitieoc.html

[U15] Py：高精度计时
来源：http://dali.hnxiangtu.top/Article/details/gt2xiwedcsn.html

t = time.perf_counter()
来源：http://dali.9152youxi.cn/Article/details/gt2rmbgbojp.html

[U16] Py：命令行参数解析
来源：http://dali.wangdashe.top/Article/details/gt2nyaoyvvh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xziqi.cn/Article/details/gt2xmzhprku.html

[U17] Py：初始化日志
来源：http://dali.hnqzz.top/Article/details/gt2ihogqtxb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.daria6918.cn/Article/details/gt2ftkvegzh.html

[U18] Py：预编译正则
来源：http://dali.haohaochexian.top/Article/details/gt2ajaiscxj.html

pat = re.compile(r"\d+")
来源：http://dali.guowangkeji.top/Article/details/gt2hqfimwxq.html

[U19] Py：正则替换带回调
来源：http://dali.yanxiufei.cn/Article/details/gt2oflgyzxk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.smart0.xyz/Article/details/gt2flipiyin.html

[U20] Py：缓存函数结果
来源：http://dali.ydzc1.top/Article/details/gt2ggcdbpzi.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cheryme.top/Article/details/gt2nzulvnny.html


<!-- 参考信息 -->