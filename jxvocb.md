代发 wailian999

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jqgfzy.top/Article/details/gtabzuiwuo.html

[R72] 等待端口就绪
来源：http://dali.gaohongyu789.top/Article/details/gtykczbmbv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhiwuduotai.top/Article/details/gtohdgtpiy.html

[R73] 分割大日志
来源：http://dali.fzhhl.top/Article/details/gtvgtzhxfo.html

split -l 1000 big.log part_
来源：http://dali.yuxming.cn/Article/details/gtyhegtlzj.html

[R74] 批量重命名
来源：http://dali.chenjidiqi.icu/Article/details/gtsgvgyplh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nwbrower.top/Article/details/gtfirhhwqt.html

[R75] 导出环境变量
来源：http://dali.aibaodan.cn/Article/details/gtykjgbmsy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yangfankeji.com/Article/details/gtbsuvwawr.html

[R76] 使用临时文件
来源：http://dali.sufxvd.cn/Article/details/gtrdrvrlgf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhoulong.xyz/Article/details/gtgdxrcypr.html

[R77] 读取用户输入
来源：http://dali.gotoacloud.top/Article/details/gtxmncnmnn.html

read -rp "请输入: " ans
来源：http://dali.yj20258.top/Article/details/gtielxclip.html

[R78] 交互式菜单
来源：http://dali.hnqzz.top/Article/details/gthkutqtpc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hnqzz.top/Article/details/gtxuyzymca.html

[R79] 解析命令行选项
来源：http://dali.jianghu66.top/Article/details/gtiugaaecn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zdqjudy.top/Article/details/gtxwytnpou.html

[R80] 查看脚本执行耗时
来源：http://dali.fzhhl.top/Article/details/gtqusrhntx.html

time ./run.sh
来源：http://dali.sufxvd.cn/Article/details/gtmwtrdhbe.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtsnzlhksa.html

S. C / C++ 专题
来源：http://dali.feifeiyinyue.top/Article/details/gteqcglwkz.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtwehfqhjo.html

[S01] C：Hello World
来源：http://dali.cheryme.top/Article/details/gtxktamyzy.html

#include <stdio.h>
来源：http://dali.pengpengdd.cyou/Article/details/gtpalfhxuq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.andypj.xyz/Article/details/gtwpuwcmmt.html

[S02] C：变量与格式化输出
来源：http://dali.gogol.net.cn/Article/details/gtyjtsxyly.html

int a = 10; printf("%d\n", a);
来源：http://dali.gzhubu.top/Article/details/gtwwvnunyx.html

[S03] C：读入整数
来源：http://dali.0kj1m.cn/Article/details/gttdhkwtjl.html

int x; scanf("%d", &x);
来源：http://dali.yuanzhike.top/Article/details/gtovoemmgo.html

[S04] C：字符串复制
来源：http://dali.xylfe.cn/Article/details/gtklkhwodq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.meibo888.top/Article/details/gtwweypupv.html

[S05] C：字符串长度
来源：http://dali.dianchejie.cn/Article/details/gtxtrxhchf.html

strlen(s)
来源：http://dali.quarkkingdee.top/Article/details/gtbbwyytkb.html

[S06] C：字符串比较
来源：http://dali.bjfxy.top/Article/details/gthkksxktd.html

strcmp(a, b) == 0
来源：http://dali.wangdashe.top/Article/details/gtquppqjcp.html

[S07] C：数组遍历求和
来源：http://dali.yj202588.top/Article/details/gtlwqmfkrv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yvedp.cn/Article/details/gtrlvvcskl.html

[S08] C：动态内存分配与释放
来源：http://dali.cashguo.top/Article/details/gtigegqfhl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.fengsongda.top/Article/details/gtfyalcgjv.html

[S09] C：结构体定义与初始化
来源：http://dali.snrcjt.cn/Article/details/gtxkvkcmhw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.0kj1m.cn/Article/details/gtuxqtkthv.html

[S10] C：指针与解引用
来源：http://dali.sweek.top/Article/details/gtbpteicwc.html

