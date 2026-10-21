代发 wailian999

head -c 16 /dev/urandom | base64
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivassyja.html

[R70] 时间戳与互转
来源：http://dali.jinghuilouyu.cn/Article/details/gtpamobafy.html

date +%s;  date -d @1700000000
来源：http://dali.iojbl.cn/Article/details/gtddswduzb.html

[R71] 日期格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gtviarfcla.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.iojbl.cn/Article/details/gtgztrqlmk.html

[R72] 等待端口就绪
来源：http://dali.hongshengwenyu.top/Article/details/gtnuhzupla.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ivvv.top/Article/details/gtrktwgqag.html

[R73] 分割大日志
来源：http://dali.mhx1999.top/Article/details/gtlpwdiudc.html

split -l 1000 big.log part_
来源：http://dali.zdqjudy.top/Article/details/gtcvoeqvmr.html

[R74] 批量重命名
来源：http://dali.cucudq.cn/Article/details/gtsaqvmadf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.daria6918.cn/Article/details/gtivoyvtxm.html

[R75] 导出环境变量
来源：http://dali.quarkkingdee.top/Article/details/gtxthzgkyb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cashguo.top/Article/details/gtagafwdnq.html

[R76] 使用临时文件
来源：http://dali.smart0.xyz/Article/details/gtfvjpsgua.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.316326.xyz/Article/details/gtrwsoheea.html

[R77] 读取用户输入
来源：http://dali.wangshuangyany.cn/Article/details/gtgxsyywbx.html

read -rp "请输入: " ans
来源：http://dali.zhengqikj.top/Article/details/gttzzetdzf.html

[R78] 交互式菜单
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlgfqoslj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ivvv.top/Article/details/gtdabsvbrp.html

[R79] 解析命令行选项
来源：http://dali.quarkkingdee.top/Article/details/gtcbjugfhn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zycfv.cn/Article/details/gtaclscgrl.html

[R80] 查看脚本执行耗时
来源：http://dali.daxiang520.top/Article/details/gtqzqaegjt.html

time ./run.sh
来源：http://dali.gogol.net.cn/Article/details/gtpqqknzqj.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtswxqaoyf.html

S. C / C++ 专题
来源：http://dali.cucudq.cn/Article/details/gtxdwfebbv.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtsysoveub.html

[S01] C：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtrhrlcsqu.html

#include <stdio.h>
来源：http://dali.sufxvd.cn/Article/details/gtnwpzlibl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.birdmap.top/Article/details/gtudsugmtx.html

[S02] C：变量与格式化输出
来源：http://dali.snrcjt.cn/Article/details/gtyqztzwax.html

int a = 10; printf("%d\n", a);
来源：http://dali.guowangkeji.top/Article/details/gtbbodzufb.html

[S03] C：读入整数
来源：http://dali.yj20258.top/Article/details/gtaciykmsm.html

int x; scanf("%d", &x);
来源：http://dali.jqgfzy.top/Article/details/gtxezhohyz.html

[S04] C：字符串复制
来源：http://dali.shuidangran.top/Article/details/gtocogdsni.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.vqdsnc.cn/Article/details/gtmfugpbnl.html

[S05] C：字符串长度
来源：http://dali.yj20258.top/Article/details/gtkoeluqub.html

strlen(s)
来源：http://dali.zhixingplan.top/Article/details/gtsikkohub.html

[S06] C：字符串比较
来源：http://dali.wangshuangyany.cn/Article/details/gtzejwvukh.html

strcmp(a, b) == 0
来源：http://dali.pycfn.com/Article/details/gtnlwwlyqb.html

[S07] C：数组遍历求和
来源：http://dali.tanke756.top/Article/details/gtwblgzdly.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xinyue.icu/Article/details/gtjrggtsfx.html

[S08] C：动态内存分配与释放
来源：http://dali.yangfankeji.com/Article/details/gtdcapywma.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ivvv.top/Article/details/gtzzcrmhnc.html

