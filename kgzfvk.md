代发 wailian999

head -c 16 /dev/urandom | base64
来源：http://dali.sysykeji.top/Article/details/gtergbhcdx.html

[R70] 时间戳与互转
来源：http://dali.9152youxi.cn/Article/details/gthkipnczb.html

date +%s;  date -d @1700000000
来源：http://dali.nanxinkj.top/Article/details/gtbrpbbuad.html

[R71] 日期格式化
来源：http://dali.tian-w.cn/Article/details/gtswxepxbi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hywenlv.cn/Article/details/gtpbietqzj.html

[R72] 等待端口就绪
来源：http://dali.yj20258888.top/Article/details/gtdxapslun.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yuanzhike.top/Article/details/gtsgynbhdr.html

[R73] 分割大日志
来源：http://dali.dashuyun.cn/Article/details/gtpehpumyl.html

split -l 1000 big.log part_
来源：http://dali.zycfv.cn/Article/details/gtaelgzlww.html

[R74] 批量重命名
来源：http://dali.shanyushiyangtech.top/Article/details/gtcjjelhyu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jiagoushi.top/Article/details/gtzthjnxqf.html

[R75] 导出环境变量
来源：http://dali.tianlin.xyz/Article/details/gtaosynsvh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.redwolf501.top/Article/details/gtckdjvhmf.html

[R76] 使用临时文件
来源：http://dali.jyoumei.cn/Article/details/gtcmiguldk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangshuangyany.cn/Article/details/gtktwttpgs.html

[R77] 读取用户输入
来源：http://dali.yanxiufei.cn/Article/details/gtxitmdoww.html

read -rp "请输入: " ans
来源：http://dali.c1oappe.top/Article/details/gtewzboobz.html

[R78] 交互式菜单
来源：http://dali.zhoulong.xyz/Article/details/gthxmednbv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.fzhhl.top/Article/details/gtxkpcbjoi.html

[R79] 解析命令行选项
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwffzdvib.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.c1oappe.top/Article/details/gtombwiqzy.html

[R80] 查看脚本执行耗时
来源：http://dali.jinyuanbaomall.cn/Article/details/gticwrcrqn.html

time ./run.sh
来源：http://dali.nanxinkj.top/Article/details/gtyoogezlq.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtpqttyjsz.html

S. C / C++ 专题
来源：http://dali.ppjwa.cn/Article/details/gthpeocloj.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtpfsdkawm.html

[S01] C：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtynggtqye.html

#include <stdio.h>
来源：http://dali.pengpengdd.cyou/Article/details/gtunzllmgu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cqqwz.cn/Article/details/gthrhpoyfz.html

[S02] C：变量与格式化输出
来源：http://dali.gogol.net.cn/Article/details/gtfppdjcwv.html

int a = 10; printf("%d\n", a);
来源：http://dali.nanxuanxn.top/Article/details/gtyrzoiini.html

[S03] C：读入整数
来源：http://dali.wangshuangyany.cn/Article/details/gtwqmlibpo.html

int x; scanf("%d", &x);
来源：http://dali.xuanzx.com/Article/details/gttwqinxwh.html

[S04] C：字符串复制
来源：http://dali.haohaochexian.top/Article/details/gtuhtaxwsv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jyoumei.cn/Article/details/gtplxwxoey.html

[S05] C：字符串长度
来源：http://dali.zdqjudy.top/Article/details/gtiedfzqbj.html

strlen(s)
来源：http://dali.yj20258.top/Article/details/gtxrbpilxi.html

[S06] C：字符串比较
来源：http://dali.yuxming.cn/Article/details/gtzovcczmq.html

strcmp(a, b) == 0
来源：http://dali.snrcjt.cn/Article/details/gtaujsujwg.html

[S07] C：数组遍历求和
来源：http://dali.yongpay.top/Article/details/gtzvsbhnuk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nwbrower.top/Article/details/gtavinvouz.html

