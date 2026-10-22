代发 wailian999

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sweek.top/Article/details/gt2krurfgsc.html

[R72] 等待端口就绪
来源：http://dali.shuidangran.top/Article/details/gt2ligfahht.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hnqzz.top/Article/details/gt2bporuvoe.html

[R73] 分割大日志
来源：http://dali.ivvv.top/Article/details/gt2xbigyekr.html

split -l 1000 big.log part_
来源：http://dali.sufxvd.cn/Article/details/gt2jiwdulxu.html

[R74] 批量重命名
来源：http://dali.xuanzx.com/Article/details/gt2eooxoyqs.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhengqikj.top/Article/details/gt2lfjstxix.html

[R75] 导出环境变量
来源：http://dali.shzxlz.cn/Article/details/gt2bpbgorwr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shzxlz.cn/Article/details/gt2twnxhzup.html

[R76] 使用临时文件
来源：http://dali.yongpay.top/Article/details/gt2eyfgsraq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhiwuduotai.top/Article/details/gt2ykghlwlq.html

[R77] 读取用户输入
来源：http://dali.yuxming.cn/Article/details/gt2votwdebc.html

read -rp "请输入: " ans
来源：http://dali.sxryk.cn/Article/details/gt2vmeqkutg.html

[R78] 交互式菜单
来源：http://dali.cucudq.cn/Article/details/gt2wrukjiwe.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhoulong.xyz/Article/details/gt2kqkikgti.html

[R79] 解析命令行选项
来源：http://dali.zdqjudy.top/Article/details/gt2drrvcuzo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yuanzhike.top/Article/details/gt2mcbslklc.html

[R80] 查看脚本执行耗时
来源：http://dali.sysykeji.top/Article/details/gt2yfjjrunn.html

time ./run.sh
来源：http://dali.fengsongda.top/Article/details/gt2wzpazwtz.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2blsolbqk.html

S. C / C++ 专题
来源：http://dali.fengsongda.top/Article/details/gt2htvaulzm.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2ekyasrbj.html

[S01] C：Hello World
来源：http://dali.xinyue.icu/Article/details/gt2kajntnrn.html

#include <stdio.h>
来源：http://dali.zdqjudy.top/Article/details/gt2oecfhfbe.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.andypj.xyz/Article/details/gt2lbojxsvh.html

[S02] C：变量与格式化输出
来源：http://dali.jqgufenzy.top/Article/details/gt2zgwzmrlb.html

int a = 10; printf("%d\n", a);
来源：http://dali.fzhhl.top/Article/details/gt2zyqcjdht.html

[S03] C：读入整数
来源：http://dali.yonumen.top/Article/details/gt2mcqdfact.html

int x; scanf("%d", &x);
来源：http://dali.c1oappe.top/Article/details/gt2ahaxukbr.html

[S04] C：字符串复制
来源：http://dali.andypj.xyz/Article/details/gt2ignrzlsu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hxbbftxz.html

[S05] C：字符串长度
来源：http://dali.jiagoushi.top/Article/details/gt2uiuhtzxl.html

strlen(s)
来源：http://dali.ydzc1.top/Article/details/gt2dwwuzxqr.html

[S06] C：字符串比较
来源：http://dali.hammf.cn/Article/details/gt2eauxvjhk.html

strcmp(a, b) == 0
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2psvrvsxj.html

[S07] C：数组遍历求和
来源：http://dali.jianghu66.top/Article/details/gt2orfdzkyq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hammf.cn/Article/details/gt2vkoowoug.html

[S08] C：动态内存分配与释放
来源：http://dali.jinqigufen.top/Article/details/gt2fimoewxb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sweek.top/Article/details/gt2raucmvkg.html

[S09] C：结构体定义与初始化
来源：http://dali.zhiwuduotai.top/Article/details/gt2igmhvpwv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj20258888.top/Article/details/gt2vjqaejtk.html

[S10] C：指针与解引用
来源：http://dali.xylfe.cn/Article/details/gt2hovamjlr.html

