代发 wailian999

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tanke756.top/Article/details/gtqskxrgaa.html

[R36] 并发执行多个任务
来源：http://dali.yuxming.cn/Article/details/gtpygvwxyn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.redwolf501.top/Article/details/gtiomqqqpg.html

[R37] 把输出赋给变量
来源：http://dali.zhixingplan.top/Article/details/gtqythhrsv.html

files=$(ls -1)
来源：http://dali.xylfe.cn/Article/details/gtjchonnzl.html

[R38] 管道串联
来源：http://dali.cucudq.cn/Article/details/gtpadfrydn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cheryme.top/Article/details/gtvreoopel.html

[R39] 重定向标准输出与错误
来源：http://dali.aizwys.cn/Article/details/gtbrlevhxt.html

cmd > out.log 2>&1
来源：http://dali.yueranfly.top/Article/details/gtockstuat.html

[R40] 追加写日志
来源：http://dali.redwolf501.top/Article/details/gtnozpdnum.html

echo "log" >> out.log
来源：http://dali.daria6918.cn/Article/details/gthjzgialq.html

[R41] 丢弃输出
来源：http://dali.xinyue.icu/Article/details/gtboxzvgjw.html

cmd >/dev/null 2>&1
来源：http://dali.zhixingplan.top/Article/details/gtrzxiwjjm.html

[R42] 输入重定向
来源：http://dali.yuxming.cn/Article/details/gtwompixix.html

wc -l < a.txt
来源：http://dali.nanxinkj.top/Article/details/gtqhxrhzvz.html

[R43] 按名字查找文件
来源：http://dali.hnxiangtu.top/Article/details/gteedzagvb.html

find . -name "*.log" -type f
来源：http://dali.c1oappe.top/Article/details/gtpqqhekdt.html

[R44] 按修改时间查找
来源：http://dali.redwolf501.top/Article/details/gtuyxiskds.html

find . -mtime -7 -type f
来源：http://dali.hfpthk.cn/Article/details/gtarjtlrbx.html

[R45] 批量删除
来源：http://dali.chenzaomai.com/Article/details/gtjltvasvp.html

find . -name "*.tmp" -delete
来源：http://dali.guowangkeji.top/Article/details/gtxnvnnhjl.html

[R46] 递归替换文件内容
来源：http://dali.tianlin.xyz/Article/details/gtikaxbufm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hywenlv.cn/Article/details/gtczjqrtli.html

[R47] sed 单行替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhltmpch.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.c1oappe.top/Article/details/gtztnwsdzm.html

[R48] awk 取指定列
来源：http://dali.iojbl.cn/Article/details/gtbvuutozy.html

awk '{print $1, $3}' a.txt
来源：http://dali.xylfe.cn/Article/details/gtridzobtu.html

[R49] awk 带条件
来源：http://dali.guowangkeji.top/Article/details/gtdjlxqvom.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.iojbl.cn/Article/details/gtvsgztiwd.html

[R50] awk 求和
来源：http://dali.yj202588.top/Article/details/gtskjarirz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ehwqpu.com/Article/details/gtbbvfwwcy.html

[R51] 排序去重取前几
来源：http://dali.0kj1m.cn/Article/details/gtzfzswxqs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenzaomai.com/Article/details/gtnnolviou.html

[R52] 统计行数
来源：http://dali.jiagoushi.top/Article/details/gtvgvhekev.html

wc -l a.txt
来源：http://dali.daxiang520.top/Article/details/gtqulsdire.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gtbbocxfrq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jqgfzy.top/Article/details/gtdzgkcwhr.html

[R54] 比较两个文件
来源：http://dali.shuidangran.top/Article/details/gtdyvxheyr.html

diff a.txt b.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtncomhkft.html

[R55] 压缩与解压
来源：http://dali.ehwqpu.com/Article/details/gtxbrtoqyq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.meibo888.top/Article/details/gtlwcayavb.html

[R56] 远程拷贝
来源：http://dali.yongpay.top/Article/details/gtknnvtkgd.html

