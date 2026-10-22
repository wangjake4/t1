代发 wailian999

head -c 16 /dev/urandom | base64
来源：http://dali.daxiang520.top/Article/details/gt2uqymfnam.html

[R70] 时间戳与互转
来源：http://dali.mhx1999.top/Article/details/gt2kncokyib.html

date +%s;  date -d @1700000000
来源：http://dali.quarkkingdee.top/Article/details/gt2dbftnrqx.html

[R71] 日期格式化
来源：http://dali.guannengcc.top/Article/details/gt2yzirqpro.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.redwolf501.top/Article/details/gt2ymzdlgyv.html

[R72] 等待端口就绪
来源：http://dali.ppjwa.cn/Article/details/gt2wgsvfyvv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gogol.net.cn/Article/details/gt2mzjtjjiy.html

[R73] 分割大日志
来源：http://dali.xziqi.cn/Article/details/gt2raierelz.html

split -l 1000 big.log part_
来源：http://dali.ppjwa.cn/Article/details/gt2vljxshzx.html

[R74] 批量重命名
来源：http://dali.gotoacloud.top/Article/details/gt2sxczueiq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yonumen.top/Article/details/gt2qrscpdmo.html

[R75] 导出环境变量
来源：http://dali.jlsjyb.cn/Article/details/gt2ojhcopcy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ivvv.top/Article/details/gt2bthbfary.html

[R76] 使用临时文件
来源：http://dali.hnxiangtu.top/Article/details/gt2ckzjoiyq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hywenlv.cn/Article/details/gt2zziyilpo.html

[R77] 读取用户输入
来源：http://dali.zhiwuduotai.top/Article/details/gt2kgbzxjks.html

read -rp "请输入: " ans
来源：http://dali.bjfxy.top/Article/details/gt2qoaijwlx.html

[R78] 交互式菜单
来源：http://dali.cashguo.top/Article/details/gt2bceagdub.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.guannengcc.top/Article/details/gt2hslvvyny.html

[R79] 解析命令行选项
来源：http://dali.iojbl.cn/Article/details/gt2ntkjdndl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jlsjyb.cn/Article/details/gt2eqhkrerx.html

[R80] 查看脚本执行耗时
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2guaufaao.html

time ./run.sh
来源：http://dali.xziqi.cn/Article/details/gt2lygnekvg.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2dhkjmmym.html

S. C / C++ 专题
来源：http://dali.yj202588.top/Article/details/gt2stqvtgrv.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2jphknbal.html

[S01] C：Hello World
来源：http://dali.aizwys.cn/Article/details/gt2ogkvfwra.html

#include <stdio.h>
来源：http://dali.shuidangran.top/Article/details/gt2vkcovint.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nanxuanxn.top/Article/details/gt2syaobovw.html

[S02] C：变量与格式化输出
来源：http://dali.zhoulong.xyz/Article/details/gt2oogzyptj.html

int a = 10; printf("%d\n", a);
来源：http://dali.hongshengwenyu.top/Article/details/gt2umaywcpz.html

[S03] C：读入整数
来源：http://dali.tian-w.cn/Article/details/gt2tigymmqr.html

int x; scanf("%d", &x);
来源：http://dali.zdqjudy.top/Article/details/gt2xmjbjiqk.html

[S04] C：字符串复制
来源：http://dali.zycfv.cn/Article/details/gt2qefhesgn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2dxuzsptq.html

[S05] C：字符串长度
来源：http://dali.sweek.top/Article/details/gt2imputjkf.html

strlen(s)
来源：http://dali.bjfxy.top/Article/details/gt2upfodygm.html

[S06] C：字符串比较
来源：http://dali.cashguo.top/Article/details/gt2spsuxhif.html

strcmp(a, b) == 0
来源：http://dali.cdnleiting.top/Article/details/gt2gqvfzgqv.html

[S07] C：数组遍历求和
来源：http://dali.yonumen.top/Article/details/gt2oujqdjjq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.iojbl.cn/Article/details/gt2dlsokamm.html

