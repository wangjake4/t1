代发 wailian999

head -c 16 /dev/urandom | base64
来源：http://dali.shzxlz.cn/Article/details/gtzfwskmlg.html

[R70] 时间戳与互转
来源：http://dali.hammf.cn/Article/details/gttpfpocgc.html

date +%s;  date -d @1700000000
来源：http://dali.chenjidiqi.icu/Article/details/gtrrtthnjb.html

[R71] 日期格式化
来源：http://dali.mhx1999.top/Article/details/gtideuzovw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hongshengwenyu.top/Article/details/gtmecjahrk.html

[R72] 等待端口就绪
来源：http://dali.smart0.xyz/Article/details/gtozdezgbf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.quarkkingdee.top/Article/details/gtqiwncfec.html

[R73] 分割大日志
来源：http://dali.xuanzx.com/Article/details/gthcoajyyl.html

split -l 1000 big.log part_
来源：http://dali.shanyushiyangkeji.top/Article/details/gtymrnbuny.html

[R74] 批量重命名
来源：http://dali.ybcxt.top/Article/details/gtvkqcirsh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xziqi.cn/Article/details/gteekiwunl.html

[R75] 导出环境变量
来源：http://dali.shuidangran.top/Article/details/gtapoymkwg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgfzy.top/Article/details/gthtisnpqv.html

[R76] 使用临时文件
来源：http://dali.ppjwa.cn/Article/details/gtadxhseps.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangshuangyany.cn/Article/details/gtknirwiem.html

[R77] 读取用户输入
来源：http://dali.nwbrower.top/Article/details/gtoudshrbh.html

read -rp "请输入: " ans
来源：http://dali.dianchejie.cn/Article/details/gtxvryecwy.html

[R78] 交互式菜单
来源：http://dali.hnxiangtu.top/Article/details/gtbjaedmrg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xziqi.cn/Article/details/gtjxojkqbz.html

[R79] 解析命令行选项
来源：http://dali.feifeiyinyue.top/Article/details/gtrmzfndoa.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenjidiqi.icu/Article/details/gtedlddzqe.html

[R80] 查看脚本执行耗时
来源：http://dali.zhengqikj.top/Article/details/gtbuuhpeez.html

time ./run.sh
来源：http://dali.pengpengdd.cyou/Article/details/gtulkjcxiy.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtzrjksihr.html

S. C / C++ 专题
来源：http://dali.birdmap.top/Article/details/gtfshoqxkj.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtrvmmxvad.html

[S01] C：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtpehcxydz.html

#include <stdio.h>
来源：http://dali.gzhubu.top/Article/details/gtfyhlqhlh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.fzhhl.top/Article/details/gtaqkppqqn.html

[S02] C：变量与格式化输出
来源：http://dali.fzhhl.top/Article/details/gtfyzeusvo.html

int a = 10; printf("%d\n", a);
来源：http://dali.jiagoushi.top/Article/details/gtbypfwoxo.html

[S03] C：读入整数
来源：http://dali.jlsjyb.cn/Article/details/gtlgihsluj.html

int x; scanf("%d", &x);
来源：http://dali.fzhhl.top/Article/details/gtzhgdtgbc.html

[S04] C：字符串复制
来源：http://dali.hnqzz.top/Article/details/gtzhwokdti.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gtximuqodx.html

[S05] C：字符串长度
来源：http://dali.jinqigufen.top/Article/details/gtzqcftqsx.html

strlen(s)
来源：http://dali.cashguo.top/Article/details/gthfvsiiji.html

[S06] C：字符串比较
来源：http://dali.yangfankeji.com/Article/details/gtmadklwbn.html

strcmp(a, b) == 0
来源：http://dali.birdmap.top/Article/details/gttfzpevbu.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gtfovvperz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hnxiangtu.top/Article/details/gtbjlntkzo.html

[S08] C：动态内存分配与释放
来源：http://dali.wangdashe.top/Article/details/gtideortmy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.birdmap.top/Article/details/gtpeytwrsj.html

