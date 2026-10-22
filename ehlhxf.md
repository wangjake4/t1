代发 wailian999

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.0kj1m.cn/Article/details/gt2onnwjuyi.html

[R80] 查看脚本执行耗时
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bpvoojwc.html

time ./run.sh
来源：http://dali.zhiwuduotai.top/Article/details/gt2yynvannq.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2syspleff.html

S. C / C++ 专题
来源：http://dali.tian-w.cn/Article/details/gt2etzptdtp.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2vpcjopim.html

[S01] C：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gt2aftiwrwd.html

#include <stdio.h>
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qqkhwwcc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yuanzhike.top/Article/details/gt2ohvalxau.html

[S02] C：变量与格式化输出
来源：http://dali.sysykeji.top/Article/details/gt2lnlojmnd.html

int a = 10; printf("%d\n", a);
来源：http://dali.9152youxi.cn/Article/details/gt2tihiidqm.html

[S03] C：读入整数
来源：http://dali.daria6918.cn/Article/details/gt2hjyrkjxs.html

int x; scanf("%d", &x);
来源：http://dali.kuanghao11.cn/Article/details/gt2kgmouvrq.html

[S04] C：字符串复制
来源：http://dali.meibo888.top/Article/details/gt2akqweigr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cujpnmzj.html

[S05] C：字符串长度
来源：http://dali.xinyue.icu/Article/details/gt2djuajoim.html

strlen(s)
来源：http://dali.jyoumei.cn/Article/details/gt2hngdqwja.html

[S06] C：字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gt2myhocjyl.html

strcmp(a, b) == 0
来源：http://dali.9152youxi.cn/Article/details/gt2pbuvolxn.html

[S07] C：数组遍历求和
来源：http://dali.hfpthk.cn/Article/details/gt2ptdnfiba.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.daria6918.cn/Article/details/gt2baphtcbt.html

[S08] C：动态内存分配与释放
来源：http://dali.gzhubu.top/Article/details/gt2kwfkwxmv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aibaodan.cn/Article/details/gt2axquibxf.html

[S09] C：结构体定义与初始化
来源：http://dali.hongshengwenyu.top/Article/details/gt2ighipdmo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.smart0.xyz/Article/details/gt2eitbniki.html

[S10] C：指针与解引用
来源：http://dali.ppjwa.cn/Article/details/gt2vynujgsm.html

int *p = &a;  *p = 5;
来源：http://dali.yonumen.top/Article/details/gt2ppcyfudk.html

[S11] C：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gt2yspnynkx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cdnleiting.top/Article/details/gt2wraftkna.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhengqikj.top/Article/details/gt2ufrfjqqi.html

fclose(f);
来源：http://dali.pengpengdd.cyou/Article/details/gt2kxocqnnr.html

[S12] C：写文件
来源：http://dali.jyoumei.cn/Article/details/gt2iyqksoie.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yueranfly.top/Article/details/gt2dzpibeqk.html

[S13] C：宏定义
来源：http://dali.cqqwz.cn/Article/details/gt2stpdipbh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jqgufenzy.top/Article/details/gt2srgjmelj.html

[S14] C：枚举
来源：http://dali.yj202588.top/Article/details/gt2sthdamlo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hywenlv.cn/Article/details/gt2vdnygneh.html

[S15] C：类型转换
来源：http://dali.gotoacloud.top/Article/details/gt2ebelwzrf.html

(double) a / b
来源：http://dali.yuanzhike.top/Article/details/gt2nqcsxsnb.html

[S16] C：位操作置位
来源：http://dali.snrcjt.cn/Article/details/gt2ltqrqpyk.html

x |= (1 << 3);
来源：http://dali.jiagoushi.top/Article/details/gt2zrlzygkl.html

[S17] C：安全拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gt2qthwbthy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zmpuqpet.html

[S18] C：命令行参数
来源：http://dali.svipenyu.cn/Article/details/gt2nkttrumg.html

int main(int argc, char **argv)
来源：http://dali.yonumen.top/Article/details/gt2jflbeajf.html

