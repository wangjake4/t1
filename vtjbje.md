代发 wailian999

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yonumen.top/Article/details/gt2cmylpjhx.html

[R72] 等待端口就绪
来源：http://dali.chenzaomai.com/Article/details/gt2dkvsugwd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xuetiantiany.cn/Article/details/gt2oniwefld.html

[R73] 分割大日志
来源：http://dali.daxiang520.top/Article/details/gt2ydijmvhf.html

split -l 1000 big.log part_
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fpnxxqwu.html

[R74] 批量重命名
来源：http://dali.gaohongyu789.top/Article/details/gt2gskzkjsm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2zqmtseuy.html

[R75] 导出环境变量
来源：http://dali.sufxvd.cn/Article/details/gt2fhgwopsm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.fengsongda.top/Article/details/gt2lwankgra.html

[R76] 使用临时文件
来源：http://dali.pycfn.com/Article/details/gt2tsgaeqqu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.guowangkeji.top/Article/details/gt2hfciwskk.html

[R77] 读取用户输入
来源：http://dali.cucudq.cn/Article/details/gt2prcmqmsm.html

read -rp "请输入: " ans
来源：http://dali.daria6918.cn/Article/details/gt2uondfhdj.html

[R78] 交互式菜单
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lculhfbx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jqgufenzy.top/Article/details/gt2zenkscam.html

[R79] 解析命令行选项
来源：http://dali.hywenlv.cn/Article/details/gt2dsysbqbz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinqigufen.top/Article/details/gt2ocngoshw.html

[R80] 查看脚本执行耗时
来源：http://dali.tanke756.top/Article/details/gt2fvtqbhod.html

time ./run.sh
来源：http://dali.316326.xyz/Article/details/gt2tpnikupr.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2bssgvikc.html

S. C / C++ 专题
来源：http://dali.daria6918.cn/Article/details/gt2locuertt.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2hraydzln.html

[S01] C：Hello World
来源：http://dali.meibo888.top/Article/details/gt2bmpyzunj.html

#include <stdio.h>
来源：http://dali.yj20258.top/Article/details/gt2tkhukedl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cucudq.cn/Article/details/gt2tguiqdbz.html

[S02] C：变量与格式化输出
来源：http://dali.dianchejie.cn/Article/details/gt2xnaszsda.html

int a = 10; printf("%d\n", a);
来源：http://dali.aizwys.cn/Article/details/gt2wcmnuijr.html

[S03] C：读入整数
来源：http://dali.dashuyun.cn/Article/details/gt2ycebpndq.html

int x; scanf("%d", &x);
来源：http://dali.sysykeji.top/Article/details/gt2sepwbksr.html

[S04] C：字符串复制
来源：http://dali.smart0.xyz/Article/details/gt2opfrhjup.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ehwqpu.com/Article/details/gt2gtiaxwyx.html

[S05] C：字符串长度
来源：http://dali.daxiang520.top/Article/details/gt2hyawljax.html

strlen(s)
来源：http://dali.yueranfly.top/Article/details/gt2yjlvqjon.html

[S06] C：字符串比较
来源：http://dali.wangshuangyany.cn/Article/details/gt2lwpoxvof.html

strcmp(a, b) == 0
来源：http://dali.yuxming.cn/Article/details/gt2mquifvww.html

[S07] C：数组遍历求和
来源：http://dali.pycfn.com/Article/details/gt2jmgderdy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.mhx1999.top/Article/details/gt2obzwfjcl.html

[S08] C：动态内存分配与释放
来源：http://dali.nanxinkj.top/Article/details/gt2bybrjole.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jianghu66.top/Article/details/gt2pbxoejqo.html

[S09] C：结构体定义与初始化
来源：http://dali.xuetiantiany.cn/Article/details/gt2mbghadtx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jlsjyb.cn/Article/details/gt2lxxjuyro.html

[S10] C：指针与解引用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sogtyetw.html

int *p = &a;  *p = 5;
来源：http://dali.yangfankeji.com/Article/details/gt2cfafvhqc.html

