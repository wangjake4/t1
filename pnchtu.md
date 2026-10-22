代发 wailian999

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cashguo.top/Article/details/gtbtmwlllk.html

[R54] 比较两个文件
来源：http://dali.snrcjt.cn/Article/details/gteyoaiinh.html

diff a.txt b.txt
来源：http://dali.havefunace.top/Article/details/gtrwldsouz.html

[R55] 压缩与解压
来源：http://dali.yj202588.top/Article/details/gtmaafyujp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tianlin.xyz/Article/details/gtduptejze.html

[R56] 远程拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gtglyfshbz.html

scp file user@host:/path/
来源：http://dali.shanyushiyangtech.top/Article/details/gttqomotzu.html

[R57] 远程执行命令
来源：http://dali.shzxlz.cn/Article/details/gtuemqqbkg.html

ssh user@host 'uptime'
来源：http://dali.shangyingyoupin.top/Article/details/gtyreentdx.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gtutaeplbl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yj202588.top/Article/details/gtejlpxmrz.html

[R59] 发 POST JSON
来源：http://dali.hysaishi.cn/Article/details/gtgsptmgxa.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yueranfly.top/Article/details/gtdythqych.html

[R60] 只看 HTTP 状态码
来源：http://dali.wangdashe.top/Article/details/gtuxhegohi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cheryme.top/Article/details/gtbeajdulp.html

[R61] 磁盘占用
来源：http://dali.shangyingyoupin.top/Article/details/gtamrqqjog.html

df -h;  du -sh *
来源：http://dali.jianghu66.top/Article/details/gttecmvqra.html

[R62] 找最占空间的文件
来源：http://dali.hysaishi.cn/Article/details/gtgvkzfmhr.html

du -ah . | sort -rh | head -10
来源：http://dali.yonumen.top/Article/details/gtkfbhskkv.html

[R63] 内存与进程
来源：http://dali.0kj1m.cn/Article/details/gtftupnzdp.html

free -h;  ps aux | grep nginx
来源：http://dali.zhiwuduotai.top/Article/details/gthfiqeeke.html

[R64] 结束进程
来源：http://dali.hysaishi.cn/Article/details/gtaaqsckwl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jianghu66.top/Article/details/gtggviqnez.html

[R65] 查看端口占用
来源：http://dali.gotoacloud.top/Article/details/gttfdggyqd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yueranfly.top/Article/details/gtcyavfauy.html

[R66] 定时任务
来源：http://dali.0kj1m.cn/Article/details/gtvwbmyvhi.html

crontab -e;  crontab -l
来源：http://dali.nanxinkj.top/Article/details/gtktdgbjiw.html

[R67] 生成随机十六进制串
来源：http://dali.xuanzx.com/Article/details/gtjiogbhdd.html

openssl rand -hex 16
来源：http://dali.yj20258.top/Article/details/gtafvlepjd.html

[R68] 计算文件校验值
来源：http://dali.jinqigufen.top/Article/details/gtupavdppn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtojbebumi.html

[R69] 生成随机密码
来源：http://dali.bjfxy.top/Article/details/gtvnfvnklh.html

head -c 16 /dev/urandom | base64
来源：http://dali.daxiang520.top/Article/details/gtbeffomzm.html

[R70] 时间戳与互转
来源：http://dali.smart0.xyz/Article/details/gtzhwxlupu.html

date +%s;  date -d @1700000000
来源：http://dali.andypj.xyz/Article/details/gtghbqwths.html

[R71] 日期格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gtmnouuwja.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zdqjudy.top/Article/details/gtytphfsto.html

[R72] 等待端口就绪
来源：http://dali.dashuyun.cn/Article/details/gtiwmnjjet.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.guowangkeji.top/Article/details/gtpomcesyv.html

[R73] 分割大日志
来源：http://dali.cdnleiting.top/Article/details/gtsajwxmtb.html

split -l 1000 big.log part_
来源：http://dali.jqgfzy.top/Article/details/gtqejlrhrf.html

