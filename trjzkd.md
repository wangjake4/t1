代发 wailian999

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zdqjudy.top/Article/details/gt2kxblrguy.html

[R72] 等待端口就绪
来源：http://dali.hammf.cn/Article/details/gt2ylofgftd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gt2seouhbcm.html

[R73] 分割大日志
来源：http://dali.haohaochexian.top/Article/details/gt2geurlxhs.html

split -l 1000 big.log part_
来源：http://dali.ybcxt.top/Article/details/gt2xqvrmosx.html

[R74] 批量重命名
来源：http://dali.pycfn.com/Article/details/gt2qhfbalhu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jianghu66.top/Article/details/gt2javqpvju.html

[R75] 导出环境变量
来源：http://dali.fengsongda.top/Article/details/gt2tssxbfuu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xinyue.icu/Article/details/gt2vlwrosjv.html

[R76] 使用临时文件
来源：http://dali.hnxiangtu.top/Article/details/gt2ppchyxsd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnxiangtu.top/Article/details/gt2agnuvgip.html

[R77] 读取用户输入
来源：http://dali.chenjidiqi.icu/Article/details/gt2oxiysorc.html

read -rp "请输入: " ans
来源：http://dali.andypj.xyz/Article/details/gt2pppgyatr.html

[R78] 交互式菜单
来源：http://dali.aizwys.cn/Article/details/gt2jlbvstqf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhixingplan.top/Article/details/gt2qlnrzfoj.html

[R79] 解析命令行选项
来源：http://dali.vqdsnc.cn/Article/details/gt2ajeahuen.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ppjwa.cn/Article/details/gt2qzfeyqmg.html

[R80] 查看脚本执行耗时
来源：http://dali.hfpthk.cn/Article/details/gt2cvdtpikz.html

time ./run.sh
来源：http://dali.hysaishi.cn/Article/details/gt2sfzkhucm.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fugdjyxf.html

S. C / C++ 专题
来源：http://dali.sxryk.cn/Article/details/gt2srkakudg.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2wemjedxk.html

[S01] C：Hello World
来源：http://dali.nwbrower.top/Article/details/gt2hbrewbdn.html

#include <stdio.h>
来源：http://dali.smart0.xyz/Article/details/gt2riiettrj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nanxinkj.top/Article/details/gt2rvgwzcxm.html

[S02] C：变量与格式化输出
来源：http://dali.shangyingyoupin.top/Article/details/gt2kzmnmrjo.html

int a = 10; printf("%d\n", a);
来源：http://dali.yuanzhike.top/Article/details/gt2sgmbvwta.html

[S03] C：读入整数
来源：http://dali.xuetiantiany.cn/Article/details/gt2sltqdqqo.html

int x; scanf("%d", &x);
来源：http://dali.daxiang520.top/Article/details/gt2rgylnjmt.html

[S04] C：字符串复制
来源：http://dali.wangshuangyany.cn/Article/details/gt2wztpntnk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shuidangran.top/Article/details/gt2bzgqmtna.html

[S05] C：字符串长度
来源：http://dali.jyoumei.cn/Article/details/gt2ausyevfy.html

strlen(s)
来源：http://dali.daria6918.cn/Article/details/gt2vunncyjs.html

[S06] C：字符串比较
来源：http://dali.ybcxt.top/Article/details/gt2brtzegyk.html

strcmp(a, b) == 0
来源：http://dali.yj20258.top/Article/details/gt2yhbnhqen.html

[S07] C：数组遍历求和
来源：http://dali.fzhhl.top/Article/details/gt2repvtxdb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.guannengcc.top/Article/details/gt2nlcppzcx.html

[S08] C：动态内存分配与释放
来源：http://dali.daxiang520.top/Article/details/gt2tbruvzjw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gogol.net.cn/Article/details/gt2swlhwxvh.html

[S09] C：结构体定义与初始化
来源：http://dali.hongshengwenyu.top/Article/details/gt2udnviufo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hnxiangtu.top/Article/details/gt2jsfkesrq.html

[S10] C：指针与解引用
来源：http://dali.hongshengwenyu.top/Article/details/gt2ywtikhif.html

