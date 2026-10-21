代发 wailian999

cmd > out.log 2>&1
来源：http://dali.jyoumei.cn/Article/details/gtnazigwkm.html

[R40] 追加写日志
来源：http://dali.gzhubu.top/Article/details/gtctitclln.html

echo "log" >> out.log
来源：http://dali.ivvv.top/Article/details/gtkbvoidvn.html

[R41] 丢弃输出
来源：http://dali.0kj1m.cn/Article/details/gtghchwzoa.html

cmd >/dev/null 2>&1
来源：http://dali.sxryk.cn/Article/details/gttzfoxdnm.html

[R42] 输入重定向
来源：http://dali.yonumen.top/Article/details/gtsyjvymdr.html

wc -l < a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtgmnlnpow.html

[R43] 按名字查找文件
来源：http://dali.chenzaomai.com/Article/details/gtxawxygln.html

find . -name "*.log" -type f
来源：http://dali.bjfxy.top/Article/details/gtfxbzdmlz.html

[R44] 按修改时间查找
来源：http://dali.dianchejie.cn/Article/details/gtyrpsdpvb.html

find . -mtime -7 -type f
来源：http://dali.shuidangran.top/Article/details/gtptphookp.html

[R45] 批量删除
来源：http://dali.yongpay.top/Article/details/gtouzahlfo.html

find . -name "*.tmp" -delete
来源：http://dali.shanyushiyangtech.top/Article/details/gtcigxdcwr.html

[R46] 递归替换文件内容
来源：http://dali.birdmap.top/Article/details/gthpyshbjj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinqigufen.top/Article/details/gtpptgwafz.html

[R47] sed 单行替换
来源：http://dali.andypj.xyz/Article/details/gtewrylkwm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtyakmkxry.html

[R48] awk 取指定列
来源：http://dali.ybcxt.top/Article/details/gtnxhbyrmt.html

awk '{print $1, $3}' a.txt
来源：http://dali.yj20258888.top/Article/details/gtipxylkfe.html

[R49] awk 带条件
来源：http://dali.wangdashe.top/Article/details/gtxjytorpu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.daria6918.cn/Article/details/gthukserxv.html

[R50] awk 求和
来源：http://dali.zdqjudy.top/Article/details/gtimxisdhp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.pycfn.com/Article/details/gtjwklsihm.html

[R51] 排序去重取前几
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkwpiexef.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuxming.cn/Article/details/gtkflnpaew.html

[R52] 统计行数
来源：http://dali.hfpthk.cn/Article/details/gtorqiennl.html

wc -l a.txt
来源：http://dali.tanke756.top/Article/details/gtnkmqjpfg.html

[R53] 查看文件头与实时尾
来源：http://dali.yangfankeji.com/Article/details/gttcyzvwrm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhiwuduotai.top/Article/details/gtqugdkjvj.html

[R54] 比较两个文件
来源：http://dali.shuidangran.top/Article/details/gtvffcvzhq.html

diff a.txt b.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzpdowdps.html

[R55] 压缩与解压
来源：http://dali.cheryme.top/Article/details/gtugeantan.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sufxvd.cn/Article/details/gtsdgkbpqx.html

[R56] 远程拷贝
来源：http://dali.chenjidiqi.icu/Article/details/gtwwxhmudp.html

scp file user@host:/path/
来源：http://dali.hysaishi.cn/Article/details/gtdeqafmps.html

[R57] 远程执行命令
来源：http://dali.smart0.xyz/Article/details/gtqlxcmulq.html

ssh user@host 'uptime'
来源：http://dali.fzhhl.top/Article/details/gtfbwziygt.html

[R58] 下载文件
来源：http://dali.sweek.top/Article/details/gtxtftjkuv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenzaomai.com/Article/details/gtxhxossdr.html

[R59] 发 POST JSON
来源：http://dali.birdmap.top/Article/details/gtgyzifhmq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sxryk.cn/Article/details/gtrfmnoylt.html

