代发 wailian999

split -l 1000 big.log part_
来源：http://dali.jyoumei.cn/Article/details/gtcuttlmkl.html

[R74] 批量重命名
来源：http://dali.meibo888.top/Article/details/gtwhurbpil.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.316326.xyz/Article/details/gtchrpuxaw.html

[R75] 导出环境变量
来源：http://dali.shzxlz.cn/Article/details/gtbwepbcwi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.snrcjt.cn/Article/details/gtyhzitbir.html

[R76] 使用临时文件
来源：http://dali.tianlin.xyz/Article/details/gtuiudcclh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.nwbrower.top/Article/details/gtzfvmxgkq.html

[R77] 读取用户输入
来源：http://dali.guowangkeji.top/Article/details/gtreaurder.html

read -rp "请输入: " ans
来源：http://dali.xuanzx.com/Article/details/gtwdzjsgvg.html

[R78] 交互式菜单
来源：http://dali.gzhubu.top/Article/details/gtqjvgcdao.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xuanzx.com/Article/details/gtgqlvxnhz.html

[R79] 解析命令行选项
来源：http://dali.cqqwz.cn/Article/details/gtpsdtgymo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.tian-w.cn/Article/details/gtuvjfaraz.html

[R80] 查看脚本执行耗时
来源：http://dali.guowangkeji.top/Article/details/gtcvgstpcg.html

time ./run.sh
来源：http://dali.yvedp.cn/Article/details/gtwerltfwc.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtcyltwzsg.html

S. C / C++ 专题
来源：http://dali.shanyushiyangkeji.top/Article/details/gttjapvjga.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtdixxycyk.html

[S01] C：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtbdiyczdg.html

#include <stdio.h>
来源：http://dali.jinqigfzy.top/Article/details/gtrdtpkged.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shzxlz.cn/Article/details/gtjwgqcsep.html

[S02] C：变量与格式化输出
来源：http://dali.yonumen.top/Article/details/gtzcgvnmst.html

int a = 10; printf("%d\n", a);
来源：http://dali.nwbrower.top/Article/details/gtqyyfgwui.html

[S03] C：读入整数
来源：http://dali.ehwqpu.com/Article/details/gtvuwahjrc.html

int x; scanf("%d", &x);
来源：http://dali.yuxming.cn/Article/details/gtwpmghpsc.html

[S04] C：字符串复制
来源：http://dali.hysaishi.cn/Article/details/gtdhyopaoo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhongyouzk.top/Article/details/gtgmzefukr.html

[S05] C：字符串长度
来源：http://dali.hnqzz.top/Article/details/gtgixsaxlp.html

strlen(s)
来源：http://dali.xuanzx.com/Article/details/gtpottyzga.html

[S06] C：字符串比较
来源：http://dali.chenjidiqi.icu/Article/details/gtzkzmxzrj.html

strcmp(a, b) == 0
来源：http://dali.havefunace.top/Article/details/gtvlupzdco.html

[S07] C：数组遍历求和
来源：http://dali.mhx1999.top/Article/details/gtrciupybo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hongshengwenyu.top/Article/details/gtnxkbdgab.html

[S08] C：动态内存分配与释放
来源：http://dali.0kj1m.cn/Article/details/gttrvadnqj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdyxtgyvz.html

[S09] C：结构体定义与初始化
来源：http://dali.yongpay.top/Article/details/gtxjtflmuq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jqgufenzy.top/Article/details/gtoxxzshjr.html

[S10] C：指针与解引用
来源：http://dali.zhiwuduotai.top/Article/details/gtgsmmscdd.html

int *p = &a;  *p = 5;
来源：http://dali.chenjidiqi.icu/Article/details/gtfwppdidv.html

[S11] C：逐行读文件
来源：http://dali.cheryme.top/Article/details/gtcffpmjik.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmlruusiq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj20258.top/Article/details/gtnxqkvxmg.html

fclose(f);
来源：http://dali.yonumen.top/Article/details/gttrfxdfjh.html

