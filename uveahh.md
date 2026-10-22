代发 wailian999

df -h;  du -sh *
来源：http://dali.aibaodan.cn/Article/details/gtbutsimvx.html

[R62] 找最占空间的文件
来源：http://dali.zhongyouzk.top/Article/details/gtenhlqtan.html

du -ah . | sort -rh | head -10
来源：http://dali.mhx1999.top/Article/details/gtmohurdrb.html

[R63] 内存与进程
来源：http://dali.cucudq.cn/Article/details/gtmwkatbwv.html

free -h;  ps aux | grep nginx
来源：http://dali.hammf.cn/Article/details/gttiogvsba.html

[R64] 结束进程
来源：http://dali.zhiwuduotai.top/Article/details/gtpuduydhn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jqgufenzy.top/Article/details/gtwyxckurp.html

[R65] 查看端口占用
来源：http://dali.aibaodan.cn/Article/details/gtmklonqte.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yueranfly.top/Article/details/gtyqyhsohu.html

[R66] 定时任务
来源：http://dali.jinqigfzy.top/Article/details/gthksyuipm.html

crontab -e;  crontab -l
来源：http://dali.gogol.net.cn/Article/details/gtqimxefwd.html

[R67] 生成随机十六进制串
来源：http://dali.zhoulong.xyz/Article/details/gtorpfldkm.html

openssl rand -hex 16
来源：http://dali.kuanghao11.cn/Article/details/gtpadixgxc.html

[R68] 计算文件校验值
来源：http://dali.chenzaomai.com/Article/details/gtahmxcztm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hywenlv.cn/Article/details/gtxjbubhad.html

[R69] 生成随机密码
来源：http://dali.cucudq.cn/Article/details/gtpjixjtmy.html

head -c 16 /dev/urandom | base64
来源：http://dali.smart0.xyz/Article/details/gtkzfhsjor.html

[R70] 时间戳与互转
来源：http://dali.yvedp.cn/Article/details/gtyynyugxs.html

date +%s;  date -d @1700000000
来源：http://dali.mhx1999.top/Article/details/gtasrrockr.html

[R71] 日期格式化
来源：http://dali.xziqi.cn/Article/details/gtcqxffkkj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.dianchejie.cn/Article/details/gtvjecidbz.html

[R72] 等待端口就绪
来源：http://dali.0kj1m.cn/Article/details/gtxhufetrt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yuanzhike.top/Article/details/gtebedkwzy.html

[R73] 分割大日志
来源：http://dali.c1oappe.top/Article/details/gtnmhnvubv.html

split -l 1000 big.log part_
来源：http://dali.yj202588.top/Article/details/gtrlibrqiy.html

[R74] 批量重命名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtivtytqgt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cqqwz.cn/Article/details/gtbypqemcb.html

[R75] 导出环境变量
来源：http://dali.xinyue.icu/Article/details/gtrrktjfdo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.c1oappe.top/Article/details/gtlcdeehbt.html

[R76] 使用临时文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbwzlubw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.andypj.xyz/Article/details/gtjqxqathz.html

[R77] 读取用户输入
来源：http://dali.jyoumei.cn/Article/details/gtcvjxbbbk.html

read -rp "请输入: " ans
来源：http://dali.yj20258.top/Article/details/gthffllnvn.html

[R78] 交互式菜单
来源：http://dali.yuxming.cn/Article/details/gthbtrzxhs.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ehwqpu.com/Article/details/gtyupnmxon.html

[R79] 解析命令行选项
来源：http://dali.xziqi.cn/Article/details/gtveatilkq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shuidangran.top/Article/details/gtsyyfdbdz.html

[R80] 查看脚本执行耗时
来源：http://dali.guannengcc.top/Article/details/gtcclwngsh.html

time ./run.sh
来源：http://dali.havefunace.top/Article/details/gtzpbpmovs.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtjcshyzjb.html

S. C / C++ 专题
来源：http://dali.bjfxy.top/Article/details/gtuzuotmds.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gthutylbnu.html

