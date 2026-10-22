代发 wailian999

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.quarkkingdee.top/Article/details/gtpfyzsqsm.html

[R52] 统计行数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtthpzxpck.html

wc -l a.txt
来源：http://dali.xinyue.icu/Article/details/gtpmdyycbp.html

[R53] 查看文件头与实时尾
来源：http://dali.jiagoushi.top/Article/details/gtzswytcis.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hnqzz.top/Article/details/gtdsdoptfk.html

[R54] 比较两个文件
来源：http://dali.redwolf501.top/Article/details/gtvlfzwaiv.html

diff a.txt b.txt
来源：http://dali.ydzc1.top/Article/details/gtrrwtafeu.html

[R55] 压缩与解压
来源：http://dali.ydzc1.top/Article/details/gtexzevrbq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xuanzx.com/Article/details/gtpijeghzn.html

[R56] 远程拷贝
来源：http://dali.cucudq.cn/Article/details/gtsrxfuxoj.html

scp file user@host:/path/
来源：http://dali.ydzc1.top/Article/details/gtlacszuhm.html

[R57] 远程执行命令
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjdgiiaxx.html

ssh user@host 'uptime'
来源：http://dali.yuxming.cn/Article/details/gtfdncynno.html

[R58] 下载文件
来源：http://dali.sweek.top/Article/details/gtijcolnnh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinqigufen.top/Article/details/gtbugpjatg.html

[R59] 发 POST JSON
来源：http://dali.jinqigfzy.top/Article/details/gtejzqbemw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jiagoushi.top/Article/details/gtipzndgom.html

[R60] 只看 HTTP 状态码
来源：http://dali.wangshuangyany.cn/Article/details/gtdndwkznr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sysykeji.top/Article/details/gtworcthqe.html

[R61] 磁盘占用
来源：http://dali.haohaochexian.top/Article/details/gtariqryxm.html

df -h;  du -sh *
来源：http://dali.shanyushiyangtech.top/Article/details/gteemruesg.html

[R62] 找最占空间的文件
来源：http://dali.yuanzhike.top/Article/details/gtblhlfbtc.html

du -ah . | sort -rh | head -10
来源：http://dali.quarkkingdee.top/Article/details/gtwopmbafk.html

[R63] 内存与进程
来源：http://dali.jinqigufen.top/Article/details/gtmumenkhw.html

free -h;  ps aux | grep nginx
来源：http://dali.ybcxt.top/Article/details/gtdwdxcmsb.html

[R64] 结束进程
来源：http://dali.jyoumei.cn/Article/details/gtrwzzgxer.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hongshengwenyu.top/Article/details/gtemvhymhf.html

[R65] 查看端口占用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtldcepknt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinqigfzy.top/Article/details/gttaxdcoep.html

[R66] 定时任务
来源：http://dali.yvedp.cn/Article/details/gtirftsvfz.html

crontab -e;  crontab -l
来源：http://dali.yuxming.cn/Article/details/gthayzqtne.html

[R67] 生成随机十六进制串
来源：http://dali.quarkkingdee.top/Article/details/gtcwerkuus.html

openssl rand -hex 16
来源：http://dali.ybcxt.top/Article/details/gtshhuqsay.html

[R68] 计算文件校验值
来源：http://dali.vqdsnc.cn/Article/details/gtqmtvqgcm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj20258.top/Article/details/gtiuideauz.html

[R69] 生成随机密码
来源：http://dali.fzhhl.top/Article/details/gteyhczrek.html

head -c 16 /dev/urandom | base64
来源：http://dali.snrcjt.cn/Article/details/gtdmnjvxpr.html

[R70] 时间戳与互转
来源：http://dali.jinghuilouyu.cn/Article/details/gtgvsqumrj.html

date +%s;  date -d @1700000000
来源：http://dali.bjfxy.top/Article/details/gtsetdobap.html

[R71] 日期格式化
来源：http://dali.daxiang520.top/Article/details/gttwdrehff.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cashguo.top/Article/details/gthswxfztb.html

