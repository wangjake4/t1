代发 wailian999

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cucudq.cn/Article/details/gtmgwpslvi.html

[R72] 等待端口就绪
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzgaqanvj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.wangshuangyany.cn/Article/details/gtzsmsegpq.html

[R73] 分割大日志
来源：http://dali.zhengqikj.top/Article/details/gtdnltpvzu.html

split -l 1000 big.log part_
来源：http://dali.gogol.net.cn/Article/details/gtgvamiacx.html

[R74] 批量重命名
来源：http://dali.tianlin.xyz/Article/details/gtursfxcmr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yvedp.cn/Article/details/gtihsmmyzy.html

[R75] 导出环境变量
来源：http://dali.yanxiufei.cn/Article/details/gtpaliunrj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.snrcjt.cn/Article/details/gtnuvhodkq.html

[R76] 使用临时文件
来源：http://dali.hnqzz.top/Article/details/gtbagucfrz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.mhx1999.top/Article/details/gtwmrpdbqj.html

[R77] 读取用户输入
来源：http://dali.sxryk.cn/Article/details/gtlpxgzmtn.html

read -rp "请输入: " ans
来源：http://dali.pengpengdd.cyou/Article/details/gtgzambecg.html

[R78] 交互式菜单
来源：http://dali.dianchejie.cn/Article/details/gtpjveweqq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xinyue.icu/Article/details/gtypnkdjjm.html

[R79] 解析命令行选项
来源：http://dali.cashguo.top/Article/details/gtyxeoowgm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.redwolf501.top/Article/details/gtbqfsixgh.html

[R80] 查看脚本执行耗时
来源：http://dali.hysaishi.cn/Article/details/gtvddvweak.html

time ./run.sh
来源：http://dali.yongpay.top/Article/details/gtwvlhpoey.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtagiyaqbl.html

S. C / C++ 专题
来源：http://dali.sweek.top/Article/details/gtnwsfvpxo.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtpxosqaad.html

[S01] C：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtcirlrjsh.html

#include <stdio.h>
来源：http://dali.316326.xyz/Article/details/gtzttoyfir.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.pengpengdd.cyou/Article/details/gthauayecw.html

[S02] C：变量与格式化输出
来源：http://dali.gzhubu.top/Article/details/gtyvwxgglm.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhiwuduotai.top/Article/details/gtfwbirjjr.html

[S03] C：读入整数
来源：http://dali.hfpthk.cn/Article/details/gtjcoajjog.html

int x; scanf("%d", &x);
来源：http://dali.aibaodan.cn/Article/details/gtriiakdsm.html

[S04] C：字符串复制
来源：http://dali.jinqigfzy.top/Article/details/gtltgnwhce.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yonumen.top/Article/details/gtkzgxtfad.html

[S05] C：字符串长度
来源：http://dali.bjfxy.top/Article/details/gtteulpcjo.html

strlen(s)
来源：http://dali.cheryme.top/Article/details/gtijhqfxah.html

[S06] C：字符串比较
来源：http://dali.cashguo.top/Article/details/gtglftreym.html

strcmp(a, b) == 0
来源：http://dali.xylfe.cn/Article/details/gtsrgmwqly.html

[S07] C：数组遍历求和
来源：http://dali.nanxuanxn.top/Article/details/gtstpkpekb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shangyingyoupin.top/Article/details/gtdzeyvjfk.html

[S08] C：动态内存分配与释放
来源：http://dali.jinyuanbaomall.cn/Article/details/gtidjqvidp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ivvv.top/Article/details/gtyxaueyfz.html

[S09] C：结构体定义与初始化
来源：http://dali.0kj1m.cn/Article/details/gtmrfxcvhn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jianghu66.top/Article/details/gtlslqwdig.html

[S10] C：指针与解引用
来源：http://dali.jqgufenzy.top/Article/details/gthvdtyxni.html

int *p = &a;  *p = 5;
来源：http://dali.hysaishi.cn/Article/details/gtsunoutiu.html

