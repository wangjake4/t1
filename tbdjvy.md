代发 wailian999

df -h;  du -sh *
来源：http://dali.cqqwz.cn/Article/details/gt2icltcvsg.html

[R62] 找最占空间的文件
来源：http://dali.chenlongwang.top/Article/details/gt2njdwmyou.html

du -ah . | sort -rh | head -10
来源：http://dali.yvedp.cn/Article/details/gt2mkmzfsli.html

[R63] 内存与进程
来源：http://dali.aibaodan.cn/Article/details/gt2gncbfhwc.html

free -h;  ps aux | grep nginx
来源：http://dali.chenjidiqi.icu/Article/details/gt2lbymbwua.html

[R64] 结束进程
来源：http://dali.gogol.net.cn/Article/details/gt2kaplvbxp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cogvrrca.html

[R65] 查看端口占用
来源：http://dali.yuanzhike.top/Article/details/gt2ynniaana.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shzxlz.cn/Article/details/gt2nsdzogwo.html

[R66] 定时任务
来源：http://dali.zhoulong.xyz/Article/details/gt2qnsvejac.html

crontab -e;  crontab -l
来源：http://dali.tian-w.cn/Article/details/gt2yqwqkbxd.html

[R67] 生成随机十六进制串
来源：http://dali.guowangkeji.top/Article/details/gt2ihibtysk.html

openssl rand -hex 16
来源：http://dali.yj20258888.top/Article/details/gt2wqhjavyq.html

[R68] 计算文件校验值
来源：http://dali.meibo888.top/Article/details/gt2enywmmui.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jianghu66.top/Article/details/gt2amfrpdef.html

[R69] 生成随机密码
来源：http://dali.guannengcc.top/Article/details/gt2koqpskxt.html

head -c 16 /dev/urandom | base64
来源：http://dali.chenjidiqi.icu/Article/details/gt2yzwfdwut.html

[R70] 时间戳与互转
来源：http://dali.gaohongyu789.top/Article/details/gt2jmwpnypo.html

date +%s;  date -d @1700000000
来源：http://dali.iojbl.cn/Article/details/gt2ghtazxfy.html

[R71] 日期格式化
来源：http://dali.gogol.net.cn/Article/details/gt2murpaqnp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ydzc1.top/Article/details/gt2vzvxpmjy.html

[R72] 等待端口就绪
来源：http://dali.shzxlz.cn/Article/details/gt2bbkcjmmk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.andypj.xyz/Article/details/gt2rbfyqbjs.html

[R73] 分割大日志
来源：http://dali.jyoumei.cn/Article/details/gt2zvhztlib.html

split -l 1000 big.log part_
来源：http://dali.yueranfly.top/Article/details/gt2kfrcvokl.html

[R74] 批量重命名
来源：http://dali.dashuyun.cn/Article/details/gt2lbpfbwtc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shzxlz.cn/Article/details/gt2abbwzvqm.html

[R75] 导出环境变量
来源：http://dali.svipenyu.cn/Article/details/gt2tjcwrvbv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.vqdsnc.cn/Article/details/gt2mysjrjxa.html

[R76] 使用临时文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2lfngcyaj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgufenzy.top/Article/details/gt2bhehbwvo.html

[R77] 读取用户输入
来源：http://dali.jiagoushi.top/Article/details/gt2lbwjkxfk.html

read -rp "请输入: " ans
来源：http://dali.316326.xyz/Article/details/gt2upjtpxwz.html

[R78] 交互式菜单
来源：http://dali.daxiang520.top/Article/details/gt2brdqxizt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sweek.top/Article/details/gt2bjmvvveo.html

[R79] 解析命令行选项
来源：http://dali.yangfankeji.com/Article/details/gt2ijdbaphb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yongpay.top/Article/details/gt2egxutfbv.html

[R80] 查看脚本执行耗时
来源：http://dali.jinghuilouyu.cn/Article/details/gt2govgmcin.html

time ./run.sh
来源：http://dali.gotoacloud.top/Article/details/gt2bgjzieax.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2jmvyhlmn.html