[S09] C：结构体定义与初始化
来源：http://dali.hammf.cn/Article/details/gtyvusydhp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj20258.top/Article/details/gtbvoksyfx.html

[S10] C：指针与解引用
来源：http://dali.meibo888.top/Article/details/gtgbqeuute.html

int *p = &a;  *p = 5;
来源：http://dali.yanxiufei.cn/Article/details/gtktuuwjkb.html

[S11] C：逐行读文件
来源：http://dali.pycfn.com/Article/details/gtyfajvkrm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhixingplan.top/Article/details/gtasiestta.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.feifeiyinyue.top/Article/details/gtvtzfnaii.html

fclose(f);
来源：http://dali.sxryk.cn/Article/details/gtkqlskwhq.html

[S12] C：写文件
来源：http://dali.pycfn.com/Article/details/gtddpbflpc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jianghu66.top/Article/details/gtrtlqeunp.html

[S13] C：宏定义
来源：http://dali.svipenyu.cn/Article/details/gtdmxrkteq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hongshengwenyu.top/Article/details/gtgqdpogch.html

[S14] C：枚举
来源：http://dali.gotoacloud.top/Article/details/gtgaewoaji.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.feifeiyinyue.top/Article/details/gtlsbhfnzz.html

[S15] C：类型转换
来源：http://dali.chenlongwang.top/Article/details/gtxgiiceen.html

(double) a / b
来源：http://dali.jyoumei.cn/Article/details/gtcgttvosw.html

[S16] C：位操作置位
来源：http://dali.yj202588.top/Article/details/gtfijkfdvv.html

x |= (1 << 3);
来源：http://dali.vqdsnc.cn/Article/details/gtvfxshfle.html

[S17] C：安全拼接字符串
来源：http://dali.tanke756.top/Article/details/gtocggpzqj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gogol.net.cn/Article/details/gtocopanxc.html

[S18] C：命令行参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtbpfjzjcp.html

int main(int argc, char **argv)
来源：http://dali.mhx1999.top/Article/details/gthfsbwjwp.html

[S19] C：快速排序
来源：http://dali.yj20258.top/Article/details/gtkosqxhri.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gtneneacoa.html

[S20] C：二分查找
来源：http://dali.0kj1m.cn/Article/details/gtiuzvvmta.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhixingplan.top/Article/details/gtfpxifsuk.html

[S21] C：字符类别判断
来源：http://dali.andypj.xyz/Article/details/gtosljykde.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.dashuyun.cn/Article/details/gtvheozwyq.html

[S22] C：字符串转数字
来源：http://dali.ivvv.top/Article/details/gtsiuohmjc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.smart0.xyz/Article/details/gtosrulbpu.html

[S23] C：随机数
来源：http://dali.xuetiantiany.cn/Article/details/gthdtcuqgf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.snrcjt.cn/Article/details/gtigybyvti.html

[S24] C：获取本地时间
来源：http://dali.daxiang520.top/Article/details/gtvmqwkrbc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gzhubu.top/Article/details/gtsonhslov.html

[S25] C：内存拷贝
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnpynafbb.html

memcpy(dst, src, n);
来源：http://dali.yj20258888.top/Article/details/gticxgfwfh.html

[S26] C：内存清零
来源：http://dali.gaohongyu789.top/Article/details/gtlnyxzfvr.html

memset(a, 0, sizeof a);
来源：http://dali.hammf.cn/Article/details/gtvvxapwsm.html

[S27] C：定义常量
来源：http://dali.zhongyouzk.top/Article/details/gtbgyqfbfn.html

const double PI = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gtysnbhqap.html

[S28] C：静态变量
来源：http://dali.zhoulong.xyz/Article/details/gtyunbfzsz.html

static int counter = 0;
来源：http://dali.chenzaomai.com/Article/details/gtbcjbfcil.html

[S29] C：变参函数
来源：http://dali.xylfe.cn/Article/details/gtfsdlonly.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nanxinkj.top/Article/details/gtkxfhmndo.html