int *p = &a;  *p = 5;
来源：http://dali.tian-w.cn/Article/details/gt2pjkwwvui.html

[S11] C：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gt2mzzdmrdy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.dashuyun.cn/Article/details/gt2sgolvxms.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jiagoushi.top/Article/details/gt2lmlbxlyq.html

fclose(f);
来源：http://dali.dianchejie.cn/Article/details/gt2ssdwwnth.html

[S12] C：写文件
来源：http://dali.zdqjudy.top/Article/details/gt2xpmlojqz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jlsjyb.cn/Article/details/gt2khqalfqq.html

[S13] C：宏定义
来源：http://dali.jinqigufen.top/Article/details/gt2utkhuywo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhoulong.xyz/Article/details/gt2jbeoqiua.html

[S14] C：枚举
来源：http://dali.meibo888.top/Article/details/gt2xdkmmddo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yj20258888.top/Article/details/gt2dtgdffnr.html

[S15] C：类型转换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2altgslyw.html

(double) a / b
来源：http://dali.jianghu66.top/Article/details/gt2lszqynif.html

[S16] C：位操作置位
来源：http://dali.c1oappe.top/Article/details/gt2tixwpfba.html

x |= (1 << 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dgcgqfqu.html

[S17] C：安全拼接字符串
来源：http://dali.yonumen.top/Article/details/gt2cgullroi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yuxming.cn/Article/details/gt2nwudgcbm.html

[S18] C：命令行参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qibqjyxk.html

int main(int argc, char **argv)
来源：http://dali.jlsjyb.cn/Article/details/gt2tsvvzvhv.html

[S19] C：快速排序
来源：http://dali.daxiang520.top/Article/details/gt2vssibibj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gt2pvhopbbu.html

[S20] C：二分查找
来源：http://dali.tianlin.xyz/Article/details/gt2poymhsio.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gzhubu.top/Article/details/gt2mercfxbg.html

[S21] C：字符类别判断
来源：http://dali.zhengqikj.top/Article/details/gt2uoulaylh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.daria6918.cn/Article/details/gt2nclychxf.html

[S22] C：字符串转数字
来源：http://dali.jlsjyb.cn/Article/details/gt2avuzazcf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.vqdsnc.cn/Article/details/gt2tgotqawr.html

[S23] C：随机数
来源：http://dali.zhongyouzk.top/Article/details/gt2orcbwgal.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tianlin.xyz/Article/details/gt2xxhmffzt.html

[S24] C：获取本地时间
来源：http://dali.vqdsnc.cn/Article/details/gt2kmgwiqdo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.c1oappe.top/Article/details/gt2oobgchia.html

[S25] C：内存拷贝
来源：http://dali.yj20258888.top/Article/details/gt2dmqdcvub.html

memcpy(dst, src, n);
来源：http://dali.yonumen.top/Article/details/gt2xqehpols.html

[S26] C：内存清零
来源：http://dali.chenzaomai.com/Article/details/gt2kcszotev.html

memset(a, 0, sizeof a);
来源：http://dali.ppjwa.cn/Article/details/gt2dnfpuynh.html

[S27] C：定义常量
来源：http://dali.hongshengwenyu.top/Article/details/gt2urqkjfxe.html

const double PI = 3.14159;
来源：http://dali.meibo888.top/Article/details/gt2yswgcgsf.html

[S28] C：静态变量
来源：http://dali.xinyue.icu/Article/details/gt2xeickmws.html

static int counter = 0;
来源：http://dali.jqgfzy.top/Article/details/gt2lfiwbcit.html

[S29] C：变参函数
来源：http://dali.zycfv.cn/Article/details/gt2yleoyqjh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xuanzx.com/Article/details/gt2xjaxksrn.html

[S30] C：头文件保护
来源：http://dali.dashuyun.cn/Article/details/gt2qcbnxksl.html

#ifndef X_H
来源：http://dali.nanxinkj.top/Article/details/gt2awgnnxss.html

#define X_H
来源：http://dali.hammf.cn/Article/details/gt2yhcurphk.html

#endif
来源：http://dali.yonumen.top/Article/details/gt2sttxmsfl.html

[S31] C++：Hello World
来源：http://dali.xziqi.cn/Article/details/gt2ctudloks.html

#include <iostream>
来源：http://dali.ydzc1.top/Article/details/gt2uauckjaa.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.aizwys.cn/Article/details/gt2mcpvjkol.html

[S32] C++：字符串
来源：http://dali.jinqigufen.top/Article/details/gt2xkyfonhi.html

std::string s = "hi";  s += "!";
来源：http://dali.nanxuanxn.top/Article/details/gt2tfaxltji.html

[S33] C++：vector 增删
来源：http://dali.xuanzx.com/Article/details/gt2aqvesipg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xylfe.cn/Article/details/gt2cszfduzs.html

[S34] C++：遍历 vector
来源：http://dali.jqgufenzy.top/Article/details/gt2jchfxuiq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.fzhhl.top/Article/details/gt2cgzlfjde.html

[S35] C++：map
来源：http://dali.tanke756.top/Article/details/gt2onsicaxu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gt2ryqmdomr.html

[S36] C++：unordered_map
来源：http://dali.hysaishi.cn/Article/details/gt2grobkljy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zycfv.cn/Article/details/gt2bosmfuuu.html

[S37] C++：set
来源：http://dali.svipenyu.cn/Article/details/gt2cypblbgk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenjidiqi.icu/Article/details/gt2uvxxeykg.html

[S38] C++：排序
来源：http://dali.zdqjudy.top/Article/details/gt2lsxmcvku.html

std::sort(v.begin(), v.end());
来源：http://dali.tianlin.xyz/Article/details/gt2bfwkhutj.html

[S39] C++：自定义比较器排序
来源：http://dali.zhiwuduotai.top/Article/details/gt2qfquwnwu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.andypj.xyz/Article/details/gt2jlfoudtn.html

[S40] C++：查找元素
来源：http://dali.daria6918.cn/Article/details/gt2rjrwaern.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hongshengwenyu.top/Article/details/gt2auliprhh.html

[S41] C++：类与构造函数
来源：http://dali.hywenlv.cn/Article/details/gt2ywintwgd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sysykeji.top/Article/details/gt2gceevjit.html

[S42] C++：继承与虚函数
来源：http://dali.cqqwz.cn/Article/details/gt2nuradqoj.html

class B : public Base { public: void f() override {} };
来源：http://dali.gotoacloud.top/Article/details/gt2szrplyko.html

[S43] C++：智能指针
来源：http://dali.hongshengwenyu.top/Article/details/gt2onmmqdms.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2awrlavif.html

[S44] C++：引用传参
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cvkkcbvx.html

void inc(int &x) { ++x; }
来源：http://dali.yuxming.cn/Article/details/gt2epjitcpo.html

[S45] C++：lambda
来源：http://dali.wangdashe.top/Article/details/gt2xswmnlfk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yuanzhike.top/Article/details/gt2gxdzitfz.html

[S46] C++：函数模板
来源：http://dali.hysaishi.cn/Article/details/gt2prhdeypj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.c1oappe.top/Article/details/gt2zkqjdgti.html

[S47] C++：结构化绑定遍历
来源：http://dali.mhx1999.top/Article/details/gt2gadqtfur.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2tovezkec.html

[S48] C++：逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ohxpjlyx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hnqzz.top/Article/details/gt2rigsbcoc.html

while (std::getline(in, line)) { }
来源：http://dali.cheryme.top/Article/details/gt2rlpqfjcl.html

[S49] C++：写文件
来源：http://dali.cheryme.top/Article/details/gt2vuzyhqwu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhongyouzk.top/Article/details/gt2xodpmeeq.html

[S50] C++：格式化数字
来源：http://dali.gotoacloud.top/Article/details/gt2xxcrogqd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gt2dvdcvktm.html

[S51] C++：显式类型转换
来源：http://dali.sysykeji.top/Article/details/gt2prvuusqi.html

static_cast<double>(a) / b
来源：http://dali.hongshengwenyu.top/Article/details/gt2uwxnihsv.html

[S52] C++：const 与 noexcept
来源：http://dali.snrcjt.cn/Article/details/gt2mxpqzgge.html

int size() const noexcept { return n_; }
来源：http://dali.wangdashe.top/Article/details/gt2xlufxdaf.html

[S53] C++：移动语义
来源：http://dali.xuanzx.com/Article/details/gt2sznhxebf.html

std::vector<int> w = std::move(v);
来源：http://dali.wangshuangyany.cn/Article/details/gt2tvfutwgi.html

[S54] C++：异常处理
来源：http://dali.gogol.net.cn/Article/details/gt2cnzmefwp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.mhx1999.top/Article/details/gt2kgookdjk.html

[S55] C++：结构化绑定
来源：http://dali.snrcjt.cn/Article/details/gt2dgtmwhgr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sxryk.cn/Article/details/gt2segasjxi.html

[S56] C++：optional
来源：http://dali.vqdsnc.cn/Article/details/gt2xcywlene.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.guannengcc.top/Article/details/gt2pqpzmoql.html

[S57] C++：编译期常量
来源：http://dali.hongshengwenyu.top/Article/details/gt2lnjmurgx.html

constexpr int N = 10;
来源：http://dali.nanxuanxn.top/Article/details/gt2xrcwdupc.html

[S58] C++：命名空间
来源：http://dali.cdnleiting.top/Article/details/gt2jarxjugj.html

namespace ns { int f() { return 1; } }
来源：http://dali.jiagoushi.top/Article/details/gt2zztcnzge.html

[S59] C++：静态断言
来源：http://dali.hnxiangtu.top/Article/details/gt2nixvzeun.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sweek.top/Article/details/gt2oiwteres.html

[S60] C++：遍历并删除元素
来源：http://dali.zhixingplan.top/Article/details/gt2pfmmceik.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ppjwa.cn/Article/details/gt2hyzvnlly.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tnwqkbzr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.mhx1999.top/Article/details/gt2hiubcfhc.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2gzlglzrg.html

[T01] Kotlin：Hello World
来源：http://dali.tianlin.xyz/Article/details/gt2lsrpewlv.html

println("Hello")
来源：http://dali.c1oappe.top/Article/details/gt2bugpsfwj.html

[T02] Kotlin：变量
来源：http://dali.vqdsnc.cn/Article/details/gt2zibncbtm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.bjfxy.top/Article/details/gt2pwowscfi.html

[T03] Kotlin：字符串模板
来源：http://dali.kuanghao11.cn/Article/details/gt2brzuuylt.html

"值: $b"
来源：http://dali.feifeiyinyue.top/Article/details/gt2gvbicaks.html

[T04] Kotlin：空安全
来源：http://dali.aibaodan.cn/Article/details/gt2dzfigwbz.html

val n: String? = null;  n?.length
来源：http://dali.shangyingyoupin.top/Article/details/gt2xfggcadf.html

[T05] Kotlin：when 表达式
来源：http://dali.vqdsnc.cn/Article/details/gt2oblpkema.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gaohongyu789.top/Article/details/gt2gvhyfmdj.html

[T06] Kotlin：集合映射
来源：http://dali.aibaodan.cn/Article/details/gt2xdzqywpi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gt2mygnlykl.html

[T07] Kotlin：集合过滤
来源：http://dali.daxiang520.top/Article/details/gt2tpnzfsvy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hnqzz.top/Article/details/gt2xrllcdgv.html

[T08] Kotlin：数据类
来源：http://dali.guowangkeji.top/Article/details/gt2fazuvtfr.html

data class User(val name: String, val age: Int)
来源：http://dali.jinqigufen.top/Article/details/gt2bufhhtmc.html

[T09] Kotlin：扩展函数
来源：http://dali.quarkkingdee.top/Article/details/gt2cqxeqndi.html

fun String.exclaim() = this + "!"
来源：http://dali.nanxinkj.top/Article/details/gt2pqfwfnda.html

[T10] Kotlin：默认参数
来源：http://dali.tian-w.cn/Article/details/gt2gslbiwqz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2soxxxdtr.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2qwuzeasr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.kuanghao11.cn/Article/details/gt2vdximhsa.html

[T12] Kotlin：解构声明
来源：http://dali.zhixingplan.top/Article/details/gt2ktibyvtv.html

val (a, b) = Pair(1, 2)
来源：http://dali.svipenyu.cn/Article/details/gt2soplukdz.html

[T13] Kotlin：只读 Map
来源：http://dali.sweek.top/Article/details/gt2rorevcjy.html

val m = mapOf("a" to 1)
来源：http://dali.xylfe.cn/Article/details/gt2icxlaznq.html

[T14] Kotlin：循环
来源：http://dali.smart0.xyz/Article/details/gt2scdyhzpc.html

for (i in 1..10) println(i)
来源：http://dali.9152youxi.cn/Article/details/gt2nspmmlfs.html

[T15] Kotlin：接口
来源：http://dali.sufxvd.cn/Article/details/gt2ziluvwbs.html

interface Shape { fun area(): Double }
来源：http://dali.chenjidiqi.icu/Article/details/gt2aqhcspwy.html

[T16] Swift：Hello World
来源：http://dali.jiagoushi.top/Article/details/gt2jgkrylnz.html

print("Hello")
来源：http://dali.xuanzx.com/Article/details/gt2xpvjaaxx.html

[T17] Swift：变量与常量
来源：http://dali.yangfankeji.com/Article/details/gt2mwzingok.html

var a = 1;  let b = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zgmenxkj.html

[T18] Swift：字符串插值
来源：http://dali.hywenlv.cn/Article/details/gt2vqyyqajk.html

"值: \(b)"
来源：http://dali.redwolf501.top/Article/details/gt2caejyzxp.html

[T19] Swift：可选绑定
来源：http://dali.jiagoushi.top/Article/details/gt2opjcnqkt.html

if let n = opt { print(n) }
来源：http://dali.tanke756.top/Article/details/gt2mivdgxpr.html

[T20] Swift：数组操作
来源：http://dali.feifeiyinyue.top/Article/details/gt2pgzevjcg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yueranfly.top/Article/details/gt2yhtbrjnb.html

[T21] Swift：遍历
来源：http://dali.316326.xyz/Article/details/gt2loidkued.html

for x in a { print(x) }
来源：http://dali.nanxinkj.top/Article/details/gt2omauvpdi.html

[T22] Swift：字典
来源：http://dali.shangyingyoupin.top/Article/details/gt2tzswqett.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yuxming.cn/Article/details/gt2ynzjzlgi.html

[T23] Swift：函数
来源：http://dali.sxryk.cn/Article/details/gt2mvxafejm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.chenzaomai.com/Article/details/gt2pzdxhsmt.html

[T24] Swift：闭包
来源：http://dali.hnxiangtu.top/Article/details/gt2yymyweba.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shzxlz.cn/Article/details/gt2pblevfdt.html

[T25] Swift：结构体
来源：http://dali.havefunace.top/Article/details/gt2fwbeftdh.html

struct P { var x: Int }
来源：http://dali.smart0.xyz/Article/details/gt2kackkysq.html

[T26] Swift：类与重写
来源：http://dali.tianlin.xyz/Article/details/gt2wprxtnqt.html

class A: Base { override func f() {} }
来源：http://dali.zhongyouzk.top/Article/details/gt2mpztvigo.html

[T27] Swift：错误处理
来源：http://dali.snrcjt.cn/Article/details/gt2orhhdluf.html

do { try f() } catch { print(error) }
来源：http://dali.jiagoushi.top/Article/details/gt2iniwdkar.html

[T28] Swift：枚举
来源：http://dali.yuxming.cn/Article/details/gt2yyytabxe.html

enum Color { case red, green }
来源：http://dali.hysaishi.cn/Article/details/gt2hduczppe.html

[T29] Swift：guard 提前返回
来源：http://dali.havefunace.top/Article/details/gt2bcktormd.html

guard let x = opt else { return }
来源：http://dali.hnxiangtu.top/Article/details/gt2vamomkqj.html

[T30] Swift：协议
来源：http://dali.yangfankeji.com/Article/details/gt2zhuelvpc.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqyfwbp.html

[T31] Lua：Hello World
来源：http://dali.dianchejie.cn/Article/details/gt2wiqmgbgk.html

print("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gt2jyqfgumv.html

[T32] Lua：局部变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gzmjiohx.html

local a = 1
来源：http://dali.snrcjt.cn/Article/details/gt2nllferdo.html

[T33] Lua：表（数组）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ntnnuzwz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yongpay.top/Article/details/gt2isdbwgzf.html

[T34] Lua：遍历表
来源：http://dali.gzhubu.top/Article/details/gt2bxorgvqt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yonumen.top/Article/details/gt2qheoxzti.html

[T35] Lua：字典表
来源：http://dali.ehwqpu.com/Article/details/gt2mabyccdx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.quarkkingdee.top/Article/details/gt2jktcdgze.html

[T36] Lua：函数
来源：http://dali.9152youxi.cn/Article/details/gt2rmzycwyr.html

function add(a, b) return a + b end
来源：http://dali.nanxuanxn.top/Article/details/gt2qrpfwhem.html

[T37] Lua：字符串拼接
来源：http://dali.xuetiantiany.cn/Article/details/gt2kyqmkpod.html

"a" .. "b"
来源：http://dali.yonumen.top/Article/details/gt2panetcda.html

[T38] Lua：条件
来源：http://dali.cdnleiting.top/Article/details/gt2upomnhik.html

if x > 0 then print("正") end
来源：http://dali.birdmap.top/Article/details/gt2cpkhzfjz.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bukrykqa.html

string.find(s, "%d+")
来源：http://dali.chenjidiqi.icu/Article/details/gt2wsqclrap.html

[T40] Lua：元表
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2skfwmvtp.html

setmetatable({}, { __index = base })
来源：http://dali.jqgfzy.top/Article/details/gt2txpvjsbv.html

[T41] Perl：Hello World
来源：http://dali.xziqi.cn/Article/details/gt2xsjocbhv.html

print "Hello\n";
来源：http://dali.ehwqpu.com/Article/details/gt2yrkmagwt.html

[T42] Perl：变量类型
来源：http://dali.yuxming.cn/Article/details/gt2wzkqetgy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.dashuyun.cn/Article/details/gt2iqactrwc.html

[T43] Perl：字符串插值
来源：http://dali.jqgfzy.top/Article/details/gt2pfnkcrby.html

"值: $a"
来源：http://dali.chenlongwang.top/Article/details/gt2cvqvyzxi.html

[T44] Perl：条件
来源：http://dali.xziqi.cn/Article/details/gt2oihsexdf.html

if ($a > 0) { print "正"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dwgeobgh.html

[T45] Perl：数组遍历
来源：http://dali.daria6918.cn/Article/details/gt2aliazcyt.html

for my $x (@arr) { print $x; }
来源：http://dali.hnqzz.top/Article/details/gt2ruiyobwu.html

[T46] Perl：哈希操作
来源：http://dali.316326.xyz/Article/details/gt2rqkorcwt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2pnnroxrx.html

[T47] Perl：正则捕获
来源：http://dali.yueranfly.top/Article/details/gt2fsdduhxv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ydzc1.top/Article/details/gt2uyxnlvlb.html

[T48] Perl：正则替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hhsrkvzc.html

$s =~ s/old/new/g;
来源：http://dali.chenlongwang.top/Article/details/gt2mbrpfapg.html

[T49] Perl：函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kmdinfgl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.aibaodan.cn/Article/details/gt2cyioadal.html

[T50] Perl：逐行读文件
来源：http://dali.yonumen.top/Article/details/gt2ynpncgqt.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2swfdwznp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.iojbl.cn/Article/details/gt2dqytxpts.html

[T51] Scala：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gt2giveolxk.html

println("Hello")
来源：http://dali.cashguo.top/Article/details/gt2aegmjgpp.html

[T52] Scala：变量
来源：http://dali.xziqi.cn/Article/details/gt2zfmnakiy.html

val a = 1;  var b = 2
来源：http://dali.cucudq.cn/Article/details/gt2uqkkpako.html

[T53] Scala：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gt2gffdjalx.html

s"值: $b"
来源：http://dali.hnxiangtu.top/Article/details/gt2zriwprdw.html

[T54] Scala：集合映射
来源：http://dali.zhiwuduotai.top/Article/details/gt2lkjepllu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.redwolf501.top/Article/details/gt2rtwidvux.html

[T55] Scala：集合过滤
来源：http://dali.hongshengwenyu.top/Article/details/gt2zzhudtkj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rkosvpsi.html

[T56] Scala：样例类
来源：http://dali.tanke756.top/Article/details/gt2adkkujdb.html

case class User(name: String, age: Int)
来源：http://dali.ydzc1.top/Article/details/gt2pikwqinq.html

[T57] Scala：模式匹配
来源：http://dali.nwbrower.top/Article/details/gt2aqfzamtf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ehwqpu.com/Article/details/gt2zcusmtwa.html

[T58] Scala：函数定义
来源：http://dali.shangyingyoupin.top/Article/details/gt2byqwemxc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinghuilouyu.cn/Article/details/gt2whmirdim.html

[T59] Scala：循环
来源：http://dali.mhx1999.top/Article/details/gt2djvvqvwc.html

for (i <- 1 to 10) println(i)
来源：http://dali.pycfn.com/Article/details/gt2cfhjpltg.html

[T60] Scala：折叠
来源：http://dali.kuanghao11.cn/Article/details/gt2wkmihjek.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.meibo888.top/Article/details/gt2oydyxriq.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2vjhkbleq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.wangshuangyany.cn/Article/details/gt2dzxwfkor.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2giivobtq.html

[U01] Py：创建虚拟环境
来源：http://dali.cheryme.top/Article/details/gt2syvybpsr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhoulong.xyz/Article/details/gt2pwocedrb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.smart0.xyz/Article/details/gt2xqjtevwl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2pkweecxu.html

[U03] Py：加载 .env 配置
来源：http://dali.jqgufenzy.top/Article/details/gt2hkdavdqj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.bjfxy.top/Article/details/gt2eypfxqne.html

[U04] Py：变量调试打印
来源：http://dali.redwolf501.top/Article/details/gt2crwotege.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shzxlz.cn/Article/details/gt2ttikuljz.html

[U05] Py：列表去重且保序
来源：http://dali.hywenlv.cn/Article/details/gt2kqttqyjb.html

list(dict.fromkeys(arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qtmhqpwc.html

[U06] Py：合并两个字典
来源：http://dali.fzhhl.top/Article/details/gt2huqfaatp.html

{**a, **b}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fpaqykga.html

[U07] Py：反转字典键值
来源：http://dali.ppjwa.cn/Article/details/gt2igneurzo.html

{v: k for k, v in d.items()}
来源：http://dali.iojbl.cn/Article/details/gt2wzvpcqep.html

[U08] Py：展平二维列表
来源：http://dali.sweek.top/Article/details/gt2nglaomis.html

[y for x in nested for y in x]
来源：http://dali.gzhubu.top/Article/details/gt2hcminpzz.html

[U09] Py：字典取最大值的键
来源：http://dali.shangyingyoupin.top/Article/details/gt2xbrwwueo.html

max(d, key=d.get)
来源：http://dali.yuxming.cn/Article/details/gt2kvbmiqnc.html

[U10] Py：按值排序字典
来源：http://dali.smart0.xyz/Article/details/gt2anrebcrm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.quarkkingdee.top/Article/details/gt2bjlfidnh.html

[U11] Py：生成器表达式
来源：http://dali.hnxiangtu.top/Article/details/gt2bdjfzamu.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2itixtlsj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xhwmkvfe.html

Counter(arr).most_common(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ujwkmwuj.html


<!-- 参考信息 -->