[S01] C：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtoodpchqk.html

#include <stdio.h>
来源：http://dali.zycfv.cn/Article/details/gtkdxvqqem.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sysykeji.top/Article/details/gtdcklbamt.html

[S02] C：变量与格式化输出
来源：http://dali.smart0.xyz/Article/details/gtuzulwzuu.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenjidiqi.icu/Article/details/gtkxbpqmwm.html

[S03] C：读入整数
来源：http://dali.gzhubu.top/Article/details/gtwmrtlgrt.html

int x; scanf("%d", &x);
来源：http://dali.chenlongwang.top/Article/details/gtgsadjqmq.html

[S04] C：字符串复制
来源：http://dali.shuidangran.top/Article/details/gtbgfvamax.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.smart0.xyz/Article/details/gtqfodwate.html

[S05] C：字符串长度
来源：http://dali.zhoulong.xyz/Article/details/gtxslhqjkp.html

strlen(s)
来源：http://dali.zycfv.cn/Article/details/gtilfrbrun.html

[S06] C：字符串比较
来源：http://dali.ydzc1.top/Article/details/gtsbqcjenx.html

strcmp(a, b) == 0
来源：http://dali.sweek.top/Article/details/gtnjvplsjv.html

[S07] C：数组遍历求和
来源：http://dali.dashuyun.cn/Article/details/gticzlpacd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gtghrnqtgk.html

[S08] C：动态内存分配与释放
来源：http://dali.yangfankeji.com/Article/details/gtaugjolsr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ydzc1.top/Article/details/gtbmtdbwei.html

[S09] C：结构体定义与初始化
来源：http://dali.zhixingplan.top/Article/details/gtaeeukbsm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.daxiang520.top/Article/details/gtzadkvnaa.html

[S10] C：指针与解引用
来源：http://dali.ivvv.top/Article/details/gtepqwkevd.html

int *p = &a;  *p = 5;
来源：http://dali.smart0.xyz/Article/details/gtpfoazhee.html

[S11] C：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gtphmkhpkt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nanxinkj.top/Article/details/gtqslpgjkl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.dashuyun.cn/Article/details/gtemygpkta.html

fclose(f);
来源：http://dali.jqgfzy.top/Article/details/gtfcahtlkh.html

[S12] C：写文件
来源：http://dali.jinqigufen.top/Article/details/gtfwzvsmco.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.dianchejie.cn/Article/details/gtfiislyhh.html

[S13] C：宏定义
来源：http://dali.gaohongyu789.top/Article/details/gtipzofarr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.pengpengdd.cyou/Article/details/gtsfafgaoa.html

[S14] C：枚举
来源：http://dali.andypj.xyz/Article/details/gtjshfobzf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jianghu66.top/Article/details/gtdiaeraqt.html

[S15] C：类型转换
来源：http://dali.9152youxi.cn/Article/details/gtjjdatzos.html

(double) a / b
来源：http://dali.zhiwuduotai.top/Article/details/gtielvxlkr.html

[S16] C：位操作置位
来源：http://dali.tanke756.top/Article/details/gtlgvdazfu.html

x |= (1 << 3);
来源：http://dali.ydzc1.top/Article/details/gtuoiafbtf.html

[S17] C：安全拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gtdvzrqoof.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yangfankeji.com/Article/details/gtbqcpsgjk.html

[S18] C：命令行参数
来源：http://dali.9152youxi.cn/Article/details/gtyldmmnxh.html

int main(int argc, char **argv)
来源：http://dali.jinqigufen.top/Article/details/gtwlvwcgle.html

[S19] C：快速排序
来源：http://dali.haohaochexian.top/Article/details/gthwstllgt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gtzcwoqzsa.html

[S20] C：二分查找
来源：http://dali.xuetiantiany.cn/Article/details/gtcdylxycf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhixingplan.top/Article/details/gtwuekdoqy.html

[S21] C：字符类别判断
来源：http://dali.gzhubu.top/Article/details/gtlywuvzks.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.9152youxi.cn/Article/details/gtpibwhjcf.html