[S08] C：动态内存分配与释放
来源：http://dali.xinyue.icu/Article/details/gtjqxwpiux.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zycfv.cn/Article/details/gtgmkaczuq.html

[S09] C：结构体定义与初始化
来源：http://dali.xinyue.icu/Article/details/gtxrzahmpz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbzwenod.html

[S10] C：指针与解引用
来源：http://dali.cheryme.top/Article/details/gtwgcjolhr.html

int *p = &a;  *p = 5;
来源：http://dali.bjfxy.top/Article/details/gtvinkqmii.html

[S11] C：逐行读文件
来源：http://dali.bjfxy.top/Article/details/gtkyehivkl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xylfe.cn/Article/details/gtocoaunkd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtboqakthq.html

fclose(f);
来源：http://dali.xinyue.icu/Article/details/gtgsqfmdpm.html

[S12] C：写文件
来源：http://dali.gogol.net.cn/Article/details/gtiduyhvnq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hongshengwenyu.top/Article/details/gtduuhfrgf.html

[S13] C：宏定义
来源：http://dali.xziqi.cn/Article/details/gtdofpczah.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sufxvd.cn/Article/details/gtyljfzepy.html

[S14] C：枚举
来源：http://dali.jyoumei.cn/Article/details/gtxhmqctgu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgepvtvpb.html

[S15] C：类型转换
来源：http://dali.jqgufenzy.top/Article/details/gtvttoykyk.html

(double) a / b
来源：http://dali.sysykeji.top/Article/details/gtjhypqwmy.html

[S16] C：位操作置位
来源：http://dali.xylfe.cn/Article/details/gtufcapckr.html

x |= (1 << 3);
来源：http://dali.aibaodan.cn/Article/details/gtfwcgxksh.html

[S17] C：安全拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gtjibkzzgq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hysaishi.cn/Article/details/gtakgacnsg.html

[S18] C：命令行参数
来源：http://dali.meibo888.top/Article/details/gtzebklspm.html

int main(int argc, char **argv)
来源：http://dali.xuanzx.com/Article/details/gtxkkfkxkq.html

[S19] C：快速排序
来源：http://dali.yj20258888.top/Article/details/gtoxcchgkb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ppjwa.cn/Article/details/gtvrsvaclm.html

[S20] C：二分查找
来源：http://dali.jqgufenzy.top/Article/details/gtxszwqaws.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yangfankeji.com/Article/details/gtgmewsoqh.html

[S21] C：字符类别判断
来源：http://dali.aizwys.cn/Article/details/gtfdttyxfu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj202588.top/Article/details/gtitgsrjag.html

[S22] C：字符串转数字
来源：http://dali.jqgufenzy.top/Article/details/gtroneveic.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhixingplan.top/Article/details/gtribcgqar.html

[S23] C：随机数
来源：http://dali.redwolf501.top/Article/details/gtrupkemmu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.quarkkingdee.top/Article/details/gtsowhxrfu.html

[S24] C：获取本地时间
来源：http://dali.jlsjyb.cn/Article/details/gtfnbdovqw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.fengsongda.top/Article/details/gtnmcvamsy.html

[S25] C：内存拷贝
来源：http://dali.kuanghao11.cn/Article/details/gtnkwddtjk.html

memcpy(dst, src, n);
来源：http://dali.cheryme.top/Article/details/gtfsrtaatu.html

[S26] C：内存清零
来源：http://dali.zhongyouzk.top/Article/details/gtwvhgmytv.html

memset(a, 0, sizeof a);
来源：http://dali.smart0.xyz/Article/details/gtgxvvbacy.html

[S27] C：定义常量
来源：http://dali.yuanzhike.top/Article/details/gtkvmjedle.html

const double PI = 3.14159;
来源：http://dali.xinyue.icu/Article/details/gtxlmfdtcf.html

[S28] C：静态变量
来源：http://dali.redwolf501.top/Article/details/gtqlbsonwg.html

static int counter = 0;
来源：http://dali.zhixingplan.top/Article/details/gtrfzlvhnw.html