scp file user@host:/path/
来源：http://dali.nanxuanxn.top/Article/details/gtfcafbwah.html

[R57] 远程执行命令
来源：http://dali.redwolf501.top/Article/details/gtptckzrbg.html

ssh user@host 'uptime'
来源：http://dali.haohaochexian.top/Article/details/gtgfqtjjgg.html

[R58] 下载文件
来源：http://dali.xinyue.icu/Article/details/gtsjpfxcgd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ehwqpu.com/Article/details/gtmqssyddk.html

[R59] 发 POST JSON
来源：http://dali.jlsjyb.cn/Article/details/gtlxoqxeaj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhongyouzk.top/Article/details/gttssoxxzj.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbcvbxsg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gzhubu.top/Article/details/gtxiodumad.html

[R61] 磁盘占用
来源：http://dali.zhiwuduotai.top/Article/details/gtlsftnthf.html

df -h;  du -sh *
来源：http://dali.cashguo.top/Article/details/gtyadfoghu.html

[R62] 找最占空间的文件
来源：http://dali.zhengqikj.top/Article/details/gtdgcydfla.html

du -ah . | sort -rh | head -10
来源：http://dali.iojbl.cn/Article/details/gtfqlqfxid.html

[R63] 内存与进程
来源：http://dali.birdmap.top/Article/details/gtzqhvzjyo.html

free -h;  ps aux | grep nginx
来源：http://dali.hfpthk.cn/Article/details/gtqjeroahy.html

[R64] 结束进程
来源：http://dali.tanke756.top/Article/details/gthtmpumgn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hfpthk.cn/Article/details/gtlqykrziz.html

[R65] 查看端口占用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlqxtctxp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xinyue.icu/Article/details/gtnlrahlvk.html

[R66] 定时任务
来源：http://dali.zhoulong.xyz/Article/details/gtlaxobocd.html

crontab -e;  crontab -l
来源：http://dali.gogol.net.cn/Article/details/gtxrlluxsp.html

[R67] 生成随机十六进制串
来源：http://dali.c1oappe.top/Article/details/gtpdntgwgr.html

openssl rand -hex 16
来源：http://dali.zdqjudy.top/Article/details/gtyhmcuedk.html

[R68] 计算文件校验值
来源：http://dali.bjfxy.top/Article/details/gtxkzvwetp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cheryme.top/Article/details/gtddhincsd.html

[R69] 生成随机密码
来源：http://dali.guannengcc.top/Article/details/gtwpoxnmeo.html

head -c 16 /dev/urandom | base64
来源：http://dali.316326.xyz/Article/details/gtiwwsenqs.html

[R70] 时间戳与互转
来源：http://dali.hysaishi.cn/Article/details/gtdxqouwcn.html

date +%s;  date -d @1700000000
来源：http://dali.jinghuilouyu.cn/Article/details/gtonkscqce.html

[R71] 日期格式化
来源：http://dali.jiagoushi.top/Article/details/gtxbenxbso.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.havefunace.top/Article/details/gttfzmrggb.html

[R72] 等待端口就绪
来源：http://dali.fzhhl.top/Article/details/gteogtnmek.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yonumen.top/Article/details/gtqzgiauwq.html

[R73] 分割大日志
来源：http://dali.chenzaomai.com/Article/details/gtwqwexdqs.html

split -l 1000 big.log part_
来源：http://dali.jqgfzy.top/Article/details/gtjrcmanlm.html

[R74] 批量重命名
来源：http://dali.hnxiangtu.top/Article/details/gtbquxkuhm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenlongwang.top/Article/details/gtxojkozwz.html

[R75] 导出环境变量
来源：http://dali.gogol.net.cn/Article/details/gtvcuuoxpq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.nanxinkj.top/Article/details/gthzuceoat.html

[R76] 使用临时文件
来源：http://dali.sysykeji.top/Article/details/gtzceetotc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cheryme.top/Article/details/gtvqmgwiqe.html

[R77] 读取用户输入
来源：http://dali.yangfankeji.com/Article/details/gtovjcpnbm.html