[S11] C：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gtqzitgxdp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj202588.top/Article/details/gtdfezelbd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gtukcqckxt.html

fclose(f);
来源：http://dali.cashguo.top/Article/details/gtpgxbdlsz.html

[S12] C：写文件
来源：http://dali.kuanghao11.cn/Article/details/gtlbevngee.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jqgfzy.top/Article/details/gtvdeasmfk.html

[S13] C：宏定义
来源：http://dali.redwolf501.top/Article/details/gtdqhgmusi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shangyingyoupin.top/Article/details/gtpmedpubp.html

[S14] C：枚举
来源：http://dali.jinqigufen.top/Article/details/gtqhzstfrt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hnxiangtu.top/Article/details/gtojudtxur.html

[S15] C：类型转换
来源：http://dali.birdmap.top/Article/details/gtfugmnwsq.html

(double) a / b
来源：http://dali.kuanghao11.cn/Article/details/gtglweiszv.html

[S16] C：位操作置位
来源：http://dali.smart0.xyz/Article/details/gtlhmzskxa.html

x |= (1 << 3);
来源：http://dali.dianchejie.cn/Article/details/gtpbfgexay.html

[S17] C：安全拼接字符串
来源：http://dali.tanke756.top/Article/details/gtogvufvaq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfgmqtgtj.html

[S18] C：命令行参数
来源：http://dali.9152youxi.cn/Article/details/gtzigtqujj.html

int main(int argc, char **argv)
来源：http://dali.jiagoushi.top/Article/details/gtwinpggqu.html

[S19] C：快速排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtwrspjqxq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.bjfxy.top/Article/details/gtdbnsekdw.html

[S20] C：二分查找
来源：http://dali.jqgfzy.top/Article/details/gtkolpgohi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.316326.xyz/Article/details/gtuadgyejk.html

[S21] C：字符类别判断
来源：http://dali.sufxvd.cn/Article/details/gtvchhwgtp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.316326.xyz/Article/details/gtsbnsakfk.html

[S22] C：字符串转数字
来源：http://dali.hammf.cn/Article/details/gtxhwpcysv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xziqi.cn/Article/details/gtuwusgbjf.html

[S23] C：随机数
来源：http://dali.guannengcc.top/Article/details/gtgvxulgek.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.dashuyun.cn/Article/details/gtghjxrsmf.html

[S24] C：获取本地时间
来源：http://dali.yongpay.top/Article/details/gtklfulspu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.havefunace.top/Article/details/gtkiigcxul.html

[S25] C：内存拷贝
来源：http://dali.guannengcc.top/Article/details/gtbhxpgels.html

memcpy(dst, src, n);
来源：http://dali.hnxiangtu.top/Article/details/gtmxhowoog.html

[S26] C：内存清零
来源：http://dali.feifeiyinyue.top/Article/details/gthvjajaaq.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gtkdjnuaxe.html

[S27] C：定义常量
来源：http://dali.cdnleiting.top/Article/details/gtmmrqswim.html

const double PI = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gtugkshzup.html

[S28] C：静态变量
来源：http://dali.yueranfly.top/Article/details/gtmlpphlzp.html

static int counter = 0;
来源：http://dali.quarkkingdee.top/Article/details/gtqvrvfreu.html

[S29] C：变参函数
来源：http://dali.gogol.net.cn/Article/details/gtpobwrosd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yuanzhike.top/Article/details/gtobobqimn.html

[S30] C：头文件保护
来源：http://dali.quarkkingdee.top/Article/details/gtfyhpdnce.html

#ifndef X_H
来源：http://dali.hfpthk.cn/Article/details/gtzgggjaxe.html

#define X_H
来源：http://dali.yongpay.top/Article/details/gtuovfmjxs.html

#endif
来源：http://dali.yvedp.cn/Article/details/gtriwpnhtb.html

[S31] C++：Hello World
来源：http://dali.daria6918.cn/Article/details/gtbxbksnek.html

