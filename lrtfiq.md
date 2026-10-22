代发 wailian999

head -c 16 /dev/urandom | base64
来源：http://dali.wangshuangyany.cn/Article/details/gtssbaoghz.html

[R70] 时间戳与互转
来源：http://dali.jinqigfzy.top/Article/details/gtpzjholns.html

date +%s;  date -d @1700000000
来源：http://dali.haohaochexian.top/Article/details/gtzaolqayd.html

[R71] 日期格式化
来源：http://dali.andypj.xyz/Article/details/gtyzilxitp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinqigufen.top/Article/details/gttsihuxas.html

[R72] 等待端口就绪
来源：http://dali.ivvv.top/Article/details/gtolycnzkp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jlsjyb.cn/Article/details/gthyyfdoko.html

[R73] 分割大日志
来源：http://dali.zhiwuduotai.top/Article/details/gtfcocfzte.html

split -l 1000 big.log part_
来源：http://dali.zhongyouzk.top/Article/details/gtxlujwiyx.html

[R74] 批量重命名
来源：http://dali.shangyingyoupin.top/Article/details/gtbuvxoghp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yj20258.top/Article/details/gtgadaexjb.html

[R75] 导出环境变量
来源：http://dali.cashguo.top/Article/details/gtpaxosgkf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yueranfly.top/Article/details/gtvkmtwspg.html

[R76] 使用临时文件
来源：http://dali.yueranfly.top/Article/details/gtjjgiianf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hongshengwenyu.top/Article/details/gtdseebmyf.html

[R77] 读取用户输入
来源：http://dali.tian-w.cn/Article/details/gtybdbcqfp.html

read -rp "请输入: " ans
来源：http://dali.ydzc1.top/Article/details/gtpfcrvvfv.html

[R78] 交互式菜单
来源：http://dali.aibaodan.cn/Article/details/gtiopszbdx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cheryme.top/Article/details/gtysfmimno.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gtdjdnrtvh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.daxiang520.top/Article/details/gthtzrsevs.html

[R80] 查看脚本执行耗时
来源：http://dali.9152youxi.cn/Article/details/gtvijjubsl.html

time ./run.sh
来源：http://dali.9152youxi.cn/Article/details/gtffbassrd.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtrasxivga.html

S. C / C++ 专题
来源：http://dali.fengsongda.top/Article/details/gtewytyrri.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtdsylusyf.html

[S01] C：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gttllgszfn.html

#include <stdio.h>
来源：http://dali.jyoumei.cn/Article/details/gtxukojwwr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.redwolf501.top/Article/details/gtdxvdevgs.html

[S02] C：变量与格式化输出
来源：http://dali.hnxiangtu.top/Article/details/gthptyciyg.html

int a = 10; printf("%d\n", a);
来源：http://dali.jlsjyb.cn/Article/details/gtnofyvczb.html

[S03] C：读入整数
来源：http://dali.jlsjyb.cn/Article/details/gttfuvaixg.html

int x; scanf("%d", &x);
来源：http://dali.dianchejie.cn/Article/details/gthizuswov.html

[S04] C：字符串复制
来源：http://dali.yvedp.cn/Article/details/gtiewshfkx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yongpay.top/Article/details/gtseesithj.html

[S05] C：字符串长度
来源：http://dali.aibaodan.cn/Article/details/gtfkmpowlk.html

strlen(s)
来源：http://dali.hfpthk.cn/Article/details/gthnkstork.html

[S06] C：字符串比较
来源：http://dali.snrcjt.cn/Article/details/gtpfkikfbj.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gtihoueppm.html

[S07] C：数组遍历求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtriqbvmli.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yangfankeji.com/Article/details/gtjpswloov.html

[S08] C：动态内存分配与释放
来源：http://dali.yj20258888.top/Article/details/gtwdmiqfqf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenzaomai.com/Article/details/gtyoccbjpg.html

