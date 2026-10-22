代发 wailian999

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.c1oappe.top/Article/details/gtgsbvybyx.html

[R52] 统计行数
来源：http://dali.yanxiufei.cn/Article/details/gtzfmmgifd.html

wc -l a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gterfbxuwb.html

[R53] 查看文件头与实时尾
来源：http://dali.yj202588.top/Article/details/gtppeqjylv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xuetiantiany.cn/Article/details/gtwtqagjqj.html

[R54] 比较两个文件
来源：http://dali.tanke756.top/Article/details/gtpopremdn.html

diff a.txt b.txt
来源：http://dali.zhoulong.xyz/Article/details/gtbcahgtnc.html

[R55] 压缩与解压
来源：http://dali.shuidangran.top/Article/details/gtiukkgclr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hywenlv.cn/Article/details/gtxgrqsneo.html

[R56] 远程拷贝
来源：http://dali.sweek.top/Article/details/gtkouolqsc.html

scp file user@host:/path/
来源：http://dali.ydzc1.top/Article/details/gtupdwbgws.html

[R57] 远程执行命令
来源：http://dali.hnxiangtu.top/Article/details/gtlqbtpzqn.html

ssh user@host 'uptime'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxctgktwi.html

[R58] 下载文件
来源：http://dali.tianlin.xyz/Article/details/gtcaywtzlo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhiwuduotai.top/Article/details/gtykjtdieg.html

[R59] 发 POST JSON
来源：http://dali.nwbrower.top/Article/details/gtclhrkszg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj202588.top/Article/details/gtbgogtmlp.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenlongwang.top/Article/details/gtlerpdflh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tian-w.cn/Article/details/gtduosajiy.html

[R61] 磁盘占用
来源：http://dali.nanxinkj.top/Article/details/gtcatjautk.html

df -h;  du -sh *
来源：http://dali.tanke756.top/Article/details/gtwtfkfnjn.html

[R62] 找最占空间的文件
来源：http://dali.meibo888.top/Article/details/gthmqqlxyz.html

du -ah . | sort -rh | head -10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcpwqqedm.html

[R63] 内存与进程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteuqtvppn.html

free -h;  ps aux | grep nginx
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkpcqiyph.html

[R64] 结束进程
来源：http://dali.fengsongda.top/Article/details/gtkicnqlml.html

kill -9 $(pgrep -f app.py)
来源：http://dali.fzhhl.top/Article/details/gtkgnmjvkl.html

[R65] 查看端口占用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfjqhlyfw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.dashuyun.cn/Article/details/gtbexwnuqb.html

[R66] 定时任务
来源：http://dali.smart0.xyz/Article/details/gtzipgnlqj.html

crontab -e;  crontab -l
来源：http://dali.daxiang520.top/Article/details/gtxjiihxyw.html

[R67] 生成随机十六进制串
来源：http://dali.xinyue.icu/Article/details/gteumjkxtd.html

openssl rand -hex 16
来源：http://dali.birdmap.top/Article/details/gtipitfxyv.html

[R68] 计算文件校验值
来源：http://dali.yuanzhike.top/Article/details/gtfkenbbzt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shuidangran.top/Article/details/gtdtpvaait.html

[R69] 生成随机密码
来源：http://dali.tianlin.xyz/Article/details/gtqiacddmu.html

head -c 16 /dev/urandom | base64
来源：http://dali.aibaodan.cn/Article/details/gtucoqlqkg.html

[R70] 时间戳与互转
来源：http://dali.jinqigfzy.top/Article/details/gtvdlbhptx.html

date +%s;  date -d @1700000000
来源：http://dali.yvedp.cn/Article/details/gtbchzzfxq.html

[R71] 日期格式化
来源：http://dali.hnxiangtu.top/Article/details/gtxnezfmld.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.havefunace.top/Article/details/gtbcleggyg.html

[R72] 等待端口就绪
来源：http://dali.quarkkingdee.top/Article/details/gteafcdife.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.iojbl.cn/Article/details/gtsociypfc.html

