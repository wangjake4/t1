代发 wailian999

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.havefunace.top/Article/details/gtfogmkzjb.html

[R52] 统计行数
来源：http://dali.bjfxy.top/Article/details/gtxokxyshf.html

wc -l a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtadciihrx.html

[R53] 查看文件头与实时尾
来源：http://dali.zhoulong.xyz/Article/details/gthzlnzuyu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.guowangkeji.top/Article/details/gtkdkaccsl.html

[R54] 比较两个文件
来源：http://dali.zhoulong.xyz/Article/details/gtbemxzdse.html

diff a.txt b.txt
来源：http://dali.snrcjt.cn/Article/details/gtwaualebg.html

[R55] 压缩与解压
来源：http://dali.sweek.top/Article/details/gtlhewnerg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xuanzx.com/Article/details/gtqosbkksb.html

[R56] 远程拷贝
来源：http://dali.daria6918.cn/Article/details/gtnpiyeafp.html

scp file user@host:/path/
来源：http://dali.shuidangran.top/Article/details/gtuwawufow.html

[R57] 远程执行命令
来源：http://dali.c1oappe.top/Article/details/gtrseitjey.html

ssh user@host 'uptime'
来源：http://dali.yonumen.top/Article/details/gtypyhcgcz.html

[R58] 下载文件
来源：http://dali.mhx1999.top/Article/details/gtzxbfkgvv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yj202588.top/Article/details/gtbhzcnuus.html

[R59] 发 POST JSON
来源：http://dali.cdnleiting.top/Article/details/gtepjcrqzz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj202588.top/Article/details/gtwcpepdst.html

[R60] 只看 HTTP 状态码
来源：http://dali.ppjwa.cn/Article/details/gtbspypkds.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhengqikj.top/Article/details/gtpudfitbp.html

[R61] 磁盘占用
来源：http://dali.hongshengwenyu.top/Article/details/gtrbshattj.html

df -h;  du -sh *
来源：http://dali.xuetiantiany.cn/Article/details/gtvzzpdprg.html

[R62] 找最占空间的文件
来源：http://dali.chenjidiqi.icu/Article/details/gtrqhjeseq.html

du -ah . | sort -rh | head -10
来源：http://dali.sufxvd.cn/Article/details/gthnyhbabq.html

[R63] 内存与进程
来源：http://dali.jqgufenzy.top/Article/details/gtskbukbtd.html

free -h;  ps aux | grep nginx
来源：http://dali.316326.xyz/Article/details/gttidsnzoi.html

[R64] 结束进程
来源：http://dali.nanxuanxn.top/Article/details/gtpjvfofvb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.guannengcc.top/Article/details/gtesbzuttk.html

[R65] 查看端口占用
来源：http://dali.sweek.top/Article/details/gtcpifwgkb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ppjwa.cn/Article/details/gtialhlkyj.html

[R66] 定时任务
来源：http://dali.yvedp.cn/Article/details/gtboldkzaa.html

crontab -e;  crontab -l
来源：http://dali.yj202588.top/Article/details/gtxdadlpls.html

[R67] 生成随机十六进制串
来源：http://dali.xziqi.cn/Article/details/gtnbkfwmlj.html

openssl rand -hex 16
来源：http://dali.gaohongyu789.top/Article/details/gtzwdvzzlw.html

[R68] 计算文件校验值
来源：http://dali.yuxming.cn/Article/details/gtpgjhygfv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtnbqfbhln.html

[R69] 生成随机密码
来源：http://dali.jinqigfzy.top/Article/details/gtebrcqgbk.html

head -c 16 /dev/urandom | base64
来源：http://dali.vqdsnc.cn/Article/details/gtcvlrtntp.html

[R70] 时间戳与互转
来源：http://dali.ivvv.top/Article/details/gtbqeagklo.html

date +%s;  date -d @1700000000
来源：http://dali.cucudq.cn/Article/details/gtzskzhhsa.html

[R71] 日期格式化
来源：http://dali.ivvv.top/Article/details/gtujynlajd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhoulong.xyz/Article/details/gtvxdqpgvu.html

