代发 wailian999

export PATH="$HOME/bin:$PATH"
来源：http://dali.iojbl.cn/Article/details/gt2iohyentj.html

[R76] 使用临时文件
来源：http://dali.gogol.net.cn/Article/details/gt2esedcrqb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rtdyzcxt.html

[R77] 读取用户输入
来源：http://dali.jinqigfzy.top/Article/details/gt2bpukhehi.html

read -rp "请输入: " ans
来源：http://dali.jqgfzy.top/Article/details/gt2kkdxvwbt.html

[R78] 交互式菜单
来源：http://dali.zhixingplan.top/Article/details/gt2hcfitpwt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.daria6918.cn/Article/details/gt2inwoaskn.html

[R79] 解析命令行选项
来源：http://dali.zhengqikj.top/Article/details/gt2zpeggnkc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hammf.cn/Article/details/gt2emzocpxx.html

[R80] 查看脚本执行耗时
来源：http://dali.c1oappe.top/Article/details/gt2rkqagdhc.html

time ./run.sh
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uqprzhhg.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2sulwzbre.html

S. C / C++ 专题
来源：http://dali.feifeiyinyue.top/Article/details/gt2duzqlfnd.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2ntmncmyq.html

[S01] C：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gt2gizoksob.html

#include <stdio.h>
来源：http://dali.sweek.top/Article/details/gt2mcfrbxob.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2eavfddir.html

[S02] C：变量与格式化输出
来源：http://dali.ybcxt.top/Article/details/gt2htlvskcv.html

int a = 10; printf("%d\n", a);
来源：http://dali.tian-w.cn/Article/details/gt2wnxpnmmn.html

[S03] C：读入整数
来源：http://dali.chenlongwang.top/Article/details/gt2frobpdcv.html

int x; scanf("%d", &x);
来源：http://dali.quarkkingdee.top/Article/details/gt2ubpkekqb.html

[S04] C：字符串复制
来源：http://dali.dianchejie.cn/Article/details/gt2ozdshpqk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.guowangkeji.top/Article/details/gt2oesklsam.html

[S05] C：字符串长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qybuuyti.html

strlen(s)
来源：http://dali.fengsongda.top/Article/details/gt2ambnavrg.html

[S06] C：字符串比较
来源：http://dali.fzhhl.top/Article/details/gt2cuberyys.html

strcmp(a, b) == 0
来源：http://dali.tian-w.cn/Article/details/gt2jubqjlzl.html

[S07] C：数组遍历求和
来源：http://dali.cdnleiting.top/Article/details/gt2acftpcoo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhixingplan.top/Article/details/gt2ortlgddi.html

[S08] C：动态内存分配与释放
来源：http://dali.ppjwa.cn/Article/details/gt2vbnammck.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hnxiangtu.top/Article/details/gt2tmufzkju.html

[S09] C：结构体定义与初始化
来源：http://dali.jianghu66.top/Article/details/gt2kgkgjhgg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nanxinkj.top/Article/details/gt2qdawzjdg.html

[S10] C：指针与解引用
来源：http://dali.ehwqpu.com/Article/details/gt2kcbbsqbu.html

int *p = &a;  *p = 5;
来源：http://dali.tianlin.xyz/Article/details/gt2ednpyqgg.html

[S11] C：逐行读文件
来源：http://dali.birdmap.top/Article/details/gt2gzvzrkcv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.dashuyun.cn/Article/details/gt2jxpevfmm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj20258888.top/Article/details/gt2hlxmxrrf.html

fclose(f);
来源：http://dali.shangyingyoupin.top/Article/details/gt2gaxjegfj.html

[S12] C：写文件
来源：http://dali.jlsjyb.cn/Article/details/gt2qqvijsxx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hnxiangtu.top/Article/details/gt2yofjsofl.html

[S13] C：宏定义
来源：http://dali.bjfxy.top/Article/details/gt2qifytedb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.bjfxy.top/Article/details/gt2leptycfq.html

[S14] C：枚举
来源：http://dali.iojbl.cn/Article/details/gt2aadekxkv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.wangshuangyany.cn/Article/details/gt2bgehfnix.html

