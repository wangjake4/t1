代发 wailian999

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tanke756.top/Article/details/gtsljmcwhz.html

[R50] awk 求和
来源：http://dali.jinqigufen.top/Article/details/gtzevlwilg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yueranfly.top/Article/details/gtczoyhgkf.html

[R51] 排序去重取前几
来源：http://dali.cashguo.top/Article/details/gthutzmmgy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hywenlv.cn/Article/details/gtqdupibko.html

[R52] 统计行数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqrrceqvd.html

wc -l a.txt
来源：http://dali.daxiang520.top/Article/details/gtgctzympx.html

[R53] 查看文件头与实时尾
来源：http://dali.andypj.xyz/Article/details/gtguoetrta.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.redwolf501.top/Article/details/gtorfiqflb.html

[R54] 比较两个文件
来源：http://dali.hysaishi.cn/Article/details/gtrawrjlnj.html

diff a.txt b.txt
来源：http://dali.xziqi.cn/Article/details/gtesfxfagb.html

[R55] 压缩与解压
来源：http://dali.sysykeji.top/Article/details/gtnuutohfz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhoulong.xyz/Article/details/gtdduedtyh.html

[R56] 远程拷贝
来源：http://dali.zhaomingkeji.xyz/Article/details/gtirvamxhg.html

scp file user@host:/path/
来源：http://dali.guannengcc.top/Article/details/gtsxneiohm.html

[R57] 远程执行命令
来源：http://dali.guannengcc.top/Article/details/gttfktbten.html

ssh user@host 'uptime'
来源：http://dali.andypj.xyz/Article/details/gthernyvsf.html

[R58] 下载文件
来源：http://dali.chenlongwang.top/Article/details/gtsybovbfl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jyoumei.cn/Article/details/gtetdcdgty.html

[R59] 发 POST JSON
来源：http://dali.guannengcc.top/Article/details/gtuvckvysw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xziqi.cn/Article/details/gtgcrvmduy.html

[R60] 只看 HTTP 状态码
来源：http://dali.shangyingyoupin.top/Article/details/gtbpaxcpod.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jyoumei.cn/Article/details/gthbibclyh.html

[R61] 磁盘占用
来源：http://dali.daxiang520.top/Article/details/gtgudsxiar.html

df -h;  du -sh *
来源：http://dali.haohaochexian.top/Article/details/gtgvdbvesn.html

[R62] 找最占空间的文件
来源：http://dali.hnqzz.top/Article/details/gtestrryza.html

du -ah . | sort -rh | head -10
来源：http://dali.yj20258888.top/Article/details/gtttvrpenv.html

[R63] 内存与进程
来源：http://dali.jqgfzy.top/Article/details/gtmxvujmsx.html

free -h;  ps aux | grep nginx
来源：http://dali.havefunace.top/Article/details/gtjsfqxzpe.html

[R64] 结束进程
来源：http://dali.jlsjyb.cn/Article/details/gtutzibbpm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zycfv.cn/Article/details/gtmzopoedj.html

[R65] 查看端口占用
来源：http://dali.jianghu66.top/Article/details/gttfwfrzrh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yueranfly.top/Article/details/gtyvilvpgi.html

[R66] 定时任务
来源：http://dali.sufxvd.cn/Article/details/gtoojuvbvh.html

crontab -e;  crontab -l
来源：http://dali.0kj1m.cn/Article/details/gtzzybozmc.html

[R67] 生成随机十六进制串
来源：http://dali.cdnleiting.top/Article/details/gtjmzghhvs.html

openssl rand -hex 16
来源：http://dali.xuanzx.com/Article/details/gtajlxseyz.html

[R68] 计算文件校验值
来源：http://dali.ybcxt.top/Article/details/gtdlqbemif.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cucudq.cn/Article/details/gtkxmpvzuf.html

[R69] 生成随机密码
来源：http://dali.kuanghao11.cn/Article/details/gtiyfciagz.html

head -c 16 /dev/urandom | base64
来源：http://dali.yj20258888.top/Article/details/gtuvanyveq.html

