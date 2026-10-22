代发 wailian999

export PATH="$HOME/bin:$PATH"
来源：http://dali.316326.xyz/Article/details/gt2qzuwbkqf.html

[R76] 使用临时文件
来源：http://dali.yj20258.top/Article/details/gt2kignxxeg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuetiantiany.cn/Article/details/gt2yeuxvcdm.html

[R77] 读取用户输入
来源：http://dali.316326.xyz/Article/details/gt2yowavrxz.html

read -rp "请输入: " ans
来源：http://dali.tianlin.xyz/Article/details/gt2ylpwkgku.html

[R78] 交互式菜单
来源：http://dali.dashuyun.cn/Article/details/gt2dzlwhjvb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.smart0.xyz/Article/details/gt2rnjefdnt.html

[R79] 解析命令行选项
来源：http://dali.xinyue.icu/Article/details/gt2dbjrxkyg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hysaishi.cn/Article/details/gt2ewmhkxsw.html

[R80] 查看脚本执行耗时
来源：http://dali.meibo888.top/Article/details/gt2lyrctekq.html

time ./run.sh
来源：http://dali.yj202588.top/Article/details/gt2qxatbdln.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2olhisxqb.html

S. C / C++ 专题
来源：http://dali.quarkkingdee.top/Article/details/gt2zxnhuecf.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2ykxluueq.html

[S01] C：Hello World
来源：http://dali.wangdashe.top/Article/details/gt2cekelkim.html

#include <stdio.h>
来源：http://dali.yueranfly.top/Article/details/gt2cxpnwusq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yblkxaqt.html

[S02] C：变量与格式化输出
来源：http://dali.fengsongda.top/Article/details/gt2abdjgqvp.html

int a = 10; printf("%d\n", a);
来源：http://dali.meibo888.top/Article/details/gt2lrivbgib.html

[S03] C：读入整数
来源：http://dali.tian-w.cn/Article/details/gt2nmqawyag.html

int x; scanf("%d", &x);
来源：http://dali.sysykeji.top/Article/details/gt2eekqteur.html

[S04] C：字符串复制
来源：http://dali.cdnleiting.top/Article/details/gt2jumpdldl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.smart0.xyz/Article/details/gt2ysmyvnmf.html

[S05] C：字符串长度
来源：http://dali.sysykeji.top/Article/details/gt2kdwfumyk.html

strlen(s)
来源：http://dali.yj20258.top/Article/details/gt2gisrdolu.html

[S06] C：字符串比较
来源：http://dali.wangshuangyany.cn/Article/details/gt2lfuuxlmc.html

strcmp(a, b) == 0
来源：http://dali.sysykeji.top/Article/details/gt2otavcxou.html

[S07] C：数组遍历求和
来源：http://dali.ybcxt.top/Article/details/gt2yjbppscn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yj202588.top/Article/details/gt2mehnywmc.html

[S08] C：动态内存分配与释放
来源：http://dali.redwolf501.top/Article/details/gt2wqmawhyv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oqrblsmp.html

[S09] C：结构体定义与初始化
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2horzaghg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gaohongyu789.top/Article/details/gt2waumpctk.html

[S10] C：指针与解引用
来源：http://dali.yangfankeji.com/Article/details/gt2rigrclpz.html

int *p = &a;  *p = 5;
来源：http://dali.birdmap.top/Article/details/gt2srpwztik.html

[S11] C：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gt2oqnwquvt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yuanzhike.top/Article/details/gt2yodtdeyi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hammf.cn/Article/details/gt2ydcjipmy.html

fclose(f);
来源：http://dali.zycfv.cn/Article/details/gt2gyagcjpa.html

[S12] C：写文件
来源：http://dali.jiagoushi.top/Article/details/gt2eepsnwns.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gt2slmbvsmu.html

[S13] C：宏定义
来源：http://dali.c1oappe.top/Article/details/gt2sdwucobh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhengqikj.top/Article/details/gt2nyrqfndi.html

[S14] C：枚举
来源：http://dali.yj20258888.top/Article/details/gt2tfmxjnaf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenjidiqi.icu/Article/details/gt2jwtsnkpg.html