[S15] C：类型转换
来源：http://dali.ehwqpu.com/Article/details/gt2ufknsbjo.html

(double) a / b
来源：http://dali.andypj.xyz/Article/details/gt2ifgvhges.html

[S16] C：位操作置位
来源：http://dali.shuidangran.top/Article/details/gt2vnceowbu.html

x |= (1 << 3);
来源：http://dali.chenzaomai.com/Article/details/gt2poelyywl.html

[S17] C：安全拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2pwapbuts.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daria6918.cn/Article/details/gt2pzqnbqxa.html

[S18] C：命令行参数
来源：http://dali.birdmap.top/Article/details/gt2wvuqhxaw.html

int main(int argc, char **argv)
来源：http://dali.tian-w.cn/Article/details/gt2yvwmtwtb.html

[S19] C：快速排序
来源：http://dali.zhongyouzk.top/Article/details/gt2ntrgoobs.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.dashuyun.cn/Article/details/gt2xyvcgvjy.html

[S20] C：二分查找
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wakzxorq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.mhx1999.top/Article/details/gt2djrrnilb.html

[S21] C：字符类别判断
来源：http://dali.yvedp.cn/Article/details/gt2qnxrsaib.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.iojbl.cn/Article/details/gt2sxcdmody.html

[S22] C：字符串转数字
来源：http://dali.hywenlv.cn/Article/details/gt2zrnfdurh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cheryme.top/Article/details/gt2ccedbgzd.html

[S23] C：随机数
来源：http://dali.haohaochexian.top/Article/details/gt2jalbdjzc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jqgfzy.top/Article/details/gt2cshkjeew.html

[S24] C：获取本地时间
来源：http://dali.cdnleiting.top/Article/details/gt2lzucmntc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.dianchejie.cn/Article/details/gt2bfyeisne.html

[S25] C：内存拷贝
来源：http://dali.tanke756.top/Article/details/gt2sbcmalhn.html

memcpy(dst, src, n);
来源：http://dali.hnqzz.top/Article/details/gt2rdddmouy.html

[S26] C：内存清零
来源：http://dali.feifeiyinyue.top/Article/details/gt2nhjnhhit.html

memset(a, 0, sizeof a);
来源：http://dali.cdnleiting.top/Article/details/gt2elxvrttt.html

[S27] C：定义常量
来源：http://dali.aibaodan.cn/Article/details/gt2qazabzxj.html

const double PI = 3.14159;
来源：http://dali.daria6918.cn/Article/details/gt2hlcjodze.html

[S28] C：静态变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2euwddllm.html

static int counter = 0;
来源：http://dali.jinqigfzy.top/Article/details/gt2zzhprdft.html

[S29] C：变参函数
来源：http://dali.sxryk.cn/Article/details/gt2irxsbkph.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yvedp.cn/Article/details/gt2ezuljyjp.html

[S30] C：头文件保护
来源：http://dali.haohaochexian.top/Article/details/gt2srvesfvc.html

#ifndef X_H
来源：http://dali.quarkkingdee.top/Article/details/gt2qgblxhoo.html

#define X_H
来源：http://dali.jinqigfzy.top/Article/details/gt2snhwyzot.html

#endif
来源：http://dali.vqdsnc.cn/Article/details/gt2spbqmegz.html

[S31] C++：Hello World
来源：http://dali.dianchejie.cn/Article/details/gt2jtmxqfaw.html

#include <iostream>
来源：http://dali.yanxiufei.cn/Article/details/gt2ivtngsxo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.wangdashe.top/Article/details/gt2gplcfaza.html

[S32] C++：字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2dkcagwfm.html

std::string s = "hi";  s += "!";
来源：http://dali.xinyue.icu/Article/details/gt2snmpcgku.html

[S33] C++：vector 增删
来源：http://dali.zhixingplan.top/Article/details/gt2pmjctpmm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xziqi.cn/Article/details/gt2dsbqlrqr.html

[S34] C++：遍历 vector
来源：http://dali.nanxinkj.top/Article/details/gt2yupbmmrd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ujbktndu.html

