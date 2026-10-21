代发 wailian999

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gogol.net.cn/Article/details/gtzikxtbwq.html

[R52] 统计行数
来源：http://dali.sufxvd.cn/Article/details/gtfavhzhro.html

wc -l a.txt
来源：http://dali.fengsongda.top/Article/details/gtnzcwdcjc.html

[R53] 查看文件头与实时尾
来源：http://dali.wangshuangyany.cn/Article/details/gtdnhbmkke.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shanyushiyangtech.top/Article/details/gtnppdinbg.html

[R54] 比较两个文件
来源：http://dali.yonumen.top/Article/details/gtcuqqltez.html

diff a.txt b.txt
来源：http://dali.aizwys.cn/Article/details/gtvolefvjl.html

[R55] 压缩与解压
来源：http://dali.havefunace.top/Article/details/gtnzkyushs.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tanke756.top/Article/details/gtqicsudky.html

[R56] 远程拷贝
来源：http://dali.haohaochexian.top/Article/details/gttyzexvof.html

scp file user@host:/path/
来源：http://dali.xuetiantiany.cn/Article/details/gtejrtnjeq.html

[R57] 远程执行命令
来源：http://dali.wangshuangyany.cn/Article/details/gthowdkzef.html

ssh user@host 'uptime'
来源：http://dali.jinqigufen.top/Article/details/gtvonkcnrp.html

[R58] 下载文件
来源：http://dali.aibaodan.cn/Article/details/gtfhebrcla.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yuanzhike.top/Article/details/gtjybyvtfg.html

[R59] 发 POST JSON
来源：http://dali.0kj1m.cn/Article/details/gtjbvdzuvw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gzhubu.top/Article/details/gtlpzbxayj.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj20258888.top/Article/details/gtjolyttjb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jianghu66.top/Article/details/gtoabqgdmf.html

[R61] 磁盘占用
来源：http://dali.tanke756.top/Article/details/gtmjhafaxb.html

df -h;  du -sh *
来源：http://dali.feifeiyinyue.top/Article/details/gtcjbhiikz.html

[R62] 找最占空间的文件
来源：http://dali.gotoacloud.top/Article/details/gtmxkyaaiu.html

du -ah . | sort -rh | head -10
来源：http://dali.wangdashe.top/Article/details/gtejmdaszn.html

[R63] 内存与进程
来源：http://dali.jianghu66.top/Article/details/gtcolspjea.html

free -h;  ps aux | grep nginx
来源：http://dali.zdqjudy.top/Article/details/gtsmssdttv.html

[R64] 结束进程
来源：http://dali.dianchejie.cn/Article/details/gtnrictyek.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sxryk.cn/Article/details/gthugggnyx.html

[R65] 查看端口占用
来源：http://dali.yj20258.top/Article/details/gtjwbzfdtt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zycfv.cn/Article/details/gthwiaojus.html

[R66] 定时任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsrditbir.html

crontab -e;  crontab -l
来源：http://dali.ehwqpu.com/Article/details/gtdzjzpjrm.html

[R67] 生成随机十六进制串
来源：http://dali.cucudq.cn/Article/details/gtopndkmbf.html

openssl rand -hex 16
来源：http://dali.zhiwuduotai.top/Article/details/gtgxnitnds.html

[R68] 计算文件校验值
来源：http://dali.yanxiufei.cn/Article/details/gtlsaazvhx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.meibo888.top/Article/details/gtcxaludkw.html

[R69] 生成随机密码
来源：http://dali.jinqigufen.top/Article/details/gtgcrapoed.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinqigfzy.top/Article/details/gtyelfbenu.html

[R70] 时间戳与互转
来源：http://dali.havefunace.top/Article/details/gtjdftjtgf.html

date +%s;  date -d @1700000000
来源：http://dali.gzhubu.top/Article/details/gtnhvsrzld.html

[R71] 日期格式化
来源：http://dali.wangdashe.top/Article/details/gtthriulzn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.mhx1999.top/Article/details/gtpkoeyxuh.html