[S09] C：结构体定义与初始化
来源：http://dali.ehwqpu.com/Article/details/gtrklmzuir.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nanxinkj.top/Article/details/gtxvnefnbt.html

[S10] C：指针与解引用
来源：http://dali.yuxming.cn/Article/details/gthzcrnttz.html

int *p = &a;  *p = 5;
来源：http://dali.shanyushiyangtech.top/Article/details/gtevucsbyy.html

[S11] C：逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gtovugmycc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tianlin.xyz/Article/details/gtkmrhudxy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenlongwang.top/Article/details/gtzirbqrub.html

fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gtkkvguocs.html

[S12] C：写文件
来源：http://dali.redwolf501.top/Article/details/gtzukecivp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yongpay.top/Article/details/gtinkazcls.html

[S13] C：宏定义
来源：http://dali.ehwqpu.com/Article/details/gtdrrihoij.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cheryme.top/Article/details/gtfbonwxsw.html

[S14] C：枚举
来源：http://dali.iojbl.cn/Article/details/gtjehzhpag.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.aibaodan.cn/Article/details/gtbhelgsrw.html

[S15] C：类型转换
来源：http://dali.tanke756.top/Article/details/gtwnfikpqy.html

(double) a / b
来源：http://dali.snrcjt.cn/Article/details/gtgfncviko.html

[S16] C：位操作置位
来源：http://dali.chenzaomai.com/Article/details/gtilbnsqah.html

x |= (1 << 3);
来源：http://dali.jyoumei.cn/Article/details/gtvknctygo.html

[S17] C：安全拼接字符串
来源：http://dali.havefunace.top/Article/details/gtpzmbuxbx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yanxiufei.cn/Article/details/gtjxcbjhxf.html

[S18] C：命令行参数
来源：http://dali.bjfxy.top/Article/details/gtgmgaacfg.html

int main(int argc, char **argv)
来源：http://dali.daria6918.cn/Article/details/gtiaomkhiz.html

[S19] C：快速排序
来源：http://dali.gzhubu.top/Article/details/gtjbhvmvir.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gtsuobaygt.html

[S20] C：二分查找
来源：http://dali.yueranfly.top/Article/details/gtssrkawmh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shuidangran.top/Article/details/gtvwyhpvnd.html

[S21] C：字符类别判断
来源：http://dali.guannengcc.top/Article/details/gtptictinw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zycfv.cn/Article/details/gtvsdvtpve.html

[S22] C：字符串转数字
来源：http://dali.yangfankeji.com/Article/details/gtixieoybn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sxryk.cn/Article/details/gtbtgttpvy.html

[S23] C：随机数
来源：http://dali.ivvv.top/Article/details/gtnmwrqfhg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ybcxt.top/Article/details/gtbbkmlzaf.html

[S24] C：获取本地时间
来源：http://dali.nwbrower.top/Article/details/gtgkoaqqmk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.aizwys.cn/Article/details/gtswvtyfgi.html

[S25] C：内存拷贝
来源：http://dali.quarkkingdee.top/Article/details/gtcrgathmq.html

memcpy(dst, src, n);
来源：http://dali.aibaodan.cn/Article/details/gtwqewtdrn.html

[S26] C：内存清零
来源：http://dali.bjfxy.top/Article/details/gtaqpqpqlh.html

memset(a, 0, sizeof a);
来源：http://dali.jinqigfzy.top/Article/details/gtfkzhogqa.html

[S27] C：定义常量
来源：http://dali.fengsongda.top/Article/details/gtqoolbpkj.html

const double PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gtixcehdyl.html

[S28] C：静态变量
来源：http://dali.nwbrower.top/Article/details/gttuhswknk.html

static int counter = 0;
来源：http://dali.ehwqpu.com/Article/details/gtqdjbfscc.html

[S29] C：变参函数
来源：http://dali.dashuyun.cn/Article/details/gtdkdddino.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.snrcjt.cn/Article/details/gtrwsuvliz.html

