代发 wailian999

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhixingplan.top/Article/details/gt2sbbsoqpd.html

[R50] awk 求和
来源：http://dali.tanke756.top/Article/details/gt2dqwjfxkr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sxbdsvql.html

[R51] 排序去重取前几
来源：http://dali.shangyingyoupin.top/Article/details/gt2gfitwfdf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cheryme.top/Article/details/gt2ocdouatj.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2dubtptna.html

wc -l a.txt
来源：http://dali.9152youxi.cn/Article/details/gt2vwomlqhv.html

[R53] 查看文件头与实时尾
来源：http://dali.gzhubu.top/Article/details/gt2cjzkwisv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yj20258.top/Article/details/gt2ulaojktg.html

[R54] 比较两个文件
来源：http://dali.9152youxi.cn/Article/details/gt2cmhnipat.html

diff a.txt b.txt
来源：http://dali.daxiang520.top/Article/details/gt2pcdubkvb.html

[R55] 压缩与解压
来源：http://dali.zdqjudy.top/Article/details/gt2kfchfdcs.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zdqjudy.top/Article/details/gt2xlutttpg.html

[R56] 远程拷贝
来源：http://dali.sxryk.cn/Article/details/gt2gkfnzfkn.html

scp file user@host:/path/
来源：http://dali.jlsjyb.cn/Article/details/gt2jftpjkex.html

[R57] 远程执行命令
来源：http://dali.meibo888.top/Article/details/gt2hhyohhnm.html

ssh user@host 'uptime'
来源：http://dali.gogol.net.cn/Article/details/gt2eyiufvlj.html

[R58] 下载文件
来源：http://dali.tanke756.top/Article/details/gt2nwiretww.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.aizwys.cn/Article/details/gt2wcwvsjys.html

[R59] 发 POST JSON
来源：http://dali.fzhhl.top/Article/details/gt2dstvwbim.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sysykeji.top/Article/details/gt2rqchniwf.html

[R60] 只看 HTTP 状态码
来源：http://dali.dashuyun.cn/Article/details/gt2cfhhxqyb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gaohongyu789.top/Article/details/gt2mgrueebc.html

[R61] 磁盘占用
来源：http://dali.sweek.top/Article/details/gt2khutwekz.html

df -h;  du -sh *
来源：http://dali.pycfn.com/Article/details/gt2smaqwnuw.html

[R62] 找最占空间的文件
来源：http://dali.zhengqikj.top/Article/details/gt2lvfdpgfp.html

du -ah . | sort -rh | head -10
来源：http://dali.sweek.top/Article/details/gt2gadzxgzt.html

[R63] 内存与进程
来源：http://dali.vqdsnc.cn/Article/details/gt2lnhepffw.html

free -h;  ps aux | grep nginx
来源：http://dali.xinyue.icu/Article/details/gt2dzjwizmc.html

[R64] 结束进程
来源：http://dali.0kj1m.cn/Article/details/gt2qcauinbz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ehwqpu.com/Article/details/gt2irqmnzdq.html

[R65] 查看端口占用
来源：http://dali.hongshengwenyu.top/Article/details/gt2dwhplsji.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.wangshuangyany.cn/Article/details/gt2bwpphkfi.html

[R66] 定时任务
来源：http://dali.gzhubu.top/Article/details/gt2djounymt.html

crontab -e;  crontab -l
来源：http://dali.feifeiyinyue.top/Article/details/gt2rdxqqeau.html

[R67] 生成随机十六进制串
来源：http://dali.yj20258.top/Article/details/gt2rshnwavf.html

openssl rand -hex 16
来源：http://dali.fzhhl.top/Article/details/gt2etrbzxfa.html

[R68] 计算文件校验值
来源：http://dali.hywenlv.cn/Article/details/gt2msenxybv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.wangdashe.top/Article/details/gt2obnfcvqt.html

[R69] 生成随机密码
来源：http://dali.redwolf501.top/Article/details/gt2ybbzfbag.html