[S35] C++：map
来源：http://dali.yj20258888.top/Article/details/gt2etmlnugb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hammf.cn/Article/details/gt2wshlmofp.html

[S36] C++：unordered_map
来源：http://dali.feifeiyinyue.top/Article/details/gt2geazatnk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gt2jqfddmwg.html

[S37] C++：set
来源：http://dali.meibo888.top/Article/details/gt2lqussiad.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.fengsongda.top/Article/details/gt2ypzjwhfj.html

[S38] C++：排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ugoviotc.html

std::sort(v.begin(), v.end());
来源：http://dali.guowangkeji.top/Article/details/gt2hgdovbjz.html

[S39] C++：自定义比较器排序
来源：http://dali.yuanzhike.top/Article/details/gt2xefrlpbq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.svipenyu.cn/Article/details/gt2afrevjpw.html

[S40] C++：查找元素
来源：http://dali.mhx1999.top/Article/details/gt2khixqzwy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cdnleiting.top/Article/details/gt2yfhqlxvb.html

[S41] C++：类与构造函数
来源：http://dali.jlsjyb.cn/Article/details/gt2nnihbxae.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yj20258888.top/Article/details/gt2dshzbcem.html

[S42] C++：继承与虚函数
来源：http://dali.daria6918.cn/Article/details/gt2kxyjxhuu.html

class B : public Base { public: void f() override {} };
来源：http://dali.aizwys.cn/Article/details/gt2ssbimoxl.html

[S43] C++：智能指针
来源：http://dali.gotoacloud.top/Article/details/gt2afslejbd.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pcvejiyg.html

[S44] C++：引用传参
来源：http://dali.zhiwuduotai.top/Article/details/gt2ijsygkuh.html

void inc(int &x) { ++x; }
来源：http://dali.cashguo.top/Article/details/gt2udvclwfx.html

[S45] C++：lambda
来源：http://dali.jiagoushi.top/Article/details/gt2eaucffkx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinqigufen.top/Article/details/gt2rkdkzvhw.html

[S46] C++：函数模板
来源：http://dali.aizwys.cn/Article/details/gt2eqwcykai.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.iojbl.cn/Article/details/gt2mmwzhbap.html

[S47] C++：结构化绑定遍历
来源：http://dali.jiagoushi.top/Article/details/gt2xwiobykb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.quarkkingdee.top/Article/details/gt2jnuvxcoc.html

[S48] C++：逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2mudlfoin.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yongpay.top/Article/details/gt2vxlveszz.html

while (std::getline(in, line)) { }
来源：http://dali.yuanzhike.top/Article/details/gt2snjhyptw.html

[S49] C++：写文件
来源：http://dali.yj20258.top/Article/details/gt2ezrlasqe.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jiagoushi.top/Article/details/gt2rlxizwzv.html

[S50] C++：格式化数字
来源：http://dali.fengsongda.top/Article/details/gt2zdbxymoo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tanke756.top/Article/details/gt2ojgjhvxo.html

[S51] C++：显式类型转换
来源：http://dali.sufxvd.cn/Article/details/gt2qqtpskmp.html

static_cast<double>(a) / b
来源：http://dali.vqdsnc.cn/Article/details/gt2kdmpegft.html

[S52] C++：const 与 noexcept
来源：http://dali.yanxiufei.cn/Article/details/gt2asagespr.html

int size() const noexcept { return n_; }
来源：http://dali.cdnleiting.top/Article/details/gt2ddkqvkrx.html

[S53] C++：移动语义
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2urguluzq.html

std::vector<int> w = std::move(v);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kblviykk.html

[S54] C++：异常处理
来源：http://dali.jqgfzy.top/Article/details/gt2wrldiqsb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tian-w.cn/Article/details/gt2weasqenk.html

[S55] C++：结构化绑定
来源：http://dali.zycfv.cn/Article/details/gt2fuudcwtp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zszclbyt.html

[S56] C++：optional
来源：http://dali.dianchejie.cn/Article/details/gt2pfcgjvul.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.svipenyu.cn/Article/details/gt2qevvcufw.html

