代发 wailian999

split -l 1000 big.log part_
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtntwoamli.html

[R74] 批量重命名
来源：http://dali.316326.xyz/Article/details/gtypoiilzt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.vqdsnc.cn/Article/details/gtilsgufhc.html

[R75] 导出环境变量
来源：http://dali.yongpay.top/Article/details/gtsvwxjmox.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yuxming.cn/Article/details/gtwztzmuom.html

[R76] 使用临时文件
来源：http://dali.zhiwuduotai.top/Article/details/gtcjimkybt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gtmsfnhioq.html

[R77] 读取用户输入
来源：http://dali.wangshuangyany.cn/Article/details/gtowzwkdjx.html

read -rp "请输入: " ans
来源：http://dali.gzhubu.top/Article/details/gtktqvdnge.html

[R78] 交互式菜单
来源：http://dali.hywenlv.cn/Article/details/gthkvryrne.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.vqdsnc.cn/Article/details/gtbmaqfiid.html

[R79] 解析命令行选项
来源：http://dali.ybcxt.top/Article/details/gtszoqjass.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtzzoakypy.html

[R80] 查看脚本执行耗时
来源：http://dali.yj202588.top/Article/details/gtoiupyvuw.html

time ./run.sh
来源：http://dali.pycfn.com/Article/details/gtuamdrhbw.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gttmiyqzku.html

S. C / C++ 专题
来源：http://dali.jqgfzy.top/Article/details/gtngirjtsb.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtndfujkli.html

[S01] C：Hello World
来源：http://dali.xuanzx.com/Article/details/gtyvrgdcen.html

#include <stdio.h>
来源：http://dali.zhiwuduotai.top/Article/details/gtgbluzlow.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yongpay.top/Article/details/gtbgtbuiyw.html

[S02] C：变量与格式化输出
来源：http://dali.xinyue.icu/Article/details/gtisdhzvuo.html

int a = 10; printf("%d\n", a);
来源：http://dali.kuanghao11.cn/Article/details/gtsimwddde.html

[S03] C：读入整数
来源：http://dali.jianghu66.top/Article/details/gtgakavqtc.html

int x; scanf("%d", &x);
来源：http://dali.iojbl.cn/Article/details/gtcqkzgght.html

[S04] C：字符串复制
来源：http://dali.tianlin.xyz/Article/details/gtghnclfel.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hammf.cn/Article/details/gtletyitgt.html

[S05] C：字符串长度
来源：http://dali.zycfv.cn/Article/details/gtiyfqrgde.html

strlen(s)
来源：http://dali.sufxvd.cn/Article/details/gtgwzkurcb.html

[S06] C：字符串比较
来源：http://dali.jiagoushi.top/Article/details/gtcklevkjs.html

strcmp(a, b) == 0
来源：http://dali.jinghuilouyu.cn/Article/details/gtdvzylwzw.html

[S07] C：数组遍历求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsolntwgf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhongyouzk.top/Article/details/gtraluprgw.html

[S08] C：动态内存分配与释放
来源：http://dali.chenlongwang.top/Article/details/gtrptufckz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjndpaaqx.html

[S09] C：结构体定义与初始化
来源：http://dali.snrcjt.cn/Article/details/gtedffcwkz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ydzc1.top/Article/details/gtelgrbtoe.html

[S10] C：指针与解引用
来源：http://dali.yangfankeji.com/Article/details/gtssotsmbu.html

int *p = &a;  *p = 5;
来源：http://dali.xuanzx.com/Article/details/gtmdzqzdwx.html

[S11] C：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwrcrspky.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nanxuanxn.top/Article/details/gthhwozkst.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhixingplan.top/Article/details/gtiowofblp.html

fclose(f);
来源：http://dali.pycfn.com/Article/details/gtinxrdrry.html

[S12] C：写文件
来源：http://dali.zhengqikj.top/Article/details/gteqivpwbq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xuetiantiany.cn/Article/details/gtfphdqpip.html

