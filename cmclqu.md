代发 wailian999

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.c1oappe.top/Article/details/gtzrvovjyl.html

[R52] 统计行数
来源：http://dali.smart0.xyz/Article/details/gtezgsvyht.html

wc -l a.txt
来源：http://dali.wangdashe.top/Article/details/gtdbhqtnrv.html

[R53] 查看文件头与实时尾
来源：http://dali.jiagoushi.top/Article/details/gtfijsxoed.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tanke756.top/Article/details/gtngzrlsdd.html

[R54] 比较两个文件
来源：http://dali.xinyue.icu/Article/details/gtdcgydzlg.html

diff a.txt b.txt
来源：http://dali.jlsjyb.cn/Article/details/gtlcfceaha.html

[R55] 压缩与解压
来源：http://dali.fzhhl.top/Article/details/gtekxkjxfz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jlsjyb.cn/Article/details/gtonqhpzjk.html

[R56] 远程拷贝
来源：http://dali.ydzc1.top/Article/details/gtzeuglpah.html

scp file user@host:/path/
来源：http://dali.gzhubu.top/Article/details/gtkjugrtwa.html

[R57] 远程执行命令
来源：http://dali.smart0.xyz/Article/details/gtmamaiukf.html

ssh user@host 'uptime'
来源：http://dali.fzhhl.top/Article/details/gthuylrmay.html

[R58] 下载文件
来源：http://dali.aizwys.cn/Article/details/gtenitucif.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinqigfzy.top/Article/details/gtgijebvwk.html

[R59] 发 POST JSON
来源：http://dali.zhixingplan.top/Article/details/gtagvhjjib.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.quarkkingdee.top/Article/details/gtnuqjiagf.html

[R60] 只看 HTTP 状态码
来源：http://dali.sweek.top/Article/details/gtwmnywcvt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yuanzhike.top/Article/details/gtuceoxgdf.html

[R61] 磁盘占用
来源：http://dali.zhiwuduotai.top/Article/details/gthsqeoeqc.html

df -h;  du -sh *
来源：http://dali.yanxiufei.cn/Article/details/gtcwemviwa.html

[R62] 找最占空间的文件
来源：http://dali.haohaochexian.top/Article/details/gtrupyhrik.html

du -ah . | sort -rh | head -10
来源：http://dali.gogol.net.cn/Article/details/gtvgphppbz.html

[R63] 内存与进程
来源：http://dali.wangshuangyany.cn/Article/details/gtewzalgdk.html

free -h;  ps aux | grep nginx
来源：http://dali.yj20258888.top/Article/details/gtdqhclcje.html

[R64] 结束进程
来源：http://dali.yj20258.top/Article/details/gtidlptoej.html

kill -9 $(pgrep -f app.py)
来源：http://dali.guannengcc.top/Article/details/gthitnobyr.html

[R65] 查看端口占用
来源：http://dali.kuanghao11.cn/Article/details/gtptpnqrfm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.316326.xyz/Article/details/gtplzntqvg.html

[R66] 定时任务
来源：http://dali.tian-w.cn/Article/details/gtwmdtrphx.html

crontab -e;  crontab -l
来源：http://dali.gotoacloud.top/Article/details/gtjactjvrx.html

[R67] 生成随机十六进制串
来源：http://dali.mhx1999.top/Article/details/gtttrgquqg.html

openssl rand -hex 16
来源：http://dali.fzhhl.top/Article/details/gtuoricgwf.html

[R68] 计算文件校验值
来源：http://dali.svipenyu.cn/Article/details/gtrskqqngn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtjbmgfvjj.html

[R69] 生成随机密码
来源：http://dali.chenlongwang.top/Article/details/gtgzblpxde.html

head -c 16 /dev/urandom | base64
来源：http://dali.kuanghao11.cn/Article/details/gtnxbdegmo.html

[R70] 时间戳与互转
来源：http://dali.yongpay.top/Article/details/gttwzpafrd.html

date +%s;  date -d @1700000000
来源：http://dali.pycfn.com/Article/details/gtumzqdpig.html

