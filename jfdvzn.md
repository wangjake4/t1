代发 wailian999

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenzaomai.com/Article/details/gtkwgdlyyp.html

[R76] 使用临时文件
来源：http://dali.zhoulong.xyz/Article/details/gtpkpyuybz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenjidiqi.icu/Article/details/gturtoxvvh.html

[R77] 读取用户输入
来源：http://dali.nanxuanxn.top/Article/details/gtwqihrsvs.html

read -rp "请输入: " ans
来源：http://dali.yj20258888.top/Article/details/gtaamongsr.html

[R78] 交互式菜单
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmdyvcftw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnzboftbw.html

[R79] 解析命令行选项
来源：http://dali.sweek.top/Article/details/gtxmmfbwzy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shuidangran.top/Article/details/gtjbbrnsjb.html

[R80] 查看脚本执行耗时
来源：http://dali.xuanzx.com/Article/details/gtcmubieuq.html

time ./run.sh
来源：http://dali.bjfxy.top/Article/details/gtzpihgxlt.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gttohsldcg.html

S. C / C++ 专题
来源：http://dali.xinyue.icu/Article/details/gtlxygwlba.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtnqvnembm.html

[S01] C：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdhglxuhd.html

#include <stdio.h>
来源：http://dali.dashuyun.cn/Article/details/gtveteshsv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhixingplan.top/Article/details/gtdaewdtio.html

[S02] C：变量与格式化输出
来源：http://dali.cheryme.top/Article/details/gtjwdbighi.html

int a = 10; printf("%d\n", a);
来源：http://dali.haohaochexian.top/Article/details/gtacnhvuxh.html

[S03] C：读入整数
来源：http://dali.nwbrower.top/Article/details/gtyjxsltxc.html

int x; scanf("%d", &x);
来源：http://dali.sweek.top/Article/details/gtzoxbyenx.html

[S04] C：字符串复制
来源：http://dali.tianlin.xyz/Article/details/gtxjbjaffq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hammf.cn/Article/details/gtkfqhaavj.html

[S05] C：字符串长度
来源：http://dali.zycfv.cn/Article/details/gtibpohksm.html

strlen(s)
来源：http://dali.ehwqpu.com/Article/details/gtpzdrnisc.html

[S06] C：字符串比较
来源：http://dali.hywenlv.cn/Article/details/gtgpjirmfr.html

strcmp(a, b) == 0
来源：http://dali.9152youxi.cn/Article/details/gtbhkbgtfg.html

[S07] C：数组遍历求和
来源：http://dali.shanyushiyangtech.top/Article/details/gtuferajnv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.quarkkingdee.top/Article/details/gthwrvnhaj.html

[S08] C：动态内存分配与释放
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmxsiuaek.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gogol.net.cn/Article/details/gtwdxdjgjg.html

[S09] C：结构体定义与初始化
来源：http://dali.wangdashe.top/Article/details/gtrnfihtvc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.meibo888.top/Article/details/gtwujnvnfz.html

[S10] C：指针与解引用
来源：http://dali.hywenlv.cn/Article/details/gtyqspbnes.html

int *p = &a;  *p = 5;
来源：http://dali.feifeiyinyue.top/Article/details/gtlcxzkshz.html

[S11] C：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gtaicyypqe.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinqigufen.top/Article/details/gtxlyazacq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.meibo888.top/Article/details/gthpncakmt.html

fclose(f);
来源：http://dali.zycfv.cn/Article/details/gtljkjskft.html

[S12] C：写文件
来源：http://dali.fzhhl.top/Article/details/gtaorzmvdk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hammf.cn/Article/details/gturaokshs.html

[S13] C：宏定义
来源：http://dali.meibo888.top/Article/details/gtkpaooiwg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jianghu66.top/Article/details/gtoyxgavow.html

[S14] C：枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzrttmaye.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.svipenyu.cn/Article/details/gtgzyqmged.html