[S12] C：写文件
来源：http://dali.chenzaomai.com/Article/details/gtvzwyzsfp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.quarkkingdee.top/Article/details/gtpbhbtzeb.html

[S13] C：宏定义
来源：http://dali.gotoacloud.top/Article/details/gtszwhnpkg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbhovlekt.html

[S14] C：枚举
来源：http://dali.tanke756.top/Article/details/gtgmnzygaz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jyoumei.cn/Article/details/gtgpuihtsw.html

[S15] C：类型转换
来源：http://dali.shuidangran.top/Article/details/gtlaqohndt.html

(double) a / b
来源：http://dali.tanke756.top/Article/details/gtgznvgucy.html

[S16] C：位操作置位
来源：http://dali.zycfv.cn/Article/details/gtmtpwggkt.html

x |= (1 << 3);
来源：http://dali.andypj.xyz/Article/details/gtesldvvqi.html

[S17] C：安全拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gttcnpvzkj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.andypj.xyz/Article/details/gtlmrpnbln.html

[S18] C：命令行参数
来源：http://dali.hnqzz.top/Article/details/gtcnapydzs.html

int main(int argc, char **argv)
来源：http://dali.sxryk.cn/Article/details/gtpryitfdm.html

[S19] C：快速排序
来源：http://dali.iojbl.cn/Article/details/gtigwmkhpr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gtrytsgcxb.html

[S20] C：二分查找
来源：http://dali.fzhhl.top/Article/details/gtcytxhdhs.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yongpay.top/Article/details/gtnysydbky.html

[S21] C：字符类别判断
来源：http://dali.sweek.top/Article/details/gtvizjakku.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.guowangkeji.top/Article/details/gturczyvuk.html

[S22] C：字符串转数字
来源：http://dali.jinqigfzy.top/Article/details/gtfcaajaux.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yueranfly.top/Article/details/gtlraltxfs.html

[S23] C：随机数
来源：http://dali.fzhhl.top/Article/details/gtrluzskpt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhengqikj.top/Article/details/gtojfehsex.html

[S24] C：获取本地时间
来源：http://dali.gaohongyu789.top/Article/details/gtgsjncyxe.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenlongwang.top/Article/details/gthilpjidk.html

[S25] C：内存拷贝
来源：http://dali.cashguo.top/Article/details/gthfwjrncd.html

memcpy(dst, src, n);
来源：http://dali.wangdashe.top/Article/details/gtaltbpxbw.html

[S26] C：内存清零
来源：http://dali.zhiwuduotai.top/Article/details/gtsqmbufng.html

memset(a, 0, sizeof a);
来源：http://dali.nanxuanxn.top/Article/details/gtbfmspsvi.html

[S27] C：定义常量
来源：http://dali.guannengcc.top/Article/details/gtflazonow.html

const double PI = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqplldngk.html

[S28] C：静态变量
来源：http://dali.c1oappe.top/Article/details/gtxaahqslp.html

static int counter = 0;
来源：http://dali.nwbrower.top/Article/details/gtfknniqic.html

[S29] C：变参函数
来源：http://dali.yvedp.cn/Article/details/gtvjwwfmer.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hywenlv.cn/Article/details/gtjulcugsr.html

[S30] C：头文件保护
来源：http://dali.haohaochexian.top/Article/details/gtjvksblbt.html

#ifndef X_H
来源：http://dali.shangyingyoupin.top/Article/details/gtyttqhdti.html

#define X_H
来源：http://dali.birdmap.top/Article/details/gtpmdtxyjz.html

#endif
来源：http://dali.cdnleiting.top/Article/details/gtbgpuqygl.html

[S31] C++：Hello World
来源：http://dali.yuxming.cn/Article/details/gtqjvxrexz.html

#include <iostream>
来源：http://dali.pengpengdd.cyou/Article/details/gtrweqatxq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tian-w.cn/Article/details/gtwhtbfcll.html

[S32] C++：字符串
来源：http://dali.xinyue.icu/Article/details/gtehvteyst.html

