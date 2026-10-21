代发 wailian999

read -rp "请输入: " ans
来源：http://dali.xylfe.cn/Article/details/gteakwknuz.html

[R78] 交互式菜单
来源：http://dali.shzxlz.cn/Article/details/gtcvmtjcoy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xinyue.icu/Article/details/gttxwcdjwu.html

[R79] 解析命令行选项
来源：http://dali.xuanzx.com/Article/details/gterrpijve.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ybcxt.top/Article/details/gtwcgzkzdf.html

[R80] 查看脚本执行耗时
来源：http://dali.daria6918.cn/Article/details/gtqsbwallf.html

time ./run.sh
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxwsesho.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtxdjteinl.html

S. C / C++ 专题
来源：http://dali.jlsjyb.cn/Article/details/gtesyvmdkz.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtrnrujquv.html

[S01] C：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtlszdpbsw.html

#include <stdio.h>
来源：http://dali.zdqjudy.top/Article/details/gtqnofjdki.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.iojbl.cn/Article/details/gttqjgpnyx.html

[S02] C：变量与格式化输出
来源：http://dali.gogol.net.cn/Article/details/gtcjkuuleh.html

int a = 10; printf("%d\n", a);
来源：http://dali.yvedp.cn/Article/details/gtpxbevici.html

[S03] C：读入整数
来源：http://dali.ydzc1.top/Article/details/gtjcojoqtx.html

int x; scanf("%d", &x);
来源：http://dali.tian-w.cn/Article/details/gtkjwyhpvu.html

[S04] C：字符串复制
来源：http://dali.zhongyouzk.top/Article/details/gtxvyyjstp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gaohongyu789.top/Article/details/gtrvoknaqz.html

[S05] C：字符串长度
来源：http://dali.smart0.xyz/Article/details/gtslavtssh.html

strlen(s)
来源：http://dali.c1oappe.top/Article/details/gtgwhrycak.html

[S06] C：字符串比较
来源：http://dali.0kj1m.cn/Article/details/gtnhjhiiui.html

strcmp(a, b) == 0
来源：http://dali.birdmap.top/Article/details/gtbxastcjm.html

[S07] C：数组遍历求和
来源：http://dali.chenzaomai.com/Article/details/gthnfswdfx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yangfankeji.com/Article/details/gtbklpxtxo.html

[S08] C：动态内存分配与释放
来源：http://dali.316326.xyz/Article/details/gtkspxacvo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ybcxt.top/Article/details/gtqjqwdtbe.html

[S09] C：结构体定义与初始化
来源：http://dali.chenjidiqi.icu/Article/details/gtkpiyaprg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.kuanghao11.cn/Article/details/gtctlabycz.html

[S10] C：指针与解引用
来源：http://dali.tianlin.xyz/Article/details/gtxgipzbww.html

int *p = &a;  *p = 5;
来源：http://dali.hnqzz.top/Article/details/gtbtutwhav.html

[S11] C：逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gtxgdbvfnw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinyuanbaomall.cn/Article/details/gticaxezpg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.pengpengdd.cyou/Article/details/gtzvgtdxeq.html

fclose(f);
来源：http://dali.xuetiantiany.cn/Article/details/gtohlpyhaw.html

[S12] C：写文件
来源：http://dali.jqgfzy.top/Article/details/gtvekeszli.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.aibaodan.cn/Article/details/gtpgytdxgf.html

[S13] C：宏定义
来源：http://dali.zhengqikj.top/Article/details/gtyykkqzgb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sufxvd.cn/Article/details/gtkvliygsd.html

[S14] C：枚举
来源：http://dali.daria6918.cn/Article/details/gtunmcjtou.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.iojbl.cn/Article/details/gtlehkyuyh.html

[S15] C：类型转换
来源：http://dali.yangfankeji.com/Article/details/gtcdfqbdom.html

(double) a / b
来源：http://dali.pengpengdd.cyou/Article/details/gtdmybezvl.html

[S16] C：位操作置位
来源：http://dali.shuidangran.top/Article/details/gtjvhinjam.html