[R60] 只看 HTTP 状态码
来源：http://dali.ybcxt.top/Article/details/gtrqkhpymg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nanxuanxn.top/Article/details/gteduybjrk.html

[R61] 磁盘占用
来源：http://dali.jinqigufen.top/Article/details/gtpamnxnjx.html

df -h;  du -sh *
来源：http://dali.aizwys.cn/Article/details/gthyhjkckm.html

[R62] 找最占空间的文件
来源：http://dali.hysaishi.cn/Article/details/gtclgaeuje.html

du -ah . | sort -rh | head -10
来源：http://dali.hywenlv.cn/Article/details/gtubiyaukv.html

[R63] 内存与进程
来源：http://dali.iojbl.cn/Article/details/gtzndprypt.html

free -h;  ps aux | grep nginx
来源：http://dali.gzhubu.top/Article/details/gtlkstspzv.html

[R64] 结束进程
来源：http://dali.zhiwuduotai.top/Article/details/gtncfkpazf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hfpthk.cn/Article/details/gtoiebdybv.html

[R65] 查看端口占用
来源：http://dali.zhixingplan.top/Article/details/gtkrihnbdd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cqqwz.cn/Article/details/gtuyrkqcom.html

[R66] 定时任务
来源：http://dali.fengsongda.top/Article/details/gtitohkwqd.html

crontab -e;  crontab -l
来源：http://dali.hongshengwenyu.top/Article/details/gtcfedpqgo.html

[R67] 生成随机十六进制串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmrakahqs.html

openssl rand -hex 16
来源：http://dali.pengpengdd.cyou/Article/details/gtqicelgup.html

[R68] 计算文件校验值
来源：http://dali.wangdashe.top/Article/details/gtdijljoqk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.aizwys.cn/Article/details/gtbgygawaf.html

[R69] 生成随机密码
来源：http://dali.zhengqikj.top/Article/details/gtsxrrtyaq.html

head -c 16 /dev/urandom | base64
来源：http://dali.quarkkingdee.top/Article/details/gtrsshqfsd.html

[R70] 时间戳与互转
来源：http://dali.sxryk.cn/Article/details/gtdyutjuhh.html

date +%s;  date -d @1700000000
来源：http://dali.mhx1999.top/Article/details/gtmekqlynp.html

[R71] 日期格式化
来源：http://dali.yuanzhike.top/Article/details/gtfrbyeelt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zdqjudy.top/Article/details/gtvwbvorgy.html

[R72] 等待端口就绪
来源：http://dali.feifeiyinyue.top/Article/details/gthizkzoti.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.daxiang520.top/Article/details/gtvbystjnh.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gtzuzeezrb.html

split -l 1000 big.log part_
来源：http://dali.9152youxi.cn/Article/details/gtjjyjsvbx.html

[R74] 批量重命名
来源：http://dali.aibaodan.cn/Article/details/gtoyrktemm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yanxiufei.cn/Article/details/gtpnnafrsc.html

[R75] 导出环境变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtasmmottd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhengqikj.top/Article/details/gtzpmzdwvd.html

[R76] 使用临时文件
来源：http://dali.quarkkingdee.top/Article/details/gtmtbwyrgs.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.c1oappe.top/Article/details/gtmccolynu.html

[R77] 读取用户输入
来源：http://dali.wangshuangyany.cn/Article/details/gtqfkmgeir.html

read -rp "请输入: " ans
来源：http://dali.sysykeji.top/Article/details/gtrgbdtdme.html

[R78] 交互式菜单
来源：http://dali.hammf.cn/Article/details/gtxggjglxb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.smart0.xyz/Article/details/gtfpgwcpca.html

[R79] 解析命令行选项
来源：http://dali.andypj.xyz/Article/details/gtjfgzkrtd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xuanzx.com/Article/details/gtkehmmezt.html

[R80] 查看脚本执行耗时
来源：http://dali.ydzc1.top/Article/details/gtbadvxemc.html

time ./run.sh
来源：http://dali.gzhubu.top/Article/details/gtpkavcjky.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gthequfwec.html