[S08] C：动态内存分配与释放
来源：http://dali.sweek.top/Article/details/gt2kipldmxf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hysaishi.cn/Article/details/gt2kymiaurw.html

[S09] C：结构体定义与初始化
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zsjexzft.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhoulong.xyz/Article/details/gt2ujzlrrkb.html

[S10] C：指针与解引用
来源：http://dali.wangshuangyany.cn/Article/details/gt2zwblzxxb.html

int *p = &a;  *p = 5;
来源：http://dali.sweek.top/Article/details/gt2zalffutc.html

[S11] C：逐行读文件
来源：http://dali.wangdashe.top/Article/details/gt2ntifdgox.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhongyouzk.top/Article/details/gt2xyyrixyc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shzxlz.cn/Article/details/gt2rmjhrowa.html

fclose(f);
来源：http://dali.andypj.xyz/Article/details/gt2xrsstjlp.html

[S12] C：写文件
来源：http://dali.jqgfzy.top/Article/details/gt2vdduizry.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj202588.top/Article/details/gt2sliisjkw.html

[S13] C：宏定义
来源：http://dali.hywenlv.cn/Article/details/gt2epzefvhr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.tianlin.xyz/Article/details/gt2uuncgesb.html

[S14] C：枚举
来源：http://dali.zhixingplan.top/Article/details/gt2usnwqexh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2adavkmkf.html

[S15] C：类型转换
来源：http://dali.hywenlv.cn/Article/details/gt2kefbvjhi.html

(double) a / b
来源：http://dali.sysykeji.top/Article/details/gt2bjpujkpe.html

[S16] C：位操作置位
来源：http://dali.yj20258.top/Article/details/gt2ljqesxwf.html

x |= (1 << 3);
来源：http://dali.yanxiufei.cn/Article/details/gt2zyykfqke.html

[S17] C：安全拼接字符串
来源：http://dali.jyoumei.cn/Article/details/gt2wtmgaean.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hysaishi.cn/Article/details/gt2edfxjeug.html

[S18] C：命令行参数
来源：http://dali.xinyue.icu/Article/details/gt2lomswons.html

int main(int argc, char **argv)
来源：http://dali.feifeiyinyue.top/Article/details/gt2lngmtohu.html

[S19] C：快速排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vvxdvlci.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gaohongyu789.top/Article/details/gt2nwhoipvc.html

[S20] C：二分查找
来源：http://dali.gogol.net.cn/Article/details/gt2eubvuukw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hnqzz.top/Article/details/gt2ijgovity.html

[S21] C：字符类别判断
来源：http://dali.meibo888.top/Article/details/gt2cpzjvgef.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.wangshuangyany.cn/Article/details/gt2hiensvvf.html

[S22] C：字符串转数字
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hztbemiu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.havefunace.top/Article/details/gt2vzmbngoz.html

[S23] C：随机数
来源：http://dali.cheryme.top/Article/details/gt2njbnvhiz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.birdmap.top/Article/details/gt2bykeigvh.html

[S24] C：获取本地时间
来源：http://dali.xuetiantiany.cn/Article/details/gt2gxqdlvyl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.kuanghao11.cn/Article/details/gt2zdgnnaxz.html

[S25] C：内存拷贝
来源：http://dali.cashguo.top/Article/details/gt2lgtsuqyp.html

memcpy(dst, src, n);
来源：http://dali.gaohongyu789.top/Article/details/gt2zqmpzmby.html

[S26] C：内存清零
来源：http://dali.fengsongda.top/Article/details/gt2hyyinhep.html

memset(a, 0, sizeof a);
来源：http://dali.guannengcc.top/Article/details/gt2qelkblib.html

[S27] C：定义常量
来源：http://dali.yuxming.cn/Article/details/gt2lvtoleuh.html

const double PI = 3.14159;
来源：http://dali.xinyue.icu/Article/details/gt2fhbcjumv.html

[S28] C：静态变量
来源：http://dali.ydzc1.top/Article/details/gt2jdcjmgma.html

