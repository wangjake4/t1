代发 wailian999

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jqgfzy.top/Article/details/gtpcazlqvc.html

[R72] 等待端口就绪
来源：http://dali.jinqigufen.top/Article/details/gtidigxlmn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.haohaochexian.top/Article/details/gttvhwkohh.html

[R73] 分割大日志
来源：http://dali.cdnleiting.top/Article/details/gtixrmpcmi.html

split -l 1000 big.log part_
来源：http://dali.hfpthk.cn/Article/details/gtyagzeeuo.html

[R74] 批量重命名
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdbvnnju.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sxryk.cn/Article/details/gtpfppnqgy.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gtnizvoqad.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cqqwz.cn/Article/details/gtprpzqtre.html

[R76] 使用临时文件
来源：http://dali.cashguo.top/Article/details/gtonjwibaj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sweek.top/Article/details/gtaqpnnfxp.html

[R77] 读取用户输入
来源：http://dali.birdmap.top/Article/details/gtltdunumr.html

read -rp "请输入: " ans
来源：http://dali.kuanghao11.cn/Article/details/gtqopbcjhn.html

[R78] 交互式菜单
来源：http://dali.zhiwuduotai.top/Article/details/gtcqqmedxv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jianghu66.top/Article/details/gtinjdrnmb.html

[R79] 解析命令行选项
来源：http://dali.zhongyouzk.top/Article/details/gtqxvkeefd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cdnleiting.top/Article/details/gtisdflkhu.html

[R80] 查看脚本执行耗时
来源：http://dali.cashguo.top/Article/details/gtuynnpggz.html

time ./run.sh
来源：http://dali.jinqigufen.top/Article/details/gtqqwhxtkh.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gthfkzjypb.html

S. C / C++ 专题
来源：http://dali.fengsongda.top/Article/details/gtejisnash.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxbhkbkyq.html

[S01] C：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtwjsfqcfj.html

#include <stdio.h>
来源：http://dali.xylfe.cn/Article/details/gtzmqjjqdx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj20258.top/Article/details/gtrvibuxws.html

[S02] C：变量与格式化输出
来源：http://dali.yonumen.top/Article/details/gtpytrgxkd.html

int a = 10; printf("%d\n", a);
来源：http://dali.hywenlv.cn/Article/details/gtordafmud.html

[S03] C：读入整数
来源：http://dali.zhiwuduotai.top/Article/details/gtbfgmyyop.html

int x; scanf("%d", &x);
来源：http://dali.jinqigfzy.top/Article/details/gtssyjkjlm.html

[S04] C：字符串复制
来源：http://dali.bjfxy.top/Article/details/gtfrypedlm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.snrcjt.cn/Article/details/gtootauirn.html

[S05] C：字符串长度
来源：http://dali.gaohongyu789.top/Article/details/gtzdyfmizz.html

strlen(s)
来源：http://dali.shzxlz.cn/Article/details/gttlwovguu.html

[S06] C：字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gtczkffcqs.html

strcmp(a, b) == 0
来源：http://dali.jyoumei.cn/Article/details/gtxhcxwvcy.html

[S07] C：数组遍历求和
来源：http://dali.jqgufenzy.top/Article/details/gtdsgwgsle.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.redwolf501.top/Article/details/gtlemrcfxj.html

[S08] C：动态内存分配与释放
来源：http://dali.cashguo.top/Article/details/gtmhmcjlua.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqmryscl.html

[S09] C：结构体定义与初始化
来源：http://dali.9152youxi.cn/Article/details/gtgeabcbgq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tanke756.top/Article/details/gtyfqhycsn.html

[S10] C：指针与解引用
来源：http://dali.9152youxi.cn/Article/details/gtzgokvpov.html

int *p = &a;  *p = 5;
来源：http://dali.jyoumei.cn/Article/details/gtelmlduff.html

[S11] C：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtnhujtvno.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxgycbjad.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhoulong.xyz/Article/details/gtmhkgjpft.html