[R72] 等待端口就绪
来源：http://dali.zycfv.cn/Article/details/gtctrpzzgp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jqgufenzy.top/Article/details/gtkgfmzowq.html

[R73] 分割大日志
来源：http://dali.zhoulong.xyz/Article/details/gtvmmpiqna.html

split -l 1000 big.log part_
来源：http://dali.dashuyun.cn/Article/details/gtigizmchw.html

[R74] 批量重命名
来源：http://dali.guannengcc.top/Article/details/gthtkgcsrv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.snrcjt.cn/Article/details/gtuuptluve.html

[R75] 导出环境变量
来源：http://dali.ppjwa.cn/Article/details/gtcatxyvms.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcygmeinv.html

[R76] 使用临时文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpdbmhuym.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenjidiqi.icu/Article/details/gtfpaqeslp.html

[R77] 读取用户输入
来源：http://dali.jinqigufen.top/Article/details/gtrenwhput.html

read -rp "请输入: " ans
来源：http://dali.cucudq.cn/Article/details/gtqjfdysaa.html

[R78] 交互式菜单
来源：http://dali.jinqigfzy.top/Article/details/gtwkrhntfr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nwbrower.top/Article/details/gtatlqzxva.html

[R79] 解析命令行选项
来源：http://dali.yueranfly.top/Article/details/gtgrzcnwpy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhiwuduotai.top/Article/details/gtwduqckrm.html

[R80] 查看脚本执行耗时
来源：http://dali.ywan-chungtsiang.top/Article/details/gtradbttkb.html

time ./run.sh
来源：http://dali.yuxming.cn/Article/details/gtrbxhwgrt.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtdhpsqcym.html

S. C / C++ 专题
来源：http://dali.sweek.top/Article/details/gtlsfbrlkn.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtfdlrorwa.html

[S01] C：Hello World
来源：http://dali.cashguo.top/Article/details/gtvyaiyzvi.html

#include <stdio.h>
来源：http://dali.ppjwa.cn/Article/details/gtzzqdorjf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xuanzx.com/Article/details/gttiolqkfh.html

[S02] C：变量与格式化输出
来源：http://dali.zycfv.cn/Article/details/gtejglrhes.html

int a = 10; printf("%d\n", a);
来源：http://dali.smart0.xyz/Article/details/gtwkifjijt.html

[S03] C：读入整数
来源：http://dali.bjfxy.top/Article/details/gtxbabkrgi.html

int x; scanf("%d", &x);
来源：http://dali.hnxiangtu.top/Article/details/gtehuzuntu.html

[S04] C：字符串复制
来源：http://dali.chenjidiqi.icu/Article/details/gtoetclzxc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cucudq.cn/Article/details/gtdfkmhkij.html

[S05] C：字符串长度
来源：http://dali.nanxinkj.top/Article/details/gtdgboclid.html

strlen(s)
来源：http://dali.snrcjt.cn/Article/details/gttucpyvjk.html

[S06] C：字符串比较
来源：http://dali.sysykeji.top/Article/details/gtxxpsxytm.html

strcmp(a, b) == 0
来源：http://dali.yj20258888.top/Article/details/gtpjumemdo.html

[S07] C：数组遍历求和
来源：http://dali.hysaishi.cn/Article/details/gtsmzztkcp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.svipenyu.cn/Article/details/gtdpanbdkj.html

[S08] C：动态内存分配与释放
来源：http://dali.nanxuanxn.top/Article/details/gtnvuvjbsq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhoulong.xyz/Article/details/gtabrsknrq.html

[S09] C：结构体定义与初始化
来源：http://dali.shangyingyoupin.top/Article/details/gtanbzpfje.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.havefunace.top/Article/details/gtsrnhivyb.html

[S10] C：指针与解引用
来源：http://dali.jiagoushi.top/Article/details/gtzokmxgvh.html

int *p = &a;  *p = 5;
来源：http://dali.aibaodan.cn/Article/details/gtfdkeowwn.html