[S29] C：变参函数
来源：http://dali.kuanghao11.cn/Article/details/gtiyeimwsu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.dashuyun.cn/Article/details/gthpgibzup.html

[S30] C：头文件保护
来源：http://dali.chenzaomai.com/Article/details/gtdaybscyo.html

#ifndef X_H
来源：http://dali.pengpengdd.cyou/Article/details/gttaqbnfnf.html

#define X_H
来源：http://dali.yj20258888.top/Article/details/gtzhrecily.html

#endif
来源：http://dali.c1oappe.top/Article/details/gtaseeyoqh.html

[S31] C++：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtcbjeoefq.html

#include <iostream>
来源：http://dali.chenzaomai.com/Article/details/gtcdkdqsii.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhongyouzk.top/Article/details/gtjuybscxr.html

[S32] C++：字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtqtxywhma.html

std::string s = "hi";  s += "!";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwgtaewmn.html

[S33] C++：vector 增删
来源：http://dali.ivvv.top/Article/details/gtvfszzdbe.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hysaishi.cn/Article/details/gtrvxgljzw.html

[S34] C++：遍历 vector
来源：http://dali.aibaodan.cn/Article/details/gtjbrhzkhn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xziqi.cn/Article/details/gtqgffqnvu.html

[S35] C++：map
来源：http://dali.pycfn.com/Article/details/gttxixpayu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daria6918.cn/Article/details/gthbxrzqld.html

[S36] C++：unordered_map
来源：http://dali.sysykeji.top/Article/details/gtyasaozaq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tanke756.top/Article/details/gtechyvwij.html

[S37] C++：set
来源：http://dali.yvedp.cn/Article/details/gtxdobqebe.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gaohongyu789.top/Article/details/gtbvmrlwpj.html

[S38] C++：排序
来源：http://dali.zhongyouzk.top/Article/details/gtpklbhura.html

std::sort(v.begin(), v.end());
来源：http://dali.zhoulong.xyz/Article/details/gtmibsafut.html

[S39] C++：自定义比较器排序
来源：http://dali.jqgfzy.top/Article/details/gtsapyceoj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.fengsongda.top/Article/details/gteaevhwiw.html

[S40] C++：查找元素
来源：http://dali.tianlin.xyz/Article/details/gtsebbrbpa.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.wangdashe.top/Article/details/gtybvostnd.html

[S41] C++：类与构造函数
来源：http://dali.jyoumei.cn/Article/details/gtbnrqbgxj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jiagoushi.top/Article/details/gtfdxiecwr.html

[S42] C++：继承与虚函数
来源：http://dali.yonumen.top/Article/details/gtprsaubgq.html

class B : public Base { public: void f() override {} };
来源：http://dali.shanyushiyangtech.top/Article/details/gtrilcqwbb.html

[S43] C++：智能指针
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzspwzfp.html

auto p = std::make_unique<int>(5);
来源：http://dali.quarkkingdee.top/Article/details/gtquljxwro.html

[S44] C++：引用传参
来源：http://dali.hysaishi.cn/Article/details/gtnmakckwi.html

void inc(int &x) { ++x; }
来源：http://dali.guannengcc.top/Article/details/gtoyeplaod.html

[S45] C++：lambda
来源：http://dali.ehwqpu.com/Article/details/gtbtwoeuqa.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cdnleiting.top/Article/details/gtbiboiflg.html

[S46] C++：函数模板
来源：http://dali.yangfankeji.com/Article/details/gtdiuutdbh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tianlin.xyz/Article/details/gtdwgrnirx.html

[S47] C++：结构化绑定遍历
来源：http://dali.gogol.net.cn/Article/details/gtkenbvmga.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.daxiang520.top/Article/details/gtboancuuw.html

[S48] C++：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtdcthhpsd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtafjrgvew.html

while (std::getline(in, line)) { }
来源：http://dali.xylfe.cn/Article/details/gtgunmmftr.html

[S49] C++：写文件
来源：http://dali.sxryk.cn/Article/details/gtazwbkghw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.dianchejie.cn/Article/details/gtgmwcgnmk.html