static int counter = 0;
来源：http://dali.sysykeji.top/Article/details/gt2yegmonub.html

[S29] C：变参函数
来源：http://dali.smart0.xyz/Article/details/gt2evfgfmvg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hywenlv.cn/Article/details/gt2vobjllze.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2etvwevnt.html

#ifndef X_H
来源：http://dali.aibaodan.cn/Article/details/gt2ucazqmoh.html

#define X_H
来源：http://dali.xylfe.cn/Article/details/gt2lzirmzjm.html

#endif
来源：http://dali.ybcxt.top/Article/details/gt2fxqkpesq.html

[S31] C++：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2auffsuuk.html

#include <iostream>
来源：http://dali.wangdashe.top/Article/details/gt2gmpapfpw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhixingplan.top/Article/details/gt2xvvkvlul.html

[S32] C++：字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jypbydeo.html

std::string s = "hi";  s += "!";
来源：http://dali.cashguo.top/Article/details/gt2yahnkdam.html

[S33] C++：vector 增删
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cckvofpo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ogwizhws.html

[S34] C++：遍历 vector
来源：http://dali.ehwqpu.com/Article/details/gt2jdlwjimc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ppjwa.cn/Article/details/gt2iqjbhcvm.html

[S35] C++：map
来源：http://dali.zhiwuduotai.top/Article/details/gt2rhaphfeo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gt2ehsgqlpp.html

[S36] C++：unordered_map
来源：http://dali.jqgfzy.top/Article/details/gt2hnzvhtek.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2nhyiasfq.html

[S37] C++：set
来源：http://dali.svipenyu.cn/Article/details/gt2gnufujha.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinqigfzy.top/Article/details/gt2vdydotbq.html

[S38] C++：排序
来源：http://dali.yangfankeji.com/Article/details/gt2tsyticsa.html

std::sort(v.begin(), v.end());
来源：http://dali.zhiwuduotai.top/Article/details/gt2rkehurgt.html

[S39] C++：自定义比较器排序
来源：http://dali.zhixingplan.top/Article/details/gt2vpunphvp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xxemwnxe.html

[S40] C++：查找元素
来源：http://dali.yuxming.cn/Article/details/gt2mxxwtxfu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xuanzx.com/Article/details/gt2hprmpqqb.html

[S41] C++：类与构造函数
来源：http://dali.mhx1999.top/Article/details/gt2ismprtph.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.c1oappe.top/Article/details/gt2ctezhton.html

[S42] C++：继承与虚函数
来源：http://dali.cqqwz.cn/Article/details/gt2keebnfru.html

class B : public Base { public: void f() override {} };
来源：http://dali.0kj1m.cn/Article/details/gt2egeeghxf.html

[S43] C++：智能指针
来源：http://dali.hongshengwenyu.top/Article/details/gt2qtflwzvf.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fcsuvhlu.html

[S44] C++：引用传参
来源：http://dali.316326.xyz/Article/details/gt2dzapyeok.html

void inc(int &x) { ++x; }
来源：http://dali.tanke756.top/Article/details/gt2udhcovlo.html

[S45] C++：lambda
来源：http://dali.yj20258.top/Article/details/gt2prnqkmek.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jlsjyb.cn/Article/details/gt2jkjkentj.html

[S46] C++：函数模板
来源：http://dali.dianchejie.cn/Article/details/gt2rygzmcwk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.snrcjt.cn/Article/details/gt2fxrjrhcp.html

[S47] C++：结构化绑定遍历
来源：http://dali.haohaochexian.top/Article/details/gt2puaqhefs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hfpthk.cn/Article/details/gt2txoedymt.html

[S48] C++：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gt2udplrsrw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.mhx1999.top/Article/details/gt2bvvgsjhm.html

while (std::getline(in, line)) { }
来源：http://dali.zycfv.cn/Article/details/gt2pzavrsgn.html

[S49] C++：写文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2hlvlvtrm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zycfv.cn/Article/details/gt2npaivmpb.html