std::string s = "hi";  s += "!";
来源：http://dali.redwolf501.top/Article/details/gtpdamocfj.html

[S33] C++：vector 增删
来源：http://dali.dashuyun.cn/Article/details/gtxxjhnkzc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zycfv.cn/Article/details/gtyusntaoi.html

[S34] C++：遍历 vector
来源：http://dali.mhx1999.top/Article/details/gtqeicaoib.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yuxming.cn/Article/details/gtnxicypoh.html

[S35] C++：map
来源：http://dali.nwbrower.top/Article/details/gtfdbhskzo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258888.top/Article/details/gtkzydyfja.html

[S36] C++：unordered_map
来源：http://dali.shanyushiyangtech.top/Article/details/gtcgrjjrxv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gthwitstdu.html

[S37] C++：set
来源：http://dali.havefunace.top/Article/details/gthumghrhr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtasnykkda.html

[S38] C++：排序
来源：http://dali.haohaochexian.top/Article/details/gtcmztkryz.html

std::sort(v.begin(), v.end());
来源：http://dali.zhiwuduotai.top/Article/details/gtevicnckl.html

[S39] C++：自定义比较器排序
来源：http://dali.tanke756.top/Article/details/gtlvbxuruc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nanxinkj.top/Article/details/gtfzefzhmw.html

[S40] C++：查找元素
来源：http://dali.yueranfly.top/Article/details/gtgibcfebm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.redwolf501.top/Article/details/gttgiwtulb.html

[S41] C++：类与构造函数
来源：http://dali.sweek.top/Article/details/gtnlgxxmgj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.quarkkingdee.top/Article/details/gtenpcrxwh.html

[S42] C++：继承与虚函数
来源：http://dali.xziqi.cn/Article/details/gtabnaqpve.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhiwuduotai.top/Article/details/gtaccfnzan.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gtciaygpel.html

auto p = std::make_unique<int>(5);
来源：http://dali.ppjwa.cn/Article/details/gtknsqrhfo.html

[S44] C++：引用传参
来源：http://dali.aibaodan.cn/Article/details/gtqnsfdlil.html

void inc(int &x) { ++x; }
来源：http://dali.chenzaomai.com/Article/details/gtphwrqpar.html

[S45] C++：lambda
来源：http://dali.pycfn.com/Article/details/gtuneqthan.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cheryme.top/Article/details/gtnpvgzezc.html

[S46] C++：函数模板
来源：http://dali.zhoulong.xyz/Article/details/gtawepgwkm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtchskqxzx.html

[S47] C++：结构化绑定遍历
来源：http://dali.meibo888.top/Article/details/gtbjryflsl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.feifeiyinyue.top/Article/details/gtbkiljepf.html

[S48] C++：逐行读文件
来源：http://dali.wangdashe.top/Article/details/gtakmwfcgt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hammf.cn/Article/details/gtmgyernxb.html

while (std::getline(in, line)) { }
来源：http://dali.zhiwuduotai.top/Article/details/gtngzlnvem.html

[S49] C++：写文件
来源：http://dali.cheryme.top/Article/details/gtrcntsswp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zdqjudy.top/Article/details/gtekpjdmdy.html

[S50] C++：格式化数字
来源：http://dali.gaohongyu789.top/Article/details/gtvdkasulj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shuidangran.top/Article/details/gtlilbeoym.html

[S51] C++：显式类型转换
来源：http://dali.zhiwuduotai.top/Article/details/gtoujkqixk.html

static_cast<double>(a) / b
来源：http://dali.xinyue.icu/Article/details/gtintrpdyl.html

[S52] C++：const 与 noexcept
来源：http://dali.pycfn.com/Article/details/gtovfdkgsg.html

int size() const noexcept { return n_; }
来源：http://dali.svipenyu.cn/Article/details/gtdbuusfcu.html

[S53] C++：移动语义
来源：http://dali.yangfankeji.com/Article/details/gtjmxbdukd.html

std::vector<int> w = std::move(v);
来源：http://dali.cashguo.top/Article/details/gtaodntpjx.html