[S19] C：快速排序
来源：http://dali.svipenyu.cn/Article/details/gt2oovuyjzi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hnqzz.top/Article/details/gt2osmyxbmw.html

[S20] C：二分查找
来源：http://dali.zdqjudy.top/Article/details/gt2cyrbqdgs.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nwbrower.top/Article/details/gt2wyhreiaj.html

[S21] C：字符类别判断
来源：http://dali.sweek.top/Article/details/gt2xqwoppdu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ppjwa.cn/Article/details/gt2lxhqcqmr.html

[S22] C：字符串转数字
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gtrgpiqz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yueranfly.top/Article/details/gt2falgsfwu.html

[S23] C：随机数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2otbhbthq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xuanzx.com/Article/details/gt2wrgtafqx.html

[S24] C：获取本地时间
来源：http://dali.xziqi.cn/Article/details/gt2ruhodleo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cashguo.top/Article/details/gt2zdncyvsf.html

[S25] C：内存拷贝
来源：http://dali.sxryk.cn/Article/details/gt2tkvpxomm.html

memcpy(dst, src, n);
来源：http://dali.chenlongwang.top/Article/details/gt2yisrqtqv.html

[S26] C：内存清零
来源：http://dali.ivvv.top/Article/details/gt2wgpibhtq.html

memset(a, 0, sizeof a);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cqnmvckk.html

[S27] C：定义常量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oqsfctbb.html

const double PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gt2nennrvdi.html

[S28] C：静态变量
来源：http://dali.yongpay.top/Article/details/gt2hufhwzru.html

static int counter = 0;
来源：http://dali.jinqigfzy.top/Article/details/gt2ykgqtkvt.html

[S29] C：变参函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2bhyhxtls.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hysaishi.cn/Article/details/gt2hdelhwic.html

[S30] C：头文件保护
来源：http://dali.dianchejie.cn/Article/details/gt2kcwkntll.html

#ifndef X_H
来源：http://dali.fengsongda.top/Article/details/gt2mxnkrihu.html

#define X_H
来源：http://dali.xuanzx.com/Article/details/gt2inbfyvta.html

#endif
来源：http://dali.cdnleiting.top/Article/details/gt2berrrtmq.html

[S31] C++：Hello World
来源：http://dali.yuxming.cn/Article/details/gt2iecjmebf.html

#include <iostream>
来源：http://dali.jyoumei.cn/Article/details/gt2pvwcusry.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yangfankeji.com/Article/details/gt2xubenvdk.html

[S32] C++：字符串
来源：http://dali.zycfv.cn/Article/details/gt2egudajyz.html

std::string s = "hi";  s += "!";
来源：http://dali.sysykeji.top/Article/details/gt2wtnvjnot.html

[S33] C++：vector 增删
来源：http://dali.xuanzx.com/Article/details/gt2tfppikkd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.havefunace.top/Article/details/gt2uwdcbxfe.html

[S34] C++：遍历 vector
来源：http://dali.ydzc1.top/Article/details/gt2cbssyppx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.daxiang520.top/Article/details/gt2gdqralad.html

[S35] C++：map
来源：http://dali.nanxuanxn.top/Article/details/gt2yfdsmtlw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnqzz.top/Article/details/gt2cvoowhev.html

[S36] C++：unordered_map
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2autlacoo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gt2eslmxszz.html

[S37] C++：set
来源：http://dali.c1oappe.top/Article/details/gt2wyaeyags.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nanxuanxn.top/Article/details/gt2iqympied.html

[S38] C++：排序
来源：http://dali.cheryme.top/Article/details/gt2bvhrqgko.html

std::sort(v.begin(), v.end());
来源：http://dali.zhoulong.xyz/Article/details/gt2wknpther.html

[S39] C++：自定义比较器排序
来源：http://dali.yvedp.cn/Article/details/gt2trgnypkw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cdnleiting.top/Article/details/gt2reienuvo.html