[S50] C++：格式化数字
来源：http://dali.ehwqpu.com/Article/details/gt2urqijjdr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yuxming.cn/Article/details/gt2yagzhdbq.html

[S51] C++：显式类型转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2lgiizwjs.html

static_cast<double>(a) / b
来源：http://dali.gzhubu.top/Article/details/gt2ivaevqpx.html

[S52] C++：const 与 noexcept
来源：http://dali.svipenyu.cn/Article/details/gt2yvjxomht.html

int size() const noexcept { return n_; }
来源：http://dali.hnxiangtu.top/Article/details/gt2czjsuagk.html

[S53] C++：移动语义
来源：http://dali.yj20258888.top/Article/details/gt2gazpxnkc.html

std::vector<int> w = std::move(v);
来源：http://dali.ehwqpu.com/Article/details/gt2rbrlpisx.html

[S54] C++：异常处理
来源：http://dali.shuidangran.top/Article/details/gt2hxbrnjcp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hongshengwenyu.top/Article/details/gt2oispceow.html

[S55] C++：结构化绑定
来源：http://dali.tianlin.xyz/Article/details/gt2pubpbzlx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.snrcjt.cn/Article/details/gt2mkdtbnoz.html

[S56] C++：optional
来源：http://dali.ehwqpu.com/Article/details/gt2tbjselqd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.haohaochexian.top/Article/details/gt2pwqrelmq.html

[S57] C++：编译期常量
来源：http://dali.pycfn.com/Article/details/gt2nxtizyui.html

constexpr int N = 10;
来源：http://dali.sweek.top/Article/details/gt2iyikmgjr.html

[S58] C++：命名空间
来源：http://dali.yonumen.top/Article/details/gt2dynnhlif.html

namespace ns { int f() { return 1; } }
来源：http://dali.svipenyu.cn/Article/details/gt2prbcmhci.html

[S59] C++：静态断言
来源：http://dali.birdmap.top/Article/details/gt2rotaryeo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.guannengcc.top/Article/details/gt2yjvefwya.html

[S60] C++：遍历并删除元素
来源：http://dali.yanxiufei.cn/Article/details/gt2pjhajxtg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yongpay.top/Article/details/gt2newmsavq.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2cidyzfuf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jqgufenzy.top/Article/details/gt2qiyocsjl.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2oehkkspw.html

[T01] Kotlin：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gt2auhsguwr.html