[R71] 日期格式化
来源：http://dali.daxiang520.top/Article/details/gtciemlhak.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xinyue.icu/Article/details/gthjycmsda.html

[R72] 等待端口就绪
来源：http://dali.yvedp.cn/Article/details/gtvgddwadm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ydzc1.top/Article/details/gtzdcdzuxu.html

[R73] 分割大日志
来源：http://dali.gzhubu.top/Article/details/gtombgtkyu.html

split -l 1000 big.log part_
来源：http://dali.9152youxi.cn/Article/details/gtixmiyutl.html

[R74] 批量重命名
来源：http://dali.zdqjudy.top/Article/details/gtfjqbmlcs.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shuidangran.top/Article/details/gtdmxdwemt.html

[R75] 导出环境变量
来源：http://dali.cashguo.top/Article/details/gtghhlvakp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzlerrfqw.html

[R76] 使用临时文件
来源：http://dali.ppjwa.cn/Article/details/gtgktzvlmj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenjidiqi.icu/Article/details/gtwezyjliy.html

[R77] 读取用户输入
来源：http://dali.gogol.net.cn/Article/details/gtifjjgwfg.html

read -rp "请输入: " ans
来源：http://dali.ydzc1.top/Article/details/gtqjdvilvg.html

[R78] 交互式菜单
来源：http://dali.zhoulong.xyz/Article/details/gtpacuyrku.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnxyzecov.html

[R79] 解析命令行选项
来源：http://dali.jqgfzy.top/Article/details/gtdxqvhiyr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.tianlin.xyz/Article/details/gtjlidfnbl.html

[R80] 查看脚本执行耗时
来源：http://dali.tianlin.xyz/Article/details/gtaupstoxa.html

time ./run.sh
来源：http://dali.fengsongda.top/Article/details/gtdshjgavi.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtyzzlriar.html

S. C / C++ 专题
来源：http://dali.yj202588.top/Article/details/gtvqyxxjpv.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtemgavwni.html

[S01] C：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtvocsbpmo.html

#include <stdio.h>
来源：http://dali.ywan-chungtsiang.top/Article/details/gtugcasijp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tanke756.top/Article/details/gtleomkbna.html

[S02] C：变量与格式化输出
来源：http://dali.sweek.top/Article/details/gtdxtlxpaf.html

int a = 10; printf("%d\n", a);
来源：http://dali.xuetiantiany.cn/Article/details/gtvvctnycd.html

[S03] C：读入整数
来源：http://dali.ivvv.top/Article/details/gtjfmjigzf.html

int x; scanf("%d", &x);
来源：http://dali.gogol.net.cn/Article/details/gtmoiehhrr.html

[S04] C：字符串复制
来源：http://dali.nwbrower.top/Article/details/gtgbxjnytx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cqqwz.cn/Article/details/gtmrmhnqtk.html

[S05] C：字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gtaloxwifk.html