S. C / C++ 专题
来源：http://dali.gzhubu.top/Article/details/gtzfulgkyx.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtcgqhcclp.html

[S01] C：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtpyhdchcw.html

#include <stdio.h>
来源：http://dali.daxiang520.top/Article/details/gtwhzfietw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xinyue.icu/Article/details/gtmxfdmoas.html

[S02] C：变量与格式化输出
来源：http://dali.nanxinkj.top/Article/details/gtjrrisawt.html

int a = 10; printf("%d\n", a);
来源：http://dali.fzhhl.top/Article/details/gtgictzgtw.html

[S03] C：读入整数
来源：http://dali.zhoulong.xyz/Article/details/gtypzeijww.html

int x; scanf("%d", &x);
来源：http://dali.hfpthk.cn/Article/details/gtptyznnkd.html

[S04] C：字符串复制
来源：http://dali.ydzc1.top/Article/details/gtgyhpfnwu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xuanzx.com/Article/details/gtsbqwkuwg.html

[S05] C：字符串长度
来源：http://dali.pengpengdd.cyou/Article/details/gtphkdmrpa.html

strlen(s)
来源：http://dali.bjfxy.top/Article/details/gtucdjzbyp.html

[S06] C：字符串比较
来源：http://dali.sysykeji.top/Article/details/gtmvdbfvtq.html

strcmp(a, b) == 0
来源：http://dali.xuetiantiany.cn/Article/details/gtourziakw.html

[S07] C：数组遍历求和
来源：http://dali.guowangkeji.top/Article/details/gtzlgjirah.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jlsjyb.cn/Article/details/gteeluoptu.html

[S08] C：动态内存分配与释放
来源：http://dali.wangdashe.top/Article/details/gtbiehqlig.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.wangshuangyany.cn/Article/details/gtmhnorech.html

[S09] C：结构体定义与初始化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtklxiekjh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.pycfn.com/Article/details/gtsqsvqzhz.html

[S10] C：指针与解引用
来源：http://dali.xuetiantiany.cn/Article/details/gtasccggmh.html

int *p = &a;  *p = 5;
来源：http://dali.daria6918.cn/Article/details/gtwbazwvvb.html

[S11] C：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkuhzewwd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xziqi.cn/Article/details/gtfoosuvwq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cqqwz.cn/Article/details/gtkooqfdpz.html

fclose(f);
来源：http://dali.shzxlz.cn/Article/details/gtavoebiwb.html

[S12] C：写文件
来源：http://dali.meibo888.top/Article/details/gtfqrdjecv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yvedp.cn/Article/details/gtnaipjluf.html

[S13] C：宏定义
来源：http://dali.cheryme.top/Article/details/gtcrfsaozm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cashguo.top/Article/details/gtfiolptuy.html

[S14] C：枚举
来源：http://dali.gaohongyu789.top/Article/details/gtyimsijbr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.nanxuanxn.top/Article/details/gtzqvayfga.html

[S15] C：类型转换
来源：http://dali.pengpengdd.cyou/Article/details/gttqtrhxyu.html

(double) a / b
来源：http://dali.xziqi.cn/Article/details/gtuaulccjl.html

[S16] C：位操作置位
来源：http://dali.kuanghao11.cn/Article/details/gtpihgqctq.html

x |= (1 << 3);
来源：http://dali.kuanghao11.cn/Article/details/gtbzqeacwb.html

[S17] C：安全拼接字符串
来源：http://dali.yuxming.cn/Article/details/gtubxaxnho.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hfpthk.cn/Article/details/gtutmddjty.html

[S18] C：命令行参数
来源：http://dali.ppjwa.cn/Article/details/gteodzlzpp.html

int main(int argc, char **argv)
来源：http://dali.jiagoushi.top/Article/details/gtvkchfsbp.html

[S19] C：快速排序
来源：http://dali.yanxiufei.cn/Article/details/gtoiiwkjvc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xinyue.icu/Article/details/gtkykwgebz.html