fclose(f);
来源：http://dali.zhongyouzk.top/Article/details/gtwprztlfi.html

[S12] C：写文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtezaujvfd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yueranfly.top/Article/details/gtskvnanbe.html

[S13] C：宏定义
来源：http://dali.316326.xyz/Article/details/gtvaxddnru.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hammf.cn/Article/details/gtmrtcllzy.html

[S14] C：枚举
来源：http://dali.guannengcc.top/Article/details/gtdyttdylz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.kuanghao11.cn/Article/details/gtbcjbcixs.html

[S15] C：类型转换
来源：http://dali.meibo888.top/Article/details/gtinmfhfrl.html

(double) a / b
来源：http://dali.nanxuanxn.top/Article/details/gtkkpbnfza.html

[S16] C：位操作置位
来源：http://dali.vqdsnc.cn/Article/details/gtcdmnhfmf.html

x |= (1 << 3);
来源：http://dali.gotoacloud.top/Article/details/gtvfegbyof.html

[S17] C：安全拼接字符串
来源：http://dali.gzhubu.top/Article/details/gtbsxtgcin.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ydzc1.top/Article/details/gtpoewtgxr.html

[S18] C：命令行参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtohpibzox.html

int main(int argc, char **argv)
来源：http://dali.c1oappe.top/Article/details/gtmybohqsa.html

[S19] C：快速排序
来源：http://dali.birdmap.top/Article/details/gtsxutqiko.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jqgufenzy.top/Article/details/gtvctbpzat.html

[S20] C：二分查找
来源：http://dali.zhoulong.xyz/Article/details/gtltibdqvr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtryfkxexh.html

[S21] C：字符类别判断
来源：http://dali.yuxming.cn/Article/details/gtzdagxdvs.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gaohongyu789.top/Article/details/gtnpxtafna.html

[S22] C：字符串转数字
来源：http://dali.hnxiangtu.top/Article/details/gtjnisbpnr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ydzc1.top/Article/details/gtadzugapv.html

[S23] C：随机数
来源：http://dali.c1oappe.top/Article/details/gtcmqzaqom.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yangfankeji.com/Article/details/gtxqeuiigq.html

[S24] C：获取本地时间
来源：http://dali.iojbl.cn/Article/details/gtpmzmwbuc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhengqikj.top/Article/details/gtukqrlnud.html

[S25] C：内存拷贝
来源：http://dali.zhongyouzk.top/Article/details/gtwdgmgrcd.html

memcpy(dst, src, n);
来源：http://dali.jqgufenzy.top/Article/details/gtmuoyivag.html

[S26] C：内存清零
来源：http://dali.vqdsnc.cn/Article/details/gtskdehgid.html

memset(a, 0, sizeof a);
来源：http://dali.daria6918.cn/Article/details/gtrqrhywfc.html

[S27] C：定义常量
来源：http://dali.jlsjyb.cn/Article/details/gthfescbig.html

const double PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gtxhtzxeuu.html

[S28] C：静态变量
来源：http://dali.vqdsnc.cn/Article/details/gteqpsdaxu.html

static int counter = 0;
来源：http://dali.316326.xyz/Article/details/gtwcfvcmfq.html

[S29] C：变参函数
来源：http://dali.shangyingyoupin.top/Article/details/gtomkpatwj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hysaishi.cn/Article/details/gtaxchgyef.html

[S30] C：头文件保护
来源：http://dali.pycfn.com/Article/details/gtoqlfffew.html

#ifndef X_H
来源：http://dali.svipenyu.cn/Article/details/gtedswdehl.html

#define X_H
来源：http://dali.xuetiantiany.cn/Article/details/gtrwolmnez.html

#endif
来源：http://dali.zhengqikj.top/Article/details/gtkibuaiyl.html

[S31] C++：Hello World
来源：http://dali.daria6918.cn/Article/details/gtxvomzdda.html