[S40] C++：查找元素
来源：http://dali.ppjwa.cn/Article/details/gt2stzipxrj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ybcxt.top/Article/details/gt2uwywrlav.html

[S41] C++：类与构造函数
来源：http://dali.xuanzx.com/Article/details/gt2grtmeiip.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sweek.top/Article/details/gt2tcomvjxt.html

[S42] C++：继承与虚函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2szjfrtlf.html

class B : public Base { public: void f() override {} };
来源：http://dali.shangyingyoupin.top/Article/details/gt2msjzqgsi.html

[S43] C++：智能指针
来源：http://dali.tian-w.cn/Article/details/gt2uzeduvsv.html

auto p = std::make_unique<int>(5);
来源：http://dali.guowangkeji.top/Article/details/gt2kgssubua.html

[S44] C++：引用传参
来源：http://dali.hysaishi.cn/Article/details/gt2hdtlkqae.html

void inc(int &x) { ++x; }
来源：http://dali.pycfn.com/Article/details/gt2nqohrbhs.html

[S45] C++：lambda
来源：http://dali.xziqi.cn/Article/details/gt2eefdxcxq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eydhzsdl.html

[S46] C++：函数模板
来源：http://dali.shanyushiyangtech.top/Article/details/gt2namesnrc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2emgpbncr.html

[S47] C++：结构化绑定遍历
来源：http://dali.jqgfzy.top/Article/details/gt2ghwekxfw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hnqzz.top/Article/details/gt2mnycxket.html

[S48] C++：逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gt2ezsnkctc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.iojbl.cn/Article/details/gt2gsfrxnwd.html

while (std::getline(in, line)) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vfaazhkb.html

[S49] C++：写文件
来源：http://dali.zhongyouzk.top/Article/details/gt2zgejkufd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.birdmap.top/Article/details/gt2ysuiuwro.html

[S50] C++：格式化数字
来源：http://dali.fzhhl.top/Article/details/gt2nfgawsvn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gt2cdppwmqo.html

[S51] C++：显式类型转换
来源：http://dali.smart0.xyz/Article/details/gt2ydpnsqcq.html

static_cast<double>(a) / b
来源：http://dali.zhoulong.xyz/Article/details/gt2xwtmzfuy.html

[S52] C++：const 与 noexcept
来源：http://dali.guowangkeji.top/Article/details/gt2mlbqgjgl.html