[R73] 分割大日志
来源：http://dali.jinghuilouyu.cn/Article/details/gtasgbqvyi.html

split -l 1000 big.log part_
来源：http://dali.smart0.xyz/Article/details/gtekeynzcj.html

[R74] 批量重命名
来源：http://dali.fzhhl.top/Article/details/gtfxbbxvey.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.dashuyun.cn/Article/details/gtjswjdahh.html

[R75] 导出环境变量
来源：http://dali.9152youxi.cn/Article/details/gtwphaicvx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfejjdunc.html

[R76] 使用临时文件
来源：http://dali.xziqi.cn/Article/details/gthussrocs.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.andypj.xyz/Article/details/gtajmmdvve.html

[R77] 读取用户输入
来源：http://dali.chenzaomai.com/Article/details/gtughaxtsq.html

read -rp "请输入: " ans
来源：http://dali.zhiwuduotai.top/Article/details/gtimhutuvl.html

[R78] 交互式菜单
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdkqhcfpt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shangyingyoupin.top/Article/details/gtspxktpqr.html

[R79] 解析命令行选项
来源：http://dali.daxiang520.top/Article/details/gtjxltgogn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.smart0.xyz/Article/details/gtjwxkpdur.html

[R80] 查看脚本执行耗时
来源：http://dali.cheryme.top/Article/details/gtualxqdge.html

time ./run.sh
来源：http://dali.jqgfzy.top/Article/details/gtkpcxdgul.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtallrhhxm.html

S. C / C++ 专题
来源：http://dali.wangshuangyany.cn/Article/details/gtrhewttjf.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtvmauizsv.html

[S01] C：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtdjbxwswp.html

#include <stdio.h>
来源：http://dali.hammf.cn/Article/details/gtnxzcniys.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.havefunace.top/Article/details/gtlcuzdwqe.html

[S02] C：变量与格式化输出
来源：http://dali.hywenlv.cn/Article/details/gteldtlmdk.html

int a = 10; printf("%d\n", a);
来源：http://dali.jlsjyb.cn/Article/details/gtkyqzkczp.html

[S03] C：读入整数
来源：http://dali.zhoulong.xyz/Article/details/gtfkmshobt.html

int x; scanf("%d", &x);
来源：http://dali.cdnleiting.top/Article/details/gtjgkjlwvn.html

[S04] C：字符串复制
来源：http://dali.fengsongda.top/Article/details/gtzyrzjqao.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gtrcodibku.html

[S05] C：字符串长度
来源：http://dali.fzhhl.top/Article/details/gtjdgswjpr.html

strlen(s)
来源：http://dali.sxryk.cn/Article/details/gtqddauxfa.html

[S06] C：字符串比较
来源：http://dali.shuidangran.top/Article/details/gtbarccnqc.html

strcmp(a, b) == 0
来源：http://dali.guannengcc.top/Article/details/gtwlhnkbcc.html

[S07] C：数组遍历求和
来源：http://dali.tian-w.cn/Article/details/gtgkqmgqcf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.tianlin.xyz/Article/details/gthbnlgkoe.html

[S08] C：动态内存分配与释放
来源：http://dali.andypj.xyz/Article/details/gtizqfyyaa.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjpfsihvh.html

[S09] C：结构体定义与初始化
来源：http://dali.jiagoushi.top/Article/details/gtltvugyfi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yonumen.top/Article/details/gtifcilwce.html

[S10] C：指针与解引用
来源：http://dali.xziqi.cn/Article/details/gtjgibbikm.html

int *p = &a;  *p = 5;
来源：http://dali.shanyushiyangtech.top/Article/details/gtziekicmo.html

[S11] C：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gterglhctd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxpwaxigg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jqgufenzy.top/Article/details/gtgcaxpnbw.html

fclose(f);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtporziytp.html

[S12] C：写文件
来源：http://dali.yueranfly.top/Article/details/gtygvrskdd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.bjfxy.top/Article/details/gtdwculenj.html