[S50] C++：格式化数字
来源：http://dali.zhongyouzk.top/Article/details/gtcvpydayb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gtxzqbdawj.html

[S51] C++：显式类型转换
来源：http://dali.vqdsnc.cn/Article/details/gtkwuhzqix.html

static_cast<double>(a) / b
来源：http://dali.tanke756.top/Article/details/gtmzgvepts.html

[S52] C++：const 与 noexcept
来源：http://dali.dianchejie.cn/Article/details/gtzpishdvj.html

int size() const noexcept { return n_; }
来源：http://dali.smart0.xyz/Article/details/gtqfprizsb.html

[S53] C++：移动语义
来源：http://dali.shzxlz.cn/Article/details/gtlolnkudp.html

std::vector<int> w = std::move(v);
来源：http://dali.xziqi.cn/Article/details/gtetzdumyw.html

[S54] C++：异常处理
来源：http://dali.bjfxy.top/Article/details/gtpyrysicl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xuanzx.com/Article/details/gtqemgtwmy.html

[S55] C++：结构化绑定
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuxrnnrwc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xuanzx.com/Article/details/gtdzttvztd.html

[S56] C++：optional
来源：http://dali.jyoumei.cn/Article/details/gtnptpurxf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jlsjyb.cn/Article/details/gtuwjvfyrj.html

[S57] C++：编译期常量
来源：http://dali.snrcjt.cn/Article/details/gtgdhiolzv.html

constexpr int N = 10;
来源：http://dali.cashguo.top/Article/details/gtxhtqvoem.html

[S58] C++：命名空间
来源：http://dali.yanxiufei.cn/Article/details/gtgsywhepe.html

namespace ns { int f() { return 1; } }
来源：http://dali.birdmap.top/Article/details/gthfrapkca.html

[S59] C++：静态断言
来源：http://dali.cheryme.top/Article/details/gtruhiczyz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xuanzx.com/Article/details/gtldkdwnca.html

[S60] C++：遍历并删除元素
来源：http://dali.daxiang520.top/Article/details/gthaojrzur.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cdnleiting.top/Article/details/gtzlhdhrhu.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtekfqeori.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenjidiqi.icu/Article/details/gthggxzqmf.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtnwgqkduk.html

[T01] Kotlin：Hello World
来源：http://dali.guannengcc.top/Article/details/gttsivnbeh.html

println("Hello")
来源：http://dali.pengpengdd.cyou/Article/details/gtaanzhmpk.html

[T02] Kotlin：变量
来源：http://dali.redwolf501.top/Article/details/gtjoocradh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.snrcjt.cn/Article/details/gtwoarifek.html

[T03] Kotlin：字符串模板
来源：http://dali.nwbrower.top/Article/details/gtzijbswwv.html

"值: $b"
来源：http://dali.hfpthk.cn/Article/details/gtckwmkvou.html

[T04] Kotlin：空安全
来源：http://dali.hysaishi.cn/Article/details/gtmriqtfec.html

val n: String? = null;  n?.length
来源：http://dali.xinyue.icu/Article/details/gtwddntmyh.html

[T05] Kotlin：when 表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtmkrzvgwk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.fzhhl.top/Article/details/gtlrgingws.html

[T06] Kotlin：集合映射
来源：http://dali.sysykeji.top/Article/details/gtzcqnguli.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yueranfly.top/Article/details/gtaiddnxqr.html

[T07] Kotlin：集合过滤
来源：http://dali.nanxuanxn.top/Article/details/gtnvkehsks.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yanxiufei.cn/Article/details/gtwdwmysnq.html

[T08] Kotlin：数据类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmdzlqsrw.html

data class User(val name: String, val age: Int)
来源：http://dali.ydzc1.top/Article/details/gtjnaqkeqg.html

[T09] Kotlin：扩展函数
来源：http://dali.pycfn.com/Article/details/gtsfbtxxiu.html