[R72] 等待端口就绪
来源：http://dali.shzxlz.cn/Article/details/gtmuspaspi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xuetiantiany.cn/Article/details/gtbbtlyiit.html

[R73] 分割大日志
来源：http://dali.wangdashe.top/Article/details/gtsbnttgpb.html

split -l 1000 big.log part_
来源：http://dali.jinyuanbaomall.cn/Article/details/gtogwckgwt.html

[R74] 批量重命名
来源：http://dali.jlsjyb.cn/Article/details/gttopelfsd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.havefunace.top/Article/details/gtuzsxldux.html

[R75] 导出环境变量
来源：http://dali.xuanzx.com/Article/details/gtcmclaxhh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwqmvyhf.html

[R76] 使用临时文件
来源：http://dali.nwbrower.top/Article/details/gtjwxrcvtx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmildhgga.html

[R77] 读取用户输入
来源：http://dali.pengpengdd.cyou/Article/details/gtilseaijz.html

read -rp "请输入: " ans
来源：http://dali.birdmap.top/Article/details/gtcakhbqni.html

[R78] 交互式菜单
来源：http://dali.aibaodan.cn/Article/details/gtbweyjudn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jqgufenzy.top/Article/details/gtsxchbvym.html

[R79] 解析命令行选项
来源：http://dali.sysykeji.top/Article/details/gttyloljuo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gotoacloud.top/Article/details/gtnrdkeqpp.html

[R80] 查看脚本执行耗时
来源：http://dali.hammf.cn/Article/details/gtdxbtnped.html

time ./run.sh
来源：http://dali.zhixingplan.top/Article/details/gttqhdfqkh.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzvzrabvh.html

S. C / C++ 专题
来源：http://dali.gaohongyu789.top/Article/details/gtcnscbcrp.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtblfsrkee.html

[S01] C：Hello World
来源：http://dali.yonumen.top/Article/details/gtwcwwurox.html

#include <stdio.h>
来源：http://dali.yj20258888.top/Article/details/gtzdjszelf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.aizwys.cn/Article/details/gtbaihxlpn.html

[S02] C：变量与格式化输出
来源：http://dali.birdmap.top/Article/details/gtchhrcqkc.html

int a = 10; printf("%d\n", a);
来源：http://dali.hongshengwenyu.top/Article/details/gtyhwpzevy.html

[S03] C：读入整数
来源：http://dali.zhixingplan.top/Article/details/gtpjwwslsz.html

int x; scanf("%d", &x);
来源：http://dali.smart0.xyz/Article/details/gtznpfofbz.html

[S04] C：字符串复制
来源：http://dali.xinyue.icu/Article/details/gttcvgsbjo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.dianchejie.cn/Article/details/gtkuqwurco.html

[S05] C：字符串长度
来源：http://dali.snrcjt.cn/Article/details/gtdgcxihna.html

strlen(s)
来源：http://dali.jinqigfzy.top/Article/details/gtaizfgwik.html

[S06] C：字符串比较
来源：http://dali.yuanzhike.top/Article/details/gtutfbiryp.html

strcmp(a, b) == 0
来源：http://dali.svipenyu.cn/Article/details/gtuffowliz.html

[S07] C：数组遍历求和
来源：http://dali.nwbrower.top/Article/details/gtbtbtfsrg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xuanzx.com/Article/details/gtnwnvmgov.html

[S08] C：动态内存分配与释放
来源：http://dali.c1oappe.top/Article/details/gtouuvhjat.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhongyouzk.top/Article/details/gtfwinmxno.html

[S09] C：结构体定义与初始化
来源：http://dali.tian-w.cn/Article/details/gtnskfyirk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sxryk.cn/Article/details/gtictfqqrz.html

[S10] C：指针与解引用
来源：http://dali.yvedp.cn/Article/details/gtxlqutdly.html

int *p = &a;  *p = 5;
来源：http://dali.meibo888.top/Article/details/gtykpvmcdf.html

