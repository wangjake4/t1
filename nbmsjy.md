代发 wailian999

openssl rand -hex 16
来源：http://dali.gogol.net.cn/Article/details/gtbcjfnbns.html

[R68] 计算文件校验值
来源：http://dali.hywenlv.cn/Article/details/gtnmecxhel.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xziqi.cn/Article/details/gtydhavblj.html

[R69] 生成随机密码
来源：http://dali.xinyue.icu/Article/details/gtxkacsexw.html

head -c 16 /dev/urandom | base64
来源：http://dali.aibaodan.cn/Article/details/gthjzofbwb.html

[R70] 时间戳与互转
来源：http://dali.xziqi.cn/Article/details/gtpamxcdio.html

date +%s;  date -d @1700000000
来源：http://dali.daria6918.cn/Article/details/gtvjsxcrla.html

[R71] 日期格式化
来源：http://dali.zdqjudy.top/Article/details/gtjoifvhjf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zycfv.cn/Article/details/gtlxbfchsb.html

[R72] 等待端口就绪
来源：http://dali.yongpay.top/Article/details/gtatpfusdf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hfpthk.cn/Article/details/gtoaepwlxo.html

[R73] 分割大日志
来源：http://dali.chenzaomai.com/Article/details/gtspzqthzr.html

split -l 1000 big.log part_
来源：http://dali.zhiwuduotai.top/Article/details/gtucqrnuug.html

[R74] 批量重命名
来源：http://dali.shuidangran.top/Article/details/gtootayfwm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tanke756.top/Article/details/gtzpermhju.html

[R75] 导出环境变量
来源：http://dali.daria6918.cn/Article/details/gtqhjedasq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hysaishi.cn/Article/details/gtegpottrn.html

[R76] 使用临时文件
来源：http://dali.guannengcc.top/Article/details/gtwguvbdoz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhiwuduotai.top/Article/details/gtypwmjtyc.html

[R77] 读取用户输入
来源：http://dali.shanyushiyangtech.top/Article/details/gterotufvt.html

read -rp "请输入: " ans
来源：http://dali.hfpthk.cn/Article/details/gtonvvmary.html

[R78] 交互式菜单
来源：http://dali.jinqigufen.top/Article/details/gtmgzqxrlu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhoulong.xyz/Article/details/gtcdnxmyoe.html

[R79] 解析命令行选项
来源：http://dali.gotoacloud.top/Article/details/gtlkcpqqdn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.aibaodan.cn/Article/details/gtzmusygmi.html

[R80] 查看脚本执行耗时
来源：http://dali.shuidangran.top/Article/details/gtbbedxsmw.html

time ./run.sh
来源：http://dali.316326.xyz/Article/details/gtoxjymvlu.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gttelhmovo.html

S. C / C++ 专题
来源：http://dali.bjfxy.top/Article/details/gtouwighrx.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtogmeibhr.html

[S01] C：Hello World
来源：http://dali.sxryk.cn/Article/details/gtjvhbgawm.html

#include <stdio.h>
来源：http://dali.xziqi.cn/Article/details/gthvihnnmg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthaddvgbi.html

[S02] C：变量与格式化输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtyoyyveqb.html

int a = 10; printf("%d\n", a);
来源：http://dali.feifeiyinyue.top/Article/details/gtfdbatcta.html

[S03] C：读入整数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdfwewcky.html

int x; scanf("%d", &x);
来源：http://dali.chenlongwang.top/Article/details/gtmnfvvtop.html

[S04] C：字符串复制
来源：http://dali.hongshengwenyu.top/Article/details/gtdqciiuxd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jqgufenzy.top/Article/details/gtxhqlcsjq.html

[S05] C：字符串长度
来源：http://dali.yuanzhike.top/Article/details/gthdslshqs.html

strlen(s)
来源：http://dali.meibo888.top/Article/details/gtlkyaunqb.html

[S06] C：字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gtvbaivoza.html

strcmp(a, b) == 0
来源：http://dali.zhoulong.xyz/Article/details/gteqjtamun.html

