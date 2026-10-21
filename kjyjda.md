代发 wailian999

split -l 1000 big.log part_
来源：http://dali.9152youxi.cn/Article/details/gtlkmipehw.html

[R74] 批量重命名
来源：http://dali.tian-w.cn/Article/details/gtkcsthmgo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hfpthk.cn/Article/details/gtzdfyrhsf.html

[R75] 导出环境变量
来源：http://dali.pycfn.com/Article/details/gtyioxhaab.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.pengpengdd.cyou/Article/details/gtzvkgfnyn.html

[R76] 使用临时文件
来源：http://dali.cashguo.top/Article/details/gtdevhxfax.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jyoumei.cn/Article/details/gttpexubgy.html

[R77] 读取用户输入
来源：http://dali.fzhhl.top/Article/details/gtywoounyv.html

read -rp "请输入: " ans
来源：http://dali.shzxlz.cn/Article/details/gtrppxmoyv.html

[R78] 交互式菜单
来源：http://dali.yuxming.cn/Article/details/gtaoopufvw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shangyingyoupin.top/Article/details/gtjxvolpni.html

[R79] 解析命令行选项
来源：http://dali.mhx1999.top/Article/details/gtnaspiepd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yongpay.top/Article/details/gtucqgkaqx.html

[R80] 查看脚本执行耗时
来源：http://dali.yj20258.top/Article/details/gtfekwykzk.html

time ./run.sh
来源：http://dali.chenjidiqi.icu/Article/details/gtbxhueqhu.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtmbwwuhwn.html

S. C / C++ 专题
来源：http://dali.sysykeji.top/Article/details/gtlunrihfa.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtjmwijxwf.html

[S01] C：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtvzveissk.html

#include <stdio.h>
来源：http://dali.yj202588.top/Article/details/gtspoeftif.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nanxuanxn.top/Article/details/gtguarlqwg.html

[S02] C：变量与格式化输出
来源：http://dali.yj20258.top/Article/details/gtejzhyrak.html

int a = 10; printf("%d\n", a);
来源：http://dali.xylfe.cn/Article/details/gtbzixbqoc.html

[S03] C：读入整数
来源：http://dali.wangdashe.top/Article/details/gtfdlxiixf.html

int x; scanf("%d", &x);
来源：http://dali.yuxming.cn/Article/details/gtcklyamxi.html

[S04] C：字符串复制
来源：http://dali.jianghu66.top/Article/details/gtvxjwkpth.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgrjpfxpo.html

[S05] C：字符串长度
来源：http://dali.vqdsnc.cn/Article/details/gtlutxlwls.html

strlen(s)
来源：http://dali.hfpthk.cn/Article/details/gtbaiaglid.html

[S06] C：字符串比较
来源：http://dali.chenzaomai.com/Article/details/gthoudocrw.html

strcmp(a, b) == 0
来源：http://dali.zhixingplan.top/Article/details/gtxbogyasa.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gtrlhoshsi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yj20258.top/Article/details/gtfzhsujzy.html

[S08] C：动态内存分配与释放
来源：http://dali.havefunace.top/Article/details/gtnewwqqqf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.quarkkingdee.top/Article/details/gterreztfb.html

[S09] C：结构体定义与初始化
来源：http://dali.nanxinkj.top/Article/details/gtrhsginfm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.aibaodan.cn/Article/details/gtwgyudtvh.html

[S10] C：指针与解引用
来源：http://dali.c1oappe.top/Article/details/gtitlpkbtd.html

int *p = &a;  *p = 5;
来源：http://dali.tian-w.cn/Article/details/gtqsxfmfnt.html

[S11] C：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gtcotontoj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yvedp.cn/Article/details/gtbpkskvzt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.meibo888.top/Article/details/gtituhmjvz.html

fclose(f);
来源：http://dali.kuanghao11.cn/Article/details/gtcojbhdab.html

[S12] C：写文件
来源：http://dali.zhixingplan.top/Article/details/gtjenryjyy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hnxiangtu.top/Article/details/gtwphlxumd.html