[S54] C++：异常处理
来源：http://dali.yanxiufei.cn/Article/details/gtgivjrqtn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.guannengcc.top/Article/details/gtglffcsvg.html

[S55] C++：结构化绑定
来源：http://dali.jinqigfzy.top/Article/details/gtvtssezmn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gogol.net.cn/Article/details/gtpxjcyecp.html

[S56] C++：optional
来源：http://dali.mhx1999.top/Article/details/gtuayrsttt.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jyoumei.cn/Article/details/gtmgesuzof.html

[S57] C++：编译期常量
来源：http://dali.hongshengwenyu.top/Article/details/gttvoercyq.html

constexpr int N = 10;
来源：http://dali.havefunace.top/Article/details/gtjkpsyzna.html

[S58] C++：命名空间
来源：http://dali.sxryk.cn/Article/details/gtlblgnpcf.html

namespace ns { int f() { return 1; } }
来源：http://dali.hongshengwenyu.top/Article/details/gtxreivmdw.html

[S59] C++：静态断言
来源：http://dali.jqgufenzy.top/Article/details/gtqadgsvim.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ppjwa.cn/Article/details/gtmduslmyv.html

[S60] C++：遍历并删除元素
来源：http://dali.gotoacloud.top/Article/details/gtstxhztts.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.wangdashe.top/Article/details/gtcrlhofcv.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtwywnvwsv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ehwqpu.com/Article/details/gtbiilyeyy.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtseixbpln.html

[T01] Kotlin：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtovyvuwqw.html