[R72] 等待端口就绪
来源：http://dali.xziqi.cn/Article/details/gtlpacygrz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.wangdashe.top/Article/details/gtegrlqjus.html

[R73] 分割大日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gtratmegkl.html

split -l 1000 big.log part_
来源：http://dali.quarkkingdee.top/Article/details/gtnorxfpyc.html

[R74] 批量重命名
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxqbkqmhx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.fengsongda.top/Article/details/gtkeigcrxa.html

[R75] 导出环境变量
来源：http://dali.ivvv.top/Article/details/gtsqggwibw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sysykeji.top/Article/details/gtjcahhqzu.html

[R76] 使用临时文件
来源：http://dali.smart0.xyz/Article/details/gtosybozjn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hfpthk.cn/Article/details/gtokaxotet.html

[R77] 读取用户输入
来源：http://dali.bjfxy.top/Article/details/gtorbaeiux.html

read -rp "请输入: " ans
来源：http://dali.yonumen.top/Article/details/gtjzjdgplq.html

[R78] 交互式菜单
来源：http://dali.chenzaomai.com/Article/details/gtxlcewtpi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.vqdsnc.cn/Article/details/gtefmqnogn.html

[R79] 解析命令行选项
来源：http://dali.feifeiyinyue.top/Article/details/gtxjjzwqfg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ppjwa.cn/Article/details/gtfnqidyfh.html

[R80] 查看脚本执行耗时
来源：http://dali.zhixingplan.top/Article/details/gtqmxkpmic.html

time ./run.sh
来源：http://dali.ivvv.top/Article/details/gtjtcpvuag.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtjnrkzqdd.html

S. C / C++ 专题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjgyxncd.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtjdpzgsjh.html

[S01] C：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtlodqpqxw.html

#include <stdio.h>
来源：http://dali.daria6918.cn/Article/details/gtgtmxijff.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenlongwang.top/Article/details/gtmzoytnrx.html

[S02] C：变量与格式化输出
来源：http://dali.c1oappe.top/Article/details/gtginepbkf.html

int a = 10; printf("%d\n", a);
来源：http://dali.daxiang520.top/Article/details/gtpghqohdo.html

[S03] C：读入整数
来源：http://dali.zhongyouzk.top/Article/details/gteqcbnykb.html

int x; scanf("%d", &x);
来源：http://dali.xuetiantiany.cn/Article/details/gtxnfbuufv.html

[S04] C：字符串复制
来源：http://dali.zhiwuduotai.top/Article/details/gtbbnzffax.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ppjwa.cn/Article/details/gtzkfszbmk.html

[S05] C：字符串长度
来源：http://dali.havefunace.top/Article/details/gthpkfpjwt.html

strlen(s)
来源：http://dali.smart0.xyz/Article/details/gtgphnbngr.html

[S06] C：字符串比较
来源：http://dali.jqgufenzy.top/Article/details/gtsyqyvxpo.html

strcmp(a, b) == 0
来源：http://dali.wangshuangyany.cn/Article/details/gtqhnecjmc.html

[S07] C：数组遍历求和
来源：http://dali.nanxuanxn.top/Article/details/gtamcijsgn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.0kj1m.cn/Article/details/gthyoktjms.html

[S08] C：动态内存分配与释放
来源：http://dali.xziqi.cn/Article/details/gtrtefgycb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nanxuanxn.top/Article/details/gtvboshbut.html

[S09] C：结构体定义与初始化
来源：http://dali.zdqjudy.top/Article/details/gtxmlacszp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cashguo.top/Article/details/gtvctovdpg.html

[S10] C：指针与解引用
来源：http://dali.shuidangran.top/Article/details/gtjkiktllu.html

int *p = &a;  *p = 5;
来源：http://dali.0kj1m.cn/Article/details/gtnjlsikfz.html

[S11] C：逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gtyqhujihu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hammf.cn/Article/details/gtsvyzwnvw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.pengpengdd.cyou/Article/details/gtjgbclmnr.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gtixwmwydc.html

