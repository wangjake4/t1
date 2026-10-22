代发 wailian999

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.daxiang520.top/Article/details/gt2pyiunprt.html

[R72] 等待端口就绪
来源：http://dali.gzhubu.top/Article/details/gt2tpuijvvf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gaohongyu789.top/Article/details/gt2qlpimopg.html

[R73] 分割大日志
来源：http://dali.jinqigufen.top/Article/details/gt2btcgxqlj.html

split -l 1000 big.log part_
来源：http://dali.jinqigfzy.top/Article/details/gt2sgjdtrou.html

[R74] 批量重命名
来源：http://dali.hywenlv.cn/Article/details/gt2sbuyfqqm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.9152youxi.cn/Article/details/gt2ixowbtnx.html

[R75] 导出环境变量
来源：http://dali.yj20258888.top/Article/details/gt2nhtkvgbd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sufxvd.cn/Article/details/gt2ikgrjzvl.html

[R76] 使用临时文件
来源：http://dali.xuanzx.com/Article/details/gt2eazzjxlo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.aibaodan.cn/Article/details/gt2bkpqpdjr.html

[R77] 读取用户输入
来源：http://dali.yuanzhike.top/Article/details/gt2quubadyn.html

read -rp "请输入: " ans
来源：http://dali.yj202588.top/Article/details/gt2harfqehv.html

[R78] 交互式菜单
来源：http://dali.vqdsnc.cn/Article/details/gt2ewlinfbs.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.kuanghao11.cn/Article/details/gt2nelqkoii.html

[R79] 解析命令行选项
来源：http://dali.tianlin.xyz/Article/details/gt2ectcnevw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yangfankeji.com/Article/details/gt2yytjjwmp.html

[R80] 查看脚本执行耗时
来源：http://dali.pengpengdd.cyou/Article/details/gt2oaqjamkt.html

time ./run.sh
来源：http://dali.hfpthk.cn/Article/details/gt2olghmokn.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2qfkmivwe.html

S. C / C++ 专题
来源：http://dali.yj202588.top/Article/details/gt2lmtqeiow.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ukggvlvo.html

[S01] C：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gt2rfhprwmw.html

#include <stdio.h>
来源：http://dali.zhongyouzk.top/Article/details/gt2fsqqnlai.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yueranfly.top/Article/details/gt2djhogjpq.html

[S02] C：变量与格式化输出
来源：http://dali.cashguo.top/Article/details/gt2nivuioij.html

int a = 10; printf("%d\n", a);
来源：http://dali.jqgufenzy.top/Article/details/gt2egvzgwlb.html

[S03] C：读入整数
来源：http://dali.hysaishi.cn/Article/details/gt2qhvnjymm.html

int x; scanf("%d", &x);
来源：http://dali.zhengqikj.top/Article/details/gt2wwazolsu.html

[S04] C：字符串复制
来源：http://dali.wangdashe.top/Article/details/gt2zqbtwyar.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hjwzeiuf.html

[S05] C：字符串长度
来源：http://dali.sweek.top/Article/details/gt2xugakeqk.html

strlen(s)
来源：http://dali.cqqwz.cn/Article/details/gt2nxqhtbur.html

[S06] C：字符串比较
来源：http://dali.sxryk.cn/Article/details/gt2jnqavqnd.html

strcmp(a, b) == 0
来源：http://dali.hnxiangtu.top/Article/details/gt2bzqppzxt.html

[S07] C：数组遍历求和
来源：http://dali.birdmap.top/Article/details/gt2lvxveutn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hywenlv.cn/Article/details/gt2glimvpcz.html

[S08] C：动态内存分配与释放
来源：http://dali.mhx1999.top/Article/details/gt2symxgizi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tianlin.xyz/Article/details/gt2ikjxvcpg.html

[S09] C：结构体定义与初始化
来源：http://dali.xuanzx.com/Article/details/gt2trdblcfg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj20258888.top/Article/details/gt2isezquid.html

[S10] C：指针与解引用
来源：http://dali.hnqzz.top/Article/details/gt2zrhxmakq.html