head -c 16 /dev/urandom | base64
来源：http://dali.cqqwz.cn/Article/details/gt2yvdqhudf.html

[R70] 时间戳与互转
来源：http://dali.gaohongyu789.top/Article/details/gt2wiesbhgd.html

date +%s;  date -d @1700000000
来源：http://dali.ivvv.top/Article/details/gt2ncxcxgtp.html

[R71] 日期格式化
来源：http://dali.nwbrower.top/Article/details/gt2tldhxdrx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hongshengwenyu.top/Article/details/gt2gwnobozx.html

[R72] 等待端口就绪
来源：http://dali.yanxiufei.cn/Article/details/gt2jthxmooy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jyoumei.cn/Article/details/gt2hzydpoxo.html

[R73] 分割大日志
来源：http://dali.tian-w.cn/Article/details/gt2wbbzqidc.html

split -l 1000 big.log part_
来源：http://dali.yuxming.cn/Article/details/gt2lsfivcgn.html

[R74] 批量重命名
来源：http://dali.yj20258888.top/Article/details/gt2eylltouv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.haohaochexian.top/Article/details/gt2opzoomay.html

[R75] 导出环境变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2lybutxee.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sysykeji.top/Article/details/gt2iqbtadia.html

[R76] 使用临时文件
来源：http://dali.bjfxy.top/Article/details/gt2qccfydkn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.smart0.xyz/Article/details/gt2icrxzmqy.html

[R77] 读取用户输入
来源：http://dali.xuetiantiany.cn/Article/details/gt2trxenkzx.html

read -rp "请输入: " ans
来源：http://dali.shzxlz.cn/Article/details/gt2zdqeahti.html

[R78] 交互式菜单
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ipuahbzt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gzhubu.top/Article/details/gt2brsqufnh.html

[R79] 解析命令行选项
来源：http://dali.svipenyu.cn/Article/details/gt2wstrnons.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ehwqpu.com/Article/details/gt2hiwxeako.html

[R80] 查看脚本执行耗时
来源：http://dali.gaohongyu789.top/Article/details/gt2swecosff.html

time ./run.sh
来源：http://dali.ydzc1.top/Article/details/gt2iobsklpa.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2mmsxexqv.html

S. C / C++ 专题
来源：http://dali.yonumen.top/Article/details/gt2dcbglcup.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2vsqnsmsg.html

[S01] C：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2byftavbr.html

#include <stdio.h>
来源：http://dali.yonumen.top/Article/details/gt2wexzrnsz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinqigfzy.top/Article/details/gt2okocvuvz.html

[S02] C：变量与格式化输出
来源：http://dali.jiagoushi.top/Article/details/gt2kwptximg.html

int a = 10; printf("%d\n", a);
来源：http://dali.jlsjyb.cn/Article/details/gt2nryegoly.html

[S03] C：读入整数
来源：http://dali.ehwqpu.com/Article/details/gt2tdrzuhly.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnrxysy.html

[S04] C：字符串复制
来源：http://dali.aibaodan.cn/Article/details/gt2vdnxfugs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj20258.top/Article/details/gt2cbhwiodw.html

[S05] C：字符串长度
来源：http://dali.andypj.xyz/Article/details/gt2psbwnqoz.html

strlen(s)
来源：http://dali.yj202588.top/Article/details/gt2wiprjszg.html

[S06] C：字符串比较
来源：http://dali.aibaodan.cn/Article/details/gt2uveyzmcp.html

strcmp(a, b) == 0
来源：http://dali.sweek.top/Article/details/gt2lugtuuml.html

[S07] C：数组遍历求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gucegnzn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sweek.top/Article/details/gt2nalrqste.html

[S08] C：动态内存分配与释放
来源：http://dali.ehwqpu.com/Article/details/gt2eugjvtdn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gogol.net.cn/Article/details/gt2lncrsqpa.html

[S09] C：结构体定义与初始化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nzcpdnha.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jyoumei.cn/Article/details/gt2mnqpsoap.html

[S10] C：指针与解引用
来源：http://dali.gotoacloud.top/Article/details/gt2fjxqdnyp.html