[S11] C：逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gt2jouwezqb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.snrcjt.cn/Article/details/gt2uqqkqjyi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oucokfeb.html

fclose(f);
来源：http://dali.yangfankeji.com/Article/details/gt2qkpfqcbc.html

[S12] C：写文件
来源：http://dali.c1oappe.top/Article/details/gt2xviqfyuz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.havefunace.top/Article/details/gt2buhodwch.html

[S13] C：宏定义
来源：http://dali.gaohongyu789.top/Article/details/gt2rhfysfhm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nanxinkj.top/Article/details/gt2bbhxpfna.html

[S14] C：枚举
来源：http://dali.yanxiufei.cn/Article/details/gt2jxunjgrr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.birdmap.top/Article/details/gt2bcgsatuv.html

[S15] C：类型转换
来源：http://dali.tianlin.xyz/Article/details/gt2zoohduum.html

(double) a / b
来源：http://dali.yanxiufei.cn/Article/details/gt2mtjcuokq.html

[S16] C：位操作置位
来源：http://dali.dashuyun.cn/Article/details/gt2iwbrqdeo.html

x |= (1 << 3);
来源：http://dali.yanxiufei.cn/Article/details/gt2hgkclgcr.html

[S17] C：安全拼接字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2tbikusfm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jqgufenzy.top/Article/details/gt2twaiudyo.html

[S18] C：命令行参数
来源：http://dali.hywenlv.cn/Article/details/gt2igtofirr.html

int main(int argc, char **argv)
来源：http://dali.yueranfly.top/Article/details/gt2nokxkhfb.html

[S19] C：快速排序
来源：http://dali.jiagoushi.top/Article/details/gt2xnzavbxy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.meibo888.top/Article/details/gt2ilkondal.html

[S20] C：二分查找
来源：http://dali.zhiwuduotai.top/Article/details/gt2cdweyjdq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jianghu66.top/Article/details/gt2eehixcbm.html

[S21] C：字符类别判断
来源：http://dali.hnxiangtu.top/Article/details/gt2qflynnzn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ybcxt.top/Article/details/gt2pvjehppx.html

[S22] C：字符串转数字
来源：http://dali.aizwys.cn/Article/details/gt2mdhokhwy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hysaishi.cn/Article/details/gt2yuhddmrb.html

[S23] C：随机数
来源：http://dali.shzxlz.cn/Article/details/gt2kqtrhjza.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cucudq.cn/Article/details/gt2uksxdmeu.html

[S24] C：获取本地时间
来源：http://dali.aibaodan.cn/Article/details/gt2vsyrqoxi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shzxlz.cn/Article/details/gt2zbhsaigv.html

[S25] C：内存拷贝
来源：http://dali.9152youxi.cn/Article/details/gt2gevlbkxo.html

memcpy(dst, src, n);
来源：http://dali.daria6918.cn/Article/details/gt2ndylncid.html

[S26] C：内存清零
来源：http://dali.shangyingyoupin.top/Article/details/gt2jiegftjq.html

memset(a, 0, sizeof a);
来源：http://dali.yonumen.top/Article/details/gt2kdzelcbd.html

[S27] C：定义常量
来源：http://dali.wangshuangyany.cn/Article/details/gt2kztmlauw.html

const double PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gt2zzhjuhbs.html

[S28] C：静态变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2nlxdacej.html

static int counter = 0;
来源：http://dali.wangdashe.top/Article/details/gt2fxjcrryo.html

[S29] C：变参函数
来源：http://dali.snrcjt.cn/Article/details/gt2yqrmmvdn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oraxpfxf.html

[S30] C：头文件保护
来源：http://dali.shzxlz.cn/Article/details/gt2ynufipeq.html

#ifndef X_H
来源：http://dali.jyoumei.cn/Article/details/gt2tvcnrzlv.html

#define X_H
来源：http://dali.cashguo.top/Article/details/gt2bllrmhwz.html

#endif
来源：http://dali.wangdashe.top/Article/details/gt2ypzxxuih.html

