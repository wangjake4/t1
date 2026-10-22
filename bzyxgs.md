代发 wailian999

files=$(ls -1)
来源：http://dali.xziqi.cn/Article/details/gtwqszonhu.html

[R38] 管道串联
来源：http://dali.yongpay.top/Article/details/gtrbxnfieo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrovvglst.html

[R39] 重定向标准输出与错误
来源：http://dali.zhiwuduotai.top/Article/details/gtguxpajzu.html

cmd > out.log 2>&1
来源：http://dali.hongshengwenyu.top/Article/details/gtmbyhgcjv.html

[R40] 追加写日志
来源：http://dali.ydzc1.top/Article/details/gtvcbnnpmn.html

echo "log" >> out.log
来源：http://dali.9152youxi.cn/Article/details/gthcvpupgl.html

[R41] 丢弃输出
来源：http://dali.gaohongyu789.top/Article/details/gthfoxkzfo.html

cmd >/dev/null 2>&1
来源：http://dali.daxiang520.top/Article/details/gtgifgwvfr.html

[R42] 输入重定向
来源：http://dali.snrcjt.cn/Article/details/gtetkesksm.html

wc -l < a.txt
来源：http://dali.svipenyu.cn/Article/details/gtotsmdtex.html

[R43] 按名字查找文件
来源：http://dali.vqdsnc.cn/Article/details/gtkmskhcwh.html

find . -name "*.log" -type f
来源：http://dali.smart0.xyz/Article/details/gtmetvdqdl.html

[R44] 按修改时间查找
来源：http://dali.cashguo.top/Article/details/gtyjmahfmh.html

find . -mtime -7 -type f
来源：http://dali.vqdsnc.cn/Article/details/gtmzecpivk.html

[R45] 批量删除
来源：http://dali.aizwys.cn/Article/details/gtlnedfmwb.html

find . -name "*.tmp" -delete
来源：http://dali.zhoulong.xyz/Article/details/gtxncugrmy.html

[R46] 递归替换文件内容
来源：http://dali.hammf.cn/Article/details/gtuayensqk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.316326.xyz/Article/details/gtzzzqebzf.html

[R47] sed 单行替换
来源：http://dali.ydzc1.top/Article/details/gtiimmtrez.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hammf.cn/Article/details/gtlqdxldyc.html

[R48] awk 取指定列
来源：http://dali.snrcjt.cn/Article/details/gttscclauf.html

awk '{print $1, $3}' a.txt
来源：http://dali.meibo888.top/Article/details/gtpxmzcmlg.html

[R49] awk 带条件
来源：http://dali.yueranfly.top/Article/details/gtmmuoxfyu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shanyushiyangtech.top/Article/details/gtiqyqyxmv.html

[R50] awk 求和
来源：http://dali.cheryme.top/Article/details/gtcyvcblvr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ivvv.top/Article/details/gtjqccmzzx.html

[R51] 排序去重取前几
来源：http://dali.nanxinkj.top/Article/details/gttddwygyn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinyuanbaomall.cn/Article/details/gteqmhjbdo.html

[R52] 统计行数
来源：http://dali.redwolf501.top/Article/details/gtlbcsjcoc.html

wc -l a.txt
来源：http://dali.jianghu66.top/Article/details/gtnmpsxoub.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gttairvixz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jqgufenzy.top/Article/details/gtwlklerhk.html

[R54] 比较两个文件
来源：http://dali.pycfn.com/Article/details/gtrgrwfcxc.html

diff a.txt b.txt
来源：http://dali.dianchejie.cn/Article/details/gtbccolytt.html

[R55] 压缩与解压
来源：http://dali.chenzaomai.com/Article/details/gtmtqgsdft.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xinyue.icu/Article/details/gtxqfhheyn.html

[R56] 远程拷贝
来源：http://dali.cucudq.cn/Article/details/gtmcydzslg.html

scp file user@host:/path/
来源：http://dali.dashuyun.cn/Article/details/gtddehpqvu.html

[R57] 远程执行命令
来源：http://dali.zhixingplan.top/Article/details/gtqnyouehv.html