int *p = &a;  *p = 5;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtctmoqury.html

[S11] C：逐行读文件
来源：http://dali.xziqi.cn/Article/details/gtjmspvohb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.pycfn.com/Article/details/gtwecwdgeu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.daxiang520.top/Article/details/gtqrcnjinx.html

fclose(f);
来源：http://dali.hnxiangtu.top/Article/details/gtotechfeh.html

[S12] C：写文件
来源：http://dali.yj20258.top/Article/details/gtqmhqvemw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.smart0.xyz/Article/details/gtcysypvhh.html

[S13] C：宏定义
来源：http://dali.chenjidiqi.icu/Article/details/gtjgtanxma.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yuxming.cn/Article/details/gtrgptdtxi.html

[S14] C：枚举
来源：http://dali.sysykeji.top/Article/details/gtmcjxbchg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.haohaochexian.top/Article/details/gtbytstngk.html

[S15] C：类型转换
来源：http://dali.yongpay.top/Article/details/gtxvfrbwzz.html

(double) a / b
来源：http://dali.cheryme.top/Article/details/gthueeqonf.html

[S16] C：位操作置位
来源：http://dali.zhixingplan.top/Article/details/gthiydxxsj.html

x |= (1 << 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtobspdzda.html

[S17] C：安全拼接字符串
来源：http://dali.hywenlv.cn/Article/details/gtiscnhpwd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfuejgjqz.html

[S18] C：命令行参数
来源：http://dali.shuidangran.top/Article/details/gtudclopom.html

int main(int argc, char **argv)
来源：http://dali.havefunace.top/Article/details/gtrowsbisr.html

[S19] C：快速排序
来源：http://dali.kuanghao11.cn/Article/details/gthpevtmxn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hfpthk.cn/Article/details/gtdevvxsmt.html

[S20] C：二分查找
来源：http://dali.nwbrower.top/Article/details/gtfttixigv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhengqikj.top/Article/details/gtfrrlgqdw.html

[S21] C：字符类别判断
来源：http://dali.gaohongyu789.top/Article/details/gtclonatfs.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shangyingyoupin.top/Article/details/gtvihalstc.html

[S22] C：字符串转数字
来源：http://dali.zhongyouzk.top/Article/details/gtmilovghq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.haohaochexian.top/Article/details/gtdrfkabrh.html

[S23] C：随机数
来源：http://dali.tian-w.cn/Article/details/gtcqsjrxst.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ydzc1.top/Article/details/gtgtyfftis.html

[S24] C：获取本地时间
来源：http://dali.wangshuangyany.cn/Article/details/gtkwdcyege.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ppjwa.cn/Article/details/gtgsydqhka.html

[S25] C：内存拷贝
来源：http://dali.sysykeji.top/Article/details/gtsjipsmql.html

memcpy(dst, src, n);
来源：http://dali.nanxinkj.top/Article/details/gtekdpyrny.html

[S26] C：内存清零
来源：http://dali.jinqigfzy.top/Article/details/gthbrdoyrx.html

memset(a, 0, sizeof a);
来源：http://dali.xinyue.icu/Article/details/gtruqwrfvv.html

[S27] C：定义常量
来源：http://dali.yonumen.top/Article/details/gtrlrmpdjg.html

const double PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtbobyanax.html

[S28] C：静态变量
来源：http://dali.fzhhl.top/Article/details/gtwzahsovr.html

static int counter = 0;
来源：http://dali.c1oappe.top/Article/details/gtpcpfnupa.html

[S29] C：变参函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmmaciifg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.c1oappe.top/Article/details/gtpyqqbzuh.html

[S30] C：头文件保护
来源：http://dali.xinyue.icu/Article/details/gtykefqyok.html

#ifndef X_H
来源：http://dali.chenzaomai.com/Article/details/gtptpdbaip.html

#define X_H
来源：http://dali.pycfn.com/Article/details/gtuwbfivfx.html

#endif
来源：http://dali.yongpay.top/Article/details/gtzpqqofkh.html

[S31] C++：Hello World
来源：http://dali.xinyue.icu/Article/details/gtmpfapkft.html

#include <iostream>
来源：http://dali.wangshuangyany.cn/Article/details/gtdtlcjdcy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ydzc1.top/Article/details/gtqmpvegdh.html

[S32] C++：字符串
来源：http://dali.snrcjt.cn/Article/details/gtayptkqnv.html

std::string s = "hi";  s += "!";
来源：http://dali.gaohongyu789.top/Article/details/gtocwnglrd.html

[S33] C++：vector 增删
来源：http://dali.cqqwz.cn/Article/details/gtcieprnsg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gtwsrssnti.html

[S34] C++：遍历 vector
来源：http://dali.birdmap.top/Article/details/gtcpxheycd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinqigfzy.top/Article/details/gtyxowozdh.html

[S35] C++：map
来源：http://dali.tian-w.cn/Article/details/gttyuhmlsu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtasfvmtzj.html

[S36] C++：unordered_map
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjinwmnc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sweek.top/Article/details/gtaznhmypn.html

[S37] C++：set
来源：http://dali.yuanzhike.top/Article/details/gtdmhizarz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yueranfly.top/Article/details/gtsmlahzno.html

[S38] C++：排序
来源：http://dali.hnqzz.top/Article/details/gtdyflbajq.html

std::sort(v.begin(), v.end());
来源：http://dali.tianlin.xyz/Article/details/gtjiasgsis.html

[S39] C++：自定义比较器排序
来源：http://dali.fengsongda.top/Article/details/gtjikfogxq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hfpthk.cn/Article/details/gtcdwbfood.html

[S40] C++：查找元素
来源：http://dali.shanyushiyangtech.top/Article/details/gttielfabf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sufxvd.cn/Article/details/gtbhsvvoqq.html

[S41] C++：类与构造函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkjanfgh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ybcxt.top/Article/details/gtuqidhloq.html

[S42] C++：继承与虚函数
来源：http://dali.yj202588.top/Article/details/gtzxsllwvc.html

class B : public Base { public: void f() override {} };
来源：http://dali.tanke756.top/Article/details/gtsuwslero.html

[S43] C++：智能指针
来源：http://dali.ydzc1.top/Article/details/gtnhgnwgjj.html

auto p = std::make_unique<int>(5);
来源：http://dali.kuanghao11.cn/Article/details/gtcgnmbqfp.html

[S44] C++：引用传参
来源：http://dali.yongpay.top/Article/details/gtccachjsi.html

void inc(int &x) { ++x; }
来源：http://dali.nanxuanxn.top/Article/details/gtnkiibyjr.html

[S45] C++：lambda
来源：http://dali.meibo888.top/Article/details/gtiaqrmgze.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.wangdashe.top/Article/details/gtefcprmqx.html

[S46] C++：函数模板
来源：http://dali.xuanzx.com/Article/details/gtorxxyyrl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhixingplan.top/Article/details/gtlbkzprli.html

[S47] C++：结构化绑定遍历
来源：http://dali.0kj1m.cn/Article/details/gtqmmzcrbd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ybcxt.top/Article/details/gtxivmknlq.html

[S48] C++：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gtjkcggxwm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzomttxbc.html

while (std::getline(in, line)) { }
来源：http://dali.yueranfly.top/Article/details/gtqwdcugyn.html

[S49] C++：写文件
来源：http://dali.yuxming.cn/Article/details/gtvhrgytwk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.guowangkeji.top/Article/details/gtfyjmfikj.html

[S50] C++：格式化数字
来源：http://dali.andypj.xyz/Article/details/gtdldwymmn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtcguogjhu.html

[S51] C++：显式类型转换
来源：http://dali.sufxvd.cn/Article/details/gtlnwrirni.html

static_cast<double>(a) / b
来源：http://dali.mhx1999.top/Article/details/gtkcumkank.html

[S52] C++：const 与 noexcept
来源：http://dali.xylfe.cn/Article/details/gtawsxhpal.html

int size() const noexcept { return n_; }
来源：http://dali.birdmap.top/Article/details/gtufbcaldc.html

[S53] C++：移动语义
来源：http://dali.jlsjyb.cn/Article/details/gtcuxtkjjz.html

std::vector<int> w = std::move(v);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkfuwacuw.html

[S54] C++：异常处理
来源：http://dali.dianchejie.cn/Article/details/gtuelatfuu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cdnleiting.top/Article/details/gtdordriht.html

[S55] C++：结构化绑定
来源：http://dali.svipenyu.cn/Article/details/gtfzvmjyvs.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yvedp.cn/Article/details/gtntyutnxd.html

[S56] C++：optional
来源：http://dali.c1oappe.top/Article/details/gtmwljwrcm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.mhx1999.top/Article/details/gtfygsnvvt.html

[S57] C++：编译期常量
来源：http://dali.hysaishi.cn/Article/details/gtqapkspyq.html

constexpr int N = 10;
来源：http://dali.jqgfzy.top/Article/details/gtunsdxkgf.html

[S58] C++：命名空间
来源：http://dali.hfpthk.cn/Article/details/gthopyukpd.html

namespace ns { int f() { return 1; } }
来源：http://dali.9152youxi.cn/Article/details/gtephqyyia.html

[S59] C++：静态断言
来源：http://dali.wangshuangyany.cn/Article/details/gtkyrtyimn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jiagoushi.top/Article/details/gtachnvryn.html

[S60] C++：遍历并删除元素
来源：http://dali.cdnleiting.top/Article/details/gtqpeepuku.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sysykeji.top/Article/details/gtweqrrzyu.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtllwczqcv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ivvv.top/Article/details/gtnyelubyx.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtimkvvpjq.html

[T01] Kotlin：Hello World
来源：http://dali.havefunace.top/Article/details/gtpnkqjmub.html

println("Hello")
来源：http://dali.bjfxy.top/Article/details/gtfpjmehmp.html

[T02] Kotlin：变量
来源：http://dali.jlsjyb.cn/Article/details/gtgzmmngfc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.guowangkeji.top/Article/details/gtxjzwenvq.html

[T03] Kotlin：字符串模板
来源：http://dali.svipenyu.cn/Article/details/gtdhnyvmrk.html

"值: $b"
来源：http://dali.yj20258888.top/Article/details/gtbxulsvny.html

[T04] Kotlin：空安全
来源：http://dali.yangfankeji.com/Article/details/gtarqdqqfh.html

val n: String? = null;  n?.length
来源：http://dali.wangdashe.top/Article/details/gterglymdw.html

[T05] Kotlin：when 表达式
来源：http://dali.yvedp.cn/Article/details/gtdrjsddpm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.wangshuangyany.cn/Article/details/gtyvfujtgy.html

[T06] Kotlin：集合映射
来源：http://dali.cqqwz.cn/Article/details/gtgitolmyt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.svipenyu.cn/Article/details/gttftajjtb.html

[T07] Kotlin：集合过滤
来源：http://dali.bjfxy.top/Article/details/gteibtkwvw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.dashuyun.cn/Article/details/gttjhswgyh.html

[T08] Kotlin：数据类
来源：http://dali.daria6918.cn/Article/details/gteinmwlbc.html

data class User(val name: String, val age: Int)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrkjqsvfn.html

[T09] Kotlin：扩展函数
来源：http://dali.shuidangran.top/Article/details/gtsxlofgfi.html

fun String.exclaim() = this + "!"
来源：http://dali.shangyingyoupin.top/Article/details/gtzlulczex.html

[T10] Kotlin：默认参数
来源：http://dali.gotoacloud.top/Article/details/gthxavyupt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.andypj.xyz/Article/details/gtljeqqqie.html

[T11] Kotlin：协程
来源：http://dali.chenlongwang.top/Article/details/gtmkevuotn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gzhubu.top/Article/details/gtclfeuibm.html

[T12] Kotlin：解构声明
来源：http://dali.nanxuanxn.top/Article/details/gtsorokyyl.html

val (a, b) = Pair(1, 2)
来源：http://dali.dashuyun.cn/Article/details/gtkrqhfnjg.html

[T13] Kotlin：只读 Map
来源：http://dali.tianlin.xyz/Article/details/gtrobuuxwi.html

val m = mapOf("a" to 1)
来源：http://dali.cqqwz.cn/Article/details/gtkftoeftq.html

[T14] Kotlin：循环
来源：http://dali.bjfxy.top/Article/details/gtoqbzfixd.html

for (i in 1..10) println(i)
来源：http://dali.316326.xyz/Article/details/gtnhwpoqzq.html

[T15] Kotlin：接口
来源：http://dali.redwolf501.top/Article/details/gtiorisitm.html

interface Shape { fun area(): Double }
来源：http://dali.sufxvd.cn/Article/details/gtschliipm.html

[T16] Swift：Hello World
来源：http://dali.chenzaomai.com/Article/details/gteqwoewmk.html

print("Hello")
来源：http://dali.svipenyu.cn/Article/details/gtqwxethxz.html

[T17] Swift：变量与常量
来源：http://dali.nanxinkj.top/Article/details/gteymhqetn.html

var a = 1;  let b = 2
来源：http://dali.sweek.top/Article/details/gtimbutdcb.html

[T18] Swift：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gtdcxpfart.html

"值: \(b)"
来源：http://dali.dianchejie.cn/Article/details/gteymoyqat.html

[T19] Swift：可选绑定
来源：http://dali.hongshengwenyu.top/Article/details/gtwasrexxx.html

if let n = opt { print(n) }
来源：http://dali.mhx1999.top/Article/details/gtiburxvyx.html

[T20] Swift：数组操作
来源：http://dali.yueranfly.top/Article/details/gtfoiqbqww.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.9152youxi.cn/Article/details/gtlgrzhavi.html

[T21] Swift：遍历
来源：http://dali.cdnleiting.top/Article/details/gtzeayzztl.html

for x in a { print(x) }
来源：http://dali.chenlongwang.top/Article/details/gtwoxlocqn.html

[T22] Swift：字典
来源：http://dali.hysaishi.cn/Article/details/gtzpwhxsvh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.nanxuanxn.top/Article/details/gttcdgdmkz.html

[T23] Swift：函数
来源：http://dali.sysykeji.top/Article/details/gtifrneiso.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ppjwa.cn/Article/details/gthdauxbcg.html

[T24] Swift：闭包
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtixivraeb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.snrcjt.cn/Article/details/gtvzaihuxk.html

[T25] Swift：结构体
来源：http://dali.chenzaomai.com/Article/details/gtuoazsmwh.html

struct P { var x: Int }
来源：http://dali.cucudq.cn/Article/details/gtscayogki.html

[T26] Swift：类与重写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtouwwsthd.html

class A: Base { override func f() {} }
来源：http://dali.xuanzx.com/Article/details/gtjsatibum.html

[T27] Swift：错误处理
来源：http://dali.meibo888.top/Article/details/gtvqcpefwp.html

do { try f() } catch { print(error) }
来源：http://dali.chenzaomai.com/Article/details/gtlckqjpmn.html

[T28] Swift：枚举
来源：http://dali.c1oappe.top/Article/details/gtpzosmfxk.html

enum Color { case red, green }
来源：http://dali.yueranfly.top/Article/details/gtugvyagug.html

[T29] Swift：guard 提前返回
来源：http://dali.yueranfly.top/Article/details/gtcmxjhgde.html

guard let x = opt else { return }
来源：http://dali.pengpengdd.cyou/Article/details/gtruipvgyu.html

[T30] Swift：协议
来源：http://dali.shangyingyoupin.top/Article/details/gtudjneqem.html

protocol Shape { func area() -> Double }
来源：http://dali.zhoulong.xyz/Article/details/gtrlgemcim.html

[T31] Lua：Hello World
来源：http://dali.aizwys.cn/Article/details/gtgxmxjotg.html

print("Hello")
来源：http://dali.daxiang520.top/Article/details/gttvtgvdjt.html

[T32] Lua：局部变量
来源：http://dali.sufxvd.cn/Article/details/gthnufghgu.html

local a = 1
来源：http://dali.sysykeji.top/Article/details/gtjhpfdjtx.html

[T33] Lua：表（数组）
来源：http://dali.jyoumei.cn/Article/details/gtppnfyxoy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.daria6918.cn/Article/details/gtdqeezvkv.html

[T34] Lua：遍历表
来源：http://dali.aizwys.cn/Article/details/gtqgzcqgch.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.andypj.xyz/Article/details/gtuqcucpqc.html

[T35] Lua：字典表
来源：http://dali.smart0.xyz/Article/details/gtyngihmwb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sysykeji.top/Article/details/gtrsyhoopy.html

[T36] Lua：函数
来源：http://dali.chenzaomai.com/Article/details/gtnomhrkww.html

function add(a, b) return a + b end
来源：http://dali.yangfankeji.com/Article/details/gtwuqstqel.html

[T37] Lua：字符串拼接
来源：http://dali.ppjwa.cn/Article/details/gtorkaxrso.html

"a" .. "b"
来源：http://dali.hywenlv.cn/Article/details/gtqbletcug.html

[T38] Lua：条件
来源：http://dali.snrcjt.cn/Article/details/gtrhjqddds.html

if x > 0 then print("正") end
来源：http://dali.feifeiyinyue.top/Article/details/gtuiilvjcs.html

[T39] Lua：模式匹配
来源：http://dali.sweek.top/Article/details/gtpwhgbyuz.html

string.find(s, "%d+")
来源：http://dali.aizwys.cn/Article/details/gtmjzpyjne.html

[T40] Lua：元表
来源：http://dali.shuidangran.top/Article/details/gtzrjttcsr.html

setmetatable({}, { __index = base })
来源：http://dali.bjfxy.top/Article/details/gtwjhcxdud.html

[T41] Perl：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtfhozuvqn.html

print "Hello\n";
来源：http://dali.yj20258888.top/Article/details/gtkzskatgr.html

[T42] Perl：变量类型
来源：http://dali.0kj1m.cn/Article/details/gtrxwbjzci.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.pengpengdd.cyou/Article/details/gtcrzvacen.html

[T43] Perl：字符串插值
来源：http://dali.ybcxt.top/Article/details/gtlhfhsllf.html

"值: $a"
来源：http://dali.jinghuilouyu.cn/Article/details/gtocjojfvq.html

[T44] Perl：条件
来源：http://dali.havefunace.top/Article/details/gtlyjvqwvu.html

if ($a > 0) { print "正"; }
来源：http://dali.wangdashe.top/Article/details/gtvlnbbwtl.html

[T45] Perl：数组遍历
来源：http://dali.yj20258.top/Article/details/gtwyrjvwhf.html

for my $x (@arr) { print $x; }
来源：http://dali.jianghu66.top/Article/details/gtntocmbqu.html

[T46] Perl：哈希操作
来源：http://dali.sysykeji.top/Article/details/gtvgflyoxv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hfpthk.cn/Article/details/gtukstoonz.html

[T47] Perl：正则捕获
来源：http://dali.pycfn.com/Article/details/gtcglfihis.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hfpthk.cn/Article/details/gtowrspfhw.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gtyqrxsioi.html

$s =~ s/old/new/g;
来源：http://dali.zhoulong.xyz/Article/details/gtzxvbllys.html

[T49] Perl：函数
来源：http://dali.sxryk.cn/Article/details/gtxqqedcrk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gtcyrfcvgh.html

[T50] Perl：逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gtylknhihk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.feifeiyinyue.top/Article/details/gthsmcgupt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhixingplan.top/Article/details/gtrsazasis.html

[T51] Scala：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtuvbcvazx.html

println("Hello")
来源：http://dali.snrcjt.cn/Article/details/gtvtohpeqw.html

[T52] Scala：变量
来源：http://dali.sufxvd.cn/Article/details/gtgpzxmhdo.html

val a = 1;  var b = 2
来源：http://dali.chenzaomai.com/Article/details/gtyudcwaoc.html

[T53] Scala：字符串插值
来源：http://dali.svipenyu.cn/Article/details/gtewlslsym.html

s"值: $b"
来源：http://dali.ehwqpu.com/Article/details/gtbgtvvzaq.html

[T54] Scala：集合映射
来源：http://dali.yongpay.top/Article/details/gtrppfxtsp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.haohaochexian.top/Article/details/gtprwqefmg.html

[T55] Scala：集合过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gtstuzvhlz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.c1oappe.top/Article/details/gtxybfcoqw.html

[T56] Scala：样例类
来源：http://dali.jlsjyb.cn/Article/details/gtkbgvfbyg.html

case class User(name: String, age: Int)
来源：http://dali.gogol.net.cn/Article/details/gtcgkaewdr.html

[T57] Scala：模式匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtorjcfcux.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.iojbl.cn/Article/details/gtnwzotbbi.html

[T58] Scala：函数定义
来源：http://dali.cdnleiting.top/Article/details/gtrigrjevu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhongyouzk.top/Article/details/gtqctdjuzk.html

[T59] Scala：循环
来源：http://dali.yueranfly.top/Article/details/gtppxgptql.html

for (i <- 1 to 10) println(i)
来源：http://dali.cqqwz.cn/Article/details/gtdznmtywh.html

[T60] Scala：折叠
来源：http://dali.yangfankeji.com/Article/details/gtgwzdzgbq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.svipenyu.cn/Article/details/gtlcrglnzf.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtpmgwxtnf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfblypsvl.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtgfnzoehp.html

[U01] Py：创建虚拟环境
来源：http://dali.mhx1999.top/Article/details/gticyqonjf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.316326.xyz/Article/details/gtflubjyiu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xuanzx.com/Article/details/gtpliqvypb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ehwqpu.com/Article/details/gtenslqfdl.html

[U03] Py：加载 .env 配置
来源：http://dali.sxryk.cn/Article/details/gttutnlkzb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.aizwys.cn/Article/details/gtceloahty.html

[U04] Py：变量调试打印
来源：http://dali.hnxiangtu.top/Article/details/gtglduvyso.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.dianchejie.cn/Article/details/gtqdhwvnij.html

[U05] Py：列表去重且保序
来源：http://dali.sweek.top/Article/details/gtgchbjymp.html

list(dict.fromkeys(arr))
来源：http://dali.redwolf501.top/Article/details/gtcdpmoaab.html

[U06] Py：合并两个字典
来源：http://dali.zhixingplan.top/Article/details/gtwrayyhma.html

{**a, **b}
来源：http://dali.cheryme.top/Article/details/gttkzofwvk.html

[U07] Py：反转字典键值
来源：http://dali.jianghu66.top/Article/details/gtfqzyquyz.html

{v: k for k, v in d.items()}
来源：http://dali.aizwys.cn/Article/details/gtfifrhuvz.html

[U08] Py：展平二维列表
来源：http://dali.0kj1m.cn/Article/details/gtsctdeocm.html

[y for x in nested for y in x]
来源：http://dali.tanke756.top/Article/details/gthojhfwbm.html

[U09] Py：字典取最大值的键
来源：http://dali.hnqzz.top/Article/details/gtlwpewdcb.html

max(d, key=d.get)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfjopltww.html

[U10] Py：按值排序字典
来源：http://dali.nanxinkj.top/Article/details/gtnqszomrs.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzvifttdm.html

[U11] Py：生成器表达式
来源：http://dali.bjfxy.top/Article/details/gtufekficx.html

(x * 2 for x in arr)
来源：http://dali.cashguo.top/Article/details/gtalwurowf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.snrcjt.cn/Article/details/gtskftvbrl.html

Counter(arr).most_common(3)
来源：http://dali.ivvv.top/Article/details/gtgljifikx.html


<!-- 参考信息 -->