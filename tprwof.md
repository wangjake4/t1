代发 wailian999

head -c 16 /dev/urandom | base64
来源：http://dali.chenzaomai.com/Article/details/gt2zhxxnzar.html

[R70] 时间戳与互转
来源：http://dali.sweek.top/Article/details/gt2dpttvqji.html

date +%s;  date -d @1700000000
来源：http://dali.tianlin.xyz/Article/details/gt2ypbzmgly.html

[R71] 日期格式化
来源：http://dali.aizwys.cn/Article/details/gt2ftnweuhu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ppjwa.cn/Article/details/gt2wodulkpe.html

[R72] 等待端口就绪
来源：http://dali.0kj1m.cn/Article/details/gt2onvxwehr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhoulong.xyz/Article/details/gt2ulyreswu.html

[R73] 分割大日志
来源：http://dali.andypj.xyz/Article/details/gt2mbgkprfv.html

split -l 1000 big.log part_
来源：http://dali.haohaochexian.top/Article/details/gt2lfvugkcy.html

[R74] 批量重命名
来源：http://dali.snrcjt.cn/Article/details/gt2ujdkvvbc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sgbytdzq.html

[R75] 导出环境变量
来源：http://dali.aibaodan.cn/Article/details/gt2tobghtyw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhoulong.xyz/Article/details/gt2jjmvfijy.html

[R76] 使用临时文件
来源：http://dali.xinyue.icu/Article/details/gt2giownvbf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gaohongyu789.top/Article/details/gt2qfydznpj.html

[R77] 读取用户输入
来源：http://dali.pycfn.com/Article/details/gt2jkmhxrto.html

read -rp "请输入: " ans
来源：http://dali.xziqi.cn/Article/details/gt2fvlgheee.html

[R78] 交互式菜单
来源：http://dali.fzhhl.top/Article/details/gt2bewszhnr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.wangdashe.top/Article/details/gt2jmeuvptm.html

[R79] 解析命令行选项
来源：http://dali.havefunace.top/Article/details/gt2gceslxdp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hammf.cn/Article/details/gt2xlmfwulv.html

[R80] 查看脚本执行耗时
来源：http://dali.zdqjudy.top/Article/details/gt2wefwftmr.html

time ./run.sh
来源：http://dali.ehwqpu.com/Article/details/gt2duqiuooc.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2qrhuswkl.html

S. C / C++ 专题
来源：http://dali.ehwqpu.com/Article/details/gt2zkrwaqvz.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2cmtgkmjx.html

[S01] C：Hello World
来源：http://dali.shzxlz.cn/Article/details/gt2pyveavco.html

#include <stdio.h>
来源：http://dali.zhoulong.xyz/Article/details/gt2pikvzpco.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hywenlv.cn/Article/details/gt2xuzsntis.html

[S02] C：变量与格式化输出
来源：http://dali.jyoumei.cn/Article/details/gt2okdifmbh.html

int a = 10; printf("%d\n", a);
来源：http://dali.jqgfzy.top/Article/details/gt2ytlpwdji.html

[S03] C：读入整数
来源：http://dali.pycfn.com/Article/details/gt2kpvayxad.html

int x; scanf("%d", &x);
来源：http://dali.fzhhl.top/Article/details/gt2cajaoprr.html

[S04] C：字符串复制
来源：http://dali.cucudq.cn/Article/details/gt2mtnvgsnc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gt2fveljweh.html

[S05] C：字符串长度
来源：http://dali.jiagoushi.top/Article/details/gt2nasqfgcm.html

strlen(s)
来源：http://dali.jianghu66.top/Article/details/gt2hgvdwovi.html

[S06] C：字符串比较
来源：http://dali.jiagoushi.top/Article/details/gt2cqoavvvf.html

strcmp(a, b) == 0
来源：http://dali.yongpay.top/Article/details/gt2kionxjfg.html

[S07] C：数组遍历求和
来源：http://dali.jiagoushi.top/Article/details/gt2szjqycmv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.daria6918.cn/Article/details/gt2ncxqxwbp.html