[S30] C：头文件保护
来源：http://dali.yanxiufei.cn/Article/details/gtwwlyerhw.html

#ifndef X_H
来源：http://dali.jlsjyb.cn/Article/details/gtgfcwovlg.html

#define X_H
来源：http://dali.feifeiyinyue.top/Article/details/gtvqxbdsxe.html

#endif
来源：http://dali.jinqigfzy.top/Article/details/gtbnhrsnda.html

[S31] C++：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtbvkxbxmi.html

#include <iostream>
来源：http://dali.feifeiyinyue.top/Article/details/gtqhpmvqne.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jqgfzy.top/Article/details/gtjelatauv.html

[S32] C++：字符串
来源：http://dali.redwolf501.top/Article/details/gtzcqwaxml.html

std::string s = "hi";  s += "!";
来源：http://dali.tianlin.xyz/Article/details/gtwhsubeoo.html

[S33] C++：vector 增删
来源：http://dali.bjfxy.top/Article/details/gtyqqdfnhp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tian-w.cn/Article/details/gtafeumkpr.html

[S34] C++：遍历 vector
来源：http://dali.tanke756.top/Article/details/gtonvpveig.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gotoacloud.top/Article/details/gtyqwlihfu.html

[S35] C++：map
来源：http://dali.pengpengdd.cyou/Article/details/gtvafprvyb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtqdbztwwi.html

[S36] C++：unordered_map
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrdiolfwm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gtqnwojsxj.html

[S37] C++：set
来源：http://dali.316326.xyz/Article/details/gtfunuezrz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.havefunace.top/Article/details/gtheotyxyv.html

[S38] C++：排序
来源：http://dali.guowangkeji.top/Article/details/gtcadqgbyx.html

std::sort(v.begin(), v.end());
来源：http://dali.jqgfzy.top/Article/details/gttxpoxcah.html

[S39] C++：自定义比较器排序
来源：http://dali.yuxming.cn/Article/details/gtjvbhcyus.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj202588.top/Article/details/gtsitggsmh.html

[S40] C++：查找元素
来源：http://dali.cdnleiting.top/Article/details/gtvmijycft.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jqgufenzy.top/Article/details/gttundemdl.html

[S41] C++：类与构造函数
来源：http://dali.jinqigufen.top/Article/details/gtdohthyww.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.wangshuangyany.cn/Article/details/gtqqxqhies.html

[S42] C++：继承与虚函数
来源：http://dali.cheryme.top/Article/details/gtnyvdezss.html

class B : public Base { public: void f() override {} };
来源：http://dali.gotoacloud.top/Article/details/gtwwwkrhdu.html

[S43] C++：智能指针
来源：http://dali.gaohongyu789.top/Article/details/gtizfoomjo.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdlpscozk.html

[S44] C++：引用传参
来源：http://dali.yuxming.cn/Article/details/gtmptpjnxc.html

void inc(int &x) { ++x; }
来源：http://dali.jiagoushi.top/Article/details/gtsdcrslcf.html

[S45] C++：lambda
来源：http://dali.jinqigfzy.top/Article/details/gtobhpkzds.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fzhhl.top/Article/details/gtzxuzbmnh.html

[S46] C++：函数模板
来源：http://dali.vqdsnc.cn/Article/details/gtuvdebnsk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shuidangran.top/Article/details/gtyypgujsb.html

[S47] C++：结构化绑定遍历
来源：http://dali.ehwqpu.com/Article/details/gtadlikzwv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sysykeji.top/Article/details/gtsirhkrfx.html

[S48] C++：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjrcbtqpa.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ydzc1.top/Article/details/gthfxkjihr.html

while (std::getline(in, line)) { }
来源：http://dali.ppjwa.cn/Article/details/gtexpdvdne.html

[S49] C++：写文件
来源：http://dali.smart0.xyz/Article/details/gtywhqfwsq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.andypj.xyz/Article/details/gtnwcpiohe.html

