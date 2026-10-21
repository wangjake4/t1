代发 wailian999

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gaohongyu789.top/Article/details/gtzlqtjhxu.html

[R72] 等待端口就绪
来源：http://dali.bjfxy.top/Article/details/gtbwnthhcg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.havefunace.top/Article/details/gtexcqowmn.html

[R73] 分割大日志
来源：http://dali.316326.xyz/Article/details/gtpyfuirpi.html

split -l 1000 big.log part_
来源：http://dali.316326.xyz/Article/details/gtgfvnnkfm.html

[R74] 批量重命名
来源：http://dali.ehwqpu.com/Article/details/gtpttmwdzq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hongshengwenyu.top/Article/details/gtcpsfjdgm.html

[R75] 导出环境变量
来源：http://dali.sufxvd.cn/Article/details/gtumqykgfw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yangfankeji.com/Article/details/gtktzxqccd.html

[R76] 使用临时文件
来源：http://dali.xziqi.cn/Article/details/gtmsgoxbpo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.smart0.xyz/Article/details/gtwbuiemaw.html

[R77] 读取用户输入
来源：http://dali.cucudq.cn/Article/details/gtmutclltd.html

read -rp "请输入: " ans
来源：http://dali.cashguo.top/Article/details/gtecdodsfx.html

[R78] 交互式菜单
来源：http://dali.quarkkingdee.top/Article/details/gtvkmwnfiv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkrsklmvy.html

[R79] 解析命令行选项
来源：http://dali.chenjidiqi.icu/Article/details/gtwvfbcsti.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.daria6918.cn/Article/details/gttfgfsscm.html

[R80] 查看脚本执行耗时
来源：http://dali.jinqigfzy.top/Article/details/gtxuqbszdu.html

time ./run.sh
来源：http://dali.jqgfzy.top/Article/details/gtzmvhmpms.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtpekivmfe.html

S. C / C++ 专题
来源：http://dali.gaohongyu789.top/Article/details/gtqonyqbtv.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtdlvxzvfu.html

[S01] C：Hello World
来源：http://dali.sxryk.cn/Article/details/gtulymvkwp.html

#include <stdio.h>
来源：http://dali.0kj1m.cn/Article/details/gtunzbvepj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhixingplan.top/Article/details/gtbovcivae.html

[S02] C：变量与格式化输出
来源：http://dali.jinqigfzy.top/Article/details/gtlhzuzvts.html

int a = 10; printf("%d\n", a);
来源：http://dali.pycfn.com/Article/details/gtmkitquom.html

[S03] C：读入整数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtucvesnzi.html

int x; scanf("%d", &x);
来源：http://dali.yuxming.cn/Article/details/gtfcghrsxi.html

[S04] C：字符串复制
来源：http://dali.hfpthk.cn/Article/details/gtjaivefeq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hywenlv.cn/Article/details/gtudbfaxzt.html

[S05] C：字符串长度
来源：http://dali.316326.xyz/Article/details/gtdyuumobm.html

strlen(s)
来源：http://dali.iojbl.cn/Article/details/gtzhfiraan.html

[S06] C：字符串比较
来源：http://dali.tanke756.top/Article/details/gtetcjqpxd.html

strcmp(a, b) == 0
来源：http://dali.jinqigfzy.top/Article/details/gtzwqtdptx.html

[S07] C：数组遍历求和
来源：http://dali.mhx1999.top/Article/details/gtvarjebyd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jlsjyb.cn/Article/details/gtxuqcdutm.html

[S08] C：动态内存分配与释放
来源：http://dali.yj20258.top/Article/details/gtvaueweax.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jiagoushi.top/Article/details/gteiavazht.html

[S09] C：结构体定义与初始化
来源：http://dali.jianghu66.top/Article/details/gtfcqttbsj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.vqdsnc.cn/Article/details/gtqlhmxkis.html

