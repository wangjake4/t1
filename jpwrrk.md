代发 wailian999

head -c 16 /dev/urandom | base64
来源：http://dali.zhixingplan.top/Article/details/gtsvncnphl.html

[R70] 时间戳与互转
来源：http://dali.mhx1999.top/Article/details/gtbhowhbha.html

date +%s;  date -d @1700000000
来源：http://dali.guannengcc.top/Article/details/gtgzexfztc.html

[R71] 日期格式化
来源：http://dali.ydzc1.top/Article/details/gthplfhlkf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenlongwang.top/Article/details/gtuiemzslb.html

[R72] 等待端口就绪
来源：http://dali.yuanzhike.top/Article/details/gtwklxlrrw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.iojbl.cn/Article/details/gtgshbfhfa.html

[R73] 分割大日志
来源：http://dali.hnxiangtu.top/Article/details/gtwugjjlhw.html

split -l 1000 big.log part_
来源：http://dali.fengsongda.top/Article/details/gtchmyrsih.html

[R74] 批量重命名
来源：http://dali.dianchejie.cn/Article/details/gtpvgzzjjf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hywenlv.cn/Article/details/gtaujtssnn.html

[R75] 导出环境变量
来源：http://dali.hammf.cn/Article/details/gtqbjfzfpz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.c1oappe.top/Article/details/gtbapwpaty.html

[R76] 使用临时文件
来源：http://dali.c1oappe.top/Article/details/gtkaukuzkj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.9152youxi.cn/Article/details/gttnmjpcbb.html

[R77] 读取用户输入
来源：http://dali.sweek.top/Article/details/gtpttzrrxe.html

read -rp "请输入: " ans
来源：http://dali.yanxiufei.cn/Article/details/gtznhdkwdo.html

[R78] 交互式菜单
来源：http://dali.chenzaomai.com/Article/details/gtbouaxjtm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.birdmap.top/Article/details/gtwuhxzrsa.html

[R79] 解析命令行选项
来源：http://dali.wangshuangyany.cn/Article/details/gtclpypwij.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yonumen.top/Article/details/gtgjwiesfb.html

[R80] 查看脚本执行耗时
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwmkjntvm.html

time ./run.sh
来源：http://dali.zhengqikj.top/Article/details/gtfzmerzew.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtpzcxlucd.html

S. C / C++ 专题
来源：http://dali.ivvv.top/Article/details/gtxqomjxzy.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtjlaqppqj.html

[S01] C：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtcxfapxxk.html

#include <stdio.h>
来源：http://dali.hywenlv.cn/Article/details/gtoqicpfsv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xuetiantiany.cn/Article/details/gtlpcnodql.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gtkgaatchn.html

int a = 10; printf("%d\n", a);
来源：http://dali.yuxming.cn/Article/details/gtxkyggkqv.html

[S03] C：读入整数
来源：http://dali.yueranfly.top/Article/details/gtxegcqqfa.html

int x; scanf("%d", &x);
来源：http://dali.jqgfzy.top/Article/details/gtvjjolygh.html

[S04] C：字符串复制
来源：http://dali.dashuyun.cn/Article/details/gtbimbveuy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hywenlv.cn/Article/details/gtjzwrpyck.html

[S05] C：字符串长度
来源：http://dali.ydzc1.top/Article/details/gtxkjfjulm.html

strlen(s)
来源：http://dali.wangdashe.top/Article/details/gtisntgdgk.html

[S06] C：字符串比较
来源：http://dali.jianghu66.top/Article/details/gtqwehzenp.html

strcmp(a, b) == 0
来源：http://dali.hnqzz.top/Article/details/gtyvdnuuln.html

[S07] C：数组遍历求和
来源：http://dali.bjfxy.top/Article/details/gtkdsdzymy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yj20258.top/Article/details/gteajqusim.html

[S08] C：动态内存分配与释放
来源：http://dali.tian-w.cn/Article/details/gtixllqvul.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tianlin.xyz/Article/details/gtjxppzyqx.html