[S09] C：结构体定义与初始化
来源：http://dali.0kj1m.cn/Article/details/gtmakfotnm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzgiyaph.html

[S10] C：指针与解引用
来源：http://dali.cdnleiting.top/Article/details/gtjevryncf.html

int *p = &a;  *p = 5;
来源：http://dali.dianchejie.cn/Article/details/gtvltluipa.html

[S11] C：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gtvnlmoagr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gtqzgdellt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.9152youxi.cn/Article/details/gtoklignbu.html

fclose(f);
来源：http://dali.jiagoushi.top/Article/details/gtipahuwjg.html

[S12] C：写文件
来源：http://dali.nwbrower.top/Article/details/gtqdyntasn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yongpay.top/Article/details/gtdqwqikcf.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gtfeivciki.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cdnleiting.top/Article/details/gtgldrtlkf.html

[S14] C：枚举
来源：http://dali.zhoulong.xyz/Article/details/gtpywnpnpc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gogol.net.cn/Article/details/gtaiukuoxr.html

[S15] C：类型转换
来源：http://dali.aizwys.cn/Article/details/gtuthvyixo.html

(double) a / b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnljmuvzv.html

[S16] C：位操作置位
来源：http://dali.cucudq.cn/Article/details/gttulutkpk.html

x |= (1 << 3);
来源：http://dali.daria6918.cn/Article/details/gtxwldgato.html

[S17] C：安全拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtlhspnmkl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nanxuanxn.top/Article/details/gtrtcexzdg.html

[S18] C：命令行参数
来源：http://dali.shangyingyoupin.top/Article/details/gtgvljaxvb.html

int main(int argc, char **argv)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwpwtuvpf.html

[S19] C：快速排序
来源：http://dali.gaohongyu789.top/Article/details/gtnkofwila.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ivvv.top/Article/details/gtdbuzlgro.html

[S20] C：二分查找
来源：http://dali.daria6918.cn/Article/details/gtqfegverm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tanke756.top/Article/details/gtkjafgasn.html

[S21] C：字符类别判断
来源：http://dali.cucudq.cn/Article/details/gtjfgruhou.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yvedp.cn/Article/details/gtcqypaznj.html

[S22] C：字符串转数字
来源：http://dali.cdnleiting.top/Article/details/gtcxrunrnk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ybcxt.top/Article/details/gtmcallivc.html

[S23] C：随机数
来源：http://dali.sysykeji.top/Article/details/gtiyyifiqa.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cashguo.top/Article/details/gtdgaxrjfv.html

[S24] C：获取本地时间
来源：http://dali.zhoulong.xyz/Article/details/gtxsbqwxow.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.dashuyun.cn/Article/details/gtynalemir.html

[S25] C：内存拷贝
来源：http://dali.jinqigufen.top/Article/details/gthhvxejnk.html

memcpy(dst, src, n);
来源：http://dali.gaohongyu789.top/Article/details/gtqpsmpnmr.html

[S26] C：内存清零
来源：http://dali.sweek.top/Article/details/gtdswdhbuf.html

memset(a, 0, sizeof a);
来源：http://dali.yongpay.top/Article/details/gtnogskvyt.html

[S27] C：定义常量
来源：http://dali.jlsjyb.cn/Article/details/gtejsbidbv.html

const double PI = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gtaobhfnxm.html

[S28] C：静态变量
来源：http://dali.nwbrower.top/Article/details/gtlphstirf.html

static int counter = 0;
来源：http://dali.feifeiyinyue.top/Article/details/gthcrwteww.html

[S29] C：变参函数
来源：http://dali.jqgufenzy.top/Article/details/gtguomozrz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.wangshuangyany.cn/Article/details/gtlenofttn.html

[S30] C：头文件保护
来源：http://dali.yangfankeji.com/Article/details/gtuihddkoh.html

#ifndef X_H
来源：http://dali.sufxvd.cn/Article/details/gtxriicnsk.html

#define X_H
来源：http://dali.xziqi.cn/Article/details/gtfgxhlsiv.html