#include <iostream>
来源：http://dali.xuanzx.com/Article/details/gtlzvoudnj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.daxiang520.top/Article/details/gtqdizeapf.html

[S32] C++：字符串
来源：http://dali.gotoacloud.top/Article/details/gtqbjvuevj.html

std::string s = "hi";  s += "!";
来源：http://dali.hfpthk.cn/Article/details/gtmbijpdxz.html

[S33] C++：vector 增删
来源：http://dali.quarkkingdee.top/Article/details/gtisenxpdp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yueranfly.top/Article/details/gtvpwrnsbt.html

[S34] C++：遍历 vector
来源：http://dali.xylfe.cn/Article/details/gtejngasvo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtckgmjqnt.html

[S35] C++：map
来源：http://dali.zhongyouzk.top/Article/details/gtrkfpdhqh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gtfbtcmdli.html

[S36] C++：unordered_map
来源：http://dali.havefunace.top/Article/details/gttdhvyaog.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.mhx1999.top/Article/details/gtesbszvew.html

[S37] C++：set
来源：http://dali.xinyue.icu/Article/details/gtfizbhrbi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwxpgncwu.html

[S38] C++：排序
来源：http://dali.bjfxy.top/Article/details/gtdthbajki.html

std::sort(v.begin(), v.end());
来源：http://dali.cdnleiting.top/Article/details/gtfwcwdnqq.html

[S39] C++：自定义比较器排序
来源：http://dali.gogol.net.cn/Article/details/gtfwnmmeiv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sufxvd.cn/Article/details/gttmzcjpvc.html

[S40] C++：查找元素
来源：http://dali.dianchejie.cn/Article/details/gttjipkhga.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.guannengcc.top/Article/details/gtiexorxsx.html

[S41] C++：类与构造函数
来源：http://dali.mhx1999.top/Article/details/gttnwxqaae.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jiagoushi.top/Article/details/gtllevlivb.html

[S42] C++：继承与虚函数
来源：http://dali.zhixingplan.top/Article/details/gtdfjnyecv.html

class B : public Base { public: void f() override {} };
来源：http://dali.guannengcc.top/Article/details/gtldrlhapo.html

[S43] C++：智能指针
来源：http://dali.nwbrower.top/Article/details/gtpqkvpvid.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gtozrgoxqa.html

[S44] C++：引用传参
来源：http://dali.wangshuangyany.cn/Article/details/gtzgdxcbud.html

void inc(int &x) { ++x; }
来源：http://dali.dashuyun.cn/Article/details/gtfcqnblpk.html

[S45] C++：lambda
来源：http://dali.yuxming.cn/Article/details/gtejfgzliz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.pycfn.com/Article/details/gtwqpnyfrg.html

[S46] C++：函数模板
来源：http://dali.gogol.net.cn/Article/details/gtjcfjebxe.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.kuanghao11.cn/Article/details/gtveztyscs.html

[S47] C++：结构化绑定遍历
来源：http://dali.meibo888.top/Article/details/gtekkqxmbl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tianlin.xyz/Article/details/gtrnddocgy.html

[S48] C++：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gtootunayu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.redwolf501.top/Article/details/gtrpyvuynf.html

while (std::getline(in, line)) { }
来源：http://dali.jinqigufen.top/Article/details/gtzfouarvd.html

[S49] C++：写文件
来源：http://dali.wangshuangyany.cn/Article/details/gtshvexoir.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cashguo.top/Article/details/gtukshtgzp.html

[S50] C++：格式化数字
来源：http://dali.tian-w.cn/Article/details/gtdhxccpuw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sweek.top/Article/details/gtuagfghdv.html

[S51] C++：显式类型转换
来源：http://dali.yongpay.top/Article/details/gtkfzwktgp.html

static_cast<double>(a) / b
来源：http://dali.cheryme.top/Article/details/gtcgmoxqmw.html

[S52] C++：const 与 noexcept
来源：http://dali.zdqjudy.top/Article/details/gtxsjxsrsf.html