x |= (1 << 3);
来源：http://dali.yvedp.cn/Article/details/gtdygwqaqa.html

[S17] C：安全拼接字符串
来源：http://dali.yvedp.cn/Article/details/gtahmgfqci.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.meibo888.top/Article/details/gtuajqppok.html

[S18] C：命令行参数
来源：http://dali.jiagoushi.top/Article/details/gtqlhlnlpf.html

int main(int argc, char **argv)
来源：http://dali.hysaishi.cn/Article/details/gtbhzzrxpk.html

[S19] C：快速排序
来源：http://dali.shanyushiyangtech.top/Article/details/gthigqstyo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenzaomai.com/Article/details/gtwqtyugov.html

[S20] C：二分查找
来源：http://dali.hywenlv.cn/Article/details/gtiotsmsaz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tanke756.top/Article/details/gtczalcved.html

[S21] C：字符类别判断
来源：http://dali.jqgufenzy.top/Article/details/gtjhkifuvj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.guannengcc.top/Article/details/gtxffcqpkr.html

[S22] C：字符串转数字
来源：http://dali.chenlongwang.top/Article/details/gttwbdcfzd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zycfv.cn/Article/details/gtaanbhenx.html

[S23] C：随机数
来源：http://dali.jinqigufen.top/Article/details/gtidlbvbur.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yongpay.top/Article/details/gtmytxrnnc.html

[S24] C：获取本地时间
来源：http://dali.jinghuilouyu.cn/Article/details/gtskawuvjm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhengqikj.top/Article/details/gtnhyckxfg.html

[S25] C：内存拷贝
来源：http://dali.cdnleiting.top/Article/details/gtmxfehwnc.html

memcpy(dst, src, n);
来源：http://dali.tanke756.top/Article/details/gtwmnbjyfk.html

[S26] C：内存清零
来源：http://dali.bjfxy.top/Article/details/gtkdbzcugb.html

memset(a, 0, sizeof a);
来源：http://dali.zdqjudy.top/Article/details/gttyrolavz.html

[S27] C：定义常量
来源：http://dali.c1oappe.top/Article/details/gtteuxzgpo.html

const double PI = 3.14159;
来源：http://dali.iojbl.cn/Article/details/gtjshzuwbe.html

[S28] C：静态变量
来源：http://dali.zycfv.cn/Article/details/gtpyadpmnp.html

static int counter = 0;
来源：http://dali.snrcjt.cn/Article/details/gtphysgmzs.html

[S29] C：变参函数
来源：http://dali.yonumen.top/Article/details/gtgiykwfpv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nanxinkj.top/Article/details/gttaavdtnv.html

[S30] C：头文件保护
来源：http://dali.nwbrower.top/Article/details/gtcsbumtcd.html

#ifndef X_H
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnglhfnne.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gtrtkyuvah.html

#endif
来源：http://dali.feifeiyinyue.top/Article/details/gtizvoaegt.html

[S31] C++：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnhyuewo.html

#include <iostream>
来源：http://dali.shuidangran.top/Article/details/gtnblhazgp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tanke756.top/Article/details/gtizepaopk.html

[S32] C++：字符串
来源：http://dali.guannengcc.top/Article/details/gtxodpptli.html

std::string s = "hi";  s += "!";
来源：http://dali.redwolf501.top/Article/details/gtcvetvgls.html

[S33] C++：vector 增删
来源：http://dali.wangshuangyany.cn/Article/details/gtnfoubctb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.quarkkingdee.top/Article/details/gtmsfjbqph.html

[S34] C++：遍历 vector
来源：http://dali.xuanzx.com/Article/details/gtcvvwkmso.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.0kj1m.cn/Article/details/gtftyjbsha.html

[S35] C++：map
来源：http://dali.smart0.xyz/Article/details/gttjgbhofe.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzyypecjz.html

[S36] C++：unordered_map
来源：http://dali.cdnleiting.top/Article/details/gtzjaoftey.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtwjjsfglr.html