#include <iostream>
来源：http://dali.meibo888.top/Article/details/gtrjotopyg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hnxiangtu.top/Article/details/gtgdqcfeyo.html

[S32] C++：字符串
来源：http://dali.yuanzhike.top/Article/details/gtjmznchpi.html

std::string s = "hi";  s += "!";
来源：http://dali.yuanzhike.top/Article/details/gtlugijeec.html

[S33] C++：vector 增删
来源：http://dali.shangyingyoupin.top/Article/details/gteaxzmkkv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtinbhyvxa.html

[S34] C++：遍历 vector
来源：http://dali.xingfuxueyuan.xyz/Article/details/gterhffstn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zycfv.cn/Article/details/gtitguyvch.html

[S35] C++：map
来源：http://dali.iojbl.cn/Article/details/gtbwndyttw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gtrcdqeqbv.html

[S36] C++：unordered_map
来源：http://dali.jinqigufen.top/Article/details/gtwnnqvpqk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtgrgdphnh.html

[S37] C++：set
来源：http://dali.nwbrower.top/Article/details/gtnrwlwlab.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.iojbl.cn/Article/details/gtznynuxxw.html

[S38] C++：排序
来源：http://dali.chenzaomai.com/Article/details/gtjaoxkkgt.html

std::sort(v.begin(), v.end());
来源：http://dali.zdqjudy.top/Article/details/gtbpsxrgll.html

[S39] C++：自定义比较器排序
来源：http://dali.sysykeji.top/Article/details/gtnegczsvc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yongpay.top/Article/details/gtbivrrwik.html

[S40] C++：查找元素
来源：http://dali.gogol.net.cn/Article/details/gtynmcdgbz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.0kj1m.cn/Article/details/gtovsfgths.html

[S41] C++：类与构造函数
来源：http://dali.iojbl.cn/Article/details/gtsuinpmek.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gthahesnts.html

[S42] C++：继承与虚函数
来源：http://dali.sxryk.cn/Article/details/gtxfmllpwl.html

class B : public Base { public: void f() override {} };
来源：http://dali.9152youxi.cn/Article/details/gtpiczsofs.html

[S43] C++：智能指针
来源：http://dali.aibaodan.cn/Article/details/gtdfhnyhvp.html

auto p = std::make_unique<int>(5);
来源：http://dali.iojbl.cn/Article/details/gtxgpgyqjn.html

[S44] C++：引用传参
来源：http://dali.sufxvd.cn/Article/details/gtmgcxfnyk.html

void inc(int &x) { ++x; }
来源：http://dali.ppjwa.cn/Article/details/gtlppbobqr.html

[S45] C++：lambda
来源：http://dali.xylfe.cn/Article/details/gtrddpssrh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hfpthk.cn/Article/details/gtzitddlez.html

[S46] C++：函数模板
来源：http://dali.shuidangran.top/Article/details/gtltexnxjy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.0kj1m.cn/Article/details/gtqfgboqlv.html

[S47] C++：结构化绑定遍历
来源：http://dali.tian-w.cn/Article/details/gtnpqjqhrx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhongyouzk.top/Article/details/gtqlnxhfqy.html

[S48] C++：逐行读文件
来源：http://dali.meibo888.top/Article/details/gttwfllftv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hammf.cn/Article/details/gtsgowktwp.html

while (std::getline(in, line)) { }
来源：http://dali.meibo888.top/Article/details/gtljrnvpdo.html

[S49] C++：写文件
来源：http://dali.yonumen.top/Article/details/gtlzudasrm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yueranfly.top/Article/details/gtpwvpqsih.html

[S50] C++：格式化数字
来源：http://dali.nanxuanxn.top/Article/details/gtapfuyfkb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gtncfoyeuc.html

[S51] C++：显式类型转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqxecuruz.html

static_cast<double>(a) / b
来源：http://dali.cdnleiting.top/Article/details/gtmahjgpan.html

