代发 wailian999

openssl rand -hex 16
来源：http://dali.jlsjyb.cn/Article/details/gtmphxkvvf.html

[R68] 计算文件校验值
来源：http://dali.jqgufenzy.top/Article/details/gtiipesihu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxgmqdwq.html

[R69] 生成随机密码
来源：http://dali.feifeiyinyue.top/Article/details/gtpzrvsejc.html

head -c 16 /dev/urandom | base64
来源：http://dali.gaohongyu789.top/Article/details/gtyjvgeicm.html

[R70] 时间戳与互转
来源：http://dali.sxryk.cn/Article/details/gtzqlnthmk.html

date +%s;  date -d @1700000000
来源：http://dali.hammf.cn/Article/details/gtqvavrjkx.html

[R71] 日期格式化
来源：http://dali.havefunace.top/Article/details/gtjspppcgf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.andypj.xyz/Article/details/gtzhavobuy.html

[R72] 等待端口就绪
来源：http://dali.yongpay.top/Article/details/gtmiszxmnz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtzyhdryfq.html

[R73] 分割大日志
来源：http://dali.chenzaomai.com/Article/details/gtpoqxtkoo.html

split -l 1000 big.log part_
来源：http://dali.chenzaomai.com/Article/details/gtkhiwixxb.html

[R74] 批量重命名
来源：http://dali.jinqigfzy.top/Article/details/gtcadeqtjd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.dashuyun.cn/Article/details/gthqbbybih.html

[R75] 导出环境变量
来源：http://dali.pycfn.com/Article/details/gtnekngeau.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.aibaodan.cn/Article/details/gtfjxcbnhk.html

[R76] 使用临时文件
来源：http://dali.shuidangran.top/Article/details/gthuppyvmj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.quarkkingdee.top/Article/details/gtqvkhiklw.html

[R77] 读取用户输入
来源：http://dali.wangdashe.top/Article/details/gthbpwmlvr.html

read -rp "请输入: " ans
来源：http://dali.zhixingplan.top/Article/details/gteodfgugi.html

[R78] 交互式菜单
来源：http://dali.andypj.xyz/Article/details/gtazgpanqi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.daria6918.cn/Article/details/gttolchdny.html

[R79] 解析命令行选项
来源：http://dali.quarkkingdee.top/Article/details/gtzykakidt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxwoyiffd.html

[R80] 查看脚本执行耗时
来源：http://dali.xuetiantiany.cn/Article/details/gtvymghlpi.html

time ./run.sh
来源：http://dali.jqgufenzy.top/Article/details/gtilqadpna.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtyewnkchy.html

S. C / C++ 专题
来源：http://dali.yueranfly.top/Article/details/gtqlomfmtv.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtuypjjhay.html

[S01] C：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtusvewkru.html

#include <stdio.h>
来源：http://dali.zycfv.cn/Article/details/gtnpahjkfe.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.c1oappe.top/Article/details/gtihmwltlk.html

[S02] C：变量与格式化输出
来源：http://dali.hfpthk.cn/Article/details/gtzctjkpnf.html

int a = 10; printf("%d\n", a);
来源：http://dali.hywenlv.cn/Article/details/gtsemumutg.html

[S03] C：读入整数
来源：http://dali.quarkkingdee.top/Article/details/gtpwzjkxku.html

int x; scanf("%d", &x);
来源：http://dali.zhoulong.xyz/Article/details/gtzfarnkbr.html

[S04] C：字符串复制
来源：http://dali.yj202588.top/Article/details/gtofdtiacm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.haohaochexian.top/Article/details/gtszzdyxze.html

[S05] C：字符串长度
来源：http://dali.ydzc1.top/Article/details/gtenddgnxr.html

strlen(s)
来源：http://dali.sxryk.cn/Article/details/gtraciriec.html

[S06] C：字符串比较
来源：http://dali.nwbrower.top/Article/details/gtldmyjqfw.html

strcmp(a, b) == 0
来源：http://dali.chenlongwang.top/Article/details/gtzxuddynh.html

