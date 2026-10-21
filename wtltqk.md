代发 wailian999

ssh user@host 'uptime'
来源：http://dali.hongshengwenyu.top/Article/details/gthgkxkniv.html

[R58] 下载文件
来源：http://dali.pycfn.com/Article/details/gtmxjyowmt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tian-w.cn/Article/details/gtoiozbkee.html

[R59] 发 POST JSON
来源：http://dali.yangfankeji.com/Article/details/gtskpkzrnn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.andypj.xyz/Article/details/gtyskvipcu.html

[R60] 只看 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gtnugxxzxl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ehwqpu.com/Article/details/gtlxagnatj.html

[R61] 磁盘占用
来源：http://dali.aizwys.cn/Article/details/gtjktogmsc.html

df -h;  du -sh *
来源：http://dali.haohaochexian.top/Article/details/gtucpfswen.html

[R62] 找最占空间的文件
来源：http://dali.jinqigfzy.top/Article/details/gtvdqovlhq.html

du -ah . | sort -rh | head -10
来源：http://dali.yuxming.cn/Article/details/gtbpfuarst.html

[R63] 内存与进程
来源：http://dali.pengpengdd.cyou/Article/details/gtsvwjvksh.html

free -h;  ps aux | grep nginx
来源：http://dali.nanxinkj.top/Article/details/gtnxcojwum.html

[R64] 结束进程
来源：http://dali.sysykeji.top/Article/details/gtuocsazkg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwxwmxxvj.html

[R65] 查看端口占用
来源：http://dali.hammf.cn/Article/details/gtbgqoljzg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.dashuyun.cn/Article/details/gtuxmdfomj.html

[R66] 定时任务
来源：http://dali.ehwqpu.com/Article/details/gtyjcwscgk.html

crontab -e;  crontab -l
来源：http://dali.xylfe.cn/Article/details/gtyshmiutf.html

[R67] 生成随机十六进制串
来源：http://dali.smart0.xyz/Article/details/gthbpcxbkt.html

openssl rand -hex 16
来源：http://dali.hfpthk.cn/Article/details/gthlzjyviu.html

[R68] 计算文件校验值
来源：http://dali.cucudq.cn/Article/details/gtqpzshjxi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xinyue.icu/Article/details/gtsrnmmfck.html

[R69] 生成随机密码
来源：http://dali.jinghuilouyu.cn/Article/details/gtkgwjnrkm.html

head -c 16 /dev/urandom | base64
来源：http://dali.hnqzz.top/Article/details/gtrxfpofwy.html

[R70] 时间戳与互转
来源：http://dali.fengsongda.top/Article/details/gtrjanswvx.html

date +%s;  date -d @1700000000
来源：http://dali.cqqwz.cn/Article/details/gttxznjxzs.html

[R71] 日期格式化
来源：http://dali.sufxvd.cn/Article/details/gtrizkdamg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuexbzdsn.html

[R72] 等待端口就绪
来源：http://dali.hysaishi.cn/Article/details/gtungrftad.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gtztmfrxfi.html

[R73] 分割大日志
来源：http://dali.zhengqikj.top/Article/details/gtvpsuudxt.html

split -l 1000 big.log part_
来源：http://dali.gotoacloud.top/Article/details/gtergvorem.html

[R74] 批量重命名
来源：http://dali.xuetiantiany.cn/Article/details/gtzyketvua.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenlongwang.top/Article/details/gtsgfokjtr.html

[R75] 导出环境变量
来源：http://dali.zhengqikj.top/Article/details/gtfzphbiou.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xuetiantiany.cn/Article/details/gtbgrbtijw.html

[R76] 使用临时文件
来源：http://dali.shzxlz.cn/Article/details/gtycmpjtxv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinghuilouyu.cn/Article/details/gtchxxdxss.html

[R77] 读取用户输入
来源：http://dali.gzhubu.top/Article/details/gtfnyoxbfi.html

read -rp "请输入: " ans
来源：http://dali.zdqjudy.top/Article/details/gtknbxweok.html

