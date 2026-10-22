代发 wailian999

df -h;  du -sh *
来源：http://dali.sweek.top/Article/details/gtlrcochwv.html

[R62] 找最占空间的文件
来源：http://dali.redwolf501.top/Article/details/gthjmgtomk.html

du -ah . | sort -rh | head -10
来源：http://dali.redwolf501.top/Article/details/gtsgcgcrnt.html

[R63] 内存与进程
来源：http://dali.jyoumei.cn/Article/details/gtifahmphy.html

free -h;  ps aux | grep nginx
来源：http://dali.iojbl.cn/Article/details/gtdhdudhyj.html

[R64] 结束进程
来源：http://dali.zycfv.cn/Article/details/gtefrnqyyk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpseeehex.html

[R65] 查看端口占用
来源：http://dali.zhoulong.xyz/Article/details/gtnbckcmvu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.nanxuanxn.top/Article/details/gtbjakbpks.html

[R66] 定时任务
来源：http://dali.cheryme.top/Article/details/gtswciylxy.html

crontab -e;  crontab -l
来源：http://dali.daxiang520.top/Article/details/gtsqaxudnh.html

[R67] 生成随机十六进制串
来源：http://dali.hysaishi.cn/Article/details/gtcypibawa.html

openssl rand -hex 16
来源：http://dali.ppjwa.cn/Article/details/gtbqebkitv.html

[R68] 计算文件校验值
来源：http://dali.ydzc1.top/Article/details/gtocjzucke.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.daxiang520.top/Article/details/gtseiyaqsi.html

[R69] 生成随机密码
来源：http://dali.hfpthk.cn/Article/details/gtrrahbzcy.html

head -c 16 /dev/urandom | base64
来源：http://dali.fengsongda.top/Article/details/gtvegujdsp.html

[R70] 时间戳与互转
来源：http://dali.cqqwz.cn/Article/details/gtxvkqoloj.html

date +%s;  date -d @1700000000
来源：http://dali.zhiwuduotai.top/Article/details/gtlokavrhi.html

[R71] 日期格式化
来源：http://dali.chenzaomai.com/Article/details/gtkvyssmjc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.redwolf501.top/Article/details/gtltoilbrw.html

[R72] 等待端口就绪
来源：http://dali.jyoumei.cn/Article/details/gtqctrhkrt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.birdmap.top/Article/details/gtfokdtluk.html

[R73] 分割大日志
来源：http://dali.pengpengdd.cyou/Article/details/gtnvskgoil.html

split -l 1000 big.log part_
来源：http://dali.cheryme.top/Article/details/gtxufopsfw.html

[R74] 批量重命名
来源：http://dali.gogol.net.cn/Article/details/gtyxszawjc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hfpthk.cn/Article/details/gtojujnhfj.html

[R75] 导出环境变量
来源：http://dali.zhiwuduotai.top/Article/details/gtfyubpvwi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jlsjyb.cn/Article/details/gtorezygdd.html

[R76] 使用临时文件
来源：http://dali.yj20258888.top/Article/details/gtifporgte.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cheryme.top/Article/details/gtozythejk.html

[R77] 读取用户输入
来源：http://dali.c1oappe.top/Article/details/gtmimnyvdo.html

read -rp "请输入: " ans
来源：http://dali.pycfn.com/Article/details/gtkwhtfjmy.html

[R78] 交互式菜单
来源：http://dali.sysykeji.top/Article/details/gtipwtucsn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.mhx1999.top/Article/details/gtuzwevopp.html

[R79] 解析命令行选项
来源：http://dali.zhoulong.xyz/Article/details/gtaccxuiqk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwektcodf.html

[R80] 查看脚本执行耗时
来源：http://dali.kuanghao11.cn/Article/details/gtgxtbzcja.html

time ./run.sh
来源：http://dali.guowangkeji.top/Article/details/gtyiytyhtl.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtwiuwkwak.html

S. C / C++ 专题
来源：http://dali.yvedp.cn/Article/details/gtzkedlcpw.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtuqvgsord.html

