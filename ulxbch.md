代发 wailian999

head -c 16 /dev/urandom | base64
来源：http://dali.aibaodan.cn/Article/details/gtkcsztcab.html

[R70] 时间戳与互转
来源：http://dali.xylfe.cn/Article/details/gtsbtaefjq.html

date +%s;  date -d @1700000000
来源：http://dali.xylfe.cn/Article/details/gtyfqgvmqp.html

[R71] 日期格式化
来源：http://dali.yanxiufei.cn/Article/details/gtztxxghjt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.snrcjt.cn/Article/details/gtgbqdddnh.html

[R72] 等待端口就绪
来源：http://dali.xylfe.cn/Article/details/gtycbqefay.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yonumen.top/Article/details/gtkcueagqh.html

[R73] 分割大日志
来源：http://dali.bjfxy.top/Article/details/gtindidvlr.html

split -l 1000 big.log part_
来源：http://dali.c1oappe.top/Article/details/gtimcrvznx.html

[R74] 批量重命名
来源：http://dali.yuxming.cn/Article/details/gtgtdmuozt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hfpthk.cn/Article/details/gtfjsffrgn.html

[R75] 导出环境变量
来源：http://dali.xziqi.cn/Article/details/gtluwwztuu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenjidiqi.icu/Article/details/gtgzckhncs.html

[R76] 使用临时文件
来源：http://dali.jqgfzy.top/Article/details/gtrnzqjqlc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shanyushiyangtech.top/Article/details/gtxapzdleb.html

[R77] 读取用户输入
来源：http://dali.yueranfly.top/Article/details/gtsdittkwo.html

read -rp "请输入: " ans
来源：http://dali.nanxuanxn.top/Article/details/gtntnqpgal.html

[R78] 交互式菜单
来源：http://dali.quarkkingdee.top/Article/details/gtgyxmjeii.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yuxming.cn/Article/details/gtorlvoofp.html

[R79] 解析命令行选项
来源：http://dali.bjfxy.top/Article/details/gtwtlohuzy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.fengsongda.top/Article/details/gtpfdwpbzn.html

[R80] 查看脚本执行耗时
来源：http://dali.hysaishi.cn/Article/details/gtdqmqjkom.html

time ./run.sh
来源：http://dali.tanke756.top/Article/details/gtcxscwtib.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtoisimmwq.html

S. C / C++ 专题
来源：http://dali.shuidangran.top/Article/details/gtkdqsrjci.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtejyzcrqa.html

[S01] C：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxmpzhsm.html

#include <stdio.h>
来源：http://dali.ehwqpu.com/Article/details/gtgvqzggvl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sweek.top/Article/details/gtbnnxtboa.html

[S02] C：变量与格式化输出
来源：http://dali.hysaishi.cn/Article/details/gtileclcvy.html

int a = 10; printf("%d\n", a);
来源：http://dali.hnxiangtu.top/Article/details/gtxyzyijzf.html

[S03] C：读入整数
来源：http://dali.pycfn.com/Article/details/gtiqtdnbkw.html

int x; scanf("%d", &x);
来源：http://dali.316326.xyz/Article/details/gtqpjuuyxt.html

[S04] C：字符串复制
来源：http://dali.xinyue.icu/Article/details/gthascwfid.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.dashuyun.cn/Article/details/gtpsuglark.html

[S05] C：字符串长度
来源：http://dali.yanxiufei.cn/Article/details/gtpgbkgbgp.html