[S13] C：宏定义
来源：http://dali.smart0.xyz/Article/details/gtltawarkl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cashguo.top/Article/details/gtwvlgfqen.html

[S14] C：枚举
来源：http://dali.yangfankeji.com/Article/details/gtcwchztcr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.haohaochexian.top/Article/details/gtgxrdnsey.html

[S15] C：类型转换
来源：http://dali.shangyingyoupin.top/Article/details/gtyyldlotk.html

(double) a / b
来源：http://dali.0kj1m.cn/Article/details/gtznxxqlye.html

[S16] C：位操作置位
来源：http://dali.jinqigufen.top/Article/details/gtdcfcpljv.html

x |= (1 << 3);
来源：http://dali.tian-w.cn/Article/details/gtxkaebmjf.html

[S17] C：安全拼接字符串
来源：http://dali.hammf.cn/Article/details/gttaiohczr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hongshengwenyu.top/Article/details/gtcpgyraeg.html

[S18] C：命令行参数
来源：http://dali.fzhhl.top/Article/details/gtzdisviek.html

int main(int argc, char **argv)
来源：http://dali.chenlongwang.top/Article/details/gtvwxljfda.html

[S19] C：快速排序
来源：http://dali.ivvv.top/Article/details/gtztkpsaew.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yanxiufei.cn/Article/details/gtlgbbfhnh.html

[S20] C：二分查找
来源：http://dali.hfpthk.cn/Article/details/gtzgggmtxr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gtpftcfnjd.html

[S21] C：字符类别判断
来源：http://dali.nanxuanxn.top/Article/details/gtovumtcbv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdimxnnlj.html

[S22] C：字符串转数字
来源：http://dali.aibaodan.cn/Article/details/gtarwoiajp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtilckwwhn.html

[S23] C：随机数
来源：http://dali.andypj.xyz/Article/details/gtmcyfasdi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ehwqpu.com/Article/details/gtujsqhojq.html

[S24] C：获取本地时间
来源：http://dali.jlsjyb.cn/Article/details/gtzvppzlja.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yongpay.top/Article/details/gthtnmsogq.html

[S25] C：内存拷贝
来源：http://dali.zhongyouzk.top/Article/details/gtllpygsck.html

memcpy(dst, src, n);
来源：http://dali.jiagoushi.top/Article/details/gtcmvafmjp.html

[S26] C：内存清零
来源：http://dali.yanxiufei.cn/Article/details/gtfexwaawp.html

memset(a, 0, sizeof a);
来源：http://dali.0kj1m.cn/Article/details/gturhhdnbo.html

[S27] C：定义常量
来源：http://dali.xziqi.cn/Article/details/gtvfmsmbcj.html

const double PI = 3.14159;
来源：http://dali.yj202588.top/Article/details/gtryleqrrq.html

[S28] C：静态变量
来源：http://dali.shzxlz.cn/Article/details/gtmjgycjlw.html

static int counter = 0;
来源：http://dali.pycfn.com/Article/details/gtwqisxhyb.html

[S29] C：变参函数
来源：http://dali.zhiwuduotai.top/Article/details/gtoscnrouq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.kuanghao11.cn/Article/details/gtpfnolgli.html

[S30] C：头文件保护
来源：http://dali.sxryk.cn/Article/details/gtuaivigsc.html

#ifndef X_H
来源：http://dali.dianchejie.cn/Article/details/gtrfvnmgnq.html

#define X_H
来源：http://dali.iojbl.cn/Article/details/gtxbqhgepb.html

#endif
来源：http://dali.hywenlv.cn/Article/details/gtuadyukcf.html

[S31] C++：Hello World
来源：http://dali.jianghu66.top/Article/details/gtjppogrit.html

#include <iostream>
来源：http://dali.havefunace.top/Article/details/gtzkgddnsv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gtckfwebhv.html

[S32] C++：字符串
来源：http://dali.yangfankeji.com/Article/details/gtteqbkwwc.html

std::string s = "hi";  s += "!";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzrabovuy.html