#endif
来源：http://dali.jianghu66.top/Article/details/gtknndplor.html

[S31] C++：Hello World
来源：http://dali.meibo888.top/Article/details/gtflhitfsc.html

#include <iostream>
来源：http://dali.fengsongda.top/Article/details/gtbobjhhzf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenlongwang.top/Article/details/gttvdaxhku.html

[S32] C++：字符串
来源：http://dali.hysaishi.cn/Article/details/gtttqritfq.html

std::string s = "hi";  s += "!";
来源：http://dali.cheryme.top/Article/details/gtxyqjjzab.html

[S33] C++：vector 增删
来源：http://dali.c1oappe.top/Article/details/gtqaoihlno.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hfpthk.cn/Article/details/gtbslitngk.html

[S34] C++：遍历 vector
来源：http://dali.zdqjudy.top/Article/details/gtjxihdvch.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.wangdashe.top/Article/details/gtxinlvteu.html

[S35] C++：map
来源：http://dali.tian-w.cn/Article/details/gtzlhtawtg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gttdmvtkgy.html

[S36] C++：unordered_map
来源：http://dali.aibaodan.cn/Article/details/gtanbvgsok.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yueranfly.top/Article/details/gtrhssnpft.html

[S37] C++：set
来源：http://dali.fzhhl.top/Article/details/gtgzvayvnd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jyoumei.cn/Article/details/gtlixifnyi.html

[S38] C++：排序
来源：http://dali.zhengqikj.top/Article/details/gtdiynfudt.html

std::sort(v.begin(), v.end());
来源：http://dali.cdnleiting.top/Article/details/gtkupczcmr.html

[S39] C++：自定义比较器排序
来源：http://dali.daria6918.cn/Article/details/gtaofkvquu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhixingplan.top/Article/details/gtlyxvfaqp.html

[S40] C++：查找元素
来源：http://dali.xziqi.cn/Article/details/gtxrrmmogv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hfpthk.cn/Article/details/gtfmqiyero.html

[S41] C++：类与构造函数
来源：http://dali.yvedp.cn/Article/details/gtymijstzc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hywenlv.cn/Article/details/gtnoolaurd.html

[S42] C++：继承与虚函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjqhlgivv.html

class B : public Base { public: void f() override {} };
来源：http://dali.havefunace.top/Article/details/gtlmcepqgn.html

[S43] C++：智能指针
来源：http://dali.yuxming.cn/Article/details/gtlafdcodu.html

auto p = std::make_unique<int>(5);
来源：http://dali.quarkkingdee.top/Article/details/gttwjvwpkt.html

[S44] C++：引用传参
来源：http://dali.wangdashe.top/Article/details/gtgntbkwvc.html

void inc(int &x) { ++x; }
来源：http://dali.gaohongyu789.top/Article/details/gteogdjcnm.html

[S45] C++：lambda
来源：http://dali.zhongyouzk.top/Article/details/gtinoijzvz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yangfankeji.com/Article/details/gtnzinyptx.html

[S46] C++：函数模板
来源：http://dali.yongpay.top/Article/details/gtohkvnpjr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cdnleiting.top/Article/details/gtnoxgojlm.html

[S47] C++：结构化绑定遍历
来源：http://dali.daxiang520.top/Article/details/gtxatlpumo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xuetiantiany.cn/Article/details/gtbajhixjt.html

[S48] C++：逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gtpioyewaz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhoulong.xyz/Article/details/gtjmyzrxww.html

while (std::getline(in, line)) { }
来源：http://dali.gogol.net.cn/Article/details/gtyujyzolo.html

[S49] C++：写文件
来源：http://dali.jinghuilouyu.cn/Article/details/gttbeqvxbo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinqigufen.top/Article/details/gtdvvjticg.html

[S50] C++：格式化数字
来源：http://dali.ehwqpu.com/Article/details/gthiwjnsmm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ybcxt.top/Article/details/gtkthecwxc.html