[S07] C：数组遍历求和
来源：http://dali.9152youxi.cn/Article/details/gtqakhqtvb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zdqjudy.top/Article/details/gtzqcvfpbn.html

[S08] C：动态内存分配与释放
来源：http://dali.gotoacloud.top/Article/details/gtfirbrkvt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shzxlz.cn/Article/details/gtymvrhprq.html

[S09] C：结构体定义与初始化
来源：http://dali.tanke756.top/Article/details/gtoipexapv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.daxiang520.top/Article/details/gtnulzqouw.html

[S10] C：指针与解引用
来源：http://dali.wangdashe.top/Article/details/gtyvyvacon.html

int *p = &a;  *p = 5;
来源：http://dali.svipenyu.cn/Article/details/gtrhquguaf.html

[S11] C：逐行读文件
来源：http://dali.cheryme.top/Article/details/gtmyiswmqb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jyoumei.cn/Article/details/gtpgruxjvf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.daria6918.cn/Article/details/gtohtcqijd.html

fclose(f);
来源：http://dali.fzhhl.top/Article/details/gtkbdfypga.html

[S12] C：写文件
来源：http://dali.dashuyun.cn/Article/details/gtdmdwztzv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sysykeji.top/Article/details/gtlamsbwll.html

[S13] C：宏定义
来源：http://dali.cashguo.top/Article/details/gtkumliqsw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nanxuanxn.top/Article/details/gtccxnyzku.html

[S14] C：枚举
来源：http://dali.ehwqpu.com/Article/details/gtvvstrppk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.fengsongda.top/Article/details/gtehlyyzhk.html

[S15] C：类型转换
来源：http://dali.yuxming.cn/Article/details/gtmkzhzojn.html

(double) a / b
来源：http://dali.vqdsnc.cn/Article/details/gthdrgaosu.html

[S16] C：位操作置位
来源：http://dali.zhaomingkeji.xyz/Article/details/gtambelzxp.html

x |= (1 << 3);
来源：http://dali.dashuyun.cn/Article/details/gtristaqsw.html

[S17] C：安全拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gtdirvgwwk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sxryk.cn/Article/details/gtbyvryvyh.html

[S18] C：命令行参数
来源：http://dali.yonumen.top/Article/details/gtmmzbysfk.html

int main(int argc, char **argv)
来源：http://dali.ehwqpu.com/Article/details/gtxhplxgid.html

[S19] C：快速排序
来源：http://dali.nanxinkj.top/Article/details/gthoduirew.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cucudq.cn/Article/details/gtzzhocodm.html

[S20] C：二分查找
来源：http://dali.tanke756.top/Article/details/gtwuwoevpo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.haohaochexian.top/Article/details/gtuccjwsto.html

[S21] C：字符类别判断
来源：http://dali.hnxiangtu.top/Article/details/gtdarluaof.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sweek.top/Article/details/gtuvxytysb.html

[S22] C：字符串转数字
来源：http://dali.xuetiantiany.cn/Article/details/gtbfeuecgs.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yueranfly.top/Article/details/gtovtmonjw.html

[S23] C：随机数
来源：http://dali.smart0.xyz/Article/details/gtsejxsjwo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtastvcwnt.html

[S24] C：获取本地时间
来源：http://dali.cheryme.top/Article/details/gtvxiltsbl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.meibo888.top/Article/details/gtlgqsjpct.html

[S25] C：内存拷贝
来源：http://dali.gzhubu.top/Article/details/gtzgcklryr.html

memcpy(dst, src, n);
来源：http://dali.hnqzz.top/Article/details/gtkcbqiivn.html

[S26] C：内存清零
来源：http://dali.yvedp.cn/Article/details/gtvzkutaba.html

memset(a, 0, sizeof a);
来源：http://dali.316326.xyz/Article/details/gtdzzsssjh.html

[S27] C：定义常量
来源：http://dali.mhx1999.top/Article/details/gtwivrapiu.html