[S15] C：类型转换
来源：http://dali.haohaochexian.top/Article/details/gtxtoxiyhd.html

(double) a / b
来源：http://dali.hysaishi.cn/Article/details/gtejgsqqiu.html

[S16] C：位操作置位
来源：http://dali.zhoulong.xyz/Article/details/gtrmuiabcy.html

x |= (1 << 3);
来源：http://dali.sxryk.cn/Article/details/gtfhjedirv.html

[S17] C：安全拼接字符串
来源：http://dali.sweek.top/Article/details/gttkguyyjk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sweek.top/Article/details/gtwrkbctjd.html

[S18] C：命令行参数
来源：http://dali.yj202588.top/Article/details/gtmqxkqgxh.html

int main(int argc, char **argv)
来源：http://dali.guannengcc.top/Article/details/gtwxnusara.html

[S19] C：快速排序
来源：http://dali.iojbl.cn/Article/details/gtjwnvuxma.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sufxvd.cn/Article/details/gtsnfonpsr.html

[S20] C：二分查找
来源：http://dali.tanke756.top/Article/details/gtvfkbmdlt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cheryme.top/Article/details/gtzqpzfpis.html

[S21] C：字符类别判断
来源：http://dali.sweek.top/Article/details/gthdfsamym.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.guowangkeji.top/Article/details/gtcuresayh.html

[S22] C：字符串转数字
来源：http://dali.chenlongwang.top/Article/details/gtyxfnodrk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj202588.top/Article/details/gtpkngcgwt.html

[S23] C：随机数
来源：http://dali.hnqzz.top/Article/details/gtwvnmpjru.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yvedp.cn/Article/details/gtubjkhlfs.html

[S24] C：获取本地时间
来源：http://dali.havefunace.top/Article/details/gtcpvjhpvj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hammf.cn/Article/details/gthhsczwun.html

[S25] C：内存拷贝
来源：http://dali.chenjidiqi.icu/Article/details/gtnriijwgr.html

memcpy(dst, src, n);
来源：http://dali.jinghuilouyu.cn/Article/details/gtqpphsjdo.html

[S26] C：内存清零
来源：http://dali.pengpengdd.cyou/Article/details/gtjcwufzkg.html

memset(a, 0, sizeof a);
来源：http://dali.9152youxi.cn/Article/details/gtodddsgyb.html

[S27] C：定义常量
来源：http://dali.0kj1m.cn/Article/details/gtmqwjvvsg.html

const double PI = 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gtzcafaupf.html

[S28] C：静态变量
来源：http://dali.guowangkeji.top/Article/details/gtxpnlwlql.html

static int counter = 0;
来源：http://dali.guowangkeji.top/Article/details/gthqvgolzq.html

[S29] C：变参函数
来源：http://dali.gaohongyu789.top/Article/details/gtdkwyswoa.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xinyue.icu/Article/details/gthusrarvi.html

[S30] C：头文件保护
来源：http://dali.xinyue.icu/Article/details/gthbhhtcxn.html

#ifndef X_H
来源：http://dali.shzxlz.cn/Article/details/gtssjqunzo.html

#define X_H
来源：http://dali.shangyingyoupin.top/Article/details/gtpydukmjx.html

#endif
来源：http://dali.nanxinkj.top/Article/details/gtjgpbyttk.html

[S31] C++：Hello World
来源：http://dali.shuidangran.top/Article/details/gtgiiulngi.html

#include <iostream>
来源：http://dali.jqgufenzy.top/Article/details/gtbslrifpo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttccbnupq.html

[S32] C++：字符串
来源：http://dali.tian-w.cn/Article/details/gtnfgxuiey.html

std::string s = "hi";  s += "!";
来源：http://dali.yongpay.top/Article/details/gtawpbhmdr.html

[S33] C++：vector 增删
来源：http://dali.hywenlv.cn/Article/details/gtjwviddwj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.316326.xyz/Article/details/gtewwlretv.html