int *p = &a;  *p = 5;
来源：http://dali.pycfn.com/Article/details/gt2jhugjhoo.html

[S11] C：逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gt2tqooohwn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhixingplan.top/Article/details/gt2jzfnmnsi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cdnleiting.top/Article/details/gt2uwlkpzox.html

fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gt2dtrvkfyj.html

[S12] C：写文件
来源：http://dali.tianlin.xyz/Article/details/gt2ihubqneh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sweek.top/Article/details/gt2cpoyfcpc.html

[S13] C：宏定义
来源：http://dali.guowangkeji.top/Article/details/gt2sbjlbrlr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tlvpcbet.html

[S14] C：枚举
来源：http://dali.zycfv.cn/Article/details/gt2ugenscib.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhixingplan.top/Article/details/gt2lriddrkd.html

[S15] C：类型转换
来源：http://dali.pycfn.com/Article/details/gt2pzuehkjt.html

(double) a / b
来源：http://dali.cqqwz.cn/Article/details/gt2wkkzqgnk.html

[S16] C：位操作置位
来源：http://dali.cheryme.top/Article/details/gt2vunnthck.html

x |= (1 << 3);
来源：http://dali.zycfv.cn/Article/details/gt2ngtcjjbg.html

[S17] C：安全拼接字符串
来源：http://dali.havefunace.top/Article/details/gt2twvhmymv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2orxrbrdv.html

[S18] C：命令行参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2bisxqnax.html

int main(int argc, char **argv)
来源：http://dali.ehwqpu.com/Article/details/gt2siqqoqik.html

[S19] C：快速排序
来源：http://dali.jqgfzy.top/Article/details/gt2yekwayxy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.svipenyu.cn/Article/details/gt2pypcmjuf.html

[S20] C：二分查找
来源：http://dali.quarkkingdee.top/Article/details/gt2eftepztk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gt2vdpntkjy.html

[S21] C：字符类别判断
来源：http://dali.yueranfly.top/Article/details/gt2trnrwhtx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cheryme.top/Article/details/gt2ihzjwcbu.html

[S22] C：字符串转数字
来源：http://dali.xuetiantiany.cn/Article/details/gt2ywmzxmoo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhengqikj.top/Article/details/gt2agwblvsz.html

[S23] C：随机数
来源：http://dali.hfpthk.cn/Article/details/gt2xapasdkd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cdnleiting.top/Article/details/gt2rjcncknt.html

[S24] C：获取本地时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yntylnkb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ybcxt.top/Article/details/gt2jedgbkcg.html

[S25] C：内存拷贝
来源：http://dali.xylfe.cn/Article/details/gt2qlwucrnf.html

memcpy(dst, src, n);
来源：http://dali.nwbrower.top/Article/details/gt2khvndvct.html

[S26] C：内存清零
来源：http://dali.jqgufenzy.top/Article/details/gt2ykxgsfol.html

memset(a, 0, sizeof a);
来源：http://dali.hammf.cn/Article/details/gt2rmflepra.html

[S27] C：定义常量
来源：http://dali.yueranfly.top/Article/details/gt2vzlsifuw.html

const double PI = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ougeqvcw.html

[S28] C：静态变量
来源：http://dali.vqdsnc.cn/Article/details/gt2moevophq.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2blsttufj.html

[S29] C：变参函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2fndvcnod.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.andypj.xyz/Article/details/gt2qgwzhgho.html

[S30] C：头文件保护
来源：http://dali.ppjwa.cn/Article/details/gt2umhvyopp.html

#ifndef X_H
来源：http://dali.zhongyouzk.top/Article/details/gt2nxbxeeqq.html

#define X_H
来源：http://dali.shangyingyoupin.top/Article/details/gt2bvgayfct.html

#endif
来源：http://dali.jqgfzy.top/Article/details/gt2btxwskda.html

[S31] C++：Hello World
来源：http://dali.yonumen.top/Article/details/gt2jcfugnkh.html

#include <iostream>
来源：http://dali.jqgfzy.top/Article/details/gt2dcownsrv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yangfankeji.com/Article/details/gt2kkjpzkxw.html