[S11] C：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxwyfxiab.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.snrcjt.cn/Article/details/gtozqcjwwn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ppjwa.cn/Article/details/gttsllknmc.html

fclose(f);
来源：http://dali.tian-w.cn/Article/details/gtnntbroyc.html

[S12] C：写文件
来源：http://dali.yj20258888.top/Article/details/gtucardakq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gotoacloud.top/Article/details/gtunhgkkjf.html

[S13] C：宏定义
来源：http://dali.quarkkingdee.top/Article/details/gtbxrswiwz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xylfe.cn/Article/details/gtkezbkytv.html

[S14] C：枚举
来源：http://dali.guowangkeji.top/Article/details/gtduvitfqg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzkshxrbc.html

[S15] C：类型转换
来源：http://dali.jyoumei.cn/Article/details/gtfswlpuqm.html

(double) a / b
来源：http://dali.nanxinkj.top/Article/details/gtrvlnfvsk.html

[S16] C：位操作置位
来源：http://dali.chenjidiqi.icu/Article/details/gtqffxciop.html

x |= (1 << 3);
来源：http://dali.xylfe.cn/Article/details/gtqnuohrpu.html

[S17] C：安全拼接字符串
来源：http://dali.xziqi.cn/Article/details/gtkmsnwyoj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yj20258.top/Article/details/gtkvzebzlv.html

[S18] C：命令行参数
来源：http://dali.yueranfly.top/Article/details/gtznrbtzfs.html

int main(int argc, char **argv)
来源：http://dali.shzxlz.cn/Article/details/gthebdlbgp.html

[S19] C：快速排序
来源：http://dali.cashguo.top/Article/details/gtupxjrqva.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.iojbl.cn/Article/details/gtjjwhcdrd.html

[S20] C：二分查找
来源：http://dali.sysykeji.top/Article/details/gtnqgpcjkh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gtpevomqsw.html

[S21] C：字符类别判断
来源：http://dali.aizwys.cn/Article/details/gtzqppqixf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.bjfxy.top/Article/details/gtpzmonpgk.html

[S22] C：字符串转数字
来源：http://dali.guannengcc.top/Article/details/gtbiepclfc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sysykeji.top/Article/details/gtrpbnuzlh.html

[S23] C：随机数
来源：http://dali.haohaochexian.top/Article/details/gtnftkvhkt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hysaishi.cn/Article/details/gtsbzezjtq.html

[S24] C：获取本地时间
来源：http://dali.316326.xyz/Article/details/gtnfinzcmj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yonumen.top/Article/details/gtjxwuulyk.html

[S25] C：内存拷贝
来源：http://dali.9152youxi.cn/Article/details/gtygnwmywk.html

memcpy(dst, src, n);
来源：http://dali.nanxinkj.top/Article/details/gtlgpubvbm.html

[S26] C：内存清零
来源：http://dali.tian-w.cn/Article/details/gtpjkpmctl.html

memset(a, 0, sizeof a);
来源：http://dali.zycfv.cn/Article/details/gtsiaphgle.html

[S27] C：定义常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjstiuyqd.html

const double PI = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtxejixrld.html

[S28] C：静态变量
来源：http://dali.yuanzhike.top/Article/details/gtulhueglu.html

static int counter = 0;
来源：http://dali.hysaishi.cn/Article/details/gtkkwekwox.html

[S29] C：变参函数
来源：http://dali.sufxvd.cn/Article/details/gtrgbernni.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.vqdsnc.cn/Article/details/gtxdgtsrxr.html

[S30] C：头文件保护
来源：http://dali.jiagoushi.top/Article/details/gtvvpsmwpt.html

#ifndef X_H
来源：http://dali.cdnleiting.top/Article/details/gteotakdns.html

#define X_H
来源：http://dali.yanxiufei.cn/Article/details/gthazlghcs.html

#endif
来源：http://dali.guowangkeji.top/Article/details/gtcrxfnclr.html

[S31] C++：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtfddwmtwd.html

