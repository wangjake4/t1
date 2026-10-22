代发 wailian999

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2mnedawpb.html

[R68] 计算文件校验值
来源：http://dali.yj20258.top/Article/details/gt2dwynjtti.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.aizwys.cn/Article/details/gt2yjxqopaz.html

[R69] 生成随机密码
来源：http://dali.9152youxi.cn/Article/details/gt2qxnnhcqx.html

head -c 16 /dev/urandom | base64
来源：http://dali.aibaodan.cn/Article/details/gt2zxweoood.html

[R70] 时间戳与互转
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2firntqlr.html

date +%s;  date -d @1700000000
来源：http://dali.fzhhl.top/Article/details/gt2oxamvfjh.html

[R71] 日期格式化
来源：http://dali.tanke756.top/Article/details/gt2hjvmgqal.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.dianchejie.cn/Article/details/gt2ipboxfst.html

[R72] 等待端口就绪
来源：http://dali.gotoacloud.top/Article/details/gt2ltkhckhw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shzxlz.cn/Article/details/gt2vuivbhml.html

[R73] 分割大日志
来源：http://dali.ybcxt.top/Article/details/gt2jhzuvjab.html

split -l 1000 big.log part_
来源：http://dali.hnxiangtu.top/Article/details/gt2ioambngp.html

[R74] 批量重命名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yhaurfxx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhengqikj.top/Article/details/gt2ybbyojpu.html

[R75] 导出环境变量
来源：http://dali.yangfankeji.com/Article/details/gt2xzcywidw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gzhubu.top/Article/details/gt2uauwenia.html

[R76] 使用临时文件
来源：http://dali.meibo888.top/Article/details/gt2zvbjgzjr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gaohongyu789.top/Article/details/gt2dfffkgtt.html

[R77] 读取用户输入
来源：http://dali.cqqwz.cn/Article/details/gt2mtwlurmw.html

read -rp "请输入: " ans
来源：http://dali.cheryme.top/Article/details/gt2ptbzajfp.html

[R78] 交互式菜单
来源：http://dali.nanxuanxn.top/Article/details/gt2ftdaigyp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ydzc1.top/Article/details/gt2vyxbspwp.html

[R79] 解析命令行选项
来源：http://dali.daxiang520.top/Article/details/gt2aibxyzjz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.0kj1m.cn/Article/details/gt2jfhhlfsj.html

[R80] 查看脚本执行耗时
来源：http://dali.jianghu66.top/Article/details/gt2vbekpdfb.html

time ./run.sh
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2muiwlvrj.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2ykjbcwbn.html

S. C / C++ 专题
来源：http://dali.bjfxy.top/Article/details/gt2reuvwngf.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2clefarnt.html

[S01] C：Hello World
来源：http://dali.svipenyu.cn/Article/details/gt2zqsqorht.html

#include <stdio.h>
来源：http://dali.jqgfzy.top/Article/details/gt2fmkefkqh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sweek.top/Article/details/gt2eovozchk.html

[S02] C：变量与格式化输出
来源：http://dali.hammf.cn/Article/details/gt2iynceqwd.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhengqikj.top/Article/details/gt2jiojowtt.html

[S03] C：读入整数
来源：http://dali.316326.xyz/Article/details/gt2iggjogen.html

int x; scanf("%d", &x);
来源：http://dali.gotoacloud.top/Article/details/gt2qmtatexs.html

[S04] C：字符串复制
来源：http://dali.chenzaomai.com/Article/details/gt2ssxeynii.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.pycfn.com/Article/details/gt2bexsknvu.html

[S05] C：字符串长度
来源：http://dali.feifeiyinyue.top/Article/details/gt2rzfwysfd.html