[R78] 交互式菜单
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfacdcbwz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhengqikj.top/Article/details/gtcfgktrys.html

[R79] 解析命令行选项
来源：http://dali.xuanzx.com/Article/details/gtzfioqcry.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.meibo888.top/Article/details/gtgvqiaunz.html

[R80] 查看脚本执行耗时
来源：http://dali.chenzaomai.com/Article/details/gtdcgdjcfm.html

time ./run.sh
来源：http://dali.nwbrower.top/Article/details/gtcdgzqwtd.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtitteoteu.html

S. C / C++ 专题
来源：http://dali.jqgufenzy.top/Article/details/gtcwlutfsf.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gthseqlpjx.html

[S01] C：Hello World
来源：http://dali.mhx1999.top/Article/details/gtembmdjvr.html

#include <stdio.h>
来源：http://dali.gogol.net.cn/Article/details/gtieajcxnp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkgusdzig.html

[S02] C：变量与格式化输出
来源：http://dali.jinghuilouyu.cn/Article/details/gtgswxkvpp.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinqigfzy.top/Article/details/gturoxtccw.html

[S03] C：读入整数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmhgfqzly.html

int x; scanf("%d", &x);
来源：http://dali.andypj.xyz/Article/details/gtdxbdzkzb.html

[S04] C：字符串复制
来源：http://dali.sysykeji.top/Article/details/gtgnzuvavu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhengqikj.top/Article/details/gttexpxcki.html

[S05] C：字符串长度
来源：http://dali.nanxuanxn.top/Article/details/gtqmrusnwk.html

strlen(s)
来源：http://dali.316326.xyz/Article/details/gtyjfnthiu.html

[S06] C：字符串比较
来源：http://dali.zhixingplan.top/Article/details/gtvbipcrxu.html

strcmp(a, b) == 0
来源：http://dali.nanxuanxn.top/Article/details/gtavzsgnja.html

[S07] C：数组遍历求和
来源：http://dali.svipenyu.cn/Article/details/gtvewpfqlt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gtebjnuuly.html

[S08] C：动态内存分配与释放
来源：http://dali.9152youxi.cn/Article/details/gtxvcvfgmx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shangyingyoupin.top/Article/details/gtmhhvdkfr.html

[S09] C：结构体定义与初始化
来源：http://dali.shanyushiyangtech.top/Article/details/gtuqyigswo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shanyushiyangkeji.top/Article/details/gttnptntfc.html

[S10] C：指针与解引用
来源：http://dali.shuidangran.top/Article/details/gtfumqipeh.html

int *p = &a;  *p = 5;
来源：http://dali.hammf.cn/Article/details/gtqaohudgk.html

[S11] C：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtuesvetfg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ivvv.top/Article/details/gtiznjgmev.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.haohaochexian.top/Article/details/gtptrbmlwm.html

fclose(f);
来源：http://dali.vqdsnc.cn/Article/details/gtfujyxqzw.html

[S12] C：写文件
来源：http://dali.shangyingyoupin.top/Article/details/gtmfldntfw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shuidangran.top/Article/details/gtcdnmhzyz.html

[S13] C：宏定义
来源：http://dali.pycfn.com/Article/details/gtoiwwunyu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.mhx1999.top/Article/details/gttiooippy.html

[S14] C：枚举
来源：http://dali.cqqwz.cn/Article/details/gtrahnrciw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhiwuduotai.top/Article/details/gtuojwjfky.html

[S15] C：类型转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttboiyfey.html

(double) a / b
来源：http://dali.wangshuangyany.cn/Article/details/gtlqmeverf.html

[S16] C：位操作置位
来源：http://dali.jinqigufen.top/Article/details/gtlloqfboj.html

x |= (1 << 3);
来源：http://dali.yj20258888.top/Article/details/gtfxizbinq.html

[S17] C：安全拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gtwjbpliru.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yuanzhike.top/Article/details/gtlrfoliab.html

[S18] C：命令行参数
来源：http://dali.sxryk.cn/Article/details/gtjldhozot.html