[S15] C：类型转换
来源：http://dali.jqgufenzy.top/Article/details/gt2sattobiv.html

(double) a / b
来源：http://dali.yangfankeji.com/Article/details/gt2zwotcihs.html

[S16] C：位操作置位
来源：http://dali.yvedp.cn/Article/details/gt2rpmzmfpb.html

x |= (1 << 3);
来源：http://dali.nanxuanxn.top/Article/details/gt2fkkaldxw.html

[S17] C：安全拼接字符串
来源：http://dali.nwbrower.top/Article/details/gt2eqijesrz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cucudq.cn/Article/details/gt2zshzydha.html

[S18] C：命令行参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2pzdamcms.html

int main(int argc, char **argv)
来源：http://dali.shuidangran.top/Article/details/gt2bazgawun.html

[S19] C：快速排序
来源：http://dali.yuxming.cn/Article/details/gt2weeakdug.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.vqdsnc.cn/Article/details/gt2bnsxnloa.html

[S20] C：二分查找
来源：http://dali.smart0.xyz/Article/details/gt2quvyfkod.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jyoumei.cn/Article/details/gt2kucboxgk.html

[S21] C：字符类别判断
来源：http://dali.fengsongda.top/Article/details/gt2xzmlezkg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ybcxt.top/Article/details/gt2iwarbnjd.html

[S22] C：字符串转数字
来源：http://dali.hywenlv.cn/Article/details/gt2plhqqxnb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.fengsongda.top/Article/details/gt2kgmtmblp.html

[S23] C：随机数
来源：http://dali.jqgufenzy.top/Article/details/gt2gmfuccwx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pbxdyavn.html

[S24] C：获取本地时间
来源：http://dali.yanxiufei.cn/Article/details/gt2zvfulxlb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yuxming.cn/Article/details/gt2qkgmhcty.html

[S25] C：内存拷贝
来源：http://dali.wangshuangyany.cn/Article/details/gt2xyhstbmb.html

memcpy(dst, src, n);
来源：http://dali.yongpay.top/Article/details/gt2dttrxpqm.html

[S26] C：内存清零
来源：http://dali.yanxiufei.cn/Article/details/gt2dkeroiqg.html

memset(a, 0, sizeof a);
来源：http://dali.hnxiangtu.top/Article/details/gt2bhyvgose.html

[S27] C：定义常量
来源：http://dali.zycfv.cn/Article/details/gt2mzxorbxl.html

const double PI = 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ylklwtxy.html

[S28] C：静态变量
来源：http://dali.nanxinkj.top/Article/details/gt2icypymgi.html

static int counter = 0;
来源：http://dali.smart0.xyz/Article/details/gt2nqiszwcl.html

[S29] C：变参函数
来源：http://dali.smart0.xyz/Article/details/gt2egntojll.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.fengsongda.top/Article/details/gt2bwpiprel.html

[S30] C：头文件保护
来源：http://dali.c1oappe.top/Article/details/gt2cbhctijx.html

#ifndef X_H
来源：http://dali.sysykeji.top/Article/details/gt2ilcpiopd.html

#define X_H
来源：http://dali.jinqigfzy.top/Article/details/gt2vrjisiqi.html

#endif
来源：http://dali.pycfn.com/Article/details/gt2htkzlibg.html

[S31] C++：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gt2rdftmrqc.html

#include <iostream>
来源：http://dali.xinyue.icu/Article/details/gt2cfoaluwe.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.aizwys.cn/Article/details/gt2atjublnt.html

[S32] C++：字符串
来源：http://dali.yongpay.top/Article/details/gt2hjyaamjy.html

std::string s = "hi";  s += "!";
来源：http://dali.zycfv.cn/Article/details/gt2aupwhiby.html

[S33] C++：vector 增删
来源：http://dali.jqgufenzy.top/Article/details/gt2rhusbadm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.fengsongda.top/Article/details/gt2zplxptjq.html

[S34] C++：遍历 vector
来源：http://dali.zhengqikj.top/Article/details/gt2kgfihoww.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cashguo.top/Article/details/gt2fvmvavvy.html