#include <iostream>
来源：http://dali.jianghu66.top/Article/details/gtbxttzgjk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.aizwys.cn/Article/details/gtaeuernos.html

[S32] C++：字符串
来源：http://dali.snrcjt.cn/Article/details/gtrrkwffxo.html

std::string s = "hi";  s += "!";
来源：http://dali.nwbrower.top/Article/details/gtlgsaherz.html

[S33] C++：vector 增删
来源：http://dali.zycfv.cn/Article/details/gttmpmtare.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.fzhhl.top/Article/details/gtnqyiitve.html

[S34] C++：遍历 vector
来源：http://dali.0kj1m.cn/Article/details/gtkyellhhq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.birdmap.top/Article/details/gtgkmhbldu.html

[S35] C++：map
来源：http://dali.yongpay.top/Article/details/gttwyawmfk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.havefunace.top/Article/details/gtqskwlabo.html

[S36] C++：unordered_map
来源：http://dali.redwolf501.top/Article/details/gtuzgnunrx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gtdzepiidz.html

[S37] C++：set
来源：http://dali.xuanzx.com/Article/details/gtkeyfklbf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhengqikj.top/Article/details/gtcnzqiema.html

[S38] C++：排序
来源：http://dali.xylfe.cn/Article/details/gtsnwlbjcq.html

std::sort(v.begin(), v.end());
来源：http://dali.mhx1999.top/Article/details/gtauivpakg.html

[S39] C++：自定义比较器排序
来源：http://dali.9152youxi.cn/Article/details/gtjjlqxxtm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yuxming.cn/Article/details/gtozbleabs.html

[S40] C++：查找元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvvcejks.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.fengsongda.top/Article/details/gtkpresbtz.html

[S41] C++：类与构造函数
来源：http://dali.wangdashe.top/Article/details/gtttimgvrb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.daxiang520.top/Article/details/gtklhrpvdd.html

[S42] C++：继承与虚函数
来源：http://dali.shangyingyoupin.top/Article/details/gtisnuknyn.html

class B : public Base { public: void f() override {} };
来源：http://dali.daxiang520.top/Article/details/gtdvevutpr.html

[S43] C++：智能指针
来源：http://dali.zhaomingkeji.xyz/Article/details/gtitxwwmxm.html

auto p = std::make_unique<int>(5);
来源：http://dali.fengsongda.top/Article/details/gtuglwvjnc.html

[S44] C++：引用传参
来源：http://dali.hysaishi.cn/Article/details/gtizzwizcu.html

void inc(int &x) { ++x; }
来源：http://dali.jiagoushi.top/Article/details/gtyaneakby.html

[S45] C++：lambda
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwaiziszx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.dashuyun.cn/Article/details/gtanduruyp.html

[S46] C++：函数模板
来源：http://dali.ppjwa.cn/Article/details/gttkrhabak.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xuanzx.com/Article/details/gtxuoltdyu.html

[S47] C++：结构化绑定遍历
来源：http://dali.jqgufenzy.top/Article/details/gtajwcawyb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xinyue.icu/Article/details/gtgdwxkuxm.html

[S48] C++：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gtohswarig.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sysykeji.top/Article/details/gttqvchlyt.html

while (std::getline(in, line)) { }
来源：http://dali.cheryme.top/Article/details/gtvirwrcwz.html

[S49] C++：写文件
来源：http://dali.shuidangran.top/Article/details/gteqmfqbfm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gtrpmhuxee.html

[S50] C++：格式化数字
来源：http://dali.gzhubu.top/Article/details/gtrdrahubh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gtbotflrsi.html

[S51] C++：显式类型转换
来源：http://dali.meibo888.top/Article/details/gtpasbajyc.html

static_cast<double>(a) / b
来源：http://dali.xziqi.cn/Article/details/gtkieqtqki.html

[S52] C++：const 与 noexcept
来源：http://dali.zycfv.cn/Article/details/gtzeqjmfev.html

int size() const noexcept { return n_; }
来源：http://dali.jinqigfzy.top/Article/details/gtmxqsqlem.html