[S10] C：指针与解引用
来源：http://dali.jianghu66.top/Article/details/gtfyhjwfdy.html

int *p = &a;  *p = 5;
来源：http://dali.tian-w.cn/Article/details/gtxbithgip.html

[S11] C：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gtlelfhkbr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwptimige.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.andypj.xyz/Article/details/gtearbkqpy.html

fclose(f);
来源：http://dali.xylfe.cn/Article/details/gtmylcxrca.html

[S12] C：写文件
来源：http://dali.0kj1m.cn/Article/details/gtsrlgwqxj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.redwolf501.top/Article/details/gtewrajjzp.html

[S13] C：宏定义
来源：http://dali.hysaishi.cn/Article/details/gtgfdiqsij.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqdkfddz.html

[S14] C：枚举
来源：http://dali.daria6918.cn/Article/details/gtapjaxuxx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.smart0.xyz/Article/details/gttvuommmq.html

[S15] C：类型转换
来源：http://dali.andypj.xyz/Article/details/gtttqofkuh.html

(double) a / b
来源：http://dali.gaohongyu789.top/Article/details/gtgxaxcvhf.html

[S16] C：位操作置位
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthpheayp.html

x |= (1 << 3);
来源：http://dali.jinqigufen.top/Article/details/gtcylmtyoy.html

[S17] C：安全拼接字符串
来源：http://dali.vqdsnc.cn/Article/details/gtsqawwyrf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.guowangkeji.top/Article/details/gtmobxxfvx.html

[S18] C：命令行参数
来源：http://dali.c1oappe.top/Article/details/gtkpkoiocm.html

int main(int argc, char **argv)
来源：http://dali.hongshengwenyu.top/Article/details/gtmeisnaeq.html

[S19] C：快速排序
来源：http://dali.gaohongyu789.top/Article/details/gtnxuaksyi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.quarkkingdee.top/Article/details/gtmpjrgqpo.html

[S20] C：二分查找
来源：http://dali.cdnleiting.top/Article/details/gtnrcdkugy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.vqdsnc.cn/Article/details/gtbrasxfbj.html

[S21] C：字符类别判断
来源：http://dali.fengsongda.top/Article/details/gtysgrvggz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ppjwa.cn/Article/details/gtgarafkcd.html

[S22] C：字符串转数字
来源：http://dali.sysykeji.top/Article/details/gtyywwupmn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhixingplan.top/Article/details/gtqtzdqxky.html

[S23] C：随机数
来源：http://dali.jlsjyb.cn/Article/details/gtuxdyxpfd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cucudq.cn/Article/details/gtiwobocdk.html

[S24] C：获取本地时间
来源：http://dali.shzxlz.cn/Article/details/gtqggqjsvj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gtaanqgmhe.html

[S25] C：内存拷贝
来源：http://dali.hfpthk.cn/Article/details/gtdyxrtzoj.html

memcpy(dst, src, n);
来源：http://dali.yangfankeji.com/Article/details/gtetvhkhxf.html

[S26] C：内存清零
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoulgzqqn.html

memset(a, 0, sizeof a);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsoapbspz.html

[S27] C：定义常量
来源：http://dali.zhixingplan.top/Article/details/gtibaiecys.html

const double PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gtstgcsutr.html

[S28] C：静态变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtisrxypzc.html

static int counter = 0;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjgngorln.html

[S29] C：变参函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtopgogdqy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigfzy.top/Article/details/gtyxzuaunc.html

[S30] C：头文件保护
来源：http://dali.mhx1999.top/Article/details/gtbftuqifa.html

#ifndef X_H
来源：http://dali.iojbl.cn/Article/details/gtqumuuyjb.html

#define X_H
来源：http://dali.jinqigufen.top/Article/details/gtfenzppto.html

#endif
来源：http://dali.chenlongwang.top/Article/details/gtrfadstee.html

[S31] C++：Hello World
来源：http://dali.wangdashe.top/Article/details/gtzqrropcj.html

