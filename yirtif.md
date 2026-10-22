代发 wailian999

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenlongwang.top/Article/details/gtxdgohiar.html

[R72] 等待端口就绪
来源：http://dali.gotoacloud.top/Article/details/gtjfqfzcpd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.redwolf501.top/Article/details/gtqojfqqhg.html

[R73] 分割大日志
来源：http://dali.zhixingplan.top/Article/details/gtnbywygmp.html

split -l 1000 big.log part_
来源：http://dali.pycfn.com/Article/details/gtxtzptkov.html

[R74] 批量重命名
来源：http://dali.hongshengwenyu.top/Article/details/gtxfueqazk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yvedp.cn/Article/details/gtcdcpxtya.html

[R75] 导出环境变量
来源：http://dali.ppjwa.cn/Article/details/gtriqrtsof.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hammf.cn/Article/details/gtqcfoexve.html

[R76] 使用临时文件
来源：http://dali.yuxming.cn/Article/details/gtkurwbpgm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cqqwz.cn/Article/details/gtkannmabd.html

[R77] 读取用户输入
来源：http://dali.shzxlz.cn/Article/details/gtovklynxp.html

read -rp "请输入: " ans
来源：http://dali.xylfe.cn/Article/details/gtuzjmsvez.html

[R78] 交互式菜单
来源：http://dali.wangshuangyany.cn/Article/details/gteebdnoez.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yonumen.top/Article/details/gtybkbrjkb.html

[R79] 解析命令行选项
来源：http://dali.kuanghao11.cn/Article/details/gtzenxloyh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shuidangran.top/Article/details/gtjmixifaj.html

[R80] 查看脚本执行耗时
来源：http://dali.dashuyun.cn/Article/details/gtihuqcuuw.html

time ./run.sh
来源：http://dali.tanke756.top/Article/details/gtfoymajiy.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtgurogwck.html

S. C / C++ 专题
来源：http://dali.jyoumei.cn/Article/details/gtbnemazhc.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtjmewtldz.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gttdhyrirm.html

#include <stdio.h>
来源：http://dali.chenlongwang.top/Article/details/gtavbiujlt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtonxidqpi.html

[S02] C：变量与格式化输出
来源：http://dali.quarkkingdee.top/Article/details/gtaddarjfi.html

int a = 10; printf("%d\n", a);
来源：http://dali.iojbl.cn/Article/details/gtwrjrpmfx.html

[S03] C：读入整数
来源：http://dali.daria6918.cn/Article/details/gtxhjkbsye.html

int x; scanf("%d", &x);
来源：http://dali.smart0.xyz/Article/details/gtevvwvzao.html

[S04] C：字符串复制
来源：http://dali.hammf.cn/Article/details/gtdwlemzlq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.redwolf501.top/Article/details/gtbguuqsff.html

[S05] C：字符串长度
来源：http://dali.chenjidiqi.icu/Article/details/gtntpuabyk.html