[S53] C++：移动语义
来源：http://dali.fengsongda.top/Article/details/gtuvwzlzeq.html

std::vector<int> w = std::move(v);
来源：http://dali.tanke756.top/Article/details/gtcnueqqjb.html

[S54] C++：异常处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxfezkmpx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shangyingyoupin.top/Article/details/gtxvudcysm.html

[S55] C++：结构化绑定
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrlhegmxf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.guannengcc.top/Article/details/gthmvnbrus.html

[S56] C++：optional
来源：http://dali.zhengqikj.top/Article/details/gtckyleuhn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zdqjudy.top/Article/details/gtggqpkkgr.html

[S57] C++：编译期常量
来源：http://dali.cashguo.top/Article/details/gtvihuszsl.html

constexpr int N = 10;
来源：http://dali.zdqjudy.top/Article/details/gtvelbnuxm.html

[S58] C++：命名空间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtayizewog.html

namespace ns { int f() { return 1; } }
来源：http://dali.aizwys.cn/Article/details/gtznehyjez.html

[S59] C++：静态断言
来源：http://dali.wangdashe.top/Article/details/gtolebclas.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ehwqpu.com/Article/details/gteslhopvp.html

[S60] C++：遍历并删除元素
来源：http://dali.dianchejie.cn/Article/details/gtvzrqcgzc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yueranfly.top/Article/details/gtkjnwijod.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtdhiyontr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenlongwang.top/Article/details/gtcqecebwu.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtuhnwwzjx.html

[T01] Kotlin：Hello World
来源：http://dali.xylfe.cn/Article/details/gtekqjttnx.html

println("Hello")
来源：http://dali.guowangkeji.top/Article/details/gtunrcpgyx.html

[T02] Kotlin：变量
来源：http://dali.zhixingplan.top/Article/details/gtnwtfktqo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.0kj1m.cn/Article/details/gtgeqkflnq.html

[T03] Kotlin：字符串模板
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoscspmcg.html

"值: $b"
来源：http://dali.zhongyouzk.top/Article/details/gtnxmifevl.html

[T04] Kotlin：空安全
来源：http://dali.chenzaomai.com/Article/details/gtxbrqdiri.html

val n: String? = null;  n?.length
来源：http://dali.hammf.cn/Article/details/gtlleqjelk.html

[T05] Kotlin：when 表达式
来源：http://dali.0kj1m.cn/Article/details/gtwzlkqmjm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gotoacloud.top/Article/details/gtdqvpamzi.html

[T06] Kotlin：集合映射
来源：http://dali.jinqigfzy.top/Article/details/gtnntkaivf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinqigufen.top/Article/details/gtratdrete.html

[T07] Kotlin：集合过滤
来源：http://dali.svipenyu.cn/Article/details/gtghfuutwp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xuetiantiany.cn/Article/details/gtkqnzuzua.html

[T08] Kotlin：数据类
来源：http://dali.yj20258.top/Article/details/gtnsdjiwzv.html

data class User(val name: String, val age: Int)
来源：http://dali.havefunace.top/Article/details/gtfjpxuwqr.html

[T09] Kotlin：扩展函数
来源：http://dali.fengsongda.top/Article/details/gtnisjgevi.html

fun String.exclaim() = this + "!"
来源：http://dali.c1oappe.top/Article/details/gtmxkwfmum.html

[T10] Kotlin：默认参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxvnwwls.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sysykeji.top/Article/details/gtxrwswwnz.html

[T11] Kotlin：协程
来源：http://dali.guannengcc.top/Article/details/gtumojsvhk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hywenlv.cn/Article/details/gtxxaiivdn.html

[T12] Kotlin：解构声明
来源：http://dali.cheryme.top/Article/details/gtlkgiruts.html

val (a, b) = Pair(1, 2)
来源：http://dali.jqgufenzy.top/Article/details/gtdsznmgdw.html

[T13] Kotlin：只读 Map
来源：http://dali.hysaishi.cn/Article/details/gtfwxxtjjt.html

