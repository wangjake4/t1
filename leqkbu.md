代发 wailian999

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ydzc1.top/Article/details/gtjqwvpqxu.html

[R72] 等待端口就绪
来源：http://dali.ivvv.top/Article/details/gtirkdkewi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrmqdcjck.html

[R73] 分割大日志
来源：http://dali.hfpthk.cn/Article/details/gtqtbwsmhh.html

split -l 1000 big.log part_
来源：http://dali.zhixingplan.top/Article/details/gtacxpddcw.html

[R74] 批量重命名
来源：http://dali.jqgufenzy.top/Article/details/gtcqwfhtyu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tianlin.xyz/Article/details/gtrzgyfjri.html

[R75] 导出环境变量
来源：http://dali.havefunace.top/Article/details/gtzdmcaozn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtczrsfsuq.html

[R76] 使用临时文件
来源：http://dali.nanxinkj.top/Article/details/gtsygaubkk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhengqikj.top/Article/details/gteegsrvum.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gthjgvgxuj.html

read -rp "请输入: " ans
来源：http://dali.feifeiyinyue.top/Article/details/gtwbfeqddo.html

[R78] 交互式菜单
来源：http://dali.yuxming.cn/Article/details/gtgepgevoc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqpqnywer.html

[R79] 解析命令行选项
来源：http://dali.sxryk.cn/Article/details/gtufxcjsxy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hnqzz.top/Article/details/gtgbderczg.html

[R80] 查看脚本执行耗时
来源：http://dali.cucudq.cn/Article/details/gtctkopmdq.html

time ./run.sh
来源：http://dali.sxryk.cn/Article/details/gthbeksfij.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtllybdzgi.html

S. C / C++ 专题
来源：http://dali.dianchejie.cn/Article/details/gtdmfsihnv.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtzwiyrgfh.html

[S01] C：Hello World
来源：http://dali.yj202588.top/Article/details/gtdfdwloek.html

#include <stdio.h>
来源：http://dali.shanyushiyangkeji.top/Article/details/gtryjogzas.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xinyue.icu/Article/details/gtmbtatizm.html

[S02] C：变量与格式化输出
来源：http://dali.chenzaomai.com/Article/details/gtxhpwmngt.html

int a = 10; printf("%d\n", a);
来源：http://dali.vqdsnc.cn/Article/details/gtmebxrbqx.html

[S03] C：读入整数
来源：http://dali.yangfankeji.com/Article/details/gtqeoydurd.html

int x; scanf("%d", &x);
来源：http://dali.cheryme.top/Article/details/gtnfyquzee.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gtxvqzqvku.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xinyue.icu/Article/details/gtfahvhayh.html

[S05] C：字符串长度
来源：http://dali.xylfe.cn/Article/details/gthvpaifik.html

strlen(s)
来源：http://dali.gotoacloud.top/Article/details/gtdpwoidmu.html

[S06] C：字符串比较
来源：http://dali.hnqzz.top/Article/details/gtyswjdigr.html

strcmp(a, b) == 0
来源：http://dali.hysaishi.cn/Article/details/gtfuenxnim.html

[S07] C：数组遍历求和
来源：http://dali.sxryk.cn/Article/details/gtluwrtxkg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yanxiufei.cn/Article/details/gtzyyioylc.html

[S08] C：动态内存分配与释放
来源：http://dali.shanyushiyangtech.top/Article/details/gtwwhtpams.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtosoyggjh.html

[S09] C：结构体定义与初始化
来源：http://dali.hammf.cn/Article/details/gtyantqeao.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.pengpengdd.cyou/Article/details/gtfxyjhflm.html

[S10] C：指针与解引用
来源：http://dali.ydzc1.top/Article/details/gtczygdjvj.html

int *p = &a;  *p = 5;
来源：http://dali.wangdashe.top/Article/details/gtcqntajka.html

[S11] C：逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gtcxszdppf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jqgufenzy.top/Article/details/gtaynzkbjx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cqqwz.cn/Article/details/gtabgpinyr.html