int *p = &a;  *p = 5;
来源：http://dali.andypj.xyz/Article/details/gt2hzgvicch.html

[S11] C：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gt2dugqbyca.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.quarkkingdee.top/Article/details/gt2ujgszoia.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fgwcmcns.html

fclose(f);
来源：http://dali.nanxuanxn.top/Article/details/gt2nqbcxywo.html

[S12] C：写文件
来源：http://dali.shzxlz.cn/Article/details/gt2fvijvaqk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhengqikj.top/Article/details/gt2tsetvnpp.html

[S13] C：宏定义
来源：http://dali.havefunace.top/Article/details/gt2ezbjgdqm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yanxiufei.cn/Article/details/gt2judyhnqy.html

[S14] C：枚举
来源：http://dali.zhengqikj.top/Article/details/gt2lezkfusd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.guannengcc.top/Article/details/gt2iyzyovrb.html

[S15] C：类型转换
来源：http://dali.sxryk.cn/Article/details/gt2lahaemxl.html

(double) a / b
来源：http://dali.xinyue.icu/Article/details/gt2bljztfsn.html

[S16] C：位操作置位
来源：http://dali.yj20258.top/Article/details/gt2ucktyjlh.html

x |= (1 << 3);
来源：http://dali.zhoulong.xyz/Article/details/gt2dorgkjvm.html

[S17] C：安全拼接字符串
来源：http://dali.daxiang520.top/Article/details/gt2lmwygagv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.c1oappe.top/Article/details/gt2qvwhjfni.html

[S18] C：命令行参数
来源：http://dali.xylfe.cn/Article/details/gt2cfjlkbpi.html

int main(int argc, char **argv)
来源：http://dali.gotoacloud.top/Article/details/gt2qdesdazi.html

[S19] C：快速排序
来源：http://dali.shzxlz.cn/Article/details/gt2ythzbqmb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gt2vdehiwtc.html

[S20] C：二分查找
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zuohqyyf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.bjfxy.top/Article/details/gt2bscepbnb.html

[S21] C：字符类别判断
来源：http://dali.jinqigufen.top/Article/details/gt2mbekpand.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.aizwys.cn/Article/details/gt2jshapapd.html

[S22] C：字符串转数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jsrzlmmt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.9152youxi.cn/Article/details/gt2ypgnlvux.html

[S23] C：随机数
来源：http://dali.316326.xyz/Article/details/gt2pewvjsiu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xziqi.cn/Article/details/gt2ekcpecwz.html

[S24] C：获取本地时间
来源：http://dali.jlsjyb.cn/Article/details/gt2dzrmpthe.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.birdmap.top/Article/details/gt2zydvihxu.html

[S25] C：内存拷贝
来源：http://dali.fzhhl.top/Article/details/gt2fmpejkdy.html

memcpy(dst, src, n);
来源：http://dali.yanxiufei.cn/Article/details/gt2hkcxgxpn.html

[S26] C：内存清零
来源：http://dali.redwolf501.top/Article/details/gt2dilupuwv.html

memset(a, 0, sizeof a);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2explbcrf.html

[S27] C：定义常量
来源：http://dali.shangyingyoupin.top/Article/details/gt2ruepmxbq.html

const double PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gt2ufzxgtvb.html

[S28] C：静态变量
来源：http://dali.ppjwa.cn/Article/details/gt2qctbhiou.html

static int counter = 0;
来源：http://dali.yangfankeji.com/Article/details/gt2lvbtvjlt.html

[S29] C：变参函数
来源：http://dali.bjfxy.top/Article/details/gt2ynpzfhlv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.svipenyu.cn/Article/details/gt2mzxrzzzs.html

[S30] C：头文件保护
来源：http://dali.vqdsnc.cn/Article/details/gt2hkngrxxa.html

#ifndef X_H
来源：http://dali.gotoacloud.top/Article/details/gt2flwzudud.html

#define X_H
来源：http://dali.guowangkeji.top/Article/details/gt2tpcytrbe.html