int size() const noexcept { return n_; }
来源：http://dali.hysaishi.cn/Article/details/gtodppdedk.html

[S53] C++：移动语义
来源：http://dali.xinyue.icu/Article/details/gtzelpfpbz.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gtsuxzvphb.html

[S54] C++：异常处理
来源：http://dali.yanxiufei.cn/Article/details/gtakxedvcv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhongyouzk.top/Article/details/gtkpnkfekj.html

[S55] C++：结构化绑定
来源：http://dali.bjfxy.top/Article/details/gtnhkteyla.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gtykjphnns.html

[S56] C++：optional
来源：http://dali.feifeiyinyue.top/Article/details/gtqdqraabh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nwbrower.top/Article/details/gtfhaxvnia.html

[S57] C++：编译期常量
来源：http://dali.ivvv.top/Article/details/gtvxslrffn.html

constexpr int N = 10;
来源：http://dali.birdmap.top/Article/details/gtsvxzebff.html

[S58] C++：命名空间
来源：http://dali.hongshengwenyu.top/Article/details/gtogkuujjt.html

namespace ns { int f() { return 1; } }
来源：http://dali.hongshengwenyu.top/Article/details/gttafowflr.html

[S59] C++：静态断言
来源：http://dali.chenzaomai.com/Article/details/gtzpsygzhy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.feifeiyinyue.top/Article/details/gtzgbuevxs.html

[S60] C++：遍历并删除元素
来源：http://dali.meibo888.top/Article/details/gtnhnfzlva.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hammf.cn/Article/details/gtlwtbpafn.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtgwxbiieb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhoulong.xyz/Article/details/gtyuauzsog.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtqosxfzmm.html

[T01] Kotlin：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtfmcoxvrg.html

println("Hello")
来源：http://dali.yj202588.top/Article/details/gtjmbbkbkl.html

[T02] Kotlin：变量
来源：http://dali.jinqigufen.top/Article/details/gtnbqjbmhe.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.snrcjt.cn/Article/details/gtlnwszaps.html

[T03] Kotlin：字符串模板
来源：http://dali.meibo888.top/Article/details/gtzxeucswv.html

"值: $b"
来源：http://dali.feifeiyinyue.top/Article/details/gtoawsvyuv.html

[T04] Kotlin：空安全
来源：http://dali.shuidangran.top/Article/details/gtprbhfrek.html

val n: String? = null;  n?.length
来源：http://dali.c1oappe.top/Article/details/gtlwodckzd.html

[T05] Kotlin：when 表达式
来源：http://dali.gotoacloud.top/Article/details/gtnntcqmxb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.bjfxy.top/Article/details/gtgafbcpik.html

[T06] Kotlin：集合映射
来源：http://dali.feifeiyinyue.top/Article/details/gtiobquhtu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.meibo888.top/Article/details/gtedqqaduz.html

[T07] Kotlin：集合过滤
来源：http://dali.hnqzz.top/Article/details/gtfagubhin.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jiagoushi.top/Article/details/gtzjmomqzg.html

[T08] Kotlin：数据类
来源：http://dali.hywenlv.cn/Article/details/gtuwdqxmrl.html

data class User(val name: String, val age: Int)
来源：http://dali.ppjwa.cn/Article/details/gtpvittvkc.html

[T09] Kotlin：扩展函数
来源：http://dali.tian-w.cn/Article/details/gtecokuwtn.html

fun String.exclaim() = this + "!"
来源：http://dali.cucudq.cn/Article/details/gtmgwplctt.html

[T10] Kotlin：默认参数
来源：http://dali.haohaochexian.top/Article/details/gtkwtvuueu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.guowangkeji.top/Article/details/gtxclahgap.html

[T11] Kotlin：协程
来源：http://dali.hysaishi.cn/Article/details/gtbjwbtcst.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xylfe.cn/Article/details/gthvuuqsgi.html

[T12] Kotlin：解构声明
来源：http://dali.jlsjyb.cn/Article/details/gtokeecgvq.html