int main(int argc, char **argv)
来源：http://dali.hammf.cn/Article/details/gtxsjawuij.html

[S19] C：快速排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtiwwqequn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.havefunace.top/Article/details/gtwnlmyxyn.html

[S20] C：二分查找
来源：http://dali.andypj.xyz/Article/details/gtxdokifpy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gtaaljnlmh.html

[S21] C：字符类别判断
来源：http://dali.shangyingyoupin.top/Article/details/gtuflxuror.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tianlin.xyz/Article/details/gtkjqsrtwf.html

[S22] C：字符串转数字
来源：http://dali.jiagoushi.top/Article/details/gtoxiimoaq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tian-w.cn/Article/details/gtdbibsouz.html

[S23] C：随机数
来源：http://dali.yvedp.cn/Article/details/gtapopigtj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.guowangkeji.top/Article/details/gtwpsbtqel.html

[S24] C：获取本地时间
来源：http://dali.jqgufenzy.top/Article/details/gtcvqbemxt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jqgfzy.top/Article/details/gtsqsukfgj.html

[S25] C：内存拷贝
来源：http://dali.yuxming.cn/Article/details/gtykplvmsi.html

memcpy(dst, src, n);
来源：http://dali.hfpthk.cn/Article/details/gtznmggyhg.html

[S26] C：内存清零
来源：http://dali.snrcjt.cn/Article/details/gtyuhiksvg.html

memset(a, 0, sizeof a);
来源：http://dali.xuanzx.com/Article/details/gthvibrsuo.html

[S27] C：定义常量
来源：http://dali.jqgfzy.top/Article/details/gtsgsshwgy.html

const double PI = 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gtaqloqifd.html

[S28] C：静态变量
来源：http://dali.feifeiyinyue.top/Article/details/gtjbqmgmbj.html

static int counter = 0;
来源：http://dali.tian-w.cn/Article/details/gtriaafbky.html

[S29] C：变参函数
来源：http://dali.andypj.xyz/Article/details/gtziltkidg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zdqjudy.top/Article/details/gtxqywhhaj.html

[S30] C：头文件保护
来源：http://dali.hywenlv.cn/Article/details/gtxzdyxavu.html

#ifndef X_H
来源：http://dali.redwolf501.top/Article/details/gtxuqsvfsy.html

#define X_H
来源：http://dali.zycfv.cn/Article/details/gtxepdvwpk.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gtxjlcybeu.html

[S31] C++：Hello World
来源：http://dali.ivvv.top/Article/details/gtzysbvpcx.html

#include <iostream>
来源：http://dali.jinghuilouyu.cn/Article/details/gtbaanpqab.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cdnleiting.top/Article/details/gtgovumcoj.html

[S32] C++：字符串
来源：http://dali.meibo888.top/Article/details/gtbycrdelq.html

std::string s = "hi";  s += "!";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiqgyicco.html

[S33] C++：vector 增删
来源：http://dali.yanxiufei.cn/Article/details/gtvqkpaixn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xinyue.icu/Article/details/gtawqcmitv.html

[S34] C++：遍历 vector
来源：http://dali.316326.xyz/Article/details/gtulxgqloj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ivvv.top/Article/details/gtgrdngubz.html

[S35] C++：map
来源：http://dali.iojbl.cn/Article/details/gtumiqbksk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtdkutaxsm.html

[S36] C++：unordered_map
来源：http://dali.jlsjyb.cn/Article/details/gtkhmoexiv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gtghomlcok.html

[S37] C++：set
来源：http://dali.yangfankeji.com/Article/details/gtptibjzek.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yonumen.top/Article/details/gtldsktfma.html

[S38] C++：排序
来源：http://dali.jlsjyb.cn/Article/details/gtsyqcrmii.html

std::sort(v.begin(), v.end());
来源：http://dali.aibaodan.cn/Article/details/gtwyrfhiky.html

[S39] C++：自定义比较器排序
来源：http://dali.0kj1m.cn/Article/details/gtympscxdu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.quarkkingdee.top/Article/details/gtyjnenkpb.html