[S57] C++：编译期常量
来源：http://dali.zhiwuduotai.top/Article/details/gt2mdgxxwbb.html

constexpr int N = 10;
来源：http://dali.yueranfly.top/Article/details/gt2utsjkrvq.html

[S58] C++：命名空间
来源：http://dali.vqdsnc.cn/Article/details/gt2oubtvlzp.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhengqikj.top/Article/details/gt2eprxegsb.html

[S59] C++：静态断言
来源：http://dali.hnqzz.top/Article/details/gt2fsogipwj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tian-w.cn/Article/details/gt2bckgunpo.html

[S60] C++：遍历并删除元素
来源：http://dali.zhixingplan.top/Article/details/gt2psjvatfh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.c1oappe.top/Article/details/gt2fyxnjbfe.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2bhbniklt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhiwuduotai.top/Article/details/gt2dsmjofvm.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2pgpkdjfo.html

[T01] Kotlin：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gt2spenvmuz.html

println("Hello")
来源：http://dali.c1oappe.top/Article/details/gt2mgfpijyh.html

[T02] Kotlin：变量
来源：http://dali.dashuyun.cn/Article/details/gt2umpgplwl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ybcxt.top/Article/details/gt2jqyhblji.html

[T03] Kotlin：字符串模板
来源：http://dali.daria6918.cn/Article/details/gt2swlkerva.html

"值: $b"
来源：http://dali.shzxlz.cn/Article/details/gt2iwnmnksu.html

[T04] Kotlin：空安全
来源：http://dali.xziqi.cn/Article/details/gt2dyfkadwu.html

val n: String? = null;  n?.length
来源：http://dali.wangdashe.top/Article/details/gt2xhobaonc.html

[T05] Kotlin：when 表达式
来源：http://dali.hfpthk.cn/Article/details/gt2opgwluok.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tanke756.top/Article/details/gt2jjxkgomg.html

[T06] Kotlin：集合映射
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2efvvrfjm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sweek.top/Article/details/gt2gmtdeope.html

[T07] Kotlin：集合过滤
来源：http://dali.kuanghao11.cn/Article/details/gt2imjbnnyr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.guowangkeji.top/Article/details/gt2ccintrig.html

[T08] Kotlin：数据类
来源：http://dali.hfpthk.cn/Article/details/gt2niqkhjgy.html

data class User(val name: String, val age: Int)
来源：http://dali.snrcjt.cn/Article/details/gt2iweqbipx.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgdfalz.html

fun String.exclaim() = this + "!"
来源：http://dali.zhengqikj.top/Article/details/gt2lponweef.html

[T10] Kotlin：默认参数
来源：http://dali.yangfankeji.com/Article/details/gt2nrzwxwhu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yonumen.top/Article/details/gt2onpyrabn.html

[T11] Kotlin：协程
来源：http://dali.yuxming.cn/Article/details/gt2zduyfobt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yangfankeji.com/Article/details/gt2kfyoaqbq.html

[T12] Kotlin：解构声明
来源：http://dali.chenzaomai.com/Article/details/gt2nlqicdop.html

val (a, b) = Pair(1, 2)
来源：http://dali.sxryk.cn/Article/details/gt2pqizcnvy.html

[T13] Kotlin：只读 Map
来源：http://dali.gogol.net.cn/Article/details/gt2rpwlxlaa.html

val m = mapOf("a" to 1)
来源：http://dali.redwolf501.top/Article/details/gt2xjdxdhcm.html

[T14] Kotlin：循环
来源：http://dali.hongshengwenyu.top/Article/details/gt2pkiinmwg.html