val (a, b) = Pair(1, 2)
来源：http://dali.jyoumei.cn/Article/details/gtlvlknojk.html

[T13] Kotlin：只读 Map
来源：http://dali.cucudq.cn/Article/details/gtozfmlayg.html

val m = mapOf("a" to 1)
来源：http://dali.havefunace.top/Article/details/gtitggnypb.html

[T14] Kotlin：循环
来源：http://dali.xuanzx.com/Article/details/gthrzfbviv.html

for (i in 1..10) println(i)
来源：http://dali.nanxinkj.top/Article/details/gtvtaxckjw.html

[T15] Kotlin：接口
来源：http://dali.hnxiangtu.top/Article/details/gttevpuhvs.html

interface Shape { fun area(): Double }
来源：http://dali.xuanzx.com/Article/details/gtkkzogoxz.html

[T16] Swift：Hello World
来源：http://dali.jyoumei.cn/Article/details/gttapovwdp.html

print("Hello")
来源：http://dali.yuxming.cn/Article/details/gtjavexjyi.html

[T17] Swift：变量与常量
来源：http://dali.wangshuangyany.cn/Article/details/gtmtoskrfo.html

var a = 1;  let b = 2
来源：http://dali.cashguo.top/Article/details/gtyrwqfnhy.html

[T18] Swift：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gtbjoheopg.html

"值: \(b)"
来源：http://dali.dianchejie.cn/Article/details/gthwxyzmbr.html

[T19] Swift：可选绑定
来源：http://dali.yj20258.top/Article/details/gtdzcbrkab.html

if let n = opt { print(n) }
来源：http://dali.xinyue.icu/Article/details/gtotaqsoni.html

[T20] Swift：数组操作
来源：http://dali.tian-w.cn/Article/details/gtdsxgmxwu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jinqigfzy.top/Article/details/gtwcmlnenl.html

[T21] Swift：遍历
来源：http://dali.yuanzhike.top/Article/details/gtuumvboff.html

for x in a { print(x) }
来源：http://dali.jianghu66.top/Article/details/gtsplyksam.html

[T22] Swift：字典
来源：http://dali.xuetiantiany.cn/Article/details/gtyncaqxkw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xinyue.icu/Article/details/gthhphmdae.html

[T23] Swift：函数
来源：http://dali.sysykeji.top/Article/details/gthfgdsogc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xinyue.icu/Article/details/gtwkshojyg.html

[T24] Swift：闭包
来源：http://dali.xuetiantiany.cn/Article/details/gtazulfyty.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yvedp.cn/Article/details/gtcpavryha.html

[T25] Swift：结构体
来源：http://dali.xuanzx.com/Article/details/gtqqodpgbk.html

struct P { var x: Int }
来源：http://dali.cucudq.cn/Article/details/gtofxotmrd.html

[T26] Swift：类与重写
来源：http://dali.xylfe.cn/Article/details/gtuzyotepf.html

class A: Base { override func f() {} }
来源：http://dali.jqgfzy.top/Article/details/gtmhapvkgg.html

[T27] Swift：错误处理
来源：http://dali.hywenlv.cn/Article/details/gtrokbiado.html

do { try f() } catch { print(error) }
来源：http://dali.zycfv.cn/Article/details/gtusqzibrm.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gtgreijmyg.html

enum Color { case red, green }
来源：http://dali.chenlongwang.top/Article/details/gtktztfcpf.html

[T29] Swift：guard 提前返回
来源：http://dali.cheryme.top/Article/details/gtofpmlrna.html

guard let x = opt else { return }
来源：http://dali.nwbrower.top/Article/details/gtorkhqjfv.html

[T30] Swift：协议
来源：http://dali.cashguo.top/Article/details/gttudiyjjp.html

protocol Shape { func area() -> Double }
来源：http://dali.shzxlz.cn/Article/details/gtdvpnztua.html

[T31] Lua：Hello World
来源：http://dali.hammf.cn/Article/details/gtdhyqynwu.html