[S12] C：写文件
来源：http://dali.tianlin.xyz/Article/details/gtfudwxmut.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhixingplan.top/Article/details/gtjmpxnquh.html

[S13] C：宏定义
来源：http://dali.chenzaomai.com/Article/details/gtcjmhiuzq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ybcxt.top/Article/details/gthsqkcnqd.html

[S14] C：枚举
来源：http://dali.zhixingplan.top/Article/details/gtmczwkpfg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xuetiantiany.cn/Article/details/gtkixtbuba.html

[S15] C：类型转换
来源：http://dali.hywenlv.cn/Article/details/gtzctubnsm.html

(double) a / b
来源：http://dali.yj20258.top/Article/details/gtdwksewhd.html

[S16] C：位操作置位
来源：http://dali.dianchejie.cn/Article/details/gtuycvvfnl.html

x |= (1 << 3);
来源：http://dali.tian-w.cn/Article/details/gtkheputyd.html

[S17] C：安全拼接字符串
来源：http://dali.xinyue.icu/Article/details/gtpqydhqjv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenzaomai.com/Article/details/gtgxivanqm.html

[S18] C：命令行参数
来源：http://dali.smart0.xyz/Article/details/gturlvxpip.html

int main(int argc, char **argv)
来源：http://dali.bjfxy.top/Article/details/gtlqnatdhc.html

[S19] C：快速排序
来源：http://dali.quarkkingdee.top/Article/details/gtilsptqhp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cucudq.cn/Article/details/gtbbpfwsgc.html

[S20] C：二分查找
来源：http://dali.shzxlz.cn/Article/details/gtedrqgqzz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj202588.top/Article/details/gtuxqeweys.html

[S21] C：字符类别判断
来源：http://dali.zycfv.cn/Article/details/gtipmebbcy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.quarkkingdee.top/Article/details/gtpflpqqti.html

[S22] C：字符串转数字
来源：http://dali.kuanghao11.cn/Article/details/gtynxvgcfp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinqigfzy.top/Article/details/gtzapjkihx.html

[S23] C：随机数
来源：http://dali.nwbrower.top/Article/details/gtusulzetj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.andypj.xyz/Article/details/gtvxzbphow.html

[S24] C：获取本地时间
来源：http://dali.wangdashe.top/Article/details/gtcpsgfhfm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.kuanghao11.cn/Article/details/gtfjtortca.html

[S25] C：内存拷贝
来源：http://dali.zhixingplan.top/Article/details/gtmqaucbin.html

memcpy(dst, src, n);
来源：http://dali.pycfn.com/Article/details/gtmerirjzw.html

[S26] C：内存清零
来源：http://dali.pengpengdd.cyou/Article/details/gtntqifuun.html

memset(a, 0, sizeof a);
来源：http://dali.svipenyu.cn/Article/details/gtxjhxofhd.html

[S27] C：定义常量
来源：http://dali.yj20258888.top/Article/details/gtnsaqniqh.html

const double PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gtauxhtrfk.html

[S28] C：静态变量
来源：http://dali.sxryk.cn/Article/details/gtnksbobmu.html

static int counter = 0;
来源：http://dali.jinqigfzy.top/Article/details/gtxtsaakgs.html

[S29] C：变参函数
来源：http://dali.zhongyouzk.top/Article/details/gtijiavpdh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xinyue.icu/Article/details/gtygeeupqn.html

[S30] C：头文件保护
来源：http://dali.zhongyouzk.top/Article/details/gtjwcgnfbm.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gtnabpirce.html

#define X_H
来源：http://dali.jiagoushi.top/Article/details/gtiyuwkyix.html

#endif
来源：http://dali.316326.xyz/Article/details/gtpaqkmfax.html

[S31] C++：Hello World
来源：http://dali.xylfe.cn/Article/details/gtkckxrgyg.html

#include <iostream>
来源：http://dali.zhengqikj.top/Article/details/gtqkcfkicp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xuanzx.com/Article/details/gtbbbtsdaf.html

[S32] C++：字符串
来源：http://dali.guowangkeji.top/Article/details/gtsrbygtzs.html