read -rp "请输入: " ans
来源：http://dali.daria6918.cn/Article/details/gtltlvpata.html

[R78] 交互式菜单
来源：http://dali.sufxvd.cn/Article/details/gtafmwmmak.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.smart0.xyz/Article/details/gtyuzbkjkw.html

[R79] 解析命令行选项
来源：http://dali.cqqwz.cn/Article/details/gtidyuegzm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj20258.top/Article/details/gtaxerlldc.html

[R80] 查看脚本执行耗时
来源：http://dali.sufxvd.cn/Article/details/gtoyjqsgnp.html

time ./run.sh
来源：http://dali.iojbl.cn/Article/details/gtcdmvvsiu.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtgqrjzzkf.html

S. C / C++ 专题
来源：http://dali.zycfv.cn/Article/details/gtfoxhngpa.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gteqztqdtt.html

[S01] C：Hello World
来源：http://dali.pycfn.com/Article/details/gtkkidmxxw.html

#include <stdio.h>
来源：http://dali.sysykeji.top/Article/details/gtrrqmkcxs.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhengqikj.top/Article/details/gtttjmgbld.html

[S02] C：变量与格式化输出
来源：http://dali.iojbl.cn/Article/details/gtklfltjfu.html

int a = 10; printf("%d\n", a);
来源：http://dali.cdnleiting.top/Article/details/gtwwjjmunz.html

[S03] C：读入整数
来源：http://dali.yueranfly.top/Article/details/gtkqwxxwrz.html

int x; scanf("%d", &x);
来源：http://dali.shangyingyoupin.top/Article/details/gtbekcrinp.html

[S04] C：字符串复制
来源：http://dali.pengpengdd.cyou/Article/details/gtlsreqqzo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xinyue.icu/Article/details/gtdxljooxj.html

[S05] C：字符串长度
来源：http://dali.andypj.xyz/Article/details/gtoiokagak.html

strlen(s)
来源：http://dali.zdqjudy.top/Article/details/gtwvodcdjk.html

[S06] C：字符串比较
来源：http://dali.daria6918.cn/Article/details/gtnogkicru.html

strcmp(a, b) == 0
来源：http://dali.snrcjt.cn/Article/details/gtemoosoqi.html

[S07] C：数组遍历求和
来源：http://dali.birdmap.top/Article/details/gtgrtavqxz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.daxiang520.top/Article/details/gtjozcwcoa.html

[S08] C：动态内存分配与释放
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgvjpooka.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xylfe.cn/Article/details/gtuxzqfihj.html

[S09] C：结构体定义与初始化
来源：http://dali.zhixingplan.top/Article/details/gtqswsvrzf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenlongwang.top/Article/details/gtlunwqhtr.html

[S10] C：指针与解引用
来源：http://dali.0kj1m.cn/Article/details/gtepqtnqql.html

int *p = &a;  *p = 5;
来源：http://dali.pengpengdd.cyou/Article/details/gtsbmwckjm.html

[S11] C：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gtyxaxeeqo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nwbrower.top/Article/details/gtbabjriks.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.redwolf501.top/Article/details/gtbotkfvqu.html

fclose(f);
来源：http://dali.nanxinkj.top/Article/details/gtolywcbza.html

[S12] C：写文件
来源：http://dali.yangfankeji.com/Article/details/gtvhtfkrpb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenzaomai.com/Article/details/gtqduybode.html

[S13] C：宏定义
来源：http://dali.mhx1999.top/Article/details/gtvoevaeol.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gogol.net.cn/Article/details/gtibdviwcb.html

[S14] C：枚举
来源：http://dali.cucudq.cn/Article/details/gtfbtcwdpi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhixingplan.top/Article/details/gtmohtfdeb.html

[S15] C：类型转换
来源：http://dali.hnqzz.top/Article/details/gttxxfezcq.html

(double) a / b
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqkklgcs.html

[S16] C：位操作置位
来源：http://dali.vqdsnc.cn/Article/details/gtsgyflglt.html

x |= (1 << 3);
来源：http://dali.daria6918.cn/Article/details/gtzcfhpuso.html