[S34] C++：遍历 vector
来源：http://dali.vqdsnc.cn/Article/details/gtnyniciei.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hfpthk.cn/Article/details/gtonkkhltf.html

[S35] C++：map
来源：http://dali.yvedp.cn/Article/details/gtanrnvvtf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gtdyouxlzc.html

[S36] C++：unordered_map
来源：http://dali.yj20258888.top/Article/details/gtnhfeefyg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gtsmtslhsc.html

[S37] C++：set
来源：http://dali.0kj1m.cn/Article/details/gtkkayqwnn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.0kj1m.cn/Article/details/gtdrgdgkzm.html

[S38] C++：排序
来源：http://dali.yj20258.top/Article/details/gtkzmnwtuj.html

std::sort(v.begin(), v.end());
来源：http://dali.pycfn.com/Article/details/gtdypnungt.html

[S39] C++：自定义比较器排序
来源：http://dali.gzhubu.top/Article/details/gtsakfmdmm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yuxming.cn/Article/details/gtpfprswzg.html

[S40] C++：查找元素
来源：http://dali.9152youxi.cn/Article/details/gtmyhhqfjg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nwbrower.top/Article/details/gtomkroapf.html

[S41] C++：类与构造函数
来源：http://dali.hfpthk.cn/Article/details/gtysipxgrb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhoulong.xyz/Article/details/gtqlisgilx.html

[S42] C++：继承与虚函数
来源：http://dali.yj202588.top/Article/details/gtgzklszdp.html

class B : public Base { public: void f() override {} };
来源：http://dali.ybcxt.top/Article/details/gtpcmwspvt.html

[S43] C++：智能指针
来源：http://dali.meibo888.top/Article/details/gtydzgqthg.html

auto p = std::make_unique<int>(5);
来源：http://dali.jianghu66.top/Article/details/gtaqsjmgym.html

[S44] C++：引用传参
来源：http://dali.shanyushiyangtech.top/Article/details/gtpcbdrizq.html

void inc(int &x) { ++x; }
来源：http://dali.gaohongyu789.top/Article/details/gtmdkrwiyo.html

[S45] C++：lambda
来源：http://dali.jianghu66.top/Article/details/gtxwomhign.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.redwolf501.top/Article/details/gtmcedvwxe.html

[S46] C++：函数模板
来源：http://dali.daria6918.cn/Article/details/gtaoaqnzwe.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtpffirstl.html

[S47] C++：结构化绑定遍历
来源：http://dali.cucudq.cn/Article/details/gtwwdtllkl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xuetiantiany.cn/Article/details/gtkpnphskn.html

[S48] C++：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtviquatxo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.316326.xyz/Article/details/gtkgacizsl.html

while (std::getline(in, line)) { }
来源：http://dali.zycfv.cn/Article/details/gtiqoyjbdw.html

[S49] C++：写文件
来源：http://dali.ybcxt.top/Article/details/gttbdobrsz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.chenzaomai.com/Article/details/gtysrzbdht.html

[S50] C++：格式化数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnjjjpktg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gtcegaxmwi.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gtdohwtuhl.html

static_cast<double>(a) / b
来源：http://dali.zycfv.cn/Article/details/gthbrrnwtz.html

[S52] C++：const 与 noexcept
来源：http://dali.meibo888.top/Article/details/gtvsmbgtxu.html

int size() const noexcept { return n_; }
来源：http://dali.yueranfly.top/Article/details/gtytgxgjjw.html

[S53] C++：移动语义
来源：http://dali.yuanzhike.top/Article/details/gtwigotbyr.html

std::vector<int> w = std::move(v);
来源：http://dali.iojbl.cn/Article/details/gtakcyzsfk.html

[S54] C++：异常处理
来源：http://dali.guannengcc.top/Article/details/gtsatpmtzl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hywenlv.cn/Article/details/gttivkinnr.html

[S55] C++：结构化绑定
来源：http://dali.jiagoushi.top/Article/details/gthavkohlj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtxnrnckai.html