for (i in 1..10) println(i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fkswvmcv.html

[T15] Kotlin：接口
来源：http://dali.bjfxy.top/Article/details/gt2gupnfegg.html

interface Shape { fun area(): Double }
来源：http://dali.chenlongwang.top/Article/details/gt2litskngw.html

[T16] Swift：Hello World
来源：http://dali.tanke756.top/Article/details/gt2yxmyqqcf.html

print("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gt2jhbjuibl.html

[T17] Swift：变量与常量
来源：http://dali.xuanzx.com/Article/details/gt2ximvaplv.html

var a = 1;  let b = 2
来源：http://dali.havefunace.top/Article/details/gt2jhgyplyc.html

[T18] Swift：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gt2kcyvoqgx.html

"值: \(b)"
来源：http://dali.yj20258888.top/Article/details/gt2mgdofcic.html

[T19] Swift：可选绑定
来源：http://dali.wangshuangyany.cn/Article/details/gt2rlhiplmy.html

if let n = opt { print(n) }
来源：http://dali.jyoumei.cn/Article/details/gt2eyufenem.html

[T20] Swift：数组操作
来源：http://dali.guannengcc.top/Article/details/gt2lcjepoun.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhengqikj.top/Article/details/gt2tbeghqdt.html

[T21] Swift：遍历
来源：http://dali.yonumen.top/Article/details/gt2aacqcvll.html

for x in a { print(x) }
来源：http://dali.andypj.xyz/Article/details/gt2jzdaqiar.html

[T22] Swift：字典
来源：http://dali.ehwqpu.com/Article/details/gt2unnsgvbb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shuidangran.top/Article/details/gt2nharxslk.html

[T23] Swift：函数
来源：http://dali.xziqi.cn/Article/details/gt2zagtokpx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gotoacloud.top/Article/details/gt2uvzrhtme.html

[T24] Swift：闭包
来源：http://dali.jqgfzy.top/Article/details/gt2azhjlvpz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sweek.top/Article/details/gt2zlihpiiv.html

[T25] Swift：结构体
来源：http://dali.quarkkingdee.top/Article/details/gt2mavgfgrg.html

struct P { var x: Int }
来源：http://dali.snrcjt.cn/Article/details/gt2lhwjqgfp.html

[T26] Swift：类与重写
来源：http://dali.aizwys.cn/Article/details/gt2ncbqcekl.html

class A: Base { override func f() {} }
来源：http://dali.xuanzx.com/Article/details/gt2frlaekcg.html

[T27] Swift：错误处理
来源：http://dali.jlsjyb.cn/Article/details/gt2abemimsu.html

do { try f() } catch { print(error) }
来源：http://dali.vqdsnc.cn/Article/details/gt2hlsrvizf.html

[T28] Swift：枚举
来源：http://dali.jiagoushi.top/Article/details/gt2dmxhxbhx.html

enum Color { case red, green }
来源：http://dali.yvedp.cn/Article/details/gt2nosasyqo.html

[T29] Swift：guard 提前返回
来源：http://dali.nanxinkj.top/Article/details/gt2otacichx.html

guard let x = opt else { return }
来源：http://dali.tanke756.top/Article/details/gt2aedomfav.html

[T30] Swift：协议
来源：http://dali.tianlin.xyz/Article/details/gt2fqsrowvk.html

protocol Shape { func area() -> Double }
来源：http://dali.mhx1999.top/Article/details/gt2vytezlsp.html

[T31] Lua：Hello World
来源：http://dali.shzxlz.cn/Article/details/gt2qgmxweez.html

print("Hello")
来源：http://dali.aizwys.cn/Article/details/gt2qvcbjyya.html

[T32] Lua：局部变量
来源：http://dali.hywenlv.cn/Article/details/gt2wgughphw.html

local a = 1
来源：http://dali.yj20258888.top/Article/details/gt2tstgfqsr.html

[T33] Lua：表（数组）
来源：http://dali.zhiwuduotai.top/Article/details/gt2bnpiqyxy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hnxiangtu.top/Article/details/gt2qzftybwq.html

[T34] Lua：遍历表
来源：http://dali.hywenlv.cn/Article/details/gt2vtwwfpcm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.redwolf501.top/Article/details/gt2ertktrlc.html

[T35] Lua：字典表
来源：http://dali.haohaochexian.top/Article/details/gt2xwuyihiu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhongyouzk.top/Article/details/gt2qcmouams.html

[T36] Lua：函数
来源：http://dali.gaohongyu789.top/Article/details/gt2rjbmbevp.html

function add(a, b) return a + b end
来源：http://dali.quarkkingdee.top/Article/details/gt2bkpqgqjl.html

[T37] Lua：字符串拼接
来源：http://dali.hammf.cn/Article/details/gt2qocannis.html

"a" .. "b"
来源：http://dali.yuxming.cn/Article/details/gt2tegsmfme.html

[T38] Lua：条件
来源：http://dali.xuanzx.com/Article/details/gt2htpvymig.html

if x > 0 then print("正") end
来源：http://dali.sxryk.cn/Article/details/gt2druesvrw.html

[T39] Lua：模式匹配
来源：http://dali.yueranfly.top/Article/details/gt2declqjkw.html

string.find(s, "%d+")
来源：http://dali.andypj.xyz/Article/details/gt2ryirkelt.html

[T40] Lua：元表
来源：http://dali.c1oappe.top/Article/details/gt2nceycmbf.html

setmetatable({}, { __index = base })
来源：http://dali.mhx1999.top/Article/details/gt2oavbkdwe.html

[T41] Perl：Hello World
来源：http://dali.yonumen.top/Article/details/gt2ivevdqhb.html

print "Hello\n";
来源：http://dali.chenzaomai.com/Article/details/gt2fgbecpno.html

[T42] Perl：变量类型
来源：http://dali.aibaodan.cn/Article/details/gt2kmojfmca.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ivvv.top/Article/details/gt2rvwmetcr.html

[T43] Perl：字符串插值
来源：http://dali.zycfv.cn/Article/details/gt2lugvjzqp.html

"值: $a"
来源：http://dali.tianlin.xyz/Article/details/gt2qwcxiioq.html

[T44] Perl：条件
来源：http://dali.daria6918.cn/Article/details/gt2udcjooct.html

if ($a > 0) { print "正"; }
来源：http://dali.smart0.xyz/Article/details/gt2dheeovhf.html

[T45] Perl：数组遍历
来源：http://dali.pycfn.com/Article/details/gt2dmjcvzzc.html

for my $x (@arr) { print $x; }
来源：http://dali.zhixingplan.top/Article/details/gt2uspwyfar.html

[T46] Perl：哈希操作
来源：http://dali.cucudq.cn/Article/details/gt2hlbvmtwd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.sxryk.cn/Article/details/gt2ktcfzaoj.html

[T47] Perl：正则捕获
来源：http://dali.ehwqpu.com/Article/details/gt2oyuvkooz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.tian-w.cn/Article/details/gt2ntlakzqj.html

[T48] Perl：正则替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wzzfvwvx.html

$s =~ s/old/new/g;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cerhbmba.html

[T49] Perl：函数
来源：http://dali.yvedp.cn/Article/details/gt2qsdbsont.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gt2agmhzmce.html

[T50] Perl：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gt2kpacypcm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.vqdsnc.cn/Article/details/gt2faevvzsk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.wangdashe.top/Article/details/gt2ticuvtno.html

[T51] Scala：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gt2zdgatuas.html

println("Hello")
来源：http://dali.xylfe.cn/Article/details/gt2wttliukc.html

[T52] Scala：变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2ksffswxv.html

val a = 1;  var b = 2
来源：http://dali.jqgufenzy.top/Article/details/gt2ccsmsdng.html

[T53] Scala：字符串插值
来源：http://dali.hywenlv.cn/Article/details/gt2tvhvnkwa.html

s"值: $b"
来源：http://dali.zdqjudy.top/Article/details/gt2fddiwtwe.html

[T54] Scala：集合映射
来源：http://dali.zhixingplan.top/Article/details/gt2gjroqtja.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.snrcjt.cn/Article/details/gt2dilnfgzf.html

[T55] Scala：集合过滤
来源：http://dali.hammf.cn/Article/details/gt2vuzhlgre.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jianghu66.top/Article/details/gt2aqlnpwsr.html

[T56] Scala：样例类
来源：http://dali.shuidangran.top/Article/details/gt2dadnfkqt.html

case class User(name: String, age: Int)
来源：http://dali.sxryk.cn/Article/details/gt2nlmlhrbl.html

[T57] Scala：模式匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jnqoexud.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cdnleiting.top/Article/details/gt2jafmhzcv.html

[T58] Scala：函数定义
来源：http://dali.chenlongwang.top/Article/details/gt2zilsuwar.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jiagoushi.top/Article/details/gt2hoorlgsq.html

[T59] Scala：循环
来源：http://dali.tian-w.cn/Article/details/gt2nahchssq.html

for (i <- 1 to 10) println(i)
来源：http://dali.cqqwz.cn/Article/details/gt2nrdblbst.html

[T60] Scala：折叠
来源：http://dali.jiagoushi.top/Article/details/gt2zsahhhof.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zdqjudy.top/Article/details/gt2zamwjwzh.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2yomsshge.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zycfv.cn/Article/details/gt2dgqcsiiu.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2xgxzdauq.html

[U01] Py：创建虚拟环境
来源：http://dali.vqdsnc.cn/Article/details/gt2dncjnwbn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yonumen.top/Article/details/gt2ifpxkglr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ybcxt.top/Article/details/gt2dujzsxsg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hywenlv.cn/Article/details/gt2pblcykdg.html

[U03] Py：加载 .env 配置
来源：http://dali.daxiang520.top/Article/details/gt2drqpydyr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.9152youxi.cn/Article/details/gt2cboslmki.html

[U04] Py：变量调试打印
来源：http://dali.zhengqikj.top/Article/details/gt2qgpwxwja.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jyoumei.cn/Article/details/gt2nfaymfym.html

[U05] Py：列表去重且保序
来源：http://dali.yj20258888.top/Article/details/gt2zrpqdfvq.html

list(dict.fromkeys(arr))
来源：http://dali.chenjidiqi.icu/Article/details/gt2irjqidxp.html

[U06] Py：合并两个字典
来源：http://dali.tianlin.xyz/Article/details/gt2wvrhbaly.html

{**a, **b}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tvwgtbvu.html

[U07] Py：反转字典键值
来源：http://dali.cheryme.top/Article/details/gt2hkhawynh.html

{v: k for k, v in d.items()}
来源：http://dali.316326.xyz/Article/details/gt2ygmvxcon.html

[U08] Py：展平二维列表
来源：http://dali.mhx1999.top/Article/details/gt2gioghhmd.html

[y for x in nested for y in x]
来源：http://dali.ydzc1.top/Article/details/gt2nbfyhkja.html

[U09] Py：字典取最大值的键
来源：http://dali.jqgfzy.top/Article/details/gt2oopevduw.html

max(d, key=d.get)
来源：http://dali.jiagoushi.top/Article/details/gt2whacmsyh.html

[U10] Py：按值排序字典
来源：http://dali.jinqigfzy.top/Article/details/gt2wkeqyzts.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hysaishi.cn/Article/details/gt2gzobwmfd.html

[U11] Py：生成器表达式
来源：http://dali.chenzaomai.com/Article/details/gt2fihlbqcg.html

(x * 2 for x in arr)
来源：http://dali.jyoumei.cn/Article/details/gt2fjgdlbbo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jiagoushi.top/Article/details/gt2sittuyju.html

Counter(arr).most_common(3)
来源：http://dali.zycfv.cn/Article/details/gt2vuatpnwc.html

[U13] Py：固定长度队列
来源：http://dali.cucudq.cn/Article/details/gt2onrbxvcu.html

deque(maxlen=10)
来源：http://dali.guowangkeji.top/Article/details/gt2axmadwuy.html

[U14] Py：分组收集到列表
来源：http://dali.hammf.cn/Article/details/gt2kayhzugj.html

defaultdict(list)
来源：http://dali.tian-w.cn/Article/details/gt2ltrirtlw.html

[U15] Py：高精度计时
来源：http://dali.redwolf501.top/Article/details/gt2wwhbqaxa.html

t = time.perf_counter()
来源：http://dali.dianchejie.cn/Article/details/gt2ukdcviuj.html

[U16] Py：命令行参数解析
来源：http://dali.yonumen.top/Article/details/gt2ktpufbsp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.snrcjt.cn/Article/details/gt2huljkpmd.html


<!-- 参考信息 -->