代发 wailian999

ssh user@host 'uptime'
来源：http://dali.guowangkeji.top/Article/details/gtzboandhp.html

[R58] 下载文件
来源：http://dali.quarkkingdee.top/Article/details/gtsztsqdtn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.pycfn.com/Article/details/gtbrcpotuj.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gtfapibufe.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ydzc1.top/Article/details/gtnryhdfup.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhoulong.xyz/Article/details/gtpquxrrad.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yuanzhike.top/Article/details/gtvualbbid.html

[R61] 磁盘占用
来源：http://dali.jyoumei.cn/Article/details/gtxeynczhj.html

df -h;  du -sh *
来源：http://dali.jinghuilouyu.cn/Article/details/gtzczuddyd.html

[R62] 找最占空间的文件
来源：http://dali.yanxiufei.cn/Article/details/gtkwqbmbuz.html

du -ah . | sort -rh | head -10
来源：http://dali.zhaomingkeji.xyz/Article/details/gtukkqgcsr.html

[R63] 内存与进程
来源：http://dali.c1oappe.top/Article/details/gtalukruwn.html

free -h;  ps aux | grep nginx
来源：http://dali.svipenyu.cn/Article/details/gtqqvleokv.html

[R64] 结束进程
来源：http://dali.zdqjudy.top/Article/details/gtyliqyecm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.dianchejie.cn/Article/details/gtzolttxdu.html

[R65] 查看端口占用
来源：http://dali.jinqigfzy.top/Article/details/gtgyczfgbe.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.0kj1m.cn/Article/details/gtoimkdrjf.html

[R66] 定时任务
来源：http://dali.daxiang520.top/Article/details/gtpajerwew.html

crontab -e;  crontab -l
来源：http://dali.jinghuilouyu.cn/Article/details/gtxbhprwsi.html

[R67] 生成随机十六进制串
来源：http://dali.guowangkeji.top/Article/details/gtzrmbstoy.html

openssl rand -hex 16
来源：http://dali.jianghu66.top/Article/details/gtdilwhwse.html

[R68] 计算文件校验值
来源：http://dali.guannengcc.top/Article/details/gtdsvfyptw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nwbrower.top/Article/details/gtbvybahgs.html

[R69] 生成随机密码
来源：http://dali.aibaodan.cn/Article/details/gtuqpfiacw.html

head -c 16 /dev/urandom | base64
来源：http://dali.sufxvd.cn/Article/details/gtkfgvwfwn.html

[R70] 时间戳与互转
来源：http://dali.guowangkeji.top/Article/details/gtcvxebmur.html

date +%s;  date -d @1700000000
来源：http://dali.xziqi.cn/Article/details/gtlrwmzalc.html

[R71] 日期格式化
来源：http://dali.shangyingyoupin.top/Article/details/gtmysctyjz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjdqpxlzz.html

[R72] 等待端口就绪
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsdzfkpsc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinqigufen.top/Article/details/gtfjfmggbg.html

[R73] 分割大日志
来源：http://dali.sysykeji.top/Article/details/gtvkrniuhv.html

split -l 1000 big.log part_
来源：http://dali.smart0.xyz/Article/details/gtveyftiyr.html

[R74] 批量重命名
来源：http://dali.jiagoushi.top/Article/details/gtfsfugefs.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jianghu66.top/Article/details/gtmnevcxau.html

[R75] 导出环境变量
来源：http://dali.gogol.net.cn/Article/details/gtmqhtcyyy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj202588.top/Article/details/gtomjyhvwn.html

[R76] 使用临时文件
来源：http://dali.yvedp.cn/Article/details/gtpanevyre.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sysykeji.top/Article/details/gtldnhywba.html

[R77] 读取用户输入
来源：http://dali.daria6918.cn/Article/details/gtycbokllf.html

read -rp "请输入: " ans
来源：http://dali.redwolf501.top/Article/details/gtublszzzd.html

[R78] 交互式菜单
来源：http://dali.yuxming.cn/Article/details/gtequiirmu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtylyzmske.html