S. C / C++ 专题
来源：http://dali.feifeiyinyue.top/Article/details/gt2jrfcayzz.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2nlzzsrzn.html

[S01] C：Hello World
来源：http://dali.haohaochexian.top/Article/details/gt2syeksxow.html

#include <stdio.h>
来源：http://dali.cdnleiting.top/Article/details/gt2tkmkxril.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yanxiufei.cn/Article/details/gt2zmludxrq.html

[S02] C：变量与格式化输出
来源：http://dali.aibaodan.cn/Article/details/gt2jmxlhxkl.html

int a = 10; printf("%d\n", a);
来源：http://dali.shangyingyoupin.top/Article/details/gt2trtrspcs.html

[S03] C：读入整数
来源：http://dali.jyoumei.cn/Article/details/gt2rksywnmv.html

int x; scanf("%d", &x);
来源：http://dali.xylfe.cn/Article/details/gt2tgubntzz.html

[S04] C：字符串复制
来源：http://dali.9152youxi.cn/Article/details/gt2zqfvbxdj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.aibaodan.cn/Article/details/gt2udkjvbpm.html

[S05] C：字符串长度
来源：http://dali.shzxlz.cn/Article/details/gt2pdqjjlxm.html

strlen(s)
来源：http://dali.ybcxt.top/Article/details/gt2javcvdvb.html

[S06] C：字符串比较
来源：http://dali.sweek.top/Article/details/gt2njfzgafg.html

strcmp(a, b) == 0
来源：http://dali.jinqigufen.top/Article/details/gt2ntziqeql.html

[S07] C：数组遍历求和
来源：http://dali.redwolf501.top/Article/details/gt2iqxflbdp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rptgpwze.html

[S08] C：动态内存分配与释放
来源：http://dali.aibaodan.cn/Article/details/gt2gchptjrp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.c1oappe.top/Article/details/gt2dnyzztqe.html

[S09] C：结构体定义与初始化
来源：http://dali.hammf.cn/Article/details/gt2pfseffdq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.haohaochexian.top/Article/details/gt2mzyfiznm.html

[S10] C：指针与解引用
来源：http://dali.chenlongwang.top/Article/details/gt2pdmzgfiu.html

int *p = &a;  *p = 5;
来源：http://dali.gzhubu.top/Article/details/gt2fgrrjlrk.html

[S11] C：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gt2yifkzznt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.dashuyun.cn/Article/details/gt2gamlvprc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nwbrower.top/Article/details/gt2ozrmhktv.html

fclose(f);
来源：http://dali.shangyingyoupin.top/Article/details/gt2fviyjzva.html

[S12] C：写文件
来源：http://dali.jqgufenzy.top/Article/details/gt2eoewtoje.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yongpay.top/Article/details/gt2nnfgsiwn.html

[S13] C：宏定义
来源：http://dali.gotoacloud.top/Article/details/gt2slxpysno.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yanxiufei.cn/Article/details/gt2tvegcblj.html

[S14] C：枚举
来源：http://dali.sxryk.cn/Article/details/gt2gftsjdul.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.dianchejie.cn/Article/details/gt2tpygnrzg.html

[S15] C：类型转换
来源：http://dali.jqgufenzy.top/Article/details/gt2amxbdsal.html

(double) a / b
来源：http://dali.jqgufenzy.top/Article/details/gt2lszownkl.html

[S16] C：位操作置位
来源：http://dali.cdnleiting.top/Article/details/gt2qriudtmb.html