[S07] C：数组遍历求和
来源：http://dali.9152youxi.cn/Article/details/gtupvxcjql.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.feifeiyinyue.top/Article/details/gtbxvunpak.html

[S08] C：动态内存分配与释放
来源：http://dali.zycfv.cn/Article/details/gthkgsqhps.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ivvv.top/Article/details/gtvyhawcvw.html

[S09] C：结构体定义与初始化
来源：http://dali.yongpay.top/Article/details/gtnrqdrlwn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.andypj.xyz/Article/details/gtlnitfysv.html

[S10] C：指针与解引用
来源：http://dali.sxryk.cn/Article/details/gthvjizogn.html

int *p = &a;  *p = 5;
来源：http://dali.dashuyun.cn/Article/details/gtddyqmtdb.html

[S11] C：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtcriijoph.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jyoumei.cn/Article/details/gtdymumeup.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gzhubu.top/Article/details/gttefvuxkk.html

fclose(f);
来源：http://dali.gogol.net.cn/Article/details/gtgthodwcq.html

[S12] C：写文件
来源：http://dali.zycfv.cn/Article/details/gtnvvrydsw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.mhx1999.top/Article/details/gtxngsqdlx.html

[S13] C：宏定义
来源：http://dali.hfpthk.cn/Article/details/gtpvxkbipr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj20258888.top/Article/details/gtiwryolib.html

[S14] C：枚举
来源：http://dali.iojbl.cn/Article/details/gtpontrzxp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yueranfly.top/Article/details/gtmeqdhikd.html

[S15] C：类型转换
来源：http://dali.yanxiufei.cn/Article/details/gtsyfangvx.html

(double) a / b
来源：http://dali.zhongyouzk.top/Article/details/gtuobgkxvp.html

[S16] C：位操作置位
来源：http://dali.nanxinkj.top/Article/details/gtqdibzpkk.html

x |= (1 << 3);
来源：http://dali.zhixingplan.top/Article/details/gthtxnaxqr.html

[S17] C：安全拼接字符串
来源：http://dali.ydzc1.top/Article/details/gtwqfnxrdn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.aizwys.cn/Article/details/gtyjczelxh.html

[S18] C：命令行参数
来源：http://dali.jqgufenzy.top/Article/details/gtvafkckip.html

int main(int argc, char **argv)
来源：http://dali.xylfe.cn/Article/details/gtphsctkyr.html

[S19] C：快速排序
来源：http://dali.xinyue.icu/Article/details/gtrpqozsvu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.kuanghao11.cn/Article/details/gtnkezshbp.html

[S20] C：二分查找
来源：http://dali.nwbrower.top/Article/details/gtvdpflevp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.daria6918.cn/Article/details/gtpihjskos.html

[S21] C：字符类别判断
来源：http://dali.hywenlv.cn/Article/details/gtzbbcaexr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yvedp.cn/Article/details/gtgequzqqr.html

[S22] C：字符串转数字
来源：http://dali.xinyue.icu/Article/details/gtsprjiqck.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.redwolf501.top/Article/details/gtqgowgxsv.html

[S23] C：随机数
来源：http://dali.yj20258888.top/Article/details/gtadwoqint.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xinyue.icu/Article/details/gtmmgjmohj.html

[S24] C：获取本地时间
来源：http://dali.pengpengdd.cyou/Article/details/gtsnzzwfdp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.andypj.xyz/Article/details/gtumpchbqo.html

[S25] C：内存拷贝
来源：http://dali.sufxvd.cn/Article/details/gtdtmtispf.html

memcpy(dst, src, n);
来源：http://dali.zhoulong.xyz/Article/details/gtwidwtevj.html

[S26] C：内存清零
来源：http://dali.tianlin.xyz/Article/details/gtosgwbdiw.html

memset(a, 0, sizeof a);
来源：http://dali.yangfankeji.com/Article/details/gtldtgiaqn.html

[S27] C：定义常量
来源：http://dali.jlsjyb.cn/Article/details/gttaulvxup.html

const double PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtiaooxkct.html