[S35] C++：map
来源：http://dali.fzhhl.top/Article/details/gt2kprhyjll.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gt2xkrbsirj.html

[S36] C++：unordered_map
来源：http://dali.svipenyu.cn/Article/details/gt2mdubmkjh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daxiang520.top/Article/details/gt2apyshgaw.html

[S37] C++：set
来源：http://dali.jqgufenzy.top/Article/details/gt2herpixui.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nanxinkj.top/Article/details/gt2vgbbgneh.html

[S38] C++：排序
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gmiobwme.html

std::sort(v.begin(), v.end());
来源：http://dali.xylfe.cn/Article/details/gt2kinxsdwt.html

[S39] C++：自定义比较器排序
来源：http://dali.bjfxy.top/Article/details/gt2eqmiaocb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zdqjudy.top/Article/details/gt2ojhcvefx.html

[S40] C++：查找元素
来源：http://dali.haohaochexian.top/Article/details/gt2hyovtwmz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nanxuanxn.top/Article/details/gt2owyzxnvb.html

[S41] C++：类与构造函数
来源：http://dali.daria6918.cn/Article/details/gt2atvdsbad.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenjidiqi.icu/Article/details/gt2dqwwjvku.html

[S42] C++：继承与虚函数
来源：http://dali.meibo888.top/Article/details/gt2cdwuwkba.html

class B : public Base { public: void f() override {} };
来源：http://dali.yuxming.cn/Article/details/gt2soybgoar.html

[S43] C++：智能指针
来源：http://dali.jinqigufen.top/Article/details/gt2emondkdb.html

auto p = std::make_unique<int>(5);
来源：http://dali.shzxlz.cn/Article/details/gt2jpwshnlm.html

[S44] C++：引用传参
来源：http://dali.hywenlv.cn/Article/details/gt2nnnpdfba.html

void inc(int &x) { ++x; }
来源：http://dali.sweek.top/Article/details/gt2pkknjkot.html

[S45] C++：lambda
来源：http://dali.yanxiufei.cn/Article/details/gt2bbaiovuw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.mhx1999.top/Article/details/gt2sbngwgmo.html

[S46] C++：函数模板
来源：http://dali.0kj1m.cn/Article/details/gt2qcmzabbw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ydzc1.top/Article/details/gt2bqhaqwit.html

[S47] C++：结构化绑定遍历
来源：http://dali.jqgfzy.top/Article/details/gt2vbetirru.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2nvcahrrn.html

[S48] C++：逐行读文件
来源：http://dali.316326.xyz/Article/details/gt2qncvhrve.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.dashuyun.cn/Article/details/gt2rcdoiiwo.html

while (std::getline(in, line)) { }
来源：http://dali.fzhhl.top/Article/details/gt2hvsysdcl.html

[S49] C++：写文件
来源：http://dali.cucudq.cn/Article/details/gt2xftpsgpf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jyoumei.cn/Article/details/gt2rbzijylp.html

[S50] C++：格式化数字
来源：http://dali.c1oappe.top/Article/details/gt2xmammczz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cheryme.top/Article/details/gt2oyrthyqy.html

[S51] C++：显式类型转换
来源：http://dali.yonumen.top/Article/details/gt2tjbouelh.html

static_cast<double>(a) / b
来源：http://dali.zhoulong.xyz/Article/details/gt2ggpmvrps.html

[S52] C++：const 与 noexcept
来源：http://dali.316326.xyz/Article/details/gt2umiuuwwt.html

int size() const noexcept { return n_; }
来源：http://dali.birdmap.top/Article/details/gt2ququfvdj.html

[S53] C++：移动语义
来源：http://dali.zdqjudy.top/Article/details/gt2gghaugwt.html

std::vector<int> w = std::move(v);
来源：http://dali.yj20258.top/Article/details/gt2nzwvxtmg.html

[S54] C++：异常处理
来源：http://dali.ydzc1.top/Article/details/gt2jigpomhr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.feifeiyinyue.top/Article/details/gt2cakjxfiy.html

[S55] C++：结构化绑定
来源：http://dali.meibo888.top/Article/details/gt2lhljdmwx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.daxiang520.top/Article/details/gt2pjikzqdt.html