[S08] C：动态内存分配与释放
来源：http://dali.xziqi.cn/Article/details/gt2wpxftvoc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gaohongyu789.top/Article/details/gt2hhyqptnv.html

[S09] C：结构体定义与初始化
来源：http://dali.hammf.cn/Article/details/gt2wrzrnjab.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zycfv.cn/Article/details/gt2pyydgbcl.html

[S10] C：指针与解引用
来源：http://dali.yueranfly.top/Article/details/gt2bwmsqixz.html

int *p = &a;  *p = 5;
来源：http://dali.haohaochexian.top/Article/details/gt2kdselzwo.html

[S11] C：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gt2wusdejri.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yuxming.cn/Article/details/gt2laxbsawy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.c1oappe.top/Article/details/gt2adjqznat.html

fclose(f);
来源：http://dali.yongpay.top/Article/details/gt2oxlawshz.html

[S12] C：写文件
来源：http://dali.guannengcc.top/Article/details/gt2rfmowbdd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gotoacloud.top/Article/details/gt2ukcmueqt.html

[S13] C：宏定义
来源：http://dali.pycfn.com/Article/details/gt2alrbgugn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nwbrower.top/Article/details/gt2pnjdhwva.html

[S14] C：枚举
来源：http://dali.yongpay.top/Article/details/gt2aapbhquz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.havefunace.top/Article/details/gt2kxafdmcb.html

[S15] C：类型转换
来源：http://dali.nwbrower.top/Article/details/gt2nrdinsdh.html

(double) a / b
来源：http://dali.yueranfly.top/Article/details/gt2yewvwnaz.html

[S16] C：位操作置位
来源：http://dali.jqgfzy.top/Article/details/gt2tfsooxhm.html

x |= (1 << 3);
来源：http://dali.9152youxi.cn/Article/details/gt2zgmrypzl.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wmpelakc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xziqi.cn/Article/details/gt2tlnckssb.html

[S18] C：命令行参数
来源：http://dali.bjfxy.top/Article/details/gt2blbvwvyg.html

int main(int argc, char **argv)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xllooteo.html

[S19] C：快速排序
来源：http://dali.xinyue.icu/Article/details/gt2lxnpnheg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hfpthk.cn/Article/details/gt2drueanlp.html

[S20] C：二分查找
来源：http://dali.shzxlz.cn/Article/details/gt2ncqybwdo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nanxinkj.top/Article/details/gt2vvrdmjvh.html

[S21] C：字符类别判断
来源：http://dali.snrcjt.cn/Article/details/gt2uwhglggy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xuanzx.com/Article/details/gt2xwdkjncg.html

[S22] C：字符串转数字
来源：http://dali.cucudq.cn/Article/details/gt2iqpyfcex.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yangfankeji.com/Article/details/gt2nvtmlpmb.html

[S23] C：随机数
来源：http://dali.kuanghao11.cn/Article/details/gt2dwpqtosl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hfpthk.cn/Article/details/gt2ooistkjp.html

[S24] C：获取本地时间
来源：http://dali.hongshengwenyu.top/Article/details/gt2ifbrmees.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.dianchejie.cn/Article/details/gt2ykjgaomh.html

[S25] C：内存拷贝
来源：http://dali.guowangkeji.top/Article/details/gt2bmrflhqi.html

memcpy(dst, src, n);
来源：http://dali.xziqi.cn/Article/details/gt2gijdfdmv.html

[S26] C：内存清零
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hplquwau.html

memset(a, 0, sizeof a);
来源：http://dali.gotoacloud.top/Article/details/gt2tnbkszck.html

[S27] C：定义常量
来源：http://dali.guannengcc.top/Article/details/gt2pqcxqtmd.html

const double PI = 3.14159;
来源：http://dali.aizwys.cn/Article/details/gt2fppkmusw.html

[S28] C：静态变量
来源：http://dali.zhoulong.xyz/Article/details/gt2nnnafniq.html

static int counter = 0;
来源：http://dali.jqgufenzy.top/Article/details/gt2eqrsvcmd.html

