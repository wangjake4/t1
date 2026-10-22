代发 wailian999

export PATH="$HOME/bin:$PATH"
来源：http://dali.hongshengwenyu.top/Article/details/gtyozccyzt.html

[R76] 使用临时文件
来源：http://dali.tianlin.xyz/Article/details/gtsoxdfgnd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhixingplan.top/Article/details/gtddkahlye.html

[R77] 读取用户输入
来源：http://dali.cdnleiting.top/Article/details/gthxlaiqsi.html

read -rp "请输入: " ans
来源：http://dali.zycfv.cn/Article/details/gtdwyagbcg.html

[R78] 交互式菜单
来源：http://dali.xinyue.icu/Article/details/gtxwhvuvsg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gzhubu.top/Article/details/gtuckgmkqq.html

[R79] 解析命令行选项
来源：http://dali.nwbrower.top/Article/details/gtdvjdshho.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hnqzz.top/Article/details/gtsibpjmwf.html

[R80] 查看脚本执行耗时
来源：http://dali.gotoacloud.top/Article/details/gtgfmgovam.html

time ./run.sh
来源：http://dali.aibaodan.cn/Article/details/gtmiisfcno.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtsgyiaufb.html

S. C / C++ 专题
来源：http://dali.zhengqikj.top/Article/details/gtpohbdzwy.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtijbqnguj.html

[S01] C：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtdngzzwrv.html

#include <stdio.h>
来源：http://dali.jinqigfzy.top/Article/details/gtwdlwumap.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.guannengcc.top/Article/details/gtxgruqbjn.html

[S02] C：变量与格式化输出
来源：http://dali.pycfn.com/Article/details/gtfllzymvb.html

int a = 10; printf("%d\n", a);
来源：http://dali.xinyue.icu/Article/details/gtwidtewhs.html

[S03] C：读入整数
来源：http://dali.shuidangran.top/Article/details/gtfudnfywc.html

int x; scanf("%d", &x);
来源：http://dali.yj202588.top/Article/details/gtqruqgghc.html

[S04] C：字符串复制
来源：http://dali.chenjidiqi.icu/Article/details/gtzmxxhkgv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj20258888.top/Article/details/gtepvterwh.html

[S05] C：字符串长度
来源：http://dali.jinqigufen.top/Article/details/gtyieqkqgc.html