ssh user@host 'uptime'
来源：http://dali.quarkkingdee.top/Article/details/gtnkuronpb.html

[R58] 下载文件
来源：http://dali.c1oappe.top/Article/details/gthwnbgplx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinqigufen.top/Article/details/gtgfppdbxc.html

[R59] 发 POST JSON
来源：http://dali.pycfn.com/Article/details/gtgkpzrqrn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.svipenyu.cn/Article/details/gtfpaycvcx.html

[R60] 只看 HTTP 状态码
来源：http://dali.0kj1m.cn/Article/details/gtaicmfalv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hongshengwenyu.top/Article/details/gtnhrobwio.html

[R61] 磁盘占用
来源：http://dali.jqgfzy.top/Article/details/gtrgyhipdi.html

df -h;  du -sh *
来源：http://dali.nanxinkj.top/Article/details/gtqseofxmm.html

[R62] 找最占空间的文件
来源：http://dali.daxiang520.top/Article/details/gtvjnwulft.html

du -ah . | sort -rh | head -10
来源：http://dali.shzxlz.cn/Article/details/gtkrxciyva.html

[R63] 内存与进程
来源：http://dali.daxiang520.top/Article/details/gtfbrnjexg.html

free -h;  ps aux | grep nginx
来源：http://dali.redwolf501.top/Article/details/gtbqqijowm.html

[R64] 结束进程
来源：http://dali.ybcxt.top/Article/details/gtshyhzzhu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.pycfn.com/Article/details/gtwpqpyvww.html

[R65] 查看端口占用
来源：http://dali.smart0.xyz/Article/details/gtfpgcsuys.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.316326.xyz/Article/details/gtrjijzifj.html

[R66] 定时任务
来源：http://dali.pycfn.com/Article/details/gtzxutfzym.html

crontab -e;  crontab -l
来源：http://dali.quarkkingdee.top/Article/details/gtkqjcqxss.html

[R67] 生成随机十六进制串
来源：http://dali.cqqwz.cn/Article/details/gtmqzxvcai.html

openssl rand -hex 16
来源：http://dali.yueranfly.top/Article/details/gtukbxznot.html

[R68] 计算文件校验值
来源：http://dali.yj202588.top/Article/details/gtguagjciy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.mhx1999.top/Article/details/gtvttqkidk.html

[R69] 生成随机密码
来源：http://dali.smart0.xyz/Article/details/gttgcoifzr.html

head -c 16 /dev/urandom | base64
来源：http://dali.daxiang520.top/Article/details/gtoqqyxwcr.html

[R70] 时间戳与互转
来源：http://dali.xylfe.cn/Article/details/gthkylvhcw.html

date +%s;  date -d @1700000000
来源：http://dali.ydzc1.top/Article/details/gtyicvgxhy.html

[R71] 日期格式化
来源：http://dali.xuanzx.com/Article/details/gttjvulvuk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtasxfrjua.html

[R72] 等待端口就绪
来源：http://dali.nwbrower.top/Article/details/gtyjkwrjrn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ydzc1.top/Article/details/gttpbtmntb.html

[R73] 分割大日志
来源：http://dali.hongshengwenyu.top/Article/details/gtvnwinwxg.html

split -l 1000 big.log part_
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrhnsthcp.html

[R74] 批量重命名
来源：http://dali.c1oappe.top/Article/details/gtelszfyny.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yuanzhike.top/Article/details/gturvpceeo.html

[R75] 导出环境变量
来源：http://dali.wangdashe.top/Article/details/gtdaoljiei.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hnxiangtu.top/Article/details/gtwvmnxsxy.html

[R76] 使用临时文件
来源：http://dali.chenzaomai.com/Article/details/gtjjcviqzb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.fengsongda.top/Article/details/gtwqhayykx.html

[R77] 读取用户输入
来源：http://dali.andypj.xyz/Article/details/gtampqpjmd.html

read -rp "请输入: " ans
来源：http://dali.hfpthk.cn/Article/details/gtfxaxvpuo.html