[S56] C++：optional
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jxsfxywq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2kgayvlfs.html

[S57] C++：编译期常量
来源：http://dali.jinqigufen.top/Article/details/gt2gmbfbdsm.html

constexpr int N = 10;
来源：http://dali.jinqigufen.top/Article/details/gt2hslykfrw.html

[S58] C++：命名空间
来源：http://dali.birdmap.top/Article/details/gt2dzkwunyd.html

namespace ns { int f() { return 1; } }
来源：http://dali.hysaishi.cn/Article/details/gt2yrlhhbvu.html

[S59] C++：静态断言
来源：http://dali.daxiang520.top/Article/details/gt2caosjhfw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.fengsongda.top/Article/details/gt2ukrgfxtq.html

[S60] C++：遍历并删除元素
来源：http://dali.zhoulong.xyz/Article/details/gt2mxeoaqzb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jlsjyb.cn/Article/details/gt2niexrwfz.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2jvrhqwsj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tian-w.cn/Article/details/gt2eqsmyrrr.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2dqresmrn.html

[T01] Kotlin：Hello World
来源：http://dali.hammf.cn/Article/details/gt2khdbbrba.html

println("Hello")
来源：http://dali.aibaodan.cn/Article/details/gt2hbgdfptp.html

[T02] Kotlin：变量
来源：http://dali.zycfv.cn/Article/details/gt2ndesjtjd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2syplzldd.html

[T03] Kotlin：字符串模板
来源：http://dali.wangdashe.top/Article/details/gt2cwovaipm.html

"值: $b"
来源：http://dali.jqgufenzy.top/Article/details/gt2pxkzqxng.html

[T04] Kotlin：空安全
来源：http://dali.yueranfly.top/Article/details/gt2vibemyds.html

val n: String? = null;  n?.length
来源：http://dali.pengpengdd.cyou/Article/details/gt2johpsodd.html

[T05] Kotlin：when 表达式
来源：http://dali.feifeiyinyue.top/Article/details/gt2luqboiot.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.birdmap.top/Article/details/gt2ovvolifm.html

[T06] Kotlin：集合映射
来源：http://dali.tanke756.top/Article/details/gt2kfdiykea.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gt2grkvugzd.html

[T07] Kotlin：集合过滤
来源：http://dali.yongpay.top/Article/details/gt2ivsqivgx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuxming.cn/Article/details/gt2zjhcnkjp.html

[T08] Kotlin：数据类
来源：http://dali.fzhhl.top/Article/details/gt2gmsmfrwr.html

data class User(val name: String, val age: Int)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hqznuajg.html

[T09] Kotlin：扩展函数
来源：http://dali.jinqigufen.top/Article/details/gt2qylhhtmv.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjttrpx.html

[T10] Kotlin：默认参数
来源：http://dali.bjfxy.top/Article/details/gt2arvtvziv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.daxiang520.top/Article/details/gt2gmhlydbq.html

[T11] Kotlin：协程
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jljyprvv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.guowangkeji.top/Article/details/gt2paouelob.html

[T12] Kotlin：解构声明
来源：http://dali.sweek.top/Article/details/gt2zyobxvmj.html

val (a, b) = Pair(1, 2)
来源：http://dali.sweek.top/Article/details/gt2loadxcta.html

[T13] Kotlin：只读 Map
来源：http://dali.nanxuanxn.top/Article/details/gt2rnqwmqnm.html

val m = mapOf("a" to 1)
来源：http://dali.yuxming.cn/Article/details/gt2sbolvmmw.html

[T14] Kotlin：循环
来源：http://dali.jqgfzy.top/Article/details/gt2jfwmqaba.html

for (i in 1..10) println(i)
来源：http://dali.hywenlv.cn/Article/details/gt2izricyqq.html

[T15] Kotlin：接口
来源：http://dali.yongpay.top/Article/details/gt2ijsgrlvd.html

interface Shape { fun area(): Double }
来源：http://dali.nanxinkj.top/Article/details/gt2qdpmbmrd.html

[T16] Swift：Hello World
来源：http://dali.shuidangran.top/Article/details/gt2dotleuzh.html