[S22] C：字符串转数字
来源：http://dali.hammf.cn/Article/details/gtgymidaxm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sxryk.cn/Article/details/gtdxbbfkka.html

[S23] C：随机数
来源：http://dali.chenzaomai.com/Article/details/gtnegudrte.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.feifeiyinyue.top/Article/details/gtoewldxvz.html

[S24] C：获取本地时间
来源：http://dali.pengpengdd.cyou/Article/details/gtmvxowbgz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shuidangran.top/Article/details/gthernxeyc.html

[S25] C：内存拷贝
来源：http://dali.tian-w.cn/Article/details/gtnbkmkrif.html

memcpy(dst, src, n);
来源：http://dali.nanxuanxn.top/Article/details/gthnxuwehu.html

[S26] C：内存清零
来源：http://dali.redwolf501.top/Article/details/gtkndboqdc.html

memset(a, 0, sizeof a);
来源：http://dali.yuxming.cn/Article/details/gtsnaoxvwf.html

[S27] C：定义常量
来源：http://dali.yuanzhike.top/Article/details/gtasjpisyx.html

const double PI = 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gtvnejnvvf.html

[S28] C：静态变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzxedfgyr.html

static int counter = 0;
来源：http://dali.zhixingplan.top/Article/details/gtueblgvcf.html

[S29] C：变参函数
来源：http://dali.yangfankeji.com/Article/details/gtmefaazsv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tanke756.top/Article/details/gtnlwkvide.html

[S30] C：头文件保护
来源：http://dali.andypj.xyz/Article/details/gttmauixqz.html

#ifndef X_H
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdlqjdmtt.html

#define X_H
来源：http://dali.svipenyu.cn/Article/details/gtaadoevgl.html

#endif
来源：http://dali.chenlongwang.top/Article/details/gtnkcbjwjd.html

[S31] C++：Hello World
来源：http://dali.fzhhl.top/Article/details/gtyevvafgc.html

#include <iostream>
来源：http://dali.hnqzz.top/Article/details/gtijrityhv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gzhubu.top/Article/details/gtchamqkne.html

[S32] C++：字符串
来源：http://dali.c1oappe.top/Article/details/gtlqdhoqxi.html

std::string s = "hi";  s += "!";
来源：http://dali.meibo888.top/Article/details/gtrtztbltt.html

[S33] C++：vector 增删
来源：http://dali.feifeiyinyue.top/Article/details/gtqfzpaezp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfnpsexbv.html

[S34] C++：遍历 vector
来源：http://dali.cdnleiting.top/Article/details/gtyywcqvjm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.daria6918.cn/Article/details/gtacqvfqzb.html

[S35] C++：map
来源：http://dali.kuanghao11.cn/Article/details/gtcsabrpgb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gtbbuutnjc.html

[S36] C++：unordered_map
来源：http://dali.jlsjyb.cn/Article/details/gtriwriuih.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gtensbocqa.html

[S37] C++：set
来源：http://dali.zhixingplan.top/Article/details/gtnnrylgtm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.smart0.xyz/Article/details/gtelamzryd.html

[S38] C++：排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpichudqm.html

std::sort(v.begin(), v.end());
来源：http://dali.feifeiyinyue.top/Article/details/gtywwnyhtq.html

[S39] C++：自定义比较器排序
来源：http://dali.nwbrower.top/Article/details/gtoouaabou.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj202588.top/Article/details/gtfszsduhb.html

[S40] C++：查找元素
来源：http://dali.cheryme.top/Article/details/gtamcbzxej.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zdqjudy.top/Article/details/gtskjxaakw.html

[S41] C++：类与构造函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaseymozt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cucudq.cn/Article/details/gtvilyhqyo.html

[S42] C++：继承与虚函数
来源：http://dali.jyoumei.cn/Article/details/gtmtacyzeu.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtatoletub.html

[S43] C++：智能指针
来源：http://dali.shzxlz.cn/Article/details/gtbyqwmtjq.html