fclose(f);
来源：http://dali.quarkkingdee.top/Article/details/gtuxdmnshd.html

[S12] C：写文件
来源：http://dali.tian-w.cn/Article/details/gtpefwlbpr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sxryk.cn/Article/details/gtdrejptof.html

[S13] C：宏定义
来源：http://dali.jinghuilouyu.cn/Article/details/gtozorbuzd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhoulong.xyz/Article/details/gtvknjcoft.html

[S14] C：枚举
来源：http://dali.birdmap.top/Article/details/gtnlhuxlaq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hammf.cn/Article/details/gtngwliyow.html

[S15] C：类型转换
来源：http://dali.316326.xyz/Article/details/gtpmxsstau.html

(double) a / b
来源：http://dali.0kj1m.cn/Article/details/gtcrwrpwjb.html

[S16] C：位操作置位
来源：http://dali.hfpthk.cn/Article/details/gtpdhloaqx.html

x |= (1 << 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtabhzmapv.html

[S17] C：安全拼接字符串
来源：http://dali.redwolf501.top/Article/details/gttxqvyvty.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrkkhytqr.html

[S18] C：命令行参数
来源：http://dali.tanke756.top/Article/details/gtdpnevosy.html

int main(int argc, char **argv)
来源：http://dali.ydzc1.top/Article/details/gtbmewhjwd.html

[S19] C：快速排序
来源：http://dali.gaohongyu789.top/Article/details/gtnpyjojti.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hnqzz.top/Article/details/gtxsczcbrw.html

[S20] C：二分查找
来源：http://dali.zhixingplan.top/Article/details/gtspdmoyqb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.aizwys.cn/Article/details/gtdtyhryhd.html

[S21] C：字符类别判断
来源：http://dali.sufxvd.cn/Article/details/gtricyhqrk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj20258888.top/Article/details/gtqicfhcbu.html

[S22] C：字符串转数字
来源：http://dali.cheryme.top/Article/details/gtptcwbaqv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cqqwz.cn/Article/details/gtiwhfrqoj.html

[S23] C：随机数
来源：http://dali.jinqigfzy.top/Article/details/gtdrwyfrox.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hywenlv.cn/Article/details/gtfafdvvub.html

[S24] C：获取本地时间
来源：http://dali.chenjidiqi.icu/Article/details/gtwqiqcaho.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.fengsongda.top/Article/details/gtpmpgokis.html

[S25] C：内存拷贝
来源：http://dali.haohaochexian.top/Article/details/gtwxdshdhf.html

memcpy(dst, src, n);
来源：http://dali.svipenyu.cn/Article/details/gtxwecvzcc.html

[S26] C：内存清零
来源：http://dali.jyoumei.cn/Article/details/gtxivgcrdt.html

memset(a, 0, sizeof a);
来源：http://dali.gogol.net.cn/Article/details/gtoifqfvgz.html

[S27] C：定义常量
来源：http://dali.hammf.cn/Article/details/gttknbutcq.html

const double PI = 3.14159;
来源：http://dali.guannengcc.top/Article/details/gtkiytklor.html

[S28] C：静态变量
来源：http://dali.ppjwa.cn/Article/details/gtrciylexx.html

static int counter = 0;
来源：http://dali.iojbl.cn/Article/details/gtssgsrjgt.html

[S29] C：变参函数
来源：http://dali.pycfn.com/Article/details/gtssnkydrf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.bjfxy.top/Article/details/gtkfzuwkxp.html

[S30] C：头文件保护
来源：http://dali.redwolf501.top/Article/details/gtnnlteyny.html

#ifndef X_H
来源：http://dali.wangshuangyany.cn/Article/details/gtdjrjypbe.html

#define X_H
来源：http://dali.fengsongda.top/Article/details/gtvqtiqaou.html

#endif
来源：http://dali.ivvv.top/Article/details/gtgzxofehr.html

[S31] C++：Hello World
来源：http://dali.9152youxi.cn/Article/details/gthxhxxoqw.html

#include <iostream>
来源：http://dali.hysaishi.cn/Article/details/gtysregemq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtwclergpl.html

[S32] C++：字符串
来源：http://dali.redwolf501.top/Article/details/gtgactwhwb.html

std::string s = "hi";  s += "!";
来源：http://dali.cheryme.top/Article/details/gtixyshpih.html

[S33] C++：vector 增删
来源：http://dali.yueranfly.top/Article/details/gtgipvnhtf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.guannengcc.top/Article/details/gtpcsdgrsf.html

[S34] C++：遍历 vector
来源：http://dali.daxiang520.top/Article/details/gtipnlyjfw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.0kj1m.cn/Article/details/gtcliqdnuz.html

[S35] C++：map
来源：http://dali.kuanghao11.cn/Article/details/gtpemmsdrh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gtjjlcwfsq.html

[S36] C++：unordered_map
来源：http://dali.chenzaomai.com/Article/details/gtukdqdfqb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pycfn.com/Article/details/gtfjzdvape.html

[S37] C++：set
来源：http://dali.daxiang520.top/Article/details/gtfvhleusl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nanxuanxn.top/Article/details/gtkgveohju.html

[S38] C++：排序
来源：http://dali.yuxming.cn/Article/details/gteuhdqxym.html

std::sort(v.begin(), v.end());
来源：http://dali.hysaishi.cn/Article/details/gthugfvrta.html

[S39] C++：自定义比较器排序
来源：http://dali.sxryk.cn/Article/details/gtqzighkog.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.c1oappe.top/Article/details/gtqruknccj.html

[S40] C++：查找元素
来源：http://dali.jqgfzy.top/Article/details/gtnuyuhqnb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.havefunace.top/Article/details/gtgozcdfhs.html

[S41] C++：类与构造函数
来源：http://dali.haohaochexian.top/Article/details/gtiznooclq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdngtefu.html

[S42] C++：继承与虚函数
来源：http://dali.chenjidiqi.icu/Article/details/gtsunepqnq.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhoulong.xyz/Article/details/gtvnjcevgh.html

[S43] C++：智能指针
来源：http://dali.cashguo.top/Article/details/gtivndtjcm.html

auto p = std::make_unique<int>(5);
来源：http://dali.haohaochexian.top/Article/details/gtyxnhbxgm.html

[S44] C++：引用传参
来源：http://dali.cucudq.cn/Article/details/gtxphaxmqq.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gtoztwaxvb.html

[S45] C++：lambda
来源：http://dali.jinqigufen.top/Article/details/gteuizdfyp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sufxvd.cn/Article/details/gtnuwuwbgy.html

[S46] C++：函数模板
来源：http://dali.svipenyu.cn/Article/details/gtrfganpdo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gzhubu.top/Article/details/gtijmdfrym.html

[S47] C++：结构化绑定遍历
来源：http://dali.bjfxy.top/Article/details/gtvoyembst.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj20258.top/Article/details/gtgtdxnuil.html

[S48] C++：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtxsdwtdtl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.haohaochexian.top/Article/details/gtlawrkqfy.html

while (std::getline(in, line)) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlpqdbgtn.html

[S49] C++：写文件
来源：http://dali.xziqi.cn/Article/details/gtsuthvquk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhengqikj.top/Article/details/gtcmkxbuml.html

[S50] C++：格式化数字
来源：http://dali.yuanzhike.top/Article/details/gthrkkjfhb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gtvkuhflwx.html

[S51] C++：显式类型转换
来源：http://dali.jlsjyb.cn/Article/details/gtcmlmatpb.html

static_cast<double>(a) / b
来源：http://dali.gotoacloud.top/Article/details/gttvhlbxus.html

[S52] C++：const 与 noexcept
来源：http://dali.jqgfzy.top/Article/details/gtuaiqqyav.html

int size() const noexcept { return n_; }
来源：http://dali.yangfankeji.com/Article/details/gtmoqokyrh.html

[S53] C++：移动语义
来源：http://dali.xinyue.icu/Article/details/gtakflieko.html

std::vector<int> w = std::move(v);
来源：http://dali.cdnleiting.top/Article/details/gtnaurcqkg.html

[S54] C++：异常处理
来源：http://dali.ivvv.top/Article/details/gtvclwujxj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sysykeji.top/Article/details/gtzhygivcm.html

[S55] C++：结构化绑定
来源：http://dali.cashguo.top/Article/details/gtxncnzsxp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hnxiangtu.top/Article/details/gtkisugecf.html

[S56] C++：optional
来源：http://dali.daxiang520.top/Article/details/gtnfrtrgza.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sysykeji.top/Article/details/gtuvahgroc.html

[S57] C++：编译期常量
来源：http://dali.ehwqpu.com/Article/details/gtvozyawic.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gtveojuwmv.html

[S58] C++：命名空间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuwgueeat.html

namespace ns { int f() { return 1; } }
来源：http://dali.jiagoushi.top/Article/details/gtifllwxne.html

[S59] C++：静态断言
来源：http://dali.aibaodan.cn/Article/details/gtqwibnyjr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tian-w.cn/Article/details/gtuwulfygr.html

[S60] C++：遍历并删除元素
来源：http://dali.cucudq.cn/Article/details/gtxthacciy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.guannengcc.top/Article/details/gtpskhuhpt.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtplgrozxg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.iojbl.cn/Article/details/gtjpwvpgnz.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtgqegeqtq.html

[T01] Kotlin：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtxubcsngp.html

println("Hello")
来源：http://dali.xylfe.cn/Article/details/gtglfcsngg.html

[T02] Kotlin：变量
来源：http://dali.chenzaomai.com/Article/details/gtewzkrkeh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.wangdashe.top/Article/details/gtrynignuz.html

[T03] Kotlin：字符串模板
来源：http://dali.nwbrower.top/Article/details/gtmuoqkzho.html

"值: $b"
来源：http://dali.xuanzx.com/Article/details/gttljzjsfx.html

[T04] Kotlin：空安全
来源：http://dali.tian-w.cn/Article/details/gtrlbkheen.html

val n: String? = null;  n?.length
来源：http://dali.sweek.top/Article/details/gtnlidzeua.html

[T05] Kotlin：when 表达式
来源：http://dali.sysykeji.top/Article/details/gtbsmlugbv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.kuanghao11.cn/Article/details/gteumygtky.html

[T06] Kotlin：集合映射
来源：http://dali.yangfankeji.com/Article/details/gtusktpelz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ydzc1.top/Article/details/gtqitwbbuo.html

[T07] Kotlin：集合过滤
来源：http://dali.yongpay.top/Article/details/gtcdglrrcz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj20258.top/Article/details/gtlbdsdprh.html

[T08] Kotlin：数据类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfevirhid.html

data class User(val name: String, val age: Int)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgvheuhqg.html

[T09] Kotlin：扩展函数
来源：http://dali.jiagoushi.top/Article/details/gtgltsylhg.html

fun String.exclaim() = this + "!"
来源：http://dali.ywan-chungtsiang.top/Article/details/gttcjdhyrs.html

[T10] Kotlin：默认参数
来源：http://dali.pengpengdd.cyou/Article/details/gttqcclpnc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ehwqpu.com/Article/details/gttmqohylt.html

[T11] Kotlin：协程
来源：http://dali.zhoulong.xyz/Article/details/gtbcqpcbme.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sweek.top/Article/details/gtcpcvvjhy.html

[T12] Kotlin：解构声明
来源：http://dali.sufxvd.cn/Article/details/gtjcerwqna.html

val (a, b) = Pair(1, 2)
来源：http://dali.hammf.cn/Article/details/gtffjnerhp.html

[T13] Kotlin：只读 Map
来源：http://dali.chenjidiqi.icu/Article/details/gtmomxaoqx.html

val m = mapOf("a" to 1)
来源：http://dali.ybcxt.top/Article/details/gtfcrtsjie.html

[T14] Kotlin：循环
来源：http://dali.yj20258.top/Article/details/gteluniuiq.html

for (i in 1..10) println(i)
来源：http://dali.aibaodan.cn/Article/details/gtmzspsjld.html

[T15] Kotlin：接口
来源：http://dali.xziqi.cn/Article/details/gthqavzmod.html

interface Shape { fun area(): Double }
来源：http://dali.guowangkeji.top/Article/details/gtutatqkbn.html

[T16] Swift：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtilivjgib.html

print("Hello")
来源：http://dali.yonumen.top/Article/details/gtvqsnabxx.html

[T17] Swift：变量与常量
来源：http://dali.zhoulong.xyz/Article/details/gtgyugtyqr.html

var a = 1;  let b = 2
来源：http://dali.pengpengdd.cyou/Article/details/gtqvixffju.html

[T18] Swift：字符串插值
来源：http://dali.jianghu66.top/Article/details/gtduguhfoo.html

"值: \(b)"
来源：http://dali.pycfn.com/Article/details/gtpcoxxucb.html

[T19] Swift：可选绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsuardzst.html

if let n = opt { print(n) }
来源：http://dali.shangyingyoupin.top/Article/details/gtgdmitfhk.html

[T20] Swift：数组操作
来源：http://dali.jinqigfzy.top/Article/details/gthxnufjxo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gogol.net.cn/Article/details/gtmofiskpr.html

[T21] Swift：遍历
来源：http://dali.fengsongda.top/Article/details/gtrbkuzvsc.html

for x in a { print(x) }
来源：http://dali.0kj1m.cn/Article/details/gttaiiztzx.html

[T22] Swift：字典
来源：http://dali.guowangkeji.top/Article/details/gtasfwwyge.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.aizwys.cn/Article/details/gtklvsuiyu.html

[T23] Swift：函数
来源：http://dali.andypj.xyz/Article/details/gtzzoofqsp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cdnleiting.top/Article/details/gtmxscjuoj.html

[T24] Swift：闭包
来源：http://dali.hywenlv.cn/Article/details/gtpyozkbpp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.316326.xyz/Article/details/gtldqmjfac.html

[T25] Swift：结构体
来源：http://dali.sweek.top/Article/details/gtsuhqzyak.html

struct P { var x: Int }
来源：http://dali.yangfankeji.com/Article/details/gtokresryh.html

[T26] Swift：类与重写
来源：http://dali.jinqigfzy.top/Article/details/gtvqhnscei.html

class A: Base { override func f() {} }
来源：http://dali.daria6918.cn/Article/details/gtpzozhegu.html

[T27] Swift：错误处理
来源：http://dali.sweek.top/Article/details/gtxmyuhjkg.html

do { try f() } catch { print(error) }
来源：http://dali.gogol.net.cn/Article/details/gtzlmlpllz.html

[T28] Swift：枚举
来源：http://dali.shanyushiyangtech.top/Article/details/gtnyfccfyg.html

enum Color { case red, green }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzcuuypdv.html

[T29] Swift：guard 提前返回
来源：http://dali.andypj.xyz/Article/details/gtyzwscaxa.html

guard let x = opt else { return }
来源：http://dali.wangdashe.top/Article/details/gtiorewmxn.html

[T30] Swift：协议
来源：http://dali.yonumen.top/Article/details/gtlhrryjzk.html

protocol Shape { func area() -> Double }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmgysyqfy.html

[T31] Lua：Hello World
来源：http://dali.gzhubu.top/Article/details/gtlwvgmedl.html

print("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gtibsvkqkz.html

[T32] Lua：局部变量
来源：http://dali.sufxvd.cn/Article/details/gtnkoxfjmj.html

local a = 1
来源：http://dali.jlsjyb.cn/Article/details/gtvtylwpoi.html

[T33] Lua：表（数组）
来源：http://dali.jqgufenzy.top/Article/details/gtcpwoluay.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zdqjudy.top/Article/details/gtzlkwmixb.html

[T34] Lua：遍历表
来源：http://dali.9152youxi.cn/Article/details/gtssqhegvv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinqigufen.top/Article/details/gtnumhdawo.html

[T35] Lua：字典表
来源：http://dali.quarkkingdee.top/Article/details/gtfwobbjjg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xinyue.icu/Article/details/gtvhbuvmxz.html

[T36] Lua：函数
来源：http://dali.zycfv.cn/Article/details/gtyewfjnce.html

function add(a, b) return a + b end
来源：http://dali.yangfankeji.com/Article/details/gtkrtmwgnj.html

[T37] Lua：字符串拼接
来源：http://dali.zhoulong.xyz/Article/details/gtjlohucqb.html

"a" .. "b"
来源：http://dali.sufxvd.cn/Article/details/gtqbuhysob.html

[T38] Lua：条件
来源：http://dali.cucudq.cn/Article/details/gtxshjkvph.html

if x > 0 then print("正") end
来源：http://dali.guannengcc.top/Article/details/gtaokovkgv.html

[T39] Lua：模式匹配
来源：http://dali.shzxlz.cn/Article/details/gtsogilgxd.html

string.find(s, "%d+")
来源：http://dali.zycfv.cn/Article/details/gtmlislxbx.html

[T40] Lua：元表
来源：http://dali.fzhhl.top/Article/details/gtizoixvlw.html

setmetatable({}, { __index = base })
来源：http://dali.snrcjt.cn/Article/details/gtlqwgwwhp.html

[T41] Perl：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtxcemqwvu.html

print "Hello\n";
来源：http://dali.havefunace.top/Article/details/gtkogiopcd.html

[T42] Perl：变量类型
来源：http://dali.yongpay.top/Article/details/gtjxwkecuo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.c1oappe.top/Article/details/gttvhfwycj.html

[T43] Perl：字符串插值
来源：http://dali.yongpay.top/Article/details/gtvchcrzfg.html

"值: $a"
来源：http://dali.gotoacloud.top/Article/details/gtozecpzoh.html

[T44] Perl：条件
来源：http://dali.cheryme.top/Article/details/gtzevgfytg.html

if ($a > 0) { print "正"; }
来源：http://dali.shzxlz.cn/Article/details/gtcoiuflio.html

[T45] Perl：数组遍历
来源：http://dali.birdmap.top/Article/details/gtdfoivpby.html

for my $x (@arr) { print $x; }
来源：http://dali.yueranfly.top/Article/details/gtclxyhaio.html

[T46] Perl：哈希操作
来源：http://dali.redwolf501.top/Article/details/gtokkbgqnt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yangfankeji.com/Article/details/gtrakzeuod.html

[T47] Perl：正则捕获
来源：http://dali.chenjidiqi.icu/Article/details/gtbtavghfw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shangyingyoupin.top/Article/details/gtelnkrafd.html

[T48] Perl：正则替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwflfvkyt.html

$s =~ s/old/new/g;
来源：http://dali.cqqwz.cn/Article/details/gtchzeqebu.html

[T49] Perl：函数
来源：http://dali.zhengqikj.top/Article/details/gtnlzkswrd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.aibaodan.cn/Article/details/gtulygpxfn.html

[T50] Perl：逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gtwbjlbufp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cashguo.top/Article/details/gtzohonrtg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.dashuyun.cn/Article/details/gtudozdold.html

[T51] Scala：Hello World
来源：http://dali.yj202588.top/Article/details/gtedtdkqzi.html

println("Hello")
来源：http://dali.mhx1999.top/Article/details/gttwjyxjjd.html

[T52] Scala：变量
来源：http://dali.quarkkingdee.top/Article/details/gtdmrkeiiw.html

val a = 1;  var b = 2
来源：http://dali.sufxvd.cn/Article/details/gtnlmhecof.html

[T53] Scala：字符串插值
来源：http://dali.zhixingplan.top/Article/details/gtnbytyhme.html

s"值: $b"
来源：http://dali.yanxiufei.cn/Article/details/gtwmttyftv.html

[T54] Scala：集合映射
来源：http://dali.ivvv.top/Article/details/gtqlekkmgn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvewukzz.html

[T55] Scala：集合过滤
来源：http://dali.chenzaomai.com/Article/details/gtvquqcoae.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hysaishi.cn/Article/details/gtveehgirm.html

[T56] Scala：样例类
来源：http://dali.zycfv.cn/Article/details/gtrxbayabx.html

case class User(name: String, age: Int)
来源：http://dali.yj202588.top/Article/details/gtvjjmnlzt.html

[T57] Scala：模式匹配
来源：http://dali.tian-w.cn/Article/details/gtfpxqxduv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhoulong.xyz/Article/details/gtxxubeozn.html

[T58] Scala：函数定义
来源：http://dali.c1oappe.top/Article/details/gtwkjiavvb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jlsjyb.cn/Article/details/gtdmvbstmk.html

[T59] Scala：循环
来源：http://dali.daxiang520.top/Article/details/gtewpuwjqp.html

for (i <- 1 to 10) println(i)
来源：http://dali.tianlin.xyz/Article/details/gtytoeukhd.html

[T60] Scala：折叠
来源：http://dali.yuanzhike.top/Article/details/gtqoelphxn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.wangshuangyany.cn/Article/details/gtjeeonlwu.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtadtostjw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenlongwang.top/Article/details/gtrnqmjycx.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtwbcyauav.html

[U01] Py：创建虚拟环境
来源：http://dali.wangshuangyany.cn/Article/details/gtgshmgyys.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.dashuyun.cn/Article/details/gtqjzxizhp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yongpay.top/Article/details/gtxmhplllu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ehwqpu.com/Article/details/gtwwsmzrqs.html

[U03] Py：加载 .env 配置
来源：http://dali.shanyushiyangtech.top/Article/details/gtpnyscfxu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.dianchejie.cn/Article/details/gtzwuiwulh.html

[U04] Py：变量调试打印
来源：http://dali.xziqi.cn/Article/details/gtruzjaqnt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinqigufen.top/Article/details/gtaaidwjxo.html

[U05] Py：列表去重且保序
来源：http://dali.hnqzz.top/Article/details/gttpakjveb.html

list(dict.fromkeys(arr))
来源：http://dali.cqqwz.cn/Article/details/gtzyzvnjgs.html

[U06] Py：合并两个字典
来源：http://dali.ivvv.top/Article/details/gthfhtljic.html

{**a, **b}
来源：http://dali.xuanzx.com/Article/details/gtxijmehpi.html

[U07] Py：反转字典键值
来源：http://dali.c1oappe.top/Article/details/gthkrspaki.html

{v: k for k, v in d.items()}
来源：http://dali.guowangkeji.top/Article/details/gtstrkkhrx.html

[U08] Py：展平二维列表
来源：http://dali.yuxming.cn/Article/details/gtseqeavmb.html

[y for x in nested for y in x]
来源：http://dali.jlsjyb.cn/Article/details/gtomqsjvbp.html

[U09] Py：字典取最大值的键
来源：http://dali.jinyuanbaomall.cn/Article/details/gttxrdkdma.html

max(d, key=d.get)
来源：http://dali.cashguo.top/Article/details/gthdhzcltt.html

[U10] Py：按值排序字典
来源：http://dali.yonumen.top/Article/details/gttyromvwh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xinyue.icu/Article/details/gtaqfsoxxo.html

[U11] Py：生成器表达式
来源：http://dali.yj202588.top/Article/details/gtkxixyora.html

(x * 2 for x in arr)
来源：http://dali.gaohongyu789.top/Article/details/gtascegmrs.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.0kj1m.cn/Article/details/gtinfziomk.html

Counter(arr).most_common(3)
来源：http://dali.mhx1999.top/Article/details/gtocekryrh.html


<!-- 参考信息 -->