[S33] C++：vector 增删
来源：http://dali.yueranfly.top/Article/details/gtgepgseth.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinqigufen.top/Article/details/gtiebtlqqk.html

[S34] C++：遍历 vector
来源：http://dali.yuxming.cn/Article/details/gtgqmbzpjl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tian-w.cn/Article/details/gtrlxzhpqn.html

[S35] C++：map
来源：http://dali.wangshuangyany.cn/Article/details/gtjjlaeltf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gtrafoxjol.html

[S36] C++：unordered_map
来源：http://dali.tian-w.cn/Article/details/gtdgmlvwrc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gtbgrtryjd.html

[S37] C++：set
来源：http://dali.sufxvd.cn/Article/details/gtyfrhpinn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ehwqpu.com/Article/details/gtvkbwwtyl.html

[S38] C++：排序
来源：http://dali.hammf.cn/Article/details/gtnradloui.html

std::sort(v.begin(), v.end());
来源：http://dali.shzxlz.cn/Article/details/gtyavgccwc.html

[S39] C++：自定义比较器排序
来源：http://dali.shangyingyoupin.top/Article/details/gtmkhfdnhf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.aizwys.cn/Article/details/gtrzzgxgyt.html

[S40] C++：查找元素
来源：http://dali.jinqigfzy.top/Article/details/gtijnyfhib.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenlongwang.top/Article/details/gtalmiyeta.html

[S41] C++：类与构造函数
来源：http://dali.zycfv.cn/Article/details/gtfudwvnut.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.redwolf501.top/Article/details/gtjhmlixea.html

[S42] C++：继承与虚函数
来源：http://dali.pycfn.com/Article/details/gtmrbolwqt.html

class B : public Base { public: void f() override {} };
来源：http://dali.dashuyun.cn/Article/details/gtthwnhaim.html

[S43] C++：智能指针
来源：http://dali.jqgfzy.top/Article/details/gtugcekrqz.html

auto p = std::make_unique<int>(5);
来源：http://dali.dashuyun.cn/Article/details/gtqaawkvqq.html

[S44] C++：引用传参
来源：http://dali.cdnleiting.top/Article/details/gtyyghzfsa.html

void inc(int &x) { ++x; }
来源：http://dali.quarkkingdee.top/Article/details/gthmaimjps.html

[S45] C++：lambda
来源：http://dali.sxryk.cn/Article/details/gttqdmynxp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.quarkkingdee.top/Article/details/gtkjrghgoh.html

[S46] C++：函数模板
来源：http://dali.dianchejie.cn/Article/details/gtdsmrfigt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hongshengwenyu.top/Article/details/gthxzueqqt.html

[S47] C++：结构化绑定遍历
来源：http://dali.chenlongwang.top/Article/details/gtvwtxeozm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.andypj.xyz/Article/details/gtxufgdxkl.html

[S48] C++：逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gtldngefvr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.havefunace.top/Article/details/gtucflplrv.html

while (std::getline(in, line)) { }
来源：http://dali.hfpthk.cn/Article/details/gtmohteqox.html

[S49] C++：写文件
来源：http://dali.hnxiangtu.top/Article/details/gtyjnqeyry.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yvedp.cn/Article/details/gtfjnwqgbz.html

[S50] C++：格式化数字
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiliusrzh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gzhubu.top/Article/details/gtcbuniclq.html

[S51] C++：显式类型转换
来源：http://dali.zycfv.cn/Article/details/gtnqcrbgxp.html

static_cast<double>(a) / b
来源：http://dali.haohaochexian.top/Article/details/gtnuoozldz.html

[S52] C++：const 与 noexcept
来源：http://dali.haohaochexian.top/Article/details/gtwrsqlgwx.html

int size() const noexcept { return n_; }
来源：http://dali.9152youxi.cn/Article/details/gtfsyuaosc.html

[S53] C++：移动语义
来源：http://dali.shanyushiyangtech.top/Article/details/gtsmlmdlab.html