[R79] 解析命令行选项
来源：http://dali.hongshengwenyu.top/Article/details/gtctenlfyk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gotoacloud.top/Article/details/gtkmiqznmo.html

[R80] 查看脚本执行耗时
来源：http://dali.havefunace.top/Article/details/gtlaolpxoc.html

time ./run.sh
来源：http://dali.pycfn.com/Article/details/gtvbbforom.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtledaupmn.html

S. C / C++ 专题
来源：http://dali.iojbl.cn/Article/details/gtjtzkjpdj.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtrachnrko.html

[S01] C：Hello World
来源：http://dali.meibo888.top/Article/details/gttdylfuga.html

#include <stdio.h>
来源：http://dali.ehwqpu.com/Article/details/gtpsqmrtlw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jqgufenzy.top/Article/details/gtlkjgntcx.html

[S02] C：变量与格式化输出
来源：http://dali.fengsongda.top/Article/details/gtlaasakrl.html

int a = 10; printf("%d\n", a);
来源：http://dali.hywenlv.cn/Article/details/gtsmfzawzo.html

[S03] C：读入整数
来源：http://dali.iojbl.cn/Article/details/gtziuwpaip.html

int x; scanf("%d", &x);
来源：http://dali.0kj1m.cn/Article/details/gtjhixnkaz.html

[S04] C：字符串复制
来源：http://dali.gaohongyu789.top/Article/details/gtnzcsjzyr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.snrcjt.cn/Article/details/gtrwfocggz.html

[S05] C：字符串长度
来源：http://dali.daria6918.cn/Article/details/gtxbxeahkb.html

strlen(s)
来源：http://dali.ivvv.top/Article/details/gtuqremwrv.html

[S06] C：字符串比较
来源：http://dali.nanxuanxn.top/Article/details/gtcvfthfqh.html

strcmp(a, b) == 0
来源：http://dali.zhengqikj.top/Article/details/gtbmzbbtif.html

[S07] C：数组遍历求和
来源：http://dali.redwolf501.top/Article/details/gtmgsmcfln.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhixingplan.top/Article/details/gtksvduojj.html

[S08] C：动态内存分配与释放
来源：http://dali.jinghuilouyu.cn/Article/details/gtdpiitwoc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shuidangran.top/Article/details/gtwoazueym.html

[S09] C：结构体定义与初始化
来源：http://dali.mhx1999.top/Article/details/gtvbyrmhhc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.iojbl.cn/Article/details/gtkjvrmasl.html

[S10] C：指针与解引用
来源：http://dali.xylfe.cn/Article/details/gtvaemdizy.html

int *p = &a;  *p = 5;
来源：http://dali.yanxiufei.cn/Article/details/gtqfxlkriw.html

[S11] C：逐行读文件
来源：http://dali.cucudq.cn/Article/details/gttusxovjd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hywenlv.cn/Article/details/gtbwfhfzuh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shuidangran.top/Article/details/gtugvbraac.html

fclose(f);
来源：http://dali.yj20258888.top/Article/details/gtztcydevw.html

[S12] C：写文件
来源：http://dali.aibaodan.cn/Article/details/gtomdfzotx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gogol.net.cn/Article/details/gtvwhuutib.html

[S13] C：宏定义
来源：http://dali.andypj.xyz/Article/details/gtpkqkcxks.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zdqjudy.top/Article/details/gtaagtpzlc.html

[S14] C：枚举
来源：http://dali.9152youxi.cn/Article/details/gtkelztmyo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yj20258888.top/Article/details/gtvrvrqids.html

[S15] C：类型转换
来源：http://dali.yonumen.top/Article/details/gtlznxzsfj.html

(double) a / b
来源：http://dali.kuanghao11.cn/Article/details/gttdldhfir.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gtgvazwbev.html

x |= (1 << 3);
来源：http://dali.sufxvd.cn/Article/details/gtonbpmetv.html

[S17] C：安全拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gtjnkbogtf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yuxming.cn/Article/details/gtnmjrftfp.html