println("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtspqpugxo.html

[T02] Kotlin：变量
来源：http://dali.iojbl.cn/Article/details/gtourwifuj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cashguo.top/Article/details/gtnqswwtjy.html

[T03] Kotlin：字符串模板
来源：http://dali.jinqigufen.top/Article/details/gtrxqkkuel.html

"值: $b"
来源：http://dali.wangdashe.top/Article/details/gtnjbzyxee.html

[T04] Kotlin：空安全
来源：http://dali.yanxiufei.cn/Article/details/gtqhthgxzs.html

val n: String? = null;  n?.length
来源：http://dali.gotoacloud.top/Article/details/gtepmemyga.html

[T05] Kotlin：when 表达式
来源：http://dali.cqqwz.cn/Article/details/gtvpjrrhzh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sufxvd.cn/Article/details/gtkbuqgkbu.html

[T06] Kotlin：集合映射
来源：http://dali.cheryme.top/Article/details/gtnscffblt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hammf.cn/Article/details/gtxbbqlvmt.html

[T07] Kotlin：集合过滤
来源：http://dali.wangdashe.top/Article/details/gthamviadg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.wangshuangyany.cn/Article/details/gtjkbofxiu.html

[T08] Kotlin：数据类
来源：http://dali.jinqigfzy.top/Article/details/gtyrlichdv.html

data class User(val name: String, val age: Int)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuxtwkswd.html

[T09] Kotlin：扩展函数
来源：http://dali.hongshengwenyu.top/Article/details/gtokkmydtx.html

fun String.exclaim() = this + "!"
来源：http://dali.tianlin.xyz/Article/details/gtxkojiayi.html

[T10] Kotlin：默认参数
来源：http://dali.cdnleiting.top/Article/details/gtodyiurjb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.feifeiyinyue.top/Article/details/gtspfoujwq.html

[T11] Kotlin：协程
来源：http://dali.hnqzz.top/Article/details/gtmmihbvnb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cheryme.top/Article/details/gtdcsmwfsw.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gtnrjqifin.html

val (a, b) = Pair(1, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtdhkqyfhn.html

[T13] Kotlin：只读 Map
来源：http://dali.nanxinkj.top/Article/details/gtwuenzfag.html

val m = mapOf("a" to 1)
来源：http://dali.jianghu66.top/Article/details/gtlhafwddh.html

[T14] Kotlin：循环
来源：http://dali.daria6918.cn/Article/details/gtblchsfpf.html

for (i in 1..10) println(i)
来源：http://dali.yanxiufei.cn/Article/details/gtsfwcxfey.html

[T15] Kotlin：接口
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtviinruch.html

interface Shape { fun area(): Double }
来源：http://dali.vqdsnc.cn/Article/details/gtajhipyey.html

[T16] Swift：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtftskwbko.html

print("Hello")
来源：http://dali.jyoumei.cn/Article/details/gtdtlxbdsh.html

[T17] Swift：变量与常量
来源：http://dali.jiagoushi.top/Article/details/gtzssfjsor.html

var a = 1;  let b = 2
来源：http://dali.xuanzx.com/Article/details/gtmgrzjdqs.html

[T18] Swift：字符串插值
来源：http://dali.jianghu66.top/Article/details/gtxugsivfk.html

"值: \(b)"
来源：http://dali.jinqigufen.top/Article/details/gtfrczdxqi.html

[T19] Swift：可选绑定
来源：http://dali.xuetiantiany.cn/Article/details/gtdnxlnamw.html

if let n = opt { print(n) }
来源：http://dali.fzhhl.top/Article/details/gtpztroomf.html

[T20] Swift：数组操作
来源：http://dali.vqdsnc.cn/Article/details/gtwwioblwy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.aibaodan.cn/Article/details/gtsesliypc.html

[T21] Swift：遍历
来源：http://dali.dashuyun.cn/Article/details/gtcualsbux.html

for x in a { print(x) }
来源：http://dali.quarkkingdee.top/Article/details/gtmlvinpdo.html

[T22] Swift：字典
来源：http://dali.hnqzz.top/Article/details/gtwcafokyy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gogol.net.cn/Article/details/gtobndlyxf.html

[T23] Swift：函数
来源：http://dali.chenzaomai.com/Article/details/gtlzufkzsa.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tian-w.cn/Article/details/gtcyzerhsy.html

[T24] Swift：闭包
来源：http://dali.shzxlz.cn/Article/details/gtzlfzcwyc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.chenlongwang.top/Article/details/gtenhdqhgd.html

[T25] Swift：结构体
来源：http://dali.hammf.cn/Article/details/gtjhdknhvo.html

struct P { var x: Int }
来源：http://dali.hnxiangtu.top/Article/details/gtuqminakv.html

[T26] Swift：类与重写
来源：http://dali.tanke756.top/Article/details/gtomqwibzt.html

class A: Base { override func f() {} }
来源：http://dali.bjfxy.top/Article/details/gtrrabhcty.html

[T27] Swift：错误处理
来源：http://dali.ydzc1.top/Article/details/gtsveyqdbv.html

do { try f() } catch { print(error) }
来源：http://dali.yueranfly.top/Article/details/gtponydfgn.html

[T28] Swift：枚举
来源：http://dali.bjfxy.top/Article/details/gteuaeqaza.html

enum Color { case red, green }
来源：http://dali.chenlongwang.top/Article/details/gthbqufctd.html

[T29] Swift：guard 提前返回
来源：http://dali.cheryme.top/Article/details/gtvqyruqji.html

guard let x = opt else { return }
来源：http://dali.shzxlz.cn/Article/details/gtcuuthkxc.html

[T30] Swift：协议
来源：http://dali.haohaochexian.top/Article/details/gtrqzmkcoo.html

protocol Shape { func area() -> Double }
来源：http://dali.vqdsnc.cn/Article/details/gtsxndkyuv.html

[T31] Lua：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtjdenuvvz.html

print("Hello")
来源：http://dali.chenlongwang.top/Article/details/gtxinbpcbl.html

[T32] Lua：局部变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttpjpgkml.html

local a = 1
来源：http://dali.hammf.cn/Article/details/gtkcezsswt.html

[T33] Lua：表（数组）
来源：http://dali.guowangkeji.top/Article/details/gtilotjgvl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cqqwz.cn/Article/details/gteugxeodj.html

[T34] Lua：遍历表
来源：http://dali.zhiwuduotai.top/Article/details/gtaywmcqeq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hammf.cn/Article/details/gtszyxuoks.html

[T35] Lua：字典表
来源：http://dali.pengpengdd.cyou/Article/details/gthxaipscl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.wangshuangyany.cn/Article/details/gtcknnymln.html

[T36] Lua：函数
来源：http://dali.feifeiyinyue.top/Article/details/gthgidmayd.html

function add(a, b) return a + b end
来源：http://dali.quarkkingdee.top/Article/details/gtfjqkxyke.html

[T37] Lua：字符串拼接
来源：http://dali.jyoumei.cn/Article/details/gtxnjumqsi.html

"a" .. "b"
来源：http://dali.dianchejie.cn/Article/details/gtdekxztyi.html

[T38] Lua：条件
来源：http://dali.hysaishi.cn/Article/details/gtlyzpvmhn.html

if x > 0 then print("正") end
来源：http://dali.shzxlz.cn/Article/details/gtrpsyeqei.html

[T39] Lua：模式匹配
来源：http://dali.haohaochexian.top/Article/details/gtdmzuxkqu.html

string.find(s, "%d+")
来源：http://dali.wangdashe.top/Article/details/gtwzxuiexo.html

[T40] Lua：元表
来源：http://dali.jianghu66.top/Article/details/gtippaedmh.html

setmetatable({}, { __index = base })
来源：http://dali.vqdsnc.cn/Article/details/gtjuloayky.html

[T41] Perl：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtcphiaczy.html

print "Hello\n";
来源：http://dali.0kj1m.cn/Article/details/gtxsrqltma.html

[T42] Perl：变量类型
来源：http://dali.zhengqikj.top/Article/details/gtkfcianjc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gzhubu.top/Article/details/gtnbfmyplw.html

[T43] Perl：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gtavdtgulr.html

"值: $a"
来源：http://dali.cucudq.cn/Article/details/gtidedndzf.html

[T44] Perl：条件
来源：http://dali.gzhubu.top/Article/details/gtsaygrrwy.html

if ($a > 0) { print "正"; }
来源：http://dali.hnxiangtu.top/Article/details/gtwycozqvd.html

[T45] Perl：数组遍历
来源：http://dali.yuxming.cn/Article/details/gtjqtsdsrv.html

for my $x (@arr) { print $x; }
来源：http://dali.ydzc1.top/Article/details/gtevpolhhe.html

[T46] Perl：哈希操作
来源：http://dali.sysykeji.top/Article/details/gtadtpwzrz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.tianlin.xyz/Article/details/gtlbpvirol.html

[T47] Perl：正则捕获
来源：http://dali.chenjidiqi.icu/Article/details/gtskwknmtv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.meibo888.top/Article/details/gtjztsbkpg.html

[T48] Perl：正则替换
来源：http://dali.nwbrower.top/Article/details/gtygsvvzwt.html

$s =~ s/old/new/g;
来源：http://dali.ybcxt.top/Article/details/gttwbjzttd.html

[T49] Perl：函数
来源：http://dali.daria6918.cn/Article/details/gtsukhulqn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.meibo888.top/Article/details/gtedqlvmss.html

[T50] Perl：逐行读文件
来源：http://dali.redwolf501.top/Article/details/gthmtrkkhz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zycfv.cn/Article/details/gthxyhvjmb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.redwolf501.top/Article/details/gtxnnmqvop.html

[T51] Scala：Hello World
来源：http://dali.xziqi.cn/Article/details/gtulziokbz.html

println("Hello")
来源：http://dali.bjfxy.top/Article/details/gtbmsawvqo.html

[T52] Scala：变量
来源：http://dali.jqgfzy.top/Article/details/gtgvuomkcl.html

val a = 1;  var b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gteesocxbu.html

[T53] Scala：字符串插值
来源：http://dali.xylfe.cn/Article/details/gtlcxrorfa.html

s"值: $b"
来源：http://dali.guannengcc.top/Article/details/gtosyhehbi.html

[T54] Scala：集合映射
来源：http://dali.cucudq.cn/Article/details/gteyxgkeqp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcjpqdvmv.html

[T55] Scala：集合过滤
来源：http://dali.fengsongda.top/Article/details/gtanxnqhrd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.dianchejie.cn/Article/details/gtzamkuzko.html

[T56] Scala：样例类
来源：http://dali.0kj1m.cn/Article/details/gtypmeqqho.html

case class User(name: String, age: Int)
来源：http://dali.pycfn.com/Article/details/gtdegydvmz.html

[T57] Scala：模式匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtnqihzffg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.iojbl.cn/Article/details/gtjhjgobfk.html

[T58] Scala：函数定义
来源：http://dali.daxiang520.top/Article/details/gtflozgszc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.haohaochexian.top/Article/details/gtpdtnrcci.html

[T59] Scala：循环
来源：http://dali.jinqigufen.top/Article/details/gtomjgjkwt.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinqigufen.top/Article/details/gtgemrjbno.html

[T60] Scala：折叠
来源：http://dali.dianchejie.cn/Article/details/gtojfxkqvq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hnqzz.top/Article/details/gtcvswuyxf.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtfftxkjtq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.pycfn.com/Article/details/gtfyaqzfri.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtndpxutrk.html

[U01] Py：创建虚拟环境
来源：http://dali.jinqigufen.top/Article/details/gtgrsolqai.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jinyuanbaomall.cn/Article/details/gtasjcbwit.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sweek.top/Article/details/gtddktpxko.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cheryme.top/Article/details/gtjeveabrc.html

[U03] Py：加载 .env 配置
来源：http://dali.hammf.cn/Article/details/gtkcrkixve.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ppjwa.cn/Article/details/gtuhjxoobc.html

[U04] Py：变量调试打印
来源：http://dali.jyoumei.cn/Article/details/gtzrfytcji.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.pycfn.com/Article/details/gtracmbsan.html

[U05] Py：列表去重且保序
来源：http://dali.jiagoushi.top/Article/details/gtgopctqiq.html

list(dict.fromkeys(arr))
来源：http://dali.chenzaomai.com/Article/details/gtrrquqrpf.html

[U06] Py：合并两个字典
来源：http://dali.yj20258888.top/Article/details/gtlzbtwirr.html

{**a, **b}
来源：http://dali.hnxiangtu.top/Article/details/gtfzrlntkx.html

[U07] Py：反转字典键值
来源：http://dali.9152youxi.cn/Article/details/gtqiuactyg.html

{v: k for k, v in d.items()}
来源：http://dali.xziqi.cn/Article/details/gtsydzbiiv.html

[U08] Py：展平二维列表
来源：http://dali.hongshengwenyu.top/Article/details/gtdxqzfcdq.html

[y for x in nested for y in x]
来源：http://dali.zhongyouzk.top/Article/details/gtyhnrrvuu.html

[U09] Py：字典取最大值的键
来源：http://dali.wangdashe.top/Article/details/gtqyzkdnqj.html

max(d, key=d.get)
来源：http://dali.ydzc1.top/Article/details/gtrcjpspht.html

[U10] Py：按值排序字典
来源：http://dali.xziqi.cn/Article/details/gtaeryaaoa.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xuetiantiany.cn/Article/details/gtmpwghcda.html

[U11] Py：生成器表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gtufuktohm.html

(x * 2 for x in arr)
来源：http://dali.gzhubu.top/Article/details/gttxlldlpg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.guowangkeji.top/Article/details/gtvkbpwkgm.html

Counter(arr).most_common(3)
来源：http://dali.iojbl.cn/Article/details/gtewqylbph.html

[U13] Py：固定长度队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gthpgwdonu.html

deque(maxlen=10)
来源：http://dali.cheryme.top/Article/details/gtbhpyeyix.html

[U14] Py：分组收集到列表
来源：http://dali.aibaodan.cn/Article/details/gtivwtvmhq.html

defaultdict(list)
来源：http://dali.gotoacloud.top/Article/details/gtkparoztg.html


<!-- 参考信息 -->