[S11] C：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtzysadroo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj202588.top/Article/details/gtdlcetvad.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yueranfly.top/Article/details/gtnomjdcwz.html

fclose(f);
来源：http://dali.chenzaomai.com/Article/details/gtmxlanrbi.html

[S12] C：写文件
来源：http://dali.wangdashe.top/Article/details/gtnofrwbdl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shzxlz.cn/Article/details/gtuclgjtnx.html

[S13] C：宏定义
来源：http://dali.aizwys.cn/Article/details/gtbuwjifka.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.guowangkeji.top/Article/details/gtnmmdnwrc.html

[S14] C：枚举
来源：http://dali.hywenlv.cn/Article/details/gtfcjdbbqr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.fzhhl.top/Article/details/gttnevlrbm.html

[S15] C：类型转换
来源：http://dali.zhixingplan.top/Article/details/gtvehjyemq.html

(double) a / b
来源：http://dali.cdnleiting.top/Article/details/gthjlmijne.html

[S16] C：位操作置位
来源：http://dali.hongshengwenyu.top/Article/details/gtxabzfxit.html

x |= (1 << 3);
来源：http://dali.9152youxi.cn/Article/details/gtqbggjful.html

[S17] C：安全拼接字符串
来源：http://dali.fzhhl.top/Article/details/gtnrjbloqn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shangyingyoupin.top/Article/details/gtjkeadfzw.html

[S18] C：命令行参数
来源：http://dali.iojbl.cn/Article/details/gthyjpnrzw.html

int main(int argc, char **argv)
来源：http://dali.daria6918.cn/Article/details/gtklwufdke.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gtvwqmmrpw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jianghu66.top/Article/details/gtrvjzaqmi.html

[S20] C：二分查找
来源：http://dali.wangshuangyany.cn/Article/details/gtutfecmlk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinqigfzy.top/Article/details/gtpyrhbgay.html

[S21] C：字符类别判断
来源：http://dali.jianghu66.top/Article/details/gtfxlhbify.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jqgufenzy.top/Article/details/gtrflsbhvk.html

[S22] C：字符串转数字
来源：http://dali.zhongyouzk.top/Article/details/gtgfhskcqg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.316326.xyz/Article/details/gtkllwyrcr.html

[S23] C：随机数
来源：http://dali.zhongyouzk.top/Article/details/gtqzwkdyfw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.redwolf501.top/Article/details/gtteenppjo.html

[S24] C：获取本地时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrcnxtrax.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinghuilouyu.cn/Article/details/gthmevvviu.html

[S25] C：内存拷贝
来源：http://dali.hnqzz.top/Article/details/gtusijcwpr.html

memcpy(dst, src, n);
来源：http://dali.xuanzx.com/Article/details/gtbullsgch.html

[S26] C：内存清零
来源：http://dali.havefunace.top/Article/details/gtcymdoqks.html

memset(a, 0, sizeof a);
来源：http://dali.andypj.xyz/Article/details/gtyihnmuwj.html

[S27] C：定义常量
来源：http://dali.quarkkingdee.top/Article/details/gtxakcincu.html

const double PI = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gttdzdzbsy.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gttprnecyg.html

static int counter = 0;
来源：http://dali.jqgufenzy.top/Article/details/gtboeawapw.html

[S29] C：变参函数
来源：http://dali.svipenyu.cn/Article/details/gtctcccmcl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.snrcjt.cn/Article/details/gtcaddexvk.html

[S30] C：头文件保护
来源：http://dali.zdqjudy.top/Article/details/gtfnbqsdpz.html

#ifndef X_H
来源：http://dali.aibaodan.cn/Article/details/gtkhgcptgj.html

#define X_H
来源：http://dali.sxryk.cn/Article/details/gtobcjvbno.html

#endif
来源：http://dali.gogol.net.cn/Article/details/gtstmocxrp.html

[S31] C++：Hello World
来源：http://dali.jianghu66.top/Article/details/gtykibfxln.html

#include <iostream>
来源：http://dali.gaohongyu789.top/Article/details/gtaiwjohrg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtyyddrsyv.html