[S18] C：命令行参数
来源：http://dali.c1oappe.top/Article/details/gtcvwvwpxp.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gtmctbhhex.html

[S19] C：快速排序
来源：http://dali.316326.xyz/Article/details/gtkulaazkp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.iojbl.cn/Article/details/gttacdztje.html

[S20] C：二分查找
来源：http://dali.yongpay.top/Article/details/gtfviptgra.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yangfankeji.com/Article/details/gtjulmeiwg.html

[S21] C：字符类别判断
来源：http://dali.sufxvd.cn/Article/details/gtrvbynkff.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shuidangran.top/Article/details/gtzpfapcxb.html

[S22] C：字符串转数字
来源：http://dali.jinghuilouyu.cn/Article/details/gtmvxtgvpi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sysykeji.top/Article/details/gtcnlydutv.html

[S23] C：随机数
来源：http://dali.zdqjudy.top/Article/details/gtraicfjjn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.haohaochexian.top/Article/details/gtmpbydbnw.html

[S24] C：获取本地时间
来源：http://dali.jyoumei.cn/Article/details/gtfalbmvtd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.9152youxi.cn/Article/details/gtmogowcmw.html

[S25] C：内存拷贝
来源：http://dali.pengpengdd.cyou/Article/details/gthtiamuhq.html

memcpy(dst, src, n);
来源：http://dali.yonumen.top/Article/details/gtbrhtqeti.html

[S26] C：内存清零
来源：http://dali.redwolf501.top/Article/details/gtvdcugnyp.html

memset(a, 0, sizeof a);
来源：http://dali.quarkkingdee.top/Article/details/gtrytgxzqz.html

[S27] C：定义常量
来源：http://dali.kuanghao11.cn/Article/details/gtbjxnserw.html

const double PI = 3.14159;
来源：http://dali.havefunace.top/Article/details/gttoaukwny.html

[S28] C：静态变量
来源：http://dali.zhengqikj.top/Article/details/gtsgbxkvuk.html

static int counter = 0;
来源：http://dali.wangdashe.top/Article/details/gtolwnxlgn.html

[S29] C：变参函数
来源：http://dali.xuanzx.com/Article/details/gtwidfwjiy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yonumen.top/Article/details/gtbwbgxmiw.html

[S30] C：头文件保护
来源：http://dali.shangyingyoupin.top/Article/details/gtkcskqtju.html

#ifndef X_H
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzqvbsigj.html

#define X_H
来源：http://dali.hammf.cn/Article/details/gtjvfalkdr.html

#endif
来源：http://dali.yueranfly.top/Article/details/gtoihptsmb.html

[S31] C++：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtxcdmjltv.html

#include <iostream>
来源：http://dali.zhongyouzk.top/Article/details/gteclfjdsa.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.daxiang520.top/Article/details/gtfooehfpn.html

[S32] C++：字符串
来源：http://dali.cdnleiting.top/Article/details/gtdanqhmdn.html

std::string s = "hi";  s += "!";
来源：http://dali.nanxuanxn.top/Article/details/gtyomwdkri.html

[S33] C++：vector 增删
来源：http://dali.nwbrower.top/Article/details/gttaikvxfo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cdnleiting.top/Article/details/gtsxhxwkhl.html

[S34] C++：遍历 vector
来源：http://dali.hammf.cn/Article/details/gtfpkvesyc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.316326.xyz/Article/details/gtrpszrzui.html

[S35] C++：map
来源：http://dali.fengsongda.top/Article/details/gtsvfhpnqv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gtczlwviga.html

[S36] C++：unordered_map
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvkpgnjsb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuanzx.com/Article/details/gtpogrzbnm.html

[S37] C++：set
来源：http://dali.0kj1m.cn/Article/details/gthtyianpg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtpdtoxnqf.html

[S38] C++：排序
来源：http://dali.zhixingplan.top/Article/details/gttummbmbk.html

std::sort(v.begin(), v.end());
来源：http://dali.nanxuanxn.top/Article/details/gtoduebjbj.html

[S39] C++：自定义比较器排序
来源：http://dali.ydzc1.top/Article/details/gtosbhgviu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xziqi.cn/Article/details/gtcweyubyq.html

