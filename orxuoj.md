代发 wailian999

openssl rand -hex 16
来源：http://dali.sxryk.cn/Article/details/gttfbplxvs.html

[R68] 计算文件校验值
来源：http://dali.snrcjt.cn/Article/details/gtibdspqmw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtvtbsjnaz.html

[R69] 生成随机密码
来源：http://dali.andypj.xyz/Article/details/gtxuvcrgcj.html

head -c 16 /dev/urandom | base64
来源：http://dali.tianlin.xyz/Article/details/gtdjqhgxnl.html

[R70] 时间戳与互转
来源：http://dali.gotoacloud.top/Article/details/gtravkezhe.html

date +%s;  date -d @1700000000
来源：http://dali.jqgufenzy.top/Article/details/gtljojwtkd.html

[R71] 日期格式化
来源：http://dali.316326.xyz/Article/details/gtpylfipij.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hammf.cn/Article/details/gtculvarcw.html

[R72] 等待端口就绪
来源：http://dali.shuidangran.top/Article/details/gttzdfvgyt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.quarkkingdee.top/Article/details/gtnxdnztex.html

[R73] 分割大日志
来源：http://dali.sysykeji.top/Article/details/gtbttmjolr.html

split -l 1000 big.log part_
来源：http://dali.iojbl.cn/Article/details/gtzrvxjahl.html

[R74] 批量重命名
来源：http://dali.nwbrower.top/Article/details/gtpytcfuqw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yj20258888.top/Article/details/gtcthyrdbb.html

[R75] 导出环境变量
来源：http://dali.mhx1999.top/Article/details/gtrfapbhfz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.quarkkingdee.top/Article/details/gtwvvnrksq.html

[R76] 使用临时文件
来源：http://dali.xuetiantiany.cn/Article/details/gtfubilspf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhoulong.xyz/Article/details/gtiorjewod.html

[R77] 读取用户输入
来源：http://dali.gotoacloud.top/Article/details/gtejxvitrn.html

read -rp "请输入: " ans
来源：http://dali.fengsongda.top/Article/details/gtkghgxoro.html

[R78] 交互式菜单
来源：http://dali.guannengcc.top/Article/details/gtdqhtunkw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gotoacloud.top/Article/details/gthoskswbx.html

[R79] 解析命令行选项
来源：http://dali.chenjidiqi.icu/Article/details/gtdnuocbhq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.bjfxy.top/Article/details/gtlfumyxjk.html

[R80] 查看脚本执行耗时
来源：http://dali.snrcjt.cn/Article/details/gtgdadahcy.html

time ./run.sh
来源：http://dali.jianghu66.top/Article/details/gtrtbyugoy.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtanwtptyt.html

S. C / C++ 专题
来源：http://dali.vqdsnc.cn/Article/details/gtiemgqpxt.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtxraiusdq.html

[S01] C：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtsuxrwsij.html

#include <stdio.h>
来源：http://dali.pengpengdd.cyou/Article/details/gtzwnyjiqy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ehwqpu.com/Article/details/gtawgbznwb.html

[S02] C：变量与格式化输出
来源：http://dali.jqgufenzy.top/Article/details/gtlfjieuxe.html

int a = 10; printf("%d\n", a);
来源：http://dali.yueranfly.top/Article/details/gtzllxdiga.html

[S03] C：读入整数
来源：http://dali.jiagoushi.top/Article/details/gtdipufmgb.html

int x; scanf("%d", &x);
来源：http://dali.hnqzz.top/Article/details/gtsldmuygb.html

[S04] C：字符串复制
来源：http://dali.birdmap.top/Article/details/gtolopmvzo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nanxuanxn.top/Article/details/gtozfirijt.html

[S05] C：字符串长度
来源：http://dali.redwolf501.top/Article/details/gtxjixdzgw.html

strlen(s)
来源：http://dali.yonumen.top/Article/details/gtgoshllyd.html

[S06] C：字符串比较
来源：http://dali.hammf.cn/Article/details/gtvmdiaphk.html