[R74] 批量重命名
来源：http://dali.yuxming.cn/Article/details/gtonkfjegm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jqgfzy.top/Article/details/gthssmladh.html

[R75] 导出环境变量
来源：http://dali.xziqi.cn/Article/details/gthliiblkb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jianghu66.top/Article/details/gtqhukkcfb.html

[R76] 使用临时文件
来源：http://dali.gotoacloud.top/Article/details/gtreykfkrw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.havefunace.top/Article/details/gtlyycxhct.html

[R77] 读取用户输入
来源：http://dali.fzhhl.top/Article/details/gtpjlrwmtm.html

read -rp "请输入: " ans
来源：http://dali.dianchejie.cn/Article/details/gtlinewhkc.html

[R78] 交互式菜单
来源：http://dali.xuetiantiany.cn/Article/details/gtrcoknyuq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhoulong.xyz/Article/details/gtrmgekbko.html

[R79] 解析命令行选项
来源：http://dali.nanxinkj.top/Article/details/gtixofshkg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yuxming.cn/Article/details/gtigmckrql.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gthoywnlvx.html

time ./run.sh
来源：http://dali.aibaodan.cn/Article/details/gtctgoxjtz.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtrwlktkhn.html

S. C / C++ 专题
来源：http://dali.nanxuanxn.top/Article/details/gtwadngrgj.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtzkeipxwk.html

[S01] C：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtansjueqq.html

#include <stdio.h>
来源：http://dali.vqdsnc.cn/Article/details/gttkksjqeo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhoulong.xyz/Article/details/gtzvithoow.html

[S02] C：变量与格式化输出
来源：http://dali.aibaodan.cn/Article/details/gtyaqrsxba.html

int a = 10; printf("%d\n", a);
来源：http://dali.hongshengwenyu.top/Article/details/gtocnoctia.html

[S03] C：读入整数
来源：http://dali.aibaodan.cn/Article/details/gtwdcmqoli.html

int x; scanf("%d", &x);
来源：http://dali.yj20258888.top/Article/details/gtbiqiuxid.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangtech.top/Article/details/gtlhbavjuq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj202588.top/Article/details/gtmxohgsnb.html

[S05] C：字符串长度
来源：http://dali.dashuyun.cn/Article/details/gtlbjrmzxs.html