fun String.exclaim() = this + "!"
来源：http://dali.yj202588.top/Article/details/gtfdyxjhyp.html

[T10] Kotlin：默认参数
来源：http://dali.daxiang520.top/Article/details/gtycpphwhz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.dianchejie.cn/Article/details/gtcyemvzox.html

[T11] Kotlin：协程
来源：http://dali.yvedp.cn/Article/details/gthtnacnps.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhongyouzk.top/Article/details/gtyfifwrlm.html

[T12] Kotlin：解构声明
来源：http://dali.zhengqikj.top/Article/details/gtxjuvnytq.html

val (a, b) = Pair(1, 2)
来源：http://dali.iojbl.cn/Article/details/gtqhazlqgp.html

[T13] Kotlin：只读 Map
来源：http://dali.jiagoushi.top/Article/details/gtblfsjxxt.html

val m = mapOf("a" to 1)
来源：http://dali.aizwys.cn/Article/details/gttnfibcgf.html

[T14] Kotlin：循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwgcnycfm.html

for (i in 1..10) println(i)
来源：http://dali.sufxvd.cn/Article/details/gtylanobhx.html

[T15] Kotlin：接口
来源：http://dali.vqdsnc.cn/Article/details/gtnuyfcaai.html

interface Shape { fun area(): Double }
来源：http://dali.sufxvd.cn/Article/details/gtgmypjtpp.html

[T16] Swift：Hello World
来源：http://dali.tanke756.top/Article/details/gtswnueieu.html

print("Hello")
来源：http://dali.zycfv.cn/Article/details/gtqufphrbf.html

[T17] Swift：变量与常量
来源：http://dali.gotoacloud.top/Article/details/gtelylrjys.html

var a = 1;  let b = 2
来源：http://dali.bjfxy.top/Article/details/gtrkbeqble.html

[T18] Swift：字符串插值
来源：http://dali.tian-w.cn/Article/details/gtbkxbzgje.html

"值: \(b)"
来源：http://dali.yonumen.top/Article/details/gtaxzfukuz.html

[T19] Swift：可选绑定
来源：http://dali.yvedp.cn/Article/details/gtqcahkner.html

if let n = opt { print(n) }
来源：http://dali.yuanzhike.top/Article/details/gtvnrkgwaj.html

[T20] Swift：数组操作
来源：http://dali.shangyingyoupin.top/Article/details/gtcslyidym.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhoulong.xyz/Article/details/gtuhuoipbp.html

[T21] Swift：遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmwayrloe.html

for x in a { print(x) }
来源：http://dali.cqqwz.cn/Article/details/gtyewzpjgc.html

[T22] Swift：字典
来源：http://dali.chenlongwang.top/Article/details/gttnbwxiff.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hammf.cn/Article/details/gtctxpqgta.html

[T23] Swift：函数
来源：http://dali.aibaodan.cn/Article/details/gtfudbvawt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinghuilouyu.cn/Article/details/gttmexadpd.html

[T24] Swift：闭包
来源：http://dali.hnxiangtu.top/Article/details/gtvyrttkog.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yuanzhike.top/Article/details/gtimjhtbyw.html

[T25] Swift：结构体
来源：http://dali.yuxming.cn/Article/details/gtvxhkidsi.html

struct P { var x: Int }
来源：http://dali.yvedp.cn/Article/details/gtwadoymas.html

[T26] Swift：类与重写
来源：http://dali.hysaishi.cn/Article/details/gtptsnfkyg.html

class A: Base { override func f() {} }
来源：http://dali.ybcxt.top/Article/details/gtwninoqik.html

[T27] Swift：错误处理
来源：http://dali.jiagoushi.top/Article/details/gtibayqrrh.html

do { try f() } catch { print(error) }
来源：http://dali.vqdsnc.cn/Article/details/gtbivrmvob.html

[T28] Swift：枚举
来源：http://dali.c1oappe.top/Article/details/gtuvqdzimv.html

enum Color { case red, green }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgmnndhza.html