[S31] C++：Hello World
来源：http://dali.yj20258.top/Article/details/gt2zrgspmsz.html

#include <iostream>
来源：http://dali.sxryk.cn/Article/details/gt2pjtpiina.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sufxvd.cn/Article/details/gt2tptcbqhv.html

[S32] C++：字符串
来源：http://dali.ybcxt.top/Article/details/gt2kvqdjqfu.html

std::string s = "hi";  s += "!";
来源：http://dali.nanxinkj.top/Article/details/gt2zvfjnbnm.html

[S33] C++：vector 增删
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zrsmlygn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnomuzt.html

[S34] C++：遍历 vector
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hghqdlwc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.daxiang520.top/Article/details/gt2lcgxuurq.html

[S35] C++：map
来源：http://dali.wangdashe.top/Article/details/gt2iajyvpgw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pleapvib.html

[S36] C++：unordered_map
来源：http://dali.sufxvd.cn/Article/details/gt2sptjlbbg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cheryme.top/Article/details/gt2qmuuwcdf.html

[S37] C++：set
来源：http://dali.havefunace.top/Article/details/gt2udelsxjt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.fzhhl.top/Article/details/gt2ohekxvcv.html

[S38] C++：排序
来源：http://dali.jianghu66.top/Article/details/gt2ikofvrhm.html

std::sort(v.begin(), v.end());
来源：http://dali.daria6918.cn/Article/details/gt2plhdguwd.html

[S39] C++：自定义比较器排序
来源：http://dali.0kj1m.cn/Article/details/gt2wdniiwoj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guowangkeji.top/Article/details/gt2cdvyvlgn.html

[S40] C++：查找元素
来源：http://dali.chenzaomai.com/Article/details/gt2mqifrvox.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yauuyjid.html

[S41] C++：类与构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dehciqtz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.aizwys.cn/Article/details/gt2zctjmepb.html

[S42] C++：继承与虚函数
来源：http://dali.gzhubu.top/Article/details/gt2fjecpjbz.html

class B : public Base { public: void f() override {} };
来源：http://dali.cheryme.top/Article/details/gt2xwjyzqmt.html

[S43] C++：智能指针
来源：http://dali.c1oappe.top/Article/details/gt2nmioqofn.html

auto p = std::make_unique<int>(5);
来源：http://dali.yangfankeji.com/Article/details/gt2dizdpmfu.html

[S44] C++：引用传参
来源：http://dali.tian-w.cn/Article/details/gt2kwrffuqx.html

void inc(int &x) { ++x; }
来源：http://dali.wangdashe.top/Article/details/gt2vswqhvrp.html

[S45] C++：lambda
来源：http://dali.xziqi.cn/Article/details/gt2xjrnxzgl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jqgfzy.top/Article/details/gt2zkmwadnw.html

[S46] C++：函数模板
来源：http://dali.sweek.top/Article/details/gt2rqmsxchi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.iojbl.cn/Article/details/gt2gmuwpapm.html

[S47] C++：结构化绑定遍历
来源：http://dali.cdnleiting.top/Article/details/gt2zhcbxtec.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ncsdokti.html

[S48] C++：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gt2altwsrlm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.daxiang520.top/Article/details/gt2psvrbmyl.html

while (std::getline(in, line)) { }
来源：http://dali.zycfv.cn/Article/details/gt2lywsemxv.html

[S49] C++：写文件
来源：http://dali.zhengqikj.top/Article/details/gt2aczktsut.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hongshengwenyu.top/Article/details/gt2nriamuzj.html

[S50] C++：格式化数字
来源：http://dali.yongpay.top/Article/details/gt2qnsvpgml.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.bjfxy.top/Article/details/gt2bukoxbea.html

[S51] C++：显式类型转换
来源：http://dali.ybcxt.top/Article/details/gt2bsmtrsdn.html

static_cast<double>(a) / b
来源：http://dali.jiagoushi.top/Article/details/gt2rdcrgonv.html

[S52] C++：const 与 noexcept
来源：http://dali.vqdsnc.cn/Article/details/gt2fsfidwec.html