[S40] C++：查找元素
来源：http://dali.pycfn.com/Article/details/gteimnyrjo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ydzc1.top/Article/details/gtidqjlkyg.html

[S41] C++：类与构造函数
来源：http://dali.dianchejie.cn/Article/details/gtfsahmjbj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yanxiufei.cn/Article/details/gtagxlwfdp.html

[S42] C++：继承与虚函数
来源：http://dali.daria6918.cn/Article/details/gtacdfzvvj.html

class B : public Base { public: void f() override {} };
来源：http://dali.chenlongwang.top/Article/details/gtwqootuez.html

[S43] C++：智能指针
来源：http://dali.smart0.xyz/Article/details/gtrzszlznd.html

auto p = std::make_unique<int>(5);
来源：http://dali.yueranfly.top/Article/details/gtrqoimlcw.html

[S44] C++：引用传参
来源：http://dali.hfpthk.cn/Article/details/gtwgjcdjnp.html

void inc(int &x) { ++x; }
来源：http://dali.daxiang520.top/Article/details/gtohlzltrt.html

[S45] C++：lambda
来源：http://dali.yj20258.top/Article/details/gtfbfbndwf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinghuilouyu.cn/Article/details/gthsoikodr.html

[S46] C++：函数模板
来源：http://dali.guowangkeji.top/Article/details/gtywbfjcvu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cqqwz.cn/Article/details/gtpbfdrjol.html

[S47] C++：结构化绑定遍历
来源：http://dali.cqqwz.cn/Article/details/gtpsjinwlk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ybcxt.top/Article/details/gtbtpixped.html

[S48] C++：逐行读文件
来源：http://dali.yonumen.top/Article/details/gtbkglzyom.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.dashuyun.cn/Article/details/gthyqvpkyz.html

while (std::getline(in, line)) { }
来源：http://dali.xziqi.cn/Article/details/gtvfqqigfk.html

[S49] C++：写文件
来源：http://dali.wangdashe.top/Article/details/gtwonebrrp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xziqi.cn/Article/details/gticgqmyao.html

[S50] C++：格式化数字
来源：http://dali.cqqwz.cn/Article/details/gtinbzjctp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.fengsongda.top/Article/details/gtpnpdpatu.html

[S51] C++：显式类型转换
来源：http://dali.zhixingplan.top/Article/details/gtdjwoofse.html

static_cast<double>(a) / b
来源：http://dali.mhx1999.top/Article/details/gtpdwmmmty.html

[S52] C++：const 与 noexcept
来源：http://dali.hnqzz.top/Article/details/gtwpcgjygf.html

int size() const noexcept { return n_; }
来源：http://dali.yj20258.top/Article/details/gtxmjwgvhj.html

[S53] C++：移动语义
来源：http://dali.yuanzhike.top/Article/details/gtlxhaurdp.html

std::vector<int> w = std::move(v);
来源：http://dali.gaohongyu789.top/Article/details/gtyremavqk.html

[S54] C++：异常处理
来源：http://dali.gaohongyu789.top/Article/details/gtzmqqcvpb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.pycfn.com/Article/details/gtletoerui.html

[S55] C++：结构化绑定
来源：http://dali.jinqigufen.top/Article/details/gtmdgazjyy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gaohongyu789.top/Article/details/gtateaesnz.html

[S56] C++：optional
来源：http://dali.cucudq.cn/Article/details/gtqbfaqhwd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sweek.top/Article/details/gtqvkcuhal.html

[S57] C++：编译期常量
来源：http://dali.hnqzz.top/Article/details/gtwwzxmfip.html

constexpr int N = 10;
来源：http://dali.wangshuangyany.cn/Article/details/gtvbeoldtq.html

[S58] C++：命名空间
来源：http://dali.sxryk.cn/Article/details/gtvlhrjbje.html

namespace ns { int f() { return 1; } }
来源：http://dali.haohaochexian.top/Article/details/gtvrlpckpt.html