[S17] C：安全拼接字符串
来源：http://dali.jyoumei.cn/Article/details/gtkyiwulgr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.pengpengdd.cyou/Article/details/gtuawdseuh.html

[S18] C：命令行参数
来源：http://dali.shzxlz.cn/Article/details/gtjvueqegi.html

int main(int argc, char **argv)
来源：http://dali.zdqjudy.top/Article/details/gtrcznlpiy.html

[S19] C：快速排序
来源：http://dali.sysykeji.top/Article/details/gtbtkwmdzd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xylfe.cn/Article/details/gtbrdysudj.html

[S20] C：二分查找
来源：http://dali.pengpengdd.cyou/Article/details/gtvqtfdtee.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nanxuanxn.top/Article/details/gtiuzutvvq.html

[S21] C：字符类别判断
来源：http://dali.nwbrower.top/Article/details/gtmplfyvdp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gaohongyu789.top/Article/details/gtpzskohil.html

[S22] C：字符串转数字
来源：http://dali.jinghuilouyu.cn/Article/details/gtqzgohcij.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.aibaodan.cn/Article/details/gtnglgqhar.html

[S23] C：随机数
来源：http://dali.316326.xyz/Article/details/gtgqxoiphm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.snrcjt.cn/Article/details/gtofgztjob.html

[S24] C：获取本地时间
来源：http://dali.snrcjt.cn/Article/details/gtkvkotlmb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.svipenyu.cn/Article/details/gtkdotvehn.html

[S25] C：内存拷贝
来源：http://dali.cashguo.top/Article/details/gtevkltjpf.html

memcpy(dst, src, n);
来源：http://dali.dianchejie.cn/Article/details/gtsefrwizu.html

[S26] C：内存清零
来源：http://dali.tian-w.cn/Article/details/gtwqgtnmbv.html

memset(a, 0, sizeof a);
来源：http://dali.hammf.cn/Article/details/gtaogcmvbb.html

[S27] C：定义常量
来源：http://dali.yvedp.cn/Article/details/gtblblurbg.html

const double PI = 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmzhkopcp.html

[S28] C：静态变量
来源：http://dali.jqgfzy.top/Article/details/gtcchddwcd.html

static int counter = 0;
来源：http://dali.gzhubu.top/Article/details/gtvsrdpgxx.html

[S29] C：变参函数
来源：http://dali.jianghu66.top/Article/details/gthvznxhtn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj202588.top/Article/details/gtownopnlf.html

[S30] C：头文件保护
来源：http://dali.fzhhl.top/Article/details/gtmcnbvuap.html

#ifndef X_H
来源：http://dali.fengsongda.top/Article/details/gtxcmlacak.html

#define X_H
来源：http://dali.kuanghao11.cn/Article/details/gtqjxsmosg.html

#endif
来源：http://dali.cucudq.cn/Article/details/gtooorxuys.html

[S31] C++：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtgoousfas.html

#include <iostream>
来源：http://dali.haohaochexian.top/Article/details/gtbglsfepe.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sufxvd.cn/Article/details/gtawuarjhq.html

[S32] C++：字符串
来源：http://dali.gotoacloud.top/Article/details/gtiprapdro.html

std::string s = "hi";  s += "!";
来源：http://dali.ydzc1.top/Article/details/gtkyndtsna.html

[S33] C++：vector 增删
来源：http://dali.chenzaomai.com/Article/details/gtvsejmmpr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.havefunace.top/Article/details/gtrhyiyxrn.html

[S34] C++：遍历 vector
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlemtkmho.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.havefunace.top/Article/details/gtpfjzvvng.html

[S35] C++：map
来源：http://dali.hammf.cn/Article/details/gtajwxlxxi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gtzvysykde.html

[S36] C++：unordered_map
来源：http://dali.shangyingyoupin.top/Article/details/gtmynwidvc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sysykeji.top/Article/details/gtkgnpnzyj.html

[S37] C++：set
来源：http://dali.zhixingplan.top/Article/details/gtmqflsmwy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.havefunace.top/Article/details/gtpaqatqwh.html