[S09] C：结构体定义与初始化
来源：http://dali.guowangkeji.top/Article/details/gtsuznuyap.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ivvv.top/Article/details/gtuzeyxpfe.html

[S10] C：指针与解引用
来源：http://dali.wangshuangyany.cn/Article/details/gtrmavtkoy.html

int *p = &a;  *p = 5;
来源：http://dali.jinqigufen.top/Article/details/gtwurofajf.html

[S11] C：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gtkhoqjeix.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.guannengcc.top/Article/details/gtcrnynbgl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.pengpengdd.cyou/Article/details/gtkzuauuni.html

fclose(f);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtszkspcar.html

[S12] C：写文件
来源：http://dali.xinyue.icu/Article/details/gtfgjodcgp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hfpthk.cn/Article/details/gtbzbdupcw.html

[S13] C：宏定义
来源：http://dali.havefunace.top/Article/details/gthrronmse.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zycfv.cn/Article/details/gtajrhnxnp.html

[S14] C：枚举
来源：http://dali.sweek.top/Article/details/gtxulalxxs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xziqi.cn/Article/details/gtiwmmwqvx.html

[S15] C：类型转换
来源：http://dali.c1oappe.top/Article/details/gtlkfstoek.html

(double) a / b
来源：http://dali.c1oappe.top/Article/details/gtcgwndbhd.html

[S16] C：位操作置位
来源：http://dali.jqgfzy.top/Article/details/gtqvjepede.html

x |= (1 << 3);
来源：http://dali.aibaodan.cn/Article/details/gtnuzoyyji.html

[S17] C：安全拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gtpwxyvlcf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlkkdolre.html

[S18] C：命令行参数
来源：http://dali.yueranfly.top/Article/details/gtyxanmszw.html

int main(int argc, char **argv)
来源：http://dali.yj20258888.top/Article/details/gtrukgenjw.html

[S19] C：快速排序
来源：http://dali.gaohongyu789.top/Article/details/gtbxppxplv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.bjfxy.top/Article/details/gtmkzpksfh.html

[S20] C：二分查找
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvvojftd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jqgufenzy.top/Article/details/gtlnrvwyii.html

[S21] C：字符类别判断
来源：http://dali.meibo888.top/Article/details/gttaxibusl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinqigfzy.top/Article/details/gtwazgcdnw.html

[S22] C：字符串转数字
来源：http://dali.cashguo.top/Article/details/gtdyxzcxkh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenzaomai.com/Article/details/gtcaybtixr.html

[S23] C：随机数
来源：http://dali.wangshuangyany.cn/Article/details/gttupxfqdq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.nanxinkj.top/Article/details/gtgiupqtow.html

[S24] C：获取本地时间
来源：http://dali.yuanzhike.top/Article/details/gtegmwgynf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.mhx1999.top/Article/details/gtnmfwncar.html

[S25] C：内存拷贝
来源：http://dali.hfpthk.cn/Article/details/gtkvqilxuv.html

memcpy(dst, src, n);
来源：http://dali.ybcxt.top/Article/details/gtkgjatczn.html

[S26] C：内存清零
来源：http://dali.gotoacloud.top/Article/details/gtxcgxbnyb.html

memset(a, 0, sizeof a);
来源：http://dali.haohaochexian.top/Article/details/gtspbumvuq.html

[S27] C：定义常量
来源：http://dali.ydzc1.top/Article/details/gtdxtcfwms.html

const double PI = 3.14159;
来源：http://dali.iojbl.cn/Article/details/gtxpcuxkmn.html

[S28] C：静态变量
来源：http://dali.jianghu66.top/Article/details/gtodiyfnxh.html

static int counter = 0;
来源：http://dali.yanxiufei.cn/Article/details/gtxpszfbrl.html

[S29] C：变参函数
来源：http://dali.zhengqikj.top/Article/details/gtzzicureh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zycfv.cn/Article/details/gtlyvyhlfo.html