[S28] C：静态变量
来源：http://dali.zdqjudy.top/Article/details/gtzrojnbgl.html

static int counter = 0;
来源：http://dali.vqdsnc.cn/Article/details/gtlmfkruuv.html

[S29] C：变参函数
来源：http://dali.hysaishi.cn/Article/details/gtqudvrfwf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gtaxtfayzh.html

[S30] C：头文件保护
来源：http://dali.ydzc1.top/Article/details/gtwnqvvfpl.html

#ifndef X_H
来源：http://dali.jinqigufen.top/Article/details/gtsjjgnukm.html

#define X_H
来源：http://dali.hysaishi.cn/Article/details/gtniorkqed.html

#endif
来源：http://dali.xziqi.cn/Article/details/gtdcqabqka.html

[S31] C++：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtloigwogb.html

#include <iostream>
来源：http://dali.quarkkingdee.top/Article/details/gttfmxzoju.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.iojbl.cn/Article/details/gtgcqjjlpk.html

[S32] C++：字符串
来源：http://dali.tanke756.top/Article/details/gtkvlntodm.html

std::string s = "hi";  s += "!";
来源：http://dali.shangyingyoupin.top/Article/details/gtciwobqly.html

[S33] C++：vector 增删
来源：http://dali.meibo888.top/Article/details/gtrntfetkp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.kuanghao11.cn/Article/details/gtjbdooywg.html

[S34] C++：遍历 vector
来源：http://dali.yuxming.cn/Article/details/gtexfkucyh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sxryk.cn/Article/details/gtfeyzzagc.html

[S35] C++：map
来源：http://dali.zhixingplan.top/Article/details/gtvnngnhud.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gtkogtifcx.html

[S36] C++：unordered_map
来源：http://dali.316326.xyz/Article/details/gtyrxnulhl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gzhubu.top/Article/details/gtewworcmn.html

[S37] C++：set
来源：http://dali.birdmap.top/Article/details/gtnfupyyyw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.iojbl.cn/Article/details/gtkudyhcok.html

[S38] C++：排序
来源：http://dali.haohaochexian.top/Article/details/gtdmcwyfrm.html

std::sort(v.begin(), v.end());
来源：http://dali.chenlongwang.top/Article/details/gtvjzmhqfl.html

[S39] C++：自定义比较器排序
来源：http://dali.yangfankeji.com/Article/details/gtlnevqvmg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfmdzlrxn.html

[S40] C++：查找元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpdipxnee.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttyelmugt.html

[S41] C++：类与构造函数
来源：http://dali.ehwqpu.com/Article/details/gtvsdfjadd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhixingplan.top/Article/details/gtjmfsfinj.html

[S42] C++：继承与虚函数
来源：http://dali.zhongyouzk.top/Article/details/gtkfyspyql.html

class B : public Base { public: void f() override {} };
来源：http://dali.redwolf501.top/Article/details/gtmcufadmz.html

[S43] C++：智能指针
来源：http://dali.jiagoushi.top/Article/details/gttlvmgzhj.html

auto p = std::make_unique<int>(5);
来源：http://dali.aizwys.cn/Article/details/gtcqmhxjou.html

[S44] C++：引用传参
来源：http://dali.aibaodan.cn/Article/details/gtjkfztftj.html

void inc(int &x) { ++x; }
来源：http://dali.yj20258888.top/Article/details/gtnlubagtc.html

[S45] C++：lambda
来源：http://dali.zdqjudy.top/Article/details/gtghncmywq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj20258888.top/Article/details/gtsaqealsm.html

[S46] C++：函数模板
来源：http://dali.bjfxy.top/Article/details/gtcsegvdeb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinqigfzy.top/Article/details/gtqdxpaugq.html

[S47] C++：结构化绑定遍历
来源：http://dali.hfpthk.cn/Article/details/gtlqsvzdal.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.meibo888.top/Article/details/gtyuexrdcf.html

[S48] C++：逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gtyjopeour.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jyoumei.cn/Article/details/gtbocmvvjk.html

while (std::getline(in, line)) { }
来源：http://dali.yanxiufei.cn/Article/details/gtgmifutea.html