print("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gt2tnmeueum.html

[T17] Swift：变量与常量
来源：http://dali.daria6918.cn/Article/details/gt2sdxyfgqm.html

var a = 1;  let b = 2
来源：http://dali.svipenyu.cn/Article/details/gt2yaghpgjx.html

[T18] Swift：字符串插值
来源：http://dali.gzhubu.top/Article/details/gt2jyruissz.html

"值: \(b)"
来源：http://dali.yuxming.cn/Article/details/gt2oyrycqxx.html

[T19] Swift：可选绑定
来源：http://dali.yuxming.cn/Article/details/gt2sukriese.html

if let n = opt { print(n) }
来源：http://dali.jinqigufen.top/Article/details/gt2yfprsyan.html

[T20] Swift：数组操作
来源：http://dali.c1oappe.top/Article/details/gt2piweyons.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hfpthk.cn/Article/details/gt2qlfqtezq.html

[T21] Swift：遍历
来源：http://dali.ydzc1.top/Article/details/gt2ohvikiix.html

for x in a { print(x) }
来源：http://dali.hnqzz.top/Article/details/gt2spehjnea.html

[T22] Swift：字典
来源：http://dali.0kj1m.cn/Article/details/gt2jksgtjxj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.chenjidiqi.icu/Article/details/gt2uilrigki.html

[T23] Swift：函数
来源：http://dali.hfpthk.cn/Article/details/gt2xnxcdrpw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.snrcjt.cn/Article/details/gt2uwvzszsg.html

[T24] Swift：闭包
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2djwkltdi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.fengsongda.top/Article/details/gt2hgpeeims.html

[T25] Swift：结构体
来源：http://dali.chenzaomai.com/Article/details/gt2xzdttdjc.html

struct P { var x: Int }
来源：http://dali.guowangkeji.top/Article/details/gt2swarrndp.html

[T26] Swift：类与重写
来源：http://dali.andypj.xyz/Article/details/gt2kpxbdwou.html

class A: Base { override func f() {} }
来源：http://dali.daria6918.cn/Article/details/gt2irbdabtt.html

[T27] Swift：错误处理
来源：http://dali.hywenlv.cn/Article/details/gt2xdtfpgqr.html

do { try f() } catch { print(error) }
来源：http://dali.haohaochexian.top/Article/details/gt2xspnisgv.html

[T28] Swift：枚举
来源：http://dali.hfpthk.cn/Article/details/gt2ppphkxyu.html

enum Color { case red, green }
来源：http://dali.jqgfzy.top/Article/details/gt2mehlfrpx.html

[T29] Swift：guard 提前返回
来源：http://dali.yuxming.cn/Article/details/gt2jqemcpzh.html

guard let x = opt else { return }
来源：http://dali.nanxinkj.top/Article/details/gt2kyinxjoi.html

[T30] Swift：协议
来源：http://dali.gzhubu.top/Article/details/gt2ixqkgopr.html

protocol Shape { func area() -> Double }
来源：http://dali.hysaishi.cn/Article/details/gt2cigekzvh.html

[T31] Lua：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gt2olbivwje.html

print("Hello")
来源：http://dali.sweek.top/Article/details/gt2hygxqjul.html

[T32] Lua：局部变量
来源：http://dali.hnxiangtu.top/Article/details/gt2piiuhvdl.html

local a = 1
来源：http://dali.sysykeji.top/Article/details/gt2glpwnufe.html

[T33] Lua：表（数组）
来源：http://dali.hnqzz.top/Article/details/gt2havvafxn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.kuanghao11.cn/Article/details/gt2mtitudoz.html

[T34] Lua：遍历表
来源：http://dali.yvedp.cn/Article/details/gt2mdwrfrjv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zycfv.cn/Article/details/gt2dzzyxvxi.html

[T35] Lua：字典表
来源：http://dali.cqqwz.cn/Article/details/gt2ihbqaflv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhongyouzk.top/Article/details/gt2tnbaxpzl.html

[T36] Lua：函数
来源：http://dali.aizwys.cn/Article/details/gt2kmbjbtyg.html

function add(a, b) return a + b end
来源：http://dali.nwbrower.top/Article/details/gt2lecdifvo.html

[T37] Lua：字符串拼接
来源：http://dali.ydzc1.top/Article/details/gt2mslwujyt.html

"a" .. "b"
来源：http://dali.zdqjudy.top/Article/details/gt2mjauodhd.html

[T38] Lua：条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wwutcsga.html

if x > 0 then print("正") end
来源：http://dali.zhixingplan.top/Article/details/gt2faowhjbf.html

[T39] Lua：模式匹配
来源：http://dali.yuxming.cn/Article/details/gt2ntcaqppv.html

string.find(s, "%d+")
来源：http://dali.jianghu66.top/Article/details/gt2bitevcgy.html

[T40] Lua：元表
来源：http://dali.vqdsnc.cn/Article/details/gt2nozxhrdk.html

setmetatable({}, { __index = base })
来源：http://dali.birdmap.top/Article/details/gt2myznjarf.html

[T41] Perl：Hello World
来源：http://dali.cheryme.top/Article/details/gt2fanbfupw.html

print "Hello\n";
来源：http://dali.dashuyun.cn/Article/details/gt2pesummam.html

[T42] Perl：变量类型
来源：http://dali.quarkkingdee.top/Article/details/gt2nuqoxchz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.meibo888.top/Article/details/gt2lchrsgqm.html

[T43] Perl：字符串插值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qkyqgngk.html

"值: $a"
来源：http://dali.c1oappe.top/Article/details/gt2prhuaxlt.html

[T44] Perl：条件
来源：http://dali.guannengcc.top/Article/details/gt2itnywldn.html

if ($a > 0) { print "正"; }
来源：http://dali.mhx1999.top/Article/details/gt2wdwdflgq.html

[T45] Perl：数组遍历
来源：http://dali.jyoumei.cn/Article/details/gt2svlgximi.html

for my $x (@arr) { print $x; }
来源：http://dali.bjfxy.top/Article/details/gt2vyhhemxd.html

[T46] Perl：哈希操作
来源：http://dali.jlsjyb.cn/Article/details/gt2vsndibvs.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gogol.net.cn/Article/details/gt2jjczovru.html

[T47] Perl：正则捕获
来源：http://dali.yueranfly.top/Article/details/gt2acsvgxju.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.quarkkingdee.top/Article/details/gt2xcvlplru.html

[T48] Perl：正则替换
来源：http://dali.smart0.xyz/Article/details/gt2wyjxpsqe.html

$s =~ s/old/new/g;
来源：http://dali.jinqigfzy.top/Article/details/gt2maarzrtx.html

[T49] Perl：函数
来源：http://dali.yj20258.top/Article/details/gt2wyailmxu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gt2pihzpesn.html

[T50] Perl：逐行读文件
来源：http://dali.fzhhl.top/Article/details/gt2aqmoewcz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.vqdsnc.cn/Article/details/gt2oeczfkbd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.svipenyu.cn/Article/details/gt2pwilbagw.html

[T51] Scala：Hello World
来源：http://dali.xziqi.cn/Article/details/gt2veiohjgn.html

println("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bazwmufv.html

[T52] Scala：变量
来源：http://dali.kuanghao11.cn/Article/details/gt2usqumcki.html

val a = 1;  var b = 2
来源：http://dali.andypj.xyz/Article/details/gt2jqfklnhn.html

[T53] Scala：字符串插值
来源：http://dali.guannengcc.top/Article/details/gt2xicrdpcr.html

s"值: $b"
来源：http://dali.hongshengwenyu.top/Article/details/gt2hyqcnjqs.html

[T54] Scala：集合映射
来源：http://dali.gaohongyu789.top/Article/details/gt2ctxwnijr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.dashuyun.cn/Article/details/gt2jttdfxaz.html

[T55] Scala：集合过滤
来源：http://dali.sweek.top/Article/details/gt2ubsxelxb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2cbalaukk.html

[T56] Scala：样例类
来源：http://dali.birdmap.top/Article/details/gt2kjmcnivz.html

case class User(name: String, age: Int)
来源：http://dali.ivvv.top/Article/details/gt2heibhrgf.html

[T57] Scala：模式匹配
来源：http://dali.wangshuangyany.cn/Article/details/gt2ntfomybe.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.nwbrower.top/Article/details/gt2xzvsauwk.html

[T58] Scala：函数定义
来源：http://dali.nanxuanxn.top/Article/details/gt2hlrdamff.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yanxiufei.cn/Article/details/gt2espldgfc.html

[T59] Scala：循环
来源：http://dali.sweek.top/Article/details/gt2kkbhgsjp.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhongyouzk.top/Article/details/gt2hseugasp.html

[T60] Scala：折叠
来源：http://dali.yvedp.cn/Article/details/gt2jdcrcfkj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jiagoushi.top/Article/details/gt2kitoumju.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2isfbfmzk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhixingplan.top/Article/details/gt2qbctgwci.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2xiajblqo.html

[U01] Py：创建虚拟环境
来源：http://dali.jianghu66.top/Article/details/gt2tqmvzcgi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sysykeji.top/Article/details/gt2ywhujiqm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.nwbrower.top/Article/details/gt2wjqtgcfv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xuanzx.com/Article/details/gt2knaygoka.html

[U03] Py：加载 .env 配置
来源：http://dali.sysykeji.top/Article/details/gt2zpfakzqh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.chenjidiqi.icu/Article/details/gt2wkvvvwle.html

[U04] Py：变量调试打印
来源：http://dali.jiagoushi.top/Article/details/gt2oufoumsv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.quarkkingdee.top/Article/details/gt2pejmmmwt.html

[U05] Py：列表去重且保序
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ishjwvsq.html

list(dict.fromkeys(arr))
来源：http://dali.yvedp.cn/Article/details/gt2urhidqab.html

[U06] Py：合并两个字典
来源：http://dali.chenlongwang.top/Article/details/gt2mxfefbmz.html

{**a, **b}
来源：http://dali.hfpthk.cn/Article/details/gt2eunmxuat.html

[U07] Py：反转字典键值
来源：http://dali.tianlin.xyz/Article/details/gt2rjnoxfbd.html

{v: k for k, v in d.items()}
来源：http://dali.daxiang520.top/Article/details/gt2lspdcqll.html

[U08] Py：展平二维列表
来源：http://dali.hywenlv.cn/Article/details/gt2scchnale.html

[y for x in nested for y in x]
来源：http://dali.gogol.net.cn/Article/details/gt2jbkxoxkb.html

[U09] Py：字典取最大值的键
来源：http://dali.birdmap.top/Article/details/gt2unvuptjd.html

max(d, key=d.get)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2grxhfzuo.html

[U10] Py：按值排序字典
来源：http://dali.zhiwuduotai.top/Article/details/gt2ffhookcm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.dashuyun.cn/Article/details/gt2oczstyrw.html

[U11] Py：生成器表达式
来源：http://dali.meibo888.top/Article/details/gt2fxpesovq.html

(x * 2 for x in arr)
来源：http://dali.yj20258.top/Article/details/gt2yxdyjkrj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xuanzx.com/Article/details/gt2dgwayemd.html

Counter(arr).most_common(3)
来源：http://dali.ydzc1.top/Article/details/gt2etxacgtb.html

[U13] Py：固定长度队列
来源：http://dali.jiagoushi.top/Article/details/gt2ruedjgbv.html

deque(maxlen=10)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lwxkyiqd.html

[U14] Py：分组收集到列表
来源：http://dali.zycfv.cn/Article/details/gt2gserazei.html

defaultdict(list)
来源：http://dali.cashguo.top/Article/details/gt2keakhdua.html

[U15] Py：高精度计时
来源：http://dali.daria6918.cn/Article/details/gt2gupnatqo.html

t = time.perf_counter()
来源：http://dali.zhongyouzk.top/Article/details/gt2baerceyy.html

[U16] Py：命令行参数解析
来源：http://dali.wangdashe.top/Article/details/gt2avtlnzbx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.aibaodan.cn/Article/details/gt2mrxcgrrz.html


<!-- 参考信息 -->