[R78] 交互式菜单
来源：http://dali.cashguo.top/Article/details/gtdmebydvi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yueranfly.top/Article/details/gttlohhimb.html

[R79] 解析命令行选项
来源：http://dali.xziqi.cn/Article/details/gttbaskawq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.snrcjt.cn/Article/details/gtgfytgvye.html

[R80] 查看脚本执行耗时
来源：http://dali.shuidangran.top/Article/details/gtudrunowd.html

time ./run.sh
来源：http://dali.gzhubu.top/Article/details/gtxvkjromj.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtymlhxbfe.html

S. C / C++ 专题
来源：http://dali.haohaochexian.top/Article/details/gtopznqdbc.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtlmkbmnih.html

[S01] C：Hello World
来源：http://dali.yueranfly.top/Article/details/gtbvwzhxge.html

#include <stdio.h>
来源：http://dali.nanxinkj.top/Article/details/gtbjehuwse.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.dianchejie.cn/Article/details/gtttivmcjn.html

[S02] C：变量与格式化输出
来源：http://dali.vqdsnc.cn/Article/details/gtxndqfcvj.html

int a = 10; printf("%d\n", a);
来源：http://dali.9152youxi.cn/Article/details/gtuejtaamk.html

[S03] C：读入整数
来源：http://dali.jianghu66.top/Article/details/gtmaveyeqs.html

int x; scanf("%d", &x);
来源：http://dali.gotoacloud.top/Article/details/gtdgqbluxa.html

[S04] C：字符串复制
来源：http://dali.shangyingyoupin.top/Article/details/gtjyehzqso.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.guowangkeji.top/Article/details/gtiplxbzwa.html

[S05] C：字符串长度
来源：http://dali.fengsongda.top/Article/details/gthikjlxpp.html

strlen(s)
来源：http://dali.jyoumei.cn/Article/details/gtqmazwqvw.html

[S06] C：字符串比较
来源：http://dali.dashuyun.cn/Article/details/gteycmousk.html

strcmp(a, b) == 0
来源：http://dali.aizwys.cn/Article/details/gtxpnowtea.html

[S07] C：数组遍历求和
来源：http://dali.ivvv.top/Article/details/gtnfalzsdi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.wangdashe.top/Article/details/gtugllyrkj.html

[S08] C：动态内存分配与释放
来源：http://dali.hfpthk.cn/Article/details/gtcdwnozkp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aibaodan.cn/Article/details/gtjruxeihs.html

[S09] C：结构体定义与初始化
来源：http://dali.316326.xyz/Article/details/gtczprxmnv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.meibo888.top/Article/details/gtekxjsmuc.html

[S10] C：指针与解引用
来源：http://dali.xuanzx.com/Article/details/gtebtntpaj.html

int *p = &a;  *p = 5;
来源：http://dali.jinqigufen.top/Article/details/gtzsazznsk.html

[S11] C：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtnttbqitt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yanxiufei.cn/Article/details/gtgyouapwg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.pycfn.com/Article/details/gtwditaztm.html

fclose(f);
来源：http://dali.shangyingyoupin.top/Article/details/gtryzmtysm.html

[S12] C：写文件
来源：http://dali.sufxvd.cn/Article/details/gtqbjsurip.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.andypj.xyz/Article/details/gtltscytqk.html

[S13] C：宏定义
来源：http://dali.havefunace.top/Article/details/gtvfuhorph.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yuanzhike.top/Article/details/gtrjdqyzcr.html

[S14] C：枚举
来源：http://dali.ivvv.top/Article/details/gtqhofrqsi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tanke756.top/Article/details/gtgcalqvdk.html

[S15] C：类型转换
来源：http://dali.yonumen.top/Article/details/gtrkurdxrs.html

(double) a / b
来源：http://dali.sweek.top/Article/details/gtpviwcifm.html

[S16] C：位操作置位
来源：http://dali.andypj.xyz/Article/details/gtnytoapll.html

x |= (1 << 3);
来源：http://dali.svipenyu.cn/Article/details/gtrsvxsofq.html