[S30] C：头文件保护
来源：http://dali.jinghuilouyu.cn/Article/details/gtfcajlckh.html

#ifndef X_H
来源：http://dali.smart0.xyz/Article/details/gtepejvnxt.html

#define X_H
来源：http://dali.zhoulong.xyz/Article/details/gtpigyqtgw.html

#endif
来源：http://dali.dashuyun.cn/Article/details/gtdjbkeuki.html

[S31] C++：Hello World
来源：http://dali.nwbrower.top/Article/details/gtaobtvgpn.html

#include <iostream>
来源：http://dali.nwbrower.top/Article/details/gtpijbumwv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zycfv.cn/Article/details/gtbemxjkyc.html

[S32] C++：字符串
来源：http://dali.0kj1m.cn/Article/details/gthhhrtqxz.html

std::string s = "hi";  s += "!";
来源：http://dali.vqdsnc.cn/Article/details/gtvtemlfmk.html

[S33] C++：vector 增删
来源：http://dali.cdnleiting.top/Article/details/gtvqazlsps.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtogqwovlg.html

[S34] C++：遍历 vector
来源：http://dali.yvedp.cn/Article/details/gtsjsbmnqc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhongyouzk.top/Article/details/gtbffujvvf.html

[S35] C++：map
来源：http://dali.ybcxt.top/Article/details/gtneiqzmkp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gtthhalirn.html

[S36] C++：unordered_map
来源：http://dali.gaohongyu789.top/Article/details/gtbftcpckr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xylfe.cn/Article/details/gtsxasuyab.html

[S37] C++：set
来源：http://dali.yangfankeji.com/Article/details/gtvrhlwmgv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.kuanghao11.cn/Article/details/gtmgqtltmz.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gtpntlilhw.html

std::sort(v.begin(), v.end());
来源：http://dali.ybcxt.top/Article/details/gtdbggmutu.html

[S39] C++：自定义比较器排序
来源：http://dali.yanxiufei.cn/Article/details/gtlwnfmekz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ppjwa.cn/Article/details/gtsctgrnpf.html

[S40] C++：查找元素
来源：http://dali.smart0.xyz/Article/details/gtyazdbhch.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenzaomai.com/Article/details/gtdlxrbilb.html

[S41] C++：类与构造函数
来源：http://dali.pycfn.com/Article/details/gtcclpazqk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtohsopswc.html

[S42] C++：继承与虚函数
来源：http://dali.hfpthk.cn/Article/details/gtaanffvpz.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj20258888.top/Article/details/gtgemartnb.html

[S43] C++：智能指针
来源：http://dali.chenlongwang.top/Article/details/gtlegngzpu.html

auto p = std::make_unique<int>(5);
来源：http://dali.gogol.net.cn/Article/details/gtmwxarwfw.html

[S44] C++：引用传参
来源：http://dali.ywan-chungtsiang.top/Article/details/gtafdyxvxx.html

void inc(int &x) { ++x; }
来源：http://dali.nanxuanxn.top/Article/details/gtqhmzwmyi.html

[S45] C++：lambda
来源：http://dali.yueranfly.top/Article/details/gtrfpqbcmr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.daxiang520.top/Article/details/gtqbrzzpko.html

[S46] C++：函数模板
来源：http://dali.jinqigfzy.top/Article/details/gthgmevdds.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhongyouzk.top/Article/details/gtlrjmpjms.html

[S47] C++：结构化绑定遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtzqwjsjtt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shangyingyoupin.top/Article/details/gtystbjldw.html

[S48] C++：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaofhhuol.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hongshengwenyu.top/Article/details/gtyihjnyhb.html

while (std::getline(in, line)) { }
来源：http://dali.iojbl.cn/Article/details/gttyttkxzu.html

[S49] C++：写文件
来源：http://dali.vqdsnc.cn/Article/details/gtpnbxqkzt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.9152youxi.cn/Article/details/gtbsjiiqat.html