[S40] C++：查找元素
来源：http://dali.dashuyun.cn/Article/details/gtcvyecuwh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gzhubu.top/Article/details/gtwpwvnboq.html

[S41] C++：类与构造函数
来源：http://dali.yuxming.cn/Article/details/gtgwnsqgxe.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.wangdashe.top/Article/details/gtahgkqrcq.html

[S42] C++：继承与虚函数
来源：http://dali.smart0.xyz/Article/details/gtmratkzzv.html

class B : public Base { public: void f() override {} };
来源：http://dali.ehwqpu.com/Article/details/gtsolgnoej.html

[S43] C++：智能指针
来源：http://dali.hfpthk.cn/Article/details/gtabvpowjk.html

auto p = std::make_unique<int>(5);
来源：http://dali.wangshuangyany.cn/Article/details/gtwqzvmugy.html

[S44] C++：引用传参
来源：http://dali.bjfxy.top/Article/details/gtzojblktu.html

void inc(int &x) { ++x; }
来源：http://dali.hywenlv.cn/Article/details/gtnfgjaikf.html

[S45] C++：lambda
来源：http://dali.zhoulong.xyz/Article/details/gtbkynjlct.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.feifeiyinyue.top/Article/details/gtrpsipzio.html

[S46] C++：函数模板
来源：http://dali.quarkkingdee.top/Article/details/gtnfqfowzx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.nanxinkj.top/Article/details/gtvqwastvx.html

[S47] C++：结构化绑定遍历
来源：http://dali.gaohongyu789.top/Article/details/gtowylvoiu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ppjwa.cn/Article/details/gtahkdljju.html

[S48] C++：逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gtlbyhpzwt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.quarkkingdee.top/Article/details/gtrdknlhgr.html

while (std::getline(in, line)) { }
来源：http://dali.tianlin.xyz/Article/details/gtfqfpymft.html

[S49] C++：写文件
来源：http://dali.birdmap.top/Article/details/gtueluycpb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.9152youxi.cn/Article/details/gtamhaneyb.html

[S50] C++：格式化数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gthzatxemw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gtvltvxkbm.html

[S51] C++：显式类型转换
来源：http://dali.yvedp.cn/Article/details/gtzebdppqe.html

static_cast<double>(a) / b
来源：http://dali.cheryme.top/Article/details/gtryhkjiuk.html

[S52] C++：const 与 noexcept
来源：http://dali.pengpengdd.cyou/Article/details/gtvetcfkcw.html

int size() const noexcept { return n_; }
来源：http://dali.aibaodan.cn/Article/details/gtembsgzvy.html

[S53] C++：移动语义
来源：http://dali.fzhhl.top/Article/details/gtbkiymqdf.html

std::vector<int> w = std::move(v);
来源：http://dali.mhx1999.top/Article/details/gtyzaezxjo.html

[S54] C++：异常处理
来源：http://dali.zhoulong.xyz/Article/details/gtjtllghpp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.feifeiyinyue.top/Article/details/gtqqpmxkeo.html

[S55] C++：结构化绑定
来源：http://dali.jiagoushi.top/Article/details/gtojtyiyrb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.kuanghao11.cn/Article/details/gttwouoogk.html

[S56] C++：optional
来源：http://dali.jinghuilouyu.cn/Article/details/gtovgkhkrn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hongshengwenyu.top/Article/details/gtotfqlsaw.html

[S57] C++：编译期常量
来源：http://dali.xziqi.cn/Article/details/gttqlsmict.html

constexpr int N = 10;
来源：http://dali.yj20258.top/Article/details/gtrklzxtsk.html

[S58] C++：命名空间
来源：http://dali.jlsjyb.cn/Article/details/gtmfhylmwp.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhongyouzk.top/Article/details/gtqlvtwdgt.html

[S59] C++：静态断言
来源：http://dali.redwolf501.top/Article/details/gtwfsxwhkc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.meibo888.top/Article/details/gtxokmnche.html