[S52] C++：const 与 noexcept
来源：http://dali.wangshuangyany.cn/Article/details/gtmxsoxhcd.html

int size() const noexcept { return n_; }
来源：http://dali.xuanzx.com/Article/details/gtihtxdkwy.html

[S53] C++：移动语义
来源：http://dali.sysykeji.top/Article/details/gtdmmcmsew.html

std::vector<int> w = std::move(v);
来源：http://dali.sysykeji.top/Article/details/gttxwmcbxn.html

[S54] C++：异常处理
来源：http://dali.shuidangran.top/Article/details/gtucrvyvec.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jyoumei.cn/Article/details/gtkzciptdy.html

[S55] C++：结构化绑定
来源：http://dali.dianchejie.cn/Article/details/gtlhxulsdc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.smart0.xyz/Article/details/gtqbqbijuf.html

[S56] C++：optional
来源：http://dali.wangshuangyany.cn/Article/details/gtzjacdpnm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xuetiantiany.cn/Article/details/gtkglagfhi.html

[S57] C++：编译期常量
来源：http://dali.redwolf501.top/Article/details/gtwjsownuo.html

constexpr int N = 10;
来源：http://dali.gaohongyu789.top/Article/details/gtqrhgbwdf.html

[S58] C++：命名空间
来源：http://dali.hongshengwenyu.top/Article/details/gtlvmtiqed.html

namespace ns { int f() { return 1; } }
来源：http://dali.snrcjt.cn/Article/details/gtfdvmcpzo.html

[S59] C++：静态断言
来源：http://dali.yonumen.top/Article/details/gtfezrorbu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gotoacloud.top/Article/details/gtrzncurll.html

[S60] C++：遍历并删除元素
来源：http://dali.ybcxt.top/Article/details/gtpzrmbeol.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sysykeji.top/Article/details/gtglrexcum.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtxvjgbskk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj20258.top/Article/details/gtbulemyzh.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtlpzbrgcd.html

[T01] Kotlin：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtiweggsla.html