[S29] C：变参函数
来源：http://dali.316326.xyz/Article/details/gt2fvifvcso.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.havefunace.top/Article/details/gt2htgwxzef.html

[S30] C：头文件保护
来源：http://dali.snrcjt.cn/Article/details/gt2pkjaento.html

#ifndef X_H
来源：http://dali.zhengqikj.top/Article/details/gt2kjgjgzpz.html

#define X_H
来源：http://dali.guowangkeji.top/Article/details/gt2rwwiepxz.html

#endif
来源：http://dali.nanxuanxn.top/Article/details/gt2ojdbcnpv.html

[S31] C++：Hello World
来源：http://dali.daxiang520.top/Article/details/gt2prkygqwr.html

#include <iostream>
来源：http://dali.tanke756.top/Article/details/gt2hmmbexpm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.birdmap.top/Article/details/gt2vmolksuy.html

[S32] C++：字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2ubvpoasj.html

std::string s = "hi";  s += "!";
来源：http://dali.cucudq.cn/Article/details/gt2yhkdfbom.html

[S33] C++：vector 增删
来源：http://dali.gotoacloud.top/Article/details/gt2eiiosiqd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.dianchejie.cn/Article/details/gt2zufamtej.html

[S34] C++：遍历 vector
来源：http://dali.xinyue.icu/Article/details/gt2hmnjewpf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2mbgoejdl.html

[S35] C++：map
来源：http://dali.sufxvd.cn/Article/details/gt2zmknkvas.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gt2ykpwacpq.html

[S36] C++：unordered_map
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oegtalzu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gt2jhmrkejd.html

[S37] C++：set
来源：http://dali.9152youxi.cn/Article/details/gt2zqiyarqj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yonumen.top/Article/details/gt2yatkwxae.html

[S38] C++：排序
来源：http://dali.chenzaomai.com/Article/details/gt2girfcodn.html

std::sort(v.begin(), v.end());
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qxyysyfd.html

[S39] C++：自定义比较器排序
来源：http://dali.yuxming.cn/Article/details/gt2tvjvydcn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yongpay.top/Article/details/gt2peubwwqo.html

[S40] C++：查找元素
来源：http://dali.zdqjudy.top/Article/details/gt2knjbvhwv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.tianlin.xyz/Article/details/gt2dcdpgjyp.html

[S41] C++：类与构造函数
来源：http://dali.hfpthk.cn/Article/details/gt2tsswjojv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sweek.top/Article/details/gt2yixdtpei.html

[S42] C++：继承与虚函数
来源：http://dali.wangdashe.top/Article/details/gt2hcttqtsi.html

class B : public Base { public: void f() override {} };
来源：http://dali.guannengcc.top/Article/details/gt2mkblgtrb.html

[S43] C++：智能指针
来源：http://dali.gzhubu.top/Article/details/gt2rbpclrvp.html

auto p = std::make_unique<int>(5);
来源：http://dali.dianchejie.cn/Article/details/gt2kgceiqff.html

[S44] C++：引用传参
来源：http://dali.chenjidiqi.icu/Article/details/gt2buckyuwy.html

void inc(int &x) { ++x; }
来源：http://dali.tian-w.cn/Article/details/gt2gbzzdjhl.html

[S45] C++：lambda
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bcuawvxc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhengqikj.top/Article/details/gt2rxyiaxyj.html

[S46] C++：函数模板
来源：http://dali.hywenlv.cn/Article/details/gt2yeihizqm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hiaitnjc.html

[S47] C++：结构化绑定遍历
来源：http://dali.xuanzx.com/Article/details/gt2phwvljce.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zycfv.cn/Article/details/gt2chixglry.html

[S48] C++：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2etwfgurz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gzhubu.top/Article/details/gt2hdjovvbx.html

while (std::getline(in, line)) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hxafcvpi.html

[S49] C++：写文件
来源：http://dali.xinyue.icu/Article/details/gt2sctpohgc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.birdmap.top/Article/details/gt2cvolalti.html