[S60] C++：遍历并删除元素
来源：http://dali.dianchejie.cn/Article/details/gterakosdt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.meibo888.top/Article/details/gtnxomuznf.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtbtwdpsed.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.redwolf501.top/Article/details/gtfetxiely.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtewemjkul.html

[T01] Kotlin：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gthnvbhaav.html

println("Hello")
来源：http://dali.shanyushiyangtech.top/Article/details/gtafbiydoi.html

[T02] Kotlin：变量
来源：http://dali.snrcjt.cn/Article/details/gtiizgxntx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tian-w.cn/Article/details/gthsupeatx.html

[T03] Kotlin：字符串模板
来源：http://dali.yonumen.top/Article/details/gtzxqepsyq.html

"值: $b"
来源：http://dali.yangfankeji.com/Article/details/gtooabceik.html

[T04] Kotlin：空安全
来源：http://dali.daxiang520.top/Article/details/gtnfrtssmt.html

val n: String? = null;  n?.length
来源：http://dali.yanxiufei.cn/Article/details/gteujrnhan.html

[T05] Kotlin：when 表达式
来源：http://dali.xuetiantiany.cn/Article/details/gtfzshlewk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gotoacloud.top/Article/details/gtthvxwrfo.html

[T06] Kotlin：集合映射
来源：http://dali.gzhubu.top/Article/details/gtfzmccexx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtfwxltsuk.html

[T07] Kotlin：集合过滤
来源：http://dali.nanxuanxn.top/Article/details/gtpwvzzckc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ybcxt.top/Article/details/gtlsvgppur.html

[T08] Kotlin：数据类
来源：http://dali.hammf.cn/Article/details/gtyunnvfdn.html

data class User(val name: String, val age: Int)
来源：http://dali.chenzaomai.com/Article/details/gtpvaojpzt.html

[T09] Kotlin：扩展函数
来源：http://dali.hongshengwenyu.top/Article/details/gtzkstxpfj.html

fun String.exclaim() = this + "!"
来源：http://dali.hysaishi.cn/Article/details/gtwveyyffc.html

[T10] Kotlin：默认参数
来源：http://dali.ydzc1.top/Article/details/gtcjeeqsjf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yongpay.top/Article/details/gtfdhmlicg.html

[T11] Kotlin：协程
来源：http://dali.tianlin.xyz/Article/details/gtbcnlwjxd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cashguo.top/Article/details/gtrbgoowvj.html

[T12] Kotlin：解构声明
来源：http://dali.yangfankeji.com/Article/details/gtyhebaayo.html