int *p = &a;  *p = 5;
来源：http://dali.zycfv.cn/Article/details/gt2pjqfkunf.html

[S11] C：逐行读文件
来源：http://dali.fengsongda.top/Article/details/gt2stzckhbd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.wangdashe.top/Article/details/gt2clgngzvz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.meibo888.top/Article/details/gt2nmzeueig.html

fclose(f);
来源：http://dali.yuxming.cn/Article/details/gt2cyxqspsu.html

[S12] C：写文件
来源：http://dali.shzxlz.cn/Article/details/gt2iytcwpdo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.dianchejie.cn/Article/details/gt2gqnksftr.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpikdys.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.bjfxy.top/Article/details/gt2lubveqqy.html

[S14] C：枚举
来源：http://dali.andypj.xyz/Article/details/gt2jwldlraj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hongshengwenyu.top/Article/details/gt2capygtjc.html

[S15] C：类型转换
来源：http://dali.tian-w.cn/Article/details/gt2esxgfktp.html

(double) a / b
来源：http://dali.yj20258888.top/Article/details/gt2hcnxzdbj.html

[S16] C：位操作置位
来源：http://dali.birdmap.top/Article/details/gt2kbljzaxr.html

x |= (1 << 3);
来源：http://dali.ydzc1.top/Article/details/gt2glwfgzpn.html

[S17] C：安全拼接字符串
来源：http://dali.xuanzx.com/Article/details/gt2uxixydte.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinqigfzy.top/Article/details/gt2safyystu.html

[S18] C：命令行参数
来源：http://dali.aibaodan.cn/Article/details/gt2tcgysoic.html

int main(int argc, char **argv)
来源：http://dali.yonumen.top/Article/details/gt2itsahqik.html

[S19] C：快速排序
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ivnzyezx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gt2nyxrcibz.html

[S20] C：二分查找
来源：http://dali.feifeiyinyue.top/Article/details/gt2ogvvczux.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yonumen.top/Article/details/gt2oskrkkgf.html

[S21] C：字符类别判断
来源：http://dali.yangfankeji.com/Article/details/gt2uzgymkmk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hammf.cn/Article/details/gt2baeckjws.html

[S22] C：字符串转数字
来源：http://dali.aizwys.cn/Article/details/gt2cdvioonc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.vqdsnc.cn/Article/details/gt2ncjktygl.html

[S23] C：随机数
来源：http://dali.chenjidiqi.icu/Article/details/gt2jihjhlck.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.iojbl.cn/Article/details/gt2caivcnxp.html

[S24] C：获取本地时间
来源：http://dali.iojbl.cn/Article/details/gt2fucxdclg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj20258888.top/Article/details/gt2gdnkbvve.html

[S25] C：内存拷贝
来源：http://dali.xinyue.icu/Article/details/gt2nqkcwwlk.html

memcpy(dst, src, n);
来源：http://dali.nwbrower.top/Article/details/gt2ldvfzvru.html

[S26] C：内存清零
来源：http://dali.shangyingyoupin.top/Article/details/gt2uexwxapa.html

memset(a, 0, sizeof a);
来源：http://dali.cqqwz.cn/Article/details/gt2xnzfqgix.html

[S27] C：定义常量
来源：http://dali.zycfv.cn/Article/details/gt2atdwjpyz.html

const double PI = 3.14159;
来源：http://dali.yongpay.top/Article/details/gt2xfrxohlr.html

[S28] C：静态变量
来源：http://dali.yueranfly.top/Article/details/gt2zpxqruut.html

static int counter = 0;
来源：http://dali.daria6918.cn/Article/details/gt2xocrhajd.html

[S29] C：变参函数
来源：http://dali.gotoacloud.top/Article/details/gt2jgkjgdjj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.birdmap.top/Article/details/gt2nvkcimtg.html

[S30] C：头文件保护
来源：http://dali.kuanghao11.cn/Article/details/gt2dsumcnqc.html

#ifndef X_H
来源：http://dali.cqqwz.cn/Article/details/gt2wkzgucri.html

#define X_H
来源：http://dali.tianlin.xyz/Article/details/gt2jpobfozq.html