auto p = std::make_unique<int>(5);
来源：http://dali.tanke756.top/Article/details/gtpyovdfrc.html

[S44] C++：引用传参
来源：http://dali.shanyushiyangtech.top/Article/details/gtvcybiull.html

void inc(int &x) { ++x; }
来源：http://dali.yueranfly.top/Article/details/gtorxikxoj.html

[S45] C++：lambda
来源：http://dali.xuetiantiany.cn/Article/details/gtfpsbqfuh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xuanzx.com/Article/details/gtqnnrqgfq.html

[S46] C++：函数模板
来源：http://dali.yvedp.cn/Article/details/gtccaevsav.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cheryme.top/Article/details/gtyvselqqj.html

[S47] C++：结构化绑定遍历
来源：http://dali.fzhhl.top/Article/details/gtomuvmqkz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yvedp.cn/Article/details/gtdjitsrve.html

[S48] C++：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gtvwbfklae.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cdnleiting.top/Article/details/gteogxvaou.html

while (std::getline(in, line)) { }
来源：http://dali.cdnleiting.top/Article/details/gtglppluqx.html

[S49] C++：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwdzkdmjo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yongpay.top/Article/details/gtmgvnnosf.html

[S50] C++：格式化数字
来源：http://dali.sxryk.cn/Article/details/gtepewxvvy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gtxgxqdziz.html

[S51] C++：显式类型转换
来源：http://dali.ehwqpu.com/Article/details/gtemmexexp.html

static_cast<double>(a) / b
来源：http://dali.hammf.cn/Article/details/gtgyxdrlgh.html

[S52] C++：const 与 noexcept
来源：http://dali.shzxlz.cn/Article/details/gtzbakvlwl.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gthtaoadbw.html

[S53] C++：移动语义
来源：http://dali.yj20258.top/Article/details/gtsjyvlasl.html

std::vector<int> w = std::move(v);
来源：http://dali.ivvv.top/Article/details/gtwysurddl.html

[S54] C++：异常处理
来源：http://dali.hongshengwenyu.top/Article/details/gthldzpucc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhoulong.xyz/Article/details/gtdbkeaekz.html

[S55] C++：结构化绑定
来源：http://dali.svipenyu.cn/Article/details/gtmfjbgypp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.smart0.xyz/Article/details/gtjmnnpubj.html

[S56] C++：optional
来源：http://dali.jinqigfzy.top/Article/details/gtnigakruj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhongyouzk.top/Article/details/gtpqybspfh.html

[S57] C++：编译期常量
来源：http://dali.tanke756.top/Article/details/gtcftpsaaf.html

constexpr int N = 10;
来源：http://dali.cqqwz.cn/Article/details/gtdtmjabmv.html

[S58] C++：命名空间
来源：http://dali.xinyue.icu/Article/details/gtxbztyaqm.html

namespace ns { int f() { return 1; } }
来源：http://dali.yueranfly.top/Article/details/gtgtenhhuc.html

[S59] C++：静态断言
来源：http://dali.ivvv.top/Article/details/gtnvhvucqb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.nanxinkj.top/Article/details/gtphjuwgrv.html

[S60] C++：遍历并删除元素
来源：http://dali.shzxlz.cn/Article/details/gtipciifux.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jqgfzy.top/Article/details/gtulayaqok.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtvlwhldwx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yonumen.top/Article/details/gtuticjpvp.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtsmkqhdnm.html

[T01] Kotlin：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtdgeifkxe.html

println("Hello")
来源：http://dali.aizwys.cn/Article/details/gtqyhoanub.html

[T02] Kotlin：变量
来源：http://dali.ydzc1.top/Article/details/gtvmlybcpz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shuidangran.top/Article/details/gtpzflsbge.html

[T03] Kotlin：字符串模板
来源：http://dali.yueranfly.top/Article/details/gtjawmyaod.html

"值: $b"
来源：http://dali.daxiang520.top/Article/details/gthgokwpns.html