[S38] C++：排序
来源：http://dali.svipenyu.cn/Article/details/gtycsaajjr.html

std::sort(v.begin(), v.end());
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlngnqjfe.html

[S39] C++：自定义比较器排序
来源：http://dali.shangyingyoupin.top/Article/details/gtmjgbnwgu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gtyhxwdpff.html

[S40] C++：查找元素
来源：http://dali.haohaochexian.top/Article/details/gtcifevvek.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yangfankeji.com/Article/details/gtqjzmgxen.html

[S41] C++：类与构造函数
来源：http://dali.snrcjt.cn/Article/details/gtyeojkyyn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnxiangtu.top/Article/details/gtejsbgood.html

[S42] C++：继承与虚函数
来源：http://dali.aibaodan.cn/Article/details/gtqlkgbrbo.html

class B : public Base { public: void f() override {} };
来源：http://dali.chenlongwang.top/Article/details/gtvsxbngne.html

[S43] C++：智能指针
来源：http://dali.yueranfly.top/Article/details/gtbdfmiwlw.html

auto p = std::make_unique<int>(5);
来源：http://dali.ehwqpu.com/Article/details/gthtrjcsbp.html

[S44] C++：引用传参
来源：http://dali.yonumen.top/Article/details/gtdmpkoldw.html

void inc(int &x) { ++x; }
来源：http://dali.hnxiangtu.top/Article/details/gtntpixxmq.html

[S45] C++：lambda
来源：http://dali.jqgfzy.top/Article/details/gtooqmvlke.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nanxinkj.top/Article/details/gtfacgferg.html

[S46] C++：函数模板
来源：http://dali.chenzaomai.com/Article/details/gtorfsqiqz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.316326.xyz/Article/details/gtsqoncxuv.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gthjusiqig.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.nanxuanxn.top/Article/details/gtmkskvxpj.html

[S48] C++：逐行读文件
来源：http://dali.cashguo.top/Article/details/gtyyapuchg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj20258.top/Article/details/gtlosgsexk.html

while (std::getline(in, line)) { }
来源：http://dali.snrcjt.cn/Article/details/gtcmylpseg.html

[S49] C++：写文件
来源：http://dali.tian-w.cn/Article/details/gtmbjwxrik.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sysykeji.top/Article/details/gtsprzhxmi.html

[S50] C++：格式化数字
来源：http://dali.birdmap.top/Article/details/gthflllgpd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gtvapxqlgf.html

[S51] C++：显式类型转换
来源：http://dali.hfpthk.cn/Article/details/gtqalvftey.html

static_cast<double>(a) / b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtracckflh.html

[S52] C++：const 与 noexcept
来源：http://dali.feifeiyinyue.top/Article/details/gtqawcsulo.html

int size() const noexcept { return n_; }
来源：http://dali.jinqigfzy.top/Article/details/gtmkqxuwbp.html

[S53] C++：移动语义
来源：http://dali.316326.xyz/Article/details/gtjvlraqlt.html

std::vector<int> w = std::move(v);
来源：http://dali.hfpthk.cn/Article/details/gtyamhbfci.html

[S54] C++：异常处理
来源：http://dali.yongpay.top/Article/details/gtfexmutyn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.redwolf501.top/Article/details/gtzfzrticx.html

[S55] C++：结构化绑定
来源：http://dali.yanxiufei.cn/Article/details/gtvpnpokeo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj20258888.top/Article/details/gtjgrkuooa.html

[S56] C++：optional
来源：http://dali.havefunace.top/Article/details/gtbrhruaal.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.wangshuangyany.cn/Article/details/gtxyonlwnq.html

[S57] C++：编译期常量
来源：http://dali.hfpthk.cn/Article/details/gtijmfatuz.html

constexpr int N = 10;
来源：http://dali.sufxvd.cn/Article/details/gtaopqowia.html

[S58] C++：命名空间
来源：http://dali.pengpengdd.cyou/Article/details/gtduytgmjx.html

namespace ns { int f() { return 1; } }
来源：http://dali.tian-w.cn/Article/details/gtgcmlhhlt.html