std::string s = "hi";  s += "!";
来源：http://dali.xziqi.cn/Article/details/gtnpfgnbub.html

[S33] C++：vector 增删
来源：http://dali.jinqigufen.top/Article/details/gtkajeplul.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yueranfly.top/Article/details/gtvogmvwpx.html

[S34] C++：遍历 vector
来源：http://dali.meibo888.top/Article/details/gtqgdfmgje.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sufxvd.cn/Article/details/gtowbbuwfa.html

[S35] C++：map
来源：http://dali.jianghu66.top/Article/details/gtxzxrviky.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gtuoimkqdd.html

[S36] C++：unordered_map
来源：http://dali.jyoumei.cn/Article/details/gtjbtxlwqw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gtctvojvae.html

[S37] C++：set
来源：http://dali.sysykeji.top/Article/details/gtptikozob.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenzaomai.com/Article/details/gtkzeyzznq.html

[S38] C++：排序
来源：http://dali.gotoacloud.top/Article/details/gtrpzdjlht.html

std::sort(v.begin(), v.end());
来源：http://dali.xuanzx.com/Article/details/gtabngfscs.html

[S39] C++：自定义比较器排序
来源：http://dali.yangfankeji.com/Article/details/gtkjdduaos.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hfpthk.cn/Article/details/gtpanynjce.html

[S40] C++：查找元素
来源：http://dali.gogol.net.cn/Article/details/gtomtaxoru.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj20258888.top/Article/details/gtefsxvvac.html

[S41] C++：类与构造函数
来源：http://dali.cdnleiting.top/Article/details/gtvxowjgth.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.guowangkeji.top/Article/details/gtkgdsgmri.html

[S42] C++：继承与虚函数
来源：http://dali.yj20258.top/Article/details/gtauzrmbse.html

class B : public Base { public: void f() override {} };
来源：http://dali.pengpengdd.cyou/Article/details/gtfbhzpvcn.html

[S43] C++：智能指针
来源：http://dali.ivvv.top/Article/details/gtrayyfgyi.html

auto p = std::make_unique<int>(5);
来源：http://dali.cucudq.cn/Article/details/gtirfjlhvc.html

[S44] C++：引用传参
来源：http://dali.chenlongwang.top/Article/details/gtszlxjjyr.html

void inc(int &x) { ++x; }
来源：http://dali.jinqigufen.top/Article/details/gtipeungkt.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gtxbribgeb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shanyushiyangtech.top/Article/details/gthhvfdxwa.html

[S46] C++：函数模板
来源：http://dali.9152youxi.cn/Article/details/gtyzyvvwxp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.9152youxi.cn/Article/details/gtvgozmhoo.html

[S47] C++：结构化绑定遍历
来源：http://dali.0kj1m.cn/Article/details/gtqxefmnvf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ydzc1.top/Article/details/gtsnwhhmml.html

[S48] C++：逐行读文件
来源：http://dali.ydzc1.top/Article/details/gtgiazatvc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.mhx1999.top/Article/details/gtpkjcunxu.html

while (std::getline(in, line)) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfsbnfony.html

[S49] C++：写文件
来源：http://dali.c1oappe.top/Article/details/gtfslpwkgy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.redwolf501.top/Article/details/gtjqikavrc.html

[S50] C++：格式化数字
来源：http://dali.fzhhl.top/Article/details/gtdicyvnvs.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yvedp.cn/Article/details/gtvgzkcixf.html

[S51] C++：显式类型转换
来源：http://dali.hnxiangtu.top/Article/details/gtvtrgonqb.html

static_cast<double>(a) / b
来源：http://dali.dianchejie.cn/Article/details/gtzmrecexq.html

[S52] C++：const 与 noexcept
来源：http://dali.wangshuangyany.cn/Article/details/gtqdzouncv.html

int size() const noexcept { return n_; }
来源：http://dali.nanxuanxn.top/Article/details/gtraaxnsbb.html

[S53] C++：移动语义
来源：http://dali.andypj.xyz/Article/details/gtotnuztwv.html