[S32] C++：字符串
来源：http://dali.xylfe.cn/Article/details/gtbscxcjao.html

std::string s = "hi";  s += "!";
来源：http://dali.jqgfzy.top/Article/details/gtlknmbcoj.html

[S33] C++：vector 增删
来源：http://dali.yvedp.cn/Article/details/gtvspinjic.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ybcxt.top/Article/details/gtsmigsiht.html

[S34] C++：遍历 vector
来源：http://dali.c1oappe.top/Article/details/gthcadkzrt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.aibaodan.cn/Article/details/gtujufsjfc.html

[S35] C++：map
来源：http://dali.dianchejie.cn/Article/details/gtspnkwlxt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gtibnnmnpy.html

[S36] C++：unordered_map
来源：http://dali.jlsjyb.cn/Article/details/gtozkowhev.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gtrrkjmncu.html

[S37] C++：set
来源：http://dali.sxryk.cn/Article/details/gthvgxtrcg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sufxvd.cn/Article/details/gtsynpmxpf.html

[S38] C++：排序
来源：http://dali.sweek.top/Article/details/gtnvfrbhux.html

std::sort(v.begin(), v.end());
来源：http://dali.jqgufenzy.top/Article/details/gthzcmzkse.html

[S39] C++：自定义比较器排序
来源：http://dali.chenjidiqi.icu/Article/details/gtstnujszo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nanxinkj.top/Article/details/gtyslkxach.html

[S40] C++：查找元素
来源：http://dali.chenlongwang.top/Article/details/gtjegerqxz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj20258888.top/Article/details/gtsprylgnp.html

[S41] C++：类与构造函数
来源：http://dali.wangdashe.top/Article/details/gtafrulroy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ehwqpu.com/Article/details/gtqskqllrf.html

[S42] C++：继承与虚函数
来源：http://dali.shzxlz.cn/Article/details/gtsfcmqpxz.html

class B : public Base { public: void f() override {} };
来源：http://dali.hammf.cn/Article/details/gtgjqwsarn.html

[S43] C++：智能指针
来源：http://dali.fzhhl.top/Article/details/gtgrumgyyc.html

auto p = std::make_unique<int>(5);
来源：http://dali.ybcxt.top/Article/details/gtjljqgrbq.html

[S44] C++：引用传参
来源：http://dali.jqgfzy.top/Article/details/gtlopkyeas.html

void inc(int &x) { ++x; }
来源：http://dali.nwbrower.top/Article/details/gthvoatijx.html

[S45] C++：lambda
来源：http://dali.yangfankeji.com/Article/details/gtezvoakgw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hammf.cn/Article/details/gtppiczkpv.html

[S46] C++：函数模板
来源：http://dali.svipenyu.cn/Article/details/gtytuoiqes.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yj202588.top/Article/details/gtjscwsuua.html

[S47] C++：结构化绑定遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtojyxbiyq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.dianchejie.cn/Article/details/gtlchkackz.html

[S48] C++：逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gtjzffsdho.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ivvv.top/Article/details/gtbumhoryc.html

while (std::getline(in, line)) { }
来源：http://dali.ehwqpu.com/Article/details/gtahkfoxrp.html

[S49] C++：写文件
来源：http://dali.sufxvd.cn/Article/details/gtdokfmjgn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj20258.top/Article/details/gtihgxugpq.html

[S50] C++：格式化数字
来源：http://dali.tanke756.top/Article/details/gtznucibdb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xuanzx.com/Article/details/gtduueuylb.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gtjbyrtbhj.html

static_cast<double>(a) / b
来源：http://dali.gaohongyu789.top/Article/details/gtcyvkdnvn.html

[S52] C++：const 与 noexcept
来源：http://dali.hnxiangtu.top/Article/details/gtuqcuqree.html

int size() const noexcept { return n_; }
来源：http://dali.yuanzhike.top/Article/details/gtxvpmadwq.html

[S53] C++：移动语义
来源：http://dali.yanxiufei.cn/Article/details/gturvxpeiu.html