strlen(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmhbdlvui.html

[S06] C：字符串比较
来源：http://dali.0kj1m.cn/Article/details/gtrfcsjidc.html

strcmp(a, b) == 0
来源：http://dali.zycfv.cn/Article/details/gtmrbatvum.html

[S07] C：数组遍历求和
来源：http://dali.yueranfly.top/Article/details/gtdhnweomm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hywenlv.cn/Article/details/gtjgotswhn.html

[S08] C：动态内存分配与释放
来源：http://dali.jqgufenzy.top/Article/details/gtokyegxtw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinqigufen.top/Article/details/gtfzwqdqoj.html

[S09] C：结构体定义与初始化
来源：http://dali.iojbl.cn/Article/details/gtsudyhomb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cashguo.top/Article/details/gtimolcxdr.html

[S10] C：指针与解引用
来源：http://dali.gotoacloud.top/Article/details/gtrkwrzjkm.html

int *p = &a;  *p = 5;
来源：http://dali.316326.xyz/Article/details/gtexlgmbbw.html

[S11] C：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gtjemqbbym.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xziqi.cn/Article/details/gtmxmndnfi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.tian-w.cn/Article/details/gtdvrsqeew.html

fclose(f);
来源：http://dali.tian-w.cn/Article/details/gtzniopdgk.html

[S12] C：写文件
来源：http://dali.jqgufenzy.top/Article/details/gtltglosvo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangdashe.top/Article/details/gtqgnaxtqu.html

[S13] C：宏定义
来源：http://dali.hammf.cn/Article/details/gtqmmyafzu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj20258.top/Article/details/gtbpuowgrg.html

[S14] C：枚举
来源：http://dali.jlsjyb.cn/Article/details/gttcjkrjjc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.dianchejie.cn/Article/details/gtqaucsgsf.html

[S15] C：类型转换
来源：http://dali.chenjidiqi.icu/Article/details/gtxasfibya.html

(double) a / b
来源：http://dali.hysaishi.cn/Article/details/gtkguqxfnb.html

[S16] C：位操作置位
来源：http://dali.shzxlz.cn/Article/details/gtiugkqmbb.html

x |= (1 << 3);
来源：http://dali.nwbrower.top/Article/details/gtyyjieitf.html

[S17] C：安全拼接字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgpfddhzp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.guowangkeji.top/Article/details/gtvrfzgpfm.html

[S18] C：命令行参数
来源：http://dali.nanxinkj.top/Article/details/gtugzewhfd.html

int main(int argc, char **argv)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyybtihnu.html

[S19] C：快速排序
来源：http://dali.hnqzz.top/Article/details/gtejmjgwld.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yongpay.top/Article/details/gtyzpyxnrc.html

[S20] C：二分查找
来源：http://dali.andypj.xyz/Article/details/gtbkennutk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.c1oappe.top/Article/details/gtmnshybva.html

[S21] C：字符类别判断
来源：http://dali.ydzc1.top/Article/details/gtfzgredgq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhiwuduotai.top/Article/details/gtdduhtwls.html

[S22] C：字符串转数字
来源：http://dali.yj20258.top/Article/details/gtunstquwp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hysaishi.cn/Article/details/gtpujouyam.html

[S23] C：随机数
来源：http://dali.feifeiyinyue.top/Article/details/gtyeenqqjh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jianghu66.top/Article/details/gtrbsgurcf.html

[S24] C：获取本地时间
来源：http://dali.guowangkeji.top/Article/details/gttkezdaxz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.havefunace.top/Article/details/gtrnpsabid.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gtrfnnthid.html

memcpy(dst, src, n);
来源：http://dali.zdqjudy.top/Article/details/gtsgduyjhw.html

[S26] C：内存清零
来源：http://dali.xuanzx.com/Article/details/gtrkakvpcq.html

memset(a, 0, sizeof a);
来源：http://dali.xuetiantiany.cn/Article/details/gtwepqmfhw.html

[S27] C：定义常量
来源：http://dali.xziqi.cn/Article/details/gtdpvgggln.html

const double PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gtutjkxhau.html

[S28] C：静态变量
来源：http://dali.hywenlv.cn/Article/details/gtpqrjlfnk.html

static int counter = 0;
来源：http://dali.mhx1999.top/Article/details/gtywtkbygf.html

[S29] C：变参函数
来源：http://dali.daria6918.cn/Article/details/gtkumlrplj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nanxuanxn.top/Article/details/gtiuywwjhy.html

[S30] C：头文件保护
来源：http://dali.ivvv.top/Article/details/gtqosywmft.html

#ifndef X_H
来源：http://dali.cucudq.cn/Article/details/gtcbogyehw.html

#define X_H
来源：http://dali.shangyingyoupin.top/Article/details/gtcsqwhjtc.html

#endif
来源：http://dali.cqqwz.cn/Article/details/gtuofubaub.html

[S31] C++：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtswxhlijs.html

#include <iostream>
来源：http://dali.shanyushiyangtech.top/Article/details/gtsddjqqpw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.pycfn.com/Article/details/gtjwluwcce.html

[S32] C++：字符串
来源：http://dali.zdqjudy.top/Article/details/gtoprirtxy.html

std::string s = "hi";  s += "!";
来源：http://dali.pycfn.com/Article/details/gtqtixaite.html

[S33] C++：vector 增删
来源：http://dali.zhixingplan.top/Article/details/gtpqltojyx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlrsmcyka.html

[S34] C++：遍历 vector
来源：http://dali.chenjidiqi.icu/Article/details/gtpcfpvsmt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.pengpengdd.cyou/Article/details/gtzdnalgmu.html

[S35] C++：map
来源：http://dali.cheryme.top/Article/details/gtgxxkbvgd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuxming.cn/Article/details/gtlwrojjjq.html

[S36] C++：unordered_map
来源：http://dali.aizwys.cn/Article/details/gthtmnnlbw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gtuvslgkze.html

[S37] C++：set
来源：http://dali.aibaodan.cn/Article/details/gtitihvjty.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhongyouzk.top/Article/details/gtmhclecnk.html

[S38] C++：排序
来源：http://dali.yueranfly.top/Article/details/gtwpdlumrk.html

std::sort(v.begin(), v.end());
来源：http://dali.yanxiufei.cn/Article/details/gtejpzqezv.html

[S39] C++：自定义比较器排序
来源：http://dali.hnqzz.top/Article/details/gtdzntjiju.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhiwuduotai.top/Article/details/gtphjjfazz.html

[S40] C++：查找元素
来源：http://dali.daria6918.cn/Article/details/gtkfogxmvb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nanxuanxn.top/Article/details/gtgxjaeabf.html

[S41] C++：类与构造函数
来源：http://dali.fzhhl.top/Article/details/gthtjfoerw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnqzz.top/Article/details/gtrsjqqlpb.html

[S42] C++：继承与虚函数
来源：http://dali.cqqwz.cn/Article/details/gtapsovsji.html

class B : public Base { public: void f() override {} };
来源：http://dali.ivvv.top/Article/details/gtnqnvuwdb.html

[S43] C++：智能指针
来源：http://dali.hywenlv.cn/Article/details/gtprekbstz.html

auto p = std::make_unique<int>(5);
来源：http://dali.tianlin.xyz/Article/details/gtfslfykso.html

[S44] C++：引用传参
来源：http://dali.nwbrower.top/Article/details/gtavpmldwv.html

void inc(int &x) { ++x; }
来源：http://dali.meibo888.top/Article/details/gtpjsjuxmo.html

[S45] C++：lambda
来源：http://dali.hfpthk.cn/Article/details/gtphujonom.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jianghu66.top/Article/details/gtlbznnflv.html

[S46] C++：函数模板
来源：http://dali.sysykeji.top/Article/details/gtosxelqrk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.andypj.xyz/Article/details/gtwvvkxklc.html

[S47] C++：结构化绑定遍历
来源：http://dali.mhx1999.top/Article/details/gtkvfdgwoj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sufxvd.cn/Article/details/gtgqugrxxa.html

[S48] C++：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtrzrfymol.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.feifeiyinyue.top/Article/details/gtwsglbrqy.html

while (std::getline(in, line)) { }
来源：http://dali.shzxlz.cn/Article/details/gtftbvhhjk.html

[S49] C++：写文件
来源：http://dali.sweek.top/Article/details/gtpwwqgcvx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jianghu66.top/Article/details/gtfsidfozh.html

[S50] C++：格式化数字
来源：http://dali.jinqigufen.top/Article/details/gtxtukienj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gttsgxgwpa.html

[S51] C++：显式类型转换
来源：http://dali.yuxming.cn/Article/details/gtbfijzhev.html

static_cast<double>(a) / b
来源：http://dali.9152youxi.cn/Article/details/gteumyieph.html

[S52] C++：const 与 noexcept
来源：http://dali.cqqwz.cn/Article/details/gtvzzkyxpf.html

int size() const noexcept { return n_; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtazfejwbj.html

[S53] C++：移动语义
来源：http://dali.hnqzz.top/Article/details/gtugejvhri.html

std::vector<int> w = std::move(v);
来源：http://dali.haohaochexian.top/Article/details/gtcjhcnjac.html

[S54] C++：异常处理
来源：http://dali.jyoumei.cn/Article/details/gtgxeisfiy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenzaomai.com/Article/details/gtpqixdcds.html

[S55] C++：结构化绑定
来源：http://dali.316326.xyz/Article/details/gtiqhhvibh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yongpay.top/Article/details/gtejciukus.html

[S56] C++：optional
来源：http://dali.kuanghao11.cn/Article/details/gtwjclwguz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cucudq.cn/Article/details/gthrgslnia.html

[S57] C++：编译期常量
来源：http://dali.shanyushiyangtech.top/Article/details/gtqogaqlsu.html

constexpr int N = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwaemhqk.html

[S58] C++：命名空间
来源：http://dali.ivvv.top/Article/details/gttztsdavu.html

namespace ns { int f() { return 1; } }
来源：http://dali.yanxiufei.cn/Article/details/gtztyidnls.html

[S59] C++：静态断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gtntzkimva.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xuetiantiany.cn/Article/details/gtlrpnuimo.html

[S60] C++：遍历并删除元素
来源：http://dali.zhengqikj.top/Article/details/gtqcrmufgl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenzaomai.com/Article/details/gtxsvradtq.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtpwbqdqpx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hammf.cn/Article/details/gtzievmevc.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtrtpjkott.html

[T01] Kotlin：Hello World
来源：http://dali.pycfn.com/Article/details/gthabbugby.html

println("Hello")
来源：http://dali.zhengqikj.top/Article/details/gtbscmzfbj.html

[T02] Kotlin：变量
来源：http://dali.tanke756.top/Article/details/gtahikultv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.havefunace.top/Article/details/gtcjmpqmiy.html

[T03] Kotlin：字符串模板
来源：http://dali.xuanzx.com/Article/details/gtzsfygdqq.html

"值: $b"
来源：http://dali.jqgufenzy.top/Article/details/gtzuvhbaye.html

[T04] Kotlin：空安全
来源：http://dali.aibaodan.cn/Article/details/gtjrvakxqa.html

val n: String? = null;  n?.length
来源：http://dali.nanxuanxn.top/Article/details/gtvjaoqzbr.html

[T05] Kotlin：when 表达式
来源：http://dali.yvedp.cn/Article/details/gtzjkqgkym.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.meibo888.top/Article/details/gtxccrrzws.html

[T06] Kotlin：集合映射
来源：http://dali.nanxuanxn.top/Article/details/gttlnryiva.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.haohaochexian.top/Article/details/gtvimhcjul.html

[T07] Kotlin：集合过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkbettyhf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwjlglppr.html

[T08] Kotlin：数据类
来源：http://dali.aizwys.cn/Article/details/gthvwwjaub.html

data class User(val name: String, val age: Int)
来源：http://dali.guowangkeji.top/Article/details/gtpmqlyaoi.html

[T09] Kotlin：扩展函数
来源：http://dali.9152youxi.cn/Article/details/gtqzontrjd.html

fun String.exclaim() = this + "!"
来源：http://dali.sxryk.cn/Article/details/gtqlxqucyb.html

[T10] Kotlin：默认参数
来源：http://dali.iojbl.cn/Article/details/gtumwhwmfg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpovfhbqy.html

[T11] Kotlin：协程
来源：http://dali.tanke756.top/Article/details/gtsfpemftv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.havefunace.top/Article/details/gtkbwxizqe.html

[T12] Kotlin：解构声明
来源：http://dali.hnxiangtu.top/Article/details/gtapkroebu.html

val (a, b) = Pair(1, 2)
来源：http://dali.yj202588.top/Article/details/gtymssjjzd.html

[T13] Kotlin：只读 Map
来源：http://dali.xuetiantiany.cn/Article/details/gtmldushhs.html

val m = mapOf("a" to 1)
来源：http://dali.andypj.xyz/Article/details/gtjxcbapuw.html

[T14] Kotlin：循环
来源：http://dali.9152youxi.cn/Article/details/gtctolngpq.html

for (i in 1..10) println(i)
来源：http://dali.kuanghao11.cn/Article/details/gtfnrdtksd.html

[T15] Kotlin：接口
来源：http://dali.zdqjudy.top/Article/details/gtwwpniftd.html

interface Shape { fun area(): Double }
来源：http://dali.jyoumei.cn/Article/details/gtuoqknomq.html

[T16] Swift：Hello World
来源：http://dali.yvedp.cn/Article/details/gtubikmluk.html

print("Hello")
来源：http://dali.zdqjudy.top/Article/details/gtxdanruxl.html

[T17] Swift：变量与常量
来源：http://dali.redwolf501.top/Article/details/gtbmpmidzw.html

var a = 1;  let b = 2
来源：http://dali.aibaodan.cn/Article/details/gtmlklbtlb.html

[T18] Swift：字符串插值
来源：http://dali.yvedp.cn/Article/details/gtfcbsevka.html

"值: \(b)"
来源：http://dali.ppjwa.cn/Article/details/gtzvmgiher.html

[T19] Swift：可选绑定
来源：http://dali.feifeiyinyue.top/Article/details/gtictncdng.html

if let n = opt { print(n) }
来源：http://dali.ydzc1.top/Article/details/gtmrzcikcv.html

[T20] Swift：数组操作
来源：http://dali.tanke756.top/Article/details/gtqkocebpr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.pengpengdd.cyou/Article/details/gtjxwjlypu.html

[T21] Swift：遍历
来源：http://dali.tanke756.top/Article/details/gtjnhgbpgz.html

for x in a { print(x) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtugkfrjpj.html

[T22] Swift：字典
来源：http://dali.iojbl.cn/Article/details/gtooosknsq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sufxvd.cn/Article/details/gtvaezqnjm.html

[T23] Swift：函数
来源：http://dali.gotoacloud.top/Article/details/gtocevwdjl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hongshengwenyu.top/Article/details/gtbfadjemn.html

[T24] Swift：闭包
来源：http://dali.shanyushiyangtech.top/Article/details/gttxvybhlr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtjyjdagos.html

[T25] Swift：结构体
来源：http://dali.havefunace.top/Article/details/gtjzizmzpm.html

struct P { var x: Int }
来源：http://dali.sxryk.cn/Article/details/gtgytwxohw.html

[T26] Swift：类与重写
来源：http://dali.tianlin.xyz/Article/details/gtlkzrijqj.html

class A: Base { override func f() {} }
来源：http://dali.havefunace.top/Article/details/gtdamgdqnr.html

[T27] Swift：错误处理
来源：http://dali.dianchejie.cn/Article/details/gteoyiwqth.html

do { try f() } catch { print(error) }
来源：http://dali.dashuyun.cn/Article/details/gtiwnawpud.html

[T28] Swift：枚举
来源：http://dali.daria6918.cn/Article/details/gtfyzvuehw.html

enum Color { case red, green }
来源：http://dali.aibaodan.cn/Article/details/gtcmrnxkcl.html

[T29] Swift：guard 提前返回
来源：http://dali.hysaishi.cn/Article/details/gtpfdrukyc.html

guard let x = opt else { return }
来源：http://dali.yj20258888.top/Article/details/gtkmjmqkmx.html

[T30] Swift：协议
来源：http://dali.gaohongyu789.top/Article/details/gtypxkvdci.html

protocol Shape { func area() -> Double }
来源：http://dali.feifeiyinyue.top/Article/details/gtpequmjto.html

[T31] Lua：Hello World
来源：http://dali.aizwys.cn/Article/details/gtsqcnrcus.html

print("Hello")
来源：http://dali.redwolf501.top/Article/details/gtmxdjftbx.html

[T32] Lua：局部变量
来源：http://dali.pycfn.com/Article/details/gtgnzmhiwa.html

local a = 1
来源：http://dali.xylfe.cn/Article/details/gtzkfmwdch.html

[T33] Lua：表（数组）
来源：http://dali.shanyushiyangtech.top/Article/details/gtduuxqtun.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.daxiang520.top/Article/details/gtocwgnwnz.html

[T34] Lua：遍历表
来源：http://dali.9152youxi.cn/Article/details/gtfsbgxtda.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinqigufen.top/Article/details/gtrrsdlkjs.html

[T35] Lua：字典表
来源：http://dali.cashguo.top/Article/details/gtymrnxndb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ppjwa.cn/Article/details/gtrqduofci.html

[T36] Lua：函数
来源：http://dali.andypj.xyz/Article/details/gtzfmiqxxo.html

function add(a, b) return a + b end
来源：http://dali.ppjwa.cn/Article/details/gtusrduqdd.html

[T37] Lua：字符串拼接
来源：http://dali.guowangkeji.top/Article/details/gtlaczkmrw.html

"a" .. "b"
来源：http://dali.fengsongda.top/Article/details/gtlwepyztj.html

[T38] Lua：条件
来源：http://dali.kuanghao11.cn/Article/details/gthmjwtrkr.html

if x > 0 then print("正") end
来源：http://dali.hongshengwenyu.top/Article/details/gtmpsztiuw.html

[T39] Lua：模式匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiakfqmyb.html

string.find(s, "%d+")
来源：http://dali.mhx1999.top/Article/details/gtlhuyadqv.html

[T40] Lua：元表
来源：http://dali.ehwqpu.com/Article/details/gtklcnjvbl.html

setmetatable({}, { __index = base })
来源：http://dali.ivvv.top/Article/details/gttagrvrsn.html

[T41] Perl：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gteihvfigt.html

print "Hello\n";
来源：http://dali.ehwqpu.com/Article/details/gtnraebprb.html

[T42] Perl：变量类型
来源：http://dali.zhoulong.xyz/Article/details/gthjlzlxxe.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yongpay.top/Article/details/gtgdiljens.html

[T43] Perl：字符串插值
来源：http://dali.c1oappe.top/Article/details/gtwluhnnxt.html

"值: $a"
来源：http://dali.xinyue.icu/Article/details/gtaddnhymj.html

[T44] Perl：条件
来源：http://dali.zycfv.cn/Article/details/gtlmatvqlw.html

if ($a > 0) { print "正"; }
来源：http://dali.hnxiangtu.top/Article/details/gtyjbfhcgq.html

[T45] Perl：数组遍历
来源：http://dali.c1oappe.top/Article/details/gtxvpeqigt.html

for my $x (@arr) { print $x; }
来源：http://dali.xuetiantiany.cn/Article/details/gtbhvizffb.html

[T46] Perl：哈希操作
来源：http://dali.sysykeji.top/Article/details/gtfhqssskz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.sysykeji.top/Article/details/gtqgdpshqr.html

[T47] Perl：正则捕获
来源：http://dali.cucudq.cn/Article/details/gtqxhuifla.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.gzhubu.top/Article/details/gtpjuprlox.html

[T48] Perl：正则替换
来源：http://dali.jianghu66.top/Article/details/gtwicbtwtb.html

$s =~ s/old/new/g;
来源：http://dali.xziqi.cn/Article/details/gtbalfzlde.html

[T49] Perl：函数
来源：http://dali.hnxiangtu.top/Article/details/gttwrtixky.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gteypodpvp.html

[T50] Perl：逐行读文件
来源：http://dali.wangdashe.top/Article/details/gtuiscnuey.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.pycfn.com/Article/details/gtasoagwip.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zycfv.cn/Article/details/gtejpbfoiw.html

[T51] Scala：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtrzzufxqz.html

println("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gtgwucdlvw.html

[T52] Scala：变量
来源：http://dali.yanxiufei.cn/Article/details/gtqsavnypj.html

val a = 1;  var b = 2
来源：http://dali.sxryk.cn/Article/details/gteymkjijs.html

[T53] Scala：字符串插值
来源：http://dali.pycfn.com/Article/details/gtirxojcvo.html

s"值: $b"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtytgwqupo.html

[T54] Scala：集合映射
来源：http://dali.snrcjt.cn/Article/details/gtcnnfsfjv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gotoacloud.top/Article/details/gtihyunvxj.html

[T55] Scala：集合过滤
来源：http://dali.hfpthk.cn/Article/details/gtcenyuwed.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yanxiufei.cn/Article/details/gtfkxqxbyi.html

[T56] Scala：样例类
来源：http://dali.gaohongyu789.top/Article/details/gtacskjrws.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gtzshkvgcr.html

[T57] Scala：模式匹配
来源：http://dali.yj20258.top/Article/details/gtjippdgnd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ydzc1.top/Article/details/gtknfpkbje.html

[T58] Scala：函数定义
来源：http://dali.hongshengwenyu.top/Article/details/gteyaomowr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.chenjidiqi.icu/Article/details/gtncivsjqd.html

[T59] Scala：循环
来源：http://dali.nwbrower.top/Article/details/gtikrjopoj.html

for (i <- 1 to 10) println(i)
来源：http://dali.hysaishi.cn/Article/details/gtoklkfeel.html

[T60] Scala：折叠
来源：http://dali.hywenlv.cn/Article/details/gtlksotitm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.guowangkeji.top/Article/details/gtnxhirnpo.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtmzfzkkui.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.wangdashe.top/Article/details/gtgefctwqy.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtningqwpv.html

[U01] Py：创建虚拟环境
来源：http://dali.feifeiyinyue.top/Article/details/gtzldfjego.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.daxiang520.top/Article/details/gtavrzdawa.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sweek.top/Article/details/gtivgcdoeb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtqgtmpslt.html

[U03] Py：加载 .env 配置
来源：http://dali.snrcjt.cn/Article/details/gtyxbwjypl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yonumen.top/Article/details/gtfsiixbhu.html

[U04] Py：变量调试打印
来源：http://dali.ydzc1.top/Article/details/gtpivvtafy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.aibaodan.cn/Article/details/gtodwhqzvz.html

[U05] Py：列表去重且保序
来源：http://dali.tanke756.top/Article/details/gtizzqvmgr.html

list(dict.fromkeys(arr))
来源：http://dali.yuxming.cn/Article/details/gtwzwtfldi.html

[U06] Py：合并两个字典
来源：http://dali.yanxiufei.cn/Article/details/gtjqbdzqsr.html

{**a, **b}
来源：http://dali.0kj1m.cn/Article/details/gtexqinjqi.html

[U07] Py：反转字典键值
来源：http://dali.gotoacloud.top/Article/details/gtdukwcrpg.html

{v: k for k, v in d.items()}
来源：http://dali.havefunace.top/Article/details/gtztqwfnjt.html

[U08] Py：展平二维列表
来源：http://dali.zycfv.cn/Article/details/gtsmhktgen.html

[y for x in nested for y in x]
来源：http://dali.zhixingplan.top/Article/details/gtqyfqdvci.html

[U09] Py：字典取最大值的键
来源：http://dali.fzhhl.top/Article/details/gtzjuzefwa.html

max(d, key=d.get)
来源：http://dali.jianghu66.top/Article/details/gtsyfxcqpg.html

[U10] Py：按值排序字典
来源：http://dali.hfpthk.cn/Article/details/gtaanmnkwj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.haohaochexian.top/Article/details/gtvxzhhbfe.html

[U11] Py：生成器表达式
来源：http://dali.chenjidiqi.icu/Article/details/gtwbndflhb.html

(x * 2 for x in arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtarnrpsks.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.aibaodan.cn/Article/details/gtfyuoccve.html

Counter(arr).most_common(3)
来源：http://dali.yonumen.top/Article/details/gtczscodhg.html


<!-- 参考信息 -->