int size() const noexcept { return n_; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2gdcyipzi.html

[S53] C++：移动语义
来源：http://dali.yanxiufei.cn/Article/details/gt2fcknubcb.html

std::vector<int> w = std::move(v);
来源：http://dali.ehwqpu.com/Article/details/gt2xqhkbdvz.html

[S54] C++：异常处理
来源：http://dali.jinqigfzy.top/Article/details/gt2qemjqsgm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shangyingyoupin.top/Article/details/gt2rtxmqozr.html

[S55] C++：结构化绑定
来源：http://dali.hammf.cn/Article/details/gt2jglkvrhu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj20258.top/Article/details/gt2gpoclbag.html

[S56] C++：optional
来源：http://dali.shangyingyoupin.top/Article/details/gt2acwfkyfw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tianlin.xyz/Article/details/gt2lqdlaxaf.html

[S57] C++：编译期常量
来源：http://dali.nwbrower.top/Article/details/gt2xocdhyoo.html

constexpr int N = 10;
来源：http://dali.yonumen.top/Article/details/gt2rjxvmptn.html

[S58] C++：命名空间
来源：http://dali.gotoacloud.top/Article/details/gt2udmocbmq.html

namespace ns { int f() { return 1; } }
来源：http://dali.nanxuanxn.top/Article/details/gt2cupribmy.html

[S59] C++：静态断言
来源：http://dali.ydzc1.top/Article/details/gt2ggiznsec.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yvedp.cn/Article/details/gt2sbamlbvh.html

[S60] C++：遍历并删除元素
来源：http://dali.tianlin.xyz/Article/details/gt2ryfmmpmx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hywenlv.cn/Article/details/gt2ebwllxde.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2ypqheyjk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.iojbl.cn/Article/details/gt2ugqrmtac.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2zammqbvl.html

[T01] Kotlin：Hello World
来源：http://dali.ivvv.top/Article/details/gt2ffgdvjjt.html

println("Hello")
来源：http://dali.yj202588.top/Article/details/gt2peslceja.html

[T02] Kotlin：变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2vewwodhn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhoulong.xyz/Article/details/gt2ealqpshh.html

[T03] Kotlin：字符串模板
来源：http://dali.cashguo.top/Article/details/gt2mqgdvipg.html

"值: $b"
来源：http://dali.havefunace.top/Article/details/gt2agyowzzx.html

[T04] Kotlin：空安全
来源：http://dali.c1oappe.top/Article/details/gt2jxvgtcpm.html

val n: String? = null;  n?.length
来源：http://dali.zhiwuduotai.top/Article/details/gt2heqbczbe.html

[T05] Kotlin：when 表达式
来源：http://dali.chenzaomai.com/Article/details/gt2kowyivap.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.feifeiyinyue.top/Article/details/gt2geckuduw.html

[T06] Kotlin：集合映射
来源：http://dali.yongpay.top/Article/details/gt2ztogredq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gt2rlasfdfu.html

[T07] Kotlin：集合过滤
来源：http://dali.316326.xyz/Article/details/gt2zrxjodnl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gaohongyu789.top/Article/details/gt2lpcmyfch.html

[T08] Kotlin：数据类
来源：http://dali.fzhhl.top/Article/details/gt2gkmvnktb.html

data class User(val name: String, val age: Int)
来源：http://dali.gogol.net.cn/Article/details/gt2hmgzzccu.html

[T09] Kotlin：扩展函数
来源：http://dali.ehwqpu.com/Article/details/gt2anyocjsg.html

fun String.exclaim() = this + "!"
来源：http://dali.yongpay.top/Article/details/gt2uxqdrssh.html

[T10] Kotlin：默认参数
来源：http://dali.xinyue.icu/Article/details/gt2jspidwcm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hammf.cn/Article/details/gt2pnohjgih.html

[T11] Kotlin：协程
来源：http://dali.ivvv.top/Article/details/gt2grywocmy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.svipenyu.cn/Article/details/gt2lievemes.html

[T12] Kotlin：解构声明
来源：http://dali.tian-w.cn/Article/details/gt2vrkyxrug.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gt2epbbwqzt.html

[T13] Kotlin：只读 Map
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wptpulpy.html

val m = mapOf("a" to 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ynksojow.html

[T14] Kotlin：循环
来源：http://dali.shzxlz.cn/Article/details/gt2masnsxzz.html

for (i in 1..10) println(i)
来源：http://dali.yonumen.top/Article/details/gt2hcunogxc.html

[T15] Kotlin：接口
来源：http://dali.yongpay.top/Article/details/gt2clyafksv.html

interface Shape { fun area(): Double }
来源：http://dali.cucudq.cn/Article/details/gt2fjgutjog.html

[T16] Swift：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gt2bqbgtbba.html

print("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gt2pnskpggf.html

[T17] Swift：变量与常量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cbsxpnxf.html

var a = 1;  let b = 2
来源：http://dali.yvedp.cn/Article/details/gt2kfotasjz.html

[T18] Swift：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2trvdhjef.html

"值: \(b)"
来源：http://dali.nanxinkj.top/Article/details/gt2bthnynlt.html

[T19] Swift：可选绑定
来源：http://dali.xuanzx.com/Article/details/gt2sabgknto.html

if let n = opt { print(n) }
来源：http://dali.cashguo.top/Article/details/gt2iyjcnhuu.html

[T20] Swift：数组操作
来源：http://dali.cheryme.top/Article/details/gt2szxwpfis.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.guannengcc.top/Article/details/gt2azdmkpum.html

[T21] Swift：遍历
来源：http://dali.yangfankeji.com/Article/details/gt2qwwouugk.html

for x in a { print(x) }
来源：http://dali.shuidangran.top/Article/details/gt2mpvtmyht.html

[T22] Swift：字典
来源：http://dali.gotoacloud.top/Article/details/gt2alguvetf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cqqwz.cn/Article/details/gt2bbnceckj.html

[T23] Swift：函数
来源：http://dali.cqqwz.cn/Article/details/gt2tpcithom.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.nanxinkj.top/Article/details/gt2vcdbjhxx.html

[T24] Swift：闭包
来源：http://dali.guannengcc.top/Article/details/gt2tiqzdqfl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.quarkkingdee.top/Article/details/gt2lkhwosqv.html

[T25] Swift：结构体
来源：http://dali.0kj1m.cn/Article/details/gt2cutzartg.html

struct P { var x: Int }
来源：http://dali.tianlin.xyz/Article/details/gt2lyucwzba.html

[T26] Swift：类与重写
来源：http://dali.xinyue.icu/Article/details/gt2dudbnjzx.html

class A: Base { override func f() {} }
来源：http://dali.tanke756.top/Article/details/gt2srejxfhz.html

[T27] Swift：错误处理
来源：http://dali.gzhubu.top/Article/details/gt2hawgxrpz.html

do { try f() } catch { print(error) }
来源：http://dali.gzhubu.top/Article/details/gt2omajfipp.html

[T28] Swift：枚举
来源：http://dali.yj20258888.top/Article/details/gt2egzwascz.html

enum Color { case red, green }
来源：http://dali.fengsongda.top/Article/details/gt2rnnkeoyg.html

[T29] Swift：guard 提前返回
来源：http://dali.zhongyouzk.top/Article/details/gt2tcylthyw.html

guard let x = opt else { return }
来源：http://dali.smart0.xyz/Article/details/gt2oadgurca.html

[T30] Swift：协议
来源：http://dali.sysykeji.top/Article/details/gt2ydoogkhr.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2nelbzvry.html

[T31] Lua：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gt2ktsfqqxz.html

print("Hello")
来源：http://dali.daria6918.cn/Article/details/gt2mefjsopv.html

[T32] Lua：局部变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hpawnhtj.html

local a = 1
来源：http://dali.xylfe.cn/Article/details/gt2jypknbil.html

[T33] Lua：表（数组）
来源：http://dali.ydzc1.top/Article/details/gt2qtzlqxqt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yonumen.top/Article/details/gt2prwbuobn.html

[T34] Lua：遍历表
来源：http://dali.cheryme.top/Article/details/gt2vontthij.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nanxinkj.top/Article/details/gt2umjdlslz.html

[T35] Lua：字典表
来源：http://dali.feifeiyinyue.top/Article/details/gt2erygauot.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yuxming.cn/Article/details/gt2girrwotq.html

[T36] Lua：函数
来源：http://dali.c1oappe.top/Article/details/gt2rjhvtrrd.html

function add(a, b) return a + b end
来源：http://dali.hfpthk.cn/Article/details/gt2llknhdrz.html

[T37] Lua：字符串拼接
来源：http://dali.hammf.cn/Article/details/gt2wrfzbfqi.html

"a" .. "b"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hkotjvlm.html

[T38] Lua：条件
来源：http://dali.shzxlz.cn/Article/details/gt2kqchoyiv.html

if x > 0 then print("正") end
来源：http://dali.mhx1999.top/Article/details/gt2uwhdsigc.html

[T39] Lua：模式匹配
来源：http://dali.hysaishi.cn/Article/details/gt2mimvzhpg.html

string.find(s, "%d+")
来源：http://dali.yuanzhike.top/Article/details/gt2ptmevxgj.html

[T40] Lua：元表
来源：http://dali.yuxming.cn/Article/details/gt2akyaalkm.html

setmetatable({}, { __index = base })
来源：http://dali.yanxiufei.cn/Article/details/gt2zwdicwke.html

[T41] Perl：Hello World
来源：http://dali.redwolf501.top/Article/details/gt2wiiawgft.html

print "Hello\n";
来源：http://dali.feifeiyinyue.top/Article/details/gt2maakvwbk.html

[T42] Perl：变量类型
来源：http://dali.ehwqpu.com/Article/details/gt2vadtypgn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.pengpengdd.cyou/Article/details/gt2dzmvfnpl.html

[T43] Perl：字符串插值
来源：http://dali.yangfankeji.com/Article/details/gt2ncnkonbu.html

"值: $a"
来源：http://dali.nanxuanxn.top/Article/details/gt2lnntpjya.html

[T44] Perl：条件
来源：http://dali.zdqjudy.top/Article/details/gt2ywlldaui.html

if ($a > 0) { print "正"; }
来源：http://dali.sufxvd.cn/Article/details/gt2uavkcbqs.html

[T45] Perl：数组遍历
来源：http://dali.ehwqpu.com/Article/details/gt2gvozhoov.html

for my $x (@arr) { print $x; }
来源：http://dali.yueranfly.top/Article/details/gt2etopdxku.html

[T46] Perl：哈希操作
来源：http://dali.daxiang520.top/Article/details/gt2kflryjul.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2ypcxxxai.html

[T47] Perl：正则捕获
来源：http://dali.sweek.top/Article/details/gt2vghtapja.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hysaishi.cn/Article/details/gt2yhwcyndi.html

[T48] Perl：正则替换
来源：http://dali.sysykeji.top/Article/details/gt2hoqkjdag.html

$s =~ s/old/new/g;
来源：http://dali.cdnleiting.top/Article/details/gt2vgclhafv.html

[T49] Perl：函数
来源：http://dali.nanxuanxn.top/Article/details/gt2uyfwxnbs.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2cryuzotk.html

[T50] Perl：逐行读文件
来源：http://dali.pycfn.com/Article/details/gt2wvkueosj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yueranfly.top/Article/details/gt2ixiliaig.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2tjtafibq.html

[T51] Scala：Hello World
来源：http://dali.yueranfly.top/Article/details/gt2shpmlsbv.html

println("Hello")
来源：http://dali.chenzaomai.com/Article/details/gt2tuyifjbo.html

[T52] Scala：变量
来源：http://dali.cdnleiting.top/Article/details/gt2mqisiqfs.html

val a = 1;  var b = 2
来源：http://dali.svipenyu.cn/Article/details/gt2tejsuzpd.html

[T53] Scala：字符串插值
来源：http://dali.meibo888.top/Article/details/gt2lvgmctzq.html

s"值: $b"
来源：http://dali.chenzaomai.com/Article/details/gt2cxyecogo.html

[T54] Scala：集合映射
来源：http://dali.yvedp.cn/Article/details/gt2dbqkcwkh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shzxlz.cn/Article/details/gt2roilbdyr.html

[T55] Scala：集合过滤
来源：http://dali.yuanzhike.top/Article/details/gt2fpcgnhjd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.iojbl.cn/Article/details/gt2yxhaohae.html

[T56] Scala：样例类
来源：http://dali.xylfe.cn/Article/details/gt2qhqlbqss.html

case class User(name: String, age: Int)
来源：http://dali.jinqigfzy.top/Article/details/gt2pkxaxtnx.html

[T57] Scala：模式匹配
来源：http://dali.xuetiantiany.cn/Article/details/gt2mbjioepn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yj202588.top/Article/details/gt2zjufdeti.html

[T58] Scala：函数定义
来源：http://dali.yueranfly.top/Article/details/gt2guztgylv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hnqzz.top/Article/details/gt2rqqcpsnq.html

[T59] Scala：循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kesbxnhv.html

for (i <- 1 to 10) println(i)
来源：http://dali.fzhhl.top/Article/details/gt2vlrzrtnh.html

[T60] Scala：折叠
来源：http://dali.sysykeji.top/Article/details/gt2hhgitanw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cucudq.cn/Article/details/gt2hueoatve.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2bnszvnwx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jqgufenzy.top/Article/details/gt2ntoexhjs.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2lhjjymih.html

[U01] Py：创建虚拟环境
来源：http://dali.cucudq.cn/Article/details/gt2ftfknafp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ppjwa.cn/Article/details/gt2dfthjfmj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.aizwys.cn/Article/details/gt2mbrudsxw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.fengsongda.top/Article/details/gt2syybqvni.html

[U03] Py：加载 .env 配置
来源：http://dali.yanxiufei.cn/Article/details/gt2gsvvkdgw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jqgfzy.top/Article/details/gt2dbxbrqbb.html

[U04] Py：变量调试打印
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cdckqbyo.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.iojbl.cn/Article/details/gt2peqovoxp.html

[U05] Py：列表去重且保序
来源：http://dali.jqgfzy.top/Article/details/gt2bdwncqny.html

list(dict.fromkeys(arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2legtafue.html

[U06] Py：合并两个字典
来源：http://dali.yj20258.top/Article/details/gt2hoyvuwzx.html

{**a, **b}
来源：http://dali.316326.xyz/Article/details/gt2dyeajges.html

[U07] Py：反转字典键值
来源：http://dali.tanke756.top/Article/details/gt2elspysrx.html

{v: k for k, v in d.items()}
来源：http://dali.aizwys.cn/Article/details/gt2zzbigozm.html

[U08] Py：展平二维列表
来源：http://dali.chenlongwang.top/Article/details/gt2kozkpwnu.html

[y for x in nested for y in x]
来源：http://dali.9152youxi.cn/Article/details/gt2ivgpmypn.html

[U09] Py：字典取最大值的键
来源：http://dali.jinghuilouyu.cn/Article/details/gt2npugyiff.html

max(d, key=d.get)
来源：http://dali.yongpay.top/Article/details/gt2goamcyjg.html

[U10] Py：按值排序字典
来源：http://dali.zdqjudy.top/Article/details/gt2xnvxjpro.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.tanke756.top/Article/details/gt2fesejoyt.html

[U11] Py：生成器表达式
来源：http://dali.xuanzx.com/Article/details/gt2nvavahph.html

(x * 2 for x in arr)
来源：http://dali.redwolf501.top/Article/details/gt2bwdtmhkb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.c1oappe.top/Article/details/gt2viobgrtk.html

Counter(arr).most_common(3)
来源：http://dali.xylfe.cn/Article/details/gt2qtavmmeg.html

[U13] Py：固定长度队列
来源：http://dali.redwolf501.top/Article/details/gt2ajdjjujn.html

deque(maxlen=10)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iectvfbe.html

[U14] Py：分组收集到列表
来源：http://dali.tanke756.top/Article/details/gt2xwkcepqm.html

defaultdict(list)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hwppivho.html

[U15] Py：高精度计时
来源：http://dali.jqgfzy.top/Article/details/gt2mekfzdnh.html

t = time.perf_counter()
来源：http://dali.zdqjudy.top/Article/details/gt2udvgqhbx.html

[U16] Py：命令行参数解析
来源：http://dali.gotoacloud.top/Article/details/gt2rthummdh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2prumdigd.html

[U17] Py：初始化日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pzbpcnua.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.meibo888.top/Article/details/gt2govpesjn.html

[U18] Py：预编译正则
来源：http://dali.gotoacloud.top/Article/details/gt2aythbqfu.html

pat = re.compile(r"\d+")
来源：http://dali.havefunace.top/Article/details/gt2cuhxqegf.html

[U19] Py：正则替换带回调
来源：http://dali.haohaochexian.top/Article/details/gt2aglqxcqx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.c1oappe.top/Article/details/gt2rbgimqyv.html

[U20] Py：缓存函数结果
来源：http://dali.zdqjudy.top/Article/details/gt2iwtutixe.html

@functools.lru_cache(maxsize=None)
来源：http://dali.smart0.xyz/Article/details/gt2jdoalhin.html


<!-- 参考信息 -->