[S59] C++：静态断言
来源：http://dali.cashguo.top/Article/details/gtfppanopf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yj202588.top/Article/details/gteqppsvfd.html

[S60] C++：遍历并删除元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzmqovinl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jqgufenzy.top/Article/details/gtwtjigyqu.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtiubccwlu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.guannengcc.top/Article/details/gtiwtrskrg.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gthtehxgvy.html

[T01] Kotlin：Hello World
来源：http://dali.ivvv.top/Article/details/gtcujqzewo.html

println("Hello")
来源：http://dali.xziqi.cn/Article/details/gtdoguftqv.html

[T02] Kotlin：变量
来源：http://dali.cdnleiting.top/Article/details/gtsjadzmlz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.pengpengdd.cyou/Article/details/gtkefiaxxv.html

[T03] Kotlin：字符串模板
来源：http://dali.xinyue.icu/Article/details/gtworpynap.html

"值: $b"
来源：http://dali.haohaochexian.top/Article/details/gttrbofznd.html

[T04] Kotlin：空安全
来源：http://dali.ydzc1.top/Article/details/gtncezgbwf.html

val n: String? = null;  n?.length
来源：http://dali.hongshengwenyu.top/Article/details/gtvfqjfizg.html

[T05] Kotlin：when 表达式
来源：http://dali.jqgfzy.top/Article/details/gtzxwbujpd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.vqdsnc.cn/Article/details/gtldzwrxgj.html

[T06] Kotlin：集合映射
来源：http://dali.snrcjt.cn/Article/details/gtnduxopgs.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gthirylluh.html

[T07] Kotlin：集合过滤
来源：http://dali.sxryk.cn/Article/details/gtmfxffxaw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tanke756.top/Article/details/gtrpwqzmop.html

[T08] Kotlin：数据类
来源：http://dali.zhiwuduotai.top/Article/details/gtocdplmos.html

data class User(val name: String, val age: Int)
来源：http://dali.nanxuanxn.top/Article/details/gtpakahlyd.html

[T09] Kotlin：扩展函数
来源：http://dali.zycfv.cn/Article/details/gtsrhtovmt.html

fun String.exclaim() = this + "!"
来源：http://dali.cheryme.top/Article/details/gtfutupbas.html

[T10] Kotlin：默认参数
来源：http://dali.yvedp.cn/Article/details/gtqnqlytug.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.0kj1m.cn/Article/details/gtubhmvynd.html

[T11] Kotlin：协程
来源：http://dali.hnxiangtu.top/Article/details/gtkqeqrgqu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.tian-w.cn/Article/details/gtzzckdmwb.html

[T12] Kotlin：解构声明
来源：http://dali.cucudq.cn/Article/details/gtpeqczchp.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhixingplan.top/Article/details/gtxiotkqup.html

[T13] Kotlin：只读 Map
来源：http://dali.sxryk.cn/Article/details/gteeacdufz.html

val m = mapOf("a" to 1)
来源：http://dali.jqgufenzy.top/Article/details/gtykdlarff.html

[T14] Kotlin：循环
来源：http://dali.ivvv.top/Article/details/gtuutkecou.html

for (i in 1..10) println(i)
来源：http://dali.jlsjyb.cn/Article/details/gtsxaivtrj.html

[T15] Kotlin：接口
来源：http://dali.dashuyun.cn/Article/details/gtctpudleb.html

interface Shape { fun area(): Double }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbjfqyip.html

[T16] Swift：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtnbktbjxm.html

print("Hello")
来源：http://dali.meibo888.top/Article/details/gtffvrvuny.html

[T17] Swift：变量与常量
来源：http://dali.havefunace.top/Article/details/gtwdqmsgal.html

var a = 1;  let b = 2
来源：http://dali.jlsjyb.cn/Article/details/gtfszgopvx.html

[T18] Swift：字符串插值
来源：http://dali.yonumen.top/Article/details/gtpwrrtybz.html

"值: \(b)"
来源：http://dali.jinqigfzy.top/Article/details/gtegfeegum.html

