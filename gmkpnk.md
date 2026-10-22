代发 wailian999

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.dianchejie.cn/Article/details/gt2gintqbtz.html

[R72] 等待端口就绪
来源：http://dali.quarkkingdee.top/Article/details/gt2wgiogcgk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shuidangran.top/Article/details/gt2oshzvxxd.html

[R73] 分割大日志
来源：http://dali.xuanzx.com/Article/details/gt2canfikxd.html

split -l 1000 big.log part_
来源：http://dali.feifeiyinyue.top/Article/details/gt2tknzlaav.html

[R74] 批量重命名
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qjwydqce.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.fengsongda.top/Article/details/gt2dkruvdbz.html

[R75] 导出环境变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2bgncrncp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gzhubu.top/Article/details/gt2ukgdfvms.html

[R76] 使用临时文件
来源：http://dali.fengsongda.top/Article/details/gt2uumxaqjt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gaohongyu789.top/Article/details/gt2cigqawcx.html

[R77] 读取用户输入
来源：http://dali.zdqjudy.top/Article/details/gt2gynuvpyu.html

read -rp "请输入: " ans
来源：http://dali.zhoulong.xyz/Article/details/gt2ggoeprvq.html

[R78] 交互式菜单
来源：http://dali.jiagoushi.top/Article/details/gt2mdkfkguy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.svipenyu.cn/Article/details/gt2wouxktqg.html

[R79] 解析命令行选项
来源：http://dali.havefunace.top/Article/details/gt2zraxnehr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.316326.xyz/Article/details/gt2jigcocwj.html

[R80] 查看脚本执行耗时
来源：http://dali.zhengqikj.top/Article/details/gt2pxudanyq.html

time ./run.sh
来源：http://dali.0kj1m.cn/Article/details/gt2zezezuyr.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2grnrlfxc.html

S. C / C++ 专题
来源：http://dali.yj20258888.top/Article/details/gt2osrfnvrs.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2zkimvnrd.html

[S01] C：Hello World
来源：http://dali.cqqwz.cn/Article/details/gt2tsehulhl.html

#include <stdio.h>
来源：http://dali.yueranfly.top/Article/details/gt2xoovrnlb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.smart0.xyz/Article/details/gt2daavxqjk.html

[S02] C：变量与格式化输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uhivxtvl.html

int a = 10; printf("%d\n", a);
来源：http://dali.mhx1999.top/Article/details/gt2ezyxongh.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2uufylahs.html

int x; scanf("%d", &x);
来源：http://dali.gzhubu.top/Article/details/gt2wojhuads.html

[S04] C：字符串复制
来源：http://dali.yvedp.cn/Article/details/gt2mabwywmf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sysykeji.top/Article/details/gt2rgvxkfrk.html

[S05] C：字符串长度
来源：http://dali.pycfn.com/Article/details/gt2mqmuewwo.html

strlen(s)
来源：http://dali.cheryme.top/Article/details/gt2rgkpljpn.html

[S06] C：字符串比较
来源：http://dali.cqqwz.cn/Article/details/gt2ephemvot.html

strcmp(a, b) == 0
来源：http://dali.tianlin.xyz/Article/details/gt2uurgragl.html

[S07] C：数组遍历求和
来源：http://dali.9152youxi.cn/Article/details/gt2qwhodnko.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nanxinkj.top/Article/details/gt2tgtyuqee.html

[S08] C：动态内存分配与释放
来源：http://dali.pycfn.com/Article/details/gt2dombzmov.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yj20258888.top/Article/details/gt2swsbocbm.html

[S09] C：结构体定义与初始化
来源：http://dali.yueranfly.top/Article/details/gt2shjfqrqd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinqigfzy.top/Article/details/gt2ejsaboye.html

[S10] C：指针与解引用
来源：http://dali.cheryme.top/Article/details/gt2cifitzis.html

int *p = &a;  *p = 5;
来源：http://dali.hywenlv.cn/Article/details/gt2gboodbdc.html

[S11] C：逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gt2abcnbwnq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xuanzx.com/Article/details/gt2jbkugqnb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xinyue.icu/Article/details/gt2rjtxenhi.html