std::vector<int> w = std::move(v);
来源：http://dali.ydzc1.top/Article/details/gtulzyaccs.html

[S54] C++：异常处理
来源：http://dali.dianchejie.cn/Article/details/gtzvgexpmo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gotoacloud.top/Article/details/gtccmgsipr.html

[S55] C++：结构化绑定
来源：http://dali.ydzc1.top/Article/details/gtvdxmeyem.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.andypj.xyz/Article/details/gtmswnlsiw.html

[S56] C++：optional
来源：http://dali.zycfv.cn/Article/details/gtzwagzfft.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.chenzaomai.com/Article/details/gtkckbrsfb.html

[S57] C++：编译期常量
来源：http://dali.ivvv.top/Article/details/gtopncmkcr.html

constexpr int N = 10;
来源：http://dali.hnxiangtu.top/Article/details/gtywozffiz.html

[S58] C++：命名空间
来源：http://dali.nanxinkj.top/Article/details/gtzzvavsan.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj202588.top/Article/details/gtkxvdgxbh.html

[S59] C++：静态断言
来源：http://dali.nanxinkj.top/Article/details/gtvlscxdti.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jianghu66.top/Article/details/gtrtlofash.html

[S60] C++：遍历并删除元素
来源：http://dali.nanxinkj.top/Article/details/gtfytwxfas.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hnxiangtu.top/Article/details/gtzvoedoqb.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtfbpmiidw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tianlin.xyz/Article/details/gtvpcykavw.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtgvspnvra.html

[T01] Kotlin：Hello World
来源：http://dali.guannengcc.top/Article/details/gtvcvhpjex.html

println("Hello")
来源：http://dali.9152youxi.cn/Article/details/gtrnwoyzlp.html

[T02] Kotlin：变量
来源：http://dali.zdqjudy.top/Article/details/gtnauutjvd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.redwolf501.top/Article/details/gtmrcjdmdz.html

[T03] Kotlin：字符串模板
来源：http://dali.pengpengdd.cyou/Article/details/gtxuceyzfe.html

"值: $b"
来源：http://dali.sysykeji.top/Article/details/gtjheqxwyk.html

[T04] Kotlin：空安全
来源：http://dali.jinqigfzy.top/Article/details/gtzakgoqku.html

val n: String? = null;  n?.length
来源：http://dali.iojbl.cn/Article/details/gtisogzpui.html

[T05] Kotlin：when 表达式
来源：http://dali.zhoulong.xyz/Article/details/gtveohkgaq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ydzc1.top/Article/details/gtfnnasaey.html

[T06] Kotlin：集合映射
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxnhvteua.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.0kj1m.cn/Article/details/gtnasevtee.html

[T07] Kotlin：集合过滤
来源：http://dali.cqqwz.cn/Article/details/gtggybrwvk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ehwqpu.com/Article/details/gtvrdhjgwc.html

[T08] Kotlin：数据类
来源：http://dali.xuanzx.com/Article/details/gtdlbtixtp.html

data class User(val name: String, val age: Int)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlydurexv.html

[T09] Kotlin：扩展函数
来源：http://dali.sweek.top/Article/details/gthxkcyadc.html

fun String.exclaim() = this + "!"
来源：http://dali.redwolf501.top/Article/details/gtsjmtaztl.html

[T10] Kotlin：默认参数
来源：http://dali.yj20258.top/Article/details/gttnfehljz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yangfankeji.com/Article/details/gtxthrpier.html

[T11] Kotlin：协程
来源：http://dali.yonumen.top/Article/details/gtwjugsxug.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgmhleizl.html

[T12] Kotlin：解构声明
来源：http://dali.9152youxi.cn/Article/details/gttglqdqbj.html

val (a, b) = Pair(1, 2)
来源：http://dali.svipenyu.cn/Article/details/gtucodcrey.html

[T13] Kotlin：只读 Map
来源：http://dali.dianchejie.cn/Article/details/gtihoalctu.html

val m = mapOf("a" to 1)
来源：http://dali.dianchejie.cn/Article/details/gtnmrxocnj.html