[S32] C++：字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2pkrlgruv.html

std::string s = "hi";  s += "!";
来源：http://dali.jqgufenzy.top/Article/details/gt2tixjuanz.html

[S33] C++：vector 增删
来源：http://dali.hywenlv.cn/Article/details/gt2kktgdfuu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2eskdclpn.html

[S34] C++：遍历 vector
来源：http://dali.zhiwuduotai.top/Article/details/gt2scxbgbxk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhongyouzk.top/Article/details/gt2pdvgcmqz.html

[S35] C++：map
来源：http://dali.sufxvd.cn/Article/details/gt2bxbkeoks.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nwbrower.top/Article/details/gt2jprpyini.html

[S36] C++：unordered_map
来源：http://dali.andypj.xyz/Article/details/gt2zudsstow.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aizwys.cn/Article/details/gt2xppzkwmi.html

[S37] C++：set
来源：http://dali.havefunace.top/Article/details/gt2yybjxbde.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yonumen.top/Article/details/gt2veztbvya.html

[S38] C++：排序
来源：http://dali.gotoacloud.top/Article/details/gt2dbmanbou.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkmpcga.html

[S39] C++：自定义比较器排序
来源：http://dali.zhiwuduotai.top/Article/details/gt2yexjzvrs.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shangyingyoupin.top/Article/details/gt2sdlwmlry.html

[S40] C++：查找元素
来源：http://dali.jianghu66.top/Article/details/gt2gnkyfrqf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ehwqpu.com/Article/details/gt2btvdryof.html

[S41] C++：类与构造函数
来源：http://dali.jinqigfzy.top/Article/details/gt2mvjwznbt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yj20258.top/Article/details/gt2badsymca.html

[S42] C++：继承与虚函数
来源：http://dali.hnqzz.top/Article/details/gt2galaeiln.html

class B : public Base { public: void f() override {} };
来源：http://dali.shangyingyoupin.top/Article/details/gt2arrikunl.html

[S43] C++：智能指针
来源：http://dali.yonumen.top/Article/details/gt2wnuyeedk.html

auto p = std::make_unique<int>(5);
来源：http://dali.daxiang520.top/Article/details/gt2xlujfxmp.html

[S44] C++：引用传参
来源：http://dali.redwolf501.top/Article/details/gt2cbcfuqdt.html

