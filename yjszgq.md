代发 wailian999

export PATH="$HOME/bin:$PATH"
来源：http://dali.cashguo.top/Article/details/gt2totbsxri.html

[R76] 使用临时文件
来源：http://dali.cqqwz.cn/Article/details/gt2hgnxzqbj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnqzz.top/Article/details/gt2nuopskka.html

[R77] 读取用户输入
来源：http://dali.nwbrower.top/Article/details/gt2cymewlhd.html

read -rp "请输入: " ans
来源：http://dali.ppjwa.cn/Article/details/gt2qznhqloj.html

[R78] 交互式菜单
来源：http://dali.ivvv.top/Article/details/gt2gnqtkxhq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.9152youxi.cn/Article/details/gt2utzpwipm.html

[R79] 解析命令行选项
来源：http://dali.wangshuangyany.cn/Article/details/gt2laafxocp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.tian-w.cn/Article/details/gt2jgtkaiay.html

[R80] 查看脚本执行耗时
来源：http://dali.mhx1999.top/Article/details/gt2xzozpfmr.html

time ./run.sh
来源：http://dali.hfpthk.cn/Article/details/gt2ygkvdevw.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2yoqfjvgg.html

S. C / C++ 专题
来源：http://dali.nanxuanxn.top/Article/details/gt2ztrfxktf.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2zyywlqnp.html

[S01] C：Hello World
来源：http://dali.nwbrower.top/Article/details/gt2auwefsuv.html

#include <stdio.h>
来源：http://dali.gzhubu.top/Article/details/gt2umcmfjvt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2chnkfedt.html

[S02] C：变量与格式化输出
来源：http://dali.c1oappe.top/Article/details/gt2kvqfofdu.html

int a = 10; printf("%d\n", a);
来源：http://dali.bjfxy.top/Article/details/gt2chgpvihi.html

[S03] C：读入整数
来源：http://dali.redwolf501.top/Article/details/gt2wctwtiem.html

int x; scanf("%d", &x);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ofjunqpc.html

[S04] C：字符串复制
来源：http://dali.yueranfly.top/Article/details/gt2gdqamgxs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.9152youxi.cn/Article/details/gt2xljmfdtl.html

[S05] C：字符串长度
来源：http://dali.chenjidiqi.icu/Article/details/gt2kwwlvnzm.html