[T19] Swift：可选绑定
来源：http://dali.bjfxy.top/Article/details/gtxmnyptqe.html

if let n = opt { print(n) }
来源：http://dali.jqgufenzy.top/Article/details/gttvrkjcbe.html

[T20] Swift：数组操作
来源：http://dali.hfpthk.cn/Article/details/gtnpthowuu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj202588.top/Article/details/gtmhixjiyl.html

[T21] Swift：遍历
来源：http://dali.zhengqikj.top/Article/details/gtlncogldt.html

for x in a { print(x) }
来源：http://dali.fengsongda.top/Article/details/gtuorbibgc.html

[T22] Swift：字典
来源：http://dali.yuanzhike.top/Article/details/gtmkvnvbgw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xuanzx.com/Article/details/gtcczrxdth.html

[T23] Swift：函数
来源：http://dali.chenlongwang.top/Article/details/gtloifmpcv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sufxvd.cn/Article/details/gtbzzzotbz.html

[T24] Swift：闭包
来源：http://dali.feifeiyinyue.top/Article/details/gtrcwztouw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtriypeqjq.html

[T25] Swift：结构体
来源：http://dali.zdqjudy.top/Article/details/gtrziciuzb.html

struct P { var x: Int }
来源：http://dali.cashguo.top/Article/details/gtxekcmkbe.html

[T26] Swift：类与重写
来源：http://dali.hammf.cn/Article/details/gtlsjxdlju.html

class A: Base { override func f() {} }
来源：http://dali.sufxvd.cn/Article/details/gtyyzjwtil.html

[T27] Swift：错误处理
来源：http://dali.xuetiantiany.cn/Article/details/gtlkjivquf.html

do { try f() } catch { print(error) }
来源：http://dali.xziqi.cn/Article/details/gthihzjphx.html

[T28] Swift：枚举
来源：http://dali.dashuyun.cn/Article/details/gtngsesnyo.html

enum Color { case red, green }
来源：http://dali.jqgfzy.top/Article/details/gtisdprmqf.html

[T29] Swift：guard 提前返回
来源：http://dali.sufxvd.cn/Article/details/gtrwxfwrsk.html

guard let x = opt else { return }
来源：http://dali.jinqigufen.top/Article/details/gtorhtovls.html

[T30] Swift：协议
来源：http://dali.shanyushiyangtech.top/Article/details/gtoechvnbq.html

protocol Shape { func area() -> Double }
来源：http://dali.hysaishi.cn/Article/details/gtrhaxxocn.html

[T31] Lua：Hello World
来源：http://dali.daria6918.cn/Article/details/gtqjniczzu.html

print("Hello")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtspuothab.html

[T32] Lua：局部变量
来源：http://dali.shangyingyoupin.top/Article/details/gtkuhgquhx.html

local a = 1
来源：http://dali.zhongyouzk.top/Article/details/gtshqhkfix.html

[T33] Lua：表（数组）
来源：http://dali.zdqjudy.top/Article/details/gtvgymimrd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvxdadasa.html

[T34] Lua：遍历表
来源：http://dali.jyoumei.cn/Article/details/gtyyatyuyq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhengqikj.top/Article/details/gtzvgjxnev.html

[T35] Lua：字典表
来源：http://dali.daria6918.cn/Article/details/gtzirgkhkf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shangyingyoupin.top/Article/details/gtfpsppify.html

[T36] Lua：函数
来源：http://dali.havefunace.top/Article/details/gtjuanwdex.html

function add(a, b) return a + b end
来源：http://dali.shanyushiyangtech.top/Article/details/gtnsjwytwk.html

[T37] Lua：字符串拼接
来源：http://dali.havefunace.top/Article/details/gtwstlmqmf.html

"a" .. "b"
来源：http://dali.chenzaomai.com/Article/details/gtlwellqvf.html

[T38] Lua：条件
来源：http://dali.yj20258888.top/Article/details/gttubqsfzv.html

if x > 0 then print("正") end
来源：http://dali.yvedp.cn/Article/details/gtmmbqspwg.html