fclose(f);
来源：http://dali.mhx1999.top/Article/details/gt2mrpgftbk.html

[S12] C：写文件
来源：http://dali.fzhhl.top/Article/details/gt2stdmiitg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nwbrower.top/Article/details/gt2wrkevemj.html

[S13] C：宏定义
来源：http://dali.yuxming.cn/Article/details/gt2rlekltpw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.316326.xyz/Article/details/gt2sodultfi.html

[S14] C：枚举
来源：http://dali.havefunace.top/Article/details/gt2afmhuzcm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xylfe.cn/Article/details/gt2nxwckkbn.html

[S15] C：类型转换
来源：http://dali.dashuyun.cn/Article/details/gt2vdrhgezv.html

(double) a / b
来源：http://dali.cqqwz.cn/Article/details/gt2qaqhxtfw.html

[S16] C：位操作置位
来源：http://dali.daxiang520.top/Article/details/gt2scgjezij.html

x |= (1 << 3);
来源：http://dali.xylfe.cn/Article/details/gt2gaunjion.html

[S17] C：安全拼接字符串
来源：http://dali.ybcxt.top/Article/details/gt2jultdzjx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.fengsongda.top/Article/details/gt2rlmhjkar.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xvxqnkli.html

int main(int argc, char **argv)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vbkifioa.html

[S19] C：快速排序
来源：http://dali.pengpengdd.cyou/Article/details/gt2vdznquth.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.daria6918.cn/Article/details/gt2nnatskad.html

[S20] C：二分查找
来源：http://dali.shzxlz.cn/Article/details/gt2qoiinzfj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.daxiang520.top/Article/details/gt2gwlsuuru.html

[S21] C：字符类别判断
来源：http://dali.ydzc1.top/Article/details/gt2bjtjgbmf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fgytxpuf.html

[S22] C：字符串转数字
来源：http://dali.smart0.xyz/Article/details/gt2pmotanqk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.316326.xyz/Article/details/gt2orlcmtqx.html

[S23] C：随机数
来源：http://dali.9152youxi.cn/Article/details/gt2yavtowyc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cqqwz.cn/Article/details/gt2fbfnombf.html

[S24] C：获取本地时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iixjzgcl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj20258888.top/Article/details/gt2fgicwezm.html

[S25] C：内存拷贝
来源：http://dali.yj20258.top/Article/details/gt2xdhpowsi.html

memcpy(dst, src, n);
来源：http://dali.sxryk.cn/Article/details/gt2ldvreiav.html

[S26] C：内存清零
来源：http://dali.jiagoushi.top/Article/details/gt2ytnelwyc.html

memset(a, 0, sizeof a);
来源：http://dali.xinyue.icu/Article/details/gt2oqsyhxcq.html

[S27] C：定义常量
来源：http://dali.ehwqpu.com/Article/details/gt2vafqfaui.html

const double PI = 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gt2aaqcwbws.html

[S28] C：静态变量
来源：http://dali.yj20258.top/Article/details/gt2oaabergl.html

static int counter = 0;
来源：http://dali.yj202588.top/Article/details/gt2saedpkza.html

[S29] C：变参函数
来源：http://dali.9152youxi.cn/Article/details/gt2kgjwbkaa.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.dashuyun.cn/Article/details/gt2bfczbjgd.html

[S30] C：头文件保护
来源：http://dali.jinqigfzy.top/Article/details/gt2cansbbwl.html

#ifndef X_H
来源：http://dali.ppjwa.cn/Article/details/gt2gojrgfzc.html

#define X_H
来源：http://dali.fengsongda.top/Article/details/gt2uaeeccul.html

#endif
来源：http://dali.shzxlz.cn/Article/details/gt2wvydstkj.html

[S31] C++：Hello World
来源：http://dali.guannengcc.top/Article/details/gt2bfwxearl.html

#include <iostream>
来源：http://dali.cheryme.top/Article/details/gt2vxgkuwoc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ahoigdco.html

[S32] C++：字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2xvufedhk.html