[S13] C：宏定义
来源：http://dali.zycfv.cn/Article/details/gtqvknhotv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hongshengwenyu.top/Article/details/gtaluldefo.html

[S14] C：枚举
来源：http://dali.ydzc1.top/Article/details/gtbtpuugxv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.iojbl.cn/Article/details/gtrweldumr.html

[S15] C：类型转换
来源：http://dali.sufxvd.cn/Article/details/gthtcqtzpj.html

(double) a / b
来源：http://dali.316326.xyz/Article/details/gtsdfcffme.html

[S16] C：位操作置位
来源：http://dali.bjfxy.top/Article/details/gtshwbwouj.html

x |= (1 << 3);
来源：http://dali.mhx1999.top/Article/details/gtwuhddqbu.html

[S17] C：安全拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gttzpzyhys.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hongshengwenyu.top/Article/details/gtnriuxmem.html

[S18] C：命令行参数
来源：http://dali.hnxiangtu.top/Article/details/gtrpollmbp.html

int main(int argc, char **argv)
来源：http://dali.hywenlv.cn/Article/details/gtitveoglr.html

[S19] C：快速排序
来源：http://dali.0kj1m.cn/Article/details/gtqbfacgij.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gtsivnrfqw.html

[S20] C：二分查找
来源：http://dali.jinyuanbaomall.cn/Article/details/gtygrkufen.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gtkjfvggae.html

[S21] C：字符类别判断
来源：http://dali.aizwys.cn/Article/details/gtooyxghaw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jiagoushi.top/Article/details/gtkbvgzjqz.html

[S22] C：字符串转数字
来源：http://dali.xuanzx.com/Article/details/gtomziimue.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tianlin.xyz/Article/details/gtnrcghxyx.html

[S23] C：随机数
来源：http://dali.yuanzhike.top/Article/details/gtjxzfnsoj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.pycfn.com/Article/details/gtkvvjoxvn.html

[S24] C：获取本地时间
来源：http://dali.zhoulong.xyz/Article/details/gttoynipub.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ybcxt.top/Article/details/gtauagvbpj.html

[S25] C：内存拷贝
来源：http://dali.bjfxy.top/Article/details/gtftifwsky.html

memcpy(dst, src, n);
来源：http://dali.bjfxy.top/Article/details/gtvsrquekk.html

[S26] C：内存清零
来源：http://dali.daria6918.cn/Article/details/gtcvudbxgw.html

memset(a, 0, sizeof a);
来源：http://dali.guowangkeji.top/Article/details/gtuwdaiemu.html

[S27] C：定义常量
来源：http://dali.sxryk.cn/Article/details/gtqbawzdfc.html

const double PI = 3.14159;
来源：http://dali.yvedp.cn/Article/details/gtsjjhrrcd.html

[S28] C：静态变量
来源：http://dali.cheryme.top/Article/details/gtjgfpztgx.html

static int counter = 0;
来源：http://dali.cqqwz.cn/Article/details/gttivqcknm.html

[S29] C：变参函数
来源：http://dali.yangfankeji.com/Article/details/gtlrfcchjq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.daria6918.cn/Article/details/gtssvvyzos.html

[S30] C：头文件保护
来源：http://dali.dianchejie.cn/Article/details/gtktclkkjb.html

#ifndef X_H
来源：http://dali.andypj.xyz/Article/details/gtjmynvknn.html

#define X_H
来源：http://dali.haohaochexian.top/Article/details/gtxsoftizc.html

#endif
来源：http://dali.zhiwuduotai.top/Article/details/gttnepqpbl.html

[S31] C++：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtuwwstyxb.html

#include <iostream>
来源：http://dali.0kj1m.cn/Article/details/gtnjloczlj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ydzc1.top/Article/details/gtiorcclyp.html

[S32] C++：字符串
来源：http://dali.meibo888.top/Article/details/gtkrhptfxw.html