val (a, b) = Pair(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gtnnxdhbhn.html

[T13] Kotlin：只读 Map
来源：http://dali.ydzc1.top/Article/details/gtrnotptxp.html

val m = mapOf("a" to 1)
来源：http://dali.havefunace.top/Article/details/gtttrcaxjb.html

[T14] Kotlin：循环
来源：http://dali.cashguo.top/Article/details/gtxaafmwhj.html

for (i in 1..10) println(i)
来源：http://dali.snrcjt.cn/Article/details/gtwazcppoi.html

[T15] Kotlin：接口
来源：http://dali.hfpthk.cn/Article/details/gtvhbkfvos.html

interface Shape { fun area(): Double }
来源：http://dali.nanxuanxn.top/Article/details/gtpzlxccnb.html

[T16] Swift：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtnvmbamiu.html

print("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsgwhoxkz.html

[T17] Swift：变量与常量
来源：http://dali.daria6918.cn/Article/details/gtrbbhyezc.html

var a = 1;  let b = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtqozoslwk.html

[T18] Swift：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gtcpymosel.html

"值: \(b)"
来源：http://dali.tanke756.top/Article/details/gtaqagjxtf.html

[T19] Swift：可选绑定
来源：http://dali.ydzc1.top/Article/details/gtnlxelqqb.html

if let n = opt { print(n) }
来源：http://dali.svipenyu.cn/Article/details/gtolxewarr.html

[T20] Swift：数组操作
来源：http://dali.zhengqikj.top/Article/details/gtarkykdei.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xinyue.icu/Article/details/gtymrrdehs.html

[T21] Swift：遍历
来源：http://dali.shzxlz.cn/Article/details/gtsqeuxkfs.html

for x in a { print(x) }
来源：http://dali.tian-w.cn/Article/details/gtmtavvjcg.html

[T22] Swift：字典
来源：http://dali.quarkkingdee.top/Article/details/gtreetpqjy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.snrcjt.cn/Article/details/gtzgrvawes.html

[T23] Swift：函数
来源：http://dali.vqdsnc.cn/Article/details/gtvaqqwpbt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xziqi.cn/Article/details/gtibxkhtyf.html

[T24] Swift：闭包
来源：http://dali.dianchejie.cn/Article/details/gtjszxasvx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yueranfly.top/Article/details/gthgsfrswx.html

[T25] Swift：结构体
来源：http://dali.dianchejie.cn/Article/details/gtqosgrmrk.html

struct P { var x: Int }
来源：http://dali.pengpengdd.cyou/Article/details/gtnjppzsdh.html

[T26] Swift：类与重写
来源：http://dali.zhiwuduotai.top/Article/details/gtjwjgllgo.html

class A: Base { override func f() {} }
来源：http://dali.aibaodan.cn/Article/details/gtdpwuxzgb.html

[T27] Swift：错误处理
来源：http://dali.tanke756.top/Article/details/gtrquqitti.html

do { try f() } catch { print(error) }
来源：http://dali.sxryk.cn/Article/details/gtfoypytht.html

[T28] Swift：枚举
来源：http://dali.chenzaomai.com/Article/details/gtpzygbuzb.html

enum Color { case red, green }
来源：http://dali.yuxming.cn/Article/details/gtmjjhoyzq.html

[T29] Swift：guard 提前返回
来源：http://dali.yanxiufei.cn/Article/details/gtbjahnlwd.html

guard let x = opt else { return }
来源：http://dali.zhiwuduotai.top/Article/details/gtgdxztksm.html

[T30] Swift：协议
来源：http://dali.zhaomingkeji.xyz/Article/details/gthswmslgm.html

protocol Shape { func area() -> Double }
来源：http://dali.shangyingyoupin.top/Article/details/gtrrshfyxz.html

[T31] Lua：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtrebvjwez.html

print("Hello")
来源：http://dali.shanyushiyangtech.top/Article/details/gtatxbsaqx.html

[T32] Lua：局部变量
来源：http://dali.jqgufenzy.top/Article/details/gtkqvoqczl.html

local a = 1
来源：http://dali.hnqzz.top/Article/details/gtkpswvzlq.html

[T33] Lua：表（数组）
来源：http://dali.haohaochexian.top/Article/details/gtbzdcbwxb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yanxiufei.cn/Article/details/gtbikhbhae.html

[T34] Lua：遍历表
来源：http://dali.daria6918.cn/Article/details/gtsvspidzy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.svipenyu.cn/Article/details/gtpyaujyaa.html

[T35] Lua：字典表
来源：http://dali.fengsongda.top/Article/details/gteougmtui.html

local d = { a = 1 };  d.b = 2
来源：http://dali.0kj1m.cn/Article/details/gthlsliesr.html

[T36] Lua：函数
来源：http://dali.jianghu66.top/Article/details/gtsmeuqgvd.html

function add(a, b) return a + b end
来源：http://dali.hongshengwenyu.top/Article/details/gtbpjdrawl.html

[T37] Lua：字符串拼接
来源：http://dali.fzhhl.top/Article/details/gtyqaknyya.html

"a" .. "b"
来源：http://dali.xylfe.cn/Article/details/gtqwaupdis.html

[T38] Lua：条件
来源：http://dali.quarkkingdee.top/Article/details/gtmqfbwdxm.html

if x > 0 then print("正") end
来源：http://dali.jyoumei.cn/Article/details/gtvpebragj.html

[T39] Lua：模式匹配
来源：http://dali.dianchejie.cn/Article/details/gtoqarzxhh.html

string.find(s, "%d+")
来源：http://dali.ppjwa.cn/Article/details/gtmsygzeyk.html

[T40] Lua：元表
来源：http://dali.quarkkingdee.top/Article/details/gtsuwltijf.html

setmetatable({}, { __index = base })
来源：http://dali.cheryme.top/Article/details/gtzhgcexqz.html

[T41] Perl：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrwdihfkp.html

print "Hello\n";
来源：http://dali.sxryk.cn/Article/details/gtnljxgjoz.html

[T42] Perl：变量类型
来源：http://dali.9152youxi.cn/Article/details/gtaddsdgdy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cucudq.cn/Article/details/gtondnpqim.html

[T43] Perl：字符串插值
来源：http://dali.cheryme.top/Article/details/gthqssatne.html

"值: $a"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrirwjfgf.html

[T44] Perl：条件
来源：http://dali.zycfv.cn/Article/details/gtidaecivd.html

if ($a > 0) { print "正"; }
来源：http://dali.chenzaomai.com/Article/details/gtoikktsol.html

[T45] Perl：数组遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtvxwdmuiv.html

for my $x (@arr) { print $x; }
来源：http://dali.hywenlv.cn/Article/details/gtkylweitj.html

[T46] Perl：哈希操作
来源：http://dali.kuanghao11.cn/Article/details/gtguxxdamu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.aibaodan.cn/Article/details/gtairnvqqr.html

[T47] Perl：正则捕获
来源：http://dali.cucudq.cn/Article/details/gtbqlqxhee.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ivvv.top/Article/details/gtvaiqrlab.html

[T48] Perl：正则替换
来源：http://dali.jinqigufen.top/Article/details/gtioflsunw.html

$s =~ s/old/new/g;
来源：http://dali.zhiwuduotai.top/Article/details/gtigrgqcoa.html

[T49] Perl：函数
来源：http://dali.zhixingplan.top/Article/details/gtqisdvnoe.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gtzguocyrt.html

[T50] Perl：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtmccdpbtk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yuxming.cn/Article/details/gtpkrxlcoo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhoulong.xyz/Article/details/gtfbzqubpg.html

[T51] Scala：Hello World
来源：http://dali.redwolf501.top/Article/details/gtznrybjut.html

println("Hello")
来源：http://dali.9152youxi.cn/Article/details/gtmlazykia.html

[T52] Scala：变量
来源：http://dali.jiagoushi.top/Article/details/gtarhtvwls.html

val a = 1;  var b = 2
来源：http://dali.gaohongyu789.top/Article/details/gtykpjqepz.html

[T53] Scala：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gthcbeztga.html

s"值: $b"
来源：http://dali.shuidangran.top/Article/details/gtkuvrkdvz.html

[T54] Scala：集合映射
来源：http://dali.quarkkingdee.top/Article/details/gtufvpnwbn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sxryk.cn/Article/details/gtamibjngc.html

[T55] Scala：集合过滤
来源：http://dali.hnqzz.top/Article/details/gtrzsnmaxf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.pycfn.com/Article/details/gtvuksnqjm.html

[T56] Scala：样例类
来源：http://dali.shzxlz.cn/Article/details/gtepcbvuew.html

case class User(name: String, age: Int)
来源：http://dali.hnxiangtu.top/Article/details/gtxtpufkoc.html

[T57] Scala：模式匹配
来源：http://dali.yangfankeji.com/Article/details/gtkdtdhhvb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.sweek.top/Article/details/gtfskocbyc.html

[T58] Scala：函数定义
来源：http://dali.svipenyu.cn/Article/details/gtvoeymyse.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hongshengwenyu.top/Article/details/gtiqezmjsb.html

[T59] Scala：循环
来源：http://dali.tianlin.xyz/Article/details/gtsphkgikf.html

for (i <- 1 to 10) println(i)
来源：http://dali.chenlongwang.top/Article/details/gtinoklntz.html

[T60] Scala：折叠
来源：http://dali.xuetiantiany.cn/Article/details/gtwdfmespq.html


<!-- 参考信息 -->