[S17] C：安全拼接字符串
来源：http://dali.gzhubu.top/Article/details/gtevbckwjk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.svipenyu.cn/Article/details/gtimymujac.html

[S18] C：命令行参数
来源：http://dali.wangdashe.top/Article/details/gtiwtbjzpi.html

int main(int argc, char **argv)
来源：http://dali.hywenlv.cn/Article/details/gtcvpubnby.html

[S19] C：快速排序
来源：http://dali.zhengqikj.top/Article/details/gtyymuuedp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.aizwys.cn/Article/details/gtkcdhwpfh.html

[S20] C：二分查找
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfavqilw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sxryk.cn/Article/details/gtfkoqsmhe.html

[S21] C：字符类别判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmabyngyw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpkpvckwq.html

[S22] C：字符串转数字
来源：http://dali.shanyushiyangtech.top/Article/details/gtbhwpsfrv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhongyouzk.top/Article/details/gtsaimrnev.html

[S23] C：随机数
来源：http://dali.yj20258888.top/Article/details/gtcbaycxco.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jlsjyb.cn/Article/details/gtxuowtjxc.html

[S24] C：获取本地时间
来源：http://dali.shzxlz.cn/Article/details/gthynnsbot.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.birdmap.top/Article/details/gtbeuuprcj.html

[S25] C：内存拷贝
来源：http://dali.cdnleiting.top/Article/details/gtfvwedzmt.html

memcpy(dst, src, n);
来源：http://dali.sufxvd.cn/Article/details/gtdjhhisam.html

[S26] C：内存清零
来源：http://dali.nwbrower.top/Article/details/gttitpavhh.html

memset(a, 0, sizeof a);
来源：http://dali.xziqi.cn/Article/details/gtjhjchyvb.html

[S27] C：定义常量
来源：http://dali.shzxlz.cn/Article/details/gtewwudkyi.html

const double PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gtnyxbpwul.html

[S28] C：静态变量
来源：http://dali.zhengqikj.top/Article/details/gthgdbiuom.html

static int counter = 0;
来源：http://dali.shanyushiyangtech.top/Article/details/gtttkmweyc.html

[S29] C：变参函数
来源：http://dali.svipenyu.cn/Article/details/gtierrfqxm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jiagoushi.top/Article/details/gtanmoetom.html

[S30] C：头文件保护
来源：http://dali.aizwys.cn/Article/details/gtiyegldxc.html

#ifndef X_H
来源：http://dali.0kj1m.cn/Article/details/gtgmgeuwsn.html

#define X_H
来源：http://dali.bjfxy.top/Article/details/gtlmutqlzg.html

#endif
来源：http://dali.jinghuilouyu.cn/Article/details/gtypiweept.html

[S31] C++：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtalijpsfj.html

#include <iostream>
来源：http://dali.xuanzx.com/Article/details/gtkggazkba.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.svipenyu.cn/Article/details/gtbvegvxgp.html

[S32] C++：字符串
来源：http://dali.ppjwa.cn/Article/details/gtoabfnyky.html

std::string s = "hi";  s += "!";
来源：http://dali.hammf.cn/Article/details/gtknsnkxtu.html

[S33] C++：vector 增删
来源：http://dali.wangshuangyany.cn/Article/details/gtpjktbkjp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cheryme.top/Article/details/gtrradpqng.html

[S34] C++：遍历 vector
来源：http://dali.yj20258888.top/Article/details/gthfuzrfuj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gzhubu.top/Article/details/gtlycfzgux.html

[S35] C++：map
来源：http://dali.daxiang520.top/Article/details/gtqbfyibgq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shuidangran.top/Article/details/gtawfjrzlz.html

[S36] C++：unordered_map
来源：http://dali.jyoumei.cn/Article/details/gtjzcgclfd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuxming.cn/Article/details/gtrifzeqjp.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gtgtgkkfht.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nanxinkj.top/Article/details/gtyqugwwiy.html

[S38] C++：排序
来源：http://dali.hammf.cn/Article/details/gtjjgghfkt.html

std::sort(v.begin(), v.end());
来源：http://dali.sufxvd.cn/Article/details/gtvyoucnfa.html