strlen(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jizetoyk.html

[S06] C：字符串比较
来源：http://dali.kuanghao11.cn/Article/details/gt2mvmjnxcv.html

strcmp(a, b) == 0
来源：http://dali.shanyushiyangtech.top/Article/details/gt2grhaxszc.html

[S07] C：数组遍历求和
来源：http://dali.yvedp.cn/Article/details/gt2dlrpdzna.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.svipenyu.cn/Article/details/gt2nrejsyjr.html

[S08] C：动态内存分配与释放
来源：http://dali.zhoulong.xyz/Article/details/gt2jkcsdfvf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.haohaochexian.top/Article/details/gt2vbxdycyw.html

[S09] C：结构体定义与初始化
来源：http://dali.hfpthk.cn/Article/details/gt2xlxncyqy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.bjfxy.top/Article/details/gt2jjbusrwg.html

[S10] C：指针与解引用
来源：http://dali.redwolf501.top/Article/details/gt2xjrmezau.html

int *p = &a;  *p = 5;
来源：http://dali.c1oappe.top/Article/details/gt2stahnmio.html

[S11] C：逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gt2nzvcxlow.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yangfankeji.com/Article/details/gt2jqmrfkkr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gt2dijezcds.html

fclose(f);
来源：http://dali.cqqwz.cn/Article/details/gt2vdhbkjhq.html

[S12] C：写文件
来源：http://dali.hnqzz.top/Article/details/gt2wtrsyznx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tian-w.cn/Article/details/gt2bhogzfdf.html

[S13] C：宏定义
来源：http://dali.zhengqikj.top/Article/details/gt2objrwdwr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenjidiqi.icu/Article/details/gt2xwnhjdqq.html

[S14] C：枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2donpmhgf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cdnleiting.top/Article/details/gt2tnuvhrsy.html

[S15] C：类型转换
来源：http://dali.yuanzhike.top/Article/details/gt2krltwvhq.html

(double) a / b
来源：http://dali.shangyingyoupin.top/Article/details/gt2ulpqedbg.html

[S16] C：位操作置位
来源：http://dali.chenlongwang.top/Article/details/gt2dolpkxuk.html

x |= (1 << 3);
来源：http://dali.ybcxt.top/Article/details/gt2ncpwrkqu.html

[S17] C：安全拼接字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2ypgdizjs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ybcxt.top/Article/details/gt2axybaokj.html

[S18] C：命令行参数
来源：http://dali.ppjwa.cn/Article/details/gt2xegixmdg.html

int main(int argc, char **argv)
来源：http://dali.sxryk.cn/Article/details/gt2vaetczwi.html

[S19] C：快速排序
来源：http://dali.mhx1999.top/Article/details/gt2zpzzqzqn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.redwolf501.top/Article/details/gt2uzrwukly.html

[S20] C：二分查找
来源：http://dali.gzhubu.top/Article/details/gt2ojhuwfvz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hjltfthi.html

[S21] C：字符类别判断
来源：http://dali.wangshuangyany.cn/Article/details/gt2mvlpzyfh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.pycfn.com/Article/details/gt2penmmwij.html

[S22] C：字符串转数字
来源：http://dali.aibaodan.cn/Article/details/gt2lkbliixh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.dashuyun.cn/Article/details/gt2ubuzyoib.html

[S23] C：随机数
来源：http://dali.hnxiangtu.top/Article/details/gt2bovqtqxj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.vqdsnc.cn/Article/details/gt2ketjytbv.html

[S24] C：获取本地时间
来源：http://dali.jinqigufen.top/Article/details/gt2vlvguvmj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cheryme.top/Article/details/gt2yjpljzbb.html

[S25] C：内存拷贝
来源：http://dali.jlsjyb.cn/Article/details/gt2ibrorxqd.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxknsts.html

[S26] C：内存清零
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ulepitqy.html

memset(a, 0, sizeof a);
来源：http://dali.jinqigfzy.top/Article/details/gt2awfmbkyv.html

[S27] C：定义常量
来源：http://dali.svipenyu.cn/Article/details/gt2nniokmwo.html

const double PI = 3.14159;
来源：http://dali.sweek.top/Article/details/gt2rkxermmb.html

[S28] C：静态变量
来源：http://dali.xuanzx.com/Article/details/gt2nyqhmult.html

static int counter = 0;
来源：http://dali.xuetiantiany.cn/Article/details/gt2lcsgazdc.html

[S29] C：变参函数
来源：http://dali.sxryk.cn/Article/details/gt2hptcmmja.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.bjfxy.top/Article/details/gt2gfhcrfcw.html

[S30] C：头文件保护
来源：http://dali.snrcjt.cn/Article/details/gt2tbwsqkhx.html

#ifndef X_H
来源：http://dali.sufxvd.cn/Article/details/gt2geyjfsoc.html

#define X_H
来源：http://dali.chenzaomai.com/Article/details/gt2jdkrvbgv.html

#endif
来源：http://dali.feifeiyinyue.top/Article/details/gt2isqoitsa.html

[S31] C++：Hello World
来源：http://dali.cqqwz.cn/Article/details/gt2guszjodg.html

#include <iostream>
来源：http://dali.sweek.top/Article/details/gt2fteqxaap.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhixingplan.top/Article/details/gt2bnrxrnvv.html

[S32] C++：字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2iogcohoa.html

std::string s = "hi";  s += "!";
来源：http://dali.dashuyun.cn/Article/details/gt2bgqgryyd.html

[S33] C++：vector 增删
来源：http://dali.snrcjt.cn/Article/details/gt2sriwvxiv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sysykeji.top/Article/details/gt2cdpdaerq.html

[S34] C++：遍历 vector
来源：http://dali.jlsjyb.cn/Article/details/gt2nnzsdwuz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhixingplan.top/Article/details/gt2vdorrkku.html

[S35] C++：map
来源：http://dali.fengsongda.top/Article/details/gt2twzkfrvz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ncucrstf.html

[S36] C++：unordered_map
来源：http://dali.shzxlz.cn/Article/details/gt2fuvajaol.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2brlbbjsx.html

[S37] C++：set
来源：http://dali.shuidangran.top/Article/details/gt2dwnmoquw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jlsjyb.cn/Article/details/gt2lfxkacje.html

[S38] C++：排序
来源：http://dali.hammf.cn/Article/details/gt2moushimg.html

std::sort(v.begin(), v.end());
来源：http://dali.jyoumei.cn/Article/details/gt2arzpdpui.html

[S39] C++：自定义比较器排序
来源：http://dali.yuxming.cn/Article/details/gt2ixpjolgs.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.meibo888.top/Article/details/gt2fwenvcjy.html

[S40] C++：查找元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kzajvmqx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2efkzmwtr.html

[S41] C++：类与构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lrbzsxmf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yongpay.top/Article/details/gt2uvqronrv.html

[S42] C++：继承与虚函数
来源：http://dali.jiagoushi.top/Article/details/gt2sqlpkoka.html

class B : public Base { public: void f() override {} };
来源：http://dali.hysaishi.cn/Article/details/gt2tlapshdw.html

[S43] C++：智能指针
来源：http://dali.daxiang520.top/Article/details/gt2xksgbnrl.html

auto p = std::make_unique<int>(5);
来源：http://dali.9152youxi.cn/Article/details/gt2qwjcutco.html

[S44] C++：引用传参
来源：http://dali.sysykeji.top/Article/details/gt2qfdvggko.html

void inc(int &x) { ++x; }
来源：http://dali.hnxiangtu.top/Article/details/gt2jkblbosz.html

[S45] C++：lambda
来源：http://dali.cdnleiting.top/Article/details/gt2magqokhl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinqigufen.top/Article/details/gt2etlsgoid.html

[S46] C++：函数模板
来源：http://dali.svipenyu.cn/Article/details/gt2nttiyvuo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hnuubwhi.html

[S47] C++：结构化绑定遍历
来源：http://dali.jiagoushi.top/Article/details/gt2kzxelahs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.kuanghao11.cn/Article/details/gt2kbcprzuh.html

[S48] C++：逐行读文件
来源：http://dali.fzhhl.top/Article/details/gt2ukigdmne.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cucudq.cn/Article/details/gt2muxtpuwk.html

while (std::getline(in, line)) { }
来源：http://dali.jlsjyb.cn/Article/details/gt2yptusbfl.html

[S49] C++：写文件
来源：http://dali.yonumen.top/Article/details/gt2ytywruzu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.haohaochexian.top/Article/details/gt2gtstrxym.html

[S50] C++：格式化数字
来源：http://dali.bjfxy.top/Article/details/gt2qqaafpvb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.redwolf501.top/Article/details/gt2xvzhsulu.html

[S51] C++：显式类型转换
来源：http://dali.jqgufenzy.top/Article/details/gt2wsqoaljs.html

static_cast<double>(a) / b
来源：http://dali.cdnleiting.top/Article/details/gt2okjqxjyl.html

[S52] C++：const 与 noexcept
来源：http://dali.ydzc1.top/Article/details/gt2whjkqaie.html

int size() const noexcept { return n_; }
来源：http://dali.dashuyun.cn/Article/details/gt2eekcarlw.html

[S53] C++：移动语义
来源：http://dali.haohaochexian.top/Article/details/gt2sqhucren.html

std::vector<int> w = std::move(v);
来源：http://dali.jqgfzy.top/Article/details/gt2huykedrx.html

[S54] C++：异常处理
来源：http://dali.wangshuangyany.cn/Article/details/gt2rqpmutqt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xszummjk.html

[S55] C++：结构化绑定
来源：http://dali.chenlongwang.top/Article/details/gt2ojvhsktf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.bjfxy.top/Article/details/gt2bfnixaug.html

[S56] C++：optional
来源：http://dali.fzhhl.top/Article/details/gt2rlstdkbu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.c1oappe.top/Article/details/gt2pescqljd.html

[S57] C++：编译期常量
来源：http://dali.cucudq.cn/Article/details/gt2gjakxdba.html

constexpr int N = 10;
来源：http://dali.yueranfly.top/Article/details/gt2slccfwjo.html

[S58] C++：命名空间
来源：http://dali.guannengcc.top/Article/details/gt2ewlbhkqk.html

namespace ns { int f() { return 1; } }
来源：http://dali.snrcjt.cn/Article/details/gt2ihxhzzlr.html

[S59] C++：静态断言
来源：http://dali.sysykeji.top/Article/details/gt2lghqyiql.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gotoacloud.top/Article/details/gt2qvnpibak.html

[S60] C++：遍历并删除元素
来源：http://dali.tianlin.xyz/Article/details/gt2gjmsdcwu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhixingplan.top/Article/details/gt2ivdmvaii.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2imzbbvzm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hnqzz.top/Article/details/gt2mdbqlpgh.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2kciqtfpu.html

[T01] Kotlin：Hello World
来源：http://dali.shzxlz.cn/Article/details/gt2khtygynu.html

println("Hello")
来源：http://dali.zdqjudy.top/Article/details/gt2qgajnzvs.html

[T02] Kotlin：变量
来源：http://dali.jqgfzy.top/Article/details/gt2qtrxkhtb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jqgufenzy.top/Article/details/gt2pkbjsyqs.html

[T03] Kotlin：字符串模板
来源：http://dali.zhixingplan.top/Article/details/gt2iwwzbupo.html

"值: $b"
来源：http://dali.havefunace.top/Article/details/gt2kcqcoioq.html

[T04] Kotlin：空安全
来源：http://dali.havefunace.top/Article/details/gt2ucoerpbw.html

val n: String? = null;  n?.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jpkzabcw.html

[T05] Kotlin：when 表达式
来源：http://dali.ybcxt.top/Article/details/gt2vayziylb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jyoumei.cn/Article/details/gt2tbtsilgl.html

[T06] Kotlin：集合映射
来源：http://dali.daxiang520.top/Article/details/gt2xiphxbow.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jianghu66.top/Article/details/gt2jnkorooc.html

[T07] Kotlin：集合过滤
来源：http://dali.aibaodan.cn/Article/details/gt2fsenngvl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xinyue.icu/Article/details/gt2omcufhru.html

[T08] Kotlin：数据类
来源：http://dali.xylfe.cn/Article/details/gt2bofnsygd.html

data class User(val name: String, val age: Int)
来源：http://dali.redwolf501.top/Article/details/gt2pckxbwzl.html

[T09] Kotlin：扩展函数
来源：http://dali.ehwqpu.com/Article/details/gt2ayosvuus.html

fun String.exclaim() = this + "!"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ebgdvnjl.html

[T10] Kotlin：默认参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zgzjaxji.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ppjwa.cn/Article/details/gt2ozytcgoa.html

[T11] Kotlin：协程
来源：http://dali.vqdsnc.cn/Article/details/gt2yqtxrecm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jiagoushi.top/Article/details/gt2qtcahmcr.html

[T12] Kotlin：解构声明
来源：http://dali.yuxming.cn/Article/details/gt2wjqafgau.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wqgbcrzf.html

[T13] Kotlin：只读 Map
来源：http://dali.gogol.net.cn/Article/details/gt2srustzdn.html

val m = mapOf("a" to 1)
来源：http://dali.gzhubu.top/Article/details/gt2ariduisr.html

[T14] Kotlin：循环
来源：http://dali.cheryme.top/Article/details/gt2fcshfpka.html

for (i in 1..10) println(i)
来源：http://dali.daria6918.cn/Article/details/gt2ozmlbyex.html

[T15] Kotlin：接口
来源：http://dali.gogol.net.cn/Article/details/gt2luuobfzt.html

interface Shape { fun area(): Double }
来源：http://dali.dashuyun.cn/Article/details/gt2ffzrdlzr.html

[T16] Swift：Hello World
来源：http://dali.nanxinkj.top/Article/details/gt2rynntfbi.html

print("Hello")
来源：http://dali.yj202588.top/Article/details/gt2dyxdgwth.html

[T17] Swift：变量与常量
来源：http://dali.fengsongda.top/Article/details/gt2rrpcskkn.html

var a = 1;  let b = 2
来源：http://dali.nanxuanxn.top/Article/details/gt2jlxjuozi.html

[T18] Swift：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gt2jabkcqki.html

"值: \(b)"
来源：http://dali.daxiang520.top/Article/details/gt2cgrsqywq.html

[T19] Swift：可选绑定
来源：http://dali.ppjwa.cn/Article/details/gt2ketcjifg.html

if let n = opt { print(n) }
来源：http://dali.0kj1m.cn/Article/details/gt2hvqyxsjz.html

[T20] Swift：数组操作
来源：http://dali.xinyue.icu/Article/details/gt2chplzbek.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.havefunace.top/Article/details/gt2cmustben.html

[T21] Swift：遍历
来源：http://dali.dianchejie.cn/Article/details/gt2uwyivqxv.html

for x in a { print(x) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bbkpbhbf.html

[T22] Swift：字典
来源：http://dali.zdqjudy.top/Article/details/gt2rlgrxmoz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.0kj1m.cn/Article/details/gt2kazwmqnz.html

[T23] Swift：函数
来源：http://dali.hnxiangtu.top/Article/details/gt2ysothmgu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cheryme.top/Article/details/gt2omxvfqwl.html

[T24] Swift：闭包
来源：http://dali.chenlongwang.top/Article/details/gt2ebhkaivm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.birdmap.top/Article/details/gt2wwkpufdf.html

[T25] Swift：结构体
来源：http://dali.zdqjudy.top/Article/details/gt2fhnbbjge.html

struct P { var x: Int }
来源：http://dali.yanxiufei.cn/Article/details/gt2xfwjshys.html

[T26] Swift：类与重写
来源：http://dali.yuanzhike.top/Article/details/gt2gkjpqsjc.html

class A: Base { override func f() {} }
来源：http://dali.wangshuangyany.cn/Article/details/gt2fuwpoijl.html

[T27] Swift：错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lmdnskar.html

do { try f() } catch { print(error) }
来源：http://dali.feifeiyinyue.top/Article/details/gt2qshxjigt.html

[T28] Swift：枚举
来源：http://dali.daria6918.cn/Article/details/gt2kdoonkcn.html

enum Color { case red, green }
来源：http://dali.hnqzz.top/Article/details/gt2bgecnoze.html

[T29] Swift：guard 提前返回
来源：http://dali.smart0.xyz/Article/details/gt2okdytupk.html

guard let x = opt else { return }
来源：http://dali.shzxlz.cn/Article/details/gt2vchoqglz.html

[T30] Swift：协议
来源：http://dali.jlsjyb.cn/Article/details/gt2lgdlxusq.html

protocol Shape { func area() -> Double }
来源：http://dali.daria6918.cn/Article/details/gt2gphewpui.html

[T31] Lua：Hello World
来源：http://dali.svipenyu.cn/Article/details/gt2lqlywbma.html

print("Hello")
来源：http://dali.guowangkeji.top/Article/details/gt2nwxekdby.html

[T32] Lua：局部变量
来源：http://dali.gotoacloud.top/Article/details/gt2vbmnfweo.html

local a = 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2pquzjcyq.html

[T33] Lua：表（数组）
来源：http://dali.shuidangran.top/Article/details/gt2rrawjcge.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.pengpengdd.cyou/Article/details/gt2khyraeju.html

[T34] Lua：遍历表
来源：http://dali.jinqigfzy.top/Article/details/gt2pcipkzpb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shuidangran.top/Article/details/gt2gtuqcxtd.html

[T35] Lua：字典表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tczwhrjy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.bjfxy.top/Article/details/gt2yippsnpw.html

[T36] Lua：函数
来源：http://dali.kuanghao11.cn/Article/details/gt2prpvrggz.html

function add(a, b) return a + b end
来源：http://dali.xylfe.cn/Article/details/gt2uawbawfr.html

[T37] Lua：字符串拼接
来源：http://dali.fzhhl.top/Article/details/gt2tglgzqfv.html

"a" .. "b"
来源：http://dali.nanxuanxn.top/Article/details/gt2eeunwnxx.html

[T38] Lua：条件
来源：http://dali.zhixingplan.top/Article/details/gt2ujpnxsew.html

if x > 0 then print("正") end
来源：http://dali.yongpay.top/Article/details/gt2rjqbwqxv.html

[T39] Lua：模式匹配
来源：http://dali.c1oappe.top/Article/details/gt2kxcgofdw.html

string.find(s, "%d+")
来源：http://dali.ppjwa.cn/Article/details/gt2ztedotoi.html

[T40] Lua：元表
来源：http://dali.yonumen.top/Article/details/gt2yedympul.html

setmetatable({}, { __index = base })
来源：http://dali.dashuyun.cn/Article/details/gt2dhvmqfra.html

[T41] Perl：Hello World
来源：http://dali.yuanzhike.top/Article/details/gt2jfsregsn.html

print "Hello\n";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fsodhgox.html

[T42] Perl：变量类型
来源：http://dali.sxryk.cn/Article/details/gt2fabzgbip.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yangfankeji.com/Article/details/gt2wjywtwhw.html

[T43] Perl：字符串插值
来源：http://dali.cucudq.cn/Article/details/gt2ficfznjp.html

"值: $a"
来源：http://dali.fzhhl.top/Article/details/gt2atfiomoe.html

[T44] Perl：条件
来源：http://dali.0kj1m.cn/Article/details/gt2tppxcwbs.html

if ($a > 0) { print "正"; }
来源：http://dali.daria6918.cn/Article/details/gt2kkuljbiu.html

[T45] Perl：数组遍历
来源：http://dali.sufxvd.cn/Article/details/gt2uazbvyob.html

for my $x (@arr) { print $x; }
来源：http://dali.smart0.xyz/Article/details/gt2cfopoxbu.html

[T46] Perl：哈希操作
来源：http://dali.guannengcc.top/Article/details/gt2dnmrahal.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.dashuyun.cn/Article/details/gt2wxyvmyuk.html

[T47] Perl：正则捕获
来源：http://dali.quarkkingdee.top/Article/details/gt2edtjppwz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cashguo.top/Article/details/gt2zwlxliep.html

[T48] Perl：正则替换
来源：http://dali.tian-w.cn/Article/details/gt2gshldjuw.html

$s =~ s/old/new/g;
来源：http://dali.havefunace.top/Article/details/gt2ymxxadhk.html

[T49] Perl：函数
来源：http://dali.jinqigufen.top/Article/details/gt2efymnosv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhongyouzk.top/Article/details/gt2zmbvomxb.html

[T50] Perl：逐行读文件
来源：http://dali.xziqi.cn/Article/details/gt2hzabxoif.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2behmbrxg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.c1oappe.top/Article/details/gt2fjrczwoy.html

[T51] Scala：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gt2ezznnpyr.html

println("Hello")
来源：http://dali.dianchejie.cn/Article/details/gt2ipwjugml.html

[T52] Scala：变量
来源：http://dali.daria6918.cn/Article/details/gt2bgruqofk.html

val a = 1;  var b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gt2dzcalyue.html

[T53] Scala：字符串插值
来源：http://dali.yongpay.top/Article/details/gt2lkxrdntl.html

s"值: $b"
来源：http://dali.cdnleiting.top/Article/details/gt2nclnigzt.html

[T54] Scala：集合映射
来源：http://dali.yuanzhike.top/Article/details/gt2jxunirbs.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hysaishi.cn/Article/details/gt2xbyvahqo.html

[T55] Scala：集合过滤
来源：http://dali.havefunace.top/Article/details/gt2wpbhfgzs.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hysaishi.cn/Article/details/gt2pqqzcumy.html

[T56] Scala：样例类
来源：http://dali.316326.xyz/Article/details/gt2rklnpxzy.html

case class User(name: String, age: Int)
来源：http://dali.chenlongwang.top/Article/details/gt2qylhawil.html

[T57] Scala：模式匹配
来源：http://dali.cqqwz.cn/Article/details/gt2biwowksz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.guowangkeji.top/Article/details/gt2jcmzqras.html

[T58] Scala：函数定义
来源：http://dali.guannengcc.top/Article/details/gt2zbivhcwj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.meibo888.top/Article/details/gt2mvuwwjoo.html

[T59] Scala：循环
来源：http://dali.yanxiufei.cn/Article/details/gt2bixdkhxj.html

for (i <- 1 to 10) println(i)
来源：http://dali.0kj1m.cn/Article/details/gt2zlxihaoy.html

[T60] Scala：折叠
来源：http://dali.chenjidiqi.icu/Article/details/gt2tmrsalsw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jyoumei.cn/Article/details/gt2lsofnili.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2olabbbnu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jiagoushi.top/Article/details/gt2zbisguyj.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jjsvhutt.html

[U01] Py：创建虚拟环境
来源：http://dali.xylfe.cn/Article/details/gt2udldhknj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.gotoacloud.top/Article/details/gt2wohvijim.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cashguo.top/Article/details/gt2zlzkmjxo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.smart0.xyz/Article/details/gt2eitxijye.html

[U03] Py：加载 .env 配置
来源：http://dali.smart0.xyz/Article/details/gt2hdjjplbw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jiagoushi.top/Article/details/gt2wapzmzmx.html

[U04] Py：变量调试打印
来源：http://dali.pycfn.com/Article/details/gt2lhhkvgsd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yj202588.top/Article/details/gt2narumccy.html

[U05] Py：列表去重且保序
来源：http://dali.nanxinkj.top/Article/details/gt2ykmwfoyt.html

list(dict.fromkeys(arr))
来源：http://dali.hnqzz.top/Article/details/gt2hmxrdukm.html

[U06] Py：合并两个字典
来源：http://dali.zhengqikj.top/Article/details/gt2lnbikrva.html

{**a, **b}
来源：http://dali.feifeiyinyue.top/Article/details/gt2yagvceuy.html

[U07] Py：反转字典键值
来源：http://dali.zhixingplan.top/Article/details/gt2ayhrnurn.html

{v: k for k, v in d.items()}
来源：http://dali.ivvv.top/Article/details/gt2jadjxesm.html

[U08] Py：展平二维列表
来源：http://dali.sufxvd.cn/Article/details/gt2syedckfy.html

[y for x in nested for y in x]
来源：http://dali.jiagoushi.top/Article/details/gt2aybmqufb.html

[U09] Py：字典取最大值的键
来源：http://dali.wangdashe.top/Article/details/gt2ifzygwzy.html

max(d, key=d.get)
来源：http://dali.cashguo.top/Article/details/gt2yeymbugu.html

[U10] Py：按值排序字典
来源：http://dali.feifeiyinyue.top/Article/details/gt2wwrmhfxu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zdqjudy.top/Article/details/gt2gyazxvsb.html

[U11] Py：生成器表达式
来源：http://dali.hongshengwenyu.top/Article/details/gt2kioxikpe.html

(x * 2 for x in arr)
来源：http://dali.guowangkeji.top/Article/details/gt2vgjositn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yj20258888.top/Article/details/gt2srnyifyh.html

Counter(arr).most_common(3)
来源：http://dali.fengsongda.top/Article/details/gt2rpzrayhm.html

[U13] Py：固定长度队列
来源：http://dali.yanxiufei.cn/Article/details/gt2mituswsp.html

deque(maxlen=10)
来源：http://dali.gotoacloud.top/Article/details/gt2souocogu.html

[U14] Py：分组收集到列表
来源：http://dali.tianlin.xyz/Article/details/gt2gdnyugvc.html

defaultdict(list)
来源：http://dali.sxryk.cn/Article/details/gt2qibcpnif.html

[U15] Py：高精度计时
来源：http://dali.pycfn.com/Article/details/gt2liwnudvd.html

t = time.perf_counter()
来源：http://dali.nanxuanxn.top/Article/details/gt2tgqyhjnn.html

[U16] Py：命令行参数解析
来源：http://dali.dianchejie.cn/Article/details/gt2ykytivhq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dsbkbhbh.html


<!-- 参考信息 -->