strcmp(a, b) == 0
来源：http://dali.yj20258.top/Article/details/gtrzdsanfl.html

[S07] C：数组遍历求和
来源：http://dali.havefunace.top/Article/details/gtajthitbf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.pycfn.com/Article/details/gtokeqngnc.html

[S08] C：动态内存分配与释放
来源：http://dali.andypj.xyz/Article/details/gtadznggje.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hnxiangtu.top/Article/details/gtnbcaqlmf.html

[S09] C：结构体定义与初始化
来源：http://dali.aizwys.cn/Article/details/gtsjutisqb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinqigufen.top/Article/details/gtjvezpmky.html

[S10] C：指针与解引用
来源：http://dali.gzhubu.top/Article/details/gtawgfjbhs.html

int *p = &a;  *p = 5;
来源：http://dali.snrcjt.cn/Article/details/gtgrilxgji.html

[S11] C：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gtjvnskkhu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.fengsongda.top/Article/details/gtnoudticd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.redwolf501.top/Article/details/gtmtgghkbu.html

fclose(f);
来源：http://dali.xuanzx.com/Article/details/gtwsuwbhoq.html

[S12] C：写文件
来源：http://dali.andypj.xyz/Article/details/gtdfwdjbci.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.c1oappe.top/Article/details/gtizsqdoht.html

[S13] C：宏定义
来源：http://dali.iojbl.cn/Article/details/gtrvgnagtt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.havefunace.top/Article/details/gtntogflgv.html

[S14] C：枚举
来源：http://dali.havefunace.top/Article/details/gtkvdykcwo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ivvv.top/Article/details/gtujrjvgvr.html

[S15] C：类型转换
来源：http://dali.xziqi.cn/Article/details/gttaxjunpl.html

(double) a / b
来源：http://dali.cqqwz.cn/Article/details/gtdvklbowa.html

[S16] C：位操作置位
来源：http://dali.hysaishi.cn/Article/details/gtjbomhrwp.html

x |= (1 << 3);
来源：http://dali.cheryme.top/Article/details/gtamiapevw.html

[S17] C：安全拼接字符串
来源：http://dali.vqdsnc.cn/Article/details/gtnedfrjds.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.guowangkeji.top/Article/details/gtvigrllmu.html

[S18] C：命令行参数
来源：http://dali.redwolf501.top/Article/details/gtsewhqhsf.html

int main(int argc, char **argv)
来源：http://dali.jlsjyb.cn/Article/details/gtpikmefmm.html

[S19] C：快速排序
来源：http://dali.jqgfzy.top/Article/details/gtqrchmsan.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ivvv.top/Article/details/gtmehimshg.html

[S20] C：二分查找
来源：http://dali.zhongyouzk.top/Article/details/gtwvzdylhd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jlsjyb.cn/Article/details/gtokrzlhqe.html

[S21] C：字符类别判断
来源：http://dali.yongpay.top/Article/details/gtbdcogddh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sxryk.cn/Article/details/gtieiposct.html

[S22] C：字符串转数字
来源：http://dali.cqqwz.cn/Article/details/gtzggefrbf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.guannengcc.top/Article/details/gtxbtftnig.html

[S23] C：随机数
来源：http://dali.jinghuilouyu.cn/Article/details/gtpyiwncub.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cheryme.top/Article/details/gtetfkmgut.html

[S24] C：获取本地时间
来源：http://dali.zhoulong.xyz/Article/details/gtxmptoajs.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinqigfzy.top/Article/details/gtlvwitpph.html

[S25] C：内存拷贝
来源：http://dali.quarkkingdee.top/Article/details/gtkvhklyvs.html

memcpy(dst, src, n);
来源：http://dali.birdmap.top/Article/details/gtdfvndtzm.html

[S26] C：内存清零
来源：http://dali.sufxvd.cn/Article/details/gtakdrgtmv.html

memset(a, 0, sizeof a);
来源：http://dali.andypj.xyz/Article/details/gtnxkeyzkc.html

[S27] C：定义常量
来源：http://dali.jlsjyb.cn/Article/details/gtximizxrp.html