#include <iostream>
来源：http://dali.chenjidiqi.icu/Article/details/gtkgeplyrt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtiznrsbyh.html

[S32] C++：字符串
来源：http://dali.sweek.top/Article/details/gtokpvviqp.html

std::string s = "hi";  s += "!";
来源：http://dali.hfpthk.cn/Article/details/gtqphcgzep.html

[S33] C++：vector 增删
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtanpmjcwc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hfpthk.cn/Article/details/gtqdciyjzh.html

[S34] C++：遍历 vector
来源：http://dali.zhengqikj.top/Article/details/gtbnuzapyn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ehwqpu.com/Article/details/gtljtsqteq.html

[S35] C++：map
来源：http://dali.pycfn.com/Article/details/gtutbmrpxl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nwbrower.top/Article/details/gtnlkazwyd.html

[S36] C++：unordered_map
来源：http://dali.haohaochexian.top/Article/details/gtgkzgkwfm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gtygqpqgpg.html

[S37] C++：set
来源：http://dali.cqqwz.cn/Article/details/gtjisxzpjx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xylfe.cn/Article/details/gtqzjnufvn.html

[S38] C++：排序
来源：http://dali.chenlongwang.top/Article/details/gtspglmmxr.html

std::sort(v.begin(), v.end());
来源：http://dali.hywenlv.cn/Article/details/gtsuzoxllc.html

[S39] C++：自定义比较器排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtspbxwctv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.316326.xyz/Article/details/gttoyiehru.html

[S40] C++：查找元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtqebvjyzg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.c1oappe.top/Article/details/gtakomhfyx.html

[S41] C++：类与构造函数
来源：http://dali.yueranfly.top/Article/details/gtxoiazgkb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gtvltvewvz.html

[S42] C++：继承与虚函数
来源：http://dali.wangdashe.top/Article/details/gttpjxvrws.html

class B : public Base { public: void f() override {} };
来源：http://dali.sxryk.cn/Article/details/gtuooejyxf.html

[S43] C++：智能指针
来源：http://dali.sufxvd.cn/Article/details/gtddfcssro.html

auto p = std::make_unique<int>(5);
来源：http://dali.kuanghao11.cn/Article/details/gthndrwypr.html

[S44] C++：引用传参
来源：http://dali.pycfn.com/Article/details/gtiyrzmncw.html

void inc(int &x) { ++x; }
来源：http://dali.316326.xyz/Article/details/gtbraehmmb.html

[S45] C++：lambda
来源：http://dali.feifeiyinyue.top/Article/details/gtvkivzqqe.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ppjwa.cn/Article/details/gtugojzgmb.html

[S46] C++：函数模板
来源：http://dali.yongpay.top/Article/details/gttvaykwhy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yj20258888.top/Article/details/gttkwaksvh.html

[S47] C++：结构化绑定遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqtcdxwhv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.fengsongda.top/Article/details/gtzhgnirra.html

[S48] C++：逐行读文件
来源：http://dali.meibo888.top/Article/details/gttmfixhli.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.wangdashe.top/Article/details/gtdxbuetus.html

while (std::getline(in, line)) { }
来源：http://dali.yonumen.top/Article/details/gtrmdvbsaw.html

[S49] C++：写文件
来源：http://dali.jianghu66.top/Article/details/gtzqzuzxtf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.kuanghao11.cn/Article/details/gtxyiqdwah.html

[S50] C++：格式化数字
来源：http://dali.birdmap.top/Article/details/gtpjtuowwp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj20258.top/Article/details/gtobwpvmne.html

[S51] C++：显式类型转换
来源：http://dali.sufxvd.cn/Article/details/gtgfbjsdqo.html

static_cast<double>(a) / b
来源：http://dali.gaohongyu789.top/Article/details/gtglrqkbmu.html

[S52] C++：const 与 noexcept
来源：http://dali.feifeiyinyue.top/Article/details/gtwbpopeod.html