println("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gt2tfbjnpsa.html

[T02] Kotlin：变量
来源：http://dali.cqqwz.cn/Article/details/gt2muxlntxk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sysykeji.top/Article/details/gt2ofotbdup.html

[T03] Kotlin：字符串模板
来源：http://dali.svipenyu.cn/Article/details/gt2fbndzxwl.html

"值: $b"
来源：http://dali.ydzc1.top/Article/details/gt2zsduzwxp.html

[T04] Kotlin：空安全
来源：http://dali.yj20258888.top/Article/details/gt2lxxvrbaz.html

val n: String? = null;  n?.length
来源：http://dali.pengpengdd.cyou/Article/details/gt2uetweqrs.html

[T05] Kotlin：when 表达式
来源：http://dali.gogol.net.cn/Article/details/gt2okzuhmpi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tanke756.top/Article/details/gt2fwnwaeep.html

[T06] Kotlin：集合映射
来源：http://dali.jinqigufen.top/Article/details/gt2iqalvbiy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gotoacloud.top/Article/details/gt2duzvrzgz.html

[T07] Kotlin：集合过滤
来源：http://dali.daria6918.cn/Article/details/gt2aqiumlrc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hysaishi.cn/Article/details/gt2bhienhcw.html

[T08] Kotlin：数据类
来源：http://dali.yuxming.cn/Article/details/gt2vxyhighc.html

data class User(val name: String, val age: Int)
来源：http://dali.snrcjt.cn/Article/details/gt2ugyetphz.html

[T09] Kotlin：扩展函数
来源：http://dali.snrcjt.cn/Article/details/gt2fnutpkay.html

fun String.exclaim() = this + "!"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2llhytiej.html

[T10] Kotlin：默认参数
来源：http://dali.shzxlz.cn/Article/details/gt2hsffxxeb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bvvcjiwg.html

[T11] Kotlin：协程
来源：http://dali.aibaodan.cn/Article/details/gt2hlwsrzwl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jyoumei.cn/Article/details/gt2aguvwcfo.html

[T12] Kotlin：解构声明
来源：http://dali.feifeiyinyue.top/Article/details/gt2rmxjbqzb.html

val (a, b) = Pair(1, 2)
来源：http://dali.yj20258888.top/Article/details/gt2kzstsugx.html

[T13] Kotlin：只读 Map
来源：http://dali.aizwys.cn/Article/details/gt2vyfsedwu.html

val m = mapOf("a" to 1)
来源：http://dali.dianchejie.cn/Article/details/gt2pchdijhj.html

[T14] Kotlin：循环
来源：http://dali.vqdsnc.cn/Article/details/gt2qncnqcxg.html

for (i in 1..10) println(i)
来源：http://dali.chenlongwang.top/Article/details/gt2xodjtbve.html

[T15] Kotlin：接口
来源：http://dali.ybcxt.top/Article/details/gt2bdogbhps.html

interface Shape { fun area(): Double }
来源：http://dali.tian-w.cn/Article/details/gt2imncasov.html

[T16] Swift：Hello World
来源：http://dali.haohaochexian.top/Article/details/gt2apyucvjp.html

print("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vtydktdf.html

[T17] Swift：变量与常量
来源：http://dali.yanxiufei.cn/Article/details/gt2ywvpdtst.html

var a = 1;  let b = 2
来源：http://dali.aizwys.cn/Article/details/gt2bdlcndfl.html

[T18] Swift：字符串插值
来源：http://dali.yj202588.top/Article/details/gt2daaisesq.html

"值: \(b)"
来源：http://dali.zhiwuduotai.top/Article/details/gt2dcprvzyu.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2beosuafx.html

if let n = opt { print(n) }
来源：http://dali.kuanghao11.cn/Article/details/gt2cysceajm.html

[T20] Swift：数组操作
来源：http://dali.zhongyouzk.top/Article/details/gt2psieakkg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sweek.top/Article/details/gt2tmcsxpyc.html

[T21] Swift：遍历
来源：http://dali.zhixingplan.top/Article/details/gt2imysocix.html

for x in a { print(x) }
来源：http://dali.birdmap.top/Article/details/gt2wftqhrdn.html

[T22] Swift：字典
来源：http://dali.nanxinkj.top/Article/details/gt2eqqnngji.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.svipenyu.cn/Article/details/gt2hdgesvom.html

[T23] Swift：函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2fufobwbq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.iojbl.cn/Article/details/gt2klqvikxx.html

[T24] Swift：闭包
来源：http://dali.tian-w.cn/Article/details/gt2rgvrzsks.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yangfankeji.com/Article/details/gt2lulbjlep.html

[T25] Swift：结构体
来源：http://dali.shangyingyoupin.top/Article/details/gt2oczfjygy.html

struct P { var x: Int }
来源：http://dali.haohaochexian.top/Article/details/gt2aeeucrsu.html

[T26] Swift：类与重写
来源：http://dali.xylfe.cn/Article/details/gt2krvgctdq.html

class A: Base { override func f() {} }
来源：http://dali.yj202588.top/Article/details/gt2utafkmpp.html

[T27] Swift：错误处理
来源：http://dali.ydzc1.top/Article/details/gt2khbzyvzy.html

do { try f() } catch { print(error) }
来源：http://dali.meibo888.top/Article/details/gt2fxnbislq.html

[T28] Swift：枚举
来源：http://dali.kuanghao11.cn/Article/details/gt2dhnnmtmu.html

enum Color { case red, green }
来源：http://dali.c1oappe.top/Article/details/gt2yacbnjpo.html

[T29] Swift：guard 提前返回
来源：http://dali.fzhhl.top/Article/details/gt2lsujbgtm.html

guard let x = opt else { return }
来源：http://dali.pengpengdd.cyou/Article/details/gt2abfupjlt.html

[T30] Swift：协议
来源：http://dali.ehwqpu.com/Article/details/gt2tukqrgzv.html

protocol Shape { func area() -> Double }
来源：http://dali.shuidangran.top/Article/details/gt2xlvnxxzc.html

[T31] Lua：Hello World
来源：http://dali.mhx1999.top/Article/details/gt2nzcipprj.html

print("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gt2xrjwmlyo.html

[T32] Lua：局部变量
来源：http://dali.kuanghao11.cn/Article/details/gt2ljxwmktp.html

local a = 1
来源：http://dali.tian-w.cn/Article/details/gt2lpsejsxr.html

[T33] Lua：表（数组）
来源：http://dali.gogol.net.cn/Article/details/gt2bidlbsyr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hammf.cn/Article/details/gt2aiviqeqr.html

[T34] Lua：遍历表
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2inaxzwuo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.chenzaomai.com/Article/details/gt2tltrvhfr.html

[T35] Lua：字典表
来源：http://dali.9152youxi.cn/Article/details/gt2scihpgvs.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ivvv.top/Article/details/gt2cbbuqqsj.html

[T36] Lua：函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2ddzjoido.html

function add(a, b) return a + b end
来源：http://dali.chenlongwang.top/Article/details/gt2zedwimwf.html

[T37] Lua：字符串拼接
来源：http://dali.daria6918.cn/Article/details/gt2cuqnovhz.html

"a" .. "b"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2joosqjbo.html

[T38] Lua：条件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rriqkmkv.html

if x > 0 then print("正") end
来源：http://dali.dashuyun.cn/Article/details/gt2nhojjvrn.html

[T39] Lua：模式匹配
来源：http://dali.yangfankeji.com/Article/details/gt2ahrqodtu.html

string.find(s, "%d+")
来源：http://dali.bjfxy.top/Article/details/gt2wmkaywsv.html

[T40] Lua：元表
来源：http://dali.sxryk.cn/Article/details/gt2bffjehkj.html

setmetatable({}, { __index = base })
来源：http://dali.gzhubu.top/Article/details/gt2hoserpqv.html

[T41] Perl：Hello World
来源：http://dali.xylfe.cn/Article/details/gt2pdrdolcx.html

print "Hello\n";
来源：http://dali.sufxvd.cn/Article/details/gt2clpsfato.html

[T42] Perl：变量类型
来源：http://dali.birdmap.top/Article/details/gt2qchonfni.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xziqi.cn/Article/details/gt2wthomlab.html

[T43] Perl：字符串插值
来源：http://dali.aizwys.cn/Article/details/gt2cmibqjrp.html

"值: $a"
来源：http://dali.fengsongda.top/Article/details/gt2nrtlnjtq.html

[T44] Perl：条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2byvdqbar.html

if ($a > 0) { print "正"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2svvptpln.html

[T45] Perl：数组遍历
来源：http://dali.0kj1m.cn/Article/details/gt2pwsizxok.html

for my $x (@arr) { print $x; }
来源：http://dali.hnxiangtu.top/Article/details/gt2bcsqiyfp.html

[T46] Perl：哈希操作
来源：http://dali.nanxinkj.top/Article/details/gt2ifdatuoc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.sufxvd.cn/Article/details/gt2szwvetrx.html

[T47] Perl：正则捕获
来源：http://dali.jiagoushi.top/Article/details/gt2jldggwvo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.gzhubu.top/Article/details/gt2mtsjiied.html

[T48] Perl：正则替换
来源：http://dali.hysaishi.cn/Article/details/gt2gedpvwfx.html

$s =~ s/old/new/g;
来源：http://dali.redwolf501.top/Article/details/gt2pnplkuzv.html

[T49] Perl：函数
来源：http://dali.yongpay.top/Article/details/gt2knyndtwg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2zeirylwk.html

[T50] Perl：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gt2wpsrlaey.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.9152youxi.cn/Article/details/gt2dztxlehs.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2cfkvykpn.html

[T51] Scala：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gt2bwwocoul.html

println("Hello")
来源：http://dali.hnqzz.top/Article/details/gt2htgxfewv.html

[T52] Scala：变量
来源：http://dali.cdnleiting.top/Article/details/gt2wytfbolb.html

val a = 1;  var b = 2
来源：http://dali.havefunace.top/Article/details/gt2htkalsnr.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlwhxuz.html

s"值: $b"
来源：http://dali.zhengqikj.top/Article/details/gt2czygxqtq.html

[T54] Scala：集合映射
来源：http://dali.pycfn.com/Article/details/gt2sfutpaqv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xpvpbwju.html

[T55] Scala：集合过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ylvevtuo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2scjsmrlc.html

[T56] Scala：样例类
来源：http://dali.jqgufenzy.top/Article/details/gt2mhkqobfu.html

case class User(name: String, age: Int)
来源：http://dali.guowangkeji.top/Article/details/gt2hqvgizun.html

[T57] Scala：模式匹配
来源：http://dali.hongshengwenyu.top/Article/details/gt2rjvgtgcj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhongyouzk.top/Article/details/gt2erylitfy.html

[T58] Scala：函数定义
来源：http://dali.hongshengwenyu.top/Article/details/gt2slezpdgy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cdnleiting.top/Article/details/gt2ertfvzcq.html

[T59] Scala：循环
来源：http://dali.yueranfly.top/Article/details/gt2ihurkfvo.html

for (i <- 1 to 10) println(i)
来源：http://dali.tianlin.xyz/Article/details/gt2qopqszav.html

[T60] Scala：折叠
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yreccnuz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.redwolf501.top/Article/details/gt2ctcjgsud.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2mkfmsyet.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2hblozdav.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2cmdifrxy.html

[U01] Py：创建虚拟环境
来源：http://dali.9152youxi.cn/Article/details/gt2crjrxbqw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yuxming.cn/Article/details/gt2mgwsawzv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jianghu66.top/Article/details/gt2pciweaok.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sufxvd.cn/Article/details/gt2ucnsqzod.html

[U03] Py：加载 .env 配置
来源：http://dali.jinqigfzy.top/Article/details/gt2qjtwxjfd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.c1oappe.top/Article/details/gt2qhkspdwa.html

[U04] Py：变量调试打印
来源：http://dali.daria6918.cn/Article/details/gt2qvvtljuv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zdqjudy.top/Article/details/gt2egcriedf.html

[U05] Py：列表去重且保序
来源：http://dali.yj20258.top/Article/details/gt2dikhauoe.html

list(dict.fromkeys(arr))
来源：http://dali.chenzaomai.com/Article/details/gt2fsilrywx.html

[U06] Py：合并两个字典
来源：http://dali.bjfxy.top/Article/details/gt2otqldwdb.html

{**a, **b}
来源：http://dali.cqqwz.cn/Article/details/gt2hvfehyvp.html

[U07] Py：反转字典键值
来源：http://dali.zhongyouzk.top/Article/details/gt2rlfgjqow.html

{v: k for k, v in d.items()}
来源：http://dali.fengsongda.top/Article/details/gt2tmrvsprr.html

[U08] Py：展平二维列表
来源：http://dali.gzhubu.top/Article/details/gt2zizuxsbi.html

[y for x in nested for y in x]
来源：http://dali.zhengqikj.top/Article/details/gt2ydbdkhma.html

[U09] Py：字典取最大值的键
来源：http://dali.tanke756.top/Article/details/gt2jwyvvtca.html

max(d, key=d.get)
来源：http://dali.zhoulong.xyz/Article/details/gt2jbwilaxg.html

[U10] Py：按值排序字典
来源：http://dali.tianlin.xyz/Article/details/gt2hgezxgbq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.aizwys.cn/Article/details/gt2nfalxuln.html


<!-- 参考信息 -->