const double PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gtpzrhvvyr.html

[S28] C：静态变量
来源：http://dali.yj202588.top/Article/details/gthdtnlypr.html

static int counter = 0;
来源：http://dali.zhengqikj.top/Article/details/gtsqagltpo.html

[S29] C：变参函数
来源：http://dali.jqgufenzy.top/Article/details/gtvbbzljqh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shuidangran.top/Article/details/gtblhgrzam.html

[S30] C：头文件保护
来源：http://dali.redwolf501.top/Article/details/gtjdituhdd.html

#ifndef X_H
来源：http://dali.xinyue.icu/Article/details/gtfsbffijd.html

#define X_H
来源：http://dali.ydzc1.top/Article/details/gtfizzgxli.html

#endif
来源：http://dali.shzxlz.cn/Article/details/gtzmhinjcv.html

[S31] C++：Hello World
来源：http://dali.yueranfly.top/Article/details/gtcqdcplla.html

#include <iostream>
来源：http://dali.zhengqikj.top/Article/details/gtiudbhzmc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.9152youxi.cn/Article/details/gtcmmwtrct.html

[S32] C++：字符串
来源：http://dali.jianghu66.top/Article/details/gtfvccrgnd.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gtauxurnfl.html

[S33] C++：vector 增删
来源：http://dali.pengpengdd.cyou/Article/details/gtcmxqocdm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jianghu66.top/Article/details/gtpwehyzas.html

[S34] C++：遍历 vector
来源：http://dali.jinqigufen.top/Article/details/gtjxhplfuz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shangyingyoupin.top/Article/details/gtwaeeeanq.html

[S35] C++：map
来源：http://dali.zhongyouzk.top/Article/details/gtubnqwndp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gtdmkakhgo.html

[S36] C++：unordered_map
来源：http://dali.gzhubu.top/Article/details/gtzbkhgvqp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yongpay.top/Article/details/gtdeqksbud.html

[S37] C++：set
来源：http://dali.smart0.xyz/Article/details/gteezxlquw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jyoumei.cn/Article/details/gtxuwqkgqo.html

[S38] C++：排序
来源：http://dali.quarkkingdee.top/Article/details/gtnhbpqckj.html

std::sort(v.begin(), v.end());
来源：http://dali.jqgfzy.top/Article/details/gtjfoitrvt.html

[S39] C++：自定义比较器排序
来源：http://dali.9152youxi.cn/Article/details/gtiikhuwxo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhengqikj.top/Article/details/gtqootvthu.html

[S40] C++：查找元素
来源：http://dali.yangfankeji.com/Article/details/gtzuosufnj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenzaomai.com/Article/details/gtkldifkth.html

[S41] C++：类与构造函数
来源：http://dali.hammf.cn/Article/details/gtoejywydn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.aizwys.cn/Article/details/gtfdofbqik.html

[S42] C++：继承与虚函数
来源：http://dali.shzxlz.cn/Article/details/gtyzelnsmk.html

class B : public Base { public: void f() override {} };
来源：http://dali.ivvv.top/Article/details/gtdyavffkd.html

[S43] C++：智能指针
来源：http://dali.chenzaomai.com/Article/details/gtzfwrecxr.html

auto p = std::make_unique<int>(5);
来源：http://dali.jlsjyb.cn/Article/details/gtvwkgbpxa.html

[S44] C++：引用传参
来源：http://dali.feifeiyinyue.top/Article/details/gtokcginkr.html

void inc(int &x) { ++x; }
来源：http://dali.shangyingyoupin.top/Article/details/gtnsmkolpi.html

[S45] C++：lambda
来源：http://dali.xuetiantiany.cn/Article/details/gtsfqvebad.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yonumen.top/Article/details/gtmwsvvuml.html

[S46] C++：函数模板
来源：http://dali.nanxinkj.top/Article/details/gtsxpyeuwc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gotoacloud.top/Article/details/gtnzjhfvur.html