[S50] C++：格式化数字
来源：http://dali.yangfankeji.com/Article/details/gt2rlhqxbfx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gt2tixjfjqn.html

[S51] C++：显式类型转换
来源：http://dali.xinyue.icu/Article/details/gt2zdarkdxb.html

static_cast<double>(a) / b
来源：http://dali.jqgfzy.top/Article/details/gt2oashrian.html

[S52] C++：const 与 noexcept
来源：http://dali.birdmap.top/Article/details/gt2kqvoxdvj.html

int size() const noexcept { return n_; }
来源：http://dali.yj20258.top/Article/details/gt2bdoxarln.html

[S53] C++：移动语义
来源：http://dali.snrcjt.cn/Article/details/gt2onfixnou.html

std::vector<int> w = std::move(v);
来源：http://dali.yuanzhike.top/Article/details/gt2lqainnet.html

[S54] C++：异常处理
来源：http://dali.gotoacloud.top/Article/details/gt2xrwtwmmd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nnohgozt.html

[S55] C++：结构化绑定
来源：http://dali.zhoulong.xyz/Article/details/gt2vybvsnao.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.pengpengdd.cyou/Article/details/gt2qxicbmel.html

[S56] C++：optional
来源：http://dali.hysaishi.cn/Article/details/gt2kcjsqgzo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cucudq.cn/Article/details/gt2kanculka.html

[S57] C++：编译期常量
来源：http://dali.gaohongyu789.top/Article/details/gt2nlbbyzyd.html

constexpr int N = 10;
来源：http://dali.jinqigufen.top/Article/details/gt2ujdnxpjl.html

[S58] C++：命名空间
来源：http://dali.yangfankeji.com/Article/details/gt2kinjjsux.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj20258888.top/Article/details/gt2xmurjneb.html

[S59] C++：静态断言
来源：http://dali.jqgufenzy.top/Article/details/gt2ljxlodbf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cheryme.top/Article/details/gt2nehgirov.html

[S60] C++：遍历并删除元素
来源：http://dali.tianlin.xyz/Article/details/gt2djndutac.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj20258.top/Article/details/gt2ciawrxny.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2cmywrrpe.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xylfe.cn/Article/details/gt2bkuyloni.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2nzkxvnyn.html

[T01] Kotlin：Hello World
来源：http://dali.zycfv.cn/Article/details/gt2zgahcqan.html