#endif
来源：http://dali.yongpay.top/Article/details/gt2tchbvilv.html

[S31] C++：Hello World
来源：http://dali.xziqi.cn/Article/details/gt2tdvsddcf.html

#include <iostream>
来源：http://dali.chenjidiqi.icu/Article/details/gt2tqnlrlsl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shzxlz.cn/Article/details/gt2rfjaudhx.html

[S32] C++：字符串
来源：http://dali.havefunace.top/Article/details/gt2hjkkhqhg.html

std::string s = "hi";  s += "!";
来源：http://dali.yj20258888.top/Article/details/gt2rvqruhjp.html

[S33] C++：vector 增删
来源：http://dali.316326.xyz/Article/details/gt2dujyjeoa.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.pengpengdd.cyou/Article/details/gt2cqtoqter.html

[S34] C++：遍历 vector
来源：http://dali.jqgufenzy.top/Article/details/gt2xhzqvikz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xziqi.cn/Article/details/gt2wupwoega.html

[S35] C++：map
来源：http://dali.chenjidiqi.icu/Article/details/gt2qyrimlul.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gt2jsuygkww.html

[S36] C++：unordered_map
来源：http://dali.jianghu66.top/Article/details/gt2acfjnhbj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2shdopsia.html

[S37] C++：set
来源：http://dali.birdmap.top/Article/details/gt2pugupacm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yanxiufei.cn/Article/details/gt2rvjflrsa.html

[S38] C++：排序
来源：http://dali.zycfv.cn/Article/details/gt2xapurztf.html

std::sort(v.begin(), v.end());
来源：http://dali.meibo888.top/Article/details/gt2btfisfwy.html

[S39] C++：自定义比较器排序
来源：http://dali.wangshuangyany.cn/Article/details/gt2jocosnzr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cqqwz.cn/Article/details/gt2fpczsjnx.html

[S40] C++：查找元素
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lnydvudo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mmclafth.html

[S41] C++：类与构造函数
来源：http://dali.mhx1999.top/Article/details/gt2gbckxibo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.snrcjt.cn/Article/details/gt2lurmhzfp.html

[S42] C++：继承与虚函数
来源：http://dali.pycfn.com/Article/details/gt2stpdoalw.html

class B : public Base { public: void f() override {} };
来源：http://dali.kuanghao11.cn/Article/details/gt2lxssarii.html

[S43] C++：智能指针
来源：http://dali.shzxlz.cn/Article/details/gt2mijurezv.html

auto p = std::make_unique<int>(5);
来源：http://dali.hongshengwenyu.top/Article/details/gt2uafuczzr.html

[S44] C++：引用传参
来源：http://dali.chenlongwang.top/Article/details/gt2xomgptvh.html

void inc(int &x) { ++x; }
来源：http://dali.andypj.xyz/Article/details/gt2glzrrvkf.html

[S45] C++：lambda
来源：http://dali.yj20258888.top/Article/details/gt2mvjgzyle.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yuanzhike.top/Article/details/gt2qhckergj.html

[S46] C++：函数模板
来源：http://dali.bjfxy.top/Article/details/gt2lumetapy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.wangdashe.top/Article/details/gt2vxwhevuz.html

[S47] C++：结构化绑定遍历
来源：http://dali.cucudq.cn/Article/details/gt2zodizpcv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hnxiangtu.top/Article/details/gt2kmevadmz.html

[S48] C++：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gt2kaxfevuz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sysykeji.top/Article/details/gt2zawjxfet.html

while (std::getline(in, line)) { }
来源：http://dali.yj202588.top/Article/details/gt2otpsrzuv.html

[S49] C++：写文件
来源：http://dali.cashguo.top/Article/details/gt2pspepqor.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yvedp.cn/Article/details/gt2uxgvydbr.html

[S50] C++：格式化数字
来源：http://dali.sufxvd.cn/Article/details/gt2xlzbghom.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gt2gbbzpazr.html

[S51] C++：显式类型转换
来源：http://dali.tian-w.cn/Article/details/gt2gapeikgk.html

static_cast<double>(a) / b
来源：http://dali.shangyingyoupin.top/Article/details/gt2amngokfs.html