std::string s = "hi";  s += "!";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdhzhcxac.html

[S33] C++：vector 增删
来源：http://dali.hywenlv.cn/Article/details/gtgsylfrcy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yangfankeji.com/Article/details/gtbhgfveqp.html

[S34] C++：遍历 vector
来源：http://dali.quarkkingdee.top/Article/details/gtcudcvace.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sysykeji.top/Article/details/gtlckoexpg.html

[S35] C++：map
来源：http://dali.redwolf501.top/Article/details/gtmcagmaqh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gtmzcgdfie.html

[S36] C++：unordered_map
来源：http://dali.jqgufenzy.top/Article/details/gtfwmdgqgk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gtzyfwpesk.html

[S37] C++：set
来源：http://dali.gotoacloud.top/Article/details/gtqfpcfiwr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cqqwz.cn/Article/details/gtvjvdxrki.html

[S38] C++：排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfsfnubrf.html

std::sort(v.begin(), v.end());
来源：http://dali.yanxiufei.cn/Article/details/gtbnsuukez.html

[S39] C++：自定义比较器排序
来源：http://dali.chenlongwang.top/Article/details/gtyuluouxm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xziqi.cn/Article/details/gtfoziwsyt.html

[S40] C++：查找元素
来源：http://dali.0kj1m.cn/Article/details/gtpxlwvvzf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.tanke756.top/Article/details/gtsfewmsqa.html

[S41] C++：类与构造函数
来源：http://dali.haohaochexian.top/Article/details/gtuxyjfmba.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cdnleiting.top/Article/details/gtihhbpaqn.html

[S42] C++：继承与虚函数
来源：http://dali.jqgfzy.top/Article/details/gtcptmzxym.html

class B : public Base { public: void f() override {} };
来源：http://dali.fengsongda.top/Article/details/gtkytbgtxe.html

[S43] C++：智能指针
来源：http://dali.aizwys.cn/Article/details/gtkceyakir.html

auto p = std::make_unique<int>(5);
来源：http://dali.hfpthk.cn/Article/details/gtxqmtxobb.html

[S44] C++：引用传参
来源：http://dali.gogol.net.cn/Article/details/gthghzblrj.html