println("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mjxtlzgh.html

[T02] Kotlin：变量
来源：http://dali.cdnleiting.top/Article/details/gt2putowfyd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.havefunace.top/Article/details/gt2uswgmzlj.html

[T03] Kotlin：字符串模板
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zhoiyaoi.html

"值: $b"
来源：http://dali.nwbrower.top/Article/details/gt2cdwmgwnq.html

[T04] Kotlin：空安全
来源：http://dali.cqqwz.cn/Article/details/gt2bzjxfglb.html

val n: String? = null;  n?.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vfxvtypz.html

[T05] Kotlin：when 表达式
来源：http://dali.sweek.top/Article/details/gt2yiryydni.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.nanxuanxn.top/Article/details/gt2drwvhrtl.html

[T06] Kotlin：集合映射
来源：http://dali.jlsjyb.cn/Article/details/gt2nshqrbcq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2gnpmnhss.html

[T07] Kotlin：集合过滤
来源：http://dali.hongshengwenyu.top/Article/details/gt2dznoowba.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cashguo.top/Article/details/gt2jpqaeyhp.html

[T08] Kotlin：数据类
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ekjckezr.html

data class User(val name: String, val age: Int)
来源：http://dali.316326.xyz/Article/details/gt2rnqevpvq.html

[T09] Kotlin：扩展函数
来源：http://dali.hammf.cn/Article/details/gt2phmnilzb.html

fun String.exclaim() = this + "!"
来源：http://dali.birdmap.top/Article/details/gt2voecniqp.html

[T10] Kotlin：默认参数
来源：http://dali.sysykeji.top/Article/details/gt2ggxwtzwn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.havefunace.top/Article/details/gt2wzhdbjgs.html

[T11] Kotlin：协程
来源：http://dali.chenjidiqi.icu/Article/details/gt2vtwfgevg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.dianchejie.cn/Article/details/gt2lygobfeh.html

[T12] Kotlin：解构声明
来源：http://dali.xuanzx.com/Article/details/gt2bzmqbwkd.html

val (a, b) = Pair(1, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2phohggfi.html

[T13] Kotlin：只读 Map
来源：http://dali.ehwqpu.com/Article/details/gt2jkxjgztp.html

val m = mapOf("a" to 1)
来源：http://dali.zycfv.cn/Article/details/gt2dojqnwxb.html

[T14] Kotlin：循环
来源：http://dali.0kj1m.cn/Article/details/gt2mvvkxteo.html

for (i in 1..10) println(i)
来源：http://dali.zhengqikj.top/Article/details/gt2yejysqvt.html

[T15] Kotlin：接口
来源：http://dali.jinqigufen.top/Article/details/gt2uokowmcd.html

interface Shape { fun area(): Double }
来源：http://dali.ehwqpu.com/Article/details/gt2ccbqcgoa.html

[T16] Swift：Hello World
来源：http://dali.chenlongwang.top/Article/details/gt2axpamlpb.html

print("Hello")
来源：http://dali.guowangkeji.top/Article/details/gt2vncxrybq.html

[T17] Swift：变量与常量
来源：http://dali.gotoacloud.top/Article/details/gt2dintkffl.html

var a = 1;  let b = 2
来源：http://dali.pengpengdd.cyou/Article/details/gt2azvhnbzi.html

[T18] Swift：字符串插值
来源：http://dali.sysykeji.top/Article/details/gt2itvbeqbv.html

"值: \(b)"
来源：http://dali.havefunace.top/Article/details/gt2cjutdjdu.html

[T19] Swift：可选绑定
来源：http://dali.ybcxt.top/Article/details/gt2lwceogxq.html

if let n = opt { print(n) }
来源：http://dali.jianghu66.top/Article/details/gt2twdxfgat.html

[T20] Swift：数组操作
来源：http://dali.feifeiyinyue.top/Article/details/gt2gbpnxyrr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.bjfxy.top/Article/details/gt2zyylmzsg.html

[T21] Swift：遍历
来源：http://dali.meibo888.top/Article/details/gt2qkcrqmgu.html

for x in a { print(x) }
来源：http://dali.haohaochexian.top/Article/details/gt2qliiosrq.html

[T22] Swift：字典
来源：http://dali.hywenlv.cn/Article/details/gt2eogjnpan.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ydzc1.top/Article/details/gt2lboeriew.html

[T23] Swift：函数
来源：http://dali.cdnleiting.top/Article/details/gt2gfwitmwb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iyppjbuk.html

[T24] Swift：闭包
来源：http://dali.jyoumei.cn/Article/details/gt2iimrzepp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ynrwuzst.html

[T25] Swift：结构体
来源：http://dali.gaohongyu789.top/Article/details/gt2shfmrjgf.html

struct P { var x: Int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hdhnzgjy.html

[T26] Swift：类与重写
来源：http://dali.ydzc1.top/Article/details/gt2pcubjcij.html

class A: Base { override func f() {} }
来源：http://dali.c1oappe.top/Article/details/gt2zldemajk.html

[T27] Swift：错误处理
来源：http://dali.nanxinkj.top/Article/details/gt2vujqkexi.html

do { try f() } catch { print(error) }
来源：http://dali.tianlin.xyz/Article/details/gt2lvxoajyk.html

[T28] Swift：枚举
来源：http://dali.meibo888.top/Article/details/gt2juxjewml.html

enum Color { case red, green }
来源：http://dali.jlsjyb.cn/Article/details/gt2pucdrjds.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2wmpwwbir.html

guard let x = opt else { return }
来源：http://dali.guannengcc.top/Article/details/gt2ndyqfieo.html

[T30] Swift：协议
来源：http://dali.bjfxy.top/Article/details/gt2jgqcruvw.html

protocol Shape { func area() -> Double }
来源：http://dali.yonumen.top/Article/details/gt2uzjnuwvq.html

[T31] Lua：Hello World
来源：http://dali.fzhhl.top/Article/details/gt2kzghlcmd.html

print("Hello")
来源：http://dali.zhiwuduotai.top/Article/details/gt2jvugsrno.html

[T32] Lua：局部变量
来源：http://dali.dianchejie.cn/Article/details/gt2isbwuhuo.html

local a = 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uyszbvdw.html

[T33] Lua：表（数组）
来源：http://dali.gotoacloud.top/Article/details/gt2tsrcogci.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shuidangran.top/Article/details/gt2niftukkb.html

[T34] Lua：遍历表
来源：http://dali.sweek.top/Article/details/gt2kxstsjnv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xuetiantiany.cn/Article/details/gt2bubplixx.html

[T35] Lua：字典表
来源：http://dali.cashguo.top/Article/details/gt2eangssht.html

local d = { a = 1 };  d.b = 2
来源：http://dali.daria6918.cn/Article/details/gt2vkzvvvcn.html

[T36] Lua：函数
来源：http://dali.fengsongda.top/Article/details/gt2gwfaynhm.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2eaplltpa.html

[T37] Lua：字符串拼接
来源：http://dali.fengsongda.top/Article/details/gt2qrmycars.html

"a" .. "b"
来源：http://dali.yvedp.cn/Article/details/gt2gllfxfet.html

[T38] Lua：条件
来源：http://dali.shangyingyoupin.top/Article/details/gt2pmswhlzl.html

if x > 0 then print("正") end
来源：http://dali.shuidangran.top/Article/details/gt2mytnwlth.html

[T39] Lua：模式匹配
来源：http://dali.gzhubu.top/Article/details/gt2szlxiutw.html

string.find(s, "%d+")
来源：http://dali.guowangkeji.top/Article/details/gt2yowhwuqi.html

[T40] Lua：元表
来源：http://dali.ivvv.top/Article/details/gt2rcykeuih.html

setmetatable({}, { __index = base })
来源：http://dali.shuidangran.top/Article/details/gt2majymwge.html

[T41] Perl：Hello World
来源：http://dali.cucudq.cn/Article/details/gt2uzjoxhgf.html

print "Hello\n";
来源：http://dali.ppjwa.cn/Article/details/gt2ojyazguo.html

[T42] Perl：变量类型
来源：http://dali.daxiang520.top/Article/details/gt2lpbrxkjw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.aizwys.cn/Article/details/gt2ugvcrieu.html

[T43] Perl：字符串插值
来源：http://dali.9152youxi.cn/Article/details/gt2qlhzqxbp.html

"值: $a"
来源：http://dali.yj20258888.top/Article/details/gt2ccmqobpy.html

[T44] Perl：条件
来源：http://dali.jyoumei.cn/Article/details/gt2azznslns.html

if ($a > 0) { print "正"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yvorbeng.html

[T45] Perl：数组遍历
来源：http://dali.yangfankeji.com/Article/details/gt2hriimazn.html

for my $x (@arr) { print $x; }
来源：http://dali.zycfv.cn/Article/details/gt2cosekoxn.html

[T46] Perl：哈希操作
来源：http://dali.haohaochexian.top/Article/details/gt2izjfmekl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zycfv.cn/Article/details/gt2wsufywiq.html

[T47] Perl：正则捕获
来源：http://dali.zhixingplan.top/Article/details/gt2bksjuvxl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.guannengcc.top/Article/details/gt2kokotnxu.html

[T48] Perl：正则替换
来源：http://dali.yuxming.cn/Article/details/gt2wmeefabe.html

$s =~ s/old/new/g;
来源：http://dali.nwbrower.top/Article/details/gt2pwmymnvu.html

[T49] Perl：函数
来源：http://dali.pycfn.com/Article/details/gt2ubjtdpkk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gt2irdejdwh.html

[T50] Perl：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gt2obhsvryw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2swwvugxs.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yuxming.cn/Article/details/gt2etddknax.html

[T51] Scala：Hello World
来源：http://dali.jyoumei.cn/Article/details/gt2zmwcvmtv.html

println("Hello")
来源：http://dali.jyoumei.cn/Article/details/gt2dnrqlbwg.html

[T52] Scala：变量
来源：http://dali.zhongyouzk.top/Article/details/gt2gbrdrkly.html

val a = 1;  var b = 2
来源：http://dali.sufxvd.cn/Article/details/gt2rdkzword.html

[T53] Scala：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gt2gnbsxthl.html

s"值: $b"
来源：http://dali.0kj1m.cn/Article/details/gt2rmuawdla.html

[T54] Scala：集合映射
来源：http://dali.zhengqikj.top/Article/details/gt2qnlilkts.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.nanxinkj.top/Article/details/gt2dalhbmkk.html

[T55] Scala：集合过滤
来源：http://dali.nwbrower.top/Article/details/gt2znvahqcl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.dianchejie.cn/Article/details/gt2ldtcjhrw.html

[T56] Scala：样例类
来源：http://dali.shzxlz.cn/Article/details/gt2jrbxtypn.html

case class User(name: String, age: Int)
来源：http://dali.ehwqpu.com/Article/details/gt2ssuvgzzq.html

[T57] Scala：模式匹配
来源：http://dali.aizwys.cn/Article/details/gt2gmjjxthb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhongyouzk.top/Article/details/gt2audblhjj.html

[T58] Scala：函数定义
来源：http://dali.cqqwz.cn/Article/details/gt2nfsznebb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yanxiufei.cn/Article/details/gt2bzykqthm.html

[T59] Scala：循环
来源：http://dali.dashuyun.cn/Article/details/gt2quboluxk.html

for (i <- 1 to 10) println(i)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qgalarzo.html

[T60] Scala：折叠
来源：http://dali.dashuyun.cn/Article/details/gt2pyljhytw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.iojbl.cn/Article/details/gt2rbjrpeat.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2xkudgqsd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hongshengwenyu.top/Article/details/gt2lluliczt.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2pxpjnqgp.html

[U01] Py：创建虚拟环境
来源：http://dali.tianlin.xyz/Article/details/gt2owzaqspt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jqgufenzy.top/Article/details/gt2tvibjzgh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ehwqpu.com/Article/details/gt2ueoaauft.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gotoacloud.top/Article/details/gt2zcnfxeio.html

[U03] Py：加载 .env 配置
来源：http://dali.daxiang520.top/Article/details/gt2gtapossx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.shuidangran.top/Article/details/gt2ruvryduv.html

[U04] Py：变量调试打印
来源：http://dali.jqgfzy.top/Article/details/gt2xzxqludq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgsztvz.html

[U05] Py：列表去重且保序
来源：http://dali.zdqjudy.top/Article/details/gt2axikbcfk.html

list(dict.fromkeys(arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jhilyrsd.html

[U06] Py：合并两个字典
来源：http://dali.yanxiufei.cn/Article/details/gt2lhejtxyl.html

{**a, **b}
来源：http://dali.birdmap.top/Article/details/gt2bisnipwh.html

[U07] Py：反转字典键值
来源：http://dali.daria6918.cn/Article/details/gt2igjuusis.html

{v: k for k, v in d.items()}
来源：http://dali.jqgufenzy.top/Article/details/gt2pjknrktg.html

[U08] Py：展平二维列表
来源：http://dali.pycfn.com/Article/details/gt2bddntrwl.html

[y for x in nested for y in x]
来源：http://dali.hammf.cn/Article/details/gt2uuiaqzme.html

[U09] Py：字典取最大值的键
来源：http://dali.haohaochexian.top/Article/details/gt2xcnzrswf.html

max(d, key=d.get)
来源：http://dali.hammf.cn/Article/details/gt2qlsfughd.html

[U10] Py：按值排序字典
来源：http://dali.tian-w.cn/Article/details/gt2duagfabi.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhongyouzk.top/Article/details/gt2vzhskukb.html


<!-- 参考信息 -->