[S52] C++：const 与 noexcept
来源：http://dali.zhengqikj.top/Article/details/gt2ulcsglld.html

int size() const noexcept { return n_; }
来源：http://dali.ybcxt.top/Article/details/gt2qfniycxq.html

[S53] C++：移动语义
来源：http://dali.iojbl.cn/Article/details/gt2kvhvymlv.html

std::vector<int> w = std::move(v);
来源：http://dali.kuanghao11.cn/Article/details/gt2eikfvmav.html

[S54] C++：异常处理
来源：http://dali.cdnleiting.top/Article/details/gt2ixsddurr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sxryk.cn/Article/details/gt2kdcvtmsu.html

[S55] C++：结构化绑定
来源：http://dali.sweek.top/Article/details/gt2ucebwgam.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nwbrower.top/Article/details/gt2meuibrvl.html

[S56] C++：optional
来源：http://dali.zhiwuduotai.top/Article/details/gt2rudqwwyn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shzxlz.cn/Article/details/gt2rkxxzldb.html

[S57] C++：编译期常量
来源：http://dali.gzhubu.top/Article/details/gt2prtpujsk.html

constexpr int N = 10;
来源：http://dali.tianlin.xyz/Article/details/gt2qfiernlg.html

[S58] C++：命名空间
来源：http://dali.dianchejie.cn/Article/details/gt2xdgkprah.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhongyouzk.top/Article/details/gt2chuoujhp.html

[S59] C++：静态断言
来源：http://dali.chenlongwang.top/Article/details/gt2oakiysik.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gogol.net.cn/Article/details/gt2sonxkrbu.html

[S60] C++：遍历并删除元素
来源：http://dali.shangyingyoupin.top/Article/details/gt2ogmafhlw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shangyingyoupin.top/Article/details/gt2ngdvizpf.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2ktngjdlz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jqeprhzj.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2qsisxepe.html

[T01] Kotlin：Hello World
来源：http://dali.tanke756.top/Article/details/gt2sjvnoiye.html

println("Hello")
来源：http://dali.daxiang520.top/Article/details/gt2nmscbgec.html

[T02] Kotlin：变量
来源：http://dali.iojbl.cn/Article/details/gt2mccfrtve.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.snrcjt.cn/Article/details/gt2kvkdtmyi.html

[T03] Kotlin：字符串模板
来源：http://dali.yongpay.top/Article/details/gt2gbtxsezc.html

"值: $b"
来源：http://dali.hywenlv.cn/Article/details/gt2rlqohyuf.html

[T04] Kotlin：空安全
来源：http://dali.jqgfzy.top/Article/details/gt2tkutryhv.html

val n: String? = null;  n?.length
来源：http://dali.gotoacloud.top/Article/details/gt2jjtiefig.html

[T05] Kotlin：when 表达式
来源：http://dali.jianghu66.top/Article/details/gt2mbdlwpgf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.kuanghao11.cn/Article/details/gt2dpbawbqu.html

[T06] Kotlin：集合映射
来源：http://dali.snrcjt.cn/Article/details/gt2lhkfqusq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinqigfzy.top/Article/details/gt2rfojyjcy.html

[T07] Kotlin：集合过滤
来源：http://dali.fzhhl.top/Article/details/gt2ocsfdfae.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ydzc1.top/Article/details/gt2pkwybrwp.html

[T08] Kotlin：数据类
来源：http://dali.daria6918.cn/Article/details/gt2ewfbazph.html

data class User(val name: String, val age: Int)
来源：http://dali.andypj.xyz/Article/details/gt2qspnoqtp.html

[T09] Kotlin：扩展函数
来源：http://dali.tian-w.cn/Article/details/gt2znvkkddq.html

fun String.exclaim() = this + "!"
来源：http://dali.zdqjudy.top/Article/details/gt2xxrcfveo.html

[T10] Kotlin：默认参数
来源：http://dali.dashuyun.cn/Article/details/gt2uzgccpwj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nanegwyf.html

[T11] Kotlin：协程
来源：http://dali.ivvv.top/Article/details/gt2hcxcojfr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yvedp.cn/Article/details/gt2zmtfbbkh.html