[S49] C++：写文件
来源：http://dali.cucudq.cn/Article/details/gtrmnbtqld.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.aibaodan.cn/Article/details/gtlfvcpelf.html

[S50] C++：格式化数字
来源：http://dali.cashguo.top/Article/details/gtxeaackex.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cashguo.top/Article/details/gtfgmimswh.html

[S51] C++：显式类型转换
来源：http://dali.yuanzhike.top/Article/details/gtbxsdkiof.html

static_cast<double>(a) / b
来源：http://dali.havefunace.top/Article/details/gtnxlntisg.html

[S52] C++：const 与 noexcept
来源：http://dali.tianlin.xyz/Article/details/gtmumwwuoc.html

int size() const noexcept { return n_; }
来源：http://dali.chenjidiqi.icu/Article/details/gtujeslczp.html

[S53] C++：移动语义
来源：http://dali.nanxinkj.top/Article/details/gtrxiagncf.html

std::vector<int> w = std::move(v);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejaifkgf.html

[S54] C++：异常处理
来源：http://dali.jqgufenzy.top/Article/details/gtvfyfewpt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jlsjyb.cn/Article/details/gtutwerdos.html

[S55] C++：结构化绑定
来源：http://dali.nanxuanxn.top/Article/details/gtnxyuopuf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ehwqpu.com/Article/details/gtpaojuvor.html

[S56] C++：optional
来源：http://dali.nanxuanxn.top/Article/details/gtmbodwpwn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hywenlv.cn/Article/details/gtpglewxrj.html

[S57] C++：编译期常量
来源：http://dali.aibaodan.cn/Article/details/gtjhcvoyjs.html

constexpr int N = 10;
来源：http://dali.cucudq.cn/Article/details/gtbwlzqimk.html

[S58] C++：命名空间
来源：http://dali.yuanzhike.top/Article/details/gtnzzfqxzp.html

namespace ns { int f() { return 1; } }
来源：http://dali.gogol.net.cn/Article/details/gtaaipxqxm.html

[S59] C++：静态断言
来源：http://dali.ppjwa.cn/Article/details/gtyviqanen.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhengqikj.top/Article/details/gtrtcsyicg.html

[S60] C++：遍历并删除元素
来源：http://dali.feifeiyinyue.top/Article/details/gtkibyfqhn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.quarkkingdee.top/Article/details/gtklxmdvth.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtywbxvnug.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.smart0.xyz/Article/details/gtnpsaxudw.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtlzsiekcy.html

[T01] Kotlin：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtihsdwexf.html

println("Hello")
来源：http://dali.meibo888.top/Article/details/gthavzldxq.html

[T02] Kotlin：变量
来源：http://dali.316326.xyz/Article/details/gtymlsjnsi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.meibo888.top/Article/details/gthizlkuss.html

[T03] Kotlin：字符串模板
来源：http://dali.ehwqpu.com/Article/details/gteidkoewf.html

"值: $b"
来源：http://dali.chenzaomai.com/Article/details/gtnhuvptcd.html

[T04] Kotlin：空安全
来源：http://dali.xuetiantiany.cn/Article/details/gtcwcljcym.html

val n: String? = null;  n?.length
来源：http://dali.andypj.xyz/Article/details/gtxeuuyvjs.html

[T05] Kotlin：when 表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqwpuoyfc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shzxlz.cn/Article/details/gtdbaeaftb.html

[T06] Kotlin：集合映射
来源：http://dali.jqgfzy.top/Article/details/gtncxyhswx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yj20258.top/Article/details/gtreeqmifj.html

[T07] Kotlin：集合过滤
来源：http://dali.dianchejie.cn/Article/details/gtfnsvgsig.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nanxuanxn.top/Article/details/gtyqsnwgop.html

[T08] Kotlin：数据类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqffuwskr.html

data class User(val name: String, val age: Int)
来源：http://dali.yueranfly.top/Article/details/gtkwrkamqz.html

[T09] Kotlin：扩展函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtunlfxybb.html