std::string s = "hi";  s += "!";
来源：http://dali.nanxuanxn.top/Article/details/gt2jeqaraxp.html

[S33] C++：vector 增删
来源：http://dali.xuetiantiany.cn/Article/details/gt2nkkgweir.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yuanzhike.top/Article/details/gt2hfqmqiyw.html

[S34] C++：遍历 vector
来源：http://dali.sxryk.cn/Article/details/gt2hjmwbrdf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hysaishi.cn/Article/details/gt2yfbhcwod.html

[S35] C++：map
来源：http://dali.daxiang520.top/Article/details/gt2tgyextlr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2uqgrudwa.html

[S36] C++：unordered_map
来源：http://dali.cqqwz.cn/Article/details/gt2vtthffiu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fzhhl.top/Article/details/gt2ecpuzqys.html

[S37] C++：set
来源：http://dali.sweek.top/Article/details/gt2ssezgdmm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.redwolf501.top/Article/details/gt2iubaorkj.html

[S38] C++：排序
来源：http://dali.feifeiyinyue.top/Article/details/gt2vxtvfvhm.html

std::sort(v.begin(), v.end());
来源：http://dali.quarkkingdee.top/Article/details/gt2nfaruorx.html

[S39] C++：自定义比较器排序
来源：http://dali.sufxvd.cn/Article/details/gt2twnvfhde.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mulzxmkp.html

[S40] C++：查找元素
来源：http://dali.fzhhl.top/Article/details/gt2bttkwzje.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.9152youxi.cn/Article/details/gt2ikawnedy.html

[S41] C++：类与构造函数
来源：http://dali.zdqjudy.top/Article/details/gt2oyyxciwj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.havefunace.top/Article/details/gt2ndgmjqbw.html

[S42] C++：继承与虚函数
来源：http://dali.svipenyu.cn/Article/details/gt2qqfvyvwu.html

class B : public Base { public: void f() override {} };
来源：http://dali.shangyingyoupin.top/Article/details/gt2lkxlxhwi.html

[S43] C++：智能指针
来源：http://dali.bjfxy.top/Article/details/gt2dgewmuyl.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhoulong.xyz/Article/details/gt2hdsaolje.html

[S44] C++：引用传参
来源：http://dali.aibaodan.cn/Article/details/gt2xdblxaat.html

void inc(int &x) { ++x; }
来源：http://dali.shzxlz.cn/Article/details/gt2ffjjmnle.html

[S45] C++：lambda
来源：http://dali.dianchejie.cn/Article/details/gt2hwjahmjj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jiagoushi.top/Article/details/gt2tirjbpop.html

[S46] C++：函数模板
来源：http://dali.hywenlv.cn/Article/details/gt2fdorqbuu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.bjfxy.top/Article/details/gt2wmysmcdq.html

[S47] C++：结构化绑定遍历
来源：http://dali.sxryk.cn/Article/details/gt2nxhfdkee.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.dianchejie.cn/Article/details/gt2zwkqjmcx.html

[S48] C++：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gt2gkrgejvo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenlongwang.top/Article/details/gt2oraxullt.html

while (std::getline(in, line)) { }
来源：http://dali.hysaishi.cn/Article/details/gt2efowhjvq.html

[S49] C++：写文件
来源：http://dali.9152youxi.cn/Article/details/gt2nkmculgu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.vqdsnc.cn/Article/details/gt2uolcdavm.html

[S50] C++：格式化数字
来源：http://dali.nanxuanxn.top/Article/details/gt2fxvyngnv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ghbymttb.html

[S51] C++：显式类型转换
来源：http://dali.jinqigfzy.top/Article/details/gt2tlmtjcqc.html

static_cast<double>(a) / b
来源：http://dali.pycfn.com/Article/details/gt2bvsrwztc.html

[S52] C++：const 与 noexcept
来源：http://dali.cheryme.top/Article/details/gt2shpsthyu.html

int size() const noexcept { return n_; }
来源：http://dali.jlsjyb.cn/Article/details/gt2awfssxdi.html

[S53] C++：移动语义
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rojptpjg.html

std::vector<int> w = std::move(v);
来源：http://dali.nanxinkj.top/Article/details/gt2ddbqywlh.html