[S39] C++：自定义比较器排序
来源：http://dali.pengpengdd.cyou/Article/details/gttdstuuet.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nwbrower.top/Article/details/gtogvsusss.html

[S40] C++：查找元素
来源：http://dali.chenlongwang.top/Article/details/gthcixsjcd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hywenlv.cn/Article/details/gtyhzhxmcd.html

[S41] C++：类与构造函数
来源：http://dali.aibaodan.cn/Article/details/gtwsdjqcod.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jianghu66.top/Article/details/gtvtcfppzm.html

[S42] C++：继承与虚函数
来源：http://dali.cheryme.top/Article/details/gtludpfeih.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhixingplan.top/Article/details/gtfrqrrqna.html

[S43] C++：智能指针
来源：http://dali.gzhubu.top/Article/details/gtjpcrekce.html

auto p = std::make_unique<int>(5);
来源：http://dali.kuanghao11.cn/Article/details/gtlfqtdftt.html

[S44] C++：引用传参
来源：http://dali.ydzc1.top/Article/details/gtsotoslal.html

void inc(int &x) { ++x; }
来源：http://dali.hongshengwenyu.top/Article/details/gtokmltslv.html

[S45] C++：lambda
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrhvsmegy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.guannengcc.top/Article/details/gtgpwwugmj.html

[S46] C++：函数模板
来源：http://dali.xylfe.cn/Article/details/gtcvrqhria.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkchzmgxy.html

[S47] C++：结构化绑定遍历
来源：http://dali.bjfxy.top/Article/details/gtvzaqfpvs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ehwqpu.com/Article/details/gtxlgujpbd.html

[S48] C++：逐行读文件
来源：http://dali.ydzc1.top/Article/details/gtqueqjbqt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ehwqpu.com/Article/details/gtmqklumzr.html

while (std::getline(in, line)) { }
来源：http://dali.cheryme.top/Article/details/gtqrgfdspv.html

[S49] C++：写文件
来源：http://dali.xziqi.cn/Article/details/gtgacksvim.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.daria6918.cn/Article/details/gtodyhxxob.html

[S50] C++：格式化数字
来源：http://dali.nwbrower.top/Article/details/gthukilgec.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nwbrower.top/Article/details/gtyyjsxsxa.html

[S51] C++：显式类型转换
来源：http://dali.jyoumei.cn/Article/details/gtvfwuzlqv.html

static_cast<double>(a) / b
来源：http://dali.hysaishi.cn/Article/details/gtrureayeo.html

[S52] C++：const 与 noexcept
来源：http://dali.yongpay.top/Article/details/gtlinptuhp.html

int size() const noexcept { return n_; }
来源：http://dali.yj202588.top/Article/details/gtxpewvnuy.html

[S53] C++：移动语义
来源：http://dali.meibo888.top/Article/details/gtonwymian.html

std::vector<int> w = std::move(v);
来源：http://dali.birdmap.top/Article/details/gtyefvyenq.html

[S54] C++：异常处理
来源：http://dali.smart0.xyz/Article/details/gtvtwsqaka.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gtlhvxgegc.html

[S55] C++：结构化绑定
来源：http://dali.pengpengdd.cyou/Article/details/gtiihmvgtm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xuetiantiany.cn/Article/details/gttbdeqdjq.html

[S56] C++：optional
来源：http://dali.quarkkingdee.top/Article/details/gtzqgqfvkx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xziqi.cn/Article/details/gtgljxsqkt.html

[S57] C++：编译期常量
来源：http://dali.jlsjyb.cn/Article/details/gttefnctcz.html

constexpr int N = 10;
来源：http://dali.svipenyu.cn/Article/details/gttcdxvlnh.html

[S58] C++：命名空间
来源：http://dali.cucudq.cn/Article/details/gtuyiffqjk.html

namespace ns { int f() { return 1; } }
来源：http://dali.hnxiangtu.top/Article/details/gtlnvphshr.html