std::vector<int> w = std::move(v);
来源：http://dali.hywenlv.cn/Article/details/gtclvhteid.html

[S54] C++：异常处理
来源：http://dali.xuanzx.com/Article/details/gttnmokpmx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.guowangkeji.top/Article/details/gtmpjhdcdq.html

[S55] C++：结构化绑定
来源：http://dali.sysykeji.top/Article/details/gtznaepwvf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhixingplan.top/Article/details/gtquyexgsb.html

[S56] C++：optional
来源：http://dali.jqgfzy.top/Article/details/gtrxlptfga.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yuanzhike.top/Article/details/gtxyxvkysm.html

[S57] C++：编译期常量
来源：http://dali.feifeiyinyue.top/Article/details/gtuuokemap.html

constexpr int N = 10;
来源：http://dali.andypj.xyz/Article/details/gtfprqewpo.html

[S58] C++：命名空间
来源：http://dali.sxryk.cn/Article/details/gtkeyhmgul.html

namespace ns { int f() { return 1; } }
来源：http://dali.tian-w.cn/Article/details/gtsugrmfud.html

[S59] C++：静态断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgcwmvjsq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.nanxinkj.top/Article/details/gtucuhayhm.html

[S60] C++：遍历并删除元素
来源：http://dali.yj20258.top/Article/details/gtfegvvbnw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ehwqpu.com/Article/details/gtmzwmipsz.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtwtatxhgy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hnqzz.top/Article/details/gtdvulvkhe.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtcembecfj.html

[T01] Kotlin：Hello World
来源：http://dali.yuxming.cn/Article/details/gtwbdrpcsn.html

println("Hello")
来源：http://dali.dashuyun.cn/Article/details/gtabdzspnj.html

[T02] Kotlin：变量
来源：http://dali.tanke756.top/Article/details/gtugrzdazt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sysykeji.top/Article/details/gtnvenyypq.html

[T03] Kotlin：字符串模板
来源：http://dali.guowangkeji.top/Article/details/gtsqrfvpue.html

"值: $b"
来源：http://dali.cashguo.top/Article/details/gtinwtwode.html

[T04] Kotlin：空安全
来源：http://dali.ppjwa.cn/Article/details/gtxqcuacld.html

val n: String? = null;  n?.length
来源：http://dali.hysaishi.cn/Article/details/gteorquzes.html

[T05] Kotlin：when 表达式
来源：http://dali.sysykeji.top/Article/details/gtosyvcmro.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gzhubu.top/Article/details/gtebuhiwad.html

[T06] Kotlin：集合映射
来源：http://dali.daxiang520.top/Article/details/gtjroxjjrd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfvnyivwr.html

[T07] Kotlin：集合过滤
来源：http://dali.9152youxi.cn/Article/details/gtryuuaqhm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhixingplan.top/Article/details/gtwjnvotok.html

[T08] Kotlin：数据类
来源：http://dali.zdqjudy.top/Article/details/gtdcjkvnkh.html

data class User(val name: String, val age: Int)
来源：http://dali.yj20258.top/Article/details/gthcdhohpz.html

[T09] Kotlin：扩展函数
来源：http://dali.9152youxi.cn/Article/details/gtusmipidu.html

fun String.exclaim() = this + "!"
来源：http://dali.smart0.xyz/Article/details/gtmksgumpd.html

[T10] Kotlin：默认参数
来源：http://dali.gogol.net.cn/Article/details/gtxmrrfyuy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.aibaodan.cn/Article/details/gtiritwrei.html

[T11] Kotlin：协程
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxvtvfxom.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.feifeiyinyue.top/Article/details/gtbdrxjoth.html

[T12] Kotlin：解构声明
来源：http://dali.nwbrower.top/Article/details/gtnfujkkfa.html