[T29] Swift：guard 提前返回
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmjsqdif.html

guard let x = opt else { return }
来源：http://dali.fzhhl.top/Article/details/gtiquwwmqd.html

[T30] Swift：协议
来源：http://dali.feifeiyinyue.top/Article/details/gtuustisjw.html

protocol Shape { func area() -> Double }
来源：http://dali.zhongyouzk.top/Article/details/gtzzyxcive.html

[T31] Lua：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzehskkki.html

print("Hello")
来源：http://dali.dashuyun.cn/Article/details/gtehdnepbq.html

[T32] Lua：局部变量
来源：http://dali.xziqi.cn/Article/details/gtstpwzavd.html

local a = 1
来源：http://dali.hammf.cn/Article/details/gtzbicfgvt.html

[T33] Lua：表（数组）
来源：http://dali.aibaodan.cn/Article/details/gtlnkwyifd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.iojbl.cn/Article/details/gtlmmkvlbu.html

[T34] Lua：遍历表
来源：http://dali.yanxiufei.cn/Article/details/gtjazgyshk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.smart0.xyz/Article/details/gtxvjfkoyn.html

[T35] Lua：字典表
来源：http://dali.haohaochexian.top/Article/details/gtyvditdgk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gzhubu.top/Article/details/gtdrrieqxr.html

[T36] Lua：函数
来源：http://dali.dianchejie.cn/Article/details/gtwlmqbzme.html

function add(a, b) return a + b end
来源：http://dali.sweek.top/Article/details/gtbgrcmjsn.html

[T37] Lua：字符串拼接
来源：http://dali.dianchejie.cn/Article/details/gtumqjrjdo.html

"a" .. "b"
来源：http://dali.jinghuilouyu.cn/Article/details/gtgghmcsas.html

[T38] Lua：条件
来源：http://dali.316326.xyz/Article/details/gtetfkjodg.html

if x > 0 then print("正") end
来源：http://dali.yanxiufei.cn/Article/details/gtlflxhvqa.html

[T39] Lua：模式匹配
来源：http://dali.chenzaomai.com/Article/details/gtqmhsizij.html

string.find(s, "%d+")
来源：http://dali.yongpay.top/Article/details/gtjnupvmfi.html

[T40] Lua：元表
来源：http://dali.tian-w.cn/Article/details/gtzqhvjcmm.html

setmetatable({}, { __index = base })
来源：http://dali.ydzc1.top/Article/details/gtfzktcgzc.html

[T41] Perl：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtrsmxnfyw.html

print "Hello\n";
来源：http://dali.hongshengwenyu.top/Article/details/gtrxzseaqw.html

[T42] Perl：变量类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtqfcpiavm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhixingplan.top/Article/details/gtjyhnqzks.html

[T43] Perl：字符串插值
来源：http://dali.vqdsnc.cn/Article/details/gtaufrlnpc.html

"值: $a"
来源：http://dali.wangshuangyany.cn/Article/details/gtzkxzwfpd.html

[T44] Perl：条件
来源：http://dali.9152youxi.cn/Article/details/gtcxcafafp.html

if ($a > 0) { print "正"; }
来源：http://dali.zhengqikj.top/Article/details/gtqhrxpgyu.html

[T45] Perl：数组遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtklfhdith.html

for my $x (@arr) { print $x; }
来源：http://dali.ydzc1.top/Article/details/gtnlsvgqdk.html

[T46] Perl：哈希操作
来源：http://dali.sxryk.cn/Article/details/gtpiqcutpw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.sxryk.cn/Article/details/gtspcrfyzi.html

[T47] Perl：正则捕获
来源：http://dali.zycfv.cn/Article/details/gtaajybmou.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cqqwz.cn/Article/details/gtejwbxfzt.html

[T48] Perl：正则替换
来源：http://dali.yuanzhike.top/Article/details/gtdjhalnmy.html

$s =~ s/old/new/g;
来源：http://dali.fengsongda.top/Article/details/gtdfephrfe.html