[S30] C：头文件保护
来源：http://dali.hnxiangtu.top/Article/details/gtwnlqgpcm.html

#ifndef X_H
来源：http://dali.yangfankeji.com/Article/details/gtivygehvl.html

#define X_H
来源：http://dali.jinqigufen.top/Article/details/gtvuoljpnd.html

#endif
来源：http://dali.sweek.top/Article/details/gtklrupwbg.html

[S31] C++：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtwxypnkft.html

#include <iostream>
来源：http://dali.dashuyun.cn/Article/details/gtvfzyucep.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.aizwys.cn/Article/details/gtykydblpk.html

[S32] C++：字符串
来源：http://dali.dianchejie.cn/Article/details/gtspzqpoto.html

std::string s = "hi";  s += "!";
来源：http://dali.redwolf501.top/Article/details/gtdxkdmnfv.html

[S33] C++：vector 增删
来源：http://dali.chenjidiqi.icu/Article/details/gtbloxnhhv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.meibo888.top/Article/details/gtlxnlaefi.html

[S34] C++：遍历 vector
来源：http://dali.hfpthk.cn/Article/details/gtlzprjuir.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.fengsongda.top/Article/details/gtjglukkrd.html

[S35] C++：map
来源：http://dali.hammf.cn/Article/details/gtykwulswc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtiqqfreka.html

[S36] C++：unordered_map
来源：http://dali.jinqigfzy.top/Article/details/gtfnbawocu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gtqoypwsya.html

[S37] C++：set
来源：http://dali.316326.xyz/Article/details/gtxjypxfor.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hfpthk.cn/Article/details/gtwiqdytqt.html

[S38] C++：排序
来源：http://dali.yj202588.top/Article/details/gtlbkesuua.html

std::sort(v.begin(), v.end());
来源：http://dali.hywenlv.cn/Article/details/gtommyaaci.html

[S39] C++：自定义比较器排序
来源：http://dali.jqgfzy.top/Article/details/gtengcmhkn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj202588.top/Article/details/gtjlmazltq.html

[S40] C++：查找元素
来源：http://dali.ppjwa.cn/Article/details/gtcxpkapli.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtuuuhemcr.html

[S41] C++：类与构造函数
来源：http://dali.pengpengdd.cyou/Article/details/gtzsvellhr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenlongwang.top/Article/details/gtfqtvfuma.html

[S42] C++：继承与虚函数
来源：http://dali.bjfxy.top/Article/details/gttolitiye.html

class B : public Base { public: void f() override {} };
来源：http://dali.yvedp.cn/Article/details/gtvfiaclao.html

[S43] C++：智能指针
来源：http://dali.jqgufenzy.top/Article/details/gtirtgzybw.html

auto p = std::make_unique<int>(5);
来源：http://dali.316326.xyz/Article/details/gtqkyckonp.html

[S44] C++：引用传参
来源：http://dali.aizwys.cn/Article/details/gtjgcdadar.html

void inc(int &x) { ++x; }
来源：http://dali.ehwqpu.com/Article/details/gtzoguaxob.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gtoqiixlzw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.dianchejie.cn/Article/details/gtgnjlxupj.html

[S46] C++：函数模板
来源：http://dali.fzhhl.top/Article/details/gtkdoatlao.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yuanzhike.top/Article/details/gtqxnylean.html

[S47] C++：结构化绑定遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtndznozcc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hnqzz.top/Article/details/gtsdjkhmxf.html

[S48] C++：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gtucgszbxv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yvedp.cn/Article/details/gtaoebwbwx.html

while (std::getline(in, line)) { }
来源：http://dali.ydzc1.top/Article/details/gtjqudfarh.html

[S49] C++：写文件
来源：http://dali.kuanghao11.cn/Article/details/gtulwqnouc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zycfv.cn/Article/details/gtfxxclorx.html