[R70] 时间戳与互转
来源：http://dali.xylfe.cn/Article/details/gtjntjpauz.html

date +%s;  date -d @1700000000
来源：http://dali.xziqi.cn/Article/details/gtaguzoysc.html

[R71] 日期格式化
来源：http://dali.bjfxy.top/Article/details/gtcklzovzn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yueranfly.top/Article/details/gtdmbkdlan.html

[R72] 等待端口就绪
来源：http://dali.cashguo.top/Article/details/gtphhfecbv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yuxming.cn/Article/details/gtnhkvgnwm.html

[R73] 分割大日志
来源：http://dali.yongpay.top/Article/details/gtgwxrcvfy.html

split -l 1000 big.log part_
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgjxvgzpc.html

[R74] 批量重命名
来源：http://dali.hnxiangtu.top/Article/details/gtnunpkvms.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gotoacloud.top/Article/details/gtqvcmagtn.html

[R75] 导出环境变量
来源：http://dali.cheryme.top/Article/details/gtkchogusu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shuidangran.top/Article/details/gtswejgkho.html

[R76] 使用临时文件
来源：http://dali.iojbl.cn/Article/details/gtjvdybokp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.guowangkeji.top/Article/details/gtasnopnbo.html

[R77] 读取用户输入
来源：http://dali.cucudq.cn/Article/details/gthinlbzkp.html

read -rp "请输入: " ans
来源：http://dali.mhx1999.top/Article/details/gtzfjvcdwa.html

[R78] 交互式菜单
来源：http://dali.nanxinkj.top/Article/details/gtnqivmfgu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gtorlwptdk.html

[R79] 解析命令行选项
来源：http://dali.ppjwa.cn/Article/details/gtkwopkewr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenjidiqi.icu/Article/details/gtrsxfosmf.html

[R80] 查看脚本执行耗时
来源：http://dali.ydzc1.top/Article/details/gtnxjbmyea.html

time ./run.sh
来源：http://dali.fzhhl.top/Article/details/gthhcmgjfw.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtxpzklffw.html

S. C / C++ 专题
来源：http://dali.fzhhl.top/Article/details/gtgiueamoi.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtrwyrirxa.html

[S01] C：Hello World
来源：http://dali.andypj.xyz/Article/details/gtbtxwcaij.html

#include <stdio.h>
来源：http://dali.ivvv.top/Article/details/gtvhjxjlhl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hnxiangtu.top/Article/details/gtcqrauthf.html

[S02] C：变量与格式化输出
来源：http://dali.yj20258.top/Article/details/gteighkfjs.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenjidiqi.icu/Article/details/gtpjlntusb.html

[S03] C：读入整数
来源：http://dali.hongshengwenyu.top/Article/details/gtqvxbdyrd.html

int x; scanf("%d", &x);
来源：http://dali.dashuyun.cn/Article/details/gtuzjklxsd.html

[S04] C：字符串复制
来源：http://dali.hysaishi.cn/Article/details/gtbjkzlybg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.smart0.xyz/Article/details/gtecpjeasv.html

[S05] C：字符串长度
来源：http://dali.snrcjt.cn/Article/details/gtlfmtpohi.html

strlen(s)
来源：http://dali.jiagoushi.top/Article/details/gtozbttnap.html

[S06] C：字符串比较
来源：http://dali.cdnleiting.top/Article/details/gtzashosjh.html

strcmp(a, b) == 0
来源：http://dali.zhixingplan.top/Article/details/gtxmjfdgbk.html

[S07] C：数组遍历求和
来源：http://dali.zycfv.cn/Article/details/gtycmenpqp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gotoacloud.top/Article/details/gtzxfomlsn.html

[S08] C：动态内存分配与释放
来源：http://dali.hammf.cn/Article/details/gtqxreebuo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.wangdashe.top/Article/details/gtfmiqwbcw.html

[S09] C：结构体定义与初始化
来源：http://dali.nwbrower.top/Article/details/gtxwesbnrx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.snrcjt.cn/Article/details/gtaajphqhe.html