[S56] C++：optional
来源：http://dali.c1oappe.top/Article/details/gtwakebuvi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.vqdsnc.cn/Article/details/gtfveurebh.html

[S57] C++：编译期常量
来源：http://dali.zycfv.cn/Article/details/gtejzmivmu.html

constexpr int N = 10;
来源：http://dali.zhixingplan.top/Article/details/gtlfokumfy.html

[S58] C++：命名空间
来源：http://dali.svipenyu.cn/Article/details/gtzcrlgobd.html

namespace ns { int f() { return 1; } }
来源：http://dali.hywenlv.cn/Article/details/gtvyfndmdm.html

[S59] C++：静态断言
来源：http://dali.ppjwa.cn/Article/details/gtrwmtwslm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.haohaochexian.top/Article/details/gtlvpdqsrb.html

[S60] C++：遍历并删除元素
来源：http://dali.hnqzz.top/Article/details/gtsjgexpku.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthcrlcgbw.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtvonhkypz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jqgufenzy.top/Article/details/gtsxvuuwts.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtrkdidnud.html

[T01] Kotlin：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtcfdeqdwe.html

println("Hello")
来源：http://dali.jinqigufen.top/Article/details/gtmofnsodw.html

[T02] Kotlin：变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwcjxudvq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gzhubu.top/Article/details/gtdvhottzd.html

[T03] Kotlin：字符串模板
来源：http://dali.fengsongda.top/Article/details/gtdildmavl.html

"值: $b"
来源：http://dali.jinghuilouyu.cn/Article/details/gtfqvhxvze.html

[T04] Kotlin：空安全
来源：http://dali.ehwqpu.com/Article/details/gtiedhjirl.html

val n: String? = null;  n?.length
来源：http://dali.cdnleiting.top/Article/details/gtcjnyummk.html

[T05] Kotlin：when 表达式
来源：http://dali.shangyingyoupin.top/Article/details/gtixjktvpb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jqgfzy.top/Article/details/gtfazwkzja.html

[T06] Kotlin：集合映射
来源：http://dali.dashuyun.cn/Article/details/gtsztdgnen.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.pycfn.com/Article/details/gtxuzkbazm.html

[T07] Kotlin：集合过滤
来源：http://dali.pycfn.com/Article/details/gtvffozzrp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxoynurp.html

[T08] Kotlin：数据类
来源：http://dali.cheryme.top/Article/details/gtahidsogx.html

data class User(val name: String, val age: Int)
来源：http://dali.hysaishi.cn/Article/details/gtqrorilbh.html

[T09] Kotlin：扩展函数
来源：http://dali.xylfe.cn/Article/details/gtzswuytfc.html

fun String.exclaim() = this + "!"
来源：http://dali.nanxinkj.top/Article/details/gtqzbikavy.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gtuurdcaxf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.kuanghao11.cn/Article/details/gtjyydneod.html

[T11] Kotlin：协程
来源：http://dali.xziqi.cn/Article/details/gtuosszxbs.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.feifeiyinyue.top/Article/details/gtzqttutfv.html

[T12] Kotlin：解构声明
来源：http://dali.havefunace.top/Article/details/gtazwxwsmx.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtkhtnurqz.html

[T13] Kotlin：只读 Map
来源：http://dali.yueranfly.top/Article/details/gtssckoayw.html

val m = mapOf("a" to 1)
来源：http://dali.cheryme.top/Article/details/gtnourthds.html

[T14] Kotlin：循环
来源：http://dali.dashuyun.cn/Article/details/gtkobfvvjt.html

for (i in 1..10) println(i)
来源：http://dali.feifeiyinyue.top/Article/details/gtxotnhrfm.html

[T15] Kotlin：接口
来源：http://dali.haohaochexian.top/Article/details/gtgxqmbdoe.html

interface Shape { fun area(): Double }
来源：http://dali.sysykeji.top/Article/details/gtflooawxp.html

[T16] Swift：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtccaudeoj.html