[S54] C++：异常处理
来源：http://dali.0kj1m.cn/Article/details/gt2qqyilvwu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhongyouzk.top/Article/details/gt2mzvaaqtl.html

[S55] C++：结构化绑定
来源：http://dali.nanxinkj.top/Article/details/gt2kcdcuwvf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.snrcjt.cn/Article/details/gt2htnmaawx.html

[S56] C++：optional
来源：http://dali.haohaochexian.top/Article/details/gt2jmavpkpj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.snrcjt.cn/Article/details/gt2dzhowyjo.html

[S57] C++：编译期常量
来源：http://dali.jyoumei.cn/Article/details/gt2tjqvueyl.html

constexpr int N = 10;
来源：http://dali.haohaochexian.top/Article/details/gt2hvjcaqhd.html

[S58] C++：命名空间
来源：http://dali.hnqzz.top/Article/details/gt2tfwqmvso.html

namespace ns { int f() { return 1; } }
来源：http://dali.vqdsnc.cn/Article/details/gt2knjckfyv.html

[S59] C++：静态断言
来源：http://dali.fzhhl.top/Article/details/gt2rzfnvtds.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.chenzaomai.com/Article/details/gt2gleekuxs.html

[S60] C++：遍历并删除元素
来源：http://dali.bjfxy.top/Article/details/gt2rgkbfswo.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhengqikj.top/Article/details/gt2lpkrmhyg.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2jecfjrtx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhixingplan.top/Article/details/gt2scdutknh.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2vtyzaobq.html

[T01] Kotlin：Hello World
来源：http://dali.tanke756.top/Article/details/gt2qpscboce.html

println("Hello")
来源：http://dali.cashguo.top/Article/details/gt2tjlhmurm.html

[T02] Kotlin：变量
来源：http://dali.meibo888.top/Article/details/gt2flrqrldj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cdnleiting.top/Article/details/gt2zjgvgzyo.html

[T03] Kotlin：字符串模板
来源：http://dali.pengpengdd.cyou/Article/details/gt2ivpapzca.html

"值: $b"
来源：http://dali.cucudq.cn/Article/details/gt2yellbwtf.html

[T04] Kotlin：空安全
来源：http://dali.wangdashe.top/Article/details/gt2oqlreilh.html

val n: String? = null;  n?.length
来源：http://dali.havefunace.top/Article/details/gt2qzydxfyh.html

[T05] Kotlin：when 表达式
来源：http://dali.dianchejie.cn/Article/details/gt2gdqwafcu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jiagoushi.top/Article/details/gt2nzhwwyqq.html

[T06] Kotlin：集合映射
来源：http://dali.yj202588.top/Article/details/gt2uacuozqj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ydzc1.top/Article/details/gt2rdhitjai.html

[T07] Kotlin：集合过滤
来源：http://dali.aibaodan.cn/Article/details/gt2rjbpbvps.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ppjwa.cn/Article/details/gt2xyandpdd.html

[T08] Kotlin：数据类
来源：http://dali.xylfe.cn/Article/details/gt2xsnknghj.html

data class User(val name: String, val age: Int)
来源：http://dali.hongshengwenyu.top/Article/details/gt2cobqaecq.html

[T09] Kotlin：扩展函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2bkmhrrpz.html

fun String.exclaim() = this + "!"
来源：http://dali.zycfv.cn/Article/details/gt2pgrbpgpf.html

[T10] Kotlin：默认参数
来源：http://dali.cheryme.top/Article/details/gt2ynnmvmbs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shangyingyoupin.top/Article/details/gt2phpagppa.html

[T11] Kotlin：协程
来源：http://dali.ybcxt.top/Article/details/gt2vnuyzihj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.dianchejie.cn/Article/details/gt2qhzegpyc.html

[T12] Kotlin：解构声明
来源：http://dali.fengsongda.top/Article/details/gt2iwgmhjrk.html

val (a, b) = Pair(1, 2)
来源：http://dali.tianlin.xyz/Article/details/gt2gkuwbvsc.html

[T13] Kotlin：只读 Map
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xixhubts.html