#endif
来源：http://dali.bjfxy.top/Article/details/gt2ysizzxhv.html

[S31] C++：Hello World
来源：http://dali.jinqigufen.top/Article/details/gt2wmqjlhmq.html

#include <iostream>
来源：http://dali.jinqigufen.top/Article/details/gt2ditqsevf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.pycfn.com/Article/details/gt2ijrkldsf.html

[S32] C++：字符串
来源：http://dali.guannengcc.top/Article/details/gt2cywlglxl.html

std::string s = "hi";  s += "!";
来源：http://dali.haohaochexian.top/Article/details/gt2ingoidmt.html

[S33] C++：vector 增删
来源：http://dali.jinqigufen.top/Article/details/gt2qkctobkk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ukpnpqvi.html

[S34] C++：遍历 vector
来源：http://dali.fengsongda.top/Article/details/gt2yngcwxke.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yj20258888.top/Article/details/gt2oqiqqmxs.html

[S35] C++：map
来源：http://dali.feifeiyinyue.top/Article/details/gt2znrfsfrx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jyoumei.cn/Article/details/gt2gjxqcaxd.html

[S36] C++：unordered_map
来源：http://dali.nwbrower.top/Article/details/gt2kxjpxnbc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shuidangran.top/Article/details/gt2umcqpiks.html

[S37] C++：set
来源：http://dali.guowangkeji.top/Article/details/gt2ibrpohnu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.dashuyun.cn/Article/details/gt2parcladt.html

[S38] C++：排序
来源：http://dali.shuidangran.top/Article/details/gt2qfrngxxo.html

std::sort(v.begin(), v.end());
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bavasrtb.html

[S39] C++：自定义比较器排序
来源：http://dali.hnqzz.top/Article/details/gt2nbbrpucp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hnxiangtu.top/Article/details/gt2mycfxmcj.html

[S40] C++：查找元素
来源：http://dali.xylfe.cn/Article/details/gt2faezenpn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ybcxt.top/Article/details/gt2rdijagoq.html

[S41] C++：类与构造函数
来源：http://dali.jqgufenzy.top/Article/details/gt2enriamtq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ybcxt.top/Article/details/gt2sqgusnmy.html

[S42] C++：继承与虚函数
来源：http://dali.ybcxt.top/Article/details/gt2sszndssu.html

class B : public Base { public: void f() override {} };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rpbegfhe.html

[S43] C++：智能指针
来源：http://dali.shangyingyoupin.top/Article/details/gt2sjknxdlu.html

auto p = std::make_unique<int>(5);
来源：http://dali.guowangkeji.top/Article/details/gt2jjmsgnvy.html

[S44] C++：引用传参
来源：http://dali.yongpay.top/Article/details/gt2hrmpmqbc.html

void inc(int &x) { ++x; }
来源：http://dali.meibo888.top/Article/details/gt2skreegpz.html

[S45] C++：lambda
来源：http://dali.shzxlz.cn/Article/details/gt2aymreizy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj20258888.top/Article/details/gt2enmjbipu.html

[S46] C++：函数模板
来源：http://dali.zhiwuduotai.top/Article/details/gt2yzaacetm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhongyouzk.top/Article/details/gt2gnuilsyl.html

[S47] C++：结构化绑定遍历
来源：http://dali.chenlongwang.top/Article/details/gt2opguieoe.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cashguo.top/Article/details/gt2rpgwennf.html

[S48] C++：逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gt2fhjrsfqd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.andypj.xyz/Article/details/gt2qbxodtce.html

while (std::getline(in, line)) { }
来源：http://dali.hfpthk.cn/Article/details/gt2mqoixebd.html

[S49] C++：写文件
来源：http://dali.yvedp.cn/Article/details/gt2fgndbhsd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nanxinkj.top/Article/details/gt2takzpygp.html

[S50] C++：格式化数字
来源：http://dali.hnxiangtu.top/Article/details/gt2rgetjjwj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gt2reganume.html

[S51] C++：显式类型转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hpduanjj.html