print("Hello")
来源：http://dali.cdnleiting.top/Article/details/gtidhsepjj.html

[T32] Lua：局部变量
来源：http://dali.smart0.xyz/Article/details/gtieofulsm.html

local a = 1
来源：http://dali.fengsongda.top/Article/details/gtrfiicwcx.html

[T33] Lua：表（数组）
来源：http://dali.aibaodan.cn/Article/details/gtlxrbbmtt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.andypj.xyz/Article/details/gtverdnbln.html

[T34] Lua：遍历表
来源：http://dali.daria6918.cn/Article/details/gtlmgkcywz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhixingplan.top/Article/details/gtddjshrjs.html

[T35] Lua：字典表
来源：http://dali.ybcxt.top/Article/details/gtdhbjrljs.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gogol.net.cn/Article/details/gtwxynlozl.html

[T36] Lua：函数
来源：http://dali.ppjwa.cn/Article/details/gtdwzmdtpd.html

function add(a, b) return a + b end
来源：http://dali.zhongyouzk.top/Article/details/gtfoioxgas.html

[T37] Lua：字符串拼接
来源：http://dali.svipenyu.cn/Article/details/gttbrqpvsf.html

"a" .. "b"
来源：http://dali.ehwqpu.com/Article/details/gtruqypzzd.html

[T38] Lua：条件
来源：http://dali.yvedp.cn/Article/details/gtzagqkenh.html

if x > 0 then print("正") end
来源：http://dali.zhaomingkeji.xyz/Article/details/gthhlloahh.html

[T39] Lua：模式匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtclonzrle.html

string.find(s, "%d+")
来源：http://dali.hywenlv.cn/Article/details/gtbcojfhvf.html

[T40] Lua：元表
来源：http://dali.tanke756.top/Article/details/gtevayjcsz.html

setmetatable({}, { __index = base })
来源：http://dali.cdnleiting.top/Article/details/gtvmnyjnmv.html

[T41] Perl：Hello World
来源：http://dali.shuidangran.top/Article/details/gtynrhaizo.html

print "Hello\n";
来源：http://dali.jianghu66.top/Article/details/gtnermgbzv.html

[T42] Perl：变量类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrqaxnhto.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shangyingyoupin.top/Article/details/gtejnkomze.html

[T43] Perl：字符串插值
来源：http://dali.zhiwuduotai.top/Article/details/gtkpobhwrc.html

"值: $a"
来源：http://dali.tianlin.xyz/Article/details/gtwfljvfuz.html

[T44] Perl：条件
来源：http://dali.cashguo.top/Article/details/gtgcxobtvu.html

if ($a > 0) { print "正"; }
来源：http://dali.cheryme.top/Article/details/gtzjnnvjoy.html

[T45] Perl：数组遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtvbxpsocc.html

for my $x (@arr) { print $x; }
来源：http://dali.hnxiangtu.top/Article/details/gtfrrzdtvt.html

[T46] Perl：哈希操作
来源：http://dali.jianghu66.top/Article/details/gtglbabqth.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyonxzuga.html

[T47] Perl：正则捕获
来源：http://dali.pengpengdd.cyou/Article/details/gtdwyvriju.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.havefunace.top/Article/details/gtnlljvvue.html

[T48] Perl：正则替换
来源：http://dali.sxryk.cn/Article/details/gtwwgnkagi.html

$s =~ s/old/new/g;
来源：http://dali.xinyue.icu/Article/details/gtnilbjtmo.html

[T49] Perl：函数
来源：http://dali.guannengcc.top/Article/details/gtyatmfdsz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sweek.top/Article/details/gtsxshhjno.html

[T50] Perl：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtihwzijwt.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yuxming.cn/Article/details/gthxuujqxw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.c1oappe.top/Article/details/gtlmtdknzb.html

[T51] Scala：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtfecpsipk.html

println("Hello")
来源：http://dali.ybcxt.top/Article/details/gtgkbqxatm.html