strlen(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtevnvxysc.html

[S06] C：字符串比较
来源：http://dali.yongpay.top/Article/details/gthxyuellg.html

strcmp(a, b) == 0
来源：http://dali.ybcxt.top/Article/details/gtnqdgfiid.html

[S07] C：数组遍历求和
来源：http://dali.sysykeji.top/Article/details/gttytysmtp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.aibaodan.cn/Article/details/gtezjrdijk.html

[S08] C：动态内存分配与释放
来源：http://dali.tianlin.xyz/Article/details/gtbthcpevf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenlongwang.top/Article/details/gtnuvoukbw.html

[S09] C：结构体定义与初始化
来源：http://dali.chenlongwang.top/Article/details/gtlbxbaawe.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ybcxt.top/Article/details/gtkfrrbyhc.html

[S10] C：指针与解引用
来源：http://dali.xuetiantiany.cn/Article/details/gtxareceir.html

int *p = &a;  *p = 5;
来源：http://dali.yj20258888.top/Article/details/gtcxkdfwst.html

[S11] C：逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gtfqnnklqx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jiagoushi.top/Article/details/gtulvbdebj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gtdjoxumit.html

fclose(f);
来源：http://dali.shangyingyoupin.top/Article/details/gtizlqzilb.html

[S12] C：写文件
来源：http://dali.zhongyouzk.top/Article/details/gtukwbxqzj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.vqdsnc.cn/Article/details/gtsrdzdvha.html

[S13] C：宏定义
来源：http://dali.shzxlz.cn/Article/details/gtvtxzhwps.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.svipenyu.cn/Article/details/gtowhnnqzr.html

[S14] C：枚举
来源：http://dali.guowangkeji.top/Article/details/gtpexsviqq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhiwuduotai.top/Article/details/gtiiyxevjt.html

[S15] C：类型转换
来源：http://dali.zhiwuduotai.top/Article/details/gthommrgic.html

(double) a / b
来源：http://dali.daria6918.cn/Article/details/gtymrgnrpf.html

[S16] C：位操作置位
来源：http://dali.gogol.net.cn/Article/details/gtiwozszgu.html

x |= (1 << 3);
来源：http://dali.daria6918.cn/Article/details/gttwttvhoi.html

[S17] C：安全拼接字符串
来源：http://dali.gzhubu.top/Article/details/gtitnshyvx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.fengsongda.top/Article/details/gtxetqllxf.html

[S18] C：命令行参数
来源：http://dali.cqqwz.cn/Article/details/gtsfmjgzjd.html

int main(int argc, char **argv)
来源：http://dali.birdmap.top/Article/details/gtuwwayxtt.html

[S19] C：快速排序
来源：http://dali.gogol.net.cn/Article/details/gtmkiaqizx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhongyouzk.top/Article/details/gtbsvwimua.html

[S20] C：二分查找
来源：http://dali.shzxlz.cn/Article/details/gtrffxomgm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.aizwys.cn/Article/details/gtbfoiphjd.html

[S21] C：字符类别判断
来源：http://dali.sxryk.cn/Article/details/gtqllaspfl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhoulong.xyz/Article/details/gtspwnbnci.html

[S22] C：字符串转数字
来源：http://dali.yuxming.cn/Article/details/gtimdltxai.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hnxiangtu.top/Article/details/gtugipufjv.html

[S23] C：随机数
来源：http://dali.chenzaomai.com/Article/details/gtkkielxlh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xuanzx.com/Article/details/gttkdbzijr.html

[S24] C：获取本地时间
来源：http://dali.shangyingyoupin.top/Article/details/gtqkzzbifc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.andypj.xyz/Article/details/gtfwphzvso.html

[S25] C：内存拷贝
来源：http://dali.andypj.xyz/Article/details/gtcrbtftmc.html

memcpy(dst, src, n);
来源：http://dali.shzxlz.cn/Article/details/gtryyjtshn.html

[S26] C：内存清零
来源：http://dali.kuanghao11.cn/Article/details/gtdehvzsau.html

memset(a, 0, sizeof a);
来源：http://dali.gogol.net.cn/Article/details/gtiwtldsop.html

[S27] C：定义常量
来源：http://dali.hnxiangtu.top/Article/details/gtggwvqgbh.html

const double PI = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gtutgejvfw.html

[S28] C：静态变量
来源：http://dali.wangshuangyany.cn/Article/details/gtipquknuc.html

static int counter = 0;
来源：http://dali.jqgufenzy.top/Article/details/gtrlljfxde.html

[S29] C：变参函数
来源：http://dali.havefunace.top/Article/details/gtthqmxrre.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jqgufenzy.top/Article/details/gtiwobtpoj.html

[S30] C：头文件保护
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtswptacpk.html

#ifndef X_H
来源：http://dali.jinyuanbaomall.cn/Article/details/gtppmvcbsx.html

#define X_H
来源：http://dali.nwbrower.top/Article/details/gtkxwskhgo.html

#endif
来源：http://dali.jinqigufen.top/Article/details/gtrrnydszg.html

[S31] C++：Hello World
来源：http://dali.smart0.xyz/Article/details/gtvtgqjelk.html

#include <iostream>
来源：http://dali.hongshengwenyu.top/Article/details/gtuqhafvzy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nanxinkj.top/Article/details/gtfjjkblkn.html

[S32] C++：字符串
来源：http://dali.yanxiufei.cn/Article/details/gthhlemffk.html

std::string s = "hi";  s += "!";
来源：http://dali.daria6918.cn/Article/details/gtjefzgzsx.html

[S33] C++：vector 增删
来源：http://dali.xziqi.cn/Article/details/gtfplgcsbf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cucudq.cn/Article/details/gtpoplrvxn.html

[S34] C++：遍历 vector
来源：http://dali.yuanzhike.top/Article/details/gtbqwrjgom.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.c1oappe.top/Article/details/gtouyuflzn.html

[S35] C++：map
来源：http://dali.fzhhl.top/Article/details/gtgugipejg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.birdmap.top/Article/details/gtshsutruq.html

[S36] C++：unordered_map
来源：http://dali.sysykeji.top/Article/details/gtphxemkoe.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuanzx.com/Article/details/gtzhucntkk.html

[S37] C++：set
来源：http://dali.yanxiufei.cn/Article/details/gtskjkrtqv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.daria6918.cn/Article/details/gteazggpwh.html

[S38] C++：排序
来源：http://dali.cdnleiting.top/Article/details/gtakpgsyza.html

std::sort(v.begin(), v.end());
来源：http://dali.vqdsnc.cn/Article/details/gtrteovaqd.html

[S39] C++：自定义比较器排序
来源：http://dali.birdmap.top/Article/details/gtqndaxcog.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nwbrower.top/Article/details/gtpqlzxhiu.html

[S40] C++：查找元素
来源：http://dali.yj20258888.top/Article/details/gtiwuzmuaw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.havefunace.top/Article/details/gtfnbtgqwj.html

[S41] C++：类与构造函数
来源：http://dali.ybcxt.top/Article/details/gtfpkrvrrd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jqgfzy.top/Article/details/gttydemlsw.html

[S42] C++：继承与虚函数
来源：http://dali.dashuyun.cn/Article/details/gtyekcudvz.html

class B : public Base { public: void f() override {} };
来源：http://dali.hnqzz.top/Article/details/gtqrsrokhn.html

[S43] C++：智能指针
来源：http://dali.jyoumei.cn/Article/details/gtfspgntmy.html

auto p = std::make_unique<int>(5);
来源：http://dali.pengpengdd.cyou/Article/details/gtzdfekcyq.html

[S44] C++：引用传参
来源：http://dali.ehwqpu.com/Article/details/gtomgykkck.html

void inc(int &x) { ++x; }
来源：http://dali.guannengcc.top/Article/details/gtgpfupxju.html

[S45] C++：lambda
来源：http://dali.guannengcc.top/Article/details/gtupgspars.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xziqi.cn/Article/details/gteqrtrdlo.html

[S46] C++：函数模板
来源：http://dali.nwbrower.top/Article/details/gtkhjlsnnn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtpdzzfowe.html

[S47] C++：结构化绑定遍历
来源：http://dali.cheryme.top/Article/details/gtjgngrolw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.wangdashe.top/Article/details/gtbcmosdgt.html

[S48] C++：逐行读文件
来源：http://dali.yonumen.top/Article/details/gtgbqeqdtp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yuanzhike.top/Article/details/gtqhgnqarc.html

while (std::getline(in, line)) { }
来源：http://dali.hywenlv.cn/Article/details/gtrwjyutan.html

[S49] C++：写文件
来源：http://dali.yj202588.top/Article/details/gthcmczzic.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.9152youxi.cn/Article/details/gthnexumin.html

[S50] C++：格式化数字
来源：http://dali.gzhubu.top/Article/details/gtwjcrjrav.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sweek.top/Article/details/gtvxqvwqzw.html

[S51] C++：显式类型转换
来源：http://dali.hfpthk.cn/Article/details/gtnrtjhuzv.html

static_cast<double>(a) / b
来源：http://dali.nanxuanxn.top/Article/details/gtdnuuffxb.html

[S52] C++：const 与 noexcept
来源：http://dali.gotoacloud.top/Article/details/gtysxwudsr.html

int size() const noexcept { return n_; }
来源：http://dali.sufxvd.cn/Article/details/gtzgdsahxb.html

[S53] C++：移动语义
来源：http://dali.yonumen.top/Article/details/gtzfpfkgnl.html

std::vector<int> w = std::move(v);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlrlpoyza.html

[S54] C++：异常处理
来源：http://dali.wangdashe.top/Article/details/gtyhsiyyry.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jiagoushi.top/Article/details/gtvabciteq.html

[S55] C++：结构化绑定
来源：http://dali.hnxiangtu.top/Article/details/gtpkgohrma.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zycfv.cn/Article/details/gtzaeheqwq.html

[S56] C++：optional
来源：http://dali.tian-w.cn/Article/details/gtohrkkaur.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfljslela.html

[S57] C++：编译期常量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnzughtop.html

constexpr int N = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gtrjvdzktn.html

[S58] C++：命名空间
来源：http://dali.zhixingplan.top/Article/details/gtzrmjhols.html

namespace ns { int f() { return 1; } }
来源：http://dali.ybcxt.top/Article/details/gtzdvwjmhf.html

[S59] C++：静态断言
来源：http://dali.ivvv.top/Article/details/gtbgoeydrw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.chenjidiqi.icu/Article/details/gtzzqimkmn.html

[S60] C++：遍历并删除元素
来源：http://dali.zdqjudy.top/Article/details/gtmclwpqwv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.dianchejie.cn/Article/details/gtkoztqlio.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtsfrtdjni.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shzxlz.cn/Article/details/gttjdiffmi.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtmvqyfyvr.html

[T01] Kotlin：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtbjsihqfi.html

println("Hello")
来源：http://dali.gzhubu.top/Article/details/gtqqybsdkw.html

[T02] Kotlin：变量
来源：http://dali.sxryk.cn/Article/details/gtuebosrbg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tanke756.top/Article/details/gtrdasrolj.html

[T03] Kotlin：字符串模板
来源：http://dali.fzhhl.top/Article/details/gtuavuvixp.html

"值: $b"
来源：http://dali.yanxiufei.cn/Article/details/gtdmlfnnvn.html

[T04] Kotlin：空安全
来源：http://dali.xuanzx.com/Article/details/gtlmrwuwjx.html

val n: String? = null;  n?.length
来源：http://dali.aibaodan.cn/Article/details/gtypsmpaur.html

[T05] Kotlin：when 表达式
来源：http://dali.chenzaomai.com/Article/details/gtiswnfuql.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hfpthk.cn/Article/details/gtavbnhyuc.html

[T06] Kotlin：集合映射
来源：http://dali.tanke756.top/Article/details/gtcojwbomk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtlfqojrzu.html

[T07] Kotlin：集合过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgswgcplm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.snrcjt.cn/Article/details/gtdnddnylw.html

[T08] Kotlin：数据类
来源：http://dali.nanxuanxn.top/Article/details/gtkplavrfx.html

data class User(val name: String, val age: Int)
来源：http://dali.yanxiufei.cn/Article/details/gthougjbfa.html

[T09] Kotlin：扩展函数
来源：http://dali.ehwqpu.com/Article/details/gtfstknkcx.html

fun String.exclaim() = this + "!"
来源：http://dali.jinghuilouyu.cn/Article/details/gtufjvmibz.html

[T10] Kotlin：默认参数
来源：http://dali.yuanzhike.top/Article/details/gtmlifftfe.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hnqzz.top/Article/details/gteidkhlzw.html

[T11] Kotlin：协程
来源：http://dali.0kj1m.cn/Article/details/gtxnzvefwv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.redwolf501.top/Article/details/gtmmgtvfhc.html

[T12] Kotlin：解构声明
来源：http://dali.daxiang520.top/Article/details/gtbgfgvhbi.html

val (a, b) = Pair(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gtpixcnzcn.html

[T13] Kotlin：只读 Map
来源：http://dali.quarkkingdee.top/Article/details/gtzrnifpen.html

val m = mapOf("a" to 1)
来源：http://dali.zhongyouzk.top/Article/details/gtdcyvvfbq.html

[T14] Kotlin：循环
来源：http://dali.hnqzz.top/Article/details/gtuvwurbbd.html

for (i in 1..10) println(i)
来源：http://dali.andypj.xyz/Article/details/gtvkggtjeg.html

[T15] Kotlin：接口
来源：http://dali.aizwys.cn/Article/details/gtiexqaryu.html

interface Shape { fun area(): Double }
来源：http://dali.zhixingplan.top/Article/details/gtamrrppvk.html

[T16] Swift：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtvcvwfcpc.html

print("Hello")
来源：http://dali.zhiwuduotai.top/Article/details/gtuzzkfokq.html

[T17] Swift：变量与常量
来源：http://dali.hfpthk.cn/Article/details/gtvnxoktdq.html

var a = 1;  let b = 2
来源：http://dali.sufxvd.cn/Article/details/gtoaudjesx.html

[T18] Swift：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gtfbpncrxr.html

"值: \(b)"
来源：http://dali.cashguo.top/Article/details/gtdkbedqfc.html

[T19] Swift：可选绑定
来源：http://dali.cucudq.cn/Article/details/gtezexqpnq.html

if let n = opt { print(n) }
来源：http://dali.cqqwz.cn/Article/details/gthlsgkljy.html

[T20] Swift：数组操作
来源：http://dali.chenjidiqi.icu/Article/details/gthlblyude.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yueranfly.top/Article/details/gtgjsnltxv.html

[T21] Swift：遍历
来源：http://dali.birdmap.top/Article/details/gtldvgdcjv.html

for x in a { print(x) }
来源：http://dali.cucudq.cn/Article/details/gtosibcjbs.html

[T22] Swift：字典
来源：http://dali.jqgufenzy.top/Article/details/gtzipkjoup.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.tanke756.top/Article/details/gtzoslyllr.html

[T23] Swift：函数
来源：http://dali.zhongyouzk.top/Article/details/gttqntgadi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xylfe.cn/Article/details/gtoykyodss.html

[T24] Swift：闭包
来源：http://dali.hammf.cn/Article/details/gtftqlybyz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkgjzrfx.html

[T25] Swift：结构体
来源：http://dali.kuanghao11.cn/Article/details/gtqewtndlb.html

struct P { var x: Int }
来源：http://dali.yonumen.top/Article/details/gtpdbhspwo.html

[T26] Swift：类与重写
来源：http://dali.fzhhl.top/Article/details/gtxqueosmr.html

class A: Base { override func f() {} }
来源：http://dali.iojbl.cn/Article/details/gtjihycdsy.html

[T27] Swift：错误处理
来源：http://dali.nanxinkj.top/Article/details/gtajvubnrd.html

do { try f() } catch { print(error) }
来源：http://dali.cdnleiting.top/Article/details/gtuaojrtth.html

[T28] Swift：枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuvtzrpmp.html

enum Color { case red, green }
来源：http://dali.iojbl.cn/Article/details/gtlembsont.html

[T29] Swift：guard 提前返回
来源：http://dali.sxryk.cn/Article/details/gtlctwzedd.html

guard let x = opt else { return }
来源：http://dali.jianghu66.top/Article/details/gtqoiwtdws.html

[T30] Swift：协议
来源：http://dali.316326.xyz/Article/details/gtsgysdnqv.html

protocol Shape { func area() -> Double }
来源：http://dali.yueranfly.top/Article/details/gthmsvmphb.html

[T31] Lua：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtzktqqmnl.html

print("Hello")
来源：http://dali.jqgufenzy.top/Article/details/gttxixzlne.html

[T32] Lua：局部变量
来源：http://dali.hnxiangtu.top/Article/details/gtyzlaxfvk.html

local a = 1
来源：http://dali.ivvv.top/Article/details/gtrumjhwwr.html

[T33] Lua：表（数组）
来源：http://dali.shangyingyoupin.top/Article/details/gtkwjzuxna.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yj20258888.top/Article/details/gtemncmcyl.html

[T34] Lua：遍历表
来源：http://dali.yangfankeji.com/Article/details/gtdyjxsazh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinqigfzy.top/Article/details/gteczchmxa.html

[T35] Lua：字典表
来源：http://dali.quarkkingdee.top/Article/details/gtpzynulin.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sysykeji.top/Article/details/gtvmtnozma.html

[T36] Lua：函数
来源：http://dali.guowangkeji.top/Article/details/gtqdiqvvtw.html

function add(a, b) return a + b end
来源：http://dali.hnxiangtu.top/Article/details/gtqjnfnokb.html

[T37] Lua：字符串拼接
来源：http://dali.nanxinkj.top/Article/details/gtobklmqyg.html

"a" .. "b"
来源：http://dali.tanke756.top/Article/details/gtzxkghacy.html

[T38] Lua：条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiumdblwp.html

if x > 0 then print("正") end
来源：http://dali.shangyingyoupin.top/Article/details/gtfagjeinc.html

[T39] Lua：模式匹配
来源：http://dali.fengsongda.top/Article/details/gtscctvsmh.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gtdyadugqk.html

[T40] Lua：元表
来源：http://dali.chenjidiqi.icu/Article/details/gtmfpwrnzt.html

setmetatable({}, { __index = base })
来源：http://dali.9152youxi.cn/Article/details/gtlmetxpyt.html

[T41] Perl：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtkvldirbp.html

print "Hello\n";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtftpcvpzt.html

[T42] Perl：变量类型
来源：http://dali.hongshengwenyu.top/Article/details/gtpvehchye.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jqgufenzy.top/Article/details/gthpbxigmy.html

[T43] Perl：字符串插值
来源：http://dali.yvedp.cn/Article/details/gtsnbjhhta.html

"值: $a"
来源：http://dali.zhengqikj.top/Article/details/gtsyqyqbgs.html

[T44] Perl：条件
来源：http://dali.wangdashe.top/Article/details/gternmvmaj.html

if ($a > 0) { print "正"; }
来源：http://dali.ivvv.top/Article/details/gtfyhjpfpk.html

[T45] Perl：数组遍历
来源：http://dali.yuanzhike.top/Article/details/gtcdsautys.html

for my $x (@arr) { print $x; }
来源：http://dali.quarkkingdee.top/Article/details/gtlgrgbnoi.html

[T46] Perl：哈希操作
来源：http://dali.dianchejie.cn/Article/details/gtiydtntzw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hfpthk.cn/Article/details/gtoxdulebp.html

[T47] Perl：正则捕获
来源：http://dali.yuanzhike.top/Article/details/gtufqmajxg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.iojbl.cn/Article/details/gtzlhgydla.html

[T48] Perl：正则替换
来源：http://dali.yongpay.top/Article/details/gtdbcdwvas.html

$s =~ s/old/new/g;
来源：http://dali.hfpthk.cn/Article/details/gtphmoydzy.html

[T49] Perl：函数
来源：http://dali.tianlin.xyz/Article/details/gtehdedidf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gtojfsviph.html

[T50] Perl：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxjnratvb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gogol.net.cn/Article/details/gtmfmihqnv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajdotqpa.html

[T51] Scala：Hello World
来源：http://dali.zycfv.cn/Article/details/gthhdydjqf.html

println("Hello")
来源：http://dali.shanyushiyangtech.top/Article/details/gttrbnbjya.html

[T52] Scala：变量
来源：http://dali.gotoacloud.top/Article/details/gttrravrig.html

val a = 1;  var b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnrijorhg.html

[T53] Scala：字符串插值
来源：http://dali.yangfankeji.com/Article/details/gtkbwwbuhk.html

s"值: $b"
来源：http://dali.xuanzx.com/Article/details/gtbuxzqtzy.html

[T54] Scala：集合映射
来源：http://dali.svipenyu.cn/Article/details/gtfnjglgzg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.snrcjt.cn/Article/details/gtegubhtbo.html

[T55] Scala：集合过滤
来源：http://dali.hywenlv.cn/Article/details/gtxmwmuito.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sweek.top/Article/details/gtweejojbt.html

[T56] Scala：样例类
来源：http://dali.iojbl.cn/Article/details/gtdbdwoxzp.html

case class User(name: String, age: Int)
来源：http://dali.yuxming.cn/Article/details/gtbuzedvhu.html

[T57] Scala：模式匹配
来源：http://dali.jqgufenzy.top/Article/details/gtsemokhmk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jianghu66.top/Article/details/gtnvkwbdbo.html

[T58] Scala：函数定义
来源：http://dali.svipenyu.cn/Article/details/gtgdrpitus.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhoulong.xyz/Article/details/gtuyuwwves.html

[T59] Scala：循环
来源：http://dali.sxryk.cn/Article/details/gtpplngfvj.html

for (i <- 1 to 10) println(i)
来源：http://dali.yanxiufei.cn/Article/details/gtroggblwe.html

[T60] Scala：折叠
来源：http://dali.zhiwuduotai.top/Article/details/gtmvvtbqwt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tianlin.xyz/Article/details/gteolqetfl.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtayjpybze.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gogol.net.cn/Article/details/gtllymtncy.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtlyfzpkna.html

[U01] Py：创建虚拟环境
来源：http://dali.yueranfly.top/Article/details/gtculioxtm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xuetiantiany.cn/Article/details/gtddvpaugi.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhoulong.xyz/Article/details/gthiphrrlu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cucudq.cn/Article/details/gtgkyikcbg.html

[U03] Py：加载 .env 配置
来源：http://dali.cucudq.cn/Article/details/gthldzncgy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.tianlin.xyz/Article/details/gtqqtueefu.html

[U04] Py：变量调试打印
来源：http://dali.yanxiufei.cn/Article/details/gthjzomaga.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shzxlz.cn/Article/details/gtielwzdfg.html

[U05] Py：列表去重且保序
来源：http://dali.dianchejie.cn/Article/details/gterherlgk.html

list(dict.fromkeys(arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gttolpsxpl.html

[U06] Py：合并两个字典
来源：http://dali.yangfankeji.com/Article/details/gtegcworfy.html

{**a, **b}
来源：http://dali.chenlongwang.top/Article/details/gtvvyltvqh.html

[U07] Py：反转字典键值
来源：http://dali.haohaochexian.top/Article/details/gtdywinsho.html

{v: k for k, v in d.items()}
来源：http://dali.hfpthk.cn/Article/details/gtgigbnami.html

[U08] Py：展平二维列表
来源：http://dali.iojbl.cn/Article/details/gtjhzjhsau.html

[y for x in nested for y in x]
来源：http://dali.cdnleiting.top/Article/details/gtipxlvpgq.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gtvfthicav.html

max(d, key=d.get)
来源：http://dali.zhengqikj.top/Article/details/gtpsnipmli.html

[U10] Py：按值排序字典
来源：http://dali.316326.xyz/Article/details/gtfewngbxk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gogol.net.cn/Article/details/gtptmusncl.html


<!-- 参考信息 -->