[S59] C++：静态断言
来源：http://dali.hnqzz.top/Article/details/gtfmsdwiwe.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jqgufenzy.top/Article/details/gtvmrhyvtn.html

[S60] C++：遍历并删除元素
来源：http://dali.jqgfzy.top/Article/details/gtrvtbxzoc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yongpay.top/Article/details/gtuofnsksy.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtxxzsrcpn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yueranfly.top/Article/details/gtjxtkoaxg.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtxldfgzfs.html

[T01] Kotlin：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtdptahraq.html

println("Hello")
来源：http://dali.meibo888.top/Article/details/gtmkwizvhp.html

[T02] Kotlin：变量
来源：http://dali.guowangkeji.top/Article/details/gtbgsbrjlr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yuxming.cn/Article/details/gtdcmuyxfv.html

[T03] Kotlin：字符串模板
来源：http://dali.hnqzz.top/Article/details/gtrewrlcvc.html

"值: $b"
来源：http://dali.316326.xyz/Article/details/gtjcrzmznn.html

[T04] Kotlin：空安全
来源：http://dali.kuanghao11.cn/Article/details/gttcejtetq.html

val n: String? = null;  n?.length
来源：http://dali.snrcjt.cn/Article/details/gtwbvmkzbj.html

[T05] Kotlin：when 表达式
来源：http://dali.hammf.cn/Article/details/gtsccgahxc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hammf.cn/Article/details/gtzuyavnko.html

[T06] Kotlin：集合映射
来源：http://dali.cucudq.cn/Article/details/gtpaxjedkr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtshlcljyu.html

[T07] Kotlin：集合过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrrrtmups.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tian-w.cn/Article/details/gtzeockrap.html

[T08] Kotlin：数据类
来源：http://dali.dashuyun.cn/Article/details/gthlyjybrv.html

data class User(val name: String, val age: Int)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtldalrsde.html

[T09] Kotlin：扩展函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcpyjvbpk.html

fun String.exclaim() = this + "!"
来源：http://dali.ppjwa.cn/Article/details/gtmhhztyls.html

[T10] Kotlin：默认参数
来源：http://dali.haohaochexian.top/Article/details/gtospefnxp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hammf.cn/Article/details/gtptrsyrti.html

[T11] Kotlin：协程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfqzgyzom.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.bjfxy.top/Article/details/gtnxaheigb.html

[T12] Kotlin：解构声明
来源：http://dali.hnqzz.top/Article/details/gtepllnlty.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtziuaezom.html

[T13] Kotlin：只读 Map
来源：http://dali.cheryme.top/Article/details/gtnkeukmfd.html

val m = mapOf("a" to 1)
来源：http://dali.yj20258.top/Article/details/gtetbtbsnl.html

[T14] Kotlin：循环
来源：http://dali.yuxming.cn/Article/details/gtnzfoerbt.html

for (i in 1..10) println(i)
来源：http://dali.iojbl.cn/Article/details/gtechttuoo.html

[T15] Kotlin：接口
来源：http://dali.tian-w.cn/Article/details/gtaqnlbmry.html

interface Shape { fun area(): Double }
来源：http://dali.jqgufenzy.top/Article/details/gtflwqjzow.html

[T16] Swift：Hello World
来源：http://dali.yongpay.top/Article/details/gtvvchxrys.html

print("Hello")
来源：http://dali.hywenlv.cn/Article/details/gtqntenjjd.html

[T17] Swift：变量与常量
来源：http://dali.hysaishi.cn/Article/details/gtjmcpinyd.html

var a = 1;  let b = 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmnkgsuii.html

[T18] Swift：字符串插值
来源：http://dali.haohaochexian.top/Article/details/gtgpudohyh.html

"值: \(b)"
来源：http://dali.yj20258888.top/Article/details/gtgtyxesug.html

[T19] Swift：可选绑定
来源：http://dali.yueranfly.top/Article/details/gtsfdumtfb.html

if let n = opt { print(n) }
来源：http://dali.svipenyu.cn/Article/details/gtmrymxdfi.html

[T20] Swift：数组操作
来源：http://dali.cucudq.cn/Article/details/gtcweyalwm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yvedp.cn/Article/details/gtbdaqjwsk.html