[S37] C++：set
来源：http://dali.nanxuanxn.top/Article/details/gtmplybdwn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.kuanghao11.cn/Article/details/gtfnjaowpz.html

[S38] C++：排序
来源：http://dali.chenjidiqi.icu/Article/details/gtsdvydfef.html

std::sort(v.begin(), v.end());
来源：http://dali.zhiwuduotai.top/Article/details/gtaqnurfoi.html

[S39] C++：自定义比较器排序
来源：http://dali.yanxiufei.cn/Article/details/gtclxkvikq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jqgfzy.top/Article/details/gtqywfnqdi.html

[S40] C++：查找元素
来源：http://dali.yuxming.cn/Article/details/gtitjetnav.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cheryme.top/Article/details/gtdqmzxvip.html

[S41] C++：类与构造函数
来源：http://dali.cashguo.top/Article/details/gtdizmcpni.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.dashuyun.cn/Article/details/gtqbdebejm.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gtbvldpkxw.html

class B : public Base { public: void f() override {} };
来源：http://dali.chenzaomai.com/Article/details/gtnczakhby.html

[S43] C++：智能指针
来源：http://dali.hammf.cn/Article/details/gtribpqiku.html

auto p = std::make_unique<int>(5);
来源：http://dali.nanxuanxn.top/Article/details/gtzipbujmn.html

[S44] C++：引用传参
来源：http://dali.zycfv.cn/Article/details/gtvtepbodp.html

void inc(int &x) { ++x; }
来源：http://dali.guowangkeji.top/Article/details/gtvipdpniz.html

[S45] C++：lambda
来源：http://dali.hysaishi.cn/Article/details/gttnyazfsv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj202588.top/Article/details/gtsgbqhyvk.html

[S46] C++：函数模板
来源：http://dali.jqgufenzy.top/Article/details/gtykbaewdw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.andypj.xyz/Article/details/gtsndtoayu.html

[S47] C++：结构化绑定遍历
来源：http://dali.cdnleiting.top/Article/details/gtlgawiovh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbfgzyoph.html

[S48] C++：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtdovwaefe.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jiagoushi.top/Article/details/gtthudatax.html

while (std::getline(in, line)) { }
来源：http://dali.ivvv.top/Article/details/gtdrygbvbk.html

[S49] C++：写文件
来源：http://dali.yanxiufei.cn/Article/details/gttugiwnpv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hongshengwenyu.top/Article/details/gteyenznlq.html

[S50] C++：格式化数字
来源：http://dali.snrcjt.cn/Article/details/gtfkgmlixv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ybcxt.top/Article/details/gtlttdosbn.html

[S51] C++：显式类型转换
来源：http://dali.tian-w.cn/Article/details/gtgmxaxjtb.html

static_cast<double>(a) / b
来源：http://dali.hywenlv.cn/Article/details/gteiriqoeb.html

[S52] C++：const 与 noexcept
来源：http://dali.gaohongyu789.top/Article/details/gthtwnkwrm.html

int size() const noexcept { return n_; }
来源：http://dali.dianchejie.cn/Article/details/gtkcwnrejd.html

[S53] C++：移动语义
来源：http://dali.yuxming.cn/Article/details/gtxqpopjru.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gtaoaetdly.html

[S54] C++：异常处理
来源：http://dali.yanxiufei.cn/Article/details/gtwvmlsyfw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hongshengwenyu.top/Article/details/gtgghajome.html

[S55] C++：结构化绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxaxanuj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.iojbl.cn/Article/details/gtdtmzwdwq.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gtzdulsmhw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cqqwz.cn/Article/details/gtxrwccgwb.html

[S57] C++：编译期常量
来源：http://dali.ybcxt.top/Article/details/gtujdseucd.html

constexpr int N = 10;
来源：http://dali.hfpthk.cn/Article/details/gtelanypkp.html

[S58] C++：命名空间
来源：http://dali.sufxvd.cn/Article/details/gtxctnjiab.html