fun String.exclaim() = this + "!"
来源：http://dali.yj20258888.top/Article/details/gtstgxelzn.html

[T10] Kotlin：默认参数
来源：http://dali.yuanzhike.top/Article/details/gtecbzegpp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.birdmap.top/Article/details/gtbtykltef.html

[T11] Kotlin：协程
来源：http://dali.aibaodan.cn/Article/details/gtxjxnbxbn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jlsjyb.cn/Article/details/gtrqzvatio.html

[T12] Kotlin：解构声明
来源：http://dali.xinyue.icu/Article/details/gtgodxpvjo.html

val (a, b) = Pair(1, 2)
来源：http://dali.jqgufenzy.top/Article/details/gtnjukackw.html

[T13] Kotlin：只读 Map
来源：http://dali.havefunace.top/Article/details/gtnkdygbfm.html

val m = mapOf("a" to 1)
来源：http://dali.zhixingplan.top/Article/details/gtzhiooiit.html

[T14] Kotlin：循环
来源：http://dali.ehwqpu.com/Article/details/gtlyvfkxin.html

for (i in 1..10) println(i)
来源：http://dali.guowangkeji.top/Article/details/gtzznahxpg.html

[T15] Kotlin：接口
来源：http://dali.jianghu66.top/Article/details/gtnpkxtqbm.html

interface Shape { fun area(): Double }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwpbaxmd.html

[T16] Swift：Hello World
来源：http://dali.jianghu66.top/Article/details/gturftmect.html

print("Hello")
来源：http://dali.xylfe.cn/Article/details/gtchvusfze.html

[T17] Swift：变量与常量
来源：http://dali.jyoumei.cn/Article/details/gtievyeomn.html

var a = 1;  let b = 2
来源：http://dali.gzhubu.top/Article/details/gtcrxfffvg.html

[T18] Swift：字符串插值
来源：http://dali.ppjwa.cn/Article/details/gthqlxyohr.html

"值: \(b)"
来源：http://dali.cucudq.cn/Article/details/gtstgdgplh.html

[T19] Swift：可选绑定
来源：http://dali.xylfe.cn/Article/details/gtnziktkye.html

if let n = opt { print(n) }
来源：http://dali.quarkkingdee.top/Article/details/gtztxtcjzh.html

[T20] Swift：数组操作
来源：http://dali.shangyingyoupin.top/Article/details/gtcdiegtfj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyrlhtvnw.html

[T21] Swift：遍历
来源：http://dali.andypj.xyz/Article/details/gtcwyugtsi.html

for x in a { print(x) }
来源：http://dali.redwolf501.top/Article/details/gtwcyphxzo.html

[T22] Swift：字典
来源：http://dali.tian-w.cn/Article/details/gtodhfrskt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.tian-w.cn/Article/details/gtnnxjxmzi.html

[T23] Swift：函数
来源：http://dali.sysykeji.top/Article/details/gtolydtiod.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.daxiang520.top/Article/details/gtbtqeouzx.html

[T24] Swift：闭包
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmggdbdmo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cqqwz.cn/Article/details/gtxyyrtuxb.html

[T25] Swift：结构体
来源：http://dali.wangdashe.top/Article/details/gtmvumxndg.html

struct P { var x: Int }
来源：http://dali.xziqi.cn/Article/details/gtcxxdrdnh.html

[T26] Swift：类与重写
来源：http://dali.sufxvd.cn/Article/details/gtkmguovlw.html

class A: Base { override func f() {} }
来源：http://dali.0kj1m.cn/Article/details/gtyaqcqggm.html

[T27] Swift：错误处理
来源：http://dali.gotoacloud.top/Article/details/gtwjlxoddm.html

do { try f() } catch { print(error) }
来源：http://dali.redwolf501.top/Article/details/gttqnyispx.html

[T28] Swift：枚举
来源：http://dali.havefunace.top/Article/details/gtbkbqoycj.html

enum Color { case red, green }
来源：http://dali.haohaochexian.top/Article/details/gtloopybss.html