int size() const noexcept { return n_; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2toppxhpi.html

[S53] C++：移动语义
来源：http://dali.ehwqpu.com/Article/details/gt2ezphzdwf.html

std::vector<int> w = std::move(v);
来源：http://dali.tanke756.top/Article/details/gt2qvmcddaj.html

[S54] C++：异常处理
来源：http://dali.dashuyun.cn/Article/details/gt2rgaaggyk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gogol.net.cn/Article/details/gt2xmquedmm.html

[S55] C++：结构化绑定
来源：http://dali.meibo888.top/Article/details/gt2zdkqvrzd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jyoumei.cn/Article/details/gt2bwikjjdr.html

[S56] C++：optional
来源：http://dali.yuxming.cn/Article/details/gt2mawwmxxl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.c1oappe.top/Article/details/gt2qzxymtkl.html

[S57] C++：编译期常量
来源：http://dali.gogol.net.cn/Article/details/gt2cpzqxnpe.html

constexpr int N = 10;
来源：http://dali.ivvv.top/Article/details/gt2sparmyln.html

[S58] C++：命名空间
来源：http://dali.xziqi.cn/Article/details/gt2euqqldcg.html

namespace ns { int f() { return 1; } }
来源：http://dali.cheryme.top/Article/details/gt2gjdeddzu.html

[S59] C++：静态断言
来源：http://dali.hysaishi.cn/Article/details/gt2pryqfstb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xuetiantiany.cn/Article/details/gt2ofwlgddc.html

[S60] C++：遍历并删除元素
来源：http://dali.yj20258888.top/Article/details/gt2khfxfvya.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.smart0.xyz/Article/details/gt2pljiwjdp.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2rnpblhdf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.smart0.xyz/Article/details/gt2txaiztco.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2ypfdvuuj.html

[T01] Kotlin：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zubxxrqk.html

println("Hello")
来源：http://dali.tian-w.cn/Article/details/gt2jtzvdrrd.html

[T02] Kotlin：变量
来源：http://dali.gotoacloud.top/Article/details/gt2atzbnmwy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gzhubu.top/Article/details/gt2ibdvmsmg.html

[T03] Kotlin：字符串模板
来源：http://dali.ydzc1.top/Article/details/gt2mpohlwlw.html

"值: $b"
来源：http://dali.cdnleiting.top/Article/details/gt2zggaoiwd.html

[T04] Kotlin：空安全
来源：http://dali.sysykeji.top/Article/details/gt2rqqgsxwt.html

val n: String? = null;  n?.length
来源：http://dali.ivvv.top/Article/details/gt2lyjeybwr.html

[T05] Kotlin：when 表达式
来源：http://dali.sxryk.cn/Article/details/gt2voshwmlr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pdpzfvjs.html

[T06] Kotlin：集合映射
来源：http://dali.0kj1m.cn/Article/details/gt2wchjmglt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.fzhhl.top/Article/details/gt2zsbxzyyx.html

[T07] Kotlin：集合过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gioorhgo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ppjwa.cn/Article/details/gt2xponxpnt.html

[T08] Kotlin：数据类
来源：http://dali.tianlin.xyz/Article/details/gt2uhazdsep.html

data class User(val name: String, val age: Int)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qnkbuzwx.html

[T09] Kotlin：扩展函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2rbjaqxrj.html

fun String.exclaim() = this + "!"
来源：http://dali.vqdsnc.cn/Article/details/gt2iuuzpvdk.html

[T10] Kotlin：默认参数
来源：http://dali.ivvv.top/Article/details/gt2vzodhzfn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gzhubu.top/Article/details/gt2kgmiatvg.html

[T11] Kotlin：协程
来源：http://dali.havefunace.top/Article/details/gt2sjvzbcav.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.feifeiyinyue.top/Article/details/gt2uouselfn.html

[T12] Kotlin：解构声明
来源：http://dali.sweek.top/Article/details/gt2texbafct.html

val (a, b) = Pair(1, 2)
来源：http://dali.ydzc1.top/Article/details/gt2iwslaciy.html

[T13] Kotlin：只读 Map
来源：http://dali.vqdsnc.cn/Article/details/gt2uyqbgyxg.html

val m = mapOf("a" to 1)
来源：http://dali.zhoulong.xyz/Article/details/gt2jwfvvmfm.html

[T14] Kotlin：循环
来源：http://dali.yanxiufei.cn/Article/details/gt2brqvuquk.html

for (i in 1..10) println(i)
来源：http://dali.xuanzx.com/Article/details/gt2uuryupbf.html

[T15] Kotlin：接口
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wcfwjqse.html

interface Shape { fun area(): Double }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ebtdpvtd.html

[T16] Swift：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gt2tjqqbxwl.html

print("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ixnbroql.html

[T17] Swift：变量与常量
来源：http://dali.zycfv.cn/Article/details/gt2kfsfhczh.html

var a = 1;  let b = 2
来源：http://dali.aizwys.cn/Article/details/gt2yqsfimzh.html

[T18] Swift：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gt2puoyouyp.html

"值: \(b)"
来源：http://dali.xziqi.cn/Article/details/gt2gccqwqqe.html

[T19] Swift：可选绑定
来源：http://dali.gogol.net.cn/Article/details/gt2hcbvdzpy.html

if let n = opt { print(n) }
来源：http://dali.zhiwuduotai.top/Article/details/gt2kyokgtvo.html

[T20] Swift：数组操作
来源：http://dali.cucudq.cn/Article/details/gt2zkswmqdf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ehwqpu.com/Article/details/gt2quybndbr.html

[T21] Swift：遍历
来源：http://dali.zhixingplan.top/Article/details/gt2tlkdisix.html

for x in a { print(x) }
来源：http://dali.sysykeji.top/Article/details/gt2olssyheq.html

[T22] Swift：字典
来源：http://dali.chenlongwang.top/Article/details/gt2qcjucnod.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.daxiang520.top/Article/details/gt2ozeznnqy.html

[T23] Swift：函数
来源：http://dali.dashuyun.cn/Article/details/gt2ogmabeky.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ppjwa.cn/Article/details/gt2rvxgaoyt.html

[T24] Swift：闭包
来源：http://dali.xinyue.icu/Article/details/gt2bscplrvw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xylfe.cn/Article/details/gt2bcdwtnkd.html

[T25] Swift：结构体
来源：http://dali.yanxiufei.cn/Article/details/gt2hfujxshs.html

struct P { var x: Int }
来源：http://dali.hnxiangtu.top/Article/details/gt2dqwyuhbu.html

[T26] Swift：类与重写
来源：http://dali.guowangkeji.top/Article/details/gt2nsmzcewn.html

class A: Base { override func f() {} }
来源：http://dali.yuxming.cn/Article/details/gt2ejeladst.html

[T27] Swift：错误处理
来源：http://dali.chenjidiqi.icu/Article/details/gt2knejcmzw.html

do { try f() } catch { print(error) }
来源：http://dali.9152youxi.cn/Article/details/gt2qgzzfqgm.html

[T28] Swift：枚举
来源：http://dali.hongshengwenyu.top/Article/details/gt2ejqeqddy.html

enum Color { case red, green }
来源：http://dali.jqgufenzy.top/Article/details/gt2opacqzgk.html

[T29] Swift：guard 提前返回
来源：http://dali.yueranfly.top/Article/details/gt2anjmgddn.html

guard let x = opt else { return }
来源：http://dali.ehwqpu.com/Article/details/gt2kagtmbym.html

[T30] Swift：协议
来源：http://dali.dashuyun.cn/Article/details/gt2rmlpwdne.html

protocol Shape { func area() -> Double }
来源：http://dali.gogol.net.cn/Article/details/gt2jqbodcgp.html

[T31] Lua：Hello World
来源：http://dali.daxiang520.top/Article/details/gt2fspcpult.html

print("Hello")
来源：http://dali.zhongyouzk.top/Article/details/gt2txsofuyl.html

[T32] Lua：局部变量
来源：http://dali.dianchejie.cn/Article/details/gt2bupefqhv.html

local a = 1
来源：http://dali.tian-w.cn/Article/details/gt2itwpzudg.html

[T33] Lua：表（数组）
来源：http://dali.fengsongda.top/Article/details/gt2tixkcbyr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.guannengcc.top/Article/details/gt2wpxmbwpf.html

[T34] Lua：遍历表
来源：http://dali.ydzc1.top/Article/details/gt2ztmpwmgr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.pycfn.com/Article/details/gt2wdcxrqfp.html

[T35] Lua：字典表
来源：http://dali.jqgufenzy.top/Article/details/gt2psjzgrsv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yvedp.cn/Article/details/gt2qynbehsc.html

[T36] Lua：函数
来源：http://dali.xylfe.cn/Article/details/gt2vnqwiswp.html

function add(a, b) return a + b end
来源：http://dali.svipenyu.cn/Article/details/gt2gnfzyyfo.html

[T37] Lua：字符串拼接
来源：http://dali.sysykeji.top/Article/details/gt2yxlyaqru.html

"a" .. "b"
来源：http://dali.kuanghao11.cn/Article/details/gt2nmzwsbru.html

[T38] Lua：条件
来源：http://dali.zycfv.cn/Article/details/gt2bdvqxhdg.html

if x > 0 then print("正") end
来源：http://dali.chenlongwang.top/Article/details/gt2xviewfod.html

[T39] Lua：模式匹配
来源：http://dali.yj202588.top/Article/details/gt2mxonvygl.html

string.find(s, "%d+")
来源：http://dali.dashuyun.cn/Article/details/gt2ojtefxos.html

[T40] Lua：元表
来源：http://dali.jinqigfzy.top/Article/details/gt2xhvouekx.html

setmetatable({}, { __index = base })
来源：http://dali.ivvv.top/Article/details/gt2gwnvgttp.html

[T41] Perl：Hello World
来源：http://dali.yongpay.top/Article/details/gt2gqklgnzn.html

print "Hello\n";
来源：http://dali.hammf.cn/Article/details/gt2wtdjosqn.html

[T42] Perl：变量类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2rlntkiji.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hnxiangtu.top/Article/details/gt2geysofbw.html

[T43] Perl：字符串插值
来源：http://dali.c1oappe.top/Article/details/gt2ljtpgybt.html

"值: $a"
来源：http://dali.fengsongda.top/Article/details/gt2rkqwvnaj.html

[T44] Perl：条件
来源：http://dali.9152youxi.cn/Article/details/gt2ubjhtsbm.html

if ($a > 0) { print "正"; }
来源：http://dali.hfpthk.cn/Article/details/gt2endxwkgk.html

[T45] Perl：数组遍历
来源：http://dali.jianghu66.top/Article/details/gt2fycbxhbi.html

for my $x (@arr) { print $x; }
来源：http://dali.sxryk.cn/Article/details/gt2ptdsusim.html

[T46] Perl：哈希操作
来源：http://dali.tianlin.xyz/Article/details/gt2adsmzfdm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.havefunace.top/Article/details/gt2zaxtgwth.html

[T47] Perl：正则捕获
来源：http://dali.yueranfly.top/Article/details/gt2brvuwscr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yangfankeji.com/Article/details/gt2ijldoawp.html

[T48] Perl：正则替换
来源：http://dali.xinyue.icu/Article/details/gt2mpgjqbry.html

$s =~ s/old/new/g;
来源：http://dali.fzhhl.top/Article/details/gt2tzaaczvf.html

[T49] Perl：函数
来源：http://dali.yj20258.top/Article/details/gt2scmkwogf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.meibo888.top/Article/details/gt2hdvoiizg.html

[T50] Perl：逐行读文件
来源：http://dali.yuxming.cn/Article/details/gt2ridfxsgj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xziqi.cn/Article/details/gt2jqkfnhkr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.snrcjt.cn/Article/details/gt2vkqzggse.html

[T51] Scala：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ribhfjxf.html

println("Hello")
来源：http://dali.hammf.cn/Article/details/gt2ccgklqvj.html

[T52] Scala：变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nyfpwnyq.html

val a = 1;  var b = 2
来源：http://dali.tian-w.cn/Article/details/gt2wylcgnil.html

[T53] Scala：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gt2ovxvuvgb.html

s"值: $b"
来源：http://dali.chenzaomai.com/Article/details/gt2zlyjdavg.html

[T54] Scala：集合映射
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pbfclevp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2dgszbbgp.html

[T55] Scala：集合过滤
来源：http://dali.zdqjudy.top/Article/details/gt2uapemrtd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.mhx1999.top/Article/details/gt2bxjrgmmn.html

[T56] Scala：样例类
来源：http://dali.ivvv.top/Article/details/gt2ipahbwts.html

case class User(name: String, age: Int)
来源：http://dali.yanxiufei.cn/Article/details/gt2gsjujvgj.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsvfjbt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.daria6918.cn/Article/details/gt2aruvnivg.html

[T58] Scala：函数定义
来源：http://dali.guowangkeji.top/Article/details/gt2ghdtokwv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yonumen.top/Article/details/gt2wtumfxql.html

[T59] Scala：循环
来源：http://dali.zycfv.cn/Article/details/gt2fvbtlvpv.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdsjdfgr.html

[T60] Scala：折叠
来源：http://dali.andypj.xyz/Article/details/gt2rnsukmuq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.bjfxy.top/Article/details/gt2xprzxvav.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2qrssaekf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.birdmap.top/Article/details/gt2caokcudd.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2vtarbjvl.html

[U01] Py：创建虚拟环境
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zlnbijhi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2meivvwrg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.aibaodan.cn/Article/details/gt2ygxijbgo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.daria6918.cn/Article/details/gt2vwpqldwv.html

[U03] Py：加载 .env 配置
来源：http://dali.tian-w.cn/Article/details/gt2kahcaqul.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.dianchejie.cn/Article/details/gt2cwujfwhy.html

[U04] Py：变量调试打印
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2asglzlyk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sysykeji.top/Article/details/gt2mhmarhsw.html

[U05] Py：列表去重且保序
来源：http://dali.0kj1m.cn/Article/details/gt2znvuqiiu.html

list(dict.fromkeys(arr))
来源：http://dali.shuidangran.top/Article/details/gt2zvloruus.html

[U06] Py：合并两个字典
来源：http://dali.gotoacloud.top/Article/details/gt2olqjialw.html

{**a, **b}
来源：http://dali.hysaishi.cn/Article/details/gt2uoatzfte.html

[U07] Py：反转字典键值
来源：http://dali.zhengqikj.top/Article/details/gt2mkdtzljv.html

{v: k for k, v in d.items()}
来源：http://dali.nanxinkj.top/Article/details/gt2gegeytib.html

[U08] Py：展平二维列表
来源：http://dali.tanke756.top/Article/details/gt2ztduvycq.html

[y for x in nested for y in x]
来源：http://dali.pycfn.com/Article/details/gt2lygtgbin.html

[U09] Py：字典取最大值的键
来源：http://dali.cashguo.top/Article/details/gt2skqojhuk.html

max(d, key=d.get)
来源：http://dali.xylfe.cn/Article/details/gt2ysilkigi.html

[U10] Py：按值排序字典
来源：http://dali.havefunace.top/Article/details/gt2yjzbrcto.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.tianlin.xyz/Article/details/gt2lzfqasjl.html

[U11] Py：生成器表达式
来源：http://dali.xylfe.cn/Article/details/gt2fypgtocm.html

(x * 2 for x in arr)
来源：http://dali.yvedp.cn/Article/details/gt2ebxbuqha.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.bjfxy.top/Article/details/gt2bacvqkob.html

Counter(arr).most_common(3)
来源：http://dali.hammf.cn/Article/details/gt2qyzankkk.html


<!-- 参考信息 -->