[S20] C：二分查找
来源：http://dali.xuetiantiany.cn/Article/details/gtdaogwnzv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.kuanghao11.cn/Article/details/gtrfezldvb.html

[S21] C：字符类别判断
来源：http://dali.yj20258888.top/Article/details/gtfnqhggve.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ydzc1.top/Article/details/gtzyhlgsqw.html

[S22] C：字符串转数字
来源：http://dali.birdmap.top/Article/details/gtejemdrrw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gtkduvenhq.html

[S23] C：随机数
来源：http://dali.xylfe.cn/Article/details/gtzdmasoxe.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkkiribzp.html

[S24] C：获取本地时间
来源：http://dali.zhoulong.xyz/Article/details/gtjhopzrec.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xuanzx.com/Article/details/gtvmdlromy.html

[S25] C：内存拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gtuvumojsz.html

memcpy(dst, src, n);
来源：http://dali.316326.xyz/Article/details/gtrbwfetyp.html

[S26] C：内存清零
来源：http://dali.jinqigufen.top/Article/details/gtuyfyxbmd.html

memset(a, 0, sizeof a);
来源：http://dali.yj20258888.top/Article/details/gtivozngjs.html

[S27] C：定义常量
来源：http://dali.ybcxt.top/Article/details/gtvujtcoea.html

const double PI = 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gtmhjvntzl.html

[S28] C：静态变量
来源：http://dali.hammf.cn/Article/details/gtfufgzhqn.html

static int counter = 0;
来源：http://dali.gogol.net.cn/Article/details/gtugoabohz.html

[S29] C：变参函数
来源：http://dali.shuidangran.top/Article/details/gtdistnbvr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gogol.net.cn/Article/details/gtylzfyylv.html

[S30] C：头文件保护
来源：http://dali.xziqi.cn/Article/details/gtjpogadhw.html

#ifndef X_H
来源：http://dali.c1oappe.top/Article/details/gtecjochco.html

#define X_H
来源：http://dali.yj20258888.top/Article/details/gtfiydomek.html

#endif
来源：http://dali.jqgufenzy.top/Article/details/gtawuilwvo.html

[S31] C++：Hello World
来源：http://dali.yongpay.top/Article/details/gtsmyvarkf.html

#include <iostream>
来源：http://dali.bjfxy.top/Article/details/gtbdyldwsf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtkkmqkekd.html

[S32] C++：字符串
来源：http://dali.birdmap.top/Article/details/gtuemezbph.html

std::string s = "hi";  s += "!";
来源：http://dali.xuetiantiany.cn/Article/details/gtvqnjwfdt.html

[S33] C++：vector 增删
来源：http://dali.chenlongwang.top/Article/details/gtshhvuisk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tanke756.top/Article/details/gtgvcywfpw.html

[S34] C++：遍历 vector
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqeacrxh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.iojbl.cn/Article/details/gtkqmklurt.html

[S35] C++：map
来源：http://dali.gzhubu.top/Article/details/gttlnqgllx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.havefunace.top/Article/details/gtuftkjekg.html

[S36] C++：unordered_map
来源：http://dali.mhx1999.top/Article/details/gtuhuvgqfq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtdbshmqie.html

[S37] C++：set
来源：http://dali.zycfv.cn/Article/details/gtnyxaszuj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenlongwang.top/Article/details/gtiywktuna.html

[S38] C++：排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkgazfkjx.html

std::sort(v.begin(), v.end());
来源：http://dali.tianlin.xyz/Article/details/gtmknsohnu.html

[S39] C++：自定义比较器排序
来源：http://dali.yueranfly.top/Article/details/gthcmujyie.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.fzhhl.top/Article/details/gtxyhqjhmb.html

[S40] C++：查找元素
来源：http://dali.daxiang520.top/Article/details/gtjasgiyle.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gotoacloud.top/Article/details/gtchizncrk.html

[S41] C++：类与构造函数
来源：http://dali.wangshuangyany.cn/Article/details/gtcbfenofl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sweek.top/Article/details/gtnoutkcpi.html