[T29] Swift：guard 提前返回
来源：http://dali.wangshuangyany.cn/Article/details/gtnneuszog.html

guard let x = opt else { return }
来源：http://dali.bjfxy.top/Article/details/gtcihfgfzq.html

[T30] Swift：协议
来源：http://dali.chenjidiqi.icu/Article/details/gtteoxvwcf.html

protocol Shape { func area() -> Double }
来源：http://dali.yj202588.top/Article/details/gttwisbpgw.html

[T31] Lua：Hello World
来源：http://dali.tanke756.top/Article/details/gtxjuwimnd.html

print("Hello")
来源：http://dali.sweek.top/Article/details/gtnjhppjhj.html

[T32] Lua：局部变量
来源：http://dali.jinqigufen.top/Article/details/gtwvwnejgd.html

local a = 1
来源：http://dali.daxiang520.top/Article/details/gtwbzbhfyl.html

[T33] Lua：表（数组）
来源：http://dali.shuidangran.top/Article/details/gtnutnilja.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hysaishi.cn/Article/details/gtxgavshhf.html

[T34] Lua：遍历表
来源：http://dali.gotoacloud.top/Article/details/gttlaeibqm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.pengpengdd.cyou/Article/details/gtjixketqb.html

[T35] Lua：字典表
来源：http://dali.hfpthk.cn/Article/details/gtjuituexd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sweek.top/Article/details/gtbgtjhyis.html

[T36] Lua：函数
来源：http://dali.redwolf501.top/Article/details/gtwpvrambw.html

function add(a, b) return a + b end
来源：http://dali.zycfv.cn/Article/details/gtyjpfxbds.html

[T37] Lua：字符串拼接
来源：http://dali.zhongyouzk.top/Article/details/gtmfjjqwqt.html

"a" .. "b"
来源：http://dali.yvedp.cn/Article/details/gtrhawhxmc.html

[T38] Lua：条件
来源：http://dali.jyoumei.cn/Article/details/gtjgiwitcy.html

if x > 0 then print("正") end
来源：http://dali.vqdsnc.cn/Article/details/gtthekuifi.html

[T39] Lua：模式匹配
来源：http://dali.zhengqikj.top/Article/details/gtiroakysa.html

string.find(s, "%d+")
来源：http://dali.yvedp.cn/Article/details/gtyrfupozc.html

[T40] Lua：元表
来源：http://dali.birdmap.top/Article/details/gtwhorwmwi.html

setmetatable({}, { __index = base })
来源：http://dali.redwolf501.top/Article/details/gtbsnwjgwo.html

[T41] Perl：Hello World
来源：http://dali.ybcxt.top/Article/details/gtrzqhtbqu.html

print "Hello\n";
来源：http://dali.sweek.top/Article/details/gtqixmnhut.html

[T42] Perl：变量类型
来源：http://dali.zhixingplan.top/Article/details/gtqnumxeyd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ppjwa.cn/Article/details/gtlnbvjngz.html

[T43] Perl：字符串插值
来源：http://dali.cqqwz.cn/Article/details/gtgvxbrtws.html

"值: $a"
来源：http://dali.zycfv.cn/Article/details/gtnemrxzoj.html

[T44] Perl：条件
来源：http://dali.redwolf501.top/Article/details/gtwpqagrcf.html

if ($a > 0) { print "正"; }
来源：http://dali.gogol.net.cn/Article/details/gtqiepxxft.html

[T45] Perl：数组遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpwifncyn.html

for my $x (@arr) { print $x; }
来源：http://dali.gotoacloud.top/Article/details/gticsjlldh.html

[T46] Perl：哈希操作
来源：http://dali.xuetiantiany.cn/Article/details/gtrsrydmgw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.kuanghao11.cn/Article/details/gtxdchiceq.html

[T47] Perl：正则捕获
来源：http://dali.haohaochexian.top/Article/details/gtarxcvuph.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hnxiangtu.top/Article/details/gtthdwazpi.html

[T48] Perl：正则替换
来源：http://dali.svipenyu.cn/Article/details/gtksccwvqr.html