const double PI = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gtbrfcmarg.html

[S28] C：静态变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwbunffjv.html

static int counter = 0;
来源：http://dali.snrcjt.cn/Article/details/gtwaeldgxo.html

[S29] C：变参函数
来源：http://dali.yanxiufei.cn/Article/details/gtouvbwvni.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.snrcjt.cn/Article/details/gthwadqkoo.html

[S30] C：头文件保护
来源：http://dali.yangfankeji.com/Article/details/gtogrqpnfx.html

#ifndef X_H
来源：http://dali.zhongyouzk.top/Article/details/gtwtkibqxj.html

#define X_H
来源：http://dali.mhx1999.top/Article/details/gttznjscrz.html

#endif
来源：http://dali.yueranfly.top/Article/details/gtrzskctzx.html

[S31] C++：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtwpenwfpd.html

#include <iostream>
来源：http://dali.fzhhl.top/Article/details/gtyisgpjoa.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.aibaodan.cn/Article/details/gtcrituawy.html

[S32] C++：字符串
来源：http://dali.aibaodan.cn/Article/details/gtdkazyvca.html

std::string s = "hi";  s += "!";
来源：http://dali.jqgfzy.top/Article/details/gtgvwibjmr.html

[S33] C++：vector 增删
来源：http://dali.hywenlv.cn/Article/details/gtlpiqzmha.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yuanzhike.top/Article/details/gtpqmtoqrc.html

[S34] C++：遍历 vector
来源：http://dali.havefunace.top/Article/details/gtxjjofjuv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.c1oappe.top/Article/details/gtvuimekjk.html

[S35] C++：map
来源：http://dali.zhaomingkeji.xyz/Article/details/gthjqrnidd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gtfaikglln.html

[S36] C++：unordered_map
来源：http://dali.jiagoushi.top/Article/details/gtpkxkrrvu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtimtydoph.html

[S37] C++：set
来源：http://dali.zhoulong.xyz/Article/details/gtlwrxhnwg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yonumen.top/Article/details/gtsdqdsqmn.html

[S38] C++：排序
来源：http://dali.zycfv.cn/Article/details/gtbtkoinfj.html

std::sort(v.begin(), v.end());
来源：http://dali.xinyue.icu/Article/details/gtynjdldbt.html

[S39] C++：自定义比较器排序
来源：http://dali.tian-w.cn/Article/details/gtobciwjqu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhixingplan.top/Article/details/gtgfqonwtp.html

[S40] C++：查找元素
来源：http://dali.daria6918.cn/Article/details/gtsbghacfp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.wangdashe.top/Article/details/gtbldkoqdw.html

[S41] C++：类与构造函数
来源：http://dali.jiagoushi.top/Article/details/gtiahxkviv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.svipenyu.cn/Article/details/gtoxshsnqi.html

[S42] C++：继承与虚函数
来源：http://dali.pengpengdd.cyou/Article/details/gtqjwalizb.html

class B : public Base { public: void f() override {} };
来源：http://dali.jiagoushi.top/Article/details/gtyjorryzp.html

[S43] C++：智能指针
来源：http://dali.ybcxt.top/Article/details/gtvvedjxqw.html

auto p = std::make_unique<int>(5);
来源：http://dali.jqgufenzy.top/Article/details/gtawcpqzso.html

[S44] C++：引用传参
来源：http://dali.kuanghao11.cn/Article/details/gtiergewma.html

void inc(int &x) { ++x; }
来源：http://dali.kuanghao11.cn/Article/details/gtmzbpcapc.html

[S45] C++：lambda
来源：http://dali.ehwqpu.com/Article/details/gtoullafqk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.chenlongwang.top/Article/details/gtrlwxfpim.html

[S46] C++：函数模板
来源：http://dali.jiagoushi.top/Article/details/gtlejgavqt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpwxnfdnm.html

[S47] C++：结构化绑定遍历
来源：http://dali.jiagoushi.top/Article/details/gtntneaqwv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.kuanghao11.cn/Article/details/gtifmrcqpc.html