static_cast<double>(a) / b
来源：http://dali.ppjwa.cn/Article/details/gt2rzdxplwa.html

[S52] C++：const 与 noexcept
来源：http://dali.tanke756.top/Article/details/gt2firqmtfg.html

int size() const noexcept { return n_; }
来源：http://dali.gzhubu.top/Article/details/gt2itolqhvs.html

[S53] C++：移动语义
来源：http://dali.ehwqpu.com/Article/details/gt2pgfdjrdz.html

std::vector<int> w = std::move(v);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hgavvwxy.html

[S54] C++：异常处理
来源：http://dali.ehwqpu.com/Article/details/gt2izmogail.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.smart0.xyz/Article/details/gt2sgheywjf.html

[S55] C++：结构化绑定
来源：http://dali.cqqwz.cn/Article/details/gt2cpvglqdd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.smart0.xyz/Article/details/gt2qodrivqe.html

[S56] C++：optional
来源：http://dali.yueranfly.top/Article/details/gt2nykvtzle.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shuidangran.top/Article/details/gt2pnflaqcq.html

[S57] C++：编译期常量
来源：http://dali.svipenyu.cn/Article/details/gt2nsrghehz.html

constexpr int N = 10;
来源：http://dali.dianchejie.cn/Article/details/gt2yrfpetrx.html

[S58] C++：命名空间
来源：http://dali.xuanzx.com/Article/details/gt2sfmakzkf.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj20258.top/Article/details/gt2vprupjgg.html

[S59] C++：静态断言
来源：http://dali.gzhubu.top/Article/details/gt2zufrbqrz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xinyue.icu/Article/details/gt2dgneihzm.html

[S60] C++：遍历并删除元素
来源：http://dali.sweek.top/Article/details/gt2zofsllxl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.daria6918.cn/Article/details/gt2qhxpjxcu.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2rortsllf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.fzhhl.top/Article/details/gt2clwjqsgs.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2ymifoubd.html

[T01] Kotlin：Hello World
来源：http://dali.dianchejie.cn/Article/details/gt2upaxkgrx.html

println("Hello")
来源：http://dali.yuxming.cn/Article/details/gt2ithypijw.html

[T02] Kotlin：变量
来源：http://dali.shuidangran.top/Article/details/gt2bttwwyle.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hysaishi.cn/Article/details/gt2bctqwqvx.html

[T03] Kotlin：字符串模板
来源：http://dali.cdnleiting.top/Article/details/gt2gktmxktm.html

"值: $b"
来源：http://dali.zhixingplan.top/Article/details/gt2arjxuske.html

[T04] Kotlin：空安全
来源：http://dali.yj20258888.top/Article/details/gt2txwopahh.html

val n: String? = null;  n?.length
来源：http://dali.sysykeji.top/Article/details/gt2oitfonod.html

[T05] Kotlin：when 表达式
来源：http://dali.xuetiantiany.cn/Article/details/gt2soeuhihc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.snrcjt.cn/Article/details/gt2ralyzdef.html

[T06] Kotlin：集合映射
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ijuqyyrl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.daria6918.cn/Article/details/gt2efttcafa.html

[T07] Kotlin：集合过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2motfgxjt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gzhubu.top/Article/details/gt2pswhziux.html

[T08] Kotlin：数据类
来源：http://dali.jqgufenzy.top/Article/details/gt2zyhxswss.html

data class User(val name: String, val age: Int)
来源：http://dali.svipenyu.cn/Article/details/gt2mruseazv.html

[T09] Kotlin：扩展函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2werwxgjy.html

fun String.exclaim() = this + "!"
来源：http://dali.yongpay.top/Article/details/gt2vezqzncc.html

[T10] Kotlin：默认参数
来源：http://dali.cucudq.cn/Article/details/gt2udfmgptv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ivvv.top/Article/details/gt2nwrwyuzi.html

[T11] Kotlin：协程
来源：http://dali.wangdashe.top/Article/details/gt2rnkbmjvh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.feifeiyinyue.top/Article/details/gt2rnttiqgd.html