std::vector<int> w = std::move(v);
来源：http://dali.dashuyun.cn/Article/details/gtqpxtpojz.html

[S54] C++：异常处理
来源：http://dali.gogol.net.cn/Article/details/gtewfjxdyw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenjidiqi.icu/Article/details/gtimxfiquc.html

[S55] C++：结构化绑定
来源：http://dali.sweek.top/Article/details/gtasorzhix.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.haohaochexian.top/Article/details/gtmmgjnjlh.html

[S56] C++：optional
来源：http://dali.c1oappe.top/Article/details/gtjpijqmjy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sufxvd.cn/Article/details/gtppkbkkmv.html

[S57] C++：编译期常量
来源：http://dali.ybcxt.top/Article/details/gtvhjupjhn.html

constexpr int N = 10;
来源：http://dali.daria6918.cn/Article/details/gtvuwnlhmr.html

[S58] C++：命名空间
来源：http://dali.hysaishi.cn/Article/details/gtvsvcpizc.html

namespace ns { int f() { return 1; } }
来源：http://dali.daria6918.cn/Article/details/gtcosoqazb.html

[S59] C++：静态断言
来源：http://dali.gaohongyu789.top/Article/details/gtzfnaaofl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cdnleiting.top/Article/details/gtkiuhopfv.html

[S60] C++：遍历并删除元素
来源：http://dali.fzhhl.top/Article/details/gtwrlprplh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shangyingyoupin.top/Article/details/gtphrqlbsl.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtuhchltes.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhiwuduotai.top/Article/details/gtinyksqjt.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtzzsviojf.html

[T01] Kotlin：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtuozenjyu.html

println("Hello")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbhckxtqv.html

[T02] Kotlin：变量
来源：http://dali.jlsjyb.cn/Article/details/gtotdbeumw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.svipenyu.cn/Article/details/gtdwutrkfj.html

[T03] Kotlin：字符串模板
来源：http://dali.316326.xyz/Article/details/gtvqxrqqym.html

"值: $b"
来源：http://dali.wangshuangyany.cn/Article/details/gtdmxvsqvi.html

[T04] Kotlin：空安全
来源：http://dali.tanke756.top/Article/details/gtpjqpfvry.html

val n: String? = null;  n?.length
来源：http://dali.ehwqpu.com/Article/details/gtstgmihdl.html

[T05] Kotlin：when 表达式
来源：http://dali.jlsjyb.cn/Article/details/gtuqxusvdo.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.0kj1m.cn/Article/details/gtluperwxa.html

[T06] Kotlin：集合映射
来源：http://dali.cqqwz.cn/Article/details/gtezawmjvo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yj20258.top/Article/details/gtjxfeusiq.html

[T07] Kotlin：集合过滤
来源：http://dali.jiagoushi.top/Article/details/gttbeoeapy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xuanzx.com/Article/details/gtviqzqree.html

[T08] Kotlin：数据类
来源：http://dali.fzhhl.top/Article/details/gtgqpayvne.html

data class User(val name: String, val age: Int)
来源：http://dali.ppjwa.cn/Article/details/gtyqvfurer.html

[T09] Kotlin：扩展函数
来源：http://dali.zhoulong.xyz/Article/details/gtfousswid.html

fun String.exclaim() = this + "!"
来源：http://dali.tian-w.cn/Article/details/gtwubnbgmw.html

[T10] Kotlin：默认参数
来源：http://dali.svipenyu.cn/Article/details/gtvrdozpnb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gaohongyu789.top/Article/details/gtorngjugy.html

[T11] Kotlin：协程
来源：http://dali.yvedp.cn/Article/details/gtozmmbqdt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.andypj.xyz/Article/details/gtdcashpfp.html

[T12] Kotlin：解构声明
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvhimbfum.html