strlen(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqocsdtu.html

[S06] C：字符串比较
来源：http://dali.yuanzhike.top/Article/details/gtdusxldis.html

strcmp(a, b) == 0
来源：http://dali.guowangkeji.top/Article/details/gtlmymxlhm.html

[S07] C：数组遍历求和
来源：http://dali.birdmap.top/Article/details/gtqtvyfszs.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nwbrower.top/Article/details/gtbonrnjbr.html

[S08] C：动态内存分配与释放
来源：http://dali.shzxlz.cn/Article/details/gtiivmanhn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbzsqvhd.html

[S09] C：结构体定义与初始化
来源：http://dali.yueranfly.top/Article/details/gtnwwauqtc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.aibaodan.cn/Article/details/gtrrwdupxp.html

[S10] C：指针与解引用
来源：http://dali.vqdsnc.cn/Article/details/gtvrudbiey.html

int *p = &a;  *p = 5;
来源：http://dali.pengpengdd.cyou/Article/details/gtykpyutvy.html

[S11] C：逐行读文件
来源：http://dali.yj20258.top/Article/details/gtnjvypoml.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shanyushiyangtech.top/Article/details/gtytijrriy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.wangshuangyany.cn/Article/details/gtkdxkcqwr.html

fclose(f);
来源：http://dali.fzhhl.top/Article/details/gtgkncirbn.html

[S12] C：写文件
来源：http://dali.xuetiantiany.cn/Article/details/gtdqbaasmd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.vqdsnc.cn/Article/details/gtgtfqztfs.html

[S13] C：宏定义
来源：http://dali.hysaishi.cn/Article/details/gtrmasoxsz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenlongwang.top/Article/details/gtakhsubrp.html

[S14] C：枚举
来源：http://dali.yuanzhike.top/Article/details/gteshztict.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.feifeiyinyue.top/Article/details/gttcouglvt.html

[S15] C：类型转换
来源：http://dali.chenzaomai.com/Article/details/gtopasasiv.html

(double) a / b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuvbztpso.html

[S16] C：位操作置位
来源：http://dali.birdmap.top/Article/details/gtpmeoqkil.html

x |= (1 << 3);
来源：http://dali.cdnleiting.top/Article/details/gtsaklyaxu.html

[S17] C：安全拼接字符串
来源：http://dali.xuanzx.com/Article/details/gthysxmbph.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cashguo.top/Article/details/gtkcpaxepx.html

[S18] C：命令行参数
来源：http://dali.jyoumei.cn/Article/details/gtmjcodsfb.html

int main(int argc, char **argv)
来源：http://dali.bjfxy.top/Article/details/gtohclfcoi.html

[S19] C：快速排序
来源：http://dali.zhengqikj.top/Article/details/gtcukuddnu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.nanxinkj.top/Article/details/gtpxyarzhn.html

[S20] C：二分查找
来源：http://dali.dashuyun.cn/Article/details/gtnhvsxbwh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.redwolf501.top/Article/details/gtzijuxrjc.html

[S21] C：字符类别判断
来源：http://dali.yonumen.top/Article/details/gtrgovdhsz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shuidangran.top/Article/details/gtcmpvuceu.html

[S22] C：字符串转数字
来源：http://dali.xuanzx.com/Article/details/gtcerwmgkn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhongyouzk.top/Article/details/gtcijzklzv.html

[S23] C：随机数
来源：http://dali.chenzaomai.com/Article/details/gttowugjfj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.fengsongda.top/Article/details/gtnalqnthp.html

[S24] C：获取本地时间
来源：http://dali.zycfv.cn/Article/details/gtmoovvgnp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj20258888.top/Article/details/gtoaemhzso.html

[S25] C：内存拷贝
来源：http://dali.zycfv.cn/Article/details/gtgaexvhei.html

memcpy(dst, src, n);
来源：http://dali.yuanzhike.top/Article/details/gtajlpyccx.html

[S26] C：内存清零
来源：http://dali.jinqigufen.top/Article/details/gtmrzftelg.html

memset(a, 0, sizeof a);
来源：http://dali.0kj1m.cn/Article/details/gtqldpkfnd.html

[S27] C：定义常量
来源：http://dali.ivvv.top/Article/details/gtyytdttqo.html

const double PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gtorewghjz.html

[S28] C：静态变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsgmtdvkv.html

static int counter = 0;
来源：http://dali.sxryk.cn/Article/details/gtvacveenx.html

[S29] C：变参函数
来源：http://dali.yj20258.top/Article/details/gtcwurwjyj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.fengsongda.top/Article/details/gtmlgctqlm.html

[S30] C：头文件保护
来源：http://dali.zhoulong.xyz/Article/details/gtwzutfjwj.html

#ifndef X_H
来源：http://dali.ehwqpu.com/Article/details/gtlfbdhizs.html

#define X_H
来源：http://dali.vqdsnc.cn/Article/details/gtssrdzhfz.html

#endif
来源：http://dali.0kj1m.cn/Article/details/gtyncatrtt.html

[S31] C++：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtvlyllyhp.html

#include <iostream>
来源：http://dali.hfpthk.cn/Article/details/gtfqnndbaf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yj202588.top/Article/details/gtpeufxsuo.html

[S32] C++：字符串
来源：http://dali.dashuyun.cn/Article/details/gtkcsfyjcj.html

std::string s = "hi";  s += "!";
来源：http://dali.yonumen.top/Article/details/gtuxmkopqw.html

[S33] C++：vector 增删
来源：http://dali.wangdashe.top/Article/details/gtnmspjdjh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinqigufen.top/Article/details/gtlasbjvqa.html

[S34] C++：遍历 vector
来源：http://dali.0kj1m.cn/Article/details/gtidghjeci.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yanxiufei.cn/Article/details/gtcfjxfoom.html

[S35] C++：map
来源：http://dali.bjfxy.top/Article/details/gthhtgnevh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gtzrucfifl.html

[S36] C++：unordered_map
来源：http://dali.hammf.cn/Article/details/gtxntahpho.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gtqpqfkvul.html

[S37] C++：set
来源：http://dali.xuanzx.com/Article/details/gtpclcjodn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinqigufen.top/Article/details/gtaszdsvxh.html

[S38] C++：排序
来源：http://dali.zhixingplan.top/Article/details/gtlpqvbykc.html

std::sort(v.begin(), v.end());
来源：http://dali.ehwqpu.com/Article/details/gtbfjidslu.html

[S39] C++：自定义比较器排序
来源：http://dali.guowangkeji.top/Article/details/gtksbdvfsu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.birdmap.top/Article/details/gtcgqykpjm.html

[S40] C++：查找元素
来源：http://dali.hywenlv.cn/Article/details/gtqhfvdihm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhengqikj.top/Article/details/gtetikecdc.html

[S41] C++：类与构造函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtotskgdjv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zdqjudy.top/Article/details/gtxseefazi.html

[S42] C++：继承与虚函数
来源：http://dali.ehwqpu.com/Article/details/gtbbeaffif.html

class B : public Base { public: void f() override {} };
来源：http://dali.0kj1m.cn/Article/details/gttcxvljyz.html

[S43] C++：智能指针
来源：http://dali.redwolf501.top/Article/details/gtnszvhfam.html

auto p = std::make_unique<int>(5);
来源：http://dali.mhx1999.top/Article/details/gtwqtwbweg.html

[S44] C++：引用传参
来源：http://dali.xziqi.cn/Article/details/gteunzvozs.html

void inc(int &x) { ++x; }
来源：http://dali.pycfn.com/Article/details/gtdoaojnbk.html

[S45] C++：lambda
来源：http://dali.shzxlz.cn/Article/details/gtqraoemxt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.0kj1m.cn/Article/details/gtaspulqun.html

[S46] C++：函数模板
来源：http://dali.snrcjt.cn/Article/details/gtvtvbmrzd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuegfwskb.html

[S47] C++：结构化绑定遍历
来源：http://dali.9152youxi.cn/Article/details/gtmtgafhec.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.0kj1m.cn/Article/details/gtdaydngme.html

[S48] C++：逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gtgmabehmi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.daria6918.cn/Article/details/gtzenmnleb.html

while (std::getline(in, line)) { }
来源：http://dali.hammf.cn/Article/details/gtjxsbfbee.html

[S49] C++：写文件
来源：http://dali.nanxinkj.top/Article/details/gtkxxkqeoy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.smart0.xyz/Article/details/gttclzucde.html

[S50] C++：格式化数字
来源：http://dali.tian-w.cn/Article/details/gtouxcfmay.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtbndbzhoe.html

[S51] C++：显式类型转换
来源：http://dali.tianlin.xyz/Article/details/gtqzdmaehe.html

static_cast<double>(a) / b
来源：http://dali.jinghuilouyu.cn/Article/details/gtdixywinm.html

[S52] C++：const 与 noexcept
来源：http://dali.fengsongda.top/Article/details/gteyacxffa.html

int size() const noexcept { return n_; }
来源：http://dali.birdmap.top/Article/details/gtiszczvjt.html

[S53] C++：移动语义
来源：http://dali.iojbl.cn/Article/details/gttgcvvksc.html

std::vector<int> w = std::move(v);
来源：http://dali.c1oappe.top/Article/details/gtctjgrvhg.html

[S54] C++：异常处理
来源：http://dali.chenzaomai.com/Article/details/gtbumzlyco.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hammf.cn/Article/details/gtqaeolbdb.html

[S55] C++：结构化绑定
来源：http://dali.nanxuanxn.top/Article/details/gtvgsxbvul.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gaohongyu789.top/Article/details/gtguhsyhzn.html

[S56] C++：optional
来源：http://dali.nanxuanxn.top/Article/details/gtydaeqonx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.snrcjt.cn/Article/details/gtfztohkct.html

[S57] C++：编译期常量
来源：http://dali.nwbrower.top/Article/details/gtryqoslsx.html

constexpr int N = 10;
来源：http://dali.shuidangran.top/Article/details/gtmqlxfvwo.html

[S58] C++：命名空间
来源：http://dali.zhiwuduotai.top/Article/details/gtrvyflkpy.html

namespace ns { int f() { return 1; } }
来源：http://dali.hfpthk.cn/Article/details/gtgkvhivha.html

[S59] C++：静态断言
来源：http://dali.sufxvd.cn/Article/details/gthmxnejwd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.guannengcc.top/Article/details/gtwbuiglrl.html

[S60] C++：遍历并删除元素
来源：http://dali.yj20258888.top/Article/details/gtszmmdijv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zdqjudy.top/Article/details/gtyrurkmod.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtahhdtupt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.vqdsnc.cn/Article/details/gtbwlczmek.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtquckanwx.html

[T01] Kotlin：Hello World
来源：http://dali.zycfv.cn/Article/details/gthzyfwrdy.html

println("Hello")
来源：http://dali.jqgfzy.top/Article/details/gtjundvzbu.html

[T02] Kotlin：变量
来源：http://dali.sxryk.cn/Article/details/gtyoyhvdnz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shangyingyoupin.top/Article/details/gtyuzksuip.html

[T03] Kotlin：字符串模板
来源：http://dali.yueranfly.top/Article/details/gtntsmtkql.html

"值: $b"
来源：http://dali.vqdsnc.cn/Article/details/gtepgevemd.html

[T04] Kotlin：空安全
来源：http://dali.xuanzx.com/Article/details/gtamnlihff.html

val n: String? = null;  n?.length
来源：http://dali.sxryk.cn/Article/details/gtbouduaax.html

[T05] Kotlin：when 表达式
来源：http://dali.fzhhl.top/Article/details/gtohtcegao.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.dashuyun.cn/Article/details/gtuqjnmfzm.html

[T06] Kotlin：集合映射
来源：http://dali.wangshuangyany.cn/Article/details/gtiolgcwam.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.mhx1999.top/Article/details/gtzwlidlpw.html

[T07] Kotlin：集合过滤
来源：http://dali.xinyue.icu/Article/details/gtsydxtfoe.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cheryme.top/Article/details/gttxzokbtp.html

[T08] Kotlin：数据类
来源：http://dali.aizwys.cn/Article/details/gtbyyhzszz.html

data class User(val name: String, val age: Int)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyhzohism.html

[T09] Kotlin：扩展函数
来源：http://dali.zhongyouzk.top/Article/details/gtzwcqpxjm.html

fun String.exclaim() = this + "!"
来源：http://dali.hfpthk.cn/Article/details/gtsinyaiyj.html

[T10] Kotlin：默认参数
来源：http://dali.hongshengwenyu.top/Article/details/gtjgdjtncp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gaohongyu789.top/Article/details/gtkwnltirj.html

[T11] Kotlin：协程
来源：http://dali.ivvv.top/Article/details/gtvswudeuu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zdqjudy.top/Article/details/gtxbjyelky.html

[T12] Kotlin：解构声明
来源：http://dali.sysykeji.top/Article/details/gtbbrdnuoh.html

val (a, b) = Pair(1, 2)
来源：http://dali.xuanzx.com/Article/details/gtamadbfbf.html

[T13] Kotlin：只读 Map
来源：http://dali.xylfe.cn/Article/details/gtzpfbgmpg.html

val m = mapOf("a" to 1)
来源：http://dali.daxiang520.top/Article/details/gtmlgnecfa.html

[T14] Kotlin：循环
来源：http://dali.tian-w.cn/Article/details/gtcnzivyyc.html

for (i in 1..10) println(i)
来源：http://dali.yonumen.top/Article/details/gtfklimicd.html

[T15] Kotlin：接口
来源：http://dali.yueranfly.top/Article/details/gtfexfprtm.html

interface Shape { fun area(): Double }
来源：http://dali.dashuyun.cn/Article/details/gtgcmhawei.html

[T16] Swift：Hello World
来源：http://dali.daxiang520.top/Article/details/gtxetoyrzn.html

print("Hello")
来源：http://dali.birdmap.top/Article/details/gtdifctijp.html

[T17] Swift：变量与常量
来源：http://dali.hongshengwenyu.top/Article/details/gtzqgnfjhv.html

var a = 1;  let b = 2
来源：http://dali.zycfv.cn/Article/details/gthumbwwvl.html

[T18] Swift：字符串插值
来源：http://dali.svipenyu.cn/Article/details/gtbqloqctj.html

"值: \(b)"
来源：http://dali.dashuyun.cn/Article/details/gtwtyzrmtz.html

[T19] Swift：可选绑定
来源：http://dali.zhiwuduotai.top/Article/details/gtasjhanmi.html

if let n = opt { print(n) }
来源：http://dali.feifeiyinyue.top/Article/details/gtlcwsyggk.html

[T20] Swift：数组操作
来源：http://dali.ydzc1.top/Article/details/gtdhavjinp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqeyttxk.html

[T21] Swift：遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtxwiqpsyq.html

for x in a { print(x) }
来源：http://dali.cheryme.top/Article/details/gtusjatzhn.html

[T22] Swift：字典
来源：http://dali.bjfxy.top/Article/details/gtlfdbappz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbfeffut.html

[T23] Swift：函数
来源：http://dali.zhongyouzk.top/Article/details/gtwtdkfzdv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gogol.net.cn/Article/details/gtktymmyao.html

[T24] Swift：闭包
来源：http://dali.jqgufenzy.top/Article/details/gtkgsbcgfu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtvzlwfgvh.html

[T25] Swift：结构体
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvizrlpnx.html

struct P { var x: Int }
来源：http://dali.chenjidiqi.icu/Article/details/gtqpgtrvty.html

[T26] Swift：类与重写
来源：http://dali.shuidangran.top/Article/details/gtrfdcqmxq.html

class A: Base { override func f() {} }
来源：http://dali.svipenyu.cn/Article/details/gtzdikawzk.html

[T27] Swift：错误处理
来源：http://dali.hongshengwenyu.top/Article/details/gtwncgykwe.html

do { try f() } catch { print(error) }
来源：http://dali.zdqjudy.top/Article/details/gttaibcjaw.html

[T28] Swift：枚举
来源：http://dali.snrcjt.cn/Article/details/gtkrqfvrfd.html

enum Color { case red, green }
来源：http://dali.ivvv.top/Article/details/gtybxlbbpx.html

[T29] Swift：guard 提前返回
来源：http://dali.tianlin.xyz/Article/details/gtcqdkxxbq.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gthdqkbblg.html

[T30] Swift：协议
来源：http://dali.guowangkeji.top/Article/details/gtwcsezxun.html

protocol Shape { func area() -> Double }
来源：http://dali.aibaodan.cn/Article/details/gtwdoxasxp.html

[T31] Lua：Hello World
来源：http://dali.ybcxt.top/Article/details/gtmegxoidy.html

print("Hello")
来源：http://dali.nanxinkj.top/Article/details/gtyaouiika.html

[T32] Lua：局部变量
来源：http://dali.wangdashe.top/Article/details/gtiqszfrop.html

local a = 1
来源：http://dali.andypj.xyz/Article/details/gtlijhlxon.html

[T33] Lua：表（数组）
来源：http://dali.gotoacloud.top/Article/details/gtglbnlzrr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.quarkkingdee.top/Article/details/gttqrvlvpq.html

[T34] Lua：遍历表
来源：http://dali.jqgfzy.top/Article/details/gtxtsxqqvo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinqigufen.top/Article/details/gtcphgrtay.html

[T35] Lua：字典表
来源：http://dali.gzhubu.top/Article/details/gtqlvlmbgv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gzhubu.top/Article/details/gtpejftjco.html

[T36] Lua：函数
来源：http://dali.jqgufenzy.top/Article/details/gtnwoyjmct.html

function add(a, b) return a + b end
来源：http://dali.xziqi.cn/Article/details/gtxxdrjsaq.html

[T37] Lua：字符串拼接
来源：http://dali.nanxuanxn.top/Article/details/gtdcmljzzr.html

"a" .. "b"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtljyjosxi.html

[T38] Lua：条件
来源：http://dali.ehwqpu.com/Article/details/gtxuhkkkuz.html

if x > 0 then print("正") end
来源：http://dali.nanxuanxn.top/Article/details/gtkgnrcjau.html

[T39] Lua：模式匹配
来源：http://dali.jianghu66.top/Article/details/gtvsifhqdy.html

string.find(s, "%d+")
来源：http://dali.yj20258888.top/Article/details/gtazldmqwv.html

[T40] Lua：元表
来源：http://dali.snrcjt.cn/Article/details/gtnnqwahdc.html

setmetatable({}, { __index = base })
来源：http://dali.wangdashe.top/Article/details/gttkbfumkp.html

[T41] Perl：Hello World
来源：http://dali.smart0.xyz/Article/details/gtvexasfrj.html

print "Hello\n";
来源：http://dali.sysykeji.top/Article/details/gtoxlmqrte.html

[T42] Perl：变量类型
来源：http://dali.ehwqpu.com/Article/details/gtgyhngazs.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yanxiufei.cn/Article/details/gtkuqfenyy.html

[T43] Perl：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gtnkyacgzm.html

"值: $a"
来源：http://dali.quarkkingdee.top/Article/details/gtvfbfitpo.html

[T44] Perl：条件
来源：http://dali.hnxiangtu.top/Article/details/gtiwilnjbv.html

if ($a > 0) { print "正"; }
来源：http://dali.fzhhl.top/Article/details/gtzdoawste.html

[T45] Perl：数组遍历
来源：http://dali.yongpay.top/Article/details/gtqwzudeka.html

for my $x (@arr) { print $x; }
来源：http://dali.tianlin.xyz/Article/details/gtieyfjdde.html

[T46] Perl：哈希操作
来源：http://dali.feifeiyinyue.top/Article/details/gtcykwehkw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.daxiang520.top/Article/details/gtudbgoirv.html

[T47] Perl：正则捕获
来源：http://dali.tianlin.xyz/Article/details/gtuntglyck.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hnxiangtu.top/Article/details/gtmexnbova.html

[T48] Perl：正则替换
来源：http://dali.feifeiyinyue.top/Article/details/gtgiqegllo.html

$s =~ s/old/new/g;
来源：http://dali.jianghu66.top/Article/details/gtekkoekmo.html

[T49] Perl：函数
来源：http://dali.guannengcc.top/Article/details/gtfzwqbilp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gtxohybmkj.html

[T50] Perl：逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gtlgxjcewc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.iojbl.cn/Article/details/gtojyxsqik.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jqgufenzy.top/Article/details/gtzfiukqvp.html

[T51] Scala：Hello World
来源：http://dali.fengsongda.top/Article/details/gtplkjpbxz.html

println("Hello")
来源：http://dali.cdnleiting.top/Article/details/gtqhkkwift.html

[T52] Scala：变量
来源：http://dali.mhx1999.top/Article/details/gtllufbugu.html

val a = 1;  var b = 2
来源：http://dali.sufxvd.cn/Article/details/gtgfjbvvgh.html

[T53] Scala：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gtfwqkwblm.html

s"值: $b"
来源：http://dali.chenlongwang.top/Article/details/gtdmtavakr.html

[T54] Scala：集合映射
来源：http://dali.jlsjyb.cn/Article/details/gtssjkppjj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.havefunace.top/Article/details/gtcxlqnych.html

[T55] Scala：集合过滤
来源：http://dali.hnqzz.top/Article/details/gtdntdgfrd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hammf.cn/Article/details/gtxbfdzfro.html

[T56] Scala：样例类
来源：http://dali.316326.xyz/Article/details/gtshkhvxxx.html

case class User(name: String, age: Int)
来源：http://dali.yueranfly.top/Article/details/gtbxyvcqnm.html

[T57] Scala：模式匹配
来源：http://dali.svipenyu.cn/Article/details/gtgnonaigw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinqigufen.top/Article/details/gtclpknfte.html

[T58] Scala：函数定义
来源：http://dali.9152youxi.cn/Article/details/gtfmaoslod.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.svipenyu.cn/Article/details/gtiaggnvsg.html

[T59] Scala：循环
来源：http://dali.meibo888.top/Article/details/gtxudemkea.html

for (i <- 1 to 10) println(i)
来源：http://dali.yanxiufei.cn/Article/details/gttzlxqatz.html

[T60] Scala：折叠
来源：http://dali.daxiang520.top/Article/details/gtqcrpetdb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yongpay.top/Article/details/gtticabjza.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gthrwknpzx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtbgctcair.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtxwtplwrj.html

[U01] Py：创建虚拟环境
来源：http://dali.zdqjudy.top/Article/details/gtwxgyaomm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.9152youxi.cn/Article/details/gttsduludp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.c1oappe.top/Article/details/gtdteutikk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yanxiufei.cn/Article/details/gtzbfjfifh.html

[U03] Py：加载 .env 配置
来源：http://dali.chenlongwang.top/Article/details/gtroqanizn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xuanzx.com/Article/details/gtaredldgt.html

[U04] Py：变量调试打印
来源：http://dali.hongshengwenyu.top/Article/details/gtnamvqrns.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yuxming.cn/Article/details/gtaudqvlzc.html

[U05] Py：列表去重且保序
来源：http://dali.hongshengwenyu.top/Article/details/gtbpbncukr.html

list(dict.fromkeys(arr))
来源：http://dali.guannengcc.top/Article/details/gtyxmawdkj.html

[U06] Py：合并两个字典
来源：http://dali.yangfankeji.com/Article/details/gtzqrdjfyd.html

{**a, **b}
来源：http://dali.andypj.xyz/Article/details/gtjixcsajs.html

[U07] Py：反转字典键值
来源：http://dali.smart0.xyz/Article/details/gttkcsehae.html

{v: k for k, v in d.items()}
来源：http://dali.cucudq.cn/Article/details/gtqtstoxcx.html

[U08] Py：展平二维列表
来源：http://dali.meibo888.top/Article/details/gtifxlbotj.html

[y for x in nested for y in x]
来源：http://dali.hnqzz.top/Article/details/gtdrhupwjh.html

[U09] Py：字典取最大值的键
来源：http://dali.ppjwa.cn/Article/details/gtpujtvgeu.html

max(d, key=d.get)
来源：http://dali.guowangkeji.top/Article/details/gtaxzqgckl.html

[U10] Py：按值排序字典
来源：http://dali.xuetiantiany.cn/Article/details/gtikyhrtss.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jianghu66.top/Article/details/gttghjkowf.html

[U11] Py：生成器表达式
来源：http://dali.9152youxi.cn/Article/details/gthutnpufm.html

(x * 2 for x in arr)
来源：http://dali.zhixingplan.top/Article/details/gtfiarvpia.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.0kj1m.cn/Article/details/gtrutkueim.html

Counter(arr).most_common(3)
来源：http://dali.ybcxt.top/Article/details/gtyyvzzzxi.html

[U13] Py：固定长度队列
来源：http://dali.hongshengwenyu.top/Article/details/gtbvjhkqpx.html

deque(maxlen=10)
来源：http://dali.cdnleiting.top/Article/details/gtpuqvgayf.html

[U14] Py：分组收集到列表
来源：http://dali.hysaishi.cn/Article/details/gtishtpmfc.html

defaultdict(list)
来源：http://dali.hnqzz.top/Article/details/gtjyigcwgh.html

[U15] Py：高精度计时
来源：http://dali.ivvv.top/Article/details/gtivomuohw.html

t = time.perf_counter()
来源：http://dali.yj202588.top/Article/details/gtulwppegi.html

[U16] Py：命令行参数解析
来源：http://dali.smart0.xyz/Article/details/gtuppavxtw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhiwuduotai.top/Article/details/gtmzzykhvu.html


<!-- 参考信息 -->