int size() const noexcept { return n_; }
来源：http://dali.fzhhl.top/Article/details/gtmdvympts.html

[S53] C++：移动语义
来源：http://dali.gaohongyu789.top/Article/details/gtjyzgtnuw.html

std::vector<int> w = std::move(v);
来源：http://dali.jqgufenzy.top/Article/details/gtaitzttjl.html

[S54] C++：异常处理
来源：http://dali.shangyingyoupin.top/Article/details/gtxexvxhek.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinqigufen.top/Article/details/gtkedzvbdn.html

[S55] C++：结构化绑定
来源：http://dali.hammf.cn/Article/details/gtpikwudsf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ivvv.top/Article/details/gtimbdcoib.html

[S56] C++：optional
来源：http://dali.yonumen.top/Article/details/gtmglzxuma.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shuidangran.top/Article/details/gtfmrmzbgl.html

[S57] C++：编译期常量
来源：http://dali.yj202588.top/Article/details/gtqvgesfgw.html

constexpr int N = 10;
来源：http://dali.nanxuanxn.top/Article/details/gtkjigovkj.html

[S58] C++：命名空间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnvmrrexf.html

namespace ns { int f() { return 1; } }
来源：http://dali.gotoacloud.top/Article/details/gtxpypexlv.html

[S59] C++：静态断言
来源：http://dali.tianlin.xyz/Article/details/gtvwgqrwtb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.nanxinkj.top/Article/details/gtkczddjob.html

[S60] C++：遍历并删除元素
来源：http://dali.aizwys.cn/Article/details/gtrlaclmpf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.vqdsnc.cn/Article/details/gtbbojrcsl.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtloxuxflt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenzaomai.com/Article/details/gtnwwinnkx.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gttlaiiizw.html

[T01] Kotlin：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtqaiuhqwn.html