[T04] Kotlin：空安全
来源：http://dali.pengpengdd.cyou/Article/details/gtqgqbzrnm.html

val n: String? = null;  n?.length
来源：http://dali.ybcxt.top/Article/details/gthhxnette.html

[T05] Kotlin：when 表达式
来源：http://dali.yonumen.top/Article/details/gtxlmhclbx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.vqdsnc.cn/Article/details/gtbmvhwudu.html

[T06] Kotlin：集合映射
来源：http://dali.cdnleiting.top/Article/details/gtkpyksvzp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.316326.xyz/Article/details/gtoebpbwsl.html

[T07] Kotlin：集合过滤
来源：http://dali.gzhubu.top/Article/details/gtrebvlgme.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuxming.cn/Article/details/gthrhbnxub.html

[T08] Kotlin：数据类
来源：http://dali.wangdashe.top/Article/details/gtcgsrmesc.html

data class User(val name: String, val age: Int)
来源：http://dali.smart0.xyz/Article/details/gtdvgrccmm.html

[T09] Kotlin：扩展函数
来源：http://dali.gogol.net.cn/Article/details/gtvdzpzwji.html

fun String.exclaim() = this + "!"
来源：http://dali.gotoacloud.top/Article/details/gtadkmgvxh.html

[T10] Kotlin：默认参数
来源：http://dali.zhoulong.xyz/Article/details/gtnrqpgwhp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hnqzz.top/Article/details/gtfmtvkscy.html

[T11] Kotlin：协程
来源：http://dali.tianlin.xyz/Article/details/gtxgcqwljv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ehwqpu.com/Article/details/gtsnhxbulb.html

[T12] Kotlin：解构声明
来源：http://dali.nwbrower.top/Article/details/gtlvmbrjiv.html

val (a, b) = Pair(1, 2)
来源：http://dali.shuidangran.top/Article/details/gtzsjmwfdq.html

[T13] Kotlin：只读 Map
来源：http://dali.hammf.cn/Article/details/gtypttqgap.html

val m = mapOf("a" to 1)
来源：http://dali.redwolf501.top/Article/details/gtkyynohof.html

[T14] Kotlin：循环
来源：http://dali.cqqwz.cn/Article/details/gtfvndkval.html

for (i in 1..10) println(i)
来源：http://dali.xuanzx.com/Article/details/gtqjokjzhb.html

[T15] Kotlin：接口
来源：http://dali.daxiang520.top/Article/details/gtlqccwxto.html

interface Shape { fun area(): Double }
来源：http://dali.zhongyouzk.top/Article/details/gtpmkxyvcu.html

[T16] Swift：Hello World
来源：http://dali.jianghu66.top/Article/details/gtdgvqwijg.html

print("Hello")
来源：http://dali.cheryme.top/Article/details/gtxhrkfhak.html

[T17] Swift：变量与常量
来源：http://dali.bjfxy.top/Article/details/gtfkynbxgv.html

var a = 1;  let b = 2
来源：http://dali.nanxinkj.top/Article/details/gtumygnohq.html

[T18] Swift：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gteciuxrlm.html

"值: \(b)"
来源：http://dali.hammf.cn/Article/details/gtycuoozdj.html

[T19] Swift：可选绑定
来源：http://dali.nwbrower.top/Article/details/gtvvhxwtdc.html

if let n = opt { print(n) }
来源：http://dali.yueranfly.top/Article/details/gtwnscpptz.html

[T20] Swift：数组操作
来源：http://dali.nwbrower.top/Article/details/gtjqffzoar.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhoulong.xyz/Article/details/gtdjkoyjcm.html

[T21] Swift：遍历
来源：http://dali.mhx1999.top/Article/details/gtukspxdoy.html

for x in a { print(x) }
来源：http://dali.cucudq.cn/Article/details/gtykgclzer.html

[T22] Swift：字典
来源：http://dali.wangdashe.top/Article/details/gtafwluueb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.0kj1m.cn/Article/details/gtjzwcgkpj.html