[S47] C++：结构化绑定遍历
来源：http://dali.yuanzhike.top/Article/details/gtuqfxqcmh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gaohongyu789.top/Article/details/gtlxjbrqit.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gtlllsvmeg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gotoacloud.top/Article/details/gtybltargp.html

while (std::getline(in, line)) { }
来源：http://dali.meibo888.top/Article/details/gtdjuomluz.html

[S49] C++：写文件
来源：http://dali.xziqi.cn/Article/details/gtfkkokgkn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.9152youxi.cn/Article/details/gtoqlnodql.html

[S50] C++：格式化数字
来源：http://dali.daria6918.cn/Article/details/gtcppjpcnh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yonumen.top/Article/details/gtqrzznjym.html

[S51] C++：显式类型转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgjazseuc.html

static_cast<double>(a) / b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbsxhotcy.html

[S52] C++：const 与 noexcept
来源：http://dali.jinghuilouyu.cn/Article/details/gtmohspzzg.html

int size() const noexcept { return n_; }
来源：http://dali.birdmap.top/Article/details/gtwnnibnph.html

[S53] C++：移动语义
来源：http://dali.dashuyun.cn/Article/details/gtcutzbqwg.html

std::vector<int> w = std::move(v);
来源：http://dali.zhoulong.xyz/Article/details/gtjcmwcvoo.html

[S54] C++：异常处理
来源：http://dali.xinyue.icu/Article/details/gtphzcnthr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yvedp.cn/Article/details/gtemdibcib.html

[S55] C++：结构化绑定
来源：http://dali.hysaishi.cn/Article/details/gtuwhvtvda.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.vqdsnc.cn/Article/details/gtecjnpuzw.html

[S56] C++：optional
来源：http://dali.hnxiangtu.top/Article/details/gtrlanyvuh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jiagoushi.top/Article/details/gtechtlovl.html

[S57] C++：编译期常量
来源：http://dali.sweek.top/Article/details/gtjjylyhwg.html

constexpr int N = 10;
来源：http://dali.quarkkingdee.top/Article/details/gtxrjkzyeh.html

[S58] C++：命名空间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfggldsvd.html

namespace ns { int f() { return 1; } }
来源：http://dali.tanke756.top/Article/details/gtvckehepx.html

[S59] C++：静态断言
来源：http://dali.cdnleiting.top/Article/details/gtaczwxplo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.daria6918.cn/Article/details/gteieqgsiw.html

[S60] C++：遍历并删除元素
来源：http://dali.fzhhl.top/Article/details/gtctfkvkin.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtowimqpvz.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtxtufvsjd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.dashuyun.cn/Article/details/gtagqvsaqq.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtdogpqkws.html

[T01] Kotlin：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtnzgxkmge.html

println("Hello")
来源：http://dali.yj202588.top/Article/details/gtmusibfgv.html

[T02] Kotlin：变量
来源：http://dali.gotoacloud.top/Article/details/gtpuyhnmxg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sxryk.cn/Article/details/gtgpytbaty.html

[T03] Kotlin：字符串模板
来源：http://dali.sysykeji.top/Article/details/gtbprxfrsm.html

"值: $b"
来源：http://dali.nanxuanxn.top/Article/details/gtdtibtesj.html

[T04] Kotlin：空安全
来源：http://dali.andypj.xyz/Article/details/gtaximzzqg.html

val n: String? = null;  n?.length
来源：http://dali.zhongyouzk.top/Article/details/gtlagtboml.html

[T05] Kotlin：when 表达式
来源：http://dali.daria6918.cn/Article/details/gthzyhsmhn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gtlbczucjd.html

[T06] Kotlin：集合映射
来源：http://dali.yanxiufei.cn/Article/details/gtjeudunum.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.smart0.xyz/Article/details/gtrnmvxoho.html

[T07] Kotlin：集合过滤
来源：http://dali.yj20258888.top/Article/details/gtlqtiipaz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ehwqpu.com/Article/details/gtripigexw.html

[T08] Kotlin：数据类
来源：http://dali.haohaochexian.top/Article/details/gtyallcbrq.html