[S48] C++：逐行读文件
来源：http://dali.havefunace.top/Article/details/gtsudxlptb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.nanxinkj.top/Article/details/gtnadpvcfv.html

while (std::getline(in, line)) { }
来源：http://dali.chenlongwang.top/Article/details/gttodylavq.html

[S49] C++：写文件
来源：http://dali.shangyingyoupin.top/Article/details/gtzyisnvwy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.svipenyu.cn/Article/details/gtnfajnugg.html

[S50] C++：格式化数字
来源：http://dali.guannengcc.top/Article/details/gtohxcpcxk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.316326.xyz/Article/details/gtyvdzmfml.html

[S51] C++：显式类型转换
来源：http://dali.cashguo.top/Article/details/gtoyutwzje.html

static_cast<double>(a) / b
来源：http://dali.aizwys.cn/Article/details/gtntxqodob.html

[S52] C++：const 与 noexcept
来源：http://dali.jianghu66.top/Article/details/gtrhobmcdd.html

int size() const noexcept { return n_; }
来源：http://dali.snrcjt.cn/Article/details/gtyqzgiubc.html

[S53] C++：移动语义
来源：http://dali.meibo888.top/Article/details/gtiuggrtnq.html

std::vector<int> w = std::move(v);
来源：http://dali.hfpthk.cn/Article/details/gtychagurb.html

[S54] C++：异常处理
来源：http://dali.zdqjudy.top/Article/details/gtcqkljoye.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cheryme.top/Article/details/gtjaveeeap.html

[S55] C++：结构化绑定
来源：http://dali.jinghuilouyu.cn/Article/details/gtnoiwknsp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cqqwz.cn/Article/details/gtsuhvtbov.html

[S56] C++：optional
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrdppglta.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shuidangran.top/Article/details/gtmltygqwk.html

[S57] C++：编译期常量
来源：http://dali.sufxvd.cn/Article/details/gtsucmjqkm.html

constexpr int N = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwcujrcp.html

[S58] C++：命名空间
来源：http://dali.tanke756.top/Article/details/gtfxrwtedp.html

namespace ns { int f() { return 1; } }
来源：http://dali.xuanzx.com/Article/details/gtabaiosxt.html

[S59] C++：静态断言
来源：http://dali.nwbrower.top/Article/details/gtozuixwbw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.c1oappe.top/Article/details/gtvkcbowvf.html

[S60] C++：遍历并删除元素
来源：http://dali.yueranfly.top/Article/details/gtadxfrdzq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdjxpgjpf.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtltbsfign.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cdnleiting.top/Article/details/gtgtraxxqg.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtlyxaxubb.html

[T01] Kotlin：Hello World
来源：http://dali.fzhhl.top/Article/details/gttpqjhbyc.html

println("Hello")
来源：http://dali.yuxming.cn/Article/details/gtjjvjrqks.html

[T02] Kotlin：变量
来源：http://dali.kuanghao11.cn/Article/details/gtienwtsjm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ivvv.top/Article/details/gtsupbocdw.html

[T03] Kotlin：字符串模板
来源：http://dali.sufxvd.cn/Article/details/gtcfmjfzou.html

"值: $b"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbocmdlhy.html

[T04] Kotlin：空安全
来源：http://dali.cqqwz.cn/Article/details/gtqcoxrqpe.html

val n: String? = null;  n?.length
来源：http://dali.yueranfly.top/Article/details/gtymlwhtzg.html

[T05] Kotlin：when 表达式
来源：http://dali.aizwys.cn/Article/details/gtywzxoipg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.nanxinkj.top/Article/details/gtxqwzjubn.html

[T06] Kotlin：集合映射
来源：http://dali.havefunace.top/Article/details/gtstlvdvji.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.svipenyu.cn/Article/details/gtxbtvcmmr.html

[T07] Kotlin：集合过滤
来源：http://dali.yuxming.cn/Article/details/gtpjmhiuyn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yongpay.top/Article/details/gtpfjjtuwn.html