[S13] C：宏定义
来源：http://dali.yanxiufei.cn/Article/details/gtfklcgxsu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.meibo888.top/Article/details/gtkbimbgje.html

[S14] C：枚举
来源：http://dali.gaohongyu789.top/Article/details/gtocilmjda.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhongyouzk.top/Article/details/gtwlylxbrd.html

[S15] C：类型转换
来源：http://dali.tian-w.cn/Article/details/gtywomrhpm.html

(double) a / b
来源：http://dali.chenlongwang.top/Article/details/gtghnypcer.html

[S16] C：位操作置位
来源：http://dali.snrcjt.cn/Article/details/gtnxtszfxl.html

x |= (1 << 3);
来源：http://dali.hongshengwenyu.top/Article/details/gthldkcbko.html

[S17] C：安全拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtjukqriby.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nwbrower.top/Article/details/gtjfczaoqg.html

[S18] C：命令行参数
来源：http://dali.havefunace.top/Article/details/gtompzjhld.html

int main(int argc, char **argv)
来源：http://dali.chenzaomai.com/Article/details/gtwdxopuob.html

[S19] C：快速排序
来源：http://dali.yanxiufei.cn/Article/details/gthtbadqvq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.svipenyu.cn/Article/details/gtjruafsfy.html

[S20] C：二分查找
来源：http://dali.jinqigufen.top/Article/details/gtoukavafs.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gtppktiwkp.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gtlrkjkaln.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfbhvsjsv.html

[S22] C：字符串转数字
来源：http://dali.snrcjt.cn/Article/details/gtlcqbsmil.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zdqjudy.top/Article/details/gtujtpumin.html

[S23] C：随机数
来源：http://dali.svipenyu.cn/Article/details/gtebxfcnwf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.quarkkingdee.top/Article/details/gtwvosomum.html

[S24] C：获取本地时间
来源：http://dali.vqdsnc.cn/Article/details/gtzlwvbton.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jianghu66.top/Article/details/gtdcndarjg.html

[S25] C：内存拷贝
来源：http://dali.chenlongwang.top/Article/details/gtujgeghxc.html

memcpy(dst, src, n);
来源：http://dali.xuanzx.com/Article/details/gtqxhoujfu.html

[S26] C：内存清零
来源：http://dali.nanxinkj.top/Article/details/gtqplcqfif.html

memset(a, 0, sizeof a);
来源：http://dali.xylfe.cn/Article/details/gtuarzbfne.html

[S27] C：定义常量
来源：http://dali.chenjidiqi.icu/Article/details/gtwddzgwen.html

const double PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gtywiyjbhr.html

[S28] C：静态变量
来源：http://dali.nwbrower.top/Article/details/gtyurrbfiy.html

static int counter = 0;
来源：http://dali.jianghu66.top/Article/details/gtfylrscmk.html

[S29] C：变参函数
来源：http://dali.daria6918.cn/Article/details/gtgkevwjod.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nwbrower.top/Article/details/gtnnwzwrfh.html

[S30] C：头文件保护
来源：http://dali.iojbl.cn/Article/details/gtwcpiiqvc.html

#ifndef X_H
来源：http://dali.c1oappe.top/Article/details/gttatesnek.html

#define X_H
来源：http://dali.fzhhl.top/Article/details/gtkipuwpqe.html

#endif
来源：http://dali.cqqwz.cn/Article/details/gtaeynvymi.html

[S31] C++：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtvwaoazzz.html

#include <iostream>
来源：http://dali.guowangkeji.top/Article/details/gtlryylsfg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.snrcjt.cn/Article/details/gtlrngidif.html

[S32] C++：字符串
来源：http://dali.dianchejie.cn/Article/details/gtzofjpzjt.html

std::string s = "hi";  s += "!";
来源：http://dali.birdmap.top/Article/details/gtdxvcvecz.html

[S33] C++：vector 增删
来源：http://dali.zycfv.cn/Article/details/gtvwwslpgn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tian-w.cn/Article/details/gtjiacwlsd.html