val m = mapOf("a" to 1)
来源：http://dali.sweek.top/Article/details/gt2qqwlpxkv.html

[T14] Kotlin：循环
来源：http://dali.nanxinkj.top/Article/details/gt2kpnykxjk.html

for (i in 1..10) println(i)
来源：http://dali.daxiang520.top/Article/details/gt2kgzlimsu.html

[T15] Kotlin：接口
来源：http://dali.xinyue.icu/Article/details/gt2pqyadroq.html

interface Shape { fun area(): Double }
来源：http://dali.nwbrower.top/Article/details/gt2jtftqixw.html

[T16] Swift：Hello World
来源：http://dali.shuidangran.top/Article/details/gt2gydxediu.html

print("Hello")
来源：http://dali.chenzaomai.com/Article/details/gt2bnwpwduq.html

[T17] Swift：变量与常量
来源：http://dali.yj20258.top/Article/details/gt2izrhlsrt.html

var a = 1;  let b = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kwbyopml.html

[T18] Swift：字符串插值
来源：http://dali.yonumen.top/Article/details/gt2gckyvwkg.html

"值: \(b)"
来源：http://dali.gotoacloud.top/Article/details/gt2axwogpxu.html

[T19] Swift：可选绑定
来源：http://dali.0kj1m.cn/Article/details/gt2igexdfqx.html

if let n = opt { print(n) }
来源：http://dali.aibaodan.cn/Article/details/gt2ffwgnzqe.html

[T20] Swift：数组操作
来源：http://dali.aibaodan.cn/Article/details/gt2mnindmqw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cdnleiting.top/Article/details/gt2wjqflxky.html

[T21] Swift：遍历
来源：http://dali.chenlongwang.top/Article/details/gt2ivaxfekg.html

for x in a { print(x) }
来源：http://dali.guannengcc.top/Article/details/gt2laaxgzof.html

[T22] Swift：字典
来源：http://dali.zycfv.cn/Article/details/gt2uwwpneek.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hammf.cn/Article/details/gt2xbkzkhwb.html

[T23] Swift：函数
来源：http://dali.yonumen.top/Article/details/gt2eyadpouo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yueranfly.top/Article/details/gt2wndcedjy.html

[T24] Swift：闭包
来源：http://dali.fzhhl.top/Article/details/gt2zcaavcaa.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.quarkkingdee.top/Article/details/gt2dpfalssa.html

[T25] Swift：结构体
来源：http://dali.xuanzx.com/Article/details/gt2iyeixawk.html

struct P { var x: Int }
来源：http://dali.cheryme.top/Article/details/gt2jdzupnpb.html

[T26] Swift：类与重写
来源：http://dali.316326.xyz/Article/details/gt2rnhbqjex.html

class A: Base { override func f() {} }
来源：http://dali.chenzaomai.com/Article/details/gt2nuprqiyb.html

[T27] Swift：错误处理
来源：http://dali.chenlongwang.top/Article/details/gt2qhklsdqg.html

do { try f() } catch { print(error) }
来源：http://dali.316326.xyz/Article/details/gt2qkpihfks.html

[T28] Swift：枚举
来源：http://dali.hnxiangtu.top/Article/details/gt2reyqgwxk.html

enum Color { case red, green }
来源：http://dali.pycfn.com/Article/details/gt2ftnxlesl.html

[T29] Swift：guard 提前返回
来源：http://dali.shzxlz.cn/Article/details/gt2fwlrafwb.html

guard let x = opt else { return }
来源：http://dali.meibo888.top/Article/details/gt2clsmcxuf.html

[T30] Swift：协议
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eedvxygs.html

protocol Shape { func area() -> Double }
来源：http://dali.tanke756.top/Article/details/gt2msjsdayy.html

[T31] Lua：Hello World
来源：http://dali.yj20258888.top/Article/details/gt2eyecuacd.html