println("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gttaeofyxx.html

[T02] Kotlin：变量
来源：http://dali.zhongyouzk.top/Article/details/gttsbefngv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hysaishi.cn/Article/details/gtdrhopuiu.html

[T03] Kotlin：字符串模板
来源：http://dali.cucudq.cn/Article/details/gtsqyxvogl.html

"值: $b"
来源：http://dali.shzxlz.cn/Article/details/gtuzhyguzs.html

[T04] Kotlin：空安全
来源：http://dali.hammf.cn/Article/details/gtdwhqdzvg.html

val n: String? = null;  n?.length
来源：http://dali.sweek.top/Article/details/gttqygdicr.html

[T05] Kotlin：when 表达式
来源：http://dali.hongshengwenyu.top/Article/details/gtodifgqla.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtllfxchty.html

[T06] Kotlin：集合映射
来源：http://dali.cashguo.top/Article/details/gtgvviwaow.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.mhx1999.top/Article/details/gtfepbjvls.html

[T07] Kotlin：集合过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gtrcwppnjz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zdqjudy.top/Article/details/gtlitbfnvw.html

[T08] Kotlin：数据类
来源：http://dali.chenzaomai.com/Article/details/gtnwcgulnz.html

data class User(val name: String, val age: Int)
来源：http://dali.ehwqpu.com/Article/details/gtaaaujefo.html

[T09] Kotlin：扩展函数
来源：http://dali.sweek.top/Article/details/gtfqaiqavo.html

fun String.exclaim() = this + "!"
来源：http://dali.sxryk.cn/Article/details/gtdntnxmuh.html

[T10] Kotlin：默认参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtfvsedgee.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xinyue.icu/Article/details/gtlboovnqj.html

[T11] Kotlin：协程
来源：http://dali.hfpthk.cn/Article/details/gtjmjwxnil.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.redwolf501.top/Article/details/gtvatiaprp.html

[T12] Kotlin：解构声明
来源：http://dali.birdmap.top/Article/details/gtxdvksgvk.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtrdnqtxtf.html

[T13] Kotlin：只读 Map
来源：http://dali.tianlin.xyz/Article/details/gtnmilltty.html

val m = mapOf("a" to 1)
来源：http://dali.yj20258888.top/Article/details/gtuflrkyuz.html

[T14] Kotlin：循环
来源：http://dali.andypj.xyz/Article/details/gtcviuphkj.html

for (i in 1..10) println(i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaoybnajr.html

[T15] Kotlin：接口
来源：http://dali.guowangkeji.top/Article/details/gtmqoenntb.html

interface Shape { fun area(): Double }
来源：http://dali.hywenlv.cn/Article/details/gtrgsbsmqs.html

[T16] Swift：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtwuldetbm.html

print("Hello")
来源：http://dali.hnqzz.top/Article/details/gthfefgfyd.html

[T17] Swift：变量与常量
来源：http://dali.tanke756.top/Article/details/gtgonxelmw.html

var a = 1;  let b = 2
来源：http://dali.yongpay.top/Article/details/gtxioaojmw.html

[T18] Swift：字符串插值
来源：http://dali.yuxming.cn/Article/details/gtjausmody.html

"值: \(b)"
来源：http://dali.9152youxi.cn/Article/details/gtkoocyujd.html

[T19] Swift：可选绑定
来源：http://dali.xinyue.icu/Article/details/gtcuvboayu.html

if let n = opt { print(n) }
来源：http://dali.yj202588.top/Article/details/gtxhrjsuwz.html

[T20] Swift：数组操作
来源：http://dali.quarkkingdee.top/Article/details/gtardoasmb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jlsjyb.cn/Article/details/gtilrlxtmn.html

[T21] Swift：遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gtfuzdqwft.html

for x in a { print(x) }
来源：http://dali.shanyushiyangtech.top/Article/details/gthngycnsq.html

[T22] Swift：字典
来源：http://dali.xuetiantiany.cn/Article/details/gtvzskrskm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.chenjidiqi.icu/Article/details/gtjiradlwc.html

[T23] Swift：函数
来源：http://dali.xuanzx.com/Article/details/gtyvanmigx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.havefunace.top/Article/details/gtthbvsdyp.html

[T24] Swift：闭包
来源：http://dali.jiagoushi.top/Article/details/gtsulmjuui.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yonumen.top/Article/details/gtqtaavuus.html

[T25] Swift：结构体
来源：http://dali.pycfn.com/Article/details/gtubrbmxut.html

struct P { var x: Int }
来源：http://dali.pengpengdd.cyou/Article/details/gtieynwwkj.html

[T26] Swift：类与重写
来源：http://dali.dianchejie.cn/Article/details/gtczwfjrrs.html

class A: Base { override func f() {} }
来源：http://dali.chenlongwang.top/Article/details/gtjaqxgiqe.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gttiqpwhnv.html

do { try f() } catch { print(error) }
来源：http://dali.shangyingyoupin.top/Article/details/gtjlwlxcmx.html

[T28] Swift：枚举
来源：http://dali.iojbl.cn/Article/details/gtndtpqdhz.html

enum Color { case red, green }
来源：http://dali.shuidangran.top/Article/details/gttwjiback.html

[T29] Swift：guard 提前返回
来源：http://dali.fengsongda.top/Article/details/gtongyvchn.html

guard let x = opt else { return }
来源：http://dali.yj20258.top/Article/details/gtqqrdpavm.html

[T30] Swift：协议
来源：http://dali.bjfxy.top/Article/details/gtgfqhkitj.html

protocol Shape { func area() -> Double }
来源：http://dali.yuanzhike.top/Article/details/gttjfutczh.html

[T31] Lua：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtlonifkid.html

print("Hello")
来源：http://dali.guannengcc.top/Article/details/gtsgjrjsml.html

[T32] Lua：局部变量
来源：http://dali.pengpengdd.cyou/Article/details/gtjhnjidwt.html

local a = 1
来源：http://dali.hongshengwenyu.top/Article/details/gtngcxjhnc.html

[T33] Lua：表（数组）
来源：http://dali.jqgufenzy.top/Article/details/gtbgkiwicr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ppjwa.cn/Article/details/gtrxbwsnjb.html

[T34] Lua：遍历表
来源：http://dali.yj20258.top/Article/details/gtmdsednvm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nanxinkj.top/Article/details/gtltjkyaaf.html

[T35] Lua：字典表
来源：http://dali.mhx1999.top/Article/details/gtbvrgkuhi.html

local d = { a = 1 };  d.b = 2
来源：http://dali.guannengcc.top/Article/details/gtubernfdo.html

[T36] Lua：函数
来源：http://dali.pengpengdd.cyou/Article/details/gtigmmnszg.html

function add(a, b) return a + b end
来源：http://dali.hfpthk.cn/Article/details/gtmviawstl.html

[T37] Lua：字符串拼接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqgbrvvvm.html

"a" .. "b"
来源：http://dali.jyoumei.cn/Article/details/gttnsatapl.html

[T38] Lua：条件
来源：http://dali.hfpthk.cn/Article/details/gtohdlqmqz.html

if x > 0 then print("正") end
来源：http://dali.birdmap.top/Article/details/gtsuhzxils.html

[T39] Lua：模式匹配
来源：http://dali.fzhhl.top/Article/details/gtdqgmtiob.html

string.find(s, "%d+")
来源：http://dali.smart0.xyz/Article/details/gttegrkwlq.html

[T40] Lua：元表
来源：http://dali.nwbrower.top/Article/details/gtvagtvrks.html

setmetatable({}, { __index = base })
来源：http://dali.yvedp.cn/Article/details/gtcikrlwzj.html

[T41] Perl：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtlsbhmmim.html

print "Hello\n";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkwxeucfj.html

[T42] Perl：变量类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfjafxadx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.daxiang520.top/Article/details/gtfdwvrupx.html

[T43] Perl：字符串插值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfbbshvgu.html

"值: $a"
来源：http://dali.yj20258.top/Article/details/gtgnhqaywh.html

[T44] Perl：条件
来源：http://dali.redwolf501.top/Article/details/gttxdzqmus.html

if ($a > 0) { print "正"; }
来源：http://dali.yvedp.cn/Article/details/gtfhuxkmwe.html

[T45] Perl：数组遍历
来源：http://dali.ybcxt.top/Article/details/gtoivrhcwu.html

for my $x (@arr) { print $x; }
来源：http://dali.zhiwuduotai.top/Article/details/gtbbhtzuaa.html

[T46] Perl：哈希操作
来源：http://dali.pengpengdd.cyou/Article/details/gtzspbtwgv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yangfankeji.com/Article/details/gtofybzhzt.html

[T47] Perl：正则捕获
来源：http://dali.xziqi.cn/Article/details/gtxjagfzoa.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.wangshuangyany.cn/Article/details/gtexwxuopj.html

[T48] Perl：正则替换
来源：http://dali.gzhubu.top/Article/details/gtdjzazevo.html

$s =~ s/old/new/g;
来源：http://dali.daria6918.cn/Article/details/gtdptiyczb.html

[T49] Perl：函数
来源：http://dali.yvedp.cn/Article/details/gtukrzhrte.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gtxbaavkhc.html

[T50] Perl：逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gtbsghdhaj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.nwbrower.top/Article/details/gtqvrvhant.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.meibo888.top/Article/details/gthbwpbkzd.html

[T51] Scala：Hello World
来源：http://dali.jianghu66.top/Article/details/gtnngowbck.html

println("Hello")
来源：http://dali.gogol.net.cn/Article/details/gtbkifojpe.html

[T52] Scala：变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtolekmwmh.html

val a = 1;  var b = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtugimoyqk.html

[T53] Scala：字符串插值
来源：http://dali.chenlongwang.top/Article/details/gtnbmfvabf.html

s"值: $b"
来源：http://dali.xylfe.cn/Article/details/gtrsgeimgx.html

[T54] Scala：集合映射
来源：http://dali.gzhubu.top/Article/details/gtazscpust.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.aibaodan.cn/Article/details/gtoyzszlnp.html

[T55] Scala：集合过滤
来源：http://dali.cheryme.top/Article/details/gtenovthsd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jlsjyb.cn/Article/details/gtrtztlxio.html

[T56] Scala：样例类
来源：http://dali.316326.xyz/Article/details/gtxwkyrjzh.html

case class User(name: String, age: Int)
来源：http://dali.sysykeji.top/Article/details/gtreeczckv.html

[T57] Scala：模式匹配
来源：http://dali.chenlongwang.top/Article/details/gttopcpfdq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdzljvdd.html

[T58] Scala：函数定义
来源：http://dali.zhixingplan.top/Article/details/gtvczhixvz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhengqikj.top/Article/details/gtuevendvr.html

[T59] Scala：循环
来源：http://dali.sysykeji.top/Article/details/gtjitdodeo.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgvetaqfu.html

[T60] Scala：折叠
来源：http://dali.jinghuilouyu.cn/Article/details/gtusaxpykc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xuanzx.com/Article/details/gtocavpcky.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtyqevasqi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gaohongyu789.top/Article/details/gtjmogjjjf.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtwkfagncs.html

[U01] Py：创建虚拟环境
来源：http://dali.316326.xyz/Article/details/gtmwxqskmv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shanyushiyangkeji.top/Article/details/gthplwjneh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ppjwa.cn/Article/details/gtkmlxsvbw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cdnleiting.top/Article/details/gtekvafwpx.html

[U03] Py：加载 .env 配置
来源：http://dali.zhoulong.xyz/Article/details/gtidsstepx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gtjgciszgb.html

[U04] Py：变量调试打印
来源：http://dali.xuetiantiany.cn/Article/details/gtqqfmhvii.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shanyushiyangkeji.top/Article/details/gteetjexzy.html

[U05] Py：列表去重且保序
来源：http://dali.jianghu66.top/Article/details/gtaactdznd.html

list(dict.fromkeys(arr))
来源：http://dali.hongshengwenyu.top/Article/details/gtykhbdejj.html

[U06] Py：合并两个字典
来源：http://dali.ehwqpu.com/Article/details/gtxumxoihe.html

{**a, **b}
来源：http://dali.chenzaomai.com/Article/details/gtvnzoerhc.html

[U07] Py：反转字典键值
来源：http://dali.dianchejie.cn/Article/details/gtiqgphmzz.html

{v: k for k, v in d.items()}
来源：http://dali.kuanghao11.cn/Article/details/gtollrxshh.html

[U08] Py：展平二维列表
来源：http://dali.kuanghao11.cn/Article/details/gtiyngpinw.html

[y for x in nested for y in x]
来源：http://dali.snrcjt.cn/Article/details/gtuitpvdaq.html

[U09] Py：字典取最大值的键
来源：http://dali.ehwqpu.com/Article/details/gtvpulgllt.html

max(d, key=d.get)
来源：http://dali.zdqjudy.top/Article/details/gtozmwocmm.html

[U10] Py：按值排序字典
来源：http://dali.wangdashe.top/Article/details/gtmetailob.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.c1oappe.top/Article/details/gtqjaqtsxf.html

[U11] Py：生成器表达式
来源：http://dali.hfpthk.cn/Article/details/gtluqjgnoj.html

(x * 2 for x in arr)
来源：http://dali.tianlin.xyz/Article/details/gtzdyhhbww.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.snrcjt.cn/Article/details/gtcpcdmwxb.html

Counter(arr).most_common(3)
来源：http://dali.hnqzz.top/Article/details/gtpxlrerxf.html


<!-- 参考信息 -->