void inc(int &x) { ++x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtchbvcibo.html

[S45] C++：lambda
来源：http://dali.daxiang520.top/Article/details/gtnxztxecu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtatslofrc.html

[S46] C++：函数模板
来源：http://dali.yanxiufei.cn/Article/details/gtbgrbopcp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xuanzx.com/Article/details/gttjfphawh.html

[S47] C++：结构化绑定遍历
来源：http://dali.cashguo.top/Article/details/gtbshvzkjn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenlongwang.top/Article/details/gtebmmbmke.html

[S48] C++：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtevhvizwi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.birdmap.top/Article/details/gtuokutcee.html

while (std::getline(in, line)) { }
来源：http://dali.fzhhl.top/Article/details/gtdnkhvulp.html

[S49] C++：写文件
来源：http://dali.xziqi.cn/Article/details/gtktirhmpg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.aizwys.cn/Article/details/gtxxpakeur.html

[S50] C++：格式化数字
来源：http://dali.xinyue.icu/Article/details/gtcfdtfobr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtschfwjzb.html

[S51] C++：显式类型转换
来源：http://dali.jinqigufen.top/Article/details/gtjdjedzrp.html

static_cast<double>(a) / b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtymssfgec.html

[S52] C++：const 与 noexcept
来源：http://dali.xinyue.icu/Article/details/gtwiejlerr.html

int size() const noexcept { return n_; }
来源：http://dali.zhiwuduotai.top/Article/details/gtkcvdbccf.html

[S53] C++：移动语义
来源：http://dali.xinyue.icu/Article/details/gtuzrchaga.html

std::vector<int> w = std::move(v);
来源：http://dali.dashuyun.cn/Article/details/gtfosnegqt.html

[S54] C++：异常处理
来源：http://dali.iojbl.cn/Article/details/gtwvsstuti.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj20258888.top/Article/details/gtwxmmtzzs.html

[S55] C++：结构化绑定
来源：http://dali.jyoumei.cn/Article/details/gtqqhqndfa.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhixingplan.top/Article/details/gtmtkwibar.html

[S56] C++：optional
来源：http://dali.ehwqpu.com/Article/details/gtexxyqzfk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinqigufen.top/Article/details/gtdagiajqs.html

[S57] C++：编译期常量
来源：http://dali.gogol.net.cn/Article/details/gtsfzvxyns.html

constexpr int N = 10;
来源：http://dali.andypj.xyz/Article/details/gtjxnlaefs.html

[S58] C++：命名空间
来源：http://dali.jqgufenzy.top/Article/details/gtbaujatwv.html

namespace ns { int f() { return 1; } }
来源：http://dali.ydzc1.top/Article/details/gtubyvdeqj.html

[S59] C++：静态断言
来源：http://dali.andypj.xyz/Article/details/gttfixuvcb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hongshengwenyu.top/Article/details/gttfnnznra.html

[S60] C++：遍历并删除元素
来源：http://dali.hywenlv.cn/Article/details/gtfaikbrvd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.pengpengdd.cyou/Article/details/gtcqnkoflt.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtwamiingv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hnqzz.top/Article/details/gtqjuscgzi.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtnzuycxgt.html

[T01] Kotlin：Hello World
来源：http://dali.iojbl.cn/Article/details/gtktximxld.html

println("Hello")
来源：http://dali.birdmap.top/Article/details/gtlfrancpw.html

[T02] Kotlin：变量
来源：http://dali.yuanzhike.top/Article/details/gtfmzoyqse.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.svipenyu.cn/Article/details/gtjagncmby.html

[T03] Kotlin：字符串模板
来源：http://dali.pengpengdd.cyou/Article/details/gtlsmwspyk.html

"值: $b"
来源：http://dali.zycfv.cn/Article/details/gtleizzvxl.html

[T04] Kotlin：空安全
来源：http://dali.xylfe.cn/Article/details/gtgbcnkmls.html

val n: String? = null;  n?.length
来源：http://dali.zhixingplan.top/Article/details/gtkzhxyvgt.html

[T05] Kotlin：when 表达式
来源：http://dali.aizwys.cn/Article/details/gtamdgucje.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yueranfly.top/Article/details/gtezullbwx.html

[T06] Kotlin：集合映射
来源：http://dali.yj20258888.top/Article/details/gtrywsbaps.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxnpileyx.html

[T07] Kotlin：集合过滤
来源：http://dali.wangdashe.top/Article/details/gtyaiwknco.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yonumen.top/Article/details/gtxijwamxy.html

[T08] Kotlin：数据类
来源：http://dali.c1oappe.top/Article/details/gtipvmgbuo.html

data class User(val name: String, val age: Int)
来源：http://dali.chenzaomai.com/Article/details/gtcmvnkumn.html

[T09] Kotlin：扩展函数
来源：http://dali.jinqigufen.top/Article/details/gtndovlgrp.html

fun String.exclaim() = this + "!"
来源：http://dali.daria6918.cn/Article/details/gtkrzomqzb.html

[T10] Kotlin：默认参数
来源：http://dali.hnxiangtu.top/Article/details/gtqteetzwf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sysykeji.top/Article/details/gtlfcbhqfq.html

[T11] Kotlin：协程
来源：http://dali.smart0.xyz/Article/details/gtjwbjrmdm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.andypj.xyz/Article/details/gtivultefz.html

[T12] Kotlin：解构声明
来源：http://dali.chenlongwang.top/Article/details/gtzrsolurm.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtivkbmdaa.html

[T13] Kotlin：只读 Map
来源：http://dali.guowangkeji.top/Article/details/gtnrcukodg.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gtncgcuvqs.html

[T14] Kotlin：循环
来源：http://dali.zhengqikj.top/Article/details/gtuapcpcsc.html

for (i in 1..10) println(i)
来源：http://dali.yonumen.top/Article/details/gtssgztmmr.html

[T15] Kotlin：接口
来源：http://dali.birdmap.top/Article/details/gtedvvnxri.html

interface Shape { fun area(): Double }
来源：http://dali.zhengqikj.top/Article/details/gtupnhnrxv.html

[T16] Swift：Hello World
来源：http://dali.xinyue.icu/Article/details/gtazwzcdmd.html

print("Hello")
来源：http://dali.c1oappe.top/Article/details/gttjpkpzyr.html

[T17] Swift：变量与常量
来源：http://dali.fzhhl.top/Article/details/gtpmjrhjum.html

var a = 1;  let b = 2
来源：http://dali.xuetiantiany.cn/Article/details/gtspuxgmiy.html

[T18] Swift：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gthfykdihi.html

"值: \(b)"
来源：http://dali.jinqigfzy.top/Article/details/gtzlqtxgiy.html

[T19] Swift：可选绑定
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaovrbezv.html

if let n = opt { print(n) }
来源：http://dali.0kj1m.cn/Article/details/gtfqvyqipy.html

[T20] Swift：数组操作
来源：http://dali.yangfankeji.com/Article/details/gtwuoefchm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.tian-w.cn/Article/details/gtziywuoby.html

[T21] Swift：遍历
来源：http://dali.smart0.xyz/Article/details/gtpxqdskwh.html

for x in a { print(x) }
来源：http://dali.fengsongda.top/Article/details/gtukkvyfhf.html

[T22] Swift：字典
来源：http://dali.vqdsnc.cn/Article/details/gtrcofnyxr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtknbbnxwa.html

[T23] Swift：函数
来源：http://dali.jinqigufen.top/Article/details/gtdsrltmmt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.daxiang520.top/Article/details/gtxcfejvjf.html

[T24] Swift：闭包
来源：http://dali.ybcxt.top/Article/details/gtjhnguhae.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.c1oappe.top/Article/details/gthwenxjlw.html

[T25] Swift：结构体
来源：http://dali.ybcxt.top/Article/details/gtmuqxktgh.html

struct P { var x: Int }
来源：http://dali.dianchejie.cn/Article/details/gtvbaiiyep.html

[T26] Swift：类与重写
来源：http://dali.birdmap.top/Article/details/gtjpafazyg.html

class A: Base { override func f() {} }
来源：http://dali.hnqzz.top/Article/details/gthedxmkxq.html

[T27] Swift：错误处理
来源：http://dali.iojbl.cn/Article/details/gtahnjpznu.html

do { try f() } catch { print(error) }
来源：http://dali.smart0.xyz/Article/details/gtvzbjegtj.html

[T28] Swift：枚举
来源：http://dali.jianghu66.top/Article/details/gtfxrijhrh.html

enum Color { case red, green }
来源：http://dali.daxiang520.top/Article/details/gteceicmzk.html

[T29] Swift：guard 提前返回
来源：http://dali.sweek.top/Article/details/gtjzziwzms.html

guard let x = opt else { return }
来源：http://dali.zhiwuduotai.top/Article/details/gtolwtxjhk.html

[T30] Swift：协议
来源：http://dali.feifeiyinyue.top/Article/details/gttzmewjqe.html

protocol Shape { func area() -> Double }
来源：http://dali.chenlongwang.top/Article/details/gtjzlhtotv.html

[T31] Lua：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtaoetvidr.html

print("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gtlkbpskri.html

[T32] Lua：局部变量
来源：http://dali.dianchejie.cn/Article/details/gttxssvtpq.html

local a = 1
来源：http://dali.xuanzx.com/Article/details/gtjawojlew.html

[T33] Lua：表（数组）
来源：http://dali.gogol.net.cn/Article/details/gtrevkuggp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.daria6918.cn/Article/details/gtwbkvegzz.html

[T34] Lua：遍历表
来源：http://dali.jqgufenzy.top/Article/details/gtnfdguvvd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.guannengcc.top/Article/details/gtbkvutkqf.html

[T35] Lua：字典表
来源：http://dali.yj20258.top/Article/details/gtkjovcsyn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jianghu66.top/Article/details/gtplvrbseq.html

[T36] Lua：函数
来源：http://dali.aizwys.cn/Article/details/gtjfpeiayr.html

function add(a, b) return a + b end
来源：http://dali.dianchejie.cn/Article/details/gtwvbjpvtj.html

[T37] Lua：字符串拼接
来源：http://dali.sufxvd.cn/Article/details/gtfffsbmei.html

"a" .. "b"
来源：http://dali.yuanzhike.top/Article/details/gtsddiylcy.html

[T38] Lua：条件
来源：http://dali.yj202588.top/Article/details/gtsdjxcofo.html

if x > 0 then print("正") end
来源：http://dali.xuanzx.com/Article/details/gtttndftty.html

[T39] Lua：模式匹配
来源：http://dali.smart0.xyz/Article/details/gtknlhsidj.html

string.find(s, "%d+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsxssvxsj.html

[T40] Lua：元表
来源：http://dali.hfpthk.cn/Article/details/gtiyovunzc.html

setmetatable({}, { __index = base })
来源：http://dali.nanxuanxn.top/Article/details/gtygycnjgs.html

[T41] Perl：Hello World
来源：http://dali.hfpthk.cn/Article/details/gthbookmww.html

print "Hello\n";
来源：http://dali.shangyingyoupin.top/Article/details/gtkkagzpsy.html

[T42] Perl：变量类型
来源：http://dali.birdmap.top/Article/details/gtdcppithj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.chenzaomai.com/Article/details/gthbaqqnea.html

[T43] Perl：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gtesdehelz.html

"值: $a"
来源：http://dali.zhixingplan.top/Article/details/gtyokxegvi.html

[T44] Perl：条件
来源：http://dali.snrcjt.cn/Article/details/gtcacxtwco.html

if ($a > 0) { print "正"; }
来源：http://dali.nwbrower.top/Article/details/gtqlkjukcc.html

[T45] Perl：数组遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtxuficuca.html

for my $x (@arr) { print $x; }
来源：http://dali.pycfn.com/Article/details/gtpdsfbmsb.html

[T46] Perl：哈希操作
来源：http://dali.yuxming.cn/Article/details/gtorprakxw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gotoacloud.top/Article/details/gtnlqdwapd.html

[T47] Perl：正则捕获
来源：http://dali.havefunace.top/Article/details/gteeymzair.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhongyouzk.top/Article/details/gtqrdlazbt.html

[T48] Perl：正则替换
来源：http://dali.hammf.cn/Article/details/gtrnefqute.html

$s =~ s/old/new/g;
来源：http://dali.316326.xyz/Article/details/gtqhuwweax.html

[T49] Perl：函数
来源：http://dali.sufxvd.cn/Article/details/gtyzfeakgi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gtzyugbfjx.html

[T50] Perl：逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gtvtfqcchy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yj20258.top/Article/details/gttrtdmhsq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.andypj.xyz/Article/details/gtzidlmukb.html

[T51] Scala：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtenlryjnh.html

println("Hello")
来源：http://dali.nanxinkj.top/Article/details/gtpbbhkfbk.html

[T52] Scala：变量
来源：http://dali.sysykeji.top/Article/details/gtrbruwaif.html

val a = 1;  var b = 2
来源：http://dali.zhixingplan.top/Article/details/gtqpiwlruj.html

[T53] Scala：字符串插值
来源：http://dali.sxryk.cn/Article/details/gtoayiorid.html

s"值: $b"
来源：http://dali.yuanzhike.top/Article/details/gtgkczilmk.html

[T54] Scala：集合映射
来源：http://dali.sxryk.cn/Article/details/gtuvmluewe.html


<!-- 参考信息 -->