[S50] C++：格式化数字
来源：http://dali.shuidangran.top/Article/details/gtlvsjjivz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtdwuofpyg.html

[S51] C++：显式类型转换
来源：http://dali.jianghu66.top/Article/details/gtmwipoqrd.html

static_cast<double>(a) / b
来源：http://dali.hammf.cn/Article/details/gtnbhzluss.html

[S52] C++：const 与 noexcept
来源：http://dali.jyoumei.cn/Article/details/gtkbbnabzd.html

int size() const noexcept { return n_; }
来源：http://dali.jlsjyb.cn/Article/details/gtnnelpbyq.html

[S53] C++：移动语义
来源：http://dali.gotoacloud.top/Article/details/gtzyshtree.html

std::vector<int> w = std::move(v);
来源：http://dali.yuanzhike.top/Article/details/gtsivhrfld.html

[S54] C++：异常处理
来源：http://dali.cashguo.top/Article/details/gtnvtahvag.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hnqzz.top/Article/details/gtxkbybkby.html

[S55] C++：结构化绑定
来源：http://dali.nanxuanxn.top/Article/details/gtvlyerbve.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.daria6918.cn/Article/details/gtcktsbnud.html

[S56] C++：optional
来源：http://dali.bjfxy.top/Article/details/gtujrcapcm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.bjfxy.top/Article/details/gtxiwiijsf.html

[S57] C++：编译期常量
来源：http://dali.chenjidiqi.icu/Article/details/gtmoosbehu.html

constexpr int N = 10;
来源：http://dali.hfpthk.cn/Article/details/gtffodfeyg.html

[S58] C++：命名空间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbetbiwyq.html

namespace ns { int f() { return 1; } }
来源：http://dali.pengpengdd.cyou/Article/details/gtktthdkkt.html

[S59] C++：静态断言
来源：http://dali.ehwqpu.com/Article/details/gtqlwkrwtu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hfpthk.cn/Article/details/gtbuyvechj.html

[S60] C++：遍历并删除元素
来源：http://dali.sysykeji.top/Article/details/gtjcythsmh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenzaomai.com/Article/details/gtyvaxppje.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtlijuenqn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.fzhhl.top/Article/details/gtbjmbakmm.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtzoypvotl.html

[T01] Kotlin：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtbjqtlojl.html

println("Hello")
来源：http://dali.yvedp.cn/Article/details/gtouhsymzx.html

[T02] Kotlin：变量
来源：http://dali.nanxuanxn.top/Article/details/gtlgedgtjp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.fengsongda.top/Article/details/gteiqiteqc.html

[T03] Kotlin：字符串模板
来源：http://dali.hfpthk.cn/Article/details/gtuayokwgu.html

"值: $b"
来源：http://dali.jiagoushi.top/Article/details/gtfzcgojsu.html

[T04] Kotlin：空安全
来源：http://dali.birdmap.top/Article/details/gtrxrpdrmi.html

val n: String? = null;  n?.length
来源：http://dali.hnxiangtu.top/Article/details/gtyoohfatz.html

[T05] Kotlin：when 表达式
来源：http://dali.birdmap.top/Article/details/gtxeeuldrv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj20258888.top/Article/details/gtfffgouqz.html

[T06] Kotlin：集合映射
来源：http://dali.shangyingyoupin.top/Article/details/gtduokezux.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenlongwang.top/Article/details/gtbtymuinh.html

[T07] Kotlin：集合过滤
来源：http://dali.guannengcc.top/Article/details/gtukdopjnm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.bjfxy.top/Article/details/gtkfrddwtk.html

[T08] Kotlin：数据类
来源：http://dali.ivvv.top/Article/details/gtndxekhgc.html

data class User(val name: String, val age: Int)
来源：http://dali.cqqwz.cn/Article/details/gtlcthedwc.html

[T09] Kotlin：扩展函数
来源：http://dali.pengpengdd.cyou/Article/details/gtgoufitss.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gtocngwcge.html

