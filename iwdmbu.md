代发 wailian999

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj20258.top/Article/details/gtdpylhnxn.html

[R80] 查看脚本执行耗时
来源：http://dali.wangshuangyany.cn/Article/details/gtyugydfcv.html

time ./run.sh
来源：http://dali.zhoulong.xyz/Article/details/gttjkplatj.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gttyndpgkq.html

S. C / C++ 专题
来源：http://dali.iojbl.cn/Article/details/gtkpbqjrfh.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtcnutwupu.html

[S01] C：Hello World
来源：http://dali.mhx1999.top/Article/details/gtccppcmfg.html

#include <stdio.h>
来源：http://dali.sweek.top/Article/details/gtbgosprcb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.snrcjt.cn/Article/details/gtrtbbwsgz.html

[S02] C：变量与格式化输出
来源：http://dali.gaohongyu789.top/Article/details/gtxhbtrqcm.html

int a = 10; printf("%d\n", a);
来源：http://dali.zdqjudy.top/Article/details/gthepmigxg.html

[S03] C：读入整数
来源：http://dali.jlsjyb.cn/Article/details/gtttwydyrj.html

int x; scanf("%d", &x);
来源：http://dali.jinqigufen.top/Article/details/gtjbwkcveo.html

[S04] C：字符串复制
来源：http://dali.sysykeji.top/Article/details/gteuxwwthh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.dashuyun.cn/Article/details/gtknbvygtr.html

[S05] C：字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gtjlxtvxhm.html

strlen(s)
来源：http://dali.0kj1m.cn/Article/details/gtfcordtzc.html

[S06] C：字符串比较
来源：http://dali.ydzc1.top/Article/details/gtdnowieyp.html

strcmp(a, b) == 0
来源：http://dali.yuanzhike.top/Article/details/gtjkcpekuv.html

[S07] C：数组遍历求和
来源：http://dali.tianlin.xyz/Article/details/gtytlifggn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xuanzx.com/Article/details/gtlupdyypn.html

[S08] C：动态内存分配与释放
来源：http://dali.daria6918.cn/Article/details/gtbrobkzhz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aibaodan.cn/Article/details/gtehdlsfkj.html

[S09] C：结构体定义与初始化
来源：http://dali.hnqzz.top/Article/details/gtnpcehdch.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yuanzhike.top/Article/details/gtcwhkfzug.html

[S10] C：指针与解引用
来源：http://dali.gzhubu.top/Article/details/gtpliryiot.html

int *p = &a;  *p = 5;
来源：http://dali.tianlin.xyz/Article/details/gtnoleuvxx.html

[S11] C：逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtrqavpqol.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gogol.net.cn/Article/details/gtonofbire.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zycfv.cn/Article/details/gtfgsaqqxj.html

fclose(f);
来源：http://dali.iojbl.cn/Article/details/gtnwoouthh.html

[S12] C：写文件
来源：http://dali.dashuyun.cn/Article/details/gtgrfwjrkn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangshuangyany.cn/Article/details/gtaqeqhepm.html

[S13] C：宏定义
来源：http://dali.yonumen.top/Article/details/gtrzjplksm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.wangdashe.top/Article/details/gtjbuddyky.html

[S14] C：枚举
来源：http://dali.yangfankeji.com/Article/details/gtcygchyrx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.havefunace.top/Article/details/gtfnqdikwl.html

[S15] C：类型转换
来源：http://dali.gzhubu.top/Article/details/gtzhavmjzf.html

(double) a / b
来源：http://dali.redwolf501.top/Article/details/gtenozrrss.html

[S16] C：位操作置位
来源：http://dali.zdqjudy.top/Article/details/gttyfypmya.html

x |= (1 << 3);
来源：http://dali.hysaishi.cn/Article/details/gtnfvtwxcd.html

[S17] C：安全拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gtsyyvllxs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtooiksmhs.html

[S18] C：命令行参数
来源：http://dali.gaohongyu789.top/Article/details/gtvqnzyvmm.html