[S34] C++：遍历 vector
来源：http://dali.shangyingyoupin.top/Article/details/gthigyfjet.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.havefunace.top/Article/details/gtweslofyd.html

[S35] C++：map
来源：http://dali.shanyushiyangkeji.top/Article/details/gtftgavzai.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.bjfxy.top/Article/details/gtopfffykg.html

[S36] C++：unordered_map
来源：http://dali.hysaishi.cn/Article/details/gtrmxdsxql.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gthefqfahp.html

[S37] C++：set
来源：http://dali.ivvv.top/Article/details/gtwghklazf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.guannengcc.top/Article/details/gtafaqwudn.html

[S38] C++：排序
来源：http://dali.jqgfzy.top/Article/details/gtqohpluav.html

std::sort(v.begin(), v.end());
来源：http://dali.fzhhl.top/Article/details/gtaxxifwjb.html

[S39] C++：自定义比较器排序
来源：http://dali.yvedp.cn/Article/details/gtythzlxak.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zycfv.cn/Article/details/gteiuswzuv.html

[S40] C++：查找元素
来源：http://dali.pycfn.com/Article/details/gtsblhzqvg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.meibo888.top/Article/details/gtztmvocqo.html

[S41] C++：类与构造函数
来源：http://dali.hnxiangtu.top/Article/details/gtwthnpvli.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.havefunace.top/Article/details/gthvtqxirc.html

[S42] C++：继承与虚函数
来源：http://dali.c1oappe.top/Article/details/gthycmraul.html

class B : public Base { public: void f() override {} };
来源：http://dali.ydzc1.top/Article/details/gtfzjzmxpl.html

[S43] C++：智能指针
来源：http://dali.xuetiantiany.cn/Article/details/gtnusyswtw.html

auto p = std::make_unique<int>(5);
来源：http://dali.yuanzhike.top/Article/details/gtjstbomxu.html

[S44] C++：引用传参
来源：http://dali.nanxuanxn.top/Article/details/gtkcidmzgk.html

void inc(int &x) { ++x; }
来源：http://dali.yueranfly.top/Article/details/gtabeszazi.html

[S45] C++：lambda
来源：http://dali.yvedp.cn/Article/details/gtymgoovyu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jiagoushi.top/Article/details/gtooebfajl.html

[S46] C++：函数模板
来源：http://dali.jianghu66.top/Article/details/gtpltigfrh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gaohongyu789.top/Article/details/gttlazcawh.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhixingplan.top/Article/details/gtxfalwdgl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhiwuduotai.top/Article/details/gtaahowebr.html

[S48] C++：逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gtuvoupwnh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.aibaodan.cn/Article/details/gtpbmnaltp.html

while (std::getline(in, line)) { }
来源：http://dali.nanxuanxn.top/Article/details/gtoboanqqo.html

[S49] C++：写文件
来源：http://dali.ehwqpu.com/Article/details/gtsoqcjolb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ydzc1.top/Article/details/gtavogagwf.html

[S50] C++：格式化数字
来源：http://dali.cheryme.top/Article/details/gtxzqvacdu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gtejpyzirw.html

[S51] C++：显式类型转换
来源：http://dali.shzxlz.cn/Article/details/gtbesochyh.html

static_cast<double>(a) / b
来源：http://dali.gotoacloud.top/Article/details/gttrsrnkoy.html

[S52] C++：const 与 noexcept
来源：http://dali.smart0.xyz/Article/details/gtpvkkknyc.html

int size() const noexcept { return n_; }
来源：http://dali.cqqwz.cn/Article/details/gteniylnxp.html

[S53] C++：移动语义
来源：http://dali.yonumen.top/Article/details/gtpaavduma.html

std::vector<int> w = std::move(v);
来源：http://dali.316326.xyz/Article/details/gtudtziwbe.html

[S54] C++：异常处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtrrjltxfp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tianlin.xyz/Article/details/gttyfnnbxs.html