[S51] C++：显式类型转换
来源：http://dali.yuxming.cn/Article/details/gtjhnvfexf.html

static_cast<double>(a) / b
来源：http://dali.shzxlz.cn/Article/details/gteaaourrz.html

[S52] C++：const 与 noexcept
来源：http://dali.pycfn.com/Article/details/gtayhwvggd.html

int size() const noexcept { return n_; }
来源：http://dali.yonumen.top/Article/details/gtuaeruzxi.html

[S53] C++：移动语义
来源：http://dali.nanxuanxn.top/Article/details/gtrzcvzkly.html

std::vector<int> w = std::move(v);
来源：http://dali.zhoulong.xyz/Article/details/gtleozdtvi.html

[S54] C++：异常处理
来源：http://dali.yonumen.top/Article/details/gtavsorhao.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfswpebew.html

[S55] C++：结构化绑定
来源：http://dali.daria6918.cn/Article/details/gtslhikfip.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jqgfzy.top/Article/details/gtmpbsooeh.html

[S56] C++：optional
来源：http://dali.pengpengdd.cyou/Article/details/gthwytylrx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yuxming.cn/Article/details/gtmixpjmmr.html

[S57] C++：编译期常量
来源：http://dali.redwolf501.top/Article/details/gtoqfawgof.html

constexpr int N = 10;
来源：http://dali.yonumen.top/Article/details/gtrsaivwdz.html

[S58] C++：命名空间
来源：http://dali.shanyushiyangtech.top/Article/details/gtwcpfghhi.html

namespace ns { int f() { return 1; } }
来源：http://dali.ybcxt.top/Article/details/gtifqtfhbq.html

[S59] C++：静态断言
来源：http://dali.ydzc1.top/Article/details/gtrsfmvlfs.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.birdmap.top/Article/details/gtgehbygem.html

[S60] C++：遍历并删除元素
来源：http://dali.guannengcc.top/Article/details/gtxtfevebv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.vqdsnc.cn/Article/details/gtzerzikqw.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtufplfixp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.guowangkeji.top/Article/details/gtzsjfcpdw.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtlpqawakr.html

[T01] Kotlin：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtfmekimpu.html