print("Hello")
来源：http://dali.zhengqikj.top/Article/details/gtjeappgok.html

[T17] Swift：变量与常量
来源：http://dali.shuidangran.top/Article/details/gtmyuurvtx.html

var a = 1;  let b = 2
来源：http://dali.cdnleiting.top/Article/details/gtileihcpl.html

[T18] Swift：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gtwgiyfrgy.html

"值: \(b)"
来源：http://dali.fzhhl.top/Article/details/gtxjtgqpze.html

[T19] Swift：可选绑定
来源：http://dali.chenlongwang.top/Article/details/gtgklwgwyo.html

if let n = opt { print(n) }
来源：http://dali.jqgfzy.top/Article/details/gtjcyklrrd.html

[T20] Swift：数组操作
来源：http://dali.svipenyu.cn/Article/details/gtforcwjol.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj202588.top/Article/details/gtdiywbjth.html

[T21] Swift：遍历
来源：http://dali.shzxlz.cn/Article/details/gtdnctuixr.html

for x in a { print(x) }
来源：http://dali.fengsongda.top/Article/details/gtigrnyoea.html

[T22] Swift：字典
来源：http://dali.hnxiangtu.top/Article/details/gthnjyifsx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yonumen.top/Article/details/gtqcsbnfbd.html

[T23] Swift：函数
来源：http://dali.316326.xyz/Article/details/gtvwwaikcb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.snrcjt.cn/Article/details/gtjemhcisl.html

[T24] Swift：闭包
来源：http://dali.guannengcc.top/Article/details/gtynfeqvbd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jiagoushi.top/Article/details/gtzjukajwm.html

[T25] Swift：结构体
来源：http://dali.vqdsnc.cn/Article/details/gtwuetesrw.html

struct P { var x: Int }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwmjjtbrl.html

[T26] Swift：类与重写
来源：http://dali.shzxlz.cn/Article/details/gtastvpekq.html

class A: Base { override func f() {} }
来源：http://dali.zdqjudy.top/Article/details/gtjeqkpxsq.html

[T27] Swift：错误处理
来源：http://dali.yj20258888.top/Article/details/gtcmerguzc.html