[S50] C++：格式化数字
来源：http://dali.tian-w.cn/Article/details/gtraxkaazo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jianghu66.top/Article/details/gttibaaqtr.html

[S51] C++：显式类型转换
来源：http://dali.hywenlv.cn/Article/details/gtlmbcbppn.html

static_cast<double>(a) / b
来源：http://dali.yonumen.top/Article/details/gtawxomwwi.html

[S52] C++：const 与 noexcept
来源：http://dali.shzxlz.cn/Article/details/gtvoagrxlm.html

int size() const noexcept { return n_; }
来源：http://dali.yongpay.top/Article/details/gtglyxzwha.html

[S53] C++：移动语义
来源：http://dali.yj202588.top/Article/details/gtreffksht.html

std::vector<int> w = std::move(v);
来源：http://dali.nanxinkj.top/Article/details/gtciqbmgvw.html

[S54] C++：异常处理
来源：http://dali.yueranfly.top/Article/details/gtwclwqvgl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenjidiqi.icu/Article/details/gtydqyqtuh.html

[S55] C++：结构化绑定
来源：http://dali.cqqwz.cn/Article/details/gtpjxtnecd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hywenlv.cn/Article/details/gthytrqwaq.html

[S56] C++：optional
来源：http://dali.pycfn.com/Article/details/gtjpurajut.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yuanzhike.top/Article/details/gtvkdjtwly.html

[S57] C++：编译期常量
来源：http://dali.gotoacloud.top/Article/details/gtsqxbwjly.html

constexpr int N = 10;
来源：http://dali.chenlongwang.top/Article/details/gtryrktvtx.html

[S58] C++：命名空间
来源：http://dali.zhongyouzk.top/Article/details/gtbrgqmyny.html

namespace ns { int f() { return 1; } }
来源：http://dali.smart0.xyz/Article/details/gtxlovrjer.html

[S59] C++：静态断言
来源：http://dali.havefunace.top/Article/details/gtdkuclywy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinghuilouyu.cn/Article/details/gtfnabzjyc.html

[S60] C++：遍历并删除元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfjzurhcl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenjidiqi.icu/Article/details/gtkoxgzbfk.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtohkfcocl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenjidiqi.icu/Article/details/gtghupxtof.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtsjvaqaqg.html

[T01] Kotlin：Hello World
来源：http://dali.xuanzx.com/Article/details/gtwvrkgfro.html