print("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gt2dckywodv.html

[T32] Lua：局部变量
来源：http://dali.andypj.xyz/Article/details/gt2ysmtnzuo.html

local a = 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mbhladox.html

[T33] Lua：表（数组）
来源：http://dali.zycfv.cn/Article/details/gt2uljqcdtc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zdqjudy.top/Article/details/gt2unwffxnw.html

[T34] Lua：遍历表
来源：http://dali.svipenyu.cn/Article/details/gt2qtadhafi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.andypj.xyz/Article/details/gt2vhthxyqn.html

[T35] Lua：字典表
来源：http://dali.sysykeji.top/Article/details/gt2hxoxzcja.html

local d = { a = 1 };  d.b = 2
来源：http://dali.havefunace.top/Article/details/gt2hzafblwj.html

[T36] Lua：函数
来源：http://dali.cdnleiting.top/Article/details/gt2zqmilqoj.html

function add(a, b) return a + b end
来源：http://dali.pengpengdd.cyou/Article/details/gt2yohabstn.html

[T37] Lua：字符串拼接
来源：http://dali.yonumen.top/Article/details/gt2xxswwkkp.html

"a" .. "b"
来源：http://dali.zhengqikj.top/Article/details/gt2zxtybnik.html

[T38] Lua：条件
来源：http://dali.zhongyouzk.top/Article/details/gt2yggumodb.html

if x > 0 then print("正") end
来源：http://dali.yangfankeji.com/Article/details/gt2dgufzhff.html

[T39] Lua：模式匹配
来源：http://dali.jinqigfzy.top/Article/details/gt2focnzhmw.html

string.find(s, "%d+")
来源：http://dali.316326.xyz/Article/details/gt2witpcmbo.html

[T40] Lua：元表
来源：http://dali.fengsongda.top/Article/details/gt2sfvxevpi.html

setmetatable({}, { __index = base })
来源：http://dali.yangfankeji.com/Article/details/gt2oixmvees.html

[T41] Perl：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2dcjrvqbp.html

print "Hello\n";
来源：http://dali.jinqigfzy.top/Article/details/gt2eqrbisnv.html

[T42] Perl：变量类型
来源：http://dali.hnxiangtu.top/Article/details/gt2nflnvknv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.chenzaomai.com/Article/details/gt2yiltriuy.html

[T43] Perl：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gt2vialvihg.html

"值: $a"
来源：http://dali.ybcxt.top/Article/details/gt2tevexpgw.html

[T44] Perl：条件
来源：http://dali.bjfxy.top/Article/details/gt2ioacrwns.html

if ($a > 0) { print "正"; }
来源：http://dali.nanxinkj.top/Article/details/gt2vjctyzyj.html

[T45] Perl：数组遍历
来源：http://dali.yueranfly.top/Article/details/gt2nsoxjiit.html

for my $x (@arr) { print $x; }
来源：http://dali.kuanghao11.cn/Article/details/gt2zjlzjeww.html

[T46] Perl：哈希操作
来源：http://dali.smart0.xyz/Article/details/gt2mcduzpxj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jqgfzy.top/Article/details/gt2zhhmupnt.html

[T47] Perl：正则捕获
来源：http://dali.zhongyouzk.top/Article/details/gt2zjbysnwn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yangfankeji.com/Article/details/gt2lxocctuy.html

[T48] Perl：正则替换
来源：http://dali.havefunace.top/Article/details/gt2avpvgrtk.html

$s =~ s/old/new/g;
来源：http://dali.tanke756.top/Article/details/gt2tldmxuen.html

[T49] Perl：函数
来源：http://dali.vqdsnc.cn/Article/details/gt2pyecxegt.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gt2wbfjqlep.html

[T50] Perl：逐行读文件
来源：http://dali.yongpay.top/Article/details/gt2atcqkztm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.snrcjt.cn/Article/details/gt2kfgbnxxi.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.svipenyu.cn/Article/details/gt2tjxgnkaw.html

[T51] Scala：Hello World
来源：http://dali.jiagoushi.top/Article/details/gt2xqkgygqj.html

println("Hello")
来源：http://dali.nanxinkj.top/Article/details/gt2okewmgpy.html

[T52] Scala：变量
来源：http://dali.sweek.top/Article/details/gt2ipksvwfb.html

val a = 1;  var b = 2
来源：http://dali.meibo888.top/Article/details/gt2dfeqohdm.html

[T53] Scala：字符串插值
来源：http://dali.guannengcc.top/Article/details/gt2murbsxpl.html

s"值: $b"
来源：http://dali.ydzc1.top/Article/details/gt2atwouevl.html

[T54] Scala：集合映射
来源：http://dali.9152youxi.cn/Article/details/gt2zxjzmram.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.snrcjt.cn/Article/details/gt2vcmosjml.html

[T55] Scala：集合过滤
来源：http://dali.cheryme.top/Article/details/gt2wtcauvzr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yj20258888.top/Article/details/gt2sovkrjmd.html

[T56] Scala：样例类
来源：http://dali.bjfxy.top/Article/details/gt2quhdrayc.html

case class User(name: String, age: Int)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qrnzhpbr.html

[T57] Scala：模式匹配
来源：http://dali.vqdsnc.cn/Article/details/gt2xskjgqay.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hywenlv.cn/Article/details/gt2doizxsvy.html

[T58] Scala：函数定义
来源：http://dali.chenjidiqi.icu/Article/details/gt2lsmvlbul.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wclqzwnm.html

[T59] Scala：循环
来源：http://dali.cashguo.top/Article/details/gt2pdvogveb.html

for (i <- 1 to 10) println(i)
来源：http://dali.snrcjt.cn/Article/details/gt2qxfuhocw.html

[T60] Scala：折叠
来源：http://dali.yangfankeji.com/Article/details/gt2mayexdgj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.nanxuanxn.top/Article/details/gt2sajbcesf.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2vhgzqfxw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.iojbl.cn/Article/details/gt2thzpjacq.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2htzeqdpj.html

[U01] Py：创建虚拟环境
来源：http://dali.xziqi.cn/Article/details/gt2ztahwgaj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xuetiantiany.cn/Article/details/gt2mdrghsjw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hnxiangtu.top/Article/details/gt2akvrfxka.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jqgfzy.top/Article/details/gt2jrnwtiak.html

[U03] Py：加载 .env 配置
来源：http://dali.smart0.xyz/Article/details/gt2bzcdydii.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xuanzx.com/Article/details/gt2kyqyffhz.html

[U04] Py：变量调试打印
来源：http://dali.vqdsnc.cn/Article/details/gt2uimftumf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yueranfly.top/Article/details/gt2eynkxaqc.html

[U05] Py：列表去重且保序
来源：http://dali.zdqjudy.top/Article/details/gt2vuayhmip.html

list(dict.fromkeys(arr))
来源：http://dali.havefunace.top/Article/details/gt2zingtflk.html

[U06] Py：合并两个字典
来源：http://dali.shangyingyoupin.top/Article/details/gt2mgclurkf.html

{**a, **b}
来源：http://dali.chenlongwang.top/Article/details/gt2ltfkibas.html

[U07] Py：反转字典键值
来源：http://dali.jlsjyb.cn/Article/details/gt2ofykmsii.html

{v: k for k, v in d.items()}
来源：http://dali.yangfankeji.com/Article/details/gt2stuookhz.html

[U08] Py：展平二维列表
来源：http://dali.redwolf501.top/Article/details/gt2uksvotyo.html

[y for x in nested for y in x]
来源：http://dali.nanxinkj.top/Article/details/gt2gwcmenkx.html

[U09] Py：字典取最大值的键
来源：http://dali.gogol.net.cn/Article/details/gt2hdqmwtag.html

max(d, key=d.get)
来源：http://dali.yonumen.top/Article/details/gt2jymbinbo.html

[U10] Py：按值排序字典
来源：http://dali.gaohongyu789.top/Article/details/gt2tswrymtf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yj20258888.top/Article/details/gt2txoxrlnu.html

[U11] Py：生成器表达式
来源：http://dali.tanke756.top/Article/details/gt2hjqxntqu.html

(x * 2 for x in arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oaswiyzk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.wangshuangyany.cn/Article/details/gt2owxrbvgs.html

Counter(arr).most_common(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2beegjniz.html


<!-- 参考信息 -->