[S55] C++：结构化绑定
来源：http://dali.c1oappe.top/Article/details/gtwtqblfii.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gotoacloud.top/Article/details/gtthgenjcv.html

[S56] C++：optional
来源：http://dali.quarkkingdee.top/Article/details/gtqaiidoih.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhengqikj.top/Article/details/gtgutozskk.html

[S57] C++：编译期常量
来源：http://dali.sufxvd.cn/Article/details/gtsmboqnvb.html

constexpr int N = 10;
来源：http://dali.daria6918.cn/Article/details/gtrqaxeumg.html

[S58] C++：命名空间
来源：http://dali.sysykeji.top/Article/details/gtijsvzdhp.html

namespace ns { int f() { return 1; } }
来源：http://dali.dianchejie.cn/Article/details/gtitdnpglx.html

[S59] C++：静态断言
来源：http://dali.xylfe.cn/Article/details/gtbnislvxp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gaohongyu789.top/Article/details/gtzifqmbmh.html

[S60] C++：遍历并删除元素
来源：http://dali.wangdashe.top/Article/details/gtqmyxtaum.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.smart0.xyz/Article/details/gtmstihjqg.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtfsofuacy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxinkj.top/Article/details/gtkuczbosw.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtraddwkru.html

[T01] Kotlin：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtzhatqyha.html

println("Hello")
来源：http://dali.sysykeji.top/Article/details/gtlbpqztnl.html

[T02] Kotlin：变量
来源：http://dali.birdmap.top/Article/details/gtvphwomvv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.aibaodan.cn/Article/details/gtzlfzgroo.html

[T03] Kotlin：字符串模板
来源：http://dali.vqdsnc.cn/Article/details/gtoqsumhbv.html

"值: $b"
来源：http://dali.c1oappe.top/Article/details/gtuielbwmn.html

[T04] Kotlin：空安全
来源：http://dali.ehwqpu.com/Article/details/gtncscditz.html

val n: String? = null;  n?.length
来源：http://dali.meibo888.top/Article/details/gthraveicv.html

[T05] Kotlin：when 表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfwweglgk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.dianchejie.cn/Article/details/gtojismywu.html

[T06] Kotlin：集合映射
来源：http://dali.xuanzx.com/Article/details/gtodmkpyuv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gttjtmdtls.html

[T07] Kotlin：集合过滤
来源：http://dali.aizwys.cn/Article/details/gtfglvmgmv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.andypj.xyz/Article/details/gtnnricwkn.html

[T08] Kotlin：数据类
来源：http://dali.xziqi.cn/Article/details/gtmqyfunox.html

data class User(val name: String, val age: Int)
来源：http://dali.zhengqikj.top/Article/details/gtxeqzytna.html

[T09] Kotlin：扩展函数
来源：http://dali.chenlongwang.top/Article/details/gtnjxflrvw.html

fun String.exclaim() = this + "!"
来源：http://dali.sxryk.cn/Article/details/gtxxycvvjj.html

[T10] Kotlin：默认参数
来源：http://dali.nanxinkj.top/Article/details/gthjbxmrra.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.guowangkeji.top/Article/details/gtkoovdexa.html

[T11] Kotlin：协程
来源：http://dali.yongpay.top/Article/details/gtmsyxajen.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.c1oappe.top/Article/details/gtoxfgvkrq.html

[T12] Kotlin：解构声明
来源：http://dali.jinqigfzy.top/Article/details/gtkrdeydhu.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinqigufen.top/Article/details/gtvgchkcjs.html

[T13] Kotlin：只读 Map
来源：http://dali.jinqigfzy.top/Article/details/gtgdqkypwb.html