namespace ns { int f() { return 1; } }
来源：http://dali.fengsongda.top/Article/details/gtfrqqtxzu.html

[S59] C++：静态断言
来源：http://dali.chenlongwang.top/Article/details/gtosdsqzbi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.wangdashe.top/Article/details/gtqsidqull.html

[S60] C++：遍历并删除元素
来源：http://dali.havefunace.top/Article/details/gtnlgffamk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.feifeiyinyue.top/Article/details/gtwoiofdqm.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtvyxaqxzc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shzxlz.cn/Article/details/gtlceytcmj.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtqxlsjqkf.html

[T01] Kotlin：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtrkuauzrt.html

println("Hello")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzdfbtltr.html

[T02] Kotlin：变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvdntryom.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shanyushiyangtech.top/Article/details/gtsiwstvyd.html

[T03] Kotlin：字符串模板
来源：http://dali.yonumen.top/Article/details/gtmhspdbnl.html

"值: $b"
来源：http://dali.hongshengwenyu.top/Article/details/gtizrhxgio.html

[T04] Kotlin：空安全
来源：http://dali.yangfankeji.com/Article/details/gtczygwllv.html

val n: String? = null;  n?.length
来源：http://dali.sysykeji.top/Article/details/gtuhvasfsq.html

[T05] Kotlin：when 表达式
来源：http://dali.yonumen.top/Article/details/gtlaybbjsw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.mhx1999.top/Article/details/gtfmbdymna.html

[T06] Kotlin：集合映射
来源：http://dali.tianlin.xyz/Article/details/gtfpfxgfbj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtqeewlmqz.html

[T07] Kotlin：集合过滤
来源：http://dali.yanxiufei.cn/Article/details/gtfhmwbwpv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.316326.xyz/Article/details/gtxytivhbb.html

[T08] Kotlin：数据类
来源：http://dali.shanyushiyangtech.top/Article/details/gtzffggmrk.html

data class User(val name: String, val age: Int)
来源：http://dali.kuanghao11.cn/Article/details/gthrmjcuyt.html

[T09] Kotlin：扩展函数
来源：http://dali.cqqwz.cn/Article/details/gtxqcbvwhb.html

fun String.exclaim() = this + "!"
来源：http://dali.nanxuanxn.top/Article/details/gthtgreyfq.html

[T10] Kotlin：默认参数
来源：http://dali.pengpengdd.cyou/Article/details/gtipjgpzxq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.svipenyu.cn/Article/details/gtpzovezst.html

[T11] Kotlin：协程
来源：http://dali.guannengcc.top/Article/details/gttzpncztx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yangfankeji.com/Article/details/gtilwhgsmy.html

[T12] Kotlin：解构声明
来源：http://dali.chenjidiqi.icu/Article/details/gtlgqdkrbx.html

val (a, b) = Pair(1, 2)
来源：http://dali.xuanzx.com/Article/details/gtfmbfsgoc.html

[T13] Kotlin：只读 Map
来源：http://dali.yongpay.top/Article/details/gtpffvzcqd.html