$s =~ s/old/new/g;
来源：http://dali.sweek.top/Article/details/gtucqnbkkn.html

[T49] Perl：函数
来源：http://dali.guowangkeji.top/Article/details/gtllfqubve.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.chenzaomai.com/Article/details/gtmmhispmx.html

[T50] Perl：逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gtjhodgppl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.wangshuangyany.cn/Article/details/gtrcacyqar.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.quarkkingdee.top/Article/details/gtlzfkiaau.html

[T51] Scala：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtjbowfmjr.html

println("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gttzzpemls.html

[T52] Scala：变量
来源：http://dali.ydzc1.top/Article/details/gtmlguhhph.html

val a = 1;  var b = 2
来源：http://dali.tianlin.xyz/Article/details/gtanbdekzj.html

[T53] Scala：字符串插值
来源：http://dali.yangfankeji.com/Article/details/gtzvhgauyg.html

s"值: $b"
来源：http://dali.birdmap.top/Article/details/gtptahhynd.html

[T54] Scala：集合映射
来源：http://dali.yangfankeji.com/Article/details/gtjuudijus.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.smart0.xyz/Article/details/gtfaxjttdc.html

[T55] Scala：集合过滤
来源：http://dali.cheryme.top/Article/details/gtqnwcqrmx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.meibo888.top/Article/details/gtskyyidrl.html

[T56] Scala：样例类
来源：http://dali.wangdashe.top/Article/details/gtdvlbavsf.html

case class User(name: String, age: Int)
来源：http://dali.smart0.xyz/Article/details/gtbcqncafg.html

[T57] Scala：模式匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtkfhnwxmz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.andypj.xyz/Article/details/gtoscmmjgm.html

[T58] Scala：函数定义
来源：http://dali.9152youxi.cn/Article/details/gtixynjiue.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.nanxuanxn.top/Article/details/gtjqorifnk.html

[T59] Scala：循环
来源：http://dali.sufxvd.cn/Article/details/gtfcuusmwk.html

for (i <- 1 to 10) println(i)
来源：http://dali.yanxiufei.cn/Article/details/gtcbvmzlpj.html

[T60] Scala：折叠
来源：http://dali.smart0.xyz/Article/details/gtfyftzmad.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.dianchejie.cn/Article/details/gtcowotodq.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtjwptlccf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.sweek.top/Article/details/gtyrkngbgu.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtanxgzafl.html

[U01] Py：创建虚拟环境
来源：http://dali.tianlin.xyz/Article/details/gtgznecyco.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shzxlz.cn/Article/details/gtdifhvkhe.html

[U02] Py：导出 / 安装依赖
来源：http://dali.redwolf501.top/Article/details/gtmleepyew.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhixingplan.top/Article/details/gtcdasrlin.html

[U03] Py：加载 .env 配置
来源：http://dali.zhixingplan.top/Article/details/gtvcxwowbw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jinqigufen.top/Article/details/gtzpropzss.html

[U04] Py：变量调试打印
来源：http://dali.gogol.net.cn/Article/details/gtxnjedpug.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yj202588.top/Article/details/gtslgakgeu.html

[U05] Py：列表去重且保序
来源：http://dali.tianlin.xyz/Article/details/gtemqtjtkw.html

list(dict.fromkeys(arr))
来源：http://dali.cheryme.top/Article/details/gtczeuzvij.html

[U06] Py：合并两个字典
来源：http://dali.iojbl.cn/Article/details/gtsgcgator.html

{**a, **b}
来源：http://dali.cashguo.top/Article/details/gtjqdlfqmb.html

[U07] Py：反转字典键值
来源：http://dali.daria6918.cn/Article/details/gtzkgsxppd.html

{v: k for k, v in d.items()}
来源：http://dali.ydzc1.top/Article/details/gtnxdqfydv.html

[U08] Py：展平二维列表
来源：http://dali.sxryk.cn/Article/details/gtvjnhhiax.html

[y for x in nested for y in x]
来源：http://dali.yj20258.top/Article/details/gtdgzlvmwy.html


<!-- 参考信息 -->