[S01] C：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtcxgzcisb.html

#include <stdio.h>
来源：http://dali.iojbl.cn/Article/details/gtptjhfbxp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ybcxt.top/Article/details/gtxrqmgqyi.html

[S02] C：变量与格式化输出
来源：http://dali.chenlongwang.top/Article/details/gttfqcmpip.html

int a = 10; printf("%d\n", a);
来源：http://dali.vqdsnc.cn/Article/details/gtazhbiewg.html

[S03] C：读入整数
来源：http://dali.hysaishi.cn/Article/details/gteizwnghs.html

int x; scanf("%d", &x);
来源：http://dali.yj20258.top/Article/details/gtinsdfiaq.html

[S04] C：字符串复制
来源：http://dali.jianghu66.top/Article/details/gtehimorxv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tanke756.top/Article/details/gtuyodjeir.html

[S05] C：字符串长度
来源：http://dali.birdmap.top/Article/details/gtmturkyeh.html

strlen(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoswweflu.html

[S06] C：字符串比较
来源：http://dali.jianghu66.top/Article/details/gtydumdifl.html

strcmp(a, b) == 0
来源：http://dali.0kj1m.cn/Article/details/gtiurteaqs.html

[S07] C：数组遍历求和
来源：http://dali.yvedp.cn/Article/details/gtpjkqconp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hywenlv.cn/Article/details/gtafjyqolx.html

[S08] C：动态内存分配与释放
来源：http://dali.0kj1m.cn/Article/details/gtbkjmzyjq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.daria6918.cn/Article/details/gtdiugkbhk.html

[S09] C：结构体定义与初始化
来源：http://dali.gogol.net.cn/Article/details/gtbgbpsvyp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.guowangkeji.top/Article/details/gtjrhiirar.html

[S10] C：指针与解引用
来源：http://dali.jlsjyb.cn/Article/details/gtwqihwxuk.html

int *p = &a;  *p = 5;
来源：http://dali.smart0.xyz/Article/details/gtmxdzjxzl.html

[S11] C：逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gtkrawkgkl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj20258.top/Article/details/gtasvuatoq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gtazwwumzl.html

fclose(f);
来源：http://dali.dashuyun.cn/Article/details/gtggimwhpe.html

[S12] C：写文件
来源：http://dali.cdnleiting.top/Article/details/gtjaxrksoe.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xuanzx.com/Article/details/gtjryspgzg.html

[S13] C：宏定义
来源：http://dali.hfpthk.cn/Article/details/gtyffdsiff.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.c1oappe.top/Article/details/gtjvbpwjtv.html

[S14] C：枚举
来源：http://dali.jiagoushi.top/Article/details/gtcauddumu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zycfv.cn/Article/details/gtuftykdmx.html

[S15] C：类型转换
来源：http://dali.jinqigfzy.top/Article/details/gtygstrlct.html

(double) a / b
来源：http://dali.wangdashe.top/Article/details/gtuyzvedbk.html

[S16] C：位操作置位
来源：http://dali.zycfv.cn/Article/details/gtanpxtjus.html

x |= (1 << 3);
来源：http://dali.gogol.net.cn/Article/details/gtdearodif.html

[S17] C：安全拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtprgancix.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cucudq.cn/Article/details/gthrfybell.html

[S18] C：命令行参数
来源：http://dali.ivvv.top/Article/details/gtnautuepw.html

int main(int argc, char **argv)
来源：http://dali.daria6918.cn/Article/details/gttykjvurh.html

[S19] C：快速排序
来源：http://dali.cqqwz.cn/Article/details/gtbwczglzv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.iojbl.cn/Article/details/gttgsypese.html

[S20] C：二分查找
来源：http://dali.0kj1m.cn/Article/details/gtxvycypyz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yongpay.top/Article/details/gteyvywalb.html

[S21] C：字符类别判断
来源：http://dali.andypj.xyz/Article/details/gtpvouksbv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jlsjyb.cn/Article/details/gtensslrue.html

[S22] C：字符串转数字
来源：http://dali.chenzaomai.com/Article/details/gtpuvwldha.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.dianchejie.cn/Article/details/gtqgdtopbs.html

[S23] C：随机数
来源：http://dali.gaohongyu789.top/Article/details/gtljxqreyp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yvedp.cn/Article/details/gtqfbbsuli.html

[S24] C：获取本地时间
来源：http://dali.shangyingyoupin.top/Article/details/gtcunxunbl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ybcxt.top/Article/details/gtpcdhpyjr.html

[S25] C：内存拷贝
来源：http://dali.ybcxt.top/Article/details/gtnkmdltnv.html

memcpy(dst, src, n);
来源：http://dali.birdmap.top/Article/details/gtlzwcrome.html

[S26] C：内存清零
来源：http://dali.yonumen.top/Article/details/gtbxthdmba.html

memset(a, 0, sizeof a);
来源：http://dali.chenlongwang.top/Article/details/gtapchvsky.html

[S27] C：定义常量
来源：http://dali.aibaodan.cn/Article/details/gthjeqekml.html

const double PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtvoqpxgxk.html

[S28] C：静态变量
来源：http://dali.yueranfly.top/Article/details/gtgyxqnybo.html

static int counter = 0;
来源：http://dali.fengsongda.top/Article/details/gtfnbfqrxo.html

[S29] C：变参函数
来源：http://dali.iojbl.cn/Article/details/gttdetjuxj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.guowangkeji.top/Article/details/gtaljtshhd.html

[S30] C：头文件保护
来源：http://dali.ehwqpu.com/Article/details/gtblpybjhg.html

#ifndef X_H
来源：http://dali.daxiang520.top/Article/details/gtuurdwjsu.html

#define X_H
来源：http://dali.iojbl.cn/Article/details/gtmprplhjr.html

#endif
来源：http://dali.wangdashe.top/Article/details/gtecgxvyho.html

[S31] C++：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtusauuodu.html

#include <iostream>
来源：http://dali.fengsongda.top/Article/details/gtnyuquttg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jqgufenzy.top/Article/details/gtmmhsibru.html

[S32] C++：字符串
来源：http://dali.meibo888.top/Article/details/gtrfdkvknb.html

std::string s = "hi";  s += "!";
来源：http://dali.hongshengwenyu.top/Article/details/gtybwqxqgr.html

[S33] C++：vector 增删
来源：http://dali.jqgufenzy.top/Article/details/gtasjxcrou.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhongyouzk.top/Article/details/gtvdynpmmp.html

[S34] C++：遍历 vector
来源：http://dali.zhoulong.xyz/Article/details/gtcvishicc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yuxming.cn/Article/details/gtrtxueigq.html

[S35] C++：map
来源：http://dali.meibo888.top/Article/details/gtqblkbbec.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtpdblubyt.html

[S36] C++：unordered_map
来源：http://dali.nanxinkj.top/Article/details/gtwhdwadxq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cucudq.cn/Article/details/gtczzcsoza.html

[S37] C++：set
来源：http://dali.316326.xyz/Article/details/gtcsuhusdk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cashguo.top/Article/details/gtcvezeipp.html

[S38] C++：排序
来源：http://dali.meibo888.top/Article/details/gthayapqvu.html

std::sort(v.begin(), v.end());
来源：http://dali.wangdashe.top/Article/details/gtvbslxzbi.html

[S39] C++：自定义比较器排序
来源：http://dali.xinyue.icu/Article/details/gtjbldhdcs.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guowangkeji.top/Article/details/gtqscedzln.html

[S40] C++：查找元素
来源：http://dali.sysykeji.top/Article/details/gtuxjgtfqh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hammf.cn/Article/details/gtpsekrihk.html

[S41] C++：类与构造函数
来源：http://dali.iojbl.cn/Article/details/gtgfnezcwj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yuanzhike.top/Article/details/gtlvkniefj.html

[S42] C++：继承与虚函数
来源：http://dali.gotoacloud.top/Article/details/gtgkvsmcvi.html

class B : public Base { public: void f() override {} };
来源：http://dali.redwolf501.top/Article/details/gtudsmyuwz.html

[S43] C++：智能指针
来源：http://dali.daxiang520.top/Article/details/gtvxxhbttg.html

auto p = std::make_unique<int>(5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzrenniri.html

[S44] C++：引用传参
来源：http://dali.daria6918.cn/Article/details/gtvwyweaaf.html

void inc(int &x) { ++x; }
来源：http://dali.dashuyun.cn/Article/details/gtyyliczqa.html

[S45] C++：lambda
来源：http://dali.ydzc1.top/Article/details/gtsilucfto.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jiagoushi.top/Article/details/gtebcdwees.html

[S46] C++：函数模板
来源：http://dali.jqgufenzy.top/Article/details/gtjldnhoma.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gogol.net.cn/Article/details/gttjcpwypb.html

[S47] C++：结构化绑定遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtcgdpznaq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jyoumei.cn/Article/details/gtzhksooni.html

[S48] C++：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gtnknxfwwr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhiwuduotai.top/Article/details/gtxtkdjbqj.html

while (std::getline(in, line)) { }
来源：http://dali.zhengqikj.top/Article/details/gtkrnotpwk.html

[S49] C++：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtectvfuyv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.c1oappe.top/Article/details/gtdlcqwpxm.html

[S50] C++：格式化数字
来源：http://dali.dashuyun.cn/Article/details/gtgaidhzfs.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gtetwxfhuo.html

[S51] C++：显式类型转换
来源：http://dali.zdqjudy.top/Article/details/gtkjnaatlw.html

static_cast<double>(a) / b
来源：http://dali.jinqigfzy.top/Article/details/gtlmodfdit.html

[S52] C++：const 与 noexcept
来源：http://dali.hongshengwenyu.top/Article/details/gtusjagnvk.html

int size() const noexcept { return n_; }
来源：http://dali.sufxvd.cn/Article/details/gtipcmqywg.html

[S53] C++：移动语义
来源：http://dali.gzhubu.top/Article/details/gtrpyjjide.html

std::vector<int> w = std::move(v);
来源：http://dali.smart0.xyz/Article/details/gtdahvlubd.html

[S54] C++：异常处理
来源：http://dali.ppjwa.cn/Article/details/gtsvbldebr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tianlin.xyz/Article/details/gtkhilsbuo.html

[S55] C++：结构化绑定
来源：http://dali.shangyingyoupin.top/Article/details/gtuupbjbso.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ybcxt.top/Article/details/gtywazeoax.html

[S56] C++：optional
来源：http://dali.guannengcc.top/Article/details/gtyqpocmfy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ydzc1.top/Article/details/gtvwjelykd.html

[S57] C++：编译期常量
来源：http://dali.sweek.top/Article/details/gtumdudkfm.html

constexpr int N = 10;
来源：http://dali.dianchejie.cn/Article/details/gtpiqfdthj.html

[S58] C++：命名空间
来源：http://dali.tian-w.cn/Article/details/gtgavfupwi.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoahucjnh.html

[S59] C++：静态断言
来源：http://dali.bjfxy.top/Article/details/gtmumvezur.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.haohaochexian.top/Article/details/gtoqrbumot.html

[S60] C++：遍历并删除元素
来源：http://dali.nanxinkj.top/Article/details/gtxtycpuhn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.dianchejie.cn/Article/details/gthvufwmme.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtvfipzisg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xuetiantiany.cn/Article/details/gttyrvtwfh.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtgkhcihpz.html

[T01] Kotlin：Hello World
来源：http://dali.0kj1m.cn/Article/details/gteravtojb.html

println("Hello")
来源：http://dali.cqqwz.cn/Article/details/gtgquahgpf.html

[T02] Kotlin：变量
来源：http://dali.ybcxt.top/Article/details/gtrmsvokzx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcocnayfb.html

[T03] Kotlin：字符串模板
来源：http://dali.dianchejie.cn/Article/details/gthrkbzdye.html

"值: $b"
来源：http://dali.jqgfzy.top/Article/details/gtqkzesulu.html

[T04] Kotlin：空安全
来源：http://dali.meibo888.top/Article/details/gtfgjvfnap.html

val n: String? = null;  n?.length
来源：http://dali.zhiwuduotai.top/Article/details/gtjhhdkddk.html

[T05] Kotlin：when 表达式
来源：http://dali.ybcxt.top/Article/details/gtmcrehnfw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinqigufen.top/Article/details/gtjqmzdvym.html

[T06] Kotlin：集合映射
来源：http://dali.aibaodan.cn/Article/details/gtbmyunvqn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtdtulnite.html

[T07] Kotlin：集合过滤
来源：http://dali.dianchejie.cn/Article/details/gtyenbkdxv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.redwolf501.top/Article/details/gtzwibovwd.html

[T08] Kotlin：数据类
来源：http://dali.jianghu66.top/Article/details/gtipaybecx.html

data class User(val name: String, val age: Int)
来源：http://dali.vqdsnc.cn/Article/details/gtyqcmsfvn.html

[T09] Kotlin：扩展函数
来源：http://dali.pycfn.com/Article/details/gtvrplklvd.html

fun String.exclaim() = this + "!"
来源：http://dali.dianchejie.cn/Article/details/gtlblsdrnc.html

[T10] Kotlin：默认参数
来源：http://dali.gaohongyu789.top/Article/details/gtpuzufdnc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.haohaochexian.top/Article/details/gtcsyeawkm.html

[T11] Kotlin：协程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtybeepxpe.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jqgfzy.top/Article/details/gtjfxnjksx.html

[T12] Kotlin：解构声明
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfbnjijwi.html

val (a, b) = Pair(1, 2)
来源：http://dali.kuanghao11.cn/Article/details/gtpaeslsvr.html

[T13] Kotlin：只读 Map
来源：http://dali.smart0.xyz/Article/details/gtpbxkxcba.html

val m = mapOf("a" to 1)
来源：http://dali.ybcxt.top/Article/details/gtedfnqlpt.html

[T14] Kotlin：循环
来源：http://dali.ivvv.top/Article/details/gtuilsvnge.html

for (i in 1..10) println(i)
来源：http://dali.fengsongda.top/Article/details/gtggirfdbr.html

[T15] Kotlin：接口
来源：http://dali.cqqwz.cn/Article/details/gtsgmusxcx.html

interface Shape { fun area(): Double }
来源：http://dali.cqqwz.cn/Article/details/gtffzduzlr.html

[T16] Swift：Hello World
来源：http://dali.meibo888.top/Article/details/gtrrfdlfij.html

print("Hello")
来源：http://dali.yvedp.cn/Article/details/gtuvizonzg.html

[T17] Swift：变量与常量
来源：http://dali.hnqzz.top/Article/details/gtxhvezpbb.html

var a = 1;  let b = 2
来源：http://dali.hfpthk.cn/Article/details/gtnkdvegjh.html

[T18] Swift：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gtqmovhzxm.html

"值: \(b)"
来源：http://dali.gzhubu.top/Article/details/gtbsufxfbz.html

[T19] Swift：可选绑定
来源：http://dali.gogol.net.cn/Article/details/gtvihbyuxy.html

if let n = opt { print(n) }
来源：http://dali.fengsongda.top/Article/details/gtyapkylhm.html

[T20] Swift：数组操作
来源：http://dali.hammf.cn/Article/details/gthyztgdyz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhiwuduotai.top/Article/details/gtpahalkss.html

[T21] Swift：遍历
来源：http://dali.birdmap.top/Article/details/gtelsgocjo.html

for x in a { print(x) }
来源：http://dali.birdmap.top/Article/details/gtlrqllxow.html

[T22] Swift：字典
来源：http://dali.cashguo.top/Article/details/gtqcyosuyg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.chenlongwang.top/Article/details/gtyhrrqveq.html

[T23] Swift：函数
来源：http://dali.sweek.top/Article/details/gtvzakuxfo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnvxffskp.html

[T24] Swift：闭包
来源：http://dali.ydzc1.top/Article/details/gtkxvwifyl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yonumen.top/Article/details/gtohwafpnt.html

[T25] Swift：结构体
来源：http://dali.andypj.xyz/Article/details/gtwxtownwd.html

struct P { var x: Int }
来源：http://dali.fengsongda.top/Article/details/gtqbfdjcsq.html

[T26] Swift：类与重写
来源：http://dali.dianchejie.cn/Article/details/gtxaqjzmhh.html

class A: Base { override func f() {} }
来源：http://dali.hywenlv.cn/Article/details/gtkwzrdsom.html

[T27] Swift：错误处理
来源：http://dali.iojbl.cn/Article/details/gtbtligwgp.html

do { try f() } catch { print(error) }
来源：http://dali.xuanzx.com/Article/details/gtensgpllw.html

[T28] Swift：枚举
来源：http://dali.hnqzz.top/Article/details/gttnpmcifw.html

enum Color { case red, green }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdlaassf.html

[T29] Swift：guard 提前返回
来源：http://dali.nwbrower.top/Article/details/gtptsxjtui.html

guard let x = opt else { return }
来源：http://dali.shuidangran.top/Article/details/gtyimfuhki.html

[T30] Swift：协议
来源：http://dali.gogol.net.cn/Article/details/gtbawavoly.html

protocol Shape { func area() -> Double }
来源：http://dali.hfpthk.cn/Article/details/gtlposygut.html

[T31] Lua：Hello World
来源：http://dali.0kj1m.cn/Article/details/gttiaokuhx.html

print("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gtdzwnpksp.html

[T32] Lua：局部变量
来源：http://dali.yuanzhike.top/Article/details/gtooumfzsx.html

local a = 1
来源：http://dali.jianghu66.top/Article/details/gtnffnyqsr.html

[T33] Lua：表（数组）
来源：http://dali.cashguo.top/Article/details/gtgaawdnzc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhongyouzk.top/Article/details/gtnxufcglp.html

[T34] Lua：遍历表
来源：http://dali.hnqzz.top/Article/details/gtfhqjbegr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jianghu66.top/Article/details/gtvrfemjqz.html

[T35] Lua：字典表
来源：http://dali.gotoacloud.top/Article/details/gtawtyryoe.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tianlin.xyz/Article/details/gtijvfruzz.html

[T36] Lua：函数
来源：http://dali.birdmap.top/Article/details/gtptrbhqvi.html

function add(a, b) return a + b end
来源：http://dali.9152youxi.cn/Article/details/gthxqgstok.html

[T37] Lua：字符串拼接
来源：http://dali.jyoumei.cn/Article/details/gtdskxetrq.html

"a" .. "b"
来源：http://dali.pengpengdd.cyou/Article/details/gtwrzzkuqs.html

[T38] Lua：条件
来源：http://dali.zdqjudy.top/Article/details/gtrmghbzbz.html

if x > 0 then print("正") end
来源：http://dali.bjfxy.top/Article/details/gtqgggtsxy.html

[T39] Lua：模式匹配
来源：http://dali.shuidangran.top/Article/details/gtjoequnxm.html

string.find(s, "%d+")
来源：http://dali.iojbl.cn/Article/details/gtjnxwrhvs.html

[T40] Lua：元表
来源：http://dali.jqgufenzy.top/Article/details/gtamkuclku.html

setmetatable({}, { __index = base })
来源：http://dali.jyoumei.cn/Article/details/gtbkryoylg.html

[T41] Perl：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtktexswqg.html

print "Hello\n";
来源：http://dali.cdnleiting.top/Article/details/gtdptjaidm.html

[T42] Perl：变量类型
来源：http://dali.cucudq.cn/Article/details/gtzzwsxfxm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.haohaochexian.top/Article/details/gtrzsmsuwv.html

[T43] Perl：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gtqkxhilux.html

"值: $a"
来源：http://dali.sxryk.cn/Article/details/gtuvvtccuq.html

[T44] Perl：条件
来源：http://dali.zycfv.cn/Article/details/gttmbfhoba.html

if ($a > 0) { print "正"; }
来源：http://dali.hywenlv.cn/Article/details/gtmncrtdfi.html

[T45] Perl：数组遍历
来源：http://dali.shuidangran.top/Article/details/gtotiifoyl.html

for my $x (@arr) { print $x; }
来源：http://dali.9152youxi.cn/Article/details/gtitozgqnr.html

[T46] Perl：哈希操作
来源：http://dali.zhongyouzk.top/Article/details/gtwkwiaszf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.nwbrower.top/Article/details/gtljyggmjb.html

[T47] Perl：正则捕获
来源：http://dali.xuetiantiany.cn/Article/details/gthkkfevav.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zdqjudy.top/Article/details/gtlwhrunur.html

[T48] Perl：正则替换
来源：http://dali.aibaodan.cn/Article/details/gtlbasqofu.html

$s =~ s/old/new/g;
来源：http://dali.chenzaomai.com/Article/details/gtqkfpvbjm.html

[T49] Perl：函数
来源：http://dali.zhixingplan.top/Article/details/gtcjuwrhqj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gtbzbklbqd.html

[T50] Perl：逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gtquwnwdoo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yvedp.cn/Article/details/gtbbhvcgbs.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.bjfxy.top/Article/details/gtvzwazxvd.html

[T51] Scala：Hello World
来源：http://dali.pycfn.com/Article/details/gtzishtxwb.html

println("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gttldrjodt.html

[T52] Scala：变量
来源：http://dali.dashuyun.cn/Article/details/gtmdfpayas.html

val a = 1;  var b = 2
来源：http://dali.snrcjt.cn/Article/details/gtkhtburxc.html

[T53] Scala：字符串插值
来源：http://dali.yueranfly.top/Article/details/gtjqgsdlta.html

s"值: $b"
来源：http://dali.jiagoushi.top/Article/details/gtpfxbkwmb.html

[T54] Scala：集合映射
来源：http://dali.redwolf501.top/Article/details/gtwwzuwcwi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hammf.cn/Article/details/gtbjmndvsv.html

[T55] Scala：集合过滤
来源：http://dali.jiagoushi.top/Article/details/gtpisskxfc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.pycfn.com/Article/details/gtzoxsazlj.html

[T56] Scala：样例类
来源：http://dali.yangfankeji.com/Article/details/gtdxcdsoty.html

case class User(name: String, age: Int)
来源：http://dali.zhengqikj.top/Article/details/gtxidnhapm.html

[T57] Scala：模式匹配
来源：http://dali.yuxming.cn/Article/details/gtysttveni.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.guannengcc.top/Article/details/gtqwqmrabm.html

[T58] Scala：函数定义
来源：http://dali.shanyushiyangtech.top/Article/details/gtvrqpyzzd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gogol.net.cn/Article/details/gteexskaga.html

[T59] Scala：循环
来源：http://dali.jyoumei.cn/Article/details/gtygrbqxne.html

for (i <- 1 to 10) println(i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxwatbcp.html

[T60] Scala：折叠
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpeconomw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ehwqpu.com/Article/details/gtkczptmds.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtepdxxdkr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yonumen.top/Article/details/gtoqbfstsy.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqxldjddh.html

[U01] Py：创建虚拟环境
来源：http://dali.dashuyun.cn/Article/details/gttftljawf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.guannengcc.top/Article/details/gtspcoxhpl.html

[U02] Py：导出 / 安装依赖
来源：http://dali.316326.xyz/Article/details/gtrlphajda.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cdnleiting.top/Article/details/gttlwcqjzm.html


<!-- 参考信息 -->