[T52] Scala：变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvodvjdnn.html

val a = 1;  var b = 2
来源：http://dali.jyoumei.cn/Article/details/gteryrgotg.html

[T53] Scala：字符串插值
来源：http://dali.yj202588.top/Article/details/gtmtptusiw.html

s"值: $b"
来源：http://dali.jianghu66.top/Article/details/gtxqddjodl.html

[T54] Scala：集合映射
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvniofuw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cdnleiting.top/Article/details/gtjnbmpazr.html

[T55] Scala：集合过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbcyfbhqz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbhhbouxn.html

[T56] Scala：样例类
来源：http://dali.bjfxy.top/Article/details/gtyrqanafp.html

case class User(name: String, age: Int)
来源：http://dali.sufxvd.cn/Article/details/gtgbllsidg.html

[T57] Scala：模式匹配
来源：http://dali.zycfv.cn/Article/details/gtxasttbju.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.haohaochexian.top/Article/details/gtwxlxhrby.html

[T58] Scala：函数定义
来源：http://dali.smart0.xyz/Article/details/gtqffzpfkx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.guowangkeji.top/Article/details/gtcnguvpoc.html

[T59] Scala：循环
来源：http://dali.hysaishi.cn/Article/details/gtycilvccc.html

for (i <- 1 to 10) println(i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgboncafa.html

[T60] Scala：折叠
来源：http://dali.kuanghao11.cn/Article/details/gtzfgwzqje.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yuanzhike.top/Article/details/gtrwkxtlyk.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtnsydxxfr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.316326.xyz/Article/details/gtssbcnmal.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtizprnsox.html

[U01] Py：创建虚拟环境
来源：http://dali.daxiang520.top/Article/details/gtcoewhcdf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.c1oappe.top/Article/details/gtzsmpxwru.html

[U02] Py：导出 / 安装依赖
来源：http://dali.daxiang520.top/Article/details/gttyiwbjuk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivadmbjd.html

[U03] Py：加载 .env 配置
来源：http://dali.ydzc1.top/Article/details/gtjrawbysu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsaaluuwn.html

[U04] Py：变量调试打印
来源：http://dali.yj20258.top/Article/details/gtgsmrcumj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.snrcjt.cn/Article/details/gtbwxwgveg.html

[U05] Py：列表去重且保序
来源：http://dali.jqgfzy.top/Article/details/gtrsflvfdu.html

list(dict.fromkeys(arr))
来源：http://dali.nanxinkj.top/Article/details/gtnitxmoil.html

[U06] Py：合并两个字典
来源：http://dali.jlsjyb.cn/Article/details/gtsctnuvws.html

{**a, **b}
来源：http://dali.hnqzz.top/Article/details/gtmukttnqn.html

[U07] Py：反转字典键值
来源：http://dali.feifeiyinyue.top/Article/details/gtqsgjfwkb.html

{v: k for k, v in d.items()}
来源：http://dali.guowangkeji.top/Article/details/gtwendxkfy.html

[U08] Py：展平二维列表
来源：http://dali.zhongyouzk.top/Article/details/gtgcjkotxk.html

[y for x in nested for y in x]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcqjzxkri.html

[U09] Py：字典取最大值的键
来源：http://dali.pycfn.com/Article/details/gtyrpuoznl.html

max(d, key=d.get)
来源：http://dali.cqqwz.cn/Article/details/gtpotjofxr.html

[U10] Py：按值排序字典
来源：http://dali.birdmap.top/Article/details/gtslyuwtmw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.316326.xyz/Article/details/gtvmlxwwez.html

[U11] Py：生成器表达式
来源：http://dali.smart0.xyz/Article/details/gtfdhulxzt.html

(x * 2 for x in arr)
来源：http://dali.yj202588.top/Article/details/gteshxzvmu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.chenjidiqi.icu/Article/details/gtkrnabeee.html

Counter(arr).most_common(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxqttcwec.html


<!-- 参考信息 -->