strlen(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtenwdigai.html

[S06] C：字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gtaxnssvtr.html

strcmp(a, b) == 0
来源：http://dali.gotoacloud.top/Article/details/gtftpgubxv.html

[S07] C：数组遍历求和
来源：http://dali.redwolf501.top/Article/details/gtjnuncwjj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenzaomai.com/Article/details/gtfgpjvmzh.html

[S08] C：动态内存分配与释放
来源：http://dali.gaohongyu789.top/Article/details/gtstkbmkeh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhiwuduotai.top/Article/details/gttpybhmua.html

[S09] C：结构体定义与初始化
来源：http://dali.hfpthk.cn/Article/details/gtlcivpztr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yangfankeji.com/Article/details/gtfekionne.html

[S10] C：指针与解引用
来源：http://dali.guannengcc.top/Article/details/gtjmsdrfom.html

int *p = &a;  *p = 5;
来源：http://dali.gotoacloud.top/Article/details/gtrsocoxti.html

[S11] C：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtdyciydak.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hfpthk.cn/Article/details/gtlkomanxz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.daria6918.cn/Article/details/gtegotzgkz.html

fclose(f);
来源：http://dali.ybcxt.top/Article/details/gtdyvvzhju.html

[S12] C：写文件
来源：http://dali.wangshuangyany.cn/Article/details/gtrgoxkaxk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sufxvd.cn/Article/details/gtaobgadwy.html

[S13] C：宏定义
来源：http://dali.yonumen.top/Article/details/gtyvygqwrj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gaohongyu789.top/Article/details/gtqzqsvdci.html

[S14] C：枚举
来源：http://dali.jianghu66.top/Article/details/gtqvuwrgee.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.svipenyu.cn/Article/details/gtdxwhwwfc.html

[S15] C：类型转换
来源：http://dali.tanke756.top/Article/details/gtqdtzinhi.html

(double) a / b
来源：http://dali.yvedp.cn/Article/details/gtfrwalzyz.html

[S16] C：位操作置位
来源：http://dali.fzhhl.top/Article/details/gtiyxarjlj.html

x |= (1 << 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtsyxjebwz.html

[S17] C：安全拼接字符串
来源：http://dali.sysykeji.top/Article/details/gtqlehdcxx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jlsjyb.cn/Article/details/gtexbcjilw.html

[S18] C：命令行参数
来源：http://dali.zhongyouzk.top/Article/details/gtnahimhdh.html

int main(int argc, char **argv)
来源：http://dali.tian-w.cn/Article/details/gtnmlxwjzl.html

[S19] C：快速排序
来源：http://dali.pycfn.com/Article/details/gtrlfubwhj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gtlmmthdwe.html

[S20] C：二分查找
来源：http://dali.zhoulong.xyz/Article/details/gtghgycnka.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hammf.cn/Article/details/gtwroehail.html

[S21] C：字符类别判断
来源：http://dali.nanxinkj.top/Article/details/gthwnlmywb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.vqdsnc.cn/Article/details/gttgbxyakh.html

[S22] C：字符串转数字
来源：http://dali.cucudq.cn/Article/details/gtypydtlzc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.guowangkeji.top/Article/details/gtdrjdcpfv.html

[S23] C：随机数
来源：http://dali.nanxinkj.top/Article/details/gtavlamefk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.kuanghao11.cn/Article/details/gtmndecrmw.html

[S24] C：获取本地时间
来源：http://dali.vqdsnc.cn/Article/details/gtaopzbcgo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhongyouzk.top/Article/details/gtuuhgrqgo.html

[S25] C：内存拷贝
来源：http://dali.sweek.top/Article/details/gtzzprtvbj.html

memcpy(dst, src, n);
来源：http://dali.yvedp.cn/Article/details/gtztkruhxz.html

[S26] C：内存清零
来源：http://dali.ybcxt.top/Article/details/gtpvvqwhxu.html

memset(a, 0, sizeof a);
来源：http://dali.birdmap.top/Article/details/gtfijjwxuz.html

[S27] C：定义常量
来源：http://dali.cashguo.top/Article/details/gtznhnrtup.html

const double PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtplgoqwvy.html

[S28] C：静态变量
来源：http://dali.316326.xyz/Article/details/gtdjiskfbk.html

static int counter = 0;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmcgozfrw.html

[S29] C：变参函数
来源：http://dali.yangfankeji.com/Article/details/gtvtyrjbcn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.andypj.xyz/Article/details/gtbghitnop.html

[S30] C：头文件保护
来源：http://dali.shanyushiyangtech.top/Article/details/gtcwvugkhq.html

#ifndef X_H
来源：http://dali.haohaochexian.top/Article/details/gtzxxagqac.html

#define X_H
来源：http://dali.xziqi.cn/Article/details/gtusqcqvlf.html

#endif
来源：http://dali.jqgufenzy.top/Article/details/gtqbrhustt.html

[S31] C++：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtwifttyaf.html

#include <iostream>
来源：http://dali.dashuyun.cn/Article/details/gthdxwhllc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yvedp.cn/Article/details/gtkfnnhrio.html

[S32] C++：字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbpclhrn.html

std::string s = "hi";  s += "!";
来源：http://dali.quarkkingdee.top/Article/details/gtehnzqfud.html

[S33] C++：vector 增删
来源：http://dali.jinghuilouyu.cn/Article/details/gtpegoglvb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.bjfxy.top/Article/details/gtzizimrqg.html

[S34] C++：遍历 vector
来源：http://dali.zhengqikj.top/Article/details/gthzsbbbyc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.smart0.xyz/Article/details/gtraicofcz.html

[S35] C++：map
来源：http://dali.shuidangran.top/Article/details/gtfxxshcsq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtbmdlrmfd.html

[S36] C++：unordered_map
来源：http://dali.zdqjudy.top/Article/details/gtcozhmagr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtneljebvj.html

[S37] C++：set
来源：http://dali.guannengcc.top/Article/details/gtbxpaxtbb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhongyouzk.top/Article/details/gthxufbvqv.html

[S38] C++：排序
来源：http://dali.cheryme.top/Article/details/gtsidyjbeh.html

std::sort(v.begin(), v.end());
来源：http://dali.cqqwz.cn/Article/details/gttrwkwswo.html

[S39] C++：自定义比较器排序
来源：http://dali.svipenyu.cn/Article/details/gtwfugglps.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hywenlv.cn/Article/details/gturyprcud.html

[S40] C++：查找元素
来源：http://dali.316326.xyz/Article/details/gtbtqqahcd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgsmoqrom.html

[S41] C++：类与构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gtufrsysmb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.smart0.xyz/Article/details/gtvykxfknz.html

[S42] C++：继承与虚函数
来源：http://dali.aibaodan.cn/Article/details/gtazypngqx.html

class B : public Base { public: void f() override {} };
来源：http://dali.nwbrower.top/Article/details/gtzkanpvvv.html

[S43] C++：智能指针
来源：http://dali.cdnleiting.top/Article/details/gtkugmuwjj.html

auto p = std::make_unique<int>(5);
来源：http://dali.andypj.xyz/Article/details/gtadxhquus.html

[S44] C++：引用传参
来源：http://dali.zhaomingkeji.xyz/Article/details/gtudvxirwv.html

void inc(int &x) { ++x; }
来源：http://dali.smart0.xyz/Article/details/gtrkyesren.html

[S45] C++：lambda
来源：http://dali.bjfxy.top/Article/details/gthicxmgvv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.bjfxy.top/Article/details/gtywdvwqey.html

[S46] C++：函数模板
来源：http://dali.fengsongda.top/Article/details/gtffzcxkcf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ivvv.top/Article/details/gtgabasyxn.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtejkugkeo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinqigufen.top/Article/details/gtkggihbzp.html

[S48] C++：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gtuisjlbhy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.fengsongda.top/Article/details/gtufvgyqmr.html

while (std::getline(in, line)) { }
来源：http://dali.tianlin.xyz/Article/details/gtukfdygjn.html

[S49] C++：写文件
来源：http://dali.zhongyouzk.top/Article/details/gtntwclymj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gzhubu.top/Article/details/gtnfwmhehk.html

[S50] C++：格式化数字
来源：http://dali.xuetiantiany.cn/Article/details/gtucocizaq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.daxiang520.top/Article/details/gtxhskhaqi.html

[S51] C++：显式类型转换
来源：http://dali.nanxinkj.top/Article/details/gtskpszory.html

static_cast<double>(a) / b
来源：http://dali.yonumen.top/Article/details/gtjnvpjrgv.html

[S52] C++：const 与 noexcept
来源：http://dali.xylfe.cn/Article/details/gtltvazafm.html

int size() const noexcept { return n_; }
来源：http://dali.zhiwuduotai.top/Article/details/gtigbhkrle.html

[S53] C++：移动语义
来源：http://dali.fzhhl.top/Article/details/gtxbxrivaq.html

std::vector<int> w = std::move(v);
来源：http://dali.zycfv.cn/Article/details/gtpltxwwta.html

[S54] C++：异常处理
来源：http://dali.birdmap.top/Article/details/gtinynfaqb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenzaomai.com/Article/details/gtntajzaea.html

[S55] C++：结构化绑定
来源：http://dali.andypj.xyz/Article/details/gtxkyboqvx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.birdmap.top/Article/details/gtglatcyws.html

[S56] C++：optional
来源：http://dali.jinqigfzy.top/Article/details/gthmdqlwmv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xylfe.cn/Article/details/gtefdqgstn.html

[S57] C++：编译期常量
来源：http://dali.zhoulong.xyz/Article/details/gtuzxkhlzt.html

constexpr int N = 10;
来源：http://dali.bjfxy.top/Article/details/gtgqkohuat.html

[S58] C++：命名空间
来源：http://dali.snrcjt.cn/Article/details/gttunfoxzq.html

namespace ns { int f() { return 1; } }
来源：http://dali.kuanghao11.cn/Article/details/gtgswmmjls.html

[S59] C++：静态断言
来源：http://dali.vqdsnc.cn/Article/details/gtxplvjhdx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.9152youxi.cn/Article/details/gtfncrcmfe.html

[S60] C++：遍历并删除元素
来源：http://dali.9152youxi.cn/Article/details/gtideswyjj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shangyingyoupin.top/Article/details/gtnzmqyawp.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtzrmcoafj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gzhubu.top/Article/details/gtqiedtpoo.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtxdmulvuz.html

[T01] Kotlin：Hello World
来源：http://dali.yj20258.top/Article/details/gttgeurwoe.html

println("Hello")
来源：http://dali.guowangkeji.top/Article/details/gtigmvkxuf.html

[T02] Kotlin：变量
来源：http://dali.yuxming.cn/Article/details/gtfxpmrphu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jyoumei.cn/Article/details/gtlvisaeba.html

[T03] Kotlin：字符串模板
来源：http://dali.cqqwz.cn/Article/details/gtmqbejhhj.html

"值: $b"
来源：http://dali.hywenlv.cn/Article/details/gtwawtckjv.html

[T04] Kotlin：空安全
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpmehpdbw.html

val n: String? = null;  n?.length
来源：http://dali.andypj.xyz/Article/details/gtzrganlre.html

[T05] Kotlin：when 表达式
来源：http://dali.zhoulong.xyz/Article/details/gtzqercytv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hywenlv.cn/Article/details/gtnffmmfva.html

[T06] Kotlin：集合映射
来源：http://dali.hnxiangtu.top/Article/details/gthmozqrfp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.tianlin.xyz/Article/details/gtdoxhyewq.html

[T07] Kotlin：集合过滤
来源：http://dali.yuxming.cn/Article/details/gtfaggtrig.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sufxvd.cn/Article/details/gtzmecvggm.html

[T08] Kotlin：数据类
来源：http://dali.meibo888.top/Article/details/gtrevuwoda.html

data class User(val name: String, val age: Int)
来源：http://dali.vqdsnc.cn/Article/details/gtseetjhzd.html

[T09] Kotlin：扩展函数
来源：http://dali.gzhubu.top/Article/details/gtrwtvwrgm.html

fun String.exclaim() = this + "!"
来源：http://dali.sweek.top/Article/details/gtfkjowlmw.html

[T10] Kotlin：默认参数
来源：http://dali.aizwys.cn/Article/details/gtkbddprob.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj20258.top/Article/details/gtwggqirgu.html

[T11] Kotlin：协程
来源：http://dali.c1oappe.top/Article/details/gtoyqorqls.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cucudq.cn/Article/details/gtqycfghej.html

[T12] Kotlin：解构声明
来源：http://dali.cdnleiting.top/Article/details/gtlzivtlra.html

val (a, b) = Pair(1, 2)
来源：http://dali.zdqjudy.top/Article/details/gtdfcrrhks.html

[T13] Kotlin：只读 Map
来源：http://dali.gogol.net.cn/Article/details/gtqbpulcqn.html

val m = mapOf("a" to 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtwnbkyiih.html

[T14] Kotlin：循环
来源：http://dali.cucudq.cn/Article/details/gtlhgkcskp.html

for (i in 1..10) println(i)
来源：http://dali.wangdashe.top/Article/details/gtzbmcprgo.html

[T15] Kotlin：接口
来源：http://dali.shanyushiyangtech.top/Article/details/gtsvsuvhko.html

interface Shape { fun area(): Double }
来源：http://dali.daxiang520.top/Article/details/gtmiqvzszs.html

[T16] Swift：Hello World
来源：http://dali.ybcxt.top/Article/details/gtaoxghhqg.html

print("Hello")
来源：http://dali.havefunace.top/Article/details/gtbfvlrgkd.html

[T17] Swift：变量与常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhovwspd.html

var a = 1;  let b = 2
来源：http://dali.0kj1m.cn/Article/details/gtseaqgztz.html

[T18] Swift：字符串插值
来源：http://dali.guowangkeji.top/Article/details/gtigjcoupr.html

"值: \(b)"
来源：http://dali.shanyushiyangtech.top/Article/details/gtlvefifvf.html

[T19] Swift：可选绑定
来源：http://dali.ydzc1.top/Article/details/gtxqfnbkzv.html

if let n = opt { print(n) }
来源：http://dali.0kj1m.cn/Article/details/gtdihcuqkg.html

[T20] Swift：数组操作
来源：http://dali.quarkkingdee.top/Article/details/gtnigjvrye.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.smart0.xyz/Article/details/gtmhnuqijt.html

[T21] Swift：遍历
来源：http://dali.redwolf501.top/Article/details/gthhwcvujn.html

for x in a { print(x) }
来源：http://dali.zhiwuduotai.top/Article/details/gtnvozlxyl.html

[T22] Swift：字典
来源：http://dali.jlsjyb.cn/Article/details/gtorxjxkgb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.pycfn.com/Article/details/gtrxiuehbp.html

[T23] Swift：函数
来源：http://dali.yuanzhike.top/Article/details/gtveocrbpu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.svipenyu.cn/Article/details/gtcrzaypjq.html

[T24] Swift：闭包
来源：http://dali.jinqigfzy.top/Article/details/gthqqkuevn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtfwbczxpa.html

[T25] Swift：结构体
来源：http://dali.zhiwuduotai.top/Article/details/gtkbqljhbw.html

struct P { var x: Int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrswwtkaa.html

[T26] Swift：类与重写
来源：http://dali.ivvv.top/Article/details/gtdjabaawt.html

class A: Base { override func f() {} }
来源：http://dali.daxiang520.top/Article/details/gtorhfnzmi.html

[T27] Swift：错误处理
来源：http://dali.redwolf501.top/Article/details/gtkaumxhdk.html

do { try f() } catch { print(error) }
来源：http://dali.hnqzz.top/Article/details/gtzgipnrhk.html

[T28] Swift：枚举
来源：http://dali.chenjidiqi.icu/Article/details/gtmlkhlrmy.html

enum Color { case red, green }
来源：http://dali.yongpay.top/Article/details/gtomtrnyum.html

[T29] Swift：guard 提前返回
来源：http://dali.chenzaomai.com/Article/details/gthymtghlv.html

guard let x = opt else { return }
来源：http://dali.shzxlz.cn/Article/details/gtjyxtbuhj.html

[T30] Swift：协议
来源：http://dali.quarkkingdee.top/Article/details/gttyryfewu.html

protocol Shape { func area() -> Double }
来源：http://dali.fzhhl.top/Article/details/gtdxntynkw.html

[T31] Lua：Hello World
来源：http://dali.xylfe.cn/Article/details/gthdfnaibm.html

print("Hello")
来源：http://dali.xinyue.icu/Article/details/gtqwnjnpkk.html

[T32] Lua：局部变量
来源：http://dali.gotoacloud.top/Article/details/gtdpabfgpb.html

local a = 1
来源：http://dali.cashguo.top/Article/details/gtmtkatcms.html

[T33] Lua：表（数组）
来源：http://dali.nanxinkj.top/Article/details/gtatsfckrg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.birdmap.top/Article/details/gtsmmrerxk.html

[T34] Lua：遍历表
来源：http://dali.tian-w.cn/Article/details/gtnzoodslm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.tian-w.cn/Article/details/gtleleptni.html

[T35] Lua：字典表
来源：http://dali.cashguo.top/Article/details/gtzkvxyegc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.bjfxy.top/Article/details/gtifzegkzu.html

[T36] Lua：函数
来源：http://dali.tanke756.top/Article/details/gtszinvsmk.html

function add(a, b) return a + b end
来源：http://dali.c1oappe.top/Article/details/gtzhhljpig.html

[T37] Lua：字符串拼接
来源：http://dali.redwolf501.top/Article/details/gtgidqjqls.html

"a" .. "b"
来源：http://dali.yvedp.cn/Article/details/gtfigjjcrl.html

[T38] Lua：条件
来源：http://dali.yvedp.cn/Article/details/gtjgzvqldm.html

if x > 0 then print("正") end
来源：http://dali.gzhubu.top/Article/details/gtmwrcwsyo.html

[T39] Lua：模式匹配
来源：http://dali.fzhhl.top/Article/details/gtaprzvozv.html

string.find(s, "%d+")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrgrunxvr.html

[T40] Lua：元表
来源：http://dali.yonumen.top/Article/details/gtrvdeefgc.html

setmetatable({}, { __index = base })
来源：http://dali.cqqwz.cn/Article/details/gtubxcpkfn.html

[T41] Perl：Hello World
来源：http://dali.daxiang520.top/Article/details/gtgusmdazb.html

print "Hello\n";
来源：http://dali.sxryk.cn/Article/details/gtbkcsahhw.html

[T42] Perl：变量类型
来源：http://dali.xinyue.icu/Article/details/gtsfhfetda.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yvedp.cn/Article/details/gteacpeumx.html

[T43] Perl：字符串插值
来源：http://dali.hammf.cn/Article/details/gtlpifwzoq.html

"值: $a"
来源：http://dali.kuanghao11.cn/Article/details/gtiysobfhj.html

[T44] Perl：条件
来源：http://dali.jinqigufen.top/Article/details/gtjoyzzkgp.html

if ($a > 0) { print "正"; }
来源：http://dali.dianchejie.cn/Article/details/gtplyfleff.html

[T45] Perl：数组遍历
来源：http://dali.hfpthk.cn/Article/details/gttmfeitew.html

for my $x (@arr) { print $x; }
来源：http://dali.ivvv.top/Article/details/gtgljrdrbt.html

[T46] Perl：哈希操作
来源：http://dali.0kj1m.cn/Article/details/gtpzrmjruz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hysaishi.cn/Article/details/gtlmnjagev.html

[T47] Perl：正则捕获
来源：http://dali.sufxvd.cn/Article/details/gtzaowlcee.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.c1oappe.top/Article/details/gtpfrqgwpp.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gtatticqxt.html

$s =~ s/old/new/g;
来源：http://dali.ydzc1.top/Article/details/gtxhbiczdd.html

[T49] Perl：函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtawfmteqo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinqigufen.top/Article/details/gtqqoffdsj.html

[T50] Perl：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gtvmcxczsx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtouwlshne.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yanxiufei.cn/Article/details/gtdurdlgxb.html

[T51] Scala：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtmjljksyw.html

println("Hello")
来源：http://dali.fengsongda.top/Article/details/gtnuhezktp.html

[T52] Scala：变量
来源：http://dali.daria6918.cn/Article/details/gtmwmxdqra.html

val a = 1;  var b = 2
来源：http://dali.havefunace.top/Article/details/gttscdcbca.html

[T53] Scala：字符串插值
来源：http://dali.smart0.xyz/Article/details/gtdevslyoh.html

s"值: $b"
来源：http://dali.jianghu66.top/Article/details/gtnxufqtfo.html

[T54] Scala：集合映射
来源：http://dali.gzhubu.top/Article/details/gtokizfsto.html


<!-- 参考信息 -->