val m = mapOf("a" to 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtmkkoyqyp.html

[T14] Kotlin：循环
来源：http://dali.gotoacloud.top/Article/details/gtgsyusjwr.html

for (i in 1..10) println(i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtedxzdvwa.html

[T15] Kotlin：接口
来源：http://dali.sysykeji.top/Article/details/gthfxmglgr.html

interface Shape { fun area(): Double }
来源：http://dali.yj202588.top/Article/details/gtztfemfgo.html

[T16] Swift：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtavtjgsmv.html

print("Hello")
来源：http://dali.birdmap.top/Article/details/gtfcxkfhic.html

[T17] Swift：变量与常量
来源：http://dali.xuetiantiany.cn/Article/details/gtlfmxraad.html

var a = 1;  let b = 2
来源：http://dali.havefunace.top/Article/details/gtwrrnhpvs.html

[T18] Swift：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gtceopzglx.html

"值: \(b)"
来源：http://dali.gaohongyu789.top/Article/details/gtyxcioixl.html

[T19] Swift：可选绑定
来源：http://dali.cheryme.top/Article/details/gtttgjaxeo.html

if let n = opt { print(n) }
来源：http://dali.haohaochexian.top/Article/details/gtltrpruoj.html

[T20] Swift：数组操作
来源：http://dali.ehwqpu.com/Article/details/gthysbjnmm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.snrcjt.cn/Article/details/gtewdtczlv.html

[T21] Swift：遍历
来源：http://dali.cdnleiting.top/Article/details/gttfidsyty.html

for x in a { print(x) }
来源：http://dali.zhixingplan.top/Article/details/gtnknpimoq.html

[T22] Swift：字典
来源：http://dali.xuanzx.com/Article/details/gtdtpihfnl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yvedp.cn/Article/details/gtfwxcuyeb.html

[T23] Swift：函数
来源：http://dali.jinqigufen.top/Article/details/gtecmytzza.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.snrcjt.cn/Article/details/gtedxnpaxu.html

[T24] Swift：闭包
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjkyzkdfo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zycfv.cn/Article/details/gtubutzzii.html

[T25] Swift：结构体
来源：http://dali.fengsongda.top/Article/details/gtgyyaefmg.html

struct P { var x: Int }
来源：http://dali.nwbrower.top/Article/details/gteraylsqc.html

[T26] Swift：类与重写
来源：http://dali.aizwys.cn/Article/details/gtfwrmsbop.html

class A: Base { override func f() {} }
来源：http://dali.chenzaomai.com/Article/details/gtkesstpih.html

[T27] Swift：错误处理
来源：http://dali.0kj1m.cn/Article/details/gtpxoozzro.html

do { try f() } catch { print(error) }
来源：http://dali.havefunace.top/Article/details/gtfmqhrdqv.html

[T28] Swift：枚举
来源：http://dali.haohaochexian.top/Article/details/gtyllhfwth.html

enum Color { case red, green }
来源：http://dali.tanke756.top/Article/details/gtzajdncns.html

[T29] Swift：guard 提前返回
来源：http://dali.iojbl.cn/Article/details/gtbzmtaled.html

guard let x = opt else { return }
来源：http://dali.jlsjyb.cn/Article/details/gtlkdetuyx.html

[T30] Swift：协议
来源：http://dali.xinyue.icu/Article/details/gttpydttbb.html

protocol Shape { func area() -> Double }
来源：http://dali.cqqwz.cn/Article/details/gtqbdurens.html

[T31] Lua：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtituuhkjy.html

print("Hello")
来源：http://dali.aibaodan.cn/Article/details/gtesroywnb.html

[T32] Lua：局部变量
来源：http://dali.jinqigfzy.top/Article/details/gtzfotgamn.html

local a = 1
来源：http://dali.svipenyu.cn/Article/details/gtoetlrjlt.html

[T33] Lua：表（数组）
来源：http://dali.bjfxy.top/Article/details/gtgvvevggk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shzxlz.cn/Article/details/gtuovhmbbz.html

[T34] Lua：遍历表
来源：http://dali.zhoulong.xyz/Article/details/gtiluoprdn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.guowangkeji.top/Article/details/gttslgvbev.html

[T35] Lua：字典表
来源：http://dali.xinyue.icu/Article/details/gtvajbhkwy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhixingplan.top/Article/details/gtilexumdj.html

[T36] Lua：函数
来源：http://dali.hnqzz.top/Article/details/gtgnlabifo.html

function add(a, b) return a + b end
来源：http://dali.yj20258888.top/Article/details/gtdkngcexq.html

[T37] Lua：字符串拼接
来源：http://dali.smart0.xyz/Article/details/gtxikfodqp.html

"a" .. "b"
来源：http://dali.jinghuilouyu.cn/Article/details/gtwtnqiwfs.html

[T38] Lua：条件
来源：http://dali.svipenyu.cn/Article/details/gtyxakztxh.html

if x > 0 then print("正") end
来源：http://dali.tian-w.cn/Article/details/gtzaygrgnd.html

[T39] Lua：模式匹配
来源：http://dali.xylfe.cn/Article/details/gtiskqsmcv.html

string.find(s, "%d+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvyuvxhux.html

[T40] Lua：元表
来源：http://dali.zhaomingkeji.xyz/Article/details/gthcocgrkn.html

setmetatable({}, { __index = base })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmoswadbw.html

[T41] Perl：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtibsaksfe.html

print "Hello\n";
来源：http://dali.vqdsnc.cn/Article/details/gtkfqmnduh.html

[T42] Perl：变量类型
来源：http://dali.redwolf501.top/Article/details/gthwarphca.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jqgufenzy.top/Article/details/gtikltdcmg.html

[T43] Perl：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gtktyrniro.html

"值: $a"
来源：http://dali.ivvv.top/Article/details/gtzxtabenq.html

[T44] Perl：条件
来源：http://dali.mhx1999.top/Article/details/gtpwugctgr.html

if ($a > 0) { print "正"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtzfegguvf.html

[T45] Perl：数组遍历
来源：http://dali.ppjwa.cn/Article/details/gtnvpnyjtx.html

for my $x (@arr) { print $x; }
来源：http://dali.aibaodan.cn/Article/details/gtculbatii.html

[T46] Perl：哈希操作
来源：http://dali.hnxiangtu.top/Article/details/gtdimzgfhn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jyoumei.cn/Article/details/gtlofgmyoo.html

[T47] Perl：正则捕获
来源：http://dali.jianghu66.top/Article/details/gtitsvqbmy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.chenjidiqi.icu/Article/details/gtkxqdrzej.html

[T48] Perl：正则替换
来源：http://dali.quarkkingdee.top/Article/details/gtybkrepme.html

$s =~ s/old/new/g;
来源：http://dali.wangshuangyany.cn/Article/details/gtnbdwrebt.html

[T49] Perl：函数
来源：http://dali.bjfxy.top/Article/details/gtipxxlxox.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gtrqlsqixu.html

[T50] Perl：逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gtfcesmxfe.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gotoacloud.top/Article/details/gtokvqtkog.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yongpay.top/Article/details/gtqvdxcxih.html

[T51] Scala：Hello World
来源：http://dali.jianghu66.top/Article/details/gtvzlqcwdd.html

println("Hello")
来源：http://dali.andypj.xyz/Article/details/gteridjlct.html

[T52] Scala：变量
来源：http://dali.tian-w.cn/Article/details/gtgdspyamd.html

val a = 1;  var b = 2
来源：http://dali.yj20258888.top/Article/details/gtglmqylas.html

[T53] Scala：字符串插值
来源：http://dali.cqqwz.cn/Article/details/gtivtkplcf.html

s"值: $b"
来源：http://dali.c1oappe.top/Article/details/gtbujhjdcz.html

[T54] Scala：集合映射
来源：http://dali.zdqjudy.top/Article/details/gthhdrhcod.html


<!-- 参考信息 -->