[S50] C++：格式化数字
来源：http://dali.zdqjudy.top/Article/details/gtnolyoflt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gtejwfsbto.html

[S51] C++：显式类型转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbqvfcjlh.html

static_cast<double>(a) / b
来源：http://dali.xziqi.cn/Article/details/gtplwkilih.html

[S52] C++：const 与 noexcept
来源：http://dali.jinqigufen.top/Article/details/gtrfdioink.html

int size() const noexcept { return n_; }
来源：http://dali.xuanzx.com/Article/details/gthyadvnoi.html

[S53] C++：移动语义
来源：http://dali.snrcjt.cn/Article/details/gtxmhxckso.html

std::vector<int> w = std::move(v);
来源：http://dali.yueranfly.top/Article/details/gtjvjqapou.html

[S54] C++：异常处理
来源：http://dali.chenjidiqi.icu/Article/details/gtesavrjsa.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.guowangkeji.top/Article/details/gtrmczuuca.html

[S55] C++：结构化绑定
来源：http://dali.yj20258888.top/Article/details/gtygylazuo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtsgvvvdfw.html

[S56] C++：optional
来源：http://dali.gzhubu.top/Article/details/gtdsuhrvxw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinqigufen.top/Article/details/gtvxnkszwy.html

[S57] C++：编译期常量
来源：http://dali.yonumen.top/Article/details/gttlftvfpr.html

constexpr int N = 10;
来源：http://dali.sysykeji.top/Article/details/gtizlwjzdk.html

[S58] C++：命名空间
来源：http://dali.shanyushiyangtech.top/Article/details/gttmxeausc.html

namespace ns { int f() { return 1; } }
来源：http://dali.hfpthk.cn/Article/details/gtdsxmvraq.html

[S59] C++：静态断言
来源：http://dali.svipenyu.cn/Article/details/gtbgxmslxs.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cashguo.top/Article/details/gttlnughku.html

[S60] C++：遍历并删除元素
来源：http://dali.zhoulong.xyz/Article/details/gtpofnrbfl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.aizwys.cn/Article/details/gtdlamvfrh.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtlksemcep.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jyoumei.cn/Article/details/gtcqclxslj.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtwghswbeo.html

[T01] Kotlin：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtsbvlgirh.html

println("Hello")
来源：http://dali.cqqwz.cn/Article/details/gtkwjeybso.html

[T02] Kotlin：变量
来源：http://dali.andypj.xyz/Article/details/gtuonwdebd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yj20258888.top/Article/details/gtwrmxniac.html

[T03] Kotlin：字符串模板
来源：http://dali.yvedp.cn/Article/details/gtaoyxnqge.html

"值: $b"
来源：http://dali.ybcxt.top/Article/details/gtbjdvhrlw.html

[T04] Kotlin：空安全
来源：http://dali.daxiang520.top/Article/details/gttkgrpgzz.html

val n: String? = null;  n?.length
来源：http://dali.yanxiufei.cn/Article/details/gtgrbjmimk.html

[T05] Kotlin：when 表达式
来源：http://dali.nwbrower.top/Article/details/gtgglvyzis.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmblcmui.html

[T06] Kotlin：集合映射
来源：http://dali.xylfe.cn/Article/details/gtcknhwnbw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtepyzwxtz.html

[T07] Kotlin：集合过滤
来源：http://dali.chenlongwang.top/Article/details/gtcpgrnsdb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sufxvd.cn/Article/details/gtmnlylpps.html

[T08] Kotlin：数据类
来源：http://dali.tianlin.xyz/Article/details/gtnmseipwl.html

data class User(val name: String, val age: Int)
来源：http://dali.guowangkeji.top/Article/details/gtheqkzzaq.html

[T09] Kotlin：扩展函数
来源：http://dali.pengpengdd.cyou/Article/details/gtulrhuulu.html

fun String.exclaim() = this + "!"
来源：http://dali.jinghuilouyu.cn/Article/details/gtmgwqmtay.html