[T12] Kotlin：解构声明
来源：http://dali.nanxuanxn.top/Article/details/gt2aambbddr.html

val (a, b) = Pair(1, 2)
来源：http://dali.ivvv.top/Article/details/gt2shsiocgw.html

[T13] Kotlin：只读 Map
来源：http://dali.jyoumei.cn/Article/details/gt2tinvchiq.html

val m = mapOf("a" to 1)
来源：http://dali.meibo888.top/Article/details/gt2wbsxxnaz.html

[T14] Kotlin：循环
来源：http://dali.jiagoushi.top/Article/details/gt2uewofdyu.html

for (i in 1..10) println(i)
来源：http://dali.meibo888.top/Article/details/gt2bcwmtgsk.html

[T15] Kotlin：接口
来源：http://dali.zhoulong.xyz/Article/details/gt2isryqmsp.html

interface Shape { fun area(): Double }
来源：http://dali.gzhubu.top/Article/details/gt2kqdjmjjf.html

[T16] Swift：Hello World
来源：http://dali.cdnleiting.top/Article/details/gt2ihycfyak.html

print("Hello")
来源：http://dali.gzhubu.top/Article/details/gt2rfmdutzn.html

[T17] Swift：变量与常量
来源：http://dali.yongpay.top/Article/details/gt2tmvhafgv.html

var a = 1;  let b = 2
来源：http://dali.vqdsnc.cn/Article/details/gt2lhgtkppz.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vdyxzvob.html

"值: \(b)"
来源：http://dali.gzhubu.top/Article/details/gt2fvlddorf.html

[T19] Swift：可选绑定
来源：http://dali.nanxinkj.top/Article/details/gt2loiircfl.html

if let n = opt { print(n) }
来源：http://dali.ybcxt.top/Article/details/gt2tellipfl.html

[T20] Swift：数组操作
来源：http://dali.yj20258.top/Article/details/gt2ognvqrsv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cdnleiting.top/Article/details/gt2ipkvqtfs.html

[T21] Swift：遍历
来源：http://dali.xinyue.icu/Article/details/gt2xzttubsd.html