[T39] Lua：模式匹配
来源：http://dali.cheryme.top/Article/details/gtglqrpkmz.html

string.find(s, "%d+")
来源：http://dali.zhengqikj.top/Article/details/gtohzrjhew.html

[T40] Lua：元表
来源：http://dali.chenlongwang.top/Article/details/gtbpruddrx.html

setmetatable({}, { __index = base })
来源：http://dali.zhixingplan.top/Article/details/gtlazgllcj.html

[T41] Perl：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtdgfxwxxd.html

print "Hello\n";
来源：http://dali.shuidangran.top/Article/details/gtflvaayhm.html

[T42] Perl：变量类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdblhbktk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.pengpengdd.cyou/Article/details/gtgzrrbbik.html

[T43] Perl：字符串插值
来源：http://dali.jqgfzy.top/Article/details/gtddqyxzgl.html

"值: $a"
来源：http://dali.jqgufenzy.top/Article/details/gtvzzwsmcl.html

[T44] Perl：条件
来源：http://dali.gaohongyu789.top/Article/details/gtgkxsohit.html

if ($a > 0) { print "正"; }
来源：http://dali.redwolf501.top/Article/details/gtghzsizoe.html

[T45] Perl：数组遍历
来源：http://dali.ppjwa.cn/Article/details/gtfjogcueg.html

for my $x (@arr) { print $x; }
来源：http://dali.xziqi.cn/Article/details/gtpxummqkj.html

[T46] Perl：哈希操作
来源：http://dali.shzxlz.cn/Article/details/gtqxzphukj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gtzoetecwu.html

[T47] Perl：正则捕获
来源：http://dali.pycfn.com/Article/details/gtiuuxfejp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jlsjyb.cn/Article/details/gttewunhcl.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gtdgpcbihs.html

$s =~ s/old/new/g;
来源：http://dali.zdqjudy.top/Article/details/gtqzaryvtc.html

[T49] Perl：函数
来源：http://dali.wangdashe.top/Article/details/gtdivujraz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zycfv.cn/Article/details/gtqhdcktxr.html

[T50] Perl：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtkkxkszta.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.wangshuangyany.cn/Article/details/gtanggbciu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zycfv.cn/Article/details/gtzkjatdns.html

[T51] Scala：Hello World
来源：http://dali.andypj.xyz/Article/details/gtwpsdsmyc.html

println("Hello")
来源：http://dali.smart0.xyz/Article/details/gtdwpazbxk.html

[T52] Scala：变量
来源：http://dali.hysaishi.cn/Article/details/gtxruxybhw.html

val a = 1;  var b = 2
来源：http://dali.aibaodan.cn/Article/details/gtbbmagotn.html

[T53] Scala：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gtttqvwzto.html

s"值: $b"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtehovuymd.html

[T54] Scala：集合映射
来源：http://dali.andypj.xyz/Article/details/gtkoipezom.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.xuanzx.com/Article/details/gtguyhckky.html

[T55] Scala：集合过滤
来源：http://dali.yj202588.top/Article/details/gtvvtlwgyi.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hnxiangtu.top/Article/details/gtqgmvnaip.html

[T56] Scala：样例类
来源：http://dali.fzhhl.top/Article/details/gtytvksjti.html

case class User(name: String, age: Int)
来源：http://dali.kuanghao11.cn/Article/details/gtoacwcvjb.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gtfsccrwtw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.sufxvd.cn/Article/details/gtpwkiqymh.html

[T58] Scala：函数定义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcjgpkbvf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.daria6918.cn/Article/details/gtmmcwugnf.html

[T59] Scala：循环
来源：http://dali.sufxvd.cn/Article/details/gtbsgaxnev.html

for (i <- 1 to 10) println(i)
来源：http://dali.guannengcc.top/Article/details/gtggvmughq.html

[T60] Scala：折叠
来源：http://dali.quarkkingdee.top/Article/details/gtxhvvsbfw.html


<!-- 参考信息 -->