[T12] Kotlin：解构声明
来源：http://dali.tanke756.top/Article/details/gt2dtriejtq.html

val (a, b) = Pair(1, 2)
来源：http://dali.nwbrower.top/Article/details/gt2jkzvykjf.html

[T13] Kotlin：只读 Map
来源：http://dali.yanxiufei.cn/Article/details/gt2dtqtoluq.html

val m = mapOf("a" to 1)
来源：http://dali.dashuyun.cn/Article/details/gt2rgaqaxtc.html

[T14] Kotlin：循环
来源：http://dali.jinghuilouyu.cn/Article/details/gt2daceffzi.html

for (i in 1..10) println(i)
来源：http://dali.zhongyouzk.top/Article/details/gt2ujmmetoy.html

[T15] Kotlin：接口
来源：http://dali.birdmap.top/Article/details/gt2hizqhkke.html

interface Shape { fun area(): Double }
来源：http://dali.svipenyu.cn/Article/details/gt2rkzkbota.html

[T16] Swift：Hello World
来源：http://dali.tian-w.cn/Article/details/gt2zwfyewit.html

print("Hello")
来源：http://dali.c1oappe.top/Article/details/gt2faoupbkm.html

[T17] Swift：变量与常量
来源：http://dali.ivvv.top/Article/details/gt2pvgjomzz.html

var a = 1;  let b = 2
来源：http://dali.jiagoushi.top/Article/details/gt2brckjgrx.html

[T18] Swift：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gt2nuykovyw.html

"值: \(b)"
来源：http://dali.wangdashe.top/Article/details/gt2puyvlpxp.html

[T19] Swift：可选绑定
来源：http://dali.havefunace.top/Article/details/gt2jpxtbvzh.html

if let n = opt { print(n) }
来源：http://dali.nanxinkj.top/Article/details/gt2cusawbxx.html

[T20] Swift：数组操作
来源：http://dali.haohaochexian.top/Article/details/gt2pngjqizb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.vqdsnc.cn/Article/details/gt2wfhluvzt.html

[T21] Swift：遍历
来源：http://dali.xylfe.cn/Article/details/gt2efnncnxm.html

for x in a { print(x) }
来源：http://dali.dashuyun.cn/Article/details/gt2jbhvpisk.html

[T22] Swift：字典
来源：http://dali.nanxuanxn.top/Article/details/gt2tbmqiruh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hywenlv.cn/Article/details/gt2otauzcft.html

[T23] Swift：函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2gynvtbjl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tanke756.top/Article/details/gt2gegnwbvs.html

[T24] Swift：闭包
来源：http://dali.bjfxy.top/Article/details/gt2qxkubbyz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hnqzz.top/Article/details/gt2pbyjhbxe.html

[T25] Swift：结构体
来源：http://dali.cqqwz.cn/Article/details/gt2frvyqdwq.html

struct P { var x: Int }
来源：http://dali.xuanzx.com/Article/details/gt2pezcyvjq.html

[T26] Swift：类与重写
来源：http://dali.snrcjt.cn/Article/details/gt2atizvgha.html

class A: Base { override func f() {} }
来源：http://dali.gzhubu.top/Article/details/gt2cigqantf.html

[T27] Swift：错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iuabxrtl.html

do { try f() } catch { print(error) }
来源：http://dali.guannengcc.top/Article/details/gt2xixscovk.html

[T28] Swift：枚举
来源：http://dali.zhengqikj.top/Article/details/gt2ybdmolwh.html

enum Color { case red, green }
来源：http://dali.c1oappe.top/Article/details/gt2orwowjhq.html

[T29] Swift：guard 提前返回
来源：http://dali.zdqjudy.top/Article/details/gt2gpsbqaaf.html

guard let x = opt else { return }
来源：http://dali.sufxvd.cn/Article/details/gt2hqosbxap.html

[T30] Swift：协议
来源：http://dali.gogol.net.cn/Article/details/gt2abtqzgib.html

protocol Shape { func area() -> Double }
来源：http://dali.ydzc1.top/Article/details/gt2kbyreusc.html