val (a, b) = Pair(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gtvqjiklvy.html

[T13] Kotlin：只读 Map
来源：http://dali.dashuyun.cn/Article/details/gtcrmtvxri.html

val m = mapOf("a" to 1)
来源：http://dali.andypj.xyz/Article/details/gtpsjepzaq.html

[T14] Kotlin：循环
来源：http://dali.gzhubu.top/Article/details/gtxsomnfdk.html

for (i in 1..10) println(i)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtvzxnlx.html

[T15] Kotlin：接口
来源：http://dali.hywenlv.cn/Article/details/gtszclccdc.html

interface Shape { fun area(): Double }
来源：http://dali.pengpengdd.cyou/Article/details/gtvvafjdnv.html

[T16] Swift：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gthxlotvxq.html

print("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtjtqxsbqp.html

[T17] Swift：变量与常量
来源：http://dali.pengpengdd.cyou/Article/details/gtcgpuxied.html

var a = 1;  let b = 2
来源：http://dali.xylfe.cn/Article/details/gturpwqjoi.html

[T18] Swift：字符串插值
来源：http://dali.cashguo.top/Article/details/gtjxohpakp.html

"值: \(b)"
来源：http://dali.wangshuangyany.cn/Article/details/gtzbdnfbgw.html

[T19] Swift：可选绑定
来源：http://dali.gaohongyu789.top/Article/details/gtgrlasnph.html

if let n = opt { print(n) }
来源：http://dali.redwolf501.top/Article/details/gtwaessxwm.html

[T20] Swift：数组操作
来源：http://dali.sysykeji.top/Article/details/gtbxmlbxgw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cdnleiting.top/Article/details/gtqjbdnnaz.html

[T21] Swift：遍历
来源：http://dali.nanxuanxn.top/Article/details/gtrdlqyqla.html

for x in a { print(x) }
来源：http://dali.guowangkeji.top/Article/details/gtmzszjydh.html

[T22] Swift：字典
来源：http://dali.tian-w.cn/Article/details/gtjozysgyt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gogol.net.cn/Article/details/gtqnzwkrdy.html

[T23] Swift：函数
来源：http://dali.9152youxi.cn/Article/details/gtbpoigcjc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gogol.net.cn/Article/details/gtrvnazckv.html

[T24] Swift：闭包
来源：http://dali.zhiwuduotai.top/Article/details/gtqoowwpnn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.nanxinkj.top/Article/details/gtnrmwvtfq.html

[T25] Swift：结构体
来源：http://dali.smart0.xyz/Article/details/gtwuacwzkq.html

struct P { var x: Int }
来源：http://dali.haohaochexian.top/Article/details/gtvytsurjf.html

[T26] Swift：类与重写
来源：http://dali.tianlin.xyz/Article/details/gtvpyqjeny.html

class A: Base { override func f() {} }
来源：http://dali.jqgufenzy.top/Article/details/gtyzeucgps.html

[T27] Swift：错误处理
来源：http://dali.zdqjudy.top/Article/details/gtsblgbikb.html

do { try f() } catch { print(error) }
来源：http://dali.yj20258888.top/Article/details/gtyabdsqwz.html

[T28] Swift：枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutiurzkk.html

enum Color { case red, green }
来源：http://dali.zhixingplan.top/Article/details/gtnmcdkltj.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gtqsvdprmj.html

guard let x = opt else { return }
来源：http://dali.316326.xyz/Article/details/gtgiiukebm.html

[T30] Swift：协议
来源：http://dali.meibo888.top/Article/details/gtakhvdfhn.html

protocol Shape { func area() -> Double }
来源：http://dali.hfpthk.cn/Article/details/gtjcvrcqdb.html

[T31] Lua：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gttaugzyed.html

print("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gtqvrhbibj.html

[T32] Lua：局部变量
来源：http://dali.meibo888.top/Article/details/gtcaqhjofi.html

local a = 1
来源：http://dali.pycfn.com/Article/details/gttbrmekrb.html

[T33] Lua：表（数组）
来源：http://dali.chenzaomai.com/Article/details/gtvrmxipru.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xziqi.cn/Article/details/gtjybygyti.html

[T34] Lua：遍历表
来源：http://dali.zycfv.cn/Article/details/gtkmzethxr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.chenzaomai.com/Article/details/gtntsfxiie.html

[T35] Lua：字典表
来源：http://dali.aizwys.cn/Article/details/gtmqmntfcp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sweek.top/Article/details/gtqzxcmfnn.html

[T36] Lua：函数
来源：http://dali.zhoulong.xyz/Article/details/gthyuafkzn.html

function add(a, b) return a + b end
来源：http://dali.jyoumei.cn/Article/details/gtyrfezvas.html

[T37] Lua：字符串拼接
来源：http://dali.bjfxy.top/Article/details/gtityfibmo.html

"a" .. "b"
来源：http://dali.shzxlz.cn/Article/details/gtxojcvqgh.html

[T38] Lua：条件
来源：http://dali.dianchejie.cn/Article/details/gtsvgutyik.html

if x > 0 then print("正") end
来源：http://dali.shanyushiyangtech.top/Article/details/gtltwicnth.html

[T39] Lua：模式匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwrasqcra.html

string.find(s, "%d+")
来源：http://dali.cheryme.top/Article/details/gtdsohumhe.html

[T40] Lua：元表
来源：http://dali.aizwys.cn/Article/details/gtiqbhixfg.html

setmetatable({}, { __index = base })
来源：http://dali.shangyingyoupin.top/Article/details/gtfgbrczpn.html

[T41] Perl：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtanfguahv.html

print "Hello\n";
来源：http://dali.chenlongwang.top/Article/details/gtviiwtvlk.html

[T42] Perl：变量类型
来源：http://dali.kuanghao11.cn/Article/details/gtsxengroz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gotoacloud.top/Article/details/gtwiwxomea.html

[T43] Perl：字符串插值
来源：http://dali.daxiang520.top/Article/details/gtbgbpgvtu.html

"值: $a"
来源：http://dali.shangyingyoupin.top/Article/details/gtyvcbyzop.html

[T44] Perl：条件
来源：http://dali.jiagoushi.top/Article/details/gtxbzfiswv.html

if ($a > 0) { print "正"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvpqppxo.html

[T45] Perl：数组遍历
来源：http://dali.aibaodan.cn/Article/details/gtfmefkmul.html

for my $x (@arr) { print $x; }
来源：http://dali.kuanghao11.cn/Article/details/gtofetdnky.html

[T46] Perl：哈希操作
来源：http://dali.dianchejie.cn/Article/details/gtcxtnednd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhongyouzk.top/Article/details/gtpmalmzko.html

[T47] Perl：正则捕获
来源：http://dali.cdnleiting.top/Article/details/gtumcwfynj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.nwbrower.top/Article/details/gtijirnafc.html

[T48] Perl：正则替换
来源：http://dali.yuanzhike.top/Article/details/gtmgzumddu.html

$s =~ s/old/new/g;
来源：http://dali.ivvv.top/Article/details/gttafxarig.html

[T49] Perl：函数
来源：http://dali.yj20258.top/Article/details/gtlbnqriov.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gtlfyudiwz.html

[T50] Perl：逐行读文件
来源：http://dali.xinyue.icu/Article/details/gtgqphtdol.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.dianchejie.cn/Article/details/gtxruyfudw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.chenzaomai.com/Article/details/gtfdqqaaim.html

[T51] Scala：Hello World
来源：http://dali.gogol.net.cn/Article/details/gthmxfgzoj.html

println("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttegiutog.html

[T52] Scala：变量
来源：http://dali.zhengqikj.top/Article/details/gtjoiiqwnq.html

val a = 1;  var b = 2
来源：http://dali.daria6918.cn/Article/details/gtcctepcdh.html

[T53] Scala：字符串插值
来源：http://dali.9152youxi.cn/Article/details/gtgmtijaex.html

s"值: $b"
来源：http://dali.yj20258888.top/Article/details/gtbsoqvybm.html

[T54] Scala：集合映射
来源：http://dali.jinqigufen.top/Article/details/gtwpttubjt.html


<!-- 参考信息 -->