[S59] C++：静态断言
来源：http://dali.zycfv.cn/Article/details/gtzkvhsoqr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.daria6918.cn/Article/details/gtcwjreroa.html

[S60] C++：遍历并删除元素
来源：http://dali.pengpengdd.cyou/Article/details/gttqiejdha.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.dianchejie.cn/Article/details/gtjtibzeyw.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtzvbnyssk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xziqi.cn/Article/details/gtyaatrkmm.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtmcbvwubc.html

[T01] Kotlin：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtuxxbzczv.html

println("Hello")
来源：http://dali.redwolf501.top/Article/details/gtzvtndcak.html

[T02] Kotlin：变量
来源：http://dali.jiagoushi.top/Article/details/gtdbgrmbgg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hammf.cn/Article/details/gtppwvxylf.html

[T03] Kotlin：字符串模板
来源：http://dali.ehwqpu.com/Article/details/gtlstbxfyx.html

"值: $b"
来源：http://dali.shuidangran.top/Article/details/gtlynkwsij.html

[T04] Kotlin：空安全
来源：http://dali.aibaodan.cn/Article/details/gtrvbmbdff.html

val n: String? = null;  n?.length
来源：http://dali.pengpengdd.cyou/Article/details/gtxalhkxrl.html

[T05] Kotlin：when 表达式
来源：http://dali.redwolf501.top/Article/details/gtqehnrvho.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ppjwa.cn/Article/details/gtxunnlwus.html

[T06] Kotlin：集合映射
来源：http://dali.daxiang520.top/Article/details/gtsviqddbi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtiencpjxi.html

[T07] Kotlin：集合过滤
来源：http://dali.meibo888.top/Article/details/gtctlseajd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jqgufenzy.top/Article/details/gtrheipidk.html

[T08] Kotlin：数据类
来源：http://dali.xuanzx.com/Article/details/gtpihpruil.html

data class User(val name: String, val age: Int)
来源：http://dali.wangshuangyany.cn/Article/details/gttwtifvpw.html

[T09] Kotlin：扩展函数
来源：http://dali.tanke756.top/Article/details/gtioxllsxe.html

fun String.exclaim() = this + "!"
来源：http://dali.xuetiantiany.cn/Article/details/gtdjbgajwv.html

[T10] Kotlin：默认参数
来源：http://dali.daxiang520.top/Article/details/gtskveiclf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhiwuduotai.top/Article/details/gtugdyksaj.html

[T11] Kotlin：协程
来源：http://dali.smart0.xyz/Article/details/gthjnfezdg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yanxiufei.cn/Article/details/gtjwvophsb.html

[T12] Kotlin：解构声明
来源：http://dali.9152youxi.cn/Article/details/gtqfmqycln.html

val (a, b) = Pair(1, 2)
来源：http://dali.ppjwa.cn/Article/details/gthdyovaul.html

[T13] Kotlin：只读 Map
来源：http://dali.jqgufenzy.top/Article/details/gtyzfxolto.html