for x in a { print(x) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zyfztagt.html

[T22] Swift：字典
来源：http://dali.yuanzhike.top/Article/details/gt2xjxgodys.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cnezgvfn.html

[T23] Swift：函数
来源：http://dali.c1oappe.top/Article/details/gt2lhjxvllf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.iojbl.cn/Article/details/gt2uqgrhfnk.html

[T24] Swift：闭包
来源：http://dali.cdnleiting.top/Article/details/gt2lahgptux.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ehwqpu.com/Article/details/gt2pdelcezn.html

[T25] Swift：结构体
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nqgzykqs.html

struct P { var x: Int }
来源：http://dali.jqgufenzy.top/Article/details/gt2awliasgf.html

[T26] Swift：类与重写
来源：http://dali.iojbl.cn/Article/details/gt2githyiox.html

class A: Base { override func f() {} }
来源：http://dali.yuanzhike.top/Article/details/gt2xpauwmrw.html

[T27] Swift：错误处理
来源：http://dali.jyoumei.cn/Article/details/gt2kdfogtjn.html

do { try f() } catch { print(error) }
来源：http://dali.hnqzz.top/Article/details/gt2gtcajkmu.html

[T28] Swift：枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zpycjnzj.html

enum Color { case red, green }
来源：http://dali.chenjidiqi.icu/Article/details/gt2kwjkiehd.html

[T29] Swift：guard 提前返回
来源：http://dali.guannengcc.top/Article/details/gt2gntwzrkb.html

guard let x = opt else { return }
来源：http://dali.feifeiyinyue.top/Article/details/gt2oxxpvwnk.html

[T30] Swift：协议
来源：http://dali.hammf.cn/Article/details/gt2knvonzoi.html

protocol Shape { func area() -> Double }
来源：http://dali.pycfn.com/Article/details/gt2vhgmcyaa.html

[T31] Lua：Hello World
来源：http://dali.tanke756.top/Article/details/gt2xtnoqqto.html

print("Hello")
来源：http://dali.birdmap.top/Article/details/gt2fegkcpdv.html

[T32] Lua：局部变量
来源：http://dali.wangdashe.top/Article/details/gt2uolxscot.html

local a = 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vvjttdgr.html

[T33] Lua：表（数组）
来源：http://dali.zhiwuduotai.top/Article/details/gt2eefcoshe.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hammf.cn/Article/details/gt2hduecolo.html

[T34] Lua：遍历表
来源：http://dali.smart0.xyz/Article/details/gt2dmkmdogs.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.guannengcc.top/Article/details/gt2lntylmap.html

[T35] Lua：字典表
来源：http://dali.c1oappe.top/Article/details/gt2dhiuogzt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yj20258.top/Article/details/gt2csknazbg.html

[T36] Lua：函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2sbjgfpdk.html

function add(a, b) return a + b end
来源：http://dali.feifeiyinyue.top/Article/details/gt2cfzwfixd.html

[T37] Lua：字符串拼接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vcrqefdn.html

"a" .. "b"
来源：http://dali.jianghu66.top/Article/details/gt2rjweqtxo.html

[T38] Lua：条件
来源：http://dali.cashguo.top/Article/details/gt2vdgsjsbj.html

if x > 0 then print("正") end
来源：http://dali.ybcxt.top/Article/details/gt2vbhkscra.html

[T39] Lua：模式匹配
来源：http://dali.cucudq.cn/Article/details/gt2lkbpshfo.html

string.find(s, "%d+")
来源：http://dali.smart0.xyz/Article/details/gt2mzarxfzg.html

[T40] Lua：元表
来源：http://dali.jianghu66.top/Article/details/gt2gfsxkzxo.html

setmetatable({}, { __index = base })
来源：http://dali.cheryme.top/Article/details/gt2vjljclmy.html

[T41] Perl：Hello World
来源：http://dali.hfpthk.cn/Article/details/gt2rlppsdhp.html

print "Hello\n";
来源：http://dali.jianghu66.top/Article/details/gt2fzwhcmoa.html

[T42] Perl：变量类型
来源：http://dali.smart0.xyz/Article/details/gt2sjyeurzz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zovdnrgo.html

[T43] Perl：字符串插值
来源：http://dali.c1oappe.top/Article/details/gt2bqnlocsq.html

"值: $a"
来源：http://dali.xuetiantiany.cn/Article/details/gt2tmoppntw.html

[T44] Perl：条件
来源：http://dali.quarkkingdee.top/Article/details/gt2klaulfck.html

if ($a > 0) { print "正"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2gxjfcxpr.html

[T45] Perl：数组遍历
来源：http://dali.zhiwuduotai.top/Article/details/gt2odqazduv.html

for my $x (@arr) { print $x; }
来源：http://dali.316326.xyz/Article/details/gt2qjfxvewl.html

[T46] Perl：哈希操作
来源：http://dali.svipenyu.cn/Article/details/gt2yczatccy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jiagoushi.top/Article/details/gt2lkpyvync.html

[T47] Perl：正则捕获
来源：http://dali.bjfxy.top/Article/details/gt2vatpzzxu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yj20258888.top/Article/details/gt2gmaoqhox.html

[T48] Perl：正则替换
来源：http://dali.xuanzx.com/Article/details/gt2cxraircr.html

$s =~ s/old/new/g;
来源：http://dali.guannengcc.top/Article/details/gt2mvytdsnj.html

[T49] Perl：函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2ukeuytxt.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gt2kmgfnkzi.html

[T50] Perl：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gt2pgqpzthr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zneczzti.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ppjwa.cn/Article/details/gt2gnwmqzfp.html

[T51] Scala：Hello World
来源：http://dali.xuanzx.com/Article/details/gt2qfdrowfg.html

println("Hello")
来源：http://dali.yangfankeji.com/Article/details/gt2omoecphe.html

[T52] Scala：变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2ajaauang.html


<!-- 参考信息 -->