[T10] Kotlin：默认参数
来源：http://dali.zycfv.cn/Article/details/gtvgxojpfi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmxonfnp.html

[T11] Kotlin：协程
来源：http://dali.jqgfzy.top/Article/details/gtdougcfzg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sufxvd.cn/Article/details/gtvmsneirg.html

[T12] Kotlin：解构声明
来源：http://dali.feifeiyinyue.top/Article/details/gtbjpievme.html

val (a, b) = Pair(1, 2)
来源：http://dali.jlsjyb.cn/Article/details/gtlctnjwkx.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gtvzmxyksk.html

val m = mapOf("a" to 1)
来源：http://dali.ivvv.top/Article/details/gtrxehzmwn.html

[T14] Kotlin：循环
来源：http://dali.daria6918.cn/Article/details/gthbmfehoy.html

for (i in 1..10) println(i)
来源：http://dali.yuanzhike.top/Article/details/gtyyiirxia.html

[T15] Kotlin：接口
来源：http://dali.nwbrower.top/Article/details/gtuisoduxq.html

interface Shape { fun area(): Double }
来源：http://dali.yuxming.cn/Article/details/gtgjmkumtj.html

[T16] Swift：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtdjirxdgs.html

print("Hello")
来源：http://dali.yangfankeji.com/Article/details/gtjmfzzhtw.html

[T17] Swift：变量与常量
来源：http://dali.ybcxt.top/Article/details/gtuptnluok.html

var a = 1;  let b = 2
来源：http://dali.yuanzhike.top/Article/details/gtduariics.html

[T18] Swift：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdstrunxv.html

"值: \(b)"
来源：http://dali.gogol.net.cn/Article/details/gtlawqatds.html

[T19] Swift：可选绑定
来源：http://dali.yuxming.cn/Article/details/gtcyzflbzw.html

if let n = opt { print(n) }
来源：http://dali.shzxlz.cn/Article/details/gtkrstgyac.html

[T20] Swift：数组操作
来源：http://dali.fengsongda.top/Article/details/gtzqrcigof.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ivvv.top/Article/details/gtxffzvqhz.html

[T21] Swift：遍历
来源：http://dali.jqgfzy.top/Article/details/gtfsfrxdqh.html

for x in a { print(x) }
来源：http://dali.shangyingyoupin.top/Article/details/gtnabmtvvz.html

[T22] Swift：字典
来源：http://dali.316326.xyz/Article/details/gtssjtcbtl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xuanzx.com/Article/details/gtdjerdjao.html

[T23] Swift：函数
来源：http://dali.ivvv.top/Article/details/gtdqasyzzy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdwiwqsja.html

[T24] Swift：闭包
来源：http://dali.meibo888.top/Article/details/gtprunrsdj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.andypj.xyz/Article/details/gtlyqusrxi.html

[T25] Swift：结构体
来源：http://dali.ydzc1.top/Article/details/gtnropbjlp.html

struct P { var x: Int }
来源：http://dali.vqdsnc.cn/Article/details/gtwtafntqv.html

[T26] Swift：类与重写
来源：http://dali.zhongyouzk.top/Article/details/gtbpgktsam.html

class A: Base { override func f() {} }
来源：http://dali.zhengqikj.top/Article/details/gtbywliswy.html

[T27] Swift：错误处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtvikyzuet.html

do { try f() } catch { print(error) }
来源：http://dali.yvedp.cn/Article/details/gtftrqfzfd.html

[T28] Swift：枚举
来源：http://dali.andypj.xyz/Article/details/gtlwnjpxah.html

enum Color { case red, green }
来源：http://dali.dianchejie.cn/Article/details/gtvfxjykze.html

[T29] Swift：guard 提前返回
来源：http://dali.zhengqikj.top/Article/details/gtamdhbecz.html

guard let x = opt else { return }
来源：http://dali.cqqwz.cn/Article/details/gtymvxwvqq.html