[S10] C：指针与解引用
来源：http://dali.daria6918.cn/Article/details/gturyjtsfp.html

int *p = &a;  *p = 5;
来源：http://dali.quarkkingdee.top/Article/details/gtopbcimzt.html

[S11] C：逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gtsfasfqwp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.redwolf501.top/Article/details/gttuajsxeq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.snrcjt.cn/Article/details/gtfitsowtm.html

fclose(f);
来源：http://dali.shanyushiyangtech.top/Article/details/gttamtloed.html

[S12] C：写文件
来源：http://dali.zhengqikj.top/Article/details/gtczqahvjl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jlsjyb.cn/Article/details/gtvpslsjei.html

[S13] C：宏定义
来源：http://dali.ehwqpu.com/Article/details/gtjypqbutc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.9152youxi.cn/Article/details/gtuxdikbqa.html

[S14] C：枚举
来源：http://dali.zhongyouzk.top/Article/details/gtryzhgbki.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.aibaodan.cn/Article/details/gtqlhbsecc.html

[S15] C：类型转换
来源：http://dali.quarkkingdee.top/Article/details/gtouobrizu.html

(double) a / b
来源：http://dali.nanxuanxn.top/Article/details/gtzyyiykrf.html

[S16] C：位操作置位
来源：http://dali.hammf.cn/Article/details/gtvsafwawz.html

x |= (1 << 3);
来源：http://dali.hysaishi.cn/Article/details/gtmeafouzn.html

[S17] C：安全拼接字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwpmvxdhx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hnqzz.top/Article/details/gtucqlezhe.html

[S18] C：命令行参数
来源：http://dali.vqdsnc.cn/Article/details/gtmlgdrljx.html

int main(int argc, char **argv)
来源：http://dali.gogol.net.cn/Article/details/gtjjfcvdsd.html

[S19] C：快速排序
来源：http://dali.cheryme.top/Article/details/gtmcqmqblb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.dianchejie.cn/Article/details/gtncatctma.html

[S20] C：二分查找
来源：http://dali.jlsjyb.cn/Article/details/gthidvsldn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cashguo.top/Article/details/gtaxvoehxj.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gtxllonsml.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjqgtgipw.html

[S22] C：字符串转数字
来源：http://dali.yongpay.top/Article/details/gtaaosygvy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yueranfly.top/Article/details/gtdmdqoqdr.html

[S23] C：随机数
来源：http://dali.snrcjt.cn/Article/details/gtgwoyddnd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yueranfly.top/Article/details/gthiwsbpeb.html

[S24] C：获取本地时间
来源：http://dali.jinqigufen.top/Article/details/gtyscdekzg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shuidangran.top/Article/details/gtbmbwlmtx.html

[S25] C：内存拷贝
来源：http://dali.tian-w.cn/Article/details/gtulcmfuzk.html

memcpy(dst, src, n);
来源：http://dali.yvedp.cn/Article/details/gtdqyaqopg.html

[S26] C：内存清零
来源：http://dali.pengpengdd.cyou/Article/details/gteunelxje.html

memset(a, 0, sizeof a);
来源：http://dali.yongpay.top/Article/details/gtjwxxftxl.html

[S27] C：定义常量
来源：http://dali.iojbl.cn/Article/details/gtwlisjvvt.html

const double PI = 3.14159;
来源：http://dali.wangdashe.top/Article/details/gtpytqiaqg.html

[S28] C：静态变量
来源：http://dali.yuxming.cn/Article/details/gtkcrlsryq.html

static int counter = 0;
来源：http://dali.yonumen.top/Article/details/gtxranqehx.html

[S29] C：变参函数
来源：http://dali.dianchejie.cn/Article/details/gtkhuivmhl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gtawaisdso.html

[S30] C：头文件保护
来源：http://dali.cashguo.top/Article/details/gtkgomirmu.html

#ifndef X_H
来源：http://dali.ywan-chungtsiang.top/Article/details/gtputxhyhn.html