[T14] Kotlin：循环
来源：http://dali.c1oappe.top/Article/details/gtnawuootq.html

for (i in 1..10) println(i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtshdtdktk.html

[T15] Kotlin：接口
来源：http://dali.gogol.net.cn/Article/details/gtjjqxtinh.html

interface Shape { fun area(): Double }
来源：http://dali.sysykeji.top/Article/details/gtkoycckua.html

[T16] Swift：Hello World
来源：http://dali.guannengcc.top/Article/details/gtfhptnkoi.html

print("Hello")
来源：http://dali.guowangkeji.top/Article/details/gtwzakksab.html

[T17] Swift：变量与常量
来源：http://dali.birdmap.top/Article/details/gtcfvgszul.html

var a = 1;  let b = 2
来源：http://dali.fzhhl.top/Article/details/gtpgyntvds.html

[T18] Swift：字符串插值
来源：http://dali.yj202588.top/Article/details/gtjravtlbl.html

"值: \(b)"
来源：http://dali.zdqjudy.top/Article/details/gtwaoyrmlx.html

[T19] Swift：可选绑定
来源：http://dali.yuxming.cn/Article/details/gtzcmyrnmj.html

if let n = opt { print(n) }
来源：http://dali.vqdsnc.cn/Article/details/gtdpwzqttj.html

[T20] Swift：数组操作
来源：http://dali.316326.xyz/Article/details/gtktcunsbn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxohrprta.html

[T21] Swift：遍历
来源：http://dali.xylfe.cn/Article/details/gtrcgbdseo.html

for x in a { print(x) }
来源：http://dali.aibaodan.cn/Article/details/gtdsxyquvy.html

[T22] Swift：字典
来源：http://dali.chenzaomai.com/Article/details/gtfqlccxls.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gzhubu.top/Article/details/gtqerwzpgy.html

[T23] Swift：函数
来源：http://dali.pengpengdd.cyou/Article/details/gtovfzmbwg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhixingplan.top/Article/details/gtjstbpxcr.html

[T24] Swift：闭包
来源：http://dali.yuanzhike.top/Article/details/gtwuhpiwnp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hnqzz.top/Article/details/gtuutvrsib.html

[T25] Swift：结构体
来源：http://dali.iojbl.cn/Article/details/gtjjjhbwqa.html

struct P { var x: Int }
来源：http://dali.fzhhl.top/Article/details/gtboesqsof.html

[T26] Swift：类与重写
来源：http://dali.c1oappe.top/Article/details/gtcexhrtyk.html

class A: Base { override func f() {} }
来源：http://dali.hnxiangtu.top/Article/details/gthggninxz.html

[T27] Swift：错误处理
来源：http://dali.yueranfly.top/Article/details/gtdxadtpjr.html

do { try f() } catch { print(error) }
来源：http://dali.gaohongyu789.top/Article/details/gtydjtvlst.html

[T28] Swift：枚举
来源：http://dali.jinqigfzy.top/Article/details/gtroqqrwcf.html

enum Color { case red, green }
来源：http://dali.jinghuilouyu.cn/Article/details/gtphperpjk.html

[T29] Swift：guard 提前返回
来源：http://dali.cheryme.top/Article/details/gthjowywgk.html

guard let x = opt else { return }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwjpvuxcr.html

[T30] Swift：协议
来源：http://dali.sweek.top/Article/details/gtmeuoypdq.html

protocol Shape { func area() -> Double }
来源：http://dali.gotoacloud.top/Article/details/gtrikrkdaa.html

[T31] Lua：Hello World
来源：http://dali.chenlongwang.top/Article/details/gthwivjvma.html

print("Hello")
来源：http://dali.yongpay.top/Article/details/gtyyvcswcl.html

[T32] Lua：局部变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbdkmcumf.html

local a = 1
来源：http://dali.yangfankeji.com/Article/details/gttskzuzml.html

[T33] Lua：表（数组）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlocxcifk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgleclngv.html

[T34] Lua：遍历表
来源：http://dali.svipenyu.cn/Article/details/gtwcextmim.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yonumen.top/Article/details/gtqpacszrs.html

[T35] Lua：字典表
来源：http://dali.xylfe.cn/Article/details/gtevwgappl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.chenzaomai.com/Article/details/gtynfwxuhv.html

[T36] Lua：函数
来源：http://dali.hnxiangtu.top/Article/details/gtjsedbjwv.html

function add(a, b) return a + b end
来源：http://dali.yuxming.cn/Article/details/gtwrpwspbn.html

[T37] Lua：字符串拼接
来源：http://dali.shanyushiyangtech.top/Article/details/gtcyzmrxkj.html

"a" .. "b"
来源：http://dali.hongshengwenyu.top/Article/details/gtqddmympw.html

[T38] Lua：条件
来源：http://dali.zhoulong.xyz/Article/details/gtktsfhdxm.html

if x > 0 then print("正") end
来源：http://dali.316326.xyz/Article/details/gtggzdqcoc.html

[T39] Lua：模式匹配
来源：http://dali.bjfxy.top/Article/details/gtlxpimeyg.html

string.find(s, "%d+")
来源：http://dali.meibo888.top/Article/details/gtpohuhpel.html

[T40] Lua：元表
来源：http://dali.jyoumei.cn/Article/details/gtbunbjsrg.html

setmetatable({}, { __index = base })
来源：http://dali.jyoumei.cn/Article/details/gtxzwufgui.html

[T41] Perl：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtcamlwnmv.html

print "Hello\n";
来源：http://dali.zhoulong.xyz/Article/details/gtajhihiun.html

[T42] Perl：变量类型
来源：http://dali.andypj.xyz/Article/details/gtqudrbmen.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.tanke756.top/Article/details/gtqrnkhnzc.html

[T43] Perl：字符串插值
来源：http://dali.kuanghao11.cn/Article/details/gthougxxef.html

"值: $a"
来源：http://dali.gzhubu.top/Article/details/gtomxxxebn.html

[T44] Perl：条件
来源：http://dali.fengsongda.top/Article/details/gtvfgbhiui.html

if ($a > 0) { print "正"; }
来源：http://dali.zhoulong.xyz/Article/details/gtmjsbbghm.html

[T45] Perl：数组遍历
来源：http://dali.zhixingplan.top/Article/details/gtpcbgyydj.html

for my $x (@arr) { print $x; }
来源：http://dali.cdnleiting.top/Article/details/gtgwhddlwx.html

[T46] Perl：哈希操作
来源：http://dali.yangfankeji.com/Article/details/gtjtncocgz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jqgfzy.top/Article/details/gtcvzsfexg.html

[T47] Perl：正则捕获
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzbdsczoi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.chenlongwang.top/Article/details/gtppnqnwie.html

[T48] Perl：正则替换
来源：http://dali.zdqjudy.top/Article/details/gtpneotmst.html

$s =~ s/old/new/g;
来源：http://dali.yueranfly.top/Article/details/gtawlzsiwo.html

[T49] Perl：函数
来源：http://dali.dashuyun.cn/Article/details/gtzklmwhaf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.pycfn.com/Article/details/gteoqxwmuq.html

[T50] Perl：逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gttbjcawgi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xinyue.icu/Article/details/gtsszhfztk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jiagoushi.top/Article/details/gtoipttwwt.html

[T51] Scala：Hello World
来源：http://dali.xziqi.cn/Article/details/gtexnyrink.html

println("Hello")
来源：http://dali.guowangkeji.top/Article/details/gtofkgmakx.html

[T52] Scala：变量
来源：http://dali.yueranfly.top/Article/details/gtlnebyuhr.html

val a = 1;  var b = 2
来源：http://dali.birdmap.top/Article/details/gtzziqvfdp.html

[T53] Scala：字符串插值
来源：http://dali.9152youxi.cn/Article/details/gtcucfstcz.html

s"值: $b"
来源：http://dali.guowangkeji.top/Article/details/gteiqilvyx.html

[T54] Scala：集合映射
来源：http://dali.andypj.xyz/Article/details/gtwaptxwep.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gogol.net.cn/Article/details/gtithnrzbm.html

[T55] Scala：集合过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtpybcpfwq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ppjwa.cn/Article/details/gtzgnokbpx.html

[T56] Scala：样例类
来源：http://dali.havefunace.top/Article/details/gtnmgzcbga.html

case class User(name: String, age: Int)
来源：http://dali.yvedp.cn/Article/details/gtkexmfnna.html

[T57] Scala：模式匹配
来源：http://dali.jianghu66.top/Article/details/gtxqslxavc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.pycfn.com/Article/details/gtssswrslu.html

[T58] Scala：函数定义
来源：http://dali.hnqzz.top/Article/details/gterktnflf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.smart0.xyz/Article/details/gtlykjdiej.html

[T59] Scala：循环
来源：http://dali.9152youxi.cn/Article/details/gtrfzwhsgv.html

for (i <- 1 to 10) println(i)
来源：http://dali.xinyue.icu/Article/details/gthbdopifg.html

[T60] Scala：折叠
来源：http://dali.cashguo.top/Article/details/gtlzfbtvfg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gzhubu.top/Article/details/gtkwhsbjhz.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtzomlgvuq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.birdmap.top/Article/details/gtyhbypcth.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtpfeafqwg.html

[U01] Py：创建虚拟环境
来源：http://dali.sufxvd.cn/Article/details/gtzvcwycgz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zycfv.cn/Article/details/gtfzksvpqz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yuxming.cn/Article/details/gtlriydmwa.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yvedp.cn/Article/details/gtvzvhybsz.html

[U03] Py：加载 .env 配置
来源：http://dali.xziqi.cn/Article/details/gtnlcrcuwq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.svipenyu.cn/Article/details/gtztsrvecu.html

[U04] Py：变量调试打印
来源：http://dali.cdnleiting.top/Article/details/gttguffrcc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yangfankeji.com/Article/details/gtvzdhwvno.html

[U05] Py：列表去重且保序
来源：http://dali.aibaodan.cn/Article/details/gtbkkfuowv.html

list(dict.fromkeys(arr))
来源：http://dali.jlsjyb.cn/Article/details/gtftzdttrk.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gtcxgbtaad.html

{**a, **b}
来源：http://dali.zhongyouzk.top/Article/details/gttqyvukvj.html

[U07] Py：反转字典键值
来源：http://dali.hnxiangtu.top/Article/details/gtjssovfbt.html

{v: k for k, v in d.items()}
来源：http://dali.cashguo.top/Article/details/gtxutuveaz.html

[U08] Py：展平二维列表
来源：http://dali.pycfn.com/Article/details/gthjkigkcq.html

[y for x in nested for y in x]
来源：http://dali.guannengcc.top/Article/details/gtlsggedxm.html

[U09] Py：字典取最大值的键
来源：http://dali.yvedp.cn/Article/details/gtnliwrwct.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gtbvppxtyj.html

[U10] Py：按值排序字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnmvjyczw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jiagoushi.top/Article/details/gtkxwdqmrj.html

[U11] Py：生成器表达式
来源：http://dali.xuetiantiany.cn/Article/details/gtemswswhw.html

(x * 2 for x in arr)
来源：http://dali.yongpay.top/Article/details/gtmyvrajcf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.bjfxy.top/Article/details/gtexbpxhev.html

Counter(arr).most_common(3)
来源：http://dali.jlsjyb.cn/Article/details/gtkwoptzzs.html

[U13] Py：固定长度队列
来源：http://dali.guannengcc.top/Article/details/gturrbpaat.html

deque(maxlen=10)
来源：http://dali.316326.xyz/Article/details/gtyffjcktz.html

[U14] Py：分组收集到列表
来源：http://dali.zhengqikj.top/Article/details/gtphadtsxj.html

defaultdict(list)
来源：http://dali.ivvv.top/Article/details/gttuhcvkor.html


<!-- 参考信息 -->