[T23] Swift：函数
来源：http://dali.hammf.cn/Article/details/gtcjlyjoce.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.guannengcc.top/Article/details/gtifoogjkg.html

[T24] Swift：闭包
来源：http://dali.gogol.net.cn/Article/details/gtrzpbytdk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xinyue.icu/Article/details/gtzfvvcqrm.html

[T25] Swift：结构体
来源：http://dali.guannengcc.top/Article/details/gtbzccqusb.html

struct P { var x: Int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfsxchwxk.html

[T26] Swift：类与重写
来源：http://dali.fzhhl.top/Article/details/gtomqouili.html

class A: Base { override func f() {} }
来源：http://dali.chenlongwang.top/Article/details/gtzixtkxiw.html

[T27] Swift：错误处理
来源：http://dali.daria6918.cn/Article/details/gtrjoswlik.html

do { try f() } catch { print(error) }
来源：http://dali.gogol.net.cn/Article/details/gtoayazkkj.html

[T28] Swift：枚举
来源：http://dali.0kj1m.cn/Article/details/gtrtpqrilm.html

enum Color { case red, green }
来源：http://dali.sweek.top/Article/details/gtzpzwwoai.html

[T29] Swift：guard 提前返回
来源：http://dali.yj202588.top/Article/details/gtpfdellev.html

guard let x = opt else { return }
来源：http://dali.jlsjyb.cn/Article/details/gtlvqpnpap.html

[T30] Swift：协议
来源：http://dali.zhixingplan.top/Article/details/gtxjspfasz.html

protocol Shape { func area() -> Double }
来源：http://dali.feifeiyinyue.top/Article/details/gtjcilcsfn.html

[T31] Lua：Hello World
来源：http://dali.yueranfly.top/Article/details/gtscmciipu.html

print("Hello")
来源：http://dali.cdnleiting.top/Article/details/gtcgbeuwiu.html

[T32] Lua：局部变量
来源：http://dali.gotoacloud.top/Article/details/gtngzhllsr.html

local a = 1
来源：http://dali.yongpay.top/Article/details/gtiadjpqps.html

[T33] Lua：表（数组）
来源：http://dali.zhoulong.xyz/Article/details/gtmtmjgiyu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xylfe.cn/Article/details/gthctuxnki.html

[T34] Lua：遍历表
来源：http://dali.zycfv.cn/Article/details/gtwkybuupy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shanyushiyangtech.top/Article/details/gtzrenkoqq.html

[T35] Lua：字典表
来源：http://dali.zhongyouzk.top/Article/details/gtlgopoaay.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gtujlxvxlh.html

[T36] Lua：函数
来源：http://dali.gogol.net.cn/Article/details/gtpqjrnwkm.html

function add(a, b) return a + b end
来源：http://dali.hammf.cn/Article/details/gtwhjhneeh.html

[T37] Lua：字符串拼接
来源：http://dali.aibaodan.cn/Article/details/gteygntfpz.html

"a" .. "b"
来源：http://dali.shuidangran.top/Article/details/gttruvcion.html

[T38] Lua：条件
来源：http://dali.shzxlz.cn/Article/details/gtchnmiwfj.html

if x > 0 then print("正") end
来源：http://dali.yj20258888.top/Article/details/gtfutbnppa.html

[T39] Lua：模式匹配
来源：http://dali.ydzc1.top/Article/details/gtonqbjrde.html

string.find(s, "%d+")
来源：http://dali.hywenlv.cn/Article/details/gtafdxwcxv.html

[T40] Lua：元表
来源：http://dali.kuanghao11.cn/Article/details/gtewwryidl.html

setmetatable({}, { __index = base })
来源：http://dali.yongpay.top/Article/details/gtljqpxluj.html

[T41] Perl：Hello World
来源：http://dali.andypj.xyz/Article/details/gtidwifdjo.html

print "Hello\n";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtexyraxzb.html

[T42] Perl：变量类型
来源：http://dali.yongpay.top/Article/details/gthoqptnyl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.birdmap.top/Article/details/gtbkqqymxq.html

[T43] Perl：字符串插值
来源：http://dali.jqgfzy.top/Article/details/gthwqwdetu.html

"值: $a"
来源：http://dali.havefunace.top/Article/details/gtvihaopka.html

[T44] Perl：条件
来源：http://dali.cucudq.cn/Article/details/gtywvwmojy.html

if ($a > 0) { print "正"; }
来源：http://dali.xinyue.icu/Article/details/gtladtjzqy.html

[T45] Perl：数组遍历
来源：http://dali.tianlin.xyz/Article/details/gtgbifperz.html

for my $x (@arr) { print $x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gthpnezhxv.html

[T46] Perl：哈希操作
来源：http://dali.feifeiyinyue.top/Article/details/gtzlsnmjik.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yj202588.top/Article/details/gtzigfbszp.html

[T47] Perl：正则捕获
来源：http://dali.gotoacloud.top/Article/details/gtzokprlaw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hnqzz.top/Article/details/gtxblshgrg.html

[T48] Perl：正则替换
来源：http://dali.yonumen.top/Article/details/gtdinamviv.html

$s =~ s/old/new/g;
来源：http://dali.zhengqikj.top/Article/details/gtuehdynbz.html

[T49] Perl：函数
来源：http://dali.chenlongwang.top/Article/details/gtaopsnmdh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gtnexkkyxa.html

[T50] Perl：逐行读文件
来源：http://dali.tanke756.top/Article/details/gtrvduurll.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.c1oappe.top/Article/details/gtkrtjtpsx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.fzhhl.top/Article/details/gtnhbzfbtr.html

[T51] Scala：Hello World
来源：http://dali.ivvv.top/Article/details/gtdqlylofu.html

println("Hello")
来源：http://dali.dashuyun.cn/Article/details/gtwgolfwxs.html

[T52] Scala：变量
来源：http://dali.dianchejie.cn/Article/details/gtcqpupioh.html

val a = 1;  var b = 2
来源：http://dali.hnqzz.top/Article/details/gtydmmbdkv.html

[T53] Scala：字符串插值
来源：http://dali.andypj.xyz/Article/details/gthvqdyqqg.html

s"值: $b"
来源：http://dali.redwolf501.top/Article/details/gtxhmhbowt.html

[T54] Scala：集合映射
来源：http://dali.gzhubu.top/Article/details/gtjqwdptrf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gaohongyu789.top/Article/details/gtawqtidci.html

[T55] Scala：集合过滤
来源：http://dali.andypj.xyz/Article/details/gtyiapjsjq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jqgufenzy.top/Article/details/gtbqcxsfhf.html

[T56] Scala：样例类
来源：http://dali.nanxinkj.top/Article/details/gtqnyckllp.html

case class User(name: String, age: Int)
来源：http://dali.sufxvd.cn/Article/details/gtdbvkoiry.html

[T57] Scala：模式匹配
来源：http://dali.dianchejie.cn/Article/details/gtkdnkbqyh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yongpay.top/Article/details/gtdbhfpxns.html

[T58] Scala：函数定义
来源：http://dali.haohaochexian.top/Article/details/gttztwmdnu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.kuanghao11.cn/Article/details/gtbxxsupxd.html

[T59] Scala：循环
来源：http://dali.jyoumei.cn/Article/details/gthzykqued.html

for (i <- 1 to 10) println(i)
来源：http://dali.316326.xyz/Article/details/gtcmpcloaj.html

[T60] Scala：折叠
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqnppldyl.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yongpay.top/Article/details/gtaptlofef.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtirplngll.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yuxming.cn/Article/details/gtwlssgzql.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtbylbfsih.html

[U01] Py：创建虚拟环境
来源：http://dali.ybcxt.top/Article/details/gtrmirnrqn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.gzhubu.top/Article/details/gtgpdiemcv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hammf.cn/Article/details/gttkquokze.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ivvv.top/Article/details/gtqmjidkpa.html


<!-- 参考信息 -->