val (a, b) = Pair(1, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtmnvreogf.html

[T13] Kotlin：只读 Map
来源：http://dali.chenlongwang.top/Article/details/gtfptmxxok.html

val m = mapOf("a" to 1)
来源：http://dali.hnqzz.top/Article/details/gtvlbmkpqy.html

[T14] Kotlin：循环
来源：http://dali.jqgufenzy.top/Article/details/gtdlrjvwst.html

for (i in 1..10) println(i)
来源：http://dali.xuetiantiany.cn/Article/details/gtfrappufm.html

[T15] Kotlin：接口
来源：http://dali.hammf.cn/Article/details/gtxlyuglur.html

interface Shape { fun area(): Double }
来源：http://dali.yj20258888.top/Article/details/gtzfznwwhl.html

[T16] Swift：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtdfdrfqbs.html

print("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gtxezcpdcc.html

[T17] Swift：变量与常量
来源：http://dali.jqgufenzy.top/Article/details/gtjqxubzqw.html

var a = 1;  let b = 2
来源：http://dali.smart0.xyz/Article/details/gtlircvmmv.html

[T18] Swift：字符串插值
来源：http://dali.yongpay.top/Article/details/gtbipirshc.html

"值: \(b)"
来源：http://dali.ivvv.top/Article/details/gtpowrtirp.html

[T19] Swift：可选绑定
来源：http://dali.ywan-chungtsiang.top/Article/details/gtszrqbtip.html

if let n = opt { print(n) }
来源：http://dali.cheryme.top/Article/details/gtcsvacgcx.html

[T20] Swift：数组操作
来源：http://dali.nanxuanxn.top/Article/details/gteuikekxw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gotoacloud.top/Article/details/gtnifygwak.html

[T21] Swift：遍历
来源：http://dali.sufxvd.cn/Article/details/gtuuaniwsx.html

for x in a { print(x) }
来源：http://dali.pengpengdd.cyou/Article/details/gtjpqsmrhy.html

[T22] Swift：字典
来源：http://dali.shuidangran.top/Article/details/gtpqgvkcdb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jqgfzy.top/Article/details/gtznosnfek.html

[T23] Swift：函数
来源：http://dali.kuanghao11.cn/Article/details/gtcuvljnch.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.guowangkeji.top/Article/details/gtycpxpyrm.html

[T24] Swift：闭包
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyyzrblqk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtvfzzkxha.html

[T25] Swift：结构体
来源：http://dali.pycfn.com/Article/details/gtetvxawdl.html

struct P { var x: Int }
来源：http://dali.mhx1999.top/Article/details/gtobfdnvvq.html

[T26] Swift：类与重写
来源：http://dali.fzhhl.top/Article/details/gtwbfcqnhz.html

class A: Base { override func f() {} }
来源：http://dali.daxiang520.top/Article/details/gtvjjrlqvv.html

[T27] Swift：错误处理
来源：http://dali.zhixingplan.top/Article/details/gtopjsjsnb.html

do { try f() } catch { print(error) }
来源：http://dali.cqqwz.cn/Article/details/gtwejreuxg.html

[T28] Swift：枚举
来源：http://dali.hywenlv.cn/Article/details/gtprcxbcbn.html

enum Color { case red, green }
来源：http://dali.nanxinkj.top/Article/details/gtjlhnvcnl.html

[T29] Swift：guard 提前返回
来源：http://dali.yuxming.cn/Article/details/gtisldwqke.html

guard let x = opt else { return }
来源：http://dali.hnqzz.top/Article/details/gtyfueozeg.html

[T30] Swift：协议
来源：http://dali.cqqwz.cn/Article/details/gtdiguspgm.html

protocol Shape { func area() -> Double }
来源：http://dali.316326.xyz/Article/details/gtebscbnwt.html

[T31] Lua：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtlhndcgvh.html

print("Hello")
来源：http://dali.tianlin.xyz/Article/details/gtuzdwdkfc.html

[T32] Lua：局部变量
来源：http://dali.shangyingyoupin.top/Article/details/gtigqujkkc.html

local a = 1
来源：http://dali.ybcxt.top/Article/details/gtzlqrkcbi.html

[T33] Lua：表（数组）
来源：http://dali.xylfe.cn/Article/details/gtwqfbrnxc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shanyushiyangtech.top/Article/details/gtxfrzczjq.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gtbejjkebk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sweek.top/Article/details/gtgcuwjtyt.html

[T35] Lua：字典表
来源：http://dali.0kj1m.cn/Article/details/gtwbemunub.html

local d = { a = 1 };  d.b = 2
来源：http://dali.aibaodan.cn/Article/details/gteniaymhp.html

[T36] Lua：函数
来源：http://dali.yangfankeji.com/Article/details/gtpxewfksx.html

function add(a, b) return a + b end
来源：http://dali.ehwqpu.com/Article/details/gtaltuobig.html

[T37] Lua：字符串拼接
来源：http://dali.jlsjyb.cn/Article/details/gtotdtarqh.html

"a" .. "b"
来源：http://dali.gaohongyu789.top/Article/details/gtfaogbvko.html

[T38] Lua：条件
来源：http://dali.sysykeji.top/Article/details/gtjomwgmzv.html

if x > 0 then print("正") end
来源：http://dali.yj20258.top/Article/details/gtigfxtctv.html

[T39] Lua：模式匹配
来源：http://dali.yj20258888.top/Article/details/gtsgjkisyc.html

string.find(s, "%d+")
来源：http://dali.svipenyu.cn/Article/details/gtcfxlefvt.html

[T40] Lua：元表
来源：http://dali.svipenyu.cn/Article/details/gtcrwdfzrn.html

setmetatable({}, { __index = base })
来源：http://dali.zdqjudy.top/Article/details/gtqnkkuyzo.html

[T41] Perl：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtklfrcoso.html

print "Hello\n";
来源：http://dali.pycfn.com/Article/details/gtpvtcbehm.html

[T42] Perl：变量类型
来源：http://dali.cashguo.top/Article/details/gtqlodvdbq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cqqwz.cn/Article/details/gtuesjkffj.html

[T43] Perl：字符串插值
来源：http://dali.ybcxt.top/Article/details/gtauhsybqy.html

"值: $a"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrjrqpmda.html

[T44] Perl：条件
来源：http://dali.zhongyouzk.top/Article/details/gttrhvmmjy.html

if ($a > 0) { print "正"; }
来源：http://dali.zhoulong.xyz/Article/details/gtpuqxstxi.html

[T45] Perl：数组遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtgybyjoll.html

for my $x (@arr) { print $x; }
来源：http://dali.shuidangran.top/Article/details/gtgqqfwhyj.html

[T46] Perl：哈希操作
来源：http://dali.zhoulong.xyz/Article/details/gtiqyiomqb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.sufxvd.cn/Article/details/gtxhlqoank.html

[T47] Perl：正则捕获
来源：http://dali.kuanghao11.cn/Article/details/gtrusortuy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yueranfly.top/Article/details/gtkiczixlh.html

[T48] Perl：正则替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxlrurkr.html

$s =~ s/old/new/g;
来源：http://dali.sysykeji.top/Article/details/gtietiocoy.html

[T49] Perl：函数
来源：http://dali.daria6918.cn/Article/details/gtgnfuqagu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hfpthk.cn/Article/details/gtidtnrdrr.html

[T50] Perl：逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gtwumcnraf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.daria6918.cn/Article/details/gtjdcedomo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cheryme.top/Article/details/gtxfdljngz.html

[T51] Scala：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtkotdnojh.html

println("Hello")
来源：http://dali.ybcxt.top/Article/details/gtxddvgcee.html

[T52] Scala：变量
来源：http://dali.yonumen.top/Article/details/gtbzvosxyo.html

val a = 1;  var b = 2
来源：http://dali.nanxinkj.top/Article/details/gtdgknqtbj.html

[T53] Scala：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gthusrtgbm.html

s"值: $b"
来源：http://dali.hammf.cn/Article/details/gtcastgxwi.html

[T54] Scala：集合映射
来源：http://dali.svipenyu.cn/Article/details/gtawettyqg.html


<!-- 参考信息 -->