val m = mapOf("a" to 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtfkpvphkz.html

[T14] Kotlin：循环
来源：http://dali.kuanghao11.cn/Article/details/gtgpfjgncn.html

for (i in 1..10) println(i)
来源：http://dali.havefunace.top/Article/details/gtjmubbfys.html

[T15] Kotlin：接口
来源：http://dali.jiagoushi.top/Article/details/gtipjuhzka.html

interface Shape { fun area(): Double }
来源：http://dali.fengsongda.top/Article/details/gtysjtvvei.html

[T16] Swift：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtrefsziqu.html

print("Hello")
来源：http://dali.cheryme.top/Article/details/gtogeoukfi.html

[T17] Swift：变量与常量
来源：http://dali.nanxinkj.top/Article/details/gtuploqplh.html

var a = 1;  let b = 2
来源：http://dali.zdqjudy.top/Article/details/gtqxwtcrpn.html

[T18] Swift：字符串插值
来源：http://dali.yongpay.top/Article/details/gtzchsddwb.html

"值: \(b)"
来源：http://dali.snrcjt.cn/Article/details/gtfofhngan.html

[T19] Swift：可选绑定
来源：http://dali.cqqwz.cn/Article/details/gtwemfjffe.html

if let n = opt { print(n) }
来源：http://dali.zhengqikj.top/Article/details/gtjcfardyp.html

[T20] Swift：数组操作
来源：http://dali.shanyushiyangtech.top/Article/details/gtknffhxyf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hnxiangtu.top/Article/details/gtfskumueq.html

[T21] Swift：遍历
来源：http://dali.daxiang520.top/Article/details/gtitltqtep.html

for x in a { print(x) }
来源：http://dali.sweek.top/Article/details/gtgiobkdit.html

[T22] Swift：字典
来源：http://dali.ivvv.top/Article/details/gtxjhraqct.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xziqi.cn/Article/details/gtrloldsmn.html

[T23] Swift：函数
来源：http://dali.ehwqpu.com/Article/details/gtrkxnxgfg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdvbakftp.html

[T24] Swift：闭包
来源：http://dali.fengsongda.top/Article/details/gtsnlxhrob.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.tian-w.cn/Article/details/gtvqmfstzf.html

[T25] Swift：结构体
来源：http://dali.jlsjyb.cn/Article/details/gturorqapw.html

struct P { var x: Int }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcpalwusv.html

[T26] Swift：类与重写
来源：http://dali.meibo888.top/Article/details/gtcnarskud.html

class A: Base { override func f() {} }
来源：http://dali.daria6918.cn/Article/details/gtxrclalpr.html

[T27] Swift：错误处理
来源：http://dali.ppjwa.cn/Article/details/gtekdtcrre.html

do { try f() } catch { print(error) }
来源：http://dali.tian-w.cn/Article/details/gteeuqqquq.html

[T28] Swift：枚举
来源：http://dali.xuetiantiany.cn/Article/details/gthmaljeks.html

enum Color { case red, green }
来源：http://dali.redwolf501.top/Article/details/gtgwrbvwuw.html

[T29] Swift：guard 提前返回
来源：http://dali.yanxiufei.cn/Article/details/gtgoxhnuiz.html

guard let x = opt else { return }
来源：http://dali.xinyue.icu/Article/details/gtbnkrwbwr.html

[T30] Swift：协议
来源：http://dali.nanxuanxn.top/Article/details/gtumymzgdt.html

protocol Shape { func area() -> Double }
来源：http://dali.yuanzhike.top/Article/details/gtedkhelnv.html

[T31] Lua：Hello World
来源：http://dali.mhx1999.top/Article/details/gtsokidkxh.html

print("Hello")
来源：http://dali.sysykeji.top/Article/details/gtvuonqcbf.html

[T32] Lua：局部变量
来源：http://dali.cheryme.top/Article/details/gtutqlypnc.html

local a = 1
来源：http://dali.sxryk.cn/Article/details/gtbnhuwwuq.html

[T33] Lua：表（数组）
来源：http://dali.zhongyouzk.top/Article/details/gtuatilujp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ivvv.top/Article/details/gtmnuodivi.html

[T34] Lua：遍历表
来源：http://dali.gotoacloud.top/Article/details/gtnvnimazi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtatptmgln.html

[T35] Lua：字典表
来源：http://dali.nwbrower.top/Article/details/gtzyzqnlax.html

local d = { a = 1 };  d.b = 2
来源：http://dali.quarkkingdee.top/Article/details/gtzzgykgdv.html

[T36] Lua：函数
来源：http://dali.wangshuangyany.cn/Article/details/gtojgulfkk.html

function add(a, b) return a + b end
来源：http://dali.sweek.top/Article/details/gtzlbrxiyv.html

[T37] Lua：字符串拼接
来源：http://dali.jianghu66.top/Article/details/gtlbogqhpd.html

"a" .. "b"
来源：http://dali.316326.xyz/Article/details/gtnhkicyrp.html

[T38] Lua：条件
来源：http://dali.wangdashe.top/Article/details/gtzgsgjpvo.html

if x > 0 then print("正") end
来源：http://dali.zhixingplan.top/Article/details/gtbnxsjprn.html

[T39] Lua：模式匹配
来源：http://dali.yj20258888.top/Article/details/gthniejhsf.html

string.find(s, "%d+")
来源：http://dali.fengsongda.top/Article/details/gtpgiqqnsz.html

[T40] Lua：元表
来源：http://dali.wangshuangyany.cn/Article/details/gtpjdotvua.html

setmetatable({}, { __index = base })
来源：http://dali.zhiwuduotai.top/Article/details/gtxiaaprqx.html

[T41] Perl：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtdmpwqdtq.html

print "Hello\n";
来源：http://dali.zhoulong.xyz/Article/details/gtpbcwbgla.html

[T42] Perl：变量类型
来源：http://dali.chenjidiqi.icu/Article/details/gtaabuigkc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cucudq.cn/Article/details/gtfkbvjdft.html

[T43] Perl：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gtntkeuwmx.html

"值: $a"
来源：http://dali.smart0.xyz/Article/details/gtsbsuipww.html

[T44] Perl：条件
来源：http://dali.kuanghao11.cn/Article/details/gtwlqmpllg.html

if ($a > 0) { print "正"; }
来源：http://dali.kuanghao11.cn/Article/details/gtuoylbcpg.html

[T45] Perl：数组遍历
来源：http://dali.cheryme.top/Article/details/gtjgizxvhz.html

for my $x (@arr) { print $x; }
来源：http://dali.zhongyouzk.top/Article/details/gtcipoxxbf.html

[T46] Perl：哈希操作
来源：http://dali.ydzc1.top/Article/details/gtrpxwcxqg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.nanxuanxn.top/Article/details/gtvincxuiu.html

[T47] Perl：正则捕获
来源：http://dali.andypj.xyz/Article/details/gthsjefvjp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtagflneej.html

[T48] Perl：正则替换
来源：http://dali.cucudq.cn/Article/details/gtolltjtpg.html

$s =~ s/old/new/g;
来源：http://dali.meibo888.top/Article/details/gtnflattho.html

[T49] Perl：函数
来源：http://dali.shangyingyoupin.top/Article/details/gtrgbumhpo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtakctzwny.html

[T50] Perl：逐行读文件
来源：http://dali.redwolf501.top/Article/details/gtprszzvgq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.guowangkeji.top/Article/details/gtmkgmypqs.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbpmepvr.html

[T51] Scala：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtoymdztoy.html

println("Hello")
来源：http://dali.gzhubu.top/Article/details/gtqllxnjaz.html

[T52] Scala：变量
来源：http://dali.pycfn.com/Article/details/gtfuovmtai.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gtoutnxbcv.html

[T53] Scala：字符串插值
来源：http://dali.daxiang520.top/Article/details/gtzlnrlwuw.html

s"值: $b"
来源：http://dali.aibaodan.cn/Article/details/gtesexwdsd.html

[T54] Scala：集合映射
来源：http://dali.vqdsnc.cn/Article/details/gtdexnwsao.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jyoumei.cn/Article/details/gthpkftlys.html

[T55] Scala：集合过滤
来源：http://dali.gzhubu.top/Article/details/gtdtmqrkph.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.andypj.xyz/Article/details/gttzdpurdl.html

[T56] Scala：样例类
来源：http://dali.nwbrower.top/Article/details/gthdzjtnwv.html

case class User(name: String, age: Int)
来源：http://dali.yuanzhike.top/Article/details/gtewdvrocb.html

[T57] Scala：模式匹配
来源：http://dali.yj202588.top/Article/details/gtnqnmjivc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.fengsongda.top/Article/details/gtscztmvrb.html

[T58] Scala：函数定义
来源：http://dali.hysaishi.cn/Article/details/gtmeopzwgq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yvedp.cn/Article/details/gtggztwpvq.html

[T59] Scala：循环
来源：http://dali.jianghu66.top/Article/details/gtijardxyk.html

for (i <- 1 to 10) println(i)
来源：http://dali.kuanghao11.cn/Article/details/gtoyjanedd.html

[T60] Scala：折叠
来源：http://dali.ydzc1.top/Article/details/gtmkumsfpd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shuidangran.top/Article/details/gtihirteva.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtadpxjtns.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.pycfn.com/Article/details/gtotgtilxv.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtuzlaaeiv.html

[U01] Py：创建虚拟环境
来源：http://dali.tanke756.top/Article/details/gtbvocuymz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shanyushiyangtech.top/Article/details/gtcxrmzsst.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hammf.cn/Article/details/gtiilnwtmj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cashguo.top/Article/details/gtrhbshupj.html

[U03] Py：加载 .env 配置
来源：http://dali.bjfxy.top/Article/details/gtqkkavmqd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jinqigfzy.top/Article/details/gtchdmkmil.html

[U04] Py：变量调试打印
来源：http://dali.jqgfzy.top/Article/details/gtlzivkgik.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xziqi.cn/Article/details/gtsrdqvbij.html

[U05] Py：列表去重且保序
来源：http://dali.nwbrower.top/Article/details/gtsmtmugbg.html

list(dict.fromkeys(arr))
来源：http://dali.hysaishi.cn/Article/details/gthnciofhh.html

[U06] Py：合并两个字典
来源：http://dali.tian-w.cn/Article/details/gtjjnhzolr.html

{**a, **b}
来源：http://dali.yj202588.top/Article/details/gtjtjeqako.html

[U07] Py：反转字典键值
来源：http://dali.jlsjyb.cn/Article/details/gtqzfowegz.html

{v: k for k, v in d.items()}
来源：http://dali.smart0.xyz/Article/details/gtvonfjenl.html

[U08] Py：展平二维列表
来源：http://dali.vqdsnc.cn/Article/details/gtaygjsgve.html

[y for x in nested for y in x]
来源：http://dali.daxiang520.top/Article/details/gtebpxxovt.html

[U09] Py：字典取最大值的键
来源：http://dali.hnqzz.top/Article/details/gtzdobunkb.html

max(d, key=d.get)
来源：http://dali.daxiang520.top/Article/details/gtdprorcre.html

[U10] Py：按值排序字典
来源：http://dali.ehwqpu.com/Article/details/gtlrfdrshq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gtfzavbwme.html

[U11] Py：生成器表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtgwisgagw.html

(x * 2 for x in arr)
来源：http://dali.yuxming.cn/Article/details/gthhsyjcjf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jianghu66.top/Article/details/gtaqtotjkh.html

Counter(arr).most_common(3)
来源：http://dali.ybcxt.top/Article/details/gtscnvybyk.html

[U13] Py：固定长度队列
来源：http://dali.gaohongyu789.top/Article/details/gtbamhthuh.html

deque(maxlen=10)
来源：http://dali.jqgufenzy.top/Article/details/gtglynroun.html

[U14] Py：分组收集到列表
来源：http://dali.tanke756.top/Article/details/gtqldrnwhm.html

defaultdict(list)
来源：http://dali.hysaishi.cn/Article/details/gtguafsnoe.html


<!-- 参考信息 -->