[T10] Kotlin：默认参数
来源：http://dali.yj20258888.top/Article/details/gtokepjtzs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.havefunace.top/Article/details/gtcqewgyim.html

[T11] Kotlin：协程
来源：http://dali.daxiang520.top/Article/details/gtzwxtnxlv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.birdmap.top/Article/details/gtlcldagka.html

[T12] Kotlin：解构声明
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoxfkcarf.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttrsiwmhy.html

[T13] Kotlin：只读 Map
来源：http://dali.yj20258888.top/Article/details/gtxhnizhsj.html

val m = mapOf("a" to 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtnwctrcwj.html

[T14] Kotlin：循环
来源：http://dali.havefunace.top/Article/details/gturqhbogb.html

for (i in 1..10) println(i)
来源：http://dali.daria6918.cn/Article/details/gtmxalrvog.html

[T15] Kotlin：接口
来源：http://dali.haohaochexian.top/Article/details/gtilteexjn.html

interface Shape { fun area(): Double }
来源：http://dali.cucudq.cn/Article/details/gtndgbxokc.html

[T16] Swift：Hello World
来源：http://dali.yongpay.top/Article/details/gtxikdltyx.html

print("Hello")
来源：http://dali.nwbrower.top/Article/details/gtaeutkbmi.html

[T17] Swift：变量与常量
来源：http://dali.quarkkingdee.top/Article/details/gtopdzyyvz.html

var a = 1;  let b = 2
来源：http://dali.ppjwa.cn/Article/details/gtkaztrptf.html

[T18] Swift：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gtmstjkhop.html

"值: \(b)"
来源：http://dali.pengpengdd.cyou/Article/details/gtrjomehyn.html

[T19] Swift：可选绑定
来源：http://dali.jyoumei.cn/Article/details/gtokpvqorf.html

if let n = opt { print(n) }
来源：http://dali.xziqi.cn/Article/details/gtprswuanu.html

[T20] Swift：数组操作
来源：http://dali.nanxuanxn.top/Article/details/gtffiduyct.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yuxming.cn/Article/details/gtqxvytlir.html

[T21] Swift：遍历
来源：http://dali.jiagoushi.top/Article/details/gtxzhmskdw.html

for x in a { print(x) }
来源：http://dali.yj20258.top/Article/details/gtxysimmqr.html

[T22] Swift：字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqgohpqky.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yuanzhike.top/Article/details/gtccpohquv.html

[T23] Swift：函数
来源：http://dali.hywenlv.cn/Article/details/gtndalmmrn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.dianchejie.cn/Article/details/gtdzoraxfu.html

[T24] Swift：闭包
来源：http://dali.snrcjt.cn/Article/details/gtcbxhfwyj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.tanke756.top/Article/details/gtonndpfao.html

[T25] Swift：结构体
来源：http://dali.xinyue.icu/Article/details/gtlntqmblm.html

struct P { var x: Int }
来源：http://dali.shangyingyoupin.top/Article/details/gtbnekvuqb.html

[T26] Swift：类与重写
来源：http://dali.jqgufenzy.top/Article/details/gtqbdfhdnl.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gtqyugstqv.html

[T27] Swift：错误处理
来源：http://dali.pengpengdd.cyou/Article/details/gtmpoqoarj.html

do { try f() } catch { print(error) }
来源：http://dali.zhixingplan.top/Article/details/gtuuynwvgr.html

[T28] Swift：枚举
来源：http://dali.gaohongyu789.top/Article/details/gtswzeavmr.html

enum Color { case red, green }
来源：http://dali.guannengcc.top/Article/details/gtkpwrarcn.html

[T29] Swift：guard 提前返回
来源：http://dali.zhoulong.xyz/Article/details/gtgtomwpdd.html

guard let x = opt else { return }
来源：http://dali.yangfankeji.com/Article/details/gtrrtpgxip.html

[T30] Swift：协议
来源：http://dali.andypj.xyz/Article/details/gttmigeszy.html

protocol Shape { func area() -> Double }
来源：http://dali.ppjwa.cn/Article/details/gtvavmtnwy.html

[T31] Lua：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtomrfhbwa.html

print("Hello")
来源：http://dali.jqgfzy.top/Article/details/gtajewjpnm.html

[T32] Lua：局部变量
来源：http://dali.zycfv.cn/Article/details/gthbkotele.html

local a = 1
来源：http://dali.chenlongwang.top/Article/details/gtjdymcnnv.html

[T33] Lua：表（数组）
来源：http://dali.jlsjyb.cn/Article/details/gteqteirki.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cashguo.top/Article/details/gtnqhqvgbh.html

[T34] Lua：遍历表
来源：http://dali.0kj1m.cn/Article/details/gtpgmgltye.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.aizwys.cn/Article/details/gtsitiohhh.html

[T35] Lua：字典表
来源：http://dali.xylfe.cn/Article/details/gtirvvmxxn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhoulong.xyz/Article/details/gtixvyqglt.html

[T36] Lua：函数
来源：http://dali.tanke756.top/Article/details/gtvnjnoiya.html

function add(a, b) return a + b end
来源：http://dali.tianlin.xyz/Article/details/gtscktkwce.html

[T37] Lua：字符串拼接
来源：http://dali.yj202588.top/Article/details/gtsnalbnfy.html

"a" .. "b"
来源：http://dali.0kj1m.cn/Article/details/gtqklqgbww.html

[T38] Lua：条件
来源：http://dali.jiagoushi.top/Article/details/gtavkfzmnw.html

if x > 0 then print("正") end
来源：http://dali.yj202588.top/Article/details/gtaezutqdq.html

[T39] Lua：模式匹配
来源：http://dali.sysykeji.top/Article/details/gtktjbdlty.html

string.find(s, "%d+")
来源：http://dali.daria6918.cn/Article/details/gtewvyopje.html

[T40] Lua：元表
来源：http://dali.yj20258.top/Article/details/gtcovhdjcv.html

setmetatable({}, { __index = base })
来源：http://dali.vqdsnc.cn/Article/details/gtesrcmxyn.html

[T41] Perl：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtpjqfgzvn.html

print "Hello\n";
来源：http://dali.zhiwuduotai.top/Article/details/gtgxhzekrc.html

[T42] Perl：变量类型
来源：http://dali.yanxiufei.cn/Article/details/gtnzuasjls.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xuanzx.com/Article/details/gtgiqeypyz.html

[T43] Perl：字符串插值
来源：http://dali.andypj.xyz/Article/details/gthtnndgma.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gtyuhrxtia.html

[T44] Perl：条件
来源：http://dali.pycfn.com/Article/details/gtlqjcmkjs.html

if ($a > 0) { print "正"; }
来源：http://dali.tanke756.top/Article/details/gtzhpxcinl.html

[T45] Perl：数组遍历
来源：http://dali.sysykeji.top/Article/details/gtwowttmai.html

for my $x (@arr) { print $x; }
来源：http://dali.jqgufenzy.top/Article/details/gtwylnnmnc.html

[T46] Perl：哈希操作
来源：http://dali.yueranfly.top/Article/details/gtbbdolyim.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.0kj1m.cn/Article/details/gtitwqpdar.html

[T47] Perl：正则捕获
来源：http://dali.chenlongwang.top/Article/details/gtmfomwlfl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.tanke756.top/Article/details/gtpqfwewrn.html

[T48] Perl：正则替换
来源：http://dali.mhx1999.top/Article/details/gtcyfytydq.html

$s =~ s/old/new/g;
来源：http://dali.cashguo.top/Article/details/gtqvmzvrha.html

[T49] Perl：函数
来源：http://dali.vqdsnc.cn/Article/details/gtywsiusbh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shuidangran.top/Article/details/gtfxuefkvb.html

[T50] Perl：逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gttsncxqlv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yongpay.top/Article/details/gtdcdwczvc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zdqjudy.top/Article/details/gtpbqjapev.html

[T51] Scala：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtsryanjuu.html

println("Hello")
来源：http://dali.aizwys.cn/Article/details/gtmewyljkn.html

[T52] Scala：变量
来源：http://dali.snrcjt.cn/Article/details/gtkyoctlds.html

val a = 1;  var b = 2
来源：http://dali.gaohongyu789.top/Article/details/gtflbvrtzz.html

[T53] Scala：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gtrfwpymzb.html

s"值: $b"
来源：http://dali.sufxvd.cn/Article/details/gtakbramwg.html

[T54] Scala：集合映射
来源：http://dali.sweek.top/Article/details/gtbxdijyqc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.xuanzx.com/Article/details/gtgpzvoqmi.html

[T55] Scala：集合过滤
来源：http://dali.gaohongyu789.top/Article/details/gtjfyrbrur.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yangfankeji.com/Article/details/gtcswvmuze.html

[T56] Scala：样例类
来源：http://dali.shuidangran.top/Article/details/gtswkurrff.html

case class User(name: String, age: Int)
来源：http://dali.aizwys.cn/Article/details/gtgesvtmef.html

[T57] Scala：模式匹配
来源：http://dali.wangdashe.top/Article/details/gtmfnloqpb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.havefunace.top/Article/details/gtqrfzshuv.html

[T58] Scala：函数定义
来源：http://dali.jinqigufen.top/Article/details/gtmrmoztit.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhoulong.xyz/Article/details/gtsrnutdwi.html

[T59] Scala：循环
来源：http://dali.sweek.top/Article/details/gtxwsbabqq.html

for (i <- 1 to 10) println(i)
来源：http://dali.haohaochexian.top/Article/details/gtgekdqagh.html

[T60] Scala：折叠
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjldvjgp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yvedp.cn/Article/details/gtxpfsleto.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtdvbuikqo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.havefunace.top/Article/details/gtfdjdmxui.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtwumyfoiz.html

[U01] Py：创建虚拟环境
来源：http://dali.hfpthk.cn/Article/details/gtjqhukaxh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.svipenyu.cn/Article/details/gtwjfghftt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.guowangkeji.top/Article/details/gtjohotgdt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.316326.xyz/Article/details/gtrgxjvaug.html

[U03] Py：加载 .env 配置
来源：http://dali.andypj.xyz/Article/details/gtcqjpkblv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.birdmap.top/Article/details/gtmfhqslnw.html

[U04] Py：变量调试打印
来源：http://dali.pengpengdd.cyou/Article/details/gttjjpmmim.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.9152youxi.cn/Article/details/gtwwvuiwqd.html

[U05] Py：列表去重且保序
来源：http://dali.wangshuangyany.cn/Article/details/gtqckrvtxk.html

list(dict.fromkeys(arr))
来源：http://dali.wangdashe.top/Article/details/gtybsryviz.html

[U06] Py：合并两个字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmlyjxao.html

{**a, **b}
来源：http://dali.hammf.cn/Article/details/gtcpddzmur.html

[U07] Py：反转字典键值
来源：http://dali.quarkkingdee.top/Article/details/gteoasnssy.html

{v: k for k, v in d.items()}
来源：http://dali.iojbl.cn/Article/details/gtcmxmcjhr.html

[U08] Py：展平二维列表
来源：http://dali.jqgfzy.top/Article/details/gtlrhjnqfe.html

[y for x in nested for y in x]
来源：http://dali.birdmap.top/Article/details/gtrzvdqwew.html

[U09] Py：字典取最大值的键
来源：http://dali.ppjwa.cn/Article/details/gtoikijnmr.html

max(d, key=d.get)
来源：http://dali.haohaochexian.top/Article/details/gtssucdubw.html

[U10] Py：按值排序字典
来源：http://dali.jinghuilouyu.cn/Article/details/gtlfbigmwv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jyoumei.cn/Article/details/gthbfdofaq.html


<!-- 参考信息 -->