do { try f() } catch { print(error) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrwvjdbes.html

[T28] Swift：枚举
来源：http://dali.pengpengdd.cyou/Article/details/gtvitsvohb.html

enum Color { case red, green }
来源：http://dali.9152youxi.cn/Article/details/gtnhkcatxh.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gtrezbfkhb.html

guard let x = opt else { return }
来源：http://dali.yangfankeji.com/Article/details/gtfgulhczt.html

[T30] Swift：协议
来源：http://dali.pengpengdd.cyou/Article/details/gtkljgcuwd.html

protocol Shape { func area() -> Double }
来源：http://dali.jinghuilouyu.cn/Article/details/gtimsmhvhx.html

[T31] Lua：Hello World
来源：http://dali.cashguo.top/Article/details/gtrslrfozc.html

print("Hello")
来源：http://dali.meibo888.top/Article/details/gtethnzenu.html

[T32] Lua：局部变量
来源：http://dali.birdmap.top/Article/details/gthgqggeqb.html

local a = 1
来源：http://dali.kuanghao11.cn/Article/details/gtozubkqyy.html

[T33] Lua：表（数组）
来源：http://dali.gotoacloud.top/Article/details/gtdmmnxcgd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jiagoushi.top/Article/details/gtujwjjrrz.html

[T34] Lua：遍历表
来源：http://dali.ydzc1.top/Article/details/gtwyelenmp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sufxvd.cn/Article/details/gtgnqoulov.html

[T35] Lua：字典表
来源：http://dali.cheryme.top/Article/details/gtqfjxfrwu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.nanxuanxn.top/Article/details/gtvckrlikz.html

[T36] Lua：函数
来源：http://dali.haohaochexian.top/Article/details/gtaergyhas.html

function add(a, b) return a + b end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtorbparoo.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gtwshafqwf.html

"a" .. "b"
来源：http://dali.316326.xyz/Article/details/gtzhdhqajx.html

[T38] Lua：条件
来源：http://dali.vqdsnc.cn/Article/details/gtazsgqnqr.html

if x > 0 then print("正") end
来源：http://dali.havefunace.top/Article/details/gtbckyqrdq.html

[T39] Lua：模式匹配
来源：http://dali.chenzaomai.com/Article/details/gtromtnrgp.html

string.find(s, "%d+")
来源：http://dali.xylfe.cn/Article/details/gtuilouwdc.html

[T40] Lua：元表
来源：http://dali.xziqi.cn/Article/details/gttsqbtets.html

setmetatable({}, { __index = base })
来源：http://dali.yj20258.top/Article/details/gtrxmawgtu.html

[T41] Perl：Hello World
来源：http://dali.fzhhl.top/Article/details/gtpgefmmpu.html

print "Hello\n";
来源：http://dali.yj20258.top/Article/details/gtjlodrsty.html

[T42] Perl：变量类型
来源：http://dali.shuidangran.top/Article/details/gtvhpuymoz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xylfe.cn/Article/details/gtuywaalty.html

[T43] Perl：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gtedsgilqy.html

"值: $a"
来源：http://dali.guowangkeji.top/Article/details/gtlfaklugp.html

[T44] Perl：条件
来源：http://dali.yuanzhike.top/Article/details/gtqwntfzxi.html

if ($a > 0) { print "正"; }
来源：http://dali.xylfe.cn/Article/details/gtbjqxhxkv.html

[T45] Perl：数组遍历
来源：http://dali.gogol.net.cn/Article/details/gtwbokinnw.html

for my $x (@arr) { print $x; }
来源：http://dali.dianchejie.cn/Article/details/gtxhzweqfh.html

[T46] Perl：哈希操作
来源：http://dali.yueranfly.top/Article/details/gtogbrxyiu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.iojbl.cn/Article/details/gtpkokxngt.html

[T47] Perl：正则捕获
来源：http://dali.xziqi.cn/Article/details/gtdzdxttnc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yj20258888.top/Article/details/gtotnfykmt.html

[T48] Perl：正则替换
来源：http://dali.chenjidiqi.icu/Article/details/gtwvcemtot.html

$s =~ s/old/new/g;
来源：http://dali.shanyushiyangtech.top/Article/details/gtrycyhhnb.html

[T49] Perl：函数
来源：http://dali.jianghu66.top/Article/details/gtwukqqhhn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtabmnqsar.html

[T50] Perl：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtedxvmady.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.fengsongda.top/Article/details/gteurhcget.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.fzhhl.top/Article/details/gtgufrakve.html

[T51] Scala：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtauwpmmon.html

println("Hello")
来源：http://dali.yj20258888.top/Article/details/gtfsjgncvd.html

[T52] Scala：变量
来源：http://dali.jianghu66.top/Article/details/gthueedpop.html

val a = 1;  var b = 2
来源：http://dali.shangyingyoupin.top/Article/details/gtrysvphjz.html

[T53] Scala：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gttmgtdlek.html

s"值: $b"
来源：http://dali.jqgfzy.top/Article/details/gtprqiuogw.html

[T54] Scala：集合映射
来源：http://dali.yueranfly.top/Article/details/gtjjxlihrx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shzxlz.cn/Article/details/gtcmasxynn.html

[T55] Scala：集合过滤
来源：http://dali.gogol.net.cn/Article/details/gtuwajkptw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yvedp.cn/Article/details/gtbhuctxme.html

[T56] Scala：样例类
来源：http://dali.pengpengdd.cyou/Article/details/gtbaytqltv.html

case class User(name: String, age: Int)
来源：http://dali.yvedp.cn/Article/details/gtekkucqpl.html

[T57] Scala：模式匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtdhcrspkk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xuanzx.com/Article/details/gtqqrkqtpw.html

[T58] Scala：函数定义
来源：http://dali.iojbl.cn/Article/details/gtsfcugnzf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.0kj1m.cn/Article/details/gtopuwmxgp.html

[T59] Scala：循环
来源：http://dali.jqgufenzy.top/Article/details/gttkdigvnl.html

for (i <- 1 to 10) println(i)
来源：http://dali.chenlongwang.top/Article/details/gtaljcumcq.html

[T60] Scala：折叠
来源：http://dali.redwolf501.top/Article/details/gtdfwfegjk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.snrcjt.cn/Article/details/gtvzytpwrd.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtjgpahses.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hnqzz.top/Article/details/gtwuiverbz.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtghnoazdl.html

[U01] Py：创建虚拟环境
来源：http://dali.hnxiangtu.top/Article/details/gtsdrozquy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxhmcqneq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhiwuduotai.top/Article/details/gthouxdboa.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.c1oappe.top/Article/details/gtzozpcibv.html

[U03] Py：加载 .env 配置
来源：http://dali.hywenlv.cn/Article/details/gtygrjrxwc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.wangshuangyany.cn/Article/details/gtbtdhwbqn.html

[U04] Py：变量调试打印
来源：http://dali.feifeiyinyue.top/Article/details/gtdllzrlpz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhongyouzk.top/Article/details/gtzufdoyhd.html

[U05] Py：列表去重且保序
来源：http://dali.iojbl.cn/Article/details/gthtzuqwpd.html

list(dict.fromkeys(arr))
来源：http://dali.iojbl.cn/Article/details/gtsbhrbhof.html

[U06] Py：合并两个字典
来源：http://dali.fzhhl.top/Article/details/gtqzadajzi.html

{**a, **b}
来源：http://dali.sufxvd.cn/Article/details/gtmrxiftap.html

[U07] Py：反转字典键值
来源：http://dali.daria6918.cn/Article/details/gttdmoqsjn.html

{v: k for k, v in d.items()}
来源：http://dali.gogol.net.cn/Article/details/gtrgtiytuz.html

[U08] Py：展平二维列表
来源：http://dali.guannengcc.top/Article/details/gtskrgerkl.html

[y for x in nested for y in x]
来源：http://dali.wangshuangyany.cn/Article/details/gtuhrttcla.html

[U09] Py：字典取最大值的键
来源：http://dali.dianchejie.cn/Article/details/gtmkeqnlqf.html

max(d, key=d.get)
来源：http://dali.aizwys.cn/Article/details/gtqfegfora.html

[U10] Py：按值排序字典
来源：http://dali.jqgfzy.top/Article/details/gtvaaoztes.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.chenjidiqi.icu/Article/details/gttvrmrqcz.html

[U11] Py：生成器表达式
来源：http://dali.xuanzx.com/Article/details/gtrblkcpjd.html

(x * 2 for x in arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdvasqdjm.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.tianlin.xyz/Article/details/gtayzwrjfo.html

Counter(arr).most_common(3)
来源：http://dali.jlsjyb.cn/Article/details/gtaqgystos.html

[U13] Py：固定长度队列
来源：http://dali.shzxlz.cn/Article/details/gtrohbzatp.html

deque(maxlen=10)
来源：http://dali.redwolf501.top/Article/details/gthgxtrunl.html

[U14] Py：分组收集到列表
来源：http://dali.chenlongwang.top/Article/details/gtgxkldcgs.html

defaultdict(list)
来源：http://dali.daxiang520.top/Article/details/gtsybtvtjy.html

[U15] Py：高精度计时
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlmsfgmhd.html

t = time.perf_counter()
来源：http://dali.fzhhl.top/Article/details/gtfqtmbkcq.html

[U16] Py：命令行参数解析
来源：http://dali.chenjidiqi.icu/Article/details/gtesimzxrx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zycfv.cn/Article/details/gtqpvomvzu.html


<!-- 参考信息 -->