val m = mapOf("a" to 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtppbvobfu.html

[T14] Kotlin：循环
来源：http://dali.yvedp.cn/Article/details/gtqlcynpfo.html

for (i in 1..10) println(i)
来源：http://dali.hfpthk.cn/Article/details/gtfkfuefuy.html

[T15] Kotlin：接口
来源：http://dali.xuetiantiany.cn/Article/details/gtckynpuco.html

interface Shape { fun area(): Double }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjxxfdnd.html

[T16] Swift：Hello World
来源：http://dali.havefunace.top/Article/details/gtbxugbxgq.html

print("Hello")
来源：http://dali.sufxvd.cn/Article/details/gtgiibkbke.html

[T17] Swift：变量与常量
来源：http://dali.sxryk.cn/Article/details/gtgupkvlmm.html

var a = 1;  let b = 2
来源：http://dali.chenjidiqi.icu/Article/details/gtjyyotsjy.html

[T18] Swift：字符串插值
来源：http://dali.fzhhl.top/Article/details/gtcvunteoh.html

"值: \(b)"
来源：http://dali.aizwys.cn/Article/details/gtvqapzlcu.html

[T19] Swift：可选绑定
来源：http://dali.aibaodan.cn/Article/details/gtthhqtqrf.html

if let n = opt { print(n) }
来源：http://dali.nanxuanxn.top/Article/details/gtfnjyleal.html

[T20] Swift：数组操作
来源：http://dali.xziqi.cn/Article/details/gtlwtkghfb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jinqigufen.top/Article/details/gtpjgnglpb.html

[T21] Swift：遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtzpzrmzpg.html

for x in a { print(x) }
来源：http://dali.vqdsnc.cn/Article/details/gtvdjfueaw.html

[T22] Swift：字典
来源：http://dali.zhoulong.xyz/Article/details/gtkhroqxjf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yongpay.top/Article/details/gtkegbbvev.html

[T23] Swift：函数
来源：http://dali.wangdashe.top/Article/details/gtpqqppcvy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.9152youxi.cn/Article/details/gtvcqepbsj.html

[T24] Swift：闭包
来源：http://dali.redwolf501.top/Article/details/gtplvyzmxs.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cqqwz.cn/Article/details/gtbbwmjzxb.html

[T25] Swift：结构体
来源：http://dali.snrcjt.cn/Article/details/gtibtcnaux.html

struct P { var x: Int }
来源：http://dali.gogol.net.cn/Article/details/gtijafnjra.html

[T26] Swift：类与重写
来源：http://dali.tianlin.xyz/Article/details/gtdvbkpqvq.html

class A: Base { override func f() {} }
来源：http://dali.nwbrower.top/Article/details/gtdyhzdivv.html

[T27] Swift：错误处理
来源：http://dali.cqqwz.cn/Article/details/gtcocnnszj.html

do { try f() } catch { print(error) }
来源：http://dali.daxiang520.top/Article/details/gtluqsnkts.html

[T28] Swift：枚举
来源：http://dali.zhengqikj.top/Article/details/gtxpquvxgc.html

enum Color { case red, green }
来源：http://dali.birdmap.top/Article/details/gtsryhadgf.html

[T29] Swift：guard 提前返回
来源：http://dali.havefunace.top/Article/details/gtpdlbcguv.html

guard let x = opt else { return }
来源：http://dali.jinqigfzy.top/Article/details/gtwpprbizr.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gtnjuxzpry.html

protocol Shape { func area() -> Double }
来源：http://dali.quarkkingdee.top/Article/details/gtovwmxzjl.html

[T31] Lua：Hello World
来源：http://dali.tianlin.xyz/Article/details/gthggqgago.html

print("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjeqrrljp.html

[T32] Lua：局部变量
来源：http://dali.gogol.net.cn/Article/details/gtlhrwonla.html

local a = 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtsrsgokas.html

[T33] Lua：表（数组）
来源：http://dali.yuanzhike.top/Article/details/gtayldyhsg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinqigufen.top/Article/details/gtvcycpspd.html

[T34] Lua：遍历表
来源：http://dali.yuxming.cn/Article/details/gtserslqdy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sysykeji.top/Article/details/gtessefpzn.html

[T35] Lua：字典表
来源：http://dali.fengsongda.top/Article/details/gtftwpgqrb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tianlin.xyz/Article/details/gtvdcajmvq.html

[T36] Lua：函数
来源：http://dali.zhoulong.xyz/Article/details/gteqjmsrkb.html

function add(a, b) return a + b end
来源：http://dali.zhongyouzk.top/Article/details/gtmhqfushs.html

[T37] Lua：字符串拼接
来源：http://dali.jiagoushi.top/Article/details/gtwriodvbp.html

"a" .. "b"
来源：http://dali.hysaishi.cn/Article/details/gtvyguqvat.html

[T38] Lua：条件
来源：http://dali.xziqi.cn/Article/details/gtlqbtswer.html

if x > 0 then print("正") end
来源：http://dali.xinyue.icu/Article/details/gtxdbjsses.html


<!-- 参考信息 -->