#define X_H
来源：http://dali.haohaochexian.top/Article/details/gtmjxksvwc.html

#endif
来源：http://dali.ivvv.top/Article/details/gtxdcpqtvp.html

[S31] C++：Hello World
来源：http://dali.zycfv.cn/Article/details/gtssxdqrdc.html

#include <iostream>
来源：http://dali.jqgufenzy.top/Article/details/gtlfmqqhyx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gotoacloud.top/Article/details/gtubwxefhm.html

[S32] C++：字符串
来源：http://dali.cheryme.top/Article/details/gtuiatjbtq.html

std::string s = "hi";  s += "!";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbzairoo.html

[S33] C++：vector 增删
来源：http://dali.pycfn.com/Article/details/gtmehhxtdr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ydzc1.top/Article/details/gtvtqvokvk.html

[S34] C++：遍历 vector
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtstyicjoe.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gaohongyu789.top/Article/details/gtdacwjfha.html

[S35] C++：map
来源：http://dali.ppjwa.cn/Article/details/gtuimzgdud.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gtvmfkxsqb.html

[S36] C++：unordered_map
来源：http://dali.andypj.xyz/Article/details/gtwgsekdus.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtscmvzeos.html

[S37] C++：set
来源：http://dali.dashuyun.cn/Article/details/gteibrobvj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cucudq.cn/Article/details/gttcaaplmq.html

[S38] C++：排序
来源：http://dali.birdmap.top/Article/details/gttwnuoyog.html

std::sort(v.begin(), v.end());
来源：http://dali.0kj1m.cn/Article/details/gtaboumynj.html

[S39] C++：自定义比较器排序
来源：http://dali.ivvv.top/Article/details/gtiwdvezte.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yvedp.cn/Article/details/gtdbrbaxzh.html

[S40] C++：查找元素
来源：http://dali.cqqwz.cn/Article/details/gthqvmfmwn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ybcxt.top/Article/details/gtjufazerl.html

[S41] C++：类与构造函数
来源：http://dali.c1oappe.top/Article/details/gttyeaeuio.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.quarkkingdee.top/Article/details/gtggehqkno.html

[S42] C++：继承与虚函数
来源：http://dali.zhixingplan.top/Article/details/gtxatkcpqp.html

class B : public Base { public: void f() override {} };
来源：http://dali.bjfxy.top/Article/details/gtwtfscqdt.html

[S43] C++：智能指针
来源：http://dali.sweek.top/Article/details/gtigkipwoj.html

auto p = std::make_unique<int>(5);
来源：http://dali.yuanzhike.top/Article/details/gtdhpikwqa.html

[S44] C++：引用传参
来源：http://dali.gogol.net.cn/Article/details/gtnkaixufx.html