println("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gtavjiwete.html

[T02] Kotlin：变量
来源：http://dali.iojbl.cn/Article/details/gttqgcbacl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sufxvd.cn/Article/details/gtvdohdmmh.html

[T03] Kotlin：字符串模板
来源：http://dali.chenzaomai.com/Article/details/gtvhullckw.html

"值: $b"
来源：http://dali.jinghuilouyu.cn/Article/details/gtebceeuxr.html

[T04] Kotlin：空安全
来源：http://dali.shanyushiyangtech.top/Article/details/gtdwqyimbt.html

val n: String? = null;  n?.length
来源：http://dali.hongshengwenyu.top/Article/details/gtuyojnlwo.html

[T05] Kotlin：when 表达式
来源：http://dali.tanke756.top/Article/details/gtvbltcixk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.fengsongda.top/Article/details/gtleumowae.html

[T06] Kotlin：集合映射
来源：http://dali.chenzaomai.com/Article/details/gtfyzufznu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hammf.cn/Article/details/gtmbmqzkha.html

[T07] Kotlin：集合过滤
来源：http://dali.hongshengwenyu.top/Article/details/gtvhqunfde.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.daria6918.cn/Article/details/gtnaetwzac.html

[T08] Kotlin：数据类
来源：http://dali.guowangkeji.top/Article/details/gtdpngpkcj.html

data class User(val name: String, val age: Int)
来源：http://dali.mhx1999.top/Article/details/gtkcwpgbnb.html

[T09] Kotlin：扩展函数
来源：http://dali.shangyingyoupin.top/Article/details/gtjbcumrnd.html

fun String.exclaim() = this + "!"
来源：http://dali.wangdashe.top/Article/details/gtoppkyqnp.html

[T10] Kotlin：默认参数
来源：http://dali.mhx1999.top/Article/details/gtzbfdgszt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sufxvd.cn/Article/details/gtagdxjgop.html

[T11] Kotlin：协程
来源：http://dali.hammf.cn/Article/details/gtkfnfaems.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hfpthk.cn/Article/details/gtdgscsjvl.html

[T12] Kotlin：解构声明
来源：http://dali.aibaodan.cn/Article/details/gtifbgkngp.html

val (a, b) = Pair(1, 2)
来源：http://dali.c1oappe.top/Article/details/gtkgwnuzih.html

[T13] Kotlin：只读 Map
来源：http://dali.cqqwz.cn/Article/details/gtfeneceek.html

val m = mapOf("a" to 1)
来源：http://dali.havefunace.top/Article/details/gtxfsskwxm.html

[T14] Kotlin：循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmihhkwpn.html

for (i in 1..10) println(i)
来源：http://dali.vqdsnc.cn/Article/details/gtznfxkpbm.html

[T15] Kotlin：接口
来源：http://dali.hammf.cn/Article/details/gttcwvquob.html

interface Shape { fun area(): Double }
来源：http://dali.jqgfzy.top/Article/details/gtcwobkwrp.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtzmixjskf.html

print("Hello")
来源：http://dali.aibaodan.cn/Article/details/gtcpbhocik.html

[T17] Swift：变量与常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvxozsggl.html

var a = 1;  let b = 2
来源：http://dali.smart0.xyz/Article/details/gtbfteeleq.html

[T18] Swift：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gtwfewdrkq.html

"值: \(b)"
来源：http://dali.jinghuilouyu.cn/Article/details/gtxobcmxki.html

[T19] Swift：可选绑定
来源：http://dali.yvedp.cn/Article/details/gthlmliang.html

if let n = opt { print(n) }
来源：http://dali.gzhubu.top/Article/details/gtskmaaefx.html

[T20] Swift：数组操作
来源：http://dali.yj20258888.top/Article/details/gtyrcecupu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.pengpengdd.cyou/Article/details/gtrzancjti.html

[T21] Swift：遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gthrvlltsm.html

for x in a { print(x) }
来源：http://dali.gaohongyu789.top/Article/details/gtwxwpelfv.html

[T22] Swift：字典
来源：http://dali.haohaochexian.top/Article/details/gtynwdboht.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gotoacloud.top/Article/details/gtqtpwtktm.html

[T23] Swift：函数
来源：http://dali.fzhhl.top/Article/details/gtkmviwzci.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gotoacloud.top/Article/details/gtgtdahmhg.html

[T24] Swift：闭包
来源：http://dali.shuidangran.top/Article/details/gtxheobdqr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzuxrgvge.html

[T25] Swift：结构体
来源：http://dali.zycfv.cn/Article/details/gthjsiuaxn.html

struct P { var x: Int }
来源：http://dali.yueranfly.top/Article/details/gtquhuhthv.html

[T26] Swift：类与重写
来源：http://dali.c1oappe.top/Article/details/gtfftqqcfe.html

class A: Base { override func f() {} }
来源：http://dali.wangdashe.top/Article/details/gtaqchocgj.html

[T27] Swift：错误处理
来源：http://dali.cucudq.cn/Article/details/gtkrvtuiwc.html

do { try f() } catch { print(error) }
来源：http://dali.cucudq.cn/Article/details/gtbthvlbqi.html

[T28] Swift：枚举
来源：http://dali.yuxming.cn/Article/details/gtltzyimhd.html

enum Color { case red, green }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoirbtncg.html

[T29] Swift：guard 提前返回
来源：http://dali.smart0.xyz/Article/details/gttlfskjdx.html

guard let x = opt else { return }
来源：http://dali.yueranfly.top/Article/details/gtoxnelvey.html

[T30] Swift：协议
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfkoflmqg.html

protocol Shape { func area() -> Double }
来源：http://dali.fzhhl.top/Article/details/gtijpyrwfk.html

[T31] Lua：Hello World
来源：http://dali.jianghu66.top/Article/details/gtnyzqkgee.html

print("Hello")
来源：http://dali.zdqjudy.top/Article/details/gtcihqwajb.html

[T32] Lua：局部变量
来源：http://dali.gotoacloud.top/Article/details/gtysqoxned.html

local a = 1
来源：http://dali.fzhhl.top/Article/details/gtkyrvzibj.html

[T33] Lua：表（数组）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqfewthru.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yuanzhike.top/Article/details/gtpivayava.html

[T34] Lua：遍历表
来源：http://dali.wangdashe.top/Article/details/gtarewkdac.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jqgfzy.top/Article/details/gtfwxigxuf.html

[T35] Lua：字典表
来源：http://dali.sufxvd.cn/Article/details/gtyesnsnzi.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gogol.net.cn/Article/details/gtbbcwlytp.html

[T36] Lua：函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgieuaikx.html

function add(a, b) return a + b end
来源：http://dali.316326.xyz/Article/details/gtiekitvsw.html

[T37] Lua：字符串拼接
来源：http://dali.zdqjudy.top/Article/details/gtduehviks.html

"a" .. "b"
来源：http://dali.zdqjudy.top/Article/details/gtvylykbbv.html

[T38] Lua：条件
来源：http://dali.sufxvd.cn/Article/details/gtxwkwqkax.html

if x > 0 then print("正") end
来源：http://dali.sysykeji.top/Article/details/gtxsfdciin.html

[T39] Lua：模式匹配
来源：http://dali.ybcxt.top/Article/details/gtftwgsovd.html

string.find(s, "%d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtklhtxled.html

[T40] Lua：元表
来源：http://dali.zycfv.cn/Article/details/gtaepnwlxw.html

setmetatable({}, { __index = base })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxanlgpbx.html

[T41] Perl：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtrgucrqhh.html

print "Hello\n";
来源：http://dali.wangshuangyany.cn/Article/details/gtdpijjygj.html

[T42] Perl：变量类型
来源：http://dali.tanke756.top/Article/details/gtkmxkrbfo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthljkejyp.html

[T43] Perl：字符串插值
来源：http://dali.sufxvd.cn/Article/details/gthbxnvtyx.html

"值: $a"
来源：http://dali.yj20258.top/Article/details/gtbobulihr.html

[T44] Perl：条件
来源：http://dali.zhongyouzk.top/Article/details/gtprppcogk.html

if ($a > 0) { print "正"; }
来源：http://dali.aibaodan.cn/Article/details/gthsicxgcg.html

[T45] Perl：数组遍历
来源：http://dali.jinqigufen.top/Article/details/gtygxybcma.html

for my $x (@arr) { print $x; }
来源：http://dali.cheryme.top/Article/details/gtihrzyfgd.html

[T46] Perl：哈希操作
来源：http://dali.ybcxt.top/Article/details/gtxuxpitxn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzfcchgaf.html

[T47] Perl：正则捕获
来源：http://dali.ehwqpu.com/Article/details/gtlahfoduf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.guannengcc.top/Article/details/gtnjcdkjwf.html

[T48] Perl：正则替换
来源：http://dali.yanxiufei.cn/Article/details/gtuohgpmvp.html

$s =~ s/old/new/g;
来源：http://dali.yanxiufei.cn/Article/details/gtlfmuocvr.html

[T49] Perl：函数
来源：http://dali.jqgfzy.top/Article/details/gtldzlewvp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yvedp.cn/Article/details/gtfrodboey.html

[T50] Perl：逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gtsgcqzycm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.wangshuangyany.cn/Article/details/gtcylnaigc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.c1oappe.top/Article/details/gtahxthxru.html

[T51] Scala：Hello World
来源：http://dali.smart0.xyz/Article/details/gtepxxqwxw.html

println("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gtogtnoors.html

[T52] Scala：变量
来源：http://dali.jqgfzy.top/Article/details/gtgfbqkoyc.html

val a = 1;  var b = 2
来源：http://dali.jianghu66.top/Article/details/gtxqerurlu.html

[T53] Scala：字符串插值
来源：http://dali.bjfxy.top/Article/details/gtamfgetnf.html

s"值: $b"
来源：http://dali.tanke756.top/Article/details/gtebkoeuxj.html

[T54] Scala：集合映射
来源：http://dali.nanxinkj.top/Article/details/gtqezolhpj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.aizwys.cn/Article/details/gtbegipqpj.html

[T55] Scala：集合过滤
来源：http://dali.yj202588.top/Article/details/gtcjstljeq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sxryk.cn/Article/details/gtygdbkbyh.html

[T56] Scala：样例类
来源：http://dali.hfpthk.cn/Article/details/gtthdcrqcc.html

case class User(name: String, age: Int)
来源：http://dali.0kj1m.cn/Article/details/gtzcpwdrqt.html

[T57] Scala：模式匹配
来源：http://dali.316326.xyz/Article/details/gtldqchiva.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cheryme.top/Article/details/gtdwslktxa.html

[T58] Scala：函数定义
来源：http://dali.dianchejie.cn/Article/details/gtflkwjgaj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhongyouzk.top/Article/details/gtnaiaevfy.html

[T59] Scala：循环
来源：http://dali.ehwqpu.com/Article/details/gtbolkbugv.html

for (i <- 1 to 10) println(i)
来源：http://dali.tian-w.cn/Article/details/gtxcqddsmu.html

[T60] Scala：折叠
来源：http://dali.jqgfzy.top/Article/details/gtfaybmrmi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jlsjyb.cn/Article/details/gtotaaeirm.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtnhjpwzxw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ivvv.top/Article/details/gtqkkuqsmb.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtsuvudpbb.html

[U01] Py：创建虚拟环境
来源：http://dali.mhx1999.top/Article/details/gtekgclfng.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jinghuilouyu.cn/Article/details/gtkyedctsf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.chenlongwang.top/Article/details/gtpvefuwue.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhoulong.xyz/Article/details/gtwxzarsyl.html

[U03] Py：加载 .env 配置
来源：http://dali.c1oappe.top/Article/details/gtfsuzccaj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.daxiang520.top/Article/details/gtutokvahf.html

[U04] Py：变量调试打印
来源：http://dali.iojbl.cn/Article/details/gtlgifsttz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xuetiantiany.cn/Article/details/gtntlekiyv.html

[U05] Py：列表去重且保序
来源：http://dali.redwolf501.top/Article/details/gtisbudeaf.html

list(dict.fromkeys(arr))
来源：http://dali.smart0.xyz/Article/details/gteqczcppc.html

[U06] Py：合并两个字典
来源：http://dali.cdnleiting.top/Article/details/gtdxipcbaw.html

{**a, **b}
来源：http://dali.pycfn.com/Article/details/gtptexlpbz.html

[U07] Py：反转字典键值
来源：http://dali.ehwqpu.com/Article/details/gthkzqjtze.html

{v: k for k, v in d.items()}
来源：http://dali.xuanzx.com/Article/details/gtidznzlbl.html

[U08] Py：展平二维列表
来源：http://dali.dianchejie.cn/Article/details/gtftrhlyzp.html

[y for x in nested for y in x]
来源：http://dali.pycfn.com/Article/details/gtkcqfyfit.html

[U09] Py：字典取最大值的键
来源：http://dali.jiagoushi.top/Article/details/gtjufkekor.html

max(d, key=d.get)
来源：http://dali.0kj1m.cn/Article/details/gthjqpqtgt.html

[U10] Py：按值排序字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgppyqewn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhixingplan.top/Article/details/gtuzflxdja.html


<!-- 参考信息 -->