[S42] C++：继承与虚函数
来源：http://dali.zhongyouzk.top/Article/details/gtpkneufif.html

class B : public Base { public: void f() override {} };
来源：http://dali.cashguo.top/Article/details/gtjrdubteo.html

[S43] C++：智能指针
来源：http://dali.chenzaomai.com/Article/details/gtzdsxsykv.html

auto p = std::make_unique<int>(5);
来源：http://dali.cqqwz.cn/Article/details/gtfmspfoef.html

[S44] C++：引用传参
来源：http://dali.jlsjyb.cn/Article/details/gtncgjdywh.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gtmlpahibf.html

[S45] C++：lambda
来源：http://dali.jinqigufen.top/Article/details/gtwfrapcpt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nanxuanxn.top/Article/details/gthotizxtz.html

[S46] C++：函数模板
来源：http://dali.jinqigfzy.top/Article/details/gtoxfdvona.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jqgufenzy.top/Article/details/gtmwypydld.html

[S47] C++：结构化绑定遍历
来源：http://dali.xinyue.icu/Article/details/gtutvzkqwq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tian-w.cn/Article/details/gtnutgngxm.html

[S48] C++：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gtnarzzeod.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.meibo888.top/Article/details/gtcqtoagol.html

while (std::getline(in, line)) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxxmqcsub.html

[S49] C++：写文件
来源：http://dali.hnqzz.top/Article/details/gtoatujmqv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sxryk.cn/Article/details/gtbsqvvitk.html

[S50] C++：格式化数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gtflxsnodd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gtopuvgfxt.html

[S51] C++：显式类型转换
来源：http://dali.jianghu66.top/Article/details/gtginjmxov.html

static_cast<double>(a) / b
来源：http://dali.quarkkingdee.top/Article/details/gtzdgxasut.html

[S52] C++：const 与 noexcept
来源：http://dali.sxryk.cn/Article/details/gtgykyxjcc.html

int size() const noexcept { return n_; }
来源：http://dali.zhixingplan.top/Article/details/gtfpxscjcr.html

[S53] C++：移动语义
来源：http://dali.tianlin.xyz/Article/details/gtlfnlcgxi.html

std::vector<int> w = std::move(v);
来源：http://dali.yueranfly.top/Article/details/gthaazvldy.html

[S54] C++：异常处理
来源：http://dali.jinqigfzy.top/Article/details/gtwnhujdbi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.fzhhl.top/Article/details/gtnzraxsth.html

[S55] C++：结构化绑定
来源：http://dali.jyoumei.cn/Article/details/gtzaubsevg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinqigufen.top/Article/details/gtvnuhpvtw.html

[S56] C++：optional
来源：http://dali.sysykeji.top/Article/details/gtyynwksgy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtusjjvtuo.html

[S57] C++：编译期常量
来源：http://dali.fzhhl.top/Article/details/gtrgvosiat.html

constexpr int N = 10;
来源：http://dali.bjfxy.top/Article/details/gtzmxqxusd.html

[S58] C++：命名空间
来源：http://dali.hywenlv.cn/Article/details/gtlkalyxub.html

namespace ns { int f() { return 1; } }
来源：http://dali.svipenyu.cn/Article/details/gtclmtyxms.html

[S59] C++：静态断言
来源：http://dali.gzhubu.top/Article/details/gtjxmhzitc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.mhx1999.top/Article/details/gtzvsmvcyi.html

[S60] C++：遍历并删除元素
来源：http://dali.zhengqikj.top/Article/details/gtsltxvndu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.aizwys.cn/Article/details/gteohllvke.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtyvshhapa.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.fzhhl.top/Article/details/gtuqxmcmvu.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtmvzzdwgo.html

[T01] Kotlin：Hello World
来源：http://dali.redwolf501.top/Article/details/gtiiczgblg.html

println("Hello")
来源：http://dali.yangfankeji.com/Article/details/gtoxcqwhkn.html