[T31] Lua：Hello World
来源：http://dali.sweek.top/Article/details/gt2bzslilum.html

print("Hello")
来源：http://dali.wangdashe.top/Article/details/gt2hnusqlzw.html

[T32] Lua：局部变量
来源：http://dali.sufxvd.cn/Article/details/gt2nivztbch.html

local a = 1
来源：http://dali.smart0.xyz/Article/details/gt2ozsiabog.html

[T33] Lua：表（数组）
来源：http://dali.ehwqpu.com/Article/details/gt2qxbnupar.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkogzkx.html

[T34] Lua：遍历表
来源：http://dali.yonumen.top/Article/details/gt2cmdfxxly.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hnxiangtu.top/Article/details/gt2fhavrftt.html

[T35] Lua：字典表
来源：http://dali.ehwqpu.com/Article/details/gt2wswygmez.html

local d = { a = 1 };  d.b = 2
来源：http://dali.dashuyun.cn/Article/details/gt2wyfvlqwo.html

[T36] Lua：函数
来源：http://dali.fzhhl.top/Article/details/gt2oicusfnd.html

function add(a, b) return a + b end
来源：http://dali.tanke756.top/Article/details/gt2paodwxye.html

[T37] Lua：字符串拼接
来源：http://dali.gogol.net.cn/Article/details/gt2uvozgoqo.html

"a" .. "b"
来源：http://dali.yuxming.cn/Article/details/gt2wpcuxjhk.html

[T38] Lua：条件
来源：http://dali.gotoacloud.top/Article/details/gt2avxggkoc.html

if x > 0 then print("正") end
来源：http://dali.jianghu66.top/Article/details/gt2akaaxhfi.html

[T39] Lua：模式匹配
来源：http://dali.c1oappe.top/Article/details/gt2nynqzjke.html