int main(int argc, char **argv)
来源：http://dali.chenlongwang.top/Article/details/gtibwdrnff.html

[S19] C：快速排序
来源：http://dali.xziqi.cn/Article/details/gtzbuecdjg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gtwkhuxtyp.html

[S20] C：二分查找
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyutiibbd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhixingplan.top/Article/details/gtrxninejr.html

[S21] C：字符类别判断
来源：http://dali.c1oappe.top/Article/details/gtczjwpcdh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.vqdsnc.cn/Article/details/gtvifvkzib.html

[S22] C：字符串转数字
来源：http://dali.316326.xyz/Article/details/gtmkmzyvgd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.wangshuangyany.cn/Article/details/gtmlubgqmy.html

[S23] C：随机数
来源：http://dali.xuanzx.com/Article/details/gtuonetmky.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.0kj1m.cn/Article/details/gtknnpcncx.html

[S24] C：获取本地时间
来源：http://dali.chenzaomai.com/Article/details/gtxrxzpmgm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.kuanghao11.cn/Article/details/gtunacnzkl.html

[S25] C：内存拷贝
来源：http://dali.gzhubu.top/Article/details/gteiyttxql.html

memcpy(dst, src, n);
来源：http://dali.9152youxi.cn/Article/details/gtlpklsggl.html

[S26] C：内存清零
来源：http://dali.yvedp.cn/Article/details/gtepkfdbqx.html

memset(a, 0, sizeof a);
来源：http://dali.yueranfly.top/Article/details/gtdyyqzayc.html

[S27] C：定义常量
来源：http://dali.vqdsnc.cn/Article/details/gtjszmlhfu.html

const double PI = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gtqcumrgaa.html

[S28] C：静态变量
来源：http://dali.guannengcc.top/Article/details/gtkcvjpehl.html

static int counter = 0;
来源：http://dali.yj202588.top/Article/details/gtrcsrbqls.html

[S29] C：变参函数
来源：http://dali.smart0.xyz/Article/details/gtfpdwmptd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shangyingyoupin.top/Article/details/gtopaiigwn.html

[S30] C：头文件保护
来源：http://dali.jlsjyb.cn/Article/details/gtlfbhvtxz.html

#ifndef X_H
来源：http://dali.gotoacloud.top/Article/details/gtfpcoftkc.html

#define X_H
来源：http://dali.hywenlv.cn/Article/details/gtlgifdzjm.html

#endif
来源：http://dali.haohaochexian.top/Article/details/gtbemnloix.html

[S31] C++：Hello World
来源：http://dali.ydzc1.top/Article/details/gtqszbuhjl.html

#include <iostream>
来源：http://dali.shuidangran.top/Article/details/gtqqodrxex.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ivvv.top/Article/details/gtagxvtwct.html

[S32] C++：字符串
来源：http://dali.ivvv.top/Article/details/gtadydtwnz.html

std::string s = "hi";  s += "!";
来源：http://dali.daxiang520.top/Article/details/gtmyabtocj.html

[S33] C++：vector 增删
来源：http://dali.xylfe.cn/Article/details/gtzzicuqpg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xylfe.cn/Article/details/gtonicgeis.html

[S34] C++：遍历 vector
来源：http://dali.fzhhl.top/Article/details/gtfbxujufe.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.wangdashe.top/Article/details/gtyoaykibz.html

[S35] C++：map
来源：http://dali.ydzc1.top/Article/details/gtpxkmrwjy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.iojbl.cn/Article/details/gtktyzwgiq.html

[S36] C++：unordered_map
来源：http://dali.snrcjt.cn/Article/details/gtxnudmdze.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guannengcc.top/Article/details/gtrqngqwub.html

[S37] C++：set
来源：http://dali.wangdashe.top/Article/details/gtrftlxgmd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtriinldmk.html

[S38] C++：排序
来源：http://dali.sufxvd.cn/Article/details/gtwtuanigy.html

std::sort(v.begin(), v.end());
来源：http://dali.cucudq.cn/Article/details/gtzxrncfoy.html