void inc(int &x) { ++x; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rxvgbaqs.html

[S45] C++：lambda
来源：http://dali.jinqigufen.top/Article/details/gt2ozlfgius.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yangfankeji.com/Article/details/gt2khounddp.html

[S46] C++：函数模板
来源：http://dali.c1oappe.top/Article/details/gt2mdazdkle.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gotoacloud.top/Article/details/gt2zkwcxfda.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhixingplan.top/Article/details/gt2wqyiemdt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.birdmap.top/Article/details/gt2hjnzeskl.html

[S48] C++：逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gt2aypsrbzh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.pycfn.com/Article/details/gt2dktymdxi.html

while (std::getline(in, line)) { }
来源：http://dali.wangdashe.top/Article/details/gt2vnxmywhi.html

[S49] C++：写文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ngjnflqf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj20258.top/Article/details/gt2ylkaqxnr.html

[S50] C++：格式化数字
来源：http://dali.jlsjyb.cn/Article/details/gt2nuiartsf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gt2qwaqtbbp.html

[S51] C++：显式类型转换
来源：http://dali.ybcxt.top/Article/details/gt2qeyiyfej.html

static_cast<double>(a) / b
来源：http://dali.gogol.net.cn/Article/details/gt2axqbxhfo.html

[S52] C++：const 与 noexcept
来源：http://dali.dashuyun.cn/Article/details/gt2mvfvlgqu.html

int size() const noexcept { return n_; }
来源：http://dali.yangfankeji.com/Article/details/gt2nfblsxfc.html

[S53] C++：移动语义
来源：http://dali.dashuyun.cn/Article/details/gt2hcymbstd.html

std::vector<int> w = std::move(v);
来源：http://dali.dashuyun.cn/Article/details/gt2nxepgrjm.html

[S54] C++：异常处理
来源：http://dali.jianghu66.top/Article/details/gt2kbhwnjwb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.bjfxy.top/Article/details/gt2qvzzjzoj.html

[S55] C++：结构化绑定
来源：http://dali.hysaishi.cn/Article/details/gt2whkrynis.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.pycfn.com/Article/details/gt2ubsjkyzq.html

[S56] C++：optional
来源：http://dali.jqgfzy.top/Article/details/gt2axwmraov.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2gfgcwppu.html

[S57] C++：编译期常量
来源：http://dali.snrcjt.cn/Article/details/gt2wnsuioyu.html

constexpr int N = 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wxalfior.html

[S58] C++：命名空间
来源：http://dali.sxryk.cn/Article/details/gt2lynlmhcr.html

namespace ns { int f() { return 1; } }
来源：http://dali.mhx1999.top/Article/details/gt2zsvxvvun.html

[S59] C++：静态断言
来源：http://dali.xuanzx.com/Article/details/gt2wurgwecc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gzhubu.top/Article/details/gt2rgfwtsxy.html

[S60] C++：遍历并删除元素
来源：http://dali.xuetiantiany.cn/Article/details/gt2vkykrbdg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.iojbl.cn/Article/details/gt2mktdssey.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2uouutejq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jqgufenzy.top/Article/details/gt2sqjnookh.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2brtbbcjr.html

[T01] Kotlin：Hello World
来源：http://dali.gogol.net.cn/Article/details/gt2sxhxscyu.html

println("Hello")
来源：http://dali.hysaishi.cn/Article/details/gt2iwpxdmpc.html

[T02] Kotlin：变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2qvgfbbfq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hammf.cn/Article/details/gt2xuvflzbl.html

[T03] Kotlin：字符串模板
来源：http://dali.xylfe.cn/Article/details/gt2lcxcpupf.html

"值: $b"
来源：http://dali.gogol.net.cn/Article/details/gt2xwzgyfxo.html

[T04] Kotlin：空安全
来源：http://dali.hammf.cn/Article/details/gt2xzdazgtg.html

val n: String? = null;  n?.length
来源：http://dali.sxryk.cn/Article/details/gt2pmcwkeov.html

[T05] Kotlin：when 表达式
来源：http://dali.shuidangran.top/Article/details/gt2qzmsqjam.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.chenjidiqi.icu/Article/details/gt2ajgduwec.html

[T06] Kotlin：集合映射
来源：http://dali.jqgufenzy.top/Article/details/gt2nnrxsgmn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zdqjudy.top/Article/details/gt2vaddtckk.html

[T07] Kotlin：集合过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tvuzjxei.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.c1oappe.top/Article/details/gt2gboytyso.html

[T08] Kotlin：数据类
来源：http://dali.ppjwa.cn/Article/details/gt2fmvusxgj.html

data class User(val name: String, val age: Int)
来源：http://dali.yuxming.cn/Article/details/gt2badcojwa.html

[T09] Kotlin：扩展函数
来源：http://dali.yonumen.top/Article/details/gt2vkflrwaa.html

fun String.exclaim() = this + "!"
来源：http://dali.hysaishi.cn/Article/details/gt2saqdemdj.html

[T10] Kotlin：默认参数
来源：http://dali.bjfxy.top/Article/details/gt2stqxrzvp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hnxiangtu.top/Article/details/gt2qsoyzobj.html

[T11] Kotlin：协程
来源：http://dali.ydzc1.top/Article/details/gt2jhxvukxq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gaohongyu789.top/Article/details/gt2ueignuem.html

[T12] Kotlin：解构声明
来源：http://dali.nwbrower.top/Article/details/gt2mgdgqarp.html

val (a, b) = Pair(1, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2aqfgzldu.html

[T13] Kotlin：只读 Map
来源：http://dali.aibaodan.cn/Article/details/gt2mtcjrkdv.html

val m = mapOf("a" to 1)
来源：http://dali.snrcjt.cn/Article/details/gt2gghhlowa.html

[T14] Kotlin：循环
来源：http://dali.chenlongwang.top/Article/details/gt2rrxfeegf.html

for (i in 1..10) println(i)
来源：http://dali.sweek.top/Article/details/gt2kevknvpa.html

[T15] Kotlin：接口
来源：http://dali.yj20258888.top/Article/details/gt2cbutsese.html

interface Shape { fun area(): Double }
来源：http://dali.yj20258.top/Article/details/gt2cvuxfrbz.html

[T16] Swift：Hello World
来源：http://dali.9152youxi.cn/Article/details/gt2uowgbgou.html

print("Hello")
来源：http://dali.hfpthk.cn/Article/details/gt2hrihrkju.html

[T17] Swift：变量与常量
来源：http://dali.yj20258888.top/Article/details/gt2reeyglii.html

var a = 1;  let b = 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2olldqbla.html

[T18] Swift：字符串插值
来源：http://dali.xuanzx.com/Article/details/gt2dlxcmfth.html

"值: \(b)"
来源：http://dali.c1oappe.top/Article/details/gt2znjkauoa.html

[T19] Swift：可选绑定
来源：http://dali.hnqzz.top/Article/details/gt2jwrikfwi.html

if let n = opt { print(n) }
来源：http://dali.jinqigufen.top/Article/details/gt2xcdiyvqx.html

[T20] Swift：数组操作
来源：http://dali.aibaodan.cn/Article/details/gt2izvzubiw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yongpay.top/Article/details/gt2nofqltgk.html

[T21] Swift：遍历
来源：http://dali.aizwys.cn/Article/details/gt2lsavfegu.html

for x in a { print(x) }
来源：http://dali.snrcjt.cn/Article/details/gt2ajrgdyxd.html

[T22] Swift：字典
来源：http://dali.yj20258.top/Article/details/gt2hjmsqmjz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jianghu66.top/Article/details/gt2sokitvea.html

[T23] Swift：函数
来源：http://dali.sweek.top/Article/details/gt2dbgnihuf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tian-w.cn/Article/details/gt2kffssila.html

[T24] Swift：闭包
来源：http://dali.xuanzx.com/Article/details/gt2zweethrc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.quarkkingdee.top/Article/details/gt2efdtklii.html

[T25] Swift：结构体
来源：http://dali.yongpay.top/Article/details/gt2vxiqsyst.html

struct P { var x: Int }
来源：http://dali.guowangkeji.top/Article/details/gt2wnnfbrfn.html

[T26] Swift：类与重写
来源：http://dali.yvedp.cn/Article/details/gt2dnugvuxd.html

class A: Base { override func f() {} }
来源：http://dali.haohaochexian.top/Article/details/gt2wudxdvje.html

[T27] Swift：错误处理
来源：http://dali.meibo888.top/Article/details/gt2melwetuh.html

do { try f() } catch { print(error) }
来源：http://dali.wangdashe.top/Article/details/gt2psfcljxw.html

[T28] Swift：枚举
来源：http://dali.yuanzhike.top/Article/details/gt2nhxyagbg.html

enum Color { case red, green }
来源：http://dali.bjfxy.top/Article/details/gt2wjafzawk.html

[T29] Swift：guard 提前返回
来源：http://dali.xziqi.cn/Article/details/gt2xxnesrtn.html

guard let x = opt else { return }
来源：http://dali.havefunace.top/Article/details/gt2iqppsazt.html

[T30] Swift：协议
来源：http://dali.haohaochexian.top/Article/details/gt2bepavves.html

protocol Shape { func area() -> Double }
来源：http://dali.vqdsnc.cn/Article/details/gt2qheetugd.html

[T31] Lua：Hello World
来源：http://dali.daxiang520.top/Article/details/gt2qtzhlheb.html

print("Hello")
来源：http://dali.xinyue.icu/Article/details/gt2irjptjcg.html

[T32] Lua：局部变量
来源：http://dali.chenlongwang.top/Article/details/gt2wjolxvgx.html

local a = 1
来源：http://dali.jqgufenzy.top/Article/details/gt2kfnzvalc.html

[T33] Lua：表（数组）
来源：http://dali.dashuyun.cn/Article/details/gt2xmhsmuac.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hammf.cn/Article/details/gt2aljkmioo.html

[T34] Lua：遍历表
来源：http://dali.316326.xyz/Article/details/gt2lwpspzom.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.tianlin.xyz/Article/details/gt2edkmvfmn.html

[T35] Lua：字典表
来源：http://dali.zhongyouzk.top/Article/details/gt2dpenrten.html

local d = { a = 1 };  d.b = 2
来源：http://dali.wangdashe.top/Article/details/gt2chuegato.html

[T36] Lua：函数
来源：http://dali.tanke756.top/Article/details/gt2gssckphs.html

function add(a, b) return a + b end
来源：http://dali.jqgufenzy.top/Article/details/gt2lhawxykx.html

[T37] Lua：字符串拼接
来源：http://dali.aibaodan.cn/Article/details/gt2mszdfyyc.html

"a" .. "b"
来源：http://dali.jlsjyb.cn/Article/details/gt2wskpuxvz.html

[T38] Lua：条件
来源：http://dali.zdqjudy.top/Article/details/gt2wykezpuj.html

if x > 0 then print("正") end
来源：http://dali.yj20258888.top/Article/details/gt2nekmktta.html

[T39] Lua：模式匹配
来源：http://dali.yangfankeji.com/Article/details/gt2zwvkdbxs.html

string.find(s, "%d+")
来源：http://dali.hammf.cn/Article/details/gt2zgiyjrrs.html

[T40] Lua：元表
来源：http://dali.hammf.cn/Article/details/gt2nbbvwxey.html

setmetatable({}, { __index = base })
来源：http://dali.ydzc1.top/Article/details/gt2zqiqrcyn.html

[T41] Perl：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2oxplceup.html

print "Hello\n";
来源：http://dali.gogol.net.cn/Article/details/gt2khkfjmez.html

[T42] Perl：变量类型
来源：http://dali.andypj.xyz/Article/details/gt2mbhmvolh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gaohongyu789.top/Article/details/gt2lvprvyfe.html

[T43] Perl：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2npckjpqr.html

"值: $a"
来源：http://dali.ppjwa.cn/Article/details/gt2xneczwle.html

[T44] Perl：条件
来源：http://dali.fengsongda.top/Article/details/gt2fwsajdpu.html

if ($a > 0) { print "正"; }
来源：http://dali.dianchejie.cn/Article/details/gt2cobmquay.html

[T45] Perl：数组遍历
来源：http://dali.hnqzz.top/Article/details/gt2qflsbkcx.html

for my $x (@arr) { print $x; }
来源：http://dali.zhixingplan.top/Article/details/gt2ycjnijdq.html

[T46] Perl：哈希操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ptssoqem.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yj202588.top/Article/details/gt2nuudfphw.html

[T47] Perl：正则捕获
来源：http://dali.yuanzhike.top/Article/details/gt2hueyecrf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.fengsongda.top/Article/details/gt2leqhfraw.html

[T48] Perl：正则替换
来源：http://dali.xuetiantiany.cn/Article/details/gt2fwnlztff.html

$s =~ s/old/new/g;
来源：http://dali.ydzc1.top/Article/details/gt2piwehqxh.html

[T49] Perl：函数
来源：http://dali.chenzaomai.com/Article/details/gt2hbjqtpxc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gt2otvjghve.html

[T50] Perl：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gt2wclcvohl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sysykeji.top/Article/details/gt2zlewthfh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gotoacloud.top/Article/details/gt2xftlxcpo.html

[T51] Scala：Hello World
来源：http://dali.cashguo.top/Article/details/gt2kepulqoa.html

println("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gt2maursowe.html

[T52] Scala：变量
来源：http://dali.tian-w.cn/Article/details/gt2lkgukfvn.html

val a = 1;  var b = 2
来源：http://dali.sufxvd.cn/Article/details/gt2zirznfid.html

[T53] Scala：字符串插值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gpublrgk.html

s"值: $b"
来源：http://dali.snrcjt.cn/Article/details/gt2cuouhpma.html

[T54] Scala：集合映射
来源：http://dali.andypj.xyz/Article/details/gt2slrhfqbc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.chenzaomai.com/Article/details/gt2vsdygvkq.html

[T55] Scala：集合过滤
来源：http://dali.daria6918.cn/Article/details/gt2mjhevacu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.tianlin.xyz/Article/details/gt2dlsrqvnz.html

[T56] Scala：样例类
来源：http://dali.yueranfly.top/Article/details/gt2yreaxeud.html

case class User(name: String, age: Int)
来源：http://dali.tanke756.top/Article/details/gt2hnznjowa.html

[T57] Scala：模式匹配
来源：http://dali.nanxuanxn.top/Article/details/gt2qbtteckv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ydzc1.top/Article/details/gt2urzgxevf.html

[T58] Scala：函数定义
来源：http://dali.nanxuanxn.top/Article/details/gt2aarxlktf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yongpay.top/Article/details/gt2phwaxjkc.html

[T59] Scala：循环
来源：http://dali.chenlongwang.top/Article/details/gt2yxfnhpmf.html

for (i <- 1 to 10) println(i)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gjjhvwim.html

[T60] Scala：折叠
来源：http://dali.smart0.xyz/Article/details/gt2coamvnsd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.aibaodan.cn/Article/details/gt2itzbppqk.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2plyenvbf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.guowangkeji.top/Article/details/gt2efbbaikl.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2urrbhgbr.html

[U01] Py：创建虚拟环境
来源：http://dali.zhoulong.xyz/Article/details/gt2ftayvoip.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xuetiantiany.cn/Article/details/gt2vuneoqut.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sweek.top/Article/details/gt2hndefoqe.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.iojbl.cn/Article/details/gt2bqhrcxht.html

[U03] Py：加载 .env 配置
来源：http://dali.tian-w.cn/Article/details/gt2kmpbzjjq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.guannengcc.top/Article/details/gt2dsglvyru.html

[U04] Py：变量调试打印
来源：http://dali.quarkkingdee.top/Article/details/gt2dccdrfiy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.aibaodan.cn/Article/details/gt2dnfspohg.html

[U05] Py：列表去重且保序
来源：http://dali.meibo888.top/Article/details/gt2sdlbobgi.html

list(dict.fromkeys(arr))
来源：http://dali.hnxiangtu.top/Article/details/gt2zfcbwoon.html

[U06] Py：合并两个字典
来源：http://dali.xinyue.icu/Article/details/gt2kwqvsjca.html

{**a, **b}
来源：http://dali.jinqigufen.top/Article/details/gt2unblhjjx.html

[U07] Py：反转字典键值
来源：http://dali.kuanghao11.cn/Article/details/gt2pxsiwbno.html

{v: k for k, v in d.items()}
来源：http://dali.xylfe.cn/Article/details/gt2nnvxlfvg.html

[U08] Py：展平二维列表
来源：http://dali.yvedp.cn/Article/details/gt2ygdpsgpk.html

[y for x in nested for y in x]
来源：http://dali.ydzc1.top/Article/details/gt2rybzfsoa.html

[U09] Py：字典取最大值的键
来源：http://dali.tianlin.xyz/Article/details/gt2orbrotpg.html

max(d, key=d.get)
来源：http://dali.nanxinkj.top/Article/details/gt2wzfujwip.html

[U10] Py：按值排序字典
来源：http://dali.hnxiangtu.top/Article/details/gt2dpsfagqy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.pycfn.com/Article/details/gt2bskdqmyl.html

[U11] Py：生成器表达式
来源：http://dali.aibaodan.cn/Article/details/gt2csklbzsc.html

(x * 2 for x in arr)
来源：http://dali.sweek.top/Article/details/gt2zftdtxed.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhoulong.xyz/Article/details/gt2flguxdad.html

Counter(arr).most_common(3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2abbpmvsg.html


<!-- 参考信息 -->