strlen(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2joqopoiy.html

[S06] C：字符串比较
来源：http://dali.yangfankeji.com/Article/details/gt2epddszfv.html

strcmp(a, b) == 0
来源：http://dali.cdnleiting.top/Article/details/gt2bnbbwxlu.html

[S07] C：数组遍历求和
来源：http://dali.havefunace.top/Article/details/gt2ttjnwiid.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sxryk.cn/Article/details/gt2dorvjwgq.html

[S08] C：动态内存分配与释放
来源：http://dali.havefunace.top/Article/details/gt2beoyqqex.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hnxiangtu.top/Article/details/gt2tgqyyuor.html

[S09] C：结构体定义与初始化
来源：http://dali.cdnleiting.top/Article/details/gt2qzvxfnqi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nanxuanxn.top/Article/details/gt2wsfarkjt.html

[S10] C：指针与解引用
来源：http://dali.wangshuangyany.cn/Article/details/gt2igucklll.html

int *p = &a;  *p = 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dtrztgsz.html

[S11] C：逐行读文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qbhkycps.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhongyouzk.top/Article/details/gt2rjhpdcui.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jianghu66.top/Article/details/gt2chwdfztv.html

fclose(f);
来源：http://dali.yvedp.cn/Article/details/gt2jrgcjbcx.html

[S12] C：写文件
来源：http://dali.sufxvd.cn/Article/details/gt2uoddfswq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2mceodssc.html

[S13] C：宏定义
来源：http://dali.hammf.cn/Article/details/gt2fiunzgsv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ydzc1.top/Article/details/gt2jrqglvoe.html

[S14] C：枚举
来源：http://dali.chenlongwang.top/Article/details/gt2hyxwzzaz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hnqzz.top/Article/details/gt2zhzxhewg.html

[S15] C：类型转换
来源：http://dali.fzhhl.top/Article/details/gt2qgnaayjj.html

(double) a / b
来源：http://dali.pengpengdd.cyou/Article/details/gt2jnanpudr.html

[S16] C：位操作置位
来源：http://dali.kuanghao11.cn/Article/details/gt2plaaxopr.html

x |= (1 << 3);
来源：http://dali.hnqzz.top/Article/details/gt2lbifeoag.html

[S17] C：安全拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gt2mdlorebc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sufxvd.cn/Article/details/gt2fdtalkjy.html

[S18] C：命令行参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2movfhejf.html

int main(int argc, char **argv)
来源：http://dali.yueranfly.top/Article/details/gt2kjnairxa.html

[S19] C：快速排序
来源：http://dali.hnxiangtu.top/Article/details/gt2pebnjyig.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.aizwys.cn/Article/details/gt2wxcelblg.html

[S20] C：二分查找
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xkvdzmek.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gt2qvuzpxrw.html

[S21] C：字符类别判断
来源：http://dali.jyoumei.cn/Article/details/gt2bmnbgznx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sweek.top/Article/details/gt2hrzbrkba.html

[S22] C：字符串转数字
来源：http://dali.tianlin.xyz/Article/details/gt2vufrczjd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xinyue.icu/Article/details/gt2flwwqtly.html

[S23] C：随机数
来源：http://dali.gzhubu.top/Article/details/gt2gjkacpvu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ydzc1.top/Article/details/gt2voslpnbn.html

[S24] C：获取本地时间
来源：http://dali.havefunace.top/Article/details/gt2auovanrg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ppjwa.cn/Article/details/gt2jbhwhiuj.html

[S25] C：内存拷贝
来源：http://dali.tanke756.top/Article/details/gt2ftuuvdst.html

memcpy(dst, src, n);
来源：http://dali.snrcjt.cn/Article/details/gt2pdjtxwhm.html

[S26] C：内存清零
来源：http://dali.zhoulong.xyz/Article/details/gt2luikubtz.html

memset(a, 0, sizeof a);
来源：http://dali.chenzaomai.com/Article/details/gt2mafaqylc.html

[S27] C：定义常量
来源：http://dali.svipenyu.cn/Article/details/gt2ftkrfikf.html

const double PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gt2fjncbsvf.html

[S28] C：静态变量
来源：http://dali.yueranfly.top/Article/details/gt2qrygiprq.html

static int counter = 0;
来源：http://dali.tianlin.xyz/Article/details/gt2sgiscgon.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rjshxaia.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.haohaochexian.top/Article/details/gt2mknxdoht.html

[S30] C：头文件保护
来源：http://dali.iojbl.cn/Article/details/gt2bzmplshk.html

#ifndef X_H
来源：http://dali.hnxiangtu.top/Article/details/gt2rpxzglam.html

#define X_H
来源：http://dali.pengpengdd.cyou/Article/details/gt2vcrzmlxz.html

#endif
来源：http://dali.haohaochexian.top/Article/details/gt2otbyoujd.html

[S31] C++：Hello World
来源：http://dali.iojbl.cn/Article/details/gt2aeumgwoe.html

#include <iostream>
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gxutqsez.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.fzhhl.top/Article/details/gt2mzqirmrc.html

[S32] C++：字符串
来源：http://dali.fzhhl.top/Article/details/gt2kvgnovsp.html

std::string s = "hi";  s += "!";
来源：http://dali.pengpengdd.cyou/Article/details/gt2jemkmtgx.html

[S33] C++：vector 增删
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2toqnsarr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.meibo888.top/Article/details/gt2pmwpqgxl.html

[S34] C++：遍历 vector
来源：http://dali.daria6918.cn/Article/details/gt2iordlyqh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.birdmap.top/Article/details/gt2jtlxxbnj.html

[S35] C++：map
来源：http://dali.xuanzx.com/Article/details/gt2indxoedj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sxryk.cn/Article/details/gt2ryenxwyd.html

[S36] C++：unordered_map
来源：http://dali.wangshuangyany.cn/Article/details/gt2ulrcetuk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2pmhssmjn.html

[S37] C++：set
来源：http://dali.cashguo.top/Article/details/gt2zugawnst.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tanke756.top/Article/details/gt2exdhlefm.html

[S38] C++：排序
来源：http://dali.vqdsnc.cn/Article/details/gt2zxrrorrl.html

std::sort(v.begin(), v.end());
来源：http://dali.kuanghao11.cn/Article/details/gt2qpqgajyw.html

[S39] C++：自定义比较器排序
来源：http://dali.pengpengdd.cyou/Article/details/gt2arvucfph.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenjidiqi.icu/Article/details/gt2mhcjjxzt.html

[S40] C++：查找元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hhdiiaut.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2koedywhp.html

[S41] C++：类与构造函数
来源：http://dali.gaohongyu789.top/Article/details/gt2ifqkibif.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ivvv.top/Article/details/gt2rfwumtie.html

[S42] C++：继承与虚函数
来源：http://dali.hysaishi.cn/Article/details/gt2yvxgcurv.html

class B : public Base { public: void f() override {} };
来源：http://dali.bjfxy.top/Article/details/gt2cyscxyqm.html

[S43] C++：智能指针
来源：http://dali.birdmap.top/Article/details/gt2qbkzcnwg.html

auto p = std::make_unique<int>(5);
来源：http://dali.gotoacloud.top/Article/details/gt2ftsgnyel.html

[S44] C++：引用传参
来源：http://dali.nanxinkj.top/Article/details/gt2eryczpbu.html

void inc(int &x) { ++x; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2lbkrgvyq.html

[S45] C++：lambda
来源：http://dali.yonumen.top/Article/details/gt2adslheeg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.iojbl.cn/Article/details/gt2afnymfdg.html

[S46] C++：函数模板
来源：http://dali.yj20258.top/Article/details/gt2dxllrupo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yanxiufei.cn/Article/details/gt2pjjktpzf.html

[S47] C++：结构化绑定遍历
来源：http://dali.xziqi.cn/Article/details/gt2nxeqpnei.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2rmtrmotd.html

[S48] C++：逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gt2qbejhqwu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.dashuyun.cn/Article/details/gt2fknjkmdw.html

while (std::getline(in, line)) { }
来源：http://dali.yj20258888.top/Article/details/gt2xjdvknqc.html

[S49] C++：写文件
来源：http://dali.hysaishi.cn/Article/details/gt2jbubvgch.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shangyingyoupin.top/Article/details/gt2vvyxdxjm.html

[S50] C++：格式化数字
来源：http://dali.hysaishi.cn/Article/details/gt2jjadphsb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cashguo.top/Article/details/gt2wrirllje.html

[S51] C++：显式类型转换
来源：http://dali.dashuyun.cn/Article/details/gt2hjwueapu.html

static_cast<double>(a) / b
来源：http://dali.yonumen.top/Article/details/gt2cerxcalo.html

[S52] C++：const 与 noexcept
来源：http://dali.zhoulong.xyz/Article/details/gt2qikokkkx.html

int size() const noexcept { return n_; }
来源：http://dali.cqqwz.cn/Article/details/gt2tznumajt.html

[S53] C++：移动语义
来源：http://dali.hysaishi.cn/Article/details/gt2uhihruvi.html

std::vector<int> w = std::move(v);
来源：http://dali.pengpengdd.cyou/Article/details/gt2cupaumxf.html

[S54] C++：异常处理
来源：http://dali.316326.xyz/Article/details/gt2anpwpwhm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gaohongyu789.top/Article/details/gt2phkvyaih.html

[S55] C++：结构化绑定
来源：http://dali.tianlin.xyz/Article/details/gt2gdgtndxi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gaohongyu789.top/Article/details/gt2eecuwxiy.html

[S56] C++：optional
来源：http://dali.aibaodan.cn/Article/details/gt2hdcxbtkx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hammf.cn/Article/details/gt2tcxpcymr.html

[S57] C++：编译期常量
来源：http://dali.dashuyun.cn/Article/details/gt2arisknxj.html

constexpr int N = 10;
来源：http://dali.gzhubu.top/Article/details/gt2kxehobqz.html

[S58] C++：命名空间
来源：http://dali.yongpay.top/Article/details/gt2qksubquz.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj202588.top/Article/details/gt2qqbmftty.html

[S59] C++：静态断言
来源：http://dali.sysykeji.top/Article/details/gt2ulrcjxes.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.dianchejie.cn/Article/details/gt2gynbsehs.html

[S60] C++：遍历并删除元素
来源：http://dali.svipenyu.cn/Article/details/gt2eeyqhdze.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dhnjljcw.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2nabgzbja.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.kuanghao11.cn/Article/details/gt2fkdohiuz.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2qcjfjbzn.html

[T01] Kotlin：Hello World
来源：http://dali.iojbl.cn/Article/details/gt2xuedkyox.html

println("Hello")
来源：http://dali.c1oappe.top/Article/details/gt2itayxjkc.html

[T02] Kotlin：变量
来源：http://dali.tianlin.xyz/Article/details/gt2bdxowedh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tanke756.top/Article/details/gt2mreqwvwp.html

[T03] Kotlin：字符串模板
来源：http://dali.andypj.xyz/Article/details/gt2xrblwhxt.html

"值: $b"
来源：http://dali.yanxiufei.cn/Article/details/gt2opyzzroe.html

[T04] Kotlin：空安全
来源：http://dali.yanxiufei.cn/Article/details/gt2avxfudrn.html

val n: String? = null;  n?.length
来源：http://dali.ybcxt.top/Article/details/gt2fmcylsca.html

[T05] Kotlin：when 表达式
来源：http://dali.jianghu66.top/Article/details/gt2lkjqljuc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.snrcjt.cn/Article/details/gt2zqxhhuhh.html

[T06] Kotlin：集合映射
来源：http://dali.jqgufenzy.top/Article/details/gt2vcmivnsy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2vbopqvot.html

[T07] Kotlin：集合过滤
来源：http://dali.sweek.top/Article/details/gt2pcdhyvql.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj20258.top/Article/details/gt2ceiaufdi.html

[T08] Kotlin：数据类
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dphnxpqq.html

data class User(val name: String, val age: Int)
来源：http://dali.cucudq.cn/Article/details/gt2fmxmzmbv.html

[T09] Kotlin：扩展函数
来源：http://dali.zhoulong.xyz/Article/details/gt2zmkfgxlo.html

fun String.exclaim() = this + "!"
来源：http://dali.hongshengwenyu.top/Article/details/gt2dmbqrypk.html

[T10] Kotlin：默认参数
来源：http://dali.hnqzz.top/Article/details/gt2zkoftcui.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.316326.xyz/Article/details/gt2xzdmyacp.html

[T11] Kotlin：协程
来源：http://dali.yanxiufei.cn/Article/details/gt2ixfvtrhr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hywenlv.cn/Article/details/gt2noexvfft.html

[T12] Kotlin：解构声明
来源：http://dali.cheryme.top/Article/details/gt2refuwhis.html

val (a, b) = Pair(1, 2)
来源：http://dali.gzhubu.top/Article/details/gt2pmvssoso.html

[T13] Kotlin：只读 Map
来源：http://dali.xuetiantiany.cn/Article/details/gt2fyxiuxnj.html

val m = mapOf("a" to 1)
来源：http://dali.shuidangran.top/Article/details/gt2unvhasia.html

[T14] Kotlin：循环
来源：http://dali.hywenlv.cn/Article/details/gt2qceixmqj.html

for (i in 1..10) println(i)
来源：http://dali.xuanzx.com/Article/details/gt2riwhfapn.html

[T15] Kotlin：接口
来源：http://dali.xinyue.icu/Article/details/gt2qfsstrpf.html

interface Shape { fun area(): Double }
来源：http://dali.yanxiufei.cn/Article/details/gt2iiwgdqdk.html

[T16] Swift：Hello World
来源：http://dali.gotoacloud.top/Article/details/gt2wpljnpcp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjbvzuo.html

[T17] Swift：变量与常量
来源：http://dali.birdmap.top/Article/details/gt2yryhngct.html

var a = 1;  let b = 2
来源：http://dali.daria6918.cn/Article/details/gt2bdmscgga.html

[T18] Swift：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gt2ohvdgxfd.html

"值: \(b)"
来源：http://dali.hammf.cn/Article/details/gt2lvqbclzj.html

[T19] Swift：可选绑定
来源：http://dali.redwolf501.top/Article/details/gt2bugkmwgh.html

if let n = opt { print(n) }
来源：http://dali.yuanzhike.top/Article/details/gt2rwkxcbro.html

[T20] Swift：数组操作
来源：http://dali.snrcjt.cn/Article/details/gt2gvxuwnpk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.guowangkeji.top/Article/details/gt2hsntholf.html

[T21] Swift：遍历
来源：http://dali.gaohongyu789.top/Article/details/gt2lvqhkxfx.html

for x in a { print(x) }
来源：http://dali.tanke756.top/Article/details/gt2omhbwwdj.html

[T22] Swift：字典
来源：http://dali.quarkkingdee.top/Article/details/gt2uikewijc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yuxming.cn/Article/details/gt2cyvnykoh.html

[T23] Swift：函数
来源：http://dali.yj202588.top/Article/details/gt2hfnmfgax.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.dashuyun.cn/Article/details/gt2iylavgoe.html

[T24] Swift：闭包
来源：http://dali.guowangkeji.top/Article/details/gt2fshywooh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.0kj1m.cn/Article/details/gt2bcxtmywo.html

[T25] Swift：结构体
来源：http://dali.sweek.top/Article/details/gt2qfuhwivk.html

struct P { var x: Int }
来源：http://dali.yj202588.top/Article/details/gt2aifgwesy.html

[T26] Swift：类与重写
来源：http://dali.smart0.xyz/Article/details/gt2hjnabnzg.html

class A: Base { override func f() {} }
来源：http://dali.xinyue.icu/Article/details/gt2njlgezpn.html

[T27] Swift：错误处理
来源：http://dali.316326.xyz/Article/details/gt2kejxojbk.html

do { try f() } catch { print(error) }
来源：http://dali.c1oappe.top/Article/details/gt2nafrtyjr.html

[T28] Swift：枚举
来源：http://dali.dianchejie.cn/Article/details/gt2kgfljkue.html

enum Color { case red, green }
来源：http://dali.xuetiantiany.cn/Article/details/gt2yrdwetgo.html

[T29] Swift：guard 提前返回
来源：http://dali.cashguo.top/Article/details/gt2rxrprpfi.html

guard let x = opt else { return }
来源：http://dali.yangfankeji.com/Article/details/gt2numfteqk.html

[T30] Swift：协议
来源：http://dali.tianlin.xyz/Article/details/gt2iqxbeeng.html

protocol Shape { func area() -> Double }
来源：http://dali.nanxuanxn.top/Article/details/gt2qcfrocfd.html

[T31] Lua：Hello World
来源：http://dali.nwbrower.top/Article/details/gt2qcvihrjx.html

print("Hello")
来源：http://dali.316326.xyz/Article/details/gt2kcycycou.html

[T32] Lua：局部变量
来源：http://dali.ivvv.top/Article/details/gt2euybdwzq.html

local a = 1
来源：http://dali.svipenyu.cn/Article/details/gt2aofpfrqa.html

[T33] Lua：表（数组）
来源：http://dali.redwolf501.top/Article/details/gt2kfxkafnh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yuxming.cn/Article/details/gt2ysyffhpm.html

[T34] Lua：遍历表
来源：http://dali.xuetiantiany.cn/Article/details/gt2jjzxsqvs.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.smart0.xyz/Article/details/gt2sxxvevwb.html

[T35] Lua：字典表
来源：http://dali.meibo888.top/Article/details/gt2vbocipac.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yuanzhike.top/Article/details/gt2wndqnwbd.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cajfjqtt.html

function add(a, b) return a + b end
来源：http://dali.fengsongda.top/Article/details/gt2rijqlpui.html

[T37] Lua：字符串拼接
来源：http://dali.pycfn.com/Article/details/gt2criwzrhp.html

"a" .. "b"
来源：http://dali.sufxvd.cn/Article/details/gt2opjycdtq.html

[T38] Lua：条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rpjivcwa.html

if x > 0 then print("正") end
来源：http://dali.fengsongda.top/Article/details/gt2kgosrjtd.html

[T39] Lua：模式匹配
来源：http://dali.daxiang520.top/Article/details/gt2zuvbalrf.html

string.find(s, "%d+")
来源：http://dali.andypj.xyz/Article/details/gt2fazphhyd.html

[T40] Lua：元表
来源：http://dali.quarkkingdee.top/Article/details/gt2bwkubcvk.html

setmetatable({}, { __index = base })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yfbflbjl.html

[T41] Perl：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mzbpnnap.html

print "Hello\n";
来源：http://dali.xziqi.cn/Article/details/gt2zbcxwjra.html

[T42] Perl：变量类型
来源：http://dali.tian-w.cn/Article/details/gt2spmoorfm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zdqjudy.top/Article/details/gt2hdbwxvxc.html

[T43] Perl：字符串插值
来源：http://dali.cucudq.cn/Article/details/gt2uefndiob.html

"值: $a"
来源：http://dali.c1oappe.top/Article/details/gt2slfswxze.html

[T44] Perl：条件
来源：http://dali.iojbl.cn/Article/details/gt2jpnolfff.html

if ($a > 0) { print "正"; }
来源：http://dali.havefunace.top/Article/details/gt2joeaioai.html

[T45] Perl：数组遍历
来源：http://dali.dashuyun.cn/Article/details/gt2faksjvas.html

for my $x (@arr) { print $x; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2xfxpkkbu.html

[T46] Perl：哈希操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uzvpwcpj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xinyue.icu/Article/details/gt2qkvumsag.html

[T47] Perl：正则捕获
来源：http://dali.svipenyu.cn/Article/details/gt2gvvlhawt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mrimenuo.html

[T48] Perl：正则替换
来源：http://dali.bjfxy.top/Article/details/gt2vjjtzdbk.html

$s =~ s/old/new/g;
来源：http://dali.zdqjudy.top/Article/details/gt2kxrovrgm.html

[T49] Perl：函数
来源：http://dali.xylfe.cn/Article/details/gt2iispnzfh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gt2ylbnprdf.html

[T50] Perl：逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gt2ackyvpub.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wllywjmm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sxryk.cn/Article/details/gt2ilcqicru.html

[T51] Scala：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gt2cdydubvh.html

println("Hello")
来源：http://dali.chenzaomai.com/Article/details/gt2cfdvnbbs.html

[T52] Scala：变量
来源：http://dali.jinqigufen.top/Article/details/gt2bighjqfq.html

val a = 1;  var b = 2
来源：http://dali.gogol.net.cn/Article/details/gt2yvmzdbgv.html

[T53] Scala：字符串插值
来源：http://dali.pycfn.com/Article/details/gt2avhnkhuv.html

s"值: $b"
来源：http://dali.dianchejie.cn/Article/details/gt2gatzlnmp.html

[T54] Scala：集合映射
来源：http://dali.snrcjt.cn/Article/details/gt2rtsuazue.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yuanzhike.top/Article/details/gt2ghxrkvgf.html

[T55] Scala：集合过滤
来源：http://dali.hfpthk.cn/Article/details/gt2lgvimyef.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hywenlv.cn/Article/details/gt2ksukejul.html

[T56] Scala：样例类
来源：http://dali.guannengcc.top/Article/details/gt2owgqjkxk.html

case class User(name: String, age: Int)
来源：http://dali.snrcjt.cn/Article/details/gt2srsvorxe.html

[T57] Scala：模式匹配
来源：http://dali.gogol.net.cn/Article/details/gt2qczqmhsg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.svipenyu.cn/Article/details/gt2gcxtsvcs.html

[T58] Scala：函数定义
来源：http://dali.aibaodan.cn/Article/details/gt2zraozyqo.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.snrcjt.cn/Article/details/gt2yxcuygil.html

[T59] Scala：循环
来源：http://dali.iojbl.cn/Article/details/gt2zqdepqiu.html

for (i <- 1 to 10) println(i)
来源：http://dali.jlsjyb.cn/Article/details/gt2hvmkwogz.html

[T60] Scala：折叠
来源：http://dali.gotoacloud.top/Article/details/gt2ztdmbbhi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yj20258888.top/Article/details/gt2ubfithfp.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2kfuyuhhp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hywenlv.cn/Article/details/gt2qiqcfdua.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2wzrahivt.html

[U01] Py：创建虚拟环境
来源：http://dali.cucudq.cn/Article/details/gt2zsxkpklv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.chenzaomai.com/Article/details/gt2fkhjczmx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.daria6918.cn/Article/details/gt2bklkgqtg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yuanzhike.top/Article/details/gt2kzykhkil.html

[U03] Py：加载 .env 配置
来源：http://dali.hywenlv.cn/Article/details/gt2rpqkknuf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ydzc1.top/Article/details/gt2cegahzon.html

[U04] Py：变量调试打印
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qanqpshx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yangfankeji.com/Article/details/gt2ecmilwxe.html

[U05] Py：列表去重且保序
来源：http://dali.yonumen.top/Article/details/gt2winxghrv.html

list(dict.fromkeys(arr))
来源：http://dali.snrcjt.cn/Article/details/gt2mlllsduu.html

[U06] Py：合并两个字典
来源：http://dali.gogol.net.cn/Article/details/gt2ohamymvq.html

{**a, **b}
来源：http://dali.kuanghao11.cn/Article/details/gt2bompzmkq.html

[U07] Py：反转字典键值
来源：http://dali.pycfn.com/Article/details/gt2hijexxty.html

{v: k for k, v in d.items()}
来源：http://dali.jqgufenzy.top/Article/details/gt2aececcmy.html

[U08] Py：展平二维列表
来源：http://dali.dashuyun.cn/Article/details/gt2mzkiwqie.html

[y for x in nested for y in x]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fsoljujo.html


<!-- 参考信息 -->