[T30] Swift：协议
来源：http://dali.yonumen.top/Article/details/gtfassxdgf.html

protocol Shape { func area() -> Double }
来源：http://dali.zhiwuduotai.top/Article/details/gtevgruepg.html

[T31] Lua：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtfwfxfcqo.html

print("Hello")
来源：http://dali.9152youxi.cn/Article/details/gthznqmffm.html

[T32] Lua：局部变量
来源：http://dali.ybcxt.top/Article/details/gtufxdnhyr.html

local a = 1
来源：http://dali.shzxlz.cn/Article/details/gtixadadtd.html

[T33] Lua：表（数组）
来源：http://dali.sxryk.cn/Article/details/gtfhzisfxf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yj20258.top/Article/details/gtkrpudclw.html

[T34] Lua：遍历表
来源：http://dali.pycfn.com/Article/details/gtdsmoogew.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hfpthk.cn/Article/details/gtjnaxkzqe.html

[T35] Lua：字典表
来源：http://dali.xuanzx.com/Article/details/gtbjdsrdng.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yueranfly.top/Article/details/gtdyfmyxzg.html

[T36] Lua：函数
来源：http://dali.zycfv.cn/Article/details/gtohivhxpk.html

function add(a, b) return a + b end
来源：http://dali.zhiwuduotai.top/Article/details/gtaodpltpb.html

[T37] Lua：字符串拼接
来源：http://dali.shzxlz.cn/Article/details/gtuswcueux.html

"a" .. "b"
来源：http://dali.hysaishi.cn/Article/details/gtofgckvlo.html

[T38] Lua：条件
来源：http://dali.chenjidiqi.icu/Article/details/gthyrfewug.html

if x > 0 then print("正") end
来源：http://dali.xinyue.icu/Article/details/gtpceycauu.html

[T39] Lua：模式匹配
来源：http://dali.jlsjyb.cn/Article/details/gtjolzzykz.html

string.find(s, "%d+")
来源：http://dali.zhongyouzk.top/Article/details/gtigoaptzv.html

[T40] Lua：元表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxnnjyhkc.html

setmetatable({}, { __index = base })
来源：http://dali.cucudq.cn/Article/details/gtmtnnudkr.html

[T41] Perl：Hello World
来源：http://dali.cashguo.top/Article/details/gtxqgkwjcd.html

print "Hello\n";
来源：http://dali.smart0.xyz/Article/details/gtksrgsvsx.html

[T42] Perl：变量类型
来源：http://dali.jqgfzy.top/Article/details/gtclbibqkt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtiymdqfxi.html

[T43] Perl：字符串插值
来源：http://dali.cucudq.cn/Article/details/gtlfbvaftv.html

"值: $a"
来源：http://dali.vqdsnc.cn/Article/details/gtcemndqvb.html

[T44] Perl：条件
来源：http://dali.c1oappe.top/Article/details/gtqooyckay.html