[T49] Perl：函数
来源：http://dali.jqgufenzy.top/Article/details/gtrfasenno.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gtcjagaxio.html

[T50] Perl：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gtewhzrujy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvqftmpt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.iojbl.cn/Article/details/gtthkywqqm.html

[T51] Scala：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtpjaytcyp.html

println("Hello")
来源：http://dali.cdnleiting.top/Article/details/gtlfuteyix.html

[T52] Scala：变量
来源：http://dali.sysykeji.top/Article/details/gtcjezdcwh.html

val a = 1;  var b = 2
来源：http://dali.yangfankeji.com/Article/details/gtvfyaeaic.html

[T53] Scala：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gtehysxpyu.html

s"值: $b"
来源：http://dali.jianghu66.top/Article/details/gtahwkdzug.html

[T54] Scala：集合映射
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjwsrefcg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhpboamg.html

[T55] Scala：集合过滤
来源：http://dali.yuanzhike.top/Article/details/gtcwvmojcw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.0kj1m.cn/Article/details/gtwrlkqjqk.html

[T56] Scala：样例类
来源：http://dali.daxiang520.top/Article/details/gtyauigckp.html

case class User(name: String, age: Int)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxmfpzyg.html

[T57] Scala：模式匹配
来源：http://dali.zhixingplan.top/Article/details/gtnomntczk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.iojbl.cn/Article/details/gtcepbcjbh.html

[T58] Scala：函数定义
来源：http://dali.yj202588.top/Article/details/gtmhbsnnfi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhengqikj.top/Article/details/gtoubllwio.html

[T59] Scala：循环
来源：http://dali.jqgufenzy.top/Article/details/gtedsvfgpn.html

for (i <- 1 to 10) println(i)
来源：http://dali.birdmap.top/Article/details/gtcamxlygx.html

[T60] Scala：折叠
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjzktjmr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.dianchejie.cn/Article/details/gtsbwlzcei.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtqsxemhcn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yj20258888.top/Article/details/gtpiqwtbpf.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtujdsdtra.html

[U01] Py：创建虚拟环境
来源：http://dali.cashguo.top/Article/details/gtloofdrlt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.havefunace.top/Article/details/gtbdstzesu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.pycfn.com/Article/details/gtlqclxrrj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cheryme.top/Article/details/gtrtghzcuj.html

[U03] Py：加载 .env 配置
来源：http://dali.sysykeji.top/Article/details/gtytwhotnz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.chenzaomai.com/Article/details/gtadkhmvlm.html

[U04] Py：变量调试打印
来源：http://dali.shanyushiyangtech.top/Article/details/gtynflmnho.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jianghu66.top/Article/details/gtfzmcgsqm.html

[U05] Py：列表去重且保序
来源：http://dali.hfpthk.cn/Article/details/gtdluwbyap.html

list(dict.fromkeys(arr))
来源：http://dali.wangdashe.top/Article/details/gtwosdkdiv.html

[U06] Py：合并两个字典
来源：http://dali.wangshuangyany.cn/Article/details/gtaiuqpzdy.html

{**a, **b}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgzqzkcon.html

[U07] Py：反转字典键值
来源：http://dali.zdqjudy.top/Article/details/gtosoqzsic.html

{v: k for k, v in d.items()}
来源：http://dali.pengpengdd.cyou/Article/details/gtkzxggfkx.html

[U08] Py：展平二维列表
来源：http://dali.jianghu66.top/Article/details/gtofeijjbu.html

[y for x in nested for y in x]
来源：http://dali.quarkkingdee.top/Article/details/gtkhbcjezb.html

[U09] Py：字典取最大值的键
来源：http://dali.zhixingplan.top/Article/details/gtavhpggnl.html

max(d, key=d.get)
来源：http://dali.xylfe.cn/Article/details/gtugldtlni.html

[U10] Py：按值排序字典
来源：http://dali.iojbl.cn/Article/details/gtqjgjrlsr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.316326.xyz/Article/details/gtsbpwuzmz.html


<!-- 参考信息 -->