[S39] C++：自定义比较器排序
来源：http://dali.chenjidiqi.icu/Article/details/gtznvtlhgd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.kuanghao11.cn/Article/details/gtjfykuggy.html

[S40] C++：查找元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzftcffcn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.daxiang520.top/Article/details/gtodgunvra.html

[S41] C++：类与构造函数
来源：http://dali.gzhubu.top/Article/details/gtqzhfcfsw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shangyingyoupin.top/Article/details/gtehzfbhqe.html

[S42] C++：继承与虚函数
来源：http://dali.yuxming.cn/Article/details/gtdiwggmof.html

class B : public Base { public: void f() override {} };
来源：http://dali.gaohongyu789.top/Article/details/gtvscmnszz.html

[S43] C++：智能指针
来源：http://dali.aizwys.cn/Article/details/gtgqtlheea.html

auto p = std::make_unique<int>(5);
来源：http://dali.meibo888.top/Article/details/gtudazvqxg.html

[S44] C++：引用传参
来源：http://dali.chenlongwang.top/Article/details/gthnreibgo.html

void inc(int &x) { ++x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfeqsigrx.html

[S45] C++：lambda
来源：http://dali.yangfankeji.com/Article/details/gtyosfiskm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ppjwa.cn/Article/details/gtyubtregz.html

[S46] C++：函数模板
来源：http://dali.fengsongda.top/Article/details/gtkcyeutgs.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.dashuyun.cn/Article/details/gtgdavtyjm.html

[S47] C++：结构化绑定遍历
来源：http://dali.xinyue.icu/Article/details/gtusxxxfwy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gaohongyu789.top/Article/details/gtqrwbxtnk.html

[S48] C++：逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gtewjdbwbb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shuidangran.top/Article/details/gtssmcidrc.html

while (std::getline(in, line)) { }
来源：http://dali.quarkkingdee.top/Article/details/gtcxtlteug.html

[S49] C++：写文件
来源：http://dali.yanxiufei.cn/Article/details/gtbonxlxhl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xziqi.cn/Article/details/gtkynblkpj.html

[S50] C++：格式化数字
来源：http://dali.gotoacloud.top/Article/details/gtrqzoluna.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtfvibhail.html

[S51] C++：显式类型转换
来源：http://dali.smart0.xyz/Article/details/gtzgkfpitr.html

static_cast<double>(a) / b
来源：http://dali.jinghuilouyu.cn/Article/details/gtxdcmabwo.html

[S52] C++：const 与 noexcept
来源：http://dali.jinqigufen.top/Article/details/gtnawbzqpe.html

int size() const noexcept { return n_; }
来源：http://dali.cheryme.top/Article/details/gtadfdhgrc.html

[S53] C++：移动语义
来源：http://dali.chenzaomai.com/Article/details/gtxsznomqg.html

std::vector<int> w = std::move(v);
来源：http://dali.gaohongyu789.top/Article/details/gtmfmjuflx.html

[S54] C++：异常处理
来源：http://dali.haohaochexian.top/Article/details/gtoudfquou.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jianghu66.top/Article/details/gtojmknwvj.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gtyjolebxz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinqigufen.top/Article/details/gtgdsojzbj.html

[S56] C++：optional
来源：http://dali.316326.xyz/Article/details/gtxphvvijh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tian-w.cn/Article/details/gtvpywmkfv.html

[S57] C++：编译期常量
来源：http://dali.sufxvd.cn/Article/details/gtwagkingj.html

constexpr int N = 10;
来源：http://dali.zhengqikj.top/Article/details/gtnrgrwbtn.html

[S58] C++：命名空间
来源：http://dali.daria6918.cn/Article/details/gtxbdbqtvg.html

namespace ns { int f() { return 1; } }
来源：http://dali.yvedp.cn/Article/details/gtxmfyydtw.html

[S59] C++：静态断言
来源：http://dali.fzhhl.top/Article/details/gtihhuxrxw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zdqjudy.top/Article/details/gtxrmdybch.html

[S60] C++：遍历并删除元素
来源：http://dali.quarkkingdee.top/Article/details/gtgyijsaxl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cashguo.top/Article/details/gtxpjfbmlh.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtsiqnpjdr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hywenlv.cn/Article/details/gtwfkdwqwu.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtkagqzgdx.html

[T01] Kotlin：Hello World
来源：http://dali.zycfv.cn/Article/details/gtzugwwzef.html

println("Hello")
来源：http://dali.ehwqpu.com/Article/details/gtivquaeny.html

[T02] Kotlin：变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjqhixtr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.pengpengdd.cyou/Article/details/gtkjvizqbm.html

[T03] Kotlin：字符串模板
来源：http://dali.haohaochexian.top/Article/details/gtiwuehbci.html

"值: $b"
来源：http://dali.guannengcc.top/Article/details/gtwfsafpit.html

[T04] Kotlin：空安全
来源：http://dali.sufxvd.cn/Article/details/gtncecnawk.html

val n: String? = null;  n?.length
来源：http://dali.yonumen.top/Article/details/gthpxijklm.html

[T05] Kotlin：when 表达式
来源：http://dali.ppjwa.cn/Article/details/gtubvfajqr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.vqdsnc.cn/Article/details/gtemfowpcd.html

[T06] Kotlin：集合映射
来源：http://dali.fzhhl.top/Article/details/gtrpgkptkf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.andypj.xyz/Article/details/gtgnnaywfr.html

[T07] Kotlin：集合过滤
来源：http://dali.cheryme.top/Article/details/gtncffqdpq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinqigfzy.top/Article/details/gtwvxdrlfo.html

[T08] Kotlin：数据类
来源：http://dali.hfpthk.cn/Article/details/gtvjwyphzz.html

data class User(val name: String, val age: Int)
来源：http://dali.yj202588.top/Article/details/gtrkwxvwux.html

[T09] Kotlin：扩展函数
来源：http://dali.snrcjt.cn/Article/details/gtvvtktfjo.html

fun String.exclaim() = this + "!"
来源：http://dali.yvedp.cn/Article/details/gtamhmnbzt.html

[T10] Kotlin：默认参数
来源：http://dali.meibo888.top/Article/details/gtohigrohy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hywenlv.cn/Article/details/gtlkxixign.html

[T11] Kotlin：协程
来源：http://dali.fengsongda.top/Article/details/gtwgnrtghc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.fengsongda.top/Article/details/gttexbkuuz.html

[T12] Kotlin：解构声明
来源：http://dali.xinyue.icu/Article/details/gttlwdqyaf.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhixingplan.top/Article/details/gtelvopkod.html

[T13] Kotlin：只读 Map
来源：http://dali.quarkkingdee.top/Article/details/gtrevpzusb.html

val m = mapOf("a" to 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtwjzpgpzj.html

[T14] Kotlin：循环
来源：http://dali.jqgufenzy.top/Article/details/gtnxbnsmtn.html

for (i in 1..10) println(i)
来源：http://dali.bjfxy.top/Article/details/gtbmcmnppp.html

[T15] Kotlin：接口
来源：http://dali.yvedp.cn/Article/details/gtdbazkyqp.html

interface Shape { fun area(): Double }
来源：http://dali.gaohongyu789.top/Article/details/gtolgikgxa.html

[T16] Swift：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtftzotzxb.html

print("Hello")
来源：http://dali.xuanzx.com/Article/details/gtdxbqhwno.html

[T17] Swift：变量与常量
来源：http://dali.xylfe.cn/Article/details/gttqjlzayn.html

var a = 1;  let b = 2
来源：http://dali.ydzc1.top/Article/details/gtqqmbjieg.html

[T18] Swift：字符串插值
来源：http://dali.sysykeji.top/Article/details/gtgpdrruho.html

"值: \(b)"
来源：http://dali.hfpthk.cn/Article/details/gtnceloiog.html

[T19] Swift：可选绑定
来源：http://dali.tianlin.xyz/Article/details/gtbezuzrgx.html

if let n = opt { print(n) }
来源：http://dali.cucudq.cn/Article/details/gtklqinawh.html

[T20] Swift：数组操作
来源：http://dali.kuanghao11.cn/Article/details/gtchofgfab.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xylfe.cn/Article/details/gtwvbxryba.html

[T21] Swift：遍历
来源：http://dali.jyoumei.cn/Article/details/gtuumfkuub.html

for x in a { print(x) }
来源：http://dali.316326.xyz/Article/details/gttolabggh.html

[T22] Swift：字典
来源：http://dali.redwolf501.top/Article/details/gtvxwooebe.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shzxlz.cn/Article/details/gturkeuffu.html

[T23] Swift：函数
来源：http://dali.yonumen.top/Article/details/gtayfndnon.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.daria6918.cn/Article/details/gtqmntkqhq.html

[T24] Swift：闭包
来源：http://dali.jqgfzy.top/Article/details/gthnlqdary.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxyftijxq.html

[T25] Swift：结构体
来源：http://dali.sweek.top/Article/details/gtqkzpkkdl.html

struct P { var x: Int }
来源：http://dali.yuanzhike.top/Article/details/gtqviqpzwd.html

[T26] Swift：类与重写
来源：http://dali.yj20258888.top/Article/details/gtfpnkyaev.html

class A: Base { override func f() {} }
来源：http://dali.hnqzz.top/Article/details/gtrqiabqwj.html

[T27] Swift：错误处理
来源：http://dali.tian-w.cn/Article/details/gtyjrzruie.html

do { try f() } catch { print(error) }
来源：http://dali.yanxiufei.cn/Article/details/gtsvtnufte.html

[T28] Swift：枚举
来源：http://dali.nanxuanxn.top/Article/details/gtpczakblb.html

enum Color { case red, green }
来源：http://dali.yanxiufei.cn/Article/details/gtcwbdqcbd.html

[T29] Swift：guard 提前返回
来源：http://dali.guannengcc.top/Article/details/gtsjhrnbtv.html

guard let x = opt else { return }
来源：http://dali.xziqi.cn/Article/details/gtwzisdfsf.html

[T30] Swift：协议
来源：http://dali.c1oappe.top/Article/details/gtqmkpehai.html

protocol Shape { func area() -> Double }
来源：http://dali.xinyue.icu/Article/details/gttbjuokiu.html

[T31] Lua：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtrbtossop.html

print("Hello")
来源：http://dali.jyoumei.cn/Article/details/gtmjfwporq.html

[T32] Lua：局部变量
来源：http://dali.ivvv.top/Article/details/gtrachresp.html

local a = 1
来源：http://dali.zdqjudy.top/Article/details/gtgkibpzpb.html

[T33] Lua：表（数组）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtruguuvqk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hysaishi.cn/Article/details/gtkmpbavsj.html

[T34] Lua：遍历表
来源：http://dali.vqdsnc.cn/Article/details/gtwahovrke.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.tanke756.top/Article/details/gtpzxxbdpu.html

[T35] Lua：字典表
来源：http://dali.9152youxi.cn/Article/details/gtmnlyqvdz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhixingplan.top/Article/details/gtdeqqdpnl.html

[T36] Lua：函数
来源：http://dali.smart0.xyz/Article/details/gtjesnakkm.html

function add(a, b) return a + b end
来源：http://dali.haohaochexian.top/Article/details/gtjawrtdjt.html

[T37] Lua：字符串拼接
来源：http://dali.cheryme.top/Article/details/gtzxugyizl.html

"a" .. "b"
来源：http://dali.jiagoushi.top/Article/details/gtcxiuamuj.html

[T38] Lua：条件
来源：http://dali.zhiwuduotai.top/Article/details/gtlgdbelyx.html

if x > 0 then print("正") end
来源：http://dali.snrcjt.cn/Article/details/gttrfzfgmp.html

[T39] Lua：模式匹配
来源：http://dali.nwbrower.top/Article/details/gtmmayoqkb.html

string.find(s, "%d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxnbadhdm.html

[T40] Lua：元表
来源：http://dali.316326.xyz/Article/details/gtgzxopvur.html

setmetatable({}, { __index = base })
来源：http://dali.ehwqpu.com/Article/details/gtjxpjvsdw.html

[T41] Perl：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtedaqzxvw.html

print "Hello\n";
来源：http://dali.shzxlz.cn/Article/details/gtfuizcbpl.html

[T42] Perl：变量类型
来源：http://dali.pengpengdd.cyou/Article/details/gtkehxfdcv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.wangdashe.top/Article/details/gtqrpfinwk.html

[T43] Perl：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gtmayamgsc.html

"值: $a"
来源：http://dali.quarkkingdee.top/Article/details/gtpwxdvgsa.html

[T44] Perl：条件
来源：http://dali.shangyingyoupin.top/Article/details/gtzatkdrbv.html

if ($a > 0) { print "正"; }
来源：http://dali.jyoumei.cn/Article/details/gtjfsgdfdp.html

[T45] Perl：数组遍历
来源：http://dali.sxryk.cn/Article/details/gtcdomycit.html

for my $x (@arr) { print $x; }
来源：http://dali.ehwqpu.com/Article/details/gtufrltwlj.html

[T46] Perl：哈希操作
来源：http://dali.nanxuanxn.top/Article/details/gtswhjmkqz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.fzhhl.top/Article/details/gtekmiebti.html

[T47] Perl：正则捕获
来源：http://dali.tanke756.top/Article/details/gtfjpqqsbk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yangfankeji.com/Article/details/gtqvcrmpsh.html

[T48] Perl：正则替换
来源：http://dali.iojbl.cn/Article/details/gthmujckkk.html

$s =~ s/old/new/g;
来源：http://dali.tian-w.cn/Article/details/gtlsguezjt.html

[T49] Perl：函数
来源：http://dali.xziqi.cn/Article/details/gtftmulawz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cqqwz.cn/Article/details/gttefbpnwn.html

[T50] Perl：逐行读文件
来源：http://dali.tian-w.cn/Article/details/gtslsvsfwt.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.dianchejie.cn/Article/details/gtepmsqioh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gotoacloud.top/Article/details/gtshhahzsa.html

[T51] Scala：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzudwgcch.html

println("Hello")
来源：http://dali.gzhubu.top/Article/details/gtvuvhiogs.html

[T52] Scala：变量
来源：http://dali.0kj1m.cn/Article/details/gtiszagnln.html

val a = 1;  var b = 2
来源：http://dali.quarkkingdee.top/Article/details/gthqcqfjtv.html

[T53] Scala：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspgmfrch.html

s"值: $b"
来源：http://dali.chenjidiqi.icu/Article/details/gtuvlhglnx.html

[T54] Scala：集合映射
来源：http://dali.wangdashe.top/Article/details/gtklhslucj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hysaishi.cn/Article/details/gtderyqtlb.html

[T55] Scala：集合过滤
来源：http://dali.gaohongyu789.top/Article/details/gtqfqtncsx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hfpthk.cn/Article/details/gtyudkqpfu.html

[T56] Scala：样例类
来源：http://dali.chenjidiqi.icu/Article/details/gtyaimgowq.html

case class User(name: String, age: Int)
来源：http://dali.c1oappe.top/Article/details/gtnuhihuwp.html

[T57] Scala：模式匹配
来源：http://dali.xinyue.icu/Article/details/gthlutlimt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cdnleiting.top/Article/details/gtuekrkdki.html

[T58] Scala：函数定义
来源：http://dali.cucudq.cn/Article/details/gtuyfnceic.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.dashuyun.cn/Article/details/gtqeqmvbak.html

[T59] Scala：循环
来源：http://dali.jinqigfzy.top/Article/details/gtveruogmd.html

for (i <- 1 to 10) println(i)
来源：http://dali.kuanghao11.cn/Article/details/gtqbokfsku.html

[T60] Scala：折叠
来源：http://dali.fengsongda.top/Article/details/gtijifarua.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.9152youxi.cn/Article/details/gtjppvbpuc.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtufzydkas.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.redwolf501.top/Article/details/gtrlwkshym.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtwxmholwf.html

[U01] Py：创建虚拟环境
来源：http://dali.0kj1m.cn/Article/details/gtepqnxnah.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.aibaodan.cn/Article/details/gtgozhpyiv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xuanzx.com/Article/details/gtzlbnqxaz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ehwqpu.com/Article/details/gtiioigqgs.html

[U03] Py：加载 .env 配置
来源：http://dali.zhoulong.xyz/Article/details/gtdfuxadzy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hammf.cn/Article/details/gtavijlrzq.html

[U04] Py：变量调试打印
来源：http://dali.yj202588.top/Article/details/gtkljosaca.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhoulong.xyz/Article/details/gtaihtaiyp.html

[U05] Py：列表去重且保序
来源：http://dali.yongpay.top/Article/details/gtknrlkkeu.html

list(dict.fromkeys(arr))
来源：http://dali.chenlongwang.top/Article/details/gtgircodcz.html

[U06] Py：合并两个字典
来源：http://dali.fengsongda.top/Article/details/gtckssjopf.html

{**a, **b}
来源：http://dali.kuanghao11.cn/Article/details/gtsoeynzpq.html

[U07] Py：反转字典键值
来源：http://dali.c1oappe.top/Article/details/gtwwergtij.html

{v: k for k, v in d.items()}
来源：http://dali.hysaishi.cn/Article/details/gtpjrroido.html

[U08] Py：展平二维列表
来源：http://dali.cucudq.cn/Article/details/gtmxivbykv.html

[y for x in nested for y in x]
来源：http://dali.yanxiufei.cn/Article/details/gtghauwvhy.html

[U09] Py：字典取最大值的键
来源：http://dali.zhixingplan.top/Article/details/gtmrwcmrsa.html

max(d, key=d.get)
来源：http://dali.jinqigfzy.top/Article/details/gtrptuwhsr.html

[U10] Py：按值排序字典
来源：http://dali.ybcxt.top/Article/details/gtsugfefgw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.redwolf501.top/Article/details/gtasqvofrf.html

[U11] Py：生成器表达式
来源：http://dali.aizwys.cn/Article/details/gtwgrvlncq.html

(x * 2 for x in arr)
来源：http://dali.xylfe.cn/Article/details/gtmouuvete.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.aizwys.cn/Article/details/gthcakhjcd.html

Counter(arr).most_common(3)
来源：http://dali.zhongyouzk.top/Article/details/gtbakrgxfv.html

[U13] Py：固定长度队列
来源：http://dali.pycfn.com/Article/details/gtvkpwpozn.html

deque(maxlen=10)
来源：http://dali.sufxvd.cn/Article/details/gtxameesbi.html

[U14] Py：分组收集到列表
来源：http://dali.sxryk.cn/Article/details/gtccfatqgf.html

defaultdict(list)
来源：http://dali.0kj1m.cn/Article/details/gtzdpnstsj.html

[U15] Py：高精度计时
来源：http://dali.shzxlz.cn/Article/details/gtxbgheesk.html

t = time.perf_counter()
来源：http://dali.jyoumei.cn/Article/details/gtwzyazafa.html

[U16] Py：命令行参数解析
来源：http://dali.cdnleiting.top/Article/details/gtjalcubug.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.fzhhl.top/Article/details/gtxvtqrbuf.html

[U17] Py：初始化日志
来源：http://dali.gaohongyu789.top/Article/details/gtgtqojzvt.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jinqigufen.top/Article/details/gtyzajejaf.html

[U18] Py：预编译正则
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzpvcjogj.html

pat = re.compile(r"\d+")
来源：http://dali.hywenlv.cn/Article/details/gtnuucqbjo.html

[U19] Py：正则替换带回调
来源：http://dali.havefunace.top/Article/details/gtckgrlkjd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.fzhhl.top/Article/details/gtpnaisgdk.html

[U20] Py：缓存函数结果
来源：http://dali.yanxiufei.cn/Article/details/gtksmqbfcp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ehwqpu.com/Article/details/gtedowljjq.html


<!-- 参考信息 -->