if ($a > 0) { print "正"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtozfrodxt.html

[T45] Perl：数组遍历
来源：http://dali.jyoumei.cn/Article/details/gtostidswe.html

for my $x (@arr) { print $x; }
来源：http://dali.cheryme.top/Article/details/gtnuluqmbc.html

[T46] Perl：哈希操作
来源：http://dali.yongpay.top/Article/details/gtqosftcth.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ivvv.top/Article/details/gtfjvqlhkb.html

[T47] Perl：正则捕获
来源：http://dali.iojbl.cn/Article/details/gtyyhkbcft.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.svipenyu.cn/Article/details/gtxnozulfh.html

[T48] Perl：正则替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtptdwbuyf.html

$s =~ s/old/new/g;
来源：http://dali.quarkkingdee.top/Article/details/gtkrrutkmu.html

[T49] Perl：函数
来源：http://dali.cheryme.top/Article/details/gtnquqwbcm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gtaafavtdf.html

[T50] Perl：逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gtypicksob.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tianlin.xyz/Article/details/gthqgludob.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtecwrumpm.html

[T51] Scala：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtbptmtkwi.html

println("Hello")
来源：http://dali.daria6918.cn/Article/details/gtwmvqgfzh.html

[T52] Scala：变量
来源：http://dali.cheryme.top/Article/details/gtqtbtcjcq.html

val a = 1;  var b = 2
来源：http://dali.sweek.top/Article/details/gtvzcpzgbb.html

[T53] Scala：字符串插值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyicfoknz.html

s"值: $b"
来源：http://dali.hammf.cn/Article/details/gtptlgskoz.html

[T54] Scala：集合映射
来源：http://dali.gaohongyu789.top/Article/details/gteuyiqavy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.wangdashe.top/Article/details/gtbgsyttwg.html

[T55] Scala：集合过滤
来源：http://dali.yj202588.top/Article/details/gtifzsfjxw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.nwbrower.top/Article/details/gtfshyzwhd.html

[T56] Scala：样例类
来源：http://dali.zycfv.cn/Article/details/gtuycqugim.html

case class User(name: String, age: Int)
来源：http://dali.xziqi.cn/Article/details/gtkvdvfpyr.html

[T57] Scala：模式匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtdonbydjq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.vqdsnc.cn/Article/details/gtjulnljyo.html

[T58] Scala：函数定义
来源：http://dali.zycfv.cn/Article/details/gtmxfhynhx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.316326.xyz/Article/details/gtthgvejta.html

[T59] Scala：循环
来源：http://dali.yuanzhike.top/Article/details/gtyzvcqtil.html

for (i <- 1 to 10) println(i)
来源：http://dali.wangdashe.top/Article/details/gtgodicsbq.html

[T60] Scala：折叠
来源：http://dali.pycfn.com/Article/details/gtlzaupnto.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhongyouzk.top/Article/details/gtgtmqcatc.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gteemriwkb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xylfe.cn/Article/details/gtmqukpbtc.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtvqcjtcjh.html

[U01] Py：创建虚拟环境
来源：http://dali.zdqjudy.top/Article/details/gtcktlscit.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yueranfly.top/Article/details/gtpisvblnq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hywenlv.cn/Article/details/gtrqltbuwq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtlecupxcf.html

[U03] Py：加载 .env 配置
来源：http://dali.ybcxt.top/Article/details/gtdajyrvmw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jlsjyb.cn/Article/details/gtdlitlmiz.html

[U04] Py：变量调试打印
来源：http://dali.zhiwuduotai.top/Article/details/gtdayxzxnl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.birdmap.top/Article/details/gtjgdacmgn.html

[U05] Py：列表去重且保序
来源：http://dali.jlsjyb.cn/Article/details/gtdrjzcssq.html

list(dict.fromkeys(arr))
来源：http://dali.xuanzx.com/Article/details/gtgwoacxrj.html

[U06] Py：合并两个字典
来源：http://dali.nwbrower.top/Article/details/gtvitsvdzz.html

{**a, **b}
来源：http://dali.wangdashe.top/Article/details/gtbheaygmh.html

[U07] Py：反转字典键值
来源：http://dali.yj20258.top/Article/details/gtdlvodtne.html

{v: k for k, v in d.items()}
来源：http://dali.snrcjt.cn/Article/details/gttzgzvlhc.html

[U08] Py：展平二维列表
来源：http://dali.jinqigufen.top/Article/details/gtpsywvfzr.html

[y for x in nested for y in x]
来源：http://dali.iojbl.cn/Article/details/gtkfymtfuk.html

[U09] Py：字典取最大值的键
来源：http://dali.xziqi.cn/Article/details/gtcxcxfpum.html

max(d, key=d.get)
来源：http://dali.yueranfly.top/Article/details/gtqdgcmsri.html

[U10] Py：按值排序字典
来源：http://dali.tanke756.top/Article/details/gtqlzflora.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yangfankeji.com/Article/details/gtoetsihpu.html


<!-- 参考信息 -->