data class User(val name: String, val age: Int)
来源：http://dali.yonumen.top/Article/details/gtxcohfpvt.html

[T09] Kotlin：扩展函数
来源：http://dali.guowangkeji.top/Article/details/gtiikylsnt.html

fun String.exclaim() = this + "!"
来源：http://dali.xylfe.cn/Article/details/gtlfielrzo.html

[T10] Kotlin：默认参数
来源：http://dali.sxryk.cn/Article/details/gtxbqcnoif.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shangyingyoupin.top/Article/details/gthbcdmour.html

[T11] Kotlin：协程
来源：http://dali.wangshuangyany.cn/Article/details/gtchqwikks.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.tianlin.xyz/Article/details/gtflwugcio.html

[T12] Kotlin：解构声明
来源：http://dali.andypj.xyz/Article/details/gtlqurgdir.html

val (a, b) = Pair(1, 2)
来源：http://dali.redwolf501.top/Article/details/gtymhulohy.html

[T13] Kotlin：只读 Map
来源：http://dali.aizwys.cn/Article/details/gtljvdnyur.html

val m = mapOf("a" to 1)
来源：http://dali.shzxlz.cn/Article/details/gtximnuysf.html

[T14] Kotlin：循环
来源：http://dali.jiagoushi.top/Article/details/gtynrjynkr.html

for (i in 1..10) println(i)
来源：http://dali.havefunace.top/Article/details/gttkdnqwhf.html

[T15] Kotlin：接口
来源：http://dali.birdmap.top/Article/details/gtjauohpow.html

interface Shape { fun area(): Double }
来源：http://dali.hongshengwenyu.top/Article/details/gtldwtazfa.html

[T16] Swift：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtalskrlds.html