[T21] Swift：遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtcfzaojpc.html

for x in a { print(x) }
来源：http://dali.ybcxt.top/Article/details/gtjllxtftl.html

[T22] Swift：字典
来源：http://dali.yongpay.top/Article/details/gtvnwegyml.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.chenlongwang.top/Article/details/gtxsmyeqjg.html

[T23] Swift：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtktqkzhjw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hnqzz.top/Article/details/gtydyeuhex.html

[T24] Swift：闭包
来源：http://dali.kuanghao11.cn/Article/details/gtqgmowrhs.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yonumen.top/Article/details/gtfgavricc.html

[T25] Swift：结构体
来源：http://dali.sufxvd.cn/Article/details/gtguatlbdc.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gtvipnrmvb.html

[T26] Swift：类与重写
来源：http://dali.cqqwz.cn/Article/details/gtgykeaqgc.html

class A: Base { override func f() {} }
来源：http://dali.jqgufenzy.top/Article/details/gtbjlxgcoz.html

[T27] Swift：错误处理
来源：http://dali.birdmap.top/Article/details/gtalgzuoye.html

do { try f() } catch { print(error) }
来源：http://dali.smart0.xyz/Article/details/gtxairlmlh.html

[T28] Swift：枚举
来源：http://dali.yj20258888.top/Article/details/gthisjtsrg.html

enum Color { case red, green }
来源：http://dali.sufxvd.cn/Article/details/gtnaxbsfbh.html

[T29] Swift：guard 提前返回
来源：http://dali.cqqwz.cn/Article/details/gtziyubzpn.html

guard let x = opt else { return }
来源：http://dali.hammf.cn/Article/details/gtztcxrrra.html

[T30] Swift：协议
来源：http://dali.jiagoushi.top/Article/details/gtqplfopet.html

protocol Shape { func area() -> Double }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxyynxzjy.html

[T31] Lua：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gttljcrccj.html

print("Hello")
来源：http://dali.hammf.cn/Article/details/gttglbxuwb.html

[T32] Lua：局部变量
来源：http://dali.jiagoushi.top/Article/details/gtbfzwmqfs.html

local a = 1
来源：http://dali.xylfe.cn/Article/details/gteapmxrys.html

[T33] Lua：表（数组）
来源：http://dali.jlsjyb.cn/Article/details/gtkrzssvrz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ydzc1.top/Article/details/gtgflzlyti.html

[T34] Lua：遍历表
来源：http://dali.xuetiantiany.cn/Article/details/gtzthijtpg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yuxming.cn/Article/details/gtvmcopsgt.html

[T35] Lua：字典表
来源：http://dali.redwolf501.top/Article/details/gtsxqlyysa.html

local d = { a = 1 };  d.b = 2
来源：http://dali.chenlongwang.top/Article/details/gtieqzkdxa.html

[T36] Lua：函数
来源：http://dali.9152youxi.cn/Article/details/gtzehsokbw.html

function add(a, b) return a + b end
来源：http://dali.zhongyouzk.top/Article/details/gtxajvxpbf.html

[T37] Lua：字符串拼接
来源：http://dali.ehwqpu.com/Article/details/gtjevlmvbr.html

"a" .. "b"
来源：http://dali.316326.xyz/Article/details/gtzvblqzaw.html

[T38] Lua：条件
来源：http://dali.havefunace.top/Article/details/gtuhsnvyxl.html

if x > 0 then print("正") end
来源：http://dali.wangshuangyany.cn/Article/details/gtyowqhtxf.html

[T39] Lua：模式匹配
来源：http://dali.sxryk.cn/Article/details/gtahmpdhbj.html

string.find(s, "%d+")
来源：http://dali.zycfv.cn/Article/details/gtvrnfvptc.html

[T40] Lua：元表
来源：http://dali.cucudq.cn/Article/details/gtbnbvaihg.html

setmetatable({}, { __index = base })
来源：http://dali.cheryme.top/Article/details/gtvrtrejfi.html


<!-- 参考信息 -->