[T02] Kotlin：变量
来源：http://dali.ivvv.top/Article/details/gtqfasbrtj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hammf.cn/Article/details/gtlgivdmlv.html

[T03] Kotlin：字符串模板
来源：http://dali.cheryme.top/Article/details/gtiiuhbtsv.html

"值: $b"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcvvofmtz.html

[T04] Kotlin：空安全
来源：http://dali.sweek.top/Article/details/gtjoeoryle.html

val n: String? = null;  n?.length
来源：http://dali.yj20258888.top/Article/details/gtxkbufkzy.html

[T05] Kotlin：when 表达式
来源：http://dali.xylfe.cn/Article/details/gtxywkgtny.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.kuanghao11.cn/Article/details/gtuapxsuox.html

[T06] Kotlin：集合映射
来源：http://dali.ivvv.top/Article/details/gtkgqkkosn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.bjfxy.top/Article/details/gtcxhsdviw.html

[T07] Kotlin：集合过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrjhkyxr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tanke756.top/Article/details/gthjvqozee.html

[T08] Kotlin：数据类
来源：http://dali.yuxming.cn/Article/details/gtudxjtdmr.html

data class User(val name: String, val age: Int)
来源：http://dali.yj202588.top/Article/details/gtijyugisc.html

[T09] Kotlin：扩展函数
来源：http://dali.nanxuanxn.top/Article/details/gtgucwyjur.html

fun String.exclaim() = this + "!"
来源：http://dali.iojbl.cn/Article/details/gtrcxlamrw.html

[T10] Kotlin：默认参数
来源：http://dali.jiagoushi.top/Article/details/gtdmxqagjs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.tianlin.xyz/Article/details/gtfwyooevv.html

[T11] Kotlin：协程
来源：http://dali.redwolf501.top/Article/details/gtvbrevzzv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdubqvhze.html

[T12] Kotlin：解构声明
来源：http://dali.jyoumei.cn/Article/details/gtjdkuhftf.html