[T08] Kotlin：数据类
来源：http://dali.kuanghao11.cn/Article/details/gtribggnmh.html

data class User(val name: String, val age: Int)
来源：http://dali.tanke756.top/Article/details/gtsepnejyc.html

[T09] Kotlin：扩展函数
来源：http://dali.ehwqpu.com/Article/details/gtoxyriwow.html

fun String.exclaim() = this + "!"
来源：http://dali.yongpay.top/Article/details/gtmlmpuwln.html

[T10] Kotlin：默认参数
来源：http://dali.snrcjt.cn/Article/details/gtgayganzy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sxryk.cn/Article/details/gtnwvfjtzk.html

[T11] Kotlin：协程
来源：http://dali.jiagoushi.top/Article/details/gtvdggxfbm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.aizwys.cn/Article/details/gtuwhhapho.html

[T12] Kotlin：解构声明
来源：http://dali.guowangkeji.top/Article/details/gttcvdgfpw.html

val (a, b) = Pair(1, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtctllkpsu.html

[T13] Kotlin：只读 Map
来源：http://dali.bjfxy.top/Article/details/gtfbbkpcoi.html

val m = mapOf("a" to 1)
来源：http://dali.feifeiyinyue.top/Article/details/gthdkfgukw.html

[T14] Kotlin：循环
来源：http://dali.sweek.top/Article/details/gtazmncand.html

for (i in 1..10) println(i)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqohtetbj.html

[T15] Kotlin：接口
来源：http://dali.yangfankeji.com/Article/details/gtfynrctuh.html

interface Shape { fun area(): Double }
来源：http://dali.zhixingplan.top/Article/details/gtmhrwiznt.html

[T16] Swift：Hello World
来源：http://dali.ppjwa.cn/Article/details/gttpwlzgon.html

print("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gtvesecuoy.html

[T17] Swift：变量与常量
来源：http://dali.hnxiangtu.top/Article/details/gtznsmvznk.html

var a = 1;  let b = 2
来源：http://dali.9152youxi.cn/Article/details/gtvygfvnrb.html

[T18] Swift：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gtaybunqnt.html

"值: \(b)"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtidjcvzmh.html

[T19] Swift：可选绑定
来源：http://dali.shangyingyoupin.top/Article/details/gtqigdotpl.html

if let n = opt { print(n) }
来源：http://dali.sufxvd.cn/Article/details/gtgjfaljdt.html

[T20] Swift：数组操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkoqjdqqg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ehwqpu.com/Article/details/gthbedjpcj.html

[T21] Swift：遍历
来源：http://dali.fzhhl.top/Article/details/gtyawlorax.html

for x in a { print(x) }
来源：http://dali.tianlin.xyz/Article/details/gtfxewsixb.html

[T22] Swift：字典
来源：http://dali.aizwys.cn/Article/details/gtazqefjpk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sxryk.cn/Article/details/gtqzovtori.html

[T23] Swift：函数
来源：http://dali.hongshengwenyu.top/Article/details/gtllavfqdv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhengqikj.top/Article/details/gtdbfszvvv.html

[T24] Swift：闭包
来源：http://dali.daxiang520.top/Article/details/gtmdujrthu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.guannengcc.top/Article/details/gtzqatzvmh.html

[T25] Swift：结构体
来源：http://dali.jinqigufen.top/Article/details/gtnfcadioz.html

struct P { var x: Int }
来源：http://dali.kuanghao11.cn/Article/details/gtrtacrjna.html

[T26] Swift：类与重写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrheiowty.html

class A: Base { override func f() {} }
来源：http://dali.pycfn.com/Article/details/gtpmcdezuw.html

[T27] Swift：错误处理
来源：http://dali.meibo888.top/Article/details/gttmfpaevx.html

do { try f() } catch { print(error) }
来源：http://dali.zhixingplan.top/Article/details/gtptmztdka.html

[T28] Swift：枚举
来源：http://dali.redwolf501.top/Article/details/gtnmnbccff.html

enum Color { case red, green }
来源：http://dali.c1oappe.top/Article/details/gtnclfisoh.html

[T29] Swift：guard 提前返回
来源：http://dali.zhoulong.xyz/Article/details/gtqurncfjr.html

guard let x = opt else { return }
来源：http://dali.andypj.xyz/Article/details/gtdrsxtvzp.html

[T30] Swift：协议
来源：http://dali.yj202588.top/Article/details/gticbbrfls.html

protocol Shape { func area() -> Double }
来源：http://dali.ivvv.top/Article/details/gtiyhabnpn.html

[T31] Lua：Hello World
来源：http://dali.316326.xyz/Article/details/gtwvyolmge.html

print("Hello")
来源：http://dali.fzhhl.top/Article/details/gtxweuelrg.html

[T32] Lua：局部变量
来源：http://dali.svipenyu.cn/Article/details/gtgcpyrglr.html

local a = 1
来源：http://dali.guowangkeji.top/Article/details/gtvalrrocq.html

[T33] Lua：表（数组）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfroalten.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shanyushiyangtech.top/Article/details/gtfbpgyzbp.html

[T34] Lua：遍历表
来源：http://dali.mhx1999.top/Article/details/gtluudbuug.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.snrcjt.cn/Article/details/gtgrffipfz.html

[T35] Lua：字典表
来源：http://dali.0kj1m.cn/Article/details/gttqgjimfo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ivvv.top/Article/details/gtanevodxo.html

[T36] Lua：函数
来源：http://dali.zhiwuduotai.top/Article/details/gtwmtksnir.html

function add(a, b) return a + b end
来源：http://dali.chenlongwang.top/Article/details/gtxkgbwurv.html

[T37] Lua：字符串拼接
来源：http://dali.snrcjt.cn/Article/details/gtrzbmyvrj.html

"a" .. "b"
来源：http://dali.dianchejie.cn/Article/details/gtgtjkszok.html

[T38] Lua：条件
来源：http://dali.zycfv.cn/Article/details/gtzsoojdpt.html

if x > 0 then print("正") end
来源：http://dali.guannengcc.top/Article/details/gtciusbazr.html

[T39] Lua：模式匹配
来源：http://dali.zycfv.cn/Article/details/gtuivdsehl.html

string.find(s, "%d+")
来源：http://dali.gaohongyu789.top/Article/details/gtstptneop.html

[T40] Lua：元表
来源：http://dali.jinqigufen.top/Article/details/gtxuribalx.html

setmetatable({}, { __index = base })
来源：http://dali.sufxvd.cn/Article/details/gtpbhtimhc.html

[T41] Perl：Hello World
来源：http://dali.hammf.cn/Article/details/gtknzxjvbg.html

print "Hello\n";
来源：http://dali.zhiwuduotai.top/Article/details/gtyvkoadqa.html

[T42] Perl：变量类型
来源：http://dali.yueranfly.top/Article/details/gtoewffhcy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.chenzaomai.com/Article/details/gtppqaujnt.html

[T43] Perl：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvhxposjm.html

"值: $a"
来源：http://dali.hfpthk.cn/Article/details/gtcufqixde.html

[T44] Perl：条件
来源：http://dali.snrcjt.cn/Article/details/gtphrgtuqe.html

if ($a > 0) { print "正"; }
来源：http://dali.jianghu66.top/Article/details/gtprldjbpq.html

[T45] Perl：数组遍历
来源：http://dali.zhoulong.xyz/Article/details/gtffmkutfn.html

for my $x (@arr) { print $x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxculwxaw.html

[T46] Perl：哈希操作
来源：http://dali.bjfxy.top/Article/details/gtqkmdnoqu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gzhubu.top/Article/details/gtzgvogriq.html

[T47] Perl：正则捕获
来源：http://dali.chenzaomai.com/Article/details/gtbgudmcko.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.chenzaomai.com/Article/details/gtcmbehgyx.html

[T48] Perl：正则替换
来源：http://dali.cucudq.cn/Article/details/gtxvtuomgi.html

$s =~ s/old/new/g;
来源：http://dali.zhixingplan.top/Article/details/gtvfkcniin.html

[T49] Perl：函数
来源：http://dali.guowangkeji.top/Article/details/gtkrrnytmx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gtlxirkggw.html

[T50] Perl：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gtgkmxnibf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhixingplan.top/Article/details/gtxburcxbs.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinqigufen.top/Article/details/gtjkqtgugv.html

[T51] Scala：Hello World
来源：http://dali.hnqzz.top/Article/details/gtoifwgayt.html

println("Hello")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdkzjbcey.html

[T52] Scala：变量
来源：http://dali.shangyingyoupin.top/Article/details/gtoytvppln.html

val a = 1;  var b = 2
来源：http://dali.wangdashe.top/Article/details/gtzkvozhmc.html

[T53] Scala：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gtaxgcrggd.html

s"值: $b"
来源：http://dali.shzxlz.cn/Article/details/gtzxfvhgfo.html

[T54] Scala：集合映射
来源：http://dali.yuanzhike.top/Article/details/gtniwwrfbt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ppjwa.cn/Article/details/gtxqjvdwcx.html

[T55] Scala：集合过滤
来源：http://dali.pycfn.com/Article/details/gtqmeddbgi.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.guannengcc.top/Article/details/gtzkuehwsf.html

[T56] Scala：样例类
来源：http://dali.aizwys.cn/Article/details/gtmosgdfmk.html

case class User(name: String, age: Int)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrszjqrvb.html

[T57] Scala：模式匹配
来源：http://dali.ivvv.top/Article/details/gtmgzvmwuz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jiagoushi.top/Article/details/gtkeonefvy.html

[T58] Scala：函数定义
来源：http://dali.xinyue.icu/Article/details/gthjuonyxu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.0kj1m.cn/Article/details/gtvjpakddi.html

[T59] Scala：循环
来源：http://dali.shanyushiyangtech.top/Article/details/gttwtyfehy.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gtvwwhdnat.html

[T60] Scala：折叠
来源：http://dali.dashuyun.cn/Article/details/gtbvftpmmc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xinyue.icu/Article/details/gtypflvxhq.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtimmmqzbr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhixingplan.top/Article/details/gttyaguhlf.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtlmpotkrt.html

[U01] Py：创建虚拟环境
来源：http://dali.xuetiantiany.cn/Article/details/gtmntwzrbz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.redwolf501.top/Article/details/gtbfwjxgzb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yj20258.top/Article/details/gtvjbddsgp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.guannengcc.top/Article/details/gtdpqemwan.html

[U03] Py：加载 .env 配置
来源：http://dali.havefunace.top/Article/details/gtvfuuorke.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.tian-w.cn/Article/details/gtqviajnst.html

[U04] Py：变量调试打印
来源：http://dali.9152youxi.cn/Article/details/gtofwrlnlk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.pycfn.com/Article/details/gtqwcirljq.html

[U05] Py：列表去重且保序
来源：http://dali.quarkkingdee.top/Article/details/gtkmtxjfto.html

list(dict.fromkeys(arr))
来源：http://dali.yangfankeji.com/Article/details/gtbpjwobkd.html

[U06] Py：合并两个字典
来源：http://dali.zdqjudy.top/Article/details/gtoqzepwuv.html

{**a, **b}
来源：http://dali.andypj.xyz/Article/details/gtbmdcuuiz.html

[U07] Py：反转字典键值
来源：http://dali.zhoulong.xyz/Article/details/gtxtzbjaie.html

{v: k for k, v in d.items()}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuzgriayg.html

[U08] Py：展平二维列表
来源：http://dali.yangfankeji.com/Article/details/gtwwomhuvz.html

[y for x in nested for y in x]
来源：http://dali.ybcxt.top/Article/details/gtbsynkmio.html


<!-- 参考信息 -->