print("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gtqhvwmasr.html

[T17] Swift：变量与常量
来源：http://dali.chenjidiqi.icu/Article/details/gtbkslpehl.html

var a = 1;  let b = 2
来源：http://dali.zycfv.cn/Article/details/gtgevmrauh.html

[T18] Swift：字符串插值
来源：http://dali.hammf.cn/Article/details/gtjtqxppdu.html

"值: \(b)"
来源：http://dali.meibo888.top/Article/details/gtfwcrsxov.html

[T19] Swift：可选绑定
来源：http://dali.nwbrower.top/Article/details/gtsygbpskg.html

if let n = opt { print(n) }
来源：http://dali.mhx1999.top/Article/details/gtaotltpmd.html

[T20] Swift：数组操作
来源：http://dali.yj20258888.top/Article/details/gtllggazze.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shzxlz.cn/Article/details/gtxpshncbp.html

[T21] Swift：遍历
来源：http://dali.shuidangran.top/Article/details/gtkvrzgkib.html

for x in a { print(x) }
来源：http://dali.9152youxi.cn/Article/details/gtniwumsmz.html

[T22] Swift：字典
来源：http://dali.cashguo.top/Article/details/gtykdhqkgv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ehwqpu.com/Article/details/gtnkksaudm.html

[T23] Swift：函数
来源：http://dali.9152youxi.cn/Article/details/gteunrucmp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cdnleiting.top/Article/details/gtkfzghhno.html

[T24] Swift：闭包
来源：http://dali.nanxuanxn.top/Article/details/gtkjsvhywd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sxryk.cn/Article/details/gtjsmloius.html

[T25] Swift：结构体
来源：http://dali.jqgufenzy.top/Article/details/gttpblriui.html

struct P { var x: Int }
来源：http://dali.yanxiufei.cn/Article/details/gtsukxoxpm.html

[T26] Swift：类与重写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvwqfjwht.html

class A: Base { override func f() {} }
来源：http://dali.dianchejie.cn/Article/details/gtqtfaqvsz.html

[T27] Swift：错误处理
来源：http://dali.yangfankeji.com/Article/details/gtrbdwgohb.html

do { try f() } catch { print(error) }
来源：http://dali.guannengcc.top/Article/details/gtvqaajrdf.html

[T28] Swift：枚举
来源：http://dali.mhx1999.top/Article/details/gtzhiymkgh.html

enum Color { case red, green }
来源：http://dali.andypj.xyz/Article/details/gtvvgiydcz.html

[T29] Swift：guard 提前返回
来源：http://dali.andypj.xyz/Article/details/gtgnytsnuy.html

guard let x = opt else { return }
来源：http://dali.nanxuanxn.top/Article/details/gtsxkmputt.html

[T30] Swift：协议
来源：http://dali.sysykeji.top/Article/details/gthbabjxpa.html

protocol Shape { func area() -> Double }
来源：http://dali.haohaochexian.top/Article/details/gteiiqmweb.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtqufplggp.html

print("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gtgvjlduyj.html

[T32] Lua：局部变量
来源：http://dali.sysykeji.top/Article/details/gtetswqndm.html

local a = 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtkoogglnt.html

[T33] Lua：表（数组）
来源：http://dali.vqdsnc.cn/Article/details/gtvsmxtiij.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.birdmap.top/Article/details/gtuzkidxmc.html

[T34] Lua：遍历表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjwauhdkq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ppjwa.cn/Article/details/gtluefiryy.html

[T35] Lua：字典表
来源：http://dali.haohaochexian.top/Article/details/gtdscryros.html

local d = { a = 1 };  d.b = 2
来源：http://dali.chenzaomai.com/Article/details/gtnlvdndht.html

[T36] Lua：函数
来源：http://dali.sufxvd.cn/Article/details/gthplxjzqa.html

function add(a, b) return a + b end
来源：http://dali.bjfxy.top/Article/details/gtsikyznmh.html

[T37] Lua：字符串拼接
来源：http://dali.xuanzx.com/Article/details/gthnilyilr.html

"a" .. "b"
来源：http://dali.tanke756.top/Article/details/gtqwaqqwtm.html

[T38] Lua：条件
来源：http://dali.jqgfzy.top/Article/details/gtlfpplbkz.html

if x > 0 then print("正") end
来源：http://dali.yongpay.top/Article/details/gtdsswnsxn.html

[T39] Lua：模式匹配
来源：http://dali.wangdashe.top/Article/details/gtsdzxmgmk.html

string.find(s, "%d+")
来源：http://dali.yuanzhike.top/Article/details/gtbhjheryz.html

[T40] Lua：元表
来源：http://dali.guannengcc.top/Article/details/gtfkzpxmwl.html

setmetatable({}, { __index = base })
来源：http://dali.meibo888.top/Article/details/gthbejhvod.html

[T41] Perl：Hello World
来源：http://dali.yongpay.top/Article/details/gtwpvepkmc.html

print "Hello\n";
来源：http://dali.cheryme.top/Article/details/gttncewtnr.html

[T42] Perl：变量类型
来源：http://dali.wangdashe.top/Article/details/gtpcmttdgr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zycfv.cn/Article/details/gtvbrhuknp.html

[T43] Perl：字符串插值
来源：http://dali.hywenlv.cn/Article/details/gtgfpwdtjh.html

"值: $a"
来源：http://dali.xylfe.cn/Article/details/gttggyefpx.html

[T44] Perl：条件
来源：http://dali.yuxming.cn/Article/details/gtnjnxcqny.html

if ($a > 0) { print "正"; }
来源：http://dali.sufxvd.cn/Article/details/gthstvgxih.html

[T45] Perl：数组遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtbidzxtkq.html

for my $x (@arr) { print $x; }
来源：http://dali.hysaishi.cn/Article/details/gtnzwcudre.html

[T46] Perl：哈希操作
来源：http://dali.jqgufenzy.top/Article/details/gtzxhhjhgk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.sweek.top/Article/details/gtgocdauun.html

[T47] Perl：正则捕获
来源：http://dali.jlsjyb.cn/Article/details/gtqlsqutnh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhengqikj.top/Article/details/gtjkyuhikj.html

[T48] Perl：正则替换
来源：http://dali.yangfankeji.com/Article/details/gttfnxwaov.html

$s =~ s/old/new/g;
来源：http://dali.sweek.top/Article/details/gtdnismnhz.html

[T49] Perl：函数
来源：http://dali.yanxiufei.cn/Article/details/gtklscwfos.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cheryme.top/Article/details/gtkijgsitb.html

[T50] Perl：逐行读文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtneogjyhb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cheryme.top/Article/details/gtcbxnwonw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinqigufen.top/Article/details/gtonzpdxgd.html

[T51] Scala：Hello World
来源：http://dali.pycfn.com/Article/details/gtkxyqcznm.html

println("Hello")
来源：http://dali.guannengcc.top/Article/details/gtaigrvqpv.html

[T52] Scala：变量
来源：http://dali.0kj1m.cn/Article/details/gtmlnuvbvu.html

val a = 1;  var b = 2
来源：http://dali.cqqwz.cn/Article/details/gttvmmqnqq.html

[T53] Scala：字符串插值
来源：http://dali.sysykeji.top/Article/details/gtkhjyircl.html

s"值: $b"
来源：http://dali.xuanzx.com/Article/details/gtsxlribtn.html

[T54] Scala：集合映射
来源：http://dali.hfpthk.cn/Article/details/gtuvsetozo.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jqgufenzy.top/Article/details/gthpbsweuk.html

[T55] Scala：集合过滤
来源：http://dali.sysykeji.top/Article/details/gtmkvjwxzv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.redwolf501.top/Article/details/gtmptntahe.html

[T56] Scala：样例类
来源：http://dali.yj20258.top/Article/details/gtkhfqucnn.html

case class User(name: String, age: Int)
来源：http://dali.zycfv.cn/Article/details/gtubxjtdzr.html

[T57] Scala：模式匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuvprnnpx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shuidangran.top/Article/details/gtxgxownyp.html

[T58] Scala：函数定义
来源：http://dali.yanxiufei.cn/Article/details/gtxjewnyjj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinqigfzy.top/Article/details/gtcebnbeta.html

[T59] Scala：循环
来源：http://dali.andypj.xyz/Article/details/gtstzjdccu.html

for (i <- 1 to 10) println(i)
来源：http://dali.xinyue.icu/Article/details/gtawaiepfk.html

[T60] Scala：折叠
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnzceervc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.nwbrower.top/Article/details/gtjbveckgo.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmtwmzvc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.redwolf501.top/Article/details/gtqmkqkiem.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtdqqadtln.html

[U01] Py：创建虚拟环境
来源：http://dali.hysaishi.cn/Article/details/gtcixatgrg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhiwuduotai.top/Article/details/gtbxcwpgxj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hongshengwenyu.top/Article/details/gtfsfrqkzv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.bjfxy.top/Article/details/gtemvkqbfg.html

[U03] Py：加载 .env 配置
来源：http://dali.zhixingplan.top/Article/details/gtrrizvcoh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jyoumei.cn/Article/details/gtuccpcelb.html

[U04] Py：变量调试打印
来源：http://dali.sxryk.cn/Article/details/gtqjvzsvky.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhiwuduotai.top/Article/details/gtcmvpvvyq.html

[U05] Py：列表去重且保序
来源：http://dali.ppjwa.cn/Article/details/gtwngkicmb.html

list(dict.fromkeys(arr))
来源：http://dali.hongshengwenyu.top/Article/details/gtmpsfeige.html

[U06] Py：合并两个字典
来源：http://dali.haohaochexian.top/Article/details/gtunqvekph.html

{**a, **b}
来源：http://dali.daxiang520.top/Article/details/gtxkullpdo.html

[U07] Py：反转字典键值
来源：http://dali.zycfv.cn/Article/details/gtehzqbwis.html

{v: k for k, v in d.items()}
来源：http://dali.daxiang520.top/Article/details/gtocwkmsqx.html

[U08] Py：展平二维列表
来源：http://dali.ivvv.top/Article/details/gtfjwbwzxe.html

[y for x in nested for y in x]
来源：http://dali.yuxming.cn/Article/details/gtnfsozfto.html


<!-- 参考信息 -->