val (a, b) = Pair(1, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtowvkkobm.html

[T13] Kotlin：只读 Map
来源：http://dali.yuanzhike.top/Article/details/gtafhihwow.html

val m = mapOf("a" to 1)
来源：http://dali.jlsjyb.cn/Article/details/gtoxqonrnb.html

[T14] Kotlin：循环
来源：http://dali.yangfankeji.com/Article/details/gtsvkwlcan.html

for (i in 1..10) println(i)
来源：http://dali.havefunace.top/Article/details/gthtkeksbu.html

[T15] Kotlin：接口
来源：http://dali.jiagoushi.top/Article/details/gtxxwoxyzl.html

interface Shape { fun area(): Double }
来源：http://dali.cheryme.top/Article/details/gtkghkpxol.html

[T16] Swift：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtdjujogna.html

print("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gtsdlifyoa.html

[T17] Swift：变量与常量
来源：http://dali.sxryk.cn/Article/details/gtzhmngvff.html

var a = 1;  let b = 2
来源：http://dali.wangdashe.top/Article/details/gtnpwlezie.html

[T18] Swift：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gtlxdwyhwf.html

"值: \(b)"
来源：http://dali.havefunace.top/Article/details/gtkmjsfqzi.html

[T19] Swift：可选绑定
来源：http://dali.sufxvd.cn/Article/details/gtqutzvnws.html

if let n = opt { print(n) }
来源：http://dali.dashuyun.cn/Article/details/gtjktmqpwp.html

[T20] Swift：数组操作
来源：http://dali.quarkkingdee.top/Article/details/gtepljwbdi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.vqdsnc.cn/Article/details/gtkwftyfvo.html

[T21] Swift：遍历
来源：http://dali.sxryk.cn/Article/details/gtzmnhvwdx.html

for x in a { print(x) }
来源：http://dali.chenzaomai.com/Article/details/gtjvztficc.html

[T22] Swift：字典
来源：http://dali.xuetiantiany.cn/Article/details/gtrueknhsg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hongshengwenyu.top/Article/details/gtprmhajkb.html

[T23] Swift：函数
来源：http://dali.xinyue.icu/Article/details/gtdcdwkqaf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tanke756.top/Article/details/gtcasdizva.html

[T24] Swift：闭包
来源：http://dali.redwolf501.top/Article/details/gtpuzusjgo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shuidangran.top/Article/details/gtagahullz.html

[T25] Swift：结构体
来源：http://dali.c1oappe.top/Article/details/gtdtknlpmc.html

struct P { var x: Int }
来源：http://dali.ydzc1.top/Article/details/gttdontnnb.html

[T26] Swift：类与重写
来源：http://dali.hfpthk.cn/Article/details/gtoaeeqemm.html

class A: Base { override func f() {} }
来源：http://dali.dianchejie.cn/Article/details/gttnlkjlgo.html

[T27] Swift：错误处理
来源：http://dali.sweek.top/Article/details/gtwdbrsvam.html

do { try f() } catch { print(error) }
来源：http://dali.ybcxt.top/Article/details/gtguocyyep.html

[T28] Swift：枚举
来源：http://dali.zdqjudy.top/Article/details/gtslvlcwqk.html

enum Color { case red, green }
来源：http://dali.andypj.xyz/Article/details/gtyhiebybm.html

[T29] Swift：guard 提前返回
来源：http://dali.gogol.net.cn/Article/details/gtswysnfir.html

guard let x = opt else { return }
来源：http://dali.c1oappe.top/Article/details/gtprgrihts.html

[T30] Swift：协议
来源：http://dali.yanxiufei.cn/Article/details/gtbxkckfhx.html

protocol Shape { func area() -> Double }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtebxumlbg.html

[T31] Lua：Hello World
来源：http://dali.cqqwz.cn/Article/details/gthknkqoad.html

print("Hello")
来源：http://dali.sysykeji.top/Article/details/gtdbzeckpi.html

[T32] Lua：局部变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqwfsboqp.html

local a = 1
来源：http://dali.ehwqpu.com/Article/details/gtpstnmdam.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gtzoyoqjgm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yj202588.top/Article/details/gtsbckvqss.html

[T34] Lua：遍历表
来源：http://dali.chenlongwang.top/Article/details/gtcebpflir.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.birdmap.top/Article/details/gtmbtaikfl.html

[T35] Lua：字典表
来源：http://dali.shanyushiyangkeji.top/Article/details/gteidnbgrh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.9152youxi.cn/Article/details/gtsoblwfrh.html

[T36] Lua：函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhmfnerw.html

function add(a, b) return a + b end
来源：http://dali.yvedp.cn/Article/details/gtwpoutbnd.html

[T37] Lua：字符串拼接
来源：http://dali.cheryme.top/Article/details/gtjufdiice.html

"a" .. "b"
来源：http://dali.ivvv.top/Article/details/gtdarrojbk.html

[T38] Lua：条件
来源：http://dali.wangshuangyany.cn/Article/details/gtzfuwvynn.html

if x > 0 then print("正") end
来源：http://dali.jinqigufen.top/Article/details/gtkahcqckm.html

[T39] Lua：模式匹配
来源：http://dali.cucudq.cn/Article/details/gtfufzvfev.html

string.find(s, "%d+")
来源：http://dali.hywenlv.cn/Article/details/gttnvsfqwn.html

[T40] Lua：元表
来源：http://dali.haohaochexian.top/Article/details/gtslnsrdhw.html

setmetatable({}, { __index = base })
来源：http://dali.haohaochexian.top/Article/details/gtmzwlbviv.html

[T41] Perl：Hello World
来源：http://dali.iojbl.cn/Article/details/gtusjokzqe.html

print "Hello\n";
来源：http://dali.yanxiufei.cn/Article/details/gtwgrsgenp.html

[T42] Perl：变量类型
来源：http://dali.shangyingyoupin.top/Article/details/gtuaksfmnr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jqgufenzy.top/Article/details/gtvrxqitty.html


<!-- 参考信息 -->