strlen(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjsacdpja.html

[S06] C：字符串比较
来源：http://dali.fengsongda.top/Article/details/gtgudpbxmv.html

strcmp(a, b) == 0
来源：http://dali.hywenlv.cn/Article/details/gtobqsacou.html

[S07] C：数组遍历求和
来源：http://dali.aibaodan.cn/Article/details/gtudcysalz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ivvv.top/Article/details/gtkyduifzp.html

[S08] C：动态内存分配与释放
来源：http://dali.yuanzhike.top/Article/details/gttfwfvcin.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yangfankeji.com/Article/details/gtzzwdrohe.html

[S09] C：结构体定义与初始化
来源：http://dali.tianlin.xyz/Article/details/gtpgnbeshl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenzaomai.com/Article/details/gtchrfqonn.html

[S10] C：指针与解引用
来源：http://dali.hammf.cn/Article/details/gtfnbrwusx.html

int *p = &a;  *p = 5;
来源：http://dali.gzhubu.top/Article/details/gtbncomhwb.html

[S11] C：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gtyilnhryc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jyoumei.cn/Article/details/gtilxntrxa.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cucudq.cn/Article/details/gtgtlscutv.html

fclose(f);
来源：http://dali.yj202588.top/Article/details/gtajdpvxdl.html

[S12] C：写文件
来源：http://dali.xylfe.cn/Article/details/gtecmsqhqq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jqgufenzy.top/Article/details/gtwmmvxnju.html

[S13] C：宏定义
来源：http://dali.aibaodan.cn/Article/details/gtclvfehkl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.wangdashe.top/Article/details/gtvhdfbssy.html

[S14] C：枚举
来源：http://dali.havefunace.top/Article/details/gtpcjxvzgp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhixingplan.top/Article/details/gtipegyyfr.html

[S15] C：类型转换
来源：http://dali.guannengcc.top/Article/details/gtumigjxah.html

(double) a / b
来源：http://dali.xylfe.cn/Article/details/gtqyeypsxt.html

[S16] C：位操作置位
来源：http://dali.kuanghao11.cn/Article/details/gtgtbyfaev.html

x |= (1 << 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtrzbdnplb.html

[S17] C：安全拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtvqttgtli.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yangfankeji.com/Article/details/gtbpauywic.html

[S18] C：命令行参数
来源：http://dali.ydzc1.top/Article/details/gtcjkzudcm.html

int main(int argc, char **argv)
来源：http://dali.fengsongda.top/Article/details/gthgufgbvv.html

[S19] C：快速排序
来源：http://dali.nanxuanxn.top/Article/details/gtfeddmtfl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hywenlv.cn/Article/details/gtutslflbq.html

[S20] C：二分查找
来源：http://dali.smart0.xyz/Article/details/gticxggbkh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj20258.top/Article/details/gtgamkqqtv.html

[S21] C：字符类别判断
来源：http://dali.snrcjt.cn/Article/details/gtoykdmeyp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ydzc1.top/Article/details/gtopdfazfy.html

[S22] C：字符串转数字
来源：http://dali.316326.xyz/Article/details/gtdgzmchss.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sxryk.cn/Article/details/gtwodnnxrp.html

[S23] C：随机数
来源：http://dali.andypj.xyz/Article/details/gtybhvfyad.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.dashuyun.cn/Article/details/gtowtfwwmo.html

[S24] C：获取本地时间
来源：http://dali.guannengcc.top/Article/details/gtbilsmwbe.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhongyouzk.top/Article/details/gtmaevbzul.html

[S25] C：内存拷贝
来源：http://dali.haohaochexian.top/Article/details/gttpudpaiq.html

memcpy(dst, src, n);
来源：http://dali.ehwqpu.com/Article/details/gtlmqmzqgs.html

[S26] C：内存清零
来源：http://dali.mhx1999.top/Article/details/gtzmijlxwj.html

memset(a, 0, sizeof a);
来源：http://dali.zhiwuduotai.top/Article/details/gtqjfgkzsx.html

[S27] C：定义常量
来源：http://dali.yonumen.top/Article/details/gtfrbgxcnj.html

const double PI = 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gtqgykjvck.html

[S28] C：静态变量
来源：http://dali.yangfankeji.com/Article/details/gtjxjzyccs.html

static int counter = 0;
来源：http://dali.yuxming.cn/Article/details/gttjbpjnde.html

[S29] C：变参函数
来源：http://dali.hywenlv.cn/Article/details/gtdsqstmdy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzucjxqyp.html

[S30] C：头文件保护
来源：http://dali.chenzaomai.com/Article/details/gtymlmviob.html

#ifndef X_H
来源：http://dali.hnxiangtu.top/Article/details/gtjuxyezls.html

#define X_H
来源：http://dali.snrcjt.cn/Article/details/gtuikzcdcs.html

#endif
来源：http://dali.hfpthk.cn/Article/details/gtzglduqbn.html

[S31] C++：Hello World
来源：http://dali.bjfxy.top/Article/details/gtycyrijnr.html

#include <iostream>
来源：http://dali.hnqzz.top/Article/details/gtpxyhygjw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ydzc1.top/Article/details/gtgtzcswnf.html

[S32] C++：字符串
来源：http://dali.andypj.xyz/Article/details/gtsipcgsvr.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gtreanntth.html

[S33] C++：vector 增删
来源：http://dali.shanyushiyangtech.top/Article/details/gtldlyailz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.guannengcc.top/Article/details/gtishlyzva.html

[S34] C++：遍历 vector
来源：http://dali.nanxinkj.top/Article/details/gtxfydflfg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.fzhhl.top/Article/details/gthxsqsrdp.html

[S35] C++：map
来源：http://dali.hammf.cn/Article/details/gtllpbgyon.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnqzz.top/Article/details/gtxctsldxz.html

[S36] C++：unordered_map
来源：http://dali.cashguo.top/Article/details/gtwwkktmcr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sxryk.cn/Article/details/gtvikwedul.html

[S37] C++：set
来源：http://dali.gaohongyu789.top/Article/details/gtuwfdivhi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.iojbl.cn/Article/details/gtmqadaojr.html

[S38] C++：排序
来源：http://dali.chenlongwang.top/Article/details/gtnzfovflv.html

std::sort(v.begin(), v.end());
来源：http://dali.yvedp.cn/Article/details/gtzzugndmv.html

[S39] C++：自定义比较器排序
来源：http://dali.zhengqikj.top/Article/details/gtnnejroui.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gogol.net.cn/Article/details/gtnzqdczjf.html

[S40] C++：查找元素
来源：http://dali.zhengqikj.top/Article/details/gtifwnhxct.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jyoumei.cn/Article/details/gtzfhqhvxe.html

[S41] C++：类与构造函数
来源：http://dali.nanxinkj.top/Article/details/gtpwjcdjci.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hywenlv.cn/Article/details/gtjaaichga.html

[S42] C++：继承与虚函数
来源：http://dali.pycfn.com/Article/details/gtulheryrq.html

class B : public Base { public: void f() override {} };
来源：http://dali.aibaodan.cn/Article/details/gttfhnqstk.html

[S43] C++：智能指针
来源：http://dali.guannengcc.top/Article/details/gtsglswvix.html

auto p = std::make_unique<int>(5);
来源：http://dali.hfpthk.cn/Article/details/gtklqfmwrx.html

[S44] C++：引用传参
来源：http://dali.shanyushiyangtech.top/Article/details/gtiqvlglml.html

void inc(int &x) { ++x; }
来源：http://dali.chenlongwang.top/Article/details/gtlbagtskw.html

[S45] C++：lambda
来源：http://dali.0kj1m.cn/Article/details/gtlfrheshg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhongyouzk.top/Article/details/gtabggksyc.html

[S46] C++：函数模板
来源：http://dali.zhiwuduotai.top/Article/details/gtgzgzminu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtznecelta.html

[S47] C++：结构化绑定遍历
来源：http://dali.sxryk.cn/Article/details/gtbpsbzelq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shangyingyoupin.top/Article/details/gtzopnatjm.html

[S48] C++：逐行读文件
来源：http://dali.yj202588.top/Article/details/gtffwxjaos.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnqatssxy.html

while (std::getline(in, line)) { }
来源：http://dali.jqgufenzy.top/Article/details/gtxvehmtnn.html

[S49] C++：写文件
来源：http://dali.tanke756.top/Article/details/gthozxosrg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinqigufen.top/Article/details/gtmmniujzd.html

[S50] C++：格式化数字
来源：http://dali.hfpthk.cn/Article/details/gtcsdgwjdp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.pycfn.com/Article/details/gtiaitpzon.html

[S51] C++：显式类型转换
来源：http://dali.hywenlv.cn/Article/details/gtrpgjbcnk.html

static_cast<double>(a) / b
来源：http://dali.chenjidiqi.icu/Article/details/gtvcaeihcz.html

[S52] C++：const 与 noexcept
来源：http://dali.jinyuanbaomall.cn/Article/details/gtepkkklac.html

int size() const noexcept { return n_; }
来源：http://dali.hnqzz.top/Article/details/gtbqqosaqf.html

[S53] C++：移动语义
来源：http://dali.hnqzz.top/Article/details/gtmbrfokjy.html

std::vector<int> w = std::move(v);
来源：http://dali.zycfv.cn/Article/details/gtjeztwdya.html

[S54] C++：异常处理
来源：http://dali.cqqwz.cn/Article/details/gtocjyfupk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gteuoddipb.html

[S55] C++：结构化绑定
来源：http://dali.ivvv.top/Article/details/gtxyzggmkg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xziqi.cn/Article/details/gtqsewrfvp.html

[S56] C++：optional
来源：http://dali.birdmap.top/Article/details/gtwvzybmzu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cheryme.top/Article/details/gtnsdcwnlm.html

[S57] C++：编译期常量
来源：http://dali.shuidangran.top/Article/details/gtpywpnxud.html

constexpr int N = 10;
来源：http://dali.nanxinkj.top/Article/details/gtuisqlchx.html

[S58] C++：命名空间
来源：http://dali.zdqjudy.top/Article/details/gthotblsna.html

namespace ns { int f() { return 1; } }
来源：http://dali.svipenyu.cn/Article/details/gtlwojmmqw.html

[S59] C++：静态断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkzkzyysr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yanxiufei.cn/Article/details/gtvudberib.html

[S60] C++：遍历并删除元素
来源：http://dali.yuxming.cn/Article/details/gtwxyvithf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jlsjyb.cn/Article/details/gtjajvqqrl.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gthhkmwozu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.daxiang520.top/Article/details/gtnwzbzagf.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gttkqhdfck.html

[T01] Kotlin：Hello World
来源：http://dali.316326.xyz/Article/details/gtzrmohbvf.html

println("Hello")
来源：http://dali.daria6918.cn/Article/details/gtfuiucosg.html

[T02] Kotlin：变量
来源：http://dali.yj202588.top/Article/details/gtnwvryjbb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinghuilouyu.cn/Article/details/gtquybtcks.html

[T03] Kotlin：字符串模板
来源：http://dali.9152youxi.cn/Article/details/gtanovikhe.html

"值: $b"
来源：http://dali.tanke756.top/Article/details/gtanzjsmxi.html

[T04] Kotlin：空安全
来源：http://dali.pengpengdd.cyou/Article/details/gtvtgqkrsl.html

val n: String? = null;  n?.length
来源：http://dali.yangfankeji.com/Article/details/gtsrkwmztg.html

[T05] Kotlin：when 表达式
来源：http://dali.yj20258.top/Article/details/gtyirnsiic.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhoulong.xyz/Article/details/gtmkphnzhu.html

[T06] Kotlin：集合映射
来源：http://dali.guowangkeji.top/Article/details/gtsslwitvm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yj20258888.top/Article/details/gtmdhejrpf.html

[T07] Kotlin：集合过滤
来源：http://dali.yueranfly.top/Article/details/gthqhvsugx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ehwqpu.com/Article/details/gtpkrlmiiu.html

[T08] Kotlin：数据类
来源：http://dali.cucudq.cn/Article/details/gtmtjsjisc.html

data class User(val name: String, val age: Int)
来源：http://dali.gaohongyu789.top/Article/details/gtppbasqmi.html

[T09] Kotlin：扩展函数
来源：http://dali.9152youxi.cn/Article/details/gtibuosijx.html

fun String.exclaim() = this + "!"
来源：http://dali.nwbrower.top/Article/details/gtnvsziycq.html

[T10] Kotlin：默认参数
来源：http://dali.shuidangran.top/Article/details/gttinoerxp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.nanxuanxn.top/Article/details/gtpflvtbzp.html

[T11] Kotlin：协程
来源：http://dali.jianghu66.top/Article/details/gtqsibfrxi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gzhubu.top/Article/details/gtxphnupyu.html

[T12] Kotlin：解构声明
来源：http://dali.zhongyouzk.top/Article/details/gthrgvknxy.html

val (a, b) = Pair(1, 2)
来源：http://dali.smart0.xyz/Article/details/gtdtiljgcd.html

[T13] Kotlin：只读 Map
来源：http://dali.9152youxi.cn/Article/details/gtegcerdah.html

val m = mapOf("a" to 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtdwqpsitl.html

[T14] Kotlin：循环
来源：http://dali.tian-w.cn/Article/details/gtnnrvvdzd.html

for (i in 1..10) println(i)
来源：http://dali.dianchejie.cn/Article/details/gtuzxeymrf.html

[T15] Kotlin：接口
来源：http://dali.zhaomingkeji.xyz/Article/details/gteprfosjs.html

interface Shape { fun area(): Double }
来源：http://dali.mhx1999.top/Article/details/gthbhjvfpk.html

[T16] Swift：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtuleikrzu.html

print("Hello")
来源：http://dali.tian-w.cn/Article/details/gtkowagxbp.html

[T17] Swift：变量与常量
来源：http://dali.zhiwuduotai.top/Article/details/gtiosmzdtm.html

var a = 1;  let b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxmjtkqbr.html

[T18] Swift：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gtyjdmtmju.html

"值: \(b)"
来源：http://dali.0kj1m.cn/Article/details/gtczwadhvn.html

[T19] Swift：可选绑定
来源：http://dali.jinghuilouyu.cn/Article/details/gtatvyuykk.html

if let n = opt { print(n) }
来源：http://dali.jianghu66.top/Article/details/gtlmewlklc.html

[T20] Swift：数组操作
来源：http://dali.jiagoushi.top/Article/details/gtptiwlytb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gzhubu.top/Article/details/gtuyhhowdo.html

[T21] Swift：遍历
来源：http://dali.yuanzhike.top/Article/details/gtrqvqooys.html

for x in a { print(x) }
来源：http://dali.gaohongyu789.top/Article/details/gtaumvwcii.html

[T22] Swift：字典
来源：http://dali.chenzaomai.com/Article/details/gtcdpwcgwg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zycfv.cn/Article/details/gtkisbayum.html

[T23] Swift：函数
来源：http://dali.316326.xyz/Article/details/gtpuhxwljx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.smart0.xyz/Article/details/gtvhzkcioi.html

[T24] Swift：闭包
来源：http://dali.zhixingplan.top/Article/details/gtcdsqdvlu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtqmvrhpxk.html

[T25] Swift：结构体
来源：http://dali.wangshuangyany.cn/Article/details/gtumtinzrc.html

struct P { var x: Int }
来源：http://dali.pycfn.com/Article/details/gtfkqdgszn.html

[T26] Swift：类与重写
来源：http://dali.zdqjudy.top/Article/details/gtmqbznrhe.html

class A: Base { override func f() {} }
来源：http://dali.yueranfly.top/Article/details/gtkfybqlzj.html

[T27] Swift：错误处理
来源：http://dali.316326.xyz/Article/details/gtndusglpe.html

do { try f() } catch { print(error) }
来源：http://dali.smart0.xyz/Article/details/gtotsqcccw.html

[T28] Swift：枚举
来源：http://dali.cashguo.top/Article/details/gthvfwyglk.html

enum Color { case red, green }
来源：http://dali.xuanzx.com/Article/details/gtdlfxwryy.html

[T29] Swift：guard 提前返回
来源：http://dali.xuanzx.com/Article/details/gtfipfzgoh.html

guard let x = opt else { return }
来源：http://dali.dianchejie.cn/Article/details/gtyudzpsqm.html

[T30] Swift：协议
来源：http://dali.zhoulong.xyz/Article/details/gtaclenpgn.html

protocol Shape { func area() -> Double }
来源：http://dali.tanke756.top/Article/details/gthtdfrnbg.html

[T31] Lua：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtgyumaduv.html

print("Hello")
来源：http://dali.yongpay.top/Article/details/gtcmtotvbc.html

[T32] Lua：局部变量
来源：http://dali.aizwys.cn/Article/details/gtjhoultte.html

local a = 1
来源：http://dali.shangyingyoupin.top/Article/details/gttbgciwbv.html

[T33] Lua：表（数组）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrugtfkry.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.0kj1m.cn/Article/details/gtjmkmsjjl.html

[T34] Lua：遍历表
来源：http://dali.quarkkingdee.top/Article/details/gtjgxlqxho.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.vqdsnc.cn/Article/details/gtrbuguysg.html

[T35] Lua：字典表
来源：http://dali.yanxiufei.cn/Article/details/gtyfjgjeht.html

local d = { a = 1 };  d.b = 2
来源：http://dali.meibo888.top/Article/details/gthmydigqo.html

[T36] Lua：函数
来源：http://dali.gotoacloud.top/Article/details/gtixfuksvs.html

function add(a, b) return a + b end
来源：http://dali.cashguo.top/Article/details/gtgkqcytpa.html

[T37] Lua：字符串拼接
来源：http://dali.gzhubu.top/Article/details/gtkqjvoxop.html

"a" .. "b"
来源：http://dali.birdmap.top/Article/details/gtednlqmie.html

[T38] Lua：条件
来源：http://dali.nanxuanxn.top/Article/details/gtzntsnusr.html

if x > 0 then print("正") end
来源：http://dali.andypj.xyz/Article/details/gtzcjdpnwn.html

[T39] Lua：模式匹配
来源：http://dali.mhx1999.top/Article/details/gtziaztlld.html

string.find(s, "%d+")
来源：http://dali.ydzc1.top/Article/details/gtbsqoqvsp.html

[T40] Lua：元表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuyjshifj.html

setmetatable({}, { __index = base })
来源：http://dali.ydzc1.top/Article/details/gtaoihrjhy.html

[T41] Perl：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtpoufjavl.html

print "Hello\n";
来源：http://dali.shangyingyoupin.top/Article/details/gtmyxlwtse.html

[T42] Perl：变量类型
来源：http://dali.cheryme.top/Article/details/gthsuiukse.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yueranfly.top/Article/details/gthobqjkco.html

[T43] Perl：字符串插值
来源：http://dali.c1oappe.top/Article/details/gtckuykiel.html

"值: $a"
来源：http://dali.jyoumei.cn/Article/details/gtykzpwmwd.html

[T44] Perl：条件
来源：http://dali.pycfn.com/Article/details/gtssthdwhk.html

if ($a > 0) { print "正"; }
来源：http://dali.dianchejie.cn/Article/details/gtydiqzbli.html

[T45] Perl：数组遍历
来源：http://dali.yueranfly.top/Article/details/gtyvgqltmi.html

for my $x (@arr) { print $x; }
来源：http://dali.andypj.xyz/Article/details/gtiqnmiyqr.html

[T46] Perl：哈希操作
来源：http://dali.meibo888.top/Article/details/gtxodwdyqp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.316326.xyz/Article/details/gtehpcxrsr.html

[T47] Perl：正则捕获
来源：http://dali.hammf.cn/Article/details/gtgqwzaerl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.0kj1m.cn/Article/details/gtchbongti.html

[T48] Perl：正则替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtymrxxvax.html

$s =~ s/old/new/g;
来源：http://dali.hnqzz.top/Article/details/gtfrmhlqjj.html

[T49] Perl：函数
来源：http://dali.kuanghao11.cn/Article/details/gtacaeouzh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gtyfruowoy.html

[T50] Perl：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtgdrpfwmb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.shzxlz.cn/Article/details/gtaeynbria.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yanxiufei.cn/Article/details/gtvbqswsat.html

[T51] Scala：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtooznnyio.html

println("Hello")
来源：http://dali.0kj1m.cn/Article/details/gteqxkklno.html

[T52] Scala：变量
来源：http://dali.guannengcc.top/Article/details/gtuzxindmb.html

val a = 1;  var b = 2
来源：http://dali.nanxinkj.top/Article/details/gtcnqlpkku.html

[T53] Scala：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gtdyfntspy.html

s"值: $b"
来源：http://dali.shzxlz.cn/Article/details/gtdzfrvurk.html

[T54] Scala：集合映射
来源：http://dali.xylfe.cn/Article/details/gtgjwcdgiy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yangfankeji.com/Article/details/gthexbswcd.html

[T55] Scala：集合过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gtinypdrqf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.pycfn.com/Article/details/gtebsmnwih.html

[T56] Scala：样例类
来源：http://dali.zycfv.cn/Article/details/gtraxnpaqr.html


<!-- 参考信息 -->