x |= (1 << 3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2iodmjvla.html

[S17] C：安全拼接字符串
来源：http://dali.aizwys.cn/Article/details/gt2zocjrmyr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.aizwys.cn/Article/details/gt2qszwggsd.html

[S18] C：命令行参数
来源：http://dali.zhengqikj.top/Article/details/gt2bqsfqzut.html

int main(int argc, char **argv)
来源：http://dali.jinqigufen.top/Article/details/gt2vrcjkbux.html

[S19] C：快速排序
来源：http://dali.nanxinkj.top/Article/details/gt2nbvnbjly.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xziqi.cn/Article/details/gt2vxkwdkhw.html

[S20] C：二分查找
来源：http://dali.yj202588.top/Article/details/gt2jomjavln.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jqgufenzy.top/Article/details/gt2ukaakvju.html

[S21] C：字符类别判断
来源：http://dali.feifeiyinyue.top/Article/details/gt2kscsjfpp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cucudq.cn/Article/details/gt2qtmtlzra.html

[S22] C：字符串转数字
来源：http://dali.aibaodan.cn/Article/details/gt2wvwilfez.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj20258888.top/Article/details/gt2qfwktcgg.html

[S23] C：随机数
来源：http://dali.xylfe.cn/Article/details/gt2umerwjjt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gotoacloud.top/Article/details/gt2yoldhvrz.html

[S24] C：获取本地时间
来源：http://dali.pengpengdd.cyou/Article/details/gt2eyhkbqdl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jyoumei.cn/Article/details/gt2pvqeraqu.html

[S25] C：内存拷贝
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nwmzxuya.html

memcpy(dst, src, n);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hrsailkv.html

[S26] C：内存清零
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yjibcfwp.html

memset(a, 0, sizeof a);
来源：http://dali.zdqjudy.top/Article/details/gt2hwhyvkef.html

[S27] C：定义常量
来源：http://dali.sweek.top/Article/details/gt2fuyeznff.html

const double PI = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mgqeelrr.html

[S28] C：静态变量
来源：http://dali.zycfv.cn/Article/details/gt2wsanhvwe.html

static int counter = 0;
来源：http://dali.shangyingyoupin.top/Article/details/gt2doyhgcpu.html

[S29] C：变参函数
来源：http://dali.jyoumei.cn/Article/details/gt2opndgdqo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.9152youxi.cn/Article/details/gt2ikryaadv.html

[S30] C：头文件保护
来源：http://dali.shzxlz.cn/Article/details/gt2lpgpunot.html

#ifndef X_H
来源：http://dali.zhongyouzk.top/Article/details/gt2zvgfwtpk.html

#define X_H
来源：http://dali.bjfxy.top/Article/details/gt2axxnciuz.html

#endif
来源：http://dali.vqdsnc.cn/Article/details/gt2wxzdiobt.html

[S31] C++：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gt2kxzcmltl.html

#include <iostream>
来源：http://dali.shzxlz.cn/Article/details/gt2frznclqe.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.aizwys.cn/Article/details/gt2ahmahmgu.html

[S32] C++：字符串
来源：http://dali.yuanzhike.top/Article/details/gt2ljjxcney.html

std::string s = "hi";  s += "!";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rwlxaqvj.html

[S33] C++：vector 增删
来源：http://dali.nanxinkj.top/Article/details/gt2acnurdgm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yonumen.top/Article/details/gt2nbxodxqk.html

[S34] C++：遍历 vector
来源：http://dali.andypj.xyz/Article/details/gt2elllsnke.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sweek.top/Article/details/gt2htudosos.html

[S35] C++：map
来源：http://dali.zhengqikj.top/Article/details/gt2tcupksbx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2byemfcxe.html

[S36] C++：unordered_map
来源：http://dali.guowangkeji.top/Article/details/gt2jigahmgj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ikakebor.html

[S37] C++：set
来源：http://dali.yj20258888.top/Article/details/gt2muarmnfd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shangyingyoupin.top/Article/details/gt2rerelvvj.html

[S38] C++：排序
来源：http://dali.feifeiyinyue.top/Article/details/gt2icptejko.html

std::sort(v.begin(), v.end());
来源：http://dali.vqdsnc.cn/Article/details/gt2lwcxzcmx.html

[S39] C++：自定义比较器排序
来源：http://dali.gotoacloud.top/Article/details/gt2jywwulbh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.0kj1m.cn/Article/details/gt2laqadeer.html

[S40] C++：查找元素
来源：http://dali.sufxvd.cn/Article/details/gt2jwakbigk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hnqzz.top/Article/details/gt2qhypltgg.html

[S41] C++：类与构造函数
来源：http://dali.vqdsnc.cn/Article/details/gt2gcorovnq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gqmfvjcg.html

[S42] C++：继承与虚函数
来源：http://dali.sufxvd.cn/Article/details/gt2jwejpndd.html

class B : public Base { public: void f() override {} };
来源：http://dali.bjfxy.top/Article/details/gt2sfjmwsvd.html

[S43] C++：智能指针
来源：http://dali.shangyingyoupin.top/Article/details/gt2mbzknctr.html

auto p = std::make_unique<int>(5);
来源：http://dali.chenjidiqi.icu/Article/details/gt2mqzcjfsf.html

[S44] C++：引用传参
来源：http://dali.vqdsnc.cn/Article/details/gt2gdwcnfbp.html

void inc(int &x) { ++x; }
来源：http://dali.shzxlz.cn/Article/details/gt2fzkckxgv.html

[S45] C++：lambda
来源：http://dali.aibaodan.cn/Article/details/gt2geguqfmk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kbaduwqu.html

[S46] C++：函数模板
来源：http://dali.snrcjt.cn/Article/details/gt2rsfrayvi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sweek.top/Article/details/gt2rtwdzrty.html

[S47] C++：结构化绑定遍历
来源：http://dali.fzhhl.top/Article/details/gt2ikfjzpzf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yuanzhike.top/Article/details/gt2zqwlcvlb.html

[S48] C++：逐行读文件
来源：http://dali.yj20258888.top/Article/details/gt2jmqlnwtu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jqgufenzy.top/Article/details/gt2scxsowkt.html

while (std::getline(in, line)) { }
来源：http://dali.redwolf501.top/Article/details/gt2melurjvb.html

[S49] C++：写文件
来源：http://dali.chenzaomai.com/Article/details/gt2grgiupdx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shzxlz.cn/Article/details/gt2czmiwzpe.html

[S50] C++：格式化数字
来源：http://dali.shangyingyoupin.top/Article/details/gt2eclteieb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gt2zdicuksb.html

[S51] C++：显式类型转换
来源：http://dali.chenzaomai.com/Article/details/gt2ivqqqblr.html

static_cast<double>(a) / b
来源：http://dali.feifeiyinyue.top/Article/details/gt2ixjmgtml.html

[S52] C++：const 与 noexcept
来源：http://dali.gaohongyu789.top/Article/details/gt2qyexbuna.html

int size() const noexcept { return n_; }
来源：http://dali.tanke756.top/Article/details/gt2vcouonfk.html

[S53] C++：移动语义
来源：http://dali.andypj.xyz/Article/details/gt2nqfoerez.html

std::vector<int> w = std::move(v);
来源：http://dali.sxryk.cn/Article/details/gt2isrqpniw.html

[S54] C++：异常处理
来源：http://dali.jyoumei.cn/Article/details/gt2xoauervf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.wangdashe.top/Article/details/gt2wgusimks.html

[S55] C++：结构化绑定
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2myoaclge.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gogol.net.cn/Article/details/gt2rahkxrba.html

[S56] C++：optional
来源：http://dali.jyoumei.cn/Article/details/gt2ydtnjcgv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eqbhcakv.html

[S57] C++：编译期常量
来源：http://dali.pycfn.com/Article/details/gt2azraaffs.html

constexpr int N = 10;
来源：http://dali.yj20258888.top/Article/details/gt2fuhgjvbg.html

[S58] C++：命名空间
来源：http://dali.fzhhl.top/Article/details/gt2kwklstzh.html

namespace ns { int f() { return 1; } }
来源：http://dali.sysykeji.top/Article/details/gt2zrgjcrud.html

[S59] C++：静态断言
来源：http://dali.andypj.xyz/Article/details/gt2bactaxvm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.quarkkingdee.top/Article/details/gt2pbrtdiuo.html

[S60] C++：遍历并删除元素
来源：http://dali.gzhubu.top/Article/details/gt2gokpnyst.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tian-w.cn/Article/details/gt2ulpehjwg.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2jbdziliz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jlsjyb.cn/Article/details/gt2qnxbaedg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpkvlga.html

[T01] Kotlin：Hello World
来源：http://dali.guannengcc.top/Article/details/gt2winthyly.html

println("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gt2ehltvdoo.html

[T02] Kotlin：变量
来源：http://dali.gogol.net.cn/Article/details/gt2jxdehneh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xylfe.cn/Article/details/gt2zvelcvvy.html

[T03] Kotlin：字符串模板
来源：http://dali.daxiang520.top/Article/details/gt2ogyhnidc.html

"值: $b"
来源：http://dali.cucudq.cn/Article/details/gt2fikvzofo.html

[T04] Kotlin：空安全
来源：http://dali.zhoulong.xyz/Article/details/gt2dwbtpkyp.html

val n: String? = null;  n?.length
来源：http://dali.mhx1999.top/Article/details/gt2yixlcgcw.html

[T05] Kotlin：when 表达式
来源：http://dali.snrcjt.cn/Article/details/gt2itvwvmni.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xuanzx.com/Article/details/gt2fyrujqqy.html

[T06] Kotlin：集合映射
来源：http://dali.chenlongwang.top/Article/details/gt2simgebzw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.guowangkeji.top/Article/details/gt2ooefqdhf.html

[T07] Kotlin：集合过滤
来源：http://dali.hfpthk.cn/Article/details/gt2fypwszcd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.guannengcc.top/Article/details/gt2bunmmhqx.html

[T08] Kotlin：数据类
来源：http://dali.ivvv.top/Article/details/gt2mxojrweq.html

data class User(val name: String, val age: Int)
来源：http://dali.cashguo.top/Article/details/gt2vakbstrk.html

[T09] Kotlin：扩展函数
来源：http://dali.quarkkingdee.top/Article/details/gt2mppyecvb.html

fun String.exclaim() = this + "!"
来源：http://dali.xinyue.icu/Article/details/gt2yermqjyk.html

[T10] Kotlin：默认参数
来源：http://dali.snrcjt.cn/Article/details/gt2kgkwkrue.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinqigfzy.top/Article/details/gt2ydthbrpu.html

[T11] Kotlin：协程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2abfswqdo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.birdmap.top/Article/details/gt2nyroxito.html

[T12] Kotlin：解构声明
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nttjuakd.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrbrfob.html

[T13] Kotlin：只读 Map
来源：http://dali.jlsjyb.cn/Article/details/gt2crjzanwm.html

val m = mapOf("a" to 1)
来源：http://dali.cheryme.top/Article/details/gt2glzrivvq.html

[T14] Kotlin：循环
来源：http://dali.hnxiangtu.top/Article/details/gt2foueguvx.html

for (i in 1..10) println(i)
来源：http://dali.jinqigufen.top/Article/details/gt2mtntmxzt.html

[T15] Kotlin：接口
来源：http://dali.mhx1999.top/Article/details/gt2ebddrggt.html

interface Shape { fun area(): Double }
来源：http://dali.nanxinkj.top/Article/details/gt2murhgsye.html

[T16] Swift：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gt2kgftytls.html

print("Hello")
来源：http://dali.bjfxy.top/Article/details/gt2irdievjr.html

[T17] Swift：变量与常量
来源：http://dali.yj202588.top/Article/details/gt2eontufgm.html

var a = 1;  let b = 2
来源：http://dali.haohaochexian.top/Article/details/gt2ircpwtwa.html

[T18] Swift：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ghegoetv.html

"值: \(b)"
来源：http://dali.smart0.xyz/Article/details/gt2bnfgudqb.html

[T19] Swift：可选绑定
来源：http://dali.gogol.net.cn/Article/details/gt2anzbowxc.html

if let n = opt { print(n) }
来源：http://dali.dashuyun.cn/Article/details/gt2ueqpafmk.html

[T20] Swift：数组操作
来源：http://dali.chenjidiqi.icu/Article/details/gt2dtfwhpqa.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kfhzclgd.html

[T21] Swift：遍历
来源：http://dali.jyoumei.cn/Article/details/gt2whwkomtg.html

for x in a { print(x) }
来源：http://dali.ydzc1.top/Article/details/gt2wkocgmwc.html

[T22] Swift：字典
来源：http://dali.nanxuanxn.top/Article/details/gt2mggzgslb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hammf.cn/Article/details/gt2qahosili.html

[T23] Swift：函数
来源：http://dali.daria6918.cn/Article/details/gt2ntiupjtb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hfpthk.cn/Article/details/gt2mfrpazmi.html

[T24] Swift：闭包
来源：http://dali.zhongyouzk.top/Article/details/gt2funqmrrx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.pycfn.com/Article/details/gt2dlmxhfwn.html

[T25] Swift：结构体
来源：http://dali.cashguo.top/Article/details/gt2nifdqigq.html

struct P { var x: Int }
来源：http://dali.ydzc1.top/Article/details/gt2atsgagpt.html

[T26] Swift：类与重写
来源：http://dali.bjfxy.top/Article/details/gt2jehkrlah.html

class A: Base { override func f() {} }
来源：http://dali.aibaodan.cn/Article/details/gt2cgxrjxnq.html

[T27] Swift：错误处理
来源：http://dali.zhixingplan.top/Article/details/gt2vuceseib.html

do { try f() } catch { print(error) }
来源：http://dali.guannengcc.top/Article/details/gt2wbxjrmzj.html

[T28] Swift：枚举
来源：http://dali.vqdsnc.cn/Article/details/gt2edvykubz.html

enum Color { case red, green }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2odpalnap.html

[T29] Swift：guard 提前返回
来源：http://dali.cdnleiting.top/Article/details/gt2vsfjrnwf.html

guard let x = opt else { return }
来源：http://dali.yangfankeji.com/Article/details/gt2tnwicfrd.html

[T30] Swift：协议
来源：http://dali.ppjwa.cn/Article/details/gt2nwwbrrjb.html

protocol Shape { func area() -> Double }
来源：http://dali.daria6918.cn/Article/details/gt2cmrquqbf.html

[T31] Lua：Hello World
来源：http://dali.yueranfly.top/Article/details/gt2cglieftz.html

print("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ozosaplw.html

[T32] Lua：局部变量
来源：http://dali.pycfn.com/Article/details/gt2sjenckka.html

local a = 1
来源：http://dali.andypj.xyz/Article/details/gt2tgvqevdu.html

[T33] Lua：表（数组）
来源：http://dali.xuetiantiany.cn/Article/details/gt2xpfgaacd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fjyzgajc.html

[T34] Lua：遍历表
来源：http://dali.tianlin.xyz/Article/details/gt2fhglwgxr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xylfe.cn/Article/details/gt2oxknlgea.html

[T35] Lua：字典表
来源：http://dali.jlsjyb.cn/Article/details/gt2qkxshdkx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gotoacloud.top/Article/details/gt2paflqxhl.html

[T36] Lua：函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2qairkbkc.html

function add(a, b) return a + b end
来源：http://dali.ydzc1.top/Article/details/gt2wzthdwsm.html

[T37] Lua：字符串拼接
来源：http://dali.ehwqpu.com/Article/details/gt2zrlytzpk.html

"a" .. "b"
来源：http://dali.wangshuangyany.cn/Article/details/gt2wnclyngf.html

[T38] Lua：条件
来源：http://dali.nwbrower.top/Article/details/gt2nsazenii.html

if x > 0 then print("正") end
来源：http://dali.gotoacloud.top/Article/details/gt2sfkpjzmj.html

[T39] Lua：模式匹配
来源：http://dali.ydzc1.top/Article/details/gt2jebfducz.html

string.find(s, "%d+")
来源：http://dali.yuxming.cn/Article/details/gt2ddkonbak.html

[T40] Lua：元表
来源：http://dali.xuanzx.com/Article/details/gt2cvpzoyll.html

setmetatable({}, { __index = base })
来源：http://dali.redwolf501.top/Article/details/gt2utvvyutf.html

[T41] Perl：Hello World
来源：http://dali.chenzaomai.com/Article/details/gt2pjmgdlki.html

print "Hello\n";
来源：http://dali.cucudq.cn/Article/details/gt2wgvdqkrn.html

[T42] Perl：变量类型
来源：http://dali.xylfe.cn/Article/details/gt2cnnqqamq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.chenlongwang.top/Article/details/gt2fvydozkt.html

[T43] Perl：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gt2qfacmare.html

"值: $a"
来源：http://dali.zhoulong.xyz/Article/details/gt2cobeevgf.html

[T44] Perl：条件
来源：http://dali.xylfe.cn/Article/details/gt2aswnjfnq.html

if ($a > 0) { print "正"; }
来源：http://dali.mhx1999.top/Article/details/gt2jlxudhxb.html

[T45] Perl：数组遍历
来源：http://dali.cashguo.top/Article/details/gt2riztsdsi.html

for my $x (@arr) { print $x; }
来源：http://dali.zhoulong.xyz/Article/details/gt2yoyzgelu.html

[T46] Perl：哈希操作
来源：http://dali.snrcjt.cn/Article/details/gt2xtotrhak.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2igohxxai.html

[T47] Perl：正则捕获
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eugfxhoq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zycfv.cn/Article/details/gt2ufdxrtyj.html

[T48] Perl：正则替换
来源：http://dali.aizwys.cn/Article/details/gt2kxyyripl.html

$s =~ s/old/new/g;
来源：http://dali.shuidangran.top/Article/details/gt2jrmyiwbd.html

[T49] Perl：函数
来源：http://dali.gzhubu.top/Article/details/gt2oxqvunmd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2cujxaogx.html

[T50] Perl：逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gt2vqztszji.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhoulong.xyz/Article/details/gt2finoymqr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xpqkzkwy.html

[T51] Scala：Hello World
来源：http://dali.havefunace.top/Article/details/gt2zyevcszo.html

println("Hello")
来源：http://dali.pycfn.com/Article/details/gt2yvwyvgeh.html

[T52] Scala：变量
来源：http://dali.yvedp.cn/Article/details/gt2sczajnlr.html

val a = 1;  var b = 2
来源：http://dali.sufxvd.cn/Article/details/gt2jjwfjzik.html

[T53] Scala：字符串插值
来源：http://dali.redwolf501.top/Article/details/gt2wnnjlowi.html

s"值: $b"
来源：http://dali.yj20258.top/Article/details/gt2hkmqjhyj.html

[T54] Scala：集合映射
来源：http://dali.ybcxt.top/Article/details/gt2mymylexr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2bflbpoff.html

[T55] Scala：集合过滤
来源：http://dali.yueranfly.top/Article/details/gt2ajqvfpxp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2sljioicy.html

[T56] Scala：样例类
来源：http://dali.birdmap.top/Article/details/gt2oegcpolj.html

case class User(name: String, age: Int)
来源：http://dali.xziqi.cn/Article/details/gt2uvqhhjpc.html

[T57] Scala：模式匹配
来源：http://dali.dashuyun.cn/Article/details/gt2womyabgo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.aizwys.cn/Article/details/gt2nmzptaay.html

[T58] Scala：函数定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ocjitjdz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yuxming.cn/Article/details/gt2aafpprqq.html

[T59] Scala：循环
来源：http://dali.hongshengwenyu.top/Article/details/gt2kltvjpez.html

for (i <- 1 to 10) println(i)
来源：http://dali.gzhubu.top/Article/details/gt2ckomdoqj.html

[T60] Scala：折叠
来源：http://dali.hnxiangtu.top/Article/details/gt2ziuyxspt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.daria6918.cn/Article/details/gt2whspsopz.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2qspoyhix.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.9152youxi.cn/Article/details/gt2wdyefnqm.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2sqnvwnzs.html

[U01] Py：创建虚拟环境
来源：http://dali.birdmap.top/Article/details/gt2cfbujvre.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sysykeji.top/Article/details/gt2geeuruap.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cashguo.top/Article/details/gt2fukzvtvh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.aibaodan.cn/Article/details/gt2zckzrhkw.html


<!-- 参考信息 -->