println("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gtyyjutjer.html

[T02] Kotlin：变量
来源：http://dali.nwbrower.top/Article/details/gtcpyekepc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tianlin.xyz/Article/details/gtyykqlnyn.html

[T03] Kotlin：字符串模板
来源：http://dali.cashguo.top/Article/details/gtsgedppqq.html

"值: $b"
来源：http://dali.shzxlz.cn/Article/details/gtdpfqkwpg.html

[T04] Kotlin：空安全
来源：http://dali.jqgfzy.top/Article/details/gtqgnkyooj.html

val n: String? = null;  n?.length
来源：http://dali.tianlin.xyz/Article/details/gtacdjiwjw.html

[T05] Kotlin：when 表达式
来源：http://dali.cqqwz.cn/Article/details/gtfnmjxteg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tian-w.cn/Article/details/gtrpawnzym.html

[T06] Kotlin：集合映射
来源：http://dali.yj20258.top/Article/details/gtmhwjtbfy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhengqikj.top/Article/details/gtzrsxxxwh.html

[T07] Kotlin：集合过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtwjltdvap.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.9152youxi.cn/Article/details/gtrzsweqtz.html

[T08] Kotlin：数据类
来源：http://dali.chenlongwang.top/Article/details/gtfmqompqf.html

data class User(val name: String, val age: Int)
来源：http://dali.yuxming.cn/Article/details/gtctcctzsn.html

[T09] Kotlin：扩展函数
来源：http://dali.quarkkingdee.top/Article/details/gtwzykkucf.html

fun String.exclaim() = this + "!"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfgmikqel.html

[T10] Kotlin：默认参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtewyruvdf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.wangdashe.top/Article/details/gtgyltjuhg.html

[T11] Kotlin：协程
来源：http://dali.snrcjt.cn/Article/details/gtffwevbcl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hysaishi.cn/Article/details/gttuzgseao.html

[T12] Kotlin：解构声明
来源：http://dali.nanxinkj.top/Article/details/gtbsaycrrl.html

val (a, b) = Pair(1, 2)
来源：http://dali.jianghu66.top/Article/details/gtnufgkwil.html

[T13] Kotlin：只读 Map
来源：http://dali.shuidangran.top/Article/details/gtbuflnful.html

val m = mapOf("a" to 1)
来源：http://dali.gotoacloud.top/Article/details/gtoltagupm.html

[T14] Kotlin：循环
来源：http://dali.yvedp.cn/Article/details/gtjkwyspzz.html

for (i in 1..10) println(i)
来源：http://dali.hywenlv.cn/Article/details/gtfpapavkz.html

[T15] Kotlin：接口
来源：http://dali.xylfe.cn/Article/details/gtdsdlsmkr.html

interface Shape { fun area(): Double }
来源：http://dali.hammf.cn/Article/details/gtgjoitdyu.html

[T16] Swift：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtxqlxtoon.html

print("Hello")
来源：http://dali.sysykeji.top/Article/details/gtqjclfben.html

[T17] Swift：变量与常量
来源：http://dali.nanxinkj.top/Article/details/gtypujfxqx.html

var a = 1;  let b = 2
来源：http://dali.yueranfly.top/Article/details/gtgpqlnbqd.html

[T18] Swift：字符串插值
来源：http://dali.zycfv.cn/Article/details/gthmpvywix.html

"值: \(b)"
来源：http://dali.cdnleiting.top/Article/details/gtsqrobxpo.html

[T19] Swift：可选绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gttuyjlbwd.html

if let n = opt { print(n) }
来源：http://dali.shuidangran.top/Article/details/gtwizjealz.html

[T20] Swift：数组操作
来源：http://dali.yueranfly.top/Article/details/gtnuizgndw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.svipenyu.cn/Article/details/gtktmuprsd.html

[T21] Swift：遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtvcfsngkr.html

for x in a { print(x) }
来源：http://dali.xuanzx.com/Article/details/gtgbuliqqt.html

[T22] Swift：字典
来源：http://dali.hnxiangtu.top/Article/details/gtzrsyvqcd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinqigfzy.top/Article/details/gtesvequkj.html

[T23] Swift：函数
来源：http://dali.sxryk.cn/Article/details/gtjtidndjt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sysykeji.top/Article/details/gtyvjaaauw.html

[T24] Swift：闭包
来源：http://dali.daria6918.cn/Article/details/gttjgfkvzg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.fengsongda.top/Article/details/gtpbvlompi.html

[T25] Swift：结构体
来源：http://dali.havefunace.top/Article/details/gtosiqlvpk.html

struct P { var x: Int }
来源：http://dali.fzhhl.top/Article/details/gtqquzraqu.html

[T26] Swift：类与重写
来源：http://dali.aizwys.cn/Article/details/gteyvmwhar.html

class A: Base { override func f() {} }
来源：http://dali.yuxming.cn/Article/details/gtsarzqakn.html

[T27] Swift：错误处理
来源：http://dali.sysykeji.top/Article/details/gtovbbwsng.html

do { try f() } catch { print(error) }
来源：http://dali.yanxiufei.cn/Article/details/gttwcokrqt.html

[T28] Swift：枚举
来源：http://dali.jqgufenzy.top/Article/details/gtofnqfasq.html

enum Color { case red, green }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoerwivmj.html

[T29] Swift：guard 提前返回
来源：http://dali.jiagoushi.top/Article/details/gtaxqillnv.html

guard let x = opt else { return }
来源：http://dali.ybcxt.top/Article/details/gtauzvrovd.html

[T30] Swift：协议
来源：http://dali.pengpengdd.cyou/Article/details/gtdzpqccrr.html

protocol Shape { func area() -> Double }
来源：http://dali.zhiwuduotai.top/Article/details/gtnxzccyvr.html

[T31] Lua：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtvqlndvop.html

print("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gtaymrtbyt.html

[T32] Lua：局部变量
来源：http://dali.meibo888.top/Article/details/gtjtaxwnif.html

local a = 1
来源：http://dali.haohaochexian.top/Article/details/gtbgvxatzr.html

[T33] Lua：表（数组）
来源：http://dali.xinyue.icu/Article/details/gtpuobtrky.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinqigufen.top/Article/details/gtmznjfbzr.html

[T34] Lua：遍历表
来源：http://dali.birdmap.top/Article/details/gtirpvghqy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.andypj.xyz/Article/details/gtigznfmim.html

[T35] Lua：字典表
来源：http://dali.yanxiufei.cn/Article/details/gtvitltfgr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xylfe.cn/Article/details/gtashmcyig.html

[T36] Lua：函数
来源：http://dali.daria6918.cn/Article/details/gtdohymkzh.html

function add(a, b) return a + b end
来源：http://dali.quarkkingdee.top/Article/details/gttawqaauu.html

[T37] Lua：字符串拼接
来源：http://dali.redwolf501.top/Article/details/gtyyxgiwlf.html

"a" .. "b"
来源：http://dali.cashguo.top/Article/details/gtkokbcqdx.html

[T38] Lua：条件
来源：http://dali.gzhubu.top/Article/details/gtwwdxxixm.html

if x > 0 then print("正") end
来源：http://dali.xuetiantiany.cn/Article/details/gtiapmhutb.html

[T39] Lua：模式匹配
来源：http://dali.chenzaomai.com/Article/details/gtuwduyfol.html

string.find(s, "%d+")
来源：http://dali.0kj1m.cn/Article/details/gtbkuweaow.html

[T40] Lua：元表
来源：http://dali.birdmap.top/Article/details/gthgelggwl.html

setmetatable({}, { __index = base })
来源：http://dali.havefunace.top/Article/details/gtvzadecvk.html

[T41] Perl：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtpxarseuj.html

print "Hello\n";
来源：http://dali.shangyingyoupin.top/Article/details/gtniwibkfp.html

[T42] Perl：变量类型
来源：http://dali.xuanzx.com/Article/details/gtiuiejbgt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cashguo.top/Article/details/gtytgbnivj.html

[T43] Perl：字符串插值
来源：http://dali.jyoumei.cn/Article/details/gtpdkfdoig.html

"值: $a"
来源：http://dali.hywenlv.cn/Article/details/gtgxphvccw.html

[T44] Perl：条件
来源：http://dali.guannengcc.top/Article/details/gttneltswa.html

if ($a > 0) { print "正"; }
来源：http://dali.hfpthk.cn/Article/details/gthlyqyvim.html

[T45] Perl：数组遍历
来源：http://dali.cucudq.cn/Article/details/gtkkgvfmqn.html

for my $x (@arr) { print $x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjenxebrr.html

[T46] Perl：哈希操作
来源：http://dali.bjfxy.top/Article/details/gtuhzttxzp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.daria6918.cn/Article/details/gtsojuqufh.html

[T47] Perl：正则捕获
来源：http://dali.redwolf501.top/Article/details/gtqziwnjae.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.wangshuangyany.cn/Article/details/gtehdnerss.html

[T48] Perl：正则替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthgchylrk.html

$s =~ s/old/new/g;
来源：http://dali.hnxiangtu.top/Article/details/gtlwnnddhb.html

[T49] Perl：函数
来源：http://dali.pengpengdd.cyou/Article/details/gtqtmmdrjw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gtswavnhgz.html

[T50] Perl：逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gtegpivbjc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.aibaodan.cn/Article/details/gtvnllavuy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.snrcjt.cn/Article/details/gtitidhskh.html

[T51] Scala：Hello World
来源：http://dali.yuxming.cn/Article/details/gtmyrjzamw.html

println("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gtpowiajio.html

[T52] Scala：变量
来源：http://dali.wangshuangyany.cn/Article/details/gtrawnqlls.html

val a = 1;  var b = 2
来源：http://dali.smart0.xyz/Article/details/gtsiubpvau.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gtrmhwtwha.html

s"值: $b"
来源：http://dali.dianchejie.cn/Article/details/gtkoapphaf.html

[T54] Scala：集合映射
来源：http://dali.xylfe.cn/Article/details/gtkocmwjdw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hfpthk.cn/Article/details/gtcsupxbqm.html

[T55] Scala：集合过滤
来源：http://dali.birdmap.top/Article/details/gtkwrmhuvq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yuxming.cn/Article/details/gtzbjgeppz.html

[T56] Scala：样例类
来源：http://dali.fengsongda.top/Article/details/gtteezrlcq.html

case class User(name: String, age: Int)
来源：http://dali.yuanzhike.top/Article/details/gtyvskzdvr.html

[T57] Scala：模式匹配
来源：http://dali.ppjwa.cn/Article/details/gtqwrnjhvt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xylfe.cn/Article/details/gtptoiexsw.html

[T58] Scala：函数定义
来源：http://dali.ybcxt.top/Article/details/gtxqgcwszv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ybcxt.top/Article/details/gtujpmqthg.html

[T59] Scala：循环
来源：http://dali.xuanzx.com/Article/details/gtgktacgge.html

for (i <- 1 to 10) println(i)
来源：http://dali.gotoacloud.top/Article/details/gtnrsffpia.html

[T60] Scala：折叠
来源：http://dali.jinghuilouyu.cn/Article/details/gtpnomxnhc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.chenjidiqi.icu/Article/details/gtudntmdtp.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxqswbsj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtowvzyxso.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtoavcpmgg.html

[U01] Py：创建虚拟环境
来源：http://dali.yuanzhike.top/Article/details/gtejsgirwp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.andypj.xyz/Article/details/gtjdlapnql.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yangfankeji.com/Article/details/gtdvsnxepi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yueranfly.top/Article/details/gtmziexpuh.html

[U03] Py：加载 .env 配置
来源：http://dali.jqgufenzy.top/Article/details/gtlvnirzwb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.svipenyu.cn/Article/details/gttusvsykc.html

[U04] Py：变量调试打印
来源：http://dali.snrcjt.cn/Article/details/gtmiumbbpo.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hammf.cn/Article/details/gtzrviendz.html

[U05] Py：列表去重且保序
来源：http://dali.shanyushiyangtech.top/Article/details/gtgmzbiomo.html

list(dict.fromkeys(arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gtrhuxxrpn.html

[U06] Py：合并两个字典
来源：http://dali.hnxiangtu.top/Article/details/gtjvgkqdzt.html

{**a, **b}
来源：http://dali.jiagoushi.top/Article/details/gtlheahyus.html

[U07] Py：反转字典键值
来源：http://dali.cucudq.cn/Article/details/gtexxelrpt.html

{v: k for k, v in d.items()}
来源：http://dali.zdqjudy.top/Article/details/gtzpwgrsjt.html

[U08] Py：展平二维列表
来源：http://dali.gotoacloud.top/Article/details/gtqbohfnui.html

[y for x in nested for y in x]
来源：http://dali.ppjwa.cn/Article/details/gtmfusjeuv.html

[U09] Py：字典取最大值的键
来源：http://dali.gotoacloud.top/Article/details/gtlmvnrugy.html

max(d, key=d.get)
来源：http://dali.fzhhl.top/Article/details/gtqzwexvdi.html

[U10] Py：按值排序字典
来源：http://dali.shanyushiyangtech.top/Article/details/gtmfzflurh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmucegctd.html

[U11] Py：生成器表达式
来源：http://dali.cheryme.top/Article/details/gthozzbvtw.html

(x * 2 for x in arr)
来源：http://dali.yueranfly.top/Article/details/gtmqkwmjwx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yueranfly.top/Article/details/gtrgpnovbv.html

Counter(arr).most_common(3)
来源：http://dali.nanxinkj.top/Article/details/gtcbtvojno.html


<!-- 参考信息 -->