val m = mapOf("a" to 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtowwgymko.html

[T14] Kotlin：循环
来源：http://dali.daria6918.cn/Article/details/gtsprdptpq.html

for (i in 1..10) println(i)
来源：http://dali.aizwys.cn/Article/details/gtkqpfznki.html

[T15] Kotlin：接口
来源：http://dali.yuxming.cn/Article/details/gtxjipbvlb.html

interface Shape { fun area(): Double }
来源：http://dali.havefunace.top/Article/details/gtwgjnkzwn.html

[T16] Swift：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtpdtqyukv.html

print("Hello")
来源：http://dali.nanxinkj.top/Article/details/gtmqbsllvc.html

[T17] Swift：变量与常量
来源：http://dali.hfpthk.cn/Article/details/gtegcgirsn.html

var a = 1;  let b = 2
来源：http://dali.dianchejie.cn/Article/details/gtgbqyoede.html

[T18] Swift：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gtrhrjbypj.html

"值: \(b)"
来源：http://dali.jyoumei.cn/Article/details/gtgqmznyji.html

[T19] Swift：可选绑定
来源：http://dali.jlsjyb.cn/Article/details/gtvoxttezk.html

if let n = opt { print(n) }
来源：http://dali.jqgfzy.top/Article/details/gtbfwwutxp.html

[T20] Swift：数组操作
来源：http://dali.haohaochexian.top/Article/details/gtqmhibgse.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jlsjyb.cn/Article/details/gtphjogjel.html

[T21] Swift：遍历
来源：http://dali.0kj1m.cn/Article/details/gtowqtpqpx.html

for x in a { print(x) }
来源：http://dali.yangfankeji.com/Article/details/gtzhedgbbn.html

[T22] Swift：字典
来源：http://dali.yueranfly.top/Article/details/gtunruhpbh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtodlejgqp.html

[T23] Swift：函数
来源：http://dali.c1oappe.top/Article/details/gtvnhyeqol.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.nanxinkj.top/Article/details/gtrzirrepb.html

[T24] Swift：闭包
来源：http://dali.pycfn.com/Article/details/gtimgcrbpf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.dianchejie.cn/Article/details/gtwiqohjyc.html

[T25] Swift：结构体
来源：http://dali.shzxlz.cn/Article/details/gtlfrcovck.html

struct P { var x: Int }
来源：http://dali.jyoumei.cn/Article/details/gtrybzdczs.html

[T26] Swift：类与重写
来源：http://dali.birdmap.top/Article/details/gtbgplcpru.html

class A: Base { override func f() {} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkkfnlsol.html

[T27] Swift：错误处理
来源：http://dali.dianchejie.cn/Article/details/gtieeythrz.html

do { try f() } catch { print(error) }
来源：http://dali.ppjwa.cn/Article/details/gtwqquqzqn.html

[T28] Swift：枚举
来源：http://dali.jqgufenzy.top/Article/details/gtznbdchve.html

enum Color { case red, green }
来源：http://dali.dashuyun.cn/Article/details/gtrxtesvpu.html

[T29] Swift：guard 提前返回
来源：http://dali.iojbl.cn/Article/details/gtuzpxacls.html

guard let x = opt else { return }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgbgffeiz.html

[T30] Swift：协议
来源：http://dali.c1oappe.top/Article/details/gtoobuzskn.html

protocol Shape { func area() -> Double }
来源：http://dali.xziqi.cn/Article/details/gtbfvzwgac.html

[T31] Lua：Hello World
来源：http://dali.yuxming.cn/Article/details/gtfurynuip.html

print("Hello")
来源：http://dali.yueranfly.top/Article/details/gtmgddhoid.html

[T32] Lua：局部变量
来源：http://dali.c1oappe.top/Article/details/gtjmvqxpzr.html

local a = 1
来源：http://dali.aibaodan.cn/Article/details/gtomavxqqx.html

[T33] Lua：表（数组）
来源：http://dali.smart0.xyz/Article/details/gtuglwykyr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ydzc1.top/Article/details/gthxshstqk.html

[T34] Lua：遍历表
来源：http://dali.vqdsnc.cn/Article/details/gtieunrndh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cqqwz.cn/Article/details/gtfmkplqgj.html

[T35] Lua：字典表
来源：http://dali.snrcjt.cn/Article/details/gtdtjpitad.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cucudq.cn/Article/details/gtctqehlom.html

[T36] Lua：函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyiwqkkye.html

function add(a, b) return a + b end
来源：http://dali.svipenyu.cn/Article/details/gtgrouicms.html

[T37] Lua：字符串拼接
来源：http://dali.birdmap.top/Article/details/gtdrhovopk.html

"a" .. "b"
来源：http://dali.316326.xyz/Article/details/gtbgkedmov.html

[T38] Lua：条件
来源：http://dali.guannengcc.top/Article/details/gtmffahxrd.html

if x > 0 then print("正") end
来源：http://dali.sweek.top/Article/details/gthfsgkhxw.html

[T39] Lua：模式匹配
来源：http://dali.jqgfzy.top/Article/details/gthodipkth.html

string.find(s, "%d+")
来源：http://dali.c1oappe.top/Article/details/gtikdpblck.html

[T40] Lua：元表
来源：http://dali.havefunace.top/Article/details/gtrxwbyfle.html

setmetatable({}, { __index = base })
来源：http://dali.sxryk.cn/Article/details/gtgbkaaywd.html

[T41] Perl：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtffdzvutl.html

print "Hello\n";
来源：http://dali.haohaochexian.top/Article/details/gtakiexrqa.html

[T42] Perl：变量类型
来源：http://dali.snrcjt.cn/Article/details/gtzwkvtgbk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.0kj1m.cn/Article/details/gtzlgetxfd.html

[T43] Perl：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gtsyjkzxod.html

"值: $a"
来源：http://dali.mhx1999.top/Article/details/gtfaxkwdjn.html

[T44] Perl：条件
来源：http://dali.shuidangran.top/Article/details/gtayxuvqoz.html

if ($a > 0) { print "正"; }
来源：http://dali.aizwys.cn/Article/details/gtjrvhrrbn.html

[T45] Perl：数组遍历
来源：http://dali.dianchejie.cn/Article/details/gtfjzntcnj.html

for my $x (@arr) { print $x; }
来源：http://dali.cashguo.top/Article/details/gtezepvvgc.html

[T46] Perl：哈希操作
来源：http://dali.sysykeji.top/Article/details/gthemgntin.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhoulong.xyz/Article/details/gtaeelzvho.html

[T47] Perl：正则捕获
来源：http://dali.ywan-chungtsiang.top/Article/details/gtctirsrti.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yuanzhike.top/Article/details/gtiiyhutxa.html

[T48] Perl：正则替换
来源：http://dali.shzxlz.cn/Article/details/gtxuedbdor.html

$s =~ s/old/new/g;
来源：http://dali.shangyingyoupin.top/Article/details/gtavemecix.html

[T49] Perl：函数
来源：http://dali.hysaishi.cn/Article/details/gtitvqpfsc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jqgfzy.top/Article/details/gtwfjrbrcx.html

[T50] Perl：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gtbnffbhwd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.chenlongwang.top/Article/details/gtsopyghrh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yvedp.cn/Article/details/gtiqqwbbvj.html

[T51] Scala：Hello World
来源：http://dali.daria6918.cn/Article/details/gtfdwrpdrt.html

println("Hello")
来源：http://dali.xziqi.cn/Article/details/gtlidabapl.html

[T52] Scala：变量
来源：http://dali.shzxlz.cn/Article/details/gtqevighmk.html

val a = 1;  var b = 2
来源：http://dali.xziqi.cn/Article/details/gtxptjzyit.html

[T53] Scala：字符串插值
来源：http://dali.ppjwa.cn/Article/details/gtdwjmvisx.html

s"值: $b"
来源：http://dali.jianghu66.top/Article/details/gtjmdmqtcx.html

[T54] Scala：集合映射
来源：http://dali.cheryme.top/Article/details/gtohxptial.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yueranfly.top/Article/details/gtxmyofktq.html

[T55] Scala：集合过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtqwzrrohy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.tian-w.cn/Article/details/gtfkymvkbr.html

[T56] Scala：样例类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwrlnwaht.html

case class User(name: String, age: Int)
来源：http://dali.jlsjyb.cn/Article/details/gtdgwmjavd.html

[T57] Scala：模式匹配
来源：http://dali.jqgufenzy.top/Article/details/gtnojhtvqm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.snrcjt.cn/Article/details/gtoqchdbbq.html

[T58] Scala：函数定义
来源：http://dali.zhoulong.xyz/Article/details/gtuffoblqg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yj20258888.top/Article/details/gtlgxudldu.html

[T59] Scala：循环
来源：http://dali.cashguo.top/Article/details/gtzrttvlhd.html

for (i <- 1 to 10) println(i)
来源：http://dali.snrcjt.cn/Article/details/gtpoyrmolx.html

[T60] Scala：折叠
来源：http://dali.zhongyouzk.top/Article/details/gtuwmwtnjh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ehwqpu.com/Article/details/gtcomtvwao.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtfkabqjen.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.nwbrower.top/Article/details/gtpsxtawvi.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtyzztgcos.html

[U01] Py：创建虚拟环境
来源：http://dali.quarkkingdee.top/Article/details/gtojefkegi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.fzhhl.top/Article/details/gtqichfsnl.html

[U02] Py：导出 / 安装依赖
来源：http://dali.0kj1m.cn/Article/details/gtlmosidpu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hnxiangtu.top/Article/details/gtptskarem.html

[U03] Py：加载 .env 配置
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvmxlnff.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.aizwys.cn/Article/details/gtasgzxdid.html

[U04] Py：变量调试打印
来源：http://dali.zdqjudy.top/Article/details/gtianlaqyq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jiagoushi.top/Article/details/gtciskgilb.html

[U05] Py：列表去重且保序
来源：http://dali.jqgfzy.top/Article/details/gtkbedrmuw.html

list(dict.fromkeys(arr))
来源：http://dali.ybcxt.top/Article/details/gtxricmohp.html

[U06] Py：合并两个字典
来源：http://dali.bjfxy.top/Article/details/gtszwyvrqv.html

{**a, **b}
来源：http://dali.hnqzz.top/Article/details/gtyevcodur.html

[U07] Py：反转字典键值
来源：http://dali.guowangkeji.top/Article/details/gtoavykeie.html

{v: k for k, v in d.items()}
来源：http://dali.nanxinkj.top/Article/details/gtcadwuypd.html

[U08] Py：展平二维列表
来源：http://dali.gogol.net.cn/Article/details/gtjrrreqhq.html

[y for x in nested for y in x]
来源：http://dali.yj20258.top/Article/details/gtjxvpgzgt.html

[U09] Py：字典取最大值的键
来源：http://dali.sweek.top/Article/details/gtmvzztwzx.html

max(d, key=d.get)
来源：http://dali.jinqigfzy.top/Article/details/gtfpsmsjhd.html

[U10] Py：按值排序字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqfzruhjp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.meibo888.top/Article/details/gtlzhmkmqc.html

[U11] Py：生成器表达式
来源：http://dali.yj20258.top/Article/details/gtzojkfnck.html

(x * 2 for x in arr)
来源：http://dali.yj20258.top/Article/details/gtqiyjvbjz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shzxlz.cn/Article/details/gtgenfhrhv.html

Counter(arr).most_common(3)
来源：http://dali.gogol.net.cn/Article/details/gtgalymlsq.html

[U13] Py：固定长度队列
来源：http://dali.ybcxt.top/Article/details/gtffqxracl.html

deque(maxlen=10)
来源：http://dali.nwbrower.top/Article/details/gtzlouqmiz.html

[U14] Py：分组收集到列表
来源：http://dali.svipenyu.cn/Article/details/gtokmtkpvf.html

defaultdict(list)
来源：http://dali.cucudq.cn/Article/details/gtjjayohme.html

[U15] Py：高精度计时
来源：http://dali.zhoulong.xyz/Article/details/gtzvrnhrtq.html

t = time.perf_counter()
来源：http://dali.yj20258.top/Article/details/gteopnycwm.html

[U16] Py：命令行参数解析
来源：http://dali.yuanzhike.top/Article/details/gtkmgoowwj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.meibo888.top/Article/details/gtsrgsffwf.html

[U17] Py：初始化日志
来源：http://dali.fengsongda.top/Article/details/gtyhabzhgz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hongshengwenyu.top/Article/details/gtvatofxby.html

[U18] Py：预编译正则
来源：http://dali.nanxinkj.top/Article/details/gtkfkuasdo.html

pat = re.compile(r"\d+")
来源：http://dali.ydzc1.top/Article/details/gtcatpwgpj.html


<!-- 参考信息 -->