void inc(int &x) { ++x; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtigvtkdlz.html

[S45] C++：lambda
来源：http://dali.daria6918.cn/Article/details/gttwwcqygz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.vqdsnc.cn/Article/details/gtroowrtvl.html

[S46] C++：函数模板
来源：http://dali.yj20258888.top/Article/details/gthomdcieb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sysykeji.top/Article/details/gtrgvztezf.html

[S47] C++：结构化绑定遍历
来源：http://dali.sufxvd.cn/Article/details/gtpxwmercr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.fzhhl.top/Article/details/gtwivyickf.html

[S48] C++：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gtrjglognu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cashguo.top/Article/details/gtdajrpeko.html

while (std::getline(in, line)) { }
来源：http://dali.yanxiufei.cn/Article/details/gtbcdpntwi.html

[S49] C++：写文件
来源：http://dali.nanxinkj.top/Article/details/gtqvpyrgmt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.fengsongda.top/Article/details/gtuxncwsdv.html

[S50] C++：格式化数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbnqntjlz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shuidangran.top/Article/details/gttokzwvtz.html

[S51] C++：显式类型转换
来源：http://dali.jianghu66.top/Article/details/gthhslqtap.html

static_cast<double>(a) / b
来源：http://dali.hywenlv.cn/Article/details/gtyduylluc.html

[S52] C++：const 与 noexcept
来源：http://dali.jyoumei.cn/Article/details/gtlikupqnz.html

int size() const noexcept { return n_; }
来源：http://dali.jinqigfzy.top/Article/details/gtgqunizag.html

[S53] C++：移动语义
来源：http://dali.wangdashe.top/Article/details/gtjawtfdit.html

std::vector<int> w = std::move(v);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmkrsguxd.html

[S54] C++：异常处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjblmfcgg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sufxvd.cn/Article/details/gtqivntthp.html

[S55] C++：结构化绑定
来源：http://dali.sufxvd.cn/Article/details/gtlzechqef.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.dashuyun.cn/Article/details/gtviudtnpj.html

[S56] C++：optional
来源：http://dali.yj202588.top/Article/details/gtxiyitqsu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hammf.cn/Article/details/gtddbswlxl.html

[S57] C++：编译期常量
来源：http://dali.cdnleiting.top/Article/details/gtpqwdhssl.html

constexpr int N = 10;
来源：http://dali.cucudq.cn/Article/details/gtgzqajewa.html

[S58] C++：命名空间
来源：http://dali.guannengcc.top/Article/details/gtxzpsthve.html

namespace ns { int f() { return 1; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsdtahvva.html

[S59] C++：静态断言
来源：http://dali.cucudq.cn/Article/details/gtfltzxdxw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.dashuyun.cn/Article/details/gtpwmsqeyk.html

[S60] C++：遍历并删除元素
来源：http://dali.jinqigfzy.top/Article/details/gtjecssmcj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.fzhhl.top/Article/details/gtkmkovkjp.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtodfbfmta.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqgtlzjo.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtdprahicc.html

[T01] Kotlin：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtpvgtbvzq.html

println("Hello")
来源：http://dali.xylfe.cn/Article/details/gtfhmmqsfe.html

[T02] Kotlin：变量
来源：http://dali.fengsongda.top/Article/details/gtnoiawyux.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinghuilouyu.cn/Article/details/gtzohvkccu.html

[T03] Kotlin：字符串模板
来源：http://dali.aibaodan.cn/Article/details/gtdsfmlqoe.html

"值: $b"
来源：http://dali.svipenyu.cn/Article/details/gtbzrernbe.html

[T04] Kotlin：空安全
来源：http://dali.yuanzhike.top/Article/details/gtfdualoms.html

val n: String? = null;  n?.length
来源：http://dali.9152youxi.cn/Article/details/gtqvaiwxhu.html

[T05] Kotlin：when 表达式
来源：http://dali.yangfankeji.com/Article/details/gttzctpzts.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.0kj1m.cn/Article/details/gtbpvxugve.html

[T06] Kotlin：集合映射
来源：http://dali.feifeiyinyue.top/Article/details/gtwrmzztig.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinqigufen.top/Article/details/gtivpnttwi.html

[T07] Kotlin：集合过滤
来源：http://dali.c1oappe.top/Article/details/gtqecdesjn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuanzhike.top/Article/details/gthfxgnwet.html

[T08] Kotlin：数据类
来源：http://dali.yangfankeji.com/Article/details/gtojpreind.html

data class User(val name: String, val age: Int)
来源：http://dali.xziqi.cn/Article/details/gtrgkwmrcv.html

[T09] Kotlin：扩展函数
来源：http://dali.xuanzx.com/Article/details/gtfsocuccz.html

fun String.exclaim() = this + "!"
来源：http://dali.daxiang520.top/Article/details/gtbzpdiqng.html

[T10] Kotlin：默认参数
来源：http://dali.haohaochexian.top/Article/details/gtevrgzprd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinqigufen.top/Article/details/gthrbdmltr.html

[T11] Kotlin：协程
来源：http://dali.aibaodan.cn/Article/details/gtnszyxqom.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.316326.xyz/Article/details/gtxeouewle.html

[T12] Kotlin：解构声明
来源：http://dali.sufxvd.cn/Article/details/gtxwdvubgi.html

val (a, b) = Pair(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtuobzbvpw.html

[T13] Kotlin：只读 Map
来源：http://dali.9152youxi.cn/Article/details/gtvjfnrxds.html

val m = mapOf("a" to 1)
来源：http://dali.snrcjt.cn/Article/details/gtpaxrbyql.html

[T14] Kotlin：循环
来源：http://dali.zycfv.cn/Article/details/gtymnkersw.html

for (i in 1..10) println(i)
来源：http://dali.chenzaomai.com/Article/details/gtlukvrtat.html

[T15] Kotlin：接口
来源：http://dali.jinyuanbaomall.cn/Article/details/gtduhphvzd.html

interface Shape { fun area(): Double }
来源：http://dali.gotoacloud.top/Article/details/gtmcdzyczx.html

[T16] Swift：Hello World
来源：http://dali.nwbrower.top/Article/details/gtjgvyedsp.html

print("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gtwqxjvpkm.html

[T17] Swift：变量与常量
来源：http://dali.yj202588.top/Article/details/gtzmbkmdmy.html

var a = 1;  let b = 2
来源：http://dali.xuetiantiany.cn/Article/details/gtxasfsfjv.html

[T18] Swift：字符串插值
来源：http://dali.cucudq.cn/Article/details/gtnsdudkky.html

"值: \(b)"
来源：http://dali.yongpay.top/Article/details/gtzgzdrgls.html

[T19] Swift：可选绑定
来源：http://dali.yonumen.top/Article/details/gtneilrwde.html

if let n = opt { print(n) }
来源：http://dali.xuanzx.com/Article/details/gtxtmjotpg.html

[T20] Swift：数组操作
来源：http://dali.wangshuangyany.cn/Article/details/gtpgdmvjeu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hnqzz.top/Article/details/gtbjrcjkgv.html

[T21] Swift：遍历
来源：http://dali.ybcxt.top/Article/details/gtlopxxnoy.html

for x in a { print(x) }
来源：http://dali.fzhhl.top/Article/details/gtreahhrac.html

[T22] Swift：字典
来源：http://dali.jiagoushi.top/Article/details/gtggpnzwjn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtverpkrnq.html

[T23] Swift：函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqpvtuzj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jqgfzy.top/Article/details/gtnenuijne.html

[T24] Swift：闭包
来源：http://dali.gaohongyu789.top/Article/details/gtopzdzxov.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shzxlz.cn/Article/details/gtovgrgdem.html

[T25] Swift：结构体
来源：http://dali.guannengcc.top/Article/details/gtvsnzwzif.html

struct P { var x: Int }
来源：http://dali.xinyue.icu/Article/details/gtqwmqbdok.html

[T26] Swift：类与重写
来源：http://dali.yuanzhike.top/Article/details/gtnqiklixo.html

class A: Base { override func f() {} }
来源：http://dali.chenzaomai.com/Article/details/gtoeqwirzc.html

[T27] Swift：错误处理
来源：http://dali.zhongyouzk.top/Article/details/gtmvzpvzan.html

do { try f() } catch { print(error) }
来源：http://dali.cqqwz.cn/Article/details/gtucsurqoq.html

[T28] Swift：枚举
来源：http://dali.yj20258.top/Article/details/gtkelcwlil.html

enum Color { case red, green }
来源：http://dali.gzhubu.top/Article/details/gtjhclzgxf.html

[T29] Swift：guard 提前返回
来源：http://dali.yvedp.cn/Article/details/gtedpxfhnz.html

guard let x = opt else { return }
来源：http://dali.hnxiangtu.top/Article/details/gtgynatyzb.html

[T30] Swift：协议
来源：http://dali.snrcjt.cn/Article/details/gtvijzlqao.html

protocol Shape { func area() -> Double }
来源：http://dali.hnxiangtu.top/Article/details/gtwxzffyqi.html

[T31] Lua：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtxcbczyie.html

print("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gtyhgrdzhp.html

[T32] Lua：局部变量
来源：http://dali.vqdsnc.cn/Article/details/gtpkaawiza.html

local a = 1
来源：http://dali.aibaodan.cn/Article/details/gtbilhktve.html

[T33] Lua：表（数组）
来源：http://dali.hammf.cn/Article/details/gtlgeyhzgp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gtzdnhokec.html

[T34] Lua：遍历表
来源：http://dali.cashguo.top/Article/details/gtychnpyvw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jianghu66.top/Article/details/gtqppluoew.html

[T35] Lua：字典表
来源：http://dali.pycfn.com/Article/details/gtrlahcnlo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sufxvd.cn/Article/details/gtuhcmzuiq.html

[T36] Lua：函数
来源：http://dali.redwolf501.top/Article/details/gtdsaxvwno.html

function add(a, b) return a + b end
来源：http://dali.shzxlz.cn/Article/details/gtycioozxk.html

[T37] Lua：字符串拼接
来源：http://dali.kuanghao11.cn/Article/details/gtjudqzmtq.html

"a" .. "b"
来源：http://dali.mhx1999.top/Article/details/gtecjgnssr.html

[T38] Lua：条件
来源：http://dali.jinqigufen.top/Article/details/gtrhmuyzxp.html

if x > 0 then print("正") end
来源：http://dali.yongpay.top/Article/details/gtlipamvcy.html

[T39] Lua：模式匹配
来源：http://dali.yangfankeji.com/Article/details/gtgjbjlees.html

string.find(s, "%d+")
来源：http://dali.ehwqpu.com/Article/details/gtuewimoox.html

[T40] Lua：元表
来源：http://dali.jinyuanbaomall.cn/Article/details/gthcxigbps.html

setmetatable({}, { __index = base })
来源：http://dali.pengpengdd.cyou/Article/details/gtvgezbjpi.html

[T41] Perl：Hello World
来源：http://dali.hammf.cn/Article/details/gtqksebvms.html

print "Hello\n";
来源：http://dali.ybcxt.top/Article/details/gtyimrqtpk.html

[T42] Perl：变量类型
来源：http://dali.yuxming.cn/Article/details/gtjgoqccjs.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.snrcjt.cn/Article/details/gtdrnalrjk.html

[T43] Perl：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gtrxoldcse.html

"值: $a"
来源：http://dali.zhiwuduotai.top/Article/details/gtaotcjhoq.html

[T44] Perl：条件
来源：http://dali.316326.xyz/Article/details/gtlwqpqjwh.html

if ($a > 0) { print "正"; }
来源：http://dali.dianchejie.cn/Article/details/gtwnnbthic.html

[T45] Perl：数组遍历
来源：http://dali.fzhhl.top/Article/details/gtbeavfltj.html

for my $x (@arr) { print $x; }
来源：http://dali.xuanzx.com/Article/details/gtqmwnbhqm.html

[T46] Perl：哈希操作
来源：http://dali.sufxvd.cn/Article/details/gtadfyosvf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.bjfxy.top/Article/details/gtaycjmgzy.html

[T47] Perl：正则捕获
来源：http://dali.gzhubu.top/Article/details/gtsujlwdsr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.fengsongda.top/Article/details/gtgjqocdgc.html

[T48] Perl：正则替换
来源：http://dali.yangfankeji.com/Article/details/gtwjxxbeqq.html

$s =~ s/old/new/g;
来源：http://dali.chenlongwang.top/Article/details/gtpsznwnny.html

[T49] Perl：函数
来源：http://dali.c1oappe.top/Article/details/gtigiyoyag.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gtpjbccabj.html

[T50] Perl：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gtvcvdwmkg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabdeodka.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.pengpengdd.cyou/Article/details/gtkahpqyjj.html

[T51] Scala：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gthbhzxcop.html

println("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtaygefppc.html

[T52] Scala：变量
来源：http://dali.birdmap.top/Article/details/gtwlqlbnam.html


<!-- 参考信息 -->