println("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtsqqhtfra.html

[T02] Kotlin：变量
来源：http://dali.kuanghao11.cn/Article/details/gtdhxuhfwt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gzhubu.top/Article/details/gtmhmegprf.html

[T03] Kotlin：字符串模板
来源：http://dali.redwolf501.top/Article/details/gtikpanaxn.html

"值: $b"
来源：http://dali.quarkkingdee.top/Article/details/gtmezurghx.html

[T04] Kotlin：空安全
来源：http://dali.jyoumei.cn/Article/details/gtzwvbugvy.html

val n: String? = null;  n?.length
来源：http://dali.sufxvd.cn/Article/details/gtbvudiaiq.html

[T05] Kotlin：when 表达式
来源：http://dali.yangfankeji.com/Article/details/gtcfxsofpp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shuidangran.top/Article/details/gtxamdlclx.html

[T06] Kotlin：集合映射
来源：http://dali.shanyushiyangtech.top/Article/details/gtguwjcgcz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hammf.cn/Article/details/gtfzivrhvi.html

[T07] Kotlin：集合过滤
来源：http://dali.zdqjudy.top/Article/details/gtfsxduced.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.fzhhl.top/Article/details/gtovqdixps.html

[T08] Kotlin：数据类
来源：http://dali.yuanzhike.top/Article/details/gtgtolrkhh.html

data class User(val name: String, val age: Int)
来源：http://dali.ehwqpu.com/Article/details/gtczrdqckv.html

[T09] Kotlin：扩展函数
来源：http://dali.jianghu66.top/Article/details/gtxyspabuw.html

fun String.exclaim() = this + "!"
来源：http://dali.shzxlz.cn/Article/details/gtlnxwwlec.html

[T10] Kotlin：默认参数
来源：http://dali.ivvv.top/Article/details/gtygwnfwui.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.birdmap.top/Article/details/gtsfpjyvhb.html

[T11] Kotlin：协程
来源：http://dali.ydzc1.top/Article/details/gtxkskzgbd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jianghu66.top/Article/details/gtqthrhzca.html

[T12] Kotlin：解构声明
来源：http://dali.pycfn.com/Article/details/gtxzwpfjmx.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhixingplan.top/Article/details/gtrquyngmm.html

[T13] Kotlin：只读 Map
来源：http://dali.xuanzx.com/Article/details/gtfcvdnuvk.html

val m = mapOf("a" to 1)
来源：http://dali.daxiang520.top/Article/details/gtllkgwgtx.html

[T14] Kotlin：循环
来源：http://dali.sxryk.cn/Article/details/gtgvptxjef.html

for (i in 1..10) println(i)
来源：http://dali.zhengqikj.top/Article/details/gtpsvqsrpt.html

[T15] Kotlin：接口
来源：http://dali.meibo888.top/Article/details/gtiiqnlwco.html

interface Shape { fun area(): Double }
来源：http://dali.haohaochexian.top/Article/details/gtiopphosn.html

[T16] Swift：Hello World
来源：http://dali.ivvv.top/Article/details/gtvpzxaksw.html

print("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gtzmmtzkdm.html

[T17] Swift：变量与常量
来源：http://dali.ydzc1.top/Article/details/gtghtgoemh.html

var a = 1;  let b = 2
来源：http://dali.fzhhl.top/Article/details/gtakydkfyc.html

[T18] Swift：字符串插值
来源：http://dali.sufxvd.cn/Article/details/gtuudaunhp.html

"值: \(b)"
来源：http://dali.fengsongda.top/Article/details/gtqiscopim.html

[T19] Swift：可选绑定
来源：http://dali.dianchejie.cn/Article/details/gtzwxqdzbr.html

if let n = opt { print(n) }
来源：http://dali.fengsongda.top/Article/details/gtclmbnotg.html

[T20] Swift：数组操作
来源：http://dali.hywenlv.cn/Article/details/gtphckzdpp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj20258888.top/Article/details/gtvvwrqzwh.html

[T21] Swift：遍历
来源：http://dali.tianlin.xyz/Article/details/gtsnepctpp.html

for x in a { print(x) }
来源：http://dali.yangfankeji.com/Article/details/gtlzvauakh.html

[T22] Swift：字典
来源：http://dali.daria6918.cn/Article/details/gtkgkggblm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yanxiufei.cn/Article/details/gtmhydpiho.html

[T23] Swift：函数
来源：http://dali.nwbrower.top/Article/details/gtstfcbdlx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.aizwys.cn/Article/details/gtfsmqssgn.html

[T24] Swift：闭包
来源：http://dali.xziqi.cn/Article/details/gtqtamglbp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.meibo888.top/Article/details/gtudwssvpm.html

[T25] Swift：结构体
来源：http://dali.snrcjt.cn/Article/details/gtnkoabbyt.html

struct P { var x: Int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpwicutjz.html

[T26] Swift：类与重写
来源：http://dali.nanxinkj.top/Article/details/gtijfqlprb.html

class A: Base { override func f() {} }
来源：http://dali.shangyingyoupin.top/Article/details/gtulrjomju.html

[T27] Swift：错误处理
来源：http://dali.nwbrower.top/Article/details/gtyxchzwyk.html

do { try f() } catch { print(error) }
来源：http://dali.jiagoushi.top/Article/details/gtnduikhhu.html

[T28] Swift：枚举
来源：http://dali.jqgufenzy.top/Article/details/gteugofbro.html

enum Color { case red, green }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwawxkrjc.html

[T29] Swift：guard 提前返回
来源：http://dali.xuetiantiany.cn/Article/details/gtmrbljoaj.html

guard let x = opt else { return }
来源：http://dali.xuanzx.com/Article/details/gtatjcfkts.html

[T30] Swift：协议
来源：http://dali.nanxinkj.top/Article/details/gtjqbkhdqp.html

protocol Shape { func area() -> Double }
来源：http://dali.jyoumei.cn/Article/details/gtvuvnqvze.html

[T31] Lua：Hello World
来源：http://dali.yuxming.cn/Article/details/gtzcrelbgj.html

print("Hello")
来源：http://dali.sweek.top/Article/details/gthsdwtarg.html

[T32] Lua：局部变量
来源：http://dali.yuxming.cn/Article/details/gtnimnvwzv.html

local a = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkbtmvzla.html

[T33] Lua：表（数组）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtondtkagn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.nanxinkj.top/Article/details/gtldfygweb.html

[T34] Lua：遍历表
来源：http://dali.shuidangran.top/Article/details/gtoilsnsxc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinghuilouyu.cn/Article/details/gtzaxnbpit.html

[T35] Lua：字典表
来源：http://dali.tian-w.cn/Article/details/gtlgyqjykb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.quarkkingdee.top/Article/details/gtgcsqczqo.html

[T36] Lua：函数
来源：http://dali.svipenyu.cn/Article/details/gtwfsvkyvq.html

function add(a, b) return a + b end
来源：http://dali.yueranfly.top/Article/details/gtmejgkxjp.html

[T37] Lua：字符串拼接
来源：http://dali.cashguo.top/Article/details/gtfkcvvcji.html

"a" .. "b"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlytjwijf.html

[T38] Lua：条件
来源：http://dali.vqdsnc.cn/Article/details/gtwvxznheo.html

if x > 0 then print("正") end
来源：http://dali.hfpthk.cn/Article/details/gtxtpuisdy.html

[T39] Lua：模式匹配
来源：http://dali.gogol.net.cn/Article/details/gtkzuvcgza.html

string.find(s, "%d+")
来源：http://dali.guowangkeji.top/Article/details/gtjleacjjz.html

[T40] Lua：元表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjtecyorm.html

setmetatable({}, { __index = base })
来源：http://dali.zdqjudy.top/Article/details/gtyejorspp.html

[T41] Perl：Hello World
来源：http://dali.hammf.cn/Article/details/gtzbrvmsqr.html

print "Hello\n";
来源：http://dali.ivvv.top/Article/details/gtztckjnmb.html

[T42] Perl：变量类型
来源：http://dali.jianghu66.top/Article/details/gtkwfpqkua.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sufxvd.cn/Article/details/gtnbqisxqu.html

[T43] Perl：字符串插值
来源：http://dali.daxiang520.top/Article/details/gtfecldouu.html

"值: $a"
来源：http://dali.hfpthk.cn/Article/details/gtheffcahd.html

[T44] Perl：条件
来源：http://dali.cheryme.top/Article/details/gtpdiwnjbl.html

if ($a > 0) { print "正"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtzfarrzos.html

[T45] Perl：数组遍历
来源：http://dali.hammf.cn/Article/details/gtugncugtw.html

for my $x (@arr) { print $x; }
来源：http://dali.shzxlz.cn/Article/details/gtnwpuvdwd.html

[T46] Perl：哈希操作
来源：http://dali.wangshuangyany.cn/Article/details/gtoqbuahtd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.snrcjt.cn/Article/details/gtfetiamwf.html

[T47] Perl：正则捕获
来源：http://dali.daria6918.cn/Article/details/gtpchplnlm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnhzbvgwa.html

[T48] Perl：正则替换
来源：http://dali.xuanzx.com/Article/details/gtuyefqiex.html

$s =~ s/old/new/g;
来源：http://dali.cqqwz.cn/Article/details/gtzzkgigfy.html

[T49] Perl：函数
来源：http://dali.shuidangran.top/Article/details/gtvdcpllpy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cdnleiting.top/Article/details/gttfxcpyru.html

[T50] Perl：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gtmolbhojj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtziwnpnqi.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.andypj.xyz/Article/details/gtjdhnrvlq.html

[T51] Scala：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gthsanzyod.html

println("Hello")
来源：http://dali.cheryme.top/Article/details/gtevynoxer.html

[T52] Scala：变量
来源：http://dali.chenjidiqi.icu/Article/details/gtvpzwlbmn.html

val a = 1;  var b = 2
来源：http://dali.hfpthk.cn/Article/details/gtvwldlojm.html

[T53] Scala：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gtqbtteonx.html

s"值: $b"
来源：http://dali.zycfv.cn/Article/details/gtwzhqsghq.html

[T54] Scala：集合映射
来源：http://dali.vqdsnc.cn/Article/details/gtexheazls.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhoulong.xyz/Article/details/gtrcrahali.html

[T55] Scala：集合过滤
来源：http://dali.pycfn.com/Article/details/gtxbsmfpbz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtmohknxxp.html

[T56] Scala：样例类
来源：http://dali.0kj1m.cn/Article/details/gtvbwassqr.html

case class User(name: String, age: Int)
来源：http://dali.pengpengdd.cyou/Article/details/gtynarmriw.html

[T57] Scala：模式匹配
来源：http://dali.yonumen.top/Article/details/gtjtvakuam.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.chenlongwang.top/Article/details/gtncdltjdx.html

[T58] Scala：函数定义
来源：http://dali.wangshuangyany.cn/Article/details/gtimyigedc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.9152youxi.cn/Article/details/gtsmpvzqgt.html

[T59] Scala：循环
来源：http://dali.redwolf501.top/Article/details/gtgihaiyug.html

for (i <- 1 to 10) println(i)
来源：http://dali.ppjwa.cn/Article/details/gtayxyjnhb.html

[T60] Scala：折叠
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnyqklgos.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.snrcjt.cn/Article/details/gtgyqcgnxw.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtzytqdolj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shuidangran.top/Article/details/gtajoeuxpn.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtjgbbgxnf.html

[U01] Py：创建虚拟环境
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthgmfmfnm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hnqzz.top/Article/details/gtxywqbrcd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yj202588.top/Article/details/gtafaelwrc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yangfankeji.com/Article/details/gtgajbvctq.html

[U03] Py：加载 .env 配置
来源：http://dali.xinyue.icu/Article/details/gtejttklmg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gzhubu.top/Article/details/gtccyqhslx.html

[U04] Py：变量调试打印
来源：http://dali.jqgufenzy.top/Article/details/gtjhdzxmys.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cucudq.cn/Article/details/gtonhkllrd.html

[U05] Py：列表去重且保序
来源：http://dali.yongpay.top/Article/details/gtwjszrfkr.html

list(dict.fromkeys(arr))
来源：http://dali.jinqigfzy.top/Article/details/gttejudgit.html

[U06] Py：合并两个字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmtdlldiz.html

{**a, **b}
来源：http://dali.shangyingyoupin.top/Article/details/gtfoszyqvb.html

[U07] Py：反转字典键值
来源：http://dali.iojbl.cn/Article/details/gtmmrzzzwm.html

{v: k for k, v in d.items()}
来源：http://dali.chenzaomai.com/Article/details/gtcvsqxzbj.html

[U08] Py：展平二维列表
来源：http://dali.chenjidiqi.icu/Article/details/gtkbspjike.html

[y for x in nested for y in x]
来源：http://dali.yj20258888.top/Article/details/gtegukfjmt.html

[U09] Py：字典取最大值的键
来源：http://dali.zhaomingkeji.xyz/Article/details/gtludnhdsq.html

max(d, key=d.get)
来源：http://dali.jiagoushi.top/Article/details/gtnwmbfybw.html

[U10] Py：按值排序字典
来源：http://dali.chenzaomai.com/Article/details/gtxhirebfd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.guannengcc.top/Article/details/gtzwmqncee.html


<!-- 参考信息 -->