string.find(s, "%d+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nqpcncrf.html

[T40] Lua：元表
来源：http://dali.tianlin.xyz/Article/details/gt2ushsjffz.html

setmetatable({}, { __index = base })
来源：http://dali.zhoulong.xyz/Article/details/gt2jwtwaejo.html

[T41] Perl：Hello World
来源：http://dali.tanke756.top/Article/details/gt2peagoiod.html

print "Hello\n";
来源：http://dali.cashguo.top/Article/details/gt2clfdckvo.html

[T42] Perl：变量类型
来源：http://dali.jqgfzy.top/Article/details/gt2yfbkphrq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhongyouzk.top/Article/details/gt2qaaicxyx.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbtirlk.html

"值: $a"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qzhxahju.html

[T44] Perl：条件
来源：http://dali.yj202588.top/Article/details/gt2svazeocy.html

if ($a > 0) { print "正"; }
来源：http://dali.daxiang520.top/Article/details/gt2bppytulr.html

[T45] Perl：数组遍历
来源：http://dali.pengpengdd.cyou/Article/details/gt2goemkstu.html

for my $x (@arr) { print $x; }
来源：http://dali.sufxvd.cn/Article/details/gt2pcfpwudx.html

[T46] Perl：哈希操作
来源：http://dali.ydzc1.top/Article/details/gt2ggbezles.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gotoacloud.top/Article/details/gt2hawtuycx.html

[T47] Perl：正则捕获
来源：http://dali.hywenlv.cn/Article/details/gt2msmkibfx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.daxiang520.top/Article/details/gt2kelsucpr.html

[T48] Perl：正则替换
来源：http://dali.kuanghao11.cn/Article/details/gt2izjluuid.html

$s =~ s/old/new/g;
来源：http://dali.jiagoushi.top/Article/details/gt2auudbiig.html

[T49] Perl：函数
来源：http://dali.yvedp.cn/Article/details/gt2qdkkafao.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gt2fnbfalax.html

[T50] Perl：逐行读文件
来源：http://dali.cucudq.cn/Article/details/gt2poltknby.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yj20258888.top/Article/details/gt2zlxqnrpd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinqigfzy.top/Article/details/gt2qayyuhdi.html

[T51] Scala：Hello World
来源：http://dali.xylfe.cn/Article/details/gt2omidxqiz.html

println("Hello")
来源：http://dali.xziqi.cn/Article/details/gt2tzfbbano.html

[T52] Scala：变量
来源：http://dali.dashuyun.cn/Article/details/gt2ihlwyysr.html

val a = 1;  var b = 2
来源：http://dali.jinqigufen.top/Article/details/gt2xufxlpps.html

[T53] Scala：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gt2hbntojwa.html

s"值: $b"
来源：http://dali.gzhubu.top/Article/details/gt2dggvephn.html

[T54] Scala：集合映射
来源：http://dali.jqgfzy.top/Article/details/gt2cqfhvmjw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.aizwys.cn/Article/details/gt2ujmgxkgp.html

[T55] Scala：集合过滤
来源：http://dali.yuxming.cn/Article/details/gt2aamqpahv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.chenlongwang.top/Article/details/gt2yljygtrd.html

[T56] Scala：样例类
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kvxxfjjz.html

case class User(name: String, age: Int)
来源：http://dali.xziqi.cn/Article/details/gt2rcspbzsu.html

[T57] Scala：模式匹配
来源：http://dali.yangfankeji.com/Article/details/gt2qxqtcyne.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhixingplan.top/Article/details/gt2tkpggbqb.html

[T58] Scala：函数定义
来源：http://dali.xziqi.cn/Article/details/gt2jplmwcvr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jiagoushi.top/Article/details/gt2kenkeuob.html

[T59] Scala：循环
来源：http://dali.redwolf501.top/Article/details/gt2dcnhmdtg.html

for (i <- 1 to 10) println(i)
来源：http://dali.havefunace.top/Article/details/gt2bcrmwogq.html

[T60] Scala：折叠
来源：http://dali.wangdashe.top/Article/details/gt2ihjugoig.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhixingplan.top/Article/details/gt2lgmufhie.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2wlckaovc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yanxiufei.cn/Article/details/gt2manmqanl.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2lgmzagwg.html

[U01] Py：创建虚拟环境
来源：http://dali.zhongyouzk.top/Article/details/gt2czwurtpq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shuidangran.top/Article/details/gt2ooqlopbb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cqqwz.cn/Article/details/gt2qlmkmgho.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.guannengcc.top/Article/details/gt2llohskqm.html

[U03] Py：加载 .env 配置
来源：http://dali.zhengqikj.top/Article/details/gt2lwbujkec.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fuijufbc.html

[U04] Py：变量调试打印
来源：http://dali.dianchejie.cn/Article/details/gt2esqvlptt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.wangdashe.top/Article/details/gt2nfxvkjoo.html

[U05] Py：列表去重且保序
来源：http://dali.kuanghao11.cn/Article/details/gt2bcelxibn.html

list(dict.fromkeys(arr))
来源：http://dali.tianlin.xyz/Article/details/gt2otnsasls.html

[U06] Py：合并两个字典
来源：http://dali.xinyue.icu/Article/details/gt2fprjqbwx.html

{**a, **b}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mnnjmgmu.html

[U07] Py：反转字典键值
来源：http://dali.wangdashe.top/Article/details/gt2nkydlyxg.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2agekrfea.html

[U08] Py：展平二维列表
来源：http://dali.xuanzx.com/Article/details/gt2dvpaajdv.html

[y for x in nested for y in x]
来源：http://dali.daria6918.cn/Article/details/gt2kjizxhlz.html

[U09] Py：字典取最大值的键
来源：http://dali.shuidangran.top/Article/details/gt2bfcggopd.html

max(d, key=d.get)
来源：http://dali.aibaodan.cn/Article/details/gt2edpaxzjx.html

[U10] Py：按值排序字典
来源：http://dali.dashuyun.cn/Article/details/gt2zqlupyvw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.daria6918.cn/Article/details/gt2tvjfluwb.html

[U11] Py：生成器表达式
来源：http://dali.jqgfzy.top/Article/details/gt2fumwzzxg.html

(x * 2 for x in arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2xtwmnags.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.pengpengdd.cyou/Article/details/gt2ntfzgzdm.html

Counter(arr).most_common(3)
来源：http://dali.jlsjyb.cn/Article/details/gt2ekbftwbj.html


<!-- 参考信息 -->